Solus - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Solus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Solus/Desktop/README.md) and [notebooks](/Dist/Solus/Notebook/README.md).

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

Total: 236

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | B85M-E                      | Desktop     | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [9f5778e082](https://linux-hardware.org/?probe=9f5778e082) | Apr 11, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown       | HX90                        | Desktop     | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown       | HX90                        | Desktop     | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown       | HX90                        | Desktop     | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [28c8bc52b8](https://linux-hardware.org/?probe=28c8bc52b8) | Mar 22, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | Notebook    | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| Sony          | VPCYB15AB                   | Notebook    | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Dell          | Latitude 5580               | Notebook    | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| Framework     | Laptop                      | Notebook    | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| Dell          | Latitude E6220              | Notebook    | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| Framework     | Laptop                      | Notebook    | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| HP            | 805F                        | Desktop     | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda    | Alpha                       | Desktop     | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar       | H61MLV2                     | Desktop     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| AZW           | SEi                         | Notebook    | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [49cd3453c7](https://linux-hardware.org/?probe=49cd3453c7) | Aug 16, 2021 |
| eMachines     | EL1852G                     | Desktop     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines     | EL1852G                     | Desktop     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [14f7d2a3c6](https://linux-hardware.org/?probe=14f7d2a3c6) | Aug 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [488ebb20fc](https://linux-hardware.org/?probe=488ebb20fc) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| Lenovo        | Board                       | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [53fef6a61a](https://linux-hardware.org/?probe=53fef6a61a) | Jul 08, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [48cb73de41](https://linux-hardware.org/?probe=48cb73de41) | Jul 01, 2021 |
| Biostar       | A320MH                      | Desktop     | [2c478119e9](https://linux-hardware.org/?probe=2c478119e9) | Jun 30, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [6fc3976633](https://linux-hardware.org/?probe=6fc3976633) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [4fc48865ef](https://linux-hardware.org/?probe=4fc48865ef) | Jun 15, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [f5c8f64400](https://linux-hardware.org/?probe=f5c8f64400) | Jun 03, 2021 |
| Howard Com... | W350                        | Notebook    | [3e55c8284e](https://linux-hardware.org/?probe=3e55c8284e) | May 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [dfa5c022b3](https://linux-hardware.org/?probe=dfa5c022b3) | May 26, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [ce04df7bae](https://linux-hardware.org/?probe=ce04df7bae) | May 23, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [a33e231e6b](https://linux-hardware.org/?probe=a33e231e6b) | May 23, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e53c63ba89](https://linux-hardware.org/?probe=e53c63ba89) | May 19, 2021 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [f759ad1793](https://linux-hardware.org/?probe=f759ad1793) | May 13, 2021 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [f28f1ea67d](https://linux-hardware.org/?probe=f28f1ea67d) | May 13, 2021 |
| Intel         | X99 V102                    | Desktop     | [bc57aedd09](https://linux-hardware.org/?probe=bc57aedd09) | May 02, 2021 |
| Gigabyte      | AORUS 17G KB                | Notebook    | [fd9385ff3c](https://linux-hardware.org/?probe=fd9385ff3c) | Apr 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b5f3f78ddb](https://linux-hardware.org/?probe=b5f3f78ddb) | Apr 25, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [5c51b7f289](https://linux-hardware.org/?probe=5c51b7f289) | Apr 25, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | Notebook    | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| Dell          | 0FH884                      | Desktop     | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e8b5a1786b](https://linux-hardware.org/?probe=e8b5a1786b) | Apr 08, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [c7c0f7323d](https://linux-hardware.org/?probe=c7c0f7323d) | Mar 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [accdafb993](https://linux-hardware.org/?probe=accdafb993) | Mar 08, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f4e39d4730](https://linux-hardware.org/?probe=f4e39d4730) | Mar 04, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [e507a57307](https://linux-hardware.org/?probe=e507a57307) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f1c277189f](https://linux-hardware.org/?probe=f1c277189f) | Feb 16, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [d8b7b99dd0](https://linux-hardware.org/?probe=d8b7b99dd0) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [cdd0998f7c](https://linux-hardware.org/?probe=cdd0998f7c) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f4ee71d37f](https://linux-hardware.org/?probe=f4ee71d37f) | Feb 12, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [7a2993f67a](https://linux-hardware.org/?probe=7a2993f67a) | Feb 03, 2021 |
| Gigabyte      | H61M-HD2                    | Desktop     | [78c877458a](https://linux-hardware.org/?probe=78c877458a) | Jan 28, 2021 |
| Lenovo        | ThinkPad T410 2522Y1L       | Notebook    | [3c4543a94f](https://linux-hardware.org/?probe=3c4543a94f) | Jan 26, 2021 |
| Gigabyte      | H61M-HD2                    | Desktop     | [6caba093b5](https://linux-hardware.org/?probe=6caba093b5) | Jan 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd5bdfd31f](https://linux-hardware.org/?probe=bd5bdfd31f) | Jan 21, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [f8c2afa143](https://linux-hardware.org/?probe=f8c2afa143) | Jan 20, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [f69556d436](https://linux-hardware.org/?probe=f69556d436) | Jan 15, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [010be27c6a](https://linux-hardware.org/?probe=010be27c6a) | Jan 11, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [0083f37f14](https://linux-hardware.org/?probe=0083f37f14) | Jan 05, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [4db9c4da66](https://linux-hardware.org/?probe=4db9c4da66) | Jan 03, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [56d39c0f21](https://linux-hardware.org/?probe=56d39c0f21) | Jan 02, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [f2c8ec14c7](https://linux-hardware.org/?probe=f2c8ec14c7) | Jan 02, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [0173204c7f](https://linux-hardware.org/?probe=0173204c7f) | Dec 23, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [26447067ee](https://linux-hardware.org/?probe=26447067ee) | Dec 20, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [5f78418b58](https://linux-hardware.org/?probe=5f78418b58) | Dec 19, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [708eaf5602](https://linux-hardware.org/?probe=708eaf5602) | Dec 14, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [3d3a517e96](https://linux-hardware.org/?probe=3d3a517e96) | Dec 11, 2020 |
| Sony          | VPCEB1S1E                   | Notebook    | [ebcb16e616](https://linux-hardware.org/?probe=ebcb16e616) | Nov 27, 2020 |
| HP            | Elite Dragonfly             | Convertible | [ce851e2475](https://linux-hardware.org/?probe=ce851e2475) | Nov 25, 2020 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [cba289e868](https://linux-hardware.org/?probe=cba289e868) | Nov 22, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8e3d2a963b](https://linux-hardware.org/?probe=8e3d2a963b) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-A                | Desktop     | [c8f850e40f](https://linux-hardware.org/?probe=c8f850e40f) | Nov 15, 2020 |
| ASUSTek       | PRIME X370-A                | Desktop     | [c86804a559](https://linux-hardware.org/?probe=c86804a559) | Nov 14, 2020 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [3a3a530ac9](https://linux-hardware.org/?probe=3a3a530ac9) | Nov 08, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [cdd1a3be02](https://linux-hardware.org/?probe=cdd1a3be02) | Nov 07, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Timi          | TM1701                      | Notebook    | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [b21d4ca9d0](https://linux-hardware.org/?probe=b21d4ca9d0) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [eb1b0d459f](https://linux-hardware.org/?probe=eb1b0d459f) | Oct 25, 2020 |
| Toshiba       | PORTEGE Z20T-B              | Notebook    | [9d789eba3c](https://linux-hardware.org/?probe=9d789eba3c) | Oct 12, 2020 |
| Toshiba       | Satellite P50-A             | Notebook    | [884731a198](https://linux-hardware.org/?probe=884731a198) | Sep 28, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [80550be62d](https://linux-hardware.org/?probe=80550be62d) | Sep 28, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C5A... | Notebook    | [2f729ef2af](https://linux-hardware.org/?probe=2f729ef2af) | Sep 11, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [9968dc910c](https://linux-hardware.org/?probe=9968dc910c) | Sep 10, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [2ae445db73](https://linux-hardware.org/?probe=2ae445db73) | Sep 10, 2020 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [bcc44c581c](https://linux-hardware.org/?probe=bcc44c581c) | Sep 09, 2020 |
| Dell          | 0M017G A00                  | Desktop     | [e51b08ee63](https://linux-hardware.org/?probe=e51b08ee63) | Sep 08, 2020 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [5e2142357f](https://linux-hardware.org/?probe=5e2142357f) | Sep 08, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [e60be6cba2](https://linux-hardware.org/?probe=e60be6cba2) | Sep 06, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [b46a79f93e](https://linux-hardware.org/?probe=b46a79f93e) | Sep 03, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [4bf4f029df](https://linux-hardware.org/?probe=4bf4f029df) | Sep 03, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [aca54beb89](https://linux-hardware.org/?probe=aca54beb89) | Sep 02, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d150d7a9ea](https://linux-hardware.org/?probe=d150d7a9ea) | Sep 02, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [793085b89a](https://linux-hardware.org/?probe=793085b89a) | Aug 15, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| Pegatron      | IPM31G                      | Desktop     | [ed7c9fc9dc](https://linux-hardware.org/?probe=ed7c9fc9dc) | Jul 24, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fda411a3d7](https://linux-hardware.org/?probe=fda411a3d7) | Jul 24, 2020 |
| Avell High... | Avell G1750 MUV / C65 MU... | Notebook    | [cf035fee07](https://linux-hardware.org/?probe=cf035fee07) | Jul 24, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7744b749d9](https://linux-hardware.org/?probe=7744b749d9) | Jul 09, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| ASUSTek       | K45A                        | Notebook    | [57c5b7b4bd](https://linux-hardware.org/?probe=57c5b7b4bd) | Jun 08, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [6081e4a770](https://linux-hardware.org/?probe=6081e4a770) | Jun 07, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [5d852ecca8](https://linux-hardware.org/?probe=5d852ecca8) | Jun 06, 2020 |
| Acer          | Predator PH315-52           | Notebook    | [b5e7780315](https://linux-hardware.org/?probe=b5e7780315) | Jun 04, 2020 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [cb0fe570e2](https://linux-hardware.org/?probe=cb0fe570e2) | May 22, 2020 |
| Dell          | Latitude 7390               | Notebook    | [49112c8937](https://linux-hardware.org/?probe=49112c8937) | May 20, 2020 |
| HP            | ProBook 6470b               | Notebook    | [59db0f436f](https://linux-hardware.org/?probe=59db0f436f) | May 13, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [b3513301a1](https://linux-hardware.org/?probe=b3513301a1) | May 08, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [e98c6a162c](https://linux-hardware.org/?probe=e98c6a162c) | May 03, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [32a9d86996](https://linux-hardware.org/?probe=32a9d86996) | May 02, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [670ddc1e5c](https://linux-hardware.org/?probe=670ddc1e5c) | Apr 13, 2020 |
| HP            | Pavilion dv6                | Notebook    | [6939cb8715](https://linux-hardware.org/?probe=6939cb8715) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [328b82f240](https://linux-hardware.org/?probe=328b82f240) | Apr 11, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0c6dc861d6](https://linux-hardware.org/?probe=0c6dc861d6) | Apr 06, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [acad555779](https://linux-hardware.org/?probe=acad555779) | Apr 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [d459f09cfe](https://linux-hardware.org/?probe=d459f09cfe) | Apr 01, 2020 |
| Lenovo        | Board                       | Desktop     | [ef01565711](https://linux-hardware.org/?probe=ef01565711) | Apr 01, 2020 |
| Lenovo        | Board                       | Desktop     | [7c54db2820](https://linux-hardware.org/?probe=7c54db2820) | Apr 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [3d9d707ea7](https://linux-hardware.org/?probe=3d9d707ea7) | Mar 30, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [f7cfd1b163](https://linux-hardware.org/?probe=f7cfd1b163) | Mar 26, 2020 |
| ASUSTek       | P5PL2                       | Desktop     | [19fbc6cfd3](https://linux-hardware.org/?probe=19fbc6cfd3) | Mar 25, 2020 |
| Acer          | Swift SF314-56              | Notebook    | [3826e4d14c](https://linux-hardware.org/?probe=3826e4d14c) | Mar 24, 2020 |
| Google        | Kip                         | Notebook    | [4f62ee34a3](https://linux-hardware.org/?probe=4f62ee34a3) | Mar 22, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [96e42952bb](https://linux-hardware.org/?probe=96e42952bb) | Mar 17, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [868fa5cf23](https://linux-hardware.org/?probe=868fa5cf23) | Mar 15, 2020 |
| Dell          | Vostro 3446                 | Notebook    | [c42d273e36](https://linux-hardware.org/?probe=c42d273e36) | Mar 12, 2020 |
| Gigabyte      | GA-890XA-UD3                | Desktop     | [e2cafdec0d](https://linux-hardware.org/?probe=e2cafdec0d) | Mar 09, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [0c527b2640](https://linux-hardware.org/?probe=0c527b2640) | Mar 08, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [3924df2c92](https://linux-hardware.org/?probe=3924df2c92) | Feb 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [1281c8c30d](https://linux-hardware.org/?probe=1281c8c30d) | Feb 26, 2020 |
| Lenovo        | ThinkPad T480 20L5S08L00    | Notebook    | [3c23e0d823](https://linux-hardware.org/?probe=3c23e0d823) | Feb 20, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [fdc69c0b70](https://linux-hardware.org/?probe=fdc69c0b70) | Feb 08, 2020 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [771600b1ae](https://linux-hardware.org/?probe=771600b1ae) | Feb 07, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [4060a4338e](https://linux-hardware.org/?probe=4060a4338e) | Feb 05, 2020 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [eb8bd4a219](https://linux-hardware.org/?probe=eb8bd4a219) | Jan 20, 2020 |
| ASUSTek       | X556UQK                     | Notebook    | [5070b3831b](https://linux-hardware.org/?probe=5070b3831b) | Dec 29, 2019 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [ad271d2feb](https://linux-hardware.org/?probe=ad271d2feb) | Dec 28, 2019 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [b039aefd9e](https://linux-hardware.org/?probe=b039aefd9e) | Dec 25, 2019 |
| Lenovo        | ThinkPad X301 4057WHQ       | Notebook    | [badcab7790](https://linux-hardware.org/?probe=badcab7790) | Dec 22, 2019 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b51c7d1ee8](https://linux-hardware.org/?probe=b51c7d1ee8) | Dec 20, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [31f9126345](https://linux-hardware.org/?probe=31f9126345) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [627975dcd4](https://linux-hardware.org/?probe=627975dcd4) | Dec 18, 2019 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [b0d238eb2e](https://linux-hardware.org/?probe=b0d238eb2e) | Dec 11, 2019 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9f6135476f](https://linux-hardware.org/?probe=9f6135476f) | Dec 10, 2019 |
| Howard Com... | W350                        | Notebook    | [7434be9250](https://linux-hardware.org/?probe=7434be9250) | Dec 10, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [99d56262c0](https://linux-hardware.org/?probe=99d56262c0) | Dec 03, 2019 |
| HP            | Pavilion 17                 | Notebook    | [09c3d61b20](https://linux-hardware.org/?probe=09c3d61b20) | Nov 18, 2019 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [372f025649](https://linux-hardware.org/?probe=372f025649) | Nov 18, 2019 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [2395d81be3](https://linux-hardware.org/?probe=2395d81be3) | Nov 15, 2019 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [7f6fec93cc](https://linux-hardware.org/?probe=7f6fec93cc) | Nov 15, 2019 |
| HP            | 255 G1                      | Notebook    | [0a0d476781](https://linux-hardware.org/?probe=0a0d476781) | Nov 06, 2019 |
| HP            | 255 G1                      | Notebook    | [ccb02c7d8e](https://linux-hardware.org/?probe=ccb02c7d8e) | Nov 04, 2019 |
| HP            | 255 G1                      | Notebook    | [2aa8aaffc1](https://linux-hardware.org/?probe=2aa8aaffc1) | Nov 04, 2019 |
| Acer          | Swift SF315-52              | Notebook    | [c5950fe2b2](https://linux-hardware.org/?probe=c5950fe2b2) | Oct 20, 2019 |
| Toshiba       | Unknown                     | Notebook    | [64c90921de](https://linux-hardware.org/?probe=64c90921de) | Oct 18, 2019 |
| Dell          | Latitude 7490               | Notebook    | [2381ee7707](https://linux-hardware.org/?probe=2381ee7707) | Oct 14, 2019 |
| HP            | ENVY dv7                    | Notebook    | [1f13304239](https://linux-hardware.org/?probe=1f13304239) | Oct 06, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4e34d8767a](https://linux-hardware.org/?probe=4e34d8767a) | Aug 03, 2019 |
| Dell          | XPS 15 9560                 | Notebook    | [65f14ca77f](https://linux-hardware.org/?probe=65f14ca77f) | Jun 11, 2019 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [9e0b67b32e](https://linux-hardware.org/?probe=9e0b67b32e) | May 05, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [d61154eabe](https://linux-hardware.org/?probe=d61154eabe) | Apr 16, 2019 |
| HP            | EliteBook 8770w             | Notebook    | [fdba82a5b5](https://linux-hardware.org/?probe=fdba82a5b5) | Apr 01, 2019 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [4aced2b19a](https://linux-hardware.org/?probe=4aced2b19a) | Feb 28, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [0ffa9711e1](https://linux-hardware.org/?probe=0ffa9711e1) | Jan 07, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [46de1b2636](https://linux-hardware.org/?probe=46de1b2636) | Jan 07, 2019 |
| Acer          | Aspire E1-532P              | Notebook    | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Solus 4.1    | 65        | 40.37%  |
| Solus 4.3    | 46        | 28.57%  |
| Solus 4.2    | 25        | 15.53%  |
| Solus 4.0    | 23        | 14.29%  |
| Solus 3.9999 | 2         | 1.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Solus | 152       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 15        | 8.77%   |
| 5.6.19-159.current  | 10        | 5.85%   |
| 5.5.7-150.current   | 8         | 4.68%   |
| 5.14.21-210.current | 7         | 4.09%   |
| 5.6.4-152.current   | 6         | 3.51%   |
| 5.6.13-153.current  | 6         | 3.51%   |
| 5.15.32-213.current | 6         | 3.51%   |
| 5.14.16-205.current | 6         | 3.51%   |
| 5.6.18-156.current  | 5         | 2.92%   |
| 5.4.12-144.current  | 5         | 2.92%   |
| 5.13.6-190.current  | 5         | 2.92%   |
| 5.13.12-193.current | 5         | 2.92%   |
| 5.13.1-187.current  | 5         | 2.92%   |
| 5.11.12-177.current | 5         | 2.92%   |
| 5.5.11-151.current  | 4         | 2.34%   |
| 5.11.22-180.current | 4         | 2.34%   |
| 5.10.15-172.current | 4         | 2.34%   |
| 5.3.7-132.current   | 3         | 1.75%   |
| 5.3.15-138.current  | 3         | 1.75%   |
| 5.2.20-130.current  | 3         | 1.75%   |
| 5.15.30-212.current | 3         | 1.75%   |
| 5.5.4-148.current   | 2         | 1.17%   |
| 5.4.1-137.current   | 2         | 1.17%   |
| 5.3.10-134.current  | 2         | 1.17%   |
| 5.2.2-122.current   | 2         | 1.17%   |
| 5.15.26-211.current | 2         | 1.17%   |
| 5.14.14-202.current | 2         | 1.17%   |
| 5.13.0-186.current  | 2         | 1.17%   |
| 5.12.10-182.current | 2         | 1.17%   |
| 5.11.9-176.current  | 2         | 1.17%   |
| 5.11.21-179.current | 2         | 1.17%   |
| 5.11.16-178.current | 2         | 1.17%   |
| 5.10.7-168.current  | 2         | 1.17%   |
| 5.10.5-167.current  | 2         | 1.17%   |
| 5.10.12-171.current | 2         | 1.17%   |
| 4.20.16-112.current | 2         | 1.17%   |
| 5.6.18-155.current  | 1         | 0.58%   |
| 5.5.3-147.current   | 1         | 0.58%   |
| 5.4.12-143.current  | 1         | 0.58%   |
| 5.3.8-133.current   | 1         | 0.58%   |
| 5.2.13-126.current  | 1         | 0.58%   |
| 5.14.7-198.current  | 1         | 0.58%   |
| 5.14.16-204.current | 1         | 0.58%   |
| 5.14.15-203.current | 1         | 0.58%   |
| 5.14.12-201.current | 1         | 0.58%   |
| 5.13.8-191.current  | 1         | 0.58%   |
| 5.13.15-194.current | 1         | 0.58%   |
| 5.12.13-185.current | 1         | 0.58%   |
| 5.10.9-169.current  | 1         | 0.58%   |
| 5.10.4-165.current  | 1         | 0.58%   |
| 5.10.2-164.current  | 1         | 0.58%   |
| 5.0.5-113.current   | 1         | 0.58%   |
| 5.0.16-116.current  | 1         | 0.58%   |
| 4.9.168-129.lts     | 1         | 0.58%   |
| 4.20.10-111.current | 1         | 0.58%   |
| 4.18.16-97.current  | 1         | 0.58%   |
| 4.14.221-168.lts    | 1         | 0.58%   |
| 4.14.215-164.lts    | 1         | 0.58%   |
| 4.14.189-161.lts    | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.6.19   | 25        | 14.62%  |
| 5.5.7    | 8         | 4.68%   |
| 5.14.21  | 7         | 4.09%   |
| 5.14.16  | 7         | 4.09%   |
| 5.6.4    | 6         | 3.51%   |
| 5.6.18   | 6         | 3.51%   |
| 5.6.13   | 6         | 3.51%   |
| 5.4.12   | 6         | 3.51%   |
| 5.15.32  | 6         | 3.51%   |
| 5.13.6   | 5         | 2.92%   |
| 5.13.12  | 5         | 2.92%   |
| 5.13.1   | 5         | 2.92%   |
| 5.11.12  | 5         | 2.92%   |
| 5.5.11   | 4         | 2.34%   |
| 5.11.22  | 4         | 2.34%   |
| 5.10.15  | 4         | 2.34%   |
| 5.3.7    | 3         | 1.75%   |
| 5.3.15   | 3         | 1.75%   |
| 5.2.20   | 3         | 1.75%   |
| 5.15.30  | 3         | 1.75%   |
| 5.5.4    | 2         | 1.17%   |
| 5.4.1    | 2         | 1.17%   |
| 5.3.10   | 2         | 1.17%   |
| 5.2.2    | 2         | 1.17%   |
| 5.15.26  | 2         | 1.17%   |
| 5.14.14  | 2         | 1.17%   |
| 5.13.0   | 2         | 1.17%   |
| 5.12.10  | 2         | 1.17%   |
| 5.11.9   | 2         | 1.17%   |
| 5.11.21  | 2         | 1.17%   |
| 5.11.16  | 2         | 1.17%   |
| 5.10.7   | 2         | 1.17%   |
| 5.10.5   | 2         | 1.17%   |
| 5.10.12  | 2         | 1.17%   |
| 4.20.16  | 2         | 1.17%   |
| 5.5.3    | 1         | 0.58%   |
| 5.3.8    | 1         | 0.58%   |
| 5.2.13   | 1         | 0.58%   |
| 5.14.7   | 1         | 0.58%   |
| 5.14.15  | 1         | 0.58%   |
| 5.14.12  | 1         | 0.58%   |
| 5.13.8   | 1         | 0.58%   |
| 5.13.15  | 1         | 0.58%   |
| 5.12.13  | 1         | 0.58%   |
| 5.10.9   | 1         | 0.58%   |
| 5.10.4   | 1         | 0.58%   |
| 5.10.2   | 1         | 0.58%   |
| 5.0.5    | 1         | 0.58%   |
| 5.0.16   | 1         | 0.58%   |
| 4.9.168  | 1         | 0.58%   |
| 4.20.10  | 1         | 0.58%   |
| 4.18.16  | 1         | 0.58%   |
| 4.14.221 | 1         | 0.58%   |
| 4.14.215 | 1         | 0.58%   |
| 4.14.189 | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 42        | 25%     |
| 5.14    | 19        | 11.31%  |
| 5.13    | 18        | 10.71%  |
| 5.5     | 15        | 8.93%   |
| 5.11    | 14        | 8.33%   |
| 5.10    | 13        | 7.74%   |
| 5.15    | 11        | 6.55%   |
| 5.3     | 9         | 5.36%   |
| 5.4     | 8         | 4.76%   |
| 5.2     | 6         | 3.57%   |
| 5.12    | 3         | 1.79%   |
| 4.20    | 3         | 1.79%   |
| 4.14    | 3         | 1.79%   |
| 5.0     | 2         | 1.19%   |
| 4.9     | 1         | 0.6%    |
| 4.18    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 152       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 91        | 57.23%  |
| Unknown | 29        | 18.24%  |
| KDE     | 15        | 9.43%   |
| GNOME   | 12        | 7.55%   |
| MATE    | 9         | 5.66%   |
| KDE5    | 3         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 151       | 98.69%  |
| Wayland | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 116       | 74.84%  |
| TDM     | 19        | 12.26%  |
| LightDM | 12        | 7.74%   |
| SDDM    | 5         | 3.23%   |
| GDM     | 3         | 1.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 77        | 50%     |
| Unknown | 13        | 8.44%   |
| pt_BR   | 8         | 5.19%   |
| de_DE   | 8         | 5.19%   |
| ru_RU   | 7         | 4.55%   |
| en_GB   | 7         | 4.55%   |
| fr_FR   | 5         | 3.25%   |
| es_ES   | 5         | 3.25%   |
| en_AU   | 4         | 2.6%    |
| pl_PL   | 3         | 1.95%   |
| tr_TR   | 2         | 1.3%    |
| it_IT   | 2         | 1.3%    |
| en_NZ   | 2         | 1.3%    |
| uk_UA   | 1         | 0.65%   |
| pt_PT   | 1         | 0.65%   |
| nl_NL   | 1         | 0.65%   |
| es_VE   | 1         | 0.65%   |
| es_CL   | 1         | 0.65%   |
| en_IN   | 1         | 0.65%   |
| en_IE   | 1         | 0.65%   |
| en_CA   | 1         | 0.65%   |
| de_AT   | 1         | 0.65%   |
| ar_SA   | 1         | 0.65%   |
| ar_EG   | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 89        | 58.17%  |
| BIOS | 64        | 41.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 143       | 92.86%  |
| Unknown | 9         | 5.84%   |
| Xfs     | 1         | 0.65%   |
| Btrfs   | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 68.79%  |
| GPT     | 39        | 24.84%  |
| MBR     | 10        | 6.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 92.16%  |
| Yes       | 12        | 7.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 80.13%  |
| Yes       | 31        | 19.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 19        | 12.5%   |
| Hewlett-Packard        | 19        | 12.5%   |
| ASUSTek Computer       | 19        | 12.5%   |
| Dell                   | 18        | 11.84%  |
| Gigabyte Technology    | 17        | 11.18%  |
| Acer                   | 15        | 9.87%   |
| MSI                    | 7         | 4.61%   |
| Toshiba                | 6         | 3.95%   |
| ASRock                 | 5         | 3.29%   |
| Apple                  | 3         | 1.97%   |
| Sony                   | 2         | 1.32%   |
| Samsung Electronics    | 2         | 1.32%   |
| Intel                  | 2         | 1.32%   |
| Google                 | 2         | 1.32%   |
| Biostar                | 2         | 1.32%   |
| Timi                   | 1         | 0.66%   |
| Shuttle                | 1         | 0.66%   |
| Pegatron               | 1         | 0.66%   |
| Panasonic              | 1         | 0.66%   |
| Packard Bell           | 1         | 0.66%   |
| MEGA                   | 1         | 0.66%   |
| Howard Computers       | 1         | 0.66%   |
| Fujitsu                | 1         | 0.66%   |
| Framework              | 1         | 0.66%   |
| eMachines              | 1         | 0.66%   |
| Chuwi                  | 1         | 0.66%   |
| AZW                    | 1         | 0.66%   |
| Avell High Performance | 1         | 0.66%   |
| Unknown                | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Acer Aspire E5-575G                                   | 2         | 1.32%   |
| Unknown                                               | 2         | 1.32%   |
| Toshiba TECRA R840                                    | 1         | 0.66%   |
| Toshiba Satellite P50-A                               | 1         | 0.66%   |
| Toshiba Satellite L855                                | 1         | 0.66%   |
| Toshiba Satellite L655                                | 1         | 0.66%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 0.66%   |
| Timi TM1701                                           | 1         | 0.66%   |
| Sony VPCYB15AB                                        | 1         | 0.66%   |
| Sony VPCEB1S1E                                        | 1         | 0.66%   |
| Shuttle XS35V4                                        | 1         | 0.66%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.66%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 0.66%   |
| Pegatron IPM31                                        | 1         | 0.66%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 0.66%   |
| Packard Bell EasyNote TS11HR                          | 1         | 0.66%   |
| MSI MS-7C91                                           | 1         | 0.66%   |
| MSI MS-7B89                                           | 1         | 0.66%   |
| MSI MS-7B85                                           | 1         | 0.66%   |
| MSI MS-7B84                                           | 1         | 0.66%   |
| MSI MS-7A34                                           | 1         | 0.66%   |
| MSI MS-7850                                           | 1         | 0.66%   |
| MSI MS-7640                                           | 1         | 0.66%   |
| MEGA G41T-M7 LGT                                      | 1         | 0.66%   |
| Lenovo Z51-70 80K6                                    | 1         | 0.66%   |
| Lenovo Z50-70 20354                                   | 1         | 0.66%   |
| Lenovo Yoga 730-13IKB 81CT                            | 1         | 0.66%   |
| Lenovo Yoga 510-14ISK 80S7                            | 1         | 0.66%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.66%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 0.66%   |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 0.66%   |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 0.66%   |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 0.66%   |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 0.66%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 0.66%   |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 0.66%   |
| Lenovo ThinkCentre M71e 3157G6S                       | 1         | 0.66%   |
| Lenovo MIIX 310-10ICR 80SG                            | 1         | 0.66%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 0.66%   |
| Lenovo IdeaPad 330S-15IKB 81F5                        | 1         | 0.66%   |
| Lenovo IdeaPad 320-15ISK 80XH                         | 1         | 0.66%   |
| Lenovo IdeaCentre K320 10031                          | 1         | 0.66%   |
| Intel X99 V102                                        | 1         | 0.66%   |
| Intel NUC8i7BEH                                       | 1         | 0.66%   |
| Howard Computers W350                                 | 1         | 0.66%   |
| HP Stream Laptop 14-cb1XX                             | 1         | 0.66%   |
| HP Spectre x360 Convertible 15-bl1XX                  | 1         | 0.66%   |
| HP ProDesk 490 G3 MT Business PC                      | 1         | 0.66%   |
| HP ProBook 650 G1                                     | 1         | 0.66%   |
| HP ProBook 6470b                                      | 1         | 0.66%   |
| HP ProBook 450 G5                                     | 1         | 0.66%   |
| HP ProBook 440 G4                                     | 1         | 0.66%   |
| HP Presario C700                                      | 1         | 0.66%   |
| HP Pavilion Laptop 15-cw0xxx                          | 1         | 0.66%   |
| HP Pavilion dv7                                       | 1         | 0.66%   |
| HP Pavilion dv6                                       | 1         | 0.66%   |
| HP Pavilion 17                                        | 1         | 0.66%   |
| HP OMEN Laptop 15-en0xxx                              | 1         | 0.66%   |
| HP ENVY x360 Convertible 13-ag0xxx                    | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 5.92%   |
| Acer Aspire            | 9         | 5.92%   |
| Dell Inspiron          | 5         | 3.29%   |
| HP ProBook             | 4         | 2.63%   |
| HP Pavilion            | 4         | 2.63%   |
| Gigabyte Z390          | 4         | 2.63%   |
| Dell XPS               | 4         | 2.63%   |
| Dell Latitude          | 4         | 2.63%   |
| Toshiba Satellite      | 3         | 1.97%   |
| ASUS TUF               | 3         | 1.97%   |
| ASUS PRIME             | 3         | 1.97%   |
| Acer Swift             | 3         | 1.97%   |
| Lenovo Yoga            | 2         | 1.32%   |
| Lenovo IdeaPad         | 2         | 1.32%   |
| HP ENVY                | 2         | 1.32%   |
| HP EliteBook           | 2         | 1.32%   |
| Dell Vostro            | 2         | 1.32%   |
| Dell OptiPlex          | 2         | 1.32%   |
| ASUS ROG               | 2         | 1.32%   |
| Unknown                | 2         | 1.32%   |
| Toshiba TECRA          | 1         | 0.66%   |
| Toshiba PORTEGE        | 1         | 0.66%   |
| Timi TM1701            | 1         | 0.66%   |
| Sony VPCYB15AB         | 1         | 0.66%   |
| Sony VPCEB1S1E         | 1         | 0.66%   |
| Shuttle XS35V4         | 1         | 0.66%   |
| Samsung 300E5EV        | 1         | 0.66%   |
| Samsung 270E5K         | 1         | 0.66%   |
| Pegatron IPM31         | 1         | 0.66%   |
| Panasonic CF-C2CCEZXCM | 1         | 0.66%   |
| Packard Bell EasyNote  | 1         | 0.66%   |
| MSI MS-7C91            | 1         | 0.66%   |
| MSI MS-7B89            | 1         | 0.66%   |
| MSI MS-7B85            | 1         | 0.66%   |
| MSI MS-7B84            | 1         | 0.66%   |
| MSI MS-7A34            | 1         | 0.66%   |
| MSI MS-7850            | 1         | 0.66%   |
| MSI MS-7640            | 1         | 0.66%   |
| MEGA G41T-M7           | 1         | 0.66%   |
| Lenovo Z51-70          | 1         | 0.66%   |
| Lenovo Z50-70          | 1         | 0.66%   |
| Lenovo ThinkCentre     | 1         | 0.66%   |
| Lenovo MIIX            | 1         | 0.66%   |
| Lenovo Legion          | 1         | 0.66%   |
| Lenovo IdeaCentre      | 1         | 0.66%   |
| Intel X99              | 1         | 0.66%   |
| Intel NUC8i7BEH        | 1         | 0.66%   |
| Howard Computers W350  | 1         | 0.66%   |
| HP Stream              | 1         | 0.66%   |
| HP Spectre             | 1         | 0.66%   |
| HP ProDesk             | 1         | 0.66%   |
| HP Presario            | 1         | 0.66%   |
| HP OMEN                | 1         | 0.66%   |
| HP Elite               | 1         | 0.66%   |
| HP 255                 | 1         | 0.66%   |
| Google Kip             | 1         | 0.66%   |
| Google Delbin          | 1         | 0.66%   |
| Gigabyte X570          | 1         | 0.66%   |
| Gigabyte P31-ES3G      | 1         | 0.66%   |
| Gigabyte J4005ND2P-CF  | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 29        | 19.08%  |
| 2019 | 15        | 9.87%   |
| 2016 | 13        | 8.55%   |
| 2017 | 12        | 7.89%   |
| 2014 | 12        | 7.89%   |
| 2012 | 12        | 7.89%   |
| 2013 | 11        | 7.24%   |
| 2020 | 9         | 5.92%   |
| 2011 | 8         | 5.26%   |
| 2008 | 7         | 4.61%   |
| 2021 | 6         | 3.95%   |
| 2010 | 6         | 3.95%   |
| 2015 | 5         | 3.29%   |
| 2009 | 4         | 2.63%   |
| 2006 | 2         | 1.32%   |
| 2007 | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 87        | 57.24%  |
| Desktop     | 56        | 36.84%  |
| Convertible | 6         | 3.95%   |
| Tablet      | 1         | 0.66%   |
| Mini pc     | 1         | 0.66%   |
| All in one  | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 152       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 150       | 98.68%  |
| Yes  | 2         | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 38        | 24.68%  |
| 3.01-4.0    | 33        | 21.43%  |
| 8.01-16.0   | 30        | 19.48%  |
| 4.01-8.0    | 26        | 16.88%  |
| 32.01-64.0  | 17        | 11.04%  |
| 24.01-32.0  | 3         | 1.95%   |
| 2.01-3.0    | 3         | 1.95%   |
| 1.01-2.0    | 3         | 1.95%   |
| 64.01-256.0 | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 53        | 32.92%  |
| 2.01-3.0  | 43        | 26.71%  |
| 4.01-8.0  | 23        | 14.29%  |
| 3.01-4.0  | 21        | 13.04%  |
| 8.01-16.0 | 11        | 6.83%   |
| 0.51-1.0  | 10        | 6.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 53.21%  |
| 2      | 47        | 30.13%  |
| 4      | 10        | 6.41%   |
| 3      | 9         | 5.77%   |
| 5      | 4         | 2.56%   |
| 6      | 2         | 1.28%   |
| 7      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 59.74%  |
| Yes       | 62        | 40.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 87.5%   |
| No        | 19        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 78.29%  |
| No        | 33        | 21.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 64.71%  |
| No        | 54        | 35.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 26        | 17.11%  |
| Brazil             | 11        | 7.24%   |
| India              | 9         | 5.92%   |
| Netherlands        | 8         | 5.26%   |
| Germany            | 8         | 5.26%   |
| Russia             | 7         | 4.61%   |
| Canada             | 6         | 3.95%   |
| Spain              | 5         | 3.29%   |
| France             | 5         | 3.29%   |
| Australia          | 5         | 3.29%   |
| Sweden             | 4         | 2.63%   |
| Poland             | 4         | 2.63%   |
| UK                 | 3         | 1.97%   |
| Turkey             | 3         | 1.97%   |
| Switzerland        | 3         | 1.97%   |
| Norway             | 3         | 1.97%   |
| New Zealand        | 3         | 1.97%   |
| Venezuela          | 2         | 1.32%   |
| Saudi Arabia       | 2         | 1.32%   |
| Mexico             | 2         | 1.32%   |
| Iran               | 2         | 1.32%   |
| Indonesia          | 2         | 1.32%   |
| Guatemala          | 2         | 1.32%   |
| Greece             | 2         | 1.32%   |
| Chile              | 2         | 1.32%   |
| Albania            | 2         | 1.32%   |
| Vietnam            | 1         | 0.66%   |
| Ukraine            | 1         | 0.66%   |
| Thailand           | 1         | 0.66%   |
| Portugal           | 1         | 0.66%   |
| Philippines        | 1         | 0.66%   |
| Peru               | 1         | 0.66%   |
| Oman               | 1         | 0.66%   |
| Nepal              | 1         | 0.66%   |
| Latvia             | 1         | 0.66%   |
| Kazakhstan         | 1         | 0.66%   |
| Japan              | 1         | 0.66%   |
| Italy              | 1         | 0.66%   |
| Ireland            | 1         | 0.66%   |
| Hungary            | 1         | 0.66%   |
| Guyana             | 1         | 0.66%   |
| Finland            | 1         | 0.66%   |
| Dominican Republic | 1         | 0.66%   |
| China              | 1         | 0.66%   |
| Belgium            | 1         | 0.66%   |
| Belarus            | 1         | 0.66%   |
| Austria            | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Toronto                 | 3         | 1.91%   |
| St Petersburg           | 2         | 1.27%   |
| Severna Park            | 2         | 1.27%   |
| Oslo                    | 2         | 1.27%   |
| New York                | 2         | 1.27%   |
| Melbourne               | 2         | 1.27%   |
| Mainz                   | 2         | 1.27%   |
| Guatemala City          | 2         | 1.27%   |
| Delhi                   | 2         | 1.27%   |
| Curitiba                | 2         | 1.27%   |
| Columbus                | 2         | 1.27%   |
| Auckland                | 2         | 1.27%   |
| Г„ngelholm           | 1         | 0.64%   |
| Zurich                  | 1         | 0.64%   |
| Zoutleeuw               | 1         | 0.64%   |
| Yverdon-les-Bains       | 1         | 0.64%   |
| Yekaterinburg           | 1         | 0.64%   |
| Winchmore Hill          | 1         | 0.64%   |
| Wilchingen, Osterfingen | 1         | 0.64%   |
| Waterloo                | 1         | 0.64%   |
| Vineland                | 1         | 0.64%   |
| Vienna                  | 1         | 0.64%   |
| Vesoul                  | 1         | 0.64%   |
| Vancouver               | 1         | 0.64%   |
| Trondheim               | 1         | 0.64%   |
| Trabzon                 | 1         | 0.64%   |
| Tirana                  | 1         | 0.64%   |
| Thessaloniki            | 1         | 0.64%   |
| The Hague               | 1         | 0.64%   |
| Tehran                  | 1         | 0.64%   |
| SГЈo Pedro            | 1         | 0.64%   |
| Stroudsburg             | 1         | 0.64%   |
| St. Cloud               | 1         | 0.64%   |
| Seville                 | 1         | 0.64%   |
| Semarang                | 1         | 0.64%   |
| Santo Domingo Este      | 1         | 0.64%   |
| Santiago                | 1         | 0.64%   |
| Santa Maria             | 1         | 0.64%   |
| San Jose                | 1         | 0.64%   |
| Saint Paul              | 1         | 0.64%   |
| Sadao                   | 1         | 0.64%   |
| Riga                    | 1         | 0.64%   |
| Red Oak                 | 1         | 0.64%   |
| Providencia             | 1         | 0.64%   |
| Portsmouth              | 1         | 0.64%   |
| Portland                | 1         | 0.64%   |
| Phoenix                 | 1         | 0.64%   |
| Pessac                  | 1         | 0.64%   |
| Perth                   | 1         | 0.64%   |
| Parkdale                | 1         | 0.64%   |
| Paracuellos de Jarama   | 1         | 0.64%   |
| Orenburg                | 1         | 0.64%   |
| Novosibirsk             | 1         | 0.64%   |
| Nijmegen                | 1         | 0.64%   |
| NieporÄ™t            | 1         | 0.64%   |
| Navelim                 | 1         | 0.64%   |
| Naaldwijk               | 1         | 0.64%   |
| MГЎlaga               | 1         | 0.64%   |
| Muscat                  | 1         | 0.64%   |
| Munich                  | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 57     | 17.02%  |
| Samsung Electronics | 38        | 67     | 16.17%  |
| Seagate             | 30        | 54     | 12.77%  |
| Toshiba             | 23        | 28     | 9.79%   |
| Kingston            | 16        | 19     | 6.81%   |
| Unknown             | 13        | 15     | 5.53%   |
| Sandisk             | 13        | 18     | 5.53%   |
| Intel               | 11        | 13     | 4.68%   |
| SK Hynix            | 7         | 7      | 2.98%   |
| Crucial             | 7         | 8      | 2.98%   |
| Micron Technology   | 6         | 7      | 2.55%   |
| Hitachi             | 5         | 5      | 2.13%   |
| A-DATA Technology   | 4         | 4      | 1.7%    |
| Silicon Motion      | 2         | 2      | 0.85%   |
| PNY                 | 2         | 2      | 0.85%   |
| HGST                | 2         | 2      | 0.85%   |
| China               | 2         | 2      | 0.85%   |
| Apple               | 2         | 6      | 0.85%   |
| Transcend           | 1         | 1      | 0.43%   |
| Phison              | 1         | 1      | 0.43%   |
| Patriot             | 1         | 1      | 0.43%   |
| Lenovo              | 1         | 1      | 0.43%   |
| KIOXIA              | 1         | 1      | 0.43%   |
| KingFast            | 1         | 1      | 0.43%   |
| Intenso             | 1         | 2      | 0.43%   |
| Gigabyte Technology | 1         | 1      | 0.43%   |
| FORESEE             | 1         | 1      | 0.43%   |
| Corsair             | 1         | 1      | 0.43%   |
| Advantech           | 1         | 1      | 0.43%   |
| AAPL                | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB            | 7         | 2.61%   |
| Samsung SSD 850 EVO 250GB               | 6         | 2.24%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 2.24%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.87%   |
| Samsung SSD 850 EVO 500GB               | 5         | 1.87%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 1.12%   |
| Seagate ST500DM002-1BD142 500GB         | 3         | 1.12%   |
| Seagate ST2000DX002-2DV164 2TB          | 3         | 1.12%   |
| Sandisk NVMe SSD Drive 256GB            | 3         | 1.12%   |
| Samsung SSD 860 EVO 250GB               | 3         | 1.12%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2         | 0.75%   |
| WDC WD2003FZEX-00SRLA0 2TB              | 2         | 0.75%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.75%   |
| WDC WD10EADS-00M2B0 1TB                 | 2         | 0.75%   |
| Unknown TP02000GB 2TB                   | 2         | 0.75%   |
| Unknown MMC Card  32GB                  | 2         | 0.75%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.75%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.75%   |
| SK Hynix PC401 HFS256GD9TNG-62A0A 256GB | 2         | 0.75%   |
| SK Hynix NVMe SSD Drive 128GB           | 2         | 0.75%   |
| Seagate ST31000528AS 1TB                | 2         | 0.75%   |
| Seagate ST31000524AS 1TB                | 2         | 0.75%   |
| Seagate ST2000DX001-1NS164 2TB          | 2         | 0.75%   |
| SanDisk SDSSDA240G 240GB                | 2         | 0.75%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.75%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.75%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.75%   |
| Intel NVMe SSD Drive 256GB              | 2         | 0.75%   |
| Intel NVMe SSD Drive 1024GB             | 2         | 0.75%   |
| Hitachi HTS545032B9A300 320GB           | 2         | 0.75%   |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.75%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.37%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD        | 1         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.37%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.37%   |
| WDC WD6400AAKS-75A7B2 640GB             | 1         | 0.37%   |
| WDC WD6400AAKS-65A7B2 640GB             | 1         | 0.37%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 0.37%   |
| WDC WD5000AVDS-63U7B1 500GB             | 1         | 0.37%   |
| WDC WD5000AVCS-632DY1 500GB             | 1         | 0.37%   |
| WDC WD5000AAKX-003CA0 500GB             | 1         | 0.37%   |
| WDC WD5000AAKX-001CA0 500GB             | 1         | 0.37%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1         | 0.37%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 0.37%   |
| WDC WD3200AAJS-00YZCA0 320GB            | 1         | 0.37%   |
| WDC WD32 00AAJS-00L7A0 320GB            | 1         | 0.37%   |
| WDC WD3000GLFS-01F8U0 304GB             | 1         | 0.37%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 0.37%   |
| WDC WD2500HHTZ-04N21V1 250GB            | 1         | 0.37%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.37%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.37%   |
| WDC WD2500BEVT-00A23T0 250GB            | 1         | 0.37%   |
| WDC WD20EARX-00PASB0 2TB                | 1         | 0.37%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.37%   |
| WDC WD2002FAEX-007BA0 2TB               | 1         | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.37%   |
| WDC WD10JPVX-08JC3T5 1TB                | 1         | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 51     | 38.04%  |
| Seagate             | 30        | 54     | 32.61%  |
| Toshiba             | 15        | 20     | 16.3%   |
| Hitachi             | 5         | 5      | 5.43%   |
| Samsung Electronics | 3         | 3      | 3.26%   |
| HGST                | 2         | 2      | 2.17%   |
| Intenso             | 1         | 2      | 1.09%   |
| AAPL                | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 40     | 33.73%  |
| Kingston            | 11        | 13     | 13.25%  |
| SanDisk             | 8         | 12     | 9.64%   |
| Micron Technology   | 5         | 6      | 6.02%   |
| Crucial             | 5         | 6      | 6.02%   |
| Intel               | 4         | 5      | 4.82%   |
| WDC                 | 3         | 3      | 3.61%   |
| A-DATA Technology   | 3         | 3      | 3.61%   |
| Unknown             | 2         | 2      | 2.41%   |
| Toshiba             | 2         | 2      | 2.41%   |
| PNY                 | 2         | 2      | 2.41%   |
| China               | 2         | 2      | 2.41%   |
| Apple               | 2         | 6      | 2.41%   |
| Transcend           | 1         | 1      | 1.2%    |
| Patriot             | 1         | 1      | 1.2%    |
| Gigabyte Technology | 1         | 1      | 1.2%    |
| FORESEE             | 1         | 1      | 1.2%    |
| Corsair             | 1         | 1      | 1.2%    |
| Advantech           | 1         | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 80        | 138    | 36.7%   |
| SSD     | 74        | 108    | 33.94%  |
| NVMe    | 50        | 66     | 22.94%  |
| MMC     | 8         | 9      | 3.67%   |
| Unknown | 6         | 8      | 2.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 115       | 237    | 63.19%  |
| NVMe | 50        | 66     | 27.47%  |
| SAS  | 9         | 17     | 4.95%   |
| MMC  | 8         | 9      | 4.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 139    | 58.44%  |
| 0.51-1.0   | 44        | 64     | 28.57%  |
| 1.01-2.0   | 15        | 35     | 9.74%   |
| 3.01-4.0   | 3         | 5      | 1.95%   |
| 2.01-3.0   | 1         | 2      | 0.65%   |
| 4.01-10.0  | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 36.13%  |
| 251-500        | 36        | 23.23%  |
| 501-1000       | 24        | 15.48%  |
| 1001-2000      | 12        | 7.74%   |
| More than 3000 | 7         | 4.52%   |
| 51-100         | 7         | 4.52%   |
| 21-50          | 5         | 3.23%   |
| 2001-3000      | 4         | 2.58%   |
| 1-20           | 2         | 1.29%   |
| Unknown        | 2         | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 35.22%  |
| 21-50          | 27        | 16.98%  |
| 101-250        | 22        | 13.84%  |
| 251-500        | 16        | 10.06%  |
| 51-100         | 14        | 8.81%   |
| 501-1000       | 10        | 6.29%   |
| 1001-2000      | 7         | 4.4%    |
| 2001-3000      | 3         | 1.89%   |
| More than 3000 | 2         | 1.26%   |
| Unknown        | 2         | 1.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 10%     |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 10%     |
| WDC WD1002FAEX-00Y9A0 1TB                      | 1         | 1      | 10%     |
| WDC WD1001FALS-75J7B0 1TB                      | 1         | 1      | 10%     |
| Seagate ST2000DM001-9YN164 2TB                 | 1         | 1      | 10%     |
| Samsung Electronics SSD 970 EVO 500GB          | 1         | 1      | 10%     |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 10%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 10%     |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 10%     |
| Crucial CT1000P1SSD8 1TB                       | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 40%     |
| Samsung Electronics | 2         | 2      | 20%     |
| Seagate             | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| Crucial             | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 66.67%  |
| Seagate | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 55.56%  |
| NVMe | 3         | 3      | 33.33%  |
| SSD  | 1         | 1      | 11.11%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 114       | 249    | 67.86%  |
| Works    | 45        | 70     | 26.79%  |
| Malfunc  | 9         | 10     | 5.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 106       | 54.64%  |
| AMD                          | 33        | 17.01%  |
| Samsung Electronics          | 17        | 8.76%   |
| SK Hynix                     | 7         | 3.61%   |
| Toshiba America Info Systems | 6         | 3.09%   |
| Sandisk                      | 5         | 2.58%   |
| Kingston Technology Company  | 5         | 2.58%   |
| JMicron Technology           | 3         | 1.55%   |
| Silicon Motion               | 2         | 1.03%   |
| Micron/Crucial Technology    | 2         | 1.03%   |
| Marvell Technology Group     | 2         | 1.03%   |
| Phison Electronics           | 1         | 0.52%   |
| Nvidia                       | 1         | 0.52%   |
| Micron Technology            | 1         | 0.52%   |
| Lenovo                       | 1         | 0.52%   |
| ASMedia Technology           | 1         | 0.52%   |
| ADATA Technology             | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 24        | 10.91%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 5.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 5.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 3.64%   |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 3.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 2.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5         | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.82%   |
| Intel SSD 660P Series                                                            | 4         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.82%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 1.36%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 1.36%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.91%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.91%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.91%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.91%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 2         | 0.91%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.91%   |
| Kingston Company KC2000 NVMe SSD                                                 | 2         | 0.91%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.91%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.91%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 0.91%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.45%   |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                      | 1         | 0.45%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.45%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.45%   |
| Samsung Electronics SATA controller                                              | 1         | 0.45%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.45%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.45%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.45%   |
| Marvell Group 88SE9182 PCIe 2.0 x2 2-port SATA 6 Gb/s Controller                 | 1         | 0.45%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1         | 0.45%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.45%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.45%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 0.45%   |
| JMicron JMB362 SATA Controller                                                   | 1         | 0.45%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.45%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.45%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.45%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 1         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 62.63%  |
| NVMe | 50        | 26.32%  |
| IDE  | 15        | 7.89%   |
| RAID | 6         | 3.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 77.63%  |
| AMD    | 34        | 22.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 3.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.63%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 2.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.97%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.32%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 1.32%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1.32%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.32%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 1.32%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 1.32%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.32%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.32%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 2         | 1.32%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.66%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz           | 1         | 0.66%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.66%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.66%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.66%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.66%   |
| Intel Pentium D CPU 3.00GHz                   | 1         | 0.66%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.66%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.66%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.66%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.66%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.66%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1         | 0.66%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.66%   |
| Intel Core i7-8559U CPU @ 2.70GHz             | 1         | 0.66%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.66%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.66%   |
| Intel Core i7-3960X CPU @ 3.30GHz             | 1         | 0.66%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.66%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 0.66%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.66%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 0.66%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 0.66%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.66%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 0.66%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 25%     |
| Intel Core i7           | 31        | 20.39%  |
| Intel Core i3           | 13        | 8.55%   |
| AMD Ryzen 7             | 12        | 7.89%   |
| Intel Celeron           | 11        | 7.24%   |
| AMD Ryzen 5             | 11        | 7.24%   |
| Other                   | 4         | 2.63%   |
| Intel Pentium           | 4         | 2.63%   |
| Intel Core 2 Duo        | 4         | 2.63%   |
| Intel Xeon              | 3         | 1.97%   |
| Intel Pentium Dual-Core | 2         | 1.32%   |
| Intel Pentium D         | 2         | 1.32%   |
| Intel Core 2 Quad       | 2         | 1.32%   |
| AMD Ryzen 9             | 2         | 1.32%   |
| AMD Phenom II X4        | 2         | 1.32%   |
| AMD FX                  | 2         | 1.32%   |
| AMD A10                 | 2         | 1.32%   |
| Intel Pentium Silver    | 1         | 0.66%   |
| Intel Pentium Dual      | 1         | 0.66%   |
| Intel Core M            | 1         | 0.66%   |
| Intel Core i9           | 1         | 0.66%   |
| Intel Atom              | 1         | 0.66%   |
| AMD E1                  | 1         | 0.66%   |
| AMD E                   | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 68        | 44.74%  |
| 4      | 53        | 34.87%  |
| 6      | 15        | 9.87%   |
| 8      | 13        | 8.55%   |
| 16     | 1         | 0.66%   |
| 3      | 1         | 0.66%   |
| 1      | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 152       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 112       | 73.68%  |
| 1      | 40        | 26.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 96.08%  |
| Unknown        | 6         | 3.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 11        | 7.14%   |
| 0x806ea    | 10        | 6.49%   |
| 0x306a9    | 10        | 6.49%   |
| 0x206a7    | 9         | 5.84%   |
| Unknown    | 8         | 5.19%   |
| 0x806e9    | 6         | 3.9%    |
| 0x1067a    | 6         | 3.9%    |
| 0x906e9    | 5         | 3.25%   |
| 0x40651    | 5         | 3.25%   |
| 0x20655    | 5         | 3.25%   |
| 0x08701021 | 5         | 3.25%   |
| 0x906ea    | 4         | 2.6%    |
| 0x806ec    | 4         | 2.6%    |
| 0x706a1    | 4         | 2.6%    |
| 0x406e3    | 4         | 2.6%    |
| 0x0800820d | 4         | 2.6%    |
| 0x806c1    | 3         | 1.95%   |
| 0x506e3    | 3         | 1.95%   |
| 0x306d4    | 3         | 1.95%   |
| 0x30678    | 3         | 1.95%   |
| 0x906ec    | 2         | 1.3%    |
| 0x6fd      | 2         | 1.3%    |
| 0x0a50000c | 2         | 1.3%    |
| 0x08701013 | 2         | 1.3%    |
| 0x08108109 | 2         | 1.3%    |
| 0x08108102 | 2         | 1.3%    |
| 0x0810100b | 2         | 1.3%    |
| 0x06003106 | 2         | 1.3%    |
| 0x06000852 | 2         | 1.3%    |
| 0xf64      | 1         | 0.65%   |
| 0xf62      | 1         | 0.65%   |
| 0xa0652    | 1         | 0.65%   |
| 0x906ed    | 1         | 0.65%   |
| 0x906eb    | 1         | 0.65%   |
| 0x906c0    | 1         | 0.65%   |
| 0x806eb    | 1         | 0.65%   |
| 0x506c9    | 1         | 0.65%   |
| 0x406c4    | 1         | 0.65%   |
| 0x206d7    | 1         | 0.65%   |
| 0x20652    | 1         | 0.65%   |
| 0x10677    | 1         | 0.65%   |
| 0x10676    | 1         | 0.65%   |
| 0x10661    | 1         | 0.65%   |
| 0x0a201204 | 1         | 0.65%   |
| 0x0a201009 | 1         | 0.65%   |
| 0x08600106 | 1         | 0.65%   |
| 0x08101016 | 1         | 0.65%   |
| 0x0800820b | 1         | 0.65%   |
| 0x06006704 | 1         | 0.65%   |
| 0x05000119 | 1         | 0.65%   |
| 0x05000029 | 1         | 0.65%   |
| 0x010000db | 1         | 0.65%   |
| 0x010000c8 | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 24.34%  |
| Haswell       | 18        | 11.84%  |
| SandyBridge   | 10        | 6.58%   |
| IvyBridge     | 10        | 6.58%   |
| Zen+          | 9         | 5.92%   |
| Zen 2         | 9         | 5.92%   |
| Penryn        | 8         | 5.26%   |
| Skylake       | 7         | 4.61%   |
| Westmere      | 6         | 3.95%   |
| Zen 3         | 4         | 2.63%   |
| Silvermont    | 4         | 2.63%   |
| Goldmont plus | 4         | 2.63%   |
| Zen           | 3         | 1.97%   |
| TigerLake     | 3         | 1.97%   |
| Core          | 3         | 1.97%   |
| Broadwell     | 3         | 1.97%   |
| Steamroller   | 2         | 1.32%   |
| Piledriver    | 2         | 1.32%   |
| NetBurst      | 2         | 1.32%   |
| K10           | 2         | 1.32%   |
| Bobcat        | 2         | 1.32%   |
| Tremont       | 1         | 0.66%   |
| Goldmont      | 1         | 0.66%   |
| Excavator     | 1         | 0.66%   |
| CometLake     | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 93        | 49.21%  |
| Nvidia | 53        | 28.04%  |
| AMD    | 43        | 22.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 9         | 4.69%   |
| Intel HD Graphics 620                                                       | 7         | 3.65%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7         | 3.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 6         | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 2.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 2.08%   |
| Nvidia GM108M [GeForce 940MX]                                               | 3         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.56%   |
| Intel HD Graphics 630                                                       | 3         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3         | 1.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.04%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 1.04%   |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 1.04%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 2         | 1.04%   |
| Nvidia GF108M [GeForce GT 540M]                                             | 2         | 1.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.04%   |
| Intel HD Graphics 5500                                                      | 2         | 1.04%   |
| Intel HD Graphics 530                                                       | 2         | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.04%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                            | 2         | 1.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.04%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                    | 2         | 1.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.04%   |
| AMD Cezanne                                                                 | 2         | 1.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.52%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.52%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 0.52%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.52%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.52%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.52%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.52%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.52%   |
| Nvidia GK208M [GeForce GT 730M]                                             | 1         | 0.52%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 38.96%  |
| 1 x AMD        | 34        | 22.08%  |
| 1 x Nvidia     | 25        | 16.23%  |
| Intel + Nvidia | 25        | 16.23%  |
| Intel + AMD    | 6         | 3.9%    |
| AMD + Nvidia   | 4         | 2.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 116       | 76.32%  |
| Proprietary | 36        | 23.68%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 41.83%  |
| 1.01-2.0   | 26        | 16.99%  |
| 0.51-1.0   | 20        | 13.07%  |
| 5.01-6.0   | 10        | 6.54%   |
| 3.01-4.0   | 10        | 6.54%   |
| 7.01-8.0   | 9         | 5.88%   |
| 0.01-0.5   | 7         | 4.58%   |
| 8.01-16.0  | 4         | 2.61%   |
| 2.01-3.0   | 3         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 14.2%   |
| Samsung Electronics     | 22        | 12.5%   |
| LG Display              | 16        | 9.09%   |
| Goldstar                | 14        | 7.95%   |
| BOE                     | 13        | 7.39%   |
| Chimei Innolux          | 12        | 6.82%   |
| AOC                     | 11        | 6.25%   |
| Dell                    | 9         | 5.11%   |
| Ancor Communications    | 5         | 2.84%   |
| SHARP                   | 4         | 2.27%   |
| LG Electronics          | 4         | 2.27%   |
| Lenovo                  | 4         | 2.27%   |
| BenQ                    | 4         | 2.27%   |
| Acer                    | 4         | 2.27%   |
| Hewlett-Packard         | 3         | 1.7%    |
| ASUSTek Computer        | 3         | 1.7%    |
| Apple                   | 3         | 1.7%    |
| Unknown                 | 2         | 1.14%   |
| Philips                 | 2         | 1.14%   |
| PANDA                   | 2         | 1.14%   |
| NEC Computers           | 2         | 1.14%   |
| Chi Mei Optoelectronics | 2         | 1.14%   |
| ___                     | 1         | 0.57%   |
| ViewSonic               | 1         | 0.57%   |
| Toshiba                 | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| MSI                     | 1         | 0.57%   |
| JRY                     | 1         | 0.57%   |
| Iiyama                  | 1         | 0.57%   |
| GKK                     | 1         | 0.57%   |
| CSO                     | 1         | 0.57%   |
| Unknown                 | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AOC 24E1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3         | 1.66%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.1%    |
| Ancor Communications LCD Monitor MG248 1920x1080                      | 2         | 1.1%    |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.55%   |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch                | 1         | 0.55%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.55%   |
| Unknown LCD Monitor HIC 3200x1080                                     | 1         | 0.55%   |
| Toshiba Internal LCD TOS5091 1366x768 340x190mm 15.3-inch             | 1         | 0.55%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.55%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.55%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.55%   |
| SHARP LCD Monitor HDMI 1920x1080                                      | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch  | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch   | 1         | 0.55%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.55%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.55%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1         | 0.55%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch     | 1         | 0.55%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 1         | 0.55%   |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch      | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.55%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.55%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch     | 1         | 0.55%   |
| Philips PHL 276E6 PHLC0FA 1920x1080 598x336mm 27.0-inch               | 1         | 0.55%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                 | 1         | 0.55%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.55%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.55%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                           | 1         | 0.55%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch            | 1         | 0.55%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                       | 1         | 0.55%   |
| LG Electronics LCD Monitor W1952 1440x900                             | 1         | 0.55%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3440x1440                     | 1         | 0.55%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                      | 1         | 0.55%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 1         | 0.55%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD05B4 1920x1080 294x165mm 13.3-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.55%   |
| LG Display LCD Monitor LGD0404 1366x768 277x156mm 12.5-inch           | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 43.71%  |
| 1366x768 (WXGA)    | 36        | 21.56%  |
| 1600x900 (HD+)     | 10        | 5.99%   |
| 2560x1440 (QHD)    | 8         | 4.79%   |
| 3840x2160 (4K)     | 6         | 3.59%   |
| 1440x900 (WXGA+)   | 6         | 3.59%   |
| 1280x1024 (SXGA)   | 5         | 2.99%   |
| Unknown            | 4         | 2.4%    |
| 2560x1080          | 3         | 1.8%    |
| 1280x800 (WXGA)    | 3         | 1.8%    |
| 1680x1050 (WSXGA+) | 2         | 1.2%    |
| 1360x768           | 2         | 1.2%    |
| 4480x1440          | 1         | 0.6%    |
| 3840x1080          | 1         | 0.6%    |
| 3440x1440          | 1         | 0.6%    |
| 3200x1080          | 1         | 0.6%    |
| 2560x1600          | 1         | 0.6%    |
| 2256x1504          | 1         | 0.6%    |
| 1920x1200 (WUXGA)  | 1         | 0.6%    |
| 1152x864           | 1         | 0.6%    |
| 1024x768 (XGA)     | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 30.99%  |
| 13      | 22        | 12.87%  |
| Unknown | 18        | 10.53%  |
| 24      | 12        | 7.02%   |
| 27      | 10        | 5.85%   |
| 14      | 9         | 5.26%   |
| 23      | 8         | 4.68%   |
| 21      | 8         | 4.68%   |
| 17      | 8         | 4.68%   |
| 18      | 7         | 4.09%   |
| 20      | 3         | 1.75%   |
| 34      | 2         | 1.17%   |
| 19      | 2         | 1.17%   |
| 12      | 2         | 1.17%   |
| 72      | 1         | 0.58%   |
| 40      | 1         | 0.58%   |
| 31      | 1         | 0.58%   |
| 29      | 1         | 0.58%   |
| 25      | 1         | 0.58%   |
| 22      | 1         | 0.58%   |
| 11      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 70        | 41.42%  |
| 501-600     | 28        | 16.57%  |
| 401-500     | 20        | 11.83%  |
| Unknown     | 18        | 10.65%  |
| 201-300     | 15        | 8.88%   |
| 351-400     | 11        | 6.51%   |
| 601-700     | 3         | 1.78%   |
| 701-800     | 2         | 1.18%   |
| 801-900     | 1         | 0.59%   |
| 1501-2000   | 1         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 116       | 74.36%  |
| Unknown | 17        | 10.9%   |
| 16/10   | 13        | 8.33%   |
| 21/9    | 3         | 1.92%   |
| 5/4     | 2         | 1.28%   |
| 4/3     | 2         | 1.28%   |
| 3/2     | 2         | 1.28%   |
| 6/5     | 1         | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 29.82%  |
| 201-250        | 25        | 14.62%  |
| 81-90          | 21        | 12.28%  |
| Unknown        | 18        | 10.53%  |
| 301-350        | 11        | 6.43%   |
| 71-80          | 10        | 5.85%   |
| 151-200        | 8         | 4.68%   |
| 121-130        | 7         | 4.09%   |
| 141-150        | 5         | 2.92%   |
| 251-300        | 4         | 2.34%   |
| 351-500        | 3         | 1.75%   |
| 61-70          | 2         | 1.17%   |
| More than 1000 | 1         | 0.58%   |
| 51-60          | 1         | 0.58%   |
| 131-140        | 1         | 0.58%   |
| 111-120        | 1         | 0.58%   |
| 501-1000       | 1         | 0.58%   |
| 91-100         | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 49        | 29.52%  |
| 101-120       | 42        | 25.3%   |
| 121-160       | 39        | 23.49%  |
| Unknown       | 18        | 10.84%  |
| 161-240       | 13        | 7.83%   |
| More than 240 | 4         | 2.41%   |
| 1-50          | 1         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 123       | 79.87%  |
| 2     | 29        | 18.83%  |
| 3     | 2         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 86        | 35.98%  |
| Intel                    | 72        | 30.13%  |
| Qualcomm Atheros         | 33        | 13.81%  |
| Broadcom                 | 13        | 5.44%   |
| TP-Link                  | 3         | 1.26%   |
| Ralink Technology        | 3         | 1.26%   |
| MediaTek                 | 3         | 1.26%   |
| Marvell Technology Group | 3         | 1.26%   |
| Xiaomi                   | 2         | 0.84%   |
| Ralink                   | 2         | 0.84%   |
| Dell                     | 2         | 0.84%   |
| Sierra Wireless          | 1         | 0.42%   |
| Samsung Electronics      | 1         | 0.42%   |
| Qualcomm                 | 1         | 0.42%   |
| OnePlus                  | 1         | 0.42%   |
| Nvidia                   | 1         | 0.42%   |
| NetGear                  | 1         | 0.42%   |
| Microchip Technology     | 1         | 0.42%   |
| Linksys                  | 1         | 0.42%   |
| Lenovo                   | 1         | 0.42%   |
| Jolla Oy                 | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| Hewlett-Packard          | 1         | 0.42%   |
| D-Link System            | 1         | 0.42%   |
| Broadcom Limited         | 1         | 0.42%   |
| Belkin Components        | 1         | 0.42%   |
| Aquantia                 | 1         | 0.42%   |
| Android                  | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 23.13%  |
| Intel Wireless 8265 / 8275                                        | 9         | 3.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.85%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.85%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.78%   |
| Intel Wireless 7260                                               | 5         | 1.78%   |
| Intel Wireless 7265                                               | 4         | 1.42%   |
| Intel Wireless 3165                                               | 4         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.07%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.71%   |
| Realtek RTL8187 Wireless Adapter                                  | 2         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.71%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 2         | 0.71%   |
| Intel Wireless 8260                                               | 2         | 0.71%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.71%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.71%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.71%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 0.71%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 0.36%   |
| Sierra Wireless EM7305                                            | 1         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.36%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 0.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.36%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.36%   |
| Realtek 802.11ac NIC                                              | 1         | 0.36%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.36%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.36%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.36%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.36%   |
| Qualcomm Mi A1                                                    | 1         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 43.94%  |
| Qualcomm Atheros      | 29        | 21.97%  |
| Realtek Semiconductor | 17        | 12.88%  |
| Broadcom              | 10        | 7.58%   |
| Ralink Technology     | 3         | 2.27%   |
| MediaTek              | 3         | 2.27%   |
| TP-Link               | 2         | 1.52%   |
| Ralink                | 2         | 1.52%   |
| Sierra Wireless       | 1         | 0.76%   |
| NetGear               | 1         | 0.76%   |
| Linksys               | 1         | 0.76%   |
| Hewlett-Packard       | 1         | 0.76%   |
| Dell                  | 1         | 0.76%   |
| D-Link System         | 1         | 0.76%   |
| Broadcom Limited      | 1         | 0.76%   |
| Belkin Components     | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 9         | 6.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 8         | 6.06%   |
| Intel Wi-Fi 6 AX200                                                        | 7         | 5.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 6         | 4.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 5         | 3.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 5         | 3.79%   |
| Intel Wireless 7260                                                        | 5         | 3.79%   |
| Intel Wireless 7265                                                        | 4         | 3.03%   |
| Intel Wireless 3165                                                        | 4         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 4         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 3         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 3         | 2.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2         | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 2         | 1.52%   |
| Realtek RTL8187 Wireless Adapter                                           | 2         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.52%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                           | 2         | 1.52%   |
| Intel Wireless 8260                                                        | 2         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                        | 2         | 1.52%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                              | 2         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 2         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                              | 2         | 1.52%   |
| Broadcom BCM4311 802.11b/g WLAN                                            | 2         | 1.52%   |
| Sierra Wireless EM7305                                                     | 1         | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                            | 1         | 0.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1         | 0.76%   |
| Realtek 802.11ac NIC                                                       | 1         | 0.76%   |
| Ralink RT5372 Wireless Adapter                                             | 1         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.76%   |
| NetGear A6150                                                              | 1         | 0.76%   |
| MediaTek Wireless                                                          | 1         | 0.76%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                              | 1         | 0.76%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 0.76%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                        | 1         | 0.76%   |
| Intel Wireless-AC 9260                                                     | 1         | 0.76%   |
| Intel Wireless 3160                                                        | 1         | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1         | 0.76%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                            | 1         | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 1         | 0.76%   |
| Intel Centrino Wireless-N 2230                                             | 1         | 0.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                             | 1         | 0.76%   |
| Intel Centrino Advanced-N 6200                                             | 1         | 0.76%   |
| HP lt4112 Gobi 4G Module Network Device                                    | 1         | 0.76%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 1         | 0.76%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 54.55%  |
| Intel                    | 40        | 27.97%  |
| Qualcomm Atheros         | 6         | 4.2%    |
| Broadcom                 | 5         | 3.5%    |
| Marvell Technology Group | 3         | 2.1%    |
| Xiaomi                   | 2         | 1.4%    |
| TP-Link                  | 1         | 0.7%    |
| Samsung Electronics      | 1         | 0.7%    |
| Qualcomm                 | 1         | 0.7%    |
| Nvidia                   | 1         | 0.7%    |
| Lenovo                   | 1         | 0.7%    |
| Jolla Oy                 | 1         | 0.7%    |
| Huawei Technologies      | 1         | 0.7%    |
| Aquantia                 | 1         | 0.7%    |
| Android                  | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 65        | 44.52%  |
| Intel I211 Gigabit Network Connection                                          | 8         | 5.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 4.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.05%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.05%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 2.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.37%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.37%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.68%   |
| Qualcomm Mi A1                                                                 | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.68%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.68%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.68%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.68%   |
| Lenovo Thinkpad USB LAN                                                        | 1         | 0.68%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 0.68%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.68%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.68%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.68%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.68%   |
| Intel 82578DC Gigabit Network Connection                                       | 1         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.68%   |
| Huawei JNY-LX1                                                                 | 1         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 0.68%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                        | 1         | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 0.68%   |
| Android Android                                                                | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 133       | 51.95%  |
| WiFi     | 120       | 46.88%  |
| Modem    | 2         | 0.78%   |
| Unknown  | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 51.2%   |
| Ethernet | 102       | 48.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 89        | 58.17%  |
| 1     | 61        | 39.87%  |
| 3     | 2         | 1.31%   |
| 0     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 88.31%  |
| Yes  | 18        | 11.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 46.08%  |
| Qualcomm Atheros Communications | 9         | 8.82%   |
| Lite-On Technology              | 9         | 8.82%   |
| Cambridge Silicon Radio         | 8         | 7.84%   |
| Broadcom                        | 7         | 6.86%   |
| Realtek Semiconductor           | 6         | 5.88%   |
| Apple                           | 4         | 3.92%   |
| IMC Networks                    | 3         | 2.94%   |
| Foxconn / Hon Hai               | 2         | 1.96%   |
| ASUSTek Computer                | 2         | 1.96%   |
| Toshiba                         | 1         | 0.98%   |
| Ralink                          | 1         | 0.98%   |
| MediaTek                        | 1         | 0.98%   |
| Hewlett-Packard                 | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 23.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 7.84%   |
| Intel AX200 Bluetooth                                                               | 7         | 6.86%   |
| Lite-On Bluetooth Device                                                            | 6         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.94%   |
| Intel Bluetooth Device                                                              | 3         | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.96%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.96%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 1.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.96%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.96%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.96%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.98%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.98%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.98%   |
| MediaTek Wireless_Device                                                            | 1         | 0.98%   |
| Lite-On Wireless_Device                                                             | 1         | 0.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.98%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.98%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.98%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.98%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.98%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.98%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 0.98%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.98%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.98%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.98%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.98%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 1         | 0.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.98%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.98%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 114       | 52.05%  |
| AMD                     | 46        | 21%     |
| Nvidia                  | 38        | 17.35%  |
| Blue Microphones        | 4         | 1.83%   |
| Logitech                | 2         | 0.91%   |
| C-Media Electronics     | 2         | 0.91%   |
| Yamaha                  | 1         | 0.46%   |
| Tenx Technology         | 1         | 0.46%   |
| SteelSeries ApS         | 1         | 0.46%   |
| SAVITECH                | 1         | 0.46%   |
| Samsung Electronics     | 1         | 0.46%   |
| RME                     | 1         | 0.46%   |
| JMTek                   | 1         | 0.46%   |
| GYROCOM C&C             | 1         | 0.46%   |
| Creative Technology     | 1         | 0.46%   |
| Creative Labs           | 1         | 0.46%   |
| Cooler Master           | 1         | 0.46%   |
| Conexant Systems        | 1         | 0.46%   |
| BEHRINGER International | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 4.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 3.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.31%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.31%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.92%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.15%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.15%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.15%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 1.15%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.77%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.77%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.77%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 0.77%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 0.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 0.77%   |
| Yamaha Steinberg UR44                                                      | 1         | 0.38%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.38%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1         | 0.38%   |
| SAVITECH ODAC-revB                                                         | 1         | 0.38%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.38%   |
| RME Babyface Pro (71964113)                                                | 1         | 0.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.38%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.38%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.38%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.38%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.38%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 19.72%  |
| SK Hynix            | 10        | 14.08%  |
| Unknown             | 7         | 9.86%   |
| Corsair             | 7         | 9.86%   |
| A-DATA Technology   | 6         | 8.45%   |
| Micron Technology   | 5         | 7.04%   |
| Kingston            | 5         | 7.04%   |
| Crucial             | 5         | 7.04%   |
| Nanya Technology    | 3         | 4.23%   |
| Ramaxel Technology  | 2         | 2.82%   |
| G.Skill             | 2         | 2.82%   |
| Elpida              | 2         | 2.82%   |
| Transcend           | 1         | 1.41%   |
| Team                | 1         | 1.41%   |
| Patriot             | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 2.67%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 2.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 2         | 2.67%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1867MT/s                   | 1         | 1.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                     | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                     | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.33%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                | 1         | 1.33%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 1.33%   |
| SK Hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.33%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.33%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.33%   |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.33%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.33%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.33%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 1         | 1.33%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.33%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.33%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.33%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 1.33%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s              | 1         | 1.33%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.33%   |
| Micron RAM Module 4096MB SODIMM DDR3 1867MT/s                    | 1         | 1.33%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 1.33%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.33%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| Kingston RAM HP24D4S7S8MBP-8 8192MB SODIMM DDR4 2400MT/s         | 1         | 1.33%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Kingston RAM 99U5663-003.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 1.33%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.33%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.33%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 1         | 1.33%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s               | 1         | 1.33%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Crucial RAM CT8G4SFS824A.C8FE 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.33%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Crucial RAM CT32G4SFD832A.M16FB 32GB SODIMM DDR4 3200MT/s        | 1         | 1.33%   |
| Crucial RAM CB4GS2400.M8E 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.33%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s        | 1         | 1.33%   |
| Corsair RAM CMY8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s              | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 49.15%  |
| DDR3   | 21        | 35.59%  |
| LPDDR3 | 4         | 6.78%   |
| DDR2   | 2         | 3.39%   |
| SDRAM  | 1         | 1.69%   |
| LPDDR4 | 1         | 1.69%   |
| DDR    | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 68.97%  |
| DIMM         | 14        | 24.14%  |
| Row Of Chips | 4         | 6.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 42.86%  |
| 4096  | 21        | 33.33%  |
| 2048  | 7         | 11.11%  |
| 16384 | 5         | 7.94%   |
| 32768 | 2         | 3.17%   |
| 1024  | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 15        | 22.39%  |
| 2667    | 9         | 13.43%  |
| 2400    | 8         | 11.94%  |
| 3200    | 7         | 10.45%  |
| 2133    | 7         | 10.45%  |
| 3466    | 2         | 2.99%   |
| 3266    | 2         | 2.99%   |
| 1334    | 2         | 2.99%   |
| 1333    | 2         | 2.99%   |
| Unknown | 2         | 2.99%   |
| 4267    | 1         | 1.49%   |
| 3866    | 1         | 1.49%   |
| 3600    | 1         | 1.49%   |
| 3000    | 1         | 1.49%   |
| 2048    | 1         | 1.49%   |
| 1867    | 1         | 1.49%   |
| 1800    | 1         | 1.49%   |
| 1067    | 1         | 1.49%   |
| 1066    | 1         | 1.49%   |
| 800     | 1         | 1.49%   |
| 667     | 1         | 1.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP DeskJet 3630 series | 1         | 25%     |
| Canon LBP7010C/7018C   | 1         | 25%     |
| Canon G3000 series     | 1         | 25%     |
| Brother MFC-9330CDW    | 1         | 25%     |

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
| Chicony Electronics                    | 23        | 21.7%   |
| Logitech                               | 11        | 10.38%  |
| Microdia                               | 10        | 9.43%   |
| Realtek Semiconductor                  | 9         | 8.49%   |
| IMC Networks                           | 8         | 7.55%   |
| Quanta                                 | 6         | 5.66%   |
| Acer                                   | 5         | 4.72%   |
| Suyin                                  | 4         | 3.77%   |
| Sunplus Innovation Technology          | 4         | 3.77%   |
| Lite-On Technology                     | 4         | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.83%   |
| Apple                                  | 3         | 2.83%   |
| Microsoft                              | 2         | 1.89%   |
| Lenovo                                 | 2         | 1.89%   |
| Importek                               | 2         | 1.89%   |
| Unknown                                | 1         | 0.94%   |
| Syntek                                 | 1         | 0.94%   |
| Silicon Motion                         | 1         | 0.94%   |
| Samsung Electronics                    | 1         | 0.94%   |
| MACROSILICON                           | 1         | 0.94%   |
| Luxvisions Innotech Limited            | 1         | 0.94%   |
| LG Electronics                         | 1         | 0.94%   |
| Intel                                  | 1         | 0.94%   |
| Hewlett-Packard                        | 1         | 0.94%   |
| A4Tech                                 | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony HD WebCam                         | 6         | 5.56%   |
| Chicony Integrated Camera                 | 4         | 3.7%    |
| Microdia Integrated_Webcam_HD             | 3         | 2.78%   |
| Logitech HD Pro Webcam C920               | 3         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam         | 3         | 2.78%   |
| Suyin HP TrueVision HD Integrated Webcam  | 2         | 1.85%   |
| Sunplus Integrated_Webcam_HD              | 2         | 1.85%   |
| Realtek Integrated Webcam_HD              | 2         | 1.85%   |
| Realtek HD WebCam                         | 2         | 1.85%   |
| Quanta HD User Facing                     | 2         | 1.85%   |
| Microdia Camera                           | 2         | 1.85%   |
| Logitech Webcam C270                      | 2         | 1.85%   |
| Logitech Logitech Webcam C160             | 2         | 1.85%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 2         | 1.85%   |
| IMC Networks Integrated Camera            | 2         | 1.85%   |
| Chicony VGA WebCam                        | 2         | 1.85%   |
| Chicony EasyCamera                        | 2         | 1.85%   |
| Apple FaceTime HD Camera (Built-in)       | 2         | 1.85%   |
| Unknown ATIV VGA CAMERA                   | 1         | 0.93%   |
| Syntek USB2.0 Camera                      | 1         | 0.93%   |
| Suyin HP TrueVision FHD RGB-IR            | 1         | 0.93%   |
| Suyin 1.3M HD WebCam                      | 1         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_HD       | 1         | 0.93%   |
| Sunplus Laptop Integrated WebCam HD       | 1         | 0.93%   |
| Silicon Motion WebCam SC-10HDD12636N      | 1         | 0.93%   |
| Samsung Galaxy A5 (MTP)                   | 1         | 0.93%   |
| Realtek Laptop Camera                     | 1         | 0.93%   |
| Realtek Integrated Webcam HD              | 1         | 0.93%   |
| Realtek Integrated Webcam                 | 1         | 0.93%   |
| Realtek Integrated Camera                 | 1         | 0.93%   |
| Realtek HP Truevision HD                  | 1         | 0.93%   |
| Quanta VGA WebCam                         | 1         | 0.93%   |
| Quanta USB2.0 HD UVC WebCam               | 1         | 0.93%   |
| Quanta HP Wide Vision HD Camera           | 1         | 0.93%   |
| Quanta HP TrueVision HD Webcam            | 1         | 0.93%   |
| Microsoft Xbox NUI Camera                 | 1         | 0.93%   |
| Microsoft LifeCam HD-3000                 | 1         | 0.93%   |
| Microdia Webcam                           | 1         | 0.93%   |
| Microdia USB 2.0 Camera                   | 1         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_0.3M    | 1         | 0.93%   |
| Microdia Integrated Webcam HD             | 1         | 0.93%   |
| Microdia Dell Laptop Integrated Webcam HD | 1         | 0.93%   |
| MACROSILICON ShadowCast                   | 1         | 0.93%   |
| Luxvisions Innotech Limited HP HD Camera  | 1         | 0.93%   |
| Logitech Webcam C310                      | 1         | 0.93%   |
| Logitech StreamCam                        | 1         | 0.93%   |
| Logitech C922 Pro Stream Webcam           | 1         | 0.93%   |
| Logitech C920 PRO HD Webcam               | 1         | 0.93%   |
| Lite-On Integrated Camera                 | 1         | 0.93%   |
| Lite-On HP Wide Vision HD Camera          | 1         | 0.93%   |
| Lite-On HP IR Camera                      | 1         | 0.93%   |
| Lite-On HP HD Webcam                      | 1         | 0.93%   |
| Lite-On HP HD Camera                      | 1         | 0.93%   |
| LG Optimus (Various Models) MTP Mode      | 1         | 0.93%   |
| Lenovo UVC Camera                         | 1         | 0.93%   |
| Lenovo Integrated Webcam [R5U877]         | 1         | 0.93%   |
| Intel RealSense 3D Camera (Front F200)    | 1         | 0.93%   |
| Importek TOSHIBA Web Camera - HD          | 1         | 0.93%   |
| Importek Laptop Integrated Webcam         | 1         | 0.93%   |
| IMC Networks UVC VGA Webcam               | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 10        | 47.62%  |
| Synaptics             | 3         | 14.29%  |
| Upek                  | 2         | 9.52%   |
| LighTuning Technology | 2         | 9.52%   |
| Elan Microelectronics | 2         | 9.52%   |
| AuthenTec             | 2         | 9.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 14.29%  |
| Validity Sensors Fingerprint scanner                   | 2         | 9.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 9.52%   |
| Elan ELAN:Fingerprint                                  | 2         | 9.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.76%   |
| Validity Sensors VFS491                                | 1         | 4.76%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.76%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.76%   |
| Synaptics  WBDI                                        | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.76%   |
| AuthenTec AES2810                                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 25%     |
| Alcor Micro | 2         | 25%     |
| O2 Micro    | 1         | 12.5%   |
| Lenovo      | 1         | 12.5%   |
| Broadcom    | 1         | 12.5%   |
| BIT4ID      | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 12.5%   |
| BIT4ID miniLector EVO                                      | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 108       | 70.59%  |
| 1     | 32        | 20.92%  |
| 2     | 12        | 7.84%   |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 21        | 35%     |
| Net/wireless          | 15        | 25%     |
| Chipcard              | 7         | 11.67%  |
| Multimedia controller | 4         | 6.67%   |
| Graphics card         | 4         | 6.67%   |
| Unassigned class      | 2         | 3.33%   |
| Camera                | 2         | 3.33%   |
| Tv card               | 1         | 1.67%   |
| Storage               | 1         | 1.67%   |
| Network               | 1         | 1.67%   |
| Net/ethernet          | 1         | 1.67%   |
| Bluetooth             | 1         | 1.67%   |


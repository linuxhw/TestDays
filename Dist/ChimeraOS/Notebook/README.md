ChimeraOS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [638c1123d0](https://linux-hardware.org/?probe=638c1123d0) | Dec 05, 2024 |
| AYANEO        | AB05-AMD                    | [60390b6f89](https://linux-hardware.org/?probe=60390b6f89) | Nov 16, 2024 |
| HP            | Victus by Gaming Laptop ... | [a1d36dc841](https://linux-hardware.org/?probe=a1d36dc841) | Nov 04, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [8659fd177c](https://linux-hardware.org/?probe=8659fd177c) | Oct 31, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [82ab276d55](https://linux-hardware.org/?probe=82ab276d55) | Oct 31, 2024 |
| HUAWEI        | BOD-WXX9                    | [353cba650d](https://linux-hardware.org/?probe=353cba650d) | Oct 19, 2024 |
| AYANEO        | AB05-AMD                    | [a9f0ebcf7c](https://linux-hardware.org/?probe=a9f0ebcf7c) | Oct 07, 2024 |
| Dell          | Latitude 7420               | [7eb7fea444](https://linux-hardware.org/?probe=7eb7fea444) | Sep 20, 2024 |
| Lenovo        | ThinkPad X230 23255J6       | [e754879569](https://linux-hardware.org/?probe=e754879569) | Sep 15, 2024 |
| HUAWEI        | NBM-WXX9                    | [4445b6689d](https://linux-hardware.org/?probe=4445b6689d) | Sep 08, 2024 |
| ONE-NETBOO... | ONEXPLAYER X1 mini          | [6b39950dc6](https://linux-hardware.org/?probe=6b39950dc6) | Aug 28, 2024 |
| HP            | Victus by Gaming Laptop ... | [ed06f1be24](https://linux-hardware.org/?probe=ed06f1be24) | Aug 17, 2024 |
| Apple         | MacBookPro11,4              | [dfede07c9d](https://linux-hardware.org/?probe=dfede07c9d) | Aug 16, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a7190fb979](https://linux-hardware.org/?probe=a7190fb979) | Jul 31, 2024 |
| ASRock        | B550M Pro4                  | [71d8153a82](https://linux-hardware.org/?probe=71d8153a82) | Jun 29, 2024 |
| MSI           | A520M-A PRO                 | [3df6b0c991](https://linux-hardware.org/?probe=3df6b0c991) | Jun 25, 2024 |
| MSI           | GP60 2QF                    | [40ac6a147a](https://linux-hardware.org/?probe=40ac6a147a) | Jun 13, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [326ee7fd03](https://linux-hardware.org/?probe=326ee7fd03) | Jun 08, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [1886617675](https://linux-hardware.org/?probe=1886617675) | May 27, 2024 |
| Micro Comp... | Uranus Series               | [e1a6fe56df](https://linux-hardware.org/?probe=e1a6fe56df) | May 19, 2024 |
| GPD           | G1618-03                    | [9e3bd9bdf5](https://linux-hardware.org/?probe=9e3bd9bdf5) | May 16, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| GPD           | G1618-04                    | [2c1da6a68d](https://linux-hardware.org/?probe=2c1da6a68d) | Apr 26, 2024 |
| GPD           | P2 MAX                      | [8e53b3ed39](https://linux-hardware.org/?probe=8e53b3ed39) | Apr 01, 2024 |
| ASUSTek       | PRIME B550M-A               | [e5fc501332](https://linux-hardware.org/?probe=e5fc501332) | Mar 31, 2024 |
| Acer          | Aspire E5-575G              | [83b5323b19](https://linux-hardware.org/?probe=83b5323b19) | Mar 18, 2024 |
| Dell          | Precision 5570              | [65270db170](https://linux-hardware.org/?probe=65270db170) | Mar 13, 2024 |
| ASUSTek       | PRIME B550M-A               | [ed405fd8da](https://linux-hardware.org/?probe=ed405fd8da) | Mar 11, 2024 |
| ASUSTek       | G551JX                      | [8a875afd94](https://linux-hardware.org/?probe=8a875afd94) | Mar 08, 2024 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [9fc35ed4b6](https://linux-hardware.org/?probe=9fc35ed4b6) | Mar 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [df560f1f39](https://linux-hardware.org/?probe=df560f1f39) | Mar 03, 2024 |
| Acer          | Aspire V3-772G              | [e9bc1c5d68](https://linux-hardware.org/?probe=e9bc1c5d68) | Jan 19, 2024 |
| Dell          | Latitude 7310               | [664667c69b](https://linux-hardware.org/?probe=664667c69b) | Jan 19, 2024 |
| HP            | Pavilion 15                 | [dad46e573f](https://linux-hardware.org/?probe=dad46e573f) | Jan 07, 2024 |
| ASUSTek       | G74Sx                       | [0933c174aa](https://linux-hardware.org/?probe=0933c174aa) | Dec 30, 2023 |
| Sony          | SVS13A25PLB                 | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP            | ProBook 4540s               | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| HP            | ProBook 4540s               | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Valve         | Galileo                     | [355d2e1a38](https://linux-hardware.org/?probe=355d2e1a38) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0018284858](https://linux-hardware.org/?probe=0018284858) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f65efa02b6](https://linux-hardware.org/?probe=f65efa02b6) | Dec 16, 2023 |
| Notebook      | P15SM-A/SM1-A               | [f7c8033eef](https://linux-hardware.org/?probe=f7c8033eef) | Dec 06, 2023 |
| Dell          | Latitude E5540              | [33e3a21810](https://linux-hardware.org/?probe=33e3a21810) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | [7cb8811992](https://linux-hardware.org/?probe=7cb8811992) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | [9d2fdb067c](https://linux-hardware.org/?probe=9d2fdb067c) | Nov 25, 2023 |
| Acer          | Aspire V3-772G              | [742d987926](https://linux-hardware.org/?probe=742d987926) | Nov 21, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | [4e71e8e7b7](https://linux-hardware.org/?probe=4e71e8e7b7) | Nov 20, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [669eb1edcb](https://linux-hardware.org/?probe=669eb1edcb) | Nov 16, 2023 |
| Dell          | G15 5510                    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| Dell          | Precision 7520              | [ab5ec5ba37](https://linux-hardware.org/?probe=ab5ec5ba37) | Oct 22, 2023 |
| Acer          | Aspire VX5-591G             | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11820fb443](https://linux-hardware.org/?probe=11820fb443) | Oct 10, 2023 |
| Alienware     | 17 R2                       | [6ad5704e29](https://linux-hardware.org/?probe=6ad5704e29) | Sep 21, 2023 |
| Alienware     | 17 R2                       | [76bf895d62](https://linux-hardware.org/?probe=76bf895d62) | Sep 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [6192c839f5](https://linux-hardware.org/?probe=6192c839f5) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [3429c55014](https://linux-hardware.org/?probe=3429c55014) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [72fb0f052e](https://linux-hardware.org/?probe=72fb0f052e) | Sep 06, 2023 |
| Dell          | Latitude 3590               | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Acer          | Nitro AN515-57              | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| Anbernic      | Win600                      | [32213b8d3b](https://linux-hardware.org/?probe=32213b8d3b) | Aug 13, 2023 |
| GPD           | P2 MAX                      | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| Acer          | Aspire A715-42G             | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| AMI           | Unknown                     | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Google        | Snappy                      | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Acer          | Nitro AN515-51              | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| MSI           | CX62 6QD                    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| ASUSTek       | K45VM                       | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| ChimeraOS 44-1 | 13        | 16.25%  |
| ChimeraOS 43-1 | 12        | 15%     |
| ChimeraOS 45-1 | 8         | 10%     |
| ChimeraOS 39   | 8         | 10%     |
| ChimeraOS 45   | 7         | 8.75%   |
| ChimeraOS 42   | 7         | 8.75%   |
| ChimeraOS 46-2 | 6         | 7.5%    |
| ChimeraOS 41   | 5         | 6.25%   |
| ChimeraOS      | 4         | 5%      |
| ChimeraOS 44   | 2         | 2.5%    |
| ChimeraOS 38   | 2         | 2.5%    |
| ChimeraOS 47-7 | 1         | 1.25%   |
| ChimeraOS 47-4 | 1         | 1.25%   |
| ChimeraOS 47-1 | 1         | 1.25%   |
| ChimeraOS 46-8 | 1         | 1.25%   |
| ChimeraOS 46   | 1         | 1.25%   |
| ChimeraOS 43   | 1         | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 80        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 6.5.6-chos1-chimeraos-1     | 13        | 16.05%  |
| 6.3.9-chimeraos-1           | 13        | 16.05%  |
| 6.6.10-chos1-chimeraos-2    | 12        | 14.81%  |
| 6.1.11-arch1-1              | 8         | 9.88%   |
| 6.1.27-1-lts                | 7         | 8.64%   |
| 6.9.12-chos7-chimeraos-1    | 6         | 7.41%   |
| 6.1.21-1-lts                | 5         | 6.17%   |
| 6.5.3-chos1-chimeraos-1     | 2         | 2.47%   |
| 6.1.1-arch1-1               | 2         | 2.47%   |
| 6.9.9-chos1-chimeraos-1     | 1         | 1.23%   |
| 6.9.3-sk-chos3-chimeraos-1  | 1         | 1.23%   |
| 6.8.2-0-generic             | 1         | 1.23%   |
| 6.6.7-chos4-chimeraos-1     | 1         | 1.23%   |
| 6.6.51-0-generic            | 1         | 1.23%   |
| 6.6.37-0-generic            | 1         | 1.23%   |
| 6.6.1-chos3-chimeraos-3     | 1         | 1.23%   |
| 6.6.1-chos3-chimeraos-1     | 1         | 1.23%   |
| 6.4.9-0-generic             | 1         | 1.23%   |
| 6.11.4-0-generic            | 1         | 1.23%   |
| 6.11.1-sk-chos1-chimeraos-1 | 1         | 1.23%   |
| 6.10.8-sk-chos1-chimeraos-1 | 1         | 1.23%   |
| 6.10.3-arch1-chimeraos-1    | 1         | 1.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.6   | 13        | 16.05%  |
| 6.3.9   | 13        | 16.05%  |
| 6.6.10  | 12        | 14.81%  |
| 6.1.11  | 8         | 9.88%   |
| 6.1.27  | 7         | 8.64%   |
| 6.9.12  | 6         | 7.41%   |
| 6.1.21  | 5         | 6.17%   |
| 6.6.1   | 2         | 2.47%   |
| 6.5.3   | 2         | 2.47%   |
| 6.1.1   | 2         | 2.47%   |
| 6.9.9   | 1         | 1.23%   |
| 6.9.3   | 1         | 1.23%   |
| 6.8.2   | 1         | 1.23%   |
| 6.6.7   | 1         | 1.23%   |
| 6.6.51  | 1         | 1.23%   |
| 6.6.37  | 1         | 1.23%   |
| 6.4.9   | 1         | 1.23%   |
| 6.11.4  | 1         | 1.23%   |
| 6.11.1  | 1         | 1.23%   |
| 6.10.8  | 1         | 1.23%   |
| 6.10.3  | 1         | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 27.16%  |
| 6.6     | 17        | 20.99%  |
| 6.5     | 15        | 18.52%  |
| 6.3     | 13        | 16.05%  |
| 6.9     | 8         | 9.88%   |
| 6.11    | 2         | 2.47%   |
| 6.10    | 2         | 2.47%   |
| 6.8     | 1         | 1.23%   |
| 6.4     | 1         | 1.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 75        | 93.75%  |
| Unknown | 3         | 3.75%   |
| KDE6    | 2         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 73        | 91.25%  |
| X11     | 5         | 6.25%   |
| Unknown | 2         | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 57        | 71.25%  |
| zh_CN   | 5         | 6.25%   |
| es_ES   | 4         | 5%      |
| pt_BR   | 3         | 3.75%   |
| fr_FR   | 3         | 3.75%   |
| Unknown | 3         | 3.75%   |
| it_IT   | 2         | 2.5%    |
| fr_CA   | 1         | 1.25%   |
| de_DE   | 1         | 1.25%   |
| C       | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 80        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 76        | 95%     |
| Ext4  | 2         | 2.5%    |
| Xfs   | 1         | 1.25%   |
| Tmpfs | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 96.25%  |
| GPT     | 3         | 3.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 98.75%  |
| Yes       | 1         | 1.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 98.75%  |
| Yes       | 1         | 1.25%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| ASUSTek Computer                 | 16        | 20%     |
| Acer                             | 9         | 11.25%  |
| Lenovo                           | 8         | 10%     |
| Hewlett-Packard                  | 8         | 10%     |
| Dell                             | 8         | 10%     |
| ONE-NETBOOK                      | 5         | 6.25%   |
| MSI                              | 5         | 6.25%   |
| GPD                              | 3         | 3.75%   |
| Razer                            | 2         | 2.5%    |
| HUAWEI                           | 2         | 2.5%    |
| AYANEO                           | 2         | 2.5%    |
| Valve                            | 1         | 1.25%   |
| Sony                             | 1         | 1.25%   |
| Notebook                         | 1         | 1.25%   |
| Micro Electronics                | 1         | 1.25%   |
| Micro Computer (HK) Tech Limited | 1         | 1.25%   |
| Google                           | 1         | 1.25%   |
| Gigabyte Technology              | 1         | 1.25%   |
| ASRock                           | 1         | 1.25%   |
| Apple                            | 1         | 1.25%   |
| Anbernic                         | 1         | 1.25%   |
| AMI                              | 1         | 1.25%   |
| Alienware                        | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 PRO ARP23P         | 2         | 2.5%    |
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 2.5%    |
| AYANEO AIR Plus                             | 2         | 2.5%    |
| Acer Aspire V3-772G                         | 2         | 2.5%    |
| Unknown                                     | 2         | 2.5%    |
| Valve Galileo                               | 1         | 1.25%   |
| Sony SVS13A25PLB                            | 1         | 1.25%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 1.25%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 1.25%   |
| ONE-NETBOOK ONEXPLAYER X1 mini              | 1         | 1.25%   |
| Notebook P15SM-A/SM1-A                      | 1         | 1.25%   |
| MSI MS-7C96                                 | 1         | 1.25%   |
| MSI MS-7C91                                 | 1         | 1.25%   |
| MSI GP60 2QF                                | 1         | 1.25%   |
| MSI GE75 Raider 10SF                        | 1         | 1.25%   |
| MSI CX62 6QD                                | 1         | 1.25%   |
| Micro MG-VCP17I-3070                        | 1         | 1.25%   |
| Micro (HK) Tech Limited Uranus Series       | 1         | 1.25%   |
| Lenovo Y50-70 20378                         | 1         | 1.25%   |
| Lenovo ThinkPad X230 23255J6                | 1         | 1.25%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 1.25%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 1.25%   |
| Lenovo IdeaPad Flex-14API 81SS              | 1         | 1.25%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.25%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 1.25%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 1.25%   |
| HUAWEI NBM-WXX9                             | 1         | 1.25%   |
| HUAWEI BOD-WXX9                             | 1         | 1.25%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 1.25%   |
| HP Victus by Gaming Laptop 16-r0xxx         | 1         | 1.25%   |
| HP Victus by Gaming Laptop 15-fb0xxx        | 1         | 1.25%   |
| HP ProBook 4540s                            | 1         | 1.25%   |
| HP Pavilion Gaming Laptop 15-dk0xxx         | 1         | 1.25%   |
| HP Pavilion 15                              | 1         | 1.25%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 1.25%   |
| HP 250 G4 Notebook PC                       | 1         | 1.25%   |
| GPD P2 MAX                                  | 1         | 1.25%   |
| GPD G1618-04                                | 1         | 1.25%   |
| GPD G1618-03                                | 1         | 1.25%   |
| Google Snappy                               | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Acer Aspire                    | 7         | 8.75%   |
| ONE-NETBOOK ONEXPLAYER         | 5         | 6.25%   |
| Lenovo IdeaPad                 | 4         | 5%      |
| Dell Latitude                  | 4         | 5%      |
| ASUS ASUS                      | 4         | 5%      |
| HP Victus                      | 3         | 3.75%   |
| ASUS TUF                       | 3         | 3.75%   |
| Razer Blade                    | 2         | 2.5%    |
| Lenovo ThinkPad                | 2         | 2.5%    |
| HP Pavilion                    | 2         | 2.5%    |
| Dell Precision                 | 2         | 2.5%    |
| AYANEO AIR                     | 2         | 2.5%    |
| ASUS ROG                       | 2         | 2.5%    |
| Acer Nitro                     | 2         | 2.5%    |
| Unknown                        | 2         | 2.5%    |
| Valve Galileo                  | 1         | 1.25%   |
| Sony SVS13A25PLB               | 1         | 1.25%   |
| Notebook P15SM-A               | 1         | 1.25%   |
| MSI MS-7C96                    | 1         | 1.25%   |
| MSI MS-7C91                    | 1         | 1.25%   |
| MSI GP60                       | 1         | 1.25%   |
| MSI GE75                       | 1         | 1.25%   |
| MSI CX62                       | 1         | 1.25%   |
| Micro MG-VCP17I-3070           | 1         | 1.25%   |
| Micro (HK) Tech Limited Uranus | 1         | 1.25%   |
| Lenovo Y50-70                  | 1         | 1.25%   |
| Lenovo Legion                  | 1         | 1.25%   |
| HUAWEI NBM-WXX9                | 1         | 1.25%   |
| HUAWEI BOD-WXX9                | 1         | 1.25%   |
| HP ProBook                     | 1         | 1.25%   |
| HP EliteBook                   | 1         | 1.25%   |
| HP 250                         | 1         | 1.25%   |
| GPD P2                         | 1         | 1.25%   |
| GPD G1618-04                   | 1         | 1.25%   |
| GPD G1618-03                   | 1         | 1.25%   |
| Google Snappy                  | 1         | 1.25%   |
| Gigabyte Z97X-Gaming           | 1         | 1.25%   |
| Dell Inspiron                  | 1         | 1.25%   |
| Dell G15                       | 1         | 1.25%   |
| ASUS Zephyrus                  | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 15        | 18.75%  |
| 2023 | 13        | 16.25%  |
| 2020 | 8         | 10%     |
| 2017 | 7         | 8.75%   |
| 2022 | 5         | 6.25%   |
| 2019 | 5         | 6.25%   |
| 2015 | 5         | 6.25%   |
| 2013 | 5         | 6.25%   |
| 2012 | 5         | 6.25%   |
| 2016 | 3         | 3.75%   |
| 2014 | 3         | 3.75%   |
| 2024 | 2         | 2.5%    |
| 2011 | 2         | 2.5%    |
| 2018 | 1         | 1.25%   |
| 2008 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 80        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 97.5%   |
| Yes  | 2         | 2.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 23        | 28.75%  |
| 4.01-8.0    | 14        | 17.5%   |
| 8.01-16.0   | 13        | 16.25%  |
| 32.01-64.0  | 12        | 15%     |
| 24.01-32.0  | 8         | 10%     |
| 3.01-4.0    | 6         | 7.5%    |
| 64.01-256.0 | 4         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 36        | 44.44%  |
| 3.01-4.0 | 17        | 20.99%  |
| 4.01-8.0 | 16        | 19.75%  |
| 1.01-2.0 | 12        | 14.81%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 61.25%  |
| 2      | 27        | 33.75%  |
| 6      | 1         | 1.25%   |
| 4      | 1         | 1.25%   |
| 3      | 1         | 1.25%   |
| 0      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 85%     |
| Yes       | 12        | 15%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 75%     |
| No        | 20        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 96.25%  |
| No        | 3         | 3.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 86.25%  |
| No        | 11        | 13.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country       | Notebooks | Percent |
|---------------|-----------|---------|
| USA           | 27        | 33.75%  |
| Brazil        | 5         | 6.25%   |
| UK            | 4         | 5%      |
| Canada        | 4         | 5%      |
| Spain         | 3         | 3.75%   |
| Germany       | 3         | 3.75%   |
| France        | 3         | 3.75%   |
| China         | 3         | 3.75%   |
| Vietnam       | 2         | 2.5%    |
| Saudi Arabia  | 2         | 2.5%    |
| Poland        | 2         | 2.5%    |
| Netherlands   | 2         | 2.5%    |
| Mexico        | 2         | 2.5%    |
| Italy         | 2         | 2.5%    |
| Colombia      | 2         | 2.5%    |
| Switzerland   | 1         | 1.25%   |
| Russia        | 1         | 1.25%   |
| Romania       | 1         | 1.25%   |
| Philippines   | 1         | 1.25%   |
| Peru          | 1         | 1.25%   |
| Malaysia      | 1         | 1.25%   |
| Hungary       | 1         | 1.25%   |
| French Guiana | 1         | 1.25%   |
| Estonia       | 1         | 1.25%   |
| Czechia       | 1         | 1.25%   |
| Costa Rica    | 1         | 1.25%   |
| Belgium       | 1         | 1.25%   |
| Austria       | 1         | 1.25%   |
| Algeria       | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 1.25%   |
| Vũng Tàu               | 1         | 1.25%   |
| Virginia Beach           | 1         | 1.25%   |
| Vila-seca                | 1         | 1.25%   |
| Vienna                   | 1         | 1.25%   |
| Vancouver                | 1         | 1.25%   |
| Tulcea                   | 1         | 1.25%   |
| Stuttgart                | 1         | 1.25%   |
| St Louis                 | 1         | 1.25%   |
| Springfield              | 1         | 1.25%   |
| Soldotna                 | 1         | 1.25%   |
| Santa Cruz das Palmeiras | 1         | 1.25%   |
| San Pedro                | 1         | 1.25%   |
| San José                | 1         | 1.25%   |
| Saltillo                 | 1         | 1.25%   |
| Ridley Park              | 1         | 1.25%   |
| Remire-Montjoly          | 1         | 1.25%   |
| Rapla                    | 1         | 1.25%   |
| Portland                 | 1         | 1.25%   |
| Pontarlier               | 1         | 1.25%   |
| Pittsburg                | 1         | 1.25%   |
| Phoenix                  | 1         | 1.25%   |
| Philadelphia             | 1         | 1.25%   |
| Parma                    | 1         | 1.25%   |
| Pachuca                  | 1         | 1.25%   |
| Ostrów Wielkopolski     | 1         | 1.25%   |
| Olympia                  | 1         | 1.25%   |
| Nules                    | 1         | 1.25%   |
| Norcross                 | 1         | 1.25%   |
| Ningbo                   | 1         | 1.25%   |
| Newport News             | 1         | 1.25%   |
| Neiva                    | 1         | 1.25%   |
| Moscow                   | 1         | 1.25%   |
| Monticello               | 1         | 1.25%   |
| Milan                    | 1         | 1.25%   |
| Miami                    | 1         | 1.25%   |
| Manchester               | 1         | 1.25%   |
| Manaus                   | 1         | 1.25%   |
| Maastricht               | 1         | 1.25%   |
| London                   | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 16        | 16     | 14.29%  |
| WDC                          | 13        | 16     | 11.61%  |
| Unknown                      | 8         | 8      | 7.14%   |
| Sandisk                      | 8         | 8      | 7.14%   |
| Seagate                      | 7         | 7      | 6.25%   |
| Micron Technology            | 7         | 7      | 6.25%   |
| Kingston                     | 7         | 7      | 6.25%   |
| SK hynix                     | 5         | 5      | 4.46%   |
| Intel                        | 5         | 5      | 4.46%   |
| Toshiba                      | 3         | 3      | 2.68%   |
| Phison Electronics           | 3         | 4      | 2.68%   |
| Micron/Crucial Technology    | 3         | 4      | 2.68%   |
| MAXIO Technology (Hangzhou)  | 3         | 4      | 2.68%   |
| Shenzhen Longsys Electronics | 2         | 3      | 1.79%   |
| Realtek Semiconductor        | 2         | 2      | 1.79%   |
| KIOXIA                       | 2         | 2      | 1.79%   |
| Hitachi                      | 2         | 2      | 1.79%   |
| HGST                         | 2         | 2      | 1.79%   |
| Crucial                      | 2         | 2      | 1.79%   |
| Biwin Storage Technology     | 2         | 2      | 1.79%   |
| WDC PC S                     | 1         | 1      | 0.89%   |
| SSSTC                        | 1         | 1      | 0.89%   |
| Silicon Motion               | 1         | 1      | 0.89%   |
| Realtek                      | 1         | 1      | 0.89%   |
| NT-1TB                       | 1         | 1      | 0.89%   |
| Kingston Technology Company  | 1         | 1      | 0.89%   |
| JMicron Technology           | 1         | 1      | 0.89%   |
| GOODRAM                      | 1         | 1      | 0.89%   |
| Apple                        | 1         | 1      | 0.89%   |
| A-DATA Technology            | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 5         | 4.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 2.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 3         | 2.63%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 2         | 1.75%   |
| Unknown MMC Card  64GB                               | 2         | 1.75%   |
| Unknown MMC Card  512GB                              | 2         | 1.75%   |
| SK hynix HFM512GD3JX016N 512GB                       | 2         | 1.75%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 1.75%   |
| Sandisk WD_BLACK SN770 2TB                           | 2         | 1.75%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 2         | 1.75%   |
| Micron 1100 SATA 256GB SSD                           | 2         | 1.75%   |
| Kingston SV300S37A120G 120GB SSD                     | 2         | 1.75%   |
| Kingston SA400S37480G 480GB SSD                      | 2         | 1.75%   |
| Intel SSDPEKNU512GZ 512GB                            | 2         | 1.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1         | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.88%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 1         | 0.88%   |
| WDC WDBNCE0010PNC 1TB SSD                            | 1         | 0.88%   |
| WDC WD7500BPVT-80HXZT3 752GB                         | 1         | 0.88%   |
| WDC WD7500BPVT-55HXZT3 752GB                         | 1         | 0.88%   |
| WDC WD20SPZX-08UA7 2TB                               | 1         | 0.88%   |
| WDC WD201KFGX-68BKJN0 20TB                           | 1         | 0.88%   |
| WDC WD10SPZX-80Z10T2 1TB                             | 1         | 0.88%   |
| WDC WD10SPZX-24Z10 1TB                               | 1         | 0.88%   |
| WDC WD10SPCX-24HWST1 1TB                             | 1         | 0.88%   |
| WDC WD10JPLX-00MBPT0 1TB                             | 1         | 0.88%   |
| WDC WD10EZEX-60M2NA0 1TB                             | 1         | 0.88%   |
| WDC PC S N530 SDBPNPZ 512GB                          | 1         | 0.88%   |
| Unknown NVMe SSD Drive 512GB                         | 1         | 0.88%   |
| Unknown NVMe SSD Drive 1024GB                        | 1         | 0.88%   |
| Unknown MMC Card  1TB                                | 1         | 0.88%   |
| Unknown MMC Card  16GB                               | 1         | 0.88%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 1         | 0.88%   |
| Toshiba MQ01ABF050 500GB                             | 1         | 0.88%   |
| Toshiba KXG50ZNV512G 512GB                           | 1         | 0.88%   |
| SSSTC CVB-8D128-HP 128GB SSD                         | 1         | 0.88%   |
| SK hynix PC801 NVMe 1TB                              | 1         | 0.88%   |
| SK hynix PC601 NVMe 512GB                            | 1         | 0.88%   |
| SK hynix HFM512GD3JX013N 512GB                       | 1         | 0.88%   |
| Silicon Motion PCIe-8 SSD 256GB                      | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 11     | 47.83%  |
| Seagate | 7         | 7      | 30.43%  |
| Hitachi | 2         | 2      | 8.7%    |
| HGST    | 2         | 2      | 8.7%    |
| Toshiba | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 20.69%  |
| Kingston            | 6         | 6      | 20.69%  |
| WDC                 | 4         | 5      | 13.79%  |
| Micron Technology   | 4         | 4      | 13.79%  |
| Crucial             | 2         | 2      | 6.9%    |
| SSSTC               | 1         | 1      | 3.45%   |
| SanDisk             | 1         | 1      | 3.45%   |
| NT-1TB              | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| GOODRAM             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 50        | 58     | 49.02%  |
| SSD     | 24        | 30     | 23.53%  |
| HDD     | 20        | 23     | 19.61%  |
| MMC     | 6         | 6      | 5.88%   |
| Unknown | 2         | 2      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 50        | 57     | 51.55%  |
| SATA | 37        | 52     | 38.14%  |
| MMC  | 6         | 6      | 6.19%   |
| SAS  | 4         | 4      | 4.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 20        | 20     | 45.45%  |
| 0.01-0.5   | 19        | 28     | 43.18%  |
| 1.01-2.0   | 3         | 3      | 6.82%   |
| 3.01-4.0   | 1         | 1      | 2.27%   |
| 10.01-20.0 | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 29        | 36.25%  |
| 1001-2000      | 29        | 36.25%  |
| 251-500        | 8         | 10%     |
| 501-1000       | 6         | 7.5%    |
| 2001-3000      | 4         | 5%      |
| 101-250        | 2         | 2.5%    |
| 21-50          | 1         | 1.25%   |
| 1-20           | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 22        | 27.16%  |
| 51-100         | 14        | 17.28%  |
| 101-250        | 13        | 16.05%  |
| 501-1000       | 12        | 14.81%  |
| 251-500        | 10        | 12.35%  |
| 1001-2000      | 4         | 4.94%   |
| More than 3000 | 3         | 3.7%    |
| 1-20           | 3         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 80        | 119    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 42        | 40.78%  |
| Samsung Electronics          | 11        | 10.68%  |
| AMD                          | 11        | 10.68%  |
| SanDisk                      | 7         | 6.8%    |
| SK hynix                     | 5         | 4.85%   |
| Phison Electronics           | 3         | 2.91%   |
| Micron/Crucial Technology    | 3         | 2.91%   |
| Micron Technology            | 3         | 2.91%   |
| MAXIO Technology (Hangzhou)  | 3         | 2.91%   |
| Toshiba America Info Systems | 2         | 1.94%   |
| Shenzhen Longsys Electronics | 2         | 1.94%   |
| Realtek Semiconductor        | 2         | 1.94%   |
| KIOXIA                       | 2         | 1.94%   |
| Kingston Technology Company  | 2         | 1.94%   |
| INNOGRIT                     | 2         | 1.94%   |
| Biwin Storage Technology     | 2         | 1.94%   |
| Silicon Motion               | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 6.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 6.48%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 5.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 4.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 3.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.78%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.78%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.78%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                              | 2         | 1.85%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 2         | 1.85%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 1.85%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 2         | 1.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.85%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.85%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.93%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.93%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.93%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.93%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.93%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.93%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 0.93%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1         | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.93%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.93%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.93%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 0.93%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 0.93%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 0.93%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 0.93%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                               | 1         | 0.93%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 50        | 47.62%  |
| SATA | 40        | 38.1%   |
| RAID | 14        | 13.33%  |
| IDE  | 1         | 0.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 66.25%  |
| AMD    | 27        | 33.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 5%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 3.75%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 3         | 3.75%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 3         | 3.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 3.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.5%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 2.5%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.5%    |
| AMD Ryzen 7 8840U w/ Radeon 780M Graphics     | 2         | 2.5%    |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics     | 2         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 2.5%    |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 1.25%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.25%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.25%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.25%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 1.25%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.25%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.25%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.25%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.25%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.25%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.25%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.25%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 1.25%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 1.25%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.25%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.25%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 16        | 20%     |
| Intel Core i7 | 16        | 20%     |
| Intel Core i5 | 16        | 20%     |
| AMD Ryzen 7   | 11        | 13.75%  |
| AMD Ryzen 5   | 9         | 11.25%  |
| AMD Ryzen 9   | 5         | 6.25%   |
| Intel Core i3 | 2         | 2.5%    |
| Intel Pentium | 1         | 1.25%   |
| Intel Core m3 | 1         | 1.25%   |
| Intel Celeron | 1         | 1.25%   |
| Intel Atom    | 1         | 1.25%   |
| AMD Athlon    | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 33        | 41.25%  |
| 2      | 15        | 18.75%  |
| 6      | 13        | 16.25%  |
| 8      | 12        | 15%     |
| 16     | 2         | 2.5%    |
| 14     | 2         | 2.5%    |
| 12     | 2         | 2.5%    |
| 10     | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 70        | 87.5%   |
| 1      | 10        | 12.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 21        | 26.25%  |
| KabyLake    | 12        | 15%     |
| Haswell     | 11        | 13.75%  |
| Zen+        | 6         | 7.5%    |
| TigerLake   | 6         | 7.5%    |
| Zen 3       | 5         | 6.25%   |
| Skylake     | 5         | 6.25%   |
| Zen 2       | 3         | 3.75%   |
| IvyBridge   | 3         | 3.75%   |
| CometLake   | 3         | 3.75%   |
| SandyBridge | 2         | 2.5%    |
| Zen         | 1         | 1.25%   |
| Silvermont  | 1         | 1.25%   |
| Goldmont    | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 39.67%  |
| Nvidia | 43        | 35.54%  |
| AMD    | 30        | 24.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 7         | 5.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 7         | 5.74%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                              | 5         | 4.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 5         | 4.1%    |
| Nvidia GM107M [GeForce GTX 950M]                                     | 4         | 3.28%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 4         | 3.28%   |
| AMD Rembrandt [Radeon 680M]                                          | 4         | 3.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 3         | 2.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 3         | 2.46%   |
| Intel HD Graphics 630                                                | 3         | 2.46%   |
| Intel HD Graphics 530                                                | 3         | 2.46%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 3         | 2.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 3         | 2.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 2         | 1.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 1.64%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 2         | 1.64%   |
| Intel UHD Graphics 620                                               | 2         | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 2         | 1.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 2         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 2         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 2         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 2         | 1.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                            | 2         | 1.64%   |
| AMD Phoenix3                                                         | 2         | 1.64%   |
| AMD Phoenix1                                                         | 2         | 1.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                           | 2         | 1.64%   |
| AMD Lucienne                                                         | 2         | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 2         | 1.64%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]              | 1         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 0.82%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                             | 1         | 0.82%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                | 1         | 0.82%   |
| Nvidia GP107M [GeForce MX350]                                        | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                          | 1         | 0.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                   | 1         | 0.82%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                | 1         | 0.82%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                           | 1         | 0.82%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 0.82%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 31        | 38.75%  |
| 1 x AMD        | 19        | 23.75%  |
| 1 x Intel      | 13        | 16.25%  |
| AMD + Nvidia   | 7         | 8.75%   |
| 1 x Nvidia     | 5         | 6.25%   |
| Intel + AMD    | 3         | 3.75%   |
| Other          | 1         | 1.25%   |
| 2 x AMD        | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 72.5%   |
| Proprietary | 21        | 26.25%  |
| Unknown     | 1         | 1.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 15        | 17.65%  |
| BOE                 | 13        | 15.29%  |
| LG Display          | 12        | 14.12%  |
| AU Optronics        | 11        | 12.94%  |
| PANDA               | 5         | 5.88%   |
| TMX                 | 2         | 2.35%   |
| Sharp               | 2         | 2.35%   |
| Samsung Electronics | 2         | 2.35%   |
| AYANEO              | 2         | 2.35%   |
| Vizio               | 1         | 1.18%   |
| Valve               | 1         | 1.18%   |
| Unknown (XXX)       | 1         | 1.18%   |
| Toshiba             | 1         | 1.18%   |
| Sceptre Tech        | 1         | 1.18%   |
| SANYO               | 1         | 1.18%   |
| RTK                 | 1         | 1.18%   |
| Philips             | 1         | 1.18%   |
| Lenovo              | 1         | 1.18%   |
| Insignia            | 1         | 1.18%   |
| HSX                 | 1         | 1.18%   |
| HKC                 | 1         | 1.18%   |
| HJW                 | 1         | 1.18%   |
| GreenWood           | 1         | 1.18%   |
| GPD                 | 1         | 1.18%   |
| Goldstar            | 1         | 1.18%   |
| GameMax             | 1         | 1.18%   |
| Fujitsu Siemens     | 1         | 1.18%   |
| Apple               | 1         | 1.18%   |
| AOC                 | 1         | 1.18%   |
| Acer                | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 4         | 4.71%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 3         | 3.53%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 2.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 2.35%   |
| AYANEO AYANEOHD AYA6108 1080x1920                                    | 2         | 2.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 2.35%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                  | 1         | 1.18%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                  | 1         | 1.18%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 1.18%   |
| Toshiba TV TSB2017 3840x2160                                         | 1         | 1.18%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 1.18%   |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch               | 1         | 1.18%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 1.18%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch              | 1         | 1.18%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch       | 1         | 1.18%   |
| SANYO LED MONITOR SAN3219 1360x768 304x228mm 15.0-inch               | 1         | 1.18%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 1.18%   |
| RTK FHD RTK2A3B 1920x1080 531x299mm 24.0-inch                        | 1         | 1.18%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1         | 1.18%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 1         | 1.18%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD05DB 1920x1080 294x165mm 13.3-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD0459 1920x1080 382x215mm 17.3-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 1.18%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 1.18%   |
| Lenovo P27h-28 LEN62ED 2560x1440 597x336mm 27.0-inch                 | 1         | 1.18%   |
| Insignia NS-26E240A13 BBY0042 1920x1080 544x326mm 25.0-inch          | 1         | 1.18%   |
| HSX YHB03P24 HSX0324 1600x2560 120x190mm 8.8-inch                    | 1         | 1.18%   |
| HKC 25E3A HKC2533 1920x1080 544x303mm 24.5-inch                      | 1         | 1.18%   |
| HJW MACROSILICON HJW9291 1680x1050 530x290mm 23.8-inch               | 1         | 1.18%   |
| GreenWood ARZOPA GWD0156 1920x1080 344x193mm 15.5-inch               | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 48        | 57.83%  |
| 1366x768 (WXGA)   | 10        | 12.05%  |
| 3840x2160 (4K)    | 5         | 6.02%   |
| 2560x1440 (QHD)   | 5         | 6.02%   |
| 1600x2560         | 5         | 6.02%   |
| 1080x1920         | 2         | 2.41%   |
| 800x1280          | 1         | 1.2%    |
| 3440x1440         | 1         | 1.2%    |
| 2880x1800         | 1         | 1.2%    |
| 1920x1200 (WUXGA) | 1         | 1.2%    |
| 1600x900 (HD+)    | 1         | 1.2%    |
| 1360x768          | 1         | 1.2%    |
| 1280x960          | 1         | 1.2%    |
| 1280x768          | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 38        | 44.71%  |
| 17      | 7         | 8.24%   |
| 13      | 6         | 7.06%   |
| 8       | 5         | 5.88%   |
| 27      | 3         | 3.53%   |
| 16      | 3         | 3.53%   |
| Unknown | 3         | 3.53%   |
| 31      | 2         | 2.35%   |
| 21      | 2         | 2.35%   |
| 14      | 2         | 2.35%   |
| 7       | 2         | 2.35%   |
| 84      | 1         | 1.18%   |
| 72      | 1         | 1.18%   |
| 57      | 1         | 1.18%   |
| 54      | 1         | 1.18%   |
| 49      | 1         | 1.18%   |
| 36      | 1         | 1.18%   |
| 35      | 1         | 1.18%   |
| 34      | 1         | 1.18%   |
| 24      | 1         | 1.18%   |
| 23      | 1         | 1.18%   |
| 12      | 1         | 1.18%   |
| 11      | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 51.76%  |
| 351-400     | 10        | 11.76%  |
| 101-200     | 6         | 7.06%   |
| 501-600     | 5         | 5.88%   |
| 201-300     | 4         | 4.71%   |
| 701-800     | 3         | 3.53%   |
| Unknown     | 3         | 3.53%   |
| 601-700     | 2         | 2.35%   |
| 401-500     | 2         | 2.35%   |
| 1501-2000   | 2         | 2.35%   |
| 1001-1500   | 2         | 2.35%   |
| 801-900     | 1         | 1.18%   |
| 1-100       | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 83.54%  |
| 0.62  | 5         | 6.33%   |
| 16/10 | 3         | 3.8%    |
| 0.56  | 3         | 3.8%    |
| 21/9  | 1         | 1.27%   |
| 0.63  | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 47.62%  |
| 1-40           | 7         | 8.33%   |
| 121-130        | 7         | 8.33%   |
| 81-90          | 6         | 7.14%   |
| More than 1000 | 4         | 4.76%   |
| 351-500        | 3         | 3.57%   |
| 301-350        | 3         | 3.57%   |
| Unknown        | 3         | 3.57%   |
| 71-80          | 2         | 2.38%   |
| 201-250        | 2         | 2.38%   |
| 501-1000       | 2         | 2.38%   |
| 61-70          | 1         | 1.19%   |
| 51-60          | 1         | 1.19%   |
| 251-300        | 1         | 1.19%   |
| 151-200        | 1         | 1.19%   |
| 111-120        | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 55.42%  |
| 101-120       | 10        | 12.05%  |
| 51-100        | 9         | 10.84%  |
| More than 240 | 6         | 7.23%   |
| 161-240       | 6         | 7.23%   |
| 1-50          | 3         | 3.61%   |
| Unknown       | 3         | 3.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 83.75%  |
| 2     | 9         | 11.25%  |
| 0     | 3         | 3.75%   |
| 3     | 1         | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 50        | 37.31%  |
| Intel                           | 45        | 33.58%  |
| Qualcomm Atheros                | 17        | 12.69%  |
| MediaTek                        | 6         | 4.48%   |
| Broadcom Limited                | 3         | 2.24%   |
| ASIX Electronics                | 3         | 2.24%   |
| Broadcom                        | 2         | 1.49%   |
| TP-Link                         | 1         | 0.75%   |
| Samsung Electronics             | 1         | 0.75%   |
| Ralink Technology               | 1         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.75%   |
| Qualcomm                        | 1         | 0.75%   |
| QNAP System                     | 1         | 0.75%   |
| Google                          | 1         | 0.75%   |
| DisplayLink                     | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 25%     |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 11        | 7.64%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 4.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 3.47%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 2.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 2.08%   |
| Intel Wireless 7265                                                    | 3         | 2.08%   |
| Intel Wireless 3165                                                    | 3         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 2.08%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 2.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 1.39%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.39%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.39%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 1.39%   |
| TP-Link 802.11ac NIC                                                   | 1         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1         | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.69%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.69%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1         | 0.69%   |
| QNAP System Pacific                                                    | 1         | 0.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.69%   |
| Intel Wireless 3160                                                    | 1         | 0.69%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 0.69%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 54.43%  |
| Qualcomm Atheros                | 13        | 16.46%  |
| Realtek Semiconductor           | 10        | 12.66%  |
| MediaTek                        | 6         | 7.59%   |
| Broadcom                        | 2         | 2.53%   |
| TP-Link                         | 1         | 1.27%   |
| Ralink Technology               | 1         | 1.27%   |
| Qualcomm Atheros Communications | 1         | 1.27%   |
| Qualcomm                        | 1         | 1.27%   |
| Broadcom Limited                | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 11        | 13.75%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 6.25%   |
| Intel Wi-Fi 6 AX201                                                  | 5         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 4         | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 5%      |
| Intel Tiger Lake PCH CNVi WiFi                                       | 4         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 3.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 3         | 3.75%   |
| Intel Wireless 7265                                                  | 3         | 3.75%   |
| Intel Wireless 3165                                                  | 3         | 3.75%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 2.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.5%    |
| Intel Wireless 8265 / 8275                                           | 2         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 2.5%    |
| TP-Link 802.11ac NIC                                                 | 1         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.25%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.25%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 1         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 1.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 1.25%   |
| Intel Wireless 3160                                                  | 1         | 1.25%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.25%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.25%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 1.25%   |
| Intel Centrino Wireless-N + WiMAX 6150                               | 1         | 1.25%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 1.25%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1         | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 1         | 1.25%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 1         | 1.25%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 1.25%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                   | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 46        | 71.88%  |
| Qualcomm Atheros      | 5         | 7.81%   |
| Intel                 | 4         | 6.25%   |
| ASIX Electronics      | 3         | 4.69%   |
| Broadcom Limited      | 2         | 3.13%   |
| Samsung Electronics   | 1         | 1.56%   |
| QNAP System           | 1         | 1.56%   |
| Google                | 1         | 1.56%   |
| DisplayLink           | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 56.25%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 9.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 4.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 4.69%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 3.13%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 3.13%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.56%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.56%   |
| QNAP System Pacific                                                    | 1         | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.56%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.56%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 1.56%   |
| Google Pixel 6                                                         | 1         | 1.56%   |
| DisplayLink HP Port Replicator (Composite Device)                      | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 56.2%   |
| Ethernet | 60        | 43.8%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 80.25%  |
| Ethernet | 16        | 19.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 60%     |
| 1     | 31        | 38.75%  |
| 3     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 63.75%  |
| Yes  | 29        | 36.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 59.42%  |
| IMC Networks                    | 8         | 11.59%  |
| Qualcomm Atheros Communications | 5         | 7.25%   |
| Lite-On Technology              | 5         | 7.25%   |
| Realtek Semiconductor           | 3         | 4.35%   |
| Realtek                         | 2         | 2.9%    |
| TP-Link                         | 1         | 1.45%   |
| MediaTek                        | 1         | 1.45%   |
| Foxconn / Hon Hai               | 1         | 1.45%   |
| Cambridge Silicon Radio         | 1         | 1.45%   |
| Apple                           | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 13        | 18.84%  |
| Intel AX210 Bluetooth                               | 11        | 15.94%  |
| Intel Bluetooth wireless interface                  | 9         | 13.04%  |
| IMC Networks Wireless_Device                        | 4         | 5.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.35%   |
| IMC Networks Bluetooth Radio                        | 3         | 4.35%   |
| Realtek Bluetooth Radio                             | 2         | 2.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.9%    |
| Lite-On Bluetooth Device                            | 2         | 2.9%    |
| Intel AX211 Bluetooth                               | 2         | 2.9%    |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 1.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.45%   |
| Realtek Bluetooth Radio                             | 1         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.45%   |
| MediaTek Wireless_Device                            | 1         | 1.45%   |
| Lite-On Wireless_Device                             | 1         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.45%   |
| Intel AX200 Bluetooth                               | 1         | 1.45%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 1.45%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.45%   |
| Apple Bluetooth Host Controller                     | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 50        | 42.74%  |
| AMD                    | 29        | 24.79%  |
| Nvidia                 | 26        | 22.22%  |
| Sony                   | 6         | 5.13%   |
| Realtek Semiconductor  | 1         | 0.85%   |
| Logitech               | 1         | 0.85%   |
| Kingston Technology    | 1         | 0.85%   |
| Jieli Technology       | 1         | 0.85%   |
| Google                 | 1         | 0.85%   |
| Generalplus Technology | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                          | 21        | 14.19%  |
| AMD Rembrandt Radeon High Definition Audio Controller               | 10        | 6.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 8         | 5.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 8         | 5.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 6         | 4.05%   |
| Intel Sunrise Point-LP HD Audio                                     | 6         | 4.05%   |
| Intel Tiger Lake-H HD Audio Controller                              | 5         | 3.38%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 4         | 2.7%    |
| Nvidia GA107 High Definition Audio Controller                       | 4         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                  | 4         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 4         | 2.7%    |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 2.03%   |
| Nvidia GP107GL High Definition Audio Controller                     | 3         | 2.03%   |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 2.03%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 2.03%   |
| Intel CM238 HD Audio Controller                                     | 3         | 2.03%   |
| Intel Cannon Lake PCH cAVS                                          | 3         | 2.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 2.03%   |
| AMD Starship/Matisse HD Audio Controller                            | 3         | 2.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 3         | 2.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 3         | 2.03%   |
| Sony DualSense wireless controller (PS5)                            | 2         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 2         | 1.35%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 1.35%   |
| Realtek Semiconductor USB Audio                                     | 1         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 0.68%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1         | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                       | 1         | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 0.68%   |
| Nvidia GF116 High Definition Audio Controller                       | 1         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 0.68%   |
| Nvidia AD107 High Definition Audio Controller                       | 1         | 0.68%   |
| Logitech Logitech G PRO X Gaming Headset                            | 1         | 0.68%   |
| Kingston Technology HyperX QuadCast                                 | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| ChangXin Memory     | 1         | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 25%     |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 25%     |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 25%     |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR4 | 2         | 66.67%  |
| DDR3   | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Row Of Chips | 2         | 66.67%  |
| SODIMM       | 1         | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 1         | 33.33%  |
| 4096 | 1         | 33.33%  |
| 1024 | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4267  | 1         | 33.33%  |
| 3733  | 1         | 33.33%  |
| 1600  | 1         | 33.33%  |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 25%     |
| IMC Networks                           | 9         | 17.31%  |
| Sunplus Innovation Technology          | 6         | 11.54%  |
| Microdia                               | 6         | 11.54%  |
| Quanta                                 | 4         | 7.69%   |
| Sonix Technology                       | 2         | 3.85%   |
| Realtek Semiconductor                  | 2         | 3.85%   |
| Bison Electronics                      | 2         | 3.85%   |
| Acer                                   | 2         | 3.85%   |
| Syntek                                 | 1         | 1.92%   |
| Suyin                                  | 1         | 1.92%   |
| Silicon Motion                         | 1         | 1.92%   |
| Logitech                               | 1         | 1.92%   |
| Goodong                                | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                | 4         | 7.69%   |
| Sunplus HD WebCam                                                | 3         | 5.77%   |
| IMC Networks Integrated Camera                                   | 3         | 5.77%   |
| Sonix USB2.0 HD UVC WebCam                                       | 2         | 3.85%   |
| Quanta HP Wide Vision HD Camera                                  | 2         | 3.85%   |
| Microdia Integrated_Webcam_HD                                    | 2         | 3.85%   |
| IMC Networks ov9734_azurewave_camera                             | 2         | 3.85%   |
| Chicony Integrated Camera                                        | 2         | 3.85%   |
| Chicony HD WebCam                                                | 2         | 3.85%   |
| Chicony HD User Facing                                           | 2         | 3.85%   |
| Syntek USB2.0 Camera                                             | 1         | 1.92%   |
| Suyin HP Truevision HD                                           | 1         | 1.92%   |
| Sunplus Integrated_Webcam_HD                                     | 1         | 1.92%   |
| Sunplus Integrated_Webcam_FHD                                    | 1         | 1.92%   |
| Sunplus ASUS Webcam                                              | 1         | 1.92%   |
| Silicon Motion 300k Pixel Camera                                 | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD                                     | 1         | 1.92%   |
| Realtek Integrated Webcam                                        | 1         | 1.92%   |
| Quanta HP HD Camera                                              | 1         | 1.92%   |
| Quanta HD User Facing                                            | 1         | 1.92%   |
| Microdia USB 2.0 Camera                                          | 1         | 1.92%   |
| Microdia Laptop_Integrated_Webcam_HD                             | 1         | 1.92%   |
| Microdia Integrated_Webcam_FHD                                   | 1         | 1.92%   |
| Microdia HP Webcam                                               | 1         | 1.92%   |
| Logitech Webcam C930e                                            | 1         | 1.92%   |
| Goodong USB Camera                                               | 1         | 1.92%   |
| Chicony USB2.0 0.3M UVC WebCam                                   | 1         | 1.92%   |
| Chicony Integrated IR Camera                                     | 1         | 1.92%   |
| Chicony HP Wide Vision HD Camera                                 | 1         | 1.92%   |
| Chicony HP Truevision HD                                         | 1         | 1.92%   |
| Chicony HP HD Webcam [Fixed]                                     | 1         | 1.92%   |
| Chicony HD WebCam (Asus N-series)                                | 1         | 1.92%   |
| Chicony EasyCamera                                               | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision FHD Camera | 1         | 1.92%   |
| Bison Lenovo EasyCamera                                          | 1         | 1.92%   |
| Bison Integrated Camera                                          | 1         | 1.92%   |
| Acer Lenovo EasyCamera                                           | 1         | 1.92%   |
| Acer BisonCam, NB Pro                                            | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| LighTuning Technology      | 1         | 11.11%  |
| FocalTech                  | 1         | 11.11%  |
| Focal-systems.Corp         | 1         | 11.11%  |
| AuthenTec                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 3         | 33.33%  |
| Synaptics WBDI                                           | 1         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 11.11%  |
| FocalTech FocalTech Fingerprint Device                   | 1         | 11.11%  |
| Focal-systems.Corp FT9201Fingerprint.Ì                | 1         | 11.11%  |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| Broadcom 58200 | 2         | 66.67%  |
| Broadcom 5880  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 44        | 55%     |
| 1     | 30        | 37.5%   |
| 2     | 6         | 7.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 22        | 51.16%  |
| Fingerprint reader    | 9         | 20.93%  |
| Multimedia controller | 4         | 9.3%    |
| Chipcard              | 3         | 6.98%   |
| Net/wireless          | 2         | 4.65%   |
| Network               | 1         | 2.33%   |
| Net/ethernet          | 1         | 2.33%   |
| Bluetooth             | 1         | 2.33%   |


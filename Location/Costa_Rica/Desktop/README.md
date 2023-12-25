Linux in Costa Rica - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 115

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B150-HD3-CF                 | [d7e062f534](https://linux-hardware.org/?probe=d7e062f534) | Nov 15, 2023 |
| ZOTAC         | NM10                        | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| HP            | 3047h                       | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| ZOTAC         | NM10                        | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Dell          | 0D28YY A00                  | [ef531e70d1](https://linux-hardware.org/?probe=ef531e70d1) | Sep 22, 2023 |
| Dell          | 0RW203 A00                  | [0c76c5a1a7](https://linux-hardware.org/?probe=0c76c5a1a7) | Aug 30, 2023 |
| MSI           | A320M-A PRO                 | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| ASUSTek       | A55BM-E                     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [607d40a328](https://linux-hardware.org/?probe=607d40a328) | Jul 04, 2023 |
| MSI           | A320M-A PRO                 | [7dffb9055b](https://linux-hardware.org/?probe=7dffb9055b) | Jun 29, 2023 |
| MSI           | Z390-A PRO                  | [638d6b4ef3](https://linux-hardware.org/?probe=638d6b4ef3) | Jun 27, 2023 |
| Dell          | 0WMJ54 A00                  | [5875771b0c](https://linux-hardware.org/?probe=5875771b0c) | May 24, 2023 |
| Dell          | 0WMJ54 A00                  | [50283ef123](https://linux-hardware.org/?probe=50283ef123) | May 24, 2023 |
| ZOTAC         | NM10                        | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| ASRock        | 970 Extreme3                | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| MSI           | PRO B650M-A WIFI            | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cc2d26e52e](https://linux-hardware.org/?probe=cc2d26e52e) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| MACHINIST     | X79 V2.82H                  | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| ZOTAC         | NM10                        | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Gigabyte      | B150-HD3-CF                 | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Gigabyte      | H410M H                     | [09129dad50](https://linux-hardware.org/?probe=09129dad50) | Nov 28, 2022 |
| Gigabyte      | H410M H                     | [88ca303518](https://linux-hardware.org/?probe=88ca303518) | Nov 28, 2022 |
| Gigabyte      | H81M-DS2                    | [f278eb7e59](https://linux-hardware.org/?probe=f278eb7e59) | Nov 27, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | PRIME Z370-A                | [5d789a1783](https://linux-hardware.org/?probe=5d789a1783) | Sep 28, 2022 |
| Intel         | DG41WV AAE90316-103         | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0HD5W2 A01                  | [1bb8ad599d](https://linux-hardware.org/?probe=1bb8ad599d) | Sep 11, 2022 |
| ASRock        | N68-S UCC                   | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| HP            | 0AECh D                     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                        | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Dell          | 040DDP A01                  | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend           | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Dell          | 0RW203 A00                  | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| Dell          | 09KPNV A01                  | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                    | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                        | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                        | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                    | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| TPV-INVENT... | 2AF2 A01                    | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| ZOTAC         | NM10                        | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                      | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Pegatron      | 2AE4                        | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Intel         | D33217CK G76541-302         | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| ASUSTek       | PRIME A320M-K               | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01                  | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                       | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF              | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Pegatron      | 2AE4                        | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                     | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3                | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| Unknown       | i845G-W83627HF              | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF              | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3                  | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01                  | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| Dell          | 042P49 A01                  | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Gigabyte      | H110M-H-CF                  | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Gateway       | FMCP7AM                     | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                    | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0               | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING                  | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| ASRock        | B450 Steel Legend           | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| ASRock        | 775i65GV                    | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| ASRock        | 775i65GV                    | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| Dell          | 042P49 A01                  | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| Gigabyte      | GA-78LMT-S2                 | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| Biostar       | H61MGV3                     | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| Biostar       | H61MGV3                     | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103         | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| Lenovo        | SHARKBAY 31900003 STD       | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| OpenMandriva 4.2   | 9        | 10%     |
| Ubuntu 20.04       | 8        | 8.89%   |
| Ubuntu 22.04       | 6        | 6.67%   |
| OpenMandriva 23.03 | 4        | 4.44%   |
| Ubuntu 18.04       | 3        | 3.33%   |
| OpenMandriva 4.3   | 3        | 3.33%   |
| Linux Mint 20.2    | 3        | 3.33%   |
| Pop!_OS 21.04      | 2        | 2.22%   |
| OpenMandriva 23.01 | 2        | 2.22%   |
| Lubuntu 22.04      | 2        | 2.22%   |
| Linux Mint 19.3    | 2        | 2.22%   |
| KDE neon 22.04     | 2        | 2.22%   |
| Fedora 38          | 2        | 2.22%   |
| Fedora 32          | 2        | 2.22%   |
| Zorin 16           | 1        | 1.11%   |
| Zorin 15           | 1        | 1.11%   |
| Zorin 12           | 1        | 1.11%   |
| Xubuntu 22.04      | 1        | 1.11%   |
| UbuntuDDE 20.04    | 1        | 1.11%   |
| Ubuntu 22.10       | 1        | 1.11%   |
| Ubuntu 20.10       | 1        | 1.11%   |
| Ubuntu 19.10       | 1        | 1.11%   |
| ROSA R8.1          | 1        | 1.11%   |
| ROSA R11.1         | 1        | 1.11%   |
| ROSA R11           | 1        | 1.11%   |
| Pop!_OS 22.04      | 1        | 1.11%   |
| Pop!_OS 20.10      | 1        | 1.11%   |
| Pop!_OS 20.04      | 1        | 1.11%   |
| OpenMandriva 4.50  | 1        | 1.11%   |
| OpenMandriva 23.11 | 1        | 1.11%   |
| OpenMandriva 23.08 | 1        | 1.11%   |
| OpenMandriva 22.12 | 1        | 1.11%   |
| Manjaro 22.0.4     | 1        | 1.11%   |
| Manjaro 22.0.0     | 1        | 1.11%   |
| Manjaro 21.3.5     | 1        | 1.11%   |
| Manjaro 21.2.5     | 1        | 1.11%   |
| Manjaro 21.2.0     | 1        | 1.11%   |
| Manjaro            | 1        | 1.11%   |
| Lubuntu 21.10      | 1        | 1.11%   |
| Lubuntu 20.04      | 1        | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 20       | 23.81%  |
| OpenMandriva | 20       | 23.81%  |
| Fedora       | 7        | 8.33%   |
| Linux Mint   | 6        | 7.14%   |
| Pop!_OS      | 5        | 5.95%   |
| Manjaro      | 5        | 5.95%   |
| Zorin        | 3        | 3.57%   |
| KDE neon     | 3        | 3.57%   |
| ROSA         | 2        | 2.38%   |
| Lubuntu      | 2        | 2.38%   |
| Elementary   | 2        | 2.38%   |
| Debian       | 2        | 2.38%   |
| Arch         | 2        | 2.38%   |
| Xubuntu      | 1        | 1.19%   |
| UbuntuDDE    | 1        | 1.19%   |
| EndeavourOS  | 1        | 1.19%   |
| BlackPanther | 1        | 1.19%   |
| ArcoLinux    | 1        | 1.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.14-desktop-1omv4002    | 9        | 9.18%   |
| 6.2.6-desktop-1omv2390      | 4        | 4.08%   |
| 5.4.0-70-generic            | 3        | 3.06%   |
| 5.16.7-desktop-1omv4003     | 3        | 3.06%   |
| 6.4.11-desktop-1omv2390     | 2        | 2.04%   |
| 5.4.0-42-generic            | 2        | 2.04%   |
| 5.19.0-45-generic           | 2        | 2.04%   |
| 5.15.0-53-generic           | 2        | 2.04%   |
| 6.5.8-custom                | 1        | 1.02%   |
| 6.5.6-200.fc38.x86_64       | 1        | 1.02%   |
| 6.4.6-76060406-generic      | 1        | 1.02%   |
| 6.3.8-200.fc38.x86_64       | 1        | 1.02%   |
| 6.3.3-custom                | 1        | 1.02%   |
| 6.2.7-200.fc37.x86_64       | 1        | 1.02%   |
| 6.2.0-33-generic            | 1        | 1.02%   |
| 6.1.4-desktop-1omv2301      | 1        | 1.02%   |
| 6.1.2-arch1-1               | 1        | 1.02%   |
| 6.1.1-desktop-1omv2290      | 1        | 1.02%   |
| 6.1.1-1-MANJARO             | 1        | 1.02%   |
| 6.1.0-custom                | 1        | 1.02%   |
| 6.0.2-2-MANJARO             | 1        | 1.02%   |
| 6.0.11-300.fc37.x86_64      | 1        | 1.02%   |
| 6.0.10-desktop-2omv22090    | 1        | 1.02%   |
| 5.9.9-arch1-1               | 1        | 1.02%   |
| 5.9.14-arch1-1              | 1        | 1.02%   |
| 5.8.0-7630-generic          | 1        | 1.02%   |
| 5.8.0-50-generic            | 1        | 1.02%   |
| 5.8.0-41-generic            | 1        | 1.02%   |
| 5.8.0-34-generic            | 1        | 1.02%   |
| 5.7.0-1-amd64               | 1        | 1.02%   |
| 5.6.19-300.fc32.x86_64      | 1        | 1.02%   |
| 5.6.16-300.fc32.x86_64      | 1        | 1.02%   |
| 5.6.14-desktop-2bP          | 1        | 1.02%   |
| 5.6.13-arch1-1              | 1        | 1.02%   |
| 5.4.40-generic-1rosa-x86_64 | 1        | 1.02%   |
| 5.4.0-91-generic            | 1        | 1.02%   |
| 5.4.0-88-generic            | 1        | 1.02%   |
| 5.4.0-60-generic            | 1        | 1.02%   |
| 5.4.0-56-generic            | 1        | 1.02%   |
| 5.4.0-52-generic            | 1        | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11       | 11.58%  |
| 5.15.0  | 9        | 9.47%   |
| 5.10.14 | 9        | 9.47%   |
| 4.15.0  | 6        | 6.32%   |
| 6.2.6   | 4        | 4.21%   |
| 5.8.0   | 4        | 4.21%   |
| 5.19.0  | 4        | 4.21%   |
| 5.11.0  | 4        | 4.21%   |
| 5.16.7  | 3        | 3.16%   |
| 6.4.11  | 2        | 2.11%   |
| 6.1.1   | 2        | 2.11%   |
| 5.3.0   | 2        | 2.11%   |
| 5.13.0  | 2        | 2.11%   |
| 6.5.8   | 1        | 1.05%   |
| 6.5.6   | 1        | 1.05%   |
| 6.4.6   | 1        | 1.05%   |
| 6.3.8   | 1        | 1.05%   |
| 6.3.3   | 1        | 1.05%   |
| 6.2.7   | 1        | 1.05%   |
| 6.2.0   | 1        | 1.05%   |
| 6.1.4   | 1        | 1.05%   |
| 6.1.2   | 1        | 1.05%   |
| 6.1.0   | 1        | 1.05%   |
| 6.0.2   | 1        | 1.05%   |
| 6.0.11  | 1        | 1.05%   |
| 6.0.10  | 1        | 1.05%   |
| 5.9.9   | 1        | 1.05%   |
| 5.9.14  | 1        | 1.05%   |
| 5.7.0   | 1        | 1.05%   |
| 5.6.19  | 1        | 1.05%   |
| 5.6.16  | 1        | 1.05%   |
| 5.6.14  | 1        | 1.05%   |
| 5.6.13  | 1        | 1.05%   |
| 5.4.40  | 1        | 1.05%   |
| 5.18.13 | 1        | 1.05%   |
| 5.18.12 | 1        | 1.05%   |
| 5.15.94 | 1        | 1.05%   |
| 5.15.11 | 1        | 1.05%   |
| 5.14.14 | 1        | 1.05%   |
| 5.13.9  | 1        | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 12.63%  |
| 5.10    | 12       | 12.63%  |
| 5.15    | 11       | 11.58%  |
| 6.2     | 6        | 6.32%   |
| 4.15    | 6        | 6.32%   |
| 6.1     | 5        | 5.26%   |
| 5.11    | 5        | 5.26%   |
| 5.8     | 4        | 4.21%   |
| 5.6     | 4        | 4.21%   |
| 5.19    | 4        | 4.21%   |
| 6.4     | 3        | 3.16%   |
| 6.0     | 3        | 3.16%   |
| 5.16    | 3        | 3.16%   |
| 5.13    | 3        | 3.16%   |
| 6.5     | 2        | 2.11%   |
| 6.3     | 2        | 2.11%   |
| 5.9     | 2        | 2.11%   |
| 5.3     | 2        | 2.11%   |
| 5.18    | 2        | 2.11%   |
| 5.7     | 1        | 1.05%   |
| 5.14    | 1        | 1.05%   |
| 4.18    | 1        | 1.05%   |
| 4.1     | 1        | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 74       | 96.1%   |
| i686   | 3        | 3.9%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 35       | 43.75%  |
| KDE5          | 24       | 30%     |
| Unknown       | 6        | 7.5%    |
| X-Cinnamon    | 4        | 5%      |
| XFCE          | 2        | 2.5%    |
| Pantheon      | 2        | 2.5%    |
| MATE          | 2        | 2.5%    |
| LXQt          | 2        | 2.5%    |
| KDE           | 1        | 1.25%   |
| GNOME Classic | 1        | 1.25%   |
| Deepin        | 1        | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 62       | 78.48%  |
| Wayland | 16       | 20.25%  |
| Tty     | 1        | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 44.44%  |
| SDDM    | 25       | 30.86%  |
| GDM     | 9        | 11.11%  |
| GDM3    | 7        | 8.64%   |
| TDM     | 2        | 2.47%   |
| LightDM | 2        | 2.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 38       | 45.24%  |
| es_CR   | 34       | 40.48%  |
| Unknown | 5        | 5.95%   |
| es_ES   | 4        | 4.76%   |
| es_MX   | 2        | 2.38%   |
| de_DE   | 1        | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 41       | 52.56%  |
| BIOS | 37       | 47.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 50       | 60.98%  |
| Overlay | 17       | 20.73%  |
| Btrfs   | 10       | 12.2%   |
| Tmpfs   | 3        | 3.66%   |
| Xfs     | 1        | 1.22%   |
| Unknown | 1        | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 46.91%  |
| GPT     | 36       | 44.44%  |
| MBR     | 7        | 8.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 78.21%  |
| Yes       | 17       | 21.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 59.49%  |
| Yes       | 32       | 40.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 20.78%  |
| Dell                | 13       | 16.88%  |
| Gigabyte Technology | 12       | 15.58%  |
| MSI                 | 9        | 11.69%  |
| ASRock              | 8        | 10.39%  |
| Hewlett-Packard     | 4        | 5.19%   |
| Intel               | 2        | 2.6%    |
| Unknown             | 2        | 2.6%    |
| ZOTAC               | 1        | 1.3%    |
| TPV-INVENTA         | 1        | 1.3%    |
| Supermicro          | 1        | 1.3%    |
| Pegatron            | 1        | 1.3%    |
| MACHINIST           | 1        | 1.3%    |
| Lenovo              | 1        | 1.3%    |
| Gateway             | 1        | 1.3%    |
| Foxconn             | 1        | 1.3%    |
| Biostar             | 1        | 1.3%    |
| Alienware           | 1        | 1.3%    |
| ABIT                | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 3020                       | 6        | 7.79%   |
| MSI MS-7C51                              | 2        | 2.6%    |
| Gigabyte B250M-DS3H                      | 2        | 2.6%    |
| Dell OptiPlex 7040                       | 2        | 2.6%    |
| ASUS TUF Gaming X570-PLUS                | 2        | 2.6%    |
| ASUS PRIME H310M-E R2.0                  | 2        | 2.6%    |
| ASUS PRIME A320M-K                       | 2        | 2.6%    |
| ASRock B450 Steel Legend                 | 2        | 2.6%    |
| Unknown                                  | 2        | 2.6%    |
| ZOTAC NM10                               | 1        | 1.3%    |
| TPV-INVENTA 18-2003LA                    | 1        | 1.3%    |
| Supermicro X9DAi                         | 1        | 1.3%    |
| Pegatron CQ2728LA                        | 1        | 1.3%    |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 1.3%    |
| MSI MS-7D77                              | 1        | 1.3%    |
| MSI MS-7B98                              | 1        | 1.3%    |
| MSI MS-7B86                              | 1        | 1.3%    |
| MSI MS-7992                              | 1        | 1.3%    |
| MSI MS-7693                              | 1        | 1.3%    |
| MSI MS-7636                              | 1        | 1.3%    |
| MACHINIST X79 V2.82H                     | 1        | 1.3%    |
| Lenovo H530S 10132                       | 1        | 1.3%    |
| Intel DG41WV AAE90316-103                | 1        | 1.3%    |
| Intel D33217CK G76541-302                | 1        | 1.3%    |
| HP Z800 Workstation                      | 1        | 1.3%    |
| HP ProDesk 600 G4 SFF                    | 1        | 1.3%    |
| HP EliteDesk 800 G1 TWR                  | 1        | 1.3%    |
| HP Compaq 6005 Pro SFF PC                | 1        | 1.3%    |
| Gigabyte Z690 UD AX DDR4                 | 1        | 1.3%    |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.3%    |
| Gigabyte X570 I AORUS PRO WIFI           | 1        | 1.3%    |
| Gigabyte H81M-DS2                        | 1        | 1.3%    |
| Gigabyte H410M H                         | 1        | 1.3%    |
| Gigabyte H110M-S2                        | 1        | 1.3%    |
| Gigabyte H110M-H                         | 1        | 1.3%    |
| Gigabyte GA-970A-D3                      | 1        | 1.3%    |
| Gigabyte GA-78LMT-USB3 6.0               | 1        | 1.3%    |
| Gigabyte B150-HD3                        | 1        | 1.3%    |
| Gateway LX6810-01                        | 1        | 1.3%    |
| Foxconn nT-iBT18/nT-iBT19/nT-iBT29 FAB   | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 11       | 14.29%  |
| ASUS PRIME             | 5        | 6.49%   |
| ASUS TUF               | 3        | 3.9%    |
| MSI MS-7C51            | 2        | 2.6%    |
| Gigabyte B250M-DS3H    | 2        | 2.6%    |
| Dell Precision         | 2        | 2.6%    |
| ASUS SABERTOOTH        | 2        | 2.6%    |
| ASRock B450            | 2        | 2.6%    |
| Unknown                | 2        | 2.6%    |
| ZOTAC NM10             | 1        | 1.3%    |
| TPV-INVENTA 18-2003LA  | 1        | 1.3%    |
| Supermicro X9DAi       | 1        | 1.3%    |
| Pegatron CQ2728LA      | 1        | 1.3%    |
| MSI Z390               | 1        | 1.3%    |
| MSI MS-7D77            | 1        | 1.3%    |
| MSI MS-7B98            | 1        | 1.3%    |
| MSI MS-7B86            | 1        | 1.3%    |
| MSI MS-7992            | 1        | 1.3%    |
| MSI MS-7693            | 1        | 1.3%    |
| MSI MS-7636            | 1        | 1.3%    |
| MACHINIST X79          | 1        | 1.3%    |
| Lenovo H530S           | 1        | 1.3%    |
| Intel DG41WV           | 1        | 1.3%    |
| Intel D33217CK         | 1        | 1.3%    |
| HP Z800                | 1        | 1.3%    |
| HP ProDesk             | 1        | 1.3%    |
| HP EliteDesk           | 1        | 1.3%    |
| HP Compaq              | 1        | 1.3%    |
| Gigabyte Z690          | 1        | 1.3%    |
| Gigabyte Z170X-Gaming  | 1        | 1.3%    |
| Gigabyte X570          | 1        | 1.3%    |
| Gigabyte H81M-DS2      | 1        | 1.3%    |
| Gigabyte H410M         | 1        | 1.3%    |
| Gigabyte H110M-S2      | 1        | 1.3%    |
| Gigabyte H110M-H       | 1        | 1.3%    |
| Gigabyte GA-970A-D3    | 1        | 1.3%    |
| Gigabyte GA-78LMT-USB3 | 1        | 1.3%    |
| Gigabyte B150-HD3      | 1        | 1.3%    |
| Gateway LX6810-01      | 1        | 1.3%    |
| Foxconn nT-iBT18       | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 10       | 12.99%  |
| 2016 | 10       | 12.99%  |
| 2014 | 10       | 12.99%  |
| 2013 | 7        | 9.09%   |
| 2012 | 7        | 9.09%   |
| 2018 | 5        | 6.49%   |
| 2010 | 4        | 5.19%   |
| 2021 | 3        | 3.9%    |
| 2020 | 3        | 3.9%    |
| 2017 | 3        | 3.9%    |
| 2011 | 3        | 3.9%    |
| 2008 | 3        | 3.9%    |
| 2022 | 2        | 2.6%    |
| 2015 | 2        | 2.6%    |
| 2009 | 2        | 2.6%    |
| 2005 | 2        | 2.6%    |
| 2007 | 1        | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 72       | 93.51%  |
| Enabled  | 5        | 6.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 24       | 29.63%  |
| 8.01-16.0       | 17       | 20.99%  |
| 3.01-4.0        | 12       | 14.81%  |
| 4.01-8.0        | 9        | 11.11%  |
| 32.01-64.0      | 9        | 11.11%  |
| 1.01-2.0        | 5        | 6.17%   |
| 24.01-32.0      | 2        | 2.47%   |
| More than 256.0 | 1        | 1.23%   |
| 2.01-3.0        | 1        | 1.23%   |
| 64.01-256.0     | 1        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 35       | 39.77%  |
| 2.01-3.0   | 18       | 20.45%  |
| 4.01-8.0   | 14       | 15.91%  |
| 3.01-4.0   | 8        | 9.09%   |
| 0.51-1.0   | 5        | 5.68%   |
| 0.01-0.5   | 3        | 3.41%   |
| 16.01-24.0 | 2        | 2.27%   |
| 8.01-16.0  | 2        | 2.27%   |
| 24.01-32.0 | 1        | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 49.37%  |
| 2      | 22       | 27.85%  |
| 4      | 7        | 8.86%   |
| 3      | 7        | 8.86%   |
| 8      | 1        | 1.27%   |
| 7      | 1        | 1.27%   |
| 6      | 1        | 1.27%   |
| 5      | 1        | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 55%     |
| Yes       | 36       | 45%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 98.7%   |
| No        | 1        | 1.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 57.69%  |
| Yes       | 33       | 42.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 74.07%  |
| Yes       | 21       | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Costa Rica | 77       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| San José   | 35       | 40.23%  |
| Heredia     | 20       | 22.99%  |
| Escazu      | 6        | 6.9%    |
| Alajuela    | 4        | 4.6%    |
| Santa Ana   | 2        | 2.3%    |
| Liberia     | 2        | 2.3%    |
| Grecia      | 2        | 2.3%    |
| Cartago     | 2        | 2.3%    |
| Tres Rios   | 1        | 1.15%   |
| Tibas       | 1        | 1.15%   |
| Santa Fe    | 1        | 1.15%   |
| San Pedro   | 1        | 1.15%   |
| Rio Segundo | 1        | 1.15%   |
| Puntarenas  | 1        | 1.15%   |
| Pavas       | 1        | 1.15%   |
| Palmares    | 1        | 1.15%   |
| Nosara      | 1        | 1.15%   |
| Naranjo     | 1        | 1.15%   |
| Curridabat  | 1        | 1.15%   |
| Cariblanca  | 1        | 1.15%   |
| Bajo Perez  | 1        | 1.15%   |
| Alajuelita  | 1        | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 29       | 50     | 21.97%  |
| WDC                   | 21       | 28     | 15.91%  |
| A-DATA Technology     | 12       | 13     | 9.09%   |
| Kingston              | 11       | 18     | 8.33%   |
| Toshiba               | 10       | 11     | 7.58%   |
| Samsung Electronics   | 7        | 16     | 5.3%    |
| Hitachi               | 6        | 8      | 4.55%   |
| XPG                   | 4        | 4      | 3.03%   |
| Realtek Semiconductor | 4        | 6      | 3.03%   |
| Patriot               | 4        | 6      | 3.03%   |
| HGST                  | 3        | 3      | 2.27%   |
| ZOTAC                 | 2        | 3      | 1.52%   |
| SanDisk               | 2        | 3      | 1.52%   |
| Mushkin               | 2        | 2      | 1.52%   |
| Maxtor                | 2        | 2      | 1.52%   |
| Crucial               | 2        | 2      | 1.52%   |
| WD MediaMax           | 1        | 1      | 0.76%   |
| Unknown               | 1        | 2      | 0.76%   |
| Team                  | 1        | 1      | 0.76%   |
| T-FORCE               | 1        | 1      | 0.76%   |
| Phison Electronics    | 1        | 1      | 0.76%   |
| Netac                 | 1        | 2      | 0.76%   |
| JMicron Technology    | 1        | 1      | 0.76%   |
| Intel                 | 1        | 1      | 0.76%   |
| Gigabyte Technology   | 1        | 2      | 0.76%   |
| CT120BX5              | 1        | 1      | 0.76%   |
| ADATA Technology      | 1        | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                      | 5        | 3.38%   |
| Kingston SA400S37240G 240GB SSD             | 5        | 3.38%   |
| A-DATA SU630 480GB SSD                      | 5        | 3.38%   |
| WDC WD10EZEX-75WN4A1 1TB                    | 3        | 2.03%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 3        | 2.03%   |
| Seagate ST1000DM003-1CH162 1TB              | 3        | 2.03%   |
| A-DATA SU650 120GB SSD                      | 3        | 2.03%   |
| XPG GAMMIX S11 Pro 256GB                    | 2        | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 2        | 1.35%   |
| Seagate ST8000DM004-2CX188 8TB              | 2        | 1.35%   |
| Seagate ST500DM002-1BD142 500GB             | 2        | 1.35%   |
| Seagate ST380815AS 80GB                     | 2        | 1.35%   |
| Seagate ST2000LM015-2E8174 2TB              | 2        | 1.35%   |
| Seagate ST2000LM007-1R8174 2TB              | 2        | 1.35%   |
| Realtek RTS5763DL NVMe SSD Controller 512GB | 2        | 1.35%   |
| Mushkin MKNSSDEL240GB                       | 2        | 1.35%   |
| HGST HTS541075A9E680 752GB                  | 2        | 1.35%   |
| ZOTAC ZTSSD-S11-240G-P 240GB                | 1        | 0.68%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB               | 1        | 0.68%   |
| XPG NVMe SSD Drive 512GB                    | 1        | 0.68%   |
| XPG NVMe SSD Drive 1TB                      | 1        | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD            | 1        | 0.68%   |
| WDC WD6400AAKS-22A7B0 640GB                 | 1        | 0.68%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1        | 0.68%   |
| WDC WD5000AAKS-00V1A0 500GB                 | 1        | 0.68%   |
| WDC WD2500AAJS-00VTA0 250GB                 | 1        | 0.68%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 1        | 0.68%   |
| WDC WD1600BEVS-26VAT0 160GB                 | 1        | 0.68%   |
| WDC WD1500HLFS-01G6U0 150GB                 | 1        | 0.68%   |
| WDC WD10SPZX-24Z10T0 1TB                    | 1        | 0.68%   |
| WDC WD10JPVX-00JC3T0 1TB                    | 1        | 0.68%   |
| WDC WD10EZEX-60ZF5A0 1TB                    | 1        | 0.68%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1        | 0.68%   |
| WDC WD10EZEX-60M2NA0 1TB                    | 1        | 0.68%   |
| WDC WD10EZEX-08M2NA0 1TB                    | 1        | 0.68%   |
| WD MediaMax WL3000GSA6472 3TB               | 1        | 0.68%   |
| Unknown MB3000EBKAB 3TB                     | 1        | 0.68%   |
| Toshiba THNSN5512GPUK NVMe 512GB            | 1        | 0.68%   |
| Toshiba RD400 256GB                         | 1        | 0.68%   |
| Toshiba MQ01ABD100 1TB                      | 1        | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 49     | 40.58%  |
| WDC                 | 19       | 24     | 27.54%  |
| Toshiba             | 8        | 9      | 11.59%  |
| Hitachi             | 6        | 8      | 8.7%    |
| HGST                | 3        | 3      | 4.35%   |
| Samsung Electronics | 2        | 2      | 2.9%    |
| Maxtor              | 2        | 2      | 2.9%    |
| Unknown             | 1        | 2      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 10       | 16     | 25%     |
| A-DATA Technology   | 10       | 11     | 25%     |
| WDC                 | 3        | 4      | 7.5%    |
| Patriot             | 3        | 5      | 7.5%    |
| ZOTAC               | 2        | 3      | 5%      |
| SanDisk             | 2        | 3      | 5%      |
| Samsung Electronics | 2        | 7      | 5%      |
| Mushkin             | 2        | 2      | 5%      |
| Team                | 1        | 1      | 2.5%    |
| JMicron Technology  | 1        | 1      | 2.5%    |
| Intel               | 1        | 1      | 2.5%    |
| Gigabyte Technology | 1        | 2      | 2.5%    |
| CT120BX5            | 1        | 1      | 2.5%    |
| Crucial             | 1        | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 54       | 99     | 49.54%  |
| SSD     | 35       | 58     | 32.11%  |
| NVMe    | 18       | 29     | 16.51%  |
| Unknown | 2        | 3      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 74       | 149    | 75.51%  |
| NVMe | 18       | 29     | 18.37%  |
| SAS  | 6        | 11     | 6.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 57       | 97     | 58.16%  |
| 0.51-1.0   | 28       | 37     | 28.57%  |
| 1.01-2.0   | 5        | 6      | 5.1%    |
| 4.01-10.0  | 5        | 13     | 5.1%    |
| 3.01-4.0   | 2        | 2      | 2.04%   |
| 2.01-3.0   | 1        | 2      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 18       | 20.69%  |
| 101-250        | 16       | 18.39%  |
| 1-20           | 14       | 16.09%  |
| 251-500        | 11       | 12.64%  |
| 1001-2000      | 9        | 10.34%  |
| More than 3000 | 7        | 8.05%   |
| 51-100         | 7        | 8.05%   |
| 2001-3000      | 2        | 2.3%    |
| Unknown        | 2        | 2.3%    |
| 21-50          | 1        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 37       | 41.11%  |
| 21-50          | 16       | 17.78%  |
| 101-250        | 8        | 8.89%   |
| 251-500        | 7        | 7.78%   |
| More than 3000 | 5        | 5.56%   |
| 501-1000       | 5        | 5.56%   |
| 51-100         | 5        | 5.56%   |
| 1001-2000      | 3        | 3.33%   |
| 2001-3000      | 2        | 2.22%   |
| Unknown        | 2        | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Unknown MB3000EBKAB 3TB             | 1        | 1      | 10%     |
| Seagate ST9160412AS 160GB           | 1        | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2      | 10%     |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 10%     |
| SanDisk SD6SB1M-128G-1006 128GB SSD | 1        | 2      | 10%     |
| Maxtor STM3160215AS 160GB           | 1        | 1      | 10%     |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1      | 10%     |
| Hitachi HDE721010SLA330 1TB         | 1        | 1      | 10%     |
| A-DATA Technology SX8100NP 256GB    | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 4        | 5      | 40%     |
| Unknown           | 1        | 1      | 10%     |
| SanDisk           | 1        | 2      | 10%     |
| Maxtor            | 1        | 1      | 10%     |
| Kingston          | 1        | 1      | 10%     |
| Hitachi           | 1        | 1      | 10%     |
| A-DATA Technology | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 57.14%  |
| Unknown | 1        | 1      | 14.29%  |
| Maxtor  | 1        | 1      | 14.29%  |
| Hitachi | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 8      | 66.67%  |
| SSD  | 2        | 3      | 22.22%  |
| NVMe | 1        | 1      | 11.11%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 45       | 96     | 51.14%  |
| Works    | 35       | 81     | 39.77%  |
| Malfunc  | 8        | 12     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 50       | 46.73%  |
| AMD                          | 25       | 23.36%  |
| ASMedia Technology           | 6        | 5.61%   |
| Realtek Semiconductor        | 5        | 4.67%   |
| ADATA Technology             | 5        | 4.67%   |
| Samsung Electronics          | 3        | 2.8%    |
| Nvidia                       | 2        | 1.87%   |
| Toshiba America Info Systems | 1        | 0.93%   |
| Silicon Motion               | 1        | 0.93%   |
| Silicon Image                | 1        | 0.93%   |
| Phison Electronics           | 1        | 0.93%   |
| OCZ Technology Group         | 1        | 0.93%   |
| Micron/Crucial Technology    | 1        | 0.93%   |
| Marvell Technology Group     | 1        | 0.93%   |
| LSI Logic / Symbios Logic    | 1        | 0.93%   |
| Kingston Technology Company  | 1        | 0.93%   |
| JMicron Technology           | 1        | 0.93%   |
| INNOGRIT                     | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11       | 9.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 5.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 4.96%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6        | 4.96%   |
| AMD FCH SATA Controller D                                                      | 6        | 4.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 4.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 4.13%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 4        | 3.31%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 3.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 2.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.65%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.83%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.83%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.83%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.83%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 0.83%   |
| Nvidia MCP79 RAID Controller                                                   | 1        | 0.83%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.83%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.83%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 0.83%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.83%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 0.83%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 1        | 0.83%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1        | 0.83%   |
| JMicron JMB368 IDE controller                                                  | 1        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.83%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 67       | 64.42%  |
| NVMe | 18       | 17.31%  |
| IDE  | 12       | 11.54%  |
| RAID | 5        | 4.81%   |
| SAS  | 1        | 0.96%   |
| SCSI | 1        | 0.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 51       | 66.23%  |
| AMD    | 26       | 33.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 6.49%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 5.19%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 3.9%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 2.6%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.6%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.6%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.6%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.6%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 2.6%    |
| Intel Xeon CPU X5667 @ 3.07GHz              | 1        | 1.3%    |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.3%    |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 1.3%    |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz         | 1        | 1.3%    |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.3%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.3%    |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.3%    |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.3%    |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 1.3%    |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.3%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.3%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 1.3%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.3%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.3%    |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.3%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.3%    |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.3%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.3%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.3%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.3%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.3%    |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.3%    |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.3%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.3%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 25.97%  |
| Intel Core i3           | 7        | 9.09%   |
| AMD Ryzen 5             | 6        | 7.79%   |
| Intel Xeon              | 5        | 6.49%   |
| Intel Core i7           | 5        | 6.49%   |
| AMD Ryzen 3             | 5        | 6.49%   |
| AMD FX                  | 5        | 6.49%   |
| Intel Celeron           | 3        | 3.9%    |
| AMD Ryzen 7             | 3        | 3.9%    |
| Other                   | 2        | 2.6%    |
| Intel Pentium           | 2        | 2.6%    |
| Intel Pentium Dual-Core | 1        | 1.3%    |
| Intel Pentium 4         | 1        | 1.3%    |
| Intel Core i9           | 1        | 1.3%    |
| Intel Core 2 Quad       | 1        | 1.3%    |
| Intel Core 2 Duo        | 1        | 1.3%    |
| Intel Core 2            | 1        | 1.3%    |
| Intel Atom              | 1        | 1.3%    |
| AMD Sempron             | 1        | 1.3%    |
| AMD Ryzen 7 PRO         | 1        | 1.3%    |
| AMD Phenom II X4        | 1        | 1.3%    |
| AMD E2                  | 1        | 1.3%    |
| AMD E1                  | 1        | 1.3%    |
| AMD Athlon II X2        | 1        | 1.3%    |
| AMD A4                  | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 37       | 48.05%  |
| 2      | 14       | 18.18%  |
| 6      | 11       | 14.29%  |
| 8      | 7        | 9.09%   |
| 1      | 5        | 6.49%   |
| 20     | 1        | 1.3%    |
| 10     | 1        | 1.3%    |
| 3      | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 75       | 97.4%   |
| 2      | 2        | 2.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 58.44%  |
| 2      | 32       | 41.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 75       | 97.4%   |
| 32-bit         | 1        | 1.3%    |
| Unknown        | 1        | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 21.69%  |
| 0x306c3    | 9        | 10.84%  |
| 0x906e9    | 4        | 4.82%   |
| 0x306a9    | 4        | 4.82%   |
| 0x08701021 | 4        | 4.82%   |
| 0x506e3    | 3        | 3.61%   |
| 0x08108109 | 3        | 3.61%   |
| 0x906eb    | 2        | 2.41%   |
| 0x306e4    | 2        | 2.41%   |
| 0x10676    | 2        | 2.41%   |
| 0x08101016 | 2        | 2.41%   |
| 0x06000852 | 2        | 2.41%   |
| 0x05000119 | 2        | 2.41%   |
| 0x010000c8 | 2        | 2.41%   |
| 0xf49      | 1        | 1.2%    |
| 0xf29      | 1        | 1.2%    |
| 0x906ec    | 1        | 1.2%    |
| 0x906ea    | 1        | 1.2%    |
| 0x90675    | 1        | 1.2%    |
| 0x90672    | 1        | 1.2%    |
| 0x706a8    | 1        | 1.2%    |
| 0x6f6      | 1        | 1.2%    |
| 0x30678    | 1        | 1.2%    |
| 0x106e5    | 1        | 1.2%    |
| 0x106ca    | 1        | 1.2%    |
| 0x106a5    | 1        | 1.2%    |
| 0x10677    | 1        | 1.2%    |
| 0x0a601201 | 1        | 1.2%    |
| 0x08701011 | 1        | 1.2%    |
| 0x0870100a | 1        | 1.2%    |
| 0x08600109 | 1        | 1.2%    |
| 0x08600106 | 1        | 1.2%    |
| 0x0800820d | 1        | 1.2%    |
| 0x06001119 | 1        | 1.2%    |
| 0x06000822 | 1        | 1.2%    |
| 0x0500010d | 1        | 1.2%    |
| 0x010000c7 | 1        | 1.2%    |
| 0x00000000 | 1        | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 11       | 14.29%  |
| Haswell          | 11       | 14.29%  |
| IvyBridge        | 7        | 9.09%   |
| Zen 2            | 6        | 7.79%   |
| Skylake          | 5        | 6.49%   |
| Piledriver       | 5        | 6.49%   |
| Zen+             | 4        | 5.19%   |
| Penryn           | 4        | 5.19%   |
| K10              | 3        | 3.9%    |
| Zen 3            | 2        | 2.6%    |
| Zen              | 2        | 2.6%    |
| NetBurst         | 2        | 2.6%    |
| Nehalem          | 2        | 2.6%    |
| Bobcat           | 2        | 2.6%    |
| Unknown          | 2        | 2.6%    |
| Westmere         | 1        | 1.3%    |
| Silvermont       | 1        | 1.3%    |
| SandyBridge      | 1        | 1.3%    |
| Goldmont plus    | 1        | 1.3%    |
| Core             | 1        | 1.3%    |
| CometLake        | 1        | 1.3%    |
| Bulldozer        | 1        | 1.3%    |
| Bonnell          | 1        | 1.3%    |
| Alderlake Hybrid | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 32       | 37.21%  |
| Nvidia | 31       | 36.05%  |
| AMD    | 23       | 26.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 10.11%  |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 4.49%   |
| Intel HD Graphics 530                                                       | 4        | 4.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.49%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 3.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.37%   |
| Intel HD Graphics 630                                                       | 3        | 3.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.25%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 2.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.25%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.25%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 1.12%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.12%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 1.12%   |
| Nvidia GT218 [ION]                                                          | 1        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.12%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.12%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.12%   |
| Nvidia GK106 [GeForce GTX 645 OEM]                                          | 1        | 1.12%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.12%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.12%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.12%   |
| Nvidia G96C [GeForce GT 120]                                                | 1        | 1.12%   |
| Nvidia G71GL [Quadro FX 3500]                                               | 1        | 1.12%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.12%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.12%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 1.12%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device          | 1        | 1.12%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 29       | 35.37%  |
| 1 x Intel      | 29       | 35.37%  |
| 1 x AMD        | 18       | 21.95%  |
| 2 x AMD        | 3        | 3.66%   |
| AMD + Nvidia   | 2        | 2.44%   |
| Intel + Nvidia | 1        | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 62       | 77.5%   |
| Proprietary | 16       | 20%     |
| Unknown     | 2        | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 40.48%  |
| 1.01-2.0   | 16       | 19.05%  |
| 0.51-1.0   | 9        | 10.71%  |
| 3.01-4.0   | 8        | 9.52%   |
| 0.01-0.5   | 7        | 8.33%   |
| 5.01-6.0   | 5        | 5.95%   |
| 7.01-8.0   | 4        | 4.76%   |
| 8.01-16.0  | 1        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 19       | 21.35%  |
| Hewlett-Packard      | 13       | 14.61%  |
| Dell                 | 10       | 11.24%  |
| Goldstar             | 9        | 10.11%  |
| ViewSonic            | 4        | 4.49%   |
| Samsung Electronics  | 4        | 4.49%   |
| BenQ                 | 4        | 4.49%   |
| Acer                 | 4        | 4.49%   |
| AGO                  | 3        | 3.37%   |
| Sony                 | 2        | 2.25%   |
| Panasonic            | 2        | 2.25%   |
| Lenovo               | 2        | 2.25%   |
| Ancor Communications | 2        | 2.25%   |
| Xerox                | 1        | 1.12%   |
| Unknown (XXX)        | 1        | 1.12%   |
| Royal Information    | 1        | 1.12%   |
| Philips              | 1        | 1.12%   |
| MSI                  | 1        | 1.12%   |
| LTM                  | 1        | 1.12%   |
| ITE                  | 1        | 1.12%   |
| Hitachi              | 1        | 1.12%   |
| Haier                | 1        | 1.12%   |
| ASRock               | 1        | 1.12%   |
| ASR                  | 1        | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5        | 5.15%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3        | 3.09%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3        | 3.09%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2        | 2.06%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2        | 2.06%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2        | 2.06%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 2.06%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 2        | 2.06%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 2        | 2.06%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 2        | 2.06%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1        | 1.03%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1        | 1.03%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1        | 1.03%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1        | 1.03%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 1.03%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.03%   |
| Sony TV SNY1B02 1360x768                                             | 1        | 1.03%   |
| Sony TV SNY0902 1920x1080                                            | 1        | 1.03%   |
| Samsung Electronics S24A31x SAM7115 1920x1080 527x296mm 23.8-inch    | 1        | 1.03%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 1.03%   |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch      | 1        | 1.03%   |
| Philips LCD Monitor 170B4 1280x1024                                  | 1        | 1.03%   |
| MSI MAG271CQR MSI3FA7 2560x1440 597x336mm 27.0-inch                  | 1        | 1.03%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                    | 1        | 1.03%   |
| Lenovo LEN T27h-20 LEN61EC 2560x1440 597x336mm 27.0-inch             | 1        | 1.03%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch             | 1        | 1.03%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 1.03%   |
| Hitachi 32E10 HTC0128 1366x768 575x323mm 26.0-inch                   | 1        | 1.03%   |
| Hewlett-Packard V202 HWP330B 1600x900 452x263mm 20.6-inch            | 1        | 1.03%   |
| Hewlett-Packard V193 HWP3178 1366x768 410x230mm 18.5-inch            | 1        | 1.03%   |
| Hewlett-Packard P223a HPN3391 1920x1080 477x268mm 21.5-inch          | 1        | 1.03%   |
| Hewlett-Packard Omni/Pro HWP410E 1366x768 410x230mm 18.5-inch        | 1        | 1.03%   |
| Hewlett-Packard LCD Monitor L1908w 1440x900                          | 1        | 1.03%   |
| Hewlett-Packard LCD Monitor Compaq W185q 3286x1080                   | 1        | 1.03%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 1.03%   |
| Hewlett-Packard L1910 HWP26E6 1280x1024 380x300mm 19.1-inch          | 1        | 1.03%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch           | 1        | 1.03%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 1        | 1.03%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 1        | 1.03%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch          | 1        | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 35       | 39.77%  |
| 1366x768 (WXGA)   | 12       | 13.64%  |
| 1280x1024 (SXGA)  | 7        | 7.95%   |
| 1600x900 (HD+)    | 6        | 6.82%   |
| 1440x900 (WXGA+)  | 6        | 6.82%   |
| 3840x2160 (4K)    | 5        | 5.68%   |
| 2560x1440 (QHD)   | 4        | 4.55%   |
| 3286x1080         | 2        | 2.27%   |
| 2944x1080         | 2        | 2.27%   |
| 2560x1080         | 2        | 2.27%   |
| 1280x720 (HD)     | 2        | 2.27%   |
| Unknown           | 2        | 2.27%   |
| 1920x1200 (WUXGA) | 1        | 1.14%   |
| 1360x768          | 1        | 1.14%   |
| 1280x960          | 1        | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 12       | 13.33%  |
| 19      | 11       | 12.22%  |
| 18      | 10       | 11.11%  |
| 24      | 9        | 10%     |
| 21      | 9        | 10%     |
| Unknown | 9        | 10%     |
| 27      | 5        | 5.56%   |
| 17      | 5        | 5.56%   |
| 12      | 3        | 3.33%   |
| 84      | 2        | 2.22%   |
| 72      | 2        | 2.22%   |
| 43      | 2        | 2.22%   |
| 34      | 2        | 2.22%   |
| 15      | 2        | 2.22%   |
| 54      | 1        | 1.11%   |
| 40      | 1        | 1.11%   |
| 36      | 1        | 1.11%   |
| 32      | 1        | 1.11%   |
| 26      | 1        | 1.11%   |
| 22      | 1        | 1.11%   |
| 20      | 1        | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 29       | 32.95%  |
| 501-600     | 26       | 29.55%  |
| Unknown     | 9        | 10.23%  |
| 301-350     | 6        | 6.82%   |
| 701-800     | 4        | 4.55%   |
| 1501-2000   | 4        | 4.55%   |
| 351-400     | 3        | 3.41%   |
| 201-300     | 3        | 3.41%   |
| 901-1000    | 2        | 2.27%   |
| 801-900     | 1        | 1.14%   |
| 1001-1500   | 1        | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 52       | 65%     |
| Unknown | 9        | 11.25%  |
| 16/10   | 7        | 8.75%   |
| 5/4     | 6        | 7.5%    |
| 4/3     | 4        | 5%      |
| 21/9    | 2        | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 27.78%  |
| 151-200        | 15       | 16.67%  |
| 141-150        | 13       | 14.44%  |
| Unknown        | 9        | 10%     |
| More than 1000 | 5        | 5.56%   |
| 301-350        | 5        | 5.56%   |
| 251-300        | 5        | 5.56%   |
| 501-1000       | 4        | 4.44%   |
| 71-80          | 3        | 3.33%   |
| 351-500        | 3        | 3.33%   |
| 131-140        | 1        | 1.11%   |
| 111-120        | 1        | 1.11%   |
| 101-110        | 1        | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 52       | 61.9%   |
| 101-120 | 13       | 15.48%  |
| Unknown | 9        | 10.71%  |
| 1-50    | 5        | 5.95%   |
| 161-240 | 4        | 4.76%   |
| 121-160 | 1        | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 73.75%  |
| 2     | 16       | 20%     |
| 0     | 5        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 55       | 49.55%  |
| Intel                           | 23       | 20.72%  |
| Qualcomm Atheros                | 7        | 6.31%   |
| TP-Link                         | 4        | 3.6%    |
| Broadcom                        | 4        | 3.6%    |
| Ralink                          | 3        | 2.7%    |
| Xiaomi                          | 2        | 1.8%    |
| Ralink Technology               | 2        | 1.8%    |
| Nvidia                          | 2        | 1.8%    |
| Linksys                         | 2        | 1.8%    |
| Huawei Technologies             | 2        | 1.8%    |
| Qualcomm Atheros Communications | 1        | 0.9%    |
| MediaTek                        | 1        | 0.9%    |
| Davicom Semiconductor           | 1        | 0.9%    |
| D-Link                          | 1        | 0.9%    |
| Broadcom Limited                | 1        | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 43       | 36.13%  |
| Realtek RTL8125 2.5GbE Controller                                                             | 4        | 3.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 2.52%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 2.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 1.68%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2        | 1.68%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 1.68%   |
| Intel Wireless-AC 9260                                                                        | 2        | 1.68%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.68%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 1.68%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 2        | 1.68%   |
| Intel Centrino Advanced-N 6235                                                                | 2        | 1.68%   |
| Huawei MAR-LX1M                                                                               | 2        | 1.68%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 2        | 1.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.84%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 0.84%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.84%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.84%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.84%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 1        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.84%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.84%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.84%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 0.84%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 0.84%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 0.84%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1        | 0.84%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 0.84%   |
| Nvidia MCP79 Ethernet                                                                         | 1        | 0.84%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 30.56%  |
| Intel                           | 7        | 19.44%  |
| TP-Link                         | 4        | 11.11%  |
| Qualcomm Atheros                | 4        | 11.11%  |
| Ralink                          | 3        | 8.33%   |
| Ralink Technology               | 2        | 5.56%   |
| Linksys                         | 2        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| MediaTek                        | 1        | 2.78%   |
| D-Link                          | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 8.33%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 5.56%   |
| Intel Wireless-AC 9260                                                                        | 2        | 5.56%   |
| Intel Centrino Advanced-N 6235                                                                | 2        | 5.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 2.78%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 2.78%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 2.78%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 2.78%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.78%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 2.78%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 2.78%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 2.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 2.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 2.78%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                | 1        | 2.78%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 2.78%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 2.78%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                                | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 50       | 60.98%  |
| Intel                 | 17       | 20.73%  |
| Broadcom              | 4        | 4.88%   |
| Qualcomm Atheros      | 3        | 3.66%   |
| Xiaomi                | 2        | 2.44%   |
| Nvidia                | 2        | 2.44%   |
| Huawei Technologies   | 2        | 2.44%   |
| Davicom Semiconductor | 1        | 1.22%   |
| Broadcom Limited      | 1        | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 51.81%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 4.82%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.41%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.41%   |
| Huawei MAR-LX1M                                                   | 2        | 2.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.2%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.2%    |
| Nvidia MCP79 Ethernet                                             | 1        | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 1        | 1.2%    |
| Intel I350 Gigabit Network Connection                             | 1        | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.2%    |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                | 1        | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.2%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.2%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.2%    |
| Davicom DM9102 Fast Ethernet Controller                           | 1        | 1.2%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.2%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.2%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 69.72%  |
| WiFi     | 33       | 30.28%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 77.38%  |
| WiFi     | 19       | 22.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 62.03%  |
| 2     | 29       | 36.71%  |
| 4     | 1        | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 98.72%  |
| Yes  | 1        | 1.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 40.91%  |
| Intel                   | 7        | 31.82%  |
| ASUSTek Computer        | 3        | 13.64%  |
| Realtek Semiconductor   | 1        | 4.55%   |
| MediaTek                | 1        | 4.55%   |
| Broadcom                | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 9        | 40.91%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 2        | 9.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 2        | 9.09%   |
| Realtek Bluetooth Radio                                      | 1        | 4.55%   |
| MediaTek Wireless_Device                                     | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 1        | 4.55%   |
| Intel AX201 Bluetooth                                        | 1        | 4.55%   |
| Intel AX200 Bluetooth                                        | 1        | 4.55%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 4.55%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 4.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1        | 4.55%   |
| ASUS Bluetooth Radio                                         | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 49       | 38.58%  |
| AMD                     | 31       | 24.41%  |
| Nvidia                  | 29       | 22.83%  |
| C-Media Electronics     | 4        | 3.15%   |
| Unknown                 | 1        | 0.79%   |
| Soundprese              | 1        | 0.79%   |
| Sony                    | 1        | 0.79%   |
| Realtek Semiconductor   | 1        | 0.79%   |
| Medeli Electronics      | 1        | 0.79%   |
| Logitech                | 1        | 0.79%   |
| GN Netcom               | 1        | 0.79%   |
| Ensoniq                 | 1        | 0.79%   |
| Creative Labs           | 1        | 0.79%   |
| Corsair                 | 1        | 0.79%   |
| BEHRINGER International | 1        | 0.79%   |
| Astro Gaming            | 1        | 0.79%   |
| Argosy Research         | 1        | 0.79%   |
| A-DATA Technology       | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 6.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 5.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 5.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 4.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 4.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 4.64%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.65%   |
| Nvidia High Definition Audio Controller                                    | 4        | 2.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.99%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.32%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.32%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.32%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.32%   |
| Unknown USB PnP Audio Device                                               | 1        | 0.66%   |
| Soundprese HD-II                                                           | 1        | 0.66%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.66%   |
| Realtek Semiconductor USB Condenser Microphone                             | 1        | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.66%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.66%   |
| Medeli Electronics USB Audio Device                                        | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 22.81%  |
| Micron Technology   | 9        | 15.79%  |
| SK hynix            | 6        | 10.53%  |
| Samsung Electronics | 5        | 8.77%   |
| A-DATA Technology   | 5        | 8.77%   |
| Unknown             | 4        | 7.02%   |
| Crucial             | 4        | 7.02%   |
| Corsair             | 4        | 7.02%   |
| G.Skill             | 3        | 5.26%   |
| V-Color             | 1        | 1.75%   |
| Patriot             | 1        | 1.75%   |
| Kimtigo             | 1        | 1.75%   |
| Unknown             | 1        | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 5        | 7.81%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s    | 3        | 4.69%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s     | 2        | 3.13%   |
| A-DATA RAM Module 16GB DIMM DDR4 2667MT/s                | 2        | 3.13%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2        | 3.13%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s          | 1        | 1.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 1.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 1.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1        | 1.56%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s      | 1        | 1.56%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s              | 1        | 1.56%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.56%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.56%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 1.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1        | 1.56%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s     | 1        | 1.56%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s         | 1        | 1.56%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.56%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 1.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 1        | 1.56%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s  | 1        | 1.56%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s          | 1        | 1.56%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s | 1        | 1.56%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 1        | 1.56%   |
| Micron RAM 16JTF25664AZ-1G4F1 2GB DIMM 1333MT/s          | 1        | 1.56%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s   | 1        | 1.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 1        | 1.56%   |
| Kingston RAM KHX2666C15/16G 16GB DIMM DDR4 2666MT/s      | 1        | 1.56%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 1.56%   |
| Kingston RAM 99U5624-001.A00G 8GB SODIMM DDR4 2667MT/s   | 1        | 1.56%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.56%   |
| Kingston RAM 99U5471-066.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Kingston RAM 99U5403-067.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Kingston RAM 99U5403-050.A00 F 4GB DIMM DDR3 667MT/s     | 1        | 1.56%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 3200MT/s     | 1        | 1.56%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s     | 1        | 1.56%   |
| Kingston RAM 9905403-038.A00G 4GB DIMM DDR3 1333MT/s     | 1        | 1.56%   |
| Kingston RAM 9905402-413.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 22       | 48.89%  |
| DDR3    | 18       | 40%     |
| SDRAM   | 2        | 4.44%   |
| DDR5    | 1        | 2.22%   |
| DDR2    | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 39       | 90.7%   |
| SODIMM | 4        | 9.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 33.33%  |
| 4096  | 16       | 33.33%  |
| 16384 | 8        | 16.67%  |
| 2048  | 5        | 10.42%  |
| 32768 | 3        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 13       | 24.07%  |
| 1333  | 6        | 11.11%  |
| 3600  | 5        | 9.26%   |
| 2667  | 4        | 7.41%   |
| 2933  | 3        | 5.56%   |
| 2400  | 3        | 5.56%   |
| 3200  | 2        | 3.7%    |
| 2133  | 2        | 3.7%    |
| 667   | 2        | 3.7%    |
| 4800  | 1        | 1.85%   |
| 3866  | 1        | 1.85%   |
| 3666  | 1        | 1.85%   |
| 3466  | 1        | 1.85%   |
| 3400  | 1        | 1.85%   |
| 3100  | 1        | 1.85%   |
| 2934  | 1        | 1.85%   |
| 2800  | 1        | 1.85%   |
| 2666  | 1        | 1.85%   |
| 2465  | 1        | 1.85%   |
| 2448  | 1        | 1.85%   |
| 1867  | 1        | 1.85%   |
| 1866  | 1        | 1.85%   |
| 1800  | 1        | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 50%     |
| Canon           | 2        | 33.33%  |
| Seiko Epson     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson L3110 Series           | 1        | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1        | 16.67%  |
| HP DeskJet 2130 series             | 1        | 16.67%  |
| HP Deskjet 2050 J510               | 1        | 16.67%  |
| Canon G2000 series                 | 1        | 16.67%  |
| Canon E400 series                  | 1        | 16.67%  |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 6        | 27.27%  |
| Microdia                | 4        | 18.18%  |
| Microsoft               | 3        | 13.64%  |
| Chicony Electronics     | 2        | 9.09%   |
| Z-Star Microelectronics | 1        | 4.55%   |
| TANDBERG                | 1        | 4.55%   |
| Philips (or NXP)        | 1        | 4.55%   |
| Jieli Technology        | 1        | 4.55%   |
| Huawei Technologies     | 1        | 4.55%   |
| Aveo Technology         | 1        | 4.55%   |
| Arkmicro Technologies   | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 3        | 13.64%  |
| Microsoft LifeCam HD-3000             | 2        | 9.09%   |
| Microdia USB 2.0 Camera               | 2        | 9.09%   |
| Microdia Integrated Camera            | 2        | 9.09%   |
| Z-Star A4 TECH USB2.0 PC Camera E     | 1        | 4.55%   |
| TANDBERG PrecisionHD Camera           | 1        | 4.55%   |
| Philips (or NXP) SPC 1300NC PC Camera | 1        | 4.55%   |
| Microsoft LifeCam Cinema              | 1        | 4.55%   |
| Logitech Webcam Pro 9000              | 1        | 4.55%   |
| Logitech Webcam C310                  | 1        | 4.55%   |
| Logitech HD Pro Webcam C920           | 1        | 4.55%   |
| Jieli USB PHY 2.0                     | 1        | 4.55%   |
| Huawei UVC Camera                     | 1        | 4.55%   |
| Chicony HP High Definition 1MP Webcam | 1        | 4.55%   |
| Chicony HP 720p HD Monitor Webcam     | 1        | 4.55%   |
| Aveo USB2.0 UVC PC Camera             | 1        | 4.55%   |
| Arkmicro Acme CA04                    | 1        | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 1        | 33.33%  |
| OmniKey                    | 1        | 33.33%  |
| Athena Smartcard Solutions | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| OmniKey CardMan 3021 / 3121                            | 1        | 33.33%  |
| Athena Smartcard Solutions ASEDrive CCID               | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 63       | 79.75%  |
| 1     | 13       | 16.46%  |
| 3     | 2        | 2.53%   |
| 2     | 1        | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 35%     |
| Net/wireless             | 5        | 25%     |
| Communication controller | 3        | 15%     |
| Chipcard                 | 3        | 15%     |
| Sound                    | 1        | 5%      |
| Network                  | 1        | 5%      |


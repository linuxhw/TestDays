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

Total: 126

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | K9N6PGM2-V2                 | [a79d33d7cf](https://linux-hardware.org/?probe=a79d33d7cf) | May 06, 2024 |
| Dell          | 0WMJ54 A00                  | [306aac13ae](https://linux-hardware.org/?probe=306aac13ae) | Mar 18, 2024 |
| Lenovo        | SHARKBAY NOK                | [abfba381b6](https://linux-hardware.org/?probe=abfba381b6) | Mar 02, 2024 |
| Lenovo        | SHARKBAY NOK                | [5d03e50172](https://linux-hardware.org/?probe=5d03e50172) | Mar 02, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [d72d6f6951](https://linux-hardware.org/?probe=d72d6f6951) | Feb 09, 2024 |
| Gigabyte      | H110M-H-CF                  | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| ZOTAC         | NM10                        | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| MSI           | A320M-A PRO                 | [f118f7960d](https://linux-hardware.org/?probe=f118f7960d) | Jan 18, 2024 |
| Dell          | 0GY6Y8 A01                  | [bece296ba4](https://linux-hardware.org/?probe=bece296ba4) | Jan 15, 2024 |
| Dell          | 0GY6Y8 A01                  | [6eb80a3aae](https://linux-hardware.org/?probe=6eb80a3aae) | Jan 15, 2024 |
| Lenovo        | Annapurna CRB NO DPK        | [7d003c702a](https://linux-hardware.org/?probe=7d003c702a) | Dec 27, 2023 |
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
| OpenMandriva 4.2   | 9        | 9.18%   |
| Ubuntu 20.04       | 8        | 8.16%   |
| Ubuntu 22.04       | 6        | 6.12%   |
| Ubuntu 18.04       | 4        | 4.08%   |
| OpenMandriva 23.03 | 4        | 4.08%   |
| OpenMandriva 4.3   | 3        | 3.06%   |
| Linux Mint 20.2    | 3        | 3.06%   |
| Zorin 16           | 2        | 2.04%   |
| Xubuntu 22.04      | 2        | 2.04%   |
| Ubuntu 22.10       | 2        | 2.04%   |
| Pop!_OS 21.04      | 2        | 2.04%   |
| OpenMandriva 23.01 | 2        | 2.04%   |
| Lubuntu 22.04      | 2        | 2.04%   |
| Linux Mint 19.3    | 2        | 2.04%   |
| KDE neon 22.04     | 2        | 2.04%   |
| Fedora 38          | 2        | 2.04%   |
| Fedora 32          | 2        | 2.04%   |
| Zorin 15           | 1        | 1.02%   |
| Zorin 12           | 1        | 1.02%   |
| UbuntuDDE 20.04    | 1        | 1.02%   |
| Ubuntu 20.10       | 1        | 1.02%   |
| Ubuntu 19.10       | 1        | 1.02%   |
| ROSA R8.1          | 1        | 1.02%   |
| ROSA R11.1         | 1        | 1.02%   |
| ROSA R11           | 1        | 1.02%   |
| Pop!_OS 22.04      | 1        | 1.02%   |
| Pop!_OS 20.10      | 1        | 1.02%   |
| Pop!_OS 20.04      | 1        | 1.02%   |
| OpenMandriva 5.0   | 1        | 1.02%   |
| OpenMandriva 4.50  | 1        | 1.02%   |
| OpenMandriva 23.11 | 1        | 1.02%   |
| OpenMandriva 23.08 | 1        | 1.02%   |
| OpenMandriva 22.12 | 1        | 1.02%   |
| Manjaro 23.1.3     | 1        | 1.02%   |
| Manjaro 22.0.4     | 1        | 1.02%   |
| Manjaro 22.0.0     | 1        | 1.02%   |
| Manjaro 21.3.5     | 1        | 1.02%   |
| Manjaro 21.2.5     | 1        | 1.02%   |
| Manjaro 21.2.0     | 1        | 1.02%   |
| Manjaro            | 1        | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 22       | 23.91%  |
| OpenMandriva | 21       | 22.83%  |
| Linux Mint   | 7        | 7.61%   |
| Fedora       | 7        | 7.61%   |
| Manjaro      | 6        | 6.52%   |
| Pop!_OS      | 5        | 5.43%   |
| Zorin        | 4        | 4.35%   |
| KDE neon     | 3        | 3.26%   |
| Xubuntu      | 2        | 2.17%   |
| ROSA         | 2        | 2.17%   |
| Lubuntu      | 2        | 2.17%   |
| Elementary   | 2        | 2.17%   |
| Debian       | 2        | 2.17%   |
| ArcoLinux    | 2        | 2.17%   |
| Arch         | 2        | 2.17%   |
| UbuntuDDE    | 1        | 1.09%   |
| EndeavourOS  | 1        | 1.09%   |
| BlackPanther | 1        | 1.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.14-desktop-1omv4002    | 9        | 8.41%   |
| 6.2.6-desktop-1omv2390      | 4        | 3.74%   |
| 5.4.0-70-generic            | 3        | 2.8%    |
| 5.16.7-desktop-1omv4003     | 3        | 2.8%    |
| 6.4.11-desktop-1omv2390     | 2        | 1.87%   |
| 5.4.0-42-generic            | 2        | 1.87%   |
| 5.19.0-45-generic           | 2        | 1.87%   |
| 5.15.0-53-generic           | 2        | 1.87%   |
| 6.7.0-custom                | 1        | 0.93%   |
| 6.7.0-arch3-1               | 1        | 0.93%   |
| 6.6.2-desktop-1omv2390      | 1        | 0.93%   |
| 6.6.19-1-MANJARO            | 1        | 0.93%   |
| 6.6.0-custom                | 1        | 0.93%   |
| 6.5.6-200.fc38.x86_64       | 1        | 0.93%   |
| 6.5.0-21-generic            | 1        | 0.93%   |
| 6.4.6-76060406-generic      | 1        | 0.93%   |
| 6.3.8-200.fc38.x86_64       | 1        | 0.93%   |
| 6.3.3-custom                | 1        | 0.93%   |
| 6.2.7-200.fc37.x86_64       | 1        | 0.93%   |
| 6.2.0-33-generic            | 1        | 0.93%   |
| 6.1.4-desktop-1omv2301      | 1        | 0.93%   |
| 6.1.2-arch1-1               | 1        | 0.93%   |
| 6.1.1-desktop-1omv2290      | 1        | 0.93%   |
| 6.1.1-1-MANJARO             | 1        | 0.93%   |
| 6.1.0-custom                | 1        | 0.93%   |
| 6.0.2-2-MANJARO             | 1        | 0.93%   |
| 6.0.11-300.fc37.x86_64      | 1        | 0.93%   |
| 6.0.10-desktop-2omv22090    | 1        | 0.93%   |
| 5.9.9-arch1-1               | 1        | 0.93%   |
| 5.9.14-arch1-1              | 1        | 0.93%   |
| 5.8.0-7630-generic          | 1        | 0.93%   |
| 5.8.0-50-generic            | 1        | 0.93%   |
| 5.8.0-41-generic            | 1        | 0.93%   |
| 5.8.0-34-generic            | 1        | 0.93%   |
| 5.7.0-1-amd64               | 1        | 0.93%   |
| 5.6.19-300.fc32.x86_64      | 1        | 0.93%   |
| 5.6.16-300.fc32.x86_64      | 1        | 0.93%   |
| 5.6.14-desktop-2bP          | 1        | 0.93%   |
| 5.6.13-arch1-1              | 1        | 0.93%   |
| 5.4.40-generic-1rosa-x86_64 | 1        | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 12       | 11.54%  |
| 5.15.0  | 11       | 10.58%  |
| 5.10.14 | 9        | 8.65%   |
| 4.15.0  | 6        | 5.77%   |
| 5.19.0  | 5        | 4.81%   |
| 6.2.6   | 4        | 3.85%   |
| 5.8.0   | 4        | 3.85%   |
| 5.11.0  | 4        | 3.85%   |
| 5.16.7  | 3        | 2.88%   |
| 6.7.0   | 2        | 1.92%   |
| 6.4.11  | 2        | 1.92%   |
| 6.1.1   | 2        | 1.92%   |
| 5.3.0   | 2        | 1.92%   |
| 5.13.0  | 2        | 1.92%   |
| 6.6.2   | 1        | 0.96%   |
| 6.6.19  | 1        | 0.96%   |
| 6.6.0   | 1        | 0.96%   |
| 6.5.6   | 1        | 0.96%   |
| 6.5.0   | 1        | 0.96%   |
| 6.4.6   | 1        | 0.96%   |
| 6.3.8   | 1        | 0.96%   |
| 6.3.3   | 1        | 0.96%   |
| 6.2.7   | 1        | 0.96%   |
| 6.2.0   | 1        | 0.96%   |
| 6.1.4   | 1        | 0.96%   |
| 6.1.2   | 1        | 0.96%   |
| 6.1.0   | 1        | 0.96%   |
| 6.0.2   | 1        | 0.96%   |
| 6.0.11  | 1        | 0.96%   |
| 6.0.10  | 1        | 0.96%   |
| 5.9.9   | 1        | 0.96%   |
| 5.9.14  | 1        | 0.96%   |
| 5.7.0   | 1        | 0.96%   |
| 5.6.19  | 1        | 0.96%   |
| 5.6.16  | 1        | 0.96%   |
| 5.6.14  | 1        | 0.96%   |
| 5.6.13  | 1        | 0.96%   |
| 5.4.40  | 1        | 0.96%   |
| 5.18.13 | 1        | 0.96%   |
| 5.18.12 | 1        | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 13       | 12.5%   |
| 5.15    | 13       | 12.5%   |
| 5.10    | 12       | 11.54%  |
| 6.2     | 6        | 5.77%   |
| 4.15    | 6        | 5.77%   |
| 6.1     | 5        | 4.81%   |
| 5.19    | 5        | 4.81%   |
| 5.11    | 5        | 4.81%   |
| 5.8     | 4        | 3.85%   |
| 5.6     | 4        | 3.85%   |
| 6.6     | 3        | 2.88%   |
| 6.4     | 3        | 2.88%   |
| 6.0     | 3        | 2.88%   |
| 5.16    | 3        | 2.88%   |
| 5.13    | 3        | 2.88%   |
| 6.7     | 2        | 1.92%   |
| 6.5     | 2        | 1.92%   |
| 6.3     | 2        | 1.92%   |
| 5.9     | 2        | 1.92%   |
| 5.3     | 2        | 1.92%   |
| 5.18    | 2        | 1.92%   |
| 5.7     | 1        | 0.96%   |
| 5.14    | 1        | 0.96%   |
| 4.18    | 1        | 0.96%   |
| 4.1     | 1        | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 96.43%  |
| i686   | 3        | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 38       | 43.68%  |
| KDE5          | 24       | 27.59%  |
| Unknown       | 6        | 6.9%    |
| X-Cinnamon    | 5        | 5.75%   |
| XFCE          | 3        | 3.45%   |
| LXQt          | 3        | 3.45%   |
| Pantheon      | 2        | 2.3%    |
| MATE          | 2        | 2.3%    |
| KDE           | 1        | 1.15%   |
| Hyprland      | 1        | 1.15%   |
| GNOME Classic | 1        | 1.15%   |
| Deepin        | 1        | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 67       | 77.01%  |
| Wayland | 19       | 21.84%  |
| Tty     | 1        | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 40.91%  |
| SDDM    | 26       | 29.55%  |
| GDM     | 10       | 11.36%  |
| GDM3    | 9        | 10.23%  |
| LightDM | 5        | 5.68%   |
| TDM     | 2        | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 41       | 45.05%  |
| es_CR   | 38       | 41.76%  |
| Unknown | 5        | 5.49%   |
| es_ES   | 4        | 4.4%    |
| es_MX   | 2        | 2.2%    |
| de_DE   | 1        | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 43       | 50.59%  |
| BIOS | 42       | 49.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 52       | 58.43%  |
| Overlay | 18       | 20.22%  |
| Btrfs   | 12       | 13.48%  |
| Tmpfs   | 5        | 5.62%   |
| Xfs     | 1        | 1.12%   |
| Unknown | 1        | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 41       | 46.59%  |
| Unknown | 38       | 43.18%  |
| MBR     | 9        | 10.23%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 77.65%  |
| Yes       | 19       | 22.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 59.77%  |
| Yes       | 35       | 40.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 19.05%  |
| Gigabyte Technology | 14       | 16.67%  |
| Dell                | 14       | 16.67%  |
| MSI                 | 11       | 13.1%   |
| ASRock              | 8        | 9.52%   |
| Hewlett-Packard     | 4        | 4.76%   |
| Lenovo              | 3        | 3.57%   |
| Intel               | 2        | 2.38%   |
| Unknown             | 2        | 2.38%   |
| ZOTAC               | 1        | 1.19%   |
| TPV-INVENTA         | 1        | 1.19%   |
| Supermicro          | 1        | 1.19%   |
| Pegatron            | 1        | 1.19%   |
| MACHINIST           | 1        | 1.19%   |
| Gateway             | 1        | 1.19%   |
| Foxconn             | 1        | 1.19%   |
| Biostar             | 1        | 1.19%   |
| Alienware           | 1        | 1.19%   |
| ABIT                | 1        | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 3020                       | 6        | 7.14%   |
| MSI MS-7C51                              | 3        | 3.57%   |
| Gigabyte H110M-H                         | 2        | 2.38%   |
| Gigabyte B250M-DS3H                      | 2        | 2.38%   |
| Dell OptiPlex 7040                       | 2        | 2.38%   |
| ASUS TUF Gaming X570-PLUS                | 2        | 2.38%   |
| ASUS PRIME H310M-E R2.0                  | 2        | 2.38%   |
| ASUS PRIME A320M-K                       | 2        | 2.38%   |
| ASRock B450 Steel Legend                 | 2        | 2.38%   |
| Unknown                                  | 2        | 2.38%   |
| ZOTAC NM10                               | 1        | 1.19%   |
| TPV-INVENTA 18-2003LA                    | 1        | 1.19%   |
| Supermicro X9DAi                         | 1        | 1.19%   |
| Pegatron CQ2728LA                        | 1        | 1.19%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 1.19%   |
| MSI MS-7D77                              | 1        | 1.19%   |
| MSI MS-7B98                              | 1        | 1.19%   |
| MSI MS-7B86                              | 1        | 1.19%   |
| MSI MS-7992                              | 1        | 1.19%   |
| MSI MS-7693                              | 1        | 1.19%   |
| MSI MS-7636                              | 1        | 1.19%   |
| MSI MS-7309                              | 1        | 1.19%   |
| MACHINIST X79 V2.82H                     | 1        | 1.19%   |
| Lenovo ThinkCentre M93p 10A8S41Q00       | 1        | 1.19%   |
| Lenovo ThinkCentre M78 21131C7           | 1        | 1.19%   |
| Lenovo H530S 10132                       | 1        | 1.19%   |
| Intel DG41WV AAE90316-103                | 1        | 1.19%   |
| Intel D33217CK G76541-302                | 1        | 1.19%   |
| HP Z800 Workstation                      | 1        | 1.19%   |
| HP ProDesk 600 G4 SFF                    | 1        | 1.19%   |
| HP EliteDesk 800 G1 TWR                  | 1        | 1.19%   |
| HP Compaq 6005 Pro SFF PC                | 1        | 1.19%   |
| Gigabyte Z690 UD AX DDR4                 | 1        | 1.19%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.19%   |
| Gigabyte X570 I AORUS PRO WIFI           | 1        | 1.19%   |
| Gigabyte H81M-DS2                        | 1        | 1.19%   |
| Gigabyte H410M H                         | 1        | 1.19%   |
| Gigabyte H110M-S2                        | 1        | 1.19%   |
| Gigabyte GA-970A-D3                      | 1        | 1.19%   |
| Gigabyte GA-78LMT-USB3 6.0               | 1        | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 12       | 14.29%  |
| ASUS PRIME             | 5        | 5.95%   |
| MSI MS-7C51            | 3        | 3.57%   |
| ASUS TUF               | 3        | 3.57%   |
| Lenovo ThinkCentre     | 2        | 2.38%   |
| Gigabyte H110M-H       | 2        | 2.38%   |
| Gigabyte B250M-DS3H    | 2        | 2.38%   |
| Dell Precision         | 2        | 2.38%   |
| ASUS SABERTOOTH        | 2        | 2.38%   |
| ASRock B450            | 2        | 2.38%   |
| Unknown                | 2        | 2.38%   |
| ZOTAC NM10             | 1        | 1.19%   |
| TPV-INVENTA 18-2003LA  | 1        | 1.19%   |
| Supermicro X9DAi       | 1        | 1.19%   |
| Pegatron CQ2728LA      | 1        | 1.19%   |
| MSI Z390               | 1        | 1.19%   |
| MSI MS-7D77            | 1        | 1.19%   |
| MSI MS-7B98            | 1        | 1.19%   |
| MSI MS-7B86            | 1        | 1.19%   |
| MSI MS-7992            | 1        | 1.19%   |
| MSI MS-7693            | 1        | 1.19%   |
| MSI MS-7636            | 1        | 1.19%   |
| MSI MS-7309            | 1        | 1.19%   |
| MACHINIST X79          | 1        | 1.19%   |
| Lenovo H530S           | 1        | 1.19%   |
| Intel DG41WV           | 1        | 1.19%   |
| Intel D33217CK         | 1        | 1.19%   |
| HP Z800                | 1        | 1.19%   |
| HP ProDesk             | 1        | 1.19%   |
| HP EliteDesk           | 1        | 1.19%   |
| HP Compaq              | 1        | 1.19%   |
| Gigabyte Z690          | 1        | 1.19%   |
| Gigabyte Z170X-Gaming  | 1        | 1.19%   |
| Gigabyte X570          | 1        | 1.19%   |
| Gigabyte H81M-DS2      | 1        | 1.19%   |
| Gigabyte H410M         | 1        | 1.19%   |
| Gigabyte H110M-S2      | 1        | 1.19%   |
| Gigabyte GA-970A-D3    | 1        | 1.19%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.19%   |
| Gigabyte B550M         | 1        | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 13.1%   |
| 2016 | 11       | 13.1%   |
| 2014 | 10       | 11.9%   |
| 2013 | 9        | 10.71%  |
| 2012 | 7        | 8.33%   |
| 2018 | 5        | 5.95%   |
| 2020 | 4        | 4.76%   |
| 2010 | 4        | 4.76%   |
| 2021 | 3        | 3.57%   |
| 2017 | 3        | 3.57%   |
| 2015 | 3        | 3.57%   |
| 2011 | 3        | 3.57%   |
| 2009 | 3        | 3.57%   |
| 2022 | 2        | 2.38%   |
| 2008 | 2        | 2.38%   |
| 2007 | 2        | 2.38%   |
| 2005 | 2        | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 84       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 79       | 94.05%  |
| Enabled  | 5        | 5.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 25       | 28.41%  |
| 8.01-16.0       | 19       | 21.59%  |
| 3.01-4.0        | 13       | 14.77%  |
| 4.01-8.0        | 11       | 12.5%   |
| 32.01-64.0      | 9        | 10.23%  |
| 1.01-2.0        | 5        | 5.68%   |
| 24.01-32.0      | 2        | 2.27%   |
| 64.01-256.0     | 2        | 2.27%   |
| More than 256.0 | 1        | 1.14%   |
| 2.01-3.0        | 1        | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 38       | 39.58%  |
| 2.01-3.0   | 19       | 19.79%  |
| 4.01-8.0   | 17       | 17.71%  |
| 3.01-4.0   | 8        | 8.33%   |
| 0.51-1.0   | 6        | 6.25%   |
| 0.01-0.5   | 3        | 3.13%   |
| 16.01-24.0 | 2        | 2.08%   |
| 8.01-16.0  | 2        | 2.08%   |
| 24.01-32.0 | 1        | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 47.13%  |
| 2      | 28       | 32.18%  |
| 4      | 7        | 8.05%   |
| 3      | 7        | 8.05%   |
| 8      | 1        | 1.15%   |
| 7      | 1        | 1.15%   |
| 6      | 1        | 1.15%   |
| 5      | 1        | 1.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 57.47%  |
| Yes       | 37       | 42.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 98.81%  |
| No        | 1        | 1.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 58.82%  |
| Yes       | 35       | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 73.86%  |
| Yes       | 23       | 26.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Costa Rica | 84       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| San José   | 40       | 42.11%  |
| Heredia     | 20       | 21.05%  |
| Escazu      | 6        | 6.32%   |
| Alajuela    | 4        | 4.21%   |
| Liberia     | 3        | 3.16%   |
| Santa Ana   | 2        | 2.11%   |
| Grecia      | 2        | 2.11%   |
| Cartago     | 2        | 2.11%   |
| Tres Rios   | 1        | 1.05%   |
| Tibas       | 1        | 1.05%   |
| Siquirres   | 1        | 1.05%   |
| Santa Fe    | 1        | 1.05%   |
| San Ramon   | 1        | 1.05%   |
| San Pedro   | 1        | 1.05%   |
| Rio Segundo | 1        | 1.05%   |
| Puntarenas  | 1        | 1.05%   |
| Pavas       | 1        | 1.05%   |
| Palmares    | 1        | 1.05%   |
| Nosara      | 1        | 1.05%   |
| Naranjo     | 1        | 1.05%   |
| Curridabat  | 1        | 1.05%   |
| Cariblanca  | 1        | 1.05%   |
| Bajo Perez  | 1        | 1.05%   |
| Alajuelita  | 1        | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 31       | 52     | 21.23%  |
| WDC                   | 22       | 30     | 15.07%  |
| Kingston              | 15       | 22     | 10.27%  |
| Toshiba               | 12       | 14     | 8.22%   |
| A-DATA Technology     | 12       | 13     | 8.22%   |
| Samsung Electronics   | 7        | 17     | 4.79%   |
| Hitachi               | 7        | 9      | 4.79%   |
| Realtek Semiconductor | 5        | 7      | 3.42%   |
| XPG                   | 4        | 4      | 2.74%   |
| Patriot               | 4        | 6      | 2.74%   |
| HGST                  | 3        | 3      | 2.05%   |
| ZOTAC                 | 2        | 3      | 1.37%   |
| Unknown               | 2        | 3      | 1.37%   |
| SanDisk               | 2        | 3      | 1.37%   |
| Mushkin               | 2        | 2      | 1.37%   |
| Maxtor                | 2        | 2      | 1.37%   |
| Crucial               | 2        | 2      | 1.37%   |
| WD MediaMax           | 1        | 1      | 0.68%   |
| Team                  | 1        | 1      | 0.68%   |
| T-FORCE               | 1        | 1      | 0.68%   |
| Phison Electronics    | 1        | 1      | 0.68%   |
| Netac                 | 1        | 2      | 0.68%   |
| JMicron Technology    | 1        | 1      | 0.68%   |
| Intel                 | 1        | 1      | 0.68%   |
| HPE                   | 1        | 1      | 0.68%   |
| Gigabyte Technology   | 1        | 2      | 0.68%   |
| CT120BX5              | 1        | 1      | 0.68%   |
| Biostar               | 1        | 1      | 0.68%   |
| ADATA Technology      | 1        | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD             | 7        | 4.32%   |
| Toshiba DT01ACA100 1TB                      | 6        | 3.7%    |
| A-DATA SU630 480GB SSD                      | 5        | 3.09%   |
| WDC WD10EZEX-75WN4A1 1TB                    | 3        | 1.85%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 3        | 1.85%   |
| Seagate ST1000DM003-1CH162 1TB              | 3        | 1.85%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB | 3        | 1.85%   |
| A-DATA SU650 120GB SSD                      | 3        | 1.85%   |
| XPG GAMMIX S11 Pro 512GB                    | 2        | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 2        | 1.23%   |
| Seagate ST8000DM004-2CX188 8TB              | 2        | 1.23%   |
| Seagate ST500DM002-1BD142 500GB             | 2        | 1.23%   |
| Seagate ST380815AS 80GB                     | 2        | 1.23%   |
| Seagate ST2000LM015-2E8174 2TB              | 2        | 1.23%   |
| Seagate ST2000LM007-1R8174 2TB              | 2        | 1.23%   |
| Mushkin MKNSSDEL240GB                       | 2        | 1.23%   |
| Kingston SUV400S37120G 120GB SSD            | 2        | 1.23%   |
| Hitachi HUA722020ALA331 2TB                 | 2        | 1.23%   |
| HGST HTS541075A9E680 752GB                  | 2        | 1.23%   |
| ZOTAC ZTSSD-S11-240G-P 240GB                | 1        | 0.62%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB               | 1        | 0.62%   |
| XPG NVMe SSD Drive 512GB                    | 1        | 0.62%   |
| XPG NVMe SSD Drive 1TB                      | 1        | 0.62%   |
| WDC WDS120G2G0A-00JH30 120GB SSD            | 1        | 0.62%   |
| WDC WD6400AAKS-22A7B0 640GB                 | 1        | 0.62%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1        | 0.62%   |
| WDC WD5000AAKS-00V1A0 500GB                 | 1        | 0.62%   |
| WDC WD2500AAJS-00VTA0 250GB                 | 1        | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 1        | 0.62%   |
| WDC WD1600BEVS-26VAT0 160GB                 | 1        | 0.62%   |
| WDC WD1500HLFS-01G6U0 150GB                 | 1        | 0.62%   |
| WDC WD10SPZX-24Z10T0 1TB                    | 1        | 0.62%   |
| WDC WD10JPVX-00JC3T0 1TB                    | 1        | 0.62%   |
| WDC WD10EZEX-75ZF5A0 1TB                    | 1        | 0.62%   |
| WDC WD10EZEX-60ZF5A0 1TB                    | 1        | 0.62%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1        | 0.62%   |
| WDC WD10EZEX-60M2NA0 1TB                    | 1        | 0.62%   |
| WDC WD10EZEX-08M2NA0 1TB                    | 1        | 0.62%   |
| WD MediaMax WL3000GSA6472 3TB               | 1        | 0.62%   |
| Unknown MB3000EBKAB 3TB                     | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 30       | 51     | 38.96%  |
| WDC                 | 20       | 25     | 25.97%  |
| Toshiba             | 10       | 12     | 12.99%  |
| Hitachi             | 7        | 9      | 9.09%   |
| HGST                | 3        | 3      | 3.9%    |
| Unknown             | 2        | 3      | 2.6%    |
| Samsung Electronics | 2        | 2      | 2.6%    |
| Maxtor              | 2        | 2      | 2.6%    |
| JMicron Technology  | 1        | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 13       | 19     | 30.23%  |
| A-DATA Technology   | 10       | 11     | 23.26%  |
| WDC                 | 3        | 5      | 6.98%   |
| Patriot             | 3        | 5      | 6.98%   |
| ZOTAC               | 2        | 3      | 4.65%   |
| SanDisk             | 2        | 3      | 4.65%   |
| Samsung Electronics | 2        | 8      | 4.65%   |
| Mushkin             | 2        | 2      | 4.65%   |
| Team                | 1        | 1      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| Gigabyte Technology | 1        | 2      | 2.33%   |
| CT120BX5            | 1        | 1      | 2.33%   |
| Crucial             | 1        | 1      | 2.33%   |
| Biostar             | 1        | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 60       | 108    | 50%     |
| SSD     | 38       | 63     | 31.67%  |
| NVMe    | 19       | 31     | 15.83%  |
| Unknown | 3        | 4      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 80       | 161    | 74.77%  |
| NVMe | 19       | 31     | 17.76%  |
| SAS  | 8        | 14     | 7.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 61       | 105    | 55.96%  |
| 0.51-1.0   | 30       | 38     | 27.52%  |
| 1.01-2.0   | 8        | 9      | 7.34%   |
| 4.01-10.0  | 5        | 8      | 4.59%   |
| 3.01-4.0   | 3        | 7      | 2.75%   |
| 2.01-3.0   | 2        | 4      | 1.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 19       | 20.21%  |
| 101-250        | 18       | 19.15%  |
| 1-20           | 14       | 14.89%  |
| 251-500        | 11       | 11.7%   |
| 1001-2000      | 11       | 11.7%   |
| More than 3000 | 8        | 8.51%   |
| 51-100         | 7        | 7.45%   |
| Unknown        | 3        | 3.19%   |
| 2001-3000      | 2        | 2.13%   |
| 21-50          | 1        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 39       | 39.8%   |
| 21-50          | 17       | 17.35%  |
| 251-500        | 10       | 10.2%   |
| 101-250        | 8        | 8.16%   |
| 501-1000       | 6        | 6.12%   |
| More than 3000 | 5        | 5.1%    |
| 51-100         | 5        | 5.1%    |
| 1001-2000      | 3        | 3.06%   |
| Unknown        | 3        | 3.06%   |
| 2001-3000      | 2        | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Unknown MB3000EBKAB 3TB             | 1        | 1      | 9.09%   |
| Seagate ST9160412AS 160GB           | 1        | 1      | 9.09%   |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2      | 9.09%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 9.09%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD | 1        | 2      | 9.09%   |
| Maxtor STM3160215AS 160GB           | 1        | 1      | 9.09%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1      | 9.09%   |
| Kingston SA400S37240G 240GB SSD     | 1        | 1      | 9.09%   |
| Hitachi HDE721010SLA330 1TB         | 1        | 1      | 9.09%   |
| A-DATA Technology SX8100NP 256GB    | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 4        | 5      | 36.36%  |
| Kingston          | 2        | 2      | 18.18%  |
| Unknown           | 1        | 1      | 9.09%   |
| SanDisk           | 1        | 2      | 9.09%   |
| Maxtor            | 1        | 1      | 9.09%   |
| Hitachi           | 1        | 1      | 9.09%   |
| A-DATA Technology | 1        | 1      | 9.09%   |

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
| HDD  | 6        | 8      | 60%     |
| SSD  | 3        | 4      | 30%     |
| NVMe | 1        | 1      | 10%     |

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
| Detected | 49       | 104    | 50.52%  |
| Works    | 39       | 89     | 40.21%  |
| Malfunc  | 9        | 13     | 9.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 53       | 45.69%  |
| AMD                          | 28       | 24.14%  |
| Realtek Semiconductor        | 6        | 5.17%   |
| ASMedia Technology           | 6        | 5.17%   |
| ADATA Technology             | 5        | 4.31%   |
| Samsung Electronics          | 3        | 2.59%   |
| Nvidia                       | 3        | 2.59%   |
| Kingston Technology Company  | 2        | 1.72%   |
| Toshiba America Info Systems | 1        | 0.86%   |
| Silicon Motion               | 1        | 0.86%   |
| Silicon Image                | 1        | 0.86%   |
| Phison Electronics           | 1        | 0.86%   |
| OCZ Technology Group         | 1        | 0.86%   |
| Micron/Crucial Technology    | 1        | 0.86%   |
| Marvell Technology Group     | 1        | 0.86%   |
| LSI Logic / Symbios Logic    | 1        | 0.86%   |
| JMicron Technology           | 1        | 0.86%   |
| INNOGRIT                     | 1        | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 12       | 9.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 5.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 5.3%    |
| AMD FCH SATA Controller D                                                      | 7        | 5.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6        | 4.55%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 5        | 3.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 3.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 3.79%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 3.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 2.27%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.52%   |
| Nvidia MCP61 IDE                                                               | 2        | 1.52%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 2        | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.52%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.52%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.52%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.76%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.76%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.76%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.76%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 0.76%   |
| Nvidia MCP79 RAID Controller                                                   | 1        | 0.76%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 0.76%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.76%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 0.76%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 1        | 0.76%   |
| JMicron JMB368 IDE controller                                                  | 1        | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.76%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 71       | 63.39%  |
| NVMe | 19       | 16.96%  |
| IDE  | 13       | 11.61%  |
| RAID | 7        | 6.25%   |
| SAS  | 1        | 0.89%   |
| SCSI | 1        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 54       | 64.29%  |
| AMD    | 30       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 7.14%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 4.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 3.57%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 3.57%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.38%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.38%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.38%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.38%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 2.38%   |
| Intel Xeon CPU X5667 @ 3.07GHz              | 1        | 1.19%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.19%   |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 1.19%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz         | 1        | 1.19%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.19%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.19%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.19%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.19%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 1.19%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.19%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.19%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 1.19%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.19%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.19%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.19%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.19%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.19%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.19%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.19%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.19%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.19%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.19%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.19%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.19%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 27.38%  |
| AMD Ryzen 5             | 8        | 9.52%   |
| Intel Core i3           | 7        | 8.33%   |
| Intel Xeon              | 5        | 5.95%   |
| Intel Core i7           | 5        | 5.95%   |
| AMD Ryzen 3             | 5        | 5.95%   |
| AMD FX                  | 5        | 5.95%   |
| Intel Celeron           | 3        | 3.57%   |
| AMD Ryzen 7             | 3        | 3.57%   |
| Other                   | 2        | 2.38%   |
| Intel Pentium           | 2        | 2.38%   |
| AMD Athlon II X2        | 2        | 2.38%   |
| Intel Pentium Dual-Core | 1        | 1.19%   |
| Intel Pentium 4         | 1        | 1.19%   |
| Intel Core i9           | 1        | 1.19%   |
| Intel Core 2 Quad       | 1        | 1.19%   |
| Intel Core 2 Duo        | 1        | 1.19%   |
| Intel Core 2            | 1        | 1.19%   |
| Intel Atom              | 1        | 1.19%   |
| AMD Sempron             | 1        | 1.19%   |
| AMD Ryzen 7 PRO         | 1        | 1.19%   |
| AMD Phenom II X4        | 1        | 1.19%   |
| AMD E2                  | 1        | 1.19%   |
| AMD E1                  | 1        | 1.19%   |
| AMD A8                  | 1        | 1.19%   |
| AMD A4                  | 1        | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 40       | 47.62%  |
| 2      | 16       | 19.05%  |
| 6      | 13       | 15.48%  |
| 8      | 7        | 8.33%   |
| 1      | 5        | 5.95%   |
| 20     | 1        | 1.19%   |
| 10     | 1        | 1.19%   |
| 3      | 1        | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 97.62%  |
| 2      | 2        | 2.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 58.33%  |
| 2      | 35       | 41.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 82       | 97.62%  |
| 32-bit         | 1        | 1.19%   |
| Unknown        | 1        | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 25.27%  |
| 0x306c3    | 9        | 9.89%   |
| 0x906e9    | 5        | 5.49%   |
| 0x306a9    | 5        | 5.49%   |
| 0x08701021 | 4        | 4.4%    |
| 0x506e3    | 3        | 3.3%    |
| 0x08108109 | 3        | 3.3%    |
| 0x906eb    | 2        | 2.2%    |
| 0x306e4    | 2        | 2.2%    |
| 0x10676    | 2        | 2.2%    |
| 0x08101016 | 2        | 2.2%    |
| 0x06000852 | 2        | 2.2%    |
| 0x05000119 | 2        | 2.2%    |
| 0x010000c8 | 2        | 2.2%    |
| 0xf49      | 1        | 1.1%    |
| 0xf29      | 1        | 1.1%    |
| 0x906ec    | 1        | 1.1%    |
| 0x906ea    | 1        | 1.1%    |
| 0x90675    | 1        | 1.1%    |
| 0x90672    | 1        | 1.1%    |
| 0x706a8    | 1        | 1.1%    |
| 0x6f6      | 1        | 1.1%    |
| 0x30678    | 1        | 1.1%    |
| 0x106e5    | 1        | 1.1%    |
| 0x106ca    | 1        | 1.1%    |
| 0x106a5    | 1        | 1.1%    |
| 0x10677    | 1        | 1.1%    |
| 0x0a601201 | 1        | 1.1%    |
| 0x08701011 | 1        | 1.1%    |
| 0x0870100a | 1        | 1.1%    |
| 0x08600109 | 1        | 1.1%    |
| 0x08600106 | 1        | 1.1%    |
| 0x0800820d | 1        | 1.1%    |
| 0x06001119 | 1        | 1.1%    |
| 0x06001116 | 1        | 1.1%    |
| 0x06000822 | 1        | 1.1%    |
| 0x0500010d | 1        | 1.1%    |
| 0x010000c7 | 1        | 1.1%    |
| 0x00000000 | 1        | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 12       | 14.29%  |
| Haswell          | 12       | 14.29%  |
| IvyBridge        | 8        | 9.52%   |
| Zen 2            | 6        | 7.14%   |
| Piledriver       | 6        | 7.14%   |
| Skylake          | 5        | 5.95%   |
| Zen+             | 4        | 4.76%   |
| Zen 3            | 4        | 4.76%   |
| Penryn           | 4        | 4.76%   |
| K10              | 4        | 4.76%   |
| Zen              | 2        | 2.38%   |
| NetBurst         | 2        | 2.38%   |
| Nehalem          | 2        | 2.38%   |
| Bobcat           | 2        | 2.38%   |
| Unknown          | 2        | 2.38%   |
| Westmere         | 1        | 1.19%   |
| Silvermont       | 1        | 1.19%   |
| SandyBridge      | 1        | 1.19%   |
| Goldmont plus    | 1        | 1.19%   |
| Core             | 1        | 1.19%   |
| CometLake        | 1        | 1.19%   |
| Bulldozer        | 1        | 1.19%   |
| Bonnell          | 1        | 1.19%   |
| Alderlake Hybrid | 1        | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 37.63%  |
| Nvidia | 33       | 35.48%  |
| AMD    | 25       | 26.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 10.42%  |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 4.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 4.17%   |
| Intel HD Graphics 630                                                       | 4        | 4.17%   |
| Intel HD Graphics 530                                                       | 4        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.17%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.08%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 2.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.04%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.04%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.04%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 1.04%   |
| Nvidia GT218 [ION]                                                          | 1        | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.04%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.04%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.04%   |
| Nvidia GK106 [GeForce GTX 645 OEM]                                          | 1        | 1.04%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.04%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.04%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.04%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.04%   |
| Nvidia G96C [GeForce GT 120]                                                | 1        | 1.04%   |
| Nvidia G71GL [Quadro FX 3500]                                               | 1        | 1.04%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.04%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.04%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 1.04%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device          | 1        | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 32       | 35.96%  |
| 1 x Nvidia     | 31       | 34.83%  |
| 1 x AMD        | 20       | 22.47%  |
| 2 x AMD        | 3        | 3.37%   |
| AMD + Nvidia   | 2        | 2.25%   |
| Intel + Nvidia | 1        | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 66       | 75.86%  |
| Proprietary | 18       | 20.69%  |
| Unknown     | 3        | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 42.86%  |
| 1.01-2.0   | 16       | 17.58%  |
| 3.01-4.0   | 9        | 9.89%   |
| 0.51-1.0   | 9        | 9.89%   |
| 0.01-0.5   | 8        | 8.79%   |
| 5.01-6.0   | 5        | 5.49%   |
| 7.01-8.0   | 4        | 4.4%    |
| 8.01-16.0  | 1        | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 22       | 22.68%  |
| Hewlett-Packard      | 13       | 13.4%   |
| Goldstar             | 10       | 10.31%  |
| Dell                 | 10       | 10.31%  |
| ViewSonic            | 5        | 5.15%   |
| Samsung Electronics  | 5        | 5.15%   |
| BenQ                 | 5        | 5.15%   |
| Acer                 | 4        | 4.12%   |
| AGO                  | 3        | 3.09%   |
| Sony                 | 2        | 2.06%   |
| Panasonic            | 2        | 2.06%   |
| Lenovo               | 2        | 2.06%   |
| Ancor Communications | 2        | 2.06%   |
| Xerox                | 1        | 1.03%   |
| Unknown (XXX)        | 1        | 1.03%   |
| Royal Information    | 1        | 1.03%   |
| Philips              | 1        | 1.03%   |
| MSI                  | 1        | 1.03%   |
| LTM                  | 1        | 1.03%   |
| ITE                  | 1        | 1.03%   |
| Hitachi              | 1        | 1.03%   |
| Haier                | 1        | 1.03%   |
| Denver               | 1        | 1.03%   |
| ASRock               | 1        | 1.03%   |
| ASR                  | 1        | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5        | 4.72%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3        | 2.83%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 3        | 2.83%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3        | 2.83%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2        | 1.89%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2        | 1.89%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2        | 1.89%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 1.89%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 2        | 1.89%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 2        | 1.89%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 2        | 1.89%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                       | 2        | 1.89%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1        | 0.94%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1        | 0.94%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch        | 1        | 0.94%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1        | 0.94%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1        | 0.94%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 0.94%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 0.94%   |
| Sony TV SNY1B02 1360x768                                             | 1        | 0.94%   |
| Sony TV SNY0902 1920x1080                                            | 1        | 0.94%   |
| Samsung Electronics S24A31x SAM7115 1920x1080 527x296mm 23.8-inch    | 1        | 0.94%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.94%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 1        | 0.94%   |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch      | 1        | 0.94%   |
| Philips LCD Monitor 170B4 1280x1024                                  | 1        | 0.94%   |
| MSI MAG271CQR MSI3FA7 2560x1440 597x336mm 27.0-inch                  | 1        | 0.94%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                    | 1        | 0.94%   |
| Lenovo LEN T27h-20 LEN61EC 2560x1440 597x336mm 27.0-inch             | 1        | 0.94%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch             | 1        | 0.94%   |
| ITE DP2VGA V260 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 0.94%   |
| Hitachi 32E10 HTC0128 1366x768 575x323mm 26.0-inch                   | 1        | 0.94%   |
| Hewlett-Packard V202 HWP330B 1600x900 452x263mm 20.6-inch            | 1        | 0.94%   |
| Hewlett-Packard V193 HWP3178 1366x768 410x230mm 18.5-inch            | 1        | 0.94%   |
| Hewlett-Packard P223a HPN3391 1920x1080 477x268mm 21.5-inch          | 1        | 0.94%   |
| Hewlett-Packard Omni/Pro HWP410E 1366x768 410x230mm 18.5-inch        | 1        | 0.94%   |
| Hewlett-Packard LCD Monitor L1908w 1440x900                          | 1        | 0.94%   |
| Hewlett-Packard LCD Monitor Compaq W185q 3286x1080                   | 1        | 0.94%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 0.94%   |
| Hewlett-Packard L1910 HWP26E6 1280x1024 380x300mm 19.1-inch          | 1        | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 36       | 37.5%   |
| 1366x768 (WXGA)   | 15       | 15.63%  |
| 3840x2160 (4K)    | 7        | 7.29%   |
| 1600x900 (HD+)    | 7        | 7.29%   |
| 1280x1024 (SXGA)  | 7        | 7.29%   |
| 1440x900 (WXGA+)  | 6        | 6.25%   |
| 2560x1440 (QHD)   | 5        | 5.21%   |
| 3286x1080         | 2        | 2.08%   |
| 2944x1080         | 2        | 2.08%   |
| 2560x1080         | 2        | 2.08%   |
| 1280x720 (HD)     | 2        | 2.08%   |
| Unknown           | 2        | 2.08%   |
| 1920x1200 (WUXGA) | 1        | 1.04%   |
| 1360x768          | 1        | 1.04%   |
| 1280x960          | 1        | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 12       | 12.24%  |
| 23      | 11       | 11.22%  |
| 24      | 10       | 10.2%   |
| 21      | 10       | 10.2%   |
| 18      | 10       | 10.2%   |
| Unknown | 9        | 9.18%   |
| 27      | 5        | 5.1%    |
| 17      | 5        | 5.1%    |
| 15      | 4        | 4.08%   |
| 72      | 3        | 3.06%   |
| 12      | 3        | 3.06%   |
| 84      | 2        | 2.04%   |
| 43      | 2        | 2.04%   |
| 34      | 2        | 2.04%   |
| 26      | 2        | 2.04%   |
| 54      | 1        | 1.02%   |
| 49      | 1        | 1.02%   |
| 40      | 1        | 1.02%   |
| 36      | 1        | 1.02%   |
| 32      | 1        | 1.02%   |
| 31      | 1        | 1.02%   |
| 22      | 1        | 1.02%   |
| 20      | 1        | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 31       | 32.29%  |
| 501-600     | 27       | 28.13%  |
| Unknown     | 9        | 9.38%   |
| 301-350     | 8        | 8.33%   |
| 1501-2000   | 5        | 5.21%   |
| 701-800     | 4        | 4.17%   |
| 351-400     | 3        | 3.13%   |
| 201-300     | 3        | 3.13%   |
| 1001-1500   | 2        | 2.08%   |
| 901-1000    | 2        | 2.08%   |
| 801-900     | 1        | 1.04%   |
| 601-700     | 1        | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 65.52%  |
| Unknown | 9        | 10.34%  |
| 16/10   | 7        | 8.05%   |
| 5/4     | 6        | 6.9%    |
| 4/3     | 5        | 5.75%   |
| 21/9    | 2        | 2.3%    |
| 32/9    | 1        | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 25.51%  |
| 151-200        | 16       | 16.33%  |
| 141-150        | 13       | 13.27%  |
| Unknown        | 9        | 9.18%   |
| More than 1000 | 6        | 6.12%   |
| 301-350        | 6        | 6.12%   |
| 251-300        | 6        | 6.12%   |
| 501-1000       | 5        | 5.1%    |
| 351-500        | 4        | 4.08%   |
| 71-80          | 3        | 3.06%   |
| 101-110        | 3        | 3.06%   |
| 131-140        | 1        | 1.02%   |
| 111-120        | 1        | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 54       | 59.34%  |
| 101-120 | 17       | 18.68%  |
| Unknown | 9        | 9.89%   |
| 1-50    | 6        | 6.59%   |
| 161-240 | 4        | 4.4%    |
| 121-160 | 1        | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 66       | 75.86%  |
| 2     | 16       | 18.39%  |
| 0     | 5        | 5.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 59       | 49.58%  |
| Intel                           | 25       | 21.01%  |
| Qualcomm Atheros                | 7        | 5.88%   |
| TP-Link                         | 5        | 4.2%    |
| Broadcom                        | 4        | 3.36%   |
| Ralink                          | 3        | 2.52%   |
| Nvidia                          | 3        | 2.52%   |
| Xiaomi                          | 2        | 1.68%   |
| Ralink Technology               | 2        | 1.68%   |
| Linksys                         | 2        | 1.68%   |
| Huawei Technologies             | 2        | 1.68%   |
| Qualcomm Atheros Communications | 1        | 0.84%   |
| MediaTek                        | 1        | 0.84%   |
| Davicom Semiconductor           | 1        | 0.84%   |
| D-Link                          | 1        | 0.84%   |
| Broadcom Limited                | 1        | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 47       | 36.43%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 3.1%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 4        | 3.1%    |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 1.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 1.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2        | 1.55%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2        | 1.55%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 1.55%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 1.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 2        | 1.55%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.55%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 1.55%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 2        | 1.55%   |
| Intel Centrino Advanced-N 6235                                                                | 2        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2        | 1.55%   |
| Huawei VTR-L09                                                                                | 2        | 1.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 2        | 1.55%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 0.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.78%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 1        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.78%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.78%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 0.78%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 0.78%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1        | 0.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 12       | 31.58%  |
| Intel                           | 7        | 18.42%  |
| TP-Link                         | 5        | 13.16%  |
| Qualcomm Atheros                | 4        | 10.53%  |
| Ralink                          | 3        | 7.89%   |
| Ralink Technology               | 2        | 5.26%   |
| Linksys                         | 2        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 2.63%   |
| MediaTek                        | 1        | 2.63%   |
| D-Link                          | 1        | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 10.26%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 5.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2        | 5.13%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2        | 5.13%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 5.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 5.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 2        | 5.13%   |
| Intel Centrino Advanced-N 6235                                                                | 2        | 5.13%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 2.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 2.56%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                                   | 1        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 2.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.56%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 2.56%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 2.56%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 2.56%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 2.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1        | 2.56%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                | 1        | 2.56%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 2.56%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                                | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 54       | 60.67%  |
| Intel                 | 19       | 21.35%  |
| Broadcom              | 4        | 4.49%   |
| Qualcomm Atheros      | 3        | 3.37%   |
| Nvidia                | 3        | 3.37%   |
| Xiaomi                | 2        | 2.25%   |
| Huawei Technologies   | 2        | 2.25%   |
| Davicom Semiconductor | 1        | 1.12%   |
| Broadcom Limited      | 1        | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 47       | 52.22%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 4.44%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 3.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 2.22%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 2.22%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.22%   |
| Intel Ethernet Controller I225-V                                       | 2        | 2.22%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 2.22%   |
| Huawei VTR-L09                                                         | 2        | 2.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.11%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.11%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.11%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 1.11%   |
| Nvidia MCP79 Ethernet                                                  | 1        | 1.11%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.11%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                     | 1        | 1.11%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.11%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 1.11%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1        | 1.11%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1        | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 1.11%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 1.11%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 1        | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 70.34%  |
| WiFi     | 35       | 29.66%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 71       | 77.17%  |
| WiFi     | 21       | 22.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 65.12%  |
| 2     | 29       | 33.72%  |
| 4     | 1        | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 98.82%  |
| Yes  | 1        | 1.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 10       | 41.67%  |
| Intel                   | 7        | 29.17%  |
| ASUSTek Computer        | 3        | 12.5%   |
| TP-Link                 | 1        | 4.17%   |
| Realtek Semiconductor   | 1        | 4.17%   |
| MediaTek                | 1        | 4.17%   |
| Broadcom                | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 10       | 41.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 2        | 8.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 2        | 8.33%   |
| TP-Link UB500 Adapter                                        | 1        | 4.17%   |
| Realtek Bluetooth Radio                                      | 1        | 4.17%   |
| MediaTek Wireless_Device                                     | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 1        | 4.17%   |
| Intel AX201 Bluetooth                                        | 1        | 4.17%   |
| Intel AX200 Bluetooth                                        | 1        | 4.17%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 4.17%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1        | 4.17%   |
| ASUS Bluetooth Radio                                         | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 52       | 37.68%  |
| AMD                     | 35       | 25.36%  |
| Nvidia                  | 32       | 23.19%  |
| C-Media Electronics     | 4        | 2.9%    |
| Unknown                 | 1        | 0.72%   |
| Soundprese              | 1        | 0.72%   |
| Sony                    | 1        | 0.72%   |
| Realtek Semiconductor   | 1        | 0.72%   |
| Medeli Electronics      | 1        | 0.72%   |
| Logitech                | 1        | 0.72%   |
| Kingston Technology     | 1        | 0.72%   |
| GN Netcom               | 1        | 0.72%   |
| Ensoniq                 | 1        | 0.72%   |
| Creative Labs           | 1        | 0.72%   |
| Corsair                 | 1        | 0.72%   |
| BEHRINGER International | 1        | 0.72%   |
| Astro Gaming            | 1        | 0.72%   |
| Argosy Research         | 1        | 0.72%   |
| A-DATA Technology       | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 7.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 6.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 4.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 4.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 4.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 4.82%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.61%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 3.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.01%   |
| Nvidia High Definition Audio Controller                                    | 4        | 2.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.81%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.81%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.81%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.2%    |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.2%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.2%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.2%    |
| Unknown USB PnP Audio Device                                               | 1        | 0.6%    |
| Soundprese HD-II                                                           | 1        | 0.6%    |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.6%    |
| Realtek Semiconductor USB Condenser Microphone                             | 1        | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.6%    |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.6%    |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 20.63%  |
| Micron Technology   | 9        | 14.29%  |
| SK hynix            | 8        | 12.7%   |
| Samsung Electronics | 6        | 9.52%   |
| A-DATA Technology   | 6        | 9.52%   |
| Unknown             | 4        | 6.35%   |
| Crucial             | 4        | 6.35%   |
| Corsair             | 4        | 6.35%   |
| G.Skill             | 3        | 4.76%   |
| Ramaxel Technology  | 2        | 3.17%   |
| V-Color             | 1        | 1.59%   |
| Patriot             | 1        | 1.59%   |
| Kimtigo             | 1        | 1.59%   |
| Unknown             | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 5        | 6.94%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s    | 3        | 4.17%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 2.78%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 2.78%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s     | 2        | 2.78%   |
| A-DATA RAM Module 16GB DIMM DDR4 2667MT/s                | 2        | 2.78%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2        | 2.78%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 1.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1        | 1.39%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s      | 1        | 1.39%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s              | 1        | 1.39%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 1.39%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 1.39%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 1.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1        | 1.39%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s     | 1        | 1.39%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s         | 1        | 1.39%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.39%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 1.39%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 1        | 1.39%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s      | 1        | 1.39%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.39%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s     | 1        | 1.39%   |
| Ramaxel RAM RMR5030MJ68F9F1600 4GB DIMM DDR3 1600MT/s    | 1        | 1.39%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s    | 1        | 1.39%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s          | 1        | 1.39%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s | 1        | 1.39%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 1        | 1.39%   |
| Micron RAM 16JTF25664AZ-1G4F1 2GB DIMM DDR3 1333MT/s     | 1        | 1.39%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s   | 1        | 1.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 1        | 1.39%   |
| Kingston RAM KHX2666C15/16G 16GB DIMM DDR4 2666MT/s      | 1        | 1.39%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 1.39%   |
| Kingston RAM 99U5624-001.A00G 8GB SODIMM DDR4 2667MT/s   | 1        | 1.39%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.39%   |
| Kingston RAM 99U5471-066.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 1.39%   |
| Kingston RAM 99U5403-067.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 46.94%  |
| DDR3    | 21       | 42.86%  |
| SDRAM   | 2        | 4.08%   |
| DDR5    | 1        | 2.04%   |
| DDR2    | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 43       | 91.49%  |
| SODIMM | 4        | 8.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 33.96%  |
| 4096  | 18       | 33.96%  |
| 16384 | 8        | 15.09%  |
| 2048  | 6        | 11.32%  |
| 32768 | 3        | 5.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 16       | 27.12%  |
| 1333  | 6        | 10.17%  |
| 3600  | 5        | 8.47%   |
| 2667  | 5        | 8.47%   |
| 2933  | 3        | 5.08%   |
| 2400  | 3        | 5.08%   |
| 3200  | 2        | 3.39%   |
| 2133  | 2        | 3.39%   |
| 667   | 2        | 3.39%   |
| 4800  | 1        | 1.69%   |
| 3866  | 1        | 1.69%   |
| 3666  | 1        | 1.69%   |
| 3466  | 1        | 1.69%   |
| 3400  | 1        | 1.69%   |
| 3100  | 1        | 1.69%   |
| 3066  | 1        | 1.69%   |
| 2934  | 1        | 1.69%   |
| 2666  | 1        | 1.69%   |
| 2465  | 1        | 1.69%   |
| 2448  | 1        | 1.69%   |
| 2000  | 1        | 1.69%   |
| 1867  | 1        | 1.69%   |
| 1866  | 1        | 1.69%   |
| 1800  | 1        | 1.69%   |

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


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Seiko Epson L3110 Series | 1        | 16.67%  |
| HP DeskJet 2600 series   | 1        | 16.67%  |
| HP DeskJet 2130 series   | 1        | 16.67%  |
| HP Deskjet 2050 J510     | 1        | 16.67%  |
| Canon G2000 series       | 1        | 16.67%  |
| Canon E400 series        | 1        | 16.67%  |

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
| Z-Star Vimicro USB Camera (Altair)    | 1        | 4.55%   |
| TANDBERG PrecisionHD Camera           | 1        | 4.55%   |
| Philips (or NXP) SPC 1300NC PC Camera | 1        | 4.55%   |
| Microsoft LifeCam Cinema              | 1        | 4.55%   |
| Logitech Webcam Pro 9000              | 1        | 4.55%   |
| Logitech Webcam C310                  | 1        | 4.55%   |
| Logitech HD Pro Webcam C920           | 1        | 4.55%   |
| Jieli USB PHY 2.0                     | 1        | 4.55%   |
| Huawei HiCamera                       | 1        | 4.55%   |
| Chicony HP High Definition 1MP Webcam | 1        | 4.55%   |
| Chicony HP 720p HD Monitor Webcam     | 1        | 4.55%   |
| Aveo USB2.0 UVC PC Camera             | 1        | 4.55%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 4.55%   |

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
| 0     | 68       | 79.07%  |
| 1     | 15       | 17.44%  |
| 3     | 2        | 2.33%   |
| 2     | 1        | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 36.36%  |
| Net/wireless             | 5        | 22.73%  |
| Communication controller | 3        | 13.64%  |
| Chipcard                 | 3        | 13.64%  |
| Storage/raid             | 1        | 4.55%   |
| Sound                    | 1        | 4.55%   |
| Network                  | 1        | 4.55%   |


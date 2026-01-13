Linux in Pakistan - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Pakistan.

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

Total: 200

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | B150M-A/M.2                 | [6921271e2f](https://linux-hardware.org/?probe=6921271e2f) | Dec 03, 2025 |
| Gigabyte      | A520M K V2                  | [5745301eda](https://linux-hardware.org/?probe=5745301eda) | Nov 15, 2025 |
| HP            | 18E7                        | [b850c9fbac](https://linux-hardware.org/?probe=b850c9fbac) | Oct 29, 2025 |
| HP            | 18E7                        | [6715d0eed8](https://linux-hardware.org/?probe=6715d0eed8) | Oct 22, 2025 |
| MSI           | MAG Z490 TOMAHAWK           | [c83957f330](https://linux-hardware.org/?probe=c83957f330) | Sep 21, 2025 |
| MAXSUN        | MS-Challenger B650M         | [c8057dd7b6](https://linux-hardware.org/?probe=c8057dd7b6) | Aug 31, 2025 |
| MAXSUN        | MS-Challenger B650M         | [a7bcc9f3e3](https://linux-hardware.org/?probe=a7bcc9f3e3) | Aug 17, 2025 |
| Gigabyte      | H610M H DDR4                | [736141081e](https://linux-hardware.org/?probe=736141081e) | Jul 18, 2025 |
| Gigabyte      | H610M H DDR4                | [6d9df2c5a6](https://linux-hardware.org/?probe=6d9df2c5a6) | Jul 17, 2025 |
| Dell          | 0YXT71 A03                  | [fcf3f4e1b0](https://linux-hardware.org/?probe=fcf3f4e1b0) | Jun 27, 2025 |
| Gigabyte      | H510M H                     | [02d089cc1a](https://linux-hardware.org/?probe=02d089cc1a) | Jun 22, 2025 |
| Dell          | 0YXT71 A03                  | [dfe6a32547](https://linux-hardware.org/?probe=dfe6a32547) | Jun 16, 2025 |
| Dell          | 0XFWHV A00                  | [a461dc2ba0](https://linux-hardware.org/?probe=a461dc2ba0) | Jun 10, 2025 |
| Biostar       | B550MX/E PRO                | [0c549af090](https://linux-hardware.org/?probe=0c549af090) | Jun 02, 2025 |
| Lenovo        | ThinkCentre M70e 0830F2U    | [2354b5bfc7](https://linux-hardware.org/?probe=2354b5bfc7) | May 30, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [588be234ef](https://linux-hardware.org/?probe=588be234ef) | May 23, 2025 |
| HP            | 0AECh D                     | [42db7ed07e](https://linux-hardware.org/?probe=42db7ed07e) | May 12, 2025 |
| Lenovo        | ThinkCentre M70e 0830F2U    | [ce29f11d32](https://linux-hardware.org/?probe=ce29f11d32) | Apr 15, 2025 |
| Gigabyte      | H110M-HD2-CF                | [842d576c18](https://linux-hardware.org/?probe=842d576c18) | Mar 24, 2025 |
| Gigabyte      | H110M-HD2-CF                | [7ac71066e8](https://linux-hardware.org/?probe=7ac71066e8) | Mar 23, 2025 |
| MSI           | X470 GAMING PLUS            | [7c5d58abb0](https://linux-hardware.org/?probe=7c5d58abb0) | Mar 10, 2025 |
| Dell          | 0YXT71 A03                  | [bf3c5c2c6f](https://linux-hardware.org/?probe=bf3c5c2c6f) | Feb 26, 2025 |
| Dell          | 0YXT71 A03                  | [c08b751c12](https://linux-hardware.org/?probe=c08b751c12) | Feb 21, 2025 |
| Gigabyte      | H110M-HD2-CF                | [a6068edc6b](https://linux-hardware.org/?probe=a6068edc6b) | Feb 12, 2025 |
| Gigabyte      | H110M-HD2-CF                | [6758b373f4](https://linux-hardware.org/?probe=6758b373f4) | Feb 12, 2025 |
| Dell          | 0PU052                      | [6a804585f0](https://linux-hardware.org/?probe=6a804585f0) | Feb 06, 2025 |
| Dell          | 0PU052                      | [a45e9e43dd](https://linux-hardware.org/?probe=a45e9e43dd) | Feb 05, 2025 |
| Dell          | 0F5C5X A00                  | [2afbd78ad0](https://linux-hardware.org/?probe=2afbd78ad0) | Jan 18, 2025 |
| Dell          | 0F5C5X A00                  | [d87244298f](https://linux-hardware.org/?probe=d87244298f) | Jan 16, 2025 |
| GEEKOM        | A5                          | [2cfb2d6d30](https://linux-hardware.org/?probe=2cfb2d6d30) | Jan 07, 2025 |
| GEEKOM        | A5                          | [3193148efc](https://linux-hardware.org/?probe=3193148efc) | Jan 07, 2025 |
| HP            | 18E7                        | [b0312cea7a](https://linux-hardware.org/?probe=b0312cea7a) | Dec 30, 2024 |
| GEEKOM        | A5                          | [2bdc0b3030](https://linux-hardware.org/?probe=2bdc0b3030) | Dec 26, 2024 |
| Dell          | 0WMJ54 A01                  | [00c962b29d](https://linux-hardware.org/?probe=00c962b29d) | Dec 14, 2024 |
| Gigabyte      | H510M H                     | [25f0eaa3ca](https://linux-hardware.org/?probe=25f0eaa3ca) | Oct 27, 2024 |
| HP            | 18E4                        | [121e713fcb](https://linux-hardware.org/?probe=121e713fcb) | Oct 11, 2024 |
| Dell          | 0DR845                      | [0f42ddcf61](https://linux-hardware.org/?probe=0f42ddcf61) | Oct 04, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [4c027e59fb](https://linux-hardware.org/?probe=4c027e59fb) | Sep 29, 2024 |
| HP            | 339A                        | [9300f2dd15](https://linux-hardware.org/?probe=9300f2dd15) | Sep 15, 2024 |
| Dell          | 0DR845                      | [7385610ecd](https://linux-hardware.org/?probe=7385610ecd) | Sep 04, 2024 |
| Dell          | 048DY8 A00                  | [02cdadf60a](https://linux-hardware.org/?probe=02cdadf60a) | Aug 23, 2024 |
| HP            | 3048h                       | [0b0cbac609](https://linux-hardware.org/?probe=0b0cbac609) | Jul 22, 2024 |
| HP            | 3048h                       | [4e0b68d2c5](https://linux-hardware.org/?probe=4e0b68d2c5) | Jul 15, 2024 |
| Dell          | OptiPlex 980                | [1ecb0bfbf0](https://linux-hardware.org/?probe=1ecb0bfbf0) | Jun 20, 2024 |
| HP            | 0AE4h                       | [3eedb438d5](https://linux-hardware.org/?probe=3eedb438d5) | Jun 19, 2024 |
| Gigabyte      | B250M-D2VX-SI-CF            | [5c277491cf](https://linux-hardware.org/?probe=5c277491cf) | Apr 27, 2024 |
| Dell          | 0VRWRC A00                  | [19c02bd31c](https://linux-hardware.org/?probe=19c02bd31c) | Apr 23, 2024 |
| HP            | 18E6                        | [e26531db78](https://linux-hardware.org/?probe=e26531db78) | Mar 01, 2024 |
| Dell          | 06X1TJ A00                  | [f3cb8642e0](https://linux-hardware.org/?probe=f3cb8642e0) | Feb 01, 2024 |
| Lenovo        | Annapurna CRB NOK           | [5b803efc86](https://linux-hardware.org/?probe=5b803efc86) | Jan 26, 2024 |
| MSI           | Z590-A PRO                  | [f6eb92aa92](https://linux-hardware.org/?probe=f6eb92aa92) | Dec 30, 2023 |
| Dell          | 0YXT71 A03                  | [7a857447b4](https://linux-hardware.org/?probe=7a857447b4) | Dec 28, 2023 |
| Dell          | 06X1TJ A00                  | [eac468f369](https://linux-hardware.org/?probe=eac468f369) | Dec 20, 2023 |
| MSI           | Z590-A PRO                  | [4298ef81a3](https://linux-hardware.org/?probe=4298ef81a3) | Dec 04, 2023 |
| HP            | 3646h                       | [1cfad160f4](https://linux-hardware.org/?probe=1cfad160f4) | Nov 12, 2023 |
| HP            | 845A                        | [95fbc211ec](https://linux-hardware.org/?probe=95fbc211ec) | Nov 11, 2023 |
| Gigabyte      | B250M-D3H-CF                | [cb1c24030f](https://linux-hardware.org/?probe=cb1c24030f) | Nov 07, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | [65b9bad459](https://linux-hardware.org/?probe=65b9bad459) | Nov 03, 2023 |
| Gigabyte      | EX58-EXTREME                | [662889cd52](https://linux-hardware.org/?probe=662889cd52) | Oct 12, 2023 |
| MSI           | Z590-A PRO                  | [373685317f](https://linux-hardware.org/?probe=373685317f) | Oct 03, 2023 |
| Lenovo        | MAHOBAY                     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [f597ec9360](https://linux-hardware.org/?probe=f597ec9360) | Sep 23, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | [187d930341](https://linux-hardware.org/?probe=187d930341) | Aug 29, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [4fe996e64f](https://linux-hardware.org/?probe=4fe996e64f) | Aug 29, 2023 |
| Unknown       | IPMSB-H61                   | [c104b6462e](https://linux-hardware.org/?probe=c104b6462e) | Aug 26, 2023 |
| HP            | 18E7                        | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| AAEON         | MF-001 V1.0                 | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Biostar       | H61MGV                      | [4fadeeb5bd](https://linux-hardware.org/?probe=4fadeeb5bd) | Jul 12, 2023 |
| Acer          | Veriton N4620G              | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| MSI           | Z590-A PRO                  | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| MSI           | Z590-A PRO                  | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | [68573d1b85](https://linux-hardware.org/?probe=68573d1b85) | May 13, 2023 |
| Inventec      | Z CLASS A02                 | [44b6a5142e](https://linux-hardware.org/?probe=44b6a5142e) | Apr 25, 2023 |
| Intel         | DQ67OW AAG28716-309         | [e628a47ac6](https://linux-hardware.org/?probe=e628a47ac6) | Apr 01, 2023 |
| Intel         | DQ67OW AAG28716-309         | [3394687910](https://linux-hardware.org/?probe=3394687910) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| HP            | 1850                        | [5ae52efa64](https://linux-hardware.org/?probe=5ae52efa64) | Mar 25, 2023 |
| Inventec      | Z CLASS A02                 | [7b5d4c040b](https://linux-hardware.org/?probe=7b5d4c040b) | Mar 05, 2023 |
| HP            | 339A                        | [07001c3589](https://linux-hardware.org/?probe=07001c3589) | Feb 19, 2023 |
| HP            | 339A                        | [0d7bb8b04a](https://linux-hardware.org/?probe=0d7bb8b04a) | Feb 19, 2023 |
| ASUSTek       | A55BM-PLUS                  | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Unknown       | IPMSB-H61                   | [7e13c996bd](https://linux-hardware.org/?probe=7e13c996bd) | Feb 02, 2023 |
| Dell          | 0KRC95 A00                  | [bf9e573abf](https://linux-hardware.org/?probe=bf9e573abf) | Jan 25, 2023 |
| MSI           | Z590-A PRO                  | [b55d0dfc1e](https://linux-hardware.org/?probe=b55d0dfc1e) | Jan 03, 2023 |
| MSI           | Z590-A PRO                  | [63adf72d53](https://linux-hardware.org/?probe=63adf72d53) | Jan 01, 2023 |
| HP            | 304Ah                       | [6106d55390](https://linux-hardware.org/?probe=6106d55390) | Dec 26, 2022 |
| Gigabyte      | Q87M-D2H                    | [0b6bf86b5e](https://linux-hardware.org/?probe=0b6bf86b5e) | Dec 10, 2022 |
| HP            | 198E                        | [9d22530b3c](https://linux-hardware.org/?probe=9d22530b3c) | Nov 25, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| Gigabyte      | Q87M-D2H                    | [e7c7b6c8a7](https://linux-hardware.org/?probe=e7c7b6c8a7) | Nov 14, 2022 |
| Gigabyte      | Q87M-D2H                    | [8224e059c6](https://linux-hardware.org/?probe=8224e059c6) | Nov 14, 2022 |
| Gigabyte      | Q87M-D2H                    | [543c3778c3](https://linux-hardware.org/?probe=543c3778c3) | Nov 12, 2022 |
| Gigabyte      | Q87M-D2H                    | [f73ba4186b](https://linux-hardware.org/?probe=f73ba4186b) | Nov 11, 2022 |
| Gigabyte      | Q87M-D2H                    | [143dc1e811](https://linux-hardware.org/?probe=143dc1e811) | Nov 05, 2022 |
| ASUSTek       | Q87M-E                      | [79f94ede46](https://linux-hardware.org/?probe=79f94ede46) | Oct 11, 2022 |
| HP            | 18E7                        | [797aa81ce0](https://linux-hardware.org/?probe=797aa81ce0) | Oct 02, 2022 |
| HP            | 18E7                        | [69e4bb94f3](https://linux-hardware.org/?probe=69e4bb94f3) | Oct 02, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| Quanta        | 2ABB 101                    | [3d241d58b9](https://linux-hardware.org/?probe=3d241d58b9) | Jul 13, 2022 |
| Gigabyte      | A520M S2H                   | [52aab7f65b](https://linux-hardware.org/?probe=52aab7f65b) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| Gigabyte      | A520M S2H                   | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| HP            | 339A                        | [a20191b759](https://linux-hardware.org/?probe=a20191b759) | Jun 23, 2022 |
| HP            | 18E7                        | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| ASUSTek       | STRIX B250H GAMING          | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| HP            | 1495                        | [9ec1730693](https://linux-hardware.org/?probe=9ec1730693) | May 11, 2022 |
| Lenovo        | SDK0E50510 WIN              | [07526b3b20](https://linux-hardware.org/?probe=07526b3b20) | May 10, 2022 |
| HP            | 3396                        | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP            | 3396                        | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| HP            | 3396                        | [2c07ec89d4](https://linux-hardware.org/?probe=2c07ec89d4) | Apr 17, 2022 |
| HP            | 87D6 SMVB                   | [57d44d9705](https://linux-hardware.org/?probe=57d44d9705) | Apr 03, 2022 |
| HP            | 87D6 SMVB                   | [e70c6e6d89](https://linux-hardware.org/?probe=e70c6e6d89) | Apr 03, 2022 |
| Dell          | 0HR330                      | [9e351420b6](https://linux-hardware.org/?probe=9e351420b6) | Mar 04, 2022 |
| Gigabyte      | A520M S2H                   | [06db14c491](https://linux-hardware.org/?probe=06db14c491) | Mar 01, 2022 |
| Dell          | 0HR330                      | [7e4c13a9bd](https://linux-hardware.org/?probe=7e4c13a9bd) | Mar 01, 2022 |
| Dell          | 0HR330                      | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 8717                        | [d5d2ee0ab5](https://linux-hardware.org/?probe=d5d2ee0ab5) | Feb 18, 2022 |
| HP            | 8061                        | [f721051d60](https://linux-hardware.org/?probe=f721051d60) | Feb 11, 2022 |
| HP            | 8717                        | [97d99714a1](https://linux-hardware.org/?probe=97d99714a1) | Feb 10, 2022 |
| Dell          | 0DR845                      | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| HP            | 0B3Ch HP P/N                | [2805378159](https://linux-hardware.org/?probe=2805378159) | Dec 10, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | [0784c5596b](https://linux-hardware.org/?probe=0784c5596b) | Dec 04, 2021 |
| Dell          | 0VHRW1 A03                  | [ebfaaee6ef](https://linux-hardware.org/?probe=ebfaaee6ef) | Dec 04, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | [50a026d588](https://linux-hardware.org/?probe=50a026d588) | Dec 02, 2021 |
| Dell          | 0VHRW1 A03                  | [19fd4c2057](https://linux-hardware.org/?probe=19fd4c2057) | Nov 30, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | [7493408721](https://linux-hardware.org/?probe=7493408721) | Nov 29, 2021 |
| Dell          | 0VHRW1 A03                  | [637bba1c58](https://linux-hardware.org/?probe=637bba1c58) | Nov 29, 2021 |
| Dell          | 06FW8P A02                  | [555032936f](https://linux-hardware.org/?probe=555032936f) | Nov 28, 2021 |
| Shuttle       | FS81                        | [ac6138c9d7](https://linux-hardware.org/?probe=ac6138c9d7) | Nov 19, 2021 |
| Shuttle       | FS81                        | [d889090212](https://linux-hardware.org/?probe=d889090212) | Nov 18, 2021 |
| HP            | 0AECh D                     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| Dell          | 06FW8P A02                  | [72f1028535](https://linux-hardware.org/?probe=72f1028535) | Nov 09, 2021 |
| Dell          | 06FW8P A02                  | [e43d36b3cf](https://linux-hardware.org/?probe=e43d36b3cf) | Nov 09, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [98ddca21d9](https://linux-hardware.org/?probe=98ddca21d9) | Nov 06, 2021 |
| HP            | 0AECh D                     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| Dell          | 06FW8P A02                  | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| Dell          | 0XPDFK A01                  | [0e66d5fd62](https://linux-hardware.org/?probe=0e66d5fd62) | Oct 16, 2021 |
| HP            | 0AECh D                     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Dell          | 06FW8P A02                  | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Dell          | 06FW8P A02                  | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| HP            | 0AECh D                     | [202ada3fc3](https://linux-hardware.org/?probe=202ada3fc3) | Sep 23, 2021 |
| HP            | 3047h                       | [356ad972a7](https://linux-hardware.org/?probe=356ad972a7) | Sep 22, 2021 |
| HP            | 1587h                       | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| Unknown       | Unknown                     | [321a93dff9](https://linux-hardware.org/?probe=321a93dff9) | Sep 07, 2021 |
| Shuttle       | FS81                        | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Dell          | 09KPNV A01                  | [7e939d9f5f](https://linux-hardware.org/?probe=7e939d9f5f) | Aug 20, 2021 |
| Lenovo        | MAHOBAY NOK                 | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| Gigabyte      | Z590 UD AC                  | [7e8e35538a](https://linux-hardware.org/?probe=7e8e35538a) | Jul 26, 2021 |
| Lenovo        | MAHOBAY NOK                 | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Gigabyte      | Z590 UD AC                  | [4fc5079d7e](https://linux-hardware.org/?probe=4fc5079d7e) | Jul 20, 2021 |
| Lenovo        | ThinkCentre M70e 0830F2U    | [8dad962f2f](https://linux-hardware.org/?probe=8dad962f2f) | Jul 09, 2021 |
| HP            | 158A                        | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| Dell          | 042P49 A00                  | [2d9b300bd3](https://linux-hardware.org/?probe=2d9b300bd3) | May 13, 2021 |
| Lenovo        | MAHOBAY NOK                 | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| Dell          | 06FW8P A01                  | [08f4c825cc](https://linux-hardware.org/?probe=08f4c825cc) | Apr 25, 2021 |
| Lenovo        | MAHOBAY NOK                 | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| Dell          | 0VHRW1 A03                  | [bc7c3f8c4d](https://linux-hardware.org/?probe=bc7c3f8c4d) | Apr 23, 2021 |
| Lenovo        | ThinkStation D30 4223CC9    | [8d7a62ce1a](https://linux-hardware.org/?probe=8d7a62ce1a) | Apr 20, 2021 |
| Dell          | 06FW8P A02                  | [583acd1f2e](https://linux-hardware.org/?probe=583acd1f2e) | Apr 20, 2021 |
| Dell          | 06FW8P A01                  | [a0b4b692ff](https://linux-hardware.org/?probe=a0b4b692ff) | Apr 20, 2021 |
| Shuttle       | FS81                        | [14e78cfe43](https://linux-hardware.org/?probe=14e78cfe43) | Apr 20, 2021 |
| Dell          | 0GU083 A00                  | [03e87a4ada](https://linux-hardware.org/?probe=03e87a4ada) | Mar 20, 2021 |
| Dell          | 0C27VV A01                  | [2ab353f0c6](https://linux-hardware.org/?probe=2ab353f0c6) | Mar 06, 2021 |
| Lenovo        | MAHOBAY NOK                 | [67ea005277](https://linux-hardware.org/?probe=67ea005277) | Feb 24, 2021 |
| Lenovo        | MAHOBAY 31900003 STD        | [845f5a30c2](https://linux-hardware.org/?probe=845f5a30c2) | Feb 13, 2021 |
| Lenovo        | ThinkCentre M58 7373C51     | [3e79476403](https://linux-hardware.org/?probe=3e79476403) | Jan 27, 2021 |
| HP            | 3047h                       | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| HP            | 3047h                       | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Dell          | 07N90W A01                  | [127c1a4946](https://linux-hardware.org/?probe=127c1a4946) | Oct 29, 2020 |
| HP            | 8433 11                     | [1d000792d8](https://linux-hardware.org/?probe=1d000792d8) | Sep 03, 2020 |
| Dell          | 0D6H9T A01                  | [1f914ddd57](https://linux-hardware.org/?probe=1f914ddd57) | Aug 31, 2020 |
| Dell          | 0HY9JP A02                  | [19795140c8](https://linux-hardware.org/?probe=19795140c8) | Aug 22, 2020 |
| Dell          | 0HY9JP A02                  | [b739a3410a](https://linux-hardware.org/?probe=b739a3410a) | Aug 22, 2020 |
| Dell          | 0PP150 A00                  | [a990cf0ce7](https://linux-hardware.org/?probe=a990cf0ce7) | Aug 21, 2020 |
| HP            | 0B4Ch D                     | [4053256264](https://linux-hardware.org/?probe=4053256264) | Aug 10, 2020 |
| Dell          | 0DR845                      | [e4ff6acb83](https://linux-hardware.org/?probe=e4ff6acb83) | Aug 01, 2020 |
| Dell          | 0DR845                      | [4b9fbd7a8f](https://linux-hardware.org/?probe=4b9fbd7a8f) | Aug 01, 2020 |
| HP            | 1589                        | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| Gigabyte      | B450M S2H                   | [4e6a9e5117](https://linux-hardware.org/?probe=4e6a9e5117) | Jun 12, 2020 |
| Gigabyte      | B250M-D3H-CF                | [f74cf1545a](https://linux-hardware.org/?probe=f74cf1545a) | May 21, 2020 |
| Dell          | 0GU083 A00                  | [a31c9c5f4f](https://linux-hardware.org/?probe=a31c9c5f4f) | May 05, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [e3400fb2b7](https://linux-hardware.org/?probe=e3400fb2b7) | May 04, 2020 |
| Dell          | 0PP150 A00                  | [51f69f1430](https://linux-hardware.org/?probe=51f69f1430) | May 02, 2020 |
| Lenovo        | ThinkCentre M57 6072W2A     | [d42ad893b6](https://linux-hardware.org/?probe=d42ad893b6) | May 01, 2020 |
| Lenovo        | ThinkCentre M57 6072W2A     | [366d3d0483](https://linux-hardware.org/?probe=366d3d0483) | May 01, 2020 |
| Dell          | 0PP150 A00                  | [f224ee60e5](https://linux-hardware.org/?probe=f224ee60e5) | Apr 30, 2020 |
| Dell          | 0XPDFK A01                  | [9434f7214c](https://linux-hardware.org/?probe=9434f7214c) | Mar 16, 2020 |
| Dell          | 0XPDFK A01                  | [4a53b5e634](https://linux-hardware.org/?probe=4a53b5e634) | Mar 11, 2020 |
| Dell          | 054KM3 A01                  | [857f976c7f](https://linux-hardware.org/?probe=857f976c7f) | Jan 29, 2020 |
| HP            | 1497                        | [fe24ec7591](https://linux-hardware.org/?probe=fe24ec7591) | Jan 28, 2020 |
| Dell          | 054KM3 A01                  | [f682ad8814](https://linux-hardware.org/?probe=f682ad8814) | Jan 21, 2020 |
| Acer          | Veriton X6620G v1.0         | [e921d3af77](https://linux-hardware.org/?probe=e921d3af77) | Dec 13, 2019 |
| ASUSTek       | Q87M-E                      | [01f990ea56](https://linux-hardware.org/?probe=01f990ea56) | Oct 19, 2019 |
| HP            | 304Ah                       | [4f72bfd1f5](https://linux-hardware.org/?probe=4f72bfd1f5) | May 13, 2019 |
| Dell          | 054KM3 A01                  | [144815a4e9](https://linux-hardware.org/?probe=144815a4e9) | Jan 15, 2019 |
| Dell          | 054KM3 A01                  | [f83bcddf2e](https://linux-hardware.org/?probe=f83bcddf2e) | Jan 08, 2019 |
| Dell          | 054KM3 A01                  | [404e699144](https://linux-hardware.org/?probe=404e699144) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 22.04        | 15       | 10.95%  |
| Ubuntu 20.04        | 12       | 8.76%   |
| Debian 11           | 6        | 4.38%   |
| Debian 10           | 6        | 4.38%   |
| Arch Rolling        | 5        | 3.65%   |
| Ubuntu 18.04        | 4        | 2.92%   |
| Pop!_OS 22.04       | 4        | 2.92%   |
| OpenMandriva 4.3    | 4        | 2.92%   |
| Zorin 15            | 3        | 2.19%   |
| Ubuntu 24.04        | 3        | 2.19%   |
| Ubuntu 21.04        | 3        | 2.19%   |
| Arch                | 3        | 2.19%   |
| Xero Rolling        | 2        | 1.46%   |
| Ubuntu 22.10        | 2        | 1.46%   |
| Ubuntu 20.10        | 2        | 1.46%   |
| Pop!_OS 20.04       | 2        | 1.46%   |
| OpenMandriva 4.2    | 2        | 1.46%   |
| OpenMandriva 25.06  | 2        | 1.46%   |
| Manjaro             | 2        | 1.46%   |
| Linux Mint 22.1     | 2        | 1.46%   |
| Linux Mint 19.3     | 2        | 1.46%   |
| Fedora 34           | 2        | 1.46%   |
| ArcoLinux Rolling   | 2        | 1.46%   |
| Zorin 17            | 1        | 0.73%   |
| Zorin 16            | 1        | 0.73%   |
| Xubuntu 22.04       | 1        | 0.73%   |
| Void Linux Rolling  | 1        | 0.73%   |
| Ubuntu MATE 18.04   | 1        | 0.73%   |
| Ubuntu Budgie 23.04 | 1        | 0.73%   |
| Ubuntu 23.10        | 1        | 0.73%   |
| SteamOS 3.7.17      | 1        | 0.73%   |
| ROSA 12.2           | 1        | 0.73%   |
| Pop!_OS 21.04       | 1        | 0.73%   |
| Parrot 4.10         | 1        | 0.73%   |
| OpenMandriva 25.90  | 1        | 0.73%   |
| OpenMandriva 24.12  | 1        | 0.73%   |
| OpenMandriva 24.09  | 1        | 0.73%   |
| OpenMandriva 23.01  | 1        | 0.73%   |
| Nitrux 3.9.0        | 1        | 0.73%   |
| Lubuntu 22.04       | 1        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 41       | 31.54%  |
| Linux Mint    | 11       | 8.46%   |
| OpenMandriva  | 10       | 7.69%   |
| Debian        | 10       | 7.69%   |
| Fedora        | 8        | 6.15%   |
| Arch          | 8        | 6.15%   |
| Pop!_OS       | 7        | 5.38%   |
| Zorin         | 5        | 3.85%   |
| Kubuntu       | 3        | 2.31%   |
| Xero          | 2        | 1.54%   |
| Manjaro       | 2        | 1.54%   |
| KDE neon      | 2        | 1.54%   |
| Kali          | 2        | 1.54%   |
| Elementary    | 2        | 1.54%   |
| ArcoLinux     | 2        | 1.54%   |
| Xubuntu       | 1        | 0.77%   |
| Void Linux    | 1        | 0.77%   |
| Ubuntu MATE   | 1        | 0.77%   |
| Ubuntu Budgie | 1        | 0.77%   |
| SteamOS       | 1        | 0.77%   |
| ROSA          | 1        | 0.77%   |
| Parrot        | 1        | 0.77%   |
| Nitrux        | 1        | 0.77%   |
| Lubuntu       | 1        | 0.77%   |
| LMDE          | 1        | 0.77%   |
| Linux Lite    | 1        | 0.77%   |
| Deepin        | 1        | 0.77%   |
| CentOS        | 1        | 0.77%   |
| BlackPanther  | 1        | 0.77%   |
| Alpine        | 1        | 0.77%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.106-1-pve            | 5        | 3.38%   |
| 5.16.7-desktop-1omv4003  | 4        | 2.7%    |
| 6.8.0-41-generic         | 3        | 2.03%   |
| 6.14.2-desktop-3omv2590  | 3        | 2.03%   |
| 5.15.0-53-generic        | 3        | 2.03%   |
| 6.8.0-51-generic         | 2        | 1.35%   |
| 6.5.0-21-generic         | 2        | 1.35%   |
| 6.10.10-arch1-1          | 2        | 1.35%   |
| 5.8.0-44-generic         | 2        | 1.35%   |
| 5.4.0-7642-generic       | 2        | 1.35%   |
| 5.4.0-28-generic         | 2        | 1.35%   |
| 5.13.19-1-pve            | 2        | 1.35%   |
| 5.13.0-40-generic        | 2        | 1.35%   |
| 5.10.14-desktop-1omv4002 | 2        | 1.35%   |
| 5.0.0-32-generic         | 2        | 1.35%   |
| 6.9.9-200.fc40.x86_64    | 1        | 0.68%   |
| 6.9.3-76060903-generic   | 1        | 0.68%   |
| 6.8.0-60-generic         | 1        | 0.68%   |
| 6.8.0-53-generic         | 1        | 0.68%   |
| 6.8.0-49-generic         | 1        | 0.68%   |
| 6.8.0-45-generic         | 1        | 0.68%   |
| 6.8.0-38-generic         | 1        | 0.68%   |
| 6.8.0-35-generic         | 1        | 0.68%   |
| 6.6.71-amd64-desktop-hwe | 1        | 0.68%   |
| 6.6.7-arch1-1            | 1        | 0.68%   |
| 6.6.4-arch1-1            | 1        | 0.68%   |
| 6.6.3-arch1-1            | 1        | 0.68%   |
| 6.6.21_1                 | 1        | 0.68%   |
| 6.5.5-arch1-1            | 1        | 0.68%   |
| 6.5.0-26-generic         | 1        | 0.68%   |
| 6.5.0-15-generic         | 1        | 0.68%   |
| 6.5.0-10-generic         | 1        | 0.68%   |
| 6.4.6-76060406-generic   | 1        | 0.68%   |
| 6.4.12-arch1-1           | 1        | 0.68%   |
| 6.3.2-arch1-1            | 1        | 0.68%   |
| 6.2.14-300.fc38.x86_64   | 1        | 0.68%   |
| 6.2.0-39-generic         | 1        | 0.68%   |
| 6.2.0-36-generic         | 1        | 0.68%   |
| 6.2.0-33-generic         | 1        | 0.68%   |
| 6.2.0-31-generic         | 1        | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 14       | 9.79%   |
| 5.4.0   | 10       | 6.99%   |
| 6.8.0   | 9        | 6.29%   |
| 5.11.0  | 8        | 5.59%   |
| 5.8.0   | 6        | 4.2%    |
| 5.19.0  | 6        | 4.2%    |
| 6.5.0   | 5        | 3.5%    |
| 5.4.106 | 5        | 3.5%    |
| 6.2.0   | 4        | 2.8%    |
| 5.16.7  | 4        | 2.8%    |
| 5.11.22 | 4        | 2.8%    |
| 5.0.0   | 4        | 2.8%    |
| 6.14.2  | 3        | 2.1%    |
| 5.13.0  | 3        | 2.1%    |
| 4.15.0  | 3        | 2.1%    |
| 6.11.0  | 2        | 1.4%    |
| 6.10.10 | 2        | 1.4%    |
| 6.1.1   | 2        | 1.4%    |
| 5.13.19 | 2        | 1.4%    |
| 5.10.14 | 2        | 1.4%    |
| 4.18.0  | 2        | 1.4%    |
| 6.9.9   | 1        | 0.7%    |
| 6.9.3   | 1        | 0.7%    |
| 6.6.71  | 1        | 0.7%    |
| 6.6.7   | 1        | 0.7%    |
| 6.6.4   | 1        | 0.7%    |
| 6.6.3   | 1        | 0.7%    |
| 6.6.21  | 1        | 0.7%    |
| 6.5.5   | 1        | 0.7%    |
| 6.4.6   | 1        | 0.7%    |
| 6.4.12  | 1        | 0.7%    |
| 6.3.2   | 1        | 0.7%    |
| 6.2.14  | 1        | 0.7%    |
| 6.17.1  | 1        | 0.7%    |
| 6.15.6  | 1        | 0.7%    |
| 6.14.9  | 1        | 0.7%    |
| 6.14.0  | 1        | 0.7%    |
| 6.12.6  | 1        | 0.7%    |
| 6.12.11 | 1        | 0.7%    |
| 6.12.10 | 1        | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 17       | 11.97%  |
| 5.15    | 15       | 10.56%  |
| 5.11    | 12       | 8.45%   |
| 6.8     | 9        | 6.34%   |
| 5.8     | 7        | 4.93%   |
| 5.19    | 7        | 4.93%   |
| 5.13    | 7        | 4.93%   |
| 6.5     | 6        | 4.23%   |
| 6.2     | 5        | 3.52%   |
| 6.14    | 5        | 3.52%   |
| 5.16    | 5        | 3.52%   |
| 6.6     | 4        | 2.82%   |
| 6.11    | 4        | 2.82%   |
| 5.10    | 4        | 2.82%   |
| 5.0     | 4        | 2.82%   |
| 6.12    | 3        | 2.11%   |
| 6.10    | 3        | 2.11%   |
| 6.1     | 3        | 2.11%   |
| 4.18    | 3        | 2.11%   |
| 4.15    | 3        | 2.11%   |
| 6.9     | 2        | 1.41%   |
| 6.4     | 2        | 1.41%   |
| 5.7     | 2        | 1.41%   |
| 5.18    | 2        | 1.41%   |
| 3.10    | 2        | 1.41%   |
| 6.3     | 1        | 0.7%    |
| 6.17    | 1        | 0.7%    |
| 6.15    | 1        | 0.7%    |
| 6.0     | 1        | 0.7%    |
| 5.3     | 1        | 0.7%    |
| 4.19    | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 121      | 99.18%  |
| i686   | 1        | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 63       | 46.67%  |
| Unknown       | 16       | 11.85%  |
| KDE5          | 15       | 11.11%  |
| KDE6          | 11       | 8.15%   |
| X-Cinnamon    | 10       | 7.41%   |
| XFCE          | 4        | 2.96%   |
| MATE          | 4        | 2.96%   |
| KDE           | 3        | 2.22%   |
| Pantheon      | 2        | 1.48%   |
| i3            | 2        | 1.48%   |
| LXQt          | 1        | 0.74%   |
| KDE4          | 1        | 0.74%   |
| GNOME Classic | 1        | 0.74%   |
| DDE           | 1        | 0.74%   |
| Budgie        | 1        | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 82       | 64.06%  |
| Wayland | 32       | 25%     |
| Tty     | 7        | 5.47%   |
| Unknown | 7        | 5.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 61       | 46.92%  |
| GDM3    | 30       | 23.08%  |
| SDDM    | 22       | 16.92%  |
| LightDM | 9        | 6.92%   |
| GDM     | 6        | 4.62%   |
| TDM     | 1        | 0.77%   |
| LXDM    | 1        | 0.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 110      | 87.3%   |
| en_GB   | 7        | 5.56%   |
| Unknown | 5        | 3.97%   |
| C       | 3        | 2.38%   |
| en_PK   | 1        | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 84       | 66.14%  |
| EFI  | 43       | 33.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 91       | 67.91%  |
| Btrfs    | 13       | 9.7%    |
| Overlay  | 12       | 8.96%   |
| Tmpfs    | 10       | 7.46%   |
| Zfs      | 6        | 4.48%   |
| Xfs      | 1        | 0.75%   |
| Reiserfs | 1        | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 46.83%  |
| GPT     | 56       | 44.44%  |
| MBR     | 11       | 8.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 83.59%  |
| Yes       | 21       | 16.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 58.46%  |
| Yes       | 54       | 41.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 35       | 28.69%  |
| Dell                | 33       | 27.05%  |
| Gigabyte Technology | 18       | 14.75%  |
| Lenovo              | 10       | 8.2%    |
| ASUSTek Computer    | 8        | 6.56%   |
| MSI                 | 3        | 2.46%   |
| Shuttle             | 2        | 1.64%   |
| Biostar             | 2        | 1.64%   |
| Acer                | 2        | 1.64%   |
| Unknown             | 2        | 1.64%   |
| Quanta              | 1        | 0.82%   |
| MAXSUN              | 1        | 0.82%   |
| Inventec            | 1        | 0.82%   |
| Intel               | 1        | 0.82%   |
| GEEKOM              | 1        | 0.82%   |
| Colorful Technology | 1        | 0.82%   |
| AAEON               | 1        | 0.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell Precision WorkStation T7500           | 4        | 3.28%   |
| HP ProDesk 600 G1 SFF                      | 3        | 2.46%   |
| Dell Precision WorkStation T3500           | 3        | 2.46%   |
| Dell OptiPlex 755                          | 3        | 2.46%   |
| Shuttle DS81D                              | 2        | 1.64%   |
| HP Z800 Workstation                        | 2        | 1.64%   |
| HP Z400 Workstation                        | 2        | 1.64%   |
| HP ProDesk 600 G1 TWR                      | 2        | 1.64%   |
| HP ProDesk 400 G7 Microtower PC            | 2        | 1.64%   |
| HP Compaq Pro 6300 SFF                     | 2        | 1.64%   |
| HP Compaq 8100 Elite SFF PC                | 2        | 1.64%   |
| Gigabyte Z590 UD AC                        | 2        | 1.64%   |
| Gigabyte Q87M-D2H                          | 2        | 1.64%   |
| Gigabyte B250M-D3H                         | 2        | 1.64%   |
| Gigabyte A520M S2H                         | 2        | 1.64%   |
| Dell XPS 630i                              | 2        | 1.64%   |
| Dell Vostro 430                            | 2        | 1.64%   |
| Dell Precision WorkStation 490             | 2        | 1.64%   |
| Dell OptiPlex 7010                         | 2        | 1.64%   |
| Unknown                                    | 2        | 1.64%   |
| Quanta TouchSmart 9300 Elite All-in-One PC | 1        | 0.82%   |
| MSI MS-7D09                                | 1        | 0.82%   |
| MSI MS-7C80                                | 1        | 0.82%   |
| MSI MS-7B79                                | 1        | 0.82%   |
| MAXSUN MS-Challenger B650M                 | 1        | 0.82%   |
| Lenovo ThinkStation D30 4223CC9            | 1        | 0.82%   |
| Lenovo ThinkCentre M93z 10ACS12B00         | 1        | 0.82%   |
| Lenovo ThinkCentre M93p 10AB000KUS         | 1        | 0.82%   |
| Lenovo ThinkCentre M82 27423K1             | 1        | 0.82%   |
| Lenovo ThinkCentre M78 16621A1             | 1        | 0.82%   |
| Lenovo ThinkCentre M70e 0830F2U            | 1        | 0.82%   |
| Lenovo ThinkCentre M58 7373C51             | 1        | 0.82%   |
| Lenovo ThinkCentre M57 6072W2A             | 1        | 0.82%   |
| Lenovo H520 10094                          | 1        | 0.82%   |
| Lenovo 3302F3U                             | 1        | 0.82%   |
| Inventec Z CLASS                           | 1        | 0.82%   |
| Intel DESKTOP 310                          | 1        | 0.82%   |
| HP Z620 Workstation                        | 1        | 0.82%   |
| HP Z420 Workstation                        | 1        | 0.82%   |
| HP Z210 Workstation                        | 1        | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 16       | 13.11%  |
| HP Compaq             | 14       | 11.48%  |
| Dell Precision        | 11       | 9.02%   |
| HP ProDesk            | 9        | 7.38%   |
| Lenovo ThinkCentre    | 7        | 5.74%   |
| Dell Vostro           | 4        | 3.28%   |
| Gigabyte A520M        | 3        | 2.46%   |
| Shuttle DS81D         | 2        | 1.64%   |
| HP Z800               | 2        | 1.64%   |
| HP Z400               | 2        | 1.64%   |
| HP Pavilion           | 2        | 1.64%   |
| HP EliteDesk          | 2        | 1.64%   |
| Gigabyte Z590         | 2        | 1.64%   |
| Gigabyte Q87M-D2H     | 2        | 1.64%   |
| Gigabyte B250M-D3H    | 2        | 1.64%   |
| Dell XPS              | 2        | 1.64%   |
| ASUS TUF              | 2        | 1.64%   |
| Acer Veriton          | 2        | 1.64%   |
| Unknown               | 2        | 1.64%   |
| Quanta TouchSmart     | 1        | 0.82%   |
| MSI MS-7D09           | 1        | 0.82%   |
| MSI MS-7C80           | 1        | 0.82%   |
| MSI MS-7B79           | 1        | 0.82%   |
| MAXSUN MS-Challenger  | 1        | 0.82%   |
| Lenovo ThinkStation   | 1        | 0.82%   |
| Lenovo H520           | 1        | 0.82%   |
| Lenovo 3302F3U        | 1        | 0.82%   |
| Inventec Z            | 1        | 0.82%   |
| Intel DESKTOP         | 1        | 0.82%   |
| HP Z620               | 1        | 0.82%   |
| HP Z420               | 1        | 0.82%   |
| HP Z210               | 1        | 0.82%   |
| HP EliteOne           | 1        | 0.82%   |
| Gigabyte Z170X-Gaming | 1        | 0.82%   |
| Gigabyte H610M        | 1        | 0.82%   |
| Gigabyte H510M        | 1        | 0.82%   |
| Gigabyte H110M-HD2    | 1        | 0.82%   |
| Gigabyte F2A88XM-D3H  | 1        | 0.82%   |
| Gigabyte EX58-EXTREME | 1        | 0.82%   |
| Gigabyte B550         | 1        | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 17       | 13.93%  |
| 2012    | 16       | 13.11%  |
| 2009    | 13       | 10.66%  |
| 2011    | 10       | 8.2%    |
| 2014    | 9        | 7.38%   |
| 2010    | 9        | 7.38%   |
| 2021    | 8        | 6.56%   |
| 2020    | 6        | 4.92%   |
| 2018    | 5        | 4.1%    |
| 2007    | 5        | 4.1%    |
| 2016    | 4        | 3.28%   |
| 2015    | 4        | 3.28%   |
| 2022    | 3        | 2.46%   |
| 2017    | 3        | 2.46%   |
| 2008    | 3        | 2.46%   |
| 2023    | 2        | 1.64%   |
| 2006    | 2        | 1.64%   |
| 2024    | 1        | 0.82%   |
| 2019    | 1        | 0.82%   |
| Unknown | 1        | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 122      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 122      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 29       | 23.58%  |
| 4.01-8.0        | 27       | 21.95%  |
| 8.01-16.0       | 22       | 17.89%  |
| 3.01-4.0        | 18       | 14.63%  |
| 32.01-64.0      | 15       | 12.2%   |
| 64.01-256.0     | 8        | 6.5%    |
| 1.01-2.0        | 2        | 1.63%   |
| More than 256.0 | 1        | 0.81%   |
| 24.01-32.0      | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 46       | 32.86%  |
| 2.01-3.0    | 41       | 29.29%  |
| 4.01-8.0    | 18       | 12.86%  |
| 3.01-4.0    | 18       | 12.86%  |
| 8.01-16.0   | 8        | 5.71%   |
| 16.01-24.0  | 3        | 2.14%   |
| 0.51-1.0    | 3        | 2.14%   |
| 32.01-64.0  | 1        | 0.71%   |
| 64.01-256.0 | 1        | 0.71%   |
| Unknown     | 1        | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 47       | 35.34%  |
| 1      | 46       | 34.59%  |
| 3      | 19       | 14.29%  |
| 4      | 6        | 4.51%   |
| 6      | 5        | 3.76%   |
| 5      | 4        | 3.01%   |
| 13     | 1        | 0.75%   |
| 11     | 1        | 0.75%   |
| 10     | 1        | 0.75%   |
| 9      | 1        | 0.75%   |
| 8      | 1        | 0.75%   |
| 0      | 1        | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 59.02%  |
| Yes       | 50       | 40.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 120      | 98.36%  |
| No        | 2        | 1.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 57.26%  |
| No        | 53       | 42.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 67.97%  |
| Yes       | 41       | 32.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Pakistan | 122      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Karachi        | 35       | 27.56%  |
| Lahore         | 34       | 26.77%  |
| Islamabad      | 19       | 14.96%  |
| Rawalpindi     | 8        | 6.3%    |
| Multan         | 5        | 3.94%   |
| Peshawar       | 3        | 2.36%   |
| Hyderabad      | 3        | 2.36%   |
| Kamoke         | 2        | 1.57%   |
| Faisalabad     | 2        | 1.57%   |
| Tando Allahyar | 1        | 0.79%   |
| Sialkot        | 1        | 0.79%   |
| Sheikhupura    | 1        | 0.79%   |
| Sargodha       | 1        | 0.79%   |
| Sahiwal        | 1        | 0.79%   |
| Quetta         | 1        | 0.79%   |
| Mardan         | 1        | 0.79%   |
| Larkana        | 1        | 0.79%   |
| Kaleke Mandi   | 1        | 0.79%   |
| Jhelum         | 1        | 0.79%   |
| Hazro          | 1        | 0.79%   |
| Hafizabad      | 1        | 0.79%   |
| Gujranwala     | 1        | 0.79%   |
| Burewala       | 1        | 0.79%   |
| Bannu          | 1        | 0.79%   |
| Abbottabad     | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 54       | 99     | 22.04%  |
| WDC                          | 38       | 67     | 15.51%  |
| Samsung Electronics          | 26       | 37     | 10.61%  |
| Hitachi                      | 14       | 21     | 5.71%   |
| Toshiba                      | 11       | 12     | 4.49%   |
| Lexar                        | 9        | 15     | 3.67%   |
| HS-SSD-E100                  | 9        | 14     | 3.67%   |
| LITEONIT                     | 7        | 10     | 2.86%   |
| Hewlett-Packard              | 7        | 18     | 2.86%   |
| LITEON                       | 6        | 9      | 2.45%   |
| Hajaan                       | 6        | 9      | 2.45%   |
| Unknown                      | 3        | 3      | 1.22%   |
| Transcend                    | 3        | 4      | 1.22%   |
| SK hynix                     | 3        | 3      | 1.22%   |
| SanDisk                      | 3        | 5      | 1.22%   |
| Micron Technology            | 3        | 4      | 1.22%   |
| Maxtor                       | 3        | 3      | 1.22%   |
| LaCie                        | 3        | 3      | 1.22%   |
| HGST                         | 3        | 3      | 1.22%   |
| Crucial                      | 3        | 3      | 1.22%   |
| China                        | 3        | 3      | 1.22%   |
| A-DATA Technology            | 3        | 4      | 1.22%   |
| Kingston                     | 2        | 2      | 0.82%   |
| Intel                        | 2        | 2      | 0.82%   |
| Gigabyte Technology          | 2        | 3      | 0.82%   |
| ADATA Technology             | 2        | 2      | 0.82%   |
| ZTE                          | 1        | 1      | 0.41%   |
| XPG                          | 1        | 1      | 0.41%   |
| Team                         | 1        | 1      | 0.41%   |
| TAMMUZ                       | 1        | 1      | 0.41%   |
| Silicon Motion               | 1        | 1      | 0.41%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.41%   |
| Netac                        | 1        | 1      | 0.41%   |
| Micron/Crucial Technology    | 1        | 1      | 0.41%   |
| MAXIO Technology (Hangzhou)  | 1        | 1      | 0.41%   |
| MARSHAL                      | 1        | 1      | 0.41%   |
| KingFast                     | 1        | 2      | 0.41%   |
| IBM-ESXS                     | 1        | 3      | 0.41%   |
| HS-SSD-WAVE(S)               | 1        | 2      | 0.41%   |
| HS-SSD-E                     | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST3000NXCLAR3000 3TB                      | 7        | 2.47%   |
| HP MB2000EBZQC 2TB                                | 6        | 2.12%   |
| Hajaan SSD 256G                                   | 6        | 2.12%   |
| Seagate ST500DM002-1BD142 500GB                   | 5        | 1.77%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD             | 5        | 1.77%   |
| HS-SSD-E100 128G                                  | 5        | 1.77%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 4        | 1.41%   |
| WDC WD5000AAKX-75U6AA0 500GB                      | 3        | 1.06%   |
| Toshiba DT01ACA100 1TB                            | 3        | 1.06%   |
| Seagate ST8000DM004-2CX188 8TB                    | 3        | 1.06%   |
| Seagate ST6000NM0024 6TB                          | 3        | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB                    | 3        | 1.06%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB SSD             | 3        | 1.06%   |
| Lexar 256GB SSD                                   | 3        | 1.06%   |
| LaCie Rugged USB-C 2TB                            | 3        | 1.06%   |
| WDC WD5002ABYS-02B1B0 500GB                       | 2        | 0.71%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 2        | 0.71%   |
| WDC WD3200AAKS-00L9A0 320GB                       | 2        | 0.71%   |
| WDC WD2500AAKS-00F0A0 250GB                       | 2        | 0.71%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 2        | 0.71%   |
| Toshiba MG03SCA300 3TB                            | 2        | 0.71%   |
| SK hynix SC300 M.2 2280 256GB SSD                 | 2        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB                   | 2        | 0.71%   |
| Seagate ST380815AS 80GB                           | 2        | 0.71%   |
| Seagate ST3500414CS 500GB                         | 2        | 0.71%   |
| Seagate ST3250318AS 250GB                         | 2        | 0.71%   |
| Seagate ST2000VM003-1ET164 2TB                    | 2        | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 0.71%   |
| Seagate ST2000DM008-2FR1 2TB                      | 2        | 0.71%   |
| Seagate ST1000DM003-1SB10C 1TB                    | 2        | 0.71%   |
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB                    | 2        | 0.71%   |
| Samsung NVMe SSD Drive 500GB                      | 2        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2        | 0.71%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD              | 2        | 0.71%   |
| Samsung HD161GJ 160GB                             | 2        | 0.71%   |
| Maxtor STM380215AS 80GB                           | 2        | 0.71%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD         | 2        | 0.71%   |
| Lexar SSD NS100 256GB                             | 2        | 0.71%   |
| HS-SSD-E100 SSD 128G                              | 2        | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 54       | 99     | 40.6%   |
| WDC                 | 36       | 62     | 27.07%  |
| Hitachi             | 14       | 21     | 10.53%  |
| Toshiba             | 10       | 11     | 7.52%   |
| Hewlett-Packard     | 7        | 18     | 5.26%   |
| Samsung Electronics | 5        | 8      | 3.76%   |
| Maxtor              | 3        | 3      | 2.26%   |
| HGST                | 3        | 3      | 2.26%   |
| MARSHAL             | 1        | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 16     | 17.11%  |
| LITEONIT            | 7        | 10     | 9.21%   |
| Lexar               | 7        | 11     | 9.21%   |
| LITEON              | 6        | 9      | 7.89%   |
| Hajaan              | 6        | 9      | 7.89%   |
| WDC                 | 4        | 5      | 5.26%   |
| Transcend           | 3        | 4      | 3.95%   |
| SK hynix            | 3        | 3      | 3.95%   |
| SanDisk             | 3        | 5      | 3.95%   |
| Micron Technology   | 3        | 4      | 3.95%   |
| HS-SSD-E100         | 3        | 4      | 3.95%   |
| Crucial             | 3        | 3      | 3.95%   |
| China               | 3        | 3      | 3.95%   |
| A-DATA Technology   | 3        | 4      | 3.95%   |
| Kingston            | 2        | 2      | 2.63%   |
| Intel               | 2        | 2      | 2.63%   |
| Toshiba             | 1        | 1      | 1.32%   |
| TAMMUZ              | 1        | 1      | 1.32%   |
| HS-SSD-WAVE(S)      | 1        | 1      | 1.32%   |
| Gigabyte Technology | 1        | 2      | 1.32%   |
| Colorful            | 1        | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 89       | 226    | 50%     |
| SSD     | 52       | 100    | 29.21%  |
| NVMe    | 19       | 27     | 10.67%  |
| Unknown | 16       | 24     | 8.99%   |
| MMC     | 2        | 2      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 113      | 322    | 77.4%   |
| NVMe | 19       | 27     | 13.01%  |
| SAS  | 12       | 28     | 8.22%   |
| MMC  | 2        | 2      | 1.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 91       | 193    | 57.96%  |
| 0.51-1.0   | 34       | 44     | 21.66%  |
| 1.01-2.0   | 17       | 45     | 10.83%  |
| 2.01-3.0   | 9        | 19     | 5.73%   |
| 4.01-10.0  | 4        | 23     | 2.55%   |
| 3.01-4.0   | 2        | 2      | 1.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 39       | 28.68%  |
| 251-500        | 21       | 15.44%  |
| 501-1000       | 17       | 12.5%   |
| 51-100         | 17       | 12.5%   |
| 1-20           | 10       | 7.35%   |
| 21-50          | 9        | 6.62%   |
| 1001-2000      | 8        | 5.88%   |
| Unknown        | 7        | 5.15%   |
| More than 3000 | 4        | 2.94%   |
| 2001-3000      | 4        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 58       | 42.65%  |
| 21-50          | 20       | 14.71%  |
| 51-100         | 14       | 10.29%  |
| 101-250        | 13       | 9.56%   |
| 251-500        | 11       | 8.09%   |
| Unknown        | 7        | 5.15%   |
| 501-1000       | 6        | 4.41%   |
| 1001-2000      | 3        | 2.21%   |
| 2001-3000      | 2        | 1.47%   |
| More than 3000 | 1        | 0.74%   |
| 0              | 1        | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD2500AAKS-00F0A0 250GB                    | 2        | 2      | 5.88%   |
| Seagate ST2000DM008-2FR1 2TB                   | 2        | 2      | 5.88%   |
| Seagate ST1000DM010-2EP102 1TB                 | 2        | 2      | 5.88%   |
| Hewlett-Packard MB2000EBZQC 2TB                | 2        | 3      | 5.88%   |
| Crucial CT525MX300SSD1 528GB                   | 2        | 2      | 5.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1        | 1      | 2.94%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 1        | 1      | 2.94%   |
| WDC WD5000 500GB                               | 1        | 2      | 2.94%   |
| WDC WD3200AAKS-00L9A0 320GB                    | 1        | 1      | 2.94%   |
| WDC WD2500HHTZ-04N21V0 250GB                   | 1        | 1      | 2.94%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1        | 1      | 2.94%   |
| WDC WD1600AAJS-22L7A0 160GB                    | 1        | 1      | 2.94%   |
| WDC WD10JPVT-60A1YT0 1TB                       | 1        | 1      | 2.94%   |
| Toshiba MQ01ABD050V 500GB                      | 1        | 1      | 2.94%   |
| Toshiba DT01ACA100 1TB                         | 1        | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB                | 1        | 1      | 2.94%   |
| Seagate ST380815AS 80GB                        | 1        | 2      | 2.94%   |
| Seagate ST3500418AS 500GB                      | 1        | 1      | 2.94%   |
| Seagate ST3160215AS 160GB                      | 1        | 1      | 2.94%   |
| Seagate ST2000DM008-2FR102 2TB                 | 1        | 2      | 2.94%   |
| Seagate ST1000DM003-1SB10C 1TB                 | 1        | 1      | 2.94%   |
| Samsung Electronics SP2004C 200GB              | 1        | 1      | 2.94%   |
| Samsung Electronics HD080HJ/ 80GB              | 1        | 1      | 2.94%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD  | 1        | 1      | 2.94%   |
| Micron Technology M500_MTFDDAK960MAV 960GB SSD | 1        | 1      | 2.94%   |
| Intel SSDSA2M080G2GN 80GB                      | 1        | 1      | 2.94%   |
| Hitachi HUA723020ALA640 2TB                    | 1        | 2      | 2.94%   |
| Hitachi HDS721680PLA380 80GB                   | 1        | 1      | 2.94%   |
| Hitachi HDS721050CLA660 500GB                  | 1        | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 11     | 28.13%  |
| Seagate             | 9        | 12     | 28.13%  |
| Hitachi             | 3        | 4      | 9.38%   |
| Toshiba             | 2        | 2      | 6.25%   |
| Samsung Electronics | 2        | 2      | 6.25%   |
| Micron Technology   | 2        | 2      | 6.25%   |
| Hewlett-Packard     | 2        | 3      | 6.25%   |
| Crucial             | 2        | 2      | 6.25%   |
| Intel               | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 33.33%  |
| Seagate             | 9        | 12     | 33.33%  |
| Hitachi             | 3        | 4      | 11.11%  |
| Toshiba             | 2        | 2      | 7.41%   |
| Samsung Electronics | 2        | 2      | 7.41%   |
| Hewlett-Packard     | 2        | 3      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 33     | 79.17%  |
| SSD  | 5        | 6      | 20.83%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD5000AZLX-60K2TA0 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 83       | 198    | 56.08%  |
| Works    | 42       | 141    | 28.38%  |
| Malfunc  | 22       | 39     | 14.86%  |
| Failed   | 1        | 1      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 97       | 62.99%  |
| AMD                          | 21       | 13.64%  |
| Samsung Electronics          | 9        | 5.84%   |
| LSI Logic / Symbios Logic    | 9        | 5.84%   |
| ADATA Technology             | 3        | 1.95%   |
| Shenzhen Longsys Electronics | 2        | 1.3%    |
| Nvidia                       | 2        | 1.3%    |
| ASMedia Technology           | 2        | 1.3%    |
| Silicon Motion               | 1        | 0.65%   |
| Phison Electronics           | 1        | 0.65%   |
| Netac Technology             | 1        | 0.65%   |
| Micron/Crucial Technology    | 1        | 0.65%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.65%   |
| Marvell Technology Group     | 1        | 0.65%   |
| Hosin Global Electronics     | 1        | 0.65%   |
| Broadcom / LSI               | 1        | 0.65%   |
| Adaptec                      | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21       | 10.34%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10       | 4.93%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 9        | 4.43%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9        | 4.43%   |
| Intel SATA Controller [RAID mode]                                              | 8        | 3.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8        | 3.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 3.45%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6        | 2.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 1.97%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4        | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 1.97%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 1.97%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 4        | 1.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 1.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 1.48%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.48%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 1.48%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 1.48%   |
| Intel 82Q35 Express PT IDER Controller                                         | 3        | 1.48%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 3        | 1.48%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 3        | 1.48%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 3        | 1.48%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 3        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 3        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 1.48%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2        | 0.99%   |
| Nvidia MCP51 IDE                                                               | 2        | 0.99%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 2        | 0.99%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                           | 2        | 0.99%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2        | 0.99%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 2        | 0.99%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 2        | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 2        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 2        | 0.99%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                         | 2        | 0.99%   |
| Intel 631xESB/632xESB IDE Controller                                           | 2        | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 96       | 55.49%  |
| IDE  | 28       | 16.18%  |
| NVMe | 19       | 10.98%  |
| RAID | 14       | 8.09%   |
| SCSI | 10       | 5.78%   |
| SAS  | 6        | 3.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 100      | 81.97%  |
| AMD    | 22       | 18.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Xeon CPU X5650 @ 2.67GHz          | 5        | 4.1%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 5        | 4.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 5        | 4.1%    |
| Intel Core i5-4570 CPU @ 3.20GHz        | 4        | 3.28%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 4        | 3.28%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4        | 3.28%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 3        | 2.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3        | 2.46%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 3        | 2.46%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3        | 2.46%   |
| Intel Xeon CPU W3520 @ 2.67GHz          | 2        | 1.64%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 2        | 1.64%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2        | 1.64%   |
| Intel Core i5-4570T CPU @ 2.90GHz       | 2        | 1.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 2        | 1.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 2        | 1.64%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 2        | 1.64%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2        | 1.64%   |
| AMD Ryzen 5 7500F 6-Core Processor      | 2        | 1.64%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2        | 1.64%   |
| Intel Xeon CPU X5660 @ 2.80GHz          | 1        | 0.82%   |
| Intel Xeon CPU X5560 @ 2.80GHz          | 1        | 0.82%   |
| Intel Xeon CPU W3680 @ 3.33GHz          | 1        | 0.82%   |
| Intel Xeon CPU W3565 @ 3.20GHz          | 1        | 0.82%   |
| Intel Xeon CPU E5506 @ 2.13GHz          | 1        | 0.82%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 0.82%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz      | 1        | 0.82%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 1        | 0.82%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1        | 0.82%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1        | 0.82%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz  | 1        | 0.82%   |
| Intel Pentium CPU G870 @ 3.10GHz        | 1        | 0.82%   |
| Intel Pentium CPU G4400 @ 3.30GHz       | 1        | 0.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1        | 0.82%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1        | 0.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 0.82%   |
| Intel Core i7-4785T CPU @ 2.20GHz       | 1        | 0.82%   |
| Intel Core i7-3770S CPU @ 3.10GHz       | 1        | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 0.82%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 38       | 31.15%  |
| Intel Xeon         | 19       | 15.57%  |
| Intel Core i7      | 13       | 10.66%  |
| Intel Core 2 Duo   | 10       | 8.2%    |
| AMD Ryzen 5        | 8        | 6.56%   |
| Intel Core i3      | 7        | 5.74%   |
| AMD Ryzen 7        | 5        | 4.1%    |
| Other              | 3        | 2.46%   |
| Intel Core 2 Quad  | 3        | 2.46%   |
| Intel Pentium      | 2        | 1.64%   |
| Intel Celeron      | 2        | 1.64%   |
| AMD Athlon II X2   | 2        | 1.64%   |
| Intel Pentium Dual | 1        | 0.82%   |
| Intel Core 2       | 1        | 0.82%   |
| Intel Atom         | 1        | 0.82%   |
| AMD Ryzen 9        | 1        | 0.82%   |
| AMD Ryzen 3        | 1        | 0.82%   |
| AMD PRO A8         | 1        | 0.82%   |
| AMD G              | 1        | 0.82%   |
| AMD Athlon X4      | 1        | 0.82%   |
| AMD A8             | 1        | 0.82%   |
| AMD A4             | 1        | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 51       | 41.46%  |
| 2      | 34       | 27.64%  |
| 6      | 17       | 13.82%  |
| 8      | 14       | 11.38%  |
| 12     | 3        | 2.44%   |
| 16     | 2        | 1.63%   |
| 1      | 2        | 1.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 115      | 93.5%   |
| 2      | 8        | 6.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 67       | 54.92%  |
| 2      | 55       | 45.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 121      | 99.18%  |
| Unknown        | 1        | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 65       | 50.39%  |
| 0x206a7    | 8        | 6.2%    |
| 0x306c3    | 7        | 5.43%   |
| 0x1067a    | 7        | 5.43%   |
| 0x306a9    | 6        | 4.65%   |
| 0x206c2    | 6        | 4.65%   |
| 0xa0655    | 3        | 2.33%   |
| 0x6f6      | 3        | 2.33%   |
| 0x206d7    | 3        | 2.33%   |
| 0x106a5    | 3        | 2.33%   |
| 0x506e3    | 2        | 1.55%   |
| 0x08701021 | 2        | 1.55%   |
| 0xa0671    | 1        | 0.78%   |
| 0x6fd      | 1        | 0.78%   |
| 0x6fb      | 1        | 0.78%   |
| 0x406c4    | 1        | 0.78%   |
| 0x20655    | 1        | 0.78%   |
| 0x20652    | 1        | 0.78%   |
| 0x10676    | 1        | 0.78%   |
| 0x0a50000d | 1        | 0.78%   |
| 0x0a50000c | 1        | 0.78%   |
| 0x0a201204 | 1        | 0.78%   |
| 0x0800820d | 1        | 0.78%   |
| 0x0600111f | 1        | 0.78%   |
| 0x05000119 | 1        | 0.78%   |
| 0x010000b6 | 1        | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 21       | 17.21%  |
| SandyBridge | 14       | 11.48%  |
| IvyBridge   | 12       | 9.84%   |
| Westmere    | 11       | 9.02%   |
| Penryn      | 10       | 8.2%    |
| Nehalem     | 7        | 5.74%   |
| Core        | 7        | 5.74%   |
| Skylake     | 6        | 4.92%   |
| Zen 3       | 5        | 4.1%    |
| Zen 2       | 5        | 4.1%    |
| CometLake   | 5        | 4.1%    |
| Unknown     | 5        | 4.1%    |
| KabyLake    | 3        | 2.46%   |
| Zen+        | 2        | 1.64%   |
| Steamroller | 2        | 1.64%   |
| Piledriver  | 2        | 1.64%   |
| K10         | 2        | 1.64%   |
| Zen         | 1        | 0.82%   |
| Silvermont  | 1        | 0.82%   |
| Bobcat      | 1        | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 54       | 41.54%  |
| Nvidia | 41       | 31.54%  |
| AMD    | 35       | 26.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 10.95%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 5.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 5.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 5.11%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 2.19%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 3        | 2.19%   |
| Nvidia GT218 [GeForce 310]                                                  | 2        | 1.46%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.46%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.46%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.46%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.46%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.46%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 2        | 1.46%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.46%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.46%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.46%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.46%   |
| AMD Redwood XT GL [FirePro V4800]                                           | 2        | 1.46%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 2        | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.46%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.73%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.73%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.73%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.73%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.73%   |
| Nvidia GT216 [GeForce 405]                                                  | 1        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.73%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.73%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.73%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.73%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.73%   |
| Nvidia GK104 [GeForce GTX 690]                                              | 1        | 0.73%   |
| Nvidia GF119 [NVS 315]                                                      | 1        | 0.73%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 0.73%   |
| Nvidia GF108M [GeForce GT 425M]                                             | 1        | 0.73%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 48       | 38.4%   |
| 1 x Nvidia     | 35       | 28%     |
| 1 x AMD        | 30       | 24%     |
| Intel + Nvidia | 3        | 2.4%    |
| Other          | 2        | 1.6%    |
| 2 x Nvidia     | 2        | 1.6%    |
| 2 x AMD        | 2        | 1.6%    |
| Intel + AMD    | 2        | 1.6%    |
| AMD + Nvidia   | 1        | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 100      | 76.92%  |
| Proprietary | 19       | 14.62%  |
| Unknown     | 11       | 8.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 83       | 65.35%  |
| 1.01-2.0   | 14       | 11.02%  |
| 0.01-0.5   | 12       | 9.45%   |
| 0.51-1.0   | 6        | 4.72%   |
| 7.01-8.0   | 3        | 2.36%   |
| 3.01-4.0   | 3        | 2.36%   |
| 8.01-16.0  | 3        | 2.36%   |
| 5.01-6.0   | 2        | 1.57%   |
| 2.01-3.0   | 1        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 25       | 27.17%  |
| Dell                | 23       | 25%     |
| Samsung Electronics | 7        | 7.61%   |
| Unknown             | 6        | 6.52%   |
| Acer                | 6        | 6.52%   |
| Lenovo              | 5        | 5.43%   |
| NEC Computers       | 4        | 4.35%   |
| ViewSonic           | 3        | 3.26%   |
| Goldstar            | 3        | 3.26%   |
| MSI                 | 2        | 2.17%   |
| Hitachi             | 2        | 2.17%   |
| Philips             | 1        | 1.09%   |
| LED                 | 1        | 1.09%   |
| HannStar            | 1        | 1.09%   |
| Hannspree           | 1        | 1.09%   |
| DFH                 | 1        | 1.09%   |
| DENON               | 1        | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 3        | 3.09%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch    | 2        | 2.06%   |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch             | 2        | 2.06%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch        | 1        | 1.03%   |
| ViewSonic VG2239 Series VSCC42B 1920x1080 477x268mm 21.5-inch        | 1        | 1.03%   |
| ViewSonic LCD Monitor VA2451 SERIES 1920x1080                        | 1        | 1.03%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                     | 1        | 1.03%   |
| Unknown LCD Monitor ITE DP2VGA V221 1680x1050                        | 1        | 1.03%   |
| Unknown LCD Monitor DellSP2008WFP 1680x1050                          | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM0586 1920x1200 518x324mm 24.1-inch | 1        | 1.03%   |
| Samsung Electronics SMBX2240 SAM0684 1920x1080 477x268mm 21.5-inch   | 1        | 1.03%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 1.03%   |
| Samsung Electronics LCD Monitor S22D390 1920x1080                    | 1        | 1.03%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1        | 1.03%   |
| Philips 150P PHL0814 1024x768 300x230mm 14.9-inch                    | 1        | 1.03%   |
| NEC Computers LCD72VM NEC6659 1280x1024 338x270mm 17.0-inch          | 1        | 1.03%   |
| NEC Computers LCD1770NX NEC6665 1280x1024 338x270mm 17.0-inch        | 1        | 1.03%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch         | 1        | 1.03%   |
| NEC Computers EA234WMi NEC6920 1920x1080 509x286mm 23.0-inch         | 1        | 1.03%   |
| MSI G24C6 MSI3BA0 1920x1080 521x293mm 23.5-inch                      | 1        | 1.03%   |
| MSI G243 MSI8BA4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.03%   |
| Lenovo LEN-M93z-B LEN0093 1920x1080 510x290mm 23.1-inch              | 1        | 1.03%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch             | 1        | 1.03%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 476x268mm 21.5-inch             | 1        | 1.03%   |
| LED TV LED2968 1366x768 575x323mm 26.0-inch                          | 1        | 1.03%   |
| Hitachi PC-DTA15AXGS HTCB88C 1024x768 304x228mm 15.0-inch            | 1        | 1.03%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch              | 1        | 1.03%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch          | 1        | 1.03%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 520x320mm 24.0-inch        | 1        | 1.03%   |
| Hewlett-Packard ZR2240w HWP2952 1920x1080 475x267mm 21.5-inch        | 1        | 1.03%   |
| Hewlett-Packard Z22i HWP308E 1920x1080 477x268mm 21.5-inch           | 1        | 1.03%   |
| Hewlett-Packard TouchSmart HWP4204 1920x1080 510x287mm 23.0-inch     | 1        | 1.03%   |
| Hewlett-Packard P240va HWP3307 1920x1080 527x296mm 23.8-inch         | 1        | 1.03%   |
| Hewlett-Packard M27fw FHD HPN370F 1920x1080 597x336mm 27.0-inch      | 1        | 1.03%   |
| Hewlett-Packard M27fw FHD HPN370E 1920x1080 597x336mm 27.0-inch      | 1        | 1.03%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch        | 1        | 1.03%   |
| Hewlett-Packard LE1901w HWP284E 1440x900 410x256mm 19.0-inch         | 1        | 1.03%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch         | 1        | 1.03%   |
| Hewlett-Packard LE1711 HWP2856 1280x1024 340x270mm 17.1-inch         | 1        | 1.03%   |
| Hewlett-Packard LCD Monitor ZR2740w                                  | 1        | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 45       | 48.91%  |
| 1680x1050 (WSXGA+) | 8        | 8.7%    |
| 1280x1024 (SXGA)   | 8        | 8.7%    |
| 1920x1200 (WUXGA)  | 5        | 5.43%   |
| 2560x1440 (QHD)    | 4        | 4.35%   |
| 3440x1440          | 3        | 3.26%   |
| 2288x1287          | 3        | 3.26%   |
| 3840x2160 (4K)     | 2        | 2.17%   |
| 1600x900 (HD+)     | 2        | 2.17%   |
| 1440x900 (WXGA+)   | 2        | 2.17%   |
| 1366x768 (WXGA)    | 2        | 2.17%   |
| 1024x768 (XGA)     | 2        | 2.17%   |
| Unknown            | 2        | 2.17%   |
| 3640x1920          | 1        | 1.09%   |
| 3520x1080          | 1        | 1.09%   |
| 2560x1600          | 1        | 1.09%   |
| 1280x960           | 1        | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 15       | 16.48%  |
| 24      | 13       | 14.29%  |
| 21      | 13       | 14.29%  |
| Unknown | 9        | 9.89%   |
| 27      | 7        | 7.69%   |
| 19      | 7        | 7.69%   |
| 22      | 5        | 5.49%   |
| 17      | 5        | 5.49%   |
| 142     | 3        | 3.3%    |
| 40      | 2        | 2.2%    |
| 32      | 2        | 2.2%    |
| 18      | 2        | 2.2%    |
| 15      | 2        | 2.2%    |
| 84      | 1        | 1.1%    |
| 72      | 1        | 1.1%    |
| 34      | 1        | 1.1%    |
| 29      | 1        | 1.1%    |
| 26      | 1        | 1.1%    |
| 20      | 1        | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 36       | 39.56%  |
| 401-500        | 24       | 26.37%  |
| Unknown        | 9        | 9.89%   |
| 301-350        | 7        | 7.69%   |
| 351-400        | 4        | 4.4%    |
| More than 2000 | 3        | 3.3%    |
| 701-800        | 3        | 3.3%    |
| 801-900        | 2        | 2.2%    |
| 1501-2000      | 2        | 2.2%    |
| 601-700        | 1        | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 52       | 59.09%  |
| 16/10   | 12       | 13.64%  |
| 5/4     | 9        | 10.23%  |
| Unknown | 9        | 10.23%  |
| 1.00    | 3        | 3.41%   |
| 4/3     | 2        | 2.27%   |
| 21/9    | 1        | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 39       | 42.86%  |
| 151-200        | 11       | 12.09%  |
| Unknown        | 9        | 9.89%   |
| 301-350        | 7        | 7.69%   |
| 141-150        | 7        | 7.69%   |
| More than 1000 | 5        | 5.49%   |
| 251-300        | 5        | 5.49%   |
| 351-500        | 4        | 4.4%    |
| 101-110        | 2        | 2.2%    |
| 501-1000       | 2        | 2.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 59       | 67.05%  |
| 101-120 | 14       | 15.91%  |
| Unknown | 9        | 10.23%  |
| 1-50    | 4        | 4.55%   |
| 121-160 | 2        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 73.23%  |
| 0     | 25       | 19.69%  |
| 2     | 9        | 7.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 67       | 31.9%   |
| Realtek Semiconductor           | 62       | 29.52%  |
| Broadcom                        | 28       | 13.33%  |
| Ralink Technology               | 14       | 6.67%   |
| Qualcomm Atheros Communications | 5        | 2.38%   |
| MediaTek                        | 5        | 2.38%   |
| Samsung Electronics             | 3        | 1.43%   |
| Huawei Technologies             | 3        | 1.43%   |
| D-Link                          | 3        | 1.43%   |
| ZTopInc                         | 2        | 0.95%   |
| TP-Link                         | 2        | 0.95%   |
| Qualcomm Atheros                | 2        | 0.95%   |
| Nvidia                          | 2        | 0.95%   |
| Marvell Technology Group        | 2        | 0.95%   |
| Broadcom Limited                | 2        | 0.95%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.48%   |
| Zoom Telephonics                | 1        | 0.48%   |
| VIA Technologies                | 1        | 0.48%   |
| Sierra Wireless                 | 1        | 0.48%   |
| Ralink                          | 1        | 0.48%   |
| OPPO Electronics                | 1        | 0.48%   |
| ASIX Electronics                | 1        | 0.48%   |
| 3Com                            | 1        | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 35       | 15.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19       | 8.41%   |
| Intel Ethernet Connection I217-LM                                      | 16       | 7.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 10       | 4.42%   |
| Ralink MT7601U Wireless Adapter                                        | 10       | 4.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 9        | 3.98%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 2.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 6        | 2.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 2.21%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 2.21%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5        | 2.21%   |
| Intel Wireless 7260                                                    | 4        | 1.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.77%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4        | 1.77%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4        | 1.77%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 1.33%   |
| MediaTek Infinix HOT 50i                                               | 3        | 1.33%   |
| Intel 82578DM Gigabit Network Connection                               | 3        | 1.33%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.33%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]   | 3        | 1.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3        | 1.33%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller    | 3        | 1.33%   |
| ZTopInc 802.11n NIC                                                    | 2        | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.88%   |
| Nvidia MCP51 Ethernet Controller                                       | 2        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 0.88%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2        | 0.88%   |
| Huawei E353/E3131                                                      | 2        | 0.88%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2        | 0.88%   |
| ZTE WCDMA MSM ZTE Mobile Broadband                                     | 1        | 0.44%   |
| Zoom Telephonics V.92 56K Mini External Modem Model 3095               | 1        | 0.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.44%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 0.44%   |
| TP-Link 802.11n NIC                                                    | 1        | 0.44%   |
| Sierra Wireless MC7710                                                 | 1        | 0.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.44%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.44%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                   | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 27       | 36.49%  |
| Ralink Technology               | 14       | 18.92%  |
| Intel                           | 9        | 12.16%  |
| Broadcom                        | 6        | 8.11%   |
| Qualcomm Atheros Communications | 5        | 6.76%   |
| D-Link                          | 3        | 4.05%   |
| ZTopInc                         | 2        | 2.7%    |
| TP-Link                         | 2        | 2.7%    |
| MediaTek                        | 2        | 2.7%    |
| Sierra Wireless                 | 1        | 1.35%   |
| Ralink                          | 1        | 1.35%   |
| Qualcomm Atheros                | 1        | 1.35%   |
| Marvell Technology Group        | 1        | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 10       | 13.33%  |
| Ralink MT7601U Wireless Adapter                                      | 10       | 13.33%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 5        | 6.67%   |
| Qualcomm Atheros AR9271 802.11n                                      | 5        | 6.67%   |
| Intel Wireless 7260                                                  | 4        | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 4%      |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 3        | 4%      |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 3        | 4%      |
| ZTopInc 802.11n NIC                                                  | 2        | 2.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 2.67%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.33%   |
| TP-Link 802.11n NIC                                                  | 1        | 1.33%   |
| Sierra Wireless MC7710                                               | 1        | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1        | 1.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 1.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 1.33%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                 | 1        | 1.33%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)            | 1        | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 1.33%   |
| Realtek RTL8187 Wireless Adapter                                     | 1        | 1.33%   |
| Realtek 802.11ac NIC                                                 | 1        | 1.33%   |
| Ralink RT5572 Wireless Adapter                                       | 1        | 1.33%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 1.33%   |
| Ralink RT2070 Wireless Adapter                                       | 1        | 1.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                            | 1        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1        | 1.33%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1        | 1.33%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 1        | 1.33%   |
| Marvell Group 88W8361 [TopDog] 802.11n Wireless                      | 1        | 1.33%   |
| Intel Wireless 3160                                                  | 1        | 1.33%   |
| Intel Centrino Advanced-N 6235                                       | 1        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1        | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 1        | 1.33%   |
| Broadcom BCM43227 802.11b/g/n                                        | 1        | 1.33%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1        | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 61       | 42.36%  |
| Realtek Semiconductor    | 42       | 29.17%  |
| Broadcom                 | 22       | 15.28%  |
| Samsung Electronics      | 3        | 2.08%   |
| MediaTek                 | 3        | 2.08%   |
| Huawei Technologies      | 3        | 2.08%   |
| Nvidia                   | 2        | 1.39%   |
| Broadcom Limited         | 2        | 1.39%   |
| VIA Technologies         | 1        | 0.69%   |
| Qualcomm Atheros         | 1        | 0.69%   |
| OPPO Electronics         | 1        | 0.69%   |
| Marvell Technology Group | 1        | 0.69%   |
| ASIX Electronics         | 1        | 0.69%   |
| 3Com                     | 1        | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 35       | 23.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19       | 12.75%  |
| Intel Ethernet Connection I217-LM                                      | 16       | 10.74%  |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 9        | 6.04%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 4.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 6        | 4.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5        | 3.36%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 2.68%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4        | 2.68%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4        | 2.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 2.01%   |
| MediaTek Infinix HOT 50i                                               | 3        | 2.01%   |
| Intel 82578DM Gigabit Network Connection                               | 3        | 2.01%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 2.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3        | 2.01%   |
| Nvidia MCP51 Ethernet Controller                                       | 2        | 1.34%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2        | 1.34%   |
| Huawei E353/E3131                                                      | 2        | 1.34%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2        | 1.34%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.67%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.67%   |
| OPPO Ace 3V                                                            | 1        | 0.67%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1        | 0.67%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.67%   |
| Intel Ethernet Controller I225-V                                       | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.67%   |
| Intel 82575GB Gigabit Network Connection                               | 1        | 0.67%   |
| Huawei Ideos (tethering mode)                                          | 1        | 0.67%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 0.67%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                            | 1        | 0.67%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 0.67%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1        | 0.67%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express        | 1        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 0.67%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 62.5%   |
| WiFi     | 70       | 36.46%  |
| Modem    | 2        | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 66.09%  |
| WiFi     | 39       | 33.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 79       | 64.23%  |
| 2     | 35       | 28.46%  |
| 3     | 5        | 4.07%   |
| 4     | 4        | 3.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 112      | 89.6%   |
| Yes  | 13       | 10.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 20       | 45.45%  |
| Intel                   | 9        | 20.45%  |
| Realtek Semiconductor   | 8        | 18.18%  |
| Broadcom                | 3        | 6.82%   |
| IMC Networks            | 2        | 4.55%   |
| Realtek                 | 1        | 2.27%   |
| AboCom Systems          | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 45.45%  |
| Realtek Bluetooth Radio                             | 7        | 15.91%  |
| Intel Bluetooth wireless interface                  | 5        | 11.36%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 6.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.27%   |
| Realtek Bluetooth Radio                             | 1        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.27%   |
| IMC Networks Wireless_Device                        | 1        | 2.27%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.27%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 2.27%   |
| Broadcom HP Bluethunder                             | 1        | 2.27%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 2.27%   |
| AboCom Systems AboCom Bluetooth Device              | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 95       | 50%     |
| Nvidia                 | 40       | 21.05%  |
| AMD                    | 38       | 20%     |
| Generalplus Technology | 6        | 3.16%   |
| C-Media Electronics    | 4        | 2.11%   |
| Texas Instruments      | 1        | 0.53%   |
| Synaptics              | 1        | 0.53%   |
| JMTek                  | 1        | 0.53%   |
| Hewlett-Packard        | 1        | 0.53%   |
| FIFINE 683 Microphone  | 1        | 0.53%   |
| Dell                   | 1        | 0.53%   |
| Creative Labs          | 1        | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 8.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17       | 7.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 12       | 5.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 4.87%   |
| Nvidia High Definition Audio Controller                                    | 9        | 3.98%   |
| AMD Ryzen HD Audio Controller                                              | 7        | 3.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 3.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 3.1%    |
| Generalplus Technology USB Audio Device                                    | 6        | 2.65%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 2.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 5        | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 2.21%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.77%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.77%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.77%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 4        | 1.77%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.33%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.33%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 1.33%   |
| Nvidia MCP51 High Definition Audio                                         | 2        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.88%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2        | 0.88%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.88%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 0.88%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 0.88%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 21       | 25.61%  |
| Samsung Electronics | 21       | 25.61%  |
| Kingston            | 8        | 9.76%   |
| Micron Technology   | 7        | 8.54%   |
| Unknown             | 3        | 3.66%   |
| Ramaxel Technology  | 3        | 3.66%   |
| A-DATA Technology   | 3        | 3.66%   |
| Unknown (2C0B)      | 2        | 2.44%   |
| Team                | 2        | 2.44%   |
| Elpida              | 2        | 2.44%   |
| Wodposit            | 1        | 1.22%   |
| Transcend           | 1        | 1.22%   |
| Toshiba-0098        | 1        | 1.22%   |
| S                   | 1        | 1.22%   |
| Lexar               | 1        | 1.22%   |
| H                   | 1        | 1.22%   |
| G.Skill             | 1        | 1.22%   |
| Crucial             | 1        | 1.22%   |
| Corsair             | 1        | 1.22%   |
| Unknown             | 1        | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s         | 4        | 3.96%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s       | 4        | 3.96%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s         | 3        | 2.97%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s            | 2        | 1.98%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 1.98%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s         | 2        | 1.98%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s        | 2        | 1.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s       | 2        | 1.98%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 2        | 1.98%   |
| Wodposit RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s     | 1        | 0.99%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1        | 0.99%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s                   | 1        | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 0.99%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                   | 1        | 0.99%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s          | 1        | 0.99%   |
| Toshiba-0098 RAM 9965516-069.A00LF 8192MB DIMM DDR3 1067MT/s | 1        | 0.99%   |
| Toshiba-0098 RAM 9965516-057.A00LF 8192MB DIMM DDR3 1067MT/s | 1        | 0.99%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 1        | 0.99%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 1        | 0.99%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                   | 1        | 0.99%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 0.99%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s                | 1        | 0.99%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1067MT/s        | 1        | 0.99%   |
| SK hynix RAM HMT42GR7AFR4A 16GB DIMM DDR3 1600MT/s           | 1        | 0.99%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM SDRAM 4915MT/s        | 1        | 0.99%   |
| SK hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| SK hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s        | 1        | 0.99%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 0.99%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1        | 0.99%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 1        | 0.99%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1        | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 1        | 0.99%   |
| Samsung RAM M393B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s         | 1        | 0.99%   |
| Samsung RAM M393B2G70QH0-YH9 16384MB DIMM DDR3 1333MT/s      | 1        | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 35       | 62.5%   |
| DDR4  | 13       | 23.21%  |
| SDRAM | 5        | 8.93%   |
| DDR5  | 2        | 3.57%   |
| DDR2  | 1        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 49       | 90.74%  |
| SODIMM | 5        | 9.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 19       | 30.65%  |
| 16384 | 14       | 22.58%  |
| 8192  | 13       | 20.97%  |
| 2048  | 12       | 19.35%  |
| 32768 | 4        | 6.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 26       | 38.24%  |
| 1333  | 10       | 14.71%  |
| 2667  | 6        | 8.82%   |
| 3200  | 3        | 4.41%   |
| 2133  | 3        | 4.41%   |
| 1866  | 3        | 4.41%   |
| 6000  | 2        | 2.94%   |
| 4915  | 1        | 1.47%   |
| 4199  | 1        | 1.47%   |
| 3800  | 1        | 1.47%   |
| 3733  | 1        | 1.47%   |
| 3600  | 1        | 1.47%   |
| 3000  | 1        | 1.47%   |
| 2933  | 1        | 1.47%   |
| 2666  | 1        | 1.47%   |
| 2200  | 1        | 1.47%   |
| 2000  | 1        | 1.47%   |
| 1867  | 1        | 1.47%   |
| 1648  | 1        | 1.47%   |
| 1067  | 1        | 1.47%   |
| 1066  | 1        | 1.47%   |
| 800   | 1        | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 66.67%  |
| STMicroelectronics | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| STMicroelectronics YICHIP3121 Virtual ComPort in FS Mode | 1        | 33.33%  |
| HP LaserJet 1300                                         | 1        | 33.33%  |
| HP DeskJet F2492 All-in-One                              | 1        | 33.33%  |

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
| Z-Star Microelectronics | 2        | 15.38%  |
| Sunplus Technology      | 1        | 7.69%   |
| Samsung Electronics     | 1        | 7.69%   |
| Realtek Semiconductor   | 1        | 7.69%   |
| OmniVision Technologies | 1        | 7.69%   |
| MacroSilicon            | 1        | 7.69%   |
| Logitech                | 1        | 7.69%   |
| Generalplus Technology  | 1        | 7.69%   |
| Bison Electronics       | 1        | 7.69%   |
| Asuscom Network         | 1        | 7.69%   |
| Arkmicro Technologies   | 1        | 7.69%   |
| Apple                   | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera              | 2        | 15.38%  |
| Sunplus USB Web-CAM                     | 1        | 7.69%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 7.69%   |
| Realtek HP 2.0MP High Definition Webcam | 1        | 7.69%   |
| OmniVision Monitor Integrated Webcam    | 1        | 7.69%   |
| MacroSilicon USB Video                  | 1        | 7.69%   |
| Logitech C922 Pro Stream Webcam         | 1        | 7.69%   |
| Generalplus GENERAL WEBCAM              | 1        | 7.69%   |
| Bison Integrated Camera                 | 1        | 7.69%   |
| Asuscom Network HD 1080P PC-Camera      | 1        | 7.69%   |
| Arkmicro USB2.0 PC CAMERA               | 1        | 7.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1        | 7.69%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 96       | 75%     |
| 1     | 23       | 17.97%  |
| 2     | 5        | 3.91%   |
| 3     | 2        | 1.56%   |
| 7     | 1        | 0.78%   |
| 4     | 1        | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 15       | 34.09%  |
| Graphics card            | 14       | 31.82%  |
| Sound                    | 7        | 15.91%  |
| Communication controller | 4        | 9.09%   |
| Net/ethernet             | 2        | 4.55%   |
| Storage/ata              | 1        | 2.27%   |
| Network                  | 1        | 2.27%   |


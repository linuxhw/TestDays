Linux in Ecuador - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

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

Total: 123

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | H110M-D                     | [7f2b907eb8](https://linux-hardware.org/?probe=7f2b907eb8) | Jan 25, 2024 |
| Gigabyte      | H110M-H-CF                  | [186230d9c6](https://linux-hardware.org/?probe=186230d9c6) | Jan 08, 2024 |
| ASUSTek       | Rampage IV GENE             | [f8466df8c5](https://linux-hardware.org/?probe=f8466df8c5) | Dec 26, 2023 |
| ASRock        | Z690M-ITX/ax                | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Gigabyte      | H270M-D3H-CF                | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | [5df6fee2f9](https://linux-hardware.org/?probe=5df6fee2f9) | Aug 09, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [d80699b846](https://linux-hardware.org/?probe=d80699b846) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Biostar       | H61MGV3                     | [109f8064f6](https://linux-hardware.org/?probe=109f8064f6) | Jun 21, 2023 |
| Intel         | DG35EC AAE29266-209         | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | [3e5a0aac78](https://linux-hardware.org/?probe=3e5a0aac78) | Jun 19, 2023 |
| ASRock        | Z690M-ITX/ax                | [1f232288d7](https://linux-hardware.org/?probe=1f232288d7) | May 07, 2023 |
| ASRock        | Z690M-ITX/ax                | [76674fb178](https://linux-hardware.org/?probe=76674fb178) | Apr 26, 2023 |
| Gigabyte      | H97-Gaming 3                | [d7d0bcde76](https://linux-hardware.org/?probe=d7d0bcde76) | Apr 15, 2023 |
| Biostar       | H81MHV3L                    | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| Dell          | 014GRG A01                  | [2e7b556001](https://linux-hardware.org/?probe=2e7b556001) | Mar 05, 2023 |
| Intel         | DB75EN AAG39650-302         | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| Intel         | DG41RQ AAE54511-205         | [0cf17a3787](https://linux-hardware.org/?probe=0cf17a3787) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2P                   | [93adad7445](https://linux-hardware.org/?probe=93adad7445) | Dec 30, 2022 |
| Dell          | 00V62H A01                  | [296edfbde5](https://linux-hardware.org/?probe=296edfbde5) | Dec 22, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| Gigabyte      | H410M H                     | [71a25274d7](https://linux-hardware.org/?probe=71a25274d7) | Oct 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [ea7b836323](https://linux-hardware.org/?probe=ea7b836323) | Oct 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| ASUSTek       | PRIME A520M-K               | [6b528465e2](https://linux-hardware.org/?probe=6b528465e2) | Sep 20, 2022 |
| HP            | 8768 A                      | [dd63bfb225](https://linux-hardware.org/?probe=dd63bfb225) | Sep 16, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Biostar       | H61MGV3                     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | H81M-A                      | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Intel         | DH61BF AAG81311-101         | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Gigabyte      | X58A-UD3R                   | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Gigabyte      | H97-Gaming 3                | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| Biostar       | G41D3C                      | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| TPV-INVENT... | 2AF2 A01                    | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Biostar       | G31-M7 TE                   | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| Intel         | H81                         | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Biostar       | H61MGV3                     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| Biostar       | A68N-2100                   | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Intel         | DG41RQ AAE54511-205         | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| ASUSTek       | H81M-A                      | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Gigabyte      | H310M H x.x                 | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Gigabyte      | H310M H x.x                 | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASRock        | B450 Gaming K4              | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Foxconn       | H61MXL-K                    | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Gigabyte      | H410M H V2                  | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Gigabyte      | H97M-DS3P                   | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | PRIME A520M-K               | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Biostar       | A68N-2100                   | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Pegatron      | 2ACC                        | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| ASUSTek       | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| ASRock        | B550M-HDV                   | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Gigabyte      | H81M-H                      | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Intel         | DB75EN AAG39650-302         | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| ASUSTek       | PRIME A520M-K               | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Shuttle       | SFM27 V20                   | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Biostar       | G31-M7 TE                   | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Intel         | DG33BU AAD79951-407         | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Intel         | DP55KG AAE47218-404         | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| ASUSTek       | PRIME A320M-A               | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| MSI           | B75A-G43                    | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| ECS           | H61H2-MV                    | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 1497                        | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Biostar       | A68N-2100                   | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| Gigabyte      | H81M-H                      | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| HP            | ProLiant MicroServer        | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Biostar       | A68N-2100                   | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| ASUSTek       | H81M-K                      | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Biostar       | G31-M7 TE                   | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| ASRock        | H61M-VS                     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| Biostar       | H81MLV3                     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Intel         | DH61WW AAG23116-203         | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | 18E7                        | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| ASUSTek       | PRIME A320M-A               | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Dell          | 0CRH6C A02                  | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| Cartimex      | H61H2-MV                    | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 15       | 17.24%  |
| Ubuntu 18.04       | 10       | 11.49%  |
| Ubuntu 22.04       | 6        | 6.9%    |
| OpenMandriva 4.3   | 4        | 4.6%    |
| OpenMandriva 4.2   | 3        | 3.45%   |
| Debian 11          | 3        | 3.45%   |
| CentOS 7           | 3        | 3.45%   |
| Zorin 16           | 2        | 2.3%    |
| Linux Mint 21.1    | 2        | 2.3%    |
| Linux Mint 19.1    | 2        | 2.3%    |
| Fedora 36          | 2        | 2.3%    |
| Fedora 34          | 2        | 2.3%    |
| Xubuntu 18.04      | 1        | 1.15%   |
| Ubuntu 22.10       | 1        | 1.15%   |
| Ubuntu 21.10       | 1        | 1.15%   |
| Ubuntu 16.04       | 1        | 1.15%   |
| Pop!_OS 21.04      | 1        | 1.15%   |
| Pop!_OS 20.04      | 1        | 1.15%   |
| Peppermint 10      | 1        | 1.15%   |
| openSUSE Leap-15.2 | 1        | 1.15%   |
| OpenMandriva 23.90 | 1        | 1.15%   |
| OpenMandriva 23.03 | 1        | 1.15%   |
| Nobara 36          | 1        | 1.15%   |
| Manjaro 21.3.7     | 1        | 1.15%   |
| Manjaro 21.2.5     | 1        | 1.15%   |
| Manjaro            | 1        | 1.15%   |
| Lubuntu 23.10      | 1        | 1.15%   |
| Lubuntu 16.04      | 1        | 1.15%   |
| LMDE 6             | 1        | 1.15%   |
| LMDE 4             | 1        | 1.15%   |
| Linux Mint 21      | 1        | 1.15%   |
| Linux Mint 20.3    | 1        | 1.15%   |
| Linux Mint 20.1    | 1        | 1.15%   |
| Kubuntu 22.04      | 1        | 1.15%   |
| KDE neon 22.04     | 1        | 1.15%   |
| Kali 2022.2        | 1        | 1.15%   |
| Fedora 39          | 1        | 1.15%   |
| Fedora 37          | 1        | 1.15%   |
| Fedora 35          | 1        | 1.15%   |
| Elementary 5.1.7   | 1        | 1.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 33       | 39.29%  |
| OpenMandriva | 7        | 8.33%   |
| Linux Mint   | 7        | 8.33%   |
| Fedora       | 7        | 8.33%   |
| Debian       | 5        | 5.95%   |
| Manjaro      | 3        | 3.57%   |
| CentOS       | 3        | 3.57%   |
| Zorin        | 2        | 2.38%   |
| Pop!_OS      | 2        | 2.38%   |
| Lubuntu      | 2        | 2.38%   |
| LMDE         | 2        | 2.38%   |
| Arch         | 2        | 2.38%   |
| Xubuntu      | 1        | 1.19%   |
| Peppermint   | 1        | 1.19%   |
| openSUSE     | 1        | 1.19%   |
| Nobara       | 1        | 1.19%   |
| Kubuntu      | 1        | 1.19%   |
| KDE neon     | 1        | 1.19%   |
| Kali         | 1        | 1.19%   |
| Elementary   | 1        | 1.19%   |
| Clear Linux  | 1        | 1.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003      | 4        | 4.21%   |
| 5.10.14-desktop-1omv4002     | 3        | 3.16%   |
| 5.8.0-50-generic             | 2        | 2.11%   |
| 5.4.0-73-generic             | 2        | 2.11%   |
| 5.4.0-54-generic             | 2        | 2.11%   |
| 5.4.0-29-generic             | 2        | 2.11%   |
| 5.15.0-56-generic            | 2        | 2.11%   |
| 4.15.0-20-generic            | 2        | 2.11%   |
| 3.10.0-1062.el7.x86_64       | 2        | 2.11%   |
| 6.6.8-arch1-1                | 1        | 1.05%   |
| 6.6.12-201.fsync.fc39.x86_64 | 1        | 1.05%   |
| 6.5.0-14-generic             | 1        | 1.05%   |
| 6.2.6-desktop-1omv2390       | 1        | 1.05%   |
| 6.2.1-desktop-1omv2390       | 1        | 1.05%   |
| 6.1.0-9-amd64                | 1        | 1.05%   |
| 6.1.0-13-amd64               | 1        | 1.05%   |
| 6.0.7-301.fc37.x86_64        | 1        | 1.05%   |
| 5.8.0-63-generic             | 1        | 1.05%   |
| 5.8.0-41-generic             | 1        | 1.05%   |
| 5.8.0-40-generic             | 1        | 1.05%   |
| 5.7.0-0.bpo.2-amd64          | 1        | 1.05%   |
| 5.4.0-91-generic             | 1        | 1.05%   |
| 5.4.0-81-generic             | 1        | 1.05%   |
| 5.4.0-7634-generic           | 1        | 1.05%   |
| 5.4.0-45-generic             | 1        | 1.05%   |
| 5.4.0-42-generic             | 1        | 1.05%   |
| 5.4.0-37-generic             | 1        | 1.05%   |
| 5.4.0-126-generic            | 1        | 1.05%   |
| 5.3.18-lp152.87-default      | 1        | 1.05%   |
| 5.3.0-46-generic             | 1        | 1.05%   |
| 5.19.9-201.fsync.fc36.x86_64 | 1        | 1.05%   |
| 5.19.0-46-generic            | 1        | 1.05%   |
| 5.19.0-45-generic            | 1        | 1.05%   |
| 5.19.0-35-generic            | 1        | 1.05%   |
| 5.18.5-200.fc36.x86_64       | 1        | 1.05%   |
| 5.17.9-602.inttf.fc36.x86_64 | 1        | 1.05%   |
| 5.17.5-76051705-generic      | 1        | 1.05%   |
| 5.17.4-200.fc35.x86_64       | 1        | 1.05%   |
| 5.17.0-kali3-amd64           | 1        | 1.05%   |
| 5.16.7-1122.native           | 1        | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 12       | 13.64%  |
| 5.15.0  | 9        | 10.23%  |
| 4.15.0  | 9        | 10.23%  |
| 5.8.0   | 5        | 5.68%   |
| 5.16.7  | 5        | 5.68%   |
| 5.11.0  | 4        | 4.55%   |
| 5.19.0  | 3        | 3.41%   |
| 5.13.0  | 3        | 3.41%   |
| 5.10.14 | 3        | 3.41%   |
| 5.10.0  | 3        | 3.41%   |
| 3.10.0  | 3        | 3.41%   |
| 6.1.0   | 2        | 2.27%   |
| 5.0.0   | 2        | 2.27%   |
| 4.19.0  | 2        | 2.27%   |
| 6.6.8   | 1        | 1.14%   |
| 6.6.12  | 1        | 1.14%   |
| 6.5.0   | 1        | 1.14%   |
| 6.2.6   | 1        | 1.14%   |
| 6.2.1   | 1        | 1.14%   |
| 6.0.7   | 1        | 1.14%   |
| 5.7.0   | 1        | 1.14%   |
| 5.3.18  | 1        | 1.14%   |
| 5.3.0   | 1        | 1.14%   |
| 5.19.9  | 1        | 1.14%   |
| 5.18.5  | 1        | 1.14%   |
| 5.17.9  | 1        | 1.14%   |
| 5.17.5  | 1        | 1.14%   |
| 5.17.4  | 1        | 1.14%   |
| 5.17.0  | 1        | 1.14%   |
| 5.16.0  | 1        | 1.14%   |
| 5.15.60 | 1        | 1.14%   |
| 5.15.28 | 1        | 1.14%   |
| 5.13.4  | 1        | 1.14%   |
| 5.11.16 | 1        | 1.14%   |
| 5.10.59 | 1        | 1.14%   |
| 5.0.10  | 1        | 1.14%   |
| 4.18.0  | 1        | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 13.64%  |
| 5.15    | 11       | 12.5%   |
| 4.15    | 9        | 10.23%  |
| 5.10    | 7        | 7.95%   |
| 5.16    | 6        | 6.82%   |
| 5.8     | 5        | 5.68%   |
| 5.11    | 5        | 5.68%   |
| 5.19    | 4        | 4.55%   |
| 5.17    | 4        | 4.55%   |
| 5.13    | 4        | 4.55%   |
| 5.0     | 3        | 3.41%   |
| 3.10    | 3        | 3.41%   |
| 6.6     | 2        | 2.27%   |
| 6.2     | 2        | 2.27%   |
| 6.1     | 2        | 2.27%   |
| 5.3     | 2        | 2.27%   |
| 4.19    | 2        | 2.27%   |
| 6.5     | 1        | 1.14%   |
| 6.0     | 1        | 1.14%   |
| 5.7     | 1        | 1.14%   |
| 5.18    | 1        | 1.14%   |
| 4.18    | 1        | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 76       | 97.44%  |
| i686   | 2        | 2.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 35       | 42.68%  |
| KDE5       | 16       | 19.51%  |
| Unknown    | 11       | 13.41%  |
| X-Cinnamon | 7        | 8.54%   |
| XFCE       | 5        | 6.1%    |
| LXDE       | 3        | 3.66%   |
| MATE       | 2        | 2.44%   |
| qtile      | 1        | 1.22%   |
| Pantheon   | 1        | 1.22%   |
| LXQt       | 1        | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 61       | 75.31%  |
| Wayland | 16       | 19.75%  |
| Unknown | 3        | 3.7%    |
| Tty     | 1        | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 51.19%  |
| SDDM    | 15       | 17.86%  |
| GDM3    | 12       | 14.29%  |
| GDM     | 8        | 9.52%   |
| LightDM | 4        | 4.76%   |
| TDM     | 2        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_EC   | 41       | 49.4%   |
| en_US   | 24       | 28.92%  |
| es_ES   | 6        | 7.23%   |
| Unknown | 6        | 7.23%   |
| ru_RU   | 1        | 1.2%    |
| es_PE   | 1        | 1.2%    |
| es_MX   | 1        | 1.2%    |
| en_GB   | 1        | 1.2%    |
| en_AG   | 1        | 1.2%    |
| C       | 1        | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 50       | 62.5%   |
| EFI  | 30       | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 60       | 73.17%  |
| Overlay | 8        | 9.76%   |
| Btrfs   | 7        | 8.54%   |
| Xfs     | 3        | 3.66%   |
| Unknown | 3        | 3.66%   |
| Tmpfs   | 1        | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 60%     |
| GPT     | 19       | 23.75%  |
| MBR     | 13       | 16.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 83.95%  |
| Yes       | 13       | 16.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 63.75%  |
| Yes       | 29       | 36.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 24       | 30.77%  |
| Gigabyte Technology | 14       | 17.95%  |
| Intel               | 9        | 11.54%  |
| Biostar             | 9        | 11.54%  |
| Hewlett-Packard     | 4        | 5.13%   |
| ASRock              | 4        | 5.13%   |
| Foxconn             | 3        | 3.85%   |
| Dell                | 3        | 3.85%   |
| MSI                 | 2        | 2.56%   |
| TPV-INVENTA         | 1        | 1.28%   |
| Shuttle             | 1        | 1.28%   |
| Pegatron            | 1        | 1.28%   |
| Google              | 1        | 1.28%   |
| ECS                 | 1        | 1.28%   |
| Cartimex            | 1        | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 4        | 5.13%   |
| ASUS PRIME A320M-A           | 3        | 3.85%   |
| Gigabyte H81M-H              | 2        | 2.56%   |
| Dell OptiPlex 9020           | 2        | 2.56%   |
| Biostar H61MGV3              | 2        | 2.56%   |
| Biostar G31-M7 TE            | 2        | 2.56%   |
| TPV-INVENTA 2AF2 A01         | 1        | 1.28%   |
| Shuttle SFM27                | 1        | 1.28%   |
| Pegatron CQ1506LA            | 1        | 1.28%   |
| MSI MS-7B98                  | 1        | 1.28%   |
| MSI MS-7758                  | 1        | 1.28%   |
| Intel H81                    | 1        | 1.28%   |
| Intel DZ68DB AAG27985-101    | 1        | 1.28%   |
| Intel DP55KG AAE47218-404    | 1        | 1.28%   |
| Intel DH61WW AAG23116-203    | 1        | 1.28%   |
| Intel DH61BF AAG81311-101    | 1        | 1.28%   |
| Intel DG41RQ AAE54511-205    | 1        | 1.28%   |
| Intel DG35EC AAE29266-209    | 1        | 1.28%   |
| Intel DG33BU AAD79951-407    | 1        | 1.28%   |
| Intel DB75EN AAG39650-302    | 1        | 1.28%   |
| HP Slim Desktop S01-pF1xxx   | 1        | 1.28%   |
| HP ProLiant MicroServer      | 1        | 1.28%   |
| HP ProDesk 600 G1 SFF        | 1        | 1.28%   |
| HP Compaq 6200 Pro MT PC     | 1        | 1.28%   |
| Google Panther               | 1        | 1.28%   |
| Gigabyte X58A-UD3R           | 1        | 1.28%   |
| Gigabyte M68MT-S2P           | 1        | 1.28%   |
| Gigabyte H97M-DS3P           | 1        | 1.28%   |
| Gigabyte H97-Gaming 3        | 1        | 1.28%   |
| Gigabyte H410M H V2          | 1        | 1.28%   |
| Gigabyte H410M H             | 1        | 1.28%   |
| Gigabyte H310M H 2.0         | 1        | 1.28%   |
| Gigabyte H270M-D3H           | 1        | 1.28%   |
| Gigabyte H110M-H             | 1        | 1.28%   |
| Gigabyte B550 AORUS ELITE V2 | 1        | 1.28%   |
| Gigabyte B450M DS3H          | 1        | 1.28%   |
| Gigabyte B150M-D3H DDR3-CF   | 1        | 1.28%   |
| Foxconn H61MXL-K             | 1        | 1.28%   |
| Foxconn H61MXE/-S/-V/-K      | 1        | 1.28%   |
| Foxconn Cinema Series        | 1        | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 10       | 12.82%  |
| ASUS All            | 4        | 5.13%   |
| Gigabyte H81M-H     | 2        | 2.56%   |
| Gigabyte H410M      | 2        | 2.56%   |
| Dell OptiPlex       | 2        | 2.56%   |
| Biostar H61MGV3     | 2        | 2.56%   |
| Biostar G31-M7      | 2        | 2.56%   |
| ASUS TUF            | 2        | 2.56%   |
| TPV-INVENTA 2AF2    | 1        | 1.28%   |
| Shuttle SFM27       | 1        | 1.28%   |
| Pegatron CQ1506LA   | 1        | 1.28%   |
| MSI MS-7B98         | 1        | 1.28%   |
| MSI MS-7758         | 1        | 1.28%   |
| Intel H81           | 1        | 1.28%   |
| Intel DZ68DB        | 1        | 1.28%   |
| Intel DP55KG        | 1        | 1.28%   |
| Intel DH61WW        | 1        | 1.28%   |
| Intel DH61BF        | 1        | 1.28%   |
| Intel DG41RQ        | 1        | 1.28%   |
| Intel DG35EC        | 1        | 1.28%   |
| Intel DG33BU        | 1        | 1.28%   |
| Intel DB75EN        | 1        | 1.28%   |
| HP Slim             | 1        | 1.28%   |
| HP ProLiant         | 1        | 1.28%   |
| HP ProDesk          | 1        | 1.28%   |
| HP Compaq           | 1        | 1.28%   |
| Google Panther      | 1        | 1.28%   |
| Gigabyte X58A-UD3R  | 1        | 1.28%   |
| Gigabyte M68MT-S2P  | 1        | 1.28%   |
| Gigabyte H97M-DS3P  | 1        | 1.28%   |
| Gigabyte H97-Gaming | 1        | 1.28%   |
| Gigabyte H310M      | 1        | 1.28%   |
| Gigabyte H270M-D3H  | 1        | 1.28%   |
| Gigabyte H110M-H    | 1        | 1.28%   |
| Gigabyte B550       | 1        | 1.28%   |
| Gigabyte B450M      | 1        | 1.28%   |
| Gigabyte B150M-D3H  | 1        | 1.28%   |
| Foxconn H61MXL-K    | 1        | 1.28%   |
| Foxconn H61MXE      | 1        | 1.28%   |
| Foxconn Cinema      | 1        | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 12.82%  |
| 2020 | 7        | 8.97%   |
| 2012 | 7        | 8.97%   |
| 2018 | 6        | 7.69%   |
| 2014 | 6        | 7.69%   |
| 2011 | 6        | 7.69%   |
| 2009 | 6        | 7.69%   |
| 2015 | 5        | 6.41%   |
| 2019 | 4        | 5.13%   |
| 2017 | 4        | 5.13%   |
| 2016 | 4        | 5.13%   |
| 2008 | 4        | 5.13%   |
| 2021 | 3        | 3.85%   |
| 2010 | 3        | 3.85%   |
| 2007 | 2        | 2.56%   |
| 2023 | 1        | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 78       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 77       | 97.47%  |
| Enabled  | 2        | 2.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 98.72%  |
| Yes  | 1        | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 22       | 26.83%  |
| 4.01-8.0    | 17       | 20.73%  |
| 3.01-4.0    | 14       | 17.07%  |
| 16.01-24.0  | 12       | 14.63%  |
| 32.01-64.0  | 6        | 7.32%   |
| 1.01-2.0    | 5        | 6.1%    |
| 24.01-32.0  | 4        | 4.88%   |
| 64.01-256.0 | 2        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 28       | 30.11%  |
| 2.01-3.0  | 26       | 27.96%  |
| 3.01-4.0  | 15       | 16.13%  |
| 4.01-8.0  | 14       | 15.05%  |
| 0.51-1.0  | 5        | 5.38%   |
| 8.01-16.0 | 3        | 3.23%   |
| 0.01-0.5  | 2        | 2.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 56.1%   |
| 2      | 20       | 24.39%  |
| 3      | 12       | 14.63%  |
| 5      | 2        | 2.44%   |
| 4      | 2        | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 50%     |
| No        | 40       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 78       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 65%     |
| Yes       | 28       | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 79.49%  |
| Yes       | 16       | 20.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ecuador | 78       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Quito                          | 33       | 42.31%  |
| Guayaquil                      | 25       | 32.05%  |
| Manta                          | 3        | 3.85%   |
| Cuenca                         | 3        | 3.85%   |
| Santo Domingo de los Colorados | 2        | 2.56%   |
| Riobamba                       | 2        | 2.56%   |
| Cotacachi                      | 2        | 2.56%   |
| Quevedo                        | 1        | 1.28%   |
| Loja                           | 1        | 1.28%   |
| Latacunga                      | 1        | 1.28%   |
| Las Pinas                      | 1        | 1.28%   |
| Guanujo                        | 1        | 1.28%   |
| Cariamanga                     | 1        | 1.28%   |
| Azogues                        | 1        | 1.28%   |
| Ambato                         | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 31       | 53     | 26.5%   |
| Seagate                     | 22       | 32     | 18.8%   |
| Kingston                    | 14       | 32     | 11.97%  |
| Toshiba                     | 12       | 16     | 10.26%  |
| Samsung Electronics         | 12       | 14     | 10.26%  |
| Hitachi                     | 6        | 6      | 5.13%   |
| A-DATA Technology           | 4        | 6      | 3.42%   |
| Hewlett-Packard             | 3        | 3      | 2.56%   |
| SPCC                        | 2        | 2      | 1.71%   |
| PNY                         | 2        | 2      | 1.71%   |
| Kingston Technology Company | 2        | 4      | 1.71%   |
| Micro Center                | 1        | 1      | 0.85%   |
| Maxtor                      | 1        | 1      | 0.85%   |
| Intel                       | 1        | 1      | 0.85%   |
| Imation                     | 1        | 1      | 0.85%   |
| HPE                         | 1        | 1      | 0.85%   |
| Gigabyte Technology         | 1        | 1      | 0.85%   |
| Fujitsu                     | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 8        | 6.02%   |
| Seagate ST500DM002-1BD142 500GB  | 6        | 4.51%   |
| Toshiba DT01ACA100 1TB           | 5        | 3.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 4        | 3.01%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 3.01%   |
| Toshiba DT01ACA200 2TB           | 3        | 2.26%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 2.26%   |
| Samsung HD502HJ 500GB            | 3        | 2.26%   |
| Kingston SV300S37A60G 64GB SSD   | 3        | 2.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 2        | 1.5%    |
| WDC WD40EFAX-68JH4N1 4TB         | 2        | 1.5%    |
| Toshiba MK7559GSXP 752GB         | 2        | 1.5%    |
| Samsung HD322HJ 320GB            | 2        | 1.5%    |
| Kingston SNVS500G 500GB          | 2        | 1.5%    |
| Kingston SA400S37960G 960GB SSD  | 2        | 1.5%    |
| Hitachi HDS721050CLA660 500GB    | 2        | 1.5%    |
| HP SSD S700 500GB                | 2        | 1.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.75%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.75%   |
| WDC WDBNCE5000PNC 500GB SSD      | 1        | 0.75%   |
| WDC WD7500BPVX-22JC3T0 752GB     | 1        | 0.75%   |
| WDC WD5000AVVS-63M8B0 500GB      | 1        | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 0.75%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.75%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 0.75%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.75%   |
| WDC WD5000AAKS-00V2B0 500GB      | 1        | 0.75%   |
| WDC WD40EFPX-68C6CN0 4TB         | 1        | 0.75%   |
| WDC WD3200AVVS-63L2B0 320GB      | 1        | 0.75%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 0.75%   |
| WDC WD3200AAJS-60M0A0 320GB      | 1        | 0.75%   |
| WDC WD30EZRS-00J99B0 3TB         | 1        | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.75%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.75%   |
| WDC WD1600HLHX-60JJPV1 160GB     | 1        | 0.75%   |
| WDC WD1600AAJS-75M0A0 160GB      | 1        | 0.75%   |
| WDC WD1200BEVS-22UST0 120GB      | 1        | 0.75%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 46     | 33.75%  |
| Seagate             | 22       | 32     | 27.5%   |
| Toshiba             | 11       | 15     | 13.75%  |
| Samsung Electronics | 11       | 13     | 13.75%  |
| Hitachi             | 6        | 6      | 7.5%    |
| Maxtor              | 1        | 1      | 1.25%   |
| HPE                 | 1        | 1      | 1.25%   |
| Fujitsu             | 1        | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 14       | 24     | 41.18%  |
| WDC                 | 6        | 7      | 17.65%  |
| Hewlett-Packard     | 3        | 3      | 8.82%   |
| A-DATA Technology   | 3        | 4      | 8.82%   |
| SPCC                | 2        | 2      | 5.88%   |
| PNY                 | 2        | 2      | 5.88%   |
| Toshiba             | 1        | 1      | 2.94%   |
| Micro Center        | 1        | 1      | 2.94%   |
| Intel               | 1        | 1      | 2.94%   |
| Gigabyte Technology | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 65       | 115    | 63.11%  |
| SSD     | 31       | 46     | 30.1%   |
| NVMe    | 6        | 15     | 5.83%   |
| Unknown | 1        | 1      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 162    | 92.77%  |
| NVMe | 6        | 15     | 7.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 54       | 91     | 52.94%  |
| 0.51-1.0   | 33       | 46     | 32.35%  |
| 1.01-2.0   | 11       | 17     | 10.78%  |
| 3.01-4.0   | 3        | 6      | 2.94%   |
| 2.01-3.0   | 1        | 1      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 22       | 25.29%  |
| 501-1000       | 19       | 21.84%  |
| 101-250        | 14       | 16.09%  |
| 1001-2000      | 11       | 12.64%  |
| 1-20           | 9        | 10.34%  |
| More than 3000 | 6        | 6.9%    |
| 51-100         | 2        | 2.3%    |
| Unknown        | 2        | 2.3%    |
| 21-50          | 1        | 1.15%   |
| 2001-3000      | 1        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 31       | 34.07%  |
| 21-50          | 16       | 17.58%  |
| 251-500        | 12       | 13.19%  |
| 51-100         | 9        | 9.89%   |
| 101-250        | 8        | 8.79%   |
| 501-1000       | 6        | 6.59%   |
| 1001-2000      | 5        | 5.49%   |
| More than 3000 | 2        | 2.2%    |
| Unknown        | 2        | 2.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 3      | 12.5%   |
| Hitachi HDS721050CLA660 500GB     | 2        | 2      | 12.5%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 6.25%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 6.25%   |
| WDC WD1200BEVS-22UST0 120GB       | 1        | 1      | 6.25%   |
| Toshiba MK7559GSXP 752GB          | 1        | 1      | 6.25%   |
| Seagate ST3750330AS 752GB         | 1        | 1      | 6.25%   |
| Seagate ST31000333AS 1TB          | 1        | 2      | 6.25%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2      | 6.25%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 6.25%   |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 6.25%   |
| Kingston SNS4151S316GD 16GB SSD   | 1        | 1      | 6.25%   |
| HPE MB0500EAMZD 500GB             | 1        | 1      | 6.25%   |
| Fujitsu MHZ2160BH G1 160GB        | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 8      | 31.25%  |
| WDC                 | 3        | 3      | 18.75%  |
| Samsung Electronics | 2        | 2      | 12.5%   |
| Hitachi             | 2        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 6.25%   |
| Kingston            | 1        | 1      | 6.25%   |
| HPE                 | 1        | 1      | 6.25%   |
| Fujitsu             | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 8      | 33.33%  |
| WDC                 | 3        | 3      | 20%     |
| Samsung Electronics | 2        | 2      | 13.33%  |
| Hitachi             | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 1      | 6.67%   |
| HPE                 | 1        | 1      | 6.67%   |
| Fujitsu             | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 18     | 91.67%  |
| SSD  | 1        | 1      | 8.33%   |

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
| Detected | 50       | 123    | 58.14%  |
| Works    | 24       | 35     | 27.91%  |
| Malfunc  | 12       | 19     | 13.95%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 58       | 61.05%  |
| AMD                         | 18       | 18.95%  |
| Marvell Technology Group    | 4        | 4.21%   |
| Kingston Technology Company | 4        | 4.21%   |
| JMicron Technology          | 3        | 3.16%   |
| ASMedia Technology          | 3        | 3.16%   |
| VIA Technologies            | 2        | 2.11%   |
| Samsung Electronics         | 1        | 1.05%   |
| Nvidia                      | 1        | 1.05%   |
| ADATA Technology            | 1        | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 8.2%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 7.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 4.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 4.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 4.1%    |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.28%   |
| AMD FCH SATA Controller D                                                               | 4        | 3.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.28%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.46%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 2        | 1.64%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 2        | 1.64%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.64%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.82%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.82%   |
| VIA Serial ATA Controller                                                               | 1        | 0.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.82%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.82%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.82%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 0.82%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 0.82%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.82%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 1        | 0.82%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 63.33%  |
| IDE  | 21       | 23.33%  |
| RAID | 6        | 6.67%   |
| NVMe | 6        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 59       | 75.64%  |
| AMD    | 19       | 24.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 5.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3.85%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 3.85%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 2.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 2.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 2.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 2.56%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 2.56%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 2.56%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 2.56%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 2.56%   |
| AMD Athlon II X2 270 Processor              | 2        | 2.56%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.28%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.28%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.28%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.28%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.28%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.28%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 1.28%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.28%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.28%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.28%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.28%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.28%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.28%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.28%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.28%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.28%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.28%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.28%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.28%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 24.36%  |
| Intel Core i7           | 14       | 17.95%  |
| AMD Ryzen 5             | 10       | 12.82%  |
| Intel Pentium           | 6        | 7.69%   |
| Intel Core i3           | 6        | 7.69%   |
| Intel Celeron           | 4        | 5.13%   |
| Intel Core 2 Duo        | 3        | 3.85%   |
| Intel Core 2 Quad       | 2        | 2.56%   |
| Intel Atom              | 2        | 2.56%   |
| AMD Ryzen 7             | 2        | 2.56%   |
| AMD E1                  | 2        | 2.56%   |
| AMD Athlon II X2        | 2        | 2.56%   |
| Other                   | 1        | 1.28%   |
| Intel Xeon              | 1        | 1.28%   |
| Intel Pentium Dual-Core | 1        | 1.28%   |
| AMD Phenom II X6        | 1        | 1.28%   |
| AMD Phenom II X2        | 1        | 1.28%   |
| AMD Athlon II Neo       | 1        | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 37       | 47.44%  |
| 2      | 25       | 32.05%  |
| 6      | 12       | 15.38%  |
| 8      | 3        | 3.85%   |
| 14     | 1        | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 78       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 57.69%  |
| 2      | 33       | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 77       | 98.72%  |
| Unknown        | 1        | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 21.95%  |
| 0x306c3    | 10       | 12.2%   |
| 0x306a9    | 8        | 9.76%   |
| 0x206a7    | 5        | 6.1%    |
| 0x1067a    | 5        | 6.1%    |
| 0xa0653    | 4        | 4.88%   |
| 0x906ed    | 2        | 2.44%   |
| 0x106e5    | 2        | 2.44%   |
| 0x0a201005 | 2        | 2.44%   |
| 0x08701021 | 2        | 2.44%   |
| 0x0810100b | 2        | 2.44%   |
| 0x010000c8 | 2        | 2.44%   |
| 0xb06f2    | 1        | 1.22%   |
| 0x906ec    | 1        | 1.22%   |
| 0x906ea    | 1        | 1.22%   |
| 0x906e9    | 1        | 1.22%   |
| 0x706a1    | 1        | 1.22%   |
| 0x6fd      | 1        | 1.22%   |
| 0x506e3    | 1        | 1.22%   |
| 0x40651    | 1        | 1.22%   |
| 0x206c2    | 1        | 1.22%   |
| 0x106ca    | 1        | 1.22%   |
| 0x106c2    | 1        | 1.22%   |
| 0x106a5    | 1        | 1.22%   |
| 0x10676    | 1        | 1.22%   |
| 0x0a50000d | 1        | 1.22%   |
| 0x0a201204 | 1        | 1.22%   |
| 0x08701013 | 1        | 1.22%   |
| 0x08101016 | 1        | 1.22%   |
| 0x08101004 | 1        | 1.22%   |
| 0x0700010f | 1        | 1.22%   |
| 0x010000bf | 1        | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 15       | 18.99%  |
| IvyBridge        | 9        | 11.39%  |
| Penryn           | 6        | 7.59%   |
| KabyLake         | 6        | 7.59%   |
| SandyBridge      | 5        | 6.33%   |
| K10              | 5        | 6.33%   |
| CometLake        | 5        | 6.33%   |
| Zen 3            | 4        | 5.06%   |
| Zen 2            | 4        | 5.06%   |
| Skylake          | 4        | 5.06%   |
| Zen              | 3        | 3.8%    |
| Nehalem          | 3        | 3.8%    |
| Bonnell          | 2        | 2.53%   |
| Zen+             | 1        | 1.27%   |
| Westmere         | 1        | 1.27%   |
| Jaguar           | 1        | 1.27%   |
| Goldmont plus    | 1        | 1.27%   |
| Core             | 1        | 1.27%   |
| Bobcat           | 1        | 1.27%   |
| Alderlake Hybrid | 1        | 1.27%   |
| Unknown          | 1        | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 43       | 50%     |
| Nvidia           | 24       | 27.91%  |
| AMD              | 18       | 20.93%  |
| VIA Technologies | 1        | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 12.79%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 8.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 4.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 3.49%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 3.49%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 2        | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.33%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.33%   |
| Intel HD Graphics 630                                                       | 2        | 2.33%   |
| Intel HD Graphics 530                                                       | 2        | 2.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.33%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 2.33%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.16%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.16%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.16%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.16%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.16%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.16%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.16%   |
| Nvidia G98 [Quadro NVS 420]                                                 | 1        | 1.16%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.16%   |
| Intel HD Graphics 510                                                       | 1        | 1.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.16%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 1        | 1.16%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.16%   |
| Intel AlderLake-S GT1                                                       | 1        | 1.16%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 1.16%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.16%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.16%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 37       | 45.68%  |
| 1 x Nvidia               | 21       | 25.93%  |
| 1 x AMD                  | 16       | 19.75%  |
| Intel + Nvidia           | 3        | 3.7%    |
| Intel + AMD              | 2        | 2.47%   |
| 1 x VIA                  | 1        | 1.23%   |
| Intel + AMD + 1 x Nvidia | 1        | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 75.31%  |
| Proprietary | 15       | 18.52%  |
| Unknown     | 5        | 6.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 58.82%  |
| 1.01-2.0   | 15       | 17.65%  |
| 0.51-1.0   | 6        | 7.06%   |
| 0.01-0.5   | 6        | 7.06%   |
| 5.01-6.0   | 3        | 3.53%   |
| 7.01-8.0   | 2        | 2.35%   |
| 8.01-16.0  | 2        | 2.35%   |
| 3.01-4.0   | 1        | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 27       | 36%     |
| Samsung Electronics  | 9        | 12%     |
| BenQ                 | 9        | 12%     |
| AOC                  | 8        | 10.67%  |
| Hewlett-Packard      | 6        | 8%      |
| LG Electronics       | 4        | 5.33%   |
| Dell                 | 3        | 4%      |
| Acer                 | 2        | 2.67%   |
| Unknown (XXX)        | 1        | 1.33%   |
| Philips              | 1        | 1.33%   |
| NEC Computers        | 1        | 1.33%   |
| MStar                | 1        | 1.33%   |
| KTC                  | 1        | 1.33%   |
| DMT                  | 1        | 1.33%   |
| Ancor Communications | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 4        | 4.88%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 3        | 3.66%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3        | 3.66%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3        | 3.66%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2        | 2.44%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2        | 2.44%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 2        | 2.44%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 2        | 2.44%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 2        | 2.44%   |
| Goldstar 20EN33 GSM4EE1 1600x900 440x250mm 19.9-inch                 | 2        | 2.44%   |
| BenQ GL930A BNQ7870 1366x768 410x230mm 18.5-inch                     | 2        | 2.44%   |
| AOC 2251w AOC2251 1920x1080 477x268mm 21.5-inch                      | 2        | 2.44%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch  | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM0027 1280x1024 312x234mm 15.4-inch | 1        | 1.22%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.22%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SMB1930N 1366x768                    | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SAM7048 1366x768 522x293mm 23.6-inch | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 1.22%   |
| Philips LCD Monitor PHL BDM4065 3840x2160                            | 1        | 1.22%   |
| NEC Computers LCD1850E NEC65D1 1280x1024 359x287mm 18.1-inch         | 1        | 1.22%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.22%   |
| LG Electronics LCD Monitor W2043 3520x1080                           | 1        | 1.22%   |
| LG Electronics LCD Monitor 2D HD LG TV                               | 1        | 1.22%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.22%   |
| KTC 32'TV KTC3200 1360x768 708x398mm 32.0-inch                       | 1        | 1.22%   |
| Hewlett-Packard w1858 HWP2835 1366x768 413x234mm 18.7-inch           | 1        | 1.22%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 1        | 1.22%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.22%   |
| Hewlett-Packard Omni/Pro HWP410E 1366x768 410x230mm 18.5-inch        | 1        | 1.22%   |
| Hewlett-Packard LCD Monitor L1710 2646x1024                          | 1        | 1.22%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch          | 1        | 1.22%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch          | 1        | 1.22%   |
| Goldstar W1742 GSM44A2 1440x900 410x256mm 19.0-inch                  | 1        | 1.22%   |
| Goldstar T1910 GSM4BD8 1280x1024 376x301mm 19.0-inch                 | 1        | 1.22%   |
| Goldstar M237WA GSM5724 1920x1080 509x286mm 23.0-inch                | 1        | 1.22%   |
| Goldstar L177WSB GSM448D 1440x900 370x232mm 17.2-inch                | 1        | 1.22%   |
| Goldstar L1530S GSM3B95 1024x768 304x228mm 15.0-inch                 | 1        | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1366x768 (WXGA)  | 21       | 27.63%  |
| 1920x1080 (FHD)  | 18       | 23.68%  |
| 1440x900 (WXGA+) | 8        | 10.53%  |
| 1600x900 (HD+)   | 7        | 9.21%   |
| 1360x768         | 7        | 9.21%   |
| 1024x768 (XGA)   | 4        | 5.26%   |
| 1280x1024 (SXGA) | 3        | 3.95%   |
| 3840x2160 (4K)   | 2        | 2.63%   |
| Unknown          | 2        | 2.63%   |
| 4093x4093        | 1        | 1.32%   |
| 3520x1080        | 1        | 1.32%   |
| 2646x1024        | 1        | 1.32%   |
| 2560x1440 (QHD)  | 1        | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 24       | 31.17%  |
| 19      | 12       | 15.58%  |
| Unknown | 9        | 11.69%  |
| 23      | 8        | 10.39%  |
| 21      | 7        | 9.09%   |
| 15      | 5        | 6.49%   |
| 20      | 4        | 5.19%   |
| 24      | 3        | 3.9%    |
| 32      | 2        | 2.6%    |
| 54      | 1        | 1.3%    |
| 52      | 1        | 1.3%    |
| 17      | 1        | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 42       | 56%     |
| 501-600     | 11       | 14.67%  |
| Unknown     | 9        | 12%     |
| 301-350     | 5        | 6.67%   |
| 351-400     | 4        | 5.33%   |
| 701-800     | 2        | 2.67%   |
| 1001-1500   | 2        | 2.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 63.89%  |
| 16/10   | 9        | 12.5%   |
| Unknown | 9        | 12.5%   |
| 4/3     | 5        | 6.94%   |
| 5/4     | 3        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 23       | 29.87%  |
| 151-200        | 19       | 24.68%  |
| 201-250        | 15       | 19.48%  |
| Unknown        | 9        | 11.69%  |
| 101-110        | 4        | 5.19%   |
| More than 1000 | 2        | 2.6%    |
| 351-500        | 2        | 2.6%    |
| 251-300        | 1        | 1.3%    |
| 131-140        | 1        | 1.3%    |
| 111-120        | 1        | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 55       | 73.33%  |
| Unknown | 9        | 12%     |
| 101-120 | 8        | 10.67%  |
| 1-50    | 3        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 85.19%  |
| 2     | 9        | 11.11%  |
| 0     | 3        | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 55       | 51.4%   |
| Intel                           | 20       | 18.69%  |
| Qualcomm Atheros                | 8        | 7.48%   |
| Ralink Technology               | 6        | 5.61%   |
| TP-Link                         | 5        | 4.67%   |
| Ralink                          | 2        | 1.87%   |
| D-Link System                   | 2        | 1.87%   |
| Broadcom                        | 2        | 1.87%   |
| Xiaomi                          | 1        | 0.93%   |
| VIA Technologies                | 1        | 0.93%   |
| TRENDnet                        | 1        | 0.93%   |
| Samsung Electronics             | 1        | 0.93%   |
| Qualcomm Atheros Communications | 1        | 0.93%   |
| Nvidia                          | 1        | 0.93%   |
| Arduino SA                      | 1        | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 41       | 35.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 6        | 5.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 3        | 2.59%   |
| Intel Ethernet Connection I217-LM                                                             | 3        | 2.59%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 2.59%   |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 2.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 2        | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 1.72%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 1.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 2        | 1.72%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.72%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 2        | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1        | 0.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.86%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS]             | 1        | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.86%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 0.86%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.86%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.86%   |
| TP-Link 802.11n NIC                                                                           | 1        | 0.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 1        | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 0.86%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 1        | 0.86%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.86%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.86%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 0.86%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1        | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 33.33%  |
| Ralink Technology               | 6        | 20%     |
| TP-Link                         | 5        | 16.67%  |
| Qualcomm Atheros                | 3        | 10%     |
| Ralink                          | 2        | 6.67%   |
| Intel                           | 2        | 6.67%   |
| TRENDnet                        | 1        | 3.33%   |
| Qualcomm Atheros Communications | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 10%     |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 6.67%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 6.67%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS]             | 1        | 3.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 3.33%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 3.33%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 3.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 3.33%   |
| TP-Link 802.11n NIC                                                                           | 1        | 3.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 3.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 3.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 3.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 3.33%   |
| Realtek 802.11ac NIC                                                                          | 1        | 3.33%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 3.33%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 3.33%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 3.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 52       | 61.9%   |
| Intel                 | 19       | 22.62%  |
| Qualcomm Atheros      | 5        | 5.95%   |
| D-Link System         | 2        | 2.38%   |
| Broadcom              | 2        | 2.38%   |
| Xiaomi                | 1        | 1.19%   |
| VIA Technologies      | 1        | 1.19%   |
| Samsung Electronics   | 1        | 1.19%   |
| Nvidia                | 1        | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 41       | 48.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 7.06%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 3.53%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 3.53%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 3.53%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 3.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 2.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2        | 2.35%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.35%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 2.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.18%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 1.18%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 1.18%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.18%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1        | 1.18%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.18%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.18%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.18%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 1.18%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 1.18%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 1.18%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 1.18%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 1.18%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.18%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                       | 1        | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 78       | 72.9%   |
| WiFi     | 28       | 26.17%  |
| Modem    | 1        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 79.75%  |
| WiFi     | 16       | 20.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 81.01%  |
| 2     | 13       | 16.46%  |
| 3     | 2        | 2.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 85.37%  |
| Yes  | 12       | 14.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 56.25%  |
| Intel                   | 2        | 12.5%   |
| TP-Link                 | 1        | 6.25%   |
| Realtek Semiconductor   | 1        | 6.25%   |
| IMC Networks            | 1        | 6.25%   |
| D-Link System           | 1        | 6.25%   |
| ASUSTek Computer        | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 56.25%  |
| TP-Link UB500 Adapter                               | 1        | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.25%   |
| Intel Bluetooth Device                              | 1        | 6.25%   |
| Intel AX201 Bluetooth                               | 1        | 6.25%   |
| IMC Networks Bluetooth Device                       | 1        | 6.25%   |
| D-Link System DBT-122 Bluetooth                     | 1        | 6.25%   |
| ASUS ASUS USB-BT500                                 | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 59       | 55.66%  |
| AMD              | 23       | 21.7%   |
| Nvidia           | 22       | 20.75%  |
| VIA Technologies | 1        | 0.94%   |
| Sony             | 1        | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 9.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 8.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 8.53%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 5.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 4.65%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 3.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 3.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 3.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.33%   |
| Nvidia High Definition Audio Controller                                    | 3        | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 2.33%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 2.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.55%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.55%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.55%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.55%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.78%   |
| Sony Audio                                                                 | 1        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.78%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.78%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 0.78%   |
| Intel USB PnP Sound Device                                                 | 1        | 0.78%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 0.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 32.5%   |
| Unknown             | 8        | 20%     |
| Corsair             | 6        | 15%     |
| A-DATA Technology   | 3        | 7.5%    |
| Samsung Electronics | 2        | 5%      |
| Micron Technology   | 2        | 5%      |
| Avant               | 2        | 5%      |
| PNY                 | 1        | 2.5%    |
| Hewlett-Packard     | 1        | 2.5%    |
| Gold Key            | 1        | 2.5%    |
| Crucial             | 1        | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 2.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 2.17%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 2.17%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1        | 2.17%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1        | 2.17%   |
| Unknown RAM Module 1GB DIMM DDR2                          | 1        | 2.17%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                   | 1        | 2.17%   |
| Samsung RAM Module 4GB DIMM DDR4 3200MT/s                 | 1        | 2.17%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| PNY RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 2.17%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 2.17%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 2.17%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s      | 1        | 2.17%   |
| Kingston RAM KHX3000C16D4/16GX 16GB DIMM DDR4 3000MT/s    | 1        | 2.17%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 2.17%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 2.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 1        | 2.17%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 2.17%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5471-038.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5403-034.A00G 4GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Kingston RAM 9905402-171.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| HP RAM 7EH55AA# 8GB DIMM DDR4 2666MT/s                    | 1        | 2.17%   |
| Gold Key RAM NMUD440D82-3200D 4GB DIMM DDR4 3200MT/s      | 1        | 2.17%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Corsair RAM CMZ16GX3M2A1600C1 8GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Corsair RAM CMV16GX4M1A2666C18 16384MB DIMM DDR4 2667MT/s | 1        | 2.17%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s    | 1        | 2.17%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 1        | 2.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 14       | 41.18%  |
| DDR4    | 13       | 38.24%  |
| DDR2    | 4        | 11.76%  |
| Unknown | 2        | 5.88%   |
| SDRAM   | 1        | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 97.06%  |
| SODIMM | 1        | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 13       | 32.5%   |
| 8192  | 12       | 30%     |
| 2048  | 8        | 20%     |
| 16384 | 4        | 10%     |
| 1024  | 2        | 5%      |
| 32768 | 1        | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 10       | 24.39%  |
| 1600    | 8        | 19.51%  |
| 3200    | 3        | 7.32%   |
| 2133    | 3        | 7.32%   |
| Unknown | 3        | 7.32%   |
| 2667    | 2        | 4.88%   |
| 3933    | 1        | 2.44%   |
| 3733    | 1        | 2.44%   |
| 3600    | 1        | 2.44%   |
| 3534    | 1        | 2.44%   |
| 3533    | 1        | 2.44%   |
| 3466    | 1        | 2.44%   |
| 3400    | 1        | 2.44%   |
| 3000    | 1        | 2.44%   |
| 2666    | 1        | 2.44%   |
| 1866    | 1        | 2.44%   |
| 800     | 1        | 2.44%   |
| 667     | 1        | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Hewlett-Packard     | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1        | 50%     |
| HP Deskjet 2050 J510               | 1        | 50%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Microdia                    | 3        | 15%     |
| KYE Systems (Mouse Systems) | 3        | 15%     |
| Pixart Imaging              | 2        | 10%     |
| Logitech                    | 2        | 10%     |
| Generalplus Technology      | 2        | 10%     |
| Unknown                     | 1        | 5%      |
| Novatek Microelectronics    | 1        | 5%      |
| Jieli Technology            | 1        | 5%      |
| IMC Networks                | 1        | 5%      |
| Genesys Logic               | 1        | 5%      |
| GEMBIRD                     | 1        | 5%      |
| Chicony Electronics         | 1        | 5%      |
| Arkmicro Technologies       | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Microdia Camera                             | 2        | 10%     |
| Logitech Webcam C270                        | 2        | 10%     |
| Unknown HD camera                           | 1        | 5%      |
| Pixart Imaging Webcam Genius iLook 300      | 1        | 5%      |
| Pixart Imaging Multimedia audio controller  | 1        | 5%      |
| Novatek NTK96550-based camera (webcam mode) | 1        | 5%      |
| Microdia Webcam Vitade AF                   | 1        | 5%      |
| KYE Systems (Mouse Systems) WideCam 1050    | 1        | 5%      |
| KYE Systems (Mouse Systems) Genius Webcam   | 1        | 5%      |
| KYE Systems (Mouse Systems) FaceCam 310     | 1        | 5%      |
| Jieli USB PHY 2.0                           | 1        | 5%      |
| IMC Networks XHC Camera                     | 1        | 5%      |
| Genesys Logic USB2.0 UVC PC Camera          | 1        | 5%      |
| Generalplus GENERAL WEBCAM                  | 1        | 5%      |
| Generalplus 808 Camera                      | 1        | 5%      |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 5%      |
| Chicony HP High Definition 1MP Webcam       | 1        | 5%      |
| Arkmicro USB2.0 PC CAMERA                   | 1        | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| AuthenTec | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AuthenTec AES1600 | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 66       | 81.48%  |
| 1     | 13       | 16.05%  |
| 2     | 2        | 2.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 47.06%  |
| Net/wireless             | 5        | 29.41%  |
| Communication controller | 2        | 11.76%  |
| Fingerprint reader       | 1        | 5.88%   |
| Chipcard                 | 1        | 5.88%   |


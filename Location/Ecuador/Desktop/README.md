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

Total: 137

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B550-A PRO                  | [204aaa19ef](https://linux-hardware.org/?probe=204aaa19ef) | Dec 13, 2024 |
| Dell          | 0F3KHR A00                  | [0293193b5e](https://linux-hardware.org/?probe=0293193b5e) | Sep 26, 2024 |
| Biostar       | H61MLB                      | [10f695fe18](https://linux-hardware.org/?probe=10f695fe18) | Jul 31, 2024 |
| ASRock        | B650M PG Riptide            | [2672901369](https://linux-hardware.org/?probe=2672901369) | Jul 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [92ca1f097e](https://linux-hardware.org/?probe=92ca1f097e) | Jun 30, 2024 |
| Gigabyte      | H81M-S1                     | [4852045434](https://linux-hardware.org/?probe=4852045434) | Jun 08, 2024 |
| Intel         | DH61BF AAG81311-102         | [e33f8a4718](https://linux-hardware.org/?probe=e33f8a4718) | Jun 01, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [ca35abddb1](https://linux-hardware.org/?probe=ca35abddb1) | May 30, 2024 |
| HP            | 8299                        | [6024274be6](https://linux-hardware.org/?probe=6024274be6) | May 06, 2024 |
| Pegatron      | 2AA1h                       | [52b3bc466c](https://linux-hardware.org/?probe=52b3bc466c) | Apr 25, 2024 |
| ASRock        | Z790 Steel Legend WiFi      | [cdfa410878](https://linux-hardware.org/?probe=cdfa410878) | Apr 05, 2024 |
| ASRock        | Z790 Steel Legend WiFi      | [9e4b6c171a](https://linux-hardware.org/?probe=9e4b6c171a) | Apr 04, 2024 |
| Intel         | H55                         | [361d690313](https://linux-hardware.org/?probe=361d690313) | Mar 26, 2024 |
| Gigabyte      | M68MT-S2P                   | [21be6e4ab5](https://linux-hardware.org/?probe=21be6e4ab5) | Feb 07, 2024 |
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
| Ubuntu 20.04       | 15       | 15%     |
| Ubuntu 18.04       | 10       | 10%     |
| Ubuntu 22.04       | 8        | 8%      |
| OpenMandriva 4.3   | 4        | 4%      |
| Debian 12          | 4        | 4%      |
| OpenMandriva 4.2   | 3        | 3%      |
| Debian 11          | 3        | 3%      |
| CentOS 7           | 3        | 3%      |
| Zorin 16           | 2        | 2%      |
| Linux Mint 21.3    | 2        | 2%      |
| Linux Mint 21.1    | 2        | 2%      |
| Linux Mint 19.1    | 2        | 2%      |
| Fedora 36          | 2        | 2%      |
| Fedora 34          | 2        | 2%      |
| Zorin 17           | 1        | 1%      |
| Xubuntu 18.04      | 1        | 1%      |
| Ubuntu 24.04       | 1        | 1%      |
| Ubuntu 22.10       | 1        | 1%      |
| Ubuntu 21.10       | 1        | 1%      |
| Ubuntu 16.04       | 1        | 1%      |
| Pop!_OS 21.04      | 1        | 1%      |
| Pop!_OS 20.04      | 1        | 1%      |
| Peppermint 10      | 1        | 1%      |
| openSUSE Leap-15.2 | 1        | 1%      |
| OpenMandriva 5.0   | 1        | 1%      |
| OpenMandriva 24.90 | 1        | 1%      |
| OpenMandriva 24.07 | 1        | 1%      |
| OpenMandriva 23.90 | 1        | 1%      |
| OpenMandriva 23.03 | 1        | 1%      |
| Nobara 36          | 1        | 1%      |
| Manjaro 21.3.7     | 1        | 1%      |
| Manjaro 21.2.5     | 1        | 1%      |
| Manjaro            | 1        | 1%      |
| Lubuntu 23.10      | 1        | 1%      |
| Lubuntu 16.04      | 1        | 1%      |
| LMDE 6             | 1        | 1%      |
| LMDE 4             | 1        | 1%      |
| Linux Mint 21      | 1        | 1%      |
| Linux Mint 20.3    | 1        | 1%      |
| Linux Mint 20.1    | 1        | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 36       | 37.11%  |
| OpenMandriva | 10       | 10.31%  |
| Linux Mint   | 9        | 9.28%   |
| Fedora       | 8        | 8.25%   |
| Debian       | 8        | 8.25%   |
| Zorin        | 3        | 3.09%   |
| Manjaro      | 3        | 3.09%   |
| CentOS       | 3        | 3.09%   |
| Pop!_OS      | 2        | 2.06%   |
| Lubuntu      | 2        | 2.06%   |
| LMDE         | 2        | 2.06%   |
| Arch         | 2        | 2.06%   |
| Xubuntu      | 1        | 1.03%   |
| Peppermint   | 1        | 1.03%   |
| openSUSE     | 1        | 1.03%   |
| Nobara       | 1        | 1.03%   |
| Kubuntu      | 1        | 1.03%   |
| KDE neon     | 1        | 1.03%   |
| Kali         | 1        | 1.03%   |
| Elementary   | 1        | 1.03%   |
| Clear Linux  | 1        | 1.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003      | 4        | 3.7%    |
| 5.10.14-desktop-1omv4002     | 3        | 2.78%   |
| 6.5.0-26-generic             | 2        | 1.85%   |
| 6.1.0-21-amd64               | 2        | 1.85%   |
| 5.8.0-50-generic             | 2        | 1.85%   |
| 5.4.0-73-generic             | 2        | 1.85%   |
| 5.4.0-54-generic             | 2        | 1.85%   |
| 5.4.0-29-generic             | 2        | 1.85%   |
| 5.15.0-56-generic            | 2        | 1.85%   |
| 4.15.0-20-generic            | 2        | 1.85%   |
| 3.10.0-1062.el7.x86_64       | 2        | 1.85%   |
| 6.8.0-50-generic             | 1        | 0.93%   |
| 6.6.8-arch1-1                | 1        | 0.93%   |
| 6.6.2-desktop-1omv2390       | 1        | 0.93%   |
| 6.6.12-201.fsync.fc39.x86_64 | 1        | 0.93%   |
| 6.5.0-35-generic             | 1        | 0.93%   |
| 6.5.0-14-generic             | 1        | 0.93%   |
| 6.2.9-300.fc38.x86_64        | 1        | 0.93%   |
| 6.2.6-desktop-1omv2390       | 1        | 0.93%   |
| 6.2.1-desktop-1omv2390       | 1        | 0.93%   |
| 6.10.9-desktop-1omv2490      | 1        | 0.93%   |
| 6.10.0-desktop-1omv2490      | 1        | 0.93%   |
| 6.1.0-9-amd64                | 1        | 0.93%   |
| 6.1.0-23-amd64               | 1        | 0.93%   |
| 6.1.0-13-amd64               | 1        | 0.93%   |
| 6.0.7-301.fc37.x86_64        | 1        | 0.93%   |
| 5.8.0-63-generic             | 1        | 0.93%   |
| 5.8.0-41-generic             | 1        | 0.93%   |
| 5.8.0-40-generic             | 1        | 0.93%   |
| 5.7.0-0.bpo.2-amd64          | 1        | 0.93%   |
| 5.4.0-91-generic             | 1        | 0.93%   |
| 5.4.0-81-generic             | 1        | 0.93%   |
| 5.4.0-7634-generic           | 1        | 0.93%   |
| 5.4.0-45-generic             | 1        | 0.93%   |
| 5.4.0-42-generic             | 1        | 0.93%   |
| 5.4.0-37-generic             | 1        | 0.93%   |
| 5.4.0-126-generic            | 1        | 0.93%   |
| 5.3.18-lp152.87-default      | 1        | 0.93%   |
| 5.3.0-46-generic             | 1        | 0.93%   |
| 5.19.9-201.fsync.fc36.x86_64 | 1        | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 12       | 12%     |
| 5.15.0  | 10       | 10%     |
| 4.15.0  | 9        | 9%      |
| 6.1.0   | 5        | 5%      |
| 5.8.0   | 5        | 5%      |
| 5.16.7  | 5        | 5%      |
| 6.5.0   | 4        | 4%      |
| 5.11.0  | 4        | 4%      |
| 5.19.0  | 3        | 3%      |
| 5.13.0  | 3        | 3%      |
| 5.10.14 | 3        | 3%      |
| 5.10.0  | 3        | 3%      |
| 3.10.0  | 3        | 3%      |
| 5.0.0   | 2        | 2%      |
| 4.19.0  | 2        | 2%      |
| 6.8.0   | 1        | 1%      |
| 6.6.8   | 1        | 1%      |
| 6.6.2   | 1        | 1%      |
| 6.6.12  | 1        | 1%      |
| 6.2.9   | 1        | 1%      |
| 6.2.6   | 1        | 1%      |
| 6.2.1   | 1        | 1%      |
| 6.10.9  | 1        | 1%      |
| 6.10.0  | 1        | 1%      |
| 6.0.7   | 1        | 1%      |
| 5.7.0   | 1        | 1%      |
| 5.3.18  | 1        | 1%      |
| 5.3.0   | 1        | 1%      |
| 5.19.9  | 1        | 1%      |
| 5.18.5  | 1        | 1%      |
| 5.17.9  | 1        | 1%      |
| 5.17.5  | 1        | 1%      |
| 5.17.4  | 1        | 1%      |
| 5.17.0  | 1        | 1%      |
| 5.16.0  | 1        | 1%      |
| 5.15.60 | 1        | 1%      |
| 5.15.28 | 1        | 1%      |
| 5.13.4  | 1        | 1%      |
| 5.11.16 | 1        | 1%      |
| 5.10.59 | 1        | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 12%     |
| 5.15    | 12       | 12%     |
| 4.15    | 9        | 9%      |
| 5.10    | 7        | 7%      |
| 5.16    | 6        | 6%      |
| 6.1     | 5        | 5%      |
| 5.8     | 5        | 5%      |
| 5.11    | 5        | 5%      |
| 6.5     | 4        | 4%      |
| 5.19    | 4        | 4%      |
| 5.17    | 4        | 4%      |
| 5.13    | 4        | 4%      |
| 6.6     | 3        | 3%      |
| 6.2     | 3        | 3%      |
| 5.0     | 3        | 3%      |
| 3.10    | 3        | 3%      |
| 6.10    | 2        | 2%      |
| 5.3     | 2        | 2%      |
| 4.19    | 2        | 2%      |
| 6.8     | 1        | 1%      |
| 6.0     | 1        | 1%      |
| 5.7     | 1        | 1%      |
| 5.18    | 1        | 1%      |
| 4.18    | 1        | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 88       | 97.78%  |
| i686   | 2        | 2.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 41       | 43.16%  |
| KDE5       | 17       | 17.89%  |
| Unknown    | 13       | 13.68%  |
| XFCE       | 8        | 8.42%   |
| X-Cinnamon | 8        | 8.42%   |
| LXDE       | 3        | 3.16%   |
| MATE       | 2        | 2.11%   |
| qtile      | 1        | 1.05%   |
| Pantheon   | 1        | 1.05%   |
| LXQt       | 1        | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 69       | 75%     |
| Wayland | 20       | 21.74%  |
| Unknown | 2        | 2.17%   |
| Tty     | 1        | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 46       | 47.42%  |
| SDDM    | 18       | 18.56%  |
| GDM3    | 15       | 15.46%  |
| LightDM | 8        | 8.25%   |
| GDM     | 8        | 8.25%   |
| TDM     | 2        | 2.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_EC   | 48       | 50.53%  |
| en_US   | 28       | 29.47%  |
| es_ES   | 6        | 6.32%   |
| Unknown | 6        | 6.32%   |
| ru_RU   | 1        | 1.05%   |
| es_PE   | 1        | 1.05%   |
| es_MX   | 1        | 1.05%   |
| es_CO   | 1        | 1.05%   |
| en_GB   | 1        | 1.05%   |
| en_AG   | 1        | 1.05%   |
| C       | 1        | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 55       | 59.78%  |
| EFI  | 37       | 40.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 65       | 69.15%  |
| Overlay | 11       | 11.7%   |
| Btrfs   | 8        | 8.51%   |
| Xfs     | 5        | 5.32%   |
| Unknown | 3        | 3.19%   |
| Tmpfs   | 2        | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 54.84%  |
| GPT     | 27       | 29.03%  |
| MBR     | 15       | 16.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 84.95%  |
| Yes       | 14       | 15.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 63.04%  |
| Yes       | 34       | 36.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 26       | 28.89%  |
| Gigabyte Technology | 15       | 16.67%  |
| Intel               | 11       | 12.22%  |
| Biostar             | 10       | 11.11%  |
| ASRock              | 6        | 6.67%   |
| Hewlett-Packard     | 5        | 5.56%   |
| Dell                | 4        | 4.44%   |
| MSI                 | 3        | 3.33%   |
| Foxconn             | 3        | 3.33%   |
| Pegatron            | 2        | 2.22%   |
| TPV-INVENTA         | 1        | 1.11%   |
| Shuttle             | 1        | 1.11%   |
| Google              | 1        | 1.11%   |
| ECS                 | 1        | 1.11%   |
| Cartimex            | 1        | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 4        | 4.44%   |
| ASUS PRIME A320M-A         | 3        | 3.33%   |
| Gigabyte H81M-H            | 2        | 2.22%   |
| Dell OptiPlex 9020         | 2        | 2.22%   |
| Biostar H61MGV3            | 2        | 2.22%   |
| Biostar G31-M7 TE          | 2        | 2.22%   |
| TPV-INVENTA 2AF2 A01       | 1        | 1.11%   |
| Shuttle SFM27              | 1        | 1.11%   |
| Pegatron CQ1506LA          | 1        | 1.11%   |
| Pegatron 2AA1h             | 1        | 1.11%   |
| MSI MS-7C56                | 1        | 1.11%   |
| MSI MS-7B98                | 1        | 1.11%   |
| MSI MS-7758                | 1        | 1.11%   |
| Intel H81                  | 1        | 1.11%   |
| Intel H55                  | 1        | 1.11%   |
| Intel DZ68DB AAG27985-101  | 1        | 1.11%   |
| Intel DP55KG AAE47218-404  | 1        | 1.11%   |
| Intel DH61WW AAG23116-203  | 1        | 1.11%   |
| Intel DH61BF AAG81311-102  | 1        | 1.11%   |
| Intel DH61BF AAG81311-101  | 1        | 1.11%   |
| Intel DG41RQ AAE54511-205  | 1        | 1.11%   |
| Intel DG35EC AAE29266-209  | 1        | 1.11%   |
| Intel DG33BU AAD79951-407  | 1        | 1.11%   |
| Intel DB75EN AAG39650-302  | 1        | 1.11%   |
| HP Slim Desktop S01-pF1xxx | 1        | 1.11%   |
| HP ProLiant MicroServer    | 1        | 1.11%   |
| HP ProDesk 600 G1 SFF      | 1        | 1.11%   |
| HP EliteDesk 800 G3 SFF    | 1        | 1.11%   |
| HP Compaq 6200 Pro MT PC   | 1        | 1.11%   |
| Google Panther             | 1        | 1.11%   |
| Gigabyte X58A-UD3R         | 1        | 1.11%   |
| Gigabyte M68MT-S2P         | 1        | 1.11%   |
| Gigabyte H97M-DS3P         | 1        | 1.11%   |
| Gigabyte H97-Gaming 3      | 1        | 1.11%   |
| Gigabyte H81M-S1           | 1        | 1.11%   |
| Gigabyte H410M H V2        | 1        | 1.11%   |
| Gigabyte H410M H           | 1        | 1.11%   |
| Gigabyte H310M H 2.0       | 1        | 1.11%   |
| Gigabyte H270M-D3H         | 1        | 1.11%   |
| Gigabyte H110M-H           | 1        | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 11       | 12.22%  |
| ASUS All            | 4        | 4.44%   |
| Dell OptiPlex       | 3        | 3.33%   |
| ASUS TUF            | 3        | 3.33%   |
| Intel DH61BF        | 2        | 2.22%   |
| Gigabyte H81M-H     | 2        | 2.22%   |
| Gigabyte H410M      | 2        | 2.22%   |
| Biostar H61MGV3     | 2        | 2.22%   |
| Biostar G31-M7      | 2        | 2.22%   |
| TPV-INVENTA 2AF2    | 1        | 1.11%   |
| Shuttle SFM27       | 1        | 1.11%   |
| Pegatron CQ1506LA   | 1        | 1.11%   |
| Pegatron 2AA1h      | 1        | 1.11%   |
| MSI MS-7C56         | 1        | 1.11%   |
| MSI MS-7B98         | 1        | 1.11%   |
| MSI MS-7758         | 1        | 1.11%   |
| Intel H81           | 1        | 1.11%   |
| Intel H55           | 1        | 1.11%   |
| Intel DZ68DB        | 1        | 1.11%   |
| Intel DP55KG        | 1        | 1.11%   |
| Intel DH61WW        | 1        | 1.11%   |
| Intel DG41RQ        | 1        | 1.11%   |
| Intel DG35EC        | 1        | 1.11%   |
| Intel DG33BU        | 1        | 1.11%   |
| Intel DB75EN        | 1        | 1.11%   |
| HP Slim             | 1        | 1.11%   |
| HP ProLiant         | 1        | 1.11%   |
| HP ProDesk          | 1        | 1.11%   |
| HP EliteDesk        | 1        | 1.11%   |
| HP Compaq           | 1        | 1.11%   |
| Google Panther      | 1        | 1.11%   |
| Gigabyte X58A-UD3R  | 1        | 1.11%   |
| Gigabyte M68MT-S2P  | 1        | 1.11%   |
| Gigabyte H97M-DS3P  | 1        | 1.11%   |
| Gigabyte H97-Gaming | 1        | 1.11%   |
| Gigabyte H81M-S1    | 1        | 1.11%   |
| Gigabyte H310M      | 1        | 1.11%   |
| Gigabyte H270M-D3H  | 1        | 1.11%   |
| Gigabyte H110M-H    | 1        | 1.11%   |
| Gigabyte B550       | 1        | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 14.44%  |
| 2020 | 8        | 8.89%   |
| 2014 | 7        | 7.78%   |
| 2012 | 7        | 7.78%   |
| 2011 | 7        | 7.78%   |
| 2018 | 6        | 6.67%   |
| 2009 | 6        | 6.67%   |
| 2021 | 5        | 5.56%   |
| 2017 | 5        | 5.56%   |
| 2015 | 5        | 5.56%   |
| 2019 | 4        | 4.44%   |
| 2016 | 4        | 4.44%   |
| 2010 | 4        | 4.44%   |
| 2008 | 4        | 4.44%   |
| 2022 | 3        | 3.33%   |
| 2007 | 2        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 90       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 89       | 97.8%   |
| Enabled  | 2        | 2.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 89       | 98.89%  |
| Yes  | 1        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 23       | 24.47%  |
| 4.01-8.0    | 21       | 22.34%  |
| 3.01-4.0    | 16       | 17.02%  |
| 16.01-24.0  | 14       | 14.89%  |
| 32.01-64.0  | 6        | 6.38%   |
| 24.01-32.0  | 6        | 6.38%   |
| 1.01-2.0    | 5        | 5.32%   |
| 64.01-256.0 | 3        | 3.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 33       | 31.13%  |
| 2.01-3.0  | 28       | 26.42%  |
| 3.01-4.0  | 18       | 16.98%  |
| 4.01-8.0  | 17       | 16.04%  |
| 0.51-1.0  | 5        | 4.72%   |
| 8.01-16.0 | 3        | 2.83%   |
| 0.01-0.5  | 2        | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 56.38%  |
| 2      | 22       | 23.4%   |
| 3      | 14       | 14.89%  |
| 5      | 2        | 2.13%   |
| 4      | 2        | 2.13%   |
| 6      | 1        | 1.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 50.54%  |
| Yes       | 46       | 49.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 90       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 63.04%  |
| Yes       | 34       | 36.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 77.78%  |
| Yes       | 20       | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ecuador | 90       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Quito                          | 38       | 42.22%  |
| Guayaquil                      | 31       | 34.44%  |
| Riobamba                       | 3        | 3.33%   |
| Manta                          | 3        | 3.33%   |
| Cuenca                         | 3        | 3.33%   |
| Santo Domingo de los Colorados | 2        | 2.22%   |
| Cotacachi                      | 2        | 2.22%   |
| Quevedo                        | 1        | 1.11%   |
| Loja                           | 1        | 1.11%   |
| Latacunga                      | 1        | 1.11%   |
| Las Pinas                      | 1        | 1.11%   |
| Guanujo                        | 1        | 1.11%   |
| Cariamanga                     | 1        | 1.11%   |
| Azogues                        | 1        | 1.11%   |
| Ambato                         | 1        | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 36       | 59     | 26.28%  |
| Seagate                     | 28       | 38     | 20.44%  |
| Kingston                    | 15       | 34     | 10.95%  |
| Toshiba                     | 13       | 18     | 9.49%   |
| Samsung Electronics         | 13       | 15     | 9.49%   |
| Hitachi                     | 7        | 7      | 5.11%   |
| Kingston Technology Company | 4        | 6      | 2.92%   |
| A-DATA Technology           | 4        | 6      | 2.92%   |
| Hewlett-Packard             | 3        | 3      | 2.19%   |
| SPCC                        | 2        | 2      | 1.46%   |
| PNY                         | 2        | 2      | 1.46%   |
| Gigabyte Technology         | 2        | 2      | 1.46%   |
| Micro Center                | 1        | 1      | 0.73%   |
| Maxtor                      | 1        | 1      | 0.73%   |
| Intel                       | 1        | 1      | 0.73%   |
| Imation                     | 1        | 1      | 0.73%   |
| HPE                         | 1        | 1      | 0.73%   |
| Fujitsu                     | 1        | 1      | 0.73%   |
| ANKEJE                      | 1        | 1      | 0.73%   |
| addlink                     | 1        | 2      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 8        | 5.19%   |
| Seagate ST500DM002-1BD142 500GB  | 7        | 4.55%   |
| Toshiba DT01ACA100 1TB           | 5        | 3.25%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 4        | 2.6%    |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 2.6%    |
| WDC WDS480G2G0A-00JH30 480GB SSD | 3        | 1.95%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 1.95%   |
| Toshiba DT01ACA200 2TB           | 3        | 1.95%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 1.95%   |
| Samsung HD502HJ 500GB            | 3        | 1.95%   |
| Kingston SV300S37A60G 64GB SSD   | 3        | 1.95%   |
| Hitachi HDS721050CLA660 500GB    | 3        | 1.95%   |
| WDC WD40EFAX-68JH4N1 4TB         | 2        | 1.3%    |
| WDC WD10EZEX-00WN4A0 1TB         | 2        | 1.3%    |
| Toshiba MK7559GSXP 752GB         | 2        | 1.3%    |
| Seagate ST31000524AS 1TB         | 2        | 1.3%    |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.3%    |
| Samsung HD322HJ 320GB            | 2        | 1.3%    |
| Kingston Company SNV2S2000G 2TB  | 2        | 1.3%    |
| Kingston SNVS500G 500GB          | 2        | 1.3%    |
| Kingston SA400S37960G 960GB SSD  | 2        | 1.3%    |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.3%    |
| HP SSD S700 500GB                | 2        | 1.3%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.65%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.65%   |
| WDC WDBNCE5000PNC 500GB SSD      | 1        | 0.65%   |
| WDC WD7500BPVX-22JC3T0 752GB     | 1        | 0.65%   |
| WDC WD5000AVVS-63M8B0 500GB      | 1        | 0.65%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 0.65%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.65%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 0.65%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.65%   |
| WDC WD5000AAKS-00V2B0 500GB      | 1        | 0.65%   |
| WDC WD40EFPX-68C6CN0 4TB         | 1        | 0.65%   |
| WDC WD3200AVVS-63L2B0 320GB      | 1        | 0.65%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 0.65%   |
| WDC WD3200AAJS-60M0A0 320GB      | 1        | 0.65%   |
| WDC WD30EZRS-00J99B0 3TB         | 1        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 51     | 33.7%   |
| Seagate             | 28       | 38     | 30.43%  |
| Toshiba             | 12       | 17     | 13.04%  |
| Samsung Electronics | 11       | 13     | 11.96%  |
| Hitachi             | 7        | 7      | 7.61%   |
| Maxtor              | 1        | 1      | 1.09%   |
| HPE                 | 1        | 1      | 1.09%   |
| Fujitsu             | 1        | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 15       | 26     | 41.67%  |
| WDC                 | 7        | 8      | 19.44%  |
| Hewlett-Packard     | 3        | 3      | 8.33%   |
| A-DATA Technology   | 3        | 4      | 8.33%   |
| SPCC                | 2        | 2      | 5.56%   |
| PNY                 | 2        | 2      | 5.56%   |
| Toshiba             | 1        | 1      | 2.78%   |
| Micro Center        | 1        | 1      | 2.78%   |
| Intel               | 1        | 1      | 2.78%   |
| Gigabyte Technology | 1        | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 74       | 129    | 61.67%  |
| SSD     | 33       | 49     | 27.5%   |
| NVMe    | 11       | 21     | 9.17%   |
| Unknown | 2        | 2      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 87       | 179    | 87.88%  |
| NVMe | 11       | 21     | 11.11%  |
| SAS  | 1        | 1      | 1.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 60       | 98     | 52.17%  |
| 0.51-1.0   | 37       | 52     | 32.17%  |
| 1.01-2.0   | 13       | 19     | 11.3%   |
| 3.01-4.0   | 3        | 6      | 2.61%   |
| 2.01-3.0   | 2        | 3      | 1.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 24       | 24.24%  |
| 501-1000       | 20       | 20.2%   |
| 101-250        | 15       | 15.15%  |
| 1001-2000      | 12       | 12.12%  |
| 1-20           | 10       | 10.1%   |
| More than 3000 | 8        | 8.08%   |
| 51-100         | 4        | 4.04%   |
| Unknown        | 3        | 3.03%   |
| 21-50          | 2        | 2.02%   |
| 2001-3000      | 1        | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 33       | 31.73%  |
| 21-50          | 19       | 18.27%  |
| 251-500        | 12       | 11.54%  |
| 51-100         | 11       | 10.58%  |
| 101-250        | 9        | 8.65%   |
| 501-1000       | 8        | 7.69%   |
| 1001-2000      | 5        | 4.81%   |
| More than 3000 | 3        | 2.88%   |
| Unknown        | 3        | 2.88%   |
| 2001-3000      | 1        | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Hitachi HDS721050CLA660 500GB     | 3        | 3      | 12.5%   |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 2      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 3      | 8.33%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 4.17%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 4.17%   |
| WDC WD1200BEVS-22UST0 120GB       | 1        | 1      | 4.17%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 4.17%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 1      | 4.17%   |
| Toshiba MK7559GSXP 752GB          | 1        | 1      | 4.17%   |
| Toshiba DT01ACA300 3TB            | 1        | 2      | 4.17%   |
| Seagate ST3750330AS 752GB         | 1        | 1      | 4.17%   |
| Seagate ST3500630AS 500GB         | 1        | 1      | 4.17%   |
| Seagate ST31000333AS 1TB          | 1        | 2      | 4.17%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 4.17%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2      | 4.17%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 4.17%   |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 4.17%   |
| Kingston SNS4151S316GD 16GB SSD   | 1        | 1      | 4.17%   |
| HPE MB0500EAMZD 500GB             | 1        | 1      | 4.17%   |
| Fujitsu MHZ2160BH G1 160GB        | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 10     | 30.43%  |
| WDC                 | 6        | 7      | 26.09%  |
| Hitachi             | 3        | 3      | 13.04%  |
| Toshiba             | 2        | 3      | 8.7%    |
| Samsung Electronics | 2        | 2      | 8.7%    |
| Kingston            | 1        | 1      | 4.35%   |
| HPE                 | 1        | 1      | 4.35%   |
| Fujitsu             | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 10     | 31.82%  |
| WDC                 | 6        | 7      | 27.27%  |
| Hitachi             | 3        | 3      | 13.64%  |
| Toshiba             | 2        | 3      | 9.09%   |
| Samsung Electronics | 2        | 2      | 9.09%   |
| HPE                 | 1        | 1      | 4.55%   |
| Fujitsu             | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 27     | 94.12%  |
| SSD  | 1        | 1      | 5.88%   |

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
| Detected | 55       | 128    | 53.4%   |
| Works    | 31       | 45     | 30.1%   |
| Malfunc  | 17       | 28     | 16.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 67       | 59.29%  |
| AMD                         | 20       | 17.7%   |
| Kingston Technology Company | 6        | 5.31%   |
| Marvell Technology Group    | 4        | 3.54%   |
| JMicron Technology          | 3        | 2.65%   |
| ASMedia Technology          | 3        | 2.65%   |
| VIA Technologies            | 2        | 1.77%   |
| Samsung Electronics         | 2        | 1.77%   |
| Phison Electronics          | 2        | 1.77%   |
| Nvidia                      | 2        | 1.77%   |
| Broadcom / LSI              | 1        | 0.88%   |
| ADATA Technology            | 1        | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 7.75%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 6.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 4.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 4.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 3.52%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4        | 2.82%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 2.82%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 4        | 2.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 2.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 2.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.11%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.11%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 2        | 1.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.41%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.41%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.7%    |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.7%    |
| VIA Serial ATA Controller                                                               | 1        | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.7%    |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                                     | 1        | 0.7%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 0.7%    |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 0.7%    |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.7%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.7%    |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 0.7%    |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 68       | 62.39%  |
| IDE  | 22       | 20.18%  |
| NVMe | 11       | 10.09%  |
| RAID | 8        | 7.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 69       | 76.67%  |
| AMD    | 21       | 23.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 4.44%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 4.44%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3.33%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 3.33%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 2.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 2.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 2.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 2.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.22%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 2.22%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 2.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 2.22%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 2.22%   |
| AMD Athlon II X2 270 Processor              | 2        | 2.22%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.11%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.11%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.11%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.11%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 1.11%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.11%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.11%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.11%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 1.11%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.11%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.11%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.11%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.11%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.11%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.11%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.11%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.11%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.11%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.11%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.11%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.11%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.11%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 24       | 26.67%  |
| Intel Core i7           | 14       | 15.56%  |
| AMD Ryzen 5             | 11       | 12.22%  |
| Intel Pentium           | 7        | 7.78%   |
| Intel Core i3           | 7        | 7.78%   |
| Intel Core 2 Duo        | 4        | 4.44%   |
| Intel Celeron           | 4        | 4.44%   |
| Other                   | 3        | 3.33%   |
| AMD Ryzen 7             | 3        | 3.33%   |
| Intel Core 2 Quad       | 2        | 2.22%   |
| Intel Atom              | 2        | 2.22%   |
| AMD E1                  | 2        | 2.22%   |
| AMD Athlon II X2        | 2        | 2.22%   |
| Intel Xeon              | 1        | 1.11%   |
| Intel Pentium Dual-Core | 1        | 1.11%   |
| AMD Phenom II X6        | 1        | 1.11%   |
| AMD Phenom II X2        | 1        | 1.11%   |
| AMD Athlon II Neo       | 1        | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 46.67%  |
| 2      | 28       | 31.11%  |
| 6      | 14       | 15.56%  |
| 8      | 4        | 4.44%   |
| 24     | 1        | 1.11%   |
| 14     | 1        | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 90       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 56.67%  |
| 2      | 39       | 43.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 89       | 98.89%  |
| Unknown        | 1        | 1.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 28.42%  |
| 0x306c3    | 10       | 10.53%  |
| 0x306a9    | 8        | 8.42%   |
| 0xa0653    | 5        | 5.26%   |
| 0x206a7    | 5        | 5.26%   |
| 0x1067a    | 5        | 5.26%   |
| 0x010000c8 | 3        | 3.16%   |
| 0x906ed    | 2        | 2.11%   |
| 0x106e5    | 2        | 2.11%   |
| 0x0a201005 | 2        | 2.11%   |
| 0x08701021 | 2        | 2.11%   |
| 0x0810100b | 2        | 2.11%   |
| 0xb06f2    | 1        | 1.05%   |
| 0x906ec    | 1        | 1.05%   |
| 0x906ea    | 1        | 1.05%   |
| 0x906e9    | 1        | 1.05%   |
| 0x90675    | 1        | 1.05%   |
| 0x706a1    | 1        | 1.05%   |
| 0x6fd      | 1        | 1.05%   |
| 0x506e3    | 1        | 1.05%   |
| 0x40651    | 1        | 1.05%   |
| 0x206c2    | 1        | 1.05%   |
| 0x106ca    | 1        | 1.05%   |
| 0x106c2    | 1        | 1.05%   |
| 0x106a5    | 1        | 1.05%   |
| 0x10676    | 1        | 1.05%   |
| 0x0a601203 | 1        | 1.05%   |
| 0x0a50000d | 1        | 1.05%   |
| 0x0a201204 | 1        | 1.05%   |
| 0x08701013 | 1        | 1.05%   |
| 0x08101016 | 1        | 1.05%   |
| 0x08101004 | 1        | 1.05%   |
| 0x0700010f | 1        | 1.05%   |
| 0x010000bf | 1        | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 16       | 17.58%  |
| IvyBridge        | 12       | 13.19%  |
| Penryn           | 7        | 7.69%   |
| KabyLake         | 6        | 6.59%   |
| CometLake        | 6        | 6.59%   |
| Zen 3            | 5        | 5.49%   |
| Skylake          | 5        | 5.49%   |
| SandyBridge      | 5        | 5.49%   |
| K10              | 5        | 5.49%   |
| Zen 2            | 4        | 4.4%    |
| Zen              | 3        | 3.3%    |
| Nehalem          | 3        | 3.3%    |
| Alderlake Hybrid | 3        | 3.3%    |
| Westmere         | 2        | 2.2%    |
| Bonnell          | 2        | 2.2%    |
| Unknown          | 2        | 2.2%    |
| Zen+             | 1        | 1.1%    |
| Jaguar           | 1        | 1.1%    |
| Goldmont plus    | 1        | 1.1%    |
| Core             | 1        | 1.1%    |
| Bobcat           | 1        | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 48       | 48.98%  |
| Nvidia           | 27       | 27.55%  |
| AMD              | 22       | 22.45%  |
| VIA Technologies | 1        | 1.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 12.12%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 10.1%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 4.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.03%   |
| Intel HD Graphics 530                                                       | 3        | 3.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 3.03%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 2        | 2.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.02%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.02%   |
| Intel HD Graphics 630                                                       | 2        | 2.02%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.02%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 2.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.02%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.01%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.01%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.01%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.01%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.01%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.01%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.01%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.01%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.01%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.01%   |
| Nvidia G98 [Quadro NVS 420]                                                 | 1        | 1.01%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.01%   |
| Nvidia C79 [GeForce 9300]                                                   | 1        | 1.01%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.01%   |
| Intel HD Graphics 510                                                       | 1        | 1.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.01%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 1        | 1.01%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.01%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 42       | 45.16%  |
| 1 x Nvidia               | 24       | 25.81%  |
| 1 x AMD                  | 19       | 20.43%  |
| Intel + Nvidia           | 3        | 3.23%   |
| Intel + AMD              | 2        | 2.15%   |
| 2 x AMD                  | 1        | 1.08%   |
| 1 x VIA                  | 1        | 1.08%   |
| Intel + AMD + 1 x Nvidia | 1        | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 75.53%  |
| Proprietary | 18       | 19.15%  |
| Unknown     | 5        | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 58       | 59.18%  |
| 1.01-2.0   | 16       | 16.33%  |
| 0.51-1.0   | 6        | 6.12%   |
| 0.01-0.5   | 6        | 6.12%   |
| 7.01-8.0   | 4        | 4.08%   |
| 5.01-6.0   | 3        | 3.06%   |
| 8.01-16.0  | 3        | 3.06%   |
| 3.01-4.0   | 2        | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 29       | 33.72%  |
| Samsung Electronics  | 13       | 15.12%  |
| BenQ                 | 9        | 10.47%  |
| AOC                  | 9        | 10.47%  |
| Hewlett-Packard      | 7        | 8.14%   |
| LG Electronics       | 4        | 4.65%   |
| Dell                 | 3        | 3.49%   |
| KTC                  | 2        | 2.33%   |
| Acer                 | 2        | 2.33%   |
| Unknown (XXX)        | 1        | 1.16%   |
| TES                  | 1        | 1.16%   |
| Philips              | 1        | 1.16%   |
| NEC Computers        | 1        | 1.16%   |
| MStar                | 1        | 1.16%   |
| HIC                  | 1        | 1.16%   |
| DMT                  | 1        | 1.16%   |
| Ancor Communications | 1        | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 4        | 4.3%    |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 3        | 3.23%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3        | 3.23%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3        | 3.23%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch    | 2        | 2.15%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2        | 2.15%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2        | 2.15%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 2        | 2.15%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 2        | 2.15%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 2        | 2.15%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 2        | 2.15%   |
| BenQ GL930A BNQ7870 1366x768 410x230mm 18.5-inch                     | 2        | 2.15%   |
| AOC 2251w AOC2251 1920x1080 477x268mm 21.5-inch                      | 2        | 2.15%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.08%   |
| TES TE-2123S TES2253 1920x1080 480x260mm 21.5-inch                   | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch  | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM0027 1280x1024 312x234mm 15.4-inch | 1        | 1.08%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.08%   |
| Samsung Electronics S24E650 SAM0CB4 1920x1080 521x293mm 23.5-inch    | 1        | 1.08%   |
| Samsung Electronics S24E650 SAM0CB3 1920x1080 521x293mm 23.5-inch    | 1        | 1.08%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SMB1930N 1366x768                    | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM7048 1366x768 522x293mm 23.6-inch | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 1.08%   |
| Philips LCD Monitor PHL BDM4065 3840x2160                            | 1        | 1.08%   |
| NEC Computers LCD1850E NEC65D1 1280x1024 359x287mm 18.1-inch         | 1        | 1.08%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 1        | 1.08%   |
| LG Electronics LCD Monitor W2043 3520x1080                           | 1        | 1.08%   |
| LG Electronics LCD Monitor 2D HD LG TV                               | 1        | 1.08%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.08%   |
| KTC 32'TV KTC3200 1360x768 708x398mm 32.0-inch                       | 1        | 1.08%   |
| KTC 22L13A-H-AN KTC2154 1920x1080 476x268mm 21.5-inch                | 1        | 1.08%   |
| HIC LCD Monitor HIC0001 1920x1080 256x192mm 12.6-inch                | 1        | 1.08%   |
| Hewlett-Packard w1858 HWP2835 1366x768 413x234mm 18.7-inch           | 1        | 1.08%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 1        | 1.08%   |
| Hewlett-Packard TouchSmart HWP4000 1920x1080 708x398mm 32.0-inch     | 1        | 1.08%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.08%   |
| Hewlett-Packard LCD Monitor L1710 2646x1024                          | 1        | 1.08%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch          | 1        | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 27.59%  |
| 1366x768 (WXGA)    | 24       | 27.59%  |
| 1440x900 (WXGA+)   | 8        | 9.2%    |
| 1600x900 (HD+)     | 7        | 8.05%   |
| 1360x768           | 7        | 8.05%   |
| 1024x768 (XGA)     | 4        | 4.6%    |
| 3840x2160 (4K)     | 3        | 3.45%   |
| 1280x1024 (SXGA)   | 3        | 3.45%   |
| Unknown            | 2        | 2.3%    |
| 4093x4093          | 1        | 1.15%   |
| 3520x1080          | 1        | 1.15%   |
| 2646x1024          | 1        | 1.15%   |
| 2560x1440 (QHD)    | 1        | 1.15%   |
| 1680x1050 (WSXGA+) | 1        | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 26       | 29.55%  |
| 19      | 12       | 13.64%  |
| 23      | 10       | 11.36%  |
| 21      | 10       | 11.36%  |
| Unknown | 9        | 10.23%  |
| 15      | 6        | 6.82%   |
| 20      | 4        | 4.55%   |
| 32      | 3        | 3.41%   |
| 24      | 3        | 3.41%   |
| 54      | 1        | 1.14%   |
| 52      | 1        | 1.14%   |
| 31      | 1        | 1.14%   |
| 17      | 1        | 1.14%   |
| 12      | 1        | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 47       | 54.65%  |
| 501-600     | 13       | 15.12%  |
| Unknown     | 9        | 10.47%  |
| 301-350     | 6        | 6.98%   |
| 351-400     | 4        | 4.65%   |
| 701-800     | 3        | 3.49%   |
| 1001-1500   | 2        | 2.33%   |
| 601-700     | 1        | 1.16%   |
| 201-300     | 1        | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 56       | 67.47%  |
| 16/10   | 9        | 10.84%  |
| Unknown | 9        | 10.84%  |
| 4/3     | 6        | 7.23%   |
| 5/4     | 3        | 3.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 25       | 28.41%  |
| 151-200        | 22       | 25%     |
| 201-250        | 17       | 19.32%  |
| Unknown        | 9        | 10.23%  |
| 101-110        | 5        | 5.68%   |
| 351-500        | 4        | 4.55%   |
| More than 1000 | 2        | 2.27%   |
| 71-80          | 1        | 1.14%   |
| 251-300        | 1        | 1.14%   |
| 131-140        | 1        | 1.14%   |
| 111-120        | 1        | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 61       | 70.93%  |
| 101-120 | 11       | 12.79%  |
| Unknown | 9        | 10.47%  |
| 1-50    | 3        | 3.49%   |
| 161-240 | 1        | 1.16%   |
| 121-160 | 1        | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 77       | 82.8%   |
| 2     | 11       | 11.83%  |
| 0     | 5        | 5.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 63       | 50.81%  |
| Intel                           | 25       | 20.16%  |
| Qualcomm Atheros                | 9        | 7.26%   |
| Ralink Technology               | 7        | 5.65%   |
| TP-Link                         | 5        | 4.03%   |
| Ralink                          | 3        | 2.42%   |
| Qualcomm Atheros Communications | 2        | 1.61%   |
| D-Link System                   | 2        | 1.61%   |
| Broadcom                        | 2        | 1.61%   |
| Xiaomi                          | 1        | 0.81%   |
| VIA Technologies                | 1        | 0.81%   |
| TRENDnet                        | 1        | 0.81%   |
| Samsung Electronics             | 1        | 0.81%   |
| Nvidia                          | 1        | 0.81%   |
| Arduino SA                      | 1        | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 46       | 34.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 7        | 5.19%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 5        | 3.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 3        | 2.22%   |
| Intel Ethernet Connection I217-LM                                                             | 3        | 2.22%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 2.22%   |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 2.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 2        | 1.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.48%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 1.48%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 1.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 1.48%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2        | 1.48%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 2        | 1.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1        | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.74%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS]             | 1        | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.74%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 0.74%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.74%   |
| TP-Link 802.11n NIC                                                                           | 1        | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 1        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 0.74%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 1        | 0.74%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.74%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.74%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 0.74%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 0.74%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                                     | 1        | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 27.78%  |
| Ralink Technology               | 7        | 19.44%  |
| TP-Link                         | 5        | 13.89%  |
| Intel                           | 5        | 13.89%  |
| Ralink                          | 3        | 8.33%   |
| Qualcomm Atheros                | 3        | 8.33%   |
| Qualcomm Atheros Communications | 2        | 5.56%   |
| TRENDnet                        | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 8.33%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 8.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 5.56%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 5.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 5.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 5.56%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS]             | 1        | 2.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 2.78%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 2.78%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 2.78%   |
| TP-Link 802.11n NIC                                                                           | 1        | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 2.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 2.78%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.78%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.78%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 2.78%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 2.78%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                                     | 1        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 2.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 1        | 2.78%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                             | 1        | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 60       | 63.16%  |
| Intel                 | 22       | 23.16%  |
| Qualcomm Atheros      | 6        | 6.32%   |
| D-Link System         | 2        | 2.11%   |
| Broadcom              | 2        | 2.11%   |
| Xiaomi                | 1        | 1.05%   |
| VIA Technologies      | 1        | 1.05%   |
| Nvidia                | 1        | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46       | 47.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7        | 7.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 5.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3        | 3.09%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 3.09%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 3.09%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 3.09%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 2.06%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 2.06%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.03%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 1.03%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1        | 1.03%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.03%   |
| Intel Ethernet Controller I225-V                                       | 1        | 1.03%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 1.03%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 1.03%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.03%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 1.03%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 1.03%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.03%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                       | 1        | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 71.43%  |
| WiFi     | 34       | 26.98%  |
| Modem    | 2        | 1.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 72       | 79.12%  |
| WiFi     | 19       | 20.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 79.12%  |
| 2     | 17       | 18.68%  |
| 3     | 2        | 2.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 80%     |
| Yes  | 19       | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 45%     |
| Intel                   | 5        | 25%     |
| TP-Link                 | 1        | 5%      |
| Realtek Semiconductor   | 1        | 5%      |
| IMC Networks            | 1        | 5%      |
| D-Link System           | 1        | 5%      |
| Broadcom                | 1        | 5%      |
| ASUSTek Computer        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 45%     |
| Intel AX211 Bluetooth                               | 2        | 10%     |
| Intel AX201 Bluetooth                               | 2        | 10%     |
| TP-Link TP-Link Bluetooth USB Adapter               | 1        | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| IMC Networks Bluetooth Device                       | 1        | 5%      |
| D-Link System DBT-122 Bluetooth                     | 1        | 5%      |
| Broadcom HP Bluetooth Module                        | 1        | 5%      |
| ASUS ASUS USB-BT500                                 | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 68       | 54.84%  |
| AMD                 | 27       | 21.77%  |
| Nvidia              | 25       | 20.16%  |
| VIA Technologies    | 1        | 0.81%   |
| Sony                | 1        | 0.81%   |
| M-Audio             | 1        | 0.81%   |
| Kingston Technology | 1        | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 8.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 8.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 7.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 4.64%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 7        | 4.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 3.97%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 2.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.99%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.99%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 1.99%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.32%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.32%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.66%   |
| Sony Audio                                                                 | 1        | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.66%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.66%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.66%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 17       | 33.33%  |
| Unknown             | 9        | 17.65%  |
| Corsair             | 8        | 15.69%  |
| Samsung Electronics | 3        | 5.88%   |
| A-DATA Technology   | 3        | 5.88%   |
| Micron Technology   | 2        | 3.92%   |
| Crucial             | 2        | 3.92%   |
| Avant               | 2        | 3.92%   |
| Team                | 1        | 1.96%   |
| PNY                 | 1        | 1.96%   |
| Hewlett-Packard     | 1        | 1.96%   |
| Gold Key            | 1        | 1.96%   |
| Unknown             | 1        | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 3.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 1.75%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM DDR2                    | 1        | 1.75%   |
| Unknown RAM Module 1GB DIMM DDR2                       | 1        | 1.75%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                | 1        | 1.75%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 1        | 1.75%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 1.75%   |
| Samsung RAM Module 4GB DIMM DDR4 3200MT/s              | 1        | 1.75%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.75%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 1        | 1.75%   |
| PNY RAM Module 4096MB DIMM DDR3 1333MT/s               | 1        | 1.75%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s            | 1        | 1.75%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s         | 1        | 1.75%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s           | 1        | 1.75%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 1        | 1.75%   |
| Kingston RAM KHX3000C16D4/16GX 16GB DIMM DDR4 3000MT/s | 1        | 1.75%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 1        | 1.75%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s    | 1        | 1.75%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 1        | 1.75%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 1        | 1.75%   |
| Kingston RAM KF552C40-32 32GB DIMM DDR5 5200MT/s       | 1        | 1.75%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s   | 1        | 1.75%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5471-038.A00LF 8GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 99U5403-034.A00G 4GB DIMM DDR3 1333MT/s   | 1        | 1.75%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s  | 1        | 1.75%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 9905471-006.A01LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| Kingston RAM 9905402-171.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 1.75%   |
| HP RAM 7EH55AA# 8GB DIMM DDR4 2666MT/s                 | 1        | 1.75%   |
| Gold Key RAM NMUD440D82-3200D 4GB DIMM DDR4 3200MT/s   | 1        | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 17       | 38.64%  |
| DDR3    | 16       | 36.36%  |
| DDR2    | 4        | 9.09%   |
| Unknown | 3        | 6.82%   |
| SDRAM   | 2        | 4.55%   |
| DDR5    | 2        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 42       | 97.67%  |
| SODIMM | 1        | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 16       | 32%     |
| 8192  | 14       | 28%     |
| 2048  | 8        | 16%     |
| 16384 | 7        | 14%     |
| 32768 | 3        | 6%      |
| 1024  | 2        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 13       | 24.53%  |
| 1600    | 9        | 16.98%  |
| 3200    | 5        | 9.43%   |
| 2133    | 4        | 7.55%   |
| 2667    | 3        | 5.66%   |
| Unknown | 3        | 5.66%   |
| 3733    | 2        | 3.77%   |
| 3600    | 2        | 3.77%   |
| 3466    | 2        | 3.77%   |
| 6000    | 1        | 1.89%   |
| 5200    | 1        | 1.89%   |
| 3933    | 1        | 1.89%   |
| 3534    | 1        | 1.89%   |
| 3400    | 1        | 1.89%   |
| 3000    | 1        | 1.89%   |
| 2666    | 1        | 1.89%   |
| 1866    | 1        | 1.89%   |
| 800     | 1        | 1.89%   |
| 667     | 1        | 1.89%   |

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
| Microdia                    | 4        | 14.29%  |
| Logitech                    | 3        | 10.71%  |
| KYE Systems (Mouse Systems) | 3        | 10.71%  |
| Pixart Imaging              | 2        | 7.14%   |
| Microsoft                   | 2        | 7.14%   |
| Jieli Technology            | 2        | 7.14%   |
| Generalplus Technology      | 2        | 7.14%   |
| Chicony Electronics         | 2        | 7.14%   |
| Unknown                     | 1        | 3.57%   |
| Novatek Microelectronics    | 1        | 3.57%   |
| MacroSilicon                | 1        | 3.57%   |
| IMC Networks                | 1        | 3.57%   |
| Genesys Logic               | 1        | 3.57%   |
| GEMBIRD                     | 1        | 3.57%   |
| eMeet                       | 1        | 3.57%   |
| Arkmicro Technologies       | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 3        | 10.71%  |
| Microsoft LifeCam VX-5000                  | 2        | 7.14%   |
| Microdia Camera                            | 2        | 7.14%   |
| Jieli USB PHY 2.0                          | 2        | 7.14%   |
| Unknown HD camera                          | 1        | 3.57%   |
| Pixart Imaging Webcam Genius iLook 300     | 1        | 3.57%   |
| Pixart Imaging Multimedia audio controller | 1        | 3.57%   |
| Novatek J1455                              | 1        | 3.57%   |
| Microdia Webcam Vitade AF                  | 1        | 3.57%   |
| Microdia Sonix USB 2.0 Camera              | 1        | 3.57%   |
| MacroSilicon USB Video                     | 1        | 3.57%   |
| KYE Systems (Mouse Systems) WideCam 1050   | 1        | 3.57%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 3.57%   |
| KYE Systems (Mouse Systems) FaceCam 310    | 1        | 3.57%   |
| IMC Networks HD Camera                     | 1        | 3.57%   |
| Genesys Logic USB2.0 UVC PC Camera         | 1        | 3.57%   |
| Generalplus GENERAL WEBCAM                 | 1        | 3.57%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 1        | 3.57%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 3.57%   |
| eMeet HD Webcam eMeet C970                 | 1        | 3.57%   |
| Chicony HP High Definition 1MP Webcam      | 1        | 3.57%   |
| Chicony CNF8050 Webcam                     | 1        | 3.57%   |
| Arkmicro USB2.0 PC CAMERA                  | 1        | 3.57%   |

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
| 0     | 78       | 83.87%  |
| 1     | 13       | 13.98%  |
| 2     | 2        | 2.15%   |

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


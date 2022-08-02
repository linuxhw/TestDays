Linux in Saudi Arabia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

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

Total: 146

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MPG X570 GAMING PLUS        | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Dell          | 0VD92X A00                  | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Dell          | 0VD92X A00                  | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| MSI           | B250M BAZOOKA               | [870c420b4b](https://linux-hardware.org/?probe=870c420b4b) | Jun 04, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [d7d06bf7ef](https://linux-hardware.org/?probe=d7d06bf7ef) | May 26, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| Dell          | 0M9KCM A01                  | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| Unknown       | HX90                        | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| Unknown       | HX90                        | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| Dell          | 0VD92X A00                  | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [bc999f46f9](https://linux-hardware.org/?probe=bc999f46f9) | Mar 28, 2022 |
| Dell          | 0VD92X A00                  | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| Gigabyte      | B75M-HD3                    | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Dell          | 0VD92X A00                  | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| Dell          | 0WWJRX A00                  | [bb620cc0f9](https://linux-hardware.org/?probe=bb620cc0f9) | Feb 26, 2022 |
| Gigabyte      | MJPLNAB-00                  | [007ec5dbf5](https://linux-hardware.org/?probe=007ec5dbf5) | Feb 24, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| ASRock        | B365M Phantom Gaming 4      | [9dd59e5403](https://linux-hardware.org/?probe=9dd59e5403) | Feb 08, 2022 |
| Dell          | 09M8Y8 A01                  | [e0748343d9](https://linux-hardware.org/?probe=e0748343d9) | Feb 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [92f528e80b](https://linux-hardware.org/?probe=92f528e80b) | Jan 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| HP            | 8906 SMVB                   | [be19f6df45](https://linux-hardware.org/?probe=be19f6df45) | Dec 29, 2021 |
| MSI           | MS-7529                     | [c9b87dcf45](https://linux-hardware.org/?probe=c9b87dcf45) | Dec 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [046dcdd20d](https://linux-hardware.org/?probe=046dcdd20d) | Dec 25, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [609baca194](https://linux-hardware.org/?probe=609baca194) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [35ec8b1dbb](https://linux-hardware.org/?probe=35ec8b1dbb) | Dec 16, 2021 |
| Gigabyte      | Z77-D3H                     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| Intel         | DP55WB AAE64798-206         | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Dell          | 0T656F A02                  | [a1abd4e08e](https://linux-hardware.org/?probe=a1abd4e08e) | Nov 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [a5026c4013](https://linux-hardware.org/?probe=a5026c4013) | Oct 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [65c4bea87a](https://linux-hardware.org/?probe=65c4bea87a) | Oct 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [d91c23c12c](https://linux-hardware.org/?probe=d91c23c12c) | Oct 08, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [b22e6dc21a](https://linux-hardware.org/?probe=b22e6dc21a) | Oct 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [428e41ed23](https://linux-hardware.org/?probe=428e41ed23) | Oct 05, 2021 |
| Dell          | 054KM3 A01                  | [6d277dcd36](https://linux-hardware.org/?probe=6d277dcd36) | Sep 18, 2021 |
| Gigabyte      | H81M-S2PH                   | [ef4fb4b996](https://linux-hardware.org/?probe=ef4fb4b996) | Aug 28, 2021 |
| Dell          | 0M9KCM A00                  | [162b090056](https://linux-hardware.org/?probe=162b090056) | Jul 14, 2021 |
| Dell          | 0M9KCM A00                  | [5bcc11cd03](https://linux-hardware.org/?probe=5bcc11cd03) | Jul 08, 2021 |
| Dell          | 0W0CHX A01                  | [e0a09aa1a5](https://linux-hardware.org/?probe=e0a09aa1a5) | Jul 01, 2021 |
| Dell          | 0XHGV1 A01                  | [4fcd4b7e98](https://linux-hardware.org/?probe=4fcd4b7e98) | Jun 22, 2021 |
| Intel         | BTC-T37                     | [6cd9eb4fd4](https://linux-hardware.org/?probe=6cd9eb4fd4) | Jun 19, 2021 |
| Intel         | BTC-T37                     | [3f0a790d81](https://linux-hardware.org/?probe=3f0a790d81) | Jun 19, 2021 |
| MSI           | Z77A-G43                    | [ea32add5cd](https://linux-hardware.org/?probe=ea32add5cd) | May 20, 2021 |
| Dell          | 042P49 A00                  | [f146c310d6](https://linux-hardware.org/?probe=f146c310d6) | May 18, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [34b2d651e1](https://linux-hardware.org/?probe=34b2d651e1) | Apr 28, 2021 |
| Gigabyte      | B75M-HD3                    | [82dd7f530a](https://linux-hardware.org/?probe=82dd7f530a) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | [f97ecb74c0](https://linux-hardware.org/?probe=f97ecb74c0) | Apr 09, 2021 |
| Dell          | 0XHGV1 A00                  | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| ASUSTek       | P6X58D PREMIUM              | [f568952b1d](https://linux-hardware.org/?probe=f568952b1d) | Mar 10, 2021 |
| Huanan        | X99-F8                      | [3bbee45dc4](https://linux-hardware.org/?probe=3bbee45dc4) | Mar 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c03aab940e](https://linux-hardware.org/?probe=c03aab940e) | Feb 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [66003aa802](https://linux-hardware.org/?probe=66003aa802) | Feb 28, 2021 |
| ASUSTek       | PRIME Z490-P                | [290dbb71c2](https://linux-hardware.org/?probe=290dbb71c2) | Feb 25, 2021 |
| HP            | 8591                        | [b6b7f6af35](https://linux-hardware.org/?probe=b6b7f6af35) | Feb 15, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [c8b28bb334](https://linux-hardware.org/?probe=c8b28bb334) | Feb 13, 2021 |
| Dell          | 0GY6Y8 A02                  | [5ed908976b](https://linux-hardware.org/?probe=5ed908976b) | Feb 09, 2021 |
| MSI           | B450M PRO-M2 V2             | [1d97b5c83d](https://linux-hardware.org/?probe=1d97b5c83d) | Jan 31, 2021 |
| MSI           | B450M PRO-M2 V2             | [5911afaa7a](https://linux-hardware.org/?probe=5911afaa7a) | Jan 27, 2021 |
| MSI           | B450M PRO-M2 V2             | [6bdd3b4a5d](https://linux-hardware.org/?probe=6bdd3b4a5d) | Jan 27, 2021 |
| Pegatron      | 2AD5                        | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2249011658](https://linux-hardware.org/?probe=2249011658) | Dec 30, 2020 |
| Dell          | 0GN6JF A01                  | [b4ea210c79](https://linux-hardware.org/?probe=b4ea210c79) | Dec 27, 2020 |
| OEM           | B250                        | [80af247c92](https://linux-hardware.org/?probe=80af247c92) | Dec 09, 2020 |
| HP            | 198E                        | [d6e4336d03](https://linux-hardware.org/?probe=d6e4336d03) | Dec 08, 2020 |
| ASRock        | X570 Steel Legend           | [6c1033e9f9](https://linux-hardware.org/?probe=6c1033e9f9) | Dec 04, 2020 |
| ASRock        | X570 Steel Legend           | [1e0a7199b7](https://linux-hardware.org/?probe=1e0a7199b7) | Dec 03, 2020 |
| HP            | 843C                        | [fd8c0fa877](https://linux-hardware.org/?probe=fd8c0fa877) | Nov 10, 2020 |
| OEM           | B250                        | [f6bcb7135c](https://linux-hardware.org/?probe=f6bcb7135c) | Nov 10, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e1c5dde63a](https://linux-hardware.org/?probe=e1c5dde63a) | Oct 12, 2020 |
| ASRock        | X470 Master SLI/ac          | [3ec057ab8d](https://linux-hardware.org/?probe=3ec057ab8d) | Sep 18, 2020 |
| ASRock        | Z270M Pro4                  | [ed0a963b78](https://linux-hardware.org/?probe=ed0a963b78) | Sep 05, 2020 |
| Gigabyte      | H81M-S2PH                   | [8634132c3a](https://linux-hardware.org/?probe=8634132c3a) | Aug 24, 2020 |
| Gigabyte      | H81M-S2PH                   | [54032f9ee7](https://linux-hardware.org/?probe=54032f9ee7) | Aug 19, 2020 |
| MSI           | Z370 KRAIT GAMING           | [c04081db17](https://linux-hardware.org/?probe=c04081db17) | Aug 07, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [fa825c1fce](https://linux-hardware.org/?probe=fa825c1fce) | Jul 26, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [3098a39bdb](https://linux-hardware.org/?probe=3098a39bdb) | Jul 26, 2020 |
| Unknown       | Unknown                     | [1c82bd39f0](https://linux-hardware.org/?probe=1c82bd39f0) | Jul 01, 2020 |
| Dell          | 0GN6JF A01                  | [452e0f2712](https://linux-hardware.org/?probe=452e0f2712) | Jun 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [6c1261f611](https://linux-hardware.org/?probe=6c1261f611) | Jun 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [eb4135b12e](https://linux-hardware.org/?probe=eb4135b12e) | Jun 07, 2020 |
| Pegatron      | 2A84h                       | [a5884bfb13](https://linux-hardware.org/?probe=a5884bfb13) | Jun 01, 2020 |
| Gigabyte      | H61M-S2P                    | [aecc9b0111](https://linux-hardware.org/?probe=aecc9b0111) | May 25, 2020 |
| Gigabyte      | B75M-HD3                    | [bedfc8fa0f](https://linux-hardware.org/?probe=bedfc8fa0f) | May 21, 2020 |
| Dell          | 0GY6Y8 A03                  | [874c2cb817](https://linux-hardware.org/?probe=874c2cb817) | May 20, 2020 |
| ASRock        | 990FX Extreme9              | [1947ac6d52](https://linux-hardware.org/?probe=1947ac6d52) | May 16, 2020 |
| ASRock        | 990FX Extreme9              | [dc7f6cc9e8](https://linux-hardware.org/?probe=dc7f6cc9e8) | May 16, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [48acf05b1b](https://linux-hardware.org/?probe=48acf05b1b) | Apr 23, 2020 |
| ASRock        | Z77 Extreme4                | [5aaf89e123](https://linux-hardware.org/?probe=5aaf89e123) | Feb 03, 2020 |
| Intel         | DP55WB AAE64798-206         | [bb1c5e0c3a](https://linux-hardware.org/?probe=bb1c5e0c3a) | Jan 01, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [0da4e7552a](https://linux-hardware.org/?probe=0da4e7552a) | Dec 29, 2019 |
| Intel         | DP55WB AAE64798-206         | [c137a7866b](https://linux-hardware.org/?probe=c137a7866b) | Dec 14, 2019 |
| MSI           | 2A78h                       | [83e806e50e](https://linux-hardware.org/?probe=83e806e50e) | Oct 25, 2019 |
| MSI           | 2A78h                       | [b5679811c8](https://linux-hardware.org/?probe=b5679811c8) | Oct 25, 2019 |
| MSI           | B360M GAMING PLUS           | [f54aa10fcc](https://linux-hardware.org/?probe=f54aa10fcc) | Oct 24, 2019 |
| MSI           | B360M GAMING PLUS           | [96ee6c9f88](https://linux-hardware.org/?probe=96ee6c9f88) | Oct 24, 2019 |
| ASUSTek       | SABERTOOTH Z97 MARK 2/US... | [4976e1673d](https://linux-hardware.org/?probe=4976e1673d) | Oct 01, 2019 |
| Dell          | 0HN7XN A01                  | [b9dd067151](https://linux-hardware.org/?probe=b9dd067151) | Aug 18, 2019 |
| Dell          | 0HN7XN A01                  | [67161826ca](https://linux-hardware.org/?probe=67161826ca) | Aug 18, 2019 |
| Intel         | DP55WB AAE64798-206         | [0a1b8c3a29](https://linux-hardware.org/?probe=0a1b8c3a29) | Aug 17, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | [bc9f90fd94](https://linux-hardware.org/?probe=bc9f90fd94) | Jul 20, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | [a5dd292f0e](https://linux-hardware.org/?probe=a5dd292f0e) | Jul 20, 2019 |
| Intel         | DP55WB AAE64798-206         | [78b4fe060a](https://linux-hardware.org/?probe=78b4fe060a) | Jul 19, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [b3224eb5fc](https://linux-hardware.org/?probe=b3224eb5fc) | Jul 19, 2019 |
| Intel         | DP55WB AAE64798-206         | [f8b4fc087b](https://linux-hardware.org/?probe=f8b4fc087b) | Jul 13, 2019 |
| Dell          | 0PC5F7 A02                  | [d5c119cb28](https://linux-hardware.org/?probe=d5c119cb28) | Jun 04, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | [9a655727f9](https://linux-hardware.org/?probe=9a655727f9) | Jun 02, 2019 |
| ASUSTek       | Z97-A                       | [5bca621b29](https://linux-hardware.org/?probe=5bca621b29) | May 31, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [14b4f17a8a](https://linux-hardware.org/?probe=14b4f17a8a) | Apr 22, 2019 |
| Dell          | 0C27VV A03                  | [4a17c281b7](https://linux-hardware.org/?probe=4a17c281b7) | Apr 05, 2019 |
| Gigabyte      | B360N WIFI-CF               | [8366ef739b](https://linux-hardware.org/?probe=8366ef739b) | Jan 19, 2019 |
| Gigabyte      | B360N WIFI-CF               | [8c5dcea151](https://linux-hardware.org/?probe=8c5dcea151) | Jan 07, 2019 |
| Gigabyte      | B360N WIFI-CF               | [f238cfd7d7](https://linux-hardware.org/?probe=f238cfd7d7) | Jan 07, 2019 |
| Lenovo        | NOK                         | [2761f888c3](https://linux-hardware.org/?probe=2761f888c3) | Nov 16, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [3e2fa165a6](https://linux-hardware.org/?probe=3e2fa165a6) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [a7272b3797](https://linux-hardware.org/?probe=a7272b3797) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [9c149f8d89](https://linux-hardware.org/?probe=9c149f8d89) | Oct 28, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [5c682ba446](https://linux-hardware.org/?probe=5c682ba446) | Oct 26, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [28a72027c5](https://linux-hardware.org/?probe=28a72027c5) | Oct 25, 2018 |
| Gigabyte      | P35-DS3R                    | [2f8f1a592b](https://linux-hardware.org/?probe=2f8f1a592b) | Aug 14, 2018 |
| Gigabyte      | H81M-S2PH                   | [d9e3df518a](https://linux-hardware.org/?probe=d9e3df518a) | Dec 08, 2017 |
| Dell          | 0VNP2H A00                  | [68fa7ad805](https://linux-hardware.org/?probe=68fa7ad805) | Nov 25, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 10       | 10.87%  |
| Ubuntu 18.04        | 7        | 7.61%   |
| Pop!_OS 21.10       | 4        | 4.35%   |
| OpenMandriva 4.3    | 4        | 4.35%   |
| OpenMandriva 4.2    | 4        | 4.35%   |
| Manjaro             | 4        | 4.35%   |
| Debian 10           | 4        | 4.35%   |
| Ubuntu 22.04        | 3        | 3.26%   |
| Ubuntu 19.10        | 3        | 3.26%   |
| ROSA R10            | 3        | 3.26%   |
| Ubuntu 21.10        | 2        | 2.17%   |
| Pop!_OS 21.04       | 2        | 2.17%   |
| Manjaro 20.2        | 2        | 2.17%   |
| Fedora 35           | 2        | 2.17%   |
| Endless 3.9.0       | 2        | 2.17%   |
| Arch                | 2        | 2.17%   |
| Zorin 15            | 1        | 1.09%   |
| Ubuntu Budgie 20.04 | 1        | 1.09%   |
| Ubuntu 19.04        | 1        | 1.09%   |
| Ubuntu 18.10        | 1        | 1.09%   |
| Ubuntu 16.04        | 1        | 1.09%   |
| Solus 4.3           | 1        | 1.09%   |
| ROSA R8             | 1        | 1.09%   |
| ROSA R11.1          | 1        | 1.09%   |
| Pop!_OS 22.04       | 1        | 1.09%   |
| Pop!_OS 20.10       | 1        | 1.09%   |
| Pear OS 20.04       | 1        | 1.09%   |
| Manjaro 21.1.6      | 1        | 1.09%   |
| Manjaro 21.0.3      | 1        | 1.09%   |
| Manjaro 20.0.3      | 1        | 1.09%   |
| Manjaro 18.0.4      | 1        | 1.09%   |
| Linux Mint 20.3     | 1        | 1.09%   |
| Kubuntu 20.04       | 1        | 1.09%   |
| Kubuntu 18.04       | 1        | 1.09%   |
| KDE neon 20.04      | 1        | 1.09%   |
| Kali 2022.2         | 1        | 1.09%   |
| Kali 2020.2         | 1        | 1.09%   |
| Fedora 36           | 1        | 1.09%   |
| Fedora 33           | 1        | 1.09%   |
| Fedora 32           | 1        | 1.09%   |
| Endless 3.8.1       | 1        | 1.09%   |
| Endless 3.5.4       | 1        | 1.09%   |
| Endless 3.4.8       | 1        | 1.09%   |
| EndeavourOS         | 1        | 1.09%   |
| Drauger OS 7.5.1    | 1        | 1.09%   |
| Debian Testing      | 1        | 1.09%   |
| Debian 11           | 1        | 1.09%   |
| Clear Linux 34170   | 1        | 1.09%   |
| CentOS 8            | 1        | 1.09%   |
| ArcoLinux Rolling   | 1        | 1.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 27       | 31.4%   |
| Manjaro       | 9        | 10.47%  |
| OpenMandriva  | 8        | 9.3%    |
| Pop!_OS       | 7        | 8.14%   |
| ROSA          | 5        | 5.81%   |
| Endless       | 5        | 5.81%   |
| Debian        | 5        | 5.81%   |
| Fedora        | 4        | 4.65%   |
| Kali          | 2        | 2.33%   |
| Arch          | 2        | 2.33%   |
| Zorin         | 1        | 1.16%   |
| Ubuntu Budgie | 1        | 1.16%   |
| Solus         | 1        | 1.16%   |
| Pear OS       | 1        | 1.16%   |
| Linux Mint    | 1        | 1.16%   |
| Kubuntu       | 1        | 1.16%   |
| KDE neon      | 1        | 1.16%   |
| EndeavourOS   | 1        | 1.16%   |
| Drauger OS    | 1        | 1.16%   |
| Clear Linux   | 1        | 1.16%   |
| CentOS        | 1        | 1.16%   |
| ArcoLinux     | 1        | 1.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003         | 4        | 3.92%   |
| 5.10.14-desktop-1omv4002        | 4        | 3.92%   |
| 5.13.0-37-generic               | 3        | 2.94%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 2.94%   |
| 5.9.11-3-MANJARO                | 2        | 1.96%   |
| 5.8.0-14-generic                | 2        | 1.96%   |
| 5.4.0-42-generic                | 2        | 1.96%   |
| 5.15.5-76051505-generic         | 2        | 1.96%   |
| 4.18.0-25-generic               | 2        | 1.96%   |
| 4.18.0-17-generic               | 2        | 1.96%   |
| 5.9.10-200.fc33.x86_64          | 1        | 0.98%   |
| 5.8.5-arch1-1                   | 1        | 0.98%   |
| 5.8.11-1-MANJARO                | 1        | 0.98%   |
| 5.8.0-7642-generic              | 1        | 0.98%   |
| 5.8.0-55-generic                | 1        | 0.98%   |
| 5.8.0-44-generic                | 1        | 0.98%   |
| 5.7.9-1-MANJARO                 | 1        | 0.98%   |
| 5.6.15-300.fc32.x86_64          | 1        | 0.98%   |
| 5.6.0-2-amd64                   | 1        | 0.98%   |
| 5.5.6-050506-generic            | 1        | 0.98%   |
| 5.5.0-kali2-amd64               | 1        | 0.98%   |
| 5.5.0-2-amd64                   | 1        | 0.98%   |
| 5.4.0-94-generic                | 1        | 0.98%   |
| 5.4.0-77-generic                | 1        | 0.98%   |
| 5.4.0-66-generic                | 1        | 0.98%   |
| 5.4.0-65-generic                | 1        | 0.98%   |
| 5.4.0-47-generic                | 1        | 0.98%   |
| 5.4.0-39-generic                | 1        | 0.98%   |
| 5.4.0-29-generic                | 1        | 0.98%   |
| 5.4.0-19-generic                | 1        | 0.98%   |
| 5.4.0-110-generic               | 1        | 0.98%   |
| 5.3.0-3-amd64                   | 1        | 0.98%   |
| 5.3.0-29-generic                | 1        | 0.98%   |
| 5.3.0-28-generic                | 1        | 0.98%   |
| 5.3.0-19-generic                | 1        | 0.98%   |
| 5.3.0-18-generic                | 1        | 0.98%   |
| 5.18.5-200.fc36.x86_64          | 1        | 0.98%   |
| 5.18.12-arch1-1                 | 1        | 0.98%   |
| 5.17.8-300.fc36.x86_64          | 1        | 0.98%   |
| 5.17.5-76051705-generic         | 1        | 0.98%   |
| 5.17.1-3-MANJARO                | 1        | 0.98%   |
| 5.16.20-200.fc35.x86_64         | 1        | 0.98%   |
| 5.16.19-76051619-generic        | 1        | 0.98%   |
| 5.16.11-arch1-1                 | 1        | 0.98%   |
| 5.16.11-200.fc35.x86_64         | 1        | 0.98%   |
| 5.16.0-kali7-amd64              | 1        | 0.98%   |
| 5.15.8-76051508-generic         | 1        | 0.98%   |
| 5.15.7-arch1-1                  | 1        | 0.98%   |
| 5.15.50-216.current             | 1        | 0.98%   |
| 5.15.32-213.current             | 1        | 0.98%   |
| 5.15.19-1-MANJARO               | 1        | 0.98%   |
| 5.15.15-76051515-generic        | 1        | 0.98%   |
| 5.15.0-37-generic               | 1        | 0.98%   |
| 5.15.0-27-generic               | 1        | 0.98%   |
| 5.15.0-23-generic               | 1        | 0.98%   |
| 5.15.0-11.1-liquorix-amd64      | 1        | 0.98%   |
| 5.14.21-210.current             | 1        | 0.98%   |
| 5.14.16-301.fc35.x86_64         | 1        | 0.98%   |
| 5.13.19-2-MANJARO               | 1        | 0.98%   |
| 5.13.0-7614-generic             | 1        | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11       | 11%     |
| 4.18.0  | 6        | 6%      |
| 5.8.0   | 5        | 5%      |
| 5.3.0   | 5        | 5%      |
| 5.13.0  | 5        | 5%      |
| 4.15.0  | 5        | 5%      |
| 5.16.7  | 4        | 4%      |
| 5.15.0  | 4        | 4%      |
| 5.11.0  | 4        | 4%      |
| 5.10.14 | 4        | 4%      |
| 4.9.60  | 3        | 3%      |
| 5.9.11  | 2        | 2%      |
| 5.5.0   | 2        | 2%      |
| 5.16.11 | 2        | 2%      |
| 5.15.5  | 2        | 2%      |
| 5.0.0   | 2        | 2%      |
| 4.19.0  | 2        | 2%      |
| 5.9.10  | 1        | 1%      |
| 5.8.5   | 1        | 1%      |
| 5.8.11  | 1        | 1%      |
| 5.7.9   | 1        | 1%      |
| 5.6.15  | 1        | 1%      |
| 5.6.0   | 1        | 1%      |
| 5.5.6   | 1        | 1%      |
| 5.18.5  | 1        | 1%      |
| 5.18.12 | 1        | 1%      |
| 5.17.8  | 1        | 1%      |
| 5.17.5  | 1        | 1%      |
| 5.17.1  | 1        | 1%      |
| 5.16.20 | 1        | 1%      |
| 5.16.19 | 1        | 1%      |
| 5.16.0  | 1        | 1%      |
| 5.15.8  | 1        | 1%      |
| 5.15.7  | 1        | 1%      |
| 5.15.50 | 1        | 1%      |
| 5.15.32 | 1        | 1%      |
| 5.15.19 | 1        | 1%      |
| 5.15.15 | 1        | 1%      |
| 5.14.21 | 1        | 1%      |
| 5.14.16 | 1        | 1%      |
| 5.13.19 | 1        | 1%      |
| 5.11.14 | 1        | 1%      |
| 5.10.7  | 1        | 1%      |
| 5.10.42 | 1        | 1%      |
| 5.10.11 | 1        | 1%      |
| 5.10.0  | 1        | 1%      |
| 4.9.155 | 1        | 1%      |
| 4.20.17 | 1        | 1%      |
| 4.1.25  | 1        | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 11       | 11.34%  |
| 5.15    | 11       | 11.34%  |
| 5.16    | 8        | 8.25%   |
| 5.10    | 8        | 8.25%   |
| 5.8     | 7        | 7.22%   |
| 4.18    | 6        | 6.19%   |
| 5.3     | 5        | 5.15%   |
| 5.13    | 5        | 5.15%   |
| 5.11    | 5        | 5.15%   |
| 4.15    | 5        | 5.15%   |
| 4.9     | 4        | 4.12%   |
| 5.9     | 3        | 3.09%   |
| 5.5     | 3        | 3.09%   |
| 5.17    | 3        | 3.09%   |
| 5.6     | 2        | 2.06%   |
| 5.18    | 2        | 2.06%   |
| 5.14    | 2        | 2.06%   |
| 5.0     | 2        | 2.06%   |
| 4.19    | 2        | 2.06%   |
| 5.7     | 1        | 1.03%   |
| 4.20    | 1        | 1.03%   |
| 4.1     | 1        | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 74       | 97.37%  |
| i686   | 2        | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 33       | 39.29%  |
| KDE5       | 19       | 22.62%  |
| Unknown    | 14       | 16.67%  |
| KDE        | 5        | 5.95%   |
| XFCE       | 4        | 4.76%   |
| KDE4       | 3        | 3.57%   |
| Budgie     | 2        | 2.38%   |
| X-Cinnamon | 1        | 1.19%   |
| Unity      | 1        | 1.19%   |
| Deepin     | 1        | 1.19%   |
| Cinnamon   | 1        | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 61       | 77.22%  |
| Unknown | 10       | 12.66%  |
| Wayland | 7        | 8.86%   |
| Tty     | 1        | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 56.98%  |
| SDDM    | 16       | 18.6%   |
| GDM3    | 7        | 8.14%   |
| GDM     | 5        | 5.81%   |
| TDM     | 3        | 3.49%   |
| LightDM | 3        | 3.49%   |
| KDM     | 3        | 3.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 49       | 59.04%  |
| Unknown | 18       | 21.69%  |
| ar_SA   | 7        | 8.43%   |
| en_GB   | 2        | 2.41%   |
| ar_EG   | 2        | 2.41%   |
| ar_AE   | 2        | 2.41%   |
| en_IL   | 1        | 1.2%    |
| en_AU   | 1        | 1.2%    |
| C       | 1        | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 49       | 61.25%  |
| EFI  | 31       | 38.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 60       | 75.95%  |
| Overlay | 6        | 7.59%   |
| Unknown | 6        | 7.59%   |
| Btrfs   | 5        | 6.33%   |
| Xfs     | 1        | 1.27%   |
| Ext2    | 1        | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 56       | 67.47%  |
| GPT     | 19       | 22.89%  |
| MBR     | 8        | 9.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 83.54%  |
| Yes       | 13       | 16.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 64.2%   |
| Yes       | 29       | 35.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 18       | 23.68%  |
| Gigabyte Technology | 12       | 15.79%  |
| ASUSTek Computer    | 11       | 14.47%  |
| MSI                 | 10       | 13.16%  |
| ASRock              | 8        | 10.53%  |
| Hewlett-Packard     | 4        | 5.26%   |
| Lenovo              | 3        | 3.95%   |
| Pegatron            | 2        | 2.63%   |
| Intel               | 2        | 2.63%   |
| Unknown             | 2        | 2.63%   |
| OEM                 | 1        | 1.32%   |
| Huanan              | 1        | 1.32%   |
| Fujitsu Siemens     | 1        | 1.32%   |
| Biostar             | 1        | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte H81M-S2PH                   | 2        | 2.63%   |
| Dell OptiPlex 9010                   | 2        | 2.63%   |
| Dell OptiPlex 7050                   | 2        | 2.63%   |
| Dell OptiPlex 7010                   | 2        | 2.63%   |
| ASUS All Series                      | 2        | 2.63%   |
| Unknown                              | 2        | 2.63%   |
| Pegatron h8-1400ex                   | 1        | 1.32%   |
| Pegatron Compaq dx7500 Microtower    | 1        | 1.32%   |
| OEM B250                             | 1        | 1.32%   |
| MSI MS-7C91                          | 1        | 1.32%   |
| MSI MS-7C90                          | 1        | 1.32%   |
| MSI MS-7C37                          | 1        | 1.32%   |
| MSI MS-7B84                          | 1        | 1.32%   |
| MSI MS-7B46                          | 1        | 1.32%   |
| MSI MS-7B19                          | 1        | 1.32%   |
| MSI MS-7A70                          | 1        | 1.32%   |
| MSI MS-7758                          | 1        | 1.32%   |
| MSI MS-7529                          | 1        | 1.32%   |
| MSI Compaq dx2390 Microtower         | 1        | 1.32%   |
| Lenovo ThinkCentre M93p 10A8S3C100   | 1        | 1.32%   |
| Lenovo ThinkCentre E73 10AS0040AX    | 1        | 1.32%   |
| Lenovo Legion T5 26IOB6 90RT00TVKS   | 1        | 1.32%   |
| Intel DP55WB AAE64798-206            | 1        | 1.32%   |
| Intel BTC-T37                        | 1        | 1.32%   |
| Huanan X99-F8                        | 1        | 1.32%   |
| HP ProDesk 400 G2 MT (TPM DP)        | 1        | 1.32%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 1.32%   |
| HP EliteDesk 800 G5 TWR              | 1        | 1.32%   |
| HP 290 G2 MT Business PC             | 1        | 1.32%   |
| Gigabyte Z97X-UD3H                   | 1        | 1.32%   |
| Gigabyte Z77-D3H                     | 1        | 1.32%   |
| Gigabyte Z390 I AORUS PRO WIFI       | 1        | 1.32%   |
| Gigabyte X570 AORUS MASTER           | 1        | 1.32%   |
| Gigabyte P35-DS3R                    | 1        | 1.32%   |
| Gigabyte H61M-S2P                    | 1        | 1.32%   |
| Gigabyte H110-D3A                    | 1        | 1.32%   |
| Gigabyte GB-BMPD-6005                | 1        | 1.32%   |
| Gigabyte B75M-HD3                    | 1        | 1.32%   |
| Gigabyte B360N WIFI                  | 1        | 1.32%   |
| Fujitsu Siemens ESPRIMO P            | 1        | 1.32%   |
| Dell Vostro 430                      | 1        | 1.32%   |
| Dell Vostro 3888                     | 1        | 1.32%   |
| Dell Precision T5600                 | 1        | 1.32%   |
| Dell Precision T3610                 | 1        | 1.32%   |
| Dell OptiPlex 990                    | 1        | 1.32%   |
| Dell OptiPlex 9020                   | 1        | 1.32%   |
| Dell OptiPlex 780                    | 1        | 1.32%   |
| Dell OptiPlex 5050                   | 1        | 1.32%   |
| Dell OptiPlex 380                    | 1        | 1.32%   |
| Dell OptiPlex 360                    | 1        | 1.32%   |
| Dell OptiPlex 3050                   | 1        | 1.32%   |
| Dell OptiPlex 3010                   | 1        | 1.32%   |
| Biostar P4M900-M7 FE                 | 1        | 1.32%   |
| ASUS Z170 PRO GAMING                 | 1        | 1.32%   |
| ASUS TUF Gaming Z690-PLUS WIFI D4    | 1        | 1.32%   |
| ASUS TUF Gaming X570-PLUS            | 1        | 1.32%   |
| ASUS ROG STRIX Z390-E GAMING         | 1        | 1.32%   |
| ASUS ROG STRIX B360-H GAMING         | 1        | 1.32%   |
| ASUS PRIME Z490-P                    | 1        | 1.32%   |
| ASUS PRIME X299-DELUXE               | 1        | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 14       | 18.42%  |
| Lenovo ThinkCentre      | 2        | 2.63%   |
| Gigabyte H81M-S2PH      | 2        | 2.63%   |
| Dell Vostro             | 2        | 2.63%   |
| Dell Precision          | 2        | 2.63%   |
| ASUS TUF                | 2        | 2.63%   |
| ASUS ROG                | 2        | 2.63%   |
| ASUS PRIME              | 2        | 2.63%   |
| ASUS All                | 2        | 2.63%   |
| ASRock X570             | 2        | 2.63%   |
| Unknown                 | 2        | 2.63%   |
| Pegatron h8-1400ex      | 1        | 1.32%   |
| Pegatron Compaq         | 1        | 1.32%   |
| OEM B250                | 1        | 1.32%   |
| MSI MS-7C91             | 1        | 1.32%   |
| MSI MS-7C90             | 1        | 1.32%   |
| MSI MS-7C37             | 1        | 1.32%   |
| MSI MS-7B84             | 1        | 1.32%   |
| MSI MS-7B46             | 1        | 1.32%   |
| MSI MS-7B19             | 1        | 1.32%   |
| MSI MS-7A70             | 1        | 1.32%   |
| MSI MS-7758             | 1        | 1.32%   |
| MSI MS-7529             | 1        | 1.32%   |
| MSI Compaq              | 1        | 1.32%   |
| Lenovo Legion           | 1        | 1.32%   |
| Intel DP55WB            | 1        | 1.32%   |
| Intel BTC-T37           | 1        | 1.32%   |
| Huanan X99-F8           | 1        | 1.32%   |
| HP ProDesk              | 1        | 1.32%   |
| HP Pavilion             | 1        | 1.32%   |
| HP EliteDesk            | 1        | 1.32%   |
| HP 290                  | 1        | 1.32%   |
| Gigabyte Z97X-UD3H      | 1        | 1.32%   |
| Gigabyte Z77-D3H        | 1        | 1.32%   |
| Gigabyte Z390           | 1        | 1.32%   |
| Gigabyte X570           | 1        | 1.32%   |
| Gigabyte P35-DS3R       | 1        | 1.32%   |
| Gigabyte H61M-S2P       | 1        | 1.32%   |
| Gigabyte H110-D3A       | 1        | 1.32%   |
| Gigabyte GB-BMPD-6005   | 1        | 1.32%   |
| Gigabyte B75M-HD3       | 1        | 1.32%   |
| Gigabyte B360N          | 1        | 1.32%   |
| Fujitsu Siemens ESPRIMO | 1        | 1.32%   |
| Biostar P4M900-M7       | 1        | 1.32%   |
| ASUS Z170               | 1        | 1.32%   |
| ASUS P6X58D             | 1        | 1.32%   |
| ASUS CROSSHAIR          | 1        | 1.32%   |
| ASRock Z77              | 1        | 1.32%   |
| ASRock Z270M            | 1        | 1.32%   |
| ASRock X470             | 1        | 1.32%   |
| ASRock H81              | 1        | 1.32%   |
| ASRock B365M            | 1        | 1.32%   |
| ASRock 990FX            | 1        | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 15.79%  |
| 2012 | 9        | 11.84%  |
| 2019 | 8        | 10.53%  |
| 2013 | 8        | 10.53%  |
| 2021 | 6        | 7.89%   |
| 2020 | 5        | 6.58%   |
| 2014 | 5        | 6.58%   |
| 2017 | 4        | 5.26%   |
| 2015 | 4        | 5.26%   |
| 2010 | 4        | 5.26%   |
| 2008 | 3        | 3.95%   |
| 2016 | 2        | 2.63%   |
| 2011 | 2        | 2.63%   |
| 2007 | 2        | 2.63%   |
| 2009 | 1        | 1.32%   |
| 2006 | 1        | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 76       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 74       | 97.37%  |
| Enabled  | 2        | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 18       | 22.78%  |
| 8.01-16.0   | 18       | 22.78%  |
| 4.01-8.0    | 13       | 16.46%  |
| 32.01-64.0  | 12       | 15.19%  |
| 3.01-4.0    | 7        | 8.86%   |
| 1.01-2.0    | 4        | 5.06%   |
| 64.01-256.0 | 3        | 3.8%    |
| 24.01-32.0  | 2        | 2.53%   |
| 2.01-3.0    | 1        | 1.27%   |
| 0.51-1.0    | 1        | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 28       | 31.11%  |
| 4.01-8.0   | 19       | 21.11%  |
| 2.01-3.0   | 16       | 17.78%  |
| 3.01-4.0   | 14       | 15.56%  |
| 0.51-1.0   | 7        | 7.78%   |
| 8.01-16.0  | 5        | 5.56%   |
| 16.01-24.0 | 1        | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 41.67%  |
| 3      | 18       | 21.43%  |
| 2      | 18       | 21.43%  |
| 4      | 5        | 5.95%   |
| 5      | 4        | 4.76%   |
| 6      | 3        | 3.57%   |
| 7      | 1        | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 59.49%  |
| Yes       | 32       | 40.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 58.44%  |
| No        | 32       | 41.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 56.96%  |
| Yes       | 34       | 43.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Saudi Arabia | 76       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Riyadh               | 35       | 42.17%  |
| Jeddah               | 20       | 24.1%   |
| Medina               | 8        | 9.64%   |
| Dammam               | 6        | 7.23%   |
| Khobar               | 4        | 4.82%   |
| Makkah               | 3        | 3.61%   |
| Al Qatif             | 3        | 3.61%   |
| Ta'if                | 1        | 1.2%    |
| Buraidah             | 1        | 1.2%    |
| Baq`a' ash Sharqiyah | 1        | 1.2%    |
| Al Faruq             | 1        | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 41       | 72     | 26.8%   |
| Seagate                   | 25       | 40     | 16.34%  |
| Kingston                  | 18       | 34     | 11.76%  |
| Samsung Electronics       | 14       | 24     | 9.15%   |
| Toshiba                   | 9        | 11     | 5.88%   |
| Crucial                   | 7        | 9      | 4.58%   |
| Silicon Motion            | 4        | 5      | 2.61%   |
| SanDisk                   | 4        | 4      | 2.61%   |
| Phison                    | 4        | 4      | 2.61%   |
| Hitachi                   | 4        | 5      | 2.61%   |
| Team                      | 3        | 3      | 1.96%   |
| Lexar                     | 3        | 3      | 1.96%   |
| Unknown                   | 2        | 3      | 1.31%   |
| Intel                     | 2        | 2      | 1.31%   |
| HGST                      | 2        | 5      | 1.31%   |
| WD MediaMax               | 1        | 1      | 0.65%   |
| SPCC Sol                  | 1        | 1      | 0.65%   |
| PNY                       | 1        | 1      | 0.65%   |
| Micron/Crucial Technology | 1        | 1      | 0.65%   |
| Maxtor                    | 1        | 1      | 0.65%   |
| JMicron Technology        | 1        | 1      | 0.65%   |
| HS-SSD-C100               | 1        | 2      | 0.65%   |
| Hoodisk                   | 1        | 1      | 0.65%   |
| Hewlett-Packard           | 1        | 1      | 0.65%   |
| China                     | 1        | 1      | 0.65%   |
| Unknown                   | 1        | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD   | 5        | 2.72%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 4        | 2.17%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 4        | 2.17%   |
| WDC WD10EZEX-75WN4A1 1TB          | 3        | 1.63%   |
| Seagate ST500DM002-1BD142 500GB   | 3        | 1.63%   |
| Kingston SA400S37960G 960GB SSD   | 3        | 1.63%   |
| Kingston SA400S37480G 480GB SSD   | 3        | 1.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 2        | 1.09%   |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 1.09%   |
| WDC WD10EADS-00M2B0 1TB           | 2        | 1.09%   |
| Toshiba MK1059GSM 1TB             | 2        | 1.09%   |
| Toshiba DT01ACA050 500GB          | 2        | 1.09%   |
| Silicon Motion NVMe SSD Drive 2TB | 2        | 1.09%   |
| Seagate ST2000LM007-1R8174 2TB    | 2        | 1.09%   |
| Seagate ST1000DM003-9YN162 1TB    | 2        | 1.09%   |
| Seagate ST1000DM003-1SB102 1TB    | 2        | 1.09%   |
| Samsung SSD 960 EVO 250GB         | 2        | 1.09%   |
| Samsung SSD 860 EVO 500GB         | 2        | 1.09%   |
| Samsung SSD 860 EVO 1TB           | 2        | 1.09%   |
| Samsung NVMe SSD Drive 500GB      | 2        | 1.09%   |
| Lexar 128GB SSD                   | 2        | 1.09%   |
| Hitachi HTS545050A7E380 500GB     | 2        | 1.09%   |
| Crucial CT500MX500SSD1 500GB      | 2        | 1.09%   |
| Crucial CT1000MX500SSD1 1TB       | 2        | 1.09%   |
| WDC WDS250G3X0C-00SJG0 250GB      | 1        | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.54%   |
| WDC WD800JD-00LSA0 80GB           | 1        | 0.54%   |
| WDC WD7500AAKS-00RBA0 752GB       | 1        | 0.54%   |
| WDC WD5000LPCX-00VHAT0 500GB      | 1        | 0.54%   |
| WDC WD5000AZRX-00A8LB0 500GB      | 1        | 0.54%   |
| WDC WD5000AZLX-75K2TA0 500GB      | 1        | 0.54%   |
| WDC WD5000AAKX-07U6AA0 500GB      | 1        | 0.54%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 0.54%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1        | 0.54%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 0.54%   |
| WDC WD5000AAKS-00TMA0 500GB       | 1        | 0.54%   |
| WDC WD40EZRZ-00G                  | 1        | 0.54%   |
| WDC WD40EMRX-82UZ0N0 4TB          | 1        | 0.54%   |
| WDC WD4005FZBX-00K5WB0 4TB        | 1        | 0.54%   |
| WDC WD3200AAKX-753CA1 320GB       | 1        | 0.54%   |
| WDC WD3200AAKS-75L9A0 320GB       | 1        | 0.54%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 0.54%   |
| WDC WD32 00AAJS-00L7A0 320GB      | 1        | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB          | 1        | 0.54%   |
| WDC WD2500JS-00MHB0 250GB         | 1        | 0.54%   |
| WDC WD2500HHTZ-04N21V1 250GB      | 1        | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 0.54%   |
| WDC WD20EURX-63T0FY0 2TB          | 1        | 0.54%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 0.54%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1        | 0.54%   |
| WDC WD2002FAEX-007BA0 2TB         | 1        | 0.54%   |
| WDC WD1600AAJS-60M0A0 160GB       | 1        | 0.54%   |
| WDC WD1600AAJS-60B4A0 160GB       | 1        | 0.54%   |
| WDC WD1600AABS-00PRA0 160GB       | 1        | 0.54%   |
| WDC WD15EADS-11P8B2 1TB           | 1        | 0.54%   |
| WDC WD10JPVX-08JC3T6 1TB          | 1        | 0.54%   |
| WDC WD10EZEX-60WN4A2 1TB          | 1        | 0.54%   |
| WDC WD10EURX-63UY4Y0 1TB          | 1        | 0.54%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 0.54%   |
| WDC WD10EARS-00MVWB0 1TB          | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 38       | 64     | 47.5%   |
| Seagate | 25       | 40     | 31.25%  |
| Toshiba | 9        | 11     | 11.25%  |
| Hitachi | 4        | 5      | 5%      |
| HGST    | 2        | 5      | 2.5%    |
| Unknown | 1        | 2      | 1.25%   |
| Maxtor  | 1        | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 17       | 32     | 36.17%  |
| Samsung Electronics | 8        | 15     | 17.02%  |
| Crucial             | 7        | 9      | 14.89%  |
| WDC                 | 3        | 6      | 6.38%   |
| Lexar               | 3        | 3      | 6.38%   |
| Team                | 2        | 2      | 4.26%   |
| SanDisk             | 2        | 2      | 4.26%   |
| SPCC Sol            | 1        | 1      | 2.13%   |
| PNY                 | 1        | 1      | 2.13%   |
| Hoodisk             | 1        | 1      | 2.13%   |
| China               | 1        | 1      | 2.13%   |
| Unknown             | 1        | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 58       | 128    | 47.54%  |
| SSD     | 40       | 74     | 32.79%  |
| NVMe    | 22       | 31     | 18.03%  |
| Unknown | 2        | 3      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 71       | 199    | 73.96%  |
| NVMe | 21       | 30     | 21.88%  |
| SAS  | 4        | 7      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 46       | 102    | 43.81%  |
| 0.51-1.0   | 36       | 65     | 34.29%  |
| 1.01-2.0   | 15       | 24     | 14.29%  |
| 3.01-4.0   | 5        | 5      | 4.76%   |
| 2.01-3.0   | 2        | 3      | 1.9%    |
| 4.01-10.0  | 1        | 3      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 22.62%  |
| 501-1000       | 17       | 20.24%  |
| 251-500        | 16       | 19.05%  |
| More than 3000 | 8        | 9.52%   |
| 1001-2000      | 8        | 9.52%   |
| 51-100         | 5        | 5.95%   |
| 2001-3000      | 4        | 4.76%   |
| 1-20           | 4        | 4.76%   |
| 21-50          | 2        | 2.38%   |
| Unknown        | 1        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 35       | 38.89%  |
| 21-50          | 16       | 17.78%  |
| 251-500        | 8        | 8.89%   |
| 501-1000       | 7        | 7.78%   |
| 101-250        | 6        | 6.67%   |
| 1001-2000      | 6        | 6.67%   |
| 51-100         | 6        | 6.67%   |
| More than 3000 | 3        | 3.33%   |
| 2001-3000      | 2        | 2.22%   |
| Unknown        | 1        | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00WWPA0 500GB    | 1        | 1      | 8.33%   |
| WDC WD3200AAJS-00L7A0 320GB     | 1        | 1      | 8.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 1      | 8.33%   |
| Seagate ST9320325AS 320GB       | 1        | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 8.33%   |
| Seagate ST2000DM001-1CH164 2TB  | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-9YN162 1TB  | 1        | 1      | 8.33%   |
| Kingston SA400S37480G 480GB SSD | 1        | 1      | 8.33%   |
| Hitachi HDS721032CLA362 320GB   | 1        | 1      | 8.33%   |
| Unknown                         | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 4        | 4      | 36.36%  |
| Seagate  | 4        | 5      | 36.36%  |
| Kingston | 1        | 1      | 9.09%   |
| Hitachi  | 1        | 1      | 9.09%   |
| Unknown  | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 44.44%  |
| Seagate | 4        | 5      | 44.44%  |
| Hitachi | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 10     | 77.78%  |
| SSD  | 2        | 2      | 22.22%  |

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
| Detected | 57       | 165    | 63.33%  |
| Works    | 25       | 59     | 27.78%  |
| Malfunc  | 8        | 12     | 8.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 62       | 58.49%  |
| AMD                         | 14       | 13.21%  |
| Samsung Electronics         | 7        | 6.6%    |
| Silicon Motion              | 5        | 4.72%   |
| Phison Electronics          | 4        | 3.77%   |
| ASMedia Technology          | 4        | 3.77%   |
| SanDisk                     | 3        | 2.83%   |
| Kingston Technology Company | 2        | 1.89%   |
| VIA Technologies            | 1        | 0.94%   |
| Micron/Crucial Technology   | 1        | 0.94%   |
| LSI Logic / Symbios Logic   | 1        | 0.94%   |
| JMicron Technology          | 1        | 0.94%   |
| ADATA Technology            | 1        | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 7.14%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 6.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 4.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 3.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 3.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 3.17%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 2.38%   |
| Phison E12 NVMe Controller                                                              | 3        | 2.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 2.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.59%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.59%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.59%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.79%   |
| VIA Serial ATA Controller                                                               | 1        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.79%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.79%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 0.79%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 0.79%   |
| Kingston Company HyperX Predator PCIe AHCI SSD                                          | 1        | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.79%   |
| Intel SSD 660P Series                                                                   | 1        | 0.79%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                                | 1        | 0.79%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.79%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.79%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.79%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.79%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.79%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 0.79%   |
| Intel 500 Series Chipset Family SATA RAID Controller                                    | 1        | 0.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 55.34%  |
| NVMe | 21       | 20.39%  |
| IDE  | 14       | 13.59%  |
| RAID | 11       | 10.68%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 63       | 82.89%  |
| AMD    | 13       | 17.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 6.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 3.9%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 2.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 2.6%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 2.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 2.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 2.6%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 2.6%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.6%    |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 2.6%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 2.6%    |
| AMD Ryzen 9 3950X 16-Core Processor         | 2        | 2.6%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 2.6%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 1.3%    |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1        | 1.3%    |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 1.3%    |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 1.3%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.3%    |
| Intel Pentium 4 CPU 3.60GHz                 | 1        | 1.3%    |
| Intel Core i9-7900X CPU @ 3.30GHz           | 1        | 1.3%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.3%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.3%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i7 CPU 965 @ 3.20GHz             | 1        | 1.3%    |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 1.3%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.3%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.3%    |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.3%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.3%    |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.3%    |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.3%    |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 1.3%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.3%    |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.3%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.3%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.3%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.3%    |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 1        | 1.3%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 1.3%    |
| Intel Core 2 CPU 4400 @ 2.00GHz             | 1        | 1.3%    |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 1.3%    |
| Intel Celeron CPU 807UE @ 1.00GHz           | 1        | 1.3%    |
| Intel Celeron CPU 440 @ 2.00GHz             | 1        | 1.3%    |
| Intel 12th Gen Core i5-12600                | 1        | 1.3%    |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 1        | 1.3%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.3%    |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1        | 1.3%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 1        | 1.3%    |
| AMD Ryzen 7 3800XT 8-Core Processor         | 1        | 1.3%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 1.3%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 1.3%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 1.3%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 1.3%    |
| AMD FX-8370 Eight-Core Processor            | 1        | 1.3%    |
| AMD FX-8350 Eight-Core Processor            | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 21       | 27.27%  |
| Intel Core i5           | 18       | 23.38%  |
| Intel Core i3           | 6        | 7.79%   |
| AMD Ryzen 5             | 5        | 6.49%   |
| Intel Core 2 Duo        | 4        | 5.19%   |
| AMD Ryzen 9             | 4        | 5.19%   |
| Intel Xeon              | 3        | 3.9%    |
| Intel Celeron           | 3        | 3.9%    |
| AMD Ryzen 7             | 3        | 3.9%    |
| Other                   | 2        | 2.6%    |
| AMD FX                  | 2        | 2.6%    |
| Intel Pentium Silver    | 1        | 1.3%    |
| Intel Pentium Dual-Core | 1        | 1.3%    |
| Intel Pentium 4         | 1        | 1.3%    |
| Intel Core i9           | 1        | 1.3%    |
| Intel Core 2 Quad       | 1        | 1.3%    |
| Intel Core 2            | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 40       | 51.95%  |
| 6      | 11       | 14.29%  |
| 2      | 9        | 11.69%  |
| 8      | 8        | 10.39%  |
| 1      | 3        | 3.9%    |
| 16     | 2        | 2.6%    |
| 12     | 2        | 2.6%    |
| 10     | 2        | 2.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 75       | 98.68%  |
| 2      | 1        | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 42       | 54.55%  |
| 1      | 35       | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 74       | 97.37%  |
| Unknown        | 2        | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 32.14%  |
| 0x306c3    | 10       | 11.9%   |
| 0x306a9    | 7        | 8.33%   |
| 0x906e9    | 5        | 5.95%   |
| 0x1067a    | 5        | 5.95%   |
| 0x206a7    | 4        | 4.76%   |
| 0x906ea    | 3        | 3.57%   |
| 0xa0653    | 2        | 2.38%   |
| 0x906ed    | 2        | 2.38%   |
| 0x08701021 | 2        | 2.38%   |
| 0xf64      | 1        | 1.19%   |
| 0x906ec    | 1        | 1.19%   |
| 0x906eb    | 1        | 1.19%   |
| 0x906c0    | 1        | 1.19%   |
| 0x6f2      | 1        | 1.19%   |
| 0x506e3    | 1        | 1.19%   |
| 0x506c9    | 1        | 1.19%   |
| 0x306f2    | 1        | 1.19%   |
| 0x306e4    | 1        | 1.19%   |
| 0x206d7    | 1        | 1.19%   |
| 0x106e5    | 1        | 1.19%   |
| 0x106a4    | 1        | 1.19%   |
| 0x10661    | 1        | 1.19%   |
| 0x0a201009 | 1        | 1.19%   |
| 0x08701013 | 1        | 1.19%   |
| 0x0800820d | 1        | 1.19%   |
| 0x06000852 | 1        | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 16       | 20.78%  |
| Haswell     | 11       | 14.29%  |
| IvyBridge   | 10       | 12.99%  |
| Penryn      | 6        | 7.79%   |
| Zen 3       | 5        | 6.49%   |
| SandyBridge | 5        | 6.49%   |
| Zen 2       | 4        | 5.19%   |
| Zen+        | 3        | 3.9%    |
| Skylake     | 3        | 3.9%    |
| Nehalem     | 3        | 3.9%    |
| Piledriver  | 2        | 2.6%    |
| Core        | 2        | 2.6%    |
| CometLake   | 2        | 2.6%    |
| Unknown     | 2        | 2.6%    |
| Tremont     | 1        | 1.3%    |
| NetBurst    | 1        | 1.3%    |
| Goldmont    | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 37       | 43.02%  |
| Intel            | 32       | 37.21%  |
| AMD              | 16       | 18.6%   |
| VIA Technologies | 1        | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.62%   |
| Intel HD Graphics 630                                                       | 5        | 5.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 4.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.49%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 3.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.37%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.25%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.25%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.25%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 2.25%   |
| AMD Cezanne                                                                 | 2        | 2.25%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.12%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.12%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.12%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.12%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.12%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.12%   |
| Nvidia GT200GL [Quadro FX 5800]                                             | 1        | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.12%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.12%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.12%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.12%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.12%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.12%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.12%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.12%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.12%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.12%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.12%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.12%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.12%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.12%   |
| Intel VGA compatible controller                                             | 1        | 1.12%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.12%   |
| Intel HD Graphics 530                                                       | 1        | 1.12%   |
| Intel HD Graphics 500                                                       | 1        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.12%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.12%   |
| AMD Turks PRO [Radeon HD 7570]                                              | 1        | 1.12%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 1.12%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.12%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 1.12%   |
| AMD RC410 [Radeon Xpress 200/1100]                                          | 1        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.12%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 1.12%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 1.12%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 34       | 44.74%  |
| 1 x Intel      | 23       | 30.26%  |
| 1 x AMD        | 11       | 14.47%  |
| Intel + AMD    | 3        | 3.95%   |
| Intel + Nvidia | 2        | 2.63%   |
| 2 x AMD        | 1        | 1.32%   |
| 1 x VIA        | 1        | 1.32%   |
| AMD + Nvidia   | 1        | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 51       | 63.75%  |
| Proprietary | 26       | 32.5%   |
| Unknown     | 3        | 3.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 48.19%  |
| 7.01-8.0   | 11       | 13.25%  |
| 1.01-2.0   | 10       | 12.05%  |
| 3.01-4.0   | 8        | 9.64%   |
| 0.51-1.0   | 4        | 4.82%   |
| 0.01-0.5   | 4        | 4.82%   |
| 8.01-16.0  | 3        | 3.61%   |
| 2.01-3.0   | 2        | 2.41%   |
| 5.01-6.0   | 1        | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 15       | 19.74%  |
| Samsung Electronics  | 13       | 17.11%  |
| BenQ                 | 9        | 11.84%  |
| Goldstar             | 5        | 6.58%   |
| Unknown              | 4        | 5.26%   |
| Hewlett-Packard      | 3        | 3.95%   |
| Sony                 | 2        | 2.63%   |
| Sharp                | 2        | 2.63%   |
| Lenovo               | 2        | 2.63%   |
| AOC                  | 2        | 2.63%   |
| Ancor Communications | 2        | 2.63%   |
| Acer                 | 2        | 2.63%   |
| ViewSonic            | 1        | 1.32%   |
| Tech Concepts        | 1        | 1.32%   |
| TCL                  | 1        | 1.32%   |
| Sun                  | 1        | 1.32%   |
| SKY                  | 1        | 1.32%   |
| SHC                  | 1        | 1.32%   |
| RTK                  | 1        | 1.32%   |
| Philips              | 1        | 1.32%   |
| LG Electronics       | 1        | 1.32%   |
| Lenovo Group Limited | 1        | 1.32%   |
| Konka                | 1        | 1.32%   |
| Gigabyte Technology  | 1        | 1.32%   |
| GDH                  | 1        | 1.32%   |
| eMachines            | 1        | 1.32%   |
| ASUSTek Computer     | 1        | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 2        | 2.35%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 2        | 2.35%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                   | 2        | 2.35%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                       | 2        | 2.35%   |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                       | 2        | 2.35%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 2        | 2.35%   |
| ViewSonic VX2253 Series VSC0A28 1920x1080 476x268mm 21.5-inch           | 1        | 1.18%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                        | 1        | 1.18%   |
| Unknown LCD Monitor SCEI MONITOR 1920x1080                              | 1        | 1.18%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 1.18%   |
| Unknown LCD Monitor AAA HDTV 1366x768                                   | 1        | 1.18%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                        | 1        | 1.18%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                     | 1        | 1.18%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1        | 1.18%   |
| Sony TV *00 SNY7C04 3840x2160 952x535mm 43.0-inch                       | 1        | 1.18%   |
| Sony LCD Monitor TV  *00 3840x2160                                      | 1        | 1.18%   |
| SKY TV-PHILCO SKY0104 1920x1080 885x498mm 40.0-inch                     | 1        | 1.18%   |
| SHC SHARP SHC0030 3840x2160 708x398mm 32.0-inch                         | 1        | 1.18%   |
| Sharp LCD Monitor HDMI 1920x1080                                        | 1        | 1.18%   |
| Sharp HDMI SHP4176 1920x1080 1210x680mm 54.6-inch                       | 1        | 1.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 1.18%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch      | 1        | 1.18%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 530x300mm 24.0-inch      | 1        | 1.18%   |
| Samsung Electronics S24C300 SAM0A2A 1920x1080 521x293mm 23.5-inch       | 1        | 1.18%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 1.18%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch       | 1        | 1.18%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch        | 1        | 1.18%   |
| Samsung Electronics LCD Monitor SMBX2450 3840x1080                      | 1        | 1.18%   |
| Samsung Electronics LCD Monitor SMBX2450                                | 1        | 1.18%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch    | 1        | 1.18%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch      | 1        | 1.18%   |
| RTK TV RTK0001 3840x2160                                                | 1        | 1.18%   |
| Philips 234CL PHLC066 1920x1080 509x286mm 23.0-inch                     | 1        | 1.18%   |
| LG Electronics LCD Monitor LG HDR WFHD                                  | 1        | 1.18%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1        | 1.18%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch                | 1        | 1.18%   |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch                | 1        | 1.18%   |
| Lenovo Group Limited LCD Monitor LEN Y27q-20 7040x1440                  | 1        | 1.18%   |
| Konka TV MONIOR KOA0030 1920x540 708x398mm 32.0-inch                    | 1        | 1.18%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch            | 1        | 1.18%   |
| Hewlett-Packard LCD Monitor 22er 1920x1080                              | 1        | 1.18%   |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch              | 1        | 1.18%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                     | 1        | 1.18%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch                | 1        | 1.18%   |
| Goldstar ULTRAGEAR GSM5B72 1920x1080 531x298mm 24.0-inch                | 1        | 1.18%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1        | 1.18%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                   | 1        | 1.18%   |
| Gigabyte Technology LCD Monitor GBT3203 2560x1440 700x390mm 31.5-inch   | 1        | 1.18%   |
| GDH PHILCO GDH0030 1920x540 708x398mm 32.0-inch                         | 1        | 1.18%   |
| eMachines E192HQ EMA00B6 1366x768 410x230mm 18.5-inch                   | 1        | 1.18%   |
| Dell U3818DW DELA0F3 3840x1600 880x367mm 37.5-inch                      | 1        | 1.18%   |
| Dell U2413 DELF047 1920x1200 520x320mm 24.0-inch                        | 1        | 1.18%   |
| Dell U2413 DELF046 1920x1200 518x324mm 24.1-inch                        | 1        | 1.18%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                     | 1        | 1.18%   |
| Dell SE2716H DEL40D8 1920x1080 598x336mm 27.0-inch                      | 1        | 1.18%   |
| Dell S2440L DELA08B 1920x1080 531x299mm 24.0-inch                       | 1        | 1.18%   |
| Dell S2340L DELD057 1920x1080 509x286mm 23.0-inch                       | 1        | 1.18%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                       | 1        | 1.18%   |
| Dell E2216H DELF069 1920x1080 476x268mm 21.5-inch                       | 1        | 1.18%   |
| Dell E2216H DELF068 1920x1080 480x270mm 21.7-inch                       | 1        | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 38       | 50.67%  |
| 3840x2160 (4K)    | 12       | 16%     |
| 1366x768 (WXGA)   | 7        | 9.33%   |
| 2560x1440 (QHD)   | 4        | 5.33%   |
| 1440x900 (WXGA+)  | 3        | 4%      |
| 2560x1080         | 2        | 2.67%   |
| 1280x1024 (SXGA)  | 2        | 2.67%   |
| Unknown           | 2        | 2.67%   |
| 7040x1440         | 1        | 1.33%   |
| 3840x1600         | 1        | 1.33%   |
| 3840x1080         | 1        | 1.33%   |
| 3440x1440         | 1        | 1.33%   |
| 1920x1200 (WUXGA) | 1        | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 15.38%  |
| 23      | 10       | 12.82%  |
| Unknown | 10       | 12.82%  |
| 27      | 8        | 10.26%  |
| 21      | 5        | 6.41%   |
| 18      | 5        | 6.41%   |
| 54      | 4        | 5.13%   |
| 31      | 4        | 5.13%   |
| 34      | 3        | 3.85%   |
| 17      | 3        | 3.85%   |
| 84      | 2        | 2.56%   |
| 52      | 2        | 2.56%   |
| 32      | 2        | 2.56%   |
| 19      | 2        | 2.56%   |
| 72      | 1        | 1.28%   |
| 65      | 1        | 1.28%   |
| 57      | 1        | 1.28%   |
| 40      | 1        | 1.28%   |
| 37      | 1        | 1.28%   |
| 25      | 1        | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 27       | 36%     |
| 401-500     | 12       | 16%     |
| Unknown     | 10       | 13.33%  |
| 1001-1500   | 8        | 10.67%  |
| 701-800     | 5        | 6.67%   |
| 601-700     | 5        | 6.67%   |
| 1501-2000   | 3        | 4%      |
| 801-900     | 2        | 2.67%   |
| 301-350     | 2        | 2.67%   |
| 351-400     | 1        | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 51       | 70.83%  |
| Unknown | 10       | 13.89%  |
| 16/10   | 5        | 6.94%   |
| 21/9    | 4        | 5.56%   |
| 5/4     | 2        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 28.57%  |
| More than 1000 | 11       | 14.29%  |
| Unknown        | 10       | 12.99%  |
| 351-500        | 9        | 11.69%  |
| 301-350        | 8        | 10.39%  |
| 141-150        | 7        | 9.09%   |
| 251-300        | 4        | 5.19%   |
| 151-200        | 3        | 3.9%    |
| 501-1000       | 2        | 2.6%    |
| 131-140        | 1        | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 45       | 59.21%  |
| Unknown | 10       | 13.16%  |
| 101-120 | 9        | 11.84%  |
| 1-50    | 8        | 10.53%  |
| 121-160 | 4        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 63       | 80.77%  |
| 2     | 10       | 12.82%  |
| 0     | 3        | 3.85%   |
| 3     | 2        | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 43       | 34.68%  |
| Realtek Semiconductor    | 37       | 29.84%  |
| Qualcomm Atheros         | 7        | 5.65%   |
| Broadcom                 | 7        | 5.65%   |
| Ralink Technology        | 5        | 4.03%   |
| Samsung Electronics      | 4        | 3.23%   |
| TP-Link                  | 2        | 1.61%   |
| Ralink                   | 2        | 1.61%   |
| MediaTek                 | 2        | 1.61%   |
| Linksys                  | 2        | 1.61%   |
| D-Link                   | 2        | 1.61%   |
| Xiaomi                   | 1        | 0.81%   |
| Wilocity                 | 1        | 0.81%   |
| VIA Technologies         | 1        | 0.81%   |
| T & A Mobile Phones      | 1        | 0.81%   |
| Microsoft                | 1        | 0.81%   |
| Marvell Technology Group | 1        | 0.81%   |
| Huawei Technologies      | 1        | 0.81%   |
| Edimax Technology        | 1        | 0.81%   |
| DisplayLink              | 1        | 0.81%   |
| Belkin Components        | 1        | 0.81%   |
| Apple                    | 1        | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 20.57%  |
| Intel Wi-Fi 6 AX200                                               | 7        | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.96%   |
| Intel I211 Gigabit Network Connection                             | 6        | 4.26%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 3.55%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 2.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 1.42%   |
| Intel Wireless 3165                                               | 2        | 1.42%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.42%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.42%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.42%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 1.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 1.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.71%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.71%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.71%   |
| T & A Mobile Phones TCL 30                                        | 1        | 0.71%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.71%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.71%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.71%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.71%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                              | 1        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.71%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 0.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.71%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.71%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.71%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.71%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 0.71%   |
| Intel Wireless-AC 9260                                            | 1        | 0.71%   |
| Intel Wireless 7260                                               | 1        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.71%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 0.71%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.71%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.71%   |
| Huawei LYA-L09                                                    | 1        | 0.71%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 32.69%  |
| Realtek Semiconductor | 7        | 13.46%  |
| Qualcomm Atheros      | 6        | 11.54%  |
| Ralink Technology     | 5        | 9.62%   |
| Broadcom              | 3        | 5.77%   |
| TP-Link               | 2        | 3.85%   |
| Ralink                | 2        | 3.85%   |
| MediaTek              | 2        | 3.85%   |
| Linksys               | 2        | 3.85%   |
| D-Link                | 2        | 3.85%   |
| Wilocity              | 1        | 1.92%   |
| Microsoft             | 1        | 1.92%   |
| Edimax Technology     | 1        | 1.92%   |
| Belkin Components     | 1        | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 7        | 13.46%  |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 4        | 7.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 3        | 5.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 2        | 3.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                        | 2        | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 2        | 3.85%   |
| Intel Wireless 3165                                                                     | 2        | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 2        | 3.85%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                      | 1        | 1.92%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                              | 1        | 1.92%   |
| TP-Link 802.11ac WLAN Adapter                                                           | 1        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                | 1        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                | 1        | 1.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                         | 1        | 1.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 1.92%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 1.92%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                   | 1        | 1.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                  | 1        | 1.92%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                    | 1        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 1.92%   |
| Microsoft Wireless XBox Controller Dongle                                               | 1        | 1.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 1.92%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 1.92%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 1.92%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]                           | 1        | 1.92%   |
| Intel Wireless-AC 9260                                                                  | 1        | 1.92%   |
| Intel Wireless 7260                                                                     | 1        | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                                          | 1        | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 1.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                        | 1        | 1.92%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                          | 1        | 1.92%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU]                  | 1        | 1.92%   |
| D-Link 802.11n WLAN Adapter                                                             | 1        | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                                         | 1        | 1.92%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 36       | 41.86%  |
| Realtek Semiconductor    | 34       | 39.53%  |
| Samsung Electronics      | 4        | 4.65%   |
| Broadcom                 | 4        | 4.65%   |
| Xiaomi                   | 1        | 1.16%   |
| VIA Technologies         | 1        | 1.16%   |
| T & A Mobile Phones      | 1        | 1.16%   |
| Qualcomm Atheros         | 1        | 1.16%   |
| Marvell Technology Group | 1        | 1.16%   |
| Huawei Technologies      | 1        | 1.16%   |
| DisplayLink              | 1        | 1.16%   |
| Apple                    | 1        | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 32.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 7.87%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.74%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 5.62%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 5.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 3.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.25%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.25%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.25%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.25%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 2.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 2.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.12%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.12%   |
| T & A Mobile Phones TCL 30                                        | 1        | 1.12%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.12%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.12%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.12%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.12%   |
| Huawei LYA-L09                                                    | 1        | 1.12%   |
| DisplayLink Dell D3100 Docking Station                            | 1        | 1.12%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.12%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.12%   |
| Apple iPad 4/Mini1                                                | 1        | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 75       | 62.5%   |
| WiFi     | 45       | 37.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 73.68%  |
| WiFi     | 20       | 26.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 55.84%  |
| 2     | 31       | 40.26%  |
| 3     | 2        | 2.6%    |
| 4     | 1        | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 77.22%  |
| Yes  | 18       | 22.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 16       | 47.06%  |
| Cambridge Silicon Radio | 13       | 38.24%  |
| Realtek Semiconductor   | 2        | 5.88%   |
| MediaTek                | 1        | 2.94%   |
| Broadcom                | 1        | 2.94%   |
| ASUSTek Computer        | 1        | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 38.24%  |
| Intel AX200 Bluetooth                               | 7        | 20.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 8.82%   |
| Realtek Bluetooth Radio                             | 2        | 5.88%   |
| Intel Bluetooth wireless interface                  | 2        | 5.88%   |
| Intel AX201 Bluetooth                               | 2        | 5.88%   |
| MediaTek Wireless_Device                            | 1        | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.94%   |
| Intel Bluetooth Device                              | 1        | 2.94%   |
| Broadcom BCM92045B3 ROM                             | 1        | 2.94%   |
| ASUS Bluetooth Device                               | 1        | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 61       | 44.2%   |
| Nvidia              | 35       | 25.36%  |
| AMD                 | 22       | 15.94%  |
| C-Media Electronics | 8        | 5.8%    |
| Creative Labs       | 3        | 2.17%   |
| VIA Technologies    | 1        | 0.72%   |
| Texas Instruments   | 1        | 0.72%   |
| Tenx Technology     | 1        | 0.72%   |
| Plantronics         | 1        | 0.72%   |
| Kingston Technology | 1        | 0.72%   |
| JMTek               | 1        | 0.72%   |
| Creative Technology | 1        | 0.72%   |
| Corsair             | 1        | 0.72%   |
| Cooler Master       | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH HD Audio                                              | 10       | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 5.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 4.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 4.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.58%   |
| C-Media Electronics CM108 Audio Controller                                 | 4        | 2.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.94%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.94%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 1.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.94%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.29%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.29%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.29%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.29%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.29%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.29%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.65%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.65%   |
| Tenx Technology TP6911 Audio Headset                                       | 1        | 0.65%   |
| Plantronics Wireless Audio                                                 | 1        | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.65%   |
| Kingston Technology HyperX Cloud Alpha S                                   | 1        | 0.65%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.65%   |
| Intel Jasper Lake HD Audio                                                 | 1        | 0.65%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.65%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 0.65%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.65%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                               | 1        | 0.65%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 19.51%  |
| Kingston            | 7        | 17.07%  |
| Micron Technology   | 6        | 14.63%  |
| G.Skill             | 6        | 14.63%  |
| SK hynix            | 5        | 12.2%   |
| Unknown             | 2        | 4.88%   |
| Team                | 1        | 2.44%   |
| Lexar Co Limited    | 1        | 2.44%   |
| Hikvision           | 1        | 2.44%   |
| Elpida              | 1        | 2.44%   |
| Crucial             | 1        | 2.44%   |
| Corsair             | 1        | 2.44%   |
| A-DATA Technology   | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 2        | 4.65%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2        | 4.65%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1        | 2.33%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1        | 2.33%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s               | 1        | 2.33%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s             | 1        | 2.33%   |
| SK hynix RAM HMA851U6DJR6N-XN 4GB DIMM DDR4 3200MT/s             | 1        | 2.33%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s             | 1        | 2.33%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                        | 1        | 2.33%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1333MT/s           | 1        | 2.33%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s              | 1        | 2.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s              | 1        | 2.33%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 2.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 2.33%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s             | 1        | 2.33%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s             | 1        | 2.33%   |
| Micron RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 2.33%   |
| Micron RAM ITC 4GB DIMM DDR3 1648MT/s                            | 1        | 2.33%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s              | 1        | 2.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s           | 1        | 2.33%   |
| Micron RAM 8JTF25664AZ-1G4D1 2048MB DIMM DDR3 1333MT/s           | 1        | 2.33%   |
| Micron RAM 36JSF1G72PZ-1G6K1 8GB DIMM DDR3 1333MT/s              | 1        | 2.33%   |
| Lexar Co Limited RAM LD4AS008G-H3200GST 8GB SODIMM DDR4 3200MT/s | 1        | 2.33%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s          | 1        | 2.33%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s           | 1        | 2.33%   |
| Kingston RAM 99U5474-023.A00LF 4GB DIMM DDR3 1600MT/s            | 1        | 2.33%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s            | 1        | 2.33%   |
| Kingston RAM 99P5471-012.A00LF 4GB DIMM DDR3 1333MT/s            | 1        | 2.33%   |
| Kingston RAM 2G-UDIMM 2GB DIMM DDR2 800MT/s                      | 1        | 2.33%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s        | 1        | 2.33%   |
| G.Skill RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1        | 2.33%   |
| G.Skill RAM F4-3200C16-8GVRB 8GB DIMM DDR4 3200MT/s              | 1        | 2.33%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 1        | 2.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 1        | 2.33%   |
| G.Skill RAM F4-3000C14-8GTZR 8GB DIMM DDR4 2133MT/s              | 1        | 2.33%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s               | 1        | 2.33%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s            | 1        | 2.33%   |
| Elpida RAM EBE21UE8AFFA-8G-F 2GB DIMM DDR2 800MT/s               | 1        | 2.33%   |
| Crucial RAM CB4GU2400.C8GT 4GB DIMM DDR4 2400MT/s                | 1        | 2.33%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s           | 1        | 2.33%   |
| A-DATA RAM Module 4GB DIMM DDR4 2667MT/s                         | 1        | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 16       | 51.61%  |
| DDR3    | 12       | 38.71%  |
| SDRAM   | 1        | 3.23%   |
| DDR2    | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 93.33%  |
| SODIMM | 2        | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 11       | 33.33%  |
| 8192  | 10       | 30.3%   |
| 16384 | 7        | 21.21%  |
| 2048  | 3        | 9.09%   |
| 32768 | 1        | 3.03%   |
| 1024  | 1        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 7        | 20%     |
| 1333  | 5        | 14.29%  |
| 1600  | 4        | 11.43%  |
| 2667  | 3        | 8.57%   |
| 2133  | 3        | 8.57%   |
| 3466  | 2        | 5.71%   |
| 2400  | 2        | 5.71%   |
| 1867  | 2        | 5.71%   |
| 1866  | 2        | 5.71%   |
| 3600  | 1        | 2.86%   |
| 1800  | 1        | 2.86%   |
| 1648  | 1        | 2.86%   |
| 800   | 1        | 2.86%   |
| 667   | 1        | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 5        | 62.5%   |
| Brother Industries     | 2        | 25%     |
| Panasonic (Matsushita) | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Brother HL-2130 series             | 2        | 25%     |
| Panasonic (Matsushita) KX-MB1500RU | 1        | 12.5%   |
| HP LaserJet P2055 series           | 1        | 12.5%   |
| HP LaserJet P2015 series           | 1        | 12.5%   |
| HP LaserJet M101-M106              | 1        | 12.5%   |
| HP LaserJet CP 1025                | 1        | 12.5%   |
| HP DeskJet 2130 series             | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 500F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microsoft                     | 3        | 33.33%  |
| Apple                         | 2        | 22.22%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| Samsung Electronics           | 1        | 11.11%  |
| Arkmicro Technologies         | 1        | 11.11%  |
| ARC International             | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE            | 2        | 22.22%  |
| Sunplus Lihappe8 Webcam L0485A2SP    | 1        | 11.11%  |
| Samsung Galaxy A5 (MTP)              | 1        | 11.11%  |
| Microsoft MicrosoftÂ LifeCam Cinema | 1        | 11.11%  |
| Microsoft LifeCam HD-5000            | 1        | 11.11%  |
| Microsoft LifeCam Cinema             | 1        | 11.11%  |
| Arkmicro USB2.0 PC CAMERA            | 1        | 11.11%  |
| ARC International Camera             | 1        | 11.11%  |

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
| 0     | 61       | 78.21%  |
| 1     | 15       | 19.23%  |
| 2     | 2        | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 9        | 50%     |
| Graphics card            | 4        | 22.22%  |
| Communication controller | 2        | 11.11%  |
| Unassigned class         | 1        | 5.56%   |
| Storage/raid             | 1        | 5.56%   |
| Camera                   | 1        | 5.56%   |


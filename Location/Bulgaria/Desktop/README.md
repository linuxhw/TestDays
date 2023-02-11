Linux in Bulgaria - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

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

Total: 480

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0J3C2F A02                  | [e4b2eae84b](https://linux-hardware.org/?probe=e4b2eae84b) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| ASRock        | H81M-ITX                    | [036832c7d1](https://linux-hardware.org/?probe=036832c7d1) | Jan 17, 2023 |
| ASUSTek       | B85M-E                      | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| ASUSTek       | B150-PLUS                   | [30b776e4e8](https://linux-hardware.org/?probe=30b776e4e8) | Jan 11, 2023 |
| ASUSTek       | B150-PLUS                   | [7cd86f1bf1](https://linux-hardware.org/?probe=7cd86f1bf1) | Jan 10, 2023 |
| MSI           | B550-A PRO                  | [183b311eb2](https://linux-hardware.org/?probe=183b311eb2) | Jan 09, 2023 |
| Fujitsu       | D3076-S1 S26361-D3076-S1    | [10b0d01482](https://linux-hardware.org/?probe=10b0d01482) | Jan 04, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| Gigabyte      | B85M-D3H                    | [a4aed5865b](https://linux-hardware.org/?probe=a4aed5865b) | Dec 18, 2022 |
| Gigabyte      | B85M-D3H                    | [532dc55c4b](https://linux-hardware.org/?probe=532dc55c4b) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| Dell          | 0VD92X A00                  | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| ASUSTek       | P8B75-M                     | [936608196d](https://linux-hardware.org/?probe=936608196d) | Dec 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [aae285b0ea](https://linux-hardware.org/?probe=aae285b0ea) | Dec 09, 2022 |
| HP            | 3047h                       | [223495dbab](https://linux-hardware.org/?probe=223495dbab) | Dec 08, 2022 |
| Gigabyte      | 970A-UD3P                   | [5ff0fd5395](https://linux-hardware.org/?probe=5ff0fd5395) | Dec 06, 2022 |
| Gigabyte      | 970A-UD3P                   | [e2ffdfc5a8](https://linux-hardware.org/?probe=e2ffdfc5a8) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO             | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| ASUSTek       | H97-PLUS                    | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| BESSTAR Te... | UM700                       | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Dell          | 0J8G6F A03                  | [1424a94eb0](https://linux-hardware.org/?probe=1424a94eb0) | Nov 29, 2022 |
| HP            | 1589                        | [4e67735055](https://linux-hardware.org/?probe=4e67735055) | Nov 27, 2022 |
| Intel         | D525MW AAE93082-401         | [d480b7ef56](https://linux-hardware.org/?probe=d480b7ef56) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | [d3b2f8aaf7](https://linux-hardware.org/?probe=d3b2f8aaf7) | Nov 25, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [faa15c49ae](https://linux-hardware.org/?probe=faa15c49ae) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | [5468f11c01](https://linux-hardware.org/?probe=5468f11c01) | Nov 15, 2022 |
| ASRock        | B450 Steel Legend           | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| MSI           | Z97 GAMING 5                | [519c833f31](https://linux-hardware.org/?probe=519c833f31) | Nov 06, 2022 |
| Dell          | 07N90W A00                  | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| Dell          | 07N90W A00                  | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| ASUSTek       | P5G41T-M LX                 | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| HP            | 8061                        | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| ASRock        | Z87 Pro3                    | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 07N90W A00                  | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | [b50165d9c9](https://linux-hardware.org/?probe=b50165d9c9) | Oct 11, 2022 |
| Dell          | 07N90W A00                  | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| ASUSTek       | PRIME X399-A                | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Intel         | D34010WYK H14771-303        | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8f41682975](https://linux-hardware.org/?probe=8f41682975) | Oct 03, 2022 |
| ASRock        | B450 Steel Legend           | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| ASRock        | B450 Steel Legend           | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| HP            | 3047h                       | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| ASRock        | B450M Steel Legend          | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [8047eeecb4](https://linux-hardware.org/?probe=8047eeecb4) | Aug 20, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | [c92d457cd6](https://linux-hardware.org/?probe=c92d457cd6) | Aug 13, 2022 |
| ASUSTek       | M2VTVM-VM890                | [8a822a57e8](https://linux-hardware.org/?probe=8a822a57e8) | Aug 13, 2022 |
| Foxconn       | 2A8C                        | [747ba68b28](https://linux-hardware.org/?probe=747ba68b28) | Aug 10, 2022 |
| ASRock        | B450M Steel Legend          | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| ASUSTek       | B85M-G                      | [616c57c367](https://linux-hardware.org/?probe=616c57c367) | Aug 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [e0129903ae](https://linux-hardware.org/?probe=e0129903ae) | Aug 04, 2022 |
| ASUSTek       | P5KC                        | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| ASUSTek       | P7H55-M LX                  | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| HP            | 1495                        | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| ASUSTek       | P8H61-M LX2                 | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| ASRock        | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Gigabyte      | X99-UD4-CF                  | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| ASUSTek       | M3A78-EM                    | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| ASRock        | N68-S                       | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASRock        | 890GM Pro3 R2.0             | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| HP            | ProLiant ML350 G5           | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| ASUSTek       | P5KC                        | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| ASUSTek       | P5K Premium                 | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| Acer          | Predator G3-605             | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| Gigabyte      | H97N                        | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| Pegatron      | 2AC3                        | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| MSI           | PRO B660-A DDR4             | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Gigabyte      | X99-UD4-CF                  | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| ASRock        | B450M Steel Legend          | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| ASRock        | B450M Steel Legend          | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| ASRock        | B450M-HDV R4.0              | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| ASRock        | A320M Pro4                  | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| ASUSTek       | P5KC                        | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| ASRock        | 960GM-GS3 FX                | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| ASUSTek       | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| ASRock        | FM2A58M-DG3+                | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| ASRock        | H110M-DGS                   | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| ASUSTek       | PRIME Z270-P                | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Gigabyte      | X570 GAMING X               | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| HP            | 3397                        | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Gigabyte      | X570 GAMING X               | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| ASUSTek       | P5E                         | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Gigabyte      | X570 GAMING X               | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| ASRock        | B450M Steel Legend          | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Dell          | 0427JK A00                  | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASRock        | B450M Steel Legend          | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| ASUSTek       | PRIME Z590-P                | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| ASUSTek       | M51BC                       | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| ASRock        | B450M Steel Legend          | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| ASUSTek       | PRIME X570-P                | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| ASRock        | B450M Steel Legend          | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| ASUSTek       | PRIME B350M-A               | [3ab004eed4](https://linux-hardware.org/?probe=3ab004eed4) | Oct 17, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| ASRock        | H81M-HDS                    | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| Gigabyte      | H310M S2P                   | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| ASRock        | FM2A58M-HD+                 | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Lenovo        | ThinkStation D20 4158E93    | [fde770f309](https://linux-hardware.org/?probe=fde770f309) | Sep 11, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [a95e304baf](https://linux-hardware.org/?probe=a95e304baf) | Sep 07, 2021 |
| Unknown       | Unknown                     | [a37b749b27](https://linux-hardware.org/?probe=a37b749b27) | Sep 06, 2021 |
| Unknown       | Unknown                     | [92e21fb915](https://linux-hardware.org/?probe=92e21fb915) | Sep 06, 2021 |
| ASRock        | X570 Pro4                   | [7c76ac10d8](https://linux-hardware.org/?probe=7c76ac10d8) | Sep 04, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [7d634f76ad](https://linux-hardware.org/?probe=7d634f76ad) | Aug 31, 2021 |
| ASRock        | FM2A58M-HD+                 | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| HP            | 18E4                        | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| ASRock        | FM2A68M-DG3+                | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| MSI           | A68HM-P33 V2                | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| Gigabyte      | GA-870A-USB3                | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| ASUSTek       | P5KC                        | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| ASUSTek       | M4A78 PRO                   | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| ASRock        | H110 Pro BTC+               | [0c191944fc](https://linux-hardware.org/?probe=0c191944fc) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | [a08f9bd38d](https://linux-hardware.org/?probe=a08f9bd38d) | Aug 02, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| Gigabyte      | GA-870A-USB3                | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| ASRock        | AB350 Pro4                  | [5d62f330ba](https://linux-hardware.org/?probe=5d62f330ba) | Jul 18, 2021 |
| ASUSTek       | TUF X299 MARK 2             | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| ASUSTek       | P5QD TURBO                  | [5ce964530d](https://linux-hardware.org/?probe=5ce964530d) | Jul 13, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [13af782a58](https://linux-hardware.org/?probe=13af782a58) | Jun 29, 2021 |
| Gigabyte      | GA-870A-USB3                | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| HP            | 1493                        | [cd54c7db25](https://linux-hardware.org/?probe=cd54c7db25) | Jun 26, 2021 |
| HP            | 1493                        | [5b7dd91534](https://linux-hardware.org/?probe=5b7dd91534) | Jun 26, 2021 |
| Gigabyte      | GA-M56S-S3                  | [e7e3e4138d](https://linux-hardware.org/?probe=e7e3e4138d) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | [c4f55611e4](https://linux-hardware.org/?probe=c4f55611e4) | Jun 20, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [f200ec0bda](https://linux-hardware.org/?probe=f200ec0bda) | Jun 08, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [9a2b696908](https://linux-hardware.org/?probe=9a2b696908) | Jun 05, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | [6bc1b9dcc9](https://linux-hardware.org/?probe=6bc1b9dcc9) | May 31, 2021 |
| Dell          | 0K240Y A02                  | [c050f79e2b](https://linux-hardware.org/?probe=c050f79e2b) | May 29, 2021 |
| Dell          | 0K240Y A02                  | [7f510d13fb](https://linux-hardware.org/?probe=7f510d13fb) | May 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| ASRock        | Z97 Anniversary             | [493f6f8057](https://linux-hardware.org/?probe=493f6f8057) | May 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | [4d5f23e6ba](https://linux-hardware.org/?probe=4d5f23e6ba) | May 17, 2021 |
| ASRock        | Z97 Anniversary             | [14ea7483bc](https://linux-hardware.org/?probe=14ea7483bc) | May 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [22657f3929](https://linux-hardware.org/?probe=22657f3929) | May 15, 2021 |
| HP            | 3396                        | [ed3fa57f54](https://linux-hardware.org/?probe=ed3fa57f54) | May 15, 2021 |
| ASUSTek       | B150M-A                     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Unknown       | Unknown                     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | P5KC                        | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASRock        | X570 Pro4                   | [3ad2c89a0a](https://linux-hardware.org/?probe=3ad2c89a0a) | May 03, 2021 |
| ASUSTek       | P5KC                        | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| ASRock        | X79 Extreme4                | [d3383d57ef](https://linux-hardware.org/?probe=d3383d57ef) | May 01, 2021 |
| ASUSTek       | Amberine M                  | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| ASRock        | B360M Pro4                  | [b1f9a4880e](https://linux-hardware.org/?probe=b1f9a4880e) | Apr 22, 2021 |
| ASUSTek       | P8P67 DELUXE                | [8c83051b44](https://linux-hardware.org/?probe=8c83051b44) | Apr 12, 2021 |
| ASRock        | Z68 Extreme7 Gen3           | [d8e2ac9e9b](https://linux-hardware.org/?probe=d8e2ac9e9b) | Apr 11, 2021 |
| ASUSTek       | PRIME X370-PRO              | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| ASRock        | A320M-HDV R4.0              | [658ec2843e](https://linux-hardware.org/?probe=658ec2843e) | Apr 03, 2021 |
| HP            | 1850                        | [517c6137a3](https://linux-hardware.org/?probe=517c6137a3) | Apr 01, 2021 |
| ASRock        | B550M Pro4                  | [333c645cc4](https://linux-hardware.org/?probe=333c645cc4) | Apr 01, 2021 |
| ASRock        | AB350M Pro4                 | [bd779f8e4e](https://linux-hardware.org/?probe=bd779f8e4e) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | [072483c895](https://linux-hardware.org/?probe=072483c895) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | [11e59c84c6](https://linux-hardware.org/?probe=11e59c84c6) | Mar 26, 2021 |
| Seco          | C40 C                       | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [e5f799a9f1](https://linux-hardware.org/?probe=e5f799a9f1) | Mar 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [d2d43a5a92](https://linux-hardware.org/?probe=d2d43a5a92) | Mar 17, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [ef2bfba994](https://linux-hardware.org/?probe=ef2bfba994) | Mar 17, 2021 |
| ECS           | MCP61M-M3                   | [39fb7fbfdd](https://linux-hardware.org/?probe=39fb7fbfdd) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | [30047ff89f](https://linux-hardware.org/?probe=30047ff89f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| ASUSTek       | PRIME X570-P                | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| Dell          | 0T10XW A02                  | [3fc42af6ee](https://linux-hardware.org/?probe=3fc42af6ee) | Mar 13, 2021 |
| Dell          | 0T10XW A02                  | [3403829400](https://linux-hardware.org/?probe=3403829400) | Mar 13, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [e2bd9d6df8](https://linux-hardware.org/?probe=e2bd9d6df8) | Mar 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | [5ff3194762](https://linux-hardware.org/?probe=5ff3194762) | Mar 10, 2021 |
| ASRock        | AB350 Pro4                  | [a76ade188b](https://linux-hardware.org/?probe=a76ade188b) | Mar 07, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [b3a1ae5051](https://linux-hardware.org/?probe=b3a1ae5051) | Mar 06, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [f14a8d2de0](https://linux-hardware.org/?probe=f14a8d2de0) | Mar 05, 2021 |
| ASUSTek       | M2N68-AM Plus               | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Intel         | X99 V102                    | [e4884fdd22](https://linux-hardware.org/?probe=e4884fdd22) | Feb 25, 2021 |
| HP            | 3396                        | [dd8601c672](https://linux-hardware.org/?probe=dd8601c672) | Feb 24, 2021 |
| HP            | 3396                        | [5c5fde40cd](https://linux-hardware.org/?probe=5c5fde40cd) | Feb 24, 2021 |
| ASUSTek       | PRIME X570-P                | [53d26490a1](https://linux-hardware.org/?probe=53d26490a1) | Feb 23, 2021 |
| HP            | 1494                        | [c369d28059](https://linux-hardware.org/?probe=c369d28059) | Feb 23, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5ad971da58](https://linux-hardware.org/?probe=5ad971da58) | Feb 23, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | [698bd7ab9c](https://linux-hardware.org/?probe=698bd7ab9c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | [e5ae830bbf](https://linux-hardware.org/?probe=e5ae830bbf) | Feb 21, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [b9b1df7b2d](https://linux-hardware.org/?probe=b9b1df7b2d) | Feb 21, 2021 |
| Dell          | 0DFRFW A01                  | [71a10bba93](https://linux-hardware.org/?probe=71a10bba93) | Feb 16, 2021 |
| MSI           | MS-7250                     | [e1f266f412](https://linux-hardware.org/?probe=e1f266f412) | Feb 15, 2021 |
| MSI           | H61M-P31                    | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| ASUSTek       | A8N-E                       | [a35eff4bb9](https://linux-hardware.org/?probe=a35eff4bb9) | Feb 14, 2021 |
| iEi           | B202 V1.0                   | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Gigabyte      | H81M-HD3                    | [b6b357f26c](https://linux-hardware.org/?probe=b6b357f26c) | Feb 14, 2021 |
| ASRock        | 890GX Extreme3              | [1168daa7de](https://linux-hardware.org/?probe=1168daa7de) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | [dc1822ee72](https://linux-hardware.org/?probe=dc1822ee72) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | [8fedc4a9c1](https://linux-hardware.org/?probe=8fedc4a9c1) | Feb 12, 2021 |
| Lenovo        | MAHOBAY NOK                 | [2d6363ed19](https://linux-hardware.org/?probe=2d6363ed19) | Feb 10, 2021 |
| ASRock        | X570 Taichi                 | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASRock        | FM2A85X Extreme4            | [2f1725cb23](https://linux-hardware.org/?probe=2f1725cb23) | Jan 30, 2021 |
| ASUSTek       | PRIME X570-P                | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5e824ae0f4](https://linux-hardware.org/?probe=5e824ae0f4) | Jan 29, 2021 |
| ASRock        | H87M Pro4                   | [88e1834599](https://linux-hardware.org/?probe=88e1834599) | Jan 24, 2021 |
| ASUSTek       | M5A78L-M LX                 | [194dbb8e46](https://linux-hardware.org/?probe=194dbb8e46) | Jan 24, 2021 |
| Gigabyte      | M68M-S2P                    | [bdee5c1907](https://linux-hardware.org/?probe=bdee5c1907) | Jan 23, 2021 |
| ASRock        | H110M-HDV                   | [6eecfdfd4b](https://linux-hardware.org/?probe=6eecfdfd4b) | Jan 21, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [e10b7bc8cf](https://linux-hardware.org/?probe=e10b7bc8cf) | Jan 21, 2021 |
| MiTAC         | E220 6A7                    | [0d75e5ba34](https://linux-hardware.org/?probe=0d75e5ba34) | Jan 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [20416ee115](https://linux-hardware.org/?probe=20416ee115) | Jan 10, 2021 |
| Dell          | 0K240Y A02                  | [1c948eea28](https://linux-hardware.org/?probe=1c948eea28) | Jan 05, 2021 |
| ASRock        | 960GM-GS3 FX                | [13e7f80b8f](https://linux-hardware.org/?probe=13e7f80b8f) | Jan 03, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [5232dd577c](https://linux-hardware.org/?probe=5232dd577c) | Jan 03, 2021 |
| ASUSTek       | P8H77-V                     | [50edfe4e5e](https://linux-hardware.org/?probe=50edfe4e5e) | Jan 01, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [05fcb61de6](https://linux-hardware.org/?probe=05fcb61de6) | Dec 29, 2020 |
| ASUSTek       | P5G41T-M LX                 | [06f63c2119](https://linux-hardware.org/?probe=06f63c2119) | Dec 24, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [fed52f343a](https://linux-hardware.org/?probe=fed52f343a) | Dec 24, 2020 |
| MiTAC         | E220 6A7                    | [e051bc126d](https://linux-hardware.org/?probe=e051bc126d) | Dec 23, 2020 |
| Dell          | 0K240Y A02                  | [d522c503da](https://linux-hardware.org/?probe=d522c503da) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [ad3ac7bcee](https://linux-hardware.org/?probe=ad3ac7bcee) | Dec 19, 2020 |
| Unknown       | GSUO H61                    | [3c4c6c8bd0](https://linux-hardware.org/?probe=3c4c6c8bd0) | Dec 14, 2020 |
| Gigabyte      | EP45-DS3L                   | [d0388f0066](https://linux-hardware.org/?probe=d0388f0066) | Dec 12, 2020 |
| Gigabyte      | EQ45M-S2                    | [2c39a254ee](https://linux-hardware.org/?probe=2c39a254ee) | Dec 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | [6502e1050d](https://linux-hardware.org/?probe=6502e1050d) | Dec 05, 2020 |
| ASRock        | 960GM-GS3 FX                | [b7e98a5926](https://linux-hardware.org/?probe=b7e98a5926) | Dec 04, 2020 |
| ASRock        | FM2A75 Pro4+                | [d12dc95e76](https://linux-hardware.org/?probe=d12dc95e76) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | [02c7320eaf](https://linux-hardware.org/?probe=02c7320eaf) | Dec 03, 2020 |
| ASRock        | G41M-S3                     | [1f91a14ff2](https://linux-hardware.org/?probe=1f91a14ff2) | Dec 03, 2020 |
| ASRock        | X370 Gaming K4              | [7b8b964ce4](https://linux-hardware.org/?probe=7b8b964ce4) | Nov 29, 2020 |
| Dell          | 0K240Y A02                  | [6f8d2322b6](https://linux-hardware.org/?probe=6f8d2322b6) | Nov 25, 2020 |
| ASUSTek       | H110M-PLUS                  | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Lenovo        | MAHOBAY                     | [7698cbedd0](https://linux-hardware.org/?probe=7698cbedd0) | Nov 12, 2020 |
| Gigabyte      | B450 AORUS M                | [c1df930d7e](https://linux-hardware.org/?probe=c1df930d7e) | Nov 10, 2020 |
| iEi           | B202 V1.0                   | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| Packard Be... | IMEDIA S2185                | [5fd02031d2](https://linux-hardware.org/?probe=5fd02031d2) | Oct 21, 2020 |
| Dell          | 0XHGV1 A00                  | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| ASUSTek       | P5GC-MX/1333                | [bfe71baced](https://linux-hardware.org/?probe=bfe71baced) | Oct 14, 2020 |
| Gigabyte      | PH67A-D3-B3                 | [61b3d8f426](https://linux-hardware.org/?probe=61b3d8f426) | Oct 09, 2020 |
| ASRock        | AB350M Pro4                 | [b178beac46](https://linux-hardware.org/?probe=b178beac46) | Oct 07, 2020 |
| ASUSTek       | P10S-V Series               | [ab381f976a](https://linux-hardware.org/?probe=ab381f976a) | Oct 04, 2020 |
| Gigabyte      | P35-S3G                     | [c55cb88668](https://linux-hardware.org/?probe=c55cb88668) | Sep 30, 2020 |
| Acer          | EG43M                       | [f70bf9f37f](https://linux-hardware.org/?probe=f70bf9f37f) | Sep 26, 2020 |
| Acer          | EG43M                       | [93fe9368c0](https://linux-hardware.org/?probe=93fe9368c0) | Sep 26, 2020 |
| ASUSTek       | Berkeley                    | [db3c1d0348](https://linux-hardware.org/?probe=db3c1d0348) | Sep 13, 2020 |
| ASUSTek       | TUF Z370-PRO GAMING         | [fd2b790572](https://linux-hardware.org/?probe=fd2b790572) | Sep 09, 2020 |
| Shuttle       | FH81                        | [f7d3c868f1](https://linux-hardware.org/?probe=f7d3c868f1) | Sep 07, 2020 |
| Gigabyte      | H97-Gaming 3                | [bc5ee009b9](https://linux-hardware.org/?probe=bc5ee009b9) | Aug 29, 2020 |
| HP            | 0AA4h                       | [e1d187b146](https://linux-hardware.org/?probe=e1d187b146) | Aug 24, 2020 |
| Gigabyte      | H97-Gaming 3                | [b636cd4fc2](https://linux-hardware.org/?probe=b636cd4fc2) | Aug 10, 2020 |
| Lenovo        | ThinkCentre M90p 5864BQ9    | [2f13897020](https://linux-hardware.org/?probe=2f13897020) | Aug 06, 2020 |
| HP            | 1632                        | [051549bbcd](https://linux-hardware.org/?probe=051549bbcd) | Aug 03, 2020 |
| HP            | 1496                        | [814a9396ee](https://linux-hardware.org/?probe=814a9396ee) | Aug 01, 2020 |
| ASUSTek       | A8N-VM CSM                  | [d6af935ba5](https://linux-hardware.org/?probe=d6af935ba5) | Jul 30, 2020 |
| ASUSTek       | X99-PRO                     | [ec4e8d2f6b](https://linux-hardware.org/?probe=ec4e8d2f6b) | Jul 30, 2020 |
| ASRock        | ConRoe945PL-GLAN            | [006d3a68b4](https://linux-hardware.org/?probe=006d3a68b4) | Jul 30, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| Gigabyte      | 990XA-UD3                   | [974c9ebd9c](https://linux-hardware.org/?probe=974c9ebd9c) | Jul 26, 2020 |
| Foxconn       | 2A8C                        | [511636781f](https://linux-hardware.org/?probe=511636781f) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [2afa9387d5](https://linux-hardware.org/?probe=2afa9387d5) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [8ced06cd1f](https://linux-hardware.org/?probe=8ced06cd1f) | Jul 25, 2020 |
| ASUSTek       | P5B-Deluxe                  | [7b8022aa05](https://linux-hardware.org/?probe=7b8022aa05) | Jul 23, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| Foxconn       | 2A8C                        | [1de3848a94](https://linux-hardware.org/?probe=1de3848a94) | Jul 19, 2020 |
| Gigabyte      | H97-Gaming 3                | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| MSI           | B350 TOMAHAWK               | [7387ae682a](https://linux-hardware.org/?probe=7387ae682a) | Jul 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | [46702d58d5](https://linux-hardware.org/?probe=46702d58d5) | Jul 04, 2020 |
| MSI           | B150 GAMING M3              | [4e837b8686](https://linux-hardware.org/?probe=4e837b8686) | Jul 01, 2020 |
| Intel         | DX58SO2 AAG10925-205        | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek       | P8H61-I LX R2.0/RM/SI       | [a5f5e5572b](https://linux-hardware.org/?probe=a5f5e5572b) | Jun 30, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [078efbe676](https://linux-hardware.org/?probe=078efbe676) | Jun 29, 2020 |
| ASRock        | 960GM-GS3 FX                | [a79843ff43](https://linux-hardware.org/?probe=a79843ff43) | Jun 27, 2020 |
| Gigabyte      | B450 AORUS M                | [5d93931a70](https://linux-hardware.org/?probe=5d93931a70) | Jun 21, 2020 |
| Gigabyte      | B450 AORUS M                | [6d318a0db0](https://linux-hardware.org/?probe=6d318a0db0) | Jun 21, 2020 |
| Gigabyte      | X99-UD4-CF                  | [f2f35bedba](https://linux-hardware.org/?probe=f2f35bedba) | Jun 20, 2020 |
| Gigabyte      | X99-UD4-CF                  | [22ca9e31e5](https://linux-hardware.org/?probe=22ca9e31e5) | Jun 15, 2020 |
| ASRock        | H110M-HDV                   | [9a04c60269](https://linux-hardware.org/?probe=9a04c60269) | Jun 15, 2020 |
| ASUSTek       | X99-PRO                     | [1b58de62cc](https://linux-hardware.org/?probe=1b58de62cc) | Jun 14, 2020 |
| ASUSTek       | X99-PRO                     | [5a279c96a5](https://linux-hardware.org/?probe=5a279c96a5) | Jun 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1e9b7bd7d0](https://linux-hardware.org/?probe=1e9b7bd7d0) | Jun 09, 2020 |
| ASRock        | 970M Pro3                   | [f40c51e426](https://linux-hardware.org/?probe=f40c51e426) | Jun 03, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [efa59eef1c](https://linux-hardware.org/?probe=efa59eef1c) | Jun 01, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [9c341d7259](https://linux-hardware.org/?probe=9c341d7259) | May 25, 2020 |
| Intel         | DG35EC AAE29266-205         | [5bd26cbc33](https://linux-hardware.org/?probe=5bd26cbc33) | May 24, 2020 |
| ASUSTek       | M2N-MX SE Plus              | [34d65fc5b5](https://linux-hardware.org/?probe=34d65fc5b5) | May 22, 2020 |
| HP            | 1496                        | [64b345823f](https://linux-hardware.org/?probe=64b345823f) | May 18, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [5d67f4aace](https://linux-hardware.org/?probe=5d67f4aace) | May 16, 2020 |
| Gigabyte      | H97-Gaming 3                | [d4a5246eaa](https://linux-hardware.org/?probe=d4a5246eaa) | May 12, 2020 |
| MSI           | MS-7368                     | [090e6cd15c](https://linux-hardware.org/?probe=090e6cd15c) | May 01, 2020 |
| MSI           | MS-7368                     | [308c2e01f6](https://linux-hardware.org/?probe=308c2e01f6) | Apr 30, 2020 |
| ASUSTek       | M2N68-CM                    | [6f787e35a1](https://linux-hardware.org/?probe=6f787e35a1) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM                    | [7dceeca2dd](https://linux-hardware.org/?probe=7dceeca2dd) | Apr 24, 2020 |
| Gigabyte      | P85-D3                      | [5972095107](https://linux-hardware.org/?probe=5972095107) | Apr 21, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [00cedd86e4](https://linux-hardware.org/?probe=00cedd86e4) | Apr 19, 2020 |
| Dell          | 08NPPY A00                  | [895a4ce7cb](https://linux-hardware.org/?probe=895a4ce7cb) | Apr 15, 2020 |
| Shuttle       | FH81                        | [61209bcee3](https://linux-hardware.org/?probe=61209bcee3) | Apr 11, 2020 |
| ASRock        | 890GX Extreme3              | [2f70e1ae2c](https://linux-hardware.org/?probe=2f70e1ae2c) | Apr 10, 2020 |
| ASRock        | 970 Extreme3                | [679cdbade2](https://linux-hardware.org/?probe=679cdbade2) | Apr 05, 2020 |
| HP            | 0A64h                       | [79aa6d6301](https://linux-hardware.org/?probe=79aa6d6301) | Apr 05, 2020 |
| ASUSTek       | P5K                         | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| ASRock        | X470 Taichi Ultimate        | [a7f7938a12](https://linux-hardware.org/?probe=a7f7938a12) | Apr 02, 2020 |
| ASUSTek       | P5KPL-AM                    | [4db785101b](https://linux-hardware.org/?probe=4db785101b) | Apr 01, 2020 |
| Dell          | 0DR845                      | [c1582b3202](https://linux-hardware.org/?probe=c1582b3202) | Apr 01, 2020 |
| ASUSTek       | P5K SE                      | [8492263fc0](https://linux-hardware.org/?probe=8492263fc0) | Mar 29, 2020 |
| ASUSTek       | P5K SE                      | [fd766dda01](https://linux-hardware.org/?probe=fd766dda01) | Mar 26, 2020 |
| ASRock        | G41M-S3                     | [19c0625a28](https://linux-hardware.org/?probe=19c0625a28) | Mar 24, 2020 |
| ASUSTek       | M4A3000E                    | [76ec7cf71b](https://linux-hardware.org/?probe=76ec7cf71b) | Mar 23, 2020 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [0d2e81fb9b](https://linux-hardware.org/?probe=0d2e81fb9b) | Mar 20, 2020 |
| ASUSTek       | P5K                         | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| ASRock        | X470 Taichi Ultimate        | [53d0f3f5fc](https://linux-hardware.org/?probe=53d0f3f5fc) | Mar 13, 2020 |
| Unknown       | K8NF6G-VSTA                 | [b4f0d62c45](https://linux-hardware.org/?probe=b4f0d62c45) | Mar 08, 2020 |
| Unknown       | K8NF6G-VSTA                 | [08691dfde3](https://linux-hardware.org/?probe=08691dfde3) | Mar 08, 2020 |
| ASRock        | 890FX Deluxe4               | [391c431de9](https://linux-hardware.org/?probe=391c431de9) | Mar 05, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [5b7e72604e](https://linux-hardware.org/?probe=5b7e72604e) | Mar 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [4c1a03683b](https://linux-hardware.org/?probe=4c1a03683b) | Mar 01, 2020 |
| Intel         | DQ57TM AAE92694-402         | [e82b578dad](https://linux-hardware.org/?probe=e82b578dad) | Feb 28, 2020 |
| ASRock        | H81M-ITX/WiFi               | [a513552c14](https://linux-hardware.org/?probe=a513552c14) | Feb 27, 2020 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | [455dbd81e1](https://linux-hardware.org/?probe=455dbd81e1) | Feb 22, 2020 |
| ASUSTek       | P8H61-M LX                  | [b09f7bb137](https://linux-hardware.org/?probe=b09f7bb137) | Feb 22, 2020 |
| ASUSTek       | H81M-PLUS                   | [8231b2fe22](https://linux-hardware.org/?probe=8231b2fe22) | Feb 18, 2020 |
| ASUSTek       | A88XM-E                     | [ea21444fa7](https://linux-hardware.org/?probe=ea21444fa7) | Feb 11, 2020 |
| ASUSTek       | A88XM-E                     | [984a9c83fd](https://linux-hardware.org/?probe=984a9c83fd) | Feb 10, 2020 |
| HP            | 0A64h                       | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| ASUSTek       | M2N68-CM                    | [201ca7dd72](https://linux-hardware.org/?probe=201ca7dd72) | Jan 28, 2020 |
| ASRock        | AB350M Pro4 R2.0            | [11e945005f](https://linux-hardware.org/?probe=11e945005f) | Jan 08, 2020 |
| ASUSTek       | H81M-PLUS                   | [6056ef2c40](https://linux-hardware.org/?probe=6056ef2c40) | Jan 07, 2020 |
| ASUSTek       | H110M-PLUS                  | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASUSTek       | V-P8H67E                    | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| Foxconn       | A55MX                       | [05c6b7995d](https://linux-hardware.org/?probe=05c6b7995d) | Dec 19, 2019 |
| Lenovo        | ThinkCentre M91p 7033W9N    | [3eb7eb388c](https://linux-hardware.org/?probe=3eb7eb388c) | Dec 17, 2019 |
| Lenovo        | ThinkCentre M91p 7033W9N    | [aaa8d34fff](https://linux-hardware.org/?probe=aaa8d34fff) | Dec 17, 2019 |
| ASUSTek       | H81M-PLUS                   | [6e09a0e0aa](https://linux-hardware.org/?probe=6e09a0e0aa) | Dec 16, 2019 |
| ASUSTek       | V-P8H67E                    | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| Intel         | DG35EC AAE29266-205         | [0a74735da6](https://linux-hardware.org/?probe=0a74735da6) | Dec 12, 2019 |
| HP            | 1850                        | [898f2b7197](https://linux-hardware.org/?probe=898f2b7197) | Dec 01, 2019 |
| ASRock        | B85M Pro4                   | [c6b09d560f](https://linux-hardware.org/?probe=c6b09d560f) | Nov 30, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [ade7b4eb87](https://linux-hardware.org/?probe=ade7b4eb87) | Nov 29, 2019 |
| ASUSTek       | H97-PLUS                    | [5b9bb1aedb](https://linux-hardware.org/?probe=5b9bb1aedb) | Nov 28, 2019 |
| ASUSTek       | H97-PLUS                    | [115ab4a8a7](https://linux-hardware.org/?probe=115ab4a8a7) | Nov 28, 2019 |
| ASRock        | H61M-GS                     | [b0cff72d0c](https://linux-hardware.org/?probe=b0cff72d0c) | Nov 24, 2019 |
| iEi           | B202 V1.0                   | [16699afe19](https://linux-hardware.org/?probe=16699afe19) | Nov 13, 2019 |
| ASRock        | H61M-VG3                    | [6bc9ab22bf](https://linux-hardware.org/?probe=6bc9ab22bf) | Nov 11, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [a2fe589062](https://linux-hardware.org/?probe=a2fe589062) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [2e5a5d8827](https://linux-hardware.org/?probe=2e5a5d8827) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [616c5e7edb](https://linux-hardware.org/?probe=616c5e7edb) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [a5359e7def](https://linux-hardware.org/?probe=a5359e7def) | Oct 29, 2019 |
| Foxconn       | A6VMX 0A                    | [74249dc009](https://linux-hardware.org/?probe=74249dc009) | Oct 29, 2019 |
| iEi           | B202 V1.0                   | [bffdad4a05](https://linux-hardware.org/?probe=bffdad4a05) | Oct 26, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASRock        | H61M-VG3                    | [260918f990](https://linux-hardware.org/?probe=260918f990) | Oct 22, 2019 |
| Foxconn       | A6VMX 0A                    | [7991685c3a](https://linux-hardware.org/?probe=7991685c3a) | Oct 14, 2019 |
| Gigabyte      | X99-UD4-CF                  | [54db2b52da](https://linux-hardware.org/?probe=54db2b52da) | Oct 02, 2019 |
| Gigabyte      | H61M-DS2                    | [28b8e9271b](https://linux-hardware.org/?probe=28b8e9271b) | Sep 27, 2019 |
| Gigabyte      | H61M-DS2                    | [3cf419c507](https://linux-hardware.org/?probe=3cf419c507) | Sep 27, 2019 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [fbd6f89151](https://linux-hardware.org/?probe=fbd6f89151) | Sep 19, 2019 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [ff27a61c6c](https://linux-hardware.org/?probe=ff27a61c6c) | Sep 16, 2019 |
| ASUSTek       | V-P8H67E                    | [612c5f53a4](https://linux-hardware.org/?probe=612c5f53a4) | Sep 07, 2019 |
| ASUSTek       | V-P8H67E                    | [9f517e5081](https://linux-hardware.org/?probe=9f517e5081) | Aug 31, 2019 |
| ASRock        | A75M-HVS                    | [c5d625831f](https://linux-hardware.org/?probe=c5d625831f) | Aug 23, 2019 |
| Dell          | 0XCR8D A02                  | [ed9cabe6d7](https://linux-hardware.org/?probe=ed9cabe6d7) | Aug 16, 2019 |
| ASUSTek       | M2N-MX                      | [97e0e3e7ce](https://linux-hardware.org/?probe=97e0e3e7ce) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | [662d4876ce](https://linux-hardware.org/?probe=662d4876ce) | Aug 04, 2019 |
| Dell          | 0CRH6C A01                  | [1e288a14af](https://linux-hardware.org/?probe=1e288a14af) | Aug 03, 2019 |
| Fujitsu Si... | D2344-A3 S26361-D2344-A3    | [82e5d349d1](https://linux-hardware.org/?probe=82e5d349d1) | Jul 28, 2019 |
| HP            | 09F8h                       | [c52ee1274d](https://linux-hardware.org/?probe=c52ee1274d) | Jul 27, 2019 |
| Gigabyte      | C1037UN-EU                  | [6790768959](https://linux-hardware.org/?probe=6790768959) | Jul 20, 2019 |
| ASUSTek       | M4A78T-E                    | [607db49638](https://linux-hardware.org/?probe=607db49638) | Jun 22, 2019 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [d8c3110cba](https://linux-hardware.org/?probe=d8c3110cba) | Jun 22, 2019 |
| Gigabyte      | X99-UD4-CF                  | [dfc4a93cdf](https://linux-hardware.org/?probe=dfc4a93cdf) | Jun 21, 2019 |
| Foxconn       | 945 7MD Series              | [1acc3bbabb](https://linux-hardware.org/?probe=1acc3bbabb) | Jun 04, 2019 |
| Dell          | 0C27VV A03                  | [d78c1d6096](https://linux-hardware.org/?probe=d78c1d6096) | May 27, 2019 |
| Dell          | 0C27VV A03                  | [c8bb3e23f9](https://linux-hardware.org/?probe=c8bb3e23f9) | May 27, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [9ed71fdbcf](https://linux-hardware.org/?probe=9ed71fdbcf) | May 20, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [b18be16b85](https://linux-hardware.org/?probe=b18be16b85) | May 17, 2019 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [673c1426f0](https://linux-hardware.org/?probe=673c1426f0) | May 12, 2019 |
| ASUSTek       | M2N-X                       | [aa1ba4b47d](https://linux-hardware.org/?probe=aa1ba4b47d) | May 07, 2019 |
| HP            | 1906                        | [7ea8acd893](https://linux-hardware.org/?probe=7ea8acd893) | May 01, 2019 |
| Fujitsu       | D3004-A1 S26361-D3004-A1    | [17448d5b73](https://linux-hardware.org/?probe=17448d5b73) | Apr 29, 2019 |
| ASRock        | B150M Pro4                  | [8227df5ae7](https://linux-hardware.org/?probe=8227df5ae7) | Apr 13, 2019 |
| Dell          | 0K240Y A02                  | [e206f8f36e](https://linux-hardware.org/?probe=e206f8f36e) | Mar 25, 2019 |
| Wibtek        | H61-M HDMI2                 | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ASUSTek       | P5P43TD                     | [8d55cb4dca](https://linux-hardware.org/?probe=8d55cb4dca) | Feb 10, 2019 |
| ASRock        | Z97 Anniversary             | [672985bb0e](https://linux-hardware.org/?probe=672985bb0e) | Jan 26, 2019 |
| ASUSTek       | P5Q-PRO                     | [e74d60bf4b](https://linux-hardware.org/?probe=e74d60bf4b) | Jan 08, 2019 |
| ASUSTek       | P5Q-PRO                     | [f5081cb119](https://linux-hardware.org/?probe=f5081cb119) | Jan 08, 2019 |
| Acer          | Extensa X2610G              | [92c3e82d58](https://linux-hardware.org/?probe=92c3e82d58) | Jan 02, 2019 |
| ASRock        | B85M Pro3                   | [70f28e74b9](https://linux-hardware.org/?probe=70f28e74b9) | Dec 10, 2018 |
| ASRock        | Z370 Pro4                   | [7594332b68](https://linux-hardware.org/?probe=7594332b68) | Dec 02, 2018 |
| ASRock        | Z370 Pro4                   | [900f783b11](https://linux-hardware.org/?probe=900f783b11) | Dec 02, 2018 |
| ASRock        | B360M-HDV                   | [fb017cece0](https://linux-hardware.org/?probe=fb017cece0) | Nov 16, 2018 |
| ASRock        | Z77 Extreme3                | [a85b28c3f9](https://linux-hardware.org/?probe=a85b28c3f9) | Nov 15, 2018 |
| Gigabyte      | H81M-S2V                    | [801b3fb729](https://linux-hardware.org/?probe=801b3fb729) | Jun 27, 2018 |
| Gigabyte      | 970A-DS3P                   | [ee5ac544fa](https://linux-hardware.org/?probe=ee5ac544fa) | Feb 24, 2018 |
| Intel         | DH67GD AAG10206-208         | [fbd1d0b016](https://linux-hardware.org/?probe=fbd1d0b016) | Feb 23, 2018 |
| Acer          | Aspire XC-605               | [cbd8d79578](https://linux-hardware.org/?probe=cbd8d79578) | Jan 19, 2018 |
| Foxconn       | A6VMX 0A                    | [8ba0c7f4c3](https://linux-hardware.org/?probe=8ba0c7f4c3) | Dec 21, 2017 |
| Intel         | DH67GD AAG10206-208         | [9722b2d773](https://linux-hardware.org/?probe=9722b2d773) | Oct 31, 2017 |
| Intel         | DH67GD AAG10206-208         | [728c8e49b2](https://linux-hardware.org/?probe=728c8e49b2) | Oct 27, 2017 |
| ASUSTek       | Maximus IX HERO             | [8db3dd798e](https://linux-hardware.org/?probe=8db3dd798e) | Sep 05, 2017 |
| ASUSTek       | Maximus IX HERO             | [9f96da724a](https://linux-hardware.org/?probe=9f96da724a) | Sep 05, 2017 |
| Dell          | 0NKW6Y A00                  | [212f6d0514](https://linux-hardware.org/?probe=212f6d0514) | Sep 03, 2017 |
| Intel         | DH67GD AAG10206-208         | [0c3b83b208](https://linux-hardware.org/?probe=0c3b83b208) | Jun 06, 2017 |
| ASUSTek       | M4A78LT-M                   | [0a1b2311b5](https://linux-hardware.org/?probe=0a1b2311b5) | May 28, 2017 |
| Supermicro    | C2SBC-Q                     | [671517f196](https://linux-hardware.org/?probe=671517f196) | Apr 15, 2017 |
| ASRock        | H61M-GS                     | [5625f5be6e](https://linux-hardware.org/?probe=5625f5be6e) | Jan 30, 2017 |
| ASRock        | H61M-GS                     | [f309dd0e46](https://linux-hardware.org/?probe=f309dd0e46) | Jan 24, 2017 |
| ASRock        | H61M-GS                     | [eb755563bf](https://linux-hardware.org/?probe=eb755563bf) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 39       | 11.44%  |
| Ubuntu 18.04                 | 30       | 8.8%    |
| OpenMandriva 4.2             | 16       | 4.69%   |
| Ubuntu 22.04                 | 12       | 3.52%   |
| Debian 11                    | 12       | 3.52%   |
| ROSA R11                     | 8        | 2.35%   |
| ROSA R10                     | 8        | 2.35%   |
| Manjaro                      | 8        | 2.35%   |
| Ubuntu 20.10                 | 7        | 2.05%   |
| ArcoLinux Rolling            | 7        | 2.05%   |
| Arch                         | 7        | 2.05%   |
| Zorin 15                     | 6        | 1.76%   |
| Xubuntu 18.04                | 6        | 1.76%   |
| OpenMandriva 4.3             | 6        | 1.76%   |
| Linux Mint 20.1              | 6        | 1.76%   |
| KDE neon 20.04               | 5        | 1.47%   |
| Ubuntu 22.10                 | 4        | 1.17%   |
| Ubuntu 19.10                 | 4        | 1.17%   |
| Ubuntu 19.04                 | 4        | 1.17%   |
| Pop!_OS 21.10                | 4        | 1.17%   |
| Pop!_OS 20.10                | 4        | 1.17%   |
| Pop!_OS 20.04                | 4        | 1.17%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.17%   |
| Linux Mint 20                | 4        | 1.17%   |
| Linux Mint 19.3              | 4        | 1.17%   |
| Ubuntu 21.04                 | 3        | 0.88%   |
| Ubuntu 16.04                 | 3        | 0.88%   |
| ROSA R8.1                    | 3        | 0.88%   |
| OpenMandriva 4.50            | 3        | 0.88%   |
| LMDE 4                       | 3        | 0.88%   |
| Kubuntu 20.04                | 3        | 0.88%   |
| CentOS 9                     | 3        | 0.88%   |
| Arch Rolling                 | 3        | 0.88%   |
| Zorin 16                     | 2        | 0.59%   |
| Xubuntu 20.04                | 2        | 0.59%   |
| Ubuntu Unity 16.04           | 2        | 0.59%   |
| Ubuntu MATE 20.04            | 2        | 0.59%   |
| Ubuntu 21.10                 | 2        | 0.59%   |
| ROSA R11.1                   | 2        | 0.59%   |
| Pop!_OS 21.04                | 2        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 104      | 32.2%   |
| OpenMandriva  | 27       | 8.36%   |
| Linux Mint    | 21       | 6.5%    |
| ROSA          | 20       | 6.19%   |
| Manjaro       | 19       | 5.88%   |
| Debian        | 17       | 5.26%   |
| Pop!_OS       | 14       | 4.33%   |
| Xubuntu       | 10       | 3.1%    |
| Arch          | 10       | 3.1%    |
| Zorin         | 8        | 2.48%   |
| KDE neon      | 7        | 2.17%   |
| Fedora        | 7        | 2.17%   |
| ArcoLinux     | 7        | 2.17%   |
| Ubuntu Unity  | 6        | 1.86%   |
| Kubuntu       | 6        | 1.86%   |
| CentOS        | 5        | 1.55%   |
| openSUSE      | 4        | 1.24%   |
| Lubuntu       | 4        | 1.24%   |
| LMDE          | 3        | 0.93%   |
| Gentoo        | 3        | 0.93%   |
| Elementary    | 3        | 0.93%   |
| Ubuntu MATE   | 2        | 0.62%   |
| Endless       | 2        | 0.62%   |
| Clear Linux   | 2        | 0.62%   |
| Artix         | 2        | 0.62%   |
| Void Linux    | 1        | 0.31%   |
| Ubuntu Budgie | 1        | 0.31%   |
| Slackware     | 1        | 0.31%   |
| Q4OS          | 1        | 0.31%   |
| Parrot        | 1        | 0.31%   |
| Novos         | 1        | 0.31%   |
| Kali          | 1        | 0.31%   |
| EndeavourOS   | 1        | 0.31%   |
| Devuan        | 1        | 0.31%   |
| BlackPanther  | 1        | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 16       | 4.24%   |
| 5.4.0-42-generic                | 7        | 1.86%   |
| 5.3.0-40-generic                | 7        | 1.86%   |
| 5.16.7-desktop-1omv4003         | 6        | 1.59%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 6        | 1.59%   |
| 5.4.0-58-generic                | 5        | 1.33%   |
| 5.9.16-1-MANJARO                | 4        | 1.06%   |
| 5.8.0-43-generic                | 4        | 1.06%   |
| 5.11.0-27-generic               | 4        | 1.06%   |
| 5.10.0-8-amd64                  | 4        | 1.06%   |
| 5.8.0-7642-generic              | 3        | 0.8%    |
| 5.8.0-40-generic                | 3        | 0.8%    |
| 5.4.0-56-generic                | 3        | 0.8%    |
| 5.4.0-37-generic                | 3        | 0.8%    |
| 5.4.0-26-generic                | 3        | 0.8%    |
| 5.3.0-46-generic                | 3        | 0.8%    |
| 5.3.0-45-generic                | 3        | 0.8%    |
| 5.3.0-42-generic                | 3        | 0.8%    |
| 5.15.0-27-generic               | 3        | 0.8%    |
| 5.0.0-37-generic                | 3        | 0.8%    |
| 5.0.0-23-generic                | 3        | 0.8%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 0.8%    |
| 4.15.0-29-generic               | 3        | 0.8%    |
| 6.1.1-desktop-1omv2290          | 2        | 0.53%   |
| 5.8.11-1-MANJARO                | 2        | 0.53%   |
| 5.8.0-44-generic                | 2        | 0.53%   |
| 5.8.0-25-generic                | 2        | 0.53%   |
| 5.4.0-7634-generic              | 2        | 0.53%   |
| 5.4.0-67-generic                | 2        | 0.53%   |
| 5.4.0-66-generic                | 2        | 0.53%   |
| 5.4.0-65-generic                | 2        | 0.53%   |
| 5.4.0-59-generic                | 2        | 0.53%   |
| 5.4.0-49-generic                | 2        | 0.53%   |
| 5.4.0-48-generic                | 2        | 0.53%   |
| 5.4.0-40-generic                | 2        | 0.53%   |
| 5.4.0-29-generic                | 2        | 0.53%   |
| 5.19.0-23-generic               | 2        | 0.53%   |
| 5.15.0-48-generic               | 2        | 0.53%   |
| 5.15.0-46-generic               | 2        | 0.53%   |
| 5.15.0-43-generic               | 2        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 14.29%  |
| 4.15.0  | 32       | 8.96%   |
| 5.8.0   | 22       | 6.16%   |
| 5.3.0   | 18       | 5.04%   |
| 5.15.0  | 17       | 4.76%   |
| 5.10.14 | 16       | 4.48%   |
| 5.11.0  | 14       | 3.92%   |
| 5.0.0   | 14       | 3.92%   |
| 5.10.0  | 12       | 3.36%   |
| 5.13.0  | 7        | 1.96%   |
| 4.18.0  | 7        | 1.96%   |
| 5.16.7  | 6        | 1.68%   |
| 5.19.0  | 5        | 1.4%    |
| 5.9.16  | 4        | 1.12%   |
| 4.19.0  | 4        | 1.12%   |
| 6.1.1   | 3        | 0.84%   |
| 5.14.0  | 3        | 0.84%   |
| 4.9.60  | 3        | 0.84%   |
| 4.9.20  | 3        | 0.84%   |
| 6.0.0   | 2        | 0.56%   |
| 5.8.18  | 2        | 0.56%   |
| 5.8.11  | 2        | 0.56%   |
| 5.7.7   | 2        | 0.56%   |
| 5.7.6   | 2        | 0.56%   |
| 5.6.0   | 2        | 0.56%   |
| 5.3.16  | 2        | 0.56%   |
| 5.3.14  | 2        | 0.56%   |
| 5.17.6  | 2        | 0.56%   |
| 5.17.5  | 2        | 0.56%   |
| 5.17.11 | 2        | 0.56%   |
| 5.16.15 | 2        | 0.56%   |
| 5.16.11 | 2        | 0.56%   |
| 5.15.6  | 2        | 0.56%   |
| 5.12.4  | 2        | 0.56%   |
| 5.11.11 | 2        | 0.56%   |
| 5.10.79 | 2        | 0.56%   |
| 5.10.16 | 2        | 0.56%   |
| 4.9.76  | 2        | 0.56%   |
| 4.9.124 | 2        | 0.56%   |
| 4.4.0   | 2        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 54       | 15.43%  |
| 5.10    | 40       | 11.43%  |
| 4.15    | 32       | 9.14%   |
| 5.8     | 28       | 8%      |
| 5.15    | 25       | 7.14%   |
| 5.3     | 22       | 6.29%   |
| 5.11    | 20       | 5.71%   |
| 5.16    | 14       | 4%      |
| 5.0     | 14       | 4%      |
| 5.19    | 10       | 2.86%   |
| 4.9     | 10       | 2.86%   |
| 5.17    | 8        | 2.29%   |
| 5.13    | 8        | 2.29%   |
| 4.18    | 7        | 2%      |
| 5.7     | 6        | 1.71%   |
| 5.14    | 6        | 1.71%   |
| 6.1     | 5        | 1.43%   |
| 5.9     | 5        | 1.43%   |
| 5.6     | 5        | 1.43%   |
| 6.0     | 4        | 1.14%   |
| 5.2     | 4        | 1.14%   |
| 5.12    | 4        | 1.14%   |
| 4.19    | 4        | 1.14%   |
| 5.18    | 3        | 0.86%   |
| 4.1     | 3        | 0.86%   |
| 4.4     | 2        | 0.57%   |
| 3.10    | 2        | 0.57%   |
| 5.5     | 1        | 0.29%   |
| 4.7     | 1        | 0.29%   |
| 4.20    | 1        | 0.29%   |
| 4.10    | 1        | 0.29%   |
| Unknown | 1        | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 301      | 98.37%  |
| i686   | 5        | 1.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 114      | 34.44%  |
| KDE5            | 60       | 18.13%  |
| Unknown         | 50       | 15.11%  |
| XFCE            | 24       | 7.25%   |
| X-Cinnamon      | 17       | 5.14%   |
| KDE4            | 15       | 4.53%   |
| MATE            | 12       | 3.63%   |
| KDE             | 11       | 3.32%   |
| Unity           | 6        | 1.81%   |
| LXQt            | 4        | 1.21%   |
| Pantheon        | 3        | 0.91%   |
| Cinnamon        | 3        | 0.91%   |
| GNOME Flashback | 2        | 0.6%    |
| Budgie          | 2        | 0.6%    |
| bspwm           | 2        | 0.6%    |
| xmonad          | 1        | 0.3%    |
| trinity         | 1        | 0.3%    |
| qtile           | 1        | 0.3%    |
| i3              | 1        | 0.3%    |
| DWM             | 1        | 0.3%    |
| awesome         | 1        | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 264      | 83.81%  |
| Wayland | 25       | 7.94%   |
| Unknown | 19       | 6.03%   |
| Tty     | 7        | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 166      | 51.88%  |
| SDDM    | 61       | 19.06%  |
| GDM3    | 25       | 7.81%   |
| LightDM | 21       | 6.56%   |
| GDM     | 18       | 5.63%   |
| KDM     | 15       | 4.69%   |
| TDM     | 14       | 4.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 172      | 54.09%  |
| bg_BG   | 65       | 20.44%  |
| Unknown | 56       | 17.61%  |
| C       | 8        | 2.52%   |
| en_GB   | 6        | 1.89%   |
| de_DE   | 5        | 1.57%   |
| ru_UA   | 1        | 0.31%   |
| ru_RU   | 1        | 0.31%   |
| POSIX   | 1        | 0.31%   |
| it_IT   | 1        | 0.31%   |
| Default | 1        | 0.31%   |
| C.UTF8  | 1        | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 210      | 66.67%  |
| EFI  | 105      | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 235      | 73.21%  |
| Overlay | 31       | 9.66%   |
| Unknown | 22       | 6.85%   |
| Btrfs   | 19       | 5.92%   |
| Xfs     | 6        | 1.87%   |
| Zfs     | 4        | 1.25%   |
| Ext3    | 2        | 0.62%   |
| Tmpfs   | 1        | 0.31%   |
| Jfs     | 1        | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 172      | 54.6%   |
| GPT     | 93       | 29.52%  |
| MBR     | 50       | 15.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 251      | 78.68%  |
| Yes       | 68       | 21.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 203      | 65.06%  |
| Yes       | 109      | 34.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 83       | 27.12%  |
| ASRock              | 59       | 19.28%  |
| Gigabyte Technology | 46       | 15.03%  |
| Hewlett-Packard     | 20       | 6.54%   |
| MSI                 | 19       | 6.21%   |
| Dell                | 17       | 5.56%   |
| Lenovo              | 16       | 5.23%   |
| Fujitsu             | 10       | 3.27%   |
| Intel               | 8        | 2.61%   |
| Foxconn             | 5        | 1.63%   |
| Acer                | 4        | 1.31%   |
| Unknown             | 4        | 1.31%   |
| Wibtek              | 2        | 0.65%   |
| Pegatron            | 2        | 0.65%   |
| Fujitsu Siemens     | 2        | 0.65%   |
| Thecus              | 1        | 0.33%   |
| Supermicro          | 1        | 0.33%   |
| Shuttle             | 1        | 0.33%   |
| Seco                | 1        | 0.33%   |
| Packard Bell        | 1        | 0.33%   |
| MiTAC               | 1        | 0.33%   |
| iEi                 | 1        | 0.33%   |
| ECS                 | 1        | 0.33%   |
| BESSTAR Tech        | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 6        | 1.96%   |
| Lenovo H520S 2561                  | 4        | 1.31%   |
| Unknown                            | 4        | 1.31%   |
| ASRock Z97 Anniversary             | 3        | 0.98%   |
| Wibtek H61-M HDMI2                 | 2        | 0.65%   |
| MSI MS-7C56                        | 2        | 0.65%   |
| MSI MS-7C37                        | 2        | 0.65%   |
| Lenovo H520e 10159                 | 2        | 0.65%   |
| HP Compaq 6005 Pro SFF PC          | 2        | 0.65%   |
| Gigabyte X99-UD4-CF                | 2        | 0.65%   |
| Gigabyte H370AORUSGAMING3WIFI      | 2        | 0.65%   |
| Gigabyte B450 AORUS M              | 2        | 0.65%   |
| Fujitsu ESPRIMO P710               | 2        | 0.65%   |
| Foxconn 500B Microtower            | 2        | 0.65%   |
| Dell Precision Tower 5810          | 2        | 0.65%   |
| Dell OptiPlex 790                  | 2        | 0.65%   |
| Dell OptiPlex 780                  | 2        | 0.65%   |
| ASUS PRIME X570-P                  | 2        | 0.65%   |
| ASUS P5Q-PRO                       | 2        | 0.65%   |
| ASUS P5KC                          | 2        | 0.65%   |
| ASUS P5G41T-M LX                   | 2        | 0.65%   |
| ASRock X570 Phantom Gaming 4       | 2        | 0.65%   |
| ASRock H110M-HDV                   | 2        | 0.65%   |
| ASRock H110M-DGS                   | 2        | 0.65%   |
| ASRock G41M-S3                     | 2        | 0.65%   |
| ASRock B450M-HDV R4.0              | 2        | 0.65%   |
| ASRock B450M Steel Legend          | 2        | 0.65%   |
| ASRock 890GX Extreme3              | 2        | 0.65%   |
| Thecus N2810                       | 1        | 0.33%   |
| Supermicro C2SBC-Q                 | 1        | 0.33%   |
| Shuttle XH81V                      | 1        | 0.33%   |
| Seco C40                           | 1        | 0.33%   |
| Pegatron Compaq 505B Microtower PC | 1        | 0.33%   |
| Pegatron 520-1030uk                | 1        | 0.33%   |
| Packard Bell IMEDIA S2185          | 1        | 0.33%   |
| MSI Pentino G-Series MT            | 1        | 0.33%   |
| MSI MS-7D59                        | 1        | 0.33%   |
| MSI MS-7C84                        | 1        | 0.33%   |
| MSI MS-7C35                        | 1        | 0.33%   |
| MSI MS-7C09                        | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| HP Compaq                     | 13       | 4.25%   |
| ASUS PRIME                    | 11       | 3.59%   |
| Dell OptiPlex                 | 10       | 3.27%   |
| Fujitsu ESPRIMO               | 8        | 2.61%   |
| Lenovo ThinkCentre            | 7        | 2.29%   |
| ASUS ROG                      | 6        | 1.96%   |
| ASUS All                      | 6        | 1.96%   |
| Lenovo H520S                  | 4        | 1.31%   |
| Dell Precision                | 4        | 1.31%   |
| ASUS P5K                      | 4        | 1.31%   |
| ASRock X570                   | 4        | 1.31%   |
| Unknown                       | 4        | 1.31%   |
| Gigabyte X570                 | 3        | 0.98%   |
| ASUS TUF                      | 3        | 0.98%   |
| ASRock Z97                    | 3        | 0.98%   |
| Wibtek H61-M                  | 2        | 0.65%   |
| MSI MS-7C56                   | 2        | 0.65%   |
| MSI MS-7C37                   | 2        | 0.65%   |
| Lenovo ThinkStation           | 2        | 0.65%   |
| Lenovo H520e                  | 2        | 0.65%   |
| Intel X99                     | 2        | 0.65%   |
| HP ProDesk                    | 2        | 0.65%   |
| Gigabyte Z490                 | 2        | 0.65%   |
| Gigabyte X99-UD4-CF           | 2        | 0.65%   |
| Gigabyte H370AORUSGAMING3WIFI | 2        | 0.65%   |
| Gigabyte B450                 | 2        | 0.65%   |
| Foxconn 500B                  | 2        | 0.65%   |
| Dell Vostro                   | 2        | 0.65%   |
| ASUS SABERTOOTH               | 2        | 0.65%   |
| ASUS P8H61-M                  | 2        | 0.65%   |
| ASUS P5Q-PRO                  | 2        | 0.65%   |
| ASUS P5P43TD                  | 2        | 0.65%   |
| ASUS P5KPL-AM                 | 2        | 0.65%   |
| ASUS P5KC                     | 2        | 0.65%   |
| ASUS P5G41T-M                 | 2        | 0.65%   |
| ASUS M2N-MX                   | 2        | 0.65%   |
| ASRock H81M-ITX               | 2        | 0.65%   |
| ASRock H110M-HDV              | 2        | 0.65%   |
| ASRock H110M-DGS              | 2        | 0.65%   |
| ASRock G41M-S3                | 2        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 31       | 10.13%  |
| 2011 | 30       | 9.8%    |
| 2012 | 28       | 9.15%   |
| 2018 | 23       | 7.52%   |
| 2014 | 23       | 7.52%   |
| 2019 | 21       | 6.86%   |
| 2017 | 21       | 6.86%   |
| 2007 | 19       | 6.21%   |
| 2009 | 18       | 5.88%   |
| 2010 | 17       | 5.56%   |
| 2008 | 15       | 4.9%    |
| 2015 | 14       | 4.58%   |
| 2020 | 13       | 4.25%   |
| 2021 | 12       | 3.92%   |
| 2016 | 9        | 2.94%   |
| 2006 | 8        | 2.61%   |
| 2005 | 3        | 0.98%   |
| 2022 | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 306      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 301      | 98.05%  |
| Enabled  | 6        | 1.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 306      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 62       | 19.5%   |
| 16.01-24.0  | 62       | 19.5%   |
| 4.01-8.0    | 59       | 18.55%  |
| 8.01-16.0   | 57       | 17.92%  |
| 32.01-64.0  | 34       | 10.69%  |
| 1.01-2.0    | 12       | 3.77%   |
| 24.01-32.0  | 11       | 3.46%   |
| 64.01-256.0 | 11       | 3.46%   |
| 2.01-3.0    | 9        | 2.83%   |
| 0.51-1.0    | 1        | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 115      | 33.05%  |
| 2.01-3.0   | 89       | 25.57%  |
| 3.01-4.0   | 47       | 13.51%  |
| 4.01-8.0   | 45       | 12.93%  |
| 0.51-1.0   | 35       | 10.06%  |
| 8.01-16.0  | 12       | 3.45%   |
| 0.01-0.5   | 3        | 0.86%   |
| 24.01-32.0 | 1        | 0.29%   |
| 16.01-24.0 | 1        | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 128      | 39.75%  |
| 2      | 102      | 31.68%  |
| 3      | 42       | 13.04%  |
| 4      | 18       | 5.59%   |
| 5      | 16       | 4.97%   |
| 6      | 8        | 2.48%   |
| 8      | 2        | 0.62%   |
| 7      | 2        | 0.62%   |
| 0      | 2        | 0.62%   |
| 11     | 1        | 0.31%   |
| 9      | 1        | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 159      | 50.48%  |
| No        | 156      | 49.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 304      | 99.35%  |
| No        | 2        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 229      | 73.63%  |
| Yes       | 82       | 26.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 244      | 78.21%  |
| Yes       | 68       | 21.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Bulgaria | 306      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sofia          | 142      | 44.51%  |
| Varna          | 25       | 7.84%   |
| Plovdiv        | 22       | 6.9%    |
| Stara Zagora   | 10       | 3.13%   |
| Rousse         | 10       | 3.13%   |
| Burgas         | 10       | 3.13%   |
| Pernik         | 7        | 2.19%   |
| Sliven         | 6        | 1.88%   |
| Veliko Tarnovo | 4        | 1.25%   |
| Shumen         | 4        | 1.25%   |
| Haskovo        | 4        | 1.25%   |
| Asenovgrad     | 4        | 1.25%   |
| Razgrad        | 3        | 0.94%   |
| Pleven         | 3        | 0.94%   |
| Kazanlak       | 3        | 0.94%   |
| Gabrovo        | 3        | 0.94%   |
| Dobrich        | 3        | 0.94%   |
| Vidin          | 2        | 0.63%   |
| Targovishte    | 2        | 0.63%   |
| Sistov         | 2        | 0.63%   |
| Novi Pazar     | 2        | 0.63%   |
| Novi Iskar     | 2        | 0.63%   |
| Montana        | 2        | 0.63%   |
| Kyustendil     | 2        | 0.63%   |
| Krumovgrad     | 2        | 0.63%   |
| Cherven        | 2        | 0.63%   |
| Blagoevgrad    | 2        | 0.63%   |
| Zlatitsa       | 1        | 0.31%   |
| Vratsa         | 1        | 0.31%   |
| Voysil         | 1        | 0.31%   |
| Velingrad      | 1        | 0.31%   |
| Tvarditsa      | 1        | 0.31%   |
| Toros          | 1        | 0.31%   |
| Svoge          | 1        | 0.31%   |
| Smolyan        | 1        | 0.31%   |
| Slatina        | 1        | 0.31%   |
| Slashten       | 1        | 0.31%   |
| Silistra       | 1        | 0.31%   |
| Septemvri      | 1        | 0.31%   |
| Saedinenie     | 1        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| Seagate                 | 110      | 183    | 19.75%  |
| WDC                     | 100      | 164    | 17.95%  |
| Samsung Electronics     | 74       | 109    | 13.29%  |
| Hitachi                 | 44       | 66     | 7.9%    |
| Toshiba                 | 36       | 50     | 6.46%   |
| Kingston                | 36       | 55     | 6.46%   |
| A-DATA Technology       | 25       | 32     | 4.49%   |
| Team                    | 13       | 14     | 2.33%   |
| Intel                   | 12       | 16     | 2.15%   |
| SanDisk                 | 9        | 10     | 1.62%   |
| Crucial                 | 9        | 17     | 1.62%   |
| SPCC                    | 8        | 9      | 1.44%   |
| Phison                  | 7        | 7      | 1.26%   |
| China                   | 7        | 9      | 1.26%   |
| HGST                    | 6        | 11     | 1.08%   |
| Patriot                 | 5        | 6      | 0.9%    |
| Maxtor                  | 5        | 9      | 0.9%    |
| XPG                     | 4        | 6      | 0.72%   |
| Realtek Semiconductor   | 4        | 5      | 0.72%   |
| Unknown                 | 3        | 6      | 0.54%   |
| Silicon Motion          | 3        | 6      | 0.54%   |
| KIOXIA                  | 3        | 3      | 0.54%   |
| KingSpec                | 3        | 3      | 0.54%   |
| JMicron Technology      | 3        | 4      | 0.54%   |
| Intenso                 | 3        | 3      | 0.54%   |
| ExcelStor               | 3        | 7      | 0.54%   |
| OCZ                     | 2        | 2      | 0.36%   |
| AMD                     | 2        | 3      | 0.36%   |
| Verbatim                | 1        | 1      | 0.18%   |
| Union Memory (Shenzhen) | 1        | 4      | 0.18%   |
| Transcend               | 1        | 2      | 0.18%   |
| TO Exter                | 1        | 1      | 0.18%   |
| OCZ-VERTEX3             | 1        | 1      | 0.18%   |
| Micron Technology       | 1        | 1      | 0.18%   |
| LITEON                  | 1        | 1      | 0.18%   |
| Innodisk                | 1        | 1      | 0.18%   |
| HS-SSD-C100             | 1        | 1      | 0.18%   |
| HPE                     | 1        | 1      | 0.18%   |
| HGST HTS                | 1        | 1      | 0.18%   |
| Hewlett-Packard         | 1        | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB        | 16       | 2.48%   |
| Kingston SA400S37120G 120GB SSD        | 10       | 1.55%   |
| Seagate ST1000DM010-2EP102 1TB         | 9        | 1.39%   |
| Toshiba DT01ACA100 1TB                 | 8        | 1.24%   |
| Seagate ST1000DM003-1ER162 1TB         | 7        | 1.08%   |
| Samsung NVMe SSD Drive 500GB           | 7        | 1.08%   |
| Kingston SA400S37480G 480GB SSD        | 7        | 1.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 6        | 0.93%   |
| Toshiba DT01ACA050 500GB               | 6        | 0.93%   |
| Samsung SSD 850 EVO 250GB              | 6        | 0.93%   |
| Kingston SV300S37A120G 120GB SSD       | 6        | 0.93%   |
| Toshiba HDWD110 1TB                    | 5        | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB         | 5        | 0.77%   |
| Samsung SSD 970 EVO Plus 500GB         | 5        | 0.77%   |
| Samsung SSD 860 EVO 250GB              | 5        | 0.77%   |
| Samsung SSD 860 EVO 1TB                | 5        | 0.77%   |
| Samsung SSD 850 PRO 256GB              | 5        | 0.77%   |
| Hitachi HDS721050CLA362 500GB          | 5        | 0.77%   |
| Hitachi HDP725050GLA360 500GB          | 5        | 0.77%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 4        | 0.62%   |
| Toshiba DT01ACA200 2TB                 | 4        | 0.62%   |
| Seagate ST3500413AS 500GB              | 4        | 0.62%   |
| Seagate ST3250312AS 250GB              | 4        | 0.62%   |
| Seagate ST3160815AS 160GB              | 4        | 0.62%   |
| Samsung SSD 970 EVO 250GB              | 4        | 0.62%   |
| Samsung SSD 860 EVO 500GB              | 4        | 0.62%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 4        | 0.62%   |
| Kingston SA400S37240G 240GB SSD        | 4        | 0.62%   |
| Hitachi HDS721616PLA380 160GB          | 4        | 0.62%   |
| A-DATA SU650 240GB SSD                 | 4        | 0.62%   |
| A-DATA SU650 120GB SSD                 | 4        | 0.62%   |
| XPG NVMe SSD Drive 512GB               | 3        | 0.46%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 3        | 0.46%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 3        | 0.46%   |
| WDC WD2002FAEX-007BA0 2TB              | 3        | 0.46%   |
| WDC WD10EZEX-22BN5A0 1TB               | 3        | 0.46%   |
| WDC WD10EZEX-00WN4A0 1TB               | 3        | 0.46%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 3        | 0.46%   |
| Team T253X2256G 256GB SSD              | 3        | 0.46%   |
| SPCC Solid State Disk 512GB            | 3        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 109      | 180    | 35.97%  |
| WDC                 | 94       | 151    | 31.02%  |
| Hitachi             | 44       | 66     | 14.52%  |
| Toshiba             | 32       | 46     | 10.56%  |
| Samsung Electronics | 6        | 8      | 1.98%   |
| HGST                | 6        | 11     | 1.98%   |
| Maxtor              | 5        | 9      | 1.65%   |
| ExcelStor           | 3        | 7      | 0.99%   |
| JMicron Technology  | 1        | 2      | 0.33%   |
| HGST HTS            | 1        | 1      | 0.33%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| ASMedia             | 1        | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 43       | 55     | 22.63%  |
| Kingston            | 33       | 47     | 17.37%  |
| A-DATA Technology   | 23       | 28     | 12.11%  |
| Team                | 13       | 14     | 6.84%   |
| Intel               | 9        | 13     | 4.74%   |
| Crucial             | 9        | 17     | 4.74%   |
| SPCC                | 8        | 9      | 4.21%   |
| WDC                 | 7        | 10     | 3.68%   |
| SanDisk             | 7        | 8      | 3.68%   |
| China               | 7        | 9      | 3.68%   |
| Patriot             | 5        | 6      | 2.63%   |
| KingSpec            | 3        | 3      | 1.58%   |
| Intenso             | 3        | 3      | 1.58%   |
| Toshiba             | 2        | 2      | 1.05%   |
| OCZ                 | 2        | 2      | 1.05%   |
| JMicron Technology  | 2        | 2      | 1.05%   |
| AMD                 | 2        | 3      | 1.05%   |
| Verbatim            | 1        | 1      | 0.53%   |
| Transcend           | 1        | 2      | 0.53%   |
| TO Exter            | 1        | 1      | 0.53%   |
| Seagate             | 1        | 2      | 0.53%   |
| OCZ-VERTEX3         | 1        | 1      | 0.53%   |
| LITEON              | 1        | 1      | 0.53%   |
| HS-SSD-C100         | 1        | 1      | 0.53%   |
| HPE                 | 1        | 1      | 0.53%   |
| Gigabyte Technology | 1        | 8      | 0.53%   |
| Emtec               | 1        | 1      | 0.53%   |
| Corsair             | 1        | 1      | 0.53%   |
| ATP                 | 1        | 2      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 239      | 483    | 51.29%  |
| SSD     | 157      | 253    | 33.69%  |
| NVMe    | 65       | 102    | 13.95%  |
| Unknown | 3        | 5      | 0.64%   |
| MMC     | 2        | 2      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 291      | 727    | 79.08%  |
| NVMe | 65       | 102    | 17.66%  |
| SAS  | 10       | 14     | 2.72%   |
| MMC  | 2        | 2      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 239      | 435    | 58.29%  |
| 0.51-1.0   | 109      | 190    | 26.59%  |
| 1.01-2.0   | 29       | 45     | 7.07%   |
| 3.01-4.0   | 13       | 29     | 3.17%   |
| 2.01-3.0   | 10       | 17     | 2.44%   |
| 4.01-10.0  | 6        | 8      | 1.46%   |
| 10.01-20.0 | 4        | 12     | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 81       | 24.62%  |
| 251-500        | 58       | 17.63%  |
| 501-1000       | 44       | 13.37%  |
| 1001-2000      | 36       | 10.94%  |
| 1-20           | 33       | 10.03%  |
| 51-100         | 23       | 6.99%   |
| More than 3000 | 21       | 6.38%   |
| Unknown        | 13       | 3.95%   |
| 2001-3000      | 12       | 3.65%   |
| 21-50          | 8        | 2.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 140      | 40.46%  |
| 21-50          | 44       | 12.72%  |
| 101-250        | 37       | 10.69%  |
| 51-100         | 36       | 10.4%   |
| 501-1000       | 26       | 7.51%   |
| 251-500        | 18       | 5.2%    |
| 1001-2000      | 18       | 5.2%    |
| Unknown        | 13       | 3.76%   |
| More than 3000 | 9        | 2.6%    |
| 2001-3000      | 5        | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD6000HLHX-01JJPV0 600GB          | 2        | 3      | 3.51%   |
| WDC WD5000AAKX-603CA0 500GB           | 2        | 6      | 3.51%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 3.51%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 2      | 3.51%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 2      | 1.75%   |
| WDC WD5000AACS-00G8B1 500GB           | 1        | 1      | 1.75%   |
| WDC WD40PURX-64GVNY0 4TB              | 1        | 1      | 1.75%   |
| WDC WD3200AAJS-07M0A0 320GB           | 1        | 2      | 1.75%   |
| WDC WD2500JS-00MHB0 250GB             | 1        | 1      | 1.75%   |
| WDC WD2500AAKX-753CA1 250GB           | 1        | 1      | 1.75%   |
| WDC WD15EARS-00S8B1 1TB               | 1        | 1      | 1.75%   |
| WDC WD10EFRX-68PJCN0 1TB              | 1        | 1      | 1.75%   |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 1.75%   |
| Toshiba MK3252GSX 320GB               | 1        | 1      | 1.75%   |
| Toshiba DT01ACA300 3TB                | 1        | 1      | 1.75%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 1.75%   |
| Seagate ST380215A 80GB                | 1        | 1      | 1.75%   |
| Seagate ST3500830AS 500GB             | 1        | 1      | 1.75%   |
| Seagate ST3320311CS 320GB             | 1        | 1      | 1.75%   |
| Seagate ST3300631AS 304GB             | 1        | 1      | 1.75%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 1.75%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 1.75%   |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 1      | 1.75%   |
| SanDisk SDSSDX480GG25 480GB           | 1        | 1      | 1.75%   |
| SanDisk SDSSDH3250G 250GB             | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 1.75%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 1.75%   |
| Patriot P200 512GB SSD                | 1        | 1      | 1.75%   |
| Maxtor 6Y160M0 160GB                  | 1        | 1      | 1.75%   |
| Maxtor 6L080P0 81GB                   | 1        | 1      | 1.75%   |
| Maxtor 2F040L0 41GB                   | 1        | 1      | 1.75%   |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 1.75%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 1.75%   |
| Kingston SUV500240G 240GB SSD         | 1        | 1      | 1.75%   |
| Kingston SA400S37480G 480GB SSD       | 1        | 1      | 1.75%   |
| KingSpec P3-128 128GB SSD             | 1        | 1      | 1.75%   |
| Intel SSDSC2BW480A4 480GB             | 1        | 2      | 1.75%   |
| Intel SSDSC2BW240H6 240GB             | 1        | 1      | 1.75%   |
| Intel SSDSC2BW120A3F 120GB            | 1        | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 20     | 22.81%  |
| Seagate             | 11       | 11     | 19.3%   |
| Hitachi             | 5        | 5      | 8.77%   |
| A-DATA Technology   | 5        | 5      | 8.77%   |
| Kingston            | 4        | 4      | 7.02%   |
| Toshiba             | 3        | 3      | 5.26%   |
| Samsung Electronics | 3        | 4      | 5.26%   |
| Maxtor              | 3        | 3      | 5.26%   |
| Intel               | 3        | 4      | 5.26%   |
| SanDisk             | 2        | 2      | 3.51%   |
| ExcelStor           | 2        | 3      | 3.51%   |
| Patriot             | 1        | 1      | 1.75%   |
| KingSpec            | 1        | 1      | 1.75%   |
| China               | 1        | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 13       | 20     | 35.14%  |
| Seagate   | 11       | 11     | 29.73%  |
| Hitachi   | 5        | 5      | 13.51%  |
| Toshiba   | 3        | 3      | 8.11%   |
| Maxtor    | 3        | 3      | 8.11%   |
| ExcelStor | 2        | 3      | 5.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 45     | 64.81%  |
| SSD  | 17       | 19     | 31.48%  |
| NVMe | 2        | 3      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD7500BPVT-22HXZT3 752GB | 1        | 1      | 100%    |

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
| Detected | 190      | 511    | 53.07%  |
| Works    | 118      | 266    | 32.96%  |
| Malfunc  | 49       | 67     | 13.69%  |
| Failed   | 1        | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 200      | 47.73%  |
| AMD                           | 91       | 21.72%  |
| Samsung Electronics           | 37       | 8.83%   |
| JMicron Technology            | 17       | 4.06%   |
| Nvidia                        | 15       | 3.58%   |
| ASMedia Technology            | 11       | 2.63%   |
| ADATA Technology              | 8        | 1.91%   |
| Phison Electronics            | 7        | 1.67%   |
| Marvell Technology Group      | 7        | 1.67%   |
| Realtek Semiconductor         | 5        | 1.19%   |
| SanDisk                       | 4        | 0.95%   |
| Silicon Motion                | 3        | 0.72%   |
| KIOXIA                        | 3        | 0.72%   |
| Kingston Technology Company   | 3        | 0.72%   |
| Toshiba America Info Systems  | 2        | 0.48%   |
| VIA Technologies              | 1        | 0.24%   |
| Union Memory (Shenzhen)       | 1        | 0.24%   |
| Micron Technology             | 1        | 0.24%   |
| Integrated Technology Express | 1        | 0.24%   |
| Hewlett-Packard               | 1        | 0.24%   |
| Chelsio Communications        | 1        | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 51       | 9.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25       | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 25       | 4.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 3.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15       | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 2.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 2.53%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 2.17%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 11       | 1.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 1.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 1.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 1.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.81%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 1.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8        | 1.44%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 1.44%   |
| Nvidia MCP61 IDE                                                                        | 7        | 1.26%   |
| JMicron JMB368 IDE controller                                                           | 7        | 1.26%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7        | 1.26%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.26%   |
| AMD FCH IDE Controller                                                                  | 6        | 1.08%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.72%   |
| Realtek Realtek Non-Volatile memory controller                                          | 4        | 0.72%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.72%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 4        | 0.72%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 4        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 224      | 53.85%  |
| IDE  | 108      | 25.96%  |
| NVMe | 66       | 15.87%  |
| RAID | 15       | 3.61%   |
| SAS  | 2        | 0.48%   |
| SCSI | 1        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 198      | 64.71%  |
| AMD    | 108      | 35.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.62%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.62%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 1.62%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 4        | 1.29%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 4        | 1.29%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 1.29%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.29%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.29%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.29%   |
| AMD FX-6300 Six-Core Processor              | 4        | 1.29%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.97%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.97%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 0.97%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.97%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 0.97%   |
| AMD Athlon II X2 250 Processor              | 3        | 0.97%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 2        | 0.65%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 0.65%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.65%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.65%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.65%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.65%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.65%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.65%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2        | 0.65%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.65%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 2        | 0.65%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.65%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 54       | 17.48%  |
| Intel Core i7           | 27       | 8.74%   |
| Intel Core i3           | 24       | 7.77%   |
| AMD Ryzen 5             | 21       | 6.8%    |
| Intel Xeon              | 18       | 5.83%   |
| Intel Core 2 Duo        | 15       | 4.85%   |
| Intel Celeron           | 14       | 4.53%   |
| Intel Pentium           | 12       | 3.88%   |
| Intel Core 2 Quad       | 12       | 3.88%   |
| AMD Ryzen 7             | 12       | 3.88%   |
| AMD Athlon 64 X2        | 10       | 3.24%   |
| AMD FX                  | 9        | 2.91%   |
| AMD Ryzen 9             | 7        | 2.27%   |
| Intel Pentium Dual-Core | 6        | 1.94%   |
| Other                   | 5        | 1.62%   |
| AMD Phenom II X4        | 5        | 1.62%   |
| AMD Athlon II X2        | 5        | 1.62%   |
| AMD Athlon 64           | 5        | 1.62%   |
| AMD A8                  | 5        | 1.62%   |
| Intel Pentium Dual      | 4        | 1.29%   |
| Intel Core i9           | 3        | 0.97%   |
| AMD Ryzen 3             | 3        | 0.97%   |
| AMD Athlon II X4        | 3        | 0.97%   |
| Intel Pentium Gold      | 2        | 0.65%   |
| Intel Core 2            | 2        | 0.65%   |
| AMD Sempron             | 2        | 0.65%   |
| AMD Ryzen 7 PRO         | 2        | 0.65%   |
| AMD Ryzen 5 PRO         | 2        | 0.65%   |
| AMD Phenom II X6        | 2        | 0.65%   |
| AMD Phenom II X2        | 2        | 0.65%   |
| AMD Phenom              | 2        | 0.65%   |
| AMD Athlon X4           | 2        | 0.65%   |
| Intel Pentium D         | 1        | 0.32%   |
| Intel Atom              | 1        | 0.32%   |
| AMD Ryzen Threadripper  | 1        | 0.32%   |
| AMD Ryzen Embedded      | 1        | 0.32%   |
| AMD Phenom II X3        | 1        | 0.32%   |
| AMD GX                  | 1        | 0.32%   |
| AMD E1                  | 1        | 0.32%   |
| AMD Athlon II X3        | 1        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 107      | 34.63%  |
| 2       | 107      | 34.63%  |
| 6       | 40       | 12.94%  |
| 8       | 22       | 7.12%   |
| 12      | 9        | 2.91%   |
| 1       | 9        | 2.91%   |
| 3       | 8        | 2.59%   |
| 16      | 3        | 0.97%   |
| 18      | 1        | 0.32%   |
| 14      | 1        | 0.32%   |
| 10      | 1        | 0.32%   |
| Unknown | 1        | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 304      | 99.35%  |
| 2      | 2        | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 170      | 55.02%  |
| 2       | 138      | 44.66%  |
| Unknown | 1        | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 302      | 97.73%  |
| Unknown        | 7        | 2.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 27.64%  |
| 0x306c3    | 27       | 8.39%   |
| 0x206a7    | 22       | 6.83%   |
| 0x306a9    | 16       | 4.97%   |
| 0x1067a    | 14       | 4.35%   |
| 0x506e3    | 13       | 4.04%   |
| 0x010000c8 | 10       | 3.11%   |
| 0x906ea    | 8        | 2.48%   |
| 0x906e9    | 7        | 2.17%   |
| 0x6fb      | 7        | 2.17%   |
| 0x6fd      | 6        | 1.86%   |
| 0x306f2    | 6        | 1.86%   |
| 0x0a201009 | 5        | 1.55%   |
| 0x0800820d | 5        | 1.55%   |
| 0x10676    | 4        | 1.24%   |
| 0x08701013 | 4        | 1.24%   |
| 0x06000852 | 4        | 1.24%   |
| 0xa0671    | 3        | 0.93%   |
| 0xa0655    | 3        | 0.93%   |
| 0x20655    | 3        | 0.93%   |
| 0x08108109 | 3        | 0.93%   |
| 0x06003106 | 3        | 0.93%   |
| 0x06001119 | 3        | 0.93%   |
| 0x0600063e | 3        | 0.93%   |
| 0xa0653    | 2        | 0.62%   |
| 0x6f6      | 2        | 0.62%   |
| 0x306e4    | 2        | 0.62%   |
| 0x206d7    | 2        | 0.62%   |
| 0x206c2    | 2        | 0.62%   |
| 0x0a20120a | 2        | 0.62%   |
| 0x0a201204 | 2        | 0.62%   |
| 0x0a201016 | 2        | 0.62%   |
| 0x08701021 | 2        | 0.62%   |
| 0x08600103 | 2        | 0.62%   |
| 0x0810100b | 2        | 0.62%   |
| 0x08001138 | 2        | 0.62%   |
| 0x03000027 | 2        | 0.62%   |
| 0x010000db | 2        | 0.62%   |
| 0xf64      | 1        | 0.31%   |
| 0x906eb    | 1        | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 42       | 13.68%  |
| SandyBridge      | 30       | 9.77%   |
| Penryn           | 27       | 8.79%   |
| IvyBridge        | 23       | 7.49%   |
| KabyLake         | 22       | 7.17%   |
| K10              | 21       | 6.84%   |
| Zen 3            | 16       | 5.21%   |
| K8 Hammer        | 16       | 5.21%   |
| Core             | 16       | 5.21%   |
| Skylake          | 15       | 4.89%   |
| Zen 2            | 13       | 4.23%   |
| Zen+             | 11       | 3.58%   |
| Piledriver       | 11       | 3.58%   |
| Zen              | 10       | 3.26%   |
| Westmere         | 6        | 1.95%   |
| CometLake        | 6        | 1.95%   |
| Steamroller      | 3        | 0.98%   |
| Silvermont       | 3        | 0.98%   |
| Bulldozer        | 3        | 0.98%   |
| Unknown          | 3        | 0.98%   |
| K10 Llano        | 2        | 0.65%   |
| Puma             | 1        | 0.33%   |
| NetBurst         | 1        | 0.33%   |
| Nehalem          | 1        | 0.33%   |
| Jaguar           | 1        | 0.33%   |
| Icelake          | 1        | 0.33%   |
| Excavator        | 1        | 0.33%   |
| Bonnell          | 1        | 0.33%   |
| Alderlake Hybrid | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 126      | 37.95%  |
| AMD    | 108      | 32.53%  |
| Intel  | 98       | 29.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 18       | 5.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17       | 4.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 4.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 2.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 2.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 2.05%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 1.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.47%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 1.47%   |
| Nvidia GF119 [GeForce GT 520]                                               | 5        | 1.47%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.47%   |
| Intel HD Graphics 530                                                       | 5        | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.47%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.17%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 4        | 1.17%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 4        | 1.17%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 4        | 1.17%   |
| AMD Renoir                                                                  | 4        | 1.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.17%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.88%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.88%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 0.88%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 3        | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.88%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 0.88%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 0.88%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 0.88%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 0.88%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 116      | 36.94%  |
| 1 x AMD        | 100      | 31.85%  |
| 1 x Intel      | 79       | 25.16%  |
| 2 x AMD        | 6        | 1.91%   |
| Intel + Nvidia | 6        | 1.91%   |
| Intel + AMD    | 3        | 0.96%   |
| AMD + Nvidia   | 3        | 0.96%   |
| 2 x Nvidia     | 1        | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 221      | 70.61%  |
| Proprietary | 80       | 25.56%  |
| Unknown     | 12       | 3.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 116      | 35.91%  |
| 1.01-2.0   | 50       | 15.48%  |
| 0.01-0.5   | 40       | 12.38%  |
| 0.51-1.0   | 36       | 11.15%  |
| 3.01-4.0   | 35       | 10.84%  |
| 7.01-8.0   | 27       | 8.36%   |
| 5.01-6.0   | 9        | 2.79%   |
| 8.01-16.0  | 5        | 1.55%   |
| 2.01-3.0   | 4        | 1.24%   |
| 16.01-24.0 | 1        | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 13.52%  |
| Dell                 | 39       | 12.26%  |
| Goldstar             | 33       | 10.38%  |
| Philips              | 26       | 8.18%   |
| Acer                 | 24       | 7.55%   |
| Ancor Communications | 20       | 6.29%   |
| AOC                  | 19       | 5.97%   |
| Hewlett-Packard      | 16       | 5.03%   |
| BenQ                 | 10       | 3.14%   |
| LG Electronics       | 8        | 2.52%   |
| Fujitsu Siemens      | 7        | 2.2%    |
| Panasonic            | 6        | 1.89%   |
| Lenovo               | 6        | 1.89%   |
| Vestel Elektronik    | 4        | 1.26%   |
| NEC Computers        | 4        | 1.26%   |
| HannStar             | 4        | 1.26%   |
| Unknown              | 3        | 0.94%   |
| Sony                 | 3        | 0.94%   |
| MSI                  | 3        | 0.94%   |
| Eizo                 | 3        | 0.94%   |
| ViewSonic            | 2        | 0.63%   |
| Vestel               | 2        | 0.63%   |
| Lenovo Group Limited | 2        | 0.63%   |
| Iiyama               | 2        | 0.63%   |
| Gigabyte Technology  | 2        | 0.63%   |
| ASUSTek Computer     | 2        | 0.63%   |
| ___                  | 1        | 0.31%   |
| WST                  | 1        | 0.31%   |
| WIN                  | 1        | 0.31%   |
| TAR                  | 1        | 0.31%   |
| SUNNY                | 1        | 0.31%   |
| Sharp                | 1        | 0.31%   |
| RTK                  | 1        | 0.31%   |
| PRISM+               | 1        | 0.31%   |
| PEGA                 | 1        | 0.31%   |
| Packard Bell         | 1        | 0.31%   |
| Optoma               | 1        | 0.31%   |
| NUG                  | 1        | 0.31%   |
| NCS                  | 1        | 0.31%   |
| KTC                  | 1        | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch   | 4        | 1.17%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch              | 3        | 0.87%   |
| Ancor Communications VW202 ACI20A2 1680x1050 433x271mm 20.1-inch        | 3        | 0.87%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 521x293mm 23.5-inch       | 2        | 0.58%   |
| Samsung Electronics SMXL2370HD SAM072B 1920x1080 510x287mm 23.0-inch    | 2        | 0.58%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch   | 2        | 0.58%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 0.58%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                     | 2        | 0.58%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch             | 2        | 0.58%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 2        | 0.58%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 2        | 0.58%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2        | 0.58%   |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                    | 2        | 0.58%   |
| Goldstar 24EN43 GSM59DF 1920x1080 510x290mm 23.1-inch                   | 2        | 0.58%   |
| BenQ FP202W BNQ76C2 1680x1050 430x270mm 20.0-inch                       | 2        | 0.58%   |
| AOC 24G2WG3- AOC2402 1920x1080 520x290mm 23.4-inch                      | 2        | 0.58%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                      | 2        | 0.58%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                          | 2        | 0.58%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                         | 2        | 0.58%   |
| Ancor Communications ASUS VB171 ACI17B6 1280x1024 340x270mm 17.1-inch   | 2        | 0.58%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                       | 2        | 0.58%   |
| Acer G257HL ACR0415 1920x1080 553x309mm 24.9-inch                       | 2        | 0.58%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                      | 2        | 0.58%   |
| ___ LCDTV16 ___0101 1360x768                                            | 1        | 0.29%   |
| WST L9VB4 WST0388 1440x900 410x256mm 19.0-inch                          | 1        | 0.29%   |
| WIN 19W MONITOR WIN0010 1440x900 420x320mm 20.8-inch                    | 1        | 0.29%   |
| ViewSonic VG2021m VSCE11D 1400x1050 408x306mm 20.1-inch                 | 1        | 0.29%   |
| ViewSonic LCD Monitor VG2236 SERIES 1920x1080                           | 1        | 0.29%   |
| Vestel LCD Monitor 48UHD_LCD_TV                                         | 1        | 0.29%   |
| Vestel LCD Monitor 22W_LCD_TV 1920x1080                                 | 1        | 0.29%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                      | 1        | 0.29%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.29%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.29%   |
| TAR LCD Monitor LCD17-6 3200x1080                                       | 1        | 0.29%   |
| SUNNY SUNNY SNN0002 1920x1080 1150x650mm 52.0-inch                      | 1        | 0.29%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                      | 1        | 0.29%   |
| Sony LCD Monitor TV 1920x1080                                           | 1        | 0.29%   |
| Sony LCD Monitor TV 1820x1023                                           | 1        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 129      | 39.81%  |
| 1280x1024 (SXGA)   | 31       | 9.57%   |
| 2560x1440 (QHD)    | 27       | 8.33%   |
| 3840x2160 (4K)     | 25       | 7.72%   |
| 1680x1050 (WSXGA+) | 25       | 7.72%   |
| 1440x900 (WXGA+)   | 13       | 4.01%   |
| Unknown            | 13       | 4.01%   |
| 1920x1200 (WUXGA)  | 10       | 3.09%   |
| 1600x900 (HD+)     | 7        | 2.16%   |
| 1366x768 (WXGA)    | 6        | 1.85%   |
| 3440x1440          | 5        | 1.54%   |
| 3840x1080          | 4        | 1.23%   |
| 3840x1200          | 3        | 0.93%   |
| 2560x1080          | 3        | 0.93%   |
| 1400x1050          | 3        | 0.93%   |
| 1360x768           | 3        | 0.93%   |
| 1024x768 (XGA)     | 3        | 0.93%   |
| 3200x1080          | 2        | 0.62%   |
| 1600x1200          | 2        | 0.62%   |
| 1280x720 (HD)      | 2        | 0.62%   |
| 6784x2160          | 1        | 0.31%   |
| 6400x1080          | 1        | 0.31%   |
| 5120x1080          | 1        | 0.31%   |
| 4240x1440          | 1        | 0.31%   |
| 3600x1200          | 1        | 0.31%   |
| 1921x1080          | 1        | 0.31%   |
| 1920x540           | 1        | 0.31%   |
| 1820x1023          | 1        | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 42       | 13.21%  |
| Unknown | 41       | 12.89%  |
| 24      | 37       | 11.64%  |
| 23      | 34       | 10.69%  |
| 27      | 33       | 10.38%  |
| 19      | 23       | 7.23%   |
| 17      | 17       | 5.35%   |
| 22      | 16       | 5.03%   |
| 20      | 15       | 4.72%   |
| 84      | 12       | 3.77%   |
| 31      | 9        | 2.83%   |
| 34      | 6        | 1.89%   |
| 18      | 6        | 1.89%   |
| 25      | 5        | 1.57%   |
| 40      | 3        | 0.94%   |
| 72      | 2        | 0.63%   |
| 54      | 2        | 0.63%   |
| 15      | 2        | 0.63%   |
| 12      | 2        | 0.63%   |
| 75      | 1        | 0.31%   |
| 65      | 1        | 0.31%   |
| 52      | 1        | 0.31%   |
| 46      | 1        | 0.31%   |
| 37      | 1        | 0.31%   |
| 33      | 1        | 0.31%   |
| 32      | 1        | 0.31%   |
| 30      | 1        | 0.31%   |
| 29      | 1        | 0.31%   |
| 28      | 1        | 0.31%   |
| 26      | 1        | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 100      | 31.85%  |
| 401-500     | 90       | 28.66%  |
| Unknown     | 41       | 13.06%  |
| 601-700     | 18       | 5.73%   |
| 301-350     | 18       | 5.73%   |
| 1501-2000   | 15       | 4.78%   |
| 351-400     | 13       | 4.14%   |
| 701-800     | 8        | 2.55%   |
| 1001-1500   | 5        | 1.59%   |
| 801-900     | 4        | 1.27%   |
| 201-300     | 2        | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 165      | 55.18%  |
| 16/10   | 48       | 16.05%  |
| Unknown | 37       | 12.37%  |
| 5/4     | 28       | 9.36%   |
| 4/3     | 10       | 3.34%   |
| 21/9    | 8        | 2.68%   |
| 6/5     | 1        | 0.33%   |
| 32/9    | 1        | 0.33%   |
| 3/2     | 1        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 97       | 31.29%  |
| 151-200        | 51       | 16.45%  |
| Unknown        | 41       | 13.23%  |
| 301-350        | 35       | 11.29%  |
| 251-300        | 20       | 6.45%   |
| 141-150        | 20       | 6.45%   |
| More than 1000 | 19       | 6.13%   |
| 351-500        | 18       | 5.81%   |
| 501-1000       | 5        | 1.61%   |
| 71-80          | 2        | 0.65%   |
| 101-110        | 2        | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 173      | 58.25%  |
| 101-120 | 59       | 19.87%  |
| Unknown | 41       | 13.8%   |
| 1-50    | 11       | 3.7%    |
| 121-160 | 8        | 2.69%   |
| 161-240 | 5        | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 250      | 79.11%  |
| 2     | 41       | 12.97%  |
| 0     | 21       | 6.65%   |
| 3     | 3        | 0.95%   |
| 4     | 1        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 169      | 41.63%  |
| Intel                             | 113      | 27.83%  |
| Qualcomm Atheros                  | 27       | 6.65%   |
| Nvidia                            | 15       | 3.69%   |
| Ralink Technology                 | 12       | 2.96%   |
| Broadcom                          | 11       | 2.71%   |
| Qualcomm Atheros Communications   | 9        | 2.22%   |
| TP-Link                           | 8        | 1.97%   |
| Broadcom Limited                  | 7        | 1.72%   |
| Sundance Technology Inc / IC Plus | 4        | 0.99%   |
| Marvell Technology Group          | 4        | 0.99%   |
| Microsoft                         | 3        | 0.74%   |
| D-Link                            | 3        | 0.74%   |
| Xiaomi                            | 2        | 0.49%   |
| Samsung Electronics               | 2        | 0.49%   |
| MediaTek                          | 2        | 0.49%   |
| D-Link System                     | 2        | 0.49%   |
| Chelsio Communications            | 2        | 0.49%   |
| Aquantia                          | 2        | 0.49%   |
| Razer USA                         | 1        | 0.25%   |
| Ralink                            | 1        | 0.25%   |
| Linksys                           | 1        | 0.25%   |
| Huawei Technologies               | 1        | 0.25%   |
| Gemtek                            | 1        | 0.25%   |
| DisplayLink                       | 1        | 0.25%   |
| ASUSTek Computer                  | 1        | 0.25%   |
| ASIX Electronics                  | 1        | 0.25%   |
| 3Com                              | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 126      | 28.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18       | 4.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 16       | 3.62%   |
| Intel I211 Gigabit Network Connection                                      | 12       | 2.71%   |
| Intel Ethernet Connection (2) I219-V                                       | 12       | 2.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11       | 2.49%   |
| Intel Wi-Fi 6 AX200                                                        | 9        | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                            | 8        | 1.81%   |
| Nvidia MCP61 Ethernet                                                      | 8        | 1.81%   |
| Intel Ethernet Controller I225-V                                           | 8        | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                          | 7        | 1.58%   |
| Intel Ethernet Connection (7) I219-V                                       | 7        | 1.58%   |
| Ralink MT7601U Wireless Adapter                                            | 6        | 1.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 6        | 1.36%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 1.36%   |
| Intel Ethernet Connection (2) I218-V                                       | 6        | 1.36%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 1.36%   |
| Intel Ethernet Connection I217-V                                           | 5        | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 4        | 0.9%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 4        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 4        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 4        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 0.9%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 0.9%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 4        | 0.9%    |
| Realtek RTL8187 Wireless Adapter                                           | 3        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3        | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 3        | 0.68%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.68%   |
| Intel 82578DM Gigabit Network Connection                                   | 3        | 0.68%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 0.68%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 3        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.45%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 2        | 0.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                            | 2        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 29.07%  |
| Realtek Semiconductor           | 13       | 15.12%  |
| Ralink Technology               | 12       | 13.95%  |
| Qualcomm Atheros Communications | 9        | 10.47%  |
| TP-Link                         | 7        | 8.14%   |
| Qualcomm Atheros                | 5        | 5.81%   |
| Microsoft                       | 3        | 3.49%   |
| D-Link                          | 3        | 3.49%   |
| Broadcom                        | 3        | 3.49%   |
| Ralink                          | 1        | 1.16%   |
| MediaTek                        | 1        | 1.16%   |
| Linksys                         | 1        | 1.16%   |
| Gemtek                          | 1        | 1.16%   |
| Broadcom Limited                | 1        | 1.16%   |
| ASUSTek Computer                | 1        | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 9        | 10.47%  |
| Qualcomm Atheros AR9271 802.11n                                                      | 8        | 9.3%    |
| Ralink MT7601U Wireless Adapter                                                      | 6        | 6.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 4        | 4.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 4        | 4.65%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 4.65%   |
| Realtek RTL8187 Wireless Adapter                                                     | 3        | 3.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 3        | 3.49%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 2        | 2.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 2        | 2.33%   |
| Microsoft XBOX ACC                                                                   | 2        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 2.33%   |
| TP-Link Archer T4U ver.3                                                             | 1        | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1        | 1.16%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1        | 1.16%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.16%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                              | 1        | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.16%   |
| Realtek 802.11ac NIC                                                                 | 1        | 1.16%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 1.16%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                | 1        | 1.16%   |
| Ralink RT2070 Wireless Adapter                                                       | 1        | 1.16%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.16%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 1.16%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 1        | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)              | 1        | 1.16%   |
| Microsoft Wireless XBox Controller Dongle                                            | 1        | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 1        | 1.16%   |
| Linksys WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870]             | 1        | 1.16%   |
| Intel Wireless-AC 9260                                                               | 1        | 1.16%   |
| Intel Wireless 7265                                                                  | 1        | 1.16%   |
| Intel Wireless 7260                                                                  | 1        | 1.16%   |
| Intel Wireless 3165                                                                  | 1        | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 1        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 162      | 47.79%  |
| Intel                             | 103      | 30.38%  |
| Qualcomm Atheros                  | 22       | 6.49%   |
| Nvidia                            | 15       | 4.42%   |
| Broadcom                          | 8        | 2.36%   |
| Broadcom Limited                  | 6        | 1.77%   |
| Sundance Technology Inc / IC Plus | 4        | 1.18%   |
| Marvell Technology Group          | 4        | 1.18%   |
| Xiaomi                            | 2        | 0.59%   |
| Samsung Electronics               | 2        | 0.59%   |
| D-Link System                     | 2        | 0.59%   |
| Chelsio Communications            | 2        | 0.59%   |
| Aquantia                          | 2        | 0.59%   |
| TP-Link                           | 1        | 0.29%   |
| Huawei Technologies               | 1        | 0.29%   |
| DisplayLink                       | 1        | 0.29%   |
| ASIX Electronics                  | 1        | 0.29%   |
| 3Com                              | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 126      | 35.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18       | 5.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 16       | 4.52%   |
| Intel I211 Gigabit Network Connection                                      | 12       | 3.39%   |
| Intel Ethernet Connection (2) I219-V                                       | 12       | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11       | 3.11%   |
| Nvidia MCP61 Ethernet                                                      | 8        | 2.26%   |
| Intel Ethernet Controller I225-V                                           | 8        | 2.26%   |
| Realtek RTL8125 2.5GbE Controller                                          | 7        | 1.98%   |
| Intel Ethernet Connection (7) I219-V                                       | 7        | 1.98%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 6        | 1.69%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 1.69%   |
| Intel Ethernet Connection (2) I218-V                                       | 6        | 1.69%   |
| Intel 82579V Gigabit Network Connection                                    | 6        | 1.69%   |
| Intel Ethernet Connection I217-V                                           | 5        | 1.41%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 4        | 1.13%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 1.13%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 1.13%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 4        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3        | 0.85%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.85%   |
| Intel 82578DM Gigabit Network Connection                                   | 3        | 0.85%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 0.85%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 3        | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2        | 0.56%   |
| Nvidia MCP65 Ethernet                                                      | 2        | 0.56%   |
| Nvidia MCP55 Ethernet                                                      | 2        | 0.56%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.56%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 1        | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.28%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 304      | 78.35%  |
| WiFi     | 82       | 21.13%  |
| Modem    | 2        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 266      | 86.36%  |
| WiFi     | 42       | 13.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 225      | 72.35%  |
| 2     | 71       | 22.83%  |
| 3     | 9        | 2.89%   |
| 0     | 3        | 0.96%   |
| 7     | 1        | 0.32%   |
| 5     | 1        | 0.32%   |
| 4     | 1        | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 302      | 98.69%  |
| Yes  | 4        | 1.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 25       | 35.71%  |
| Cambridge Silicon Radio    | 22       | 31.43%  |
| Integrated System Solution | 7        | 10%     |
| ASUSTek Computer           | 5        | 7.14%   |
| Realtek Semiconductor      | 4        | 5.71%   |
| Broadcom                   | 3        | 4.29%   |
| MediaTek                   | 1        | 1.43%   |
| Lite-On Technology         | 1        | 1.43%   |
| IMC Networks               | 1        | 1.43%   |
| Apple                      | 1        | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 22       | 31.43%  |
| Intel AX200 Bluetooth                                 | 9        | 12.86%  |
| Intel Bluetooth Device                                | 4        | 5.71%   |
| Intel AX210 Bluetooth                                 | 4        | 5.71%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4        | 5.71%   |
| Realtek Bluetooth Radio                               | 3        | 4.29%   |
| Intel Bluetooth wireless interface                    | 3        | 4.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 4.29%   |
| Integrated System Solution Bluetooth Device           | 3        | 4.29%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 4.29%   |
| Broadcom BCM2045 Bluetooth                            | 2        | 2.86%   |
| Realtek RTL8723B Bluetooth                            | 1        | 1.43%   |
| MediaTek Wireless_Device                              | 1        | 1.43%   |
| Lite-On Bluetooth Device                              | 1        | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.43%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.43%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 1.43%   |
| ASUS Bluetooth Adapter                                | 1        | 1.43%   |
| ASUS BCM20702A0                                       | 1        | 1.43%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 187      | 36.59%  |
| AMD                                  | 134      | 26.22%  |
| Nvidia                               | 118      | 23.09%  |
| C-Media Electronics                  | 15       | 2.94%   |
| Creative Labs                        | 13       | 2.54%   |
| GN Netcom                            | 4        | 0.78%   |
| Texas Instruments                    | 3        | 0.59%   |
| Plantronics                          | 3        | 0.59%   |
| Creative Technology                  | 3        | 0.59%   |
| ASUSTek Computer                     | 3        | 0.59%   |
| VIA Technologies                     | 2        | 0.39%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.39%   |
| Tenx Technology                      | 2        | 0.39%   |
| Razer USA                            | 2        | 0.39%   |
| Logitech                             | 2        | 0.39%   |
| Generalplus Technology               | 2        | 0.39%   |
| BEHRINGER International              | 2        | 0.39%   |
| Trust                                | 1        | 0.2%    |
| SteelSeries ApS                      | 1        | 0.2%    |
| Sennheiser Communications            | 1        | 0.2%    |
| Samson Technologies                  | 1        | 0.2%    |
| Roland                               | 1        | 0.2%    |
| Ploytec                              | 1        | 0.2%    |
| NAD Electronics                      | 1        | 0.2%    |
| M-Audio                              | 1        | 0.2%    |
| JMTek                                | 1        | 0.2%    |
| FiiO Electronics Technology          | 1        | 0.2%    |
| Evolution Electronics                | 1        | 0.2%    |
| ESS Technology                       | 1        | 0.2%    |
| Dell                                 | 1        | 0.2%    |
| Corsair                              | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 33       | 5.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26       | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25       | 4.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 22       | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21       | 3.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 3.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 2.51%   |
| Nvidia GF119 HDMI Audio Controller                                         | 14       | 2.34%   |
| Intel 200 Series PCH HD Audio                                              | 14       | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13       | 2.17%   |
| AMD FCH Azalia Controller                                                  | 13       | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12       | 2.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 1.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.51%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9        | 1.51%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 1.34%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 1.34%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 1.34%   |
| Nvidia High Definition Audio Controller                                    | 7        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.17%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7        | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 6        | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1%      |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.84%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5        | 0.84%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 0.84%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 0.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 41       | 22.16%  |
| Unknown             | 30       | 16.22%  |
| Corsair             | 20       | 10.81%  |
| Samsung Electronics | 16       | 8.65%   |
| SK hynix            | 15       | 8.11%   |
| A-DATA Technology   | 15       | 8.11%   |
| Micron Technology   | 9        | 4.86%   |
| Team                | 6        | 3.24%   |
| G.Skill             | 6        | 3.24%   |
| Crucial             | 6        | 3.24%   |
| Nanya Technology    | 4        | 2.16%   |
| Ramaxel Technology  | 3        | 1.62%   |
| pqi                 | 2        | 1.08%   |
| Goodram             | 2        | 1.08%   |
| Atermiter           | 2        | 1.08%   |
| Unknown             | 2        | 1.08%   |
| Transcend           | 1        | 0.54%   |
| Thermaltake         | 1        | 0.54%   |
| Silicon Power       | 1        | 0.54%   |
| HBS                 | 1        | 0.54%   |
| Elpida              | 1        | 0.54%   |
| CSX                 | 1        | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 3        | 1.46%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s   | 3        | 1.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 3        | 1.46%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 0.98%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 2        | 0.98%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 2        | 0.98%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 2        | 0.98%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s            | 2        | 0.98%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s  | 2        | 0.98%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s   | 2        | 0.98%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s | 2        | 0.98%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s  | 2        | 0.98%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 3333MT/s  | 2        | 0.98%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s   | 2        | 0.98%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3            | 2        | 0.98%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s   | 2        | 0.98%   |
| Corsair RAM CMV8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s  | 2        | 0.98%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 2        | 0.98%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 0.98%   |
| Unknown                                               | 2        | 0.98%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s             | 1        | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s             | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s           | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR2                   | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s              | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 1        | 0.49%   |
| Unknown RAM Module 256MB DIMM DDR 333MT/s             | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s           | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 1        | 0.49%   |
| Unknown RAM Module 1GB FB-DIMM DDR2 667MT/s           | 1        | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s              | 1        | 0.49%   |
| Unknown RAM Module 1GB DIMM 400MT/s                   | 1        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 63       | 39.38%  |
| DDR3    | 60       | 37.5%   |
| DDR2    | 15       | 9.38%   |
| SDRAM   | 10       | 6.25%   |
| Unknown | 10       | 6.25%   |
| DDR     | 2        | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 150      | 96.15%  |
| SODIMM  | 4        | 2.56%   |
| RIMM    | 1        | 0.64%   |
| FB-DIMM | 1        | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 57       | 32.95%  |
| 8192  | 45       | 26.01%  |
| 2048  | 31       | 17.92%  |
| 16384 | 20       | 11.56%  |
| 1024  | 10       | 5.78%   |
| 32768 | 7        | 4.05%   |
| 512   | 2        | 1.16%   |
| 256   | 1        | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 34       | 19.43%  |
| 1333    | 22       | 12.57%  |
| 800     | 13       | 7.43%   |
| 3600    | 11       | 6.29%   |
| 3200    | 11       | 6.29%   |
| 2133    | 9        | 5.14%   |
| 2400    | 8        | 4.57%   |
| 2667    | 6        | 3.43%   |
| 1867    | 5        | 2.86%   |
| 667     | 5        | 2.86%   |
| 3466    | 4        | 2.29%   |
| 3000    | 4        | 2.29%   |
| 333     | 4        | 2.29%   |
| Unknown | 4        | 2.29%   |
| 3800    | 3        | 1.71%   |
| 2933    | 3        | 1.71%   |
| 2666    | 3        | 1.71%   |
| 1800    | 3        | 1.71%   |
| 3400    | 2        | 1.14%   |
| 3333    | 2        | 1.14%   |
| 2800    | 2        | 1.14%   |
| 1866    | 2        | 1.14%   |
| 57535   | 1        | 0.57%   |
| 4133    | 1        | 0.57%   |
| 3733    | 1        | 0.57%   |
| 3467    | 1        | 0.57%   |
| 3266    | 1        | 0.57%   |
| 3151    | 1        | 0.57%   |
| 3066    | 1        | 0.57%   |
| 2481    | 1        | 0.57%   |
| 2200    | 1        | 0.57%   |
| 2000    | 1        | 0.57%   |
| 1639    | 1        | 0.57%   |
| 1067    | 1        | 0.57%   |
| 1066    | 1        | 0.57%   |
| 533     | 1        | 0.57%   |
| 400     | 1        | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 35.29%  |
| Brother Industries  | 3        | 17.65%  |
| Xerox               | 2        | 11.76%  |
| Samsung Electronics | 2        | 11.76%  |
| Prolific Technology | 1        | 5.88%   |
| Kyocera             | 1        | 5.88%   |
| Citizen             | 1        | 5.88%   |
| ATEN International  | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| HP LaserJet 1020                         | 2        | 11.76%  |
| Xerox Phaser 3140 and 3155               | 1        | 5.88%   |
| Xerox Phaser 3020                        | 1        | 5.88%   |
| Samsung Xerox Phaser 3117 Laser Printer  | 1        | 5.88%   |
| Samsung ML-2010P Mono Laser Printer      | 1        | 5.88%   |
| Prolific PL2305 Parallel Port            | 1        | 5.88%   |
| Kyocera ECOSYS P2040dn                   | 1        | 5.88%   |
| HP LaserJet Professional P1566           | 1        | 5.88%   |
| HP LaserJet P1102                        | 1        | 5.88%   |
| HP LaserJet 4350                         | 1        | 5.88%   |
| HP DeskJet 4530 series                   | 1        | 5.88%   |
| Citizen Barcode Printer                  | 1        | 5.88%   |
| Brother Printer                          | 1        | 5.88%   |
| Brother MFC-B7715DW series               | 1        | 5.88%   |
| Brother DCP-T300                         | 1        | 5.88%   |
| ATEN International UC-1284B Printer Port | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 50%     |
| Canon CanoScan LiDE 110            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia                      | 8        | 17.02%  |
| Z-Star Microelectronics       | 7        | 14.89%  |
| Logitech                      | 6        | 12.77%  |
| Microsoft                     | 5        | 10.64%  |
| Sunplus Innovation Technology | 2        | 4.26%   |
| Silicon Motion                | 2        | 4.26%   |
| Creative Technology           | 2        | 4.26%   |
| Unknown                       | 1        | 2.13%   |
| Suyin                         | 1        | 2.13%   |
| Samsung Electronics           | 1        | 2.13%   |
| Razer USA                     | 1        | 2.13%   |
| Pixart Imaging                | 1        | 2.13%   |
| Hewlett-Packard               | 1        | 2.13%   |
| Google                        | 1        | 2.13%   |
| Genesys Logic                 | 1        | 2.13%   |
| Generalplus Technology        | 1        | 2.13%   |
| GEMBIRD                       | 1        | 2.13%   |
| Divio                         | 1        | 2.13%   |
| Chicony Electronics           | 1        | 2.13%   |
| Aveo Technology               | 1        | 2.13%   |
| Apple                         | 1        | 2.13%   |
| Alcor Micro                   | 1        | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Z-Star A4 TECH HD PC Camera                 | 4        | 8.51%   |
| Microdia Camera                             | 4        | 8.51%   |
| Z-Star Venus USB2.0 Camera                  | 2        | 4.26%   |
| Microsoft LifeCam HD-3000                   | 2        | 4.26%   |
| Microdia USB 2.0 Camera                     | 2        | 4.26%   |
| Logitech Webcam C170                        | 2        | 4.26%   |
| Z-Star Vega USB 2.0 Camera                  | 1        | 2.13%   |
| Unknown HD camera                           | 1        | 2.13%   |
| Suyin Acer/HP Integrated Webcam [CN0314]    | 1        | 2.13%   |
| Sunplus Full HD webcam                      | 1        | 2.13%   |
| Sunplus 2K FHD camera                       | 1        | 2.13%   |
| Silicon Motion WebCam SCB-0385N             | 1        | 2.13%   |
| Silicon Motion Silicon Motion Camera        | 1        | 2.13%   |
| Samsung Galaxy A5 (MTP)                     | 1        | 2.13%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 2.13%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 2.13%   |
| Microsoft MicrosoftÂ LifeCam HD-5001       | 1        | 2.13%   |
| Microsoft LifeCam VX-500 [1357]             | 1        | 2.13%   |
| Microsoft LifeCam Studio                    | 1        | 2.13%   |
| Microdia Sonix USB 2.0 Camera               | 1        | 2.13%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 2.13%   |
| Logitech Webcam Pro 9000                    | 1        | 2.13%   |
| Logitech Webcam C300                        | 1        | 2.13%   |
| Logitech Webcam C270                        | 1        | 2.13%   |
| Logitech HD Webcam C615                     | 1        | 2.13%   |
| HP Webcam 1300                              | 1        | 2.13%   |
| Google Nexus/Pixel Device (MTP + debug)     | 1        | 2.13%   |
| Genesys Logic Camera                        | 1        | 2.13%   |
| Generalplus 808 Camera #9 (web-cam mode)    | 1        | 2.13%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 2.13%   |
| Divio ProLink DS3303u Webcam                | 1        | 2.13%   |
| Creative Live! Cam Sync HD [VF0770]         | 1        | 2.13%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 2.13%   |
| Chicony HP 720p HD Monitor Webcam           | 1        | 2.13%   |
| Aveo UVC camera (Bresser microscope)        | 1        | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE                   | 1        | 2.13%   |
| Alcor Micro USB 2.0 PC Camera               | 1        | 2.13%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| OmniKey               | 2        | 66.67%  |
| Advanced Card Systems | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                  | 2        | 66.67%  |
| Advanced Card Systems ACR38 SmartCard Reader | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 267      | 85.85%  |
| 1     | 40       | 12.86%  |
| 2     | 3        | 0.96%   |
| 4     | 1        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 34.78%  |
| Unassigned class         | 8        | 17.39%  |
| Net/wireless             | 6        | 13.04%  |
| Net/ethernet             | 3        | 6.52%   |
| Communication controller | 3        | 6.52%   |
| Camera                   | 3        | 6.52%   |
| Multimedia controller    | 2        | 4.35%   |
| Card reader              | 2        | 4.35%   |
| Storage/ata              | 1        | 2.17%   |
| Sound                    | 1        | 2.17%   |
| Chipcard                 | 1        | 2.17%   |


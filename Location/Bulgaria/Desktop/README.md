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

Total: 508

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MEG X670E ACE               | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 8954                        | [e7a2f29df5](https://linux-hardware.org/?probe=e7a2f29df5) | Mar 27, 2023 |
| ASRock        | B365 Pro4                   | [ec1dd7f3ab](https://linux-hardware.org/?probe=ec1dd7f3ab) | Mar 26, 2023 |
| ASUSTek       | P5B-Deluxe                  | [f5a9d12043](https://linux-hardware.org/?probe=f5a9d12043) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | [41289d94bf](https://linux-hardware.org/?probe=41289d94bf) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | [1ccaab03c4](https://linux-hardware.org/?probe=1ccaab03c4) | Mar 25, 2023 |
| Gigabyte      | M52S-S3P                    | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| ASUSTek       | P5KC                        | [3c4c536325](https://linux-hardware.org/?probe=3c4c536325) | Mar 23, 2023 |
| ASRock        | B450M Steel Legend          | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| ASRock        | Z370 Pro4                   | [95da35c192](https://linux-hardware.org/?probe=95da35c192) | Mar 11, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | [0d5c00b6fa](https://linux-hardware.org/?probe=0d5c00b6fa) | Mar 11, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c3d0c5da79](https://linux-hardware.org/?probe=c3d0c5da79) | Mar 01, 2023 |
| Gigabyte      | Z490 VISION D               | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [f9cae700c7](https://linux-hardware.org/?probe=f9cae700c7) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| Dell          | 0NNNCT A01                  | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| Dell          | 0WMJ54 A01                  | [5ebabab1c5](https://linux-hardware.org/?probe=5ebabab1c5) | Feb 14, 2023 |
| ASUSTek       | P5QL PRO                    | [65ebc31f26](https://linux-hardware.org/?probe=65ebc31f26) | Feb 08, 2023 |
| ASUSTek       | P5QL PRO                    | [9f2664ae2a](https://linux-hardware.org/?probe=9f2664ae2a) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Intel         | DH77EB AAG39073-304         | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| Dell          | 0T10XW A02                  | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 39       | 10.8%   |
| Ubuntu 18.04                 | 31       | 8.59%   |
| Ubuntu 22.04                 | 17       | 4.71%   |
| OpenMandriva 4.2             | 16       | 4.43%   |
| Debian 11                    | 14       | 3.88%   |
| ROSA R11                     | 8        | 2.22%   |
| ROSA R10                     | 8        | 2.22%   |
| Manjaro                      | 8        | 2.22%   |
| Ubuntu 20.10                 | 7        | 1.94%   |
| ArcoLinux Rolling            | 7        | 1.94%   |
| Arch                         | 7        | 1.94%   |
| Zorin 15                     | 6        | 1.66%   |
| Xubuntu 18.04                | 6        | 1.66%   |
| Ubuntu 22.10                 | 6        | 1.66%   |
| OpenMandriva 4.3             | 6        | 1.66%   |
| Linux Mint 20.1              | 6        | 1.66%   |
| Pop!_OS 20.04                | 5        | 1.39%   |
| KDE neon 20.04               | 5        | 1.39%   |
| Ubuntu 19.10                 | 4        | 1.11%   |
| Ubuntu 19.04                 | 4        | 1.11%   |
| Pop!_OS 21.10                | 4        | 1.11%   |
| Pop!_OS 20.10                | 4        | 1.11%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.11%   |
| Linux Mint 20                | 4        | 1.11%   |
| Linux Mint 19.3              | 4        | 1.11%   |
| Arch Rolling                 | 4        | 1.11%   |
| Ubuntu 21.04                 | 3        | 0.83%   |
| Ubuntu 16.04                 | 3        | 0.83%   |
| ROSA R8.1                    | 3        | 0.83%   |
| OpenMandriva 4.50            | 3        | 0.83%   |
| LMDE 4                       | 3        | 0.83%   |
| Kubuntu 22.04                | 3        | 0.83%   |
| Kubuntu 20.04                | 3        | 0.83%   |
| CentOS 9                     | 3        | 0.83%   |
| Zorin 16                     | 2        | 0.55%   |
| Xubuntu 20.04                | 2        | 0.55%   |
| Ubuntu Unity 16.04           | 2        | 0.55%   |
| Ubuntu MATE 20.04            | 2        | 0.55%   |
| Ubuntu 21.10                 | 2        | 0.55%   |
| ROSA R11.1                   | 2        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 112      | 32.84%  |
| OpenMandriva  | 29       | 8.5%    |
| Linux Mint    | 21       | 6.16%   |
| ROSA          | 20       | 5.87%   |
| Manjaro       | 19       | 5.57%   |
| Debian        | 19       | 5.57%   |
| Pop!_OS       | 15       | 4.4%    |
| Xubuntu       | 11       | 3.23%   |
| Arch          | 10       | 2.93%   |
| Zorin         | 8        | 2.35%   |
| KDE neon      | 8        | 2.35%   |
| Fedora        | 8        | 2.35%   |
| Kubuntu       | 7        | 2.05%   |
| ArcoLinux     | 7        | 2.05%   |
| Ubuntu Unity  | 6        | 1.76%   |
| openSUSE      | 5        | 1.47%   |
| CentOS        | 5        | 1.47%   |
| Lubuntu       | 4        | 1.17%   |
| LMDE          | 3        | 0.88%   |
| Gentoo        | 3        | 0.88%   |
| Elementary    | 3        | 0.88%   |
| Ubuntu MATE   | 2        | 0.59%   |
| Endless       | 2        | 0.59%   |
| Clear Linux   | 2        | 0.59%   |
| Artix         | 2        | 0.59%   |
| Void Linux    | 1        | 0.29%   |
| Ubuntu Budgie | 1        | 0.29%   |
| Slackware     | 1        | 0.29%   |
| Q4OS          | 1        | 0.29%   |
| Parrot        | 1        | 0.29%   |
| Novos         | 1        | 0.29%   |
| Kali          | 1        | 0.29%   |
| EndeavourOS   | 1        | 0.29%   |
| Devuan        | 1        | 0.29%   |
| BlackPanther  | 1        | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 16       | 4%      |
| 5.4.0-42-generic                | 7        | 1.75%   |
| 5.3.0-40-generic                | 7        | 1.75%   |
| 5.16.7-desktop-1omv4003         | 6        | 1.5%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 6        | 1.5%    |
| 5.4.0-58-generic                | 5        | 1.25%   |
| 5.9.16-1-MANJARO                | 4        | 1%      |
| 5.8.0-43-generic                | 4        | 1%      |
| 5.11.0-27-generic               | 4        | 1%      |
| 5.10.0-8-amd64                  | 4        | 1%      |
| 5.8.0-7642-generic              | 3        | 0.75%   |
| 5.8.0-40-generic                | 3        | 0.75%   |
| 5.4.0-56-generic                | 3        | 0.75%   |
| 5.4.0-37-generic                | 3        | 0.75%   |
| 5.4.0-26-generic                | 3        | 0.75%   |
| 5.3.0-46-generic                | 3        | 0.75%   |
| 5.3.0-45-generic                | 3        | 0.75%   |
| 5.3.0-42-generic                | 3        | 0.75%   |
| 5.15.0-67-generic               | 3        | 0.75%   |
| 5.15.0-27-generic               | 3        | 0.75%   |
| 5.0.0-37-generic                | 3        | 0.75%   |
| 5.0.0-23-generic                | 3        | 0.75%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 0.75%   |
| 4.15.0-29-generic               | 3        | 0.75%   |
| 6.2.6-desktop-1omv2390          | 2        | 0.5%    |
| 6.1.1-desktop-1omv2290          | 2        | 0.5%    |
| 5.8.11-1-MANJARO                | 2        | 0.5%    |
| 5.8.0-44-generic                | 2        | 0.5%    |
| 5.8.0-25-generic                | 2        | 0.5%    |
| 5.4.0-7634-generic              | 2        | 0.5%    |
| 5.4.0-67-generic                | 2        | 0.5%    |
| 5.4.0-66-generic                | 2        | 0.5%    |
| 5.4.0-65-generic                | 2        | 0.5%    |
| 5.4.0-59-generic                | 2        | 0.5%    |
| 5.4.0-49-generic                | 2        | 0.5%    |
| 5.4.0-48-generic                | 2        | 0.5%    |
| 5.4.0-40-generic                | 2        | 0.5%    |
| 5.4.0-29-generic                | 2        | 0.5%    |
| 5.4.0-144-generic               | 2        | 0.5%    |
| 5.19.0-35-generic               | 2        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 52       | 13.72%  |
| 4.15.0  | 32       | 8.44%   |
| 5.8.0   | 22       | 5.8%    |
| 5.15.0  | 22       | 5.8%    |
| 5.3.0   | 18       | 4.75%   |
| 5.10.14 | 16       | 4.22%   |
| 5.11.0  | 14       | 3.69%   |
| 5.10.0  | 14       | 3.69%   |
| 5.0.0   | 14       | 3.69%   |
| 5.19.0  | 9        | 2.37%   |
| 5.13.0  | 7        | 1.85%   |
| 4.18.0  | 7        | 1.85%   |
| 5.16.7  | 6        | 1.58%   |
| 5.9.16  | 4        | 1.06%   |
| 4.19.0  | 4        | 1.06%   |
| 6.1.1   | 3        | 0.79%   |
| 5.17.5  | 3        | 0.79%   |
| 5.14.0  | 3        | 0.79%   |
| 4.9.60  | 3        | 0.79%   |
| 4.9.20  | 3        | 0.79%   |
| 6.2.6   | 2        | 0.53%   |
| 6.0.0   | 2        | 0.53%   |
| 5.8.18  | 2        | 0.53%   |
| 5.8.11  | 2        | 0.53%   |
| 5.7.7   | 2        | 0.53%   |
| 5.7.6   | 2        | 0.53%   |
| 5.6.0   | 2        | 0.53%   |
| 5.3.16  | 2        | 0.53%   |
| 5.3.14  | 2        | 0.53%   |
| 5.17.6  | 2        | 0.53%   |
| 5.17.11 | 2        | 0.53%   |
| 5.16.15 | 2        | 0.53%   |
| 5.16.11 | 2        | 0.53%   |
| 5.15.6  | 2        | 0.53%   |
| 5.12.4  | 2        | 0.53%   |
| 5.11.11 | 2        | 0.53%   |
| 5.10.79 | 2        | 0.53%   |
| 5.10.16 | 2        | 0.53%   |
| 4.9.76  | 2        | 0.53%   |
| 4.9.124 | 2        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 14.82%  |
| 5.10    | 42       | 11.32%  |
| 4.15    | 32       | 8.63%   |
| 5.15    | 31       | 8.36%   |
| 5.8     | 28       | 7.55%   |
| 5.3     | 22       | 5.93%   |
| 5.11    | 20       | 5.39%   |
| 5.19    | 14       | 3.77%   |
| 5.16    | 14       | 3.77%   |
| 5.0     | 14       | 3.77%   |
| 4.9     | 10       | 2.7%    |
| 5.17    | 9        | 2.43%   |
| 5.13    | 8        | 2.16%   |
| 6.1     | 7        | 1.89%   |
| 5.14    | 7        | 1.89%   |
| 4.18    | 7        | 1.89%   |
| 5.7     | 6        | 1.62%   |
| 5.9     | 5        | 1.35%   |
| 5.6     | 5        | 1.35%   |
| 6.0     | 4        | 1.08%   |
| 5.2     | 4        | 1.08%   |
| 5.18    | 4        | 1.08%   |
| 5.12    | 4        | 1.08%   |
| 4.19    | 4        | 1.08%   |
| 6.2     | 3        | 0.81%   |
| 4.1     | 3        | 0.81%   |
| 4.4     | 2        | 0.54%   |
| 3.10    | 2        | 0.54%   |
| 5.5     | 1        | 0.27%   |
| 4.7     | 1        | 0.27%   |
| 4.20    | 1        | 0.27%   |
| 4.10    | 1        | 0.27%   |
| Unknown | 1        | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 319      | 98.46%  |
| i686   | 5        | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 124      | 35.43%  |
| KDE5            | 65       | 18.57%  |
| Unknown         | 53       | 15.14%  |
| XFCE            | 25       | 7.14%   |
| X-Cinnamon      | 17       | 4.86%   |
| KDE4            | 15       | 4.29%   |
| MATE            | 12       | 3.43%   |
| KDE             | 11       | 3.14%   |
| Unity           | 6        | 1.71%   |
| LXQt            | 4        | 1.14%   |
| Pantheon        | 3        | 0.86%   |
| Cinnamon        | 3        | 0.86%   |
| GNOME Flashback | 2        | 0.57%   |
| Budgie          | 2        | 0.57%   |
| bspwm           | 2        | 0.57%   |
| xmonad          | 1        | 0.29%   |
| trinity         | 1        | 0.29%   |
| qtile           | 1        | 0.29%   |
| i3              | 1        | 0.29%   |
| DWM             | 1        | 0.29%   |
| awesome         | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 276      | 82.63%  |
| Wayland | 28       | 8.38%   |
| Unknown | 19       | 5.69%   |
| Tty     | 11       | 3.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 172      | 50.89%  |
| SDDM    | 66       | 19.53%  |
| GDM3    | 30       | 8.88%   |
| LightDM | 23       | 6.8%    |
| GDM     | 18       | 5.33%   |
| KDM     | 15       | 4.44%   |
| TDM     | 14       | 4.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 189      | 56.25%  |
| bg_BG   | 65       | 19.35%  |
| Unknown | 56       | 16.67%  |
| C       | 9        | 2.68%   |
| en_GB   | 6        | 1.79%   |
| de_DE   | 5        | 1.49%   |
| ru_UA   | 1        | 0.3%    |
| ru_RU   | 1        | 0.3%    |
| POSIX   | 1        | 0.3%    |
| it_IT   | 1        | 0.3%    |
| Default | 1        | 0.3%    |
| C.UTF8  | 1        | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 218      | 65.47%  |
| EFI  | 115      | 34.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 251      | 73.82%  |
| Overlay | 32       | 9.41%   |
| Unknown | 22       | 6.47%   |
| Btrfs   | 21       | 6.18%   |
| Xfs     | 6        | 1.76%   |
| Zfs     | 4        | 1.18%   |
| Ext3    | 2        | 0.59%   |
| Tmpfs   | 1        | 0.29%   |
| Jfs     | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 175      | 52.55%  |
| GPT     | 106      | 31.83%  |
| MBR     | 52       | 15.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 266      | 78.93%  |
| Yes       | 71       | 21.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 64.85%  |
| Yes       | 116      | 35.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 87       | 26.85%  |
| ASRock              | 61       | 18.83%  |
| Gigabyte Technology | 50       | 15.43%  |
| MSI                 | 21       | 6.48%   |
| Hewlett-Packard     | 21       | 6.48%   |
| Dell                | 19       | 5.86%   |
| Lenovo              | 16       | 4.94%   |
| Fujitsu             | 11       | 3.4%    |
| Intel               | 9        | 2.78%   |
| Foxconn             | 6        | 1.85%   |
| Acer                | 4        | 1.23%   |
| Unknown             | 4        | 1.23%   |
| Wibtek              | 2        | 0.62%   |
| Pegatron            | 2        | 0.62%   |
| Fujitsu Siemens     | 2        | 0.62%   |
| Thecus              | 1        | 0.31%   |
| Supermicro          | 1        | 0.31%   |
| Shuttle             | 1        | 0.31%   |
| Seco                | 1        | 0.31%   |
| Packard Bell        | 1        | 0.31%   |
| MiTAC               | 1        | 0.31%   |
| iEi                 | 1        | 0.31%   |
| ECS                 | 1        | 0.31%   |
| BESSTAR Tech        | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 6        | 1.85%   |
| Lenovo H520S 2561                  | 4        | 1.23%   |
| Unknown                            | 4        | 1.23%   |
| ASRock Z97 Anniversary             | 3        | 0.93%   |
| Wibtek H61-M HDMI2                 | 2        | 0.62%   |
| MSI MS-7C56                        | 2        | 0.62%   |
| MSI MS-7C37                        | 2        | 0.62%   |
| Lenovo H520e 10159                 | 2        | 0.62%   |
| HP Compaq 6005 Pro SFF PC          | 2        | 0.62%   |
| Gigabyte X99-UD4-CF                | 2        | 0.62%   |
| Gigabyte H370AORUSGAMING3WIFI      | 2        | 0.62%   |
| Gigabyte B450 AORUS M              | 2        | 0.62%   |
| Fujitsu ESPRIMO P710               | 2        | 0.62%   |
| Foxconn 500B Microtower            | 2        | 0.62%   |
| Dell Precision Tower 5810          | 2        | 0.62%   |
| Dell OptiPlex 790                  | 2        | 0.62%   |
| Dell OptiPlex 780                  | 2        | 0.62%   |
| ASUS PRIME X570-P                  | 2        | 0.62%   |
| ASUS P5Q-PRO                       | 2        | 0.62%   |
| ASUS P5KC                          | 2        | 0.62%   |
| ASUS P5G41T-M LX                   | 2        | 0.62%   |
| ASUS P5B-Deluxe                    | 2        | 0.62%   |
| ASRock Z370 Pro4                   | 2        | 0.62%   |
| ASRock X570 Phantom Gaming 4       | 2        | 0.62%   |
| ASRock H110M-HDV                   | 2        | 0.62%   |
| ASRock H110M-DGS                   | 2        | 0.62%   |
| ASRock G41M-S3                     | 2        | 0.62%   |
| ASRock B450M-HDV R4.0              | 2        | 0.62%   |
| ASRock B450M Steel Legend          | 2        | 0.62%   |
| ASRock 890GX Extreme3              | 2        | 0.62%   |
| Thecus N2810                       | 1        | 0.31%   |
| Supermicro C2SBC-Q                 | 1        | 0.31%   |
| Shuttle XH81V                      | 1        | 0.31%   |
| Seco C40                           | 1        | 0.31%   |
| Pegatron Compaq 505B Microtower PC | 1        | 0.31%   |
| Pegatron 520-1030uk                | 1        | 0.31%   |
| Packard Bell IMEDIA S2185          | 1        | 0.31%   |
| MSI Pentino G-Series MT            | 1        | 0.31%   |
| MSI MS-7D75                        | 1        | 0.31%   |
| MSI MS-7D69                        | 1        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| HP Compaq                     | 13       | 4.01%   |
| Dell OptiPlex                 | 11       | 3.4%    |
| ASUS PRIME                    | 11       | 3.4%    |
| Fujitsu ESPRIMO               | 9        | 2.78%   |
| ASUS ROG                      | 8        | 2.47%   |
| Lenovo ThinkCentre            | 7        | 2.16%   |
| ASUS All                      | 6        | 1.85%   |
| Dell Precision                | 5        | 1.54%   |
| Lenovo H520S                  | 4        | 1.23%   |
| ASUS P5K                      | 4        | 1.23%   |
| ASRock X570                   | 4        | 1.23%   |
| Unknown                       | 4        | 1.23%   |
| Gigabyte Z490                 | 3        | 0.93%   |
| Gigabyte X570                 | 3        | 0.93%   |
| ASUS TUF                      | 3        | 0.93%   |
| ASRock Z97                    | 3        | 0.93%   |
| Wibtek H61-M                  | 2        | 0.62%   |
| MSI MS-7C56                   | 2        | 0.62%   |
| MSI MS-7C37                   | 2        | 0.62%   |
| Lenovo ThinkStation           | 2        | 0.62%   |
| Lenovo H520e                  | 2        | 0.62%   |
| Intel X99                     | 2        | 0.62%   |
| HP ProDesk                    | 2        | 0.62%   |
| Gigabyte X99-UD4-CF           | 2        | 0.62%   |
| Gigabyte H370AORUSGAMING3WIFI | 2        | 0.62%   |
| Gigabyte B550                 | 2        | 0.62%   |
| Gigabyte B450                 | 2        | 0.62%   |
| Foxconn 500B                  | 2        | 0.62%   |
| Dell Vostro                   | 2        | 0.62%   |
| ASUS SABERTOOTH               | 2        | 0.62%   |
| ASUS P8H61-M                  | 2        | 0.62%   |
| ASUS P5Q-PRO                  | 2        | 0.62%   |
| ASUS P5P43TD                  | 2        | 0.62%   |
| ASUS P5KPL-AM                 | 2        | 0.62%   |
| ASUS P5KC                     | 2        | 0.62%   |
| ASUS P5G41T-M                 | 2        | 0.62%   |
| ASUS P5B-Deluxe               | 2        | 0.62%   |
| ASUS M2N-MX                   | 2        | 0.62%   |
| ASRock Z370                   | 2        | 0.62%   |
| ASRock H81M-ITX               | 2        | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 31       | 9.57%   |
| 2011 | 31       | 9.57%   |
| 2012 | 29       | 8.95%   |
| 2014 | 25       | 7.72%   |
| 2018 | 24       | 7.41%   |
| 2019 | 23       | 7.1%    |
| 2017 | 23       | 7.1%    |
| 2007 | 20       | 6.17%   |
| 2009 | 18       | 5.56%   |
| 2010 | 17       | 5.25%   |
| 2008 | 16       | 4.94%   |
| 2020 | 15       | 4.63%   |
| 2015 | 14       | 4.32%   |
| 2021 | 12       | 3.7%    |
| 2016 | 9        | 2.78%   |
| 2006 | 9        | 2.78%   |
| 2022 | 4        | 1.23%   |
| 2005 | 3        | 0.93%   |
| 2023 | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 324      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 319      | 98.15%  |
| Enabled  | 6        | 1.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 324      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 66       | 19.58%  |
| 3.01-4.0    | 64       | 18.99%  |
| 4.01-8.0    | 61       | 18.1%   |
| 8.01-16.0   | 59       | 17.51%  |
| 32.01-64.0  | 39       | 11.57%  |
| 24.01-32.0  | 14       | 4.15%   |
| 64.01-256.0 | 12       | 3.56%   |
| 1.01-2.0    | 12       | 3.56%   |
| 2.01-3.0    | 9        | 2.67%   |
| 0.51-1.0    | 1        | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 120      | 32.52%  |
| 2.01-3.0   | 94       | 25.47%  |
| 3.01-4.0   | 50       | 13.55%  |
| 4.01-8.0   | 49       | 13.28%  |
| 0.51-1.0   | 36       | 9.76%   |
| 8.01-16.0  | 14       | 3.79%   |
| 0.01-0.5   | 4        | 1.08%   |
| 24.01-32.0 | 1        | 0.27%   |
| 16.01-24.0 | 1        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 134      | 39.41%  |
| 2      | 105      | 30.88%  |
| 3      | 47       | 13.82%  |
| 4      | 19       | 5.59%   |
| 5      | 17       | 5%      |
| 6      | 10       | 2.94%   |
| 8      | 2        | 0.59%   |
| 7      | 2        | 0.59%   |
| 0      | 2        | 0.59%   |
| 11     | 1        | 0.29%   |
| 9      | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 50.75%  |
| Yes       | 164      | 49.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 322      | 99.38%  |
| No        | 2        | 0.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 237      | 72.04%  |
| Yes       | 92       | 27.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 255      | 77.27%  |
| Yes       | 75       | 22.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Bulgaria | 324      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sofia             | 148      | 43.79%  |
| Varna             | 26       | 7.69%   |
| Plovdiv           | 23       | 6.8%    |
| Burgas            | 11       | 3.25%   |
| Stara Zagora      | 10       | 2.96%   |
| Rousse            | 10       | 2.96%   |
| Pernik            | 7        | 2.07%   |
| Sliven            | 6        | 1.78%   |
| Veliko Tarnovo    | 4        | 1.18%   |
| Shumen            | 4        | 1.18%   |
| Haskovo           | 4        | 1.18%   |
| Dobrich           | 4        | 1.18%   |
| Asenovgrad        | 4        | 1.18%   |
| Razgrad           | 3        | 0.89%   |
| Pleven            | 3        | 0.89%   |
| Montana           | 3        | 0.89%   |
| Kazanlak          | 3        | 0.89%   |
| Gabrovo           | 3        | 0.89%   |
| Yambol            | 2        | 0.59%   |
| Vidin             | 2        | 0.59%   |
| Targovishte       | 2        | 0.59%   |
| Svoge             | 2        | 0.59%   |
| Sistov            | 2        | 0.59%   |
| Novi Pazar        | 2        | 0.59%   |
| Novi Iskar        | 2        | 0.59%   |
| Kyustendil        | 2        | 0.59%   |
| Krumovgrad        | 2        | 0.59%   |
| Gorna Oryahovitsa | 2        | 0.59%   |
| Cherven           | 2        | 0.59%   |
| Blagoevgrad       | 2        | 0.59%   |
| Zlatitsa          | 1        | 0.3%    |
| Vratsa            | 1        | 0.3%    |
| Voysil            | 1        | 0.3%    |
| Velingrad         | 1        | 0.3%    |
| Tvarditsa         | 1        | 0.3%    |
| Toros             | 1        | 0.3%    |
| Smolyan           | 1        | 0.3%    |
| Slatina           | 1        | 0.3%    |
| Slashten          | 1        | 0.3%    |
| Silistra          | 1        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 113      | 191    | 19.06%  |
| WDC                         | 104      | 170    | 17.54%  |
| Samsung Electronics         | 81       | 120    | 13.66%  |
| Hitachi                     | 46       | 69     | 7.76%   |
| Toshiba                     | 38       | 52     | 6.41%   |
| Kingston                    | 37       | 58     | 6.24%   |
| A-DATA Technology           | 25       | 32     | 4.22%   |
| Intel                       | 14       | 18     | 2.36%   |
| Team                        | 13       | 14     | 2.19%   |
| Crucial                     | 13       | 24     | 2.19%   |
| SPCC                        | 9        | 10     | 1.52%   |
| SanDisk                     | 9        | 10     | 1.52%   |
| Phison                      | 7        | 7      | 1.18%   |
| HGST                        | 7        | 13     | 1.18%   |
| China                       | 7        | 9      | 1.18%   |
| Maxtor                      | 6        | 11     | 1.01%   |
| XPG                         | 5        | 7      | 0.84%   |
| Realtek Semiconductor       | 5        | 7      | 0.84%   |
| Patriot                     | 5        | 6      | 0.84%   |
| Unknown                     | 3        | 6      | 0.51%   |
| Silicon Motion              | 3        | 6      | 0.51%   |
| Phison Electronics          | 3        | 5      | 0.51%   |
| KIOXIA                      | 3        | 3      | 0.51%   |
| KingSpec                    | 3        | 4      | 0.51%   |
| JMicron Technology          | 3        | 4      | 0.51%   |
| Intenso                     | 3        | 3      | 0.51%   |
| ExcelStor                   | 3        | 7      | 0.51%   |
| OCZ                         | 2        | 2      | 0.34%   |
| AMD                         | 2        | 3      | 0.34%   |
| Verbatim                    | 1        | 1      | 0.17%   |
| Union Memory (Shenzhen)     | 1        | 4      | 0.17%   |
| Transcend                   | 1        | 2      | 0.17%   |
| TO Exter                    | 1        | 1      | 0.17%   |
| StoreJet                    | 1        | 1      | 0.17%   |
| Origin                      | 1        | 1      | 0.17%   |
| OCZ-VERTEX3                 | 1        | 1      | 0.17%   |
| Micron Technology           | 1        | 1      | 0.17%   |
| LITEON                      | 1        | 1      | 0.17%   |
| Kingston Technology Company | 1        | 3      | 0.17%   |
| Innodisk                    | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 16       | 2.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 10       | 1.46%   |
| Kingston SA400S37120G 120GB SSD                     | 10       | 1.46%   |
| Toshiba DT01ACA100 1TB                              | 8        | 1.16%   |
| Seagate ST1000DM003-1ER162 1TB                      | 7        | 1.02%   |
| Samsung NVMe SSD Drive 500GB                        | 7        | 1.02%   |
| Kingston SA400S37480G 480GB SSD                     | 7        | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6        | 0.87%   |
| Toshiba DT01ACA050 500GB                            | 6        | 0.87%   |
| Samsung SSD 850 EVO 250GB                           | 6        | 0.87%   |
| Kingston SV300S37A120G 120GB SSD                    | 6        | 0.87%   |
| Hitachi HDP725050GLA360 500GB                       | 6        | 0.87%   |
| Toshiba HDWD110 1TB                                 | 5        | 0.73%   |
| Toshiba DT01ACA200 2TB                              | 5        | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5        | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB                      | 5        | 0.73%   |
| Samsung SSD 860 EVO 250GB                           | 5        | 0.73%   |
| Samsung SSD 860 EVO 1TB                             | 5        | 0.73%   |
| Samsung SSD 850 PRO 256GB                           | 5        | 0.73%   |
| Hitachi HDS721050CLA362 500GB                       | 5        | 0.73%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 4        | 0.58%   |
| Seagate ST3500413AS 500GB                           | 4        | 0.58%   |
| Seagate ST3250312AS 250GB                           | 4        | 0.58%   |
| Seagate ST3160815AS 160GB                           | 4        | 0.58%   |
| Samsung SSD 970 EVO 250GB                           | 4        | 0.58%   |
| Samsung SSD 860 EVO 500GB                           | 4        | 0.58%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 4        | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4        | 0.58%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 0.58%   |
| Hitachi HDS721616PLA380 160GB                       | 4        | 0.58%   |
| A-DATA SU650 240GB SSD                              | 4        | 0.58%   |
| A-DATA SU650 120GB SSD                              | 4        | 0.58%   |
| XPG NVMe SSD Drive 512GB                            | 3        | 0.44%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 3        | 0.44%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 3        | 0.44%   |
| WDC WD2002FAEX-007BA0 2TB                           | 3        | 0.44%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 3        | 0.44%   |
| WDC WD10EZEX-00WN4A0 1TB                            | 3        | 0.44%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 3        | 0.44%   |
| Team T253X2256G 256GB SSD                           | 3        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 112      | 188    | 35.44%  |
| WDC                 | 98       | 157    | 31.01%  |
| Hitachi             | 46       | 69     | 14.56%  |
| Toshiba             | 33       | 47     | 10.44%  |
| Samsung Electronics | 7        | 9      | 2.22%   |
| HGST                | 7        | 13     | 2.22%   |
| Maxtor              | 6        | 11     | 1.9%    |
| ExcelStor           | 3        | 7      | 0.95%   |
| JMicron Technology  | 1        | 2      | 0.32%   |
| HGST HTS            | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| ASMedia             | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 46       | 59     | 22.77%  |
| Kingston            | 33       | 47     | 16.34%  |
| A-DATA Technology   | 23       | 28     | 11.39%  |
| Team                | 13       | 14     | 6.44%   |
| Crucial             | 12       | 22     | 5.94%   |
| Intel               | 10       | 14     | 4.95%   |
| SPCC                | 9        | 10     | 4.46%   |
| WDC                 | 7        | 10     | 3.47%   |
| SanDisk             | 7        | 8      | 3.47%   |
| China               | 7        | 9      | 3.47%   |
| Patriot             | 5        | 6      | 2.48%   |
| Toshiba             | 3        | 3      | 1.49%   |
| KingSpec            | 3        | 4      | 1.49%   |
| Intenso             | 3        | 3      | 1.49%   |
| OCZ                 | 2        | 2      | 0.99%   |
| JMicron Technology  | 2        | 2      | 0.99%   |
| AMD                 | 2        | 3      | 0.99%   |
| XPG                 | 1        | 1      | 0.5%    |
| Verbatim            | 1        | 1      | 0.5%    |
| Transcend           | 1        | 2      | 0.5%    |
| TO Exter            | 1        | 1      | 0.5%    |
| StoreJet            | 1        | 1      | 0.5%    |
| Seagate             | 1        | 2      | 0.5%    |
| Origin              | 1        | 1      | 0.5%    |
| OCZ-VERTEX3         | 1        | 1      | 0.5%    |
| LITEON              | 1        | 1      | 0.5%    |
| HS-SSD-C100         | 1        | 1      | 0.5%    |
| HPE                 | 1        | 1      | 0.5%    |
| Gigabyte Technology | 1        | 8      | 0.5%    |
| Emtec               | 1        | 1      | 0.5%    |
| Corsair             | 1        | 1      | 0.5%    |
| ATP                 | 1        | 2      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 249      | 506    | 50.1%   |
| SSD     | 167      | 269    | 33.6%   |
| NVMe    | 76       | 124    | 15.29%  |
| Unknown | 3        | 5      | 0.6%    |
| MMC     | 2        | 2      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 306      | 765    | 77.47%  |
| NVMe | 76       | 124    | 19.24%  |
| SAS  | 11       | 15     | 2.78%   |
| MMC  | 2        | 2      | 0.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 249      | 456    | 57.77%  |
| 0.51-1.0   | 113      | 196    | 26.22%  |
| 1.01-2.0   | 34       | 51     | 7.89%   |
| 3.01-4.0   | 14       | 31     | 3.25%   |
| 2.01-3.0   | 10       | 17     | 2.32%   |
| 4.01-10.0  | 7        | 12     | 1.62%   |
| 10.01-20.0 | 4        | 12     | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 84       | 24%     |
| 251-500        | 64       | 18.29%  |
| 501-1000       | 49       | 14%     |
| 1001-2000      | 38       | 10.86%  |
| 1-20           | 34       | 9.71%   |
| 51-100         | 24       | 6.86%   |
| More than 3000 | 22       | 6.29%   |
| 2001-3000      | 14       | 4%      |
| Unknown        | 13       | 3.71%   |
| 21-50          | 8        | 2.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 143      | 38.86%  |
| 21-50          | 48       | 13.04%  |
| 101-250        | 40       | 10.87%  |
| 51-100         | 40       | 10.87%  |
| 501-1000       | 29       | 7.88%   |
| 251-500        | 21       | 5.71%   |
| 1001-2000      | 19       | 5.16%   |
| Unknown        | 13       | 3.53%   |
| More than 3000 | 9        | 2.45%   |
| 2001-3000      | 6        | 1.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| WDC WD6000HLHX-01JJPV0 600GB                                    | 2        | 3      | 3.33%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2        | 6      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB                                 | 2        | 2      | 3.33%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 2        | 2      | 3.33%   |
| WDC WD5000AADS-00S9B0 500GB                                     | 1        | 2      | 1.67%   |
| WDC WD5000AACS-00G8B1 500GB                                     | 1        | 1      | 1.67%   |
| WDC WD40PURX-64GVNY0 4TB                                        | 1        | 1      | 1.67%   |
| WDC WD3200AAJS-07M0A0 320GB                                     | 1        | 2      | 1.67%   |
| WDC WD2500JS-00MHB0 250GB                                       | 1        | 1      | 1.67%   |
| WDC WD2500AAKX-753CA1 250GB                                     | 1        | 1      | 1.67%   |
| WDC WD15EARS-00S8B1 1TB                                         | 1        | 1      | 1.67%   |
| WDC WD10EFRX-68PJCN0 1TB                                        | 1        | 1      | 1.67%   |
| WDC WD10EARS-00MVWB0 1TB                                        | 1        | 1      | 1.67%   |
| Toshiba MK3252GSX 320GB                                         | 1        | 1      | 1.67%   |
| Toshiba DT01ACA300 3TB                                          | 1        | 1      | 1.67%   |
| Toshiba DT01ACA050 500GB                                        | 1        | 1      | 1.67%   |
| SPCC Solid State Disk 128GB                                     | 1        | 1      | 1.67%   |
| Seagate ST380215A 80GB                                          | 1        | 1      | 1.67%   |
| Seagate ST3500830AS 500GB                                       | 1        | 1      | 1.67%   |
| Seagate ST3320311CS 320GB                                       | 1        | 1      | 1.67%   |
| Seagate ST3300631AS 304GB                                       | 1        | 1      | 1.67%   |
| Seagate ST31000333AS 1TB                                        | 1        | 1      | 1.67%   |
| Seagate ST250DM000-1BD141 250GB                                 | 1        | 2      | 1.67%   |
| Seagate ST2000DM001-9YN164 2TB                                  | 1        | 1      | 1.67%   |
| SanDisk SDSSDX480GG25 480GB                                     | 1        | 1      | 1.67%   |
| SanDisk SDSSDH3250G 250GB                                       | 1        | 1      | 1.67%   |
| Samsung Electronics SSD 970 EVO 250GB                           | 1        | 1      | 1.67%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 1        | 2      | 1.67%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 1        | 1      | 1.67%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1        | 1      | 1.67%   |
| Patriot P200 512GB SSD                                          | 1        | 1      | 1.67%   |
| Maxtor 6Y160M0 160GB                                            | 1        | 1      | 1.67%   |
| Maxtor 6L080P0 81GB                                             | 1        | 1      | 1.67%   |
| Maxtor 2F040L0 41GB                                             | 1        | 1      | 1.67%   |
| Kingston SV300S37A60G 64GB SSD                                  | 1        | 1      | 1.67%   |
| Kingston SV300S37A120G 120GB SSD                                | 1        | 1      | 1.67%   |
| Kingston SUV500240G 240GB SSD                                   | 1        | 1      | 1.67%   |
| Kingston SA400S37480G 480GB SSD                                 | 1        | 1      | 1.67%   |
| KingSpec P3-128 128GB SSD                                       | 1        | 2      | 1.67%   |
| Intel SSDSC2CT060A3 64GB                                        | 1        | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 20     | 21.67%  |
| Seagate             | 11       | 12     | 18.33%  |
| Hitachi             | 5        | 5      | 8.33%   |
| A-DATA Technology   | 5        | 5      | 8.33%   |
| Samsung Electronics | 4        | 5      | 6.67%   |
| Kingston            | 4        | 4      | 6.67%   |
| Intel               | 4        | 5      | 6.67%   |
| Toshiba             | 3        | 3      | 5%      |
| Maxtor              | 3        | 3      | 5%      |
| SanDisk             | 2        | 2      | 3.33%   |
| ExcelStor           | 2        | 3      | 3.33%   |
| SPCC                | 1        | 1      | 1.67%   |
| Patriot             | 1        | 1      | 1.67%   |
| KingSpec            | 1        | 2      | 1.67%   |
| China               | 1        | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 13       | 20     | 35.14%  |
| Seagate   | 11       | 12     | 29.73%  |
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
| HDD  | 35       | 46     | 62.5%   |
| SSD  | 18       | 22     | 32.14%  |
| NVMe | 3        | 4      | 5.36%   |

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
| Detected | 198      | 536    | 52.38%  |
| Works    | 128      | 297    | 33.86%  |
| Malfunc  | 51       | 72     | 13.49%  |
| Failed   | 1        | 1      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 212      | 46.9%   |
| AMD                           | 96       | 21.24%  |
| Samsung Electronics           | 42       | 9.29%   |
| JMicron Technology            | 17       | 3.76%   |
| Nvidia                        | 16       | 3.54%   |
| ASMedia Technology            | 14       | 3.1%    |
| Phison Electronics            | 10       | 2.21%   |
| Marvell Technology Group      | 8        | 1.77%   |
| ADATA Technology              | 8        | 1.77%   |
| Realtek Semiconductor         | 6        | 1.33%   |
| SanDisk                       | 4        | 0.88%   |
| Kingston Technology Company   | 4        | 0.88%   |
| Silicon Motion                | 3        | 0.66%   |
| KIOXIA                        | 3        | 0.66%   |
| Toshiba America Info Systems  | 2        | 0.44%   |
| VIA Technologies              | 1        | 0.22%   |
| Union Memory (Shenzhen)       | 1        | 0.22%   |
| Micron/Crucial Technology     | 1        | 0.22%   |
| Micron Technology             | 1        | 0.22%   |
| Integrated Technology Express | 1        | 0.22%   |
| Hewlett-Packard               | 1        | 0.22%   |
| Chelsio Communications        | 1        | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 55       | 9.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 27       | 4.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26       | 4.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15       | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 2.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 2.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14       | 2.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 2.37%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 2.03%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 11       | 1.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 1.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.69%   |
| Nvidia MCP61 SATA Controller                                                            | 9        | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.52%   |
| Nvidia MCP61 IDE                                                                        | 8        | 1.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8        | 1.35%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 1.35%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 1.18%   |
| JMicron JMB368 IDE controller                                                           | 7        | 1.18%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7        | 1.18%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 1.18%   |
| AMD FCH IDE Controller                                                                  | 6        | 1.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 0.85%   |
| Realtek NVMe Controller                                                                 | 5        | 0.85%   |
| Phison E12 NVMe Controller                                                              | 5        | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 0.85%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 5        | 0.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 239      | 53.71%  |
| IDE  | 111      | 24.94%  |
| NVMe | 77       | 17.3%   |
| RAID | 15       | 3.37%   |
| SAS  | 2        | 0.45%   |
| SCSI | 1        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 210      | 64.81%  |
| AMD    | 114      | 35.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.53%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.53%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 1.53%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 4        | 1.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 1.22%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 4        | 1.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.22%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.22%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 1.22%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.22%   |
| AMD FX-6300 Six-Core Processor              | 4        | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.92%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 0.92%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 0.92%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 0.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.92%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 0.92%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 0.92%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 0.92%   |
| AMD Athlon II X2 250 Processor              | 3        | 0.92%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 3        | 0.92%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 2        | 0.61%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 0.61%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.61%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.61%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 0.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.61%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.61%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.61%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 58       | 17.74%  |
| Intel Core i7           | 30       | 9.17%   |
| Intel Core i3           | 25       | 7.65%   |
| AMD Ryzen 5             | 21       | 6.42%   |
| Intel Xeon              | 18       | 5.5%    |
| Intel Core 2 Duo        | 16       | 4.89%   |
| Intel Celeron           | 14       | 4.28%   |
| Intel Core 2 Quad       | 13       | 3.98%   |
| Intel Pentium           | 12       | 3.67%   |
| AMD Ryzen 9             | 12       | 3.67%   |
| AMD Ryzen 7             | 12       | 3.67%   |
| AMD Athlon 64 X2        | 11       | 3.36%   |
| AMD FX                  | 9        | 2.75%   |
| Other                   | 6        | 1.83%   |
| Intel Pentium Dual-Core | 6        | 1.83%   |
| AMD Phenom II X4        | 5        | 1.53%   |
| AMD Athlon II X2        | 5        | 1.53%   |
| AMD Athlon 64           | 5        | 1.53%   |
| AMD A8                  | 5        | 1.53%   |
| Intel Pentium Dual      | 4        | 1.22%   |
| Intel Core i9           | 4        | 1.22%   |
| AMD Ryzen 3             | 3        | 0.92%   |
| AMD Athlon II X4        | 3        | 0.92%   |
| Intel Pentium Gold      | 2        | 0.61%   |
| Intel Core 2            | 2        | 0.61%   |
| AMD Sempron             | 2        | 0.61%   |
| AMD Ryzen 7 PRO         | 2        | 0.61%   |
| AMD Ryzen 5 PRO         | 2        | 0.61%   |
| AMD Phenom II X6        | 2        | 0.61%   |
| AMD Phenom II X2        | 2        | 0.61%   |
| AMD Phenom              | 2        | 0.61%   |
| AMD Athlon X4           | 2        | 0.61%   |
| Intel Pentium D         | 1        | 0.31%   |
| Intel Atom              | 1        | 0.31%   |
| AMD Ryzen Threadripper  | 1        | 0.31%   |
| AMD Ryzen Embedded      | 1        | 0.31%   |
| AMD Phenom II X3        | 1        | 0.31%   |
| AMD GX                  | 1        | 0.31%   |
| AMD E1                  | 1        | 0.31%   |
| AMD Athlon II X3        | 1        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 111      | 33.94%  |
| 2       | 109      | 33.33%  |
| 6       | 43       | 13.15%  |
| 8       | 23       | 7.03%   |
| 12      | 12       | 3.67%   |
| 1       | 10       | 3.06%   |
| 3       | 8        | 2.45%   |
| 16      | 6        | 1.83%   |
| 10      | 2        | 0.61%   |
| 18      | 1        | 0.31%   |
| 14      | 1        | 0.31%   |
| Unknown | 1        | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 322      | 99.38%  |
| 2      | 2        | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 178      | 54.43%  |
| 2       | 148      | 45.26%  |
| Unknown | 1        | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 320      | 97.86%  |
| Unknown        | 7        | 2.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 97       | 28.45%  |
| 0x306c3    | 28       | 8.21%   |
| 0x206a7    | 22       | 6.45%   |
| 0x306a9    | 18       | 5.28%   |
| 0x1067a    | 14       | 4.11%   |
| 0x506e3    | 13       | 3.81%   |
| 0x010000c8 | 10       | 2.93%   |
| 0x906ea    | 9        | 2.64%   |
| 0x906e9    | 7        | 2.05%   |
| 0x6fb      | 7        | 2.05%   |
| 0x6fd      | 6        | 1.76%   |
| 0x306f2    | 6        | 1.76%   |
| 0x0a201009 | 5        | 1.47%   |
| 0x0800820d | 5        | 1.47%   |
| 0xa0655    | 4        | 1.17%   |
| 0x10676    | 4        | 1.17%   |
| 0x08701013 | 4        | 1.17%   |
| 0x06000852 | 4        | 1.17%   |
| 0xa0671    | 3        | 0.88%   |
| 0x20655    | 3        | 0.88%   |
| 0x0a201204 | 3        | 0.88%   |
| 0x08108109 | 3        | 0.88%   |
| 0x06003106 | 3        | 0.88%   |
| 0x06001119 | 3        | 0.88%   |
| 0x0600063e | 3        | 0.88%   |
| 0xa0653    | 2        | 0.59%   |
| 0x90672    | 2        | 0.59%   |
| 0x6f6      | 2        | 0.59%   |
| 0x306e4    | 2        | 0.59%   |
| 0x206d7    | 2        | 0.59%   |
| 0x206c2    | 2        | 0.59%   |
| 0x0a601203 | 2        | 0.59%   |
| 0x0a20120a | 2        | 0.59%   |
| 0x0a201016 | 2        | 0.59%   |
| 0x08701021 | 2        | 0.59%   |
| 0x08600103 | 2        | 0.59%   |
| 0x0810100b | 2        | 0.59%   |
| 0x08001138 | 2        | 0.59%   |
| 0x03000027 | 2        | 0.59%   |
| 0x010000db | 2        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 44       | 13.54%  |
| SandyBridge      | 30       | 9.23%   |
| Penryn           | 29       | 8.92%   |
| KabyLake         | 25       | 7.69%   |
| IvyBridge        | 25       | 7.69%   |
| K10              | 21       | 6.46%   |
| Zen 3            | 18       | 5.54%   |
| K8 Hammer        | 17       | 5.23%   |
| Skylake          | 16       | 4.92%   |
| Core             | 16       | 4.92%   |
| Zen 2            | 13       | 4%      |
| Zen+             | 11       | 3.38%   |
| Piledriver       | 11       | 3.38%   |
| Zen              | 10       | 3.08%   |
| CometLake        | 7        | 2.15%   |
| Unknown          | 7        | 2.15%   |
| Westmere         | 6        | 1.85%   |
| Steamroller      | 3        | 0.92%   |
| Silvermont       | 3        | 0.92%   |
| Bulldozer        | 3        | 0.92%   |
| K10 Llano        | 2        | 0.62%   |
| Puma             | 1        | 0.31%   |
| NetBurst         | 1        | 0.31%   |
| Nehalem          | 1        | 0.31%   |
| Jaguar           | 1        | 0.31%   |
| Icelake          | 1        | 0.31%   |
| Excavator        | 1        | 0.31%   |
| Bonnell          | 1        | 0.31%   |
| Alderlake Hybrid | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 134      | 37.85%  |
| AMD    | 114      | 32.2%   |
| Intel  | 106      | 29.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 5.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19       | 5.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 4.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 2.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 2.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 2.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 1.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 1.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.37%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 1.37%   |
| Nvidia GF119 [GeForce GT 520]                                               | 5        | 1.37%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 5        | 1.37%   |
| Intel HD Graphics 530                                                       | 5        | 1.37%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.37%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4        | 1.1%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.1%    |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 4        | 1.1%    |
| Nvidia GF108 [GeForce GT 730]                                               | 4        | 1.1%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.1%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 4        | 1.1%    |
| AMD Renoir                                                                  | 4        | 1.1%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.82%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.82%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 0.82%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 3        | 0.82%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 0.82%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 0.82%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 0.82%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 122      | 36.64%  |
| 1 x AMD        | 103      | 30.93%  |
| 1 x Intel      | 86       | 25.83%  |
| 2 x AMD        | 6        | 1.8%    |
| Intel + Nvidia | 6        | 1.8%    |
| AMD + Nvidia   | 5        | 1.5%    |
| Intel + AMD    | 4        | 1.2%    |
| 2 x Nvidia     | 1        | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 233      | 70.18%  |
| Proprietary | 85       | 25.6%   |
| Unknown     | 14       | 4.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 130      | 37.9%   |
| 1.01-2.0   | 51       | 14.87%  |
| 0.01-0.5   | 40       | 11.66%  |
| 3.01-4.0   | 37       | 10.79%  |
| 0.51-1.0   | 36       | 10.5%   |
| 7.01-8.0   | 28       | 8.16%   |
| 5.01-6.0   | 9        | 2.62%   |
| 8.01-16.0  | 6        | 1.75%   |
| 2.01-3.0   | 4        | 1.17%   |
| 16.01-24.0 | 2        | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 13.07%  |
| Dell                 | 40       | 12.16%  |
| Goldstar             | 34       | 10.33%  |
| Philips              | 27       | 8.21%   |
| Acer                 | 24       | 7.29%   |
| AOC                  | 20       | 6.08%   |
| Ancor Communications | 20       | 6.08%   |
| Hewlett-Packard      | 16       | 4.86%   |
| BenQ                 | 10       | 3.04%   |
| LG Electronics       | 9        | 2.74%   |
| Fujitsu Siemens      | 8        | 2.43%   |
| Panasonic            | 7        | 2.13%   |
| Lenovo               | 7        | 2.13%   |
| Vestel Elektronik    | 4        | 1.22%   |
| NEC Computers        | 4        | 1.22%   |
| HannStar             | 4        | 1.22%   |
| ASUSTek Computer     | 4        | 1.22%   |
| Unknown              | 3        | 0.91%   |
| Sony                 | 3        | 0.91%   |
| MSI                  | 3        | 0.91%   |
| Eizo                 | 3        | 0.91%   |
| ViewSonic            | 2        | 0.61%   |
| Vestel               | 2        | 0.61%   |
| RTK                  | 2        | 0.61%   |
| Lenovo Group Limited | 2        | 0.61%   |
| Iiyama               | 2        | 0.61%   |
| Gigabyte Technology  | 2        | 0.61%   |
| ___                  | 1        | 0.3%    |
| WST                  | 1        | 0.3%    |
| WIN                  | 1        | 0.3%    |
| TAR                  | 1        | 0.3%    |
| SUNNY                | 1        | 0.3%    |
| Sharp                | 1        | 0.3%    |
| PRISM+               | 1        | 0.3%    |
| PEGA                 | 1        | 0.3%    |
| Packard Bell         | 1        | 0.3%    |
| Optoma               | 1        | 0.3%    |
| NUG                  | 1        | 0.3%    |
| NCS                  | 1        | 0.3%    |
| KTC                  | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 4        | 1.12%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 3        | 0.84%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch              | 3        | 0.84%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                        | 3        | 0.84%   |
| Ancor Communications VW202 ACI20A2 1680x1050 433x271mm 20.1-inch        | 3        | 0.84%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 521x293mm 23.5-inch       | 2        | 0.56%   |
| Samsung Electronics SMXL2370HD SAM072B 1920x1080 510x287mm 23.0-inch    | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch   | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch   | 2        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 0.56%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch             | 2        | 0.56%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 2        | 0.56%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 2        | 0.56%   |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                    | 2        | 0.56%   |
| Goldstar 24EN43 GSM59DF 1920x1080 510x290mm 23.1-inch                   | 2        | 0.56%   |
| BenQ FP202W BNQ76C2 1680x1050 430x270mm 20.0-inch                       | 2        | 0.56%   |
| ASUSTek Computer VG34V AUS3435 3440x1440 797x334mm 34.0-inch            | 2        | 0.56%   |
| AOC 24G2WG3- AOC2402 1920x1080 520x290mm 23.4-inch                      | 2        | 0.56%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                      | 2        | 0.56%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                        | 2        | 0.56%   |
| Ancor Communications ASUS VB171 ACI17B6 1280x720 340x270mm 17.1-inch    | 2        | 0.56%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                       | 2        | 0.56%   |
| Acer G257HL ACR0415 1920x1080 553x309mm 24.9-inch                       | 2        | 0.56%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                      | 2        | 0.56%   |
| ___ LCDTV16 ___0101 1360x768                                            | 1        | 0.28%   |
| WST L9VB4 WST0388 1440x900 410x256mm 19.0-inch                          | 1        | 0.28%   |
| WIN 19W MONITOR WIN0010 1440x900 420x320mm 20.8-inch                    | 1        | 0.28%   |
| ViewSonic VG2021m VSCE11D 1400x1050 408x306mm 20.1-inch                 | 1        | 0.28%   |
| ViewSonic LCD Monitor VG2236 SERIES 1920x1080                           | 1        | 0.28%   |
| Vestel LCD Monitor 48UHD_LCD_TV                                         | 1        | 0.28%   |
| Vestel LCD Monitor 22W_LCD_TV 1920x1080                                 | 1        | 0.28%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                      | 1        | 0.28%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.28%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.28%   |
| TAR LCD Monitor LCD17-6 3200x1080                                       | 1        | 0.28%   |
| SUNNY SUNNY SNN0002 1920x1080 1150x650mm 52.0-inch                      | 1        | 0.28%   |
| Sony TV *00 SNYF303 1920x1080 1085x610mm 49.0-inch                      | 1        | 0.28%   |
| Sony LCD Monitor TV 1920x1080                                           | 1        | 0.28%   |
| Sony LCD Monitor TV 1820x1023                                           | 1        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 134      | 39.88%  |
| 1280x1024 (SXGA)   | 32       | 9.52%   |
| 2560x1440 (QHD)    | 29       | 8.63%   |
| 3840x2160 (4K)     | 26       | 7.74%   |
| 1680x1050 (WSXGA+) | 25       | 7.44%   |
| 1440x900 (WXGA+)   | 13       | 3.87%   |
| Unknown            | 13       | 3.87%   |
| 1920x1200 (WUXGA)  | 10       | 2.98%   |
| 1600x900 (HD+)     | 7        | 2.08%   |
| 1366x768 (WXGA)    | 7        | 2.08%   |
| 3440x1440          | 6        | 1.79%   |
| 3840x1080          | 4        | 1.19%   |
| 2560x1080          | 4        | 1.19%   |
| 3840x1200          | 3        | 0.89%   |
| 1400x1050          | 3        | 0.89%   |
| 1360x768           | 3        | 0.89%   |
| 1024x768 (XGA)     | 3        | 0.89%   |
| 3200x1080          | 2        | 0.6%    |
| 1600x1200          | 2        | 0.6%    |
| 1280x720 (HD)      | 2        | 0.6%    |
| 6784x2160          | 1        | 0.3%    |
| 6400x1080          | 1        | 0.3%    |
| 5120x1080          | 1        | 0.3%    |
| 4240x1440          | 1        | 0.3%    |
| 3600x1200          | 1        | 0.3%    |
| 1921x1080          | 1        | 0.3%    |
| 1920x540           | 1        | 0.3%    |
| 1820x1023          | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 44       | 13.33%  |
| Unknown | 43       | 13.03%  |
| 24      | 39       | 11.82%  |
| 23      | 34       | 10.3%   |
| 27      | 32       | 9.7%    |
| 19      | 23       | 6.97%   |
| 17      | 18       | 5.45%   |
| 22      | 16       | 4.85%   |
| 20      | 15       | 4.55%   |
| 84      | 13       | 3.94%   |
| 31      | 10       | 3.03%   |
| 34      | 8        | 2.42%   |
| 18      | 7        | 2.12%   |
| 25      | 5        | 1.52%   |
| 40      | 3        | 0.91%   |
| 15      | 3        | 0.91%   |
| 72      | 2        | 0.61%   |
| 54      | 2        | 0.61%   |
| 12      | 2        | 0.61%   |
| 75      | 1        | 0.3%    |
| 65      | 1        | 0.3%    |
| 52      | 1        | 0.3%    |
| 46      | 1        | 0.3%    |
| 37      | 1        | 0.3%    |
| 33      | 1        | 0.3%    |
| 32      | 1        | 0.3%    |
| 30      | 1        | 0.3%    |
| 29      | 1        | 0.3%    |
| 28      | 1        | 0.3%    |
| 26      | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 101      | 30.98%  |
| 401-500     | 93       | 28.53%  |
| Unknown     | 43       | 13.19%  |
| 301-350     | 20       | 6.13%   |
| 601-700     | 19       | 5.83%   |
| 1501-2000   | 16       | 4.91%   |
| 351-400     | 13       | 3.99%   |
| 701-800     | 10       | 3.07%   |
| 1001-1500   | 5        | 1.53%   |
| 801-900     | 4        | 1.23%   |
| 201-300     | 2        | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 171      | 54.98%  |
| 16/10   | 49       | 15.76%  |
| Unknown | 39       | 12.54%  |
| 5/4     | 29       | 9.32%   |
| 4/3     | 10       | 3.22%   |
| 21/9    | 10       | 3.22%   |
| 6/5     | 1        | 0.32%   |
| 32/9    | 1        | 0.32%   |
| 3/2     | 1        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 100      | 31.06%  |
| 151-200        | 51       | 15.84%  |
| Unknown        | 43       | 13.35%  |
| 301-350        | 34       | 10.56%  |
| 141-150        | 22       | 6.83%   |
| 351-500        | 21       | 6.52%   |
| 251-300        | 21       | 6.52%   |
| More than 1000 | 20       | 6.21%   |
| 501-1000       | 5        | 1.55%   |
| 101-110        | 3        | 0.93%   |
| 71-80          | 2        | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 179      | 57.74%  |
| 101-120 | 64       | 20.65%  |
| Unknown | 43       | 13.87%  |
| 1-50    | 11       | 3.55%   |
| 121-160 | 10       | 3.23%   |
| 161-240 | 3        | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 263      | 78.74%  |
| 2     | 43       | 12.87%  |
| 0     | 24       | 7.19%   |
| 3     | 3        | 0.9%    |
| 4     | 1        | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 177      | 40.78%  |
| Intel                                 | 123      | 28.34%  |
| Qualcomm Atheros                      | 27       | 6.22%   |
| Nvidia                                | 16       | 3.69%   |
| Broadcom                              | 13       | 3%      |
| Ralink Technology                     | 12       | 2.76%   |
| Qualcomm Atheros Communications       | 10       | 2.3%    |
| TP-Link                               | 9        | 2.07%   |
| Broadcom Limited                      | 7        | 1.61%   |
| Marvell Technology Group              | 5        | 1.15%   |
| Sundance Technology Inc / IC Plus     | 4        | 0.92%   |
| Microsoft                             | 4        | 0.92%   |
| D-Link                                | 4        | 0.92%   |
| MediaTek                              | 3        | 0.69%   |
| Aquantia                              | 3        | 0.69%   |
| Xiaomi                                | 2        | 0.46%   |
| Samsung Electronics                   | 2        | 0.46%   |
| D-Link System                         | 2        | 0.46%   |
| Chelsio Communications                | 2        | 0.46%   |
| Razer USA                             | 1        | 0.23%   |
| Ralink                                | 1        | 0.23%   |
| Huawei Technologies                   | 1        | 0.23%   |
| Gemtek                                | 1        | 0.23%   |
| DisplayLink                           | 1        | 0.23%   |
| ASUSTek Computer                      | 1        | 0.23%   |
| ASIX Electronics                      | 1        | 0.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.23%   |
| 3Com                                  | 1        | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 128      | 26.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18       | 3.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 17       | 3.56%   |
| Intel Ethernet Connection (2) I219-V                                       | 15       | 3.14%   |
| Intel I211 Gigabit Network Connection                                      | 13       | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11       | 2.31%   |
| Intel Wi-Fi 6 AX200                                                        | 10       | 2.1%    |
| Intel Ethernet Controller I225-V                                           | 10       | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                          | 9        | 1.89%   |
| Qualcomm Atheros AR9271 802.11n                                            | 9        | 1.89%   |
| Nvidia MCP61 Ethernet                                                      | 9        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                                       | 7        | 1.47%   |
| Intel 82579V Gigabit Network Connection                                    | 7        | 1.47%   |
| Ralink MT7601U Wireless Adapter                                            | 6        | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 6        | 1.26%   |
| Intel Ethernet Connection I217-V                                           | 6        | 1.26%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 1.26%   |
| Intel Ethernet Connection (2) I218-V                                       | 6        | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 5        | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 5        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 5        | 1.05%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 4        | 0.84%   |
| Realtek RTL8187 Wireless Adapter                                           | 4        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 0.84%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 0.84%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 4        | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.63%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3        | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 3        | 0.63%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.63%   |
| Intel 82578DM Gigabit Network Connection                                   | 3        | 0.63%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 0.63%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 3        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.42%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 2        | 0.42%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                            | 2        | 0.42%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 2        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 28       | 28.57%  |
| Realtek Semiconductor                 | 17       | 17.35%  |
| Ralink Technology                     | 12       | 12.24%  |
| Qualcomm Atheros Communications       | 10       | 10.2%   |
| TP-Link                               | 8        | 8.16%   |
| Qualcomm Atheros                      | 5        | 5.1%    |
| Microsoft                             | 4        | 4.08%   |
| Broadcom                              | 4        | 4.08%   |
| D-Link                                | 3        | 3.06%   |
| MediaTek                              | 2        | 2.04%   |
| Ralink                                | 1        | 1.02%   |
| Gemtek                                | 1        | 1.02%   |
| Broadcom Limited                      | 1        | 1.02%   |
| ASUSTek Computer                      | 1        | 1.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 10       | 10.2%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 9        | 9.18%   |
| Ralink MT7601U Wireless Adapter                                                      | 6        | 6.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 5        | 5.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5        | 5.1%    |
| Intel Comet Lake PCH CNVi WiFi                                                       | 5        | 5.1%    |
| Realtek RTL8187 Wireless Adapter                                                     | 4        | 4.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 3        | 3.06%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 2        | 2.04%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 2        | 2.04%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 2        | 2.04%   |
| Realtek 802.11ac NIC                                                                 | 2        | 2.04%   |
| Microsoft XBOX ACC                                                                   | 2        | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 2.04%   |
| TP-Link Archer T4U ver.3                                                             | 1        | 1.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 1        | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1        | 1.02%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.02%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                              | 1        | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.02%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 1.02%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                | 1        | 1.02%   |
| Ralink RT2070 Wireless Adapter                                                       | 1        | 1.02%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.02%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 1.02%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 1        | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)              | 1        | 1.02%   |
| Microsoft Xbox 360 Wireless Adapter                                                  | 1        | 1.02%   |
| Microsoft Wireless XBox Controller Dongle                                            | 1        | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 1.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 1        | 1.02%   |
| Intel Wireless-AC 9260                                                               | 1        | 1.02%   |
| Intel Wireless 7265                                                                  | 1        | 1.02%   |
| Intel Wireless 7260                                                                  | 1        | 1.02%   |
| Intel Wireless 3165                                                                  | 1        | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 167      | 46.52%  |
| Intel                             | 113      | 31.48%  |
| Qualcomm Atheros                  | 22       | 6.13%   |
| Nvidia                            | 16       | 4.46%   |
| Broadcom                          | 9        | 2.51%   |
| Broadcom Limited                  | 6        | 1.67%   |
| Marvell Technology Group          | 5        | 1.39%   |
| Sundance Technology Inc / IC Plus | 4        | 1.11%   |
| Aquantia                          | 3        | 0.84%   |
| Xiaomi                            | 2        | 0.56%   |
| Samsung Electronics               | 2        | 0.56%   |
| D-Link System                     | 2        | 0.56%   |
| Chelsio Communications            | 2        | 0.56%   |
| TP-Link                           | 1        | 0.28%   |
| Huawei Technologies               | 1        | 0.28%   |
| DisplayLink                       | 1        | 0.28%   |
| D-Link                            | 1        | 0.28%   |
| ASIX Electronics                  | 1        | 0.28%   |
| 3Com                              | 1        | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 128      | 33.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 18       | 4.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 17       | 4.51%   |
| Intel Ethernet Connection (2) I219-V                                       | 15       | 3.98%   |
| Intel I211 Gigabit Network Connection                                      | 13       | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11       | 2.92%   |
| Intel Ethernet Controller I225-V                                           | 10       | 2.65%   |
| Realtek RTL8125 2.5GbE Controller                                          | 9        | 2.39%   |
| Nvidia MCP61 Ethernet                                                      | 9        | 2.39%   |
| Intel Ethernet Connection (7) I219-V                                       | 7        | 1.86%   |
| Intel 82579V Gigabit Network Connection                                    | 7        | 1.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 6        | 1.59%   |
| Intel Ethernet Connection I217-V                                           | 6        | 1.59%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 1.59%   |
| Intel Ethernet Connection (2) I218-V                                       | 6        | 1.59%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 4        | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 1.06%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 1.06%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 4        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.8%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3        | 0.8%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.8%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.8%    |
| Intel 82578DM Gigabit Network Connection                                   | 3        | 0.8%    |
| Intel 82574L Gigabit Network Connection                                    | 3        | 0.8%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 3        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2        | 0.53%   |
| Nvidia MCP65 Ethernet                                                      | 2        | 0.53%   |
| Nvidia MCP55 Ethernet                                                      | 2        | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 2        | 0.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 2        | 0.53%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.53%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                         | 2        | 0.53%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 322      | 77.4%   |
| WiFi     | 92       | 22.12%  |
| Modem    | 2        | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 283      | 86.28%  |
| WiFi     | 45       | 13.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 235      | 71.43%  |
| 2     | 77       | 23.4%   |
| 3     | 10       | 3.04%   |
| 0     | 3        | 0.91%   |
| 4     | 2        | 0.61%   |
| 7     | 1        | 0.3%    |
| 5     | 1        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 320      | 98.77%  |
| Yes  | 4        | 1.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 28       | 35.9%   |
| Cambridge Silicon Radio    | 23       | 29.49%  |
| Integrated System Solution | 7        | 8.97%   |
| Realtek Semiconductor      | 5        | 6.41%   |
| ASUSTek Computer           | 5        | 6.41%   |
| MediaTek                   | 3        | 3.85%   |
| Broadcom                   | 3        | 3.85%   |
| Apple                      | 2        | 2.56%   |
| Lite-On Technology         | 1        | 1.28%   |
| IMC Networks               | 1        | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 23       | 29.49%  |
| Intel AX200 Bluetooth                                 | 10       | 12.82%  |
| Intel AX210 Bluetooth                                 | 5        | 6.41%   |
| Intel AX201 Bluetooth                                 | 5        | 6.41%   |
| Realtek Bluetooth Radio                               | 4        | 5.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4        | 5.13%   |
| MediaTek Wireless_Device                              | 3        | 3.85%   |
| Intel Bluetooth wireless interface                    | 3        | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 3.85%   |
| Integrated System Solution Bluetooth Device           | 3        | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 3.85%   |
| Broadcom BCM2045 Bluetooth                            | 2        | 2.56%   |
| Realtek RTL8723B Bluetooth                            | 1        | 1.28%   |
| Lite-On Bluetooth Device                              | 1        | 1.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.28%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.28%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 1.28%   |
| ASUS Bluetooth Adapter                                | 1        | 1.28%   |
| ASUS BCM20702A0                                       | 1        | 1.28%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.28%   |
| Apple Bluetooth Host Controller                       | 1        | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 198      | 36.33%  |
| AMD                                  | 142      | 26.06%  |
| Nvidia                               | 126      | 23.12%  |
| C-Media Electronics                  | 17       | 3.12%   |
| Creative Labs                        | 13       | 2.39%   |
| Texas Instruments                    | 4        | 0.73%   |
| GN Netcom                            | 4        | 0.73%   |
| ASUSTek Computer                     | 4        | 0.73%   |
| Plantronics                          | 3        | 0.55%   |
| Creative Technology                  | 3        | 0.55%   |
| VIA Technologies                     | 2        | 0.37%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.37%   |
| Tenx Technology                      | 2        | 0.37%   |
| Razer USA                            | 2        | 0.37%   |
| Micro Star International             | 2        | 0.37%   |
| Logitech                             | 2        | 0.37%   |
| Generalplus Technology               | 2        | 0.37%   |
| BEHRINGER International              | 2        | 0.37%   |
| Trust                                | 1        | 0.18%   |
| SteelSeries ApS                      | 1        | 0.18%   |
| Samson Technologies                  | 1        | 0.18%   |
| Roland                               | 1        | 0.18%   |
| Ploytec                              | 1        | 0.18%   |
| NAD Electronics                      | 1        | 0.18%   |
| M-Audio                              | 1        | 0.18%   |
| JMTek                                | 1        | 0.18%   |
| FiiO Electronics Technology          | 1        | 0.18%   |
| Evolution Electronics                | 1        | 0.18%   |
| ESS Technology                       | 1        | 0.18%   |
| DSEA A/S                             | 1        | 0.18%   |
| Dell                                 | 1        | 0.18%   |
| Corsair                              | 1        | 0.18%   |
| CEntrance                            | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 34       | 5.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 4.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26       | 4.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23       | 3.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19       | 2.98%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 2.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 2.35%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 2.35%   |
| Nvidia GF119 HDMI Audio Controller                                         | 14       | 2.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13       | 2.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 2.04%   |
| AMD FCH Azalia Controller                                                  | 13       | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 1.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.57%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 1.57%   |
| Nvidia MCP61 High Definition Audio                                         | 9        | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9        | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.26%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 1.26%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 1.26%   |
| Nvidia High Definition Audio Controller                                    | 7        | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 0.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 6        | 0.94%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 6        | 0.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 0.94%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5        | 0.78%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 45       | 22.61%  |
| Unknown             | 33       | 16.58%  |
| Corsair             | 21       | 10.55%  |
| Samsung Electronics | 17       | 8.54%   |
| A-DATA Technology   | 16       | 8.04%   |
| SK hynix            | 15       | 7.54%   |
| Micron Technology   | 10       | 5.03%   |
| Team                | 6        | 3.02%   |
| G.Skill             | 6        | 3.02%   |
| Crucial             | 6        | 3.02%   |
| Nanya Technology    | 4        | 2.01%   |
| Ramaxel Technology  | 3        | 1.51%   |
| Unknown             | 3        | 1.51%   |
| pqi                 | 2        | 1.01%   |
| Goodram             | 2        | 1.01%   |
| Elpida              | 2        | 1.01%   |
| Atermiter           | 2        | 1.01%   |
| Transcend           | 1        | 0.5%    |
| Thermaltake         | 1        | 0.5%    |
| Silicon Power       | 1        | 0.5%    |
| Patriot             | 1        | 0.5%    |
| HBS                 | 1        | 0.5%    |
| CSX                 | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 3        | 1.36%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s   | 3        | 1.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 3        | 1.36%   |
| Unknown                                               | 3        | 1.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 0.91%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 2        | 0.91%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 2        | 0.91%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s            | 2        | 0.91%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s  | 2        | 0.91%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s   | 2        | 0.91%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s | 2        | 0.91%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s  | 2        | 0.91%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 3333MT/s  | 2        | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s     | 2        | 0.91%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s   | 2        | 0.91%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s   | 2        | 0.91%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s   | 2        | 0.91%   |
| Corsair RAM CMV8GX3M1A1600C11 8GB DIMM 1600MT/s       | 2        | 0.91%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 2        | 0.91%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 0.91%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s             | 1        | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s             | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s             | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 400MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s           | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR2                   | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s               | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s              | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM 667MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 1        | 0.45%   |
| Unknown RAM Module 256MB DIMM DDR 333MT/s             | 1        | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 1        | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s           | 1        | 0.45%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 1        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 68       | 39.53%  |
| DDR3    | 63       | 36.63%  |
| DDR2    | 15       | 8.72%   |
| Unknown | 11       | 6.4%    |
| SDRAM   | 10       | 5.81%   |
| DDR     | 3        | 1.74%   |
| DDR5    | 2        | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 161      | 95.83%  |
| SODIMM  | 5        | 2.98%   |
| RIMM    | 1        | 0.6%    |
| FB-DIMM | 1        | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 59       | 31.55%  |
| 8192  | 51       | 27.27%  |
| 2048  | 33       | 17.65%  |
| 16384 | 23       | 12.3%   |
| 1024  | 11       | 5.88%   |
| 32768 | 7        | 3.74%   |
| 512   | 2        | 1.07%   |
| 256   | 1        | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 35       | 18.52%  |
| 1333    | 25       | 13.23%  |
| 3200    | 13       | 6.88%   |
| 800     | 13       | 6.88%   |
| 3600    | 11       | 5.82%   |
| 2133    | 9        | 4.76%   |
| 2400    | 8        | 4.23%   |
| 2667    | 7        | 3.7%    |
| 667     | 6        | 3.17%   |
| 1867    | 5        | 2.65%   |
| 3466    | 4        | 2.12%   |
| 3000    | 4        | 2.12%   |
| 333     | 4        | 2.12%   |
| Unknown | 4        | 2.12%   |
| 3800    | 3        | 1.59%   |
| 3400    | 3        | 1.59%   |
| 2933    | 3        | 1.59%   |
| 2666    | 3        | 1.59%   |
| 1800    | 3        | 1.59%   |
| 3333    | 2        | 1.06%   |
| 2800    | 2        | 1.06%   |
| 1866    | 2        | 1.06%   |
| 400     | 2        | 1.06%   |
| 57535   | 1        | 0.53%   |
| 6000    | 1        | 0.53%   |
| 4800    | 1        | 0.53%   |
| 4133    | 1        | 0.53%   |
| 3733    | 1        | 0.53%   |
| 3666    | 1        | 0.53%   |
| 3467    | 1        | 0.53%   |
| 3266    | 1        | 0.53%   |
| 3151    | 1        | 0.53%   |
| 3066    | 1        | 0.53%   |
| 2481    | 1        | 0.53%   |
| 2200    | 1        | 0.53%   |
| 2000    | 1        | 0.53%   |
| 1639    | 1        | 0.53%   |
| 1400    | 1        | 0.53%   |
| 1067    | 1        | 0.53%   |
| 1066    | 1        | 0.53%   |

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
| Microdia                      | 8        | 16.67%  |
| Z-Star Microelectronics       | 7        | 14.58%  |
| Logitech                      | 7        | 14.58%  |
| Microsoft                     | 5        | 10.42%  |
| Sunplus Innovation Technology | 2        | 4.17%   |
| Silicon Motion                | 2        | 4.17%   |
| Creative Technology           | 2        | 4.17%   |
| Unknown                       | 1        | 2.08%   |
| Suyin                         | 1        | 2.08%   |
| Samsung Electronics           | 1        | 2.08%   |
| Razer USA                     | 1        | 2.08%   |
| Pixart Imaging                | 1        | 2.08%   |
| Hewlett-Packard               | 1        | 2.08%   |
| Google                        | 1        | 2.08%   |
| Genesys Logic                 | 1        | 2.08%   |
| Generalplus Technology        | 1        | 2.08%   |
| GEMBIRD                       | 1        | 2.08%   |
| Divio                         | 1        | 2.08%   |
| Chicony Electronics           | 1        | 2.08%   |
| Aveo Technology               | 1        | 2.08%   |
| Apple                         | 1        | 2.08%   |
| Alcor Micro                   | 1        | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Z-Star A4 TECH HD PC Camera                 | 4        | 8.33%   |
| Microdia Camera                             | 4        | 8.33%   |
| Z-Star Venus USB2.0 Camera                  | 2        | 4.17%   |
| Microsoft LifeCam HD-3000                   | 2        | 4.17%   |
| Microdia USB 2.0 Camera                     | 2        | 4.17%   |
| Logitech Webcam C270                        | 2        | 4.17%   |
| Logitech Webcam C170                        | 2        | 4.17%   |
| Z-Star Vega USB 2.0 Camera                  | 1        | 2.08%   |
| Unknown HD camera                           | 1        | 2.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]    | 1        | 2.08%   |
| Sunplus ZET USB WEBCAM                      | 1        | 2.08%   |
| Sunplus Full HD webcam                      | 1        | 2.08%   |
| Silicon Motion WebCam SCB-0385N             | 1        | 2.08%   |
| Silicon Motion Silicon Motion Camera        | 1        | 2.08%   |
| Samsung Galaxy A5 (MTP)                     | 1        | 2.08%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 2.08%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 2.08%   |
| Microsoft MicrosoftÂ LifeCam HD-5001       | 1        | 2.08%   |
| Microsoft LifeCam VX-500 [1357]             | 1        | 2.08%   |
| Microsoft LifeCam Studio                    | 1        | 2.08%   |
| Microdia Sonix USB 2.0 Camera               | 1        | 2.08%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 2.08%   |
| Logitech Webcam Pro 9000                    | 1        | 2.08%   |
| Logitech Webcam C300                        | 1        | 2.08%   |
| Logitech HD Webcam C615                     | 1        | 2.08%   |
| HP Webcam 1300                              | 1        | 2.08%   |
| Google Nexus/Pixel Device (MTP + debug)     | 1        | 2.08%   |
| Genesys Logic Camera                        | 1        | 2.08%   |
| Generalplus 808 Camera #9 (web-cam mode)    | 1        | 2.08%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 2.08%   |
| Divio ProLink DS3303u Webcam                | 1        | 2.08%   |
| Creative Live! Cam Sync HD [VF0770]         | 1        | 2.08%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 2.08%   |
| Chicony HP 720p HD Monitor Webcam           | 1        | 2.08%   |
| Aveo UVC camera (Bresser microscope)        | 1        | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X             | 1        | 2.08%   |
| Alcor Micro USB 2.0 PC Camera               | 1        | 2.08%   |

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
| 0     | 280      | 85.11%  |
| 1     | 43       | 13.07%  |
| 2     | 4        | 1.22%   |
| 5     | 1        | 0.3%    |
| 3     | 1        | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 35.19%  |
| Unassigned class         | 8        | 14.81%  |
| Net/wireless             | 8        | 14.81%  |
| Net/ethernet             | 4        | 7.41%   |
| Communication controller | 4        | 7.41%   |
| Camera                   | 3        | 5.56%   |
| Multimedia controller    | 2        | 3.7%    |
| Card reader              | 2        | 3.7%    |
| Storage/ata              | 1        | 1.85%   |
| Storage                  | 1        | 1.85%   |
| Sound                    | 1        | 1.85%   |
| Chipcard                 | 1        | 1.85%   |


Red OS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 383

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Graviton      | DMB-Q670-TMI01              | [c609b9c45c](https://linux-hardware.org/?probe=c609b9c45c) | Dec 26, 2024 |
| Graviton      | DMB-Q670-TMI01              | [425c41687c](https://linux-hardware.org/?probe=425c41687c) | Dec 26, 2024 |
| Gigabyte      | H110M-S2H-CF                | [89c03187e1](https://linux-hardware.org/?probe=89c03187e1) | Dec 19, 2024 |
| Gigabyte      | A620M H                     | [bef78fc714](https://linux-hardware.org/?probe=bef78fc714) | Dec 19, 2024 |
| Gigabyte      | A620M H                     | [a48a1efcc8](https://linux-hardware.org/?probe=a48a1efcc8) | Dec 18, 2024 |
| Intel         | DH61BF AAG81311-101         | [4d21569356](https://linux-hardware.org/?probe=4d21569356) | Dec 18, 2024 |
| Gigabyte      | H510M H                     | [a49d561fb0](https://linux-hardware.org/?probe=a49d561fb0) | Dec 15, 2024 |
| BESHTAU       | Q670D5RU002 V1.0            | [59e2adb673](https://linux-hardware.org/?probe=59e2adb673) | Dec 13, 2024 |
| Gigabyte      | A520M S2H                   | [5fc4416068](https://linux-hardware.org/?probe=5fc4416068) | Dec 13, 2024 |
| Intel         | DH61CR AAG14064-203         | [2acdad4c78](https://linux-hardware.org/?probe=2acdad4c78) | Dec 12, 2024 |
| DEPO Compu... | DPH410S                     | [a986fc28d0](https://linux-hardware.org/?probe=a986fc28d0) | Dec 11, 2024 |
| ASUSTek       | PRIME B360M-C               | [5110e95caf](https://linux-hardware.org/?probe=5110e95caf) | Dec 10, 2024 |
| ASUSTek       | PRIME B360M-C               | [b08f5fe789](https://linux-hardware.org/?probe=b08f5fe789) | Dec 10, 2024 |
| Intel         | DH61CR AAG14064-203         | [c4751390a8](https://linux-hardware.org/?probe=c4751390a8) | Dec 09, 2024 |
| ECS           | H81H3-M4                    | [bc47715809](https://linux-hardware.org/?probe=bc47715809) | Dec 06, 2024 |
| INFERIT       | IFMBH510MKPR G10a           | [48fdaa7cd0](https://linux-hardware.org/?probe=48fdaa7cd0) | Dec 04, 2024 |
| Kraftway      | KWH510                      | [1f385fb7ae](https://linux-hardware.org/?probe=1f385fb7ae) | Dec 04, 2024 |
| Gigabyte      | A520M S2H                   | [1f167af92b](https://linux-hardware.org/?probe=1f167af92b) | Nov 28, 2024 |
| Gigabyte      | A520M S2H                   | [08a50a8073](https://linux-hardware.org/?probe=08a50a8073) | Nov 28, 2024 |
| MSI           | B250M PRO-VDH               | [95c02414bb](https://linux-hardware.org/?probe=95c02414bb) | Nov 27, 2024 |
| Dell          | 0VNM11 A01                  | [40eccd6be6](https://linux-hardware.org/?probe=40eccd6be6) | Nov 26, 2024 |
| Supermicro    | X10DRiB                     | [b00821a487](https://linux-hardware.org/?probe=b00821a487) | Nov 25, 2024 |
| Gigabyte      | B365M DS3H                  | [8690967d76](https://linux-hardware.org/?probe=8690967d76) | Nov 13, 2024 |
| Gigabyte      | B365M D3H-CF                | [a5838abf59](https://linux-hardware.org/?probe=a5838abf59) | Nov 12, 2024 |
| BESHTAU       | H610RU001 V1.0              | [50a3234041](https://linux-hardware.org/?probe=50a3234041) | Nov 12, 2024 |
| ASUSTek       | P8H67-M PRO                 | [c694929d4d](https://linux-hardware.org/?probe=c694929d4d) | Nov 11, 2024 |
| ASUSTek       | H61M-K                      | [caea237027](https://linux-hardware.org/?probe=caea237027) | Nov 11, 2024 |
| ASUSTek       | B85M-G                      | [8057418501](https://linux-hardware.org/?probe=8057418501) | Nov 11, 2024 |
| Gigabyte      | H81M-S2VP                   | [30e754b191](https://linux-hardware.org/?probe=30e754b191) | Nov 11, 2024 |
| Gigabyte      | F2A55M-S1                   | [b1994169b0](https://linux-hardware.org/?probe=b1994169b0) | Nov 11, 2024 |
| Gigabyte      | H81M-S2VP                   | [0bd4b5605c](https://linux-hardware.org/?probe=0bd4b5605c) | Nov 11, 2024 |
| Gigabyte      | F2A55M-S1                   | [44d2040a89](https://linux-hardware.org/?probe=44d2040a89) | Nov 11, 2024 |
| MSI           | A520M-A PRO                 | [d5bdcf81dd](https://linux-hardware.org/?probe=d5bdcf81dd) | Nov 11, 2024 |
| ASRock        | H610M-HVS                   | [b304feae94](https://linux-hardware.org/?probe=b304feae94) | Nov 07, 2024 |
| Gigabyte      | H55M-UD2H                   | [961478c114](https://linux-hardware.org/?probe=961478c114) | Nov 07, 2024 |
| ASRock        | H310CM-DVS                  | [a1ad62188e](https://linux-hardware.org/?probe=a1ad62188e) | Nov 07, 2024 |
| MSI           | B360M PRO-VDH               | [7991e1acba](https://linux-hardware.org/?probe=7991e1acba) | Nov 02, 2024 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [e2785d8d28](https://linux-hardware.org/?probe=e2785d8d28) | Oct 21, 2024 |
| Aquarius      | AQH310CM                    | [cf03695b5e](https://linux-hardware.org/?probe=cf03695b5e) | Oct 18, 2024 |
| Gigabyte      | B75M-D3V                    | [3360dc0f64](https://linux-hardware.org/?probe=3360dc0f64) | Oct 08, 2024 |
| ASRock        | H310CM-HDV/M.2              | [797e92230b](https://linux-hardware.org/?probe=797e92230b) | Oct 04, 2024 |
| Dell          | 0KYWH7 A03                  | [c029d50cdd](https://linux-hardware.org/?probe=c029d50cdd) | Oct 02, 2024 |
| Dell          | 0V4W66 A00                  | [fbe88e537a](https://linux-hardware.org/?probe=fbe88e537a) | Sep 30, 2024 |
| Huanan        | X99-BD4 V1.34               | [9ff89a88f1](https://linux-hardware.org/?probe=9ff89a88f1) | Aug 25, 2024 |
| Acer          | Aspire XC-885 V:1.1         | [09f000529a](https://linux-hardware.org/?probe=09f000529a) | Aug 22, 2024 |
| MSI           | H310M PRO-VDH               | [1e0b767085](https://linux-hardware.org/?probe=1e0b767085) | Aug 22, 2024 |
| ICL           | H410SB                      | [05b3ed6993](https://linux-hardware.org/?probe=05b3ed6993) | Aug 16, 2024 |
| Huanan        | X99-BD4 V1.34               | [d62a8cb955](https://linux-hardware.org/?probe=d62a8cb955) | Aug 09, 2024 |
| Intel         | DH61BF AAG81311-101         | [b9ef99ffd8](https://linux-hardware.org/?probe=b9ef99ffd8) | Jul 29, 2024 |
| ASUSTek       | PRIME H510M-R               | [8bbda40ace](https://linux-hardware.org/?probe=8bbda40ace) | Jul 29, 2024 |
| Gigabyte      | B365M DS3H                  | [785322816c](https://linux-hardware.org/?probe=785322816c) | Jul 29, 2024 |
| Gigabyte      | B360HD3                     | [1cd46b9994](https://linux-hardware.org/?probe=1cd46b9994) | Jul 29, 2024 |
| Aquarius      | AQH410T                     | [f30b737c64](https://linux-hardware.org/?probe=f30b737c64) | Jul 25, 2024 |
| HP            | 8599                        | [5571e112b3](https://linux-hardware.org/?probe=5571e112b3) | Jul 23, 2024 |
| MSI           | B450M MORTAR MAX            | [2a0cbaac64](https://linux-hardware.org/?probe=2a0cbaac64) | Jul 20, 2024 |
| Foxconn       | M61PMV FAB                  | [4c63ed31bc](https://linux-hardware.org/?probe=4c63ed31bc) | Jul 14, 2024 |
| Foxconn       | M61PMV FAB                  | [8fba56f752](https://linux-hardware.org/?probe=8fba56f752) | Jul 12, 2024 |
| HP            | 3396                        | [c4cd06b045](https://linux-hardware.org/?probe=c4cd06b045) | Jul 08, 2024 |
| HP            | 18E6                        | [0201e189b7](https://linux-hardware.org/?probe=0201e189b7) | Jul 02, 2024 |
| Lenovo        | 3111 NOK                    | [8a4da42802](https://linux-hardware.org/?probe=8a4da42802) | Jul 02, 2024 |
| ASUSTek       | B85M-G                      | [9618ac190c](https://linux-hardware.org/?probe=9618ac190c) | Jun 28, 2024 |
| ASRock        | H610M-HVS                   | [44957c7ccb](https://linux-hardware.org/?probe=44957c7ccb) | Jun 26, 2024 |
| ASUSTek       | B150M-K                     | [fac6b0f586](https://linux-hardware.org/?probe=fac6b0f586) | Jun 19, 2024 |
| ASUSTek       | B150M-K                     | [326710cc69](https://linux-hardware.org/?probe=326710cc69) | Jun 19, 2024 |
| MSI           | H61M-P31                    | [d0742079a6](https://linux-hardware.org/?probe=d0742079a6) | May 31, 2024 |
| Intel         | DH61BF AAG81311-101         | [210077e8dc](https://linux-hardware.org/?probe=210077e8dc) | May 31, 2024 |
| Gigabyte      | GA-880GMA-UD2H              | [2cb7e34625](https://linux-hardware.org/?probe=2cb7e34625) | May 17, 2024 |
| MSI           | PRO H610M-E DDR4            | [a415f46a9e](https://linux-hardware.org/?probe=a415f46a9e) | May 07, 2024 |
| MSI           | PRO H610M-E DDR4            | [e4adc14010](https://linux-hardware.org/?probe=e4adc14010) | May 06, 2024 |
| ASRock        | H610M-HVS                   | [bb1b76d77f](https://linux-hardware.org/?probe=bb1b76d77f) | Apr 10, 2024 |
| ASUSTek       | H110-PLUS                   | [f9d667563c](https://linux-hardware.org/?probe=f9d667563c) | Apr 10, 2024 |
| Gigabyte      | B75M-D3V                    | [606efbdac3](https://linux-hardware.org/?probe=606efbdac3) | Apr 10, 2024 |
| Gigabyte      | B75M-D3V                    | [af364f4b61](https://linux-hardware.org/?probe=af364f4b61) | Apr 09, 2024 |
| Gigabyte      | B75M-D3V                    | [2c9d3860d1](https://linux-hardware.org/?probe=2c9d3860d1) | Apr 05, 2024 |
| ASRock        | H610M-HVS                   | [0fe84d2ae2](https://linux-hardware.org/?probe=0fe84d2ae2) | Apr 05, 2024 |
| Foxconn       | 2ABF                        | [1948e2f590](https://linux-hardware.org/?probe=1948e2f590) | Mar 28, 2024 |
| MSI           | MAG B760M MORTAR            | [a7d3ac796f](https://linux-hardware.org/?probe=a7d3ac796f) | Mar 24, 2024 |
| Gigabyte      | A520M K V2                  | [bb5ad21304](https://linux-hardware.org/?probe=bb5ad21304) | Mar 24, 2024 |
| Gigabyte      | H510M S2H V2                | [cbfecba3df](https://linux-hardware.org/?probe=cbfecba3df) | Mar 20, 2024 |
| Gigabyte      | H510M S2H V2                | [f9d491fb3a](https://linux-hardware.org/?probe=f9d491fb3a) | Mar 20, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [6c0a847cf4](https://linux-hardware.org/?probe=6c0a847cf4) | Mar 20, 2024 |
| Gigabyte      | H310M H                     | [041eca17dc](https://linux-hardware.org/?probe=041eca17dc) | Mar 20, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | [21877754a0](https://linux-hardware.org/?probe=21877754a0) | Mar 20, 2024 |
| HP            | 198E                        | [dfdd44b32d](https://linux-hardware.org/?probe=dfdd44b32d) | Mar 20, 2024 |
| ASUSTek       | PRIME B360-PLUS             | [286fb4ec0a](https://linux-hardware.org/?probe=286fb4ec0a) | Mar 20, 2024 |
| Unknown       | T360D11                     | [8dc0de16f8](https://linux-hardware.org/?probe=8dc0de16f8) | Mar 20, 2024 |
| HP            | 2B43                        | [365885e742](https://linux-hardware.org/?probe=365885e742) | Mar 20, 2024 |
| Acer          | Aspire XC-885 V:1.1         | [ec2b946862](https://linux-hardware.org/?probe=ec2b946862) | Mar 20, 2024 |
| Gigabyte      | B75M-D3V                    | [4a7f8b6b79](https://linux-hardware.org/?probe=4a7f8b6b79) | Mar 15, 2024 |
| ASRock        | H610M-HVS                   | [3189e4304b](https://linux-hardware.org/?probe=3189e4304b) | Mar 13, 2024 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | [3b98bf5ca7](https://linux-hardware.org/?probe=3b98bf5ca7) | Mar 11, 2024 |
| INTECH PRO    | H510-M2 v5.0                | [6afefbab74](https://linux-hardware.org/?probe=6afefbab74) | Mar 11, 2024 |
| ASUSTek       | PRIME B360M-D               | [7d2950146c](https://linux-hardware.org/?probe=7d2950146c) | Mar 09, 2024 |
| MSI           | H61I-E35                    | [dbc777c090](https://linux-hardware.org/?probe=dbc777c090) | Mar 07, 2024 |
| MSI           | H61I-E35                    | [d9c1e6f02c](https://linux-hardware.org/?probe=d9c1e6f02c) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [7c13263839](https://linux-hardware.org/?probe=7c13263839) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [b389d340cc](https://linux-hardware.org/?probe=b389d340cc) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [42d07a20da](https://linux-hardware.org/?probe=42d07a20da) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [be3349f314](https://linux-hardware.org/?probe=be3349f314) | Feb 29, 2024 |
| Gigabyte      | H510M H                     | [e3f138dca5](https://linux-hardware.org/?probe=e3f138dca5) | Feb 28, 2024 |
| Gigabyte      | H510M H                     | [3f8d7911a8](https://linux-hardware.org/?probe=3f8d7911a8) | Feb 28, 2024 |
| Unknown       | T610D11-ALD                 | [5015ded00e](https://linux-hardware.org/?probe=5015ded00e) | Feb 22, 2024 |
| Unknown       | TA320 Series                | [df96f8b57d](https://linux-hardware.org/?probe=df96f8b57d) | Feb 16, 2024 |
| ASUSTek       | PRIME H510T2/CSM            | [6b8f0a0684](https://linux-hardware.org/?probe=6b8f0a0684) | Feb 09, 2024 |
| Gigabyte      | B760M DS3H DDR4             | [672b95fe29](https://linux-hardware.org/?probe=672b95fe29) | Feb 08, 2024 |
| Gigabyte      | B365M H                     | [ac7a22a8f4](https://linux-hardware.org/?probe=ac7a22a8f4) | Jan 30, 2024 |
| Unknown       | T360D11                     | [4f06f14ee6](https://linux-hardware.org/?probe=4f06f14ee6) | Jan 30, 2024 |
| Gigabyte      | B360HD3                     | [7a7e6d1518](https://linux-hardware.org/?probe=7a7e6d1518) | Jan 30, 2024 |
| Gigabyte      | B75M-D3V                    | [5628f77cd1](https://linux-hardware.org/?probe=5628f77cd1) | Jan 30, 2024 |
| ASUSTek       | X99-E WS                    | [92cb95eaef](https://linux-hardware.org/?probe=92cb95eaef) | Jan 25, 2024 |
| ASRock        | B365M-ITX/ac                | [1a48a2a936](https://linux-hardware.org/?probe=1a48a2a936) | Jan 24, 2024 |
| ASRock        | B365M-ITX/ac                | [e7719cba1d](https://linux-hardware.org/?probe=e7719cba1d) | Jan 24, 2024 |
| ASRock        | B365M-ITX/ac                | [b2abf616b0](https://linux-hardware.org/?probe=b2abf616b0) | Jan 24, 2024 |
| HP            | 3399                        | [5126e6fb32](https://linux-hardware.org/?probe=5126e6fb32) | Jan 23, 2024 |
| Foxconn       | 2ABF                        | [4983fd3ab4](https://linux-hardware.org/?probe=4983fd3ab4) | Jan 22, 2024 |
| ASRock        | B365M-ITX/ac                | [45d94979a5](https://linux-hardware.org/?probe=45d94979a5) | Jan 19, 2024 |
| MSI           | PRO H610M-E DDR4            | [66e82c879d](https://linux-hardware.org/?probe=66e82c879d) | Jan 19, 2024 |
| MSI           | PRO H610M-E DDR4            | [af8a99bcf3](https://linux-hardware.org/?probe=af8a99bcf3) | Jan 19, 2024 |
| ASRock        | H81M-VG4 R2.0               | [f13e1664ba](https://linux-hardware.org/?probe=f13e1664ba) | Jan 12, 2024 |
| BESHTAU       | B560RU V51                  | [dec20966d4](https://linux-hardware.org/?probe=dec20966d4) | Jan 11, 2024 |
| ASUSTek       | H97M-E                      | [090fcf5a52](https://linux-hardware.org/?probe=090fcf5a52) | Dec 21, 2023 |
| Lenovo        | ThinkCentre A70 7099L8G     | [9720608634](https://linux-hardware.org/?probe=9720608634) | Dec 20, 2023 |
| ASUSTek       | PRIME B360M-K               | [d52ec68e39](https://linux-hardware.org/?probe=d52ec68e39) | Dec 18, 2023 |
| Biostar       | H610MH                      | [6a0d454360](https://linux-hardware.org/?probe=6a0d454360) | Dec 18, 2023 |
| MSI           | A320M-A PRO                 | [0542ba556a](https://linux-hardware.org/?probe=0542ba556a) | Dec 10, 2023 |
| ASRock        | B365M-ITX/ac                | [01d47685dd](https://linux-hardware.org/?probe=01d47685dd) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ae4263fce1](https://linux-hardware.org/?probe=ae4263fce1) | Nov 28, 2023 |
| Gigabyte      | H410M S2H V2                | [07a85d20b8](https://linux-hardware.org/?probe=07a85d20b8) | Nov 27, 2023 |
| ASUSTek       | P8H61 PRO                   | [f5ae04b987](https://linux-hardware.org/?probe=f5ae04b987) | Nov 22, 2023 |
| Dell          | 0MGK50 A02                  | [44cca29f66](https://linux-hardware.org/?probe=44cca29f66) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | [e029a02461](https://linux-hardware.org/?probe=e029a02461) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | [966108e5dc](https://linux-hardware.org/?probe=966108e5dc) | Nov 21, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [b95aa31de0](https://linux-hardware.org/?probe=b95aa31de0) | Nov 21, 2023 |
| Gigabyte      | H61M-S1                     | [5b55e90cd2](https://linux-hardware.org/?probe=5b55e90cd2) | Nov 20, 2023 |
| ASUSTek       | Z87-A                       | [ef419190cb](https://linux-hardware.org/?probe=ef419190cb) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | [c492bd0c05](https://linux-hardware.org/?probe=c492bd0c05) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [05b1279d72](https://linux-hardware.org/?probe=05b1279d72) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | [d203bd1f2e](https://linux-hardware.org/?probe=d203bd1f2e) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | [3fb45b3fae](https://linux-hardware.org/?probe=3fb45b3fae) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | [1e85870bb4](https://linux-hardware.org/?probe=1e85870bb4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d97ba119eb](https://linux-hardware.org/?probe=d97ba119eb) | Nov 20, 2023 |
| Unknown       | TA320 Series                | [2ba015f4da](https://linux-hardware.org/?probe=2ba015f4da) | Nov 20, 2023 |
| ASRock        | B365M-ITX/ac                | [d9aef8d62e](https://linux-hardware.org/?probe=d9aef8d62e) | Nov 20, 2023 |
| ONDA          | H410D4 IPC                  | [5ace66c92d](https://linux-hardware.org/?probe=5ace66c92d) | Nov 20, 2023 |
| BESHTAU       | B560RU V51                  | [188829d0c2](https://linux-hardware.org/?probe=188829d0c2) | Nov 20, 2023 |
| ICL           | H410SB-TM2                  | [d63641c6e3](https://linux-hardware.org/?probe=d63641c6e3) | Nov 17, 2023 |
| Gigabyte      | B75M-D3V                    | [2ca3738c72](https://linux-hardware.org/?probe=2ca3738c72) | Nov 17, 2023 |
| ASRock        | H81M-DG4                    | [089b0f3839](https://linux-hardware.org/?probe=089b0f3839) | Nov 17, 2023 |
| ASRock        | B365M Pro4-F                | [cc09f89cd0](https://linux-hardware.org/?probe=cc09f89cd0) | Nov 09, 2023 |
| ASRock        | B365M Pro4-F                | [17ec369170](https://linux-hardware.org/?probe=17ec369170) | Nov 09, 2023 |
| Gigabyte      | A320M-H-CF                  | [290c167538](https://linux-hardware.org/?probe=290c167538) | Nov 08, 2023 |
| Gigabyte      | B75M-D3V                    | [c6d1fc4965](https://linux-hardware.org/?probe=c6d1fc4965) | Oct 31, 2023 |
| Gigabyte      | H510M H                     | [d89e17690d](https://linux-hardware.org/?probe=d89e17690d) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [893389d935](https://linux-hardware.org/?probe=893389d935) | Oct 25, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [9bf87234d6](https://linux-hardware.org/?probe=9bf87234d6) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [d1f56e838d](https://linux-hardware.org/?probe=d1f56e838d) | Oct 23, 2023 |
| MSI           | A320M-A PRO                 | [6290cec60c](https://linux-hardware.org/?probe=6290cec60c) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | [287fa14302](https://linux-hardware.org/?probe=287fa14302) | Oct 20, 2023 |
| Gigabyte      | B75M-D3V                    | [0fd9732532](https://linux-hardware.org/?probe=0fd9732532) | Oct 19, 2023 |
| Unknown       | Unknown                     | [9947f3f38b](https://linux-hardware.org/?probe=9947f3f38b) | Oct 17, 2023 |
| ASRock        | H510M-HVS R2.0              | [83c36787ea](https://linux-hardware.org/?probe=83c36787ea) | Oct 17, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6457a793cd](https://linux-hardware.org/?probe=6457a793cd) | Oct 14, 2023 |
| Lenovo        | 3752 NOK                    | [e3eda8aae7](https://linux-hardware.org/?probe=e3eda8aae7) | Oct 10, 2023 |
| Lenovo        | 3752 NOK                    | [5e3d37b336](https://linux-hardware.org/?probe=5e3d37b336) | Oct 05, 2023 |
| Gigabyte      | H61M-DS2H                   | [f3e31ed154](https://linux-hardware.org/?probe=f3e31ed154) | Sep 22, 2023 |
| Unknown       | DMB-A520-MCA01              | [a959513e7c](https://linux-hardware.org/?probe=a959513e7c) | Sep 18, 2023 |
| Gigabyte      | H110M-H-CF                  | [5eadb71ae4](https://linux-hardware.org/?probe=5eadb71ae4) | Sep 15, 2023 |
| ASRock        | H510M-HVS R2.0              | [018a3b8abe](https://linux-hardware.org/?probe=018a3b8abe) | Sep 08, 2023 |
| MSI           | MS-B0A41                    | [c93409061c](https://linux-hardware.org/?probe=c93409061c) | Sep 06, 2023 |
| DEPO Compu... | DPH410S                     | [88076446b3](https://linux-hardware.org/?probe=88076446b3) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | [201a0612e4](https://linux-hardware.org/?probe=201a0612e4) | Aug 18, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| Gigabyte      | B360HD3                     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| Biostar       | H610MH                      | [ba1951d1fa](https://linux-hardware.org/?probe=ba1951d1fa) | Jun 19, 2023 |
| ASRock        | A320M-HDV R4.0              | [2a3c6cf0ab](https://linux-hardware.org/?probe=2a3c6cf0ab) | Jun 14, 2023 |
| Gigabyte      | H510M H                     | [337e4a106e](https://linux-hardware.org/?probe=337e4a106e) | Jun 13, 2023 |
| Dell          | 0VNM11 A01                  | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| Gigabyte      | B560M D3H                   | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| HP            | 83F0                        | [77cfad8631](https://linux-hardware.org/?probe=77cfad8631) | May 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | [a98cdfee26](https://linux-hardware.org/?probe=a98cdfee26) | May 25, 2023 |
| Gigabyte      | Z77-DS3H                    | [1e1fb2110f](https://linux-hardware.org/?probe=1e1fb2110f) | May 24, 2023 |
| MSI           | H510M-A PRO                 | [c5f452ea28](https://linux-hardware.org/?probe=c5f452ea28) | May 18, 2023 |
| Aquarius      | AQH410T                     | [aeeb40c393](https://linux-hardware.org/?probe=aeeb40c393) | May 04, 2023 |
| Unknown       | Unknown                     | [3522381ca7](https://linux-hardware.org/?probe=3522381ca7) | May 02, 2023 |
| Unknown       | Unknown                     | [4ec0da1442](https://linux-hardware.org/?probe=4ec0da1442) | May 02, 2023 |
| MSI           | A520M PRO                   | [6d37fb0e46](https://linux-hardware.org/?probe=6d37fb0e46) | May 02, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [41d545e4d7](https://linux-hardware.org/?probe=41d545e4d7) | Apr 28, 2023 |
| ASRock        | B365M-ITX/ac                | [e4c8218911](https://linux-hardware.org/?probe=e4c8218911) | Apr 27, 2023 |
| Gigabyte      | B365M H                     | [aca220e594](https://linux-hardware.org/?probe=aca220e594) | Apr 22, 2023 |
| Gigabyte      | H310M S2H x.x               | [eec2055c19](https://linux-hardware.org/?probe=eec2055c19) | Apr 20, 2023 |
| Intel         | DH61BF AAG81311-101         | [a9329736fb](https://linux-hardware.org/?probe=a9329736fb) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | [e2ed275252](https://linux-hardware.org/?probe=e2ed275252) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | [a6aaf5f17a](https://linux-hardware.org/?probe=a6aaf5f17a) | Apr 19, 2023 |
| MSI           | G41M-P33 Combo              | [d2623477d9](https://linux-hardware.org/?probe=d2623477d9) | Apr 10, 2023 |
| Intel         | D945GNT AAC96315-405        | [cdfdfbcda4](https://linux-hardware.org/?probe=cdfdfbcda4) | Apr 07, 2023 |
| Intel         | DH61BF AAG81311-101         | [49921908d1](https://linux-hardware.org/?probe=49921908d1) | Apr 06, 2023 |
| MSI           | PRO Z790-A WIFI             | [5fd883493a](https://linux-hardware.org/?probe=5fd883493a) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | [44b5c81131](https://linux-hardware.org/?probe=44b5c81131) | Apr 03, 2023 |
| Quanta        | 2AC5 100                    | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| MSI           | G41M-P33 Combo              | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| HP            | 0AA4h                       | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D945GNT AAC96315-405        | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| DEPO Compu... | MS-7846                     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| Intel         | D945GNT AAC96315-405        | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Biostar       | H610MH                      | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| HP            | 0B4Ch D                     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| ASRock        | H61M-DGS                    | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| Gigabyte      | B560M AORUS PRO             | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| HP            | 8599                        | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Intel         | D945GNT AAC96315-405        | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| Aquarius      | AQB560M                     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| Aquarius      | AQB560M                     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| Gigabyte      | B365M H                     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Intel         | DH61CR AAG14064-204         | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| HP            | 18E7                        | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| iRU           | v1.0                        | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| ICL           | H410SB                      | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| MSI           | PRO B660M-E DDR4            | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| Gigabyte      | B560M DS3H V2               | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| MSI           | H510M-A PRO                 | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| Gigabyte      | B365M DS3H                  | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Gigabyte      | M61SME-S2                   | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Compal        | DIP00                       | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| ASRock        | H61M-VG4                    | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| HP            | 8599                        | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| HP            | 8599                        | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| Gigabyte      | B365M H                     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| DEPO Compu... | DPH410S                     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | H81M-K                      | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| HP            | 18E4                        | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Gigabyte      | H610M S2H DDR4              | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| MSI           | PRO H610M-E DDR4            | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| Unknown       | T310D11                     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Gigabyte      | B360HD3                     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | PRIME B365M-A               | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| DEPO Compu... | DPH410S                     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| MSI           | B450-A PRO MAX              | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Gigabyte      | M61SME-S2                   | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| MSI           | B450-A PRO MAX              | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| ASUSTek       | PB62                        | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Gigabyte      | B365M DS3H                  | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| ASUSTek       | P7H55-M                     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| ASRock        | H510M-HVS R2.0              | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| Gigabyte      | B365M DS3H                  | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Gigabyte      | X570S UD                    | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| ASUSTek       | PRIME Z590-P                | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| Gigabyte      | B365M DS3H                  | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| ASRock        | P43Twins1600                | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASRock        | H310CM-DVS                  | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| HP            | 2179                        | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| ASRock        | H61M-VG4                    | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Gigabyte      | A520M DS3H                  | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Gigabyte      | B560M H                     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| ASUSTek       | H81M-K                      | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | 3708 NOK                    | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Gigabyte      | H510M S2H                   | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| ASUSTek       | H81M-K                      | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| HP            | 1495                        | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| MSI           | H55M-E33                    | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| ASRock        | B360M-HDV                   | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| RDW           | MB-B450M V.1                | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| Gigabyte      | H110M-S2-CF                 | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Unknown       | Unknown                     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| ASRock        | N68-VS3 FX                  | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| ASRock        | H110M-DVS R2.0              | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Dell          | 040DDP A00                  | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| DEPO Compu... | DPH310T                     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Gigabyte      | 970A-D3                     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| ASUSTek       | M2N68-AM Plus               | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| MSI           | A520M PRO                   | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte      | B365M H                     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek       | H81M-K                      | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock        | B560 Pro4                   | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte      | B75M-D3V                    | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | H110-PLUS                   | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte      | B560M DS3H                  | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius      | AQB560M                     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock        | H470M-HDV                   | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek       | H110-PLUS                   | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte      | B365M DS3H                  | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek       | H81M-K                      | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3   | 170      | 56.67%  |
| Red OS 7.3.1 | 50       | 16.67%  |
| Red OS 7.3.2 | 49       | 16.33%  |
| Red OS 8.0   | 22       | 7.33%   |
| Red OS 7.2   | 9        | 3%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 285      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.1.52-1.el7.3.x86_64   | 65       | 20.77%  |
| 5.10.29-1.el7.x86_64    | 28       | 8.95%   |
| 5.15.10-1.el7.x86_64    | 27       | 8.63%   |
| 5.15.87-1.el7.3.x86_64  | 26       | 8.31%   |
| 5.15.35-5.el7.3.x86_64  | 19       | 6.07%   |
| 5.15.72-1.el7.3.x86_64  | 18       | 5.75%   |
| 5.15.78-2.el7.3.x86_64  | 11       | 3.51%   |
| 6.6.6-1.red80.x86_64    | 10       | 3.19%   |
| 5.15.35-1.el7.3.x86_64  | 10       | 3.19%   |
| 6.1.110-1.el7.3.x86_64  | 9        | 2.88%   |
| 5.15.131-1.el7.3.x86_64 | 9        | 2.88%   |
| 6.6.51-1.red80.x86_64   | 8        | 2.56%   |
| 5.14.9-1.el7.x86_64     | 8        | 2.56%   |
| 5.10.29-3.el7.x86_64    | 8        | 2.56%   |
| 6.1.44-1.el7.3.x86_64   | 7        | 2.24%   |
| 5.15.35-4.el7.3.x86_64  | 7        | 2.24%   |
| 4.19.79-1.el7.x86_64    | 7        | 2.24%   |
| 6.1.20-2.el7.3.x86_64   | 5        | 1.6%    |
| 6.1.94-1.el7.3.x86_64   | 4        | 1.28%   |
| 5.15.167-1.el7.3.x86_64 | 4        | 1.28%   |
| 6.1.38-2.el7.3.x86_64   | 3        | 0.96%   |
| 5.15.125-1.el7.3.x86_64 | 3        | 0.96%   |
| 5.15.10-3.el7.x86_64    | 3        | 0.96%   |
| 5.15.10-2.el7.x86_64    | 3        | 0.96%   |
| 6.6.34-1.red80.x86_64   | 2        | 0.64%   |
| 6.6.26-1.red80.x86_64   | 2        | 0.64%   |
| 6.1.52-1.red80.x86_64   | 1        | 0.32%   |
| 6.1.11-1.el7.3.x86_64   | 1        | 0.32%   |
| 5.10.24-3.el7.x86_64    | 1        | 0.32%   |
| 5.10.24-2.el7.x86_64    | 1        | 0.32%   |
| 5.10.1-1.el7.x86_64     | 1        | 0.32%   |
| 4.19.56-2.el7.x86_64    | 1        | 0.32%   |
| 4.19.204-1.el7.x86_64   | 1        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.52   | 66       | 21.29%  |
| 5.10.29  | 36       | 11.61%  |
| 5.15.35  | 33       | 10.65%  |
| 5.15.10  | 33       | 10.65%  |
| 5.15.87  | 26       | 8.39%   |
| 5.15.72  | 18       | 5.81%   |
| 5.15.78  | 11       | 3.55%   |
| 6.6.6    | 10       | 3.23%   |
| 6.1.110  | 9        | 2.9%    |
| 5.15.131 | 9        | 2.9%    |
| 6.6.51   | 8        | 2.58%   |
| 5.14.9   | 8        | 2.58%   |
| 6.1.44   | 7        | 2.26%   |
| 4.19.79  | 7        | 2.26%   |
| 6.1.20   | 5        | 1.61%   |
| 6.1.94   | 4        | 1.29%   |
| 5.15.167 | 4        | 1.29%   |
| 6.1.38   | 3        | 0.97%   |
| 5.15.125 | 3        | 0.97%   |
| 6.6.34   | 2        | 0.65%   |
| 6.6.26   | 2        | 0.65%   |
| 5.10.24  | 2        | 0.65%   |
| 6.1.11   | 1        | 0.32%   |
| 5.10.1   | 1        | 0.32%   |
| 4.19.56  | 1        | 0.32%   |
| 4.19.204 | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 125      | 42.09%  |
| 6.1     | 95       | 31.99%  |
| 5.10    | 39       | 13.13%  |
| 6.6     | 21       | 7.07%   |
| 4.19    | 9        | 3.03%   |
| 5.14    | 8        | 2.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 285      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 240      | 81.63%  |
| Cinnamon   | 30       | 10.2%   |
| X-Cinnamon | 10       | 3.4%    |
| KDE5       | 6        | 2.04%   |
| Unknown    | 5        | 1.7%    |
| GNOME      | 3        | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 253      | 87.54%  |
| Tty     | 26       | 9%      |
| Wayland | 8        | 2.77%   |
| Unknown | 2        | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 263      | 91%     |
| SDDM    | 10       | 3.46%   |
| Unknown | 9        | 3.11%   |
| LightDM | 7        | 2.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 191      | 65.64%  |
| Unknown | 95       | 32.65%  |
| en_US   | 5        | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 199      | 68.62%  |
| BIOS | 91       | 31.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 281      | 97.91%  |
| Btrfs   | 5        | 1.74%   |
| Unknown | 1        | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 202      | 69.9%   |
| MBR     | 82       | 28.37%  |
| Unknown | 5        | 1.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 270      | 92.78%  |
| Yes       | 21       | 7.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 79.09%  |
| Yes       | 60       | 20.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 74       | 25.96%  |
| ASUSTek Computer    | 50       | 17.54%  |
| MSI                 | 33       | 11.58%  |
| ASRock              | 33       | 11.58%  |
| Hewlett-Packard     | 14       | 4.91%   |
| Unknown             | 10       | 3.51%   |
| Lenovo              | 9        | 3.16%   |
| DEPO Computers      | 9        | 3.16%   |
| Aquarius            | 9        | 3.16%   |
| Intel               | 7        | 2.46%   |
| Dell                | 6        | 2.11%   |
| Foxconn             | 4        | 1.4%    |
| BESHTAU             | 4        | 1.4%    |
| ICL                 | 3        | 1.05%   |
| Biostar             | 3        | 1.05%   |
| ECS                 | 2        | 0.7%    |
| Acer                | 2        | 0.7%    |
| Supermicro          | 1        | 0.35%   |
| RDW                 | 1        | 0.35%   |
| Quanta              | 1        | 0.35%   |
| ONDA                | 1        | 0.35%   |
| Kraftway            | 1        | 0.35%   |
| iRU                 | 1        | 0.35%   |
| INTECH PRO          | 1        | 0.35%   |
| INFERIT             | 1        | 0.35%   |
| Huanan              | 1        | 0.35%   |
| Graviton            | 1        | 0.35%   |
| Compal              | 1        | 0.35%   |
| Colorful Technology | 1        | 0.35%   |
| 3Logic Group        | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 10       | 3.51%   |
| ASUS All Series              | 7        | 2.46%   |
| MSI MS-7677                  | 6        | 2.11%   |
| Gigabyte B365M DS3H          | 6        | 2.11%   |
| ASRock H510M-HVS R2.0        | 5        | 1.75%   |
| ASRock B365M-ITX/ac          | 5        | 1.75%   |
| Gigabyte H510M H             | 4        | 1.4%    |
| DEPO Computers DPH410S       | 4        | 1.4%    |
| DEPO Computers DPH310T       | 4        | 1.4%    |
| MSI MS-7D48                  | 3        | 1.05%   |
| MSI MS-7D14                  | 3        | 1.05%   |
| MSI MS-7C51                  | 3        | 1.05%   |
| Intel D945GNT AAC96315-405   | 3        | 1.05%   |
| Gigabyte H110M-S2            | 3        | 1.05%   |
| Gigabyte A320M-S2H           | 3        | 1.05%   |
| Biostar H610MH               | 3        | 1.05%   |
| ASUS PRIME H510T2/CSM        | 3        | 1.05%   |
| ASUS PRIME H310M-R R2.0      | 3        | 1.05%   |
| ASRock H61M-DGS              | 3        | 1.05%   |
| ASRock H610M-HVS             | 3        | 1.05%   |
| MSI MS-7D22                  | 2        | 0.7%    |
| Intel DH61BF AAG81311-101    | 2        | 0.7%    |
| ICL RAY B102                 | 2        | 0.7%    |
| HP ProDesk 400 G6 MT         | 2        | 0.7%    |
| Gigabyte H81M-S2VP           | 2        | 0.7%    |
| Gigabyte H510M S2H V2        | 2        | 0.7%    |
| Gigabyte H270-HD3            | 2        | 0.7%    |
| Gigabyte F2A55M-S1           | 2        | 0.7%    |
| Gigabyte B75M-D3V            | 2        | 0.7%    |
| Gigabyte B560M DS3H          | 2        | 0.7%    |
| Gigabyte B550 AORUS ELITE V2 | 2        | 0.7%    |
| Gigabyte B365M H             | 2        | 0.7%    |
| Gigabyte A520M S2H           | 2        | 0.7%    |
| Foxconn Pro3500 Series       | 2        | 0.7%    |
| Dell OptiPlex 7000           | 2        | 0.7%    |
| BESHTAU B560RU               | 2        | 0.7%    |
| ASUS PRIME B360M-C           | 2        | 0.7%    |
| ASUS PRIME B350M-K           | 2        | 0.7%    |
| ASUS PC                      | 2        | 0.7%    |
| ASUS P8H61 PRO               | 2        | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 20       | 7.02%   |
| Unknown                | 10       | 3.51%   |
| Gigabyte B365M         | 9        | 3.16%   |
| Gigabyte H510M         | 7        | 2.46%   |
| ASUS All               | 7        | 2.46%   |
| MSI MS-7677            | 6        | 2.11%   |
| Dell OptiPlex          | 6        | 2.11%   |
| Lenovo ThinkCentre     | 5        | 1.75%   |
| HP ProDesk             | 5        | 1.75%   |
| Gigabyte B560M         | 5        | 1.75%   |
| ASRock H510M-HVS       | 5        | 1.75%   |
| ASRock B365M-ITX       | 5        | 1.75%   |
| HP Compaq              | 4        | 1.4%    |
| Gigabyte A520M         | 4        | 1.4%    |
| Gigabyte A320M-S2H     | 4        | 1.4%    |
| DEPO Computers DPH410S | 4        | 1.4%    |
| DEPO Computers DPH310T | 4        | 1.4%    |
| MSI MS-7D48            | 3        | 1.05%   |
| MSI MS-7D14            | 3        | 1.05%   |
| MSI MS-7C51            | 3        | 1.05%   |
| Intel D945GNT          | 3        | 1.05%   |
| ICL RAY                | 3        | 1.05%   |
| Gigabyte H410M         | 3        | 1.05%   |
| Gigabyte H110M-S2      | 3        | 1.05%   |
| Gigabyte B550          | 3        | 1.05%   |
| Biostar H610MH         | 3        | 1.05%   |
| ASRock H61M-DGS        | 3        | 1.05%   |
| ASRock H610M-HVS       | 3        | 1.05%   |
| Aquarius Pro           | 3        | 1.05%   |
| MSI MS-7D22            | 2        | 0.7%    |
| Intel DH61CR           | 2        | 0.7%    |
| Intel DH61BF           | 2        | 0.7%    |
| Gigabyte H81M-S2VP     | 2        | 0.7%    |
| Gigabyte H310M         | 2        | 0.7%    |
| Gigabyte H270-HD3      | 2        | 0.7%    |
| Gigabyte F2A55M-S1     | 2        | 0.7%    |
| Gigabyte B75M-D3V      | 2        | 0.7%    |
| Gigabyte B450          | 2        | 0.7%    |
| Foxconn Pro3500        | 2        | 0.7%    |
| BESHTAU B560RU         | 2        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 56       | 19.65%  |
| 2022 | 33       | 11.58%  |
| 2019 | 32       | 11.23%  |
| 2018 | 25       | 8.77%   |
| 2011 | 19       | 6.67%   |
| 2020 | 18       | 6.32%   |
| 2012 | 18       | 6.32%   |
| 2013 | 14       | 4.91%   |
| 2016 | 11       | 3.86%   |
| 2014 | 11       | 3.86%   |
| 2023 | 9        | 3.16%   |
| 2010 | 9        | 3.16%   |
| 2017 | 8        | 2.81%   |
| 2015 | 6        | 2.11%   |
| 2009 | 4        | 1.4%    |
| 2007 | 4        | 1.4%    |
| 2024 | 3        | 1.05%   |
| 2006 | 3        | 1.05%   |
| 2008 | 2        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 285      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 279      | 97.89%  |
| Enabled  | 6        | 2.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 285      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 108      | 37.76%  |
| 16.01-24.0  | 74       | 25.87%  |
| 3.01-4.0    | 41       | 14.34%  |
| 8.01-16.0   | 35       | 12.24%  |
| 32.01-64.0  | 8        | 2.8%    |
| 1.01-2.0    | 7        | 2.45%   |
| 24.01-32.0  | 5        | 1.75%   |
| 2.01-3.0    | 3        | 1.05%   |
| 64.01-256.0 | 3        | 1.05%   |
| 0.51-1.0    | 1        | 0.35%   |
| Unknown     | 1        | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 119      | 39.27%  |
| 2.01-3.0  | 69       | 22.77%  |
| 4.01-8.0  | 46       | 15.18%  |
| 3.01-4.0  | 35       | 11.55%  |
| 0.51-1.0  | 20       | 6.6%    |
| 8.01-16.0 | 10       | 3.3%    |
| 0.01-0.5  | 3        | 0.99%   |
| Unknown   | 1        | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 201      | 68.84%  |
| 2      | 67       | 22.95%  |
| 3      | 16       | 5.48%   |
| 4      | 5        | 1.71%   |
| 5      | 2        | 0.68%   |
| 6      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 201      | 70.03%  |
| Yes       | 86       | 29.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 284      | 99.65%  |
| No        | 1        | 0.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 221      | 76.74%  |
| Yes       | 67       | 23.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 238      | 82.64%  |
| Yes       | 50       | 17.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 284      | 99.65%  |
| Ukraine | 1        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 52       | 17.93%  |
| Salekhard         | 33       | 11.38%  |
| Murom             | 28       | 9.66%   |
| Novy Urengoy      | 19       | 6.55%   |
| Perm              | 11       | 3.79%   |
| Zima              | 10       | 3.45%   |
| Yekaterinburg     | 7        | 2.41%   |
| St Petersburg     | 7        | 2.41%   |
| Polazna           | 7        | 2.41%   |
| Labytnangi        | 7        | 2.41%   |
| Volgograd         | 6        | 2.07%   |
| Krasnodar         | 5        | 1.72%   |
| Vladimir          | 3        | 1.03%   |
| Tver              | 3        | 1.03%   |
| Stavropol         | 3        | 1.03%   |
| Novosibirsk       | 3        | 1.03%   |
| Muromskiy         | 3        | 1.03%   |
| Kurgan            | 3        | 1.03%   |
| Kaluga            | 3        | 1.03%   |
| Chelyabinsk       | 3        | 1.03%   |
| Bryansk           | 3        | 1.03%   |
| Barnaul           | 3        | 1.03%   |
| Balashikha        | 3        | 1.03%   |
| Veliky Novgorod   | 2        | 0.69%   |
| Ulyanovsk         | 2        | 0.69%   |
| Tomsk             | 2        | 0.69%   |
| Surgut            | 2        | 0.69%   |
| Pushkino          | 2        | 0.69%   |
| Penza             | 2        | 0.69%   |
| Orenburg          | 2        | 0.69%   |
| Nal'chik          | 2        | 0.69%   |
| Nadym             | 2        | 0.69%   |
| Lipetsk           | 2        | 0.69%   |
| Krasnoyarsk       | 2        | 0.69%   |
| Kol'chugino       | 2        | 0.69%   |
| Kirov             | 2        | 0.69%   |
| Khabarovsk        | 2        | 0.69%   |
| Irkutsk           | 2        | 0.69%   |
| Baksan            | 2        | 0.69%   |
| Yuzhno-Sakhalinsk | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 73       | 99     | 18.81%  |
| WDC                          | 52       | 63     | 13.4%   |
| Toshiba                      | 46       | 65     | 11.86%  |
| Kingston                     | 30       | 32     | 7.73%   |
| A-DATA Technology            | 27       | 30     | 6.96%   |
| Samsung Electronics          | 24       | 32     | 6.19%   |
| Apacer                       | 13       | 13     | 3.35%   |
| Foxline                      | 11       | 11     | 2.84%   |
| KingSpec                     | 10       | 11     | 2.58%   |
| AGI                          | 8        | 8      | 2.06%   |
| Hitachi                      | 7        | 7      | 1.8%    |
| ExeGate                      | 7        | 9      | 1.8%    |
| SanDisk                      | 6        | 10     | 1.55%   |
| Patriot                      | 6        | 6      | 1.55%   |
| Crucial                      | 6        | 10     | 1.55%   |
| SPCC                         | 5        | 6      | 1.29%   |
| Netac                        | 5        | 5      | 1.29%   |
| Intel                        | 5        | 5      | 1.29%   |
| China                        | 5        | 5      | 1.29%   |
| AMD                          | 4        | 4      | 1.03%   |
| Qumo                         | 3        | 3      | 0.77%   |
| Smartbuy                     | 2        | 2      | 0.52%   |
| Silicon Motion               | 2        | 2      | 0.52%   |
| Shenzhen Longsys Electronics | 2        | 2      | 0.52%   |
| Plextor                      | 2        | 2      | 0.52%   |
| Phison                       | 2        | 2      | 0.52%   |
| MSI                          | 2        | 2      | 0.52%   |
| KIOXIA-EXCERIA               | 2        | 2      | 0.52%   |
| HYDRA                        | 2        | 2      | 0.52%   |
| GOODRAM                      | 2        | 2      | 0.52%   |
| Unknown                      | 2        | 2      | 0.52%   |
| XPG                          | 1        | 1      | 0.26%   |
| Verbatim                     | 1        | 1      | 0.26%   |
| USB                          | 1        | 1      | 0.26%   |
| Unknown                      | 1        | 1      | 0.26%   |
| Phison Electronics           | 1        | 1      | 0.26%   |
| OSCOO                        | 1        | 1      | 0.26%   |
| Micron Technology            | 1        | 1      | 0.26%   |
| MAXIO Technology (Hangzhou)  | 1        | 1      | 0.26%   |
| KIOXIA                       | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                  | 17       | 4.19%   |
| Seagate ST500DM002-1BD142 500GB      | 13       | 3.2%    |
| Seagate ST1000DM010-2EP102 1TB       | 11       | 2.71%   |
| Kingston SA400S37240G 240GB SSD      | 10       | 2.46%   |
| Toshiba DT01ACA100 1TB               | 9        | 2.22%   |
| A-DATA SX6000PNP 256GB               | 9        | 2.22%   |
| Toshiba HDWL110 1TB                  | 6        | 1.48%   |
| Kingston SA400S37480G 480GB SSD      | 6        | 1.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 5        | 1.23%   |
| Seagate ST1000LM049-2GH172 1TB       | 5        | 1.23%   |
| Apacer AS2280P4 256GB                | 5        | 1.23%   |
| Toshiba DT01ACA050 500GB             | 4        | 0.99%   |
| Seagate ST3160811AS 160GB            | 4        | 0.99%   |
| Seagate ST1000DM010-2DM162 1TB       | 4        | 0.99%   |
| Samsung SSD 860 EVO 250GB            | 4        | 0.99%   |
| Kingston SA400S37120G 120GB SSD      | 4        | 0.99%   |
| KingSpec P3-256 256GB                | 4        | 0.99%   |
| Apacer AS340 240GB SSD               | 4        | 0.99%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 3        | 0.74%   |
| WDC WD Blue SA510 2.5 500GB          | 3        | 0.74%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB | 3        | 0.74%   |
| Toshiba HDWD105 500GB                | 3        | 0.74%   |
| Seagate ST1000DM003-1ER162 1TB       | 3        | 0.74%   |
| Samsung SSD 980 PRO 500GB            | 3        | 0.74%   |
| Samsung SSD 870 EVO 250GB            | 3        | 0.74%   |
| Patriot Burst Elite 240GB SSD        | 3        | 0.74%   |
| Foxline FLSSD240X5SE 240GB           | 3        | 0.74%   |
| Crucial CT240BX500SSD1 240GB         | 3        | 0.74%   |
| AGI AGI512G16AI198 512GB             | 3        | 0.74%   |
| A-DATA SX6000PNP 512GB               | 3        | 0.74%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2        | 0.49%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2        | 0.49%   |
| WDC WD10EZEX-00BBHA0 1TB             | 2        | 0.49%   |
| Toshiba MK2565GSX 250GB              | 2        | 0.49%   |
| Toshiba DT01ACA050 LENOVO 500GB      | 2        | 0.49%   |
| SPCC Solid State Disk 256GB          | 2        | 0.49%   |
| SPCC M.2 PCIe SSD 512GB              | 2        | 0.49%   |
| Seagate ST500DM005 HD502HJ 500GB     | 2        | 0.49%   |
| Seagate ST3500418AS 500GB            | 2        | 0.49%   |
| Seagate ST3500413AS 500GB            | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 72       | 98     | 43.37%  |
| Toshiba             | 45       | 64     | 27.11%  |
| WDC                 | 36       | 44     | 21.69%  |
| Hitachi             | 7        | 7      | 4.22%   |
| Samsung Electronics | 4        | 5      | 2.41%   |
| USB                 | 1        | 1      | 0.6%    |
| HGST                | 1        | 1      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 24       | 25     | 16.55%  |
| WDC                 | 14       | 14     | 9.66%   |
| Samsung Electronics | 11       | 13     | 7.59%   |
| KingSpec            | 10       | 11     | 6.9%    |
| A-DATA Technology   | 10       | 10     | 6.9%    |
| Foxline             | 8        | 8      | 5.52%   |
| Apacer              | 7        | 7      | 4.83%   |
| SanDisk             | 5        | 9      | 3.45%   |
| Patriot             | 5        | 5      | 3.45%   |
| ExeGate             | 5        | 6      | 3.45%   |
| Crucial             | 5        | 9      | 3.45%   |
| China               | 5        | 5      | 3.45%   |
| Intel               | 4        | 4      | 2.76%   |
| SPCC                | 3        | 4      | 2.07%   |
| Qumo                | 3        | 3      | 2.07%   |
| AGI                 | 3        | 3      | 2.07%   |
| Smartbuy            | 2        | 2      | 1.38%   |
| Plextor             | 2        | 2      | 1.38%   |
| Netac               | 2        | 2      | 1.38%   |
| KIOXIA-EXCERIA      | 2        | 2      | 1.38%   |
| HYDRA               | 2        | 2      | 1.38%   |
| GOODRAM             | 2        | 2      | 1.38%   |
| Verbatim            | 1        | 1      | 0.69%   |
| Toshiba             | 1        | 1      | 0.69%   |
| Seagate             | 1        | 1      | 0.69%   |
| OSCOO               | 1        | 1      | 0.69%   |
| Micron Technology   | 1        | 1      | 0.69%   |
| HS-SSD-E100         | 1        | 1      | 0.69%   |
| Digma               | 1        | 1      | 0.69%   |
| DEXP                | 1        | 1      | 0.69%   |
| Dahua               | 1        | 1      | 0.69%   |
| AMD                 | 1        | 1      | 0.69%   |
| Unknown             | 1        | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 152      | 220    | 41.53%  |
| SSD  | 135      | 159    | 36.89%  |
| NVMe | 78       | 89     | 21.31%  |
| MMC  | 1        | 1      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 237      | 373    | 73.6%   |
| NVMe | 78       | 89     | 24.22%  |
| SAS  | 6        | 6      | 1.86%   |
| MMC  | 1        | 1      | 0.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 171      | 215    | 60.64%  |
| 0.51-1.0   | 96       | 144    | 34.04%  |
| 1.01-2.0   | 8        | 12     | 2.84%   |
| 3.01-4.0   | 4        | 4      | 1.42%   |
| 2.01-3.0   | 2        | 2      | 0.71%   |
| 4.01-10.0  | 1        | 2      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 104      | 35.37%  |
| 251-500        | 82       | 27.89%  |
| 501-1000       | 55       | 18.71%  |
| 1001-2000      | 26       | 8.84%   |
| 51-100         | 12       | 4.08%   |
| 2001-3000      | 5        | 1.7%    |
| More than 3000 | 4        | 1.36%   |
| 21-50          | 3        | 1.02%   |
| Unknown        | 3        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 130      | 42.9%   |
| 21-50          | 83       | 27.39%  |
| 101-250        | 28       | 9.24%   |
| 51-100         | 26       | 8.58%   |
| 251-500        | 13       | 4.29%   |
| 501-1000       | 12       | 3.96%   |
| 1001-2000      | 4        | 1.32%   |
| Unknown        | 3        | 0.99%   |
| More than 3000 | 2        | 0.66%   |
| 2001-3000      | 2        | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 8        | 9      | 17.78%  |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 2      | 4.44%   |
| Toshiba MK2565GSX 250GB           | 2        | 2      | 4.44%   |
| Seagate ST3500413AS 500GB         | 2        | 2      | 4.44%   |
| Seagate ST3160811AS 160GB         | 2        | 2      | 4.44%   |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 6      | 4.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 2.22%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 1      | 2.22%   |
| WDC WD7500BPVT-00HXZT3 752GB      | 1        | 1      | 2.22%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 2      | 2.22%   |
| WDC WD5000AAKS-00D2B0 500GB       | 1        | 1      | 2.22%   |
| WDC WD3200AAKX-001CA0 320GB       | 1        | 1      | 2.22%   |
| WDC WD1600AAJS-00B4A0 160GB       | 1        | 1      | 2.22%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 2      | 2.22%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 1      | 2.22%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 2.22%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.22%   |
| WDC WD10EALX-009BA0 1TB           | 1        | 1      | 2.22%   |
| WDC WD1001FALS-00J7B1 1TB         | 1        | 1      | 2.22%   |
| WDC WD Blue SA510 2.5 500GB       | 1        | 1      | 2.22%   |
| Toshiba HDWD110 1TB               | 1        | 1      | 2.22%   |
| SPCC M.2 PCIe SSD 512GB           | 1        | 1      | 2.22%   |
| Seagate ST9500423AS 500GB         | 1        | 1      | 2.22%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 2.22%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 2.22%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 2.22%   |
| Seagate ST31000524NS 1TB          | 1        | 1      | 2.22%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 2.22%   |
| Samsung Electronics HD400LJ 400GB | 1        | 1      | 2.22%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 2.22%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 2.22%   |
| Hitachi HTS543216L9A300 160GB     | 1        | 1      | 2.22%   |
| Hitachi HDS5C1050CLA382 500GB     | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 26     | 44.44%  |
| WDC                 | 16       | 18     | 35.56%  |
| Toshiba             | 3        | 3      | 6.67%   |
| Samsung Electronics | 2        | 2      | 4.44%   |
| Hitachi             | 2        | 2      | 4.44%   |
| SPCC                | 1        | 1      | 2.22%   |
| Kingston            | 1        | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 26     | 50%     |
| WDC                 | 13       | 15     | 32.5%   |
| Toshiba             | 3        | 3      | 7.5%    |
| Samsung Electronics | 2        | 2      | 5%      |
| Hitachi             | 2        | 2      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 48     | 87.8%   |
| SSD  | 4        | 4      | 9.76%   |
| NVMe | 1        | 1      | 2.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST250LT012-9WS141 250GB   | 1        | 1      | 50%     |
| A-DATA Technology SX6000PNP 512GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 1        | 1      | 50%     |
| A-DATA Technology | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 253      | 396    | 82.14%  |
| Malfunc  | 41       | 53     | 13.31%  |
| Detected | 12       | 18     | 3.9%    |
| Failed   | 2        | 2      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 236      | 63.1%   |
| AMD                          | 44       | 11.76%  |
| Realtek Semiconductor        | 16       | 4.28%   |
| Phison Electronics           | 14       | 3.74%   |
| Samsung Electronics          | 12       | 3.21%   |
| Silicon Motion               | 9        | 2.41%   |
| ADATA Technology             | 7        | 1.87%   |
| Kingston Technology Company  | 6        | 1.6%    |
| SanDisk                      | 5        | 1.34%   |
| Nvidia                       | 4        | 1.07%   |
| JMicron Technology           | 4        | 1.07%   |
| Netac Technology             | 3        | 0.8%    |
| MAXIO Technology (Hangzhou)  | 3        | 0.8%    |
| ASMedia Technology           | 3        | 0.8%    |
| VIA Technologies             | 2        | 0.53%   |
| Shenzhen Longsys Electronics | 2        | 0.53%   |
| ShenZhen TIGO Semiconductor  | 1        | 0.27%   |
| Micron/Crucial Technology    | 1        | 0.27%   |
| Marvell Technology Group     | 1        | 0.27%   |
| KIOXIA                       | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                                               | 47       | 10.96%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 31       | 7.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                                      | 24       | 5.59%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 22       | 5.13%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                                                 | 21       | 4.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                                                         | 19       | 4.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 17       | 3.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 14       | 3.26%   |
| AMD 500 Series Chipset SATA Controller                                                                             | 14       | 3.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                                               | 13       | 3.03%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 12       | 2.8%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                                                  | 10       | 2.33%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                                                       | 10       | 2.33%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 9        | 2.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 9        | 2.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                                                          | 7        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5)                            | 7        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3)                            | 7        | 1.63%   |
| AMD 400 Series Chipset SATA Controller                                                                             | 7        | 1.63%   |
| Intel SATA Controller [RAID mode]                                                                                  | 6        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 5        | 1.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 4        | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 4        | 0.93%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                                                  | 4        | 0.93%   |
| Nvidia MCP61 SATA Controller                                                                                       | 4        | 0.93%   |
| Nvidia MCP61 IDE                                                                                                   | 4        | 0.93%   |
| JMicron JMB368 IDE controller                                                                                      | 4        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]                                       | 4        | 0.93%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)                             | 4        | 0.93%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                                              | 3        | 0.7%    |
| Intel Raptor Lake SATA AHCI Controller                                                                             | 3        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                                              | 3        | 0.7%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]                                        | 3        | 0.7%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]                                        | 3        | 0.7%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                                                      | 3        | 0.7%    |
| AMD 300 Series Chipset SATA Controller                                                                             | 3        | 0.7%    |
| VIA VT6415 PATA IDE Host Controller                                                                                | 2        | 0.47%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 2        | 0.47%   |
| Netac PCIe 3 SM based NVMe SSD (DRAM-less)                                                                         | 2        | 0.47%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                                           | 2        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 249      | 66.76%  |
| NVMe | 78       | 20.91%  |
| IDE  | 37       | 9.92%   |
| RAID | 9        | 2.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 237      | 83.16%  |
| AMD    | 48       | 16.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 20       | 7.02%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 19       | 6.67%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 18       | 6.32%   |
| Intel 12th Gen Core i5-12400                | 8        | 2.81%   |
| Intel 12th Gen Core i3-12100                | 8        | 2.81%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 7        | 2.46%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 2.46%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 7        | 2.46%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 6        | 2.11%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 5        | 1.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.4%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 1.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.4%    |
| Intel Core i5-10500 CPU @ 3.10GHz           | 4        | 1.4%    |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 4        | 1.4%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.4%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 3        | 1.05%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 3        | 1.05%   |
| Intel Pentium 4 CPU 3.06GHz                 | 3        | 1.05%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 3        | 1.05%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 1.05%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.05%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 1.05%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 3        | 1.05%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 1.05%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.05%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.05%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 0.7%    |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.7%    |
| Intel Core i5-9500 CPU @ 3.00GHz            | 2        | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.7%    |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2        | 0.7%    |
| Intel Core i5-4430 CPU @ 3.00GHz            | 2        | 0.7%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 0.7%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 89       | 31.23%  |
| Intel Core i3           | 50       | 17.54%  |
| Other                   | 31       | 10.88%  |
| Intel Core i7           | 18       | 6.32%   |
| AMD Ryzen 5             | 15       | 5.26%   |
| Intel Pentium Gold      | 13       | 4.56%   |
| Intel Pentium           | 12       | 4.21%   |
| Intel Celeron           | 9        | 3.16%   |
| AMD Ryzen 7             | 6        | 2.11%   |
| AMD Ryzen 3             | 6        | 2.11%   |
| Intel Core 2 Duo        | 5        | 1.75%   |
| Intel Xeon              | 4        | 1.4%    |
| AMD Ryzen 5 PRO         | 4        | 1.4%    |
| AMD A6                  | 4        | 1.4%    |
| Intel Pentium 4         | 3        | 1.05%   |
| AMD FX                  | 3        | 1.05%   |
| AMD Athlon II X2        | 3        | 1.05%   |
| AMD Ryzen 7 PRO         | 2        | 0.7%    |
| AMD Athlon              | 2        | 0.7%    |
| Intel Pentium Dual-Core | 1        | 0.35%   |
| Intel Pentium Dual      | 1        | 0.35%   |
| Intel Core 2            | 1        | 0.35%   |
| AMD Ryzen 9             | 1        | 0.35%   |
| AMD Phenom              | 1        | 0.35%   |
| AMD Athlon II X4        | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 106      | 37.19%  |
| 6      | 85       | 29.82%  |
| 2      | 63       | 22.11%  |
| 8      | 17       | 5.96%   |
| 1      | 8        | 2.81%   |
| 12     | 3        | 1.05%   |
| 20     | 1        | 0.35%   |
| 14     | 1        | 0.35%   |
| 3      | 1        | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 284      | 99.65%  |
| 2      | 1        | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 173      | 60.7%   |
| 1      | 112      | 39.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 284      | 99.65%  |
| Unknown        | 1        | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 51       | 17.65%  |
| 0x906ea    | 24       | 8.3%    |
| Unknown    | 22       | 7.61%   |
| 0x206a7    | 19       | 6.57%   |
| 0x306c3    | 18       | 6.23%   |
| 0x306a9    | 18       | 6.23%   |
| 0x90675    | 17       | 5.88%   |
| 0x906ed    | 13       | 4.5%    |
| 0x506e3    | 9        | 3.11%   |
| 0xa0671    | 8        | 2.77%   |
| 0x906e9    | 7        | 2.42%   |
| 0x906eb    | 6        | 2.08%   |
| 0x08600106 | 6        | 2.08%   |
| 0x1067a    | 5        | 1.73%   |
| 0x08108109 | 5        | 1.73%   |
| 0xa0655    | 4        | 1.38%   |
| 0x0a50000d | 4        | 1.38%   |
| 0x0a50000c | 4        | 1.38%   |
| 0xf49      | 3        | 1.04%   |
| 0x08101016 | 3        | 1.04%   |
| 0x0810100b | 3        | 1.04%   |
| 0x90672    | 2        | 0.69%   |
| 0x706a8    | 2        | 0.69%   |
| 0x6fd      | 2        | 0.69%   |
| 0x106e5    | 2        | 0.69%   |
| 0x08701021 | 2        | 0.69%   |
| 0x06006118 | 2        | 0.69%   |
| 0x06001119 | 2        | 0.69%   |
| 0x0600063e | 2        | 0.69%   |
| 0x010000c8 | 2        | 0.69%   |
| 0xb06f5    | 1        | 0.35%   |
| 0xb06f2    | 1        | 0.35%   |
| 0xa0654    | 1        | 0.35%   |
| 0xa0652    | 1        | 0.35%   |
| 0x6f6      | 1        | 0.35%   |
| 0x306f2    | 1        | 0.35%   |
| 0x206c2    | 1        | 0.35%   |
| 0x20652    | 1        | 0.35%   |
| 0x106a5    | 1        | 0.35%   |
| 0x10661    | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 58       | 20.35%  |
| KabyLake         | 57       | 20%     |
| Alderlake Hybrid | 23       | 8.07%   |
| Haswell          | 21       | 7.37%   |
| SandyBridge      | 20       | 7.02%   |
| IvyBridge        | 18       | 6.32%   |
| Zen 3            | 11       | 3.86%   |
| Skylake          | 11       | 3.86%   |
| Zen 2            | 10       | 3.51%   |
| Zen+             | 7        | 2.46%   |
| Zen              | 7        | 2.46%   |
| Penryn           | 5        | 1.75%   |
| K10              | 5        | 1.75%   |
| Icelake          | 5        | 1.75%   |
| Unknown          | 5        | 1.75%   |
| Core             | 4        | 1.4%    |
| Piledriver       | 3        | 1.05%   |
| NetBurst         | 3        | 1.05%   |
| Nehalem          | 3        | 1.05%   |
| Westmere         | 2        | 0.7%    |
| Goldmont plus    | 2        | 0.7%    |
| Excavator        | 2        | 0.7%    |
| Bulldozer        | 2        | 0.7%    |
| Broadwell        | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 199      | 67.69%  |
| AMD               | 47       | 15.99%  |
| Nvidia            | 45       | 15.31%  |
| ATI Technologies  | 2        | 0.68%   |
| ASPEED Technology | 1        | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 49       | 16.61%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 32       | 10.85%  |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 17       | 5.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16       | 5.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 16       | 5.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 12       | 4.07%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 10       | 3.39%   |
| Intel HD Graphics 530                                                       | 8        | 2.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 2.71%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 7        | 2.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 2.03%   |
| Intel HD Graphics 630                                                       | 6        | 2.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.36%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.36%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 1.02%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 3        | 1.02%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 3        | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.68%   |
| Nvidia GK107GL [Quadro K420]                                                | 2        | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.68%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 2        | 0.68%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 0.68%   |
| Intel AlderLake-S GT1                                                       | 2        | 0.68%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 2        | 0.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.68%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 2        | 0.68%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 0.68%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 0.68%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 0.68%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1        | 0.34%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.34%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.34%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.34%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.34%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.34%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 191      | 67.02%  |
| 1 x AMD        | 46       | 16.14%  |
| 1 x Nvidia     | 42       | 14.74%  |
| Intel + Nvidia | 2        | 0.7%    |
| 2 x AMD        | 1        | 0.35%   |
| Intel + AMD    | 1        | 0.35%   |
| 1 x ASPEED     | 1        | 0.35%   |
| AMD + Nvidia   | 1        | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 239      | 83.57%  |
| Unknown     | 35       | 12.24%  |
| Proprietary | 12       | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 207      | 72.63%  |
| 0.01-0.5   | 26       | 9.12%   |
| 1.01-2.0   | 22       | 7.72%   |
| 0.51-1.0   | 21       | 7.37%   |
| 3.01-4.0   | 4        | 1.4%    |
| 7.01-8.0   | 3        | 1.05%   |
| 5.01-6.0   | 1        | 0.35%   |
| 2.01-3.0   | 1        | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 44       | 16.86%  |
| Samsung Electronics  | 35       | 13.41%  |
| Acer                 | 24       | 9.2%    |
| ViewSonic            | 19       | 7.28%   |
| AOC                  | 16       | 6.13%   |
| Hewlett-Packard      | 15       | 5.75%   |
| Goldstar             | 15       | 5.75%   |
| BenQ                 | 14       | 5.36%   |
| Dell                 | 13       | 4.98%   |
| SGT                  | 9        | 3.45%   |
| RTK                  | 6        | 2.3%    |
| ASUSTek Computer     | 5        | 1.92%   |
| NEC Computers        | 4        | 1.53%   |
| Lenovo               | 4        | 1.53%   |
| Sony                 | 3        | 1.15%   |
| OOO                  | 3        | 1.15%   |
| Daewoo               | 3        | 1.15%   |
| CHD                  | 3        | 1.15%   |
| Ancor Communications | 3        | 1.15%   |
| VIE                  | 2        | 0.77%   |
| SKM                  | 2        | 0.77%   |
| Mi                   | 2        | 0.77%   |
| CHR                  | 2        | 0.77%   |
| XYK                  | 1        | 0.38%   |
| STD                  | 1        | 0.38%   |
| SAC                  | 1        | 0.38%   |
| JRY                  | 1        | 0.38%   |
| ITE                  | 1        | 0.38%   |
| HUAWEI               | 1        | 0.38%   |
| HLM                  | 1        | 0.38%   |
| HIB                  | 1        | 0.38%   |
| Fujitsu Siemens      | 1        | 0.38%   |
| DOY                  | 1        | 0.38%   |
| CS_                  | 1        | 0.38%   |
| BOE                  | 1        | 0.38%   |
| AVX                  | 1        | 0.38%   |
| ATN                  | 1        | 0.38%   |
| Unknown              | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 17       | 6.23%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 9        | 3.3%    |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 7        | 2.56%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 6        | 2.2%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 6        | 2.2%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 1.83%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 5        | 1.83%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 3        | 1.1%    |
| ViewSonic VA2046 SERIES VSC6D2E 1600x900 432x240mm 19.5-inch          | 3        | 1.1%    |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 3        | 1.1%    |
| RTK HDMI RTK2732 2560x1440 597x336mm 27.0-inch                        | 3        | 1.1%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 3        | 1.1%    |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                   | 3        | 1.1%    |
| Daewoo HDMI DWE2100 1280x1024 476x268mm 21.5-inch                     | 3        | 1.1%    |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 0.73%   |
| VIE IM27VL1 VIE1919 1920x1080 600x330mm 27.0-inch                     | 2        | 0.73%   |
| SKM LCD Monitor SKM9322 1920x1080 519x324mm 24.1-inch                 | 2        | 0.73%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 2        | 0.73%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 2        | 0.73%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 2        | 0.73%   |
| Samsung Electronics S24B300 SAM08B2 1920x1080 530x300mm 24.0-inch     | 2        | 0.73%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch     | 2        | 0.73%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 0.73%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 0.73%   |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                        | 2        | 0.73%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 0.73%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 2        | 0.73%   |
| OOO HDMI OOO2380 1920x1080 526x296mm 23.8-inch                        | 2        | 0.73%   |
| NEC Computers PA241W NEC67CE 1920x1200 518x324mm 24.1-inch            | 2        | 0.73%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 0.73%   |
| CHD DM-MONB2401 CHD2380 1920x1080 527x296mm 23.8-inch                 | 2        | 0.73%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2        | 0.73%   |
| ASUSTek Computer VA27D AUS270A 1920x1080 598x336mm 27.0-inch          | 2        | 0.73%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 2        | 0.73%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 0.73%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.73%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 2        | 0.73%   |
| Acer V233H ACR0090 1920x1080 510x287mm 23.0-inch                      | 2        | 0.73%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2        | 0.73%   |
| Acer ET241Y ACR056C 1920x1080 527x296mm 23.8-inch                     | 2        | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 154      | 63.11%  |
| 1280x1024 (SXGA)   | 27       | 11.07%  |
| 2560x1440 (QHD)    | 19       | 7.79%   |
| 1600x900 (HD+)     | 13       | 5.33%   |
| 1920x1200 (WUXGA)  | 11       | 4.51%   |
| 3840x2160 (4K)     | 6        | 2.46%   |
| 1366x768 (WXGA)    | 4        | 1.64%   |
| 3440x1440          | 2        | 0.82%   |
| 1600x1200          | 2        | 0.82%   |
| 2560x1080          | 1        | 0.41%   |
| 1680x1050 (WSXGA+) | 1        | 0.41%   |
| 1440x900 (WXGA+)   | 1        | 0.41%   |
| 1360x768           | 1        | 0.41%   |
| 1280x960           | 1        | 0.41%   |
| 1024x768 (XGA)     | 1        | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 58       | 22.14%  |
| 23     | 58       | 22.14%  |
| 21     | 41       | 15.65%  |
| 27     | 35       | 13.36%  |
| 19     | 20       | 7.63%   |
| 20     | 12       | 4.58%   |
| 17     | 11       | 4.2%    |
| 31     | 7        | 2.67%   |
| 18     | 5        | 1.91%   |
| 34     | 3        | 1.15%   |
| 32     | 3        | 1.15%   |
| 15     | 3        | 1.15%   |
| 25     | 2        | 0.76%   |
| 22     | 2        | 0.76%   |
| 57     | 1        | 0.38%   |
| 46     | 1        | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 137      | 55.92%  |
| 401-500     | 62       | 25.31%  |
| 351-400     | 17       | 6.94%   |
| 301-350     | 14       | 5.71%   |
| 601-700     | 7        | 2.86%   |
| 701-800     | 6        | 2.45%   |
| 1001-1500   | 2        | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 187      | 77.92%  |
| 5/4   | 28       | 11.67%  |
| 16/10 | 19       | 7.92%   |
| 4/3   | 3        | 1.25%   |
| 21/9  | 3        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 121      | 48.02%  |
| 151-200        | 46       | 18.25%  |
| 301-350        | 35       | 13.89%  |
| 251-300        | 17       | 6.75%   |
| 141-150        | 15       | 5.95%   |
| 351-500        | 13       | 5.16%   |
| 101-110        | 3        | 1.19%   |
| More than 1000 | 1        | 0.4%    |
| 501-1000       | 1        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 183      | 75.62%  |
| 101-120 | 55       | 22.73%  |
| 1-50    | 2        | 0.83%   |
| 161-240 | 1        | 0.41%   |
| 121-160 | 1        | 0.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 212      | 72.11%  |
| 0     | 45       | 15.31%  |
| 2     | 37       | 12.59%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 216      | 64.29%  |
| Intel                                  | 83       | 24.7%   |
| TP-Link                                | 4        | 1.19%   |
| Nvidia                                 | 4        | 1.19%   |
| Broadcom                               | 4        | 1.19%   |
| Qualcomm Atheros                       | 3        | 0.89%   |
| Samsung Electronics                    | 2        | 0.6%    |
| Ralink Technology                      | 2        | 0.6%    |
| Ralink                                 | 2        | 0.6%    |
| Mercucys                               | 2        | 0.6%    |
| MediaTek                               | 2        | 0.6%    |
| D-Link                                 | 2        | 0.6%    |
| Xiaomi                                 | 1        | 0.3%    |
| VIA Technologies                       | 1        | 0.3%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.3%    |
| Qualcomm Atheros Communications        | 1        | 0.3%    |
| Qualcomm                               | 1        | 0.3%    |
| Metrologic Instruments                 | 1        | 0.3%    |
| Marvell Technology Group               | 1        | 0.3%    |
| Huawei Technologies                    | 1        | 0.3%    |
| Edimax Technology                      | 1        | 0.3%    |
| ASIX Electronics                       | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 192      | 51.06%  |
| Intel Ethernet Connection (2) I219-V                                   | 13       | 3.46%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11       | 2.93%   |
| Intel Ethernet Connection (14) I219-V                                  | 9        | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8        | 2.13%   |
| Intel Ethernet Controller I225-V                                       | 8        | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7        | 1.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 1.33%   |
| Intel Ethernet Connection (17) I219-V                                  | 5        | 1.33%   |
| Intel Ethernet Connection (17) I219-LM                                 | 5        | 1.33%   |
| Realtek 802.11ac NIC                                                   | 4        | 1.06%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.06%   |
| Intel Wireless 7265                                                    | 4        | 1.06%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 4        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 1.06%   |
| Intel Wireless 3165                                                    | 3        | 0.8%    |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.8%    |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2        | 0.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.53%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 0.53%   |
| Mercucys 802.11n NIC                                                   | 2        | 0.53%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 0.53%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 0.53%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                  | 2        | 0.53%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.27%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.27%   |
| TP-Link USB 10/100 LAN                                                 | 1        | 0.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.27%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 40%     |
| Intel                           | 25       | 35.71%  |
| TP-Link                         | 3        | 4.29%   |
| Broadcom                        | 3        | 4.29%   |
| Ralink Technology               | 2        | 2.86%   |
| Ralink                          | 2        | 2.86%   |
| Mercucys                        | 2        | 2.86%   |
| D-Link                          | 2        | 2.86%   |
| Qualcomm Atheros Communications | 1        | 1.43%   |
| MediaTek                        | 1        | 1.43%   |
| Edimax Technology               | 1        | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 8        | 11.43%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 7        | 10%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5        | 7.14%   |
| Realtek 802.11ac NIC                                            | 4        | 5.71%   |
| Intel Wireless 7265                                             | 4        | 5.71%   |
| Intel Wireless 3165                                             | 3        | 4.29%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 3        | 4.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 2        | 2.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 2        | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 2        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                 | 2        | 2.86%   |
| Mercucys 802.11n NIC                                            | 2        | 2.86%   |
| Intel Wi-Fi 6 AX200                                             | 2        | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 2        | 2.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                     | 1        | 1.43%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 1.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1        | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 1.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 1.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 1.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1        | 1.43%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)       | 1        | 1.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                       | 1        | 1.43%   |
| Ralink RT2561/RT61 802.11g PCI                                  | 1        | 1.43%   |
| Qualcomm Atheros AR9271 802.11n                                 | 1        | 1.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1        | 1.43%   |
| Intel Wireless 7260                                             | 1        | 1.43%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 1        | 1.43%   |
| Intel Raptor Lake-S PCH CNVi WiFi                               | 1        | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 1        | 1.43%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.43%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]   | 1        | 1.43%   |
| D-Link 802.11 n WLAN                                            | 1        | 1.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 1        | 1.43%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter    | 1        | 1.43%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 1        | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 206      | 69.59%  |
| Intel                                  | 72       | 24.32%  |
| Nvidia                                 | 4        | 1.35%   |
| Qualcomm Atheros                       | 3        | 1.01%   |
| Xiaomi                                 | 1        | 0.34%   |
| VIA Technologies                       | 1        | 0.34%   |
| TP-Link                                | 1        | 0.34%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.34%   |
| Samsung Electronics                    | 1        | 0.34%   |
| Qualcomm                               | 1        | 0.34%   |
| MediaTek                               | 1        | 0.34%   |
| Marvell Technology Group               | 1        | 0.34%   |
| Huawei Technologies                    | 1        | 0.34%   |
| Broadcom                               | 1        | 0.34%   |
| ASIX Electronics                       | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 192      | 63.16%  |
| Intel Ethernet Connection (2) I219-V                                   | 13       | 4.28%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11       | 3.62%   |
| Intel Ethernet Connection (14) I219-V                                  | 9        | 2.96%   |
| Intel Ethernet Controller I225-V                                       | 8        | 2.63%   |
| Intel Ethernet Connection (17) I219-V                                  | 5        | 1.64%   |
| Intel Ethernet Connection (17) I219-LM                                 | 5        | 1.64%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.32%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 4        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 1.32%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.99%   |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.66%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 0.66%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.66%   |
| Intel Ethernet Connection (10) I219-V                                  | 2        | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.33%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.33%   |
| TP-Link USB 10/100 LAN                                                 | 1        | 0.33%   |
| Sony Ericsson Mobile AB H8266                                          | 1        | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.33%   |
| Qualcomm Airtel 4G                                                     | 1        | 0.33%   |
| MediaTek Infinix SMART 5                                               | 1        | 0.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1        | 0.33%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.33%   |
| Intel Ethernet Controller I225-LM                                      | 1        | 0.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.33%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.33%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 0.33%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 284      | 80.45%  |
| WiFi     | 67       | 18.98%  |
| Modem    | 2        | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 272      | 93.79%  |
| WiFi     | 18       | 6.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 228      | 79.72%  |
| 2     | 56       | 19.58%  |
| 4     | 1        | 0.35%   |
| 3     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 280      | 97.9%   |
| Yes  | 6        | 2.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 24       | 48%     |
| Realtek Semiconductor   | 14       | 28%     |
| Cambridge Silicon Radio | 3        | 6%      |
| TP-Link                 | 2        | 4%      |
| IMC Networks            | 2        | 4%      |
| Broadcom                | 2        | 4%      |
| MediaTek                | 1        | 2%      |
| ASUSTek Computer        | 1        | 2%      |
| Actions                 | 1        | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 12       | 24%     |
| Intel Bluetooth wireless interface                  | 9        | 18%     |
| Intel Wireless-AC 3168 Bluetooth                    | 7        | 14%     |
| Intel AX211 Bluetooth                               | 3        | 6%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 6%      |
| TP-Link TP-Link Bluetooth USB Adapter               | 2        | 4%      |
| Realtek Bluetooth 5.3 Radio                         | 2        | 4%      |
| Intel AX201 Bluetooth                               | 2        | 4%      |
| IMC Networks Bluetooth Radio                        | 2        | 4%      |
| MediaTek Wireless_Device                            | 1        | 2%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2%      |
| Intel AX210 Bluetooth                               | 1        | 2%      |
| Intel AX200 Bluetooth                               | 1        | 2%      |
| Broadcom HP Portable Bumble Bee                     | 1        | 2%      |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 2%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2%      |
| Actions general adapter                             | 1        | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 236      | 66.86%  |
| AMD                    | 56       | 15.86%  |
| Nvidia                 | 40       | 11.33%  |
| Texas Instruments      | 6        | 1.7%    |
| C-Media Electronics    | 6        | 1.7%    |
| Razer USA              | 2        | 0.57%   |
| Logitech               | 2        | 0.57%   |
| Creative Technology    | 2        | 0.57%   |
| Samson Technologies    | 1        | 0.28%   |
| Lenovo                 | 1        | 0.28%   |
| Generalplus Technology | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Smart Sound Technology (SST) Audio Controller                        | 40       | 9.98%   |
| Intel 200 Series PCH HD Audio                                              | 33       | 8.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 31       | 7.73%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 27       | 6.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 21       | 5.24%   |
| Intel Alder Lake-S HD Audio Controller                                     | 21       | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 4.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15       | 3.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15       | 3.74%   |
| Intel Comet Lake PCH-V cAVS                                                | 14       | 3.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 3.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 2.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 2.24%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.75%   |
| Texas Instruments PCM2902 Audio Codec                                      | 6        | 1.5%    |
| Nvidia High Definition Audio Controller                                    | 6        | 1.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 1.25%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1%      |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.75%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 0.75%   |
| Razer USA Kraken Tournament Edition                                        | 2        | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.5%    |
| Logitech 960 Headset                                                       | 2        | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.5%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 0.5%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 2        | 0.5%    |
| AMD FCH Azalia Controller                                                  | 2        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Crucial                                 | 50       | 16.5%   |
| Kingston                                | 42       | 13.86%  |
| Unknown                                 | 28       | 9.24%   |
| Samsung Electronics                     | 23       | 7.59%   |
| Foxline                                 | 21       | 6.93%   |
| Apacer                                  | 18       | 5.94%   |
| Patriot                                 | 15       | 4.95%   |
| AMD                                     | 14       | 4.62%   |
| SK hynix                                | 13       | 4.29%   |
| A-DATA Technology                       | 12       | 3.96%   |
| Micron Technology                       | 7        | 2.31%   |
| Unknown                                 | 7        | 2.31%   |
| KingSpec                                | 4        | 1.32%   |
| Neo Forza                               | 3        | 0.99%   |
| G.Skill                                 | 3        | 0.99%   |
| Elpida                                  | 3        | 0.99%   |
| Corsair                                 | 3        | 0.99%   |
| Unknown (ABCD)                          | 2        | 0.66%   |
| Unknown (89F7)                          | 2        | 0.66%   |
| Unknown (0x0080)                        | 2        | 0.66%   |
| Silicon Power                           | 2        | 0.66%   |
| Ramaxel Technology                      | 2        | 0.66%   |
| Qumo                                    | 2        | 0.66%   |
| Nanya Technology                        | 2        | 0.66%   |
| KingTiger                               | 2        | 0.66%   |
| HomeNet                                 | 2        | 0.66%   |
| Gold Key                                | 2        | 0.66%   |
| Unknown (8AD6)                          | 1        | 0.33%   |
| Unknown (0x7FFF)                        | 1        | 0.33%   |
| Unknown (0x0BF7)                        | 1        | 0.33%   |
| Unknown (0B7A)                          | 1        | 0.33%   |
| Transcend                               | 1        | 0.33%   |
| Silicon Power Computer & Communications | 1        | 0.33%   |
| Shenzhen Micro Innovation Industry      | 1        | 0.33%   |
| SHARETRONIC                             | 1        | 0.33%   |
| Patriot Memory (PDP Systems)            | 1        | 0.33%   |
| Netac                                   | 1        | 0.33%   |
| Kingmax                                 | 1        | 0.33%   |
| Innodisk                                | 1        | 0.33%   |
| GOODRAM                                 | 1        | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s            | 7        | 2.24%   |
| Unknown                                                      | 7        | 2.24%   |
| Patriot RAM PSD44G266681 4GB DIMM DDR4 2667MT/s              | 5        | 1.6%    |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s          | 5        | 1.6%    |
| Crucial RAM CT8G4DFS8266.M8FD 8192MB DIMM DDR4 3600MT/s      | 5        | 1.6%    |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                  | 5        | 1.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 4        | 1.28%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 4        | 1.28%   |
| Apacer RAM D12.2755BS.001 16GB DIMM DDR4 3200MT/s            | 4        | 1.28%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 3        | 0.96%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s          | 3        | 0.96%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s              | 3        | 0.96%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s        | 3        | 0.96%   |
| KingSpec RAM KS2666D4P12008G 8GB DIMM DDR4 2667MT/s          | 3        | 0.96%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s       | 3        | 0.96%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 2        | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2        | 0.64%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                    | 2        | 0.64%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2        | 0.64%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 2        | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 2        | 0.64%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3                  | 2        | 0.64%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                     | 2        | 0.64%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s       | 2        | 0.64%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s              | 2        | 0.64%   |
| Nanya RAM M2F4GH64CB8HB 4GB DIMM DDR3 1600MT/s               | 2        | 0.64%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s           | 2        | 0.64%   |
| KingTiger RAM Module 2GB DIMM DDR3 1333MT/s                  | 2        | 0.64%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 0.64%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s             | 2        | 0.64%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s        | 2        | 0.64%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2        | 0.64%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s        | 2        | 0.64%   |
| HomeNet RAM HN SO 8GB 8192MB SODIMM DDR4 3200MT/s            | 2        | 0.64%   |
| Gold Key RAM GKE800UD102408-2666A 8GB DIMM DDR4 2667MT/s     | 2        | 0.64%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s          | 2        | 0.64%   |
| Foxline RAM FL3200D4U22-16G 16GB DIMM DDR4 3200MT/s          | 2        | 0.64%   |
| Foxline RAM FL2666D4U19-16G 16GB DIMM DDR4 2667MT/s          | 2        | 0.64%   |
| Foxline RAM FL2666D4S19S-16G 16GB SODIMM DDR4 2667MT/s       | 2        | 0.64%   |
| Crucial RAM ST51264BA1339.16FK 4GB DIMM DDR3 1333MT/s        | 2        | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 189      | 67.5%   |
| DDR3    | 58       | 20.71%  |
| SDRAM   | 10       | 3.57%   |
| Unknown | 8        | 2.86%   |
| DDR2    | 7        | 2.5%    |
| DDR5    | 4        | 1.43%   |
| LPDDR4  | 3        | 1.07%   |
| DDR     | 1        | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 238      | 85.92%  |
| SODIMM | 39       | 14.08%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 145      | 49.15%  |
| 4096  | 73       | 24.75%  |
| 16384 | 36       | 12.2%   |
| 2048  | 25       | 8.47%   |
| 1024  | 8        | 2.71%   |
| 32768 | 7        | 2.37%   |
| 512   | 1        | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 76       | 26.03%  |
| 3200    | 50       | 17.12%  |
| 1333    | 30       | 10.27%  |
| 1600    | 28       | 9.59%   |
| 2400    | 22       | 7.53%   |
| 2133    | 10       | 3.42%   |
| 3600    | 8        | 2.74%   |
| 2666    | 7        | 2.4%    |
| 2933    | 5        | 1.71%   |
| 800     | 5        | 1.71%   |
| 2800    | 4        | 1.37%   |
| 2934    | 3        | 1.03%   |
| 1800    | 3        | 1.03%   |
| 1066    | 3        | 1.03%   |
| 533     | 3        | 1.03%   |
| Unknown | 3        | 1.03%   |
| 5200    | 2        | 0.68%   |
| 4800    | 2        | 0.68%   |
| 4000    | 2        | 0.68%   |
| 3533    | 2        | 0.68%   |
| 2866    | 2        | 0.68%   |
| 2733    | 2        | 0.68%   |
| 1866    | 2        | 0.68%   |
| 667     | 2        | 0.68%   |
| 333     | 2        | 0.68%   |
| 3800    | 1        | 0.34%   |
| 3733    | 1        | 0.34%   |
| 3466    | 1        | 0.34%   |
| 3334    | 1        | 0.34%   |
| 3266    | 1        | 0.34%   |
| 3066    | 1        | 0.34%   |
| 3000    | 1        | 0.34%   |
| 2734    | 1        | 0.34%   |
| 2187    | 1        | 0.34%   |
| 2134    | 1        | 0.34%   |
| 2000    | 1        | 0.34%   |
| 1867    | 1        | 0.34%   |
| 1648    | 1        | 0.34%   |
| 400     | 1        | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 41.18%  |
| Canon               | 4        | 23.53%  |
| Pantum              | 3        | 17.65%  |
| Samsung Electronics | 1        | 5.88%   |
| Kyocera             | 1        | 5.88%   |
| CACTUS              | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-4300 Series       | 1        | 5.88%   |
| Pantum P3010DW series         | 1        | 5.88%   |
| Pantum BM5100FDW series       | 1        | 5.88%   |
| Pantum BM5100ADN series       | 1        | 5.88%   |
| Kyocera FS-1040               | 1        | 5.88%   |
| HP LaserJet P2055 series      | 1        | 5.88%   |
| HP LaserJet M203-M206         | 1        | 5.88%   |
| HP LaserJet M109-M112         | 1        | 5.88%   |
| HP LaserJet 1010              | 1        | 5.88%   |
| HP HP LaserJet Pro M428-M429  | 1        | 5.88%   |
| HP HP LaserJet P2035          | 1        | 5.88%   |
| HP Designjet T1200 PostScript | 1        | 5.88%   |
| Canon MF450 Series            | 1        | 5.88%   |
| Canon MF440 Series            | 1        | 5.88%   |
| Canon MF410 Series            | 1        | 5.88%   |
| Canon LBP6030/6030B/6018L     | 1        | 5.88%   |
| CACTUS CS-LP1120              | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet Pro 2000 s2  | 1        | 33.33%  |
| Canon CanoScan LIDE 25  | 1        | 33.33%  |
| Canon CanoScan LiDE 110 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| SunplusIT                     | 14       | 21.88%  |
| Realtek Semiconductor         | 9        | 14.06%  |
| Microdia                      | 8        | 12.5%   |
| Logitech                      | 7        | 10.94%  |
| Sunplus Innovation Technology | 5        | 7.81%   |
| Alcor Micro                   | 5        | 7.81%   |
| Chicony Electronics           | 3        | 4.69%   |
| lihappe8                      | 2        | 3.13%   |
| KYE Systems (Mouse Systems)   | 2        | 3.13%   |
| Creative Technology           | 2        | 3.13%   |
| WaveRider Communications      | 1        | 1.56%   |
| QuickShot                     | 1        | 1.56%   |
| Novatek Microelectronics      | 1        | 1.56%   |
| Hopewin Electronic Material   | 1        | 1.56%   |
| Arkmicro Technologies         | 1        | 1.56%   |
| Apple                         | 1        | 1.56%   |
| AlcorMicroCorp                | 1        | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| SunplusIT USB Camera                          | 14       | 21.88%  |
| Microdia Camera                               | 8        | 12.5%   |
| Sunplus USB Microphone                        | 4        | 6.25%   |
| Realtek 1080p Camera                          | 4        | 6.25%   |
| Alcor Micro USB 2.0 PC Camera                 | 4        | 6.25%   |
| Realtek USB Camera                            | 3        | 4.69%   |
| Logitech HD Webcam C615                       | 3        | 4.69%   |
| Logitech Webcam C270                          | 2        | 3.13%   |
| lihappe8 USB 2.0 Camera                       | 2        | 3.13%   |
| Chicony HP High Definition 1MP Webcam         | 2        | 3.13%   |
| WaveRider USB Camera                          | 1        | 1.56%   |
| Sunplus Integrated_Webcam_5M                  | 1        | 1.56%   |
| Realtek NexiGo N660P FHD Webcam               | 1        | 1.56%   |
| Realtek HP 2.0MP High Definition Webcam       | 1        | 1.56%   |
| QuickShot USB 2.0 PC Camera                   | 1        | 1.56%   |
| Novatek HP High Definition 2MP Webcam         | 1        | 1.56%   |
| Logitech Webcam C310                          | 1        | 1.56%   |
| Logitech B525 HD Webcam                       | 1        | 1.56%   |
| KYE Systems (Mouse Systems) Genius Webcam     | 1        | 1.56%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 1.56%   |
| Hopewin Electronic Material Integrated Camera | 1        | 1.56%   |
| Creative VF0530 Live! Cam Chat IM             | 1        | 1.56%   |
| Creative Live! Cam inPerson HD VF0720         | 1        | 1.56%   |
| Chicony HP 0.3MP Webcam                       | 1        | 1.56%   |
| Arkmicro USB2.0 PC CAMERA                     | 1        | 1.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 1        | 1.56%   |
| AlcorMicroCorp SHUNCCM                        | 1        | 1.56%   |
| Alcor Micro USB FHD Camera                    | 1        | 1.56%   |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Aktiv                     | 7        | 70%     |
| Aladdin R.D.              | 2        | 20%     |
| Aladdin Knowledge Systems | 1        | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Aktiv Rutoken lite                    | 7        | 70%     |
| Aladdin R.D. Smart card reader JCR721 | 1        | 10%     |
| Aladdin R.D. JaCarta                  | 1        | 10%     |
| Aladdin Knowledge Systems Token JC    | 1        | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 234      | 81.25%  |
| 1     | 50       | 17.36%  |
| 2     | 2        | 0.69%   |
| 4     | 1        | 0.35%   |
| 3     | 1        | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 39       | 63.93%  |
| Net/wireless             | 9        | 14.75%  |
| Communication controller | 4        | 6.56%   |
| Chipcard                 | 4        | 6.56%   |
| Unassigned class         | 2        | 3.28%   |
| Sound                    | 1        | 1.64%   |
| Net/ethernet             | 1        | 1.64%   |
| Multimedia controller    | 1        | 1.64%   |


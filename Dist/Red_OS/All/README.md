Red OS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Red OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Red_OS/Desktop/README.md) and [notebooks](/Dist/Red_OS/Notebook/README.md).

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

Total: 644

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Notebook    | [3c4e207a92](https://linux-hardware.org/?probe=3c4e207a92) | May 09, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [a415f46a9e](https://linux-hardware.org/?probe=a415f46a9e) | May 07, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [e4adc14010](https://linux-hardware.org/?probe=e4adc14010) | May 06, 2024 |
| Dell          | Precision M4700             | Notebook    | [fa5aa96761](https://linux-hardware.org/?probe=fa5aa96761) | Apr 23, 2024 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [03f369c46b](https://linux-hardware.org/?probe=03f369c46b) | Apr 15, 2024 |
| Acer          | Aspire C24-963              | All in one  | [45437c3235](https://linux-hardware.org/?probe=45437c3235) | Apr 11, 2024 |
| ASRock        | H610M-HVS                   | Desktop     | [bb1b76d77f](https://linux-hardware.org/?probe=bb1b76d77f) | Apr 10, 2024 |
| MACHENIKE     | L17A                        | Notebook    | [5bd336609a](https://linux-hardware.org/?probe=5bd336609a) | Apr 10, 2024 |
| ASUSTek       | H110-PLUS                   | Desktop     | [f9d667563c](https://linux-hardware.org/?probe=f9d667563c) | Apr 10, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [606efbdac3](https://linux-hardware.org/?probe=606efbdac3) | Apr 10, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [af364f4b61](https://linux-hardware.org/?probe=af364f4b61) | Apr 09, 2024 |
| Dell          | Precision M4700             | Notebook    | [14e5ad11ff](https://linux-hardware.org/?probe=14e5ad11ff) | Apr 08, 2024 |
| Unknown       | X133                        | Notebook    | [c85c7ccafc](https://linux-hardware.org/?probe=c85c7ccafc) | Apr 05, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [2c9d3860d1](https://linux-hardware.org/?probe=2c9d3860d1) | Apr 05, 2024 |
| ASRock        | H610M-HVS                   | Desktop     | [0fe84d2ae2](https://linux-hardware.org/?probe=0fe84d2ae2) | Apr 05, 2024 |
| HP            | 85A2                        | All in one  | [4c618f5dde](https://linux-hardware.org/?probe=4c618f5dde) | Apr 02, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [1948e2f590](https://linux-hardware.org/?probe=1948e2f590) | Mar 28, 2024 |
| MSI           | MAG B760M MORTAR            | Desktop     | [a7d3ac796f](https://linux-hardware.org/?probe=a7d3ac796f) | Mar 24, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [bb5ad21304](https://linux-hardware.org/?probe=bb5ad21304) | Mar 24, 2024 |
| Gigabyte      | H510M S2H V2                | Desktop     | [cbfecba3df](https://linux-hardware.org/?probe=cbfecba3df) | Mar 20, 2024 |
| HP            | 85A2                        | All in one  | [c43047c854](https://linux-hardware.org/?probe=c43047c854) | Mar 20, 2024 |
| Gigabyte      | H510M S2H V2                | Desktop     | [f9d491fb3a](https://linux-hardware.org/?probe=f9d491fb3a) | Mar 20, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6c0a847cf4](https://linux-hardware.org/?probe=6c0a847cf4) | Mar 20, 2024 |
| Gigabyte      | H310M H                     | Desktop     | [041eca17dc](https://linux-hardware.org/?probe=041eca17dc) | Mar 20, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [21877754a0](https://linux-hardware.org/?probe=21877754a0) | Mar 20, 2024 |
| HP            | 198E                        | Desktop     | [dfdd44b32d](https://linux-hardware.org/?probe=dfdd44b32d) | Mar 20, 2024 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [286fb4ec0a](https://linux-hardware.org/?probe=286fb4ec0a) | Mar 20, 2024 |
| Unknown       | T360D11                     | Desktop     | [8dc0de16f8](https://linux-hardware.org/?probe=8dc0de16f8) | Mar 20, 2024 |
| HP            | 2B43                        | Desktop     | [365885e742](https://linux-hardware.org/?probe=365885e742) | Mar 20, 2024 |
| Dell          | Precision M4700             | Notebook    | [667558cba6](https://linux-hardware.org/?probe=667558cba6) | Mar 20, 2024 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [ec2b946862](https://linux-hardware.org/?probe=ec2b946862) | Mar 20, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [4a7f8b6b79](https://linux-hardware.org/?probe=4a7f8b6b79) | Mar 15, 2024 |
| Fujitsu Si... | LIFEBOOK T5010              | Notebook    | [99e6ef98f0](https://linux-hardware.org/?probe=99e6ef98f0) | Mar 14, 2024 |
| ASRock        | H610M-HVS                   | Desktop     | [3189e4304b](https://linux-hardware.org/?probe=3189e4304b) | Mar 13, 2024 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [3b98bf5ca7](https://linux-hardware.org/?probe=3b98bf5ca7) | Mar 11, 2024 |
| INTECH PRO    | H510-M2 v5.0                | Desktop     | [6afefbab74](https://linux-hardware.org/?probe=6afefbab74) | Mar 11, 2024 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [7d2950146c](https://linux-hardware.org/?probe=7d2950146c) | Mar 09, 2024 |
| MSI           | H61I-E35                    | Desktop     | [dbc777c090](https://linux-hardware.org/?probe=dbc777c090) | Mar 07, 2024 |
| Acer          | Extensa 215-33              | Notebook    | [efe3c07386](https://linux-hardware.org/?probe=efe3c07386) | Mar 04, 2024 |
| Acer          | Extensa 215-33              | Notebook    | [0b2c9b5116](https://linux-hardware.org/?probe=0b2c9b5116) | Mar 04, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [f0aab0e0f6](https://linux-hardware.org/?probe=f0aab0e0f6) | Mar 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [de96f427a2](https://linux-hardware.org/?probe=de96f427a2) | Mar 02, 2024 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [abf2cc9c16](https://linux-hardware.org/?probe=abf2cc9c16) | Mar 01, 2024 |
| Dell          | Precision M4700             | Notebook    | [8e50df0d77](https://linux-hardware.org/?probe=8e50df0d77) | Mar 01, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [e05c7c262b](https://linux-hardware.org/?probe=e05c7c262b) | Mar 01, 2024 |
| ASUSTek       | ROG Zephyrus S17 GX701LX... | Notebook    | [15a8eddc01](https://linux-hardware.org/?probe=15a8eddc01) | Feb 29, 2024 |
| MSI           | H61I-E35                    | Desktop     | [d9c1e6f02c](https://linux-hardware.org/?probe=d9c1e6f02c) | Feb 29, 2024 |
| MSI           | H61I-E35                    | Desktop     | [7c13263839](https://linux-hardware.org/?probe=7c13263839) | Feb 29, 2024 |
| MSI           | H61I-E35                    | Desktop     | [b389d340cc](https://linux-hardware.org/?probe=b389d340cc) | Feb 29, 2024 |
| MSI           | H61I-E35                    | Desktop     | [42d07a20da](https://linux-hardware.org/?probe=42d07a20da) | Feb 29, 2024 |
| MSI           | H61I-E35                    | Desktop     | [be3349f314](https://linux-hardware.org/?probe=be3349f314) | Feb 29, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [e76d792669](https://linux-hardware.org/?probe=e76d792669) | Feb 29, 2024 |
| Gigabyte      | H510M H                     | Desktop     | [e3f138dca5](https://linux-hardware.org/?probe=e3f138dca5) | Feb 28, 2024 |
| Gigabyte      | H510M H                     | Desktop     | [3f8d7911a8](https://linux-hardware.org/?probe=3f8d7911a8) | Feb 28, 2024 |
| Graviton      | DMB-Q670-TMI01              | All in one  | [401238ae67](https://linux-hardware.org/?probe=401238ae67) | Feb 27, 2024 |
| Graviton      | DMB-Q670-TMI01              | All in one  | [bfb39519ce](https://linux-hardware.org/?probe=bfb39519ce) | Feb 27, 2024 |
| Unknown       | T610D11-ALD                 | Desktop     | [5015ded00e](https://linux-hardware.org/?probe=5015ded00e) | Feb 22, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [b6a4906cf3](https://linux-hardware.org/?probe=b6a4906cf3) | Feb 20, 2024 |
| Unknown       | TA320 Series                | Desktop     | [df96f8b57d](https://linux-hardware.org/?probe=df96f8b57d) | Feb 16, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [96c7b5b101](https://linux-hardware.org/?probe=96c7b5b101) | Feb 15, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [5299dd1826](https://linux-hardware.org/?probe=5299dd1826) | Feb 13, 2024 |
| Dell          | Precision M4700             | Notebook    | [02cfb33222](https://linux-hardware.org/?probe=02cfb33222) | Feb 13, 2024 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [f1d916474f](https://linux-hardware.org/?probe=f1d916474f) | Feb 12, 2024 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [43a65f4060](https://linux-hardware.org/?probe=43a65f4060) | Feb 12, 2024 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [6b8f0a0684](https://linux-hardware.org/?probe=6b8f0a0684) | Feb 09, 2024 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [672b95fe29](https://linux-hardware.org/?probe=672b95fe29) | Feb 08, 2024 |
| Gigabyte      | B365M H                     | Desktop     | [ac7a22a8f4](https://linux-hardware.org/?probe=ac7a22a8f4) | Jan 30, 2024 |
| Unknown       | T360D11                     | Desktop     | [4f06f14ee6](https://linux-hardware.org/?probe=4f06f14ee6) | Jan 30, 2024 |
| HP            | 8431                        | All in one  | [a0646a07e1](https://linux-hardware.org/?probe=a0646a07e1) | Jan 30, 2024 |
| Gigabyte      | B360HD3                     | Desktop     | [7a7e6d1518](https://linux-hardware.org/?probe=7a7e6d1518) | Jan 30, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [5628f77cd1](https://linux-hardware.org/?probe=5628f77cd1) | Jan 30, 2024 |
| HP            | 8431                        | All in one  | [e07be0c225](https://linux-hardware.org/?probe=e07be0c225) | Jan 29, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [db2cd07d84](https://linux-hardware.org/?probe=db2cd07d84) | Jan 26, 2024 |
| ASUSTek       | X99-E WS                    | Desktop     | [92cb95eaef](https://linux-hardware.org/?probe=92cb95eaef) | Jan 25, 2024 |
| ASRock        | B365M-ITX/ac                | Desktop     | [1a48a2a936](https://linux-hardware.org/?probe=1a48a2a936) | Jan 24, 2024 |
| ASRock        | B365M-ITX/ac                | Desktop     | [e7719cba1d](https://linux-hardware.org/?probe=e7719cba1d) | Jan 24, 2024 |
| ASRock        | B365M-ITX/ac                | Desktop     | [b2abf616b0](https://linux-hardware.org/?probe=b2abf616b0) | Jan 24, 2024 |
| HP            | 3399                        | Desktop     | [5126e6fb32](https://linux-hardware.org/?probe=5126e6fb32) | Jan 23, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [4983fd3ab4](https://linux-hardware.org/?probe=4983fd3ab4) | Jan 22, 2024 |
| ASRock        | B365M-ITX/ac                | Desktop     | [45d94979a5](https://linux-hardware.org/?probe=45d94979a5) | Jan 19, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [66e82c879d](https://linux-hardware.org/?probe=66e82c879d) | Jan 19, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [af8a99bcf3](https://linux-hardware.org/?probe=af8a99bcf3) | Jan 19, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ca9e77a64e](https://linux-hardware.org/?probe=ca9e77a64e) | Jan 19, 2024 |
| Supermicro    | X10DRiB                     | Server      | [6d35cc0c34](https://linux-hardware.org/?probe=6d35cc0c34) | Jan 16, 2024 |
| Intel         | S2600WFT H48104-854         | Server      | [781f43495a](https://linux-hardware.org/?probe=781f43495a) | Jan 16, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [abc7a5352b](https://linux-hardware.org/?probe=abc7a5352b) | Jan 14, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [166d3493a4](https://linux-hardware.org/?probe=166d3493a4) | Jan 14, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [f13e1664ba](https://linux-hardware.org/?probe=f13e1664ba) | Jan 12, 2024 |
| BESHTAU       | B560RU V51                  | Desktop     | [dec20966d4](https://linux-hardware.org/?probe=dec20966d4) | Jan 11, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [04855eeea8](https://linux-hardware.org/?probe=04855eeea8) | Jan 09, 2024 |
| Acer          | Extensa 215-22              | Notebook    | [c2884d7a5d](https://linux-hardware.org/?probe=c2884d7a5d) | Jan 09, 2024 |
| Unknown       | Unknown                     | All in one  | [e96082202f](https://linux-hardware.org/?probe=e96082202f) | Jan 09, 2024 |
| Lenovo        | ThinkPad T61 6464WM6        | Notebook    | [a0b959c7c4](https://linux-hardware.org/?probe=a0b959c7c4) | Jan 05, 2024 |
| Lenovo        | ThinkPad T61 6464WM6        | Notebook    | [3cf7d0764e](https://linux-hardware.org/?probe=3cf7d0764e) | Jan 05, 2024 |
| Lenovo        | ThinkPad T430 23493V2       | Notebook    | [8cbff5c75a](https://linux-hardware.org/?probe=8cbff5c75a) | Jan 02, 2024 |
| KVADRA        | NAU LE15T                   | Notebook    | [b53fe7cc28](https://linux-hardware.org/?probe=b53fe7cc28) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [c71368b0eb](https://linux-hardware.org/?probe=c71368b0eb) | Jan 01, 2024 |
| iRU           | 15ALC                       | Notebook    | [28f7177799](https://linux-hardware.org/?probe=28f7177799) | Dec 22, 2023 |
| Dell          | Precision M4700             | Notebook    | [3048d06ee6](https://linux-hardware.org/?probe=3048d06ee6) | Dec 21, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [090fcf5a52](https://linux-hardware.org/?probe=090fcf5a52) | Dec 21, 2023 |
| Lenovo        | ThinkCentre A70 7099L8G     | Desktop     | [9720608634](https://linux-hardware.org/?probe=9720608634) | Dec 20, 2023 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [90d82dc1a1](https://linux-hardware.org/?probe=90d82dc1a1) | Dec 18, 2023 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [d52ec68e39](https://linux-hardware.org/?probe=d52ec68e39) | Dec 18, 2023 |
| Biostar       | H610MH                      | Desktop     | [6a0d454360](https://linux-hardware.org/?probe=6a0d454360) | Dec 18, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [c4aead03a2](https://linux-hardware.org/?probe=c4aead03a2) | Dec 13, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [0542ba556a](https://linux-hardware.org/?probe=0542ba556a) | Dec 10, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [02763925e5](https://linux-hardware.org/?probe=02763925e5) | Dec 08, 2023 |
| Acer          | Aspire C24-963              | All in one  | [60ba059a0f](https://linux-hardware.org/?probe=60ba059a0f) | Dec 07, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [d9e7bff910](https://linux-hardware.org/?probe=d9e7bff910) | Dec 07, 2023 |
| ASRock        | B365M-ITX/ac                | Desktop     | [01d47685dd](https://linux-hardware.org/?probe=01d47685dd) | Dec 06, 2023 |
| Acer          | Aspire C24-963              | All in one  | [9c0233708f](https://linux-hardware.org/?probe=9c0233708f) | Dec 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3b62534051](https://linux-hardware.org/?probe=3b62534051) | Nov 29, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | Notebook    | [bf518076d5](https://linux-hardware.org/?probe=bf518076d5) | Nov 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ae4263fce1](https://linux-hardware.org/?probe=ae4263fce1) | Nov 28, 2023 |
| Dell          | Vostro 3590                 | Notebook    | [8ca5eb4e42](https://linux-hardware.org/?probe=8ca5eb4e42) | Nov 27, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [07a85d20b8](https://linux-hardware.org/?probe=07a85d20b8) | Nov 27, 2023 |
| ASUSTek       | E5402WHA                    | All in one  | [f10bbeba90](https://linux-hardware.org/?probe=f10bbeba90) | Nov 23, 2023 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [f5ae04b987](https://linux-hardware.org/?probe=f5ae04b987) | Nov 22, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1TQ0... | Notebook    | [5586688561](https://linux-hardware.org/?probe=5586688561) | Nov 21, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [44cca29f66](https://linux-hardware.org/?probe=44cca29f66) | Nov 21, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [7d7599e0d0](https://linux-hardware.org/?probe=7d7599e0d0) | Nov 21, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [95caa4b8a1](https://linux-hardware.org/?probe=95caa4b8a1) | Nov 21, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [0324427380](https://linux-hardware.org/?probe=0324427380) | Nov 21, 2023 |
| Lenovo        | 3738 No DPK                 | All in one  | [963309ed48](https://linux-hardware.org/?probe=963309ed48) | Nov 21, 2023 |
| Lenovo        | 3738 No DPK                 | All in one  | [894963056c](https://linux-hardware.org/?probe=894963056c) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [e029a02461](https://linux-hardware.org/?probe=e029a02461) | Nov 21, 2023 |
| Lenovo        | 3738 No DPK                 | All in one  | [ac1b4a389c](https://linux-hardware.org/?probe=ac1b4a389c) | Nov 21, 2023 |
| Acer          | Aspire Z3620                | All in one  | [96fedbc73a](https://linux-hardware.org/?probe=96fedbc73a) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [966108e5dc](https://linux-hardware.org/?probe=966108e5dc) | Nov 21, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [b95aa31de0](https://linux-hardware.org/?probe=b95aa31de0) | Nov 21, 2023 |
| HP            | ProLiant DL180 Gen9         | Server      | [941492dd99](https://linux-hardware.org/?probe=941492dd99) | Nov 20, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5b55e90cd2](https://linux-hardware.org/?probe=5b55e90cd2) | Nov 20, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [ef419190cb](https://linux-hardware.org/?probe=ef419190cb) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [c492bd0c05](https://linux-hardware.org/?probe=c492bd0c05) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [05b1279d72](https://linux-hardware.org/?probe=05b1279d72) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d203bd1f2e](https://linux-hardware.org/?probe=d203bd1f2e) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [3fb45b3fae](https://linux-hardware.org/?probe=3fb45b3fae) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [1e85870bb4](https://linux-hardware.org/?probe=1e85870bb4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d97ba119eb](https://linux-hardware.org/?probe=d97ba119eb) | Nov 20, 2023 |
| Unknown       | TA320 Series                | Desktop     | [2ba015f4da](https://linux-hardware.org/?probe=2ba015f4da) | Nov 20, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [076964fb48](https://linux-hardware.org/?probe=076964fb48) | Nov 20, 2023 |
| ASRock        | B365M-ITX/ac                | Desktop     | [d9aef8d62e](https://linux-hardware.org/?probe=d9aef8d62e) | Nov 20, 2023 |
| ONDA          | H410D4 IPC                  | Desktop     | [5ace66c92d](https://linux-hardware.org/?probe=5ace66c92d) | Nov 20, 2023 |
| BESHTAU       | B560RU V51                  | Desktop     | [188829d0c2](https://linux-hardware.org/?probe=188829d0c2) | Nov 20, 2023 |
| HP            | 87F3 0100                   | All in one  | [240a088585](https://linux-hardware.org/?probe=240a088585) | Nov 18, 2023 |
| ICL           | H410SB-TM2                  | Desktop     | [d63641c6e3](https://linux-hardware.org/?probe=d63641c6e3) | Nov 17, 2023 |
| SYS           | DMB-H310-TMI01              | All in one  | [473c0522d9](https://linux-hardware.org/?probe=473c0522d9) | Nov 17, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [2ca3738c72](https://linux-hardware.org/?probe=2ca3738c72) | Nov 17, 2023 |
| Acer          | Aspire C24-420              | All in one  | [b4c4e14837](https://linux-hardware.org/?probe=b4c4e14837) | Nov 17, 2023 |
| ASRock        | H81M-DG4                    | Desktop     | [089b0f3839](https://linux-hardware.org/?probe=089b0f3839) | Nov 17, 2023 |
| Acer          | Aspire C24-320              | All in one  | [645dabc9b8](https://linux-hardware.org/?probe=645dabc9b8) | Nov 17, 2023 |
| ASUSTek       | V241FA                      | All in one  | [370bf37b1c](https://linux-hardware.org/?probe=370bf37b1c) | Nov 17, 2023 |
| Intel         | 600 Series Chipset          | All in one  | [0ddf62e15e](https://linux-hardware.org/?probe=0ddf62e15e) | Nov 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [9dbd54affc](https://linux-hardware.org/?probe=9dbd54affc) | Nov 14, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [e86d8effd9](https://linux-hardware.org/?probe=e86d8effd9) | Nov 11, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [cc09f89cd0](https://linux-hardware.org/?probe=cc09f89cd0) | Nov 09, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [17ec369170](https://linux-hardware.org/?probe=17ec369170) | Nov 09, 2023 |
| iRU           | LPGR.469559.010             | All in one  | [65ecfd904d](https://linux-hardware.org/?probe=65ecfd904d) | Nov 08, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [290c167538](https://linux-hardware.org/?probe=290c167538) | Nov 08, 2023 |
| Dell          | Precision M4700             | Notebook    | [ab52e67d9d](https://linux-hardware.org/?probe=ab52e67d9d) | Nov 01, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [c6d1fc4965](https://linux-hardware.org/?probe=c6d1fc4965) | Oct 31, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d89e17690d](https://linux-hardware.org/?probe=d89e17690d) | Oct 31, 2023 |
| HP            | 84EE 1100                   | All in one  | [85b02dcac3](https://linux-hardware.org/?probe=85b02dcac3) | Oct 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [893389d935](https://linux-hardware.org/?probe=893389d935) | Oct 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d8a8dfefd7](https://linux-hardware.org/?probe=d8a8dfefd7) | Oct 24, 2023 |
| Dell          | Precision M4700             | Notebook    | [4d590a378f](https://linux-hardware.org/?probe=4d590a378f) | Oct 24, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [41dfd82cb6](https://linux-hardware.org/?probe=41dfd82cb6) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [9bf87234d6](https://linux-hardware.org/?probe=9bf87234d6) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [d1f56e838d](https://linux-hardware.org/?probe=d1f56e838d) | Oct 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [71c2062cbf](https://linux-hardware.org/?probe=71c2062cbf) | Oct 22, 2023 |
| Graviton      | DMB-H310-TMI01              | All in one  | [2c1e5f43d9](https://linux-hardware.org/?probe=2c1e5f43d9) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [6290cec60c](https://linux-hardware.org/?probe=6290cec60c) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [287fa14302](https://linux-hardware.org/?probe=287fa14302) | Oct 20, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [0fd9732532](https://linux-hardware.org/?probe=0fd9732532) | Oct 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [9947f3f38b](https://linux-hardware.org/?probe=9947f3f38b) | Oct 17, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [83c36787ea](https://linux-hardware.org/?probe=83c36787ea) | Oct 17, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6457a793cd](https://linux-hardware.org/?probe=6457a793cd) | Oct 14, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [23b760e539](https://linux-hardware.org/?probe=23b760e539) | Oct 12, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [c3a319200c](https://linux-hardware.org/?probe=c3a319200c) | Oct 12, 2023 |
| Graviton      | Unknown                     | Notebook    | [69c721a100](https://linux-hardware.org/?probe=69c721a100) | Oct 10, 2023 |
| Lenovo        | 3752 NOK                    | Desktop     | [e3eda8aae7](https://linux-hardware.org/?probe=e3eda8aae7) | Oct 10, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [4440996d7b](https://linux-hardware.org/?probe=4440996d7b) | Oct 07, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7774477854](https://linux-hardware.org/?probe=7774477854) | Oct 07, 2023 |
| Lenovo        | 3752 NOK                    | Desktop     | [5e3d37b336](https://linux-hardware.org/?probe=5e3d37b336) | Oct 05, 2023 |
| HUAWEI        | BDZ-WXX9                    | Notebook    | [a33a848e40](https://linux-hardware.org/?probe=a33a848e40) | Sep 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [b85adec006](https://linux-hardware.org/?probe=b85adec006) | Sep 25, 2023 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [f3e31ed154](https://linux-hardware.org/?probe=f3e31ed154) | Sep 22, 2023 |
| Intel         | NUC10i5FNB M38063-308       | Mini pc     | [bb9b5c4509](https://linux-hardware.org/?probe=bb9b5c4509) | Sep 21, 2023 |
| Unknown       | DMB-A520-MCA01              | Desktop     | [a959513e7c](https://linux-hardware.org/?probe=a959513e7c) | Sep 18, 2023 |
| iRU           | 15ALC                       | Notebook    | [c5839fb7da](https://linux-hardware.org/?probe=c5839fb7da) | Sep 17, 2023 |
| iRU           | 15ALC                       | Notebook    | [87679b8dc1](https://linux-hardware.org/?probe=87679b8dc1) | Sep 17, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [5eadb71ae4](https://linux-hardware.org/?probe=5eadb71ae4) | Sep 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [baf81a81a2](https://linux-hardware.org/?probe=baf81a81a2) | Sep 13, 2023 |
| HP            | ProBook 6570b               | Notebook    | [90aaacf4af](https://linux-hardware.org/?probe=90aaacf4af) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [006062545f](https://linux-hardware.org/?probe=006062545f) | Sep 13, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [018a3b8abe](https://linux-hardware.org/?probe=018a3b8abe) | Sep 08, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [c93409061c](https://linux-hardware.org/?probe=c93409061c) | Sep 06, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2135954523](https://linux-hardware.org/?probe=2135954523) | Sep 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [7c560dfe57](https://linux-hardware.org/?probe=7c560dfe57) | Aug 31, 2023 |
| ICL           | S1511 G1R                   | Notebook    | [421df1df8d](https://linux-hardware.org/?probe=421df1df8d) | Aug 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a3a1e805b2](https://linux-hardware.org/?probe=a3a1e805b2) | Aug 27, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [88076446b3](https://linux-hardware.org/?probe=88076446b3) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [201a0612e4](https://linux-hardware.org/?probe=201a0612e4) | Aug 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cfe21994b6](https://linux-hardware.org/?probe=cfe21994b6) | Aug 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| Dell          | Precision M4700             | Notebook    | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ee71316b5e](https://linux-hardware.org/?probe=ee71316b5e) | Jul 17, 2023 |
| Gigabyte      | G5 ME                       | Notebook    | [eaefa9c2c6](https://linux-hardware.org/?probe=eaefa9c2c6) | Jul 17, 2023 |
| RDW           | MB-B450M V.1                | All in one  | [cc732c4e21](https://linux-hardware.org/?probe=cc732c4e21) | Jul 12, 2023 |
| Dell          | Precision M4700             | Notebook    | [7dc84c10b5](https://linux-hardware.org/?probe=7dc84c10b5) | Jul 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [3f5ae451c0](https://linux-hardware.org/?probe=3f5ae451c0) | Jul 09, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [30e96afcdd](https://linux-hardware.org/?probe=30e96afcdd) | Jul 08, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [cd2b7e13ce](https://linux-hardware.org/?probe=cd2b7e13ce) | Jul 04, 2023 |
| ICL           | Si1407                      | Notebook    | [c4c9d43042](https://linux-hardware.org/?probe=c4c9d43042) | Jul 04, 2023 |
| Biostar       | H610MH                      | Desktop     | [ba1951d1fa](https://linux-hardware.org/?probe=ba1951d1fa) | Jun 19, 2023 |
| Aquarius      | NS483                       | Notebook    | [dd5daf7f12](https://linux-hardware.org/?probe=dd5daf7f12) | Jun 18, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a161ef52b4](https://linux-hardware.org/?probe=a161ef52b4) | Jun 18, 2023 |
| HP            | 895F                        | All in one  | [1f8ae4f41b](https://linux-hardware.org/?probe=1f8ae4f41b) | Jun 15, 2023 |
| HP            | 895F                        | All in one  | [998f1d4e21](https://linux-hardware.org/?probe=998f1d4e21) | Jun 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2a3c6cf0ab](https://linux-hardware.org/?probe=2a3c6cf0ab) | Jun 14, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [337e4a106e](https://linux-hardware.org/?probe=337e4a106e) | Jun 13, 2023 |
| HP            | 895F                        | All in one  | [355d6e856c](https://linux-hardware.org/?probe=355d6e856c) | Jun 08, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [ac55415914](https://linux-hardware.org/?probe=ac55415914) | Jun 05, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| MSI           | MS-ACD31                    | All in one  | [d958890b05](https://linux-hardware.org/?probe=d958890b05) | May 30, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [4843789a62](https://linux-hardware.org/?probe=4843789a62) | May 30, 2023 |
| Intel         | NUC7JYB J67970-403          | Mini pc     | [8af314920e](https://linux-hardware.org/?probe=8af314920e) | May 29, 2023 |
| HP            | 83F0                        | Desktop     | [77cfad8631](https://linux-hardware.org/?probe=77cfad8631) | May 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a98cdfee26](https://linux-hardware.org/?probe=a98cdfee26) | May 25, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [1e1fb2110f](https://linux-hardware.org/?probe=1e1fb2110f) | May 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [59d36ef46d](https://linux-hardware.org/?probe=59d36ef46d) | May 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3ad250d762](https://linux-hardware.org/?probe=3ad250d762) | May 22, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [c5f452ea28](https://linux-hardware.org/?probe=c5f452ea28) | May 18, 2023 |
| MTR           | DP1000T-B V2.0              | All in one  | [f607fe37d0](https://linux-hardware.org/?probe=f607fe37d0) | May 18, 2023 |
| MSI           | GL62 6QF                    | Notebook    | [6ae5c650f3](https://linux-hardware.org/?probe=6ae5c650f3) | May 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [cf7aa805b4](https://linux-hardware.org/?probe=cf7aa805b4) | May 11, 2023 |
| Dell          | Vostro 5391                 | Notebook    | [f5342b41ec](https://linux-hardware.org/?probe=f5342b41ec) | May 06, 2023 |
| Graviton      | N14I-T                      | Notebook    | [e82c8f00d8](https://linux-hardware.org/?probe=e82c8f00d8) | May 05, 2023 |
| Aquarius      | AQH410T                     | Desktop     | [aeeb40c393](https://linux-hardware.org/?probe=aeeb40c393) | May 04, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [0c5d92ebf9](https://linux-hardware.org/?probe=0c5d92ebf9) | May 04, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [7f787e2e46](https://linux-hardware.org/?probe=7f787e2e46) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [3522381ca7](https://linux-hardware.org/?probe=3522381ca7) | May 02, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a61a9a88bc](https://linux-hardware.org/?probe=a61a9a88bc) | May 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [4ec0da1442](https://linux-hardware.org/?probe=4ec0da1442) | May 02, 2023 |
| MSI           | A520M PRO                   | Desktop     | [6d37fb0e46](https://linux-hardware.org/?probe=6d37fb0e46) | May 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8f8a912636](https://linux-hardware.org/?probe=8f8a912636) | May 01, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [41d545e4d7](https://linux-hardware.org/?probe=41d545e4d7) | Apr 28, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [387eecc18e](https://linux-hardware.org/?probe=387eecc18e) | Apr 27, 2023 |
| Acer          | Aspire C24-963              | All in one  | [7b4eeebdbc](https://linux-hardware.org/?probe=7b4eeebdbc) | Apr 27, 2023 |
| ASRock        | B365M-ITX/ac                | Desktop     | [e4c8218911](https://linux-hardware.org/?probe=e4c8218911) | Apr 27, 2023 |
| Lenovo        | 36F3 No DPK                 | All in one  | [40bd947612](https://linux-hardware.org/?probe=40bd947612) | Apr 24, 2023 |
| Lenovo        | 36F3 SDK0J40688 WIN 3424... | All in one  | [7a81eae6f1](https://linux-hardware.org/?probe=7a81eae6f1) | Apr 24, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [aca220e594](https://linux-hardware.org/?probe=aca220e594) | Apr 22, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [40aaf19667](https://linux-hardware.org/?probe=40aaf19667) | Apr 21, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [eec2055c19](https://linux-hardware.org/?probe=eec2055c19) | Apr 20, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [a9329736fb](https://linux-hardware.org/?probe=a9329736fb) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e2ed275252](https://linux-hardware.org/?probe=e2ed275252) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [a6aaf5f17a](https://linux-hardware.org/?probe=a6aaf5f17a) | Apr 19, 2023 |
| HP            | 81BA 0010                   | All in one  | [b4e5d6fafb](https://linux-hardware.org/?probe=b4e5d6fafb) | Apr 12, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [d2623477d9](https://linux-hardware.org/?probe=d2623477d9) | Apr 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [c959a62e36](https://linux-hardware.org/?probe=c959a62e36) | Apr 10, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [2082d3c772](https://linux-hardware.org/?probe=2082d3c772) | Apr 08, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [cdfdfbcda4](https://linux-hardware.org/?probe=cdfdfbcda4) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [70ff15284b](https://linux-hardware.org/?probe=70ff15284b) | Apr 07, 2023 |
| 3Logic Gro... | TUNDRA                      | Server      | [51dc310024](https://linux-hardware.org/?probe=51dc310024) | Apr 07, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [49921908d1](https://linux-hardware.org/?probe=49921908d1) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [9a068872f6](https://linux-hardware.org/?probe=9a068872f6) | Apr 06, 2023 |
| 3Logic Gro... | TUNDRA                      | Server      | [d4d160584c](https://linux-hardware.org/?probe=d4d160584c) | Apr 06, 2023 |
| HP            | ProBook 4525s               | Notebook    | [164d8993b4](https://linux-hardware.org/?probe=164d8993b4) | Apr 04, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [5fd883493a](https://linux-hardware.org/?probe=5fd883493a) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [44b5c81131](https://linux-hardware.org/?probe=44b5c81131) | Apr 03, 2023 |
| MSI           | Sword 15 A12UE              | Notebook    | [3389b32105](https://linux-hardware.org/?probe=3389b32105) | Apr 01, 2023 |
| Quanta        | 2AC5 100                    | Desktop     | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [36b3103f3f](https://linux-hardware.org/?probe=36b3103f3f) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [deb6990c19](https://linux-hardware.org/?probe=deb6990c19) | Mar 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [ef91ef3645](https://linux-hardware.org/?probe=ef91ef3645) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [eded7b36b1](https://linux-hardware.org/?probe=eded7b36b1) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [9ee3ca41c8](https://linux-hardware.org/?probe=9ee3ca41c8) | Mar 27, 2023 |
| HP            | 0AA4h                       | Desktop     | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| iRU           | P231                        | All in one  | [98e5c0ba37](https://linux-hardware.org/?probe=98e5c0ba37) | Mar 23, 2023 |
| DEPO Compu... | MS-7846                     | Desktop     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| MSI           | Sword 15 A12UE              | Notebook    | [f4341a491a](https://linux-hardware.org/?probe=f4341a491a) | Mar 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [be9b767d92](https://linux-hardware.org/?probe=be9b767d92) | Mar 20, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Biostar       | H610MH                      | Desktop     | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [b473b68faf](https://linux-hardware.org/?probe=b473b68faf) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [4a8589fbdf](https://linux-hardware.org/?probe=4a8589fbdf) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| HP            | 8599                        | Desktop     | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| ASUSTek       | V241DA                      | All in one  | [0779deca8b](https://linux-hardware.org/?probe=0779deca8b) | Feb 28, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4c3b90ede8](https://linux-hardware.org/?probe=4c3b90ede8) | Feb 28, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [98eee7b827](https://linux-hardware.org/?probe=98eee7b827) | Feb 28, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | Desktop     | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [e3156cc208](https://linux-hardware.org/?probe=e3156cc208) | Feb 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [243ef00f70](https://linux-hardware.org/?probe=243ef00f70) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| HP            | 18E7                        | Desktop     | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| iRU           | v1.0                        | Desktop     | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | 31A7 NOK                    | Mini pc     | [17f1e0f135](https://linux-hardware.org/?probe=17f1e0f135) | Feb 16, 2023 |
| iRU           | P231                        | All in one  | [4aa7858493](https://linux-hardware.org/?probe=4aa7858493) | Feb 14, 2023 |
| ICL           | H410SB                      | Desktop     | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| HP            | 895F                        | All in one  | [0c23df771f](https://linux-hardware.org/?probe=0c23df771f) | Feb 13, 2023 |
| Acer          | Aspire C27-1655             | All in one  | [4fe6ca7f88](https://linux-hardware.org/?probe=4fe6ca7f88) | Feb 13, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| HP            | G62                         | Notebook    | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Compal        | DIP00                       | Desktop     | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| HP            | 8599                        | Desktop     | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [c53133f306](https://linux-hardware.org/?probe=c53133f306) | Jan 31, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [9721d24c04](https://linux-hardware.org/?probe=9721d24c04) | Jan 31, 2023 |
| HP            | 8599                        | Desktop     | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| Intel         | S2600WFT H48104-854         | Server      | [68791b3635](https://linux-hardware.org/?probe=68791b3635) | Jan 30, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | Desktop     | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [87c61b6748](https://linux-hardware.org/?probe=87c61b6748) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [186aef8e0c](https://linux-hardware.org/?probe=186aef8e0c) | Jan 24, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| HP            | 18E4                        | Desktop     | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [a74a5b3b7b](https://linux-hardware.org/?probe=a74a5b3b7b) | Jan 20, 2023 |
| ASUSTek       | V241FA                      | All in one  | [24ed481783](https://linux-hardware.org/?probe=24ed481783) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8472d89767](https://linux-hardware.org/?probe=8472d89767) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7d95709d81](https://linux-hardware.org/?probe=7d95709d81) | Jan 19, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [03c97b653e](https://linux-hardware.org/?probe=03c97b653e) | Jan 18, 2023 |
| NCI           | PC BLICK101                 | Soc         | [018eb0b0bb](https://linux-hardware.org/?probe=018eb0b0bb) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [35cae36101](https://linux-hardware.org/?probe=35cae36101) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Unknown       | T310D11                     | Desktop     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [aea58aa72f](https://linux-hardware.org/?probe=aea58aa72f) | Jan 16, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| HP            | 82DC 1000                   | All in one  | [12c8c204ff](https://linux-hardware.org/?probe=12c8c204ff) | Dec 30, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| HP            | 895F                        | All in one  | [670e3fa0fa](https://linux-hardware.org/?probe=670e3fa0fa) | Dec 26, 2022 |
| HP            | Notebook                    | Notebook    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| HP            | 895F                        | All in one  | [8e512dfec4](https://linux-hardware.org/?probe=8e512dfec4) | Dec 23, 2022 |
| HP            | 895F                        | All in one  | [0360aa0d07](https://linux-hardware.org/?probe=0360aa0d07) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| DEPO Compu... | DPH410S                     | Desktop     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | Desktop     | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| ASUSTek       | PB62                        | Desktop     | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| ASUSTek       | PB62                        | Desktop     | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | Notebook    | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| Lenovo        | 10088                       | All in one  | [5fe857bab3](https://linux-hardware.org/?probe=5fe857bab3) | Dec 07, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| MSI           | Sword 15 A12UE              | Notebook    | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| HP            | 84EE 1100                   | All in one  | [7efea8ad7f](https://linux-hardware.org/?probe=7efea8ad7f) | Dec 01, 2022 |
| Lenovo        | Aptio CRB No DPK            | Mini pc     | [eeddc09936](https://linux-hardware.org/?probe=eeddc09936) | Nov 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ddb1791ff6](https://linux-hardware.org/?probe=ddb1791ff6) | Nov 28, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d9ae3d1795](https://linux-hardware.org/?probe=d9ae3d1795) | Nov 27, 2022 |
| Gigabyte      | X570S UD                    | Desktop     | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [812cce763f](https://linux-hardware.org/?probe=812cce763f) | Nov 25, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [bfe8939ffc](https://linux-hardware.org/?probe=bfe8939ffc) | Nov 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ff3d0a1ecf](https://linux-hardware.org/?probe=ff3d0a1ecf) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [f86569d54b](https://linux-hardware.org/?probe=f86569d54b) | Nov 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [a54f42b51e](https://linux-hardware.org/?probe=a54f42b51e) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [faa0deab8f](https://linux-hardware.org/?probe=faa0deab8f) | Nov 18, 2022 |
| Unknown       | P43Twins1600                | Desktop     | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| HP            | 2179                        | Desktop     | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| Lenovo        | ThinkPad X220 4290RB3       | Notebook    | [37959973aa](https://linux-hardware.org/?probe=37959973aa) | Nov 11, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fd33e6782](https://linux-hardware.org/?probe=3fd33e6782) | Nov 09, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [e525d01069](https://linux-hardware.org/?probe=e525d01069) | Nov 08, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [b74787fe62](https://linux-hardware.org/?probe=b74787fe62) | Nov 08, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [dba14315ca](https://linux-hardware.org/?probe=dba14315ca) | Nov 03, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4776ed964f](https://linux-hardware.org/?probe=4776ed964f) | Nov 03, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [2c20efc0df](https://linux-hardware.org/?probe=2c20efc0df) | Nov 03, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | Desktop     | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | Desktop     | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Lenovo        | 3708 NOK                    | Desktop     | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [4887ba4bfa](https://linux-hardware.org/?probe=4887ba4bfa) | Oct 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | Desktop     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [39838b7f39](https://linux-hardware.org/?probe=39838b7f39) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [1011557c31](https://linux-hardware.org/?probe=1011557c31) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [f81210f730](https://linux-hardware.org/?probe=f81210f730) | Oct 18, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [7fa3948164](https://linux-hardware.org/?probe=7fa3948164) | Oct 17, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| HP            | 1495                        | Desktop     | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [97b57f8628](https://linux-hardware.org/?probe=97b57f8628) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [f74f853f54](https://linux-hardware.org/?probe=f74f853f54) | Oct 12, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| MSI           | H55M-E33                    | Desktop     | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASUSTek       | X540NV                      | Notebook    | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | Desktop     | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Lenovo        | 32E4 NOK                    | Mini pc     | [f49f7ba847](https://linux-hardware.org/?probe=f49f7ba847) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | Notebook    | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| ASRock        | B360M-HDV                   | Desktop     | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| RDW           | MB-B450M V.1                | Desktop     | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | Desktop     | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| MSI           | FX610                       | Notebook    | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | Desktop     | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | Notebook    | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4f1a1bfb2d](https://linux-hardware.org/?probe=4f1a1bfb2d) | Jul 19, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| Aquarius      | NS685U                      | Notebook    | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| ICL           | Unknown                     | Notebook    | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| iRU           | v1.0                        | Mini pc     | [845212ce42](https://linux-hardware.org/?probe=845212ce42) | Jun 02, 2022 |
| iRU           | v1.0                        | Mini pc     | [15b125fb9e](https://linux-hardware.org/?probe=15b125fb9e) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [991e061d78](https://linux-hardware.org/?probe=991e061d78) | May 31, 2022 |
| MSI           | A520M PRO                   | Desktop     | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | Desktop     | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | Desktop     | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| ASUSTek       | V241IC-R                    | All in one  | [48add8dc01](https://linux-hardware.org/?probe=48add8dc01) | May 19, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| mtech         | MTL1578                     | Notebook    | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [eefe92e281](https://linux-hardware.org/?probe=eefe92e281) | May 04, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| Aquarius      | NS585 R32                   | Notebook    | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e76e5359b7](https://linux-hardware.org/?probe=e76e5359b7) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | All in one  | [4d3df118f0](https://linux-hardware.org/?probe=4d3df118f0) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [bf51c93832](https://linux-hardware.org/?probe=bf51c93832) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [a831ba5c10](https://linux-hardware.org/?probe=a831ba5c10) | Feb 22, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ICL           | RAYbook Si1514              | Notebook    | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| ASRock        | H470M-HDV                   | Desktop     | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | H110-PLUS                   | Desktop     | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | Desktop     | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| Pegatron      | A35                         | Notebook    | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Red_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Red OS 7.3   | 220       | 47.41%  |
| Red OS 7.3.2 | 110       | 23.71%  |
| Red OS 7.3.1 | 104       | 22.41%  |
| Red OS 8.0   | 19        | 4.09%   |
| Red OS 7.2   | 11        | 2.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Red OS | 441       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.1.52-1.el7.3.x86_64   | 75        | 15.46%  |
| 5.15.87-1.el7.3.x86_64  | 56        | 11.55%  |
| 5.15.10-1.el7.x86_64    | 54        | 11.13%  |
| 5.15.72-1.el7.3.x86_64  | 50        | 10.31%  |
| 5.10.29-1.el7.x86_64    | 37        | 7.63%   |
| 5.15.35-5.el7.3.x86_64  | 25        | 5.15%   |
| 5.15.35-4.el7.3.x86_64  | 19        | 3.92%   |
| 5.10.29-3.el7.x86_64    | 19        | 3.92%   |
| 5.15.78-2.el7.3.x86_64  | 18        | 3.71%   |
| 6.6.6-1.red80.x86_64    | 17        | 3.51%   |
| 5.15.35-1.el7.3.x86_64  | 17        | 3.51%   |
| 6.1.20-2.el7.3.x86_64   | 13        | 2.68%   |
| 5.15.131-1.el7.3.x86_64 | 13        | 2.68%   |
| 6.1.44-1.el7.3.x86_64   | 10        | 2.06%   |
| 5.14.9-1.el7.x86_64     | 8         | 1.65%   |
| 4.19.79-1.el7.x86_64    | 8         | 1.65%   |
| 6.1.38-2.el7.3.x86_64   | 7         | 1.44%   |
| 5.15.125-1.el7.3.x86_64 | 6         | 1.24%   |
| 5.15.10-2.el7.x86_64    | 5         | 1.03%   |
| 5.15.10-3.el7.x86_64    | 4         | 0.82%   |
| 5.10.1-1.el7.x86_64     | 4         | 0.82%   |
| 5.10.24-2.el7.x86_64    | 3         | 0.62%   |
| 6.1.52-1.red80.x86_64   | 2         | 0.41%   |
| 6.1.11-1.el7.3.x86_64   | 2         | 0.41%   |
| 5.18.1-1.el7.x86_64     | 2         | 0.41%   |
| 5.15.10-4.el7.x86_64    | 2         | 0.41%   |
| 6.8.0-rc5+              | 1         | 0.21%   |
| 5.4.197-1.el7.aarch64   | 1         | 0.21%   |
| 5.15.120                | 1         | 0.21%   |
| 5.13.15-1.el7.x86_64    | 1         | 0.21%   |
| 5.10.24-3.el7.x86_64    | 1         | 0.21%   |
| 5.10.24-1.el7.x86_64    | 1         | 0.21%   |
| 4.19.56-2.el7.x86_64    | 1         | 0.21%   |
| 4.19.204-2.el7.x86_64   | 1         | 0.21%   |
| 4.19.204-1.el7.x86_64   | 1         | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.52   | 77        | 16.01%  |
| 5.15.10  | 65        | 13.51%  |
| 5.15.35  | 57        | 11.85%  |
| 5.15.87  | 56        | 11.64%  |
| 5.10.29  | 56        | 11.64%  |
| 5.15.72  | 50        | 10.4%   |
| 5.15.78  | 18        | 3.74%   |
| 6.6.6    | 17        | 3.53%   |
| 6.1.20   | 13        | 2.7%    |
| 5.15.131 | 13        | 2.7%    |
| 6.1.44   | 10        | 2.08%   |
| 5.14.9   | 8         | 1.66%   |
| 4.19.79  | 8         | 1.66%   |
| 6.1.38   | 7         | 1.46%   |
| 5.15.125 | 6         | 1.25%   |
| 5.10.24  | 5         | 1.04%   |
| 5.10.1   | 4         | 0.83%   |
| 6.1.11   | 2         | 0.42%   |
| 5.18.1   | 2         | 0.42%   |
| 4.19.204 | 2         | 0.42%   |
| 6.8.0    | 1         | 0.21%   |
| 5.4.197  | 1         | 0.21%   |
| 5.15.120 | 1         | 0.21%   |
| 5.13.15  | 1         | 0.21%   |
| 4.19.56  | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 247       | 53.7%   |
| 6.1     | 108       | 23.48%  |
| 5.10    | 64        | 13.91%  |
| 6.6     | 17        | 3.7%    |
| 4.19    | 11        | 2.39%   |
| 5.14    | 8         | 1.74%   |
| 5.18    | 2         | 0.43%   |
| 6.8     | 1         | 0.22%   |
| 5.4     | 1         | 0.22%   |
| 5.13    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 440       | 99.77%  |
| aarch64 | 1         | 0.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 365       | 80.75%  |
| Cinnamon   | 53        | 11.73%  |
| X-Cinnamon | 19        | 4.2%    |
| KDE5       | 5         | 1.11%   |
| GNOME      | 5         | 1.11%   |
| Unknown    | 5         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 398       | 89.04%  |
| Tty     | 35        | 7.83%   |
| Wayland | 12        | 2.68%   |
| Unknown | 2         | 0.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 409       | 91.5%   |
| SDDM    | 15        | 3.36%   |
| LightDM | 12        | 2.68%   |
| Unknown | 11        | 2.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| ru_RU   | 257       | 56.61%  |
| Unknown | 190       | 41.85%  |
| en_US   | 6         | 1.32%   |
| en_GB   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 342       | 76.68%  |
| BIOS | 104       | 23.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 435       | 97.97%  |
| Btrfs   | 6         | 1.35%   |
| Xfs     | 1         | 0.23%   |
| Overlay | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 342       | 77.03%  |
| MBR     | 95        | 21.4%   |
| Unknown | 7         | 1.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 414       | 92.62%  |
| Yes       | 33        | 7.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 346       | 77.75%  |
| Yes       | 99        | 22.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 75        | 17.01%  |
| Gigabyte Technology            | 63        | 14.29%  |
| ASUSTek Computer               | 53        | 12.02%  |
| Hewlett-Packard                | 42        | 9.52%   |
| MSI                            | 33        | 7.48%   |
| ASRock                         | 29        | 6.58%   |
| Acer                           | 16        | 3.63%   |
| Unknown                        | 15        | 3.4%    |
| Aquarius                       | 12        | 2.72%   |
| Intel                          | 9         | 2.04%   |
| ICL                            | 9         | 2.04%   |
| Dell                           | 9         | 2.04%   |
| Graviton                       | 8         | 1.81%   |
| DEPO Computers                 | 8         | 1.81%   |
| iRU                            | 7         | 1.59%   |
| HUAWEI                         | 6         | 1.36%   |
| 3Logic Group                   | 5         | 1.13%   |
| Digma                          | 4         | 0.91%   |
| Kraftway                       | 3         | 0.68%   |
| Foxconn                        | 3         | 0.68%   |
| Biostar                        | 3         | 0.68%   |
| RDW                            | 2         | 0.45%   |
| MACHENIKE                      | 2         | 0.45%   |
| IP3 Technology                 | 2         | 0.45%   |
| HONOR                          | 2         | 0.45%   |
| BESHTAU                        | 2         | 0.45%   |
| YADRO                          | 1         | 0.23%   |
| Timi                           | 1         | 0.23%   |
| THUNDEROBOT                    | 1         | 0.23%   |
| SYS                            | 1         | 0.23%   |
| Supermicro                     | 1         | 0.23%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.23%   |
| Quanta                         | 1         | 0.23%   |
| Pegatron                       | 1         | 0.23%   |
| ONDA                           | 1         | 0.23%   |
| NCI                            | 1         | 0.23%   |
| MTR                            | 1         | 0.23%   |
| mtech                          | 1         | 0.23%   |
| KVADRA                         | 1         | 0.23%   |
| INTECH PRO                     | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                              | 17        | 3.85%   |
| Unknown                                          | 17        | 3.85%   |
| MSI MS-7677                                      | 6         | 1.36%   |
| Gigabyte B365M DS3H                              | 5         | 1.13%   |
| ASUS All Series                                  | 5         | 1.13%   |
| ASRock H510M-HVS R2.0                            | 5         | 1.13%   |
| ASRock B365M-ITX/ac                              | 5         | 1.13%   |
| DEPO Computers DPH310T                           | 4         | 0.91%   |
| MSI MS-7D48                                      | 3         | 0.68%   |
| MSI MS-7D14                                      | 3         | 0.68%   |
| MSI MS-7C51                                      | 3         | 0.68%   |
| Lenovo ThinkCentre M70q 11DT003GRU               | 3         | 0.68%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                  | 3         | 0.68%   |
| Kraftway ACCORD                                  | 3         | 0.68%   |
| Intel D945GNT AAC96315-405                       | 3         | 0.68%   |
| ICL RAYbook Si1512                               | 3         | 0.68%   |
| HP Laptop 15s-eq1xxx                             | 3         | 0.68%   |
| Graviton M52i                                    | 3         | 0.68%   |
| Gigabyte H510M H                                 | 3         | 0.68%   |
| Gigabyte H110M-S2                                | 3         | 0.68%   |
| Gigabyte A320M-S2H                               | 3         | 0.68%   |
| DEPO Computers DPH410S                           | 3         | 0.68%   |
| Biostar H610MH                                   | 3         | 0.68%   |
| ASUS PRIME H510T2/CSM                            | 3         | 0.68%   |
| ASUS PRIME H310M-R R2.0                          | 3         | 0.68%   |
| ASRock H61M-DGS                                  | 3         | 0.68%   |
| Acer Aspire C24-963                              | 3         | 0.68%   |
| Acer Aspire A315-24P                             | 3         | 0.68%   |
| MSI MS-7D22                                      | 2         | 0.45%   |
| Lenovo ThinkCentre M720q 10T7S18500              | 2         | 0.45%   |
| Lenovo IdeaPad L340-15API 81LW                   | 2         | 0.45%   |
| Lenovo IdeaCentre AIO 3 24IIL5 F0FR004QRK        | 2         | 0.45%   |
| iRU P2320P                                       | 2         | 0.45%   |
| iRU 15ALC                                        | 2         | 0.45%   |
| IP3 ACN30                                        | 2         | 0.45%   |
| HP EliteOne 870 27 inch G9 All-in-One Desktop PC | 2         | 0.45%   |
| Gigabyte H510M S2H V2                            | 2         | 0.45%   |
| Gigabyte H270-HD3                                | 2         | 0.45%   |
| Gigabyte B75M-D3V                                | 2         | 0.45%   |
| Gigabyte B560M DS3H                              | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo V15-IWL         | 17        | 3.85%   |
| ASUS PRIME             | 17        | 3.85%   |
| Unknown                | 17        | 3.85%   |
| Lenovo ThinkCentre     | 15        | 3.4%    |
| Acer Aspire            | 13        | 2.95%   |
| Lenovo IdeaPad         | 11        | 2.49%   |
| Lenovo ThinkPad        | 9         | 2.04%   |
| Lenovo IdeaCentre      | 8         | 1.81%   |
| Gigabyte B365M         | 7         | 1.59%   |
| MSI MS-7677            | 6         | 1.36%   |
| Lenovo ThinkBook       | 6         | 1.36%   |
| HP Laptop              | 6         | 1.36%   |
| Gigabyte H510M         | 6         | 1.36%   |
| HP Pavilion            | 5         | 1.13%   |
| Gigabyte B560M         | 5         | 1.13%   |
| ASUS All               | 5         | 1.13%   |
| ASRock H510M-HVS       | 5         | 1.13%   |
| ASRock B365M-ITX       | 5         | 1.13%   |
| ICL RAYbook            | 4         | 0.91%   |
| HP ProDesk             | 4         | 0.91%   |
| Gigabyte A320M-S2H     | 4         | 0.91%   |
| DEPO Computers DPH310T | 4         | 0.91%   |
| MSI MS-7D48            | 3         | 0.68%   |
| MSI MS-7D14            | 3         | 0.68%   |
| MSI MS-7C51            | 3         | 0.68%   |
| Kraftway ACCORD        | 3         | 0.68%   |
| Intel D945GNT          | 3         | 0.68%   |
| HP ProOne              | 3         | 0.68%   |
| HP ProBook             | 3         | 0.68%   |
| HP EliteBook           | 3         | 0.68%   |
| HP Compaq              | 3         | 0.68%   |
| Graviton M52i          | 3         | 0.68%   |
| Gigabyte H410M         | 3         | 0.68%   |
| Gigabyte H110M-S2      | 3         | 0.68%   |
| Gigabyte B550          | 3         | 0.68%   |
| Digma EVE              | 3         | 0.68%   |
| DEPO Computers DPH410S | 3         | 0.68%   |
| Dell Vostro            | 3         | 0.68%   |
| Dell OptiPlex          | 3         | 0.68%   |
| Biostar H610MH         | 3         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 84        | 19.05%  |
| 2022 | 75        | 17.01%  |
| 2019 | 68        | 15.42%  |
| 2020 | 48        | 10.88%  |
| 2018 | 28        | 6.35%   |
| 2012 | 26        | 5.9%    |
| 2011 | 22        | 4.99%   |
| 2016 | 14        | 3.17%   |
| 2010 | 12        | 2.72%   |
| 2023 | 11        | 2.49%   |
| 2014 | 10        | 2.27%   |
| 2013 | 10        | 2.27%   |
| 2017 | 9         | 2.04%   |
| 2015 | 8         | 1.81%   |
| 2007 | 6         | 1.36%   |
| 2009 | 4         | 0.91%   |
| 2008 | 3         | 0.68%   |
| 2006 | 3         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 231       | 52.38%  |
| Notebook       | 140       | 31.75%  |
| All in one     | 46        | 10.43%  |
| Mini pc        | 16        | 3.63%   |
| Server         | 6         | 1.36%   |
| System on chip | 1         | 0.23%   |
| Tablet         | 1         | 0.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 436       | 98.87%  |
| Enabled  | 5         | 1.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 441       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 205       | 46.28%  |
| 16.01-24.0      | 95        | 21.44%  |
| 3.01-4.0        | 56        | 12.64%  |
| 8.01-16.0       | 50        | 11.29%  |
| 32.01-64.0      | 12        | 2.71%   |
| 1.01-2.0        | 8         | 1.81%   |
| 2.01-3.0        | 5         | 1.13%   |
| 64.01-256.0     | 4         | 0.9%    |
| More than 256.0 | 3         | 0.68%   |
| 24.01-32.0      | 3         | 0.68%   |
| 0.51-1.0        | 1         | 0.23%   |
| Unknown         | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 223       | 47.75%  |
| 2.01-3.0    | 103       | 22.06%  |
| 4.01-8.0    | 46        | 9.85%   |
| 3.01-4.0    | 44        | 9.42%   |
| 0.51-1.0    | 35        | 7.49%   |
| 8.01-16.0   | 9         | 1.93%   |
| 0.01-0.5    | 3         | 0.64%   |
| 64.01-256.0 | 2         | 0.43%   |
| 16.01-24.0  | 1         | 0.21%   |
| Unknown     | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 336       | 74.17%  |
| 2      | 79        | 17.44%  |
| 3      | 20        | 4.42%   |
| 4      | 7         | 1.55%   |
| 20     | 2         | 0.44%   |
| 7      | 2         | 0.44%   |
| 5      | 2         | 0.44%   |
| 0      | 2         | 0.44%   |
| 19     | 1         | 0.22%   |
| 12     | 1         | 0.22%   |
| 11     | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 336       | 75.68%  |
| Yes       | 108       | 24.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 404       | 91.61%  |
| No        | 37        | 8.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 56.4%   |
| No        | 194       | 43.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 230       | 51.8%   |
| Yes       | 214       | 48.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 438       | 99.32%  |
| Ukraine | 2         | 0.45%   |
| Germany | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 92        | 20.22%  |
| Salekhard         | 52        | 11.43%  |
| Murom             | 44        | 9.67%   |
| Novy Urengoy      | 24        | 5.27%   |
| Labytnangi        | 19        | 4.18%   |
| St Petersburg     | 17        | 3.74%   |
| Perm              | 16        | 3.52%   |
| Yekaterinburg     | 14        | 3.08%   |
| Zima              | 11        | 2.42%   |
| Krasnodar         | 8         | 1.76%   |
| Yuzhno-Sakhalinsk | 7         | 1.54%   |
| Volgograd         | 5         | 1.1%    |
| Vladimir          | 5         | 1.1%    |
| Ryazan            | 5         | 1.1%    |
| Orenburg          | 5         | 1.1%    |
| Kaluga            | 5         | 1.1%    |
| Tver              | 4         | 0.88%   |
| Novosibirsk       | 4         | 0.88%   |
| Muromskiy         | 4         | 0.88%   |
| Khabarovsk        | 4         | 0.88%   |
| Balashikha        | 4         | 0.88%   |
| Yakutsk           | 3         | 0.66%   |
| Veliky Novgorod   | 3         | 0.66%   |
| Ulyanovsk         | 3         | 0.66%   |
| Stavropol         | 3         | 0.66%   |
| Shakhtersk        | 3         | 0.66%   |
| Pushkino          | 3         | 0.66%   |
| Nizhniy Novgorod  | 3         | 0.66%   |
| Nal'chik          | 3         | 0.66%   |
| Nadym             | 3         | 0.66%   |
| Kursk             | 3         | 0.66%   |
| Kurgan            | 3         | 0.66%   |
| Krasnoyarsk       | 3         | 0.66%   |
| Bryansk           | 3         | 0.66%   |
| Vladivostok       | 2         | 0.44%   |
| Ufa               | 2         | 0.44%   |
| Tomsk             | 2         | 0.44%   |
| Surgut            | 2         | 0.44%   |
| Sevastopol        | 2         | 0.44%   |
| Saransk           | 2         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 79        | 105    | 13.88%  |
| WDC                          | 73        | 93     | 12.83%  |
| Samsung Electronics          | 59        | 96     | 10.37%  |
| Kingston                     | 43        | 46     | 7.56%   |
| Toshiba                      | 41        | 80     | 7.21%   |
| A-DATA Technology            | 35        | 37     | 6.15%   |
| SK hynix                     | 20        | 24     | 3.51%   |
| Apacer                       | 14        | 15     | 2.46%   |
| SanDisk                      | 13        | 17     | 2.28%   |
| Foxline                      | 13        | 13     | 2.28%   |
| Intel                        | 11        | 17     | 1.93%   |
| Unknown                      | 9         | 9      | 1.58%   |
| Micron Technology            | 9         | 16     | 1.58%   |
| KingSpec                     | 9         | 9      | 1.58%   |
| Crucial                      | 9         | 13     | 1.58%   |
| Patriot                      | 7         | 7      | 1.23%   |
| China                        | 7         | 14     | 1.23%   |
| Netac                        | 6         | 6      | 1.05%   |
| Hitachi                      | 6         | 6      | 1.05%   |
| HGST                         | 6         | 6      | 1.05%   |
| AGI                          | 6         | 6      | 1.05%   |
| Unknown                      | 6         | 7      | 1.05%   |
| UMIS                         | 5         | 5      | 0.88%   |
| Silicon Motion               | 5         | 5      | 0.88%   |
| Phison                       | 5         | 5      | 0.88%   |
| ExeGate                      | 5         | 6      | 0.88%   |
| AMD                          | 5         | 5      | 0.88%   |
| YMTC                         | 4         | 4      | 0.7%    |
| Transcend                    | 4         | 4      | 0.7%    |
| Qumo                         | 4         | 5      | 0.7%    |
| Gigabyte Technology          | 4         | 4      | 0.7%    |
| SPCC                         | 3         | 3      | 0.53%   |
| Lenovo                       | 3         | 33     | 0.53%   |
| KIOXIA                       | 3         | 3      | 0.53%   |
| HYDRA                        | 3         | 3      | 0.53%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.35%   |
| Plextor                      | 2         | 2      | 0.35%   |
| MSI                          | 2         | 2      | 0.35%   |
| KIOXIA-EXCERIA               | 2         | 2      | 0.35%   |
| JMicron Technology           | 2         | 2      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 3.03%   |
| Toshiba HDWD110 1TB                    | 13        | 2.18%   |
| Kingston SA400S37240G 240GB SSD        | 13        | 2.18%   |
| Seagate ST500DM002-1BD142 500GB        | 11        | 1.85%   |
| A-DATA SX6000PNP 256GB                 | 9         | 1.51%   |
| Seagate ST1000LM049-2GH172 1TB         | 8         | 1.34%   |
| Seagate ST1000DM010-2EP102 1TB         | 8         | 1.34%   |
| Toshiba HDWL110 1TB                    | 6         | 1.01%   |
| Toshiba DT01ACA100 1TB                 | 6         | 1.01%   |
| Foxline FLSSD256M80E13TCX5 256GB       | 6         | 1.01%   |
| Apacer AS2280P4 256GB                  | 6         | 1.01%   |
| Unknown                                | 6         | 1.01%   |
| Samsung SSD 860 EVO 250GB              | 5         | 0.84%   |
| Kingston SNVS500G 500GB                | 5         | 0.84%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.84%   |
| AGI AGI512G16AI198 512GB               | 5         | 0.84%   |
| SK hynix HFM128GDHTNG-8310B 128GB      | 4         | 0.67%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 4         | 0.67%   |
| Seagate ST3160811AS 160GB              | 4         | 0.67%   |
| Seagate ST1000DM010-2DM162 1TB         | 4         | 0.67%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 0.67%   |
| Apacer AS340 240GB SSD                 | 4         | 0.67%   |
| A-DATA SX6000PNP 512GB                 | 4         | 0.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 3         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3         | 0.5%    |
| WDC WD5000AAKX-60U6AA0 500GB           | 3         | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB               | 3         | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB            | 3         | 0.5%    |
| UMIS RPIRJ256VME2MWD 256GB             | 3         | 0.5%    |
| Toshiba DT01ACA050 500GB               | 3         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB         | 3         | 0.5%    |
| SanDisk SD8SBAT256G1122 256GB SSD      | 3         | 0.5%    |
| SanDisk NVMe SSD Drive 512GB           | 3         | 0.5%    |
| Samsung SSD 980 PRO 500GB              | 3         | 0.5%    |
| Samsung SSD 870 EVO 250GB              | 3         | 0.5%    |
| Samsung MZALQ512HALU-000L2 512GB       | 3         | 0.5%    |
| Samsung MZALQ256HBJD-00BL2 256GB       | 3         | 0.5%    |
| Kingston SA400S37120G 120GB SSD        | 3         | 0.5%    |
| Kingston RBUSNS8154P3256GJ1 256GB      | 3         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 104    | 40.84%  |
| WDC                 | 49        | 66     | 25.65%  |
| Toshiba             | 37        | 75     | 19.37%  |
| Hitachi             | 6         | 6      | 3.14%   |
| HGST                | 6         | 6      | 3.14%   |
| Samsung Electronics | 4         | 5      | 2.09%   |
| Unknown             | 3         | 3      | 1.57%   |
| Lenovo              | 2         | 32     | 1.05%   |
| JMicron Technology  | 2         | 2      | 1.05%   |
| Hewlett-Packard     | 2         | 30     | 1.05%   |
| LIO-ORG             | 1         | 1      | 0.52%   |
| HPE                 | 1         | 2      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 32     | 16.95%  |
| Samsung Electronics | 16        | 30     | 9.04%   |
| A-DATA Technology   | 15        | 15     | 8.47%   |
| WDC                 | 12        | 12     | 6.78%   |
| KingSpec            | 9         | 9      | 5.08%   |
| Crucial             | 8         | 12     | 4.52%   |
| Apacer              | 8         | 9      | 4.52%   |
| Foxline             | 7         | 7      | 3.95%   |
| China               | 7         | 14     | 3.95%   |
| SanDisk             | 6         | 10     | 3.39%   |
| Patriot             | 6         | 6      | 3.39%   |
| Intel               | 6         | 12     | 3.39%   |
| ExeGate             | 5         | 6      | 2.82%   |
| Transcend           | 4         | 4      | 2.26%   |
| Qumo                | 4         | 5      | 2.26%   |
| HYDRA               | 3         | 3      | 1.69%   |
| SPCC                | 2         | 2      | 1.13%   |
| Plextor             | 2         | 2      | 1.13%   |
| Netac               | 2         | 2      | 1.13%   |
| Micron Technology   | 2         | 2      | 1.13%   |
| KIOXIA-EXCERIA      | 2         | 2      | 1.13%   |
| GOODRAM             | 2         | 2      | 1.13%   |
| AMD                 | 2         | 2      | 1.13%   |
| Unknown             | 2         | 2      | 1.13%   |
| Verbatim            | 1         | 1      | 0.56%   |
| TXRUI               | 1         | 1      | 0.56%   |
| Toshiba             | 1         | 1      | 0.56%   |
| Thinkplus           | 1         | 1      | 0.56%   |
| SPCC Sol            | 1         | 1      | 0.56%   |
| Smartbuy            | 1         | 1      | 0.56%   |
| Seagate             | 1         | 1      | 0.56%   |
| Lenovo              | 1         | 1      | 0.56%   |
| HS-SSD-E100         | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 4      | 0.56%   |
| Gigabyte Technology | 1         | 1      | 0.56%   |
| Digma               | 1         | 1      | 0.56%   |
| Dahua               | 1         | 1      | 0.56%   |
| Corsair             | 1         | 2      | 0.56%   |
| AGI                 | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 190       | 230    | 35.12%  |
| HDD     | 174       | 332    | 32.16%  |
| SSD     | 165       | 221    | 30.5%   |
| MMC     | 7         | 9      | 1.29%   |
| Unknown | 5         | 5      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 284       | 535    | 57.37%  |
| NVMe | 190       | 230    | 38.38%  |
| SAS  | 14        | 23     | 2.83%   |
| MMC  | 7         | 9      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 210       | 296    | 61.4%   |
| 0.51-1.0   | 109       | 169    | 31.87%  |
| 1.01-2.0   | 11        | 22     | 3.22%   |
| 2.01-3.0   | 5         | 46     | 1.46%   |
| 3.01-4.0   | 4         | 8      | 1.17%   |
| 4.01-10.0  | 3         | 12     | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 189       | 41.81%  |
| 251-500        | 118       | 26.11%  |
| 501-1000       | 72        | 15.93%  |
| 1001-2000      | 32        | 7.08%   |
| 51-100         | 17        | 3.76%   |
| 21-50          | 8         | 1.77%   |
| More than 3000 | 6         | 1.33%   |
| 2001-3000      | 5         | 1.11%   |
| 1-20           | 4         | 0.88%   |
| Unknown        | 1         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 260       | 56.03%  |
| 21-50          | 99        | 21.34%  |
| 101-250        | 31        | 6.68%   |
| 51-100         | 30        | 6.47%   |
| 501-1000       | 18        | 3.88%   |
| 251-500        | 14        | 3.02%   |
| 1001-2000      | 6         | 1.29%   |
| More than 3000 | 4         | 0.86%   |
| 2001-3000      | 1         | 0.22%   |
| Unknown        | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 7         | 8      | 12.96%  |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 3.7%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 3.7%    |
| Toshiba MK2565GSX 250GB             | 2         | 2      | 3.7%    |
| Seagate ST3500413AS 500GB           | 2         | 2      | 3.7%    |
| Seagate ST3160811AS 160GB           | 2         | 2      | 3.7%    |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 6      | 3.7%    |
| WDC WD7500BPVT-00HXZT3 752GB        | 1         | 1      | 1.85%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 2      | 1.85%   |
| WDC WD5000AAKS-00D2B0 500GB         | 1         | 1      | 1.85%   |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 1.85%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 1.85%   |
| WDC WD10EZEX-75ZF5A0 1TB            | 1         | 2      | 1.85%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1         | 1      | 1.85%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1         | 1      | 1.85%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 1.85%   |
| WDC WD10EALX-009BA0 1TB             | 1         | 1      | 1.85%   |
| WDC WD Green M.2 2280 240GB         | 1         | 1      | 1.85%   |
| WDC WD Blue SA510 2.5 500GB SSD     | 1         | 1      | 1.85%   |
| Toshiba MQ01ABF050 500GB            | 1         | 15     | 1.85%   |
| Toshiba MK5075GSX 500GB             | 1         | 9      | 1.85%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 1.85%   |
| SPCC M.2 PCIe SSD 512GB             | 1         | 1      | 1.85%   |
| Seagate ST9500423AS 500GB           | 1         | 1      | 1.85%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 1.85%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 1.85%   |
| Seagate ST3250823AS 250GB           | 1         | 1      | 1.85%   |
| Seagate ST3250318AS 250GB           | 1         | 2      | 1.85%   |
| Seagate ST31000524NS 1TB            | 1         | 1      | 1.85%   |
| Seagate ST2000DM001-1CH164 2TB      | 1         | 1      | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 1.85%   |
| Samsung Electronics HD400LJ 400GB   | 1         | 1      | 1.85%   |
| Samsung Electronics HD161HJ 160GB   | 1         | 1      | 1.85%   |
| Kingston SUV400S37120G 120GB SSD    | 1         | 1      | 1.85%   |
| Kingston SHPM2280P2H 240G SSD       | 1         | 1      | 1.85%   |
| HYDRA SSD 256G                      | 1         | 1      | 1.85%   |
| Hitachi HTS543232A7A384 320GB       | 1         | 1      | 1.85%   |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 1.85%   |
| Hitachi HDS5C1050CLA382 500GB       | 1         | 1      | 1.85%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 27     | 39.62%  |
| WDC                 | 16        | 18     | 30.19%  |
| Toshiba             | 4         | 27     | 7.55%   |
| Hitachi             | 3         | 3      | 5.66%   |
| Samsung Electronics | 2         | 2      | 3.77%   |
| Kingston            | 2         | 2      | 3.77%   |
| SPCC                | 1         | 1      | 1.89%   |
| HYDRA               | 1         | 1      | 1.89%   |
| HGST                | 1         | 1      | 1.89%   |
| A-DATA Technology   | 1         | 1      | 1.89%   |
| Unknown             | 1         | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 27     | 47.73%  |
| WDC                 | 13        | 15     | 29.55%  |
| Toshiba             | 4         | 27     | 9.09%   |
| Hitachi             | 3         | 3      | 6.82%   |
| Samsung Electronics | 2         | 2      | 4.55%   |
| HGST                | 1         | 1      | 2.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 75     | 83.33%  |
| SSD  | 7         | 8      | 14.58%  |
| NVMe | 1         | 1      | 2.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST250LT012-9WS141 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 389       | 659    | 82.77%  |
| Malfunc  | 48        | 84     | 10.21%  |
| Detected | 32        | 53     | 6.81%   |
| Failed   | 1         | 1      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 344       | 56.49%  |
| AMD                            | 60        | 9.85%   |
| Samsung Electronics            | 41        | 6.73%   |
| Phison Electronics             | 23        | 3.78%   |
| SK hynix                       | 20        | 3.28%   |
| SanDisk                        | 19        | 3.12%   |
| Kingston Technology Company    | 15        | 2.46%   |
| Silicon Motion                 | 13        | 2.13%   |
| Realtek Semiconductor          | 13        | 2.13%   |
| ADATA Technology               | 9         | 1.48%   |
| Micron Technology              | 7         | 1.15%   |
| Union Memory (Shenzhen)        | 5         | 0.82%   |
| Yangtze Memory Technologies    | 4         | 0.66%   |
| MAXIO Technology (Hangzhou)    | 4         | 0.66%   |
| Toshiba America Info Systems   | 3         | 0.49%   |
| Shenzhen Longsys Electronics   | 3         | 0.49%   |
| Nvidia                         | 3         | 0.49%   |
| Netac Technology               | 3         | 0.49%   |
| LSI Logic / Symbios Logic      | 3         | 0.49%   |
| KIOXIA                         | 3         | 0.49%   |
| ASMedia Technology             | 3         | 0.49%   |
| ShenZhen TIGO Semiconductor    | 2         | 0.33%   |
| JMicron Technology             | 2         | 0.33%   |
| Hewlett-Packard                | 2         | 0.33%   |
| Zhaoxin                        | 1         | 0.16%   |
| VIA Technologies               | 1         | 0.16%   |
| Solid State Storage Technology | 1         | 0.16%   |
| Micron/Crucial Technology      | 1         | 0.16%   |
| Marvell Technology Group       | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 47        | 6.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 42        | 6.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 31        | 4.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 30        | 4.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 28        | 4.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23        | 3.4%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 22        | 3.25%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 20        | 2.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 14        | 2.07%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 13        | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11        | 1.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 1.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 11        | 1.62%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11        | 1.62%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 10        | 1.48%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 10        | 1.48%   |
| AMD FCH SATA Controller D                                                               | 10        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9         | 1.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 8         | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 1.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 7         | 1.03%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 7         | 1.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 6         | 0.89%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 0.89%   |
| SK hynix BC511 NVMe SSD                                                                 | 5         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 5         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 0.74%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)  | 5         | 0.74%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 4         | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 0.59%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 4         | 0.59%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 4         | 0.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 365       | 59.16%  |
| NVMe | 190       | 30.79%  |
| IDE  | 35        | 5.67%   |
| RAID | 25        | 4.05%   |
| SAS  | 2         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 360       | 81.63%  |
| AMD          | 79        | 17.91%  |
| CentaurHauls | 1         | 0.23%   |
| ARM          | 1         | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz              | 20        | 4.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 4.08%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 18        | 4.08%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 13        | 2.95%   |
| Intel 12th Gen Core i5-12400                  | 9         | 2.04%   |
| Intel 12th Gen Core i3-12100                  | 9         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.81%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 7         | 1.59%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 1.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 1.36%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 6         | 1.36%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 1.13%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 5         | 1.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.13%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 5         | 1.13%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 4         | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.91%   |
| Intel Core i5-8400T CPU @ 1.70GHz             | 4         | 0.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.91%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.91%   |
| Intel Core i3-8100T CPU @ 3.10GHz             | 4         | 0.91%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 4         | 0.91%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.91%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 4         | 0.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.91%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 4         | 0.91%   |
| Intel Pentium CPU G4500 @ 3.50GHz             | 3         | 0.68%   |
| Intel Pentium 4 CPU 3.06GHz                   | 3         | 0.68%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 3         | 0.68%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 0.68%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 3         | 0.68%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 3         | 0.68%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 3         | 0.68%   |
| Intel Core i3-10100T CPU @ 3.00GHz            | 3         | 0.68%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.68%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.68%   |
| Intel 12th Gen Core i5-12500H                 | 3         | 0.68%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 3         | 0.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 131       | 29.71%  |
| Intel Core i3                  | 72        | 16.33%  |
| Other                          | 71        | 16.1%   |
| AMD Ryzen 5                    | 26        | 5.9%    |
| Intel Core i7                  | 22        | 4.99%   |
| AMD Ryzen 3                    | 21        | 4.76%   |
| Intel Celeron                  | 18        | 4.08%   |
| Intel Pentium                  | 13        | 2.95%   |
| Intel Pentium Gold             | 12        | 2.72%   |
| AMD Ryzen 7                    | 8         | 1.81%   |
| Intel Core 2 Duo               | 7         | 1.59%   |
| Intel Xeon                     | 5         | 1.13%   |
| AMD Ryzen 5 PRO                | 5         | 1.13%   |
| Intel Pentium 4                | 3         | 0.68%   |
| AMD FX                         | 3         | 0.68%   |
| AMD A6                         | 3         | 0.68%   |
| AMD Ryzen 7 PRO                | 2         | 0.45%   |
| AMD Phenom II                  | 2         | 0.45%   |
| AMD Athlon II X2               | 2         | 0.45%   |
| AMD Athlon                     | 2         | 0.45%   |
| Intel Xeon Silver              | 1         | 0.23%   |
| Intel Xeon Gold                | 1         | 0.23%   |
| Intel Xeon Bronze              | 1         | 0.23%   |
| Intel Pentium Silver           | 1         | 0.23%   |
| Intel Pentium Dual-Core        | 1         | 0.23%   |
| Intel Pentium Dual             | 1         | 0.23%   |
| Intel Core 2                   | 1         | 0.23%   |
| Intel Atom                     | 1         | 0.23%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.23%   |
| AMD Ryzen 9                    | 1         | 0.23%   |
| AMD Ryzen 3 PRO                | 1         | 0.23%   |
| AMD Phenom                     | 1         | 0.23%   |
| AMD A4                         | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 187       | 42.4%   |
| 2      | 106       | 24.04%  |
| 6      | 96        | 21.77%  |
| 8      | 23        | 5.22%   |
| 12     | 8         | 1.81%   |
| 10     | 6         | 1.36%   |
| 1      | 6         | 1.36%   |
| 16     | 2         | 0.45%   |
| 14     | 2         | 0.45%   |
| 3      | 2         | 0.45%   |
| 36     | 1         | 0.23%   |
| 28     | 1         | 0.23%   |
| 24     | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 436       | 98.87%  |
| 2      | 5         | 1.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 299       | 67.8%   |
| 1      | 142       | 32.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 440       | 99.77%  |
| Unknown        | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0xa0653    | 53        | 11.91%  |
| 0x806ec    | 26        | 5.84%   |
| 0x906ea    | 24        | 5.39%   |
| 0x206a7    | 24        | 5.39%   |
| 0x90675    | 21        | 4.72%   |
| 0x306a9    | 21        | 4.72%   |
| Unknown    | 21        | 4.72%   |
| 0x806c1    | 17        | 3.82%   |
| 0x906ed    | 14        | 3.15%   |
| 0x306c3    | 14        | 3.15%   |
| 0x806ea    | 12        | 2.7%    |
| 0x08600106 | 12        | 2.7%    |
| 0x506e3    | 11        | 2.47%   |
| 0x08108109 | 11        | 2.47%   |
| 0x906eb    | 10        | 2.25%   |
| 0xa0671    | 9         | 2.02%   |
| 0x0a50000c | 9         | 2.02%   |
| 0x906e9    | 7         | 1.57%   |
| 0x906a4    | 7         | 1.57%   |
| 0x906a3    | 7         | 1.57%   |
| 0x706e5    | 7         | 1.57%   |
| 0x08608103 | 7         | 1.57%   |
| 0xa0655    | 4         | 0.9%    |
| 0x40651    | 4         | 0.9%    |
| 0x1067a    | 4         | 0.9%    |
| 0x0810100b | 4         | 0.9%    |
| 0xf49      | 3         | 0.67%   |
| 0x90672    | 3         | 0.67%   |
| 0x806d1    | 3         | 0.67%   |
| 0x706a8    | 3         | 0.67%   |
| 0x50657    | 3         | 0.67%   |
| 0x406e3    | 3         | 0.67%   |
| 0x306f2    | 3         | 0.67%   |
| 0x0a50000d | 3         | 0.67%   |
| 0x08a00006 | 3         | 0.67%   |
| 0x08108102 | 3         | 0.67%   |
| 0x08101016 | 3         | 0.67%   |
| 0x010000c8 | 3         | 0.67%   |
| 0x706a1    | 2         | 0.45%   |
| 0x6fd      | 2         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 99        | 22.45%  |
| CometLake        | 62        | 14.06%  |
| Alderlake Hybrid | 41        | 9.3%    |
| SandyBridge      | 24        | 5.44%   |
| IvyBridge        | 21        | 4.76%   |
| Haswell          | 21        | 4.76%   |
| TigerLake        | 18        | 4.08%   |
| Skylake          | 18        | 4.08%   |
| Unknown          | 18        | 4.08%   |
| Zen+             | 16        | 3.63%   |
| Zen 2            | 16        | 3.63%   |
| IceLake          | 16        | 3.63%   |
| Zen 3            | 14        | 3.17%   |
| Zen              | 8         | 1.81%   |
| Penryn           | 6         | 1.36%   |
| Goldmont plus    | 6         | 1.36%   |
| Westmere         | 5         | 1.13%   |
| K10              | 5         | 1.13%   |
| Core             | 5         | 1.13%   |
| Goldmont         | 4         | 0.91%   |
| Excavator        | 4         | 0.91%   |
| NetBurst         | 3         | 0.68%   |
| Silvermont       | 2         | 0.45%   |
| Nehalem          | 2         | 0.45%   |
| Bulldozer        | 2         | 0.45%   |
| Piledriver       | 1         | 0.23%   |
| K8 & K10 hybrid  | 1         | 0.23%   |
| Gracemont        | 1         | 0.23%   |
| Broadwell        | 1         | 0.23%   |
| Bonnell          | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 319       | 66.32%  |
| AMD                        | 84        | 17.46%  |
| Nvidia                     | 69        | 14.35%  |
| ASPEED Technology          | 4         | 0.83%   |
| Matrox Electronics Systems | 2         | 0.42%   |
| ATI Technologies           | 2         | 0.42%   |
| Zhaoxin                    | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 50        | 10.29%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 39        | 8.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 21        | 4.32%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 19        | 3.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19        | 3.91%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 14        | 2.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 14        | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11        | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 11        | 2.26%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                            | 11        | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11        | 2.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10        | 2.06%   |
| Intel HD Graphics 530                                                       | 9         | 1.85%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 7         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 7         | 1.44%   |
| AMD Lucienne                                                                | 7         | 1.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 6         | 1.23%   |
| Intel HD Graphics 630                                                       | 6         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 1.23%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 6         | 1.23%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 1.03%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 5         | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 0.82%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 4         | 0.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 0.82%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 4         | 0.82%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 4         | 0.82%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4         | 0.82%   |
| ASPEED Technology ASPEED Graphics Family                                    | 4         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 3         | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 3         | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 0.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 0.62%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3         | 0.62%   |
| Intel HD Graphics 500                                                       | 3         | 0.62%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 3         | 0.62%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3         | 0.62%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 282       | 63.95%  |
| 1 x AMD        | 71        | 16.1%   |
| 1 x Nvidia     | 40        | 9.07%   |
| Intel + Nvidia | 25        | 5.67%   |
| Intel + AMD    | 8         | 1.81%   |
| 1 x ASPEED     | 4         | 0.91%   |
| AMD + Nvidia   | 4         | 0.91%   |
| 2 x AMD        | 3         | 0.68%   |
| 1 x Matrox     | 2         | 0.45%   |
| Other          | 1         | 0.23%   |
| 1 x Zhaoxin    | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 378       | 85.14%  |
| Unknown     | 51        | 11.49%  |
| Proprietary | 15        | 3.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 315       | 70.79%  |
| 1.01-2.0   | 49        | 11.01%  |
| 0.01-0.5   | 39        | 8.76%   |
| 0.51-1.0   | 27        | 6.07%   |
| 3.01-4.0   | 11        | 2.47%   |
| 7.01-8.0   | 3         | 0.67%   |
| 2.01-3.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 61        | 14.45%  |
| Philips              | 45        | 10.66%  |
| Samsung Electronics  | 44        | 10.43%  |
| Acer                 | 30        | 7.11%   |
| LG Display           | 19        | 4.5%    |
| Lenovo               | 18        | 4.27%   |
| Hewlett-Packard      | 18        | 4.27%   |
| Chimei Innolux       | 17        | 4.03%   |
| BenQ                 | 15        | 3.55%   |
| ViewSonic            | 14        | 3.32%   |
| AU Optronics         | 14        | 3.32%   |
| AOC                  | 14        | 3.32%   |
| Dell                 | 13        | 3.08%   |
| Goldstar             | 11        | 2.61%   |
| SGT                  | 9         | 2.13%   |
| ASUSTek Computer     | 8         | 1.9%    |
| PANDA                | 5         | 1.18%   |
| SKM                  | 4         | 0.95%   |
| NEC Computers        | 4         | 0.95%   |
| CHD                  | 4         | 0.95%   |
| Toshiba              | 3         | 0.71%   |
| Sony                 | 3         | 0.71%   |
| OOO                  | 3         | 0.71%   |
| Iiyama               | 3         | 0.71%   |
| ECS                  | 3         | 0.71%   |
| Daewoo               | 3         | 0.71%   |
| Ancor Communications | 3         | 0.71%   |
| VIE                  | 2         | 0.47%   |
| TR_                  | 2         | 0.47%   |
| TMX                  | 2         | 0.47%   |
| RTK                  | 2         | 0.47%   |
| NLE                  | 2         | 0.47%   |
| ITE                  | 2         | 0.47%   |
| HUAWEI               | 2         | 0.47%   |
| CS_                  | 2         | 0.47%   |
| CHR                  | 2         | 0.47%   |
| XYK                  | 1         | 0.24%   |
| XSP                  | 1         | 0.24%   |
| WYT                  | 1         | 0.24%   |
| STD                  | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 19        | 4.39%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 15        | 3.46%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 9         | 2.08%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                 | 9         | 2.08%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 7         | 1.62%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 6         | 1.39%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 5         | 1.15%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5         | 1.15%   |
| Lenovo TIO22Gen4 LEN111A 1920x1080 476x268mm 21.5-inch                | 5         | 1.15%   |
| Acer LCD Monitor ACR40B0 1920x1080 527x296mm 23.8-inch                | 5         | 1.15%   |
| SKM T24 Air SKM9322 1920x1080 519x324mm 24.1-inch                     | 4         | 0.92%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.92%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.92%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 4         | 0.92%   |
| Acer SA240Y ACR057F 1920x1080 530x300mm 24.0-inch                     | 4         | 0.92%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 3         | 0.69%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.69%   |
| Lenovo LEN-A-A LENF908 1920x1080 596x335mm 26.9-inch                  | 3         | 0.69%   |
| Lenovo LEN-24ARR-B LEN1201 1920x1080 527x296mm 23.8-inch              | 3         | 0.69%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                   | 3         | 0.69%   |
| ECS AIO PC ECS2486 1920x1080 520x300mm 23.6-inch                      | 3         | 0.69%   |
| Daewoo HDMI DWE2100 1280x1024 476x268mm 21.5-inch                     | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.69%   |
| CHD DM-MONB2401 CHD2380 1920x1080 527x296mm 23.8-inch                 | 3         | 0.69%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                 | 3         | 0.69%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO0100 1920x1080                            | 3         | 0.69%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2         | 0.46%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2         | 0.46%   |
| VIE IM27VL1 VIE1919 1920x1080 600x330mm 27.0-inch                     | 2         | 0.46%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 2         | 0.46%   |
| Toshiba LCD Monitor 1 1 5" LCD000D 1024x768 304x228mm 15.0-inch       | 2         | 0.46%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 2         | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 2         | 0.46%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2         | 0.46%   |
| Samsung Electronics S24B300 SAM08B2 1920x1080 531x299mm 24.0-inch     | 2         | 0.46%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch     | 2         | 0.46%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 282       | 72.12%  |
| 1280x1024 (SXGA)   | 25        | 6.39%   |
| 1366x768 (WXGA)    | 20        | 5.12%   |
| 2560x1440 (QHD)    | 16        | 4.09%   |
| 1600x900 (HD+)     | 13        | 3.32%   |
| 1920x1200 (WUXGA)  | 9         | 2.3%    |
| 3840x2160 (4K)     | 8         | 2.05%   |
| 3440x1440          | 3         | 0.77%   |
| 1280x800 (WXGA)    | 3         | 0.77%   |
| 1024x768 (XGA)     | 3         | 0.77%   |
| 1600x1200          | 2         | 0.51%   |
| 3200x2000          | 1         | 0.26%   |
| 2560x1600          | 1         | 0.26%   |
| 2560x1080          | 1         | 0.26%   |
| 2240x1400          | 1         | 0.26%   |
| 1680x1050 (WSXGA+) | 1         | 0.26%   |
| 1440x900 (WXGA+)   | 1         | 0.26%   |
| 1280x960           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 104       | 24.94%  |
| 23      | 76        | 18.23%  |
| 24      | 63        | 15.11%  |
| 21      | 52        | 12.47%  |
| 27      | 28        | 6.71%   |
| 19      | 15        | 3.6%    |
| 17      | 15        | 3.6%    |
| 20      | 12        | 2.88%   |
| 14      | 9         | 2.16%   |
| 13      | 6         | 1.44%   |
| 31      | 4         | 0.96%   |
| 26      | 4         | 0.96%   |
| 12      | 4         | 0.96%   |
| Unknown | 4         | 0.96%   |
| 34      | 3         | 0.72%   |
| 18      | 3         | 0.72%   |
| 84      | 2         | 0.48%   |
| 40      | 2         | 0.48%   |
| 32      | 2         | 0.48%   |
| 25      | 2         | 0.48%   |
| 22      | 2         | 0.48%   |
| 16      | 2         | 0.48%   |
| 55      | 1         | 0.24%   |
| 54      | 1         | 0.24%   |
| 11      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 161       | 39.95%  |
| 301-350     | 129       | 32.01%  |
| 401-500     | 67        | 16.63%  |
| 351-400     | 21        | 5.21%   |
| 201-300     | 6         | 1.49%   |
| 701-800     | 5         | 1.24%   |
| 601-700     | 4         | 0.99%   |
| Unknown     | 4         | 0.99%   |
| 1501-2000   | 2         | 0.5%    |
| 1001-1500   | 2         | 0.5%    |
| 901-1000    | 2         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 323       | 83.46%  |
| 16/10 | 28        | 7.24%   |
| 5/4   | 25        | 6.46%   |
| 4/3   | 5         | 1.29%   |
| 21/9  | 5         | 1.29%   |
| 6/5   | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 146       | 35.52%  |
| 101-110        | 104       | 25.3%   |
| 151-200        | 48        | 11.68%  |
| 301-350        | 32        | 7.79%   |
| 251-300        | 23        | 5.6%    |
| 81-90          | 14        | 3.41%   |
| 141-150        | 12        | 2.92%   |
| 351-500        | 9         | 2.19%   |
| 121-130        | 5         | 1.22%   |
| More than 1000 | 4         | 0.97%   |
| 61-70          | 4         | 0.97%   |
| Unknown        | 4         | 0.97%   |
| 501-1000       | 2         | 0.49%   |
| 71-80          | 1         | 0.24%   |
| 51-60          | 1         | 0.24%   |
| 131-140        | 1         | 0.24%   |
| 111-120        | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 199       | 50.38%  |
| 121-160       | 102       | 25.82%  |
| 101-120       | 82        | 20.76%  |
| 161-240       | 5         | 1.27%   |
| Unknown       | 4         | 1.01%   |
| 1-50          | 2         | 0.51%   |
| More than 240 | 1         | 0.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 338       | 75.11%  |
| 0     | 65        | 14.44%  |
| 2     | 45        | 10%     |
| 3     | 2         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 312       | 52.7%   |
| Intel                    | 177       | 29.9%   |
| Qualcomm Atheros         | 22        | 3.72%   |
| Broadcom                 | 17        | 2.87%   |
| Xiaomi                   | 11        | 1.86%   |
| MediaTek                 | 10        | 1.69%   |
| TP-Link                  | 7         | 1.18%   |
| Samsung Electronics      | 4         | 0.68%   |
| Ralink                   | 4         | 0.68%   |
| Mercucys                 | 4         | 0.68%   |
| Ralink Technology        | 3         | 0.51%   |
| Nvidia                   | 3         | 0.51%   |
| Huawei Technologies      | 3         | 0.51%   |
| Qualcomm                 | 2         | 0.34%   |
| Xilinx                   | 1         | 0.17%   |
| VIA Technologies         | 1         | 0.17%   |
| OPPO Electronics         | 1         | 0.17%   |
| OKB SAPR                 | 1         | 0.17%   |
| Metrologic Instruments   | 1         | 0.17%   |
| Mellanox Technologies    | 1         | 0.17%   |
| Marvell Technology Group | 1         | 0.17%   |
| Edimax Technology        | 1         | 0.17%   |
| D-Link                   | 1         | 0.17%   |
| Broadcom Limited         | 1         | 0.17%   |
| ASUSTek Computer         | 1         | 0.17%   |
| ASIX Electronics         | 1         | 0.17%   |
| American Megatrends      | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 243       | 34.52%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 41        | 5.82%   |
| Intel Wireless 7265                                                    | 17        | 2.41%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 13        | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.56%   |
| Intel Ethernet Controller I225-V                                       | 11        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 1.42%   |
| Intel Ethernet Connection (17) I219-V                                  | 10        | 1.42%   |
| Intel Ethernet Connection (14) I219-V                                  | 10        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 10        | 1.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 1.28%   |
| Intel Wireless 3165                                                    | 9         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 1.14%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 0.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 6         | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.71%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 0.71%   |
| Intel Ethernet Connection (11) I219-V                                  | 5         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.57%   |
| Mercucys 802.11n NIC                                                   | 4         | 0.57%   |
| Intel Wireless 8265 / 8275                                             | 4         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.57%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 4         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 0.57%   |
| Intel Ethernet Connection (17) I219-LM                                 | 4         | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 3         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 116       | 44.44%  |
| Realtek Semiconductor | 86        | 32.95%  |
| Qualcomm Atheros      | 16        | 6.13%   |
| Broadcom              | 14        | 5.36%   |
| MediaTek              | 7         | 2.68%   |
| TP-Link               | 6         | 2.3%    |
| Ralink                | 4         | 1.53%   |
| Mercucys              | 4         | 1.53%   |
| Ralink Technology     | 3         | 1.15%   |
| Qualcomm              | 1         | 0.38%   |
| Edimax Technology     | 1         | 0.38%   |
| D-Link                | 1         | 0.38%   |
| Broadcom Limited      | 1         | 0.38%   |
| ASUSTek Computer      | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 41        | 15.59%  |
| Intel Wireless 7265                                            | 17        | 6.46%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 4.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 4.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 3.8%    |
| Intel Wireless 3165                                            | 9         | 3.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 3.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 3.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 2.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6         | 2.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5         | 1.9%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.52%   |
| Mercucys 802.11n NIC                                           | 4         | 1.52%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.14%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 1.14%   |
| Realtek 802.11ac NIC                                           | 3         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.14%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 3         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.14%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.14%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 274       | 64.32%  |
| Intel                    | 111       | 26.06%  |
| Xiaomi                   | 11        | 2.58%   |
| Qualcomm Atheros         | 6         | 1.41%   |
| Samsung Electronics      | 4         | 0.94%   |
| Nvidia                   | 3         | 0.7%    |
| MediaTek                 | 3         | 0.7%    |
| Broadcom                 | 3         | 0.7%    |
| Huawei Technologies      | 2         | 0.47%   |
| VIA Technologies         | 1         | 0.23%   |
| TP-Link                  | 1         | 0.23%   |
| Qualcomm                 | 1         | 0.23%   |
| OPPO Electronics         | 1         | 0.23%   |
| OKB SAPR                 | 1         | 0.23%   |
| Mellanox Technologies    | 1         | 0.23%   |
| Marvell Technology Group | 1         | 0.23%   |
| ASIX Electronics         | 1         | 0.23%   |
| American Megatrends      | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 243       | 55.48%  |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 2.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.51%   |
| Intel Ethernet Controller I225-V                                       | 11        | 2.51%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 2.28%   |
| Intel Ethernet Connection (17) I219-V                                  | 10        | 2.28%   |
| Intel Ethernet Connection (14) I219-V                                  | 10        | 2.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 2.05%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 2.05%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 1.83%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 1.14%   |
| Intel Ethernet Connection (11) I219-V                                  | 5         | 1.14%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 4         | 0.91%   |
| Intel Ethernet Connection (17) I219-LM                                 | 4         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.68%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.68%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.46%   |
| MediaTek RMX3085                                                       | 2         | 0.46%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 0.46%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.46%   |
| Intel Ethernet Controller I225-LM                                      | 2         | 0.46%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.46%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.46%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.46%   |
| Intel Ethernet Connection (12) I219-V                                  | 2         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.46%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.46%   |
| Huawei VTR-L09                                                         | 2         | 0.46%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.23%   |
| TP-Link USB 10/100 LAN                                                 | 1         | 0.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.23%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.23%   |
| Qualcomm Nokia G42 5G                                                  | 1         | 0.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 405       | 61.46%  |
| WiFi     | 251       | 38.09%  |
| Modem    | 2         | 0.3%    |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 337       | 74.56%  |
| WiFi     | 115       | 25.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 242       | 54.88%  |
| 2     | 186       | 42.18%  |
| 4     | 5         | 1.13%   |
| 0     | 5         | 1.13%   |
| 3     | 2         | 0.45%   |
| 7     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 430       | 96.85%  |
| Yes  | 14        | 3.15%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 106       | 49.53%  |
| Realtek Semiconductor           | 55        | 25.7%   |
| IMC Networks                    | 11        | 5.14%   |
| Broadcom                        | 11        | 5.14%   |
| Qualcomm Atheros Communications | 7         | 3.27%   |
| Lite-On Technology              | 5         | 2.34%   |
| Foxconn / Hon Hai               | 3         | 1.4%    |
| Cambridge Silicon Radio         | 3         | 1.4%    |
| TP-Link                         | 2         | 0.93%   |
| Realtek                         | 2         | 0.93%   |
| Ralink                          | 2         | 0.93%   |
| Hewlett-Packard                 | 2         | 0.93%   |
| Taiyo Yuden                     | 1         | 0.47%   |
| Opticis                         | 1         | 0.47%   |
| MediaTek                        | 1         | 0.47%   |
| Foxconn International           | 1         | 0.47%   |
| ASUSTek Computer                | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 49        | 22.9%   |
| Intel AX201 Bluetooth                               | 35        | 16.36%  |
| Intel Bluetooth wireless interface                  | 29        | 13.55%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 7.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 4.21%   |
| Intel AX211 Bluetooth                               | 7         | 3.27%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.34%   |
| Intel Bluetooth Device                              | 5         | 2.34%   |
| Intel AX200 Bluetooth                               | 5         | 2.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 1.4%    |
| IMC Networks Wireless_Device                        | 3         | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.4%    |
| TP-Link UB500 Adapter                               | 2         | 0.93%   |
| Realtek Bluetooth Radio                             | 2         | 0.93%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.93%   |
| IMC Networks Bluetooth Device                       | 2         | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.93%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.93%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.93%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.47%   |
| Realtek Bluetooth 5.3 Radio                         | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.47%   |
| Opticis Bluetooth Radio                             | 1         | 0.47%   |
| MediaTek Wireless_Device                            | 1         | 0.47%   |
| Lite-On Wireless_Device                             | 1         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.47%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.47%   |
| Broadcom HP Portable Valentine                      | 1         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.47%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.47%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.47%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.47%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 354       | 68.34%  |
| AMD                    | 85        | 16.41%  |
| Nvidia                 | 48        | 9.27%   |
| Lenovo                 | 7         | 1.35%   |
| Texas Instruments      | 6         | 1.16%   |
| C-Media Electronics    | 6         | 1.16%   |
| Razer USA              | 2         | 0.39%   |
| Logitech               | 2         | 0.39%   |
| Generalplus Technology | 2         | 0.39%   |
| Zhaoxin                | 1         | 0.19%   |
| Samson Technologies    | 1         | 0.19%   |
| MosArt Semiconductor   | 1         | 0.19%   |
| JMTek                  | 1         | 0.19%   |
| GN Netcom              | 1         | 0.19%   |
| Creative Technology    | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 58        | 9.7%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 39        | 6.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 32        | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 31        | 5.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 5.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 29        | 4.85%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 4.35%   |
| Intel Alder Lake-S HD Audio Controller                                     | 24        | 4.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 3.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 3.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 2.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 2.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 2.01%   |
| Intel Comet Lake PCH-V cAVS                                                | 12        | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 1.67%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.51%   |
| Nvidia High Definition Audio Controller                                    | 7         | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.17%   |
| Texas Instruments PCM2902 Audio Codec                                      | 6         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 0.84%   |
| Lenovo ThinkCentre TIO22Gen4 for USB Audio                                 | 5         | 0.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 0.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.67%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 0.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 0.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.67%   |
| Nvidia MCP61 High Definition Audio                                         | 3         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 95        | 20.04%  |
| Crucial                                 | 57        | 12.03%  |
| SK hynix                                | 52        | 10.97%  |
| Kingston                                | 51        | 10.76%  |
| Unknown                                 | 30        | 6.33%   |
| Foxline                                 | 28        | 5.91%   |
| Micron Technology                       | 23        | 4.85%   |
| Apacer                                  | 14        | 2.95%   |
| Ramaxel Technology                      | 13        | 2.74%   |
| Patriot                                 | 13        | 2.74%   |
| A-DATA Technology                       | 13        | 2.74%   |
| AMD                                     | 10        | 2.11%   |
| Unknown                                 | 8         | 1.69%   |
| Unknown (ABCD)                          | 7         | 1.48%   |
| Elpida                                  | 5         | 1.05%   |
| Silicon Power Computer & Communications | 3         | 0.63%   |
| Silicon Power                           | 3         | 0.63%   |
| Qumo                                    | 3         | 0.63%   |
| KingSpec                                | 3         | 0.63%   |
| G.Skill                                 | 3         | 0.63%   |
| Corsair                                 | 3         | 0.63%   |
| Unknown (89F7)                          | 2         | 0.42%   |
| Unknown (0x7FFF)                        | 2         | 0.42%   |
| Unknown (0x0080)                        | 2         | 0.42%   |
| SHARETRONIC                             | 2         | 0.42%   |
| Neo Forza                               | 2         | 0.42%   |
| KingTiger                               | 2         | 0.42%   |
| HomeNet                                 | 2         | 0.42%   |
| Hewlett-Packard                         | 2         | 0.42%   |
| ChangXin Memory                         | 2         | 0.42%   |
| Unknown (BA8A)                          | 1         | 0.21%   |
| Unknown (8AD6)                          | 1         | 0.21%   |
| Unknown (0B7A)                          | 1         | 0.21%   |
| TXRUI                                   | 1         | 0.21%   |
| Transcend                               | 1         | 0.21%   |
| Shenzhen Micro Innovation Industry      | 1         | 0.21%   |
| Patriot Memory (PDP Systems)            | 1         | 0.21%   |
| Netac                                   | 1         | 0.21%   |
| Kingmax                                 | 1         | 0.21%   |
| King Tiger                              | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 3.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 1.62%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 8         | 1.62%   |
| Unknown                                                          | 8         | 1.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.21%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s                | 6         | 1.21%   |
| Patriot RAM PSD44G266681 4GB DIMM DDR4 2667MT/s                  | 5         | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.81%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.81%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.81%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 4         | 0.81%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 4         | 0.81%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                      | 4         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 3         | 0.61%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 0.61%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 3         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.61%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.61%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s              | 3         | 0.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.61%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 3         | 0.61%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 3         | 0.61%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s             | 3         | 0.61%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s           | 3         | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.4%    |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 316       | 73.15%  |
| DDR3    | 67        | 15.51%  |
| LPDDR4  | 11        | 2.55%   |
| DDR2    | 10        | 2.31%   |
| Unknown | 10        | 2.31%   |
| SDRAM   | 8         | 1.85%   |
| LPDDR5  | 5         | 1.16%   |
| DDR5    | 3         | 0.69%   |
| LPDDR3  | 1         | 0.23%   |
| DDR     | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 211       | 48.06%  |
| DIMM         | 206       | 46.92%  |
| Row Of Chips | 21        | 4.78%   |
| Chip         | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 242       | 52.72%  |
| 4096  | 107       | 23.31%  |
| 16384 | 54        | 11.76%  |
| 2048  | 32        | 6.97%   |
| 1024  | 12        | 2.61%   |
| 32768 | 10        | 2.18%   |
| 65536 | 1         | 0.22%   |
| 512   | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 125       | 27.78%  |
| 3200    | 122       | 27.11%  |
| 1600    | 37        | 8.22%   |
| 2400    | 35        | 7.78%   |
| 1333    | 25        | 5.56%   |
| 2133    | 13        | 2.89%   |
| 2666    | 10        | 2.22%   |
| 2933    | 7         | 1.56%   |
| 3600    | 6         | 1.33%   |
| 6400    | 5         | 1.11%   |
| 800     | 5         | 1.11%   |
| 667     | 5         | 1.11%   |
| 3266    | 4         | 0.89%   |
| 533     | 4         | 0.89%   |
| 4800    | 3         | 0.67%   |
| 2800    | 3         | 0.67%   |
| 1866    | 3         | 0.67%   |
| 1800    | 3         | 0.67%   |
| 1066    | 3         | 0.67%   |
| Unknown | 3         | 0.67%   |
| 5200    | 2         | 0.44%   |
| 3866    | 2         | 0.44%   |
| 3733    | 2         | 0.44%   |
| 3533    | 2         | 0.44%   |
| 3466    | 2         | 0.44%   |
| 2934    | 2         | 0.44%   |
| 1334    | 2         | 0.44%   |
| 333     | 2         | 0.44%   |
| 3800    | 1         | 0.22%   |
| 3334    | 1         | 0.22%   |
| 3066    | 1         | 0.22%   |
| 3000    | 1         | 0.22%   |
| 2866    | 1         | 0.22%   |
| 2733    | 1         | 0.22%   |
| 2187    | 1         | 0.22%   |
| 2134    | 1         | 0.22%   |
| 2000    | 1         | 0.22%   |
| 1648    | 1         | 0.22%   |
| 1067    | 1         | 0.22%   |
| 975     | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 10        | 58.82%  |
| Canon           | 4         | 23.53%  |
| Kyocera         | 2         | 11.76%  |
| Pantum          | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP LaserJet P2055 series      | 2         | 11.76%  |
| HP HP LaserJet P2035          | 2         | 11.76%  |
| Pantum BM5100ADN series       | 1         | 5.88%   |
| Kyocera FS-1040               | 1         | 5.88%   |
| Kyocera ECOSYS M2135dn        | 1         | 5.88%   |
| HP LaserJet Pro M428-M429     | 1         | 5.88%   |
| HP LaserJet M402dn            | 1         | 5.88%   |
| HP LaserJet M203-M206         | 1         | 5.88%   |
| HP LaserJet M109-M112         | 1         | 5.88%   |
| HP LaserJet 1010              | 1         | 5.88%   |
| HP Designjet T1200 PostScript | 1         | 5.88%   |
| Canon MF4800 Series           | 1         | 5.88%   |
| Canon MF440 Series            | 1         | 5.88%   |
| Canon MF410 Series            | 1         | 5.88%   |
| Canon MF3010                  | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP ScanJet Pro 2000 s2  | 1         | 33.33%  |
| Canon CanoScan LIDE 25  | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 14.91%  |
| Syntek                                 | 25        | 10.96%  |
| IMC Networks                           | 20        | 8.77%   |
| SunplusIT                              | 17        | 7.46%   |
| Microdia                               | 16        | 7.02%   |
| Bison Electronics                      | 15        | 6.58%   |
| Realtek Semiconductor                  | 13        | 5.7%    |
| Quanta                                 | 13        | 5.7%    |
| Alcor Micro                            | 11        | 4.82%   |
| Sunplus Innovation Technology          | 9         | 3.95%   |
| Logitech                               | 7         | 3.07%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.63%   |
| Luxvisions Innotech Limited            | 5         | 2.19%   |
| Hopewin Electronic Material            | 5         | 2.19%   |
| Acer                                   | 5         | 2.19%   |
| Z-Star Microelectronics                | 3         | 1.32%   |
| Suyin                                  | 3         | 1.32%   |
| USB Camera CS                          | 2         | 0.88%   |
| Sonix Technology                       | 2         | 0.88%   |
| Lite-On Technology                     | 2         | 0.88%   |
| lihappe8                               | 2         | 0.88%   |
| KYE Systems (Mouse Systems)            | 2         | 0.88%   |
| AlcorMicroCorp                         | 2         | 0.88%   |
| Primax Electronics                     | 1         | 0.44%   |
| Novatek Microelectronics               | 1         | 0.44%   |
| JMicron Technology                     | 1         | 0.44%   |
| icSpring                               | 1         | 0.44%   |
| GEMBIRD                                | 1         | 0.44%   |
| Creative Technology                    | 1         | 0.44%   |
| Arkmicro Technologies                  | 1         | 0.44%   |
| Apple                                  | 1         | 0.44%   |
| Unknown                                | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 22        | 9.65%   |
| SunplusIT USB Camera                                | 13        | 5.7%    |
| Chicony USB camera                                  | 10        | 4.39%   |
| Alcor Micro USB 2.0 PC Camera                       | 8         | 3.51%   |
| IMC Networks Integrated Camera                      | 7         | 3.07%   |
| Microdia USB 2.0 Camera                             | 6         | 2.63%   |
| Bison Integrated Camera                             | 6         | 2.63%   |
| Realtek USB Camera                                  | 5         | 2.19%   |
| Realtek 1080p Camera                                | 5         | 2.19%   |
| Microdia Camera                                     | 5         | 2.19%   |
| Hopewin Electronic Material Integrated Camera       | 5         | 2.19%   |
| Chicony Integrated Camera                           | 5         | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.75%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 1.75%   |
| Bison BisonCam,NB Pro                               | 4         | 1.75%   |
| Sunplus PC Camera                                   | 3         | 1.32%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.32%   |
| Logitech HD Webcam C615                             | 3         | 1.32%   |
| IMC Networks HD Camera                              | 3         | 1.32%   |
| Chicony HP High Definition 1MP Webcam               | 3         | 1.32%   |
| Chicony ACER HD User Facing                         | 3         | 1.32%   |
| Acer Integrated Camera                              | 3         | 1.32%   |
| USB Camera CS USB Camera CS                         | 2         | 0.88%   |
| SunplusIT USB 2.0 Camera                            | 2         | 0.88%   |
| Sonix USB 2.0 Camera                                | 2         | 0.88%   |
| Realtek Integrated_Webcam_HD                        | 2         | 0.88%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 0.88%   |
| Quanta HP Webcam                                    | 2         | 0.88%   |
| Microdia Webcam Vitade AF                           | 2         | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.88%   |
| Logitech Webcam C270                                | 2         | 0.88%   |
| Lite-On HP 2.0MP High Definition Webcam             | 2         | 0.88%   |
| lihappe8 USB 2.0 Camera                             | 2         | 0.88%   |
| Chicony USB2.0 Camera                               | 2         | 0.88%   |
| Chicony HP Webcam [2 MP Macro]                      | 2         | 0.88%   |
| Chicony HD User Facing                              | 2         | 0.88%   |
| Bison HD Webcam                                     | 2         | 0.88%   |
| AlcorMicroCorp SHUNCCM                              | 2         | 0.88%   |
| Alcor Micro USB FHD Camera                          | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 9         | 56.25%  |
| Validity Sensors           | 4         | 25%     |
| Synaptics                  | 2         | 12.5%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 9         | 56.25%  |
| Validity Sensors VFS451 Fingerprint Reader        | 2         | 12.5%   |
| Synaptics UWP WBDI Device                         | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 6.25%   |
| AuthenTec AES2550 Fingerprint Sensor              | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Aktiv        | 8         | 72.73%  |
| Aladdin R.D. | 2         | 18.18%  |
| Upek         | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Aktiv Rutoken lite                                         | 8         | 72.73%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 9.09%   |
| Aladdin R.D. Smart card reader JCR721                      | 1         | 9.09%   |
| Aladdin R.D. JaCarta                                       | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 332       | 74.27%  |
| 1     | 93        | 20.81%  |
| 2     | 17        | 3.8%    |
| 4     | 3         | 0.67%   |
| 3     | 2         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 60        | 43.8%   |
| Net/wireless             | 26        | 18.98%  |
| Fingerprint reader       | 16        | 11.68%  |
| Unassigned class         | 8         | 5.84%   |
| Communication controller | 7         | 5.11%   |
| Multimedia controller    | 5         | 3.65%   |
| Sound                    | 3         | 2.19%   |
| Chipcard                 | 3         | 2.19%   |
| Network                  | 2         | 1.46%   |
| Net/ethernet             | 2         | 1.46%   |
| Bluetooth                | 2         | 1.46%   |
| Storage/raid             | 1         | 0.73%   |
| Storage                  | 1         | 0.73%   |
| Camera                   | 1         | 0.73%   |


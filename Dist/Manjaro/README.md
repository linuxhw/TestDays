Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 9801

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | Desktop     | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | Desktop     | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | Notebook    | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Pegatron      | Benicia                     | Desktop     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [44b55b4721](https://linux-hardware.org/?probe=44b55b4721) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Multilaser    | UB820                       | All in one  | [3796d857b1](https://linux-hardware.org/?probe=3796d857b1) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [38c117ee87](https://linux-hardware.org/?probe=38c117ee87) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [3c50d5d61c](https://linux-hardware.org/?probe=3c50d5d61c) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [f2d4f962d2](https://linux-hardware.org/?probe=f2d4f962d2) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [f75685d3be](https://linux-hardware.org/?probe=f75685d3be) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | Desktop     | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | Notebook    | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [3efc88e5df](https://linux-hardware.org/?probe=3efc88e5df) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | Notebook    | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e8e85fe2af](https://linux-hardware.org/?probe=e8e85fe2af) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | Desktop     | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [0c49ead576](https://linux-hardware.org/?probe=0c49ead576) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | Notebook    | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | 802E                        | Desktop     | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| ASUSTek       | GR6                         | Desktop     | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| AZW           | GT-R                        | Notebook    | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4e6c5f4b6](https://linux-hardware.org/?probe=f4e6c5f4b6) | Apr 12, 2023 |
| Dell          | Precision 5520              | Notebook    | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | Desktop     | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [8e2b7b11ec](https://linux-hardware.org/?probe=8e2b7b11ec) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| Lenovo        | SKYBAY SDK0J40679 WIN 32... | All in one  | [810692eb45](https://linux-hardware.org/?probe=810692eb45) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Huanan        | X99-F8                      | Desktop     | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HP            | 84FD                        | Desktop     | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5fb3f8e0ef](https://linux-hardware.org/?probe=5fb3f8e0ef) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4061ae40b8](https://linux-hardware.org/?probe=4061ae40b8) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [7d6ecc10d8](https://linux-hardware.org/?probe=7d6ecc10d8) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| Star Labs     | StarBook                    | Notebook    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | Notebook    | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Dell          | Precision M6400             | Notebook    | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | Notebook    | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| HP            | 82BF                        | Mini pc     | [305883be65](https://linux-hardware.org/?probe=305883be65) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [d6a9697313](https://linux-hardware.org/?probe=d6a9697313) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | Notebook    | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | Notebook    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | Notebook    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | Desktop     | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [36fece4941](https://linux-hardware.org/?probe=36fece4941) | Mar 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Multilaser    | UB820                       | All in one  | [9d056bd8e0](https://linux-hardware.org/?probe=9d056bd8e0) | Mar 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| Intel         | NUC12WSBv7 M36952-400       | Mini pc     | [f7ecd6ff17](https://linux-hardware.org/?probe=f7ecd6ff17) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | Notebook    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| HP            | 245 G8                      | Notebook    | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Sony          | SVZ1311C5E                  | Notebook    | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [fe5cfbcd29](https://linux-hardware.org/?probe=fe5cfbcd29) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c325d4fcb0](https://linux-hardware.org/?probe=c325d4fcb0) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | Notebook    | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Dell          | G5 5587                     | Notebook    | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [e1c3ac639e](https://linux-hardware.org/?probe=e1c3ac639e) | Mar 14, 2023 |
| Positivo      | Q464B                       | Notebook    | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | Desktop     | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | Desktop     | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | Desktop     | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | Desktop     | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | Notebook    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [9e24f3fc16](https://linux-hardware.org/?probe=9e24f3fc16) | Mar 12, 2023 |
| HP            | 212B                        | Desktop     | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| Dell          | Latitude 5590               | Notebook    | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | Notebook    | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | Notebook    | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| HP            | 8597                        | Desktop     | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| Google        | Delbin                      | Notebook    | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| LG Electro... | 22V240 FAB3                 | All in one  | [163c52fd3c](https://linux-hardware.org/?probe=163c52fd3c) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | Notebook    | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| AZW           | GTR V01                     | Mini pc     | [c788211e6d](https://linux-hardware.org/?probe=c788211e6d) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | Desktop     | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1213e49ca8](https://linux-hardware.org/?probe=1213e49ca8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [97b08529eb](https://linux-hardware.org/?probe=97b08529eb) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | Notebook    | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | Notebook    | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| AZW           | SER                         | Mini pc     | [bca19a22d8](https://linux-hardware.org/?probe=bca19a22d8) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [235831e22a](https://linux-hardware.org/?probe=235831e22a) | Feb 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | Notebook    | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | Desktop     | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [2c41f563a1](https://linux-hardware.org/?probe=2c41f563a1) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | Desktop     | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| HP            | Notebook                    | Notebook    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | Desktop     | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [3599b137c4](https://linux-hardware.org/?probe=3599b137c4) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Dell          | G3 3590                     | Notebook    | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Intel         | H61                         | Desktop     | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [43fbbe7df5](https://linux-hardware.org/?probe=43fbbe7df5) | Feb 17, 2023 |
| HP            | 8053                        | Desktop     | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| Jumper        | EZbook                      | Notebook    | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | Notebook    | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [3e6dcbc3f9](https://linux-hardware.org/?probe=3e6dcbc3f9) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | Notebook    | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | Desktop     | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [ca16764b59](https://linux-hardware.org/?probe=ca16764b59) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| HP            | 3397                        | Desktop     | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [cbdda8d7e0](https://linux-hardware.org/?probe=cbdda8d7e0) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [270400302e](https://linux-hardware.org/?probe=270400302e) | Feb 10, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | Notebook    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [ef2d2504b8](https://linux-hardware.org/?probe=ef2d2504b8) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1f4b88ad7f](https://linux-hardware.org/?probe=1f4b88ad7f) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [9baaf935a7](https://linux-hardware.org/?probe=9baaf935a7) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | Notebook    | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | Desktop     | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| Timi          | A34S                        | Notebook    | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Intel         | H61                         | Desktop     | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | Notebook    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | Notebook    | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | Notebook    | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Unknown       | ARM5                        | Mini pc     | [aad3a07e37](https://linux-hardware.org/?probe=aad3a07e37) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [2fee4a59ba](https://linux-hardware.org/?probe=2fee4a59ba) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| HP            | Compaq 6530b                | Notebook    | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Unknown       | ARM5                        | Mini pc     | [1b3ea4360c](https://linux-hardware.org/?probe=1b3ea4360c) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [027f04536c](https://linux-hardware.org/?probe=027f04536c) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [d23feafd62](https://linux-hardware.org/?probe=d23feafd62) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [405a60b1e3](https://linux-hardware.org/?probe=405a60b1e3) | Jan 24, 2023 |
| realme        | CloudProXXXX                | Notebook    | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| Dell          | Inspiron 7573               | Convertible | [855d0fd69b](https://linux-hardware.org/?probe=855d0fd69b) | Jan 24, 2023 |
| Dell          | Inspiron 7573               | Convertible | [f2df75c3db](https://linux-hardware.org/?probe=f2df75c3db) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 9320                    | Notebook    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| Acer          | Aspire C22-865              | All in one  | [eb0191f969](https://linux-hardware.org/?probe=eb0191f969) | Jan 23, 2023 |
| System76      | Darter UltraThin            | Notebook    | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Samsung       | 730QDA                      | Convertible | [4796f92a58](https://linux-hardware.org/?probe=4796f92a58) | Jan 22, 2023 |
| Samsung       | 730QDA                      | Convertible | [bbd0fe538f](https://linux-hardware.org/?probe=bbd0fe538f) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| Toshiba       | Satellite C50-C             | Notebook    | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | Notebook    | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| HP            | 85A2                        | All in one  | [13fcd2dd69](https://linux-hardware.org/?probe=13fcd2dd69) | Jan 20, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| Acer          | Aspire C22-865              | All in one  | [90ea1c9655](https://linux-hardware.org/?probe=90ea1c9655) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| AZW           | SER V01                     | Mini pc     | [b209807db5](https://linux-hardware.org/?probe=b209807db5) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | Desktop     | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | Desktop     | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Intel         | X99                         | Desktop     | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4b877715b1](https://linux-hardware.org/?probe=4b877715b1) | Jan 15, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [9ac53f405e](https://linux-hardware.org/?probe=9ac53f405e) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | Notebook    | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| Shuttle       | FS61                        | Desktop     | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9f06213ef6](https://linux-hardware.org/?probe=9f06213ef6) | Jan 12, 2023 |
| HP            | ProBook 6560b               | Notebook    | [5b71b83435](https://linux-hardware.org/?probe=5b71b83435) | Jan 12, 2023 |
| Notebook      | L14xMU                      | Notebook    | [48b282b529](https://linux-hardware.org/?probe=48b282b529) | Jan 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [ede9b6da76](https://linux-hardware.org/?probe=ede9b6da76) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [5be6eaa40c](https://linux-hardware.org/?probe=5be6eaa40c) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [f78e703512](https://linux-hardware.org/?probe=f78e703512) | Jan 11, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [1fa3917cc0](https://linux-hardware.org/?probe=1fa3917cc0) | Jan 11, 2023 |
| Dell          | Precision 7710              | Notebook    | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e829eab59d](https://linux-hardware.org/?probe=e829eab59d) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [c618ab31a8](https://linux-hardware.org/?probe=c618ab31a8) | Jan 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [99bb69023a](https://linux-hardware.org/?probe=99bb69023a) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| Dell          | Precision 7710              | Notebook    | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [af68cbff10](https://linux-hardware.org/?probe=af68cbff10) | Jan 09, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [2eaea530ea](https://linux-hardware.org/?probe=2eaea530ea) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [8682a08d74](https://linux-hardware.org/?probe=8682a08d74) | Jan 09, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [5feb203761](https://linux-hardware.org/?probe=5feb203761) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [da175172b3](https://linux-hardware.org/?probe=da175172b3) | Jan 08, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ca9c5df4b3](https://linux-hardware.org/?probe=ca9c5df4b3) | Jan 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| IPASON        | MaxBook P1X                 | Notebook    | [b7d1ce416f](https://linux-hardware.org/?probe=b7d1ce416f) | Jan 07, 2023 |
| Sony          | SVS1512U1RW                 | Notebook    | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [5f50538338](https://linux-hardware.org/?probe=5f50538338) | Jan 06, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [631c1eea14](https://linux-hardware.org/?probe=631c1eea14) | Jan 06, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c298dd423d](https://linux-hardware.org/?probe=c298dd423d) | Jan 05, 2023 |
| Unknown       | AM02                        | Mini pc     | [6f6c81bf78](https://linux-hardware.org/?probe=6f6c81bf78) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [47654afbbc](https://linux-hardware.org/?probe=47654afbbc) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| Lenovo        | 31900058 STD or WIN         | Desktop     | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [c8d9352d43](https://linux-hardware.org/?probe=c8d9352d43) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [ddadb5f34d](https://linux-hardware.org/?probe=ddadb5f34d) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| Dell          | Latitude 7410               | Notebook    | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [c5d2fc381a](https://linux-hardware.org/?probe=c5d2fc381a) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [04364cac9a](https://linux-hardware.org/?probe=04364cac9a) | Jan 02, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | Desktop     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | Notebook    | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5b5e58e433](https://linux-hardware.org/?probe=5b5e58e433) | Dec 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c2a949b725](https://linux-hardware.org/?probe=c2a949b725) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7be9115c85](https://linux-hardware.org/?probe=7be9115c85) | Dec 30, 2022 |
| Google        | Nautilus                    | Convertible | [8d1977d0ae](https://linux-hardware.org/?probe=8d1977d0ae) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [599c42b4e6](https://linux-hardware.org/?probe=599c42b4e6) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [0e619635fe](https://linux-hardware.org/?probe=0e619635fe) | Dec 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c42c0afa9b](https://linux-hardware.org/?probe=c42c0afa9b) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | Desktop     | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a986dd2bf4](https://linux-hardware.org/?probe=a986dd2bf4) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| HP            | ProBook 6470b               | Notebook    | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | Notebook    | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | Notebook    | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [c36792aeaa](https://linux-hardware.org/?probe=c36792aeaa) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [434eb9ba86](https://linux-hardware.org/?probe=434eb9ba86) | Dec 23, 2022 |
| Dell          | Precision M6600             | Notebook    | [00840d085c](https://linux-hardware.org/?probe=00840d085c) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | Notebook    | [94e5bdb2cb](https://linux-hardware.org/?probe=94e5bdb2cb) | Dec 22, 2022 |
| HP            | 8053                        | Desktop     | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Acer          | Spin SP314-21               | Convertible | [3f7986b3c2](https://linux-hardware.org/?probe=3f7986b3c2) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [59f4b3b5b4](https://linux-hardware.org/?probe=59f4b3b5b4) | Dec 21, 2022 |
| ASRock        | X670E Taichi                | Desktop     | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [4e38f93dd3](https://linux-hardware.org/?probe=4e38f93dd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [1498d2b037](https://linux-hardware.org/?probe=1498d2b037) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [36ac1009a7](https://linux-hardware.org/?probe=36ac1009a7) | Dec 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | Notebook    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [654a04cdc4](https://linux-hardware.org/?probe=654a04cdc4) | Dec 20, 2022 |
| ATOPNUC       | MA90                        | Mini pc     | [441c2c54c5](https://linux-hardware.org/?probe=441c2c54c5) | Dec 19, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [6ab908c6b2](https://linux-hardware.org/?probe=6ab908c6b2) | Dec 19, 2022 |
| K.A.Techno... | TM1                         | Notebook    | [88e36a5d00](https://linux-hardware.org/?probe=88e36a5d00) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | Desktop     | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| ASUSTek       | Zenbook Flip UP5302ZA_UP... | Convertible | [a9925bf157](https://linux-hardware.org/?probe=a9925bf157) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| HP            | 2000                        | Notebook    | [6273a792ae](https://linux-hardware.org/?probe=6273a792ae) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [86fbbf1bc2](https://linux-hardware.org/?probe=86fbbf1bc2) | Dec 17, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Alienware     | 15                          | Notebook    | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [8f50c0d881](https://linux-hardware.org/?probe=8f50c0d881) | Dec 15, 2022 |
| Dell          | Vostro 7590                 | Notebook    | [c758af3223](https://linux-hardware.org/?probe=c758af3223) | Dec 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| ZOTAC         | ION                         | Desktop     | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [3878d884cb](https://linux-hardware.org/?probe=3878d884cb) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [98f6e27cac](https://linux-hardware.org/?probe=98f6e27cac) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| K.A.Techno... | TM1                         | Notebook    | [a27835f164](https://linux-hardware.org/?probe=a27835f164) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 2722      | 38.62%  |
| Manjaro 22.0.0 | 323       | 4.58%   |
| Manjaro 20.1   | 291       | 4.13%   |
| Manjaro 20.2.1 | 283       | 4.01%   |
| Manjaro 20.2   | 243       | 3.45%   |
| Manjaro 20.0.3 | 223       | 3.16%   |
| Manjaro 21.2.6 | 176       | 2.5%    |
| Manjaro 21.1.0 | 149       | 2.11%   |
| Manjaro 18.1.5 | 143       | 2.03%   |
| Manjaro 21.2.0 | 127       | 1.8%    |
| Manjaro 21.2.5 | 126       | 1.79%   |
| Manjaro 21.1.6 | 114       | 1.62%   |
| Manjaro 21.0.7 | 113       | 1.6%    |
| Manjaro 20.0   | 101       | 1.43%   |
| Manjaro 19.0.2 | 97        | 1.38%   |
| Manjaro 18.0.4 | 96        | 1.36%   |
| Manjaro 21.0   | 87        | 1.23%   |
| Manjaro 21.0.5 | 80        | 1.13%   |
| Manjaro 20.1.2 | 80        | 1.13%   |
| Manjaro 21.2.3 | 74        | 1.05%   |
| Manjaro 21.2.1 | 73        | 1.04%   |
| Manjaro 20.1.1 | 71        | 1.01%   |
| Manjaro 20.0.1 | 69        | 0.98%   |
| Manjaro 22.1.0 | 61        | 0.87%   |
| Manjaro 22.0.4 | 56        | 0.79%   |
| Manjaro 21.3.7 | 56        | 0.79%   |
| Manjaro 21.0.4 | 50        | 0.71%   |
| Manjaro 21.3.6 | 49        | 0.7%    |
| Manjaro 21.2.2 | 46        | 0.65%   |
| Manjaro 21.2.4 | 45        | 0.64%   |
| Manjaro 21.1.2 | 41        | 0.58%   |
| Manjaro 21.1.4 | 37        | 0.52%   |
| Manjaro 21.0.1 | 36        | 0.51%   |
| Manjaro 22.0.5 | 35        | 0.5%    |
| Manjaro 21.0.2 | 34        | 0.48%   |
| Manjaro 21.3.1 | 32        | 0.45%   |
| Manjaro 21.3.0 | 31        | 0.44%   |
| Manjaro 21.0.3 | 31        | 0.44%   |
| Manjaro 21.1.1 | 30        | 0.43%   |
| Manjaro 22.0   | 29        | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 6458      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 294       | 3.82%   |
| 5.13.19-2-MANJARO | 180       | 2.34%   |
| 5.8.6-1-MANJARO   | 140       | 1.82%   |
| 5.9.11-3-MANJARO  | 129       | 1.68%   |
| 5.8.11-1-MANJARO  | 122       | 1.59%   |
| 5.15.28-1-MANJARO | 118       | 1.54%   |
| 5.10.42-1-MANJARO | 102       | 1.33%   |
| 6.1.1-1-MANJARO   | 101       | 1.31%   |
| 5.8.18-1-MANJARO  | 101       | 1.31%   |
| 5.15.32-1-MANJARO | 100       | 1.3%    |
| 6.1.12-1-MANJARO  | 86        | 1.12%   |
| 5.15.12-1-MANJARO | 82        | 1.07%   |
| 5.6.16-1-MANJARO  | 74        | 0.96%   |
| 5.15.60-1-MANJARO | 74        | 0.96%   |
| 5.8.16-2-MANJARO  | 73        | 0.95%   |
| 5.10.2-2-MANJARO  | 65        | 0.85%   |
| 5.15.65-1-MANJARO | 62        | 0.81%   |
| 5.7.9-1-MANJARO   | 61        | 0.79%   |
| 5.10.36-2-MANJARO | 61        | 0.79%   |
| 5.6.19-2-MANJARO  | 60        | 0.78%   |
| 5.10.7-3-MANJARO  | 60        | 0.78%   |
| 5.7.0-3-MANJARO   | 58        | 0.75%   |
| 5.8.3-2-MANJARO   | 57        | 0.74%   |
| 5.6.15-1-MANJARO  | 57        | 0.74%   |
| 5.12.9-1-MANJARO  | 54        | 0.7%    |
| 5.7.17-2-MANJARO  | 52        | 0.68%   |
| 5.15.78-1-MANJARO | 51        | 0.66%   |
| 5.15.41-1-MANJARO | 51        | 0.66%   |
| 5.14.10-1-MANJARO | 51        | 0.66%   |
| 5.9.1-1-MANJARO   | 50        | 0.65%   |
| 5.17.1-3-MANJARO  | 49        | 0.64%   |
| 5.10.23-1-MANJARO | 49        | 0.64%   |
| 5.16.14-1-MANJARO | 48        | 0.62%   |
| 5.15.74-3-MANJARO | 48        | 0.62%   |
| 5.15.7-1-MANJARO  | 48        | 0.62%   |
| 5.11.6-1-MANJARO  | 47        | 0.61%   |
| 5.15.85-1-MANJARO | 45        | 0.59%   |
| 5.15.25-1-MANJARO | 45        | 0.59%   |
| 5.10.34-1-MANJARO | 45        | 0.59%   |
| 5.6.12-1-MANJARO  | 44        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 294       | 3.83%   |
| 5.13.19 | 181       | 2.36%   |
| 5.8.6   | 140       | 1.82%   |
| 5.9.11  | 136       | 1.77%   |
| 5.8.11  | 123       | 1.6%    |
| 5.15.28 | 118       | 1.54%   |
| 5.10.42 | 102       | 1.33%   |
| 6.1.1   | 101       | 1.31%   |
| 5.8.18  | 101       | 1.31%   |
| 5.15.32 | 101       | 1.31%   |
| 6.1.12  | 86        | 1.12%   |
| 5.15.12 | 82        | 1.07%   |
| 5.8.16  | 74        | 0.96%   |
| 5.6.16  | 74        | 0.96%   |
| 5.15.60 | 74        | 0.96%   |
| 5.7.0   | 73        | 0.95%   |
| 5.9.1   | 69        | 0.9%    |
| 5.6.19  | 66        | 0.86%   |
| 5.10.2  | 65        | 0.85%   |
| 5.15.65 | 62        | 0.81%   |
| 5.10.7  | 62        | 0.81%   |
| 5.7.9   | 61        | 0.79%   |
| 5.17.1  | 61        | 0.79%   |
| 5.10.36 | 61        | 0.79%   |
| 5.8.3   | 58        | 0.75%   |
| 5.6.15  | 57        | 0.74%   |
| 5.12.9  | 54        | 0.7%    |
| 5.7.17  | 53        | 0.69%   |
| 5.15.78 | 51        | 0.66%   |
| 5.15.41 | 51        | 0.66%   |
| 5.14.10 | 51        | 0.66%   |
| 5.15.7  | 50        | 0.65%   |
| 5.15.74 | 49        | 0.64%   |
| 5.10.23 | 49        | 0.64%   |
| 5.16.14 | 48        | 0.62%   |
| 5.11.6  | 48        | 0.62%   |
| 5.6.12  | 46        | 0.6%    |
| 5.15.2  | 46        | 0.6%    |
| 5.15.85 | 45        | 0.59%   |
| 5.15.25 | 45        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1229      | 17.02%  |
| 5.10    | 915       | 12.67%  |
| 5.4     | 629       | 8.71%   |
| 5.9     | 590       | 8.17%   |
| 5.8     | 553       | 7.66%   |
| 6.1     | 400       | 5.54%   |
| 5.6     | 393       | 5.44%   |
| 5.13    | 358       | 4.96%   |
| 5.7     | 264       | 3.65%   |
| 4.19    | 198       | 2.74%   |
| 5.11    | 185       | 2.56%   |
| 5.16    | 175       | 2.42%   |
| 5.12    | 157       | 2.17%   |
| 5.14    | 152       | 2.1%    |
| 6.0     | 150       | 2.08%   |
| 5.17    | 142       | 1.97%   |
| 5.19    | 138       | 1.91%   |
| 5.18    | 130       | 1.8%    |
| 5.5     | 109       | 1.51%   |
| 5.3     | 92        | 1.27%   |
| 6.2     | 62        | 0.86%   |
| 4.14    | 60        | 0.83%   |
| 5.2     | 41        | 0.57%   |
| 5.0     | 30        | 0.42%   |
| 5.1     | 26        | 0.36%   |
| 4.20    | 14        | 0.19%   |
| 4.18    | 12        | 0.17%   |
| 6.3     | 4         | 0.06%   |
| 4.9     | 4         | 0.06%   |
| 4.16    | 4         | 0.06%   |
| 4.17    | 3         | 0.04%   |
| 4.7     | 2         | 0.03%   |
| 4.4     | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6455      | 99.95%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2398      | 35.84%  |
| XFCE                     | 1441      | 21.54%  |
| GNOME                    | 1400      | 20.93%  |
| KDE                      | 559       | 8.36%   |
| Unknown                  | 311       | 4.65%   |
| X-Cinnamon               | 173       | 2.59%   |
| i3                       | 128       | 1.91%   |
| MATE                     | 61        | 0.91%   |
| Cinnamon                 | 56        | 0.84%   |
| Deepin                   | 50        | 0.75%   |
| Budgie                   | 30        | 0.45%   |
| Awesome                  | 17        | 0.25%   |
| LXQt                     | 15        | 0.22%   |
| sway                     | 11        | 0.16%   |
| LXDE                     | 7         | 0.1%    |
| Bspwm                    | 5         | 0.07%   |
| i3-with-shmlog           | 4         | 0.06%   |
| GNOME Classic            | 3         | 0.04%   |
| DWM                      | 3         | 0.04%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| LeftWM                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Enlightenment            | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |
| Unity                    | 1         | 0.01%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.01%   |
| qtile                    | 1         | 0.01%   |
| openbox                  | 1         | 0.01%   |
| Hyprland                 | 1         | 0.01%   |
| herbstluftwm             | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5593      | 85.18%  |
| Wayland | 773       | 11.77%  |
| Unknown | 137       | 2.09%   |
| Tty     | 63        | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2702      | 40.74%  |
| SDDM    | 1680      | 25.33%  |
| LightDM | 1148      | 17.31%  |
| GDM     | 859       | 12.95%  |
| TDM     | 218       | 3.29%   |
| LXDM    | 10        | 0.15%   |
| GREETD  | 6         | 0.09%   |
| SLiM    | 3         | 0.05%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LYNDE   | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2718      | 41.49%  |
| de_DE   | 518       | 7.91%   |
| ru_RU   | 463       | 7.07%   |
| en_GB   | 438       | 6.69%   |
| Unknown | 415       | 6.33%   |
| pt_BR   | 266       | 4.06%   |
| fr_FR   | 176       | 2.69%   |
| es_ES   | 141       | 2.15%   |
| en_CA   | 141       | 2.15%   |
| it_IT   | 138       | 2.11%   |
| pl_PL   | 119       | 1.82%   |
| en_AU   | 83        | 1.27%   |
| en_IN   | 79        | 1.21%   |
| es_MX   | 57        | 0.87%   |
| zh_CN   | 50        | 0.76%   |
| de_AT   | 44        | 0.67%   |
| nl_NL   | 40        | 0.61%   |
| ru_UA   | 39        | 0.6%    |
| es_AR   | 32        | 0.49%   |
| en_IE   | 29        | 0.44%   |
| sv_SE   | 27        | 0.41%   |
| fi_FI   | 23        | 0.35%   |
| cs_CZ   | 22        | 0.34%   |
| C       | 22        | 0.34%   |
| pt_PT   | 21        | 0.32%   |
| es_CL   | 21        | 0.32%   |
| tr_TR   | 19        | 0.29%   |
| hu_HU   | 19        | 0.29%   |
| en_ZA   | 19        | 0.29%   |
| en_DK   | 19        | 0.29%   |
| de_CH   | 19        | 0.29%   |
| en_NZ   | 18        | 0.27%   |
| uk_UA   | 17        | 0.26%   |
| es_CO   | 16        | 0.24%   |
| en_PH   | 16        | 0.24%   |
| fr_CA   | 15        | 0.23%   |
| nl_BE   | 12        | 0.18%   |
| en_IL   | 12        | 0.18%   |
| da_DK   | 12        | 0.18%   |
| en_DE   | 11        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3625      | 55.12%  |
| EFI  | 2951      | 44.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5474      | 83.83%  |
| Btrfs    | 634       | 9.71%   |
| Overlay  | 138       | 2.11%   |
| Unknown  | 129       | 1.98%   |
| Xfs      | 78        | 1.19%   |
| Tmpfs    | 32        | 0.49%   |
| F2fs     | 26        | 0.4%    |
| Ext3     | 5         | 0.08%   |
| Zfs      | 4         | 0.06%   |
| Ext2     | 4         | 0.06%   |
| Reiserfs | 3         | 0.05%   |
| XXXX     | 1         | 0.02%   |
| XXXfs    | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3061      | 46.44%  |
| Unknown | 2948      | 44.72%  |
| MBR     | 583       | 8.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5735      | 87.44%  |
| Yes       | 824       | 12.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4444      | 67.62%  |
| Yes       | 2128      | 32.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1194      | 18.49%  |
| Lenovo              | 1037      | 16.06%  |
| Hewlett-Packard     | 829       | 12.84%  |
| Dell                | 695       | 10.76%  |
| Gigabyte Technology | 519       | 8.04%   |
| MSI                 | 502       | 7.77%   |
| Acer                | 324       | 5.02%   |
| ASRock              | 274       | 4.24%   |
| Apple               | 132       | 2.04%   |
| Intel               | 88        | 1.36%   |
| Samsung Electronics | 66        | 1.02%   |
| Toshiba             | 64        | 0.99%   |
| HUAWEI              | 62        | 0.96%   |
| Unknown             | 42        | 0.65%   |
| Timi                | 38        | 0.59%   |
| Fujitsu             | 35        | 0.54%   |
| Sony                | 31        | 0.48%   |
| Notebook            | 29        | 0.45%   |
| Google              | 28        | 0.43%   |
| Microsoft           | 20        | 0.31%   |
| Biostar             | 20        | 0.31%   |
| Pegatron            | 18        | 0.28%   |
| Medion              | 18        | 0.28%   |
| TUXEDO              | 17        | 0.26%   |
| Alienware           | 17        | 0.26%   |
| AZW                 | 16        | 0.25%   |
| Razer               | 15        | 0.23%   |
| Positivo            | 15        | 0.23%   |
| Huanan              | 13        | 0.2%    |
| Schenker            | 11        | 0.17%   |
| LG Electronics      | 11        | 0.17%   |
| Foxconn             | 11        | 0.17%   |
| Packard Bell        | 10        | 0.15%   |
| System76            | 9         | 0.14%   |
| HONOR               | 9         | 0.14%   |
| BESSTAR Tech        | 9         | 0.14%   |
| ZOTAC               | 7         | 0.11%   |
| TrekStor            | 7         | 0.11%   |
| Panasonic           | 7         | 0.11%   |
| ECS                 | 7         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 71        | 1.1%    |
| Unknown                             | 54        | 0.84%   |
| MSI MS-7C37                         | 27        | 0.42%   |
| Gigabyte B450M DS3H                 | 27        | 0.42%   |
| MSI MS-7C02                         | 24        | 0.37%   |
| HP Notebook                         | 22        | 0.34%   |
| ASUS TUF Gaming X570-PLUS           | 21        | 0.33%   |
| ASUS PRIME A320M-K                  | 19        | 0.29%   |
| MSI MS-7C91                         | 17        | 0.26%   |
| MSI MS-7B86                         | 17        | 0.26%   |
| ASRock B450M Pro4                   | 16        | 0.25%   |
| MSI MS-7B79                         | 15        | 0.23%   |
| ASUS ROG STRIX B450-F GAMING        | 14        | 0.22%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.2%    |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 13        | 0.2%    |
| Dell XPS 15 9500                    | 13        | 0.2%    |
| Dell XPS 13 9310                    | 13        | 0.2%    |
| MSI MS-7A38                         | 12        | 0.19%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 12        | 0.19%   |
| HP Pavilion Notebook                | 12        | 0.19%   |
| Gigabyte X570 AORUS ELITE           | 12        | 0.19%   |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.19%   |
| ASUS ROG STRIX B550-F GAMING        | 12        | 0.19%   |
| ASUS PRIME B450M-A                  | 12        | 0.19%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.17%   |
| Dell OptiPlex 9020                  | 11        | 0.17%   |
| Dell OptiPlex 7010                  | 11        | 0.17%   |
| ASUS PRIME B350-PLUS                | 11        | 0.17%   |
| MSI MS-7B89                         | 10        | 0.15%   |
| HP Pavilion dv7                     | 10        | 0.15%   |
| HP Laptop 15-bs0xx                  | 10        | 0.15%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.15%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.15%   |
| Gigabyte B450 AORUS M               | 10        | 0.15%   |
| Gigabyte 970A-DS3P                  | 10        | 0.15%   |
| ASUS ROG STRIX X570-E GAMING        | 10        | 0.15%   |
| MSI MS-7817                         | 9         | 0.14%   |
| MSI MS-7693                         | 9         | 0.14%   |
| HP Pavilion g6                      | 9         | 0.14%   |
| HP Pavilion 15                      | 9         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 434       | 6.72%   |
| Lenovo IdeaPad     | 250       | 3.87%   |
| Acer Aspire        | 202       | 3.13%   |
| Dell Inspiron      | 199       | 3.08%   |
| ASUS ROG           | 197       | 3.05%   |
| HP Pavilion        | 164       | 2.54%   |
| ASUS PRIME         | 160       | 2.48%   |
| Dell Latitude      | 143       | 2.21%   |
| Dell XPS           | 115       | 1.78%   |
| ASUS TUF           | 108       | 1.67%   |
| HP ProBook         | 98        | 1.52%   |
| HP Laptop          | 95        | 1.47%   |
| HP EliteBook       | 93        | 1.44%   |
| Dell OptiPlex      | 82        | 1.27%   |
| ASUS VivoBook      | 76        | 1.18%   |
| HP ENVY            | 71        | 1.1%    |
| ASUS All           | 71        | 1.1%    |
| Lenovo Legion      | 68        | 1.05%   |
| Dell Precision     | 65        | 1.01%   |
| Toshiba Satellite  | 55        | 0.85%   |
| Unknown            | 54        | 0.84%   |
| Lenovo Yoga        | 52        | 0.81%   |
| HP Compaq          | 50        | 0.77%   |
| Gigabyte X570      | 46        | 0.71%   |
| Gigabyte B450M     | 44        | 0.68%   |
| Dell Vostro        | 42        | 0.65%   |
| ASUS ZenBook       | 37        | 0.57%   |
| Acer Swift         | 36        | 0.56%   |
| Gigabyte B450      | 33        | 0.51%   |
| HP OMEN            | 30        | 0.46%   |
| Acer Nitro         | 30        | 0.46%   |
| MSI MS-7C37        | 27        | 0.42%   |
| Lenovo ThinkBook   | 26        | 0.4%    |
| ASRock B450M       | 26        | 0.4%    |
| MSI MS-7C02        | 24        | 0.37%   |
| Lenovo ThinkCentre | 24        | 0.37%   |
| Fujitsu LIFEBOOK   | 24        | 0.37%   |
| ASUS ASUS          | 24        | 0.37%   |
| Lenovo IdeaPadFlex | 22        | 0.34%   |
| HP Notebook        | 22        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 877       | 13.58%  |
| 2018    | 830       | 12.85%  |
| 2020    | 817       | 12.65%  |
| 2017    | 545       | 8.44%   |
| 2012    | 477       | 7.39%   |
| 2021    | 465       | 7.2%    |
| 2013    | 386       | 5.98%   |
| 2014    | 354       | 5.48%   |
| 2015    | 337       | 5.22%   |
| 2011    | 333       | 5.16%   |
| 2016    | 328       | 5.08%   |
| 2010    | 200       | 3.1%    |
| 2022    | 149       | 2.31%   |
| 2009    | 131       | 2.03%   |
| 2008    | 120       | 1.86%   |
| 2007    | 71        | 1.1%    |
| 2006    | 20        | 0.31%   |
| 2023    | 8         | 0.12%   |
| 2005    | 5         | 0.08%   |
| Unknown | 5         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3568      | 55.25%  |
| Desktop     | 2477      | 38.36%  |
| Convertible | 236       | 3.65%   |
| Mini pc     | 76        | 1.18%   |
| All in one  | 49        | 0.76%   |
| Tablet      | 43        | 0.67%   |
| Server      | 8         | 0.12%   |
| Phone       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6454      | 99.89%  |
| Enabled  | 7         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6412      | 99.29%  |
| Yes  | 46        | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1779      | 27.17%  |
| 4.01-8.0        | 1447      | 22.1%   |
| 8.01-16.0       | 1295      | 19.78%  |
| 32.01-64.0      | 821       | 12.54%  |
| 3.01-4.0        | 745       | 11.38%  |
| 64.01-256.0     | 174       | 2.66%   |
| 24.01-32.0      | 145       | 2.21%   |
| 1.01-2.0        | 106       | 1.62%   |
| 2.01-3.0        | 33        | 0.5%    |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 1860      | 25.82%  |
| 1.01-2.0        | 1742      | 24.18%  |
| 4.01-8.0        | 1579      | 21.92%  |
| 3.01-4.0        | 1225      | 17%     |
| 8.01-16.0       | 475       | 6.59%   |
| 0.51-1.0        | 213       | 2.96%   |
| 16.01-24.0      | 61        | 0.85%   |
| 0.01-0.5        | 19        | 0.26%   |
| 24.01-32.0      | 17        | 0.24%   |
| 32.01-64.0      | 11        | 0.15%   |
| More than 256.0 | 1         | 0.01%   |
| 64.01-256.0     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3370      | 50.59%  |
| 2      | 1904      | 28.58%  |
| 3      | 667       | 10.01%  |
| 4      | 355       | 5.33%   |
| 5      | 192       | 2.88%   |
| 6      | 72        | 1.08%   |
| 7      | 38        | 0.57%   |
| 0      | 31        | 0.47%   |
| 8      | 14        | 0.21%   |
| 9      | 9         | 0.14%   |
| 11     | 4         | 0.06%   |
| 10     | 3         | 0.05%   |
| 12     | 2         | 0.03%   |
| 20     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4702      | 72.14%  |
| Yes       | 1816      | 27.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5393      | 83.34%  |
| No        | 1078      | 16.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5094      | 78.42%  |
| No        | 1402      | 21.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4311      | 66.05%  |
| No        | 2216      | 33.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1097      | 16.87%  |
| Germany      | 759       | 11.67%  |
| Russia       | 583       | 8.97%   |
| Brazil       | 376       | 5.78%   |
| France       | 241       | 3.71%   |
| UK           | 233       | 3.58%   |
| Italy        | 211       | 3.25%   |
| Canada       | 207       | 3.18%   |
| Spain        | 192       | 2.95%   |
| Poland       | 190       | 2.92%   |
| Netherlands  | 147       | 2.26%   |
| Ukraine      | 146       | 2.25%   |
| India        | 124       | 1.91%   |
| Austria      | 93        | 1.43%   |
| Australia    | 93        | 1.43%   |
| Mexico       | 92        | 1.41%   |
| Sweden       | 88        | 1.35%   |
| China        | 68        | 1.05%   |
| Switzerland  | 63        | 0.97%   |
| Belgium      | 62        | 0.95%   |
| Turkey       | 59        | 0.91%   |
| Finland      | 59        | 0.91%   |
| Romania      | 58        | 0.89%   |
| Czechia      | 52        | 0.8%    |
| Portugal     | 51        | 0.78%   |
| Argentina    | 50        | 0.77%   |
| Indonesia    | 47        | 0.72%   |
| Hungary      | 47        | 0.72%   |
| Greece       | 46        | 0.71%   |
| Bulgaria     | 46        | 0.71%   |
| Norway       | 44        | 0.68%   |
| Belarus      | 41        | 0.63%   |
| Denmark      | 37        | 0.57%   |
| Colombia     | 29        | 0.45%   |
| Chile        | 29        | 0.45%   |
| Bangladesh   | 28        | 0.43%   |
| Taiwan       | 27        | 0.42%   |
| South Africa | 27        | 0.42%   |
| Israel       | 25        | 0.38%   |
| Japan        | 24        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 133       | 1.94%   |
| St Petersburg     | 78        | 1.14%   |
| Vienna            | 56        | 0.82%   |
| Berlin            | 52        | 0.76%   |
| Paris             | 46        | 0.67%   |
| Warsaw            | 43        | 0.63%   |
| Sao Paulo         | 42        | 0.61%   |
| Kyiv              | 42        | 0.61%   |
| Amsterdam         | 39        | 0.57%   |
| Toronto           | 32        | 0.47%   |
| Frankfurt am Main | 32        | 0.47%   |
| Milan             | 31        | 0.45%   |
| Madrid            | 30        | 0.44%   |
| Hamburg           | 30        | 0.44%   |
| Rome              | 28        | 0.41%   |
| Munich            | 27        | 0.39%   |
| Helsinki          | 27        | 0.39%   |
| Stockholm         | 26        | 0.38%   |
| Athens            | 25        | 0.36%   |
| Minsk             | 24        | 0.35%   |
| Melbourne         | 24        | 0.35%   |
| Istanbul          | 24        | 0.35%   |
| London            | 23        | 0.33%   |
| Bucharest         | 23        | 0.33%   |
| Barcelona         | 23        | 0.33%   |
| Sofia             | 22        | 0.32%   |
| Novosibirsk       | 22        | 0.32%   |
| Bengaluru         | 22        | 0.32%   |
| Krakow            | 21        | 0.31%   |
| Cologne           | 21        | 0.31%   |
| Sydney            | 20        | 0.29%   |
| Prague            | 20        | 0.29%   |
| Mexico City       | 20        | 0.29%   |
| Rio de Janeiro    | 19        | 0.28%   |
| Dhaka             | 19        | 0.28%   |
| Yekaterinburg     | 18        | 0.26%   |
| Montreal          | 18        | 0.26%   |
| Los Angeles       | 18        | 0.26%   |
| Krasnodar         | 18        | 0.26%   |
| Budapest          | 18        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1837      | 2826   | 17.25%  |
| WDC                         | 1521      | 2304   | 14.28%  |
| Seagate                     | 1452      | 2186   | 13.64%  |
| Toshiba                     | 684       | 837    | 6.42%   |
| SanDisk                     | 631       | 822    | 5.93%   |
| Kingston                    | 616       | 809    | 5.79%   |
| Crucial                     | 453       | 639    | 4.25%   |
| Unknown                     | 326       | 430    | 3.06%   |
| Intel                       | 302       | 399    | 2.84%   |
| SK hynix                    | 300       | 362    | 2.82%   |
| Hitachi                     | 224       | 299    | 2.1%    |
| HGST                        | 208       | 271    | 1.95%   |
| Micron Technology           | 160       | 201    | 1.5%    |
| A-DATA Technology           | 145       | 192    | 1.36%   |
| Phison                      | 130       | 179    | 1.22%   |
| China                       | 97        | 124    | 0.91%   |
| Apple                       | 78        | 96     | 0.73%   |
| KIOXIA                      | 74        | 88     | 0.69%   |
| Silicon Motion              | 73        | 100    | 0.69%   |
| Micron/Crucial Technology   | 62        | 76     | 0.58%   |
| Transcend                   | 56        | 62     | 0.53%   |
| PNY                         | 51        | 77     | 0.48%   |
| Phison Electronics          | 50        | 53     | 0.47%   |
| SPCC                        | 48        | 57     | 0.45%   |
| Patriot                     | 47        | 56     | 0.44%   |
| OCZ                         | 47        | 65     | 0.44%   |
| Intenso                     | 46        | 63     | 0.43%   |
| GOODRAM                     | 45        | 68     | 0.42%   |
| XPG                         | 43        | 54     | 0.4%    |
| JMicron Technology          | 42        | 50     | 0.39%   |
| Plextor                     | 36        | 48     | 0.34%   |
| Corsair                     | 35        | 46     | 0.33%   |
| LITEONIT                    | 33        | 42     | 0.31%   |
| LITEON                      | 31        | 34     | 0.29%   |
| Realtek Semiconductor       | 26        | 33     | 0.24%   |
| Kingston Technology Company | 26        | 27     | 0.24%   |
| Lexar                       | 23        | 25     | 0.22%   |
| Team                        | 21        | 27     | 0.2%    |
| Apacer                      | 21        | 23     | 0.2%    |
| Hewlett-Packard             | 20        | 28     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 130       | 1.09%   |
| Samsung SSD 860 EVO 500GB                          | 107       | 0.9%    |
| Seagate ST1000LM035-1RK172 970GB                   | 105       | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 94        | 0.79%   |
| Samsung SSD 850 EVO 500GB                          | 86        | 0.72%   |
| Samsung NVMe SSD Drive 512GB                       | 86        | 0.72%   |
| Samsung NVMe SSD Drive 500GB                       | 83        | 0.69%   |
| Samsung NVMe SSD Drive 1TB                         | 82        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                     | 78        | 0.65%   |
| Samsung SSD 850 EVO 250GB                          | 78        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                    | 78        | 0.65%   |
| Crucial CT500MX500SSD1 500GB                       | 75        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                     | 71        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 69        | 0.58%   |
| Samsung SSD 860 EVO 1TB                            | 65        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                    | 63        | 0.53%   |
| HGST HTS721010A9E630 1TB                           | 63        | 0.53%   |
| Toshiba MQ01ABD100 1TB                             | 61        | 0.51%   |
| Samsung NVMe SSD Drive 256GB                       | 61        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                        | 61        | 0.51%   |
| Samsung SSD 860 EVO 250GB                          | 58        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 56        | 0.47%   |
| Toshiba MQ04ABF100 1TB                             | 56        | 0.47%   |
| Toshiba DT01ACA100 1TB                             | 55        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                      | 55        | 0.46%   |
| Seagate Expansion 4TB                              | 54        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                       | 53        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                       | 52        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 48        | 0.4%    |
| Unknown SD/MMC/MS PRO 249GB                        | 46        | 0.39%   |
| Unknown MMC Card  64GB                             | 46        | 0.39%   |
| Toshiba MQ01ABF050 500GB                           | 46        | 0.39%   |
| SanDisk NVMe SSD Drive 500GB                       | 45        | 0.38%   |
| Intel NVMe SSD Drive 512GB                         | 44        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                    | 42        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                     | 42        | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                         | 42        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                     | 41        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                   | 39        | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 38        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1418      | 2121   | 36.52%  |
| WDC                 | 1211      | 1820   | 31.19%  |
| Toshiba             | 499       | 609    | 12.85%  |
| Hitachi             | 224       | 299    | 5.77%   |
| HGST                | 207       | 270    | 5.33%   |
| Samsung Electronics | 152       | 229    | 3.91%   |
| Unknown             | 52        | 64     | 1.34%   |
| JMicron Technology  | 22        | 27     | 0.57%   |
| Fujitsu             | 18        | 18     | 0.46%   |
| Apple               | 17        | 22     | 0.44%   |
| Maxtor              | 13        | 15     | 0.33%   |
| Intenso             | 8         | 12     | 0.21%   |
| USB3.0              | 7         | 7      | 0.18%   |
| ASMT                | 7         | 13     | 0.18%   |
| ASMedia             | 5         | 7      | 0.13%   |
| HGST HTS            | 3         | 3      | 0.08%   |
| Hewlett-Packard     | 3         | 3      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| Maxone              | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 2      | 0.05%   |
| SABRENT             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 3      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 897       | 1270   | 24.87%  |
| Kingston            | 496       | 644    | 13.75%  |
| Crucial             | 412       | 589    | 11.42%  |
| SanDisk             | 303       | 395    | 8.4%    |
| WDC                 | 223       | 296    | 6.18%   |
| A-DATA Technology   | 116       | 153    | 3.22%   |
| China               | 96        | 123    | 2.66%   |
| Intel               | 94        | 119    | 2.61%   |
| Micron Technology   | 68        | 85     | 1.89%   |
| SK hynix            | 58        | 68     | 1.61%   |
| Toshiba             | 54        | 68     | 1.5%    |
| Transcend           | 49        | 54     | 1.36%   |
| OCZ                 | 47        | 65     | 1.3%    |
| PNY                 | 45        | 71     | 1.25%   |
| Patriot             | 44        | 53     | 1.22%   |
| Apple               | 44        | 49     | 1.22%   |
| GOODRAM             | 43        | 66     | 1.19%   |
| SPCC                | 37        | 45     | 1.03%   |
| Plextor             | 33        | 45     | 0.91%   |
| LITEONIT            | 33        | 42     | 0.91%   |
| Intenso             | 30        | 41     | 0.83%   |
| LITEON              | 25        | 28     | 0.69%   |
| Corsair             | 24        | 33     | 0.67%   |
| Lexar               | 22        | 24     | 0.61%   |
| Apacer              | 20        | 22     | 0.55%   |
| Team                | 17        | 23     | 0.47%   |
| Seagate             | 16        | 23     | 0.44%   |
| KingSpec            | 15        | 17     | 0.42%   |
| Gigabyte Technology | 13        | 18     | 0.36%   |
| Netac               | 12        | 18     | 0.33%   |
| Leven               | 11        | 12     | 0.3%    |
| KingDian            | 11        | 11     | 0.3%    |
| TO Exter            | 9         | 11     | 0.25%   |
| Hewlett-Packard     | 9         | 13     | 0.25%   |
| ASMT                | 8         | 12     | 0.22%   |
| Unknown             | 8         | 11     | 0.22%   |
| Mushkin             | 7         | 8      | 0.19%   |
| NGFF                | 6         | 6      | 0.17%   |
| Hoodisk             | 6         | 6      | 0.17%   |
| External            | 6         | 8      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3148      | 5558   | 33.77%  |
| SSD     | 3050      | 4829   | 32.72%  |
| NVMe    | 2713      | 3915   | 29.1%   |
| MMC     | 253       | 326    | 2.71%   |
| Unknown | 158       | 203    | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4684      | 9959   | 57.86%  |
| NVMe | 2709      | 3890   | 33.47%  |
| SAS  | 449       | 656    | 5.55%   |
| MMC  | 253       | 326    | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3402      | 5598   | 51.23%  |
| 0.51-1.0   | 2129      | 3100   | 32.06%  |
| 1.01-2.0   | 605       | 877    | 9.11%   |
| 3.01-4.0   | 217       | 335    | 3.27%   |
| 4.01-10.0  | 140       | 241    | 2.11%   |
| 2.01-3.0   | 123       | 190    | 1.85%   |
| 10.01-20.0 | 25        | 46     | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1564      | 23.08%  |
| 251-500        | 1514      | 22.34%  |
| 501-1000       | 1077      | 15.89%  |
| 1001-2000      | 766       | 11.3%   |
| More than 3000 | 452       | 6.67%   |
| Unknown        | 391       | 5.77%   |
| 51-100         | 357       | 5.27%   |
| 2001-3000      | 298       | 4.4%    |
| 1-20           | 195       | 2.88%   |
| 21-50          | 163       | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1410      | 19.92%  |
| 21-50          | 1153      | 16.29%  |
| 101-250        | 1151      | 16.26%  |
| 51-100         | 961       | 13.58%  |
| 251-500        | 769       | 10.86%  |
| 501-1000       | 596       | 8.42%   |
| Unknown        | 391       | 5.52%   |
| 1001-2000      | 348       | 4.92%   |
| More than 3000 | 172       | 2.43%   |
| 2001-3000      | 123       | 1.74%   |
| 0              | 5         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 970GB                    | 11        | 12     | 2.02%   |
| HGST HTS545050A7E680 500GB                          | 10        | 10     | 1.83%   |
| HGST HTS721010A9E630 1TB                            | 9         | 9      | 1.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 8      | 1.47%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.28%   |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.28%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 1.1%    |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.1%    |
| Seagate ST500LT012-9WS142 500GB                     | 6         | 23     | 1.1%    |
| WDC WD5000AAKX-001CA0 500GB                         | 5         | 7      | 0.92%   |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 0.92%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 5         | 5      | 0.92%   |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 0.92%   |
| Hitachi HDS721010CLA332 1TB                         | 5         | 5      | 0.92%   |
| Crucial CT525MX300SSD1 528GB                        | 5         | 5      | 0.92%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 4      | 0.73%   |
| Seagate ST9500325AS 500GB                           | 4         | 5      | 0.73%   |
| Seagate ST9320325AS 320GB                           | 4         | 5      | 0.73%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.73%   |
| Seagate ST1000DX001-1CM162 1TB                      | 4         | 6      | 0.73%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.73%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 6      | 0.73%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 4      | 0.73%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 0.73%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.73%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.55%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.55%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.55%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.55%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.55%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 3         | 3      | 0.55%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.55%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.55%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 10     | 0.55%   |
| Seagate ST31000524AS 1TB                            | 3         | 5      | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.55%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.55%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 0.55%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 3      | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 3      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 208    | 26.55%  |
| WDC                 | 123       | 143    | 23.16%  |
| Samsung Electronics | 41        | 48     | 7.72%   |
| HGST                | 40        | 40     | 7.53%   |
| Hitachi             | 38        | 41     | 7.16%   |
| Toshiba             | 35        | 42     | 6.59%   |
| Crucial             | 16        | 19     | 3.01%   |
| SanDisk             | 15        | 18     | 2.82%   |
| Kingston            | 15        | 15     | 2.82%   |
| Intel               | 15        | 17     | 2.82%   |
| SK hynix            | 9         | 14     | 1.69%   |
| A-DATA Technology   | 7         | 8      | 1.32%   |
| Micron Technology   | 5         | 7      | 0.94%   |
| LITEON              | 3         | 3      | 0.56%   |
| Transcend           | 2         | 2      | 0.38%   |
| OCZ                 | 2         | 2      | 0.38%   |
| KingSpec            | 2         | 3      | 0.38%   |
| Corsair             | 2         | 6      | 0.38%   |
| ASMT                | 2         | 6      | 0.38%   |
| Apacer              | 2         | 2      | 0.38%   |
| TwinMOS             | 1         | 1      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| Realtek             | 1         | 1      | 0.19%   |
| Phison              | 1         | 2      | 0.19%   |
| Patriot             | 1         | 1      | 0.19%   |
| Maxtor              | 1         | 1      | 0.19%   |
| MaxDigital          | 1         | 1      | 0.19%   |
| LITEONIT            | 1         | 1      | 0.19%   |
| Intenso             | 1         | 4      | 0.19%   |
| IM3D                | 1         | 1      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| Fujitsu             | 1         | 1      | 0.19%   |
| Faspeed             | 1         | 1      | 0.19%   |
| Drevo               | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 140       | 205    | 35.62%  |
| WDC                 | 121       | 141    | 30.79%  |
| HGST                | 40        | 40     | 10.18%  |
| Hitachi             | 38        | 41     | 9.67%   |
| Toshiba             | 31        | 38     | 7.89%   |
| Samsung Electronics | 20        | 25     | 5.09%   |
| Maxtor              | 1         | 1      | 0.25%   |
| MaxDigital          | 1         | 1      | 0.25%   |
| Fujitsu             | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 373       | 493    | 73.43%  |
| SSD  | 112       | 145    | 22.05%  |
| NVMe | 23        | 26     | 4.53%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4141      | 9128   | 57.79%  |
| Works    | 2521      | 5023   | 35.18%  |
| Malfunc  | 489       | 664    | 6.82%   |
| Failed   | 15        | 16     | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3855      | 43.98%  |
| AMD                              | 1722      | 19.65%  |
| Samsung Electronics              | 1007      | 11.49%  |
| SanDisk                          | 464       | 5.29%   |
| SK hynix                         | 239       | 2.73%   |
| Phison Electronics               | 198       | 2.26%   |
| ASMedia Technology               | 161       | 1.84%   |
| Kingston Technology Company      | 148       | 1.69%   |
| Toshiba America Info Systems     | 125       | 1.43%   |
| Micron/Crucial Technology        | 104       | 1.19%   |
| Micron Technology                | 91        | 1.04%   |
| Silicon Motion                   | 90        | 1.03%   |
| KIOXIA                           | 86        | 0.98%   |
| Marvell Technology Group         | 75        | 0.86%   |
| ADATA Technology                 | 72        | 0.82%   |
| JMicron Technology               | 61        | 0.7%    |
| Nvidia                           | 59        | 0.67%   |
| Realtek Semiconductor            | 40        | 0.46%   |
| Union Memory (Shenzhen)          | 30        | 0.34%   |
| Solid State Storage Technology   | 18        | 0.21%   |
| Lite-On Technology               | 17        | 0.19%   |
| Apple                            | 17        | 0.19%   |
| Seagate Technology               | 12        | 0.14%   |
| Shenzhen Longsys Electronics     | 11        | 0.13%   |
| LSI Logic / Symbios Logic        | 9         | 0.1%    |
| VIA Technologies                 | 7         | 0.08%   |
| Silicon Image                    | 6         | 0.07%   |
| Lenovo                           | 6         | 0.07%   |
| Broadcom / LSI                   | 6         | 0.07%   |
| Yangtze Memory Technologies      | 4         | 0.05%   |
| Biwin Storage Technology         | 4         | 0.05%   |
| Adaptec                          | 4         | 0.05%   |
| Transcend                        | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.02%   |
| Promise Technology               | 1         | 0.01%   |
| PMC-Sierra                       | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1304      | 13.12%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 562       | 5.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 363       | 3.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 342       | 3.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 271       | 2.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 256       | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 235       | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 163       | 1.64%   |
| Samsung NVMe SSD Controller 980                                                | 161       | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 161       | 1.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 158       | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 154       | 1.55%   |
| AMD 500 Series Chipset SATA Controller                                         | 149       | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 143       | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 137       | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 135       | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 130       | 1.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 129       | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 127       | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 122       | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 113       | 1.14%   |
| Intel SSD 660P Series                                                          | 112       | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 108       | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 104       | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 104       | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 104       | 1.05%   |
| Phison E12 NVMe Controller                                                     | 94        | 0.95%   |
| Micron NVMe Storage Controller                                                 | 90        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 90        | 0.91%   |
| Intel SATA Controller [RAID mode]                                              | 89        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 87        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                         | 86        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 84        | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 73        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 71        | 0.71%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 70        | 0.7%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 69        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 65        | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 60        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 59        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4915      | 57.05%  |
| NVMe | 2719      | 31.56%  |
| IDE  | 484       | 5.62%   |
| RAID | 475       | 5.51%   |
| SAS  | 20        | 0.23%   |
| SCSI | 3         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4380      | 67.81%  |
| AMD    | 2078      | 32.17%  |
| ARM    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 130       | 2.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 93        | 1.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 78        | 1.2%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 77        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 75        | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 72        | 1.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 70        | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 69        | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 69        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 69        | 1.07%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 63        | 0.97%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 62        | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 61        | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 60        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 60        | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 53        | 0.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 47        | 0.73%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 47        | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 0.71%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 45        | 0.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 44        | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 43        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 40        | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 40        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 40        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 34        | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 33        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.51%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 33        | 0.51%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 33        | 0.51%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 33        | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 31        | 0.48%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 30        | 0.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.45%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 29        | 0.45%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 28        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1461      | 22.58%  |
| Intel Core i7           | 1374      | 21.23%  |
| AMD Ryzen 5             | 693       | 10.71%  |
| AMD Ryzen 7             | 559       | 8.64%   |
| Intel Core i3           | 394       | 6.09%   |
| Other                   | 328       | 5.07%   |
| Intel Celeron           | 208       | 3.21%   |
| AMD Ryzen 9             | 153       | 2.36%   |
| Intel Core 2 Duo        | 140       | 2.16%   |
| Intel Xeon              | 128       | 1.98%   |
| Intel Pentium           | 119       | 1.84%   |
| AMD FX                  | 111       | 1.72%   |
| AMD Ryzen 3             | 100       | 1.55%   |
| Intel Core i9           | 47        | 0.73%   |
| Intel Atom              | 47        | 0.73%   |
| AMD A10                 | 44        | 0.68%   |
| Intel Pentium Dual-Core | 42        | 0.65%   |
| AMD Ryzen 7 PRO         | 40        | 0.62%   |
| AMD A8                  | 40        | 0.62%   |
| AMD A4                  | 35        | 0.54%   |
| AMD A6                  | 30        | 0.46%   |
| AMD Ryzen Threadripper  | 29        | 0.45%   |
| Intel Core 2 Quad       | 28        | 0.43%   |
| AMD Phenom II X4        | 26        | 0.4%    |
| Intel Core 2            | 23        | 0.36%   |
| Intel Pentium Silver    | 22        | 0.34%   |
| AMD Athlon              | 21        | 0.32%   |
| AMD E1                  | 20        | 0.31%   |
| AMD E                   | 19        | 0.29%   |
| AMD Athlon II X2        | 19        | 0.29%   |
| AMD Ryzen 5 PRO         | 14        | 0.22%   |
| AMD Athlon 64 X2        | 12        | 0.19%   |
| AMD Phenom II X6        | 11        | 0.17%   |
| AMD E2                  | 10        | 0.15%   |
| Intel Pentium Gold      | 9         | 0.14%   |
| Intel Genuine           | 9         | 0.14%   |
| AMD Athlon X4           | 9         | 0.14%   |
| AMD Athlon II X4        | 9         | 0.14%   |
| Intel Pentium Dual      | 7         | 0.11%   |
| AMD Turion 64 X2 Mobile | 7         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2393      | 36.99%  |
| 2       | 2021      | 31.24%  |
| 6       | 982       | 15.18%  |
| 8       | 721       | 11.15%  |
| 12      | 129       | 1.99%   |
| 16      | 67        | 1.04%   |
| 3       | 47        | 0.73%   |
| 1       | 44        | 0.68%   |
| 10      | 27        | 0.42%   |
| 14      | 21        | 0.32%   |
| 24      | 7         | 0.11%   |
| 32      | 5         | 0.08%   |
| Unknown | 3         | 0.05%   |
| 20      | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 6435      | 99.64%  |
| 2      | 22        | 0.34%   |
| 4      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4899      | 75.75%  |
| 1       | 1565      | 24.2%   |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6362      | 98.41%  |
| Unknown        | 102       | 1.58%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3253      | 48.65%  |
| 0x306a9    | 211       | 3.16%   |
| 0x906ea    | 181       | 2.71%   |
| 0x306c3    | 164       | 2.45%   |
| 0x206a7    | 143       | 2.14%   |
| 0x08701021 | 133       | 1.99%   |
| 0x806ea    | 130       | 1.94%   |
| 0x806ec    | 126       | 1.88%   |
| 0x806c1    | 106       | 1.59%   |
| 0x0800820d | 101       | 1.51%   |
| 0x806e9    | 94        | 1.41%   |
| 0x906e9    | 87        | 1.3%    |
| 0x506e3    | 81        | 1.21%   |
| 0x406e3    | 81        | 1.21%   |
| 0x08701013 | 78        | 1.17%   |
| 0x40651    | 76        | 1.14%   |
| 0x08108102 | 70        | 1.05%   |
| 0x08600106 | 69        | 1.03%   |
| 0x1067a    | 66        | 0.99%   |
| 0x0a50000c | 66        | 0.99%   |
| 0x08108109 | 62        | 0.93%   |
| 0x306d4    | 60        | 0.9%    |
| 0x706e5    | 49        | 0.73%   |
| 0x06000852 | 48        | 0.72%   |
| 0xa0652    | 47        | 0.7%    |
| 0x08600104 | 46        | 0.69%   |
| 0x08600103 | 46        | 0.69%   |
| 0x806eb    | 45        | 0.67%   |
| 0x08608103 | 40        | 0.6%    |
| 0x20655    | 33        | 0.49%   |
| 0x08001138 | 32        | 0.48%   |
| 0x010000c8 | 27        | 0.4%    |
| 0x0810100b | 26        | 0.39%   |
| 0x906ed    | 24        | 0.36%   |
| 0x406c4    | 24        | 0.36%   |
| 0x0a201016 | 24        | 0.36%   |
| 0x306f2    | 23        | 0.34%   |
| 0x08600102 | 23        | 0.34%   |
| 0x06001119 | 23        | 0.34%   |
| 0x906a3    | 22        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1268      | 19.6%   |
| Zen 2            | 599       | 9.26%   |
| Haswell          | 561       | 8.67%   |
| IvyBridge        | 425       | 6.57%   |
| Zen+             | 417       | 6.44%   |
| SandyBridge      | 368       | 5.69%   |
| Skylake          | 340       | 5.25%   |
| Zen 3            | 273       | 4.22%   |
| Zen              | 208       | 3.21%   |
| Unknown          | 202       | 3.12%   |
| Penryn           | 189       | 2.92%   |
| TigerLake        | 182       | 2.81%   |
| Broadwell        | 166       | 2.57%   |
| CometLake        | 153       | 2.36%   |
| Piledriver       | 144       | 2.23%   |
| Westmere         | 126       | 1.95%   |
| Silvermont       | 116       | 1.79%   |
| Icelake          | 104       | 1.61%   |
| K10              | 88        | 1.36%   |
| Goldmont plus    | 78        | 1.21%   |
| Core             | 77        | 1.19%   |
| Excavator        | 67        | 1.04%   |
| Goldmont         | 46        | 0.71%   |
| Nehalem          | 43        | 0.66%   |
| Alderlake Hybrid | 38        | 0.59%   |
| Bobcat           | 32        | 0.49%   |
| Steamroller      | 31        | 0.48%   |
| Puma             | 24        | 0.37%   |
| Jaguar           | 24        | 0.37%   |
| K8 Hammer        | 23        | 0.36%   |
| Bulldozer        | 18        | 0.28%   |
| K10 Llano        | 14        | 0.22%   |
| Bonnell          | 13        | 0.2%    |
| NetBurst         | 6         | 0.09%   |
| K8 & K10 hybrid  | 5         | 0.08%   |
| Tremont          | 3         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3339      | 42.18%  |
| Nvidia                     | 2561      | 32.35%  |
| AMD                        | 2007      | 25.35%  |
| ASPEED Technology          | 5         | 0.06%   |
| ATI Technologies           | 3         | 0.04%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 255       | 3.15%   |
| AMD Renoir                                                                               | 252       | 3.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 238       | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 223       | 2.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 213       | 2.63%   |
| Intel UHD Graphics 620                                                                   | 208       | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 205       | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 172       | 2.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 166       | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 160       | 1.98%   |
| Intel HD Graphics 620                                                                    | 148       | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 132       | 1.63%   |
| Intel HD Graphics 5500                                                                   | 128       | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 127       | 1.57%   |
| Intel HD Graphics 630                                                                    | 118       | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 116       | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 100       | 1.23%   |
| Intel HD Graphics 530                                                                    | 94        | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 94        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 89        | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 89        | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 87        | 1.07%   |
| AMD Lucienne                                                                             | 79        | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 74        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 72        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 70        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 70        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 69        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 62        | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 61        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 53        | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 52        | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 51        | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47        | 0.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 45        | 0.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 45        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2107      | 32.38%  |
| 1 x AMD            | 1581      | 24.3%   |
| 1 x Nvidia         | 1319      | 20.27%  |
| Intel + Nvidia     | 1024      | 15.74%  |
| AMD + Nvidia       | 187       | 2.87%   |
| Intel + AMD        | 139       | 2.14%   |
| 2 x AMD            | 109       | 1.68%   |
| 2 x Nvidia         | 29        | 0.45%   |
| 1 x ASPEED         | 4         | 0.06%   |
| Other              | 3         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.02%   |
| 1 x Matrox         | 1         | 0.02%   |
| Intel + 2 x AMD    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4735      | 72.5%   |
| Proprietary | 1782      | 27.29%  |
| Unknown     | 14        | 0.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4103      | 62.21%  |
| 1.01-2.0   | 559       | 8.48%   |
| 0.01-0.5   | 427       | 6.47%   |
| 7.01-8.0   | 425       | 6.44%   |
| 3.01-4.0   | 385       | 5.84%   |
| 0.51-1.0   | 275       | 4.17%   |
| 5.01-6.0   | 236       | 3.58%   |
| 8.01-16.0  | 109       | 1.65%   |
| 2.01-3.0   | 60        | 0.91%   |
| 16.01-24.0 | 14        | 0.21%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 838       | 11.04%  |
| AU Optronics            | 776       | 10.22%  |
| LG Display              | 683       | 9%      |
| BOE                     | 681       | 8.97%   |
| Chimei Innolux          | 665       | 8.76%   |
| Goldstar                | 434       | 5.72%   |
| Dell                    | 406       | 5.35%   |
| Acer                    | 289       | 3.81%   |
| AOC                     | 230       | 3.03%   |
| Ancor Communications    | 218       | 2.87%   |
| BenQ                    | 217       | 2.86%   |
| Hewlett-Packard         | 200       | 2.63%   |
| Philips                 | 163       | 2.15%   |
| Sharp                   | 161       | 2.12%   |
| Lenovo                  | 120       | 1.58%   |
| Apple                   | 116       | 1.53%   |
| LG Electronics          | 105       | 1.38%   |
| PANDA                   | 96        | 1.26%   |
| ViewSonic               | 90        | 1.19%   |
| Chi Mei Optoelectronics | 80        | 1.05%   |
| ASUSTek Computer        | 77        | 1.01%   |
| Iiyama                  | 60        | 0.79%   |
| Unknown                 | 48        | 0.63%   |
| Sony                    | 41        | 0.54%   |
| InfoVision              | 41        | 0.54%   |
| Unknown                 | 36        | 0.47%   |
| Panasonic               | 26        | 0.34%   |
| CSO                     | 25        | 0.33%   |
| Vizio                   | 24        | 0.32%   |
| MSI                     | 24        | 0.32%   |
| Eizo                    | 24        | 0.32%   |
| NEC Computers           | 21        | 0.28%   |
| Fujitsu Siemens         | 21        | 0.28%   |
| Toshiba                 | 18        | 0.24%   |
| Sceptre Tech            | 18        | 0.24%   |
| TMX                     | 17        | 0.22%   |
| LGD                     | 17        | 0.22%   |
| AUS                     | 17        | 0.22%   |
| Gigabyte Technology     | 15        | 0.2%    |
| LG Philips              | 14        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 44        | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 42        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 38        | 0.48%   |
| Unknown                                                                  | 36        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 34        | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 28        | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 28        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 21        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 20        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 20        | 0.25%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 20        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 17        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 15        | 0.19%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 15        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 15        | 0.19%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.19%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 15        | 0.19%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.18%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch                 | 13        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 13        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.15%   |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.15%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                       | 12        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3455      | 47.89%  |
| 1366x768 (WXGA)    | 1063      | 14.73%  |
| 3840x2160 (4K)     | 485       | 6.72%   |
| 2560x1440 (QHD)    | 406       | 5.63%   |
| 1600x900 (HD+)     | 197       | 2.73%   |
| Unknown            | 188       | 2.61%   |
| 1920x1200 (WUXGA)  | 157       | 2.18%   |
| 1680x1050 (WSXGA+) | 157       | 2.18%   |
| 1280x1024 (SXGA)   | 137       | 1.9%    |
| 1440x900 (WXGA+)   | 130       | 1.8%    |
| 2560x1080          | 98        | 1.36%   |
| 3440x1440          | 96        | 1.33%   |
| 1280x800 (WXGA)    | 84        | 1.16%   |
| 3840x1080          | 79        | 1.09%   |
| 2560x1600          | 58        | 0.8%    |
| 1360x768           | 42        | 0.58%   |
| 2880x1800          | 40        | 0.55%   |
| 2160x1440          | 24        | 0.33%   |
| 3840x2400          | 22        | 0.3%    |
| 1920x540           | 17        | 0.24%   |
| 4480x1440          | 13        | 0.18%   |
| 3200x1800 (QHD+)   | 13        | 0.18%   |
| 3840x1600          | 12        | 0.17%   |
| 5760x1080          | 10        | 0.14%   |
| 5120x1440          | 10        | 0.14%   |
| 1280x720 (HD)      | 10        | 0.14%   |
| 1024x768 (XGA)     | 10        | 0.14%   |
| 3456x2160          | 9         | 0.12%   |
| 3200x2000          | 9         | 0.12%   |
| 1600x1200          | 9         | 0.12%   |
| 5760x2160          | 8         | 0.11%   |
| 2736x1824          | 8         | 0.11%   |
| 2256x1504          | 8         | 0.11%   |
| 3600x1080          | 7         | 0.1%    |
| 3286x1080          | 7         | 0.1%    |
| 1920x1280          | 7         | 0.1%    |
| 3840x1200          | 6         | 0.08%   |
| 3000x2000          | 6         | 0.08%   |
| 3520x1080          | 5         | 0.07%   |
| 3360x1080          | 5         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1880      | 25.23%  |
| 13      | 719       | 9.65%   |
| Unknown | 593       | 7.96%   |
| 14      | 585       | 7.85%   |
| 27      | 566       | 7.6%    |
| 24      | 561       | 7.53%   |
| 23      | 471       | 6.32%   |
| 21      | 390       | 5.23%   |
| 17      | 313       | 4.2%    |
| 31      | 168       | 2.25%   |
| 34      | 151       | 2.03%   |
| 19      | 149       | 2%      |
| 12      | 105       | 1.41%   |
| 22      | 104       | 1.4%    |
| 18      | 92        | 1.23%   |
| 20      | 78        | 1.05%   |
| 11      | 63        | 0.85%   |
| 16      | 54        | 0.72%   |
| 84      | 50        | 0.67%   |
| 32      | 34        | 0.46%   |
| 40      | 31        | 0.42%   |
| 72      | 28        | 0.38%   |
| 54      | 28        | 0.38%   |
| 25      | 26        | 0.35%   |
| 26      | 19        | 0.25%   |
| 28      | 18        | 0.24%   |
| 48      | 15        | 0.2%    |
| 37      | 15        | 0.2%    |
| 65      | 14        | 0.19%   |
| 49      | 13        | 0.17%   |
| 33      | 12        | 0.16%   |
| 29      | 10        | 0.13%   |
| 43      | 9         | 0.12%   |
| 52      | 8         | 0.11%   |
| 42      | 8         | 0.11%   |
| 36      | 8         | 0.11%   |
| 46      | 7         | 0.09%   |
| 35      | 7         | 0.09%   |
| 10      | 7         | 0.09%   |
| 39      | 6         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2869      | 39.37%  |
| 501-600     | 1450      | 19.9%   |
| 401-500     | 721       | 9.89%   |
| Unknown     | 593       | 8.14%   |
| 201-300     | 533       | 7.31%   |
| 351-400     | 395       | 5.42%   |
| 601-700     | 251       | 3.44%   |
| 701-800     | 204       | 2.8%    |
| 1001-1500   | 99        | 1.36%   |
| 1501-2000   | 88        | 1.21%   |
| 801-900     | 64        | 0.88%   |
| 901-1000    | 17        | 0.23%   |
| 101-200     | 3         | 0.04%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4965      | 74.76%  |
| 16/10   | 660       | 9.94%   |
| Unknown | 546       | 8.22%   |
| 21/9    | 173       | 2.61%   |
| 5/4     | 127       | 1.91%   |
| 3/2     | 89        | 1.34%   |
| 4/3     | 41        | 0.62%   |
| 32/9    | 21        | 0.32%   |
| 6/5     | 6         | 0.09%   |
| 0.62    | 3         | 0.05%   |
| 3.40    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.20    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.80    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1887      | 25.58%  |
| 201-250        | 1235      | 16.74%  |
| 81-90          | 1006      | 13.64%  |
| Unknown        | 593       | 8.04%   |
| 301-350        | 577       | 7.82%   |
| 351-500        | 393       | 5.33%   |
| 151-200        | 319       | 4.32%   |
| 71-80          | 303       | 4.11%   |
| 121-130        | 225       | 3.05%   |
| 251-300        | 191       | 2.59%   |
| More than 1000 | 162       | 2.2%    |
| 141-150        | 124       | 1.68%   |
| 501-1000       | 104       | 1.41%   |
| 61-70          | 89        | 1.21%   |
| 51-60          | 66        | 0.89%   |
| 131-140        | 39        | 0.53%   |
| 111-120        | 37        | 0.5%    |
| 91-100         | 18        | 0.24%   |
| 41-50          | 6         | 0.08%   |
| 1-40           | 4         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2086      | 29.15%  |
| 51-100        | 2081      | 29.08%  |
| 101-120       | 1605      | 22.43%  |
| Unknown       | 593       | 8.29%   |
| 161-240       | 462       | 6.46%   |
| More than 240 | 196       | 2.74%   |
| 1-50          | 133       | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5106      | 77.41%  |
| 2     | 1271      | 19.27%  |
| 3     | 150       | 2.27%   |
| 0     | 57        | 0.86%   |
| 4     | 12        | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3645      | 37.58%  |
| Intel                             | 3343      | 34.47%  |
| Qualcomm Atheros                  | 981       | 10.11%  |
| Broadcom                          | 402       | 4.14%   |
| Ralink Technology                 | 125       | 1.29%   |
| TP-Link                           | 123       | 1.27%   |
| MediaTek                          | 119       | 1.23%   |
| Broadcom Limited                  | 92        | 0.95%   |
| Ralink                            | 71        | 0.73%   |
| Marvell Technology Group          | 58        | 0.6%    |
| Microsoft                         | 50        | 0.52%   |
| Nvidia                            | 43        | 0.44%   |
| Xiaomi                            | 42        | 0.43%   |
| Samsung Electronics               | 40        | 0.41%   |
| ASIX Electronics                  | 37        | 0.38%   |
| Sierra Wireless                   | 32        | 0.33%   |
| Aquantia                          | 32        | 0.33%   |
| Qualcomm Atheros Communications   | 31        | 0.32%   |
| Huawei Technologies               | 29        | 0.3%    |
| ASUSTek Computer                  | 28        | 0.29%   |
| Lenovo                            | 26        | 0.27%   |
| NetGear                           | 23        | 0.24%   |
| DisplayLink                       | 22        | 0.23%   |
| Dell                              | 22        | 0.23%   |
| Qualcomm                          | 21        | 0.22%   |
| D-Link                            | 21        | 0.22%   |
| Linksys                           | 19        | 0.2%    |
| JMicron Technology                | 17        | 0.18%   |
| Hewlett-Packard                   | 15        | 0.15%   |
| Edimax Technology                 | 13        | 0.13%   |
| Ericsson Business Mobile Networks | 11        | 0.11%   |
| D-Link System                     | 10        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.09%   |
| Microchip Technology              | 9         | 0.09%   |
| Google                            | 9         | 0.09%   |
| Motorola PCS                      | 7         | 0.07%   |
| FIBOCOM                           | 7         | 0.07%   |
| Apple                             | 7         | 0.07%   |
| ZyXEL Communications              | 6         | 0.06%   |
| Mellanox Technologies             | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2559      | 22.46%  |
| Intel Wi-Fi 6 AX200                                               | 496       | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 349       | 3.06%   |
| Intel I211 Gigabit Network Connection                             | 279       | 2.45%   |
| Intel Wireless 8265 / 8275                                        | 228       | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 201       | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 191       | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 184       | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 173       | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 162       | 1.42%   |
| Intel Wireless 7265                                               | 162       | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 152       | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 138       | 1.21%   |
| Intel Wireless 7260                                               | 137       | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 134       | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 128       | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 124       | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 120       | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 110       | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 109       | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 106       | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 102       | 0.9%    |
| Intel Wireless 8260                                               | 102       | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 98        | 0.86%   |
| Intel Wireless 3165                                               | 95        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 92        | 0.81%   |
| Intel Wireless-AC 9260                                            | 91        | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 85        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 82        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 74        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 73        | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 63        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 61        | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 55        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 52        | 0.46%   |
| Intel Wireless 3160                                               | 48        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 48        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2611      | 48.41%  |
| Realtek Semiconductor                 | 934       | 17.32%  |
| Qualcomm Atheros                      | 766       | 14.2%   |
| Broadcom                              | 295       | 5.47%   |
| Ralink Technology                     | 125       | 2.32%   |
| TP-Link                               | 116       | 2.15%   |
| MediaTek                              | 106       | 1.97%   |
| Ralink                                | 71        | 1.32%   |
| Broadcom Limited                      | 68        | 1.26%   |
| Microsoft                             | 47        | 0.87%   |
| Qualcomm Atheros Communications       | 31        | 0.57%   |
| ASUSTek Computer                      | 26        | 0.48%   |
| Sierra Wireless                       | 24        | 0.45%   |
| NetGear                               | 23        | 0.43%   |
| D-Link                                | 21        | 0.39%   |
| Linksys                               | 18        | 0.33%   |
| Dell                                  | 16        | 0.3%    |
| Marvell Technology Group              | 14        | 0.26%   |
| Edimax Technology                     | 13        | 0.24%   |
| Qualcomm                              | 10        | 0.19%   |
| FIBOCOM                               | 7         | 0.13%   |
| D-Link System                         | 7         | 0.13%   |
| ZyXEL Communications                  | 6         | 0.11%   |
| Hewlett-Packard                       | 5         | 0.09%   |
| Belkin Components                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyDAS                                 | 3         | 0.06%   |
| Quectel Wireless Solutions            | 3         | 0.06%   |
| Mercucys                              | 3         | 0.06%   |
| IMC Networks                          | 3         | 0.06%   |
| Tenda                                 | 2         | 0.04%   |
| Samsung Electronics                   | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Xiaomi                                | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 496       | 9.12%   |
| Intel Wireless 8265 / 8275                                     | 228       | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 184       | 3.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 173       | 3.18%   |
| Intel Wireless 7265                                            | 162       | 2.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 152       | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 138       | 2.54%   |
| Intel Wireless 7260                                            | 137       | 2.52%   |
| Intel Wi-Fi 6 AX201                                            | 134       | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 128       | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 120       | 2.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 110       | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 109       | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 106       | 1.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 102       | 1.88%   |
| Intel Wireless 8260                                            | 102       | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 98        | 1.8%    |
| Intel Wireless 3165                                            | 95        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 92        | 1.69%   |
| Intel Wireless-AC 9260                                         | 91        | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 82        | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 74        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 73        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 63        | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 55        | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 52        | 0.96%   |
| Intel Wireless 3160                                            | 48        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 45        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 45        | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 44        | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 44        | 0.81%   |
| Realtek 802.11ac NIC                                           | 43        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 42        | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 41        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                | 41        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 41        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 41        | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 40        | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 37        | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 35        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3270      | 57.15%  |
| Intel                                  | 1546      | 27.02%  |
| Qualcomm Atheros                       | 298       | 5.21%   |
| Broadcom                               | 162       | 2.83%   |
| Marvell Technology Group               | 44        | 0.77%   |
| Nvidia                                 | 43        | 0.75%   |
| Xiaomi                                 | 40        | 0.7%    |
| ASIX Electronics                       | 37        | 0.65%   |
| Aquantia                               | 32        | 0.56%   |
| Broadcom Limited                       | 27        | 0.47%   |
| Lenovo                                 | 26        | 0.45%   |
| DisplayLink                            | 22        | 0.38%   |
| Samsung Electronics                    | 21        | 0.37%   |
| Huawei Technologies                    | 19        | 0.33%   |
| JMicron Technology                     | 17        | 0.3%    |
| MediaTek                               | 11        | 0.19%   |
| Qualcomm                               | 10        | 0.17%   |
| Google                                 | 9         | 0.16%   |
| Sierra Wireless                        | 8         | 0.14%   |
| TP-Link                                | 7         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.1%    |
| Mellanox Technologies                  | 6         | 0.1%    |
| Apple                                  | 6         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 5         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.07%   |
| OPPO Electronics                       | 4         | 0.07%   |
| Motorola PCS                           | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| Microsoft                              | 3         | 0.05%   |
| ICS Advent                             | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link System                          | 3         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Foxconn / Hon Hai                      | 2         | 0.03%   |
| Attansic Technology                    | 2         | 0.03%   |
| ASUSTek Computer                       | 2         | 0.03%   |
| VIA Technologies                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2559      | 43.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 349       | 5.96%   |
| Intel I211 Gigabit Network Connection                             | 279       | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 201       | 3.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 191       | 3.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 162       | 2.76%   |
| Intel Ethernet Connection (2) I219-V                              | 124       | 2.12%   |
| Intel Ethernet Controller I225-V                                  | 85        | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 61        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 48        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 45        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 40        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 35        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 33        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 32        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 32        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 31        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 29        | 0.49%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 25        | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 24        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 23        | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 21        | 0.36%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.36%   |
| Intel I210 Gigabit Network Connection                             | 20        | 0.34%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 20        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5380      | 50.89%  |
| WiFi     | 5094      | 48.19%  |
| Modem    | 86        | 0.81%   |
| Unknown  | 11        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3990      | 59.06%  |
| Ethernet | 2766      | 40.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3395      | 52.35%  |
| 1     | 2850      | 43.95%  |
| 3     | 153       | 2.36%   |
| 0     | 68        | 1.05%   |
| 4     | 9         | 0.14%   |
| 5     | 8         | 0.12%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5487      | 83.53%  |
| Yes  | 1082      | 16.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2224      | 50.81%  |
| Realtek Semiconductor           | 479       | 10.94%  |
| Cambridge Silicon Radio         | 334       | 7.63%   |
| Qualcomm Atheros Communications | 326       | 7.45%   |
| IMC Networks                    | 179       | 4.09%   |
| Broadcom                        | 152       | 3.47%   |
| Lite-On Technology              | 142       | 3.24%   |
| Apple                           | 114       | 2.6%    |
| ASUSTek Computer                | 105       | 2.4%    |
| Foxconn / Hon Hai               | 84        | 1.92%   |
| Realtek                         | 42        | 0.96%   |
| Ralink                          | 25        | 0.57%   |
| Dell                            | 24        | 0.55%   |
| Hewlett-Packard                 | 18        | 0.41%   |
| MediaTek                        | 16        | 0.37%   |
| Toshiba                         | 14        | 0.32%   |
| TP-Link                         | 13        | 0.3%    |
| Marvell Semiconductor           | 11        | 0.25%   |
| Foxconn International           | 9         | 0.21%   |
| Edimax Technology               | 8         | 0.18%   |
| Opticis                         | 7         | 0.16%   |
| Dynex                           | 7         | 0.16%   |
| Ralink Technology               | 6         | 0.14%   |
| HTC (High Tech Computer)        | 5         | 0.11%   |
| Belkin Components               | 5         | 0.11%   |
| Alps Electric                   | 5         | 0.11%   |
| SINO WEALTH                     | 4         | 0.09%   |
| Conwise Technology              | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| Integrated System Solution      | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 725       | 16.54%  |
| Intel AX200 Bluetooth                               | 468       | 10.68%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 340       | 7.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 334       | 7.62%   |
| Intel AX201 Bluetooth                               | 327       | 7.46%   |
| Realtek Bluetooth Radio                             | 307       | 7%      |
| Qualcomm Atheros  Bluetooth Device                  | 203       | 4.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 123       | 2.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 106       | 2.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 86        | 1.96%   |
| IMC Networks Bluetooth Radio                        | 71        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 62        | 1.41%   |
| Intel AX210 Bluetooth                               | 59        | 1.35%   |
| Apple Bluetooth Host Controller                     | 54        | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 48        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1%      |
| Lite-On Bluetooth Device                            | 44        | 1%      |
| IMC Networks Bluetooth Device                       | 43        | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 40        | 0.91%   |
| Apple Bluetooth USB Host Controller                 | 39        | 0.89%   |
| Intel Bluetooth Device                              | 38        | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 38        | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 37        | 0.84%   |
| Realtek 802.11ac WLAN Adapter                       | 35        | 0.8%    |
| IMC Networks Wireless_Device                        | 35        | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 0.8%    |
| Ralink RT3290 Bluetooth                             | 25        | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 22        | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 21        | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.36%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.36%   |
| ASUS Bluetooth Radio                                | 15        | 0.34%   |
| ASUS ASUS USB-BT500                                 | 15        | 0.34%   |
| MediaTek Wireless_Device                            | 14        | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 14        | 0.32%   |
| TP-Link UB500 Adapter                               | 13        | 0.3%    |
| Realtek RTL8723B Bluetooth                          | 13        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4270      | 44.12%  |
| AMD                                  | 2367      | 24.46%  |
| Nvidia                               | 1732      | 17.9%   |
| C-Media Electronics                  | 222       | 2.29%   |
| Logitech                             | 92        | 0.95%   |
| Creative Labs                        | 70        | 0.72%   |
| Kingston Technology                  | 59        | 0.61%   |
| JMTek                                | 52        | 0.54%   |
| Texas Instruments                    | 45        | 0.46%   |
| SteelSeries ApS                      | 38        | 0.39%   |
| Realtek Semiconductor                | 37        | 0.38%   |
| Focusrite-Novation                   | 36        | 0.37%   |
| Corsair                              | 36        | 0.37%   |
| Razer USA                            | 34        | 0.35%   |
| Generalplus Technology               | 33        | 0.34%   |
| Creative Technology                  | 33        | 0.34%   |
| Blue Microphones                     | 28        | 0.29%   |
| ASUSTek Computer                     | 27        | 0.28%   |
| Plantronics                          | 26        | 0.27%   |
| Lenovo                               | 26        | 0.27%   |
| GN Netcom                            | 26        | 0.27%   |
| BEHRINGER International              | 22        | 0.23%   |
| Sony                                 | 16        | 0.17%   |
| GYROCOM C&C                          | 16        | 0.17%   |
| Apple                                | 14        | 0.14%   |
| Sennheiser Communications            | 13        | 0.13%   |
| Samson Technologies                  | 12        | 0.12%   |
| M-Audio                              | 11        | 0.11%   |
| VIA Technologies                     | 10        | 0.1%    |
| RODE Microphones                     | 10        | 0.1%    |
| SAVITECH                             | 9         | 0.09%   |
| Turtle Beach                         | 8         | 0.08%   |
| Giga-Byte Technology                 | 8         | 0.08%   |
| Astro Gaming                         | 8         | 0.08%   |
| Yamaha                               | 7         | 0.07%   |
| XMOS                                 | 7         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.07%   |
| Dell                                 | 7         | 0.07%   |
| DCMT Technology                      | 7         | 0.07%   |
| Micro Star International             | 6         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 837       | 7.16%   |
| Intel Sunrise Point-LP HD Audio                                            | 534       | 4.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 431       | 3.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 418       | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 414       | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 331       | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 324       | 2.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 300       | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 295       | 2.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 266       | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 240       | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 198       | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 193       | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 189       | 1.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 182       | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 178       | 1.52%   |
| Intel 8 Series HD Audio Controller                                         | 170       | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 169       | 1.44%   |
| AMD FCH Azalia Controller                                                  | 159       | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 151       | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 150       | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 150       | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 146       | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 138       | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                              | 137       | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 136       | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 135       | 1.15%   |
| AMD Navi 10 HDMI Audio                                                     | 116       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 103       | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 103       | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 101       | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 101       | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 95        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 94        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 90        | 0.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 86        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 83        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 82        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 82        | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 81        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1030      | 22.66%  |
| SK hynix            | 684       | 15.05%  |
| Kingston            | 545       | 11.99%  |
| Micron Technology   | 466       | 10.25%  |
| Corsair             | 339       | 7.46%   |
| Unknown             | 305       | 6.71%   |
| Crucial             | 291       | 6.4%    |
| G.Skill             | 253       | 5.57%   |
| A-DATA Technology   | 107       | 2.35%   |
| Ramaxel Technology  | 71        | 1.56%   |
| Elpida              | 58        | 1.28%   |
| Team                | 50        | 1.1%    |
| Patriot             | 46        | 1.01%   |
| Nanya Technology    | 41        | 0.9%    |
| Unknown (ABCD)      | 31        | 0.68%   |
| GOODRAM             | 27        | 0.59%   |
| Smart               | 22        | 0.48%   |
| Transcend           | 18        | 0.4%    |
| Unknown             | 18        | 0.4%    |
| Apacer              | 10        | 0.22%   |
| AMD                 | 10        | 0.22%   |
| Silicon Power       | 7         | 0.15%   |
| Kllisre             | 7         | 0.15%   |
| ASint Technology    | 7         | 0.15%   |
| GeIL                | 5         | 0.11%   |
| Teikon              | 4         | 0.09%   |
| Qumo                | 4         | 0.09%   |
| PNY                 | 4         | 0.09%   |
| Goldkey             | 4         | 0.09%   |
| Atermiter           | 4         | 0.09%   |
| Smart Brazil        | 3         | 0.07%   |
| SHARETRONIC         | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Kingmax             | 3         | 0.07%   |
| CSX                 | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| Unknown (08C8)      | 2         | 0.04%   |
| TwinMOS             | 2         | 0.04%   |
| Timetec             | 2         | 0.04%   |
| Qimonda             | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 58        | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 57        | 1.17%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.92%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 42        | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 40        | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 32        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 25        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 20        | 0.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 20        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 19        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.37%   |
| Unknown                                                          | 18        | 0.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 17        | 0.35%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 17        | 0.35%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 17        | 0.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.33%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 16        | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2227      | 56.77%  |
| DDR3    | 1111      | 28.32%  |
| LPDDR4  | 162       | 4.13%   |
| LPDDR3  | 125       | 3.19%   |
| Unknown | 83        | 2.12%   |
| DDR2    | 74        | 1.89%   |
| SDRAM   | 72        | 1.84%   |
| DDR5    | 38        | 0.97%   |
| LPDDR5  | 14        | 0.36%   |
| DDR     | 14        | 0.36%   |
| DRAM    | 3         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2127      | 54.29%  |
| DIMM         | 1406      | 35.89%  |
| Row Of Chips | 349       | 8.91%   |
| Chip         | 20        | 0.51%   |
| Unknown      | 10        | 0.26%   |
| RIMM         | 3         | 0.08%   |
| FB-DIMM      | 3         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1898      | 44.61%  |
| 4096  | 1145      | 26.91%  |
| 16384 | 647       | 15.21%  |
| 2048  | 350       | 8.23%   |
| 32768 | 141       | 3.31%   |
| 1024  | 67        | 1.57%   |
| 512   | 5         | 0.12%   |
| 65536 | 1         | 0.02%   |
| 3072  | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 776       | 18.03%  |
| 2667    | 738       | 17.15%  |
| 3200    | 713       | 16.57%  |
| 2400    | 347       | 8.06%   |
| 2133    | 238       | 5.53%   |
| 1333    | 201       | 4.67%   |
| 3600    | 176       | 4.09%   |
| 1867    | 100       | 2.32%   |
| 1334    | 98        | 2.28%   |
| 3266    | 72        | 1.67%   |
| 4267    | 70        | 1.63%   |
| 3466    | 57        | 1.32%   |
| 800     | 57        | 1.32%   |
| 3400    | 52        | 1.21%   |
| 3000    | 52        | 1.21%   |
| 667     | 47        | 1.09%   |
| Unknown | 38        | 0.88%   |
| 4800    | 34        | 0.79%   |
| 3733    | 33        | 0.77%   |
| 1866    | 33        | 0.77%   |
| 3800    | 32        | 0.74%   |
| 1067    | 32        | 0.74%   |
| 3866    | 27        | 0.63%   |
| 4199    | 25        | 0.58%   |
| 2933    | 22        | 0.51%   |
| 1066    | 22        | 0.51%   |
| 4266    | 19        | 0.44%   |
| 2800    | 15        | 0.35%   |
| 2666    | 15        | 0.35%   |
| 6400    | 14        | 0.33%   |
| 2048    | 11        | 0.26%   |
| 1800    | 11        | 0.26%   |
| 3666    | 10        | 0.23%   |
| 975     | 9         | 0.21%   |
| 8400    | 7         | 0.16%   |
| 333     | 7         | 0.16%   |
| 3334    | 6         | 0.14%   |
| 2448    | 6         | 0.14%   |
| 3534    | 5         | 0.12%   |
| 5200    | 4         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 57        | 39.86%  |
| Brother Industries    | 24        | 16.78%  |
| Canon                 | 18        | 12.59%  |
| Seiko Epson           | 13        | 9.09%   |
| Samsung Electronics   | 9         | 6.29%   |
| Pantum                | 3         | 2.1%    |
| Apple                 | 3         | 2.1%    |
| Xerox                 | 2         | 1.4%    |
| Ricoh                 | 2         | 1.4%    |
| Prolific Technology   | 2         | 1.4%    |
| Dymo-CoStar           | 2         | 1.4%    |
| Xiaomi                | 1         | 0.7%    |
| STMicroelectronics    | 1         | 0.7%    |
| Sagem                 | 1         | 0.7%    |
| QinHeng Electronics   | 1         | 0.7%    |
| Oki Data              | 1         | 0.7%    |
| Lexmark International | 1         | 0.7%    |
| Kyocera               | 1         | 0.7%    |
| Graphtec America      | 1         | 0.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                                  | 4         | 2.78%   |
| HP LaserJet 1300                                          | 3         | 2.08%   |
| HP ENVY 4520 series                                       | 3         | 2.08%   |
| Apple Gamesir-T1s 2.0b                                    | 3         | 2.08%   |
| Xerox Phaser 3020                                         | 2         | 1.39%   |
| Seiko Epson L120 Series                                   | 2         | 1.39%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 1.39%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.39%   |
| HP Officejet 2620 series                                  | 2         | 1.39%   |
| HP DeskJet 4530 series                                    | 2         | 1.39%   |
| HP DeskJet 3630 series                                    | 2         | 1.39%   |
| HP DeskJet 2700 series                                    | 2         | 1.39%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 1.39%   |
| HP DeskJet 2130 series                                    | 2         | 1.39%   |
| HP Color LaserJet Pro M453-4                              | 2         | 1.39%   |
| Canon PIXMA MX340                                         | 2         | 1.39%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.39%   |
| Canon MG5700 series                                       | 2         | 1.39%   |
| Brother MFC-L2710DW series                                | 2         | 1.39%   |
| Brother HL-L2300D series                                  | 2         | 1.39%   |
| Brother HL-5370DW series                                  | 2         | 1.39%   |
| Brother DCP-7040                                          | 2         | 1.39%   |
| Xiaomi MiMouse 2                                          | 1         | 0.69%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.69%   |
| Seiko Epson XP-4100 Series                                | 1         | 0.69%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.69%   |
| Seiko Epson Printer                                       | 1         | 0.69%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.69%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.69%   |
| Seiko Epson L805 Series                                   | 1         | 0.69%   |
| Seiko Epson L4260 Series                                  | 1         | 0.69%   |
| Seiko Epson L365 Series                                   | 1         | 0.69%   |
| Seiko Epson L355 Series                                   | 1         | 0.69%   |
| Seiko Epson L3150 Series                                  | 1         | 0.69%   |
| Seiko Epson ET-4760 Series                                | 1         | 0.69%   |
| Seiko Epson ET-3850 Series                                | 1         | 0.69%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.69%   |
| Samsung ML-1865                                           | 1         | 0.69%   |
| Samsung ML-1660 Series                                    | 1         | 0.69%   |
| Samsung M2020 Series                                      | 1         | 0.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 20        | 64.52%  |
| Seiko Epson        | 5         | 16.13%  |
| Hewlett-Packard    | 2         | 6.45%   |
| Visioneer          | 1         | 3.23%   |
| Ultima Electronics | 1         | 3.23%   |
| Mustek Systems     | 1         | 3.23%   |
| AGFA-Gevaert NV    | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 16.13%  |
| Canon CanoScan LiDE 110                                                               | 5         | 16.13%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 6.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 6.45%   |
| Canon CanoScan LIDE 25                                                                | 2         | 6.45%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.23%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.23%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.23%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.23%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.23%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 3.23%   |
| HP ScanJet 3500c                                                                      | 1         | 3.23%   |
| HP ScanJet 3400cse                                                                    | 1         | 3.23%   |
| Canon CanoScan LiDE 90                                                                | 1         | 3.23%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.23%   |
| Canon CanoScan LiDE 210                                                               | 1         | 3.23%   |
| Canon CanoScan LiDE 200                                                               | 1         | 3.23%   |
| Canon CanoScan LiDE 120                                                               | 1         | 3.23%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 839       | 20.19%  |
| IMC Networks                           | 489       | 11.77%  |
| Microdia                               | 318       | 7.65%   |
| Realtek Semiconductor                  | 311       | 7.48%   |
| Logitech                               | 294       | 7.08%   |
| Quanta                                 | 215       | 5.17%   |
| Sunplus Innovation Technology          | 186       | 4.48%   |
| Acer                                   | 164       | 3.95%   |
| Bison Electronics                      | 151       | 3.63%   |
| Cheng Uei Precision Industry (Foxlink) | 144       | 3.47%   |
| Syntek                                 | 115       | 2.77%   |
| Lite-On Technology                     | 115       | 2.77%   |
| Apple                                  | 94        | 2.26%   |
| Suyin                                  | 90        | 2.17%   |
| Microsoft                              | 68        | 1.64%   |
| Silicon Motion                         | 57        | 1.37%   |
| Luxvisions Innotech Limited            | 53        | 1.28%   |
| Alcor Micro                            | 52        | 1.25%   |
| Samsung Electronics                    | 46        | 1.11%   |
| Z-Star Microelectronics                | 25        | 0.6%    |
| Ricoh                                  | 19        | 0.46%   |
| Sonix Technology                       | 15        | 0.36%   |
| Creative Technology                    | 15        | 0.36%   |
| Lenovo                                 | 14        | 0.34%   |
| GEMBIRD                                | 13        | 0.31%   |
| Importek                               | 12        | 0.29%   |
| Primax Electronics                     | 10        | 0.24%   |
| MacroSilicon                           | 10        | 0.24%   |
| Generalplus Technology                 | 10        | 0.24%   |
| LG Electronics                         | 9         | 0.22%   |
| ARC International                      | 9         | 0.22%   |
| SunplusIT                              | 8         | 0.19%   |
| KYE Systems (Mouse Systems)            | 8         | 0.19%   |
| Google                                 | 8         | 0.19%   |
| Genesys Logic                          | 8         | 0.19%   |
| DigiTech                               | 7         | 0.17%   |
| Cubeternet                             | 7         | 0.17%   |
| ALi                                    | 6         | 0.14%   |
| Valve Software                         | 5         | 0.12%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 213       | 5.09%   |
| IMC Networks Integrated Camera                      | 163       | 3.9%    |
| Microdia Integrated_Webcam_HD                       | 143       | 3.42%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 121       | 2.89%   |
| Realtek Integrated_Webcam_HD                        | 116       | 2.77%   |
| Chicony HD WebCam                                   | 95        | 2.27%   |
| Syntek Integrated Camera                            | 77        | 1.84%   |
| Logitech Webcam C270                                | 72        | 1.72%   |
| Acer Integrated Camera                              | 61        | 1.46%   |
| Sunplus Integrated_Webcam_HD                        | 54        | 1.29%   |
| Logitech HD Pro Webcam C920                         | 48        | 1.15%   |
| Samsung Galaxy series, misc. (MTP mode)             | 46        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 45        | 1.08%   |
| Bison Integrated Camera                             | 44        | 1.05%   |
| Lite-On Integrated Camera                           | 39        | 0.93%   |
| Chicony HP Wide Vision HD Camera                    | 36        | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 32        | 0.76%   |
| Chicony HP HD Camera                                | 31        | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 31        | 0.74%   |
| Quanta HD User Facing                               | 30        | 0.72%   |
| Bison HD Webcam                                     | 30        | 0.72%   |
| Chicony USB2.0 Camera                               | 27        | 0.65%   |
| Chicony HD User Facing                              | 27        | 0.65%   |
| Microsoft LifeCam HD-3000                           | 26        | 0.62%   |
| Lite-On HP HD Camera                                | 26        | 0.62%   |
| Chicony USB2.0 HD UVC WebCam                        | 25        | 0.6%    |
| Bison SunplusIT Integrated Camera                   | 25        | 0.6%    |
| Realtek USB Camera                                  | 24        | 0.57%   |
| Quanta HP Wide Vision HD Camera                     | 24        | 0.57%   |
| Quanta HD Webcam                                    | 24        | 0.57%   |
| Chicony EasyCamera                                  | 24        | 0.57%   |
| Acer Lenovo EasyCamera                              | 24        | 0.57%   |
| Microdia Integrated Webcam                          | 23        | 0.55%   |
| Logitech C922 Pro Stream Webcam                     | 23        | 0.55%   |
| Chicony Lenovo EasyCamera                           | 23        | 0.55%   |
| Chicony HP Truevision HD                            | 23        | 0.55%   |
| IMC Networks HD Camera                              | 22        | 0.53%   |
| Syntek Lenovo EasyCamera                            | 21        | 0.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.5%    |
| Apple FaceTime HD Camera (Built-in)                 | 21        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 270       | 31.43%  |
| Validity Sensors                   | 243       | 28.29%  |
| Shenzhen Goodix Technology         | 178       | 20.72%  |
| Elan Microelectronics              | 62        | 7.22%   |
| LighTuning Technology              | 34        | 3.96%   |
| Upek                               | 27        | 3.14%   |
| AuthenTec                          | 22        | 2.56%   |
| STMicroelectronics                 | 8         | 0.93%   |
| Samsung Electronics                | 6         | 0.7%    |
| Focal-systems.Corp                 | 4         | 0.47%   |
| DigitalPersona                     | 2         | 0.23%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.12%   |
| HOLTEK                             | 1         | 0.12%   |
| Futronic Technology                | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 84        | 9.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 65        | 7.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 65        | 7.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 5.82%   |
| Elan ELAN:Fingerprint                                                      | 39        | 4.54%   |
| Synaptics UWP WBDI                                                         | 37        | 4.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 3.96%   |
| Synaptics WBDI                                                             | 29        | 3.38%   |
| Shenzhen Goodix FingerPrint                                                | 29        | 3.38%   |
| Validity Sensors Synaptics WBDI                                            | 28        | 3.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 3.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.79%   |
| Synaptics  WBDI                                                            | 23        | 2.68%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 23        | 2.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 22        | 2.56%   |
| Elan ELAN:ARM-M4                                                           | 19        | 2.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 1.98%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.98%   |
| Validity Sensors VFS491                                                    | 15        | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 14        | 1.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.51%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.4%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.05%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.81%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.81%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.58%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.58%   |
| Synaptics WBDI Device                                                      | 5         | 0.58%   |
| AuthenTec AES2810                                                          | 5         | 0.58%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.47%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 4         | 0.47%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 0.47%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 93        | 34.96%  |
| Broadcom                          | 89        | 33.46%  |
| Upek                              | 16        | 6.02%   |
| O2 Micro                          | 16        | 6.02%   |
| Lenovo                            | 16        | 6.02%   |
| Yubico.com                        | 8         | 3.01%   |
| Gemalto (was Gemplus)             | 8         | 3.01%   |
| VASCO Data Security International | 4         | 1.5%    |
| Realtek Semiconductor             | 4         | 1.5%    |
| OmniKey                           | 3         | 1.13%   |
| SCM Microsystems                  | 1         | 0.38%   |
| Reiner SCT Kartensysteme          | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Clay Logic                        | 1         | 0.38%   |
| Cherry                            | 1         | 0.38%   |
| C3PO                              | 1         | 0.38%   |
| Bit4id                            | 1         | 0.38%   |
| Aladdin Knowledge Systems         | 1         | 0.38%   |
| Advanced Card Systems             | 1         | 0.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 92        | 34.59%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 13.16%  |
| Broadcom 5880                                                                | 25        | 9.4%    |
| Broadcom 58200                                                               | 17        | 6.39%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 6.02%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.02%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 5.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.51%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.63%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.88%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.5%    |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 1.13%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.75%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 0.38%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.38%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.38%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.38%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.38%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.38%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.38%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.38%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.38%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.38%   |
| Bit4id miniLector EVO                                                        | 1         | 0.38%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.38%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.38%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4570      | 69.38%  |
| 1     | 1646      | 24.99%  |
| 2     | 340       | 5.16%   |
| 3     | 28        | 0.43%   |
| 4     | 3         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 843       | 35.99%  |
| Graphics card            | 409       | 17.46%  |
| Net/wireless             | 305       | 13.02%  |
| Chipcard                 | 233       | 9.95%   |
| Multimedia controller    | 185       | 7.9%    |
| Camera                   | 83        | 3.54%   |
| Net/ethernet             | 61        | 2.6%    |
| Unassigned class         | 54        | 2.31%   |
| Bluetooth                | 46        | 1.96%   |
| Sound                    | 26        | 1.11%   |
| Communication controller | 23        | 0.98%   |
| Storage                  | 21        | 0.9%    |
| Card reader              | 16        | 0.68%   |
| Dvb card                 | 12        | 0.51%   |
| Network                  | 8         | 0.34%   |
| Storage/raid             | 6         | 0.26%   |
| Modem                    | 4         | 0.17%   |
| Video                    | 2         | 0.09%   |
| Storage/nvme             | 2         | 0.09%   |
| Storage/ide              | 2         | 0.09%   |
| Storage/ata              | 1         | 0.04%   |


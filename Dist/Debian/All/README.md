Debian - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Debian.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian/Desktop/README.md) and [notebooks](/Dist/Debian/Notebook/README.md).

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

Total: 18033

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [26647a45b1](https://linux-hardware.org/?probe=26647a45b1) | Jan 02, 2024 |
| Lenovo        | G505 20240                  | Notebook    | [ff10a3ab7d](https://linux-hardware.org/?probe=ff10a3ab7d) | Jan 02, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [d87da5bee4](https://linux-hardware.org/?probe=d87da5bee4) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [5570fbf22f](https://linux-hardware.org/?probe=5570fbf22f) | Jan 02, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [d290e010eb](https://linux-hardware.org/?probe=d290e010eb) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [197c876252](https://linux-hardware.org/?probe=197c876252) | Jan 02, 2024 |
| HP            | Pavilion 15                 | Notebook    | [277c4aa7d6](https://linux-hardware.org/?probe=277c4aa7d6) | Jan 02, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [48afb483d6](https://linux-hardware.org/?probe=48afb483d6) | Jan 02, 2024 |
| TUXEDO        | N8xxEZ                      | Notebook    | [4eb785f281](https://linux-hardware.org/?probe=4eb785f281) | Jan 01, 2024 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [757bac1cef](https://linux-hardware.org/?probe=757bac1cef) | Jan 01, 2024 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [769eb69c0e](https://linux-hardware.org/?probe=769eb69c0e) | Jan 01, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [5f34a26ab3](https://linux-hardware.org/?probe=5f34a26ab3) | Jan 01, 2024 |
| Supermicro    | X10SRi-FB                   | Server      | [f4d124acc9](https://linux-hardware.org/?probe=f4d124acc9) | Jan 01, 2024 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [7271f244c2](https://linux-hardware.org/?probe=7271f244c2) | Jan 01, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [dea2dc38e4](https://linux-hardware.org/?probe=dea2dc38e4) | Jan 01, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2f74327d87](https://linux-hardware.org/?probe=2f74327d87) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [29ab65f09e](https://linux-hardware.org/?probe=29ab65f09e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [3afdb557c8](https://linux-hardware.org/?probe=3afdb557c8) | Jan 01, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [0bf596656b](https://linux-hardware.org/?probe=0bf596656b) | Jan 01, 2024 |
| Dell          | Vostro 3405                 | Notebook    | [78db308528](https://linux-hardware.org/?probe=78db308528) | Jan 01, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4434600249](https://linux-hardware.org/?probe=4434600249) | Jan 01, 2024 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [23f3ddf830](https://linux-hardware.org/?probe=23f3ddf830) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [ca2b52b64f](https://linux-hardware.org/?probe=ca2b52b64f) | Dec 31, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [edf3eae913](https://linux-hardware.org/?probe=edf3eae913) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [70bbf55180](https://linux-hardware.org/?probe=70bbf55180) | Dec 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [b67462ae25](https://linux-hardware.org/?probe=b67462ae25) | Dec 31, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [eb264efa92](https://linux-hardware.org/?probe=eb264efa92) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [70c84eadc0](https://linux-hardware.org/?probe=70c84eadc0) | Dec 31, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5f1c662ba4](https://linux-hardware.org/?probe=5f1c662ba4) | Dec 31, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [fde784b0b5](https://linux-hardware.org/?probe=fde784b0b5) | Dec 31, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [8fb51545f7](https://linux-hardware.org/?probe=8fb51545f7) | Dec 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [b5bf7051ef](https://linux-hardware.org/?probe=b5bf7051ef) | Dec 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [49a4d9cad0](https://linux-hardware.org/?probe=49a4d9cad0) | Dec 31, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [942c025f11](https://linux-hardware.org/?probe=942c025f11) | Dec 31, 2023 |
| ASUSTek       | P11C-I Series               | Desktop     | [b38bcf215d](https://linux-hardware.org/?probe=b38bcf215d) | Dec 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [4f95b9d510](https://linux-hardware.org/?probe=4f95b9d510) | Dec 30, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2b7e4fe145](https://linux-hardware.org/?probe=2b7e4fe145) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [f96a0610cb](https://linux-hardware.org/?probe=f96a0610cb) | Dec 30, 2023 |
| ASRockRack    | E3C256D4U-2L2T              | Server      | [b599abfcfe](https://linux-hardware.org/?probe=b599abfcfe) | Dec 30, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [90b5ba3d1e](https://linux-hardware.org/?probe=90b5ba3d1e) | Dec 30, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [0b8c1c9e17](https://linux-hardware.org/?probe=0b8c1c9e17) | Dec 30, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [7cd1d9d16c](https://linux-hardware.org/?probe=7cd1d9d16c) | Dec 30, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [ca0a0fe5cf](https://linux-hardware.org/?probe=ca0a0fe5cf) | Dec 30, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5fa6e9f755](https://linux-hardware.org/?probe=5fa6e9f755) | Dec 30, 2023 |
| Dell          | 0C4Y3R A00                  | Server      | [c49d0c3239](https://linux-hardware.org/?probe=c49d0c3239) | Dec 30, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [92615e0827](https://linux-hardware.org/?probe=92615e0827) | Dec 30, 2023 |
| HP            | Pavilion 17                 | Notebook    | [d6e11fbd64](https://linux-hardware.org/?probe=d6e11fbd64) | Dec 30, 2023 |
| ASUSTek       | X751LJ                      | Notebook    | [0ebf64067f](https://linux-hardware.org/?probe=0ebf64067f) | Dec 30, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [c6751f4e51](https://linux-hardware.org/?probe=c6751f4e51) | Dec 30, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [8340ced087](https://linux-hardware.org/?probe=8340ced087) | Dec 30, 2023 |
| HP            | 1495                        | Desktop     | [48d0ae2bf5](https://linux-hardware.org/?probe=48d0ae2bf5) | Dec 30, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [b95cb4b883](https://linux-hardware.org/?probe=b95cb4b883) | Dec 30, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [80604ec459](https://linux-hardware.org/?probe=80604ec459) | Dec 30, 2023 |
| Apple         | Mac-F4208AC8 PVT            | Desktop     | [11a7c2b836](https://linux-hardware.org/?probe=11a7c2b836) | Dec 30, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [c10327a38f](https://linux-hardware.org/?probe=c10327a38f) | Dec 29, 2023 |
| HC Technol... | HCAR5000-MI2                | Desktop     | [44a9ba60e7](https://linux-hardware.org/?probe=44a9ba60e7) | Dec 29, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [01aeb12545](https://linux-hardware.org/?probe=01aeb12545) | Dec 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [afd9883450](https://linux-hardware.org/?probe=afd9883450) | Dec 29, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [604c05059a](https://linux-hardware.org/?probe=604c05059a) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [d11d965739](https://linux-hardware.org/?probe=d11d965739) | Dec 29, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [80ed6c8614](https://linux-hardware.org/?probe=80ed6c8614) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [c7383a1237](https://linux-hardware.org/?probe=c7383a1237) | Dec 29, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [30f06f373e](https://linux-hardware.org/?probe=30f06f373e) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [cc8196ebec](https://linux-hardware.org/?probe=cc8196ebec) | Dec 29, 2023 |
| Toshiba       | Satellite C50D-A-138        | Notebook    | [cfb74314e2](https://linux-hardware.org/?probe=cfb74314e2) | Dec 29, 2023 |
| Lenovo        | 1038                        | Server      | [99f96df8da](https://linux-hardware.org/?probe=99f96df8da) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | Notebook    | [50589e94ba](https://linux-hardware.org/?probe=50589e94ba) | Dec 29, 2023 |
| ASUSTek       | K53BE                       | Notebook    | [23efadbf2f](https://linux-hardware.org/?probe=23efadbf2f) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | Notebook    | [71ef8433cc](https://linux-hardware.org/?probe=71ef8433cc) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [791788fbbc](https://linux-hardware.org/?probe=791788fbbc) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [4861953728](https://linux-hardware.org/?probe=4861953728) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [650d02f634](https://linux-hardware.org/?probe=650d02f634) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [0a2d1d5688](https://linux-hardware.org/?probe=0a2d1d5688) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [3d0513bb6c](https://linux-hardware.org/?probe=3d0513bb6c) | Dec 29, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [690962312c](https://linux-hardware.org/?probe=690962312c) | Dec 29, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [aa3f2ed203](https://linux-hardware.org/?probe=aa3f2ed203) | Dec 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c5bc64bc85](https://linux-hardware.org/?probe=c5bc64bc85) | Dec 29, 2023 |
| Lenovo        | 3000 N500 42333GS           | Notebook    | [523a81b813](https://linux-hardware.org/?probe=523a81b813) | Dec 29, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e648f1abef](https://linux-hardware.org/?probe=e648f1abef) | Dec 29, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [529b92f758](https://linux-hardware.org/?probe=529b92f758) | Dec 28, 2023 |
| COIN COMPU... | LUM580                      | Notebook    | [6a8246b500](https://linux-hardware.org/?probe=6a8246b500) | Dec 28, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [bbcdf32afc](https://linux-hardware.org/?probe=bbcdf32afc) | Dec 28, 2023 |
| Dell          | 054KM3 A01                  | Desktop     | [1d078128fe](https://linux-hardware.org/?probe=1d078128fe) | Dec 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e91f6abee5](https://linux-hardware.org/?probe=e91f6abee5) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [76b6ceb6cf](https://linux-hardware.org/?probe=76b6ceb6cf) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [32b6e45042](https://linux-hardware.org/?probe=32b6e45042) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [5d86cb3268](https://linux-hardware.org/?probe=5d86cb3268) | Dec 28, 2023 |
| MACHINIST     | X99 RS9                     | Desktop     | [1e431dc2fc](https://linux-hardware.org/?probe=1e431dc2fc) | Dec 28, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [cb13028da5](https://linux-hardware.org/?probe=cb13028da5) | Dec 28, 2023 |
| AZW           | SER V1                      | Desktop     | [9491b3dfb6](https://linux-hardware.org/?probe=9491b3dfb6) | Dec 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [96266413d3](https://linux-hardware.org/?probe=96266413d3) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS0N200    | Notebook    | [e94a7fb094](https://linux-hardware.org/?probe=e94a7fb094) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AV0031FR    | Notebook    | [96e1e4403d](https://linux-hardware.org/?probe=96e1e4403d) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [98b0838eb2](https://linux-hardware.org/?probe=98b0838eb2) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | Notebook    | [4eb0a16723](https://linux-hardware.org/?probe=4eb0a16723) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0J60... | Notebook    | [0f46c7112d](https://linux-hardware.org/?probe=0f46c7112d) | Dec 28, 2023 |
| MSI           | PRO A620M-E                 | Desktop     | [b2e410ff06](https://linux-hardware.org/?probe=b2e410ff06) | Dec 28, 2023 |
| Google        | Lillipup                    | Notebook    | [e8ac3dc206](https://linux-hardware.org/?probe=e8ac3dc206) | Dec 28, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [7345f4357e](https://linux-hardware.org/?probe=7345f4357e) | Dec 28, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [de1329753d](https://linux-hardware.org/?probe=de1329753d) | Dec 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [de88e1d09c](https://linux-hardware.org/?probe=de88e1d09c) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [37fe922c9d](https://linux-hardware.org/?probe=37fe922c9d) | Dec 28, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [4118aee355](https://linux-hardware.org/?probe=4118aee355) | Dec 28, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [2a36715319](https://linux-hardware.org/?probe=2a36715319) | Dec 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [1948c445d8](https://linux-hardware.org/?probe=1948c445d8) | Dec 27, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [f1144c99b2](https://linux-hardware.org/?probe=f1144c99b2) | Dec 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [40c72fd8c2](https://linux-hardware.org/?probe=40c72fd8c2) | Dec 27, 2023 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [08d900cdbb](https://linux-hardware.org/?probe=08d900cdbb) | Dec 27, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [758aa4d9a1](https://linux-hardware.org/?probe=758aa4d9a1) | Dec 27, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [175d9f4391](https://linux-hardware.org/?probe=175d9f4391) | Dec 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7b5e390f00](https://linux-hardware.org/?probe=7b5e390f00) | Dec 27, 2023 |
| Biostar       | A68N-5000                   | Desktop     | [19f4961efd](https://linux-hardware.org/?probe=19f4961efd) | Dec 27, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [5ef2e29839](https://linux-hardware.org/?probe=5ef2e29839) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6d222bdbcb](https://linux-hardware.org/?probe=6d222bdbcb) | Dec 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [fde01139b9](https://linux-hardware.org/?probe=fde01139b9) | Dec 27, 2023 |
| Lenovo        | ThinkPad L530 2475A61       | Notebook    | [990d8dce86](https://linux-hardware.org/?probe=990d8dce86) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e623c937a6](https://linux-hardware.org/?probe=e623c937a6) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [f6c6dba166](https://linux-hardware.org/?probe=f6c6dba166) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [705f4fa6fd](https://linux-hardware.org/?probe=705f4fa6fd) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9435700f28](https://linux-hardware.org/?probe=9435700f28) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [06264d7b71](https://linux-hardware.org/?probe=06264d7b71) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [09c41915d8](https://linux-hardware.org/?probe=09c41915d8) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [a89881fc3b](https://linux-hardware.org/?probe=a89881fc3b) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [b18f714a89](https://linux-hardware.org/?probe=b18f714a89) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [2424999ad8](https://linux-hardware.org/?probe=2424999ad8) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [1126414dff](https://linux-hardware.org/?probe=1126414dff) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [2ddc54287d](https://linux-hardware.org/?probe=2ddc54287d) | Dec 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [a5ce676225](https://linux-hardware.org/?probe=a5ce676225) | Dec 27, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [69dbcf46c7](https://linux-hardware.org/?probe=69dbcf46c7) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4290B52       | Notebook    | [f4ec8bd5f1](https://linux-hardware.org/?probe=f4ec8bd5f1) | Dec 27, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d73ec66a3a](https://linux-hardware.org/?probe=d73ec66a3a) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | Notebook    | [5a76629311](https://linux-hardware.org/?probe=5a76629311) | Dec 26, 2023 |
| Biostar       | A68N-5000                   | Desktop     | [39703ac1bc](https://linux-hardware.org/?probe=39703ac1bc) | Dec 26, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [1e952ed878](https://linux-hardware.org/?probe=1e952ed878) | Dec 26, 2023 |
| Rockchip      | RK3318 BOX                  | Soc         | [9dc03fd3b7](https://linux-hardware.org/?probe=9dc03fd3b7) | Dec 26, 2023 |
| Schenker      | N13xWU                      | Notebook    | [c94ab912c7](https://linux-hardware.org/?probe=c94ab912c7) | Dec 26, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [9227fed37d](https://linux-hardware.org/?probe=9227fed37d) | Dec 26, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [a58934ade1](https://linux-hardware.org/?probe=a58934ade1) | Dec 26, 2023 |
| Schenker      | N13xWU                      | Notebook    | [b2ff4375a0](https://linux-hardware.org/?probe=b2ff4375a0) | Dec 26, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [8616b021c1](https://linux-hardware.org/?probe=8616b021c1) | Dec 26, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [81860bf790](https://linux-hardware.org/?probe=81860bf790) | Dec 26, 2023 |
| HP            | ENVY Notebook               | Notebook    | [6ffaa62d3d](https://linux-hardware.org/?probe=6ffaa62d3d) | Dec 26, 2023 |
| HP            | ProLiant DL60 Gen9          | Server      | [6f39c976b7](https://linux-hardware.org/?probe=6f39c976b7) | Dec 26, 2023 |
| Lenovo        | ThinkPad P51 20HH0016GE     | Notebook    | [27f368f0df](https://linux-hardware.org/?probe=27f368f0df) | Dec 26, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [d1434eb282](https://linux-hardware.org/?probe=d1434eb282) | Dec 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [83c0e37ece](https://linux-hardware.org/?probe=83c0e37ece) | Dec 25, 2023 |
| HP            | 8876 11                     | Desktop     | [ffec9b5140](https://linux-hardware.org/?probe=ffec9b5140) | Dec 25, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [7a4d238793](https://linux-hardware.org/?probe=7a4d238793) | Dec 25, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [14157f8630](https://linux-hardware.org/?probe=14157f8630) | Dec 25, 2023 |
| ASUSTek       | Z9PR-D12 Series             | Server      | [59a7d0cee6](https://linux-hardware.org/?probe=59a7d0cee6) | Dec 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [edc0cbda53](https://linux-hardware.org/?probe=edc0cbda53) | Dec 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a0c82919c0](https://linux-hardware.org/?probe=a0c82919c0) | Dec 25, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9a82f5d4ae](https://linux-hardware.org/?probe=9a82f5d4ae) | Dec 25, 2023 |
| Acer          | Aspire A5SP14-51MTN         | Convertible | [873ace2728](https://linux-hardware.org/?probe=873ace2728) | Dec 25, 2023 |
| sunxi         | Unknown                     | Soc         | [fb46535d30](https://linux-hardware.org/?probe=fb46535d30) | Dec 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a9fdc9aee5](https://linux-hardware.org/?probe=a9fdc9aee5) | Dec 25, 2023 |
| Gigabyte      | P55-UD4P                    | Desktop     | [62b547894e](https://linux-hardware.org/?probe=62b547894e) | Dec 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [75a45b1c88](https://linux-hardware.org/?probe=75a45b1c88) | Dec 25, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5HM0... | Notebook    | [b30f25ba57](https://linux-hardware.org/?probe=b30f25ba57) | Dec 25, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [463b7572aa](https://linux-hardware.org/?probe=463b7572aa) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [cba7a81460](https://linux-hardware.org/?probe=cba7a81460) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [5820853b65](https://linux-hardware.org/?probe=5820853b65) | Dec 24, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e9120b7c4e](https://linux-hardware.org/?probe=e9120b7c4e) | Dec 24, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b3b2c1f621](https://linux-hardware.org/?probe=b3b2c1f621) | Dec 24, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e94cee527d](https://linux-hardware.org/?probe=e94cee527d) | Dec 24, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [8e4881d45c](https://linux-hardware.org/?probe=8e4881d45c) | Dec 24, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [7789aa889f](https://linux-hardware.org/?probe=7789aa889f) | Dec 24, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [0762c25f51](https://linux-hardware.org/?probe=0762c25f51) | Dec 24, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [95ab790a9c](https://linux-hardware.org/?probe=95ab790a9c) | Dec 24, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [3c112941d6](https://linux-hardware.org/?probe=3c112941d6) | Dec 24, 2023 |
| iRU           | LPGR.469559.012             | Desktop     | [0f955d2b87](https://linux-hardware.org/?probe=0f955d2b87) | Dec 24, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [abd0319296](https://linux-hardware.org/?probe=abd0319296) | Dec 24, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [256b476a15](https://linux-hardware.org/?probe=256b476a15) | Dec 24, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [d698ea94f5](https://linux-hardware.org/?probe=d698ea94f5) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [bfe0870fab](https://linux-hardware.org/?probe=bfe0870fab) | Dec 24, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [d6c1f0d202](https://linux-hardware.org/?probe=d6c1f0d202) | Dec 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ee7b7ce7cc](https://linux-hardware.org/?probe=ee7b7ce7cc) | Dec 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [43718a5746](https://linux-hardware.org/?probe=43718a5746) | Dec 24, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [f76e4b41dc](https://linux-hardware.org/?probe=f76e4b41dc) | Dec 24, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [c3680bfd29](https://linux-hardware.org/?probe=c3680bfd29) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [27124f064a](https://linux-hardware.org/?probe=27124f064a) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [e12710e5bd](https://linux-hardware.org/?probe=e12710e5bd) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [1fe8e8f18d](https://linux-hardware.org/?probe=1fe8e8f18d) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [381955efac](https://linux-hardware.org/?probe=381955efac) | Dec 24, 2023 |
| HP            | Pavilion g7                 | Notebook    | [bbe3fb1914](https://linux-hardware.org/?probe=bbe3fb1914) | Dec 24, 2023 |
| HP            | 1998                        | Desktop     | [c2e72e513c](https://linux-hardware.org/?probe=c2e72e513c) | Dec 23, 2023 |
| IBM           | ThinkPad R50e 1842QDU       | Notebook    | [32a349ab97](https://linux-hardware.org/?probe=32a349ab97) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [c2681f33cc](https://linux-hardware.org/?probe=c2681f33cc) | Dec 23, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ba4e48312e](https://linux-hardware.org/?probe=ba4e48312e) | Dec 23, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [fe6c638acc](https://linux-hardware.org/?probe=fe6c638acc) | Dec 23, 2023 |
| Intel         | S5000PSL                    | Server      | [4abb5e39fc](https://linux-hardware.org/?probe=4abb5e39fc) | Dec 23, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [e91530e41d](https://linux-hardware.org/?probe=e91530e41d) | Dec 23, 2023 |
| HP            | ProBook 655 G2              | Notebook    | [033325e722](https://linux-hardware.org/?probe=033325e722) | Dec 23, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| AVITA         | NS14A6                      | Notebook    | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| T-bao Tian... | GOD78                       | Desktop     | [cd28753d06](https://linux-hardware.org/?probe=cd28753d06) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [8753b04999](https://linux-hardware.org/?probe=8753b04999) | Dec 23, 2023 |
| eMachines     | EMCP61M                     | Desktop     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [6c9e82db47](https://linux-hardware.org/?probe=6c9e82db47) | Dec 23, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [4d38d67af1](https://linux-hardware.org/?probe=4d38d67af1) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [bbd50ba27b](https://linux-hardware.org/?probe=bbd50ba27b) | Dec 23, 2023 |
| Intel         | NUC10i3FNB M38070-308       | Mini pc     | [006c2edbad](https://linux-hardware.org/?probe=006c2edbad) | Dec 22, 2023 |
| Google        | Reks                        | Notebook    | [52375a57c5](https://linux-hardware.org/?probe=52375a57c5) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [5e8dc79e2c](https://linux-hardware.org/?probe=5e8dc79e2c) | Dec 22, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a11f0a948c](https://linux-hardware.org/?probe=a11f0a948c) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [f71924e3e4](https://linux-hardware.org/?probe=f71924e3e4) | Dec 22, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [1310ad15a9](https://linux-hardware.org/?probe=1310ad15a9) | Dec 22, 2023 |
| Irbis         | NB264                       | Notebook    | [8821679765](https://linux-hardware.org/?probe=8821679765) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [5d41a0e0d5](https://linux-hardware.org/?probe=5d41a0e0d5) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [ad67aeb103](https://linux-hardware.org/?probe=ad67aeb103) | Dec 22, 2023 |
| HP            | ENVY 15                     | Notebook    | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [c6cefd749d](https://linux-hardware.org/?probe=c6cefd749d) | Dec 22, 2023 |
| MSI           | B75A-G43                    | Desktop     | [70c44f3ff8](https://linux-hardware.org/?probe=70c44f3ff8) | Dec 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfc1d4289e](https://linux-hardware.org/?probe=dfc1d4289e) | Dec 22, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [cdff1cf322](https://linux-hardware.org/?probe=cdff1cf322) | Dec 22, 2023 |
| ASUSTek       | B150-PRO D3                 | Desktop     | [a686071950](https://linux-hardware.org/?probe=a686071950) | Dec 22, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [26743f9015](https://linux-hardware.org/?probe=26743f9015) | Dec 22, 2023 |
| Gigabyte      | MZ72-HB0-00 01020102        | Server      | [771f7edd98](https://linux-hardware.org/?probe=771f7edd98) | Dec 22, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [3256f09051](https://linux-hardware.org/?probe=3256f09051) | Dec 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [aa3d919a29](https://linux-hardware.org/?probe=aa3d919a29) | Dec 22, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [1c225a853e](https://linux-hardware.org/?probe=1c225a853e) | Dec 21, 2023 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | Notebook    | [093906d110](https://linux-hardware.org/?probe=093906d110) | Dec 21, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [82304c2a5f](https://linux-hardware.org/?probe=82304c2a5f) | Dec 21, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2e9f8a97e5](https://linux-hardware.org/?probe=2e9f8a97e5) | Dec 21, 2023 |
| Google        | Reks                        | Notebook    | [9a6f15c5d9](https://linux-hardware.org/?probe=9a6f15c5d9) | Dec 21, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b87a575222](https://linux-hardware.org/?probe=b87a575222) | Dec 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [22b9c27eb8](https://linux-hardware.org/?probe=22b9c27eb8) | Dec 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a102e5839d](https://linux-hardware.org/?probe=a102e5839d) | Dec 21, 2023 |
| sunxi         | Unknown                     | Soc         | [07307d0820](https://linux-hardware.org/?probe=07307d0820) | Dec 21, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [4b020f53e1](https://linux-hardware.org/?probe=4b020f53e1) | Dec 21, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [d41c926291](https://linux-hardware.org/?probe=d41c926291) | Dec 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [3a065e8d32](https://linux-hardware.org/?probe=3a065e8d32) | Dec 21, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [edc5223b9b](https://linux-hardware.org/?probe=edc5223b9b) | Dec 21, 2023 |
| AZW           | EQ                          | Desktop     | [11b8a012c0](https://linux-hardware.org/?probe=11b8a012c0) | Dec 21, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [47d1d26375](https://linux-hardware.org/?probe=47d1d26375) | Dec 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [1c3113c9b9](https://linux-hardware.org/?probe=1c3113c9b9) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d5f60126bb](https://linux-hardware.org/?probe=d5f60126bb) | Dec 20, 2023 |
| HP            | 3396                        | Desktop     | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Cisco Syst... | UCSC-C220-M4S 74-12419-0... | Server      | [80f235148b](https://linux-hardware.org/?probe=80f235148b) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [2464a532b8](https://linux-hardware.org/?probe=2464a532b8) | Dec 20, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [2c968508ee](https://linux-hardware.org/?probe=2c968508ee) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [2785a8b9c6](https://linux-hardware.org/?probe=2785a8b9c6) | Dec 20, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [74136911a0](https://linux-hardware.org/?probe=74136911a0) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | Desktop     | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ef17f12758](https://linux-hardware.org/?probe=ef17f12758) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32f0587c3f](https://linux-hardware.org/?probe=32f0587c3f) | Dec 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [237331a1ba](https://linux-hardware.org/?probe=237331a1ba) | Dec 20, 2023 |
| Dynabook      | CS40L-HB                    | Notebook    | [da68e155cd](https://linux-hardware.org/?probe=da68e155cd) | Dec 20, 2023 |
| Clevo         | W240BU                      | Notebook    | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [54ed87ec87](https://linux-hardware.org/?probe=54ed87ec87) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [2ff77e3571](https://linux-hardware.org/?probe=2ff77e3571) | Dec 20, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a641f9b41d](https://linux-hardware.org/?probe=a641f9b41d) | Dec 20, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [8e678ffb8c](https://linux-hardware.org/?probe=8e678ffb8c) | Dec 20, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b6b4165e86](https://linux-hardware.org/?probe=b6b4165e86) | Dec 20, 2023 |
| Cisco Syst... | UCSC-C220-M4S 74-12419-0... | Server      | [ccb072d03a](https://linux-hardware.org/?probe=ccb072d03a) | Dec 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fecbe03785](https://linux-hardware.org/?probe=fecbe03785) | Dec 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3eead324a8](https://linux-hardware.org/?probe=3eead324a8) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [ca0eab5d48](https://linux-hardware.org/?probe=ca0eab5d48) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Unknown       | Unknown                     | Other       | [92d87c0e52](https://linux-hardware.org/?probe=92d87c0e52) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [9b8d8ec134](https://linux-hardware.org/?probe=9b8d8ec134) | Dec 19, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [7fe77a3476](https://linux-hardware.org/?probe=7fe77a3476) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [65b6d3dcc0](https://linux-hardware.org/?probe=65b6d3dcc0) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [ab5bffcf0a](https://linux-hardware.org/?probe=ab5bffcf0a) | Dec 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [9f3471e435](https://linux-hardware.org/?probe=9f3471e435) | Dec 19, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [752a59a0cc](https://linux-hardware.org/?probe=752a59a0cc) | Dec 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [bff7dced45](https://linux-hardware.org/?probe=bff7dced45) | Dec 19, 2023 |
| Dell          | G7 7790                     | Notebook    | [bcc6b4046b](https://linux-hardware.org/?probe=bcc6b4046b) | Dec 19, 2023 |
| Lenovo        | IdeaPadFlex 4-1570 80SB     | Convertible | [c55227422a](https://linux-hardware.org/?probe=c55227422a) | Dec 19, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [61211b72bb](https://linux-hardware.org/?probe=61211b72bb) | Dec 19, 2023 |
| DellInc.      | Venue 8 Pro 5830            | Notebook    | [d6408a26a1](https://linux-hardware.org/?probe=d6408a26a1) | Dec 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [993b9536cf](https://linux-hardware.org/?probe=993b9536cf) | Dec 19, 2023 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [782dad2128](https://linux-hardware.org/?probe=782dad2128) | Dec 19, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [619bbec719](https://linux-hardware.org/?probe=619bbec719) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [6a962e40ec](https://linux-hardware.org/?probe=6a962e40ec) | Dec 19, 2023 |
| Acer          | Aspire AV15-52              | Notebook    | [daf4aa326d](https://linux-hardware.org/?probe=daf4aa326d) | Dec 19, 2023 |
| Biostar       | A55MH                       | Desktop     | [f1106ef8c7](https://linux-hardware.org/?probe=f1106ef8c7) | Dec 19, 2023 |
| MSI           | B450M BAZOOKA               | Desktop     | [0bfcb5be94](https://linux-hardware.org/?probe=0bfcb5be94) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [fd9a0ec0c4](https://linux-hardware.org/?probe=fd9a0ec0c4) | Dec 19, 2023 |
| MSI           | Pulse 17 B13VGK             | Notebook    | [71d0660568](https://linux-hardware.org/?probe=71d0660568) | Dec 18, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [e94e9e0fd9](https://linux-hardware.org/?probe=e94e9e0fd9) | Dec 18, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [020e3af833](https://linux-hardware.org/?probe=020e3af833) | Dec 18, 2023 |
| Gigabyte      | AORUS 17H BXF               | Notebook    | [ad8b646e5c](https://linux-hardware.org/?probe=ad8b646e5c) | Dec 18, 2023 |
| HP            | 2B45                        | All in one  | [dbc7094ab4](https://linux-hardware.org/?probe=dbc7094ab4) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [f47c731a09](https://linux-hardware.org/?probe=f47c731a09) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [229df442f5](https://linux-hardware.org/?probe=229df442f5) | Dec 18, 2023 |
| HP            | 1998                        | Desktop     | [1d45f9958a](https://linux-hardware.org/?probe=1d45f9958a) | Dec 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [95d29a0474](https://linux-hardware.org/?probe=95d29a0474) | Dec 18, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [5a5f20e49a](https://linux-hardware.org/?probe=5a5f20e49a) | Dec 18, 2023 |
| Dell          | 072T6D A05                  | Server      | [70a0b85bf3](https://linux-hardware.org/?probe=70a0b85bf3) | Dec 18, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [dd9d263269](https://linux-hardware.org/?probe=dd9d263269) | Dec 18, 2023 |
| Dell          | 072T6D A05                  | Server      | [b9942f8526](https://linux-hardware.org/?probe=b9942f8526) | Dec 18, 2023 |
| Unknown       | Unknown                     | Soc         | [86edce9654](https://linux-hardware.org/?probe=86edce9654) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5fae29f23f](https://linux-hardware.org/?probe=5fae29f23f) | Dec 18, 2023 |
| Gigabyte      | H510M H V2                  | Desktop     | [3228539880](https://linux-hardware.org/?probe=3228539880) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [3764b249f4](https://linux-hardware.org/?probe=3764b249f4) | Dec 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ec4da8d1a3](https://linux-hardware.org/?probe=ec4da8d1a3) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [f46bf3981f](https://linux-hardware.org/?probe=f46bf3981f) | Dec 18, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [1293ea8b65](https://linux-hardware.org/?probe=1293ea8b65) | Dec 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [81187bebc0](https://linux-hardware.org/?probe=81187bebc0) | Dec 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [709891824c](https://linux-hardware.org/?probe=709891824c) | Dec 18, 2023 |
| MSI           | Vector GP77 13VG            | Notebook    | [7b6b5a14f8](https://linux-hardware.org/?probe=7b6b5a14f8) | Dec 18, 2023 |
| MSI           | A75MA-G55                   | Desktop     | [6af3c61744](https://linux-hardware.org/?probe=6af3c61744) | Dec 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [94757e986e](https://linux-hardware.org/?probe=94757e986e) | Dec 18, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9133031c56](https://linux-hardware.org/?probe=9133031c56) | Dec 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [2eb95b1a7c](https://linux-hardware.org/?probe=2eb95b1a7c) | Dec 18, 2023 |
| Unknown       | Unknown                     | Soc         | [86e857365e](https://linux-hardware.org/?probe=86e857365e) | Dec 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [79c73e5927](https://linux-hardware.org/?probe=79c73e5927) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [87024c17b5](https://linux-hardware.org/?probe=87024c17b5) | Dec 17, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [bb37946b48](https://linux-hardware.org/?probe=bb37946b48) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [fd17674af7](https://linux-hardware.org/?probe=fd17674af7) | Dec 17, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [a4753bb26d](https://linux-hardware.org/?probe=a4753bb26d) | Dec 17, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [af666cc67d](https://linux-hardware.org/?probe=af666cc67d) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [8f2a76eb09](https://linux-hardware.org/?probe=8f2a76eb09) | Dec 17, 2023 |
| Medion        | BEAST X30                   | Notebook    | [cec06735ba](https://linux-hardware.org/?probe=cec06735ba) | Dec 17, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b61d950623](https://linux-hardware.org/?probe=b61d950623) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [d38e1077ae](https://linux-hardware.org/?probe=d38e1077ae) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0134ee9104](https://linux-hardware.org/?probe=0134ee9104) | Dec 17, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [9d204d6a41](https://linux-hardware.org/?probe=9d204d6a41) | Dec 17, 2023 |
| MSI           | Vector GP77 13VG            | Notebook    | [267679e074](https://linux-hardware.org/?probe=267679e074) | Dec 17, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [7ff498fc83](https://linux-hardware.org/?probe=7ff498fc83) | Dec 17, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [b6b44f1b80](https://linux-hardware.org/?probe=b6b44f1b80) | Dec 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [628e8cf362](https://linux-hardware.org/?probe=628e8cf362) | Dec 17, 2023 |
| ASUSTek       | P4P800-VM                   | Desktop     | [8fb6faae11](https://linux-hardware.org/?probe=8fb6faae11) | Dec 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [774f3d4feb](https://linux-hardware.org/?probe=774f3d4feb) | Dec 17, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [b9738c48b0](https://linux-hardware.org/?probe=b9738c48b0) | Dec 17, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [02e1fcae39](https://linux-hardware.org/?probe=02e1fcae39) | Dec 17, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [c878de7adb](https://linux-hardware.org/?probe=c878de7adb) | Dec 17, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [ad7f762f22](https://linux-hardware.org/?probe=ad7f762f22) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [720421dab6](https://linux-hardware.org/?probe=720421dab6) | Dec 17, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [90024d365b](https://linux-hardware.org/?probe=90024d365b) | Dec 17, 2023 |
| Samsung       | 760XDA                      | Notebook    | [53ab21d486](https://linux-hardware.org/?probe=53ab21d486) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [e0fa989ed0](https://linux-hardware.org/?probe=e0fa989ed0) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4d81e6300c](https://linux-hardware.org/?probe=4d81e6300c) | Dec 17, 2023 |
| Alienware     | m18 R1                      | Notebook    | [a136406723](https://linux-hardware.org/?probe=a136406723) | Dec 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5059d80ef9](https://linux-hardware.org/?probe=5059d80ef9) | Dec 16, 2023 |
| HP            | 829A                        | Mini pc     | [e0b2d004a0](https://linux-hardware.org/?probe=e0b2d004a0) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [7162b25b98](https://linux-hardware.org/?probe=7162b25b98) | Dec 16, 2023 |
| ASUSTek       | Pro WS W680M-ACE SE         | Desktop     | [f1b9ec56ea](https://linux-hardware.org/?probe=f1b9ec56ea) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [0aa5382212](https://linux-hardware.org/?probe=0aa5382212) | Dec 16, 2023 |
| PC Special... | N150CU                      | Notebook    | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [e4c855bedc](https://linux-hardware.org/?probe=e4c855bedc) | Dec 16, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [5f19b6ce4f](https://linux-hardware.org/?probe=5f19b6ce4f) | Dec 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e8847d53ec](https://linux-hardware.org/?probe=e8847d53ec) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [6f4f0f65bb](https://linux-hardware.org/?probe=6f4f0f65bb) | Dec 15, 2023 |
| Lenovo        | ThinkPad P1 20MDS02BGE      | Notebook    | [65eb962233](https://linux-hardware.org/?probe=65eb962233) | Dec 15, 2023 |
| Dell          | 0M5WNK A02                  | Desktop     | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [ec4a48125c](https://linux-hardware.org/?probe=ec4a48125c) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [d43271b873](https://linux-hardware.org/?probe=d43271b873) | Dec 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a785d6574b](https://linux-hardware.org/?probe=a785d6574b) | Dec 15, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [98e30b12f1](https://linux-hardware.org/?probe=98e30b12f1) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [a8677e8420](https://linux-hardware.org/?probe=a8677e8420) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [059918d809](https://linux-hardware.org/?probe=059918d809) | Dec 15, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [969d4fd521](https://linux-hardware.org/?probe=969d4fd521) | Dec 15, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [a80537094f](https://linux-hardware.org/?probe=a80537094f) | Dec 15, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [06ed7608bf](https://linux-hardware.org/?probe=06ed7608bf) | Dec 15, 2023 |
| Biostar       | A32M2                       | Desktop     | [f3fb9d0673](https://linux-hardware.org/?probe=f3fb9d0673) | Dec 15, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [ef9cf1d767](https://linux-hardware.org/?probe=ef9cf1d767) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [b4bcda5523](https://linux-hardware.org/?probe=b4bcda5523) | Dec 15, 2023 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [e0e94706d7](https://linux-hardware.org/?probe=e0e94706d7) | Dec 15, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [46178ea298](https://linux-hardware.org/?probe=46178ea298) | Dec 14, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [0305f80c2d](https://linux-hardware.org/?probe=0305f80c2d) | Dec 14, 2023 |
| Gigabyte      | P35-DS4                     | Desktop     | [23e146afdc](https://linux-hardware.org/?probe=23e146afdc) | Dec 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [69e37f3d93](https://linux-hardware.org/?probe=69e37f3d93) | Dec 14, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [de24d459c5](https://linux-hardware.org/?probe=de24d459c5) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [09a184f2e4](https://linux-hardware.org/?probe=09a184f2e4) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | Notebook    | [d9de3edb6b](https://linux-hardware.org/?probe=d9de3edb6b) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | Notebook    | [84f162f88f](https://linux-hardware.org/?probe=84f162f88f) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [67a32f0dd0](https://linux-hardware.org/?probe=67a32f0dd0) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [283dc2dab5](https://linux-hardware.org/?probe=283dc2dab5) | Dec 14, 2023 |
| HP            | 8463                        | Desktop     | [0d01616e1c](https://linux-hardware.org/?probe=0d01616e1c) | Dec 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [545a3cecbc](https://linux-hardware.org/?probe=545a3cecbc) | Dec 14, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [f1860954b3](https://linux-hardware.org/?probe=f1860954b3) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [1ed13ea8f2](https://linux-hardware.org/?probe=1ed13ea8f2) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [eafb9ad287](https://linux-hardware.org/?probe=eafb9ad287) | Dec 14, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [3504153caa](https://linux-hardware.org/?probe=3504153caa) | Dec 14, 2023 |
| Lenovo        | IdeaPadFlex 5-1470 81C9     | Convertible | [8e1afeddd0](https://linux-hardware.org/?probe=8e1afeddd0) | Dec 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [f2efee9279](https://linux-hardware.org/?probe=f2efee9279) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [0e23ff0a06](https://linux-hardware.org/?probe=0e23ff0a06) | Dec 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c4e3486e91](https://linux-hardware.org/?probe=c4e3486e91) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5200cedaa0](https://linux-hardware.org/?probe=5200cedaa0) | Dec 13, 2023 |
| Lenovo        | Flex 2 Pro-15               | Notebook    | [da278da4b6](https://linux-hardware.org/?probe=da278da4b6) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [1668553525](https://linux-hardware.org/?probe=1668553525) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [89bef2fed5](https://linux-hardware.org/?probe=89bef2fed5) | Dec 13, 2023 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [0ed1d85207](https://linux-hardware.org/?probe=0ed1d85207) | Dec 13, 2023 |
| Acer          | Aspire 1510 Rev.A           | Desktop     | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [68e68f1683](https://linux-hardware.org/?probe=68e68f1683) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5a65590bed](https://linux-hardware.org/?probe=5a65590bed) | Dec 13, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [e6205fb709](https://linux-hardware.org/?probe=e6205fb709) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [50c635dba3](https://linux-hardware.org/?probe=50c635dba3) | Dec 13, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [6f5272ea27](https://linux-hardware.org/?probe=6f5272ea27) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cfa115323d](https://linux-hardware.org/?probe=cfa115323d) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| Dell          | Latitude 5424 Rugged        | Notebook    | [ce56e420fc](https://linux-hardware.org/?probe=ce56e420fc) | Dec 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [1ac3287ee1](https://linux-hardware.org/?probe=1ac3287ee1) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [75bcf5966c](https://linux-hardware.org/?probe=75bcf5966c) | Dec 12, 2023 |
| Unknown       | AMedia X96 Max+             | Soc         | [4df1c17523](https://linux-hardware.org/?probe=4df1c17523) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 6-14ARR 81HA    | Convertible | [676e339cc5](https://linux-hardware.org/?probe=676e339cc5) | Dec 12, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [e28730f84d](https://linux-hardware.org/?probe=e28730f84d) | Dec 12, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [f90b33b7d5](https://linux-hardware.org/?probe=f90b33b7d5) | Dec 12, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [97ca767d40](https://linux-hardware.org/?probe=97ca767d40) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [1ef755944c](https://linux-hardware.org/?probe=1ef755944c) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [e4fcf233c5](https://linux-hardware.org/?probe=e4fcf233c5) | Dec 12, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [774925ed25](https://linux-hardware.org/?probe=774925ed25) | Dec 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | Notebook    | [e99a0bd1db](https://linux-hardware.org/?probe=e99a0bd1db) | Dec 12, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [6b62180e3e](https://linux-hardware.org/?probe=6b62180e3e) | Dec 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [c811c8be03](https://linux-hardware.org/?probe=c811c8be03) | Dec 12, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [7471a7b26e](https://linux-hardware.org/?probe=7471a7b26e) | Dec 12, 2023 |
| Positivo      | H14BT58                     | Notebook    | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| Dell          | 0VD5HY A10                  | Desktop     | [366f1ac830](https://linux-hardware.org/?probe=366f1ac830) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [a9059220f3](https://linux-hardware.org/?probe=a9059220f3) | Dec 12, 2023 |
| Fujitsu       | JIH61Y3                     | Desktop     | [cb566e2fd0](https://linux-hardware.org/?probe=cb566e2fd0) | Dec 12, 2023 |
| Acer          | Aspire one                  | Notebook    | [fb1f2ccd2e](https://linux-hardware.org/?probe=fb1f2ccd2e) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [756283ec58](https://linux-hardware.org/?probe=756283ec58) | Dec 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [4053f6be95](https://linux-hardware.org/?probe=4053f6be95) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c258c213e6](https://linux-hardware.org/?probe=c258c213e6) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [79c6d70468](https://linux-hardware.org/?probe=79c6d70468) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0d7abecf9b](https://linux-hardware.org/?probe=0d7abecf9b) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [3dcb225ff4](https://linux-hardware.org/?probe=3dcb225ff4) | Dec 11, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [f5b7104728](https://linux-hardware.org/?probe=f5b7104728) | Dec 11, 2023 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [bfe021294b](https://linux-hardware.org/?probe=bfe021294b) | Dec 11, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [d5500a3830](https://linux-hardware.org/?probe=d5500a3830) | Dec 11, 2023 |
| Google        | Electro                     | Notebook    | [503645df79](https://linux-hardware.org/?probe=503645df79) | Dec 11, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [88b93b571e](https://linux-hardware.org/?probe=88b93b571e) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [57a80d9d1b](https://linux-hardware.org/?probe=57a80d9d1b) | Dec 11, 2023 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [29590179a8](https://linux-hardware.org/?probe=29590179a8) | Dec 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [9d7ed9efae](https://linux-hardware.org/?probe=9d7ed9efae) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2c6a120dd2](https://linux-hardware.org/?probe=2c6a120dd2) | Dec 10, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [4a2deac69b](https://linux-hardware.org/?probe=4a2deac69b) | Dec 10, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [9d707e64d4](https://linux-hardware.org/?probe=9d707e64d4) | Dec 10, 2023 |
| HP            | 0968h                       | Desktop     | [b1fb94198e](https://linux-hardware.org/?probe=b1fb94198e) | Dec 10, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [201fa157d6](https://linux-hardware.org/?probe=201fa157d6) | Dec 10, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [18f6c41058](https://linux-hardware.org/?probe=18f6c41058) | Dec 10, 2023 |
| Acer          | Aspire Z24-890              | All in one  | [2853098aad](https://linux-hardware.org/?probe=2853098aad) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [324e195003](https://linux-hardware.org/?probe=324e195003) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f60e90cfd0](https://linux-hardware.org/?probe=f60e90cfd0) | Dec 10, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25d8aaca3c](https://linux-hardware.org/?probe=25d8aaca3c) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [c1d93cb6b2](https://linux-hardware.org/?probe=c1d93cb6b2) | Dec 09, 2023 |
| Lenovo        | ThinkPad T530 242922G       | Notebook    | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [93f24d2411](https://linux-hardware.org/?probe=93f24d2411) | Dec 09, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ae61f1039f](https://linux-hardware.org/?probe=ae61f1039f) | Dec 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [1435c0e9db](https://linux-hardware.org/?probe=1435c0e9db) | Dec 09, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [c02997fc15](https://linux-hardware.org/?probe=c02997fc15) | Dec 09, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ad002286ac](https://linux-hardware.org/?probe=ad002286ac) | Dec 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [9d633902a0](https://linux-hardware.org/?probe=9d633902a0) | Dec 09, 2023 |
| AZW           | MINI S                      | Desktop     | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [2b1117b052](https://linux-hardware.org/?probe=2b1117b052) | Dec 09, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4106c6dbcf](https://linux-hardware.org/?probe=4106c6dbcf) | Dec 09, 2023 |
| ASUSTek       | X507UB                      | Notebook    | [f1a1ea60e6](https://linux-hardware.org/?probe=f1a1ea60e6) | Dec 09, 2023 |
| Dell          | Precision 3550              | Notebook    | [a3be7ab761](https://linux-hardware.org/?probe=a3be7ab761) | Dec 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [af22ca1731](https://linux-hardware.org/?probe=af22ca1731) | Dec 08, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [cc6cd166f2](https://linux-hardware.org/?probe=cc6cd166f2) | Dec 08, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [0ce9d18c51](https://linux-hardware.org/?probe=0ce9d18c51) | Dec 08, 2023 |
| Toshiba       | Satellite L50-A-19P         | Notebook    | [cd3314169e](https://linux-hardware.org/?probe=cd3314169e) | Dec 08, 2023 |
| HP            | G42                         | Notebook    | [f23e6ffe56](https://linux-hardware.org/?probe=f23e6ffe56) | Dec 08, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [7ca4962c57](https://linux-hardware.org/?probe=7ca4962c57) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [b53080f09f](https://linux-hardware.org/?probe=b53080f09f) | Dec 08, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67371c6af4](https://linux-hardware.org/?probe=67371c6af4) | Dec 08, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| MSI           | G31TM-P35                   | Desktop     | [e241cfaeca](https://linux-hardware.org/?probe=e241cfaeca) | Dec 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA    | Notebook    | [b46d0490b6](https://linux-hardware.org/?probe=b46d0490b6) | Dec 08, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [39d65538cb](https://linux-hardware.org/?probe=39d65538cb) | Dec 08, 2023 |
| Dell          | 0X45NX A01                  | Server      | [b89424543d](https://linux-hardware.org/?probe=b89424543d) | Dec 08, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [0e2900b443](https://linux-hardware.org/?probe=0e2900b443) | Dec 08, 2023 |
| MSI           | MEG X399 CREATION           | Desktop     | [02adc5ef8b](https://linux-hardware.org/?probe=02adc5ef8b) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8H800    | Notebook    | [49fbd4df76](https://linux-hardware.org/?probe=49fbd4df76) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8C000    | Notebook    | [bff5eac6db](https://linux-hardware.org/?probe=bff5eac6db) | Dec 08, 2023 |
| Dell          | 0KP561                      | Desktop     | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| Dell          | 04YP6J A01                  | Desktop     | [186bb25f07](https://linux-hardware.org/?probe=186bb25f07) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [031fd2298b](https://linux-hardware.org/?probe=031fd2298b) | Dec 07, 2023 |
| HP            | G62                         | Notebook    | [c2f10412aa](https://linux-hardware.org/?probe=c2f10412aa) | Dec 07, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Intel         | JSL MRD                     | Desktop     | [fb3b75c8cc](https://linux-hardware.org/?probe=fb3b75c8cc) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| HP            | 339A                        | Desktop     | [a114886e67](https://linux-hardware.org/?probe=a114886e67) | Dec 07, 2023 |
| Dell          | 0GVPNP A03                  | Server      | [c618310d44](https://linux-hardware.org/?probe=c618310d44) | Dec 07, 2023 |
| Acer          | Extensa 4210                | Notebook    | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| Aquarius      | NS585                       | Notebook    | [b6b0a78cfa](https://linux-hardware.org/?probe=b6b0a78cfa) | Dec 07, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [b1c3e47458](https://linux-hardware.org/?probe=b1c3e47458) | Dec 07, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [116dce4b93](https://linux-hardware.org/?probe=116dce4b93) | Dec 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [39a966c6da](https://linux-hardware.org/?probe=39a966c6da) | Dec 07, 2023 |
| Dell          | Precision 7550              | Notebook    | [11f63c8ba3](https://linux-hardware.org/?probe=11f63c8ba3) | Dec 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [256fbd42a6](https://linux-hardware.org/?probe=256fbd42a6) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dcb3b62f73](https://linux-hardware.org/?probe=dcb3b62f73) | Dec 06, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [21b8166e02](https://linux-hardware.org/?probe=21b8166e02) | Dec 06, 2023 |
| Intel         | H61                         | Desktop     | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [b118593b9d](https://linux-hardware.org/?probe=b118593b9d) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [600935b467](https://linux-hardware.org/?probe=600935b467) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [d4ece1c445](https://linux-hardware.org/?probe=d4ece1c445) | Dec 06, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [523404e018](https://linux-hardware.org/?probe=523404e018) | Dec 06, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b7070058fb](https://linux-hardware.org/?probe=b7070058fb) | Dec 06, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [280a9a93e6](https://linux-hardware.org/?probe=280a9a93e6) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [46bc5ee727](https://linux-hardware.org/?probe=46bc5ee727) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b5430476af](https://linux-hardware.org/?probe=b5430476af) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6e61bec2ab](https://linux-hardware.org/?probe=6e61bec2ab) | Dec 06, 2023 |
| HP            | ENVY Notebook               | Notebook    | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0cb29ce493](https://linux-hardware.org/?probe=0cb29ce493) | Dec 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6d4537080b](https://linux-hardware.org/?probe=6d4537080b) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [ce624b95df](https://linux-hardware.org/?probe=ce624b95df) | Dec 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7bd10d1922](https://linux-hardware.org/?probe=7bd10d1922) | Dec 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6e7c9a6ebc](https://linux-hardware.org/?probe=6e7c9a6ebc) | Dec 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [71c469e9dd](https://linux-hardware.org/?probe=71c469e9dd) | Dec 05, 2023 |
| ASUSTek       | P553UJ                      | Notebook    | [e5ed994bf9](https://linux-hardware.org/?probe=e5ed994bf9) | Dec 05, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [68784031ca](https://linux-hardware.org/?probe=68784031ca) | Dec 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [1b39d673f8](https://linux-hardware.org/?probe=1b39d673f8) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | Notebook    | [68ec81b134](https://linux-hardware.org/?probe=68ec81b134) | Dec 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [8132e0caf0](https://linux-hardware.org/?probe=8132e0caf0) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [56dab5d412](https://linux-hardware.org/?probe=56dab5d412) | Dec 04, 2023 |
| HP            | Spectre Notebook            | Notebook    | [95b8230b80](https://linux-hardware.org/?probe=95b8230b80) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [da8437565a](https://linux-hardware.org/?probe=da8437565a) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [de877c77b2](https://linux-hardware.org/?probe=de877c77b2) | Dec 04, 2023 |
| MSI           | Thin GF63 12VE              | Notebook    | [ada68f6d8a](https://linux-hardware.org/?probe=ada68f6d8a) | Dec 04, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [f382271478](https://linux-hardware.org/?probe=f382271478) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [969efab4b8](https://linux-hardware.org/?probe=969efab4b8) | Dec 04, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [87616f0d71](https://linux-hardware.org/?probe=87616f0d71) | Dec 04, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [76fdeed52e](https://linux-hardware.org/?probe=76fdeed52e) | Dec 04, 2023 |
| Dell          | 0RN474                      | Desktop     | [17392605bb](https://linux-hardware.org/?probe=17392605bb) | Dec 04, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fde3c9253f](https://linux-hardware.org/?probe=fde3c9253f) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | Notebook    | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [23cf3c751a](https://linux-hardware.org/?probe=23cf3c751a) | Dec 04, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [890efb3114](https://linux-hardware.org/?probe=890efb3114) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [22b736c30d](https://linux-hardware.org/?probe=22b736c30d) | Dec 04, 2023 |
| Supermicro    | X8DTU                       | Server      | [d2bc04d563](https://linux-hardware.org/?probe=d2bc04d563) | Dec 04, 2023 |
| Supermicro    | X8DTU                       | Server      | [436a64c8fb](https://linux-hardware.org/?probe=436a64c8fb) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3f26c37883](https://linux-hardware.org/?probe=3f26c37883) | Dec 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | Notebook    | [592eb925fd](https://linux-hardware.org/?probe=592eb925fd) | Dec 04, 2023 |
| HP            | 8619                        | Desktop     | [a33e273f33](https://linux-hardware.org/?probe=a33e273f33) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | Notebook    | [75603d3c20](https://linux-hardware.org/?probe=75603d3c20) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [7afcab06a4](https://linux-hardware.org/?probe=7afcab06a4) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [961b00cfbe](https://linux-hardware.org/?probe=961b00cfbe) | Dec 04, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [7c16c8b9ac](https://linux-hardware.org/?probe=7c16c8b9ac) | Dec 03, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [830b83bf5c](https://linux-hardware.org/?probe=830b83bf5c) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [bbd413d34b](https://linux-hardware.org/?probe=bbd413d34b) | Dec 03, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [83b954a1cd](https://linux-hardware.org/?probe=83b954a1cd) | Dec 03, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [848e0dbd37](https://linux-hardware.org/?probe=848e0dbd37) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [b8af3ee6d5](https://linux-hardware.org/?probe=b8af3ee6d5) | Dec 03, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [c4e675a705](https://linux-hardware.org/?probe=c4e675a705) | Dec 03, 2023 |
| Acer          | Unknown                     | Notebook    | [6555dd06ac](https://linux-hardware.org/?probe=6555dd06ac) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [67efae847f](https://linux-hardware.org/?probe=67efae847f) | Dec 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [47222bf19c](https://linux-hardware.org/?probe=47222bf19c) | Dec 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5a5296e72f](https://linux-hardware.org/?probe=5a5296e72f) | Dec 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [595fc0137d](https://linux-hardware.org/?probe=595fc0137d) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [41ef064705](https://linux-hardware.org/?probe=41ef064705) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [b14a847625](https://linux-hardware.org/?probe=b14a847625) | Dec 03, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [3c6a13271b](https://linux-hardware.org/?probe=3c6a13271b) | Dec 03, 2023 |
| Dell          | Precision M4800             | Notebook    | [ff01ff15f9](https://linux-hardware.org/?probe=ff01ff15f9) | Dec 03, 2023 |
| Jumper        | EZbook                      | Notebook    | [54cf2bf1d4](https://linux-hardware.org/?probe=54cf2bf1d4) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [3222457362](https://linux-hardware.org/?probe=3222457362) | Dec 03, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [a28372598e](https://linux-hardware.org/?probe=a28372598e) | Dec 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [bb1b02ee0c](https://linux-hardware.org/?probe=bb1b02ee0c) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5aeec2e399](https://linux-hardware.org/?probe=5aeec2e399) | Dec 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [89effd522f](https://linux-hardware.org/?probe=89effd522f) | Dec 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2492e6ae2e](https://linux-hardware.org/?probe=2492e6ae2e) | Dec 02, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [daa56bab51](https://linux-hardware.org/?probe=daa56bab51) | Dec 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [744c430aa7](https://linux-hardware.org/?probe=744c430aa7) | Dec 02, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [1462381824](https://linux-hardware.org/?probe=1462381824) | Dec 02, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [c0f6772db1](https://linux-hardware.org/?probe=c0f6772db1) | Dec 02, 2023 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [d97ecb484d](https://linux-hardware.org/?probe=d97ecb484d) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [99293a328c](https://linux-hardware.org/?probe=99293a328c) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [b8e3a992b3](https://linux-hardware.org/?probe=b8e3a992b3) | Dec 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [138a63b91b](https://linux-hardware.org/?probe=138a63b91b) | Dec 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [f366381075](https://linux-hardware.org/?probe=f366381075) | Dec 02, 2023 |
| Sony          | VPCEB46FX                   | Notebook    | [b331dc017f](https://linux-hardware.org/?probe=b331dc017f) | Dec 02, 2023 |
| Lenovo        | ThinkPad X220 4291OL3       | Notebook    | [d07f89fdd6](https://linux-hardware.org/?probe=d07f89fdd6) | Dec 02, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [aa52a8ceac](https://linux-hardware.org/?probe=aa52a8ceac) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [d0bbc73e29](https://linux-hardware.org/?probe=d0bbc73e29) | Dec 02, 2023 |
| Gigabyte      | H470 HD3                    | Desktop     | [0b9cf3a0a5](https://linux-hardware.org/?probe=0b9cf3a0a5) | Dec 02, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [109cecbcba](https://linux-hardware.org/?probe=109cecbcba) | Dec 01, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3cbadbe556](https://linux-hardware.org/?probe=3cbadbe556) | Dec 01, 2023 |
| Sony          | VPCF11M1E                   | Notebook    | [f185cc14da](https://linux-hardware.org/?probe=f185cc14da) | Dec 01, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [13e072ec20](https://linux-hardware.org/?probe=13e072ec20) | Dec 01, 2023 |
| Dell          | Latitude 7440               | Notebook    | [b4179d70c3](https://linux-hardware.org/?probe=b4179d70c3) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [8a625099b1](https://linux-hardware.org/?probe=8a625099b1) | Dec 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [fc30a356f0](https://linux-hardware.org/?probe=fc30a356f0) | Dec 01, 2023 |
| HP            | 212B                        | Desktop     | [dc1382e549](https://linux-hardware.org/?probe=dc1382e549) | Dec 01, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [c4f3b7fec9](https://linux-hardware.org/?probe=c4f3b7fec9) | Dec 01, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [b0c7a29604](https://linux-hardware.org/?probe=b0c7a29604) | Dec 01, 2023 |
| Toshiba       | Satellite L775              | Notebook    | [da7cc192f7](https://linux-hardware.org/?probe=da7cc192f7) | Dec 01, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [f17a1eb208](https://linux-hardware.org/?probe=f17a1eb208) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | Notebook    | [7590036270](https://linux-hardware.org/?probe=7590036270) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4ab4cd31f3](https://linux-hardware.org/?probe=4ab4cd31f3) | Nov 30, 2023 |
| MSI           | A78M-E45                    | Desktop     | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | Desktop     | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Supermicro    | X11SSL-F                    | Server      | [0ad16d30ae](https://linux-hardware.org/?probe=0ad16d30ae) | Nov 30, 2023 |
| HP            | 8053                        | Desktop     | [a2b9b5d498](https://linux-hardware.org/?probe=a2b9b5d498) | Nov 30, 2023 |
| Supermicro    | X8DTU                       | Server      | [35b42f6bdb](https://linux-hardware.org/?probe=35b42f6bdb) | Nov 30, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [cf7d8fdbf1](https://linux-hardware.org/?probe=cf7d8fdbf1) | Nov 30, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4bac6b7cd5](https://linux-hardware.org/?probe=4bac6b7cd5) | Nov 30, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ede8970ea9](https://linux-hardware.org/?probe=ede8970ea9) | Nov 30, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [a828388299](https://linux-hardware.org/?probe=a828388299) | Nov 30, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b0642c446](https://linux-hardware.org/?probe=2b0642c446) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [c7b394b498](https://linux-hardware.org/?probe=c7b394b498) | Nov 30, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | Notebook    | [352fffb7a9](https://linux-hardware.org/?probe=352fffb7a9) | Nov 30, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [38e526321f](https://linux-hardware.org/?probe=38e526321f) | Nov 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [9035e39786](https://linux-hardware.org/?probe=9035e39786) | Nov 29, 2023 |
| Toshiba       | Satellite L455D             | Notebook    | [d08710e3d3](https://linux-hardware.org/?probe=d08710e3d3) | Nov 29, 2023 |
| MACHINIST     | X99 RS9                     | Desktop     | [722f516451](https://linux-hardware.org/?probe=722f516451) | Nov 29, 2023 |
| HP            | 304Ah                       | Desktop     | [03437e0238](https://linux-hardware.org/?probe=03437e0238) | Nov 29, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [01aee620f1](https://linux-hardware.org/?probe=01aee620f1) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [384fc3c571](https://linux-hardware.org/?probe=384fc3c571) | Nov 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [dae10e70d0](https://linux-hardware.org/?probe=dae10e70d0) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| Supermicro    | X13SAE-F                    | Server      | [6fa7511431](https://linux-hardware.org/?probe=6fa7511431) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d2284172c7](https://linux-hardware.org/?probe=d2284172c7) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4521051e77](https://linux-hardware.org/?probe=4521051e77) | Nov 29, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [6a2c279391](https://linux-hardware.org/?probe=6a2c279391) | Nov 29, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5894ef78ae](https://linux-hardware.org/?probe=5894ef78ae) | Nov 29, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | Desktop     | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ef2a2ab2a9](https://linux-hardware.org/?probe=ef2a2ab2a9) | Nov 29, 2023 |
| ASUSTek       | M50Vc                       | Notebook    | [0eba431c7a](https://linux-hardware.org/?probe=0eba431c7a) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6865be0fd7](https://linux-hardware.org/?probe=6865be0fd7) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [414132dc07](https://linux-hardware.org/?probe=414132dc07) | Nov 29, 2023 |
| Lenovo        | ThinkPad T520 4243VU3       | Notebook    | [6cbaf1893d](https://linux-hardware.org/?probe=6cbaf1893d) | Nov 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [66847c493b](https://linux-hardware.org/?probe=66847c493b) | Nov 29, 2023 |
| Dell          | Precision 7560              | Notebook    | [035f0d6f41](https://linux-hardware.org/?probe=035f0d6f41) | Nov 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bb3faeeed7](https://linux-hardware.org/?probe=bb3faeeed7) | Nov 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cf46975c18](https://linux-hardware.org/?probe=cf46975c18) | Nov 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0d6a4cd900](https://linux-hardware.org/?probe=0d6a4cd900) | Nov 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b01d99f799](https://linux-hardware.org/?probe=b01d99f799) | Nov 28, 2023 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [b3de42156e](https://linux-hardware.org/?probe=b3de42156e) | Nov 28, 2023 |
| ASRock        | H61DE/S3                    | Desktop     | [50d5c63e0f](https://linux-hardware.org/?probe=50d5c63e0f) | Nov 28, 2023 |
| MSI           | X299 GAMING PRO CARBON      | Desktop     | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [416a759973](https://linux-hardware.org/?probe=416a759973) | Nov 28, 2023 |
| Dell          | 0WCJNT A04                  | Server      | [3adc9b76ee](https://linux-hardware.org/?probe=3adc9b76ee) | Nov 28, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [6b10244910](https://linux-hardware.org/?probe=6b10244910) | Nov 28, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [d24b2b8298](https://linux-hardware.org/?probe=d24b2b8298) | Nov 28, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [413049d0f4](https://linux-hardware.org/?probe=413049d0f4) | Nov 28, 2023 |
| MSI           | Prestige 16Studio A13VF     | Notebook    | [4d8fb7dd05](https://linux-hardware.org/?probe=4d8fb7dd05) | Nov 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [66554ab5d7](https://linux-hardware.org/?probe=66554ab5d7) | Nov 28, 2023 |
| Gigabyte      | H470 HD3                    | Desktop     | [0ecb969c2c](https://linux-hardware.org/?probe=0ecb969c2c) | Nov 28, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [1f87fc5fca](https://linux-hardware.org/?probe=1f87fc5fca) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2289ab10b3](https://linux-hardware.org/?probe=2289ab10b3) | Nov 27, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [93d9d89a9a](https://linux-hardware.org/?probe=93d9d89a9a) | Nov 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [3fe11b3243](https://linux-hardware.org/?probe=3fe11b3243) | Nov 27, 2023 |
| Lenovo        | Flex 2 Pro-15               | Notebook    | [7e7f94ca3b](https://linux-hardware.org/?probe=7e7f94ca3b) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | Notebook    | [705aa34dce](https://linux-hardware.org/?probe=705aa34dce) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | Notebook    | [569db41ca1](https://linux-hardware.org/?probe=569db41ca1) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | Notebook    | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| HP            | 895F                        | All in one  | [9322fd4f07](https://linux-hardware.org/?probe=9322fd4f07) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d185d53d8a](https://linux-hardware.org/?probe=d185d53d8a) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S2YS00    | Notebook    | [635d73bd44](https://linux-hardware.org/?probe=635d73bd44) | Nov 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5d7a20cf12](https://linux-hardware.org/?probe=5d7a20cf12) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4609a7f037](https://linux-hardware.org/?probe=4609a7f037) | Nov 27, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [a7890b3e79](https://linux-hardware.org/?probe=a7890b3e79) | Nov 27, 2023 |
| Google        | Terra                       | Notebook    | [b21072bf0e](https://linux-hardware.org/?probe=b21072bf0e) | Nov 27, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [1660aa24b1](https://linux-hardware.org/?probe=1660aa24b1) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [97e207d679](https://linux-hardware.org/?probe=97e207d679) | Nov 27, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [b784691187](https://linux-hardware.org/?probe=b784691187) | Nov 27, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [1e36c88b83](https://linux-hardware.org/?probe=1e36c88b83) | Nov 27, 2023 |
| ECS           | G31T-M9                     | Desktop     | [fa44ca9239](https://linux-hardware.org/?probe=fa44ca9239) | Nov 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [419daf1e57](https://linux-hardware.org/?probe=419daf1e57) | Nov 27, 2023 |
| Lenovo        | ThinkPad X200 7458PN6       | Notebook    | [e37f4ef1d4](https://linux-hardware.org/?probe=e37f4ef1d4) | Nov 27, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [182a3875c4](https://linux-hardware.org/?probe=182a3875c4) | Nov 27, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [196be5def7](https://linux-hardware.org/?probe=196be5def7) | Nov 27, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [02ece75e31](https://linux-hardware.org/?probe=02ece75e31) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [5cf9f0b3e1](https://linux-hardware.org/?probe=5cf9f0b3e1) | Nov 27, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [f18c7cb67b](https://linux-hardware.org/?probe=f18c7cb67b) | Nov 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [007cf510b3](https://linux-hardware.org/?probe=007cf510b3) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [332eec50ca](https://linux-hardware.org/?probe=332eec50ca) | Nov 26, 2023 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [97dfb05d56](https://linux-hardware.org/?probe=97dfb05d56) | Nov 26, 2023 |
| MSI           | B85M-G43                    | Desktop     | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [5bf94efca1](https://linux-hardware.org/?probe=5bf94efca1) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6005ac3fdd](https://linux-hardware.org/?probe=6005ac3fdd) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [281c935424](https://linux-hardware.org/?probe=281c935424) | Nov 26, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e4c365b554](https://linux-hardware.org/?probe=e4c365b554) | Nov 26, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [abd56e94a2](https://linux-hardware.org/?probe=abd56e94a2) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [484699c792](https://linux-hardware.org/?probe=484699c792) | Nov 26, 2023 |
| Chuwi         | Hi10 plus tablet            | Tablet      | [d5306a60da](https://linux-hardware.org/?probe=d5306a60da) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [aaf90bfd52](https://linux-hardware.org/?probe=aaf90bfd52) | Nov 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [b1448b5814](https://linux-hardware.org/?probe=b1448b5814) | Nov 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [73eebdebc2](https://linux-hardware.org/?probe=73eebdebc2) | Nov 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [8cba28d4a5](https://linux-hardware.org/?probe=8cba28d4a5) | Nov 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1e4a3ed089](https://linux-hardware.org/?probe=1e4a3ed089) | Nov 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2bbfbaca9](https://linux-hardware.org/?probe=e2bbfbaca9) | Nov 25, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [a6ab0954e0](https://linux-hardware.org/?probe=a6ab0954e0) | Nov 25, 2023 |
| Unknown       | HX90                        | Desktop     | [b4eef50430](https://linux-hardware.org/?probe=b4eef50430) | Nov 25, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [f740e978fc](https://linux-hardware.org/?probe=f740e978fc) | Nov 25, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [a0480513dd](https://linux-hardware.org/?probe=a0480513dd) | Nov 25, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [e01ac99a92](https://linux-hardware.org/?probe=e01ac99a92) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [84fefe8e38](https://linux-hardware.org/?probe=84fefe8e38) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | Notebook    | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [9620d48b2f](https://linux-hardware.org/?probe=9620d48b2f) | Nov 25, 2023 |
| Dell          | Latitude 3510               | Notebook    | [0ebe37e56d](https://linux-hardware.org/?probe=0ebe37e56d) | Nov 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [eb4379efae](https://linux-hardware.org/?probe=eb4379efae) | Nov 24, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [6a4204f060](https://linux-hardware.org/?probe=6a4204f060) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [52e54c41e4](https://linux-hardware.org/?probe=52e54c41e4) | Nov 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [dc456b5cc5](https://linux-hardware.org/?probe=dc456b5cc5) | Nov 24, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [4b725b7022](https://linux-hardware.org/?probe=4b725b7022) | Nov 24, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6497745451](https://linux-hardware.org/?probe=6497745451) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [2d59329fc6](https://linux-hardware.org/?probe=2d59329fc6) | Nov 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [59a3d34f64](https://linux-hardware.org/?probe=59a3d34f64) | Nov 24, 2023 |
| AZW           | U59                         | Desktop     | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [00ef59a95d](https://linux-hardware.org/?probe=00ef59a95d) | Nov 24, 2023 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [f99cb416db](https://linux-hardware.org/?probe=f99cb416db) | Nov 24, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [d8e9de7c1d](https://linux-hardware.org/?probe=d8e9de7c1d) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [499c7927dd](https://linux-hardware.org/?probe=499c7927dd) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9102327ebf](https://linux-hardware.org/?probe=9102327ebf) | Nov 23, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [a293e791bf](https://linux-hardware.org/?probe=a293e791bf) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e5ad7dda0](https://linux-hardware.org/?probe=1e5ad7dda0) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [9d776a8aa8](https://linux-hardware.org/?probe=9d776a8aa8) | Nov 23, 2023 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [d850b7a222](https://linux-hardware.org/?probe=d850b7a222) | Nov 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6706fb6f0f](https://linux-hardware.org/?probe=6706fb6f0f) | Nov 23, 2023 |
| Supermicro    | X8DTH                       | Server      | [585c41a46b](https://linux-hardware.org/?probe=585c41a46b) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | Notebook    | [adabeb3e91](https://linux-hardware.org/?probe=adabeb3e91) | Nov 23, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [415b88184f](https://linux-hardware.org/?probe=415b88184f) | Nov 23, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [b6496b25f7](https://linux-hardware.org/?probe=b6496b25f7) | Nov 23, 2023 |
| Unknown       | Libre Computer AML-S905X... | Soc         | [32e27eeecd](https://linux-hardware.org/?probe=32e27eeecd) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [be47adc197](https://linux-hardware.org/?probe=be47adc197) | Nov 23, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [101c96a0c0](https://linux-hardware.org/?probe=101c96a0c0) | Nov 22, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f990b64367](https://linux-hardware.org/?probe=f990b64367) | Nov 22, 2023 |
| Google        | Edgar                       | Notebook    | [12d8e1b6af](https://linux-hardware.org/?probe=12d8e1b6af) | Nov 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1a0c353a8e](https://linux-hardware.org/?probe=1a0c353a8e) | Nov 22, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [ace74e0228](https://linux-hardware.org/?probe=ace74e0228) | Nov 22, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Dell          | Precision M4600             | Notebook    | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | Desktop     | [04e88a7e08](https://linux-hardware.org/?probe=04e88a7e08) | Nov 22, 2023 |
| Lenovo        | ThinkPad P52 20MAS21905     | Notebook    | [ada7aab2dd](https://linux-hardware.org/?probe=ada7aab2dd) | Nov 22, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [e0781004e0](https://linux-hardware.org/?probe=e0781004e0) | Nov 22, 2023 |
| Huanan        | X99-F8D PLUS V1.2           | Desktop     | [2edde2bb35](https://linux-hardware.org/?probe=2edde2bb35) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [43a399828f](https://linux-hardware.org/?probe=43a399828f) | Nov 22, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c95cbb7ba7](https://linux-hardware.org/?probe=c95cbb7ba7) | Nov 22, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | Desktop     | [03140aee39](https://linux-hardware.org/?probe=03140aee39) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [b72fbdf43a](https://linux-hardware.org/?probe=b72fbdf43a) | Nov 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [942a2e278a](https://linux-hardware.org/?probe=942a2e278a) | Nov 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [11bf0b075f](https://linux-hardware.org/?probe=11bf0b075f) | Nov 22, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f6c29a55ad](https://linux-hardware.org/?probe=f6c29a55ad) | Nov 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [adb43d89ab](https://linux-hardware.org/?probe=adb43d89ab) | Nov 22, 2023 |
| Dell          | Latitude 7440               | Notebook    | [fa13937043](https://linux-hardware.org/?probe=fa13937043) | Nov 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [96e98f8c80](https://linux-hardware.org/?probe=96e98f8c80) | Nov 22, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [f892ee3011](https://linux-hardware.org/?probe=f892ee3011) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a38fd35585](https://linux-hardware.org/?probe=a38fd35585) | Nov 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [618916ad03](https://linux-hardware.org/?probe=618916ad03) | Nov 21, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a51c296185](https://linux-hardware.org/?probe=a51c296185) | Nov 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dd61ef221a](https://linux-hardware.org/?probe=dd61ef221a) | Nov 21, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [c2e0a4cefc](https://linux-hardware.org/?probe=c2e0a4cefc) | Nov 21, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [729045e89d](https://linux-hardware.org/?probe=729045e89d) | Nov 21, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [80a223d120](https://linux-hardware.org/?probe=80a223d120) | Nov 21, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [09b6107952](https://linux-hardware.org/?probe=09b6107952) | Nov 20, 2023 |
| MSI           | G31M3                       | Desktop     | [d9e2a5683a](https://linux-hardware.org/?probe=d9e2a5683a) | Nov 20, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | G62                         | Notebook    | [de2f290631](https://linux-hardware.org/?probe=de2f290631) | Nov 20, 2023 |
| Panasonic     | CF-33-1                     | Tablet      | [a2bfa66a7e](https://linux-hardware.org/?probe=a2bfa66a7e) | Nov 20, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [7c6999858f](https://linux-hardware.org/?probe=7c6999858f) | Nov 20, 2023 |
| HP            | 1905                        | Desktop     | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| Dell          | 0DPRKF A04                  | Server      | [99d59495ed](https://linux-hardware.org/?probe=99d59495ed) | Nov 20, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [9fab1b4add](https://linux-hardware.org/?probe=9fab1b4add) | Nov 20, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7d8f15f875](https://linux-hardware.org/?probe=7d8f15f875) | Nov 20, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [48a562a1b6](https://linux-hardware.org/?probe=48a562a1b6) | Nov 20, 2023 |
| ADLINK Tec... | MXE5400                     | Desktop     | [ae09533003](https://linux-hardware.org/?probe=ae09533003) | Nov 20, 2023 |
| Dell          | 072T6D A05                  | Server      | [146f803f7a](https://linux-hardware.org/?probe=146f803f7a) | Nov 20, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [67cba6139f](https://linux-hardware.org/?probe=67cba6139f) | Nov 20, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3ec9fbcdea](https://linux-hardware.org/?probe=3ec9fbcdea) | Nov 20, 2023 |
| Dell          | 072T6D A05                  | Server      | [3837a0359c](https://linux-hardware.org/?probe=3837a0359c) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e394aadce0](https://linux-hardware.org/?probe=e394aadce0) | Nov 20, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [eccc68d336](https://linux-hardware.org/?probe=eccc68d336) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9d71a8e453](https://linux-hardware.org/?probe=9d71a8e453) | Nov 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [66b4ff8f76](https://linux-hardware.org/?probe=66b4ff8f76) | Nov 20, 2023 |
| Dell          | Latitude 5401               | Notebook    | [b3698296b0](https://linux-hardware.org/?probe=b3698296b0) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [a090e73dbf](https://linux-hardware.org/?probe=a090e73dbf) | Nov 20, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2567713f24](https://linux-hardware.org/?probe=2567713f24) | Nov 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [a40bc78bcf](https://linux-hardware.org/?probe=a40bc78bcf) | Nov 19, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ac68da4f7c](https://linux-hardware.org/?probe=ac68da4f7c) | Nov 19, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [4173fd74a2](https://linux-hardware.org/?probe=4173fd74a2) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c9b5f09ea5](https://linux-hardware.org/?probe=c9b5f09ea5) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c76562a6ce](https://linux-hardware.org/?probe=c76562a6ce) | Nov 19, 2023 |
| IBM           | ThinkPad T42 2374GB1        | Notebook    | [455a2c937b](https://linux-hardware.org/?probe=455a2c937b) | Nov 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [80d502e7c1](https://linux-hardware.org/?probe=80d502e7c1) | Nov 19, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [65f7027c84](https://linux-hardware.org/?probe=65f7027c84) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [deea1f8184](https://linux-hardware.org/?probe=deea1f8184) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [08f1313c20](https://linux-hardware.org/?probe=08f1313c20) | Nov 19, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [866a100b18](https://linux-hardware.org/?probe=866a100b18) | Nov 19, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| Acer          | Predator G3620              | Desktop     | [16a30abb8e](https://linux-hardware.org/?probe=16a30abb8e) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [aacf668d6c](https://linux-hardware.org/?probe=aacf668d6c) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| HP            | 8754                        | Mini pc     | [869f3e6995](https://linux-hardware.org/?probe=869f3e6995) | Nov 18, 2023 |
| MSI           | N6105                       | Notebook    | [647e6d71a4](https://linux-hardware.org/?probe=647e6d71a4) | Nov 18, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [674a7d1154](https://linux-hardware.org/?probe=674a7d1154) | Nov 18, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [9a96aff4c7](https://linux-hardware.org/?probe=9a96aff4c7) | Nov 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [666f76f4e9](https://linux-hardware.org/?probe=666f76f4e9) | Nov 18, 2023 |
| Shuttle       | SW580                       | Desktop     | [31e6c1c2bf](https://linux-hardware.org/?probe=31e6c1c2bf) | Nov 18, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [10abd64eac](https://linux-hardware.org/?probe=10abd64eac) | Nov 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [fe873e258e](https://linux-hardware.org/?probe=fe873e258e) | Nov 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f25d22654a](https://linux-hardware.org/?probe=f25d22654a) | Nov 18, 2023 |
| Dell          | Latitude E6230              | Notebook    | [2a2d7c242e](https://linux-hardware.org/?probe=2a2d7c242e) | Nov 18, 2023 |
| HP            | Stream Notebook             | Notebook    | [5d318f7956](https://linux-hardware.org/?probe=5d318f7956) | Nov 18, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0fcb08b949](https://linux-hardware.org/?probe=0fcb08b949) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | Desktop     | [c475259455](https://linux-hardware.org/?probe=c475259455) | Nov 17, 2023 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [34b83fef89](https://linux-hardware.org/?probe=34b83fef89) | Nov 17, 2023 |
| BananaPi      | RK3568-BPI-R2PRO-PC HDMI... | Soc         | [9395029e63](https://linux-hardware.org/?probe=9395029e63) | Nov 17, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [95e4318549](https://linux-hardware.org/?probe=95e4318549) | Nov 17, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [416018ed84](https://linux-hardware.org/?probe=416018ed84) | Nov 17, 2023 |
| Irbis         | NB120                       | Notebook    | [a90949861b](https://linux-hardware.org/?probe=a90949861b) | Nov 17, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [6237baa616](https://linux-hardware.org/?probe=6237baa616) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | Desktop     | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [c8af1c096b](https://linux-hardware.org/?probe=c8af1c096b) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [026b13382d](https://linux-hardware.org/?probe=026b13382d) | Nov 17, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [be914025c2](https://linux-hardware.org/?probe=be914025c2) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11a05c0944](https://linux-hardware.org/?probe=11a05c0944) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | Notebook    | [f61bc8d881](https://linux-hardware.org/?probe=f61bc8d881) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3486cc9544](https://linux-hardware.org/?probe=3486cc9544) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | Notebook    | [53dd735333](https://linux-hardware.org/?probe=53dd735333) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [24ea543d99](https://linux-hardware.org/?probe=24ea543d99) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [893762777e](https://linux-hardware.org/?probe=893762777e) | Nov 17, 2023 |
| Supermicro    | X8DTH                       | Server      | [ac2b5e4a3d](https://linux-hardware.org/?probe=ac2b5e4a3d) | Nov 17, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [05634e2369](https://linux-hardware.org/?probe=05634e2369) | Nov 17, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [bea2b1a0b7](https://linux-hardware.org/?probe=bea2b1a0b7) | Nov 17, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [04206b8a50](https://linux-hardware.org/?probe=04206b8a50) | Nov 17, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [8031c90846](https://linux-hardware.org/?probe=8031c90846) | Nov 17, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [b0eba2e921](https://linux-hardware.org/?probe=b0eba2e921) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | Notebook    | [ba85d81d10](https://linux-hardware.org/?probe=ba85d81d10) | Nov 16, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [604f785353](https://linux-hardware.org/?probe=604f785353) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | Notebook    | [b2c3886395](https://linux-hardware.org/?probe=b2c3886395) | Nov 16, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [5b38f976c4](https://linux-hardware.org/?probe=5b38f976c4) | Nov 16, 2023 |
| Intel         | NUC7i5DNB J57626-507        | Mini pc     | [110973f4a4](https://linux-hardware.org/?probe=110973f4a4) | Nov 16, 2023 |
| LG Electro... | 22V30R FAB1                 | All in one  | [868b385080](https://linux-hardware.org/?probe=868b385080) | Nov 16, 2023 |
| Aquarius      | Catfish AQC624CF            | Server      | [2f79afe06c](https://linux-hardware.org/?probe=2f79afe06c) | Nov 16, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [0331447937](https://linux-hardware.org/?probe=0331447937) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [9ac3245bda](https://linux-hardware.org/?probe=9ac3245bda) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [e66475e9e4](https://linux-hardware.org/?probe=e66475e9e4) | Nov 16, 2023 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [54383b8394](https://linux-hardware.org/?probe=54383b8394) | Nov 16, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [b166167703](https://linux-hardware.org/?probe=b166167703) | Nov 16, 2023 |
| NZXT          | N7 B650E                    | Desktop     | [588de38c13](https://linux-hardware.org/?probe=588de38c13) | Nov 16, 2023 |
| Dell          | Latitude 5530               | Notebook    | [4490ae8afe](https://linux-hardware.org/?probe=4490ae8afe) | Nov 16, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [7f136c3e39](https://linux-hardware.org/?probe=7f136c3e39) | Nov 16, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [23bd3ec971](https://linux-hardware.org/?probe=23bd3ec971) | Nov 16, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [494b815098](https://linux-hardware.org/?probe=494b815098) | Nov 16, 2023 |
| Dell          | Latitude 3320               | Notebook    | [19a9472e3c](https://linux-hardware.org/?probe=19a9472e3c) | Nov 16, 2023 |
| Dell          | Latitude 3320               | Notebook    | [285ad2f27a](https://linux-hardware.org/?probe=285ad2f27a) | Nov 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [496e69e1e4](https://linux-hardware.org/?probe=496e69e1e4) | Nov 16, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [3c8c80409b](https://linux-hardware.org/?probe=3c8c80409b) | Nov 15, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [07a1bedd9b](https://linux-hardware.org/?probe=07a1bedd9b) | Nov 15, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2e59ea85e9](https://linux-hardware.org/?probe=2e59ea85e9) | Nov 15, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [a21066a759](https://linux-hardware.org/?probe=a21066a759) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [182484eef8](https://linux-hardware.org/?probe=182484eef8) | Nov 15, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1c21a56b5c](https://linux-hardware.org/?probe=1c21a56b5c) | Nov 15, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3f0b4a0bfe](https://linux-hardware.org/?probe=3f0b4a0bfe) | Nov 15, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d2cafb1814](https://linux-hardware.org/?probe=d2cafb1814) | Nov 15, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [477b965e66](https://linux-hardware.org/?probe=477b965e66) | Nov 15, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [694833562c](https://linux-hardware.org/?probe=694833562c) | Nov 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7404738ed](https://linux-hardware.org/?probe=a7404738ed) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | Notebook    | [1eb15d0477](https://linux-hardware.org/?probe=1eb15d0477) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [98dd1a4a4f](https://linux-hardware.org/?probe=98dd1a4a4f) | Nov 15, 2023 |
| Supermicro    | X11SPM-F                    | Server      | [fa3fb34e95](https://linux-hardware.org/?probe=fa3fb34e95) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [e91aa41101](https://linux-hardware.org/?probe=e91aa41101) | Nov 15, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [7bfb7a76bb](https://linux-hardware.org/?probe=7bfb7a76bb) | Nov 15, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b259a4a4bd](https://linux-hardware.org/?probe=b259a4a4bd) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| Lenovo        | ThinkPad X280 20KES5840A    | Notebook    | [8800b951d8](https://linux-hardware.org/?probe=8800b951d8) | Nov 14, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [1d0338a823](https://linux-hardware.org/?probe=1d0338a823) | Nov 14, 2023 |
| Phoenix/Si... | M730SR                      | Notebook    | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [e90f4e1799](https://linux-hardware.org/?probe=e90f4e1799) | Nov 14, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [6dbb14b567](https://linux-hardware.org/?probe=6dbb14b567) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [bdac7a70aa](https://linux-hardware.org/?probe=bdac7a70aa) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ec3e7b63cb](https://linux-hardware.org/?probe=ec3e7b63cb) | Nov 14, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [4470b846a0](https://linux-hardware.org/?probe=4470b846a0) | Nov 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [01ce54e1ed](https://linux-hardware.org/?probe=01ce54e1ed) | Nov 14, 2023 |
| Acer          | Extensa 2540                | Notebook    | [22e65d0a5b](https://linux-hardware.org/?probe=22e65d0a5b) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | Notebook    | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c5f890cb08](https://linux-hardware.org/?probe=c5f890cb08) | Nov 14, 2023 |
| Dell          | 0FJM8V A03                  | Server      | [358c84ceae](https://linux-hardware.org/?probe=358c84ceae) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [c505d16c82](https://linux-hardware.org/?probe=c505d16c82) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [e0349fcb14](https://linux-hardware.org/?probe=e0349fcb14) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [f7a8d7d27e](https://linux-hardware.org/?probe=f7a8d7d27e) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [149bf90d88](https://linux-hardware.org/?probe=149bf90d88) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [1b4972f4e1](https://linux-hardware.org/?probe=1b4972f4e1) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [7d0e39fe9f](https://linux-hardware.org/?probe=7d0e39fe9f) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [f9bfe70cef](https://linux-hardware.org/?probe=f9bfe70cef) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [af04867373](https://linux-hardware.org/?probe=af04867373) | Nov 14, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [edc5aa4d33](https://linux-hardware.org/?probe=edc5aa4d33) | Nov 13, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [d44803c611](https://linux-hardware.org/?probe=d44803c611) | Nov 13, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [42d05f19a2](https://linux-hardware.org/?probe=42d05f19a2) | Nov 13, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [57e4a13fab](https://linux-hardware.org/?probe=57e4a13fab) | Nov 13, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [63e36c8c1e](https://linux-hardware.org/?probe=63e36c8c1e) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [137d579104](https://linux-hardware.org/?probe=137d579104) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [aacc7d1f61](https://linux-hardware.org/?probe=aacc7d1f61) | Nov 13, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [429add2d41](https://linux-hardware.org/?probe=429add2d41) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| WanYou        | WanYouChunXiao              | Desktop     | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| HP            | Presario CQ57               | Notebook    | [0d4999d483](https://linux-hardware.org/?probe=0d4999d483) | Nov 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [fe2966d899](https://linux-hardware.org/?probe=fe2966d899) | Nov 13, 2023 |
| ASRock        | QC5000-ITX/PH               | Desktop     | [983df9a44c](https://linux-hardware.org/?probe=983df9a44c) | Nov 13, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [3c0f8e3cdd](https://linux-hardware.org/?probe=3c0f8e3cdd) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8b8d073259](https://linux-hardware.org/?probe=8b8d073259) | Nov 13, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [189c917237](https://linux-hardware.org/?probe=189c917237) | Nov 13, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [960b3732b0](https://linux-hardware.org/?probe=960b3732b0) | Nov 13, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [0d2accfed1](https://linux-hardware.org/?probe=0d2accfed1) | Nov 13, 2023 |
| Supermicro    | X13SAE-F                    | Server      | [aa50e2cf9c](https://linux-hardware.org/?probe=aa50e2cf9c) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fa552b9901](https://linux-hardware.org/?probe=fa552b9901) | Nov 13, 2023 |
| Lenovo        | 3744 WIN SDK0T76466 3424... | All in one  | [765a9d56c1](https://linux-hardware.org/?probe=765a9d56c1) | Nov 12, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [bbc6a54b40](https://linux-hardware.org/?probe=bbc6a54b40) | Nov 12, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [27f69cd90a](https://linux-hardware.org/?probe=27f69cd90a) | Nov 12, 2023 |
| Google        | Hanawl                      | Notebook    | [39b8f28b8e](https://linux-hardware.org/?probe=39b8f28b8e) | Nov 12, 2023 |
| Google        | Hana                        | Notebook    | [80ae861cdf](https://linux-hardware.org/?probe=80ae861cdf) | Nov 12, 2023 |
| Google        | cozmo                       | Soc         | [71a554097a](https://linux-hardware.org/?probe=71a554097a) | Nov 12, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [539da3b61a](https://linux-hardware.org/?probe=539da3b61a) | Nov 12, 2023 |
| Google        | Akemi                       | Notebook    | [c0722184e7](https://linux-hardware.org/?probe=c0722184e7) | Nov 12, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [02a5498c27](https://linux-hardware.org/?probe=02a5498c27) | Nov 12, 2023 |
| Lenovo        | ThinkPad Edge E535 32607... | Notebook    | [f5bea4eb8b](https://linux-hardware.org/?probe=f5bea4eb8b) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [929afc7ae1](https://linux-hardware.org/?probe=929afc7ae1) | Nov 12, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfd502b2af](https://linux-hardware.org/?probe=dfd502b2af) | Nov 12, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [d3d9b9a9ba](https://linux-hardware.org/?probe=d3d9b9a9ba) | Nov 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3b86ff657d](https://linux-hardware.org/?probe=3b86ff657d) | Nov 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fa8b97688](https://linux-hardware.org/?probe=2fa8b97688) | Nov 12, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [26e08a35c7](https://linux-hardware.org/?probe=26e08a35c7) | Nov 12, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d3fd2f491d](https://linux-hardware.org/?probe=d3fd2f491d) | Nov 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [e89b871c81](https://linux-hardware.org/?probe=e89b871c81) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [d61e9c84e5](https://linux-hardware.org/?probe=d61e9c84e5) | Nov 12, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [b310ceb608](https://linux-hardware.org/?probe=b310ceb608) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e086a0153d](https://linux-hardware.org/?probe=e086a0153d) | Nov 12, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [15601ebf87](https://linux-hardware.org/?probe=15601ebf87) | Nov 12, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [d15a200351](https://linux-hardware.org/?probe=d15a200351) | Nov 11, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [a0230d58fd](https://linux-hardware.org/?probe=a0230d58fd) | Nov 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d49ee32dd4](https://linux-hardware.org/?probe=d49ee32dd4) | Nov 11, 2023 |
| HP            | 15                          | Notebook    | [dbd704fdbb](https://linux-hardware.org/?probe=dbd704fdbb) | Nov 11, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [e713ed7256](https://linux-hardware.org/?probe=e713ed7256) | Nov 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [d77b36d8b7](https://linux-hardware.org/?probe=d77b36d8b7) | Nov 11, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [f08c831e30](https://linux-hardware.org/?probe=f08c831e30) | Nov 11, 2023 |
| ASUSTek       | TS10                        | Desktop     | [c35ca1dadb](https://linux-hardware.org/?probe=c35ca1dadb) | Nov 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [3da6dfb4b3](https://linux-hardware.org/?probe=3da6dfb4b3) | Nov 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 6806      | 52.69%  |
| Debian 12                       | 2527      | 19.56%  |
| Debian 10                       | 1787      | 13.84%  |
| Debian Testing                  | 644       | 4.99%   |
| Debian                          | 415       | 3.21%   |
| Debian 9                        | 324       | 2.51%   |
| Debian Unstable                 | 263       | 2.04%   |
| Debian 11-updates               | 47        | 0.36%   |
| Debian 8                        | 40        | 0.31%   |
| Debian Testing/unstable         | 31        | 0.24%   |
| Debian Sid                      | 7         | 0.05%   |
| Debian 23                       | 7         | 0.05%   |
| Debian 7                        | 5         | 0.04%   |
| Debian Testing-proposed-updates | 3         | 0.02%   |
| Debian 6                        | 3         | 0.02%   |
| Debian 22                       | 3         | 0.02%   |
| Debian 12-updates               | 2         | 0.02%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 23100609                 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 12208     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 983       | 6.93%   |
| 5.10.0-7-amd64  | 691       | 4.87%   |
| 5.10.0-10-amd64 | 578       | 4.07%   |
| 6.1.0-13-amd64  | 531       | 3.74%   |
| 5.10.0-21-amd64 | 478       | 3.37%   |
| 5.10.0-20-amd64 | 375       | 2.64%   |
| 5.10.0-16-amd64 | 372       | 2.62%   |
| 5.10.0-9-amd64  | 330       | 2.33%   |
| 6.1.0-10-amd64  | 304       | 2.14%   |
| 6.1.0-9-amd64   | 302       | 2.13%   |
| 5.10.0-19-amd64 | 294       | 2.07%   |
| 5.10.0-18-amd64 | 294       | 2.07%   |
| 6.1.0-11-amd64  | 290       | 2.04%   |
| 5.10.0-13-amd64 | 265       | 1.87%   |
| 6.1.0-4-amd64   | 226       | 1.59%   |
| 5.10.0-23-amd64 | 215       | 1.52%   |
| 6.1.0-12-amd64  | 206       | 1.45%   |
| 5.10.0-11-amd64 | 196       | 1.38%   |
| 5.10.0-2-amd64  | 167       | 1.18%   |
| 4.19.0-6-amd64  | 145       | 1.02%   |
| 4.19.0-9-amd64  | 143       | 1.01%   |
| 5.10.0-14-amd64 | 142       | 1%      |
| 6.1.0-16-amd64  | 129       | 0.91%   |
| 5.10.0-17-amd64 | 127       | 0.9%    |
| 4.19.0-13-amd64 | 125       | 0.88%   |
| 4.19.0-8-amd64  | 120       | 0.85%   |
| 4.19.0-16-amd64 | 110       | 0.78%   |
| 5.10.0-15-amd64 | 109       | 0.77%   |
| 5.10.0-22-amd64 | 107       | 0.75%   |
| 4.19.0-14-amd64 | 104       | 0.73%   |
| 5.15.0-2-amd64  | 96        | 0.68%   |
| 6.1.0-7-amd64   | 95        | 0.67%   |
| 4.19.0-17-amd64 | 94        | 0.66%   |
| 4.19.0-10-amd64 | 92        | 0.65%   |
| 4.19.0-12-amd64 | 88        | 0.62%   |
| 5.10.0-12-amd64 | 74        | 0.52%   |
| 4.9.0-8-amd64   | 70        | 0.49%   |
| 5.10.0-6-amd64  | 66        | 0.47%   |
| 5.10.0-26-amd64 | 64        | 0.45%   |
| 6.0.0-6-amd64   | 53        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 5869      | 44.11%  |
| 6.1.0    | 2356      | 17.71%  |
| 4.19.0   | 1261      | 9.48%   |
| 6.0.0    | 264       | 1.98%   |
| 4.9.0    | 242       | 1.82%   |
| 5.18.0   | 201       | 1.51%   |
| 5.15.0   | 169       | 1.27%   |
| 5.9.0    | 150       | 1.13%   |
| 5.16.0   | 137       | 1.03%   |
| 6.5.0    | 133       | 1%      |
| 5.19.0   | 123       | 0.92%   |
| 5.7.0    | 121       | 0.91%   |
| 5.8.0    | 120       | 0.9%    |
| 5.4.0    | 118       | 0.89%   |
| 5.6.0    | 100       | 0.75%   |
| 6.2.16   | 97        | 0.73%   |
| 5.14.0   | 92        | 0.69%   |
| 6.4.0    | 84        | 0.63%   |
| 5.17.0   | 71        | 0.53%   |
| 5.13.19  | 60        | 0.45%   |
| 6.3.0    | 54        | 0.41%   |
| 5.3.0    | 39        | 0.29%   |
| 5.15.107 | 35        | 0.26%   |
| 5.10.10  | 35        | 0.26%   |
| 6.1.21   | 32        | 0.24%   |
| 5.5.0    | 32        | 0.24%   |
| 5.15.74  | 32        | 0.24%   |
| 6.5.11   | 30        | 0.23%   |
| 5.11.22  | 28        | 0.21%   |
| 5.2.0    | 21        | 0.16%   |
| 5.15.85  | 21        | 0.16%   |
| 4.18.0   | 21        | 0.16%   |
| 5.15.84  | 20        | 0.15%   |
| 5.15.102 | 20        | 0.15%   |
| 3.16.0   | 20        | 0.15%   |
| 5.15.83  | 19        | 0.14%   |
| 5.15.32  | 19        | 0.14%   |
| 5.15.39  | 18        | 0.14%   |
| 5.15.30  | 18        | 0.14%   |
| 5.15.35  | 17        | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 6033      | 45.58%  |
| 6.1     | 2457      | 18.56%  |
| 4.19    | 1281      | 9.68%   |
| 5.15    | 511       | 3.86%   |
| 6.0     | 285       | 2.15%   |
| 4.9     | 255       | 1.93%   |
| 5.4     | 222       | 1.68%   |
| 5.18    | 214       | 1.62%   |
| 6.5     | 178       | 1.34%   |
| 5.9     | 159       | 1.2%    |
| 5.16    | 150       | 1.13%   |
| 5.19    | 144       | 1.09%   |
| 5.8     | 132       | 1%      |
| 6.2     | 130       | 0.98%   |
| 5.7     | 129       | 0.97%   |
| 5.6     | 110       | 0.83%   |
| 6.4     | 108       | 0.82%   |
| 5.14    | 102       | 0.77%   |
| 5.17    | 86        | 0.65%   |
| 5.13    | 83        | 0.63%   |
| 6.3     | 67        | 0.51%   |
| 5.3     | 66        | 0.5%    |
| 5.11    | 51        | 0.39%   |
| 5.5     | 38        | 0.29%   |
| 6.6     | 30        | 0.23%   |
| 5.2     | 27        | 0.2%    |
| 4.18    | 22        | 0.17%   |
| 3.16    | 20        | 0.15%   |
| 4.15    | 19        | 0.14%   |
| 5.12    | 16        | 0.12%   |
| 5.0     | 13        | 0.1%    |
| 4.4     | 13        | 0.1%    |
| 5       | 11        | 0.08%   |
| 4.14    | 9         | 0.07%   |
| 4.17    | 8         | 0.06%   |
| 4.1     | 8         | 0.06%   |
| 5.1     | 6         | 0.05%   |
| 6       | 4         | 0.03%   |
| 3.10    | 4         | 0.03%   |
| 4.8     | 3         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 11445     | 93.73%  |
| i686        | 353       | 2.89%   |
| aarch64     | 307       | 2.51%   |
| armv7l      | 65        | 0.53%   |
| riscv64     | 19        | 0.16%   |
| ppc64       | 7         | 0.06%   |
| mips64      | 3         | 0.02%   |
| i586        | 3         | 0.02%   |
| ppc64le     | 2         | 0.02%   |
| loongarch64 | 2         | 0.02%   |
| sparc64     | 1         | 0.01%   |
| sh4a        | 1         | 0.01%   |
| i486        | 1         | 0.01%   |
| armv6l      | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 3631      | 29.02%  |
| GNOME             | 3046      | 24.34%  |
| KDE5              | 1672      | 13.36%  |
| XFCE              | 1505      | 12.03%  |
| MATE              | 522       | 4.17%   |
| X-Cinnamon        | 453       | 3.62%   |
| LXDE              | 383       | 3.06%   |
| Cinnamon          | 317       | 2.53%   |
| KDE               | 221       | 1.77%   |
| LXQt              | 190       | 1.52%   |
| i3                | 163       | 1.3%    |
| Openbox           | 72        | 0.58%   |
| GNOME Flashback   | 71        | 0.57%   |
| lightdm-xsession  | 50        | 0.4%    |
| Budgie            | 36        | 0.29%   |
| GNOME Classic     | 35        | 0.28%   |
| trinity           | 30        | 0.24%   |
| awesome           | 11        | 0.09%   |
| sway              | 10        | 0.08%   |
| fluxbox           | 8         | 0.06%   |
| GNUstep           | 7         | 0.06%   |
| Enlightenment     | 7         | 0.06%   |
| DWM               | 7         | 0.06%   |
| LXDE-pi-wayfire   | 6         | 0.05%   |
| KDE4              | 6         | 0.05%   |
| x-session-manager | 5         | 0.04%   |
| bspwm             | 5         | 0.04%   |
| Unity             | 4         | 0.03%   |
| Phosh:GNOME       | 4         | 0.03%   |
| ICEWM             | 4         | 0.03%   |
| Cutefish          | 4         | 0.03%   |
| xmonad            | 3         | 0.02%   |
| default           | 3         | 0.02%   |
| BunsenLabs        | 3         | 0.02%   |
| fvwm              | 2         | 0.02%   |
| Deepin            | 2         | 0.02%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| TOS:GNOME         | 1         | 0.01%   |
| qtile             | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 6375      | 51.12%  |
| Wayland     | 2352      | 18.86%  |
| Unknown     | 2325      | 18.64%  |
| Tty         | 1405      | 11.27%  |
| Web         | 7         | 0.06%   |
| Unspecified | 6         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5449      | 43.57%  |
| LightDM | 2147      | 17.17%  |
| GDM     | 1659      | 13.27%  |
| SDDM    | 1476      | 11.8%   |
| GDM3    | 990       | 7.92%   |
| TDM     | 600       | 4.8%    |
| NODM    | 51        | 0.41%   |
| XDM     | 45        | 0.36%   |
| SLiM    | 36        | 0.29%   |
| LXDM    | 20        | 0.16%   |
| KDM     | 15        | 0.12%   |
| Ly      | 6         | 0.05%   |
| GREETD  | 5         | 0.04%   |
| WDM     | 4         | 0.03%   |
| SU      | 2         | 0.02%   |
| LDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4330      | 34.91%  |
| Unknown | 1551      | 12.5%   |
| ru_RU   | 1336      | 10.77%  |
| de_DE   | 790       | 6.37%   |
| en_GB   | 644       | 5.19%   |
| fr_FR   | 639       | 5.15%   |
| pt_BR   | 362       | 2.92%   |
| es_ES   | 331       | 2.67%   |
| it_IT   | 297       | 2.39%   |
| C       | 194       | 1.56%   |
| pl_PL   | 180       | 1.45%   |
| en_CA   | 169       | 1.36%   |
| en_AU   | 151       | 1.22%   |
| zh_CN   | 91        | 0.73%   |
| en_IN   | 88        | 0.71%   |
| es_MX   | 87        | 0.7%    |
| es_AR   | 75        | 0.6%    |
| en_IE   | 66        | 0.53%   |
| hu_HU   | 59        | 0.48%   |
| es_VE   | 48        | 0.39%   |
| sv_SE   | 46        | 0.37%   |
| es_CL   | 46        | 0.37%   |
| de_CH   | 46        | 0.37%   |
| de_AT   | 44        | 0.35%   |
| en_ZA   | 38        | 0.31%   |
| pt_PT   | 37        | 0.3%    |
| nl_NL   | 37        | 0.3%    |
| ja_JP   | 36        | 0.29%   |
| cs_CZ   | 33        | 0.27%   |
| en_NZ   | 31        | 0.25%   |
| fi_FI   | 30        | 0.24%   |
| fr_BE   | 26        | 0.21%   |
| nl_BE   | 23        | 0.19%   |
| es_CO   | 23        | 0.19%   |
| tr_TR   | 21        | 0.17%   |
| ca_ES   | 21        | 0.17%   |
| fr_CH   | 20        | 0.16%   |
| ru_UA   | 17        | 0.14%   |
| zh_TW   | 16        | 0.13%   |
| ko_KR   | 16        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 6697      | 54.18%  |
| BIOS | 5663      | 45.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 8906      | 72.26%  |
| Overlay    | 2200      | 17.85%  |
| Btrfs      | 465       | 3.77%   |
| Zfs        | 205       | 1.66%   |
| Unknown    | 172       | 1.4%    |
| Xfs        | 149       | 1.21%   |
| Tmpfs      | 89        | 0.72%   |
| Rootfs     | 47        | 0.38%   |
| Ext3       | 37        | 0.3%    |
| Ext2       | 30        | 0.24%   |
| F2fs       | 8         | 0.06%   |
| Aufs       | 8         | 0.06%   |
| Jfs        | 3         | 0.02%   |
| XXXXXXX    | 2         | 0.02%   |
| Ubifs      | 2         | 0.02%   |
| XXXXX      | 1         | 0.01%   |
| Fuse.sshfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 7117      | 57.34%  |
| MBR     | 2952      | 23.79%  |
| Unknown | 2342      | 18.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10214     | 82.46%  |
| Yes       | 2173      | 17.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8808      | 71.34%  |
| Yes       | 3538      | 28.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1843      | 15.1%   |
| Lenovo                  | 1804      | 14.78%  |
| Hewlett-Packard         | 1374      | 11.25%  |
| Dell                    | 1300      | 10.65%  |
| Gigabyte Technology     | 794       | 6.5%    |
| Apple                   | 786       | 6.44%   |
| MSI                     | 611       | 5%      |
| Acer                    | 488       | 4%      |
| ASRock                  | 450       | 3.69%   |
| Intel                   | 280       | 2.29%   |
| Unknown                 | 213       | 1.74%   |
| Google                  | 211       | 1.73%   |
| Raspberry Pi Foundation | 194       | 1.59%   |
| Supermicro              | 131       | 1.07%   |
| Toshiba                 | 105       | 0.86%   |
| Samsung Electronics     | 97        | 0.79%   |
| Fujitsu                 | 94        | 0.77%   |
| ECS                     | 59        | 0.48%   |
| AZW                     | 59        | 0.48%   |
| HUAWEI                  | 58        | 0.48%   |
| Aquarius                | 52        | 0.43%   |
| Sony                    | 50        | 0.41%   |
| Foxconn                 | 44        | 0.36%   |
| ASRockRack              | 41        | 0.34%   |
| Notebook                | 33        | 0.27%   |
| Medion                  | 33        | 0.27%   |
| Positivo                | 30        | 0.25%   |
| Biostar                 | 30        | 0.25%   |
| Pegatron                | 28        | 0.23%   |
| IBM                     | 26        | 0.21%   |
| AMI                     | 26        | 0.21%   |
| Microsoft               | 25        | 0.2%    |
| Packard Bell            | 23        | 0.19%   |
| Alienware               | 23        | 0.19%   |
| sunxi                   | 21        | 0.17%   |
| Fujitsu Siemens         | 21        | 0.17%   |
| BESSTAR Tech            | 21        | 0.17%   |
| Shuttle                 | 19        | 0.16%   |
| Panasonic               | 17        | 0.14%   |
| Inventec                | 17        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 355       | 2.91%   |
| Unknown                                   | 253       | 2.07%   |
| ASUS All Series                           | 141       | 1.15%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 0.93%   |
| Apple MacBookAir7,2                       | 81        | 0.66%   |
| Apple MacBookAir7,1                       | 77        | 0.63%   |
| Google Enguarde                           | 74        | 0.61%   |
| Apple MacBook2,1                          | 58        | 0.48%   |
| ASUS S20 K29                              | 55        | 0.45%   |
| Aquarius NS585                            | 48        | 0.39%   |
| MSI MS-7996                               | 45        | 0.37%   |
| Google Reks                               | 45        | 0.37%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 38        | 0.31%   |
| Supermicro Super Server                   | 31        | 0.25%   |
| HP Notebook                               | 28        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 27        | 0.22%   |
| MSI MS-7817                               | 27        | 0.22%   |
| ECS G31T-M9                               | 25        | 0.2%    |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 24        | 0.2%    |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 24        | 0.2%    |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.2%    |
| Google Terra                              | 24        | 0.2%    |
| Gigabyte H81M-S2V                         | 24        | 0.2%    |
| Apple MacBook4,1                          | 23        | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 22        | 0.18%   |
| Dell OptiPlex 7010                        | 21        | 0.17%   |
| ASUS PRIME H510M-A                        | 20        | 0.16%   |
| ASRock H470M-HVS                          | 20        | 0.16%   |
| Gigabyte B450M DS3H                       | 19        | 0.16%   |
| ASUS TUF Gaming X570-PLUS                 | 19        | 0.16%   |
| HP Pavilion g6                            | 18        | 0.15%   |
| ASUS PRIME A320M-K                        | 18        | 0.15%   |
| ECS H61H2-M13                             | 17        | 0.14%   |
| Acer Aspire A315-23                       | 17        | 0.14%   |
| RPi Raspberry Pi                          | 16        | 0.13%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.13%   |
| Gigabyte H410M S2H                        | 16        | 0.13%   |
| ASUS P8H61-M LX3 R2.0                     | 16        | 0.13%   |
| ASUS H110M-R                              | 16        | 0.13%   |
| MSI MS-7B79                               | 15        | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1058      | 8.67%   |
| Apple MacBook5     | 357       | 2.92%   |
| Dell Latitude      | 350       | 2.87%   |
| Acer Aspire        | 310       | 2.54%   |
| Dell Inspiron      | 283       | 2.32%   |
| ASUS PRIME         | 269       | 2.2%    |
| Unknown            | 253       | 2.07%   |
| Lenovo IdeaPad     | 242       | 1.98%   |
| HP EliteBook       | 203       | 1.66%   |
| RPi Raspberry      | 194       | 1.59%   |
| Dell OptiPlex      | 175       | 1.43%   |
| HP Pavilion        | 170       | 1.39%   |
| Apple MacBookAir7  | 158       | 1.29%   |
| ASUS ROG           | 150       | 1.23%   |
| ASUS All           | 141       | 1.15%   |
| HP ProBook         | 135       | 1.11%   |
| HP Laptop          | 133       | 1.09%   |
| Dell Precision     | 129       | 1.06%   |
| Dell XPS           | 125       | 1.02%   |
| HP Compaq          | 122       | 1%      |
| Lenovo ThinkCentre | 115       | 0.94%   |
| ASUS VivoBook      | 101       | 0.83%   |
| ASUS TUF           | 99        | 0.81%   |
| Dell Vostro        | 90        | 0.74%   |
| Dell PowerEdge     | 87        | 0.71%   |
| Toshiba Satellite  | 82        | 0.67%   |
| Google Enguarde    | 74        | 0.61%   |
| HP ProLiant        | 62        | 0.51%   |
| Apple MacBook2     | 58        | 0.48%   |
| Lenovo Yoga        | 55        | 0.45%   |
| ASUS S20           | 55        | 0.45%   |
| ASUS ASUS          | 50        | 0.41%   |
| HP ENVY            | 49        | 0.4%    |
| HP EliteDesk       | 48        | 0.39%   |
| Aquarius NS585     | 48        | 0.39%   |
| MSI MS-7996        | 45        | 0.37%   |
| Lenovo Legion      | 45        | 0.37%   |
| Google Reks        | 45        | 0.37%   |
| Gigabyte B450M     | 45        | 0.37%   |
| ASUS ZenBook       | 43        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 1228      | 10.06%  |
| 2019    | 991       | 8.12%   |
| 2021    | 987       | 8.08%   |
| 2018    | 952       | 7.8%    |
| 2012    | 845       | 6.92%   |
| 2009    | 774       | 6.34%   |
| 2013    | 698       | 5.72%   |
| 2017    | 692       | 5.67%   |
| 2011    | 682       | 5.59%   |
| 2022    | 654       | 5.36%   |
| 2016    | 609       | 4.99%   |
| 2014    | 586       | 4.8%    |
| 2015    | 534       | 4.37%   |
| 2010    | 455       | 3.73%   |
| Unknown | 366       | 3%      |
| 2007    | 363       | 2.97%   |
| 2008    | 350       | 2.87%   |
| 2023    | 248       | 2.03%   |
| 2006    | 87        | 0.71%   |
| 2005    | 53        | 0.43%   |
| 2004    | 26        | 0.21%   |
| 2003    | 17        | 0.14%   |
| 2002    | 4         | 0.03%   |
| 2001    | 3         | 0.02%   |
| 2024    | 2         | 0.02%   |
| 2000    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6124      | 50.16%  |
| Desktop        | 4659      | 38.16%  |
| System on chip | 336       | 2.75%   |
| Convertible    | 326       | 2.67%   |
| Mini pc        | 293       | 2.4%    |
| Server         | 272       | 2.23%   |
| All in one     | 112       | 0.92%   |
| Tablet         | 70        | 0.57%   |
| Phone          | 11        | 0.09%   |
| Other          | 2         | 0.02%   |
| Stick pc       | 2         | 0.02%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 11557     | 94.15%  |
| Enabled  | 718       | 5.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11975     | 98.08%  |
| Yes  | 234       | 1.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2599      | 20.84%  |
| 16.01-24.0      | 2321      | 18.61%  |
| 3.01-4.0        | 2046      | 16.41%  |
| 8.01-16.0       | 1987      | 15.93%  |
| 32.01-64.0      | 1244      | 9.98%   |
| 1.01-2.0        | 874       | 7.01%   |
| 64.01-256.0     | 625       | 5.01%   |
| 24.01-32.0      | 229       | 1.84%   |
| 2.01-3.0        | 220       | 1.76%   |
| 0.51-1.0        | 196       | 1.57%   |
| 0.01-0.5        | 56        | 0.45%   |
| More than 256.0 | 53        | 0.42%   |
| Unknown         | 19        | 0.15%   |
| 0               | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 3851      | 29.22%  |
| 2.01-3.0        | 2476      | 18.78%  |
| 4.01-8.0        | 1937      | 14.7%   |
| 0.51-1.0        | 1816      | 13.78%  |
| 3.01-4.0        | 1432      | 10.86%  |
| 8.01-16.0       | 654       | 4.96%   |
| 0.01-0.5        | 588       | 4.46%   |
| 16.01-24.0      | 176       | 1.34%   |
| 32.01-64.0      | 96        | 0.73%   |
| 24.01-32.0      | 74        | 0.56%   |
| 64.01-256.0     | 49        | 0.37%   |
| Unknown         | 28        | 0.21%   |
| More than 256.0 | 3         | 0.02%   |
| 0               | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7741      | 61.94%  |
| 2       | 2643      | 21.15%  |
| 3       | 880       | 7.04%   |
| 4       | 495       | 3.96%   |
| 5       | 231       | 1.85%   |
| 6       | 138       | 1.1%    |
| 0       | 102       | 0.82%   |
| 7       | 81        | 0.65%   |
| 8       | 58        | 0.46%   |
| 9       | 35        | 0.28%   |
| 10      | 20        | 0.16%   |
| 13      | 12        | 0.1%    |
| 11      | 10        | 0.08%   |
| 12      | 9         | 0.07%   |
| 14      | 7         | 0.06%   |
| 19      | 4         | 0.03%   |
| 16      | 4         | 0.03%   |
| 21      | 3         | 0.02%   |
| 17      | 3         | 0.02%   |
| Unknown | 3         | 0.02%   |
| 29      | 2         | 0.02%   |
| 28      | 2         | 0.02%   |
| 27      | 2         | 0.02%   |
| 26      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 79      | 1         | 0.01%   |
| 70      | 1         | 0.01%   |
| 47      | 1         | 0.01%   |
| 46      | 1         | 0.01%   |
| 32      | 1         | 0.01%   |
| 23      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8492      | 69.18%  |
| Yes       | 3784      | 30.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10526     | 86.01%  |
| No        | 1712      | 13.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8329      | 67.95%  |
| No        | 3929      | 32.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6881      | 55.9%   |
| No        | 5428      | 44.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2557      | 20.84%  |
| Russia       | 1590      | 12.96%  |
| Germany      | 1252      | 10.21%  |
| France       | 818       | 6.67%   |
| Brazil       | 552       | 4.5%    |
| Spain        | 477       | 3.89%   |
| Italy        | 462       | 3.77%   |
| UK           | 352       | 2.87%   |
| Canada       | 310       | 2.53%   |
| Poland       | 292       | 2.38%   |
| Netherlands  | 206       | 1.68%   |
| Australia    | 198       | 1.61%   |
| Switzerland  | 190       | 1.55%   |
| China        | 167       | 1.36%   |
| Mexico       | 148       | 1.21%   |
| Sweden       | 133       | 1.08%   |
| India        | 128       | 1.04%   |
| Austria      | 121       | 0.99%   |
| Argentina    | 118       | 0.96%   |
| Belgium      | 111       | 0.9%    |
| Hungary      | 106       | 0.86%   |
| Ukraine      | 105       | 0.86%   |
| Finland      | 91        | 0.74%   |
| Czechia      | 91        | 0.74%   |
| Portugal     | 89        | 0.73%   |
| Turkey       | 86        | 0.7%    |
| Norway       | 74        | 0.6%    |
| Romania      | 63        | 0.51%   |
| Greece       | 61        | 0.5%    |
| Japan        | 59        | 0.48%   |
| Chile        | 57        | 0.46%   |
| Venezuela    | 56        | 0.46%   |
| Bulgaria     | 53        | 0.43%   |
| Ireland      | 49        | 0.4%    |
| South Africa | 48        | 0.39%   |
| Denmark      | 48        | 0.39%   |
| Indonesia    | 46        | 0.37%   |
| New Zealand  | 43        | 0.35%   |
| Colombia     | 43        | 0.35%   |
| Slovakia     | 40        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 857       | 6.64%   |
| Bangor            | 824       | 6.38%   |
| Dover-Foxcroft    | 304       | 2.35%   |
| Moscow            | 199       | 1.54%   |
| St Petersburg     | 150       | 1.16%   |
| Paris             | 130       | 1.01%   |
| Berlin            | 103       | 0.8%    |
| Vienna            | 81        | 0.63%   |
| Sao Paulo         | 79        | 0.61%   |
| Madrid            | 76        | 0.59%   |
| Seville           | 66        | 0.51%   |
| Milan             | 66        | 0.51%   |
| Zurich            | 64        | 0.5%    |
| Warsaw            | 61        | 0.47%   |
| Amsterdam         | 59        | 0.46%   |
| Sydney            | 56        | 0.43%   |
| Munich            | 53        | 0.41%   |
| Toronto           | 51        | 0.4%    |
| Hamburg           | 50        | 0.39%   |
| Frankfurt am Main | 50        | 0.39%   |
| Barcelona         | 49        | 0.38%   |
| Budapest          | 45        | 0.35%   |
| Roubaix           | 44        | 0.34%   |
| Perm              | 43        | 0.33%   |
| Prague            | 41        | 0.32%   |
| Rio de Janeiro    | 40        | 0.31%   |
| Helsinki          | 40        | 0.31%   |
| Melbourne         | 39        | 0.3%    |
| Falkenstein       | 37        | 0.29%   |
| London            | 36        | 0.28%   |
| Cologne           | 36        | 0.28%   |
| Dublin            | 35        | 0.27%   |
| Brisbane          | 34        | 0.26%   |
| Brasília         | 34        | 0.26%   |
| Rome              | 33        | 0.26%   |
| Athens            | 33        | 0.26%   |
| Stuttgart         | 32        | 0.25%   |
| Istanbul          | 32        | 0.25%   |
| Beijing           | 31        | 0.24%   |
| New York          | 29        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2741      | 4233   | 15.57%  |
| WDC                         | 2461      | 4246   | 13.98%  |
| Seagate                     | 2235      | 4034   | 12.69%  |
| Toshiba                     | 1125      | 1678   | 6.39%   |
| Kingston                    | 1024      | 1341   | 5.82%   |
| Unknown                     | 948       | 1262   | 5.38%   |
| Crucial                     | 809       | 1090   | 4.59%   |
| SanDisk                     | 755       | 980    | 4.29%   |
| Hitachi                     | 497       | 710    | 2.82%   |
| Intel                       | 413       | 590    | 2.35%   |
| SK hynix                    | 383       | 481    | 2.18%   |
| HGST                        | 308       | 622    | 1.75%   |
| Fujitsu                     | 305       | 325    | 1.73%   |
| A-DATA Technology           | 298       | 496    | 1.69%   |
| Micron Technology           | 264       | 311    | 1.5%    |
| Apple                       | 249       | 320    | 1.41%   |
| China                       | 176       | 207    | 1%      |
| Unknown                     | 132       | 148    | 0.75%   |
| KIOXIA                      | 115       | 132    | 0.65%   |
| SPCC                        | 107       | 130    | 0.61%   |
| Phison                      | 102       | 136    | 0.58%   |
| Transcend                   | 101       | 121    | 0.57%   |
| PNY                         | 90        | 157    | 0.51%   |
| Patriot                     | 74        | 90     | 0.42%   |
| Intenso                     | 73        | 96     | 0.41%   |
| Corsair                     | 72        | 103    | 0.41%   |
| OCZ                         | 71        | 84     | 0.4%    |
| JMicron Technology          | 67        | 75     | 0.38%   |
| LITEON                      | 64        | 77     | 0.36%   |
| Hewlett-Packard             | 64        | 103    | 0.36%   |
| Silicon Motion              | 62        | 74     | 0.35%   |
| Netac                       | 57        | 142    | 0.32%   |
| Maxtor                      | 56        | 70     | 0.32%   |
| GOODRAM                     | 48        | 83     | 0.27%   |
| Kingston Technology Company | 46        | 58     | 0.26%   |
| Gigabyte Technology         | 45        | 53     | 0.26%   |
| Micron/Crucial Technology   | 42        | 50     | 0.24%   |
| Team                        | 41        | 71     | 0.23%   |
| SABRENT                     | 38        | 40     | 0.22%   |
| Apacer                      | 37        | 48     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 239       | 1.22%   |
| Kingston SA400S37240G 240GB SSD    | 214       | 1.09%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 138       | 0.7%    |
| Unknown                            | 132       | 0.67%   |
| Seagate ST500DM002-1BD142 500GB    | 131       | 0.67%   |
| Kingston SA400S37120G 120GB SSD    | 129       | 0.66%   |
| Samsung SSD 860 EVO 500GB          | 112       | 0.57%   |
| Kingston SA400S37480G 480GB SSD    | 112       | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB     | 111       | 0.56%   |
| Crucial CT500MX500SSD1 500GB       | 108       | 0.55%   |
| Samsung SSD 850 EVO 250GB          | 107       | 0.54%   |
| Crucial CT480BX500SSD1 480GB       | 105       | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB       | 104       | 0.53%   |
| Samsung SSD 860 EVO 250GB          | 99        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD   | 96        | 0.49%   |
| Samsung SSD 860 EVO 1TB            | 94        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB        | 92        | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB     | 90        | 0.46%   |
| Toshiba DT01ACA050 500GB           | 89        | 0.45%   |
| Unknown MMC Card  32GB             | 87        | 0.44%   |
| Crucial CT240BX500SSD1 240GB       | 83        | 0.42%   |
| Samsung SSD 850 EVO 500GB          | 81        | 0.41%   |
| Apple SSD SM0128G 121GB            | 77        | 0.39%   |
| Apple SSD AP0128H 121GB            | 77        | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 76        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 75        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB     | 67        | 0.34%   |
| Toshiba MQ01ABD100 1TB             | 66        | 0.34%   |
| SanDisk NVMe SSD Drive 1TB         | 64        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 63        | 0.32%   |
| HGST HTS721010A9E630 1TB           | 63        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB     | 62        | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB           | 61        | 0.31%   |
| Samsung SSD 870 EVO 500GB          | 60        | 0.31%   |
| Samsung SSD 980 1TB                | 59        | 0.3%    |
| Unknown MMC Card  64GB             | 58        | 0.3%    |
| A-DATA SU800 512GB SSD             | 55        | 0.28%   |
| Samsung SSD 980 PRO 1TB            | 54        | 0.27%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.27%   |
| Seagate ST4000DM004-2CV104 4TB     | 52        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2173      | 3918   | 33%     |
| WDC                 | 1870      | 3355   | 28.4%   |
| Toshiba             | 889       | 1375   | 13.5%   |
| Hitachi             | 496       | 708    | 7.53%   |
| HGST                | 306       | 618    | 4.65%   |
| Fujitsu             | 305       | 325    | 4.63%   |
| Samsung Electronics | 221       | 286    | 3.36%   |
| Unknown             | 54        | 68     | 0.82%   |
| Maxtor              | 53        | 61     | 0.8%    |
| Apple               | 39        | 45     | 0.59%   |
| SABRENT             | 38        | 40     | 0.58%   |
| Hewlett-Packard     | 13        | 31     | 0.2%    |
| TO Exter            | 11        | 12     | 0.17%   |
| ASMT                | 11        | 31     | 0.17%   |
| Intenso             | 8         | 10     | 0.12%   |
| IBM/Hitachi         | 6         | 7      | 0.09%   |
| External            | 6         | 8      | 0.09%   |
| ASMedia             | 6         | 6      | 0.09%   |
| JMicron Technology  | 5         | 9      | 0.08%   |
| HPE                 | 5         | 13     | 0.08%   |
| USB3.0              | 4         | 4      | 0.06%   |
| QNAP                | 4         | 6      | 0.06%   |
| IBM-ESXS            | 4         | 7      | 0.06%   |
| USB                 | 3         | 3      | 0.05%   |
| LaCie               | 3         | 3      | 0.05%   |
| StoreJet            | 2         | 2      | 0.03%   |
| SILICONMOTION       | 2         | 2      | 0.03%   |
| Pear 2TB            | 2         | 2      | 0.03%   |
| NETAPP              | 2         | 6      | 0.03%   |
| Inateck             | 2         | 2      | 0.03%   |
| IET                 | 2         | 2      | 0.03%   |
| IBM                 | 2         | 2      | 0.03%   |
| H/W                 | 2         | 10     | 0.03%   |
| DELLBOSS            | 2         | 3      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| WD MediaMax         | 1         | 6      | 0.02%   |
| WALRAM              | 1         | 1      | 0.02%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| Synology            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1259      | 1792   | 21.62%  |
| Kingston            | 841       | 1111   | 14.44%  |
| Crucial             | 689       | 921    | 11.83%  |
| SanDisk             | 466       | 617    | 8%      |
| WDC                 | 288       | 368    | 4.95%   |
| A-DATA Technology   | 212       | 371    | 3.64%   |
| China               | 173       | 204    | 2.97%   |
| Intel               | 167       | 248    | 2.87%   |
| Apple               | 122       | 139    | 2.1%    |
| Micron Technology   | 104       | 135    | 1.79%   |
| Transcend           | 88        | 107    | 1.51%   |
| SPCC                | 85        | 102    | 1.46%   |
| Toshiba             | 84        | 107    | 1.44%   |
| SK hynix            | 79        | 94     | 1.36%   |
| OCZ                 | 71        | 84     | 1.22%   |
| PNY                 | 70        | 130    | 1.2%    |
| Intenso             | 61        | 78     | 1.05%   |
| Patriot             | 60        | 70     | 1.03%   |
| LITEON              | 52        | 62     | 0.89%   |
| Netac               | 51        | 136    | 0.88%   |
| GOODRAM             | 42        | 62     | 0.72%   |
| Team                | 34        | 61     | 0.58%   |
| JMicron Technology  | 30        | 32     | 0.52%   |
| Apacer              | 30        | 36     | 0.52%   |
| LITEONIT            | 28        | 38     | 0.48%   |
| Corsair             | 28        | 33     | 0.48%   |
| Hewlett-Packard     | 27        | 36     | 0.46%   |
| Plextor             | 24        | 30     | 0.41%   |
| Unknown             | 23        | 28     | 0.39%   |
| Seagate             | 21        | 27     | 0.36%   |
| Gigabyte Technology | 21        | 23     | 0.36%   |
| KingDian            | 20        | 21     | 0.34%   |
| ASMT                | 18        | 22     | 0.31%   |
| Lexar               | 16        | 19     | 0.27%   |
| KingSpec            | 14        | 15     | 0.24%   |
| Unknown             | 13        | 16     | 0.22%   |
| LDLC                | 13        | 13     | 0.22%   |
| Mushkin             | 12        | 13     | 0.21%   |
| KIOXIA-EXCERIA      | 12        | 15     | 0.21%   |
| FORESEE             | 12        | 13     | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 5521      | 11044  | 35.03%  |
| SSD     | 5081      | 7873   | 32.24%  |
| NVMe    | 3976      | 5890   | 25.23%  |
| MMC     | 977       | 1265   | 6.2%    |
| Unknown | 204       | 305    | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8601      | 17921  | 60.46%  |
| NVMe | 3967      | 5859   | 27.89%  |
| MMC  | 977       | 1265   | 6.87%   |
| SAS  | 680       | 1332   | 4.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives  | Percent |
|-------------|-----------|---------|---------|
| 0.01-0.5    | 6504      | 9691    | 57.31%  |
| 0.51-1.0    | 2853      | 4618    | 25.14%  |
| 1.01-2.0    | 951       | 1772    | 8.38%   |
| 3.01-4.0    | 400       | 1023    | 3.52%   |
| 4.01-10.0   | 327       | 1026    | 2.88%   |
| 2.01-3.0    | 224       | 439     | 1.97%   |
| 10.01-20.0  | 86        | 343     | 0.76%   |
| 20.01-50.0  | 1         | 1       | 0.01%   |
| 50.01-100.0 | 1         | 4       | 0.01%   |
| 0           | 1         | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2806      | 22.14%  |
| 251-500        | 2388      | 18.84%  |
| Unknown        | 1902      | 15.01%  |
| 501-1000       | 1636      | 12.91%  |
| 1001-2000      | 866       | 6.83%   |
| 51-100         | 842       | 6.64%   |
| More than 3000 | 729       | 5.75%   |
| 1-20           | 644       | 5.08%   |
| 21-50          | 519       | 4.1%    |
| 2001-3000      | 340       | 2.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4505      | 34.57%  |
| Unknown        | 1902      | 14.6%   |
| 21-50          | 1478      | 11.34%  |
| 101-250        | 1457      | 11.18%  |
| 51-100         | 1164      | 8.93%   |
| 251-500        | 933       | 7.16%   |
| 501-1000       | 685       | 5.26%   |
| 1001-2000      | 414       | 3.18%   |
| More than 3000 | 306       | 2.35%   |
| 2001-3000      | 161       | 1.24%   |
| 0              | 25        | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 32        | 47     | 1.78%   |
| Kingston SV300S37A120G 120GB SSD     | 26        | 28     | 1.45%   |
| Fujitsu MHZ2160BH FFS G1 160GB       | 25        | 25     | 1.39%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 22        | 38     | 1.22%   |
| Seagate ST9500325AS 500GB            | 18        | 20     | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 14        | 17     | 0.78%   |
| Toshiba MQ01ABD100 1TB               | 13        | 14     | 0.72%   |
| Seagate ST3500418AS 500GB            | 13        | 19     | 0.72%   |
| Seagate ST1000DM003-9YN162 1TB       | 12        | 13     | 0.67%   |
| Hitachi HDS721050CLA362 500GB        | 12        | 14     | 0.67%   |
| Seagate ST9500420AS 500GB            | 11        | 11     | 0.61%   |
| Seagate ST31000528AS 1TB             | 11        | 13     | 0.61%   |
| Hitachi HTS543216L9SA02 160GB        | 11        | 11     | 0.61%   |
| HGST HTS725050A7E630 500GB           | 11        | 14     | 0.61%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 9         | 9      | 0.5%    |
| Toshiba MK1655GSXF 160GB             | 9         | 9      | 0.5%    |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 0.5%    |
| Seagate ST3250318AS 250GB            | 9         | 10     | 0.5%    |
| Seagate ST31500341AS 1TB             | 9         | 15     | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB       | 9         | 12     | 0.5%    |
| WDC WD20EARS-00MVWB0 2TB             | 8         | 8      | 0.45%   |
| Toshiba DT01ACA050 500GB             | 8         | 9      | 0.45%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 8         | 10     | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB      | 8         | 8      | 0.45%   |
| Seagate ST3250410AS 250GB            | 8         | 9      | 0.45%   |
| Seagate ST250DM000-1BD141 250GB      | 8         | 8      | 0.45%   |
| Hitachi HTS545050B9A300 500GB        | 8         | 8      | 0.45%   |
| HGST HTS541010A9E680 1TB             | 8         | 8      | 0.45%   |
| WDC WD20EARX-00PASB0 2TB             | 7         | 10     | 0.39%   |
| Toshiba MQ01ABF050 500GB             | 7         | 7      | 0.39%   |
| Toshiba DT01ACA100 1TB               | 7         | 9      | 0.39%   |
| Seagate ST500LT012-9WS142 500GB      | 7         | 8      | 0.39%   |
| Seagate ST3320613AS 320GB            | 7         | 7      | 0.39%   |
| Seagate ST3160815AS 160GB            | 7         | 9      | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB       | 7         | 8      | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB       | 7         | 7      | 0.39%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 8      | 0.39%   |
| HGST HTS545050A7E680 500GB           | 7         | 7      | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 6         | 6      | 0.33%   |
| WDC WD5000AAKX-001CA0 500GB          | 6         | 8      | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 441       | 602    | 25.51%  |
| WDC                 | 366       | 521    | 21.17%  |
| Hitachi             | 160       | 197    | 9.25%   |
| Samsung Electronics | 134       | 150    | 7.75%   |
| Toshiba             | 126       | 142    | 7.29%   |
| Kingston            | 69        | 79     | 3.99%   |
| Intel               | 54        | 71     | 3.12%   |
| HGST                | 51        | 55     | 2.95%   |
| Fujitsu             | 41        | 43     | 2.37%   |
| Crucial             | 37        | 44     | 2.14%   |
| SK hynix            | 36        | 43     | 2.08%   |
| SanDisk             | 29        | 34     | 1.68%   |
| A-DATA Technology   | 29        | 37     | 1.68%   |
| Micron Technology   | 23        | 30     | 1.33%   |
| Maxtor              | 22        | 24     | 1.27%   |
| OCZ                 | 10        | 11     | 0.58%   |
| LITEON              | 7         | 7      | 0.4%    |
| Corsair             | 7         | 7      | 0.4%    |
| China               | 7         | 7      | 0.4%    |
| Apple               | 6         | 7      | 0.35%   |
| LITEONIT            | 5         | 6      | 0.29%   |
| KingDian            | 5         | 5      | 0.29%   |
| JMicron Technology  | 4         | 5      | 0.23%   |
| SSSTC               | 3         | 3      | 0.17%   |
| SPCC                | 3         | 3      | 0.17%   |
| KingSpec            | 3         | 3      | 0.17%   |
| Hewlett-Packard     | 3         | 5      | 0.17%   |
| Unknown             | 2         | 2      | 0.12%   |
| Transcend           | 2         | 2      | 0.12%   |
| ShiJi               | 2         | 5      | 0.12%   |
| PNY                 | 2         | 7      | 0.12%   |
| Plextor             | 2         | 3      | 0.12%   |
| Netac               | 2         | 3      | 0.12%   |
| Lenovo              | 2         | 2      | 0.12%   |
| Kimtigo             | 2         | 2      | 0.12%   |
| IBM/Hitachi         | 2         | 2      | 0.12%   |
| IBM                 | 2         | 2      | 0.12%   |
| Apacer              | 2         | 2      | 0.12%   |
| Unknown             | 2         | 2      | 0.12%   |
| ZHITAI              | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 441       | 602    | 34.64%  |
| WDC                 | 350       | 503    | 27.49%  |
| Hitachi             | 160       | 197    | 12.57%  |
| Toshiba             | 122       | 138    | 9.58%   |
| Samsung Electronics | 68        | 74     | 5.34%   |
| HGST                | 51        | 55     | 4.01%   |
| Fujitsu             | 41        | 43     | 3.22%   |
| Maxtor              | 22        | 24     | 1.73%   |
| Apple               | 5         | 6      | 0.39%   |
| Hewlett-Packard     | 3         | 5      | 0.24%   |
| JMicron Technology  | 2         | 3      | 0.16%   |
| IBM/Hitachi         | 2         | 2      | 0.16%   |
| IBM                 | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |
| ASMT                | 1         | 2      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1189      | 1659   | 72.41%  |
| SSD     | 375       | 444    | 22.84%  |
| NVMe    | 77        | 97     | 4.69%   |
| Unknown | 1         | 1      | 0.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 5.41%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 5.41%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 2.7%    |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1         | 1      | 2.7%    |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 2.7%    |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.7%    |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500DM005 HD502HJ 500GB                 | 1         | 1      | 2.7%    |
| Seagate ST3500830AS 500GB                        | 1         | 1      | 2.7%    |
| Seagate ST3500630A 500GB                         | 1         | 1      | 2.7%    |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 2.7%    |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 2.7%    |
| Seagate ST2000NM0011 2TB                         | 1         | 1      | 2.7%    |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 980 250GB                | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 2.7%    |
| Samsung Electronics SP0802N 80GB                 | 1         | 1      | 2.7%    |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB     | 1         | 1      | 2.7%    |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 2.7%    |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 2.7%    |
| Samsung Electronics HD253GJ 250GB                | 1         | 1      | 2.7%    |
| Samsung Electronics HD103SJ 1TB                  | 1         | 2      | 2.7%    |
| KingDian S400 120GB                              | 1         | 1      | 2.7%    |
| Intel SSDSC2KW256G8 256GB                        | 1         | 1      | 2.7%    |
| Inland SATA SSD 128GB                            | 1         | 1      | 2.7%    |
| IBM-ESXS ST9300605SS 304GB                       | 1         | 2      | 2.7%    |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.7%    |
| HGST HUH728080ALN600 8TB                         | 1         | 1      | 2.7%    |
| HGST HTS725050A7E630 500GB                       | 1         | 2      | 2.7%    |
| HGST HDN724040ALE640 4TB                         | 1         | 1      | 2.7%    |
| Hewlett-Packard SSD S700 500GB                   | 1         | 2      | 2.7%    |
| Crucial CT500P2SSD8 500GB                        | 1         | 1      | 2.7%    |
| Crucial CT1000P1SSD8 1TB                         | 1         | 1      | 2.7%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 16     | 29.73%  |
| Seagate             | 10        | 11     | 27.03%  |
| WDC                 | 3         | 3      | 8.11%   |
| HGST                | 3         | 4      | 8.11%   |
| Toshiba             | 2         | 2      | 5.41%   |
| Crucial             | 2         | 2      | 5.41%   |
| KingDian            | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| Inland              | 1         | 1      | 2.7%    |
| IBM-ESXS            | 1         | 2      | 2.7%    |
| Hitachi             | 1         | 2      | 2.7%    |
| Hewlett-Packard     | 1         | 2      | 2.7%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 8303      | 16697  | 60.69%  |
| Detected | 3744      | 7429   | 27.36%  |
| Malfunc  | 1595      | 2201   | 11.66%  |
| Failed   | 37        | 47     | 0.27%   |
| Limited  | 3         | 3      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7380      | 48.77%  |
| AMD                              | 2079      | 13.74%  |
| Samsung Electronics              | 1538      | 10.16%  |
| SanDisk                          | 634       | 4.19%   |
| Nvidia                           | 503       | 3.32%   |
| SK hynix                         | 288       | 1.9%    |
| ASMedia Technology               | 278       | 1.84%   |
| Phison Electronics               | 245       | 1.62%   |
| Kingston Technology Company      | 239       | 1.58%   |
| Marvell Technology Group         | 189       | 1.25%   |
| Micron/Crucial Technology        | 173       | 1.14%   |
| Toshiba America Info Systems     | 172       | 1.14%   |
| Micron Technology                | 162       | 1.07%   |
| JMicron Technology               | 134       | 0.89%   |
| Silicon Motion                   | 121       | 0.8%    |
| ADATA Technology                 | 120       | 0.79%   |
| LSI Logic / Symbios Logic        | 117       | 0.77%   |
| KIOXIA                           | 116       | 0.77%   |
| Broadcom / LSI                   | 102       | 0.67%   |
| Apple                            | 91        | 0.6%    |
| VIA Technologies                 | 51        | 0.34%   |
| Adaptec                          | 38        | 0.25%   |
| MAXIO Technology (Hangzhou)      | 37        | 0.24%   |
| Solid State Storage Technology   | 34        | 0.22%   |
| Realtek Semiconductor            | 30        | 0.2%    |
| Hewlett-Packard                  | 29        | 0.19%   |
| Silicon Image                    | 28        | 0.19%   |
| Union Memory (Shenzhen)          | 25        | 0.17%   |
| Seagate Technology               | 24        | 0.16%   |
| Silicon Integrated Systems [SiS] | 20        | 0.13%   |
| Lite-On Technology               | 19        | 0.13%   |
| Shenzhen Longsys Electronics     | 16        | 0.11%   |
| INNOGRIT                         | 12        | 0.08%   |
| Yangtze Memory Technologies      | 11        | 0.07%   |
| Biwin Storage Technology         | 9         | 0.06%   |
| Transcend                        | 6         | 0.04%   |
| Lenovo                           | 6         | 0.04%   |
| IBM                              | 5         | 0.03%   |
| 3ware                            | 5         | 0.03%   |
| ULi Electronics                  | 4         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1416      | 8.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 750       | 4.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 532       | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 530       | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 416       | 2.39%   |
| Nvidia MCP79 AHCI Controller                                                   | 379       | 2.18%   |
| AMD 400 Series Chipset SATA Controller                                         | 311       | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 295       | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 287       | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 278       | 1.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 268       | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 264       | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 262       | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 260       | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 247       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 246       | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 238       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 232       | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 231       | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 204       | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 196       | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 190       | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 184       | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 184       | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 164       | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 157       | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 153       | 0.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 151       | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 144       | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 128       | 0.74%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 126       | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 126       | 0.72%   |
| Intel SATA Controller [RAID mode]                                              | 121       | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 115       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 113       | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 113       | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 112       | 0.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 111       | 0.64%   |
| Phison E12 NVMe Controller                                                     | 110       | 0.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 110       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8495      | 55.75%  |
| NVMe | 3977      | 26.1%   |
| IDE  | 1602      | 10.51%  |
| RAID | 957       | 6.28%   |
| SAS  | 157       | 1.03%   |
| SCSI | 50        | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9211      | 75.43%  |
| AMD                   | 2577      | 21.1%   |
| ARM                   | 357       | 2.92%   |
| Unknown               | 16        | 0.13%   |
| CentaurHauls          | 12        | 0.1%    |
| sifive,u74-mc         | 10        | 0.08%   |
| Qualcomm              | 6         | 0.05%   |
| CHRP IBM,8233-E8B     | 5         | 0.04%   |
| Phytium               | 4         | 0.03%   |
| sifive,bullet0        | 3         | 0.02%   |
| Marvell Semiconductor | 2         | 0.02%   |
| Loongson              | 2         | 0.02%   |
| CHRP IBM,9131-52A     | 2         | 0.02%   |
| PowerNV FP5466G2      | 1         | 0.01%   |
| PowerNV C829UAG3      | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |
| AppliedMicro          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 357       | 2.91%   |
| ARM Processor                                 | 284       | 2.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 215       | 1.76%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 152       | 1.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 138       | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 100       | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 99        | 0.81%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 99        | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 94        | 0.77%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 91        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 86        | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 83        | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 81        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 78        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 72        | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 72        | 0.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 70        | 0.57%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 67        | 0.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 65        | 0.53%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 63        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 62        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 62        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 59        | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 56        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 52        | 0.42%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 51        | 0.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 50        | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 49        | 0.4%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 49        | 0.4%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 48        | 0.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 46        | 0.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 46        | 0.38%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 45        | 0.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 44        | 0.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 44        | 0.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 44        | 0.36%   |
| Intel Celeron N5105 @ 2.00GHz                 | 44        | 0.36%   |
| Intel 12th Gen Core i5-1235U                  | 43        | 0.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 42        | 0.34%   |
| Intel 12th Gen Core i7-12700H                 | 42        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2333      | 19.07%  |
| Intel Core i7           | 1700      | 13.9%   |
| Other                   | 1399      | 11.44%  |
| Intel Core i3           | 818       | 6.69%   |
| Intel Celeron           | 796       | 6.51%   |
| Intel Core 2 Duo        | 774       | 6.33%   |
| AMD Ryzen 5             | 638       | 5.22%   |
| Intel Xeon              | 511       | 4.18%   |
| AMD Ryzen 7             | 510       | 4.17%   |
| Intel Pentium           | 345       | 2.82%   |
| Intel Atom              | 253       | 2.07%   |
| AMD Ryzen 9             | 219       | 1.79%   |
| AMD FX                  | 143       | 1.17%   |
| Intel Pentium Dual-Core | 124       | 1.01%   |
| Intel Core 2            | 120       | 0.98%   |
| AMD Ryzen 3             | 117       | 0.96%   |
| Intel Core 2 Quad       | 78        | 0.64%   |
| AMD Ryzen 7 PRO         | 76        | 0.62%   |
| AMD A6                  | 59        | 0.48%   |
| Intel Core i9           | 57        | 0.47%   |
| AMD A8                  | 57        | 0.47%   |
| AMD Ryzen 5 PRO         | 52        | 0.43%   |
| AMD A10                 | 50        | 0.41%   |
| AMD A4                  | 46        | 0.38%   |
| AMD Athlon              | 44        | 0.36%   |
| Intel Pentium Dual      | 41        | 0.34%   |
| Intel Pentium 4         | 40        | 0.33%   |
| AMD Ryzen Threadripper  | 40        | 0.33%   |
| Intel Pentium Silver    | 39        | 0.32%   |
| Intel Genuine           | 38        | 0.31%   |
| AMD Athlon 64 X2        | 38        | 0.31%   |
| Intel Pentium M         | 37        | 0.3%    |
| AMD Phenom II X4        | 37        | 0.3%    |
| AMD Athlon II X2        | 36        | 0.29%   |
| Intel Pentium Gold      | 34        | 0.28%   |
| AMD E                   | 34        | 0.28%   |
| ARM Allwinner           | 28        | 0.23%   |
| AMD E1                  | 27        | 0.22%   |
| AMD GX                  | 24        | 0.2%    |
| Intel Xeon Silver       | 21        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4774      | 39%     |
| 4       | 4121      | 33.67%  |
| 6       | 1136      | 9.28%   |
| 8       | 918       | 7.5%    |
| 1       | 379       | 3.1%    |
| 12      | 260       | 2.12%   |
| 16      | 169       | 1.38%   |
| 10      | 148       | 1.21%   |
| 14      | 84        | 0.69%   |
| Unknown | 67        | 0.55%   |
| 3       | 54        | 0.44%   |
| 24      | 48        | 0.39%   |
| 32      | 23        | 0.19%   |
| 20      | 15        | 0.12%   |
| 28      | 8         | 0.07%   |
| 18      | 6         | 0.05%   |
| 64      | 4         | 0.03%   |
| 48      | 4         | 0.03%   |
| 44      | 4         | 0.03%   |
| 40      | 4         | 0.03%   |
| 22      | 4         | 0.03%   |
| 36      | 3         | 0.02%   |
| 5       | 3         | 0.02%   |
| 192     | 1         | 0.01%   |
| 128     | 1         | 0.01%   |
| 96      | 1         | 0.01%   |
| 80      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11890     | 97.33%  |
| 2       | 243       | 1.99%   |
| Unknown | 66        | 0.54%   |
| 4       | 8         | 0.07%   |
| 3       | 6         | 0.05%   |
| 16      | 1         | 0.01%   |
| 8       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7518      | 61.47%  |
| 1       | 4638      | 37.92%  |
| Unknown | 67        | 0.55%   |
| 4       | 7         | 0.06%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11745     | 96.11%  |
| Unknown        | 263       | 2.15%   |
| 32-bit         | 182       | 1.49%   |
| 64-bit         | 30        | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3242      | 25.84%  |
| 0x1067a    | 703       | 5.6%    |
| 0x306a9    | 505       | 4.02%   |
| 0x306c3    | 499       | 3.98%   |
| 0x206a7    | 481       | 3.83%   |
| 0x806c1    | 384       | 3.06%   |
| 0x306d4    | 293       | 2.34%   |
| 0x806ec    | 263       | 2.1%    |
| 0x906ea    | 254       | 2.02%   |
| 0x506e3    | 229       | 1.83%   |
| 0x806e9    | 206       | 1.64%   |
| 0x806ea    | 201       | 1.6%    |
| 0x406e3    | 173       | 1.38%   |
| 0x40651    | 169       | 1.35%   |
| 0x906e9    | 163       | 1.3%    |
| 0x30678    | 161       | 1.28%   |
| 0x08108109 | 154       | 1.23%   |
| 0x406c4    | 143       | 1.14%   |
| 0x08701021 | 136       | 1.08%   |
| 0x0a50000c | 114       | 0.91%   |
| 0x20655    | 107       | 0.85%   |
| 0xa0653    | 101       | 0.8%    |
| 0x08600106 | 101       | 0.8%    |
| 0x706a8    | 94        | 0.75%   |
| 0x906c0    | 91        | 0.73%   |
| 0x906a3    | 89        | 0.71%   |
| 0xa0652    | 85        | 0.68%   |
| 0x6f6      | 85        | 0.68%   |
| 0x6fd      | 84        | 0.67%   |
| 0x10676    | 83        | 0.66%   |
| 0x08608103 | 81        | 0.65%   |
| 0x906eb    | 79        | 0.63%   |
| 0x0a50000d | 78        | 0.62%   |
| 0x506c9    | 76        | 0.61%   |
| 0x0800820d | 73        | 0.58%   |
| 0x906a4    | 69        | 0.55%   |
| 0x706e5    | 64        | 0.51%   |
| 0x0a201016 | 64        | 0.51%   |
| 0x906ed    | 60        | 0.48%   |
| 0x08108102 | 60        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1716      | 14.01%  |
| Haswell          | 963       | 7.86%   |
| Penryn           | 898       | 7.33%   |
| Unknown          | 868       | 7.09%   |
| IvyBridge        | 723       | 5.9%    |
| SandyBridge      | 716       | 5.85%   |
| Skylake          | 608       | 4.96%   |
| TigerLake        | 466       | 3.8%    |
| Zen 2            | 455       | 3.71%   |
| Zen 3            | 438       | 3.58%   |
| Silvermont       | 433       | 3.53%   |
| Broadwell        | 391       | 3.19%   |
| Zen+             | 385       | 3.14%   |
| Core             | 328       | 2.68%   |
| CometLake        | 326       | 2.66%   |
| Westmere         | 271       | 2.21%   |
| Alderlake Hybrid | 260       | 2.12%   |
| Zen              | 208       | 1.7%    |
| K10              | 172       | 1.4%    |
| Goldmont plus    | 172       | 1.4%    |
| Piledriver       | 159       | 1.3%    |
| IceLake          | 151       | 1.23%   |
| Bonnell          | 139       | 1.13%   |
| Excavator        | 138       | 1.13%   |
| Goldmont         | 106       | 0.87%   |
| Tremont          | 105       | 0.86%   |
| Nehalem          | 100       | 0.82%   |
| P6               | 85        | 0.69%   |
| K8 Hammer        | 82        | 0.67%   |
| Bobcat           | 81        | 0.66%   |
| NetBurst         | 68        | 0.56%   |
| Jaguar           | 54        | 0.44%   |
| Steamroller      | 47        | 0.38%   |
| Puma             | 46        | 0.38%   |
| Bulldozer        | 37        | 0.3%    |
| K10 Llano        | 27        | 0.22%   |
| K8 & K10 hybrid  | 10        | 0.08%   |
| Gracemont        | 9         | 0.07%   |
| K6               | 7         | 0.06%   |
| Geode            | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 6995      | 51.82%  |
| Nvidia                                       | 3356      | 24.86%  |
| AMD                                          | 2737      | 20.28%  |
| Matrox Electronics Systems                   | 198       | 1.47%   |
| ASPEED Technology                            | 168       | 1.24%   |
| VIA Technologies                             | 13        | 0.1%    |
| Silicon Integrated Systems [SiS]             | 13        | 0.1%    |
| Zhaoxin                                      | 4         | 0.03%   |
| Loongson Technology                          | 3         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.01%   |
| S3 Graphics                                  | 2         | 0.01%   |
| Huawei Technologies                          | 2         | 0.01%   |
| Silicon Motion                               | 1         | 0.01%   |
| Neomagic                                     | 1         | 0.01%   |
| Cirrus Logic                                 | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 480       | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 424       | 3.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 374       | 2.69%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 355       | 2.55%   |
| Intel UHD Graphics 620                                                                   | 270       | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 259       | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 258       | 1.85%   |
| Intel HD Graphics 620                                                                    | 252       | 1.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 224       | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 221       | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 220       | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 217       | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 208       | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 204       | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 200       | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 192       | 1.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 186       | 1.34%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 168       | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 165       | 1.18%   |
| Intel HD Graphics 6000                                                                   | 162       | 1.16%   |
| Intel HD Graphics 5500                                                                   | 160       | 1.15%   |
| Intel HD Graphics 530                                                                    | 160       | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 151       | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 145       | 1.04%   |
| Intel HD Graphics 630                                                                    | 141       | 1.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 134       | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 133       | 0.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 132       | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 129       | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 123       | 0.88%   |
| AMD Lucienne                                                                             | 117       | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 116       | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 103       | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 98        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 97        | 0.7%    |
| Intel JasperLake [UHD Graphics]                                                          | 96        | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 95        | 0.68%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 90        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 87        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 87        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 5509      | 44.87%  |
| 1 x AMD                           | 2208      | 17.98%  |
| 1 x Nvidia                        | 2026      | 16.5%   |
| Intel + Nvidia                    | 1117      | 9.1%    |
| Other                             | 429       | 3.49%   |
| Intel + AMD                       | 221       | 1.8%    |
| 1 x Matrox                        | 187       | 1.52%   |
| AMD + Nvidia                      | 157       | 1.28%   |
| 1 x ASPEED                        | 136       | 1.11%   |
| 2 x AMD                           | 129       | 1.05%   |
| 2 x Intel                         | 41        | 0.33%   |
| 2 x Nvidia                        | 20        | 0.16%   |
| Nvidia + ASPEED                   | 17        | 0.14%   |
| 1 x VIA                           | 13        | 0.11%   |
| 1 x SiS                           | 13        | 0.11%   |
| AMD + ASPEED                      | 11        | 0.09%   |
| Nvidia + Matrox                   | 8         | 0.07%   |
| Intel + 2 x Nvidia                | 5         | 0.04%   |
| 1 x Zhaoxin                       | 4         | 0.03%   |
| AMD + Matrox                      | 4         | 0.03%   |
| 2 x Nvidia + 1 x ASPEED           | 3         | 0.02%   |
| 3 x AMD                           | 2         | 0.02%   |
| 1 x S3 Graphics                   | 2         | 0.02%   |
| 2 x Nvidia + 1 x Matrox           | 1         | 0.01%   |
| 2 x Loongson Technology           | 1         | 0.01%   |
| 2 x Intel + 1 x Nvidia            | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x XGI                           | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| Nvidia + Huawei Technologies      | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Loongson Technology           | 1         | 0.01%   |
| Intel + ASPEED                    | 1         | 0.01%   |
| 1 x Huawei Technologies           | 1         | 0.01%   |
| 1 x Cirrus Logic                  | 1         | 0.01%   |
| AMD + Loongson Technology         | 1         | 0.01%   |
| AMD + 3DLabs                      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9077      | 73.53%  |
| Unknown     | 1999      | 16.19%  |
| Proprietary | 1268      | 10.27%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 8657      | 69.8%   |
| 0.01-0.5       | 1253      | 10.1%   |
| 1.01-2.0       | 802       | 6.47%   |
| 0.51-1.0       | 510       | 4.11%   |
| 3.01-4.0       | 506       | 4.08%   |
| 7.01-8.0       | 315       | 2.54%   |
| 5.01-6.0       | 176       | 1.42%   |
| 8.01-16.0      | 89        | 0.72%   |
| 2.01-3.0       | 61        | 0.49%   |
| 16.01-24.0     | 23        | 0.19%   |
| 4.01-5.0       | 6         | 0.05%   |
| More than 64.0 | 1         | 0.01%   |
| 32.01-64.0     | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |
| 0              | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1396      | 12.2%   |
| Samsung Electronics     | 1245      | 10.88%  |
| BOE                     | 958       | 8.38%   |
| Chimei Innolux          | 835       | 7.3%    |
| LG Display              | 831       | 7.27%   |
| Apple                   | 737       | 6.44%   |
| Dell                    | 715       | 6.25%   |
| Goldstar                | 538       | 4.7%    |
| Hewlett-Packard         | 356       | 3.11%   |
| Acer                    | 311       | 2.72%   |
| BenQ                    | 296       | 2.59%   |
| Philips                 | 278       | 2.43%   |
| AOC                     | 268       | 2.34%   |
| Lenovo                  | 247       | 2.16%   |
| Ancor Communications    | 228       | 1.99%   |
| Sharp                   | 163       | 1.43%   |
| Iiyama                  | 145       | 1.27%   |
| ViewSonic               | 133       | 1.16%   |
| InfoVision              | 115       | 1.01%   |
| Chi Mei Optoelectronics | 111       | 0.97%   |
| Unknown                 | 104       | 0.91%   |
| ASUSTek Computer        | 98        | 0.86%   |
| PANDA                   | 90        | 0.79%   |
| Eizo                    | 67        | 0.59%   |
| Sony                    | 64        | 0.56%   |
| LG Electronics          | 56        | 0.49%   |
| NEC Computers           | 54        | 0.47%   |
| HannStar                | 53        | 0.46%   |
| CSO                     | 51        | 0.45%   |
| LG Philips              | 44        | 0.38%   |
| Unknown                 | 32        | 0.28%   |
| Fujitsu Siemens         | 28        | 0.24%   |
| MSI                     | 26        | 0.23%   |
| Vizio                   | 23        | 0.2%    |
| Panasonic               | 23        | 0.2%    |
| Sceptre Tech            | 22        | 0.19%   |
| Medion                  | 22        | 0.19%   |
| RTK                     | 20        | 0.17%   |
| Toshiba                 | 18        | 0.16%   |
| CPT                     | 18        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                  | 210       | 1.78%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 191       | 1.62%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 112       | 0.95%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 70        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 61        | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 60        | 0.51%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 48        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 48        | 0.41%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 48        | 0.41%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 45        | 0.38%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 42        | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 40        | 0.34%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 38        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 35        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 34        | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 33        | 0.28%   |
| Unknown                                                               | 32        | 0.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 31        | 0.26%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 29        | 0.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 28        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 27        | 0.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 26        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 26        | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 25        | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 25        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                     | 24        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 24        | 0.2%    |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                  | 23        | 0.2%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 22        | 0.19%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 20        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 20        | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 20        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 20        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 20        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 20        | 0.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 19        | 0.16%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 19        | 0.16%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 19        | 0.16%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 19        | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 18        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4567      | 41.62%  |
| 1366x768 (WXGA)    | 1848      | 16.84%  |
| 3840x2160 (4K)     | 640       | 5.83%   |
| 1280x800 (WXGA)    | 619       | 5.64%   |
| 2560x1440 (QHD)    | 502       | 4.57%   |
| 1280x1024 (SXGA)   | 403       | 3.67%   |
| 1600x900 (HD+)     | 368       | 3.35%   |
| 1920x1200 (WUXGA)  | 335       | 3.05%   |
| 1440x900 (WXGA+)   | 269       | 2.45%   |
| 1680x1050 (WSXGA+) | 255       | 2.32%   |
| Unknown            | 139       | 1.27%   |
| 2560x1080          | 101       | 0.92%   |
| 3440x1440          | 97        | 0.88%   |
| 1024x600           | 81        | 0.74%   |
| 2560x1600          | 80        | 0.73%   |
| 1024x768 (XGA)     | 73        | 0.67%   |
| 1360x768           | 67        | 0.61%   |
| 2288x1287          | 62        | 0.57%   |
| 3840x1080          | 52        | 0.47%   |
| 1600x1200          | 45        | 0.41%   |
| 3840x2400          | 37        | 0.34%   |
| 2880x1800          | 35        | 0.32%   |
| 1920x540           | 27        | 0.25%   |
| 2160x1440          | 19        | 0.17%   |
| 2736x1824          | 15        | 0.14%   |
| 3200x1800 (QHD+)   | 13        | 0.12%   |
| 4480x1440          | 12        | 0.11%   |
| 2256x1504          | 12        | 0.11%   |
| 1280x720 (HD)      | 12        | 0.11%   |
| 1920x1280          | 11        | 0.1%    |
| 1400x1050          | 11        | 0.1%    |
| 3840x1600          | 10        | 0.09%   |
| 5760x2160          | 9         | 0.08%   |
| 2048x1152          | 8         | 0.07%   |
| 3840x1200          | 7         | 0.06%   |
| 3200x1080          | 7         | 0.06%   |
| 3072x1920          | 7         | 0.06%   |
| 3000x2000          | 7         | 0.06%   |
| 7680x2160          | 6         | 0.05%   |
| 5760x1080          | 6         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2258      | 19.85%  |
| 13      | 1610      | 14.15%  |
| 14      | 944       | 8.3%    |
| 24      | 862       | 7.58%   |
| 27      | 775       | 6.81%   |
| 23      | 663       | 5.83%   |
| 21      | 592       | 5.2%    |
| 17      | 546       | 4.8%    |
| Unknown | 449       | 3.95%   |
| 11      | 365       | 3.21%   |
| 19      | 303       | 2.66%   |
| 12      | 266       | 2.34%   |
| 18      | 212       | 1.86%   |
| 31      | 203       | 1.78%   |
| 20      | 157       | 1.38%   |
| 22      | 156       | 1.37%   |
| 34      | 150       | 1.32%   |
| 16      | 104       | 0.91%   |
| 10      | 90        | 0.79%   |
| 84      | 70        | 0.62%   |
| 142     | 60        | 0.53%   |
| 25      | 56        | 0.49%   |
| 32      | 54        | 0.47%   |
| 72      | 52        | 0.46%   |
| 54      | 46        | 0.4%    |
| 40      | 42        | 0.37%   |
| 26      | 33        | 0.29%   |
| 28      | 31        | 0.27%   |
| 29      | 24        | 0.21%   |
| 52      | 20        | 0.18%   |
| 48      | 19        | 0.17%   |
| 65      | 14        | 0.12%   |
| 46      | 13        | 0.11%   |
| 33      | 13        | 0.11%   |
| 43      | 12        | 0.11%   |
| 8       | 12        | 0.11%   |
| 39      | 11        | 0.1%    |
| 49      | 10        | 0.09%   |
| 35      | 10        | 0.09%   |
| 37      | 8         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3921      | 35.04%  |
| 501-600        | 2150      | 19.21%  |
| 201-300        | 1814      | 16.21%  |
| 401-500        | 1216      | 10.87%  |
| 351-400        | 621       | 5.55%   |
| Unknown        | 449       | 4.01%   |
| 601-700        | 350       | 3.13%   |
| 701-800        | 223       | 1.99%   |
| 1001-1500      | 145       | 1.3%    |
| 1501-2000      | 129       | 1.15%   |
| 801-900        | 73        | 0.65%   |
| More than 2000 | 61        | 0.55%   |
| 901-1000       | 21        | 0.19%   |
| 101-200        | 15        | 0.13%   |
| 1-100          | 3         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7375      | 71.24%  |
| 16/10   | 1649      | 15.93%  |
| 5/4     | 374       | 3.61%   |
| Unknown | 372       | 3.59%   |
| 21/9    | 185       | 1.79%   |
| 4/3     | 158       | 1.53%   |
| 3/2     | 108       | 1.04%   |
| 1.00    | 64        | 0.62%   |
| 6/5     | 20        | 0.19%   |
| 32/9    | 19        | 0.18%   |
| 2.65    | 6         | 0.06%   |
| 0.56    | 5         | 0.05%   |
| 3.40    | 3         | 0.03%   |
| 3.20    | 3         | 0.03%   |
| 1.96    | 3         | 0.03%   |
| 2.00    | 2         | 0.02%   |
| 0.67    | 2         | 0.02%   |
| 0.45    | 2         | 0.02%   |
| 3.73    | 1         | 0.01%   |
| 11/10   | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2243      | 19.87%  |
| 81-90          | 1984      | 17.58%  |
| 201-250        | 1792      | 15.88%  |
| 301-350        | 799       | 7.08%   |
| 151-200        | 630       | 5.58%   |
| 71-80          | 573       | 5.08%   |
| 351-500        | 469       | 4.16%   |
| Unknown        | 449       | 3.98%   |
| 51-60          | 368       | 3.26%   |
| 141-150        | 358       | 3.17%   |
| 251-300        | 351       | 3.11%   |
| 121-130        | 310       | 2.75%   |
| More than 1000 | 306       | 2.71%   |
| 61-70          | 243       | 2.15%   |
| 501-1000       | 119       | 1.05%   |
| 111-120        | 95        | 0.84%   |
| 41-50          | 89        | 0.79%   |
| 131-140        | 61        | 0.54%   |
| 91-100         | 29        | 0.26%   |
| 1-40           | 18        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3360      | 30.62%  |
| 121-160       | 3121      | 28.44%  |
| 101-120       | 2808      | 25.59%  |
| 161-240       | 776       | 7.07%   |
| Unknown       | 450       | 4.1%    |
| 1-50          | 262       | 2.39%   |
| More than 240 | 196       | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8464      | 67.96%  |
| 0     | 2202      | 17.68%  |
| 2     | 1597      | 12.82%  |
| 3     | 183       | 1.47%   |
| 4     | 8         | 0.06%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5938      | 33.4%   |
| Intel                             | 5762      | 32.41%  |
| Qualcomm Atheros                  | 1621      | 9.12%   |
| Broadcom                          | 1208      | 6.79%   |
| Nvidia                            | 477       | 2.68%   |
| Broadcom Limited                  | 360       | 2.02%   |
| MediaTek                          | 275       | 1.55%   |
| Marvell Technology Group          | 238       | 1.34%   |
| Ralink Technology                 | 164       | 0.92%   |
| TP-Link                           | 148       | 0.83%   |
| ASIX Electronics                  | 122       | 0.69%   |
| Ralink                            | 120       | 0.67%   |
| Samsung Electronics               | 79        | 0.44%   |
| Qualcomm                          | 57        | 0.32%   |
| Dell                              | 55        | 0.31%   |
| Xiaomi                            | 52        | 0.29%   |
| Lenovo                            | 51        | 0.29%   |
| Sierra Wireless                   | 49        | 0.28%   |
| Aquantia                          | 45        | 0.25%   |
| Microchip Technology              | 44        | 0.25%   |
| Mellanox Technologies             | 42        | 0.24%   |
| Huawei Technologies               | 41        | 0.23%   |
| Ericsson Business Mobile Networks | 38        | 0.21%   |
| Qualcomm Atheros Communications   | 36        | 0.2%    |
| JMicron Technology                | 36        | 0.2%    |
| DisplayLink                       | 36        | 0.2%    |
| Microsoft                         | 32        | 0.18%   |
| D-Link System                     | 32        | 0.18%   |
| ASUSTek Computer                  | 29        | 0.16%   |
| D-Link                            | 28        | 0.16%   |
| NetGear                           | 27        | 0.15%   |
| Hewlett-Packard                   | 24        | 0.13%   |
| American Megatrends               | 24        | 0.13%   |
| Edimax Technology                 | 23        | 0.13%   |
| VIA Technologies                  | 20        | 0.11%   |
| IBM                               | 19        | 0.11%   |
| Fibocom                           | 19        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.1%    |
| QinHeng Electronics               | 18        | 0.1%    |
| Sigma Designs                     | 16        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 4106      | 19.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 565       | 2.7%    |
| Intel Wi-Fi 6 AX200                                                  | 404       | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 386       | 1.85%   |
| Nvidia MCP79 Ethernet                                                | 382       | 1.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 378       | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 366       | 1.75%   |
| Intel Wi-Fi 6 AX201                                                  | 362       | 1.73%   |
| Intel Wireless 8265 / 8275                                           | 320       | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                    | 299       | 1.43%   |
| Intel Wireless 7265                                                  | 294       | 1.41%   |
| Intel Wireless 7260                                                  | 275       | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 271       | 1.3%    |
| Intel I211 Gigabit Network Connection                                | 244       | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 209       | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 185       | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 180       | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 178       | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 176       | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 175       | 0.84%   |
| Intel Wireless 8260                                                  | 174       | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 168       | 0.8%    |
| Intel Ethernet Controller I225-V                                     | 167       | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 163       | 0.78%   |
| Intel Wireless 3165                                                  | 156       | 0.75%   |
| Intel Ethernet Connection (13) I219-V                                | 155       | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 153       | 0.73%   |
| Intel Ethernet Connection I217-LM                                    | 150       | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 146       | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 145       | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 145       | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                 | 143       | 0.68%   |
| Intel I210 Gigabit Network Connection                                | 138       | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 125       | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 121       | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 120       | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 116       | 0.55%   |
| Intel Wireless-AC 9260                                               | 109       | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                | 109       | 0.52%   |
| Intel 82579V Gigabit Network Connection                              | 104       | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4033      | 46.26%  |
| Qualcomm Atheros                      | 1310      | 15.02%  |
| Realtek Semiconductor                 | 1229      | 14.1%   |
| Broadcom                              | 815       | 9.35%   |
| Broadcom Limited                      | 268       | 3.07%   |
| MediaTek                              | 255       | 2.92%   |
| Ralink Technology                     | 164       | 1.88%   |
| Ralink                                | 120       | 1.38%   |
| TP-Link                               | 119       | 1.36%   |
| Sierra Wireless                       | 49        | 0.56%   |
| Qualcomm Atheros Communications       | 36        | 0.41%   |
| Qualcomm                              | 36        | 0.41%   |
| Dell                                  | 32        | 0.37%   |
| ASUSTek Computer                      | 29        | 0.33%   |
| NetGear                               | 27        | 0.31%   |
| D-Link                                | 25        | 0.29%   |
| Marvell Technology Group              | 23        | 0.26%   |
| Edimax Technology                     | 21        | 0.24%   |
| Microsoft                             | 19        | 0.22%   |
| Fibocom                               | 19        | 0.22%   |
| D-Link System                         | 17        | 0.19%   |
| Belkin Components                     | 11        | 0.13%   |
| Wilocity                              | 7         | 0.08%   |
| Linksys                               | 7         | 0.08%   |
| Gemtek                                | 6         | 0.07%   |
| IMC Networks                          | 5         | 0.06%   |
| Hewlett-Packard                       | 5         | 0.06%   |
| Ericsson Business Mobile Networks     | 5         | 0.06%   |
| AVM                                   | 4         | 0.05%   |
| Quectel Wireless Solutions            | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.02%   |
| 3Com                                  | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| ZyDAS                                 | 1         | 0.01%   |
| Z-Com                                 | 1         | 0.01%   |
| Xiaomi                                | 1         | 0.01%   |
| Winbond Electronics                   | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 404       | 4.61%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 378       | 4.31%   |
| Intel Wi-Fi 6 AX201                                                                   | 362       | 4.13%   |
| Intel Wireless 8265 / 8275                                                            | 320       | 3.65%   |
| Intel Wireless 7265                                                                   | 294       | 3.35%   |
| Intel Wireless 7260                                                                   | 275       | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 271       | 3.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 209       | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 185       | 2.11%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 180       | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 178       | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 176       | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 175       | 2%      |
| Intel Wireless 8260                                                                   | 174       | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 168       | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 163       | 1.86%   |
| Intel Wireless 3165                                                                   | 156       | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 153       | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 146       | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 145       | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 145       | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 125       | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 121       | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 120       | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 116       | 1.32%   |
| Intel Wireless-AC 9260                                                                | 109       | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 98        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 95        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 77        | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 69        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 62        | 0.71%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 62        | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 61        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                                       | 60        | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 60        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 59        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 56        | 0.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 56        | 0.64%   |
| Intel Wireless 3160                                                                   | 56        | 0.64%   |
| Realtek 802.11ac NIC                                                                  | 53        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5442      | 47.67%  |
| Intel                             | 3349      | 29.33%  |
| Broadcom                          | 488       | 4.27%   |
| Nvidia                            | 476       | 4.17%   |
| Qualcomm Atheros                  | 468       | 4.1%    |
| Marvell Technology Group          | 216       | 1.89%   |
| ASIX Electronics                  | 122       | 1.07%   |
| Broadcom Limited                  | 96        | 0.84%   |
| Xiaomi                            | 51        | 0.45%   |
| Samsung Electronics               | 51        | 0.45%   |
| Lenovo                            | 51        | 0.45%   |
| Aquantia                          | 45        | 0.39%   |
| Microchip Technology              | 42        | 0.37%   |
| Mellanox Technologies             | 39        | 0.34%   |
| JMicron Technology                | 36        | 0.32%   |
| DisplayLink                       | 36        | 0.32%   |
| TP-Link                           | 29        | 0.25%   |
| Huawei Technologies               | 29        | 0.25%   |
| American Megatrends               | 24        | 0.21%   |
| VIA Technologies                  | 20        | 0.18%   |
| Qualcomm                          | 19        | 0.17%   |
| MediaTek                          | 19        | 0.17%   |
| IBM                               | 19        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.16%   |
| D-Link System                     | 15        | 0.13%   |
| Google                            | 13        | 0.11%   |
| OPPO Electronics                  | 12        | 0.11%   |
| Microsoft                         | 12        | 0.11%   |
| ICS Advent                        | 12        | 0.11%   |
| 3Com                              | 12        | 0.11%   |
| Motorola PCS                      | 11        | 0.1%    |
| Hewlett-Packard                   | 10        | 0.09%   |
| Dell                              | 10        | 0.09%   |
| Standard Microsystems             | 9         | 0.08%   |
| Cypress Semiconductor             | 9         | 0.08%   |
| Emulex                            | 8         | 0.07%   |
| Attansic Technology               | 8         | 0.07%   |
| Insyde Software                   | 7         | 0.06%   |
| Apple                             | 7         | 0.06%   |
| Sundance Technology Inc / IC Plus | 5         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4106      | 34.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 565       | 4.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 386       | 3.26%   |
| Nvidia MCP79 Ethernet                                             | 382       | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 366       | 3.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 299       | 2.53%   |
| Intel I211 Gigabit Network Connection                             | 244       | 2.06%   |
| Intel Ethernet Controller I225-V                                  | 167       | 1.41%   |
| Intel Ethernet Connection (13) I219-V                             | 155       | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 150       | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 143       | 1.21%   |
| Intel I210 Gigabit Network Connection                             | 138       | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 109       | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 104       | 0.88%   |
| Intel I350 Gigabit Network Connection                             | 95        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 95        | 0.8%    |
| Intel 82574L Gigabit Network Connection                           | 92        | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 89        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 86        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 79        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 77        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 74        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 70        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 70        | 0.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 68        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 66        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 64        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 63        | 0.53%   |
| Intel Ethernet Connection (14) I219-V                             | 55        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 55        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 0.44%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 50        | 0.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 49        | 0.41%   |
| Nvidia MCP61 Ethernet                                             | 48        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 47        | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 46        | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 46        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 45        | 0.38%   |
| Intel Ethernet Connection I219-V                                  | 45        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10517     | 54.96%  |
| WiFi     | 8313      | 43.45%  |
| Modem    | 276       | 1.44%   |
| Unknown  | 28        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6466      | 52.81%  |
| WiFi     | 5774      | 47.16%  |
| Modem    | 3         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6306      | 51.43%  |
| 1     | 4793      | 39.09%  |
| 0     | 499       | 4.07%   |
| 3     | 363       | 2.96%   |
| 4     | 173       | 1.41%   |
| 6     | 51        | 0.42%   |
| 5     | 28        | 0.23%   |
| 8     | 19        | 0.15%   |
| 7     | 11        | 0.09%   |
| 9     | 4         | 0.03%   |
| 12    | 3         | 0.02%   |
| 20    | 2         | 0.02%   |
| 10    | 2         | 0.02%   |
| 33    | 1         | 0.01%   |
| 21    | 1         | 0.01%   |
| 17    | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 11    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 10071     | 81.33%  |
| Yes     | 2311      | 18.66%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3302      | 47.37%  |
| Apple                           | 759       | 10.89%  |
| Realtek Semiconductor           | 638       | 9.15%   |
| Qualcomm Atheros Communications | 473       | 6.79%   |
| Cambridge Silicon Radio         | 322       | 4.62%   |
| Broadcom                        | 310       | 4.45%   |
| IMC Networks                    | 257       | 3.69%   |
| Lite-On Technology              | 194       | 2.78%   |
| Foxconn / Hon Hai               | 177       | 2.54%   |
| ASUSTek Computer                | 115       | 1.65%   |
| Dell                            | 73        | 1.05%   |
| MediaTek                        | 72        | 1.03%   |
| Hewlett-Packard                 | 59        | 0.85%   |
| Realtek                         | 38        | 0.55%   |
| Toshiba                         | 36        | 0.52%   |
| Ralink                          | 21        | 0.3%    |
| TP-Link                         | 18        | 0.26%   |
| USI                             | 15        | 0.22%   |
| Foxconn International           | 13        | 0.19%   |
| Marvell Semiconductor           | 11        | 0.16%   |
| Ralink Technology               | 9         | 0.13%   |
| Alps Electric                   | 8         | 0.11%   |
| Taiyo Yuden                     | 5         | 0.07%   |
| Edimax Technology               | 5         | 0.07%   |
| Belkin Components               | 5         | 0.07%   |
| Micro Star International        | 4         | 0.06%   |
| Integrated System Solution      | 4         | 0.06%   |
| Fujitsu                         | 4         | 0.06%   |
| Dynex                           | 3         | 0.04%   |
| Qcom                            | 2         | 0.03%   |
| Opticis                         | 2         | 0.03%   |
| Chicony Electronics             | 2         | 0.03%   |
| Askey Computer                  | 2         | 0.03%   |
| Actions                         | 2         | 0.03%   |
| Unknown                         | 2         | 0.03%   |
| Unknown                         | 1         | 0.01%   |
| Smart Modular Technologies      | 1         | 0.01%   |
| Sitecom Europe                  | 1         | 0.01%   |
| SINO WEALTH                     | 1         | 0.01%   |
| Microsoft                       | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1204      | 17.25%  |
| Intel Bluetooth Device                              | 856       | 12.27%  |
| Realtek Bluetooth Radio                             | 446       | 6.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 440       | 6.31%   |
| Intel AX200 Bluetooth                               | 385       | 5.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 378       | 5.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 322       | 4.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 254       | 3.64%   |
| Apple Bluetooth USB Host Controller                 | 214       | 3.07%   |
| Realtek  Bluetooth 4.2 Adapter                      | 124       | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 112       | 1.61%   |
| Intel AX210 Bluetooth                               | 106       | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 105       | 1.5%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 79        | 1.13%   |
| MediaTek Wireless_Device                            | 71        | 1.02%   |
| IMC Networks Bluetooth Radio                        | 70        | 1%      |
| Apple Bluetooth Host Controller                     | 68        | 0.97%   |
| IMC Networks Wireless_Device                        | 67        | 0.96%   |
| IMC Networks Bluetooth Device                       | 67        | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 65        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 59        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 57        | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 51        | 0.73%   |
| Lite-On Bluetooth Device                            | 50        | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 47        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 46        | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 0.63%   |
| Realtek Bluetooth Radio                             | 38        | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 36        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 34        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 33        | 0.47%   |
| Lite-On Wireless_Device                             | 30        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 28        | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                   | 27        | 0.39%   |
| Realtek RTL8723B Bluetooth                          | 26        | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 0.37%   |
| ASUS Bluetooth Device                               | 24        | 0.34%   |
| Dell DW375 Bluetooth Module                         | 23        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8198      | 53.82%  |
| AMD                                          | 2898      | 19.03%  |
| Nvidia                                       | 2583      | 16.96%  |
| C-Media Electronics                          | 232       | 1.52%   |
| Logitech                                     | 118       | 0.77%   |
| Creative Labs                                | 77        | 0.51%   |
| ASUSTek Computer                             | 64        | 0.42%   |
| Realtek Semiconductor                        | 61        | 0.4%    |
| Texas Instruments                            | 59        | 0.39%   |
| Lenovo                                       | 56        | 0.37%   |
| GN Netcom                                    | 46        | 0.3%    |
| Generalplus Technology                       | 46        | 0.3%    |
| Plantronics                                  | 42        | 0.28%   |
| JMTek                                        | 42        | 0.28%   |
| Focusrite-Novation                           | 35        | 0.23%   |
| Creative Technology                          | 35        | 0.23%   |
| Micro Star International                     | 32        | 0.21%   |
| Kingston Technology                          | 28        | 0.18%   |
| VIA Technologies                             | 26        | 0.17%   |
| KTMicro                                      | 26        | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 24        | 0.16%   |
| SteelSeries ApS                              | 23        | 0.15%   |
| Hewlett-Packard                              | 23        | 0.15%   |
| Silicon Integrated Systems [SiS]             | 20        | 0.13%   |
| Dell                                         | 20        | 0.13%   |
| Razer USA                                    | 18        | 0.12%   |
| BEHRINGER International                      | 16        | 0.11%   |
| Corsair                                      | 15        | 0.1%    |
| Microsoft                                    | 14        | 0.09%   |
| Blue Microphones                             | 14        | 0.09%   |
| RODE Microphones                             | 13        | 0.09%   |
| GYROCOM C&C                                  | 11        | 0.07%   |
| Cambridge Silicon Radio                      | 11        | 0.07%   |
| BR23                                         | 11        | 0.07%   |
| Yamaha                                       | 10        | 0.07%   |
| M-Audio                                      | 10        | 0.07%   |
| DSEA A/S                                     | 10        | 0.07%   |
| Tenx Technology                              | 9         | 0.06%   |
| Apple                                        | 9         | 0.06%   |
| Sennheiser Communications                    | 8         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 1014      | 5.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 819       | 4.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 646       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 623       | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 558       | 3.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 510       | 2.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 464       | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 435       | 2.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 433       | 2.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 404       | 2.23%   |
| Nvidia MCP79 High Definition Audio                                                                | 386       | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 344       | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 343       | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 340       | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 335       | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 323       | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 298       | 1.64%   |
| Intel 200 Series PCH HD Audio                                                                     | 267       | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 249       | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 245       | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 240       | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 231       | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 229       | 1.26%   |
| Intel 8 Series HD Audio Controller                                                                | 229       | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 216       | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 207       | 1.14%   |
| Intel Comet Lake PCH cAVS                                                                         | 195       | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 187       | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 185       | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 177       | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 173       | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 171       | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 169       | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 169       | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 163       | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 158       | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 153       | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 128       | 0.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 123       | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 115       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2397      | 21.41%  |
| SK hynix            | 2091      | 18.68%  |
| Kingston            | 1316      | 11.76%  |
| Unknown             | 1111      | 9.92%   |
| Micron Technology   | 983       | 8.78%   |
| Crucial             | 813       | 7.26%   |
| Corsair             | 460       | 4.11%   |
| G.Skill             | 342       | 3.06%   |
| A-DATA Technology   | 204       | 1.82%   |
| Elpida              | 188       | 1.68%   |
| Ramaxel Technology  | 161       | 1.44%   |
| Unknown (ABCD)      | 106       | 0.95%   |
| Patriot             | 106       | 0.95%   |
| Unknown             | 100       | 0.89%   |
| Nanya Technology    | 94        | 0.84%   |
| Team                | 65        | 0.58%   |
| Smart               | 64        | 0.57%   |
| Transcend           | 50        | 0.45%   |
| GOODRAM             | 39        | 0.35%   |
| AMD                 | 35        | 0.31%   |
| Hewlett-Packard     | 23        | 0.21%   |
| Apacer              | 22        | 0.2%    |
| Hikvision           | 21        | 0.19%   |
| Timetec             | 17        | 0.15%   |
| Teikon              | 16        | 0.14%   |
| Qimonda             | 14        | 0.13%   |
| ASint Technology    | 14        | 0.13%   |
| Silicon Power       | 13        | 0.12%   |
| Avant               | 13        | 0.12%   |
| 48spaces            | 13        | 0.12%   |
| PNY                 | 11        | 0.1%    |
| GeIL                | 10        | 0.09%   |
| 4ea5                | 9         | 0.08%   |
| Micro Memory Bank   | 8         | 0.07%   |
| ff                  | 8         | 0.07%   |
| Unknown (0x5846)    | 7         | 0.06%   |
| Wilk                | 6         | 0.05%   |
| Unifosa             | 6         | 0.05%   |
| Toshiba             | 6         | 0.05%   |
| Smart Brazil        | 6         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 265       | 2.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 177       | 1.47%   |
| Unknown                                                          | 100       | 0.83%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 69        | 0.57%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 69        | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 68        | 0.57%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 57        | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 55        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 54        | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 54        | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 54        | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 54        | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 53        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 52        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 52        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 51        | 0.42%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 50        | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 49        | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 48        | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 47        | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 47        | 0.39%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 46        | 0.38%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 45        | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 44        | 0.37%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 44        | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 41        | 0.34%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 39        | 0.32%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 38        | 0.32%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s         | 38        | 0.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 38        | 0.32%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 37        | 0.31%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4096MB DIMM DDR4 2133MT/s        | 36        | 0.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 35        | 0.29%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 34        | 0.28%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 33        | 0.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 33        | 0.27%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 32        | 0.27%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 32        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 4330      | 43.93%  |
| DDR3         | 3124      | 31.7%   |
| DDR2         | 872       | 8.85%   |
| Unknown      | 308       | 3.13%   |
| LPDDR4       | 307       | 3.11%   |
| SDRAM        | 296       | 3%      |
| LPDDR3       | 247       | 2.51%   |
| DDR5         | 177       | 1.8%    |
| DDR          | 90        | 0.91%   |
| LPDDR5       | 74        | 0.75%   |
| DRAM         | 29        | 0.29%   |
| RAM          | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 5381      | 54.8%   |
| DIMM         | 3747      | 38.16%  |
| Row Of Chips | 508       | 5.17%   |
| Unknown      | 113       | 1.15%   |
| Chip         | 41        | 0.42%   |
| FB-DIMM      | 18        | 0.18%   |
| RIMM         | 12        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 3637      | 34.02%  |
| 4096    | 2502      | 23.4%   |
| 16384   | 1553      | 14.53%  |
| 2048    | 1530      | 14.31%  |
| 1024    | 799       | 7.47%   |
| 32768   | 517       | 4.84%   |
| 512     | 96        | 0.9%    |
| 256     | 25        | 0.23%   |
| 65536   | 13        | 0.12%   |
| 1536    | 5         | 0.05%   |
| 128     | 4         | 0.04%   |
| 49152   | 1         | 0.01%   |
| 24576   | 1         | 0.01%   |
| 16315   | 1         | 0.01%   |
| 8072    | 1         | 0.01%   |
| 6144    | 1         | 0.01%   |
| 3072    | 1         | 0.01%   |
| 384     | 1         | 0.01%   |
| 64      | 1         | 0.01%   |
| 16      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2019      | 19.07%  |
| 3200    | 1647      | 15.55%  |
| 2667    | 1323      | 12.49%  |
| 2400    | 685       | 6.47%   |
| 1333    | 679       | 6.41%   |
| 800     | 593       | 5.6%    |
| 2133    | 526       | 4.97%   |
| 667     | 331       | 3.13%   |
| Unknown | 275       | 2.6%    |
| 1334    | 239       | 2.26%   |
| 3600    | 233       | 2.2%    |
| 1867    | 202       | 1.91%   |
| 1067    | 121       | 1.14%   |
| 4800    | 117       | 1.1%    |
| 1866    | 117       | 1.1%    |
| 2666    | 107       | 1.01%   |
| 4267    | 104       | 0.98%   |
| 1066    | 100       | 0.94%   |
| 6400    | 78        | 0.74%   |
| 3733    | 71        | 0.67%   |
| 3266    | 71        | 0.67%   |
| 2933    | 68        | 0.64%   |
| 3400    | 62        | 0.59%   |
| 3000    | 58        | 0.55%   |
| 1800    | 53        | 0.5%    |
| 533     | 50        | 0.47%   |
| 4199    | 42        | 0.4%    |
| 2048    | 38        | 0.36%   |
| 3800    | 37        | 0.35%   |
| 400     | 36        | 0.34%   |
| 2866    | 27        | 0.25%   |
| 5600    | 26        | 0.25%   |
| 3466    | 26        | 0.25%   |
| 975     | 24        | 0.23%   |
| 6000    | 23        | 0.22%   |
| 8400    | 21        | 0.2%    |
| 3533    | 20        | 0.19%   |
| 333     | 20        | 0.19%   |
| 4266    | 19        | 0.18%   |
| 4333    | 16        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 77        | 30.68%  |
| Brother Industries     | 48        | 19.12%  |
| Canon                  | 34        | 13.55%  |
| Samsung Electronics    | 18        | 7.17%   |
| Seiko Epson            | 15        | 5.98%   |
| Xerox                  | 9         | 3.59%   |
| Dymo-CoStar            | 9         | 3.59%   |
| Prolific Technology    | 6         | 2.39%   |
| Lexmark International  | 6         | 2.39%   |
| Zebra                  | 4         | 1.59%   |
| Pantum                 | 4         | 1.59%   |
| Kyocera                | 4         | 1.59%   |
| STMicroelectronics     | 2         | 0.8%    |
| QinHeng Electronics    | 2         | 0.8%    |
| Oki Data               | 2         | 0.8%    |
| Datamax-O'Neil         | 2         | 0.8%    |
| Xiaomi                 | 1         | 0.4%    |
| Ricoh                  | 1         | 0.4%    |
| Printer                | 1         | 0.4%    |
| Panasonic (Matsushita) | 1         | 0.4%    |
| nemonic                | 1         | 0.4%    |
| Konica Minolta         | 1         | 0.4%    |
| GODEX INTERNATIONAL    | 1         | 0.4%    |
| Dell                   | 1         | 0.4%    |
| Apple                  | 1         | 0.4%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 7         | 2.76%   |
| HP LaserJet 1020                                          | 7         | 2.76%   |
| Prolific PL2305 Parallel Port                             | 6         | 2.36%   |
| HP LaserJet 1200                                          | 6         | 2.36%   |
| Canon LiDE 400                                            | 5         | 1.97%   |
| HP DeskJet 2130 series                                    | 4         | 1.57%   |
| Canon PIXMA MG3600 Series                                 | 4         | 1.57%   |
| Seiko Epson Printer                                       | 3         | 1.18%   |
| Samsung ML-1660 Series                                    | 3         | 1.18%   |
| Pantum P2500W series                                      | 3         | 1.18%   |
| HP LaserJet P1005                                         | 3         | 1.18%   |
| HP LaserJet M101-M106                                     | 3         | 1.18%   |
| HP DeskJet 2700 series                                    | 3         | 1.18%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 3         | 1.18%   |
| Brother HL-52x0 series                                    | 3         | 1.18%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.79%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 0.79%   |
| Samsung M2020 Series                                      | 2         | 0.79%   |
| QinHeng CH340S                                            | 2         | 0.79%   |
| Oki Data USB Device                                       | 2         | 0.79%   |
| Lexmark International CS417dn                             | 2         | 0.79%   |
| HP LaserJet Pro M404-M405                                 | 2         | 0.79%   |
| HP LaserJet M14-M17                                       | 2         | 0.79%   |
| HP LaserJet 400 M401a                                     | 2         | 0.79%   |
| HP LaserJet 1150                                          | 2         | 0.79%   |
| HP LaserJet 1022                                          | 2         | 0.79%   |
| HP LaserJet 1018                                          | 2         | 0.79%   |
| HP ENVY Photo 6200 series                                 | 2         | 0.79%   |
| HP ENVY 4520 series                                       | 2         | 0.79%   |
| HP DeskJet Plus 4100 series                               | 2         | 0.79%   |
| HP DeskJet 2600 series                                    | 2         | 0.79%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 0.79%   |
| Datamax-O'Neil Datamax E-4304                             | 2         | 0.79%   |
| Canon PIXMA MX920 Series                                  | 2         | 0.79%   |
| Canon MF4410                                              | 2         | 0.79%   |
| Canon MF3010                                              | 2         | 0.79%   |
| Canon G3010 series                                        | 2         | 0.79%   |
| Canon CanoScan LiDE 300                                   | 2         | 0.79%   |
| Brother PT-9500PC                                         | 2         | 0.79%   |
| Brother Printer                                           | 2         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 44        | 59.46%  |
| Seiko Epson        | 16        | 21.62%  |
| Hewlett-Packard    | 6         | 8.11%   |
| Mustek Systems     | 3         | 4.05%   |
| Ultima Electronics | 2         | 2.7%    |
| AGFA-Gevaert NV    | 2         | 2.7%    |
| Plustek            | 1         | 1.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 9         | 12.16%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 7         | 9.46%   |
| Canon CanoScan LiDE 210                                                               | 7         | 9.46%   |
| Canon CanoScan LiDE 220                                                               | 6         | 8.11%   |
| Canon CanoScan LIDE 25                                                                | 3         | 4.05%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 2.7%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 2         | 2.7%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 2         | 2.7%    |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.7%    |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.7%    |
| Canon CanoScan LiDE 60                                                                | 2         | 2.7%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2         | 2.7%    |
| Canon CanoScan LiDE 120                                                               | 2         | 2.7%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 2.7%    |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 1.35%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 1.35%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1         | 1.35%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 1.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.35%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.35%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 1.35%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1         | 1.35%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 1.35%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.35%   |
| Plustek 1200dpi USB Scanner                                                           | 1         | 1.35%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.35%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 1.35%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 1.35%   |
| HP ScanJet Pro 2500 f1                                                                | 1         | 1.35%   |
| HP ScanJet 82x0C                                                                      | 1         | 1.35%   |
| HP ScanJet 7650                                                                       | 1         | 1.35%   |
| HP ScanJet 3970c                                                                      | 1         | 1.35%   |
| HP Scanjet 300                                                                        | 1         | 1.35%   |
| HP Scanjet 200                                                                        | 1         | 1.35%   |
| Canon CanoScan 9000F Mark II                                                          | 1         | 1.35%   |
| Canon CanoScan 8800F                                                                  | 1         | 1.35%   |
| Canon CanoScan 5600F                                                                  | 1         | 1.35%   |
| Canon CanoScan 4400F                                                                  | 1         | 1.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1335      | 21.34%  |
| IMC Networks                           | 559       | 8.93%   |
| Bison Electronics                      | 486       | 7.77%   |
| Microdia                               | 468       | 7.48%   |
| Realtek Semiconductor                  | 406       | 6.49%   |
| Quanta                                 | 406       | 6.49%   |
| Logitech                               | 395       | 6.31%   |
| Sunplus Innovation Technology          | 308       | 4.92%   |
| Acer                                   | 178       | 2.84%   |
| Cheng Uei Precision Industry (Foxlink) | 176       | 2.81%   |
| Apple                                  | 165       | 2.64%   |
| Suyin                                  | 149       | 2.38%   |
| Lite-On Technology                     | 140       | 2.24%   |
| Syntek                                 | 137       | 2.19%   |
| Luxvisions Innotech Limited            | 127       | 2.03%   |
| Silicon Motion                         | 69        | 1.1%    |
| Microsoft                              | 60        | 0.96%   |
| Alcor Micro                            | 59        | 0.94%   |
| Samsung Electronics                    | 50        | 0.8%    |
| Z-Star Microelectronics                | 44        | 0.7%    |
| Sonix Technology                       | 42        | 0.67%   |
| Lenovo                                 | 42        | 0.67%   |
| Ricoh                                  | 36        | 0.58%   |
| Generalplus Technology                 | 34        | 0.54%   |
| Primax Electronics                     | 21        | 0.34%   |
| GEMBIRD                                | 20        | 0.32%   |
| Jieli Technology                       | 19        | 0.3%    |
| Creative Technology                    | 19        | 0.3%    |
| KYE Systems (Mouse Systems)            | 15        | 0.24%   |
| ARC International                      | 15        | 0.24%   |
| SunplusIT                              | 14        | 0.22%   |
| icSpring                               | 14        | 0.22%   |
| Genesys Logic                          | 13        | 0.21%   |
| ALi                                    | 13        | 0.21%   |
| MacroSilicon                           | 12        | 0.19%   |
| Importek                               | 12        | 0.19%   |
| OmniVision Technologies                | 10        | 0.16%   |
| Intel                                  | 7         | 0.11%   |
| Huawei Technologies                    | 7         | 0.11%   |
| Cubeternet                             | 7         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 375       | 5.94%   |
| Bison Integrated Camera                             | 201       | 3.18%   |
| Microdia Integrated_Webcam_HD                       | 196       | 3.1%    |
| IMC Networks Integrated Camera                      | 195       | 3.09%   |
| Realtek Integrated_Webcam_HD                        | 153       | 2.42%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 138       | 2.18%   |
| Sunplus Integrated_Webcam_HD                        | 111       | 1.76%   |
| Chicony HD WebCam                                   | 103       | 1.63%   |
| Quanta Chromebook HD Camera                         | 102       | 1.61%   |
| Logitech Webcam C270                                | 97        | 1.54%   |
| Syntek Integrated Camera                            | 82        | 1.3%    |
| Acer Integrated 5M Camera                           | 73        | 1.16%   |
| Chicony HP HD Camera                                | 70        | 1.11%   |
| Logitech HD Pro Webcam C920                         | 59        | 0.93%   |
| Bison BisonCam, NB Pro                              | 57        | 0.9%    |
| Quanta HP TrueVision HD Camera                      | 54        | 0.85%   |
| Lite-On Integrated Camera                           | 53        | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 52        | 0.82%   |
| Quanta HD User Facing                               | 50        | 0.79%   |
| Chicony USB2.0 HD UVC WebCam                        | 50        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)             | 49        | 0.78%   |
| Apple Built-in iSight                               | 48        | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 45        | 0.71%   |
| Chicony Integrated 5M Camera                        | 44        | 0.7%    |
| Bison SunplusIT Integrated Camera                   | 44        | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE                           | 44        | 0.7%    |
| Lite-On HP HD Camera                                | 42        | 0.66%   |
| Microdia Integrated Webcam                          | 41        | 0.65%   |
| Chicony Integrated Camera (1280x720@30)             | 40        | 0.63%   |
| Quanta HP HD Camera                                 | 39        | 0.62%   |
| Chicony HD User Facing                              | 39        | 0.62%   |
| Apple FaceTime HD Camera (Built-in)                 | 38        | 0.6%    |
| Chicony HP Truevision HD camera                     | 37        | 0.59%   |
| Logitech C922 Pro Stream Webcam                     | 35        | 0.55%   |
| Sunplus HD WebCam                                   | 34        | 0.54%   |
| Realtek USB Camera                                  | 34        | 0.54%   |
| Chicony EasyCamera                                  | 34        | 0.54%   |
| Bison HD Webcam                                     | 33        | 0.52%   |
| Acer Integrated Camera                              | 33        | 0.52%   |
| Quanta VGA WebCam                                   | 32        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 492       | 39.94%  |
| Validity Sensors                   | 341       | 27.68%  |
| Shenzhen Goodix Technology         | 148       | 12.01%  |
| Elan Microelectronics              | 64        | 5.19%   |
| Upek                               | 60        | 4.87%   |
| AuthenTec                          | 59        | 4.79%   |
| LighTuning Technology              | 32        | 2.6%    |
| STMicroelectronics                 | 19        | 1.54%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.49%   |
| Samsung Electronics                | 4         | 0.32%   |
| Focal-systems.Corp                 | 3         | 0.24%   |
| DigitalPersona                     | 2         | 0.16%   |
| Microsoft                          | 1         | 0.08%   |
| HOLTEK                             | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 263       | 21.35%  |
| Shenzhen Goodix  Fingerprint Device                                        | 85        | 6.9%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 67        | 5.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 61        | 4.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 60        | 4.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 54        | 4.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 53        | 4.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 41        | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 38        | 3.08%   |
| Elan ELAN:Fingerprint                                                      | 33        | 2.68%   |
| Elan ELAN:ARM-M4                                                           | 30        | 2.44%   |
| AuthenTec AES2810                                                          | 26        | 2.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 25        | 2.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 24        | 1.95%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 1.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 21        | 1.7%    |
| Synaptics WBDI                                                             | 20        | 1.62%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 1.62%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 1.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 19        | 1.54%   |
| Synaptics  WBDI                                                            | 19        | 1.54%   |
| Validity Sensors VFS491                                                    | 17        | 1.38%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 1.38%   |
| Synaptics UWP WBDI Device                                                  | 14        | 1.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 0.97%   |
| Synaptics UWP WBDI                                                         | 12        | 0.97%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 0.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.89%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 0.81%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 0.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 0.65%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.41%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 214       | 36.46%  |
| Alcor Micro                | 207       | 35.26%  |
| Upek                       | 36        | 6.13%   |
| Lenovo                     | 34        | 5.79%   |
| O2 Micro                   | 31        | 5.28%   |
| Gemalto (was Gemplus)      | 11        | 1.87%   |
| SCM Microsystems           | 8         | 1.36%   |
| Yubico.com                 | 7         | 1.19%   |
| Advanced Card Systems      | 7         | 1.19%   |
| Clay Logic                 | 6         | 1.02%   |
| Cherry                     | 5         | 0.85%   |
| Realtek Semiconductor      | 4         | 0.68%   |
| Chicony Electronics        | 4         | 0.68%   |
| Aladdin Knowledge Systems  | 4         | 0.68%   |
| Reiner SCT Kartensysteme   | 3         | 0.51%   |
| OmniKey                    | 2         | 0.34%   |
| Hewlett-Packard            | 1         | 0.17%   |
| Feitian Technologies       | 1         | 0.17%   |
| C3PO                       | 1         | 0.17%   |
| Athena Smartcard Solutions | 1         | 0.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 203       | 34.58%  |
| Broadcom 58200                                                               | 63        | 10.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 58        | 9.88%   |
| Broadcom 5880                                                                | 52        | 8.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 39        | 6.64%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 36        | 6.13%   |
| Lenovo Integrated Smart Card Reader                                          | 33        | 5.62%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 4.43%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 1.19%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 0.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 0.85%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 0.68%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 4         | 0.68%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 0.68%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 0.51%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 3         | 0.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.51%   |
| Clay Logic Nitrokey Start                                                    | 3         | 0.51%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.51%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 0.51%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 0.34%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.34%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.34%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.34%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.34%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.17%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.17%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.17%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.17%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.17%   |
| OmniKey CardMan 4321                                                         | 1         | 0.17%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.17%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.17%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.17%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.17%   |
| Feitian Technologies SCR301                                                  | 1         | 0.17%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.17%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.17%   |
| C3PO LTC31v2                                                                 | 1         | 0.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7495      | 60.18%  |
| 1     | 3878      | 31.14%  |
| 2     | 828       | 6.65%   |
| 3     | 182       | 1.46%   |
| 4     | 42        | 0.34%   |
| 5     | 19        | 0.15%   |
| 6     | 8         | 0.06%   |
| 7     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 2303      | 38.48%  |
| Fingerprint reader       | 1226      | 20.48%  |
| Net/wireless             | 550       | 9.19%   |
| Chipcard                 | 515       | 8.6%    |
| Multimedia controller    | 369       | 6.17%   |
| Communication controller | 259       | 4.33%   |
| Unassigned class         | 168       | 2.81%   |
| Camera                   | 139       | 2.32%   |
| Bluetooth                | 111       | 1.85%   |
| Sound                    | 83        | 1.39%   |
| Card reader              | 66        | 1.1%    |
| Storage                  | 50        | 0.84%   |
| Net/ethernet             | 46        | 0.77%   |
| Network                  | 24        | 0.4%    |
| Modem                    | 21        | 0.35%   |
| Storage/raid             | 16        | 0.27%   |
| Storage/ide              | 9         | 0.15%   |
| Flash memory             | 7         | 0.12%   |
| Dvb card                 | 7         | 0.12%   |
| Wireless                 | 5         | 0.08%   |
| Tv card                  | 5         | 0.08%   |
| Firewire controller      | 3         | 0.05%   |
| Storage/nvme             | 2         | 0.03%   |
| Storage/ata              | 1         | 0.02%   |


Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 4460

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H610M-E D4            | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | [577b5e8f51](https://linux-hardware.org/?probe=577b5e8f51) | May 01, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [27fdafaf01](https://linux-hardware.org/?probe=27fdafaf01) | May 01, 2023 |
| Gigabyte      | Z77MX-D3H                   | [fa4e32fe2c](https://linux-hardware.org/?probe=fa4e32fe2c) | May 01, 2023 |
| Dell          | 09KPNV A01                  | [45dad4b8e9](https://linux-hardware.org/?probe=45dad4b8e9) | May 01, 2023 |
| ASRock        | B660M-HDV                   | [a137e6ab62](https://linux-hardware.org/?probe=a137e6ab62) | May 01, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [4f0b170b70](https://linux-hardware.org/?probe=4f0b170b70) | May 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [f10c443a56](https://linux-hardware.org/?probe=f10c443a56) | May 01, 2023 |
| Dell          | 07PR60 A00                  | [e6f49bbe8a](https://linux-hardware.org/?probe=e6f49bbe8a) | Apr 30, 2023 |
| ASUSTek       | H81-PLUS                    | [3b45144d62](https://linux-hardware.org/?probe=3b45144d62) | Apr 30, 2023 |
| Gigabyte      | EP45-UD3P                   | [8d99ef5cc7](https://linux-hardware.org/?probe=8d99ef5cc7) | Apr 30, 2023 |
| ASUSTek       | H81I-PLUS                   | [01578538eb](https://linux-hardware.org/?probe=01578538eb) | Apr 30, 2023 |
| MSI           | PRO Z690-A WIFI             | [bfa4eb5eda](https://linux-hardware.org/?probe=bfa4eb5eda) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [68d85dd28f](https://linux-hardware.org/?probe=68d85dd28f) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [5166f820a6](https://linux-hardware.org/?probe=5166f820a6) | Apr 30, 2023 |
| ASRock        | 960GM-GS3 FX                | [392492c032](https://linux-hardware.org/?probe=392492c032) | Apr 30, 2023 |
| Medion        | H81H3-EM2                   | [c85a3da4ab](https://linux-hardware.org/?probe=c85a3da4ab) | Apr 30, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [a88277b7f9](https://linux-hardware.org/?probe=a88277b7f9) | Apr 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [88e7444fa5](https://linux-hardware.org/?probe=88e7444fa5) | Apr 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [763e7fa1b6](https://linux-hardware.org/?probe=763e7fa1b6) | Apr 30, 2023 |
| ASRock        | B450M Steel Legend          | [fed083feba](https://linux-hardware.org/?probe=fed083feba) | Apr 30, 2023 |
| Dell          | 00V62H A00                  | [86cb104ceb](https://linux-hardware.org/?probe=86cb104ceb) | Apr 29, 2023 |
| ASUSTek       | PRIME X470-PRO              | [244cfe88a4](https://linux-hardware.org/?probe=244cfe88a4) | Apr 29, 2023 |
| ASRock        | N68C-S UCC                  | [13628f3559](https://linux-hardware.org/?probe=13628f3559) | Apr 29, 2023 |
| ASUSTek       | H110M-D                     | [81cff8a578](https://linux-hardware.org/?probe=81cff8a578) | Apr 29, 2023 |
| Gigabyte      | Z790 UD                     | [536a24a0e3](https://linux-hardware.org/?probe=536a24a0e3) | Apr 29, 2023 |
| ASRock        | N68C-S UCC                  | [f7f4643b8f](https://linux-hardware.org/?probe=f7f4643b8f) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [6b44ad5061](https://linux-hardware.org/?probe=6b44ad5061) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [ce73a703b6](https://linux-hardware.org/?probe=ce73a703b6) | Apr 29, 2023 |
| YANYU         | EPIC-N56_I522E Ver          | [4798ab5c06](https://linux-hardware.org/?probe=4798ab5c06) | Apr 29, 2023 |
| ASUSTek       | PRIME B450M-K               | [3592ce514a](https://linux-hardware.org/?probe=3592ce514a) | Apr 29, 2023 |
| Gigabyte      | G41MT-S2                    | [ba5c65f4e3](https://linux-hardware.org/?probe=ba5c65f4e3) | Apr 29, 2023 |
| Lenovo        | XXXX 3000 H210              | [96644846f5](https://linux-hardware.org/?probe=96644846f5) | Apr 29, 2023 |
| Dell          | 0T0MHW A02                  | [4f08178f96](https://linux-hardware.org/?probe=4f08178f96) | Apr 29, 2023 |
| ECS           | H81H3-M4                    | [67da6cebd3](https://linux-hardware.org/?probe=67da6cebd3) | Apr 29, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [16b28befee](https://linux-hardware.org/?probe=16b28befee) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | [bd3dba564e](https://linux-hardware.org/?probe=bd3dba564e) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | [cab1aa59e0](https://linux-hardware.org/?probe=cab1aa59e0) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [e0367e684f](https://linux-hardware.org/?probe=e0367e684f) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [fed0a1a719](https://linux-hardware.org/?probe=fed0a1a719) | Apr 28, 2023 |
| ASUSTek       | Z87-PLUS                    | [7477be45f8](https://linux-hardware.org/?probe=7477be45f8) | Apr 28, 2023 |
| ASUSTek       | PRIME X370-PRO              | [ddb48a2def](https://linux-hardware.org/?probe=ddb48a2def) | Apr 28, 2023 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [43942fab0f](https://linux-hardware.org/?probe=43942fab0f) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | [01c8d89ab9](https://linux-hardware.org/?probe=01c8d89ab9) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | [f8aee85cd4](https://linux-hardware.org/?probe=f8aee85cd4) | Apr 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [815dd8e866](https://linux-hardware.org/?probe=815dd8e866) | Apr 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | [589810ee4b](https://linux-hardware.org/?probe=589810ee4b) | Apr 28, 2023 |
| Gigabyte      | Z490 AORUS ULTRA            | [96371860f5](https://linux-hardware.org/?probe=96371860f5) | Apr 28, 2023 |
| HP            | 21D0                        | [a26451e82c](https://linux-hardware.org/?probe=a26451e82c) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d138bfdf52](https://linux-hardware.org/?probe=d138bfdf52) | Apr 28, 2023 |
| ASRock        | A75M-HVS                    | [528362dfca](https://linux-hardware.org/?probe=528362dfca) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | [f4d7a6ed92](https://linux-hardware.org/?probe=f4d7a6ed92) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | [94f2408a63](https://linux-hardware.org/?probe=94f2408a63) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | [76c36882d9](https://linux-hardware.org/?probe=76c36882d9) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | [3d73e4cd7e](https://linux-hardware.org/?probe=3d73e4cd7e) | Apr 27, 2023 |
| Intel         | DH87RL AAG74240-403         | [54b1c509f2](https://linux-hardware.org/?probe=54b1c509f2) | Apr 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [49033dd76c](https://linux-hardware.org/?probe=49033dd76c) | Apr 27, 2023 |
| MSI           | X99A GAMING 9 ACK           | [3d79f67248](https://linux-hardware.org/?probe=3d79f67248) | Apr 27, 2023 |
| Dell          | 0HHV7N A00                  | [33517b7bfe](https://linux-hardware.org/?probe=33517b7bfe) | Apr 27, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [641d7d0398](https://linux-hardware.org/?probe=641d7d0398) | Apr 27, 2023 |
| Lenovo        | ThinkCentre M71e 3129B8G    | [2b6c3d498a](https://linux-hardware.org/?probe=2b6c3d498a) | Apr 27, 2023 |
| Gigabyte      | Z97P-D3                     | [40b51d3cae](https://linux-hardware.org/?probe=40b51d3cae) | Apr 27, 2023 |
| HP            | 18E7                        | [c6a760cb50](https://linux-hardware.org/?probe=c6a760cb50) | Apr 27, 2023 |
| ASUSTek       | H110M-A                     | [1fa553ab02](https://linux-hardware.org/?probe=1fa553ab02) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3e8fe7fed4](https://linux-hardware.org/?probe=3e8fe7fed4) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [9211d42ee3](https://linux-hardware.org/?probe=9211d42ee3) | Apr 27, 2023 |
| HP            | 3047h                       | [3e6dada8a9](https://linux-hardware.org/?probe=3e6dada8a9) | Apr 26, 2023 |
| ECS           | G41T-R3                     | [fcbdd2737a](https://linux-hardware.org/?probe=fcbdd2737a) | Apr 26, 2023 |
| ASRock        | H61M-VG4                    | [a8e7de2e0b](https://linux-hardware.org/?probe=a8e7de2e0b) | Apr 26, 2023 |
| MSI           | MAG B550M MORTAR            | [f91ac46cfd](https://linux-hardware.org/?probe=f91ac46cfd) | Apr 26, 2023 |
| HP            | 1825                        | [5a26051aec](https://linux-hardware.org/?probe=5a26051aec) | Apr 26, 2023 |
| Gigabyte      | Z370M D3H-CF                | [ada8ff75dd](https://linux-hardware.org/?probe=ada8ff75dd) | Apr 26, 2023 |
| MSI           | B450-A PRO MAX              | [2d7c2dd8f9](https://linux-hardware.org/?probe=2d7c2dd8f9) | Apr 26, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [45c453eb4e](https://linux-hardware.org/?probe=45c453eb4e) | Apr 26, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [b79a40ebdc](https://linux-hardware.org/?probe=b79a40ebdc) | Apr 26, 2023 |
| ASUSTek       | X99-A                       | [6788eea8d2](https://linux-hardware.org/?probe=6788eea8d2) | Apr 26, 2023 |
| MSI           | PRO Z690-A WIFI             | [23c9be7614](https://linux-hardware.org/?probe=23c9be7614) | Apr 26, 2023 |
| Pegatron      | IPXSB-H61                   | [2b0ee4d542](https://linux-hardware.org/?probe=2b0ee4d542) | Apr 26, 2023 |
| ASUSTek       | PRIME B450M-A               | [d8c1be05af](https://linux-hardware.org/?probe=d8c1be05af) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | [290f3ebad7](https://linux-hardware.org/?probe=290f3ebad7) | Apr 25, 2023 |
| Acer          | Aspire X3995                | [877c9deb7a](https://linux-hardware.org/?probe=877c9deb7a) | Apr 25, 2023 |
| Biostar       | A68N-5600E                  | [ccaeaae27b](https://linux-hardware.org/?probe=ccaeaae27b) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [4668a2409b](https://linux-hardware.org/?probe=4668a2409b) | Apr 25, 2023 |
| Acer          | Predator G3-605             | [37cd92a7f0](https://linux-hardware.org/?probe=37cd92a7f0) | Apr 25, 2023 |
| Acer          | Predator G3-605             | [0b966e7b88](https://linux-hardware.org/?probe=0b966e7b88) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b091628e5](https://linux-hardware.org/?probe=7b091628e5) | Apr 25, 2023 |
| Gigabyte      | Z270X-UD3-CF                | [06fbe4d0b6](https://linux-hardware.org/?probe=06fbe4d0b6) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| OEM           | HN B85 Ver:1.4              | [1da5934b27](https://linux-hardware.org/?probe=1da5934b27) | Apr 25, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [1a58c88206](https://linux-hardware.org/?probe=1a58c88206) | Apr 25, 2023 |
| ASUSTek       | M4A78LT-M                   | [11f1e291a7](https://linux-hardware.org/?probe=11f1e291a7) | Apr 25, 2023 |
| ASUSTek       | M3A                         | [c16000b1e4](https://linux-hardware.org/?probe=c16000b1e4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [342918aa38](https://linux-hardware.org/?probe=342918aa38) | Apr 24, 2023 |
| Lenovo        | 313A NOK                    | [34a521ebad](https://linux-hardware.org/?probe=34a521ebad) | Apr 24, 2023 |
| MSI           | H110M ECO                   | [bfa2b17374](https://linux-hardware.org/?probe=bfa2b17374) | Apr 24, 2023 |
| Dell          | 0VTJVC A00                  | [da7d66917d](https://linux-hardware.org/?probe=da7d66917d) | Apr 24, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [beabf00341](https://linux-hardware.org/?probe=beabf00341) | Apr 24, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e18fd8d449](https://linux-hardware.org/?probe=e18fd8d449) | Apr 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [ed8414c493](https://linux-hardware.org/?probe=ed8414c493) | Apr 24, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [267c5b8075](https://linux-hardware.org/?probe=267c5b8075) | Apr 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [695220be38](https://linux-hardware.org/?probe=695220be38) | Apr 24, 2023 |
| Lenovo        | 32E9 SDK0T76463 WIN 3422... | [9f49daf25a](https://linux-hardware.org/?probe=9f49daf25a) | Apr 24, 2023 |
| Lenovo        | 32E9 SDK0T76463 WIN 3422... | [cc7a31d3d6](https://linux-hardware.org/?probe=cc7a31d3d6) | Apr 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [eb716c53fa](https://linux-hardware.org/?probe=eb716c53fa) | Apr 24, 2023 |
| Gigabyte      | G41MT-S2                    | [de1981f9e6](https://linux-hardware.org/?probe=de1981f9e6) | Apr 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [39fd6ad31f](https://linux-hardware.org/?probe=39fd6ad31f) | Apr 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | [68d1859c93](https://linux-hardware.org/?probe=68d1859c93) | Apr 23, 2023 |
| Gigabyte      | Z97P-D3                     | [5da4c37f75](https://linux-hardware.org/?probe=5da4c37f75) | Apr 23, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [e653a5dd45](https://linux-hardware.org/?probe=e653a5dd45) | Apr 23, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [95e77b87f5](https://linux-hardware.org/?probe=95e77b87f5) | Apr 23, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [0e96ee4471](https://linux-hardware.org/?probe=0e96ee4471) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [793e094165](https://linux-hardware.org/?probe=793e094165) | Apr 23, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [eac9934073](https://linux-hardware.org/?probe=eac9934073) | Apr 23, 2023 |
| ASUSTek       | Maximus VII FORMULA         | [0d45b24479](https://linux-hardware.org/?probe=0d45b24479) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [b342cd8fe0](https://linux-hardware.org/?probe=b342cd8fe0) | Apr 23, 2023 |
| Intel         | DH61BE AAG14062-206         | [c1817da6ab](https://linux-hardware.org/?probe=c1817da6ab) | Apr 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [4a55a10fd0](https://linux-hardware.org/?probe=4a55a10fd0) | Apr 23, 2023 |
| ASUSTek       | PRIME Z390-A                | [3fc4048a96](https://linux-hardware.org/?probe=3fc4048a96) | Apr 23, 2023 |
| ASUSTek       | Z87-PRO                     | [08ebdd71ab](https://linux-hardware.org/?probe=08ebdd71ab) | Apr 23, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [1c85c89b5d](https://linux-hardware.org/?probe=1c85c89b5d) | Apr 22, 2023 |
| System76      | Thelio thelio-r1            | [d48efc62c4](https://linux-hardware.org/?probe=d48efc62c4) | Apr 22, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [1404fc66cf](https://linux-hardware.org/?probe=1404fc66cf) | Apr 22, 2023 |
| Gigabyte      | Z390 UD                     | [c9e17ad011](https://linux-hardware.org/?probe=c9e17ad011) | Apr 22, 2023 |
| Intel         | H81                         | [fbc2766f35](https://linux-hardware.org/?probe=fbc2766f35) | Apr 22, 2023 |
| Gigabyte      | Z790 UD                     | [8536a23081](https://linux-hardware.org/?probe=8536a23081) | Apr 22, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bab80153bf](https://linux-hardware.org/?probe=bab80153bf) | Apr 22, 2023 |
| MSI           | Z77A-G41                    | [9cd2294229](https://linux-hardware.org/?probe=9cd2294229) | Apr 22, 2023 |
| ASUSTek       | PRIME X570-P                | [f23eeda727](https://linux-hardware.org/?probe=f23eeda727) | Apr 22, 2023 |
| MSI           | B550-A PRO                  | [06bc639254](https://linux-hardware.org/?probe=06bc639254) | Apr 22, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [d4d3e7f8d6](https://linux-hardware.org/?probe=d4d3e7f8d6) | Apr 21, 2023 |
| MSI           | IONA                        | [3820fb6576](https://linux-hardware.org/?probe=3820fb6576) | Apr 21, 2023 |
| Shuttle       | FG45 V10                    | [b5a9d7b1e4](https://linux-hardware.org/?probe=b5a9d7b1e4) | Apr 21, 2023 |
| ASRock        | H81M-HDS R2.0               | [eaf8476afd](https://linux-hardware.org/?probe=eaf8476afd) | Apr 21, 2023 |
| Unknown       | Unknown                     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| HP            | 1825                        | [e586a2657b](https://linux-hardware.org/?probe=e586a2657b) | Apr 21, 2023 |
| HP            | 1494                        | [625373a1de](https://linux-hardware.org/?probe=625373a1de) | Apr 21, 2023 |
| ASUSTek       | PRIME B360M-A               | [61d7104ec4](https://linux-hardware.org/?probe=61d7104ec4) | Apr 21, 2023 |
| Dell          | 0RY206                      | [8290af518f](https://linux-hardware.org/?probe=8290af518f) | Apr 21, 2023 |
| ASUSTek       | PRIME TRX40-PRO S           | [b2ac72f8d9](https://linux-hardware.org/?probe=b2ac72f8d9) | Apr 20, 2023 |
| HP            | ProLiant MicroServer        | [ea76b8632f](https://linux-hardware.org/?probe=ea76b8632f) | Apr 20, 2023 |
| ASUSTek       | PRIME TRX40-PRO S           | [4748a2ce89](https://linux-hardware.org/?probe=4748a2ce89) | Apr 20, 2023 |
| ASRock        | G31M-S                      | [7c2bfcaeca](https://linux-hardware.org/?probe=7c2bfcaeca) | Apr 20, 2023 |
| Acer          | Aspire M3970                | [d43372f3fd](https://linux-hardware.org/?probe=d43372f3fd) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [42ca23ca64](https://linux-hardware.org/?probe=42ca23ca64) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [e315ba7088](https://linux-hardware.org/?probe=e315ba7088) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f5da23bee0](https://linux-hardware.org/?probe=f5da23bee0) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [e367a9a4ab](https://linux-hardware.org/?probe=e367a9a4ab) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| Apple         | Mac-F221BEC8                | [798a408c25](https://linux-hardware.org/?probe=798a408c25) | Apr 20, 2023 |
| ASRock        | A320M-HDV                   | [114bd5a129](https://linux-hardware.org/?probe=114bd5a129) | Apr 19, 2023 |
| Acer          | Veriton X2632G V:1.0        | [0fa4554c3c](https://linux-hardware.org/?probe=0fa4554c3c) | Apr 19, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b830d8001e](https://linux-hardware.org/?probe=b830d8001e) | Apr 19, 2023 |
| Gigabyte      | Z97-HD3                     | [8b560b455e](https://linux-hardware.org/?probe=8b560b455e) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| MSI           | PRO Z690-A WIFI             | [26c96a2c4b](https://linux-hardware.org/?probe=26c96a2c4b) | Apr 19, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [2822b1a8c3](https://linux-hardware.org/?probe=2822b1a8c3) | Apr 19, 2023 |
| ASUSTek       | Z87-PRO                     | [7981ad8440](https://linux-hardware.org/?probe=7981ad8440) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [c0a82bb35a](https://linux-hardware.org/?probe=c0a82bb35a) | Apr 19, 2023 |
| Intel         | DH61AG AAG23736-504         | [9a853b9c86](https://linux-hardware.org/?probe=9a853b9c86) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a775ede9a0](https://linux-hardware.org/?probe=a775ede9a0) | Apr 18, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [da85d2406d](https://linux-hardware.org/?probe=da85d2406d) | Apr 18, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [8bb9dc2419](https://linux-hardware.org/?probe=8bb9dc2419) | Apr 18, 2023 |
| HP            | 1825                        | [5c637a9ef6](https://linux-hardware.org/?probe=5c637a9ef6) | Apr 18, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | [ae7ea68877](https://linux-hardware.org/?probe=ae7ea68877) | Apr 18, 2023 |
| Medion        | BTDD-LT                     | [b26cb60a3f](https://linux-hardware.org/?probe=b26cb60a3f) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [eb66896af3](https://linux-hardware.org/?probe=eb66896af3) | Apr 18, 2023 |
| MSI           | PRO B660-A DDR4             | [b274726abd](https://linux-hardware.org/?probe=b274726abd) | Apr 17, 2023 |
| MSI           | Z97 GAMING 5                | [152e32b151](https://linux-hardware.org/?probe=152e32b151) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| Dell          | 0K83V0 A00                  | [9e0514e439](https://linux-hardware.org/?probe=9e0514e439) | Apr 17, 2023 |
| Dell          | 0J4NFV A01                  | [a6b3ac3ff2](https://linux-hardware.org/?probe=a6b3ac3ff2) | Apr 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5109f5c8d9](https://linux-hardware.org/?probe=5109f5c8d9) | Apr 17, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | [3154b04b37](https://linux-hardware.org/?probe=3154b04b37) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [dbd2cfbd81](https://linux-hardware.org/?probe=dbd2cfbd81) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | [44293ba6b9](https://linux-hardware.org/?probe=44293ba6b9) | Apr 17, 2023 |
| ASUSTek       | EX-B560M-V5                 | [243b7b3722](https://linux-hardware.org/?probe=243b7b3722) | Apr 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [45722c96bb](https://linux-hardware.org/?probe=45722c96bb) | Apr 17, 2023 |
| Dell          | 0F896N A03                  | [4ec01d373e](https://linux-hardware.org/?probe=4ec01d373e) | Apr 17, 2023 |
| ASRock        | B450M Pro4                  | [ddbe51a022](https://linux-hardware.org/?probe=ddbe51a022) | Apr 17, 2023 |
| HP            | 8055                        | [f9b8b05db5](https://linux-hardware.org/?probe=f9b8b05db5) | Apr 17, 2023 |
| HP            | 8055                        | [462446d664](https://linux-hardware.org/?probe=462446d664) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [a7f312ea0a](https://linux-hardware.org/?probe=a7f312ea0a) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [f1afe43806](https://linux-hardware.org/?probe=f1afe43806) | Apr 16, 2023 |
| MSI           | B560M PRO-VDH WIFI          | [fd0b3fe549](https://linux-hardware.org/?probe=fd0b3fe549) | Apr 16, 2023 |
| Dell          | 0TP412                      | [7491d6d66d](https://linux-hardware.org/?probe=7491d6d66d) | Apr 16, 2023 |
| Foxconn       | A7DA 3 series               | [a8f557c1c3](https://linux-hardware.org/?probe=a8f557c1c3) | Apr 16, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [e8b30a69f9](https://linux-hardware.org/?probe=e8b30a69f9) | Apr 16, 2023 |
| Foxconn       | A7DA 3 series               | [4f7648a3d0](https://linux-hardware.org/?probe=4f7648a3d0) | Apr 16, 2023 |
| Dell          | 0TP412                      | [c5f0ba736e](https://linux-hardware.org/?probe=c5f0ba736e) | Apr 16, 2023 |
| HP            | 18E4                        | [bc45bcdf89](https://linux-hardware.org/?probe=bc45bcdf89) | Apr 16, 2023 |
| Dell          | 0MR5MV A00                  | [ed13b58a51](https://linux-hardware.org/?probe=ed13b58a51) | Apr 16, 2023 |
| HP            | 1850                        | [9ba17e1d9c](https://linux-hardware.org/?probe=9ba17e1d9c) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| ASRock        | H87 Pro4                    | [e85b3e34b0](https://linux-hardware.org/?probe=e85b3e34b0) | Apr 16, 2023 |
| Lenovo        | ThinkCentre M71z 1782W14    | [c4434a61df](https://linux-hardware.org/?probe=c4434a61df) | Apr 15, 2023 |
| HP            | 83E2                        | [af01123687](https://linux-hardware.org/?probe=af01123687) | Apr 15, 2023 |
| HP            | 83E2                        | [f5052291a4](https://linux-hardware.org/?probe=f5052291a4) | Apr 15, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [fb75806ceb](https://linux-hardware.org/?probe=fb75806ceb) | Apr 15, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [6d930e2f8a](https://linux-hardware.org/?probe=6d930e2f8a) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [2c7e1238eb](https://linux-hardware.org/?probe=2c7e1238eb) | Apr 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [9deba6cdac](https://linux-hardware.org/?probe=9deba6cdac) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7c8e58956e](https://linux-hardware.org/?probe=7c8e58956e) | Apr 15, 2023 |
| HP            | 1850                        | [d30cea781b](https://linux-hardware.org/?probe=d30cea781b) | Apr 15, 2023 |
| Dell          | 0D24M8 A01                  | [5244c86993](https://linux-hardware.org/?probe=5244c86993) | Apr 15, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | [5439790362](https://linux-hardware.org/?probe=5439790362) | Apr 15, 2023 |
| ASUSTek       | ET1612I                     | [f67ace875b](https://linux-hardware.org/?probe=f67ace875b) | Apr 14, 2023 |
| HP            | 2B4B                        | [9103ce1fce](https://linux-hardware.org/?probe=9103ce1fce) | Apr 14, 2023 |
| Acer          | Aspire M3970                | [0792e082e7](https://linux-hardware.org/?probe=0792e082e7) | Apr 14, 2023 |
| Gigabyte      | H97M-D3H                    | [e48eeac368](https://linux-hardware.org/?probe=e48eeac368) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [87acc1eb9d](https://linux-hardware.org/?probe=87acc1eb9d) | Apr 14, 2023 |
| Gigabyte      | B560M DS3H V2               | [fe75c98b15](https://linux-hardware.org/?probe=fe75c98b15) | Apr 14, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | [9ab9baf194](https://linux-hardware.org/?probe=9ab9baf194) | Apr 14, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a1c457ea48](https://linux-hardware.org/?probe=a1c457ea48) | Apr 14, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [6cf54a6bf4](https://linux-hardware.org/?probe=6cf54a6bf4) | Apr 14, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [30d6d32fc1](https://linux-hardware.org/?probe=30d6d32fc1) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c3eb775c80](https://linux-hardware.org/?probe=c3eb775c80) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [654728e9fe](https://linux-hardware.org/?probe=654728e9fe) | Apr 13, 2023 |
| Dell          | 00V62H A00                  | [0632bfe4d0](https://linux-hardware.org/?probe=0632bfe4d0) | Apr 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [89a7f8f7e7](https://linux-hardware.org/?probe=89a7f8f7e7) | Apr 13, 2023 |
| Gigabyte      | B460M DS3H V2               | [4e09a1cd3e](https://linux-hardware.org/?probe=4e09a1cd3e) | Apr 13, 2023 |
| MSI           | A520M-A PRO                 | [b5f4a1670f](https://linux-hardware.org/?probe=b5f4a1670f) | Apr 13, 2023 |
| ECS           | G41T-R3                     | [2c589a38f7](https://linux-hardware.org/?probe=2c589a38f7) | Apr 13, 2023 |
| MSI           | X370 GAMING PLUS            | [f63c87bf19](https://linux-hardware.org/?probe=f63c87bf19) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| Intel         | DH67BL AAG10189-209         | [b8e206486d](https://linux-hardware.org/?probe=b8e206486d) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| HP            | 1495                        | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| ECS           | H61H2-MV                    | [5a3fbafb75](https://linux-hardware.org/?probe=5a3fbafb75) | Apr 12, 2023 |
| Dell          | 0XHGV1 A00                  | [6cbdeb350e](https://linux-hardware.org/?probe=6cbdeb350e) | Apr 12, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [4d3cf8103e](https://linux-hardware.org/?probe=4d3cf8103e) | Apr 12, 2023 |
| Intel         | D33217GKE G76540-203        | [c07a4d67ca](https://linux-hardware.org/?probe=c07a4d67ca) | Apr 12, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [378f217cd4](https://linux-hardware.org/?probe=378f217cd4) | Apr 12, 2023 |
| Gigabyte      | X79-UP4                     | [8f9b60caf3](https://linux-hardware.org/?probe=8f9b60caf3) | Apr 12, 2023 |
| ASRock        | H410D4-P1                   | [3f7d6e5bfb](https://linux-hardware.org/?probe=3f7d6e5bfb) | Apr 12, 2023 |
| Dell          | 042P49 A02                  | [b6d105b2b9](https://linux-hardware.org/?probe=b6d105b2b9) | Apr 12, 2023 |
| MiTAC         | PD10EHI                     | [13f79a1843](https://linux-hardware.org/?probe=13f79a1843) | Apr 12, 2023 |
| Win elemen... | M600                        | [4268d36ca4](https://linux-hardware.org/?probe=4268d36ca4) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | [ef5cbba147](https://linux-hardware.org/?probe=ef5cbba147) | Apr 12, 2023 |
| Dell          | 0K83V0 A00                  | [3bc76fa8ab](https://linux-hardware.org/?probe=3bc76fa8ab) | Apr 12, 2023 |
| Gigabyte      | 990FXA-UD3                  | [30fdc58d69](https://linux-hardware.org/?probe=30fdc58d69) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | [1649a1f9b5](https://linux-hardware.org/?probe=1649a1f9b5) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | [497756c5ab](https://linux-hardware.org/?probe=497756c5ab) | Apr 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [46eba03bed](https://linux-hardware.org/?probe=46eba03bed) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [dc55b7997e](https://linux-hardware.org/?probe=dc55b7997e) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [b35d9a7487](https://linux-hardware.org/?probe=b35d9a7487) | Apr 12, 2023 |
| ASUSTek       | H110M-A                     | [2f7cf166f0](https://linux-hardware.org/?probe=2f7cf166f0) | Apr 11, 2023 |
| Acer          | H57M01                      | [c62231ca98](https://linux-hardware.org/?probe=c62231ca98) | Apr 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| MSI           | A320M-A PRO MAX             | [d5e033eb2e](https://linux-hardware.org/?probe=d5e033eb2e) | Apr 11, 2023 |
| Gigabyte      | Z68P-DS3                    | [6026c92eaa](https://linux-hardware.org/?probe=6026c92eaa) | Apr 11, 2023 |
| ASUSTek       | H97I-PLUS                   | [8fdee327be](https://linux-hardware.org/?probe=8fdee327be) | Apr 11, 2023 |
| ASRock        | B85M-HDS R2.0               | [24bdbac13a](https://linux-hardware.org/?probe=24bdbac13a) | Apr 11, 2023 |
| ASUSTek       | PRIME Z690-A                | [b434d4a0b5](https://linux-hardware.org/?probe=b434d4a0b5) | Apr 11, 2023 |
| Dell          | 0GXM1W A01                  | [eafb6edf1e](https://linux-hardware.org/?probe=eafb6edf1e) | Apr 10, 2023 |
| Dell          | 0GXM1W A01                  | [cbd05b393a](https://linux-hardware.org/?probe=cbd05b393a) | Apr 10, 2023 |
| Dell          | 0F6X5P A00                  | [ab53417291](https://linux-hardware.org/?probe=ab53417291) | Apr 10, 2023 |
| ASRock        | 960GC-GS FX                 | [e3eee10ad1](https://linux-hardware.org/?probe=e3eee10ad1) | Apr 10, 2023 |
| Gigabyte      | B450M H                     | [7806838777](https://linux-hardware.org/?probe=7806838777) | Apr 09, 2023 |
| MSI           | MS-B0A21                    | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| Dell          | 0WR7PY A00                  | [2719755017](https://linux-hardware.org/?probe=2719755017) | Apr 08, 2023 |
| Gigabyte      | Z690 UD DDR4                | [6f2fcf320a](https://linux-hardware.org/?probe=6f2fcf320a) | Apr 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [097df073bd](https://linux-hardware.org/?probe=097df073bd) | Apr 08, 2023 |
| ASRock        | X99 Taichi                  | [7ae23e9c38](https://linux-hardware.org/?probe=7ae23e9c38) | Apr 07, 2023 |
| HP            | ProLiant MicroServer Gen... | [0258b5925f](https://linux-hardware.org/?probe=0258b5925f) | Apr 07, 2023 |
| Gigabyte      | F2A68HM-H                   | [98bc626360](https://linux-hardware.org/?probe=98bc626360) | Apr 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a6e4c91ee0](https://linux-hardware.org/?probe=a6e4c91ee0) | Apr 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [64b9978ed0](https://linux-hardware.org/?probe=64b9978ed0) | Apr 06, 2023 |
| HP            | 8055                        | [8ef78a4649](https://linux-hardware.org/?probe=8ef78a4649) | Apr 06, 2023 |
| HP            | 8055                        | [8afe68fd20](https://linux-hardware.org/?probe=8afe68fd20) | Apr 06, 2023 |
| eMachines     | EMCP73VT-PM                 | [936f8c6692](https://linux-hardware.org/?probe=936f8c6692) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [b81dc294df](https://linux-hardware.org/?probe=b81dc294df) | Apr 06, 2023 |
| ASUSTek       | Z87M-PLUS                   | [a17064a0db](https://linux-hardware.org/?probe=a17064a0db) | Apr 06, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f1e8cec7f8](https://linux-hardware.org/?probe=f1e8cec7f8) | Apr 06, 2023 |
| ASUSTek       | H97M-E                      | [4d639304bf](https://linux-hardware.org/?probe=4d639304bf) | Apr 05, 2023 |
| Biostar       | N68S3B                      | [3b25aad650](https://linux-hardware.org/?probe=3b25aad650) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4f0083481e](https://linux-hardware.org/?probe=4f0083481e) | Apr 05, 2023 |
| Lenovo        | 313A NOK                    | [824eadb157](https://linux-hardware.org/?probe=824eadb157) | Apr 05, 2023 |
| Dell          | 0HHV7N A00                  | [b715735168](https://linux-hardware.org/?probe=b715735168) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [7dc5bea17c](https://linux-hardware.org/?probe=7dc5bea17c) | Apr 05, 2023 |
| ASUSTek       | Benicia                     | [8dc3b9ede2](https://linux-hardware.org/?probe=8dc3b9ede2) | Apr 05, 2023 |
| Dell          | 0HHV7N A00                  | [4f1c6c0b48](https://linux-hardware.org/?probe=4f1c6c0b48) | Apr 05, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [5304b3bb66](https://linux-hardware.org/?probe=5304b3bb66) | Apr 05, 2023 |
| ASRock        | A320M-HDV R4.0              | [c26cae6392](https://linux-hardware.org/?probe=c26cae6392) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3569575b7c](https://linux-hardware.org/?probe=3569575b7c) | Apr 05, 2023 |
| MSI           | 2A9C                        | [7a007c46d0](https://linux-hardware.org/?probe=7a007c46d0) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b7068fce05](https://linux-hardware.org/?probe=b7068fce05) | Apr 04, 2023 |
| HP            | 2B52                        | [4def1937bc](https://linux-hardware.org/?probe=4def1937bc) | Apr 04, 2023 |
| MSI           | H110M ECO                   | [983153c81e](https://linux-hardware.org/?probe=983153c81e) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b0126bbd6a](https://linux-hardware.org/?probe=b0126bbd6a) | Apr 04, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [015c7769f4](https://linux-hardware.org/?probe=015c7769f4) | Apr 04, 2023 |
| ASUSTek       | P5N-EM HDMI                 | [2db7dfe129](https://linux-hardware.org/?probe=2db7dfe129) | Apr 04, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [250b63078d](https://linux-hardware.org/?probe=250b63078d) | Apr 04, 2023 |
| ASRock        | B450M Pro4                  | [6bf9bb58c5](https://linux-hardware.org/?probe=6bf9bb58c5) | Apr 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6e8ca2befa](https://linux-hardware.org/?probe=6e8ca2befa) | Apr 04, 2023 |
| MSI           | MAG B560M MORTAR            | [bbb597effc](https://linux-hardware.org/?probe=bbb597effc) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [32958eb969](https://linux-hardware.org/?probe=32958eb969) | Apr 04, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [613715ddc7](https://linux-hardware.org/?probe=613715ddc7) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e22fcce997](https://linux-hardware.org/?probe=e22fcce997) | Apr 04, 2023 |
| Dell          | 07PR60 A02                  | [c41c1c9ead](https://linux-hardware.org/?probe=c41c1c9ead) | Apr 04, 2023 |
| Wistron       | ProLiant ML110 G6           | [c898729067](https://linux-hardware.org/?probe=c898729067) | Apr 04, 2023 |
| Gigabyte      | Z77-D3H                     | [6f4b1ef628](https://linux-hardware.org/?probe=6f4b1ef628) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [fd09aac13e](https://linux-hardware.org/?probe=fd09aac13e) | Apr 04, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [e6b864d24e](https://linux-hardware.org/?probe=e6b864d24e) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [8eb8bb5119](https://linux-hardware.org/?probe=8eb8bb5119) | Apr 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [c05957b7c0](https://linux-hardware.org/?probe=c05957b7c0) | Apr 03, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [22cc49b906](https://linux-hardware.org/?probe=22cc49b906) | Apr 03, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [db0170e4f7](https://linux-hardware.org/?probe=db0170e4f7) | Apr 03, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [11d3f42d9c](https://linux-hardware.org/?probe=11d3f42d9c) | Apr 03, 2023 |
| Gigabyte      | Z77X-UD3H                   | [5499373552](https://linux-hardware.org/?probe=5499373552) | Apr 03, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [f0de4366f7](https://linux-hardware.org/?probe=f0de4366f7) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0662f665d7](https://linux-hardware.org/?probe=0662f665d7) | Apr 03, 2023 |
| HP            | 1850                        | [04243d9db8](https://linux-hardware.org/?probe=04243d9db8) | Apr 03, 2023 |
| HP            | 1850                        | [62b8f8056b](https://linux-hardware.org/?probe=62b8f8056b) | Apr 03, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c9cd8b0217](https://linux-hardware.org/?probe=c9cd8b0217) | Apr 03, 2023 |
| ASUSTek       | P8H61-I R2.0                | [ad5bbe6fdb](https://linux-hardware.org/?probe=ad5bbe6fdb) | Apr 03, 2023 |
| ASUSTek       | P8H61-I R2.0                | [1df5ebb958](https://linux-hardware.org/?probe=1df5ebb958) | Apr 03, 2023 |
| Lenovo        | SHARKBAY NOK                | [4f7dd215fe](https://linux-hardware.org/?probe=4f7dd215fe) | Apr 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [c98048fb64](https://linux-hardware.org/?probe=c98048fb64) | Apr 02, 2023 |
| Intel         | DZ68BC AAG30742-401         | [83c97bc045](https://linux-hardware.org/?probe=83c97bc045) | Apr 02, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [e3845b9610](https://linux-hardware.org/?probe=e3845b9610) | Apr 02, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [36947e0f6f](https://linux-hardware.org/?probe=36947e0f6f) | Apr 02, 2023 |
| MSI           | Boston                      | [5a875def3f](https://linux-hardware.org/?probe=5a875def3f) | Apr 02, 2023 |
| MSI           | MAG H670 TOMAHAWK WIFI D... | [453a5fd36e](https://linux-hardware.org/?probe=453a5fd36e) | Apr 02, 2023 |
| Dell          | 0HHV7N A00                  | [d986429836](https://linux-hardware.org/?probe=d986429836) | Apr 02, 2023 |
| Lenovo        | SHARKBAY NOK                | [e67cca2c98](https://linux-hardware.org/?probe=e67cca2c98) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [16e982e5cb](https://linux-hardware.org/?probe=16e982e5cb) | Apr 02, 2023 |
| ASRock        | B450 Pro4                   | [ac4522914d](https://linux-hardware.org/?probe=ac4522914d) | Apr 02, 2023 |
| HP            | 339A                        | [fc8d521237](https://linux-hardware.org/?probe=fc8d521237) | Apr 02, 2023 |
| Acer          | Predator G3-605             | [f7ca1573d0](https://linux-hardware.org/?probe=f7ca1573d0) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [99f18572a2](https://linux-hardware.org/?probe=99f18572a2) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [43ab458990](https://linux-hardware.org/?probe=43ab458990) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [98cd4ea3a6](https://linux-hardware.org/?probe=98cd4ea3a6) | Apr 01, 2023 |
| Acer          | Aspire X3400                | [093b0a0239](https://linux-hardware.org/?probe=093b0a0239) | Apr 01, 2023 |
| MSI           | PRO H610M-B DDR4            | [5fc258772a](https://linux-hardware.org/?probe=5fc258772a) | Apr 01, 2023 |
| MSI           | PRO H610M-B DDR4            | [2addcb84c6](https://linux-hardware.org/?probe=2addcb84c6) | Apr 01, 2023 |
| Acer          | H57M01                      | [215701a84d](https://linux-hardware.org/?probe=215701a84d) | Apr 01, 2023 |
| Dell          | 09M8Y8 A01                  | [17d5390549](https://linux-hardware.org/?probe=17d5390549) | Apr 01, 2023 |
| Dell          | 09KPNV A01                  | [2b25e4872f](https://linux-hardware.org/?probe=2b25e4872f) | Apr 01, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [f05009caac](https://linux-hardware.org/?probe=f05009caac) | Apr 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [2be0fa6524](https://linux-hardware.org/?probe=2be0fa6524) | Apr 01, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [45a242d18f](https://linux-hardware.org/?probe=45a242d18f) | Mar 31, 2023 |
| HP            | 0A64h                       | [f4fd3904f0](https://linux-hardware.org/?probe=f4fd3904f0) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [6694c9279d](https://linux-hardware.org/?probe=6694c9279d) | Mar 31, 2023 |
| ASUSTek       | Z97-K                       | [da56f6c38c](https://linux-hardware.org/?probe=da56f6c38c) | Mar 31, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [0945961c85](https://linux-hardware.org/?probe=0945961c85) | Mar 31, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [72c08c8ca9](https://linux-hardware.org/?probe=72c08c8ca9) | Mar 31, 2023 |
| Dell          | 0FG47G A02                  | [d1cf6fa11e](https://linux-hardware.org/?probe=d1cf6fa11e) | Mar 31, 2023 |
| Gigabyte      | H310M H x.x                 | [68fce9ae2d](https://linux-hardware.org/?probe=68fce9ae2d) | Mar 31, 2023 |
| ECS           | H61H2-M6                    | [6c33ee7e15](https://linux-hardware.org/?probe=6c33ee7e15) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | [f8e723a8dc](https://linux-hardware.org/?probe=f8e723a8dc) | Mar 31, 2023 |
| MSI           | PRO X670-P WIFI             | [bb72de54b6](https://linux-hardware.org/?probe=bb72de54b6) | Mar 31, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [0e374d0aea](https://linux-hardware.org/?probe=0e374d0aea) | Mar 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [c239e06998](https://linux-hardware.org/?probe=c239e06998) | Mar 31, 2023 |
| Gigabyte      | F2A88X-UP4                  | [72c4b553b4](https://linux-hardware.org/?probe=72c4b553b4) | Mar 31, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3aac57dfbd](https://linux-hardware.org/?probe=3aac57dfbd) | Mar 30, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [4cfac9a162](https://linux-hardware.org/?probe=4cfac9a162) | Mar 30, 2023 |
| Unknown       | Unknown                     | [3773f3cd04](https://linux-hardware.org/?probe=3773f3cd04) | Mar 30, 2023 |
| Dell          | 0KV62T A02                  | [c7765df604](https://linux-hardware.org/?probe=c7765df604) | Mar 30, 2023 |
| Packard Be... | FMP55                       | [88a15e20b2](https://linux-hardware.org/?probe=88a15e20b2) | Mar 30, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [41a76fad3f](https://linux-hardware.org/?probe=41a76fad3f) | Mar 30, 2023 |
| MSI           | X79A-GD45                   | [6d78703b2c](https://linux-hardware.org/?probe=6d78703b2c) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [92981c741d](https://linux-hardware.org/?probe=92981c741d) | Mar 30, 2023 |
| MSI           | PRO X670-P WIFI             | [ed35fbea6c](https://linux-hardware.org/?probe=ed35fbea6c) | Mar 30, 2023 |
| HP            | 82B4                        | [0829a64947](https://linux-hardware.org/?probe=0829a64947) | Mar 30, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [dfd9900ccf](https://linux-hardware.org/?probe=dfd9900ccf) | Mar 30, 2023 |
| ASUSTek       | M5A97                       | [4d12d122e1](https://linux-hardware.org/?probe=4d12d122e1) | Mar 30, 2023 |
| Shuttle       | FH170                       | [0fa0f1ab72](https://linux-hardware.org/?probe=0fa0f1ab72) | Mar 30, 2023 |
| ASUSTek       | P5E WS Pro                  | [6c70ac23df](https://linux-hardware.org/?probe=6c70ac23df) | Mar 30, 2023 |
| Gigabyte      | H81M-S2V                    | [5a16920bc0](https://linux-hardware.org/?probe=5a16920bc0) | Mar 30, 2023 |
| HP            | 8591                        | [b887990c12](https://linux-hardware.org/?probe=b887990c12) | Mar 30, 2023 |
| MSI           | FM2-A75MA-E35               | [10de0ae048](https://linux-hardware.org/?probe=10de0ae048) | Mar 30, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [185cb6df15](https://linux-hardware.org/?probe=185cb6df15) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [cd308ca372](https://linux-hardware.org/?probe=cd308ca372) | Mar 29, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | [7b984afb2c](https://linux-hardware.org/?probe=7b984afb2c) | Mar 29, 2023 |
| ASUSTek       | H81M-V3                     | [fd123bea36](https://linux-hardware.org/?probe=fd123bea36) | Mar 29, 2023 |
| Dell          | 09KPNV A01                  | [6024b90eea](https://linux-hardware.org/?probe=6024b90eea) | Mar 29, 2023 |
| Gigabyte      | GA-A75-UD4H                 | [e5433e75fb](https://linux-hardware.org/?probe=e5433e75fb) | Mar 29, 2023 |
| MSI           | X79A-GD45                   | [bb4680bc5b](https://linux-hardware.org/?probe=bb4680bc5b) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [23256b54cf](https://linux-hardware.org/?probe=23256b54cf) | Mar 29, 2023 |
| Intel         | H61                         | [bb6e201a08](https://linux-hardware.org/?probe=bb6e201a08) | Mar 29, 2023 |
| Gigabyte      | P41T-D3                     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| Intel         | B75                         | [2bddb84c2e](https://linux-hardware.org/?probe=2bddb84c2e) | Mar 29, 2023 |
| ASUSTek       | H81M-V3                     | [ce98454e55](https://linux-hardware.org/?probe=ce98454e55) | Mar 29, 2023 |
| Dell          | 0200DY A01                  | [095eb7be41](https://linux-hardware.org/?probe=095eb7be41) | Mar 29, 2023 |
| Gigabyte      | B365M DS3H                  | [e6b01be2f1](https://linux-hardware.org/?probe=e6b01be2f1) | Mar 29, 2023 |
| ASUSTek       | H110M-A                     | [147c0afb99](https://linux-hardware.org/?probe=147c0afb99) | Mar 29, 2023 |
| ASRock        | H61M-DG3/USB3               | [6e7b188568](https://linux-hardware.org/?probe=6e7b188568) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [7ec74ffcfa](https://linux-hardware.org/?probe=7ec74ffcfa) | Mar 28, 2023 |
| ASUSTek       | Z97-P                       | [0a0ca96d28](https://linux-hardware.org/?probe=0a0ca96d28) | Mar 28, 2023 |
| MSI           | Z170A SLI PLUS              | [50affe59d1](https://linux-hardware.org/?probe=50affe59d1) | Mar 28, 2023 |
| Lenovo        | SHARKBAY NOK                | [0cbe19c074](https://linux-hardware.org/?probe=0cbe19c074) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [7e5cb33850](https://linux-hardware.org/?probe=7e5cb33850) | Mar 28, 2023 |
| ASRock        | X399 Taichi                 | [f16690a3df](https://linux-hardware.org/?probe=f16690a3df) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [19ffc63f56](https://linux-hardware.org/?probe=19ffc63f56) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | [7f46837f94](https://linux-hardware.org/?probe=7f46837f94) | Mar 28, 2023 |
| Pegatron      | 2AE3                        | [806b4e1780](https://linux-hardware.org/?probe=806b4e1780) | Mar 28, 2023 |
| Pegatron      | 2AE3                        | [23ce0f4fd5](https://linux-hardware.org/?probe=23ce0f4fd5) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b8d58bafe3](https://linux-hardware.org/?probe=b8d58bafe3) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [68117fedfe](https://linux-hardware.org/?probe=68117fedfe) | Mar 28, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [cdb2c38b76](https://linux-hardware.org/?probe=cdb2c38b76) | Mar 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [1dd1eab13e](https://linux-hardware.org/?probe=1dd1eab13e) | Mar 27, 2023 |
| Pegatron      | IPMIP-H55-GEN               | [7dcf9e9b51](https://linux-hardware.org/?probe=7dcf9e9b51) | Mar 27, 2023 |
| HP            | 3648h                       | [fbc5138852](https://linux-hardware.org/?probe=fbc5138852) | Mar 27, 2023 |
| MSI           | X99A SLI PLUS               | [519fc70e27](https://linux-hardware.org/?probe=519fc70e27) | Mar 27, 2023 |
| ASRock        | X570 Steel Legend           | [490155a63a](https://linux-hardware.org/?probe=490155a63a) | Mar 27, 2023 |
| MSI           | Z170A SLI PLUS              | [8a1c592e98](https://linux-hardware.org/?probe=8a1c592e98) | Mar 27, 2023 |
| Gigabyte      | A520M H                     | [7afe508254](https://linux-hardware.org/?probe=7afe508254) | Mar 27, 2023 |
| Gigabyte      | Z590 GAMING X               | [de1cb772e9](https://linux-hardware.org/?probe=de1cb772e9) | Mar 27, 2023 |
| Gigabyte      | Z590 GAMING X               | [db7671affd](https://linux-hardware.org/?probe=db7671affd) | Mar 27, 2023 |
| ASUSTek       | P8H61-M LE                  | [e834f14d64](https://linux-hardware.org/?probe=e834f14d64) | Mar 27, 2023 |
| Intel         | X58M                        | [823813881b](https://linux-hardware.org/?probe=823813881b) | Mar 27, 2023 |
| MSI           | PRO H610M-B DDR4            | [a9ca07dc80](https://linux-hardware.org/?probe=a9ca07dc80) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| ASRock        | B365 Pro4                   | [ec1dd7f3ab](https://linux-hardware.org/?probe=ec1dd7f3ab) | Mar 26, 2023 |
| Lenovo        | ThinkCentre M90p 3282A8U    | [5edac0955d](https://linux-hardware.org/?probe=5edac0955d) | Mar 26, 2023 |
| Gigabyte      | H310M H x.x                 | [d79b6fc95c](https://linux-hardware.org/?probe=d79b6fc95c) | Mar 26, 2023 |
| Wistron       | ProLiant ML110 G6           | [2e14ac2984](https://linux-hardware.org/?probe=2e14ac2984) | Mar 26, 2023 |
| MSI           | B550-A PRO                  | [eddf5a759a](https://linux-hardware.org/?probe=eddf5a759a) | Mar 26, 2023 |
| HP            | 0B54h D                     | [540caaf04c](https://linux-hardware.org/?probe=540caaf04c) | Mar 26, 2023 |
| ASUSTek       | P5W DH Deluxe               | [781cafa540](https://linux-hardware.org/?probe=781cafa540) | Mar 26, 2023 |
| Gigabyte      | A520M H                     | [cfacabcd33](https://linux-hardware.org/?probe=cfacabcd33) | Mar 26, 2023 |
| Gigabyte      | A520M H                     | [ed01b04ada](https://linux-hardware.org/?probe=ed01b04ada) | Mar 26, 2023 |
| Shuttle       | B10IE01                     | [bc74a6b1a2](https://linux-hardware.org/?probe=bc74a6b1a2) | Mar 26, 2023 |
| Dell          | 0MGK50 A02                  | [75b4691fd2](https://linux-hardware.org/?probe=75b4691fd2) | Mar 26, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c7e347798a](https://linux-hardware.org/?probe=c7e347798a) | Mar 26, 2023 |
| ASUSTek       | P5B-Deluxe                  | [f5a9d12043](https://linux-hardware.org/?probe=f5a9d12043) | Mar 26, 2023 |
| Lenovo        | ThinkCentre M90p 3282A8U    | [40b8057336](https://linux-hardware.org/?probe=40b8057336) | Mar 26, 2023 |
| Intel         | DG41CN AAE82429-102         | [c671afb118](https://linux-hardware.org/?probe=c671afb118) | Mar 26, 2023 |
| HP            | 339A                        | [1009c2d048](https://linux-hardware.org/?probe=1009c2d048) | Mar 26, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [b7b93f24a2](https://linux-hardware.org/?probe=b7b93f24a2) | Mar 26, 2023 |
| Gigabyte      | X58A-UD3R                   | [2325b601fe](https://linux-hardware.org/?probe=2325b601fe) | Mar 25, 2023 |
| ASRock        | A320M-HDV R4.0              | [1b5f2b52bc](https://linux-hardware.org/?probe=1b5f2b52bc) | Mar 25, 2023 |
| Dell          | 02YYK5 A01                  | [92e64e0e8c](https://linux-hardware.org/?probe=92e64e0e8c) | Mar 25, 2023 |
| Gigabyte      | Z77X-D3H                    | [5fff36a878](https://linux-hardware.org/?probe=5fff36a878) | Mar 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [98dc4bb06b](https://linux-hardware.org/?probe=98dc4bb06b) | Mar 25, 2023 |
| ASUSTek       | H81I-PLUS                   | [bb353ccddf](https://linux-hardware.org/?probe=bb353ccddf) | Mar 25, 2023 |
| Packard Be... | FIH57                       | [794fd45482](https://linux-hardware.org/?probe=794fd45482) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | [41289d94bf](https://linux-hardware.org/?probe=41289d94bf) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | [1ccaab03c4](https://linux-hardware.org/?probe=1ccaab03c4) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | [104b9b1c12](https://linux-hardware.org/?probe=104b9b1c12) | Mar 25, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | [02d9269abc](https://linux-hardware.org/?probe=02d9269abc) | Mar 25, 2023 |
| HP            | 18E9                        | [f015f44555](https://linux-hardware.org/?probe=f015f44555) | Mar 25, 2023 |
| Dell          | 00V62H A01                  | [5312ec3cc9](https://linux-hardware.org/?probe=5312ec3cc9) | Mar 25, 2023 |
| HP            | 8906 SMVB                   | [7650a804d9](https://linux-hardware.org/?probe=7650a804d9) | Mar 25, 2023 |
| Dell          | 02YYK5 A01                  | [aeb58a6898](https://linux-hardware.org/?probe=aeb58a6898) | Mar 24, 2023 |
| ASUSTek       | Basswood3G                  | [d71f476c72](https://linux-hardware.org/?probe=d71f476c72) | Mar 24, 2023 |
| Dell          | 0TP406                      | [a58cf3b551](https://linux-hardware.org/?probe=a58cf3b551) | Mar 24, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [8a0cc5a4cb](https://linux-hardware.org/?probe=8a0cc5a4cb) | Mar 24, 2023 |
| HP            | 0A64h                       | [c53db667a1](https://linux-hardware.org/?probe=c53db667a1) | Mar 24, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [fea1e4cf50](https://linux-hardware.org/?probe=fea1e4cf50) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eeeac5db0f](https://linux-hardware.org/?probe=eeeac5db0f) | Mar 24, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [b5cecce6b9](https://linux-hardware.org/?probe=b5cecce6b9) | Mar 24, 2023 |
| Intel         | X99 V1.x                    | [391a73b307](https://linux-hardware.org/?probe=391a73b307) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [dc56fbfedb](https://linux-hardware.org/?probe=dc56fbfedb) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [67d60d55e4](https://linux-hardware.org/?probe=67d60d55e4) | Mar 24, 2023 |
| ASRock        | H310CM-HDV/M.2              | [cebe46bd74](https://linux-hardware.org/?probe=cebe46bd74) | Mar 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [360866bcc5](https://linux-hardware.org/?probe=360866bcc5) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0c824a1f88](https://linux-hardware.org/?probe=0c824a1f88) | Mar 24, 2023 |
| HP            | 2B05                        | [b34e6d230c](https://linux-hardware.org/?probe=b34e6d230c) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [10b7d76bff](https://linux-hardware.org/?probe=10b7d76bff) | Mar 24, 2023 |
| MSI           | Z390-A PRO                  | [36d6fdda74](https://linux-hardware.org/?probe=36d6fdda74) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [8af246641b](https://linux-hardware.org/?probe=8af246641b) | Mar 24, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [704fb36197](https://linux-hardware.org/?probe=704fb36197) | Mar 23, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [a5795c9f91](https://linux-hardware.org/?probe=a5795c9f91) | Mar 23, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [cd3e7fa4e5](https://linux-hardware.org/?probe=cd3e7fa4e5) | Mar 23, 2023 |
| HP            | 1905                        | [7bccc34bf4](https://linux-hardware.org/?probe=7bccc34bf4) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6a57dfd8fc](https://linux-hardware.org/?probe=6a57dfd8fc) | Mar 23, 2023 |
| MSI           | G41M-P26                    | [49854744e6](https://linux-hardware.org/?probe=49854744e6) | Mar 23, 2023 |
| AMI           | Intel                       | [5e7b21c227](https://linux-hardware.org/?probe=5e7b21c227) | Mar 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [7d303a08d4](https://linux-hardware.org/?probe=7d303a08d4) | Mar 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [20267be489](https://linux-hardware.org/?probe=20267be489) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | [e1783f9cd4](https://linux-hardware.org/?probe=e1783f9cd4) | Mar 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [1a2e1919ee](https://linux-hardware.org/?probe=1a2e1919ee) | Mar 22, 2023 |
| ASUSTek       | X99-E                       | [62535f81e4](https://linux-hardware.org/?probe=62535f81e4) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [47b661fcb3](https://linux-hardware.org/?probe=47b661fcb3) | Mar 22, 2023 |
| ASUSTek       | PB60                        | [ec438486aa](https://linux-hardware.org/?probe=ec438486aa) | Mar 22, 2023 |
| ASRockRack    | B665D4U-1L                  | [2be23ead3c](https://linux-hardware.org/?probe=2be23ead3c) | Mar 22, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [49bc505f3e](https://linux-hardware.org/?probe=49bc505f3e) | Mar 22, 2023 |
| ASUSTek       | X99-E                       | [eb6fe4121d](https://linux-hardware.org/?probe=eb6fe4121d) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [f848ecf9cf](https://linux-hardware.org/?probe=f848ecf9cf) | Mar 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [568fac441d](https://linux-hardware.org/?probe=568fac441d) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [789ca3dc74](https://linux-hardware.org/?probe=789ca3dc74) | Mar 22, 2023 |
| MSI           | Z97 GAMING 7                | [4fbe5017fe](https://linux-hardware.org/?probe=4fbe5017fe) | Mar 21, 2023 |
| HP            | 339A                        | [f1a067a512](https://linux-hardware.org/?probe=f1a067a512) | Mar 21, 2023 |
| HP            | 1495                        | [3fe89757bb](https://linux-hardware.org/?probe=3fe89757bb) | Mar 21, 2023 |
| HP            | 1494                        | [e682c9975e](https://linux-hardware.org/?probe=e682c9975e) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [844b9094f9](https://linux-hardware.org/?probe=844b9094f9) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [846f31de3e](https://linux-hardware.org/?probe=846f31de3e) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [7ccc7e9ae1](https://linux-hardware.org/?probe=7ccc7e9ae1) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [4544e68d4a](https://linux-hardware.org/?probe=4544e68d4a) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [96c3f3ecc4](https://linux-hardware.org/?probe=96c3f3ecc4) | Mar 21, 2023 |
| Dell          | 09KPNV A00                  | [5074a23172](https://linux-hardware.org/?probe=5074a23172) | Mar 20, 2023 |
| Unknown       | Unknown                     | [a931b7a520](https://linux-hardware.org/?probe=a931b7a520) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| MSI           | H310M PRO-VD                | [1b98d965e7](https://linux-hardware.org/?probe=1b98d965e7) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [436b9d15b0](https://linux-hardware.org/?probe=436b9d15b0) | Mar 20, 2023 |
| Gigabyte      | H310M H x.x                 | [0d7cc03c37](https://linux-hardware.org/?probe=0d7cc03c37) | Mar 20, 2023 |
| Intel         | DX58OG AAG10926-203         | [f5e2774fb9](https://linux-hardware.org/?probe=f5e2774fb9) | Mar 20, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [662d96a2ed](https://linux-hardware.org/?probe=662d96a2ed) | Mar 20, 2023 |
| ASUSTek       | PRIME X570-P                | [417d3cf9b7](https://linux-hardware.org/?probe=417d3cf9b7) | Mar 19, 2023 |
| Gigabyte      | GB-BRR7H-4700               | [9d7f6de46c](https://linux-hardware.org/?probe=9d7f6de46c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [adc87fc9fa](https://linux-hardware.org/?probe=adc87fc9fa) | Mar 19, 2023 |
| ASUSTek       | PRIME B450M-A II            | [eab4473d9f](https://linux-hardware.org/?probe=eab4473d9f) | Mar 19, 2023 |
| ASUSTek       | PRIME B250M-K               | [99cb000a4e](https://linux-hardware.org/?probe=99cb000a4e) | Mar 19, 2023 |
| ASUSTek       | P5K                         | [5f34498a89](https://linux-hardware.org/?probe=5f34498a89) | Mar 19, 2023 |
| MSI           | MS-B0A21                    | [7b5c0f63da](https://linux-hardware.org/?probe=7b5c0f63da) | Mar 18, 2023 |
| Dell          | 0K240Y A01                  | [269f35c6d4](https://linux-hardware.org/?probe=269f35c6d4) | Mar 18, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [c399d3fbf5](https://linux-hardware.org/?probe=c399d3fbf5) | Mar 18, 2023 |
| Intel         | H61                         | [10b44e8f3e](https://linux-hardware.org/?probe=10b44e8f3e) | Mar 18, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [7cf7439659](https://linux-hardware.org/?probe=7cf7439659) | Mar 18, 2023 |
| ASRock        | 4X4-4000 Series             | [3718d345ca](https://linux-hardware.org/?probe=3718d345ca) | Mar 18, 2023 |
| ASRock        | QC6000M                     | [b897493246](https://linux-hardware.org/?probe=b897493246) | Mar 18, 2023 |
| Intel         | DG41RQ AAE54511-203         | [a5775c7491](https://linux-hardware.org/?probe=a5775c7491) | Mar 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [2a17e297a2](https://linux-hardware.org/?probe=2a17e297a2) | Mar 17, 2023 |
| Medion        | MS-7707                     | [4748632926](https://linux-hardware.org/?probe=4748632926) | Mar 17, 2023 |
| ASRock        | Z390 Phantom Gaming 6       | [33fb26b354](https://linux-hardware.org/?probe=33fb26b354) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ceb794a09f](https://linux-hardware.org/?probe=ceb794a09f) | Mar 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | [96742a0cb2](https://linux-hardware.org/?probe=96742a0cb2) | Mar 17, 2023 |
| ASUSTek       | P9X79 WS                    | [29e03bb7ce](https://linux-hardware.org/?probe=29e03bb7ce) | Mar 17, 2023 |
| Gigabyte      | H110M-S2HP-CF               | [17d28488f3](https://linux-hardware.org/?probe=17d28488f3) | Mar 17, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | [8f1c6b4288](https://linux-hardware.org/?probe=8f1c6b4288) | Mar 17, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | [571d56ae48](https://linux-hardware.org/?probe=571d56ae48) | Mar 17, 2023 |
| HP            | 1850                        | [c805a3a08f](https://linux-hardware.org/?probe=c805a3a08f) | Mar 17, 2023 |
| Intel         | X99                         | [e7d23adc36](https://linux-hardware.org/?probe=e7d23adc36) | Mar 17, 2023 |
| HP            | 8299                        | [160716473a](https://linux-hardware.org/?probe=160716473a) | Mar 17, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [d21c2315d1](https://linux-hardware.org/?probe=d21c2315d1) | Mar 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [338ab5a12e](https://linux-hardware.org/?probe=338ab5a12e) | Mar 17, 2023 |
| ASRock        | A300M-STX                   | [133fb3bed5](https://linux-hardware.org/?probe=133fb3bed5) | Mar 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e6d8cd5424](https://linux-hardware.org/?probe=e6d8cd5424) | Mar 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [a85b96633c](https://linux-hardware.org/?probe=a85b96633c) | Mar 16, 2023 |
| MSI           | B550-A PRO                  | [730eec29f4](https://linux-hardware.org/?probe=730eec29f4) | Mar 16, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [5200e8032c](https://linux-hardware.org/?probe=5200e8032c) | Mar 15, 2023 |
| Medion        | B360H4-EM V1.0              | [839899a14d](https://linux-hardware.org/?probe=839899a14d) | Mar 15, 2023 |
| HP            | 3397                        | [5f261fa554](https://linux-hardware.org/?probe=5f261fa554) | Mar 15, 2023 |
| Dell          | 0NW6H5 A00                  | [400732bc40](https://linux-hardware.org/?probe=400732bc40) | Mar 15, 2023 |
| Dell          | 0W0CHX A01                  | [29197fc6e4](https://linux-hardware.org/?probe=29197fc6e4) | Mar 15, 2023 |
| HP            | 8299                        | [d76d2b1088](https://linux-hardware.org/?probe=d76d2b1088) | Mar 15, 2023 |
| Lenovo        | SHARKBAY NOK                | [adb5a907d1](https://linux-hardware.org/?probe=adb5a907d1) | Mar 15, 2023 |
| Acer          | TDPS05                      | [a2cdc5b3cd](https://linux-hardware.org/?probe=a2cdc5b3cd) | Mar 15, 2023 |
| Acer          | TDPS05                      | [8f528a91a5](https://linux-hardware.org/?probe=8f528a91a5) | Mar 15, 2023 |
| Gigabyte      | H310M H x.x                 | [9f440a48b9](https://linux-hardware.org/?probe=9f440a48b9) | Mar 15, 2023 |
| Dell          | 04YP6J A02                  | [183b46131c](https://linux-hardware.org/?probe=183b46131c) | Mar 15, 2023 |
| HP            | 1850                        | [c5439b2fea](https://linux-hardware.org/?probe=c5439b2fea) | Mar 15, 2023 |
| MSI           | B85-G43                     | [d8334d09fa](https://linux-hardware.org/?probe=d8334d09fa) | Mar 15, 2023 |
| MSI           | H510M-A PRO                 | [92c35e8f43](https://linux-hardware.org/?probe=92c35e8f43) | Mar 15, 2023 |
| Dell          | 0JP3NX A00                  | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| Dell          | 04YP6J A02                  | [048aa1cb05](https://linux-hardware.org/?probe=048aa1cb05) | Mar 14, 2023 |
| Pegatron      | Eureka3                     | [9a13411e08](https://linux-hardware.org/?probe=9a13411e08) | Mar 14, 2023 |
| ASRock        | 970 Pro3 R2.0               | [137a000737](https://linux-hardware.org/?probe=137a000737) | Mar 14, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [09dae67fd1](https://linux-hardware.org/?probe=09dae67fd1) | Mar 14, 2023 |
| Dell          | 0Y7WYT A00                  | [f8c17c2464](https://linux-hardware.org/?probe=f8c17c2464) | Mar 14, 2023 |
| ASRock        | Z97E-ITX/ac                 | [02c6d19dfa](https://linux-hardware.org/?probe=02c6d19dfa) | Mar 14, 2023 |
| Lenovo        | Annapurna CRB 0B98401 WI... | [c4603a155e](https://linux-hardware.org/?probe=c4603a155e) | Mar 14, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [b54b641b36](https://linux-hardware.org/?probe=b54b641b36) | Mar 14, 2023 |
| Google        | Teemo                       | [8082fe87d4](https://linux-hardware.org/?probe=8082fe87d4) | Mar 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ac3240d021](https://linux-hardware.org/?probe=ac3240d021) | Mar 14, 2023 |
| ASUSTek       | H110M-D                     | [c436834b30](https://linux-hardware.org/?probe=c436834b30) | Mar 14, 2023 |
| MSI           | A320M-A PRO                 | [b3bea1d3a0](https://linux-hardware.org/?probe=b3bea1d3a0) | Mar 14, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | [11056484c3](https://linux-hardware.org/?probe=11056484c3) | Mar 13, 2023 |
| Gigabyte      | H110M-S2HP-CF               | [e59eca90ee](https://linux-hardware.org/?probe=e59eca90ee) | Mar 13, 2023 |
| Biostar       | A320MH                      | [6fbd813bc2](https://linux-hardware.org/?probe=6fbd813bc2) | Mar 13, 2023 |
| Medion        | MS-7707                     | [14febb7194](https://linux-hardware.org/?probe=14febb7194) | Mar 13, 2023 |
| MSI           | B85-G43                     | [e270b5804a](https://linux-hardware.org/?probe=e270b5804a) | Mar 13, 2023 |
| Gigabyte      | B75M-D3H                    | [e035b82dec](https://linux-hardware.org/?probe=e035b82dec) | Mar 13, 2023 |
| HP            | 806A                        | [2203b83131](https://linux-hardware.org/?probe=2203b83131) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | [2d0688b56c](https://linux-hardware.org/?probe=2d0688b56c) | Mar 13, 2023 |
| HP            | 8433 11                     | [5ff8aa6d61](https://linux-hardware.org/?probe=5ff8aa6d61) | Mar 12, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [7933355c0d](https://linux-hardware.org/?probe=7933355c0d) | Mar 12, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [c1a757a07a](https://linux-hardware.org/?probe=c1a757a07a) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [9e9d31abe8](https://linux-hardware.org/?probe=9e9d31abe8) | Mar 12, 2023 |
| Apple         | Mac-F221BEC8                | [d57befe967](https://linux-hardware.org/?probe=d57befe967) | Mar 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [e259b3e70a](https://linux-hardware.org/?probe=e259b3e70a) | Mar 12, 2023 |
| Pegatron      | Benicia                     | [5cbae84e37](https://linux-hardware.org/?probe=5cbae84e37) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [36981b0d78](https://linux-hardware.org/?probe=36981b0d78) | Mar 12, 2023 |
| ASRock        | B460M Pro4                  | [50e790583a](https://linux-hardware.org/?probe=50e790583a) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [e3a9c91eea](https://linux-hardware.org/?probe=e3a9c91eea) | Mar 12, 2023 |
| ASRock        | X399 Taichi                 | [1ad7f4ea8e](https://linux-hardware.org/?probe=1ad7f4ea8e) | Mar 12, 2023 |
| Dell          | 0HHV7N A00                  | [75e9243247](https://linux-hardware.org/?probe=75e9243247) | Mar 12, 2023 |
| Dell          | 0F428D A00                  | [b175f76585](https://linux-hardware.org/?probe=b175f76585) | Mar 12, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [b8eedb947a](https://linux-hardware.org/?probe=b8eedb947a) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | [ec4064a64c](https://linux-hardware.org/?probe=ec4064a64c) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | [929aa1d9a8](https://linux-hardware.org/?probe=929aa1d9a8) | Mar 11, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3e9c39ec40](https://linux-hardware.org/?probe=3e9c39ec40) | Mar 11, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [916f61c8c4](https://linux-hardware.org/?probe=916f61c8c4) | Mar 11, 2023 |
| GALAX         | B550M                       | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [9366807359](https://linux-hardware.org/?probe=9366807359) | Mar 11, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [4fff7009b7](https://linux-hardware.org/?probe=4fff7009b7) | Mar 11, 2023 |
| Dell          | 02YYK5 A01                  | [615aa7769d](https://linux-hardware.org/?probe=615aa7769d) | Mar 11, 2023 |
| Lenovo        | 313A NOK                    | [eac2246a83](https://linux-hardware.org/?probe=eac2246a83) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | [6c90dd73e7](https://linux-hardware.org/?probe=6c90dd73e7) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | [c792b83b69](https://linux-hardware.org/?probe=c792b83b69) | Mar 11, 2023 |
| ASRock        | Z370 Pro4                   | [95da35c192](https://linux-hardware.org/?probe=95da35c192) | Mar 11, 2023 |
| HP            | 339A                        | [23c40110da](https://linux-hardware.org/?probe=23c40110da) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ef3ba694a9](https://linux-hardware.org/?probe=ef3ba694a9) | Mar 11, 2023 |
| ASRock        | FM2A58M-VG3+                | [2f98601c14](https://linux-hardware.org/?probe=2f98601c14) | Mar 11, 2023 |
| MSI           | Z590-A PRO                  | [c0c43b3296](https://linux-hardware.org/?probe=c0c43b3296) | Mar 11, 2023 |
| ECS2          | EASTWOOD2 V1.0              | [822e4fa621](https://linux-hardware.org/?probe=822e4fa621) | Mar 11, 2023 |
| MSI           | MS-7369                     | [7900c0d288](https://linux-hardware.org/?probe=7900c0d288) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [66f9a13087](https://linux-hardware.org/?probe=66f9a13087) | Mar 11, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [7edece131b](https://linux-hardware.org/?probe=7edece131b) | Mar 11, 2023 |
| Acer          | Aspire TC-780               | [e65980107f](https://linux-hardware.org/?probe=e65980107f) | Mar 11, 2023 |
| MSI           | Z370 SLI PLUS               | [ab6bce7264](https://linux-hardware.org/?probe=ab6bce7264) | Mar 11, 2023 |
| ASUSTek       | P5E-V HDMI                  | [0f85d5d628](https://linux-hardware.org/?probe=0f85d5d628) | Mar 11, 2023 |
| Intel         | DH55HC AAE70933-503         | [4d1f3745ac](https://linux-hardware.org/?probe=4d1f3745ac) | Mar 10, 2023 |
| Intel         | DH55HC AAE70933-503         | [46160d5ef3](https://linux-hardware.org/?probe=46160d5ef3) | Mar 10, 2023 |
| ASUSTek       | P6T WS PRO                  | [7d5df3a3d7](https://linux-hardware.org/?probe=7d5df3a3d7) | Mar 10, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d49d17f980](https://linux-hardware.org/?probe=d49d17f980) | Mar 10, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [6cce878289](https://linux-hardware.org/?probe=6cce878289) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1f7b2c8bd5](https://linux-hardware.org/?probe=1f7b2c8bd5) | Mar 10, 2023 |
| ASRock        | 970 Pro3 R2.0               | [0217eab769](https://linux-hardware.org/?probe=0217eab769) | Mar 10, 2023 |
| Foxconn       | 945 7AD Series              | [d8601ee583](https://linux-hardware.org/?probe=d8601ee583) | Mar 10, 2023 |
| MSI           | B450I GAMING PLUS AC        | [502bf5911c](https://linux-hardware.org/?probe=502bf5911c) | Mar 10, 2023 |
| Gigabyte      | H61M-S2PV                   | [76f456d63a](https://linux-hardware.org/?probe=76f456d63a) | Mar 10, 2023 |
| ASUSTek       | H170-PRO                    | [26e8e51ba6](https://linux-hardware.org/?probe=26e8e51ba6) | Mar 10, 2023 |
| ASUSTek       | P5Q-E                       | [9b675b1e49](https://linux-hardware.org/?probe=9b675b1e49) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5a1af5afcf](https://linux-hardware.org/?probe=5a1af5afcf) | Mar 10, 2023 |
| Gigabyte      | Z77X-UD3H                   | [e4fe786b7a](https://linux-hardware.org/?probe=e4fe786b7a) | Mar 10, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [0c95ceb5b2](https://linux-hardware.org/?probe=0c95ceb5b2) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [a5a874dac0](https://linux-hardware.org/?probe=a5a874dac0) | Mar 10, 2023 |
| MSI           | B550-A PRO                  | [493a2b9df6](https://linux-hardware.org/?probe=493a2b9df6) | Mar 10, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [507d61b2a9](https://linux-hardware.org/?probe=507d61b2a9) | Mar 10, 2023 |
| HP            | 2B35                        | [ddb4d051ab](https://linux-hardware.org/?probe=ddb4d051ab) | Mar 09, 2023 |
| HP            | 2B35                        | [83f9096b77](https://linux-hardware.org/?probe=83f9096b77) | Mar 09, 2023 |
| Supermicro    | X7DVL                       | [7b689d297c](https://linux-hardware.org/?probe=7b689d297c) | Mar 09, 2023 |
| HP            | 1905                        | [dc86818199](https://linux-hardware.org/?probe=dc86818199) | Mar 09, 2023 |
| MSI           | A78M-E35                    | [789fc90b18](https://linux-hardware.org/?probe=789fc90b18) | Mar 09, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [5df81d1297](https://linux-hardware.org/?probe=5df81d1297) | Mar 09, 2023 |
| Dell          | 0JP3NX A01                  | [946f48cdf6](https://linux-hardware.org/?probe=946f48cdf6) | Mar 09, 2023 |
| ASUSTek       | F2A85-V                     | [1470c9fc46](https://linux-hardware.org/?probe=1470c9fc46) | Mar 09, 2023 |
| MSI           | MS-7366                     | [97443c2383](https://linux-hardware.org/?probe=97443c2383) | Mar 09, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | [1140b33d95](https://linux-hardware.org/?probe=1140b33d95) | Mar 09, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [c81f97ee71](https://linux-hardware.org/?probe=c81f97ee71) | Mar 09, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [515a056886](https://linux-hardware.org/?probe=515a056886) | Mar 09, 2023 |
| MSI           | A75MA-P35                   | [5e428388b6](https://linux-hardware.org/?probe=5e428388b6) | Mar 09, 2023 |
| Dell          | 0GDG8Y A00                  | [407bcc53b5](https://linux-hardware.org/?probe=407bcc53b5) | Mar 09, 2023 |
| MSI           | Z68MA-ED55                  | [17a3d0c88b](https://linux-hardware.org/?probe=17a3d0c88b) | Mar 09, 2023 |
| Intel         | DH61BF AAG81311-101         | [b960fb0ebf](https://linux-hardware.org/?probe=b960fb0ebf) | Mar 08, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [7219e84299](https://linux-hardware.org/?probe=7219e84299) | Mar 08, 2023 |
| Pegatron      | 2AB5                        | [7e36ff0272](https://linux-hardware.org/?probe=7e36ff0272) | Mar 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [25b5ea3981](https://linux-hardware.org/?probe=25b5ea3981) | Mar 08, 2023 |
| Dell          | 0JP3NX A01                  | [705893644e](https://linux-hardware.org/?probe=705893644e) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [cefdfde063](https://linux-hardware.org/?probe=cefdfde063) | Mar 08, 2023 |
| Packard Be... | IMEDIA S3810                | [7bbac39491](https://linux-hardware.org/?probe=7bbac39491) | Mar 08, 2023 |
| Packard Be... | IMEDIA S3810                | [1f6f044145](https://linux-hardware.org/?probe=1f6f044145) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a84a348f29](https://linux-hardware.org/?probe=a84a348f29) | Mar 08, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [cea86809fd](https://linux-hardware.org/?probe=cea86809fd) | Mar 08, 2023 |
| Intel         | D33217GKE G76540-203        | [f18444c5dd](https://linux-hardware.org/?probe=f18444c5dd) | Mar 08, 2023 |
| Medion        | MS-7800                     | [fcd708adc0](https://linux-hardware.org/?probe=fcd708adc0) | Mar 08, 2023 |
| HP            | 8591                        | [1620787dc3](https://linux-hardware.org/?probe=1620787dc3) | Mar 08, 2023 |
| Packard Be... | FIH57                       | [676c23a829](https://linux-hardware.org/?probe=676c23a829) | Mar 08, 2023 |
| Acer          | Aspire G7713                | [ef1594178c](https://linux-hardware.org/?probe=ef1594178c) | Mar 08, 2023 |
| Gigabyte      | B85M-D3H                    | [a3a158ccf2](https://linux-hardware.org/?probe=a3a158ccf2) | Mar 08, 2023 |
| ASUSTek       | PRO H410M-C                 | [a97c12b513](https://linux-hardware.org/?probe=a97c12b513) | Mar 08, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [1162f373d9](https://linux-hardware.org/?probe=1162f373d9) | Mar 08, 2023 |
| Packard Be... | IXTREME M5850               | [60b6ba7904](https://linux-hardware.org/?probe=60b6ba7904) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [43a939870d](https://linux-hardware.org/?probe=43a939870d) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f64ba0ea72](https://linux-hardware.org/?probe=f64ba0ea72) | Mar 07, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f4dd257e1d](https://linux-hardware.org/?probe=f4dd257e1d) | Mar 07, 2023 |
| ECS           | CMLU-MINI                   | [b537e49549](https://linux-hardware.org/?probe=b537e49549) | Mar 07, 2023 |
| MSI           | X470 GAMING PRO MAX         | [eada75807b](https://linux-hardware.org/?probe=eada75807b) | Mar 07, 2023 |
| Wistron       | ProLiant ML110 G5           | [a36361538b](https://linux-hardware.org/?probe=a36361538b) | Mar 07, 2023 |
| Intel         | DG965WH AAD41692-304        | [51017515be](https://linux-hardware.org/?probe=51017515be) | Mar 07, 2023 |
| Intel         | DG965WH AAD41692-304        | [2ce36cc539](https://linux-hardware.org/?probe=2ce36cc539) | Mar 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [59cb6854e5](https://linux-hardware.org/?probe=59cb6854e5) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7e668b89fa](https://linux-hardware.org/?probe=7e668b89fa) | Mar 07, 2023 |
| ASRock        | X99 Extreme4                | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| ASUSTek       | A88XM-E                     | [b809f137cd](https://linux-hardware.org/?probe=b809f137cd) | Mar 07, 2023 |
| MSI           | B450M-A PRO MAX             | [c6119be13a](https://linux-hardware.org/?probe=c6119be13a) | Mar 07, 2023 |
| HP            | 3398                        | [024ce6b407](https://linux-hardware.org/?probe=024ce6b407) | Mar 06, 2023 |
| MSI           | A55M-E33                    | [1f48360cc9](https://linux-hardware.org/?probe=1f48360cc9) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [19c3fcae2a](https://linux-hardware.org/?probe=19c3fcae2a) | Mar 06, 2023 |
| Medion        | B360H4-EM V1.0              | [fff333f854](https://linux-hardware.org/?probe=fff333f854) | Mar 06, 2023 |
| ECS           | X58B-A                      | [e074c61884](https://linux-hardware.org/?probe=e074c61884) | Mar 06, 2023 |
| Acer          | Aspire TC-390               | [2d092d008e](https://linux-hardware.org/?probe=2d092d008e) | Mar 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [8812bcfc2b](https://linux-hardware.org/?probe=8812bcfc2b) | Mar 06, 2023 |
| Dell          | 048DY8 A00                  | [2ae03ba26f](https://linux-hardware.org/?probe=2ae03ba26f) | Mar 06, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [39187f7b13](https://linux-hardware.org/?probe=39187f7b13) | Mar 06, 2023 |
| ASUSTek       | Z97-DELUXE/USB              | [46d851b146](https://linux-hardware.org/?probe=46d851b146) | Mar 06, 2023 |
| ASUSTek       | PRIME B365M-A               | [c23b8aa247](https://linux-hardware.org/?probe=c23b8aa247) | Mar 06, 2023 |
| ASUSTek       | P5KC                        | [72d0284bdd](https://linux-hardware.org/?probe=72d0284bdd) | Mar 05, 2023 |
| Dell          | 014GRG A01                  | [2e7b556001](https://linux-hardware.org/?probe=2e7b556001) | Mar 05, 2023 |
| Gigabyte      | G41M-ES2L                   | [6f52c3fe5e](https://linux-hardware.org/?probe=6f52c3fe5e) | Mar 05, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [06bb73cbaa](https://linux-hardware.org/?probe=06bb73cbaa) | Mar 05, 2023 |
| ASRock        | G31M-S                      | [69f88597a5](https://linux-hardware.org/?probe=69f88597a5) | Mar 05, 2023 |
| Biostar       | TA780G M2+                  | [f5ddb4d21a](https://linux-hardware.org/?probe=f5ddb4d21a) | Mar 05, 2023 |
| Gigabyte      | G41M-ES2L                   | [b3fa56bc6f](https://linux-hardware.org/?probe=b3fa56bc6f) | Mar 05, 2023 |
| MSI           | A75MA-P35                   | [240feec1ab](https://linux-hardware.org/?probe=240feec1ab) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [109fa85017](https://linux-hardware.org/?probe=109fa85017) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [0d99cfc372](https://linux-hardware.org/?probe=0d99cfc372) | Mar 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [c9ad4b8ba2](https://linux-hardware.org/?probe=c9ad4b8ba2) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [65aa79b0a3](https://linux-hardware.org/?probe=65aa79b0a3) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [ab7448d0bf](https://linux-hardware.org/?probe=ab7448d0bf) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | [71ba309b29](https://linux-hardware.org/?probe=71ba309b29) | Mar 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [2d9dfed892](https://linux-hardware.org/?probe=2d9dfed892) | Mar 05, 2023 |
| Intel         | DG965WH AAD41692-304        | [cbbf38ac91](https://linux-hardware.org/?probe=cbbf38ac91) | Mar 05, 2023 |
| Gigabyte      | H510M H                     | [9eeb7d071e](https://linux-hardware.org/?probe=9eeb7d071e) | Mar 05, 2023 |
| Dell          | 00V62H A01                  | [dda13d9c8e](https://linux-hardware.org/?probe=dda13d9c8e) | Mar 05, 2023 |
| ASUSTek       | A88XM-E                     | [ea145a8349](https://linux-hardware.org/?probe=ea145a8349) | Mar 05, 2023 |
| Shuttle       | DH670                       | [29f90ad317](https://linux-hardware.org/?probe=29f90ad317) | Mar 05, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [4653cfc293](https://linux-hardware.org/?probe=4653cfc293) | Mar 05, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [6ce972aa89](https://linux-hardware.org/?probe=6ce972aa89) | Mar 05, 2023 |
| HP            | 339A                        | [ee0d9b5bb4](https://linux-hardware.org/?probe=ee0d9b5bb4) | Mar 05, 2023 |
| HP            | 339A                        | [d4e0e68816](https://linux-hardware.org/?probe=d4e0e68816) | Mar 05, 2023 |
| Intel         | DG965WH AAD41692-304        | [93717f1fd1](https://linux-hardware.org/?probe=93717f1fd1) | Mar 05, 2023 |
| Intel         | DG965WH AAD41692-304        | [1fb2473520](https://linux-hardware.org/?probe=1fb2473520) | Mar 05, 2023 |
| AZW           | U59                         | [609fdf5242](https://linux-hardware.org/?probe=609fdf5242) | Mar 05, 2023 |
| ZOTAC         | H77ITX-A-E                  | [2fdc29d4fd](https://linux-hardware.org/?probe=2fdc29d4fd) | Mar 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [cf87d901a9](https://linux-hardware.org/?probe=cf87d901a9) | Mar 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [789ca3b7bd](https://linux-hardware.org/?probe=789ca3b7bd) | Mar 05, 2023 |
| ZOTAC         | H77ITX-A-E                  | [9cbf7f2ca0](https://linux-hardware.org/?probe=9cbf7f2ca0) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [a4a7beacc6](https://linux-hardware.org/?probe=a4a7beacc6) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [bae33b90df](https://linux-hardware.org/?probe=bae33b90df) | Mar 05, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [f49b87fc79](https://linux-hardware.org/?probe=f49b87fc79) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [e9719645f3](https://linux-hardware.org/?probe=e9719645f3) | Mar 04, 2023 |
| ASUSTek       | P8P67                       | [70ee1f3c06](https://linux-hardware.org/?probe=70ee1f3c06) | Mar 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [fd33b65218](https://linux-hardware.org/?probe=fd33b65218) | Mar 04, 2023 |
| ASUSTek       | B85M-G                      | [6105f440e0](https://linux-hardware.org/?probe=6105f440e0) | Mar 04, 2023 |
| Intel         | DH55HC AAE70933-503         | [e038320969](https://linux-hardware.org/?probe=e038320969) | Mar 04, 2023 |
| ASRock        | H81M-DGS R2.0               | [396ad2d6aa](https://linux-hardware.org/?probe=396ad2d6aa) | Mar 04, 2023 |
| Gigabyte      | 970A-DS3P                   | [621391a7e0](https://linux-hardware.org/?probe=621391a7e0) | Mar 04, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [fc4e41c940](https://linux-hardware.org/?probe=fc4e41c940) | Mar 04, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [d850dacb6a](https://linux-hardware.org/?probe=d850dacb6a) | Mar 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0e106ed41e](https://linux-hardware.org/?probe=0e106ed41e) | Mar 04, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [f177ea06e6](https://linux-hardware.org/?probe=f177ea06e6) | Mar 04, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [01de5e633e](https://linux-hardware.org/?probe=01de5e633e) | Mar 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a8904b4cc0](https://linux-hardware.org/?probe=a8904b4cc0) | Mar 04, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [1c45b9b74f](https://linux-hardware.org/?probe=1c45b9b74f) | Mar 04, 2023 |
| ASUSTek       | P8H61-M PRO                 | [5861c1d198](https://linux-hardware.org/?probe=5861c1d198) | Mar 03, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [942ff998a6](https://linux-hardware.org/?probe=942ff998a6) | Mar 03, 2023 |
| Pegatron      | NARRA5                      | [8670ad8f50](https://linux-hardware.org/?probe=8670ad8f50) | Mar 03, 2023 |
| HP            | ProLiant ML110 Gen9         | [2ac4801793](https://linux-hardware.org/?probe=2ac4801793) | Mar 03, 2023 |
| ASUSTek       | PRO H410M-C                 | [b0076c9250](https://linux-hardware.org/?probe=b0076c9250) | Mar 03, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | [6396907447](https://linux-hardware.org/?probe=6396907447) | Mar 03, 2023 |
| Acer          | Aspire G7713                | [179b18e8a7](https://linux-hardware.org/?probe=179b18e8a7) | Mar 03, 2023 |
| Dell          | 0T10XW A02                  | [2470e02bf6](https://linux-hardware.org/?probe=2470e02bf6) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | [80720d46a2](https://linux-hardware.org/?probe=80720d46a2) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | [dd01af3afe](https://linux-hardware.org/?probe=dd01af3afe) | Mar 03, 2023 |
| Gigabyte      | Z370M D3H-CF                | [e51c87218a](https://linux-hardware.org/?probe=e51c87218a) | Mar 03, 2023 |
| HP            | 806A                        | [66c29ddd8a](https://linux-hardware.org/?probe=66c29ddd8a) | Mar 03, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [ae8815c871](https://linux-hardware.org/?probe=ae8815c871) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | [9a9f442174](https://linux-hardware.org/?probe=9a9f442174) | Mar 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [5033b7233d](https://linux-hardware.org/?probe=5033b7233d) | Mar 03, 2023 |
| Gateway       | SX2380                      | [fc26630b37](https://linux-hardware.org/?probe=fc26630b37) | Mar 03, 2023 |
| Supermicro    | X7DVL                       | [aaa4d53ae2](https://linux-hardware.org/?probe=aaa4d53ae2) | Mar 03, 2023 |
| Dell          | 0T10XW A02                  | [9c09cef0dc](https://linux-hardware.org/?probe=9c09cef0dc) | Mar 03, 2023 |
| ASRock        | Z170 Extreme4               | [428377b153](https://linux-hardware.org/?probe=428377b153) | Mar 03, 2023 |
| HP            | 3398                        | [6479dbaa0e](https://linux-hardware.org/?probe=6479dbaa0e) | Mar 02, 2023 |
| ASRock        | B365 Pro4                   | [16875fc443](https://linux-hardware.org/?probe=16875fc443) | Mar 02, 2023 |
| SZMZ          | X99M-G2                     | [e2244668d1](https://linux-hardware.org/?probe=e2244668d1) | Mar 02, 2023 |
| HP            | 1497                        | [c74b2b540e](https://linux-hardware.org/?probe=c74b2b540e) | Mar 02, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [f0343cd266](https://linux-hardware.org/?probe=f0343cd266) | Mar 02, 2023 |
| ASRock        | Z170 Gaming K4              | [96fb41423a](https://linux-hardware.org/?probe=96fb41423a) | Mar 02, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | [ab9ad1a310](https://linux-hardware.org/?probe=ab9ad1a310) | Mar 02, 2023 |
| Gigabyte      | H81M-S1                     | [0a38248462](https://linux-hardware.org/?probe=0a38248462) | Mar 02, 2023 |
| ASUSTek       | B85M-E                      | [e821b0d96a](https://linux-hardware.org/?probe=e821b0d96a) | Mar 02, 2023 |
| Medion        | Cattle24 1M                 | [639a660b02](https://linux-hardware.org/?probe=639a660b02) | Mar 02, 2023 |
| HP            | 1998                        | [269c6134f1](https://linux-hardware.org/?probe=269c6134f1) | Mar 01, 2023 |
| Fujitsu       | D3502-A1 S26361-D3502-A1    | [0cfb2983cb](https://linux-hardware.org/?probe=0cfb2983cb) | Mar 01, 2023 |
| SZMZ          | X99M-G2                     | [4e45d95aa1](https://linux-hardware.org/?probe=4e45d95aa1) | Mar 01, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [10f864cbb0](https://linux-hardware.org/?probe=10f864cbb0) | Mar 01, 2023 |
| Dell          | 0CU409                      | [706fbfb004](https://linux-hardware.org/?probe=706fbfb004) | Mar 01, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [784ef5ef12](https://linux-hardware.org/?probe=784ef5ef12) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [84a1a2c71e](https://linux-hardware.org/?probe=84a1a2c71e) | Mar 01, 2023 |
| ASRock        | X370 Pro4                   | [cd39348090](https://linux-hardware.org/?probe=cd39348090) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [44e24e77eb](https://linux-hardware.org/?probe=44e24e77eb) | Mar 01, 2023 |
| Biostar       | B450MH                      | [aa05ee87d1](https://linux-hardware.org/?probe=aa05ee87d1) | Mar 01, 2023 |
| Gigabyte      | Z390 UD                     | [006fbf48e9](https://linux-hardware.org/?probe=006fbf48e9) | Mar 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [7f3d018e9c](https://linux-hardware.org/?probe=7f3d018e9c) | Mar 01, 2023 |
| HP            | 8299                        | [7287268c92](https://linux-hardware.org/?probe=7287268c92) | Mar 01, 2023 |
| ASUSTek       | Z170-A                      | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [48e150f274](https://linux-hardware.org/?probe=48e150f274) | Feb 28, 2023 |
| ASRockRack    | E3C246D4U2-2T               | [1ad2cb5102](https://linux-hardware.org/?probe=1ad2cb5102) | Feb 28, 2023 |
| ASRock        | KBL-NUC                     | [cb504c5fa0](https://linux-hardware.org/?probe=cb504c5fa0) | Feb 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [64b2c8d5b9](https://linux-hardware.org/?probe=64b2c8d5b9) | Feb 28, 2023 |
| ASUSTek       | PRIME X570-P                | [dda5eec4b9](https://linux-hardware.org/?probe=dda5eec4b9) | Feb 28, 2023 |
| Lenovo        | 3102 NOK                    | [17a2e663e1](https://linux-hardware.org/?probe=17a2e663e1) | Feb 28, 2023 |
| Lenovo        | 3102 NOK                    | [6dabaffa28](https://linux-hardware.org/?probe=6dabaffa28) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [aefca0b663](https://linux-hardware.org/?probe=aefca0b663) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [12ccf2fe8b](https://linux-hardware.org/?probe=12ccf2fe8b) | Feb 28, 2023 |
| Dell          | 0HD5W2 A01                  | [f30a31a8ee](https://linux-hardware.org/?probe=f30a31a8ee) | Feb 28, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [cb687f4572](https://linux-hardware.org/?probe=cb687f4572) | Feb 28, 2023 |
| Acer          | TDPS05                      | [c4a636fb79](https://linux-hardware.org/?probe=c4a636fb79) | Feb 28, 2023 |
| Acer          | TDPS05                      | [114e21597f](https://linux-hardware.org/?probe=114e21597f) | Feb 28, 2023 |
| ASUSTek       | PRIME B360M-A               | [5860f51cd8](https://linux-hardware.org/?probe=5860f51cd8) | Feb 27, 2023 |
| Gigabyte      | EX58-UD5                    | [eaec9511de](https://linux-hardware.org/?probe=eaec9511de) | Feb 27, 2023 |
| HP            | 339A                        | [308d8dfac0](https://linux-hardware.org/?probe=308d8dfac0) | Feb 27, 2023 |
| Casper        | H510 001 G10a               | [95a9cfbf0b](https://linux-hardware.org/?probe=95a9cfbf0b) | Feb 27, 2023 |
| Gigabyte      | A320M-H-CF                  | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| Gigabyte      | H110M-S2V-CF                | [509c2a6e57](https://linux-hardware.org/?probe=509c2a6e57) | Feb 27, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | [686c8d56c4](https://linux-hardware.org/?probe=686c8d56c4) | Feb 27, 2023 |
| ASRock        | A320M-HDV R4.0              | [37d2aab670](https://linux-hardware.org/?probe=37d2aab670) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [49f3238d4a](https://linux-hardware.org/?probe=49f3238d4a) | Feb 26, 2023 |
| HP            | 81B4 01                     | [bc06df8d32](https://linux-hardware.org/?probe=bc06df8d32) | Feb 26, 2023 |
| Gigabyte      | Z390 UD                     | [b40f9ce0d1](https://linux-hardware.org/?probe=b40f9ce0d1) | Feb 26, 2023 |
| MSI           | B450M PRO-M2 MAX            | [0c5f9a10dd](https://linux-hardware.org/?probe=0c5f9a10dd) | Feb 26, 2023 |
| Pegatron      | NARRA5                      | [fbff48e326](https://linux-hardware.org/?probe=fbff48e326) | Feb 26, 2023 |
| Lenovo        | Annapurna CRB NOK           | [77122f785f](https://linux-hardware.org/?probe=77122f785f) | Feb 26, 2023 |
| Lenovo        | Annapurna CRB NOK           | [0e521e12aa](https://linux-hardware.org/?probe=0e521e12aa) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | [4cd492ee3e](https://linux-hardware.org/?probe=4cd492ee3e) | Feb 26, 2023 |
| ASRock        | B85 Pro4                    | [0b4daba4fb](https://linux-hardware.org/?probe=0b4daba4fb) | Feb 26, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [49b1cd5754](https://linux-hardware.org/?probe=49b1cd5754) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | [9471b0f763](https://linux-hardware.org/?probe=9471b0f763) | Feb 26, 2023 |
| Gigabyte      | B560M DS3H V2               | [31f6d9e11d](https://linux-hardware.org/?probe=31f6d9e11d) | Feb 26, 2023 |
| Dell          | 0WMJ54 A01                  | [f9cae700c7](https://linux-hardware.org/?probe=f9cae700c7) | Feb 26, 2023 |
| HP            | 1632                        | [394b988862](https://linux-hardware.org/?probe=394b988862) | Feb 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [f24a3027d0](https://linux-hardware.org/?probe=f24a3027d0) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Dell          | 0HR330                      | [9110acd156](https://linux-hardware.org/?probe=9110acd156) | Feb 26, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | [f56bb767fd](https://linux-hardware.org/?probe=f56bb767fd) | Feb 26, 2023 |
| ASUSTek       | H87-PLUS                    | [98e70b4028](https://linux-hardware.org/?probe=98e70b4028) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| Dell          | 0F428D A00                  | [7d01f8893e](https://linux-hardware.org/?probe=7d01f8893e) | Feb 25, 2023 |
| ASRock        | Z97 Pro4                    | [451c626830](https://linux-hardware.org/?probe=451c626830) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [336a7cad31](https://linux-hardware.org/?probe=336a7cad31) | Feb 25, 2023 |
| eMachines     | EL1850                      | [81741a438a](https://linux-hardware.org/?probe=81741a438a) | Feb 25, 2023 |
| HP            | 3398                        | [5e7ae4c866](https://linux-hardware.org/?probe=5e7ae4c866) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [0620aa7f6f](https://linux-hardware.org/?probe=0620aa7f6f) | Feb 25, 2023 |
| Gigabyte      | B550M DS3H                  | [0ac3b49261](https://linux-hardware.org/?probe=0ac3b49261) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [30afdb56c5](https://linux-hardware.org/?probe=30afdb56c5) | Feb 25, 2023 |
| Protectli     | VP2420                      | [ea5f851cf3](https://linux-hardware.org/?probe=ea5f851cf3) | Feb 25, 2023 |
| Quanta        | 2AC7 011                    | [3505fadb68](https://linux-hardware.org/?probe=3505fadb68) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfa5623f15](https://linux-hardware.org/?probe=bfa5623f15) | Feb 25, 2023 |
| Acer          | Aspire X3990                | [c83e31d66b](https://linux-hardware.org/?probe=c83e31d66b) | Feb 25, 2023 |
| Acer          | Aspire X3990                | [4be9f68049](https://linux-hardware.org/?probe=4be9f68049) | Feb 25, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [7864921f8d](https://linux-hardware.org/?probe=7864921f8d) | Feb 25, 2023 |
| Dell          | 051FJ8 A02                  | [05f5f23fbb](https://linux-hardware.org/?probe=05f5f23fbb) | Feb 25, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [d78e737aaf](https://linux-hardware.org/?probe=d78e737aaf) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [df734c276f](https://linux-hardware.org/?probe=df734c276f) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [3f931a7600](https://linux-hardware.org/?probe=3f931a7600) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | [99b5c2f7f9](https://linux-hardware.org/?probe=99b5c2f7f9) | Feb 24, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | [0bb7bc3713](https://linux-hardware.org/?probe=0bb7bc3713) | Feb 24, 2023 |
| ASUSTek       | PRIME B360M-A               | [6d7221488b](https://linux-hardware.org/?probe=6d7221488b) | Feb 24, 2023 |
| Pegatron      | NARRA5                      | [af6be34173](https://linux-hardware.org/?probe=af6be34173) | Feb 24, 2023 |
| MSI           | K9N6PGM2-V2                 | [e88df81d6f](https://linux-hardware.org/?probe=e88df81d6f) | Feb 24, 2023 |
| HP            | 8433 11                     | [e8663b2a0c](https://linux-hardware.org/?probe=e8663b2a0c) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | [f4e2bfd7a0](https://linux-hardware.org/?probe=f4e2bfd7a0) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [916f372721](https://linux-hardware.org/?probe=916f372721) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [6e82a5c5d6](https://linux-hardware.org/?probe=6e82a5c5d6) | Feb 24, 2023 |
| ASRock        | B550M-C                     | [96edee86aa](https://linux-hardware.org/?probe=96edee86aa) | Feb 24, 2023 |
| ASRock        | B550M-C                     | [454c89b4eb](https://linux-hardware.org/?probe=454c89b4eb) | Feb 24, 2023 |
| Pegatron      | NARRA5                      | [ca884f817b](https://linux-hardware.org/?probe=ca884f817b) | Feb 24, 2023 |
| ASUSTek       | Q87M-E                      | [e31da94f7b](https://linux-hardware.org/?probe=e31da94f7b) | Feb 24, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [a458effa12](https://linux-hardware.org/?probe=a458effa12) | Feb 24, 2023 |
| ASUSTek       | PRIME B460M-A R2.0          | [0ccac8edb4](https://linux-hardware.org/?probe=0ccac8edb4) | Feb 24, 2023 |
| ASRock        | H510M/ac                    | [b7d570e46c](https://linux-hardware.org/?probe=b7d570e46c) | Feb 24, 2023 |
| Dell          | 0M5DCD A00                  | [88b0bf49fd](https://linux-hardware.org/?probe=88b0bf49fd) | Feb 24, 2023 |
| Dell          | 0MWYPT A02                  | [2491b0e5eb](https://linux-hardware.org/?probe=2491b0e5eb) | Feb 23, 2023 |
| HP            | 8433 11                     | [9aa13c1fa5](https://linux-hardware.org/?probe=9aa13c1fa5) | Feb 23, 2023 |
| Gigabyte      | Z390 UD                     | [5a6ab06c02](https://linux-hardware.org/?probe=5a6ab06c02) | Feb 23, 2023 |
| ASUSTek       | P5K                         | [2fb7f1713b](https://linux-hardware.org/?probe=2fb7f1713b) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6bdb8ada9c](https://linux-hardware.org/?probe=6bdb8ada9c) | Feb 23, 2023 |
| ASUSTek       | Maximus VI HERO             | [16618052ef](https://linux-hardware.org/?probe=16618052ef) | Feb 23, 2023 |
| ASUSTek       | B85M-E                      | [8a09d5e812](https://linux-hardware.org/?probe=8a09d5e812) | Feb 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [00e573a880](https://linux-hardware.org/?probe=00e573a880) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| Dell          | 0WG855                      | [49c149cff7](https://linux-hardware.org/?probe=49c149cff7) | Feb 23, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [7b27b03f4a](https://linux-hardware.org/?probe=7b27b03f4a) | Feb 23, 2023 |
| T-bao         | MINI PC                     | [68ba9fc610](https://linux-hardware.org/?probe=68ba9fc610) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [e0687d11bb](https://linux-hardware.org/?probe=e0687d11bb) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [49e71eb5b4](https://linux-hardware.org/?probe=49e71eb5b4) | Feb 22, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ce8874cff4](https://linux-hardware.org/?probe=ce8874cff4) | Feb 22, 2023 |
| MSI           | B350 TOMAHAWK               | [71aa647a28](https://linux-hardware.org/?probe=71aa647a28) | Feb 22, 2023 |
| ASRock        | B450 Pro4                   | [87600137b2](https://linux-hardware.org/?probe=87600137b2) | Feb 22, 2023 |
| ASUSTek       | PRO H410M-C                 | [d6edc5401d](https://linux-hardware.org/?probe=d6edc5401d) | Feb 22, 2023 |
| MSI           | B550-A PRO                  | [11d4db7a00](https://linux-hardware.org/?probe=11d4db7a00) | Feb 22, 2023 |
| ASUSTek       | Maximus VI HERO             | [754e37e18d](https://linux-hardware.org/?probe=754e37e18d) | Feb 22, 2023 |
| Unknown       | 1.0                         | [b7475435a7](https://linux-hardware.org/?probe=b7475435a7) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | [3362226081](https://linux-hardware.org/?probe=3362226081) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | [8230de4836](https://linux-hardware.org/?probe=8230de4836) | Feb 22, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [adc8d2fb16](https://linux-hardware.org/?probe=adc8d2fb16) | Feb 22, 2023 |
| MSI           | MEG X570 UNIFY              | [edc30b8a22](https://linux-hardware.org/?probe=edc30b8a22) | Feb 22, 2023 |
| Acer          | Aspire TC-605               | [7234bd12f6](https://linux-hardware.org/?probe=7234bd12f6) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| Gigabyte      | EP43-UD3L                   | [52c293dde6](https://linux-hardware.org/?probe=52c293dde6) | Feb 21, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6b883f967d](https://linux-hardware.org/?probe=6b883f967d) | Feb 21, 2023 |
| Gigabyte      | B365M DS3H                  | [8049beda96](https://linux-hardware.org/?probe=8049beda96) | Feb 21, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [d9a5611225](https://linux-hardware.org/?probe=d9a5611225) | Feb 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [50261acb6b](https://linux-hardware.org/?probe=50261acb6b) | Feb 21, 2023 |
| Dell          | 0HY9JP A01                  | [8c1473e111](https://linux-hardware.org/?probe=8c1473e111) | Feb 21, 2023 |
| MSI           | B550 GAMING GEN3            | [d92a4239ee](https://linux-hardware.org/?probe=d92a4239ee) | Feb 21, 2023 |
| HP            | 18E7                        | [913411cd18](https://linux-hardware.org/?probe=913411cd18) | Feb 21, 2023 |
| Acer          | Aspire X1935                | [8c4f88db47](https://linux-hardware.org/?probe=8c4f88db47) | Feb 21, 2023 |
| Dell          | 0CK520 A01                  | [6e92aa0096](https://linux-hardware.org/?probe=6e92aa0096) | Feb 20, 2023 |
| ASUSTek       | H170-PRO                    | [011dc701c1](https://linux-hardware.org/?probe=011dc701c1) | Feb 20, 2023 |
| Alienware     | 07W25T A01                  | [0ce3af1e23](https://linux-hardware.org/?probe=0ce3af1e23) | Feb 20, 2023 |
| Alienware     | 07W25T A01                  | [f965f4658b](https://linux-hardware.org/?probe=f965f4658b) | Feb 20, 2023 |
| Dell          | 0H4VK7 A01                  | [19ded2f15b](https://linux-hardware.org/?probe=19ded2f15b) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | [796ba78b54](https://linux-hardware.org/?probe=796ba78b54) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [04130aaf41](https://linux-hardware.org/?probe=04130aaf41) | Feb 20, 2023 |
| Supermicro    | X10DRiB                     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| ASRock        | H61M-DGS R2.0               | [3d8b32f453](https://linux-hardware.org/?probe=3d8b32f453) | Feb 20, 2023 |
| AZW           | GK mini                     | [6fc9af1346](https://linux-hardware.org/?probe=6fc9af1346) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a47920e014](https://linux-hardware.org/?probe=a47920e014) | Feb 20, 2023 |
| Dell          | 0WMJ54 A01                  | [59ce46dfe2](https://linux-hardware.org/?probe=59ce46dfe2) | Feb 20, 2023 |
| Pegatron      | NARRA5                      | [6d0714a928](https://linux-hardware.org/?probe=6d0714a928) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| HP            | 18E7                        | [c59f4fb1ab](https://linux-hardware.org/?probe=c59f4fb1ab) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| ASRock        | H81M-HDS R2.0               | [32b47345a6](https://linux-hardware.org/?probe=32b47345a6) | Feb 20, 2023 |
| Dell          | 0D24M8 A02                  | [a9e9dae786](https://linux-hardware.org/?probe=a9e9dae786) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8ab5bffea6](https://linux-hardware.org/?probe=8ab5bffea6) | Feb 19, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-56-generic      | 289      | 8.48%   |
| 5.15.0-52-generic      | 250      | 7.33%   |
| 5.15.0-58-generic      | 240      | 7.04%   |
| 5.19.0-35-generic      | 207      | 6.07%   |
| 5.15.0-48-generic      | 201      | 5.89%   |
| 5.15.0-47-generic      | 196      | 5.75%   |
| 5.15.0-43-generic      | 185      | 5.43%   |
| 5.15.0-53-generic      | 150      | 4.4%    |
| 5.19.0-32-generic      | 145      | 4.25%   |
| 5.19.0-38-generic      | 139      | 4.08%   |
| 5.15.0-46-generic      | 137      | 4.02%   |
| 5.15.0-25-generic      | 103      | 3.02%   |
| 5.15.0-27-generic      | 102      | 2.99%   |
| 5.15.0-60-generic      | 93       | 2.73%   |
| 5.15.0-41-generic      | 93       | 2.73%   |
| 5.15.0-40-generic      | 91       | 2.67%   |
| 5.15.0-57-generic      | 82       | 2.4%    |
| 5.15.0-50-generic      | 79       | 2.32%   |
| 5.19.0-40-generic      | 63       | 1.85%   |
| 5.15.0-67-generic      | 63       | 1.85%   |
| 5.15.0-33-generic      | 60       | 1.76%   |
| 5.15.0-30-generic      | 53       | 1.55%   |
| 5.15.0-39-generic      | 46       | 1.35%   |
| 5.15.0-35-generic      | 44       | 1.29%   |
| 5.15.0-37-generic      | 41       | 1.2%    |
| 5.15.0-69-generic      | 39       | 1.14%   |
| 5.19.0-41-generic      | 33       | 0.97%   |
| 5.15.0-23-generic      | 12       | 0.35%   |
| 5.15.0-70-generic      | 11       | 0.32%   |
| 5.15.0-18-generic      | 9        | 0.26%   |
| 5.15.0-32-generic      | 7        | 0.21%   |
| 5.13.0-19-generic      | 7        | 0.21%   |
| 5.17.0-1020-oem        | 6        | 0.18%   |
| 5.18.0-051800-generic  | 4        | 0.12%   |
| 5.15.0-71-generic      | 4        | 0.12%   |
| 5.15.0-54-generic      | 4        | 0.12%   |
| 5.15.0-28-generic      | 4        | 0.12%   |
| 5.18.10-051810-generic | 3        | 0.09%   |
| 5.15.0-45-generic      | 3        | 0.09%   |
| 5.15.0-22-generic      | 3        | 0.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2451     | 78.66%  |
| 5.19.0  | 571      | 18.32%  |
| 5.17.0  | 19       | 0.61%   |
| 5.13.0  | 14       | 0.45%   |
| 5.18.0  | 5        | 0.16%   |
| 6.0.0   | 4        | 0.13%   |
| 6.1.0   | 3        | 0.1%    |
| 5.18.10 | 3        | 0.1%    |
| 6.2.11  | 2        | 0.06%   |
| 6.1.11  | 2        | 0.06%   |
| 6.0.9   | 2        | 0.06%   |
| 6.0.1   | 2        | 0.06%   |
| 5.8.0   | 2        | 0.06%   |
| 5.19.5  | 2        | 0.06%   |
| 5.19.17 | 2        | 0.06%   |
| 5.17.9  | 2        | 0.06%   |
| 5.17.15 | 2        | 0.06%   |
| 5.15.13 | 2        | 0.06%   |
| 6.2.9   | 1        | 0.03%   |
| 6.2.3   | 1        | 0.03%   |
| 6.2.1   | 1        | 0.03%   |
| 6.2.0   | 1        | 0.03%   |
| 6.1.8   | 1        | 0.03%   |
| 6.1.6   | 1        | 0.03%   |
| 6.1.4   | 1        | 0.03%   |
| 6.1.10  | 1        | 0.03%   |
| 6.0.8   | 1        | 0.03%   |
| 5.4.0   | 1        | 0.03%   |
| 5.19.3  | 1        | 0.03%   |
| 5.18.8  | 1        | 0.03%   |
| 5.18.3  | 1        | 0.03%   |
| 5.18.19 | 1        | 0.03%   |
| 5.18.13 | 1        | 0.03%   |
| 5.18.1  | 1        | 0.03%   |
| 5.17.7  | 1        | 0.03%   |
| 5.17.5  | 1        | 0.03%   |
| 5.17.4  | 1        | 0.03%   |
| 5.17.2  | 1        | 0.03%   |
| 5.17.14 | 1        | 0.03%   |
| 5.17.1  | 1        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2453     | 78.75%  |
| 5.19    | 576      | 18.49%  |
| 5.17    | 28       | 0.9%    |
| 5.13    | 14       | 0.45%   |
| 5.18    | 13       | 0.42%   |
| 6.1     | 9        | 0.29%   |
| 6.0     | 9        | 0.29%   |
| 6.2     | 6        | 0.19%   |
| 5.8     | 2        | 0.06%   |
| 5.4     | 1        | 0.03%   |
| 5.16    | 1        | 0.03%   |
| 5.14    | 1        | 0.03%   |
| 5.11    | 1        | 0.03%   |
| 5.10    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3037     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 2764     | 90.95%  |
| Unknown         | 153      | 5.03%   |
| GNUstep         | 66       | 2.17%   |
| X-Cinnamon      | 31       | 1.02%   |
| GNOME Flashback | 10       | 0.33%   |
| GNOME Classic   | 7        | 0.23%   |
| i3              | 4        | 0.13%   |
| ubuntu=GNOME    | 1        | 0.03%   |
| ubuntu          | 1        | 0.03%   |
| i3-with-shmlog  | 1        | 0.03%   |
| awesome         | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1638     | 52.89%  |
| X11     | 1213     | 39.17%  |
| Tty     | 180      | 5.81%   |
| Unknown | 65       | 2.1%    |
| Web     | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 2639     | 86.7%   |
| Unknown | 270      | 8.87%   |
| LightDM | 106      | 3.48%   |
| GDM     | 14       | 0.46%   |
| SDDM    | 11       | 0.36%   |
| SLiM    | 3        | 0.1%    |
| LXDM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1334     | 43.81%  |
| de_DE   | 309      | 10.15%  |
| fr_FR   | 189      | 6.21%   |
| en_GB   | 150      | 4.93%   |
| pt_BR   | 120      | 3.94%   |
| it_IT   | 105      | 3.45%   |
| en_CA   | 85       | 2.79%   |
| ru_RU   | 82       | 2.69%   |
| es_ES   | 68       | 2.23%   |
| en_AU   | 52       | 1.71%   |
| en_IN   | 44       | 1.44%   |
| pl_PL   | 42       | 1.38%   |
| nl_NL   | 33       | 1.08%   |
| C       | 32       | 1.05%   |
| cs_CZ   | 30       | 0.99%   |
| Unknown | 26       | 0.85%   |
| ja_JP   | 24       | 0.79%   |
| de_AT   | 23       | 0.76%   |
| sv_SE   | 20       | 0.66%   |
| es_AR   | 19       | 0.62%   |
| es_MX   | 18       | 0.59%   |
| zh_CN   | 16       | 0.53%   |
| en_ZA   | 16       | 0.53%   |
| fi_FI   | 15       | 0.49%   |
| pt_PT   | 12       | 0.39%   |
| hu_HU   | 12       | 0.39%   |
| fr_BE   | 11       | 0.36%   |
| el_GR   | 11       | 0.36%   |
| nl_BE   | 10       | 0.33%   |
| en_PH   | 10       | 0.33%   |
| de_CH   | 10       | 0.33%   |
| tr_TR   | 9        | 0.3%    |
| en_NZ   | 9        | 0.3%    |
| ko_KR   | 8        | 0.26%   |
| fr_CA   | 7        | 0.23%   |
| sk_SK   | 5        | 0.16%   |
| es_CO   | 5        | 0.16%   |
| zh_TW   | 4        | 0.13%   |
| nb_NO   | 4        | 0.13%   |
| es_VE   | 4        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2131     | 69.48%  |
| EFI  | 936      | 30.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 2758     | 90.22%  |
| Overlay       | 87       | 2.85%   |
| Zfs           | 74       | 2.42%   |
| Tmpfs         | 66       | 2.16%   |
| Btrfs         | 36       | 1.18%   |
| Xfs           | 22       | 0.72%   |
| Ext2          | 6        | 0.2%    |
| Unknown       | 4        | 0.13%   |
| XXXX          | 1        | 0.03%   |
| Jfs           | 1        | 0.03%   |
| Fuse.snapfuse | 1        | 0.03%   |
| Ext3          | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1954     | 62.05%  |
| Unknown | 882      | 28.01%  |
| MBR     | 313      | 9.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2529     | 82.32%  |
| Yes       | 543      | 17.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1752     | 57.18%  |
| Yes       | 1312     | 42.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 786      | 25.88%  |
| Gigabyte Technology | 450      | 14.82%  |
| MSI                 | 383      | 12.61%  |
| Dell                | 311      | 10.24%  |
| ASRock              | 233      | 7.67%   |
| Hewlett-Packard     | 230      | 7.57%   |
| Lenovo              | 121      | 3.98%   |
| Intel               | 83       | 2.73%   |
| Acer                | 64       | 2.11%   |
| Fujitsu             | 53       | 1.75%   |
| Unknown             | 34       | 1.12%   |
| Medion              | 28       | 0.92%   |
| Pegatron            | 27       | 0.89%   |
| Foxconn             | 25       | 0.82%   |
| Biostar             | 18       | 0.59%   |
| Apple               | 17       | 0.56%   |
| Shuttle             | 16       | 0.53%   |
| ECS                 | 16       | 0.53%   |
| Alienware           | 12       | 0.4%    |
| Supermicro          | 11       | 0.36%   |
| Huanan              | 10       | 0.33%   |
| Packard Bell        | 8        | 0.26%   |
| BESSTAR Tech        | 7        | 0.23%   |
| Positivo            | 6        | 0.2%    |
| Gateway             | 6        | 0.2%    |
| AZW                 | 6        | 0.2%    |
| ASRockRack          | 5        | 0.16%   |
| OEM                 | 4        | 0.13%   |
| eMachines           | 4        | 0.13%   |
| Wistron             | 3        | 0.1%    |
| Google              | 3        | 0.1%    |
| AMI                 | 3        | 0.1%    |
| YANYU               | 2        | 0.07%   |
| Protectli           | 2        | 0.07%   |
| NCR                 | 2        | 0.07%   |
| MiTAC               | 2        | 0.07%   |
| Maxtang             | 2        | 0.07%   |
| MACHINIST           | 2        | 0.07%   |
| LattePanda          | 2        | 0.07%   |
| Fujitsu Siemens     | 2        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 82       | 2.7%    |
| Unknown                         | 39       | 1.28%   |
| Dell OptiPlex 7010              | 27       | 0.89%   |
| ASUS PRIME A320M-K              | 22       | 0.72%   |
| ASUS TUF Gaming X570-PLUS       | 21       | 0.69%   |
| MSI MS-7721                     | 18       | 0.59%   |
| Dell OptiPlex 9020              | 18       | 0.59%   |
| ASUS PRIME Z590-P               | 18       | 0.59%   |
| MSI MS-7C37                     | 17       | 0.56%   |
| Dell OptiPlex 3020              | 16       | 0.53%   |
| ASUS PRIME X570-PRO             | 14       | 0.46%   |
| Dell OptiPlex 790               | 13       | 0.43%   |
| ASUS ROG STRIX B550-F GAMING    | 13       | 0.43%   |
| ASUS PRIME B550M-A              | 13       | 0.43%   |
| MSI MS-7C91                     | 12       | 0.4%    |
| HP Compaq 8200 Elite SFF PC     | 12       | 0.4%    |
| MSI MS-7C52                     | 11       | 0.36%   |
| ASRock B450M Pro4               | 11       | 0.36%   |
| Gigabyte B450M DS3H             | 10       | 0.33%   |
| Dell OptiPlex 7050              | 10       | 0.33%   |
| Dell OptiPlex 3050              | 10       | 0.33%   |
| MSI MS-7C02                     | 9        | 0.3%    |
| MSI MS-7B79                     | 9        | 0.3%    |
| Intel H61                       | 9        | 0.3%    |
| HP ProDesk 600 G1 SFF           | 9        | 0.3%    |
| ASUS M5A78L-M/USB3              | 9        | 0.3%    |
| MSI MS-7C56                     | 8        | 0.26%   |
| MSI MS-7B86                     | 8        | 0.26%   |
| MSI MS-7817                     | 8        | 0.26%   |
| MSI MS-7693                     | 8        | 0.26%   |
| Dell OptiPlex 9010              | 8        | 0.26%   |
| Dell OptiPlex 780               | 8        | 0.26%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI | 8        | 0.26%   |
| ASRock A320M-HDV R4.0           | 8        | 0.26%   |
| Apple MacPro5,1                 | 8        | 0.26%   |
| HP Z440 Workstation             | 7        | 0.23%   |
| HP EliteDesk 800 G1 SFF         | 7        | 0.23%   |
| HP Compaq Pro 6300 SFF          | 7        | 0.23%   |
| Gigabyte B75M-D3H               | 7        | 0.23%   |
| Gigabyte A320M-S2H              | 7        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 190      | 6.26%   |
| ASUS PRIME          | 182      | 5.99%   |
| ASUS ROG            | 89       | 2.93%   |
| ASUS All            | 82       | 2.7%    |
| ASUS TUF            | 80       | 2.63%   |
| HP Compaq           | 75       | 2.47%   |
| Lenovo ThinkCentre  | 63       | 2.07%   |
| Dell Precision      | 50       | 1.65%   |
| Acer Aspire         | 42       | 1.38%   |
| Unknown             | 39       | 1.28%   |
| HP EliteDesk        | 36       | 1.19%   |
| Dell Inspiron       | 29       | 0.95%   |
| Fujitsu ESPRIMO     | 28       | 0.92%   |
| HP ProDesk          | 27       | 0.89%   |
| Lenovo ThinkStation | 21       | 0.69%   |
| Gigabyte X570       | 20       | 0.66%   |
| Gigabyte B450M      | 19       | 0.63%   |
| Fujitsu CELSIUS     | 19       | 0.63%   |
| ASUS M5A78L-M       | 19       | 0.63%   |
| MSI MS-7721         | 18       | 0.59%   |
| MSI MS-7C37         | 17       | 0.56%   |
| ASUS M5A97          | 17       | 0.56%   |
| ASRock B450M        | 17       | 0.56%   |
| Lenovo IdeaCentre   | 16       | 0.53%   |
| Gigabyte Z390       | 15       | 0.49%   |
| Dell XPS            | 15       | 0.49%   |
| ASUS Pro            | 14       | 0.46%   |
| Gigabyte B450       | 13       | 0.43%   |
| ASUS P8H61-M        | 13       | 0.43%   |
| MSI MS-7C91         | 12       | 0.4%    |
| Gigabyte B550M      | 12       | 0.4%    |
| Gigabyte B550       | 12       | 0.4%    |
| Dell Vostro         | 12       | 0.4%    |
| ASUS CROSSHAIR      | 12       | 0.4%    |
| MSI MS-7C52         | 11       | 0.36%   |
| HP ProLiant         | 10       | 0.33%   |
| HP Pavilion         | 10       | 0.33%   |
| Acer Veriton        | 10       | 0.33%   |
| MSI MS-7C02         | 9        | 0.3%    |
| MSI MS-7B79         | 9        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 279      | 9.19%   |
| 2013    | 266      | 8.76%   |
| 2012    | 263      | 8.66%   |
| 2021    | 241      | 7.94%   |
| 2019    | 240      | 7.9%    |
| 2020    | 238      | 7.84%   |
| 2011    | 221      | 7.28%   |
| 2014    | 215      | 7.08%   |
| 2017    | 195      | 6.42%   |
| 2015    | 173      | 5.7%    |
| 2010    | 152      | 5%      |
| 2009    | 128      | 4.21%   |
| 2022    | 126      | 4.15%   |
| 2016    | 120      | 3.95%   |
| 2008    | 88       | 2.9%    |
| 2007    | 58       | 1.91%   |
| 2006    | 17       | 0.56%   |
| 2023    | 8        | 0.26%   |
| 2005    | 6        | 0.2%    |
| Unknown | 3        | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3037     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2931     | 96.32%  |
| Enabled  | 112      | 3.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3031     | 99.8%   |
| Yes  | 6        | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 807      | 26.36%  |
| 8.01-16.0       | 532      | 17.38%  |
| 32.01-64.0      | 525      | 17.15%  |
| 4.01-8.0        | 485      | 15.84%  |
| 3.01-4.0        | 350      | 11.43%  |
| 64.01-256.0     | 215      | 7.02%   |
| 24.01-32.0      | 77       | 2.52%   |
| 1.01-2.0        | 39       | 1.27%   |
| 2.01-3.0        | 18       | 0.59%   |
| More than 256.0 | 11       | 0.36%   |
| 0.51-1.0        | 2        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1040     | 32.23%  |
| 2.01-3.0    | 961      | 29.78%  |
| 4.01-8.0    | 480      | 14.87%  |
| 3.01-4.0    | 464      | 14.38%  |
| 8.01-16.0   | 161      | 4.99%   |
| 0.51-1.0    | 62       | 1.92%   |
| 16.01-24.0  | 24       | 0.74%   |
| 0.01-0.5    | 14       | 0.43%   |
| 24.01-32.0  | 11       | 0.34%   |
| 32.01-64.0  | 9        | 0.28%   |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1221     | 39.36%  |
| 2      | 924      | 29.79%  |
| 3      | 465      | 14.99%  |
| 4      | 214      | 6.9%    |
| 5      | 116      | 3.74%   |
| 6      | 50       | 1.61%   |
| 0      | 37       | 1.19%   |
| 7      | 31       | 1%      |
| 8      | 15       | 0.48%   |
| 9      | 11       | 0.35%   |
| 11     | 6        | 0.19%   |
| 10     | 4        | 0.13%   |
| 13     | 2        | 0.06%   |
| 38     | 1        | 0.03%   |
| 25     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 17     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |
| 12     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1688     | 55.18%  |
| Yes       | 1371     | 44.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3014     | 99.21%  |
| No        | 24       | 0.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1689     | 55.27%  |
| Yes       | 1367     | 44.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2094     | 68.5%   |
| Yes       | 963      | 31.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 655      | 21.55%  |
| Germany      | 360      | 11.84%  |
| France       | 198      | 6.51%   |
| Brazil       | 158      | 5.2%    |
| UK           | 142      | 4.67%   |
| Russia       | 123      | 4.05%   |
| Italy        | 122      | 4.01%   |
| Switzerland  | 121      | 3.98%   |
| Canada       | 117      | 3.85%   |
| Spain        | 77       | 2.53%   |
| Netherlands  | 59       | 1.94%   |
| Australia    | 57       | 1.88%   |
| Poland       | 56       | 1.84%   |
| India        | 48       | 1.58%   |
| Austria      | 40       | 1.32%   |
| Belgium      | 37       | 1.22%   |
| Finland      | 35       | 1.15%   |
| Czechia      | 35       | 1.15%   |
| Sweden       | 34       | 1.12%   |
| Mexico       | 31       | 1.02%   |
| Japan        | 31       | 1.02%   |
| Argentina    | 31       | 1.02%   |
| Greece       | 26       | 0.86%   |
| Turkey       | 20       | 0.66%   |
| South Africa | 20       | 0.66%   |
| Hungary      | 20       | 0.66%   |
| China        | 18       | 0.59%   |
| Portugal     | 17       | 0.56%   |
| Bulgaria     | 17       | 0.56%   |
| Romania      | 16       | 0.53%   |
| Slovakia     | 15       | 0.49%   |
| South Korea  | 14       | 0.46%   |
| Norway       | 12       | 0.39%   |
| Denmark      | 11       | 0.36%   |
| Serbia       | 10       | 0.33%   |
| New Zealand  | 10       | 0.33%   |
| Algeria      | 10       | 0.33%   |
| Thailand     | 9        | 0.3%    |
| Slovenia     | 9        | 0.3%    |
| Philippines  | 9        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zurich            | 94       | 2.99%   |
| Berlin            | 28       | 0.89%   |
| Vienna            | 27       | 0.86%   |
| Sydney            | 24       | 0.76%   |
| Cheboksary        | 24       | 0.76%   |
| Moscow            | 22       | 0.7%    |
| Milan             | 22       | 0.7%    |
| Paris             | 21       | 0.67%   |
| Helsinki          | 19       | 0.6%    |
| Sao Paulo         | 17       | 0.54%   |
| Rio de Janeiro    | 16       | 0.51%   |
| Madrid            | 16       | 0.51%   |
| Seattle           | 15       | 0.48%   |
| Prague            | 15       | 0.48%   |
| St Petersburg     | 14       | 0.44%   |
| London            | 14       | 0.44%   |
| Athens            | 14       | 0.44%   |
| Toronto           | 13       | 0.41%   |
| San Jose          | 13       | 0.41%   |
| Warsaw            | 12       | 0.38%   |
| New York          | 12       | 0.38%   |
| Munich            | 12       | 0.38%   |
| Istanbul          | 12       | 0.38%   |
| Hamburg           | 12       | 0.38%   |
| Dallas            | 12       | 0.38%   |
| Frankfurt am Main | 11       | 0.35%   |
| Rome              | 10       | 0.32%   |
| Los Angeles       | 10       | 0.32%   |
| Budapest          | 10       | 0.32%   |
| Amsterdam         | 10       | 0.32%   |
| Sofia             | 9        | 0.29%   |
| Brisbane          | 9        | 0.29%   |
| Turin             | 8        | 0.25%   |
| Perth             | 8        | 0.25%   |
| Novosibirsk       | 8        | 0.25%   |
| Manchester        | 8        | 0.25%   |
| Lima              | 8        | 0.25%   |
| Košice           | 8        | 0.25%   |
| Houston           | 8        | 0.25%   |
| Bengaluru         | 8        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1009     | 1578   | 18.82%  |
| WDC                         | 988      | 1602   | 18.43%  |
| Samsung Electronics         | 815      | 1244   | 15.2%   |
| Kingston                    | 325      | 398    | 6.06%   |
| Toshiba                     | 276      | 362    | 5.15%   |
| SanDisk                     | 255      | 363    | 4.76%   |
| Crucial                     | 232      | 328    | 4.33%   |
| Hitachi                     | 175      | 211    | 3.26%   |
| A-DATA Technology           | 81       | 96     | 1.51%   |
| Intel                       | 76       | 88     | 1.42%   |
| Unknown                     | 62       | 102    | 1.16%   |
| HGST                        | 61       | 88     | 1.14%   |
| China                       | 61       | 70     | 1.14%   |
| SK hynix                    | 50       | 60     | 0.93%   |
| Phison Electronics          | 46       | 62     | 0.86%   |
| Intenso                     | 45       | 52     | 0.84%   |
| Silicon Motion              | 41       | 49     | 0.76%   |
| PNY                         | 39       | 45     | 0.73%   |
| SPCC                        | 32       | 51     | 0.6%    |
| Phison                      | 31       | 44     | 0.58%   |
| Micron/Crucial Technology   | 30       | 44     | 0.56%   |
| Kingston Technology Company | 30       | 34     | 0.56%   |
| Micron Technology           | 28       | 39     | 0.52%   |
| OCZ                         | 25       | 41     | 0.47%   |
| Maxtor                      | 23       | 32     | 0.43%   |
| Corsair                     | 22       | 25     | 0.41%   |
| Patriot                     | 21       | 24     | 0.39%   |
| Lexar                       | 21       | 21     | 0.39%   |
| Gigabyte Technology         | 21       | 25     | 0.39%   |
| Transcend                   | 18       | 18     | 0.34%   |
| Team                        | 16       | 25     | 0.3%    |
| Unknown                     | 16       | 18     | 0.3%    |
| Hewlett-Packard             | 15       | 45     | 0.28%   |
| Apacer                      | 13       | 13     | 0.24%   |
| ADATA Technology            | 13       | 17     | 0.24%   |
| KIOXIA                      | 12       | 23     | 0.22%   |
| Realtek Semiconductor       | 11       | 13     | 0.21%   |
| KingSpec                    | 11       | 11     | 0.21%   |
| JMicron Technology          | 11       | 11     | 0.21%   |
| ASMT                        | 11       | 16     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                        | 85       | 1.36%   |
| Seagate ST1000DM010-2EP102 1TB                         | 79       | 1.26%   |
| Seagate ST2000DM008-2FR102 2TB                         | 71       | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB      | 70       | 1.12%   |
| Kingston SA400S37240G 240GB SSD                        | 70       | 1.12%   |
| Samsung SSD 850 EVO 250GB                              | 58       | 0.93%   |
| Samsung SSD 850 EVO 500GB                              | 54       | 0.86%   |
| Samsung SSD 860 EVO 500GB                              | 53       | 0.85%   |
| Samsung SSD 980 PRO 1TB                                | 51       | 0.82%   |
| Kingston SA400S37480G 480GB SSD                        | 41       | 0.66%   |
| Toshiba DT01ACA100 1TB                                 | 40       | 0.64%   |
| Toshiba DT01ACA050 500GB                               | 40       | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB                         | 39       | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB                         | 38       | 0.61%   |
| Crucial CT500MX500SSD1 500GB                           | 36       | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                               | 34       | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                         | 33       | 0.53%   |
| Kingston SA400S37120G 120GB SSD                        | 32       | 0.51%   |
| Samsung NVMe SSD Drive 1TB                             | 31       | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                            | 30       | 0.48%   |
| Toshiba HDWD110 1TB                                    | 29       | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                             | 29       | 0.46%   |
| Crucial CT240BX500SSD1 240GB                           | 29       | 0.46%   |
| Samsung SSD 980 1TB                                    | 28       | 0.45%   |
| Unknown SD/MMC/MS PRO 249GB                            | 26       | 0.42%   |
| Seagate ST2000DM006-2DM164 2TB                         | 26       | 0.42%   |
| Samsung SSD 860 EVO 1TB                                | 25       | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB                         | 24       | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB     | 24       | 0.38%   |
| Toshiba VT180 240GB SSD                                | 23       | 0.37%   |
| Toshiba DT01ACA200 2TB                                 | 22       | 0.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 22       | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                       | 22       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB                         | 21       | 0.34%   |
| Seagate ST3500418AS 500GB                              | 20       | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB                         | 20       | 0.32%   |
| Samsung SSD 870 QVO 1TB                                | 20       | 0.32%   |
| Samsung SSD 860 EVO 250GB                              | 20       | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB                           | 19       | 0.3%    |
| Samsung SSD 870 EVO 500GB                              | 19       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 986      | 1531   | 38.32%  |
| WDC                 | 870      | 1410   | 33.81%  |
| Toshiba             | 235      | 302    | 9.13%   |
| Hitachi             | 175      | 211    | 6.8%    |
| Samsung Electronics | 133      | 189    | 5.17%   |
| HGST                | 61       | 84     | 2.37%   |
| Unknown             | 29       | 38     | 1.13%   |
| Maxtor              | 21       | 28     | 0.82%   |
| Intenso             | 13       | 14     | 0.51%   |
| JMicron Technology  | 10       | 10     | 0.39%   |
| Fujitsu             | 6        | 7      | 0.23%   |
| Apple               | 6        | 6      | 0.23%   |
| WD MediaMax         | 4        | 4      | 0.16%   |
| Hewlett-Packard     | 3        | 10     | 0.12%   |
| ASMT                | 3        | 4      | 0.12%   |
| ASMedia             | 3        | 3      | 0.12%   |
| USB3.0              | 2        | 3      | 0.08%   |
| Inateck             | 2        | 2      | 0.08%   |
| HPE                 | 2        | 3      | 0.08%   |
| SABRENT             | 1        | 2      | 0.04%   |
| QUANTUM             | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 1      | 0.04%   |
| LaCie               | 1        | 1      | 0.04%   |
| HGST HTS            | 1        | 1      | 0.04%   |
| External            | 1        | 1      | 0.04%   |
| ExcelStor           | 1        | 1      | 0.04%   |
| DAS                 | 1        | 3      | 0.04%   |
| Adaptec             | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 419      | 553    | 22.78%  |
| Kingston            | 273      | 332    | 14.85%  |
| Crucial             | 211      | 298    | 11.47%  |
| SanDisk             | 141      | 199    | 7.67%   |
| WDC                 | 110      | 132    | 5.98%   |
| A-DATA Technology   | 70       | 84     | 3.81%   |
| China               | 60       | 68     | 3.26%   |
| Toshiba             | 48       | 53     | 2.61%   |
| Intel               | 46       | 50     | 2.5%    |
| PNY                 | 35       | 41     | 1.9%    |
| SPCC                | 31       | 49     | 1.69%   |
| Intenso             | 24       | 29     | 1.31%   |
| OCZ                 | 23       | 27     | 1.25%   |
| Patriot             | 20       | 23     | 1.09%   |
| Transcend           | 18       | 18     | 0.98%   |
| Micron Technology   | 18       | 29     | 0.98%   |
| Team                | 16       | 25     | 0.87%   |
| SK hynix            | 16       | 20     | 0.87%   |
| Lexar               | 15       | 15     | 0.82%   |
| Gigabyte Technology | 15       | 19     | 0.82%   |
| Corsair             | 13       | 15     | 0.71%   |
| KingSpec            | 11       | 11     | 0.6%    |
| Hewlett-Packard     | 11       | 11     | 0.6%    |
| Apacer              | 11       | 11     | 0.6%    |
| GOODRAM             | 9        | 14     | 0.49%   |
| Unknown             | 9        | 10     | 0.49%   |
| ASMT                | 8        | 12     | 0.44%   |
| LITEONIT            | 6        | 6      | 0.33%   |
| LITEON              | 6        | 7      | 0.33%   |
| Emtec               | 6        | 6      | 0.33%   |
| Dogfish             | 6        | 10     | 0.33%   |
| Seagate             | 5        | 7      | 0.27%   |
| Netac               | 5        | 6      | 0.27%   |
| Mushkin             | 5        | 5      | 0.27%   |
| Fanxiang            | 5        | 6      | 0.27%   |
| Plextor             | 4        | 4      | 0.22%   |
| LDLC                | 4        | 4      | 0.22%   |
| KingDian            | 4        | 4      | 0.22%   |
| Verbatim            | 3        | 4      | 0.16%   |
| Leven               | 3        | 6      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2000     | 3871   | 43.79%  |
| SSD     | 1562     | 2332   | 34.2%   |
| NVMe    | 878      | 1323   | 19.22%  |
| Unknown | 109      | 182    | 2.39%   |
| MMC     | 18       | 26     | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2658     | 6011   | 70.19%  |
| NVMe | 873      | 1314   | 23.05%  |
| SAS  | 238      | 383    | 6.28%   |
| MMC  | 18       | 26     | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1858     | 2940   | 47.59%  |
| 0.51-1.0   | 1112     | 1667   | 28.48%  |
| 1.01-2.0   | 461      | 716    | 11.81%  |
| 3.01-4.0   | 203      | 307    | 5.2%    |
| 4.01-10.0  | 119      | 297    | 3.05%   |
| 2.01-3.0   | 106      | 154    | 2.72%   |
| 10.01-20.0 | 45       | 122    | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 751      | 23.99%  |
| 251-500        | 587      | 18.75%  |
| 501-1000       | 576      | 18.4%   |
| 1001-2000      | 345      | 11.02%  |
| More than 3000 | 310      | 9.9%    |
| 2001-3000      | 161      | 5.14%   |
| 51-100         | 156      | 4.98%   |
| 1-20           | 125      | 3.99%   |
| 21-50          | 60       | 1.92%   |
| Unknown        | 59       | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1017     | 31.8%   |
| 21-50          | 574      | 17.95%  |
| 51-100         | 379      | 11.85%  |
| 101-250        | 373      | 11.66%  |
| 251-500        | 261      | 8.16%   |
| 501-1000       | 218      | 6.82%   |
| More than 3000 | 135      | 4.22%   |
| 1001-2000      | 124      | 3.88%   |
| Unknown        | 59       | 1.84%   |
| 2001-3000      | 57       | 1.78%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 7        | 7      | 2.57%   |
| WDC WD40EFRX-68WT0N0 4TB            | 6        | 7      | 2.21%   |
| WDC WD10EARS-00Y5B1 1TB             | 4        | 5      | 1.47%   |
| Seagate ST3250310AS 250GB           | 3        | 3      | 1.1%    |
| SanDisk SSD PLUS 480GB              | 3        | 3      | 1.1%    |
| Kingston SA400S37240G 240GB SSD     | 3        | 3      | 1.1%    |
| WDC WD5000AAKX-08ERMA0 500GB        | 2        | 2      | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 0.74%   |
| WDC WD4003FZEX-00Z4SA0 4TB          | 2        | 4      | 0.74%   |
| WDC WD30EZRX-00MMMB0 3TB            | 2        | 6      | 0.74%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 2        | 2      | 0.74%   |
| WDC WD10EZEX-22MFCA0 1TB            | 2        | 2      | 0.74%   |
| Toshiba DT01ACA100 1TB              | 2        | 2      | 0.74%   |
| Seagate ST3750528AS 752GB           | 2        | 2      | 0.74%   |
| Seagate ST3500418AS 500GB           | 2        | 2      | 0.74%   |
| Seagate ST3320620AS 320GB           | 2        | 2      | 0.74%   |
| Seagate ST31000528AS 1TB            | 2        | 2      | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB      | 2        | 2      | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 2      | 0.74%   |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 2      | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 2      | 0.74%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 2      | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 2      | 0.74%   |
| Samsung Electronics SSD 980 PRO 1TB | 2        | 3      | 0.74%   |
| Samsung Electronics SSD 970 EVO 1TB | 2        | 2      | 0.74%   |
| Samsung Electronics SSD 870 EVO 1TB | 2        | 2      | 0.74%   |
| Samsung Electronics HD322GJ 320GB   | 2        | 2      | 0.74%   |
| LITEONIT LCT-128M3S 128GB SSD       | 2        | 2      | 0.74%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 2      | 0.74%   |
| Intel SSDSC2CW120A3 120GB           | 2        | 2      | 0.74%   |
| Hitachi HUA722010CLA330 1TB         | 2        | 2      | 0.74%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 2      | 0.74%   |
| Crucial CT480M500SSD1 480GB         | 2        | 2      | 0.74%   |
| A-DATA Technology SU650 240GB SSD   | 2        | 2      | 0.74%   |
| YS SSD 128GB                        | 1        | 1      | 0.37%   |
| XPG GAMMIX S41 512GB                | 1        | 1      | 0.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 1      | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 0.37%   |
| WDC WD7500AARS-00Y5B1 752GB         | 1        | 1      | 0.37%   |
| WDC WD75 00BPVT-16HXZ 752GB         | 1        | 1      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 82       | 100    | 30.71%  |
| Seagate             | 68       | 78     | 25.47%  |
| Samsung Electronics | 29       | 33     | 10.86%  |
| Hitachi             | 18       | 18     | 6.74%   |
| Toshiba             | 9        | 9      | 3.37%   |
| Kingston            | 9        | 9      | 3.37%   |
| Intel               | 7        | 7      | 2.62%   |
| Crucial             | 6        | 7      | 2.25%   |
| SanDisk             | 5        | 5      | 1.87%   |
| Maxtor              | 5        | 6      | 1.87%   |
| A-DATA Technology   | 4        | 4      | 1.5%    |
| LITEONIT            | 3        | 3      | 1.12%   |
| China               | 3        | 3      | 1.12%   |
| LDLC                | 2        | 2      | 0.75%   |
| Intenso             | 2        | 2      | 0.75%   |
| YS                  | 1        | 1      | 0.37%   |
| XPG                 | 1        | 1      | 0.37%   |
| WD MediaMax         | 1        | 1      | 0.37%   |
| SK hynix            | 1        | 1      | 0.37%   |
| Silicon Motion      | 1        | 1      | 0.37%   |
| PNY                 | 1        | 1      | 0.37%   |
| OCZ                 | 1        | 1      | 0.37%   |
| Netac               | 1        | 1      | 0.37%   |
| Mushkin             | 1        | 1      | 0.37%   |
| Micron Technology   | 1        | 7      | 0.37%   |
| KingSpec            | 1        | 1      | 0.37%   |
| HGST                | 1        | 2      | 0.37%   |
| Gigabyte Technology | 1        | 1      | 0.37%   |
| ASMedia             | 1        | 1      | 0.37%   |
| Unknown             | 1        | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 80       | 98     | 40.61%  |
| Seagate             | 68       | 78     | 34.52%  |
| Hitachi             | 18       | 18     | 9.14%   |
| Samsung Electronics | 15       | 16     | 7.61%   |
| Toshiba             | 8        | 8      | 4.06%   |
| Maxtor              | 5        | 6      | 2.54%   |
| WD MediaMax         | 1        | 1      | 0.51%   |
| HGST                | 1        | 2      | 0.51%   |
| ASMedia             | 1        | 1      | 0.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 184      | 228    | 72.44%  |
| SSD  | 57       | 65     | 22.44%  |
| NVMe | 13       | 15     | 5.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-22VWA0 320GB           | 1        | 1      | 20%     |
| Samsung Electronics SSD 980 500GB     | 1        | 1      | 20%     |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 20%     |
| Intel SSDPEKKW256G7 256GB             | 1        | 1      | 20%     |
| Hewlett-Packard EF0450FARMV 450GB     | 1        | 4      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |
| Intel               | 1        | 1      | 20%     |
| Hewlett-Packard     | 1        | 4      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2066     | 5308   | 62.74%  |
| Works    | 986      | 2110   | 29.94%  |
| Malfunc  | 236      | 308    | 7.17%   |
| Failed   | 5        | 8      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 2011     | 45.84%  |
| AMD                            | 927      | 21.13%  |
| Samsung Electronics            | 345      | 7.86%   |
| ASMedia Technology             | 172      | 3.92%   |
| SanDisk                        | 170      | 3.88%   |
| Marvell Technology Group       | 93       | 2.12%   |
| Phison Electronics             | 89       | 2.03%   |
| Kingston Technology Company    | 85       | 1.94%   |
| JMicron Technology             | 85       | 1.94%   |
| Nvidia                         | 75       | 1.71%   |
| Micron/Crucial Technology      | 54       | 1.23%   |
| Silicon Motion                 | 46       | 1.05%   |
| SK hynix                       | 36       | 0.82%   |
| ADATA Technology               | 27       | 0.62%   |
| LSI Logic / Symbios Logic      | 19       | 0.43%   |
| KIOXIA                         | 17       | 0.39%   |
| Realtek Semiconductor          | 16       | 0.36%   |
| Silicon Image                  | 15       | 0.34%   |
| VIA Technologies               | 13       | 0.3%    |
| Broadcom / LSI                 | 13       | 0.3%    |
| Seagate Technology             | 12       | 0.27%   |
| Micron Technology              | 11       | 0.25%   |
| MAXIO Technology (Hangzhou)    | 9        | 0.21%   |
| Adaptec                        | 7        | 0.16%   |
| Shenzhen Longsys Electronics   | 6        | 0.14%   |
| Toshiba America Info Systems   | 4        | 0.09%   |
| Lite-On Technology             | 3        | 0.07%   |
| Hewlett-Packard                | 3        | 0.07%   |
| Union Memory (Shenzhen)        | 2        | 0.05%   |
| Solidigm                       | 2        | 0.05%   |
| OCZ Technology Group           | 2        | 0.05%   |
| Integrated Technology Express  | 2        | 0.05%   |
| INNOGRIT                       | 2        | 0.05%   |
| Apple                          | 2        | 0.05%   |
| 3ware                          | 2        | 0.05%   |
| Western Digital                | 1        | 0.02%   |
| TenaFe                         | 1        | 0.02%   |
| Tekram Technology              | 1        | 0.02%   |
| Solid State Storage Technology | 1        | 0.02%   |
| Lite-On IT Corp. / Plextor     | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 507      | 9.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 249      | 4.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 173      | 3.25%   |
| AMD 400 Series Chipset SATA Controller                                                  | 171      | 3.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 170      | 3.2%    |
| Intel SATA Controller [RAID mode]                                                       | 162      | 3.05%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 160      | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 157      | 2.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 141      | 2.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 140      | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 129      | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 120      | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 109      | 2.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 102      | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 92       | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 91       | 1.71%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 82       | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 81       | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 75       | 1.41%   |
| AMD FCH SATA Controller D                                                               | 70       | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 62       | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 61       | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 59       | 1.11%   |
| Samsung NVMe SSD Controller 980                                                         | 54       | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 51       | 0.96%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 47       | 0.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 42       | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 41       | 0.77%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 39       | 0.73%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 39       | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 38       | 0.71%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 38       | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 35       | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 34       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34       | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 33       | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 32       | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                                 | 31       | 0.58%   |
| AMD 300 Series Chipset SATA Controller                                                  | 31       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2491     | 58.17%  |
| NVMe | 876      | 20.46%  |
| IDE  | 578      | 13.5%   |
| RAID | 288      | 6.73%   |
| SAS  | 37       | 0.86%   |
| SCSI | 12       | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2050     | 67.5%   |
| AMD    | 987      | 32.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 54       | 1.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 47       | 1.54%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 40       | 1.31%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 37       | 1.21%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 37       | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 34       | 1.12%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 34       | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 33       | 1.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 33       | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 32       | 1.05%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 31       | 1.02%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 30       | 0.98%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 30       | 0.98%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 29       | 0.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 29       | 0.95%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 28       | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 27       | 0.89%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 27       | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 24       | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 24       | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 24       | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 23       | 0.76%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 21       | 0.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 20       | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 20       | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 19       | 0.62%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 19       | 0.62%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 18       | 0.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 18       | 0.59%   |
| Intel 12th Gen Core i9-12900K               | 18       | 0.59%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 18       | 0.59%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 17       | 0.56%   |
| Intel 11th Gen Core i9-11900F @ 2.50GHz     | 17       | 0.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 17       | 0.56%   |
| AMD FX-6300 Six-Core Processor              | 17       | 0.56%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 16       | 0.53%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 16       | 0.53%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 16       | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 16       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 594      | 19.53%  |
| Intel Core i7           | 443      | 14.57%  |
| Intel Core i3           | 251      | 8.25%   |
| AMD Ryzen 5             | 242      | 7.96%   |
| Intel Xeon              | 192      | 6.31%   |
| Other                   | 174      | 5.72%   |
| AMD Ryzen 7             | 164      | 5.39%   |
| AMD FX                  | 106      | 3.49%   |
| AMD Ryzen 9             | 105      | 3.45%   |
| Intel Celeron           | 84       | 2.76%   |
| Intel Core 2 Duo        | 71       | 2.33%   |
| Intel Core 2 Quad       | 68       | 2.24%   |
| Intel Pentium           | 66       | 2.17%   |
| AMD Ryzen 3             | 50       | 1.64%   |
| AMD A10                 | 36       | 1.18%   |
| Intel Pentium Dual-Core | 31       | 1.02%   |
| AMD Phenom II X4        | 31       | 1.02%   |
| Intel Core i9           | 30       | 0.99%   |
| AMD A8                  | 29       | 0.95%   |
| AMD Athlon II X2        | 27       | 0.89%   |
| AMD Ryzen Threadripper  | 26       | 0.85%   |
| AMD A6                  | 18       | 0.59%   |
| AMD Athlon 64 X2        | 17       | 0.56%   |
| AMD A4                  | 16       | 0.53%   |
| Intel Core 2            | 15       | 0.49%   |
| AMD Phenom II X6        | 15       | 0.49%   |
| Intel Atom              | 13       | 0.43%   |
| AMD Athlon II X4        | 13       | 0.43%   |
| AMD Athlon              | 11       | 0.36%   |
| Intel Pentium Dual      | 9        | 0.3%    |
| AMD Sempron             | 8        | 0.26%   |
| AMD Ryzen 5 PRO         | 8        | 0.26%   |
| AMD Phenom II X2        | 8        | 0.26%   |
| AMD Athlon II X3        | 7        | 0.23%   |
| Intel Pentium 4         | 5        | 0.16%   |
| Intel Pentium Gold      | 4        | 0.13%   |
| AMD Ryzen 7 PRO         | 4        | 0.13%   |
| AMD Ryzen 3 PRO         | 4        | 0.13%   |
| AMD Phenom              | 4        | 0.13%   |
| AMD Athlon X4           | 4        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1253     | 41.18%  |
| 2      | 654      | 21.49%  |
| 6      | 449      | 14.76%  |
| 8      | 330      | 10.84%  |
| 12     | 115      | 3.78%   |
| 16     | 86       | 2.83%   |
| 1      | 50       | 1.64%   |
| 3      | 42       | 1.38%   |
| 10     | 24       | 0.79%   |
| 24     | 13       | 0.43%   |
| 32     | 9        | 0.3%    |
| 14     | 6        | 0.2%    |
| 20     | 4        | 0.13%   |
| 28     | 3        | 0.1%    |
| 64     | 2        | 0.07%   |
| 18     | 2        | 0.07%   |
| 40     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2982     | 98.19%  |
| 2      | 55       | 1.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 1788     | 58.84%  |
| 1      | 1249     | 41.1%   |
| 6      | 1        | 0.03%   |
| 4      | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3035     | 99.9%   |
| Unknown        | 3        | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1869     | 60.06%  |
| 0x306c3    | 128      | 4.11%   |
| 0x306a9    | 90       | 2.89%   |
| 0x506e3    | 80       | 2.57%   |
| 0x206a7    | 67       | 2.15%   |
| 0x08701021 | 52       | 1.67%   |
| 0x906e9    | 48       | 1.54%   |
| 0x906ea    | 47       | 1.51%   |
| 0x90672    | 36       | 1.16%   |
| 0x0a201016 | 34       | 1.09%   |
| 0xa0653    | 30       | 0.96%   |
| 0x06000852 | 30       | 0.96%   |
| 0xa0671    | 29       | 0.93%   |
| 0x306f2    | 29       | 0.93%   |
| 0x0800820d | 27       | 0.87%   |
| 0x010000c8 | 25       | 0.8%    |
| 0x0a20120a | 24       | 0.77%   |
| 0x906ed    | 22       | 0.71%   |
| 0x1067a    | 22       | 0.71%   |
| 0xa0655    | 19       | 0.61%   |
| 0x08108109 | 17       | 0.55%   |
| 0x08701013 | 16       | 0.51%   |
| 0x06003106 | 14       | 0.45%   |
| 0x906ec    | 13       | 0.42%   |
| 0x0a50000c | 13       | 0.42%   |
| 0x06001119 | 13       | 0.42%   |
| 0x906eb    | 11       | 0.35%   |
| 0x0a50000d | 11       | 0.35%   |
| 0x0a201205 | 11       | 0.35%   |
| 0x106a5    | 10       | 0.32%   |
| 0x0a601203 | 10       | 0.32%   |
| 0x90675    | 9        | 0.29%   |
| 0x406f1    | 9        | 0.29%   |
| 0x0a201204 | 9        | 0.29%   |
| 0x0a201009 | 9        | 0.29%   |
| 0x0810100b | 9        | 0.29%   |
| 0xb0671    | 8        | 0.26%   |
| 0x20655    | 8        | 0.26%   |
| 0x206d7    | 7        | 0.22%   |
| 0x106e5    | 7        | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 403      | 13.25%  |
| KabyLake         | 275      | 9.04%   |
| IvyBridge        | 249      | 8.19%   |
| Zen 3            | 212      | 6.97%   |
| SandyBridge      | 210      | 6.91%   |
| Skylake          | 195      | 6.41%   |
| Zen 2            | 188      | 6.18%   |
| Penryn           | 146      | 4.8%    |
| Piledriver       | 134      | 4.41%   |
| K10              | 118      | 3.88%   |
| Zen+             | 110      | 3.62%   |
| Unknown          | 107      | 3.52%   |
| CometLake        | 91       | 2.99%   |
| Westmere         | 89       | 2.93%   |
| Zen              | 81       | 2.66%   |
| Core             | 71       | 2.33%   |
| Nehalem          | 51       | 1.68%   |
| Alderlake Hybrid | 51       | 1.68%   |
| Steamroller      | 33       | 1.09%   |
| Icelake          | 30       | 0.99%   |
| Silvermont       | 29       | 0.95%   |
| K8 Hammer        | 27       | 0.89%   |
| Broadwell        | 22       | 0.72%   |
| Excavator        | 21       | 0.69%   |
| Bulldozer        | 21       | 0.69%   |
| Goldmont plus    | 17       | 0.56%   |
| Goldmont         | 12       | 0.39%   |
| NetBurst         | 9        | 0.3%    |
| K10 Llano        | 7        | 0.23%   |
| Tremont          | 6        | 0.2%    |
| TigerLake        | 6        | 0.2%    |
| Puma             | 5        | 0.16%   |
| Jaguar           | 5        | 0.16%   |
| Bonnell          | 5        | 0.16%   |
| Bobcat           | 5        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1372     | 42.05%  |
| Intel                                        | 1035     | 31.72%  |
| AMD                                          | 824      | 25.25%  |
| Matrox Electronics Systems                   | 15       | 0.46%   |
| ASPEED Technology                            | 13       | 0.4%    |
| ATI Technologies                             | 2        | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.03%   |
| VIA Technologies                             | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 189      | 5.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 103      | 3.09%   |
| Intel HD Graphics 530                                                       | 100      | 3%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 100      | 3%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 97       | 2.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 76       | 2.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 70       | 2.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 52       | 1.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 51       | 1.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 51       | 1.53%   |
| Intel HD Graphics 630                                                       | 50       | 1.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 45       | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 45       | 1.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 42       | 1.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 41       | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 40       | 1.2%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 38       | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 36       | 1.08%   |
| Intel AlderLake-S GT1                                                       | 34       | 1.02%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 33       | 0.99%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 33       | 0.99%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 29       | 0.87%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 27       | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 26       | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 26       | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 25       | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 25       | 0.75%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 25       | 0.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 24       | 0.72%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 24       | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 24       | 0.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 23       | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 23       | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 23       | 0.69%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 22       | 0.66%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 22       | 0.66%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 21       | 0.63%   |
| Nvidia GP107GL [Quadro P400]                                                | 20       | 0.6%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 19       | 0.57%   |
| AMD RS780L [Radeon 3000]                                                    | 19       | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1249     | 40.79%  |
| 1 x Intel                | 880      | 28.74%  |
| 1 x AMD                  | 742      | 24.23%  |
| Intel + Nvidia           | 54       | 1.76%   |
| AMD + Nvidia             | 34       | 1.11%   |
| 2 x AMD                  | 30       | 0.98%   |
| 2 x Nvidia               | 21       | 0.69%   |
| Intel + AMD              | 17       | 0.56%   |
| 1 x Matrox               | 11       | 0.36%   |
| 1 x ASPEED               | 7        | 0.23%   |
| Nvidia + ASPEED          | 5        | 0.16%   |
| Nvidia + Matrox          | 3        | 0.1%    |
| Other                    | 2        | 0.07%   |
| 3 x AMD                  | 1        | 0.03%   |
| 1 x XGI                  | 1        | 0.03%   |
| 1 x VIA                  | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |
| AMD + ASPEED             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2087     | 67.67%  |
| Proprietary | 843      | 27.33%  |
| Unknown     | 154      | 4.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2206     | 71.53%  |
| 1.01-2.0   | 204      | 6.61%   |
| 0.51-1.0   | 146      | 4.73%   |
| 7.01-8.0   | 145      | 4.7%    |
| 3.01-4.0   | 128      | 4.15%   |
| 0.01-0.5   | 91       | 2.95%   |
| 8.01-16.0  | 72       | 2.33%   |
| 5.01-6.0   | 46       | 1.49%   |
| 16.01-24.0 | 21       | 0.68%   |
| 2.01-3.0   | 20       | 0.65%   |
| 4.01-5.0   | 5        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 534      | 17.61%  |
| Dell                 | 352      | 11.61%  |
| Goldstar             | 265      | 8.74%   |
| Hewlett-Packard      | 208      | 6.86%   |
| Acer                 | 208      | 6.86%   |
| BenQ                 | 153      | 5.04%   |
| Philips              | 140      | 4.62%   |
| AOC                  | 136      | 4.48%   |
| Ancor Communications | 126      | 4.15%   |
| Lenovo               | 67       | 2.21%   |
| Iiyama               | 66       | 2.18%   |
| ViewSonic            | 61       | 2.01%   |
| ASUSTek Computer     | 56       | 1.85%   |
| Sony                 | 39       | 1.29%   |
| Vizio                | 32       | 1.06%   |
| Fujitsu Siemens      | 26       | 0.86%   |
| LG Electronics       | 25       | 0.82%   |
| Unknown              | 22       | 0.73%   |
| Panasonic            | 22       | 0.73%   |
| NEC Computers        | 22       | 0.73%   |
| Eizo                 | 20       | 0.66%   |
| Sceptre Tech         | 19       | 0.63%   |
| MSI                  | 17       | 0.56%   |
| Medion               | 17       | 0.56%   |
| Unknown              | 17       | 0.56%   |
| HannStar             | 15       | 0.49%   |
| Toshiba              | 12       | 0.4%    |
| Sharp                | 10       | 0.33%   |
| HKC                  | 10       | 0.33%   |
| Gigabyte Technology  | 10       | 0.33%   |
| Vestel Elektronik    | 9        | 0.3%    |
| Hitachi              | 9        | 0.3%    |
| Apple                | 9        | 0.3%    |
| MStar                | 8        | 0.26%   |
| Unknown (XXX)        | 7        | 0.23%   |
| RTK                  | 7        | 0.23%   |
| Plain Tree Systems   | 7        | 0.23%   |
| Onkyo                | 7        | 0.23%   |
| Mi                   | 7        | 0.23%   |
| Gericom              | 7        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 21       | 0.65%   |
| Unknown                                                                | 17       | 0.53%   |
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                    | 15       | 0.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 13       | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 13       | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 11       | 0.34%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 11       | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 11       | 0.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 10       | 0.31%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 10       | 0.31%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 9        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 9        | 0.28%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                    | 9        | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 8        | 0.25%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 7        | 0.22%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 7        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 7        | 0.22%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 7        | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 6        | 0.19%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 6        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 6        | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 6        | 0.19%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 6        | 0.19%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 6        | 0.19%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 6        | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 6        | 0.19%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 6        | 0.19%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                     | 6        | 0.19%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                        | 6        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 6        | 0.19%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 6        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 6        | 0.19%   |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                      | 6        | 0.19%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                      | 6        | 0.19%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch       | 6        | 0.19%   |
| ViewSonic VA2246 Series VSC6F2E 1920x1080 477x268mm 21.5-inch          | 5        | 0.16%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 5        | 0.16%   |
| Sceptre Tech E248W-19203S SPT099D 1920x1080 443x249mm 20.0-inch        | 5        | 0.16%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 5        | 0.16%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 5        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1400     | 47.09%  |
| 3840x2160 (4K)     | 331      | 11.13%  |
| 2560x1440 (QHD)    | 208      | 7%      |
| 1280x1024 (SXGA)   | 169      | 5.68%   |
| 1680x1050 (WSXGA+) | 146      | 4.91%   |
| 1366x768 (WXGA)    | 104      | 3.5%    |
| 1920x1200 (WUXGA)  | 97       | 3.26%   |
| 1440x900 (WXGA+)   | 90       | 3.03%   |
| 1600x900 (HD+)     | 86       | 2.89%   |
| 3440x1440          | 43       | 1.45%   |
| Unknown            | 43       | 1.45%   |
| 2560x1080          | 38       | 1.28%   |
| 1360x768           | 36       | 1.21%   |
| 1920x540           | 31       | 1.04%   |
| 3840x1080          | 27       | 0.91%   |
| 1280x720 (HD)      | 19       | 0.64%   |
| 1024x768 (XGA)     | 18       | 0.61%   |
| 1600x1200          | 13       | 0.44%   |
| 2560x1600          | 10       | 0.34%   |
| 2288x1287          | 10       | 0.34%   |
| 3840x1600          | 6        | 0.2%    |
| 2048x1152          | 5        | 0.17%   |
| 3840x1200          | 4        | 0.13%   |
| 1400x1050          | 4        | 0.13%   |
| 1280x960           | 4        | 0.13%   |
| 4480x1440          | 3        | 0.1%    |
| 5120x1440          | 2        | 0.07%   |
| 3600x1080          | 2        | 0.07%   |
| 3360x1080          | 2        | 0.07%   |
| 720x480            | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 5760x2160          | 1        | 0.03%   |
| 5760x1080          | 1        | 0.03%   |
| 5520x1080          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4093x4093          | 1        | 0.03%   |
| 4080x2058          | 1        | 0.03%   |
| 3840x2560          | 1        | 0.03%   |
| 3520x1200          | 1        | 0.03%   |
| 3520x1080          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 427      | 14.07%  |
| 24      | 414      | 13.65%  |
| 23      | 369      | 12.16%  |
| 21      | 332      | 10.94%  |
| Unknown | 230      | 7.58%   |
| 19      | 185      | 6.1%    |
| 31      | 164      | 5.41%   |
| 22      | 98       | 3.23%   |
| 20      | 98       | 3.23%   |
| 18      | 95       | 3.13%   |
| 17      | 86       | 2.83%   |
| 34      | 62       | 2.04%   |
| 84      | 58       | 1.91%   |
| 32      | 49       | 1.62%   |
| 15      | 40       | 1.32%   |
| 72      | 35       | 1.15%   |
| 40      | 32       | 1.05%   |
| 25      | 30       | 0.99%   |
| 54      | 23       | 0.76%   |
| 28      | 16       | 0.53%   |
| 65      | 12       | 0.4%    |
| 37      | 12       | 0.4%    |
| 52      | 11       | 0.36%   |
| 42      | 11       | 0.36%   |
| 36      | 11       | 0.36%   |
| 29      | 11       | 0.36%   |
| 48      | 10       | 0.33%   |
| 43      | 10       | 0.33%   |
| 26      | 9        | 0.3%    |
| 46      | 8        | 0.26%   |
| 49      | 7        | 0.23%   |
| 142     | 6        | 0.2%    |
| 64      | 6        | 0.2%    |
| 14      | 6        | 0.2%    |
| 47      | 5        | 0.16%   |
| 35      | 5        | 0.16%   |
| 69      | 4        | 0.13%   |
| 60      | 4        | 0.13%   |
| 57      | 4        | 0.13%   |
| 39      | 4        | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1134     | 38.44%  |
| 401-500        | 700      | 23.73%  |
| 601-700        | 239      | 8.1%    |
| Unknown        | 230      | 7.8%    |
| 701-800        | 125      | 4.24%   |
| 301-350        | 120      | 4.07%   |
| 351-400        | 108      | 3.66%   |
| 1501-2000      | 100      | 3.39%   |
| 1001-1500      | 99       | 3.36%   |
| 801-900        | 55       | 1.86%   |
| 901-1000       | 22       | 0.75%   |
| 201-300        | 11       | 0.37%   |
| More than 2000 | 7        | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1936     | 68.39%  |
| 16/10   | 359      | 12.68%  |
| Unknown | 191      | 6.75%   |
| 5/4     | 170      | 6%      |
| 21/9    | 85       | 3%      |
| 4/3     | 42       | 1.48%   |
| 32/9    | 17       | 0.6%    |
| 3/2     | 13       | 0.46%   |
| 1.00    | 8        | 0.28%   |
| 6/5     | 6        | 0.21%   |
| 1.96    | 2        | 0.07%   |
| 0.89    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 946      | 31.71%  |
| 301-350        | 438      | 14.68%  |
| 151-200        | 392      | 13.14%  |
| 351-500        | 298      | 9.99%   |
| Unknown        | 230      | 7.71%   |
| More than 1000 | 182      | 6.1%    |
| 251-300        | 171      | 5.73%   |
| 141-150        | 155      | 5.2%    |
| 501-1000       | 109      | 3.65%   |
| 101-110        | 34       | 1.14%   |
| 111-120        | 8        | 0.27%   |
| 131-140        | 7        | 0.23%   |
| 71-80          | 6        | 0.2%    |
| 81-90          | 3        | 0.1%    |
| 121-130        | 2        | 0.07%   |
| 91-100         | 2        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1777     | 62.11%  |
| 101-120       | 491      | 17.16%  |
| Unknown       | 230      | 8.04%   |
| 1-50          | 157      | 5.49%   |
| 121-160       | 144      | 5.03%   |
| 161-240       | 61       | 2.13%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2319     | 75.27%  |
| 2     | 457      | 14.83%  |
| 0     | 260      | 8.44%   |
| 3     | 39       | 1.27%   |
| 4     | 4        | 0.13%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1811     | 42.2%   |
| Intel                           | 1393     | 32.46%  |
| Qualcomm Atheros                | 222      | 5.17%   |
| Broadcom                        | 127      | 2.96%   |
| Ralink Technology               | 91       | 2.12%   |
| TP-Link                         | 89       | 2.07%   |
| Nvidia                          | 63       | 1.47%   |
| Ralink                          | 54       | 1.26%   |
| MediaTek                        | 42       | 0.98%   |
| NetGear                         | 30       | 0.7%    |
| Broadcom Limited                | 29       | 0.68%   |
| Marvell Technology Group        | 27       | 0.63%   |
| Aquantia                        | 26       | 0.61%   |
| Qualcomm Atheros Communications | 21       | 0.49%   |
| Samsung Electronics             | 19       | 0.44%   |
| Microsoft                       | 19       | 0.44%   |
| D-Link System                   | 17       | 0.4%    |
| D-Link                          | 17       | 0.4%    |
| Xiaomi                          | 14       | 0.33%   |
| ASIX Electronics                | 14       | 0.33%   |
| Edimax Technology               | 13       | 0.3%    |
| ASUSTek Computer                | 12       | 0.28%   |
| Linksys                         | 11       | 0.26%   |
| IMC Networks                    | 10       | 0.23%   |
| DisplayLink                     | 7        | 0.16%   |
| Sitecom Europe                  | 6        | 0.14%   |
| Qualcomm                        | 6        | 0.14%   |
| Belkin Components               | 6        | 0.14%   |
| Wilocity                        | 4        | 0.09%   |
| VIA Technologies                | 4        | 0.09%   |
| JMicron Technology              | 4        | 0.09%   |
| AVM                             | 4        | 0.09%   |
| ZyDAS                           | 3        | 0.07%   |
| Texas Instruments               | 3        | 0.07%   |
| OPPO Electronics                | 3        | 0.07%   |
| Mellanox Technologies           | 3        | 0.07%   |
| ICS Advent                      | 3        | 0.07%   |
| Huawei Technologies             | 3        | 0.07%   |
| Dresden Elektronik              | 3        | 0.07%   |
| Unknown                         | 3        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1412     | 28.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 197      | 4.03%   |
| Intel I211 Gigabit Network Connection                             | 155      | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 146      | 2.99%   |
| Intel Wi-Fi 6 AX200                                               | 143      | 2.93%   |
| Intel Ethernet Connection (2) I219-V                              | 114      | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 103      | 2.11%   |
| Intel Ethernet Controller I225-V                                  | 99       | 2.03%   |
| Intel 82579V Gigabit Network Connection                           | 63       | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 56       | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 56       | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 53       | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 50       | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 48       | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 48       | 0.98%   |
| Realtek 802.11ac NIC                                              | 46       | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 46       | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 45       | 0.92%   |
| Intel Ethernet Connection (2) I218-V                              | 42       | 0.86%   |
| Intel 82574L Gigabit Network Connection                           | 38       | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 36       | 0.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 33       | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 31       | 0.63%   |
| Intel Wireless-AC 9260                                            | 29       | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29       | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27       | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23       | 0.47%   |
| Intel Wireless 7260                                               | 22       | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.43%   |
| Intel Wireless 7265                                               | 21       | 0.43%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 21       | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 20       | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 20       | 0.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19       | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19       | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 19       | 0.39%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19       | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 19       | 0.39%   |
| Ralink RT5370 Wireless Adapter                                    | 18       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 487      | 33.24%  |
| Realtek Semiconductor           | 338      | 23.07%  |
| Qualcomm Atheros                | 127      | 8.67%   |
| Ralink Technology               | 91       | 6.21%   |
| TP-Link                         | 87       | 5.94%   |
| Ralink                          | 54       | 3.69%   |
| Broadcom                        | 51       | 3.48%   |
| MediaTek                        | 37       | 2.53%   |
| NetGear                         | 30       | 2.05%   |
| Qualcomm Atheros Communications | 21       | 1.43%   |
| Microsoft                       | 19       | 1.3%    |
| D-Link                          | 17       | 1.16%   |
| Edimax Technology               | 13       | 0.89%   |
| D-Link System                   | 13       | 0.89%   |
| Broadcom Limited                | 13       | 0.89%   |
| ASUSTek Computer                | 12       | 0.82%   |
| IMC Networks                    | 10       | 0.68%   |
| Linksys                         | 9        | 0.61%   |
| Sitecom Europe                  | 6        | 0.41%   |
| Belkin Components               | 6        | 0.41%   |
| Wilocity                        | 4        | 0.27%   |
| AVM                             | 4        | 0.27%   |
| ZyDAS                           | 3        | 0.2%    |
| Micro Star International        | 2        | 0.14%   |
| Mercucys                        | 2        | 0.14%   |
| Encore Electronics              | 2        | 0.14%   |
| BUFFALO                         | 2        | 0.14%   |
| Sagem                           | 1        | 0.07%   |
| Philips (or NXP)                | 1        | 0.07%   |
| LSI                             | 1        | 0.07%   |
| Gemtek                          | 1        | 0.07%   |
| Dell                            | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 143      | 9.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 56       | 3.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 53       | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 48       | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 48       | 3.23%   |
| Realtek 802.11ac NIC                                       | 46       | 3.1%    |
| Ralink MT7601U Wireless Adapter                            | 36       | 2.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 33       | 2.22%   |
| Intel Wireless-AC 9260                                     | 29       | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 27       | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 23       | 1.55%   |
| Intel Wireless 7260                                        | 22       | 1.48%   |
| Intel Wireless 7265                                        | 21       | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 21       | 1.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 20       | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 19       | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 19       | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                             | 19       | 1.28%   |
| Ralink RT5370 Wireless Adapter                             | 18       | 1.21%   |
| Qualcomm Atheros AR9271 802.11n                            | 18       | 1.21%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 18       | 1.21%   |
| Intel Wireless 3165                                        | 18       | 1.21%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 17       | 1.14%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 16       | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 16       | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 15       | 1.01%   |
| Intel Wireless 8260                                        | 15       | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 14       | 0.94%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 14       | 0.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 14       | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 13       | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 13       | 0.87%   |
| TP-Link 802.11ac WLAN Adapter                              | 12       | 0.81%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 12       | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 12       | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 11       | 0.74%   |
| Microsoft Xbox Wireless Adapter for Windows                | 11       | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 10       | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 10       | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 10       | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1687     | 52%     |
| Intel                                  | 1140     | 35.14%  |
| Qualcomm Atheros                       | 104      | 3.21%   |
| Broadcom                               | 77       | 2.37%   |
| Nvidia                                 | 63       | 1.94%   |
| Marvell Technology Group               | 27       | 0.83%   |
| Aquantia                               | 26       | 0.8%    |
| Broadcom Limited                       | 16       | 0.49%   |
| Xiaomi                                 | 14       | 0.43%   |
| ASIX Electronics                       | 14       | 0.43%   |
| Samsung Electronics                    | 13       | 0.4%    |
| DisplayLink                            | 7        | 0.22%   |
| Qualcomm                               | 6        | 0.18%   |
| VIA Technologies                       | 4        | 0.12%   |
| MediaTek                               | 4        | 0.12%   |
| JMicron Technology                     | 4        | 0.12%   |
| D-Link System                          | 4        | 0.12%   |
| OPPO Electronics                       | 3        | 0.09%   |
| ICS Advent                             | 3        | 0.09%   |
| TP-Link                                | 2        | 0.06%   |
| Tehuti Networks                        | 2        | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.06%   |
| Mellanox Technologies                  | 2        | 0.06%   |
| Linksys                                | 2        | 0.06%   |
| Huawei Technologies                    | 2        | 0.06%   |
| Chelsio Communications                 | 2        | 0.06%   |
| Apple                                  | 2        | 0.06%   |
| American Megatrends                    | 2        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| Prolific Technology                    | 1        | 0.03%   |
| Motorola PCS                           | 1        | 0.03%   |
| MosChip Semiconductor                  | 1        | 0.03%   |
| LG Electronics                         | 1        | 0.03%   |
| Google                                 | 1        | 0.03%   |
| Compal Electronics                     | 1        | 0.03%   |
| 3Com                                   | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1412     | 42.06%  |
| Realtek RTL8125 2.5GbE Controller                                 | 197      | 5.87%   |
| Intel I211 Gigabit Network Connection                             | 155      | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 146      | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 114      | 3.4%    |
| Intel Ethernet Connection I217-LM                                 | 103      | 3.07%   |
| Intel Ethernet Controller I225-V                                  | 99       | 2.95%   |
| Intel 82579V Gigabit Network Connection                           | 63       | 1.88%   |
| Intel Ethernet Connection (7) I219-V                              | 56       | 1.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 50       | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 46       | 1.37%   |
| Intel Ethernet Connection I217-V                                  | 45       | 1.34%   |
| Intel Ethernet Connection (2) I218-V                              | 42       | 1.25%   |
| Intel 82574L Gigabit Network Connection                           | 38       | 1.13%   |
| Nvidia MCP61 Ethernet                                             | 31       | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29       | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 20       | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 19       | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 19       | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 18       | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 15       | 0.45%   |
| Intel 82578DC Gigabit Network Connection                          | 15       | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 15       | 0.45%   |
| Intel Ethernet Controller X550                                    | 14       | 0.42%   |
| Intel Ethernet Connection (14) I219-V                             | 14       | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13       | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 13       | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13       | 0.39%   |
| Intel Ethernet Connection (2) I218-LM                             | 13       | 0.39%   |
| Intel Ethernet Connection (11) I219-V                             | 12       | 0.36%   |
| Intel 82578DM Gigabit Network Connection                          | 12       | 0.36%   |
| Intel Ethernet Connection (17) I219-V                             | 11       | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11       | 0.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 11       | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10       | 0.3%    |
| Nvidia MCP77 Ethernet                                             | 10       | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3013     | 68.15%  |
| WiFi     | 1369     | 30.97%  |
| Modem    | 34       | 0.77%   |
| Unknown  | 5        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2405     | 75.92%  |
| WiFi     | 762      | 24.05%  |
| Modem    | 1        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1924     | 63.1%   |
| 2     | 939      | 30.8%   |
| 3     | 136      | 4.46%   |
| 4     | 21       | 0.69%   |
| 0     | 18       | 0.59%   |
| 5     | 7        | 0.23%   |
| 7     | 2        | 0.07%   |
| 8     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2075     | 67.94%  |
| Yes  | 979      | 32.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 444      | 44.8%   |
| Cambridge Silicon Radio         | 204      | 20.59%  |
| Realtek Semiconductor           | 71       | 7.16%   |
| ASUSTek Computer                | 66       | 6.66%   |
| Qualcomm Atheros Communications | 41       | 4.14%   |
| Broadcom                        | 36       | 3.63%   |
| IMC Networks                    | 22       | 2.22%   |
| MediaTek                        | 21       | 2.12%   |
| Apple                           | 18       | 1.82%   |
| TP-Link                         | 14       | 1.41%   |
| Lite-On Technology              | 14       | 1.41%   |
| Logitech                        | 4        | 0.4%    |
| Edimax Technology               | 4        | 0.4%    |
| Dell                            | 4        | 0.4%    |
| Belkin Components               | 4        | 0.4%    |
| Realtek                         | 3        | 0.3%    |
| Micro Star International        | 3        | 0.3%    |
| Foxconn / Hon Hai               | 3        | 0.3%    |
| Integrated System Solution      | 2        | 0.2%    |
| Hewlett-Packard                 | 2        | 0.2%    |
| D-Link System                   | 2        | 0.2%    |
| Conwise Technology              | 2        | 0.2%    |
| TRENDnet                        | 1        | 0.1%    |
| Toshiba                         | 1        | 0.1%    |
| Ralink                          | 1        | 0.1%    |
| Mobile Action Technology        | 1        | 0.1%    |
| HTC (High Tech Computer)        | 1        | 0.1%    |
| Dynex                           | 1        | 0.1%    |
| Unknown                         | 1        | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 204      | 20.54%  |
| Intel AX200 Bluetooth                                 | 121      | 12.19%  |
| Intel Bluetooth wireless interface                    | 85       | 8.56%   |
| Intel AX201 Bluetooth                                 | 57       | 5.74%   |
| Intel AX210 Bluetooth                                 | 55       | 5.54%   |
| Realtek Bluetooth Radio                               | 51       | 5.14%   |
| Intel Wireless-AC 3168 Bluetooth                      | 46       | 4.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 31       | 3.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 28       | 2.82%   |
| ASUS ASUS USB-BT500                                   | 22       | 2.22%   |
| Qualcomm Atheros  Bluetooth Device                    | 21       | 2.11%   |
| MediaTek Wireless_Device                              | 21       | 2.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 21       | 2.11%   |
| Intel Bluetooth Device                                | 16       | 1.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 16       | 1.61%   |
| TP-Link UB500 Adapter                                 | 14       | 1.41%   |
| Realtek  Bluetooth 4.2 Adapter                        | 12       | 1.21%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 11       | 1.11%   |
| IMC Networks Bluetooth Radio                          | 11       | 1.11%   |
| Lite-On Bluetooth Device                              | 8        | 0.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 8        | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 7        | 0.7%    |
| ASUS Bluetooth Radio                                  | 7        | 0.7%    |
| IMC Networks Wireless_Device                          | 6        | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.5%    |
| ASUS Qualcomm Bluetooth 4.1                           | 5        | 0.5%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 5        | 0.5%    |
| ASUS Bluetooth Device                                 | 5        | 0.5%    |
| ASUS BCM20702A0                                       | 5        | 0.5%    |
| Apple Bluetooth Host Controller                       | 5        | 0.5%    |
| Realtek RTL8821A Bluetooth                            | 4        | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.4%    |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 4        | 0.4%    |
| Realtek Bluetooth Radio                               | 3        | 0.3%    |
| Micro Star International Bluetooth Device             | 3        | 0.3%    |
| IMC Networks Bluetooth Device                         | 3        | 0.3%    |
| Foxconn / Hon Hai Wireless_Device                     | 3        | 0.3%    |
| Edimax Bluetooth Adapter                              | 3        | 0.3%    |
| Broadcom BCM2045 Bluetooth                            | 3        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1954     | 38.71%  |
| Nvidia                                       | 1299     | 25.73%  |
| AMD                                          | 1211     | 23.99%  |
| C-Media Electronics                          | 97       | 1.92%   |
| Creative Labs                                | 52       | 1.03%   |
| Logitech                                     | 50       | 0.99%   |
| ASUSTek Computer                             | 29       | 0.57%   |
| GN Netcom                                    | 25       | 0.5%    |
| Texas Instruments                            | 23       | 0.46%   |
| Micro Star International                     | 23       | 0.46%   |
| Kingston Technology                          | 19       | 0.38%   |
| JMTek                                        | 17       | 0.34%   |
| Razer USA                                    | 14       | 0.28%   |
| Focusrite-Novation                           | 14       | 0.28%   |
| Creative Technology                          | 13       | 0.26%   |
| SteelSeries ApS                              | 12       | 0.24%   |
| Corsair                                      | 11       | 0.22%   |
| Generalplus Technology                       | 10       | 0.2%    |
| Tenx Technology                              | 8        | 0.16%   |
| Plantronics                                  | 8        | 0.16%   |
| VIA Technologies                             | 6        | 0.12%   |
| Giga-Byte Technology                         | 6        | 0.12%   |
| Blue Microphones                             | 6        | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.1%    |
| Sennheiser Communications                    | 5        | 0.1%    |
| Astro Gaming                                 | 5        | 0.1%    |
| Apple                                        | 5        | 0.1%    |
| Sony                                         | 4        | 0.08%   |
| Realtek Semiconductor                        | 4        | 0.08%   |
| M-Audio                                      | 4        | 0.08%   |
| Samson Technologies                          | 3        | 0.06%   |
| RODE Microphones                             | 3        | 0.06%   |
| KTMicro                                      | 3        | 0.06%   |
| Hewlett-Packard                              | 3        | 0.06%   |
| DSEA A/S                                     | 3        | 0.06%   |
| Dell                                         | 3        | 0.06%   |
| Cambridge Silicon Radio                      | 3        | 0.06%   |
| Bose                                         | 3        | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.04%   |
| Syntek                                       | 2        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 327      | 5.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 282      | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 222      | 3.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 209      | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 194      | 3.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 183      | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 182      | 3.14%   |
| Intel 200 Series PCH HD Audio                                              | 154      | 2.66%   |
| AMD Family 17h/19h HD Audio Controller                                     | 152      | 2.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 114      | 1.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 113      | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 109      | 1.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 106      | 1.83%   |
| AMD FCH Azalia Controller                                                  | 98       | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 94       | 1.62%   |
| Intel Alder Lake-S HD Audio Controller                                     | 80       | 1.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 77       | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 77       | 1.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 76       | 1.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 74       | 1.28%   |
| Nvidia High Definition Audio Controller                                    | 72       | 1.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71       | 1.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 69       | 1.19%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 68       | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 66       | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 65       | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                              | 64       | 1.1%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 62       | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 61       | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 60       | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 60       | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 59       | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 52       | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 49       | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 47       | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 46       | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 44       | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                              | 44       | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 44       | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 44       | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 305      | 19.29%  |
| Corsair                      | 239      | 15.12%  |
| Samsung Electronics          | 162      | 10.25%  |
| SK hynix                     | 154      | 9.74%   |
| G.Skill                      | 129      | 8.16%   |
| Unknown                      | 127      | 8.03%   |
| Crucial                      | 121      | 7.65%   |
| Micron Technology            | 75       | 4.74%   |
| A-DATA Technology            | 43       | 2.72%   |
| Team                         | 31       | 1.96%   |
| Unknown                      | 27       | 1.71%   |
| Patriot                      | 19       | 1.2%    |
| Ramaxel Technology           | 14       | 0.89%   |
| Nanya Technology             | 13       | 0.82%   |
| Unknown (ABCD)               | 7        | 0.44%   |
| Transcend                    | 7        | 0.44%   |
| Smart                        | 7        | 0.44%   |
| PNY                          | 7        | 0.44%   |
| Elpida                       | 6        | 0.38%   |
| AMD                          | 6        | 0.38%   |
| Silicon Power                | 5        | 0.32%   |
| GOODRAM                      | 5        | 0.32%   |
| Apacer                       | 5        | 0.32%   |
| Timetec                      | 4        | 0.25%   |
| KETECH                       | 4        | 0.25%   |
| Hewlett-Packard              | 4        | 0.25%   |
| GeIL                         | 4        | 0.25%   |
| Asgard                       | 4        | 0.25%   |
| KLEVV                        | 3        | 0.19%   |
| Kingmax                      | 3        | 0.19%   |
| Avant                        | 3        | 0.19%   |
| Atermiter                    | 3        | 0.19%   |
| ASint Technology             | 3        | 0.19%   |
| Super Talent                 | 2        | 0.13%   |
| Qumo                         | 2        | 0.13%   |
| Patriot Memory (PDP Systems) | 2        | 0.13%   |
| Neo Forza                    | 2        | 0.13%   |
| ZION                         | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (AD8A)               | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 27       | 1.58%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s       | 18       | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 16       | 0.94%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 12       | 0.7%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 12       | 0.7%    |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s          | 12       | 0.7%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 12       | 0.7%    |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 11       | 0.65%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 10       | 0.59%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 10       | 0.59%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 10       | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 9        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 9        | 0.53%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s          | 9        | 0.53%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 9        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 8        | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 8        | 0.47%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 8        | 0.47%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s         | 8        | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 7        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7        | 0.41%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 7        | 0.41%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 7        | 0.41%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 7        | 0.41%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 7        | 0.41%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 7        | 0.41%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 6        | 0.35%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 6        | 0.35%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 6        | 0.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 6        | 0.35%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 6        | 0.35%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 6        | 0.35%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 6        | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 5        | 0.29%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 5        | 0.29%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s             | 5        | 0.29%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 5        | 0.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 5        | 0.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 5        | 0.29%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 5        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 764      | 54.34%  |
| DDR3    | 449      | 31.93%  |
| Unknown | 55       | 3.91%   |
| SDRAM   | 38       | 2.7%    |
| DDR5    | 37       | 2.63%   |
| DDR2    | 34       | 2.42%   |
| LPDDR4  | 15       | 1.07%   |
| DDR     | 10       | 0.71%   |
| LPDDR3  | 2        | 0.14%   |
| DRAM    | 2        | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1273     | 92.18%  |
| SODIMM       | 91       | 6.59%   |
| RIMM         | 9        | 0.65%   |
| Row Of Chips | 6        | 0.43%   |
| FB-DIMM      | 1        | 0.07%   |
| Unknown      | 1        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 552      | 37.2%   |
| 4096   | 322      | 21.7%   |
| 16384  | 319      | 21.5%   |
| 2048   | 145      | 9.77%   |
| 32768  | 117      | 7.88%   |
| 1024   | 25       | 1.68%   |
| 65536  | 2        | 0.13%   |
| 131072 | 1        | 0.07%   |
| 512    | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 278      | 18.03%  |
| 3200    | 198      | 12.84%  |
| 1333    | 142      | 9.21%   |
| 2400    | 124      | 8.04%   |
| 3600    | 118      | 7.65%   |
| 2667    | 97       | 6.29%   |
| 2133    | 68       | 4.41%   |
| 3000    | 41       | 2.66%   |
| 1867    | 39       | 2.53%   |
| 800     | 34       | 2.2%    |
| 2666    | 30       | 1.95%   |
| 3466    | 27       | 1.75%   |
| 3400    | 22       | 1.43%   |
| 2933    | 22       | 1.43%   |
| 667     | 22       | 1.43%   |
| 3800    | 20       | 1.3%    |
| 1800    | 20       | 1.3%    |
| 4800    | 18       | 1.17%   |
| 1066    | 17       | 1.1%    |
| 3733    | 15       | 0.97%   |
| 1866    | 15       | 0.97%   |
| 3266    | 10       | 0.65%   |
| 3534    | 9        | 0.58%   |
| 1067    | 9        | 0.58%   |
| Unknown | 9        | 0.58%   |
| 3666    | 8        | 0.52%   |
| 2000    | 7        | 0.45%   |
| 400     | 7        | 0.45%   |
| 5600    | 6        | 0.39%   |
| 3866    | 6        | 0.39%   |
| 3500    | 6        | 0.39%   |
| 2800    | 6        | 0.39%   |
| 5200    | 5        | 0.32%   |
| 3334    | 5        | 0.32%   |
| 6400    | 4        | 0.26%   |
| 5808    | 4        | 0.26%   |
| 3933    | 4        | 0.26%   |
| 2733    | 4        | 0.26%   |
| 2472    | 4        | 0.26%   |
| 2465    | 4        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 49       | 31.01%  |
| Brother Industries    | 35       | 22.15%  |
| Canon                 | 21       | 13.29%  |
| Samsung Electronics   | 18       | 11.39%  |
| Seiko Epson           | 17       | 10.76%  |
| Prolific Technology   | 3        | 1.9%    |
| Lexmark International | 3        | 1.9%    |
| Dymo-CoStar           | 3        | 1.9%    |
| STMicroelectronics    | 2        | 1.27%   |
| QinHeng Electronics   | 2        | 1.27%   |
| Zebra                 | 1        | 0.63%   |
| Pantum                | 1        | 0.63%   |
| Oki Data              | 1        | 0.63%   |
| BESTEASY              | 1        | 0.63%   |
| Apple                 | 1        | 0.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Seiko Epson ET-2720 Series                                | 3        | 1.85%   |
| Samsung Composite Device                                  | 3        | 1.85%   |
| Prolific PL2305 Parallel Port                             | 3        | 1.85%   |
| HP OfficeJet 3830 series                                  | 3        | 1.85%   |
| HP DeskJet 2130 series                                    | 3        | 1.85%   |
| Brother Printer                                           | 3        | 1.85%   |
| Brother HL-1440 Laser Printer                             | 3        | 1.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 1.23%   |
| Seiko Epson XP-2100 Series                                | 2        | 1.23%   |
| Seiko Epson L222 Series                                   | 2        | 1.23%   |
| Seiko Epson ET-2810 Series                                | 2        | 1.23%   |
| Samsung M2070 Series                                      | 2        | 1.23%   |
| Samsung C460 Series                                       | 2        | 1.23%   |
| QinHeng CH340S                                            | 2        | 1.23%   |
| HP OfficeJet Pro 8020 series                              | 2        | 1.23%   |
| HP LaserJet P1005                                         | 2        | 1.23%   |
| HP LaserJet M14-M17                                       | 2        | 1.23%   |
| HP LaserJet 4250                                          | 2        | 1.23%   |
| HP DeskJet 4100 series                                    | 2        | 1.23%   |
| HP DeskJet 2300 series                                    | 2        | 1.23%   |
| HP DeskJet 1110 series                                    | 2        | 1.23%   |
| Dymo-CoStar LabelWriter 400                               | 2        | 1.23%   |
| Canon TS3100 series                                       | 2        | 1.23%   |
| Canon LBP2900                                             | 2        | 1.23%   |
| Brother HL-L2375DW series                                 | 2        | 1.23%   |
| Brother HL-L2350DW series                                 | 2        | 1.23%   |
| Brother HL-2270DW Laser Printer                           | 2        | 1.23%   |
| Brother DCP-J105                                          | 2        | 1.23%   |
| Brother DCP-7055 scanner/printer                          | 2        | 1.23%   |
| Zebra ZP 450 Printer                                      | 1        | 0.62%   |
| Seiko Epson WF-3520 Series                                | 1        | 0.62%   |
| Seiko Epson WF-2840 Series                                | 1        | 0.62%   |
| Seiko Epson WF-2510 Series                                | 1        | 0.62%   |
| Seiko Epson L4260 Series                                  | 1        | 0.62%   |
| Seiko Epson L396 Series                                   | 1        | 0.62%   |
| Seiko Epson L3150 Series                                  | 1        | 0.62%   |
| Seiko Epson L3110 Series                                  | 1        | 0.62%   |
| Seiko Epson L310 Series                                   | 1        | 0.62%   |
| Seiko Epson ET-8550 Series                                | 1        | 0.62%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1        | 0.62%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 16       | 61.54%  |
| Hewlett-Packard             | 5        | 19.23%  |
| Seiko Epson                 | 4        | 15.38%  |
| Acer Peripherals (now BenQ) | 1        | 3.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                             | 4        | 15.38%  |
| Canon CanoScan LiDE 100                             | 3        | 11.54%  |
| Canon CanoScan LiDE 110                             | 2        | 7.69%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1        | 3.85%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1        | 3.85%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]  | 1        | 3.85%   |
| Seiko Epson GT-7700U [Perfection 1240U]             | 1        | 3.85%   |
| HP Scanjet N6010                                    | 1        | 3.85%   |
| HP ScanJet G4010                                    | 1        | 3.85%   |
| HP ScanJet 4850C/4890C                              | 1        | 3.85%   |
| HP ScanJet 3970c                                    | 1        | 3.85%   |
| HP ScanJet 3400cse                                  | 1        | 3.85%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1        | 3.85%   |
| Canon CanoScan N1240U/LiDE 30                       | 1        | 3.85%   |
| Canon CanoScan LIDE 25                              | 1        | 3.85%   |
| Canon CanoScan LiDE 220                             | 1        | 3.85%   |
| Canon CanoScan LiDE 200                             | 1        | 3.85%   |
| Canon CanoScan 9000F Mark II                        | 1        | 3.85%   |
| Canon CanoScan 4200F                                | 1        | 3.85%   |
| Acer Peripherals (now BenQ) Benq 5000               | 1        | 3.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 208      | 36.49%  |
| Microdia                      | 48       | 8.42%   |
| Microsoft                     | 43       | 7.54%   |
| Sunplus Innovation Technology | 26       | 4.56%   |
| Apple                         | 22       | 3.86%   |
| Samsung Electronics           | 17       | 2.98%   |
| Z-Star Microelectronics       | 15       | 2.63%   |
| Realtek Semiconductor         | 15       | 2.63%   |
| Generalplus Technology        | 14       | 2.46%   |
| ARC International             | 13       | 2.28%   |
| Chicony Electronics           | 11       | 1.93%   |
| Creative Technology           | 8        | 1.4%    |
| 2M UVC CAMERA                 | 7        | 1.23%   |
| Trust                         | 6        | 1.05%   |
| Razer USA                     | 6        | 1.05%   |
| GEMBIRD                       | 6        | 1.05%   |
| MacroSilicon                  | 5        | 0.88%   |
| Cubeternet                    | 5        | 0.88%   |
| Sonix Technology              | 4        | 0.7%    |
| Hewlett-Packard               | 4        | 0.7%    |
| AVerMedia Technologies        | 4        | 0.7%    |
| YGTek                         | 3        | 0.53%   |
| WaveRider Communications      | 3        | 0.53%   |
| Philips (or NXP)              | 3        | 0.53%   |
| KYE Systems (Mouse Systems)   | 3        | 0.53%   |
| IMC Networks                  | 3        | 0.53%   |
| Asuscom Network               | 3        | 0.53%   |
| Alcor Micro                   | 3        | 0.53%   |
| Sunplus IT                    | 2        | 0.35%   |
| Quanta                        | 2        | 0.35%   |
| Pixart Imaging                | 2        | 0.35%   |
| OPPO Electronics              | 2        | 0.35%   |
| Linux Foundation              | 2        | 0.35%   |
| Jieli Technology              | 2        | 0.35%   |
| Huawei Technologies           | 2        | 0.35%   |
| GenesysLogic Technology       | 2        | 0.35%   |
| Genesys Logic                 | 2        | 0.35%   |
| Aveo Technology               | 2        | 0.35%   |
| Arkmicro Technologies         | 2        | 0.35%   |
| Xiongmai                      | 1        | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 47       | 8.23%   |
| Logitech HD Pro Webcam C920                | 33       | 5.78%   |
| Logitech C922 Pro Stream Webcam            | 22       | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X            | 20       | 3.5%    |
| Samsung Galaxy series, misc. (MTP mode)    | 17       | 2.98%   |
| Microdia Webcam Vitade AF                  | 16       | 2.8%    |
| ARC International Camera                   | 13       | 2.28%   |
| Microsoft LifeCam HD-3000                  | 12       | 2.1%    |
| Logitech HD Webcam C615                    | 12       | 2.1%    |
| Logitech C920 PRO HD Webcam                | 12       | 2.1%    |
| Microdia USB 2.0 Camera                    | 9        | 1.58%   |
| Sunplus FHD Camera Microphone              | 8        | 1.4%    |
| Microsoft LifeCam Cinema                   | 8        | 1.4%    |
| Logitech Webcam C170                       | 8        | 1.4%    |
| Logitech HD Webcam C525                    | 8        | 1.4%    |
| Sunplus Canyon CNS-CWC5 Webcam             | 7        | 1.23%   |
| Microdia Camera                            | 7        | 1.23%   |
| Logitech Webcam C310                       | 7        | 1.23%   |
| Generalplus GENERAL WEBCAM                 | 7        | 1.23%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam        | 7        | 1.23%   |
| Microdia Sonix USB 2.0 Camera              | 6        | 1.05%   |
| GEMBIRD USB2.0 PC CAMERA                   | 6        | 1.05%   |
| Z-Star Venus USB2.0 Camera                 | 5        | 0.88%   |
| Realtek USB Camera                         | 5        | 0.88%   |
| Realtek Full HD webcam                     | 5        | 0.88%   |
| Logitech Webcam C925e                      | 5        | 0.88%   |
| Logitech BRIO Ultra HD Webcam              | 5        | 0.88%   |
| Razer USA Gaming Webcam [Kiyo]             | 4        | 0.7%    |
| MacroSilicon USB Video                     | 4        | 0.7%    |
| Logitech QuickCam Pro 9000                 | 4        | 0.7%    |
| Generalplus WEB CAM                        | 4        | 0.7%    |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 4        | 0.7%    |
| Z-Star Lenovo USB 2.0 UVC Camera           | 3        | 0.53%   |
| YGTek Webcam                               | 3        | 0.53%   |
| WaveRider USB 2.0 Camera                   | 3        | 0.53%   |
| Microsoft LifeCam VX-500 [1357]            | 3        | 0.53%   |
| Microsoft LifeCam Studio                   | 3        | 0.53%   |
| Microsoft LifeCam HD-5000                  | 3        | 0.53%   |
| Microdia PC-LM1E                           | 3        | 0.53%   |
| Microdia Integrated Camera                 | 3        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Dell                  | 2        | 50%     |
| Microsoft             | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 50%     |
| Microsoft Fingerprint Reader                   | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 7        | 24.14%  |
| Realtek Semiconductor     | 4        | 13.79%  |
| SCM Microsystems          | 3        | 10.34%  |
| Gemalto (was Gemplus)     | 3        | 10.34%  |
| Chicony Electronics       | 3        | 10.34%  |
| Alcor Micro               | 3        | 10.34%  |
| Reiner SCT Kartensysteme  | 1        | 3.45%   |
| Lenovo                    | 1        | 3.45%   |
| Fujitsu Siemens Computers | 1        | 3.45%   |
| Cherry                    | 1        | 3.45%   |
| Bit4id                    | 1        | 3.45%   |
| Aladdin Knowledge Systems | 1        | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 13.79%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 10.34%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 10.34%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 10.34%  |
| Advanced Card Systems ACR38 SmartCard Reader                               | 3        | 10.34%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 2        | 6.9%    |
| Advanced Card Systems ACR122U                                              | 2        | 6.9%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 3.45%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 3.45%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.45%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 3.45%   |
| Bit4id miniLector EVO                                                      | 1        | 3.45%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 3.45%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 3.45%   |
| Advanced Card Systems ACR39U                                               | 1        | 3.45%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2546     | 82.64%  |
| 1     | 452      | 14.67%  |
| 2     | 48       | 1.56%   |
| 3     | 20       | 0.65%   |
| 5     | 8        | 0.26%   |
| 4     | 3        | 0.1%    |
| 8     | 2        | 0.06%   |
| 7     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 233      | 36.46%  |
| Net/wireless             | 143      | 22.38%  |
| Unassigned class         | 67       | 10.49%  |
| Communication controller | 45       | 7.04%   |
| Sound                    | 40       | 6.26%   |
| Chipcard                 | 19       | 2.97%   |
| Multimedia controller    | 14       | 2.19%   |
| Camera                   | 13       | 2.03%   |
| Bluetooth                | 13       | 2.03%   |
| Net/ethernet             | 12       | 1.88%   |
| Storage/raid             | 11       | 1.72%   |
| Network                  | 7        | 1.1%    |
| Card reader              | 4        | 0.63%   |
| Storage/nvme             | 3        | 0.47%   |
| Storage/ata              | 3        | 0.47%   |
| Modem                    | 3        | 0.47%   |
| Dvb card                 | 3        | 0.47%   |
| Tv card                  | 2        | 0.31%   |
| Fingerprint reader       | 2        | 0.31%   |
| Wireless                 | 1        | 0.16%   |
| Firewire controller      | 1        | 0.16%   |


Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 2172

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M2V                         | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| Dell          | 0FM586                      | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| HP            | 1998                        | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| Dell          | 0FM586                      | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| Gigabyte      | H410M H V3                  | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| ASUSTek       | Maximus VII HERO            | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| MSI           | MS-7309                     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| Gateway       | SX2851                      | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Unknown       | Unknown                     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| MSI           | 870A-G54                    | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| Unknown       | Unknown                     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Acer          | Aspire TC-280               | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| AZW           | Green G3                    | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| HP            | 82F1                        | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| MSI           | Z390-A PRO                  | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| AZW           | MINI S 10                   | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Intel         | H61                         | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| Intel         | H61                         | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| ECS           | H61H2-M2                    | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| JHZD          | BQM5                        | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | 0RW199                      | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| Intel         | H61                         | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| Gigabyte      | H510M H                     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| HP            | 1497                        | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | STI 001359                  | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| HP            | 21F5 0A                     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| HP            | 1998                        | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| MSI           | Boston                      | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| HP            | 2215                        | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| ASUSTek       | SABERTOOTH P67              | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| EPSON DIRE... | AT992E                      | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| ASUSTek       | P7H55-M LX                  | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| AMI           | Intel                       | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Unknown       | Unknown                     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| MSI           | G41M-P33 Combo              | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| Pegatron      | EVANS                       | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Intel         | X99                         | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Dell          | 0RW199                      | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Pegatron      | EVANS                       | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| MSI           | B85M-E45                    | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| Intel         | X79M-S                      | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Acer          | Predator G3610              | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| HP            | 2B35                        | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | 0Y5DDC A00                  | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Dell          | 0HN7XN A01                  | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | 0F3KHR A00                  | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| Biostar       | H61MLC                      | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| MSI           | B550-A PRO                  | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| ASUSTek       | CG8270                      | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| HP            | 8299                        | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| HP            | 0B54h D                     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Gigabyte      | Z97X-UD5H                   | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | X79M-S                      | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| HP            | 8054                        | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| Intel         | H61                         | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| GuoGuang      | IC2M1028N                   | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| MSI           | Z87 MPOWER MAX              | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| AZW           | MINI S                      | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| HP            | 8299                        | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| Unknown       | Unknown                     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Dell          | 0GY6Y8 A02                  | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| HP            | 3047h                       | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| HP            | 3032h                       | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| Intel         | X79M-S                      | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Biostar       | H410MH                      | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| MSI           | 2AE0                        | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Intel         | DZ68BC AAG30742-401         | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| Dell          | 0WMJ54 A01                  | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Unknown       | Unknown                     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | 89B5 A                      | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| ASUSTek       | M4N68T-M LE                 | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | M68MT-S2                    | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| MP            | MS-7848                     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Dell          | 088DT1 A01                  | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Dell          | 0MN1TX A04                  | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | 0C27VV A02                  | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| HP            | 8299                        | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Dell          | 0HN7XN A01                  | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| ASRock        | FP6D4-P1                    | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | 21F5 0A                     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Dell          | 0GY6Y8 A02                  | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| HP            | 2B47                        | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| MSI           | B85M-E45                    | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| HP            | 2B47                        | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | 0HN7XN A01                  | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| HP            | 8350                        | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| ASUSTek       | H87-PRO                     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| Dell          | 0T10XW A00                  | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Gigabyte      | B550 AORUS PRO              | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | 03KWTV A02                  | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| HP            | 2AF7                        | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Acer          | Aspire XC-780               | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | 2AF7                        | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | 2AF7                        | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| HP            | 2AF7                        | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASRock        | G31M-S                      | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Dell          | 0MGK50 A04                  | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | 8750                        | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Biostar       | A520MH                      | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| HP            | 82FE 11                     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Biostar       | TPower X58                  | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| AZW           | U59                         | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| HP            | 8433 11                     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| OEM           | H110 Ver:2.21               | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Gateway       | SX2851                      | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| BESSTAR Te... | HM90                        | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Dell          | 0HN7XN A01                  | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| HP            | 822A                        | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | 2AE0                        | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| HP            | 0AA4h                       | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 73       | 4.52%   |
| 5.11.0-38-generic | 62       | 3.84%   |
| 5.15.0-67-generic | 58       | 3.59%   |
| 5.15.0-69-generic | 56       | 3.47%   |
| 5.15.0-46-generic | 56       | 3.47%   |
| 5.11.0-27-generic | 56       | 3.47%   |
| 5.11.0-40-generic | 50       | 3.1%    |
| 5.15.0-52-generic | 49       | 3.04%   |
| 5.13.0-39-generic | 49       | 3.04%   |
| 5.15.0-78-generic | 46       | 2.85%   |
| 5.15.0-58-generic | 46       | 2.85%   |
| 5.15.0-60-generic | 45       | 2.79%   |
| 5.15.0-48-generic | 41       | 2.54%   |
| 5.11.0-41-generic | 41       | 2.54%   |
| 5.15.0-71-generic | 40       | 2.48%   |
| 5.13.0-30-generic | 40       | 2.48%   |
| 5.13.0-40-generic | 38       | 2.35%   |
| 5.15.0-76-generic | 37       | 2.29%   |
| 5.11.0-43-generic | 36       | 2.23%   |
| 5.15.0-41-generic | 35       | 2.17%   |
| 5.11.0-37-generic | 35       | 2.17%   |
| 5.15.0-84-generic | 34       | 2.11%   |
| 5.13.0-28-generic | 31       | 1.92%   |
| 5.11.0-34-generic | 31       | 1.92%   |
| 5.15.0-88-generic | 29       | 1.8%    |
| 5.15.0-53-generic | 29       | 1.8%    |
| 5.13.0-35-generic | 28       | 1.73%   |
| 5.15.0-73-generic | 27       | 1.67%   |
| 5.13.0-27-generic | 26       | 1.61%   |
| 5.13.0-41-generic | 25       | 1.55%   |
| 5.15.0-89-generic | 24       | 1.49%   |
| 5.15.0-83-generic | 24       | 1.49%   |
| 5.13.0-52-generic | 24       | 1.49%   |
| 5.15.0-72-generic | 23       | 1.43%   |
| 5.13.0-44-generic | 21       | 1.3%    |
| 5.15.0-87-generic | 20       | 1.24%   |
| 5.15.0-79-generic | 19       | 1.18%   |
| 5.13.0-51-generic | 17       | 1.05%   |
| 5.15.0-91-generic | 16       | 0.99%   |
| 5.15.0-86-generic | 16       | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 776      | 53.67%  |
| 5.11.0  | 334      | 23.1%   |
| 5.13.0  | 293      | 20.26%  |
| 5.8.0   | 25       | 1.73%   |
| 5.4.0   | 2        | 0.14%   |
| 6.5.7   | 1        | 0.07%   |
| 6.3.2   | 1        | 0.07%   |
| 6.3.0   | 1        | 0.07%   |
| 6.2.7   | 1        | 0.07%   |
| 6.2.16  | 1        | 0.07%   |
| 6.1.8   | 1        | 0.07%   |
| 6.1.7   | 1        | 0.07%   |
| 6.0.8   | 1        | 0.07%   |
| 5.19.6  | 1        | 0.07%   |
| 5.19.2  | 1        | 0.07%   |
| 5.19.12 | 1        | 0.07%   |
| 5.17.9  | 1        | 0.07%   |
| 5.17.5  | 1        | 0.07%   |
| 5.17.1  | 1        | 0.07%   |
| 5.15.13 | 1        | 0.07%   |
| 5.14.0  | 1        | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 777      | 53.77%  |
| 5.11    | 334      | 23.11%  |
| 5.13    | 293      | 20.28%  |
| 5.8     | 25       | 1.73%   |
| 5.19    | 3        | 0.21%   |
| 5.17    | 3        | 0.21%   |
| 6.3     | 2        | 0.14%   |
| 6.2     | 2        | 0.14%   |
| 5.4     | 2        | 0.14%   |
| 6.5     | 1        | 0.07%   |
| 6.1     | 1        | 0.07%   |
| 6.0     | 1        | 0.07%   |
| 5.14    | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1389     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1207     | 86.34%  |
| XFCE       | 179      | 12.8%   |
| Unknown    | 6        | 0.43%   |
| KDE5       | 2        | 0.14%   |
| Cinnamon   | 2        | 0.14%   |
| X-Cinnamon | 1        | 0.07%   |
| MATE       | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1378     | 98.92%  |
| Wayland | 13       | 0.93%   |
| Tty     | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1164     | 82.85%  |
| GDM     | 104      | 7.4%    |
| GDM3    | 100      | 7.12%   |
| LightDM | 36       | 2.56%   |
| TDM     | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 560      | 40.2%   |
| de_DE       | 144      | 10.34%  |
| en_GB       | 96       | 6.89%   |
| pt_BR       | 94       | 6.75%   |
| fr_FR       | 48       | 3.45%   |
| en_CA       | 42       | 3.02%   |
| it_IT       | 37       | 2.66%   |
| pl_PL       | 30       | 2.15%   |
| es_ES       | 30       | 2.15%   |
| en_IN       | 28       | 2.01%   |
| en_AU       | 27       | 1.94%   |
| nl_NL       | 23       | 1.65%   |
| ru_RU       | 18       | 1.29%   |
| es_AR       | 18       | 1.29%   |
| hu_HU       | 15       | 1.08%   |
| es_MX       | 14       | 1.01%   |
| en_ZA       | 14       | 1.01%   |
| cs_CZ       | 10       | 0.72%   |
| pt_PT       | 9        | 0.65%   |
| nl_BE       | 8        | 0.57%   |
| fr_CA       | 8        | 0.57%   |
| tr_TR       | 6        | 0.43%   |
| sv_SE       | 6        | 0.43%   |
| nb_NO       | 6        | 0.43%   |
| fi_FI       | 6        | 0.43%   |
| es_CL       | 6        | 0.43%   |
| en_NZ       | 6        | 0.43%   |
| sk_SK       | 5        | 0.36%   |
| ja_JP       | 5        | 0.36%   |
| es_VE       | 5        | 0.36%   |
| el_GR       | 5        | 0.36%   |
| da_DK       | 5        | 0.36%   |
| en_PH       | 4        | 0.29%   |
| de_CH       | 4        | 0.29%   |
| sl_SI       | 3        | 0.22%   |
| ar_EG       | 3        | 0.22%   |
| zh_CN       | 2        | 0.14%   |
| sr_RS@latin | 2        | 0.14%   |
| sr_RS       | 2        | 0.14%   |
| fr_BE       | 2        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 734      | 52.35%  |
| EFI  | 668      | 47.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1293     | 92.62%  |
| Zfs      | 29       | 2.08%   |
| Tmpfs    | 29       | 2.08%   |
| Overlay  | 20       | 1.43%   |
| Btrfs    | 13       | 0.93%   |
| Xfs      | 5        | 0.36%   |
| Ext3     | 3        | 0.21%   |
| Ext2     | 3        | 0.21%   |
| Reiserfs | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1216     | 86.61%  |
| GPT     | 123      | 8.76%   |
| MBR     | 65       | 4.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1347     | 96.77%  |
| Yes       | 45       | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1256     | 90.17%  |
| Yes       | 137      | 9.83%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 322      | 23.18%  |
| Gigabyte Technology | 216      | 15.55%  |
| MSI                 | 148      | 10.66%  |
| Dell                | 148      | 10.66%  |
| Hewlett-Packard     | 136      | 9.79%   |
| ASRock              | 91       | 6.55%   |
| Lenovo              | 63       | 4.54%   |
| Intel               | 40       | 2.88%   |
| Acer                | 26       | 1.87%   |
| Unknown             | 24       | 1.73%   |
| Biostar             | 20       | 1.44%   |
| Pegatron            | 19       | 1.37%   |
| Fujitsu             | 17       | 1.22%   |
| Foxconn             | 15       | 1.08%   |
| AZW                 | 8        | 0.58%   |
| Positivo            | 5        | 0.36%   |
| ECS                 | 5        | 0.36%   |
| Apple               | 5        | 0.36%   |
| Alienware           | 5        | 0.36%   |
| OEM                 | 4        | 0.29%   |
| Google              | 4        | 0.29%   |
| BESSTAR Tech        | 4        | 0.29%   |
| Shuttle             | 3        | 0.22%   |
| Medion              | 3        | 0.22%   |
| Huanan              | 3        | 0.22%   |
| Gateway             | 3        | 0.22%   |
| eMachines           | 3        | 0.22%   |
| QIYIDA              | 2        | 0.14%   |
| PCWare              | 2        | 0.14%   |
| Packard Bell        | 2        | 0.14%   |
| MAXSUN              | 2        | 0.14%   |
| LORD ELECTRONICS    | 2        | 0.14%   |
| JGINYUE             | 2        | 0.14%   |
| Fujitsu Siemens     | 2        | 0.14%   |
| Wortmann AG         | 1        | 0.07%   |
| WIPRO               | 1        | 0.07%   |
| Win Element         | 1        | 0.07%   |
| Vorke               | 1        | 0.07%   |
| TYAN Computer       | 1        | 0.07%   |
| System76            | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 32       | 2.3%    |
| Unknown                          | 25       | 1.8%    |
| Dell OptiPlex 7010               | 13       | 0.94%   |
| MSI MS-7817                      | 9        | 0.65%   |
| Dell OptiPlex 790                | 8        | 0.58%   |
| Intel H61                        | 7        | 0.5%    |
| Dell OptiPlex 780                | 7        | 0.5%    |
| Dell OptiPlex 380                | 7        | 0.5%    |
| ASUS TUF Gaming X570-PLUS        | 7        | 0.5%    |
| ASUS M5A78L-M/USB3               | 7        | 0.5%    |
| MSI MS-7C02                      | 6        | 0.43%   |
| Gigabyte B450 AORUS M            | 6        | 0.43%   |
| Gigabyte A320M-S2H               | 6        | 0.43%   |
| Dell OptiPlex 3010               | 6        | 0.43%   |
| ASUS M5A97 R2.0                  | 6        | 0.43%   |
| MSI MS-7C37                      | 5        | 0.36%   |
| HP EliteDesk 800 G1 SFF          | 5        | 0.36%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.36%   |
| Dell Precision WorkStation T3500 | 5        | 0.36%   |
| Dell OptiPlex 990                | 5        | 0.36%   |
| Dell OptiPlex 3020               | 5        | 0.36%   |
| ASUS P8Z77-V LX                  | 5        | 0.36%   |
| ASRock B450 Pro4                 | 5        | 0.36%   |
| MSI MS-7B89                      | 4        | 0.29%   |
| MSI MS-7B86                      | 4        | 0.29%   |
| Intel X79M-S                     | 4        | 0.29%   |
| Intel H55                        | 4        | 0.29%   |
| HP ProDesk 600 G1 SFF            | 4        | 0.29%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.29%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.29%   |
| Gigabyte GA-78LMT-USB3 6.0       | 4        | 0.29%   |
| Gigabyte GA-78LMT-S2             | 4        | 0.29%   |
| Dell OptiPlex 9020               | 4        | 0.29%   |
| Dell OptiPlex 7050               | 4        | 0.29%   |
| Dell OptiPlex 7040               | 4        | 0.29%   |
| Dell OptiPlex 7020               | 4        | 0.29%   |
| Dell OptiPlex 360                | 4        | 0.29%   |
| Dell OptiPlex 3050               | 4        | 0.29%   |
| AZW MINI S                       | 4        | 0.29%   |
| ASUS ROG CROSSHAIR VIII HERO     | 4        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 94       | 6.77%   |
| ASUS PRIME             | 49       | 3.53%   |
| Lenovo ThinkCentre     | 42       | 3.02%   |
| ASUS ROG               | 42       | 3.02%   |
| HP Compaq              | 38       | 2.74%   |
| ASUS TUF               | 36       | 2.59%   |
| ASUS All               | 32       | 2.3%    |
| Unknown                | 25       | 1.8%    |
| HP EliteDesk           | 22       | 1.58%   |
| Dell Precision         | 18       | 1.3%    |
| Gigabyte B450          | 13       | 0.94%   |
| Fujitsu ESPRIMO        | 13       | 0.94%   |
| Dell Inspiron          | 13       | 0.94%   |
| Acer Aspire            | 13       | 0.94%   |
| HP ProDesk             | 12       | 0.86%   |
| HP Pavilion            | 11       | 0.79%   |
| ASUS M5A97             | 10       | 0.72%   |
| ASUS M5A78L-M          | 10       | 0.72%   |
| MSI MS-7817            | 9        | 0.65%   |
| Gigabyte X570          | 9        | 0.65%   |
| Lenovo IdeaCentre      | 8        | 0.58%   |
| Gigabyte B450M         | 8        | 0.58%   |
| ASRock B450            | 8        | 0.58%   |
| Intel H61              | 7        | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 7        | 0.5%    |
| Gigabyte A320M-S2H     | 7        | 0.5%    |
| Dell XPS               | 7        | 0.5%    |
| ASUS P8H61-M           | 7        | 0.5%    |
| ASRock B450M           | 7        | 0.5%    |
| MSI MS-7C02            | 6        | 0.43%   |
| ASUS P8Z77-V           | 6        | 0.43%   |
| MSI MS-7C37            | 5        | 0.36%   |
| Gigabyte B550M         | 5        | 0.36%   |
| Dell Vostro            | 5        | 0.36%   |
| ASRock 970             | 5        | 0.36%   |
| MSI MS-7B89            | 4        | 0.29%   |
| MSI MS-7B86            | 4        | 0.29%   |
| Intel X79M-S           | 4        | 0.29%   |
| Intel H55              | 4        | 0.29%   |
| Gigabyte Z390          | 4        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 136      | 9.79%   |
| 2012    | 127      | 9.14%   |
| 2018    | 123      | 8.86%   |
| 2011    | 116      | 8.35%   |
| 2014    | 108      | 7.78%   |
| 2020    | 94       | 6.77%   |
| 2019    | 94       | 6.77%   |
| 2021    | 83       | 5.98%   |
| 2010    | 83       | 5.98%   |
| 2017    | 82       | 5.9%    |
| 2009    | 65       | 4.68%   |
| 2008    | 61       | 4.39%   |
| 2016    | 55       | 3.96%   |
| 2015    | 46       | 3.31%   |
| 2022    | 43       | 3.1%    |
| 2007    | 32       | 2.3%    |
| 2023    | 17       | 1.22%   |
| 2006    | 15       | 1.08%   |
| 2005    | 6        | 0.43%   |
| Unknown | 3        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1389     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1305     | 93.62%  |
| Enabled  | 89       | 6.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1385     | 99.71%  |
| Yes  | 4        | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 351      | 24.93%  |
| 8.01-16.0       | 296      | 21.02%  |
| 4.01-8.0        | 234      | 16.62%  |
| 32.01-64.0      | 195      | 13.85%  |
| 3.01-4.0        | 195      | 13.85%  |
| 64.01-256.0     | 54       | 3.84%   |
| 24.01-32.0      | 36       | 2.56%   |
| 1.01-2.0        | 27       | 1.92%   |
| 2.01-3.0        | 17       | 1.21%   |
| 0.51-1.0        | 2        | 0.14%   |
| More than 256.0 | 1        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 533      | 35.14%  |
| 2.01-3.0   | 472      | 31.11%  |
| 4.01-8.0   | 220      | 14.5%   |
| 3.01-4.0   | 220      | 14.5%   |
| 8.01-16.0  | 41       | 2.7%    |
| 0.51-1.0   | 20       | 1.32%   |
| 16.01-24.0 | 7        | 0.46%   |
| 32.01-64.0 | 2        | 0.13%   |
| 24.01-32.0 | 1        | 0.07%   |
| 0.01-0.5   | 1        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 627      | 43.78%  |
| 2      | 413      | 28.84%  |
| 3      | 177      | 12.36%  |
| 4      | 103      | 7.19%   |
| 5      | 52       | 3.63%   |
| 6      | 32       | 2.23%   |
| 7      | 11       | 0.77%   |
| 8      | 8        | 0.56%   |
| 0      | 6        | 0.42%   |
| 51     | 1        | 0.07%   |
| 11     | 1        | 0.07%   |
| 9      | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 711      | 50.79%  |
| Yes       | 689      | 49.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1372     | 98.78%  |
| No        | 17       | 1.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 720      | 51.32%  |
| No        | 683      | 48.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 915      | 65.31%  |
| Yes       | 486      | 34.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 355      | 25.47%  |
| Germany      | 153      | 10.98%  |
| Brazil       | 102      | 7.32%   |
| UK           | 93       | 6.67%   |
| Canada       | 54       | 3.87%   |
| Italy        | 46       | 3.3%    |
| France       | 43       | 3.08%   |
| Netherlands  | 39       | 2.8%    |
| Poland       | 35       | 2.51%   |
| Spain        | 31       | 2.22%   |
| India        | 29       | 2.08%   |
| Australia    | 28       | 2.01%   |
| Argentina    | 21       | 1.51%   |
| Hungary      | 19       | 1.36%   |
| Mexico       | 18       | 1.29%   |
| Belgium      | 17       | 1.22%   |
| Russia       | 15       | 1.08%   |
| Denmark      | 15       | 1.08%   |
| South Africa | 14       | 1%      |
| Sweden       | 13       | 0.93%   |
| Portugal     | 12       | 0.86%   |
| Norway       | 12       | 0.86%   |
| Greece       | 12       | 0.86%   |
| Czechia      | 12       | 0.86%   |
| Switzerland  | 10       | 0.72%   |
| Serbia       | 10       | 0.72%   |
| Turkey       | 9        | 0.65%   |
| Finland      | 9        | 0.65%   |
| Egypt        | 9        | 0.65%   |
| Chile        | 9        | 0.65%   |
| Malaysia     | 8        | 0.57%   |
| Venezuela    | 7        | 0.5%    |
| Slovakia     | 7        | 0.5%    |
| New Zealand  | 7        | 0.5%    |
| Slovenia     | 6        | 0.43%   |
| Romania      | 6        | 0.43%   |
| Japan        | 6        | 0.43%   |
| Indonesia    | 5        | 0.36%   |
| Bulgaria     | 5        | 0.36%   |
| Philippines  | 4        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 13       | 0.9%    |
| Rio de Janeiro | 12       | 0.83%   |
| Munich         | 10       | 0.69%   |
| Houston        | 8        | 0.55%   |
| Cape Town      | 8        | 0.55%   |
| Sao Paulo      | 7        | 0.48%   |
| Milan          | 7        | 0.48%   |
| Athens         | 7        | 0.48%   |
| Rome           | 6        | 0.41%   |
| Phoenix        | 6        | 0.41%   |
| Hamburg        | 6        | 0.41%   |
| Denver         | 6        | 0.41%   |
| Copenhagen     | 6        | 0.41%   |
| Sydney         | 5        | 0.34%   |
| Portland       | 5        | 0.34%   |
| Perth          | 5        | 0.34%   |
| Montreal       | 5        | 0.34%   |
| Dallas         | 5        | 0.34%   |
| Calgary        | 5        | 0.34%   |
| Buenos Aires   | 5        | 0.34%   |
| Adelaide       | 5        | 0.34%   |
| The Hague      | 4        | 0.28%   |
| Santiago       | 4        | 0.28%   |
| Salt Lake City | 4        | 0.28%   |
| Richmond       | 4        | 0.28%   |
| Prague         | 4        | 0.28%   |
| Melbourne      | 4        | 0.28%   |
| Johannesburg   | 4        | 0.28%   |
| Dayton         | 4        | 0.28%   |
| Budapest       | 4        | 0.28%   |
| Brussels       | 4        | 0.28%   |
| Brasília      | 4        | 0.28%   |
| Bengaluru      | 4        | 0.28%   |
| Belgrade       | 4        | 0.28%   |
| Atlanta        | 4        | 0.28%   |
| Zurich         | 3        | 0.21%   |
| Warsaw         | 3        | 0.21%   |
| Vienna         | 3        | 0.21%   |
| Toronto        | 3        | 0.21%   |
| Tijuana        | 3        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 473      | 738    | 19.04%  |
| WDC                         | 411      | 607    | 16.55%  |
| Samsung Electronics         | 317      | 491    | 12.76%  |
| Kingston                    | 155      | 227    | 6.24%   |
| SanDisk                     | 134      | 183    | 5.39%   |
| Toshiba                     | 130      | 199    | 5.23%   |
| Hitachi                     | 102      | 128    | 4.11%   |
| Crucial                     | 102      | 123    | 4.11%   |
| China                       | 42       | 47     | 1.69%   |
| A-DATA Technology           | 33       | 43     | 1.33%   |
| Unknown                     | 30       | 49     | 1.21%   |
| Silicon Motion              | 26       | 36     | 1.05%   |
| Intel                       | 25       | 30     | 1.01%   |
| PNY                         | 21       | 29     | 0.85%   |
| SK hynix                    | 20       | 25     | 0.81%   |
| Phison                      | 20       | 22     | 0.81%   |
| Intenso                     | 19       | 21     | 0.76%   |
| HGST                        | 19       | 27     | 0.76%   |
| Micron/Crucial Technology   | 17       | 20     | 0.68%   |
| Patriot                     | 15       | 21     | 0.6%    |
| SPCC                        | 14       | 21     | 0.56%   |
| Micron Technology           | 13       | 13     | 0.52%   |
| Maxtor                      | 13       | 17     | 0.52%   |
| GOODRAM                     | 13       | 16     | 0.52%   |
| Lexar                       | 12       | 12     | 0.48%   |
| Unknown                     | 12       | 13     | 0.48%   |
| Phison Electronics          | 11       | 14     | 0.44%   |
| OCZ                         | 11       | 13     | 0.44%   |
| JMicron Technology          | 11       | 13     | 0.44%   |
| Realtek Semiconductor       | 10       | 10     | 0.4%    |
| MAXIO Technology (Hangzhou) | 10       | 10     | 0.4%    |
| KingSpec                    | 10       | 13     | 0.4%    |
| Hewlett-Packard             | 10       | 14     | 0.4%    |
| Gigabyte Technology         | 9        | 11     | 0.36%   |
| Apple                       | 9        | 10     | 0.36%   |
| Netac                       | 8        | 12     | 0.32%   |
| Kingston Technology Company | 8        | 11     | 0.32%   |
| Apacer                      | 8        | 11     | 0.32%   |
| XPG                         | 7        | 8      | 0.28%   |
| Team                        | 7        | 9      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 48       | 1.68%   |
| Kingston SA400S37240G 240GB SSD                       | 42       | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB                        | 29       | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 25       | 0.88%   |
| Samsung SSD 860 EVO 500GB                             | 24       | 0.84%   |
| Crucial CT240BX500SSD1 240GB                          | 24       | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB                        | 22       | 0.77%   |
| Samsung SSD 850 EVO 250GB                             | 21       | 0.74%   |
| Kingston SA400S37120G 120GB SSD                       | 21       | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 20       | 0.7%    |
| Toshiba HDWD110 1TB                                   | 18       | 0.63%   |
| Samsung NVMe SSD Drive 1TB                            | 17       | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 17       | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB                        | 16       | 0.56%   |
| Seagate ST3500418AS 500GB                             | 15       | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                        | 15       | 0.53%   |
| Toshiba DT01ACA100 1TB                                | 14       | 0.49%   |
| Samsung NVMe SSD Drive 500GB                          | 14       | 0.49%   |
| Kingston SV300S37A120G 120GB SSD                      | 14       | 0.49%   |
| Unknown SD/MMC/MS PRO 128GB                           | 13       | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB                        | 13       | 0.46%   |
| Seagate ST3500413AS 500GB                             | 13       | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                        | 13       | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 13       | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                           | 13       | 0.46%   |
| Toshiba DT01ACA050 500GB                              | 12       | 0.42%   |
| Seagate ST3500312CS 500GB                             | 12       | 0.42%   |
| Seagate ST1000DM003-1SB102 1TB                        | 12       | 0.42%   |
| SanDisk NVMe SSD Drive 1TB                            | 12       | 0.42%   |
| Samsung SSD 870 EVO 1TB                               | 12       | 0.42%   |
| Crucial CT500MX500SSD1 500GB                          | 12       | 0.42%   |
| Unknown                                               | 12       | 0.42%   |
| SanDisk NVMe SSD Drive 500GB                          | 11       | 0.39%   |
| Samsung SSD 850 EVO 500GB                             | 11       | 0.39%   |
| Seagate ST31000528AS 1TB                              | 10       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB                        | 10       | 0.35%   |
| SanDisk SSD PLUS 240GB                                | 10       | 0.35%   |
| Samsung HD103SJ 1TB                                   | 10       | 0.35%   |
| Toshiba DT01ACA200 2TB                                | 9        | 0.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 9        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 467      | 718    | 39.21%  |
| WDC                 | 375      | 540    | 31.49%  |
| Toshiba             | 113      | 179    | 9.49%   |
| Hitachi             | 102      | 128    | 8.56%   |
| Samsung Electronics | 68       | 88     | 5.71%   |
| HGST                | 19       | 27     | 1.6%    |
| Unknown             | 14       | 18     | 1.18%   |
| Maxtor              | 13       | 17     | 1.09%   |
| Apple               | 6        | 7      | 0.5%    |
| Hewlett-Packard     | 4        | 7      | 0.34%   |
| USB3.0              | 3        | 4      | 0.25%   |
| WD MediaMax         | 1        | 1      | 0.08%   |
| TDAS                | 1        | 3      | 0.08%   |
| QUANTUM             | 1        | 1      | 0.08%   |
| Intenso             | 1        | 1      | 0.08%   |
| HGST HTS            | 1        | 1      | 0.08%   |
| External            | 1        | 1      | 0.08%   |
| ACASIS              | 1        | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 168      | 243    | 18.79%  |
| Kingston            | 130      | 177    | 14.54%  |
| Crucial             | 97       | 118    | 10.85%  |
| SanDisk             | 81       | 108    | 9.06%   |
| WDC                 | 44       | 57     | 4.92%   |
| China               | 42       | 47     | 4.7%    |
| A-DATA Technology   | 31       | 41     | 3.47%   |
| PNY                 | 21       | 29     | 2.35%   |
| Intel               | 15       | 17     | 1.68%   |
| SPCC                | 14       | 21     | 1.57%   |
| Patriot             | 14       | 20     | 1.57%   |
| Intenso             | 14       | 16     | 1.57%   |
| Lexar               | 12       | 12     | 1.34%   |
| GOODRAM             | 12       | 15     | 1.34%   |
| Toshiba             | 11       | 13     | 1.23%   |
| OCZ                 | 11       | 13     | 1.23%   |
| KingSpec            | 9        | 12     | 1.01%   |
| SK hynix            | 8        | 8      | 0.89%   |
| Netac               | 8        | 11     | 0.89%   |
| Micron Technology   | 8        | 8      | 0.89%   |
| JMicron Technology  | 8        | 9      | 0.89%   |
| Apacer              | 8        | 11     | 0.89%   |
| Team                | 7        | 9      | 0.78%   |
| Gigabyte Technology | 7        | 8      | 0.78%   |
| Hewlett-Packard     | 6        | 7      | 0.67%   |
| Transcend           | 5        | 5      | 0.56%   |
| Leven               | 5        | 6      | 0.56%   |
| Unknown             | 5        | 6      | 0.56%   |
| Super Talent        | 4        | 5      | 0.45%   |
| Verbatim            | 3        | 3      | 0.34%   |
| Seagate             | 3        | 6      | 0.34%   |
| LITEON              | 3        | 3      | 0.34%   |
| KIOXIA-EXCERIA      | 3        | 7      | 0.34%   |
| Fanxiang            | 3        | 3      | 0.34%   |
| Corsair             | 3        | 8      | 0.34%   |
| Acer                | 3        | 5      | 0.34%   |
| Teclast             | 2        | 2      | 0.22%   |
| Plextor             | 2        | 3      | 0.22%   |
| Pioneer             | 2        | 2      | 0.22%   |
| ORTIAL              | 2        | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 923      | 1742   | 44.27%  |
| SSD     | 748      | 1172   | 35.88%  |
| NVMe    | 345      | 525    | 16.55%  |
| Unknown | 62       | 79     | 2.97%   |
| MMC     | 7        | 8      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1280     | 2839   | 73.78%  |
| NVMe | 341      | 516    | 19.65%  |
| SAS  | 107      | 163    | 6.17%   |
| MMC  | 7        | 8      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 957      | 1605   | 53.46%  |
| 0.51-1.0   | 496      | 766    | 27.71%  |
| 1.01-2.0   | 194      | 280    | 10.84%  |
| 3.01-4.0   | 59       | 124    | 3.3%    |
| 4.01-10.0  | 42       | 63     | 2.35%   |
| 2.01-3.0   | 34       | 48     | 1.9%    |
| 10.01-20.0 | 7        | 27     | 0.39%   |
| 20.01-50.0 | 1        | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 427      | 29.33%  |
| 251-500        | 334      | 22.94%  |
| 501-1000       | 233      | 16%     |
| 1001-2000      | 148      | 10.16%  |
| More than 3000 | 107      | 7.35%   |
| 51-100         | 77       | 5.29%   |
| 2001-3000      | 48       | 3.3%    |
| 21-50          | 32       | 2.2%    |
| 1-20           | 32       | 2.2%    |
| Unknown        | 18       | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 483      | 31.8%   |
| 21-50          | 401      | 26.4%   |
| 51-100         | 189      | 12.44%  |
| 101-250        | 144      | 9.48%   |
| 251-500        | 100      | 6.58%   |
| 501-1000       | 75       | 4.94%   |
| More than 3000 | 55       | 3.62%   |
| 1001-2000      | 40       | 2.63%   |
| Unknown        | 18       | 1.18%   |
| 2001-3000      | 14       | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB                 | 2        | 2      | 4%      |
| Seagate ST500DM002-1BD142 500GB          | 2        | 2      | 4%      |
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 4%      |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1      | 2%      |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 2%      |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 2%      |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 2%      |
| WDC WD20EZRX-22D8PB0 2TB                 | 1        | 1      | 2%      |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 2%      |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 2%      |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 2%      |
| WDC WD Green 2.5 1000GB                  | 1        | 1      | 2%      |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 2%      |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 2%      |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 2%      |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 2%      |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 2%      |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 2%      |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 2%      |
| Seagate ST9500420AS 500GB                | 1        | 1      | 2%      |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 2%      |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 2%      |
| Seagate ST3500514NS 500GB                | 1        | 1      | 2%      |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2%      |
| Seagate ST3500312CS 500GB                | 1        | 1      | 2%      |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2%      |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2%      |
| Seagate ST3250318AS 250GB                | 1        | 1      | 2%      |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 2%      |
| Seagate ST320LT009-9WC142 320GB          | 1        | 1      | 2%      |
| Seagate ST3160310CS 160GB                | 1        | 1      | 2%      |
| Seagate ST2000LM007-1R8174 2TB           | 1        | 1      | 2%      |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 2%      |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 2%      |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 2%      |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 2%      |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 2%      |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 2%      |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 2%      |
| Maxtor STM3320613AS 320GB                | 1        | 1      | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 38.78%  |
| WDC                 | 11       | 12     | 22.45%  |
| Toshiba             | 6        | 6      | 12.24%  |
| HGST                | 3        | 3      | 6.12%   |
| Kingston            | 2        | 2      | 4.08%   |
| A-DATA Technology   | 2        | 2      | 4.08%   |
| Silicon Motion      | 1        | 1      | 2.04%   |
| Samsung Electronics | 1        | 1      | 2.04%   |
| OCZ                 | 1        | 1      | 2.04%   |
| Maxtor              | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| China               | 1        | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 50%     |
| WDC                 | 9        | 10     | 23.68%  |
| Toshiba             | 5        | 5      | 13.16%  |
| HGST                | 3        | 3      | 7.89%   |
| Samsung Electronics | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 40     | 75.56%  |
| SSD  | 9        | 9      | 20%     |
| NVMe | 2        | 2      | 4.44%   |

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
| Detected | 1281     | 3164   | 88.34%  |
| Works    | 125      | 311    | 8.62%   |
| Malfunc  | 44       | 51     | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 909      | 47.84%  |
| AMD                            | 436      | 22.95%  |
| Samsung Electronics            | 112      | 5.89%   |
| Sandisk                        | 63       | 3.32%   |
| ASMedia Technology             | 55       | 2.89%   |
| Kingston Technology Company    | 39       | 2.05%   |
| JMicron Technology             | 39       | 2.05%   |
| Phison Electronics             | 33       | 1.74%   |
| Nvidia                         | 33       | 1.74%   |
| Silicon Motion                 | 28       | 1.47%   |
| Marvell Technology Group       | 28       | 1.47%   |
| Micron/Crucial Technology      | 22       | 1.16%   |
| ADATA Technology               | 12       | 0.63%   |
| SK hynix                       | 11       | 0.58%   |
| MAXIO Technology (Hangzhou)    | 11       | 0.58%   |
| Realtek Semiconductor          | 10       | 0.53%   |
| VIA Technologies               | 8        | 0.42%   |
| Seagate Technology             | 8        | 0.42%   |
| Silicon Image                  | 7        | 0.37%   |
| KIOXIA                         | 7        | 0.37%   |
| Toshiba America Info Systems   | 5        | 0.26%   |
| Micron Technology              | 5        | 0.26%   |
| Shenzhen Longsys Electronics   | 3        | 0.16%   |
| INNOGRIT                       | 3        | 0.16%   |
| Broadcom / LSI                 | 3        | 0.16%   |
| TenaFe                         | 1        | 0.05%   |
| Solid State Storage Technology | 1        | 0.05%   |
| OCZ Technology Group           | 1        | 0.05%   |
| Nextorage                      | 1        | 0.05%   |
| Netac Technology               | 1        | 0.05%   |
| Lite-On Technology             | 1        | 0.05%   |
| Integrated Technology Express  | 1        | 0.05%   |
| HighPoint Technologies         | 1        | 0.05%   |
| Beijing Starblaze Technology   | 1        | 0.05%   |
| Apple                          | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 237      | 9.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 141      | 5.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 88       | 3.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 86       | 3.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 80       | 3.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 76       | 3.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 68       | 2.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 62       | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 60       | 2.51%   |
| Intel SATA Controller [RAID mode]                                                       | 59       | 2.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 55       | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 52       | 2.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 51       | 2.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 49       | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 47       | 1.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 45       | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 36       | 1.51%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 35       | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 33       | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 32       | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 29       | 1.21%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 24       | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 23       | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 23       | 0.96%   |
| AMD FCH SATA Controller D                                                               | 21       | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 20       | 0.84%   |
| AMD 300 Series Chipset SATA Controller                                                  | 20       | 0.84%   |
| Phison E12 NVMe Controller                                                              | 18       | 0.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 18       | 0.75%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 16       | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 16       | 0.67%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 16       | 0.67%   |
| Nvidia MCP61 IDE                                                                        | 15       | 0.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 15       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 15       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 15       | 0.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 14       | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 14       | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 14       | 0.59%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 13       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1108     | 57.83%  |
| IDE  | 356      | 18.58%  |
| NVMe | 340      | 17.75%  |
| RAID | 103      | 5.38%   |
| SAS  | 6        | 0.31%   |
| SCSI | 3        | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 921      | 66.31%  |
| AMD    | 468      | 33.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 28       | 2.01%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 25       | 1.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 24       | 1.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 21       | 1.51%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 1.15%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 1.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 14       | 1%      |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 1%      |
| Intel Core i5-4460 CPU @ 3.20GHz            | 14       | 1%      |
| Intel Core i3-4160 CPU @ 3.60GHz            | 14       | 1%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 14       | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 14       | 1%      |
| Intel Core i7-2600 CPU @ 3.40GHz            | 13       | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 13       | 0.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 13       | 0.93%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 13       | 0.93%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 0.93%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 13       | 0.93%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.86%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11       | 0.79%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 0.79%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 11       | 0.79%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 11       | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.72%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 9        | 0.65%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 9        | 0.65%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 0.65%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 0.65%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 8        | 0.57%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 8        | 0.57%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 8        | 0.57%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 8        | 0.57%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 8        | 0.57%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 0.57%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 0.57%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 7        | 0.5%    |
| Intel Core i3-7100 CPU @ 3.90GHz            | 7        | 0.5%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 7        | 0.5%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 7        | 0.5%    |
| Intel Core i3 CPU 540 @ 3.07GHz             | 7        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 281      | 20.2%   |
| Intel Core i7           | 159      | 11.43%  |
| Intel Core i3           | 124      | 8.91%   |
| AMD Ryzen 5             | 118      | 8.48%   |
| Intel Xeon              | 71       | 5.1%    |
| AMD Ryzen 7             | 59       | 4.24%   |
| AMD FX                  | 53       | 3.81%   |
| Other                   | 48       | 3.45%   |
| Intel Core 2 Duo        | 45       | 3.24%   |
| AMD Ryzen 9             | 45       | 3.24%   |
| Intel Celeron           | 39       | 2.8%    |
| Intel Core 2 Quad       | 33       | 2.37%   |
| Intel Pentium Dual-Core | 32       | 2.3%    |
| Intel Pentium           | 28       | 2.01%   |
| AMD Athlon II X2        | 25       | 1.8%    |
| AMD Ryzen 3             | 23       | 1.65%   |
| Intel Pentium Dual      | 18       | 1.29%   |
| AMD Phenom II X4        | 18       | 1.29%   |
| AMD A8                  | 15       | 1.08%   |
| AMD A10                 | 15       | 1.08%   |
| AMD A6                  | 14       | 1.01%   |
| Intel Core i9           | 13       | 0.93%   |
| AMD Phenom II X6        | 11       | 0.79%   |
| AMD Athlon 64 X2        | 11       | 0.79%   |
| Intel Atom              | 9        | 0.65%   |
| Intel Core 2            | 8        | 0.58%   |
| Intel Pentium 4         | 7        | 0.5%    |
| AMD Athlon II X4        | 7        | 0.5%    |
| AMD Athlon              | 7        | 0.5%    |
| Intel Pentium Gold      | 5        | 0.36%   |
| AMD Athlon II X3        | 5        | 0.36%   |
| AMD A4                  | 5        | 0.36%   |
| AMD Phenom              | 4        | 0.29%   |
| AMD E1                  | 4        | 0.29%   |
| AMD Ryzen 5 PRO         | 3        | 0.22%   |
| AMD PRO A10             | 3        | 0.22%   |
| AMD GX                  | 3        | 0.22%   |
| Intel Pentium D         | 2        | 0.14%   |
| AMD Sempron             | 2        | 0.14%   |
| AMD E2                  | 2        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 574      | 41.24%  |
| 2      | 393      | 28.23%  |
| 6      | 190      | 13.65%  |
| 8      | 113      | 8.12%   |
| 12     | 35       | 2.51%   |
| 1      | 28       | 2.01%   |
| 16     | 21       | 1.51%   |
| 3      | 21       | 1.51%   |
| 10     | 12       | 0.86%   |
| 28     | 2        | 0.14%   |
| 14     | 2        | 0.14%   |
| 24     | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1379     | 99.28%  |
| 2      | 10       | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 742      | 53.38%  |
| 1      | 648      | 46.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1389     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 163      | 11.58%  |
| Unknown    | 109      | 7.75%   |
| 0x306a9    | 106      | 7.53%   |
| 0x206a7    | 95       | 6.75%   |
| 0x1067a    | 84       | 5.97%   |
| 0x506e3    | 58       | 4.12%   |
| 0x08701021 | 51       | 3.62%   |
| 0x06000852 | 37       | 2.63%   |
| 0x906ea    | 31       | 2.2%    |
| 0x906e9    | 28       | 1.99%   |
| 0x0800820d | 27       | 1.92%   |
| 0x010000c8 | 27       | 1.92%   |
| 0xa0655    | 23       | 1.63%   |
| 0xa0653    | 23       | 1.63%   |
| 0x6fd      | 21       | 1.49%   |
| 0x0a201016 | 19       | 1.35%   |
| 0x08108109 | 18       | 1.28%   |
| 0x06001119 | 18       | 1.28%   |
| 0x6fb      | 15       | 1.07%   |
| 0x0600063e | 15       | 1.07%   |
| 0xa0671    | 14       | 1%      |
| 0x906ed    | 14       | 1%      |
| 0x08001138 | 14       | 1%      |
| 0x906eb    | 13       | 0.92%   |
| 0x010000dc | 13       | 0.92%   |
| 0x20655    | 12       | 0.85%   |
| 0x010000db | 12       | 0.85%   |
| 0x0a50000d | 11       | 0.78%   |
| 0x08701013 | 11       | 0.78%   |
| 0x90672    | 10       | 0.71%   |
| 0x306e4    | 10       | 0.71%   |
| 0x206d7    | 10       | 0.71%   |
| 0x20652    | 10       | 0.71%   |
| 0x106e5    | 10       | 0.71%   |
| 0x06003106 | 10       | 0.71%   |
| 0x306f2    | 9        | 0.64%   |
| 0x106a5    | 9        | 0.64%   |
| 0x10676    | 9        | 0.64%   |
| 0x0a601203 | 9        | 0.64%   |
| 0x0a201009 | 8        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 187      | 13.44%  |
| IvyBridge        | 119      | 8.55%   |
| SandyBridge      | 111      | 7.98%   |
| KabyLake         | 100      | 7.19%   |
| Penryn           | 99       | 7.12%   |
| Zen 2            | 80       | 5.75%   |
| K10              | 72       | 5.18%   |
| Zen 3            | 67       | 4.82%   |
| Skylake          | 60       | 4.31%   |
| Piledriver       | 58       | 4.17%   |
| Core             | 49       | 3.52%   |
| CometLake        | 49       | 3.52%   |
| Zen+             | 48       | 3.45%   |
| Zen              | 43       | 3.09%   |
| Unknown          | 36       | 2.59%   |
| Westmere         | 29       | 2.08%   |
| Nehalem          | 24       | 1.73%   |
| K8 Hammer        | 17       | 1.22%   |
| Icelake          | 15       | 1.08%   |
| Excavator        | 15       | 1.08%   |
| Bulldozer        | 15       | 1.08%   |
| Alderlake Hybrid | 14       | 1.01%   |
| Silvermont       | 13       | 0.93%   |
| Steamroller      | 11       | 0.79%   |
| NetBurst         | 10       | 0.72%   |
| Puma             | 7        | 0.5%    |
| Jaguar           | 7        | 0.5%    |
| Bonnell          | 7        | 0.5%    |
| K10 Llano        | 6        | 0.43%   |
| Broadwell        | 6        | 0.43%   |
| Goldmont plus    | 5        | 0.36%   |
| Bobcat           | 5        | 0.36%   |
| Tremont          | 4        | 0.29%   |
| Goldmont         | 2        | 0.14%   |
| TigerLake        | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 546      | 36.64%  |
| Intel                      | 485      | 32.55%  |
| AMD                        | 454      | 30.47%  |
| VIA Technologies           | 2        | 0.13%   |
| Matrox Electronics Systems | 1        | 0.07%   |
| ATI Technologies           | 1        | 0.07%   |
| ASPEED Technology          | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 89       | 5.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 57       | 3.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 52       | 3.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 46       | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 35       | 2.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 34       | 2.24%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 32       | 2.11%   |
| Intel HD Graphics 530                                                       | 30       | 1.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 26       | 1.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 24       | 1.58%   |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 1.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 20       | 1.32%   |
| Intel HD Graphics 630                                                       | 19       | 1.25%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 19       | 1.25%   |
| Nvidia GF119 [GeForce GT 610]                                               | 18       | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                         | 18       | 1.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18       | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 16       | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 16       | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 16       | 1.05%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 14       | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 14       | 0.92%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14       | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 14       | 0.92%   |
| AMD RS780L [Radeon 3000]                                                    | 14       | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 13       | 0.86%   |
| Nvidia GF108 [GeForce GT 730]                                               | 12       | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 12       | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 11       | 0.72%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 11       | 0.72%   |
| AMD Raphael                                                                 | 11       | 0.72%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 11       | 0.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 10       | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 9        | 0.59%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 0.59%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 0.59%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 9        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 8        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 502      | 35.75%  |
| 1 x Intel            | 424      | 30.2%   |
| 1 x AMD              | 416      | 29.63%  |
| 2 x AMD              | 15       | 1.07%   |
| Intel + Nvidia       | 15       | 1.07%   |
| AMD + Nvidia         | 14       | 1%      |
| Intel + AMD          | 10       | 0.71%   |
| 2 x Nvidia           | 3        | 0.21%   |
| 1 x VIA              | 2        | 0.14%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.07%   |
| 1 x Matrox           | 1        | 0.07%   |
| 1 x ASPEED           | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 968      | 68.9%   |
| Proprietary | 351      | 24.98%  |
| Unknown     | 86       | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 616      | 43.41%  |
| 1.01-2.0   | 174      | 12.26%  |
| 0.51-1.0   | 164      | 11.56%  |
| 0.01-0.5   | 143      | 10.08%  |
| 3.01-4.0   | 116      | 8.17%   |
| 7.01-8.0   | 106      | 7.47%   |
| 8.01-16.0  | 41       | 2.89%   |
| 5.01-6.0   | 35       | 2.47%   |
| 2.01-3.0   | 20       | 1.41%   |
| 16.01-24.0 | 4        | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 215      | 15.74%  |
| Dell                 | 133      | 9.74%   |
| Goldstar             | 127      | 9.3%    |
| Hewlett-Packard      | 104      | 7.61%   |
| Acer                 | 91       | 6.66%   |
| AOC                  | 80       | 5.86%   |
| Philips              | 70       | 5.12%   |
| BenQ                 | 49       | 3.59%   |
| Ancor Communications | 49       | 3.59%   |
| LG Electronics       | 30       | 2.2%    |
| Lenovo               | 25       | 1.83%   |
| ViewSonic            | 24       | 1.76%   |
| Unknown              | 24       | 1.76%   |
| Unknown              | 22       | 1.61%   |
| Sony                 | 19       | 1.39%   |
| Iiyama               | 16       | 1.17%   |
| ASUSTek Computer     | 14       | 1.02%   |
| Fujitsu Siemens      | 13       | 0.95%   |
| Sceptre Tech         | 12       | 0.88%   |
| NEC Computers        | 12       | 0.88%   |
| Vizio                | 10       | 0.73%   |
| HPN                  | 10       | 0.73%   |
| Eizo                 | 10       | 0.73%   |
| Toshiba              | 8        | 0.59%   |
| MSI                  | 8        | 0.59%   |
| FUS                  | 7        | 0.51%   |
| Panasonic            | 6        | 0.44%   |
| Microstep            | 6        | 0.44%   |
| Idek Iiyama          | 6        | 0.44%   |
| AUS                  | 6        | 0.44%   |
| Vestel               | 5        | 0.37%   |
| Pixio                | 5        | 0.37%   |
| Unknown (XXX)        | 4        | 0.29%   |
| RTK                  | 4        | 0.29%   |
| Medion               | 4        | 0.29%   |
| Lenovo Group Limited | 4        | 0.29%   |
| ITE                  | 4        | 0.29%   |
| Gigabyte Technology  | 4        | 0.29%   |
| Envision             | 4        | 0.29%   |
| ___                  | 3        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 22       | 1.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 9        | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 9        | 0.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 7        | 0.48%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 5        | 0.34%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 5        | 0.34%   |
| Philips LCD Monitor FTV 1920x1080                                       | 5        | 0.34%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 5        | 0.34%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 4        | 0.28%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 4        | 0.28%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch               | 4        | 0.28%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 4        | 0.28%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 4        | 0.28%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 0.21%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 3        | 0.21%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 3        | 0.21%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch                | 3        | 0.21%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 3        | 0.21%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 3        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 3        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch   | 3        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3        | 0.21%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch                 | 3        | 0.21%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 3        | 0.21%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 3        | 0.21%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 3        | 0.21%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                      | 3        | 0.21%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                       | 3        | 0.21%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 3        | 0.21%   |
| Dell LCD Monitor E228WFP                                                | 3        | 0.21%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                       | 3        | 0.21%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                       | 3        | 0.21%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 3        | 0.21%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 3        | 0.21%   |
| ___ LCDTV16 ___9000 1360x768                                            | 2        | 0.14%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 2        | 0.14%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch               | 2        | 0.14%   |
| Vizio E320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                      | 2        | 0.14%   |
| Unknown LCD Monitor SAMSUNG                                             | 2        | 0.14%   |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                        | 2        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 568      | 42.07%  |
| 3840x2160 (4K)     | 115      | 8.52%   |
| 1680x1050 (WSXGA+) | 80       | 5.93%   |
| 1280x1024 (SXGA)   | 79       | 5.85%   |
| 2560x1440 (QHD)    | 65       | 4.81%   |
| 1600x900 (HD+)     | 62       | 4.59%   |
| Unknown            | 59       | 4.37%   |
| 1366x768 (WXGA)    | 57       | 4.22%   |
| 1440x900 (WXGA+)   | 50       | 3.7%    |
| 1360x768           | 32       | 2.37%   |
| 3440x1440          | 30       | 2.22%   |
| 3840x1080          | 29       | 2.15%   |
| 1920x1200 (WUXGA)  | 29       | 2.15%   |
| 2560x1080          | 17       | 1.26%   |
| 1920x540           | 11       | 0.81%   |
| 1024x768 (XGA)     | 9        | 0.67%   |
| 1600x1200          | 7        | 0.52%   |
| 3840x1600          | 4        | 0.3%    |
| 1280x720 (HD)      | 4        | 0.3%    |
| 4480x1440          | 3        | 0.22%   |
| 5760x2160          | 2        | 0.15%   |
| 5760x1080          | 2        | 0.15%   |
| 5120x1440          | 2        | 0.15%   |
| 4480x1080          | 2        | 0.15%   |
| 3600x1080          | 2        | 0.15%   |
| 3360x1080          | 2        | 0.15%   |
| 3200x1200          | 2        | 0.15%   |
| 3120x1050          | 2        | 0.15%   |
| 2944x1080          | 2        | 0.15%   |
| 2560x1600          | 2        | 0.15%   |
| 7680x2160          | 1        | 0.07%   |
| 6880x1440          | 1        | 0.07%   |
| 6400x1440          | 1        | 0.07%   |
| 5440x1080          | 1        | 0.07%   |
| 5040x1050          | 1        | 0.07%   |
| 4480x1600          | 1        | 0.07%   |
| 4160x1440          | 1        | 0.07%   |
| 3780x2160          | 1        | 0.07%   |
| 3360x1050          | 1        | 0.07%   |
| 3040x1050          | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 256      | 19.1%   |
| 24      | 135      | 10.07%  |
| 27      | 131      | 9.78%   |
| 21      | 122      | 9.1%    |
| 23      | 120      | 8.96%   |
| 19      | 87       | 6.49%   |
| 20      | 71       | 5.3%    |
| 31      | 63       | 4.7%    |
| 22      | 55       | 4.1%    |
| 18      | 52       | 3.88%   |
| 17      | 38       | 2.84%   |
| 34      | 31       | 2.31%   |
| 40      | 22       | 1.64%   |
| 15      | 19       | 1.42%   |
| 84      | 14       | 1.04%   |
| 54      | 14       | 1.04%   |
| 72      | 13       | 0.97%   |
| 32      | 13       | 0.97%   |
| 26      | 9        | 0.67%   |
| 25      | 7        | 0.52%   |
| 36      | 6        | 0.45%   |
| 52      | 5        | 0.37%   |
| 49      | 5        | 0.37%   |
| 48      | 5        | 0.37%   |
| 28      | 5        | 0.37%   |
| 65      | 4        | 0.3%    |
| 46      | 3        | 0.22%   |
| 35      | 3        | 0.22%   |
| 33      | 3        | 0.22%   |
| 29      | 3        | 0.22%   |
| 74      | 2        | 0.15%   |
| 58      | 2        | 0.15%   |
| 57      | 2        | 0.15%   |
| 42      | 2        | 0.15%   |
| 41      | 2        | 0.15%   |
| 37      | 2        | 0.15%   |
| 142     | 1        | 0.07%   |
| 86      | 1        | 0.07%   |
| 75      | 1        | 0.07%   |
| 69      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 356      | 27.49%  |
| 401-500        | 335      | 25.87%  |
| Unknown        | 256      | 19.77%  |
| 601-700        | 87       | 6.72%   |
| 301-350        | 56       | 4.32%   |
| 701-800        | 53       | 4.09%   |
| 1001-1500      | 44       | 3.4%    |
| 351-400        | 41       | 3.17%   |
| 1501-2000      | 32       | 2.47%   |
| 801-900        | 28       | 2.16%   |
| 901-1000       | 5        | 0.39%   |
| More than 2000 | 1        | 0.08%   |
| 201-300        | 1        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 710      | 56.94%  |
| Unknown | 237      | 19.01%  |
| 16/10   | 154      | 12.35%  |
| 5/4     | 71       | 5.69%   |
| 21/9    | 40       | 3.21%   |
| 4/3     | 21       | 1.68%   |
| 32/9    | 8        | 0.64%   |
| 6/5     | 4        | 0.32%   |
| 3/2     | 1        | 0.08%   |
| 1.00    | 1        | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 350      | 26.52%  |
| Unknown        | 256      | 19.39%  |
| 151-200        | 200      | 15.15%  |
| 301-350        | 134      | 10.15%  |
| 351-500        | 117      | 8.86%   |
| 141-150        | 74       | 5.61%   |
| More than 1000 | 67       | 5.08%   |
| 251-300        | 53       | 4.02%   |
| 501-1000       | 46       | 3.48%   |
| 101-110        | 14       | 1.06%   |
| 111-120        | 4        | 0.3%    |
| 81-90          | 1        | 0.08%   |
| 71-80          | 1        | 0.08%   |
| 131-140        | 1        | 0.08%   |
| 121-130        | 1        | 0.08%   |
| 91-100         | 1        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 707      | 56.2%   |
| Unknown | 256      | 20.35%  |
| 101-120 | 180      | 14.31%  |
| 1-50    | 66       | 5.25%   |
| 121-160 | 35       | 2.78%   |
| 161-240 | 14       | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1117     | 78.94%  |
| 2     | 187      | 13.22%  |
| 0     | 91       | 6.43%   |
| 3     | 18       | 1.27%   |
| 4     | 2        | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 877      | 42.63%  |
| Intel                             | 565      | 27.47%  |
| Qualcomm Atheros                  | 128      | 6.22%   |
| Broadcom                          | 72       | 3.5%    |
| Ralink Technology                 | 68       | 3.31%   |
| TP-Link                           | 57       | 2.77%   |
| Nvidia                            | 29       | 1.41%   |
| MediaTek                          | 29       | 1.41%   |
| Ralink                            | 27       | 1.31%   |
| Samsung Electronics               | 17       | 0.83%   |
| NetGear                           | 17       | 0.83%   |
| Broadcom Limited                  | 13       | 0.63%   |
| Microsoft                         | 12       | 0.58%   |
| D-Link                            | 12       | 0.58%   |
| Xiaomi                            | 10       | 0.49%   |
| Qualcomm Atheros Communications   | 10       | 0.49%   |
| D-Link System                     | 10       | 0.49%   |
| Marvell Technology Group          | 9        | 0.44%   |
| ASIX Electronics                  | 9        | 0.44%   |
| Huawei Technologies               | 8        | 0.39%   |
| Edimax Technology                 | 6        | 0.29%   |
| ASUSTek Computer                  | 6        | 0.29%   |
| Aquantia                          | 6        | 0.29%   |
| OPPO Electronics                  | 4        | 0.19%   |
| Motorola PCS                      | 4        | 0.19%   |
| Linksys                           | 4        | 0.19%   |
| Belkin Components                 | 4        | 0.19%   |
| DisplayLink                       | 3        | 0.15%   |
| ZyDAS                             | 2        | 0.1%    |
| VIA Technologies                  | 2        | 0.1%    |
| Sundance Technology Inc / IC Plus | 2        | 0.1%    |
| QinHeng Electronics               | 2        | 0.1%    |
| Motorola                          | 2        | 0.1%    |
| Gemtek                            | 2        | 0.1%    |
| AVM                               | 2        | 0.1%    |
| Arduino SA                        | 2        | 0.1%    |
| U-Blox                            | 1        | 0.05%   |
| TRENDnet                          | 1        | 0.05%   |
| T & A Mobile Phones               | 1        | 0.05%   |
| Sigma Sport                       | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 659      | 28.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78       | 3.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71       | 3.04%   |
| Intel Wi-Fi 6 AX200                                               | 59       | 2.53%   |
| Intel I211 Gigabit Network Connection                             | 58       | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 53       | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51       | 2.18%   |
| Intel Ethernet Connection (2) I219-V                              | 42       | 1.8%    |
| Intel Ethernet Controller I225-V                                  | 36       | 1.54%   |
| Realtek 802.11ac NIC                                              | 34       | 1.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 32       | 1.37%   |
| Ralink MT7601U Wireless Adapter                                   | 30       | 1.28%   |
| Intel Ethernet Connection I217-V                                  | 25       | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23       | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 22       | 0.94%   |
| Intel Wireless 7265                                               | 21       | 0.9%    |
| Nvidia MCP61 Ethernet                                             | 19       | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18       | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 16       | 0.68%   |
| Intel Wireless-AC 9260                                            | 15       | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 15       | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 14       | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 14       | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.6%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 14       | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 13       | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 13       | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12       | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12       | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11       | 0.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 11       | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 10       | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 10       | 0.43%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 10       | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10       | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10       | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 219      | 27.31%  |
| Realtek Semiconductor                 | 215      | 26.81%  |
| Ralink Technology                     | 68       | 8.48%   |
| Qualcomm Atheros                      | 63       | 7.86%   |
| TP-Link                               | 55       | 6.86%   |
| Broadcom                              | 33       | 4.11%   |
| Ralink                                | 27       | 3.37%   |
| MediaTek                              | 25       | 3.12%   |
| NetGear                               | 17       | 2.12%   |
| Microsoft                             | 12       | 1.5%    |
| D-Link                                | 12       | 1.5%    |
| Qualcomm Atheros Communications       | 10       | 1.25%   |
| D-Link System                         | 8        | 1%      |
| Edimax Technology                     | 6        | 0.75%   |
| ASUSTek Computer                      | 6        | 0.75%   |
| Broadcom Limited                      | 5        | 0.62%   |
| Linksys                               | 4        | 0.5%    |
| Belkin Components                     | 4        | 0.5%    |
| ZyDAS                                 | 2        | 0.25%   |
| Gemtek                                | 2        | 0.25%   |
| AVM                                   | 2        | 0.25%   |
| Xiaomi                                | 1        | 0.12%   |
| TRENDnet                              | 1        | 0.12%   |
| Panasonic (Matsushita)                | 1        | 0.12%   |
| Ovislink                              | 1        | 0.12%   |
| Marvell Technology Group              | 1        | 0.12%   |
| ADMtek                                | 1        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 59       | 7.26%   |
| Realtek 802.11ac NIC                                           | 34       | 4.18%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 32       | 3.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 32       | 3.94%   |
| Ralink MT7601U Wireless Adapter                                | 30       | 3.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 23       | 2.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 22       | 2.71%   |
| Intel Wireless 7265                                            | 21       | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18       | 2.21%   |
| Intel Wireless-AC 9260                                         | 15       | 1.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 14       | 1.72%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 1.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 14       | 1.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 13       | 1.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 13       | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12       | 1.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 10       | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 10       | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 1.23%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 9        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9        | 1.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 8        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8        | 0.98%   |
| Intel Wireless 7260                                            | 8        | 0.98%   |
| Intel Wireless 3165                                            | 8        | 0.98%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 8        | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 7        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7        | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                | 7        | 0.86%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 7        | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6        | 0.74%   |
| Microsoft Xbox 360 Wireless Adapter                            | 6        | 0.74%   |
| MediaTek WiFi                                                  | 6        | 0.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 5        | 0.62%   |
| TP-Link 802.11ac WLAN Adapter                                  | 5        | 0.62%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5        | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 5        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 801      | 54.56%  |
| Intel                             | 441      | 30.04%  |
| Qualcomm Atheros                  | 69       | 4.7%    |
| Broadcom                          | 40       | 2.72%   |
| Nvidia                            | 29       | 1.98%   |
| Samsung Electronics               | 12       | 0.82%   |
| Xiaomi                            | 9        | 0.61%   |
| ASIX Electronics                  | 9        | 0.61%   |
| Marvell Technology Group          | 8        | 0.54%   |
| Broadcom Limited                  | 8        | 0.54%   |
| Huawei Technologies               | 7        | 0.48%   |
| Aquantia                          | 6        | 0.41%   |
| OPPO Electronics                  | 4        | 0.27%   |
| MediaTek                          | 4        | 0.27%   |
| DisplayLink                       | 3        | 0.2%    |
| VIA Technologies                  | 2        | 0.14%   |
| TP-Link                           | 2        | 0.14%   |
| Sundance Technology Inc / IC Plus | 2        | 0.14%   |
| Motorola PCS                      | 2        | 0.14%   |
| D-Link System                     | 2        | 0.14%   |
| Research In Motion                | 1        | 0.07%   |
| Qualcomm                          | 1        | 0.07%   |
| JMicron Technology                | 1        | 0.07%   |
| ICS Advent                        | 1        | 0.07%   |
| HMD Global                        | 1        | 0.07%   |
| Google                            | 1        | 0.07%   |
| Apple                             | 1        | 0.07%   |
| Accton Technology                 | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 659      | 44.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78       | 5.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71       | 4.74%   |
| Intel I211 Gigabit Network Connection                             | 58       | 3.87%   |
| Intel Ethernet Connection I217-LM                                 | 53       | 3.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51       | 3.41%   |
| Intel Ethernet Connection (2) I219-V                              | 42       | 2.81%   |
| Intel Ethernet Controller I225-V                                  | 36       | 2.4%    |
| Intel Ethernet Connection I217-V                                  | 25       | 1.67%   |
| Nvidia MCP61 Ethernet                                             | 19       | 1.27%   |
| Intel 82579V Gigabit Network Connection                           | 16       | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 15       | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.94%   |
| Intel Ethernet Connection (2) I218-V                              | 14       | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12       | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11       | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10       | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.6%    |
| Intel Ethernet Connection (12) I219-V                             | 8        | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 7        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6        | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 6        | 0.4%    |
| Huawei MAR-LX1M                                                   | 6        | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                     | 6        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5        | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 5        | 0.33%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 5        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 5        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1372     | 64.78%  |
| WiFi     | 722      | 34.09%  |
| Modem    | 19       | 0.9%    |
| Unknown  | 5        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1031     | 70.71%  |
| WiFi     | 423      | 29.01%  |
| Modem    | 2        | 0.14%   |
| Unknown  | 2        | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 895      | 63.93%  |
| 2     | 437      | 31.21%  |
| 3     | 49       | 3.5%    |
| 0     | 14       | 1%      |
| 5     | 2        | 0.14%   |
| 4     | 2        | 0.14%   |
| 7     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 924      | 65.58%  |
| Yes  | 485      | 34.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 184      | 37.1%   |
| Cambridge Silicon Radio         | 98       | 19.76%  |
| Realtek Semiconductor           | 69       | 13.91%  |
| Broadcom                        | 28       | 5.65%   |
| ASUSTek Computer                | 23       | 4.64%   |
| Qualcomm Atheros Communications | 16       | 3.23%   |
| IMC Networks                    | 13       | 2.62%   |
| MediaTek                        | 12       | 2.42%   |
| TP-Link                         | 8        | 1.61%   |
| Apple                           | 8        | 1.61%   |
| Dynex                           | 5        | 1.01%   |
| Foxconn / Hon Hai               | 4        | 0.81%   |
| Realtek                         | 3        | 0.6%    |
| Lite-On Technology              | 3        | 0.6%    |
| Integrated System Solution      | 3        | 0.6%    |
| Belkin Components               | 3        | 0.6%    |
| Actions                         | 3        | 0.6%    |
| Unknown                         | 3        | 0.6%    |
| Dell                            | 2        | 0.4%    |
| Sitecom Europe                  | 1        | 0.2%    |
| Ralink                          | 1        | 0.2%    |
| National Semiconductor          | 1        | 0.2%    |
| Micro Star International        | 1        | 0.2%    |
| Marvell Semiconductor           | 1        | 0.2%    |
| Logitech                        | 1        | 0.2%    |
| Edimax Technology               | 1        | 0.2%    |
| D-Link System                   | 1        | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 98       | 19.76%  |
| Realtek Bluetooth Radio                                  | 53       | 10.69%  |
| Intel AX200 Bluetooth                                    | 46       | 9.27%   |
| Intel Bluetooth wireless interface                       | 41       | 8.27%   |
| Intel AX210 Bluetooth                                    | 28       | 5.65%   |
| Intel Wireless-AC 3168 Bluetooth                         | 22       | 4.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 16       | 3.23%   |
| Intel AX201 Bluetooth                                    | 13       | 2.62%   |
| MediaTek Wireless_Device                                 | 12       | 2.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 11       | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 11       | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 10       | 2.02%   |
| IMC Networks Bluetooth Radio                             | 9        | 1.81%   |
| TP-Link TP-Cdj+ UB5A Adapter                             | 8        | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                           | 6        | 1.21%   |
| Realtek Bluetooth 5.1 Radio                              | 5        | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5        | 1.01%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 5        | 1.01%   |
| Apple Bluetooth Host Controller                          | 5        | 1.01%   |
| Realtek 802.11ac WLAN Adapter                            | 4        | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 4        | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 4        | 0.81%   |
| ASUS Bluetooth Radio                                     | 4        | 0.81%   |
| Realtek Bluetooth Radio                                  | 3        | 0.6%    |
| Lite-On Bluetooth Device                                 | 3        | 0.6%    |
| Intel Bluetooth Device                                   | 3        | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                        | 3        | 0.6%    |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.6%    |
| Broadcom Bluetooth 2.0+eDR dongle                        | 3        | 0.6%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 3        | 0.6%    |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.6%    |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.6%    |
| ASUS ASUS USB-BT500                                      | 3        | 0.6%    |
| Actions general adapter                                  | 3        | 0.6%    |
| Unknown                                                  | 3        | 0.6%    |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.4%    |
| Integrated System Solution Bluetooth Device              | 2        | 0.4%    |
| IMC Networks Wireless_Device                             | 2        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 896      | 38.64%  |
| AMD                                          | 598      | 25.79%  |
| Nvidia                                       | 518      | 22.34%  |
| C-Media Electronics                          | 54       | 2.33%   |
| Creative Labs                                | 25       | 1.08%   |
| Logitech                                     | 17       | 0.73%   |
| Kingston Technology                          | 15       | 0.65%   |
| ASUSTek Computer                             | 15       | 0.65%   |
| JMTek                                        | 14       | 0.6%    |
| Generalplus Technology                       | 12       | 0.52%   |
| Texas Instruments                            | 9        | 0.39%   |
| VIA Technologies                             | 8        | 0.34%   |
| Razer USA                                    | 8        | 0.34%   |
| Plantronics                                  | 8        | 0.34%   |
| Creative Technology                          | 7        | 0.3%    |
| Micro Star International                     | 6        | 0.26%   |
| GN Netcom                                    | 6        | 0.26%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.17%   |
| Tenx Technology                              | 4        | 0.17%   |
| Realtek Semiconductor                        | 4        | 0.17%   |
| KTMicro                                      | 4        | 0.17%   |
| Focusrite-Novation                           | 4        | 0.17%   |
| BR25                                         | 4        | 0.17%   |
| SteelSeries ApS                              | 3        | 0.13%   |
| RODE Microphones                             | 3        | 0.13%   |
| Astro Gaming                                 | 3        | 0.13%   |
| Asahi Kasei Microsystems                     | 3        | 0.13%   |
| Yamaha                                       | 2        | 0.09%   |
| Microsoft                                    | 2        | 0.09%   |
| DSEA A/S                                     | 2        | 0.09%   |
| DCMT Technology                              | 2        | 0.09%   |
| Corsair                                      | 2        | 0.09%   |
| Cambridge Audio                              | 2        | 0.09%   |
| Blue Microphones                             | 2        | 0.09%   |
| BEHRINGER International                      | 2        | 0.09%   |
| Audio-Technica                               | 2        | 0.09%   |
| ZOOM                                         | 1        | 0.04%   |
| XMOS                                         | 1        | 0.04%   |
| Valve Software                               | 1        | 0.04%   |
| Universal Audio                              | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 148      | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 127      | 4.69%   |
| AMD Starship/Matisse HD Audio Controller                                          | 116      | 4.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 115      | 4.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 103      | 3.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 84       | 3.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 84       | 3.1%    |
| AMD Family 17h/19h HD Audio Controller                                            | 78       | 2.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 61       | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 58       | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 54       | 1.99%   |
| AMD FCH Azalia Controller                                                         | 52       | 1.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 51       | 1.88%   |
| Intel 200 Series PCH HD Audio                                                     | 50       | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                        | 44       | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 41       | 1.51%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 33       | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 33       | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 32       | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 32       | 1.18%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 32       | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                                     | 31       | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                     | 31       | 1.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 28       | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                | 27       | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 27       | 1%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 27       | 1%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 26       | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 24       | 0.89%   |
| AMD Navi 10 HDMI Audio                                                            | 24       | 0.89%   |
| Nvidia High Definition Audio Controller                                           | 23       | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 23       | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                     | 22       | 0.81%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 22       | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 21       | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                     | 20       | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                | 20       | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                                     | 20       | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                                     | 20       | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                          | 19       | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 35       | 16.2%   |
| Kingston            | 30       | 13.89%  |
| Samsung Electronics | 25       | 11.57%  |
| Corsair             | 21       | 9.72%   |
| G.Skill             | 20       | 9.26%   |
| SK hynix            | 17       | 7.87%   |
| Crucial             | 16       | 7.41%   |
| Team                | 11       | 5.09%   |
| Micron Technology   | 9        | 4.17%   |
| Unknown             | 5        | 2.31%   |
| Nanya Technology    | 3        | 1.39%   |
| A-DATA Technology   | 3        | 1.39%   |
| Wilk                | 2        | 0.93%   |
| Unifosa             | 2        | 0.93%   |
| Ramaxel Technology  | 2        | 0.93%   |
| Patriot             | 2        | 0.93%   |
| Avant               | 2        | 0.93%   |
| Transcend           | 1        | 0.46%   |
| Timetec             | 1        | 0.46%   |
| SUPER KINGSTEK      | 1        | 0.46%   |
| Qimonda             | 1        | 0.46%   |
| Patriot Memory      | 1        | 0.46%   |
| Goldkey             | 1        | 0.46%   |
| Golden Empire       | 1        | 0.46%   |
| F7852C80            | 1        | 0.46%   |
| Elpida              | 1        | 0.46%   |
| Apacer              | 1        | 0.46%   |
| AMD                 | 1        | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 6        | 2.54%   |
| Unknown                                                 | 5        | 2.12%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 3        | 1.27%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 3        | 1.27%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.27%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 0.85%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s      | 2        | 0.85%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s      | 2        | 0.85%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s      | 2        | 0.85%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.85%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 0.85%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 0.85%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 2        | 0.85%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 2        | 0.85%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 2        | 0.85%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 0.85%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1648MT/s     | 2        | 0.85%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.85%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 0.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 0.85%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s   | 2        | 0.85%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s  | 2        | 0.85%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2        | 0.85%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 2        | 0.85%   |
| Wilk RAM IRX3200D464L16A/16G 16384MB DIMM DDR4 3200MT/s | 1        | 0.42%   |
| Wilk RAM GX3236D464S/8GSBS1 8192MB DIMM DDR4 3467MT/s   | 1        | 0.42%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM SDRAM                       | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                  | 1        | 0.42%   |
| Unknown RAM Module 512MB DIMM 667MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s              | 1        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 84       | 43.98%  |
| DDR3    | 70       | 36.65%  |
| Unknown | 13       | 6.81%   |
| SDRAM   | 8        | 4.19%   |
| DDR2    | 8        | 4.19%   |
| DDR5    | 3        | 1.57%   |
| DDR     | 3        | 1.57%   |
| LPDDR4  | 2        | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 175      | 93.09%  |
| SODIMM       | 10       | 5.32%   |
| Row Of Chips | 2        | 1.06%   |
| FB-DIMM      | 1        | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 84       | 39.81%  |
| 4096  | 56       | 26.54%  |
| 2048  | 25       | 11.85%  |
| 16384 | 23       | 10.9%   |
| 32768 | 16       | 7.58%   |
| 1024  | 6        | 2.84%   |
| 512   | 1        | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 38       | 18.1%   |
| 1333    | 26       | 12.38%  |
| 3200    | 21       | 10%     |
| 3600    | 16       | 7.62%   |
| 2667    | 10       | 4.76%   |
| 2133    | 9        | 4.29%   |
| 3000    | 7        | 3.33%   |
| 2400    | 7        | 3.33%   |
| 3733    | 6        | 2.86%   |
| 1866    | 6        | 2.86%   |
| 1800    | 6        | 2.86%   |
| 800     | 6        | 2.86%   |
| Unknown | 4        | 1.9%    |
| 4800    | 3        | 1.43%   |
| 3800    | 3        | 1.43%   |
| 2933    | 3        | 1.43%   |
| 2666    | 3        | 1.43%   |
| 1867    | 3        | 1.43%   |
| 667     | 3        | 1.43%   |
| 3866    | 2        | 0.95%   |
| 3666    | 2        | 0.95%   |
| 3500    | 2        | 0.95%   |
| 3466    | 2        | 0.95%   |
| 1066    | 2        | 0.95%   |
| 400     | 2        | 0.95%   |
| 6000    | 1        | 0.48%   |
| 5354    | 1        | 0.48%   |
| 5200    | 1        | 0.48%   |
| 4266    | 1        | 0.48%   |
| 4000    | 1        | 0.48%   |
| 3933    | 1        | 0.48%   |
| 3534    | 1        | 0.48%   |
| 3467    | 1        | 0.48%   |
| 3400    | 1        | 0.48%   |
| 2800    | 1        | 0.48%   |
| 2733    | 1        | 0.48%   |
| 2465    | 1        | 0.48%   |
| 2200    | 1        | 0.48%   |
| 2000    | 1        | 0.48%   |
| 1400    | 1        | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 20       | 27.03%  |
| Canon                 | 16       | 21.62%  |
| Brother Industries    | 13       | 17.57%  |
| Seiko Epson           | 10       | 13.51%  |
| Samsung Electronics   | 9        | 12.16%  |
| Lexmark International | 2        | 2.7%    |
| Ricoh                 | 1        | 1.35%   |
| QinHeng Electronics   | 1        | 1.35%   |
| Konica Minolta        | 1        | 1.35%   |
| GG IMAGE              | 1        | 1.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L3110 Series                     | 2        | 2.7%    |
| Samsung C460 Series                          | 2        | 2.7%    |
| HP OfficeJet 6950                            | 2        | 2.7%    |
| HP LaserJet Professional P1102w              | 2        | 2.7%    |
| HP DeskJet 2700 series                       | 2        | 2.7%    |
| HP DeskJet 2130 series                       | 2        | 2.7%    |
| Canon PIXMA MG3600 Series                    | 2        | 2.7%    |
| Canon LiDE 400                               | 2        | 2.7%    |
| Seiko Epson XP-7100 Series                   | 1        | 1.35%   |
| Seiko Epson XP-200 Series                    | 1        | 1.35%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.35%   |
| Seiko Epson L805 Series                      | 1        | 1.35%   |
| Seiko Epson L6270 Series                     | 1        | 1.35%   |
| Seiko Epson L355 Series                      | 1        | 1.35%   |
| Seiko Epson L3150 Series                     | 1        | 1.35%   |
| Seiko Epson ET-2820 Series                   | 1        | 1.35%   |
| Samsung SCX-483x 5x3x Series                 | 1        | 1.35%   |
| Samsung SCX-4623 Series                      | 1        | 1.35%   |
| Samsung SCX-4200 series                      | 1        | 1.35%   |
| Samsung SCX-3400 Series                      | 1        | 1.35%   |
| Samsung ML-2950 Series                       | 1        | 1.35%   |
| Samsung ML-216x Series Laser Printer         | 1        | 1.35%   |
| Samsung M2070 Series                         | 1        | 1.35%   |
| Ricoh SP 112SU                               | 1        | 1.35%   |
| QinHeng CH340S                               | 1        | 1.35%   |
| Lexmark International MX317dn                | 1        | 1.35%   |
| Lexmark International Laser Printer E232     | 1        | 1.35%   |
| Konica Minolta PagePro 1380MF                | 1        | 1.35%   |
| HP Smart Tank 510 series                     | 1        | 1.35%   |
| HP PSC 1100 series                           | 1        | 1.35%   |
| HP Officejet 6600                            | 1        | 1.35%   |
| HP OfficeJet 5600 (USBHUB)                   | 1        | 1.35%   |
| HP OfficeJet 4650 series                     | 1        | 1.35%   |
| HP LaserJet Pro M148-M149                    | 1        | 1.35%   |
| HP LaserJet 1320                             | 1        | 1.35%   |
| HP ENVY Photo 7800 series                    | 1        | 1.35%   |
| HP ENVY 4520 series                          | 1        | 1.35%   |
| HP Deskjet D1400 series                      | 1        | 1.35%   |
| HP DeskJet 3630 series                       | 1        | 1.35%   |
| HP Color LaserJet CP1215                     | 1        | 1.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 9        | 69.23%  |
| Hewlett-Packard | 3        | 23.08%  |
| Seiko Epson     | 1        | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                | 2        | 14.29%  |
| Seiko Epson Scanner                    | 1        | 7.14%   |
| HP ScanJet 2400c                       | 1        | 7.14%   |
| HP Scanjet 200                         | 1        | 7.14%   |
| HP PSC 1200                            | 1        | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20     | 1        | 7.14%   |
| Canon CanoScan LiDE 90                 | 1        | 7.14%   |
| Canon CanoScan LiDE 60                 | 1        | 7.14%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 7.14%   |
| Canon CanoScan LiDE 110                | 1        | 7.14%   |
| Canon CanoScan LiDE 100                | 1        | 7.14%   |
| Canon CanoScan D660U                   | 1        | 7.14%   |
| Canon CanoScan 8800F                   | 1        | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 63       | 27.51%  |
| Microdia                      | 23       | 10.04%  |
| Microsoft                     | 16       | 6.99%   |
| Sunplus Innovation Technology | 13       | 5.68%   |
| Generalplus Technology        | 10       | 4.37%   |
| Apple                         | 9        | 3.93%   |
| Samsung Electronics           | 8        | 3.49%   |
| ARC International             | 7        | 3.06%   |
| Chicony Electronics           | 6        | 2.62%   |
| Jieli Technology              | 5        | 2.18%   |
| Z-Star Microelectronics       | 4        | 1.75%   |
| Realtek Semiconductor         | 4        | 1.75%   |
| Razer USA                     | 4        | 1.75%   |
| Creative Technology           | 4        | 1.75%   |
| Tobii Technology AB           | 3        | 1.31%   |
| HDR webcam                    | 3        | 1.31%   |
| GEMBIRD                       | 3        | 1.31%   |
| A4Tech                        | 3        | 1.31%   |
| Xiongmai                      | 2        | 0.87%   |
| WaveRider Communications      | 2        | 0.87%   |
| Trust                         | 2        | 0.87%   |
| Suyin                         | 2        | 0.87%   |
| MacroSilicon                  | 2        | 0.87%   |
| lihappe8                      | 2        | 0.87%   |
| IMC Networks                  | 2        | 0.87%   |
| Guillemot                     | 2        | 0.87%   |
| Cubeternet                    | 2        | 0.87%   |
| Xiaomi                        | 1        | 0.44%   |
| Unknown                       | 1        | 0.44%   |
| Teslong Camera                | 1        | 0.44%   |
| Sweex                         | 1        | 0.44%   |
| Sunplus Technology            | 1        | 0.44%   |
| Sonix Technology              | 1        | 0.44%   |
| Silicon Motion                | 1        | 0.44%   |
| Ruision                       | 1        | 0.44%   |
| Pixart Imaging                | 1        | 0.44%   |
| Lenovo                        | 1        | 0.44%   |
| KYE Systems (Mouse Systems)   | 1        | 0.44%   |
| Intel                         | 1        | 0.44%   |
| INOGENI                       | 1        | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 16       | 6.93%   |
| Logitech HD Pro Webcam C920              | 12       | 5.19%   |
| Microsoft LifeCam HD-3000                | 9        | 3.9%    |
| Samsung Galaxy series, misc. (MTP mode)  | 8        | 3.46%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 8        | 3.46%   |
| ARC International Camera                 | 7        | 3.03%   |
| Microdia USB 2.0 Camera                  | 6        | 2.6%    |
| Sunplus FHD Camera Microphone            | 5        | 2.16%   |
| Microdia Webcam Vitade AF                | 5        | 2.16%   |
| Logitech HD Webcam C615                  | 5        | 2.16%   |
| Logitech C920 PRO HD Webcam              | 5        | 2.16%   |
| Jieli USB PHY 2.0                        | 5        | 2.16%   |
| Sunplus HD 720P webcam                   | 4        | 1.73%   |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 1.73%   |
| Microdia USB Camera                      | 4        | 1.73%   |
| Generalplus GENERAL WEBCAM               | 4        | 1.73%   |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.73%   |
| Chicony HP High Definition 1MP Webcam    | 4        | 1.73%   |
| Tobii AB EyeChip                         | 3        | 1.3%    |
| Microsoft LifeCam VX-500 [1357]          | 3        | 1.3%    |
| Microdia Integrated Camera               | 3        | 1.3%    |
| Logitech Logitech Webcam C925e           | 3        | 1.3%    |
| Logitech HD Webcam C910                  | 3        | 1.3%    |
| HDR webcam HDR webcam                    | 3        | 1.3%    |
| Z-Star Integrated Camera                 | 2        | 0.87%   |
| Xiongmai web camera                      | 2        | 0.87%   |
| WaveRider USB Live camera                | 2        | 0.87%   |
| Suyin HD WebCam                          | 2        | 0.87%   |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 0.87%   |
| Microdia USB Live camera                 | 2        | 0.87%   |
| Logitech Webcam C310                     | 2        | 0.87%   |
| Logitech QuickCam Pro for Notebooks      | 2        | 0.87%   |
| Logitech HD Webcam C525                  | 2        | 0.87%   |
| Logitech C922 Pro Stream Webcam          | 2        | 0.87%   |
| lihappe8 USB 2.0 Camera                  | 2        | 0.87%   |
| Generalplus WEB CAM                      | 2        | 0.87%   |
| GEMBIRD USB2.0 PC CAMERA                 | 2        | 0.87%   |
| Creative Live! Cam Sync HD [VF0770]      | 2        | 0.87%   |
| A4Tech REDRAGON Live Camera              | 2        | 0.87%   |
| Z-Star Venus USB2.0 Camera               | 1        | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 66.67%  |
| AuthenTec             | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor        | 2        | 66.67%  |
| AuthenTec AES2501 Fingerprint Sensor | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 18.18%  |
| Advanced Card Systems             | 2        | 18.18%  |
| VASCO Data Security International | 1        | 9.09%   |
| SCM Microsystems                  | 1        | 9.09%   |
| Reiner SCT Kartensysteme          | 1        | 9.09%   |
| Jing-Mold Enterprise              | 1        | 9.09%   |
| Fujitsu Siemens Computers         | 1        | 9.09%   |
| Chicony Electronics               | 1        | 9.09%   |
| Alcor Micro                       | 1        | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 18.18%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 9.09%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 9.09%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 9.09%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 9.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                               | 1        | 9.09%   |
| Advanced Card Systems ACR39U                                      | 1        | 9.09%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1128     | 79.6%   |
| 1     | 254      | 17.93%  |
| 2     | 30       | 2.12%   |
| 3     | 4        | 0.28%   |
| 4     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 126      | 40.13%  |
| Net/wireless             | 119      | 37.9%   |
| Communication controller | 14       | 4.46%   |
| Multimedia controller    | 10       | 3.18%   |
| Unassigned class         | 8        | 2.55%   |
| Chipcard                 | 7        | 2.23%   |
| Storage/raid             | 6        | 1.91%   |
| Bluetooth                | 5        | 1.59%   |
| Modem                    | 4        | 1.27%   |
| Sound                    | 3        | 0.96%   |
| Fingerprint reader       | 3        | 0.96%   |
| Network                  | 2        | 0.64%   |
| Net/ethernet             | 2        | 0.64%   |
| Camera                   | 2        | 0.64%   |
| Storage/ide              | 1        | 0.32%   |
| Dvb card                 | 1        | 0.32%   |
| Card reader              | 1        | 0.32%   |


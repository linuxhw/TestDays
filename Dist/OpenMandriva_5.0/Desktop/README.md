OpenMandriva 5.0 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 5.0.

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

Total: 412

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | PRO B650M-A WIFI            | [c5f27e5e7b](https://linux-hardware.org/?probe=c5f27e5e7b) | May 09, 2024 |
| ASUSTek       | PRIME A320M-E               | [d97bbebd45](https://linux-hardware.org/?probe=d97bbebd45) | May 07, 2024 |
| HP            | 8299                        | [6024274be6](https://linux-hardware.org/?probe=6024274be6) | May 06, 2024 |
| Intel         | DG45ID AAE27729-312         | [9610cedb7b](https://linux-hardware.org/?probe=9610cedb7b) | May 05, 2024 |
| HP            | 1850                        | [5bab4e9f9b](https://linux-hardware.org/?probe=5bab4e9f9b) | May 05, 2024 |
| Acer          | EQ45LM                      | [52563cbf82](https://linux-hardware.org/?probe=52563cbf82) | May 04, 2024 |
| MouseCompu... | H61MU-S01                   | [9ab7d4b6e9](https://linux-hardware.org/?probe=9ab7d4b6e9) | May 04, 2024 |
| Gigabyte      | GA-78LMT-S2                 | [6a9fd41a39](https://linux-hardware.org/?probe=6a9fd41a39) | May 04, 2024 |
| Gigabyte      | 970A-DS3P                   | [0cf6542a99](https://linux-hardware.org/?probe=0cf6542a99) | May 04, 2024 |
| Unknown       | G41 A01                     | [537cc137bd](https://linux-hardware.org/?probe=537cc137bd) | May 04, 2024 |
| Centerm       | C92                         | [beaeac18bc](https://linux-hardware.org/?probe=beaeac18bc) | May 04, 2024 |
| Gigabyte      | B450M DS3H V2               | [87b5a4320e](https://linux-hardware.org/?probe=87b5a4320e) | May 03, 2024 |
| ASRock        | X300M-STX                   | [58d58080cd](https://linux-hardware.org/?probe=58d58080cd) | May 03, 2024 |
| Acer          | FIH57                       | [8e4b02facb](https://linux-hardware.org/?probe=8e4b02facb) | May 02, 2024 |
| HP            | 2129                        | [3a5c2b8ae5](https://linux-hardware.org/?probe=3a5c2b8ae5) | May 02, 2024 |
| Acer          | EM61SM/EM61PM               | [3b2c0bd5f6](https://linux-hardware.org/?probe=3b2c0bd5f6) | May 01, 2024 |
| Dell          | 0KRC95 A00                  | [72ba135dda](https://linux-hardware.org/?probe=72ba135dda) | May 01, 2024 |
| Gigabyte      | H81M-HD3                    | [adcbc97b26](https://linux-hardware.org/?probe=adcbc97b26) | May 01, 2024 |
| MSI           | B450M MORTAR MAX            | [527f3123a6](https://linux-hardware.org/?probe=527f3123a6) | May 01, 2024 |
| Lenovo        | H410                        | [d16690b0c4](https://linux-hardware.org/?probe=d16690b0c4) | May 01, 2024 |
| Gigabyte      | B85M-D2V                    | [40ae77d112](https://linux-hardware.org/?probe=40ae77d112) | May 01, 2024 |
| MSI           | A68HM-E33                   | [abf75e8321](https://linux-hardware.org/?probe=abf75e8321) | Apr 29, 2024 |
| MSI           | PRO H610M-G DDR4            | [1492484deb](https://linux-hardware.org/?probe=1492484deb) | Apr 29, 2024 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [ed1d2dac2d](https://linux-hardware.org/?probe=ed1d2dac2d) | Apr 28, 2024 |
| ASUSTek       | A8NE-FM                     | [dbabd85077](https://linux-hardware.org/?probe=dbabd85077) | Apr 28, 2024 |
| Dell          | 096JG8 A01                  | [5848ea3def](https://linux-hardware.org/?probe=5848ea3def) | Apr 27, 2024 |
| MSI           | PRO Z690-P DDR4             | [c43d04d511](https://linux-hardware.org/?probe=c43d04d511) | Apr 27, 2024 |
| Acer          | Revo M2-601 A01             | [54a18aaccb](https://linux-hardware.org/?probe=54a18aaccb) | Apr 24, 2024 |
| ASUSTek       | PRIME B550M-A               | [b662ccf901](https://linux-hardware.org/?probe=b662ccf901) | Apr 22, 2024 |
| ASUSTek       | M5A99X EVO                  | [afb6abad8d](https://linux-hardware.org/?probe=afb6abad8d) | Apr 21, 2024 |
| ASUSTek       | Amberine                    | [618eece8ca](https://linux-hardware.org/?probe=618eece8ca) | Apr 21, 2024 |
| ASUSTek       | PRIME H410M-A               | [41da917e67](https://linux-hardware.org/?probe=41da917e67) | Apr 21, 2024 |
| ASUSTek       | A88XM-E                     | [6ff101f38c](https://linux-hardware.org/?probe=6ff101f38c) | Apr 19, 2024 |
| Gigabyte      | H170M-D3H DDR3-CF           | [f7a78f85d8](https://linux-hardware.org/?probe=f7a78f85d8) | Apr 18, 2024 |
| ASUSTek       | P5N72-T PREMIUM             | [067b12dd29](https://linux-hardware.org/?probe=067b12dd29) | Apr 16, 2024 |
| Dell          | 0D28YY A03                  | [0332c27e2c](https://linux-hardware.org/?probe=0332c27e2c) | Apr 16, 2024 |
| ASUSTek       | P8H61-MX R2.0               | [53a06e22d4](https://linux-hardware.org/?probe=53a06e22d4) | Apr 16, 2024 |
| MSI           | H81M-E34                    | [61891eff16](https://linux-hardware.org/?probe=61891eff16) | Apr 15, 2024 |
| HP            | 805D                        | [f3b0ef4a3b](https://linux-hardware.org/?probe=f3b0ef4a3b) | Apr 14, 2024 |
| Gigabyte      | H110M-DS2V-CF               | [40fe788bf0](https://linux-hardware.org/?probe=40fe788bf0) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a829e68e1f](https://linux-hardware.org/?probe=a829e68e1f) | Apr 14, 2024 |
| MAXSUN        | MS-Terminator B760M D4 V... | [5a0687cb6d](https://linux-hardware.org/?probe=5a0687cb6d) | Apr 13, 2024 |
| ASRock        | H510M-HDV R2.0              | [5b213df28c](https://linux-hardware.org/?probe=5b213df28c) | Apr 12, 2024 |
| Gigabyte      | GA-970A-D3                  | [1a6e8ab59b](https://linux-hardware.org/?probe=1a6e8ab59b) | Apr 12, 2024 |
| ASUSTek       | P5Q                         | [05d54173b4](https://linux-hardware.org/?probe=05d54173b4) | Apr 08, 2024 |
| ASUSTek       | P8H77-V                     | [721926ded3](https://linux-hardware.org/?probe=721926ded3) | Apr 08, 2024 |
| Daten Tecn... | DA75PRO                     | [aaf78d3f34](https://linux-hardware.org/?probe=aaf78d3f34) | Apr 07, 2024 |
| HP            | 8054                        | [55c6935be9](https://linux-hardware.org/?probe=55c6935be9) | Apr 07, 2024 |
| ASRock        | 970A-G                      | [e1e0f99df4](https://linux-hardware.org/?probe=e1e0f99df4) | Apr 06, 2024 |
| Gigabyte      | B85M-D3H                    | [69a0e2f77d](https://linux-hardware.org/?probe=69a0e2f77d) | Apr 06, 2024 |
| ASRock        | B150M Pro4                  | [75a5d3af57](https://linux-hardware.org/?probe=75a5d3af57) | Apr 06, 2024 |
| HP            | 8653 A                      | [1ab035c8c7](https://linux-hardware.org/?probe=1ab035c8c7) | Apr 06, 2024 |
| ASUSTek       | P5KPL-CM                    | [7fb2e983ef](https://linux-hardware.org/?probe=7fb2e983ef) | Apr 06, 2024 |
| Gigabyte      | GA-880GM-USB3               | [2ad3b3efa3](https://linux-hardware.org/?probe=2ad3b3efa3) | Apr 06, 2024 |
| Gigabyte      | B85M-HD3                    | [3d81eb0d82](https://linux-hardware.org/?probe=3d81eb0d82) | Apr 05, 2024 |
| ASUSTek       | PRIME Z590-P                | [9ef1b07dc2](https://linux-hardware.org/?probe=9ef1b07dc2) | Apr 05, 2024 |
| MSI           | Z590 PRO WIFI               | [b4b9cef6a6](https://linux-hardware.org/?probe=b4b9cef6a6) | Apr 05, 2024 |
| ASUSTek       | PRIME X470-PRO              | [e16e4757cf](https://linux-hardware.org/?probe=e16e4757cf) | Apr 04, 2024 |
| MSI           | H310M PRO-VDH               | [98d131eacb](https://linux-hardware.org/?probe=98d131eacb) | Apr 04, 2024 |
| ASUSTek       | PRIME H570-PLUS             | [69279a9792](https://linux-hardware.org/?probe=69279a9792) | Apr 04, 2024 |
| ASRock        | A520M Pro4                  | [dd6acd4be2](https://linux-hardware.org/?probe=dd6acd4be2) | Apr 04, 2024 |
| ASRock        | B450 Pro4 R2.0              | [60056839c9](https://linux-hardware.org/?probe=60056839c9) | Apr 03, 2024 |
| Gigabyte      | MFLP5IP-00                  | [aedb7d1450](https://linux-hardware.org/?probe=aedb7d1450) | Apr 03, 2024 |
| Gigabyte      | F2A68HM-H                   | [e9bf1ed29d](https://linux-hardware.org/?probe=e9bf1ed29d) | Apr 01, 2024 |
| ASUSTek       | PRIME A320I-K               | [463d13b7df](https://linux-hardware.org/?probe=463d13b7df) | Apr 01, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [2f1c067d48](https://linux-hardware.org/?probe=2f1c067d48) | Apr 01, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [939cfeb31e](https://linux-hardware.org/?probe=939cfeb31e) | Apr 01, 2024 |
| ASRock        | FM2A88X Extreme6+           | [1f8ed16982](https://linux-hardware.org/?probe=1f8ed16982) | Apr 01, 2024 |
| Gigabyte      | B250M-Gaming5-CF            | [47d0634e2a](https://linux-hardware.org/?probe=47d0634e2a) | Mar 31, 2024 |
| MSI           | H310M PRO-M2                | [b2753ac794](https://linux-hardware.org/?probe=b2753ac794) | Mar 31, 2024 |
| ASUSTek       | PRIME H310M-D R2.0          | [b251cdc4d6](https://linux-hardware.org/?probe=b251cdc4d6) | Mar 31, 2024 |
| MouseCompu... | B85H3-M4/2.0                | [0318e0dbfb](https://linux-hardware.org/?probe=0318e0dbfb) | Mar 31, 2024 |
| ASUSTek       | H81M-K                      | [483eaeb53c](https://linux-hardware.org/?probe=483eaeb53c) | Mar 30, 2024 |
| ASRock        | G31M-S                      | [7df654f75f](https://linux-hardware.org/?probe=7df654f75f) | Mar 30, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1fb5102d8c](https://linux-hardware.org/?probe=1fb5102d8c) | Mar 30, 2024 |
| Gigabyte      | H87-HD3                     | [2dc48c8319](https://linux-hardware.org/?probe=2dc48c8319) | Mar 30, 2024 |
| Gigabyte      | B450M DS3H V2               | [e239e5305b](https://linux-hardware.org/?probe=e239e5305b) | Mar 30, 2024 |
| Dell          | 0GDG8Y A00                  | [70199cb1ec](https://linux-hardware.org/?probe=70199cb1ec) | Mar 29, 2024 |
| ASRock        | Z87 Extreme6                | [a7ffff15ff](https://linux-hardware.org/?probe=a7ffff15ff) | Mar 28, 2024 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [697b22a027](https://linux-hardware.org/?probe=697b22a027) | Mar 28, 2024 |
| ASUSTek       | P8Z77-V LX                  | [af967ddbdc](https://linux-hardware.org/?probe=af967ddbdc) | Mar 26, 2024 |
| Dell          | 0JP3NX A01                  | [01246bca4d](https://linux-hardware.org/?probe=01246bca4d) | Mar 26, 2024 |
| ASUSTek       | P5K SE                      | [2391cf9f32](https://linux-hardware.org/?probe=2391cf9f32) | Mar 26, 2024 |
| AFOX          | IH61-MA5                    | [a5418cfc92](https://linux-hardware.org/?probe=a5418cfc92) | Mar 24, 2024 |
| Acer          | Veriton M4620G v1.0         | [d6f6ee455f](https://linux-hardware.org/?probe=d6f6ee455f) | Mar 23, 2024 |
| Unknown       | Unknown                     | [52255354d1](https://linux-hardware.org/?probe=52255354d1) | Mar 21, 2024 |
| Dell          | 0K240Y A02                  | [8c345dca31](https://linux-hardware.org/?probe=8c345dca31) | Mar 21, 2024 |
| ASRock        | E35LM1                      | [d67fe2fd09](https://linux-hardware.org/?probe=d67fe2fd09) | Mar 21, 2024 |
| Lenovo        | 367D SDK0J40709 WIN         | [178bf2c5e4](https://linux-hardware.org/?probe=178bf2c5e4) | Mar 19, 2024 |
| Dell          | 0D6H9T A01                  | [c3691d0e66](https://linux-hardware.org/?probe=c3691d0e66) | Mar 19, 2024 |
| MSI           | MS-B0A21                    | [e4301d435b](https://linux-hardware.org/?probe=e4301d435b) | Mar 18, 2024 |
| Lenovo        | 3752 NOK                    | [346e8ecb30](https://linux-hardware.org/?probe=346e8ecb30) | Mar 13, 2024 |
| Lenovo        | 3176 SDK0K17763 WIN 1801... | [51143831ed](https://linux-hardware.org/?probe=51143831ed) | Mar 12, 2024 |
| HP            | 2171                        | [83cba3a447](https://linux-hardware.org/?probe=83cba3a447) | Mar 11, 2024 |
| ASUSTek       | PRIME B450M-A II            | [c37a273452](https://linux-hardware.org/?probe=c37a273452) | Mar 11, 2024 |
| ASUSTek       | H110M-K                     | [321f393354](https://linux-hardware.org/?probe=321f393354) | Mar 10, 2024 |
| Intel         | DG31PR AAE39516-300         | [787913150f](https://linux-hardware.org/?probe=787913150f) | Mar 10, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [7bd68b9029](https://linux-hardware.org/?probe=7bd68b9029) | Mar 10, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [32f4bd1301](https://linux-hardware.org/?probe=32f4bd1301) | Mar 10, 2024 |
| Unknown       | Intel X79                   | [221191b973](https://linux-hardware.org/?probe=221191b973) | Mar 09, 2024 |
| Gigabyte      | B75-D3V                     | [52cebe0303](https://linux-hardware.org/?probe=52cebe0303) | Mar 08, 2024 |
| ASUSTek       | P7P55D                      | [21057a4ccd](https://linux-hardware.org/?probe=21057a4ccd) | Mar 08, 2024 |
| HP            | 212B                        | [781ec8e8f8](https://linux-hardware.org/?probe=781ec8e8f8) | Mar 07, 2024 |
| Dell          | 0NC2VH A01                  | [3b3cdc41db](https://linux-hardware.org/?probe=3b3cdc41db) | Mar 07, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [a04cc41ec5](https://linux-hardware.org/?probe=a04cc41ec5) | Mar 07, 2024 |
| Biostar       | H310MHC2                    | [29b173907b](https://linux-hardware.org/?probe=29b173907b) | Mar 06, 2024 |
| MSI           | X570-A PRO                  | [551069870d](https://linux-hardware.org/?probe=551069870d) | Mar 05, 2024 |
| MSI           | B350 PC MATE                | [8e5587f137](https://linux-hardware.org/?probe=8e5587f137) | Mar 05, 2024 |
| Acer          | EQ45LM                      | [876c209627](https://linux-hardware.org/?probe=876c209627) | Mar 04, 2024 |
| ASUSTek       | PRIME B550M-A               | [406bdeb1e8](https://linux-hardware.org/?probe=406bdeb1e8) | Mar 04, 2024 |
| Pegatron      | BYT-X1                      | [2e817a0b80](https://linux-hardware.org/?probe=2e817a0b80) | Mar 03, 2024 |
| ASUSTek       | P5Q                         | [93b54d8b77](https://linux-hardware.org/?probe=93b54d8b77) | Mar 02, 2024 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [a87711bf87](https://linux-hardware.org/?probe=a87711bf87) | Mar 01, 2024 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [cbc637aa6a](https://linux-hardware.org/?probe=cbc637aa6a) | Mar 01, 2024 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [29c944d669](https://linux-hardware.org/?probe=29c944d669) | Feb 29, 2024 |
| ASUSTek       | P5LD2                       | [db694867b8](https://linux-hardware.org/?probe=db694867b8) | Feb 25, 2024 |
| ASUSTek       | A88XM-A                     | [0213a33c8b](https://linux-hardware.org/?probe=0213a33c8b) | Feb 25, 2024 |
| ASUSTek       | PRIME B450M-A II            | [2ee09e9d30](https://linux-hardware.org/?probe=2ee09e9d30) | Feb 24, 2024 |
| Dell          | 014GRG A03                  | [17454c7fbf](https://linux-hardware.org/?probe=17454c7fbf) | Feb 22, 2024 |
| ASUSTek       | TUF B450M-PRO GAMING        | [346ff4be29](https://linux-hardware.org/?probe=346ff4be29) | Feb 21, 2024 |
| Gigabyte      | Z390 UD                     | [81ce4601b2](https://linux-hardware.org/?probe=81ce4601b2) | Feb 21, 2024 |
| ASUSTek       | M4N68T-M-LE-V2              | [5ff0972f57](https://linux-hardware.org/?probe=5ff0972f57) | Feb 20, 2024 |
| Acer          | EQ45LM                      | [295ed7c12d](https://linux-hardware.org/?probe=295ed7c12d) | Feb 19, 2024 |
| ASUSTek       | P5KPL-AM EPU                | [2049db8150](https://linux-hardware.org/?probe=2049db8150) | Feb 19, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [522f55db74](https://linux-hardware.org/?probe=522f55db74) | Feb 18, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [93992c9687](https://linux-hardware.org/?probe=93992c9687) | Feb 18, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS D4    | [f9c4c79116](https://linux-hardware.org/?probe=f9c4c79116) | Feb 18, 2024 |
| ASUSTek       | PRIME X370-PRO              | [98c654fd9c](https://linux-hardware.org/?probe=98c654fd9c) | Feb 18, 2024 |
| ASRock        | 970 Pro3 R2.0               | [bb647c01d4](https://linux-hardware.org/?probe=bb647c01d4) | Feb 18, 2024 |
| HP            | 339B                        | [4f6aa657ef](https://linux-hardware.org/?probe=4f6aa657ef) | Feb 18, 2024 |
| Gigabyte      | Z690 AORUS PRO              | [6b11953f07](https://linux-hardware.org/?probe=6b11953f07) | Feb 18, 2024 |
| HP            | 2215                        | [dcdc271971](https://linux-hardware.org/?probe=dcdc271971) | Feb 18, 2024 |
| HP            | Compaq 6005 Pro SFF PC      | [16de46e6cf](https://linux-hardware.org/?probe=16de46e6cf) | Feb 18, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [966e0998a7](https://linux-hardware.org/?probe=966e0998a7) | Feb 15, 2024 |
| Gigabyte      | G41MT-ES2L                  | [60cdce8ae3](https://linux-hardware.org/?probe=60cdce8ae3) | Feb 14, 2024 |
| HP            | 8055                        | [c9502cd080](https://linux-hardware.org/?probe=c9502cd080) | Feb 13, 2024 |
| ASUSTek       | P5G41-M LE                  | [bb4aa86fa0](https://linux-hardware.org/?probe=bb4aa86fa0) | Feb 13, 2024 |
| ASUSTek       | P5G41-M LE                  | [16ea131211](https://linux-hardware.org/?probe=16ea131211) | Feb 10, 2024 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [437af6a442](https://linux-hardware.org/?probe=437af6a442) | Feb 10, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [b60ad9d7c8](https://linux-hardware.org/?probe=b60ad9d7c8) | Feb 09, 2024 |
| ASUSTek       | SABERTOOTH X58              | [2eda41290c](https://linux-hardware.org/?probe=2eda41290c) | Feb 09, 2024 |
| Acer          | EQ45LM                      | [0f040d7ea3](https://linux-hardware.org/?probe=0f040d7ea3) | Feb 09, 2024 |
| HP            | 3646h                       | [458c563fc1](https://linux-hardware.org/?probe=458c563fc1) | Feb 07, 2024 |
| Gigabyte      | F2A55M-S1                   | [527a67ba4f](https://linux-hardware.org/?probe=527a67ba4f) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [82733ca802](https://linux-hardware.org/?probe=82733ca802) | Feb 05, 2024 |
| MSI           | 2AE0                        | [dd1f107447](https://linux-hardware.org/?probe=dd1f107447) | Feb 04, 2024 |
| Medion        | Z170H4-EA                   | [17c714c6b5](https://linux-hardware.org/?probe=17c714c6b5) | Feb 02, 2024 |
| HP            | 8055                        | [1eec2a37ce](https://linux-hardware.org/?probe=1eec2a37ce) | Feb 02, 2024 |
| Foxconn       | 2ADA                        | [e92639ba10](https://linux-hardware.org/?probe=e92639ba10) | Feb 02, 2024 |
| ASUSTek       | F2A85-M LE                  | [680ba020e2](https://linux-hardware.org/?probe=680ba020e2) | Feb 02, 2024 |
| ASRock        | H77 Pro4-M                  | [794e5341d9](https://linux-hardware.org/?probe=794e5341d9) | Feb 01, 2024 |
| ASRock        | A320M-HDV R4.0              | [9262af6ace](https://linux-hardware.org/?probe=9262af6ace) | Jan 31, 2024 |
| ASUSTek       | P8Z77-V LX                  | [011fd25549](https://linux-hardware.org/?probe=011fd25549) | Jan 31, 2024 |
| Intel         | DH55PJ AAE93812-302         | [acc04ef6ef](https://linux-hardware.org/?probe=acc04ef6ef) | Jan 31, 2024 |
| Biostar       | H610MH                      | [fb0234d450](https://linux-hardware.org/?probe=fb0234d450) | Jan 31, 2024 |
| Biostar       | NF61S-M2A                   | [4b42e5cd37](https://linux-hardware.org/?probe=4b42e5cd37) | Jan 31, 2024 |
| MSI           | PRO X670-P WIFI             | [2640847c88](https://linux-hardware.org/?probe=2640847c88) | Jan 31, 2024 |
| Dell          | 0FM586                      | [a66d080473](https://linux-hardware.org/?probe=a66d080473) | Jan 31, 2024 |
| Acer          | Aspire TC-780               | [00c699c62c](https://linux-hardware.org/?probe=00c699c62c) | Jan 28, 2024 |
| ASRock        | B75M R2.0                   | [7a7e12dca2](https://linux-hardware.org/?probe=7a7e12dca2) | Jan 27, 2024 |
| Gigabyte      | H97-HD3                     | [92984a124e](https://linux-hardware.org/?probe=92984a124e) | Jan 27, 2024 |
| Gigabyte      | H410M H V3                  | [018db3f12a](https://linux-hardware.org/?probe=018db3f12a) | Jan 26, 2024 |
| Gigabyte      | H470M K                     | [644982a46f](https://linux-hardware.org/?probe=644982a46f) | Jan 26, 2024 |
| Gigabyte      | H81M-S1                     | [b727252ca9](https://linux-hardware.org/?probe=b727252ca9) | Jan 25, 2024 |
| Gigabyte      | EG41MF-US2H                 | [882d3605ed](https://linux-hardware.org/?probe=882d3605ed) | Jan 25, 2024 |
| Gigabyte      | GA-78LMT-S2P                | [066f355824](https://linux-hardware.org/?probe=066f355824) | Jan 25, 2024 |
| ASUSTek       | PRIME H510M-E               | [ea518cb09d](https://linux-hardware.org/?probe=ea518cb09d) | Jan 24, 2024 |
| ASRock        | B650M Pro RS                | [2d706981c5](https://linux-hardware.org/?probe=2d706981c5) | Jan 24, 2024 |
| Pegatron      | Benicia                     | [9a4be691fc](https://linux-hardware.org/?probe=9a4be691fc) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [f2919e84e4](https://linux-hardware.org/?probe=f2919e84e4) | Jan 22, 2024 |
| HP            | 82B4                        | [0eca4196b3](https://linux-hardware.org/?probe=0eca4196b3) | Jan 21, 2024 |
| ASRock        | FM2A85X-ITX                 | [30f6aa7ead](https://linux-hardware.org/?probe=30f6aa7ead) | Jan 20, 2024 |
| ASUSTek       | H81M-K                      | [5b51e88413](https://linux-hardware.org/?probe=5b51e88413) | Jan 20, 2024 |
| Dell          | 042P49 A01                  | [e164f495e7](https://linux-hardware.org/?probe=e164f495e7) | Jan 19, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [276a0b5785](https://linux-hardware.org/?probe=276a0b5785) | Jan 19, 2024 |
| HP            | 81B4 01                     | [967d9af55c](https://linux-hardware.org/?probe=967d9af55c) | Jan 19, 2024 |
| Gigabyte      | H610M K DDR4                | [5c9e5ec7aa](https://linux-hardware.org/?probe=5c9e5ec7aa) | Jan 18, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | [344b6767cd](https://linux-hardware.org/?probe=344b6767cd) | Jan 17, 2024 |
| MACHINIST     | E5-RS9 V1.11                | [2b48345368](https://linux-hardware.org/?probe=2b48345368) | Jan 17, 2024 |
| Gigabyte      | H61M-S2PV                   | [3baca805c4](https://linux-hardware.org/?probe=3baca805c4) | Jan 17, 2024 |
| EPoX Compu... | NF6100 + NF410 DDR2: MGF... | [ba08d6e05c](https://linux-hardware.org/?probe=ba08d6e05c) | Jan 17, 2024 |
| MSI           | A68HM-E33 V2                | [da97b5c9f5](https://linux-hardware.org/?probe=da97b5c9f5) | Jan 17, 2024 |
| Gigabyte      | EP35-DS3                    | [18f8b43855](https://linux-hardware.org/?probe=18f8b43855) | Jan 16, 2024 |
| ASRock        | Z390 Taichi                 | [84a79a7e97](https://linux-hardware.org/?probe=84a79a7e97) | Jan 16, 2024 |
| ASUSTek       | UN65U                       | [0c9b6c61f2](https://linux-hardware.org/?probe=0c9b6c61f2) | Jan 16, 2024 |
| Gigabyte      | H270M-D3H-CF                | [636ad953ab](https://linux-hardware.org/?probe=636ad953ab) | Jan 16, 2024 |
| ASRock        | H81M-VG4 R2.0               | [4854968095](https://linux-hardware.org/?probe=4854968095) | Jan 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | [122b72e9f2](https://linux-hardware.org/?probe=122b72e9f2) | Jan 15, 2024 |
| Dell          | 0KC9NP A01                  | [71596d8f5f](https://linux-hardware.org/?probe=71596d8f5f) | Jan 12, 2024 |
| ASRock        | H110M-HDV                   | [5f7f485a15](https://linux-hardware.org/?probe=5f7f485a15) | Jan 12, 2024 |
| Gigabyte      | H310M M.2 x.x               | [f67cc2282f](https://linux-hardware.org/?probe=f67cc2282f) | Jan 12, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [febf87bf81](https://linux-hardware.org/?probe=febf87bf81) | Jan 11, 2024 |
| GEEKOM        | Mini IT 8                   | [16b759767e](https://linux-hardware.org/?probe=16b759767e) | Jan 11, 2024 |
| MSI           | Z87I                        | [35114b37dd](https://linux-hardware.org/?probe=35114b37dd) | Jan 10, 2024 |
| Pegatron      | NARRA3                      | [08c60d9c7a](https://linux-hardware.org/?probe=08c60d9c7a) | Jan 10, 2024 |
| ASUSTek       | P8P67 EVO                   | [d54cf27190](https://linux-hardware.org/?probe=d54cf27190) | Jan 09, 2024 |
| Gigabyte      | GA-E350N-USB3               | [222f3e6908](https://linux-hardware.org/?probe=222f3e6908) | Jan 08, 2024 |
| ALDO          | C2016-BSWI-D2               | [1e3d4c2e55](https://linux-hardware.org/?probe=1e3d4c2e55) | Jan 08, 2024 |
| ASUSTek       | A4320A6420                  | [5df0f2025e](https://linux-hardware.org/?probe=5df0f2025e) | Jan 04, 2024 |
| Acer          | Veriton N4620G              | [f438d41562](https://linux-hardware.org/?probe=f438d41562) | Jan 03, 2024 |
| Acer          | WMCP78M                     | [5e254245ae](https://linux-hardware.org/?probe=5e254245ae) | Jan 03, 2024 |
| ASUSTek       | P7P55D                      | [23a30b2497](https://linux-hardware.org/?probe=23a30b2497) | Jan 01, 2024 |
| HP            | 8054                        | [5389720de6](https://linux-hardware.org/?probe=5389720de6) | Dec 31, 2023 |
| HP            | 339A                        | [f109c46a8a](https://linux-hardware.org/?probe=f109c46a8a) | Dec 31, 2023 |
| Dell          | 0GY6Y8 A02                  | [81e91658c9](https://linux-hardware.org/?probe=81e91658c9) | Dec 30, 2023 |
| Intel         | Thurley                     | [2ad7d27607](https://linux-hardware.org/?probe=2ad7d27607) | Dec 29, 2023 |
| HP            | 3029h                       | [de537af4ba](https://linux-hardware.org/?probe=de537af4ba) | Dec 28, 2023 |
| Dell          | 0DF42J A00                  | [2b8f841667](https://linux-hardware.org/?probe=2b8f841667) | Dec 27, 2023 |
| eMachines     | MCP61PM-GM                  | [08b1aaf187](https://linux-hardware.org/?probe=08b1aaf187) | Dec 27, 2023 |
| Lenovo        | Annapurna CRB NO DPK        | [7d003c702a](https://linux-hardware.org/?probe=7d003c702a) | Dec 27, 2023 |
| ASUSTek       | P5K Premium                 | [b1c8bc2127](https://linux-hardware.org/?probe=b1c8bc2127) | Dec 26, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [0516914d99](https://linux-hardware.org/?probe=0516914d99) | Dec 26, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [0535c48b0a](https://linux-hardware.org/?probe=0535c48b0a) | Dec 26, 2023 |
| HP            | 1495                        | [c8b50e17f9](https://linux-hardware.org/?probe=c8b50e17f9) | Dec 26, 2023 |
| Pegatron      | Eureka3                     | [0dfc8b6795](https://linux-hardware.org/?probe=0dfc8b6795) | Dec 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [5775a72a93](https://linux-hardware.org/?probe=5775a72a93) | Dec 25, 2023 |
| Lenovo        | MAHOBAY NOK                 | [f85a8a3b68](https://linux-hardware.org/?probe=f85a8a3b68) | Dec 25, 2023 |
| ASUSTek       | PRIME H410M-A               | [d6257b5255](https://linux-hardware.org/?probe=d6257b5255) | Dec 25, 2023 |
| Biostar       | A320MH                      | [0898691249](https://linux-hardware.org/?probe=0898691249) | Dec 24, 2023 |
| Lenovo        | ThinkCentre M81 5049RK4     | [9ea1bc22a1](https://linux-hardware.org/?probe=9ea1bc22a1) | Dec 24, 2023 |
| Intel         | H61                         | [a10f481c10](https://linux-hardware.org/?probe=a10f481c10) | Dec 24, 2023 |
| Dell          | 0WMJ54 A01                  | [ac0b6ab055](https://linux-hardware.org/?probe=ac0b6ab055) | Dec 23, 2023 |
| ASUSTek       | P7P55D-E                    | [dc2914021f](https://linux-hardware.org/?probe=dc2914021f) | Dec 23, 2023 |
| HP            | 18E7                        | [71f34bba13](https://linux-hardware.org/?probe=71f34bba13) | Dec 21, 2023 |
| ASUSTek       | PRIME Z690-P                | [72187eb090](https://linux-hardware.org/?probe=72187eb090) | Dec 21, 2023 |
| Intel         | H61                         | [01b739e240](https://linux-hardware.org/?probe=01b739e240) | Dec 20, 2023 |
| Gigabyte      | B450 GAMING X               | [28f3e414e2](https://linux-hardware.org/?probe=28f3e414e2) | Dec 17, 2023 |
| MSI           | MS-7255                     | [efdf3ede47](https://linux-hardware.org/?probe=efdf3ede47) | Dec 17, 2023 |
| Dell          | 053CWD A00                  | [6cee8cbfd7](https://linux-hardware.org/?probe=6cee8cbfd7) | Dec 17, 2023 |
| Gigabyte      | B75M-D3H                    | [f306ab4590](https://linux-hardware.org/?probe=f306ab4590) | Dec 17, 2023 |
| Intel         | H81                         | [9aaa6b2ab6](https://linux-hardware.org/?probe=9aaa6b2ab6) | Dec 16, 2023 |
| Dell          | 0HD5W2 A01                  | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| HP            | 8653 A                      | [186fc771e8](https://linux-hardware.org/?probe=186fc771e8) | Dec 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [45900bcfb2](https://linux-hardware.org/?probe=45900bcfb2) | Dec 16, 2023 |
| Dell          | 0C27VV A02                  | [94560c4ce8](https://linux-hardware.org/?probe=94560c4ce8) | Dec 15, 2023 |
| ASUSTek       | M4A78T-E                    | [f34b148b2e](https://linux-hardware.org/?probe=f34b148b2e) | Dec 14, 2023 |
| HP            | 1496                        | [a89ca6e62d](https://linux-hardware.org/?probe=a89ca6e62d) | Dec 14, 2023 |
| ASUSTek       | P8H61                       | [00f636bb09](https://linux-hardware.org/?probe=00f636bb09) | Dec 14, 2023 |
| HP            | 212B                        | [18d100b09c](https://linux-hardware.org/?probe=18d100b09c) | Dec 14, 2023 |
| ASUSTek       | P9X79-E WS                  | [5dd7c998ce](https://linux-hardware.org/?probe=5dd7c998ce) | Dec 14, 2023 |
| HP            | 18E4                        | [1dd0e805dc](https://linux-hardware.org/?probe=1dd0e805dc) | Dec 13, 2023 |
| Dell          | 0R790T A00                  | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| Dell          | 0HN7XN A00                  | [c85fd96dcb](https://linux-hardware.org/?probe=c85fd96dcb) | Dec 13, 2023 |
| Lenovo        | Unknown                     | [d49ddc416f](https://linux-hardware.org/?probe=d49ddc416f) | Dec 12, 2023 |
| ASRock        | G41M-VS3                    | [894c4cf9fb](https://linux-hardware.org/?probe=894c4cf9fb) | Dec 12, 2023 |
| Unknown       | Unknown                     | [c9eae3e15f](https://linux-hardware.org/?probe=c9eae3e15f) | Dec 12, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [2a6159034b](https://linux-hardware.org/?probe=2a6159034b) | Dec 12, 2023 |
| MSI           | H61M-E33                    | [6123a79100](https://linux-hardware.org/?probe=6123a79100) | Dec 12, 2023 |
| Gigabyte      | B150M-D3H-CF                | [a46aa4d97c](https://linux-hardware.org/?probe=a46aa4d97c) | Dec 11, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [0343e0a98e](https://linux-hardware.org/?probe=0343e0a98e) | Dec 11, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9e23503add](https://linux-hardware.org/?probe=9e23503add) | Dec 11, 2023 |
| Intel         | DQ57TM AAE70931-402         | [fa57e6edd3](https://linux-hardware.org/?probe=fa57e6edd3) | Dec 10, 2023 |
| HP            | 3032h                       | [ca8902be00](https://linux-hardware.org/?probe=ca8902be00) | Dec 10, 2023 |
| MSI           | 970A-G46                    | [86bd084c44](https://linux-hardware.org/?probe=86bd084c44) | Dec 10, 2023 |
| MSI           | B550-A PRO                  | [43b1cafae8](https://linux-hardware.org/?probe=43b1cafae8) | Dec 10, 2023 |
| ASUSTek       | B150M-A/M.2                 | [dd4ad4373b](https://linux-hardware.org/?probe=dd4ad4373b) | Dec 10, 2023 |
| MSI           | PRO X670-P WIFI             | [be0d6f2f74](https://linux-hardware.org/?probe=be0d6f2f74) | Dec 10, 2023 |
| HP            | 8433 11                     | [65bca719f6](https://linux-hardware.org/?probe=65bca719f6) | Dec 09, 2023 |
| HP            | 0B4Ch D                     | [d129c3b01f](https://linux-hardware.org/?probe=d129c3b01f) | Dec 09, 2023 |
| Intel         | DH61CR AAG14064-204         | [a319465535](https://linux-hardware.org/?probe=a319465535) | Dec 09, 2023 |
| ASUSTek       | F1A55-M LE R2.0             | [83885aa02c](https://linux-hardware.org/?probe=83885aa02c) | Dec 09, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [4202011d88](https://linux-hardware.org/?probe=4202011d88) | Dec 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [beb5466523](https://linux-hardware.org/?probe=beb5466523) | Dec 08, 2023 |
| Pegatron      | 3580                        | [580355d3da](https://linux-hardware.org/?probe=580355d3da) | Dec 08, 2023 |
| Dell          | 00V62H A00                  | [f26cee0fe0](https://linux-hardware.org/?probe=f26cee0fe0) | Dec 08, 2023 |
| Intel         | DG965SS AAD41678-304        | [186a397074](https://linux-hardware.org/?probe=186a397074) | Dec 08, 2023 |
| Dell          | 02YYK5 A01                  | [1989264cba](https://linux-hardware.org/?probe=1989264cba) | Dec 08, 2023 |
| Dell          | 0GM819                      | [5c9ffb0977](https://linux-hardware.org/?probe=5c9ffb0977) | Dec 07, 2023 |
| FIC           | K2MCP61P PCB                | [fe4889cc68](https://linux-hardware.org/?probe=fe4889cc68) | Dec 07, 2023 |
| AMI           | Intel                       | [d2e7be0ff3](https://linux-hardware.org/?probe=d2e7be0ff3) | Dec 07, 2023 |
| MSI           | B350M BAZOOKA               | [4b67bc0273](https://linux-hardware.org/?probe=4b67bc0273) | Dec 07, 2023 |
| Dell          | 0YXT71 A03                  | [a3080a2577](https://linux-hardware.org/?probe=a3080a2577) | Dec 06, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [0ab3c62102](https://linux-hardware.org/?probe=0ab3c62102) | Dec 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [9960314986](https://linux-hardware.org/?probe=9960314986) | Dec 06, 2023 |
| AMI           | Intel                       | [8649d088c6](https://linux-hardware.org/?probe=8649d088c6) | Dec 06, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [8c397afeca](https://linux-hardware.org/?probe=8c397afeca) | Dec 05, 2023 |
| MSI           | 2A9C                        | [2ae992c0d5](https://linux-hardware.org/?probe=2ae992c0d5) | Dec 05, 2023 |
| Gigabyte      | GA-970A-UD3                 | [08a2ed40a1](https://linux-hardware.org/?probe=08a2ed40a1) | Dec 05, 2023 |
| Lenovo        | ThinkCentre M81 0267A38     | [a9f041fc10](https://linux-hardware.org/?probe=a9f041fc10) | Dec 05, 2023 |
| Fujitsu       | JIH61Y3                     | [8aa3f5fa84](https://linux-hardware.org/?probe=8aa3f5fa84) | Dec 05, 2023 |
| Dell          | 0WMJ54 A01                  | [76f6609343](https://linux-hardware.org/?probe=76f6609343) | Dec 05, 2023 |
| Acer          | Aspire XC-704G              | [44c713b05d](https://linux-hardware.org/?probe=44c713b05d) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [d28a7f3ad6](https://linux-hardware.org/?probe=d28a7f3ad6) | Dec 04, 2023 |
| ASUSTek       | Z87M-PLUS                   | [be471e354a](https://linux-hardware.org/?probe=be471e354a) | Dec 04, 2023 |
| ASUSTek       | P5P800-VM                   | [dff0c991af](https://linux-hardware.org/?probe=dff0c991af) | Dec 04, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [e215f304c3](https://linux-hardware.org/?probe=e215f304c3) | Dec 03, 2023 |
| HP            | 1998                        | [14cb2b69d2](https://linux-hardware.org/?probe=14cb2b69d2) | Dec 03, 2023 |
| Gigabyte      | H77-DS3H                    | [4c97431f16](https://linux-hardware.org/?probe=4c97431f16) | Dec 03, 2023 |
| Dell          | 03NVJ6 A02                  | [7f9b2fa7e0](https://linux-hardware.org/?probe=7f9b2fa7e0) | Dec 03, 2023 |
| Dell          | 0C2XKD A01                  | [e946c07f76](https://linux-hardware.org/?probe=e946c07f76) | Dec 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [388cf45c84](https://linux-hardware.org/?probe=388cf45c84) | Dec 03, 2023 |
| Acer          | IPXHW-RL                    | [aa0f30e67f](https://linux-hardware.org/?probe=aa0f30e67f) | Dec 02, 2023 |
| HP            | 8299                        | [fb5b226159](https://linux-hardware.org/?probe=fb5b226159) | Dec 02, 2023 |
| Dell          | 07N90W A01                  | [53c34cdf7d](https://linux-hardware.org/?probe=53c34cdf7d) | Dec 02, 2023 |
| MSI           | B350 GAMING PLUS            | [883665fb17](https://linux-hardware.org/?probe=883665fb17) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [5ea999f7bc](https://linux-hardware.org/?probe=5ea999f7bc) | Dec 02, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | [00159f1b41](https://linux-hardware.org/?probe=00159f1b41) | Dec 01, 2023 |
| ASUSTek       | H97M-E                      | [9e60faee5f](https://linux-hardware.org/?probe=9e60faee5f) | Dec 01, 2023 |
| Intel         | H61 V1.5                    | [45487af3d7](https://linux-hardware.org/?probe=45487af3d7) | Dec 01, 2023 |
| Gigabyte      | GA-870A-UD3                 | [0ae66633bc](https://linux-hardware.org/?probe=0ae66633bc) | Dec 01, 2023 |
| Gigabyte      | B460M D3H                   | [b83f7a31ff](https://linux-hardware.org/?probe=b83f7a31ff) | Dec 01, 2023 |
| ASRock        | H310CM-HDV/M.2              | [4b91971e62](https://linux-hardware.org/?probe=4b91971e62) | Dec 01, 2023 |
| Dell          | 014GRG A03                  | [581d6ec42f](https://linux-hardware.org/?probe=581d6ec42f) | Nov 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [aa1896b627](https://linux-hardware.org/?probe=aa1896b627) | Nov 30, 2023 |
| Dell          | 0WK833                      | [f363206bab](https://linux-hardware.org/?probe=f363206bab) | Nov 30, 2023 |
| MSI           | A88X-G45 GAMING             | [c3ad03c61d](https://linux-hardware.org/?probe=c3ad03c61d) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [5cfd0eb0f5](https://linux-hardware.org/?probe=5cfd0eb0f5) | Nov 30, 2023 |
| HP            | 843B                        | [5a69492f49](https://linux-hardware.org/?probe=5a69492f49) | Nov 30, 2023 |
| ASRock        | B450 Pro4 R2.0              | [53fc7f6723](https://linux-hardware.org/?probe=53fc7f6723) | Nov 30, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [4747b76126](https://linux-hardware.org/?probe=4747b76126) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [01105932ac](https://linux-hardware.org/?probe=01105932ac) | Nov 30, 2023 |
| MSI           | B250M PRO-VD                | [e0dead14ab](https://linux-hardware.org/?probe=e0dead14ab) | Nov 29, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [bf1caf0dae](https://linux-hardware.org/?probe=bf1caf0dae) | Nov 29, 2023 |
| HP            | 8298                        | [f66cb29dd1](https://linux-hardware.org/?probe=f66cb29dd1) | Nov 29, 2023 |
| Unknown       | N15                         | [a968ec315f](https://linux-hardware.org/?probe=a968ec315f) | Nov 29, 2023 |
| ASRock        | J3355M                      | [a767ff37ed](https://linux-hardware.org/?probe=a767ff37ed) | Nov 29, 2023 |
| ASUSTek       | PRIME A520M-K               | [cd63a4710a](https://linux-hardware.org/?probe=cd63a4710a) | Nov 29, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | [8bc25c47be](https://linux-hardware.org/?probe=8bc25c47be) | Nov 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [655dc71f64](https://linux-hardware.org/?probe=655dc71f64) | Nov 29, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a97b3bd106](https://linux-hardware.org/?probe=a97b3bd106) | Nov 29, 2023 |
| HP            | 805D                        | [997f828456](https://linux-hardware.org/?probe=997f828456) | Nov 29, 2023 |
| MSI           | Z170A PC MATE               | [913553eac4](https://linux-hardware.org/?probe=913553eac4) | Nov 29, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [c70f79dd89](https://linux-hardware.org/?probe=c70f79dd89) | Nov 29, 2023 |
| Gigabyte      | H310M S2                    | [4cd53ef516](https://linux-hardware.org/?probe=4cd53ef516) | Nov 29, 2023 |
| Founder       | Q87H3-AM V:1.0              | [56a7ef0f8a](https://linux-hardware.org/?probe=56a7ef0f8a) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [bd474c263c](https://linux-hardware.org/?probe=bd474c263c) | Nov 29, 2023 |
| HP            | 8648                        | [f6804eecf5](https://linux-hardware.org/?probe=f6804eecf5) | Nov 29, 2023 |
| HP            | 8906 SMVB                   | [a94fe27744](https://linux-hardware.org/?probe=a94fe27744) | Nov 28, 2023 |
| MSI           | KA790GX                     | [5bc35f82f6](https://linux-hardware.org/?probe=5bc35f82f6) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c93b09ccf3](https://linux-hardware.org/?probe=c93b09ccf3) | Nov 28, 2023 |
| Unknown       | Unknown                     | [b4e8fd1ac2](https://linux-hardware.org/?probe=b4e8fd1ac2) | Nov 28, 2023 |
| Dell          | 0HD5W2 A01                  | [2627da2538](https://linux-hardware.org/?probe=2627da2538) | Nov 28, 2023 |
| HP            | 304Bh                       | [3cb20d232f](https://linux-hardware.org/?probe=3cb20d232f) | Nov 28, 2023 |
| ECS           | G31T-M9                     | [535a19c400](https://linux-hardware.org/?probe=535a19c400) | Nov 28, 2023 |
| Lenovo        | SDK0F82993 WIN              | [d9bc93a89f](https://linux-hardware.org/?probe=d9bc93a89f) | Nov 28, 2023 |
| Gigabyte      | 945GZM-S2                   | [0a673a3528](https://linux-hardware.org/?probe=0a673a3528) | Nov 28, 2023 |
| Dell          | 0T7D40 A01                  | [6c16a6716b](https://linux-hardware.org/?probe=6c16a6716b) | Nov 28, 2023 |
| Medion        | MS-7621                     | [18f32a871d](https://linux-hardware.org/?probe=18f32a871d) | Nov 28, 2023 |
| ASRock        | H81M-DGS R2.0               | [2196f5ec5e](https://linux-hardware.org/?probe=2196f5ec5e) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [2df2a6f5d8](https://linux-hardware.org/?probe=2df2a6f5d8) | Nov 28, 2023 |
| Dell          | 07KY25 A01                  | [f1905255d0](https://linux-hardware.org/?probe=f1905255d0) | Nov 28, 2023 |
| Dell          | 03NVJ6 A03                  | [2eae8e704b](https://linux-hardware.org/?probe=2eae8e704b) | Nov 28, 2023 |
| ASUSTek       | Z170-A                      | [d4488776c4](https://linux-hardware.org/?probe=d4488776c4) | Nov 27, 2023 |
| ASUSTek       | CM1435                      | [deceba2322](https://linux-hardware.org/?probe=deceba2322) | Nov 27, 2023 |
| ASUSTek       | F2A85-M                     | [0c272521ab](https://linux-hardware.org/?probe=0c272521ab) | Nov 27, 2023 |
| Acer          | Veriton X2632G V:1.0        | [0c50fc3c6f](https://linux-hardware.org/?probe=0c50fc3c6f) | Nov 27, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [a82d950345](https://linux-hardware.org/?probe=a82d950345) | Nov 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [d848c8ed0e](https://linux-hardware.org/?probe=d848c8ed0e) | Nov 27, 2023 |
| ASRock        | H61M-VG3                    | [8b7f6c2f5f](https://linux-hardware.org/?probe=8b7f6c2f5f) | Nov 27, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [c5f3edc9d1](https://linux-hardware.org/?probe=c5f3edc9d1) | Nov 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [cd7362b85e](https://linux-hardware.org/?probe=cd7362b85e) | Nov 27, 2023 |
| Dell          | 0F3KHR A00                  | [c744967be3](https://linux-hardware.org/?probe=c744967be3) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [ee22e39495](https://linux-hardware.org/?probe=ee22e39495) | Nov 27, 2023 |
| Gigabyte      | B75M-D3V                    | [142a3240d4](https://linux-hardware.org/?probe=142a3240d4) | Nov 27, 2023 |
| Foxconn       | 2ABF                        | [a5016a519f](https://linux-hardware.org/?probe=a5016a519f) | Nov 27, 2023 |
| ASUSTek       | H81M-K                      | [121db7e081](https://linux-hardware.org/?probe=121db7e081) | Nov 27, 2023 |
| HP            | 8056                        | [9972a0e20f](https://linux-hardware.org/?probe=9972a0e20f) | Nov 27, 2023 |
| HP            | 8184 X4                     | [0813228fc1](https://linux-hardware.org/?probe=0813228fc1) | Nov 27, 2023 |
| Gigabyte      | G31M-ES2L                   | [f3e5b85b92](https://linux-hardware.org/?probe=f3e5b85b92) | Nov 27, 2023 |
| ASUSTek       | PRIME J4005I-C              | [23f26e0c45](https://linux-hardware.org/?probe=23f26e0c45) | Nov 27, 2023 |
| Dell          | 00VTMF A01                  | [bb1a93e07b](https://linux-hardware.org/?probe=bb1a93e07b) | Nov 27, 2023 |
| HP            | 82F2 A01                    | [21ece36869](https://linux-hardware.org/?probe=21ece36869) | Nov 27, 2023 |
| HP            | 2AF7                        | [a366a85d8c](https://linux-hardware.org/?probe=a366a85d8c) | Nov 27, 2023 |
| AZW           | MINI S 10                   | [c0fda6103a](https://linux-hardware.org/?probe=c0fda6103a) | Nov 26, 2023 |
| Dell          | 0YP806 A01                  | [078d014e70](https://linux-hardware.org/?probe=078d014e70) | Nov 26, 2023 |
| ASRock        | B550M-ITX/ac                | [c28cfb7cd7](https://linux-hardware.org/?probe=c28cfb7cd7) | Nov 26, 2023 |
| HP            | 8704                        | [594422dbde](https://linux-hardware.org/?probe=594422dbde) | Nov 26, 2023 |
| HP            | 1497                        | [5922e57d93](https://linux-hardware.org/?probe=5922e57d93) | Nov 26, 2023 |
| Gigabyte      | P55-US3L                    | [fdb0f32546](https://linux-hardware.org/?probe=fdb0f32546) | Nov 26, 2023 |
| Gigabyte      | G41M-ES2L                   | [f2856297d6](https://linux-hardware.org/?probe=f2856297d6) | Nov 26, 2023 |
| Shenzhen M... | F7BAA                       | [a48bfbc481](https://linux-hardware.org/?probe=a48bfbc481) | Nov 26, 2023 |
| Dell          | 0200DY A02                  | [7d5df62892](https://linux-hardware.org/?probe=7d5df62892) | Nov 26, 2023 |
| MSI           | A68HM-E33 V2                | [9247159905](https://linux-hardware.org/?probe=9247159905) | Nov 26, 2023 |
| HP            | 0B54h D                     | [0fccef5d79](https://linux-hardware.org/?probe=0fccef5d79) | Nov 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Acer          | Veriton M290                | [30dd8ffe84](https://linux-hardware.org/?probe=30dd8ffe84) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-P                | [b25d830579](https://linux-hardware.org/?probe=b25d830579) | Nov 26, 2023 |
| ASRock        | G41M-GS3                    | [0e679ecab4](https://linux-hardware.org/?probe=0e679ecab4) | Nov 26, 2023 |
| HP            | 8055                        | [88122b7512](https://linux-hardware.org/?probe=88122b7512) | Nov 26, 2023 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [d384af59f3](https://linux-hardware.org/?probe=d384af59f3) | Nov 26, 2023 |
| Huanan        | X99-BD4 V1.1, NALEX         | [751dbeae2c](https://linux-hardware.org/?probe=751dbeae2c) | Nov 26, 2023 |
| Medion        | MS-7728                     | [1e13c1a36d](https://linux-hardware.org/?probe=1e13c1a36d) | Nov 26, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [33dabf03ca](https://linux-hardware.org/?probe=33dabf03ca) | Nov 26, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [66dac22b5a](https://linux-hardware.org/?probe=66dac22b5a) | Nov 26, 2023 |
| HP            | 3397                        | [a846952acf](https://linux-hardware.org/?probe=a846952acf) | Nov 26, 2023 |
| MSI           | H310M PRO-VH PLUS           | [f21d57f728](https://linux-hardware.org/?probe=f21d57f728) | Nov 26, 2023 |
| Acer          | Aspire X1920                | [c97acbf5df](https://linux-hardware.org/?probe=c97acbf5df) | Nov 26, 2023 |
| Biostar       | H61MLV2                     | [1e2b4c3878](https://linux-hardware.org/?probe=1e2b4c3878) | Nov 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [aa7fb6a279](https://linux-hardware.org/?probe=aa7fb6a279) | Nov 26, 2023 |
| ASUSTek       | A55BM-E                     | [28fe1a1fe1](https://linux-hardware.org/?probe=28fe1a1fe1) | Nov 26, 2023 |
| Gigabyte      | B560M DS3H AC               | [906f471cf6](https://linux-hardware.org/?probe=906f471cf6) | Nov 26, 2023 |
| HP            | 339A                        | [5cad333081](https://linux-hardware.org/?probe=5cad333081) | Nov 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [4f4c868c9a](https://linux-hardware.org/?probe=4f4c868c9a) | Nov 26, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [ef4ad69c79](https://linux-hardware.org/?probe=ef4ad69c79) | Nov 26, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [6cdf6e663e](https://linux-hardware.org/?probe=6cdf6e663e) | Nov 26, 2023 |
| Intel         | H61 V124A                   | [eaa125b476](https://linux-hardware.org/?probe=eaa125b476) | Nov 26, 2023 |
| Gigabyte      | AM1M-S2H                    | [c3bdc08988](https://linux-hardware.org/?probe=c3bdc08988) | Nov 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [15da0b054a](https://linux-hardware.org/?probe=15da0b054a) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1f874b5293](https://linux-hardware.org/?probe=1f874b5293) | Nov 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a3f4bbe816](https://linux-hardware.org/?probe=a3f4bbe816) | Nov 25, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [5c990c2d29](https://linux-hardware.org/?probe=5c990c2d29) | Nov 25, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [af8e097b69](https://linux-hardware.org/?probe=af8e097b69) | Nov 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [7514ce50b9](https://linux-hardware.org/?probe=7514ce50b9) | Nov 25, 2023 |
| ASRock        | H470M-ITX/ac                | [5b558c30c8](https://linux-hardware.org/?probe=5b558c30c8) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9c4c337fe9](https://linux-hardware.org/?probe=9c4c337fe9) | Nov 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [381486f3da](https://linux-hardware.org/?probe=381486f3da) | Nov 25, 2023 |
| MSI           | PRO B760M-P DDR4            | [462b5c65a7](https://linux-hardware.org/?probe=462b5c65a7) | Nov 25, 2023 |
| HP            | 339A                        | [35c70dde9e](https://linux-hardware.org/?probe=35c70dde9e) | Nov 25, 2023 |
| ASRock        | B550M-ITX/ac                | [fd893be7c7](https://linux-hardware.org/?probe=fd893be7c7) | Nov 25, 2023 |
| Dell          | OptiPlex 745                | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Gigabyte      | B85M-HD3                    | [5992237ea5](https://linux-hardware.org/?probe=5992237ea5) | Nov 15, 2023 |
| MSI           | A520M PRO                   | [b83b272494](https://linux-hardware.org/?probe=b83b272494) | Nov 06, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 6.6.2-desktop-1omv2390       | 405      | 98.78%  |
| 6.6.1-desktop-1omv2390       | 3        | 0.73%   |
| 6.7.0-desktop-0.rc2.1omv2390 | 1        | 0.24%   |
| 6.6.0-desktop-1omv2390       | 1        | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6.2   | 405      | 98.78%  |
| 6.6.1   | 3        | 0.73%   |
| 6.7.0   | 1        | 0.24%   |
| 6.6.0   | 1        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6     | 409      | 99.76%  |
| 6.7     | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 410      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 307      | 74.88%  |
| LXQt     | 69       | 16.83%  |
| GNOME    | 31       | 7.56%   |
| Cinnamon | 2        | 0.49%   |
| Unknown  | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 400      | 97.56%  |
| X11     | 10       | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 378      | 92.2%   |
| GDM     | 31       | 7.56%   |
| LightDM | 1        | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 215      | 52.44%  |
| ru_RU | 33       | 8.05%   |
| de_DE | 28       | 6.83%   |
| pl_PL | 24       | 5.85%   |
| it_IT | 18       | 4.39%   |
| fr_FR | 18       | 4.39%   |
| pt_BR | 11       | 2.68%   |
| es_ES | 10       | 2.44%   |
| en_GB | 9        | 2.2%    |
| es_AR | 5        | 1.22%   |
| es_MX | 4        | 0.98%   |
| ja_JP | 3        | 0.73%   |
| en_IN | 3        | 0.73%   |
| en_IL | 3        | 0.73%   |
| en_CA | 3        | 0.73%   |
| en_AU | 3        | 0.73%   |
| nb_NO | 2        | 0.49%   |
| fr_CA | 2        | 0.49%   |
| UTF-8 | 1        | 0.24%   |
| tr_TR | 1        | 0.24%   |
| ro_RO | 1        | 0.24%   |
| pt_PT | 1        | 0.24%   |
| nl_NL | 1        | 0.24%   |
| hu_HU | 1        | 0.24%   |
| fr_BE | 1        | 0.24%   |
| es_VE | 1        | 0.24%   |
| es_EC | 1        | 0.24%   |
| es_DO | 1        | 0.24%   |
| es_CR | 1        | 0.24%   |
| en_SG | 1        | 0.24%   |
| en_NZ | 1        | 0.24%   |
| de_CH | 1        | 0.24%   |
| de_AT | 1        | 0.24%   |
| cs_CZ | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 218      | 53.17%  |
| BIOS | 192      | 46.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 232      | 56.59%  |
| Ext4    | 167      | 40.73%  |
| Btrfs   | 5        | 1.22%   |
| Xfs     | 4        | 0.98%   |
| F2fs    | 1        | 0.24%   |
| Ext3    | 1        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 314      | 76.59%  |
| MBR  | 96       | 23.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 227      | 55.37%  |
| No        | 183      | 44.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 55.37%  |
| Yes       | 183      | 44.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 101      | 24.63%  |
| Gigabyte Technology                  | 65       | 15.85%  |
| Hewlett-Packard                      | 46       | 11.22%  |
| Dell                                 | 39       | 9.51%   |
| MSI                                  | 36       | 8.78%   |
| ASRock                               | 31       | 7.56%   |
| Acer                                 | 17       | 4.15%   |
| Lenovo                               | 12       | 2.93%   |
| Intel                                | 12       | 2.93%   |
| Fujitsu                              | 7        | 1.71%   |
| Unknown                              | 6        | 1.46%   |
| Pegatron                             | 5        | 1.22%   |
| Biostar                              | 5        | 1.22%   |
| Medion                               | 3        | 0.73%   |
| Foxconn                              | 3        | 0.73%   |
| Red Hat                              | 2        | 0.49%   |
| MouseComputer                        | 2        | 0.49%   |
| AMI                                  | 2        | 0.49%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.24%   |
| MAXSUN                               | 1        | 0.24%   |
| MACHINIST                            | 1        | 0.24%   |
| Lenovo Product                       | 1        | 0.24%   |
| Huanan                               | 1        | 0.24%   |
| GEEKOM                               | 1        | 0.24%   |
| Founder                              | 1        | 0.24%   |
| FIC                                  | 1        | 0.24%   |
| EPoX Computer                        | 1        | 0.24%   |
| eMachines                            | 1        | 0.24%   |
| ECS                                  | 1        | 0.24%   |
| Daten Tecnologia                     | 1        | 0.24%   |
| Centerm                              | 1        | 0.24%   |
| AZW                                  | 1        | 0.24%   |
| ALDO                                 | 1        | 0.24%   |
| AFOX                                 | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 7        | 1.71%   |
| ASUS All Series               | 5        | 1.22%   |
| Dell OptiPlex 9020            | 4        | 0.98%   |
| Dell OptiPlex 780             | 4        | 0.98%   |
| ASUS PRIME B550M-A            | 4        | 0.98%   |
| Acer Veriton L670G            | 4        | 0.98%   |
| MSI MS-7721                   | 3        | 0.73%   |
| HP EliteDesk 800 G2 DM 35W    | 3        | 0.73%   |
| Dell OptiPlex 7040            | 3        | 0.73%   |
| Dell OptiPlex 7010            | 3        | 0.73%   |
| ASUS P8Z77-V LX               | 3        | 0.73%   |
| ASRock FM2A88X Extreme6+      | 3        | 0.73%   |
| Red Hat KVM                   | 2        | 0.49%   |
| MSI MS-7D67                   | 2        | 0.49%   |
| MSI MS-7A34                   | 2        | 0.49%   |
| Intel H61                     | 2        | 0.49%   |
| HP Z440 Workstation           | 2        | 0.49%   |
| HP ProDesk 600 G2 SFF         | 2        | 0.49%   |
| HP Pavilion Desktop 590-p0xxx | 2        | 0.49%   |
| HP EliteDesk 800 G3 SFF       | 2        | 0.49%   |
| HP EliteDesk 800 G2 SFF       | 2        | 0.49%   |
| HP Compaq Pro 6300 MT         | 2        | 0.49%   |
| Gigabyte B85M-HD3             | 2        | 0.49%   |
| Gigabyte B450M DS3H V2        | 2        | 0.49%   |
| Gigabyte A320M-S2H            | 2        | 0.49%   |
| Dell OptiPlex 745             | 2        | 0.49%   |
| Dell OptiPlex 5040            | 2        | 0.49%   |
| Dell OptiPlex 3020            | 2        | 0.49%   |
| ASUS TUF B450M-PLUS GAMING    | 2        | 0.49%   |
| ASUS PRIME Z390M-PLUS         | 2        | 0.49%   |
| ASUS PRIME X370-PRO           | 2        | 0.49%   |
| ASUS PRIME H410M-A            | 2        | 0.49%   |
| ASUS PRIME B450M-A II         | 2        | 0.49%   |
| ASUS PRIME A520M-K            | 2        | 0.49%   |
| ASUS PRIME A320M-K            | 2        | 0.49%   |
| ASUS P7P55D                   | 2        | 0.49%   |
| ASUS P5Q                      | 2        | 0.49%   |
| ASUS P5G41-M LE               | 2        | 0.49%   |
| ASUS M5A97 R2.0               | 2        | 0.49%   |
| ASRock B450 Pro4 R2.0         | 2        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 31       | 7.56%   |
| ASUS PRIME         | 31       | 7.56%   |
| HP Compaq          | 14       | 3.41%   |
| HP EliteDesk       | 12       | 2.93%   |
| ASUS ROG           | 9        | 2.2%    |
| Acer Veriton       | 8        | 1.95%   |
| ASUS TUF           | 7        | 1.71%   |
| Unknown            | 7        | 1.71%   |
| Acer Aspire        | 6        | 1.46%   |
| HP ProDesk         | 5        | 1.22%   |
| HP Pavilion        | 5        | 1.22%   |
| Fujitsu ESPRIMO    | 5        | 1.22%   |
| ASUS All           | 5        | 1.22%   |
| Lenovo ThinkCentre | 4        | 0.98%   |
| Intel H61          | 4        | 0.98%   |
| Dell Inspiron      | 4        | 0.98%   |
| MSI MS-7721        | 3        | 0.73%   |
| Lenovo IdeaCentre  | 3        | 0.73%   |
| Gigabyte B450M     | 3        | 0.73%   |
| Gigabyte B450      | 3        | 0.73%   |
| ASUS P8Z77-V       | 3        | 0.73%   |
| ASRock FM2A88X     | 3        | 0.73%   |
| Red Hat KVM        | 2        | 0.49%   |
| MSI PRO            | 2        | 0.49%   |
| MSI MS-7D67        | 2        | 0.49%   |
| MSI MS-7A34        | 2        | 0.49%   |
| HP Z440            | 2        | 0.49%   |
| Gigabyte Z690      | 2        | 0.49%   |
| Gigabyte Z390      | 2        | 0.49%   |
| Gigabyte X570      | 2        | 0.49%   |
| Gigabyte H310M     | 2        | 0.49%   |
| Gigabyte B85M-HD3  | 2        | 0.49%   |
| Gigabyte A320M-S2H | 2        | 0.49%   |
| Foxconn Pro        | 2        | 0.49%   |
| Dell Vostro        | 2        | 0.49%   |
| ASUS SABERTOOTH    | 2        | 0.49%   |
| ASUS P7P55D        | 2        | 0.49%   |
| ASUS P5Q           | 2        | 0.49%   |
| ASUS P5K           | 2        | 0.49%   |
| ASUS P5G41-M       | 2        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 42       | 10.24%  |
| 2018 | 38       | 9.27%   |
| 2013 | 35       | 8.54%   |
| 2015 | 31       | 7.56%   |
| 2021 | 29       | 7.07%   |
| 2020 | 27       | 6.59%   |
| 2017 | 27       | 6.59%   |
| 2014 | 25       | 6.1%    |
| 2011 | 25       | 6.1%    |
| 2009 | 22       | 5.37%   |
| 2010 | 18       | 4.39%   |
| 2022 | 16       | 3.9%    |
| 2016 | 16       | 3.9%    |
| 2019 | 15       | 3.66%   |
| 2008 | 15       | 3.66%   |
| 2023 | 11       | 2.68%   |
| 2007 | 8        | 1.95%   |
| 2006 | 8        | 1.95%   |
| 2005 | 2        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 410      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 410      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 410      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 100      | 24.39%  |
| 4.01-8.0    | 94       | 22.93%  |
| 8.01-16.0   | 89       | 21.71%  |
| 3.01-4.0    | 68       | 16.59%  |
| 32.01-64.0  | 40       | 9.76%   |
| 24.01-32.0  | 9        | 2.2%    |
| 1.01-2.0    | 8        | 1.95%   |
| 64.01-256.0 | 1        | 0.24%   |
| 0.51-1.0    | 1        | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 256      | 62.44%  |
| 2.01-3.0 | 76       | 18.54%  |
| 0.51-1.0 | 62       | 15.12%  |
| 0.01-0.5 | 9        | 2.2%    |
| 3.01-4.0 | 4        | 0.98%   |
| 4.01-8.0 | 3        | 0.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 191      | 46.59%  |
| 2      | 108      | 26.34%  |
| 3      | 57       | 13.9%   |
| 4      | 21       | 5.12%   |
| 5      | 10       | 2.44%   |
| 0      | 10       | 2.44%   |
| 6      | 8        | 1.95%   |
| 7      | 3        | 0.73%   |
| 9      | 1        | 0.24%   |
| 8      | 1        | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 217      | 52.93%  |
| No        | 193      | 47.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 400      | 97.56%  |
| No        | 10       | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 245      | 59.76%  |
| Yes       | 165      | 40.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 299      | 72.93%  |
| Yes       | 111      | 27.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 66       | 16.1%   |
| Russia      | 48       | 11.71%  |
| Germany     | 37       | 9.02%   |
| Poland      | 34       | 8.29%   |
| Italy       | 23       | 5.61%   |
| France      | 22       | 5.37%   |
| Brazil      | 21       | 5.12%   |
| UK          | 14       | 3.41%   |
| Canada      | 12       | 2.93%   |
| Spain       | 10       | 2.44%   |
| Romania     | 9        | 2.2%    |
| Sweden      | 7        | 1.71%   |
| Japan       | 7        | 1.71%   |
| Hungary     | 7        | 1.71%   |
| Argentina   | 7        | 1.71%   |
| China       | 6        | 1.46%   |
| Australia   | 6        | 1.46%   |
| Mexico      | 5        | 1.22%   |
| Israel      | 5        | 1.22%   |
| Turkey      | 4        | 0.98%   |
| India       | 4        | 0.98%   |
| Serbia      | 3        | 0.73%   |
| Greece      | 3        | 0.73%   |
| Czechia     | 3        | 0.73%   |
| Belgium     | 3        | 0.73%   |
| Uruguay     | 2        | 0.49%   |
| Ukraine     | 2        | 0.49%   |
| Thailand    | 2        | 0.49%   |
| South Korea | 2        | 0.49%   |
| Singapore   | 2        | 0.49%   |
| Peru        | 2        | 0.49%   |
| Norway      | 2        | 0.49%   |
| Netherlands | 2        | 0.49%   |
| Morocco     | 2        | 0.49%   |
| Kenya       | 2        | 0.49%   |
| Kazakhstan  | 2        | 0.49%   |
| Jamaica     | 2        | 0.49%   |
| Venezuela   | 1        | 0.24%   |
| Taiwan      | 1        | 0.24%   |
| Switzerland | 1        | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Moscow          | 9        | 2.2%    |
| Citrus Heights  | 6        | 1.46%   |
| Warsaw          | 4        | 0.98%   |
| Târgu Mureş   | 4        | 0.98%   |
| Rome            | 4        | 0.98%   |
| Rio de Janeiro  | 4        | 0.98%   |
| Tucson          | 3        | 0.73%   |
| Toulouse        | 3        | 0.73%   |
| St Petersburg   | 3        | 0.73%   |
| Munich          | 3        | 0.73%   |
| Hemet           | 3        | 0.73%   |
| Berlin          | 3        | 0.73%   |
| Wroclaw         | 2        | 0.49%   |
| Wiesloch        | 2        | 0.49%   |
| Ulyanovsk       | 2        | 0.49%   |
| Tel Aviv        | 2        | 0.49%   |
| Spring Valley   | 2        | 0.49%   |
| Singapore       | 2        | 0.49%   |
| Sao Paulo       | 2        | 0.49%   |
| Samara          | 2        | 0.49%   |
| Rostov-on-Don   | 2        | 0.49%   |
| Paris           | 2        | 0.49%   |
| Oslo            | 2        | 0.49%   |
| Olesno          | 2        | 0.49%   |
| Novosibirsk     | 2        | 0.49%   |
| Montevideo      | 2        | 0.49%   |
| Miercurea-Ciuc  | 2        | 0.49%   |
| Mentor          | 2        | 0.49%   |
| Marseille       | 2        | 0.49%   |
| Madrid          | 2        | 0.49%   |
| Lima            | 2        | 0.49%   |
| Leipzig         | 2        | 0.49%   |
| Kronberg        | 2        | 0.49%   |
| Krasnodar       | 2        | 0.49%   |
| Krakow          | 2        | 0.49%   |
| Kingston        | 2        | 0.49%   |
| Jacksonville    | 2        | 0.49%   |
| Hickory         | 2        | 0.49%   |
| Greater Sudbury | 2        | 0.49%   |
| Denver          | 2        | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 123      | 153    | 17.75%  |
| Seagate             | 110      | 133    | 15.87%  |
| Kingston            | 65       | 72     | 9.38%   |
| Samsung Electronics | 61       | 76     | 8.8%    |
| Toshiba             | 38       | 40     | 5.48%   |
| Crucial             | 28       | 31     | 4.04%   |
| SanDisk             | 23       | 25     | 3.32%   |
| Hitachi             | 23       | 23     | 3.32%   |
| China               | 18       | 19     | 2.6%    |
| GOODRAM             | 14       | 15     | 2.02%   |
| A-DATA Technology   | 14       | 15     | 2.02%   |
| Intel               | 12       | 12     | 1.73%   |
| Unknown             | 10       | 10     | 1.44%   |
| SPCC                | 9        | 12     | 1.3%    |
| Patriot             | 9        | 11     | 1.3%    |
| Intenso             | 8        | 8      | 1.15%   |
| PNY                 | 6        | 7      | 0.87%   |
| JMicron Technology  | 6        | 6      | 0.87%   |
| SK hynix            | 5        | 6      | 0.72%   |
| Micron Technology   | 5        | 5      | 0.72%   |
| Maxtor              | 5        | 5      | 0.72%   |
| HPQ                 | 5        | 5      | 0.72%   |
| ASMT                | 5        | 6      | 0.72%   |
| Unknown             | 5        | 5      | 0.72%   |
| Apacer              | 4        | 4      | 0.58%   |
| Smartbuy            | 3        | 3      | 0.43%   |
| Silicon Motion      | 3        | 4      | 0.43%   |
| Netac               | 3        | 3      | 0.43%   |
| Lexar               | 3        | 3      | 0.43%   |
| KingDian            | 3        | 4      | 0.43%   |
| AMD                 | 3        | 3      | 0.43%   |
| TO Exter            | 2        | 2      | 0.29%   |
| Team                | 2        | 2      | 0.29%   |
| Reeinno             | 2        | 2      | 0.29%   |
| PNY USB             | 2        | 2      | 0.29%   |
| OCZ                 | 2        | 2      | 0.29%   |
| MSI                 | 2        | 2      | 0.29%   |
| LITEON              | 2        | 2      | 0.29%   |
| KIOXIA              | 2        | 2      | 0.29%   |
| KingFast            | 2        | 2      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 16       | 2.09%   |
| Kingston SA400S37240G 240GB SSD  | 13       | 1.69%   |
| Toshiba DT01ACA100 1TB           | 10       | 1.3%    |
| Kingston SA400S37120G 120GB SSD  | 9        | 1.17%   |
| Kingston SA400S37480G 480GB SSD  | 8        | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB   | 7        | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 0.78%   |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 0.78%   |
| SanDisk NVMe SSD Drive 1TB       | 6        | 0.78%   |
| Unknown SD/MMC/MS PRO 128GB      | 5        | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 0.65%   |
| HPQ BF450DASTK 450GB             | 5        | 0.65%   |
| Unknown                          | 5        | 0.65%   |
| Toshiba HDWD130 3TB              | 4        | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 0.52%   |
| Kingston SUV400S37120G 120GB SSD | 4        | 0.52%   |
| Crucial CT275MX300SSD1 275GB     | 4        | 0.52%   |
| Crucial CT240BX500SSD1 240GB     | 4        | 0.52%   |
| Crucial CT120BX500SSD1 120GB     | 4        | 0.52%   |
| ASMT 2115 128GB                  | 4        | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.39%   |
| WDC WD10PURX-64E5EY0 1TB         | 3        | 0.39%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 0.39%   |
| WDC WD10EZEX-00BBHA0 1TB         | 3        | 0.39%   |
| Toshiba MQ01ABD050V 500GB        | 3        | 0.39%   |
| Toshiba DT01ACA050 500GB         | 3        | 0.39%   |
| SPCC Solid State Disk 256GB      | 3        | 0.39%   |
| SPCC Solid State Disk 128GB      | 3        | 0.39%   |
| Seagate ST3500413AS 500GB        | 3        | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB   | 3        | 0.39%   |
| Seagate Expansion 2TB            | 3        | 0.39%   |
| SanDisk NVMe SSD Drive 500GB     | 3        | 0.39%   |
| Samsung SSD 980 1TB              | 3        | 0.39%   |
| Samsung SSD 970 EVO 250GB        | 3        | 0.39%   |
| Samsung SSD 860 QVO 1TB          | 3        | 0.39%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.39%   |
| Samsung HD321KJ 320GB            | 3        | 0.39%   |
| Kingston SNVS500G 500GB          | 3        | 0.39%   |
| Kingston SNV2S500G 500GB         | 3        | 0.39%   |
| JMicron Tech 250GB               | 3        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 108      | 129    | 34.18%  |
| Seagate             | 108      | 131    | 34.18%  |
| Toshiba             | 35       | 37     | 11.08%  |
| Hitachi             | 21       | 21     | 6.65%   |
| Samsung Electronics | 15       | 18     | 4.75%   |
| Unknown             | 5        | 5      | 1.58%   |
| Maxtor              | 5        | 5      | 1.58%   |
| HPQ                 | 5        | 5      | 1.58%   |
| JMicron Technology  | 3        | 3      | 0.95%   |
| TO Exter            | 2        | 2      | 0.63%   |
| HGST                | 2        | 2      | 0.63%   |
| WD MediaMax         | 1        | 1      | 0.32%   |
| KESU                | 1        | 1      | 0.32%   |
| Intenso             | 1        | 1      | 0.32%   |
| Inateck             | 1        | 1      | 0.32%   |
| Fujitsu             | 1        | 1      | 0.32%   |
| CIRAGO              | 1        | 1      | 0.32%   |
| Apple               | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 46       | 49     | 17.42%  |
| Samsung Electronics | 29       | 32     | 10.98%  |
| Crucial             | 23       | 25     | 8.71%   |
| China               | 18       | 19     | 6.82%   |
| GOODRAM             | 13       | 14     | 4.92%   |
| WDC                 | 12       | 12     | 4.55%   |
| SanDisk             | 12       | 13     | 4.55%   |
| SPCC                | 8        | 10     | 3.03%   |
| Intel               | 8        | 8      | 3.03%   |
| Patriot             | 7        | 9      | 2.65%   |
| A-DATA Technology   | 7        | 7      | 2.65%   |
| Intenso             | 6        | 6      | 2.27%   |
| ASMT                | 5        | 6      | 1.89%   |
| Unknown             | 5        | 5      | 1.89%   |
| PNY                 | 4        | 5      | 1.52%   |
| Micron Technology   | 4        | 4      | 1.52%   |
| Apacer              | 4        | 4      | 1.52%   |
| KingDian            | 3        | 4      | 1.14%   |
| Smartbuy            | 2        | 2      | 0.76%   |
| SK hynix            | 2        | 2      | 0.76%   |
| Reeinno             | 2        | 2      | 0.76%   |
| PNY USB             | 2        | 2      | 0.76%   |
| OCZ                 | 2        | 2      | 0.76%   |
| Netac               | 2        | 2      | 0.76%   |
| LITEON              | 2        | 2      | 0.76%   |
| KingFast            | 2        | 2      | 0.76%   |
| Hitachi             | 2        | 2      | 0.76%   |
| Fanxiang            | 2        | 2      | 0.76%   |
| Dogfish             | 2        | 2      | 0.76%   |
| AMD                 | 2        | 2      | 0.76%   |
| XrayDisk            | 1        | 2      | 0.38%   |
| Western             | 1        | 1      | 0.38%   |
| Verbatim            | 1        | 1      | 0.38%   |
| Vaseky              | 1        | 1      | 0.38%   |
| USB3.0              | 1        | 1      | 0.38%   |
| TSA                 | 1        | 1      | 0.38%   |
| Transcend           | 1        | 1      | 0.38%   |
| Toshiba             | 1        | 1      | 0.38%   |
| tecmiyo             | 1        | 1      | 0.38%   |
| TCSUNBOW            | 1        | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 250      | 365    | 43.94%  |
| SSD     | 209      | 283    | 36.73%  |
| NVMe    | 103      | 135    | 18.1%   |
| Unknown | 5        | 5      | 0.88%   |
| MMC     | 2        | 2      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 357      | 606    | 70.55%  |
| NVMe | 102      | 132    | 20.16%  |
| SAS  | 45       | 50     | 8.89%   |
| MMC  | 2        | 2      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 284      | 418    | 59.54%  |
| 0.51-1.0   | 125      | 147    | 26.21%  |
| 1.01-2.0   | 43       | 56     | 9.01%   |
| 2.01-3.0   | 9        | 9      | 1.89%   |
| 3.01-4.0   | 8        | 10     | 1.68%   |
| 4.01-10.0  | 6        | 6      | 1.26%   |
| 10.01-20.0 | 2        | 2      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 144      | 35.12%  |
| 101-250        | 78       | 19.02%  |
| 251-500        | 58       | 14.15%  |
| Unknown        | 28       | 6.83%   |
| 21-50          | 27       | 6.59%   |
| 501-1000       | 24       | 5.85%   |
| 51-100         | 24       | 5.85%   |
| 1001-2000      | 16       | 3.9%    |
| More than 3000 | 8        | 1.95%   |
| 2001-3000      | 3        | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 291      | 70.98%  |
| Unknown        | 28       | 6.83%   |
| 21-50          | 22       | 5.37%   |
| 0              | 19       | 4.63%   |
| 101-250        | 15       | 3.66%   |
| 51-100         | 13       | 3.17%   |
| 251-500        | 11       | 2.68%   |
| 2001-3000      | 3        | 0.73%   |
| 1001-2000      | 3        | 0.73%   |
| 501-1000       | 3        | 0.73%   |
| More than 3000 | 2        | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 5        | 5      | 3.79%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2        | 2      | 1.52%   |
| WDC WD5000AAKX-001CA0 500GB           | 2        | 2      | 1.52%   |
| WDC WD10EARS-22Y5B1 1TB               | 2        | 2      | 1.52%   |
| WDC WD10EADS-00L5B1 1TB               | 2        | 2      | 1.52%   |
| Toshiba MQ01ABD050V 500GB             | 2        | 2      | 1.52%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 1.52%   |
| Seagate ST3500418AS 500GB             | 2        | 2      | 1.52%   |
| Seagate ST3320613AS 320GB             | 2        | 2      | 1.52%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 3      | 1.52%   |
| Seagate ST1000DM003-1ER162 1TB        | 2        | 2      | 1.52%   |
| Samsung Electronics SSD 970 EVO 500GB | 2        | 2      | 1.52%   |
| Samsung Electronics SP2504C 250GB     | 2        | 2      | 1.52%   |
| Samsung Electronics HD321KJ 320GB     | 2        | 2      | 1.52%   |
| Hitachi HDS721010CLA332 1TB           | 2        | 2      | 1.52%   |
| Crucial CT275MX300SSD1 275GB          | 2        | 2      | 1.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 1      | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1        | 1      | 0.76%   |
| WDC WD800JB-32JJC0 80GB               | 1        | 1      | 0.76%   |
| WDC WD6401AALS-00L3B2 640GB           | 1        | 1      | 0.76%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-221CA1 500GB           | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-083CA1 500GB           | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-07U6AA1 500GB          | 1        | 1      | 0.76%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 0.76%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 0.76%   |
| WDC WD3200AAKS-61L9A0 320GB           | 1        | 1      | 0.76%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1        | 1      | 0.76%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 0.76%   |
| WDC WD2500YS-01SHB1 256GB             | 1        | 1      | 0.76%   |
| WDC WD2500AAKX-753CA1 250GB           | 1        | 1      | 0.76%   |
| WDC WD2500AAJS-60Z0A0 250GB           | 1        | 1      | 0.76%   |
| WDC WD20EURX-63T0FY0 2TB              | 1        | 2      | 0.76%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 1      | 0.76%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 0.76%   |
| WDC WD2000FYYZ-01UL1B1 2TB            | 1        | 1      | 0.76%   |
| WDC WD1600BEVT-60ZCT1 160GB           | 1        | 1      | 0.76%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1        | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 41       | 45     | 32.8%   |
| Seagate             | 35       | 39     | 28%     |
| Samsung Electronics | 10       | 12     | 8%      |
| Hitachi             | 7        | 7      | 5.6%    |
| Toshiba             | 6        | 6      | 4.8%    |
| Maxtor              | 3        | 3      | 2.4%    |
| Kingston            | 3        | 3      | 2.4%    |
| China               | 3        | 3      | 2.4%    |
| A-DATA Technology   | 3        | 3      | 2.4%    |
| Micron Technology   | 2        | 2      | 1.6%    |
| HGST                | 2        | 2      | 1.6%    |
| Crucial             | 2        | 2      | 1.6%    |
| WD MediaMax         | 1        | 1      | 0.8%    |
| SPCC                | 1        | 1      | 0.8%    |
| SanDisk             | 1        | 1      | 0.8%    |
| Reeinno             | 1        | 1      | 0.8%    |
| Intel               | 1        | 1      | 0.8%    |
| HUSKY               | 1        | 1      | 0.8%    |
| Apple               | 1        | 1      | 0.8%    |
| AMD                 | 1        | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 37       | 41     | 36.63%  |
| Seagate             | 35       | 39     | 34.65%  |
| Samsung Electronics | 9        | 10     | 8.91%   |
| Hitachi             | 7        | 7      | 6.93%   |
| Toshiba             | 6        | 6      | 5.94%   |
| Maxtor              | 3        | 3      | 2.97%   |
| HGST                | 2        | 2      | 1.98%   |
| WD MediaMax         | 1        | 1      | 0.99%   |
| Apple               | 1        | 1      | 0.99%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 95       | 110    | 79.17%  |
| SSD  | 22       | 22     | 18.33%  |
| NVMe | 3        | 3      | 2.5%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB          | 1        | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 349      | 607    | 68.7%   |
| Malfunc  | 115      | 135    | 22.64%  |
| Detected | 42       | 46     | 8.27%   |
| Failed   | 2        | 2      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 271      | 47.54%  |
| AMD                          | 121      | 21.23%  |
| Samsung Electronics          | 23       | 4.04%   |
| Kingston Technology Company  | 22       | 3.86%   |
| SanDisk                      | 21       | 3.68%   |
| ASMedia Technology           | 20       | 3.51%   |
| JMicron Technology           | 13       | 2.28%   |
| Nvidia                       | 12       | 2.11%   |
| Phison Electronics           | 11       | 1.93%   |
| Marvell Technology Group     | 11       | 1.93%   |
| Silicon Motion               | 8        | 1.4%    |
| MAXIO Technology (Hangzhou)  | 6        | 1.05%   |
| Micron/Crucial Technology    | 5        | 0.88%   |
| SK hynix                     | 4        | 0.7%    |
| ADATA Technology             | 4        | 0.7%    |
| Realtek Semiconductor        | 3        | 0.53%   |
| KIOXIA                       | 3        | 0.53%   |
| Broadcom / LSI               | 3        | 0.53%   |
| Shenzhen Longsys Electronics | 2        | 0.35%   |
| Micron Technology            | 2        | 0.35%   |
| VIA Technologies             | 1        | 0.18%   |
| Toshiba America Info Systems | 1        | 0.18%   |
| Silicon Image                | 1        | 0.18%   |
| Seagate Technology           | 1        | 0.18%   |
| Adaptec                      | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 60       | 8.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 30       | 4.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 27       | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23       | 3.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22       | 3.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 3.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 3.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.73%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 16       | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 2.3%    |
| Intel SATA Controller [RAID mode]                                                       | 15       | 2.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 1.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 1.29%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 1.15%   |
| AMD FCH SATA Controller D                                                               | 8        | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 7        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7        | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.01%   |
| AMD FCH IDE Controller                                                                  | 7        | 1.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.86%   |
| Nvidia MCP61 IDE                                                                        | 6        | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.86%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 5        | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.72%   |
| Phison E12 NVMe Controller                                                              | 5        | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 5        | 0.72%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 5        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.72%   |
| AMD 600 Series Chipset SATA Controller                                                  | 5        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 327      | 60.22%  |
| NVMe | 101      | 18.6%   |
| IDE  | 91       | 16.76%  |
| RAID | 22       | 4.05%   |
| SAS  | 1        | 0.18%   |
| SCSI | 1        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 277      | 67.56%  |
| AMD    | 133      | 32.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9        | 2.2%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 8        | 1.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 7        | 1.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 7        | 1.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 6        | 1.46%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 6        | 1.46%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 6        | 1.46%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6        | 1.46%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 5        | 1.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 5        | 1.22%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5        | 1.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4        | 0.98%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 4        | 0.98%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 4        | 0.98%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 4        | 0.98%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 3        | 0.73%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 3        | 0.73%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3        | 0.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3        | 0.73%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3        | 0.73%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 3        | 0.73%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 3        | 0.73%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3        | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 0.73%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 3        | 0.73%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 3        | 0.73%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 3        | 0.73%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3        | 0.73%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3        | 0.73%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3        | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 0.73%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 3        | 0.73%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 3        | 0.73%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3        | 0.73%   |
| AMD Ryzen 5 5600 6-Core Processor             | 3        | 0.73%   |
| AMD Ryzen 5 5500                              | 3        | 0.73%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 3        | 0.73%   |
| Intel Pentium CPU G645 @ 2.90GHz              | 2        | 0.49%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 88       | 21.46%  |
| Intel Core i7           | 35       | 8.54%   |
| AMD Ryzen 5             | 35       | 8.54%   |
| Intel Core i3           | 30       | 7.32%   |
| Intel Core 2 Duo        | 21       | 5.12%   |
| Other                   | 18       | 4.39%   |
| Intel Celeron           | 18       | 4.39%   |
| Intel Pentium           | 17       | 4.15%   |
| Intel Xeon              | 15       | 3.66%   |
| AMD Ryzen 7             | 14       | 3.41%   |
| AMD FX                  | 13       | 3.17%   |
| AMD A8                  | 12       | 2.93%   |
| Intel Pentium Dual-Core | 9        | 2.2%    |
| Intel Core 2 Quad       | 8        | 1.95%   |
| AMD A10                 | 7        | 1.71%   |
| AMD Ryzen 9             | 6        | 1.46%   |
| AMD Athlon              | 6        | 1.46%   |
| Intel Pentium Gold      | 5        | 1.22%   |
| AMD Ryzen 3             | 5        | 1.22%   |
| AMD Athlon 64 X2        | 5        | 1.22%   |
| Intel Core i9           | 4        | 0.98%   |
| Intel Core 2            | 4        | 0.98%   |
| AMD Phenom II X4        | 4        | 0.98%   |
| AMD Phenom II X2        | 4        | 0.98%   |
| AMD A4                  | 3        | 0.73%   |
| Intel Pentium Dual      | 2        | 0.49%   |
| AMD Ryzen 3 PRO         | 2        | 0.49%   |
| AMD PRO A10             | 2        | 0.49%   |
| AMD Phenom II X6        | 2        | 0.49%   |
| AMD E                   | 2        | 0.49%   |
| AMD Athlon X4           | 2        | 0.49%   |
| AMD Athlon Dual Core    | 2        | 0.49%   |
| AMD Athlon 64           | 2        | 0.49%   |
| AMD A6                  | 2        | 0.49%   |
| Intel Pentium Silver    | 1        | 0.24%   |
| Intel Pentium 4         | 1        | 0.24%   |
| Intel Genuine           | 1        | 0.24%   |
| AMD Ryzen 7 PRO         | 1        | 0.24%   |
| AMD Athlon II X4        | 1        | 0.24%   |
| AMD Athlon II X2        | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 157      | 38.29%  |
| 2      | 145      | 35.37%  |
| 6      | 57       | 13.9%   |
| 8      | 26       | 6.34%   |
| 1      | 7        | 1.71%   |
| 10     | 6        | 1.46%   |
| 12     | 4        | 0.98%   |
| 16     | 3        | 0.73%   |
| 3      | 3        | 0.73%   |
| 18     | 1        | 0.24%   |
| 14     | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 407      | 99.27%  |
| 6      | 1        | 0.24%   |
| 4      | 1        | 0.24%   |
| 2      | 1        | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 206      | 50.24%  |
| 1      | 204      | 49.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 410      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 291      | 70.98%  |
| 0x06001119 | 9        | 2.2%    |
| 0x0800820d | 8        | 1.95%   |
| 0x06003106 | 8        | 1.95%   |
| 0x0a50000d | 6        | 1.46%   |
| 0x0a50000c | 5        | 1.22%   |
| 0x0a20120a | 5        | 1.22%   |
| 0x08701021 | 5        | 1.22%   |
| 0x08108109 | 5        | 1.22%   |
| 0x08001138 | 5        | 1.22%   |
| 0x0a50000f | 4        | 0.98%   |
| 0x08701030 | 4        | 0.98%   |
| 0x06000822 | 4        | 0.98%   |
| 0x010000b6 | 4        | 0.98%   |
| 0x0a601206 | 3        | 0.73%   |
| 0x08101016 | 3        | 0.73%   |
| 0x06001116 | 3        | 0.73%   |
| 0x010000bf | 3        | 0.73%   |
| 0x0a601203 | 2        | 0.49%   |
| 0x0810100b | 2        | 0.49%   |
| 0x0700010b | 2        | 0.49%   |
| 0x0600611a | 2        | 0.49%   |
| 0x06000817 | 2        | 0.49%   |
| 0x06000613 | 2        | 0.49%   |
| 0x05000028 | 2        | 0.49%   |
| 0x03000027 | 2        | 0.49%   |
| 0x010000c8 | 2        | 0.49%   |
| 0x0a404102 | 1        | 0.24%   |
| 0x0a20120e | 1        | 0.24%   |
| 0x0a20102b | 1        | 0.24%   |
| 0x0a201016 | 1        | 0.24%   |
| 0x08600109 | 1        | 0.24%   |
| 0x08600106 | 1        | 0.24%   |
| 0x08600103 | 1        | 0.24%   |
| 0x08001129 | 1        | 0.24%   |
| 0x07030105 | 1        | 0.24%   |
| 0x06003109 | 1        | 0.24%   |
| 0x06003104 | 1        | 0.24%   |
| 0x0600081c | 1        | 0.24%   |
| 0x0600063d | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 43       | 10.49%  |
| Haswell          | 41       | 10%     |
| Penryn           | 37       | 9.02%   |
| IvyBridge        | 34       | 8.29%   |
| Skylake          | 28       | 6.83%   |
| Zen 3            | 24       | 5.85%   |
| SandyBridge      | 22       | 5.37%   |
| Piledriver       | 19       | 4.63%   |
| CometLake        | 15       | 3.66%   |
| Zen+             | 13       | 3.17%   |
| K10              | 13       | 3.17%   |
| Zen 2            | 12       | 2.93%   |
| Zen              | 12       | 2.93%   |
| Alderlake Hybrid | 12       | 2.93%   |
| Steamroller      | 10       | 2.44%   |
| Core             | 10       | 2.44%   |
| K8 Hammer        | 9        | 2.2%    |
| Westmere         | 7        | 1.71%   |
| Nehalem          | 7        | 1.71%   |
| Unknown          | 7        | 1.71%   |
| Bulldozer        | 6        | 1.46%   |
| Silvermont       | 4        | 0.98%   |
| Icelake          | 4        | 0.98%   |
| Goldmont plus    | 3        | 0.73%   |
| Tremont          | 2        | 0.49%   |
| K10 Llano        | 2        | 0.49%   |
| Jaguar           | 2        | 0.49%   |
| Gracemont        | 2        | 0.49%   |
| Goldmont         | 2        | 0.49%   |
| Excavator        | 2        | 0.49%   |
| Broadwell        | 2        | 0.49%   |
| Bobcat           | 2        | 0.49%   |
| Puma             | 1        | 0.24%   |
| NetBurst         | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 163      | 38.44%  |
| Nvidia                               | 130      | 30.66%  |
| AMD                                  | 126      | 29.72%  |
| Red Hat                              | 2        | 0.47%   |
| NVidia / SGS Thomson (Joint Venture) | 2        | 0.47%   |
| ATI Technologies                     | 1        | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23       | 5.31%   |
| Intel HD Graphics 530                                                       | 18       | 4.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 17       | 3.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17       | 3.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 15       | 3.46%   |
| Intel HD Graphics 630                                                       | 14       | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 2.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 10       | 2.31%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 2.08%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 9        | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 1.62%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.15%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 1.15%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 1.15%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5        | 1.15%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 1.15%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 1.15%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 0.92%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.92%   |
| Nvidia GM107GL [Quadro K2200]                                               | 4        | 0.92%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.92%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 4        | 0.92%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 4        | 0.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 0.69%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.69%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 3        | 0.69%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 0.69%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 3        | 0.69%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 3        | 0.69%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 0.69%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.69%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 3        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                          | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| 1 x Intel                                     | 138      | 33.66%  |
| 1 x Nvidia                                    | 119      | 29.02%  |
| 1 x AMD                                       | 113      | 27.56%  |
| 2 x Intel                                     | 14       | 3.41%   |
| 2 x AMD                                       | 9        | 2.2%    |
| Intel + Nvidia                                | 8        | 1.95%   |
| Intel + AMD                                   | 3        | 0.73%   |
| 1 x Red Hat                                   | 2        | 0.49%   |
| AMD + Nvidia                                  | 2        | 0.49%   |
| 1 x NVidia / SGS Thomson (Joint Venture)      | 1        | 0.24%   |
| Nvidia + NVidia / SGS Thomson (Joint Venture) | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 396      | 96.59%  |
| Unknown     | 8        | 1.95%   |
| Proprietary | 6        | 1.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 161      | 39.27%  |
| 1.01-2.0   | 56       | 13.66%  |
| 0.51-1.0   | 54       | 13.17%  |
| 0.01-0.5   | 50       | 12.2%   |
| 3.01-4.0   | 42       | 10.24%  |
| 7.01-8.0   | 16       | 3.9%    |
| 8.01-16.0  | 15       | 3.66%   |
| 5.01-6.0   | 10       | 2.44%   |
| 2.01-3.0   | 4        | 0.98%   |
| 4.01-5.0   | 1        | 0.24%   |
| 16.01-24.0 | 1        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 74       | 18.64%  |
| Hewlett-Packard      | 43       | 10.83%  |
| Goldstar             | 39       | 9.82%   |
| Dell                 | 36       | 9.07%   |
| Philips              | 25       | 6.3%    |
| AOC                  | 25       | 6.3%    |
| Acer                 | 21       | 5.29%   |
| Ancor Communications | 19       | 4.79%   |
| ASUSTek Computer     | 11       | 2.77%   |
| Lenovo               | 9        | 2.27%   |
| Iiyama               | 9        | 2.27%   |
| ViewSonic            | 8        | 2.02%   |
| BenQ                 | 7        | 1.76%   |
| Sony                 | 6        | 1.51%   |
| NEC Computers        | 6        | 1.51%   |
| HannStar             | 3        | 0.76%   |
| Eizo                 | 3        | 0.76%   |
| Unknown              | 2        | 0.5%    |
| Sharp                | 2        | 0.5%    |
| Sceptre Tech         | 2        | 0.5%    |
| RTK                  | 2        | 0.5%    |
| RHT                  | 2        | 0.5%    |
| MSI                  | 2        | 0.5%    |
| LG Electronics       | 2        | 0.5%    |
| HUAWEI               | 2        | 0.5%    |
| HKC                  | 2        | 0.5%    |
| GDH                  | 2        | 0.5%    |
| Fujitsu Siemens      | 2        | 0.5%    |
| Denver               | 2        | 0.5%    |
| ___                  | 1        | 0.25%   |
| Wacom                | 1        | 0.25%   |
| Vizio                | 1        | 0.25%   |
| Vestel Elektronik    | 1        | 0.25%   |
| TCL                  | 1        | 0.25%   |
| STA                  | 1        | 0.25%   |
| SKY                  | 1        | 0.25%   |
| SANYO                | 1        | 0.25%   |
| PZG                  | 1        | 0.25%   |
| PRI                  | 1        | 0.25%   |
| Pioneer              | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5        | 1.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 1.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 1.25%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5        | 1.25%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                  | 4        | 1%      |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 3        | 0.75%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                     | 3        | 0.75%   |
| Samsung Electronics SMBX2331 SAM076E 1920x1080 509x286mm 23.0-inch    | 2        | 0.5%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.5%    |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 2        | 0.5%    |
| RHT QEMU Monitor RHT1234 2048x1152 325x203mm 15.1-inch                | 2        | 0.5%    |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 2        | 0.5%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2        | 0.5%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2        | 0.5%    |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 2        | 0.5%    |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                  | 2        | 0.5%    |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 2        | 0.5%    |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 2        | 0.5%    |
| Hewlett-Packard 24yh HPN3504 1920x1080 528x297mm 23.9-inch            | 2        | 0.5%    |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 2        | 0.5%    |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 2        | 0.5%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 0.5%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.5%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 2        | 0.5%    |
| Goldstar L1953S GSM4B3E 1280x1024 338x270mm 17.0-inch                 | 2        | 0.5%    |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 2        | 0.5%    |
| Goldstar 24MB35 GSM5A49 1920x1080 510x290mm 23.1-inch                 | 2        | 0.5%    |
| GDH TV PHILCO GDH0030 3840x2160 708x398mm 32.0-inch                   | 2        | 0.5%    |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 2        | 0.5%    |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                     | 2        | 0.5%    |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 2        | 0.5%    |
| Dell E196FP DELA015 1280x1024 376x301mm 19.0-inch                     | 2        | 0.5%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 2        | 0.5%    |
| ASUSTek Computer VP278 AUS27AE 1920x1080 598x336mm 27.0-inch          | 2        | 0.5%    |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2        | 0.5%    |
| Ancor Communications MW201 ACI20B1 1680x1050 433x270mm 20.1-inch      | 2        | 0.5%    |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 408x255mm 18.9-inch  | 2        | 0.5%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.5%    |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 2        | 0.5%    |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 2        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 210      | 53.71%  |
| 3840x2160 (4K)     | 40       | 10.23%  |
| 1280x1024 (SXGA)   | 33       | 8.44%   |
| 1680x1050 (WSXGA+) | 23       | 5.88%   |
| 1366x768 (WXGA)    | 19       | 4.86%   |
| 1440x900 (WXGA+)   | 15       | 3.84%   |
| 2560x1440 (QHD)    | 12       | 3.07%   |
| 1920x1200 (WUXGA)  | 10       | 2.56%   |
| 1600x900 (HD+)     | 8        | 2.05%   |
| 1360x768           | 4        | 1.02%   |
| 2560x1080          | 3        | 0.77%   |
| 1920x540           | 3        | 0.77%   |
| 1024x768 (XGA)     | 3        | 0.77%   |
| 3440x1440          | 2        | 0.51%   |
| 2048x1152          | 2        | 0.51%   |
| 3520x1080          | 1        | 0.26%   |
| 2288x1287          | 1        | 0.26%   |
| 1600x1200          | 1        | 0.26%   |
| 1280x960           | 1        | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 57       | 14.36%  |
| 23      | 56       | 14.11%  |
| 21      | 56       | 14.11%  |
| 24      | 53       | 13.35%  |
| 19      | 33       | 8.31%   |
| 18      | 21       | 5.29%   |
| 22      | 15       | 3.78%   |
| 20      | 14       | 3.53%   |
| 17      | 14       | 3.53%   |
| 40      | 9        | 2.27%   |
| 31      | 9        | 2.27%   |
| Unknown | 9        | 2.27%   |
| 84      | 7        | 1.76%   |
| 54      | 6        | 1.51%   |
| 72      | 3        | 0.76%   |
| 34      | 3        | 0.76%   |
| 32      | 3        | 0.76%   |
| 25      | 3        | 0.76%   |
| 52      | 2        | 0.5%    |
| 46      | 2        | 0.5%    |
| 37      | 2        | 0.5%    |
| 29      | 2        | 0.5%    |
| 28      | 2        | 0.5%    |
| 26      | 2        | 0.5%    |
| 15      | 2        | 0.5%    |
| 13      | 2        | 0.5%    |
| 142     | 1        | 0.25%   |
| 85      | 1        | 0.25%   |
| 65      | 1        | 0.25%   |
| 64      | 1        | 0.25%   |
| 60      | 1        | 0.25%   |
| 49      | 1        | 0.25%   |
| 48      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 41      | 1        | 0.25%   |
| 12      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 160      | 40.71%  |
| 401-500        | 124      | 31.55%  |
| 351-400        | 18       | 4.58%   |
| 601-700        | 17       | 4.33%   |
| 301-350        | 16       | 4.07%   |
| 1001-1500      | 15       | 3.82%   |
| 801-900        | 11       | 2.8%    |
| 1501-2000      | 11       | 2.8%    |
| Unknown        | 9        | 2.29%   |
| 701-800        | 6        | 1.53%   |
| 201-300        | 3        | 0.76%   |
| 901-1000       | 2        | 0.51%   |
| More than 2000 | 1        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 278      | 71.65%  |
| 16/10   | 54       | 13.92%  |
| 5/4     | 32       | 8.25%   |
| 4/3     | 7        | 1.8%    |
| Unknown | 6        | 1.55%   |
| 21/9    | 5        | 1.29%   |
| 3/2     | 3        | 0.77%   |
| 32/9    | 2        | 0.52%   |
| 1.00    | 1        | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 144      | 36.36%  |
| 151-200        | 65       | 16.41%  |
| 301-350        | 60       | 15.15%  |
| 141-150        | 33       | 8.33%   |
| More than 1000 | 24       | 6.06%   |
| 251-300        | 23       | 5.81%   |
| 351-500        | 17       | 4.29%   |
| 501-1000       | 16       | 4.04%   |
| Unknown        | 9        | 2.27%   |
| 81-90          | 2        | 0.51%   |
| 111-120        | 2        | 0.51%   |
| 71-80          | 1        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 285      | 73.08%  |
| 101-120 | 69       | 17.69%  |
| 1-50    | 16       | 4.1%    |
| Unknown | 9        | 2.31%   |
| 121-160 | 7        | 1.79%   |
| 161-240 | 4        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 384      | 93.66%  |
| 2     | 16       | 3.9%    |
| 0     | 10       | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 264      | 48.09%  |
| Intel                           | 156      | 28.42%  |
| Qualcomm Atheros                | 34       | 6.19%   |
| Broadcom                        | 13       | 2.37%   |
| Ralink Technology               | 12       | 2.19%   |
| TP-Link                         | 11       | 2%      |
| Nvidia                          | 9        | 1.64%   |
| Ralink                          | 8        | 1.46%   |
| MediaTek                        | 6        | 1.09%   |
| Xiaomi                          | 3        | 0.55%   |
| Qualcomm Atheros Communications | 3        | 0.55%   |
| NetGear                         | 3        | 0.55%   |
| Marvell Technology Group        | 3        | 0.55%   |
| Broadcom Limited                | 3        | 0.55%   |
| Belkin Components               | 2        | 0.36%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.18%   |
| VIA Technologies                | 1        | 0.18%   |
| Senao                           | 1        | 0.18%   |
| Samsung Electronics             | 1        | 0.18%   |
| Padix (Rockfire)                | 1        | 0.18%   |
| OPPO Electronics                | 1        | 0.18%   |
| Motorola PCS                    | 1        | 0.18%   |
| Microsoft                       | 1        | 0.18%   |
| Interlogix.                     | 1        | 0.18%   |
| IMC Networks                    | 1        | 0.18%   |
| Huawei Technologies             | 1        | 0.18%   |
| HMD Global                      | 1        | 0.18%   |
| Emtec                           | 1        | 0.18%   |
| DisplayLink                     | 1        | 0.18%   |
| D-Link System                   | 1        | 0.18%   |
| D-Link                          | 1        | 0.18%   |
| ASUSTek Computer                | 1        | 0.18%   |
| ASIX Electronics                | 1        | 0.18%   |
| 3Com                            | 1        | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 209      | 34.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18       | 3%      |
| Intel I211 Gigabit Network Connection                                  | 16       | 2.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 14       | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 14       | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 12       | 2%      |
| Intel Ethernet Connection I217-LM                                      | 11       | 1.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 10       | 1.66%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 10       | 1.66%   |
| Realtek 802.11ac NIC                                                   | 9        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8        | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 8        | 1.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                        | 7        | 1.16%   |
| Intel Wi-Fi 6 AX200                                                    | 7        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                                   | 7        | 1.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 6        | 1%      |
| Intel Ethernet Controller I225-V                                       | 6        | 1%      |
| Nvidia MCP61 Ethernet                                                  | 5        | 0.83%   |
| Intel Wireless 7265                                                    | 5        | 0.83%   |
| Intel Wireless 7260                                                    | 5        | 0.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 4        | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 4        | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 4        | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4        | 0.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 0.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4        | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4        | 0.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3        | 0.5%    |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.5%    |
| Intel Ethernet Connection (2) I218-LM                                  | 3        | 0.5%    |
| Intel 82578DM Gigabit Network Connection                               | 3        | 0.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 51       | 30.36%  |
| Intel                           | 45       | 26.79%  |
| Qualcomm Atheros                | 18       | 10.71%  |
| Ralink Technology               | 12       | 7.14%   |
| TP-Link                         | 10       | 5.95%   |
| Ralink                          | 8        | 4.76%   |
| MediaTek                        | 6        | 3.57%   |
| Broadcom                        | 4        | 2.38%   |
| Qualcomm Atheros Communications | 3        | 1.79%   |
| NetGear                         | 3        | 1.79%   |
| Belkin Components               | 2        | 1.19%   |
| Senao                           | 1        | 0.6%    |
| Microsoft                       | 1        | 0.6%    |
| IMC Networks                    | 1        | 0.6%    |
| D-Link System                   | 1        | 0.6%    |
| D-Link                          | 1        | 0.6%    |
| ASUSTek Computer                | 1        | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10       | 5.88%   |
| Realtek 802.11ac NIC                                           | 9        | 5.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8        | 4.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8        | 4.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7        | 4.12%   |
| Ralink MT7601U Wireless Adapter                                | 7        | 4.12%   |
| Intel Wi-Fi 6 AX200                                            | 7        | 4.12%   |
| Intel Wireless 7265                                            | 5        | 2.94%   |
| Intel Wireless 7260                                            | 5        | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4        | 2.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4        | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4        | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 2.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 4        | 2.35%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4        | 2.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3        | 1.76%   |
| Qualcomm Atheros AR9271 802.11n                                | 3        | 1.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3        | 1.76%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2        | 1.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2        | 1.18%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 2        | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2        | 1.18%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                | 2        | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2        | 1.18%   |
| Intel Wireless 3165                                            | 2        | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 1.18%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2        | 1.18%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2        | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.59%   |
| TP-Link Archer T4U ver.3                                       | 1        | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.59%   |
| TP-Link 802.11ac NIC                                           | 1        | 0.59%   |
| Senao 802.11 n WLAN                                            | 1        | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 242      | 57.62%  |
| Intel                      | 122      | 29.05%  |
| Qualcomm Atheros           | 19       | 4.52%   |
| Nvidia                     | 9        | 2.14%   |
| Broadcom                   | 9        | 2.14%   |
| Xiaomi                     | 3        | 0.71%   |
| Marvell Technology Group   | 3        | 0.71%   |
| Broadcom Limited           | 3        | 0.71%   |
| ZTE WCDMA Technologies MSM | 1        | 0.24%   |
| VIA Technologies           | 1        | 0.24%   |
| TP-Link                    | 1        | 0.24%   |
| Samsung Electronics        | 1        | 0.24%   |
| OPPO Electronics           | 1        | 0.24%   |
| Huawei Technologies        | 1        | 0.24%   |
| HMD Global                 | 1        | 0.24%   |
| DisplayLink                | 1        | 0.24%   |
| ASIX Electronics           | 1        | 0.24%   |
| 3Com                       | 1        | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 209      | 48.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18       | 4.22%   |
| Intel I211 Gigabit Network Connection                                  | 16       | 3.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 14       | 3.28%   |
| Intel Ethernet Connection (2) I219-LM                                  | 14       | 3.28%   |
| Intel Ethernet Connection (2) I219-V                                   | 12       | 2.81%   |
| Intel Ethernet Connection I217-LM                                      | 11       | 2.58%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 10       | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8        | 1.87%   |
| Intel Ethernet Connection (7) I219-V                                   | 7        | 1.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 6        | 1.41%   |
| Intel Ethernet Controller I225-V                                       | 6        | 1.41%   |
| Nvidia MCP61 Ethernet                                                  | 5        | 1.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 4        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4        | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3        | 0.7%    |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.7%    |
| Intel Ethernet Connection (2) I218-LM                                  | 3        | 0.7%    |
| Intel 82578DM Gigabit Network Connection                               | 3        | 0.7%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3        | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.47%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.47%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.47%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.47%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 0.47%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 2        | 0.47%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                    | 1        | 0.23%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1        | 0.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.23%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 400      | 70.42%  |
| WiFi     | 164      | 28.87%  |
| Unknown  | 3        | 0.53%   |
| Modem    | 1        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 318      | 78.71%  |
| WiFi     | 86       | 21.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 298      | 72.68%  |
| 2     | 102      | 24.88%  |
| 3     | 5        | 1.22%   |
| 0     | 5        | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 269      | 65.61%  |
| Yes  | 141      | 34.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 40       | 35.71%  |
| Cambridge Silicon Radio         | 31       | 27.68%  |
| Realtek Semiconductor           | 10       | 8.93%   |
| ASUSTek Computer                | 7        | 6.25%   |
| Qualcomm Atheros Communications | 5        | 4.46%   |
| MediaTek                        | 4        | 3.57%   |
| IMC Networks                    | 4        | 3.57%   |
| Broadcom                        | 3        | 2.68%   |
| TP-Link                         | 2        | 1.79%   |
| Ralink                          | 1        | 0.89%   |
| Lite-On Technology              | 1        | 0.89%   |
| Integrated System Solution      | 1        | 0.89%   |
| Foxconn / Hon Hai               | 1        | 0.89%   |
| Apple                           | 1        | 0.89%   |
| Unknown                         | 1        | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31       | 27.68%  |
| Intel Bluetooth wireless interface                  | 11       | 9.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8        | 7.14%   |
| Intel AX200 Bluetooth                               | 7        | 6.25%   |
| Realtek Bluetooth Radio                             | 4        | 3.57%   |
| MediaTek Wireless_Device                            | 4        | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 2.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 2.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 2.68%   |
| Intel AX201 Bluetooth                               | 3        | 2.68%   |
| ASUS Bluetooth Radio                                | 3        | 2.68%   |
| TP-Link UB500 Adapter                               | 2        | 1.79%   |
| Realtek 802.11ac WLAN Adapter                       | 2        | 1.79%   |
| Intel AX210 Bluetooth                               | 2        | 1.79%   |
| IMC Networks Bluetooth Radio                        | 2        | 1.79%   |
| IMC Networks Bluetooth Device                       | 2        | 1.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 1.79%   |
| Realtek RTL8723B Bluetooth                          | 1        | 0.89%   |
| Ralink RT3290 Bluetooth                             | 1        | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 0.89%   |
| Lite-On Bluetooth Device                            | 1        | 0.89%   |
| Intel Bluetooth Device                              | 1        | 0.89%   |
| Intel AX211 Bluetooth                               | 1        | 0.89%   |
| Integrated System Solution Bluetooth Device         | 1        | 0.89%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 0.89%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 0.89%   |
| Broadcom Bluetooth 2.1 Device                       | 1        | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 0.89%   |
| ASUS Bluetooth Adapter                              | 1        | 0.89%   |
| ASUS ASUS USB-BT500                                 | 1        | 0.89%   |
| Apple Bluetooth Host Controller                     | 1        | 0.89%   |
| Unknown                                             | 1        | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 266      | 45.78%  |
| AMD                                          | 148      | 25.47%  |
| Nvidia                                       | 115      | 19.79%  |
| C-Media Electronics                          | 15       | 2.58%   |
| Creative Labs                                | 8        | 1.38%   |
| Generalplus Technology                       | 3        | 0.52%   |
| Tenx Technology                              | 2        | 0.34%   |
| Razer USA                                    | 2        | 0.34%   |
| Micro Star International                     | 2        | 0.34%   |
| Medeli Electronics                           | 2        | 0.34%   |
| Logitech                                     | 2        | 0.34%   |
| ASUSTek Computer                             | 2        | 0.34%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.17%   |
| Yamaha                                       | 1        | 0.17%   |
| XMOS                                         | 1        | 0.17%   |
| VIA Technologies                             | 1        | 0.17%   |
| JMTek                                        | 1        | 0.17%   |
| Giga-Byte Technology                         | 1        | 0.17%   |
| FiiO Electronics Technology                  | 1        | 0.17%   |
| Ensoniq                                      | 1        | 0.17%   |
| Emotiva                                      | 1        | 0.17%   |
| Corsair                                      | 1        | 0.17%   |
| BY EDIFIER                                   | 1        | 0.17%   |
| BR25                                         | 1        | 0.17%   |
| ATI Technologies                             | 1        | 0.17%   |
| Unknown                                      | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35       | 4.95%   |
| AMD Family 17h/19h HD Audio Controller                                     | 34       | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 31       | 4.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 30       | 4.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26       | 3.68%   |
| AMD FCH Azalia Controller                                                  | 26       | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25       | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24       | 3.39%   |
| Intel 200 Series PCH HD Audio                                              | 21       | 2.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20       | 2.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18       | 2.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 17       | 2.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 15       | 2.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 1.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 13       | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 1.84%   |
| Nvidia High Definition Audio Controller                                    | 11       | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 10       | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10       | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 1.41%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 10       | 1.41%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 1.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 7        | 0.99%   |
| Intel Comet Lake PCH-V cAVS                                                | 7        | 0.99%   |
| Intel Alder Lake-S HD Audio Controller                                     | 7        | 0.99%   |
| AMD Trinity HDMI Audio Controller                                          | 7        | 0.99%   |
| Nvidia MCP61 High Definition Audio                                         | 6        | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 5        | 0.71%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.71%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 5        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 82       | 17.26%  |
| Unknown                                 | 65       | 13.68%  |
| SK hynix                                | 52       | 10.95%  |
| Samsung Electronics                     | 48       | 10.11%  |
| Crucial                                 | 33       | 6.95%   |
| Corsair                                 | 29       | 6.11%   |
| Micron Technology                       | 28       | 5.89%   |
| G.Skill                                 | 22       | 4.63%   |
| A-DATA Technology                       | 14       | 2.95%   |
| Nanya Technology                        | 12       | 2.53%   |
| Team                                    | 9        | 1.89%   |
| Unknown                                 | 8        | 1.68%   |
| Ramaxel Technology                      | 7        | 1.47%   |
| AMD                                     | 7        | 1.47%   |
| GOODRAM                                 | 6        | 1.26%   |
| Patriot                                 | 5        | 1.05%   |
| Transcend                               | 3        | 0.63%   |
| Silicon Power                           | 3        | 0.63%   |
| Patriot Memory (PDP Systems)            | 3        | 0.63%   |
| Golden Empire                           | 3        | 0.63%   |
| Wilk                                    | 2        | 0.42%   |
| Unknown (ABCD)                          | 2        | 0.42%   |
| Red Hat                                 | 2        | 0.42%   |
| PNY                                     | 2        | 0.42%   |
| Essencore                               | 2        | 0.42%   |
| Unknown (89F7)                          | 1        | 0.21%   |
| Unknown (0x7FFF)                        | 1        | 0.21%   |
| Unknown (0x0E9D)                        | 1        | 0.21%   |
| Toshiba                                 | 1        | 0.21%   |
| Teikon                                  | 1        | 0.21%   |
| Teclast                                 | 1        | 0.21%   |
| TakeMS                                  | 1        | 0.21%   |
| Swissbit                                | 1        | 0.21%   |
| Silicon Power Computer & Communications | 1        | 0.21%   |
| S                                       | 1        | 0.21%   |
| Ramos Technology                        | 1        | 0.21%   |
| Qumo                                    | 1        | 0.21%   |
| Qimonda                                 | 1        | 0.21%   |
| PUSKILL                                 | 1        | 0.21%   |
| OCZ                                     | 1        | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 8        | 1.51%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 6        | 1.13%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 6        | 1.13%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 5        | 0.94%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 5        | 0.94%   |
| Unknown RAM Module 1GB DIMM                                  | 5        | 0.94%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                    | 5        | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 4        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 4        | 0.75%   |
| Samsung RAM M4 70T5663RZ3-CE6 2GB SODIMM DDR2 667MT/s        | 4        | 0.75%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s          | 4        | 0.75%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s       | 4        | 0.75%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 4        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 3        | 0.56%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s          | 3        | 0.56%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3        | 0.56%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s         | 3        | 0.56%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 3        | 0.56%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s          | 3        | 0.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 3        | 0.56%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 3        | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2        | 0.38%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 2        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 2        | 0.38%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 2        | 0.38%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                         | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                     | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                         | 2        | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 2        | 0.38%   |
| Transcend RAM JM1600KLH-16GK 8GB DIMM DDR3 1600MT/s          | 2        | 0.38%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s          | 2        | 0.38%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                   | 2        | 0.38%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2        | 0.38%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 2        | 0.38%   |
| SK hynix RAM HMA851U6JJR6N-VK 4GB DIMM DDR4 2667MT/s         | 2        | 0.38%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s         | 2        | 0.38%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 2        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 169      | 41.22%  |
| DDR3    | 151      | 36.83%  |
| DDR2    | 24       | 5.85%   |
| Unknown | 24       | 5.85%   |
| SDRAM   | 20       | 4.88%   |
| DDR     | 9        | 2.2%    |
| DDR5    | 8        | 1.95%   |
| RAM     | 2        | 0.49%   |
| LPDDR4  | 2        | 0.49%   |
| DRAM    | 1        | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 372      | 92.08%  |
| SODIMM | 31       | 7.67%   |
| RIMM   | 1        | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 159      | 35.25%  |
| 4096  | 136      | 30.16%  |
| 2048  | 70       | 15.52%  |
| 16384 | 49       | 10.86%  |
| 1024  | 22       | 4.88%   |
| 32768 | 11       | 2.44%   |
| 512   | 3        | 0.67%   |
| 12536 | 1        | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 91       | 20.27%  |
| 1333    | 59       | 13.14%  |
| 3200    | 37       | 8.24%   |
| 2400    | 33       | 7.35%   |
| 2667    | 30       | 6.68%   |
| 2133    | 23       | 5.12%   |
| Unknown | 19       | 4.23%   |
| 667     | 18       | 4.01%   |
| 800     | 17       | 3.79%   |
| 3600    | 16       | 3.56%   |
| 3733    | 8        | 1.78%   |
| 1800    | 8        | 1.78%   |
| 3400    | 7        | 1.56%   |
| 2666    | 7        | 1.56%   |
| 2933    | 5        | 1.11%   |
| 1866    | 5        | 1.11%   |
| 3066    | 4        | 0.89%   |
| 1867    | 4        | 0.89%   |
| 400     | 4        | 0.89%   |
| 6000    | 3        | 0.67%   |
| 5200    | 3        | 0.67%   |
| 3866    | 3        | 0.67%   |
| 3800    | 3        | 0.67%   |
| 2200    | 3        | 0.67%   |
| 1334    | 3        | 0.67%   |
| 1066    | 3        | 0.67%   |
| 3500    | 2        | 0.45%   |
| 3333    | 2        | 0.45%   |
| 3266    | 2        | 0.45%   |
| 3000    | 2        | 0.45%   |
| 2048    | 2        | 0.45%   |
| 1400    | 2        | 0.45%   |
| 5600    | 1        | 0.22%   |
| 4800    | 1        | 0.22%   |
| 4533    | 1        | 0.22%   |
| 4000    | 1        | 0.22%   |
| 3666    | 1        | 0.22%   |
| 3534    | 1        | 0.22%   |
| 3466    | 1        | 0.22%   |
| 3151    | 1        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 9        | 40.91%  |
| Brother Industries  | 6        | 27.27%  |
| Canon               | 4        | 18.18%  |
| Seiko Epson         | 2        | 9.09%   |
| Prolific Technology | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP LaserJet 1018                | 2        | 9.09%   |
| Canon LiDE 300                  | 2        | 9.09%   |
| Seiko Epson ET-2820 Series      | 1        | 4.55%   |
| Seiko Epson ET-2710 Series      | 1        | 4.55%   |
| Prolific PL2305 Parallel Port   | 1        | 4.55%   |
| HP LaserJet M402dn              | 1        | 4.55%   |
| HP Laser 107w                   | 1        | 4.55%   |
| HP DeskJet F4200 series         | 1        | 4.55%   |
| HP DeskJet 6940 series          | 1        | 4.55%   |
| HP DeskJet 4670 series          | 1        | 4.55%   |
| HP DeskJet 2700 series          | 1        | 4.55%   |
| HP DeskJet 2600 series          | 1        | 4.55%   |
| Canon PRO-100 series            | 1        | 4.55%   |
| Canon PIXMA MG3600 Series       | 1        | 4.55%   |
| Brother MFC-J480DW              | 1        | 4.55%   |
| Brother MFC-J1010DW             | 1        | 4.55%   |
| Brother HL-L2375DW series       | 1        | 4.55%   |
| Brother HL-2270DW Laser Printer | 1        | 4.55%   |
| Brother HL-2140 series          | 1        | 4.55%   |
| Brother DCP-L2510D series       | 1        | 4.55%   |

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


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 2        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 19       | 37.25%  |
| Microsoft                     | 4        | 7.84%   |
| Sunplus Innovation Technology | 3        | 5.88%   |
| Realtek Semiconductor         | 3        | 5.88%   |
| Microdia                      | 3        | 5.88%   |
| Chicony Electronics           | 3        | 5.88%   |
| Samsung Electronics           | 2        | 3.92%   |
| Linux Foundation              | 2        | 3.92%   |
| eMeet                         | 2        | 3.92%   |
| Z-Star Microelectronics       | 1        | 1.96%   |
| Novatek Microelectronics      | 1        | 1.96%   |
| Netchip Technology            | 1        | 1.96%   |
| Lenovo                        | 1        | 1.96%   |
| Jieli Technology              | 1        | 1.96%   |
| Generalplus Technology        | 1        | 1.96%   |
| GEMBIRD                       | 1        | 1.96%   |
| Creative Technology           | 1        | 1.96%   |
| Aveo Technology               | 1        | 1.96%   |
| Alcor Micro                   | 1        | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 6        | 11.76%  |
| Logitech HD Pro Webcam C920                | 5        | 9.8%    |
| Samsung Galaxy series, misc. (MTP mode)    | 2        | 3.92%   |
| Microsoft LifeCam VX-5000                  | 2        | 3.92%   |
| Logitech Webcam C310                       | 2        | 3.92%   |
| Linux Foundation EEM Gadget                | 2        | 3.92%   |
| Z-Star Lenovo ThinkCentre Web Camera       | 1        | 1.96%   |
| Sunplus PC Camera                          | 1        | 1.96%   |
| Sunplus Full HD webcam                     | 1        | 1.96%   |
| Sunplus 5Mega Webcam                       | 1        | 1.96%   |
| Realtek Webcam                             | 1        | 1.96%   |
| Realtek USB Camera                         | 1        | 1.96%   |
| Realtek FULL HD 1080P Webcam               | 1        | 1.96%   |
| Novatek HP High Definition 2MP Webcam      | 1        | 1.96%   |
| Netchip Nuroum V11                         | 1        | 1.96%   |
| Microsoft Xbox NUI Camera                  | 1        | 1.96%   |
| Microsoft LifeCam VX-700                   | 1        | 1.96%   |
| Microdia Sonix USB 2.0 Camera              | 1        | 1.96%   |
| Microdia Integrated Camera                 | 1        | 1.96%   |
| Microdia ACR010 USB Webcam                 | 1        | 1.96%   |
| Logitech StreamCam                         | 1        | 1.96%   |
| Logitech QuickCam E 3500                   | 1        | 1.96%   |
| Logitech QuickCam Communicate Deluxe/S7500 | 1        | 1.96%   |
| Logitech HD Webcam C510                    | 1        | 1.96%   |
| Logitech CrystalCam                        | 1        | 1.96%   |
| Logitech BRIO Ultra HD Webcam              | 1        | 1.96%   |
| Lenovo Lenovo 500 RGB Camera               | 1        | 1.96%   |
| Jieli USB PHY 2.0                          | 1        | 1.96%   |
| Generalplus GENERAL WEBCAM                 | 1        | 1.96%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 1.96%   |
| eMeet HD Webcam C970L                      | 1        | 1.96%   |
| eMeet HD Webcam C950                       | 1        | 1.96%   |
| Creative Live! Cam Optia                   | 1        | 1.96%   |
| Chicony WebCam                             | 1        | 1.96%   |
| Chicony USB2.0 HD UVC WebCam               | 1        | 1.96%   |
| Chicony HP WebCam                          | 1        | 1.96%   |
| Aveo Camera                                | 1        | 1.96%   |
| Alcor Micro 1080P-Webcam                   | 1        | 1.96%   |

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
| 0     | 375      | 91.46%  |
| 1     | 33       | 8.05%   |
| 3     | 1        | 0.24%   |
| 2     | 1        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 21       | 58.33%  |
| Multimedia controller    | 5        | 13.89%  |
| Unassigned class         | 4        | 11.11%  |
| Communication controller | 2        | 5.56%   |
| Network                  | 1        | 2.78%   |
| Net/wireless             | 1        | 2.78%   |
| Camera                   | 1        | 2.78%   |
| Bluetooth                | 1        | 2.78%   |


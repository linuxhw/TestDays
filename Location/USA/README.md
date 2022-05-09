Linux in USA - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Linux in USA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/USA/Desktop/README.md) and [notebooks](/Location/USA/Notebook/README.md).

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

Total: 36755

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7400               | Notebook    | [7214a2058e](https://linux-hardware.org/?probe=7214a2058e) | May 07, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [09480b1677](https://linux-hardware.org/?probe=09480b1677) | May 07, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [9ba6326bdc](https://linux-hardware.org/?probe=9ba6326bdc) | May 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [b345350038](https://linux-hardware.org/?probe=b345350038) | May 07, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [d5210f6852](https://linux-hardware.org/?probe=d5210f6852) | May 07, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [7e14e0a766](https://linux-hardware.org/?probe=7e14e0a766) | May 07, 2022 |
| HP            | 802F                        | Desktop     | [5afe279c1b](https://linux-hardware.org/?probe=5afe279c1b) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [d9c26e7eee](https://linux-hardware.org/?probe=d9c26e7eee) | May 07, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [047f75af38](https://linux-hardware.org/?probe=047f75af38) | May 07, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [f5c19a4d13](https://linux-hardware.org/?probe=f5c19a4d13) | May 07, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [256b60b267](https://linux-hardware.org/?probe=256b60b267) | May 07, 2022 |
| Google        | Droid                       | Notebook    | [422252faa5](https://linux-hardware.org/?probe=422252faa5) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Toshiba       | TECRA A50-E                 | Notebook    | [29935ac4c6](https://linux-hardware.org/?probe=29935ac4c6) | May 06, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [71d02059fa](https://linux-hardware.org/?probe=71d02059fa) | May 06, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [56676d23c1](https://linux-hardware.org/?probe=56676d23c1) | May 06, 2022 |
| Lenovo        | ThinkPad W540 20BG0011US    | Notebook    | [1679543d3d](https://linux-hardware.org/?probe=1679543d3d) | May 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3ad1c93995](https://linux-hardware.org/?probe=3ad1c93995) | May 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [53e5fa5fd0](https://linux-hardware.org/?probe=53e5fa5fd0) | May 06, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [6ae88a39dd](https://linux-hardware.org/?probe=6ae88a39dd) | May 06, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [4071a1a35e](https://linux-hardware.org/?probe=4071a1a35e) | May 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0ff6d83ec3](https://linux-hardware.org/?probe=0ff6d83ec3) | May 06, 2022 |
| Dell          | 025M63 A00                  | All in one  | [515f746557](https://linux-hardware.org/?probe=515f746557) | May 06, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [f9fa385bcf](https://linux-hardware.org/?probe=f9fa385bcf) | May 06, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [7fbe03b837](https://linux-hardware.org/?probe=7fbe03b837) | May 06, 2022 |
| HP            | Mini 110-1000               | Notebook    | [e1a5afc203](https://linux-hardware.org/?probe=e1a5afc203) | May 06, 2022 |
| Framework     | Laptop                      | Notebook    | [67c58248dd](https://linux-hardware.org/?probe=67c58248dd) | May 06, 2022 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [738ea70d2a](https://linux-hardware.org/?probe=738ea70d2a) | May 06, 2022 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [a97d89680b](https://linux-hardware.org/?probe=a97d89680b) | May 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [52d956751f](https://linux-hardware.org/?probe=52d956751f) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [0ca81980a3](https://linux-hardware.org/?probe=0ca81980a3) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | Notebook    | [710c086b29](https://linux-hardware.org/?probe=710c086b29) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | Notebook    | [76fb8bb966](https://linux-hardware.org/?probe=76fb8bb966) | May 06, 2022 |
| Google        | Panther                     | Desktop     | [4b7366ed94](https://linux-hardware.org/?probe=4b7366ed94) | May 06, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [43b827546c](https://linux-hardware.org/?probe=43b827546c) | May 06, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [955a89377b](https://linux-hardware.org/?probe=955a89377b) | May 06, 2022 |
| Dell          | Inspiron 5575               | Notebook    | [0240c458be](https://linux-hardware.org/?probe=0240c458be) | May 06, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [080b4f2667](https://linux-hardware.org/?probe=080b4f2667) | May 06, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [66a01dfd2d](https://linux-hardware.org/?probe=66a01dfd2d) | May 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [7e44142aac](https://linux-hardware.org/?probe=7e44142aac) | May 05, 2022 |
| Dell          | Precision 3520              | Notebook    | [2d5c4aa671](https://linux-hardware.org/?probe=2d5c4aa671) | May 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [8e99db77e1](https://linux-hardware.org/?probe=8e99db77e1) | May 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [9df718b88f](https://linux-hardware.org/?probe=9df718b88f) | May 05, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [a6fcd090d0](https://linux-hardware.org/?probe=a6fcd090d0) | May 05, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4d8cad2c31](https://linux-hardware.org/?probe=4d8cad2c31) | May 05, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [71c0c4f257](https://linux-hardware.org/?probe=71c0c4f257) | May 05, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [9e2f057ead](https://linux-hardware.org/?probe=9e2f057ead) | May 05, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [2ce796a070](https://linux-hardware.org/?probe=2ce796a070) | May 05, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [6452e690a7](https://linux-hardware.org/?probe=6452e690a7) | May 05, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [fcfb95470e](https://linux-hardware.org/?probe=fcfb95470e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f9bb1a20a9](https://linux-hardware.org/?probe=f9bb1a20a9) | May 05, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [071a56caf3](https://linux-hardware.org/?probe=071a56caf3) | May 05, 2022 |
| ASRock        | H77 Pro4-M                  | Desktop     | [6dbce2b58e](https://linux-hardware.org/?probe=6dbce2b58e) | May 05, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [35aa84c6f4](https://linux-hardware.org/?probe=35aa84c6f4) | May 05, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [791bf14da8](https://linux-hardware.org/?probe=791bf14da8) | May 05, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [3c83210e52](https://linux-hardware.org/?probe=3c83210e52) | May 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [be10abdbfc](https://linux-hardware.org/?probe=be10abdbfc) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [13c20da3be](https://linux-hardware.org/?probe=13c20da3be) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8496c35f54](https://linux-hardware.org/?probe=8496c35f54) | May 05, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [3112ea6d6a](https://linux-hardware.org/?probe=3112ea6d6a) | May 05, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [6dbe28a107](https://linux-hardware.org/?probe=6dbe28a107) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [60d50d3190](https://linux-hardware.org/?probe=60d50d3190) | May 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fa5e301933](https://linux-hardware.org/?probe=fa5e301933) | May 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [26feab407f](https://linux-hardware.org/?probe=26feab407f) | May 05, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [1c70ba9e33](https://linux-hardware.org/?probe=1c70ba9e33) | May 05, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [29abb73f0b](https://linux-hardware.org/?probe=29abb73f0b) | May 05, 2022 |
| Intel         | NUC8i7HNB J68197-503        | Mini pc     | [54e4287d25](https://linux-hardware.org/?probe=54e4287d25) | May 05, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [5be2ebf3e2](https://linux-hardware.org/?probe=5be2ebf3e2) | May 05, 2022 |
| Dell          | Studio 1749                 | Notebook    | [aa0fee4460](https://linux-hardware.org/?probe=aa0fee4460) | May 05, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [51cb15494c](https://linux-hardware.org/?probe=51cb15494c) | May 05, 2022 |
| Gigabyte      | B150N-GSM-CF                | Desktop     | [b49d3deec3](https://linux-hardware.org/?probe=b49d3deec3) | May 05, 2022 |
| Dell          | 0WG855                      | Desktop     | [da01c6ab1d](https://linux-hardware.org/?probe=da01c6ab1d) | May 04, 2022 |
| Google        | Candy                       | Notebook    | [d461281743](https://linux-hardware.org/?probe=d461281743) | May 04, 2022 |
| Dell          | Latitude 3420               | Notebook    | [9cb2524716](https://linux-hardware.org/?probe=9cb2524716) | May 04, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [e137e37282](https://linux-hardware.org/?probe=e137e37282) | May 04, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [57760ec318](https://linux-hardware.org/?probe=57760ec318) | May 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [b07b2b3c9d](https://linux-hardware.org/?probe=b07b2b3c9d) | May 04, 2022 |
| Azulle        | Access4                     | Stick pc    | [c54b619851](https://linux-hardware.org/?probe=c54b619851) | May 04, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [97fe4a05c4](https://linux-hardware.org/?probe=97fe4a05c4) | May 04, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [b007cf4ed2](https://linux-hardware.org/?probe=b007cf4ed2) | May 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ab2a599951](https://linux-hardware.org/?probe=ab2a599951) | May 04, 2022 |
| Azulle        | Access4                     | Stick pc    | [d8472da434](https://linux-hardware.org/?probe=d8472da434) | May 04, 2022 |
| HP            | Pavilion g7                 | Notebook    | [e213ff845c](https://linux-hardware.org/?probe=e213ff845c) | May 04, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [3150d3df19](https://linux-hardware.org/?probe=3150d3df19) | May 04, 2022 |
| Lenovo        | ThinkPad L412 0553A13       | Notebook    | [bd3cf16002](https://linux-hardware.org/?probe=bd3cf16002) | May 04, 2022 |
| Gigabyte      | P65                         | Notebook    | [0bbc07114a](https://linux-hardware.org/?probe=0bbc07114a) | May 04, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [540a55671c](https://linux-hardware.org/?probe=540a55671c) | May 04, 2022 |
| Acer          | Spin SP315-51               | Convertible | [b96494c3bc](https://linux-hardware.org/?probe=b96494c3bc) | May 04, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d9ec0c5eea](https://linux-hardware.org/?probe=d9ec0c5eea) | May 04, 2022 |
| ASRock        | A320M/ac                    | Desktop     | [297c3bf935](https://linux-hardware.org/?probe=297c3bf935) | May 04, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d9ed530aa9](https://linux-hardware.org/?probe=d9ed530aa9) | May 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6c1a4b1bc6](https://linux-hardware.org/?probe=6c1a4b1bc6) | May 04, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [99d850c205](https://linux-hardware.org/?probe=99d850c205) | May 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [978f98cef3](https://linux-hardware.org/?probe=978f98cef3) | May 04, 2022 |
| Dell          | Latitude E6530              | Notebook    | [089da6b706](https://linux-hardware.org/?probe=089da6b706) | May 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [404c22feca](https://linux-hardware.org/?probe=404c22feca) | May 04, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [c642093ad4](https://linux-hardware.org/?probe=c642093ad4) | May 04, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [f07e1c9d1c](https://linux-hardware.org/?probe=f07e1c9d1c) | May 04, 2022 |
| Alienware     | 17                          | Notebook    | [1a4cd056f8](https://linux-hardware.org/?probe=1a4cd056f8) | May 04, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [b6437729be](https://linux-hardware.org/?probe=b6437729be) | May 04, 2022 |
| HP            | 212B                        | Desktop     | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [fa58b1d93f](https://linux-hardware.org/?probe=fa58b1d93f) | May 04, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [cf2375fae1](https://linux-hardware.org/?probe=cf2375fae1) | May 04, 2022 |
| Google        | Candy                       | Notebook    | [2c41b3e736](https://linux-hardware.org/?probe=2c41b3e736) | May 04, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [96f5ffc8ba](https://linux-hardware.org/?probe=96f5ffc8ba) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7eb149a2ac](https://linux-hardware.org/?probe=7eb149a2ac) | May 04, 2022 |
| Dell          | Studio 1749                 | Notebook    | [c72c5ef974](https://linux-hardware.org/?probe=c72c5ef974) | May 04, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [ee2487bbfc](https://linux-hardware.org/?probe=ee2487bbfc) | May 04, 2022 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [923eb0c417](https://linux-hardware.org/?probe=923eb0c417) | May 03, 2022 |
| HP            | 2B47                        | Desktop     | [e7433db9d1](https://linux-hardware.org/?probe=e7433db9d1) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1d475f29ce](https://linux-hardware.org/?probe=1d475f29ce) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Dell          | 073Y7Y A00                  | Desktop     | [6a5b9ba1c0](https://linux-hardware.org/?probe=6a5b9ba1c0) | May 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [19833f6b84](https://linux-hardware.org/?probe=19833f6b84) | May 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [593afa280b](https://linux-hardware.org/?probe=593afa280b) | May 03, 2022 |
| Dell          | Inspiron 7573               | Convertible | [b9d41d47e5](https://linux-hardware.org/?probe=b9d41d47e5) | May 03, 2022 |
| Supermicro    | X10DAL-i                    | Server      | [3db85b0e2e](https://linux-hardware.org/?probe=3db85b0e2e) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [744b50ab3b](https://linux-hardware.org/?probe=744b50ab3b) | May 03, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [5d62fcaf51](https://linux-hardware.org/?probe=5d62fcaf51) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ae09db17d6](https://linux-hardware.org/?probe=ae09db17d6) | May 03, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [e9ad2578c3](https://linux-hardware.org/?probe=e9ad2578c3) | May 03, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2089066a7d](https://linux-hardware.org/?probe=2089066a7d) | May 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1f33fda19d](https://linux-hardware.org/?probe=1f33fda19d) | May 03, 2022 |
| Acer          | Spin SP315-51               | Convertible | [227f2d9f45](https://linux-hardware.org/?probe=227f2d9f45) | May 03, 2022 |
| Azulle        | Access4                     | Stick pc    | [3fce0e8ce2](https://linux-hardware.org/?probe=3fce0e8ce2) | May 03, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [26aa108efd](https://linux-hardware.org/?probe=26aa108efd) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e126640b3b](https://linux-hardware.org/?probe=e126640b3b) | May 03, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [6156fc41a9](https://linux-hardware.org/?probe=6156fc41a9) | May 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [142c1f1a2f](https://linux-hardware.org/?probe=142c1f1a2f) | May 03, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [e32cfbd1a0](https://linux-hardware.org/?probe=e32cfbd1a0) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [1fea9af929](https://linux-hardware.org/?probe=1fea9af929) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [d49d0283d4](https://linux-hardware.org/?probe=d49d0283d4) | May 03, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [d8b5fec9fe](https://linux-hardware.org/?probe=d8b5fec9fe) | May 03, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [b958961909](https://linux-hardware.org/?probe=b958961909) | May 03, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [2c2fd29320](https://linux-hardware.org/?probe=2c2fd29320) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [3eaa8fece6](https://linux-hardware.org/?probe=3eaa8fece6) | May 03, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [9505d0e8b7](https://linux-hardware.org/?probe=9505d0e8b7) | May 03, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| Dell          | Inspiron 5755               | Notebook    | [5ae0d07e61](https://linux-hardware.org/?probe=5ae0d07e61) | May 03, 2022 |
| Dell          | Latitude E6520              | Notebook    | [fa055124dd](https://linux-hardware.org/?probe=fa055124dd) | May 03, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b32500381a](https://linux-hardware.org/?probe=b32500381a) | May 03, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [72c0b48dc2](https://linux-hardware.org/?probe=72c0b48dc2) | May 03, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [b9864b6d4b](https://linux-hardware.org/?probe=b9864b6d4b) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| Google        | Edgar                       | Notebook    | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [f83ae845fe](https://linux-hardware.org/?probe=f83ae845fe) | May 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [8af6378145](https://linux-hardware.org/?probe=8af6378145) | May 02, 2022 |
| Dell          | Precision 5520              | Notebook    | [bcd6d0d584](https://linux-hardware.org/?probe=bcd6d0d584) | May 02, 2022 |
| Pepper Job... | GLK-UC2X                    | Desktop     | [114a368438](https://linux-hardware.org/?probe=114a368438) | May 02, 2022 |
| HP            | 0B54h D                     | Desktop     | [a90845be26](https://linux-hardware.org/?probe=a90845be26) | May 02, 2022 |
| Acer          | Aspire 6930                 | Notebook    | [ab42c723ad](https://linux-hardware.org/?probe=ab42c723ad) | May 02, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d98dcbfa7d](https://linux-hardware.org/?probe=d98dcbfa7d) | May 02, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASRock        | B550AM Gaming               | Desktop     | [e31ad2a03f](https://linux-hardware.org/?probe=e31ad2a03f) | May 02, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [7bee091d47](https://linux-hardware.org/?probe=7bee091d47) | May 02, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [c4662bd608](https://linux-hardware.org/?probe=c4662bd608) | May 02, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [6c38249bc4](https://linux-hardware.org/?probe=6c38249bc4) | May 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [45a9821bc8](https://linux-hardware.org/?probe=45a9821bc8) | May 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [44583b1142](https://linux-hardware.org/?probe=44583b1142) | May 02, 2022 |
| HP            | 1497                        | Desktop     | [16c772cb33](https://linux-hardware.org/?probe=16c772cb33) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| HP            | 1497                        | Desktop     | [a680758da3](https://linux-hardware.org/?probe=a680758da3) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4177Q5U       | Notebook    | [b4c3ba0e32](https://linux-hardware.org/?probe=b4c3ba0e32) | May 02, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6b16661a63](https://linux-hardware.org/?probe=6b16661a63) | May 02, 2022 |
| Alienware     | 07JNH0 A02                  | Desktop     | [d39a57aed6](https://linux-hardware.org/?probe=d39a57aed6) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4177Q5U       | Notebook    | [81a02f0bb6](https://linux-hardware.org/?probe=81a02f0bb6) | May 02, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [2b35f16b31](https://linux-hardware.org/?probe=2b35f16b31) | May 02, 2022 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [0ec6cf5c64](https://linux-hardware.org/?probe=0ec6cf5c64) | May 02, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [8115992c41](https://linux-hardware.org/?probe=8115992c41) | May 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b7709ed1c5](https://linux-hardware.org/?probe=b7709ed1c5) | May 02, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [d17d17b778](https://linux-hardware.org/?probe=d17d17b778) | May 02, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [301694185a](https://linux-hardware.org/?probe=301694185a) | May 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [510cfcefd5](https://linux-hardware.org/?probe=510cfcefd5) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | Desktop     | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [b2a40a1006](https://linux-hardware.org/?probe=b2a40a1006) | May 02, 2022 |
| System76      | Oryx Pro                    | Notebook    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [6a29f83afe](https://linux-hardware.org/?probe=6a29f83afe) | May 02, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [e76fc542d8](https://linux-hardware.org/?probe=e76fc542d8) | May 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bb4754906d](https://linux-hardware.org/?probe=bb4754906d) | May 02, 2022 |
| AZW           | GTR V01                     | Mini pc     | [8b16cdb8b3](https://linux-hardware.org/?probe=8b16cdb8b3) | May 02, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [dd85719ec6](https://linux-hardware.org/?probe=dd85719ec6) | May 02, 2022 |
| Dell          | Latitude E5570              | Notebook    | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [4de04607db](https://linux-hardware.org/?probe=4de04607db) | May 02, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [7636489d8e](https://linux-hardware.org/?probe=7636489d8e) | May 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d6bd192469](https://linux-hardware.org/?probe=d6bd192469) | May 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [ec8a9ceb87](https://linux-hardware.org/?probe=ec8a9ceb87) | May 01, 2022 |
| Lenovo        | N22 80S6                    | Notebook    | [f08359857b](https://linux-hardware.org/?probe=f08359857b) | May 01, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [73396d4b0b](https://linux-hardware.org/?probe=73396d4b0b) | May 01, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| HP            | 255 G1                      | Notebook    | [48c43a229d](https://linux-hardware.org/?probe=48c43a229d) | May 01, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c224bc180c](https://linux-hardware.org/?probe=c224bc180c) | May 01, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [965ebad5cb](https://linux-hardware.org/?probe=965ebad5cb) | May 01, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [e1184317fa](https://linux-hardware.org/?probe=e1184317fa) | May 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [be68c0201a](https://linux-hardware.org/?probe=be68c0201a) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2d06b54d63](https://linux-hardware.org/?probe=2d06b54d63) | May 01, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [4ab59c4f2e](https://linux-hardware.org/?probe=4ab59c4f2e) | May 01, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [32b6e040c6](https://linux-hardware.org/?probe=32b6e040c6) | May 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [83a8bbb313](https://linux-hardware.org/?probe=83a8bbb313) | May 01, 2022 |
| Dell          | Latitude 3410               | Notebook    | [1f33e5ca08](https://linux-hardware.org/?probe=1f33e5ca08) | May 01, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [48afcac3f0](https://linux-hardware.org/?probe=48afcac3f0) | May 01, 2022 |
| Dell          | 0G919G A00                  | Desktop     | [f70b64d6b4](https://linux-hardware.org/?probe=f70b64d6b4) | May 01, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [89a959efc4](https://linux-hardware.org/?probe=89a959efc4) | May 01, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [36bd67db48](https://linux-hardware.org/?probe=36bd67db48) | May 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [acdc37bb16](https://linux-hardware.org/?probe=acdc37bb16) | May 01, 2022 |
| HP            | 3047h                       | Desktop     | [ce68f3ee8c](https://linux-hardware.org/?probe=ce68f3ee8c) | May 01, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [6cefd4f4de](https://linux-hardware.org/?probe=6cefd4f4de) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0132f4f349](https://linux-hardware.org/?probe=0132f4f349) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f2dccc8fb8](https://linux-hardware.org/?probe=f2dccc8fb8) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [379c6be15c](https://linux-hardware.org/?probe=379c6be15c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [620c550b04](https://linux-hardware.org/?probe=620c550b04) | May 01, 2022 |
| HP            | 0B48h                       | Desktop     | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [215758ad8a](https://linux-hardware.org/?probe=215758ad8a) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [cb6d49fe71](https://linux-hardware.org/?probe=cb6d49fe71) | Apr 30, 2022 |
| Dell          | Precision M2800             | Notebook    | [deffc81ac5](https://linux-hardware.org/?probe=deffc81ac5) | Apr 30, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [9d2383d1f8](https://linux-hardware.org/?probe=9d2383d1f8) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [57241594ad](https://linux-hardware.org/?probe=57241594ad) | Apr 30, 2022 |
| Alienware     | x17 R2                      | Notebook    | [d78db966bc](https://linux-hardware.org/?probe=d78db966bc) | Apr 30, 2022 |
| LattePanda    | Alpha                       | Desktop     | [4e0dc573e1](https://linux-hardware.org/?probe=4e0dc573e1) | Apr 30, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [76ee3be416](https://linux-hardware.org/?probe=76ee3be416) | Apr 30, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [5a54ce639c](https://linux-hardware.org/?probe=5a54ce639c) | Apr 30, 2022 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [5f540a16c9](https://linux-hardware.org/?probe=5f540a16c9) | Apr 30, 2022 |
| Lenovo        | 81VS                        | Notebook    | [1ff46f7cdc](https://linux-hardware.org/?probe=1ff46f7cdc) | Apr 30, 2022 |
| Lenovo        | 81VS                        | Notebook    | [ea23b0e852](https://linux-hardware.org/?probe=ea23b0e852) | Apr 30, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| IBM           | 00D4062                     | Server      | [d18004b017](https://linux-hardware.org/?probe=d18004b017) | Apr 30, 2022 |
| Dell          | XPS M1530                   | Notebook    | [0e58eb209d](https://linux-hardware.org/?probe=0e58eb209d) | Apr 30, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [2b03a9568d](https://linux-hardware.org/?probe=2b03a9568d) | Apr 30, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [21dbd84bbc](https://linux-hardware.org/?probe=21dbd84bbc) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83e47f9c91](https://linux-hardware.org/?probe=83e47f9c91) | Apr 30, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [10975a661b](https://linux-hardware.org/?probe=10975a661b) | Apr 30, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c4d7dc5e80](https://linux-hardware.org/?probe=c4d7dc5e80) | Apr 30, 2022 |
| HP            | 1791                        | Desktop     | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| Toshiba       | Dakar10FW8                  | Notebook    | [fbe2aaac31](https://linux-hardware.org/?probe=fbe2aaac31) | Apr 30, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [1c72c0839b](https://linux-hardware.org/?probe=1c72c0839b) | Apr 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2065a3c2f3](https://linux-hardware.org/?probe=2065a3c2f3) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [47c28082e8](https://linux-hardware.org/?probe=47c28082e8) | Apr 30, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [6ae554c455](https://linux-hardware.org/?probe=6ae554c455) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| ASUSTek       | A55M-E                      | Desktop     | [eed78fb5ab](https://linux-hardware.org/?probe=eed78fb5ab) | Apr 30, 2022 |
| Intel         | NUC9VXQNB K47179-403        | Mini pc     | [c99c3cdac6](https://linux-hardware.org/?probe=c99c3cdac6) | Apr 30, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| Google        | Fleex                       | Notebook    | [212ff0673f](https://linux-hardware.org/?probe=212ff0673f) | Apr 30, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [3b9e57fc42](https://linux-hardware.org/?probe=3b9e57fc42) | Apr 30, 2022 |
| Dell          | 0K068D A00                  | Desktop     | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [a87f5d4c6e](https://linux-hardware.org/?probe=a87f5d4c6e) | Apr 30, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [087399e252](https://linux-hardware.org/?probe=087399e252) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [297dca51b9](https://linux-hardware.org/?probe=297dca51b9) | Apr 30, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [e6557824cb](https://linux-hardware.org/?probe=e6557824cb) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| Lenovo        | SHARKBAY 0B98405 STD        | Desktop     | [4842f5aef2](https://linux-hardware.org/?probe=4842f5aef2) | Apr 30, 2022 |
| Foxconn       | 2A92                        | Desktop     | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | Desktop     | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| Foxconn       | 2A92                        | Desktop     | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [07cb268e5e](https://linux-hardware.org/?probe=07cb268e5e) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | Desktop     | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| HP            | 0B54h D                     | Desktop     | [2023024a05](https://linux-hardware.org/?probe=2023024a05) | Apr 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [4924979f39](https://linux-hardware.org/?probe=4924979f39) | Apr 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [58dfeebbb5](https://linux-hardware.org/?probe=58dfeebbb5) | Apr 29, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [767590ac38](https://linux-hardware.org/?probe=767590ac38) | Apr 29, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [082e245a6c](https://linux-hardware.org/?probe=082e245a6c) | Apr 29, 2022 |
| Supermicro    | X9DRW-7TPF+                 | Server      | [6bd590bc17](https://linux-hardware.org/?probe=6bd590bc17) | Apr 29, 2022 |
| Dell          | Precision M6600             | Notebook    | [bb40a22dd3](https://linux-hardware.org/?probe=bb40a22dd3) | Apr 29, 2022 |
| TUXEDO        | Book BM15 Gen10             | Notebook    | [45b5b1bba9](https://linux-hardware.org/?probe=45b5b1bba9) | Apr 29, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b4946e7399](https://linux-hardware.org/?probe=b4946e7399) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [a2dd962374](https://linux-hardware.org/?probe=a2dd962374) | Apr 29, 2022 |
| Google        | Enguarde                    | Notebook    | [878203f099](https://linux-hardware.org/?probe=878203f099) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [fafda83c57](https://linux-hardware.org/?probe=fafda83c57) | Apr 29, 2022 |
| Supermicro    | X11SSH-F                    | Desktop     | [0d475e91f3](https://linux-hardware.org/?probe=0d475e91f3) | Apr 29, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [ea3b16fcfd](https://linux-hardware.org/?probe=ea3b16fcfd) | Apr 29, 2022 |
| HP            | 158A                        | Desktop     | [11b5037897](https://linux-hardware.org/?probe=11b5037897) | Apr 29, 2022 |
| Dell          | 0RN4PJ A00                  | Server      | [72d2aa925f](https://linux-hardware.org/?probe=72d2aa925f) | Apr 29, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [ced6ab1ae8](https://linux-hardware.org/?probe=ced6ab1ae8) | Apr 29, 2022 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [65c9d1ca57](https://linux-hardware.org/?probe=65c9d1ca57) | Apr 29, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [5df7751e99](https://linux-hardware.org/?probe=5df7751e99) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Pepper Job... | GLK-UC2X                    | Desktop     | [28495f32bd](https://linux-hardware.org/?probe=28495f32bd) | Apr 29, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [ca711b9db0](https://linux-hardware.org/?probe=ca711b9db0) | Apr 29, 2022 |
| Lenovo        | 3136 SDK0K17763 WIN 1801... | Mini pc     | [7b13bcb624](https://linux-hardware.org/?probe=7b13bcb624) | Apr 29, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [45630a42df](https://linux-hardware.org/?probe=45630a42df) | Apr 29, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [1c8e1b39cb](https://linux-hardware.org/?probe=1c8e1b39cb) | Apr 29, 2022 |
| Lenovo        | ThinkPad X390 20Q1SCDR00    | Notebook    | [41a3cac1f4](https://linux-hardware.org/?probe=41a3cac1f4) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [ed6e7a9362](https://linux-hardware.org/?probe=ed6e7a9362) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [2b0042d784](https://linux-hardware.org/?probe=2b0042d784) | Apr 29, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [27df4d83ea](https://linux-hardware.org/?probe=27df4d83ea) | Apr 29, 2022 |
| System76      | Oryx Pro                    | Notebook    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| MSI           | A78M-E35                    | Desktop     | [8f9bf75a08](https://linux-hardware.org/?probe=8f9bf75a08) | Apr 29, 2022 |
| HP            | 8704                        | Desktop     | [41d896b51d](https://linux-hardware.org/?probe=41d896b51d) | Apr 29, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [4cf62cf9a3](https://linux-hardware.org/?probe=4cf62cf9a3) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [c7eeb7b79d](https://linux-hardware.org/?probe=c7eeb7b79d) | Apr 28, 2022 |
| Google        | Enguarde                    | Notebook    | [194e2eb81b](https://linux-hardware.org/?probe=194e2eb81b) | Apr 28, 2022 |
| Lenovo        | ThinkPad L412 440332U       | Notebook    | [6616ce20ee](https://linux-hardware.org/?probe=6616ce20ee) | Apr 28, 2022 |
| Dell          | Precision 7510              | Notebook    | [afaea67857](https://linux-hardware.org/?probe=afaea67857) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [f898a6a476](https://linux-hardware.org/?probe=f898a6a476) | Apr 28, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d5998a6183](https://linux-hardware.org/?probe=d5998a6183) | Apr 28, 2022 |
| Google        | Enguarde                    | Notebook    | [37794c3d3a](https://linux-hardware.org/?probe=37794c3d3a) | Apr 28, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f3eb7d23b1](https://linux-hardware.org/?probe=f3eb7d23b1) | Apr 28, 2022 |
| Lenovo        | ThinkPad T431s 20ACS03P0... | Notebook    | [3c0878aee3](https://linux-hardware.org/?probe=3c0878aee3) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ae46ece731](https://linux-hardware.org/?probe=ae46ece731) | Apr 28, 2022 |
| IBM           | 00D4062                     | Server      | [cd977a86ce](https://linux-hardware.org/?probe=cd977a86ce) | Apr 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1126937638](https://linux-hardware.org/?probe=1126937638) | Apr 28, 2022 |
| HP            | 8299                        | Desktop     | [7a54bfae05](https://linux-hardware.org/?probe=7a54bfae05) | Apr 28, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [e41e5725a7](https://linux-hardware.org/?probe=e41e5725a7) | Apr 28, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [634294bb8a](https://linux-hardware.org/?probe=634294bb8a) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [2bf0ef0725](https://linux-hardware.org/?probe=2bf0ef0725) | Apr 28, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [703a704f72](https://linux-hardware.org/?probe=703a704f72) | Apr 28, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b483bb308e](https://linux-hardware.org/?probe=b483bb308e) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Qualcomm T... | SDM845 v2.1 MTP PVT         | Soc         | [1efe3337b5](https://linux-hardware.org/?probe=1efe3337b5) | Apr 28, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3e88e21f3c](https://linux-hardware.org/?probe=3e88e21f3c) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [94defd50ef](https://linux-hardware.org/?probe=94defd50ef) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [16f0860d82](https://linux-hardware.org/?probe=16f0860d82) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [d52cf822df](https://linux-hardware.org/?probe=d52cf822df) | Apr 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6f26e0d7bd](https://linux-hardware.org/?probe=6f26e0d7bd) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [ad35094812](https://linux-hardware.org/?probe=ad35094812) | Apr 28, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [998ef3a4fe](https://linux-hardware.org/?probe=998ef3a4fe) | Apr 27, 2022 |
| Dell          | 0YJHYD A00                  | Desktop     | [6111a9976e](https://linux-hardware.org/?probe=6111a9976e) | Apr 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f70215ac5e](https://linux-hardware.org/?probe=f70215ac5e) | Apr 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [f420f53eca](https://linux-hardware.org/?probe=f420f53eca) | Apr 27, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [820098c075](https://linux-hardware.org/?probe=820098c075) | Apr 27, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [d5d6cde087](https://linux-hardware.org/?probe=d5d6cde087) | Apr 27, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3e5933fe0d](https://linux-hardware.org/?probe=3e5933fe0d) | Apr 27, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [b304c37639](https://linux-hardware.org/?probe=b304c37639) | Apr 27, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [2f6fdef961](https://linux-hardware.org/?probe=2f6fdef961) | Apr 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [a8752656c1](https://linux-hardware.org/?probe=a8752656c1) | Apr 27, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Lenovo        | Unknown                     | Notebook    | [869b7e6d8d](https://linux-hardware.org/?probe=869b7e6d8d) | Apr 27, 2022 |
| Lenovo        | Unknown                     | Notebook    | [88f2e3a710](https://linux-hardware.org/?probe=88f2e3a710) | Apr 27, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [0212dc3208](https://linux-hardware.org/?probe=0212dc3208) | Apr 27, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [4d84b677ae](https://linux-hardware.org/?probe=4d84b677ae) | Apr 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b2bddaf1b1](https://linux-hardware.org/?probe=b2bddaf1b1) | Apr 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [02b0c35fed](https://linux-hardware.org/?probe=02b0c35fed) | Apr 27, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dc46901a64](https://linux-hardware.org/?probe=dc46901a64) | Apr 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS3X800    | Notebook    | [adbec7ed2e](https://linux-hardware.org/?probe=adbec7ed2e) | Apr 27, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1243ca01bb](https://linux-hardware.org/?probe=1243ca01bb) | Apr 27, 2022 |
| HP            | 15                          | Notebook    | [63e5782bc3](https://linux-hardware.org/?probe=63e5782bc3) | Apr 27, 2022 |
| HP            | 15                          | Notebook    | [e240f03797](https://linux-hardware.org/?probe=e240f03797) | Apr 27, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [81aed15a37](https://linux-hardware.org/?probe=81aed15a37) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [56da721176](https://linux-hardware.org/?probe=56da721176) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [1619af58d4](https://linux-hardware.org/?probe=1619af58d4) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | Notebook    | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [2d6ef9c4b6](https://linux-hardware.org/?probe=2d6ef9c4b6) | Apr 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [fd2b7d1fe2](https://linux-hardware.org/?probe=fd2b7d1fe2) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| Lenovo        | IdeaPad Y470 0855           | Notebook    | [ee26833b58](https://linux-hardware.org/?probe=ee26833b58) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [31b5451ae1](https://linux-hardware.org/?probe=31b5451ae1) | Apr 27, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [e408254cc8](https://linux-hardware.org/?probe=e408254cc8) | Apr 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [1a2453d50d](https://linux-hardware.org/?probe=1a2453d50d) | Apr 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| Dell          | 0DR845                      | Desktop     | [5f00785e45](https://linux-hardware.org/?probe=5f00785e45) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0f8a6e887d](https://linux-hardware.org/?probe=0f8a6e887d) | Apr 26, 2022 |
| Intel         | NUC11TNBv5 M11900-404       | Mini pc     | [d21f47aef8](https://linux-hardware.org/?probe=d21f47aef8) | Apr 26, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [35a063e4e9](https://linux-hardware.org/?probe=35a063e4e9) | Apr 26, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [36ae8140f9](https://linux-hardware.org/?probe=36ae8140f9) | Apr 26, 2022 |
| Unknown       | 1.0                         | Desktop     | [7c17b2186e](https://linux-hardware.org/?probe=7c17b2186e) | Apr 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [fa07d6f127](https://linux-hardware.org/?probe=fa07d6f127) | Apr 26, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [8f61feb9d0](https://linux-hardware.org/?probe=8f61feb9d0) | Apr 26, 2022 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [faee56dd80](https://linux-hardware.org/?probe=faee56dd80) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [98251fced6](https://linux-hardware.org/?probe=98251fced6) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6a34230d87](https://linux-hardware.org/?probe=6a34230d87) | Apr 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [c3e7bcf701](https://linux-hardware.org/?probe=c3e7bcf701) | Apr 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ed0065a715](https://linux-hardware.org/?probe=ed0065a715) | Apr 26, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ff9f82ef2d](https://linux-hardware.org/?probe=ff9f82ef2d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | Desktop     | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [28e635a30b](https://linux-hardware.org/?probe=28e635a30b) | Apr 25, 2022 |
| Lenovo        | Reno                        | Server      | [02fecd4d4a](https://linux-hardware.org/?probe=02fecd4d4a) | Apr 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [40b23da6dc](https://linux-hardware.org/?probe=40b23da6dc) | Apr 25, 2022 |
| Dell          | G15 5510                    | Notebook    | [ef1787abc5](https://linux-hardware.org/?probe=ef1787abc5) | Apr 25, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [0d3c8ed904](https://linux-hardware.org/?probe=0d3c8ed904) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| HP            | 82FE 11                     | Desktop     | [1b7d145108](https://linux-hardware.org/?probe=1b7d145108) | Apr 25, 2022 |
| Lenovo        | IdeaPadFlex 5-1470 81C9     | Convertible | [038b7bda71](https://linux-hardware.org/?probe=038b7bda71) | Apr 25, 2022 |
| Google        | Enguarde                    | Notebook    | [9b28418435](https://linux-hardware.org/?probe=9b28418435) | Apr 25, 2022 |
| EVGA          | X299 MICRO                  | Desktop     | [924977085d](https://linux-hardware.org/?probe=924977085d) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4c3bf947f5](https://linux-hardware.org/?probe=4c3bf947f5) | Apr 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9236e9bc93](https://linux-hardware.org/?probe=9236e9bc93) | Apr 25, 2022 |
| HP            | 82FE 11                     | Desktop     | [895a0442d0](https://linux-hardware.org/?probe=895a0442d0) | Apr 25, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4fc3f5659d](https://linux-hardware.org/?probe=4fc3f5659d) | Apr 25, 2022 |
| HP            | 212B                        | Desktop     | [f202f01728](https://linux-hardware.org/?probe=f202f01728) | Apr 25, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [127dd69ddf](https://linux-hardware.org/?probe=127dd69ddf) | Apr 25, 2022 |
| Pegatron      | Narra6                      | Desktop     | [0bfaba2999](https://linux-hardware.org/?probe=0bfaba2999) | Apr 25, 2022 |
| Lenovo        | ThinkPad T530 2359CTO       | Notebook    | [58199da0ee](https://linux-hardware.org/?probe=58199da0ee) | Apr 25, 2022 |
| Dell          | 0KP561                      | Desktop     | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [f41f324f01](https://linux-hardware.org/?probe=f41f324f01) | Apr 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [37314a1343](https://linux-hardware.org/?probe=37314a1343) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [d1d705c163](https://linux-hardware.org/?probe=d1d705c163) | Apr 25, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [97ff7b7591](https://linux-hardware.org/?probe=97ff7b7591) | Apr 25, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [82d6475ef3](https://linux-hardware.org/?probe=82d6475ef3) | Apr 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fe067fc3d4](https://linux-hardware.org/?probe=fe067fc3d4) | Apr 25, 2022 |
| HP            | 2B47                        | Desktop     | [3805de3dc4](https://linux-hardware.org/?probe=3805de3dc4) | Apr 25, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [256f703e7e](https://linux-hardware.org/?probe=256f703e7e) | Apr 25, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [8a96f457bb](https://linux-hardware.org/?probe=8a96f457bb) | Apr 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fb26f3ab65](https://linux-hardware.org/?probe=fb26f3ab65) | Apr 25, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [be64d5f610](https://linux-hardware.org/?probe=be64d5f610) | Apr 25, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [5df6c147c0](https://linux-hardware.org/?probe=5df6c147c0) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | Notebook    | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8104edaf22](https://linux-hardware.org/?probe=8104edaf22) | Apr 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [a7f5507dcd](https://linux-hardware.org/?probe=a7f5507dcd) | Apr 24, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [2e5a3b2158](https://linux-hardware.org/?probe=2e5a3b2158) | Apr 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e039df74b3](https://linux-hardware.org/?probe=e039df74b3) | Apr 24, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [9c9601a864](https://linux-hardware.org/?probe=9c9601a864) | Apr 24, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [3582362347](https://linux-hardware.org/?probe=3582362347) | Apr 24, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [14b3e7c65a](https://linux-hardware.org/?probe=14b3e7c65a) | Apr 24, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [0abccb142a](https://linux-hardware.org/?probe=0abccb142a) | Apr 24, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [54aa68a653](https://linux-hardware.org/?probe=54aa68a653) | Apr 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [1b392b96c3](https://linux-hardware.org/?probe=1b392b96c3) | Apr 24, 2022 |
| Lenovo        | ThinkPad W700 275236U       | Notebook    | [b7c7a5216b](https://linux-hardware.org/?probe=b7c7a5216b) | Apr 24, 2022 |
| Lenovo        | ThinkPad W700 275236U       | Notebook    | [4d31fc069f](https://linux-hardware.org/?probe=4d31fc069f) | Apr 24, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | Notebook    | [6748d74892](https://linux-hardware.org/?probe=6748d74892) | Apr 24, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [2e4a211c66](https://linux-hardware.org/?probe=2e4a211c66) | Apr 24, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [2e3ae2a664](https://linux-hardware.org/?probe=2e3ae2a664) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [88318f48e8](https://linux-hardware.org/?probe=88318f48e8) | Apr 24, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [df7e090d9c](https://linux-hardware.org/?probe=df7e090d9c) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [30bac0dca3](https://linux-hardware.org/?probe=30bac0dca3) | Apr 24, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [79460e1288](https://linux-hardware.org/?probe=79460e1288) | Apr 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [a1eaf40bdb](https://linux-hardware.org/?probe=a1eaf40bdb) | Apr 24, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [343a4c47a6](https://linux-hardware.org/?probe=343a4c47a6) | Apr 24, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [34ac6fff67](https://linux-hardware.org/?probe=34ac6fff67) | Apr 24, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [58065270dd](https://linux-hardware.org/?probe=58065270dd) | Apr 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [83eab02369](https://linux-hardware.org/?probe=83eab02369) | Apr 24, 2022 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [e0298dd8f0](https://linux-hardware.org/?probe=e0298dd8f0) | Apr 24, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [3d46ae9ba9](https://linux-hardware.org/?probe=3d46ae9ba9) | Apr 23, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2bb4e3b744](https://linux-hardware.org/?probe=2bb4e3b744) | Apr 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9beab176cd](https://linux-hardware.org/?probe=9beab176cd) | Apr 23, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [f57f07921b](https://linux-hardware.org/?probe=f57f07921b) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | Desktop     | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [36f385210f](https://linux-hardware.org/?probe=36f385210f) | Apr 23, 2022 |
| HP            | 15                          | Notebook    | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d0a5573598](https://linux-hardware.org/?probe=d0a5573598) | Apr 23, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [c1c54ece08](https://linux-hardware.org/?probe=c1c54ece08) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [0534d32a13](https://linux-hardware.org/?probe=0534d32a13) | Apr 23, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [00181fd144](https://linux-hardware.org/?probe=00181fd144) | Apr 23, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [9f7348e2ec](https://linux-hardware.org/?probe=9f7348e2ec) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [3b01c4a4a5](https://linux-hardware.org/?probe=3b01c4a4a5) | Apr 23, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [47cbc95032](https://linux-hardware.org/?probe=47cbc95032) | Apr 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [cba75446b8](https://linux-hardware.org/?probe=cba75446b8) | Apr 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [8ed6b948aa](https://linux-hardware.org/?probe=8ed6b948aa) | Apr 23, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [fb3d31a363](https://linux-hardware.org/?probe=fb3d31a363) | Apr 23, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [8ae54427ca](https://linux-hardware.org/?probe=8ae54427ca) | Apr 23, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a0eb199a0c](https://linux-hardware.org/?probe=a0eb199a0c) | Apr 23, 2022 |
| Dell          | Latitude 7400               | Notebook    | [189ae3d755](https://linux-hardware.org/?probe=189ae3d755) | Apr 23, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | Notebook    | [2dd8baa591](https://linux-hardware.org/?probe=2dd8baa591) | Apr 23, 2022 |
| Dell          | Precision 3560              | Notebook    | [58f2749e54](https://linux-hardware.org/?probe=58f2749e54) | Apr 23, 2022 |
| Dell          | Precision 3560              | Notebook    | [72129eb241](https://linux-hardware.org/?probe=72129eb241) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c46c916a16](https://linux-hardware.org/?probe=c46c916a16) | Apr 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [5b78ae1e5e](https://linux-hardware.org/?probe=5b78ae1e5e) | Apr 23, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [3cb8eac116](https://linux-hardware.org/?probe=3cb8eac116) | Apr 23, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [69b46ca57d](https://linux-hardware.org/?probe=69b46ca57d) | Apr 23, 2022 |
| Framework     | Laptop                      | Notebook    | [dbc00cbd42](https://linux-hardware.org/?probe=dbc00cbd42) | Apr 23, 2022 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [cb93a4a05d](https://linux-hardware.org/?probe=cb93a4a05d) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Pegatron      | 2A86E01                     | Desktop     | [9c1149c9f7](https://linux-hardware.org/?probe=9c1149c9f7) | Apr 23, 2022 |
| HP            | Pavilion g7                 | Notebook    | [40588f77cb](https://linux-hardware.org/?probe=40588f77cb) | Apr 23, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d1111c70c7](https://linux-hardware.org/?probe=d1111c70c7) | Apr 23, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [477b1e873f](https://linux-hardware.org/?probe=477b1e873f) | Apr 23, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [d9c8361847](https://linux-hardware.org/?probe=d9c8361847) | Apr 23, 2022 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [291cbe0513](https://linux-hardware.org/?probe=291cbe0513) | Apr 23, 2022 |
| Seco          | C40 C                       | Desktop     | [3e1fffcda7](https://linux-hardware.org/?probe=3e1fffcda7) | Apr 22, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [0c1628930f](https://linux-hardware.org/?probe=0c1628930f) | Apr 22, 2022 |
| HP            | 8768 A                      | Desktop     | [a939560d30](https://linux-hardware.org/?probe=a939560d30) | Apr 22, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [9e72ff0940](https://linux-hardware.org/?probe=9e72ff0940) | Apr 22, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [26727e92e4](https://linux-hardware.org/?probe=26727e92e4) | Apr 22, 2022 |
| Supermicro    | X5DP8                       | Desktop     | [991180636d](https://linux-hardware.org/?probe=991180636d) | Apr 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [91744e20c7](https://linux-hardware.org/?probe=91744e20c7) | Apr 22, 2022 |
| Lenovo        | Unknown                     | Notebook    | [f582eb96bb](https://linux-hardware.org/?probe=f582eb96bb) | Apr 22, 2022 |
| Google        | Enguarde                    | Notebook    | [d23e0dd7ea](https://linux-hardware.org/?probe=d23e0dd7ea) | Apr 22, 2022 |
| Supermicro    | X5DP8                       | Desktop     | [3e50d9b6b4](https://linux-hardware.org/?probe=3e50d9b6b4) | Apr 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [46ae253039](https://linux-hardware.org/?probe=46ae253039) | Apr 22, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6718ac3459](https://linux-hardware.org/?probe=6718ac3459) | Apr 22, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a0ab7e8078](https://linux-hardware.org/?probe=a0ab7e8078) | Apr 22, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [0773779335](https://linux-hardware.org/?probe=0773779335) | Apr 22, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [3b1d5e2bb8](https://linux-hardware.org/?probe=3b1d5e2bb8) | Apr 22, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [cf250660ab](https://linux-hardware.org/?probe=cf250660ab) | Apr 22, 2022 |
| Dell          | Latitude E5500              | Notebook    | [500b4b5ee2](https://linux-hardware.org/?probe=500b4b5ee2) | Apr 22, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [1ca3d685bc](https://linux-hardware.org/?probe=1ca3d685bc) | Apr 22, 2022 |
| HP            | 158B                        | Desktop     | [af3f62d027](https://linux-hardware.org/?probe=af3f62d027) | Apr 22, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [40d59bce4b](https://linux-hardware.org/?probe=40d59bce4b) | Apr 22, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [db3046a43d](https://linux-hardware.org/?probe=db3046a43d) | Apr 22, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [bcd53f4be6](https://linux-hardware.org/?probe=bcd53f4be6) | Apr 22, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [8009de24c8](https://linux-hardware.org/?probe=8009de24c8) | Apr 22, 2022 |
| ASRock        | Z370 Pro4-IB                | Desktop     | [c0c51e4d53](https://linux-hardware.org/?probe=c0c51e4d53) | Apr 22, 2022 |
| HP            | Folio 13 - 2000             | Notebook    | [e6bd30864d](https://linux-hardware.org/?probe=e6bd30864d) | Apr 22, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8abbc8a322](https://linux-hardware.org/?probe=8abbc8a322) | Apr 22, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [9936062b3c](https://linux-hardware.org/?probe=9936062b3c) | Apr 22, 2022 |
| HP            | Folio 13 - 2000             | Notebook    | [801488394d](https://linux-hardware.org/?probe=801488394d) | Apr 22, 2022 |
| Google        | Candy                       | Notebook    | [5a31bd1da8](https://linux-hardware.org/?probe=5a31bd1da8) | Apr 22, 2022 |
| HP            | 2B4B                        | Desktop     | [c3dd8ed52a](https://linux-hardware.org/?probe=c3dd8ed52a) | Apr 22, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [017717599c](https://linux-hardware.org/?probe=017717599c) | Apr 22, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [0e3c909996](https://linux-hardware.org/?probe=0e3c909996) | Apr 22, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ddfd89e9dc](https://linux-hardware.org/?probe=ddfd89e9dc) | Apr 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [35e11e3e60](https://linux-hardware.org/?probe=35e11e3e60) | Apr 22, 2022 |
| Sony          | VPCEB3PGX                   | Notebook    | [1771623608](https://linux-hardware.org/?probe=1771623608) | Apr 22, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [a1e3d6d19a](https://linux-hardware.org/?probe=a1e3d6d19a) | Apr 22, 2022 |
| Google        | Droid                       | Notebook    | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [0dc3df4e7e](https://linux-hardware.org/?probe=0dc3df4e7e) | Apr 22, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [dd7f66f6dc](https://linux-hardware.org/?probe=dd7f66f6dc) | Apr 22, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [288f415604](https://linux-hardware.org/?probe=288f415604) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [29a508398a](https://linux-hardware.org/?probe=29a508398a) | Apr 22, 2022 |
| Dell          | 0KP561                      | Desktop     | [87398af452](https://linux-hardware.org/?probe=87398af452) | Apr 22, 2022 |
| Intel         | DQ45CB AAE30148-206         | Desktop     | [c4278ebcaa](https://linux-hardware.org/?probe=c4278ebcaa) | Apr 22, 2022 |
| Google        | Enguarde                    | Notebook    | [dbace8fc61](https://linux-hardware.org/?probe=dbace8fc61) | Apr 22, 2022 |
| Dell          | XPS M1530                   | Notebook    | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| MSI           | 970A-G45                    | Desktop     | [35f8f0652d](https://linux-hardware.org/?probe=35f8f0652d) | Apr 21, 2022 |
| SiS Techno... | 741                         | Desktop     | [46a25ce1d0](https://linux-hardware.org/?probe=46a25ce1d0) | Apr 21, 2022 |
| SiS Techno... | 741                         | Desktop     | [7cf3dd5251](https://linux-hardware.org/?probe=7cf3dd5251) | Apr 21, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [4c6e3f36dd](https://linux-hardware.org/?probe=4c6e3f36dd) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [bb2195b690](https://linux-hardware.org/?probe=bb2195b690) | Apr 21, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [4e74006288](https://linux-hardware.org/?probe=4e74006288) | Apr 21, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [82b11931ed](https://linux-hardware.org/?probe=82b11931ed) | Apr 21, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d2ba372696](https://linux-hardware.org/?probe=d2ba372696) | Apr 21, 2022 |
| Samsung       | 730QDA                      | Convertible | [3a9f66fbd6](https://linux-hardware.org/?probe=3a9f66fbd6) | Apr 21, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [753f5d4e22](https://linux-hardware.org/?probe=753f5d4e22) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [074f40a67b](https://linux-hardware.org/?probe=074f40a67b) | Apr 21, 2022 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [f1a2e57e22](https://linux-hardware.org/?probe=f1a2e57e22) | Apr 21, 2022 |
| HP            | 8054                        | Desktop     | [f9ec7b0896](https://linux-hardware.org/?probe=f9ec7b0896) | Apr 21, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [664867989b](https://linux-hardware.org/?probe=664867989b) | Apr 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [761f4046fa](https://linux-hardware.org/?probe=761f4046fa) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [329905cab9](https://linux-hardware.org/?probe=329905cab9) | Apr 21, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [180e1b4ab7](https://linux-hardware.org/?probe=180e1b4ab7) | Apr 21, 2022 |
| HP            | 2AF7                        | Desktop     | [0a92bfa831](https://linux-hardware.org/?probe=0a92bfa831) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [ab9982c327](https://linux-hardware.org/?probe=ab9982c327) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [93a5ff0ad9](https://linux-hardware.org/?probe=93a5ff0ad9) | Apr 21, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [480a64a95a](https://linux-hardware.org/?probe=480a64a95a) | Apr 21, 2022 |
| Wiltronic     | iVIEW i896QW                | Notebook    | [34e1873984](https://linux-hardware.org/?probe=34e1873984) | Apr 21, 2022 |
| Toshiba       | Satellite P75-A             | Notebook    | [7530153886](https://linux-hardware.org/?probe=7530153886) | Apr 21, 2022 |
| Toshiba       | Satellite P75-A             | Notebook    | [c9e373245c](https://linux-hardware.org/?probe=c9e373245c) | Apr 21, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [40c3ccc42c](https://linux-hardware.org/?probe=40c3ccc42c) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ff5e15c4d9](https://linux-hardware.org/?probe=ff5e15c4d9) | Apr 21, 2022 |
| Gateway       | NV59C                       | Notebook    | [c7f652c9f8](https://linux-hardware.org/?probe=c7f652c9f8) | Apr 21, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [9fc8be1cac](https://linux-hardware.org/?probe=9fc8be1cac) | Apr 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b59670505a](https://linux-hardware.org/?probe=b59670505a) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| HP            | Notebook                    | Notebook    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| Google        | Celes                       | Notebook    | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [c5158da48f](https://linux-hardware.org/?probe=c5158da48f) | Apr 21, 2022 |
| Dell          | Precision M4600             | Notebook    | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell          | Precision M4800             | Notebook    | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [2e19ae4498](https://linux-hardware.org/?probe=2e19ae4498) | Apr 21, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [ef169ddb1d](https://linux-hardware.org/?probe=ef169ddb1d) | Apr 20, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [c1d8847c06](https://linux-hardware.org/?probe=c1d8847c06) | Apr 20, 2022 |
| Dell          | 00VTMF A01                  | Desktop     | [5c93377fd1](https://linux-hardware.org/?probe=5c93377fd1) | Apr 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [33bcd3ec01](https://linux-hardware.org/?probe=33bcd3ec01) | Apr 20, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [5fbb55d515](https://linux-hardware.org/?probe=5fbb55d515) | Apr 20, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [e71954f2f9](https://linux-hardware.org/?probe=e71954f2f9) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [2bad463aa0](https://linux-hardware.org/?probe=2bad463aa0) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7338b3ccc3](https://linux-hardware.org/?probe=7338b3ccc3) | Apr 20, 2022 |
| Dell          | 02KGF7 A00                  | Desktop     | [960e7981ca](https://linux-hardware.org/?probe=960e7981ca) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [d39dbe919e](https://linux-hardware.org/?probe=d39dbe919e) | Apr 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4daf24b44d](https://linux-hardware.org/?probe=4daf24b44d) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [c9ef889715](https://linux-hardware.org/?probe=c9ef889715) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [63afa83513](https://linux-hardware.org/?probe=63afa83513) | Apr 20, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [0e990c65f0](https://linux-hardware.org/?probe=0e990c65f0) | Apr 20, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [f42bf105dc](https://linux-hardware.org/?probe=f42bf105dc) | Apr 20, 2022 |
| eMachines     | MCP61PM-GM                  | Desktop     | [16c4522843](https://linux-hardware.org/?probe=16c4522843) | Apr 20, 2022 |
| Toshiba       | Satellite S75-A             | Notebook    | [90ba54ad32](https://linux-hardware.org/?probe=90ba54ad32) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [75c049c0a1](https://linux-hardware.org/?probe=75c049c0a1) | Apr 20, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d493d2cda0](https://linux-hardware.org/?probe=d493d2cda0) | Apr 20, 2022 |
| Dell          | 0FGK1C A00                  | Desktop     | [b8fe9256d0](https://linux-hardware.org/?probe=b8fe9256d0) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [181bb3b047](https://linux-hardware.org/?probe=181bb3b047) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [9b62ce9d7f](https://linux-hardware.org/?probe=9b62ce9d7f) | Apr 20, 2022 |
| Google        | Enguarde                    | Notebook    | [3e6dd7d3ee](https://linux-hardware.org/?probe=3e6dd7d3ee) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [f7102a5d2b](https://linux-hardware.org/?probe=f7102a5d2b) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ee4c469a07](https://linux-hardware.org/?probe=ee4c469a07) | Apr 20, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [a6e1c8829e](https://linux-hardware.org/?probe=a6e1c8829e) | Apr 20, 2022 |
| Dell          | Latitude E6510              | Notebook    | [f082fd7a23](https://linux-hardware.org/?probe=f082fd7a23) | Apr 20, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f32b27ae86](https://linux-hardware.org/?probe=f32b27ae86) | Apr 20, 2022 |
| Dell          | 0YF8P5 A00                  | Desktop     | [11d8a53dd0](https://linux-hardware.org/?probe=11d8a53dd0) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [ce9f79fdbe](https://linux-hardware.org/?probe=ce9f79fdbe) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [e65ff110bb](https://linux-hardware.org/?probe=e65ff110bb) | Apr 20, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [466f67adb3](https://linux-hardware.org/?probe=466f67adb3) | Apr 20, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [2851261ddb](https://linux-hardware.org/?probe=2851261ddb) | Apr 20, 2022 |
| ASRock        | B550 Pro4                   | Desktop     | [a1806b3e86](https://linux-hardware.org/?probe=a1806b3e86) | Apr 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | GS60 2PE Ghost Pro          | Notebook    | [89a2ef83fd](https://linux-hardware.org/?probe=89a2ef83fd) | Apr 20, 2022 |
| Dell          | 06D7TR A01                  | Desktop     | [fe1217f09c](https://linux-hardware.org/?probe=fe1217f09c) | Apr 20, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4a4df2dc70](https://linux-hardware.org/?probe=4a4df2dc70) | Apr 20, 2022 |
| Dell          | XPS M1530                   | Notebook    | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [e409d7a8df](https://linux-hardware.org/?probe=e409d7a8df) | Apr 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [0bb6e11e4f](https://linux-hardware.org/?probe=0bb6e11e4f) | Apr 19, 2022 |
| Google        | Enguarde                    | Notebook    | [ad9cda8c65](https://linux-hardware.org/?probe=ad9cda8c65) | Apr 19, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7f83049cd5](https://linux-hardware.org/?probe=7f83049cd5) | Apr 19, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [6c4022059c](https://linux-hardware.org/?probe=6c4022059c) | Apr 19, 2022 |
| Lenovo        | 3000 N100 076835U           | Notebook    | [31a5dc6cf6](https://linux-hardware.org/?probe=31a5dc6cf6) | Apr 19, 2022 |
| Google        | Enguarde                    | Notebook    | [8a92222bf2](https://linux-hardware.org/?probe=8a92222bf2) | Apr 19, 2022 |
| MSI           | 2AE0                        | Desktop     | [da90dbf2f2](https://linux-hardware.org/?probe=da90dbf2f2) | Apr 19, 2022 |
| Dell          | Precision 5550              | Notebook    | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo        | ThinkPad T440p 20AWS03H0... | Notebook    | [0458ae6c71](https://linux-hardware.org/?probe=0458ae6c71) | Apr 19, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [a6cd5f07ee](https://linux-hardware.org/?probe=a6cd5f07ee) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7f4254b1b1](https://linux-hardware.org/?probe=7f4254b1b1) | Apr 19, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [5a75c038d2](https://linux-hardware.org/?probe=5a75c038d2) | Apr 19, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [d2125b0881](https://linux-hardware.org/?probe=d2125b0881) | Apr 19, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [8a262ac580](https://linux-hardware.org/?probe=8a262ac580) | Apr 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [d985c073a1](https://linux-hardware.org/?probe=d985c073a1) | Apr 19, 2022 |
| HP            | 18E7                        | Desktop     | [5f675779f1](https://linux-hardware.org/?probe=5f675779f1) | Apr 19, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [9cabfec30b](https://linux-hardware.org/?probe=9cabfec30b) | Apr 19, 2022 |
| HP            | 3397                        | Desktop     | [feeb7b4a56](https://linux-hardware.org/?probe=feeb7b4a56) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [93159530ba](https://linux-hardware.org/?probe=93159530ba) | Apr 19, 2022 |
| Sony          | VGN-SZ120P                  | Notebook    | [550f0939eb](https://linux-hardware.org/?probe=550f0939eb) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [e44ad7d84e](https://linux-hardware.org/?probe=e44ad7d84e) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [a010271a3d](https://linux-hardware.org/?probe=a010271a3d) | Apr 19, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [3a20d298f9](https://linux-hardware.org/?probe=3a20d298f9) | Apr 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [eff0448051](https://linux-hardware.org/?probe=eff0448051) | Apr 19, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [fc4ba6c008](https://linux-hardware.org/?probe=fc4ba6c008) | Apr 19, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [4fe85803b7](https://linux-hardware.org/?probe=4fe85803b7) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [d6203110b3](https://linux-hardware.org/?probe=d6203110b3) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [cb11a3f634](https://linux-hardware.org/?probe=cb11a3f634) | Apr 19, 2022 |
| HP            | Notebook                    | Notebook    | [b746d96b41](https://linux-hardware.org/?probe=b746d96b41) | Apr 19, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [7290650d08](https://linux-hardware.org/?probe=7290650d08) | Apr 19, 2022 |
| Alienware     | 0VDT73 A00                  | Desktop     | [1053bd7904](https://linux-hardware.org/?probe=1053bd7904) | Apr 18, 2022 |
| Sony          | VGN-SZ120P                  | Notebook    | [d8af65a51a](https://linux-hardware.org/?probe=d8af65a51a) | Apr 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dc42beaa8d](https://linux-hardware.org/?probe=dc42beaa8d) | Apr 18, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [f01fe0dd05](https://linux-hardware.org/?probe=f01fe0dd05) | Apr 18, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [fa995794ba](https://linux-hardware.org/?probe=fa995794ba) | Apr 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5d0b8a14f2](https://linux-hardware.org/?probe=5d0b8a14f2) | Apr 18, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [c8b6437680](https://linux-hardware.org/?probe=c8b6437680) | Apr 18, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [e6f96a585c](https://linux-hardware.org/?probe=e6f96a585c) | Apr 18, 2022 |
| Dell          | Latitude 7490               | Notebook    | [c1a1427ad0](https://linux-hardware.org/?probe=c1a1427ad0) | Apr 18, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [90597097b2](https://linux-hardware.org/?probe=90597097b2) | Apr 18, 2022 |
| Dell          | 06D7TR A01                  | Desktop     | [36f481beb4](https://linux-hardware.org/?probe=36f481beb4) | Apr 18, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [2cca37f312](https://linux-hardware.org/?probe=2cca37f312) | Apr 18, 2022 |
| HP            | G42                         | Notebook    | [18486c3d27](https://linux-hardware.org/?probe=18486c3d27) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [9f5287d8cb](https://linux-hardware.org/?probe=9f5287d8cb) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [b3f2a146ea](https://linux-hardware.org/?probe=b3f2a146ea) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [d597e4df9c](https://linux-hardware.org/?probe=d597e4df9c) | Apr 18, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ab4247484f](https://linux-hardware.org/?probe=ab4247484f) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [3bf424720c](https://linux-hardware.org/?probe=3bf424720c) | Apr 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [bbb26b6822](https://linux-hardware.org/?probe=bbb26b6822) | Apr 18, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [e1d2871cd8](https://linux-hardware.org/?probe=e1d2871cd8) | Apr 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f11d63b866](https://linux-hardware.org/?probe=f11d63b866) | Apr 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [add6d454bd](https://linux-hardware.org/?probe=add6d454bd) | Apr 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [c9e6f401ab](https://linux-hardware.org/?probe=c9e6f401ab) | Apr 18, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [028f7e340b](https://linux-hardware.org/?probe=028f7e340b) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [81b837dc13](https://linux-hardware.org/?probe=81b837dc13) | Apr 18, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [ebe60e3c9e](https://linux-hardware.org/?probe=ebe60e3c9e) | Apr 18, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [3a370d720b](https://linux-hardware.org/?probe=3a370d720b) | Apr 18, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a315b0490b](https://linux-hardware.org/?probe=a315b0490b) | Apr 18, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7178bd9e1d](https://linux-hardware.org/?probe=7178bd9e1d) | Apr 18, 2022 |
| Acer          | TMP645-M                    | Notebook    | [9b20e644dd](https://linux-hardware.org/?probe=9b20e644dd) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [bd331015ea](https://linux-hardware.org/?probe=bd331015ea) | Apr 18, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [c661d7a105](https://linux-hardware.org/?probe=c661d7a105) | Apr 18, 2022 |
| HP            | Spectre Notebook            | Notebook    | [42d4ceac84](https://linux-hardware.org/?probe=42d4ceac84) | Apr 18, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [7bac0abf51](https://linux-hardware.org/?probe=7bac0abf51) | Apr 18, 2022 |
| ASUSTek       | U47A                        | Notebook    | [575ed9230d](https://linux-hardware.org/?probe=575ed9230d) | Apr 17, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [4d29f7d8eb](https://linux-hardware.org/?probe=4d29f7d8eb) | Apr 17, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [7b61fb0ba4](https://linux-hardware.org/?probe=7b61fb0ba4) | Apr 17, 2022 |
| HP            | 339A                        | Desktop     | [7949378026](https://linux-hardware.org/?probe=7949378026) | Apr 17, 2022 |
| Timi          | A7S                         | Notebook    | [a9d2b97739](https://linux-hardware.org/?probe=a9d2b97739) | Apr 17, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | Notebook    | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| HP            | 1850                        | Desktop     | [7c24268bc3](https://linux-hardware.org/?probe=7c24268bc3) | Apr 17, 2022 |
| Dell          | Latitude 5490               | Notebook    | [04964a95f3](https://linux-hardware.org/?probe=04964a95f3) | Apr 17, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [52a97f186f](https://linux-hardware.org/?probe=52a97f186f) | Apr 17, 2022 |
| Framework     | Laptop                      | Notebook    | [acad8f1ccb](https://linux-hardware.org/?probe=acad8f1ccb) | Apr 17, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [abdd8db787](https://linux-hardware.org/?probe=abdd8db787) | Apr 17, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f11c0320c0](https://linux-hardware.org/?probe=f11c0320c0) | Apr 17, 2022 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [42836ca452](https://linux-hardware.org/?probe=42836ca452) | Apr 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [170b2f2002](https://linux-hardware.org/?probe=170b2f2002) | Apr 17, 2022 |
| CompuLab      | fitlet                      | Mini pc     | [556d51f12c](https://linux-hardware.org/?probe=556d51f12c) | Apr 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0ca03714c7](https://linux-hardware.org/?probe=0ca03714c7) | Apr 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [cd9d75f503](https://linux-hardware.org/?probe=cd9d75f503) | Apr 17, 2022 |
| HP            | 18E4                        | Desktop     | [695c520694](https://linux-hardware.org/?probe=695c520694) | Apr 17, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [4e70c05231](https://linux-hardware.org/?probe=4e70c05231) | Apr 17, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [ef65603ba9](https://linux-hardware.org/?probe=ef65603ba9) | Apr 17, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [278ccbaf44](https://linux-hardware.org/?probe=278ccbaf44) | Apr 17, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [f0d5c82d74](https://linux-hardware.org/?probe=f0d5c82d74) | Apr 17, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [441b2fd4ab](https://linux-hardware.org/?probe=441b2fd4ab) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [601e55a0a8](https://linux-hardware.org/?probe=601e55a0a8) | Apr 17, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [b109942662](https://linux-hardware.org/?probe=b109942662) | Apr 17, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [49f90b075b](https://linux-hardware.org/?probe=49f90b075b) | Apr 17, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [f273c6051a](https://linux-hardware.org/?probe=f273c6051a) | Apr 17, 2022 |
| Google        | Candy                       | Notebook    | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [30cb790818](https://linux-hardware.org/?probe=30cb790818) | Apr 17, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [4dbd302f8c](https://linux-hardware.org/?probe=4dbd302f8c) | Apr 17, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [000a991767](https://linux-hardware.org/?probe=000a991767) | Apr 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4151908bf](https://linux-hardware.org/?probe=f4151908bf) | Apr 17, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [9123d206b0](https://linux-hardware.org/?probe=9123d206b0) | Apr 16, 2022 |
| HP            | ENVY TS 17                  | Notebook    | [83c35e58d5](https://linux-hardware.org/?probe=83c35e58d5) | Apr 16, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [1cfc273a11](https://linux-hardware.org/?probe=1cfc273a11) | Apr 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f7292b20a](https://linux-hardware.org/?probe=1f7292b20a) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [800aefa57e](https://linux-hardware.org/?probe=800aefa57e) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e9fccc0549](https://linux-hardware.org/?probe=e9fccc0549) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| AZW           | U59                         | Desktop     | [fc7e5f0c5c](https://linux-hardware.org/?probe=fc7e5f0c5c) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a37c8a7b48](https://linux-hardware.org/?probe=a37c8a7b48) | Apr 16, 2022 |
| AZW           | U59                         | Desktop     | [377d280037](https://linux-hardware.org/?probe=377d280037) | Apr 16, 2022 |
| Alienware     | Area-51m R2                 | Notebook    | [e6a7b0ef42](https://linux-hardware.org/?probe=e6a7b0ef42) | Apr 16, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7c543b7a6e](https://linux-hardware.org/?probe=7c543b7a6e) | Apr 16, 2022 |
| GMKTEC        | NucBox4                     | Mini pc     | [d29e9757d0](https://linux-hardware.org/?probe=d29e9757d0) | Apr 16, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0d918922ac](https://linux-hardware.org/?probe=0d918922ac) | Apr 16, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [dc1e145cf3](https://linux-hardware.org/?probe=dc1e145cf3) | Apr 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [a8c0eeb473](https://linux-hardware.org/?probe=a8c0eeb473) | Apr 16, 2022 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [d789592552](https://linux-hardware.org/?probe=d789592552) | Apr 16, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [9a5d59c375](https://linux-hardware.org/?probe=9a5d59c375) | Apr 16, 2022 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [333287a94f](https://linux-hardware.org/?probe=333287a94f) | Apr 16, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [65b68d5bb9](https://linux-hardware.org/?probe=65b68d5bb9) | Apr 16, 2022 |
| Dell          | 06D7TR A01                  | Desktop     | [9a21a6c0f4](https://linux-hardware.org/?probe=9a21a6c0f4) | Apr 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e3658d7c35](https://linux-hardware.org/?probe=e3658d7c35) | Apr 16, 2022 |
| Dell          | 0DN075                      | Desktop     | [05bd1b50f1](https://linux-hardware.org/?probe=05bd1b50f1) | Apr 16, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2ed6fa2459](https://linux-hardware.org/?probe=2ed6fa2459) | Apr 16, 2022 |
| HP            | Pavilion m7                 | Notebook    | [ed02e5b37c](https://linux-hardware.org/?probe=ed02e5b37c) | Apr 16, 2022 |
| Lenovo        | ThinkPad P50s 20FL000MUS    | Notebook    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Supermicro    | H8QG6                       | Desktop     | [060f1e3d34](https://linux-hardware.org/?probe=060f1e3d34) | Apr 16, 2022 |
| Dell          | 0VYXHD A00                  | Desktop     | [4280de633d](https://linux-hardware.org/?probe=4280de633d) | Apr 16, 2022 |
| Google        | Phaser360                   | Notebook    | [ab97623a21](https://linux-hardware.org/?probe=ab97623a21) | Apr 16, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [90c143abed](https://linux-hardware.org/?probe=90c143abed) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [b0a5b307c9](https://linux-hardware.org/?probe=b0a5b307c9) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS03H0... | Notebook    | [64fb4146d0](https://linux-hardware.org/?probe=64fb4146d0) | Apr 16, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [81dced5e0a](https://linux-hardware.org/?probe=81dced5e0a) | Apr 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4cf57abb44](https://linux-hardware.org/?probe=4cf57abb44) | Apr 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6f358d55e7](https://linux-hardware.org/?probe=6f358d55e7) | Apr 16, 2022 |
| HP            | 14                          | Notebook    | [2a8a40d96b](https://linux-hardware.org/?probe=2a8a40d96b) | Apr 16, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [9ba73648b1](https://linux-hardware.org/?probe=9ba73648b1) | Apr 16, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [2b2833576e](https://linux-hardware.org/?probe=2b2833576e) | Apr 16, 2022 |
| Dell          | Inspiron 7300 2n1           | Convertible | [17b7ab1ae3](https://linux-hardware.org/?probe=17b7ab1ae3) | Apr 16, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| MSI           | 2AE0                        | Desktop     | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [53cc2d28a7](https://linux-hardware.org/?probe=53cc2d28a7) | Apr 15, 2022 |
| ASUSTek       | U47A                        | Notebook    | [9634258fee](https://linux-hardware.org/?probe=9634258fee) | Apr 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c8161370ea](https://linux-hardware.org/?probe=c8161370ea) | Apr 15, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [d7f72a830c](https://linux-hardware.org/?probe=d7f72a830c) | Apr 15, 2022 |
| Google        | Enguarde                    | Notebook    | [6e1d5488f8](https://linux-hardware.org/?probe=6e1d5488f8) | Apr 15, 2022 |
| Unknown       | HX90                        | Desktop     | [a9b1d5a579](https://linux-hardware.org/?probe=a9b1d5a579) | Apr 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [b1e71b5b4c](https://linux-hardware.org/?probe=b1e71b5b4c) | Apr 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [539ce7e59a](https://linux-hardware.org/?probe=539ce7e59a) | Apr 15, 2022 |
| Alienware     | x17 R1                      | Notebook    | [86a2d88704](https://linux-hardware.org/?probe=86a2d88704) | Apr 15, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [623024de22](https://linux-hardware.org/?probe=623024de22) | Apr 15, 2022 |
| Google        | Enguarde                    | Notebook    | [7c4a4092d5](https://linux-hardware.org/?probe=7c4a4092d5) | Apr 15, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [b95a9bcbf0](https://linux-hardware.org/?probe=b95a9bcbf0) | Apr 15, 2022 |
| Google        | Enguarde                    | Notebook    | [26c2f26771](https://linux-hardware.org/?probe=26c2f26771) | Apr 15, 2022 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [521cf503e2](https://linux-hardware.org/?probe=521cf503e2) | Apr 15, 2022 |
| Sony          | VPCF115FM                   | Notebook    | [b174df5915](https://linux-hardware.org/?probe=b174df5915) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| HP            | 2129                        | Desktop     | [be64efcffd](https://linux-hardware.org/?probe=be64efcffd) | Apr 15, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| Google        | Enguarde                    | Notebook    | [f0ec477b78](https://linux-hardware.org/?probe=f0ec477b78) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d14605acc1](https://linux-hardware.org/?probe=d14605acc1) | Apr 15, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [d92d515d6b](https://linux-hardware.org/?probe=d92d515d6b) | Apr 15, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [32b40d296d](https://linux-hardware.org/?probe=32b40d296d) | Apr 15, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [fc39ac9f46](https://linux-hardware.org/?probe=fc39ac9f46) | Apr 15, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [96eae556f2](https://linux-hardware.org/?probe=96eae556f2) | Apr 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e9969def2d](https://linux-hardware.org/?probe=e9969def2d) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [96faf32841](https://linux-hardware.org/?probe=96faf32841) | Apr 15, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [78da1f043b](https://linux-hardware.org/?probe=78da1f043b) | Apr 15, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |
| Dell          | Studio 1537                 | Notebook    | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [89fb08092b](https://linux-hardware.org/?probe=89fb08092b) | Apr 15, 2022 |
| Dell          | Precision 5560              | Notebook    | [54914c0033](https://linux-hardware.org/?probe=54914c0033) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [edca3eae97](https://linux-hardware.org/?probe=edca3eae97) | Apr 15, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [d7c378ac40](https://linux-hardware.org/?probe=d7c378ac40) | Apr 15, 2022 |
| Intel         | DQ67EP AAG12529-307         | Desktop     | [8e345bbb6a](https://linux-hardware.org/?probe=8e345bbb6a) | Apr 15, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [f9b54f42f5](https://linux-hardware.org/?probe=f9b54f42f5) | Apr 15, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [499a00bcf8](https://linux-hardware.org/?probe=499a00bcf8) | Apr 15, 2022 |
| Dell          | Precision M4700             | Notebook    | [850dba476c](https://linux-hardware.org/?probe=850dba476c) | Apr 15, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [dcae73146f](https://linux-hardware.org/?probe=dcae73146f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7e8c906437](https://linux-hardware.org/?probe=7e8c906437) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [92da438638](https://linux-hardware.org/?probe=92da438638) | Apr 15, 2022 |
| ASUSTek       | Q302LA                      | Notebook    | [9bcb945cba](https://linux-hardware.org/?probe=9bcb945cba) | Apr 15, 2022 |
| Nvidia        | Jetson Xavier NX Develop... | Soc         | [a786d1f74e](https://linux-hardware.org/?probe=a786d1f74e) | Apr 15, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9391400fc7](https://linux-hardware.org/?probe=9391400fc7) | Apr 14, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [eec6d07447](https://linux-hardware.org/?probe=eec6d07447) | Apr 14, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [5b4d5a6e7a](https://linux-hardware.org/?probe=5b4d5a6e7a) | Apr 14, 2022 |
| Lenovo        | ThinkPad T440 20B7S1970B    | Notebook    | [055812a1f1](https://linux-hardware.org/?probe=055812a1f1) | Apr 14, 2022 |
| Getac         | S410                        | Notebook    | [a0ec8cd50e](https://linux-hardware.org/?probe=a0ec8cd50e) | Apr 14, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [d8235b139b](https://linux-hardware.org/?probe=d8235b139b) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [3f5020068f](https://linux-hardware.org/?probe=3f5020068f) | Apr 14, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [832620cf67](https://linux-hardware.org/?probe=832620cf67) | Apr 14, 2022 |
| Dell          | 0WPG9H A01                  | All in one  | [f5abf0c2d1](https://linux-hardware.org/?probe=f5abf0c2d1) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [a5950266d1](https://linux-hardware.org/?probe=a5950266d1) | Apr 14, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ffe2d9db36](https://linux-hardware.org/?probe=ffe2d9db36) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [c54f344fdb](https://linux-hardware.org/?probe=c54f344fdb) | Apr 14, 2022 |
| Sony          | VPCF115FM                   | Notebook    | [03f96804b2](https://linux-hardware.org/?probe=03f96804b2) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0bd7facf9b](https://linux-hardware.org/?probe=0bd7facf9b) | Apr 14, 2022 |
| HP            | 21EF                        | Desktop     | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [17622a538e](https://linux-hardware.org/?probe=17622a538e) | Apr 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [cc1fade012](https://linux-hardware.org/?probe=cc1fade012) | Apr 14, 2022 |
| NZXT          | N7 B550                     | Desktop     | [71e92a4807](https://linux-hardware.org/?probe=71e92a4807) | Apr 14, 2022 |
| Dell          | Inspiron 7375               | Notebook    | [aa96823ff7](https://linux-hardware.org/?probe=aa96823ff7) | Apr 14, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | Notebook    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c49c891a78](https://linux-hardware.org/?probe=c49c891a78) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [089fb5aac7](https://linux-hardware.org/?probe=089fb5aac7) | Apr 14, 2022 |
| Lenovo        | ThinkPad T450 20BV000AUS    | Notebook    | [85267dc4f7](https://linux-hardware.org/?probe=85267dc4f7) | Apr 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b30795783f](https://linux-hardware.org/?probe=b30795783f) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [f0cbf88366](https://linux-hardware.org/?probe=f0cbf88366) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [6846ee88e0](https://linux-hardware.org/?probe=6846ee88e0) | Apr 14, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [819cf0afbc](https://linux-hardware.org/?probe=819cf0afbc) | Apr 14, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [893e3f4940](https://linux-hardware.org/?probe=893e3f4940) | Apr 14, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [bfa1733e6a](https://linux-hardware.org/?probe=bfa1733e6a) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [411f63de57](https://linux-hardware.org/?probe=411f63de57) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [3fd74b2f86](https://linux-hardware.org/?probe=3fd74b2f86) | Apr 14, 2022 |
| Google        | Enguarde                    | Notebook    | [b06b81bc8f](https://linux-hardware.org/?probe=b06b81bc8f) | Apr 14, 2022 |
| Gateway       | NV59C                       | Notebook    | [cce0d00cc1](https://linux-hardware.org/?probe=cce0d00cc1) | Apr 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [7bdc6ca6ed](https://linux-hardware.org/?probe=7bdc6ca6ed) | Apr 14, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [184356c1d7](https://linux-hardware.org/?probe=184356c1d7) | Apr 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [41b0487e91](https://linux-hardware.org/?probe=41b0487e91) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | Desktop     | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| Dell          | Precision 5540              | Notebook    | [cc5b5069ae](https://linux-hardware.org/?probe=cc5b5069ae) | Apr 14, 2022 |
| HP            | 158B                        | Desktop     | [01b455c74a](https://linux-hardware.org/?probe=01b455c74a) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 41786UU       | Notebook    | [2211278055](https://linux-hardware.org/?probe=2211278055) | Apr 14, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [3f0d544715](https://linux-hardware.org/?probe=3f0d544715) | Apr 14, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [0276364302](https://linux-hardware.org/?probe=0276364302) | Apr 14, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [b7df514e20](https://linux-hardware.org/?probe=b7df514e20) | Apr 14, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [a816c79e4e](https://linux-hardware.org/?probe=a816c79e4e) | Apr 14, 2022 |
| Dell          | 014GRG A00                  | Desktop     | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| Dell          | G5 5505                     | Notebook    | [7c8b949b95](https://linux-hardware.org/?probe=7c8b949b95) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [6d4e35a28f](https://linux-hardware.org/?probe=6d4e35a28f) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | Notebook    | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d0933b6a76](https://linux-hardware.org/?probe=d0933b6a76) | Apr 14, 2022 |
| Lenovo        | ThinkPad T550 20CKCTO1WW    | Notebook    | [81d6a811d5](https://linux-hardware.org/?probe=81d6a811d5) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [6e22aff30c](https://linux-hardware.org/?probe=6e22aff30c) | Apr 14, 2022 |
| ASRock        | AB350M                      | Desktop     | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [9200891771](https://linux-hardware.org/?probe=9200891771) | Apr 14, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [84815ec94e](https://linux-hardware.org/?probe=84815ec94e) | Apr 14, 2022 |
| Dell          | 0D28YY A02                  | Desktop     | [c1ff26008f](https://linux-hardware.org/?probe=c1ff26008f) | Apr 14, 2022 |
| Dell          | 0GN6JF A01                  | Desktop     | [c215aa8e06](https://linux-hardware.org/?probe=c215aa8e06) | Apr 14, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [47f495eda5](https://linux-hardware.org/?probe=47f495eda5) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | Notebook    | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Dell          | Inspiron One 2320           | All in one  | [dfdb90274e](https://linux-hardware.org/?probe=dfdb90274e) | Apr 14, 2022 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [77d75fd5b2](https://linux-hardware.org/?probe=77d75fd5b2) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [e579135b1d](https://linux-hardware.org/?probe=e579135b1d) | Apr 14, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [4296dc030e](https://linux-hardware.org/?probe=4296dc030e) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7e080e5205](https://linux-hardware.org/?probe=7e080e5205) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [16d27bad7a](https://linux-hardware.org/?probe=16d27bad7a) | Apr 14, 2022 |
| System76      | Serval WS                   | Notebook    | [f02bcd64a2](https://linux-hardware.org/?probe=f02bcd64a2) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [b9a5212f6c](https://linux-hardware.org/?probe=b9a5212f6c) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [a21bd26d1e](https://linux-hardware.org/?probe=a21bd26d1e) | Apr 14, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [3cbf78454e](https://linux-hardware.org/?probe=3cbf78454e) | Apr 14, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| Lenovo        | IdeaPad 710S Plus Touch-... | Notebook    | [f4578ea652](https://linux-hardware.org/?probe=f4578ea652) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1a7a8bf92e](https://linux-hardware.org/?probe=1a7a8bf92e) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [52d05bca1d](https://linux-hardware.org/?probe=52d05bca1d) | Apr 13, 2022 |
| ASRock        | A320M-ITX                   | Desktop     | [eaf6bbd74e](https://linux-hardware.org/?probe=eaf6bbd74e) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [744144c472](https://linux-hardware.org/?probe=744144c472) | Apr 13, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [061aeeecf7](https://linux-hardware.org/?probe=061aeeecf7) | Apr 13, 2022 |
| Dell          | Inspiron 7375               | Notebook    | [14bf6ad207](https://linux-hardware.org/?probe=14bf6ad207) | Apr 13, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [1771fcfd14](https://linux-hardware.org/?probe=1771fcfd14) | Apr 13, 2022 |
| Google        | Enguarde                    | Notebook    | [7accbcbfdb](https://linux-hardware.org/?probe=7accbcbfdb) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [e0ebd58f3d](https://linux-hardware.org/?probe=e0ebd58f3d) | Apr 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [b7043f3712](https://linux-hardware.org/?probe=b7043f3712) | Apr 13, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [20ed59527a](https://linux-hardware.org/?probe=20ed59527a) | Apr 13, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [8f3e545e28](https://linux-hardware.org/?probe=8f3e545e28) | Apr 13, 2022 |
| Intel         | D945GCL AAD82064-200        | Desktop     | [c6d6c5a3df](https://linux-hardware.org/?probe=c6d6c5a3df) | Apr 13, 2022 |
| Gigabyte      | Z77-HD4                     | Desktop     | [f6323a1611](https://linux-hardware.org/?probe=f6323a1611) | Apr 13, 2022 |
| Dell          | 0RY007                      | Desktop     | [f4384d4c1e](https://linux-hardware.org/?probe=f4384d4c1e) | Apr 13, 2022 |
| Lenovo        | ThinkPad T440p 20AN006GU... | Notebook    | [8c26cf3ce0](https://linux-hardware.org/?probe=8c26cf3ce0) | Apr 13, 2022 |
| Dell          | 0YC03K A04                  | Desktop     | [4fd6bd10ff](https://linux-hardware.org/?probe=4fd6bd10ff) | Apr 13, 2022 |
| Dell          | 084YMW A05                  | Server      | [f08f5999ac](https://linux-hardware.org/?probe=f08f5999ac) | Apr 13, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [db7617dfb0](https://linux-hardware.org/?probe=db7617dfb0) | Apr 13, 2022 |
| Dell          | Precision 7540              | Notebook    | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [aada4d4d5e](https://linux-hardware.org/?probe=aada4d4d5e) | Apr 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3cc44dcc8f](https://linux-hardware.org/?probe=3cc44dcc8f) | Apr 13, 2022 |
| HP            | 83E0                        | Desktop     | [6d3109eba8](https://linux-hardware.org/?probe=6d3109eba8) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [01e2f073c1](https://linux-hardware.org/?probe=01e2f073c1) | Apr 13, 2022 |
| Foxconn       | 2AB7                        | Desktop     | [1f974543fc](https://linux-hardware.org/?probe=1f974543fc) | Apr 13, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [5f2f221d6c](https://linux-hardware.org/?probe=5f2f221d6c) | Apr 13, 2022 |
| Dell          | Precision 5760              | Notebook    | [546a52d1a9](https://linux-hardware.org/?probe=546a52d1a9) | Apr 13, 2022 |
| MSI           | GX70 3BE                    | Notebook    | [995842e632](https://linux-hardware.org/?probe=995842e632) | Apr 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2d62a54d55](https://linux-hardware.org/?probe=2d62a54d55) | Apr 13, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Unknown       | Unknown                     | Soc         | [43769378a7](https://linux-hardware.org/?probe=43769378a7) | Apr 13, 2022 |
| Dell          | Precision 5760              | Notebook    | [11cd26ed64](https://linux-hardware.org/?probe=11cd26ed64) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [315cbe72dd](https://linux-hardware.org/?probe=315cbe72dd) | Apr 13, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [dcca838772](https://linux-hardware.org/?probe=dcca838772) | Apr 13, 2022 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [600b198520](https://linux-hardware.org/?probe=600b198520) | Apr 13, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | Notebook    | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [964485a193](https://linux-hardware.org/?probe=964485a193) | Apr 13, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3f181a161f](https://linux-hardware.org/?probe=3f181a161f) | Apr 13, 2022 |
| System76      | Thelio Major thelio-majo... | Desktop     | [5924b8c844](https://linux-hardware.org/?probe=5924b8c844) | Apr 13, 2022 |
| Lenovo        | NOK                         | Desktop     | [f99d93fc1e](https://linux-hardware.org/?probe=f99d93fc1e) | Apr 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [bceb7ff5a3](https://linux-hardware.org/?probe=bceb7ff5a3) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b076cac85d](https://linux-hardware.org/?probe=b076cac85d) | Apr 13, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [24b2dc344a](https://linux-hardware.org/?probe=24b2dc344a) | Apr 13, 2022 |
| System76      | Pangolin                    | Notebook    | [3976805ed7](https://linux-hardware.org/?probe=3976805ed7) | Apr 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [b2fc1649d1](https://linux-hardware.org/?probe=b2fc1649d1) | Apr 13, 2022 |
| Dell          | 0WVYMC A00                  | Desktop     | [e2f9d3638d](https://linux-hardware.org/?probe=e2f9d3638d) | Apr 13, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [8a64db97de](https://linux-hardware.org/?probe=8a64db97de) | Apr 13, 2022 |
| Lenovo        | ThinkPad T420 N1004Z1       | Notebook    | [b92e24104f](https://linux-hardware.org/?probe=b92e24104f) | Apr 13, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e048f91515](https://linux-hardware.org/?probe=e048f91515) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [dd7183fda2](https://linux-hardware.org/?probe=dd7183fda2) | Apr 13, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [79b33f857d](https://linux-hardware.org/?probe=79b33f857d) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [70b154b039](https://linux-hardware.org/?probe=70b154b039) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | Desktop     | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [7f3347b13e](https://linux-hardware.org/?probe=7f3347b13e) | Apr 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [dbe88a4373](https://linux-hardware.org/?probe=dbe88a4373) | Apr 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [11ca71a8e4](https://linux-hardware.org/?probe=11ca71a8e4) | Apr 13, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Dell          | Latitude 5580               | Notebook    | [3d7b173021](https://linux-hardware.org/?probe=3d7b173021) | Apr 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5aa4b5ec65](https://linux-hardware.org/?probe=5aa4b5ec65) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [dba21fb2d0](https://linux-hardware.org/?probe=dba21fb2d0) | Apr 13, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [47267431ed](https://linux-hardware.org/?probe=47267431ed) | Apr 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [95a47dfd7f](https://linux-hardware.org/?probe=95a47dfd7f) | Apr 13, 2022 |
| System76      | Oryx Pro                    | Notebook    | [bfba9dbec0](https://linux-hardware.org/?probe=bfba9dbec0) | Apr 13, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [01f7261143](https://linux-hardware.org/?probe=01f7261143) | Apr 13, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [28c58dfde0](https://linux-hardware.org/?probe=28c58dfde0) | Apr 13, 2022 |
| Dell          | G5 5505                     | Notebook    | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [6dc94a82ab](https://linux-hardware.org/?probe=6dc94a82ab) | Apr 13, 2022 |
| HP            | 829A                        | Mini pc     | [82d14c37b5](https://linux-hardware.org/?probe=82d14c37b5) | Apr 13, 2022 |
| Dell          | Precision 7550              | Notebook    | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Dell          | Precision 5550              | Notebook    | [08ecd3525d](https://linux-hardware.org/?probe=08ecd3525d) | Apr 13, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [0af514ea2b](https://linux-hardware.org/?probe=0af514ea2b) | Apr 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [fa4a611c3a](https://linux-hardware.org/?probe=fa4a611c3a) | Apr 13, 2022 |
| Framework     | Laptop                      | Notebook    | [6de996aa1e](https://linux-hardware.org/?probe=6de996aa1e) | Apr 13, 2022 |
| HP            | 18E4                        | Desktop     | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | Desktop     | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [5792134e78](https://linux-hardware.org/?probe=5792134e78) | Apr 13, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [e2d3867bd4](https://linux-hardware.org/?probe=e2d3867bd4) | Apr 13, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6267f2f88d](https://linux-hardware.org/?probe=6267f2f88d) | Apr 13, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [ee1ec3e09d](https://linux-hardware.org/?probe=ee1ec3e09d) | Apr 13, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [a6c665d142](https://linux-hardware.org/?probe=a6c665d142) | Apr 13, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [be27a452e2](https://linux-hardware.org/?probe=be27a452e2) | Apr 13, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5adcbc1b64](https://linux-hardware.org/?probe=5adcbc1b64) | Apr 13, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [19bfd91984](https://linux-hardware.org/?probe=19bfd91984) | Apr 13, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [13a7544bd3](https://linux-hardware.org/?probe=13a7544bd3) | Apr 13, 2022 |
| ASUSTek       | G752VL                      | Notebook    | [910e126de2](https://linux-hardware.org/?probe=910e126de2) | Apr 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [a37b2c860f](https://linux-hardware.org/?probe=a37b2c860f) | Apr 13, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [d2672b76fa](https://linux-hardware.org/?probe=d2672b76fa) | Apr 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [4d5c3fc937](https://linux-hardware.org/?probe=4d5c3fc937) | Apr 13, 2022 |
| Unknown       | Unknown                     | Soc         | [58b8028451](https://linux-hardware.org/?probe=58b8028451) | Apr 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4a6bf4ec79](https://linux-hardware.org/?probe=4a6bf4ec79) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [46ce27bfa6](https://linux-hardware.org/?probe=46ce27bfa6) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [ce5b3c38ab](https://linux-hardware.org/?probe=ce5b3c38ab) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [0b0db918aa](https://linux-hardware.org/?probe=0b0db918aa) | Apr 13, 2022 |
| Dell          | 00NH4P A14                  | Server      | [274931609f](https://linux-hardware.org/?probe=274931609f) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [3385b17dd8](https://linux-hardware.org/?probe=3385b17dd8) | Apr 13, 2022 |
| Dell          | Latitude E6420              | Notebook    | [db57e5f43d](https://linux-hardware.org/?probe=db57e5f43d) | Apr 13, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [5a0a8374bd](https://linux-hardware.org/?probe=5a0a8374bd) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [0d300b2fc3](https://linux-hardware.org/?probe=0d300b2fc3) | Apr 12, 2022 |
| HP            | Presario CQ57               | Notebook    | [ece28d4d57](https://linux-hardware.org/?probe=ece28d4d57) | Apr 12, 2022 |
| Foxconn       | 2AB7                        | Desktop     | [7a75548677](https://linux-hardware.org/?probe=7a75548677) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M71e 5033A3U    | Desktop     | [9b0b83369e](https://linux-hardware.org/?probe=9b0b83369e) | Apr 12, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [cabbac0657](https://linux-hardware.org/?probe=cabbac0657) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [32f07398c4](https://linux-hardware.org/?probe=32f07398c4) | Apr 12, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [52828f419f](https://linux-hardware.org/?probe=52828f419f) | Apr 12, 2022 |
| Pegatron      | 2A86E01                     | Desktop     | [605526fdad](https://linux-hardware.org/?probe=605526fdad) | Apr 12, 2022 |
| Dell          | Latitude E6430              | Notebook    | [88e38083ac](https://linux-hardware.org/?probe=88e38083ac) | Apr 12, 2022 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [401c412e61](https://linux-hardware.org/?probe=401c412e61) | Apr 12, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [9b5a7ca73e](https://linux-hardware.org/?probe=9b5a7ca73e) | Apr 12, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d7659bd74](https://linux-hardware.org/?probe=4d7659bd74) | Apr 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [68dd0c90a1](https://linux-hardware.org/?probe=68dd0c90a1) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [93ec29bb99](https://linux-hardware.org/?probe=93ec29bb99) | Apr 12, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [2c0a8e3ad5](https://linux-hardware.org/?probe=2c0a8e3ad5) | Apr 12, 2022 |
| MSI           | GL65 9SC                    | Notebook    | [2a533aa287](https://linux-hardware.org/?probe=2a533aa287) | Apr 12, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [6ad3d2d565](https://linux-hardware.org/?probe=6ad3d2d565) | Apr 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [e43f2609cc](https://linux-hardware.org/?probe=e43f2609cc) | Apr 12, 2022 |
| System76      | Darter Pro                  | Notebook    | [669d3cf4e4](https://linux-hardware.org/?probe=669d3cf4e4) | Apr 12, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [9ae1f72e77](https://linux-hardware.org/?probe=9ae1f72e77) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M91P 7034A2U    | Desktop     | [a5b9a57a64](https://linux-hardware.org/?probe=a5b9a57a64) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Razer         | Blade                       | Notebook    | [13c7eb09fa](https://linux-hardware.org/?probe=13c7eb09fa) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [dc635b2efb](https://linux-hardware.org/?probe=dc635b2efb) | Apr 12, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [ceb55f32d7](https://linux-hardware.org/?probe=ceb55f32d7) | Apr 12, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [617c029290](https://linux-hardware.org/?probe=617c029290) | Apr 12, 2022 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [082a102be9](https://linux-hardware.org/?probe=082a102be9) | Apr 12, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [69fbad2150](https://linux-hardware.org/?probe=69fbad2150) | Apr 12, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [b9f39d99ba](https://linux-hardware.org/?probe=b9f39d99ba) | Apr 12, 2022 |
| Framework     | Laptop                      | Notebook    | [02b837b78a](https://linux-hardware.org/?probe=02b837b78a) | Apr 12, 2022 |
| MSI           | GE76 Raider 11UE            | Notebook    | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Supermicro    | X8DTN                       | Server      | [6668785c6e](https://linux-hardware.org/?probe=6668785c6e) | Apr 12, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [839b9579c3](https://linux-hardware.org/?probe=839b9579c3) | Apr 12, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cee28f4953](https://linux-hardware.org/?probe=cee28f4953) | Apr 12, 2022 |
| ASUSTek       | M11BB                       | Desktop     | [6e0e26d007](https://linux-hardware.org/?probe=6e0e26d007) | Apr 12, 2022 |
| ASUSTek       | M11BB                       | Desktop     | [caf3596edc](https://linux-hardware.org/?probe=caf3596edc) | Apr 11, 2022 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [9618216033](https://linux-hardware.org/?probe=9618216033) | Apr 11, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ee2c10f4b2](https://linux-hardware.org/?probe=ee2c10f4b2) | Apr 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [14cec557dd](https://linux-hardware.org/?probe=14cec557dd) | Apr 11, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [aff1557d72](https://linux-hardware.org/?probe=aff1557d72) | Apr 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fd26a6f906](https://linux-hardware.org/?probe=fd26a6f906) | Apr 11, 2022 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [10d0131978](https://linux-hardware.org/?probe=10d0131978) | Apr 11, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [8c6cc15607](https://linux-hardware.org/?probe=8c6cc15607) | Apr 11, 2022 |
| Toshiba       | Satellite E55-A             | Notebook    | [dc9e2fd729](https://linux-hardware.org/?probe=dc9e2fd729) | Apr 11, 2022 |
| Dell          | 0HJ054                      | Desktop     | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |
| ASUSTek       | P5B                         | Desktop     | [c8191103ef](https://linux-hardware.org/?probe=c8191103ef) | Apr 11, 2022 |
| Notebook      | X170KM-G                    | Notebook    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b181b35e18](https://linux-hardware.org/?probe=b181b35e18) | Apr 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [285b194f70](https://linux-hardware.org/?probe=285b194f70) | Apr 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [17dd873118](https://linux-hardware.org/?probe=17dd873118) | Apr 11, 2022 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [7536bcd98d](https://linux-hardware.org/?probe=7536bcd98d) | Apr 11, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [69eac21427](https://linux-hardware.org/?probe=69eac21427) | Apr 11, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [c80f104836](https://linux-hardware.org/?probe=c80f104836) | Apr 11, 2022 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [20e831b4af](https://linux-hardware.org/?probe=20e831b4af) | Apr 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [3f5e320c89](https://linux-hardware.org/?probe=3f5e320c89) | Apr 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [af85d08115](https://linux-hardware.org/?probe=af85d08115) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| Intel         | powered classmate PC        | Notebook    | [39f9a3dcac](https://linux-hardware.org/?probe=39f9a3dcac) | Apr 11, 2022 |
| ASUSTek       | Q302LA                      | Notebook    | [b93cabbcf4](https://linux-hardware.org/?probe=b93cabbcf4) | Apr 11, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| Dell          | Studio 1537                 | Notebook    | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [5711914b1c](https://linux-hardware.org/?probe=5711914b1c) | Apr 11, 2022 |
| Alienware     | M17xR4                      | Notebook    | [2cfdbdd572](https://linux-hardware.org/?probe=2cfdbdd572) | Apr 11, 2022 |
| ASUSTek       | Amberine M                  | Desktop     | [e47a1f2886](https://linux-hardware.org/?probe=e47a1f2886) | Apr 11, 2022 |
| ASRock        | B250M Performance           | Desktop     | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [1d1ff81694](https://linux-hardware.org/?probe=1d1ff81694) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| ASUSTek       | G752VL                      | Notebook    | [ee065014a8](https://linux-hardware.org/?probe=ee065014a8) | Apr 11, 2022 |
| MSI           | H81M-E33                    | Desktop     | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| HP            | 15                          | Notebook    | [5aeb5a94c1](https://linux-hardware.org/?probe=5aeb5a94c1) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [c3d5951840](https://linux-hardware.org/?probe=c3d5951840) | Apr 10, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [94fccb48fd](https://linux-hardware.org/?probe=94fccb48fd) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [36b98241e2](https://linux-hardware.org/?probe=36b98241e2) | Apr 10, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e1b3743bc7](https://linux-hardware.org/?probe=e1b3743bc7) | Apr 10, 2022 |
| HP            | 0A64h                       | Desktop     | [45c89ff83d](https://linux-hardware.org/?probe=45c89ff83d) | Apr 10, 2022 |
| Dell          | Precision M6800             | Notebook    | [571eab63d2](https://linux-hardware.org/?probe=571eab63d2) | Apr 10, 2022 |
| Dell          | Precision M6800             | Notebook    | [236217f64d](https://linux-hardware.org/?probe=236217f64d) | Apr 10, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [cb8b648eac](https://linux-hardware.org/?probe=cb8b648eac) | Apr 10, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [a62a7338e9](https://linux-hardware.org/?probe=a62a7338e9) | Apr 10, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [73bbbb42c5](https://linux-hardware.org/?probe=73bbbb42c5) | Apr 10, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9ec146cb7c](https://linux-hardware.org/?probe=9ec146cb7c) | Apr 10, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [84927bf894](https://linux-hardware.org/?probe=84927bf894) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Lenovo        | ThinkPad W520 427639U       | Notebook    | [79f1e842a8](https://linux-hardware.org/?probe=79f1e842a8) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [81f5f2dadb](https://linux-hardware.org/?probe=81f5f2dadb) | Apr 10, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d03632cea9](https://linux-hardware.org/?probe=d03632cea9) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| eMachines     | EL1850G                     | Desktop     | [cfa8d1c8d5](https://linux-hardware.org/?probe=cfa8d1c8d5) | Apr 10, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Foxconn       | 2A92                        | Desktop     | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| Acer          | Aspire 3830T                | Notebook    | [0132818857](https://linux-hardware.org/?probe=0132818857) | Apr 10, 2022 |
| Dell          | 0DN075                      | Desktop     | [043e18273e](https://linux-hardware.org/?probe=043e18273e) | Apr 10, 2022 |
| Dell          | 0DN075                      | Desktop     | [759d8d5556](https://linux-hardware.org/?probe=759d8d5556) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [08ef3b4eb5](https://linux-hardware.org/?probe=08ef3b4eb5) | Apr 10, 2022 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [eb69184ad7](https://linux-hardware.org/?probe=eb69184ad7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [117eded7f8](https://linux-hardware.org/?probe=117eded7f8) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| Lenovo        | ThinkPad W530 24474E0       | Notebook    | [d467b8f7ce](https://linux-hardware.org/?probe=d467b8f7ce) | Apr 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [1345425e85](https://linux-hardware.org/?probe=1345425e85) | Apr 10, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [82db7996ff](https://linux-hardware.org/?probe=82db7996ff) | Apr 09, 2022 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [ff860c31b8](https://linux-hardware.org/?probe=ff860c31b8) | Apr 09, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [703a4e77a3](https://linux-hardware.org/?probe=703a4e77a3) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [1c57ef464e](https://linux-hardware.org/?probe=1c57ef464e) | Apr 09, 2022 |
| MSI           | GS66 Stealth 11UG           | Notebook    | [1fc8942ea4](https://linux-hardware.org/?probe=1fc8942ea4) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [e641889a70](https://linux-hardware.org/?probe=e641889a70) | Apr 09, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2ab0e2bf2d](https://linux-hardware.org/?probe=2ab0e2bf2d) | Apr 09, 2022 |
| Alienware     | 0J560M A00                  | Desktop     | [a0b422480a](https://linux-hardware.org/?probe=a0b422480a) | Apr 09, 2022 |
| NZXT          | N7 B550                     | Desktop     | [838fd4244b](https://linux-hardware.org/?probe=838fd4244b) | Apr 09, 2022 |
| NZXT          | N7 B550                     | Desktop     | [e3f895a70b](https://linux-hardware.org/?probe=e3f895a70b) | Apr 09, 2022 |
| Google        | Akemi                       | Notebook    | [ef80c1e22e](https://linux-hardware.org/?probe=ef80c1e22e) | Apr 09, 2022 |
| HP            | 840 G6                      | Notebook    | [7f8b25d480](https://linux-hardware.org/?probe=7f8b25d480) | Apr 09, 2022 |
| HP            | 81C9                        | Desktop     | [2eff1b8a02](https://linux-hardware.org/?probe=2eff1b8a02) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [1bd70fbd59](https://linux-hardware.org/?probe=1bd70fbd59) | Apr 09, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aa9de07827](https://linux-hardware.org/?probe=aa9de07827) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [dad9d965c5](https://linux-hardware.org/?probe=dad9d965c5) | Apr 09, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [1d0d38c7c8](https://linux-hardware.org/?probe=1d0d38c7c8) | Apr 09, 2022 |
| Lenovo        | ThinkPad T470 20HD000VUS    | Notebook    | [6bcb6b6f6d](https://linux-hardware.org/?probe=6bcb6b6f6d) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cce4df6a0c](https://linux-hardware.org/?probe=cce4df6a0c) | Apr 09, 2022 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [e6281eef7f](https://linux-hardware.org/?probe=e6281eef7f) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [14ae36ec3e](https://linux-hardware.org/?probe=14ae36ec3e) | Apr 09, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [ff682e31dc](https://linux-hardware.org/?probe=ff682e31dc) | Apr 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a54c91912a](https://linux-hardware.org/?probe=a54c91912a) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [2240b6c593](https://linux-hardware.org/?probe=2240b6c593) | Apr 09, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [470a09fc31](https://linux-hardware.org/?probe=470a09fc31) | Apr 09, 2022 |
| Dell          | G7 7700                     | Notebook    | [62180a0287](https://linux-hardware.org/?probe=62180a0287) | Apr 09, 2022 |
| Dell          | Latitude E6510              | Notebook    | [5c9b8036fe](https://linux-hardware.org/?probe=5c9b8036fe) | Apr 09, 2022 |
| Supermicro    | X9SRH-7F/7TF                | Desktop     | [ad534e1bb2](https://linux-hardware.org/?probe=ad534e1bb2) | Apr 09, 2022 |
| Dell          | Latitude E5520              | Notebook    | [3f3548b57e](https://linux-hardware.org/?probe=3f3548b57e) | Apr 09, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [251b8049e2](https://linux-hardware.org/?probe=251b8049e2) | Apr 09, 2022 |
| Dell          | Latitude E5520              | Notebook    | [dbd85ba35f](https://linux-hardware.org/?probe=dbd85ba35f) | Apr 09, 2022 |
| Framework     | Laptop                      | Notebook    | [14cf383f81](https://linux-hardware.org/?probe=14cf383f81) | Apr 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [163d8c26a5](https://linux-hardware.org/?probe=163d8c26a5) | Apr 09, 2022 |
| Dell          | 033FF6 A00                  | Desktop     | [5a96e1cad1](https://linux-hardware.org/?probe=5a96e1cad1) | Apr 09, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a78a4e608e](https://linux-hardware.org/?probe=a78a4e608e) | Apr 09, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [cfba789097](https://linux-hardware.org/?probe=cfba789097) | Apr 09, 2022 |
| HP            | 0A64h                       | Desktop     | [1dda6c8ea9](https://linux-hardware.org/?probe=1dda6c8ea9) | Apr 09, 2022 |
| ASRock        | Z170 Extreme6               | Desktop     | [616ea06acb](https://linux-hardware.org/?probe=616ea06acb) | Apr 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2d822ae226](https://linux-hardware.org/?probe=2d822ae226) | Apr 08, 2022 |
| Acer          | Extensa 5620                | Notebook    | [ea3ff1851b](https://linux-hardware.org/?probe=ea3ff1851b) | Apr 08, 2022 |
| Gateway       | NV57H                       | Notebook    | [a9a0b3fb18](https://linux-hardware.org/?probe=a9a0b3fb18) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [04e63d8b54](https://linux-hardware.org/?probe=04e63d8b54) | Apr 08, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [7e54067e6a](https://linux-hardware.org/?probe=7e54067e6a) | Apr 08, 2022 |
| Acer          | Veriton X6630G              | Desktop     | [69dfc9b91a](https://linux-hardware.org/?probe=69dfc9b91a) | Apr 08, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [c40867ec67](https://linux-hardware.org/?probe=c40867ec67) | Apr 08, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [b075fcae50](https://linux-hardware.org/?probe=b075fcae50) | Apr 08, 2022 |
| Dell          | Latitude E7270              | Notebook    | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |
| Dell          | Latitude E5440              | Notebook    | [ef1450a7a6](https://linux-hardware.org/?probe=ef1450a7a6) | Apr 08, 2022 |
| Dell          | Latitude E5440              | Notebook    | [db64d0481a](https://linux-hardware.org/?probe=db64d0481a) | Apr 08, 2022 |
| Samsung       | 950QDB                      | Convertible | [41d1bb5ecf](https://linux-hardware.org/?probe=41d1bb5ecf) | Apr 08, 2022 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [f04f8764a1](https://linux-hardware.org/?probe=f04f8764a1) | Apr 08, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [4119278c12](https://linux-hardware.org/?probe=4119278c12) | Apr 08, 2022 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [95f7ceba3b](https://linux-hardware.org/?probe=95f7ceba3b) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fc6b27af99](https://linux-hardware.org/?probe=fc6b27af99) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| Biostar       | TB250-BTC PRO               | Desktop     | [e06b543a59](https://linux-hardware.org/?probe=e06b543a59) | Apr 08, 2022 |
| Toshiba       | Satellite C655D             | Notebook    | [a9090685e6](https://linux-hardware.org/?probe=a9090685e6) | Apr 08, 2022 |
| MSI           | FM2-A75MA-E35               | Desktop     | [5d1a0661c9](https://linux-hardware.org/?probe=5d1a0661c9) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [40c5824930](https://linux-hardware.org/?probe=40c5824930) | Apr 08, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3d20e0e751](https://linux-hardware.org/?probe=3d20e0e751) | Apr 08, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [61d0948083](https://linux-hardware.org/?probe=61d0948083) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ed6ff884fc](https://linux-hardware.org/?probe=ed6ff884fc) | Apr 08, 2022 |
| Dell          | Latitude E7250              | Notebook    | [ba9c744af5](https://linux-hardware.org/?probe=ba9c744af5) | Apr 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [ab08910014](https://linux-hardware.org/?probe=ab08910014) | Apr 08, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f320ca37a5](https://linux-hardware.org/?probe=f320ca37a5) | Apr 08, 2022 |
| MSI           | 785GT-E63                   | Desktop     | [7e7ad6f032](https://linux-hardware.org/?probe=7e7ad6f032) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [b06f6f6879](https://linux-hardware.org/?probe=b06f6f6879) | Apr 08, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [7c20470181](https://linux-hardware.org/?probe=7c20470181) | Apr 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| Gigabyte      | Z77-HD4                     | Desktop     | [6162b961f2](https://linux-hardware.org/?probe=6162b961f2) | Apr 07, 2022 |
| HP            | 81C9                        | Desktop     | [80ec21f760](https://linux-hardware.org/?probe=80ec21f760) | Apr 07, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [a03fac6f8d](https://linux-hardware.org/?probe=a03fac6f8d) | Apr 07, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [40d9656aec](https://linux-hardware.org/?probe=40d9656aec) | Apr 07, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [527c75b918](https://linux-hardware.org/?probe=527c75b918) | Apr 07, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [cd57728495](https://linux-hardware.org/?probe=cd57728495) | Apr 07, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [4a53e94722](https://linux-hardware.org/?probe=4a53e94722) | Apr 07, 2022 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [d0ec506aa1](https://linux-hardware.org/?probe=d0ec506aa1) | Apr 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [98688480ec](https://linux-hardware.org/?probe=98688480ec) | Apr 07, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f8b24828c3](https://linux-hardware.org/?probe=f8b24828c3) | Apr 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [82b5d0a46e](https://linux-hardware.org/?probe=82b5d0a46e) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [7d87907153](https://linux-hardware.org/?probe=7d87907153) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [41fc926d28](https://linux-hardware.org/?probe=41fc926d28) | Apr 07, 2022 |
| HP            | ENVY 15                     | Notebook    | [cdd8aea3c3](https://linux-hardware.org/?probe=cdd8aea3c3) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [586edef1b9](https://linux-hardware.org/?probe=586edef1b9) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [bb881ed0ee](https://linux-hardware.org/?probe=bb881ed0ee) | Apr 07, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [c0a176be72](https://linux-hardware.org/?probe=c0a176be72) | Apr 07, 2022 |
| MSI           | FM2-A75MA-E35               | Desktop     | [b691235c0f](https://linux-hardware.org/?probe=b691235c0f) | Apr 07, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7f8be54a68](https://linux-hardware.org/?probe=7f8be54a68) | Apr 07, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [6af126abbf](https://linux-hardware.org/?probe=6af126abbf) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | Desktop     | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| Lenovo        | ThinkPad T470 20HD000VUS    | Notebook    | [8067eb22b2](https://linux-hardware.org/?probe=8067eb22b2) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [c610098aac](https://linux-hardware.org/?probe=c610098aac) | Apr 07, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [a9b44e63a1](https://linux-hardware.org/?probe=a9b44e63a1) | Apr 07, 2022 |
| ASUSTek       | GL553VW                     | Notebook    | [779c7e3858](https://linux-hardware.org/?probe=779c7e3858) | Apr 07, 2022 |
| Dell          | 0WG855                      | Desktop     | [17ad6cf614](https://linux-hardware.org/?probe=17ad6cf614) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [ce5b95cf78](https://linux-hardware.org/?probe=ce5b95cf78) | Apr 07, 2022 |
| Alienware     | m15                         | Notebook    | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad W520 4284EE6       | Notebook    | [444497b8b6](https://linux-hardware.org/?probe=444497b8b6) | Apr 07, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7c72e22d2c](https://linux-hardware.org/?probe=7c72e22d2c) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [150570ed10](https://linux-hardware.org/?probe=150570ed10) | Apr 07, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [6cd80e7357](https://linux-hardware.org/?probe=6cd80e7357) | Apr 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [2f09a13f44](https://linux-hardware.org/?probe=2f09a13f44) | Apr 07, 2022 |
| MSI           | GT80S 6QD                   | Notebook    | [f7184626cb](https://linux-hardware.org/?probe=f7184626cb) | Apr 07, 2022 |
| Dell          | 0RY007                      | Desktop     | [5ce0e84669](https://linux-hardware.org/?probe=5ce0e84669) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [c5278a4104](https://linux-hardware.org/?probe=c5278a4104) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4440e8ed7c](https://linux-hardware.org/?probe=4440e8ed7c) | Apr 07, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [269e88405a](https://linux-hardware.org/?probe=269e88405a) | Apr 06, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Dell          | Latitude 3520               | Notebook    | [1ec7dedd4c](https://linux-hardware.org/?probe=1ec7dedd4c) | Apr 06, 2022 |
| Dell          | Precision 7550              | Notebook    | [89df3f1bfd](https://linux-hardware.org/?probe=89df3f1bfd) | Apr 06, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [944ffb7e3f](https://linux-hardware.org/?probe=944ffb7e3f) | Apr 06, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [92966a1240](https://linux-hardware.org/?probe=92966a1240) | Apr 06, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [e42a83e13e](https://linux-hardware.org/?probe=e42a83e13e) | Apr 06, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [322440c462](https://linux-hardware.org/?probe=322440c462) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [56244d6def](https://linux-hardware.org/?probe=56244d6def) | Apr 06, 2022 |
| Dell          | 0WG855                      | Desktop     | [e7d59a199c](https://linux-hardware.org/?probe=e7d59a199c) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [e3d9b54f28](https://linux-hardware.org/?probe=e3d9b54f28) | Apr 06, 2022 |
| Samsung       | 950QDB                      | Convertible | [5d9a29f314](https://linux-hardware.org/?probe=5d9a29f314) | Apr 06, 2022 |
| Dell          | 0VNP2H A01                  | Desktop     | [ce01d1704a](https://linux-hardware.org/?probe=ce01d1704a) | Apr 06, 2022 |
| Dell          | 0U880P A01                  | Desktop     | [584ec9a64f](https://linux-hardware.org/?probe=584ec9a64f) | Apr 06, 2022 |
| Dell          | 0U880P A01                  | Desktop     | [54c8306a14](https://linux-hardware.org/?probe=54c8306a14) | Apr 06, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4e232c446f](https://linux-hardware.org/?probe=4e232c446f) | Apr 06, 2022 |
| HP            | 1588h                       | Desktop     | [0729a9b12d](https://linux-hardware.org/?probe=0729a9b12d) | Apr 06, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [af6989215e](https://linux-hardware.org/?probe=af6989215e) | Apr 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [a668b151a3](https://linux-hardware.org/?probe=a668b151a3) | Apr 06, 2022 |
| ECS           | Livermore                   | Desktop     | [afafdb72a7](https://linux-hardware.org/?probe=afafdb72a7) | Apr 06, 2022 |
| HP            | 840 G6                      | Notebook    | [76665316f7](https://linux-hardware.org/?probe=76665316f7) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [7280ff078b](https://linux-hardware.org/?probe=7280ff078b) | Apr 06, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [257046178c](https://linux-hardware.org/?probe=257046178c) | Apr 06, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [ef16b5252f](https://linux-hardware.org/?probe=ef16b5252f) | Apr 06, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [8aad15d96c](https://linux-hardware.org/?probe=8aad15d96c) | Apr 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [73a02fadb2](https://linux-hardware.org/?probe=73a02fadb2) | Apr 06, 2022 |
| Toshiba       | Satellite A205              | Notebook    | [a10f998cea](https://linux-hardware.org/?probe=a10f998cea) | Apr 06, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [83ec935bc4](https://linux-hardware.org/?probe=83ec935bc4) | Apr 06, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [45a343796d](https://linux-hardware.org/?probe=45a343796d) | Apr 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6fa4fe160c](https://linux-hardware.org/?probe=6fa4fe160c) | Apr 06, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [e20e2247c0](https://linux-hardware.org/?probe=e20e2247c0) | Apr 06, 2022 |
| Alienware     | 04VWF2 A02                  | Desktop     | [1637810ad2](https://linux-hardware.org/?probe=1637810ad2) | Apr 06, 2022 |
| HP            | 2129                        | Desktop     | [bb9c98d729](https://linux-hardware.org/?probe=bb9c98d729) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [27004240de](https://linux-hardware.org/?probe=27004240de) | Apr 06, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [bc09cc4eee](https://linux-hardware.org/?probe=bc09cc4eee) | Apr 06, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [802551fe50](https://linux-hardware.org/?probe=802551fe50) | Apr 06, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [97c87cecd7](https://linux-hardware.org/?probe=97c87cecd7) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | FM2-A75MA-E35               | Desktop     | [231d07274a](https://linux-hardware.org/?probe=231d07274a) | Apr 06, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [4cd501da13](https://linux-hardware.org/?probe=4cd501da13) | Apr 05, 2022 |
| Framework     | Laptop                      | Notebook    | [59a51973bb](https://linux-hardware.org/?probe=59a51973bb) | Apr 05, 2022 |
| Lenovo        | ThinkPad E525 120038U       | Notebook    | [03429f5a08](https://linux-hardware.org/?probe=03429f5a08) | Apr 05, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [0e99e2c6cb](https://linux-hardware.org/?probe=0e99e2c6cb) | Apr 05, 2022 |
| Gigabyte      | H470M DS3H                  | Desktop     | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f5106f79ee](https://linux-hardware.org/?probe=f5106f79ee) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [93cd6f380c](https://linux-hardware.org/?probe=93cd6f380c) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [aedb38f5de](https://linux-hardware.org/?probe=aedb38f5de) | Apr 05, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [accd10a83f](https://linux-hardware.org/?probe=accd10a83f) | Apr 05, 2022 |
| Lenovo        | ThinkPad E525 120038U       | Notebook    | [7a979a7678](https://linux-hardware.org/?probe=7a979a7678) | Apr 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b1050b51ec](https://linux-hardware.org/?probe=b1050b51ec) | Apr 05, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [19fc8f7fb8](https://linux-hardware.org/?probe=19fc8f7fb8) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [30591629c3](https://linux-hardware.org/?probe=30591629c3) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [95ffbe83e4](https://linux-hardware.org/?probe=95ffbe83e4) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [13e25ee6db](https://linux-hardware.org/?probe=13e25ee6db) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [8181b0cd19](https://linux-hardware.org/?probe=8181b0cd19) | Apr 05, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [568f9433a9](https://linux-hardware.org/?probe=568f9433a9) | Apr 05, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | 0DR845                      | Desktop     | [d7fc0864f8](https://linux-hardware.org/?probe=d7fc0864f8) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [dd1fef9175](https://linux-hardware.org/?probe=dd1fef9175) | Apr 05, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [8f985de338](https://linux-hardware.org/?probe=8f985de338) | Apr 05, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [e7576083a0](https://linux-hardware.org/?probe=e7576083a0) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [f5f6f27478](https://linux-hardware.org/?probe=f5f6f27478) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [f6b6435546](https://linux-hardware.org/?probe=f6b6435546) | Apr 05, 2022 |
| Google        | Treeya                      | Notebook    | [4ccd48fa75](https://linux-hardware.org/?probe=4ccd48fa75) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3e71b939a5](https://linux-hardware.org/?probe=3e71b939a5) | Apr 05, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1599d3b8b5](https://linux-hardware.org/?probe=1599d3b8b5) | Apr 05, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [219ae7c834](https://linux-hardware.org/?probe=219ae7c834) | Apr 05, 2022 |
| Intel         | D945GCF AAD73937-203        | Desktop     | [e9a0b1b355](https://linux-hardware.org/?probe=e9a0b1b355) | Apr 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [9a0f2c7fe7](https://linux-hardware.org/?probe=9a0f2c7fe7) | Apr 05, 2022 |
| HP            | ProBook 4440s               | Notebook    | [b42402a97e](https://linux-hardware.org/?probe=b42402a97e) | Apr 05, 2022 |
| Lenovo        | ThinkPad P70 20ESS04S00     | Notebook    | [18bcdf72db](https://linux-hardware.org/?probe=18bcdf72db) | Apr 05, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [82b79674a9](https://linux-hardware.org/?probe=82b79674a9) | Apr 05, 2022 |
| Foxconn       | 2A92                        | Desktop     | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f1a7708b3c](https://linux-hardware.org/?probe=f1a7708b3c) | Apr 05, 2022 |
| Sony          | VJZ141C11L                  | Notebook    | [bb26d704f1](https://linux-hardware.org/?probe=bb26d704f1) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [770088302a](https://linux-hardware.org/?probe=770088302a) | Apr 05, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [02f61ec71d](https://linux-hardware.org/?probe=02f61ec71d) | Apr 05, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [8b13f1e4ca](https://linux-hardware.org/?probe=8b13f1e4ca) | Apr 05, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [bac9bb4c7e](https://linux-hardware.org/?probe=bac9bb4c7e) | Apr 05, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [55de739c49](https://linux-hardware.org/?probe=55de739c49) | Apr 05, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [aa22c203eb](https://linux-hardware.org/?probe=aa22c203eb) | Apr 05, 2022 |
| Dell          | G15 5510                    | Notebook    | [9577f77159](https://linux-hardware.org/?probe=9577f77159) | Apr 05, 2022 |
| Dell          | Latitude E7270              | Notebook    | [e71de9a286](https://linux-hardware.org/?probe=e71de9a286) | Apr 04, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [a8ad77f915](https://linux-hardware.org/?probe=a8ad77f915) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [ca1d842423](https://linux-hardware.org/?probe=ca1d842423) | Apr 04, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [1d852a26c6](https://linux-hardware.org/?probe=1d852a26c6) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [5c28fb1391](https://linux-hardware.org/?probe=5c28fb1391) | Apr 04, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [1df77edf05](https://linux-hardware.org/?probe=1df77edf05) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [fe7fdad91b](https://linux-hardware.org/?probe=fe7fdad91b) | Apr 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [6fe78737f4](https://linux-hardware.org/?probe=6fe78737f4) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [a26b03795a](https://linux-hardware.org/?probe=a26b03795a) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [d467a8e89f](https://linux-hardware.org/?probe=d467a8e89f) | Apr 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0a0a02bac3](https://linux-hardware.org/?probe=0a0a02bac3) | Apr 04, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [5a31323a98](https://linux-hardware.org/?probe=5a31323a98) | Apr 04, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [6d2af993e2](https://linux-hardware.org/?probe=6d2af993e2) | Apr 04, 2022 |
| ASUSTek       | U47A                        | Notebook    | [5dd90629ff](https://linux-hardware.org/?probe=5dd90629ff) | Apr 04, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [fb9ba92aa8](https://linux-hardware.org/?probe=fb9ba92aa8) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [9228f355dc](https://linux-hardware.org/?probe=9228f355dc) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [31d50c441c](https://linux-hardware.org/?probe=31d50c441c) | Apr 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [92335fa3ac](https://linux-hardware.org/?probe=92335fa3ac) | Apr 04, 2022 |
| Biostar       | B350GT5                     | Desktop     | [b8aba828d1](https://linux-hardware.org/?probe=b8aba828d1) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [1e78710d6e](https://linux-hardware.org/?probe=1e78710d6e) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [5cfb35fb9e](https://linux-hardware.org/?probe=5cfb35fb9e) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [5712d63047](https://linux-hardware.org/?probe=5712d63047) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [42084c0823](https://linux-hardware.org/?probe=42084c0823) | Apr 04, 2022 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [2553eb95aa](https://linux-hardware.org/?probe=2553eb95aa) | Apr 04, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [4a47a3bd23](https://linux-hardware.org/?probe=4a47a3bd23) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [f6e3225172](https://linux-hardware.org/?probe=f6e3225172) | Apr 04, 2022 |
| HP            | ZBook 15                    | Notebook    | [46df6ce915](https://linux-hardware.org/?probe=46df6ce915) | Apr 04, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| HP            | Presario R4100 (PN495AV)    | Notebook    | [22b3001c0d](https://linux-hardware.org/?probe=22b3001c0d) | Apr 04, 2022 |
| HP            | 2AFB                        | Desktop     | [5d4114c272](https://linux-hardware.org/?probe=5d4114c272) | Apr 04, 2022 |
| HP            | 2AFB                        | Desktop     | [6e8e6bb327](https://linux-hardware.org/?probe=6e8e6bb327) | Apr 04, 2022 |
| Intel         | D945GCF AAD73937-203        | Desktop     | [6409bdc542](https://linux-hardware.org/?probe=6409bdc542) | Apr 04, 2022 |
| HP            | 15 TS                       | Notebook    | [4ad3dad048](https://linux-hardware.org/?probe=4ad3dad048) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [2bbc147beb](https://linux-hardware.org/?probe=2bbc147beb) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [d9cbb34331](https://linux-hardware.org/?probe=d9cbb34331) | Apr 04, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [8c03dcd371](https://linux-hardware.org/?probe=8c03dcd371) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [062e604ef0](https://linux-hardware.org/?probe=062e604ef0) | Apr 04, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [8d1d44d764](https://linux-hardware.org/?probe=8d1d44d764) | Apr 04, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [1c4423ca19](https://linux-hardware.org/?probe=1c4423ca19) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [5bcff46ee9](https://linux-hardware.org/?probe=5bcff46ee9) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2c39a577ac](https://linux-hardware.org/?probe=2c39a577ac) | Apr 04, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [9aea13fa1b](https://linux-hardware.org/?probe=9aea13fa1b) | Apr 04, 2022 |
| AWOW          | AK41                        | Notebook    | [f491f6f0fa](https://linux-hardware.org/?probe=f491f6f0fa) | Apr 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a6aea71be3](https://linux-hardware.org/?probe=a6aea71be3) | Apr 04, 2022 |
| ASUSTek       | UX301LAA                    | Notebook    | [1c631fdb63](https://linux-hardware.org/?probe=1c631fdb63) | Apr 04, 2022 |
| Dell          | Precision M4600             | Notebook    | [98d32306ea](https://linux-hardware.org/?probe=98d32306ea) | Apr 04, 2022 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [9104f4d730](https://linux-hardware.org/?probe=9104f4d730) | Apr 04, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4008f4f114](https://linux-hardware.org/?probe=4008f4f114) | Apr 04, 2022 |
| HP            | Pavilion TS 15              | Notebook    | [3e3b21e230](https://linux-hardware.org/?probe=3e3b21e230) | Apr 04, 2022 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [5231ab387c](https://linux-hardware.org/?probe=5231ab387c) | Apr 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7a354d771f](https://linux-hardware.org/?probe=7a354d771f) | Apr 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [400dbf6141](https://linux-hardware.org/?probe=400dbf6141) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b13db55f03](https://linux-hardware.org/?probe=b13db55f03) | Apr 03, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8e5b3df957](https://linux-hardware.org/?probe=8e5b3df957) | Apr 03, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e05f59de23](https://linux-hardware.org/?probe=e05f59de23) | Apr 03, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [a87f9de14e](https://linux-hardware.org/?probe=a87f9de14e) | Apr 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43ff476479](https://linux-hardware.org/?probe=43ff476479) | Apr 03, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [d268200bd2](https://linux-hardware.org/?probe=d268200bd2) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5469395f5c](https://linux-hardware.org/?probe=5469395f5c) | Apr 03, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| Dell          | 0427JK A00                  | Desktop     | [9349950b11](https://linux-hardware.org/?probe=9349950b11) | Apr 03, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [7220cef16c](https://linux-hardware.org/?probe=7220cef16c) | Apr 03, 2022 |
| Dell          | 0427JK A00                  | Desktop     | [47980a5b52](https://linux-hardware.org/?probe=47980a5b52) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [79f27f1c98](https://linux-hardware.org/?probe=79f27f1c98) | Apr 03, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [8cfc92a419](https://linux-hardware.org/?probe=8cfc92a419) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Alienware     | 07W25T A01                  | Desktop     | [e7280e6116](https://linux-hardware.org/?probe=e7280e6116) | Apr 03, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [bf16aedd75](https://linux-hardware.org/?probe=bf16aedd75) | Apr 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5736b2f194](https://linux-hardware.org/?probe=5736b2f194) | Apr 03, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [f6d4a4c17e](https://linux-hardware.org/?probe=f6d4a4c17e) | Apr 03, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [40a40fe75c](https://linux-hardware.org/?probe=40a40fe75c) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [0d5d7d117b](https://linux-hardware.org/?probe=0d5d7d117b) | Apr 03, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | M51AC                       | Desktop     | [0b15974e5c](https://linux-hardware.org/?probe=0b15974e5c) | Apr 03, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [17c6187b71](https://linux-hardware.org/?probe=17c6187b71) | Apr 03, 2022 |
| ASUSTek       | M51AC                       | Desktop     | [1943dbe3b7](https://linux-hardware.org/?probe=1943dbe3b7) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [53df2c9f1a](https://linux-hardware.org/?probe=53df2c9f1a) | Apr 03, 2022 |
| Lenovo        | ThinkPad T430 23473B2       | Notebook    | [aa0ad3f513](https://linux-hardware.org/?probe=aa0ad3f513) | Apr 03, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [08a6a3ec1c](https://linux-hardware.org/?probe=08a6a3ec1c) | Apr 03, 2022 |
| Toshiba       | BDB                         | Notebook    | [985b6a2865](https://linux-hardware.org/?probe=985b6a2865) | Apr 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ca9b5c03cb](https://linux-hardware.org/?probe=ca9b5c03cb) | Apr 03, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [ec2fb21c00](https://linux-hardware.org/?probe=ec2fb21c00) | Apr 03, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3ac5a0da56](https://linux-hardware.org/?probe=3ac5a0da56) | Apr 03, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ECS           | Livermore                   | Desktop     | [d801396140](https://linux-hardware.org/?probe=d801396140) | Apr 02, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [d8657defc8](https://linux-hardware.org/?probe=d8657defc8) | Apr 02, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [cf8c999bb1](https://linux-hardware.org/?probe=cf8c999bb1) | Apr 02, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [3c0ef3960c](https://linux-hardware.org/?probe=3c0ef3960c) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M91p 7033HS8    | Desktop     | [0fab8669e0](https://linux-hardware.org/?probe=0fab8669e0) | Apr 02, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [8bd2b269ff](https://linux-hardware.org/?probe=8bd2b269ff) | Apr 02, 2022 |
| Lenovo        | BRASWELL SDK0J40705 WIN ... | Desktop     | [7901a70a76](https://linux-hardware.org/?probe=7901a70a76) | Apr 02, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a4228141cb](https://linux-hardware.org/?probe=a4228141cb) | Apr 02, 2022 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [4c2eb85ea8](https://linux-hardware.org/?probe=4c2eb85ea8) | Apr 02, 2022 |
| ASUSTek       | F2A55-M                     | Desktop     | [62b4ad0ce3](https://linux-hardware.org/?probe=62b4ad0ce3) | Apr 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [fad7c9dda0](https://linux-hardware.org/?probe=fad7c9dda0) | Apr 02, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [ece77d7f2f](https://linux-hardware.org/?probe=ece77d7f2f) | Apr 02, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [a1bd9b5b35](https://linux-hardware.org/?probe=a1bd9b5b35) | Apr 02, 2022 |
| Acer          | One S1003                   | Tablet      | [b607734fb3](https://linux-hardware.org/?probe=b607734fb3) | Apr 02, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [11153fc9f1](https://linux-hardware.org/?probe=11153fc9f1) | Apr 02, 2022 |
| Acer          | One S1003                   | Tablet      | [e35497edb3](https://linux-hardware.org/?probe=e35497edb3) | Apr 02, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [4589c59d45](https://linux-hardware.org/?probe=4589c59d45) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [6b2cbca4b2](https://linux-hardware.org/?probe=6b2cbca4b2) | Apr 02, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [62bdba9365](https://linux-hardware.org/?probe=62bdba9365) | Apr 02, 2022 |
| MOTILE        | M141                        | Notebook    | [d93780c02c](https://linux-hardware.org/?probe=d93780c02c) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [055b15c7a9](https://linux-hardware.org/?probe=055b15c7a9) | Apr 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4696339b4e](https://linux-hardware.org/?probe=4696339b4e) | Apr 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [a773d8dfef](https://linux-hardware.org/?probe=a773d8dfef) | Apr 02, 2022 |
| Dell          | Latitude E6410              | Notebook    | [fde59f81d5](https://linux-hardware.org/?probe=fde59f81d5) | Apr 02, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e4d54618ca](https://linux-hardware.org/?probe=e4d54618ca) | Apr 02, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [805be6bbe7](https://linux-hardware.org/?probe=805be6bbe7) | Apr 01, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f30982f3ac](https://linux-hardware.org/?probe=f30982f3ac) | Apr 01, 2022 |
| HP            | Presario R4100 (PN495AV)    | Notebook    | [1eda605bc1](https://linux-hardware.org/?probe=1eda605bc1) | Apr 01, 2022 |
| HP            | Pavilion dm4                | Notebook    | [269069b765](https://linux-hardware.org/?probe=269069b765) | Apr 01, 2022 |
| Dell          | G7 7588                     | Notebook    | [3ca575dc99](https://linux-hardware.org/?probe=3ca575dc99) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dea55476fe](https://linux-hardware.org/?probe=dea55476fe) | Apr 01, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [03812d6355](https://linux-hardware.org/?probe=03812d6355) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b96ec01020](https://linux-hardware.org/?probe=b96ec01020) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ef9f9c2f65](https://linux-hardware.org/?probe=ef9f9c2f65) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [af9d333cd4](https://linux-hardware.org/?probe=af9d333cd4) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b2eaafbf96](https://linux-hardware.org/?probe=b2eaafbf96) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0804424b4a](https://linux-hardware.org/?probe=0804424b4a) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62f07bc1cf](https://linux-hardware.org/?probe=62f07bc1cf) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b22e4b7f86](https://linux-hardware.org/?probe=b22e4b7f86) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [574953b85a](https://linux-hardware.org/?probe=574953b85a) | Apr 01, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [27a8653896](https://linux-hardware.org/?probe=27a8653896) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cf24d6edcd](https://linux-hardware.org/?probe=cf24d6edcd) | Apr 01, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [a3688ae140](https://linux-hardware.org/?probe=a3688ae140) | Apr 01, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9e33e09c7f](https://linux-hardware.org/?probe=9e33e09c7f) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [48f4708670](https://linux-hardware.org/?probe=48f4708670) | Apr 01, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [de06c856b6](https://linux-hardware.org/?probe=de06c856b6) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [22036d225f](https://linux-hardware.org/?probe=22036d225f) | Apr 01, 2022 |
| Dell          | 0N867P A02                  | Desktop     | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [24401fbb54](https://linux-hardware.org/?probe=24401fbb54) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d0961cfe8d](https://linux-hardware.org/?probe=d0961cfe8d) | Apr 01, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b1a83acfb6](https://linux-hardware.org/?probe=b1a83acfb6) | Apr 01, 2022 |
| HP            | 212B                        | Desktop     | [ee85431891](https://linux-hardware.org/?probe=ee85431891) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f584ce346d](https://linux-hardware.org/?probe=f584ce346d) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2dc0936b94](https://linux-hardware.org/?probe=2dc0936b94) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4e2f534de0](https://linux-hardware.org/?probe=4e2f534de0) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [33ca39806c](https://linux-hardware.org/?probe=33ca39806c) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [db32d2887b](https://linux-hardware.org/?probe=db32d2887b) | Apr 01, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [981900a07b](https://linux-hardware.org/?probe=981900a07b) | Apr 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [625d6cc105](https://linux-hardware.org/?probe=625d6cc105) | Apr 01, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [5679458b7b](https://linux-hardware.org/?probe=5679458b7b) | Apr 01, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [94f7b6208e](https://linux-hardware.org/?probe=94f7b6208e) | Apr 01, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [50f088d544](https://linux-hardware.org/?probe=50f088d544) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| Dell          | Latitude E7250              | Notebook    | [d31f6b8a4a](https://linux-hardware.org/?probe=d31f6b8a4a) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [d7e0c70bf4](https://linux-hardware.org/?probe=d7e0c70bf4) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [d18cd45522](https://linux-hardware.org/?probe=d18cd45522) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [ec162ebae4](https://linux-hardware.org/?probe=ec162ebae4) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [05c1b046da](https://linux-hardware.org/?probe=05c1b046da) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [b89bd4d737](https://linux-hardware.org/?probe=b89bd4d737) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [ef7c5cdb4c](https://linux-hardware.org/?probe=ef7c5cdb4c) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [61383d9bd0](https://linux-hardware.org/?probe=61383d9bd0) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [65009176b4](https://linux-hardware.org/?probe=65009176b4) | Apr 01, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4fb10b4b1b](https://linux-hardware.org/?probe=4fb10b4b1b) | Apr 01, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [81e7639a72](https://linux-hardware.org/?probe=81e7639a72) | Apr 01, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [60ed5062f4](https://linux-hardware.org/?probe=60ed5062f4) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [d3f3139ac2](https://linux-hardware.org/?probe=d3f3139ac2) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [647fd89862](https://linux-hardware.org/?probe=647fd89862) | Apr 01, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [616258c6a5](https://linux-hardware.org/?probe=616258c6a5) | Apr 01, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0e42cf4c00](https://linux-hardware.org/?probe=0e42cf4c00) | Apr 01, 2022 |
| HP            | Pavilion dv6000 (GA443UA... | Notebook    | [b9a90b57c8](https://linux-hardware.org/?probe=b9a90b57c8) | Apr 01, 2022 |
| Alienware     | M11x                        | Notebook    | [f83c01bb34](https://linux-hardware.org/?probe=f83c01bb34) | Apr 01, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [cb8702ec94](https://linux-hardware.org/?probe=cb8702ec94) | Apr 01, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [9658d99893](https://linux-hardware.org/?probe=9658d99893) | Apr 01, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a14dde61dc](https://linux-hardware.org/?probe=a14dde61dc) | Apr 01, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [24e5262a03](https://linux-hardware.org/?probe=24e5262a03) | Apr 01, 2022 |
| ASUSTek       | K55A                        | Notebook    | [71137b6a1e](https://linux-hardware.org/?probe=71137b6a1e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3177873d94](https://linux-hardware.org/?probe=3177873d94) | Apr 01, 2022 |
| HP            | ProBook 6550b               | Notebook    | [d337221af6](https://linux-hardware.org/?probe=d337221af6) | Apr 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [17eda00f3d](https://linux-hardware.org/?probe=17eda00f3d) | Apr 01, 2022 |
| HP            | 2129                        | Desktop     | [a49e4cbced](https://linux-hardware.org/?probe=a49e4cbced) | Apr 01, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [7633664f7f](https://linux-hardware.org/?probe=7633664f7f) | Apr 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [d4691ddfac](https://linux-hardware.org/?probe=d4691ddfac) | Apr 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [254b38e98f](https://linux-hardware.org/?probe=254b38e98f) | Apr 01, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [7d2cce0d13](https://linux-hardware.org/?probe=7d2cce0d13) | Apr 01, 2022 |
| HP            | Laptop 17z-ca300            | Notebook    | [726d1e7b0f](https://linux-hardware.org/?probe=726d1e7b0f) | Mar 31, 2022 |
| Lenovo        | ThinkPad L512 2598AM7       | Notebook    | [92d91f4fb8](https://linux-hardware.org/?probe=92d91f4fb8) | Mar 31, 2022 |
| HP            | 0A64h                       | Desktop     | [732f81838c](https://linux-hardware.org/?probe=732f81838c) | Mar 31, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [5cdc7436c0](https://linux-hardware.org/?probe=5cdc7436c0) | Mar 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [87e9817856](https://linux-hardware.org/?probe=87e9817856) | Mar 31, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [99276b473e](https://linux-hardware.org/?probe=99276b473e) | Mar 31, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [965f8f58d5](https://linux-hardware.org/?probe=965f8f58d5) | Mar 31, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell          | Latitude E5250              | Notebook    | [03edbe8be4](https://linux-hardware.org/?probe=03edbe8be4) | Mar 31, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [112e437f5d](https://linux-hardware.org/?probe=112e437f5d) | Mar 31, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [293958c009](https://linux-hardware.org/?probe=293958c009) | Mar 31, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | Desktop     | [f74de3797f](https://linux-hardware.org/?probe=f74de3797f) | Mar 31, 2022 |
| System76      | Pangolin                    | Notebook    | [17a9fddb99](https://linux-hardware.org/?probe=17a9fddb99) | Mar 31, 2022 |
| HP            | 805D                        | Desktop     | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [44eafd5b02](https://linux-hardware.org/?probe=44eafd5b02) | Mar 31, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [a18aa9fa7e](https://linux-hardware.org/?probe=a18aa9fa7e) | Mar 31, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [09a8208d01](https://linux-hardware.org/?probe=09a8208d01) | Mar 31, 2022 |
| ASRock        | Z170A-X1                    | Desktop     | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [901a31bbe6](https://linux-hardware.org/?probe=901a31bbe6) | Mar 31, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c8236dd974](https://linux-hardware.org/?probe=c8236dd974) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [ea7372d041](https://linux-hardware.org/?probe=ea7372d041) | Mar 31, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f330902df9](https://linux-hardware.org/?probe=f330902df9) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9a7f8f2cf8](https://linux-hardware.org/?probe=9a7f8f2cf8) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [38772371c1](https://linux-hardware.org/?probe=38772371c1) | Mar 31, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [ec255331c0](https://linux-hardware.org/?probe=ec255331c0) | Mar 31, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [216b7bdf70](https://linux-hardware.org/?probe=216b7bdf70) | Mar 31, 2022 |
| Dell          | 0XHYJF A01                  | All in one  | [7c368b59b2](https://linux-hardware.org/?probe=7c368b59b2) | Mar 31, 2022 |
| HP            | 8457                        | Mini pc     | [da32c501fe](https://linux-hardware.org/?probe=da32c501fe) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| Dell          | G15 5510                    | Notebook    | [79f800bf0c](https://linux-hardware.org/?probe=79f800bf0c) | Mar 31, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [96b26ba64a](https://linux-hardware.org/?probe=96b26ba64a) | Mar 31, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [ec031b8180](https://linux-hardware.org/?probe=ec031b8180) | Mar 31, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [58413a83b2](https://linux-hardware.org/?probe=58413a83b2) | Mar 31, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [600e1be474](https://linux-hardware.org/?probe=600e1be474) | Mar 31, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [4fdbbcf1f5](https://linux-hardware.org/?probe=4fdbbcf1f5) | Mar 31, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [28ddf22c68](https://linux-hardware.org/?probe=28ddf22c68) | Mar 31, 2022 |
| Lenovo        | ThinkPad L512 2598AM7       | Notebook    | [661c16a667](https://linux-hardware.org/?probe=661c16a667) | Mar 31, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [4ba34b9b1f](https://linux-hardware.org/?probe=4ba34b9b1f) | Mar 31, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6f2c298e00](https://linux-hardware.org/?probe=6f2c298e00) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| ASUSTek       | Zephyrus M GU502GW          | Notebook    | [9d604c46d4](https://linux-hardware.org/?probe=9d604c46d4) | Mar 30, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [e6273d0bd9](https://linux-hardware.org/?probe=e6273d0bd9) | Mar 30, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b20141ddbb](https://linux-hardware.org/?probe=b20141ddbb) | Mar 30, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [d19fa42706](https://linux-hardware.org/?probe=d19fa42706) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [bf34d64bea](https://linux-hardware.org/?probe=bf34d64bea) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [c230fd441f](https://linux-hardware.org/?probe=c230fd441f) | Mar 30, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [bd6647f441](https://linux-hardware.org/?probe=bd6647f441) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [11b3bf1895](https://linux-hardware.org/?probe=11b3bf1895) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [f83d4681a5](https://linux-hardware.org/?probe=f83d4681a5) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [760130a724](https://linux-hardware.org/?probe=760130a724) | Mar 30, 2022 |
| HP            | 843B                        | Desktop     | [9c9f43770f](https://linux-hardware.org/?probe=9c9f43770f) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0eba3f5110](https://linux-hardware.org/?probe=0eba3f5110) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9031594389](https://linux-hardware.org/?probe=9031594389) | Mar 30, 2022 |
| Acer          | AOA150                      | Notebook    | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [70136a8a52](https://linux-hardware.org/?probe=70136a8a52) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [4b33b74c8d](https://linux-hardware.org/?probe=4b33b74c8d) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [ba75246f7d](https://linux-hardware.org/?probe=ba75246f7d) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [23c567f8ae](https://linux-hardware.org/?probe=23c567f8ae) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [c98ccf97ad](https://linux-hardware.org/?probe=c98ccf97ad) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [44539860bb](https://linux-hardware.org/?probe=44539860bb) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [2620b02831](https://linux-hardware.org/?probe=2620b02831) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [61f09eb46a](https://linux-hardware.org/?probe=61f09eb46a) | Mar 30, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [7752026321](https://linux-hardware.org/?probe=7752026321) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [ab864365bf](https://linux-hardware.org/?probe=ab864365bf) | Mar 30, 2022 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [d0de552c9f](https://linux-hardware.org/?probe=d0de552c9f) | Mar 30, 2022 |
| HP            | 843B                        | Desktop     | [84ae0f086f](https://linux-hardware.org/?probe=84ae0f086f) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [e05e42cfe8](https://linux-hardware.org/?probe=e05e42cfe8) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [01a45d419a](https://linux-hardware.org/?probe=01a45d419a) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [933efd1329](https://linux-hardware.org/?probe=933efd1329) | Mar 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [d8d0331e9e](https://linux-hardware.org/?probe=d8d0331e9e) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b3fbea8036](https://linux-hardware.org/?probe=b3fbea8036) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [cab2537c84](https://linux-hardware.org/?probe=cab2537c84) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [9cdc782ae4](https://linux-hardware.org/?probe=9cdc782ae4) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [82626bd1a6](https://linux-hardware.org/?probe=82626bd1a6) | Mar 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [db3d70e53a](https://linux-hardware.org/?probe=db3d70e53a) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [cd13aaa811](https://linux-hardware.org/?probe=cd13aaa811) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [62d19db44d](https://linux-hardware.org/?probe=62d19db44d) | Mar 30, 2022 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [3c0ae7514b](https://linux-hardware.org/?probe=3c0ae7514b) | Mar 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [40e9b13efb](https://linux-hardware.org/?probe=40e9b13efb) | Mar 30, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d466363fa3](https://linux-hardware.org/?probe=d466363fa3) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [4f76df5f21](https://linux-hardware.org/?probe=4f76df5f21) | Mar 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [d6ff25310b](https://linux-hardware.org/?probe=d6ff25310b) | Mar 30, 2022 |
| HP            | 300-240                     | Notebook    | [ce3af573e2](https://linux-hardware.org/?probe=ce3af573e2) | Mar 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [a26bba474b](https://linux-hardware.org/?probe=a26bba474b) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [e29a05bc98](https://linux-hardware.org/?probe=e29a05bc98) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [b916133743](https://linux-hardware.org/?probe=b916133743) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3577dffc4a](https://linux-hardware.org/?probe=3577dffc4a) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [8c3096482b](https://linux-hardware.org/?probe=8c3096482b) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [d479b367f3](https://linux-hardware.org/?probe=d479b367f3) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [5f02f56ad9](https://linux-hardware.org/?probe=5f02f56ad9) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b15259b9b9](https://linux-hardware.org/?probe=b15259b9b9) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [781cfeebd7](https://linux-hardware.org/?probe=781cfeebd7) | Mar 30, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [3d76ab6a14](https://linux-hardware.org/?probe=3d76ab6a14) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3c1da81190](https://linux-hardware.org/?probe=3c1da81190) | Mar 30, 2022 |
| Dell          | Inspiron 5100               | Notebook    | [64fefc70d1](https://linux-hardware.org/?probe=64fefc70d1) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [38ef312ce4](https://linux-hardware.org/?probe=38ef312ce4) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [80fbb03d04](https://linux-hardware.org/?probe=80fbb03d04) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c561ead77d](https://linux-hardware.org/?probe=c561ead77d) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [8fb97ff64b](https://linux-hardware.org/?probe=8fb97ff64b) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [64849cb92f](https://linux-hardware.org/?probe=64849cb92f) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [71c9be4b4e](https://linux-hardware.org/?probe=71c9be4b4e) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [8c96659249](https://linux-hardware.org/?probe=8c96659249) | Mar 30, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ade49f5201](https://linux-hardware.org/?probe=ade49f5201) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [1db213284b](https://linux-hardware.org/?probe=1db213284b) | Mar 30, 2022 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [d4352ae69d](https://linux-hardware.org/?probe=d4352ae69d) | Mar 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6e9d4f3b25](https://linux-hardware.org/?probe=6e9d4f3b25) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b36ea3eb7b](https://linux-hardware.org/?probe=b36ea3eb7b) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [731fe969ef](https://linux-hardware.org/?probe=731fe969ef) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [354d8402cf](https://linux-hardware.org/?probe=354d8402cf) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [c2ceaea91f](https://linux-hardware.org/?probe=c2ceaea91f) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [ec7465ab62](https://linux-hardware.org/?probe=ec7465ab62) | Mar 30, 2022 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [9c5ceb2c7d](https://linux-hardware.org/?probe=9c5ceb2c7d) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [a7bbd66733](https://linux-hardware.org/?probe=a7bbd66733) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [b981a3ff94](https://linux-hardware.org/?probe=b981a3ff94) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [21fb011d5a](https://linux-hardware.org/?probe=21fb011d5a) | Mar 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [97d8bc4ad6](https://linux-hardware.org/?probe=97d8bc4ad6) | Mar 30, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [4ce8485084](https://linux-hardware.org/?probe=4ce8485084) | Mar 30, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [dfa1ad49a0](https://linux-hardware.org/?probe=dfa1ad49a0) | Mar 30, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [379d455c8e](https://linux-hardware.org/?probe=379d455c8e) | Mar 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2362d1fd43](https://linux-hardware.org/?probe=2362d1fd43) | Mar 30, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [2d6f6c72fa](https://linux-hardware.org/?probe=2d6f6c72fa) | Mar 30, 2022 |
| HP            | 2129                        | Desktop     | [0a2cac4bdb](https://linux-hardware.org/?probe=0a2cac4bdb) | Mar 30, 2022 |
| ASUSTek       | Amberine M                  | Desktop     | [767946408c](https://linux-hardware.org/?probe=767946408c) | Mar 30, 2022 |
| HP            | 2129                        | Desktop     | [b6db1efd0c](https://linux-hardware.org/?probe=b6db1efd0c) | Mar 30, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [d219905770](https://linux-hardware.org/?probe=d219905770) | Mar 30, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [2a2e308343](https://linux-hardware.org/?probe=2a2e308343) | Mar 30, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [ffd68351a6](https://linux-hardware.org/?probe=ffd68351a6) | Mar 30, 2022 |
| HP            | 300-240                     | Notebook    | [5b2c959cb9](https://linux-hardware.org/?probe=5b2c959cb9) | Mar 30, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [a582876e2e](https://linux-hardware.org/?probe=a582876e2e) | Mar 30, 2022 |
| HP            | Compaq nx6125 (PZ896UA#A... | Notebook    | [bba6b8d33d](https://linux-hardware.org/?probe=bba6b8d33d) | Mar 30, 2022 |
| HP            | Compaq nx6125 (PZ896UA#A... | Notebook    | [9f382b5166](https://linux-hardware.org/?probe=9f382b5166) | Mar 30, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [6dcbfc4389](https://linux-hardware.org/?probe=6dcbfc4389) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [412577fc74](https://linux-hardware.org/?probe=412577fc74) | Mar 30, 2022 |
| Dell          | Latitude D531               | Notebook    | [8aa1b4069b](https://linux-hardware.org/?probe=8aa1b4069b) | Mar 30, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [c2081d11be](https://linux-hardware.org/?probe=c2081d11be) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [3e182ccdbe](https://linux-hardware.org/?probe=3e182ccdbe) | Mar 30, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eeef359646](https://linux-hardware.org/?probe=eeef359646) | Mar 30, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [c247b0bad3](https://linux-hardware.org/?probe=c247b0bad3) | Mar 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [3265336364](https://linux-hardware.org/?probe=3265336364) | Mar 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [062f9e2455](https://linux-hardware.org/?probe=062f9e2455) | Mar 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [2c9a5997cf](https://linux-hardware.org/?probe=2c9a5997cf) | Mar 30, 2022 |
| SiS Techno... | 741                         | Desktop     | [fe2c3a2118](https://linux-hardware.org/?probe=fe2c3a2118) | Mar 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [7d745ddc67](https://linux-hardware.org/?probe=7d745ddc67) | Mar 29, 2022 |
| ASUSTek       | G750JM                      | Notebook    | [03f1e79745](https://linux-hardware.org/?probe=03f1e79745) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [2515533d52](https://linux-hardware.org/?probe=2515533d52) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [f9f0d59a6a](https://linux-hardware.org/?probe=f9f0d59a6a) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [5d91344a23](https://linux-hardware.org/?probe=5d91344a23) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [048725554b](https://linux-hardware.org/?probe=048725554b) | Mar 29, 2022 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [9424649aa5](https://linux-hardware.org/?probe=9424649aa5) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [df356ba664](https://linux-hardware.org/?probe=df356ba664) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [3cadd2951c](https://linux-hardware.org/?probe=3cadd2951c) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3ab0308776](https://linux-hardware.org/?probe=3ab0308776) | Mar 29, 2022 |
| HP            | Pavilion dv8000 (EP409UA... | Notebook    | [56c91c9396](https://linux-hardware.org/?probe=56c91c9396) | Mar 29, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [fd1759c341](https://linux-hardware.org/?probe=fd1759c341) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0a003d8ab8](https://linux-hardware.org/?probe=0a003d8ab8) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [cacdb5e357](https://linux-hardware.org/?probe=cacdb5e357) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [95abe0d79d](https://linux-hardware.org/?probe=95abe0d79d) | Mar 29, 2022 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [b9b4a49da0](https://linux-hardware.org/?probe=b9b4a49da0) | Mar 29, 2022 |
| Dell          | 0X75JG A00                  | Desktop     | [b108b6d817](https://linux-hardware.org/?probe=b108b6d817) | Mar 29, 2022 |
| Dell          | Precision 7560              | Notebook    | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [9a53450a67](https://linux-hardware.org/?probe=9a53450a67) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0a51e9f7e3](https://linux-hardware.org/?probe=0a51e9f7e3) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [d2fdc4290a](https://linux-hardware.org/?probe=d2fdc4290a) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [3881639f77](https://linux-hardware.org/?probe=3881639f77) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [0c1586c75f](https://linux-hardware.org/?probe=0c1586c75f) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [506d1ce2f4](https://linux-hardware.org/?probe=506d1ce2f4) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [f8ce95fcf1](https://linux-hardware.org/?probe=f8ce95fcf1) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2441749cc0](https://linux-hardware.org/?probe=2441749cc0) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [47040a16f3](https://linux-hardware.org/?probe=47040a16f3) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0394259b79](https://linux-hardware.org/?probe=0394259b79) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [bf18a492d3](https://linux-hardware.org/?probe=bf18a492d3) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [6a9aeeecb7](https://linux-hardware.org/?probe=6a9aeeecb7) | Mar 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [d132380ec5](https://linux-hardware.org/?probe=d132380ec5) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [6e07849e21](https://linux-hardware.org/?probe=6e07849e21) | Mar 29, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [1bd6fc632b](https://linux-hardware.org/?probe=1bd6fc632b) | Mar 29, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [c38a41d563](https://linux-hardware.org/?probe=c38a41d563) | Mar 29, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b38fbe5154](https://linux-hardware.org/?probe=b38fbe5154) | Mar 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [a750b29a25](https://linux-hardware.org/?probe=a750b29a25) | Mar 29, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [0befbade0d](https://linux-hardware.org/?probe=0befbade0d) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [8d3e053ed8](https://linux-hardware.org/?probe=8d3e053ed8) | Mar 29, 2022 |
| BUYMPC Mic... | EU3G00                      | Notebook    | [28ad16f130](https://linux-hardware.org/?probe=28ad16f130) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [660ce58e45](https://linux-hardware.org/?probe=660ce58e45) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bd0fe415fe](https://linux-hardware.org/?probe=bd0fe415fe) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8fc2c1595f](https://linux-hardware.org/?probe=8fc2c1595f) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f1cbe3ec83](https://linux-hardware.org/?probe=f1cbe3ec83) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [345d3921c7](https://linux-hardware.org/?probe=345d3921c7) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3278bd5768](https://linux-hardware.org/?probe=3278bd5768) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bf479b678d](https://linux-hardware.org/?probe=bf479b678d) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9a7a8222ac](https://linux-hardware.org/?probe=9a7a8222ac) | Mar 29, 2022 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [dbf958a815](https://linux-hardware.org/?probe=dbf958a815) | Mar 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [a7eacc9559](https://linux-hardware.org/?probe=a7eacc9559) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74b5af8c0c](https://linux-hardware.org/?probe=74b5af8c0c) | Mar 29, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [426cd0671d](https://linux-hardware.org/?probe=426cd0671d) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a07c0e57cc](https://linux-hardware.org/?probe=a07c0e57cc) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2313250bcb](https://linux-hardware.org/?probe=2313250bcb) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c689323c11](https://linux-hardware.org/?probe=c689323c11) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab646d59d1](https://linux-hardware.org/?probe=ab646d59d1) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [018c06cb92](https://linux-hardware.org/?probe=018c06cb92) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d2588cac79](https://linux-hardware.org/?probe=d2588cac79) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2b871b3da9](https://linux-hardware.org/?probe=2b871b3da9) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aa39d43d92](https://linux-hardware.org/?probe=aa39d43d92) | Mar 29, 2022 |
| MicronPc_M... | EU3G00                      | Notebook    | [2d442b0016](https://linux-hardware.org/?probe=2d442b0016) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d7da50d464](https://linux-hardware.org/?probe=d7da50d464) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5c562b0228](https://linux-hardware.org/?probe=5c562b0228) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8c1d82154a](https://linux-hardware.org/?probe=8c1d82154a) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9e4fb8b26d](https://linux-hardware.org/?probe=9e4fb8b26d) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [38d65a3bc2](https://linux-hardware.org/?probe=38d65a3bc2) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d4733c58dd](https://linux-hardware.org/?probe=d4733c58dd) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [eaf3a98419](https://linux-hardware.org/?probe=eaf3a98419) | Mar 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6a6bb9ee06](https://linux-hardware.org/?probe=6a6bb9ee06) | Mar 29, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [118c9a57aa](https://linux-hardware.org/?probe=118c9a57aa) | Mar 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [0039c01471](https://linux-hardware.org/?probe=0039c01471) | Mar 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [88b64a12df](https://linux-hardware.org/?probe=88b64a12df) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [a6218b029c](https://linux-hardware.org/?probe=a6218b029c) | Mar 29, 2022 |
| ASUSTek       | P6T                         | Desktop     | [00868ae20c](https://linux-hardware.org/?probe=00868ae20c) | Mar 29, 2022 |
| Dell          | 0GWHMW A00                  | Desktop     | [3c0907dc45](https://linux-hardware.org/?probe=3c0907dc45) | Mar 29, 2022 |
| Dell          | 0K83V0 A00                  | Desktop     | [0428ae1966](https://linux-hardware.org/?probe=0428ae1966) | Mar 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| Dell          | 0K83V0 A00                  | Desktop     | [ef509c5553](https://linux-hardware.org/?probe=ef509c5553) | Mar 29, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [5d3604d4cc](https://linux-hardware.org/?probe=5d3604d4cc) | Mar 29, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [db66e10c17](https://linux-hardware.org/?probe=db66e10c17) | Mar 29, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [d435cef05e](https://linux-hardware.org/?probe=d435cef05e) | Mar 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [1ea47adec9](https://linux-hardware.org/?probe=1ea47adec9) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2541e3be0e](https://linux-hardware.org/?probe=2541e3be0e) | Mar 29, 2022 |
| MSI           | Z270 PC MATE                | Desktop     | [8193ff7289](https://linux-hardware.org/?probe=8193ff7289) | Mar 29, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| Sony          | SVE15115FXS                 | Notebook    | [fd28d82701](https://linux-hardware.org/?probe=fd28d82701) | Mar 28, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [471e3e8293](https://linux-hardware.org/?probe=471e3e8293) | Mar 28, 2022 |
| Dell          | Precision 7550              | Notebook    | [66605d1c53](https://linux-hardware.org/?probe=66605d1c53) | Mar 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e9097a9cd4](https://linux-hardware.org/?probe=e9097a9cd4) | Mar 28, 2022 |
| Framework     | Laptop                      | Notebook    | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [440e0a4b6a](https://linux-hardware.org/?probe=440e0a4b6a) | Mar 28, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [edee0670e3](https://linux-hardware.org/?probe=edee0670e3) | Mar 28, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [3907b39fde](https://linux-hardware.org/?probe=3907b39fde) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [12f752cfc8](https://linux-hardware.org/?probe=12f752cfc8) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a974509dee](https://linux-hardware.org/?probe=a974509dee) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d7a5ae41f2](https://linux-hardware.org/?probe=d7a5ae41f2) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [008012c088](https://linux-hardware.org/?probe=008012c088) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [17805ee544](https://linux-hardware.org/?probe=17805ee544) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [54e0481249](https://linux-hardware.org/?probe=54e0481249) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4d81d40f34](https://linux-hardware.org/?probe=4d81d40f34) | Mar 28, 2022 |
| MSI           | H81M-E34                    | Desktop     | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c7ff0867fc](https://linux-hardware.org/?probe=c7ff0867fc) | Mar 28, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [9d24029a71](https://linux-hardware.org/?probe=9d24029a71) | Mar 28, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [73f272bab9](https://linux-hardware.org/?probe=73f272bab9) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e216cbf213](https://linux-hardware.org/?probe=e216cbf213) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5709a6e5d0](https://linux-hardware.org/?probe=5709a6e5d0) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0e99c719be](https://linux-hardware.org/?probe=0e99c719be) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f32dd8d233](https://linux-hardware.org/?probe=f32dd8d233) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fd4baa1c1e](https://linux-hardware.org/?probe=fd4baa1c1e) | Mar 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [7c1a584c98](https://linux-hardware.org/?probe=7c1a584c98) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d3d93cf582](https://linux-hardware.org/?probe=d3d93cf582) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [456c7e3e39](https://linux-hardware.org/?probe=456c7e3e39) | Mar 28, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [9163c709cf](https://linux-hardware.org/?probe=9163c709cf) | Mar 28, 2022 |
| HP            | 300-240                     | Notebook    | [48bfec0c03](https://linux-hardware.org/?probe=48bfec0c03) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [be84a067b1](https://linux-hardware.org/?probe=be84a067b1) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f0d0126345](https://linux-hardware.org/?probe=f0d0126345) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c8d9b1bbbb](https://linux-hardware.org/?probe=c8d9b1bbbb) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1c3b0cc9e8](https://linux-hardware.org/?probe=1c3b0cc9e8) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a8ef2cbae1](https://linux-hardware.org/?probe=a8ef2cbae1) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [719f1a8407](https://linux-hardware.org/?probe=719f1a8407) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [956cfe6d5c](https://linux-hardware.org/?probe=956cfe6d5c) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4b6a0f5fd2](https://linux-hardware.org/?probe=4b6a0f5fd2) | Mar 28, 2022 |
| Samsung       | 950QDB                      | Convertible | [b6e10e0357](https://linux-hardware.org/?probe=b6e10e0357) | Mar 28, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [35d3d94c48](https://linux-hardware.org/?probe=35d3d94c48) | Mar 28, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [9f60c6f2e0](https://linux-hardware.org/?probe=9f60c6f2e0) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6d24b5808d](https://linux-hardware.org/?probe=6d24b5808d) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f4fea2bd15](https://linux-hardware.org/?probe=f4fea2bd15) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a9c2095b0b](https://linux-hardware.org/?probe=a9c2095b0b) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f5176d36d5](https://linux-hardware.org/?probe=f5176d36d5) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e23415449a](https://linux-hardware.org/?probe=e23415449a) | Mar 28, 2022 |
| Dell          | 0C27VV A04                  | Desktop     | [168c917da8](https://linux-hardware.org/?probe=168c917da8) | Mar 28, 2022 |
| Fujitsu       | LIFEBOOK T734               | Notebook    | [2b36726e65](https://linux-hardware.org/?probe=2b36726e65) | Mar 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [70a12c79b6](https://linux-hardware.org/?probe=70a12c79b6) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [02740e983b](https://linux-hardware.org/?probe=02740e983b) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2c0ff98f42](https://linux-hardware.org/?probe=2c0ff98f42) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7bde6013e3](https://linux-hardware.org/?probe=7bde6013e3) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6659ce53aa](https://linux-hardware.org/?probe=6659ce53aa) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ddac67a3a6](https://linux-hardware.org/?probe=ddac67a3a6) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fc280527ac](https://linux-hardware.org/?probe=fc280527ac) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2283ac732b](https://linux-hardware.org/?probe=2283ac732b) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0cc32ff2fb](https://linux-hardware.org/?probe=0cc32ff2fb) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dae44fb976](https://linux-hardware.org/?probe=dae44fb976) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [63946e4ce7](https://linux-hardware.org/?probe=63946e4ce7) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f9282ec588](https://linux-hardware.org/?probe=f9282ec588) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e51526c34e](https://linux-hardware.org/?probe=e51526c34e) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ebc5c80b22](https://linux-hardware.org/?probe=ebc5c80b22) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b9443a4996](https://linux-hardware.org/?probe=b9443a4996) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d98f1e1341](https://linux-hardware.org/?probe=d98f1e1341) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f384fccae7](https://linux-hardware.org/?probe=f384fccae7) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [22132403ff](https://linux-hardware.org/?probe=22132403ff) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4f653f41d0](https://linux-hardware.org/?probe=4f653f41d0) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab1880f222](https://linux-hardware.org/?probe=ab1880f222) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [77fa32cd21](https://linux-hardware.org/?probe=77fa32cd21) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cc5db0e4f8](https://linux-hardware.org/?probe=cc5db0e4f8) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [50d7e4493e](https://linux-hardware.org/?probe=50d7e4493e) | Mar 28, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [a44c1d3cc6](https://linux-hardware.org/?probe=a44c1d3cc6) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2e4fe83644](https://linux-hardware.org/?probe=2e4fe83644) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2d7895b0fc](https://linux-hardware.org/?probe=2d7895b0fc) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c6baccbb87](https://linux-hardware.org/?probe=c6baccbb87) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6636104d38](https://linux-hardware.org/?probe=6636104d38) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c3380865d9](https://linux-hardware.org/?probe=c3380865d9) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1bd520a5d4](https://linux-hardware.org/?probe=1bd520a5d4) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [637b3b139a](https://linux-hardware.org/?probe=637b3b139a) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [389c81b3ba](https://linux-hardware.org/?probe=389c81b3ba) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c0f7394bf5](https://linux-hardware.org/?probe=c0f7394bf5) | Mar 28, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e6fbc3ef69](https://linux-hardware.org/?probe=e6fbc3ef69) | Mar 28, 2022 |
| Toshiba       | Satellite L755D             | Notebook    | [d99ccc2771](https://linux-hardware.org/?probe=d99ccc2771) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [e60363109b](https://linux-hardware.org/?probe=e60363109b) | Mar 28, 2022 |
| HP            | ProBook 6465b               | Notebook    | [a375a0e7f7](https://linux-hardware.org/?probe=a375a0e7f7) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | Notebook    | [25066676e9](https://linux-hardware.org/?probe=25066676e9) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | Notebook    | [977e15d60c](https://linux-hardware.org/?probe=977e15d60c) | Mar 28, 2022 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [f499c7de86](https://linux-hardware.org/?probe=f499c7de86) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c1384b9063](https://linux-hardware.org/?probe=c1384b9063) | Mar 28, 2022 |
| MSI           | P67A-C43                    | Desktop     | [fb5d1f7bc1](https://linux-hardware.org/?probe=fb5d1f7bc1) | Mar 28, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [e33537863b](https://linux-hardware.org/?probe=e33537863b) | Mar 28, 2022 |
| HP            | 21B4 A01                    | Desktop     | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Samsung       | 940X5N                      | Convertible | [56e9fb4f71](https://linux-hardware.org/?probe=56e9fb4f71) | Mar 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6f2a0d378d](https://linux-hardware.org/?probe=6f2a0d378d) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [acb42fe25a](https://linux-hardware.org/?probe=acb42fe25a) | Mar 28, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [d39c4f7d2b](https://linux-hardware.org/?probe=d39c4f7d2b) | Mar 28, 2022 |
| MSI           | P67A-C43                    | Desktop     | [dac91a1c12](https://linux-hardware.org/?probe=dac91a1c12) | Mar 28, 2022 |
| MSI           | 970A-G46                    | Desktop     | [2e74d95856](https://linux-hardware.org/?probe=2e74d95856) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9c5efbe2a7](https://linux-hardware.org/?probe=9c5efbe2a7) | Mar 28, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [0ba5c7464c](https://linux-hardware.org/?probe=0ba5c7464c) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Precision M4800             | Notebook    | [1eacfc1ab5](https://linux-hardware.org/?probe=1eacfc1ab5) | Mar 27, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d72468b304](https://linux-hardware.org/?probe=d72468b304) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| ASUSTek       | M2N32-SLI PREMIUM           | Desktop     | [bf03850686](https://linux-hardware.org/?probe=bf03850686) | Mar 27, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a06ee5ea23](https://linux-hardware.org/?probe=a06ee5ea23) | Mar 27, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [17a15d4648](https://linux-hardware.org/?probe=17a15d4648) | Mar 27, 2022 |
| HP            | 1791                        | Desktop     | [dbde5293e1](https://linux-hardware.org/?probe=dbde5293e1) | Mar 27, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [8016c351c8](https://linux-hardware.org/?probe=8016c351c8) | Mar 27, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [48ab5aae1e](https://linux-hardware.org/?probe=48ab5aae1e) | Mar 27, 2022 |
| HP            | 1791                        | Desktop     | [23e62d94fc](https://linux-hardware.org/?probe=23e62d94fc) | Mar 27, 2022 |
| Pegatron      | Benicia                     | Desktop     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| ASUSTek       | Amberine M                  | Desktop     | [cf54d7e964](https://linux-hardware.org/?probe=cf54d7e964) | Mar 27, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [1f36f7eada](https://linux-hardware.org/?probe=1f36f7eada) | Mar 27, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [526eb02d22](https://linux-hardware.org/?probe=526eb02d22) | Mar 27, 2022 |
| ASUSTek       | P8Z77 WS                    | Desktop     | [069d2c186e](https://linux-hardware.org/?probe=069d2c186e) | Mar 27, 2022 |
| HP            | 1850                        | Desktop     | [297472c5f0](https://linux-hardware.org/?probe=297472c5f0) | Mar 27, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [986e01838e](https://linux-hardware.org/?probe=986e01838e) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [db1c53597b](https://linux-hardware.org/?probe=db1c53597b) | Mar 27, 2022 |
| HP            | 1495                        | Desktop     | [19569ad62b](https://linux-hardware.org/?probe=19569ad62b) | Mar 27, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | Desktop     | [5efb11c731](https://linux-hardware.org/?probe=5efb11c731) | Mar 27, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [d0d493d449](https://linux-hardware.org/?probe=d0d493d449) | Mar 27, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [d214df0c57](https://linux-hardware.org/?probe=d214df0c57) | Mar 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8cdf89a270](https://linux-hardware.org/?probe=8cdf89a270) | Mar 27, 2022 |
| HP            | ENVY dv6                    | Notebook    | [bfe11c2160](https://linux-hardware.org/?probe=bfe11c2160) | Mar 27, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [f3eb3387fb](https://linux-hardware.org/?probe=f3eb3387fb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [9213736f1c](https://linux-hardware.org/?probe=9213736f1c) | Mar 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [09cccd4869](https://linux-hardware.org/?probe=09cccd4869) | Mar 27, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [956099e687](https://linux-hardware.org/?probe=956099e687) | Mar 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [6298903ec7](https://linux-hardware.org/?probe=6298903ec7) | Mar 27, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [8766d8c04e](https://linux-hardware.org/?probe=8766d8c04e) | Mar 27, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [aeb87f174c](https://linux-hardware.org/?probe=aeb87f174c) | Mar 27, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [6e19fc670b](https://linux-hardware.org/?probe=6e19fc670b) | Mar 27, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [a30c3c112b](https://linux-hardware.org/?probe=a30c3c112b) | Mar 27, 2022 |
| Lenovo        | ThinkStation S20 4157V4A    | Desktop     | [b5b78f62fc](https://linux-hardware.org/?probe=b5b78f62fc) | Mar 27, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [c4ce562b21](https://linux-hardware.org/?probe=c4ce562b21) | Mar 27, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [5019c3645d](https://linux-hardware.org/?probe=5019c3645d) | Mar 26, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [aa5528c50f](https://linux-hardware.org/?probe=aa5528c50f) | Mar 26, 2022 |
| Dell          | Precision M4800             | Notebook    | [90a4438dfa](https://linux-hardware.org/?probe=90a4438dfa) | Mar 26, 2022 |
| Toshiba       | Satellite A105              | Notebook    | [5e63e884cf](https://linux-hardware.org/?probe=5e63e884cf) | Mar 26, 2022 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [e18a60f6bf](https://linux-hardware.org/?probe=e18a60f6bf) | Mar 26, 2022 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [f7daea6e27](https://linux-hardware.org/?probe=f7daea6e27) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91b7f328b1](https://linux-hardware.org/?probe=91b7f328b1) | Mar 26, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [e058d02926](https://linux-hardware.org/?probe=e058d02926) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [48ce1c3bd8](https://linux-hardware.org/?probe=48ce1c3bd8) | Mar 26, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [7bc7e689a4](https://linux-hardware.org/?probe=7bc7e689a4) | Mar 26, 2022 |
| Acer          | Aspire 6530                 | Notebook    | [d5dbe99079](https://linux-hardware.org/?probe=d5dbe99079) | Mar 26, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [bd913c7613](https://linux-hardware.org/?probe=bd913c7613) | Mar 26, 2022 |
| Dell          | Latitude D620               | Notebook    | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [156a0ab630](https://linux-hardware.org/?probe=156a0ab630) | Mar 26, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e143ea2c3d](https://linux-hardware.org/?probe=e143ea2c3d) | Mar 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [0d58e4449b](https://linux-hardware.org/?probe=0d58e4449b) | Mar 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [6ebd5ce185](https://linux-hardware.org/?probe=6ebd5ce185) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [9298b99a93](https://linux-hardware.org/?probe=9298b99a93) | Mar 26, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [8e439f57c8](https://linux-hardware.org/?probe=8e439f57c8) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Alienware     | 15 R4                       | Notebook    | [204145e795](https://linux-hardware.org/?probe=204145e795) | Mar 26, 2022 |
| Dell          | 03015M A01                  | Server      | [c2cae944b4](https://linux-hardware.org/?probe=c2cae944b4) | Mar 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [433cd3631d](https://linux-hardware.org/?probe=433cd3631d) | Mar 26, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [49eb5762eb](https://linux-hardware.org/?probe=49eb5762eb) | Mar 26, 2022 |
| HP            | ENVY m7 Notebook            | Notebook    | [c7b7914b87](https://linux-hardware.org/?probe=c7b7914b87) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [3825c4904e](https://linux-hardware.org/?probe=3825c4904e) | Mar 26, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [abcfa0354f](https://linux-hardware.org/?probe=abcfa0354f) | Mar 26, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [27f565aeca](https://linux-hardware.org/?probe=27f565aeca) | Mar 26, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [3a8a0e2c0c](https://linux-hardware.org/?probe=3a8a0e2c0c) | Mar 26, 2022 |
| Biostar       | B450MH                      | Desktop     | [9152345747](https://linux-hardware.org/?probe=9152345747) | Mar 26, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [6d9a59620b](https://linux-hardware.org/?probe=6d9a59620b) | Mar 26, 2022 |
| Dell          | 0TDG4V A01                  | Desktop     | [4df00a11b0](https://linux-hardware.org/?probe=4df00a11b0) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7807908b58](https://linux-hardware.org/?probe=7807908b58) | Mar 25, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [9e60987b3d](https://linux-hardware.org/?probe=9e60987b3d) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dde1d560f2](https://linux-hardware.org/?probe=dde1d560f2) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f434655dac](https://linux-hardware.org/?probe=f434655dac) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8a36194692](https://linux-hardware.org/?probe=8a36194692) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [65ba230e9d](https://linux-hardware.org/?probe=65ba230e9d) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0c1eb0be3b](https://linux-hardware.org/?probe=0c1eb0be3b) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [33fca0b8e8](https://linux-hardware.org/?probe=33fca0b8e8) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2c807078d7](https://linux-hardware.org/?probe=2c807078d7) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6b32ecb341](https://linux-hardware.org/?probe=6b32ecb341) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b437d8da72](https://linux-hardware.org/?probe=b437d8da72) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5125c0521c](https://linux-hardware.org/?probe=5125c0521c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [abc708b290](https://linux-hardware.org/?probe=abc708b290) | Mar 25, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [abdf251dcf](https://linux-hardware.org/?probe=abdf251dcf) | Mar 25, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [c98aa1ccf9](https://linux-hardware.org/?probe=c98aa1ccf9) | Mar 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [6f9e55a36c](https://linux-hardware.org/?probe=6f9e55a36c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1e1bb4af73](https://linux-hardware.org/?probe=1e1bb4af73) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9704e96de5](https://linux-hardware.org/?probe=9704e96de5) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e7330e61bb](https://linux-hardware.org/?probe=e7330e61bb) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c27e4bc406](https://linux-hardware.org/?probe=c27e4bc406) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bc3f554cff](https://linux-hardware.org/?probe=bc3f554cff) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c5ee11038e](https://linux-hardware.org/?probe=c5ee11038e) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9a61f61544](https://linux-hardware.org/?probe=9a61f61544) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fcdb43fa91](https://linux-hardware.org/?probe=fcdb43fa91) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9d79605905](https://linux-hardware.org/?probe=9d79605905) | Mar 25, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [c54f820ef2](https://linux-hardware.org/?probe=c54f820ef2) | Mar 25, 2022 |
| Dell          | Latitude E6420              | Notebook    | [299e4392f4](https://linux-hardware.org/?probe=299e4392f4) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aa99f96a44](https://linux-hardware.org/?probe=aa99f96a44) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [df8eb24e3c](https://linux-hardware.org/?probe=df8eb24e3c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c657a9d192](https://linux-hardware.org/?probe=c657a9d192) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4336eaee74](https://linux-hardware.org/?probe=4336eaee74) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74fcf8c949](https://linux-hardware.org/?probe=74fcf8c949) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8d3414ad53](https://linux-hardware.org/?probe=8d3414ad53) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [78578266ad](https://linux-hardware.org/?probe=78578266ad) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7d91fcf80d](https://linux-hardware.org/?probe=7d91fcf80d) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cf2a01ff9c](https://linux-hardware.org/?probe=cf2a01ff9c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [82faeea830](https://linux-hardware.org/?probe=82faeea830) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cf84791e1f](https://linux-hardware.org/?probe=cf84791e1f) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ba101b1005](https://linux-hardware.org/?probe=ba101b1005) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c36888e0db](https://linux-hardware.org/?probe=c36888e0db) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4d1111031e](https://linux-hardware.org/?probe=4d1111031e) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c581266c76](https://linux-hardware.org/?probe=c581266c76) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9744a2e3db](https://linux-hardware.org/?probe=9744a2e3db) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b7d0c4f4c3](https://linux-hardware.org/?probe=b7d0c4f4c3) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e4f0fbf6c3](https://linux-hardware.org/?probe=e4f0fbf6c3) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b530d04a82](https://linux-hardware.org/?probe=b530d04a82) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b322ce7a81](https://linux-hardware.org/?probe=b322ce7a81) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f7b8fa68ec](https://linux-hardware.org/?probe=f7b8fa68ec) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [215f7f551f](https://linux-hardware.org/?probe=215f7f551f) | Mar 25, 2022 |
| HP            | Pavilion dv6                | Notebook    | [c7dff2cc50](https://linux-hardware.org/?probe=c7dff2cc50) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ac11ee21c5](https://linux-hardware.org/?probe=ac11ee21c5) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62c53df9ac](https://linux-hardware.org/?probe=62c53df9ac) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8f3bdec5eb](https://linux-hardware.org/?probe=8f3bdec5eb) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [279defcae0](https://linux-hardware.org/?probe=279defcae0) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3263f3eee4](https://linux-hardware.org/?probe=3263f3eee4) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e1dfe6c51c](https://linux-hardware.org/?probe=e1dfe6c51c) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [84ee0b4519](https://linux-hardware.org/?probe=84ee0b4519) | Mar 25, 2022 |
| Sony          | VPCS111FM                   | Notebook    | [3b8480ce30](https://linux-hardware.org/?probe=3b8480ce30) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d835835c89](https://linux-hardware.org/?probe=d835835c89) | Mar 25, 2022 |
| Dell          | Inspiron 1521               | Notebook    | [546a428d9d](https://linux-hardware.org/?probe=546a428d9d) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [73117249bd](https://linux-hardware.org/?probe=73117249bd) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [40d76c9602](https://linux-hardware.org/?probe=40d76c9602) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c4062b3cd1](https://linux-hardware.org/?probe=c4062b3cd1) | Mar 25, 2022 |
| Dell          | Latitude E6320              | Notebook    | [9f34afdd61](https://linux-hardware.org/?probe=9f34afdd61) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [34a1bfdb97](https://linux-hardware.org/?probe=34a1bfdb97) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7b5dde6c42](https://linux-hardware.org/?probe=7b5dde6c42) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fcc6373f81](https://linux-hardware.org/?probe=fcc6373f81) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6c83d2fc1a](https://linux-hardware.org/?probe=6c83d2fc1a) | Mar 25, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [21864991c1](https://linux-hardware.org/?probe=21864991c1) | Mar 25, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [47bfb83f06](https://linux-hardware.org/?probe=47bfb83f06) | Mar 25, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [c6d5d7eaba](https://linux-hardware.org/?probe=c6d5d7eaba) | Mar 25, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [9d1c916f94](https://linux-hardware.org/?probe=9d1c916f94) | Mar 25, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [c4c99ca0fa](https://linux-hardware.org/?probe=c4c99ca0fa) | Mar 25, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [6d05225eaa](https://linux-hardware.org/?probe=6d05225eaa) | Mar 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [8de9332df6](https://linux-hardware.org/?probe=8de9332df6) | Mar 25, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [81a6571a8b](https://linux-hardware.org/?probe=81a6571a8b) | Mar 25, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [250b8a3542](https://linux-hardware.org/?probe=250b8a3542) | Mar 25, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [7ca811cae5](https://linux-hardware.org/?probe=7ca811cae5) | Mar 25, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [8163b935aa](https://linux-hardware.org/?probe=8163b935aa) | Mar 25, 2022 |
| Toshiba       | Satellite S55t-C            | Notebook    | [0bebc02627](https://linux-hardware.org/?probe=0bebc02627) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1cf6ad2e8e](https://linux-hardware.org/?probe=1cf6ad2e8e) | Mar 25, 2022 |
| ASUSTek       | Z170-AR                     | Desktop     | [f3edf6dd88](https://linux-hardware.org/?probe=f3edf6dd88) | Mar 25, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47d5193c84](https://linux-hardware.org/?probe=47d5193c84) | Mar 25, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [170657280c](https://linux-hardware.org/?probe=170657280c) | Mar 25, 2022 |
| Panasonic     | CF-19AHUDX1M                | Notebook    | [638470e61d](https://linux-hardware.org/?probe=638470e61d) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [da85b84f18](https://linux-hardware.org/?probe=da85b84f18) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [cda786fd40](https://linux-hardware.org/?probe=cda786fd40) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f453ee2c77](https://linux-hardware.org/?probe=f453ee2c77) | Mar 25, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [c6f4cf8c7a](https://linux-hardware.org/?probe=c6f4cf8c7a) | Mar 25, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [faf19b248a](https://linux-hardware.org/?probe=faf19b248a) | Mar 25, 2022 |
| Dell          | Latitude 9420               | Notebook    | [5227a4fbe3](https://linux-hardware.org/?probe=5227a4fbe3) | Mar 24, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| Dell          | 01KD4V A01                  | Desktop     | [9fae82a988](https://linux-hardware.org/?probe=9fae82a988) | Mar 24, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [aa7d01e08b](https://linux-hardware.org/?probe=aa7d01e08b) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2424807acb](https://linux-hardware.org/?probe=2424807acb) | Mar 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [bcf7ead91d](https://linux-hardware.org/?probe=bcf7ead91d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aab65645ee](https://linux-hardware.org/?probe=aab65645ee) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62cb62ab87](https://linux-hardware.org/?probe=62cb62ab87) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ae6ec4d664](https://linux-hardware.org/?probe=ae6ec4d664) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f2dffc79e4](https://linux-hardware.org/?probe=f2dffc79e4) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [15754d5c95](https://linux-hardware.org/?probe=15754d5c95) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ee8a7cd57e](https://linux-hardware.org/?probe=ee8a7cd57e) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [94c7609895](https://linux-hardware.org/?probe=94c7609895) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0d4426b790](https://linux-hardware.org/?probe=0d4426b790) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7102173ac3](https://linux-hardware.org/?probe=7102173ac3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [62af595883](https://linux-hardware.org/?probe=62af595883) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d6d6620190](https://linux-hardware.org/?probe=d6d6620190) | Mar 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [fdf1687d02](https://linux-hardware.org/?probe=fdf1687d02) | Mar 24, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [7f92319a04](https://linux-hardware.org/?probe=7f92319a04) | Mar 24, 2022 |
| MSI           | B550M PRO                   | Desktop     | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| MSI           | GS60 2PE Ghost Pro          | Notebook    | [7700fa2b69](https://linux-hardware.org/?probe=7700fa2b69) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bb744f9763](https://linux-hardware.org/?probe=bb744f9763) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2ccfbd59d3](https://linux-hardware.org/?probe=2ccfbd59d3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [65cb054464](https://linux-hardware.org/?probe=65cb054464) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d734538c37](https://linux-hardware.org/?probe=d734538c37) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bf707614f0](https://linux-hardware.org/?probe=bf707614f0) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [28be54345a](https://linux-hardware.org/?probe=28be54345a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6e466ec146](https://linux-hardware.org/?probe=6e466ec146) | Mar 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d59da741c5](https://linux-hardware.org/?probe=d59da741c5) | Mar 24, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [995b41ef83](https://linux-hardware.org/?probe=995b41ef83) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e09f56c996](https://linux-hardware.org/?probe=e09f56c996) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a0ada25db4](https://linux-hardware.org/?probe=a0ada25db4) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [47936430a1](https://linux-hardware.org/?probe=47936430a1) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [37c1241c1c](https://linux-hardware.org/?probe=37c1241c1c) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [41d33f527a](https://linux-hardware.org/?probe=41d33f527a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f136c79dbc](https://linux-hardware.org/?probe=f136c79dbc) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [128118c93d](https://linux-hardware.org/?probe=128118c93d) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | Notebook    | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| Dell          | 0P096C A01                  | Desktop     | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| Google        | Falco                       | Notebook    | [77727aa3fe](https://linux-hardware.org/?probe=77727aa3fe) | Mar 24, 2022 |
| ASRock        | 4X4-V1000                   | Desktop     | [f02931fb21](https://linux-hardware.org/?probe=f02931fb21) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e87cdc1828](https://linux-hardware.org/?probe=e87cdc1828) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8f1306f636](https://linux-hardware.org/?probe=8f1306f636) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6635105391](https://linux-hardware.org/?probe=6635105391) | Mar 24, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [cd5daedfc2](https://linux-hardware.org/?probe=cd5daedfc2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cc133ffbd7](https://linux-hardware.org/?probe=cc133ffbd7) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b86ea04329](https://linux-hardware.org/?probe=b86ea04329) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [baab66b8b3](https://linux-hardware.org/?probe=baab66b8b3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [05e7265b57](https://linux-hardware.org/?probe=05e7265b57) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fe835fdaef](https://linux-hardware.org/?probe=fe835fdaef) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [90c5855c40](https://linux-hardware.org/?probe=90c5855c40) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a67d7b4b52](https://linux-hardware.org/?probe=a67d7b4b52) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2122efb62f](https://linux-hardware.org/?probe=2122efb62f) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [dff3a1e5e0](https://linux-hardware.org/?probe=dff3a1e5e0) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [28c45e2dc9](https://linux-hardware.org/?probe=28c45e2dc9) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fb057065f3](https://linux-hardware.org/?probe=fb057065f3) | Mar 24, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [53ed9f8c5e](https://linux-hardware.org/?probe=53ed9f8c5e) | Mar 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [7c80283af3](https://linux-hardware.org/?probe=7c80283af3) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fe472b0e78](https://linux-hardware.org/?probe=fe472b0e78) | Mar 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25d5cba9dc](https://linux-hardware.org/?probe=25d5cba9dc) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b7a00a8bde](https://linux-hardware.org/?probe=b7a00a8bde) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [53b374ae77](https://linux-hardware.org/?probe=53b374ae77) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f6ed637eb2](https://linux-hardware.org/?probe=f6ed637eb2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bb47dbf24f](https://linux-hardware.org/?probe=bb47dbf24f) | Mar 24, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [80a259fdac](https://linux-hardware.org/?probe=80a259fdac) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [392e41cec2](https://linux-hardware.org/?probe=392e41cec2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [58f1f922d2](https://linux-hardware.org/?probe=58f1f922d2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [367de3521a](https://linux-hardware.org/?probe=367de3521a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cd3f77fcf2](https://linux-hardware.org/?probe=cd3f77fcf2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6a59e4c1b2](https://linux-hardware.org/?probe=6a59e4c1b2) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [93e3bd611b](https://linux-hardware.org/?probe=93e3bd611b) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8102e35a3d](https://linux-hardware.org/?probe=8102e35a3d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab53fea207](https://linux-hardware.org/?probe=ab53fea207) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5868e6209c](https://linux-hardware.org/?probe=5868e6209c) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c510eb8c99](https://linux-hardware.org/?probe=c510eb8c99) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2a93c0b48a](https://linux-hardware.org/?probe=2a93c0b48a) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9a536804c6](https://linux-hardware.org/?probe=9a536804c6) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fde5826e36](https://linux-hardware.org/?probe=fde5826e36) | Mar 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [bb8709d24f](https://linux-hardware.org/?probe=bb8709d24f) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d4144cc441](https://linux-hardware.org/?probe=d4144cc441) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5d45d7b64f](https://linux-hardware.org/?probe=5d45d7b64f) | Mar 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3c0bae87d1](https://linux-hardware.org/?probe=3c0bae87d1) | Mar 24, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [00fe92cee0](https://linux-hardware.org/?probe=00fe92cee0) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c291d8eef5](https://linux-hardware.org/?probe=c291d8eef5) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8f415cbd99](https://linux-hardware.org/?probe=8f415cbd99) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6460babd10](https://linux-hardware.org/?probe=6460babd10) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6d4bd09da1](https://linux-hardware.org/?probe=6d4bd09da1) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [794e2f8f7d](https://linux-hardware.org/?probe=794e2f8f7d) | Mar 24, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b3241d1c46](https://linux-hardware.org/?probe=b3241d1c46) | Mar 24, 2022 |
| Gateway       | NV59C                       | Notebook    | [f00a460bfa](https://linux-hardware.org/?probe=f00a460bfa) | Mar 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [0d7d21ac36](https://linux-hardware.org/?probe=0d7d21ac36) | Mar 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [0edbcfb4c8](https://linux-hardware.org/?probe=0edbcfb4c8) | Mar 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [1fa2b1e2ad](https://linux-hardware.org/?probe=1fa2b1e2ad) | Mar 24, 2022 |
| HP            | G60                         | Notebook    | [f45e7aa896](https://linux-hardware.org/?probe=f45e7aa896) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [52bc15cdf9](https://linux-hardware.org/?probe=52bc15cdf9) | Mar 24, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [3f091e30fe](https://linux-hardware.org/?probe=3f091e30fe) | Mar 24, 2022 |
| Lenovo        | 3718 SDK0J40700 WIN 3258... | All in one  | [24e2c55031](https://linux-hardware.org/?probe=24e2c55031) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6136cfa920](https://linux-hardware.org/?probe=6136cfa920) | Mar 24, 2022 |
| ASUSTek       | N56JN                       | Notebook    | [8302116452](https://linux-hardware.org/?probe=8302116452) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4c70e2fa37](https://linux-hardware.org/?probe=4c70e2fa37) | Mar 24, 2022 |
| ASUSTek       | U52F                        | Notebook    | [d311381222](https://linux-hardware.org/?probe=d311381222) | Mar 24, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [e2163528af](https://linux-hardware.org/?probe=e2163528af) | Mar 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [5c424251c8](https://linux-hardware.org/?probe=5c424251c8) | Mar 24, 2022 |
| HP            | 1998                        | Desktop     | [ec47a4edb9](https://linux-hardware.org/?probe=ec47a4edb9) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [4bc13fce28](https://linux-hardware.org/?probe=4bc13fce28) | Mar 24, 2022 |
| HP            | Notebook                    | Notebook    | [677fad4aab](https://linux-hardware.org/?probe=677fad4aab) | Mar 24, 2022 |
| Dell          | 08NG84 A01                  | All in one  | [8e2101ed83](https://linux-hardware.org/?probe=8e2101ed83) | Mar 24, 2022 |
| Lenovo        | ThinkPad X260 20F5S2C600    | Notebook    | [12df54f389](https://linux-hardware.org/?probe=12df54f389) | Mar 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [54cea35939](https://linux-hardware.org/?probe=54cea35939) | Mar 24, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [53c3899d7b](https://linux-hardware.org/?probe=53c3899d7b) | Mar 24, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [3b5e516908](https://linux-hardware.org/?probe=3b5e516908) | Mar 24, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b0aa487e97](https://linux-hardware.org/?probe=b0aa487e97) | Mar 23, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ace3fe8d13](https://linux-hardware.org/?probe=ace3fe8d13) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4b51a85bb4](https://linux-hardware.org/?probe=4b51a85bb4) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [508ed60efb](https://linux-hardware.org/?probe=508ed60efb) | Mar 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [8538b8dce2](https://linux-hardware.org/?probe=8538b8dce2) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0b3b856a53](https://linux-hardware.org/?probe=0b3b856a53) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [18547acdd1](https://linux-hardware.org/?probe=18547acdd1) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [f85ce6fe0c](https://linux-hardware.org/?probe=f85ce6fe0c) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [637e407924](https://linux-hardware.org/?probe=637e407924) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2616ad6b02](https://linux-hardware.org/?probe=2616ad6b02) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2e6b70998b](https://linux-hardware.org/?probe=2e6b70998b) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4626c38970](https://linux-hardware.org/?probe=4626c38970) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [eaf6dbd4f8](https://linux-hardware.org/?probe=eaf6dbd4f8) | Mar 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3fbd06d734](https://linux-hardware.org/?probe=3fbd06d734) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e6f7fdf843](https://linux-hardware.org/?probe=e6f7fdf843) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8c6409aaba](https://linux-hardware.org/?probe=8c6409aaba) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bc27c043c5](https://linux-hardware.org/?probe=bc27c043c5) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [430a34c792](https://linux-hardware.org/?probe=430a34c792) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [1e4b172f54](https://linux-hardware.org/?probe=1e4b172f54) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [6bf3e48b09](https://linux-hardware.org/?probe=6bf3e48b09) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [582db03602](https://linux-hardware.org/?probe=582db03602) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [5e68d6cb5c](https://linux-hardware.org/?probe=5e68d6cb5c) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [50bc4ca517](https://linux-hardware.org/?probe=50bc4ca517) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [e16f90e260](https://linux-hardware.org/?probe=e16f90e260) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [85a1ede47b](https://linux-hardware.org/?probe=85a1ede47b) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d47415dd08](https://linux-hardware.org/?probe=d47415dd08) | Mar 23, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [53a7830bc0](https://linux-hardware.org/?probe=53a7830bc0) | Mar 23, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [f46418a449](https://linux-hardware.org/?probe=f46418a449) | Mar 23, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [440e4d8b48](https://linux-hardware.org/?probe=440e4d8b48) | Mar 23, 2022 |
| Acer          | Aspire E1-731               | Notebook    | [404bb5bb48](https://linux-hardware.org/?probe=404bb5bb48) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d7de78e9e1](https://linux-hardware.org/?probe=d7de78e9e1) | Mar 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [18d216846f](https://linux-hardware.org/?probe=18d216846f) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4853561da5](https://linux-hardware.org/?probe=4853561da5) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [418c2622f2](https://linux-hardware.org/?probe=418c2622f2) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a88309b4bf](https://linux-hardware.org/?probe=a88309b4bf) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [08dbb01903](https://linux-hardware.org/?probe=08dbb01903) | Mar 23, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [447996a0c7](https://linux-hardware.org/?probe=447996a0c7) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ffeb6952f6](https://linux-hardware.org/?probe=ffeb6952f6) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [22bb81595e](https://linux-hardware.org/?probe=22bb81595e) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [be978d1795](https://linux-hardware.org/?probe=be978d1795) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d9c9b752b6](https://linux-hardware.org/?probe=d9c9b752b6) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [17b58d5660](https://linux-hardware.org/?probe=17b58d5660) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [401373809f](https://linux-hardware.org/?probe=401373809f) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2b95b80b3c](https://linux-hardware.org/?probe=2b95b80b3c) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a6bb3d9848](https://linux-hardware.org/?probe=a6bb3d9848) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7c85c90d78](https://linux-hardware.org/?probe=7c85c90d78) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2a2cf984ae](https://linux-hardware.org/?probe=2a2cf984ae) | Mar 23, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [c7bfffa6d4](https://linux-hardware.org/?probe=c7bfffa6d4) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [cb79c4afd7](https://linux-hardware.org/?probe=cb79c4afd7) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3d143aaa23](https://linux-hardware.org/?probe=3d143aaa23) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [0a88a77844](https://linux-hardware.org/?probe=0a88a77844) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74de92b5d5](https://linux-hardware.org/?probe=74de92b5d5) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4be2205977](https://linux-hardware.org/?probe=4be2205977) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [a50b453324](https://linux-hardware.org/?probe=a50b453324) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d822d3976a](https://linux-hardware.org/?probe=d822d3976a) | Mar 23, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [bf779a4e15](https://linux-hardware.org/?probe=bf779a4e15) | Mar 23, 2022 |
| HP            | 3048h                       | Desktop     | [fdbbb2adf6](https://linux-hardware.org/?probe=fdbbb2adf6) | Mar 23, 2022 |
| HP            | 18E4                        | Desktop     | [42cc8215b7](https://linux-hardware.org/?probe=42cc8215b7) | Mar 23, 2022 |
| Matsushita... | CF-19FHGADAM                | Notebook    | [72135c79c9](https://linux-hardware.org/?probe=72135c79c9) | Mar 23, 2022 |
| Dell          | 0VNP2H A00                  | Desktop     | [7f8e588fd2](https://linux-hardware.org/?probe=7f8e588fd2) | Mar 23, 2022 |
| Toshiba       | Satellite C75D-A            | Notebook    | [8e595c777b](https://linux-hardware.org/?probe=8e595c777b) | Mar 23, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [b56ffe462f](https://linux-hardware.org/?probe=b56ffe462f) | Mar 23, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [a889471411](https://linux-hardware.org/?probe=a889471411) | Mar 23, 2022 |
| Dell          | Latitude 7490               | Notebook    | [46726fbceb](https://linux-hardware.org/?probe=46726fbceb) | Mar 23, 2022 |
| Toshiba       | PORTEGE Z15t-A              | Notebook    | [54a157be17](https://linux-hardware.org/?probe=54a157be17) | Mar 23, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [cf169cd574](https://linux-hardware.org/?probe=cf169cd574) | Mar 23, 2022 |
| Matsushita... | CF-52GUNBP2M                | Notebook    | [1a2b03dac6](https://linux-hardware.org/?probe=1a2b03dac6) | Mar 23, 2022 |
| Dell          | G5 5505                     | Notebook    | [74a1eb8027](https://linux-hardware.org/?probe=74a1eb8027) | Mar 23, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [b8906f2c35](https://linux-hardware.org/?probe=b8906f2c35) | Mar 23, 2022 |
| MSI           | GS30 2M Shadow              | Notebook    | [5a117cae70](https://linux-hardware.org/?probe=5a117cae70) | Mar 23, 2022 |
| Alienware     | 0FPV4P A00                  | Desktop     | [b1d20542b8](https://linux-hardware.org/?probe=b1d20542b8) | Mar 23, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [5936c86b5d](https://linux-hardware.org/?probe=5936c86b5d) | Mar 23, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [ad7882c51c](https://linux-hardware.org/?probe=ad7882c51c) | Mar 23, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| Gigabyte      | X99-Designare EX-CF         | Desktop     | [868791f75e](https://linux-hardware.org/?probe=868791f75e) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [3024cce066](https://linux-hardware.org/?probe=3024cce066) | Mar 23, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [ce3756c3cb](https://linux-hardware.org/?probe=ce3756c3cb) | Mar 23, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [d9a46720c0](https://linux-hardware.org/?probe=d9a46720c0) | Mar 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [44ff6c5827](https://linux-hardware.org/?probe=44ff6c5827) | Mar 22, 2022 |
| Dell          | 0YMVJ6 A00                  | Desktop     | [0db6363744](https://linux-hardware.org/?probe=0db6363744) | Mar 22, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3208ae7baf](https://linux-hardware.org/?probe=3208ae7baf) | Mar 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [b53e246436](https://linux-hardware.org/?probe=b53e246436) | Mar 22, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [285d6800fc](https://linux-hardware.org/?probe=285d6800fc) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [33d0891c50](https://linux-hardware.org/?probe=33d0891c50) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [8317fd0383](https://linux-hardware.org/?probe=8317fd0383) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b06e223c59](https://linux-hardware.org/?probe=b06e223c59) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [76aa9f3f9e](https://linux-hardware.org/?probe=76aa9f3f9e) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ab9b2cba96](https://linux-hardware.org/?probe=ab9b2cba96) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4a729eb987](https://linux-hardware.org/?probe=4a729eb987) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [34676db3b2](https://linux-hardware.org/?probe=34676db3b2) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d84c579f5d](https://linux-hardware.org/?probe=d84c579f5d) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [2a7bb7679e](https://linux-hardware.org/?probe=2a7bb7679e) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [aafc2871d3](https://linux-hardware.org/?probe=aafc2871d3) | Mar 22, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e28a8e0a3c](https://linux-hardware.org/?probe=e28a8e0a3c) | Mar 22, 2022 |
| Gateway       | NV59C                       | Notebook    | [ce722c3cc0](https://linux-hardware.org/?probe=ce722c3cc0) | Mar 22, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [6fc4d08da4](https://linux-hardware.org/?probe=6fc4d08da4) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fcad1031fe](https://linux-hardware.org/?probe=fcad1031fe) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [04d444e019](https://linux-hardware.org/?probe=04d444e019) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [245849a085](https://linux-hardware.org/?probe=245849a085) | Mar 22, 2022 |
| Samsung       | 950QDB                      | Convertible | [7ed28a1254](https://linux-hardware.org/?probe=7ed28a1254) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7e271264aa](https://linux-hardware.org/?probe=7e271264aa) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [c557216143](https://linux-hardware.org/?probe=c557216143) | Mar 22, 2022 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | Desktop     | [d1fd7ebdcc](https://linux-hardware.org/?probe=d1fd7ebdcc) | Mar 22, 2022 |
| Intel         | E5 M2L-8D                   | Desktop     | [12234d8f86](https://linux-hardware.org/?probe=12234d8f86) | Mar 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [6df1ac7011](https://linux-hardware.org/?probe=6df1ac7011) | Mar 22, 2022 |
| MSI           | GE62 6QF                    | Notebook    | [4596b4e280](https://linux-hardware.org/?probe=4596b4e280) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [d510106ed6](https://linux-hardware.org/?probe=d510106ed6) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | Notebook    | [4d54a6af03](https://linux-hardware.org/?probe=4d54a6af03) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [74c5cea3d3](https://linux-hardware.org/?probe=74c5cea3d3) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [eaf7658e60](https://linux-hardware.org/?probe=eaf7658e60) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9b259c8e34](https://linux-hardware.org/?probe=9b259c8e34) | Mar 22, 2022 |
| ASUSTek       | X99-M WS                    | Desktop     | [5f29519a18](https://linux-hardware.org/?probe=5f29519a18) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [46f732ce06](https://linux-hardware.org/?probe=46f732ce06) | Mar 22, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [e40796fc4e](https://linux-hardware.org/?probe=e40796fc4e) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [75f9b4edf4](https://linux-hardware.org/?probe=75f9b4edf4) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [245f481ab3](https://linux-hardware.org/?probe=245f481ab3) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ccce01ca4d](https://linux-hardware.org/?probe=ccce01ca4d) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [fb4b10e80f](https://linux-hardware.org/?probe=fb4b10e80f) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [7662580f58](https://linux-hardware.org/?probe=7662580f58) | Mar 22, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [28ac28ad02](https://linux-hardware.org/?probe=28ac28ad02) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [b2bd27f11b](https://linux-hardware.org/?probe=b2bd27f11b) | Mar 22, 2022 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [631ae2fff8](https://linux-hardware.org/?probe=631ae2fff8) | Mar 22, 2022 |
| Apple         | Mac-27AD2F918AE68F61        | Desktop     | [03e06a3a70](https://linux-hardware.org/?probe=03e06a3a70) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [4133dff23f](https://linux-hardware.org/?probe=4133dff23f) | Mar 22, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [0ae4b366a6](https://linux-hardware.org/?probe=0ae4b366a6) | Mar 22, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [3b0fd0ec8b](https://linux-hardware.org/?probe=3b0fd0ec8b) | Mar 22, 2022 |
| Google        | Falco                       | Notebook    | [1999050fdc](https://linux-hardware.org/?probe=1999050fdc) | Mar 22, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [d034ba5d2b](https://linux-hardware.org/?probe=d034ba5d2b) | Mar 22, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [e7f8300ff6](https://linux-hardware.org/?probe=e7f8300ff6) | Mar 22, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [35488c8cce](https://linux-hardware.org/?probe=35488c8cce) | Mar 22, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [ac271ec90a](https://linux-hardware.org/?probe=ac271ec90a) | Mar 22, 2022 |
| Google        | Falco                       | Notebook    | [279dc118ab](https://linux-hardware.org/?probe=279dc118ab) | Mar 22, 2022 |
| MOTILE        | M142                        | Notebook    | [ee5bcdf209](https://linux-hardware.org/?probe=ee5bcdf209) | Mar 22, 2022 |
| Matsushita... | CF-19FHGADAM                | Notebook    | [c5c47f4c5e](https://linux-hardware.org/?probe=c5c47f4c5e) | Mar 22, 2022 |
| Samsung       | 730QDA                      | Convertible | [c2354d6e00](https://linux-hardware.org/?probe=c2354d6e00) | Mar 22, 2022 |
| Panasonic     | CF53-4                      | Notebook    | [b5ec65aed6](https://linux-hardware.org/?probe=b5ec65aed6) | Mar 22, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [395ccacda8](https://linux-hardware.org/?probe=395ccacda8) | Mar 22, 2022 |
| HP            | 18E4                        | Desktop     | [c4dec6c79b](https://linux-hardware.org/?probe=c4dec6c79b) | Mar 22, 2022 |
| HP            | 18E4                        | Desktop     | [e06e0c412c](https://linux-hardware.org/?probe=e06e0c412c) | Mar 22, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [6934e641a4](https://linux-hardware.org/?probe=6934e641a4) | Mar 22, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [0b2a7b240f](https://linux-hardware.org/?probe=0b2a7b240f) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d755a1a962](https://linux-hardware.org/?probe=d755a1a962) | Mar 22, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d9f1365e01](https://linux-hardware.org/?probe=d9f1365e01) | Mar 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [4307f7f265](https://linux-hardware.org/?probe=4307f7f265) | Mar 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [30529b1b3a](https://linux-hardware.org/?probe=30529b1b3a) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2cfe733664](https://linux-hardware.org/?probe=2cfe733664) | Mar 22, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e862658aa](https://linux-hardware.org/?probe=9e862658aa) | Mar 22, 2022 |
| Alienware     | M15x                        | Notebook    | [d4ec607218](https://linux-hardware.org/?probe=d4ec607218) | Mar 22, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [132a6a3ee7](https://linux-hardware.org/?probe=132a6a3ee7) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [f06aa387e9](https://linux-hardware.org/?probe=f06aa387e9) | Mar 22, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [42e766a482](https://linux-hardware.org/?probe=42e766a482) | Mar 22, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c90c0f1819](https://linux-hardware.org/?probe=c90c0f1819) | Mar 22, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [228a2ce045](https://linux-hardware.org/?probe=228a2ce045) | Mar 22, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [e9ee0cbafc](https://linux-hardware.org/?probe=e9ee0cbafc) | Mar 22, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [ab7183bade](https://linux-hardware.org/?probe=ab7183bade) | Mar 22, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [61b027d6b1](https://linux-hardware.org/?probe=61b027d6b1) | Mar 22, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [73dc218dc5](https://linux-hardware.org/?probe=73dc218dc5) | Mar 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [44d6d432f9](https://linux-hardware.org/?probe=44d6d432f9) | Mar 21, 2022 |
| Dell          | Vostro 3350                 | Notebook    | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| MSI           | 760GM -E51                  | Desktop     | [fd746ce3ee](https://linux-hardware.org/?probe=fd746ce3ee) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| MiTAC         | UltraPoint                  | Desktop     | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [dcd23d9883](https://linux-hardware.org/?probe=dcd23d9883) | Mar 21, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [439c82275d](https://linux-hardware.org/?probe=439c82275d) | Mar 21, 2022 |
| Lenovo        | ThinkPad T430s 2356GRU      | Notebook    | [d19e2a8c06](https://linux-hardware.org/?probe=d19e2a8c06) | Mar 21, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [0aa28d1e37](https://linux-hardware.org/?probe=0aa28d1e37) | Mar 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [bfe7047633](https://linux-hardware.org/?probe=bfe7047633) | Mar 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f4552c4008](https://linux-hardware.org/?probe=f4552c4008) | Mar 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [70a784f09c](https://linux-hardware.org/?probe=70a784f09c) | Mar 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [9c194b83e5](https://linux-hardware.org/?probe=9c194b83e5) | Mar 21, 2022 |
| Lenovo        | 3172 SDK0T08861 WIN 3305... | Mini pc     | [eb86d89d86](https://linux-hardware.org/?probe=eb86d89d86) | Mar 21, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [929c5491f8](https://linux-hardware.org/?probe=929c5491f8) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [78b6d2b02e](https://linux-hardware.org/?probe=78b6d2b02e) | Mar 21, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [7491ca0a9a](https://linux-hardware.org/?probe=7491ca0a9a) | Mar 21, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [a4d8d08ea6](https://linux-hardware.org/?probe=a4d8d08ea6) | Mar 21, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [ef5f0dcfe7](https://linux-hardware.org/?probe=ef5f0dcfe7) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [0fab7594d6](https://linux-hardware.org/?probe=0fab7594d6) | Mar 21, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [0f3a8eb166](https://linux-hardware.org/?probe=0f3a8eb166) | Mar 21, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [609641d7df](https://linux-hardware.org/?probe=609641d7df) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [2298f934bd](https://linux-hardware.org/?probe=2298f934bd) | Mar 21, 2022 |
| Dell          | System XPS L322X            | Notebook    | [ee172af23a](https://linux-hardware.org/?probe=ee172af23a) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [a0f38f14e0](https://linux-hardware.org/?probe=a0f38f14e0) | Mar 21, 2022 |
| Intel         | DH55TC AAE70932-301         | Desktop     | [e0c4ac33b9](https://linux-hardware.org/?probe=e0c4ac33b9) | Mar 21, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [b94dc1035d](https://linux-hardware.org/?probe=b94dc1035d) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| HP            | G60                         | Notebook    | [f31bbf627a](https://linux-hardware.org/?probe=f31bbf627a) | Mar 21, 2022 |
| HP            | 2000                        | Notebook    | [88c00b222a](https://linux-hardware.org/?probe=88c00b222a) | Mar 21, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [2e5fe11634](https://linux-hardware.org/?probe=2e5fe11634) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2b39b0fda2](https://linux-hardware.org/?probe=2b39b0fda2) | Mar 21, 2022 |
| Google        | Nautilus                    | Notebook    | [a0b462dbe1](https://linux-hardware.org/?probe=a0b462dbe1) | Mar 21, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c9284d222f](https://linux-hardware.org/?probe=c9284d222f) | Mar 20, 2022 |
| HP            | 2000                        | Notebook    | [a81c5796af](https://linux-hardware.org/?probe=a81c5796af) | Mar 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [00a1f6adfb](https://linux-hardware.org/?probe=00a1f6adfb) | Mar 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [aa3a5ca6b2](https://linux-hardware.org/?probe=aa3a5ca6b2) | Mar 20, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [d221b2c3f6](https://linux-hardware.org/?probe=d221b2c3f6) | Mar 20, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Unknown       | Unknown                     | Soc         | [dad2f6c4ba](https://linux-hardware.org/?probe=dad2f6c4ba) | Mar 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8f18a30bbf](https://linux-hardware.org/?probe=8f18a30bbf) | Mar 20, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [a1cf64d032](https://linux-hardware.org/?probe=a1cf64d032) | Mar 20, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [f14f6a101f](https://linux-hardware.org/?probe=f14f6a101f) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| MicroByte     | ezbook                      | Notebook    | [d1e89638df](https://linux-hardware.org/?probe=d1e89638df) | Mar 20, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1a94f7526c](https://linux-hardware.org/?probe=1a94f7526c) | Mar 20, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [48816e7394](https://linux-hardware.org/?probe=48816e7394) | Mar 20, 2022 |
| HP            | G60                         | Notebook    | [1c6928748c](https://linux-hardware.org/?probe=1c6928748c) | Mar 20, 2022 |
| HP            | 212B                        | Desktop     | [fd6a569226](https://linux-hardware.org/?probe=fd6a569226) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | Desktop     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| ECS           | Nettle2                     | Desktop     | [7de5975b89](https://linux-hardware.org/?probe=7de5975b89) | Mar 20, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [ddc4f4eb12](https://linux-hardware.org/?probe=ddc4f4eb12) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Lenovo        | ThinkStation S30 060618U    | Desktop     | [c448617378](https://linux-hardware.org/?probe=c448617378) | Mar 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | Notebook    | [40767d2545](https://linux-hardware.org/?probe=40767d2545) | Mar 20, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| AMI           | Cherry Trail Tablet         | Desktop     | [d0d93b8255](https://linux-hardware.org/?probe=d0d93b8255) | Mar 20, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [bde47f2d75](https://linux-hardware.org/?probe=bde47f2d75) | Mar 20, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [0a049d10a0](https://linux-hardware.org/?probe=0a049d10a0) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| MSI           | MEG Z390 ACE                | Desktop     | [688c3edc68](https://linux-hardware.org/?probe=688c3edc68) | Mar 20, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [f4ddfd1d86](https://linux-hardware.org/?probe=f4ddfd1d86) | Mar 20, 2022 |
| HP            | 2129                        | Desktop     | [9e7ce5ec4f](https://linux-hardware.org/?probe=9e7ce5ec4f) | Mar 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f350633b4c](https://linux-hardware.org/?probe=f350633b4c) | Mar 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [18068927e6](https://linux-hardware.org/?probe=18068927e6) | Mar 20, 2022 |
| ASUSTek       | Q302LA                      | Notebook    | [6becfd09c7](https://linux-hardware.org/?probe=6becfd09c7) | Mar 20, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [978401b13f](https://linux-hardware.org/?probe=978401b13f) | Mar 19, 2022 |
| HP            | 2129                        | Desktop     | [0d503098ab](https://linux-hardware.org/?probe=0d503098ab) | Mar 19, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [e28d2754db](https://linux-hardware.org/?probe=e28d2754db) | Mar 19, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [73734bbce5](https://linux-hardware.org/?probe=73734bbce5) | Mar 19, 2022 |
| Toshiba       | Satellite C55-A             | Notebook    | [64205d8db1](https://linux-hardware.org/?probe=64205d8db1) | Mar 19, 2022 |
| Dell          | Inspiron 23 Model 5348      | All in one  | [395b83dbee](https://linux-hardware.org/?probe=395b83dbee) | Mar 19, 2022 |
| Toshiba       | Satellite A215              | Notebook    | [71640615db](https://linux-hardware.org/?probe=71640615db) | Mar 19, 2022 |
| ASUSTek       | VC62B                       | Desktop     | [c7bb3b876e](https://linux-hardware.org/?probe=c7bb3b876e) | Mar 19, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [c2085f4682](https://linux-hardware.org/?probe=c2085f4682) | Mar 19, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [174ce8eaee](https://linux-hardware.org/?probe=174ce8eaee) | Mar 19, 2022 |
| HP            | Laptop 17z-ca100            | Notebook    | [048eff2daf](https://linux-hardware.org/?probe=048eff2daf) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a3859ab679](https://linux-hardware.org/?probe=a3859ab679) | Mar 19, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [26259fd4dc](https://linux-hardware.org/?probe=26259fd4dc) | Mar 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9323d5d425](https://linux-hardware.org/?probe=9323d5d425) | Mar 19, 2022 |
| HP            | 1497                        | Desktop     | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a2f09086d6](https://linux-hardware.org/?probe=a2f09086d6) | Mar 19, 2022 |
| HP            | 1497                        | Desktop     | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [de08cb0741](https://linux-hardware.org/?probe=de08cb0741) | Mar 19, 2022 |
| Lenovo        | ThinkPad X380 Yoga S1 20... | Convertible | [2483796507](https://linux-hardware.org/?probe=2483796507) | Mar 19, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1c178b66d4](https://linux-hardware.org/?probe=1c178b66d4) | Mar 19, 2022 |
| Dell          | System XPS L502X            | Notebook    | [6de37bd23c](https://linux-hardware.org/?probe=6de37bd23c) | Mar 19, 2022 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [ebc42c3206](https://linux-hardware.org/?probe=ebc42c3206) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [eca789aa9e](https://linux-hardware.org/?probe=eca789aa9e) | Mar 19, 2022 |
| Sony          | VGN-NW265F                  | Notebook    | [0bd4cf9bde](https://linux-hardware.org/?probe=0bd4cf9bde) | Mar 19, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [893f0d0600](https://linux-hardware.org/?probe=893f0d0600) | Mar 19, 2022 |
| Sony          | VGN-NW265F                  | Notebook    | [31435ee17a](https://linux-hardware.org/?probe=31435ee17a) | Mar 19, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [1897912bfc](https://linux-hardware.org/?probe=1897912bfc) | Mar 19, 2022 |
| HP            | 212B                        | Desktop     | [a85896bd48](https://linux-hardware.org/?probe=a85896bd48) | Mar 19, 2022 |
| Dell          | Precision M4600             | Notebook    | [917eabe3cc](https://linux-hardware.org/?probe=917eabe3cc) | Mar 19, 2022 |
| ASUSTek       | K52F                        | Notebook    | [b064184bd6](https://linux-hardware.org/?probe=b064184bd6) | Mar 19, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [bbe016165a](https://linux-hardware.org/?probe=bbe016165a) | Mar 19, 2022 |
| HP            | 2B4B                        | Desktop     | [def1b2ee5b](https://linux-hardware.org/?probe=def1b2ee5b) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6c063a5e86](https://linux-hardware.org/?probe=6c063a5e86) | Mar 19, 2022 |
| Quanta        | XV1                         | All in one  | [664ab2f9a0](https://linux-hardware.org/?probe=664ab2f9a0) | Mar 19, 2022 |
| Unknown       | MNT Reform 2                | Soc         | [e76c7cf9c8](https://linux-hardware.org/?probe=e76c7cf9c8) | Mar 19, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [336e7a8d1d](https://linux-hardware.org/?probe=336e7a8d1d) | Mar 19, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [10ae2a1745](https://linux-hardware.org/?probe=10ae2a1745) | Mar 19, 2022 |
| HP            | 84EF 01100                  | All in one  | [be542cf367](https://linux-hardware.org/?probe=be542cf367) | Mar 19, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [9cd261d803](https://linux-hardware.org/?probe=9cd261d803) | Mar 19, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8b3c916bb0](https://linux-hardware.org/?probe=8b3c916bb0) | Mar 19, 2022 |
| Acer          | Unknown                     | Notebook    | [3c80f8700c](https://linux-hardware.org/?probe=3c80f8700c) | Mar 19, 2022 |
| HP            | 212A                        | Desktop     | [785ff8748d](https://linux-hardware.org/?probe=785ff8748d) | Mar 19, 2022 |
| HP            | Presario CQ61               | Notebook    | [42e2a0f23c](https://linux-hardware.org/?probe=42e2a0f23c) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [502161d29c](https://linux-hardware.org/?probe=502161d29c) | Mar 19, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [1061ea850a](https://linux-hardware.org/?probe=1061ea850a) | Mar 19, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [7da4dbd801](https://linux-hardware.org/?probe=7da4dbd801) | Mar 19, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [61cccd28c6](https://linux-hardware.org/?probe=61cccd28c6) | Mar 18, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [e46a5c3db4](https://linux-hardware.org/?probe=e46a5c3db4) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [a2b06f49d3](https://linux-hardware.org/?probe=a2b06f49d3) | Mar 18, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [188141a9c9](https://linux-hardware.org/?probe=188141a9c9) | Mar 18, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4db96169bf](https://linux-hardware.org/?probe=4db96169bf) | Mar 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3603330b59](https://linux-hardware.org/?probe=3603330b59) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [9e32abccd6](https://linux-hardware.org/?probe=9e32abccd6) | Mar 18, 2022 |
| GMKTEC        | NucBox4                     | Mini pc     | [66d039c977](https://linux-hardware.org/?probe=66d039c977) | Mar 18, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [d50c3e8e85](https://linux-hardware.org/?probe=d50c3e8e85) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [b2d732d46b](https://linux-hardware.org/?probe=b2d732d46b) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [6dbcdd388c](https://linux-hardware.org/?probe=6dbcdd388c) | Mar 18, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7d4d2482ed](https://linux-hardware.org/?probe=7d4d2482ed) | Mar 18, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Intel         | NUC7i3BNB J22859-308        | Mini pc     | [418f0a8f9a](https://linux-hardware.org/?probe=418f0a8f9a) | Mar 18, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [5531c7e4aa](https://linux-hardware.org/?probe=5531c7e4aa) | Mar 18, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [117807dfde](https://linux-hardware.org/?probe=117807dfde) | Mar 18, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [1cfb4ec565](https://linux-hardware.org/?probe=1cfb4ec565) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [ca76b3a899](https://linux-hardware.org/?probe=ca76b3a899) | Mar 18, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c869642fe9](https://linux-hardware.org/?probe=c869642fe9) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [f444e85d64](https://linux-hardware.org/?probe=f444e85d64) | Mar 18, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [99852ed093](https://linux-hardware.org/?probe=99852ed093) | Mar 18, 2022 |
| MSI           | MS-7309                     | Desktop     | [60978399dd](https://linux-hardware.org/?probe=60978399dd) | Mar 18, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [bf2f07e405](https://linux-hardware.org/?probe=bf2f07e405) | Mar 18, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [337a1bad36](https://linux-hardware.org/?probe=337a1bad36) | Mar 17, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [39379d5442](https://linux-hardware.org/?probe=39379d5442) | Mar 17, 2022 |
| Dell          | Precision M6300             | Notebook    | [aac71b9e66](https://linux-hardware.org/?probe=aac71b9e66) | Mar 17, 2022 |
| HP            | ZBook 15                    | Notebook    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [ed96937786](https://linux-hardware.org/?probe=ed96937786) | Mar 17, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e97e686e5e](https://linux-hardware.org/?probe=e97e686e5e) | Mar 17, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [ddca79ef25](https://linux-hardware.org/?probe=ddca79ef25) | Mar 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c5e201fa28](https://linux-hardware.org/?probe=c5e201fa28) | Mar 17, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4730bac7be](https://linux-hardware.org/?probe=4730bac7be) | Mar 17, 2022 |
| Quanta        | XV1                         | All in one  | [254f07ab99](https://linux-hardware.org/?probe=254f07ab99) | Mar 17, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [14d41935a3](https://linux-hardware.org/?probe=14d41935a3) | Mar 17, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [984debdd3a](https://linux-hardware.org/?probe=984debdd3a) | Mar 17, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [c6b6cc1f1d](https://linux-hardware.org/?probe=c6b6cc1f1d) | Mar 17, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f7eb058e61](https://linux-hardware.org/?probe=f7eb058e61) | Mar 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f8dc18bdeb](https://linux-hardware.org/?probe=f8dc18bdeb) | Mar 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [9d6f42b14f](https://linux-hardware.org/?probe=9d6f42b14f) | Mar 17, 2022 |
| HP            | 1408h                       | Desktop     | [d80307d774](https://linux-hardware.org/?probe=d80307d774) | Mar 17, 2022 |
| HP            | 18E4                        | Desktop     | [d7f09dbc7f](https://linux-hardware.org/?probe=d7f09dbc7f) | Mar 17, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [8713806c38](https://linux-hardware.org/?probe=8713806c38) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [662aed3d5d](https://linux-hardware.org/?probe=662aed3d5d) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b3fc1a1d0f](https://linux-hardware.org/?probe=b3fc1a1d0f) | Mar 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [42b5f424ce](https://linux-hardware.org/?probe=42b5f424ce) | Mar 17, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [ef6cbc7487](https://linux-hardware.org/?probe=ef6cbc7487) | Mar 17, 2022 |
| Toshiba       | NB205                       | Notebook    | [ffef19b228](https://linux-hardware.org/?probe=ffef19b228) | Mar 17, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [4ce7c47ad3](https://linux-hardware.org/?probe=4ce7c47ad3) | Mar 17, 2022 |
| Intel         | NUC11DBBi7 M17027-302       | Mini pc     | [e1e4cbbe30](https://linux-hardware.org/?probe=e1e4cbbe30) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b844e23ce9](https://linux-hardware.org/?probe=b844e23ce9) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [09c5000bcf](https://linux-hardware.org/?probe=09c5000bcf) | Mar 17, 2022 |
| Dell          | 0KP561                      | Desktop     | [15e036da0a](https://linux-hardware.org/?probe=15e036da0a) | Mar 17, 2022 |
| HP            | 2B38                        | Desktop     | [c6683944f3](https://linux-hardware.org/?probe=c6683944f3) | Mar 17, 2022 |
| Google        | Nightfury                   | Notebook    | [33c6929b2c](https://linux-hardware.org/?probe=33c6929b2c) | Mar 16, 2022 |
| MSI           | 760GM -E51                  | Desktop     | [0d9d56531d](https://linux-hardware.org/?probe=0d9d56531d) | Mar 16, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [97ebb0ca74](https://linux-hardware.org/?probe=97ebb0ca74) | Mar 16, 2022 |
| Lenovo        | ThinkPad X220 428767U       | Notebook    | [380351014b](https://linux-hardware.org/?probe=380351014b) | Mar 16, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ffa4f295ea](https://linux-hardware.org/?probe=ffa4f295ea) | Mar 16, 2022 |
| Intel         | S3420GPV E80883-108         | Server      | [4578cc36e9](https://linux-hardware.org/?probe=4578cc36e9) | Mar 16, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [f89e1abb77](https://linux-hardware.org/?probe=f89e1abb77) | Mar 16, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [511799e917](https://linux-hardware.org/?probe=511799e917) | Mar 16, 2022 |
| Dell          | 0V8WGR A02                  | Desktop     | [be045a4a24](https://linux-hardware.org/?probe=be045a4a24) | Mar 16, 2022 |
| Dell          | 0D28YY A02                  | Desktop     | [a00f7419d4](https://linux-hardware.org/?probe=a00f7419d4) | Mar 16, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [0d0e297d92](https://linux-hardware.org/?probe=0d0e297d92) | Mar 16, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [bff9275f72](https://linux-hardware.org/?probe=bff9275f72) | Mar 16, 2022 |
| HP            | Pavilion dv7                | Notebook    | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [33a4b92bf4](https://linux-hardware.org/?probe=33a4b92bf4) | Mar 16, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [f785998dcb](https://linux-hardware.org/?probe=f785998dcb) | Mar 16, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2bb6b8bfd0](https://linux-hardware.org/?probe=2bb6b8bfd0) | Mar 16, 2022 |
| HP            | Beats 15                    | Notebook    | [7313ce7e1c](https://linux-hardware.org/?probe=7313ce7e1c) | Mar 16, 2022 |
| Dell          | 0XHYJF A00                  | All in one  | [c792f3478c](https://linux-hardware.org/?probe=c792f3478c) | Mar 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [71d2d562d7](https://linux-hardware.org/?probe=71d2d562d7) | Mar 16, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [ac96c74ffa](https://linux-hardware.org/?probe=ac96c74ffa) | Mar 16, 2022 |
| Acer          | Predator G9-793             | Notebook    | [c8068717f8](https://linux-hardware.org/?probe=c8068717f8) | Mar 16, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [24c4fad70d](https://linux-hardware.org/?probe=24c4fad70d) | Mar 16, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [9aa148dba8](https://linux-hardware.org/?probe=9aa148dba8) | Mar 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2f4e37d664](https://linux-hardware.org/?probe=2f4e37d664) | Mar 16, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [da960303b7](https://linux-hardware.org/?probe=da960303b7) | Mar 15, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [25c3d1bf8e](https://linux-hardware.org/?probe=25c3d1bf8e) | Mar 15, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [acdee8aa65](https://linux-hardware.org/?probe=acdee8aa65) | Mar 15, 2022 |
| HP            | 1791                        | Desktop     | [f183c3d0f0](https://linux-hardware.org/?probe=f183c3d0f0) | Mar 15, 2022 |
| ASUSTek       | KRPG-U8-M Series 60SB08F... | Server      | [fc76dc2d45](https://linux-hardware.org/?probe=fc76dc2d45) | Mar 15, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [46b66a5e79](https://linux-hardware.org/?probe=46b66a5e79) | Mar 15, 2022 |
| HP            | Notebook                    | Notebook    | [9f8b00a91e](https://linux-hardware.org/?probe=9f8b00a91e) | Mar 15, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [bf80f02a40](https://linux-hardware.org/?probe=bf80f02a40) | Mar 15, 2022 |
| Lenovo        | ThinkPad T430s 23539LU      | Notebook    | [2712be9a10](https://linux-hardware.org/?probe=2712be9a10) | Mar 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| ASRock        | X470 Gaming K4              | Desktop     | [90eaa170d1](https://linux-hardware.org/?probe=90eaa170d1) | Mar 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [38dfe1da08](https://linux-hardware.org/?probe=38dfe1da08) | Mar 15, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [8070a2b368](https://linux-hardware.org/?probe=8070a2b368) | Mar 15, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [880e4559ea](https://linux-hardware.org/?probe=880e4559ea) | Mar 15, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2aa5fb5b66](https://linux-hardware.org/?probe=2aa5fb5b66) | Mar 15, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [49e50389ea](https://linux-hardware.org/?probe=49e50389ea) | Mar 15, 2022 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [66bda745cd](https://linux-hardware.org/?probe=66bda745cd) | Mar 15, 2022 |
| Gigabyte      | P64V7                       | Notebook    | [13f2e44186](https://linux-hardware.org/?probe=13f2e44186) | Mar 15, 2022 |
| Dell          | Precision 5560              | Notebook    | [37f8320dbb](https://linux-hardware.org/?probe=37f8320dbb) | Mar 15, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [c630bfd983](https://linux-hardware.org/?probe=c630bfd983) | Mar 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e80ab61827](https://linux-hardware.org/?probe=e80ab61827) | Mar 15, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [de6a7f79dc](https://linux-hardware.org/?probe=de6a7f79dc) | Mar 15, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [989803570d](https://linux-hardware.org/?probe=989803570d) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5af008b464](https://linux-hardware.org/?probe=5af008b464) | Mar 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [8fade33706](https://linux-hardware.org/?probe=8fade33706) | Mar 15, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [e2c193b366](https://linux-hardware.org/?probe=e2c193b366) | Mar 15, 2022 |
| Dell          | Latitude E6420              | Notebook    | [87d2a9b938](https://linux-hardware.org/?probe=87d2a9b938) | Mar 15, 2022 |
| Dell          | Latitude E6420              | Notebook    | [9bef261182](https://linux-hardware.org/?probe=9bef261182) | Mar 15, 2022 |
| Lenovo        | ThinkPad T520 4242C29       | Notebook    | [a531420462](https://linux-hardware.org/?probe=a531420462) | Mar 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [1b4dece8ef](https://linux-hardware.org/?probe=1b4dece8ef) | Mar 15, 2022 |
| Lenovo        | IdeaPad 130S-11IGM 81KT     | Notebook    | [11141a22b9](https://linux-hardware.org/?probe=11141a22b9) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a4cc8c4dda](https://linux-hardware.org/?probe=a4cc8c4dda) | Mar 15, 2022 |
| ASUSTek       | U50F                        | Notebook    | [c141bcbfe2](https://linux-hardware.org/?probe=c141bcbfe2) | Mar 15, 2022 |
| Dell          | 048DY8 A01                  | Desktop     | [112d1b7284](https://linux-hardware.org/?probe=112d1b7284) | Mar 15, 2022 |
| Dell          | Precision 7540              | Notebook    | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| Dell          | Latitude 5179               | Tablet      | [e2e7d9ce38](https://linux-hardware.org/?probe=e2e7d9ce38) | Mar 15, 2022 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [fcb0dd110e](https://linux-hardware.org/?probe=fcb0dd110e) | Mar 15, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [6f3fb1f058](https://linux-hardware.org/?probe=6f3fb1f058) | Mar 15, 2022 |
| Sony          | VPCEB3PGX                   | Notebook    | [a11076558f](https://linux-hardware.org/?probe=a11076558f) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0755c3c4a6](https://linux-hardware.org/?probe=0755c3c4a6) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [affad66907](https://linux-hardware.org/?probe=affad66907) | Mar 14, 2022 |
| Google        | Akemi                       | Notebook    | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [8116dd6dc0](https://linux-hardware.org/?probe=8116dd6dc0) | Mar 14, 2022 |
| Acer          | Aspire E5-571P              | Notebook    | [dd68b81b43](https://linux-hardware.org/?probe=dd68b81b43) | Mar 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [510f8a2d24](https://linux-hardware.org/?probe=510f8a2d24) | Mar 14, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [3c7163e5d1](https://linux-hardware.org/?probe=3c7163e5d1) | Mar 14, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7284aabd99](https://linux-hardware.org/?probe=7284aabd99) | Mar 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [96846ed571](https://linux-hardware.org/?probe=96846ed571) | Mar 14, 2022 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [f78973af80](https://linux-hardware.org/?probe=f78973af80) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [79744a34f1](https://linux-hardware.org/?probe=79744a34f1) | Mar 14, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fe194c95e7](https://linux-hardware.org/?probe=fe194c95e7) | Mar 14, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [58afe91a23](https://linux-hardware.org/?probe=58afe91a23) | Mar 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a15fc5e821](https://linux-hardware.org/?probe=a15fc5e821) | Mar 14, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [3eb18e0c33](https://linux-hardware.org/?probe=3eb18e0c33) | Mar 14, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [cc0cf690b8](https://linux-hardware.org/?probe=cc0cf690b8) | Mar 14, 2022 |
| Acer          | Aspire X1920                | Desktop     | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3292ffd09b](https://linux-hardware.org/?probe=3292ffd09b) | Mar 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [b400e8a455](https://linux-hardware.org/?probe=b400e8a455) | Mar 14, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [ae1bd048b6](https://linux-hardware.org/?probe=ae1bd048b6) | Mar 14, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [4c6f20c36b](https://linux-hardware.org/?probe=4c6f20c36b) | Mar 14, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [5cdaea7c5a](https://linux-hardware.org/?probe=5cdaea7c5a) | Mar 14, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [2e45a56117](https://linux-hardware.org/?probe=2e45a56117) | Mar 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [a140c71898](https://linux-hardware.org/?probe=a140c71898) | Mar 14, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [3ec42009e9](https://linux-hardware.org/?probe=3ec42009e9) | Mar 14, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [9c1fd2beff](https://linux-hardware.org/?probe=9c1fd2beff) | Mar 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Lenovo        | Flex 3-1120 80LX            | Notebook    | [181446e2e8](https://linux-hardware.org/?probe=181446e2e8) | Mar 14, 2022 |
| Dell          | Precision M6300             | Notebook    | [33461d300c](https://linux-hardware.org/?probe=33461d300c) | Mar 14, 2022 |
| Dell          | 0CU409                      | Desktop     | [2e684afab9](https://linux-hardware.org/?probe=2e684afab9) | Mar 14, 2022 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| Purism        | Librem Mini v2              | Desktop     | [909124577c](https://linux-hardware.org/?probe=909124577c) | Mar 14, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d623639513](https://linux-hardware.org/?probe=d623639513) | Mar 14, 2022 |
| Intel         | B75                         | Desktop     | [12d9e05170](https://linux-hardware.org/?probe=12d9e05170) | Mar 14, 2022 |
| Eluktronic... | Mech-15 G2                  | Notebook    | [5dd8b83919](https://linux-hardware.org/?probe=5dd8b83919) | Mar 14, 2022 |
| Lenovo        | ThinkPad X240 20AM001FUS    | Notebook    | [bb0dd6b2c6](https://linux-hardware.org/?probe=bb0dd6b2c6) | Mar 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d20947cecc](https://linux-hardware.org/?probe=d20947cecc) | Mar 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [7bf2683ce7](https://linux-hardware.org/?probe=7bf2683ce7) | Mar 13, 2022 |
| Dell          | Vostro 1014                 | Notebook    | [8df761ef60](https://linux-hardware.org/?probe=8df761ef60) | Mar 13, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5bbcfdb40a](https://linux-hardware.org/?probe=5bbcfdb40a) | Mar 13, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [50ca449b34](https://linux-hardware.org/?probe=50ca449b34) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [79211f85fd](https://linux-hardware.org/?probe=79211f85fd) | Mar 13, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [4a24f1b828](https://linux-hardware.org/?probe=4a24f1b828) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [ef67eef250](https://linux-hardware.org/?probe=ef67eef250) | Mar 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2d92a0b793](https://linux-hardware.org/?probe=2d92a0b793) | Mar 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [0f7b503cac](https://linux-hardware.org/?probe=0f7b503cac) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [9ca31007a9](https://linux-hardware.org/?probe=9ca31007a9) | Mar 13, 2022 |
| HP            | Notebook                    | Notebook    | [2a7e60663b](https://linux-hardware.org/?probe=2a7e60663b) | Mar 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b46a2338a9](https://linux-hardware.org/?probe=b46a2338a9) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692ae92211](https://linux-hardware.org/?probe=692ae92211) | Mar 13, 2022 |
| HP            | Presario CQ62               | Notebook    | [143eade9bc](https://linux-hardware.org/?probe=143eade9bc) | Mar 13, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [0141fa64e7](https://linux-hardware.org/?probe=0141fa64e7) | Mar 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [75561646a7](https://linux-hardware.org/?probe=75561646a7) | Mar 13, 2022 |
| HP            | ProBook 6570b               | Notebook    | [9f0b342200](https://linux-hardware.org/?probe=9f0b342200) | Mar 13, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [12b1601612](https://linux-hardware.org/?probe=12b1601612) | Mar 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8748617cf6](https://linux-hardware.org/?probe=8748617cf6) | Mar 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a4a0bfd589](https://linux-hardware.org/?probe=a4a0bfd589) | Mar 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [69776eaddb](https://linux-hardware.org/?probe=69776eaddb) | Mar 13, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [faea9769bd](https://linux-hardware.org/?probe=faea9769bd) | Mar 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5d90a423a](https://linux-hardware.org/?probe=d5d90a423a) | Mar 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [d8d5ec973e](https://linux-hardware.org/?probe=d8d5ec973e) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6e9075eebf](https://linux-hardware.org/?probe=6e9075eebf) | Mar 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [fa25281433](https://linux-hardware.org/?probe=fa25281433) | Mar 13, 2022 |
| ASUSTek       | H110T                       | Desktop     | [5ef8fe35e7](https://linux-hardware.org/?probe=5ef8fe35e7) | Mar 13, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b009bb5f7b](https://linux-hardware.org/?probe=b009bb5f7b) | Mar 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [3c0450f79e](https://linux-hardware.org/?probe=3c0450f79e) | Mar 12, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1dac441515](https://linux-hardware.org/?probe=1dac441515) | Mar 12, 2022 |
| HP            | Pavilion dm4                | Notebook    | [994eb45f2d](https://linux-hardware.org/?probe=994eb45f2d) | Mar 12, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b8783a8415](https://linux-hardware.org/?probe=b8783a8415) | Mar 12, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b0d58c6895](https://linux-hardware.org/?probe=b0d58c6895) | Mar 12, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| HP            | Pavilion dm4                | Notebook    | [603ede9010](https://linux-hardware.org/?probe=603ede9010) | Mar 12, 2022 |
| Dell          | 0G214D A00                  | Desktop     | [e46f86cef3](https://linux-hardware.org/?probe=e46f86cef3) | Mar 12, 2022 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [e3f3e0ced8](https://linux-hardware.org/?probe=e3f3e0ced8) | Mar 12, 2022 |
| System76      | Bonobo Extreme              | Notebook    | [c6e68c91be](https://linux-hardware.org/?probe=c6e68c91be) | Mar 12, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [d12c9208e2](https://linux-hardware.org/?probe=d12c9208e2) | Mar 12, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [27ad4e792a](https://linux-hardware.org/?probe=27ad4e792a) | Mar 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [330df8b88f](https://linux-hardware.org/?probe=330df8b88f) | Mar 12, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5aebd2929](https://linux-hardware.org/?probe=f5aebd2929) | Mar 12, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [2ce797deb7](https://linux-hardware.org/?probe=2ce797deb7) | Mar 12, 2022 |
| HP            | Pavilion dm1                | Notebook    | [d65e1a184d](https://linux-hardware.org/?probe=d65e1a184d) | Mar 12, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [99ca8628cb](https://linux-hardware.org/?probe=99ca8628cb) | Mar 12, 2022 |
| ASUSTek       | UX303LB                     | Notebook    | [72333c923a](https://linux-hardware.org/?probe=72333c923a) | Mar 12, 2022 |
| MSI           | B85I                        | Desktop     | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [2e7a87521b](https://linux-hardware.org/?probe=2e7a87521b) | Mar 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [cef0b5d08f](https://linux-hardware.org/?probe=cef0b5d08f) | Mar 12, 2022 |
| Toshiba       | Satellite M505              | Notebook    | [924c539075](https://linux-hardware.org/?probe=924c539075) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [a610ee6ad5](https://linux-hardware.org/?probe=a610ee6ad5) | Mar 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [bad1a1b41f](https://linux-hardware.org/?probe=bad1a1b41f) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6e87cdd1f8](https://linux-hardware.org/?probe=6e87cdd1f8) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [a89e3579bb](https://linux-hardware.org/?probe=a89e3579bb) | Mar 12, 2022 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [2b5fbf2b8d](https://linux-hardware.org/?probe=2b5fbf2b8d) | Mar 12, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [f631bcb571](https://linux-hardware.org/?probe=f631bcb571) | Mar 12, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [446c4bf806](https://linux-hardware.org/?probe=446c4bf806) | Mar 12, 2022 |
| Lenovo        | IdeaPad Y470 0855           | Notebook    | [c8147cdb14](https://linux-hardware.org/?probe=c8147cdb14) | Mar 12, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [767b1b8d8a](https://linux-hardware.org/?probe=767b1b8d8a) | Mar 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a90ce91192](https://linux-hardware.org/?probe=a90ce91192) | Mar 12, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [aeb0fd4285](https://linux-hardware.org/?probe=aeb0fd4285) | Mar 12, 2022 |
| Dell          | Inspiron 3737               | Notebook    | [3774744b28](https://linux-hardware.org/?probe=3774744b28) | Mar 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d27fc1966e](https://linux-hardware.org/?probe=d27fc1966e) | Mar 12, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [d5da8049b1](https://linux-hardware.org/?probe=d5da8049b1) | Mar 12, 2022 |
| Dell          | Latitude 5179               | Tablet      | [19e47782ab](https://linux-hardware.org/?probe=19e47782ab) | Mar 12, 2022 |
| Dell          | G7 7590                     | Notebook    | [61a03c12fd](https://linux-hardware.org/?probe=61a03c12fd) | Mar 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [1d225e4863](https://linux-hardware.org/?probe=1d225e4863) | Mar 12, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4Q20... | Notebook    | [4d9c3fdcc5](https://linux-hardware.org/?probe=4d9c3fdcc5) | Mar 12, 2022 |
| MSI           | H81M-E34                    | Desktop     | [8d5b326668](https://linux-hardware.org/?probe=8d5b326668) | Mar 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [df1ed73c0f](https://linux-hardware.org/?probe=df1ed73c0f) | Mar 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [110670e1e6](https://linux-hardware.org/?probe=110670e1e6) | Mar 11, 2022 |
| Acer          | Aspire V5-552PG             | Notebook    | [5f0d6016fc](https://linux-hardware.org/?probe=5f0d6016fc) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [facc8337d2](https://linux-hardware.org/?probe=facc8337d2) | Mar 11, 2022 |
| Dell          | 0KP561                      | Desktop     | [1a7c8bbe84](https://linux-hardware.org/?probe=1a7c8bbe84) | Mar 11, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [d98e8dd76d](https://linux-hardware.org/?probe=d98e8dd76d) | Mar 11, 2022 |
| Nvidia        | Tegra                       | Soc         | [3f369fa012](https://linux-hardware.org/?probe=3f369fa012) | Mar 11, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0c4ce09431](https://linux-hardware.org/?probe=0c4ce09431) | Mar 11, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e3c4fb5a9c](https://linux-hardware.org/?probe=e3c4fb5a9c) | Mar 11, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [fb67cfa88f](https://linux-hardware.org/?probe=fb67cfa88f) | Mar 11, 2022 |
| Eluktronic... | MAG-15u                     | Notebook    | [93c4944323](https://linux-hardware.org/?probe=93c4944323) | Mar 11, 2022 |
| Alienware     | 15 R2                       | Notebook    | [4ffade43e3](https://linux-hardware.org/?probe=4ffade43e3) | Mar 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5be1842448](https://linux-hardware.org/?probe=5be1842448) | Mar 11, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [4f1cae64b4](https://linux-hardware.org/?probe=4f1cae64b4) | Mar 11, 2022 |
| ASUSTek       | Q501LA                      | Notebook    | [bf2f9b2c1d](https://linux-hardware.org/?probe=bf2f9b2c1d) | Mar 11, 2022 |
| HP            | 3396                        | Desktop     | [7bd27c71ed](https://linux-hardware.org/?probe=7bd27c71ed) | Mar 11, 2022 |
| HP            | 3396                        | Desktop     | [adeef3162a](https://linux-hardware.org/?probe=adeef3162a) | Mar 11, 2022 |
| Dell          | G7 7588                     | Notebook    | [bd49253351](https://linux-hardware.org/?probe=bd49253351) | Mar 11, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b43ace9110](https://linux-hardware.org/?probe=b43ace9110) | Mar 11, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [3ecbd85311](https://linux-hardware.org/?probe=3ecbd85311) | Mar 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [cddc590270](https://linux-hardware.org/?probe=cddc590270) | Mar 11, 2022 |
| Dell          | Latitude 5179               | Tablet      | [6430380d5b](https://linux-hardware.org/?probe=6430380d5b) | Mar 11, 2022 |
| HP            | HDX18                       | Notebook    | [a6788bfe93](https://linux-hardware.org/?probe=a6788bfe93) | Mar 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f953ec8b63](https://linux-hardware.org/?probe=f953ec8b63) | Mar 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [21509b1c8f](https://linux-hardware.org/?probe=21509b1c8f) | Mar 11, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [2a4e580bd6](https://linux-hardware.org/?probe=2a4e580bd6) | Mar 11, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [841857dd45](https://linux-hardware.org/?probe=841857dd45) | Mar 11, 2022 |
| Lenovo        | ThinkPad T450 20BUS14900    | Notebook    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [5e908476ac](https://linux-hardware.org/?probe=5e908476ac) | Mar 11, 2022 |
| ASUSTek       | H110T                       | Desktop     | [2e32ea8d20](https://linux-hardware.org/?probe=2e32ea8d20) | Mar 10, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [c21a817015](https://linux-hardware.org/?probe=c21a817015) | Mar 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [b15d6eb8fb](https://linux-hardware.org/?probe=b15d6eb8fb) | Mar 10, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [3617d41378](https://linux-hardware.org/?probe=3617d41378) | Mar 10, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [dc38e0d85a](https://linux-hardware.org/?probe=dc38e0d85a) | Mar 10, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [93c8bff33b](https://linux-hardware.org/?probe=93c8bff33b) | Mar 10, 2022 |
| HP            | 82F1                        | Desktop     | [390462d20a](https://linux-hardware.org/?probe=390462d20a) | Mar 10, 2022 |
| HP            | 82F1                        | Desktop     | [63273af14a](https://linux-hardware.org/?probe=63273af14a) | Mar 10, 2022 |
| Dell          | Latitude 5179               | Tablet      | [3e5a3e7110](https://linux-hardware.org/?probe=3e5a3e7110) | Mar 10, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c9b7431269](https://linux-hardware.org/?probe=c9b7431269) | Mar 10, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [60a1d94845](https://linux-hardware.org/?probe=60a1d94845) | Mar 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d4c070b714](https://linux-hardware.org/?probe=d4c070b714) | Mar 10, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [f094b510c8](https://linux-hardware.org/?probe=f094b510c8) | Mar 10, 2022 |
| Lenovo        | ThinkPad X280 20KES4H34G    | Notebook    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Biostar       | TA785G3                     | Desktop     | [320e862589](https://linux-hardware.org/?probe=320e862589) | Mar 10, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [a4d2e10715](https://linux-hardware.org/?probe=a4d2e10715) | Mar 10, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [caf1f719f4](https://linux-hardware.org/?probe=caf1f719f4) | Mar 10, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2c17897902](https://linux-hardware.org/?probe=2c17897902) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [c2c9c6fab7](https://linux-hardware.org/?probe=c2c9c6fab7) | Mar 10, 2022 |
| ASUSTek       | H110T                       | Desktop     | [1a3a353683](https://linux-hardware.org/?probe=1a3a353683) | Mar 10, 2022 |
| Dell          | Latitude 3500               | Notebook    | [6b355ab81f](https://linux-hardware.org/?probe=6b355ab81f) | Mar 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [370e992e57](https://linux-hardware.org/?probe=370e992e57) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Lenovo        | ThinkPad X230 2325P38       | Notebook    | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| Dell          | 04G47W A00                  | All in one  | [ea489d447c](https://linux-hardware.org/?probe=ea489d447c) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Dell          | G7 7590                     | Notebook    | [3411708ddf](https://linux-hardware.org/?probe=3411708ddf) | Mar 10, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [26a4220432](https://linux-hardware.org/?probe=26a4220432) | Mar 09, 2022 |
| Gigabyte      | Z77P-D3                     | Desktop     | [55cb8434d9](https://linux-hardware.org/?probe=55cb8434d9) | Mar 09, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [e7a3d16cc0](https://linux-hardware.org/?probe=e7a3d16cc0) | Mar 09, 2022 |
| Dell          | 068NXX A00                  | Server      | [85004f427a](https://linux-hardware.org/?probe=85004f427a) | Mar 09, 2022 |
| Acer          | Aspire Z1620                | All in one  | [33937e8f75](https://linux-hardware.org/?probe=33937e8f75) | Mar 09, 2022 |
| HP            | 82F2                        | Desktop     | [71511d4306](https://linux-hardware.org/?probe=71511d4306) | Mar 09, 2022 |
| Biostar       | B450MHC                     | Desktop     | [b4d3516747](https://linux-hardware.org/?probe=b4d3516747) | Mar 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [30aa9c3047](https://linux-hardware.org/?probe=30aa9c3047) | Mar 09, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [2eeb109321](https://linux-hardware.org/?probe=2eeb109321) | Mar 09, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [1a3f77be23](https://linux-hardware.org/?probe=1a3f77be23) | Mar 09, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [fe8ce505f4](https://linux-hardware.org/?probe=fe8ce505f4) | Mar 09, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [8714d12640](https://linux-hardware.org/?probe=8714d12640) | Mar 09, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [a6fa73ec8d](https://linux-hardware.org/?probe=a6fa73ec8d) | Mar 09, 2022 |
| Shuttle       | FZ270                       | Desktop     | [ed3e018227](https://linux-hardware.org/?probe=ed3e018227) | Mar 09, 2022 |
| Dell          | 0M5DCD A02                  | Desktop     | [01cae1bb94](https://linux-hardware.org/?probe=01cae1bb94) | Mar 09, 2022 |
| HP            | 82F2                        | Desktop     | [89f622e4b8](https://linux-hardware.org/?probe=89f622e4b8) | Mar 09, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [3e80ef6096](https://linux-hardware.org/?probe=3e80ef6096) | Mar 09, 2022 |
| HP            | 82F2                        | Desktop     | [66bdfc76e1](https://linux-hardware.org/?probe=66bdfc76e1) | Mar 09, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [db53a0fd9b](https://linux-hardware.org/?probe=db53a0fd9b) | Mar 09, 2022 |
| MSI           | Z590 PRO WIFI [CEC]         | Desktop     | [e543f0217a](https://linux-hardware.org/?probe=e543f0217a) | Mar 09, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [4f0186b9ec](https://linux-hardware.org/?probe=4f0186b9ec) | Mar 09, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [60550484ba](https://linux-hardware.org/?probe=60550484ba) | Mar 09, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c8929cd98b](https://linux-hardware.org/?probe=c8929cd98b) | Mar 09, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [0d84aa6c5a](https://linux-hardware.org/?probe=0d84aa6c5a) | Mar 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [64ff6efbda](https://linux-hardware.org/?probe=64ff6efbda) | Mar 09, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [cb5d9880c6](https://linux-hardware.org/?probe=cb5d9880c6) | Mar 09, 2022 |
| HP            | 83E9                        | Desktop     | [3c45f526d3](https://linux-hardware.org/?probe=3c45f526d3) | Mar 09, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5550136ffd](https://linux-hardware.org/?probe=5550136ffd) | Mar 09, 2022 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [29764fb241](https://linux-hardware.org/?probe=29764fb241) | Mar 09, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [eaa5b0f454](https://linux-hardware.org/?probe=eaa5b0f454) | Mar 08, 2022 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [ecafc7a265](https://linux-hardware.org/?probe=ecafc7a265) | Mar 08, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [283c6ec3a9](https://linux-hardware.org/?probe=283c6ec3a9) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [4378396a20](https://linux-hardware.org/?probe=4378396a20) | Mar 08, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7c7762632c](https://linux-hardware.org/?probe=7c7762632c) | Mar 08, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [e207d2bf0a](https://linux-hardware.org/?probe=e207d2bf0a) | Mar 08, 2022 |
| Framework     | Laptop                      | Notebook    | [15219c6b68](https://linux-hardware.org/?probe=15219c6b68) | Mar 08, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [8dbe399133](https://linux-hardware.org/?probe=8dbe399133) | Mar 08, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b17f80ef48](https://linux-hardware.org/?probe=b17f80ef48) | Mar 08, 2022 |
| Framework     | Laptop                      | Notebook    | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [316c39133f](https://linux-hardware.org/?probe=316c39133f) | Mar 08, 2022 |
| Dell          | Latitude 9420               | Notebook    | [6cb4dd22ee](https://linux-hardware.org/?probe=6cb4dd22ee) | Mar 08, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ed11376acd](https://linux-hardware.org/?probe=ed11376acd) | Mar 08, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [05bb30084a](https://linux-hardware.org/?probe=05bb30084a) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [4eb9de0f3a](https://linux-hardware.org/?probe=4eb9de0f3a) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [02b4ade19f](https://linux-hardware.org/?probe=02b4ade19f) | Mar 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a529d98d69](https://linux-hardware.org/?probe=a529d98d69) | Mar 08, 2022 |
| Qualcomm T... | SDM845 v2.1 MTP PVT         | Soc         | [5eccd016b4](https://linux-hardware.org/?probe=5eccd016b4) | Mar 08, 2022 |
| Dell          | 064N3D A00                  | All in one  | [681d2000f3](https://linux-hardware.org/?probe=681d2000f3) | Mar 08, 2022 |
| Dell          | 064N3D A00                  | All in one  | [74096fa54e](https://linux-hardware.org/?probe=74096fa54e) | Mar 08, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [f683f10953](https://linux-hardware.org/?probe=f683f10953) | Mar 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ce025d2364](https://linux-hardware.org/?probe=ce025d2364) | Mar 08, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [2cd2af2acb](https://linux-hardware.org/?probe=2cd2af2acb) | Mar 08, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [392c7890c2](https://linux-hardware.org/?probe=392c7890c2) | Mar 08, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [c2d96b88c5](https://linux-hardware.org/?probe=c2d96b88c5) | Mar 08, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [bd22f532ef](https://linux-hardware.org/?probe=bd22f532ef) | Mar 08, 2022 |
| Dell          | 0M5DCD A02                  | Desktop     | [9435c7f3b8](https://linux-hardware.org/?probe=9435c7f3b8) | Mar 08, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [72d45d3636](https://linux-hardware.org/?probe=72d45d3636) | Mar 08, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [6c40e8cf0f](https://linux-hardware.org/?probe=6c40e8cf0f) | Mar 08, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [a1a19b3342](https://linux-hardware.org/?probe=a1a19b3342) | Mar 08, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [1784618cfe](https://linux-hardware.org/?probe=1784618cfe) | Mar 08, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [ccbc1e6d9c](https://linux-hardware.org/?probe=ccbc1e6d9c) | Mar 08, 2022 |
| Dell          | Latitude XT3                | Notebook    | [780d68029c](https://linux-hardware.org/?probe=780d68029c) | Mar 08, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [73526f92ac](https://linux-hardware.org/?probe=73526f92ac) | Mar 08, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [dcefffbbbf](https://linux-hardware.org/?probe=dcefffbbbf) | Mar 08, 2022 |
| HP            | Notebook                    | Notebook    | [be0d0cad90](https://linux-hardware.org/?probe=be0d0cad90) | Mar 08, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [e06660b923](https://linux-hardware.org/?probe=e06660b923) | Mar 08, 2022 |
| ASRock        | A785GM-LE                   | Desktop     | [9857313ad9](https://linux-hardware.org/?probe=9857313ad9) | Mar 08, 2022 |
| HP            | 8266                        | Desktop     | [3f34cb2ada](https://linux-hardware.org/?probe=3f34cb2ada) | Mar 07, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [c99d57dabd](https://linux-hardware.org/?probe=c99d57dabd) | Mar 07, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [ce108fc7c0](https://linux-hardware.org/?probe=ce108fc7c0) | Mar 07, 2022 |
| ASUSTek       | U43F                        | Notebook    | [d547c2e9d6](https://linux-hardware.org/?probe=d547c2e9d6) | Mar 07, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [db38480b2f](https://linux-hardware.org/?probe=db38480b2f) | Mar 07, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6765f9623b](https://linux-hardware.org/?probe=6765f9623b) | Mar 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [d5c1e965d0](https://linux-hardware.org/?probe=d5c1e965d0) | Mar 07, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [fbd59f7138](https://linux-hardware.org/?probe=fbd59f7138) | Mar 07, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [64771feb72](https://linux-hardware.org/?probe=64771feb72) | Mar 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [6c639bb98e](https://linux-hardware.org/?probe=6c639bb98e) | Mar 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [d00f0e5d1f](https://linux-hardware.org/?probe=d00f0e5d1f) | Mar 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d55dd6147a](https://linux-hardware.org/?probe=d55dd6147a) | Mar 07, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [ebb68892dc](https://linux-hardware.org/?probe=ebb68892dc) | Mar 07, 2022 |
| Sony          | VPCEH25FM                   | Notebook    | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| AZW           | GTR V01                     | Mini pc     | [8a85aeaf5a](https://linux-hardware.org/?probe=8a85aeaf5a) | Mar 07, 2022 |
| MSI           | A75A-G35                    | Desktop     | [8dfa30cef5](https://linux-hardware.org/?probe=8dfa30cef5) | Mar 07, 2022 |
| MSI           | B85I                        | Desktop     | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [2ba8489718](https://linux-hardware.org/?probe=2ba8489718) | Mar 07, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [9bc2f4ce28](https://linux-hardware.org/?probe=9bc2f4ce28) | Mar 07, 2022 |
| HP            | 0A64h                       | Desktop     | [ce6a8f8d54](https://linux-hardware.org/?probe=ce6a8f8d54) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [bf9c067da8](https://linux-hardware.org/?probe=bf9c067da8) | Mar 07, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [afa3998157](https://linux-hardware.org/?probe=afa3998157) | Mar 07, 2022 |
| Dell          | Studio 1749                 | Notebook    | [4d0f69126e](https://linux-hardware.org/?probe=4d0f69126e) | Mar 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [561f82adc5](https://linux-hardware.org/?probe=561f82adc5) | Mar 07, 2022 |
| Dell          | Precision 5520              | Notebook    | [cd1a178797](https://linux-hardware.org/?probe=cd1a178797) | Mar 07, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [422afde3de](https://linux-hardware.org/?probe=422afde3de) | Mar 07, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [fd978b3f7b](https://linux-hardware.org/?probe=fd978b3f7b) | Mar 07, 2022 |
| HP            | 802F                        | Desktop     | [af498c9331](https://linux-hardware.org/?probe=af498c9331) | Mar 07, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8a87e0ca46](https://linux-hardware.org/?probe=8a87e0ca46) | Mar 07, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [eda63a0bb2](https://linux-hardware.org/?probe=eda63a0bb2) | Mar 07, 2022 |
| Dell          | Latitude D630               | Notebook    | [712b22ad9b](https://linux-hardware.org/?probe=712b22ad9b) | Mar 07, 2022 |
| Gateway       | M-6307                      | Notebook    | [046587a2d1](https://linux-hardware.org/?probe=046587a2d1) | Mar 07, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [bc052daf77](https://linux-hardware.org/?probe=bc052daf77) | Mar 07, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7901968d67](https://linux-hardware.org/?probe=7901968d67) | Mar 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [a54e3f7d94](https://linux-hardware.org/?probe=a54e3f7d94) | Mar 07, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [acdeb0a436](https://linux-hardware.org/?probe=acdeb0a436) | Mar 07, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [50420d6d58](https://linux-hardware.org/?probe=50420d6d58) | Mar 07, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [ffa701db86](https://linux-hardware.org/?probe=ffa701db86) | Mar 06, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [188f13e83e](https://linux-hardware.org/?probe=188f13e83e) | Mar 06, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [2ee17064c4](https://linux-hardware.org/?probe=2ee17064c4) | Mar 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [86796279cb](https://linux-hardware.org/?probe=86796279cb) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e14e313311](https://linux-hardware.org/?probe=e14e313311) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5546a82362](https://linux-hardware.org/?probe=5546a82362) | Mar 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [71ec492183](https://linux-hardware.org/?probe=71ec492183) | Mar 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c838207e1b](https://linux-hardware.org/?probe=c838207e1b) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [e893774a5b](https://linux-hardware.org/?probe=e893774a5b) | Mar 06, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [89a66354f4](https://linux-hardware.org/?probe=89a66354f4) | Mar 06, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [1bb7472f87](https://linux-hardware.org/?probe=1bb7472f87) | Mar 06, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [645c9e1a6c](https://linux-hardware.org/?probe=645c9e1a6c) | Mar 06, 2022 |
| Dell          | Latitude D620               | Notebook    | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [6218135a7c](https://linux-hardware.org/?probe=6218135a7c) | Mar 06, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [715dec819e](https://linux-hardware.org/?probe=715dec819e) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [308df080e6](https://linux-hardware.org/?probe=308df080e6) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [19c66b47da](https://linux-hardware.org/?probe=19c66b47da) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [71714718d9](https://linux-hardware.org/?probe=71714718d9) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [ccd6a19ec5](https://linux-hardware.org/?probe=ccd6a19ec5) | Mar 06, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [d8ea22eff5](https://linux-hardware.org/?probe=d8ea22eff5) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [e66faafcce](https://linux-hardware.org/?probe=e66faafcce) | Mar 06, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [d20b4fcfa5](https://linux-hardware.org/?probe=d20b4fcfa5) | Mar 06, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [2bb4d5ab6d](https://linux-hardware.org/?probe=2bb4d5ab6d) | Mar 06, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [fea067392c](https://linux-hardware.org/?probe=fea067392c) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [4b98ae2c5e](https://linux-hardware.org/?probe=4b98ae2c5e) | Mar 06, 2022 |
| HP            | Laptop 17z-ca100            | Notebook    | [a646411afd](https://linux-hardware.org/?probe=a646411afd) | Mar 06, 2022 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [fdd29c8f1e](https://linux-hardware.org/?probe=fdd29c8f1e) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [be30358301](https://linux-hardware.org/?probe=be30358301) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [a630a0c13c](https://linux-hardware.org/?probe=a630a0c13c) | Mar 06, 2022 |
| HP            | 8266                        | Desktop     | [e0991ef205](https://linux-hardware.org/?probe=e0991ef205) | Mar 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c31954f957](https://linux-hardware.org/?probe=c31954f957) | Mar 06, 2022 |
| AZW           | GT-R                        | Notebook    | [a97ebeedcc](https://linux-hardware.org/?probe=a97ebeedcc) | Mar 06, 2022 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [30faf7e57a](https://linux-hardware.org/?probe=30faf7e57a) | Mar 06, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [95c71b7670](https://linux-hardware.org/?probe=95c71b7670) | Mar 05, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [ed4256b15d](https://linux-hardware.org/?probe=ed4256b15d) | Mar 05, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [886e04118a](https://linux-hardware.org/?probe=886e04118a) | Mar 05, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [7a3b2a52e6](https://linux-hardware.org/?probe=7a3b2a52e6) | Mar 05, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [efb5f5ca61](https://linux-hardware.org/?probe=efb5f5ca61) | Mar 05, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [6911de7c71](https://linux-hardware.org/?probe=6911de7c71) | Mar 05, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e29f709958](https://linux-hardware.org/?probe=e29f709958) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [531e740b37](https://linux-hardware.org/?probe=531e740b37) | Mar 05, 2022 |
| System76      | Gazelle                     | Notebook    | [13946c778f](https://linux-hardware.org/?probe=13946c778f) | Mar 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d5ab693301](https://linux-hardware.org/?probe=d5ab693301) | Mar 05, 2022 |
| Lenovo        | ThinkPad T530 2359CTO       | Notebook    | [ceec77f198](https://linux-hardware.org/?probe=ceec77f198) | Mar 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [e1090a394c](https://linux-hardware.org/?probe=e1090a394c) | Mar 05, 2022 |
| Biostar       | A68N-5600                   | Desktop     | [63c0dd5a2a](https://linux-hardware.org/?probe=63c0dd5a2a) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8215dc9a65](https://linux-hardware.org/?probe=8215dc9a65) | Mar 05, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [c303702ac5](https://linux-hardware.org/?probe=c303702ac5) | Mar 05, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [551ff0b485](https://linux-hardware.org/?probe=551ff0b485) | Mar 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [980908e205](https://linux-hardware.org/?probe=980908e205) | Mar 05, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [7ea271a455](https://linux-hardware.org/?probe=7ea271a455) | Mar 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [eb0e69e637](https://linux-hardware.org/?probe=eb0e69e637) | Mar 05, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [d7d139723f](https://linux-hardware.org/?probe=d7d139723f) | Mar 05, 2022 |
| Dell          | Inspiron 5720               | Notebook    | [f676c1d4b6](https://linux-hardware.org/?probe=f676c1d4b6) | Mar 05, 2022 |
| HP            | 1850                        | Desktop     | [c3c194dcb6](https://linux-hardware.org/?probe=c3c194dcb6) | Mar 05, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [179c20b384](https://linux-hardware.org/?probe=179c20b384) | Mar 05, 2022 |
| MOTILE        | M141                        | Notebook    | [932800cf07](https://linux-hardware.org/?probe=932800cf07) | Mar 05, 2022 |
| Dell          | Inspiron 5735               | Notebook    | [cc6ad48a04](https://linux-hardware.org/?probe=cc6ad48a04) | Mar 05, 2022 |
| Dell          | Precision M6700             | Notebook    | [c5cb8cd111](https://linux-hardware.org/?probe=c5cb8cd111) | Mar 05, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [5177de3258](https://linux-hardware.org/?probe=5177de3258) | Mar 05, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [8131bd8724](https://linux-hardware.org/?probe=8131bd8724) | Mar 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ce783fbb35](https://linux-hardware.org/?probe=ce783fbb35) | Mar 05, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [37410fc3e3](https://linux-hardware.org/?probe=37410fc3e3) | Mar 05, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [4c83283b70](https://linux-hardware.org/?probe=4c83283b70) | Mar 05, 2022 |
| ALLDOCUBE     | i1022d                      | Tablet      | [e35ef99862](https://linux-hardware.org/?probe=e35ef99862) | Mar 05, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [90e4cc2972](https://linux-hardware.org/?probe=90e4cc2972) | Mar 05, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [a786074185](https://linux-hardware.org/?probe=a786074185) | Mar 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f7af100d8d](https://linux-hardware.org/?probe=f7af100d8d) | Mar 05, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [d1003b5fce](https://linux-hardware.org/?probe=d1003b5fce) | Mar 05, 2022 |
| Supermicro    | H8DGU                       | Server      | [3051cea326](https://linux-hardware.org/?probe=3051cea326) | Mar 05, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [04ee5a06f2](https://linux-hardware.org/?probe=04ee5a06f2) | Mar 05, 2022 |
| Dell          | Precision WorkStation 53... | Desktop     | [0969471740](https://linux-hardware.org/?probe=0969471740) | Mar 05, 2022 |
| Supermicro    | H8DGU                       | Server      | [0924057da7](https://linux-hardware.org/?probe=0924057da7) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [55d8863b7b](https://linux-hardware.org/?probe=55d8863b7b) | Mar 05, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [18b982d433](https://linux-hardware.org/?probe=18b982d433) | Mar 05, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [102ee4603a](https://linux-hardware.org/?probe=102ee4603a) | Mar 05, 2022 |
| System76      | Gazelle                     | Notebook    | [2fcfb8f348](https://linux-hardware.org/?probe=2fcfb8f348) | Mar 05, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2383184762](https://linux-hardware.org/?probe=2383184762) | Mar 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [277b94df81](https://linux-hardware.org/?probe=277b94df81) | Mar 05, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [0391ac1ba1](https://linux-hardware.org/?probe=0391ac1ba1) | Mar 05, 2022 |
| System76      | Kudu Professional           | Notebook    | [6dd5d90fae](https://linux-hardware.org/?probe=6dd5d90fae) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Dell          | Precision 3561              | Notebook    | [031274adf6](https://linux-hardware.org/?probe=031274adf6) | Mar 04, 2022 |
| Toshiba       | Satellite A660              | Notebook    | [1a6607437d](https://linux-hardware.org/?probe=1a6607437d) | Mar 04, 2022 |
| Gigabyte      | 2AC8                        | Desktop     | [af655fd169](https://linux-hardware.org/?probe=af655fd169) | Mar 04, 2022 |
| Toshiba       | Satellite A660              | Notebook    | [584c89737c](https://linux-hardware.org/?probe=584c89737c) | Mar 04, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [5097aa7911](https://linux-hardware.org/?probe=5097aa7911) | Mar 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [55ba5029ac](https://linux-hardware.org/?probe=55ba5029ac) | Mar 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [86dd550b46](https://linux-hardware.org/?probe=86dd550b46) | Mar 04, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1a54683c7c](https://linux-hardware.org/?probe=1a54683c7c) | Mar 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8e109e46c5](https://linux-hardware.org/?probe=8e109e46c5) | Mar 04, 2022 |
| Intel         | DH55TC AAE70932-301         | Desktop     | [2780250f97](https://linux-hardware.org/?probe=2780250f97) | Mar 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [a83c0a9cda](https://linux-hardware.org/?probe=a83c0a9cda) | Mar 04, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [7c9250a463](https://linux-hardware.org/?probe=7c9250a463) | Mar 04, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b56038968a](https://linux-hardware.org/?probe=b56038968a) | Mar 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [1c879cd60e](https://linux-hardware.org/?probe=1c879cd60e) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8e27cc62b4](https://linux-hardware.org/?probe=8e27cc62b4) | Mar 04, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [20b50225eb](https://linux-hardware.org/?probe=20b50225eb) | Mar 04, 2022 |
| HP            | 1850                        | Desktop     | [569e3e1c70](https://linux-hardware.org/?probe=569e3e1c70) | Mar 04, 2022 |
| Qualcomm T... | SDM845 v2.1 MTP PVT         | Soc         | [28143bf30e](https://linux-hardware.org/?probe=28143bf30e) | Mar 04, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [4ac263a1a4](https://linux-hardware.org/?probe=4ac263a1a4) | Mar 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [37be210ff8](https://linux-hardware.org/?probe=37be210ff8) | Mar 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [77188d21bf](https://linux-hardware.org/?probe=77188d21bf) | Mar 04, 2022 |
| Qualcomm T... | SDM845 v2.1 MTP PVT         | Soc         | [c2cd717e53](https://linux-hardware.org/?probe=c2cd717e53) | Mar 03, 2022 |
| Dell          | Latitude 7480               | Notebook    | [68996ba096](https://linux-hardware.org/?probe=68996ba096) | Mar 03, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [2b6fd5817c](https://linux-hardware.org/?probe=2b6fd5817c) | Mar 03, 2022 |
| Lenovo        | 3172 SDK0T08861 WIN 3305... | Mini pc     | [ee32355409](https://linux-hardware.org/?probe=ee32355409) | Mar 03, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [d42b913693](https://linux-hardware.org/?probe=d42b913693) | Mar 03, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [73b9b32509](https://linux-hardware.org/?probe=73b9b32509) | Mar 03, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [6acfc75347](https://linux-hardware.org/?probe=6acfc75347) | Mar 03, 2022 |
| Dell          | Precision 3561              | Notebook    | [42b439636a](https://linux-hardware.org/?probe=42b439636a) | Mar 03, 2022 |
| Dell          | Latitude 7480               | Notebook    | [4eb2f9a217](https://linux-hardware.org/?probe=4eb2f9a217) | Mar 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ee8029d2c8](https://linux-hardware.org/?probe=ee8029d2c8) | Mar 03, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [0f8e19d199](https://linux-hardware.org/?probe=0f8e19d199) | Mar 03, 2022 |
| HP            | ZBook 15                    | Notebook    | [e6360d2766](https://linux-hardware.org/?probe=e6360d2766) | Mar 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Ubuntu 20.04         | 4108      | 17.38%  |
| Ubuntu 18.04         | 2057      | 8.7%    |
| Debian 11            | 1137      | 4.81%   |
| Pop!_OS 21.04        | 581       | 2.46%   |
| Pop!_OS 20.04        | 567       | 2.4%    |
| Pop!_OS 20.10        | 532       | 2.25%   |
| Arch                 | 505       | 2.14%   |
| OpenMandriva 4.2     | 441       | 1.87%   |
| KDE neon 20.04       | 441       | 1.87%   |
| Ubuntu 20.10         | 437       | 1.85%   |
| Manjaro              | 397       | 1.68%   |
| Linux Mint 20.1      | 396       | 1.68%   |
| Ubuntu 19.10         | 379       | 1.6%    |
| Linux Mint 20.2      | 367       | 1.55%   |
| Ubuntu 21.10         | 359       | 1.52%   |
| Zorin 16             | 355       | 1.5%    |
| Linux Mint 19.3      | 329       | 1.39%   |
| Xubuntu 20.04        | 326       | 1.38%   |
| Zorin 15             | 324       | 1.37%   |
| Pop!_OS 21.10        | 321       | 1.36%   |
| Linux Mint 20        | 316       | 1.34%   |
| Ubuntu 21.04         | 310       | 1.31%   |
| Fedora 33            | 301       | 1.27%   |
| Ubuntu 19.04         | 300       | 1.27%   |
| Fedora 32            | 297       | 1.26%   |
| Fedora 34            | 293       | 1.24%   |
| Arch Rolling         | 290       | 1.23%   |
| Fedora 35            | 289       | 1.22%   |
| Linux Mint 20.3      | 264       | 1.12%   |
| Debian 10            | 247       | 1.04%   |
| OpenMandriva 4.3     | 243       | 1.03%   |
| Kubuntu 20.04        | 240       | 1.02%   |
| ArcoLinux Rolling    | 216       | 0.91%   |
| Fedora 31            | 187       | 0.79%   |
| Ubuntu 16.04         | 176       | 0.74%   |
| Linux Mint 19.1      | 135       | 0.57%   |
| Linux Mint 19.2      | 131       | 0.55%   |
| Ubuntu 18.10         | 128       | 0.54%   |
| BlackPanther 18.1    | 126       | 0.53%   |
| Xubuntu 18.04        | 117       | 0.49%   |
| Gentoo 2.7           | 97        | 0.41%   |
| Endless 3.7.8        | 90        | 0.38%   |
| Ubuntu 22.04         | 87        | 0.37%   |
| EndeavourOS Rolling  | 87        | 0.37%   |
| CentOS 7             | 79        | 0.33%   |
| OpenMandriva 4.50    | 76        | 0.32%   |
| Ubuntu MATE 20.04    | 74        | 0.31%   |
| Gentoo 2.6           | 72        | 0.3%    |
| KDE neon 18.04       | 66        | 0.28%   |
| Fedora 30            | 66        | 0.28%   |
| CentOS 8             | 66        | 0.28%   |
| Peppermint 10        | 65        | 0.27%   |
| Lubuntu 20.04        | 60        | 0.25%   |
| Debian Testing       | 60        | 0.25%   |
| Zorin 12             | 56        | 0.24%   |
| Manjaro 20.1         | 55        | 0.23%   |
| ROSA R10             | 53        | 0.22%   |
| LMDE 4               | 50        | 0.21%   |
| Garuda Linux Soaring | 46        | 0.19%   |
| Kubuntu 20.10        | 45        | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 8047      | 35.63%  |
| Pop!_OS       | 1939      | 8.58%   |
| Linux Mint    | 1863      | 8.25%   |
| Debian        | 1501      | 6.65%   |
| Fedora        | 1381      | 6.11%   |
| Manjaro       | 816       | 3.61%   |
| Arch          | 793       | 3.51%   |
| OpenMandriva  | 758       | 3.36%   |
| Zorin         | 730       | 3.23%   |
| Xubuntu       | 531       | 2.35%   |
| KDE neon      | 506       | 2.24%   |
| Kubuntu       | 432       | 1.91%   |
| Endless       | 262       | 1.16%   |
| ArcoLinux     | 247       | 1.09%   |
| openSUSE      | 214       | 0.95%   |
| Kali          | 199       | 0.88%   |
| Gentoo        | 190       | 0.84%   |
| Clear Linux   | 176       | 0.78%   |
| ROSA          | 170       | 0.75%   |
| CentOS        | 149       | 0.66%   |
| Ubuntu MATE   | 137       | 0.61%   |
| BlackPanther  | 129       | 0.57%   |
| Elementary    | 124       | 0.55%   |
| Lubuntu       | 117       | 0.52%   |
| EndeavourOS   | 112       | 0.5%    |
| Ubuntu Budgie | 85        | 0.38%   |
| Parrot        | 81        | 0.36%   |
| Peppermint    | 76        | 0.34%   |
| Garuda Linux  | 73        | 0.32%   |
| MX            | 72        | 0.32%   |
| LMDE          | 63        | 0.28%   |
| RHEL          | 50        | 0.22%   |
| Raspbian      | 37        | 0.16%   |
| LinuxFX       | 34        | 0.15%   |
| Reborn OS     | 31        | 0.14%   |
| Solus         | 27        | 0.12%   |
| Slackware     | 25        | 0.11%   |
| Manjaro-ARM   | 25        | 0.11%   |
| Artix         | 23        | 0.1%    |
| SkiffOS       | 22        | 0.1%    |
| Void Linux    | 21        | 0.09%   |
| Alpine        | 19        | 0.08%   |
| Android       | 16        | 0.07%   |
| Xero          | 13        | 0.06%   |
| Rocky Linux   | 13        | 0.06%   |
| Oracle Linux  | 13        | 0.06%   |
| Mageia        | 12        | 0.05%   |
| GalliumOS     | 11        | 0.05%   |
| Deepin        | 11        | 0.05%   |
| Chrome OS     | 11        | 0.05%   |
| PureOS        | 9         | 0.04%   |
| Makulu        | 9         | 0.04%   |
| Sparky        | 8         | 0.04%   |
| antergos      | 8         | 0.04%   |
| SteamOS       | 7         | 0.03%   |
| GNOME OS      | 7         | 0.03%   |
| Devuan        | 7         | 0.03%   |
| BunsenLabs    | 7         | 0.03%   |
| antiX         | 7         | 0.03%   |
| Ubuntu Studio | 6         | 0.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 627       | 2.38%   |
| 5.10.0-8-amd64           | 490       | 1.86%   |
| 5.10.0-10-amd64          | 424       | 1.61%   |
| 5.10.14-desktop-1omv4002 | 422       | 1.6%    |
| 5.4.0-58-generic         | 310       | 1.18%   |
| 5.11.0-7620-generic      | 285       | 1.08%   |
| 5.4.0-48-generic         | 257       | 0.97%   |
| 5.4.0-52-generic         | 248       | 0.94%   |
| 5.4.0-29-generic         | 247       | 0.94%   |
| 5.4.0-26-generic         | 245       | 0.93%   |
| 5.16.7-desktop-1omv4003  | 241       | 0.91%   |
| 5.3.0-28-generic         | 226       | 0.86%   |
| 5.8.0-7630-generic       | 223       | 0.85%   |
| 5.4.0-40-generic         | 216       | 0.82%   |
| 5.4.0-7634-generic       | 189       | 0.72%   |
| 5.3.0-40-generic         | 185       | 0.7%    |
| 5.11.0-38-generic        | 183       | 0.69%   |
| 5.4.0-54-generic         | 181       | 0.69%   |
| 5.4.0-37-generic         | 181       | 0.69%   |
| 5.8.0-43-generic         | 179       | 0.68%   |
| 5.3.0-46-generic         | 178       | 0.67%   |
| 5.13.0-39-generic        | 170       | 0.64%   |
| 5.11.0-37-generic        | 169       | 0.64%   |
| 5.4.0-65-generic         | 165       | 0.63%   |
| 5.11.0-27-generic        | 164       | 0.62%   |
| 5.11.0-40-generic        | 161       | 0.61%   |
| 5.0.0-37-generic         | 161       | 0.61%   |
| 5.4.0-47-generic         | 159       | 0.6%    |
| 5.8.0-7642-generic       | 156       | 0.59%   |
| 5.13.0-30-generic        | 156       | 0.59%   |
| 5.4.0-91-generic         | 148       | 0.56%   |
| 5.11.0-7614-generic      | 144       | 0.55%   |
| 5.13.0-7614-generic      | 141       | 0.53%   |
| 5.13.0-28-generic        | 141       | 0.53%   |
| 5.8.0-44-generic         | 135       | 0.51%   |
| 5.4.0-31-generic         | 135       | 0.51%   |
| 5.11.0-43-generic        | 135       | 0.51%   |
| 5.8.0-50-generic         | 132       | 0.5%    |
| 5.4.0-7642-generic       | 130       | 0.49%   |
| 5.13.0-7620-generic      | 130       | 0.49%   |
| 5.4.0-56-generic         | 129       | 0.49%   |
| 5.4.0-74-generic         | 128       | 0.49%   |
| 5.4.0-66-generic         | 124       | 0.47%   |
| 5.4.0-33-generic         | 124       | 0.47%   |
| 5.11.0-41-generic        | 123       | 0.47%   |
| 5.11.0-25-generic        | 122       | 0.46%   |
| 5.13.0-35-generic        | 119       | 0.45%   |
| 5.8.0-59-generic         | 118       | 0.45%   |
| 5.3.0-42-generic         | 117       | 0.44%   |
| 5.8.0-48-generic         | 114       | 0.43%   |
| 5.4.0-73-generic         | 111       | 0.42%   |
| 5.4.0-72-generic         | 109       | 0.41%   |
| 5.13.0-27-generic        | 109       | 0.41%   |
| 5.11.0-34-generic        | 108       | 0.41%   |
| 5.0.0-32-generic         | 105       | 0.4%    |
| 5.4.0-70-generic         | 102       | 0.39%   |
| 5.8.0-53-generic         | 97        | 0.37%   |
| 5.3.0-51-generic         | 96        | 0.36%   |
| 5.8.0-63-generic         | 93        | 0.35%   |
| 5.0.0-23-generic         | 93        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 5372      | 21.99%  |
| 5.8.0   | 2036      | 8.34%   |
| 5.11.0  | 2005      | 8.21%   |
| 4.15.0  | 1481      | 6.06%   |
| 5.13.0  | 1406      | 5.76%   |
| 5.3.0   | 1336      | 5.47%   |
| 5.10.0  | 1275      | 5.22%   |
| 5.0.0   | 802       | 3.28%   |
| 4.18.0  | 592       | 2.42%   |
| 5.10.14 | 433       | 1.77%   |
| 4.19.0  | 262       | 1.07%   |
| 5.16.7  | 248       | 1.02%   |
| 5.15.0  | 154       | 0.63%   |
| 5.16.11 | 115       | 0.47%   |
| 4.18.16 | 103       | 0.42%   |
| 5.14.0  | 102       | 0.42%   |
| 3.10.0  | 97        | 0.4%    |
| 5.9.16  | 92        | 0.38%   |
| 5.15.15 | 91        | 0.37%   |
| 5.15.5  | 89        | 0.36%   |
| 4.4.0   | 89        | 0.36%   |
| 5.6.0   | 77        | 0.32%   |
| 5.12.4  | 75        | 0.31%   |
| 5.7.0   | 73        | 0.3%    |
| 5.16.15 | 67        | 0.27%   |
| 5.13.19 | 67        | 0.27%   |
| 5.15.8  | 66        | 0.27%   |
| 5.16.19 | 60        | 0.25%   |
| 5.15.11 | 60        | 0.25%   |
| 5.6.14  | 59        | 0.24%   |
| 5.17.1  | 58        | 0.24%   |
| 5.9.0   | 57        | 0.23%   |
| 5.3.18  | 56        | 0.23%   |
| 5.15.12 | 56        | 0.23%   |
| 5.8.11  | 53        | 0.22%   |
| 5.13.13 | 53        | 0.22%   |
| 5.15.7  | 49        | 0.2%    |
| 5.8.6   | 48        | 0.2%    |
| 5.16.0  | 48        | 0.2%    |
| 5.9.14  | 46        | 0.19%   |
| 5.9.11  | 45        | 0.18%   |
| 5.8.5   | 45        | 0.18%   |
| 5.16.18 | 43        | 0.18%   |
| 5.15.6  | 43        | 0.18%   |
| 5.13.12 | 42        | 0.17%   |
| 5.11.12 | 42        | 0.17%   |
| 4.9.60  | 42        | 0.17%   |
| 5.11.11 | 41        | 0.17%   |
| 4.12.14 | 41        | 0.17%   |
| 5.8.14  | 39        | 0.16%   |
| 5.14.10 | 39        | 0.16%   |
| 5.9.10  | 38        | 0.16%   |
| 5.9.1   | 38        | 0.16%   |
| 5.8.4   | 38        | 0.16%   |
| 5.8.18  | 38        | 0.16%   |
| 5.12.13 | 38        | 0.16%   |
| 5.8.15  | 37        | 0.15%   |
| 5.8.16  | 36        | 0.15%   |
| 5.6.15  | 36        | 0.15%   |
| 5.16.14 | 35        | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 5770      | 23.96%  |
| 5.8     | 2535      | 10.53%  |
| 5.11    | 2305      | 9.57%   |
| 5.10    | 2271      | 9.43%   |
| 5.13    | 1701      | 7.06%   |
| 5.3     | 1507      | 6.26%   |
| 4.15    | 1488      | 6.18%   |
| 5.0     | 856       | 3.55%   |
| 5.15    | 855       | 3.55%   |
| 5.16    | 779       | 3.23%   |
| 4.18    | 710       | 2.95%   |
| 5.9     | 433       | 1.8%    |
| 5.6     | 385       | 1.6%    |
| 5.14    | 382       | 1.59%   |
| 4.19    | 362       | 1.5%    |
| 5.12    | 338       | 1.4%    |
| 5.7     | 309       | 1.28%   |
| 5.5     | 181       | 0.75%   |
| 4.9     | 172       | 0.71%   |
| 5.17    | 167       | 0.69%   |
| 4.4     | 105       | 0.44%   |
| 3.10    | 99        | 0.41%   |
| 5.2     | 84        | 0.35%   |
| 5.1     | 55        | 0.23%   |
| 4.12    | 42        | 0.17%   |
| 4.14    | 28        | 0.12%   |
| 4.1     | 28        | 0.12%   |
| 4.16    | 27        | 0.11%   |
| 4.13    | 17        | 0.07%   |
| 4.10    | 17        | 0.07%   |
| 4.20    | 16        | 0.07%   |
| 4.8     | 9         | 0.04%   |
| 4.17    | 8         | 0.03%   |
| 5.18    | 5         | 0.02%   |
| 4.7     | 5         | 0.02%   |
| 3.13    | 4         | 0.02%   |
| 2.6     | 4         | 0.02%   |
| 4.6     | 3         | 0.01%   |
| 4.3     | 3         | 0.01%   |
| 3.18    | 3         | 0.01%   |
| 3.16    | 3         | 0.01%   |
| 4.11    | 2         | 0.01%   |
| 3.4     | 2         | 0.01%   |
| Unknown | 2         | 0.01%   |
| 5.15.6  | 1         | 0.004%  |
| 5.14.12 | 1         | 0.004%  |
| 5       | 1         | 0.004%  |
| 4.5     | 1         | 0.004%  |
| 3.14    | 1         | 0.004%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 21051     | 96.34%  |
| i686    | 432       | 1.98%   |
| aarch64 | 287       | 1.31%   |
| armv7l  | 63        | 0.29%   |
| armv8l  | 10        | 0.05%   |
| armv6l  | 3         | 0.01%   |
| ppc64le | 2         | 0.01%   |
| ppc64   | 1         | 0.005%  |
| ppc     | 1         | 0.005%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 10447     | 45.8%   |
| Unknown                  | 4097      | 17.96%  |
| KDE5                     | 2420      | 10.61%  |
| XFCE                     | 1524      | 6.68%   |
| X-Cinnamon               | 1409      | 6.18%   |
| KDE                      | 903       | 3.96%   |
| MATE                     | 535       | 2.35%   |
| Cinnamon                 | 269       | 1.18%   |
| Unity                    | 147       | 0.64%   |
| LXQt                     | 139       | 0.61%   |
| Budgie                   | 137       | 0.6%    |
| LXDE                     | 122       | 0.53%   |
| i3                       | 109       | 0.48%   |
| Pantheon                 | 107       | 0.47%   |
| KDE4                     | 98        | 0.43%   |
| GNOME Flashback          | 74        | 0.32%   |
| Deepin                   | 58        | 0.25%   |
| awesome                  | 29        | 0.13%   |
| openbox                  | 27        | 0.12%   |
| GNOME Classic            | 26        | 0.11%   |
| Enlightenment            | 16        | 0.07%   |
| bspwm                    | 14        | 0.06%   |
| xmonad                   | 13        | 0.06%   |
| DWM                      | 11        | 0.05%   |
| sway                     | 10        | 0.04%   |
| Trinity                  | 9         | 0.04%   |
| lightdm-xsession         | 9         | 0.04%   |
| qtile                    | 8         | 0.04%   |
| ICEWM                    | 6         | 0.03%   |
| LeftWM                   | 4         | 0.02%   |
| GNUstep                  | 3         | 0.01%   |
| fluxbox                  | 3         | 0.01%   |
| xubuntu                  | 2         | 0.01%   |
| Xsession                 | 2         | 0.01%   |
| i3-with-shmlog           | 2         | 0.01%   |
| herbstluftwm             | 2         | 0.01%   |
| fvwm                     | 2         | 0.01%   |
| default                  | 2         | 0.01%   |
| Yaru:ubuntu:GNOME        | 1         | 0.004%  |
| xwmconfig                | 1         | 0.004%  |
| Xpra                     | 1         | 0.004%  |
| Wayfire                  | 1         | 0.004%  |
| qtile-default            | 1         | 0.004%  |
| plasma5                  | 1         | 0.004%  |
| Phosh:GNOME              | 1         | 0.004%  |
| pearl:GNOME              | 1         | 0.004%  |
| none+xmonad              | 1         | 0.004%  |
| none+i3                  | 1         | 0.004%  |
| matchbox                 | 1         | 0.004%  |
| Lumina                   | 1         | 0.004%  |
| jwm                      | 1         | 0.004%  |
| fvwm2                    | 1         | 0.004%  |
| cwm                      | 1         | 0.004%  |
| Core                     | 1         | 0.004%  |
| /usr/bin/openbox-session | 1         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 17415     | 77.96%  |
| Unknown | 2464      | 11.03%  |
| Wayland | 2016      | 9.03%   |
| Tty     | 438       | 1.96%   |
| Web     | 4         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 14507     | 64.44%  |
| GDM     | 2398      | 10.65%  |
| SDDM    | 2136      | 9.49%   |
| LightDM | 1327      | 5.89%   |
| GDM3    | 1074      | 4.77%   |
| TDM     | 845       | 3.75%   |
| KDM     | 98        | 0.44%   |
| XDM     | 57        | 0.25%   |
| LXDM    | 25        | 0.11%   |
| SLiM    | 24        | 0.11%   |
| MDM     | 9         | 0.04%   |
| Ly      | 6         | 0.03%   |
| NODM    | 4         | 0.02%   |
| GREETD  | 2         | 0.01%   |
| LDM     | 1         | 0.004%  |
| EMPTTY  | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang              | Computers | Percent |
|-------------------|-----------|---------|
| en_US             | 17655     | 79.61%  |
| Unknown           | 3610      | 16.28%  |
| C                 | 505       | 2.28%   |
| en_CA             | 116       | 0.52%   |
| en_GB             | 62        | 0.28%   |
| POSIX             | 25        | 0.11%   |
| zh_CN             | 24        | 0.11%   |
| es_US             | 18        | 0.08%   |
| C.UTF8            | 17        | 0.08%   |
| en_AU             | 14        | 0.06%   |
| en_IN             | 11        | 0.05%   |
| es_MX             | 9         | 0.04%   |
| ru_RU             | 8         | 0.04%   |
| de_DE             | 8         | 0.04%   |
| fr_FR             | 7         | 0.03%   |
| es_VE             | 5         | 0.02%   |
| es_ES             | 5         | 0.02%   |
| en_US.UTF8        | 5         | 0.02%   |
| unm_US            | 4         | 0.02%   |
| pl_PL             | 4         | 0.02%   |
| ko_KR             | 4         | 0.02%   |
| ja_JP             | 4         | 0.02%   |
| zh_TW             | 3         | 0.01%   |
| pt_BR             | 3         | 0.01%   |
| en-US             | 3         | 0.01%   |
| uk_UA             | 2         | 0.01%   |
| sv_SE             | 2         | 0.01%   |
| ru_UA             | 2         | 0.01%   |
| fr_CA             | 2         | 0.01%   |
| es_SV             | 2         | 0.01%   |
| es_CR             | 2         | 0.01%   |
| es_CO             | 2         | 0.01%   |
| es_AR             | 2         | 0.01%   |
| eo_US             | 2         | 0.01%   |
| eo                | 2         | 0.01%   |
| en_ZA             | 2         | 0.01%   |
| en_US.UTf-8       | 2         | 0.01%   |
| en_IE             | 2         | 0.01%   |
| en_001            | 2         | 0.01%   |
| tr_TR             | 1         | 0.005%  |
| osa_US            | 1         | 0.005%  |
| nl_NL             | 1         | 0.005%  |
| it_IT             | 1         | 0.005%  |
| he_IL             | 1         | 0.005%  |
| fr_CH             | 1         | 0.005%  |
| es_PR             | 1         | 0.005%  |
| es_CU             | 1         | 0.005%  |
| es_CL             | 1         | 0.005%  |
| en_XX@POSIX       | 1         | 0.005%  |
| en_US.ISO-8859-15 | 1         | 0.005%  |
| en_PH             | 1         | 0.005%  |
| en_IL             | 1         | 0.005%  |
| en_HK             | 1         | 0.005%  |
| en_BW             | 1         | 0.005%  |
| Default           | 1         | 0.005%  |
| da_DK             | 1         | 0.005%  |
| cinnamon.desktop  | 1         | 0.005%  |
| ca_ES             | 1         | 0.005%  |
| aa_DJ             | 1         | 0.005%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 11675     | 52.18%  |
| EFI  | 10698     | 47.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 17014     | 76.46%  |
| Overlay             | 2028      | 9.11%   |
| Btrfs               | 1465      | 6.58%   |
| Unknown             | 881       | 3.96%   |
| Xfs                 | 420       | 1.89%   |
| Zfs                 | 237       | 1.07%   |
| Ext2                | 68        | 0.31%   |
| Ext3                | 42        | 0.19%   |
| Tmpfs               | 36        | 0.16%   |
| F2fs                | 21        | 0.09%   |
| Reiserfs            | 13        | 0.06%   |
| Jfs                 | 7         | 0.03%   |
| Aufs                | 7         | 0.03%   |
| Fuse.fuse-overlayfs | 3         | 0.01%   |
| XXX                 | 2         | 0.01%   |
| Ubifs               | 2         | 0.01%   |
| Rootfs              | 2         | 0.01%   |
| XXXXX               | 1         | 0.004%  |
| XXXX                | 1         | 0.004%  |
| XXXfs               | 1         | 0.004%  |
| Xtrfs               | 1         | 0.004%  |
| SquasXfs            | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 14218     | 64.09%  |
| GPT     | 6261      | 28.22%  |
| MBR     | 1705      | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 19191     | 86.44%  |
| Yes       | 3010      | 13.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 17129     | 77.19%  |
| Yes       | 5062      | 22.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 4186      | 19.17%  |
| Hewlett-Packard                | 3292      | 15.08%  |
| ASUSTek Computer               | 2717      | 12.44%  |
| Lenovo                         | 2678      | 12.26%  |
| Apple                          | 1256      | 5.75%   |
| Gigabyte Technology            | 1240      | 5.68%   |
| MSI                            | 1200      | 5.5%    |
| ASRock                         | 816       | 3.74%   |
| Acer                           | 591       | 2.71%   |
| Toshiba                        | 461       | 2.11%   |
| Intel                          | 339       | 1.55%   |
| Google                         | 240       | 1.1%    |
| Raspberry Pi Foundation        | 212       | 0.97%   |
| System76                       | 211       | 0.97%   |
| Unknown                        | 173       | 0.79%   |
| Supermicro                     | 172       | 0.79%   |
| Pegatron                       | 166       | 0.76%   |
| Alienware                      | 154       | 0.71%   |
| Gateway                        | 139       | 0.64%   |
| Microsoft                      | 134       | 0.61%   |
| Foxconn                        | 118       | 0.54%   |
| Sony                           | 109       | 0.5%    |
| Samsung Electronics            | 100       | 0.46%   |
| Biostar                        | 59        | 0.27%   |
| ECS                            | 53        | 0.24%   |
| Razer                          | 49        | 0.22%   |
| Notebook                       | 46        | 0.21%   |
| eMachines                      | 46        | 0.21%   |
| Panasonic                      | 43        | 0.2%    |
| Framework                      | 42        | 0.19%   |
| Fujitsu                        | 35        | 0.16%   |
| EVGA                           | 35        | 0.16%   |
| AMI                            | 32        | 0.15%   |
| Pine Microsystems              | 29        | 0.13%   |
| GPU Company                    | 28        | 0.13%   |
| Nvidia                         | 25        | 0.11%   |
| ZOTAC                          | 22        | 0.1%    |
| HUAWEI                         | 22        | 0.1%    |
| Hardkernel                     | 19        | 0.09%   |
| LG Electronics                 | 18        | 0.08%   |
| Chuwi                          | 17        | 0.08%   |
| Shuttle                        | 16        | 0.07%   |
| AZW                            | 16        | 0.07%   |
| ASRockRack                     | 14        | 0.06%   |
| IBM                            | 13        | 0.06%   |
| Eluktronics                    | 13        | 0.06%   |
| TYAN Computer                  | 12        | 0.05%   |
| MOTILE                         | 12        | 0.05%   |
| AAEON                          | 12        | 0.05%   |
| Purism                         | 11        | 0.05%   |
| EVOO                           | 11        | 0.05%   |
| BESSTAR Tech                   | 11        | 0.05%   |
| Compulab                       | 10        | 0.05%   |
| AWOW                           | 10        | 0.05%   |
| Quanta                         | 9         | 0.04%   |
| Matsushita Electric Industrial | 8         | 0.04%   |
| Valve                          | 7         | 0.03%   |
| Minix                          | 7         | 0.03%   |
| Inventec                       | 7         | 0.03%   |
| GPD                            | 7         | 0.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 313       | 1.43%   |
| Unknown                                   | 204       | 0.93%   |
| ASUS All Series                           | 165       | 0.76%   |
| RPi Raspberry Pi                          | 126       | 0.58%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 110       | 0.5%    |
| Dell OptiPlex 7010                        | 109       | 0.5%    |
| ASUS TUF GAMING X570-PLUS                 | 95        | 0.44%   |
| Apple MacBookAir7,2                       | 93        | 0.43%   |
| HP Notebook                               | 90        | 0.41%   |
| Apple MacBookAir7,1                       | 85        | 0.39%   |
| Dell OptiPlex 9020                        | 82        | 0.38%   |
| Google Enguarde                           | 78        | 0.36%   |
| HP Pavilion dv7                           | 69        | 0.32%   |
| Dell Latitude E6420                       | 66        | 0.3%    |
| MSI MS-7C02                               | 58        | 0.27%   |
| Apple MacBook2,1                          | 58        | 0.27%   |
| HP 2000                                   | 55        | 0.25%   |
| Gigabyte B450M DS3H                       | 55        | 0.25%   |
| Dell OptiPlex 790                         | 55        | 0.25%   |
| MSI MS-7C37                               | 53        | 0.24%   |
| Dell Latitude E6430                       | 52        | 0.24%   |
| Dell OptiPlex 990                         | 48        | 0.22%   |
| MSI MS-7693                               | 47        | 0.22%   |
| HP Pavilion dv6                           | 46        | 0.21%   |
| Dell OptiPlex 3020                        | 45        | 0.21%   |
| HP Pavilion Notebook                      | 44        | 0.2%    |
| Dell OptiPlex 780                         | 43        | 0.2%    |
| ASRock B450M Pro4                         | 43        | 0.2%    |
| MSI MS-7B79                               | 42        | 0.19%   |
| Framework Laptop                          | 42        | 0.19%   |
| Dell Latitude E6410                       | 42        | 0.19%   |
| Dell OptiPlex 390                         | 41        | 0.19%   |
| HP 15 Notebook PC                         | 40        | 0.18%   |
| Dell OptiPlex 3010                        | 40        | 0.18%   |
| Dell Inspiron 3847                        | 40        | 0.18%   |
| Supermicro Super Server                   | 39        | 0.18%   |
| ASUS ROG STRIX B450-F GAMING              | 39        | 0.18%   |
| System76 Oryx Pro                         | 38        | 0.17%   |
| Dell XPS 13 9370                          | 38        | 0.17%   |
| Dell XPS 15 7590                          | 35        | 0.16%   |
| Dell OptiPlex 9010                        | 35        | 0.16%   |
| Gigabyte B450 AORUS M                     | 34        | 0.16%   |
| Dell XPS 13 9300                          | 34        | 0.16%   |
| HP Pavilion g7                            | 32        | 0.15%   |
| Dell XPS 15 9560                          | 32        | 0.15%   |
| Dell XPS 15 9500                          | 32        | 0.15%   |
| Dell Latitude E6400                       | 32        | 0.15%   |
| Dell Latitude D630                        | 32        | 0.15%   |
| Apple MacBookPro8,1                       | 32        | 0.15%   |
| Apple MacBook4,1                          | 32        | 0.15%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 31        | 0.14%   |
| MSI MS-7A34                               | 31        | 0.14%   |
| HP 15                                     | 31        | 0.14%   |
| Dell Inspiron 1545                        | 31        | 0.14%   |
| HP Compaq Elite 8300 SFF                  | 30        | 0.14%   |
| ASUS ROG STRIX B550-F GAMING              | 30        | 0.14%   |
| ASUS M5A97 R2.0                           | 30        | 0.14%   |
| HP Laptop 15-db0xxx                       | 29        | 0.13%   |
| Dell OptiPlex 760                         | 29        | 0.13%   |
| Dell Latitude E6510                       | 29        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 1413      | 6.47%   |
| Dell Inspiron          | 1123      | 5.14%   |
| Dell Latitude          | 851       | 3.9%    |
| Dell OptiPlex          | 783       | 3.59%   |
| HP Pavilion            | 602       | 2.76%   |
| Dell XPS               | 541       | 2.48%   |
| Lenovo IdeaPad         | 474       | 2.17%   |
| Dell Precision         | 434       | 1.99%   |
| Toshiba Satellite      | 426       | 1.95%   |
| ASUS ROG               | 401       | 1.84%   |
| Acer Aspire            | 399       | 1.83%   |
| HP Laptop              | 339       | 1.55%   |
| HP Compaq              | 337       | 1.54%   |
| Apple MacBook5         | 322       | 1.47%   |
| HP EliteBook           | 306       | 1.4%    |
| ASUS PRIME             | 271       | 1.24%   |
| HP ENVY                | 240       | 1.1%    |
| ASUS TUF               | 224       | 1.03%   |
| RPi Raspberry          | 212       | 0.97%   |
| Unknown                | 204       | 0.93%   |
| Lenovo ThinkCentre     | 198       | 0.91%   |
| Apple MacBookAir7      | 178       | 0.82%   |
| HP ProBook             | 169       | 0.77%   |
| ASUS All               | 165       | 0.76%   |
| Lenovo Yoga            | 142       | 0.65%   |
| Microsoft Surface      | 134       | 0.61%   |
| Dell PowerEdge         | 114       | 0.52%   |
| Gigabyte X570          | 113       | 0.52%   |
| Dell Studio            | 92        | 0.42%   |
| HP Notebook            | 90        | 0.41%   |
| Dell Vostro            | 86        | 0.39%   |
| ASUS VivoBook          | 85        | 0.39%   |
| HP EliteDesk           | 82        | 0.38%   |
| HP Stream              | 81        | 0.37%   |
| Gigabyte B450          | 80        | 0.37%   |
| Google Enguarde        | 78        | 0.36%   |
| HP 15                  | 77        | 0.35%   |
| HP ZBook               | 75        | 0.34%   |
| HP OMEN                | 75        | 0.34%   |
| HP Spectre             | 73        | 0.33%   |
| Gigabyte B450M         | 73        | 0.33%   |
| ASRock X570            | 71        | 0.33%   |
| Lenovo Legion          | 69        | 0.32%   |
| ASRock B450M           | 69        | 0.32%   |
| Gigabyte GA-78LMT-USB3 | 64        | 0.29%   |
| Apple MacBookPro8      | 63        | 0.29%   |
| ASUS M5A97             | 62        | 0.28%   |
| ASUS M5A78L-M          | 59        | 0.27%   |
| MSI MS-7C02            | 58        | 0.27%   |
| Apple MacBook2         | 58        | 0.27%   |
| Lenovo IdeaCentre      | 55        | 0.25%   |
| HP 2000                | 55        | 0.25%   |
| ASUS SABERTOOTH        | 55        | 0.25%   |
| MSI MS-7C37            | 53        | 0.24%   |
| Razer Blade            | 48        | 0.22%   |
| Apple MacBookPro11     | 48        | 0.22%   |
| MSI MS-7693            | 47        | 0.22%   |
| Gigabyte Z390          | 45        | 0.21%   |
| Acer Nitro             | 45        | 0.21%   |
| HP ProDesk             | 43        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 2239      | 10.25%  |
| 2019    | 2200      | 10.08%  |
| 2020    | 2017      | 9.24%   |
| 2012    | 1717      | 7.86%   |
| 2011    | 1673      | 7.66%   |
| 2013    | 1493      | 6.84%   |
| 2017    | 1385      | 6.34%   |
| 2014    | 1277      | 5.85%   |
| 2015    | 1257      | 5.76%   |
| 2016    | 1251      | 5.73%   |
| 2009    | 1201      | 5.5%    |
| 2010    | 1072      | 4.91%   |
| 2021    | 926       | 4.24%   |
| 2008    | 868       | 3.98%   |
| 2007    | 549       | 2.51%   |
| Unknown | 331       | 1.52%   |
| 2006    | 182       | 0.83%   |
| 2005    | 84        | 0.38%   |
| 2022    | 58        | 0.27%   |
| 2004    | 28        | 0.13%   |
| 2003    | 22        | 0.1%    |
| 2002    | 5         | 0.02%   |
| 2000    | 1         | 0.005%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 10610     | 48.59%  |
| Desktop        | 8864      | 40.59%  |
| Convertible    | 818       | 3.75%   |
| All in one     | 361       | 1.65%   |
| Mini pc        | 319       | 1.46%   |
| System on chip | 317       | 1.45%   |
| Server         | 315       | 1.44%   |
| Tablet         | 202       | 0.93%   |
| Phone          | 27        | 0.12%   |
| Stick pc       | 3         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 20429     | 92.85%  |
| Enabled  | 1574      | 7.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21482     | 98.38%  |
| Yes  | 354       | 1.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 4828      | 21.75%  |
| 4.01-8.0        | 4297      | 19.35%  |
| 3.01-4.0        | 3829      | 17.25%  |
| 8.01-16.0       | 3779      | 17.02%  |
| 32.01-64.0      | 2549      | 11.48%  |
| 1.01-2.0        | 1058      | 4.77%   |
| 64.01-256.0     | 934       | 4.21%   |
| 24.01-32.0      | 390       | 1.76%   |
| 2.01-3.0        | 304       | 1.37%   |
| 0.51-1.0        | 137       | 0.62%   |
| More than 256.0 | 63        | 0.28%   |
| 0.01-0.5        | 20        | 0.09%   |
| Unknown         | 13        | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 9519      | 39.08%  |
| 2.01-3.0        | 5762      | 23.66%  |
| 4.01-8.0        | 3248      | 13.34%  |
| 3.01-4.0        | 2826      | 11.6%   |
| 0.51-1.0        | 1491      | 6.12%   |
| 8.01-16.0       | 905       | 3.72%   |
| 0.01-0.5        | 260       | 1.07%   |
| 16.01-24.0      | 173       | 0.71%   |
| 24.01-32.0      | 73        | 0.3%    |
| 32.01-64.0      | 50        | 0.21%   |
| Unknown         | 24        | 0.1%    |
| 64.01-256.0     | 23        | 0.09%   |
| More than 256.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 13227     | 58.33%  |
| 2       | 5339      | 23.55%  |
| 3       | 1817      | 8.01%   |
| 4       | 894       | 3.94%   |
| 5       | 498       | 2.2%    |
| 0       | 300       | 1.32%   |
| 6       | 223       | 0.98%   |
| 7       | 140       | 0.62%   |
| 8       | 60        | 0.26%   |
| Unknown | 39        | 0.17%   |
| 9       | 34        | 0.15%   |
| 11      | 21        | 0.09%   |
| 13      | 15        | 0.07%   |
| 10      | 15        | 0.07%   |
| 12      | 10        | 0.04%   |
| 14      | 8         | 0.04%   |
| 16      | 5         | 0.02%   |
| 15      | 4         | 0.02%   |
| 20      | 3         | 0.01%   |
| 19      | 3         | 0.01%   |
| 97      | 2         | 0.01%   |
| 93      | 2         | 0.01%   |
| 36      | 2         | 0.01%   |
| 25      | 2         | 0.01%   |
| 17      | 2         | 0.01%   |
| 71      | 1         | 0.004%  |
| 68      | 1         | 0.004%  |
| 45      | 1         | 0.004%  |
| 30      | 1         | 0.004%  |
| 28      | 1         | 0.004%  |
| 27      | 1         | 0.004%  |
| 24      | 1         | 0.004%  |
| 23      | 1         | 0.004%  |
| 21      | 1         | 0.004%  |
| 18      | 1         | 0.004%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 12208     | 55.36%  |
| Yes       | 9843      | 44.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18621     | 85.06%  |
| No        | 3270      | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16923     | 76.91%  |
| No        | 5080      | 23.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12676     | 57.37%  |
| No        | 9418      | 42.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 21836     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Bangor           | 543       | 2.36%   |
| Portland         | 475       | 2.07%   |
| Chicago          | 319       | 1.39%   |
| New York         | 269       | 1.17%   |
| Los Angeles      | 247       | 1.07%   |
| Denver           | 238       | 1.04%   |
| Dallas           | 225       | 0.98%   |
| Seattle          | 218       | 0.95%   |
| Houston          | 213       | 0.93%   |
| Phoenix          | 177       | 0.77%   |
| Miami            | 169       | 0.74%   |
| Atlanta          | 165       | 0.72%   |
| Austin           | 164       | 0.71%   |
| San Jose         | 146       | 0.64%   |
| Brooklyn         | 139       | 0.6%    |
| Minneapolis      | 128       | 0.56%   |
| San Antonio      | 118       | 0.51%   |
| Las Vegas        | 118       | 0.51%   |
| San Francisco    | 116       | 0.5%    |
| San Diego        | 115       | 0.5%    |
| Orlando          | 101       | 0.44%   |
| Washington       | 100       | 0.44%   |
| Tucson           | 98        | 0.43%   |
| Rochester        | 90        | 0.39%   |
| Salt Lake City   | 86        | 0.37%   |
| Saint Paul       | 84        | 0.37%   |
| Pittsburgh       | 84        | 0.37%   |
| Springfield      | 83        | 0.36%   |
| Queens           | 82        | 0.36%   |
| Arlington        | 82        | 0.36%   |
| Albuquerque      | 78        | 0.34%   |
| Kansas City      | 76        | 0.33%   |
| Columbus         | 75        | 0.33%   |
| St Louis         | 74        | 0.32%   |
| Madison          | 74        | 0.32%   |
| Tampa            | 71        | 0.31%   |
| Raleigh          | 71        | 0.31%   |
| Rockville        | 70        | 0.3%    |
| Jacksonville     | 70        | 0.3%    |
| Mesa             | 67        | 0.29%   |
| Colorado Springs | 67        | 0.29%   |
| Spokane          | 65        | 0.28%   |
| Ashburn          | 65        | 0.28%   |
| Indianapolis     | 64        | 0.28%   |
| Richmond         | 62        | 0.27%   |
| Cleveland        | 61        | 0.27%   |
| Charlotte        | 60        | 0.26%   |
| Philadelphia     | 59        | 0.26%   |
| Lexington        | 59        | 0.26%   |
| Fort Worth       | 59        | 0.26%   |
| Buffalo          | 59        | 0.26%   |
| Oakland          | 57        | 0.25%   |
| Cincinnati       | 57        | 0.25%   |
| Sacramento       | 54        | 0.23%   |
| Eugene           | 52        | 0.23%   |
| Louisville       | 50        | 0.22%   |
| Alexandria       | 50        | 0.22%   |
| Omaha            | 49        | 0.21%   |
| Dover-Foxcroft   | 49        | 0.21%   |
| Oklahoma City    | 47        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 5125      | 8631   | 16.09%  |
| Seagate                   | 4982      | 8522   | 15.64%  |
| Samsung Electronics       | 4823      | 7638   | 15.14%  |
| Toshiba                   | 2144      | 2871   | 6.73%   |
| Unknown                   | 1775      | 2406   | 5.57%   |
| SanDisk                   | 1648      | 2153   | 5.17%   |
| Hitachi                   | 1251      | 1765   | 3.93%   |
| Crucial                   | 1017      | 1456   | 3.19%   |
| Intel                     | 877       | 1328   | 2.75%   |
| Kingston                  | 721       | 939    | 2.26%   |
| SK Hynix                  | 706       | 886    | 2.22%   |
| HGST                      | 696       | 1283   | 2.18%   |
| PNY                       | 484       | 635    | 1.52%   |
| Apple                     | 475       | 580    | 1.49%   |
| Phison                    | 474       | 702    | 1.49%   |
| A-DATA Technology         | 385       | 520    | 1.21%   |
| Fujitsu                   | 359       | 381    | 1.13%   |
| Micron Technology         | 311       | 386    | 0.98%   |
| SPCC                      | 289       | 369    | 0.91%   |
| China                     | 251       | 347    | 0.79%   |
| SABRENT                   | 143       | 174    | 0.45%   |
| LITEON                    | 142       | 164    | 0.45%   |
| Silicon Motion            | 140       | 203    | 0.44%   |
| OCZ                       | 135       | 168    | 0.42%   |
| Hewlett-Packard           | 131       | 228    | 0.41%   |
| Team                      | 122       | 159    | 0.38%   |
| Micron/Crucial Technology | 114       | 152    | 0.36%   |
| KIOXIA                    | 111       | 143    | 0.35%   |
| LITEONIT                  | 110       | 134    | 0.35%   |
| ASMT                      | 101       | 146    | 0.32%   |
| Mushkin                   | 98        | 152    | 0.31%   |
| JMicron                   | 89        | 109    | 0.28%   |
| Patriot                   | 81        | 112    | 0.25%   |
| Corsair                   | 75        | 113    | 0.24%   |
| MAXTOR                    | 72        | 92     | 0.23%   |
| Transcend                 | 70        | 99     | 0.22%   |
| XPG                       | 53        | 79     | 0.17%   |
| Phison Electronics        | 49        | 60     | 0.15%   |
| Unknown                   | 41        | 46     | 0.13%   |
| dogfish                   | 36        | 43     | 0.11%   |
| OWC                       | 35        | 40     | 0.11%   |
| PLEXTOR                   | 33        | 50     | 0.1%    |
| Realtek Semiconductor     | 32        | 43     | 0.1%    |
| KingSpec                  | 30        | 41     | 0.09%   |
| KingFast                  | 30        | 36     | 0.09%   |
| Lite-On                   | 26        | 30     | 0.08%   |
| Lenovo                    | 26        | 29     | 0.08%   |
| BIWIN                     | 25        | 29     | 0.08%   |
| BHT                       | 24        | 26     | 0.08%   |
| TO Exter                  | 21        | 32     | 0.07%   |
| WD MediaMax               | 20        | 36     | 0.06%   |
| Lexar                     | 20        | 20     | 0.06%   |
| External                  | 20        | 22     | 0.06%   |
| PNY USB                   | 19        | 27     | 0.06%   |
| T-FORCE                   | 18        | 21     | 0.06%   |
| Dell                      | 18        | 21     | 0.06%   |
| Zheino                    | 17        | 18     | 0.05%   |
| LaCie                     | 17        | 34     | 0.05%   |
| KingDian                  | 17        | 22     | 0.05%   |
| Super Talent              | 16        | 22     | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 337       | 0.94%   |
| Unknown MMC Card  32GB             | 317       | 0.88%   |
| Samsung SSD 860 EVO 1TB            | 313       | 0.87%   |
| Samsung NVMe SSD Drive 500GB       | 268       | 0.75%   |
| Unknown MMC Card  64GB             | 258       | 0.72%   |
| Samsung SSD 850 EVO 500GB          | 250       | 0.7%    |
| Samsung NVMe SSD Drive 1TB         | 249       | 0.69%   |
| Seagate ST500DM002-1BD142 500GB    | 241       | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB           | 237       | 0.66%   |
| Samsung NVMe SSD Drive 512GB       | 215       | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB     | 211       | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB     | 209       | 0.58%   |
| Unknown SD/MMC/MS PRO 128GB        | 203       | 0.57%   |
| Fujitsu MHZ2160BH FFS G1 160GB     | 202       | 0.56%   |
| Samsung SSD 850 EVO 250GB          | 197       | 0.55%   |
| Unknown MMC Card  128GB            | 184       | 0.51%   |
| Toshiba MQ01ABD100 1TB             | 183       | 0.51%   |
| HGST HTS721010A9E630 1TB           | 174       | 0.49%   |
| Samsung NVMe SSD Drive 256GB       | 160       | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 154       | 0.43%   |
| Sandisk NVMe SSD Drive 1TB         | 150       | 0.42%   |
| Toshiba MQ01ABF050 500GB           | 149       | 0.42%   |
| Toshiba DT01ACA100 1TB             | 144       | 0.4%    |
| Crucial CT1000MX500SSD1 1TB        | 143       | 0.4%    |
| Sandisk NVMe SSD Drive 500GB       | 137       | 0.38%   |
| Kingston SA400S37240G 240GB SSD    | 133       | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB           | 130       | 0.36%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 127       | 0.35%   |
| Crucial CT500MX500SSD1 500GB       | 126       | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB     | 124       | 0.35%   |
| Intel NVMe SSD Drive 512GB         | 124       | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB     | 123       | 0.34%   |
| Seagate ST500LT012-1DG142 500GB    | 122       | 0.34%   |
| Unknown MMC Card  16GB             | 121       | 0.34%   |
| SABRENT Disk 250GB                 | 120       | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB       | 116       | 0.32%   |
| Kingston SA400S37120G 120GB SSD    | 115       | 0.32%   |
| Seagate ST31000528AS 1TB           | 113       | 0.32%   |
| Samsung SSD 860 EVO 250GB          | 112       | 0.31%   |
| PNY CS900 240GB SSD                | 108       | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 103       | 0.29%   |
| Seagate Expansion Desk 3TB         | 101       | 0.28%   |
| Sandisk NVMe SSD Drive 512GB       | 101       | 0.28%   |
| Toshiba MQ04ABF100 1TB             | 100       | 0.28%   |
| SK Hynix NVMe SSD Drive 256GB      | 99        | 0.28%   |
| Phison NVMe SSD Drive 1TB          | 96        | 0.27%   |
| Seagate ST2000DM001-1ER164 2TB     | 95        | 0.26%   |
| Intel NVMe SSD Drive 1024GB        | 94        | 0.26%   |
| WDC WDBNCE5000PNC 500GB SSD        | 93        | 0.26%   |
| Apple SSD SM0128G 121GB            | 92        | 0.26%   |
| Seagate ST1000DM010-2EP102 1TB     | 91        | 0.25%   |
| PNY CS900 120GB SSD                | 91        | 0.25%   |
| Samsung NVMe SSD Drive 1024GB      | 90        | 0.25%   |
| Samsung SSD 970 EVO 500GB          | 89        | 0.25%   |
| Toshiba NVMe SSD Drive 256GB       | 88        | 0.25%   |
| Seagate ST2000DM006-2DM164 2TB     | 88        | 0.25%   |
| Sandisk NVMe SSD Drive 256GB       | 88        | 0.25%   |
| Seagate ST3500418AS 500GB          | 87        | 0.24%   |
| SK Hynix NVMe SSD Drive 512GB      | 86        | 0.24%   |
| SanDisk SDSSDA240G 240GB           | 86        | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 4833      | 8177    | 34.63%  |
| WDC                 | 4185      | 7185    | 29.98%  |
| Toshiba             | 1601      | 2169    | 11.47%  |
| Hitachi             | 1251      | 1765    | 8.96%   |
| HGST                | 693       | 1140    | 4.97%   |
| Fujitsu             | 359       | 381     | 2.57%   |
| Samsung Electronics | 240       | 303     | 1.72%   |
| Unknown             | 220       | 363     | 1.58%   |
| SABRENT             | 131       | 159     | 0.94%   |
| Apple               | 125       | 142     | 0.9%    |
| MAXTOR              | 71        | 91      | 0.51%   |
| ASMT                | 68        | 103     | 0.49%   |
| JMicron             | 30        | 45      | 0.21%   |
| Hewlett-Packard     | 25        | 65      | 0.18%   |
| Apricorn            | 11        | 13      | 0.08%   |
| WD MediaMax         | 9         | 17      | 0.06%   |
| IBM/Hitachi         | 8         | 10      | 0.06%   |
| USB                 | 7         | 10      | 0.05%   |
| MARVELL             | 6         | 10      | 0.04%   |
| ASMT109x            | 6         | 19      | 0.04%   |
| USB 3.0             | 4         | 8       | 0.03%   |
| LaCie               | 4         | 14      | 0.03%   |
| KESU                | 4         | 4       | 0.03%   |
| Inateck             | 4         | 9       | 0.03%   |
| HPE                 | 4         | 7       | 0.03%   |
| HGST HTS            | 4         | 4       | 0.03%   |
| Fantom              | 4         | 5       | 0.03%   |
| USB3.0              | 3         | 3       | 0.02%   |
| RSH-339             | 3         | 3       | 0.02%   |
| RSH-319             | 3         | 3       | 0.02%   |
| PHD 3.0             | 3         | 3       | 0.02%   |
| Maxone              | 3         | 3       | 0.02%   |
| MaxDigital          | 3         | 4       | 0.02%   |
| asmedia             | 3         | 5       | 0.02%   |
| SUN                 | 2         | 6       | 0.01%   |
| StoreJet            | 2         | 2       | 0.01%   |
| H/W                 | 2         | 2       | 0.01%   |
| DELLBOSS            | 2         | 2       | 0.01%   |
| Dell                | 2         | 2       | 0.01%   |
| DAS                 | 2         | 6       | 0.01%   |
| TrueNAS             | 1         | 1       | 0.01%   |
| SCST_FIO            | 1         | 9       | 0.01%   |
| QUANTUM             | 1         | 2       | 0.01%   |
| OEM                 | 1         | 1       | 0.01%   |
| Maxtor 6            | 1         | 1       | 0.01%   |
| Magnetic Data       | 1         | 2       | 0.01%   |
| Lenovo              | 1         | 2       | 0.01%   |
| Intenso             | 1         | 1       | 0.01%   |
| InnoDisk            | 1         | 1       | 0.01%   |
| IBM                 | 1         | 1       | 0.01%   |
| HGST HUS            | 1         | 1       | 0.01%   |
| Glyph               | 1         | 2       | 0.01%   |
| Emphase             | 1         | 2       | 0.01%   |
| ASMT106x            | 1         | 1       | 0.01%   |
| ACASIS              | 1         | 1       | 0.01%   |
| AAPL                | 1         | Unknown | 0.01%   |
| 3ware               | 1         | 4       | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2664      | 4036   | 26.62%  |
| SanDisk             | 1055      | 1378   | 10.54%  |
| Crucial             | 917       | 1322   | 9.16%   |
| WDC                 | 685       | 914    | 6.84%   |
| Kingston            | 628       | 823    | 6.27%   |
| PNY                 | 469       | 615    | 4.69%   |
| Intel               | 333       | 443    | 3.33%   |
| A-DATA Technology   | 326       | 435    | 3.26%   |
| SPCC                | 261       | 337    | 2.61%   |
| China               | 251       | 347    | 2.51%   |
| Apple               | 228       | 257    | 2.28%   |
| Micron Technology   | 206       | 251    | 2.06%   |
| SK Hynix            | 203       | 245    | 2.03%   |
| Toshiba             | 158       | 218    | 1.58%   |
| OCZ                 | 133       | 166    | 1.33%   |
| LITEON              | 129       | 151    | 1.29%   |
| Team                | 113       | 143    | 1.13%   |
| LITEONIT            | 110       | 134    | 1.1%    |
| Mushkin             | 88        | 142    | 0.88%   |
| Hewlett-Packard     | 82        | 123    | 0.82%   |
| Patriot             | 77        | 108    | 0.77%   |
| Transcend           | 67        | 92     | 0.67%   |
| Seagate             | 57        | 88     | 0.57%   |
| Corsair             | 55        | 72     | 0.55%   |
| Dogfish             | 36        | 43     | 0.36%   |
| OWC                 | 32        | 35     | 0.32%   |
| Unknown             | 30        | 34     | 0.3%    |
| PLEXTOR             | 30        | 47     | 0.3%    |
| KingSpec            | 28        | 38     | 0.28%   |
| ASMT                | 27        | 35     | 0.27%   |
| BHT                 | 24        | 26     | 0.24%   |
| TO Exter            | 21        | 32     | 0.21%   |
| JMicron             | 20        | 24     | 0.2%    |
| PNY USB             | 19        | 27     | 0.19%   |
| BIWIN               | 19        | 22     | 0.19%   |
| Lexar               | 18        | 18     | 0.18%   |
| External            | 18        | 20     | 0.18%   |
| KingFast            | 16        | 16     | 0.16%   |
| KingDian            | 16        | 21     | 0.16%   |
| FORESEE             | 15        | 20     | 0.15%   |
| Pioneer             | 14        | 21     | 0.14%   |
| MyDigitalSSD        | 14        | 22     | 0.14%   |
| Super Talent        | 13        | 17     | 0.13%   |
| Dell                | 13        | 15     | 0.13%   |
| Netac               | 10        | 11     | 0.1%    |
| DREVO               | 10        | 13     | 0.1%    |
| Apacer              | 10        | 17     | 0.1%    |
| Zheino              | 9         | 10     | 0.09%   |
| Mercury             | 8         | 9      | 0.08%   |
| Hoodisk             | 8         | 9      | 0.08%   |
| ASMedia             | 8         | 12     | 0.08%   |
| T-FORCE             | 7         | 8      | 0.07%   |
| Vaseky              | 6         | 7      | 0.06%   |
| USB3.0              | 6         | 6      | 0.06%   |
| TCSUNBOW            | 6         | 7      | 0.06%   |
| Unknown             | 6         | 8      | 0.06%   |
| Union Memory        | 5         | 7      | 0.05%   |
| INDMEM              | 5         | 6      | 0.05%   |
| EDGE                | 5         | 8      | 0.05%   |
| ADATA SU            | 5         | 5      | 0.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 11600     | 22294  | 41.18%  |
| SSD     | 8640      | 13728  | 30.67%  |
| NVMe    | 5901      | 9028   | 20.95%  |
| MMC     | 1487      | 1910   | 5.28%   |
| Unknown | 540       | 924    | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16718     | 33686  | 64.86%  |
| NVMe | 5898      | 9015   | 22.88%  |
| SAS  | 1674      | 3273   | 6.49%   |
| MMC  | 1487      | 1910   | 5.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives  | Percent |
|------------|-----------|---------|---------|
| 0.01-0.5   | 11870     | 18490   | 53.84%  |
| 0.51-1.0   | 6405      | 10021   | 29.05%  |
| 1.01-2.0   | 2009      | 3255    | 9.11%   |
| 3.01-4.0   | 662       | 1477    | 3%      |
| 4.01-10.0  | 518       | 1386    | 2.35%   |
| 2.01-3.0   | 494       | 1002    | 2.24%   |
| 10.01-20.0 | 88        | 391     | 0.4%    |
| 0          | 1         | Unknown | 0.005%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 5493      | 23.77%  |
| 251-500        | 4873      | 21.09%  |
| 501-1000       | 3844      | 16.64%  |
| 1001-2000      | 1866      | 8.08%   |
| More than 3000 | 1615      | 6.99%   |
| 1-20           | 1494      | 6.47%   |
| 51-100         | 1173      | 5.08%   |
| Unknown        | 1145      | 4.96%   |
| 21-50          | 839       | 3.63%   |
| 2001-3000      | 765       | 3.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9748      | 40.56%  |
| 21-50          | 3938      | 16.39%  |
| 101-250        | 2572      | 10.7%   |
| 51-100         | 2403      | 10%     |
| 251-500        | 1466      | 6.1%    |
| Unknown        | 1145      | 4.76%   |
| 501-1000       | 1136      | 4.73%   |
| 1001-2000      | 770       | 3.2%    |
| More than 3000 | 542       | 2.26%   |
| 2001-3000      | 303       | 1.26%   |
| 0              | 9         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB            | 28        | 29     | 1.9%    |
| Seagate ST500DM002-1BD142 500GB     | 24        | 28     | 1.63%   |
| Fujitsu MHZ2160BH FFS G1 160GB      | 20        | 20     | 1.36%   |
| Seagate ST31000528AS 1TB            | 16        | 18     | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 17     | 1.02%   |
| Toshiba MQ01ABD100 1TB              | 14        | 17     | 0.95%   |
| HGST HTS725050A7E630 500GB          | 13        | 13     | 0.88%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 14     | 0.82%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 13     | 0.75%   |
| Seagate ST31000524AS 1TB            | 11        | 12     | 0.75%   |
| Hitachi HDS721010CLA332 1TB         | 10        | 12     | 0.68%   |
| Toshiba MK1653GSX 160GB             | 9         | 9      | 0.61%   |
| Seagate ST31500341AS 1TB            | 9         | 12     | 0.61%   |
| HGST HTS541010A9E680 1TB            | 9         | 9      | 0.61%   |
| Toshiba MQ01ABF050 500GB            | 8         | 8      | 0.54%   |
| Toshiba MK1655GSXF 160GB            | 8         | 8      | 0.54%   |
| Seagate ST9750420AS 752GB           | 8         | 8      | 0.54%   |
| Seagate ST9500325AS 500GB           | 8         | 8      | 0.54%   |
| Seagate ST3500418AS 500GB           | 8         | 9      | 0.54%   |
| Seagate ST320LT007-9ZV142 320GB     | 8         | 8      | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 8      | 0.54%   |
| Hitachi HTS547575A9E384 752GB       | 8         | 8      | 0.54%   |
| Hitachi HTS542512K9SA00 120GB       | 8         | 9      | 0.54%   |
| HGST HTS545050A7E680 500GB          | 8         | 8      | 0.54%   |
| HGST HTS545050A7E380 500GB          | 8         | 8      | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB            | 7         | 8      | 0.48%   |
| Seagate ST9500420AS 500GB           | 7         | 7      | 0.48%   |
| Seagate ST2000DM001-9YN164 2TB      | 7         | 8      | 0.48%   |
| Seagate ST1000LX015-1U7172 1TB      | 7         | 7      | 0.48%   |
| Hitachi HTS545050B9A300 500GB       | 7         | 7      | 0.48%   |
| Crucial CT525MX300SSD1 528GB        | 7         | 8      | 0.48%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 6         | 7      | 0.41%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 6      | 0.41%   |
| Hitachi HTS543216L9SA02 160GB       | 6         | 6      | 0.41%   |
| WDC WD30EFRX-68EUZN0 3TB            | 5         | 6      | 0.34%   |
| WDC WD10EADS-65M2B1 1TB             | 5         | 8      | 0.34%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 5         | 7      | 0.34%   |
| Toshiba MQ04ABF100 1TB              | 5         | 5      | 0.34%   |
| Toshiba DT01ACA050 500GB            | 5         | 5      | 0.34%   |
| Seagate ST250DM000-1BD141 250GB     | 5         | 7      | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB      | 5         | 6      | 0.34%   |
| Seagate ST2000DL003-9VT166 2TB      | 5         | 5      | 0.34%   |
| Seagate ST1000DM003-1SB102 1TB      | 5         | 6      | 0.34%   |
| Hitachi HUA722020ALA331 2TB         | 5         | 5      | 0.34%   |
| Hitachi HTS725032A9A364 320GB       | 5         | 6      | 0.34%   |
| Hitachi HTS547564A9E384 640GB       | 5         | 5      | 0.34%   |
| Hitachi HTS543216L9A300 160GB       | 5         | 5      | 0.34%   |
| Hitachi HDS722020ALA330 2TB         | 5         | 6      | 0.34%   |
| Crucial CT240M500SSD1 240GB         | 5         | 5      | 0.34%   |
| WDC WD5000AAKX-753CA1 500GB         | 4         | 4      | 0.27%   |
| WDC WD20EARS-00MVWB0 2TB            | 4         | 4      | 0.27%   |
| WDC WD1600BUDT-63DPZY0 160GB        | 4         | 4      | 0.27%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 4         | 5      | 0.27%   |
| WDC WD10EADS-00L5B1 1TB             | 4         | 4      | 0.27%   |
| WDC WD1001FALS-00J7B0 1TB           | 4         | 4      | 0.27%   |
| Toshiba MK3275GSX 320GB             | 4         | 7      | 0.27%   |
| Toshiba DT01ACA100 1TB              | 4         | 5      | 0.27%   |
| Seagate ST9320423AS 320GB           | 4         | 4      | 0.27%   |
| Seagate ST9320325AS 320GB           | 4         | 4      | 0.27%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 4         | 4      | 0.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 353       | 419    | 24.74%  |
| WDC                 | 304       | 388    | 21.3%   |
| Hitachi             | 147       | 169    | 10.3%   |
| Toshiba             | 131       | 148    | 9.18%   |
| Samsung Electronics | 84        | 109    | 5.89%   |
| HGST                | 81        | 84     | 5.68%   |
| Intel               | 47        | 65     | 3.29%   |
| Crucial             | 38        | 51     | 2.66%   |
| Fujitsu             | 32        | 32     | 2.24%   |
| SanDisk             | 30        | 34     | 2.1%    |
| Kingston            | 30        | 38     | 2.1%    |
| SK Hynix            | 19        | 26     | 1.33%   |
| A-DATA Technology   | 14        | 16     | 0.98%   |
| Micron Technology   | 13        | 20     | 0.91%   |
| SPCC                | 10        | 10     | 0.7%    |
| Apple               | 10        | 11     | 0.7%    |
| MAXTOR              | 9         | 11     | 0.63%   |
| OCZ                 | 7         | 9      | 0.49%   |
| LITEON              | 7         | 8      | 0.49%   |
| ASMT                | 7         | 11     | 0.49%   |
| Corsair             | 6         | 7      | 0.42%   |
| Mushkin             | 5         | 5      | 0.35%   |
| LITEONIT            | 5         | 6      | 0.35%   |
| Hewlett-Packard     | 5         | 5      | 0.35%   |
| IBM/Hitachi         | 3         | 3      | 0.21%   |
| Transcend           | 2         | 3      | 0.14%   |
| SSSTC               | 2         | 2      | 0.14%   |
| PNY                 | 2         | 2      | 0.14%   |
| PLEXTOR             | 2         | 2      | 0.14%   |
| KingSpec            | 2         | 2      | 0.14%   |
| WD MediaMax         | 1         | 2      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |
| Team                | 1         | 2      | 0.07%   |
| SSD                 | 1         | 1      | 0.07%   |
| Silicon Motion      | 1         | 1      | 0.07%   |
| RSH-339             | 1         | 1      | 0.07%   |
| Phison              | 1         | 2      | 0.07%   |
| Patriot             | 1         | 1      | 0.07%   |
| OWC                 | 1         | 1      | 0.07%   |
| ORICO               | 1         | 1      | 0.07%   |
| Neo Forza           | 1         | 1      | 0.07%   |
| Lenovo              | 1         | 1      | 0.07%   |
| KingDian            | 1         | 1      | 0.07%   |
| JMicron             | 1         | 1      | 0.07%   |
| IBM                 | 1         | 1      | 0.07%   |
| Eluktro             | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 2      | 0.07%   |
| Apricorn            | 1         | 1      | 0.07%   |
| Apacer              | 1         | 1      | 0.07%   |
| 240G                | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 353       | 419    | 32.27%  |
| WDC                 | 301       | 383    | 27.51%  |
| Hitachi             | 147       | 169    | 13.44%  |
| Toshiba             | 124       | 140    | 11.33%  |
| HGST                | 81        | 84     | 7.4%    |
| Fujitsu             | 32        | 32     | 2.93%   |
| Samsung Electronics | 27        | 27     | 2.47%   |
| MAXTOR              | 9         | 11     | 0.82%   |
| Apple               | 6         | 7      | 0.55%   |
| ASMT                | 5         | 5      | 0.46%   |
| IBM/Hitachi         | 3         | 3      | 0.27%   |
| WD MediaMax         | 1         | 2      | 0.09%   |
| RSH-339             | 1         | 1      | 0.09%   |
| JMicron             | 1         | 1      | 0.09%   |
| IBM                 | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 1      | 0.09%   |
| Apricorn            | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1026      | 1287   | 75.55%  |
| SSD  | 279       | 349    | 20.54%  |
| NVMe | 53        | 84     | 3.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Crucial CT500P2SSD8 500GB         | 3         | 3      | 8.11%   |
| WDC WD5000LPVX-80V0TT0 500GB      | 2         | 2      | 5.41%   |
| Kingston SV300S37A120G 120GB SSD  | 2         | 2      | 5.41%   |
| HGST HTS541010A9E680 1TB          | 2         | 2      | 5.41%   |
| WDC WDS256G1X0C-00ENX0 256GB      | 1         | 1      | 2.7%    |
| WDC WD5000LPLX-75ZNTT0 500GB      | 1         | 1      | 2.7%    |
| WDC WD5000AVDS-63U7B1 500GB       | 1         | 1      | 2.7%    |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 2.7%    |
| WDC WD2500BEVT-60ZCT1 250GB       | 1         | 1      | 2.7%    |
| WDC WD2500BEVT-22A23T0 250GB      | 1         | 1      | 2.7%    |
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 2.7%    |
| WDC WD10JPVT-75A1YT0 1TB          | 1         | 1      | 2.7%    |
| WDC WD10EAVS-00D7B1 1TB           | 1         | 1      | 2.7%    |
| Toshiba THNSN5512GPU7 512GB       | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF032 320GB          | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 2.7%    |
| Toshiba MK6465GSX 640GB           | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 2.7%    |
| Seagate ST3500630AS 500GB         | 1         | 2      | 2.7%    |
| Seagate ST32000644NS 2TB          | 1         | 1      | 2.7%    |
| Seagate ST32000641AS 2TB          | 1         | 2      | 2.7%    |
| SanDisk SSD i100 24GB             | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 2.7%    |
| Samsung Electronics HD321HJ 320GB | 1         | 1      | 2.7%    |
| Samsung Electronics HD160JJ 160GB | 1         | 1      | 2.7%    |
| Patriot Pyro SSD 120GB            | 1         | 2      | 2.7%    |
| Hitachi HTS721010G9SA00 100GB     | 1         | 1      | 2.7%    |
| Hitachi HTS547575A9E384 752GB     | 1         | 2      | 2.7%    |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 2.7%    |
| HGST HUS724040ALA640 4TB          | 1         | 1      | 2.7%    |
| HGST HDN724040ALE640 4TB          | 1         | 1      | 2.7%    |
| Apple HDD HTS541010A9E662 1TB     | 1         | 1      | 2.7%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 29.73%  |
| Toshiba             | 4         | 4      | 10.81%  |
| Seagate             | 4         | 6      | 10.81%  |
| HGST                | 4         | 4      | 10.81%  |
| Samsung Electronics | 3         | 3      | 8.11%   |
| Hitachi             | 3         | 4      | 8.11%   |
| Crucial             | 3         | 3      | 8.11%   |
| Kingston            | 2         | 2      | 5.41%   |
| SanDisk             | 1         | 1      | 2.7%    |
| Patriot             | 1         | 2      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 14950     | 32701  | 64.48%  |
| Works    | 6864      | 13421  | 29.61%  |
| Malfunc  | 1333      | 1720   | 5.75%   |
| Failed   | 37        | 42     | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13331     | 49.38%  |
| AMD                              | 4936      | 18.28%  |
| Samsung Electronics              | 2536      | 9.39%   |
| Sandisk                          | 956       | 3.54%   |
| Nvidia                           | 789       | 2.92%   |
| ASMedia Technology               | 597       | 2.21%   |
| Phison Electronics               | 582       | 2.16%   |
| SK Hynix                         | 490       | 1.82%   |
| Toshiba America Info Systems     | 396       | 1.47%   |
| Marvell Technology Group         | 395       | 1.46%   |
| JMicron Technology               | 255       | 0.94%   |
| Micron/Crucial Technology        | 206       | 0.76%   |
| Silicon Motion                   | 193       | 0.71%   |
| LSI Logic / Symbios Logic        | 175       | 0.65%   |
| Broadcom / LSI                   | 147       | 0.54%   |
| Apple                            | 127       | 0.47%   |
| KIOXIA                           | 114       | 0.42%   |
| Micron Technology                | 113       | 0.42%   |
| ADATA Technology                 | 107       | 0.4%    |
| Kingston Technology Company      | 96        | 0.36%   |
| Realtek Semiconductor            | 55        | 0.2%    |
| Silicon Image                    | 43        | 0.16%   |
| Lite-On Technology               | 42        | 0.16%   |
| VIA Technologies                 | 41        | 0.15%   |
| Adaptec                          | 35        | 0.13%   |
| Seagate Technology               | 34        | 0.13%   |
| Hewlett-Packard                  | 34        | 0.13%   |
| Union Memory (Shenzhen)          | 30        | 0.11%   |
| Lenovo                           | 23        | 0.09%   |
| Solid State Storage Technology   | 22        | 0.08%   |
| Integrated Technology Express    | 11        | 0.04%   |
| Shenzhen Longsys Electronics     | 10        | 0.04%   |
| HighPoint Technologies           | 8         | 0.03%   |
| Unknown                          | 7         | 0.03%   |
| Silicon Integrated Systems [SiS] | 6         | 0.02%   |
| Biwin Storage Technology         | 6         | 0.02%   |
| Promise Technology               | 5         | 0.02%   |
| OCZ Technology Group             | 5         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.02%   |
| Dell                             | 5         | 0.02%   |
| 3ware                            | 5         | 0.02%   |
| ULi Electronics                  | 3         | 0.01%   |
| Broadcom                         | 3         | 0.01%   |
| ATTO Technology                  | 3         | 0.01%   |
| Yangtze Memory Technologies      | 2         | 0.01%   |
| Western Digital                  | 2         | 0.01%   |
| Toshiba                          | 2         | 0.01%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.01%   |
| Areca Technology                 | 2         | 0.01%   |
| ScaleFlux                        | 1         | 0.004%  |
| PMC-Sierra                       | 1         | 0.004%  |
| O2 Micro                         | 1         | 0.004%  |
| Unknown                          | 1         | 0.004%  |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 3305      | 10.4%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1516      | 4.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 943       | 2.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 902       | 2.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 882       | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 737       | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 724       | 2.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 695       | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 672       | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 587       | 1.85%   |
| Intel SATA Controller [RAID mode]                                                       | 571       | 1.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 550       | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 485       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 480       | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 428       | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 419       | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 405       | 1.27%   |
| Nvidia MCP79 AHCI Controller                                                            | 399       | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 386       | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 373       | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 360       | 1.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 358       | 1.13%   |
| Phison E12 NVMe Controller                                                              | 344       | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 340       | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 318       | 1%      |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 303       | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 292       | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 283       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 257       | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 247       | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 237       | 0.75%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 235       | 0.74%   |
| Samsung NVMe SSD Controller 980                                                         | 226       | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 223       | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 221       | 0.7%    |
| Intel SSD 660P Series                                                                   | 212       | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 203       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 202       | 0.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 201       | 0.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 193       | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                                  | 188       | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 182       | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 180       | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 168       | 0.53%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 166       | 0.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 160       | 0.5%    |
| Nvidia MCP61 SATA Controller                                                            | 156       | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 151       | 0.48%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 150       | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 150       | 0.47%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 144       | 0.45%   |
| Samsung Electronics SATA controller                                                     | 143       | 0.45%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 138       | 0.43%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 137       | 0.43%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 136       | 0.43%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 136       | 0.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 133       | 0.42%   |
| SK Hynix Gold P31 SSD                                                                   | 131       | 0.41%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 131       | 0.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 131       | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 15594     | 57.12%  |
| NVMe | 5990      | 21.94%  |
| IDE  | 3233      | 11.84%  |
| RAID | 2200      | 8.06%   |
| SAS  | 199       | 0.73%   |
| SCSI | 83        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 15915     | 72.88%  |
| AMD                      | 5552      | 25.43%  |
| ARM                      | 341       | 1.56%   |
| QUALCOMM                 | 16        | 0.07%   |
| Unknown                  | 7         | 0.03%   |
| PowerNV C1P9S01 REV 1.01 | 2         | 0.01%   |
| PowerMac8,1              | 1         | 0.005%  |
| PowerBook5,5             | 1         | 0.005%  |
| CentaurHauls             | 1         | 0.005%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 315       | 1.44%   |
| ARM Processor                                 | 266       | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 249       | 1.14%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 220       | 1.01%   |
| AMD Ryzen 5 3600 6-Core Processor             | 211       | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 190       | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 183       | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 178       | 0.81%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 165       | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 152       | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 152       | 0.69%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 152       | 0.69%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 148       | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 146       | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 144       | 0.66%   |
| AMD FX-8350 Eight-Core Processor              | 141       | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 136       | 0.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 133       | 0.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 129       | 0.59%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 128       | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 125       | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 123       | 0.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 119       | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 113       | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 112       | 0.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 111       | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 109       | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 108       | 0.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 108       | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 108       | 0.49%   |
| AMD FX-6300 Six-Core Processor                | 100       | 0.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 99        | 0.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 99        | 0.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 98        | 0.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 95        | 0.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 94        | 0.43%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 93        | 0.42%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 93        | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 91        | 0.42%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 89        | 0.41%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 88        | 0.4%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 86        | 0.39%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 86        | 0.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 84        | 0.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 84        | 0.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 83        | 0.38%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 79        | 0.36%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 79        | 0.36%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 78        | 0.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 77        | 0.35%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 75        | 0.34%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 75        | 0.34%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 74        | 0.34%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 74        | 0.34%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 73        | 0.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 73        | 0.33%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 72        | 0.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 72        | 0.33%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 71        | 0.32%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 71        | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 4657      | 21.29%  |
| Intel Core i5                  | 4412      | 20.17%  |
| Intel Core 2 Duo               | 1282      | 5.86%   |
| Intel Core i3                  | 1181      | 5.4%    |
| AMD Ryzen 5                    | 1057      | 4.83%   |
| Other                          | 1032      | 4.72%   |
| AMD Ryzen 7                    | 928       | 4.24%   |
| Intel Celeron                  | 890       | 4.07%   |
| Intel Xeon                     | 841       | 3.85%   |
| AMD FX                         | 541       | 2.47%   |
| Intel Pentium                  | 466       | 2.13%   |
| AMD Ryzen 9                    | 374       | 1.71%   |
| AMD A6                         | 275       | 1.26%   |
| Intel Atom                     | 262       | 1.2%    |
| AMD Ryzen 3                    | 251       | 1.15%   |
| Intel Core i9                  | 248       | 1.13%   |
| AMD A8                         | 214       | 0.98%   |
| AMD A10                        | 208       | 0.95%   |
| Intel Pentium Dual-Core        | 195       | 0.89%   |
| Intel Core 2 Quad              | 193       | 0.88%   |
| Intel Core 2                   | 163       | 0.75%   |
| AMD Phenom II X4               | 152       | 0.7%    |
| AMD Ryzen Threadripper         | 128       | 0.59%   |
| AMD A4                         | 118       | 0.54%   |
| AMD Athlon II X2               | 106       | 0.48%   |
| AMD Athlon 64 X2               | 102       | 0.47%   |
| AMD E                          | 92        | 0.42%   |
| AMD Athlon II X4               | 88        | 0.4%    |
| Intel Pentium Dual             | 84        | 0.38%   |
| Intel Pentium 4                | 84        | 0.38%   |
| AMD E2                         | 71        | 0.32%   |
| Intel Genuine                  | 68        | 0.31%   |
| AMD Phenom II X6               | 65        | 0.3%    |
| AMD Ryzen 7 PRO                | 59        | 0.27%   |
| ARM BCM                        | 55        | 0.25%   |
| AMD Athlon                     | 54        | 0.25%   |
| Intel Pentium Silver           | 53        | 0.24%   |
| AMD Phenom                     | 49        | 0.22%   |
| Intel Pentium D                | 48        | 0.22%   |
| AMD E1                         | 46        | 0.21%   |
| AMD Turion 64 X2 Mobile        | 43        | 0.2%    |
| AMD A12                        | 38        | 0.17%   |
| Intel Core m3                  | 36        | 0.16%   |
| AMD Sempron                    | 36        | 0.16%   |
| AMD Ryzen 5 PRO                | 26        | 0.12%   |
| AMD Athlon II                  | 26        | 0.12%   |
| AMD Opteron                    | 25        | 0.11%   |
| Intel Pentium M                | 24        | 0.11%   |
| AMD Phenom II X2               | 21        | 0.1%    |
| AMD Phenom II                  | 19        | 0.09%   |
| Intel Celeron M                | 17        | 0.08%   |
| AMD GX                         | 17        | 0.08%   |
| AMD Athlon X2                  | 17        | 0.08%   |
| AMD Turion X2 Dual-Core Mobile | 15        | 0.07%   |
| AMD Athlon II X3               | 15        | 0.07%   |
| AMD Athlon 64                  | 15        | 0.07%   |
| Intel Core 2 Extreme           | 14        | 0.06%   |
| AMD C-50                       | 14        | 0.06%   |
| AMD EPYC                       | 13        | 0.06%   |
| AMD Athlon X4                  | 13        | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8528      | 38.98%  |
| 4       | 7969      | 36.42%  |
| 6       | 2121      | 9.69%   |
| 8       | 1682      | 7.69%   |
| 1       | 529       | 2.42%   |
| 12      | 376       | 1.72%   |
| 16      | 212       | 0.97%   |
| 3       | 185       | 0.85%   |
| 10      | 79        | 0.36%   |
| 24      | 46        | 0.21%   |
| 32      | 44        | 0.2%    |
| 20      | 32        | 0.15%   |
| Unknown | 12        | 0.05%   |
| 64      | 11        | 0.05%   |
| 18      | 10        | 0.05%   |
| 28      | 9         | 0.04%   |
| 14      | 9         | 0.04%   |
| 40      | 7         | 0.03%   |
| 48      | 5         | 0.02%   |
| 5       | 4         | 0.02%   |
| 44      | 3         | 0.01%   |
| 22      | 2         | 0.01%   |
| 128     | 1         | 0.005%  |
| 96      | 1         | 0.005%  |
| 56      | 1         | 0.005%  |
| 52      | 1         | 0.005%  |
| 36      | 1         | 0.005%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 21358     | 97.79%  |
| 2       | 453       | 2.07%   |
| 4       | 15        | 0.07%   |
| Unknown | 10        | 0.05%   |
| 3       | 4         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 14026     | 64.12%  |
| 1       | 7830      | 35.8%   |
| Unknown | 12        | 0.05%   |
| 8       | 2         | 0.01%   |
| 4       | 2         | 0.01%   |
| 112     | 1         | 0.005%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20939     | 95.57%  |
| Unknown        | 748       | 3.41%   |
| 32-bit         | 188       | 0.86%   |
| 64-bit         | 34        | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5273      | 23.3%   |
| 0x206a7    | 1257      | 5.55%   |
| 0x306a9    | 1120      | 4.95%   |
| 0x1067a    | 1086      | 4.8%    |
| 0x306c3    | 995       | 4.4%    |
| 0x906ea    | 606       | 2.68%   |
| 0x306d4    | 487       | 2.15%   |
| 0x506e3    | 467       | 2.06%   |
| 0x806ea    | 464       | 2.05%   |
| 0x40651    | 406       | 1.79%   |
| 0x906e9    | 393       | 1.74%   |
| 0x406e3    | 393       | 1.74%   |
| 0x806e9    | 386       | 1.71%   |
| 0x806c1    | 380       | 1.68%   |
| 0x08701021 | 357       | 1.58%   |
| 0x806ec    | 355       | 1.57%   |
| 0x20655    | 299       | 1.32%   |
| 0x30678    | 292       | 1.29%   |
| 0x06000852 | 292       | 1.29%   |
| 0x0800820d | 249       | 1.1%    |
| 0x08701013 | 245       | 1.08%   |
| 0x010000c8 | 223       | 0.99%   |
| 0x06001119 | 211       | 0.93%   |
| 0x10676    | 208       | 0.92%   |
| 0x6fd      | 200       | 0.88%   |
| 0x406c4    | 191       | 0.84%   |
| 0xa0652    | 189       | 0.83%   |
| 0x906ed    | 179       | 0.79%   |
| 0x706e5    | 170       | 0.75%   |
| 0x08108109 | 158       | 0.7%    |
| 0x6fb      | 143       | 0.63%   |
| 0x08108102 | 140       | 0.62%   |
| 0x206c2    | 133       | 0.59%   |
| 0x20652    | 130       | 0.57%   |
| 0x6f6      | 128       | 0.57%   |
| 0x206d7    | 115       | 0.51%   |
| 0x106e5    | 115       | 0.51%   |
| 0x106a5    | 110       | 0.49%   |
| 0x05000119 | 110       | 0.49%   |
| 0x07030105 | 108       | 0.48%   |
| 0x06006705 | 101       | 0.45%   |
| 0x806eb    | 100       | 0.44%   |
| 0x706a1    | 100       | 0.44%   |
| 0xa0655    | 99        | 0.44%   |
| 0x306f2    | 98        | 0.43%   |
| 0x03000027 | 97        | 0.43%   |
| 0x0a50000c | 94        | 0.42%   |
| 0x0810100b | 93        | 0.41%   |
| 0x08001137 | 89        | 0.39%   |
| 0x406c3    | 88        | 0.39%   |
| 0x08001138 | 88        | 0.39%   |
| 0x0600063e | 83        | 0.37%   |
| 0x0700010f | 82        | 0.36%   |
| 0x08600106 | 80        | 0.35%   |
| 0x010000db | 79        | 0.35%   |
| 0x0a201009 | 78        | 0.34%   |
| 0x706a8    | 77        | 0.34%   |
| 0x506c9    | 77        | 0.34%   |
| 0x08600104 | 74        | 0.33%   |
| 0x306e4    | 73        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 3232      | 14.78%  |
| Haswell          | 1938      | 8.86%   |
| SandyBridge      | 1648      | 7.54%   |
| Penryn           | 1495      | 6.84%   |
| IvyBridge        | 1470      | 6.72%   |
| Skylake          | 1159      | 5.3%    |
| Zen 2            | 1132      | 5.18%   |
| Zen+             | 802       | 3.67%   |
| Silvermont       | 708       | 3.24%   |
| Piledriver       | 697       | 3.19%   |
| Westmere         | 666       | 3.05%   |
| Broadwell        | 663       | 3.03%   |
| K10              | 611       | 2.79%   |
| Core             | 610       | 2.79%   |
| CometLake        | 534       | 2.44%   |
| Zen              | 526       | 2.41%   |
| Unknown          | 517       | 2.36%   |
| TigerLake        | 472       | 2.16%   |
| Zen 3            | 354       | 1.62%   |
| Excavator        | 315       | 1.44%   |
| IceLake          | 298       | 1.36%   |
| Nehalem          | 284       | 1.3%    |
| K8 Hammer        | 223       | 1.02%   |
| Goldmont plus    | 215       | 0.98%   |
| Bobcat           | 173       | 0.79%   |
| Puma             | 158       | 0.72%   |
| NetBurst         | 152       | 0.7%    |
| Jaguar           | 120       | 0.55%   |
| Goldmont         | 117       | 0.54%   |
| K10 Llano        | 112       | 0.51%   |
| Bulldozer        | 108       | 0.49%   |
| Steamroller      | 105       | 0.48%   |
| Bonnell          | 91        | 0.42%   |
| P6               | 85        | 0.39%   |
| K8 & K10 hybrid  | 49        | 0.22%   |
| Alderlake Hybrid | 20        | 0.09%   |
| K6               | 5         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 11632     | 47.46%  |
| Nvidia                                       | 6888      | 28.1%   |
| AMD                                          | 5675      | 23.15%  |
| Matrox Electronics Systems                   | 160       | 0.65%   |
| ASPEED Technology                            | 125       | 0.51%   |
| ATI Technologies                             | 9         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 6         | 0.02%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.02%   |
| S3 Graphics                                  | 5         | 0.02%   |
| VIA Technologies                             | 3         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.004%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1169      | 4.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 747       | 2.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 598       | 2.36%   |
| Intel UHD Graphics 620                                                                   | 542       | 2.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 483       | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 481       | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 456       | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 442       | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 438       | 1.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 381       | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 375       | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 369       | 1.46%   |
| Intel HD Graphics 620                                                                    | 362       | 1.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 354       | 1.4%    |
| Intel HD Graphics 5500                                                                   | 352       | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 334       | 1.32%   |
| Intel HD Graphics 530                                                                    | 324       | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 318       | 1.26%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 315       | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 313       | 1.24%   |
| Intel HD Graphics 630                                                                    | 303       | 1.2%    |
| AMD Renoir                                                                               | 281       | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 258       | 1.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 240       | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 236       | 0.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 228       | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 222       | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 218       | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 194       | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 190       | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 190       | 0.75%   |
| Intel HD Graphics 6000                                                                   | 186       | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 180       | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 177       | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 162       | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 162       | 0.64%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 158       | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 153       | 0.6%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 150       | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 148       | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 143       | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 136       | 0.54%   |
| AMD Cezanne                                                                              | 135       | 0.53%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 125       | 0.49%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 124       | 0.49%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 121       | 0.48%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 117       | 0.46%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 117       | 0.46%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 115       | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 112       | 0.44%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 112       | 0.44%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 110       | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 108       | 0.43%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 108       | 0.43%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 107       | 0.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 105       | 0.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 101       | 0.4%    |
| Intel Iris Plus Graphics G7                                                              | 99        | 0.39%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 97        | 0.38%   |
| Nvidia GT218 [GeForce 210]                                                               | 93        | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 9077      | 41.22%  |
| 1 x AMD                                  | 4823      | 21.9%   |
| 1 x Nvidia                               | 4631      | 21.03%  |
| Intel + Nvidia                           | 1854      | 8.42%   |
| Other                                    | 372       | 1.69%   |
| Intel + AMD                              | 367       | 1.67%   |
| AMD + Nvidia                             | 240       | 1.09%   |
| 2 x AMD                                  | 213       | 0.97%   |
| 1 x Matrox                               | 126       | 0.57%   |
| 1 x ASPEED                               | 97        | 0.44%   |
| 2 x Nvidia                               | 91        | 0.41%   |
| Nvidia + Matrox                          | 21        | 0.1%    |
| Nvidia + ASPEED                          | 21        | 0.1%    |
| AMD + Matrox                             | 15        | 0.07%   |
| Intel + 2 x Nvidia                       | 10        | 0.05%   |
| 2 x Intel                                | 6         | 0.03%   |
| AMD + ASPEED                             | 6         | 0.03%   |
| 1 x XGI                                  | 5         | 0.02%   |
| 1 x SiS                                  | 5         | 0.02%   |
| Intel + AMD + 1 x Nvidia                 | 5         | 0.02%   |
| 2 x AMD + 1 x Nvidia                     | 4         | 0.02%   |
| 1 x S3 Graphics                          | 4         | 0.02%   |
| Intel + 2 x AMD                          | 4         | 0.02%   |
| 3 x Nvidia                               | 3         | 0.01%   |
| 1 x VIA                                  | 3         | 0.01%   |
| AMD + 2 x Nvidia                         | 3         | 0.01%   |
| 6 x Nvidia                               | 1         | 0.005%  |
| 4 x Nvidia                               | 1         | 0.005%  |
| 3 x AMD + 1 x Nvidia                     | 1         | 0.005%  |
| 3 x AMD                                  | 1         | 0.005%  |
| 2 x AMD + 2 x Nvidia + 1 x Matrox        | 1         | 0.005%  |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED        | 1         | 0.005%  |
| 2 x AMD + 1 x ASPEED                     | 1         | 0.005%  |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.005%  |
| Nvidia + XGI                             | 1         | 0.005%  |
| Intel + 5 x AMD + Nvidia                 | 1         | 0.005%  |
| 1 x Intel + 4 x Nvidia                   | 1         | 0.005%  |
| Intel + ASPEED                           | 1         | 0.005%  |
| Intel + AMD + 2 x Nvidia                 | 1         | 0.005%  |
| AMD + S3 Graphics                        | 1         | 0.005%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 17257     | 77.85%  |
| Proprietary | 3859      | 17.41%  |
| Unknown     | 1052      | 4.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12111     | 53.78%  |
| 0.01-0.5   | 2770      | 12.3%   |
| 1.01-2.0   | 2317      | 10.29%  |
| 0.51-1.0   | 1500      | 6.66%   |
| 3.01-4.0   | 1485      | 6.59%   |
| 7.01-8.0   | 1269      | 5.64%   |
| 5.01-6.0   | 590       | 2.62%   |
| 8.01-16.0  | 262       | 1.16%   |
| 2.01-3.0   | 181       | 0.8%    |
| 16.01-24.0 | 23        | 0.1%    |
| 4.01-5.0   | 6         | 0.03%   |
| 32.01-64.0 | 3         | 0.01%   |
| 24.01-32.0 | 1         | 0.004%  |
| 0          | 1         | 0.004%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2661      | 11.15%  |
| AU Optronics            | 2485      | 10.42%  |
| Dell                    | 2190      | 9.18%   |
| LG Display              | 1945      | 8.15%   |
| Chimei Innolux          | 1379      | 5.78%   |
| BOE                     | 1372      | 5.75%   |
| Hewlett-Packard         | 1305      | 5.47%   |
| Acer                    | 1233      | 5.17%   |
| Apple                   | 1139      | 4.77%   |
| Goldstar                | 877       | 3.68%   |
| Ancor Communications    | 768       | 3.22%   |
| Sharp                   | 604       | 2.53%   |
| ViewSonic               | 471       | 1.97%   |
| AOC                     | 407       | 1.71%   |
| Vizio                   | 390       | 1.63%   |
| Lenovo                  | 375       | 1.57%   |
| Chi Mei Optoelectronics | 319       | 1.34%   |
| Sceptre Tech            | 278       | 1.17%   |
| Unknown                 | 212       | 0.89%   |
| Sony                    | 201       | 0.84%   |
| ASUSTek Computer        | 199       | 0.83%   |
| BenQ                    | 189       | 0.79%   |
| LG Electronics          | 168       | 0.7%    |
| PANDA                   | 140       | 0.59%   |
| Insignia                | 137       | 0.57%   |
| InfoVision              | 122       | 0.51%   |
| LG Philips              | 109       | 0.46%   |
| HannStar                | 102       | 0.43%   |
| Panasonic               | 87        | 0.36%   |
| NEC Computers           | 86        | 0.36%   |
| Toshiba                 | 79        | 0.33%   |
| Philips                 | 75        | 0.31%   |
| Gateway                 | 69        | 0.29%   |
| MSI                     | 67        | 0.28%   |
| ONN                     | 65        | 0.27%   |
| Westinghouse            | 58        | 0.24%   |
| VIZ                     | 45        | 0.19%   |
| Element                 | 42        | 0.18%   |
| Sanyo                   | 37        | 0.16%   |
| Sceptre                 | 35        | 0.15%   |
| Planar                  | 33        | 0.14%   |
| RTK                     | 32        | 0.13%   |
| Pixio                   | 32        | 0.13%   |
| Hitachi                 | 32        | 0.13%   |
| Gigabyte Technology     | 31        | 0.13%   |
| Viotek                  | 29        | 0.12%   |
| Seiki                   | 28        | 0.12%   |
| LGD                     | 28        | 0.12%   |
| CPT                     | 28        | 0.12%   |
| eMachines               | 27        | 0.11%   |
| CSO                     | 27        | 0.11%   |
| HPN                     | 26        | 0.11%   |
| MStar                   | 25        | 0.1%    |
| Envision                | 25        | 0.1%    |
| Lenovo Group Limited    | 24        | 0.1%    |
| AUS                     | 24        | 0.1%    |
| InnoLux Display         | 23        | 0.1%    |
| Seiko/Epson             | 20        | 0.08%   |
| STD                     | 19        | 0.08%   |
| PRI                     | 16        | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                     | 205       | 0.82%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 168       | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 122       | 0.49%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 112       | 0.45%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch           | 107       | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 76        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 70        | 0.28%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 63        | 0.25%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 62        | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 59        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 58        | 0.23%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                      | 53        | 0.21%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 53        | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 52        | 0.21%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 51        | 0.2%    |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                     | 50        | 0.2%    |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                   | 49        | 0.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 49        | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 49        | 0.2%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 49        | 0.2%    |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 48        | 0.19%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 47        | 0.19%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 47        | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 47        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 47        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 46        | 0.18%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                        | 45        | 0.18%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 44        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 44        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 44        | 0.18%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 43        | 0.17%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 43        | 0.17%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 42        | 0.17%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 42        | 0.17%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 42        | 0.17%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch    | 42        | 0.17%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 39        | 0.16%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 39        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 39        | 0.16%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 39        | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 38        | 0.15%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 38        | 0.15%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                      | 36        | 0.14%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 36        | 0.14%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch             | 36        | 0.14%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                    | 36        | 0.14%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch    | 36        | 0.14%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 35        | 0.14%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 35        | 0.14%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch         | 35        | 0.14%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 34        | 0.14%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 34        | 0.14%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch              | 33        | 0.13%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 33        | 0.13%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                        | 32        | 0.13%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch              | 31        | 0.12%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 31        | 0.12%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 31        | 0.12%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 31        | 0.12%   |
| Toshiba TV TSB0206 1920x1080 700x390mm 31.5-inch                         | 30        | 0.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 9106      | 39.44%  |
| 1366x768 (WXGA)    | 3880      | 16.8%   |
| 3840x2160 (4K)     | 1614      | 6.99%   |
| 1600x900 (HD+)     | 1320      | 5.72%   |
| 2560x1440 (QHD)    | 961       | 4.16%   |
| 1280x800 (WXGA)    | 888       | 3.85%   |
| 1440x900 (WXGA+)   | 755       | 3.27%   |
| 1280x1024 (SXGA)   | 646       | 2.8%    |
| 1680x1050 (WSXGA+) | 613       | 2.65%   |
| 1920x1200 (WUXGA)  | 546       | 2.36%   |
| Unknown            | 436       | 1.89%   |
| 2560x1080          | 237       | 1.03%   |
| 3440x1440          | 232       | 1%      |
| 1360x768           | 217       | 0.94%   |
| 3840x1080          | 181       | 0.78%   |
| 1920x540           | 146       | 0.63%   |
| 2560x1600          | 126       | 0.55%   |
| 1024x768 (XGA)     | 117       | 0.51%   |
| 3200x1800 (QHD+)   | 77        | 0.33%   |
| 2880x1800          | 74        | 0.32%   |
| 3840x2400          | 72        | 0.31%   |
| 1024x600           | 65        | 0.28%   |
| 1600x1200          | 61        | 0.26%   |
| 2736x1824          | 52        | 0.23%   |
| 2256x1504          | 48        | 0.21%   |
| 1280x720 (HD)      | 34        | 0.15%   |
| 2160x1440          | 32        | 0.14%   |
| 3840x1600          | 26        | 0.11%   |
| 3840x1200          | 24        | 0.1%    |
| 3000x2000          | 23        | 0.1%    |
| 1920x1280          | 22        | 0.1%    |
| 5760x1080          | 21        | 0.09%   |
| 7680x2160          | 18        | 0.08%   |
| 4480x1440          | 18        | 0.08%   |
| 2048x1152          | 18        | 0.08%   |
| 3520x1080          | 17        | 0.07%   |
| 5760x2160          | 15        | 0.06%   |
| 2288x1287          | 14        | 0.06%   |
| 3600x1080          | 13        | 0.06%   |
| 1400x1050          | 13        | 0.06%   |
| 1280x960           | 13        | 0.06%   |
| 3072x1920          | 12        | 0.05%   |
| 5120x1440          | 10        | 0.04%   |
| 3200x1080          | 10        | 0.04%   |
| 2400x1600          | 9         | 0.04%   |
| 1800x1200          | 9         | 0.04%   |
| 1280x768           | 9         | 0.04%   |
| 800x1280           | 8         | 0.03%   |
| 2800x1752          | 8         | 0.03%   |
| 3286x1080          | 7         | 0.03%   |
| 1680x945           | 7         | 0.03%   |
| 6400x1440          | 6         | 0.03%   |
| 5120x1080          | 6         | 0.03%   |
| 2240x1400          | 6         | 0.03%   |
| 6400x2160          | 5         | 0.02%   |
| 5360x1440          | 5         | 0.02%   |
| 4480x1080          | 5         | 0.02%   |
| 3280x1080          | 5         | 0.02%   |
| 3200x900           | 5         | 0.02%   |
| 2160x1200          | 5         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4934      | 20.86%  |
| 13      | 2407      | 10.18%  |
| 27      | 1893      | 8%      |
| 24      | 1596      | 6.75%   |
| Unknown | 1550      | 6.55%   |
| 17      | 1465      | 6.2%    |
| 14      | 1429      | 6.04%   |
| 23      | 1393      | 5.89%   |
| 21      | 1046      | 4.42%   |
| 31      | 761       | 3.22%   |
| 19      | 711       | 3.01%   |
| 20      | 595       | 2.52%   |
| 11      | 500       | 2.11%   |
| 34      | 383       | 1.62%   |
| 12      | 381       | 1.61%   |
| 22      | 378       | 1.6%    |
| 18      | 317       | 1.34%   |
| 32      | 195       | 0.82%   |
| 72      | 158       | 0.67%   |
| 84      | 149       | 0.63%   |
| 26      | 112       | 0.47%   |
| 49      | 103       | 0.44%   |
| 54      | 100       | 0.42%   |
| 10      | 98        | 0.41%   |
| 25      | 97        | 0.41%   |
| 40      | 91        | 0.38%   |
| 29      | 63        | 0.27%   |
| 16      | 61        | 0.26%   |
| 48      | 60        | 0.25%   |
| 37      | 56        | 0.24%   |
| 42      | 49        | 0.21%   |
| 74      | 45        | 0.19%   |
| 28      | 44        | 0.19%   |
| 52      | 36        | 0.15%   |
| 46      | 36        | 0.15%   |
| 39      | 31        | 0.13%   |
| 38      | 30        | 0.13%   |
| 36      | 30        | 0.13%   |
| 47      | 28        | 0.12%   |
| 41      | 27        | 0.11%   |
| 35      | 22        | 0.09%   |
| 65      | 21        | 0.09%   |
| 43      | 18        | 0.08%   |
| 8       | 18        | 0.08%   |
| 44      | 16        | 0.07%   |
| 60      | 15        | 0.06%   |
| 57      | 15        | 0.06%   |
| 30      | 15        | 0.06%   |
| 69      | 12        | 0.05%   |
| 66      | 8         | 0.03%   |
| 64      | 8         | 0.03%   |
| 142     | 6         | 0.03%   |
| 55      | 6         | 0.03%   |
| 75      | 4         | 0.02%   |
| 7       | 4         | 0.02%   |
| 61      | 3         | 0.01%   |
| 59      | 3         | 0.01%   |
| 50      | 3         | 0.01%   |
| 33      | 3         | 0.01%   |
| 100     | 2         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7259      | 31.27%  |
| 501-600        | 4531      | 19.52%  |
| 401-500        | 2636      | 11.36%  |
| 201-300        | 2600      | 11.2%   |
| 351-400        | 1725      | 7.43%   |
| Unknown        | 1550      | 6.68%   |
| 601-700        | 1126      | 4.85%   |
| 701-800        | 610       | 2.63%   |
| 1001-1500      | 440       | 1.9%    |
| 1501-2000      | 369       | 1.59%   |
| 801-900        | 225       | 0.97%   |
| 901-1000       | 109       | 0.47%   |
| 101-200        | 23        | 0.1%    |
| More than 2000 | 8         | 0.03%   |
| 1-100          | 2         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 15422     | 71.47%  |
| 16/10   | 3094      | 14.34%  |
| Unknown | 1344      | 6.23%   |
| 5/4     | 586       | 2.72%   |
| 21/9    | 443       | 2.05%   |
| 3/2     | 235       | 1.09%   |
| 4/3     | 222       | 1.03%   |
| 32/9    | 97        | 0.45%   |
| 6/5     | 58        | 0.27%   |
| 1.96    | 29        | 0.13%   |
| 0.62    | 11        | 0.05%   |
| 1.00    | 8         | 0.04%   |
| 0.45    | 8         | 0.04%   |
| 2.65    | 5         | 0.02%   |
| 3.40    | 4         | 0.02%   |
| 3.20    | 4         | 0.02%   |
| 2.01    | 2         | 0.01%   |
| 2.00    | 2         | 0.01%   |
| 11/10   | 2         | 0.01%   |
| 1.98    | 1         | 0.005%  |
| 0.57    | 1         | 0.005%  |
| 0.56    | 1         | 0.005%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4921      | 21.01%  |
| 201-250        | 3390      | 14.48%  |
| 81-90          | 2829      | 12.08%  |
| 301-350        | 1952      | 8.34%   |
| 151-200        | 1743      | 7.44%   |
| Unknown        | 1550      | 6.62%   |
| 351-500        | 1377      | 5.88%   |
| 71-80          | 1017      | 4.34%   |
| 121-130        | 992       | 4.24%   |
| 251-300        | 705       | 3.01%   |
| More than 1000 | 683       | 2.92%   |
| 51-60          | 510       | 2.18%   |
| 501-1000       | 509       | 2.17%   |
| 141-150        | 502       | 2.14%   |
| 61-70          | 337       | 1.44%   |
| 131-140        | 176       | 0.75%   |
| 41-50          | 92        | 0.39%   |
| 111-120        | 56        | 0.24%   |
| 91-100         | 51        | 0.22%   |
| 1-40           | 25        | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 7673      | 33.86%  |
| 101-120       | 5731      | 25.29%  |
| 121-160       | 4926      | 21.74%  |
| Unknown       | 1550      | 6.84%   |
| 161-240       | 1288      | 5.68%   |
| 1-50          | 793       | 3.5%    |
| More than 240 | 701       | 3.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17648     | 78.86%  |
| 2     | 3241      | 14.48%  |
| 0     | 1017      | 4.54%   |
| 3     | 425       | 1.9%    |
| 4     | 41        | 0.18%   |
| 5     | 5         | 0.02%   |
| 6     | 3         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 11531     | 35.03%  |
| Realtek Semiconductor                 | 9965      | 30.27%  |
| Qualcomm Atheros                      | 3321      | 10.09%  |
| Broadcom                              | 2544      | 7.73%   |
| Nvidia                                | 715       | 2.17%   |
| Broadcom Limited                      | 679       | 2.06%   |
| Ralink Technology                     | 514       | 1.56%   |
| Marvell Technology Group              | 476       | 1.45%   |
| Ralink                                | 362       | 1.1%    |
| NetGear                               | 289       | 0.88%   |
| TP-Link                               | 223       | 0.68%   |
| ASIX Electronics                      | 178       | 0.54%   |
| Samsung Electronics                   | 161       | 0.49%   |
| MediaTek                              | 129       | 0.39%   |
| Linksys                               | 120       | 0.36%   |
| Microsoft                             | 103       | 0.31%   |
| DisplayLink                           | 94        | 0.29%   |
| Aquantia                              | 92        | 0.28%   |
| Belkin Components                     | 91        | 0.28%   |
| ASUSTek Computer                      | 90        | 0.27%   |
| Edimax Technology                     | 76        | 0.23%   |
| Qualcomm Atheros Communications       | 72        | 0.22%   |
| Motorola PCS                          | 62        | 0.19%   |
| Google                                | 59        | 0.18%   |
| Qualcomm                              | 57        | 0.17%   |
| D-Link System                         | 57        | 0.17%   |
| Lenovo                                | 56        | 0.17%   |
| Mellanox Technologies                 | 46        | 0.14%   |
| Microchip Technology                  | 44        | 0.13%   |
| Apple                                 | 38        | 0.12%   |
| Dell                                  | 35        | 0.11%   |
| InterBiometrics                       | 33        | 0.1%    |
| LG Electronics                        | 27        | 0.08%   |
| Arduino SA                            | 27        | 0.08%   |
| D-Link                                | 25        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 25        | 0.08%   |
| Sierra Wireless                       | 22        | 0.07%   |
| Hewlett-Packard                       | 19        | 0.06%   |
| Cypress Semiconductor                 | 17        | 0.05%   |
| 3Com                                  | 17        | 0.05%   |
| VIA Technologies                      | 14        | 0.04%   |
| Gemtek                                | 14        | 0.04%   |
| U-Blox                                | 13        | 0.04%   |
| AMD                                   | 13        | 0.04%   |
| T & A Mobile Phones                   | 12        | 0.04%   |
| Micro Star International              | 12        | 0.04%   |
| ADMtek                                | 12        | 0.04%   |
| ZyDAS                                 | 11        | 0.03%   |
| Sigma Designs                         | 11        | 0.03%   |
| JMicron Technology                    | 11        | 0.03%   |
| ZTE WCDMA Technologies MSM            | 10        | 0.03%   |
| Xiaomi                                | 10        | 0.03%   |
| Wilocity                              | 9         | 0.03%   |
| OnePlus Technology (Shenzhen)         | 8         | 0.02%   |
| Accton Technology                     | 8         | 0.02%   |
| Solarflare Communications             | 7         | 0.02%   |
| Input Club                            | 7         | 0.02%   |
| Exar                                  | 7         | 0.02%   |
| Ericsson Business Mobile Networks     | 7         | 0.02%   |
| Emulex                                | 7         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6371      | 16.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1442      | 3.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1194      | 3.04%   |
| Intel Wi-Fi 6 AX200                                               | 1143      | 2.91%   |
| Intel I211 Gigabit Network Connection                             | 834       | 2.13%   |
| Intel Wireless 7260                                               | 687       | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 590       | 1.5%    |
| Intel Wireless 7265                                               | 554       | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 527       | 1.34%   |
| Intel Ethernet Connection I217-LM                                 | 475       | 1.21%   |
| Intel Wireless 8260                                               | 462       | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 448       | 1.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 426       | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 421       | 1.07%   |
| Nvidia MCP79 Ethernet                                             | 404       | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 403       | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 394       | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 386       | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 381       | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 370       | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 368       | 0.94%   |
| Intel Wi-Fi 6 AX201                                               | 359       | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 354       | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 324       | 0.83%   |
| Intel Wireless-AC 9260                                            | 314       | 0.8%    |
| Intel Wireless 3165                                               | 292       | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 276       | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 244       | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 244       | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 239       | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 238       | 0.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 237       | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 233       | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 226       | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 225       | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 219       | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 195       | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 192       | 0.49%   |
| Intel 82577LM Gigabit Network Connection                          | 187       | 0.48%   |
| Intel Wireless 3160                                               | 186       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 185       | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 181       | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 181       | 0.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 181       | 0.46%   |
| Intel Centrino Ultimate-N 6300                                    | 180       | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 166       | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 161       | 0.41%   |
| Intel Ethernet Controller I225-V                                  | 161       | 0.41%   |
| Realtek 802.11ac NIC                                              | 160       | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 160       | 0.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 158       | 0.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 157       | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 157       | 0.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 156       | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 151       | 0.38%   |
| Intel Ethernet Connection I219-LM                                 | 151       | 0.38%   |
| Intel Ethernet Connection (2) I218-V                              | 149       | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 147       | 0.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 144       | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 139       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 8183      | 45.21%  |
| Realtek Semiconductor                 | 2692      | 14.87%  |
| Qualcomm Atheros                      | 2563      | 14.16%  |
| Broadcom                              | 1799      | 9.94%   |
| Ralink Technology                     | 514       | 2.84%   |
| Broadcom Limited                      | 506       | 2.8%    |
| Ralink                                | 362       | 2%      |
| NetGear                               | 283       | 1.56%   |
| TP-Link                               | 199       | 1.1%    |
| Linksys                               | 114       | 0.63%   |
| MediaTek                              | 105       | 0.58%   |
| Marvell Technology Group              | 105       | 0.58%   |
| ASUSTek Computer                      | 89        | 0.49%   |
| Belkin Components                     | 88        | 0.49%   |
| Microsoft                             | 80        | 0.44%   |
| Edimax Technology                     | 76        | 0.42%   |
| Qualcomm Atheros Communications       | 72        | 0.4%    |
| D-Link System                         | 36        | 0.2%    |
| Qualcomm                              | 30        | 0.17%   |
| Dell                                  | 30        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 25        | 0.14%   |
| D-Link                                | 24        | 0.13%   |
| Sierra Wireless                       | 22        | 0.12%   |
| Gemtek                                | 14        | 0.08%   |
| Micro Star International              | 12        | 0.07%   |
| ZyDAS                                 | 11        | 0.06%   |
| Wilocity                              | 9         | 0.05%   |
| TRENDnet                              | 5         | 0.03%   |
| BUFFALO                               | 5         | 0.03%   |
| Samsung Electronics                   | 4         | 0.02%   |
| Panasonic (Matsushita)                | 4         | 0.02%   |
| Hawking Technologies                  | 4         | 0.02%   |
| Accton Technology                     | 4         | 0.02%   |
| ZyXEL Communications                  | 3         | 0.02%   |
| Texas Instruments                     | 3         | 0.02%   |
| Tenda                                 | 3         | 0.02%   |
| Senao                                 | 3         | 0.02%   |
| Belkin                                | 3         | 0.02%   |
| Apple                                 | 3         | 0.02%   |
| Z-Com                                 | 1         | 0.01%   |
| Xiaomi                                | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| Thales Norway A/S                     | 1         | 0.01%   |
| Realtek                               | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| Hewlett-Packard                       | 1         | 0.01%   |
| Elecom                                | 1         | 0.01%   |
| Comneon                               | 1         | 0.01%   |
| Cinterion                             | 1         | 0.01%   |
| Atmel                                 | 1         | 0.01%   |
| AirVast                               | 1         | 0.01%   |
| AboCom Systems                        | 1         | 0.01%   |
| 3Com                                  | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 1143      | 6.24%   |
| Intel Wireless 7260                                                     | 687       | 3.75%   |
| Intel Wireless 8265 / 8275                                              | 590       | 3.22%   |
| Intel Wireless 7265                                                     | 554       | 3.02%   |
| Intel Wireless 8260                                                     | 462       | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 448       | 2.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 426       | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 421       | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 403       | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 394       | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 386       | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 370       | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 368       | 2.01%   |
| Intel Wi-Fi 6 AX201                                                     | 359       | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 354       | 1.93%   |
| Intel Wireless-AC 9260                                                  | 314       | 1.71%   |
| Intel Wireless 3165                                                     | 292       | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 276       | 1.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 244       | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 244       | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 239       | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 238       | 1.3%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 237       | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 233       | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 226       | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 219       | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 195       | 1.06%   |
| Intel Wireless 3160                                                     | 186       | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 181       | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 181       | 0.99%   |
| Intel Centrino Ultimate-N 6300                                          | 180       | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 161       | 0.88%   |
| Realtek 802.11ac NIC                                                    | 160       | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 158       | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 157       | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 156       | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 136       | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 134       | 0.73%   |
| Ralink MT7601U Wireless Adapter                                         | 131       | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 129       | 0.7%    |
| Intel Centrino Advanced-N 6200                                          | 128       | 0.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 125       | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 122       | 0.67%   |
| Intel Centrino Advanced-N 6235                                          | 113       | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 105       | 0.57%   |
| Intel Centrino Wireless-N 2230                                          | 102       | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 100       | 0.55%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 100       | 0.55%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 98        | 0.53%   |
| Ralink RT5370 Wireless Adapter                                          | 95        | 0.52%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 95        | 0.52%   |
| Intel WiFi Link 5100                                                    | 92        | 0.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 92        | 0.5%    |
| Ralink RT5372 Wireless Adapter                                          | 89        | 0.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 87        | 0.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 87        | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 83        | 0.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 0.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 83        | 0.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 78        | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 8789      | 44.09%  |
| Intel                            | 6652      | 33.37%  |
| Broadcom                         | 1091      | 5.47%   |
| Qualcomm Atheros                 | 1021      | 5.12%   |
| Nvidia                           | 715       | 3.59%   |
| Marvell Technology Group         | 371       | 1.86%   |
| Broadcom Limited                 | 191       | 0.96%   |
| ASIX Electronics                 | 178       | 0.89%   |
| Samsung Electronics              | 157       | 0.79%   |
| DisplayLink                      | 94        | 0.47%   |
| Aquantia                         | 92        | 0.46%   |
| Lenovo                           | 56        | 0.28%   |
| Google                           | 47        | 0.24%   |
| Motorola PCS                     | 35        | 0.18%   |
| Apple                            | 35        | 0.18%   |
| Mellanox Technologies            | 32        | 0.16%   |
| LG Electronics                   | 25        | 0.13%   |
| TP-Link                          | 24        | 0.12%   |
| Microsoft                        | 23        | 0.12%   |
| Qualcomm                         | 21        | 0.11%   |
| MediaTek                         | 21        | 0.11%   |
| D-Link System                    | 21        | 0.11%   |
| Microchip Technology             | 20        | 0.1%    |
| Cypress Semiconductor            | 17        | 0.09%   |
| 3Com                             | 16        | 0.08%   |
| VIA Technologies                 | 13        | 0.07%   |
| ADMtek                           | 12        | 0.06%   |
| JMicron Technology               | 11        | 0.06%   |
| Hewlett-Packard                  | 11        | 0.06%   |
| ZTE WCDMA Technologies MSM       | 9         | 0.05%   |
| Xiaomi                           | 9         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.04%   |
| Solarflare Communications        | 7         | 0.04%   |
| Emulex                           | 7         | 0.04%   |
| Tehuti Networks                  | 6         | 0.03%   |
| Standard Microsystems            | 6         | 0.03%   |
| Novatel Wireless                 | 6         | 0.03%   |
| NetGear                          | 6         | 0.03%   |
| Linksys                          | 6         | 0.03%   |
| IBM                              | 6         | 0.03%   |
| Silicon Integrated Systems [SiS] | 5         | 0.03%   |
| T & A Mobile Phones              | 4         | 0.02%   |
| Netchip Technology               | 4         | 0.02%   |
| National Semiconductor           | 4         | 0.02%   |
| Accton Technology                | 4         | 0.02%   |
| NetXen Incorporated              | 3         | 0.02%   |
| Lite-On Communications           | 3         | 0.02%   |
| ICS Advent                       | 3         | 0.02%   |
| Davicom Semiconductor            | 3         | 0.02%   |
| Belkin Components                | 3         | 0.02%   |
| ZyXEL Communications             | 2         | 0.01%   |
| Unknown                          | 2         | 0.01%   |
| QLogic                           | 2         | 0.01%   |
| Kyocera                          | 2         | 0.01%   |
| Huawei Technologies              | 2         | 0.01%   |
| American Megatrends              | 2         | 0.01%   |
| Yulong                           | 1         | 0.01%   |
| Xilinx                           | 1         | 0.01%   |
| Westell                          | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6371      | 31.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1442      | 7.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1194      | 5.81%   |
| Intel I211 Gigabit Network Connection                             | 834       | 4.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 527       | 2.57%   |
| Intel Ethernet Connection I217-LM                                 | 475       | 2.31%   |
| Nvidia MCP79 Ethernet                                             | 404       | 1.97%   |
| Intel Ethernet Connection (2) I219-V                              | 381       | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 324       | 1.58%   |
| Intel Ethernet Connection (7) I219-V                              | 225       | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 192       | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 187       | 0.91%   |
| Intel 82574L Gigabit Network Connection                           | 185       | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 181       | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 166       | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 161       | 0.78%   |
| Intel I210 Gigabit Network Connection                             | 160       | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 157       | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 151       | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 151       | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 149       | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 147       | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 144       | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 139       | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 138       | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 136       | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 133       | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 129       | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 128       | 0.62%   |
| Intel Ethernet Connection (13) I219-V                             | 127       | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 123       | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 120       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 109       | 0.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 103       | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 99        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 95        | 0.46%   |
| Intel I350 Gigabit Network Connection                             | 91        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 90        | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 90        | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 82        | 0.4%    |
| Intel Ethernet Connection (4) I219-V                              | 82        | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 77        | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 76        | 0.37%   |
| Intel Ethernet Connection (10) I219-V                             | 69        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 68        | 0.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 68        | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 67        | 0.33%   |
| Intel Ethernet Connection (6) I219-V                              | 67        | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 64        | 0.31%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 63        | 0.31%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 61        | 0.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 59        | 0.29%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 53        | 0.26%   |
| Intel 82562V-2 10/100 Network Connection                          | 53        | 0.26%   |
| Intel Ethernet Connection (6) I219-LM                             | 49        | 0.24%   |
| Intel 82576 Gigabit Network Connection                            | 49        | 0.24%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 49        | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 47        | 0.23%   |
| Intel Ethernet Connection I219-V                                  | 47        | 0.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 45        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18600     | 51.86%  |
| WiFi     | 16905     | 47.13%  |
| Modem    | 295       | 0.82%   |
| Unknown  | 68        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 14104     | 52.25%  |
| Ethernet | 12869     | 47.67%  |
| Unknown  | 15        | 0.06%   |
| Modem    | 7         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12051     | 54.88%  |
| 1     | 8357      | 38.06%  |
| 3     | 685       | 3.12%   |
| 0     | 561       | 2.55%   |
| 4     | 203       | 0.92%   |
| 6     | 43        | 0.2%    |
| 5     | 40        | 0.18%   |
| 8     | 9         | 0.04%   |
| 10    | 2         | 0.01%   |
| 132   | 1         | 0.005%  |
| 66    | 1         | 0.005%  |
| 18    | 1         | 0.005%  |
| 13    | 1         | 0.005%  |
| 12    | 1         | 0.005%  |
| 9     | 1         | 0.005%  |
| 7     | 1         | 0.005%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 18953     | 85.22%  |
| Yes  | 3287      | 14.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6492      | 50.48%  |
| Apple                           | 1207      | 9.38%   |
| Qualcomm Atheros Communications | 1037      | 8.06%   |
| Realtek Semiconductor           | 1015      | 7.89%   |
| Broadcom                        | 830       | 6.45%   |
| Cambridge Silicon Radio         | 583       | 4.53%   |
| Dell                            | 239       | 1.86%   |
| IMC Networks                    | 231       | 1.8%    |
| Lite-On Technology              | 229       | 1.78%   |
| ASUSTek Computer                | 224       | 1.74%   |
| Foxconn / Hon Hai               | 197       | 1.53%   |
| Hewlett-Packard                 | 104       | 0.81%   |
| Marvell Semiconductor           | 103       | 0.8%    |
| Toshiba                         | 72        | 0.56%   |
| Dynex                           | 63        | 0.49%   |
| Ralink                          | 56        | 0.44%   |
| Alps Electric                   | 26        | 0.2%    |
| Edimax Technology               | 20        | 0.16%   |
| Realtek                         | 17        | 0.13%   |
| MediaTek                        | 16        | 0.12%   |
| HTC (High Tech Computer)        | 16        | 0.12%   |
| Micro Star International        | 13        | 0.1%    |
| Ralink Technology               | 9         | 0.07%   |
| Primax Electronics              | 9         | 0.07%   |
| Taiyo Yuden                     | 8         | 0.06%   |
| Foxconn International           | 8         | 0.06%   |
| Integrated System Solution      | 6         | 0.05%   |
| Kensington                      | 5         | 0.04%   |
| TP-Link                         | 4         | 0.03%   |
| Unknown                         | 3         | 0.02%   |
| Fujitsu                         | 3         | 0.02%   |
| Askey Computer                  | 3         | 0.02%   |
| Mobile Action Technology        | 2         | 0.02%   |
| Conwise Technology              | 2         | 0.02%   |
| Chicony Electronics             | 2         | 0.02%   |
| Roper                           | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |
| Opticis                         | 1         | 0.01%   |
| Motorola PCS                    | 1         | 0.01%   |
| Microsoft                       | 1         | 0.01%   |
| Logitech                        | 1         | 0.01%   |
| Cypress Semiconductor           | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 2575      | 19.97%  |
| Intel AX200 Bluetooth                                                               | 1073      | 8.32%   |
| Intel AX201 Bluetooth                                                               | 939       | 7.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 787       | 6.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 583       | 4.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 578       | 4.48%   |
| Realtek Bluetooth Radio                                                             | 522       | 4.05%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 419       | 3.25%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 390       | 3.03%   |
| Apple Bluetooth USB Host Controller                                                 | 362       | 2.81%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 346       | 2.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 303       | 2.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 286       | 2.22%   |
| Apple Bluetooth Host Controller                                                     | 259       | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 196       | 1.52%   |
| Intel AX210 Bluetooth                                                               | 150       | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 127       | 0.99%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 112       | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 112       | 0.87%   |
| Intel Bluetooth Device                                                              | 98        | 0.76%   |
| Dell DW375 Bluetooth Module                                                         | 93        | 0.72%   |
| IMC Networks Bluetooth Radio                                                        | 89        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 89        | 0.69%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 89        | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 83        | 0.64%   |
| Apple Bluetooth HCI                                                                 | 80        | 0.62%   |
| Lite-On Bluetooth Device                                                            | 78        | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 76        | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 74        | 0.57%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 68        | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 68        | 0.53%   |
| Realtek 802.11n WLAN Adapter                                                        | 65        | 0.5%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 63        | 0.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 61        | 0.47%   |
| Realtek RTL8821A Bluetooth                                                          | 60        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 60        | 0.47%   |
| Ralink RT3290 Bluetooth                                                             | 56        | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 55        | 0.43%   |
| IMC Networks Bluetooth Device                                                       | 51        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 51        | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 49        | 0.38%   |
| ASUS Bluetooth Radio                                                                | 41        | 0.32%   |
| Broadcom HP Portable SoftSailing                                                    | 40        | 0.31%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 35        | 0.27%   |
| IMC Networks Wireless_Device                                                        | 34        | 0.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 34        | 0.26%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 32        | 0.25%   |
| Broadcom BCM20702A0                                                                 | 31        | 0.24%   |
| Toshiba Bluetooth Device                                                            | 29        | 0.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 29        | 0.22%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 27        | 0.21%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 26        | 0.2%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 26        | 0.2%    |
| ASUS ASUS USB-BT500                                                                 | 26        | 0.2%    |
| Toshiba BCM43142A0                                                                  | 23        | 0.18%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 23        | 0.18%   |
| ASUS BCM20702A0                                                                     | 23        | 0.18%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 22        | 0.17%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.17%   |
| Dell Wireless 365 Bluetooth                                                         | 21        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 14743     | 48.75%  |
| AMD                                             | 6527      | 21.58%  |
| Nvidia                                          | 5692      | 18.82%  |
| C-Media Electronics                             | 525       | 1.74%   |
| Logitech                                        | 290       | 0.96%   |
| Creative Labs                                   | 230       | 0.76%   |
| Texas Instruments                               | 161       | 0.53%   |
| JMTek                                           | 126       | 0.42%   |
| Corsair                                         | 111       | 0.37%   |
| Realtek Semiconductor                           | 106       | 0.35%   |
| Blue Microphones                                | 102       | 0.34%   |
| SteelSeries ApS                                 | 85        | 0.28%   |
| Focusrite-Novation                              | 78        | 0.26%   |
| Razer USA                                       | 76        | 0.25%   |
| Kingston Technology                             | 76        | 0.25%   |
| Plantronics                                     | 73        | 0.24%   |
| Lenovo                                          | 63        | 0.21%   |
| Creative Technology                             | 62        | 0.21%   |
| Tenx Technology                                 | 58        | 0.19%   |
| GN Netcom                                       | 54        | 0.18%   |
| ASUSTek Computer                                | 48        | 0.16%   |
| Apple                                           | 42        | 0.14%   |
| Generalplus Technology                          | 40        | 0.13%   |
| VIA Technologies                                | 38        | 0.13%   |
| Dell                                            | 31        | 0.1%    |
| Sony                                            | 28        | 0.09%   |
| GYROCOM C&C                                     | 27        | 0.09%   |
| Giga-Byte Technology                            | 24        | 0.08%   |
| Sennheiser Communications                       | 23        | 0.08%   |
| Microsoft                                       | 22        | 0.07%   |
| Samson Technologies                             | 20        | 0.07%   |
| Audio-Technica                                  | 20        | 0.07%   |
| SAVITECH                                        | 18        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 18        | 0.06%   |
| XMOS                                            | 17        | 0.06%   |
| Valve Software                                  | 17        | 0.06%   |
| Unknown                                         | 17        | 0.06%   |
| Turtle Beach                                    | 17        | 0.06%   |
| Cambridge Silicon Radio                         | 17        | 0.06%   |
| PreSonus Audio Electronics                      | 16        | 0.05%   |
| ONN                                             | 16        | 0.05%   |
| No brand                                        | 15        | 0.05%   |
| Astro Gaming                                    | 15        | 0.05%   |
| M-Audio                                         | 14        | 0.05%   |
| BEHRINGER International                         | 14        | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 12        | 0.04%   |
| Hewlett-Packard                                 | 12        | 0.04%   |
| FiiO Electronics Technology                     | 12        | 0.04%   |
| Asahi Kasei Microsystems                        | 12        | 0.04%   |
| Schiit Audio                                    | 11        | 0.04%   |
| Yamaha                                          | 10        | 0.03%   |
| Samsung Electronics                             | 10        | 0.03%   |
| Alesis                                          | 10        | 0.03%   |
| AKAI Professional M.I.                          | 10        | 0.03%   |
| ROCCAT                                          | 9         | 0.03%   |
| Micro Star International                        | 9         | 0.03%   |
| Bose                                            | 9         | 0.03%   |
| Ensoniq                                         | 8         | 0.03%   |
| Antlion Audio                                   | 8         | 0.03%   |
| Syntek                                          | 6         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1511      | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1459      | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1389      | 3.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1132      | 3.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1094      | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1089      | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1007      | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 896       | 2.49%   |
| AMD FCH Azalia Controller                                                                         | 837       | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 815       | 2.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 702       | 1.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 633       | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 617       | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 615       | 1.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 609       | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 596       | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 575       | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 539       | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 502       | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 495       | 1.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 472       | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 431       | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 419       | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 416       | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 413       | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 410       | 1.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 409       | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 379       | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 374       | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 362       | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 360       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 353       | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 333       | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 329       | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 327       | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 325       | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 309       | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 301       | 0.84%   |
| AMD Navi 10 HDMI Audio                                                                            | 301       | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 293       | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 289       | 0.8%    |
| Nvidia High Definition Audio Controller                                                           | 257       | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                                  | 246       | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 246       | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 242       | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 238       | 0.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 237       | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 233       | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 229       | 0.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 213       | 0.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 212       | 0.59%   |
| AMD Trinity HDMI Audio Controller                                                                 | 201       | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 193       | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 193       | 0.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 191       | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 180       | 0.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 173       | 0.48%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 168       | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 166       | 0.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 156       | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 2628      | 23.11%  |
| SK Hynix                     | 2338      | 20.56%  |
| Micron Technology            | 1110      | 9.76%   |
| Unknown                      | 910       | 8%      |
| Crucial                      | 805       | 7.08%   |
| G.Skill                      | 770       | 6.77%   |
| Kingston                     | 749       | 6.59%   |
| Corsair                      | 666       | 5.86%   |
| Elpida                       | 224       | 1.97%   |
| Ramaxel Technology           | 157       | 1.38%   |
| Nanya Technology             | 154       | 1.35%   |
| A-DATA Technology            | 153       | 1.35%   |
| Team                         | 107       | 0.94%   |
| Patriot                      | 105       | 0.92%   |
| Unknown (ABCD)               | 64        | 0.56%   |
| PNY                          | 52        | 0.46%   |
| Avant                        | 34        | 0.3%    |
| Neo Forza                    | 27        | 0.24%   |
| Goldkey                      | 27        | 0.24%   |
| Unknown                      | 21        | 0.18%   |
| Silicon Power                | 18        | 0.16%   |
| Qimonda                      | 17        | 0.15%   |
| Sesame                       | 16        | 0.14%   |
| Transcend                    | 14        | 0.12%   |
| TIMETEC                      | 11        | 0.1%    |
| Apacer                       | 10        | 0.09%   |
| Golden Empire                | 9         | 0.08%   |
| ASint Technology             | 9         | 0.08%   |
| CSX                          | 8         | 0.07%   |
| EVGA                         | 7         | 0.06%   |
| Unifosa                      | 6         | 0.05%   |
| Infineon                     | 6         | 0.05%   |
| Hewlett-Packard              | 6         | 0.05%   |
| GEIL                         | 6         | 0.05%   |
| SHARETRONIC                  | 5         | 0.04%   |
| OLOY                         | 5         | 0.04%   |
| OCZ                          | 5         | 0.04%   |
| V-Color                      | 4         | 0.04%   |
| Toshiba                      | 4         | 0.04%   |
| Super Talent                 | 4         | 0.04%   |
| AXIOM                        | 4         | 0.04%   |
| Unknown (0x8551)             | 3         | 0.03%   |
| Unknown (0x02BA)             | 3         | 0.03%   |
| S                            | 3         | 0.03%   |
| Innodisk                     | 3         | 0.03%   |
| H                            | 3         | 0.03%   |
| Centon                       | 3         | 0.03%   |
| Unknown (F785)               | 2         | 0.02%   |
| Unknown (AB)                 | 2         | 0.02%   |
| Unknown (0x8319)             | 2         | 0.02%   |
| Unknown (02BA)               | 2         | 0.02%   |
| Ramos Technology             | 2         | 0.02%   |
| Patriot Memory (PDP Systems) | 2         | 0.02%   |
| Patriot Memory               | 2         | 0.02%   |
| Mushkin                      | 2         | 0.02%   |
| M                            | 2         | 0.02%   |
| KomputerBay                  | 2         | 0.02%   |
| ISD Technology Limited       | 2         | 0.02%   |
| HPE                          | 2         | 0.02%   |
| Goldenmars                   | 2         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                         | 256       | 2.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 156       | 1.28%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 89        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 86        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 83        | 0.68%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 76        | 0.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 72        | 0.59%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s               | 70        | 0.57%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                         | 69        | 0.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 68        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 67        | 0.55%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 66        | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 65        | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 62        | 0.51%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 61        | 0.5%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 60        | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 58        | 0.48%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 57        | 0.47%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s              | 55        | 0.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 54        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 50        | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 48        | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 46        | 0.38%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 44        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 44        | 0.36%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 44        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 43        | 0.35%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 41        | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 39        | 0.32%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 39        | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 39        | 0.32%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 38        | 0.31%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 38        | 0.31%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 37        | 0.3%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 37        | 0.3%    |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 37        | 0.3%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 36        | 0.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 36        | 0.3%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 35        | 0.29%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 35        | 0.29%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 35        | 0.29%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 34        | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 34        | 0.28%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 33        | 0.27%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 31        | 0.25%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 31        | 0.25%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 30        | 0.25%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 30        | 0.25%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                          | 30        | 0.25%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 29        | 0.24%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 29        | 0.24%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 29        | 0.24%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 29        | 0.24%   |
| Crucial RAM CT8G4SFS824A.M8FE 8192MB SODIMM DDR4 2667MT/s           | 29        | 0.24%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s               | 29        | 0.24%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s             | 28        | 0.23%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 28        | 0.23%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s              | 28        | 0.23%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 27        | 0.22%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s               | 27        | 0.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 4403      | 43.8%   |
| DDR3         | 3575      | 35.57%  |
| DDR2         | 834       | 8.3%    |
| LPDDR3       | 362       | 3.6%    |
| LPDDR4       | 292       | 2.9%    |
| SDRAM        | 242       | 2.41%   |
| Unknown      | 231       | 2.3%    |
| DDR          | 91        | 0.91%   |
| DRAM         | 21        | 0.21%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 5413      | 54.36%  |
| DIMM         | 3761      | 37.77%  |
| Row Of Chips | 625       | 6.28%   |
| Chip         | 66        | 0.66%   |
| Unknown      | 49        | 0.49%   |
| FB-DIMM      | 23        | 0.23%   |
| RIMM         | 20        | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 3792      | 34.91%  |
| 4096  | 2932      | 26.99%  |
| 16384 | 1473      | 13.56%  |
| 2048  | 1445      | 13.3%   |
| 1024  | 703       | 6.47%   |
| 32768 | 415       | 3.82%   |
| 512   | 63        | 0.58%   |
| 256   | 19        | 0.17%   |
| 65536 | 14        | 0.13%   |
| 1536  | 3         | 0.03%   |
| 128   | 1         | 0.01%   |
| 64    | 1         | 0.01%   |
| 32    | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2425      | 22.56%  |
| 2667    | 1397      | 13%     |
| 3200    | 1242      | 11.55%  |
| 1333    | 779       | 7.25%   |
| 2400    | 729       | 6.78%   |
| 2133    | 612       | 5.69%   |
| 800     | 519       | 4.83%   |
| 3600    | 400       | 3.72%   |
| 667     | 308       | 2.87%   |
| 1867    | 254       | 2.36%   |
| 1334    | 231       | 2.15%   |
| 1067    | 149       | 1.39%   |
| 4267    | 146       | 1.36%   |
| 3466    | 142       | 1.32%   |
| Unknown | 130       | 1.21%   |
| 1066    | 109       | 1.01%   |
| 3000    | 104       | 0.97%   |
| 3266    | 95        | 0.88%   |
| 2666    | 78        | 0.73%   |
| 3733    | 72        | 0.67%   |
| 2048    | 71        | 0.66%   |
| 1866    | 61        | 0.57%   |
| 2933    | 60        | 0.56%   |
| 533     | 60        | 0.56%   |
| 1800    | 45        | 0.42%   |
| 975     | 43        | 0.4%    |
| 4199    | 42        | 0.39%   |
| 3400    | 32        | 0.3%    |
| 2800    | 32        | 0.3%    |
| 49926   | 24        | 0.22%   |
| 3866    | 24        | 0.22%   |
| 400     | 24        | 0.22%   |
| 3800    | 18        | 0.17%   |
| 2200    | 18        | 0.17%   |
| 333     | 17        | 0.16%   |
| 3333    | 14        | 0.13%   |
| 3100    | 14        | 0.13%   |
| 266     | 14        | 0.13%   |
| 4266    | 13        | 0.12%   |
| 3067    | 13        | 0.12%   |
| 2000    | 13        | 0.12%   |
| 2733    | 10        | 0.09%   |
| 1639    | 10        | 0.09%   |
| 2465    | 9         | 0.08%   |
| 4800    | 8         | 0.07%   |
| 4000    | 8         | 0.07%   |
| 3334    | 8         | 0.07%   |
| 4333    | 7         | 0.07%   |
| 3007    | 7         | 0.07%   |
| 2132    | 7         | 0.07%   |
| 3666    | 6         | 0.06%   |
| 3500    | 6         | 0.06%   |
| 1400    | 6         | 0.06%   |
| 4400    | 5         | 0.05%   |
| 3533    | 5         | 0.05%   |
| 3066    | 5         | 0.05%   |
| 8400    | 4         | 0.04%   |
| 2473    | 4         | 0.04%   |
| 2134    | 4         | 0.04%   |
| 2934    | 3         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 271       | 38.83%  |
| Brother Industries                 | 181       | 25.93%  |
| Canon                              | 120       | 17.19%  |
| Samsung Electronics                | 35        | 5.01%   |
| Seiko Epson                        | 16        | 2.29%   |
| Dymo-CoStar                        | 14        | 2.01%   |
| Zebra                              | 11        | 1.58%   |
| Prolific Technology                | 10        | 1.43%   |
| QinHeng Electronics                | 8         | 1.15%   |
| Dell                               | 6         | 0.86%   |
| Xerox                              | 5         | 0.72%   |
| Pantum                             | 4         | 0.57%   |
| STMicroelectronics                 | 3         | 0.43%   |
| Lexmark International              | 2         | 0.29%   |
| TSC Auto ID Technology             | 1         | 0.14%   |
| Star Micronics                     | 1         | 0.14%   |
| Sharp                              | 1         | 0.14%   |
| Ricoh                              | 1         | 0.14%   |
| Omnidirectional Control Technology | 1         | 0.14%   |
| MIIIW                              | 1         | 0.14%   |
| Kyocera                            | 1         | 0.14%   |
| Konica Minolta                     | 1         | 0.14%   |
| ICS Advent                         | 1         | 0.14%   |
| Coopaty                            | 1         | 0.14%   |
| Boca Systems                       | 1         | 0.14%   |
| Apple                              | 1         | 0.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother Printer                                           | 19        | 2.66%   |
| Canon PIXMA MG2500 Series                                 | 14        | 1.96%   |
| HP LaserJet 3050                                          | 13        | 1.82%   |
| Brother HL-2270DW Laser Printer                           | 11        | 1.54%   |
| Prolific PL2305 Parallel Port                             | 10        | 1.4%    |
| HP DeskJet 2600 series                                    | 10        | 1.4%    |
| Canon PIXMA MX920 Series                                  | 9         | 1.26%   |
| Samsung SCX-3400 Series                                   | 8         | 1.12%   |
| QinHeng CH340S                                            | 8         | 1.12%   |
| HP OfficeJet 5200 series                                  | 8         | 1.12%   |
| Brother HL-L2340D series                                  | 8         | 1.12%   |
| Brother HL-L2320D series                                  | 8         | 1.12%   |
| Brother HL-L2300D series                                  | 8         | 1.12%   |
| HP OfficeJet 3830 series                                  | 7         | 0.98%   |
| HP LaserJet 400 M401dne                                   | 7         | 0.98%   |
| Brother DCP-L2540DW                                       | 7         | 0.98%   |
| HP Officejet 4500 G510g-m                                 | 6         | 0.84%   |
| HP LaserJet P1006                                         | 6         | 0.84%   |
| HP ENVY 4520 series                                       | 6         | 0.84%   |
| HP DeskJet 3630 series                                    | 6         | 0.84%   |
| HP Deskjet 2540 series                                    | 6         | 0.84%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 6         | 0.84%   |
| Canon PIXMA MG3600 Series                                 | 6         | 0.84%   |
| HP Printing Support                                       | 5         | 0.7%    |
| HP Officejet 4500 G510n-z                                 | 5         | 0.7%    |
| HP LaserJet Professional P1102w                           | 5         | 0.7%    |
| HP LaserJet 1012                                          | 5         | 0.7%    |
| HP DeskJet 2130 series                                    | 5         | 0.7%    |
| HP Deskjet 1050 J410                                      | 5         | 0.7%    |
| Brother MFC-J485DW                                        | 5         | 0.7%    |
| Brother MFC-J470DW                                        | 5         | 0.7%    |
| Brother HL-L2380DW                                        | 5         | 0.7%    |
| Brother HL-2240 series                                    | 5         | 0.7%    |
| Brother HL-2140 series                                    | 5         | 0.7%    |
| Pantum P2500W series                                      | 4         | 0.56%   |
| HP OfficeJet Pro 69                                       | 4         | 0.56%   |
| HP Officejet 6600                                         | 4         | 0.56%   |
| HP OfficeJet 4650 series                                  | 4         | 0.56%   |
| HP LaserJet M14-M17                                       | 4         | 0.56%   |
| HP LaserJet M101-M106                                     | 4         | 0.56%   |
| HP LaserJet 1200                                          | 4         | 0.56%   |
| HP LaserJet 1020                                          | 4         | 0.56%   |
| HP DeskJet 1110 series                                    | 4         | 0.56%   |
| Canon TS3300 series                                       | 4         | 0.56%   |
| Brother MFC-L2710DW series                                | 4         | 0.56%   |
| Brother HL-L2360D series                                  | 4         | 0.56%   |
| Brother HL-L2305 series                                   | 4         | 0.56%   |
| Brother HL-5250DN Printer                                 | 4         | 0.56%   |
| Brother HL-3170CDW series                                 | 4         | 0.56%   |
| Brother HL-2240D series                                   | 4         | 0.56%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 3         | 0.42%   |
| Zebra ZP 450 Printer                                      | 3         | 0.42%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 3         | 0.42%   |
| Samsung M2070 Series                                      | 3         | 0.42%   |
| Samsung M2020 Series                                      | 3         | 0.42%   |
| HP OfficeJet Pro 8020 series                              | 3         | 0.42%   |
| HP OfficeJet Pro 7740 series                              | 3         | 0.42%   |
| HP OfficeJet Pro 6960                                     | 3         | 0.42%   |
| HP OfficeJet 6960                                         | 3         | 0.42%   |
| HP LaserJet P2035                                         | 3         | 0.42%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Canon                  | 37        | 42.05%  |
| Seiko Epson            | 34        | 38.64%  |
| Hewlett-Packard        | 14        | 15.91%  |
| Visioneer              | 1         | 1.14%   |
| UMAX                   | 1         | 1.14%   |
| Microtek International | 1         | 1.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                     | 9         | 10.11%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 8         | 8.99%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]     | 4         | 4.49%   |
| Canon CanoScan LIDE 25                                      | 4         | 4.49%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 3         | 3.37%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 3         | 3.37%   |
| HP ScanJet 82x0C                                            | 3         | 3.37%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 3         | 3.37%   |
| Canon CanoScan N1240U/LiDE 30                               | 3         | 3.37%   |
| Canon CanoScan LiDE 220                                     | 3         | 3.37%   |
| Canon CanoScan LiDE 210                                     | 3         | 3.37%   |
| Seiko Epson Scanner                                         | 2         | 2.25%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 2         | 2.25%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                | 2         | 2.25%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 2         | 2.25%   |
| Seiko Epson ES-D200 [GT-S50]                                | 2         | 2.25%   |
| Canon CanoScan LiDE 60                                      | 2         | 2.25%   |
| Canon CanoScan LiDE 200                                     | 2         | 2.25%   |
| Canon CanoScan LiDE 120                                     | 2         | 2.25%   |
| Visioneer OneTouch 5300 USB                                 | 1         | 1.12%   |
| UMAX Astra 2200/2200SU                                      | 1         | 1.12%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                 | 1         | 1.12%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                 | 1         | 1.12%   |
| Seiko Epson GT-X700 [Perfection 4870]                       | 1         | 1.12%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                 | 1         | 1.12%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 1.12%   |
| Seiko Epson GT-9400UF [Perfection 3170]                     | 1         | 1.12%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]               | 1         | 1.12%   |
| Microtek International ScanMaker V6USL                      | 1         | 1.12%   |
| HP ScanJet G4050                                            | 1         | 1.12%   |
| HP ScanJet 7650                                             | 1         | 1.12%   |
| HP ScanJet 7400c                                            | 1         | 1.12%   |
| HP ScanJet 6200c                                            | 1         | 1.12%   |
| HP ScanJet 5590                                             | 1         | 1.12%   |
| HP ScanJet 5470c/5490c                                      | 1         | 1.12%   |
| HP ScanJet 5300c/5370c                                      | 1         | 1.12%   |
| HP ScanJet 4850C/4890C                                      | 1         | 1.12%   |
| HP PSC-2100                                                 | 1         | 1.12%   |
| HP PSC 1200                                                 | 1         | 1.12%   |
| HP HP4470C                                                  | 1         | 1.12%   |
| Canon CanoScan N650U/N656U                                  | 1         | 1.12%   |
| Canon CanoScan LiDE 70                                      | 1         | 1.12%   |
| Canon CanoScan LiDE 500F                                    | 1         | 1.12%   |
| Canon CanoScan LiDE 100                                     | 1         | 1.12%   |
| Canon CanoScan 9950F                                        | 1         | 1.12%   |
| Canon CanoScan 8800F                                        | 1         | 1.12%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2355      | 19.64%  |
| Microdia                               | 1143      | 9.53%   |
| Logitech                               | 1053      | 8.78%   |
| Realtek Semiconductor                  | 964       | 8.04%   |
| Acer                                   | 898       | 7.49%   |
| IMC Networks                           | 768       | 6.41%   |
| Sunplus Innovation Technology          | 738       | 6.16%   |
| Apple                                  | 622       | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 503       | 4.2%    |
| Quanta                                 | 476       | 3.97%   |
| Suyin                                  | 360       | 3%      |
| Lite-On Technology                     | 225       | 1.88%   |
| Samsung Electronics                    | 195       | 1.63%   |
| Syntek                                 | 180       | 1.5%    |
| Microsoft                              | 155       | 1.29%   |
| Ricoh                                  | 126       | 1.05%   |
| Importek                               | 94        | 0.78%   |
| Alcor Micro                            | 91        | 0.76%   |
| Luxvisions Innotech Limited            | 76        | 0.63%   |
| Silicon Motion                         | 74        | 0.62%   |
| Lenovo                                 | 70        | 0.58%   |
| LG Electronics                         | 51        | 0.43%   |
| ARC International                      | 49        | 0.41%   |
| OmniVision Technologies                | 41        | 0.34%   |
| Primax Electronics                     | 40        | 0.33%   |
| Z-Star Microelectronics                | 38        | 0.32%   |
| Unknown                                | 35        | 0.29%   |
| Intel                                  | 31        | 0.26%   |
| MacroSilicon                           | 30        | 0.25%   |
| Razer USA                              | 25        | 0.21%   |
| Generalplus Technology                 | 25        | 0.21%   |
| GEMBIRD                                | 23        | 0.19%   |
| Creative Technology                    | 22        | 0.18%   |
| ALi                                    | 21        | 0.18%   |
| Cubeternet                             | 20        | 0.17%   |
| Huawei Technologies                    | 19        | 0.16%   |
| Hewlett-Packard                        | 18        | 0.15%   |
| Valve Software                         | 16        | 0.13%   |
| KYE Systems (Mouse Systems)            | 15        | 0.13%   |
| webcam                                 | 14        | 0.12%   |
| CQG-5693-201019                        | 11        | 0.09%   |
| Jieli Technology                       | 10        | 0.08%   |
| Genesys Logic                          | 10        | 0.08%   |
| AVerMedia Technologies                 | 10        | 0.08%   |
| Sonix Technology                       | 9         | 0.08%   |
| Tobii Technology AB                    | 8         | 0.07%   |
| Sunplus Technology                     | 8         | 0.07%   |
| GenesysLogic Technology                | 8         | 0.07%   |
| 8SSC20F27114V1GZ07N14V2                | 8         | 0.07%   |
| Ruision                                | 7         | 0.06%   |
| Novatek Microelectronics               | 7         | 0.06%   |
| Linux Foundation                       | 7         | 0.06%   |
| Dynex                                  | 7         | 0.06%   |
| Arkmicro Technologies                  | 7         | 0.06%   |
| YGTek                                  | 6         | 0.05%   |
| USB Camera                             | 6         | 0.05%   |
| Pixart Imaging                         | 6         | 0.05%   |
| SJ-180517-N                            | 5         | 0.04%   |
| Magic Control Technology               | 5         | 0.04%   |
| Google                                 | 5         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 533       | 4.38%   |
| Realtek Integrated_Webcam_HD                                   | 422       | 3.47%   |
| Microdia Integrated_Webcam_HD                                  | 418       | 3.44%   |
| Acer Integrated Camera                                         | 323       | 2.66%   |
| Sunplus Integrated_Webcam_HD                                   | 288       | 2.37%   |
| IMC Networks Integrated Camera                                 | 272       | 2.24%   |
| Logitech HD Pro Webcam C920                                    | 254       | 2.09%   |
| Samsung Galaxy A5 (MTP)                                        | 190       | 1.56%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 186       | 1.53%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 175       | 1.44%   |
| Apple Built-in iSight                                          | 164       | 1.35%   |
| Logitech Webcam C270                                           | 163       | 1.34%   |
| Chicony HD WebCam                                              | 163       | 1.34%   |
| Microdia Integrated Webcam                                     | 133       | 1.09%   |
| Apple FaceTime HD Camera (Built-in)                            | 121       | 1%      |
| Chicony HP TrueVision HD                                       | 119       | 0.98%   |
| Quanta HP TrueVision HD Camera                                 | 110       | 0.9%    |
| Logitech HD Webcam C615                                        | 104       | 0.86%   |
| Syntek Integrated Camera                                       | 103       | 0.85%   |
| Apple FaceTime HD Camera                                       | 101       | 0.83%   |
| Microdia Webcam Vitade AF                                      | 100       | 0.82%   |
| Chicony USB2.0 Camera                                          | 80        | 0.66%   |
| Chicony TOSHIBA Web Camera - HD                                | 79        | 0.65%   |
| Realtek USB Camera                                             | 78        | 0.64%   |
| Lite-On Integrated Camera                                      | 78        | 0.64%   |
| Acer BisonCam,NB Pro                                           | 77        | 0.63%   |
| Chicony HP Wide Vision HD Camera                               | 74        | 0.61%   |
| Chicony EasyCamera                                             | 74        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 74        | 0.61%   |
| Chicony HP HD Camera                                           | 72        | 0.59%   |
| Realtek Integrated Webcam HD                                   | 71        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 70        | 0.58%   |
| Acer Integrated 5M Camera                                      | 69        | 0.57%   |
| Suyin HP Truevision HD                                         | 66        | 0.54%   |
| Chicony HP Truevision HD camera                                | 66        | 0.54%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 65        | 0.53%   |
| Logitech Webcam C310                                           | 63        | 0.52%   |
| Acer HD Webcam                                                 | 62        | 0.51%   |
| Quanta Chromebook HD Camera                                    | 60        | 0.49%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 60        | 0.49%   |
| Chicony USB2.0 HD UVC WebCam                                   | 57        | 0.47%   |
| Logitech C922 Pro Stream Webcam                                | 56        | 0.46%   |
| Chicony HP Webcam                                              | 55        | 0.45%   |
| Realtek Integrated Webcam                                      | 53        | 0.44%   |
| Chicony USB 2.0 Camera                                         | 53        | 0.44%   |
| Acer Lenovo EasyCamera                                         | 53        | 0.44%   |
| Importek TOSHIBA Web Camera - HD                               | 52        | 0.43%   |
| Chicony Lenovo EasyCamera                                      | 52        | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 52        | 0.43%   |
| Acer EasyCamera                                                | 52        | 0.43%   |
| Acer BisonCam, NB Pro                                          | 52        | 0.43%   |
| Sunplus HD WebCam                                              | 49        | 0.4%    |
| Quanta HD Webcam                                               | 48        | 0.39%   |
| Microdia Integrated Webcam HD                                  | 48        | 0.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 48        | 0.39%   |
| Chicony Integrated Camera (1280x720@30)                        | 47        | 0.39%   |
| Quanta HP Wide Vision HD Camera                                | 46        | 0.38%   |
| ARC International Camera                                       | 46        | 0.38%   |
| Chicony Integrated 5M Camera                                   | 45        | 0.37%   |
| Acer SunplusIT Integrated Camera                               | 45        | 0.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 793       | 34.57%  |
| Synaptics                  | 777       | 33.87%  |
| Shenzhen Goodix Technology | 265       | 11.55%  |
| AuthenTec                  | 119       | 5.19%   |
| Upek                       | 107       | 4.66%   |
| Elan Microelectronics      | 98        | 4.27%   |
| LighTuning Technology      | 57        | 2.48%   |
| STMicroelectronics         | 52        | 2.27%   |
| Samsung Electronics        | 19        | 0.83%   |
| DigitalPersona             | 5         | 0.22%   |
| Focal-systems.Corp         | 1         | 0.04%   |
| Dell                       | 1         | 0.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 302       | 13.16%  |
| Unknown                                                                    | 199       | 8.67%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 133       | 5.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 118       | 5.14%   |
| Shenzhen Goodix FingerPrint                                                | 110       | 4.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 109       | 4.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 102       | 4.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 95        | 4.14%   |
| Validity Sensors Fingerprint scanner                                       | 92        | 4.01%   |
| Elan ELAN:Fingerprint                                                      | 69        | 3.01%   |
| Synaptics  WBDI                                                            | 68        | 2.96%   |
| Validity Sensors VFS491                                                    | 60        | 2.62%   |
| Shenzhen Goodix  FingerPrint Device                                        | 60        | 2.62%   |
| Validity Sensors Synaptics WBDI                                            | 58        | 2.53%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 53        | 2.31%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 52        | 2.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 51        | 2.22%   |
| STMicroelectronics Fingerprint Reader                                      | 50        | 2.18%   |
| AuthenTec AES2810                                                          | 49        | 2.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 42        | 1.83%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 39        | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 37        | 1.61%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 33        | 1.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 31        | 1.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 30        | 1.31%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 22        | 0.96%   |
| Elan ELAN:ARM-M4                                                           | 21        | 0.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 0.92%   |
| Synaptics WBDI Device                                                      | 20        | 0.87%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 0.83%   |
| AuthenTec Fingerprint Sensor                                               | 17        | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 16        | 0.7%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 15        | 0.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 13        | 0.57%   |
| AuthenTec AES1600                                                          | 13        | 0.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 10        | 0.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 0.44%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 0.39%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 7         | 0.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 5         | 0.22%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 5         | 0.22%   |
| DigitalPersona Fingerprint Reader                                          | 5         | 0.22%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.17%   |
| Samsung Fingerprint Device                                                 | 4         | 0.17%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.13%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.13%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.09%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.09%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.09%   |
| Upek TCS1C EIM/STM32 Fingerprint sensor                                    | 1         | 0.04%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.04%   |
| Elan Elan Security-WBF Fingerprint Sensor                                  | 1         | 0.04%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 584       | 61.02%  |
| Alcor Micro           | 126       | 13.17%  |
| O2 Micro              | 73        | 7.63%   |
| Upek                  | 68        | 7.11%   |
| Lenovo                | 33        | 3.45%   |
| SCM Microsystems      | 32        | 3.34%   |
| OmniKey               | 8         | 0.84%   |
| Realtek Semiconductor | 7         | 0.73%   |
| Yubico.com            | 6         | 0.63%   |
| Advanced Card Systems | 4         | 0.42%   |
| Gemalto (was Gemplus) | 3         | 0.31%   |
| Chicony Electronics   | 3         | 0.31%   |
| Cherry                | 3         | 0.31%   |
| NXP Semiconductors    | 1         | 0.1%    |
| Mako Technologies     | 1         | 0.1%    |
| MagTek                | 1         | 0.1%    |
| Jing-Mold Enterprise  | 1         | 0.1%    |
| HID Global            | 1         | 0.1%    |
| Hewlett-Packard       | 1         | 0.1%    |
| BLUTRONICS            | 1         | 0.1%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 295       | 30.76%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 122       | 12.72%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 114       | 11.89%  |
| Broadcom 5880                                                                | 114       | 11.89%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 68        | 7.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 61        | 6.36%   |
| Broadcom 58200                                                               | 55        | 5.74%   |
| Lenovo Integrated Smart Card Reader                                          | 33        | 3.44%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 17        | 1.77%   |
| O2 Micro Oz776 SmartCard Reader                                              | 12        | 1.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 8         | 0.83%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 7         | 0.73%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 6         | 0.63%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 0.52%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 0.42%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 3         | 0.31%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 0.31%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 0.31%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 2         | 0.21%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.21%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.21%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.21%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.1%    |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.1%    |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.1%    |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.1%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.1%    |
| SCM Microsystems SCR3311 Smart Card Reader                                   | 1         | 0.1%    |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.1%    |
| OmniKey Smart Card Reader USB                                                | 1         | 0.1%    |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.1%    |
| OmniKey CardMan 4321                                                         | 1         | 0.1%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.1%    |
| NXP Semiconductors PR533                                                     | 1         | 0.1%    |
| Mako Technologies SZZCS-ZCS80                                                | 1         | 0.1%    |
| MagTek ZCS160-PCSC                                                           | 1         | 0.1%    |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.1%    |
| HID Global USB Reader V3                                                     | 1         | 0.1%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.1%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.1%    |
| BLUTRONICS BLUDRIVE II CCID                                                  | 1         | 0.1%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.1%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 15490     | 69.11%  |
| 1     | 5655      | 25.23%  |
| 2     | 1003      | 4.48%   |
| 3     | 181       | 0.81%   |
| 4     | 40        | 0.18%   |
| 5     | 25        | 0.11%   |
| 6     | 10        | 0.04%   |
| 7     | 5         | 0.02%   |
| 8     | 3         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 2263      | 27.88%  |
| Graphics card            | 1324      | 16.31%  |
| Net/wireless             | 1318      | 16.24%  |
| Chipcard                 | 872       | 10.74%  |
| Multimedia controller    | 576       | 7.1%    |
| Communication controller | 519       | 6.39%   |
| Unassigned class         | 250       | 3.08%   |
| Storage                  | 181       | 2.23%   |
| Camera                   | 168       | 2.07%   |
| Bluetooth                | 153       | 1.88%   |
| Sound                    | 126       | 1.55%   |
| Net/ethernet             | 96        | 1.18%   |
| Network                  | 56        | 0.69%   |
| Card reader              | 56        | 0.69%   |
| Modem                    | 49        | 0.6%    |
| Storage/raid             | 31        | 0.38%   |
| Storage/ide              | 20        | 0.25%   |
| Firewire controller      | 16        | 0.2%    |
| Dvb card                 | 16        | 0.2%    |
| Storage/nvme             | 7         | 0.09%   |
| Storage/ata              | 7         | 0.09%   |
| Tv card                  | 6         | 0.07%   |
| Flash memory             | 5         | 0.06%   |
| Wireless                 | 1         | 0.01%   |
| Unclassified device      | 1         | 0.01%   |


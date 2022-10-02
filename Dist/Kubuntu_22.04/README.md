Kubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_22.04/Notebook/README.md).

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

Total: 423

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [ed9cd240cc](https://linux-hardware.org/?probe=ed9cd240cc) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [8e77417877](https://linux-hardware.org/?probe=8e77417877) | Sep 28, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ca8786a47](https://linux-hardware.org/?probe=1ca8786a47) | Sep 13, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [20b4c0a5b2](https://linux-hardware.org/?probe=20b4c0a5b2) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [a27d14af07](https://linux-hardware.org/?probe=a27d14af07) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Dell          | Latitude 7430               | Notebook    | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Acer          | Predator G3-571             | Notebook    | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [58062d2ad3](https://linux-hardware.org/?probe=58062d2ad3) | Sep 06, 2022 |
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [45dceb981a](https://linux-hardware.org/?probe=45dceb981a) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| HP            | Notebook                    | Notebook    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [33784347f5](https://linux-hardware.org/?probe=33784347f5) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | Notebook    | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [54f5dc3cf8](https://linux-hardware.org/?probe=54f5dc3cf8) | Aug 26, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Dell          | Latitude 5590               | Notebook    | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [9c53dae23e](https://linux-hardware.org/?probe=9c53dae23e) | Aug 10, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Intel         | Unknown                     | Notebook    | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| HP            | 8459                        | Desktop     | [a1d6ae45cb](https://linux-hardware.org/?probe=a1d6ae45cb) | Jul 28, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| Dell          | Latitude 5590               | Notebook    | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [8b027b07d9](https://linux-hardware.org/?probe=8b027b07d9) | Jul 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [1177e7dbe0](https://linux-hardware.org/?probe=1177e7dbe0) | Jul 21, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | Desktop     | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | Notebook    | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | 8459                        | Desktop     | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | Desktop     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [66b40738ff](https://linux-hardware.org/?probe=66b40738ff) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| Jumper        | EZpad                       | Notebook    | [3ea5b3080d](https://linux-hardware.org/?probe=3ea5b3080d) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| Haier         | A1420EM                     | Notebook    | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | Notebook    | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | Notebook    | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Jumper        | EZpad                       | Notebook    | [b1a0e53c08](https://linux-hardware.org/?probe=b1a0e53c08) | Jun 16, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [91316a0904](https://linux-hardware.org/?probe=91316a0904) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | Notebook    | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | Notebook    | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | Notebook    | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3a58a9889b](https://linux-hardware.org/?probe=3a58a9889b) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [acf0372bdc](https://linux-hardware.org/?probe=acf0372bdc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | Notebook    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [c8e2700624](https://linux-hardware.org/?probe=c8e2700624) | Jun 02, 2022 |
| Dell          | Latitude 7420               | Notebook    | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | Notebook    | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | Notebook    | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [540416deba](https://linux-hardware.org/?probe=540416deba) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [63a10ce1e0](https://linux-hardware.org/?probe=63a10ce1e0) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| HP            | ProBook 6470b               | Notebook    | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | Desktop     | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | Notebook    | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | Notebook    | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ef1e814871](https://linux-hardware.org/?probe=ef1e814871) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3ea846ae2a](https://linux-hardware.org/?probe=3ea846ae2a) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | Notebook    | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2015948e6d](https://linux-hardware.org/?probe=2015948e6d) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2c7c189ffa](https://linux-hardware.org/?probe=2c7c189ffa) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-47-generic          | 35        | 10.61%  |
| 5.15.0-46-generic          | 31        | 9.39%   |
| 5.15.0-41-generic          | 29        | 8.79%   |
| 5.15.0-40-generic          | 26        | 7.88%   |
| 5.15.0-27-generic          | 24        | 7.27%   |
| 5.15.0-25-generic          | 21        | 6.36%   |
| 5.15.0-48-generic          | 19        | 5.76%   |
| 5.15.0-43-generic          | 19        | 5.76%   |
| 5.15.0-33-generic          | 18        | 5.45%   |
| 5.15.0-37-generic          | 10        | 3.03%   |
| 5.15.0-30-generic          | 10        | 3.03%   |
| 5.15.0-39-generic          | 8         | 2.42%   |
| 5.15.0-35-generic          | 6         | 1.82%   |
| 5.15.0-18-generic          | 5         | 1.52%   |
| 5.15.0-48-lowlatency       | 4         | 1.21%   |
| 5.15.0-46-lowlatency       | 4         | 1.21%   |
| 5.15.0-43-lowlatency       | 4         | 1.21%   |
| 5.15.0-30-lowlatency       | 3         | 0.91%   |
| 5.15.0-27-lowlatency       | 3         | 0.91%   |
| 5.13.0-19-generic          | 3         | 0.91%   |
| 5.19.5-051905-generic      | 2         | 0.61%   |
| 5.18.10-051810-generic     | 2         | 0.61%   |
| 5.15.0-47-lowlatency       | 2         | 0.61%   |
| 5.15.0-32-generic          | 2         | 0.61%   |
| 5.15.0-23-generic          | 2         | 0.61%   |
| 5.15.0-10033-tuxedo        | 2         | 0.61%   |
| 6.0.0-060000rc3-generic    | 1         | 0.3%    |
| 5.4.0-122-generic          | 1         | 0.3%    |
| 5.19.2-051902-generic      | 1         | 0.3%    |
| 5.18.6-051806-generic      | 1         | 0.3%    |
| 5.18.4-xanmod1             | 1         | 0.3%    |
| 5.18.4-vitodoc             | 1         | 0.3%    |
| 5.18.15-051815-generic     | 1         | 0.3%    |
| 5.18.12-051812-generic     | 1         | 0.3%    |
| 5.17.6-051706-generic      | 1         | 0.3%    |
| 5.17.5-051705-generic      | 1         | 0.3%    |
| 5.17.4-051704-generic      | 1         | 0.3%    |
| 5.17.2-051702-generic      | 1         | 0.3%    |
| 5.17.14-xanmod1            | 1         | 0.3%    |
| 5.17.0-12.1-liquorix-amd64 | 1         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 286       | 90.22%  |
| 5.17.0   | 4         | 1.26%   |
| 5.13.0   | 4         | 1.26%   |
| 5.19.5   | 2         | 0.63%   |
| 5.18.4   | 2         | 0.63%   |
| 5.18.10  | 2         | 0.63%   |
| 6.0.0    | 1         | 0.32%   |
| 5.4.0    | 1         | 0.32%   |
| 5.19.2   | 1         | 0.32%   |
| 5.18.6   | 1         | 0.32%   |
| 5.18.15  | 1         | 0.32%   |
| 5.18.12  | 1         | 0.32%   |
| 5.17.6   | 1         | 0.32%   |
| 5.17.5   | 1         | 0.32%   |
| 5.17.4   | 1         | 0.32%   |
| 5.17.2   | 1         | 0.32%   |
| 5.17.14  | 1         | 0.32%   |
| 5.16.2   | 1         | 0.32%   |
| 5.16.0   | 1         | 0.32%   |
| 5.15.65  | 1         | 0.32%   |
| 5.15.34  | 1         | 0.32%   |
| 5.15.13  | 1         | 0.32%   |
| 5.10.123 | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 288       | 91.14%  |
| 5.17    | 9         | 2.85%   |
| 5.18    | 7         | 2.22%   |
| 5.13    | 4         | 1.27%   |
| 5.19    | 3         | 0.95%   |
| 5.16    | 2         | 0.63%   |
| 6.0     | 1         | 0.32%   |
| 5.4     | 1         | 0.32%   |
| 5.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 311       | 99.68%  |
| aarch64 | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 310       | 99.36%  |
| MATE    | 1         | 0.32%   |
| GNUstep | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 293       | 93.61%  |
| Wayland | 16        | 5.11%   |
| Tty     | 4         | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 233       | 74.2%   |
| Unknown | 60        | 19.11%  |
| GDM3    | 17        | 5.41%   |
| LightDM | 3         | 0.96%   |
| LXDM    | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 164       | 52.4%   |
| ru_RU   | 16        | 5.11%   |
| en_GB   | 16        | 5.11%   |
| de_DE   | 16        | 5.11%   |
| it_IT   | 15        | 4.79%   |
| fr_FR   | 13        | 4.15%   |
| en_AU   | 10        | 3.19%   |
| en_CA   | 7         | 2.24%   |
| pt_BR   | 6         | 1.92%   |
| pl_PL   | 6         | 1.92%   |
| es_ES   | 6         | 1.92%   |
| en_IN   | 5         | 1.6%    |
| en_ZA   | 3         | 0.96%   |
| en_SG   | 3         | 0.96%   |
| en_PH   | 3         | 0.96%   |
| sl_SI   | 2         | 0.64%   |
| es_AR   | 2         | 0.64%   |
| en_NZ   | 2         | 0.64%   |
| tr_TR   | 1         | 0.32%   |
| ru_UA   | 1         | 0.32%   |
| nl_NL   | 1         | 0.32%   |
| nl_BE   | 1         | 0.32%   |
| hu_HU   | 1         | 0.32%   |
| et_EE   | 1         | 0.32%   |
| es_MX   | 1         | 0.32%   |
| es_EC   | 1         | 0.32%   |
| es_CR   | 1         | 0.32%   |
| es_CO   | 1         | 0.32%   |
| en_IL   | 1         | 0.32%   |
| en_AG   | 1         | 0.32%   |
| el_GR   | 1         | 0.32%   |
| de_CH   | 1         | 0.32%   |
| de_AT   | 1         | 0.32%   |
| Default | 1         | 0.32%   |
| cs_CZ   | 1         | 0.32%   |
| C       | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 159       | 50.32%  |
| EFI  | 157       | 49.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 277       | 88.78%  |
| Overlay | 15        | 4.81%   |
| Btrfs   | 15        | 4.81%   |
| Xfs     | 3         | 0.96%   |
| Zfs     | 1         | 0.32%   |
| Ext3    | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 168       | 53.5%   |
| Unknown | 133       | 42.36%  |
| MBR     | 13        | 4.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 284       | 90.45%  |
| Yes       | 30        | 9.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 188       | 60.06%  |
| Yes       | 125       | 39.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 50        | 16.03%  |
| Lenovo                         | 48        | 15.38%  |
| Hewlett-Packard                | 41        | 13.14%  |
| Dell                           | 37        | 11.86%  |
| MSI                            | 24        | 7.69%   |
| Gigabyte Technology            | 24        | 7.69%   |
| Acer                           | 12        | 3.85%   |
| ASRock                         | 11        | 3.53%   |
| Apple                          | 7         | 2.24%   |
| Toshiba                        | 5         | 1.6%    |
| HUAWEI                         | 4         | 1.28%   |
| TUXEDO                         | 3         | 0.96%   |
| Supermicro                     | 3         | 0.96%   |
| Samsung Electronics            | 3         | 0.96%   |
| Google                         | 3         | 0.96%   |
| System76                       | 2         | 0.64%   |
| Sony                           | 2         | 0.64%   |
| HONOR                          | 2         | 0.64%   |
| Fujitsu                        | 2         | 0.64%   |
| Biostar                        | 2         | 0.64%   |
| AZW                            | 2         | 0.64%   |
| Unknown                        | 2         | 0.64%   |
| ZOTAC                          | 1         | 0.32%   |
| Timi                           | 1         | 0.32%   |
| Standard                       | 1         | 0.32%   |
| SLIMBOOK                       | 1         | 0.32%   |
| SK hynix                       | 1         | 0.32%   |
| Shuttle                        | 1         | 0.32%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.32%   |
| Schenker                       | 1         | 0.32%   |
| Razer                          | 1         | 0.32%   |
| Positivo                       | 1         | 0.32%   |
| Pegatron                       | 1         | 0.32%   |
| Panasonic                      | 1         | 0.32%   |
| OEM                            | 1         | 0.32%   |
| Microsoft                      | 1         | 0.32%   |
| LG Electronics                 | 1         | 0.32%   |
| Jumper                         | 1         | 0.32%   |
| Intel                          | 1         | 0.32%   |
| Huanan                         | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 5         | 1.6%    |
| Unknown                            | 5         | 1.6%    |
| Gigabyte B450M DS3H                | 3         | 0.96%   |
| Supermicro SKAGIT09                | 2         | 0.64%   |
| MSI MS-7C56                        | 2         | 0.64%   |
| MSI MS-7B86                        | 2         | 0.64%   |
| MSI MS-7B79                        | 2         | 0.64%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 2         | 0.64%   |
| HUAWEI CREM-WXX9                   | 2         | 0.64%   |
| HP ProBook 6470b                   | 2         | 0.64%   |
| Gigabyte X570 GAMING X             | 2         | 0.64%   |
| Gigabyte B450 I AORUS PRO WIFI     | 2         | 0.64%   |
| Dell XPS 15 9560                   | 2         | 0.64%   |
| ASUS ROG ZENITH EXTREME            | 2         | 0.64%   |
| ASUS ROG STRIX B550-F GAMING       | 2         | 0.64%   |
| ZOTAC ZBOXNANO-CI520NANO/CI540NANO | 1         | 0.32%   |
| TUXEDO Stellaris AMD Gen3 (CZN)    | 1         | 0.32%   |
| TUXEDO Polaris 15 AMD Gen1         | 1         | 0.32%   |
| TUXEDO InfinityBook S 15 Gen6      | 1         | 0.32%   |
| Toshiba TECRA S11                  | 1         | 0.32%   |
| Toshiba Satellite P70-B            | 1         | 0.32%   |
| Toshiba Satellite L850             | 1         | 0.32%   |
| Toshiba Satellite L655             | 1         | 0.32%   |
| Toshiba Satellite C650D            | 1         | 0.32%   |
| Timi Mi Laptop Air 12.5            | 1         | 0.32%   |
| System76 Lemur Ultra               | 1         | 0.32%   |
| System76 Kudu Professional         | 1         | 0.32%   |
| Supermicro X8ST3                   | 1         | 0.32%   |
| Sony VGN-NR11Z_T                   | 1         | 0.32%   |
| Sony SVE1512J6EW                   | 1         | 0.32%   |
| SLIMBOOK PROX15-AMD                | 1         | 0.32%   |
| SK hynix Onnyx III                 | 1         | 0.32%   |
| Shuttle NC01U                      | 1         | 0.32%   |
| Shanghai Zhaoxin ZXE CRB           | 1         | 0.32%   |
| Schenker XMG APEX (Mid 2021)       | 1         | 0.32%   |
| Samsung 870Z5E/880Z5E/680Z5E       | 1         | 0.32%   |
| Samsung 300E4C/300E5C/300E7C       | 1         | 0.32%   |
| Samsung 270E5G/270E5U              | 1         | 0.32%   |
| Razer Blade 15 Mid 2019-Base       | 1         | 0.32%   |
| Positivo POS-PARS760GCD            | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 18        | 5.77%   |
| ASUS ROG            | 12        | 3.85%   |
| Lenovo IdeaPad      | 11        | 3.53%   |
| Dell Latitude       | 11        | 3.53%   |
| HP Pavilion         | 9         | 2.88%   |
| Dell Inspiron       | 7         | 2.24%   |
| Dell XPS            | 6         | 1.92%   |
| Acer Aspire         | 6         | 1.92%   |
| Lenovo ThinkCentre  | 5         | 1.6%    |
| HP ProBook          | 5         | 1.6%    |
| HP EliteBook        | 5         | 1.6%    |
| Dell OptiPlex       | 5         | 1.6%    |
| ASUS VivoBook       | 5         | 1.6%    |
| ASUS All            | 5         | 1.6%    |
| Unknown             | 5         | 1.6%    |
| Toshiba Satellite   | 4         | 1.28%   |
| Lenovo ThinkBook    | 4         | 1.28%   |
| ASUS TUF            | 4         | 1.28%   |
| ASUS PRIME          | 4         | 1.28%   |
| Lenovo Yoga         | 3         | 0.96%   |
| HP Laptop           | 3         | 0.96%   |
| Gigabyte X570       | 3         | 0.96%   |
| Gigabyte B450M      | 3         | 0.96%   |
| Supermicro SKAGIT09 | 2         | 0.64%   |
| MSI MS-7C56         | 2         | 0.64%   |
| MSI MS-7B86         | 2         | 0.64%   |
| MSI MS-7B79         | 2         | 0.64%   |
| Lenovo Legion       | 2         | 0.64%   |
| HUAWEI CREM-WXX9    | 2         | 0.64%   |
| HP ProDesk          | 2         | 0.64%   |
| HP OMEN             | 2         | 0.64%   |
| HP ENVY             | 2         | 0.64%   |
| Gigabyte H410M      | 2         | 0.64%   |
| Gigabyte B450       | 2         | 0.64%   |
| Fujitsu ESPRIMO     | 2         | 0.64%   |
| Dell Vostro         | 2         | 0.64%   |
| Dell Precision      | 2         | 0.64%   |
| ASUS ZenBook        | 2         | 0.64%   |
| ASRock B550         | 2         | 0.64%   |
| Apple MacBookPro11  | 2         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 54        | 17.31%  |
| 2021    | 51        | 16.35%  |
| 2019    | 32        | 10.26%  |
| 2018    | 26        | 8.33%   |
| 2012    | 22        | 7.05%   |
| 2022    | 16        | 5.13%   |
| 2017    | 16        | 5.13%   |
| 2016    | 16        | 5.13%   |
| 2014    | 16        | 5.13%   |
| 2013    | 15        | 4.81%   |
| 2015    | 14        | 4.49%   |
| 2011    | 14        | 4.49%   |
| 2010    | 9         | 2.88%   |
| 2008    | 4         | 1.28%   |
| 2007    | 4         | 1.28%   |
| 2009    | 2         | 0.64%   |
| Unknown | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 173       | 55.45%  |
| Desktop        | 119       | 38.14%  |
| Convertible    | 11        | 3.53%   |
| Mini pc        | 4         | 1.28%   |
| All in one     | 2         | 0.64%   |
| System on chip | 1         | 0.32%   |
| Tablet         | 1         | 0.32%   |
| Server         | 1         | 0.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 283       | 90.42%  |
| Enabled  | 30        | 9.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 309       | 99.04%  |
| Yes  | 3         | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 106       | 33.65%  |
| 4.01-8.0    | 60        | 19.05%  |
| 8.01-16.0   | 60        | 19.05%  |
| 32.01-64.0  | 40        | 12.7%   |
| 3.01-4.0    | 26        | 8.25%   |
| 64.01-256.0 | 15        | 4.76%   |
| 24.01-32.0  | 5         | 1.59%   |
| 2.01-3.0    | 3         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 95        | 29.05%  |
| 4.01-8.0   | 75        | 22.94%  |
| 3.01-4.0   | 71        | 21.71%  |
| 1.01-2.0   | 63        | 19.27%  |
| 8.01-16.0  | 21        | 6.42%   |
| 32.01-64.0 | 1         | 0.31%   |
| 0.51-1.0   | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 161       | 50.63%  |
| 2      | 92        | 28.93%  |
| 3      | 34        | 10.69%  |
| 4      | 13        | 4.09%   |
| 5      | 10        | 3.14%   |
| 6      | 5         | 1.57%   |
| 11     | 1         | 0.31%   |
| 9      | 1         | 0.31%   |
| 7      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 227       | 72.76%  |
| Yes       | 85        | 27.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 81.09%  |
| No        | 59        | 18.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 262       | 83.71%  |
| No        | 51        | 16.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 227       | 72.06%  |
| No        | 88        | 27.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 59        | 18.91%  |
| Russia       | 26        | 8.33%   |
| Germany      | 24        | 7.69%   |
| Italy        | 22        | 7.05%   |
| France       | 19        | 6.09%   |
| UK           | 15        | 4.81%   |
| Poland       | 12        | 3.85%   |
| Brazil       | 12        | 3.85%   |
| Spain        | 9         | 2.88%   |
| Australia    | 8         | 2.56%   |
| Switzerland  | 7         | 2.24%   |
| Canada       | 7         | 2.24%   |
| Netherlands  | 6         | 1.92%   |
| India        | 6         | 1.92%   |
| Slovenia     | 4         | 1.28%   |
| Philippines  | 4         | 1.28%   |
| Indonesia    | 4         | 1.28%   |
| Sweden       | 3         | 0.96%   |
| South Africa | 3         | 0.96%   |
| Singapore    | 3         | 0.96%   |
| New Zealand  | 3         | 0.96%   |
| Mexico       | 3         | 0.96%   |
| Greece       | 3         | 0.96%   |
| Czechia      | 3         | 0.96%   |
| Bulgaria     | 3         | 0.96%   |
| Argentina    | 3         | 0.96%   |
| Thailand     | 2         | 0.64%   |
| Serbia       | 2         | 0.64%   |
| Portugal     | 2         | 0.64%   |
| Malaysia     | 2         | 0.64%   |
| Hungary      | 2         | 0.64%   |
| Estonia      | 2         | 0.64%   |
| Ecuador      | 2         | 0.64%   |
| Denmark      | 2         | 0.64%   |
| China        | 2         | 0.64%   |
| Belgium      | 2         | 0.64%   |
| Austria      | 2         | 0.64%   |
| Ukraine      | 1         | 0.32%   |
| UAE          | 1         | 0.32%   |
| Turkey       | 1         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 7         | 2.21%   |
| St Petersburg  | 5         | 1.58%   |
| Milan          | 4         | 1.26%   |
| Berlin         | 4         | 1.26%   |
| Wroclaw        | 3         | 0.95%   |
| Washington     | 3         | 0.95%   |
| Vladivostok    | 3         | 0.95%   |
| Singapore      | 3         | 0.95%   |
| Sao Paulo      | 3         | 0.95%   |
| Bougival       | 3         | 0.95%   |
| Bengaluru      | 3         | 0.95%   |
| Zurich         | 2         | 0.63%   |
| Vienna         | 2         | 0.63%   |
| Turin          | 2         | 0.63%   |
| Tallinn        | 2         | 0.63%   |
| Sydney         | 2         | 0.63%   |
| Sofia          | 2         | 0.63%   |
| Rio de Janeiro | 2         | 0.63%   |
| Prague         | 2         | 0.63%   |
| Parma          | 2         | 0.63%   |
| Nîmes         | 2         | 0.63%   |
| Munich         | 2         | 0.63%   |
| Marseille      | 2         | 0.63%   |
| Madrid         | 2         | 0.63%   |
| Katowice       | 2         | 0.63%   |
| Katerini       | 2         | 0.63%   |
| Johannesburg   | 2         | 0.63%   |
| Jakarta        | 2         | 0.63%   |
| Jacksonville   | 2         | 0.63%   |
| Fucecchio      | 2         | 0.63%   |
| Derby          | 2         | 0.63%   |
| Dallas         | 2         | 0.63%   |
| Canberra       | 2         | 0.63%   |
| Brooklyn       | 2         | 0.63%   |
| Brasília      | 2         | 0.63%   |
| Belgrade       | 2         | 0.63%   |
| Auckland       | 2         | 0.63%   |
| Zwijndrecht    | 1         | 0.32%   |
| Zagreb         | 1         | 0.32%   |
| Zaandam        | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 78        | 100    | 15.76%  |
| WDC                            | 62        | 88     | 12.53%  |
| Seagate                        | 52        | 95     | 10.51%  |
| Kingston                       | 38        | 42     | 7.68%   |
| Toshiba                        | 34        | 40     | 6.87%   |
| SanDisk                        | 28        | 30     | 5.66%   |
| SK hynix                       | 20        | 22     | 4.04%   |
| Crucial                        | 17        | 21     | 3.43%   |
| Intel                          | 16        | 20     | 3.23%   |
| Unknown                        | 15        | 20     | 3.03%   |
| Hitachi                        | 15        | 15     | 3.03%   |
| HGST                           | 8         | 9      | 1.62%   |
| Patriot                        | 7         | 7      | 1.41%   |
| Micron Technology              | 7         | 7      | 1.41%   |
| KIOXIA                         | 7         | 7      | 1.41%   |
| China                          | 7         | 8      | 1.41%   |
| A-DATA Technology              | 7         | 8      | 1.41%   |
| Apple                          | 5         | 6      | 1.01%   |
| PNY                            | 4         | 4      | 0.81%   |
| Transcend                      | 3         | 4      | 0.61%   |
| SSSTC                          | 3         | 3      | 0.61%   |
| Phison Electronics             | 3         | 3      | 0.61%   |
| Phison                         | 3         | 3      | 0.61%   |
| Micron/Crucial Technology      | 3         | 4      | 0.61%   |
| LITEON                         | 3         | 3      | 0.61%   |
| Unknown                        | 3         | 3      | 0.61%   |
| Verbatim                       | 2         | 2      | 0.4%    |
| USB3.0                         | 2         | 2      | 0.4%    |
| Silicon Motion                 | 2         | 2      | 0.4%    |
| Realtek Semiconductor          | 2         | 2      | 0.4%    |
| KODAK                          | 2         | 2      | 0.4%    |
| JMicron Technology             | 2         | 2      | 0.4%    |
| Gigabyte Technology            | 2         | 2      | 0.4%    |
| Emtec                          | 2         | 2      | 0.4%    |
| Corsair                        | 2         | 3      | 0.4%    |
| XPG                            | 1         | 1      | 0.2%    |
| UMIS                           | 1         | 1      | 0.2%    |
| tecmiyo                        | 1         | 2      | 0.2%    |
| Team                           | 1         | 1      | 0.2%    |
| Solid State Storage Technology | 1         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 9         | 1.61%   |
| Seagate ST4000DM004-2CV104 4TB         | 6         | 1.07%   |
| Crucial CT500MX500SSD1 500GB           | 5         | 0.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 4         | 0.72%   |
| Toshiba DT01ACA100 1TB                 | 4         | 0.72%   |
| SanDisk NVMe SSD Drive 500GB           | 4         | 0.72%   |
| Samsung SSD 860 QVO 1TB                | 4         | 0.72%   |
| Samsung SSD 860 EVO 500GB              | 4         | 0.72%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.72%   |
| Kingston SA2000M81000G 1TB             | 4         | 0.72%   |
| WDC WD10EZEX-22MFCA0 1TB               | 3         | 0.54%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.54%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.54%   |
| Seagate Expansion 1TB                  | 3         | 0.54%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.54%   |
| Samsung SSD 980 1TB                    | 3         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.54%   |
| Samsung SSD 870 EVO 1TB                | 3         | 0.54%   |
| Samsung SSD 860 EVO 1TB                | 3         | 0.54%   |
| Samsung SSD 850 EVO 500GB              | 3         | 0.54%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.54%   |
| Patriot Burst 240GB SSD                | 3         | 0.54%   |
| Kingston SV300S37A120G 120GB SSD       | 3         | 0.54%   |
| Hitachi HTS547550A9E384 500GB          | 3         | 0.54%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.54%   |
| Unknown                                | 3         | 0.54%   |
| WDC WD5000AADS-00S9B0 500GB            | 2         | 0.36%   |
| WDC WD40EFAX-68JH4N1 4TB               | 2         | 0.36%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.36%   |
| WDC PC SN730 SDBPNTY-512G              | 2         | 0.36%   |
| USB3.0 Super Speed 240GB               | 2         | 0.36%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.36%   |
| Toshiba HDWD110 1TB                    | 2         | 0.36%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 2         | 0.36%   |
| SK hynix PC801 NVMe 1TB                | 2         | 0.36%   |
| SK hynix BC711 HFM512GD3JX013N 512GB   | 2         | 0.36%   |
| Seagate ST4000VN008-2DR166 4TB         | 2         | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB         | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 88     | 33.78%  |
| WDC                 | 43        | 56     | 29.05%  |
| Toshiba             | 19        | 22     | 12.84%  |
| Hitachi             | 15        | 15     | 10.14%  |
| HGST                | 8         | 9      | 5.41%   |
| Samsung Electronics | 6         | 6      | 4.05%   |
| USB3.0              | 2         | 2      | 1.35%   |
| Unknown             | 1         | 1      | 0.68%   |
| SAGE                | 1         | 1      | 0.68%   |
| JMicron Technology  | 1         | 1      | 0.68%   |
| IET                 | 1         | 1      | 0.68%   |
| HGST HTS            | 1         | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 51     | 24.02%  |
| Kingston            | 26        | 27     | 14.53%  |
| SanDisk             | 16        | 17     | 8.94%   |
| Crucial             | 15        | 17     | 8.38%   |
| WDC                 | 11        | 15     | 6.15%   |
| Patriot             | 7         | 7      | 3.91%   |
| China               | 6         | 7      | 3.35%   |
| Intel               | 5         | 5      | 2.79%   |
| A-DATA Technology   | 5         | 6      | 2.79%   |
| Toshiba             | 4         | 6      | 2.23%   |
| PNY                 | 3         | 3      | 1.68%   |
| Micron Technology   | 3         | 3      | 1.68%   |
| LITEON              | 3         | 3      | 1.68%   |
| Apple               | 3         | 3      | 1.68%   |
| Verbatim            | 2         | 2      | 1.12%   |
| Transcend           | 2         | 2      | 1.12%   |
| KODAK               | 2         | 2      | 1.12%   |
| tecmiyo             | 1         | 2      | 0.56%   |
| Team                | 1         | 1      | 0.56%   |
| Smartbuy            | 1         | 1      | 0.56%   |
| Smart               | 1         | 1      | 0.56%   |
| SK hynix            | 1         | 1      | 0.56%   |
| Plextor             | 1         | 1      | 0.56%   |
| OCZ                 | 1         | 1      | 0.56%   |
| Netac               | 1         | 1      | 0.56%   |
| Maxtor              | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| KingFast            | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| INNOVATION IT       | 1         | 1      | 0.56%   |
| INDMEM              | 1         | 1      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| Emtec               | 1         | 1      | 0.56%   |
| Drevo               | 1         | 1      | 0.56%   |
| Dogfish             | 1         | 1      | 0.56%   |
| Corsair             | 1         | 1      | 0.56%   |
| BAITITON            | 1         | 1      | 0.56%   |
| Apacer              | 1         | 1      | 0.56%   |
| Aireye              | 1         | 1      | 0.56%   |
| Unknown             | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 151       | 200    | 34.47%  |
| NVMe    | 145       | 195    | 33.11%  |
| HDD     | 122       | 203    | 27.85%  |
| MMC     | 17        | 21     | 3.88%   |
| Unknown | 3         | 3      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 203       | 374    | 52.59%  |
| NVMe | 144       | 193    | 37.31%  |
| SAS  | 22        | 34     | 5.7%    |
| MMC  | 17        | 21     | 4.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 152       | 209    | 52.41%  |
| 0.51-1.0   | 81        | 109    | 27.93%  |
| 1.01-2.0   | 23        | 30     | 7.93%   |
| 3.01-4.0   | 18        | 30     | 6.21%   |
| 2.01-3.0   | 7         | 9      | 2.41%   |
| 4.01-10.0  | 7         | 14     | 2.41%   |
| 10.01-20.0 | 2         | 2      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 23.2%   |
| 251-500        | 65        | 20.38%  |
| 501-1000       | 58        | 18.18%  |
| 1001-2000      | 43        | 13.48%  |
| More than 3000 | 24        | 7.52%   |
| 2001-3000      | 20        | 6.27%   |
| 51-100         | 15        | 4.7%    |
| 1-20           | 13        | 4.08%   |
| 21-50          | 6         | 1.88%   |
| Unknown        | 1         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 78        | 24.38%  |
| 101-250        | 51        | 15.94%  |
| 21-50          | 48        | 15%     |
| 251-500        | 40        | 12.5%   |
| 51-100         | 35        | 10.94%  |
| 501-1000       | 34        | 10.63%  |
| 1001-2000      | 14        | 4.38%   |
| More than 3000 | 11        | 3.44%   |
| 2001-3000      | 8         | 2.5%    |
| Unknown        | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000AVVS-63M8B0 500GB                         | 1         | 1      | 3.33%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.33%   |
| tecmiyo SATA SSD 128GB                              | 1         | 2      | 3.33%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 3.33%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 3.33%   |
| Seagate ST3160827AS 160GB                           | 1         | 1      | 3.33%   |
| Seagate ST31500341AS 1TB                            | 1         | 1      | 3.33%   |
| Seagate ST31000524AS 1TB                            | 1         | 2      | 3.33%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 3.33%   |
| Seagate ST1000DM003-1SB102 1TB                      | 1         | 1      | 3.33%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 1      | 3.33%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 840 Series 250GB            | 1         | 1      | 3.33%   |
| Samsung Electronics HM321HI 320GB                   | 1         | 1      | 3.33%   |
| Samsung Electronics HD103SI 1TB                     | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 3.33%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 3.33%   |
| Hitachi HDP725050GLA360 500GB                       | 1         | 1      | 3.33%   |
| Hitachi HCT721010SLA360 1TB                         | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.33%   |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 3.33%   |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 3.33%   |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 27.59%  |
| Samsung Electronics | 4         | 4      | 13.79%  |
| Hitachi             | 4         | 4      | 13.79%  |
| WDC                 | 2         | 2      | 6.9%    |
| SK hynix            | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| tecmiyo             | 1         | 2      | 3.45%   |
| SanDisk             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| BAITITON            | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 42.11%  |
| Hitachi             | 4         | 4      | 21.05%  |
| WDC                 | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 21     | 66.67%  |
| SSD  | 7         | 9      | 25.93%  |
| NVMe | 2         | 2      | 7.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 171       | 292    | 49%     |
| Detected | 150       | 296    | 42.98%  |
| Malfunc  | 27        | 32     | 7.74%   |
| Failed   | 1         | 2      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 178       | 40.83%  |
| AMD                            | 81        | 18.58%  |
| Samsung Electronics            | 38        | 8.72%   |
| SanDisk                        | 26        | 5.96%   |
| SK hynix                       | 19        | 4.36%   |
| Kingston Technology Company    | 15        | 3.44%   |
| Toshiba America Info Systems   | 12        | 2.75%   |
| ASMedia Technology             | 10        | 2.29%   |
| Phison Electronics             | 9         | 2.06%   |
| Micron/Crucial Technology      | 6         | 1.38%   |
| KIOXIA                         | 6         | 1.38%   |
| Solid State Storage Technology | 4         | 0.92%   |
| Micron Technology              | 4         | 0.92%   |
| JMicron Technology             | 4         | 0.92%   |
| Silicon Motion                 | 3         | 0.69%   |
| Seagate Technology             | 3         | 0.69%   |
| ADATA Technology               | 3         | 0.69%   |
| Realtek Semiconductor          | 2         | 0.46%   |
| Marvell Technology Group       | 2         | 0.46%   |
| LSI Logic / Symbios Logic      | 2         | 0.46%   |
| Apple                          | 2         | 0.46%   |
| Zhaoxin                        | 1         | 0.23%   |
| VIA Technologies               | 1         | 0.23%   |
| Unknown                        | 1         | 0.23%   |
| Union Memory (Shenzhen)        | 1         | 0.23%   |
| Silicon Image                  | 1         | 0.23%   |
| Shenzhen Longsys Electronics   | 1         | 0.23%   |
| Nvidia                         | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 58        | 11.6%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 3.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 3.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 15        | 3%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 2.6%    |
| SK hynix Gold P31 SSD                                                          | 11        | 2.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 2.2%    |
| Samsung NVMe SSD Controller 980                                                | 10        | 2%      |
| SanDisk Non-Volatile memory controller                                         | 9         | 1.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.8%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 1.6%    |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7         | 1.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.2%    |
| Intel SSD 660P Series                                                          | 6         | 1.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1%      |
| Kingston Company Company Non-Volatile memory controller                        | 5         | 1%      |
| Kingston Company OM3PDP3 NVMe SSD                                              | 5         | 1%      |
| Kingston Company A2000 NVMe SSD                                                | 5         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1%      |
| Solid State Storage Non-Volatile memory controller                             | 4         | 0.8%    |
| SK hynix Non-Volatile memory controller                                        | 4         | 0.8%    |
| Phison E12 NVMe Controller                                                     | 4         | 0.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 0.8%    |
| Micron Non-Volatile memory controller                                          | 4         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 0.8%    |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.8%    |
| Intel Non-Volatile memory controller                                           | 4         | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 232       | 53.95%  |
| NVMe | 144       | 33.49%  |
| RAID | 33        | 7.67%   |
| IDE  | 21        | 4.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 211       | 67.63%  |
| AMD          | 99        | 31.73%  |
| CentaurHauls | 1         | 0.32%   |
| ARM          | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 8         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 8         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 6         | 1.92%   |
| Intel 12th Gen Core i7-12700H                  | 6         | 1.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 5         | 1.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics         | 5         | 1.6%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 5         | 1.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz              | 4         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 4         | 1.28%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 4         | 1.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 4         | 1.28%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 4         | 1.28%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3         | 0.96%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz             | 3         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 3         | 0.96%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 3         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 3         | 0.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 0.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 3         | 0.96%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 3         | 0.96%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3         | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz              | 2         | 0.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2         | 0.64%   |
| Intel Core i7-4770S CPU @ 3.10GHz              | 2         | 0.64%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz             | 2         | 0.64%   |
| Intel Core i7-3612QM CPU @ 2.10GHz             | 2         | 0.64%   |
| Intel Core i7-2670QM CPU @ 2.20GHz             | 2         | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 2         | 0.64%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 2         | 0.64%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2         | 0.64%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2         | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 2         | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 2         | 0.64%   |
| Intel Celeron CPU N3450 @ 1.10GHz              | 2         | 0.64%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz        | 2         | 0.64%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz        | 2         | 0.64%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2         | 0.64%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2         | 0.64%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 66        | 21.15%  |
| Intel Core i5           | 54        | 17.31%  |
| Other                   | 44        | 14.1%   |
| AMD Ryzen 5             | 31        | 9.94%   |
| AMD Ryzen 7             | 25        | 8.01%   |
| AMD Ryzen 9             | 12        | 3.85%   |
| Intel Core i3           | 11        | 3.53%   |
| Intel Celeron           | 11        | 3.53%   |
| AMD Ryzen 3             | 8         | 2.56%   |
| Intel Xeon              | 7         | 2.24%   |
| Intel Core 2 Duo        | 6         | 1.92%   |
| Intel Pentium           | 5         | 1.6%    |
| AMD FX                  | 4         | 1.28%   |
| AMD Ryzen Threadripper  | 3         | 0.96%   |
| AMD Ryzen 7 PRO         | 3         | 0.96%   |
| Intel Core i9           | 2         | 0.64%   |
| Intel Core 2 Quad       | 2         | 0.64%   |
| AMD Phenom II X2        | 2         | 0.64%   |
| AMD Opteron             | 2         | 0.64%   |
| AMD E                   | 2         | 0.64%   |
| AMD A4                  | 2         | 0.64%   |
| Intel Pentium Silver    | 1         | 0.32%   |
| Intel Pentium Gold      | 1         | 0.32%   |
| Intel Core m3           | 1         | 0.32%   |
| Intel Core 2            | 1         | 0.32%   |
| Intel Celeron Dual-Core | 1         | 0.32%   |
| AMD Phenom II X4        | 1         | 0.32%   |
| AMD E1                  | 1         | 0.32%   |
| AMD A8                  | 1         | 0.32%   |
| AMD A6                  | 1         | 0.32%   |
| AMD A10                 | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 123       | 39.42%  |
| 2       | 78        | 25%     |
| 6       | 47        | 15.06%  |
| 8       | 40        | 12.82%  |
| 12      | 7         | 2.24%   |
| 16      | 6         | 1.92%   |
| 14      | 6         | 1.92%   |
| 10      | 3         | 0.96%   |
| 1       | 1         | 0.32%   |
| Unknown | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 310       | 99.36%  |
| 2       | 1         | 0.32%   |
| Unknown | 1         | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 249       | 79.81%  |
| 1       | 62        | 19.87%  |
| Unknown | 1         | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 312       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 42.59%  |
| 0x806c1    | 14        | 4.42%   |
| 0x306a9    | 12        | 3.79%   |
| 0x0a50000c | 12        | 3.79%   |
| 0x306c3    | 10        | 3.15%   |
| 0x08600106 | 8         | 2.52%   |
| 0x806ec    | 7         | 2.21%   |
| 0x08701021 | 7         | 2.21%   |
| 0x806e9    | 6         | 1.89%   |
| 0x906ea    | 5         | 1.58%   |
| 0x906a3    | 5         | 1.58%   |
| 0x206a7    | 5         | 1.58%   |
| 0x906e9    | 4         | 1.26%   |
| 0x806ea    | 4         | 1.26%   |
| 0x406e3    | 4         | 1.26%   |
| 0x08608103 | 4         | 1.26%   |
| 0x0800820d | 4         | 1.26%   |
| 0xa0653    | 3         | 0.95%   |
| 0x0a201205 | 3         | 0.95%   |
| 0x08608102 | 3         | 0.95%   |
| 0x08108109 | 3         | 0.95%   |
| 0x010000c8 | 3         | 0.95%   |
| 0xa0655    | 2         | 0.63%   |
| 0xa0652    | 2         | 0.63%   |
| 0x906ed    | 2         | 0.63%   |
| 0x90672    | 2         | 0.63%   |
| 0x806d1    | 2         | 0.63%   |
| 0x806c2    | 2         | 0.63%   |
| 0x6fb      | 2         | 0.63%   |
| 0x506e3    | 2         | 0.63%   |
| 0x506c9    | 2         | 0.63%   |
| 0x406f1    | 2         | 0.63%   |
| 0x40661    | 2         | 0.63%   |
| 0x20652    | 2         | 0.63%   |
| 0x1067a    | 2         | 0.63%   |
| 0x0a201016 | 2         | 0.63%   |
| 0x0a201009 | 2         | 0.63%   |
| 0x08600103 | 2         | 0.63%   |
| 0x08001138 | 2         | 0.63%   |
| 0x906a4    | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 13.74%  |
| Haswell          | 31        | 9.9%    |
| Zen 3            | 30        | 9.58%   |
| TigerLake        | 25        | 7.99%   |
| IvyBridge        | 24        | 7.67%   |
| Zen 2            | 23        | 7.35%   |
| Unknown          | 18        | 5.75%   |
| Zen+             | 15        | 4.79%   |
| Skylake          | 15        | 4.79%   |
| SandyBridge      | 12        | 3.83%   |
| CometLake        | 9         | 2.88%   |
| Alderlake Hybrid | 8         | 2.56%   |
| Piledriver       | 7         | 2.24%   |
| Zen              | 6         | 1.92%   |
| Goldmont plus    | 6         | 1.92%   |
| Westmere         | 5         | 1.6%    |
| Penryn           | 5         | 1.6%    |
| Core             | 5         | 1.6%    |
| K10              | 4         | 1.28%   |
| Goldmont         | 4         | 1.28%   |
| Broadwell        | 4         | 1.28%   |
| Nehalem          | 3         | 0.96%   |
| Icelake          | 3         | 0.96%   |
| Silvermont       | 2         | 0.64%   |
| Excavator        | 2         | 0.64%   |
| Bobcat           | 2         | 0.64%   |
| Steamroller      | 1         | 0.32%   |
| Puma             | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 158       | 41.91%  |
| Nvidia                     | 118       | 31.3%   |
| AMD                        | 98        | 25.99%  |
| Matrox Electronics Systems | 2         | 0.53%   |
| Zhaoxin                    | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 23        | 5.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 17        | 4.43%   |
| AMD Cezanne                                                                           | 14        | 3.65%   |
| AMD Renoir                                                                            | 12        | 3.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 9         | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 8         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 8         | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 8         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 1.82%   |
| Intel HD Graphics 620                                                                 | 7         | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 1.82%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 7         | 1.82%   |
| AMD Lucienne                                                                          | 7         | 1.82%   |
| Intel HD Graphics 630                                                                 | 6         | 1.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 6         | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 5         | 1.3%    |
| Intel UHD Graphics 620                                                                | 5         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 4         | 1.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 4         | 1.04%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.04%   |
| Intel HD Graphics 530                                                                 | 4         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 0.78%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 3         | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 3         | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                | 3         | 0.78%   |
| Intel HD Graphics 500                                                                 | 3         | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.52%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                 | 2         | 0.52%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 2         | 0.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                             | 2         | 0.52%   |
| Nvidia GT218 [GeForce 210]                                                            | 2         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 106       | 33.97%  |
| 1 x AMD                  | 69        | 22.12%  |
| 1 x Nvidia               | 68        | 21.79%  |
| Intel + Nvidia           | 35        | 11.22%  |
| Intel + AMD              | 11        | 3.53%   |
| AMD + Nvidia             | 11        | 3.53%   |
| 2 x AMD                  | 4         | 1.28%   |
| Other                    | 2         | 0.64%   |
| 2 x Nvidia               | 2         | 0.64%   |
| 1 x Zhaoxin              | 1         | 0.32%   |
| Nvidia + Matrox          | 1         | 0.32%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.32%   |
| AMD + Matrox             | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 214       | 68.59%  |
| Proprietary | 89        | 28.53%  |
| Unknown     | 9         | 2.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 61.2%   |
| 0.01-0.5   | 27        | 8.52%   |
| 1.01-2.0   | 23        | 7.26%   |
| 7.01-8.0   | 19        | 5.99%   |
| 3.01-4.0   | 17        | 5.36%   |
| 0.51-1.0   | 14        | 4.42%   |
| 5.01-6.0   | 13        | 4.1%    |
| 8.01-16.0  | 7         | 2.21%   |
| 4.01-5.0   | 1         | 0.32%   |
| 2.01-3.0   | 1         | 0.32%   |
| 16.01-24.0 | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 46        | 12.47%  |
| AU Optronics            | 36        | 9.76%   |
| BOE                     | 35        | 9.49%   |
| Chimei Innolux          | 31        | 8.4%    |
| LG Display              | 27        | 7.32%   |
| Dell                    | 25        | 6.78%   |
| Hewlett-Packard         | 21        | 5.69%   |
| Goldstar                | 20        | 5.42%   |
| Acer                    | 16        | 4.34%   |
| Philips                 | 11        | 2.98%   |
| BenQ                    | 11        | 2.98%   |
| AOC                     | 11        | 2.98%   |
| Sharp                   | 10        | 2.71%   |
| Iiyama                  | 6         | 1.63%   |
| Apple                   | 6         | 1.63%   |
| InfoVision              | 5         | 1.36%   |
| CSO                     | 5         | 1.36%   |
| Ancor Communications    | 5         | 1.36%   |
| Sony                    | 4         | 1.08%   |
| Lenovo                  | 4         | 1.08%   |
| Chi Mei Optoelectronics | 4         | 1.08%   |
| ASUSTek Computer        | 4         | 1.08%   |
| NEC Computers           | 3         | 0.81%   |
| Vizio                   | 2         | 0.54%   |
| Panasonic               | 2         | 0.54%   |
| Idek Iiyama             | 2         | 0.54%   |
| Vita                    | 1         | 0.27%   |
| Unknown                 | 1         | 0.27%   |
| Sunplus                 | 1         | 0.27%   |
| STD                     | 1         | 0.27%   |
| SLD                     | 1         | 0.27%   |
| Sceptre Tech            | 1         | 0.27%   |
| RTK                     | 1         | 0.27%   |
| QUS                     | 1         | 0.27%   |
| Planar                  | 1         | 0.27%   |
| LG Electronics          | 1         | 0.27%   |
| Gigabyte Technology     | 1         | 0.27%   |
| Fujitsu Siemens         | 1         | 0.27%   |
| Envision Peripherals    | 1         | 0.27%   |
| Eizo                    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.05%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 3         | 0.79%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.79%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.53%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                       | 2         | 0.53%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch                | 2         | 0.53%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                    | 2         | 0.53%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch         | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.53%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.53%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                        | 2         | 0.53%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                         | 2         | 0.53%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                        | 2         | 0.53%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                        | 2         | 0.53%   |
| Vizio E320-B0 VIZ1007 1366x768 697x392mm 31.5-inch                       | 1         | 0.26%   |
| Vizio E241-A1 VIZ0098 1920x1080 521x293mm 23.5-inch                      | 1         | 0.26%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                         | 1         | 0.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 0.26%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.26%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                            | 1         | 0.26%   |
| Sony TV SNYEE01 1920x1080                                                | 1         | 0.26%   |
| Sony TV SNYC901 1920x1080                                                | 1         | 0.26%   |
| Sony TV SNY7702 1920x1080 886x498mm 40.0-inch                            | 1         | 0.26%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                       | 1         | 0.26%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 1         | 0.26%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 175       | 51.17%  |
| 1366x768 (WXGA)    | 41        | 11.99%  |
| 3840x2160 (4K)     | 25        | 7.31%   |
| 2560x1440 (QHD)    | 19        | 5.56%   |
| 1920x1200 (WUXGA)  | 12        | 3.51%   |
| 1600x900 (HD+)     | 10        | 2.92%   |
| 2560x1600          | 9         | 2.63%   |
| 1680x1050 (WSXGA+) | 9         | 2.63%   |
| 2880x1800          | 6         | 1.75%   |
| 1280x1024 (SXGA)   | 6         | 1.75%   |
| 2560x1080          | 5         | 1.46%   |
| 3440x1440          | 4         | 1.17%   |
| 1440x900 (WXGA+)   | 4         | 1.17%   |
| 2520x1680          | 2         | 0.58%   |
| 1280x800 (WXGA)    | 2         | 0.58%   |
| 1280x720 (HD)      | 2         | 0.58%   |
| 3840x1080          | 1         | 0.29%   |
| 3600x1200          | 1         | 0.29%   |
| 2736x1824          | 1         | 0.29%   |
| 2288x1287          | 1         | 0.29%   |
| 2240x1400          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 2160x1350          | 1         | 0.29%   |
| 1920x540           | 1         | 0.29%   |
| 1360x768           | 1         | 0.29%   |
| 1024x768 (XGA)     | 1         | 0.29%   |
| Unknown            | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 84        | 22.89%  |
| 24      | 42        | 11.44%  |
| 27      | 30        | 8.17%   |
| 14      | 30        | 8.17%   |
| 13      | 28        | 7.63%   |
| 21      | 25        | 6.81%   |
| 23      | 20        | 5.45%   |
| 17      | 13        | 3.54%   |
| 31      | 12        | 3.27%   |
| 16      | 11        | 3%      |
| 19      | 10        | 2.72%   |
| 34      | 9         | 2.45%   |
| 22      | 8         | 2.18%   |
| 12      | 6         | 1.63%   |
| 11      | 5         | 1.36%   |
| 18      | 4         | 1.09%   |
| Unknown | 4         | 1.09%   |
| 46      | 3         | 0.82%   |
| 32      | 3         | 0.82%   |
| 20      | 3         | 0.82%   |
| 72      | 2         | 0.54%   |
| 65      | 2         | 0.54%   |
| 60      | 2         | 0.54%   |
| 40      | 2         | 0.54%   |
| 142     | 1         | 0.27%   |
| 55      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 48      | 1         | 0.27%   |
| 43      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 36      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 131       | 37.01%  |
| 501-600        | 77        | 21.75%  |
| 401-500        | 44        | 12.43%  |
| 201-300        | 28        | 7.91%   |
| 351-400        | 23        | 6.5%    |
| 601-700        | 17        | 4.8%    |
| 701-800        | 13        | 3.67%   |
| 1001-1500      | 10        | 2.82%   |
| Unknown        | 4         | 1.13%   |
| 801-900        | 2         | 0.56%   |
| 1501-2000      | 2         | 0.56%   |
| 901-1000       | 2         | 0.56%   |
| More than 2000 | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 248       | 77.5%   |
| 16/10   | 46        | 14.38%  |
| 21/9    | 9         | 2.81%   |
| 5/4     | 6         | 1.88%   |
| 3/2     | 4         | 1.25%   |
| Unknown | 3         | 0.94%   |
| 4/3     | 1         | 0.31%   |
| 32/9    | 1         | 0.31%   |
| 1.98    | 1         | 0.31%   |
| 1.00    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 24.02%  |
| 201-250        | 68        | 18.99%  |
| 81-90          | 44        | 12.29%  |
| 301-350        | 30        | 8.38%   |
| 351-500        | 24        | 6.7%    |
| 151-200        | 22        | 6.15%   |
| 71-80          | 15        | 4.19%   |
| 251-300        | 12        | 3.35%   |
| 121-130        | 12        | 3.35%   |
| More than 1000 | 9         | 2.51%   |
| 501-1000       | 9         | 2.51%   |
| 111-120        | 8         | 2.23%   |
| 61-70          | 5         | 1.4%    |
| 51-60          | 5         | 1.4%    |
| 141-150        | 4         | 1.12%   |
| Unknown        | 4         | 1.12%   |
| 91-100         | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 106       | 30.9%   |
| 51-100        | 106       | 30.9%   |
| 101-120       | 69        | 20.12%  |
| 161-240       | 34        | 9.91%   |
| 1-50          | 14        | 4.08%   |
| More than 240 | 10        | 2.92%   |
| Unknown       | 4         | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 227       | 72.06%  |
| 2     | 71        | 22.54%  |
| 0     | 8         | 2.54%   |
| 3     | 7         | 2.22%   |
| 4     | 2         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 180       | 36.66%  |
| Intel                           | 170       | 34.62%  |
| Qualcomm Atheros                | 42        | 8.55%   |
| Broadcom                        | 23        | 4.68%   |
| MediaTek                        | 12        | 2.44%   |
| Ralink Technology               | 10        | 2.04%   |
| TP-Link                         | 5         | 1.02%   |
| Samsung Electronics             | 5         | 1.02%   |
| ASIX Electronics                | 5         | 1.02%   |
| Aquantia                        | 5         | 1.02%   |
| Ralink                          | 3         | 0.61%   |
| Huawei Technologies             | 3         | 0.61%   |
| Xiaomi                          | 2         | 0.41%   |
| Marvell Technology Group        | 2         | 0.41%   |
| Lenovo                          | 2         | 0.41%   |
| ASUSTek Computer                | 2         | 0.41%   |
| ZyXEL Communications            | 1         | 0.2%    |
| Wilocity                        | 1         | 0.2%    |
| VIA Technologies                | 1         | 0.2%    |
| Sierra Wireless                 | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| Qualcomm                        | 1         | 0.2%    |
| Nvidia                          | 1         | 0.2%    |
| NetGear                         | 1         | 0.2%    |
| Motorola PCS                    | 1         | 0.2%    |
| Microsoft                       | 1         | 0.2%    |
| Mercucys                        | 1         | 0.2%    |
| Linksys                         | 1         | 0.2%    |
| Google                          | 1         | 0.2%    |
| Edimax Technology               | 1         | 0.2%    |
| DisplayLink                     | 1         | 0.2%    |
| Dell                            | 1         | 0.2%    |
| D-Link System                   | 1         | 0.2%    |
| D-Link                          | 1         | 0.2%    |
| Broadcom Limited                | 1         | 0.2%    |
| Belkin Components               | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 115       | 20.46%  |
| Intel Wi-Fi 6 AX200                                               | 21        | 3.74%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 3.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 15        | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 1.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 1.78%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.6%    |
| Realtek 802.11ac NIC                                              | 9         | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.42%   |
| Intel Wireless 7260                                               | 8         | 1.42%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.42%   |
| Intel Ethernet Controller I225-V                                  | 8         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.25%   |
| Intel Wireless 7265                                               | 6         | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.89%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.89%   |
| Intel Wireless 8260                                               | 5         | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.89%   |
| Intel Wireless 3165                                               | 4         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.71%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 46.35%  |
| Realtek Semiconductor           | 49        | 17.88%  |
| Qualcomm Atheros                | 30        | 10.95%  |
| Broadcom                        | 22        | 8.03%   |
| MediaTek                        | 11        | 4.01%   |
| Ralink Technology               | 10        | 3.65%   |
| TP-Link                         | 4         | 1.46%   |
| Ralink                          | 3         | 1.09%   |
| ASUSTek Computer                | 2         | 0.73%   |
| ZyXEL Communications            | 1         | 0.36%   |
| Wilocity                        | 1         | 0.36%   |
| Sierra Wireless                 | 1         | 0.36%   |
| Qualcomm Atheros Communications | 1         | 0.36%   |
| Qualcomm                        | 1         | 0.36%   |
| NetGear                         | 1         | 0.36%   |
| Microsoft                       | 1         | 0.36%   |
| Mercucys                        | 1         | 0.36%   |
| Marvell Technology Group        | 1         | 0.36%   |
| Linksys                         | 1         | 0.36%   |
| Edimax Technology               | 1         | 0.36%   |
| Dell                            | 1         | 0.36%   |
| D-Link System                   | 1         | 0.36%   |
| D-Link                          | 1         | 0.36%   |
| Broadcom Limited                | 1         | 0.36%   |
| Belkin Components               | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 21        | 7.58%   |
| Intel Wi-Fi 6 AX201                                           | 20        | 7.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 15        | 5.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 10        | 3.61%   |
| Realtek 802.11ac NIC                                          | 9         | 3.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 8         | 2.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 8         | 2.89%   |
| Intel Wireless 7260                                           | 8         | 2.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 8         | 2.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 8         | 2.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 7         | 2.53%   |
| Intel Wireless 7265                                           | 6         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 6         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 6         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 1.81%   |
| Intel Wireless 8265 / 8275                                    | 5         | 1.81%   |
| Intel Wireless 8260                                           | 5         | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 5         | 1.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 5         | 1.81%   |
| Intel Wireless 3165                                           | 4         | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 3         | 1.08%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 3         | 1.08%   |
| Intel Wireless-AC 9260                                        | 3         | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 3         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 3         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 1.08%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                  | 2         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                | 2         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 2         | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                     | 2         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 150       | 54.15%  |
| Intel                    | 80        | 28.88%  |
| Qualcomm Atheros         | 13        | 4.69%   |
| Samsung Electronics      | 5         | 1.81%   |
| Broadcom                 | 5         | 1.81%   |
| ASIX Electronics         | 5         | 1.81%   |
| Aquantia                 | 5         | 1.81%   |
| Huawei Technologies      | 3         | 1.08%   |
| Xiaomi                   | 2         | 0.72%   |
| Lenovo                   | 2         | 0.72%   |
| VIA Technologies         | 1         | 0.36%   |
| TP-Link                  | 1         | 0.36%   |
| Nvidia                   | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| Marvell Technology Group | 1         | 0.36%   |
| Google                   | 1         | 0.36%   |
| DisplayLink              | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 115       | 40.49%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.52%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 3.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.17%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.82%   |
| Intel Ethernet Controller I225-V                                  | 8         | 2.82%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 2.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.76%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.76%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4         | 1.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.06%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.06%   |
| Huawei YAL-L21                                                    | 3         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.7%    |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.7%    |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.7%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.35%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 262       | 50.87%  |
| Ethernet | 252       | 48.93%  |
| Unknown  | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 202       | 61.03%  |
| Ethernet | 129       | 38.97%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 160       | 51.28%  |
| 1     | 139       | 44.55%  |
| 3     | 6         | 1.92%   |
| 0     | 5         | 1.6%    |
| 6     | 1         | 0.32%   |
| 4     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 232       | 73.65%  |
| Yes  | 83        | 26.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 108       | 46.15%  |
| Realtek Semiconductor           | 25        | 10.68%  |
| Cambridge Silicon Radio         | 22        | 9.4%    |
| Qualcomm Atheros Communications | 13        | 5.56%   |
| IMC Networks                    | 12        | 5.13%   |
| Broadcom                        | 12        | 5.13%   |
| Lite-On Technology              | 8         | 3.42%   |
| Foxconn / Hon Hai               | 7         | 2.99%   |
| ASUSTek Computer                | 6         | 2.56%   |
| Apple                           | 5         | 2.14%   |
| Toshiba                         | 3         | 1.28%   |
| Edimax Technology               | 3         | 1.28%   |
| TP-Link                         | 2         | 0.85%   |
| Realtek                         | 2         | 0.85%   |
| Dell                            | 2         | 0.85%   |
| Marvell Semiconductor           | 1         | 0.43%   |
| Hewlett-Packard                 | 1         | 0.43%   |
| Foxconn International           | 1         | 0.43%   |
| Alps Electric                   | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 28        | 11.97%  |
| Intel Bluetooth wireless interface                  | 26        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 9.4%    |
| Realtek Bluetooth Radio                             | 21        | 8.97%   |
| Intel AX200 Bluetooth                               | 21        | 8.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 5.56%   |
| Intel Bluetooth Device                              | 8         | 3.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.14%   |
| Intel AX210 Bluetooth                               | 5         | 2.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.71%   |
| Lite-On Wireless_Device                             | 4         | 1.71%   |
| IMC Networks Wireless_Device                        | 4         | 1.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.28%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.28%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.28%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.28%   |
| ASUS ASUS USB-BT500                                 | 3         | 1.28%   |
| Apple Bluetooth Host Controller                     | 3         | 1.28%   |
| TP-Link UB500 Adapter                               | 2         | 0.85%   |
| Realtek Bluetooth Radio                             | 2         | 0.85%   |
| IMC Networks Bluetooth Device                       | 2         | 0.85%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.85%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.43%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.43%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.43%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.43%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.43%   |
| Lite-On Bluetooth Device                            | 1         | 0.43%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.43%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 205       | 41.75%  |
| AMD                      | 119       | 24.24%  |
| Nvidia                   | 96        | 19.55%  |
| C-Media Electronics      | 8         | 1.63%   |
| GN Netcom                | 6         | 1.22%   |
| JMTek                    | 5         | 1.02%   |
| Creative Labs            | 4         | 0.81%   |
| ZOOM                     | 2         | 0.41%   |
| VIA Technologies         | 2         | 0.41%   |
| Texas Instruments        | 2         | 0.41%   |
| Logitech                 | 2         | 0.41%   |
| Lenovo                   | 2         | 0.41%   |
| Kingston Technology      | 2         | 0.41%   |
| Generalplus Technology   | 2         | 0.41%   |
| BY EDIFIER               | 2         | 0.41%   |
| ASUSTek Computer         | 2         | 0.41%   |
| Arturia                  | 2         | 0.41%   |
| Zhaoxin                  | 1         | 0.2%    |
| Yamaha                   | 1         | 0.2%    |
| Unknown                  | 1         | 0.2%    |
| TerraTec Electronic      | 1         | 0.2%    |
| SteelSeries ApS          | 1         | 0.2%    |
| Sony                     | 1         | 0.2%    |
| Samson Technologies      | 1         | 0.2%    |
| Razer USA                | 1         | 0.2%    |
| QinHeng Electronics      | 1         | 0.2%    |
| Philips (or NXP)         | 1         | 0.2%    |
| Nordic Semiconductor ASA | 1         | 0.2%    |
| Microdia                 | 1         | 0.2%    |
| Micro Star International | 1         | 0.2%    |
| M-Audio                  | 1         | 0.2%    |
| KORG                     | 1         | 0.2%    |
| Hangzhou Worlde          | 1         | 0.2%    |
| Focusrite-Novation       | 1         | 0.2%    |
| DisplayLink              | 1         | 0.2%    |
| Dell                     | 1         | 0.2%    |
| Cyber Acoustics          | 1         | 0.2%    |
| Creative Technology      | 1         | 0.2%    |
| Corsair                  | 1         | 0.2%    |
| Bose                     | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 46        | 8.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 5.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 4.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24        | 4.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 21        | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 3.66%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 2.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 2.09%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 1.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 1.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.4%    |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 1.22%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.22%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5         | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 0.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.87%   |
| AMD FCH Azalia Controller                                                  | 5         | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.7%    |
| Intel CM238 HD Audio Controller                                            | 4         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.7%    |
| Nvidia TU102 High Definition Audio Controller                              | 3         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 65        | 28.14%  |
| SK hynix            | 34        | 14.72%  |
| Kingston            | 27        | 11.69%  |
| Micron Technology   | 20        | 8.66%   |
| Corsair             | 18        | 7.79%   |
| G.Skill             | 14        | 6.06%   |
| Crucial             | 14        | 6.06%   |
| Unknown             | 8         | 3.46%   |
| A-DATA Technology   | 4         | 1.73%   |
| Unknown             | 4         | 1.73%   |
| Elpida              | 3         | 1.3%    |
| Unknown (ABCD)      | 2         | 0.87%   |
| Team                | 2         | 0.87%   |
| Ramaxel Technology  | 2         | 0.87%   |
| Patriot             | 2         | 0.87%   |
| AMD                 | 2         | 0.87%   |
| Wilk                | 1         | 0.43%   |
| Unknown (8A02)      | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| Shenzhen Zhongteng  | 1         | 0.43%   |
| Shenzhen WODPOSIT   | 1         | 0.43%   |
| Qimonda             | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| Nanya Technology    | 1         | 0.43%   |
| Kingmax             | 1         | 0.43%   |
| Atermiter           | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 1.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.59%   |
| Unknown                                                          | 4         | 1.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.2%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.8%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.8%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Micron RAM 8ATF1G64AZ-2G6E1 8192MB DIMM DDR4 2667MT/s            | 2         | 0.8%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s           | 2         | 0.8%    |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.4%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.4%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 0.4%    |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s              | 1         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 1         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.4%    |
| Unknown (8A02) RAM DDR3 1600 4G 4GB SODIMM DDR3 1600MT/s         | 1         | 0.4%    |
| Unknown (8A02) RAM DDR3 1600 4G 4GB Chip DDR3 1600MT/s           | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s              | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s               | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 123       | 61.19%  |
| DDR3    | 49        | 24.38%  |
| LPDDR4  | 10        | 4.98%   |
| DDR5    | 4         | 1.99%   |
| DDR2    | 4         | 1.99%   |
| SDRAM   | 3         | 1.49%   |
| LPDDR3  | 3         | 1.49%   |
| Unknown | 3         | 1.49%   |
| LPDDR5  | 2         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 52.22%  |
| DIMM         | 71        | 34.98%  |
| Row Of Chips | 24        | 11.82%  |
| RIMM         | 1         | 0.49%   |
| Chip         | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 103       | 47.69%  |
| 4096  | 51        | 23.61%  |
| 16384 | 33        | 15.28%  |
| 2048  | 14        | 6.48%   |
| 32768 | 11        | 5.09%   |
| 1024  | 4         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 55        | 25.58%  |
| 2667    | 32        | 14.88%  |
| 1600    | 32        | 14.88%  |
| 2400    | 13        | 6.05%   |
| 1333    | 13        | 6.05%   |
| 2133    | 11        | 5.12%   |
| 3600    | 5         | 2.33%   |
| 1334    | 5         | 2.33%   |
| 4800    | 4         | 1.86%   |
| 4267    | 4         | 1.86%   |
| 3000    | 4         | 1.86%   |
| 2666    | 4         | 1.86%   |
| 1867    | 4         | 1.86%   |
| 3066    | 3         | 1.4%    |
| 6400    | 2         | 0.93%   |
| 4266    | 2         | 0.93%   |
| 3800    | 2         | 0.93%   |
| 3266    | 2         | 0.93%   |
| 667     | 2         | 0.93%   |
| 6000    | 1         | 0.47%   |
| 5800    | 1         | 0.47%   |
| 4000    | 1         | 0.47%   |
| 3666    | 1         | 0.47%   |
| 3467    | 1         | 0.47%   |
| 3466    | 1         | 0.47%   |
| 3333    | 1         | 0.47%   |
| 2933    | 1         | 0.47%   |
| 2800    | 1         | 0.47%   |
| 2448    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 1067    | 1         | 0.47%   |
| 1066    | 1         | 0.47%   |
| 800     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 36.36%  |
| Seiko Epson         | 2         | 18.18%  |
| Xerox               | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Datamax-O'Neil      | 1         | 9.09%   |
| Canon               | 1         | 9.09%   |
| Brother Industries  | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155    | 1         | 9.09%   |
| Seiko Epson L3110 Series      | 1         | 9.09%   |
| Seiko Epson L222 Series       | 1         | 9.09%   |
| Samsung M2070 Series          | 1         | 9.09%   |
| HP OfficeJet 5500 series      | 1         | 9.09%   |
| HP LaserJet 1022              | 1         | 9.09%   |
| HP ENVY 4500 series           | 1         | 9.09%   |
| HP DeskJet 3700 series        | 1         | 9.09%   |
| Datamax-O'Neil Datamax E-4304 | 1         | 9.09%   |
| Canon PIXMA MX470 Series      | 1         | 9.09%   |
| Brother MFC-J460DW            | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 66.67%  |
| Seiko Epson    | 1         | 16.67%  |
| Mustek Systems | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 16.67%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 16.67%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 16.67%  |
| Canon CanoScan LiDE 220                     | 1         | 16.67%  |
| Canon CanoScan LiDE 210                     | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 19.9%   |
| Microdia                               | 23        | 11.17%  |
| IMC Networks                           | 21        | 10.19%  |
| Logitech                               | 19        | 9.22%   |
| Acer                                   | 19        | 9.22%   |
| Realtek Semiconductor                  | 13        | 6.31%   |
| Quanta                                 | 13        | 6.31%   |
| Luxvisions Innotech Limited            | 8         | 3.88%   |
| Sunplus Innovation Technology          | 7         | 3.4%    |
| Silicon Motion                         | 4         | 1.94%   |
| Lite-On Technology                     | 4         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.94%   |
| Apple                                  | 4         | 1.94%   |
| Microsoft                              | 3         | 1.46%   |
| Y Media                                | 2         | 0.97%   |
| Syntek                                 | 2         | 0.97%   |
| KYE Systems (Mouse Systems)            | 2         | 0.97%   |
| Jieli Technology                       | 2         | 0.97%   |
| Generalplus Technology                 | 2         | 0.97%   |
| Z-Star Microelectronics                | 1         | 0.49%   |
| SunplusIT                              | 1         | 0.49%   |
| ShineTech                              | 1         | 0.49%   |
| Samsung Electronics                    | 1         | 0.49%   |
| Novatek Microelectronics               | 1         | 0.49%   |
| Importek                               | 1         | 0.49%   |
| icSpring                               | 1         | 0.49%   |
| Hewlett-Packard                        | 1         | 0.49%   |
| Goodong                                | 1         | 0.49%   |
| eMPIA Technology                       | 1         | 0.49%   |
| Asuscom Network                        | 1         | 0.49%   |
| ARC International                      | 1         | 0.49%   |
| Alcor Micro                            | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 11        | 5.29%   |
| Acer Integrated Camera                                          | 10        | 4.81%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 4.33%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 3.37%   |
| IMC Networks Integrated Camera                                  | 6         | 2.88%   |
| Chicony HD WebCam                                               | 6         | 2.88%   |
| Realtek Integrated_Webcam_HD                                    | 4         | 1.92%   |
| Quanta HP TrueVision HD Camera                                  | 4         | 1.92%   |
| Microdia Webcam Vitade AF                                       | 4         | 1.92%   |
| Logitech Webcam C270                                            | 4         | 1.92%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 1.44%   |
| Realtek USB Camera                                              | 3         | 1.44%   |
| Quanta HP Wide Vision HD Camera                                 | 3         | 1.44%   |
| Quanta HD User Facing                                           | 3         | 1.44%   |
| Microdia Integrated_Webcam_FHD                                  | 3         | 1.44%   |
| Logitech Webcam C310                                            | 3         | 1.44%   |
| Logitech HD Pro Webcam C920                                     | 3         | 1.44%   |
| Chicony USB2.0 Camera                                           | 3         | 1.44%   |
| Y Media USB Camera                                              | 2         | 0.96%   |
| Microdia Integrated Camera                                      | 2         | 0.96%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 0.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 0.96%   |
| Luxvisions Innotech Limited HP HD Camera                        | 2         | 0.96%   |
| Logitech StreamCam                                              | 2         | 0.96%   |
| Logitech C922 Pro Stream Webcam                                 | 2         | 0.96%   |
| Logitech C920 PRO HD Webcam                                     | 2         | 0.96%   |
| Lite-On Integrated Camera                                       | 2         | 0.96%   |
| Jieli USB PHY 2.0                                               | 2         | 0.96%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 2         | 0.96%   |
| IMC Networks USB Camera                                         | 2         | 0.96%   |
| IMC Networks HD Camera                                          | 2         | 0.96%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 0.96%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 0.96%   |
| Chicony HP TrueVision HD                                        | 2         | 0.96%   |
| Chicony HP HD Camera                                            | 2         | 0.96%   |
| Chicony HD User Facing                                          | 2         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 0.96%   |
| Acer ThinkPad P50 Integrated Camera                             | 2         | 0.96%   |
| Z-Star A4 TECH USB2.0 PC Camera E                               | 1         | 0.48%   |
| Syntek Integrated Camera                                        | 1         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 16        | 34.78%  |
| Synaptics                  | 13        | 28.26%  |
| Validity Sensors           | 9         | 19.57%  |
| Elan Microelectronics      | 4         | 8.7%    |
| AuthenTec                  | 3         | 6.52%   |
| STMicroelectronics         | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                         | 15        | 32.61%  |
| Elan ELAN:ARM-M4                                            | 4         | 8.7%    |
| Unknown                                                     | 4         | 8.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 3         | 6.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 2         | 4.35%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2         | 4.35%   |
| AuthenTec Fingerprint Sensor                                | 2         | 4.35%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 2.17%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 2.17%   |
| Validity Sensors VFS491                                     | 1         | 2.17%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 2.17%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 1         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 2.17%   |
| Validity Sensors Fingerprint scanner                        | 1         | 2.17%   |
| Synaptics  WBDI                                             | 1         | 2.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 1         | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 2.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 2.17%   |
| STMicroelectronics Fingerprint Reader                       | 1         | 2.17%   |
| Shenzhen Goodix Fingerprint Reader                          | 1         | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 46.15%  |
| Alcor Micro           | 3         | 23.08%  |
| Upek                  | 1         | 7.69%   |
| O2 Micro              | 1         | 7.69%   |
| Gemalto (was Gemplus) | 1         | 7.69%   |
| Bit4id                | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 23.08%  |
| Broadcom 5880                                                                | 2         | 15.38%  |
| Broadcom 58200                                                               | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.69%   |
| Bit4id miniLector EVO                                                        | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 210       | 66.88%  |
| 1     | 84        | 26.75%  |
| 2     | 17        | 5.41%   |
| 3     | 2         | 0.64%   |
| 9     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 37.1%   |
| Net/wireless             | 14        | 11.29%  |
| Graphics card            | 13        | 10.48%  |
| Chipcard                 | 13        | 10.48%  |
| Multimedia controller    | 10        | 8.06%   |
| Camera                   | 8         | 6.45%   |
| Unassigned class         | 6         | 4.84%   |
| Bluetooth                | 5         | 4.03%   |
| Sound                    | 4         | 3.23%   |
| Communication controller | 3         | 2.42%   |
| Network                  | 1         | 0.81%   |
| Card reader              | 1         | 0.81%   |


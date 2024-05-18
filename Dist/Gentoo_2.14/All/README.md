Gentoo 2.14 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.14.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.14/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.14/Notebook/README.md).

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

Total: 540

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Z170A GAMING M7             | Desktop     | [e1892a119b](https://linux-hardware.org/?probe=e1892a119b) | May 08, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0bcef3f207](https://linux-hardware.org/?probe=0bcef3f207) | May 06, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [66c6c3e199](https://linux-hardware.org/?probe=66c6c3e199) | May 06, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [24ef78e496](https://linux-hardware.org/?probe=24ef78e496) | May 06, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [f6152a7042](https://linux-hardware.org/?probe=f6152a7042) | May 03, 2024 |
| HP            | ProBook 4510s               | Notebook    | [a6f89b6485](https://linux-hardware.org/?probe=a6f89b6485) | May 02, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [50ea9a7b8e](https://linux-hardware.org/?probe=50ea9a7b8e) | May 01, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [39ab9869d2](https://linux-hardware.org/?probe=39ab9869d2) | May 01, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8fa3424cce](https://linux-hardware.org/?probe=8fa3424cce) | Apr 30, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [62914f0506](https://linux-hardware.org/?probe=62914f0506) | Apr 30, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [9dcdf5a463](https://linux-hardware.org/?probe=9dcdf5a463) | Apr 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [703d565003](https://linux-hardware.org/?probe=703d565003) | Apr 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [c207bea569](https://linux-hardware.org/?probe=c207bea569) | Apr 25, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [cdc42c64dd](https://linux-hardware.org/?probe=cdc42c64dd) | Apr 22, 2024 |
| Gigabyte      | B75-D3V                     | Desktop     | [4ddc5c0d0d](https://linux-hardware.org/?probe=4ddc5c0d0d) | Apr 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4c782693bf](https://linux-hardware.org/?probe=4c782693bf) | Apr 20, 2024 |
| Quanta        | S210-X12MS 31S2MMB0040      | Server      | [7dbf4f941d](https://linux-hardware.org/?probe=7dbf4f941d) | Apr 20, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [2bb3d4f699](https://linux-hardware.org/?probe=2bb3d4f699) | Apr 19, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [90165c7480](https://linux-hardware.org/?probe=90165c7480) | Apr 18, 2024 |
| Lenovo        | ZHAOYANG E43                | Notebook    | [1192eac8f1](https://linux-hardware.org/?probe=1192eac8f1) | Apr 17, 2024 |
| Chuwi         | GemiBook XPro               | Notebook    | [9ebacb4cf9](https://linux-hardware.org/?probe=9ebacb4cf9) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [25c95d871e](https://linux-hardware.org/?probe=25c95d871e) | Apr 16, 2024 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [8a95e3759a](https://linux-hardware.org/?probe=8a95e3759a) | Apr 15, 2024 |
| Lenovo        | ThinkPad T480 20L6SAYX00    | Notebook    | [f53da67ab4](https://linux-hardware.org/?probe=f53da67ab4) | Apr 15, 2024 |
| Unknown       | RK3588 OPi 5 Plus           | Soc         | [c74a284aaf](https://linux-hardware.org/?probe=c74a284aaf) | Apr 15, 2024 |
| Lenovo        | ThinkPad T480 20L6SAYX00    | Notebook    | [fc73e6bb02](https://linux-hardware.org/?probe=fc73e6bb02) | Apr 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [c28ddacfd6](https://linux-hardware.org/?probe=c28ddacfd6) | Apr 13, 2024 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [6e49d2f74b](https://linux-hardware.org/?probe=6e49d2f74b) | Apr 13, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2eea232a7e](https://linux-hardware.org/?probe=2eea232a7e) | Apr 13, 2024 |
| Dell          | Latitude 5440               | Notebook    | [1fb5966e12](https://linux-hardware.org/?probe=1fb5966e12) | Apr 12, 2024 |
| Dell          | G15 5510                    | Notebook    | [e8cfa16a81](https://linux-hardware.org/?probe=e8cfa16a81) | Apr 12, 2024 |
| Dell          | G15 5510                    | Notebook    | [9ed69c889f](https://linux-hardware.org/?probe=9ed69c889f) | Apr 12, 2024 |
| HP            | 1589                        | Desktop     | [fd455c0623](https://linux-hardware.org/?probe=fd455c0623) | Apr 12, 2024 |
| ASUSTek       | P6X58D-E                    | Desktop     | [143efb64e8](https://linux-hardware.org/?probe=143efb64e8) | Apr 12, 2024 |
| IBM           | ThinkPad T41 23737JU        | Notebook    | [3e03052246](https://linux-hardware.org/?probe=3e03052246) | Apr 12, 2024 |
| Supermicro    | X10SRL-FB                   | Server      | [10b2f6ed9d](https://linux-hardware.org/?probe=10b2f6ed9d) | Apr 11, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f15f757ee9](https://linux-hardware.org/?probe=f15f757ee9) | Apr 11, 2024 |
| HP            | 1589                        | Desktop     | [bf38ba715e](https://linux-hardware.org/?probe=bf38ba715e) | Apr 10, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [bef494961d](https://linux-hardware.org/?probe=bef494961d) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6d013c64d2](https://linux-hardware.org/?probe=6d013c64d2) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [0ca999c16b](https://linux-hardware.org/?probe=0ca999c16b) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [40e7da85c2](https://linux-hardware.org/?probe=40e7da85c2) | Apr 06, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [0d1189e3fb](https://linux-hardware.org/?probe=0d1189e3fb) | Apr 04, 2024 |
| Dell          | Precision 5480              | Notebook    | [665a2dee23](https://linux-hardware.org/?probe=665a2dee23) | Apr 04, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [30921e196b](https://linux-hardware.org/?probe=30921e196b) | Apr 03, 2024 |
| ASUSTek       | X99-E                       | Desktop     | [f9f01b1a69](https://linux-hardware.org/?probe=f9f01b1a69) | Apr 03, 2024 |
| ASUSTek       | X99-E                       | Desktop     | [e87752dc61](https://linux-hardware.org/?probe=e87752dc61) | Apr 03, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [ebc630507b](https://linux-hardware.org/?probe=ebc630507b) | Apr 02, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [3186452a8d](https://linux-hardware.org/?probe=3186452a8d) | Apr 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [9d19446a7f](https://linux-hardware.org/?probe=9d19446a7f) | Apr 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [82ac8c0b36](https://linux-hardware.org/?probe=82ac8c0b36) | Mar 31, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [0b20dc1c09](https://linux-hardware.org/?probe=0b20dc1c09) | Mar 30, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | Notebook    | [b0c74f7b30](https://linux-hardware.org/?probe=b0c74f7b30) | Mar 30, 2024 |
| Lenovo        | ThinkPad T470 20HES18R20    | Notebook    | [0c5f481d17](https://linux-hardware.org/?probe=0c5f481d17) | Mar 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [e4035a3519](https://linux-hardware.org/?probe=e4035a3519) | Mar 25, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [73b0c5faa2](https://linux-hardware.org/?probe=73b0c5faa2) | Mar 25, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [3e42f1f6bb](https://linux-hardware.org/?probe=3e42f1f6bb) | Mar 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [e4e9866823](https://linux-hardware.org/?probe=e4e9866823) | Mar 22, 2024 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [f406391d1a](https://linux-hardware.org/?probe=f406391d1a) | Mar 20, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [b3056c47f2](https://linux-hardware.org/?probe=b3056c47f2) | Mar 19, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [14031f3746](https://linux-hardware.org/?probe=14031f3746) | Mar 17, 2024 |
| Dell          | G5 5590                     | Notebook    | [c914da4cc5](https://linux-hardware.org/?probe=c914da4cc5) | Mar 17, 2024 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [c44e343345](https://linux-hardware.org/?probe=c44e343345) | Mar 17, 2024 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [8f5d6ee906](https://linux-hardware.org/?probe=8f5d6ee906) | Mar 17, 2024 |
| Colorful T... | CVN Z790M FROZEN D5 V20     | Desktop     | [05f6953852](https://linux-hardware.org/?probe=05f6953852) | Mar 17, 2024 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [63eb058c79](https://linux-hardware.org/?probe=63eb058c79) | Mar 17, 2024 |
| HP            | ProBook 430 G7              | Notebook    | [05be2ac277](https://linux-hardware.org/?probe=05be2ac277) | Mar 17, 2024 |
| Dell          | Latitude E6540              | Notebook    | [bbc5613ffc](https://linux-hardware.org/?probe=bbc5613ffc) | Mar 15, 2024 |
| ASRock        | N68C-GS UCC                 | Desktop     | [d723eedac0](https://linux-hardware.org/?probe=d723eedac0) | Mar 15, 2024 |
| Colorful T... | CVN Z790M FROZEN D5 V20     | Desktop     | [d43454b637](https://linux-hardware.org/?probe=d43454b637) | Mar 15, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [b8a3fe05f4](https://linux-hardware.org/?probe=b8a3fe05f4) | Mar 13, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | Notebook    | [093a0c28e4](https://linux-hardware.org/?probe=093a0c28e4) | Mar 11, 2024 |
| Lenovo        | ThinkPad T480 20L50013US    | Notebook    | [8b29b924ae](https://linux-hardware.org/?probe=8b29b924ae) | Mar 10, 2024 |
| Dell          | Latitude 7490               | Notebook    | [af0f098b77](https://linux-hardware.org/?probe=af0f098b77) | Mar 10, 2024 |
| Google        | Panther                     | Desktop     | [f2c3361edf](https://linux-hardware.org/?probe=f2c3361edf) | Mar 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [b4686bb020](https://linux-hardware.org/?probe=b4686bb020) | Mar 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [4d7fa7ac88](https://linux-hardware.org/?probe=4d7fa7ac88) | Mar 10, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [63f6678f1c](https://linux-hardware.org/?probe=63f6678f1c) | Mar 09, 2024 |
| transtec      | GE2 Series                  | Desktop     | [c6ff6cabae](https://linux-hardware.org/?probe=c6ff6cabae) | Mar 08, 2024 |
| transtec      | GE2 Series                  | Desktop     | [10d18de264](https://linux-hardware.org/?probe=10d18de264) | Mar 08, 2024 |
| HP            | 8767 A                      | Desktop     | [3775377131](https://linux-hardware.org/?probe=3775377131) | Mar 05, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2ce71ad477](https://linux-hardware.org/?probe=2ce71ad477) | Mar 04, 2024 |
| Acer          | Swift SF314-41              | Notebook    | [9143ec0c20](https://linux-hardware.org/?probe=9143ec0c20) | Mar 04, 2024 |
| HP            | 8767 A                      | Desktop     | [5903e66479](https://linux-hardware.org/?probe=5903e66479) | Mar 04, 2024 |
| ASRock        | N68C-GS UCC                 | Desktop     | [044465e0aa](https://linux-hardware.org/?probe=044465e0aa) | Mar 04, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [279f64b529](https://linux-hardware.org/?probe=279f64b529) | Mar 04, 2024 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [402f19be59](https://linux-hardware.org/?probe=402f19be59) | Mar 02, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [f02e3ceba7](https://linux-hardware.org/?probe=f02e3ceba7) | Mar 02, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [aad04111a4](https://linux-hardware.org/?probe=aad04111a4) | Mar 01, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [cce884f287](https://linux-hardware.org/?probe=cce884f287) | Mar 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [9d279afdd2](https://linux-hardware.org/?probe=9d279afdd2) | Feb 29, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [4e7241b44f](https://linux-hardware.org/?probe=4e7241b44f) | Feb 29, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [32c850d7a0](https://linux-hardware.org/?probe=32c850d7a0) | Feb 28, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | Notebook    | [1b28fd0c04](https://linux-hardware.org/?probe=1b28fd0c04) | Feb 28, 2024 |
| Anbernic      | Win600                      | Notebook    | [309a79c0c5](https://linux-hardware.org/?probe=309a79c0c5) | Feb 28, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [3ccf63844b](https://linux-hardware.org/?probe=3ccf63844b) | Feb 27, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [8ac39746cc](https://linux-hardware.org/?probe=8ac39746cc) | Feb 26, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f88143daa2](https://linux-hardware.org/?probe=f88143daa2) | Feb 26, 2024 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [98c285762c](https://linux-hardware.org/?probe=98c285762c) | Feb 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c6cff98a84](https://linux-hardware.org/?probe=c6cff98a84) | Feb 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [448ad7f7cf](https://linux-hardware.org/?probe=448ad7f7cf) | Feb 24, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [2d34bf7198](https://linux-hardware.org/?probe=2d34bf7198) | Feb 23, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9ff0ddca4e](https://linux-hardware.org/?probe=9ff0ddca4e) | Feb 23, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5e789b17a4](https://linux-hardware.org/?probe=5e789b17a4) | Feb 22, 2024 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [f3d1efb331](https://linux-hardware.org/?probe=f3d1efb331) | Feb 22, 2024 |
| Positivo      | C4128B-3                    | Convertible | [3b60d88c2b](https://linux-hardware.org/?probe=3b60d88c2b) | Feb 21, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | Notebook    | [6f6430db27](https://linux-hardware.org/?probe=6f6430db27) | Feb 20, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [05d7ddd936](https://linux-hardware.org/?probe=05d7ddd936) | Feb 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d3554f701e](https://linux-hardware.org/?probe=d3554f701e) | Feb 19, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [acc39c2774](https://linux-hardware.org/?probe=acc39c2774) | Feb 19, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | Notebook    | [a6ee663daa](https://linux-hardware.org/?probe=a6ee663daa) | Feb 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | Notebook    | [5b768d1518](https://linux-hardware.org/?probe=5b768d1518) | Feb 18, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [82ae92e9ec](https://linux-hardware.org/?probe=82ae92e9ec) | Feb 18, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [7987e39eb7](https://linux-hardware.org/?probe=7987e39eb7) | Feb 18, 2024 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [233bfc2f43](https://linux-hardware.org/?probe=233bfc2f43) | Feb 18, 2024 |
| Dell          | Latitude E6540              | Notebook    | [b3d3fd2a6e](https://linux-hardware.org/?probe=b3d3fd2a6e) | Feb 18, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [95950fa2f0](https://linux-hardware.org/?probe=95950fa2f0) | Feb 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [b579279ced](https://linux-hardware.org/?probe=b579279ced) | Feb 16, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [04f68f7039](https://linux-hardware.org/?probe=04f68f7039) | Feb 16, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c7fd8dfb5c](https://linux-hardware.org/?probe=c7fd8dfb5c) | Feb 14, 2024 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [9c0e3d1a1a](https://linux-hardware.org/?probe=9c0e3d1a1a) | Feb 14, 2024 |
| TUXEDO        | Book BA1510                 | Notebook    | [5e0d56776d](https://linux-hardware.org/?probe=5e0d56776d) | Feb 14, 2024 |
| Unknown       | Unknown                     | Soc         | [d7293bd35d](https://linux-hardware.org/?probe=d7293bd35d) | Feb 12, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [00b96d40d1](https://linux-hardware.org/?probe=00b96d40d1) | Feb 12, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [6c68343018](https://linux-hardware.org/?probe=6c68343018) | Feb 12, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8ec5fdc816](https://linux-hardware.org/?probe=8ec5fdc816) | Feb 12, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [833f48af30](https://linux-hardware.org/?probe=833f48af30) | Feb 12, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [35afc5314f](https://linux-hardware.org/?probe=35afc5314f) | Feb 12, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2da5a2578](https://linux-hardware.org/?probe=d2da5a2578) | Feb 11, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5862e4c7c5](https://linux-hardware.org/?probe=5862e4c7c5) | Feb 11, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [38cf6f3eff](https://linux-hardware.org/?probe=38cf6f3eff) | Feb 11, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [9c2f5e83e3](https://linux-hardware.org/?probe=9c2f5e83e3) | Feb 11, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b49ffe659b](https://linux-hardware.org/?probe=b49ffe659b) | Feb 11, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [c7ab9b0fc5](https://linux-hardware.org/?probe=c7ab9b0fc5) | Feb 11, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [847f271141](https://linux-hardware.org/?probe=847f271141) | Feb 11, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | Notebook    | [8e506a8c7e](https://linux-hardware.org/?probe=8e506a8c7e) | Feb 09, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [db94db2244](https://linux-hardware.org/?probe=db94db2244) | Feb 09, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [40f5ce16c1](https://linux-hardware.org/?probe=40f5ce16c1) | Feb 08, 2024 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [d528da165f](https://linux-hardware.org/?probe=d528da165f) | Feb 07, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [016a8ba655](https://linux-hardware.org/?probe=016a8ba655) | Feb 07, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c2d2eb2434](https://linux-hardware.org/?probe=c2d2eb2434) | Feb 06, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [671e98c249](https://linux-hardware.org/?probe=671e98c249) | Feb 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [12792a9fa5](https://linux-hardware.org/?probe=12792a9fa5) | Feb 06, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [075e2f410b](https://linux-hardware.org/?probe=075e2f410b) | Feb 05, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a6b7480c05](https://linux-hardware.org/?probe=a6b7480c05) | Feb 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [48a88ebbfb](https://linux-hardware.org/?probe=48a88ebbfb) | Feb 04, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [9af8a36721](https://linux-hardware.org/?probe=9af8a36721) | Feb 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [66ad35082d](https://linux-hardware.org/?probe=66ad35082d) | Feb 04, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [f6f5d83216](https://linux-hardware.org/?probe=f6f5d83216) | Feb 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [075ee0ca67](https://linux-hardware.org/?probe=075ee0ca67) | Feb 02, 2024 |
| Razer         | Blade 14 - RZ09-0482        | Notebook    | [49f14f0aae](https://linux-hardware.org/?probe=49f14f0aae) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afbbc9ebf0](https://linux-hardware.org/?probe=afbbc9ebf0) | Jan 31, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7ad6a0ecce](https://linux-hardware.org/?probe=7ad6a0ecce) | Jan 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [4690cc047a](https://linux-hardware.org/?probe=4690cc047a) | Jan 30, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cc38ac2dfc](https://linux-hardware.org/?probe=cc38ac2dfc) | Jan 29, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8949a81c2e](https://linux-hardware.org/?probe=8949a81c2e) | Jan 29, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [76a1ecf2ba](https://linux-hardware.org/?probe=76a1ecf2ba) | Jan 29, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e17793cd71](https://linux-hardware.org/?probe=e17793cd71) | Jan 28, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [19c619ae3f](https://linux-hardware.org/?probe=19c619ae3f) | Jan 27, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [999ea9c685](https://linux-hardware.org/?probe=999ea9c685) | Jan 26, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9b7cbb57c7](https://linux-hardware.org/?probe=9b7cbb57c7) | Jan 26, 2024 |
| HP            | 1589                        | Desktop     | [d731924276](https://linux-hardware.org/?probe=d731924276) | Jan 25, 2024 |
| Star Labs     | StarBook                    | Notebook    | [a324d865a6](https://linux-hardware.org/?probe=a324d865a6) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ff2fc44691](https://linux-hardware.org/?probe=ff2fc44691) | Jan 23, 2024 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [07799fb2f9](https://linux-hardware.org/?probe=07799fb2f9) | Jan 19, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [13086bc4ce](https://linux-hardware.org/?probe=13086bc4ce) | Jan 19, 2024 |
| Gigabyte      | B650M D3HP                  | Desktop     | [fdc83ca691](https://linux-hardware.org/?probe=fdc83ca691) | Jan 18, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [e736cc5c9a](https://linux-hardware.org/?probe=e736cc5c9a) | Jan 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [18a0aeeddf](https://linux-hardware.org/?probe=18a0aeeddf) | Jan 18, 2024 |
| HP            | Laptop 15t-dy100            | Notebook    | [68c23a7bd3](https://linux-hardware.org/?probe=68c23a7bd3) | Jan 17, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [409e7e4e42](https://linux-hardware.org/?probe=409e7e4e42) | Jan 17, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ed6bfe4f8f](https://linux-hardware.org/?probe=ed6bfe4f8f) | Jan 16, 2024 |
| Dell          | 0VHRW1 A03                  | Desktop     | [668e361f20](https://linux-hardware.org/?probe=668e361f20) | Jan 15, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [e509920598](https://linux-hardware.org/?probe=e509920598) | Jan 14, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [dc433d32e3](https://linux-hardware.org/?probe=dc433d32e3) | Jan 13, 2024 |
| HP            | 1589                        | Desktop     | [194b5a119c](https://linux-hardware.org/?probe=194b5a119c) | Jan 13, 2024 |
| MSI           | Pulse 15 B13VFK             | Notebook    | [75dde9eefd](https://linux-hardware.org/?probe=75dde9eefd) | Jan 12, 2024 |
| HP            | Laptop 15 da0018nk          | Notebook    | [11c54a0e5b](https://linux-hardware.org/?probe=11c54a0e5b) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [30679c3606](https://linux-hardware.org/?probe=30679c3606) | Jan 11, 2024 |
| Dell          | 030VXY A01                  | Desktop     | [50a18e5eba](https://linux-hardware.org/?probe=50a18e5eba) | Jan 10, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d3f6265673](https://linux-hardware.org/?probe=d3f6265673) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [7bef06dee9](https://linux-hardware.org/?probe=7bef06dee9) | Jan 10, 2024 |
| DEXP          | Aquilon C14                 | Notebook    | [d38932d74f](https://linux-hardware.org/?probe=d38932d74f) | Jan 10, 2024 |
| Gigabyte      | Z590 UD                     | Desktop     | [6953296967](https://linux-hardware.org/?probe=6953296967) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [36dc56b0ed](https://linux-hardware.org/?probe=36dc56b0ed) | Jan 09, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [ac39f0a923](https://linux-hardware.org/?probe=ac39f0a923) | Jan 08, 2024 |
| Star Labs     | StarLite                    | Notebook    | [751432d737](https://linux-hardware.org/?probe=751432d737) | Jan 07, 2024 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [ca5d4c7c00](https://linux-hardware.org/?probe=ca5d4c7c00) | Jan 07, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [33b192a7d0](https://linux-hardware.org/?probe=33b192a7d0) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [513f1c7737](https://linux-hardware.org/?probe=513f1c7737) | Jan 06, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1ecec883dd](https://linux-hardware.org/?probe=1ecec883dd) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [98da18a6c0](https://linux-hardware.org/?probe=98da18a6c0) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2602d65d52](https://linux-hardware.org/?probe=2602d65d52) | Jan 06, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [94b30c5116](https://linux-hardware.org/?probe=94b30c5116) | Jan 06, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [3b6e799f22](https://linux-hardware.org/?probe=3b6e799f22) | Jan 06, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8d63c2ea2b](https://linux-hardware.org/?probe=8d63c2ea2b) | Jan 06, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [90b8ceb64c](https://linux-hardware.org/?probe=90b8ceb64c) | Jan 05, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [42bd246eae](https://linux-hardware.org/?probe=42bd246eae) | Jan 05, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [f7ad5f683a](https://linux-hardware.org/?probe=f7ad5f683a) | Jan 04, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bf93755f2](https://linux-hardware.org/?probe=7bf93755f2) | Jan 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [da0c7ff210](https://linux-hardware.org/?probe=da0c7ff210) | Jan 04, 2024 |
| ASUSTek       | P8H67-M                     | Desktop     | [06843ca788](https://linux-hardware.org/?probe=06843ca788) | Jan 04, 2024 |
| Star Labs     | StarLite                    | Notebook    | [9f0fae17e5](https://linux-hardware.org/?probe=9f0fae17e5) | Jan 02, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a0e025d32d](https://linux-hardware.org/?probe=a0e025d32d) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [ab04c74157](https://linux-hardware.org/?probe=ab04c74157) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [ee3998d501](https://linux-hardware.org/?probe=ee3998d501) | Jan 02, 2024 |
| Acer          | Aspire A517-52G             | Notebook    | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [6826d7c88d](https://linux-hardware.org/?probe=6826d7c88d) | Jan 01, 2024 |
| Dell          | Latitude D630               | Notebook    | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| MSI           | Stealth 16Studio A13VF      | Notebook    | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [0e7bbb6dea](https://linux-hardware.org/?probe=0e7bbb6dea) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | Notebook    | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| Dell          | Precision 5560              | Notebook    | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [618dfee965](https://linux-hardware.org/?probe=618dfee965) | Dec 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [619ddf5210](https://linux-hardware.org/?probe=619ddf5210) | Dec 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [983d2046a3](https://linux-hardware.org/?probe=983d2046a3) | Dec 27, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [af7c011930](https://linux-hardware.org/?probe=af7c011930) | Dec 25, 2023 |
| ASUSTek       | D500MD                      | Desktop     | [21870febdd](https://linux-hardware.org/?probe=21870febdd) | Dec 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [47255f4ba3](https://linux-hardware.org/?probe=47255f4ba3) | Dec 25, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [c1abfa26d5](https://linux-hardware.org/?probe=c1abfa26d5) | Dec 24, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [646b9af5a9](https://linux-hardware.org/?probe=646b9af5a9) | Dec 24, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [8503d79f6c](https://linux-hardware.org/?probe=8503d79f6c) | Dec 24, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [391ef34135](https://linux-hardware.org/?probe=391ef34135) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c6caf2cc7a](https://linux-hardware.org/?probe=c6caf2cc7a) | Dec 22, 2023 |
| Dell          | Precision 5480              | Notebook    | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [f65d61f128](https://linux-hardware.org/?probe=f65d61f128) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [37ee5a4acd](https://linux-hardware.org/?probe=37ee5a4acd) | Dec 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [89fd7ee431](https://linux-hardware.org/?probe=89fd7ee431) | Dec 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [3504b628f1](https://linux-hardware.org/?probe=3504b628f1) | Dec 18, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [877c79184e](https://linux-hardware.org/?probe=877c79184e) | Dec 18, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e0b7c61c9f](https://linux-hardware.org/?probe=e0b7c61c9f) | Dec 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [25525c17e0](https://linux-hardware.org/?probe=25525c17e0) | Dec 17, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [c01e13535f](https://linux-hardware.org/?probe=c01e13535f) | Dec 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [402a34ec30](https://linux-hardware.org/?probe=402a34ec30) | Dec 17, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [776cc9f3bb](https://linux-hardware.org/?probe=776cc9f3bb) | Dec 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f02dc20ac0](https://linux-hardware.org/?probe=f02dc20ac0) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| HP            | 8592                        | Desktop     | [511feb6066](https://linux-hardware.org/?probe=511feb6066) | Dec 15, 2023 |
| HP            | 8592                        | Desktop     | [c5817452fd](https://linux-hardware.org/?probe=c5817452fd) | Dec 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ba4e95a15e](https://linux-hardware.org/?probe=ba4e95a15e) | Dec 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5eaaa9dcdc](https://linux-hardware.org/?probe=5eaaa9dcdc) | Dec 13, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [8524c9dcd5](https://linux-hardware.org/?probe=8524c9dcd5) | Dec 13, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| Dell          | 02C2CP A03                  | Server      | [3a651d8f80](https://linux-hardware.org/?probe=3a651d8f80) | Dec 13, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9b92833e92](https://linux-hardware.org/?probe=9b92833e92) | Dec 12, 2023 |
| Foxconn       | TPS01                       | Desktop     | [a417ff19ae](https://linux-hardware.org/?probe=a417ff19ae) | Dec 12, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [e07d68d658](https://linux-hardware.org/?probe=e07d68d658) | Dec 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8bf4107eed](https://linux-hardware.org/?probe=8bf4107eed) | Dec 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b87d7c1c10](https://linux-hardware.org/?probe=b87d7c1c10) | Dec 10, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ba355033b7](https://linux-hardware.org/?probe=ba355033b7) | Dec 08, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [7e738d8259](https://linux-hardware.org/?probe=7e738d8259) | Dec 08, 2023 |
| Dell          | XPS 9320                    | Notebook    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d57960be0a](https://linux-hardware.org/?probe=d57960be0a) | Dec 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1fe1dc7462](https://linux-hardware.org/?probe=1fe1dc7462) | Dec 04, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [675f997c0b](https://linux-hardware.org/?probe=675f997c0b) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [358a92be0d](https://linux-hardware.org/?probe=358a92be0d) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | Notebook    | [d1306fe54f](https://linux-hardware.org/?probe=d1306fe54f) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | Notebook    | [a0f107fc92](https://linux-hardware.org/?probe=a0f107fc92) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [3f49a16307](https://linux-hardware.org/?probe=3f49a16307) | Dec 02, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [7f49fad2c7](https://linux-hardware.org/?probe=7f49fad2c7) | Dec 02, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [fc87fb1112](https://linux-hardware.org/?probe=fc87fb1112) | Dec 01, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f9175866ae](https://linux-hardware.org/?probe=f9175866ae) | Nov 30, 2023 |
| Unknown       | Unknown                     | Soc         | [ab9297851b](https://linux-hardware.org/?probe=ab9297851b) | Nov 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [720eead0a5](https://linux-hardware.org/?probe=720eead0a5) | Nov 29, 2023 |
| Unknown       | Unknown                     | Soc         | [7acffa679c](https://linux-hardware.org/?probe=7acffa679c) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [f16bc78368](https://linux-hardware.org/?probe=f16bc78368) | Nov 29, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [d4c90a615f](https://linux-hardware.org/?probe=d4c90a615f) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [879c59cf41](https://linux-hardware.org/?probe=879c59cf41) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d71979dbb](https://linux-hardware.org/?probe=1d71979dbb) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [68644f2689](https://linux-hardware.org/?probe=68644f2689) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [9d3e14a9ba](https://linux-hardware.org/?probe=9d3e14a9ba) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6fcbd9b64c](https://linux-hardware.org/?probe=6fcbd9b64c) | Nov 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2a04ec7adc](https://linux-hardware.org/?probe=2a04ec7adc) | Nov 27, 2023 |
| Dell          | Latitude D630               | Notebook    | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [26b99168f7](https://linux-hardware.org/?probe=26b99168f7) | Nov 26, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [9e8f9907bb](https://linux-hardware.org/?probe=9e8f9907bb) | Nov 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [fde8cf07ef](https://linux-hardware.org/?probe=fde8cf07ef) | Nov 24, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [c397c51bfb](https://linux-hardware.org/?probe=c397c51bfb) | Nov 24, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4eae08c59f](https://linux-hardware.org/?probe=4eae08c59f) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [2305a057a8](https://linux-hardware.org/?probe=2305a057a8) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [8d33a8020d](https://linux-hardware.org/?probe=8d33a8020d) | Nov 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac6d14ae8d](https://linux-hardware.org/?probe=ac6d14ae8d) | Nov 20, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [221dcda3ae](https://linux-hardware.org/?probe=221dcda3ae) | Nov 19, 2023 |
| UMAX          | VisionBook 9Wi Pro          | Tablet      | [816a26352f](https://linux-hardware.org/?probe=816a26352f) | Nov 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [fc7f2d74b8](https://linux-hardware.org/?probe=fc7f2d74b8) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | Notebook    | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [85f5d912da](https://linux-hardware.org/?probe=85f5d912da) | Nov 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a868498279](https://linux-hardware.org/?probe=a868498279) | Nov 18, 2023 |
| Dell          | Precision 5480              | Notebook    | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [477c710fe1](https://linux-hardware.org/?probe=477c710fe1) | Nov 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [76092ba872](https://linux-hardware.org/?probe=76092ba872) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6a5b4cf051](https://linux-hardware.org/?probe=6a5b4cf051) | Nov 15, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f27cfbe5ca](https://linux-hardware.org/?probe=f27cfbe5ca) | Nov 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1105d135a2](https://linux-hardware.org/?probe=1105d135a2) | Nov 14, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8080101e6f](https://linux-hardware.org/?probe=8080101e6f) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [de369665dc](https://linux-hardware.org/?probe=de369665dc) | Nov 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [9d2aeb3f90](https://linux-hardware.org/?probe=9d2aeb3f90) | Nov 13, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [ab65845e2f](https://linux-hardware.org/?probe=ab65845e2f) | Nov 12, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [51cd292a70](https://linux-hardware.org/?probe=51cd292a70) | Nov 12, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [3efb188b16](https://linux-hardware.org/?probe=3efb188b16) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [16d356b88c](https://linux-hardware.org/?probe=16d356b88c) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [bce581924a](https://linux-hardware.org/?probe=bce581924a) | Nov 12, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [6996973cde](https://linux-hardware.org/?probe=6996973cde) | Nov 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4aae90aee9](https://linux-hardware.org/?probe=4aae90aee9) | Nov 11, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [4c763ba78a](https://linux-hardware.org/?probe=4c763ba78a) | Nov 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [379584ba47](https://linux-hardware.org/?probe=379584ba47) | Nov 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [1de1299edf](https://linux-hardware.org/?probe=1de1299edf) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecc25dda7](https://linux-hardware.org/?probe=7ecc25dda7) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [715aee0ee7](https://linux-hardware.org/?probe=715aee0ee7) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [b865e2f52d](https://linux-hardware.org/?probe=b865e2f52d) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [503b6e943c](https://linux-hardware.org/?probe=503b6e943c) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8e8cfaa103](https://linux-hardware.org/?probe=8e8cfaa103) | Nov 05, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [40deedc435](https://linux-hardware.org/?probe=40deedc435) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [57d643d36b](https://linux-hardware.org/?probe=57d643d36b) | Oct 31, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7b6fe38982](https://linux-hardware.org/?probe=7b6fe38982) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f6e8c279ef](https://linux-hardware.org/?probe=f6e8c279ef) | Oct 31, 2023 |
| Dell          | Latitude 7320               | Notebook    | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0cea8f6bb](https://linux-hardware.org/?probe=d0cea8f6bb) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [50b77f9f9e](https://linux-hardware.org/?probe=50b77f9f9e) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [78bdbc6419](https://linux-hardware.org/?probe=78bdbc6419) | Oct 25, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f4a0aca53d](https://linux-hardware.org/?probe=f4a0aca53d) | Oct 24, 2023 |
| HP            | 3397                        | Desktop     | [1344d9d38b](https://linux-hardware.org/?probe=1344d9d38b) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [9a65857d3c](https://linux-hardware.org/?probe=9a65857d3c) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [001c668695](https://linux-hardware.org/?probe=001c668695) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [95d6dab241](https://linux-hardware.org/?probe=95d6dab241) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [4b93c11bcb](https://linux-hardware.org/?probe=4b93c11bcb) | Oct 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [62ae73f967](https://linux-hardware.org/?probe=62ae73f967) | Oct 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [b677f99638](https://linux-hardware.org/?probe=b677f99638) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [3368da4a2b](https://linux-hardware.org/?probe=3368da4a2b) | Oct 19, 2023 |
| ASRock        | H170 Pro4S                  | Desktop     | [e3960f114d](https://linux-hardware.org/?probe=e3960f114d) | Oct 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| Dell          | 0MNPJ9 A03                  | Desktop     | [36e7a1e261](https://linux-hardware.org/?probe=36e7a1e261) | Oct 18, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [1e2597a152](https://linux-hardware.org/?probe=1e2597a152) | Oct 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [65277f3f01](https://linux-hardware.org/?probe=65277f3f01) | Oct 16, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [d3cf683bad](https://linux-hardware.org/?probe=d3cf683bad) | Oct 15, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| PINE64        | Pinebook Pro                | Soc         | [e62b12571a](https://linux-hardware.org/?probe=e62b12571a) | Oct 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [f0f128becf](https://linux-hardware.org/?probe=f0f128becf) | Oct 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [212f394b32](https://linux-hardware.org/?probe=212f394b32) | Oct 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [586d5eef76](https://linux-hardware.org/?probe=586d5eef76) | Oct 08, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6f6e394cdf](https://linux-hardware.org/?probe=6f6e394cdf) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [c5d7f755ac](https://linux-hardware.org/?probe=c5d7f755ac) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| HP            | 1589                        | Desktop     | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| Dell          | 0NGT4D A01                  | Mini pc     | [457dfea13d](https://linux-hardware.org/?probe=457dfea13d) | Oct 03, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [e684c274a6](https://linux-hardware.org/?probe=e684c274a6) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fd9631bea](https://linux-hardware.org/?probe=8fd9631bea) | Oct 03, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [5e6d01b044](https://linux-hardware.org/?probe=5e6d01b044) | Oct 03, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [5018997f48](https://linux-hardware.org/?probe=5018997f48) | Oct 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [25c3794b84](https://linux-hardware.org/?probe=25c3794b84) | Oct 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [ff0e651b1b](https://linux-hardware.org/?probe=ff0e651b1b) | Oct 01, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [c2ba80af3b](https://linux-hardware.org/?probe=c2ba80af3b) | Sep 26, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6dca52cc54](https://linux-hardware.org/?probe=6dca52cc54) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [fb93d199f3](https://linux-hardware.org/?probe=fb93d199f3) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8a581a8a85](https://linux-hardware.org/?probe=8a581a8a85) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [d17427680f](https://linux-hardware.org/?probe=d17427680f) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [1c0c7815dd](https://linux-hardware.org/?probe=1c0c7815dd) | Sep 24, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [b0297cff82](https://linux-hardware.org/?probe=b0297cff82) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7732f1eb9b](https://linux-hardware.org/?probe=7732f1eb9b) | Sep 22, 2023 |
| Dell          | 0RY206                      | Desktop     | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [e1b56bb588](https://linux-hardware.org/?probe=e1b56bb588) | Sep 19, 2023 |
| ASRock        | B85M                        | Desktop     | [8a3dc73931](https://linux-hardware.org/?probe=8a3dc73931) | Sep 18, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [8dcd49002d](https://linux-hardware.org/?probe=8dcd49002d) | Sep 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [524eb9d966](https://linux-hardware.org/?probe=524eb9d966) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [2f86649b91](https://linux-hardware.org/?probe=2f86649b91) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [077f5b81b8](https://linux-hardware.org/?probe=077f5b81b8) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [12f4431262](https://linux-hardware.org/?probe=12f4431262) | Sep 12, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [0dabf67d5f](https://linux-hardware.org/?probe=0dabf67d5f) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [ce24c28731](https://linux-hardware.org/?probe=ce24c28731) | Sep 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [87971ac772](https://linux-hardware.org/?probe=87971ac772) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [a6bbf0ac50](https://linux-hardware.org/?probe=a6bbf0ac50) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [7987abcc44](https://linux-hardware.org/?probe=7987abcc44) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [f3cbaf1a86](https://linux-hardware.org/?probe=f3cbaf1a86) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [b0e01251ca](https://linux-hardware.org/?probe=b0e01251ca) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [32a90ea48e](https://linux-hardware.org/?probe=32a90ea48e) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f0e20e0089](https://linux-hardware.org/?probe=f0e20e0089) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [ad154077da](https://linux-hardware.org/?probe=ad154077da) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [e3ca221ba9](https://linux-hardware.org/?probe=e3ca221ba9) | Aug 28, 2023 |
| Dell          | 0RY206                      | Desktop     | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [63a0a35452](https://linux-hardware.org/?probe=63a0a35452) | Aug 18, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Dell          | 0RY206                      | Desktop     | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [aa4c1f2237](https://linux-hardware.org/?probe=aa4c1f2237) | Aug 13, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [13aee7ad4d](https://linux-hardware.org/?probe=13aee7ad4d) | Aug 13, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [6f3ec125fd](https://linux-hardware.org/?probe=6f3ec125fd) | Aug 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ae8c13e17e](https://linux-hardware.org/?probe=ae8c13e17e) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4fe5238f21](https://linux-hardware.org/?probe=4fe5238f21) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [5712d7b72d](https://linux-hardware.org/?probe=5712d7b72d) | Aug 11, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7e6ad75fc4](https://linux-hardware.org/?probe=7e6ad75fc4) | Jul 28, 2023 |
| MSI           | TRX40 PRO 10G               | Desktop     | [6391114079](https://linux-hardware.org/?probe=6391114079) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d9839bbe](https://linux-hardware.org/?probe=60d9839bbe) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [45149f899d](https://linux-hardware.org/?probe=45149f899d) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [8504edcacf](https://linux-hardware.org/?probe=8504edcacf) | Jul 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4884c4b183](https://linux-hardware.org/?probe=4884c4b183) | Jul 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo_2.14/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.1.57-gentoo          | 16        | 4.31%   |
| 6.1.57-gentoo-x86_64   | 14        | 3.77%   |
| 6.6.13-gentoo          | 12        | 3.23%   |
| 6.1.67-gentoo          | 10        | 2.7%    |
| 6.1.53-gentoo-r1       | 10        | 2.7%    |
| 6.6.13-gentoo-x86_64   | 9         | 2.43%   |
| 6.6.21-gentoo-dist     | 8         | 2.16%   |
| 6.1.46-gentoo          | 8         | 2.16%   |
| 6.6.21-gentoo          | 7         | 1.89%   |
| 6.6.13-gentoo-dist     | 7         | 1.89%   |
| 6.6.21-gentoo-x86_64   | 6         | 1.62%   |
| 6.1.67-gentoo-x86_64   | 6         | 1.62%   |
| 6.1.67-gentoo-dist     | 6         | 1.62%   |
| 6.6.8-gentoo           | 5         | 1.35%   |
| 6.6.16-gentoo-dist     | 5         | 1.35%   |
| 6.6.0-gentoo           | 5         | 1.35%   |
| 6.4.10-gentoo-x86_64   | 5         | 1.35%   |
| 6.1.57-gentoo-dist     | 5         | 1.35%   |
| 6.1.41-gentoo          | 5         | 1.35%   |
| 6.7.0-gentoo           | 4         | 1.08%   |
| 6.6.8-gentoo-x86_64    | 4         | 1.08%   |
| 6.6.2-gentoo           | 4         | 1.08%   |
| 6.5.7-gentoo           | 4         | 1.08%   |
| 6.1.46-gentoo-x86_64   | 4         | 1.08%   |
| 6.7.4-gentoo           | 3         | 0.81%   |
| 6.6.9-gentoo           | 3         | 0.81%   |
| 6.6.3-gentoo           | 3         | 0.81%   |
| 6.5.0-gentoo           | 3         | 0.81%   |
| 6.1.69-gentoo-dist     | 3         | 0.81%   |
| 6.1.60-gentoo-dist     | 3         | 0.81%   |
| 6.1.46-gentoo-dist     | 3         | 0.81%   |
| 6.7.4-gentoo-dist      | 2         | 0.54%   |
| 6.7.0-rc1              | 2         | 0.54%   |
| 6.6.7-gentoo-dist      | 2         | 0.54%   |
| 6.6.0-gentoo-x86_64    | 2         | 0.54%   |
| 6.5.9-gentoo-x86_64    | 2         | 0.54%   |
| 6.5.9-gentoo           | 2         | 0.54%   |
| 6.5.8-gentoo-r1-x86_64 | 2         | 0.54%   |
| 6.5.8-gentoo-r1        | 2         | 0.54%   |
| 6.5.7-gentoo-x86_64    | 2         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.57  | 40        | 10.87%  |
| 6.6.13  | 31        | 8.42%   |
| 6.6.21  | 23        | 6.25%   |
| 6.1.67  | 23        | 6.25%   |
| 6.1.53  | 18        | 4.89%   |
| 6.1.46  | 18        | 4.89%   |
| 6.6.8   | 13        | 3.53%   |
| 6.7.0   | 9         | 2.45%   |
| 6.6.0   | 9         | 2.45%   |
| 6.1.41  | 9         | 2.45%   |
| 6.6.16  | 8         | 2.17%   |
| 6.5.7   | 8         | 2.17%   |
| 6.4.10  | 8         | 2.17%   |
| 6.6.2   | 7         | 1.9%    |
| 6.7.4   | 6         | 1.63%   |
| 6.5.9   | 6         | 1.63%   |
| 6.5.8   | 6         | 1.63%   |
| 6.5.0   | 6         | 1.63%   |
| 6.6.3   | 5         | 1.36%   |
| 6.6.1   | 5         | 1.36%   |
| 6.5.5   | 5         | 1.36%   |
| 6.6.9   | 4         | 1.09%   |
| 6.5.3   | 4         | 1.09%   |
| 6.7.1   | 3         | 0.82%   |
| 6.6.7   | 3         | 0.82%   |
| 6.6.6   | 3         | 0.82%   |
| 6.6.14  | 3         | 0.82%   |
| 6.5.1   | 3         | 0.82%   |
| 6.4.4   | 3         | 0.82%   |
| 6.4.3   | 3         | 0.82%   |
| 6.4.11  | 3         | 0.82%   |
| 6.1.69  | 3         | 0.82%   |
| 6.1.66  | 3         | 0.82%   |
| 6.1.60  | 3         | 0.82%   |
| 6.9.0   | 2         | 0.54%   |
| 6.8.1   | 2         | 0.54%   |
| 6.8.0   | 2         | 0.54%   |
| 6.7.6   | 2         | 0.54%   |
| 6.7.3   | 2         | 0.54%   |
| 6.7.2   | 2         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 113       | 33.43%  |
| 6.1     | 111       | 32.84%  |
| 6.5     | 40        | 11.83%  |
| 6.4     | 27        | 7.99%   |
| 6.7     | 26        | 7.69%   |
| 6.8     | 7         | 2.07%   |
| 5.15    | 5         | 1.48%   |
| 6.3     | 3         | 0.89%   |
| 6.9     | 2         | 0.59%   |
| 6.2     | 1         | 0.3%    |
| 5.19    | 1         | 0.3%    |
| 5.16    | 1         | 0.3%    |
| 5.14    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 300       | 96.77%  |
| aarch64     | 6         | 1.94%   |
| loongarch64 | 2         | 0.65%   |
| i686        | 2         | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 101       | 31.86%  |
| KDE5          | 84        | 26.5%   |
| XFCE          | 37        | 11.67%  |
| GNOME         | 32        | 10.09%  |
| Hyprland      | 12        | 3.79%   |
| MATE          | 9         | 2.84%   |
| LXQt          | 8         | 2.52%   |
| DWM           | 8         | 2.52%   |
| i3            | 5         | 1.58%   |
| X-Cinnamon    | 4         | 1.26%   |
| sway          | 3         | 0.95%   |
| KDE           | 3         | 0.95%   |
| KDE6          | 2         | 0.63%   |
| Trinity       | 1         | 0.32%   |
| LXDE          | 1         | 0.32%   |
| ICEWM         | 1         | 0.32%   |
| GNOME Classic | 1         | 0.32%   |
| fluxbox       | 1         | 0.32%   |
| Enlightenment | 1         | 0.32%   |
| dwl           | 1         | 0.32%   |
| Cinnamon      | 1         | 0.32%   |
| bspwm         | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 120       | 36.92%  |
| Wayland | 93        | 28.62%  |
| Unknown | 66        | 20.31%  |
| Tty     | 46        | 14.15%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 132       | 41.9%   |
| SDDM    | 97        | 30.79%  |
| LightDM | 49        | 15.56%  |
| GDM     | 19        | 6.03%   |
| SLiM    | 7         | 2.22%   |
| GREETD  | 5         | 1.59%   |
| XDM     | 2         | 0.63%   |
| LXDM    | 2         | 0.63%   |
| TDM     | 1         | 0.32%   |
| Ly      | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_US          | 114       | 36.42%  |
| C.UTF8         | 44        | 14.06%  |
| Unknown        | 33        | 10.54%  |
| en_GB          | 24        | 7.67%   |
| ru_RU          | 13        | 4.15%   |
| fr_FR          | 11        | 3.51%   |
| de_DE          | 11        | 3.51%   |
| C              | 11        | 3.51%   |
| it_IT          | 5         | 1.6%    |
| cs_CZ          | 5         | 1.6%    |
| zh_CN          | 4         | 1.28%   |
| pt_BR          | 3         | 0.96%   |
| es_ES          | 3         | 0.96%   |
| es_AR          | 3         | 0.96%   |
| de_CH          | 3         | 0.96%   |
| POSIX          | 2         | 0.64%   |
| pl_PL          | 2         | 0.64%   |
| en_IE          | 2         | 0.64%   |
| en_DK          | 2         | 0.64%   |
| zh_TW          | 1         | 0.32%   |
| uk_UA          | 1         | 0.32%   |
| ru_RU.UTF8     | 1         | 0.32%   |
| nl_NL          | 1         | 0.32%   |
| lt_LT          | 1         | 0.32%   |
| ja_JP          | 1         | 0.32%   |
| it_IT.iso88591 | 1         | 0.32%   |
| fr_CA          | 1         | 0.32%   |
| fi_FI          | 1         | 0.32%   |
| es_MX          | 1         | 0.32%   |
| es_ES.UTF8     | 1         | 0.32%   |
| es_CL          | 1         | 0.32%   |
| en_IE@euro     | 1         | 0.32%   |
| en_AU          | 1         | 0.32%   |
| en             | 1         | 0.32%   |
| el_GR          | 1         | 0.32%   |
| ca_ES          | 1         | 0.32%   |
| bg_BG          | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 264       | 84.35%  |
| BIOS | 49        | 15.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 156       | 50%     |
| Btrfs    | 74        | 23.72%  |
| Xfs      | 43        | 13.78%  |
| F2fs     | 17        | 5.45%   |
| Zfs      | 14        | 4.49%   |
| XXXXXXX  | 4         | 1.28%   |
| Bcachefs | 2         | 0.64%   |
| Reiserfs | 1         | 0.32%   |
| Ext2     | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 280       | 90.03%  |
| MBR     | 16        | 5.14%   |
| Unknown | 15        | 4.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 73.19%  |
| Yes       | 85        | 26.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 226       | 71.75%  |
| Yes       | 89        | 28.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 74        | 23.87%  |
| Lenovo                  | 45        | 14.52%  |
| Hewlett-Packard         | 34        | 10.97%  |
| Dell                    | 31        | 10%     |
| Gigabyte Technology     | 28        | 9.03%   |
| MSI                     | 23        | 7.42%   |
| ASRock                  | 11        | 3.55%   |
| Unknown                 | 9         | 2.9%    |
| Framework               | 7         | 2.26%   |
| Acer                    | 6         | 1.94%   |
| Supermicro              | 4         | 1.29%   |
| Star Labs               | 2         | 0.65%   |
| Raspberry Pi Foundation | 2         | 0.65%   |
| Notebook                | 2         | 0.65%   |
| Loongson                | 2         | 0.65%   |
| Intel                   | 2         | 0.65%   |
| Fujitsu                 | 2         | 0.65%   |
| UMAX                    | 1         | 0.32%   |
| TUXEDO                  | 1         | 0.32%   |
| TULPAR                  | 1         | 0.32%   |
| transtec                | 1         | 0.32%   |
| Timi                    | 1         | 0.32%   |
| SZMZ                    | 1         | 0.32%   |
| System76                | 1         | 0.32%   |
| Razer                   | 1         | 0.32%   |
| Quanta                  | 1         | 0.32%   |
| Positivo                | 1         | 0.32%   |
| PINE64                  | 1         | 0.32%   |
| Medion                  | 1         | 0.32%   |
| IBM                     | 1         | 0.32%   |
| HUAWEI                  | 1         | 0.32%   |
| Google                  | 1         | 0.32%   |
| Foxconn                 | 1         | 0.32%   |
| Fanless Mini PC         | 1         | 0.32%   |
| DEXP                    | 1         | 0.32%   |
| Colorful Technology     | 1         | 0.32%   |
| Chuwi                   | 1         | 0.32%   |
| BESSTAR Tech            | 1         | 0.32%   |
| BANGHO                  | 1         | 0.32%   |
| ASRockRack              | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 9         | 2.9%    |
| Framework Laptop (13th Gen Intel Core)     | 4         | 1.29%   |
| HP EliteBook 845 14 inch G10 Notebook PC   | 3         | 0.97%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 3         | 0.97%   |
| Dell Precision 5480                        | 3         | 0.97%   |
| ASUS TUF Gaming B550-PLUS                  | 3         | 0.97%   |
| Supermicro Super Server                    | 2         | 0.65%   |
| Notebook NS5x_NS7xPU                       | 2         | 0.65%   |
| MSI MS-7C02                                | 2         | 0.65%   |
| Lenovo Yoga 7 16ARP8 83BS                  | 2         | 0.65%   |
| HP Z420 Workstation                        | 2         | 0.65%   |
| Gigabyte X570 AORUS ELITE                  | 2         | 0.65%   |
| Gigabyte B550 AORUS ELITE V2               | 2         | 0.65%   |
| Gigabyte B450M DS3H                        | 2         | 0.65%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II      | 2         | 0.65%   |
| ASUS ROG STRIX X670E-E GAMING WIFI         | 2         | 0.65%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.65%   |
| ASUS PRIME H510M-E                         | 2         | 0.65%   |
| ASUS PRIME B660-PLUS D4                    | 2         | 0.65%   |
| ASUS M3A78-CM                              | 2         | 0.65%   |
| UMAX VisionBook 9Wi Pro                    | 1         | 0.32%   |
| TUXEDO Book BA1510                         | 1         | 0.32%   |
| TULPAR A5 V20.3                            | 1         | 0.32%   |
| transtec GE2 Series                        | 1         | 0.32%   |
| Timi RedmiBook Pro 15S                     | 1         | 0.32%   |
| SZMZ X99M-G2                               | 1         | 0.32%   |
| System76 Pangolin                          | 1         | 0.32%   |
| Supermicro X10SL7-F                        | 1         | 0.32%   |
| Supermicro SYS-5038MD-H24TRF-OS012         | 1         | 0.32%   |
| Star Labs StarLite                         | 1         | 0.32%   |
| Star Labs StarBook                         | 1         | 0.32%   |
| Razer Blade 14 - RZ09-0482                 | 1         | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 1         | 0.32%   |
| RPi Raspberry Pi 3 Model B Rev 1.2         | 1         | 0.32%   |
| Quanta S210-X12MS                          | 1         | 0.32%   |
| Positivo C4128B-3                          | 1         | 0.32%   |
| PINE64 Pinebook Pro                        | 1         | 0.32%   |
| MSI Stealth 16Studio A13VF                 | 1         | 0.32%   |
| MSI Pulse 15 B13VFK                        | 1         | 0.32%   |
| MSI MS-7E27                                | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 30        | 9.68%   |
| ASUS ROG         | 20        | 6.45%   |
| ASUS PRIME       | 17        | 5.48%   |
| ASUS TUF         | 9         | 2.9%    |
| Unknown          | 9         | 2.9%    |
| HP EliteBook     | 8         | 2.58%   |
| Dell Precision   | 8         | 2.58%   |
| ASUS VivoBook    | 8         | 2.58%   |
| HP Laptop        | 7         | 2.26%   |
| Framework Laptop | 7         | 2.26%   |
| Dell Latitude    | 6         | 1.94%   |
| HP ProBook       | 5         | 1.61%   |
| Dell XPS         | 5         | 1.61%   |
| Lenovo Legion    | 4         | 1.29%   |
| Dell OptiPlex    | 4         | 1.29%   |
| Dell Inspiron    | 4         | 1.29%   |
| ASUS ASUS        | 4         | 1.29%   |
| Acer Aspire      | 4         | 1.29%   |
| Lenovo IdeaPad   | 3         | 0.97%   |
| HP Victus        | 3         | 0.97%   |
| HP Pavilion      | 3         | 0.97%   |
| Gigabyte X570    | 3         | 0.97%   |
| Gigabyte B550    | 3         | 0.97%   |
| ASUS ZenBook     | 3         | 0.97%   |
| Supermicro Super | 2         | 0.65%   |
| RPi Raspberry    | 2         | 0.65%   |
| Notebook NS5x    | 2         | 0.65%   |
| MSI MS-7C02      | 2         | 0.65%   |
| Lenovo Yoga      | 2         | 0.65%   |
| HP Z420          | 2         | 0.65%   |
| HP Spectre       | 2         | 0.65%   |
| Gigabyte B560M   | 2         | 0.65%   |
| Gigabyte B450M   | 2         | 0.65%   |
| Dell G5          | 2         | 0.65%   |
| ASUS M3A78-CM    | 2         | 0.65%   |
| Acer Swift       | 2         | 0.65%   |
| UMAX VisionBook  | 1         | 0.32%   |
| TUXEDO Book      | 1         | 0.32%   |
| TULPAR A5        | 1         | 0.32%   |
| transtec GE2     | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 47        | 15.16%  |
| 2022    | 47        | 15.16%  |
| 2021    | 42        | 13.55%  |
| 2020    | 34        | 10.97%  |
| 2019    | 32        | 10.32%  |
| 2018    | 24        | 7.74%   |
| 2017    | 13        | 4.19%   |
| 2012    | 12        | 3.87%   |
| Unknown | 11        | 3.55%   |
| 2013    | 8         | 2.58%   |
| 2014    | 7         | 2.26%   |
| 2010    | 7         | 2.26%   |
| 2016    | 6         | 1.94%   |
| 2015    | 4         | 1.29%   |
| 2011    | 4         | 1.29%   |
| 2009    | 4         | 1.29%   |
| 2008    | 3         | 0.97%   |
| 2007    | 3         | 0.97%   |
| 2024    | 1         | 0.32%   |
| 2004    | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 144       | 46.45%  |
| Desktop        | 142       | 45.81%  |
| Convertible    | 7         | 2.26%   |
| System on chip | 6         | 1.94%   |
| Server         | 6         | 1.94%   |
| Tablet         | 2         | 0.65%   |
| Mini pc        | 2         | 0.65%   |
| Stick pc       | 1         | 0.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 300       | 96.46%  |
| Enabled  | 11        | 3.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 309       | 99.68%  |
| Yes  | 1         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 90        | 28.94%  |
| 64.01-256.0 | 52        | 16.72%  |
| 16.01-24.0  | 52        | 16.72%  |
| 8.01-16.0   | 46        | 14.79%  |
| 4.01-8.0    | 32        | 10.29%  |
| 24.01-32.0  | 21        | 6.75%   |
| 3.01-4.0    | 12        | 3.86%   |
| 1.01-2.0    | 3         | 0.96%   |
| 2.01-3.0    | 1         | 0.32%   |
| 0.51-1.0    | 1         | 0.32%   |
| 0.01-0.5    | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 69        | 20.23%  |
| 1.01-2.0   | 65        | 19.06%  |
| 2.01-3.0   | 56        | 16.42%  |
| 3.01-4.0   | 46        | 13.49%  |
| 0.51-1.0   | 33        | 9.68%   |
| 8.01-16.0  | 31        | 9.09%   |
| 0.01-0.5   | 19        | 5.57%   |
| 16.01-24.0 | 16        | 4.69%   |
| 32.01-64.0 | 4         | 1.17%   |
| 24.01-32.0 | 2         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 148       | 46.84%  |
| 2      | 83        | 26.27%  |
| 3      | 31        | 9.81%   |
| 4      | 21        | 6.65%   |
| 5      | 10        | 3.16%   |
| 6      | 8         | 2.53%   |
| 7      | 6         | 1.9%    |
| 8      | 4         | 1.27%   |
| 31     | 1         | 0.32%   |
| 19     | 1         | 0.32%   |
| 14     | 1         | 0.32%   |
| 13     | 1         | 0.32%   |
| 9      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 255       | 81.99%  |
| Yes       | 56        | 18.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 259       | 83.28%  |
| No        | 52        | 16.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 72.58%  |
| No        | 85        | 27.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 66.45%  |
| No        | 104       | 33.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 64        | 20.51%  |
| Germany         | 33        | 10.58%  |
| Russia          | 28        | 8.97%   |
| UK              | 15        | 4.81%   |
| France          | 14        | 4.49%   |
| Poland          | 13        | 4.17%   |
| Czechia         | 12        | 3.85%   |
| Spain           | 11        | 3.53%   |
| Italy           | 11        | 3.53%   |
| China           | 11        | 3.53%   |
| Belgium         | 11        | 3.53%   |
| Canada          | 7         | 2.24%   |
| Brazil          | 7         | 2.24%   |
| Sweden          | 6         | 1.92%   |
| Ireland         | 6         | 1.92%   |
| Switzerland     | 5         | 1.6%    |
| Netherlands     | 5         | 1.6%    |
| Finland         | 5         | 1.6%    |
| Greece          | 4         | 1.28%   |
| Austria         | 4         | 1.28%   |
| Argentina       | 4         | 1.28%   |
| Turkey          | 3         | 0.96%   |
| Bulgaria        | 3         | 0.96%   |
| Ukraine         | 2         | 0.64%   |
| The Netherlands | 2         | 0.64%   |
| Slovakia        | 2         | 0.64%   |
| New Zealand     | 2         | 0.64%   |
| Japan           | 2         | 0.64%   |
| Indonesia       | 2         | 0.64%   |
| Hong Kong       | 2         | 0.64%   |
| Taiwan          | 1         | 0.32%   |
| South Africa    | 1         | 0.32%   |
| Serbia          | 1         | 0.32%   |
| Portugal        | 1         | 0.32%   |
| Paraguay        | 1         | 0.32%   |
| Mexico          | 1         | 0.32%   |
| Malaysia        | 1         | 0.32%   |
| Luxembourg      | 1         | 0.32%   |
| Latvia          | 1         | 0.32%   |
| Iran            | 1         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 7         | 2.14%   |
| St Petersburg     | 6         | 1.83%   |
| Louvain-la-Neuve  | 6         | 1.83%   |
| Stockholm         | 5         | 1.53%   |
| Šlapanice        | 5         | 1.53%   |
| New York          | 5         | 1.53%   |
| Milano            | 5         | 1.53%   |
| Berlin            | 5         | 1.53%   |
| Warsaw            | 4         | 1.22%   |
| Toulouse          | 4         | 1.22%   |
| Dublin            | 4         | 1.22%   |
| Cieszyn           | 4         | 1.22%   |
| Athens            | 4         | 1.22%   |
| Rostov-on-Don     | 3         | 0.92%   |
| Prague            | 3         | 0.92%   |
| Paris             | 3         | 0.92%   |
| Miami             | 3         | 0.92%   |
| Madrid            | 3         | 0.92%   |
| Helsinki          | 3         | 0.92%   |
| Dumfries          | 3         | 0.92%   |
| Beijing           | 3         | 0.92%   |
| Amsterdam         | 3         | 0.92%   |
| Vienna            | 2         | 0.61%   |
| Sofia             | 2         | 0.61%   |
| San Antonio       | 2         | 0.61%   |
| Samarinda         | 2         | 0.61%   |
| Pittsburgh        | 2         | 0.61%   |
| Oulx              | 2         | 0.61%   |
| Novosibirsk       | 2         | 0.61%   |
| Mönchengladbach  | 2         | 0.61%   |
| Lincoln           | 2         | 0.61%   |
| Le Boulou         | 2         | 0.61%   |
| Krefeld           | 2         | 0.61%   |
| Krasnodar         | 2         | 0.61%   |
| Istanbul          | 2         | 0.61%   |
| Irkutsk           | 2         | 0.61%   |
| Igualada          | 2         | 0.61%   |
| Girona            | 2         | 0.61%   |
| Frankfurt am Main | 2         | 0.61%   |
| Detmold           | 2         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 111       | 190    | 20.26%  |
| Seagate                     | 54        | 101    | 9.85%   |
| WDC                         | 49        | 91     | 8.94%   |
| Sandisk                     | 40        | 53     | 7.3%    |
| SK hynix                    | 23        | 25     | 4.2%    |
| Kingston                    | 23        | 29     | 4.2%    |
| Toshiba                     | 21        | 61     | 3.83%   |
| Phison Electronics          | 20        | 26     | 3.65%   |
| Intel                       | 20        | 27     | 3.65%   |
| Unknown                     | 16        | 24     | 2.92%   |
| Micron Technology           | 16        | 22     | 2.92%   |
| KIOXIA                      | 14        | 17     | 2.55%   |
| Micron/Crucial Technology   | 13        | 15     | 2.37%   |
| Crucial                     | 13        | 21     | 2.37%   |
| Kingston Technology Company | 10        | 10     | 1.82%   |
| Hitachi                     | 8         | 30     | 1.46%   |
| A-DATA Technology           | 6         | 7      | 1.09%   |
| Realtek Semiconductor       | 5         | 5      | 0.91%   |
| China                       | 5         | 7      | 0.91%   |
| Unknown                     | 5         | 5      | 0.91%   |
| MAXIO Technology (Hangzhou) | 4         | 4      | 0.73%   |
| HGST                        | 4         | 5      | 0.73%   |
| GOODRAM                     | 4         | 25     | 0.73%   |
| ADATA Technology            | 4         | 5      | 0.73%   |
| Yangtze Memory Technologies | 3         | 5      | 0.55%   |
| Transcend                   | 3         | 3      | 0.55%   |
| Silicon Motion              | 3         | 3      | 0.55%   |
| Patriot                     | 3         | 5      | 0.55%   |
| OCZ                         | 3         | 3      | 0.55%   |
| Verbatim                    | 2         | 2      | 0.36%   |
| Union Memory                | 2         | 3      | 0.36%   |
| Seagate Technology          | 2         | 2      | 0.36%   |
| SABRENT                     | 2         | 2      | 0.36%   |
| Phison                      | 2         | 2      | 0.36%   |
| LITEON                      | 2         | 3      | 0.36%   |
| KingSpec                    | 2         | 3      | 0.36%   |
| Intenso                     | 2         | 2      | 0.36%   |
| Hewlett-Packard             | 2         | 8      | 0.36%   |
| Fujitsu                     | 2         | 2      | 0.36%   |
| Yangtze Memory              | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 34        | 5.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB              | 27        | 4.32%   |
| Samsung SSD 980 1TB                                             | 11        | 1.76%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                             | 8         | 1.28%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 7         | 1.12%   |
| Phison E12 NVMe Controller 2TB                                  | 7         | 1.12%   |
| Unknown MMC Card  128GB                                         | 6         | 0.96%   |
| Seagate ST4000DM004-2CV104 4TB                                  | 6         | 0.96%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 5         | 0.8%    |
| Sandisk WD Blue SN550 NVMe SSD 2TB                              | 5         | 0.8%    |
| Sandisk WD Black SN850 512GB                                    | 5         | 0.8%    |
| Samsung SSD 860 EVO 500GB                                       | 5         | 0.8%    |
| Samsung SSD 860 EVO 1TB                                         | 5         | 0.8%    |
| Kingston Company A2000 NVMe SSD 500GB                           | 5         | 0.8%    |
| Intel SSD 660P Series 1024GB                                    | 5         | 0.8%    |
| Intel SSD 600P Series 256GB                                     | 5         | 0.8%    |
| Unknown                                                         | 5         | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                                | 4         | 0.64%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 4         | 0.64%   |
| Seagate ST2000DM008-2UB102 2TB                                  | 4         | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                | 4         | 0.64%   |
| Samsung SSD 990 PRO 2TB                                         | 4         | 0.64%   |
| Samsung SSD 860 EVO 250GB                                       | 4         | 0.64%   |
| Samsung SSD 850 EVO 500GB                                       | 4         | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB               | 4         | 0.64%   |
| Kingston SA400S37480G 480GB SSD                                 | 4         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                                     | 4         | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 4         | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 3         | 0.48%   |
| WDC WD30EFRX-68EUZN0 3TB                                        | 3         | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 3         | 0.48%   |
| Toshiba MQ04ABF100 1TB                                          | 3         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive 512GB                     | 3         | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB           | 3         | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                                 | 3         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 0.48%   |
| Sandisk WD_BLACK SN850X 2000GB                                  | 3         | 0.48%   |
| SanDisk SSD PLUS 240GB                                          | 3         | 0.48%   |
| Samsung SSD 870 EVO 1TB                                         | 3         | 0.48%   |
| Samsung SSD 860 QVO 1TB                                         | 3         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 100    | 39.71%  |
| WDC                 | 42        | 78     | 30.88%  |
| Toshiba             | 17        | 57     | 12.5%   |
| Hitachi             | 8         | 30     | 5.88%   |
| HGST                | 4         | 5      | 2.94%   |
| Samsung Electronics | 2         | 3      | 1.47%   |
| SABRENT             | 2         | 2      | 1.47%   |
| Fujitsu             | 2         | 2      | 1.47%   |
| Teleplan            | 1         | 1      | 0.74%   |
| NETAPP              | 1         | 3      | 0.74%   |
| Maxtor              | 1         | 1      | 0.74%   |
| FC-1307             | 1         | 1      | 0.74%   |
| Unknown             | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 61     | 27.21%  |
| Kingston            | 14        | 17     | 9.52%   |
| Crucial             | 13        | 21     | 8.84%   |
| WDC                 | 11        | 13     | 7.48%   |
| SanDisk             | 10        | 12     | 6.8%    |
| China               | 5         | 7      | 3.4%    |
| A-DATA Technology   | 5         | 6      | 3.4%    |
| GOODRAM             | 4         | 25     | 2.72%   |
| Unknown             | 4         | 4      | 2.72%   |
| Patriot             | 3         | 5      | 2.04%   |
| OCZ                 | 3         | 3      | 2.04%   |
| Intel               | 3         | 3      | 2.04%   |
| Verbatim            | 2         | 2      | 1.36%   |
| Transcend           | 2         | 2      | 1.36%   |
| Toshiba             | 2         | 2      | 1.36%   |
| LITEON              | 2         | 3      | 1.36%   |
| KingSpec            | 2         | 3      | 1.36%   |
| Intenso             | 2         | 2      | 1.36%   |
| Hewlett-Packard     | 2         | 2      | 1.36%   |
| Team                | 1         | 1      | 0.68%   |
| StoreJet            | 1         | 1      | 0.68%   |
| Star                | 1         | 1      | 0.68%   |
| SPCC                | 1         | 3      | 0.68%   |
| SK hynix            | 1         | 1      | 0.68%   |
| SCCTS-603-256G      | 1         | 1      | 0.68%   |
| PNY                 | 1         | 1      | 0.68%   |
| LITEONIT            | 1         | 1      | 0.68%   |
| Lexar               | 1         | 1      | 0.68%   |
| Lenovo              | 1         | 1      | 0.68%   |
| Kingchuxing         | 1         | 5      | 0.68%   |
| GLOWAY              | 1         | 1      | 0.68%   |
| FREEBSD             | 1         | 12     | 0.68%   |
| EYOTA               | 1         | 1      | 0.68%   |
| Corsair             | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |
| Apacer              | 1         | 1      | 0.68%   |
| AGI                 | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 224       | 357    | 48.28%  |
| SSD     | 121       | 228    | 26.08%  |
| HDD     | 104       | 284    | 22.41%  |
| MMC     | 13        | 18     | 2.8%    |
| Unknown | 2         | 10     | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 224       | 356    | 54.9%   |
| SATA | 160       | 502    | 39.22%  |
| MMC  | 13        | 18     | 3.19%   |
| SAS  | 11        | 21     | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 104       | 179    | 40.31%  |
| 0.51-1.0   | 72        | 112    | 27.91%  |
| 1.01-2.0   | 34        | 67     | 13.18%  |
| 3.01-4.0   | 20        | 52     | 7.75%   |
| 2.01-3.0   | 11        | 37     | 4.26%   |
| 4.01-10.0  | 11        | 45     | 4.26%   |
| 10.01-20.0 | 6         | 20     | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 60        | 18.69%  |
| More than 3000 | 51        | 15.89%  |
| 251-500        | 49        | 15.26%  |
| 101-250        | 46        | 14.33%  |
| 1001-2000      | 43        | 13.4%   |
| 1-20           | 28        | 8.72%   |
| Unknown        | 17        | 5.3%    |
| 2001-3000      | 12        | 3.74%   |
| 51-100         | 8         | 2.49%   |
| 21-50          | 7         | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 76        | 23.24%  |
| 101-250        | 55        | 16.82%  |
| 21-50          | 39        | 11.93%  |
| 251-500        | 36        | 11.01%  |
| 501-1000       | 28        | 8.56%   |
| 1001-2000      | 26        | 7.95%   |
| 51-100         | 23        | 7.03%   |
| More than 3000 | 20        | 6.12%   |
| Unknown        | 17        | 5.2%    |
| 2001-3000      | 7         | 2.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Computers | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 2         | 2      | 5%      |
| WDC WD5000BEVT-22ZAT0 500GB                                    | 1         | 1      | 2.5%    |
| WDC WD3200BEVT-22ZCT0 320GB                                    | 1         | 1      | 2.5%    |
| WDC WD30EFRX-68EUZN0 3TB                                       | 1         | 4      | 2.5%    |
| WDC WD20EFRX-68EUZN0 2TB                                       | 1         | 1      | 2.5%    |
| WDC WD2002FAEX-007BA0 2TB                                      | 1         | 1      | 2.5%    |
| WDC WD10EZEX-00RKKA0 1TB                                       | 1         | 1      | 2.5%    |
| WDC WD10EFRX-68PJCN0 1TB                                       | 1         | 1      | 2.5%    |
| WDC WD10EADS-00M2B0 1TB                                        | 1         | 1      | 2.5%    |
| WDC WD Green 2.5 240GB                                         | 1         | 1      | 2.5%    |
| Toshiba HDWE150 5TB                                            | 1         | 4      | 2.5%    |
| Toshiba HDWD240 4TB                                            | 1         | 2      | 2.5%    |
| SK hynix PC711 HFS512GDE9X073N 512GB                           | 1         | 1      | 2.5%    |
| SK hynix BC501 NVMe Solid State Drive 512GB                    | 1         | 1      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB                                | 1         | 1      | 2.5%    |
| Seagate ST500DM002-1BC142 500GB                                | 1         | 1      | 2.5%    |
| Seagate ST3160811AS 160GB                                      | 1         | 1      | 2.5%    |
| Seagate ST31000524AS 1TB                                       | 1         | 1      | 2.5%    |
| Seagate ST3000DM008-2DM166 3TB                                 | 1         | 2      | 2.5%    |
| Seagate ST2000LM007-1R8174 2TB                                 | 1         | 1      | 2.5%    |
| Seagate ST2000DM005-2CW102 2TB                                 | 1         | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                             | 1         | 2      | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB                                 | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 980 1TB                                | 1         | 1      | 2.5%    |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1      | 2.5%    |
| Samsung Electronics MZ7WD960HMHP-00003 960GB SSD               | 1         | 1      | 2.5%    |
| PNY SSD2SC120G1LC763C121S459P 120GB                            | 1         | 1      | 2.5%    |
| OCZ AGILITY3 128GB SSD                                         | 1         | 1      | 2.5%    |
| Maxtor STM3160215A 160GB                                       | 1         | 1      | 2.5%    |
| LITEON CV8-8E128-HP 128GB SSD                                  | 1         | 2      | 2.5%    |
| Kingston SV300S37A240G 240GB SSD                               | 1         | 1      | 2.5%    |
| Kingston SV300S37A 120G SSD                                    | 1         | 1      | 2.5%    |
| Intel SSDSCKKF180G8L 180GB                                     | 1         | 1      | 2.5%    |
| Hitachi HUS724030ALE641 3TB                                    | 1         | 1      | 2.5%    |
| Hitachi HDS722020ALA330 2TB                                    | 1         | 1      | 2.5%    |
| HGST HTS725050A7E630 500GB                                     | 1         | 1      | 2.5%    |
| HGST HTS721010A9E630 1TB                                       | 1         | 1      | 2.5%    |
| A-DATA Technology SP900 128GB SSD                              | 1         | 1      | 2.5%    |
| Unknown                                                        | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 14     | 25.64%  |
| Seagate             | 9         | 11     | 23.08%  |
| Samsung Electronics | 3         | 3      | 7.69%   |
| Toshiba             | 2         | 6      | 5.13%   |
| SK hynix            | 2         | 2      | 5.13%   |
| Kingston            | 2         | 2      | 5.13%   |
| Hitachi             | 2         | 2      | 5.13%   |
| HGST                | 2         | 2      | 5.13%   |
| PNY                 | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| Maxtor              | 1         | 1      | 2.56%   |
| LITEON              | 1         | 2      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |
| Unknown             | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 13     | 34.62%  |
| Seagate | 9         | 11     | 34.62%  |
| Toshiba | 2         | 6      | 7.69%   |
| Hitachi | 2         | 2      | 7.69%   |
| HGST    | 2         | 2      | 7.69%   |
| Maxtor  | 1         | 1      | 3.85%   |
| Unknown | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 36     | 65.79%  |
| SSD  | 9         | 10     | 23.68%  |
| NVMe | 4         | 4      | 10.53%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS723232L9A360 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 288       | 760    | 80.45%  |
| Malfunc  | 36        | 50     | 10.06%  |
| Detected | 33        | 86     | 9.22%   |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 130       | 25.95%  |
| AMD                              | 89        | 17.76%  |
| Samsung Electronics              | 80        | 15.97%  |
| Sandisk                          | 31        | 6.19%   |
| SK hynix                         | 22        | 4.39%   |
| Phison Electronics               | 22        | 4.39%   |
| Kingston Technology Company      | 20        | 3.99%   |
| Micron Technology                | 16        | 3.19%   |
| KIOXIA                           | 14        | 2.79%   |
| Micron/Crucial Technology        | 13        | 2.59%   |
| ASMedia Technology               | 12        | 2.4%    |
| Realtek Semiconductor            | 5         | 1%      |
| ADATA Technology                 | 5         | 1%      |
| Yangtze Memory Technologies      | 4         | 0.8%    |
| MAXIO Technology (Hangzhou)      | 4         | 0.8%    |
| Marvell Technology Group         | 4         | 0.8%    |
| Silicon Motion                   | 3         | 0.6%    |
| Nvidia                           | 3         | 0.6%    |
| LSI Logic / Symbios Logic        | 3         | 0.6%    |
| Broadcom / LSI                   | 3         | 0.6%    |
| Union Memory (Shenzhen)          | 2         | 0.4%    |
| Toshiba America Info Systems     | 2         | 0.4%    |
| Solid State Storage Technology   | 2         | 0.4%    |
| Seagate Technology               | 2         | 0.4%    |
| Loongson Technology              | 2         | 0.4%    |
| JMicron Technology               | 2         | 0.4%    |
| INNOGRIT                         | 2         | 0.4%    |
| VIA Technologies                 | 1         | 0.2%    |
| Transcend                        | 1         | 0.2%    |
| Solidigm                         | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 43        | 7.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 34        | 5.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 4.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 20        | 3.52%   |
| AMD 500 Series Chipset SATA Controller                                         | 19        | 3.35%   |
| AMD 600 Series Chipset SATA Controller                                         | 14        | 2.46%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 10        | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 1.76%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 1.58%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 1.41%   |
| Phison E18 PCIe4 NVMe Controller                                               | 8         | 1.41%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 8         | 1.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 1.41%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 7         | 1.23%   |
| Phison E12 NVMe Controller                                                     | 7         | 1.23%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 7         | 1.23%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 7         | 1.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7         | 1.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.06%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6         | 1.06%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5         | 0.88%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 5         | 0.88%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 5         | 0.88%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 5         | 0.88%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 5         | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 0.88%   |
| Intel SSD 660P Series                                                          | 5         | 0.88%   |
| Intel SSD 600P Series                                                          | 5         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5         | 0.88%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 0.7%    |
| Sandisk WD Black SN850X NVMe SSD                                               | 4         | 0.7%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 0.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 224       | 47.16%  |
| SATA | 192       | 40.42%  |
| RAID | 33        | 6.95%   |
| IDE  | 18        | 3.79%   |
| SAS  | 8         | 1.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 166       | 53.55%  |
| AMD          | 135       | 43.55%  |
| ARM          | 6         | 1.94%   |
| Loongson     | 2         | 0.65%   |
| CyrixInstead | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor           | 9         | 2.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 2.25%   |
| ARM Processor                                 | 6         | 1.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.61%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 1.29%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 4         | 1.29%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 4         | 1.29%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.29%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 4         | 1.29%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 4         | 1.29%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.29%   |
| Intel N100                                    | 3         | 0.96%   |
| Intel 13th Gen Core i9-13900H                 | 3         | 0.96%   |
| Intel 13th Gen Core i7-1370P                  | 3         | 0.96%   |
| Intel 13th Gen Core i7-13700H                 | 3         | 0.96%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.96%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics     | 3         | 0.96%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 3         | 0.96%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.96%   |
| Loongson 3A6000                               | 2         | 0.64%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz           | 2         | 0.64%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 2         | 0.64%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz           | 2         | 0.64%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 0.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.64%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.64%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 68        | 21.94%  |
| AMD Ryzen 7            | 43        | 13.87%  |
| Intel Core i7          | 37        | 11.94%  |
| AMD Ryzen 5            | 34        | 10.97%  |
| AMD Ryzen 9            | 33        | 10.65%  |
| Intel Core i5          | 26        | 8.39%   |
| Intel Xeon             | 16        | 5.16%   |
| AMD Ryzen 7 PRO        | 10        | 3.23%   |
| Intel Core i3          | 7         | 2.26%   |
| Intel Celeron          | 5         | 1.61%   |
| Intel Core i9          | 4         | 1.29%   |
| AMD FX                 | 4         | 1.29%   |
| Intel Pentium          | 3         | 0.97%   |
| Intel Core 2 Duo       | 3         | 0.97%   |
| Intel Atom             | 3         | 0.97%   |
| Intel Pentium Silver   | 2         | 0.65%   |
| AMD Ryzen Threadripper | 2         | 0.65%   |
| AMD Phenom II X4       | 2         | 0.65%   |
| Intel Pentium M        | 1         | 0.32%   |
| Intel Core 2           | 1         | 0.32%   |
| AMD Ryzen 5 PRO        | 1         | 0.32%   |
| AMD Ryzen 3            | 1         | 0.32%   |
| AMD Phenom II X6       | 1         | 0.32%   |
| AMD EPYC               | 1         | 0.32%   |
| AMD Athlon 64 X2       | 1         | 0.32%   |
| AMD Athlon             | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 86        | 27.74%  |
| 8       | 67        | 21.61%  |
| 6       | 50        | 16.13%  |
| 12      | 27        | 8.71%   |
| 2       | 27        | 8.71%   |
| 16      | 18        | 5.81%   |
| 14      | 14        | 4.52%   |
| 10      | 8         | 2.58%   |
| 1       | 4         | 1.29%   |
| Unknown | 3         | 0.97%   |
| 32      | 2         | 0.65%   |
| 24      | 2         | 0.65%   |
| 20      | 2         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 302       | 97.42%  |
| 2       | 5         | 1.61%   |
| Unknown | 3         | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 262       | 84.52%  |
| 1       | 44        | 14.19%  |
| Unknown | 3         | 0.97%   |
| 4       | 1         | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 308       | 99.35%  |
| 32-bit         | 2         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 44.06%  |
| 0xb06a2    | 10        | 3.13%   |
| 0x0a50000d | 9         | 2.81%   |
| 0x0a50000c | 9         | 2.81%   |
| 0x0a20120a | 9         | 2.81%   |
| 0x0a601203 | 8         | 2.5%    |
| 0x0a404102 | 8         | 2.5%    |
| 0x0a601206 | 7         | 2.19%   |
| 0x0a704103 | 6         | 1.88%   |
| 0x08701021 | 6         | 1.88%   |
| 0x806ec    | 5         | 1.56%   |
| 0x0a201016 | 5         | 1.56%   |
| 0x806c1    | 4         | 1.25%   |
| 0x08600106 | 4         | 1.25%   |
| 0x906ea    | 3         | 0.94%   |
| 0x90672    | 3         | 0.94%   |
| 0x806ea    | 3         | 0.94%   |
| 0x706a8    | 3         | 0.94%   |
| 0x306e4    | 3         | 0.94%   |
| 0x306c3    | 3         | 0.94%   |
| 0x306a9    | 3         | 0.94%   |
| 0x206d7    | 3         | 0.94%   |
| 0x206a7    | 3         | 0.94%   |
| 0x08701030 | 3         | 0.94%   |
| 0x08108109 | 3         | 0.94%   |
| 0x0800820d | 3         | 0.94%   |
| 0xb06e0    | 2         | 0.63%   |
| 0xb0671    | 2         | 0.63%   |
| 0x906a3    | 2         | 0.63%   |
| 0x506e3    | 2         | 0.63%   |
| 0x306f2    | 2         | 0.63%   |
| 0x20652    | 2         | 0.63%   |
| 0x0a50000f | 2         | 0.63%   |
| 0x08608103 | 2         | 0.63%   |
| 0x08600104 | 2         | 0.63%   |
| 0x08108102 | 2         | 0.63%   |
| 0x010000db | 2         | 0.63%   |
| 0xa0671    | 1         | 0.31%   |
| 0xa0652    | 1         | 0.31%   |
| 0x906ed    | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 52        | 16.61%  |
| Zen 3            | 46        | 14.7%   |
| KabyLake         | 37        | 11.82%  |
| Alderlake Hybrid | 35        | 11.18%  |
| Zen 2            | 26        | 8.31%   |
| Zen+             | 14        | 4.47%   |
| TigerLake        | 11        | 3.51%   |
| Icelake          | 11        | 3.51%   |
| Haswell          | 11        | 3.51%   |
| IvyBridge        | 10        | 3.19%   |
| SandyBridge      | 9         | 2.88%   |
| Skylake          | 6         | 1.92%   |
| CometLake        | 6         | 1.92%   |
| Westmere         | 5         | 1.6%    |
| Goldmont plus    | 5         | 1.6%    |
| Broadwell        | 5         | 1.6%    |
| Piledriver       | 3         | 0.96%   |
| K10              | 3         | 0.96%   |
| Gracemont        | 3         | 0.96%   |
| Core             | 3         | 0.96%   |
| Zen              | 2         | 0.64%   |
| Silvermont       | 2         | 0.64%   |
| Bonnell          | 2         | 0.64%   |
| Tremont          | 1         | 0.32%   |
| Penryn           | 1         | 0.32%   |
| P6               | 1         | 0.32%   |
| Nehalem          | 1         | 0.32%   |
| K8 Hammer        | 1         | 0.32%   |
| Bulldozer        | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| AMD                              | 134       | 37.33%  |
| Intel                            | 109       | 30.36%  |
| Nvidia                           | 103       | 28.69%  |
| ASPEED Technology                | 8         | 2.23%   |
| Matrox Electronics Systems       | 2         | 0.56%   |
| Loongson Technology              | 2         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 15        | 3.99%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                               | 13        | 3.46%   |
| AMD Raphael                                                          | 13        | 3.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 13        | 3.46%   |
| Intel UHD Graphics 620                                               | 12        | 3.19%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]        | 12        | 3.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 11        | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 11        | 2.93%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]        | 9         | 2.39%   |
| AMD Rembrandt [Radeon 680M]                                          | 9         | 2.39%   |
| AMD Phoenix1                                                         | 9         | 2.39%   |
| ASPEED Technology ASPEED Graphics Family                             | 8         | 2.13%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                            | 7         | 1.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                       | 7         | 1.86%   |
| AMD Barcelo                                                          | 6         | 1.6%    |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                      | 5         | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                            | 5         | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 5         | 1.33%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                              | 4         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 4         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                  | 4         | 1.06%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                           | 4         | 1.06%   |
| AMD Lucienne                                                         | 4         | 1.06%   |
| Nvidia GT218 [GeForce 210]                                           | 3         | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                   | 3         | 0.8%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 3         | 0.8%    |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                   | 3         | 0.8%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                   | 3         | 0.8%    |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                      | 3         | 0.8%    |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                      | 3         | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 3         | 0.8%    |
| Intel Raptor Lake-P [UHD Graphics]                                   | 3         | 0.8%    |
| Intel HD Graphics 530                                                | 3         | 0.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 3         | 0.8%    |
| Intel Alder Lake-N [UHD Graphics]                                    | 3         | 0.8%    |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                       | 3         | 0.8%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                           | 3         | 0.8%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]           | 3         | 0.8%    |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                           | 2         | 0.53%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 2         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x AMD                   | 103       | 32.91%  |
| 1 x Intel                 | 72        | 23%     |
| 1 x Nvidia                | 53        | 16.93%  |
| Intel + Nvidia            | 32        | 10.22%  |
| AMD + Nvidia              | 16        | 5.11%   |
| 2 x AMD                   | 10        | 3.19%   |
| Other                     | 7         | 2.24%   |
| 1 x ASPEED                | 6         | 1.92%   |
| 2 x Intel                 | 3         | 0.96%   |
| Intel + AMD               | 3         | 0.96%   |
| 1 x Matrox                | 2         | 0.64%   |
| AMD + Loongson Technology | 2         | 0.64%   |
| 2 x Nvidia                | 1         | 0.32%   |
| 1 x SiS                   | 1         | 0.32%   |
| Nvidia + ASPEED           | 1         | 0.32%   |
| AMD + ASPEED              | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 211       | 67.2%   |
| Proprietary | 72        | 22.93%  |
| Unknown     | 31        | 9.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 152       | 47.8%   |
| 0.01-0.5   | 39        | 12.26%  |
| 1.01-2.0   | 31        | 9.75%   |
| 7.01-8.0   | 30        | 9.43%   |
| 8.01-16.0  | 25        | 7.86%   |
| 0.51-1.0   | 16        | 5.03%   |
| 3.01-4.0   | 14        | 4.4%    |
| 5.01-6.0   | 6         | 1.89%   |
| 16.01-24.0 | 4         | 1.26%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 38        | 11.01%  |
| Samsung Electronics  | 34        | 9.86%   |
| Chimei Innolux       | 28        | 8.12%   |
| BOE                  | 27        | 7.83%   |
| Goldstar             | 26        | 7.54%   |
| Dell                 | 23        | 6.67%   |
| BenQ                 | 17        | 4.93%   |
| LG Display           | 16        | 4.64%   |
| Philips              | 11        | 3.19%   |
| AOC                  | 11        | 3.19%   |
| Acer                 | 10        | 2.9%    |
| Lenovo               | 9         | 2.61%   |
| Sharp                | 8         | 2.32%   |
| ViewSonic            | 7         | 2.03%   |
| ASUSTek Computer     | 7         | 2.03%   |
| Iiyama               | 6         | 1.74%   |
| Hewlett-Packard      | 6         | 1.74%   |
| PANDA                | 5         | 1.45%   |
| Gigabyte Technology  | 4         | 1.16%   |
| CSO                  | 4         | 1.16%   |
| Ancor Communications | 4         | 1.16%   |
| Unknown              | 3         | 0.87%   |
| TMX                  | 3         | 0.87%   |
| UGD                  | 2         | 0.58%   |
| Toshiba              | 2         | 0.58%   |
| RTK                  | 2         | 0.58%   |
| NEC Computers        | 2         | 0.58%   |
| Mi                   | 2         | 0.58%   |
| HUAWEI               | 2         | 0.58%   |
| YZA                  | 1         | 0.29%   |
| VDO                  | 1         | 0.29%   |
| Valve                | 1         | 0.29%   |
| SuperFrame           | 1         | 0.29%   |
| Sceptre Tech         | 1         | 0.29%   |
| Nvidia               | 1         | 0.29%   |
| MSI                  | 1         | 0.29%   |
| Monoprice            | 1         | 0.29%   |
| Microstep            | 1         | 0.29%   |
| Medion Akoya         | 1         | 0.29%   |
| LG Electronics       | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 6         | 1.66%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 4         | 1.1%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1614 1920x1200 344x215mm 16.0-inch      | 3         | 0.83%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 3         | 0.83%   |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                     | 3         | 0.83%   |
| AU Optronics LCD Monitor AUO6DA8 2560x1600 301x188mm 14.0-inch        | 3         | 0.83%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.83%   |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch               | 2         | 0.55%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch     | 2         | 0.55%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 2         | 0.55%   |
| Samsung Electronics SMS27A650 SAM082E 1920x1080 598x336mm 27.0-inch   | 2         | 0.55%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch     | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 0.55%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                     | 2         | 0.55%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                      | 2         | 0.55%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch          | 2         | 0.55%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 2         | 0.55%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 2         | 0.55%   |
| Hewlett-Packard S230tm HWP3115 1920x1080 509x286mm 23.0-inch          | 2         | 0.55%   |
| Hewlett-Packard LA2206 HWP2946 1920x1080 476x268mm 21.5-inch          | 2         | 0.55%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.55%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 2         | 0.55%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 0.55%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                     | 2         | 0.55%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 0.55%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.55%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                      | 2         | 0.55%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.55%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 2         | 0.55%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2         | 0.55%   |
| AU Optronics LCD Monitor AUOF99A 1920x1200 301x188mm 14.0-inch        | 2         | 0.55%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch        | 2         | 0.55%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2         | 0.55%   |
| AOC 24V2W1G5 AOC2402 1920x1080 530x300mm 24.0-inch                    | 2         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 143       | 45.98%  |
| 3840x2160 (4K)     | 36        | 11.58%  |
| 2560x1440 (QHD)    | 33        | 10.61%  |
| 1920x1200 (WUXGA)  | 22        | 7.07%   |
| 1366x768 (WXGA)    | 14        | 4.5%    |
| 2560x1600          | 9         | 2.89%   |
| 1280x1024 (SXGA)   | 8         | 2.57%   |
| 2256x1504          | 7         | 2.25%   |
| 3440x1440          | 5         | 1.61%   |
| 2560x1080          | 5         | 1.61%   |
| 3840x2400          | 3         | 0.96%   |
| 2288x1287          | 3         | 0.96%   |
| 3840x1080          | 2         | 0.64%   |
| 3200x2000          | 2         | 0.64%   |
| 2880x1620          | 2         | 0.64%   |
| 1600x900 (HD+)     | 2         | 0.64%   |
| 1600x1200          | 2         | 0.64%   |
| 1280x800 (WXGA)    | 2         | 0.64%   |
| 7680x2160          | 1         | 0.32%   |
| 3456x2160          | 1         | 0.32%   |
| 3000x2000          | 1         | 0.32%   |
| 2880x1800          | 1         | 0.32%   |
| 2048x1152          | 1         | 0.32%   |
| 1920x540           | 1         | 0.32%   |
| 1920x1280          | 1         | 0.32%   |
| 1680x1050 (WSXGA+) | 1         | 0.32%   |
| 1440x900 (WXGA+)   | 1         | 0.32%   |
| 1400x1050          | 1         | 0.32%   |
| Unknown            | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 54        | 15.84%  |
| 27      | 51        | 14.96%  |
| 13      | 35        | 10.26%  |
| 14      | 34        | 9.97%   |
| 24      | 33        | 9.68%   |
| 23      | 26        | 7.62%   |
| 21      | 23        | 6.74%   |
| 16      | 14        | 4.11%   |
| 31      | 13        | 3.81%   |
| 17      | 12        | 3.52%   |
| 34      | 10        | 2.93%   |
| 19      | 5         | 1.47%   |
| Unknown | 5         | 1.47%   |
| 142     | 3         | 0.88%   |
| 20      | 3         | 0.88%   |
| 84      | 2         | 0.59%   |
| 48      | 2         | 0.59%   |
| 36      | 2         | 0.59%   |
| 28      | 2         | 0.59%   |
| 18      | 2         | 0.59%   |
| 74      | 1         | 0.29%   |
| 72      | 1         | 0.29%   |
| 57      | 1         | 0.29%   |
| 38      | 1         | 0.29%   |
| 32      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 25      | 1         | 0.29%   |
| 11      | 1         | 0.29%   |
| 10      | 1         | 0.29%   |
| 7       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 119       | 36.17%  |
| 501-600        | 97        | 29.48%  |
| 401-500        | 27        | 8.21%   |
| 201-300        | 23        | 6.99%   |
| 601-700        | 21        | 6.38%   |
| 701-800        | 14        | 4.26%   |
| 351-400        | 12        | 3.65%   |
| Unknown        | 5         | 1.52%   |
| 1501-2000      | 4         | 1.22%   |
| More than 2000 | 3         | 0.91%   |
| 1001-1500      | 2         | 0.61%   |
| 801-900        | 1         | 0.3%    |
| 101-200        | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 211       | 71.04%  |
| 16/10   | 46        | 15.49%  |
| 21/9    | 10        | 3.37%   |
| 3/2     | 9         | 3.03%   |
| 5/4     | 8         | 2.69%   |
| Unknown | 5         | 1.68%   |
| 1.00    | 3         | 1.01%   |
| 4/3     | 2         | 0.67%   |
| 32/9    | 2         | 0.67%   |
| 0.56    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 56        | 16.82%  |
| 201-250        | 55        | 16.52%  |
| 101-110        | 53        | 15.92%  |
| 301-350        | 52        | 15.62%  |
| 351-500        | 24        | 7.21%   |
| 251-300        | 18        | 5.41%   |
| 111-120        | 15        | 4.5%    |
| 71-80          | 13        | 3.9%    |
| 151-200        | 12        | 3.6%    |
| More than 1000 | 8         | 2.4%    |
| 141-150        | 7         | 2.1%    |
| 121-130        | 7         | 2.1%    |
| 501-1000       | 5         | 1.5%    |
| Unknown        | 5         | 1.5%    |
| 51-60          | 2         | 0.6%    |
| 1-40           | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 110       | 33.74%  |
| 51-100        | 93        | 28.53%  |
| 101-120       | 58        | 17.79%  |
| 161-240       | 45        | 13.8%   |
| More than 240 | 8         | 2.45%   |
| 1-50          | 7         | 2.15%   |
| Unknown       | 5         | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 214       | 67.3%   |
| 2     | 52        | 16.35%  |
| 0     | 35        | 11.01%  |
| 3     | 13        | 4.09%   |
| 4     | 4         | 1.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 186       | 40.26%  |
| Realtek Semiconductor                 | 171       | 37.01%  |
| MediaTek                              | 34        | 7.36%   |
| Qualcomm Atheros                      | 11        | 2.38%   |
| Broadcom                              | 9         | 1.95%   |
| Qualcomm                              | 6         | 1.3%    |
| ASIX Electronics                      | 6         | 1.3%    |
| Ralink Technology                     | 4         | 0.87%   |
| TP-Link                               | 3         | 0.65%   |
| Nvidia                                | 3         | 0.65%   |
| Marvell Technology Group              | 3         | 0.65%   |
| Xiaomi                                | 2         | 0.43%   |
| Samsung Electronics                   | 2         | 0.43%   |
| Loongson Technology                   | 2         | 0.43%   |
| Lenovo                                | 2         | 0.43%   |
| Broadcom Limited                      | 2         | 0.43%   |
| U-Blox                                | 1         | 0.22%   |
| Texas Instruments                     | 1         | 0.22%   |
| Qualcomm Atheros Communications       | 1         | 0.22%   |
| QinHeng Electronics                   | 1         | 0.22%   |
| Prusa                                 | 1         | 0.22%   |
| NetGear                               | 1         | 0.22%   |
| Microsoft                             | 1         | 0.22%   |
| Microchip Technology                  | 1         | 0.22%   |
| Mellanox Technologies                 | 1         | 0.22%   |
| Insyde Software                       | 1         | 0.22%   |
| Huawei Technologies                   | 1         | 0.22%   |
| Google                                | 1         | 0.22%   |
| Emulex                                | 1         | 0.22%   |
| D-Link System                         | 1         | 0.22%   |
| Cisco Aironet Wireless Communications | 1         | 0.22%   |
| American Megatrends                   | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 103       | 19.11%  |
| Realtek RTL8125 2.5GbE Controller                                      | 41        | 7.61%   |
| Intel Wi-Fi 6 AX200                                                    | 26        | 4.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 21        | 3.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 14        | 2.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 12        | 2.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 12        | 2.23%   |
| Intel I211 Gigabit Network Connection                                  | 12        | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.04%   |
| Intel Ethernet Controller I225-V                                       | 11        | 2.04%   |
| Intel Wireless 8265 / 8275                                             | 10        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.3%    |
| Intel Wi-Fi 6 AX201                                                    | 7         | 1.3%    |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 6         | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 6         | 1.11%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 1.11%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 5         | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 4         | 0.74%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.56%   |
| Intel Wireless 7265                                                    | 3         | 0.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 0.56%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 0.56%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.56%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.56%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 135       | 58.95%  |
| MediaTek                              | 33        | 14.41%  |
| Realtek Semiconductor                 | 32        | 13.97%  |
| Qualcomm Atheros                      | 7         | 3.06%   |
| Qualcomm                              | 6         | 2.62%   |
| Broadcom                              | 5         | 2.18%   |
| Ralink Technology                     | 4         | 1.75%   |
| TP-Link                               | 2         | 0.87%   |
| Qualcomm Atheros Communications       | 1         | 0.44%   |
| NetGear                               | 1         | 0.44%   |
| Microsoft                             | 1         | 0.44%   |
| Cisco Aironet Wireless Communications | 1         | 0.44%   |
| Broadcom Limited                      | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                | 26        | 11.3%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]          | 21        | 9.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 14        | 6.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 12        | 5.22%   |
| Intel Raptor Lake PCH CNVi WiFi                                    | 12        | 5.22%   |
| Intel Wireless 8265 / 8275                                         | 10        | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 8         | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 7         | 3.04%   |
| Intel Wi-Fi 6 AX201                                                | 7         | 3.04%   |
| Qualcomm QCNFA765 Wireless Network Adapter                         | 6         | 2.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 6         | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 6         | 2.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 5         | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 4         | 1.74%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                  | 4         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 1.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 3         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 3         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 3         | 1.3%    |
| Intel Wireless 7265                                                | 3         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                     | 3         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                     | 3         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 3         | 1.3%    |
| Ralink RT5572 Wireless Adapter                                     | 2         | 0.87%   |
| Intel Wireless 8260                                                | 2         | 0.87%   |
| Intel Wireless 3165                                                | 2         | 0.87%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 2         | 0.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                                   | 2         | 0.87%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                             | 1         | 0.43%   |
| TP-Link 802.11ac NIC                                               | 1         | 0.43%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller        | 1         | 0.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                         | 1         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 160       | 54.42%  |
| Intel                    | 95        | 32.31%  |
| ASIX Electronics         | 6         | 2.04%   |
| Qualcomm Atheros         | 4         | 1.36%   |
| Broadcom                 | 4         | 1.36%   |
| Nvidia                   | 3         | 1.02%   |
| Marvell Technology Group | 3         | 1.02%   |
| Xiaomi                   | 2         | 0.68%   |
| Samsung Electronics      | 2         | 0.68%   |
| Loongson Technology      | 2         | 0.68%   |
| Lenovo                   | 2         | 0.68%   |
| TP-Link                  | 1         | 0.34%   |
| Microchip Technology     | 1         | 0.34%   |
| Mellanox Technologies    | 1         | 0.34%   |
| MediaTek                 | 1         | 0.34%   |
| Insyde Software          | 1         | 0.34%   |
| Huawei Technologies      | 1         | 0.34%   |
| Google                   | 1         | 0.34%   |
| Emulex                   | 1         | 0.34%   |
| D-Link System            | 1         | 0.34%   |
| Broadcom Limited         | 1         | 0.34%   |
| American Megatrends      | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 103       | 33.88%  |
| Realtek RTL8125 2.5GbE Controller                                             | 41        | 13.49%  |
| Intel I211 Gigabit Network Connection                                         | 12        | 3.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 11        | 3.62%   |
| Intel Ethernet Controller I225-V                                              | 11        | 3.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.96%   |
| Intel I210 Gigabit Network Connection                                         | 6         | 1.97%   |
| Intel Ethernet Connection (7) I219-V                                          | 6         | 1.97%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 6         | 1.97%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 5         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                                         | 5         | 1.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 0.99%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 0.99%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 0.99%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.66%   |
| Nvidia MCP61 Ethernet                                                         | 2         | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2         | 0.66%   |
| Loongson Ethernet controller                                                  | 2         | 0.66%   |
| Intel Ethernet Controller I226-V                                              | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.66%   |
| Intel Ethernet Connection (16) I219-V                                         | 2         | 0.66%   |
| Intel Ethernet Connection (14) I219-V                                         | 2         | 0.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.33%   |
| TP-Link USB 10/100 LAN                                                        | 1         | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1         | 0.33%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.33%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.33%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                 | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 259       | 53.07%  |
| WiFi     | 224       | 45.9%   |
| Modem    | 5         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 51.79%  |
| Ethernet | 148       | 48.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 162       | 52.09%  |
| 1     | 119       | 38.26%  |
| 3     | 13        | 4.18%   |
| 0     | 9         | 2.89%   |
| 4     | 6         | 1.93%   |
| 7     | 1         | 0.32%   |
| 5     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 217       | 69.11%  |
| Yes  | 97        | 30.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 117       | 56.52%  |
| Realtek Semiconductor   | 20        | 9.66%   |
| IMC Networks            | 12        | 5.8%    |
| Foxconn / Hon Hai       | 12        | 5.8%    |
| MediaTek                | 11        | 5.31%   |
| Cambridge Silicon Radio | 11        | 5.31%   |
| Lite-On Technology      | 6         | 2.9%    |
| USI                     | 5         | 2.42%   |
| Broadcom                | 4         | 1.93%   |
| Dell                    | 2         | 0.97%   |
| TP-Link                 | 1         | 0.48%   |
| Realtek                 | 1         | 0.48%   |
| Hewlett-Packard         | 1         | 0.48%   |
| Foxconn International   | 1         | 0.48%   |
| Edimax Technology       | 1         | 0.48%   |
| Apple                   | 1         | 0.48%   |
| Actions                 | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 24        | 11.59%  |
| Intel AX200 Bluetooth                               | 22        | 10.63%  |
| Intel AX211 Bluetooth                               | 18        | 8.7%    |
| Intel AX210 Bluetooth                               | 18        | 8.7%    |
| Realtek Bluetooth Radio                             | 16        | 7.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.76%   |
| MediaTek Wireless_Device                            | 11        | 5.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 5.31%   |
| Intel Bluetooth Device                              | 10        | 4.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 3.86%   |
| Intel Bluetooth wireless interface                  | 7         | 3.38%   |
| USI Bluetooth Device                                | 5         | 2.42%   |
| IMC Networks Wireless_Device                        | 5         | 2.42%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.45%   |
| Lite-On Wireless_Device                             | 3         | 1.45%   |
| Lite-On Bluetooth Device                            | 3         | 1.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.97%   |
| IMC Networks Bluetooth Device                       | 2         | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.97%   |
| TP-Link UB500 Adapter                               | 1         | 0.48%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.48%   |
| Realtek Bluetooth Radio                             | 1         | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.48%   |
| IMC Networks BCM20702A0                             | 1         | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.48%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 0.48%   |
| Edimax Edimax Bluetooth Adapter                     | 1         | 0.48%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.48%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.48%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.48%   |
| Apple Bluetooth Host Controller                     | 1         | 0.48%   |
| Actions general adapter                             | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| AMD                                          | 152       | 30.83%  |
| Intel                                        | 151       | 30.63%  |
| Nvidia                                       | 84        | 17.04%  |
| C-Media Electronics                          | 12        | 2.43%   |
| SteelSeries ApS                              | 6         | 1.22%   |
| Logitech                                     | 6         | 1.22%   |
| Micro Star International                     | 5         | 1.01%   |
| Kingston Technology                          | 5         | 1.01%   |
| ASUSTek Computer                             | 5         | 1.01%   |
| Texas Instruments                            | 4         | 0.81%   |
| Razer USA                                    | 4         | 0.81%   |
| Plantronics                                  | 4         | 0.81%   |
| Realtek Semiconductor                        | 3         | 0.61%   |
| Lenovo                                       | 3         | 0.61%   |
| JMTek                                        | 3         | 0.61%   |
| Hewlett-Packard                              | 3         | 0.61%   |
| GN Netcom                                    | 3         | 0.61%   |
| Generalplus Technology                       | 3         | 0.61%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.41%   |
| Mark of the Unicorn                          | 2         | 0.41%   |
| Loongson Technology                          | 2         | 0.41%   |
| JBL                                          | 2         | 0.41%   |
| Creative Technology                          | 2         | 0.41%   |
| Creative Labs                                | 2         | 0.41%   |
| Audient                                      | 2         | 0.41%   |
| Unknown                                      | 2         | 0.41%   |
| Valve Software                               | 1         | 0.2%    |
| Thesycon Systemsoftware & Consulting         | 1         | 0.2%    |
| Sony                                         | 1         | 0.2%    |
| No brand                                     | 1         | 0.2%    |
| Microsoft                                    | 1         | 0.2%    |
| MAG Technology                               | 1         | 0.2%    |
| M-Audio                                      | 1         | 0.2%    |
| JOUNIVO                                      | 1         | 0.2%    |
| iCreate Technologies                         | 1         | 0.2%    |
| Huawei Technologies                          | 1         | 0.2%    |
| Focusrite-Novation                           | 1         | 0.2%    |
| FIFINE Microphones                           | 1         | 0.2%    |
| Elgato Systems                               | 1         | 0.2%    |
| DSEA A/S                                     | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 76        | 12.46%  |
| AMD Starship/Matisse HD Audio Controller                                   | 36        | 5.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 34        | 5.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 29        | 4.75%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 28        | 4.59%   |
| Nvidia Audio device                                                        | 18        | 2.95%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 17        | 2.79%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14        | 2.3%    |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 1.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.15%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 0.98%   |
| AMD Navi 10 HDMI Audio                                                     | 6         | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.82%   |
| Micro Star International USB Audio                                         | 5         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.66%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 0.66%   |
| Intel Raptor Lake High Definition Audio Controller                         | 4         | 0.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 0.66%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 0.66%   |
| ASUSTek Computer USB Audio                                                 | 4         | 0.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 0.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.66%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.49%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 60        | 18.58%  |
| Micron Technology            | 40        | 12.38%  |
| SK hynix                     | 37        | 11.46%  |
| Kingston                     | 32        | 9.91%   |
| Crucial                      | 30        | 9.29%   |
| Corsair                      | 29        | 8.98%   |
| G.Skill                      | 28        | 8.67%   |
| Unknown                      | 16        | 4.95%   |
| Unknown                      | 11        | 3.41%   |
| A-DATA Technology            | 9         | 2.79%   |
| Team                         | 5         | 1.55%   |
| Patriot                      | 4         | 1.24%   |
| Elpida                       | 4         | 1.24%   |
| Unknown (ABCD)               | 3         | 0.93%   |
| Ramaxel Technology           | 2         | 0.62%   |
| Unknown (0x0B92)             | 1         | 0.31%   |
| Transcend                    | 1         | 0.31%   |
| Patriot Memory (PDP Systems) | 1         | 0.31%   |
| Nanya Technology             | 1         | 0.31%   |
| Mushkin                      | 1         | 0.31%   |
| Lexar Co Limited             | 1         | 0.31%   |
| Kllisre                      | 1         | 0.31%   |
| Kimtigo                      | 1         | 0.31%   |
| Foxline                      | 1         | 0.31%   |
| CSX                          | 1         | 0.31%   |
| Avant                        | 1         | 0.31%   |
| Apacer                       | 1         | 0.31%   |
| AMD                          | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 11        | 3.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.14%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.85%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 3         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.85%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 3         | 0.85%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 3         | 0.85%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 3         | 0.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 0.85%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16384MB SODIMM DDR4 3200MT/s      | 3         | 0.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 2         | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 2         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.57%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.57%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.57%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.57%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.57%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.57%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.57%   |
| Kingston RAM KF556S40-32 32GB SODIMM DDR5 5600MT/s               | 2         | 0.57%   |
| Kingston RAM KF556C36-32 32GB DIMM DDR5 5600MT/s                 | 2         | 0.57%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.57%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s             | 2         | 0.57%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s             | 2         | 0.57%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s           | 2         | 0.57%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 0.57%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 2         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 172       | 60.35%  |
| DDR5    | 36        | 12.63%  |
| DDR3    | 35        | 12.28%  |
| LPDDR5  | 17        | 5.96%   |
| LPDDR4  | 10        | 3.51%   |
| DDR2    | 7         | 2.46%   |
| Unknown | 3         | 1.05%   |
| SDRAM   | 2         | 0.7%    |
| LPDDR3  | 1         | 0.35%   |
| DRAM    | 1         | 0.35%   |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 137       | 48.07%  |
| DIMM         | 127       | 44.56%  |
| Row Of Chips | 20        | 7.02%   |
| Unknown      | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 116       | 36.94%  |
| 16384 | 87        | 27.71%  |
| 32768 | 48        | 15.29%  |
| 4096  | 43        | 13.69%  |
| 2048  | 16        | 5.1%    |
| 1024  | 3         | 0.96%   |
| 49152 | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 85        | 26.81%  |
| 2667    | 30        | 9.46%   |
| 1600    | 22        | 6.94%   |
| 2400    | 19        | 5.99%   |
| 6400    | 17        | 5.36%   |
| 4800    | 17        | 5.36%   |
| 3600    | 17        | 5.36%   |
| 5600    | 13        | 4.1%    |
| 2133    | 12        | 3.79%   |
| 1866    | 7         | 2.21%   |
| 3733    | 6         | 1.89%   |
| 4267    | 5         | 1.58%   |
| 3266    | 5         | 1.58%   |
| 1333    | 5         | 1.58%   |
| 667     | 5         | 1.58%   |
| 3866    | 4         | 1.26%   |
| 1334    | 4         | 1.26%   |
| 6000    | 3         | 0.95%   |
| 8400    | 2         | 0.63%   |
| 4266    | 2         | 0.63%   |
| 4000    | 2         | 0.63%   |
| 3800    | 2         | 0.63%   |
| 3666    | 2         | 0.63%   |
| 3534    | 2         | 0.63%   |
| 3400    | 2         | 0.63%   |
| 3000    | 2         | 0.63%   |
| 2933    | 2         | 0.63%   |
| 2666    | 2         | 0.63%   |
| 2048    | 2         | 0.63%   |
| 800     | 2         | 0.63%   |
| Unknown | 2         | 0.63%   |
| 49926   | 1         | 0.32%   |
| 8600    | 1         | 0.32%   |
| 7500    | 1         | 0.32%   |
| 5500    | 1         | 0.32%   |
| 5200    | 1         | 0.32%   |
| 3500    | 1         | 0.32%   |
| 3466    | 1         | 0.32%   |
| 3333    | 1         | 0.32%   |
| 3066    | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Brother Industries  | 3         | 33.33%  |
| Prolific Technology | 1         | 11.11%  |
| NXP Semiconductors  | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP HP LaserJet M14-M17        | 2         | 22.22%  |
| Prolific PL2305 Parallel Port | 1         | 11.11%  |
| NXP Semiconductors Printer-80 | 1         | 11.11%  |
| HP Deskjet 9800               | 1         | 11.11%  |
| Canon PIXMA MG2900 Series     | 1         | 11.11%  |
| Brother QL-500 label printer  | 1         | 11.11%  |
| Brother MFC-9340CDW           | 1         | 11.11%  |
| Brother HL-L2370DW series     | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 20.36%  |
| IMC Networks                           | 23        | 13.77%  |
| Logitech                               | 17        | 10.18%  |
| Microdia                               | 14        | 8.38%   |
| Realtek Semiconductor                  | 11        | 6.59%   |
| Quanta                                 | 9         | 5.39%   |
| Bison Electronics                      | 9         | 5.39%   |
| Luxvisions Innotech Limited            | 8         | 4.79%   |
| Sunplus Innovation Technology          | 4         | 2.4%    |
| Sonix Technology                       | 4         | 2.4%    |
| Lite-On Technology                     | 4         | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.4%    |
| Syntek                                 | 2         | 1.2%    |
| Samsung Electronics                    | 2         | 1.2%    |
| MacroSilicon                           | 2         | 1.2%    |
| BTF-230906-J                           | 2         | 1.2%    |
| Zhejiang Dahua Technology              | 1         | 0.6%    |
| Valve Software                         | 1         | 0.6%    |
| Tripath Technology                     | 1         | 0.6%    |
| Silicon Motion                         | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Microsoft                              | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| kingcome                               | 1         | 0.6%    |
| icSpring                               | 1         | 0.6%    |
| Google                                 | 1         | 0.6%    |
| Goodong                                | 1         | 0.6%    |
| Generalplus Technology                 | 1         | 0.6%    |
| Elgato Systems                         | 1         | 0.6%    |
| Creative Technology                    | 1         | 0.6%    |
| Arkmicro Technologies                  | 1         | 0.6%    |
| ARC International                      | 1         | 0.6%    |
| Acer                                   | 1         | 0.6%    |
| A4Tech                                 | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 17        | 10%     |
| IMC Networks USB2.0 HD UVC WebCam                    | 8         | 4.71%   |
| IMC Networks Integrated Camera                       | 7         | 4.12%   |
| Logitech Webcam C270                                 | 6         | 3.53%   |
| Realtek Laptop Camera                                | 5         | 2.94%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.94%   |
| Lite-On HP HD Camera                                 | 4         | 2.35%   |
| Quanta HD User Facing                                | 3         | 1.76%   |
| Microdia USB 2.0 Camera                              | 3         | 1.76%   |
| Logitech C922 Pro Stream Webcam                      | 3         | 1.76%   |
| Chicony Integrated IR Camera                         | 3         | 1.76%   |
| Cheng Uei Precision Industry (Foxlink) HP 5MP Camera | 3         | 1.76%   |
| Bison Integrated Camera                              | 3         | 1.76%   |
| Syntek Integrated Camera                             | 2         | 1.18%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 1.18%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 1.18%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 1.18%   |
| Realtek Integrated_Webcam_FHD                        | 2         | 1.18%   |
| Quanta HP TrueVision HD Camera                       | 2         | 1.18%   |
| Microdia Webcam Vitade AF                            | 2         | 1.18%   |
| MacroSilicon USB3. 0 capture                         | 2         | 1.18%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 2         | 1.18%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.18%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 1.18%   |
| Logitech HD Webcam C525                              | 2         | 1.18%   |
| Logitech HD Pro Webcam C920                          | 2         | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 1.18%   |
| Chicony USB2.0 Camera                                | 2         | 1.18%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.18%   |
| Chicony HP Wide Vision HD Camera                     | 2         | 1.18%   |
| Chicony HP HD Camera                                 | 2         | 1.18%   |
| Chicony HP 720p HD Monitor Webcam                    | 2         | 1.18%   |
| Chicony HD WebCam                                    | 2         | 1.18%   |
| Chicony HD User Facing                               | 2         | 1.18%   |
| BTF-230906-J Hy-UXGA(B5M2)-Camera                    | 2         | 1.18%   |
| Bison HD Webcam                                      | 2         | 1.18%   |
| Zhejiang Dahua HTI-UC325                             | 1         | 0.59%   |
| Valve Software 3D Camera                             | 1         | 0.59%   |
| Tripath USB Camera                                   | 1         | 0.59%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 17        | 51.52%  |
| Validity Sensors                   | 6         | 18.18%  |
| Shenzhen Goodix Technology         | 6         | 18.18%  |
| Upek                               | 1         | 3.03%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 3.03%   |
| LighTuning Technology              | 1         | 3.03%   |
| Elan Microelectronics              | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 24.24%  |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 12.12%  |
| Validity Sensors Synaptics WBDI                                            | 3         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 6.06%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 6.06%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 6.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.03%   |
| Synaptics UWP WBDI Device                                                  | 1         | 3.03%   |
| Synaptics UWP WBDI                                                         | 1         | 3.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.03%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.03%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.03%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 33.33%  |
| Alcor Micro           | 6         | 33.33%  |
| Clay Logic            | 2         | 11.11%  |
| OmniKey               | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |
| Lenovo                | 1         | 5.56%   |
| Gemalto (was Gemplus) | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 6         | 33.33%  |
| Broadcom 58200                                 | 4         | 22.22%  |
| Clay Logic Nitrokey Pro                        | 2         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 11.11%  |
| OmniKey CardMan 3021 / 3121                    | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 5.56%   |
| Lenovo Integrated Smart Card Reader            | 1         | 5.56%   |
| Gemalto (was Gemplus) eToken 5110+ FIPS        | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 160       | 48.93%  |
| 1     | 83        | 25.38%  |
| 2     | 39        | 11.93%  |
| 3     | 26        | 7.95%   |
| 5     | 10        | 3.06%   |
| 4     | 7         | 2.14%   |
| 6     | 2         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 50        | 17.06%  |
| Communication controller | 48        | 16.38%  |
| Bluetooth                | 33        | 11.26%  |
| Fingerprint reader       | 32        | 10.92%  |
| Net/wireless             | 24        | 8.19%   |
| Multimedia controller    | 23        | 7.85%   |
| Camera                   | 22        | 7.51%   |
| Chipcard                 | 16        | 5.46%   |
| Sound                    | 8         | 2.73%   |
| Net/ethernet             | 7         | 2.39%   |
| Unassigned class         | 6         | 2.05%   |
| Network                  | 6         | 2.05%   |
| Card reader              | 6         | 2.05%   |
| Storage/ide              | 4         | 1.37%   |
| Firewire controller      | 4         | 1.37%   |
| Storage/ata              | 2         | 0.68%   |
| Storage/raid             | 1         | 0.34%   |
| Storage/nvme             | 1         | 0.34%   |


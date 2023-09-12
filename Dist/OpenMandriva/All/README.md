OpenMandriva - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva/Desktop/README.md) and [notebooks](/Dist/OpenMandriva/Notebook/README.md).

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

Total: 15984

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | AO722                       | Notebook    | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f3bdad3061](https://linux-hardware.org/?probe=f3bdad3061) | Sep 07, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [38ebaae5c3](https://linux-hardware.org/?probe=38ebaae5c3) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | Desktop     | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1bc029ed5e](https://linux-hardware.org/?probe=1bc029ed5e) | Sep 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| ASRock        | A68M-ITX                    | Desktop     | [f995094d6b](https://linux-hardware.org/?probe=f995094d6b) | Sep 07, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [5b276b13a8](https://linux-hardware.org/?probe=5b276b13a8) | Sep 07, 2023 |
| Google        | Blooguard                   | Notebook    | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5254176a5a](https://linux-hardware.org/?probe=5254176a5a) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [0be77d9ece](https://linux-hardware.org/?probe=0be77d9ece) | Sep 07, 2023 |
| Toshiba       | STI 006998G                 | Desktop     | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| Lenovo        | 32E4 SDK0T76538 WIN 3556... | Mini pc     | [ac035f8420](https://linux-hardware.org/?probe=ac035f8420) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [0bada236bc](https://linux-hardware.org/?probe=0bada236bc) | Sep 07, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [987d1bc40e](https://linux-hardware.org/?probe=987d1bc40e) | Sep 06, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [3f98176bb7](https://linux-hardware.org/?probe=3f98176bb7) | Sep 06, 2023 |
| Clevo         | M1100M                      | Notebook    | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [29d9f2566a](https://linux-hardware.org/?probe=29d9f2566a) | Sep 06, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [849ecb3c82](https://linux-hardware.org/?probe=849ecb3c82) | Sep 06, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [22af76a0b6](https://linux-hardware.org/?probe=22af76a0b6) | Sep 06, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| MSI           | Bravo 15 C7VF               | Notebook    | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a738df6114](https://linux-hardware.org/?probe=a738df6114) | Sep 06, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| MSI           | Boston                      | Desktop     | [f4749c6ef7](https://linux-hardware.org/?probe=f4749c6ef7) | Sep 06, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [3ce904c03e](https://linux-hardware.org/?probe=3ce904c03e) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [9e650e7107](https://linux-hardware.org/?probe=9e650e7107) | Sep 06, 2023 |
| Lenovo        | IdeaCentre K330B            | Desktop     | [a53977eb83](https://linux-hardware.org/?probe=a53977eb83) | Sep 06, 2023 |
| Lenovo        | H420                        | Desktop     | [f84aae6411](https://linux-hardware.org/?probe=f84aae6411) | Sep 06, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [3266fb476d](https://linux-hardware.org/?probe=3266fb476d) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [3f1c2a5cfa](https://linux-hardware.org/?probe=3f1c2a5cfa) | Sep 06, 2023 |
| Dell          | 0RN4PJ A01                  | Server      | [342dfcbde0](https://linux-hardware.org/?probe=342dfcbde0) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| MSI           | GS60 2PC Ghost              | Notebook    | [0b971b067a](https://linux-hardware.org/?probe=0b971b067a) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | Notebook    | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [5ba13c092c](https://linux-hardware.org/?probe=5ba13c092c) | Sep 06, 2023 |
| Dell          | 0CU409                      | Desktop     | [f5ae8200cf](https://linux-hardware.org/?probe=f5ae8200cf) | Sep 06, 2023 |
| Google        | Pirika                      | Notebook    | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [10bb2b77f8](https://linux-hardware.org/?probe=10bb2b77f8) | Sep 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [07f51e668b](https://linux-hardware.org/?probe=07f51e668b) | Sep 06, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [afba6fc1eb](https://linux-hardware.org/?probe=afba6fc1eb) | Sep 06, 2023 |
| Unknown       | HX90                        | Desktop     | [928ebd5aa7](https://linux-hardware.org/?probe=928ebd5aa7) | Sep 06, 2023 |
| HP            | Notebook                    | Notebook    | [ad9bafda30](https://linux-hardware.org/?probe=ad9bafda30) | Sep 06, 2023 |
| HP            | Pavilion dv4                | Notebook    | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| Purism        | Librem 15 v3                | Notebook    | [d3a66abc8b](https://linux-hardware.org/?probe=d3a66abc8b) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [4a055a6f9c](https://linux-hardware.org/?probe=4a055a6f9c) | Sep 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | Notebook    | [cb8de94658](https://linux-hardware.org/?probe=cb8de94658) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [5dca7c7315](https://linux-hardware.org/?probe=5dca7c7315) | Sep 05, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [1c93682de6](https://linux-hardware.org/?probe=1c93682de6) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Intel         | H61                         | Desktop     | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [344c861540](https://linux-hardware.org/?probe=344c861540) | Sep 05, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | Notebook    | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [97ac9f9de8](https://linux-hardware.org/?probe=97ac9f9de8) | Sep 05, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [97e43e20d7](https://linux-hardware.org/?probe=97e43e20d7) | Sep 05, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [a66c2d8e50](https://linux-hardware.org/?probe=a66c2d8e50) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| Toshiba       | Satellite C850-1DZ          | Notebook    | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [5738356b52](https://linux-hardware.org/?probe=5738356b52) | Sep 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [4823d1487d](https://linux-hardware.org/?probe=4823d1487d) | Sep 05, 2023 |
| ASRock        | E35LM1                      | Desktop     | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| HP            | mt40                        | Notebook    | [c3a4682e40](https://linux-hardware.org/?probe=c3a4682e40) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [4c136b6049](https://linux-hardware.org/?probe=4c136b6049) | Sep 04, 2023 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [f2ac0f8904](https://linux-hardware.org/?probe=f2ac0f8904) | Sep 04, 2023 |
| ASRock        | A55M-HVS                    | Desktop     | [eaa27d1ba6](https://linux-hardware.org/?probe=eaa27d1ba6) | Sep 04, 2023 |
| HP            | Notebook                    | Notebook    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [f7250cb3ae](https://linux-hardware.org/?probe=f7250cb3ae) | Sep 04, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [08e7b606c8](https://linux-hardware.org/?probe=08e7b606c8) | Sep 04, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [46627e6392](https://linux-hardware.org/?probe=46627e6392) | Sep 04, 2023 |
| ASUSTek       | P5P43TD/USB3                | Desktop     | [619032e1d0](https://linux-hardware.org/?probe=619032e1d0) | Sep 04, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [c4334a53b6](https://linux-hardware.org/?probe=c4334a53b6) | Sep 04, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [66dedbf64b](https://linux-hardware.org/?probe=66dedbf64b) | Sep 04, 2023 |
| Dell          | 0J8G6F A03                  | Desktop     | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [2380eeae30](https://linux-hardware.org/?probe=2380eeae30) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Lenovo        | ThinkPad SL510 28473QB      | Notebook    | [e1ff8baa87](https://linux-hardware.org/?probe=e1ff8baa87) | Sep 04, 2023 |
| HP            | 8055                        | Desktop     | [2ed2e99af3](https://linux-hardware.org/?probe=2ed2e99af3) | Sep 04, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b87e106b6b](https://linux-hardware.org/?probe=b87e106b6b) | Sep 04, 2023 |
| Acer          | Aspire 4741                 | Notebook    | [2f2b673625](https://linux-hardware.org/?probe=2f2b673625) | Sep 04, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [ce82ba5660](https://linux-hardware.org/?probe=ce82ba5660) | Sep 04, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| ASRock        | NF6-GLAN                    | Desktop     | [80d9233886](https://linux-hardware.org/?probe=80d9233886) | Sep 04, 2023 |
| Dell          | Vostro 5590                 | Notebook    | [24ee101fee](https://linux-hardware.org/?probe=24ee101fee) | Sep 04, 2023 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [bce72e53fa](https://linux-hardware.org/?probe=bce72e53fa) | Sep 04, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [b173b156f9](https://linux-hardware.org/?probe=b173b156f9) | Sep 04, 2023 |
| MSI           | H61M-P20                    | Desktop     | [cdf64232fc](https://linux-hardware.org/?probe=cdf64232fc) | Sep 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [dcb565d513](https://linux-hardware.org/?probe=dcb565d513) | Sep 04, 2023 |
| HUAWEI        | MateBook HZ-W09             | Tablet      | [1e12adec6b](https://linux-hardware.org/?probe=1e12adec6b) | Sep 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d8efe50ca5](https://linux-hardware.org/?probe=d8efe50ca5) | Sep 04, 2023 |
| HP            | 8526 MVB, A                 | Desktop     | [3133ab688e](https://linux-hardware.org/?probe=3133ab688e) | Sep 04, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [7c149b5f95](https://linux-hardware.org/?probe=7c149b5f95) | Sep 04, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | Desktop     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [b3e23f1718](https://linux-hardware.org/?probe=b3e23f1718) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| OEM           | Intel H81                   | Desktop     | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5f9e18ee26](https://linux-hardware.org/?probe=5f9e18ee26) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| Samsung       | 950QED                      | Convertible | [3d5bc9f8ca](https://linux-hardware.org/?probe=3d5bc9f8ca) | Sep 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [2ba34b459a](https://linux-hardware.org/?probe=2ba34b459a) | Sep 04, 2023 |
| MSI           | B360M MORTAR                | Desktop     | [d023a05e0b](https://linux-hardware.org/?probe=d023a05e0b) | Sep 04, 2023 |
| AZW           | MINI S 10                   | Desktop     | [54967a6b36](https://linux-hardware.org/?probe=54967a6b36) | Sep 04, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [760698ac8a](https://linux-hardware.org/?probe=760698ac8a) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [85cc15f8ea](https://linux-hardware.org/?probe=85cc15f8ea) | Sep 04, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Gigabyte      | GB-BKi3A-7100               | Notebook    | [40c832efb9](https://linux-hardware.org/?probe=40c832efb9) | Sep 04, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [09e7a8c91b](https://linux-hardware.org/?probe=09e7a8c91b) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [02160fded0](https://linux-hardware.org/?probe=02160fded0) | Sep 04, 2023 |
| ASUSTek       | X75A1                       | Notebook    | [d8be6d6952](https://linux-hardware.org/?probe=d8be6d6952) | Sep 04, 2023 |
| Compaq        | 430                         | Notebook    | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [caa794eff8](https://linux-hardware.org/?probe=caa794eff8) | Sep 04, 2023 |
| HP            | 8449 00100                  | All in one  | [fa5e880618](https://linux-hardware.org/?probe=fa5e880618) | Sep 04, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| HP            | 829E                        | Mini pc     | [205ab47a36](https://linux-hardware.org/?probe=205ab47a36) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [b02b2cb5f0](https://linux-hardware.org/?probe=b02b2cb5f0) | Sep 04, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [08a80ee482](https://linux-hardware.org/?probe=08a80ee482) | Sep 04, 2023 |
| ASUSTek       | N56JN                       | Notebook    | [eb9458de08](https://linux-hardware.org/?probe=eb9458de08) | Sep 04, 2023 |
| HP            | 1000                        | Notebook    | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | Notebook    | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | Notebook    | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [362e60bccc](https://linux-hardware.org/?probe=362e60bccc) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [922ff6eddb](https://linux-hardware.org/?probe=922ff6eddb) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [3a25585a10](https://linux-hardware.org/?probe=3a25585a10) | Sep 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1cc4b106a4](https://linux-hardware.org/?probe=1cc4b106a4) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [49d36f6acc](https://linux-hardware.org/?probe=49d36f6acc) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | Notebook    | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [82f3e710d9](https://linux-hardware.org/?probe=82f3e710d9) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| VIT           | P2400                       | Notebook    | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [518f9f381b](https://linux-hardware.org/?probe=518f9f381b) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | Desktop     | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [9bacefd984](https://linux-hardware.org/?probe=9bacefd984) | Sep 04, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | Notebook    | [183e5c528c](https://linux-hardware.org/?probe=183e5c528c) | Sep 03, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [a3356b9a91](https://linux-hardware.org/?probe=a3356b9a91) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [1b89968327](https://linux-hardware.org/?probe=1b89968327) | Sep 03, 2023 |
| Intel         | NUC8i7HNB J68197-603        | Mini pc     | [cfa756b2c1](https://linux-hardware.org/?probe=cfa756b2c1) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| ALLDOCUBE     | i1402A                      | Notebook    | [d5d2c60681](https://linux-hardware.org/?probe=d5d2c60681) | Sep 03, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [c13b1a693d](https://linux-hardware.org/?probe=c13b1a693d) | Sep 03, 2023 |
| Acer          | Nitro AN515-41              | Notebook    | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [f92734bf2b](https://linux-hardware.org/?probe=f92734bf2b) | Sep 03, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [3ba5173eb2](https://linux-hardware.org/?probe=3ba5173eb2) | Sep 03, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c5ffec4746](https://linux-hardware.org/?probe=c5ffec4746) | Sep 03, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [12894bacfb](https://linux-hardware.org/?probe=12894bacfb) | Sep 03, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [6ce264a945](https://linux-hardware.org/?probe=6ce264a945) | Sep 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [7b776b30bd](https://linux-hardware.org/?probe=7b776b30bd) | Sep 03, 2023 |
| Intel         | H61                         | Desktop     | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | Notebook    | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [36b5fac615](https://linux-hardware.org/?probe=36b5fac615) | Sep 03, 2023 |
| HP            | 1825                        | Desktop     | [ea5da3d446](https://linux-hardware.org/?probe=ea5da3d446) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [70172e3461](https://linux-hardware.org/?probe=70172e3461) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [5656c8fd0b](https://linux-hardware.org/?probe=5656c8fd0b) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | Notebook    | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Desktop     | [3ad034200f](https://linux-hardware.org/?probe=3ad034200f) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b44e37eec5](https://linux-hardware.org/?probe=b44e37eec5) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | Notebook    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| ASRock        | FM2A78M-HD+                 | Desktop     | [a2d8c14a71](https://linux-hardware.org/?probe=a2d8c14a71) | Sep 03, 2023 |
| HP            | ENVY m6                     | Notebook    | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [5ed468ca65](https://linux-hardware.org/?probe=5ed468ca65) | Sep 03, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f02e3011d3](https://linux-hardware.org/?probe=f02e3011d3) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [71305b0cca](https://linux-hardware.org/?probe=71305b0cca) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | Desktop     | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| NEC Comput... | MS-7451MA                   | Desktop     | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| HP            | 828A                        | Desktop     | [13126d5ce1](https://linux-hardware.org/?probe=13126d5ce1) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| HP            | 843B                        | Desktop     | [d0cef21578](https://linux-hardware.org/?probe=d0cef21578) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b49fa94760](https://linux-hardware.org/?probe=b49fa94760) | Sep 03, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [55bb236bde](https://linux-hardware.org/?probe=55bb236bde) | Sep 03, 2023 |
| Pegatron      | IPMSB-GS                    | Desktop     | [35b8f645a7](https://linux-hardware.org/?probe=35b8f645a7) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | Notebook    | [a785a4e9bb](https://linux-hardware.org/?probe=a785a4e9bb) | Sep 03, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [8e63bb873b](https://linux-hardware.org/?probe=8e63bb873b) | Sep 03, 2023 |
| Toshiba       | dynabook R73/J              | Notebook    | [c63c97e4a8](https://linux-hardware.org/?probe=c63c97e4a8) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f09a79291](https://linux-hardware.org/?probe=2f09a79291) | Sep 03, 2023 |
| Google        | Lick                        | Notebook    | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [9e80502e5d](https://linux-hardware.org/?probe=9e80502e5d) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [d68ec21cac](https://linux-hardware.org/?probe=d68ec21cac) | Sep 03, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4cb41c4eb3](https://linux-hardware.org/?probe=4cb41c4eb3) | Sep 03, 2023 |
| Acer          | Aspire E5-471G              | Notebook    | [b1332205f3](https://linux-hardware.org/?probe=b1332205f3) | Sep 03, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [96dbf56986](https://linux-hardware.org/?probe=96dbf56986) | Sep 03, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [0f08b5b0ad](https://linux-hardware.org/?probe=0f08b5b0ad) | Sep 03, 2023 |
| Intel         | H81                         | Desktop     | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | Notebook    | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Intel         | H81                         | Desktop     | [75aabbccf5](https://linux-hardware.org/?probe=75aabbccf5) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [78f4fd9711](https://linux-hardware.org/?probe=78f4fd9711) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| ASUSTek       | M2N                         | Desktop     | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [37bfab5442](https://linux-hardware.org/?probe=37bfab5442) | Sep 02, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [a76e69489c](https://linux-hardware.org/?probe=a76e69489c) | Sep 02, 2023 |
| Alienware     | m15 R3                      | Notebook    | [c2e00a5341](https://linux-hardware.org/?probe=c2e00a5341) | Sep 02, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | Notebook    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| Lenovo        | ThinkPad A485 20MVS16C00    | Notebook    | [4d39e78f8f](https://linux-hardware.org/?probe=4d39e78f8f) | Sep 02, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [656df7cddd](https://linux-hardware.org/?probe=656df7cddd) | Sep 02, 2023 |
| HP            | 3646h                       | Desktop     | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4fa68712c5](https://linux-hardware.org/?probe=4fa68712c5) | Sep 02, 2023 |
| Multilaser    | UM125                       | Mini pc     | [a43bdb65de](https://linux-hardware.org/?probe=a43bdb65de) | Sep 02, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| Lenovo        | ThinkPad T460s 20F9003CU... | Notebook    | [8c94711a27](https://linux-hardware.org/?probe=8c94711a27) | Sep 02, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6a4908587f](https://linux-hardware.org/?probe=6a4908587f) | Sep 02, 2023 |
| HP            | 1497                        | Desktop     | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| UMAX          | 13Wr                        | Notebook    | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [53cd38e0c5](https://linux-hardware.org/?probe=53cd38e0c5) | Sep 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [d25c5d75c1](https://linux-hardware.org/?probe=d25c5d75c1) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| ASRock        | B660M Pro RS                | Desktop     | [f24f7fb5bf](https://linux-hardware.org/?probe=f24f7fb5bf) | Sep 02, 2023 |
| Acer          | TravelMate 8372             | Notebook    | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| Microtech     | ebookPro                    | Notebook    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [8e05d94e36](https://linux-hardware.org/?probe=8e05d94e36) | Sep 02, 2023 |
| Lenovo        | ThinkPad T540p 20BFCTO      | Notebook    | [6c4bd340bc](https://linux-hardware.org/?probe=6c4bd340bc) | Sep 02, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [2df9675af1](https://linux-hardware.org/?probe=2df9675af1) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7907301c2f](https://linux-hardware.org/?probe=7907301c2f) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e7b6359ed9](https://linux-hardware.org/?probe=e7b6359ed9) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| MSI           | MS-1688                     | Notebook    | [30cd2d6e9a](https://linux-hardware.org/?probe=30cd2d6e9a) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| MSI           | GP70 2OD                    | Notebook    | [4bc109f9a0](https://linux-hardware.org/?probe=4bc109f9a0) | Sep 02, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Acer          | Aspire TC-875 V:1.0         | Desktop     | [a25ba0bd0c](https://linux-hardware.org/?probe=a25ba0bd0c) | Sep 02, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| HP            | 1000                        | Notebook    | [aedfad957a](https://linux-hardware.org/?probe=aedfad957a) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | Notebook    | [dd49edce58](https://linux-hardware.org/?probe=dd49edce58) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [a8bdd5bcca](https://linux-hardware.org/?probe=a8bdd5bcca) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | Notebook    | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Biostar       | N68S3B                      | Desktop     | [fc063709f7](https://linux-hardware.org/?probe=fc063709f7) | Sep 02, 2023 |
| Dell          | Latitude 2120               | Notebook    | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [f3655da9eb](https://linux-hardware.org/?probe=f3655da9eb) | Sep 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [7cf0b6a1c4](https://linux-hardware.org/?probe=7cf0b6a1c4) | Sep 01, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Dell          | 0XT4CY A01                  | Desktop     | [26665d2c19](https://linux-hardware.org/?probe=26665d2c19) | Sep 01, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [f7e029febe](https://linux-hardware.org/?probe=f7e029febe) | Sep 01, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [f11dacb362](https://linux-hardware.org/?probe=f11dacb362) | Sep 01, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [f8ac18ebd1](https://linux-hardware.org/?probe=f8ac18ebd1) | Sep 01, 2023 |
| Intel         | DP67DE AAG10217-300         | Desktop     | [4d0db0b964](https://linux-hardware.org/?probe=4d0db0b964) | Sep 01, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [455a21dde9](https://linux-hardware.org/?probe=455a21dde9) | Sep 01, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [c4727ff179](https://linux-hardware.org/?probe=c4727ff179) | Sep 01, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [35e287844f](https://linux-hardware.org/?probe=35e287844f) | Sep 01, 2023 |
| HP            | Pavilion g6                 | Notebook    | [0f0960322d](https://linux-hardware.org/?probe=0f0960322d) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [a5e1bdfce5](https://linux-hardware.org/?probe=a5e1bdfce5) | Sep 01, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [28fc3470c8](https://linux-hardware.org/?probe=28fc3470c8) | Sep 01, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [2528493f15](https://linux-hardware.org/?probe=2528493f15) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| Medion        | A17                         | Notebook    | [31b4226638](https://linux-hardware.org/?probe=31b4226638) | Sep 01, 2023 |
| Dell          | Vostro 3590                 | Notebook    | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| Lenovo        | ThinkPad L450 20DSS1DT00    | Notebook    | [89ca82b3af](https://linux-hardware.org/?probe=89ca82b3af) | Sep 01, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [0f9de0fdf4](https://linux-hardware.org/?probe=0f9de0fdf4) | Sep 01, 2023 |
| Sony          | SVS1512DCXB                 | Notebook    | [b712723d6c](https://linux-hardware.org/?probe=b712723d6c) | Sep 01, 2023 |
| Lenovo        | ThinkPad X250 20CL001DGE    | Notebook    | [f6bc603569](https://linux-hardware.org/?probe=f6bc603569) | Sep 01, 2023 |
| HP            | 3032h                       | Desktop     | [7dfc9fa7a0](https://linux-hardware.org/?probe=7dfc9fa7a0) | Sep 01, 2023 |
| HP            | 1632                        | Desktop     | [a36b07aeda](https://linux-hardware.org/?probe=a36b07aeda) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | Desktop     | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9e7e8b4fbd](https://linux-hardware.org/?probe=9e7e8b4fbd) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| Intel         | H110                        | Desktop     | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| HP            | Compaq 15                   | Notebook    | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [2a11f6be15](https://linux-hardware.org/?probe=2a11f6be15) | Sep 01, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [2107ba0ad7](https://linux-hardware.org/?probe=2107ba0ad7) | Sep 01, 2023 |
| AZW           | U59                         | Desktop     | [4cca42eeb3](https://linux-hardware.org/?probe=4cca42eeb3) | Sep 01, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [da70c2acd8](https://linux-hardware.org/?probe=da70c2acd8) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8cc90dd6b0](https://linux-hardware.org/?probe=8cc90dd6b0) | Sep 01, 2023 |
| ASUSTek       | H81M2                       | Desktop     | [55dd352412](https://linux-hardware.org/?probe=55dd352412) | Sep 01, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [2b2efe00dd](https://linux-hardware.org/?probe=2b2efe00dd) | Sep 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c37cbe9bd9](https://linux-hardware.org/?probe=c37cbe9bd9) | Sep 01, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [905ee212e5](https://linux-hardware.org/?probe=905ee212e5) | Sep 01, 2023 |
| Positivo      | Mobile                      | Notebook    | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Acer          | TravelMate 5760G            | Notebook    | [1a0a1749fc](https://linux-hardware.org/?probe=1a0a1749fc) | Sep 01, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4660dc9f99](https://linux-hardware.org/?probe=4660dc9f99) | Sep 01, 2023 |
| AOpen         | i65HMx-D R1.04AL            | Desktop     | [aef1de4c53](https://linux-hardware.org/?probe=aef1de4c53) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Medion        | B250H4-EM                   | Desktop     | [c2e1f2eb0b](https://linux-hardware.org/?probe=c2e1f2eb0b) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [cc7fea9c3a](https://linux-hardware.org/?probe=cc7fea9c3a) | Sep 01, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [4ab20a426a](https://linux-hardware.org/?probe=4ab20a426a) | Sep 01, 2023 |
| Lenovo        | IdeaPad Z370                | Notebook    | [5c21431c9d](https://linux-hardware.org/?probe=5c21431c9d) | Sep 01, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [6010a74736](https://linux-hardware.org/?probe=6010a74736) | Sep 01, 2023 |
| BGH           | C46G                        | Notebook    | [c56474510e](https://linux-hardware.org/?probe=c56474510e) | Sep 01, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [54433f96fd](https://linux-hardware.org/?probe=54433f96fd) | Sep 01, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [021bbea0d4](https://linux-hardware.org/?probe=021bbea0d4) | Sep 01, 2023 |
| ASUSTek       | N3050T                      | Desktop     | [fa4b0cbf08](https://linux-hardware.org/?probe=fa4b0cbf08) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [f40d8bbc73](https://linux-hardware.org/?probe=f40d8bbc73) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| Dell          | Inspiron 7786               | Convertible | [bde311c07c](https://linux-hardware.org/?probe=bde311c07c) | Sep 01, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [04f5152e0c](https://linux-hardware.org/?probe=04f5152e0c) | Sep 01, 2023 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [f90ed18892](https://linux-hardware.org/?probe=f90ed18892) | Sep 01, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [033a5ccf76](https://linux-hardware.org/?probe=033a5ccf76) | Sep 01, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [b0127b4bff](https://linux-hardware.org/?probe=b0127b4bff) | Sep 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [499b5c3b2f](https://linux-hardware.org/?probe=499b5c3b2f) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| MSI           | MS-7390                     | Desktop     | [7115ad031a](https://linux-hardware.org/?probe=7115ad031a) | Sep 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0dbf80863b](https://linux-hardware.org/?probe=0dbf80863b) | Sep 01, 2023 |
| Fujitsu       | D3410-B2 S26361-D3410-B2    | Desktop     | [924293e07f](https://linux-hardware.org/?probe=924293e07f) | Sep 01, 2023 |
| MSI           | X99A WORKSTATION            | Desktop     | [46d1af7083](https://linux-hardware.org/?probe=46d1af7083) | Sep 01, 2023 |
| HP            | 1632                        | Desktop     | [13de11f1ff](https://linux-hardware.org/?probe=13de11f1ff) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [406d9fd5fc](https://linux-hardware.org/?probe=406d9fd5fc) | Sep 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d728ff01da](https://linux-hardware.org/?probe=d728ff01da) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [082d8a2ebf](https://linux-hardware.org/?probe=082d8a2ebf) | Sep 01, 2023 |
| Dell          | Latitude 3320               | Notebook    | [7c40b4eb0d](https://linux-hardware.org/?probe=7c40b4eb0d) | Sep 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [16059fa2ec](https://linux-hardware.org/?probe=16059fa2ec) | Sep 01, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [b6a24176aa](https://linux-hardware.org/?probe=b6a24176aa) | Aug 31, 2023 |
| ASUSTek       | K43SJ                       | Notebook    | [ab5c104bef](https://linux-hardware.org/?probe=ab5c104bef) | Aug 31, 2023 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [a01568da7d](https://linux-hardware.org/?probe=a01568da7d) | Aug 31, 2023 |
| HP            | 18E5                        | Desktop     | [75c3b34f87](https://linux-hardware.org/?probe=75c3b34f87) | Aug 31, 2023 |
| ASUSTek       | S301LP                      | Notebook    | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| HP            | 3397                        | Desktop     | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Positivo      | ONE500                      | Desktop     | [1e84a5bf44](https://linux-hardware.org/?probe=1e84a5bf44) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | Desktop     | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [c5fc2337ec](https://linux-hardware.org/?probe=c5fc2337ec) | Aug 31, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [8ad8098315](https://linux-hardware.org/?probe=8ad8098315) | Aug 31, 2023 |
| Intel         | H61                         | Desktop     | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [b5cdfbd338](https://linux-hardware.org/?probe=b5cdfbd338) | Aug 31, 2023 |
| Intel         | B75                         | Desktop     | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | Desktop     | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| HP            | 339A                        | Desktop     | [1ac5cd4af8](https://linux-hardware.org/?probe=1ac5cd4af8) | Aug 31, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [a45654cfd8](https://linux-hardware.org/?probe=a45654cfd8) | Aug 31, 2023 |
| HP            | 8768 A                      | Desktop     | [99787646c5](https://linux-hardware.org/?probe=99787646c5) | Aug 31, 2023 |
| HP            | 2215                        | Desktop     | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5720a360fb](https://linux-hardware.org/?probe=5720a360fb) | Aug 31, 2023 |
| Intel         | HM570                       | Desktop     | [d7c97890f9](https://linux-hardware.org/?probe=d7c97890f9) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | Desktop     | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [8e27446a62](https://linux-hardware.org/?probe=8e27446a62) | Aug 31, 2023 |
| Intel         | H55                         | Desktop     | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Gigabyte      | MTGU5AB-00                  | Desktop     | [2501ea0755](https://linux-hardware.org/?probe=2501ea0755) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| ASUSTek       | PN40                        | Mini pc     | [980ae9bc2d](https://linux-hardware.org/?probe=980ae9bc2d) | Aug 31, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [305133ce29](https://linux-hardware.org/?probe=305133ce29) | Aug 31, 2023 |
| Acer          | Extensa 5230                | Notebook    | [e4877c4cd7](https://linux-hardware.org/?probe=e4877c4cd7) | Aug 31, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [ee8a1b4fb5](https://linux-hardware.org/?probe=ee8a1b4fb5) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [0dd23cfbaa](https://linux-hardware.org/?probe=0dd23cfbaa) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e3eb4b9ef5](https://linux-hardware.org/?probe=e3eb4b9ef5) | Aug 31, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [25339d5009](https://linux-hardware.org/?probe=25339d5009) | Aug 31, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [a5847ee104](https://linux-hardware.org/?probe=a5847ee104) | Aug 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [5b79d93d0a](https://linux-hardware.org/?probe=5b79d93d0a) | Aug 31, 2023 |
| Medion        | Akoya E6239                 | Notebook    | [ec5460d846](https://linux-hardware.org/?probe=ec5460d846) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [19cb61cbf6](https://linux-hardware.org/?probe=19cb61cbf6) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | Desktop     | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| Biostar       | G41D3                       | Desktop     | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [9d05ea660f](https://linux-hardware.org/?probe=9d05ea660f) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [06860111ba](https://linux-hardware.org/?probe=06860111ba) | Aug 31, 2023 |
| MSI           | MS-B1421                    | Desktop     | [65d24e365e](https://linux-hardware.org/?probe=65d24e365e) | Aug 31, 2023 |
| MSI           | A88X-G41 PC Mate            | Desktop     | [13724b9cc2](https://linux-hardware.org/?probe=13724b9cc2) | Aug 31, 2023 |
| MSI           | A320M PRO-E                 | Desktop     | [92c4032614](https://linux-hardware.org/?probe=92c4032614) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| HP            | 82DD 0001                   | All in one  | [4d67f21aa7](https://linux-hardware.org/?probe=4d67f21aa7) | Aug 31, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [12785fd41a](https://linux-hardware.org/?probe=12785fd41a) | Aug 31, 2023 |
| HP            | 1587h                       | Desktop     | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6cd62bfac4](https://linux-hardware.org/?probe=6cd62bfac4) | Aug 31, 2023 |
| HP            | 806A                        | Desktop     | [638dfe4edc](https://linux-hardware.org/?probe=638dfe4edc) | Aug 31, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [649fb869a6](https://linux-hardware.org/?probe=649fb869a6) | Aug 31, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [d672293a11](https://linux-hardware.org/?probe=d672293a11) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [56e3937602](https://linux-hardware.org/?probe=56e3937602) | Aug 31, 2023 |
| ViewSonic     | VPC14-WP                    | Desktop     | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [81ae698cf8](https://linux-hardware.org/?probe=81ae698cf8) | Aug 31, 2023 |
| HP            | 8768 A                      | Desktop     | [3b19eaee36](https://linux-hardware.org/?probe=3b19eaee36) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [e180d8d91b](https://linux-hardware.org/?probe=e180d8d91b) | Aug 31, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [faf094d2ca](https://linux-hardware.org/?probe=faf094d2ca) | Aug 31, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [c222da255e](https://linux-hardware.org/?probe=c222da255e) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| MSI           | 880G-E45                    | Desktop     | [f10edf60fd](https://linux-hardware.org/?probe=f10edf60fd) | Aug 31, 2023 |
| MSI           | 2A78h                       | Desktop     | [78b5a663f2](https://linux-hardware.org/?probe=78b5a663f2) | Aug 31, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| Lenovo        | ThinkPad T480s 20L70025U... | Notebook    | [917664de79](https://linux-hardware.org/?probe=917664de79) | Aug 31, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [fab320d1d5](https://linux-hardware.org/?probe=fab320d1d5) | Aug 31, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [9173d00240](https://linux-hardware.org/?probe=9173d00240) | Aug 31, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [1a3fdd076f](https://linux-hardware.org/?probe=1a3fdd076f) | Aug 31, 2023 |
| MSI           | Boston                      | Desktop     | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| HP            | Laptop 14-bs1xx             | Notebook    | [335b828114](https://linux-hardware.org/?probe=335b828114) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| ECS           | A780GM-A                    | Desktop     | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [62b0ee9c60](https://linux-hardware.org/?probe=62b0ee9c60) | Aug 31, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | Notebook    | [6af4b49ea2](https://linux-hardware.org/?probe=6af4b49ea2) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | Desktop     | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [bdae370995](https://linux-hardware.org/?probe=bdae370995) | Aug 30, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [d9760de265](https://linux-hardware.org/?probe=d9760de265) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [7de2ff1052](https://linux-hardware.org/?probe=7de2ff1052) | Aug 30, 2023 |
| HP            | 3647h                       | Desktop     | [50ac4e01a4](https://linux-hardware.org/?probe=50ac4e01a4) | Aug 30, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| Medion        | P7818                       | Notebook    | [b2e6745157](https://linux-hardware.org/?probe=b2e6745157) | Aug 30, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [ca56f1b803](https://linux-hardware.org/?probe=ca56f1b803) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| Lenovo        | G40-70 20369                | Notebook    | [f3cef329f6](https://linux-hardware.org/?probe=f3cef329f6) | Aug 30, 2023 |
| Dell          | OptiPlex 7050               | Desktop     | [a35a9d7d8a](https://linux-hardware.org/?probe=a35a9d7d8a) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470 20HES0ET0R    | Notebook    | [65d003a7a0](https://linux-hardware.org/?probe=65d003a7a0) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [42f87cb09b](https://linux-hardware.org/?probe=42f87cb09b) | Aug 30, 2023 |
| Dell          | Latitude 3510               | Notebook    | [220b298103](https://linux-hardware.org/?probe=220b298103) | Aug 30, 2023 |
| HP            | ProBook 6360b               | Notebook    | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| Lenovo        | 81CA                        | Convertible | [a289ed0457](https://linux-hardware.org/?probe=a289ed0457) | Aug 30, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [5eee145629](https://linux-hardware.org/?probe=5eee145629) | Aug 30, 2023 |
| HUAWEI        | KLVF-XX                     | Notebook    | [747a685cc1](https://linux-hardware.org/?probe=747a685cc1) | Aug 30, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| Acer          | Aspire E1-530               | Notebook    | [39c2df1a0b](https://linux-hardware.org/?probe=39c2df1a0b) | Aug 30, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| ASUSTek       | P8H61 EVO                   | Desktop     | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [8ba058add5](https://linux-hardware.org/?probe=8ba058add5) | Aug 30, 2023 |
| HP            | 3047h                       | Desktop     | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [76eb125a56](https://linux-hardware.org/?probe=76eb125a56) | Aug 30, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [cd7bf0b2db](https://linux-hardware.org/?probe=cd7bf0b2db) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [2e1b103708](https://linux-hardware.org/?probe=2e1b103708) | Aug 30, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [6b6a2e7632](https://linux-hardware.org/?probe=6b6a2e7632) | Aug 30, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [57c65a2bc8](https://linux-hardware.org/?probe=57c65a2bc8) | Aug 30, 2023 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [5e3be336db](https://linux-hardware.org/?probe=5e3be336db) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a452d9eadf](https://linux-hardware.org/?probe=a452d9eadf) | Aug 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a65c8bb631](https://linux-hardware.org/?probe=a65c8bb631) | Aug 30, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3a0999b4a7](https://linux-hardware.org/?probe=3a0999b4a7) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ef1b605965](https://linux-hardware.org/?probe=ef1b605965) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [ac9c55fcb3](https://linux-hardware.org/?probe=ac9c55fcb3) | Aug 30, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [f69425a68d](https://linux-hardware.org/?probe=f69425a68d) | Aug 30, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [fac263bf1a](https://linux-hardware.org/?probe=fac263bf1a) | Aug 30, 2023 |
| ASUSTek       | P6T                         | Desktop     | [69879aca23](https://linux-hardware.org/?probe=69879aca23) | Aug 30, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [071785ab97](https://linux-hardware.org/?probe=071785ab97) | Aug 30, 2023 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [fa550a5ea1](https://linux-hardware.org/?probe=fa550a5ea1) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [362ee070d7](https://linux-hardware.org/?probe=362ee070d7) | Aug 30, 2023 |
| ASUSTek       | EB1035                      | All in one  | [ea73e26c86](https://linux-hardware.org/?probe=ea73e26c86) | Aug 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [efee17a022](https://linux-hardware.org/?probe=efee17a022) | Aug 30, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [4f6b648f42](https://linux-hardware.org/?probe=4f6b648f42) | Aug 30, 2023 |
| ASRock        | M3A UCC                     | Desktop     | [b46f15b2d2](https://linux-hardware.org/?probe=b46f15b2d2) | Aug 30, 2023 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [8bd315f814](https://linux-hardware.org/?probe=8bd315f814) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| ASUSTek       | A88XM-E/USB                 | Desktop     | [376615315b](https://linux-hardware.org/?probe=376615315b) | Aug 30, 2023 |
| Dell          | Precision 7730              | Notebook    | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Dell          | Latitude E6440              | Notebook    | [0b63ef8851](https://linux-hardware.org/?probe=0b63ef8851) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | Notebook    | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [28c0349031](https://linux-hardware.org/?probe=28c0349031) | Aug 30, 2023 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [311596a316](https://linux-hardware.org/?probe=311596a316) | Aug 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f040a85f2f](https://linux-hardware.org/?probe=f040a85f2f) | Aug 30, 2023 |
| ASUSTek       | P8H67-V                     | Desktop     | [24b196c99a](https://linux-hardware.org/?probe=24b196c99a) | Aug 30, 2023 |
| Alurin        | Go Notebook                 | Notebook    | [d07fd99df0](https://linux-hardware.org/?probe=d07fd99df0) | Aug 30, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [c95eb85e58](https://linux-hardware.org/?probe=c95eb85e58) | Aug 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9ed00c6987](https://linux-hardware.org/?probe=9ed00c6987) | Aug 30, 2023 |
| Foxconn       | H55MXV Series               | Desktop     | [af9d0ad662](https://linux-hardware.org/?probe=af9d0ad662) | Aug 30, 2023 |
| HP            | 876C SMVB                   | Desktop     | [25176eb482](https://linux-hardware.org/?probe=25176eb482) | Aug 30, 2023 |
| MSI           | Katana GF76 11UC            | Notebook    | [dd25d90357](https://linux-hardware.org/?probe=dd25d90357) | Aug 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [c1a4e5d47f](https://linux-hardware.org/?probe=c1a4e5d47f) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ded378b5da](https://linux-hardware.org/?probe=ded378b5da) | Aug 30, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 876C SMVB                   | Desktop     | [246cb7a1ca](https://linux-hardware.org/?probe=246cb7a1ca) | Aug 30, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [6f5bafed6c](https://linux-hardware.org/?probe=6f5bafed6c) | Aug 30, 2023 |
| ASRock        | H170M-ITX/ac                | Desktop     | [7921e28c6b](https://linux-hardware.org/?probe=7921e28c6b) | Aug 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [dda651a1c4](https://linux-hardware.org/?probe=dda651a1c4) | Aug 30, 2023 |
| OEM           | Intel H81                   | Desktop     | [7d179cb8e9](https://linux-hardware.org/?probe=7d179cb8e9) | Aug 30, 2023 |
| Acer          | TMP645-M                    | Notebook    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| Dell          | 0DR845                      | Desktop     | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [f59364572a](https://linux-hardware.org/?probe=f59364572a) | Aug 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [958ecd81e5](https://linux-hardware.org/?probe=958ecd81e5) | Aug 30, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c7fe7f6c55](https://linux-hardware.org/?probe=c7fe7f6c55) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [ea2ba90391](https://linux-hardware.org/?probe=ea2ba90391) | Aug 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [b3caa97382](https://linux-hardware.org/?probe=b3caa97382) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [20bd10b5f4](https://linux-hardware.org/?probe=20bd10b5f4) | Aug 30, 2023 |
| Foxconn       | D180S/D190S/D290S Series... | Desktop     | [5f6030cb69](https://linux-hardware.org/?probe=5f6030cb69) | Aug 30, 2023 |
| Dell          | Latitude 3350               | Notebook    | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | Desktop     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| Dell          | Latitude 5290               | Notebook    | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [04424409ef](https://linux-hardware.org/?probe=04424409ef) | Aug 29, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [1782829fec](https://linux-hardware.org/?probe=1782829fec) | Aug 29, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| HP            | 1589                        | Desktop     | [047e0158e8](https://linux-hardware.org/?probe=047e0158e8) | Aug 29, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7094317c17](https://linux-hardware.org/?probe=7094317c17) | Aug 29, 2023 |
| Lenovo        | 3000 G410                   | Notebook    | [26c592ddd6](https://linux-hardware.org/?probe=26c592ddd6) | Aug 29, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [390b033780](https://linux-hardware.org/?probe=390b033780) | Aug 29, 2023 |
| MSI           | PH61-SP35                   | Desktop     | [590f47f3fd](https://linux-hardware.org/?probe=590f47f3fd) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [7547ab7e8e](https://linux-hardware.org/?probe=7547ab7e8e) | Aug 29, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [fe431ea565](https://linux-hardware.org/?probe=fe431ea565) | Aug 29, 2023 |
| Intel         | DG45ID AAE27729-312         | Desktop     | [add370815d](https://linux-hardware.org/?probe=add370815d) | Aug 29, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [36cc5803b3](https://linux-hardware.org/?probe=36cc5803b3) | Aug 29, 2023 |
| Kobian        | PI945GCM ECS                | Desktop     | [85683b5fa3](https://linux-hardware.org/?probe=85683b5fa3) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [c1e12f9da7](https://linux-hardware.org/?probe=c1e12f9da7) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| HP            | 885F A                      | Desktop     | [d665bb8939](https://linux-hardware.org/?probe=d665bb8939) | Aug 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [9ed16c423b](https://linux-hardware.org/?probe=9ed16c423b) | Aug 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430 2349H86       | Notebook    | [6ed258911c](https://linux-hardware.org/?probe=6ed258911c) | Aug 29, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [b4acaedb21](https://linux-hardware.org/?probe=b4acaedb21) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [5222737445](https://linux-hardware.org/?probe=5222737445) | Aug 29, 2023 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [7d9c3aa2ad](https://linux-hardware.org/?probe=7d9c3aa2ad) | Aug 29, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b5ee83c5af](https://linux-hardware.org/?probe=b5ee83c5af) | Aug 29, 2023 |
| System76      | Galago Pro                  | Notebook    | [31330746e6](https://linux-hardware.org/?probe=31330746e6) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M91p 4518B84    | Desktop     | [e2fd5511ee](https://linux-hardware.org/?probe=e2fd5511ee) | Aug 29, 2023 |
| HP            | 89B4 A                      | Desktop     | [e70b3a2352](https://linux-hardware.org/?probe=e70b3a2352) | Aug 29, 2023 |
| ASUSTek       | M3N78-EH                    | Desktop     | [c0fb869905](https://linux-hardware.org/?probe=c0fb869905) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [338a8026f3](https://linux-hardware.org/?probe=338a8026f3) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Panasonic     | CF-54-2                     | Notebook    | [7d2f4f34c9](https://linux-hardware.org/?probe=7d2f4f34c9) | Aug 28, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [50b9b4c466](https://linux-hardware.org/?probe=50b9b4c466) | Aug 28, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [7ac77b7bac](https://linux-hardware.org/?probe=7ac77b7bac) | Aug 28, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [23712e9380](https://linux-hardware.org/?probe=23712e9380) | Aug 28, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [2e7cb45969](https://linux-hardware.org/?probe=2e7cb45969) | Aug 28, 2023 |
| Intel         | H81                         | Desktop     | [9b70a28b25](https://linux-hardware.org/?probe=9b70a28b25) | Aug 28, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [6d4609efa2](https://linux-hardware.org/?probe=6d4609efa2) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [54930549e6](https://linux-hardware.org/?probe=54930549e6) | Aug 28, 2023 |
| HP            | ProBook 430 G4 NOTEBOOK ... | Notebook    | [6ee102c046](https://linux-hardware.org/?probe=6ee102c046) | Aug 28, 2023 |
| HP            | 21D0                        | Desktop     | [8978dfd3bf](https://linux-hardware.org/?probe=8978dfd3bf) | Aug 28, 2023 |
| ASUSTek       | K53E                        | Notebook    | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [409ccc747c](https://linux-hardware.org/?probe=409ccc747c) | Aug 28, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [4cb158cafc](https://linux-hardware.org/?probe=4cb158cafc) | Aug 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [844b4e4dc2](https://linux-hardware.org/?probe=844b4e4dc2) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | Notebook    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| Lenovo        | ThinkPad X201 36809D4       | Notebook    | [1e4311af0b](https://linux-hardware.org/?probe=1e4311af0b) | Aug 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [22d4876142](https://linux-hardware.org/?probe=22d4876142) | Aug 28, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| Lenovo        | ThinkPad L512 259766G       | Notebook    | [4b92af4aba](https://linux-hardware.org/?probe=4b92af4aba) | Aug 28, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [1afaed6ffa](https://linux-hardware.org/?probe=1afaed6ffa) | Aug 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [12f61ffe4a](https://linux-hardware.org/?probe=12f61ffe4a) | Aug 28, 2023 |
| Dell          | Latitude 5580               | Notebook    | [eb2a994e98](https://linux-hardware.org/?probe=eb2a994e98) | Aug 28, 2023 |
| HP            | ProBook 6550b               | Notebook    | [2906ded48c](https://linux-hardware.org/?probe=2906ded48c) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | Notebook    | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | Notebook    | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [5cd969711d](https://linux-hardware.org/?probe=5cd969711d) | Aug 28, 2023 |
| Dell          | 0C0YYY A00                  | Desktop     | [1ac938e884](https://linux-hardware.org/?probe=1ac938e884) | Aug 28, 2023 |
| Sony          | VPCEB43FG                   | Notebook    | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | Notebook    | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [590de6cfc8](https://linux-hardware.org/?probe=590de6cfc8) | Aug 28, 2023 |
| HP            | 829A                        | Mini pc     | [603dced1cd](https://linux-hardware.org/?probe=603dced1cd) | Aug 27, 2023 |
| Positivo      | POS-PQ45AU                  | Desktop     | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| Dell          | Latitude 7480               | Notebook    | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b4411a9169](https://linux-hardware.org/?probe=b4411a9169) | Aug 27, 2023 |
| Fujitsu       | FMVU14003                   | Notebook    | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [a477892896](https://linux-hardware.org/?probe=a477892896) | Aug 27, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2c0f5739a3](https://linux-hardware.org/?probe=2c0f5739a3) | Aug 27, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| MSI           | B85M-G43                    | Desktop     | [96fd52d530](https://linux-hardware.org/?probe=96fd52d530) | Aug 27, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [d3a4f92f62](https://linux-hardware.org/?probe=d3a4f92f62) | Aug 27, 2023 |
| System76      | Gazelle                     | Notebook    | [83bc87f8fc](https://linux-hardware.org/?probe=83bc87f8fc) | Aug 27, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [a139f22d59](https://linux-hardware.org/?probe=a139f22d59) | Aug 27, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [20dc6d4044](https://linux-hardware.org/?probe=20dc6d4044) | Aug 27, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [6e40336ff6](https://linux-hardware.org/?probe=6e40336ff6) | Aug 27, 2023 |
| Dell          | Latitude E6410              | Notebook    | [451d5477e5](https://linux-hardware.org/?probe=451d5477e5) | Aug 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [79c52635ec](https://linux-hardware.org/?probe=79c52635ec) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bc180f5143](https://linux-hardware.org/?probe=bc180f5143) | Aug 27, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [0baf10cd76](https://linux-hardware.org/?probe=0baf10cd76) | Aug 27, 2023 |
| HP            | EliteBook 835 G7 Noteboo... | Notebook    | [fec29a37b2](https://linux-hardware.org/?probe=fec29a37b2) | Aug 27, 2023 |
| Lenovo        | 31900058 STD                | All in one  | [5c0b22c537](https://linux-hardware.org/?probe=5c0b22c537) | Aug 27, 2023 |
| Dell          | XPS M1330                   | Notebook    | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6c54b2881a](https://linux-hardware.org/?probe=6c54b2881a) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [713e62f936](https://linux-hardware.org/?probe=713e62f936) | Aug 27, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [b0a8f65bca](https://linux-hardware.org/?probe=b0a8f65bca) | Aug 27, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [97caef0e98](https://linux-hardware.org/?probe=97caef0e98) | Aug 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4112e03a31](https://linux-hardware.org/?probe=4112e03a31) | Aug 27, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [cfbb311c97](https://linux-hardware.org/?probe=cfbb311c97) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [883d4fbfeb](https://linux-hardware.org/?probe=883d4fbfeb) | Aug 27, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fe372a098d](https://linux-hardware.org/?probe=fe372a098d) | Aug 27, 2023 |
| HP            | 87D6 SMVB                   | Desktop     | [a2cf3918b7](https://linux-hardware.org/?probe=a2cf3918b7) | Aug 27, 2023 |
| Dell          | 0HR330                      | Desktop     | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea6d90ba09](https://linux-hardware.org/?probe=ea6d90ba09) | Aug 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [cc91bf6584](https://linux-hardware.org/?probe=cc91bf6584) | Aug 27, 2023 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [81636f5198](https://linux-hardware.org/?probe=81636f5198) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | Notebook    | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [8586d608af](https://linux-hardware.org/?probe=8586d608af) | Aug 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [25b5ca25b8](https://linux-hardware.org/?probe=25b5ca25b8) | Aug 26, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | Notebook    | [46a647db9b](https://linux-hardware.org/?probe=46a647db9b) | Aug 26, 2023 |
| Dell          | Precision M4600             | Notebook    | [fcc3763c08](https://linux-hardware.org/?probe=fcc3763c08) | Aug 26, 2023 |
| Dell          | Precision 7720              | Notebook    | [2281163932](https://linux-hardware.org/?probe=2281163932) | Aug 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [1aa1747b87](https://linux-hardware.org/?probe=1aa1747b87) | Aug 26, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [c0480c060a](https://linux-hardware.org/?probe=c0480c060a) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 25222AU       | Notebook    | [fdc78cf5a0](https://linux-hardware.org/?probe=fdc78cf5a0) | Aug 26, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [b67fbfb529](https://linux-hardware.org/?probe=b67fbfb529) | Aug 26, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| HP            | 1998                        | Desktop     | [2c6c07a7d3](https://linux-hardware.org/?probe=2c6c07a7d3) | Aug 26, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dfa16eab4](https://linux-hardware.org/?probe=7dfa16eab4) | Aug 26, 2023 |
| Intel         | D33217CK G76541-301         | Desktop     | [24b3b7aac4](https://linux-hardware.org/?probe=24b3b7aac4) | Aug 26, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [9bde22726b](https://linux-hardware.org/?probe=9bde22726b) | Aug 26, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [c5cae456b6](https://linux-hardware.org/?probe=c5cae456b6) | Aug 26, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | Notebook    | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [2ee2c8dd6c](https://linux-hardware.org/?probe=2ee2c8dd6c) | Aug 26, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7db44bc8af](https://linux-hardware.org/?probe=7db44bc8af) | Aug 26, 2023 |
| Positivo      | POS-PIG41BA POSITIVO        | Desktop     | [05dc1d19de](https://linux-hardware.org/?probe=05dc1d19de) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [69824bbd6d](https://linux-hardware.org/?probe=69824bbd6d) | Aug 26, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [ff832aca4a](https://linux-hardware.org/?probe=ff832aca4a) | Aug 26, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [aa3b7fe20f](https://linux-hardware.org/?probe=aa3b7fe20f) | Aug 26, 2023 |
| ASUSTek       | AT5NM10-I                   | Desktop     | [15edd1ec31](https://linux-hardware.org/?probe=15edd1ec31) | Aug 26, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e86c3faf2e](https://linux-hardware.org/?probe=e86c3faf2e) | Aug 26, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [451af13730](https://linux-hardware.org/?probe=451af13730) | Aug 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [9cf3912874](https://linux-hardware.org/?probe=9cf3912874) | Aug 26, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [0620b43b6a](https://linux-hardware.org/?probe=0620b43b6a) | Aug 26, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [aa48da4e34](https://linux-hardware.org/?probe=aa48da4e34) | Aug 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [3c528e98c6](https://linux-hardware.org/?probe=3c528e98c6) | Aug 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [78df724503](https://linux-hardware.org/?probe=78df724503) | Aug 26, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [5febb12d66](https://linux-hardware.org/?probe=5febb12d66) | Aug 26, 2023 |
| Biostar       | G41D3C                      | Desktop     | [5e2c852104](https://linux-hardware.org/?probe=5e2c852104) | Aug 26, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [32e62fd188](https://linux-hardware.org/?probe=32e62fd188) | Aug 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [35aa466ca4](https://linux-hardware.org/?probe=35aa466ca4) | Aug 26, 2023 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [6fc7c35bc9](https://linux-hardware.org/?probe=6fc7c35bc9) | Aug 26, 2023 |
| Lenovo        | IdeaPad Z480                | Notebook    | [e0989b8f9e](https://linux-hardware.org/?probe=e0989b8f9e) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [baa3bc61e9](https://linux-hardware.org/?probe=baa3bc61e9) | Aug 25, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [0f16274ad6](https://linux-hardware.org/?probe=0f16274ad6) | Aug 25, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [98a1dbe051](https://linux-hardware.org/?probe=98a1dbe051) | Aug 25, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [2d3a15b432](https://linux-hardware.org/?probe=2d3a15b432) | Aug 25, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [d9898111f8](https://linux-hardware.org/?probe=d9898111f8) | Aug 25, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [03740cd24c](https://linux-hardware.org/?probe=03740cd24c) | Aug 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [5457261ab6](https://linux-hardware.org/?probe=5457261ab6) | Aug 25, 2023 |
| Dell          | Latitude E6400              | Notebook    | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [1bc8a402b3](https://linux-hardware.org/?probe=1bc8a402b3) | Aug 25, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b5c86f44b7](https://linux-hardware.org/?probe=b5c86f44b7) | Aug 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [0145505cea](https://linux-hardware.org/?probe=0145505cea) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | Notebook    | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [03fbbf3d84](https://linux-hardware.org/?probe=03fbbf3d84) | Aug 25, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [8445b944a5](https://linux-hardware.org/?probe=8445b944a5) | Aug 25, 2023 |
| Dell          | Studio 1747                 | Notebook    | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| Dell          | Studio 1735                 | Notebook    | [5932ab2004](https://linux-hardware.org/?probe=5932ab2004) | Aug 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [255eeb3d65](https://linux-hardware.org/?probe=255eeb3d65) | Aug 25, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b328603445](https://linux-hardware.org/?probe=b328603445) | Aug 25, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [70a6d20dbf](https://linux-hardware.org/?probe=70a6d20dbf) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d3c6faac81](https://linux-hardware.org/?probe=d3c6faac81) | Aug 25, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [081372c3c4](https://linux-hardware.org/?probe=081372c3c4) | Aug 25, 2023 |
| HP            | Laptop                      | Notebook    | [94fd1a7af2](https://linux-hardware.org/?probe=94fd1a7af2) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [5f24b13b35](https://linux-hardware.org/?probe=5f24b13b35) | Aug 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8237cf85b3](https://linux-hardware.org/?probe=8237cf85b3) | Aug 25, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [7da367fdec](https://linux-hardware.org/?probe=7da367fdec) | Aug 25, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [037e041959](https://linux-hardware.org/?probe=037e041959) | Aug 25, 2023 |
| HP            | 21F5 0A                     | Desktop     | [812718f3e7](https://linux-hardware.org/?probe=812718f3e7) | Aug 25, 2023 |
| Star Labs     | Lite                        | Notebook    | [0d0821a7dd](https://linux-hardware.org/?probe=0d0821a7dd) | Aug 25, 2023 |
| Dell          | G5 5590                     | Notebook    | [c13a60889c](https://linux-hardware.org/?probe=c13a60889c) | Aug 25, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0cb8d58c01](https://linux-hardware.org/?probe=0cb8d58c01) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [53323ddb53](https://linux-hardware.org/?probe=53323ddb53) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Toshiba       | PORTEGE R705                | Notebook    | [cae49b36a8](https://linux-hardware.org/?probe=cae49b36a8) | Aug 24, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| Lenovo        | ThinkPad T450s 20BWS2M30... | Notebook    | [052c7eaa90](https://linux-hardware.org/?probe=052c7eaa90) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [85984e2830](https://linux-hardware.org/?probe=85984e2830) | Aug 24, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [df7d53dd55](https://linux-hardware.org/?probe=df7d53dd55) | Aug 24, 2023 |
| Pegatron      | EVANS                       | Desktop     | [1b32c5d271](https://linux-hardware.org/?probe=1b32c5d271) | Aug 24, 2023 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | Desktop     | [088ba21947](https://linux-hardware.org/?probe=088ba21947) | Aug 24, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [928ea69caf](https://linux-hardware.org/?probe=928ea69caf) | Aug 24, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [2431197665](https://linux-hardware.org/?probe=2431197665) | Aug 24, 2023 |
| Acer          | Aspire TC-115               | Desktop     | [1c22aff012](https://linux-hardware.org/?probe=1c22aff012) | Aug 24, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [4d282e98b2](https://linux-hardware.org/?probe=4d282e98b2) | Aug 24, 2023 |
| Lenovo        | ThinkCentre M72e 3597A56    | Desktop     | [6b6d2e95f9](https://linux-hardware.org/?probe=6b6d2e95f9) | Aug 24, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | Notebook    | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [1bb6f8d738](https://linux-hardware.org/?probe=1bb6f8d738) | Aug 24, 2023 |
| Acer          | EQ45LM                      | Desktop     | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [4953513629](https://linux-hardware.org/?probe=4953513629) | Aug 24, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [03cff37b1a](https://linux-hardware.org/?probe=03cff37b1a) | Aug 24, 2023 |
| ASUSTek       | P7H55-M BR                  | Desktop     | [820b86d560](https://linux-hardware.org/?probe=820b86d560) | Aug 24, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [88533268cf](https://linux-hardware.org/?probe=88533268cf) | Aug 23, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [e45572b49a](https://linux-hardware.org/?probe=e45572b49a) | Aug 23, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0eb0410780](https://linux-hardware.org/?probe=0eb0410780) | Aug 23, 2023 |
| Thomson       | GENEO14C-4WH128             | Notebook    | [b145cbea54](https://linux-hardware.org/?probe=b145cbea54) | Aug 23, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| Intel         | DZ77BH-55K AAG39008-400     | Desktop     | [30c81f585a](https://linux-hardware.org/?probe=30c81f585a) | Aug 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0228bd6d42](https://linux-hardware.org/?probe=0228bd6d42) | Aug 23, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [2d16969538](https://linux-hardware.org/?probe=2d16969538) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [94195a7c07](https://linux-hardware.org/?probe=94195a7c07) | Aug 23, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [c5ea9af7cd](https://linux-hardware.org/?probe=c5ea9af7cd) | Aug 23, 2023 |
| ASUSTek       | Q550LF                      | Notebook    | [f6531bb92a](https://linux-hardware.org/?probe=f6531bb92a) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | Notebook    | [d0f87a58ec](https://linux-hardware.org/?probe=d0f87a58ec) | Aug 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [50bcada7d4](https://linux-hardware.org/?probe=50bcada7d4) | Aug 23, 2023 |
| Positivo      | M7X0S Bottom                | Notebook    | [f78713080f](https://linux-hardware.org/?probe=f78713080f) | Aug 23, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [aa959925b8](https://linux-hardware.org/?probe=aa959925b8) | Aug 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [796925bf51](https://linux-hardware.org/?probe=796925bf51) | Aug 23, 2023 |
| GEEKOM        | GM08i3T                     | Desktop     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Positivo      | C14CU51                     | Notebook    | [b8c9fbc7b7](https://linux-hardware.org/?probe=b8c9fbc7b7) | Aug 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [618b994ac1](https://linux-hardware.org/?probe=618b994ac1) | Aug 23, 2023 |
| Dell          | Latitude E5420              | Notebook    | [102bee1da1](https://linux-hardware.org/?probe=102bee1da1) | Aug 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | Notebook    | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [7da77cb4d7](https://linux-hardware.org/?probe=7da77cb4d7) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [be00a84105](https://linux-hardware.org/?probe=be00a84105) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [65747a7530](https://linux-hardware.org/?probe=65747a7530) | Aug 22, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| Intel         | H81                         | Desktop     | [fe1e95123d](https://linux-hardware.org/?probe=fe1e95123d) | Aug 22, 2023 |
| MSI           | CR610M                      | Notebook    | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [e99aa2e4d7](https://linux-hardware.org/?probe=e99aa2e4d7) | Aug 22, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [c8aa8973a4](https://linux-hardware.org/?probe=c8aa8973a4) | Aug 22, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3f2ff7e9c7](https://linux-hardware.org/?probe=3f2ff7e9c7) | Aug 22, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [577e8e228f](https://linux-hardware.org/?probe=577e8e228f) | Aug 22, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [cb2839d263](https://linux-hardware.org/?probe=cb2839d263) | Aug 22, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [d39f8430ac](https://linux-hardware.org/?probe=d39f8430ac) | Aug 22, 2023 |
| HP            | 1850                        | Desktop     | [d9b3f59f97](https://linux-hardware.org/?probe=d9b3f59f97) | Aug 22, 2023 |
| HP            | Presario CQ57               | Notebook    | [bfc59ff9cd](https://linux-hardware.org/?probe=bfc59ff9cd) | Aug 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [10badbd20d](https://linux-hardware.org/?probe=10badbd20d) | Aug 22, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | Desktop     | [48f65a86aa](https://linux-hardware.org/?probe=48f65a86aa) | Aug 22, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [d5350f0d1c](https://linux-hardware.org/?probe=d5350f0d1c) | Aug 22, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [3bdb30f543](https://linux-hardware.org/?probe=3bdb30f543) | Aug 22, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [9b3a3cd47b](https://linux-hardware.org/?probe=9b3a3cd47b) | Aug 22, 2023 |
| ASUSTek       | Z450UAK                     | Notebook    | [68fb2ce5ec](https://linux-hardware.org/?probe=68fb2ce5ec) | Aug 22, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [04a07b8fa6](https://linux-hardware.org/?probe=04a07b8fa6) | Aug 22, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [05eae6c877](https://linux-hardware.org/?probe=05eae6c877) | Aug 22, 2023 |
| Lenovo        | H415                        | Desktop     | [e6277f1ab8](https://linux-hardware.org/?probe=e6277f1ab8) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | Notebook    | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [33442fefbf](https://linux-hardware.org/?probe=33442fefbf) | Aug 21, 2023 |
| ASRock        | 890GX Pro3                  | Desktop     | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [191c724d49](https://linux-hardware.org/?probe=191c724d49) | Aug 21, 2023 |
| Intel         | H61                         | Desktop     | [4d6bf88f48](https://linux-hardware.org/?probe=4d6bf88f48) | Aug 21, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [e9c7a12d52](https://linux-hardware.org/?probe=e9c7a12d52) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [9455337239](https://linux-hardware.org/?probe=9455337239) | Aug 21, 2023 |
| Toshiba       | dynabook B350/22A           | Notebook    | [80ad4cd1ff](https://linux-hardware.org/?probe=80ad4cd1ff) | Aug 21, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [33ad1ac951](https://linux-hardware.org/?probe=33ad1ac951) | Aug 21, 2023 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [4590ebf626](https://linux-hardware.org/?probe=4590ebf626) | Aug 21, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [7993a53688](https://linux-hardware.org/?probe=7993a53688) | Aug 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [e3b2126509](https://linux-hardware.org/?probe=e3b2126509) | Aug 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e28046c842](https://linux-hardware.org/?probe=e28046c842) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [97ed27473e](https://linux-hardware.org/?probe=97ed27473e) | Aug 20, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [e84eba7c7d](https://linux-hardware.org/?probe=e84eba7c7d) | Aug 20, 2023 |
| eMachines     | E520 V1.06                  | Notebook    | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| HP            | 2B52                        | Desktop     | [ed7526d18f](https://linux-hardware.org/?probe=ed7526d18f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8c805fa379](https://linux-hardware.org/?probe=8c805fa379) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [dac6078c1b](https://linux-hardware.org/?probe=dac6078c1b) | Aug 20, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [e5512efda4](https://linux-hardware.org/?probe=e5512efda4) | Aug 20, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6c5abd788f](https://linux-hardware.org/?probe=6c5abd788f) | Aug 20, 2023 |
| HP            | 15 TouchSmart               | Notebook    | [d756b77e06](https://linux-hardware.org/?probe=d756b77e06) | Aug 20, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [61ae2e27b8](https://linux-hardware.org/?probe=61ae2e27b8) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [398280327e](https://linux-hardware.org/?probe=398280327e) | Aug 19, 2023 |
| Intel         | X99                         | Desktop     | [e16fe5b0f3](https://linux-hardware.org/?probe=e16fe5b0f3) | Aug 19, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [64a2767d60](https://linux-hardware.org/?probe=64a2767d60) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [f75baa8a07](https://linux-hardware.org/?probe=f75baa8a07) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [344dab6e5e](https://linux-hardware.org/?probe=344dab6e5e) | Aug 19, 2023 |
| Dell          | Latitude E5520              | Notebook    | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [1824f3c712](https://linux-hardware.org/?probe=1824f3c712) | Aug 19, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | Desktop     | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c19ed9405c](https://linux-hardware.org/?probe=c19ed9405c) | Aug 19, 2023 |
| Danew         | Dbook 131                   | Notebook    | [35ea124809](https://linux-hardware.org/?probe=35ea124809) | Aug 19, 2023 |
| HP            | G62                         | Notebook    | [778c1c04b9](https://linux-hardware.org/?probe=778c1c04b9) | Aug 19, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [5768055184](https://linux-hardware.org/?probe=5768055184) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [76dda9cde6](https://linux-hardware.org/?probe=76dda9cde6) | Aug 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8e7844a79d](https://linux-hardware.org/?probe=8e7844a79d) | Aug 19, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [bbf0f31c1b](https://linux-hardware.org/?probe=bbf0f31c1b) | Aug 19, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [8735b5577b](https://linux-hardware.org/?probe=8735b5577b) | Aug 18, 2023 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [8da8bfe394](https://linux-hardware.org/?probe=8da8bfe394) | Aug 18, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Toshiba       | IS 1422                     | Notebook    | [2ad1bbf471](https://linux-hardware.org/?probe=2ad1bbf471) | Aug 18, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [b5e6b20270](https://linux-hardware.org/?probe=b5e6b20270) | Aug 18, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [9b7cf0384c](https://linux-hardware.org/?probe=9b7cf0384c) | Aug 18, 2023 |
| Dell          | Latitude E6500              | Notebook    | [5d1f16198a](https://linux-hardware.org/?probe=5d1f16198a) | Aug 18, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7add4465a9](https://linux-hardware.org/?probe=7add4465a9) | Aug 18, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c8eaccabf2](https://linux-hardware.org/?probe=c8eaccabf2) | Aug 18, 2023 |
| AZW           | EQ                          | Desktop     | [6fda99ad46](https://linux-hardware.org/?probe=6fda99ad46) | Aug 18, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [d4849fe5f4](https://linux-hardware.org/?probe=d4849fe5f4) | Aug 18, 2023 |
| ECS           | A55F-M4                     | Desktop     | [93a5944754](https://linux-hardware.org/?probe=93a5944754) | Aug 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [bab5968f80](https://linux-hardware.org/?probe=bab5968f80) | Aug 18, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [ae37d9f640](https://linux-hardware.org/?probe=ae37d9f640) | Aug 18, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [41b00dc8b3](https://linux-hardware.org/?probe=41b00dc8b3) | Aug 18, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [154e2db6b7](https://linux-hardware.org/?probe=154e2db6b7) | Aug 18, 2023 |
| Lenovo        | ThinkPad T420 418063G       | Notebook    | [f8e7a666cc](https://linux-hardware.org/?probe=f8e7a666cc) | Aug 18, 2023 |
| Toshiba       | Satellite Pro C850-10N      | Notebook    | [590ac28f26](https://linux-hardware.org/?probe=590ac28f26) | Aug 18, 2023 |
| Intel         | NUC13ANBi7 N13084-202       | Mini pc     | [f5c73b3526](https://linux-hardware.org/?probe=f5c73b3526) | Aug 18, 2023 |
| Dell          | 0200DY A00                  | Desktop     | [9b94c2313c](https://linux-hardware.org/?probe=9b94c2313c) | Aug 18, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d84596d3c1](https://linux-hardware.org/?probe=d84596d3c1) | Aug 18, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [c156f586f5](https://linux-hardware.org/?probe=c156f586f5) | Aug 18, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [41b34e60fd](https://linux-hardware.org/?probe=41b34e60fd) | Aug 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f1441ed73a](https://linux-hardware.org/?probe=f1441ed73a) | Aug 18, 2023 |
| Medion        | S14406                      | Convertible | [c510f62cbb](https://linux-hardware.org/?probe=c510f62cbb) | Aug 18, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [b7ae4d22b3](https://linux-hardware.org/?probe=b7ae4d22b3) | Aug 17, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7658411c87](https://linux-hardware.org/?probe=7658411c87) | Aug 17, 2023 |
| Panasonic     | CF-31AQAAA1M                | Notebook    | [64416dbba5](https://linux-hardware.org/?probe=64416dbba5) | Aug 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [7da49ac1c3](https://linux-hardware.org/?probe=7da49ac1c3) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [809590bdb0](https://linux-hardware.org/?probe=809590bdb0) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [c956862ccd](https://linux-hardware.org/?probe=c956862ccd) | Aug 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| HP            | 8768 A                      | Desktop     | [a2b7f6905c](https://linux-hardware.org/?probe=a2b7f6905c) | Aug 17, 2023 |
| Sony          | VGN-NW2SRF_S                | Notebook    | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [29c2bc1929](https://linux-hardware.org/?probe=29c2bc1929) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [1f416788fa](https://linux-hardware.org/?probe=1f416788fa) | Aug 17, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [0ddde115f9](https://linux-hardware.org/?probe=0ddde115f9) | Aug 17, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [915e37b55d](https://linux-hardware.org/?probe=915e37b55d) | Aug 17, 2023 |
| Dell          | Latitude E6520              | Notebook    | [15420bd102](https://linux-hardware.org/?probe=15420bd102) | Aug 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [0a48b003bb](https://linux-hardware.org/?probe=0a48b003bb) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dbdb6ca163](https://linux-hardware.org/?probe=dbdb6ca163) | Aug 17, 2023 |
| Shuttle       | DS20U                       | Desktop     | [3a1ceb6021](https://linux-hardware.org/?probe=3a1ceb6021) | Aug 17, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [fe8d01fa26](https://linux-hardware.org/?probe=fe8d01fa26) | Aug 17, 2023 |
| Dell          | XPS 9320                    | Notebook    | [cb112d9f03](https://linux-hardware.org/?probe=cb112d9f03) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b82ccd639](https://linux-hardware.org/?probe=6b82ccd639) | Aug 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| GPU Compan... | GWTN141-1                   | Notebook    | [97416e9fda](https://linux-hardware.org/?probe=97416e9fda) | Aug 16, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [1ed920cd72](https://linux-hardware.org/?probe=1ed920cd72) | Aug 16, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [d3926b324c](https://linux-hardware.org/?probe=d3926b324c) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [080867b516](https://linux-hardware.org/?probe=080867b516) | Aug 16, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [aeb3f34daa](https://linux-hardware.org/?probe=aeb3f34daa) | Aug 16, 2023 |
| Gigabyte      | 965P-S3                     | Desktop     | [d9557da16c](https://linux-hardware.org/?probe=d9557da16c) | Aug 16, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [3151636f73](https://linux-hardware.org/?probe=3151636f73) | Aug 16, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| Dell          | Latitude E6430              | Notebook    | [87849c0e6c](https://linux-hardware.org/?probe=87849c0e6c) | Aug 16, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [6026ba6c8a](https://linux-hardware.org/?probe=6026ba6c8a) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [4e25d8ef9f](https://linux-hardware.org/?probe=4e25d8ef9f) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | Notebook    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [78a5205783](https://linux-hardware.org/?probe=78a5205783) | Aug 16, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [881b50cb6f](https://linux-hardware.org/?probe=881b50cb6f) | Aug 16, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [57a2ddf4a7](https://linux-hardware.org/?probe=57a2ddf4a7) | Aug 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [140af1f27b](https://linux-hardware.org/?probe=140af1f27b) | Aug 15, 2023 |
| Acer          | EM61SM/EM61PM               | Desktop     | [428f134de7](https://linux-hardware.org/?probe=428f134de7) | Aug 15, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [166b18583b](https://linux-hardware.org/?probe=166b18583b) | Aug 15, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [8b4200849d](https://linux-hardware.org/?probe=8b4200849d) | Aug 15, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [8d6a3e990c](https://linux-hardware.org/?probe=8d6a3e990c) | Aug 15, 2023 |
| Packard Be... | EasyNote TSX66HR            | Notebook    | [f1b16023fd](https://linux-hardware.org/?probe=f1b16023fd) | Aug 15, 2023 |
| Dell          | Latitude E5470              | Notebook    | [f09173281d](https://linux-hardware.org/?probe=f09173281d) | Aug 15, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | Notebook    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [a5086e207e](https://linux-hardware.org/?probe=a5086e207e) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [ac6dd63085](https://linux-hardware.org/?probe=ac6dd63085) | Aug 15, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [f53da0a40d](https://linux-hardware.org/?probe=f53da0a40d) | Aug 15, 2023 |
| Samsung       | 755XDA                      | Notebook    | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASRock        | A320M/ac                    | Desktop     | [5012358457](https://linux-hardware.org/?probe=5012358457) | Aug 15, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [1bb822c058](https://linux-hardware.org/?probe=1bb822c058) | Aug 13, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c24273512e](https://linux-hardware.org/?probe=c24273512e) | Aug 13, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ebc3e37c86](https://linux-hardware.org/?probe=ebc3e37c86) | Aug 13, 2023 |
| Lenovo        | ThinkPad E595 20NF0006GE    | Notebook    | [c9c068e82b](https://linux-hardware.org/?probe=c9c068e82b) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [e934dcd506](https://linux-hardware.org/?probe=e934dcd506) | Aug 13, 2023 |
| HP            | 3031h                       | Desktop     | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [60746f5bad](https://linux-hardware.org/?probe=60746f5bad) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | Notebook    | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| Samsung       | 960XFH                      | Notebook    | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [f900ebabde](https://linux-hardware.org/?probe=f900ebabde) | Aug 13, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [61908d704c](https://linux-hardware.org/?probe=61908d704c) | Aug 13, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | Notebook    | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [67f821bd4d](https://linux-hardware.org/?probe=67f821bd4d) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | Notebook    | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0c0df32662](https://linux-hardware.org/?probe=0c0df32662) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| ASRock        | 970A-G                      | Desktop     | [5a2b77eaee](https://linux-hardware.org/?probe=5a2b77eaee) | Aug 12, 2023 |
| ZOTAC         | ZBOXNANO-ID67/ID68/ID69     | Mini pc     | [169c6d3b85](https://linux-hardware.org/?probe=169c6d3b85) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Biostar       | B660GTQ                     | Desktop     | [520d57cadc](https://linux-hardware.org/?probe=520d57cadc) | Aug 11, 2023 |
| MSI           | H410M-A PRO                 | Desktop     | [de3739c2a5](https://linux-hardware.org/?probe=de3739c2a5) | Aug 11, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [a60b6f6ca2](https://linux-hardware.org/?probe=a60b6f6ca2) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| HP            | ProLiant ML115 G5           | Desktop     | [305ccefd04](https://linux-hardware.org/?probe=305ccefd04) | Aug 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ee14fdafcf](https://linux-hardware.org/?probe=ee14fdafcf) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| HP            | 18E7                        | Desktop     | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Google        | Kip                         | Notebook    | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| HP            | 2215                        | Desktop     | [40ace58487](https://linux-hardware.org/?probe=40ace58487) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Acer          | Extensa 5630                | Notebook    | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [73c1dd0c14](https://linux-hardware.org/?probe=73c1dd0c14) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [7acbd56a40](https://linux-hardware.org/?probe=7acbd56a40) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| ASUSTek       | F3L                         | Notebook    | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | Notebook    | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [e3cf4cec26](https://linux-hardware.org/?probe=e3cf4cec26) | Aug 09, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [a936584caa](https://linux-hardware.org/?probe=a936584caa) | Aug 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 4665      | 30.02%  |
| OpenMandriva 4.3    | 4570      | 29.41%  |
| OpenMandriva 23.01  | 1966      | 12.65%  |
| OpenMandriva 23.03  | 1868      | 12.02%  |
| OpenMandriva 4.50   | 870       | 5.6%    |
| OpenMandriva 23.08  | 743       | 4.78%   |
| OpenMandriva 4.90   | 351       | 2.26%   |
| OpenMandriva 23.07  | 124       | 0.8%    |
| OpenMandriva 23.06  | 111       | 0.71%   |
| OpenMandriva 23.90  | 82        | 0.53%   |
| OpenMandriva 22.12  | 80        | 0.51%   |
| OpenMandriva 23.09  | 71        | 0.46%   |
| OpenMandriva 4.1    | 14        | 0.09%   |
| OpenMandriva 22.11  | 8         | 0.05%   |
| OpenMandriva 22.90  | 6         | 0.04%   |
| OpenMandriva 2014.0 | 4         | 0.03%   |
| OpenMandriva 3.0    | 3         | 0.02%   |
| OpenMandriva 4.0    | 2         | 0.01%   |
| OpenMandriva 4.0.1  | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| OpenMandriva | 14591     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 4495      | 28.66%  |
| 5.16.7-desktop-1omv4003       | 4286      | 27.32%  |
| 6.2.6-desktop-1omv2390        | 1805      | 11.51%  |
| 6.1.1-desktop-1omv2290        | 1801      | 11.48%  |
| 6.4.11-desktop-1omv2390       | 544       | 3.47%   |
| 5.12.4-desktop-1omv4050       | 372       | 2.37%   |
| 5.16.13-desktop-1omv4003      | 326       | 2.08%   |
| 5.18.12-desktop-3omv4090      | 302       | 1.93%   |
| 6.3.5-desktop-3omv2390        | 217       | 1.38%   |
| 5.11.12-desktop-1omv4002      | 214       | 1.36%   |
| 6.4.8-desktop-2omv2390        | 206       | 1.31%   |
| 5.19.5-desktop-1omv4090       | 166       | 1.06%   |
| 6.1.4-desktop-1omv2301        | 140       | 0.89%   |
| 5.19.12-desktop-2omv4090      | 123       | 0.78%   |
| 5.14.7-desktop-1omv4050       | 107       | 0.68%   |
| 6.0.10-desktop-2omv22090      | 80        | 0.51%   |
| 6.5.0-desktop-1omv2390        | 69        | 0.44%   |
| 6.2.2-desktop-1omv2390        | 45        | 0.29%   |
| 5.14.14-desktop-1omv4050      | 26        | 0.17%   |
| 6.2.1-desktop-1omv2390        | 23        | 0.15%   |
| 5.12.7-desktop-1omv4003       | 22        | 0.14%   |
| 5.17.1-desktop-2omv4050       | 21        | 0.13%   |
| 6.5.1-desktop-1omv2390        | 17        | 0.11%   |
| 5.19.11-desktop-2omv4090      | 17        | 0.11%   |
| 6.0.2-desktop-1omv4090        | 16        | 0.1%    |
| 6.1.2-desktop-1omv2301        | 14        | 0.09%   |
| 5.5.12-desktop-1omv4001       | 12        | 0.08%   |
| 5.11.0-desktop-clang-1omv4002 | 10        | 0.06%   |
| 6.2.8-desktop-1omv2390        | 7         | 0.04%   |
| 6.2.0-desktop-0.rc2.1omv2301  | 7         | 0.04%   |
| 6.1.11-desktop-1omv2390       | 7         | 0.04%   |
| 6.0.2-desktop-1omv4050        | 7         | 0.04%   |
| 5.19.1-desktop-1omv4090       | 6         | 0.04%   |
| 5.18.13-desktop-1omv4090      | 6         | 0.04%   |
| 5.16.3-desktop-2omv4050       | 6         | 0.04%   |
| 6.0.9-desktop-1omv22090       | 5         | 0.03%   |
| 5.16.5-desktop-2omv4003       | 5         | 0.03%   |
| 5.10.13-desktop-1omv4002      | 5         | 0.03%   |
| 6.4.7-desktop-1omv2390        | 4         | 0.03%   |
| 6.4.3-desktop-2omv2390        | 4         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.14 | 4495      | 28.66%  |
| 5.16.7  | 4288      | 27.34%  |
| 6.2.6   | 1805      | 11.51%  |
| 6.1.1   | 1801      | 11.48%  |
| 6.4.11  | 544       | 3.47%   |
| 5.12.4  | 372       | 2.37%   |
| 5.16.13 | 328       | 2.09%   |
| 5.18.12 | 302       | 1.93%   |
| 6.3.5   | 217       | 1.38%   |
| 5.11.12 | 214       | 1.36%   |
| 6.4.8   | 206       | 1.31%   |
| 5.19.5  | 166       | 1.06%   |
| 6.1.4   | 143       | 0.91%   |
| 5.19.12 | 124       | 0.79%   |
| 5.14.7  | 107       | 0.68%   |
| 6.0.10  | 82        | 0.52%   |
| 6.5.0   | 72        | 0.46%   |
| 6.2.2   | 45        | 0.29%   |
| 5.14.14 | 26        | 0.17%   |
| 5.12.7  | 25        | 0.16%   |
| 6.2.1   | 23        | 0.15%   |
| 6.0.2   | 23        | 0.15%   |
| 5.17.1  | 23        | 0.15%   |
| 5.19.11 | 18        | 0.11%   |
| 6.5.1   | 17        | 0.11%   |
| 6.1.2   | 14        | 0.09%   |
| 5.5.12  | 12        | 0.08%   |
| 5.11.0  | 12        | 0.08%   |
| 6.2.0   | 9         | 0.06%   |
| 6.2.8   | 7         | 0.04%   |
| 6.1.11  | 7         | 0.04%   |
| 6.0.9   | 7         | 0.04%   |
| 5.19.1  | 6         | 0.04%   |
| 5.18.13 | 6         | 0.04%   |
| 5.16.5  | 6         | 0.04%   |
| 5.16.3  | 6         | 0.04%   |
| 6.0.0   | 5         | 0.03%   |
| 5.10.13 | 5         | 0.03%   |
| 6.4.7   | 4         | 0.03%   |
| 6.4.3   | 4         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 4564      | 29.24%  |
| 5.10    | 4506      | 28.87%  |
| 6.1     | 1972      | 12.63%  |
| 6.2     | 1894      | 12.13%  |
| 6.4     | 764       | 4.89%   |
| 5.12    | 402       | 2.58%   |
| 5.19    | 324       | 2.08%   |
| 5.18    | 315       | 2.02%   |
| 5.11    | 234       | 1.5%    |
| 6.3     | 228       | 1.46%   |
| 5.14    | 134       | 0.86%   |
| 6.0     | 121       | 0.78%   |
| 6.5     | 89        | 0.57%   |
| 5.17    | 25        | 0.16%   |
| 5.5     | 14        | 0.09%   |
| 5.13    | 5         | 0.03%   |
| 4.1     | 4         | 0.03%   |
| 5.15    | 3         | 0.02%   |
| 5.9     | 2         | 0.01%   |
| 5.8     | 2         | 0.01%   |
| 5.1     | 2         | 0.01%   |
| 4.19    | 2         | 0.01%   |
| 5.3     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 14589     | 99.99%  |
| aarch64 | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 13895     | 94.31%  |
| GNOME    | 532       | 3.61%   |
| LXQt     | 208       | 1.41%   |
| Unknown  | 49        | 0.33%   |
| Cinnamon | 19        | 0.13%   |
| Budgie   | 15        | 0.1%    |
| XFCE     | 10        | 0.07%   |
| KDE4     | 2         | 0.01%   |
| KDE      | 2         | 0.01%   |
| DWM      | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 13514     | 91.21%  |
| Wayland | 1299      | 8.77%   |
| Unknown | 3         | 0.02%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 14114     | 96.14%  |
| GDM     | 532       | 3.62%   |
| LightDM | 22        | 0.15%   |
| Unknown | 10        | 0.07%   |
| KDM     | 2         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 7906      | 52.9%   |
| de_DE   | 1161      | 7.77%   |
| fr_FR   | 858       | 5.74%   |
| ru_RU   | 816       | 5.46%   |
| pt_BR   | 637       | 4.26%   |
| pl_PL   | 526       | 3.52%   |
| it_IT   | 431       | 2.88%   |
| en_GB   | 413       | 2.76%   |
| es_ES   | 338       | 2.26%   |
| cs_CZ   | 264       | 1.77%   |
| es_MX   | 149       | 1%      |
| es_AR   | 108       | 0.72%   |
| de_AT   | 101       | 0.68%   |
| en_CA   | 97        | 0.65%   |
| hu_HU   | 96        | 0.64%   |
| en_AU   | 78        | 0.52%   |
| nl_NL   | 74        | 0.5%    |
| en_IN   | 67        | 0.45%   |
| fr_CA   | 54        | 0.36%   |
| de_CH   | 51        | 0.34%   |
| es_CO   | 49        | 0.33%   |
| pt_PT   | 48        | 0.32%   |
| es_CL   | 45        | 0.3%    |
| tr_TR   | 44        | 0.29%   |
| fr_BE   | 43        | 0.29%   |
| es_VE   | 35        | 0.23%   |
| da_DK   | 33        | 0.22%   |
| nl_BE   | 32        | 0.21%   |
| ru_UA   | 30        | 0.2%    |
| es_PE   | 25        | 0.17%   |
| fr_CH   | 24        | 0.16%   |
| Unknown | 24        | 0.16%   |
| ro_RO   | 23        | 0.15%   |
| es_UY   | 18        | 0.12%   |
| en_NZ   | 16        | 0.11%   |
| en_ZA   | 15        | 0.1%    |
| nb_NO   | 14        | 0.09%   |
| uk_UA   | 13        | 0.09%   |
| ja_JP   | 13        | 0.09%   |
| en_HK   | 12        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 7435      | 50.56%  |
| BIOS | 7270      | 49.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 10701     | 70.21%  |
| Ext4     | 4114      | 26.99%  |
| Btrfs    | 264       | 1.73%   |
| Xfs      | 58        | 0.38%   |
| F2fs     | 58        | 0.38%   |
| Ext3     | 12        | 0.08%   |
| Ext2     | 11        | 0.07%   |
| Jfs      | 9         | 0.06%   |
| Unknown  | 8         | 0.05%   |
| Reiserfs | 6         | 0.04%   |
| Tmpfs    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 9913      | 67.09%  |
| MBR     | 4822      | 32.64%  |
| Unknown | 40        | 0.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8107      | 54.3%   |
| No        | 6823      | 45.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7839      | 53.16%  |
| Yes       | 6908      | 46.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 2531      | 17.35%  |
| Hewlett-Packard     | 1880      | 12.88%  |
| Lenovo              | 1770      | 12.13%  |
| Dell                | 1693      | 11.6%   |
| Gigabyte Technology | 1211      | 8.3%    |
| Acer                | 974       | 6.68%   |
| MSI                 | 861       | 5.9%    |
| ASRock              | 638       | 4.37%   |
| Toshiba             | 344       | 2.36%   |
| Intel               | 290       | 1.99%   |
| Apple               | 217       | 1.49%   |
| Fujitsu             | 192       | 1.32%   |
| Samsung Electronics | 162       | 1.11%   |
| Sony                | 161       | 1.1%    |
| Medion              | 123       | 0.84%   |
| Foxconn             | 90        | 0.62%   |
| Unknown             | 85        | 0.58%   |
| Biostar             | 84        | 0.58%   |
| Positivo            | 83        | 0.57%   |
| Pegatron            | 78        | 0.53%   |
| Packard Bell        | 73        | 0.5%    |
| ECS                 | 57        | 0.39%   |
| Fujitsu Siemens     | 43        | 0.29%   |
| HUAWEI              | 42        | 0.29%   |
| AZW                 | 40        | 0.27%   |
| Chuwi               | 37        | 0.25%   |
| eMachines           | 36        | 0.25%   |
| Notebook            | 31        | 0.21%   |
| Microsoft           | 30        | 0.21%   |
| TUXEDO              | 27        | 0.19%   |
| Philco              | 26        | 0.18%   |
| BESSTAR Tech        | 26        | 0.18%   |
| LG Electronics      | 23        | 0.16%   |
| Gateway             | 23        | 0.16%   |
| Alienware           | 22        | 0.15%   |
| Google              | 21        | 0.14%   |
| Supermicro          | 18        | 0.12%   |
| NEC Computers       | 17        | 0.12%   |
| ZOTAC               | 16        | 0.11%   |
| Shuttle             | 16        | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| ASUS All Series               | 137       | 0.94%   |
| Unknown                       | 130       | 0.89%   |
| ASUS UX31E                    | 125       | 0.86%   |
| HP Notebook                   | 69        | 0.47%   |
| Dell OptiPlex 7010            | 51        | 0.35%   |
| Dell Latitude 3120            | 48        | 0.33%   |
| Dell OptiPlex 780             | 39        | 0.27%   |
| Dell Latitude 3190 2-in-1     | 34        | 0.23%   |
| HP Pavilion g6                | 32        | 0.22%   |
| Dell Inspiron 3451            | 32        | 0.22%   |
| ASUS PRIME A320M-K            | 31        | 0.21%   |
| Intel H61                     | 30        | 0.21%   |
| Dell Latitude 3310            | 29        | 0.2%    |
| Dell OptiPlex 9020            | 28        | 0.19%   |
| Gigabyte H410M H V3           | 27        | 0.19%   |
| HP Pavilion dv6               | 26        | 0.18%   |
| HP EliteDesk 800 G1 SFF       | 25        | 0.17%   |
| Dell OptiPlex 3020            | 25        | 0.17%   |
| Toshiba dynabook T653/46JR    | 24        | 0.16%   |
| Gigabyte 970A-DS3P            | 24        | 0.16%   |
| MSI MS-7817                   | 23        | 0.16%   |
| Gigabyte B450M DS3H           | 23        | 0.16%   |
| Dell Latitude E6430           | 23        | 0.16%   |
| MSI MS-7721                   | 22        | 0.15%   |
| HP Compaq Pro 6300 SFF        | 22        | 0.15%   |
| Sony VGN-FZ31Z                | 21        | 0.14%   |
| MSI MS-7C37                   | 21        | 0.14%   |
| MSI MS-7C02                   | 21        | 0.14%   |
| ASUS TUF Gaming X570-PLUS     | 21        | 0.14%   |
| ASUS SABERTOOTH Z77           | 21        | 0.14%   |
| ASUS PRIME B450M-A            | 21        | 0.14%   |
| HP Pavilion 15                | 20        | 0.14%   |
| Gigabyte A320M-S2H            | 20        | 0.14%   |
| Dell OptiPlex 790             | 20        | 0.14%   |
| ASUS M5A78L-M/USB3            | 20        | 0.14%   |
| MSI MS-7C91                   | 19        | 0.13%   |
| Dell Latitude E6410           | 19        | 0.13%   |
| Dell Inspiron 15-3567         | 19        | 0.13%   |
| Lenovo IdeaPad 3 15ADA05 81W1 | 18        | 0.12%   |
| HP Compaq 8200 Elite SFF PC   | 18        | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 682       | 4.67%   |
| Lenovo ThinkPad       | 597       | 4.09%   |
| Dell Latitude         | 570       | 3.91%   |
| Lenovo IdeaPad        | 427       | 2.93%   |
| Dell Inspiron         | 385       | 2.64%   |
| Dell OptiPlex         | 377       | 2.58%   |
| HP Pavilion           | 310       | 2.12%   |
| ASUS PRIME            | 307       | 2.1%    |
| HP Compaq             | 299       | 2.05%   |
| Toshiba Satellite     | 261       | 1.79%   |
| HP Laptop             | 190       | 1.3%    |
| Lenovo ThinkCentre    | 184       | 1.26%   |
| HP EliteBook          | 156       | 1.07%   |
| ASUS VivoBook         | 156       | 1.07%   |
| HP ProBook            | 139       | 0.95%   |
| ASUS ROG              | 137       | 0.94%   |
| ASUS All              | 137       | 0.94%   |
| Unknown               | 130       | 0.89%   |
| ASUS UX31E            | 125       | 0.86%   |
| ASUS TUF              | 123       | 0.84%   |
| Dell Precision        | 105       | 0.72%   |
| HP EliteDesk          | 96        | 0.66%   |
| Dell Vostro           | 92        | 0.63%   |
| Fujitsu ESPRIMO       | 83        | 0.57%   |
| HP ProDesk            | 75        | 0.51%   |
| Fujitsu LIFEBOOK      | 73        | 0.5%    |
| Dell XPS              | 70        | 0.48%   |
| ASUS M5A78L-M         | 70        | 0.48%   |
| HP Notebook           | 69        | 0.47%   |
| Lenovo IdeaCentre     | 62        | 0.42%   |
| Lenovo Yoga           | 55        | 0.38%   |
| Gigabyte B450M        | 55        | 0.38%   |
| Acer Veriton          | 53        | 0.36%   |
| Packard Bell EasyNote | 51        | 0.35%   |
| Toshiba dynabook      | 46        | 0.32%   |
| ASUS P8H61-M          | 46        | 0.32%   |
| Acer TravelMate       | 45        | 0.31%   |
| Acer Nitro            | 42        | 0.29%   |
| ASUS SABERTOOTH       | 40        | 0.27%   |
| Acer Extensa          | 39        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 1427      | 9.78%   |
| 2011    | 1376      | 9.43%   |
| 2013    | 1179      | 8.08%   |
| 2018    | 1080      | 7.4%    |
| 2019    | 1021      | 7%      |
| 2014    | 986       | 6.76%   |
| 2020    | 985       | 6.75%   |
| 2010    | 934       | 6.4%    |
| 2021    | 876       | 6%      |
| 2017    | 818       | 5.61%   |
| 2015    | 745       | 5.11%   |
| 2008    | 732       | 5.02%   |
| 2016    | 716       | 4.91%   |
| 2009    | 716       | 4.91%   |
| 2007    | 457       | 3.13%   |
| 2022    | 284       | 1.95%   |
| 2006    | 168       | 1.15%   |
| 2023    | 49        | 0.34%   |
| 2005    | 26        | 0.18%   |
| 2004    | 8         | 0.05%   |
| Unknown | 8         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6989      | 47.9%   |
| Desktop        | 6795      | 46.57%  |
| Convertible    | 252       | 1.73%   |
| All in one     | 233       | 1.6%    |
| Mini pc        | 221       | 1.51%   |
| Tablet         | 61        | 0.42%   |
| Server         | 39        | 0.27%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 14591     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 14553     | 99.73%  |
| Yes  | 39        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3915      | 26.56%  |
| 3.01-4.0        | 3879      | 26.32%  |
| 8.01-16.0       | 2657      | 18.03%  |
| 16.01-24.0      | 2274      | 15.43%  |
| 32.01-64.0      | 862       | 5.85%   |
| 1.01-2.0        | 521       | 3.54%   |
| 2.01-3.0        | 218       | 1.48%   |
| 24.01-32.0      | 192       | 1.3%    |
| 64.01-256.0     | 185       | 1.26%   |
| 0.51-1.0        | 26        | 0.18%   |
| More than 256.0 | 8         | 0.05%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 10839     | 71.56%  |
| 2.01-3.0   | 1959      | 12.93%  |
| 0.51-1.0   | 1719      | 11.35%  |
| 3.01-4.0   | 273       | 1.8%    |
| 0.01-0.5   | 245       | 1.62%   |
| 4.01-8.0   | 87        | 0.57%   |
| 8.01-16.0  | 20        | 0.13%   |
| 16.01-24.0 | 2         | 0.01%   |
| 32.01-64.0 | 1         | 0.01%   |
| Unknown    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 8671      | 58.45%  |
| 2      | 3630      | 24.47%  |
| 3      | 1229      | 8.28%   |
| 4      | 592       | 3.99%   |
| 0      | 250       | 1.69%   |
| 5      | 249       | 1.68%   |
| 6      | 105       | 0.71%   |
| 7      | 48        | 0.32%   |
| 8      | 31        | 0.21%   |
| 9      | 9         | 0.06%   |
| 10     | 6         | 0.04%   |
| 12     | 4         | 0.03%   |
| 11     | 4         | 0.03%   |
| 13     | 3         | 0.02%   |
| 15     | 2         | 0.01%   |
| 25     | 1         | 0.01%   |
| 18     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7554      | 51.52%  |
| No        | 7109      | 48.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 13292     | 91.09%  |
| No        | 1300      | 8.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10099     | 68.95%  |
| No        | 4547      | 31.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7372      | 50.26%  |
| Yes       | 7297      | 49.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1787      | 12.23%  |
| Germany     | 1636      | 11.19%  |
| France      | 1041      | 7.12%   |
| Russia      | 1029      | 7.04%   |
| Brazil      | 992       | 6.79%   |
| Poland      | 762       | 5.21%   |
| Italy       | 681       | 4.66%   |
| UK          | 504       | 3.45%   |
| Spain       | 474       | 3.24%   |
| Canada      | 414       | 2.83%   |
| Netherlands | 339       | 2.32%   |
| Czechia     | 314       | 2.15%   |
| Mexico      | 244       | 1.67%   |
| Australia   | 229       | 1.57%   |
| Japan       | 220       | 1.51%   |
| India       | 212       | 1.45%   |
| Hungary     | 162       | 1.11%   |
| Finland     | 154       | 1.05%   |
| Romania     | 144       | 0.99%   |
| Argentina   | 144       | 0.99%   |
| Ukraine     | 142       | 0.97%   |
| Austria     | 142       | 0.97%   |
| Portugal    | 134       | 0.92%   |
| Belgium     | 134       | 0.92%   |
| Indonesia   | 131       | 0.9%    |
| Switzerland | 129       | 0.88%   |
| Sweden      | 115       | 0.79%   |
| Turkey      | 97        | 0.66%   |
| Greece      | 92        | 0.63%   |
| Slovakia    | 90        | 0.62%   |
| Colombia    | 83        | 0.57%   |
| Serbia      | 80        | 0.55%   |
| Bulgaria    | 78        | 0.53%   |
| Chile       | 72        | 0.49%   |
| China       | 67        | 0.46%   |
| Norway      | 64        | 0.44%   |
| Denmark     | 61        | 0.42%   |
| Venezuela   | 55        | 0.38%   |
| Malaysia    | 55        | 0.38%   |
| Peru        | 53        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 196       | 1.29%   |
| Prague           | 153       | 1.01%   |
| Schagen          | 137       | 0.9%    |
| Warsaw           | 129       | 0.85%   |
| Berlin           | 122       | 0.8%    |
| Paris            | 114       | 0.75%   |
| Milan            | 100       | 0.66%   |
| Sao Paulo        | 96        | 0.63%   |
| St Petersburg    | 84        | 0.55%   |
| Vienna           | 73        | 0.48%   |
| Rio de Janeiro   | 73        | 0.48%   |
| Rome             | 69        | 0.45%   |
| Munich           | 67        | 0.44%   |
| Krakow           | 66        | 0.44%   |
| Mexico City      | 62        | 0.41%   |
| Helsinki         | 61        | 0.4%    |
| Madrid           | 57        | 0.38%   |
| Hamburg          | 57        | 0.38%   |
| Sydney           | 52        | 0.34%   |
| Melbourne        | 50        | 0.33%   |
| Budapest         | 45        | 0.3%    |
| Athens           | 43        | 0.28%   |
| Brisbane         | 39        | 0.26%   |
| Montreal         | 37        | 0.24%   |
| Barcelona        | 37        | 0.24%   |
| Belgrade         | 36        | 0.24%   |
| Poznan           | 34        | 0.22%   |
| Jakarta          | 34        | 0.22%   |
| Cologne          | 34        | 0.22%   |
| Yekaterinburg    | 33        | 0.22%   |
| Krasnodar        | 33        | 0.22%   |
| Buenos Aires     | 33        | 0.22%   |
| Bengaluru        | 33        | 0.22%   |
| Stuttgart        | 32        | 0.21%   |
| Lima             | 32        | 0.21%   |
| Bucharest        | 32        | 0.21%   |
| Wroclaw          | 31        | 0.2%    |
| Nizhniy Novgorod | 31        | 0.2%    |
| Istanbul         | 31        | 0.2%    |
| Curitiba         | 30        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3702      | 4795   | 17.29%  |
| Seagate             | 3332      | 4266   | 15.56%  |
| Samsung Electronics | 2589      | 3393   | 12.09%  |
| Toshiba             | 1497      | 1710   | 6.99%   |
| Kingston            | 1312      | 1512   | 6.13%   |
| Crucial             | 951       | 1146   | 4.44%   |
| SanDisk             | 942       | 1068   | 4.4%    |
| Hitachi             | 841       | 930    | 3.93%   |
| Unknown             | 580       | 667    | 2.71%   |
| A-DATA Technology   | 435       | 489    | 2.03%   |
| HGST                | 349       | 404    | 1.63%   |
| SK hynix            | 330       | 356    | 1.54%   |
| Intel               | 304       | 356    | 1.42%   |
| China               | 293       | 320    | 1.37%   |
| Micron Technology   | 185       | 203    | 0.86%   |
| PNY                 | 183       | 213    | 0.85%   |
| SPCC                | 182       | 208    | 0.85%   |
| GOODRAM             | 152       | 174    | 0.71%   |
| Patriot             | 151       | 164    | 0.71%   |
| Intenso             | 150       | 168    | 0.7%    |
| Maxtor              | 115       | 139    | 0.54%   |
| JMicron Technology  | 114       | 119    | 0.53%   |
| Transcend           | 106       | 113    | 0.5%    |
| Phison              | 104       | 128    | 0.49%   |
| Apple               | 104       | 116    | 0.49%   |
| Unknown             | 103       | 109    | 0.48%   |
| Apacer              | 96        | 105    | 0.45%   |
| OCZ                 | 86        | 92     | 0.4%    |
| Fujitsu             | 86        | 90     | 0.4%    |
| KIOXIA              | 81        | 88     | 0.38%   |
| LITEON              | 77        | 79     | 0.36%   |
| Netac               | 76        | 85     | 0.35%   |
| Gigabyte Technology | 73        | 81     | 0.34%   |
| Corsair             | 70        | 77     | 0.33%   |
| Team                | 66        | 68     | 0.31%   |
| Silicon Motion      | 66        | 74     | 0.31%   |
| Hewlett-Packard     | 62        | 75     | 0.29%   |
| KingSpec            | 61        | 62     | 0.28%   |
| ASMT                | 58        | 66     | 0.27%   |
| Lexar               | 49        | 50     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 291       | 1.24%   |
| Seagate ST500DM002-1BD142 500GB     | 225       | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB      | 180       | 0.77%   |
| Kingston SA400S37480G 480GB SSD     | 160       | 0.68%   |
| Seagate ST500LT012-1DG142 500GB     | 152       | 0.65%   |
| Toshiba DT01ACA100 1TB              | 145       | 0.62%   |
| Samsung SSD 860 EVO 500GB           | 143       | 0.61%   |
| Kingston SA400S37120G 120GB SSD     | 138       | 0.59%   |
| Toshiba MQ01ABF050 500GB            | 134       | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 131       | 0.56%   |
| Unknown SD/MMC/MS PRO 1GB           | 130       | 0.55%   |
| Crucial CT240BX500SSD1 240GB        | 130       | 0.55%   |
| Crucial CT500MX500SSD1 500GB        | 129       | 0.55%   |
| Toshiba MQ01ABD100 1TB              | 126       | 0.54%   |
| SanDisk SSD U100 256GB              | 125       | 0.53%   |
| Kingston SV300S37A120G 120GB SSD    | 120       | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB      | 118       | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB      | 117       | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB            | 109       | 0.46%   |
| Samsung SSD 850 EVO 250GB           | 108       | 0.46%   |
| Unknown                             | 103       | 0.44%   |
| Samsung SSD 860 EVO 250GB           | 101       | 0.43%   |
| Toshiba DT01ACA050 500GB            | 98        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB         | 98        | 0.42%   |
| Seagate ST3500418AS 500GB           | 95        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 92        | 0.39%   |
| Toshiba MQ04ABF100 1TB              | 90        | 0.38%   |
| Samsung SSD 850 EVO 500GB           | 89        | 0.38%   |
| Seagate ST9500325AS 500GB           | 84        | 0.36%   |
| Crucial CT480BX500SSD1 480GB        | 82        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB      | 80        | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB      | 75        | 0.32%   |
| HGST HTS721010A9E630 1TB            | 72        | 0.31%   |
| Toshiba HDWD110 1TB                 | 70        | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 66        | 0.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 65        | 0.28%   |
| HGST HTS545050A7E680 500GB          | 65        | 0.28%   |
| Seagate ST1000DM003-1CH162 1TB      | 64        | 0.27%   |
| Samsung SSD 860 EVO 1TB             | 64        | 0.27%   |
| JMicron Generic 1TB                 | 64        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3280      | 4176   | 33.23%  |
| WDC                 | 2979      | 3783   | 30.18%  |
| Toshiba             | 1308      | 1491   | 13.25%  |
| Hitachi             | 841       | 930    | 8.52%   |
| Samsung Electronics | 522       | 607    | 5.29%   |
| HGST                | 349       | 404    | 3.54%   |
| Unknown             | 134       | 141    | 1.36%   |
| Maxtor              | 111       | 135    | 1.12%   |
| Fujitsu             | 85        | 89     | 0.86%   |
| Apple               | 48        | 49     | 0.49%   |
| SABRENT             | 30        | 36     | 0.3%    |
| External            | 19        | 19     | 0.19%   |
| Hewlett-Packard     | 17        | 22     | 0.17%   |
| USB3.0              | 13        | 13     | 0.13%   |
| Intenso             | 12        | 12     | 0.12%   |
| WD MediaMax         | 9         | 14     | 0.09%   |
| USB                 | 8         | 9      | 0.08%   |
| ExcelStor           | 8         | 8      | 0.08%   |
| ASMT                | 8         | 15     | 0.08%   |
| IBM/Hitachi         | 7         | 8      | 0.07%   |
| SAGE                | 6         | 6      | 0.06%   |
| HGST HTS            | 6         | 6      | 0.06%   |
| SSK                 | 5         | 7      | 0.05%   |
| QUANTUM             | 5         | 5      | 0.05%   |
| Initio              | 5         | 5      | 0.05%   |
| Inateck             | 5         | 5      | 0.05%   |
| HPE                 | 5         | 6      | 0.05%   |
| ASMedia             | 4         | 4      | 0.04%   |
| Unknown             | 4         | 4      | 0.04%   |
| StoreJet            | 3         | 3      | 0.03%   |
| Min Yi U            | 3         | 3      | 0.03%   |
| Magnetic Data       | 3         | 3      | 0.03%   |
| JMicron Technology  | 3         | 3      | 0.03%   |
| China               | 3         | 4      | 0.03%   |
| RSH-319             | 2         | 2      | 0.02%   |
| MDT                 | 2         | 2      | 0.02%   |
| LaCie               | 2         | 2      | 0.02%   |
| KESU                | 2         | 3      | 0.02%   |
| WALRAM              | 1         | 1      | 0.01%   |
| USB 3.0             | 1         | 2      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1359      | 1710   | 16.81%  |
| Kingston            | 1084      | 1235   | 13.41%  |
| Crucial             | 799       | 944    | 9.88%   |
| SanDisk             | 797       | 896    | 9.86%   |
| WDC                 | 481       | 552    | 5.95%   |
| A-DATA Technology   | 357       | 390    | 4.42%   |
| China               | 290       | 316    | 3.59%   |
| PNY                 | 160       | 184    | 1.98%   |
| SPCC                | 148       | 165    | 1.83%   |
| GOODRAM             | 148       | 167    | 1.83%   |
| Intel               | 137       | 151    | 1.69%   |
| Patriot             | 135       | 148    | 1.67%   |
| Toshiba             | 132       | 145    | 1.63%   |
| Intenso             | 130       | 146    | 1.61%   |
| Micron Technology   | 114       | 125    | 1.41%   |
| SK hynix            | 108       | 116    | 1.34%   |
| Transcend           | 94        | 100    | 1.16%   |
| OCZ                 | 86        | 92     | 1.06%   |
| Apacer              | 84        | 89     | 1.04%   |
| JMicron Technology  | 74        | 78     | 0.92%   |
| LITEON              | 69        | 71     | 0.85%   |
| Netac               | 63        | 72     | 0.78%   |
| KingSpec            | 58        | 59     | 0.72%   |
| Team                | 55        | 56     | 0.68%   |
| Unknown             | 53        | 55     | 0.66%   |
| ASMT                | 45        | 46     | 0.56%   |
| Gigabyte Technology | 44        | 46     | 0.54%   |
| Apple               | 41        | 42     | 0.51%   |
| Lexar               | 36        | 37     | 0.45%   |
| Corsair             | 36        | 40     | 0.45%   |
| LITEONIT            | 32        | 34     | 0.4%    |
| Hewlett-Packard     | 31        | 35     | 0.38%   |
| Unknown             | 28        | 29     | 0.35%   |
| KIOXIA-EXCERIA      | 27        | 28     | 0.33%   |
| Seagate             | 26        | 31     | 0.32%   |
| Plextor             | 25        | 27     | 0.31%   |
| Verbatim            | 24        | 26     | 0.3%    |
| KingFast            | 24        | 26     | 0.3%    |
| Leven               | 23        | 24     | 0.28%   |
| XrayDisk            | 22        | 22     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 8300      | 12054  | 44.41%  |
| SSD     | 6811      | 9199   | 36.44%  |
| NVMe    | 2881      | 3701   | 15.42%  |
| MMC     | 481       | 540    | 2.57%   |
| Unknown | 216       | 266    | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12485     | 20276  | 74.07%  |
| NVMe | 2874      | 3669   | 17.05%  |
| SAS  | 1016      | 1275   | 6.03%   |
| MMC  | 481       | 540    | 2.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 9878      | 13655  | 63.09%  |
| 0.51-1.0        | 4155      | 5419   | 26.54%  |
| 1.01-2.0        | 1027      | 1358   | 6.56%   |
| 2.01-3.0        | 206       | 268    | 1.32%   |
| 3.01-4.0        | 205       | 292    | 1.31%   |
| 4.01-10.0       | 146       | 214    | 0.93%   |
| 10.01-20.0      | 39        | 45     | 0.25%   |
| More than 100.0 | 1         | 2      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7212      | 47.02%  |
| 101-250        | 2473      | 16.12%  |
| 251-500        | 1595      | 10.4%   |
| Unknown        | 1309      | 8.53%   |
| 501-1000       | 897       | 5.85%   |
| 51-100         | 742       | 4.84%   |
| 21-50          | 623       | 4.06%   |
| 1001-2000      | 299       | 1.95%   |
| 2001-3000      | 99        | 0.65%   |
| More than 3000 | 90        | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12003     | 79.64%  |
| Unknown        | 1309      | 8.68%   |
| 21-50          | 517       | 3.43%   |
| 101-250        | 374       | 2.48%   |
| 51-100         | 355       | 2.36%   |
| 251-500        | 235       | 1.56%   |
| 501-1000       | 162       | 1.07%   |
| 1001-2000      | 70        | 0.46%   |
| More than 3000 | 25        | 0.17%   |
| 2001-3000      | 21        | 0.14%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 125       | 126    | 2.83%   |
| Seagate ST500DM002-1BD142 500GB     | 98        | 107    | 2.22%   |
| Seagate ST9500325AS 500GB           | 66        | 70     | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 49        | 54     | 1.11%   |
| Seagate ST500LT012-1DG142 500GB     | 47        | 49     | 1.06%   |
| Seagate ST3500418AS 500GB           | 44        | 50     | 1%      |
| HGST HTS545050A7E680 500GB          | 42        | 43     | 0.95%   |
| Seagate ST500LT012-9WS142 500GB     | 41        | 43     | 0.93%   |
| Toshiba MQ01ABD075 752GB            | 34        | 35     | 0.77%   |
| Kingston SV300S37A120G 120GB SSD    | 34        | 36     | 0.77%   |
| Toshiba MQ01ABF050 500GB            | 33        | 34     | 0.75%   |
| Seagate ST9320325AS 320GB           | 31        | 31     | 0.7%    |
| HGST HTS541010A9E680 1TB            | 31        | 33     | 0.7%    |
| Toshiba MQ01ABD100 1TB              | 28        | 28     | 0.63%   |
| Toshiba DT01ACA100 1TB              | 24        | 26     | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB      | 24        | 25     | 0.54%   |
| HGST HTS721010A9E630 1TB            | 24        | 31     | 0.54%   |
| Toshiba MQ01ABD050 500GB            | 22        | 22     | 0.5%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 21        | 22     | 0.48%   |
| WDC WD5000AAKX-001CA0 500GB         | 21        | 24     | 0.48%   |
| Seagate ST31000528AS 1TB            | 21        | 22     | 0.48%   |
| Seagate ST31000524AS 1TB            | 21        | 21     | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB      | 21        | 24     | 0.48%   |
| Hitachi HTS545050A7E380 500GB       | 21        | 23     | 0.48%   |
| Hitachi HTS543232A7A384 320GB       | 21        | 22     | 0.48%   |
| Toshiba DT01ACA050 500GB            | 20        | 22     | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB     | 20        | 20     | 0.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 20        | 20     | 0.45%   |
| HGST HTS545050A7E380 500GB          | 19        | 21     | 0.43%   |
| Crucial CT240M500SSD1 240GB         | 19        | 20     | 0.43%   |
| Seagate ST3500413AS 500GB           | 18        | 20     | 0.41%   |
| Samsung Electronics HD322HJ 320GB   | 18        | 20     | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB      | 17        | 17     | 0.38%   |
| Seagate ST1000DM003-9YN162 1TB      | 17        | 18     | 0.38%   |
| Samsung Electronics HD161HJ 160GB   | 17        | 17     | 0.38%   |
| Hitachi HDS721050CLA362 500GB       | 17        | 20     | 0.38%   |
| HGST HTS725050A7E630 500GB          | 17        | 18     | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB            | 16        | 17     | 0.36%   |
| Seagate ST3320418AS 320GB           | 16        | 18     | 0.36%   |
| Samsung Electronics HD502HJ 500GB   | 16        | 16     | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1163      | 1301   | 27.12%  |
| WDC                 | 960       | 1105   | 22.38%  |
| Hitachi             | 422       | 464    | 9.84%   |
| Toshiba             | 387       | 402    | 9.02%   |
| Samsung Electronics | 314       | 351    | 7.32%   |
| SanDisk             | 192       | 197    | 4.48%   |
| HGST                | 164       | 180    | 3.82%   |
| Kingston            | 109       | 116    | 2.54%   |
| Maxtor              | 73        | 83     | 1.7%    |
| Crucial             | 56        | 60     | 1.31%   |
| Intel               | 48        | 52     | 1.12%   |
| A-DATA Technology   | 44        | 48     | 1.03%   |
| China               | 38        | 38     | 0.89%   |
| SK hynix            | 33        | 35     | 0.77%   |
| Fujitsu             | 32        | 34     | 0.75%   |
| Micron Technology   | 22        | 24     | 0.51%   |
| OCZ                 | 15        | 15     | 0.35%   |
| SPCC                | 13        | 13     | 0.3%    |
| Hewlett-Packard     | 11        | 11     | 0.26%   |
| Apple               | 11        | 11     | 0.26%   |
| Netac               | 10        | 10     | 0.23%   |
| LITEON              | 10        | 10     | 0.23%   |
| ASMT                | 10        | 11     | 0.23%   |
| KingSpec            | 8         | 8      | 0.19%   |
| GOODRAM             | 8         | 8      | 0.19%   |
| Unknown             | 8         | 8      | 0.19%   |
| Intenso             | 7         | 8      | 0.16%   |
| Corsair             | 7         | 8      | 0.16%   |
| IBM/Hitachi         | 5         | 6      | 0.12%   |
| Plextor             | 4         | 4      | 0.09%   |
| Patriot             | 4         | 4      | 0.09%   |
| JMicron Technology  | 4         | 4      | 0.09%   |
| ExcelStor           | 4         | 4      | 0.09%   |
| XPG                 | 3         | 3      | 0.07%   |
| WD MediaMax         | 3         | 3      | 0.07%   |
| Transcend           | 3         | 4      | 0.07%   |
| PNY                 | 3         | 4      | 0.07%   |
| Initio              | 3         | 3      | 0.07%   |
| Dogfish             | 3         | 3      | 0.07%   |
| ASMedia             | 3         | 3      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1162      | 1300   | 33.67%  |
| WDC                 | 913       | 1048   | 26.46%  |
| Hitachi             | 422       | 464    | 12.23%  |
| Toshiba             | 380       | 395    | 11.01%  |
| Samsung Electronics | 256       | 286    | 7.42%   |
| HGST                | 164       | 180    | 4.75%   |
| Maxtor              | 73        | 83     | 2.12%   |
| Fujitsu             | 32        | 34     | 0.93%   |
| Hewlett-Packard     | 8         | 8      | 0.23%   |
| Apple               | 7         | 7      | 0.2%    |
| IBM/Hitachi         | 5         | 6      | 0.14%   |
| ExcelStor           | 4         | 4      | 0.12%   |
| WD MediaMax         | 3         | 3      | 0.09%   |
| Initio              | 3         | 3      | 0.09%   |
| ASMT                | 3         | 4      | 0.09%   |
| USB3.0              | 2         | 2      | 0.06%   |
| QUANTUM             | 2         | 2      | 0.06%   |
| HPE                 | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| RSH-339             | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| IB                  | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3187      | 3841   | 79.26%  |
| SSD     | 775       | 828    | 19.27%  |
| NVMe    | 57        | 61     | 1.42%   |
| Unknown | 2         | 2      | 0.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB         | 4         | 4      | 3.48%   |
| Apple HDD HTS541010A9E662 1TB     | 4         | 4      | 3.48%   |
| Seagate ST3500418AS 500GB         | 3         | 5      | 2.61%   |
| Samsung Electronics HD502HJ 500GB | 3         | 3      | 2.61%   |
| Samsung Electronics HD103SJ 1TB   | 3         | 3      | 2.61%   |
| WDC WD800JD-00LSA0 80GB           | 2         | 3      | 1.74%   |
| WDC WD3200BEVT-11ZCT0 320GB       | 2         | 2      | 1.74%   |
| WDC WD2500BEVS-22UST0 250GB       | 2         | 2      | 1.74%   |
| WDC WD20EZRX-00D8PB0 2TB          | 2         | 2      | 1.74%   |
| Toshiba MQ01ABD100 1TB            | 2         | 2      | 1.74%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 1.74%   |
| Seagate ST31000528AS 1TB          | 2         | 2      | 1.74%   |
| Samsung Electronics HD103UJ 1TB   | 2         | 4      | 1.74%   |
| Hitachi HTS545050A7E380 500GB     | 2         | 2      | 1.74%   |
| Crucial CT500P2SSD8 500GB         | 2         | 2      | 1.74%   |
| WDC WD800JD-75MSA3 80GB           | 1         | 1      | 0.87%   |
| WDC WD800JD-00MSA1 80GB           | 1         | 1      | 0.87%   |
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 0.87%   |
| WDC WD7500BPVT-22HXZT3 752GB      | 1         | 1      | 0.87%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB  | 1         | 1      | 0.87%   |
| WDC WD5000LPLX-75ZNTT0 500GB      | 1         | 1      | 0.87%   |
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 0.87%   |
| WDC WD5000BEVT-22ZAT0 500GB       | 1         | 1      | 0.87%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 1      | 0.87%   |
| WDC WD5000AAKS-00C8A0 500GB       | 1         | 1      | 0.87%   |
| WDC WD3200BUCT-63TWBY0 320GB      | 1         | 1      | 0.87%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 0.87%   |
| WDC WD3200BPVT-00JJ5T0 320GB      | 1         | 1      | 0.87%   |
| WDC WD3200BEKT-60KA9T0 320GB      | 1         | 1      | 0.87%   |
| WDC WD3200AAJS-60Z0A0 320GB       | 1         | 1      | 0.87%   |
| WDC WD2500BEVT-60ZCT1 250GB       | 1         | 1      | 0.87%   |
| WDC WD2500BEVT-35A23T0 250GB      | 1         | 1      | 0.87%   |
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 0.87%   |
| WDC WD1600YS-23SHB0 160GB         | 1         | 1      | 0.87%   |
| WDC WD1600BEVT-75A23T0 160GB      | 1         | 1      | 0.87%   |
| WDC WD1600AAJS-00YZCA0 160GB      | 1         | 1      | 0.87%   |
| WDC WD10JPVX-60JC3T0 1TB          | 1         | 1      | 0.87%   |
| WDC WD10JPVT-75A1YT0 1TB          | 1         | 1      | 0.87%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1         | 1      | 0.87%   |
| WDC WD10EARX-22N0YB0 1TB          | 1         | 1      | 0.87%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 36     | 30.43%  |
| Seagate             | 22        | 24     | 19.13%  |
| Samsung Electronics | 22        | 24     | 19.13%  |
| Toshiba             | 10        | 11     | 8.7%    |
| Hitachi             | 10        | 10     | 8.7%    |
| Apple               | 5         | 5      | 4.35%   |
| HGST                | 2         | 2      | 1.74%   |
| Crucial             | 2         | 2      | 1.74%   |
| TPH00800640GB       | 1         | 1      | 0.87%   |
| SK hynix            | 1         | 1      | 0.87%   |
| Maxtor              | 1         | 1      | 0.87%   |
| Kingston            | 1         | 1      | 0.87%   |
| Intel               | 1         | 1      | 0.87%   |
| GOODRAM             | 1         | 1      | 0.87%   |
| External            | 1         | 1      | 0.87%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 11368     | 18859  | 66.83%  |
| Malfunc  | 3928      | 4732   | 23.09%  |
| Detected | 1601      | 2048   | 9.41%   |
| Failed   | 113       | 121    | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 10243     | 57.92%  |
| AMD                              | 3249      | 18.37%  |
| Samsung Electronics              | 920       | 5.2%    |
| SanDisk                          | 490       | 2.77%   |
| Nvidia                           | 306       | 1.73%   |
| ASMedia Technology               | 270       | 1.53%   |
| Kingston Technology Company      | 262       | 1.48%   |
| Phison Electronics               | 258       | 1.46%   |
| JMicron Technology               | 249       | 1.41%   |
| SK hynix                         | 204       | 1.15%   |
| Marvell Technology Group         | 201       | 1.14%   |
| Micron/Crucial Technology        | 164       | 0.93%   |
| Silicon Motion                   | 153       | 0.87%   |
| KIOXIA                           | 89        | 0.5%    |
| Micron Technology                | 83        | 0.47%   |
| ADATA Technology                 | 74        | 0.42%   |
| Toshiba America Info Systems     | 70        | 0.4%    |
| VIA Technologies                 | 62        | 0.35%   |
| Realtek Semiconductor            | 52        | 0.29%   |
| Solid State Storage Technology   | 38        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 34        | 0.19%   |
| Union Memory (Shenzhen)          | 32        | 0.18%   |
| Seagate Technology               | 23        | 0.13%   |
| Silicon Image                    | 18        | 0.1%    |
| Broadcom / LSI                   | 18        | 0.1%    |
| LSI Logic / Symbios Logic        | 14        | 0.08%   |
| Lite-On Technology               | 13        | 0.07%   |
| Silicon Integrated Systems [SiS] | 12        | 0.07%   |
| Shenzhen Longsys Electronics     | 12        | 0.07%   |
| Apple                            | 11        | 0.06%   |
| Integrated Technology Express    | 10        | 0.06%   |
| Adaptec                          | 8         | 0.05%   |
| Biwin Storage Technology         | 7         | 0.04%   |
| Netac Technology                 | 6         | 0.03%   |
| Promise Technology               | 5         | 0.03%   |
| Lenovo                           | 5         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 4         | 0.02%   |
| INNOGRIT                         | 4         | 0.02%   |
| Hewlett-Packard                  | 4         | 0.02%   |
| Yangtze Memory Technologies      | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1995      | 9.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 744       | 3.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 731       | 3.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 651       | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 618       | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 474       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 452       | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 431       | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 422       | 2%      |
| AMD 400 Series Chipset SATA Controller                                                  | 417       | 1.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 415       | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 415       | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 392       | 1.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 349       | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 345       | 1.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 331       | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 303       | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 296       | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 293       | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 278       | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 278       | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 266       | 1.26%   |
| Samsung NVMe SSD Controller 980                                                         | 247       | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 245       | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 244       | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 240       | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 233       | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 228       | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 227       | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 213       | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 204       | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 203       | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 202       | 0.96%   |
| AMD FCH SATA Controller D                                                               | 156       | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 150       | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 146       | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 145       | 0.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 135       | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 132       | 0.63%   |
| Nvidia MCP61 SATA Controller                                                            | 130       | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 11496     | 63.7%   |
| NVMe | 2867      | 15.89%  |
| IDE  | 2753      | 15.25%  |
| RAID | 884       | 4.9%    |
| SAS  | 28        | 0.16%   |
| SCSI | 19        | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 10834     | 74.25%  |
| AMD    | 3756      | 25.74%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 125       | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 115       | 0.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 108       | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 100       | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 99        | 0.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 90        | 0.62%   |
| AMD Ryzen 5 3600 6-Core Processor             | 90        | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 88        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 86        | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 85        | 0.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 80        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 79        | 0.54%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 78        | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 74        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 74        | 0.51%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 73        | 0.5%    |
| Intel Core i3-3220 CPU @ 3.30GHz              | 72        | 0.49%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 69        | 0.47%   |
| AMD FX-8350 Eight-Core Processor              | 69        | 0.47%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 68        | 0.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 65        | 0.44%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 65        | 0.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 64        | 0.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 64        | 0.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 63        | 0.43%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 63        | 0.43%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 63        | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 62        | 0.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 62        | 0.42%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 61        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 60        | 0.41%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 59        | 0.4%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 58        | 0.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 58        | 0.4%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 58        | 0.4%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 58        | 0.4%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 58        | 0.4%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 57        | 0.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 57        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3164      | 21.65%  |
| Intel Core i7           | 1748      | 11.96%  |
| Intel Core i3           | 1581      | 10.82%  |
| Intel Celeron           | 1030      | 7.05%   |
| Intel Core 2 Duo        | 910       | 6.23%   |
| AMD Ryzen 5             | 768       | 5.26%   |
| Intel Pentium           | 579       | 3.96%   |
| Other                   | 500       | 3.42%   |
| AMD Ryzen 7             | 475       | 3.25%   |
| AMD FX                  | 287       | 1.96%   |
| Intel Pentium Dual-Core | 281       | 1.92%   |
| AMD Ryzen 3             | 234       | 1.6%    |
| Intel Xeon              | 228       | 1.56%   |
| Intel Core 2 Quad       | 204       | 1.4%    |
| AMD A8                  | 180       | 1.23%   |
| AMD A6                  | 156       | 1.07%   |
| Intel Pentium Silver    | 139       | 0.95%   |
| AMD A4                  | 138       | 0.94%   |
| AMD Ryzen 9             | 127       | 0.87%   |
| AMD A10                 | 126       | 0.86%   |
| Intel Pentium Dual      | 118       | 0.81%   |
| Intel Core 2            | 108       | 0.74%   |
| Intel Atom              | 108       | 0.74%   |
| AMD Athlon II X2        | 103       | 0.7%    |
| AMD Athlon              | 100       | 0.68%   |
| AMD Phenom II X4        | 96        | 0.66%   |
| AMD E                   | 94        | 0.64%   |
| AMD Athlon 64 X2        | 92        | 0.63%   |
| AMD E1                  | 87        | 0.6%    |
| AMD E2                  | 49        | 0.34%   |
| AMD Athlon II X4        | 44        | 0.3%    |
| Intel Core i9           | 43        | 0.29%   |
| Intel Pentium Gold      | 40        | 0.27%   |
| Intel Genuine           | 39        | 0.27%   |
| AMD Ryzen 5 PRO         | 39        | 0.27%   |
| AMD Phenom II X6        | 38        | 0.26%   |
| AMD Phenom              | 34        | 0.23%   |
| Intel Pentium 4         | 32        | 0.22%   |
| AMD Sempron             | 31        | 0.21%   |
| AMD C-60                | 31        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7537      | 51.55%  |
| 4       | 4543      | 31.07%  |
| 6       | 1119      | 7.65%   |
| 8       | 664       | 4.54%   |
| 1       | 378       | 2.59%   |
| 3       | 121       | 0.83%   |
| 12      | 109       | 0.75%   |
| 16      | 57        | 0.39%   |
| 10      | 37        | 0.25%   |
| 14      | 36        | 0.25%   |
| 24      | 9         | 0.06%   |
| 28      | 3         | 0.02%   |
| 32      | 2         | 0.01%   |
| 20      | 2         | 0.01%   |
| 5       | 2         | 0.01%   |
| 128     | 1         | 0.01%   |
| 44      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 14539     | 99.64%  |
| 2      | 51        | 0.35%   |
| 16     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8170      | 55.9%   |
| 1       | 6383      | 43.67%  |
| 4       | 34        | 0.23%   |
| 8       | 19        | 0.13%   |
| 12      | 6         | 0.04%   |
| 16      | 1         | 0.01%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 14586     | 99.96%  |
| Unknown        | 6         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2644      | 17.54%  |
| 0x206a7    | 1141      | 7.57%   |
| 0x306a9    | 1024      | 6.79%   |
| 0x1067a    | 805       | 5.34%   |
| 0x306c3    | 783       | 5.19%   |
| 0x20655    | 329       | 2.18%   |
| 0x506e3    | 284       | 1.88%   |
| 0x40651    | 277       | 1.84%   |
| 0x08108109 | 255       | 1.69%   |
| 0x906ea    | 248       | 1.64%   |
| 0x6fd      | 246       | 1.63%   |
| 0x406e3    | 243       | 1.61%   |
| 0x08701021 | 235       | 1.56%   |
| 0x306d4    | 232       | 1.54%   |
| 0x806e9    | 227       | 1.51%   |
| 0x906e9    | 206       | 1.37%   |
| 0x10676    | 194       | 1.29%   |
| 0x806ea    | 191       | 1.27%   |
| 0x30678    | 181       | 1.2%    |
| 0x06001119 | 168       | 1.11%   |
| 0x010000c8 | 153       | 1.01%   |
| 0x806ec    | 144       | 0.96%   |
| 0x706a1    | 132       | 0.88%   |
| 0x0800820d | 132       | 0.88%   |
| 0x6fb      | 123       | 0.82%   |
| 0x0a50000c | 118       | 0.78%   |
| 0x706a8    | 117       | 0.78%   |
| 0x20652    | 113       | 0.75%   |
| 0x406c4    | 112       | 0.74%   |
| 0x06006705 | 107       | 0.71%   |
| 0x506c9    | 105       | 0.7%    |
| 0x806c1    | 104       | 0.69%   |
| 0x08101016 | 101       | 0.67%   |
| 0x06000822 | 95        | 0.63%   |
| 0x08600106 | 94        | 0.62%   |
| 0xa0653    | 92        | 0.61%   |
| 0x07030105 | 91        | 0.6%    |
| 0x0a50000d | 90        | 0.6%    |
| 0x106e5    | 89        | 0.59%   |
| 0x06003106 | 86        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1483      | 10.15%  |
| SandyBridge      | 1360      | 9.31%   |
| Haswell          | 1304      | 8.93%   |
| IvyBridge        | 1243      | 8.51%   |
| Penryn           | 1202      | 8.23%   |
| Skylake          | 703       | 4.81%   |
| Core             | 602       | 4.12%   |
| Westmere         | 545       | 3.73%   |
| Zen+             | 512       | 3.51%   |
| Zen 2            | 461       | 3.16%   |
| Silvermont       | 448       | 3.07%   |
| K10              | 438       | 3%      |
| Piledriver       | 431       | 2.95%   |
| Zen 3            | 361       | 2.47%   |
| Zen              | 333       | 2.28%   |
| Goldmont plus    | 313       | 2.14%   |
| Broadwell        | 308       | 2.11%   |
| CometLake        | 279       | 1.91%   |
| Excavator        | 228       | 1.56%   |
| Bobcat           | 195       | 1.34%   |
| Icelake          | 183       | 1.25%   |
| Unknown          | 178       | 1.22%   |
| TigerLake        | 175       | 1.2%    |
| K8 Hammer        | 167       | 1.14%   |
| Nehalem          | 150       | 1.03%   |
| Puma             | 138       | 0.94%   |
| Goldmont         | 131       | 0.9%    |
| Alderlake Hybrid | 119       | 0.81%   |
| Steamroller      | 108       | 0.74%   |
| Tremont          | 97        | 0.66%   |
| Jaguar           | 91        | 0.62%   |
| Bonnell          | 78        | 0.53%   |
| K10 Llano        | 74        | 0.51%   |
| NetBurst         | 68        | 0.47%   |
| Bulldozer        | 60        | 0.41%   |
| K8 & K10 hybrid  | 31        | 0.21%   |
| Gracemont        | 7         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8117      | 50.11%  |
| AMD                                          | 4024      | 24.84%  |
| Nvidia                                       | 4008      | 24.74%  |
| Matrox Electronics Systems                   | 19        | 0.12%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.05%   |
| ASPEED Technology                            | 7         | 0.04%   |
| VIA Technologies                             | 6         | 0.04%   |
| ATI Technologies                             | 3         | 0.02%   |
| Red Hat                                      | 2         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.01%   |
| Conexant Systems                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1075      | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 607       | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 400       | 2.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 382       | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 362       | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 353       | 2.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 325       | 1.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 274       | 1.64%   |
| Intel HD Graphics 620                                                                    | 270       | 1.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 268       | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 250       | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 248       | 1.49%   |
| Intel HD Graphics 5500                                                                   | 244       | 1.46%   |
| Intel HD Graphics 530                                                                    | 240       | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 236       | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 210       | 1.26%   |
| Intel UHD Graphics 620                                                                   | 201       | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 198       | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 184       | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 173       | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 173       | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 172       | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 162       | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 160       | 0.96%   |
| Intel HD Graphics 630                                                                    | 153       | 0.92%   |
| AMD Renoir                                                                               | 153       | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 150       | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 146       | 0.88%   |
| Nvidia GT218 [GeForce 210]                                                               | 137       | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 130       | 0.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 128       | 0.77%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 118       | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 112       | 0.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 107       | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 107       | 0.64%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 101       | 0.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 101       | 0.61%   |
| Intel JasperLake [UHD Graphics]                                                          | 99        | 0.59%   |
| Intel HD Graphics 500                                                                    | 99        | 0.59%   |
| AMD Lucienne                                                                             | 99        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 6442      | 43.88%  |
| 1 x AMD                                  | 3409      | 23.22%  |
| 1 x Nvidia                               | 2787      | 18.98%  |
| Intel + Nvidia                           | 1079      | 7.35%   |
| Intel + AMD                              | 278       | 1.89%   |
| 2 x Intel                                | 268       | 1.83%   |
| 2 x AMD                                  | 223       | 1.52%   |
| AMD + Nvidia                             | 119       | 0.81%   |
| 2 x Nvidia                               | 23        | 0.16%   |
| 1 x Matrox                               | 15        | 0.1%    |
| 1 x SiS                                  | 8         | 0.05%   |
| 1 x VIA                                  | 6         | 0.04%   |
| 1 x ASPEED                               | 6         | 0.04%   |
| 1 x Red Hat                              | 2         | 0.01%   |
| Nvidia + Matrox                          | 2         | 0.01%   |
| Intel + 2 x Nvidia                       | 2         | 0.01%   |
| Intel + AMD + 1 x Nvidia                 | 2         | 0.01%   |
| Other                                    | 1         | 0.01%   |
| 3 x AMD                                  | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox                  | 1         | 0.01%   |
| 2 x Intel + 1 x Nvidia                   | 1         | 0.01%   |
| 1 x S3 Graphics                          | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + XGI                             | 1         | 0.01%   |
| Nvidia + ASPEED                          | 1         | 0.01%   |
| Intel + Conexant Systems                 | 1         | 0.01%   |
| AMD + Matrox                             | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 14233     | 97.2%   |
| Unknown     | 312       | 2.13%   |
| Proprietary | 98        | 0.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7074      | 48.14%  |
| 0.01-0.5   | 2150      | 14.63%  |
| 1.01-2.0   | 2054      | 13.98%  |
| 0.51-1.0   | 1636      | 11.13%  |
| 3.01-4.0   | 803       | 5.46%   |
| 7.01-8.0   | 498       | 3.39%   |
| 5.01-6.0   | 272       | 1.85%   |
| 8.01-16.0  | 103       | 0.7%    |
| 2.01-3.0   | 89        | 0.61%   |
| 16.01-24.0 | 12        | 0.08%   |
| 4.01-5.0   | 5         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2093      | 14.2%   |
| AU Optronics            | 1567      | 10.63%  |
| LG Display              | 1250      | 8.48%   |
| BOE                     | 1056      | 7.17%   |
| Chimei Innolux          | 1033      | 7.01%   |
| Goldstar                | 903       | 6.13%   |
| Dell                    | 706       | 4.79%   |
| Hewlett-Packard         | 679       | 4.61%   |
| Acer                    | 595       | 4.04%   |
| Philips                 | 446       | 3.03%   |
| AOC                     | 432       | 2.93%   |
| BenQ                    | 345       | 2.34%   |
| Lenovo                  | 305       | 2.07%   |
| Ancor Communications    | 289       | 1.96%   |
| Chi Mei Optoelectronics | 260       | 1.76%   |
| ViewSonic               | 191       | 1.3%    |
| Apple                   | 186       | 1.26%   |
| Iiyama                  | 174       | 1.18%   |
| CPT                     | 147       | 1%      |
| Eizo                    | 124       | 0.84%   |
| ASUSTek Computer        | 124       | 0.84%   |
| Sharp                   | 118       | 0.8%    |
| LG Philips              | 108       | 0.73%   |
| Sony                    | 106       | 0.72%   |
| PANDA                   | 88        | 0.6%    |
| InfoVision              | 81        | 0.55%   |
| Fujitsu Siemens         | 71        | 0.48%   |
| NEC Computers           | 66        | 0.45%   |
| HannStar                | 57        | 0.39%   |
| Panasonic               | 49        | 0.33%   |
| Toshiba                 | 48        | 0.33%   |
| Unknown                 | 38        | 0.26%   |
| MSI                     | 37        | 0.25%   |
| Vizio                   | 34        | 0.23%   |
| Sceptre Tech            | 34        | 0.23%   |
| Medion                  | 32        | 0.22%   |
| Vestel Elektronik       | 30        | 0.2%    |
| Hitachi                 | 26        | 0.18%   |
| RTK                     | 21        | 0.14%   |
| InnoLux Display         | 20        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 125       | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 76        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 73        | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 69        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 61        | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 59        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 58        | 0.39%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 57        | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 52        | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 50        | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 50        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 40        | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 39        | 0.26%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 38        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 37        | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 37        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 36        | 0.24%   |
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 32        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 32        | 0.21%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 31        | 0.21%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 31        | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 31        | 0.21%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                            | 30        | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 30        | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 29        | 0.19%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 29        | 0.19%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 29        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 28        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 28        | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 26        | 0.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 26        | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 26        | 0.17%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 25        | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 24        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 24        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5803      | 40.1%   |
| 1366x768 (WXGA)    | 3593      | 24.83%  |
| 1600x900 (HD+)     | 846       | 5.85%   |
| 3840x2160 (4K)     | 740       | 5.11%   |
| 1280x1024 (SXGA)   | 619       | 4.28%   |
| 1680x1050 (WSXGA+) | 516       | 3.57%   |
| 1440x900 (WXGA+)   | 475       | 3.28%   |
| 2560x1440 (QHD)    | 435       | 3.01%   |
| 1280x800 (WXGA)    | 408       | 2.82%   |
| 1920x1200 (WUXGA)  | 273       | 1.89%   |
| 1360x768           | 142       | 0.98%   |
| 2560x1080          | 77        | 0.53%   |
| 3440x1440          | 74        | 0.51%   |
| 2560x1600          | 68        | 0.47%   |
| 1920x540           | 51        | 0.35%   |
| 1024x768 (XGA)     | 47        | 0.32%   |
| 1600x1200          | 25        | 0.17%   |
| 2160x1440          | 24        | 0.17%   |
| 2880x1800          | 23        | 0.16%   |
| 1024x600           | 23        | 0.16%   |
| 3200x1800 (QHD+)   | 21        | 0.15%   |
| 1280x720 (HD)      | 20        | 0.14%   |
| 2288x1287          | 19        | 0.13%   |
| 2736x1824          | 15        | 0.1%    |
| 1280x960           | 13        | 0.09%   |
| 1920x1280          | 11        | 0.08%   |
| 1680x945           | 11        | 0.08%   |
| 3840x2400          | 10        | 0.07%   |
| 3840x1080          | 10        | 0.07%   |
| 2048x1152          | 9         | 0.06%   |
| Unknown            | 9         | 0.06%   |
| 2256x1504          | 7         | 0.05%   |
| 1400x1050          | 5         | 0.03%   |
| 1280x768           | 5         | 0.03%   |
| 3840x1600          | 4         | 0.03%   |
| 1152x864           | 4         | 0.03%   |
| 800x1280           | 3         | 0.02%   |
| 3456x2160          | 3         | 0.02%   |
| 2880x1920          | 3         | 0.02%   |
| 2240x1400          | 3         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3520      | 23.85%  |
| 13      | 1196      | 8.1%    |
| 23      | 1193      | 8.08%   |
| 21      | 1078      | 7.3%    |
| 17      | 1012      | 6.86%   |
| 27      | 972       | 6.59%   |
| 24      | 939       | 6.36%   |
| 14      | 880       | 5.96%   |
| 19      | 615       | 4.17%   |
| 18      | 468       | 3.17%   |
| 31      | 387       | 2.62%   |
| 22      | 356       | 2.41%   |
| 20      | 301       | 2.04%   |
| 11      | 277       | 1.88%   |
| 12      | 271       | 1.84%   |
| Unknown | 148       | 1%      |
| 34      | 129       | 0.87%   |
| 84      | 126       | 0.85%   |
| 54      | 85        | 0.58%   |
| 32      | 84        | 0.57%   |
| 72      | 72        | 0.49%   |
| 16      | 70        | 0.47%   |
| 40      | 67        | 0.45%   |
| 26      | 67        | 0.45%   |
| 25      | 54        | 0.37%   |
| 10      | 48        | 0.33%   |
| 52      | 33        | 0.22%   |
| 65      | 27        | 0.18%   |
| 28      | 25        | 0.17%   |
| 48      | 24        | 0.16%   |
| 46      | 21        | 0.14%   |
| 33      | 21        | 0.14%   |
| 39      | 20        | 0.14%   |
| 37      | 19        | 0.13%   |
| 142     | 15        | 0.1%    |
| 42      | 15        | 0.1%    |
| 29      | 15        | 0.1%    |
| 35      | 14        | 0.09%   |
| 74      | 12        | 0.08%   |
| 36      | 11        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 5218      | 35.79%  |
| 501-600        | 2966      | 20.34%  |
| 401-500        | 2490      | 17.08%  |
| 201-300        | 1190      | 8.16%   |
| 351-400        | 1186      | 8.13%   |
| 601-700        | 521       | 3.57%   |
| 701-800        | 246       | 1.69%   |
| 1001-1500      | 234       | 1.6%    |
| 1501-2000      | 215       | 1.47%   |
| Unknown        | 148       | 1.02%   |
| 801-900        | 122       | 0.84%   |
| 901-1000       | 26        | 0.18%   |
| More than 2000 | 15        | 0.1%    |
| 1-100          | 3         | 0.02%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 11083     | 78.97%  |
| 16/10   | 1808      | 12.88%  |
| 5/4     | 610       | 4.35%   |
| 21/9    | 145       | 1.03%   |
| 3/2     | 135       | 0.96%   |
| 4/3     | 131       | 0.93%   |
| Unknown | 57        | 0.41%   |
| 32/9    | 18        | 0.13%   |
| 1.00    | 15        | 0.11%   |
| 6/5     | 14        | 0.1%    |
| 1.96    | 5         | 0.04%   |
| 0.67    | 3         | 0.02%   |
| 2.12    | 2         | 0.01%   |
| 2.00    | 2         | 0.01%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.65    | 1         | 0.01%   |
| 2.01    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3495      | 23.84%  |
| 201-250        | 2891      | 19.72%  |
| 81-90          | 1561      | 10.65%  |
| 151-200        | 1278      | 8.72%   |
| 301-350        | 1020      | 6.96%   |
| 141-150        | 690       | 4.71%   |
| 351-500        | 646       | 4.41%   |
| 121-130        | 577       | 3.94%   |
| 71-80          | 532       | 3.63%   |
| More than 1000 | 427       | 2.91%   |
| 251-300        | 394       | 2.69%   |
| 51-60          | 284       | 1.94%   |
| 61-70          | 240       | 1.64%   |
| 501-1000       | 191       | 1.3%    |
| Unknown        | 148       | 1.01%   |
| 131-140        | 140       | 0.96%   |
| 111-120        | 69        | 0.47%   |
| 41-50          | 43        | 0.29%   |
| 91-100         | 29        | 0.2%    |
| 1-40           | 4         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 5922      | 41.19%  |
| 101-120       | 4551      | 31.65%  |
| 121-160       | 2783      | 19.36%  |
| 161-240       | 500       | 3.48%   |
| 1-50          | 370       | 2.57%   |
| Unknown       | 148       | 1.03%   |
| More than 240 | 103       | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 13327     | 90.89%  |
| 2     | 1108      | 7.56%   |
| 0     | 165       | 1.13%   |
| 3     | 52        | 0.35%   |
| 4     | 7         | 0.05%   |
| 6     | 2         | 0.01%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8506      | 39.61%  |
| Intel                             | 5809      | 27.05%  |
| Qualcomm Atheros                  | 3013      | 14.03%  |
| Broadcom                          | 1080      | 5.03%   |
| Marvell Technology Group          | 288       | 1.34%   |
| Ralink Technology                 | 286       | 1.33%   |
| Broadcom Limited                  | 280       | 1.3%    |
| Ralink                            | 263       | 1.22%   |
| Nvidia                            | 242       | 1.13%   |
| Samsung Electronics               | 177       | 0.82%   |
| MediaTek                          | 164       | 0.76%   |
| TP-Link                           | 162       | 0.75%   |
| Qualcomm Atheros Communications   | 95        | 0.44%   |
| Huawei Technologies               | 87        | 0.41%   |
| JMicron Technology                | 77        | 0.36%   |
| Dell                              | 66        | 0.31%   |
| ASIX Electronics                  | 64        | 0.3%    |
| D-Link                            | 56        | 0.26%   |
| Ericsson Business Mobile Networks | 49        | 0.23%   |
| D-Link System                     | 46        | 0.21%   |
| NetGear                           | 44        | 0.2%    |
| ASUSTek Computer                  | 44        | 0.2%    |
| Sierra Wireless                   | 37        | 0.17%   |
| Xiaomi                            | 31        | 0.14%   |
| Belkin Components                 | 31        | 0.14%   |
| VIA Technologies                  | 28        | 0.13%   |
| Microsoft                         | 28        | 0.13%   |
| Motorola PCS                      | 25        | 0.12%   |
| Aquantia                          | 25        | 0.12%   |
| DisplayLink                       | 22        | 0.1%    |
| Linksys                           | 21        | 0.1%    |
| Hewlett-Packard                   | 20        | 0.09%   |
| ZTE WCDMA Technologies MSM        | 19        | 0.09%   |
| OPPO Electronics                  | 19        | 0.09%   |
| Edimax Technology                 | 19        | 0.09%   |
| IMC Networks                      | 15        | 0.07%   |
| AVM                               | 15        | 0.07%   |
| Qualcomm                          | 13        | 0.06%   |
| 3Com                              | 13        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6043      | 24.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1153      | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 583       | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 470       | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 448       | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 391       | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 387       | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 339       | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 337       | 1.36%   |
| Intel Wireless 7265                                               | 295       | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 257       | 1.04%   |
| Intel Wireless 8265 / 8275                                        | 254       | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 236       | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 229       | 0.92%   |
| Intel Wireless 7260                                               | 224       | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 212       | 0.85%   |
| Intel I211 Gigabit Network Connection                             | 210       | 0.85%   |
| Intel Wireless 3165                                               | 200       | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 200       | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 191       | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 191       | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 191       | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 186       | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 186       | 0.75%   |
| Intel Wireless 8260                                               | 184       | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 166       | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 161       | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 161       | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 156       | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 136       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 132       | 0.53%   |
| Intel Wireless 3160                                               | 128       | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 121       | 0.49%   |
| Intel Wi-Fi 6 AX201                                               | 119       | 0.48%   |
| Intel WiFi Link 5100                                              | 118       | 0.48%   |
| Intel Ethernet Controller I225-V                                  | 117       | 0.47%   |
| Nvidia MCP61 Ethernet                                             | 113       | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 108       | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 108       | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 107       | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4046      | 38.56%  |
| Qualcomm Atheros                      | 2382      | 22.7%   |
| Realtek Semiconductor                 | 1972      | 18.79%  |
| Broadcom                              | 610       | 5.81%   |
| Ralink Technology                     | 286       | 2.73%   |
| Ralink                                | 263       | 2.51%   |
| MediaTek                              | 142       | 1.35%   |
| TP-Link                               | 126       | 1.2%    |
| Broadcom Limited                      | 122       | 1.16%   |
| Qualcomm Atheros Communications       | 95        | 0.91%   |
| D-Link                                | 52        | 0.5%    |
| ASUSTek Computer                      | 42        | 0.4%    |
| Sierra Wireless                       | 37        | 0.35%   |
| NetGear                               | 37        | 0.35%   |
| Dell                                  | 34        | 0.32%   |
| Belkin Components                     | 30        | 0.29%   |
| Microsoft                             | 26        | 0.25%   |
| D-Link System                         | 25        | 0.24%   |
| Linksys                               | 19        | 0.18%   |
| Edimax Technology                     | 19        | 0.18%   |
| Marvell Technology Group              | 17        | 0.16%   |
| IMC Networks                          | 15        | 0.14%   |
| AVM                                   | 15        | 0.14%   |
| Ericsson Business Mobile Networks     | 8         | 0.08%   |
| Mercucys                              | 6         | 0.06%   |
| Hewlett-Packard                       | 6         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.05%   |
| ZyDAS                                 | 4         | 0.04%   |
| Wilocity                              | 4         | 0.04%   |
| Sitecom Europe                        | 4         | 0.04%   |
| Guillemot                             | 4         | 0.04%   |
| Gemtek                                | 4         | 0.04%   |
| Fibocom                               | 4         | 0.04%   |
| Qcom                                  | 3         | 0.03%   |
| PLANEX                                | 3         | 0.03%   |
| BUFFALO                               | 3         | 0.03%   |
| ZyXEL Communications                  | 2         | 0.02%   |
| Wacom                                 | 2         | 0.02%   |
| Sweex                                 | 2         | 0.02%   |
| Senao                                 | 2         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 470       | 4.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 448       | 4.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 391       | 3.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 387       | 3.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 339       | 3.22%   |
| Intel Wi-Fi 6 AX200                                                     | 337       | 3.2%    |
| Intel Wireless 7265                                                     | 295       | 2.8%    |
| Intel Wireless 8265 / 8275                                              | 254       | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 229       | 2.17%   |
| Intel Wireless 7260                                                     | 224       | 2.13%   |
| Intel Wireless 3165                                                     | 200       | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 200       | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 191       | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 191       | 1.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 186       | 1.76%   |
| Intel Wireless 8260                                                     | 184       | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 161       | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 156       | 1.48%   |
| Ralink MT7601U Wireless Adapter                                         | 136       | 1.29%   |
| Intel Wireless 3160                                                     | 128       | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 121       | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 119       | 1.13%   |
| Intel WiFi Link 5100                                                    | 118       | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 108       | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 107       | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 105       | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 104       | 0.99%   |
| Intel Wireless-AC 9260                                                  | 100       | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 97        | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 96        | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 94        | 0.89%   |
| Intel Centrino Advanced-N 6200                                          | 92        | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 91        | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 90        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 88        | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 88        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 84        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 83        | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                         | 81        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 79        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 7772      | 55.97%  |
| Intel                            | 3116      | 22.44%  |
| Qualcomm Atheros                 | 942       | 6.78%   |
| Broadcom                         | 610       | 4.39%   |
| Marvell Technology Group         | 271       | 1.95%   |
| Nvidia                           | 241       | 1.74%   |
| Samsung Electronics              | 177       | 1.27%   |
| Broadcom Limited                 | 162       | 1.17%   |
| JMicron Technology               | 77        | 0.55%   |
| Huawei Technologies              | 77        | 0.55%   |
| ASIX Electronics                 | 64        | 0.46%   |
| TP-Link                          | 38        | 0.27%   |
| Xiaomi                           | 31        | 0.22%   |
| VIA Technologies                 | 25        | 0.18%   |
| Aquantia                         | 25        | 0.18%   |
| MediaTek                         | 22        | 0.16%   |
| DisplayLink                      | 22        | 0.16%   |
| D-Link System                    | 21        | 0.15%   |
| OPPO Electronics                 | 19        | 0.14%   |
| ZTE WCDMA Technologies MSM       | 18        | 0.13%   |
| Motorola PCS                     | 17        | 0.12%   |
| 3Com                             | 13        | 0.09%   |
| Silicon Integrated Systems [SiS] | 12        | 0.09%   |
| Qualcomm                         | 11        | 0.08%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.06%   |
| ICS Advent                       | 8         | 0.06%   |
| NetGear                          | 7         | 0.05%   |
| Lenovo                           | 7         | 0.05%   |
| T & A Mobile Phones              | 6         | 0.04%   |
| Apple                            | 6         | 0.04%   |
| Hewlett-Packard                  | 5         | 0.04%   |
| Spreadtrum Communications        | 4         | 0.03%   |
| LG Electronics                   | 4         | 0.03%   |
| HTC (High Tech Computer)         | 4         | 0.03%   |
| Google                           | 4         | 0.03%   |
| D-Link                           | 4         | 0.03%   |
| Attansic Technology              | 4         | 0.03%   |
| vivo                             | 3         | 0.02%   |
| Mellanox Technologies            | 3         | 0.02%   |
| HMD Global                       | 3         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6043      | 42.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1153      | 8.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 583       | 4.13%   |
| Intel Ethernet Connection I217-LM                                 | 257       | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 236       | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 212       | 1.5%    |
| Intel I211 Gigabit Network Connection                             | 210       | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 191       | 1.35%   |
| Intel Ethernet Connection (2) I219-V                              | 186       | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 166       | 1.18%   |
| Intel 82579V Gigabit Network Connection                           | 161       | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 132       | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 117       | 0.83%   |
| Nvidia MCP61 Ethernet                                             | 113       | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 108       | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 106       | 0.75%   |
| Intel 82567LM Gigabit Network Connection                          | 98        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 94        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 88        | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 88        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 88        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 86        | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 85        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 75        | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 75        | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 73        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 70        | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 69        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 68        | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 67        | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 61        | 0.43%   |
| Huawei E353/E3131                                                 | 56        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 55        | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 55        | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 53        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 52        | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 52        | 0.37%   |
| Intel 82574L Gigabit Network Connection                           | 50        | 0.35%   |
| Intel Ethernet Connection (2) I218-V                              | 48        | 0.34%   |
| ASIX AX88179 Gigabit Ethernet                                     | 48        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 13288     | 56.45%  |
| WiFi     | 10101     | 42.91%  |
| Modem    | 120       | 0.51%   |
| Unknown  | 29        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8060      | 55.93%  |
| WiFi     | 6350      | 44.06%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7657      | 52.37%  |
| 1     | 6593      | 45.09%  |
| 3     | 200       | 1.37%   |
| 0     | 140       | 0.96%   |
| 4     | 23        | 0.16%   |
| 5     | 4         | 0.03%   |
| 6     | 2         | 0.01%   |
| 10    | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 10576     | 71.55%  |
| Yes     | 4205      | 28.45%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2940      | 39.98%  |
| Realtek Semiconductor           | 804       | 10.93%  |
| Qualcomm Atheros Communications | 696       | 9.46%   |
| Cambridge Silicon Radio         | 521       | 7.08%   |
| Broadcom                        | 454       | 6.17%   |
| Lite-On Technology              | 357       | 4.85%   |
| IMC Networks                    | 336       | 4.57%   |
| Foxconn / Hon Hai               | 231       | 3.14%   |
| Apple                           | 203       | 2.76%   |
| Dell                            | 134       | 1.82%   |
| ASUSTek Computer                | 121       | 1.65%   |
| Toshiba                         | 111       | 1.51%   |
| Hewlett-Packard                 | 104       | 1.41%   |
| Ralink                          | 63        | 0.86%   |
| MediaTek                        | 45        | 0.61%   |
| Realtek                         | 30        | 0.41%   |
| Alps Electric                   | 21        | 0.29%   |
| Foxconn International           | 20        | 0.27%   |
| TP-Link                         | 19        | 0.26%   |
| Marvell Semiconductor           | 18        | 0.24%   |
| Ralink Technology               | 14        | 0.19%   |
| Chicony Electronics             | 13        | 0.18%   |
| Belkin Components               | 13        | 0.18%   |
| Askey Computer                  | 12        | 0.16%   |
| Integrated System Solution      | 11        | 0.15%   |
| Fujitsu                         | 7         | 0.1%    |
| Edimax Technology               | 7         | 0.1%    |
| Dynex                           | 7         | 0.1%    |
| Taiyo Yuden                     | 6         | 0.08%   |
| Primax Electronics              | 6         | 0.08%   |
| Micro Star International        | 6         | 0.08%   |
| Unknown                         | 5         | 0.07%   |
| USI                             | 3         | 0.04%   |
| Qcom                            | 3         | 0.04%   |
| ISSC                            | 3         | 0.04%   |
| Smart Modular Technologies      | 2         | 0.03%   |
| SINO WEALTH                     | 2         | 0.03%   |
| Accel Semiconductor             | 2         | 0.03%   |
| Unknown                         | 1         | 0.01%   |
| Opticis                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1315      | 17.87%  |
| Realtek Bluetooth Radio                                                             | 544       | 7.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 521       | 7.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 391       | 5.31%   |
| Intel AX201 Bluetooth                                                               | 332       | 4.51%   |
| Intel AX200 Bluetooth                                                               | 322       | 4.38%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 317       | 4.31%   |
| Intel Bluetooth Device                                                              | 239       | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 204       | 2.77%   |
| IMC Networks Bluetooth Radio                                                        | 132       | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 129       | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 128       | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 117       | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 112       | 1.52%   |
| IMC Networks Bluetooth Device                                                       | 98        | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 90        | 1.22%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 88        | 1.2%    |
| Apple Bluetooth Host Controller                                                     | 85        | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 83        | 1.13%   |
| Lite-On Bluetooth Device                                                            | 82        | 1.11%   |
| Intel AX210 Bluetooth                                                               | 76        | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 71        | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 69        | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 65        | 0.88%   |
| Ralink RT3290 Bluetooth                                                             | 63        | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 60        | 0.82%   |
| Apple Bluetooth USB Host Controller                                                 | 60        | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 58        | 0.79%   |
| Dell DW375 Bluetooth Module                                                         | 58        | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 45        | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 43        | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 42        | 0.57%   |
| MediaTek Wireless_Device                                                            | 42        | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 41        | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 41        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 36        | 0.49%   |
| Toshiba Bluetooth Device                                                            | 35        | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 34        | 0.46%   |
| Realtek RTL8821A Bluetooth                                                          | 33        | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 33        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 10562     | 54.54%  |
| AMD                                  | 4368      | 22.56%  |
| Nvidia                               | 3136      | 16.2%   |
| C-Media Electronics                  | 268       | 1.38%   |
| Creative Labs                        | 181       | 0.93%   |
| Logitech                             | 84        | 0.43%   |
| Texas Instruments                    | 58        | 0.3%    |
| Generalplus Technology               | 50        | 0.26%   |
| Creative Technology                  | 48        | 0.25%   |
| JMTek                                | 46        | 0.24%   |
| ASUSTek Computer                     | 33        | 0.17%   |
| VIA Technologies                     | 31        | 0.16%   |
| GN Netcom                            | 22        | 0.11%   |
| Razer USA                            | 20        | 0.1%    |
| Tenx Technology                      | 19        | 0.1%    |
| Realtek Semiconductor                | 16        | 0.08%   |
| Kingston Technology                  | 15        | 0.08%   |
| Focusrite-Novation                   | 15        | 0.08%   |
| Plantronics                          | 13        | 0.07%   |
| Silicon Integrated Systems [SiS]     | 12        | 0.06%   |
| KTMicro                              | 12        | 0.06%   |
| Micro Star International             | 11        | 0.06%   |
| XMOS                                 | 10        | 0.05%   |
| Thesycon Systemsoftware & Consulting | 10        | 0.05%   |
| SteelSeries ApS                      | 10        | 0.05%   |
| Samson Technologies                  | 10        | 0.05%   |
| Dell                                 | 10        | 0.05%   |
| Hewlett-Packard                      | 9         | 0.05%   |
| Corsair                              | 9         | 0.05%   |
| Apple                                | 9         | 0.05%   |
| Yamaha                               | 8         | 0.04%   |
| SAVITECH                             | 8         | 0.04%   |
| M-Audio                              | 8         | 0.04%   |
| Giga-Byte Technology                 | 8         | 0.04%   |
| PreSonus Audio Electronics           | 7         | 0.04%   |
| Lenovo                               | 7         | 0.04%   |
| GYROCOM C&C                          | 7         | 0.04%   |
| Ensoniq                              | 7         | 0.04%   |
| Blue Microphones                     | 7         | 0.04%   |
| BEHRINGER International              | 7         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1285      | 5.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1241      | 5.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1063      | 4.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 834       | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 813       | 3.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 794       | 3.41%   |
| AMD FCH Azalia Controller                                                                         | 687       | 2.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 636       | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 614       | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 612       | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 510       | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 504       | 2.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 451       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 418       | 1.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 399       | 1.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 364       | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 346       | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 329       | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 325       | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 318       | 1.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 310       | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 309       | 1.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 294       | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 289       | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 285       | 1.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 284       | 1.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 281       | 1.21%   |
| Nvidia High Definition Audio Controller                                                           | 268       | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 258       | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 248       | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 223       | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 213       | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 181       | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 180       | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 176       | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 174       | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 157       | 0.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 155       | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 151       | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 149       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3252      | 18.72%  |
| SK hynix            | 2611      | 15.03%  |
| Unknown             | 2290      | 13.19%  |
| Kingston            | 2264      | 13.04%  |
| Micron Technology   | 1382      | 7.96%   |
| Crucial             | 926       | 5.33%   |
| Corsair             | 730       | 4.2%    |
| G.Skill             | 529       | 3.05%   |
| Elpida              | 434       | 2.5%    |
| A-DATA Technology   | 381       | 2.19%   |
| Ramaxel Technology  | 324       | 1.87%   |
| Nanya Technology    | 298       | 1.72%   |
| Smart               | 179       | 1.03%   |
| Unknown (ABCD)      | 161       | 0.93%   |
| Unknown             | 154       | 0.89%   |
| Patriot             | 134       | 0.77%   |
| Team                | 133       | 0.77%   |
| GOODRAM             | 85        | 0.49%   |
| Transcend           | 78        | 0.45%   |
| AMD                 | 60        | 0.35%   |
| Apacer              | 57        | 0.33%   |
| Teikon              | 46        | 0.26%   |
| ASint Technology    | 36        | 0.21%   |
| Silicon Power       | 33        | 0.19%   |
| Kingmax             | 33        | 0.19%   |
| Toshiba             | 32        | 0.18%   |
| Avant               | 31        | 0.18%   |
| Qimonda             | 30        | 0.17%   |
| High Bridge         | 26        | 0.15%   |
| Unifosa             | 24        | 0.14%   |
| PNY                 | 23        | 0.13%   |
| GeIL                | 23        | 0.13%   |
| CSX                 | 22        | 0.13%   |
| Multilaser          | 21        | 0.12%   |
| Smart Brazil        | 19        | 0.11%   |
| Timetec             | 17        | 0.1%    |
| Goldkey             | 14        | 0.08%   |
| Atermiter           | 14        | 0.08%   |
| Kllisre             | 13        | 0.07%   |
| 48spaces            | 12        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 175       | 0.93%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 157       | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 155       | 0.82%   |
| Unknown                                                          | 154       | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 145       | 0.77%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 131       | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 130       | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 129       | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 127       | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 126       | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 120       | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 111       | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 107       | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 106       | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 101       | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 100       | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 98        | 0.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 91        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 77        | 0.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 76        | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 73        | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 69        | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 68        | 0.36%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 65        | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 65        | 0.34%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 64        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 64        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 60        | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 58        | 0.31%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 58        | 0.31%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 55        | 0.29%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 55        | 0.29%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 55        | 0.29%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 55        | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 54        | 0.29%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 53        | 0.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 53        | 0.28%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 53        | 0.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 53        | 0.28%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 53        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 6582      | 44.65%  |
| DDR4    | 4782      | 32.44%  |
| DDR2    | 1209      | 8.2%    |
| SDRAM   | 712       | 4.83%   |
| Unknown | 702       | 4.76%   |
| LPDDR4  | 401       | 2.72%   |
| DDR     | 124       | 0.84%   |
| LPDDR3  | 108       | 0.73%   |
| DDR5    | 56        | 0.38%   |
| DRAM    | 38        | 0.26%   |
| LPDDR5  | 26        | 0.18%   |
| RAM     | 2         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 7601      | 52.44%  |
| DIMM         | 6393      | 44.11%  |
| Row Of Chips | 424       | 2.93%   |
| Chip         | 31        | 0.21%   |
| Unknown      | 26        | 0.18%   |
| RIMM         | 11        | 0.08%   |
| FB-DIMM      | 8         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 5806      | 35.31%  |
| 8192  | 4973      | 30.24%  |
| 2048  | 3394      | 20.64%  |
| 16384 | 1120      | 6.81%   |
| 1024  | 780       | 4.74%   |
| 32768 | 281       | 1.71%   |
| 512   | 82        | 0.5%    |
| 256   | 3         | 0.02%   |
| 65536 | 1         | 0.01%   |
| 15616 | 1         | 0.01%   |
| 12333 | 1         | 0.01%   |
| 3072  | 1         | 0.01%   |
| 64    | 1         | 0.01%   |
| 32    | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 4068      | 24.78%  |
| 1333    | 1760      | 10.72%  |
| 2667    | 1517      | 9.24%   |
| 3200    | 1263      | 7.69%   |
| 2400    | 1086      | 6.62%   |
| 1334    | 769       | 4.68%   |
| 667     | 674       | 4.11%   |
| 800     | 649       | 3.95%   |
| 2133    | 570       | 3.47%   |
| Unknown | 468       | 2.85%   |
| 3600    | 343       | 2.09%   |
| 1067    | 320       | 1.95%   |
| 1867    | 279       | 1.7%    |
| 1066    | 187       | 1.14%   |
| 3266    | 167       | 1.02%   |
| 1866    | 161       | 0.98%   |
| 4199    | 146       | 0.89%   |
| 2048    | 127       | 0.77%   |
| 1800    | 124       | 0.76%   |
| 533     | 121       | 0.74%   |
| 2666    | 117       | 0.71%   |
| 4267    | 104       | 0.63%   |
| 3400    | 101       | 0.62%   |
| 3000    | 99        | 0.6%    |
| 2933    | 99        | 0.6%    |
| 975     | 89        | 0.54%   |
| 400     | 87        | 0.53%   |
| 3733    | 64        | 0.39%   |
| 3800    | 47        | 0.29%   |
| 3866    | 44        | 0.27%   |
| 2800    | 44        | 0.27%   |
| 4800    | 37        | 0.23%   |
| 3533    | 36        | 0.22%   |
| 3466    | 36        | 0.22%   |
| 333     | 35        | 0.21%   |
| 4266    | 33        | 0.2%    |
| 2000    | 31        | 0.19%   |
| 3666    | 30        | 0.18%   |
| 1639    | 29        | 0.18%   |
| 6400    | 27        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 211       | 40.19%  |
| Brother Industries    | 103       | 19.62%  |
| Canon                 | 80        | 15.24%  |
| Samsung Electronics   | 46        | 8.76%   |
| Seiko Epson           | 43        | 8.19%   |
| Lexmark International | 10        | 1.9%    |
| Prolific Technology   | 7         | 1.33%   |
| Xerox                 | 5         | 0.95%   |
| QinHeng Electronics   | 5         | 0.95%   |
| Kyocera               | 4         | 0.76%   |
| Dymo-CoStar           | 3         | 0.57%   |
| Ricoh                 | 2         | 0.38%   |
| Zebra                 | 1         | 0.19%   |
| Philips (or NXP)      | 1         | 0.19%   |
| Oki Data              | 1         | 0.19%   |
| NXP Semiconductors    | 1         | 0.19%   |
| MIIIW                 | 1         | 0.19%   |
| Citizen               | 1         | 0.19%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP DeskJet 2600 series               | 12        | 2.25%   |
| HP DeskJet 2700 series               | 9         | 1.69%   |
| Samsung ML-1640 Series Laser Printer | 8         | 1.5%    |
| Prolific PL2305 Parallel Port        | 7         | 1.31%   |
| HP ENVY 4520 series                  | 7         | 1.31%   |
| HP DeskJet 3630 series               | 7         | 1.31%   |
| Samsung M2070 Series                 | 6         | 1.13%   |
| Samsung M2020 Series                 | 6         | 1.13%   |
| HP LaserJet 1020                     | 6         | 1.13%   |
| HP DeskJet 2130 series               | 6         | 1.13%   |
| Brother Printer                      | 6         | 1.13%   |
| Brother HL-L2390DW                   | 6         | 1.13%   |
| QinHeng CH340S                       | 5         | 0.94%   |
| HP LaserJet 1018                     | 5         | 0.94%   |
| Canon PIXMA MG3600 Series            | 5         | 0.94%   |
| Seiko Epson ET-2710 Series           | 4         | 0.75%   |
| HP OfficeJet Pro 7740 series         | 4         | 0.75%   |
| HP LaserJet P1006                    | 4         | 0.75%   |
| HP LaserJet P1005                    | 4         | 0.75%   |
| HP Ink Tank Wireless 410 series      | 4         | 0.75%   |
| HP ENVY Photo 6200 series            | 4         | 0.75%   |
| Canon PIXMA MX920 Series             | 4         | 0.75%   |
| Canon LiDE 400                       | 4         | 0.75%   |
| Canon LBP2900                        | 4         | 0.75%   |
| Canon CanoScan LiDE 300              | 4         | 0.75%   |
| Brother HL-3140CW series             | 4         | 0.75%   |
| Brother DCP-7055W                    | 4         | 0.75%   |
| Seiko Epson L365 Series              | 3         | 0.56%   |
| Seiko Epson L120 Series              | 3         | 0.56%   |
| Samsung SCX-3400 Series              | 3         | 0.56%   |
| Samsung ML-2010P Mono Laser Printer  | 3         | 0.56%   |
| HP OfficeJet 6950                    | 3         | 0.56%   |
| HP OfficeJet 3830 series             | 3         | 0.56%   |
| HP LaserJet Pro M148f-M149f          | 3         | 0.56%   |
| HP LaserJet P1102                    | 3         | 0.56%   |
| HP LaserJet M14-M17                  | 3         | 0.56%   |
| HP LaserJet 1200                     | 3         | 0.56%   |
| HP LaserJet 1010                     | 3         | 0.56%   |
| HP ENVY 5000 series                  | 3         | 0.56%   |
| HP Deskjet F4500 series              | 3         | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 53        | 55.21%  |
| Hewlett-Packard             | 15        | 15.63%  |
| Seiko Epson                 | 13        | 13.54%  |
| Mustek Systems              | 7         | 7.29%   |
| AGFA-Gevaert NV             | 3         | 3.13%   |
| KYE Systems (Mouse Systems) | 2         | 2.08%   |
| Plustek                     | 1         | 1.04%   |
| Fujitsu                     | 1         | 1.04%   |
| Acer Peripherals (now BenQ) | 1         | 1.04%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 10        | 10.42%  |
| Canon CanoScan LiDE 210                                  | 7         | 7.29%   |
| Canon CanoScan LiDE 100                                  | 6         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 4         | 4.17%   |
| Canon CanoScan LiDE 120                                  | 4         | 4.17%   |
| Mustek Systems ScanExpress 1200 UB                       | 3         | 3.13%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 3         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 3         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 3         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 2.08%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 2.08%   |
| HP ScanJet 5590                                          | 2         | 2.08%   |
| HP ScanJet 4500C/5550C                                   | 2         | 2.08%   |
| HP ScanJet 2400c                                         | 2         | 2.08%   |
| Canon CanoScan LiDE 70                                   | 2         | 2.08%   |
| Canon CanoScan LiDE 60                                   | 2         | 2.08%   |
| Canon CanoScan LiDE 200                                  | 2         | 2.08%   |
| AGFA-Gevaert NV SnapScan e20                             | 2         | 2.08%   |
| Seiko Epson Scanner                                      | 1         | 1.04%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1         | 1.04%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1         | 1.04%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 1.04%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1         | 1.04%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 1.04%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 1.04%   |
| Seiko Epson GT-9400UF [Perfection 3170]                  | 1         | 1.04%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1         | 1.04%   |
| Plustek 600DPI USB Scanner                               | 1         | 1.04%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 1.04%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 1.04%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 1.04%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1         | 1.04%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 1.04%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE      | 1         | 1.04%   |
| HP ScanJet G4010                                         | 1         | 1.04%   |
| HP Scanjet G2710                                         | 1         | 1.04%   |
| HP ScanJet 4570c                                         | 1         | 1.04%   |
| HP ScanJet 4370                                          | 1         | 1.04%   |
| HP ScanJet 3800c                                         | 1         | 1.04%   |
| HP ScanJet 3670                                          | 1         | 1.04%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1714      | 23.24%  |
| Realtek Semiconductor                  | 630       | 8.54%   |
| Microdia                               | 623       | 8.45%   |
| IMC Networks                           | 535       | 7.25%   |
| Suyin                                  | 385       | 5.22%   |
| Bison Electronics                      | 364       | 4.94%   |
| Logitech                               | 360       | 4.88%   |
| Sunplus Innovation Technology          | 359       | 4.87%   |
| Quanta                                 | 278       | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 265       | 3.59%   |
| Syntek                                 | 219       | 2.97%   |
| Apple                                  | 165       | 2.24%   |
| Alcor Micro                            | 130       | 1.76%   |
| Silicon Motion                         | 128       | 1.74%   |
| Lite-On Technology                     | 124       | 1.68%   |
| Acer                                   | 111       | 1.51%   |
| Ricoh                                  | 108       | 1.46%   |
| Microsoft                              | 75        | 1.02%   |
| Lenovo                                 | 63        | 0.85%   |
| Luxvisions Innotech Limited            | 61        | 0.83%   |
| Z-Star Microelectronics                | 59        | 0.8%    |
| Importek                               | 53        | 0.72%   |
| ALi                                    | 43        | 0.58%   |
| Primax Electronics                     | 37        | 0.5%    |
| Samsung Electronics                    | 30        | 0.41%   |
| Generalplus Technology                 | 26        | 0.35%   |
| Sonix Technology                       | 24        | 0.33%   |
| GEMBIRD                                | 23        | 0.31%   |
| OmniVision Technologies                | 20        | 0.27%   |
| DigiTech                               | 19        | 0.26%   |
| KYE Systems (Mouse Systems)            | 17        | 0.23%   |
| Cubeternet                             | 17        | 0.23%   |
| Creative Technology                    | 17        | 0.23%   |
| Aveo Technology                        | 17        | 0.23%   |
| ARC International                      | 15        | 0.2%    |
| Hewlett-Packard                        | 13        | 0.18%   |
| Jieli Technology                       | 12        | 0.16%   |
| Genesys Logic                          | 12        | 0.16%   |
| Sunplus Technology                     | 11        | 0.15%   |
| Huawei Technologies                    | 10        | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 225       | 3.03%   |
| Microdia Integrated_Webcam_HD                       | 182       | 2.45%   |
| Chicony HD WebCam                                   | 157       | 2.11%   |
| Realtek Integrated_Webcam_HD                        | 136       | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 116       | 1.56%   |
| Sunplus Integrated_Webcam_HD                        | 112       | 1.51%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 102       | 1.37%   |
| Syntek Integrated Camera                            | 98        | 1.32%   |
| IMC Networks Integrated Camera                      | 96        | 1.29%   |
| Bison Integrated Camera                             | 95        | 1.28%   |
| Logitech Webcam C270                                | 88        | 1.18%   |
| Microdia Integrated Webcam                          | 80        | 1.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 72        | 0.97%   |
| Realtek USB Camera                                  | 72        | 0.97%   |
| Chicony VGA WebCam                                  | 67        | 0.9%    |
| Chicony USB 2.0 Camera                              | 65        | 0.88%   |
| Realtek Integrated_Webcam_5M                        | 59        | 0.79%   |
| Sunplus HD WebCam                                   | 58        | 0.78%   |
| Chicony TOSHIBA Web Camera - HD                     | 56        | 0.75%   |
| Chicony HP Truevision HD                            | 56        | 0.75%   |
| Chicony Lenovo EasyCamera                           | 55        | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                        | 52        | 0.7%    |
| Syntek Lenovo EasyCamera                            | 51        | 0.69%   |
| Chicony HP TrueVision HD Camera                     | 51        | 0.69%   |
| Apple Built-in iSight                               | 51        | 0.69%   |
| Chicony EasyCamera                                  | 50        | 0.67%   |
| Chicony FJ Camera                                   | 48        | 0.65%   |
| Logitech HD Pro Webcam C920                         | 47        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 46        | 0.62%   |
| Quanta HD User Facing                               | 44        | 0.59%   |
| Lite-On Integrated Camera                           | 44        | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam                       | 44        | 0.59%   |
| Apple FaceTime HD Camera (Built-in)                 | 44        | 0.59%   |
| Chicony HD User Facing                              | 43        | 0.58%   |
| Suyin Integrated_Webcam_HD                          | 41        | 0.55%   |
| Chicony HP Webcam                                   | 41        | 0.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 40        | 0.54%   |
| Bison Lenovo EasyCamera                             | 40        | 0.54%   |
| Quanta VGA WebCam                                   | 39        | 0.53%   |
| IMC Networks UVC VGA Webcam                         | 39        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 331       | 37.4%   |
| AuthenTec                          | 133       | 15.03%  |
| Synaptics                          | 108       | 12.2%   |
| Upek                               | 87        | 9.83%   |
| Shenzhen Goodix Technology         | 72        | 8.14%   |
| Elan Microelectronics              | 65        | 7.34%   |
| LighTuning Technology              | 42        | 4.75%   |
| STMicroelectronics                 | 32        | 3.62%   |
| Focal-systems.Corp                 | 8         | 0.9%    |
| Samsung Electronics                | 4         | 0.45%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.11%   |
| HOLTEK                             | 1         | 0.11%   |
| DigitalPersona                     | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 80        | 9.04%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 61        | 6.89%   |
| AuthenTec AES2810                                                          | 51        | 5.76%   |
| Shenzhen Goodix  Fingerprint Device                                        | 47        | 5.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 43        | 4.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 34        | 3.84%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 3.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 31        | 3.5%    |
| Validity Sensors VFS491                                                    | 31        | 3.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 30        | 3.39%   |
| Elan ELAN:Fingerprint                                                      | 29        | 3.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 25        | 2.82%   |
| Elan ELAN:ARM-M4                                                           | 25        | 2.82%   |
| Validity Sensors Synaptics WBDI                                            | 24        | 2.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 2.49%   |
| Synaptics  WBDI                                                            | 21        | 2.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 2.37%   |
| AuthenTec AES1600                                                          | 19        | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 18        | 2.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 1.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 1.81%   |
| AuthenTec Fingerprint Sensor                                               | 16        | 1.81%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 1.58%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.58%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 1.36%   |
| Elan WBF Fingerprint Sensor                                                | 11        | 1.24%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.02%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 0.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.9%    |
| LighTuning Fingerprint Reader                                              | 8         | 0.9%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 8         | 0.9%    |
| Upek TCS5B Fingerprint sensor                                              | 7         | 0.79%   |
| Synaptics WBDI                                                             | 7         | 0.79%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.79%   |
| Synaptics UWP WBDI                                                         | 7         | 0.79%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.68%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 245       | 48.42%  |
| Alcor Micro                       | 85        | 16.8%   |
| O2 Micro                          | 61        | 12.06%  |
| Upek                              | 38        | 7.51%   |
| Lenovo                            | 37        | 7.31%   |
| SCM Microsystems                  | 9         | 1.78%   |
| Gemalto (was Gemplus)             | 7         | 1.38%   |
| Realtek Semiconductor             | 5         | 0.99%   |
| OmniKey                           | 3         | 0.59%   |
| BIT4ID                            | 3         | 0.59%   |
| Advanced Card Systems             | 3         | 0.59%   |
| Reiner SCT Kartensysteme          | 2         | 0.4%    |
| Cherry                            | 2         | 0.4%    |
| VASCO Data Security International | 1         | 0.2%    |
| Microchip Technology              | 1         | 0.2%    |
| Hewlett-Packard                   | 1         | 0.2%    |
| Fujitsu Siemens Computers         | 1         | 0.2%    |
| Castles Technology                | 1         | 0.2%    |
| Aladdin Knowledge Systems         | 1         | 0.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 122       | 24.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 82        | 16.21%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 60        | 11.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 58        | 11.46%  |
| Broadcom 5880                                                                | 52        | 10.28%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 38        | 7.51%   |
| Lenovo Integrated Smart Card Reader                                          | 37        | 7.31%   |
| Broadcom 58200                                                               | 12        | 2.37%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 0.99%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.59%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.59%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.59%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.4%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.4%    |
| BIT4ID miniLector EVO                                                        | 2         | 0.4%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.4%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.4%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.2%    |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.2%    |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.2%    |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.2%    |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.2%    |
| OmniKey CardMan 4321                                                         | 1         | 0.2%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.2%    |
| OmniKey CardMan 1021                                                         | 1         | 0.2%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.2%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.2%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.2%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.2%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.2%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.2%    |
| Cherry Smart Terminal XX44                                                   | 1         | 0.2%    |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.2%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.2%    |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.2%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.2%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.2%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12036     | 82.02%  |
| 1     | 2263      | 15.42%  |
| 2     | 332       | 2.26%   |
| 3     | 38        | 0.26%   |
| 6     | 2         | 0.01%   |
| 4     | 2         | 0.01%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 885       | 29.68%  |
| Graphics card            | 738       | 24.75%  |
| Chipcard                 | 494       | 16.57%  |
| Net/wireless             | 269       | 9.02%   |
| Multimedia controller    | 146       | 4.9%    |
| Bluetooth                | 107       | 3.59%   |
| Storage                  | 84        | 2.82%   |
| Communication controller | 70        | 2.35%   |
| Unassigned class         | 64        | 2.15%   |
| Camera                   | 63        | 2.11%   |
| Sound                    | 14        | 0.47%   |
| Network                  | 13        | 0.44%   |
| Card reader              | 9         | 0.3%    |
| Flash memory             | 6         | 0.2%    |
| Net/ethernet             | 5         | 0.17%   |
| Wireless                 | 4         | 0.13%   |
| Modem                    | 4         | 0.13%   |
| Storage/raid             | 2         | 0.07%   |
| Storage/ata              | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Unclassified device      | 1         | 0.03%   |


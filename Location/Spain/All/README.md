Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 6300

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [f0db98f6bb](https://linux-hardware.org/?probe=f0db98f6bb) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [fc832e8881](https://linux-hardware.org/?probe=fc832e8881) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [416db8870a](https://linux-hardware.org/?probe=416db8870a) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | Notebook    | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [55aa58c274](https://linux-hardware.org/?probe=55aa58c274) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| Unknown       | Unknown                     | Soc         | [44fc490d82](https://linux-hardware.org/?probe=44fc490d82) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | Notebook    | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Intel         | H410M-E                     | Desktop     | [854c3ec5b1](https://linux-hardware.org/?probe=854c3ec5b1) | Oct 27, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [5b6d2d2922](https://linux-hardware.org/?probe=5b6d2d2922) | Oct 27, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [033d6281bd](https://linux-hardware.org/?probe=033d6281bd) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [f9e114a7e9](https://linux-hardware.org/?probe=f9e114a7e9) | Oct 26, 2022 |
| Intel         | H410M-E                     | Desktop     | [69d7d07e13](https://linux-hardware.org/?probe=69d7d07e13) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | Notebook    | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [696c30d8c3](https://linux-hardware.org/?probe=696c30d8c3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | Notebook    | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c05a08e1af](https://linux-hardware.org/?probe=c05a08e1af) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [936e43f0bc](https://linux-hardware.org/?probe=936e43f0bc) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [cce3979970](https://linux-hardware.org/?probe=cce3979970) | Oct 22, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6105b0d3a9](https://linux-hardware.org/?probe=6105b0d3a9) | Oct 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | Notebook    | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | K54C                        | Notebook    | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [18c1a4a04d](https://linux-hardware.org/?probe=18c1a4a04d) | Oct 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff6334ee8f](https://linux-hardware.org/?probe=ff6334ee8f) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [e1eacaa737](https://linux-hardware.org/?probe=e1eacaa737) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| MSI           | IONA                        | Desktop     | [7c164d5733](https://linux-hardware.org/?probe=7c164d5733) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a7941186ab](https://linux-hardware.org/?probe=a7941186ab) | Oct 16, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| HP            | 1495                        | Desktop     | [109913631a](https://linux-hardware.org/?probe=109913631a) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [8bfcad8486](https://linux-hardware.org/?probe=8bfcad8486) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [99fe717434](https://linux-hardware.org/?probe=99fe717434) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [b75b67267c](https://linux-hardware.org/?probe=b75b67267c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [0e3ba8fdb3](https://linux-hardware.org/?probe=0e3ba8fdb3) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [78abe50673](https://linux-hardware.org/?probe=78abe50673) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | Notebook    | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [100f7e1b46](https://linux-hardware.org/?probe=100f7e1b46) | Oct 12, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [5b1999a241](https://linux-hardware.org/?probe=5b1999a241) | Oct 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [1a2fe5eeb4](https://linux-hardware.org/?probe=1a2fe5eeb4) | Oct 12, 2022 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [f3b5809fc9](https://linux-hardware.org/?probe=f3b5809fc9) | Oct 12, 2022 |
| HP            | 3397                        | Desktop     | [c374208e14](https://linux-hardware.org/?probe=c374208e14) | Oct 11, 2022 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [b8c2a39217](https://linux-hardware.org/?probe=b8c2a39217) | Oct 10, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c3a4a7983b](https://linux-hardware.org/?probe=c3a4a7983b) | Oct 10, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [d223d492fe](https://linux-hardware.org/?probe=d223d492fe) | Oct 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | Notebook    | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [dd8bbe4068](https://linux-hardware.org/?probe=dd8bbe4068) | Oct 08, 2022 |
| Medion        | E2221T MD61083              | Convertible | [9f7f0f4ea8](https://linux-hardware.org/?probe=9f7f0f4ea8) | Oct 07, 2022 |
| Medion        | E2221T MD61083              | Convertible | [2eaf3df98c](https://linux-hardware.org/?probe=2eaf3df98c) | Oct 07, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5b30b0591e](https://linux-hardware.org/?probe=5b30b0591e) | Oct 07, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [2550504760](https://linux-hardware.org/?probe=2550504760) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6f0bd5a568](https://linux-hardware.org/?probe=6f0bd5a568) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | Notebook    | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Lenovo        | 1031 SDK0E50510 WIN 2625... | Desktop     | [771e19629c](https://linux-hardware.org/?probe=771e19629c) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [c6dd3eef5d](https://linux-hardware.org/?probe=c6dd3eef5d) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | Notebook    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Shuttle       | DH470                       | Desktop     | [408e44b18b](https://linux-hardware.org/?probe=408e44b18b) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | Notebook    | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [fc1fb9966e](https://linux-hardware.org/?probe=fc1fb9966e) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [d19e0fb48b](https://linux-hardware.org/?probe=d19e0fb48b) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4707a778dc](https://linux-hardware.org/?probe=4707a778dc) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [255a0a928a](https://linux-hardware.org/?probe=255a0a928a) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [77d108e391](https://linux-hardware.org/?probe=77d108e391) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| HP            | 2B35                        | Desktop     | [724e0d61e3](https://linux-hardware.org/?probe=724e0d61e3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Acer          | Aspire X1900                | Desktop     | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | Notebook    | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [173834876c](https://linux-hardware.org/?probe=173834876c) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | Notebook    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [d00d31309a](https://linux-hardware.org/?probe=d00d31309a) | Sep 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [cb519b4bfe](https://linux-hardware.org/?probe=cb519b4bfe) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Sony          | VPCEB1Z1E                   | Notebook    | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | Notebook    | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Minix         | NEO G41V-4 Max              | Desktop     | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Unknown       | 1.0                         | Desktop     | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | Notebook    | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [7ea35cc80a](https://linux-hardware.org/?probe=7ea35cc80a) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0b32a9e842](https://linux-hardware.org/?probe=0b32a9e842) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [fab04fe2c7](https://linux-hardware.org/?probe=fab04fe2c7) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | Notebook    | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | Notebook    | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | Notebook    | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [0b03396c93](https://linux-hardware.org/?probe=0b03396c93) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Acer          | Aspire X3990                | Desktop     | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [c5ebccdc5d](https://linux-hardware.org/?probe=c5ebccdc5d) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [74a9860a2e](https://linux-hardware.org/?probe=74a9860a2e) | Sep 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | Notebook    | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [93a5a7089c](https://linux-hardware.org/?probe=93a5a7089c) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | Notebook    | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | Notebook    | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [0caf1e7324](https://linux-hardware.org/?probe=0caf1e7324) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [06d3f051d1](https://linux-hardware.org/?probe=06d3f051d1) | Sep 09, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Medion        | H61H2-LM3 V1.0              | Desktop     | [96b497db35](https://linux-hardware.org/?probe=96b497db35) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [c0ad8b81fa](https://linux-hardware.org/?probe=c0ad8b81fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9128ddb611](https://linux-hardware.org/?probe=9128ddb611) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6596b0d415](https://linux-hardware.org/?probe=6596b0d415) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b84d0acafb](https://linux-hardware.org/?probe=b84d0acafb) | Sep 01, 2022 |
| Dell          | 07PXPY A04                  | Server      | [f0b9cd86ef](https://linux-hardware.org/?probe=f0b9cd86ef) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | Notebook    | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3955b91269](https://linux-hardware.org/?probe=3955b91269) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3148482797](https://linux-hardware.org/?probe=3148482797) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [12033c4a8b](https://linux-hardware.org/?probe=12033c4a8b) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| MSI           | H97M-G43                    | Desktop     | [978d5b45be](https://linux-hardware.org/?probe=978d5b45be) | Aug 31, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [71ce0b707c](https://linux-hardware.org/?probe=71ce0b707c) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | Notebook    | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | F3F                         | Notebook    | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | Notebook    | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [437b0cd64f](https://linux-hardware.org/?probe=437b0cd64f) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [28ebe8cc1f](https://linux-hardware.org/?probe=28ebe8cc1f) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| Gigabyte      | H81M-D3H                    | Desktop     | [89ced19bd4](https://linux-hardware.org/?probe=89ced19bd4) | Aug 25, 2022 |
| Fujitsu       | D3173-A1 S26361-D3173-A1    | Mini pc     | [273ce0954a](https://linux-hardware.org/?probe=273ce0954a) | Aug 25, 2022 |
| MSI           | H97M-G43                    | Desktop     | [3f781247f0](https://linux-hardware.org/?probe=3f781247f0) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | Notebook    | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HP            | 3647h                       | Desktop     | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | Notebook    | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [216ea6f436](https://linux-hardware.org/?probe=216ea6f436) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Gateway       | DS50                        | Desktop     | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | Desktop     | [02f9463f2b](https://linux-hardware.org/?probe=02f9463f2b) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | Notebook    | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | Notebook    | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| sunxi         | Unknown                     | Soc         | [a57117f63f](https://linux-hardware.org/?probe=a57117f63f) | Aug 15, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [f223d64d8f](https://linux-hardware.org/?probe=f223d64d8f) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b69d60f568](https://linux-hardware.org/?probe=b69d60f568) | Aug 15, 2022 |
| GPD           | G1618-03                    | Notebook    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | Notebook    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Pegatron      | 2A94                        | Desktop     | [81b0cdd377](https://linux-hardware.org/?probe=81b0cdd377) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fd9bae65fa](https://linux-hardware.org/?probe=fd9bae65fa) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [1840f48c85](https://linux-hardware.org/?probe=1840f48c85) | Aug 12, 2022 |
| Dell          | Latitude D630               | Notebook    | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [be29e8b357](https://linux-hardware.org/?probe=be29e8b357) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | Notebook    | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | 3397                        | Desktop     | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [f04f6e3bed](https://linux-hardware.org/?probe=f04f6e3bed) | Aug 07, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [305bf6182f](https://linux-hardware.org/?probe=305bf6182f) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | Notebook    | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| ASUSTek       | M3A78                       | Desktop     | [bda5207234](https://linux-hardware.org/?probe=bda5207234) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | Notebook    | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ab497e8975](https://linux-hardware.org/?probe=ab497e8975) | Aug 04, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f013fa996e](https://linux-hardware.org/?probe=f013fa996e) | Aug 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [c290aae7c6](https://linux-hardware.org/?probe=c290aae7c6) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [19d2273e6b](https://linux-hardware.org/?probe=19d2273e6b) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [8e83e6141d](https://linux-hardware.org/?probe=8e83e6141d) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Acer          | Aspire X3470                | Desktop     | [88ad041430](https://linux-hardware.org/?probe=88ad041430) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | 2AF7                        | Desktop     | [da51487005](https://linux-hardware.org/?probe=da51487005) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e3a44e4c5b](https://linux-hardware.org/?probe=e3a44e4c5b) | Jul 30, 2022 |
| HP            | Compaq 8510p                | Notebook    | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [db241f583d](https://linux-hardware.org/?probe=db241f583d) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | Notebook    | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [d29d943a24](https://linux-hardware.org/?probe=d29d943a24) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | Notebook    | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | Notebook    | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [6b300beb70](https://linux-hardware.org/?probe=6b300beb70) | Jul 25, 2022 |
| Acer          | Aspire 5749                 | Notebook    | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [c7c46e080e](https://linux-hardware.org/?probe=c7c46e080e) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7cc616f3c8](https://linux-hardware.org/?probe=7cc616f3c8) | Jul 24, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [ce14e41b96](https://linux-hardware.org/?probe=ce14e41b96) | Jul 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| Dell          | 0GM819                      | Desktop     | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [89fadaa563](https://linux-hardware.org/?probe=89fadaa563) | Jul 23, 2022 |
| HP            | Stream Notebook             | Notebook    | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | Notebook    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| Dell          | 0GM819                      | Desktop     | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [7ff3bd3639](https://linux-hardware.org/?probe=7ff3bd3639) | Jul 20, 2022 |
| Foxconn       | ETON                        | Desktop     | [1686897e74](https://linux-hardware.org/?probe=1686897e74) | Jul 20, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [67faad589b](https://linux-hardware.org/?probe=67faad589b) | Jul 19, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | Notebook    | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | Notebook    | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [03fca40d38](https://linux-hardware.org/?probe=03fca40d38) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | Notebook    | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| MSI           | Boston                      | Desktop     | [c1474f9d2f](https://linux-hardware.org/?probe=c1474f9d2f) | Jul 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | Notebook    | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c7a2ebd9dc](https://linux-hardware.org/?probe=c7a2ebd9dc) | Jul 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | Notebook    | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [3fe93a38f6](https://linux-hardware.org/?probe=3fe93a38f6) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Acer          | Aspire X3470                | Desktop     | [61b7216da0](https://linux-hardware.org/?probe=61b7216da0) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [3ec331da1f](https://linux-hardware.org/?probe=3ec331da1f) | Jul 12, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [26c70348e9](https://linux-hardware.org/?probe=26c70348e9) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | 318D                        | All in one  | [6c8aa85c66](https://linux-hardware.org/?probe=6c8aa85c66) | Jul 10, 2022 |
| HP            | 805E                        | All in one  | [c7570f51e8](https://linux-hardware.org/?probe=c7570f51e8) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [75f0ca97b8](https://linux-hardware.org/?probe=75f0ca97b8) | Jul 08, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [560e81bb64](https://linux-hardware.org/?probe=560e81bb64) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [4f57a8d7f4](https://linux-hardware.org/?probe=4f57a8d7f4) | Jul 08, 2022 |
| Dell          | Latitude 5285               | Notebook    | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| HP            | 18E7                        | Desktop     | [68781cd22f](https://linux-hardware.org/?probe=68781cd22f) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [aed7de4f94](https://linux-hardware.org/?probe=aed7de4f94) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [8e5892c130](https://linux-hardware.org/?probe=8e5892c130) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | Notebook    | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| MSI           | Z87 MPOWER                  | Desktop     | [ba26baf84a](https://linux-hardware.org/?probe=ba26baf84a) | Jun 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [6dff126482](https://linux-hardware.org/?probe=6dff126482) | Jun 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| HP            | 3647h                       | Desktop     | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [ace3582eee](https://linux-hardware.org/?probe=ace3582eee) | Jun 28, 2022 |
| HP            | 805E                        | All in one  | [efbad579d1](https://linux-hardware.org/?probe=efbad579d1) | Jun 27, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [5d18d90cda](https://linux-hardware.org/?probe=5d18d90cda) | Jun 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [6c18625cb3](https://linux-hardware.org/?probe=6c18625cb3) | Jun 27, 2022 |
| ASUSTek       | P5K                         | Desktop     | [e401eb71bc](https://linux-hardware.org/?probe=e401eb71bc) | Jun 27, 2022 |
| Lenovo        | YB1-X91F                    | Convertible | [0a0f43a4af](https://linux-hardware.org/?probe=0a0f43a4af) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [48cbc869da](https://linux-hardware.org/?probe=48cbc869da) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [ea31080862](https://linux-hardware.org/?probe=ea31080862) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | Notebook    | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | Notebook    | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [2d1c05fefc](https://linux-hardware.org/?probe=2d1c05fefc) | Jun 26, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [5047471b41](https://linux-hardware.org/?probe=5047471b41) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [874e7081c6](https://linux-hardware.org/?probe=874e7081c6) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [b91a1b0ded](https://linux-hardware.org/?probe=b91a1b0ded) | Jun 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | Notebook    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| Acer          | Aspire X1700                | Desktop     | [6a67f8cba0](https://linux-hardware.org/?probe=6a67f8cba0) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | Notebook    | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | Notebook    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | Notebook    | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | Notebook    | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | 18E7                        | Desktop     | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [5f5c3fcba9](https://linux-hardware.org/?probe=5f5c3fcba9) | Jun 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [a5d23b52d1](https://linux-hardware.org/?probe=a5d23b52d1) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d22ca1b39a](https://linux-hardware.org/?probe=d22ca1b39a) | Jun 12, 2022 |
| HP            | 1496                        | Desktop     | [d6fba97175](https://linux-hardware.org/?probe=d6fba97175) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 460 20EMCT... | Convertible | [2e1daf6e92](https://linux-hardware.org/?probe=2e1daf6e92) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a3ca1ea153](https://linux-hardware.org/?probe=a3ca1ea153) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |
| Alienware     | m15 R4                      | Notebook    | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [839663a1af](https://linux-hardware.org/?probe=839663a1af) | Jun 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [eb7ee3a693](https://linux-hardware.org/?probe=eb7ee3a693) | Jun 10, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| HP            | Compaq 6715b (GR667ET#AB... | Notebook    | [44de2345bb](https://linux-hardware.org/?probe=44de2345bb) | Jun 09, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [40c1095611](https://linux-hardware.org/?probe=40c1095611) | Jun 08, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [ceae668577](https://linux-hardware.org/?probe=ceae668577) | Jun 07, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [4ca91078a2](https://linux-hardware.org/?probe=4ca91078a2) | Jun 07, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [c46dcc9b6f](https://linux-hardware.org/?probe=c46dcc9b6f) | Jun 07, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 805E                        | All in one  | [68c1d719ea](https://linux-hardware.org/?probe=68c1d719ea) | Jun 05, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Lenovo        | 318D                        | All in one  | [266c9dd651](https://linux-hardware.org/?probe=266c9dd651) | Jun 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3dd8394bb5](https://linux-hardware.org/?probe=3dd8394bb5) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [1f88a2c07c](https://linux-hardware.org/?probe=1f88a2c07c) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [3cc513c431](https://linux-hardware.org/?probe=3cc513c431) | Jun 04, 2022 |
| Acer          | F90M R01-D1                 | Desktop     | [ecc8d1f955](https://linux-hardware.org/?probe=ecc8d1f955) | Jun 03, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb96d40d38](https://linux-hardware.org/?probe=bb96d40d38) | Jun 03, 2022 |
| eMachines     | eME732                      | Notebook    | [c6d57c850c](https://linux-hardware.org/?probe=c6d57c850c) | Jun 03, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [8c60f1e8e0](https://linux-hardware.org/?probe=8c60f1e8e0) | Jun 03, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2e621739e6](https://linux-hardware.org/?probe=2e621739e6) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [3210714de1](https://linux-hardware.org/?probe=3210714de1) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [9b01043ab8](https://linux-hardware.org/?probe=9b01043ab8) | Jun 03, 2022 |
| Chuwi         | UBOOK                       | Convertible | [6e2b3d6ee7](https://linux-hardware.org/?probe=6e2b3d6ee7) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | TX201LA                     | Notebook    | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | Notebook    | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [185587d5e1](https://linux-hardware.org/?probe=185587d5e1) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [65f67bae3c](https://linux-hardware.org/?probe=65f67bae3c) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [41cad28720](https://linux-hardware.org/?probe=41cad28720) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | Notebook    | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [c996bce6b5](https://linux-hardware.org/?probe=c996bce6b5) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | Notebook    | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fe1f2d0f](https://linux-hardware.org/?probe=08fe1f2d0f) | May 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1dfbe3337](https://linux-hardware.org/?probe=a1dfbe3337) | May 31, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [22b617425d](https://linux-hardware.org/?probe=22b617425d) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580abb0cf9](https://linux-hardware.org/?probe=580abb0cf9) | May 30, 2022 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [867e55cbfe](https://linux-hardware.org/?probe=867e55cbfe) | May 30, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [4c4e4e6690](https://linux-hardware.org/?probe=4c4e4e6690) | May 30, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [23d012c738](https://linux-hardware.org/?probe=23d012c738) | May 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [4fadee73e4](https://linux-hardware.org/?probe=4fadee73e4) | May 29, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [432c1135b8](https://linux-hardware.org/?probe=432c1135b8) | May 29, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [60128f5782](https://linux-hardware.org/?probe=60128f5782) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [b0e56c97d2](https://linux-hardware.org/?probe=b0e56c97d2) | May 28, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [774d5a9eae](https://linux-hardware.org/?probe=774d5a9eae) | May 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [b816732403](https://linux-hardware.org/?probe=b816732403) | May 27, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [475179d795](https://linux-hardware.org/?probe=475179d795) | May 27, 2022 |
| MSI           | PR600                       | Notebook    | [09b736e706](https://linux-hardware.org/?probe=09b736e706) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| Medion        | S6421 MD60703               | Notebook    | [9fffed019c](https://linux-hardware.org/?probe=9fffed019c) | May 27, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [e4082f489e](https://linux-hardware.org/?probe=e4082f489e) | May 27, 2022 |
| HP            | 8767 A                      | Desktop     | [553a8de02a](https://linux-hardware.org/?probe=553a8de02a) | May 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4673dbdffc](https://linux-hardware.org/?probe=4673dbdffc) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0d0af584d5](https://linux-hardware.org/?probe=0d0af584d5) | May 26, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [57d71fca8a](https://linux-hardware.org/?probe=57d71fca8a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [cca34ae407](https://linux-hardware.org/?probe=cca34ae407) | May 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d998776096](https://linux-hardware.org/?probe=d998776096) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [29dd7760ba](https://linux-hardware.org/?probe=29dd7760ba) | May 25, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [2ab0d31bce](https://linux-hardware.org/?probe=2ab0d31bce) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | Notebook    | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ca5eb0e4ff](https://linux-hardware.org/?probe=ca5eb0e4ff) | May 24, 2022 |
| MSI           | Prestige 15 A11SCS          | Notebook    | [2433529434](https://linux-hardware.org/?probe=2433529434) | May 24, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [bb4ce9afdd](https://linux-hardware.org/?probe=bb4ce9afdd) | May 24, 2022 |
| Unknown       | Aspire E                    | Notebook    | [d437b15b97](https://linux-hardware.org/?probe=d437b15b97) | May 24, 2022 |
| Unknown       | Aspire E                    | Notebook    | [f46b38824f](https://linux-hardware.org/?probe=f46b38824f) | May 24, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [dbc555961b](https://linux-hardware.org/?probe=dbc555961b) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| HP            | 15                          | Notebook    | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8cd4fba0ca](https://linux-hardware.org/?probe=8cd4fba0ca) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c4c8431707](https://linux-hardware.org/?probe=c4c8431707) | May 22, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [eda69f1faf](https://linux-hardware.org/?probe=eda69f1faf) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a8e1b16b1b](https://linux-hardware.org/?probe=a8e1b16b1b) | May 22, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [85fe027fff](https://linux-hardware.org/?probe=85fe027fff) | May 22, 2022 |
| Dell          | G15 5510                    | Notebook    | [0ca1f736f9](https://linux-hardware.org/?probe=0ca1f736f9) | May 22, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [c146b79bd6](https://linux-hardware.org/?probe=c146b79bd6) | May 22, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [a4275c42f4](https://linux-hardware.org/?probe=a4275c42f4) | May 22, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| Packard Be... | MCP73PV                     | Desktop     | [14085bdcf2](https://linux-hardware.org/?probe=14085bdcf2) | May 20, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [2f1ec161d1](https://linux-hardware.org/?probe=2f1ec161d1) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [42315f5cab](https://linux-hardware.org/?probe=42315f5cab) | May 19, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [48e5424ecb](https://linux-hardware.org/?probe=48e5424ecb) | May 19, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [a941ac6fa0](https://linux-hardware.org/?probe=a941ac6fa0) | May 19, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [189b62a372](https://linux-hardware.org/?probe=189b62a372) | May 19, 2022 |
| HP            | 8924 0100                   | All in one  | [67c69eba1d](https://linux-hardware.org/?probe=67c69eba1d) | May 19, 2022 |
| HP            | 8924 0100                   | All in one  | [496b64fffa](https://linux-hardware.org/?probe=496b64fffa) | May 19, 2022 |
| HP            | 8591                        | Desktop     | [60c5d4f8ca](https://linux-hardware.org/?probe=60c5d4f8ca) | May 19, 2022 |
| Dell          | Latitude E4310              | Notebook    | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| HP            | 8591                        | Desktop     | [fd05ae27e7](https://linux-hardware.org/?probe=fd05ae27e7) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [badf4d0a88](https://linux-hardware.org/?probe=badf4d0a88) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [7d96e10672](https://linux-hardware.org/?probe=7d96e10672) | May 17, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| HP            | 8924 0100                   | All in one  | [ba5d4617f9](https://linux-hardware.org/?probe=ba5d4617f9) | May 17, 2022 |
| Lenovo        | G580 2189                   | Notebook    | [e7de790c8a](https://linux-hardware.org/?probe=e7de790c8a) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| HP            | 885E A01                    | All in one  | [6b6dd9140a](https://linux-hardware.org/?probe=6b6dd9140a) | May 16, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [bccdb55064](https://linux-hardware.org/?probe=bccdb55064) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [70cde2437b](https://linux-hardware.org/?probe=70cde2437b) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS0LE00    | Notebook    | [59eecf466b](https://linux-hardware.org/?probe=59eecf466b) | May 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [dd305c13de](https://linux-hardware.org/?probe=dd305c13de) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| HP            | 8433 11                     | Desktop     | [d3f305a093](https://linux-hardware.org/?probe=d3f305a093) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [f367f3bb66](https://linux-hardware.org/?probe=f367f3bb66) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e1fc077918](https://linux-hardware.org/?probe=e1fc077918) | May 14, 2022 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2ac5991afa](https://linux-hardware.org/?probe=2ac5991afa) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| Medion        | Z370H4-EM                   | Desktop     | [2030abcd26](https://linux-hardware.org/?probe=2030abcd26) | May 12, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [8134289438](https://linux-hardware.org/?probe=8134289438) | May 12, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8328bbecb9](https://linux-hardware.org/?probe=8328bbecb9) | May 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a6f3293aea](https://linux-hardware.org/?probe=a6f3293aea) | May 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4f5ac891f4](https://linux-hardware.org/?probe=4f5ac891f4) | May 11, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f720d9e031](https://linux-hardware.org/?probe=f720d9e031) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e6d1749248](https://linux-hardware.org/?probe=e6d1749248) | May 10, 2022 |
| MSI           | Modern 14 B11MO             | Notebook    | [75bc7c18db](https://linux-hardware.org/?probe=75bc7c18db) | May 10, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [02925e8fac](https://linux-hardware.org/?probe=02925e8fac) | May 10, 2022 |
| Acer          | TravelMate 6592             | Notebook    | [353516147d](https://linux-hardware.org/?probe=353516147d) | May 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ae80aa69fe](https://linux-hardware.org/?probe=ae80aa69fe) | May 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ceaf962cba](https://linux-hardware.org/?probe=ceaf962cba) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| ECS           | H81H3-I                     | Desktop     | [e184359c46](https://linux-hardware.org/?probe=e184359c46) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f269fd3294](https://linux-hardware.org/?probe=f269fd3294) | May 09, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [29c0818bcd](https://linux-hardware.org/?probe=29c0818bcd) | May 08, 2022 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [39f623cf4d](https://linux-hardware.org/?probe=39f623cf4d) | May 08, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [1d37964706](https://linux-hardware.org/?probe=1d37964706) | May 08, 2022 |
| MSI           | GE62 2QD                    | Notebook    | [cef8637026](https://linux-hardware.org/?probe=cef8637026) | May 08, 2022 |
| SLIMBOOK      | Essential15L                | Notebook    | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | Notebook    | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [255ff705ac](https://linux-hardware.org/?probe=255ff705ac) | May 07, 2022 |
| Acer          | Aspire M1935                | Desktop     | [a679a25c13](https://linux-hardware.org/?probe=a679a25c13) | May 07, 2022 |
| Acer          | Aspire M1935                | Desktop     | [62424ad96d](https://linux-hardware.org/?probe=62424ad96d) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [c0d0f6435b](https://linux-hardware.org/?probe=c0d0f6435b) | May 06, 2022 |
| HP            | 84FD                        | Desktop     | [f99c153a46](https://linux-hardware.org/?probe=f99c153a46) | May 06, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| Dell          | Latitude 5420               | Notebook    | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Compaq 15                   | Notebook    | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [1467c3bb41](https://linux-hardware.org/?probe=1467c3bb41) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [e8556f4acf](https://linux-hardware.org/?probe=e8556f4acf) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [917add86ab](https://linux-hardware.org/?probe=917add86ab) | May 05, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [c5fc878a83](https://linux-hardware.org/?probe=c5fc878a83) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| ASRock        | FM2A78M Pro4+               | Desktop     | [7a00557ba5](https://linux-hardware.org/?probe=7a00557ba5) | May 05, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [d6293e8334](https://linux-hardware.org/?probe=d6293e8334) | May 05, 2022 |
| HP            | 1998                        | Desktop     | [b35fc936e5](https://linux-hardware.org/?probe=b35fc936e5) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [0afdbf373d](https://linux-hardware.org/?probe=0afdbf373d) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a30b11f1a0](https://linux-hardware.org/?probe=a30b11f1a0) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ecc7f176ff](https://linux-hardware.org/?probe=ecc7f176ff) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| Acer          | Aspire one 1-131            | Notebook    | [ade813cf7f](https://linux-hardware.org/?probe=ade813cf7f) | May 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d30c5337d6](https://linux-hardware.org/?probe=d30c5337d6) | May 02, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [37dfe53a95](https://linux-hardware.org/?probe=37dfe53a95) | May 02, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [aff42aff28](https://linux-hardware.org/?probe=aff42aff28) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0698d33be4](https://linux-hardware.org/?probe=0698d33be4) | May 02, 2022 |
| MSI           | H170A PC MATE               | Desktop     | [3ebb871ecc](https://linux-hardware.org/?probe=3ebb871ecc) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Notebook                    | Notebook    | [3bdd2a5e96](https://linux-hardware.org/?probe=3bdd2a5e96) | May 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Lenovo        | ThinkCentre M58p 6137E61    | Desktop     | [dbf0d596fc](https://linux-hardware.org/?probe=dbf0d596fc) | May 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| HP            | 650                         | Notebook    | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | TravelMate 6592             | Notebook    | [7d4878ff33](https://linux-hardware.org/?probe=7d4878ff33) | Apr 29, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [dc1c531e45](https://linux-hardware.org/?probe=dc1c531e45) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | Notebook    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | Desktop     | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [c3dad3331c](https://linux-hardware.org/?probe=c3dad3331c) | Apr 28, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| ASUSTek       | Maximus II Formula          | Desktop     | [66a4342140](https://linux-hardware.org/?probe=66a4342140) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| MSI           | H170A PC MATE               | Desktop     | [558be4bee8](https://linux-hardware.org/?probe=558be4bee8) | Apr 26, 2022 |
| Dell          | G15 5510                    | Notebook    | [5126d58147](https://linux-hardware.org/?probe=5126d58147) | Apr 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [3fcb247b21](https://linux-hardware.org/?probe=3fcb247b21) | Apr 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [23747b18ed](https://linux-hardware.org/?probe=23747b18ed) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [a1ff9cf092](https://linux-hardware.org/?probe=a1ff9cf092) | Apr 24, 2022 |
| MSI           | GX700                       | Notebook    | [b2cc52d381](https://linux-hardware.org/?probe=b2cc52d381) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | Notebook    | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [347ded3d71](https://linux-hardware.org/?probe=347ded3d71) | Apr 23, 2022 |
| Foxconn       | 945 7AD Series              | Desktop     | [04346c58f5](https://linux-hardware.org/?probe=04346c58f5) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [14089322a6](https://linux-hardware.org/?probe=14089322a6) | Apr 23, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| Lenovo        | ThinkPad P53 20QN000ESP     | Notebook    | [16b3189bd8](https://linux-hardware.org/?probe=16b3189bd8) | Apr 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7d38b3b29f](https://linux-hardware.org/?probe=7d38b3b29f) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [61d45f784c](https://linux-hardware.org/?probe=61d45f784c) | Apr 21, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [18578239d6](https://linux-hardware.org/?probe=18578239d6) | Apr 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [8034b9ae8c](https://linux-hardware.org/?probe=8034b9ae8c) | Apr 21, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [37ec4fb91d](https://linux-hardware.org/?probe=37ec4fb91d) | Apr 21, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [e1c710c88f](https://linux-hardware.org/?probe=e1c710c88f) | Apr 21, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [8e6566a555](https://linux-hardware.org/?probe=8e6566a555) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0ceaadd5e3](https://linux-hardware.org/?probe=0ceaadd5e3) | Apr 20, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [bc5f8558f3](https://linux-hardware.org/?probe=bc5f8558f3) | Apr 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| eMachines     | D730                        | Notebook    | [09350021b3](https://linux-hardware.org/?probe=09350021b3) | Apr 20, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a9126e3886](https://linux-hardware.org/?probe=a9126e3886) | Apr 19, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | Notebook    | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a5584e7ec2](https://linux-hardware.org/?probe=a5584e7ec2) | Apr 18, 2022 |
| Chuwi         | Unknown                     | Notebook    | [a44bd392c5](https://linux-hardware.org/?probe=a44bd392c5) | Apr 18, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [10e97d2168](https://linux-hardware.org/?probe=10e97d2168) | Apr 18, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [c278a421cd](https://linux-hardware.org/?probe=c278a421cd) | Apr 18, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [fb3e0b6b22](https://linux-hardware.org/?probe=fb3e0b6b22) | Apr 18, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [e693d05883](https://linux-hardware.org/?probe=e693d05883) | Apr 17, 2022 |
| Unknown       | Unknown                     | All in one  | [85f7750f62](https://linux-hardware.org/?probe=85f7750f62) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4058d0c1ca](https://linux-hardware.org/?probe=4058d0c1ca) | Apr 17, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [d921190f7e](https://linux-hardware.org/?probe=d921190f7e) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [4ce545cc86](https://linux-hardware.org/?probe=4ce545cc86) | Apr 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a016ec1bce](https://linux-hardware.org/?probe=a016ec1bce) | Apr 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [65edd32378](https://linux-hardware.org/?probe=65edd32378) | Apr 16, 2022 |
| ASUSTek       | P5VD2-MX                    | Desktop     | [57fec52891](https://linux-hardware.org/?probe=57fec52891) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | Notebook    | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Medion        | MS-7728                     | Desktop     | [443a5ff3dd](https://linux-hardware.org/?probe=443a5ff3dd) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| Toshiba       | NB520                       | Notebook    | [105666a973](https://linux-hardware.org/?probe=105666a973) | Apr 15, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [72af1b2afe](https://linux-hardware.org/?probe=72af1b2afe) | Apr 15, 2022 |
| AMI           | Intel                       | Notebook    | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | Notebook    | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [55b07b48b3](https://linux-hardware.org/?probe=55b07b48b3) | Apr 14, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [48794f7ff0](https://linux-hardware.org/?probe=48794f7ff0) | Apr 14, 2022 |
| SLIMBOOK      | PRO                         | Notebook    | [97f545c3d4](https://linux-hardware.org/?probe=97f545c3d4) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [45b5664eb1](https://linux-hardware.org/?probe=45b5664eb1) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | Notebook    | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [558d84adac](https://linux-hardware.org/?probe=558d84adac) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [f0f5bfea81](https://linux-hardware.org/?probe=f0f5bfea81) | Apr 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [63f76ffc2b](https://linux-hardware.org/?probe=63f76ffc2b) | Apr 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [3a9245cdab](https://linux-hardware.org/?probe=3a9245cdab) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [0fbee9d8dc](https://linux-hardware.org/?probe=0fbee9d8dc) | Apr 13, 2022 |
| Gateway       | DS71                        | Desktop     | [3bd1ad84ce](https://linux-hardware.org/?probe=3bd1ad84ce) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [1acc227c33](https://linux-hardware.org/?probe=1acc227c33) | Apr 13, 2022 |
| Sony          | VGN-NW21EF_S                | Notebook    | [4ade997baf](https://linux-hardware.org/?probe=4ade997baf) | Apr 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c5c12d6818](https://linux-hardware.org/?probe=c5c12d6818) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [a5bf5ddddf](https://linux-hardware.org/?probe=a5bf5ddddf) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [760d46f52e](https://linux-hardware.org/?probe=760d46f52e) | Apr 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [19ccaef18f](https://linux-hardware.org/?probe=19ccaef18f) | Apr 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dabfb4bb05](https://linux-hardware.org/?probe=dabfb4bb05) | Apr 11, 2022 |
| Gigabyte      | Q67M-D2H                    | Desktop     | [c95352a142](https://linux-hardware.org/?probe=c95352a142) | Apr 10, 2022 |
| ASUSTek       | Z87-WS                      | Desktop     | [7706049c53](https://linux-hardware.org/?probe=7706049c53) | Apr 10, 2022 |
| Medion        | MS-7366                     | Desktop     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [22502631b3](https://linux-hardware.org/?probe=22502631b3) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9cc7cc23d6](https://linux-hardware.org/?probe=9cc7cc23d6) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3845180872](https://linux-hardware.org/?probe=3845180872) | Apr 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 702       | 15.34%  |
| Ubuntu 18.04      | 501       | 10.95%  |
| OpenMandriva 4.2  | 181       | 3.95%   |
| Debian 11         | 174       | 3.8%    |
| Ubuntu 22.04      | 121       | 2.64%   |
| KDE neon 20.04    | 110       | 2.4%    |
| OpenMandriva 4.3  | 100       | 2.18%   |
| Debian 10         | 80        | 1.75%   |
| Ubuntu 20.10      | 72        | 1.57%   |
| Manjaro           | 70        | 1.53%   |
| Linux Mint 19.3   | 70        | 1.53%   |
| Zorin 16          | 67        | 1.46%   |
| Arch              | 65        | 1.42%   |
| Linux Mint 20.3   | 64        | 1.4%    |
| Ubuntu 19.04      | 61        | 1.33%   |
| Xubuntu 20.04     | 60        | 1.31%   |
| Ubuntu 19.10      | 58        | 1.27%   |
| Linux Mint 20.1   | 57        | 1.25%   |
| Ubuntu 21.04      | 53        | 1.16%   |
| Linux Mint 20     | 52        | 1.14%   |
| Arch Rolling      | 52        | 1.14%   |
| Ubuntu 21.10      | 50        | 1.09%   |
| Fedora 35         | 47        | 1.03%   |
| Xubuntu 18.04     | 46        | 1.01%   |
| Linux Mint 20.2   | 46        | 1.01%   |
| Fedora 36         | 46        | 1.01%   |
| ROSA R10          | 43        | 0.94%   |
| Kubuntu 20.04     | 42        | 0.92%   |
| Fedora 34         | 40        | 0.87%   |
| Zorin 15          | 39        | 0.85%   |
| Pop!_OS 20.04     | 37        | 0.81%   |
| Fedora 33         | 37        | 0.81%   |
| Ubuntu 18.10      | 33        | 0.72%   |
| Linux Mint 19.2   | 30        | 0.66%   |
| Ubuntu 16.04      | 29        | 0.63%   |
| Debian Testing    | 29        | 0.63%   |
| ROSA R11          | 28        | 0.61%   |
| BlackPanther 18.1 | 26        | 0.57%   |
| Fedora 32         | 25        | 0.55%   |
| Ubuntu MATE 20.04 | 24        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1610      | 37%     |
| Linux Mint    | 350       | 8.04%   |
| OpenMandriva  | 306       | 7.03%   |
| Debian        | 301       | 6.92%   |
| Fedora        | 206       | 4.73%   |
| Manjaro       | 166       | 3.82%   |
| KDE neon      | 122       | 2.8%    |
| Endless       | 121       | 2.78%   |
| Xubuntu       | 120       | 2.76%   |
| Arch          | 115       | 2.64%   |
| Zorin         | 111       | 2.55%   |
| ROSA          | 106       | 2.44%   |
| Pop!_OS       | 104       | 2.39%   |
| Kubuntu       | 88        | 2.02%   |
| Ubuntu MATE   | 48        | 1.1%    |
| Elementary    | 45        | 1.03%   |
| Gentoo        | 42        | 0.97%   |
| openSUSE      | 39        | 0.9%    |
| Ubuntu Unity  | 37        | 0.85%   |
| BlackPanther  | 28        | 0.64%   |
| ArcoLinux     | 28        | 0.64%   |
| Lubuntu       | 22        | 0.51%   |
| Kali          | 19        | 0.44%   |
| LMDE          | 18        | 0.41%   |
| Parrot        | 17        | 0.39%   |
| Clear Linux   | 15        | 0.34%   |
| MX            | 14        | 0.32%   |
| EndeavourOS   | 14        | 0.32%   |
| SteamOS       | 12        | 0.28%   |
| Ubuntu Budgie | 10        | 0.23%   |
| Reborn OS     | 8         | 0.18%   |
| CentOS        | 8         | 0.18%   |
| Garuda Linux  | 6         | 0.14%   |
| Deepin        | 6         | 0.14%   |
| Solus         | 5         | 0.11%   |
| RHEL          | 5         | 0.11%   |
| Peppermint    | 5         | 0.11%   |
| Nobara        | 4         | 0.09%   |
| UbuntuDDE     | 3         | 0.07%   |
| Ubuntu Studio | 3         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 3.55%   |
| 5.16.7-desktop-1omv4003         | 100       | 2%      |
| 5.4.0-42-generic                | 95        | 1.9%    |
| 5.4.0-58-generic                | 60        | 1.2%    |
| 5.10.0-8-amd64                  | 56        | 1.12%   |
| 5.4.0-52-generic                | 49        | 0.98%   |
| 5.4.0-54-generic                | 48        | 0.96%   |
| 5.4.0-26-generic                | 47        | 0.94%   |
| 5.3.0-28-generic                | 42        | 0.84%   |
| 5.4.0-48-generic                | 39        | 0.78%   |
| 5.3.0-40-generic                | 37        | 0.74%   |
| 5.11.0-27-generic               | 36        | 0.72%   |
| 5.0.0-37-generic                | 36        | 0.72%   |
| 5.4.0-29-generic                | 34        | 0.68%   |
| 5.3.0-46-generic                | 32        | 0.64%   |
| 5.4.0-65-generic                | 31        | 0.62%   |
| 5.11.0-43-generic               | 30        | 0.6%    |
| 5.0.0-32-generic                | 30        | 0.6%    |
| 5.4.0-72-generic                | 29        | 0.58%   |
| 5.4.0-40-generic                | 29        | 0.58%   |
| 5.13.0-30-generic               | 29        | 0.58%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.58%   |
| 5.4.0-47-generic                | 27        | 0.54%   |
| 5.4.0-37-generic                | 27        | 0.54%   |
| 5.3.0-51-generic                | 27        | 0.54%   |
| 5.15.0-52-generic               | 26        | 0.52%   |
| 5.15.0-48-generic               | 26        | 0.52%   |
| 5.13.0-39-generic               | 26        | 0.52%   |
| 5.13.0-28-generic               | 26        | 0.52%   |
| 5.11.0-41-generic               | 26        | 0.52%   |
| 5.8.0-43-generic                | 25        | 0.5%    |
| 5.10.0-18-amd64                 | 25        | 0.5%    |
| 5.8.0-44-generic                | 24        | 0.48%   |
| 5.11.0-37-generic               | 24        | 0.48%   |
| 5.4.0-70-generic                | 23        | 0.46%   |
| 5.3.0-45-generic                | 23        | 0.46%   |
| 5.15.0-50-generic               | 23        | 0.46%   |
| 5.15.0-47-generic               | 23        | 0.46%   |
| 5.8.0-48-generic                | 22        | 0.44%   |
| 5.4.0-56-generic                | 22        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 917       | 19.6%   |
| 4.15.0  | 413       | 8.83%   |
| 5.11.0  | 270       | 5.77%   |
| 5.8.0   | 266       | 5.68%   |
| 5.3.0   | 254       | 5.43%   |
| 5.13.0  | 225       | 4.81%   |
| 5.15.0  | 215       | 4.59%   |
| 5.10.0  | 213       | 4.55%   |
| 5.0.0   | 198       | 4.23%   |
| 5.10.14 | 179       | 3.83%   |
| 4.18.0  | 113       | 2.42%   |
| 5.16.7  | 104       | 2.22%   |
| 4.19.0  | 82        | 1.75%   |
| 4.9.60  | 33        | 0.71%   |
| 5.19.0  | 23        | 0.49%   |
| 4.4.0   | 22        | 0.47%   |
| 4.18.16 | 22        | 0.47%   |
| 5.14.0  | 18        | 0.38%   |
| 5.18.0  | 16        | 0.34%   |
| 5.9.16  | 15        | 0.32%   |
| 5.17.5  | 14        | 0.3%    |
| 5.9.0   | 13        | 0.28%   |
| 5.7.0   | 12        | 0.26%   |
| 5.3.18  | 12        | 0.26%   |
| 5.12.4  | 12        | 0.26%   |
| 4.9.20  | 12        | 0.26%   |
| 5.16.11 | 11        | 0.24%   |
| 5.16.0  | 11        | 0.24%   |
| 5.15.6  | 11        | 0.24%   |
| 5.8.11  | 10        | 0.21%   |
| 5.6.0   | 10        | 0.21%   |
| 5.15.32 | 10        | 0.21%   |
| 5.13.12 | 10        | 0.21%   |
| 5.11.12 | 10        | 0.21%   |
| 5.17.1  | 9         | 0.19%   |
| 5.15.15 | 9         | 0.19%   |
| 5.14.14 | 9         | 0.19%   |
| 5.11.11 | 9         | 0.19%   |
| 4.9.0   | 9         | 0.19%   |
| 5.19.9  | 8         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 979       | 21.14%  |
| 5.10    | 472       | 10.19%  |
| 4.15    | 413       | 8.92%   |
| 5.8     | 326       | 7.04%   |
| 5.11    | 326       | 7.04%   |
| 5.15    | 318       | 6.87%   |
| 5.3     | 282       | 6.09%   |
| 5.13    | 263       | 5.68%   |
| 5.0     | 202       | 4.36%   |
| 5.16    | 163       | 3.52%   |
| 4.18    | 136       | 2.94%   |
| 4.19    | 97        | 2.1%    |
| 4.9     | 79        | 1.71%   |
| 5.19    | 74        | 1.6%    |
| 5.14    | 70        | 1.51%   |
| 5.18    | 60        | 1.3%    |
| 5.9     | 52        | 1.12%   |
| 5.6     | 51        | 1.1%    |
| 5.17    | 46        | 0.99%   |
| 5.7     | 45        | 0.97%   |
| 5.12    | 44        | 0.95%   |
| 5.5     | 26        | 0.56%   |
| 4.4     | 26        | 0.56%   |
| 6.0     | 18        | 0.39%   |
| 4.1     | 9         | 0.19%   |
| 5.2     | 8         | 0.17%   |
| 5.1     | 7         | 0.15%   |
| 4.16    | 6         | 0.13%   |
| 3.10    | 6         | 0.13%   |
| 4.20    | 4         | 0.09%   |
| 4.17    | 4         | 0.09%   |
| 4.13    | 4         | 0.09%   |
| 4.8     | 3         | 0.06%   |
| 4.14    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 4.12    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |
| 3.18    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4001      | 95.22%  |
| i686    | 171       | 4.07%   |
| aarch64 | 23        | 0.55%   |
| armv7l  | 6         | 0.14%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1887      | 42.61%  |
| KDE5            | 706       | 15.94%  |
| Unknown         | 617       | 13.93%  |
| XFCE            | 323       | 7.29%   |
| X-Cinnamon      | 266       | 6.01%   |
| KDE             | 157       | 3.54%   |
| MATE            | 139       | 3.14%   |
| KDE4            | 47        | 1.06%   |
| Cinnamon        | 46        | 1.04%   |
| Pantheon        | 41        | 0.93%   |
| Unity           | 36        | 0.81%   |
| LXQt            | 34        | 0.77%   |
| i3              | 25        | 0.56%   |
| Budgie          | 19        | 0.43%   |
| LXDE            | 18        | 0.41%   |
| Deepin          | 18        | 0.41%   |
| GNOME Flashback | 13        | 0.29%   |
| Openbox         | 8         | 0.18%   |
| qtile           | 4         | 0.09%   |
| GNOME Classic   | 4         | 0.09%   |
| bspwm           | 4         | 0.09%   |
| Enlightenment   | 3         | 0.07%   |
| DWM             | 3         | 0.07%   |
| xmonad          | 2         | 0.05%   |
| Trinity         | 2         | 0.05%   |
| river           | 1         | 0.02%   |
| Lubuntu         | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| i3-with-shmlog  | 1         | 0.02%   |
| fvwm            | 1         | 0.02%   |
| Cutefish        | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3467      | 80.2%   |
| Wayland | 466       | 10.78%  |
| Unknown | 329       | 7.61%   |
| Tty     | 61        | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2448      | 56.15%  |
| SDDM    | 632       | 14.5%   |
| GDM     | 497       | 11.4%   |
| LightDM | 283       | 6.49%   |
| GDM3    | 278       | 6.38%   |
| TDM     | 150       | 3.44%   |
| KDM     | 47        | 1.08%   |
| XDM     | 13        | 0.3%    |
| Ly      | 5         | 0.11%   |
| LXDM    | 4         | 0.09%   |
| SLiM    | 3         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 2498      | 57.72%  |
| en_US          | 682       | 15.76%  |
| Unknown        | 632       | 14.6%   |
| ca_ES          | 157       | 3.63%   |
| en_GB          | 88        | 2.03%   |
| C              | 41        | 0.95%   |
| gl_ES          | 31        | 0.72%   |
| de_DE          | 27        | 0.62%   |
| eu_ES          | 21        | 0.49%   |
| fr_FR          | 18        | 0.42%   |
| ru_RU          | 16        | 0.37%   |
| it_IT          | 11        | 0.25%   |
| an_ES          | 10        | 0.23%   |
| es_MX          | 9         | 0.21%   |
| es_AR          | 7         | 0.16%   |
| pt_BR          | 6         | 0.14%   |
| en_IE          | 6         | 0.14%   |
| ca_AD          | 6         | 0.14%   |
| C.UTF8         | 5         | 0.12%   |
| ro_RO          | 4         | 0.09%   |
| pl_PL          | 4         | 0.09%   |
| nl_NL          | 3         | 0.07%   |
| fr_BE          | 3         | 0.07%   |
| es_ES.UTF8     | 3         | 0.07%   |
| en_AG          | 3         | 0.07%   |
| ca_ES@valencia | 3         | 0.07%   |
| pt_PT          | 2         | 0.05%   |
| POSIX          | 2         | 0.05%   |
| fr_CH          | 2         | 0.05%   |
| es_US          | 2         | 0.05%   |
| es_BO          | 2         | 0.05%   |
| en_DK          | 2         | 0.05%   |
| en_AU          | 2         | 0.05%   |
| bg_BG          | 2         | 0.05%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |
| et_EE          | 1         | 0.02%   |
| es_VE          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2263      | 52.7%   |
| EFI  | 2031      | 47.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3360      | 78.25%  |
| Overlay  | 342       | 7.96%   |
| Btrfs    | 242       | 5.64%   |
| Unknown  | 212       | 4.94%   |
| Xfs      | 57        | 1.33%   |
| Ext3     | 32        | 0.75%   |
| Zfs      | 18        | 0.42%   |
| Ext2     | 15        | 0.35%   |
| Tmpfs    | 7         | 0.16%   |
| Reiserfs | 4         | 0.09%   |
| Jfs      | 2         | 0.05%   |
| Aufs     | 2         | 0.05%   |
| F2fs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2651      | 61.69%  |
| GPT     | 1209      | 28.14%  |
| MBR     | 437       | 10.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3604      | 83.91%  |
| Yes       | 691       | 16.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2865      | 66.89%  |
| Yes       | 1418      | 33.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 820       | 19.52%  |
| Hewlett-Packard         | 599       | 14.26%  |
| Lenovo                  | 494       | 11.76%  |
| MSI                     | 358       | 8.52%   |
| Gigabyte Technology     | 349       | 8.31%   |
| Acer                    | 282       | 6.71%   |
| Dell                    | 267       | 6.36%   |
| ASRock                  | 111       | 2.64%   |
| Toshiba                 | 99        | 2.36%   |
| Apple                   | 95        | 2.26%   |
| Intel                   | 62        | 1.48%   |
| Unknown                 | 58        | 1.38%   |
| Packard Bell            | 40        | 0.95%   |
| Sony                    | 35        | 0.83%   |
| Medion                  | 34        | 0.81%   |
| Chuwi                   | 31        | 0.74%   |
| HUAWEI                  | 28        | 0.67%   |
| Samsung Electronics     | 26        | 0.62%   |
| Notebook                | 25        | 0.6%    |
| SLIMBOOK                | 24        | 0.57%   |
| Fujitsu                 | 20        | 0.48%   |
| Raspberry Pi Foundation | 19        | 0.45%   |
| LG Electronics          | 19        | 0.45%   |
| Pegatron                | 17        | 0.4%    |
| eMachines               | 17        | 0.4%    |
| ECS                     | 16        | 0.38%   |
| Teclast                 | 12        | 0.29%   |
| Fujitsu Siemens         | 12        | 0.29%   |
| BESSTAR Tech            | 12        | 0.29%   |
| Timi                    | 11        | 0.26%   |
| Foxconn                 | 11        | 0.26%   |
| Huanan                  | 10        | 0.24%   |
| AMI                     | 10        | 0.24%   |
| Valve                   | 9         | 0.21%   |
| Supermicro              | 7         | 0.17%   |
| Clevo                   | 7         | 0.17%   |
| Shuttle                 | 6         | 0.14%   |
| IBM                     | 6         | 0.14%   |
| AZW                     | 6         | 0.14%   |
| Microsoft               | 5         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 83        | 1.98%   |
| ASUS All Series                            | 50        | 1.19%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.52%   |
| HP Pavilion g6                             | 20        | 0.48%   |
| HP Pavilion dv6                            | 19        | 0.45%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.43%   |
| HP Notebook                                | 16        | 0.38%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.36%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 14        | 0.33%   |
| MSI MS-7C37                                | 11        | 0.26%   |
| RPi Raspberry Pi                           | 10        | 0.24%   |
| MSI MS-7817                                | 10        | 0.24%   |
| HP Laptop 15-da0xxx                        | 10        | 0.24%   |
| HP G62                                     | 10        | 0.24%   |
| Gigabyte 970A-DS3P                         | 10        | 0.24%   |
| Dell XPS 13 7390                           | 10        | 0.24%   |
| ASUS P5G41T-M LX                           | 10        | 0.24%   |
| Valve Jupiter                              | 9         | 0.21%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.21%   |
| Gigabyte B450M DS3H                        | 9         | 0.21%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.19%   |
| MSI MS-7B79                                | 8         | 0.19%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.19%   |
| HP Pavilion 15                             | 8         | 0.19%   |
| Gigabyte H110M-S2H                         | 8         | 0.19%   |
| ASUS X540NA                                | 8         | 0.19%   |
| ASUS PRIME B450M-A                         | 8         | 0.19%   |
| ASUS PRIME A320M-K                         | 8         | 0.19%   |
| MSI MS-7C02                                | 7         | 0.17%   |
| MSI MS-7B86                                | 7         | 0.17%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.17%   |
| Lenovo G50-70 20351                        | 7         | 0.17%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.17%   |
| HP Pavilion dv7                            | 7         | 0.17%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.17%   |
| Gigabyte H61M-DS2                          | 7         | 0.17%   |
| Gigabyte B450 AORUS M                      | 7         | 0.17%   |
| ASUS X555LAB                               | 7         | 0.17%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 7         | 0.17%   |
| ASUS P5K                                   | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 203       | 4.83%   |
| Lenovo ThinkPad       | 157       | 3.74%   |
| HP Pavilion           | 132       | 3.14%   |
| Lenovo IdeaPad        | 115       | 2.74%   |
| HP Compaq             | 83        | 1.98%   |
| Unknown               | 83        | 1.98%   |
| Dell Latitude         | 79        | 1.88%   |
| Toshiba Satellite     | 78        | 1.86%   |
| ASUS PRIME            | 68        | 1.62%   |
| ASUS VivoBook         | 66        | 1.57%   |
| HP Laptop             | 64        | 1.52%   |
| HP EliteBook          | 55        | 1.31%   |
| ASUS TUF              | 54        | 1.29%   |
| Dell XPS              | 53        | 1.26%   |
| ASUS ROG              | 53        | 1.26%   |
| ASUS All              | 50        | 1.19%   |
| Lenovo ThinkCentre    | 48        | 1.14%   |
| Dell OptiPlex         | 44        | 1.05%   |
| HP ProBook            | 36        | 0.86%   |
| Dell Inspiron         | 36        | 0.86%   |
| ASUS ZenBook          | 32        | 0.76%   |
| Packard Bell EasyNote | 28        | 0.67%   |
| HP 250                | 28        | 0.67%   |
| MSI Prestige          | 24        | 0.57%   |
| Lenovo Yoga           | 22        | 0.52%   |
| Gigabyte X570         | 20        | 0.48%   |
| RPi Raspberry         | 19        | 0.45%   |
| HP OMEN               | 19        | 0.45%   |
| Dell Precision        | 18        | 0.43%   |
| Acer Extensa          | 17        | 0.4%    |
| MSI Modern            | 16        | 0.38%   |
| Lenovo ThinkBook      | 16        | 0.38%   |
| Lenovo Legion         | 16        | 0.38%   |
| HP Notebook           | 16        | 0.38%   |
| HP ENVY               | 16        | 0.38%   |
| Acer TravelMate       | 16        | 0.38%   |
| Gigabyte B450M        | 15        | 0.36%   |
| ASUS ASUS             | 15        | 0.36%   |
| Gigabyte B450         | 14        | 0.33%   |
| HP EliteDesk          | 13        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 445       | 10.6%   |
| 2019    | 405       | 9.64%   |
| 2020    | 355       | 8.45%   |
| 2014    | 299       | 7.12%   |
| 2013    | 277       | 6.6%    |
| 2017    | 260       | 6.19%   |
| 2012    | 259       | 6.17%   |
| 2011    | 255       | 6.07%   |
| 2015    | 239       | 5.69%   |
| 2010    | 233       | 5.55%   |
| 2021    | 220       | 5.24%   |
| 2008    | 212       | 5.05%   |
| 2009    | 206       | 4.9%    |
| 2016    | 198       | 4.71%   |
| 2007    | 147       | 3.5%    |
| 2006    | 81        | 1.93%   |
| 2022    | 44        | 1.05%   |
| Unknown | 29        | 0.69%   |
| 2005    | 22        | 0.52%   |
| 2004    | 7         | 0.17%   |
| 2003    | 3         | 0.07%   |
| 2002    | 2         | 0.05%   |
| 2001    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2310      | 55%     |
| Desktop        | 1611      | 38.36%  |
| All in one     | 69        | 1.64%   |
| Convertible    | 61        | 1.45%   |
| Mini pc        | 59        | 1.4%    |
| Tablet         | 35        | 0.83%   |
| System on chip | 26        | 0.62%   |
| Server         | 25        | 0.6%    |
| Phone          | 3         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3953      | 93.56%  |
| Enabled  | 272       | 6.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4195      | 99.88%  |
| Yes  | 5         | 0.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 934       | 21.88%  |
| 4.01-8.0        | 921       | 21.58%  |
| 16.01-24.0      | 874       | 20.48%  |
| 8.01-16.0       | 778       | 18.23%  |
| 32.01-64.0      | 325       | 7.61%   |
| 1.01-2.0        | 211       | 4.94%   |
| 2.01-3.0        | 73        | 1.71%   |
| 64.01-256.0     | 55        | 1.29%   |
| 0.51-1.0        | 55        | 1.29%   |
| 24.01-32.0      | 35        | 0.82%   |
| More than 256.0 | 4         | 0.09%   |
| 0.01-0.5        | 2         | 0.05%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1860      | 40.04%  |
| 2.01-3.0   | 1163      | 25.04%  |
| 4.01-8.0   | 550       | 11.84%  |
| 3.01-4.0   | 478       | 10.29%  |
| 0.51-1.0   | 381       | 8.2%    |
| 8.01-16.0  | 144       | 3.1%    |
| 0.01-0.5   | 54        | 1.16%   |
| 24.01-32.0 | 7         | 0.15%   |
| 16.01-24.0 | 6         | 0.13%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2598      | 59.85%  |
| 2       | 1075      | 24.76%  |
| 3       | 360       | 8.29%   |
| 4       | 152       | 3.5%    |
| 5       | 60        | 1.38%   |
| 0       | 38        | 0.88%   |
| 6       | 28        | 0.65%   |
| 7       | 11        | 0.25%   |
| 8       | 6         | 0.14%   |
| 9       | 5         | 0.12%   |
| 11      | 2         | 0.05%   |
| 10      | 2         | 0.05%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2457      | 57.95%  |
| Yes       | 1783      | 42.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3655      | 86.76%  |
| No        | 558       | 13.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3130      | 73.91%  |
| No        | 1105      | 26.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2357      | 55.42%  |
| No        | 1896      | 44.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 4200      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 676       | 14.79%  |
| Barcelona                  | 471       | 10.31%  |
| Seville                    | 157       | 3.44%   |
| Valencia                   | 154       | 3.37%   |
| Zaragoza                   | 69        | 1.51%   |
| Málaga                    | 60        | 1.31%   |
| Granada                    | 57        | 1.25%   |
| Sabadell                   | 46        | 1.01%   |
| Palma                      | 46        | 1.01%   |
| Valladolid                 | 42        | 0.92%   |
| Las Palmas de Gran Canaria | 41        | 0.9%    |
| Bilbao                     | 41        | 0.9%    |
| Vigo                       | 40        | 0.88%   |
| Alcobendas                 | 40        | 0.88%   |
| Córdoba                   | 38        | 0.83%   |
| Ourense                    | 37        | 0.81%   |
| Pamplona                   | 33        | 0.72%   |
| Murcia                     | 32        | 0.7%    |
| Alcalá de Henares         | 29        | 0.63%   |
| Gijón                     | 27        | 0.59%   |
| Donostia / San Sebastian   | 27        | 0.59%   |
| Almería                   | 25        | 0.55%   |
| Alicante                   | 25        | 0.55%   |
| A Coruña                  | 25        | 0.55%   |
| Oviedo                     | 24        | 0.53%   |
| Santiago de Compostela     | 23        | 0.5%    |
| Santa Cruz de Tenerife     | 23        | 0.5%    |
| León                      | 23        | 0.5%    |
| Barakaldo                  | 23        | 0.5%    |
| Vitoria-Gasteiz            | 21        | 0.46%   |
| Mostoles                   | 20        | 0.44%   |
| Burgos                     | 20        | 0.44%   |
| Albacete                   | 20        | 0.44%   |
| Santander                  | 19        | 0.42%   |
| Salamanca                  | 19        | 0.42%   |
| Reus                       | 17        | 0.37%   |
| Pontevedra                 | 17        | 0.37%   |
| Getxo                      | 17        | 0.37%   |
| Cartagena                  | 17        | 0.37%   |
| Terrassa                   | 15        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1078      | 1654   | 17.64%  |
| WDC                       | 878       | 1270   | 14.37%  |
| Samsung Electronics       | 792       | 1135   | 12.96%  |
| Kingston                  | 690       | 951    | 11.29%  |
| Toshiba                   | 473       | 703    | 7.74%   |
| SanDisk                   | 328       | 431    | 5.37%   |
| Unknown                   | 235       | 297    | 3.85%   |
| Crucial                   | 219       | 302    | 3.58%   |
| Hitachi                   | 200       | 240    | 3.27%   |
| SK hynix                  | 142       | 183    | 2.32%   |
| Intel                     | 127       | 162    | 2.08%   |
| HGST                      | 110       | 139    | 1.8%    |
| Micron Technology         | 83        | 94     | 1.36%   |
| China                     | 51        | 68     | 0.83%   |
| Phison                    | 47        | 53     | 0.77%   |
| Fujitsu                   | 43        | 49     | 0.7%    |
| Maxtor                    | 35        | 46     | 0.57%   |
| KIOXIA                    | 33        | 39     | 0.54%   |
| Apple                     | 32        | 46     | 0.52%   |
| OCZ                       | 28        | 35     | 0.46%   |
| Micron/Crucial Technology | 25        | 32     | 0.41%   |
| Silicon Motion            | 20        | 26     | 0.33%   |
| Netac                     | 20        | 27     | 0.33%   |
| JMicron Technology        | 20        | 21     | 0.33%   |
| LITEON                    | 19        | 20     | 0.31%   |
| Corsair                   | 19        | 24     | 0.31%   |
| A-DATA Technology         | 19        | 24     | 0.31%   |
| Transcend                 | 18        | 38     | 0.29%   |
| KingSpec                  | 18        | 24     | 0.29%   |
| KingDian                  | 16        | 18     | 0.26%   |
| Unknown                   | 15        | 17     | 0.25%   |
| USB30                     | 14        | 28     | 0.23%   |
| PNY                       | 13        | 20     | 0.21%   |
| KIOXIA-EXCERIA            | 12        | 17     | 0.2%    |
| EMTEC                     | 12        | 13     | 0.2%    |
| Patriot                   | 10        | 16     | 0.16%   |
| Drevo                     | 9         | 12     | 0.15%   |
| Teclast                   | 8         | 8      | 0.13%   |
| FORESEE                   | 8         | 9      | 0.13%   |
| Intenso                   | 7         | 9      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 227       | 3.38%   |
| Kingston SA400S37480G 480GB SSD        | 88        | 1.31%   |
| Seagate ST1000DM010-2EP102 1TB         | 81        | 1.21%   |
| Kingston SA400S37120G 120GB SSD        | 74        | 1.1%    |
| Seagate ST500DM002-1BD142 500GB        | 68        | 1.01%   |
| Kingston SV300S37A120G 120GB SSD       | 66        | 0.98%   |
| Seagate ST3500418AS 500GB              | 57        | 0.85%   |
| Samsung SSD 860 EVO 500GB              | 53        | 0.79%   |
| Unknown MMC Card  64GB                 | 50        | 0.75%   |
| Unknown MMC Card  32GB                 | 43        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB         | 43        | 0.64%   |
| Samsung SSD 850 EVO 500GB              | 41        | 0.61%   |
| Seagate ST500LT012-1DG142 500GB        | 40        | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB         | 40        | 0.6%    |
| Samsung SSD 850 EVO 250GB              | 40        | 0.6%    |
| Toshiba DT01ACA100 1TB                 | 39        | 0.58%   |
| Toshiba MQ01ABD100 1TB                 | 38        | 0.57%   |
| Crucial CT500MX500SSD1 500GB           | 37        | 0.55%   |
| Seagate ST9500325AS 500GB              | 36        | 0.54%   |
| Samsung NVMe SSD Drive 512GB           | 36        | 0.54%   |
| Samsung NVMe SSD Drive 500GB           | 36        | 0.54%   |
| Kingston SUV400S37240G 240GB SSD       | 36        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB         | 35        | 0.52%   |
| HGST HTS721010A9E630 1TB               | 35        | 0.52%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 0.51%   |
| Toshiba MQ01ABF050 500GB               | 33        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 33        | 0.49%   |
| SanDisk SSD PLUS 480GB                 | 33        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB           | 32        | 0.48%   |
| Kingston SV300S37A240G 240GB SSD       | 32        | 0.48%   |
| Seagate ST31000528AS 1TB               | 30        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB         | 30        | 0.45%   |
| Intel NVMe SSD Drive 512GB             | 30        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 28        | 0.42%   |
| Toshiba MQ04ABF100 1TB                 | 27        | 0.4%    |
| Toshiba MQ01ABD050 500GB               | 27        | 0.4%    |
| Unknown SD/MMC/MS PRO 1TB              | 26        | 0.39%   |
| Toshiba TR200 240GB SSD                | 26        | 0.39%   |
| Seagate Expansion 2TB                  | 26        | 0.39%   |
| Unknown MMC Card  128GB                | 24        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1069      | 1640   | 40.17%  |
| WDC                 | 693       | 996    | 26.04%  |
| Toshiba             | 341       | 471    | 12.81%  |
| Hitachi             | 200       | 240    | 7.52%   |
| HGST                | 110       | 139    | 4.13%   |
| Samsung Electronics | 109       | 136    | 4.1%    |
| Fujitsu             | 42        | 48     | 1.58%   |
| Maxtor              | 30        | 40     | 1.13%   |
| Unknown             | 26        | 31     | 0.98%   |
| Apple               | 14        | 18     | 0.53%   |
| USB3.0              | 5         | 5      | 0.19%   |
| ASMT                | 4         | 7      | 0.15%   |
| Hewlett-Packard     | 3         | 4      | 0.11%   |
| USB                 | 1         | 1      | 0.04%   |
| SABRENT             | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| OEM                 | 1         | 1      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| Inateck             | 1         | 1      | 0.04%   |
| IBM-207x            | 1         | 8      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Generic-            | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 633       | 870    | 30.52%  |
| Samsung Electronics | 365       | 503    | 17.6%   |
| SanDisk             | 204       | 254    | 9.84%   |
| Crucial             | 197       | 271    | 9.5%    |
| WDC                 | 109       | 151    | 5.26%   |
| Toshiba             | 90        | 161    | 4.34%   |
| China               | 49        | 66     | 2.36%   |
| SK hynix            | 34        | 38     | 1.64%   |
| Intel               | 32        | 48     | 1.54%   |
| Micron Technology   | 30        | 36     | 1.45%   |
| OCZ                 | 28        | 35     | 1.35%   |
| Netac               | 20        | 27     | 0.96%   |
| LITEON              | 18        | 18     | 0.87%   |
| KingSpec            | 18        | 24     | 0.87%   |
| Transcend           | 17        | 37     | 0.82%   |
| A-DATA Technology   | 16        | 21     | 0.77%   |
| KingDian            | 15        | 17     | 0.72%   |
| USB30               | 14        | 28     | 0.68%   |
| Apple               | 13        | 16     | 0.63%   |
| Emtec               | 10        | 11     | 0.48%   |
| PNY                 | 9         | 16     | 0.43%   |
| Patriot             | 9         | 15     | 0.43%   |
| KIOXIA-EXCERIA      | 9         | 13     | 0.43%   |
| Teclast             | 8         | 8      | 0.39%   |
| FORESEE             | 8         | 9      | 0.39%   |
| Corsair             | 8         | 11     | 0.39%   |
| Unknown             | 7         | 7      | 0.34%   |
| Intenso             | 6         | 7      | 0.29%   |
| GOODRAM             | 6         | 7      | 0.29%   |
| Drevo               | 6         | 8      | 0.29%   |
| Maxtor              | 5         | 6      | 0.24%   |
| LITEONIT            | 4         | 5      | 0.19%   |
| Hoodisk             | 4         | 5      | 0.19%   |
| BAITITON            | 4         | 4      | 0.19%   |
| Unknown             | 3         | 3      | 0.14%   |
| TCSUNBOW            | 3         | 3      | 0.14%   |
| Plextor             | 3         | 4      | 0.14%   |
| Hewlett-Packard     | 3         | 8      | 0.14%   |
| Dogfish             | 3         | 3      | 0.14%   |
| ASMT                | 3         | 3      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2269      | 3797   | 41.67%  |
| SSD     | 1793      | 2838   | 32.93%  |
| NVMe    | 1106      | 1533   | 20.31%  |
| MMC     | 213       | 278    | 3.91%   |
| Unknown | 64        | 81     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3260      | 6478   | 68.43%  |
| NVMe | 1094      | 1514   | 22.96%  |
| MMC  | 213       | 278    | 4.47%   |
| SAS  | 197       | 257    | 4.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2594      | 4238   | 62.22%  |
| 0.51-1.0   | 1112      | 1643   | 26.67%  |
| 1.01-2.0   | 298       | 459    | 7.15%   |
| 2.01-3.0   | 68        | 108    | 1.63%   |
| 3.01-4.0   | 66        | 115    | 1.58%   |
| 4.01-10.0  | 30        | 71     | 0.72%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1266      | 28.42%  |
| 251-500        | 1040      | 23.34%  |
| 501-1000       | 580       | 13.02%  |
| 1-20           | 328       | 7.36%   |
| 51-100         | 317       | 7.12%   |
| 1001-2000      | 301       | 6.76%   |
| 21-50          | 194       | 4.35%   |
| More than 3000 | 162       | 3.64%   |
| 2001-3000      | 157       | 3.52%   |
| Unknown        | 110       | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1822      | 39.29%  |
| 21-50          | 802       | 17.3%   |
| 101-250        | 592       | 12.77%  |
| 51-100         | 475       | 10.24%  |
| 251-500        | 338       | 7.29%   |
| 501-1000       | 244       | 5.26%   |
| 1001-2000      | 143       | 3.08%   |
| Unknown        | 110       | 2.37%   |
| More than 3000 | 60        | 1.29%   |
| 2001-3000      | 49        | 1.06%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 11        | 11     | 2.88%   |
| Kingston SV300S37A120G 120GB SSD   | 11        | 13     | 2.88%   |
| Seagate ST3500418AS 500GB          | 10        | 16     | 2.62%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 2.09%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 1.57%   |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 7      | 1.57%   |
| SanDisk SSD PLUS 480GB             | 5         | 6      | 1.31%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 6      | 1.05%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 1.05%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 1.05%   |
| Seagate ST3500320AS 500GB          | 4         | 7      | 1.05%   |
| Seagate ST31000528AS 1TB           | 4         | 5      | 1.05%   |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 7      | 1.05%   |
| HGST HTS545050A7E680 500GB         | 4         | 6      | 1.05%   |
| Drevo X1 SSD 64GB                  | 4         | 6      | 1.05%   |
| WDC WD20EZRX-00DC0B0 2TB           | 3         | 3      | 0.79%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 0.79%   |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.79%   |
| Seagate ST31500341AS 1TB           | 3         | 3      | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 3      | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 0.79%   |
| Samsung Electronics HD501LJ 500GB  | 3         | 3      | 0.79%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.79%   |
| HGST HTS721010A9E630 1TB           | 3         | 3      | 0.79%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.79%   |
| Fujitsu MHZ2250BH G2 250GB         | 3         | 4      | 0.79%   |
| WDC WD6400AAKS-22A7B0 640GB        | 2         | 2      | 0.52%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 0.52%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 2         | 2      | 0.52%   |
| WDC WD40EZRX-00SPEB0 4TB           | 2         | 3      | 0.52%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 2      | 0.52%   |
| WDC WD2500AAJS-00B4A0 250GB        | 2         | 2      | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 3      | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB            | 2         | 2      | 0.52%   |
| Toshiba Q300. 240GB SSD            | 2         | 2      | 0.52%   |
| Toshiba MQ01ABD075 752GB           | 2         | 3      | 0.52%   |
| Toshiba MK5076GSX 500GB            | 2         | 2      | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 2      | 0.52%   |
| Seagate ST3500830AS 500GB          | 2         | 3      | 0.52%   |
| Seagate ST3500820AS 500GB          | 2         | 2      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 130       | 167    | 34.76%  |
| WDC                 | 68        | 79     | 18.18%  |
| Hitachi             | 27        | 29     | 7.22%   |
| Samsung Electronics | 26        | 27     | 6.95%   |
| Toshiba             | 25        | 27     | 6.68%   |
| Kingston            | 20        | 26     | 5.35%   |
| HGST                | 14        | 17     | 3.74%   |
| SanDisk             | 10        | 11     | 2.67%   |
| Intel               | 9         | 9      | 2.41%   |
| Maxtor              | 7         | 7      | 1.87%   |
| Crucial             | 7         | 8      | 1.87%   |
| Fujitsu             | 6         | 7      | 1.6%    |
| Drevo               | 5         | 7      | 1.34%   |
| OCZ                 | 3         | 3      | 0.8%    |
| China               | 3         | 4      | 0.8%    |
| Micron Technology   | 2         | 2      | 0.53%   |
| KingDian            | 2         | 2      | 0.53%   |
| Transcend           | 1         | 4      | 0.27%   |
| SK hynix            | 1         | 1      | 0.27%   |
| Patriot             | 1         | 1      | 0.27%   |
| Intenso             | 1         | 1      | 0.27%   |
| IBM                 | 1         | 1      | 0.27%   |
| Hypertec            | 1         | 1      | 0.27%   |
| ASMT                | 1         | 2      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |
| A-DATA Technology   | 1         | 1      | 0.27%   |
| Unknown             | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 130       | 167    | 44.83%  |
| WDC                 | 66        | 77     | 22.76%  |
| Hitachi             | 27        | 29     | 9.31%   |
| Toshiba             | 20        | 22     | 6.9%    |
| Samsung Electronics | 16        | 17     | 5.52%   |
| HGST                | 14        | 17     | 4.83%   |
| Maxtor              | 7         | 7      | 2.41%   |
| Fujitsu             | 6         | 7      | 2.07%   |
| IBM                 | 1         | 1      | 0.34%   |
| China               | 1         | 1      | 0.34%   |
| ASMT                | 1         | 2      | 0.34%   |
| Apple               | 1         | 1      | 0.34%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 270       | 348    | 77.36%  |
| SSD  | 74        | 93     | 21.2%   |
| NVMe | 5         | 5      | 1.43%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 10%     |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 10%     |
| Seagate ST3500830AS 500GB         | 1         | 1      | 10%     |
| Seagate ST31000528AS 1TB          | 1         | 1      | 10%     |
| Seagate ST31000520AS 1TB          | 1         | 1      | 10%     |
| Seagate ST31000333AS 1TB          | 1         | 1      | 10%     |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 10%     |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 10%     |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 50%     |
| Samsung Electronics | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| Toshiba             | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2771      | 5514   | 60.94%  |
| Works    | 1431      | 2557   | 31.47%  |
| Malfunc  | 335       | 446    | 7.37%   |
| Failed   | 10        | 10     | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2895      | 57.03%  |
| AMD                              | 713       | 14.05%  |
| Samsung Electronics              | 374       | 7.37%   |
| SanDisk                          | 214       | 4.22%   |
| Nvidia                           | 100       | 1.97%   |
| SK hynix                         | 99        | 1.95%   |
| JMicron Technology               | 75        | 1.48%   |
| Phison Electronics               | 72        | 1.42%   |
| Kingston Technology Company      | 70        | 1.38%   |
| ASMedia Technology               | 70        | 1.38%   |
| Marvell Technology Group         | 57        | 1.12%   |
| Micron Technology                | 55        | 1.08%   |
| Toshiba America Info Systems     | 47        | 0.93%   |
| Micron/Crucial Technology        | 45        | 0.89%   |
| KIOXIA                           | 43        | 0.85%   |
| VIA Technologies                 | 31        | 0.61%   |
| Silicon Motion                   | 27        | 0.53%   |
| Silicon Integrated Systems [SiS] | 20        | 0.39%   |
| LSI Logic / Symbios Logic        | 11        | 0.22%   |
| Union Memory (Shenzhen)          | 7         | 0.14%   |
| Hewlett-Packard                  | 6         | 0.12%   |
| Silicon Image                    | 5         | 0.1%    |
| Apple                            | 5         | 0.1%    |
| Realtek Semiconductor            | 4         | 0.08%   |
| ADATA Technology                 | 4         | 0.08%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| Adaptec                          | 3         | 0.06%   |
| Unknown                          | 2         | 0.04%   |
| Seagate Technology               | 2         | 0.04%   |
| O2 Micro                         | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Lite-On Technology               | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Broadcom / LSI                   | 2         | 0.04%   |
| ULi Electronics                  | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 500       | 8.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 233       | 3.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 215       | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 208       | 3.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 132       | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 130       | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 120       | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 118       | 1.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 115       | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 112       | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 110       | 1.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 103       | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 89        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 85        | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 82        | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 82        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 77        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 75        | 1.25%   |
| Intel SATA Controller [RAID mode]                                                       | 74        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 74        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 74        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 73        | 1.22%   |
| Samsung NVMe SSD Controller 980                                                         | 70        | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 70        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 70        | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 69        | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 61        | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 60        | 1%      |
| Intel SSD 660P Series                                                                   | 59        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 59        | 0.98%   |
| Micron Non-Volatile memory controller                                                   | 55        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 52        | 0.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 51        | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 50        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 47        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 47        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 46        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 44        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 43        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 43        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2995      | 57.64%  |
| NVMe | 1108      | 21.32%  |
| IDE  | 758       | 14.59%  |
| RAID | 321       | 6.18%   |
| SCSI | 9         | 0.17%   |
| SAS  | 5         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3279      | 78.07%  |
| AMD          | 890       | 21.19%  |
| ARM          | 28        | 0.67%   |
| QUALCOMM     | 2         | 0.05%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 56        | 1.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 54        | 1.28%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.19%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 1.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 38        | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 35        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 33        | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 32        | 0.76%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 0.74%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 31        | 0.74%   |
| AMD Ryzen 5 3600 6-Core Processor             | 29        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 28        | 0.66%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 26        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 25        | 0.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 25        | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.55%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 23        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 22        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 22        | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.5%    |
| ARM Processor                                 | 21        | 0.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.5%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 20        | 0.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 20        | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.47%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 20        | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 18        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.43%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.43%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 18        | 0.43%   |
| AMD FX-8350 Eight-Core Processor              | 18        | 0.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 17        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 816       | 19.38%  |
| Intel Core i7           | 808       | 19.19%  |
| Intel Core i3           | 339       | 8.05%   |
| Intel Celeron           | 262       | 6.22%   |
| Other                   | 227       | 5.39%   |
| Intel Core 2 Duo        | 219       | 5.2%    |
| AMD Ryzen 5             | 208       | 4.94%   |
| AMD Ryzen 7             | 185       | 4.39%   |
| Intel Atom              | 124       | 2.94%   |
| Intel Xeon              | 90        | 2.14%   |
| Intel Pentium           | 77        | 1.83%   |
| Intel Pentium Dual-Core | 70        | 1.66%   |
| Intel Core 2 Quad       | 68        | 1.61%   |
| AMD FX                  | 56        | 1.33%   |
| Intel Pentium Dual      | 49        | 1.16%   |
| Intel Core 2            | 48        | 1.14%   |
| AMD A4                  | 42        | 1%      |
| AMD Ryzen 3             | 35        | 0.83%   |
| Intel Genuine           | 32        | 0.76%   |
| AMD Ryzen 9             | 32        | 0.76%   |
| AMD A6                  | 32        | 0.76%   |
| AMD A10                 | 28        | 0.66%   |
| AMD A8                  | 27        | 0.64%   |
| Intel Pentium 4         | 25        | 0.59%   |
| Intel Core i9           | 25        | 0.59%   |
| AMD Athlon 64 X2        | 23        | 0.55%   |
| AMD E1                  | 18        | 0.43%   |
| AMD Athlon II X2        | 18        | 0.43%   |
| AMD Athlon              | 18        | 0.43%   |
| AMD Phenom II X4        | 13        | 0.31%   |
| AMD Ryzen 7 PRO         | 11        | 0.26%   |
| AMD E                   | 11        | 0.26%   |
| Intel Pentium D         | 10        | 0.24%   |
| AMD Phenom              | 10        | 0.24%   |
| Intel Pentium M         | 9         | 0.21%   |
| Intel Pentium Silver    | 8         | 0.19%   |
| Intel Pentium Gold      | 7         | 0.17%   |
| Intel Core m3           | 7         | 0.17%   |
| Intel Celeron M         | 7         | 0.17%   |
| AMD Sempron             | 7         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1778      | 42.17%  |
| 4       | 1500      | 35.58%  |
| 6       | 377       | 8.94%   |
| 8       | 274       | 6.5%    |
| 1       | 167       | 3.96%   |
| 12      | 40        | 0.95%   |
| 3       | 19        | 0.45%   |
| 10      | 15        | 0.36%   |
| 16      | 14        | 0.33%   |
| Unknown | 13        | 0.31%   |
| 14      | 11        | 0.26%   |
| 20      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 32      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4165      | 99.14%  |
| 2       | 33        | 0.79%   |
| Unknown | 3         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2578      | 61.21%  |
| 1       | 1621      | 38.49%  |
| Unknown | 13        | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4015      | 94.96%  |
| Unknown        | 113       | 2.67%   |
| 32-bit         | 66        | 1.56%   |
| 64-bit         | 34        | 0.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 812       | 18.65%  |
| 0x306c3    | 243       | 5.58%   |
| 0x206a7    | 213       | 4.89%   |
| 0x306a9    | 195       | 4.48%   |
| 0x1067a    | 168       | 3.86%   |
| 0x906ea    | 132       | 3.03%   |
| 0x806ea    | 104       | 2.39%   |
| 0x6fd      | 99        | 2.27%   |
| 0x806c1    | 98        | 2.25%   |
| 0x506e3    | 94        | 2.16%   |
| 0x806ec    | 89        | 2.04%   |
| 0x40651    | 89        | 2.04%   |
| 0x20655    | 88        | 2.02%   |
| 0x806e9    | 81        | 1.86%   |
| 0x406e3    | 78        | 1.79%   |
| 0x306d4    | 73        | 1.68%   |
| 0x906e9    | 65        | 1.49%   |
| 0x08108109 | 58        | 1.33%   |
| 0x30678    | 53        | 1.22%   |
| 0x10676    | 50        | 1.15%   |
| 0x6fb      | 46        | 1.06%   |
| 0x20652    | 44        | 1.01%   |
| 0x706a1    | 43        | 0.99%   |
| 0x08701021 | 43        | 0.99%   |
| 0x0800820d | 40        | 0.92%   |
| 0x706e5    | 37        | 0.85%   |
| 0x506c9    | 37        | 0.85%   |
| 0x406c4    | 36        | 0.83%   |
| 0x6f6      | 35        | 0.8%    |
| 0xa0652    | 34        | 0.78%   |
| 0x0a50000c | 33        | 0.76%   |
| 0x08108102 | 33        | 0.76%   |
| 0x06006705 | 33        | 0.76%   |
| 0x010000c8 | 32        | 0.74%   |
| 0x08600106 | 31        | 0.71%   |
| 0x06000852 | 31        | 0.71%   |
| 0x06001119 | 29        | 0.67%   |
| 0x806eb    | 28        | 0.64%   |
| 0x406c3    | 27        | 0.62%   |
| 0x706a8    | 26        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 652       | 15.48%  |
| Haswell          | 419       | 9.95%   |
| Penryn           | 274       | 6.51%   |
| SandyBridge      | 264       | 6.27%   |
| Core             | 237       | 5.63%   |
| IvyBridge        | 230       | 5.46%   |
| Skylake          | 207       | 4.92%   |
| Zen+             | 166       | 3.94%   |
| Zen 2            | 161       | 3.82%   |
| Westmere         | 158       | 3.75%   |
| Silvermont       | 149       | 3.54%   |
| TigerLake        | 124       | 2.94%   |
| Broadwell        | 95        | 2.26%   |
| CometLake        | 91        | 2.16%   |
| Unknown          | 86        | 2.04%   |
| Piledriver       | 84        | 1.99%   |
| Goldmont plus    | 83        | 1.97%   |
| K10              | 82        | 1.95%   |
| Zen 3            | 76        | 1.8%    |
| Zen              | 76        | 1.8%    |
| Bonnell          | 59        | 1.4%    |
| Icelake          | 58        | 1.38%   |
| Excavator        | 58        | 1.38%   |
| K8 Hammer        | 51        | 1.21%   |
| Goldmont         | 42        | 1%      |
| Nehalem          | 40        | 0.95%   |
| NetBurst         | 38        | 0.9%    |
| P6               | 30        | 0.71%   |
| Puma             | 29        | 0.69%   |
| Jaguar           | 24        | 0.57%   |
| Bobcat           | 18        | 0.43%   |
| Steamroller      | 16        | 0.38%   |
| Alderlake Hybrid | 10        | 0.24%   |
| K10 Llano        | 9         | 0.21%   |
| Bulldozer        | 7         | 0.17%   |
| Tremont          | 4         | 0.09%   |
| K8 & K10 hybrid  | 3         | 0.07%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2419      | 48.96%  |
| Nvidia                                       | 1447      | 29.29%  |
| AMD                                          | 1024      | 20.72%  |
| Matrox Electronics Systems                   | 17        | 0.34%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.26%   |
| VIA Technologies                             | 10        | 0.2%    |
| ASPEED Technology                            | 8         | 0.16%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 180       | 3.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 119       | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 118       | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 114       | 2.23%   |
| Intel UHD Graphics 620                                                                   | 104       | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 100       | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 99        | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 95        | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 90        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 89        | 1.74%   |
| Intel HD Graphics 620                                                                    | 83        | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 82        | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 77        | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 77        | 1.51%   |
| AMD Renoir                                                                               | 77        | 1.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 76        | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 75        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 72        | 1.41%   |
| Intel HD Graphics 5500                                                                   | 68        | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 66        | 1.29%   |
| Intel HD Graphics 530                                                                    | 62        | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 61        | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 1.17%   |
| Intel HD Graphics 630                                                                    | 58        | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 57        | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                               | 54        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 50        | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 48        | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 42        | 0.82%   |
| AMD Cezanne                                                                              | 42        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 41        | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 41        | 0.8%    |
| Intel HD Graphics 500                                                                    | 40        | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 39        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 38        | 0.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1741      | 41.18%  |
| 1 x Nvidia             | 824       | 19.49%  |
| 1 x AMD                | 813       | 19.23%  |
| Intel + Nvidia         | 538       | 12.72%  |
| Intel + AMD            | 87        | 2.06%   |
| AMD + Nvidia           | 67        | 1.58%   |
| 2 x AMD                | 58        | 1.37%   |
| Other                  | 33        | 0.78%   |
| 2 x Nvidia             | 14        | 0.33%   |
| 1 x Matrox             | 14        | 0.33%   |
| 1 x SiS                | 13        | 0.31%   |
| 1 x VIA                | 10        | 0.24%   |
| 1 x ASPEED             | 5         | 0.12%   |
| Nvidia + Matrox        | 3         | 0.07%   |
| Nvidia + ASPEED        | 3         | 0.07%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3374      | 79.02%  |
| Proprietary | 715       | 16.74%  |
| Unknown     | 181       | 4.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2237      | 51.66%  |
| 1.01-2.0   | 611       | 14.11%  |
| 0.01-0.5   | 523       | 12.08%  |
| 3.01-4.0   | 344       | 7.94%   |
| 0.51-1.0   | 331       | 7.64%   |
| 7.01-8.0   | 156       | 3.6%    |
| 5.01-6.0   | 78        | 1.8%    |
| 2.01-3.0   | 26        | 0.6%    |
| 8.01-16.0  | 20        | 0.46%   |
| 16.01-24.0 | 4         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 546       | 12.12%  |
| AU Optronics            | 481       | 10.68%  |
| Chimei Innolux          | 429       | 9.52%   |
| LG Display              | 387       | 8.59%   |
| Goldstar                | 323       | 7.17%   |
| BOE                     | 290       | 6.44%   |
| Hewlett-Packard         | 224       | 4.97%   |
| BenQ                    | 179       | 3.97%   |
| Dell                    | 176       | 3.91%   |
| Acer                    | 158       | 3.51%   |
| Ancor Communications    | 140       | 3.11%   |
| Philips                 | 121       | 2.69%   |
| AOC                     | 88        | 1.95%   |
| Chi Mei Optoelectronics | 85        | 1.89%   |
| Apple                   | 83        | 1.84%   |
| Sharp                   | 78        | 1.73%   |
| Lenovo                  | 70        | 1.55%   |
| PANDA                   | 53        | 1.18%   |
| LG Electronics          | 51        | 1.13%   |
| Unknown                 | 45        | 1%      |
| Sony                    | 42        | 0.93%   |
| LG Philips              | 38        | 0.84%   |
| HannStar                | 36        | 0.8%    |
| ASUSTek Computer        | 28        | 0.62%   |
| ViewSonic               | 23        | 0.51%   |
| InfoVision              | 18        | 0.4%    |
| MSI                     | 14        | 0.31%   |
| Eizo                    | 12        | 0.27%   |
| OEM                     | 11        | 0.24%   |
| Toshiba                 | 10        | 0.22%   |
| ___                     | 9         | 0.2%    |
| Panasonic               | 9         | 0.2%    |
| Hitachi                 | 9         | 0.2%    |
| CPT                     | 9         | 0.2%    |
| Packard Bell            | 8         | 0.18%   |
| Xiaomi                  | 7         | 0.16%   |
| Vestel Elektronik       | 7         | 0.16%   |
| Quanta Display          | 7         | 0.16%   |
| NEC Computers           | 7         | 0.16%   |
| Iiyama                  | 7         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 62        | 1.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 0.69%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 26        | 0.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 26        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.49%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 20        | 0.43%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 18        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                  | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 12        | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.26%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.26%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 12        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 11        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.24%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 11        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 11        | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 10        | 0.21%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.21%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 10        | 0.21%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1849      | 43.04%  |
| 1366x768 (WXGA)    | 911       | 21.21%  |
| 3840x2160 (4K)     | 193       | 4.49%   |
| 1280x1024 (SXGA)   | 191       | 4.45%   |
| 2560x1440 (QHD)    | 149       | 3.47%   |
| 1280x800 (WXGA)    | 149       | 3.47%   |
| 1680x1050 (WSXGA+) | 135       | 3.14%   |
| 1440x900 (WXGA+)   | 132       | 3.07%   |
| 1600x900 (HD+)     | 97        | 2.26%   |
| 1920x1200 (WUXGA)  | 68        | 1.58%   |
| Unknown            | 55        | 1.28%   |
| 2560x1080          | 45        | 1.05%   |
| 1360x768           | 43        | 1%      |
| 1024x600           | 37        | 0.86%   |
| 3440x1440          | 26        | 0.61%   |
| 1024x768 (XGA)     | 23        | 0.54%   |
| 2560x1600          | 18        | 0.42%   |
| 2160x1440          | 18        | 0.42%   |
| 3840x1080          | 15        | 0.35%   |
| 1920x540           | 13        | 0.3%    |
| 1600x1200          | 12        | 0.28%   |
| 2880x1800          | 11        | 0.26%   |
| 800x1280           | 9         | 0.21%   |
| 3200x1800 (QHD+)   | 6         | 0.14%   |
| 3200x1080          | 5         | 0.12%   |
| 2288x1287          | 5         | 0.12%   |
| 4480x1080          | 4         | 0.09%   |
| 3840x2400          | 4         | 0.09%   |
| 1280x768           | 4         | 0.09%   |
| 3840x1200          | 3         | 0.07%   |
| 3600x1080          | 3         | 0.07%   |
| 3360x1080          | 3         | 0.07%   |
| 2960x1050          | 3         | 0.07%   |
| 2048x1152          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 5760x2160          | 2         | 0.05%   |
| 4480x1440          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 3200x2000          | 2         | 0.05%   |
| 2944x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1322      | 29.42%  |
| 13      | 338       | 7.52%   |
| 24      | 321       | 7.14%   |
| 21      | 321       | 7.14%   |
| 27      | 287       | 6.39%   |
| Unknown | 276       | 6.14%   |
| 23      | 256       | 5.7%    |
| 17      | 236       | 5.25%   |
| 14      | 224       | 4.98%   |
| 19      | 143       | 3.18%   |
| 18      | 108       | 2.4%    |
| 22      | 78        | 1.74%   |
| 34      | 65        | 1.45%   |
| 20      | 64        | 1.42%   |
| 31      | 61        | 1.36%   |
| 12      | 58        | 1.29%   |
| 11      | 46        | 1.02%   |
| 10      | 45        | 1%      |
| 84      | 38        | 0.85%   |
| 16      | 24        | 0.53%   |
| 72      | 21        | 0.47%   |
| 26      | 21        | 0.47%   |
| 25      | 20        | 0.45%   |
| 54      | 19        | 0.42%   |
| 32      | 18        | 0.4%    |
| 40      | 12        | 0.27%   |
| 52      | 7         | 0.16%   |
| 65      | 6         | 0.13%   |
| 46      | 6         | 0.13%   |
| 28      | 6         | 0.13%   |
| 142     | 4         | 0.09%   |
| 60      | 4         | 0.09%   |
| 48      | 4         | 0.09%   |
| 33      | 4         | 0.09%   |
| 8       | 4         | 0.09%   |
| 47      | 3         | 0.07%   |
| 43      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 75      | 2         | 0.04%   |
| 39      | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1774      | 40.17%  |
| 501-600        | 805       | 18.23%  |
| 401-500        | 643       | 14.56%  |
| 201-300        | 347       | 7.86%   |
| Unknown        | 276       | 6.25%   |
| 351-400        | 240       | 5.43%   |
| 601-700        | 100       | 2.26%   |
| 701-800        | 84        | 1.9%    |
| 1501-2000      | 61        | 1.38%   |
| 1001-1500      | 51        | 1.15%   |
| 801-900        | 18        | 0.41%   |
| 901-1000       | 6         | 0.14%   |
| More than 2000 | 4         | 0.09%   |
| 101-200        | 4         | 0.09%   |
| 1-100          | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2979      | 73.05%  |
| 16/10   | 510       | 12.51%  |
| Unknown | 231       | 5.66%   |
| 5/4     | 176       | 4.32%   |
| 21/9    | 67        | 1.64%   |
| 4/3     | 49        | 1.2%    |
| 3/2     | 42        | 1.03%   |
| 0.62    | 10        | 0.25%   |
| 1.00    | 4         | 0.1%    |
| 32/9    | 3         | 0.07%   |
| 6/5     | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1319      | 29.54%  |
| 201-250        | 798       | 17.87%  |
| 81-90          | 395       | 8.85%   |
| 151-200        | 302       | 6.76%   |
| 301-350        | 294       | 6.58%   |
| Unknown        | 276       | 6.18%   |
| 141-150        | 192       | 4.3%    |
| 71-80          | 168       | 3.76%   |
| 351-500        | 147       | 3.29%   |
| 251-300        | 114       | 2.55%   |
| More than 1000 | 107       | 2.4%    |
| 121-130        | 102       | 2.28%   |
| 61-70          | 51        | 1.14%   |
| 51-60          | 46        | 1.03%   |
| 41-50          | 45        | 1.01%   |
| 501-1000       | 36        | 0.81%   |
| 131-140        | 31        | 0.69%   |
| 111-120        | 20        | 0.45%   |
| 91-100         | 15        | 0.34%   |
| 1-40           | 7         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1523      | 35.08%  |
| 101-120       | 1208      | 27.82%  |
| 121-160       | 991       | 22.82%  |
| Unknown       | 276       | 6.36%   |
| 161-240       | 197       | 4.54%   |
| 1-50          | 93        | 2.14%   |
| More than 240 | 54        | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3429      | 79.74%  |
| 2     | 604       | 14.05%  |
| 0     | 194       | 4.51%   |
| 3     | 69        | 1.6%    |
| 4     | 4         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2390      | 37.67%  |
| Intel                             | 1761      | 27.76%  |
| Qualcomm Atheros                  | 830       | 13.08%  |
| Broadcom                          | 396       | 6.24%   |
| Ralink Technology                 | 104       | 1.64%   |
| TP-Link                           | 103       | 1.62%   |
| Marvell Technology Group          | 96        | 1.51%   |
| Broadcom Limited                  | 86        | 1.36%   |
| Nvidia                            | 84        | 1.32%   |
| Ralink                            | 67        | 1.06%   |
| Qualcomm Atheros Communications   | 40        | 0.63%   |
| MediaTek                          | 35        | 0.55%   |
| Xiaomi                            | 25        | 0.39%   |
| Samsung Electronics               | 23        | 0.36%   |
| D-Link                            | 22        | 0.35%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.28%   |
| ASIX Electronics                  | 18        | 0.28%   |
| VIA Technologies                  | 17        | 0.27%   |
| D-Link System                     | 16        | 0.25%   |
| ASUSTek Computer                  | 16        | 0.25%   |
| Qualcomm                          | 13        | 0.2%    |
| Sierra Wireless                   | 11        | 0.17%   |
| DisplayLink                       | 11        | 0.17%   |
| Dell                              | 11        | 0.17%   |
| Belkin Components                 | 11        | 0.17%   |
| Ericsson Business Mobile Networks | 10        | 0.16%   |
| Lenovo                            | 9         | 0.14%   |
| JMicron Technology                | 9         | 0.14%   |
| Hewlett-Packard                   | 9         | 0.14%   |
| Microsoft                         | 7         | 0.11%   |
| Huawei Technologies               | 7         | 0.11%   |
| ZyDAS                             | 5         | 0.08%   |
| Microchip Technology              | 5         | 0.08%   |
| LSI                               | 4         | 0.06%   |
| Gemtek                            | 4         | 0.06%   |
| Edimax Technology                 | 4         | 0.06%   |
| Attansic Technology               | 4         | 0.06%   |
| Toshiba                           | 3         | 0.05%   |
| Texas Instruments                 | 3         | 0.05%   |
| Linksys                           | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1642      | 22.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 276       | 3.78%   |
| Intel Wi-Fi 6 AX200                                                     | 168       | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 123       | 1.68%   |
| Intel Wireless 8265 / 8275                                              | 104       | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 99        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 97        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 96        | 1.31%   |
| Intel Wi-Fi 6 AX201                                                     | 94        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 93        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 93        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 91        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 91        | 1.25%   |
| Intel Wireless 7265                                                     | 88        | 1.21%   |
| Intel Wireless 3165                                                     | 80        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 80        | 1.1%    |
| Intel I211 Gigabit Network Connection                                   | 75        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                    | 71        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 59        | 0.81%   |
| Intel Wireless 7260                                                     | 56        | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 54        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 43        | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 42        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 0.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 41        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 40        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 39        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 39        | 0.53%   |
| Intel WiFi Link 5100                                                    | 38        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                 | 38        | 0.52%   |
| Intel Wireless 8260                                                     | 37        | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 36        | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 36        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 36        | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1317      | 39.54%  |
| Qualcomm Atheros                | 637       | 19.12%  |
| Realtek Semiconductor           | 616       | 18.49%  |
| Broadcom                        | 243       | 7.3%    |
| Ralink Technology               | 104       | 3.12%   |
| TP-Link                         | 86        | 2.58%   |
| Ralink                          | 67        | 2.01%   |
| Broadcom Limited                | 59        | 1.77%   |
| Qualcomm Atheros Communications | 40        | 1.2%    |
| MediaTek                        | 34        | 1.02%   |
| D-Link                          | 22        | 0.66%   |
| ASUSTek Computer                | 16        | 0.48%   |
| Sierra Wireless                 | 11        | 0.33%   |
| Belkin Components               | 11        | 0.33%   |
| D-Link System                   | 10        | 0.3%    |
| Microsoft                       | 7         | 0.21%   |
| Dell                            | 6         | 0.18%   |
| ZyDAS                           | 5         | 0.15%   |
| Qualcomm                        | 4         | 0.12%   |
| Marvell Technology Group        | 4         | 0.12%   |
| Gemtek                          | 4         | 0.12%   |
| Edimax Technology               | 4         | 0.12%   |
| Texas Instruments               | 3         | 0.09%   |
| Linksys                         | 3         | 0.09%   |
| Sitecom Europe                  | 2         | 0.06%   |
| NetGear                         | 2         | 0.06%   |
| Hewlett-Packard                 | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |
| Xiaomi                          | 1         | 0.03%   |
| Wilocity                        | 1         | 0.03%   |
| Wacom                           | 1         | 0.03%   |
| TRENDnet                        | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| Standard Microsystems           | 1         | 0.03%   |
| Samsung Electronics             | 1         | 0.03%   |
| FIBOCOM                         | 1         | 0.03%   |
| AirTies Wireless Networks       | 1         | 0.03%   |
| Accton Technology               | 1         | 0.03%   |
| 3Com                            | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 168       | 5.01%   |
| Intel Wireless 8265 / 8275                                              | 104       | 3.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 99        | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 97        | 2.89%   |
| Intel Wi-Fi 6 AX201                                                     | 94        | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 93        | 2.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 93        | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 91        | 2.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 91        | 2.71%   |
| Intel Wireless 7265                                                     | 88        | 2.62%   |
| Intel Wireless 3165                                                     | 80        | 2.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 80        | 2.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 59        | 1.76%   |
| Intel Wireless 7260                                                     | 56        | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 43        | 1.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 42        | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 39        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 39        | 1.16%   |
| Intel WiFi Link 5100                                                    | 38        | 1.13%   |
| Intel Wireless 8260                                                     | 37        | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                         | 36        | 1.07%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 36        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 36        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 1.07%   |
| Intel Wireless 3160                                                     | 34        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 32        | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 31        | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 30        | 0.89%   |
| Realtek 802.11ac NIC                                                    | 28        | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 28        | 0.83%   |
| Intel Wireless-AC 9260                                                  | 28        | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 25        | 0.75%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2137      | 56.02%  |
| Intel                                  | 801       | 21%     |
| Qualcomm Atheros                       | 268       | 7.02%   |
| Broadcom                               | 197       | 5.16%   |
| Marvell Technology Group               | 93        | 2.44%   |
| Nvidia                                 | 84        | 2.2%    |
| Broadcom Limited                       | 29        | 0.76%   |
| Xiaomi                                 | 24        | 0.63%   |
| Samsung Electronics                    | 22        | 0.58%   |
| Silicon Integrated Systems [SiS]       | 18        | 0.47%   |
| ASIX Electronics                       | 18        | 0.47%   |
| VIA Technologies                       | 17        | 0.45%   |
| TP-Link                                | 17        | 0.45%   |
| DisplayLink                            | 11        | 0.29%   |
| Qualcomm                               | 9         | 0.24%   |
| Lenovo                                 | 9         | 0.24%   |
| JMicron Technology                     | 9         | 0.24%   |
| D-Link System                          | 6         | 0.16%   |
| LSI                                    | 4         | 0.1%    |
| Attansic Technology                    | 4         | 0.1%    |
| Microchip Technology                   | 3         | 0.08%   |
| IBM                                    | 3         | 0.08%   |
| Hewlett-Packard                        | 3         | 0.08%   |
| Apple                                  | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.05%   |
| Huawei Technologies                    | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Davicom Semiconductor                  | 2         | 0.05%   |
| Aquantia                               | 2         | 0.05%   |
| ADMtek                                 | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OnePlus                                | 1         | 0.03%   |
| National Semiconductor                 | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |
| Meizu                                  | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1642      | 42.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 276       | 7.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 96        | 2.47%   |
| Intel I211 Gigabit Network Connection                             | 75        | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 71        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 54        | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 41        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 40        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 33        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 32        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 32        | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 26        | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 25        | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 23        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                              | 22        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 21        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 20        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 17        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.44%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 16        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3653      | 53.44%  |
| WiFi     | 3128      | 45.76%  |
| Modem    | 51        | 0.75%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2380      | 54.39%  |
| Ethernet | 1995      | 45.59%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2256      | 53.45%  |
| 1     | 1782      | 42.22%  |
| 0     | 102       | 2.42%   |
| 3     | 58        | 1.37%   |
| 4     | 15        | 0.36%   |
| 6     | 4         | 0.09%   |
| 5     | 4         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4092      | 97.04%  |
| Yes  | 125       | 2.96%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1030      | 43.1%   |
| Realtek Semiconductor           | 278       | 11.63%  |
| Cambridge Silicon Radio         | 223       | 9.33%   |
| Qualcomm Atheros Communications | 144       | 6.03%   |
| IMC Networks                    | 141       | 5.9%    |
| Broadcom                        | 106       | 4.44%   |
| Apple                           | 92        | 3.85%   |
| Lite-On Technology              | 78        | 3.26%   |
| Foxconn / Hon Hai               | 72        | 3.01%   |
| ASUSTek Computer                | 44        | 1.84%   |
| Toshiba                         | 33        | 1.38%   |
| Realtek                         | 28        | 1.17%   |
| Dell                            | 26        | 1.09%   |
| Hewlett-Packard                 | 22        | 0.92%   |
| Ralink                          | 17        | 0.71%   |
| Alps Electric                   | 12        | 0.5%    |
| Belkin Components               | 9         | 0.38%   |
| Integrated System Solution      | 7         | 0.29%   |
| Foxconn International           | 6         | 0.25%   |
| TP-Link                         | 3         | 0.13%   |
| Ralink Technology               | 3         | 0.13%   |
| MediaTek                        | 3         | 0.13%   |
| Roper                           | 2         | 0.08%   |
| Marvell Semiconductor           | 2         | 0.08%   |
| Edimax Technology               | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 396       | 16.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 223       | 9.33%   |
| Realtek Bluetooth Radio                             | 195       | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 175       | 7.32%   |
| Intel AX201 Bluetooth                               | 172       | 7.2%    |
| Intel AX200 Bluetooth                               | 163       | 6.82%   |
| IMC Networks Bluetooth Radio                        | 63        | 2.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 59        | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 2.26%   |
| IMC Networks Bluetooth Device                       | 46        | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 1.59%   |
| Apple Bluetooth Host Controller                     | 38        | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 1.42%   |
| Foxconn / Hon Hai Bluetooth Device                  | 34        | 1.42%   |
| Realtek Bluetooth Radio                             | 28        | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 28        | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.13%   |
| Apple Bluetooth USB Host Controller                 | 26        | 1.09%   |
| Lite-On Bluetooth Device                            | 23        | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 0.92%   |
| Intel AX210 Bluetooth                               | 22        | 0.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.79%   |
| IMC Networks Wireless_Device                        | 18        | 0.75%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 15        | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.59%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.59%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.46%   |
| Broadcom BCM2045 Bluetooth                          | 11        | 0.46%   |
| Apple Bluetooth HCI                                 | 11        | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 0.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.42%   |
| Toshiba Integrated Bluetooth HCI                    | 9         | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.33%   |
| Realtek RTL8821A Bluetooth                          | 8         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3086      | 54.74%  |
| AMD                                  | 1083      | 19.21%  |
| Nvidia                               | 978       | 17.35%  |
| C-Media Electronics                  | 95        | 1.68%   |
| Creative Labs                        | 35        | 0.62%   |
| Logitech                             | 32        | 0.57%   |
| Silicon Integrated Systems [SiS]     | 20        | 0.35%   |
| Texas Instruments                    | 19        | 0.34%   |
| JMTek                                | 19        | 0.34%   |
| VIA Technologies                     | 18        | 0.32%   |
| GN Netcom                            | 16        | 0.28%   |
| Kingston Technology                  | 15        | 0.27%   |
| Plantronics                          | 14        | 0.25%   |
| Corsair                              | 13        | 0.23%   |
| Focusrite-Novation                   | 11        | 0.2%    |
| Creative Technology                  | 11        | 0.2%    |
| Generalplus Technology               | 10        | 0.18%   |
| Realtek Semiconductor                | 9         | 0.16%   |
| Lenovo                               | 9         | 0.16%   |
| SteelSeries ApS                      | 8         | 0.14%   |
| Ensoniq                              | 6         | 0.11%   |
| ASUSTek Computer                     | 6         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.09%   |
| Sennheiser Communications            | 5         | 0.09%   |
| M-Audio                              | 5         | 0.09%   |
| Hewlett-Packard                      | 5         | 0.09%   |
| BEHRINGER International              | 5         | 0.09%   |
| Yamaha                               | 4         | 0.07%   |
| Tenx Technology                      | 4         | 0.07%   |
| Blue Microphones                     | 4         | 0.07%   |
| Apple                                | 4         | 0.07%   |
| SAVITECH                             | 3         | 0.05%   |
| Razer USA                            | 3         | 0.05%   |
| QinHeng Electronics                  | 3         | 0.05%   |
| Guillemot                            | 3         | 0.05%   |
| Evolution Electronics                | 3         | 0.05%   |
| Elite Silicon                        | 3         | 0.05%   |
| XMOS                                 | 2         | 0.04%   |
| Sony                                 | 2         | 0.04%   |
| PreSonus Audio Electronics           | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 289       | 4.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 286       | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 251       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 243       | 3.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 229       | 3.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 207       | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 189       | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 174       | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 168       | 2.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 164       | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 137       | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 128       | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 124       | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 122       | 1.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 119       | 1.79%   |
| AMD FCH Azalia Controller                                                  | 119       | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 117       | 1.76%   |
| Intel 8 Series HD Audio Controller                                         | 115       | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 114       | 1.71%   |
| AMD Starship/Matisse HD Audio Controller                                   | 107       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 100       | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 99        | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 94        | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 91        | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 89        | 1.34%   |
| Intel 200 Series PCH HD Audio                                              | 88        | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                               | 87        | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 83        | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 81        | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 78        | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 72        | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 62        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 61        | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 57        | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 57        | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 55        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 54        | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 49        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 49        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 46        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 518       | 22.61%  |
| SK hynix                     | 362       | 15.8%   |
| Kingston                     | 357       | 15.58%  |
| Unknown                      | 264       | 11.52%  |
| Micron Technology            | 201       | 8.77%   |
| Crucial                      | 150       | 6.55%   |
| Corsair                      | 94        | 4.1%    |
| G.Skill                      | 78        | 3.4%    |
| Ramaxel Technology           | 59        | 2.58%   |
| Unknown (ABCD)               | 33        | 1.44%   |
| Elpida                       | 33        | 1.44%   |
| Nanya Technology             | 19        | 0.83%   |
| A-DATA Technology            | 19        | 0.83%   |
| Silicon Power                | 12        | 0.52%   |
| Goodram                      | 10        | 0.44%   |
| Transcend                    | 8         | 0.35%   |
| Unknown                      | 8         | 0.35%   |
| Unifosa                      | 6         | 0.26%   |
| Team                         | 5         | 0.22%   |
| Apacer                       | 5         | 0.22%   |
| Wilk                         | 4         | 0.17%   |
| Patriot                      | 4         | 0.17%   |
| ASint Technology             | 4         | 0.17%   |
| Kllisre                      | 3         | 0.13%   |
| Atermiter                    | 3         | 0.13%   |
| SHARETRONIC                  | 2         | 0.09%   |
| Qimonda                      | 2         | 0.09%   |
| PNY                          | 2         | 0.09%   |
| KomputerBay                  | 2         | 0.09%   |
| Innodisk                     | 2         | 0.09%   |
| Exceleram                    | 2         | 0.09%   |
| Avant                        | 2         | 0.09%   |
| Unknown (AB)                 | 1         | 0.04%   |
| Unknown (07FB)               | 1         | 0.04%   |
| Toshiba                      | 1         | 0.04%   |
| Timetec                      | 1         | 0.04%   |
| Thermaltake                  | 1         | 0.04%   |
| Pioneer                      | 1         | 0.04%   |
| Patriot Memory (PDP Systems) | 1         | 0.04%   |
| Netlist                      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 27        | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 22        | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 21        | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 19        | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 17        | 0.69%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s               | 17        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 16        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 16        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 16        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 14        | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 14        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s        | 12        | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 12        | 0.49%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 12        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 12        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 11        | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 11        | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 11        | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 11        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 11        | 0.45%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                 | 11        | 0.45%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s            | 11        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 10        | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 10        | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 10        | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 10        | 0.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                 | 10        | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 10        | 0.41%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 9         | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 8         | 0.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 8         | 0.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 8         | 0.32%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 8         | 0.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.32%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 8         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 923       | 46.38%  |
| DDR3    | 669       | 33.62%  |
| DDR2    | 125       | 6.28%   |
| LPDDR4  | 71        | 3.57%   |
| Unknown | 68        | 3.42%   |
| SDRAM   | 60        | 3.02%   |
| LPDDR3  | 49        | 2.46%   |
| DDR     | 15        | 0.75%   |
| DRAM    | 6         | 0.3%    |
| DDR5    | 3         | 0.15%   |
| LPDDR5  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1172      | 58.78%  |
| DIMM         | 685       | 34.35%  |
| Row Of Chips | 124       | 6.22%   |
| Chip         | 9         | 0.45%   |
| FB-DIMM      | 3         | 0.15%   |
| RIMM         | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 796       | 36.61%  |
| 4096  | 625       | 28.75%  |
| 2048  | 309       | 14.21%  |
| 16384 | 292       | 13.43%  |
| 1024  | 102       | 4.69%   |
| 32768 | 37        | 1.7%    |
| 512   | 8         | 0.37%   |
| 65536 | 2         | 0.09%   |
| 256   | 2         | 0.09%   |
| 3072  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 421       | 19.49%  |
| 2667    | 323       | 14.95%  |
| 3200    | 293       | 13.56%  |
| 2400    | 176       | 8.15%   |
| 1333    | 150       | 6.94%   |
| 2133    | 112       | 5.19%   |
| 667     | 83        | 3.84%   |
| 1334    | 69        | 3.19%   |
| 800     | 65        | 3.01%   |
| 3600    | 57        | 2.64%   |
| Unknown | 52        | 2.41%   |
| 1867    | 43        | 1.99%   |
| 8400    | 28        | 1.3%    |
| 4267    | 25        | 1.16%   |
| 1067    | 23        | 1.06%   |
| 3466    | 22        | 1.02%   |
| 3266    | 20        | 0.93%   |
| 2933    | 18        | 0.83%   |
| 1866    | 17        | 0.79%   |
| 1066    | 15        | 0.69%   |
| 533     | 14        | 0.65%   |
| 4199    | 12        | 0.56%   |
| 3400    | 12        | 0.56%   |
| 2733    | 12        | 0.56%   |
| 2048    | 12        | 0.56%   |
| 3000    | 10        | 0.46%   |
| 3733    | 5         | 0.23%   |
| 2666    | 5         | 0.23%   |
| 975     | 5         | 0.23%   |
| 400     | 5         | 0.23%   |
| 3800    | 4         | 0.19%   |
| 3500    | 4         | 0.19%   |
| 1800    | 4         | 0.19%   |
| 1639    | 4         | 0.19%   |
| 4800    | 3         | 0.14%   |
| 4266    | 3         | 0.14%   |
| 2800    | 3         | 0.14%   |
| 333     | 3         | 0.14%   |
| 6400    | 2         | 0.09%   |
| 3866    | 2         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 56        | 48.28%  |
| Brother Industries       | 23        | 19.83%  |
| Canon                    | 12        | 10.34%  |
| Samsung Electronics      | 9         | 7.76%   |
| Seiko Epson              | 7         | 6.03%   |
| Oki Data                 | 2         | 1.72%   |
| Dymo-CoStar              | 2         | 1.72%   |
| Ricoh                    | 1         | 0.86%   |
| Magic Control Technology | 1         | 0.86%   |
| Lexmark International    | 1         | 0.86%   |
| Kyocera                  | 1         | 0.86%   |
| Apple                    | 1         | 0.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 4.27%   |
| Brother HL-2030 Laser Printer                   | 5         | 4.27%   |
| Canon PIXMA MG2500 Series                       | 4         | 3.42%   |
| HP LaserJet 1020                                | 3         | 2.56%   |
| HP Deskjet 1050 J410                            | 3         | 2.56%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.71%   |
| Samsung M2070 Series                            | 2         | 1.71%   |
| Oki Data USB Device                             | 2         | 1.71%   |
| HP LaserJet 1010                                | 2         | 1.71%   |
| HP ENVY 5540 series                             | 2         | 1.71%   |
| HP ENVY 5000 series                             | 2         | 1.71%   |
| HP ENVY 4520 series                             | 2         | 1.71%   |
| HP DeskJet F2492 All-in-One                     | 2         | 1.71%   |
| HP DeskJet 5550                                 | 2         | 1.71%   |
| HP DeskJet 3630 series                          | 2         | 1.71%   |
| HP DeskJet 2620 All-in-One Printer              | 2         | 1.71%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.71%   |
| Canon LiDE 400                                  | 2         | 1.71%   |
| Brother Printer                                 | 2         | 1.71%   |
| Brother MFC-J5330DW                             | 2         | 1.71%   |
| Brother DCP-1510                                | 2         | 1.71%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.85%   |
| Seiko Epson XP-230 Series                       | 1         | 0.85%   |
| Seiko Epson XP-225 Series                       | 1         | 0.85%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.85%   |
| Seiko Epson Printer                             | 1         | 0.85%   |
| Seiko Epson L555 Series                         | 1         | 0.85%   |
| Seiko Epson L1300 Series                        | 1         | 0.85%   |
| Samsung SCX-4300 Series                         | 1         | 0.85%   |
| Samsung SCX-3400 Series                         | 1         | 0.85%   |
| Samsung SCX-3200 Series                         | 1         | 0.85%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.85%   |
| Samsung M267x 287x Series                       | 1         | 0.85%   |
| Ricoh SP 112                                    | 1         | 0.85%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.85%   |
| Lexmark International B2236dw                   | 1         | 0.85%   |
| Kyocera ECOSYS M5521cdn                         | 1         | 0.85%   |
| HP PSC-1315/PSC-1317                            | 1         | 0.85%   |
| HP PSC 1500 series                              | 1         | 0.85%   |
| HP Printing Support                             | 1         | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 45.16%  |
| Hewlett-Packard             | 8         | 25.81%  |
| Seiko Epson                 | 5         | 16.13%  |
| Acer Peripherals (now BenQ) | 2         | 6.45%   |
| Mustek Systems              | 1         | 3.23%   |
| KYE Systems (Mouse Systems) | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.9%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.45%   |
| HP Scanjet 300                                           | 2         | 6.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.45%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.45%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.45%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.45%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.23%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.23%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.23%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.23%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.23%   |
| HP Scanjet N6010                                         | 1         | 3.23%   |
| HP ScanJet 5200c                                         | 1         | 3.23%   |
| HP ScanJet 4570c                                         | 1         | 3.23%   |
| HP ScanJet 4300c                                         | 1         | 3.23%   |
| HP ScanJet 3570c                                         | 1         | 3.23%   |
| HP ScanJet 3300c                                         | 1         | 3.23%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.23%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.23%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 558       | 23.12%  |
| IMC Networks                           | 263       | 10.9%   |
| Acer                                   | 232       | 9.61%   |
| Realtek Semiconductor                  | 154       | 6.38%   |
| Microdia                               | 151       | 6.26%   |
| Logitech                               | 113       | 4.68%   |
| Suyin                                  | 111       | 4.6%    |
| Quanta                                 | 105       | 4.35%   |
| Sunplus Innovation Technology          | 104       | 4.31%   |
| Cheng Uei Precision Industry (Foxlink) | 84        | 3.48%   |
| Syntek                                 | 65        | 2.69%   |
| Apple                                  | 64        | 2.65%   |
| Alcor Micro                            | 42        | 1.74%   |
| Lite-On Technology                     | 39        | 1.62%   |
| Ricoh                                  | 28        | 1.16%   |
| Luxvisions Innotech Limited            | 26        | 1.08%   |
| Silicon Motion                         | 19        | 0.79%   |
| Samsung Electronics                    | 19        | 0.79%   |
| Creative Technology                    | 17        | 0.7%    |
| Z-Star Microelectronics                | 14        | 0.58%   |
| GEMBIRD                                | 13        | 0.54%   |
| Microsoft                              | 12        | 0.5%    |
| Generalplus Technology                 | 11        | 0.46%   |
| Lenovo                                 | 9         | 0.37%   |
| Importek                               | 9         | 0.37%   |
| KYE Systems (Mouse Systems)            | 8         | 0.33%   |
| ARC International                      | 8         | 0.33%   |
| ALi                                    | 8         | 0.33%   |
| Sunplus Technology                     | 7         | 0.29%   |
| Sonix Technology                       | 7         | 0.29%   |
| Jieli Technology                       | 7         | 0.29%   |
| icSpring                               | 7         | 0.29%   |
| Genesys Logic                          | 6         | 0.25%   |
| Cubeternet                             | 6         | 0.25%   |
| 2M UVC CAMERA                          | 6         | 0.25%   |
| Primax Electronics                     | 5         | 0.21%   |
| Intel                                  | 5         | 0.21%   |
| OmniVision Technologies                | 4         | 0.17%   |
| DigiTech                               | 4         | 0.17%   |
| Aveo Technology                        | 4         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam        | 70        | 2.88%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 62        | 2.55%   |
| Chicony HD Webcam                        | 59        | 2.43%   |
| Acer Integrated Camera                   | 56        | 2.31%   |
| Chicony Integrated Camera                | 53        | 2.18%   |
| Microdia Integrated_Webcam_HD            | 52        | 2.14%   |
| Acer HD Webcam                           | 45        | 1.85%   |
| IMC Networks Integrated Camera           | 42        | 1.73%   |
| Chicony USB2.0 VGA UVC WebCam            | 38        | 1.56%   |
| Realtek Integrated_Webcam_HD             | 32        | 1.32%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 30        | 1.24%   |
| Quanta HP TrueVision HD Camera           | 29        | 1.19%   |
| Logitech Webcam C270                     | 28        | 1.15%   |
| Apple Built-in iSight                    | 27        | 1.11%   |
| Chicony TOSHIBA Web Camera - HD          | 26        | 1.07%   |
| Chicony EasyCamera                       | 25        | 1.03%   |
| Syntek Integrated Camera                 | 24        | 0.99%   |
| Chicony USB 2.0 Camera                   | 24        | 0.99%   |
| Realtek USB Camera                       | 23        | 0.95%   |
| Sunplus HD WebCam                        | 22        | 0.91%   |
| Microdia Webcam Vitade AF                | 20        | 0.82%   |
| Acer EasyCamera                          | 20        | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)  | 19        | 0.78%   |
| Chicony USB2.0 HD UVC WebCam             | 19        | 0.78%   |
| Acer HD Camera                           | 19        | 0.78%   |
| Lite-On Integrated Camera                | 17        | 0.7%    |
| Chicony HP Truevision HD                 | 17        | 0.7%    |
| Syntek EasyCamera                        | 16        | 0.66%   |
| Apple FaceTime HD Camera (Built-in)      | 16        | 0.66%   |
| Acer Lenovo EasyCamera                   | 16        | 0.66%   |
| Realtek Lenovo EasyCamera                | 15        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)  | 15        | 0.62%   |
| Chicony HP TrueVision HD Camera          | 15        | 0.62%   |
| Acer BisonCam, NB Pro                    | 15        | 0.62%   |
| Syntek Lenovo EasyCamera                 | 14        | 0.58%   |
| Quanta HP HD Camera                      | 14        | 0.58%   |
| Microdia USB 2.0 Camera                  | 14        | 0.58%   |
| Logitech HD Pro Webcam C920              | 14        | 0.58%   |
| Chicony VGA Webcam                       | 14        | 0.58%   |
| Chicony USB2.0 Camera                    | 14        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 102       | 29.57%  |
| Validity Sensors           | 82        | 23.77%  |
| Shenzhen Goodix Technology | 56        | 16.23%  |
| Elan Microelectronics      | 35        | 10.14%  |
| AuthenTec                  | 33        | 9.57%   |
| Upek                       | 21        | 6.09%   |
| LighTuning Technology      | 10        | 2.9%    |
| STMicroelectronics         | 6         | 1.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 42        | 12.17%  |
| Shenzhen Goodix  FingerPrint Device                                        | 37        | 10.72%  |
| Elan ELAN:Fingerprint                                                      | 33        | 9.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 7.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 4.93%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 4.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 4.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 4.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.19%   |
| Synaptics  WBDI                                                            | 9         | 2.61%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.32%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.32%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.74%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.74%   |
| AuthenTec AES1600                                                          | 6         | 1.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.45%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.45%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.45%   |
| AuthenTec AES2810                                                          | 5         | 1.45%   |
| Validity Sensors VFS491                                                    | 4         | 1.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.16%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.16%   |
| LighTuning EgisTec_ES603                                                   | 4         | 1.16%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.16%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.87%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.87%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.58%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.58%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.58%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.58%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.58%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.58%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.58%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.29%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 63        | 35%     |
| Broadcom                  | 45        | 25%     |
| O2 Micro                  | 23        | 12.78%  |
| Advanced Card Systems     | 8         | 4.44%   |
| Lenovo                    | 7         | 3.89%   |
| Chicony Electronics       | 5         | 2.78%   |
| Cherry                    | 5         | 2.78%   |
| C3PO                      | 5         | 2.78%   |
| Upek                      | 4         | 2.22%   |
| Realtek Semiconductor     | 4         | 2.22%   |
| Gemalto (was Gemplus)     | 3         | 1.67%   |
| SCM Microsystems          | 2         | 1.11%   |
| OmniKey                   | 2         | 1.11%   |
| Hewlett-Packard           | 2         | 1.11%   |
| In Focus Systems          | 1         | 0.56%   |
| Fujitsu Siemens Computers | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 59        | 32.78%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 12.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 8.89%   |
| Broadcom 5880                                                                | 12        | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5%      |
| Broadcom 58200                                                               | 8         | 4.44%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.89%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 3.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 5         | 2.78%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.22%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.22%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 2.22%   |
| C3PO LTC31v2                                                                 | 4         | 2.22%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 2.22%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.11%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.11%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.11%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.56%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.56%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.56%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.56%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.56%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.56%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.56%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3176      | 73.79%  |
| 1     | 905       | 21.03%  |
| 2     | 182       | 4.23%   |
| 3     | 28        | 0.65%   |
| 4     | 7         | 0.16%   |
| 5     | 3         | 0.07%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 339       | 25.09%  |
| Graphics card            | 325       | 24.06%  |
| Net/wireless             | 206       | 15.25%  |
| Chipcard                 | 146       | 10.81%  |
| Multimedia controller    | 87        | 6.44%   |
| Communication controller | 42        | 3.11%   |
| Camera                   | 36        | 2.66%   |
| Bluetooth                | 35        | 2.59%   |
| Unassigned class         | 25        | 1.85%   |
| Storage                  | 21        | 1.55%   |
| Sound                    | 19        | 1.41%   |
| Card reader              | 19        | 1.41%   |
| Net/ethernet             | 13        | 0.96%   |
| Network                  | 10        | 0.74%   |
| Flash memory             | 10        | 0.74%   |
| Modem                    | 9         | 0.67%   |
| Dvb card                 | 5         | 0.37%   |
| Firewire controller      | 3         | 0.22%   |
| Storage/ide              | 1         | 0.07%   |


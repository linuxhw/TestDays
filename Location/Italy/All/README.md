Linux in Italy - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 9561

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [b792043acd](https://linux-hardware.org/?probe=b792043acd) | Feb 01, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a8a3f37ad8](https://linux-hardware.org/?probe=a8a3f37ad8) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [48bccd4f38](https://linux-hardware.org/?probe=48bccd4f38) | Feb 01, 2023 |
| Pegatron      | 2A94                        | Desktop     | [58961a542f](https://linux-hardware.org/?probe=58961a542f) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [92f6e450b8](https://linux-hardware.org/?probe=92f6e450b8) | Jan 31, 2023 |
| HP            | ENVY 15                     | Notebook    | [c688eb85bb](https://linux-hardware.org/?probe=c688eb85bb) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [f4e30fc177](https://linux-hardware.org/?probe=f4e30fc177) | Jan 31, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [77cc2bd640](https://linux-hardware.org/?probe=77cc2bd640) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [656bb989e7](https://linux-hardware.org/?probe=656bb989e7) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [8e8ae85d60](https://linux-hardware.org/?probe=8e8ae85d60) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [0d254e85dd](https://linux-hardware.org/?probe=0d254e85dd) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [3c8b3f4e7d](https://linux-hardware.org/?probe=3c8b3f4e7d) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [3bdb934f29](https://linux-hardware.org/?probe=3bdb934f29) | Jan 30, 2023 |
| Dell          | Precision 3560              | Notebook    | [3d5432deef](https://linux-hardware.org/?probe=3d5432deef) | Jan 30, 2023 |
| Dell          | Precision 3560              | Notebook    | [c250c935bd](https://linux-hardware.org/?probe=c250c935bd) | Jan 30, 2023 |
| Dell          | Precision 3571              | Notebook    | [55f371f4ef](https://linux-hardware.org/?probe=55f371f4ef) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | Notebook    | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Intel         | B75                         | Desktop     | [6597bed6da](https://linux-hardware.org/?probe=6597bed6da) | Jan 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [8200b57a5b](https://linux-hardware.org/?probe=8200b57a5b) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [7af163f694](https://linux-hardware.org/?probe=7af163f694) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3ac195a476](https://linux-hardware.org/?probe=3ac195a476) | Jan 29, 2023 |
| MSI           | P55-CD53                    | Desktop     | [7c46f17179](https://linux-hardware.org/?probe=7c46f17179) | Jan 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e91c24c3f9](https://linux-hardware.org/?probe=e91c24c3f9) | Jan 29, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [f8ef554d85](https://linux-hardware.org/?probe=f8ef554d85) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [615e9f22e4](https://linux-hardware.org/?probe=615e9f22e4) | Jan 29, 2023 |
| ASRock        | H610M-HVS                   | Desktop     | [2774d547be](https://linux-hardware.org/?probe=2774d547be) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [37c0fb77f5](https://linux-hardware.org/?probe=37c0fb77f5) | Jan 29, 2023 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [8bf2fa8d9b](https://linux-hardware.org/?probe=8bf2fa8d9b) | Jan 28, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [890cad48c3](https://linux-hardware.org/?probe=890cad48c3) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ea763da5f](https://linux-hardware.org/?probe=5ea763da5f) | Jan 28, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [17a8246044](https://linux-hardware.org/?probe=17a8246044) | Jan 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8f6ea9ffff](https://linux-hardware.org/?probe=8f6ea9ffff) | Jan 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [bbe5b30c42](https://linux-hardware.org/?probe=bbe5b30c42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [73b3f84699](https://linux-hardware.org/?probe=73b3f84699) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [292892acd3](https://linux-hardware.org/?probe=292892acd3) | Jan 28, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [312e07a824](https://linux-hardware.org/?probe=312e07a824) | Jan 28, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [23a84c76b8](https://linux-hardware.org/?probe=23a84c76b8) | Jan 27, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [4bf7b18ab1](https://linux-hardware.org/?probe=4bf7b18ab1) | Jan 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6f449734a9](https://linux-hardware.org/?probe=6f449734a9) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [01e47b07a8](https://linux-hardware.org/?probe=01e47b07a8) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [4ae098906f](https://linux-hardware.org/?probe=4ae098906f) | Jan 26, 2023 |
| Toshiba       | Satellite Pro C50-A-1FD     | Notebook    | [7f7198cdcb](https://linux-hardware.org/?probe=7f7198cdcb) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [759ae65214](https://linux-hardware.org/?probe=759ae65214) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8128876a22](https://linux-hardware.org/?probe=8128876a22) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [027f04536c](https://linux-hardware.org/?probe=027f04536c) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [bea1d8a9ce](https://linux-hardware.org/?probe=bea1d8a9ce) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [596316a81c](https://linux-hardware.org/?probe=596316a81c) | Jan 25, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [edb16eafc7](https://linux-hardware.org/?probe=edb16eafc7) | Jan 25, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [3e1520340a](https://linux-hardware.org/?probe=3e1520340a) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [7b93d7477b](https://linux-hardware.org/?probe=7b93d7477b) | Jan 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [25c4dbbe9c](https://linux-hardware.org/?probe=25c4dbbe9c) | Jan 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [cfd65f9e9e](https://linux-hardware.org/?probe=cfd65f9e9e) | Jan 24, 2023 |
| MSI           | Boston                      | Desktop     | [456d7782ad](https://linux-hardware.org/?probe=456d7782ad) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| MSI           | P55-CD53                    | Desktop     | [7c3a675f94](https://linux-hardware.org/?probe=7c3a675f94) | Jan 24, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [5df97c3eb1](https://linux-hardware.org/?probe=5df97c3eb1) | Jan 24, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [60962892bc](https://linux-hardware.org/?probe=60962892bc) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | Desktop     | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [cbd812094c](https://linux-hardware.org/?probe=cbd812094c) | Jan 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [a05bb7e519](https://linux-hardware.org/?probe=a05bb7e519) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [917f63e659](https://linux-hardware.org/?probe=917f63e659) | Jan 23, 2023 |
| Packard Be... | EG43M                       | Desktop     | [92810508a2](https://linux-hardware.org/?probe=92810508a2) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [972194ff6e](https://linux-hardware.org/?probe=972194ff6e) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [d0f4730f71](https://linux-hardware.org/?probe=d0f4730f71) | Jan 23, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5cd697d63d](https://linux-hardware.org/?probe=5cd697d63d) | Jan 23, 2023 |
| Acer          | Aspire C22-865              | All in one  | [eb0191f969](https://linux-hardware.org/?probe=eb0191f969) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [bff960bae2](https://linux-hardware.org/?probe=bff960bae2) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [adcd91409c](https://linux-hardware.org/?probe=adcd91409c) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [e2fd85407d](https://linux-hardware.org/?probe=e2fd85407d) | Jan 23, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8460e3552a](https://linux-hardware.org/?probe=8460e3552a) | Jan 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8941c8857e](https://linux-hardware.org/?probe=8941c8857e) | Jan 22, 2023 |
| ASRock        | H61M                        | Desktop     | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [89c37ebdfa](https://linux-hardware.org/?probe=89c37ebdfa) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | 8433 11                     | Desktop     | [a5c598c4c5](https://linux-hardware.org/?probe=a5c598c4c5) | Jan 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [b919144e1c](https://linux-hardware.org/?probe=b919144e1c) | Jan 22, 2023 |
| ASRock        | G31M-S                      | Desktop     | [dbf8922f3a](https://linux-hardware.org/?probe=dbf8922f3a) | Jan 22, 2023 |
| MSI           | Boston                      | Desktop     | [34413408ce](https://linux-hardware.org/?probe=34413408ce) | Jan 22, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [5d3b4c4823](https://linux-hardware.org/?probe=5d3b4c4823) | Jan 22, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [a3ce3d4a23](https://linux-hardware.org/?probe=a3ce3d4a23) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [0aa5260ed0](https://linux-hardware.org/?probe=0aa5260ed0) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [7389389089](https://linux-hardware.org/?probe=7389389089) | Jan 22, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [6a8cc962ad](https://linux-hardware.org/?probe=6a8cc962ad) | Jan 22, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [44fa1b3713](https://linux-hardware.org/?probe=44fa1b3713) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | Desktop     | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| HP            | 1497                        | Desktop     | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [09650cf189](https://linux-hardware.org/?probe=09650cf189) | Jan 22, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| Acer          | TravelMate Spin B118-RN     | Convertible | [de7f588126](https://linux-hardware.org/?probe=de7f588126) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [140706838b](https://linux-hardware.org/?probe=140706838b) | Jan 21, 2023 |
| HP            | ProBook 4520s               | Notebook    | [ab9f74eb2c](https://linux-hardware.org/?probe=ab9f74eb2c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Toshiba       | Satellite Pro C850-10L      | Notebook    | [c1de4d0e2b](https://linux-hardware.org/?probe=c1de4d0e2b) | Jan 21, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [9229e3b2ae](https://linux-hardware.org/?probe=9229e3b2ae) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [62dc562b9e](https://linux-hardware.org/?probe=62dc562b9e) | Jan 21, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [eb57bb7cd7](https://linux-hardware.org/?probe=eb57bb7cd7) | Jan 21, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [d020dd93e4](https://linux-hardware.org/?probe=d020dd93e4) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [98d6ab791c](https://linux-hardware.org/?probe=98d6ab791c) | Jan 21, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [b8660798ec](https://linux-hardware.org/?probe=b8660798ec) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [c87740267f](https://linux-hardware.org/?probe=c87740267f) | Jan 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [0a4700fc75](https://linux-hardware.org/?probe=0a4700fc75) | Jan 20, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [77ac7a6fc3](https://linux-hardware.org/?probe=77ac7a6fc3) | Jan 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b2c0017481](https://linux-hardware.org/?probe=b2c0017481) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [712fdb1fa7](https://linux-hardware.org/?probe=712fdb1fa7) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [5b1b812b6e](https://linux-hardware.org/?probe=5b1b812b6e) | Jan 20, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [8fc05186e7](https://linux-hardware.org/?probe=8fc05186e7) | Jan 20, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [2e73bc84e7](https://linux-hardware.org/?probe=2e73bc84e7) | Jan 20, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [5175eeeff4](https://linux-hardware.org/?probe=5175eeeff4) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [2f712e8614](https://linux-hardware.org/?probe=2f712e8614) | Jan 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| Acer          | Aspire C22-865              | All in one  | [90ea1c9655](https://linux-hardware.org/?probe=90ea1c9655) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [67e4dd8f10](https://linux-hardware.org/?probe=67e4dd8f10) | Jan 19, 2023 |
| Insyde        | Braswell                    | Notebook    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [2e54ccac4d](https://linux-hardware.org/?probe=2e54ccac4d) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [763f4cb45f](https://linux-hardware.org/?probe=763f4cb45f) | Jan 18, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [a6c30f3d53](https://linux-hardware.org/?probe=a6c30f3d53) | Jan 18, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [b582c4f1b5](https://linux-hardware.org/?probe=b582c4f1b5) | Jan 18, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dcf9186db1](https://linux-hardware.org/?probe=dcf9186db1) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [79ad95dada](https://linux-hardware.org/?probe=79ad95dada) | Jan 18, 2023 |
| ASRock        | G31M-S                      | Desktop     | [d3aa4e7eea](https://linux-hardware.org/?probe=d3aa4e7eea) | Jan 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d1d3fadd60](https://linux-hardware.org/?probe=d1d3fadd60) | Jan 18, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [d58a30b560](https://linux-hardware.org/?probe=d58a30b560) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| ASUSTek       | TP301UJ                     | Notebook    | [4ee30e82ab](https://linux-hardware.org/?probe=4ee30e82ab) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [4e8759fda2](https://linux-hardware.org/?probe=4e8759fda2) | Jan 18, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [f17b69afa1](https://linux-hardware.org/?probe=f17b69afa1) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [d1310959ea](https://linux-hardware.org/?probe=d1310959ea) | Jan 17, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [ec4d653e2f](https://linux-hardware.org/?probe=ec4d653e2f) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [52c1a6c197](https://linux-hardware.org/?probe=52c1a6c197) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9f958e5c4](https://linux-hardware.org/?probe=b9f958e5c4) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [44bf2e2ced](https://linux-hardware.org/?probe=44bf2e2ced) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [df73fafeb7](https://linux-hardware.org/?probe=df73fafeb7) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [4d4b18a5b3](https://linux-hardware.org/?probe=4d4b18a5b3) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| HP            | 15                          | Notebook    | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [3891575263](https://linux-hardware.org/?probe=3891575263) | Jan 16, 2023 |
| Sony          | SVT1312M1ES                 | Notebook    | [9244e6ad96](https://linux-hardware.org/?probe=9244e6ad96) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [1dd0101330](https://linux-hardware.org/?probe=1dd0101330) | Jan 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [360173820c](https://linux-hardware.org/?probe=360173820c) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [58c875e5d5](https://linux-hardware.org/?probe=58c875e5d5) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [084cfebfdb](https://linux-hardware.org/?probe=084cfebfdb) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [f8c56a73c0](https://linux-hardware.org/?probe=f8c56a73c0) | Jan 15, 2023 |
| Acer          | TravelMate P253             | Notebook    | [8f2246679e](https://linux-hardware.org/?probe=8f2246679e) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [d30e9b41ef](https://linux-hardware.org/?probe=d30e9b41ef) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [a265db8e50](https://linux-hardware.org/?probe=a265db8e50) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [aa28cfacc3](https://linux-hardware.org/?probe=aa28cfacc3) | Jan 15, 2023 |
| HP            | Notebook                    | Notebook    | [be5a441ca6](https://linux-hardware.org/?probe=be5a441ca6) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [5f9aaa4add](https://linux-hardware.org/?probe=5f9aaa4add) | Jan 15, 2023 |
| HP            | 15                          | Notebook    | [3faa6c9265](https://linux-hardware.org/?probe=3faa6c9265) | Jan 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b3cbaccd13](https://linux-hardware.org/?probe=b3cbaccd13) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7b8818c038](https://linux-hardware.org/?probe=7b8818c038) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [74dfb9a261](https://linux-hardware.org/?probe=74dfb9a261) | Jan 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [08bbff061e](https://linux-hardware.org/?probe=08bbff061e) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [51581940b0](https://linux-hardware.org/?probe=51581940b0) | Jan 15, 2023 |
| Acer          | TravelMate P253             | Notebook    | [15c26878b5](https://linux-hardware.org/?probe=15c26878b5) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| Kiano         | SlimNote 14,2               | Notebook    | [7596dc87b3](https://linux-hardware.org/?probe=7596dc87b3) | Jan 14, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [5f9c2eebd4](https://linux-hardware.org/?probe=5f9c2eebd4) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [e5c76bef74](https://linux-hardware.org/?probe=e5c76bef74) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2a08ec8e9e](https://linux-hardware.org/?probe=2a08ec8e9e) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | Notebook    | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | Notebook    | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| HP            | Notebook                    | Notebook    | [4c9b4e3b67](https://linux-hardware.org/?probe=4c9b4e3b67) | Jan 14, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [d4cc07d2d2](https://linux-hardware.org/?probe=d4cc07d2d2) | Jan 14, 2023 |
| Toshiba       | Satellite Pro C850-1HD      | Notebook    | [d9ecac6816](https://linux-hardware.org/?probe=d9ecac6816) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [d1175d8dba](https://linux-hardware.org/?probe=d1175d8dba) | Jan 14, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [dda4a9ae38](https://linux-hardware.org/?probe=dda4a9ae38) | Jan 14, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [60b21ee22f](https://linux-hardware.org/?probe=60b21ee22f) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| HP            | 8753                        | Desktop     | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [b8de11c93d](https://linux-hardware.org/?probe=b8de11c93d) | Jan 13, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [05f1e26e96](https://linux-hardware.org/?probe=05f1e26e96) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [1318c97f67](https://linux-hardware.org/?probe=1318c97f67) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [a86e03551c](https://linux-hardware.org/?probe=a86e03551c) | Jan 13, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [b3fed0d61d](https://linux-hardware.org/?probe=b3fed0d61d) | Jan 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [d0391da5d8](https://linux-hardware.org/?probe=d0391da5d8) | Jan 13, 2023 |
| Dell          | Precision 3551              | Notebook    | [66d483ea58](https://linux-hardware.org/?probe=66d483ea58) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [feb261f5f5](https://linux-hardware.org/?probe=feb261f5f5) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [0559975d13](https://linux-hardware.org/?probe=0559975d13) | Jan 13, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [176a3488df](https://linux-hardware.org/?probe=176a3488df) | Jan 12, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [64808b5735](https://linux-hardware.org/?probe=64808b5735) | Jan 12, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8322c3202b](https://linux-hardware.org/?probe=8322c3202b) | Jan 12, 2023 |
| Google        | Sasuke                      | Notebook    | [7241244512](https://linux-hardware.org/?probe=7241244512) | Jan 12, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [611b2fb2a3](https://linux-hardware.org/?probe=611b2fb2a3) | Jan 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [a8d6ad51af](https://linux-hardware.org/?probe=a8d6ad51af) | Jan 12, 2023 |
| AOpen         | D1007 0BBA                  | Desktop     | [63a1413fa3](https://linux-hardware.org/?probe=63a1413fa3) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Acer          | Aspire V5-561G              | Notebook    | [1551c2b90c](https://linux-hardware.org/?probe=1551c2b90c) | Jan 12, 2023 |
| HP            | Pavilion dv6                | Notebook    | [43e7923f04](https://linux-hardware.org/?probe=43e7923f04) | Jan 11, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [828a42310a](https://linux-hardware.org/?probe=828a42310a) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [0d6b77da1a](https://linux-hardware.org/?probe=0d6b77da1a) | Jan 11, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [75584dc48c](https://linux-hardware.org/?probe=75584dc48c) | Jan 11, 2023 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [0daf81fe54](https://linux-hardware.org/?probe=0daf81fe54) | Jan 11, 2023 |
| HP            | 8767 A                      | Desktop     | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| Google        | Sasuke                      | Notebook    | [99ba2827e0](https://linux-hardware.org/?probe=99ba2827e0) | Jan 10, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [53c9ec0145](https://linux-hardware.org/?probe=53c9ec0145) | Jan 10, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [71f6d7912a](https://linux-hardware.org/?probe=71f6d7912a) | Jan 10, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [07d13b3b0b](https://linux-hardware.org/?probe=07d13b3b0b) | Jan 10, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| MSI           | Modern 15 A11M              | Notebook    | [5b55647c95](https://linux-hardware.org/?probe=5b55647c95) | Jan 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [0d0a198245](https://linux-hardware.org/?probe=0d0a198245) | Jan 10, 2023 |
| ASRockRack    | EPC602D8A                   | Desktop     | [2d1d53f993](https://linux-hardware.org/?probe=2d1d53f993) | Jan 10, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [36530dbc41](https://linux-hardware.org/?probe=36530dbc41) | Jan 10, 2023 |
| HP            | 15                          | Notebook    | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9f1f002f51](https://linux-hardware.org/?probe=9f1f002f51) | Jan 09, 2023 |
| Dell          | Precision 7540              | Notebook    | [77b35e556c](https://linux-hardware.org/?probe=77b35e556c) | Jan 09, 2023 |
| MSI           | H310M PRO-D                 | Desktop     | [1ba0a170aa](https://linux-hardware.org/?probe=1ba0a170aa) | Jan 09, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9d476dfade](https://linux-hardware.org/?probe=9d476dfade) | Jan 09, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [4d7677f391](https://linux-hardware.org/?probe=4d7677f391) | Jan 09, 2023 |
| MSI           | MS-7378                     | Desktop     | [965cd11e84](https://linux-hardware.org/?probe=965cd11e84) | Jan 09, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [f4b0c86cfa](https://linux-hardware.org/?probe=f4b0c86cfa) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [1549344aef](https://linux-hardware.org/?probe=1549344aef) | Jan 09, 2023 |
| ASRock        | H87 Performance             | Desktop     | [8e1b7a9033](https://linux-hardware.org/?probe=8e1b7a9033) | Jan 09, 2023 |
| MSI           | H310M PRO-D                 | Desktop     | [e5a8783118](https://linux-hardware.org/?probe=e5a8783118) | Jan 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d3177dc8b3](https://linux-hardware.org/?probe=d3177dc8b3) | Jan 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [77590fdff4](https://linux-hardware.org/?probe=77590fdff4) | Jan 09, 2023 |
| Dell          | XPS 9320                    | Notebook    | [a58b8a72b7](https://linux-hardware.org/?probe=a58b8a72b7) | Jan 09, 2023 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [92d7b143d8](https://linux-hardware.org/?probe=92d7b143d8) | Jan 09, 2023 |
| HP            | Notebook                    | Notebook    | [c4cc7fb9f6](https://linux-hardware.org/?probe=c4cc7fb9f6) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | Desktop     | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [0a7899316d](https://linux-hardware.org/?probe=0a7899316d) | Jan 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ca7597c4fb](https://linux-hardware.org/?probe=ca7597c4fb) | Jan 08, 2023 |
| Dell          | Latitude E6440              | Notebook    | [faeb2d5372](https://linux-hardware.org/?probe=faeb2d5372) | Jan 08, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [1c85ed2f4b](https://linux-hardware.org/?probe=1c85ed2f4b) | Jan 08, 2023 |
| Dell          | Latitude 3450               | Notebook    | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [88714f1928](https://linux-hardware.org/?probe=88714f1928) | Jan 08, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [a303af0bcf](https://linux-hardware.org/?probe=a303af0bcf) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| HP            | Notebook                    | Notebook    | [1174de12fc](https://linux-hardware.org/?probe=1174de12fc) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [953d771250](https://linux-hardware.org/?probe=953d771250) | Jan 08, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [75def9e004](https://linux-hardware.org/?probe=75def9e004) | Jan 07, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| HUAWEI        | MateBook HZ-W09             | Tablet      | [1de7d37b18](https://linux-hardware.org/?probe=1de7d37b18) | Jan 07, 2023 |
| Dell          | Latitude 9430               | Convertible | [d04e9626cf](https://linux-hardware.org/?probe=d04e9626cf) | Jan 07, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [d742870a51](https://linux-hardware.org/?probe=d742870a51) | Jan 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c011ef538e](https://linux-hardware.org/?probe=c011ef538e) | Jan 07, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [84fc096e00](https://linux-hardware.org/?probe=84fc096e00) | Jan 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [fae1531801](https://linux-hardware.org/?probe=fae1531801) | Jan 07, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [c5a401b596](https://linux-hardware.org/?probe=c5a401b596) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| HP            | 8399                        | Desktop     | [eccd5189f5](https://linux-hardware.org/?probe=eccd5189f5) | Jan 07, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [dac20769fc](https://linux-hardware.org/?probe=dac20769fc) | Jan 07, 2023 |
| Dell          | Latitude E6230              | Notebook    | [7a7cd04af0](https://linux-hardware.org/?probe=7a7cd04af0) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [c08993d504](https://linux-hardware.org/?probe=c08993d504) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [d39ec5e414](https://linux-hardware.org/?probe=d39ec5e414) | Jan 07, 2023 |
| HP            | 250 G3                      | Notebook    | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| Dell          | Latitude 7520               | Notebook    | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [05356ec25d](https://linux-hardware.org/?probe=05356ec25d) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [391d13c7ba](https://linux-hardware.org/?probe=391d13c7ba) | Jan 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ce4648337e](https://linux-hardware.org/?probe=ce4648337e) | Jan 05, 2023 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| HP            | 350 G1                      | Notebook    | [09f234d211](https://linux-hardware.org/?probe=09f234d211) | Jan 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ce1a1d086](https://linux-hardware.org/?probe=3ce1a1d086) | Jan 05, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [667c8405f0](https://linux-hardware.org/?probe=667c8405f0) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [dca6d06bf4](https://linux-hardware.org/?probe=dca6d06bf4) | Jan 05, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [591d1b0ea9](https://linux-hardware.org/?probe=591d1b0ea9) | Jan 04, 2023 |
| Intel         | B75                         | Desktop     | [bb046d2540](https://linux-hardware.org/?probe=bb046d2540) | Jan 04, 2023 |
| Dell          | XPS 9320                    | Notebook    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | 1005P                       | Notebook    | [7ccbcf9b28](https://linux-hardware.org/?probe=7ccbcf9b28) | Jan 04, 2023 |
| HP            | 15                          | Notebook    | [d0aae7c4b7](https://linux-hardware.org/?probe=d0aae7c4b7) | Jan 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9496d56fab](https://linux-hardware.org/?probe=9496d56fab) | Jan 04, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [a7563dd7b2](https://linux-hardware.org/?probe=a7563dd7b2) | Jan 04, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9aadf12194](https://linux-hardware.org/?probe=9aadf12194) | Jan 04, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [3b43c0575b](https://linux-hardware.org/?probe=3b43c0575b) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0e9393e884](https://linux-hardware.org/?probe=0e9393e884) | Jan 03, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [31dfc11401](https://linux-hardware.org/?probe=31dfc11401) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [1497921a99](https://linux-hardware.org/?probe=1497921a99) | Jan 03, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [f01e4b79c2](https://linux-hardware.org/?probe=f01e4b79c2) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASRock        | H77M                        | Desktop     | [b7f415926b](https://linux-hardware.org/?probe=b7f415926b) | Jan 03, 2023 |
| ASRock        | H77M                        | Desktop     | [82c399688f](https://linux-hardware.org/?probe=82c399688f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| HP            | 350 G1                      | Notebook    | [0929eec44b](https://linux-hardware.org/?probe=0929eec44b) | Jan 03, 2023 |
| Pegatron      | Benicia                     | Desktop     | [008e5d125e](https://linux-hardware.org/?probe=008e5d125e) | Jan 03, 2023 |
| Pegatron      | Benicia                     | Desktop     | [0d47a13713](https://linux-hardware.org/?probe=0d47a13713) | Jan 03, 2023 |
| Pegatron      | Benicia                     | Desktop     | [25466113c1](https://linux-hardware.org/?probe=25466113c1) | Jan 02, 2023 |
| MSI           | H310M PRO-D                 | Desktop     | [27482bbe30](https://linux-hardware.org/?probe=27482bbe30) | Jan 02, 2023 |
| Dell          | 0RF703                      | Desktop     | [66180b5fdf](https://linux-hardware.org/?probe=66180b5fdf) | Jan 02, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [90c0016c38](https://linux-hardware.org/?probe=90c0016c38) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| Dell          | Latitude 7410               | Notebook    | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [1aa3c58aa5](https://linux-hardware.org/?probe=1aa3c58aa5) | Jan 01, 2023 |
| Acer          | TravelMate P253             | Notebook    | [a90b917fbe](https://linux-hardware.org/?probe=a90b917fbe) | Jan 01, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [b953257b12](https://linux-hardware.org/?probe=b953257b12) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | Desktop     | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| HP            | 82B4                        | Desktop     | [4e2d86906f](https://linux-hardware.org/?probe=4e2d86906f) | Jan 01, 2023 |
| Acer          | TravelMate 5735Z            | Notebook    | [9fa5978af4](https://linux-hardware.org/?probe=9fa5978af4) | Jan 01, 2023 |
| Dell          | XPS 9320                    | Notebook    | [08626b8d57](https://linux-hardware.org/?probe=08626b8d57) | Jan 01, 2023 |
| Google        | Blooglet                    | Notebook    | [711ca24e79](https://linux-hardware.org/?probe=711ca24e79) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [527a92f562](https://linux-hardware.org/?probe=527a92f562) | Dec 31, 2022 |
| HP            | Notebook                    | Notebook    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| ASUSTek       | ProArt StudioBook H5600Q... | Notebook    | [07ca2ed63d](https://linux-hardware.org/?probe=07ca2ed63d) | Dec 31, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [afdda0ad31](https://linux-hardware.org/?probe=afdda0ad31) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3659d7377d](https://linux-hardware.org/?probe=3659d7377d) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | Notebook    | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Chuwi         | HeroBook                    | Notebook    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | Notebook    | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [42a9dc760d](https://linux-hardware.org/?probe=42a9dc760d) | Dec 30, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [bf0f36d69a](https://linux-hardware.org/?probe=bf0f36d69a) | Dec 30, 2022 |
| HP            | 255 G3                      | Notebook    | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| BESSTAR Te... | C-J34 Pro                   | Desktop     | [1b54a52c3c](https://linux-hardware.org/?probe=1b54a52c3c) | Dec 30, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [10f0b28589](https://linux-hardware.org/?probe=10f0b28589) | Dec 29, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0ee655e2cc](https://linux-hardware.org/?probe=0ee655e2cc) | Dec 29, 2022 |
| HP            | 0AE8h                       | Desktop     | [b23a6da065](https://linux-hardware.org/?probe=b23a6da065) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [8a4ef9ab88](https://linux-hardware.org/?probe=8a4ef9ab88) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | Notebook    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [9294bf57da](https://linux-hardware.org/?probe=9294bf57da) | Dec 28, 2022 |
| Lenovo        | ThinkPad E480 20KQS13M00    | Notebook    | [fb7e2874d3](https://linux-hardware.org/?probe=fb7e2874d3) | Dec 28, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [efdc6bb5cb](https://linux-hardware.org/?probe=efdc6bb5cb) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [d0969c6a4c](https://linux-hardware.org/?probe=d0969c6a4c) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [8a4dce4662](https://linux-hardware.org/?probe=8a4dce4662) | Dec 28, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [92155ba882](https://linux-hardware.org/?probe=92155ba882) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6297565fda](https://linux-hardware.org/?probe=6297565fda) | Dec 28, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [0dede5b37a](https://linux-hardware.org/?probe=0dede5b37a) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| System76      | Darter Pro                  | Notebook    | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [79427500b5](https://linux-hardware.org/?probe=79427500b5) | Dec 28, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [05ae1afd3f](https://linux-hardware.org/?probe=05ae1afd3f) | Dec 28, 2022 |
| HP            | 0AE8h                       | Desktop     | [c1bd1ff073](https://linux-hardware.org/?probe=c1bd1ff073) | Dec 27, 2022 |
| Teclast       | F15Plus 2                   | Notebook    | [71564a5900](https://linux-hardware.org/?probe=71564a5900) | Dec 27, 2022 |
| Teclast       | F15Plus 2                   | Notebook    | [4d10c4922e](https://linux-hardware.org/?probe=4d10c4922e) | Dec 27, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [57bfe7c99d](https://linux-hardware.org/?probe=57bfe7c99d) | Dec 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [ccce0caf7e](https://linux-hardware.org/?probe=ccce0caf7e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [039600625a](https://linux-hardware.org/?probe=039600625a) | Dec 27, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [4eda9a1749](https://linux-hardware.org/?probe=4eda9a1749) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | Notebook    | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| System76      | Darter Pro                  | Notebook    | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [78512365ca](https://linux-hardware.org/?probe=78512365ca) | Dec 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [9843ba5174](https://linux-hardware.org/?probe=9843ba5174) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | Desktop     | [b2acfa6e70](https://linux-hardware.org/?probe=b2acfa6e70) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | Desktop     | [59e6ec4132](https://linux-hardware.org/?probe=59e6ec4132) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [10e22b317f](https://linux-hardware.org/?probe=10e22b317f) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [6a2c20cb74](https://linux-hardware.org/?probe=6a2c20cb74) | Dec 26, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2df8b7768a](https://linux-hardware.org/?probe=2df8b7768a) | Dec 26, 2022 |
| HP            | Compaq 6730s                | Notebook    | [ac1ae104e8](https://linux-hardware.org/?probe=ac1ae104e8) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| HP            | Compaq 6730s                | Notebook    | [0cc88159aa](https://linux-hardware.org/?probe=0cc88159aa) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [7e46b9fd5b](https://linux-hardware.org/?probe=7e46b9fd5b) | Dec 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [4665d79293](https://linux-hardware.org/?probe=4665d79293) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ff90a6a029](https://linux-hardware.org/?probe=ff90a6a029) | Dec 25, 2022 |
| MSI           | Boston                      | Desktop     | [5ffbd4e9a5](https://linux-hardware.org/?probe=5ffbd4e9a5) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [faba7b00c6](https://linux-hardware.org/?probe=faba7b00c6) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [384d09ccdb](https://linux-hardware.org/?probe=384d09ccdb) | Dec 25, 2022 |
| Dell          | 0DN075                      | Desktop     | [9fd08be389](https://linux-hardware.org/?probe=9fd08be389) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| AMI           | Cherry Trail FFD            | Desktop     | [7070bf387d](https://linux-hardware.org/?probe=7070bf387d) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Foxconn       | 2AA9                        | Desktop     | [07650be639](https://linux-hardware.org/?probe=07650be639) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | Notebook    | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [d53469cd41](https://linux-hardware.org/?probe=d53469cd41) | Dec 23, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [568df9daf7](https://linux-hardware.org/?probe=568df9daf7) | Dec 23, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [c36792aeaa](https://linux-hardware.org/?probe=c36792aeaa) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [9ddf91aa1b](https://linux-hardware.org/?probe=9ddf91aa1b) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | Desktop     | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [9e19c2db67](https://linux-hardware.org/?probe=9e19c2db67) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| Timi          | TM1701                      | Notebook    | [2f28d7e2dc](https://linux-hardware.org/?probe=2f28d7e2dc) | Dec 23, 2022 |
| Timi          | TM1701                      | Notebook    | [dfb4f8774f](https://linux-hardware.org/?probe=dfb4f8774f) | Dec 23, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Medion        | X6816                       | Notebook    | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | Notebook    | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [8c936284b0](https://linux-hardware.org/?probe=8c936284b0) | Dec 22, 2022 |
| ASRock        | FM2A88M-HD+                 | Desktop     | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [ec808658f8](https://linux-hardware.org/?probe=ec808658f8) | Dec 22, 2022 |
| Monster       | TULPAR T5 V20.1             | Notebook    | [23cb6e06f8](https://linux-hardware.org/?probe=23cb6e06f8) | Dec 22, 2022 |
| Acer          | Aspire M3920                | Desktop     | [803cd5d8f9](https://linux-hardware.org/?probe=803cd5d8f9) | Dec 22, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [01aae2d5df](https://linux-hardware.org/?probe=01aae2d5df) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | Notebook    | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a62d8c781d](https://linux-hardware.org/?probe=a62d8c781d) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| Packard Be... | DOT S                       | Notebook    | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [20150bbe50](https://linux-hardware.org/?probe=20150bbe50) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [fc162d4cb2](https://linux-hardware.org/?probe=fc162d4cb2) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [1cdb02c6db](https://linux-hardware.org/?probe=1cdb02c6db) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [5e48f71064](https://linux-hardware.org/?probe=5e48f71064) | Dec 20, 2022 |
| HP            | Sona                        | Notebook    | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [aa6f672c23](https://linux-hardware.org/?probe=aa6f672c23) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [c7b2f48d96](https://linux-hardware.org/?probe=c7b2f48d96) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [d949885cee](https://linux-hardware.org/?probe=d949885cee) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | Notebook    | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3b38fc673c](https://linux-hardware.org/?probe=3b38fc673c) | Dec 19, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [cf93a75cf0](https://linux-hardware.org/?probe=cf93a75cf0) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| HP            | 829E                        | Mini pc     | [effdd89e26](https://linux-hardware.org/?probe=effdd89e26) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [7808d8a51f](https://linux-hardware.org/?probe=7808d8a51f) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ad506ad64e](https://linux-hardware.org/?probe=ad506ad64e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [831f650b05](https://linux-hardware.org/?probe=831f650b05) | Dec 19, 2022 |
| HP            | 18E7                        | Desktop     | [9f601a9f1a](https://linux-hardware.org/?probe=9f601a9f1a) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | Notebook    | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [686a93a02a](https://linux-hardware.org/?probe=686a93a02a) | Dec 19, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8e10fc1464](https://linux-hardware.org/?probe=8e10fc1464) | Dec 18, 2022 |
| ASUSTek       | 900SD                       | Notebook    | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [14ea50f3b2](https://linux-hardware.org/?probe=14ea50f3b2) | Dec 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2d046f9339](https://linux-hardware.org/?probe=2d046f9339) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7dc7a80819](https://linux-hardware.org/?probe=7dc7a80819) | Dec 18, 2022 |
| Acer          | TravelMate P253             | Notebook    | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [262849f0f6](https://linux-hardware.org/?probe=262849f0f6) | Dec 18, 2022 |
| Intel         | H55                         | Desktop     | [a5033f178f](https://linux-hardware.org/?probe=a5033f178f) | Dec 18, 2022 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [1e294ecd38](https://linux-hardware.org/?probe=1e294ecd38) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [ab6fd91b71](https://linux-hardware.org/?probe=ab6fd91b71) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [dc92ebcc7c](https://linux-hardware.org/?probe=dc92ebcc7c) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [c2db38b403](https://linux-hardware.org/?probe=c2db38b403) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [a54756ab6f](https://linux-hardware.org/?probe=a54756ab6f) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [fcb9b3ba60](https://linux-hardware.org/?probe=fcb9b3ba60) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| MSI           | MS-B1711                    | Desktop     | [a5b142e258](https://linux-hardware.org/?probe=a5b142e258) | Dec 17, 2022 |
| Unknown       | AM02                        | Mini pc     | [e60a6e7777](https://linux-hardware.org/?probe=e60a6e7777) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [5e5909e93f](https://linux-hardware.org/?probe=5e5909e93f) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [feb5e321dc](https://linux-hardware.org/?probe=feb5e321dc) | Dec 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| Acer          | TravelMate P253             | Notebook    | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [dcf616e068](https://linux-hardware.org/?probe=dcf616e068) | Dec 16, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [25ba267a65](https://linux-hardware.org/?probe=25ba267a65) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [14d39a67c2](https://linux-hardware.org/?probe=14d39a67c2) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [fc99e84afd](https://linux-hardware.org/?probe=fc99e84afd) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| Alienware     | 15                          | Notebook    | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| MSI           | AM1I                        | Desktop     | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| MSI           | AM1I                        | Desktop     | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [dd664077fe](https://linux-hardware.org/?probe=dd664077fe) | Dec 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [d9c3d0a5cd](https://linux-hardware.org/?probe=d9c3d0a5cd) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e69127d249](https://linux-hardware.org/?probe=e69127d249) | Dec 15, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [f722162e15](https://linux-hardware.org/?probe=f722162e15) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5e8318b8b8](https://linux-hardware.org/?probe=5e8318b8b8) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d5c9abda1e](https://linux-hardware.org/?probe=d5c9abda1e) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [d39c428918](https://linux-hardware.org/?probe=d39c428918) | Dec 15, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [a9d66f9686](https://linux-hardware.org/?probe=a9d66f9686) | Dec 14, 2022 |
| HP            | Compaq 6735s                | Notebook    | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Samsung       | 750XDA                      | Notebook    | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| HP            | 843C                        | Desktop     | [e647aa1207](https://linux-hardware.org/?probe=e647aa1207) | Dec 14, 2022 |
| HP            | 2AF7                        | Desktop     | [089612dee6](https://linux-hardware.org/?probe=089612dee6) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| HP            | 2AF7                        | Desktop     | [2c6c08c8b8](https://linux-hardware.org/?probe=2c6c08c8b8) | Dec 14, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [c8207bdc43](https://linux-hardware.org/?probe=c8207bdc43) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | Notebook    | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [8061225355](https://linux-hardware.org/?probe=8061225355) | Dec 13, 2022 |
| PC Special... | Elimina Iv 17               | Notebook    | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [ff5b82cee3](https://linux-hardware.org/?probe=ff5b82cee3) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [48f3c01650](https://linux-hardware.org/?probe=48f3c01650) | Dec 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [3d835ed57d](https://linux-hardware.org/?probe=3d835ed57d) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [45630329df](https://linux-hardware.org/?probe=45630329df) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [9a73e431ee](https://linux-hardware.org/?probe=9a73e431ee) | Dec 12, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [1e0eec72b2](https://linux-hardware.org/?probe=1e0eec72b2) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [2212bad256](https://linux-hardware.org/?probe=2212bad256) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [20cb7a525a](https://linux-hardware.org/?probe=20cb7a525a) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [367579550b](https://linux-hardware.org/?probe=367579550b) | Dec 11, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| MSI           | Boston                      | Desktop     | [4cc25e826f](https://linux-hardware.org/?probe=4cc25e826f) | Dec 11, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [e92985332e](https://linux-hardware.org/?probe=e92985332e) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Teclast       | F5                          | Convertible | [02e54783b6](https://linux-hardware.org/?probe=02e54783b6) | Dec 11, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [7b9b41bfb5](https://linux-hardware.org/?probe=7b9b41bfb5) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [63128e9c0f](https://linux-hardware.org/?probe=63128e9c0f) | Dec 11, 2022 |
| Google        | Blooglet                    | Notebook    | [a9d65d2144](https://linux-hardware.org/?probe=a9d65d2144) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [26c1e67dff](https://linux-hardware.org/?probe=26c1e67dff) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [e143b181a1](https://linux-hardware.org/?probe=e143b181a1) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| HP            | Pavilion dv6000 (RY649EA... | Notebook    | [9deecc89f5](https://linux-hardware.org/?probe=9deecc89f5) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [c9313e3820](https://linux-hardware.org/?probe=c9313e3820) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [746c717d34](https://linux-hardware.org/?probe=746c717d34) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4d78d14f00](https://linux-hardware.org/?probe=4d78d14f00) | Dec 10, 2022 |
| Toshiba       | Satellite C70-C-11L         | Notebook    | [8de407e526](https://linux-hardware.org/?probe=8de407e526) | Dec 09, 2022 |
| HP            | 250 G3                      | Notebook    | [7e7b65bb5f](https://linux-hardware.org/?probe=7e7b65bb5f) | Dec 09, 2022 |
| HP            | 250 G3                      | Notebook    | [170a8b35c6](https://linux-hardware.org/?probe=170a8b35c6) | Dec 09, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [4c0af21017](https://linux-hardware.org/?probe=4c0af21017) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| Google        | Blooglet                    | Notebook    | [241c0f4331](https://linux-hardware.org/?probe=241c0f4331) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| Unknown       | Unknown                     | Soc         | [c2f69bb6ef](https://linux-hardware.org/?probe=c2f69bb6ef) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [970f8e990b](https://linux-hardware.org/?probe=970f8e990b) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [0e7da55713](https://linux-hardware.org/?probe=0e7da55713) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | Notebook    | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| Acer          | Veriton N2620G              | Desktop     | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | Notebook    | [f470667df1](https://linux-hardware.org/?probe=f470667df1) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | Notebook    | [2562e31e5a](https://linux-hardware.org/?probe=2562e31e5a) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [f4bf9ede5b](https://linux-hardware.org/?probe=f4bf9ede5b) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8745419f51](https://linux-hardware.org/?probe=8745419f51) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [f3774cb1c4](https://linux-hardware.org/?probe=f3774cb1c4) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| Dell          | 0RM5DR A00                  | Desktop     | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| Google        | Sasuke                      | Notebook    | [527f49b0ae](https://linux-hardware.org/?probe=527f49b0ae) | Dec 07, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [a8aa92bfed](https://linux-hardware.org/?probe=a8aa92bfed) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [768329e263](https://linux-hardware.org/?probe=768329e263) | Dec 07, 2022 |
| Google        | Sasuke                      | Notebook    | [5bd0b833cb](https://linux-hardware.org/?probe=5bd0b833cb) | Dec 07, 2022 |
| ASRock        | Z170 Extreme7+              | Desktop     | [15f86800ee](https://linux-hardware.org/?probe=15f86800ee) | Dec 07, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [9d8dee4e41](https://linux-hardware.org/?probe=9d8dee4e41) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [fd3597e4bf](https://linux-hardware.org/?probe=fd3597e4bf) | Dec 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [10fea00e5a](https://linux-hardware.org/?probe=10fea00e5a) | Dec 06, 2022 |
| HP            | 843C                        | Desktop     | [278cbd2708](https://linux-hardware.org/?probe=278cbd2708) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [5e155a318e](https://linux-hardware.org/?probe=5e155a318e) | Dec 06, 2022 |
| HP            | 0A64h                       | Desktop     | [58658d8b61](https://linux-hardware.org/?probe=58658d8b61) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| MSI           | MS-B1711                    | Desktop     | [1fbaa02605](https://linux-hardware.org/?probe=1fbaa02605) | Dec 05, 2022 |
| MSI           | Boston                      | Desktop     | [fd25ac3a2e](https://linux-hardware.org/?probe=fd25ac3a2e) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [d0230b5c69](https://linux-hardware.org/?probe=d0230b5c69) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [af27460f17](https://linux-hardware.org/?probe=af27460f17) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [8c3beba1e1](https://linux-hardware.org/?probe=8c3beba1e1) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [84bc78ebb6](https://linux-hardware.org/?probe=84bc78ebb6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | Desktop     | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [f2d1d7fb3d](https://linux-hardware.org/?probe=f2d1d7fb3d) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f34caf87d5](https://linux-hardware.org/?probe=f34caf87d5) | Dec 03, 2022 |
| MSI           | X99S SLI PLUS               | Desktop     | [03a2e66a94](https://linux-hardware.org/?probe=03a2e66a94) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d42d3210f](https://linux-hardware.org/?probe=7d42d3210f) | Dec 03, 2022 |
| HP            | 2B52                        | Desktop     | [e2e8bdd4f6](https://linux-hardware.org/?probe=e2e8bdd4f6) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [dc233f857f](https://linux-hardware.org/?probe=dc233f857f) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| HP            | Pavilion 15                 | Notebook    | [87de142ecd](https://linux-hardware.org/?probe=87de142ecd) | Dec 03, 2022 |
| Google        | Blooglet                    | Notebook    | [045f75ab43](https://linux-hardware.org/?probe=045f75ab43) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Lenovo        | G580 2189                   | Notebook    | [80fe3f7171](https://linux-hardware.org/?probe=80fe3f7171) | Dec 03, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [91edd3827d](https://linux-hardware.org/?probe=91edd3827d) | Dec 02, 2022 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [4dc73d8f69](https://linux-hardware.org/?probe=4dc73d8f69) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [709c3a84ea](https://linux-hardware.org/?probe=709c3a84ea) | Dec 02, 2022 |
| HP            | Unknown                     | Notebook    | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| HP            | Notebook                    | Notebook    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ee17f7d657](https://linux-hardware.org/?probe=ee17f7d657) | Dec 02, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e4fd5dfa0e](https://linux-hardware.org/?probe=e4fd5dfa0e) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9d27bb4f90](https://linux-hardware.org/?probe=9d27bb4f90) | Dec 01, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1df1f552ff](https://linux-hardware.org/?probe=1df1f552ff) | Dec 01, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [961f58c143](https://linux-hardware.org/?probe=961f58c143) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [a8236e24a5](https://linux-hardware.org/?probe=a8236e24a5) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [ab421fd2d4](https://linux-hardware.org/?probe=ab421fd2d4) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [198d7f2534](https://linux-hardware.org/?probe=198d7f2534) | Dec 01, 2022 |
| ASUSTek       | K52F                        | Notebook    | [63c08600c3](https://linux-hardware.org/?probe=63c08600c3) | Dec 01, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4276cc2cb9](https://linux-hardware.org/?probe=4276cc2cb9) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [4f517e816d](https://linux-hardware.org/?probe=4f517e816d) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| MSI           | Boston                      | Desktop     | [0564f7ed2d](https://linux-hardware.org/?probe=0564f7ed2d) | Nov 30, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [dfe92c80c1](https://linux-hardware.org/?probe=dfe92c80c1) | Nov 30, 2022 |
| Dell          | Studio 1558                 | Notebook    | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [0866a64897](https://linux-hardware.org/?probe=0866a64897) | Nov 30, 2022 |
| Apple         | MacBookAir8,1               | Notebook    | [7581ef0e85](https://linux-hardware.org/?probe=7581ef0e85) | Nov 29, 2022 |
| IBM           | MSI-9151 Boards             | Desktop     | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| HP            | 3048h                       | Desktop     | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [719921de81](https://linux-hardware.org/?probe=719921de81) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [f998b6a0d9](https://linux-hardware.org/?probe=f998b6a0d9) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [d5702f8b2d](https://linux-hardware.org/?probe=d5702f8b2d) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [640a031786](https://linux-hardware.org/?probe=640a031786) | Nov 29, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [cbb0c1dca7](https://linux-hardware.org/?probe=cbb0c1dca7) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| HP            | 843B                        | Desktop     | [19bd35484c](https://linux-hardware.org/?probe=19bd35484c) | Nov 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [c306dcfa4f](https://linux-hardware.org/?probe=c306dcfa4f) | Nov 27, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [44a305db4d](https://linux-hardware.org/?probe=44a305db4d) | Nov 27, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [63d2134051](https://linux-hardware.org/?probe=63d2134051) | Nov 27, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [8f510e55e2](https://linux-hardware.org/?probe=8f510e55e2) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | G5 5587                     | Notebook    | [689db41249](https://linux-hardware.org/?probe=689db41249) | Nov 27, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [f397d89e9b](https://linux-hardware.org/?probe=f397d89e9b) | Nov 27, 2022 |
| Lenovo        | ThinkPad X280 20KES2DD0D    | Notebook    | [394b24459c](https://linux-hardware.org/?probe=394b24459c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [b5260b5609](https://linux-hardware.org/?probe=b5260b5609) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [eb0921d1f6](https://linux-hardware.org/?probe=eb0921d1f6) | Nov 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [57e4892065](https://linux-hardware.org/?probe=57e4892065) | Nov 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ce7815f106](https://linux-hardware.org/?probe=ce7815f106) | Nov 26, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [949860da0f](https://linux-hardware.org/?probe=949860da0f) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [0569fa8cc9](https://linux-hardware.org/?probe=0569fa8cc9) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | Notebook    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| Sony          | SVP1121X9EB                 | Notebook    | [78df785a47](https://linux-hardware.org/?probe=78df785a47) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| ASUSTek       | X202E                       | Notebook    | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| HP            | 3397                        | Desktop     | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [d044aabfec](https://linux-hardware.org/?probe=d044aabfec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Dell          | Latitude 3450               | Notebook    | [d7af694917](https://linux-hardware.org/?probe=d7af694917) | Nov 25, 2022 |
| ASUSTek       | P8H61-I LX/RM/SI            | Desktop     | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| MSI           | H81M-E33                    | Desktop     | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Alienware     | 15                          | Notebook    | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [30081f61ca](https://linux-hardware.org/?probe=30081f61ca) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [9e33d3b8f1](https://linux-hardware.org/?probe=9e33d3b8f1) | Nov 24, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [894c4e9ebf](https://linux-hardware.org/?probe=894c4e9ebf) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [7ce85c6de5](https://linux-hardware.org/?probe=7ce85c6de5) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [fd8121fecd](https://linux-hardware.org/?probe=fd8121fecd) | Nov 22, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [14c0f082d8](https://linux-hardware.org/?probe=14c0f082d8) | Nov 22, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [e497c428f0](https://linux-hardware.org/?probe=e497c428f0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [d0bd92a5e0](https://linux-hardware.org/?probe=d0bd92a5e0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [b4cc2dc00b](https://linux-hardware.org/?probe=b4cc2dc00b) | Nov 22, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [dc74022dc5](https://linux-hardware.org/?probe=dc74022dc5) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Microtech     | etabPro4+                   | Tablet      | [4fe8061ebd](https://linux-hardware.org/?probe=4fe8061ebd) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| HP            | 83E2                        | Desktop     | [b04e1014da](https://linux-hardware.org/?probe=b04e1014da) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | Notebook    | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Latitude 9420               | Notebook    | [ddf8c8749c](https://linux-hardware.org/?probe=ddf8c8749c) | Nov 21, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [a94bd1fd5a](https://linux-hardware.org/?probe=a94bd1fd5a) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [7ccd7842c1](https://linux-hardware.org/?probe=7ccd7842c1) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| HP            | 2AF3                        | Desktop     | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Microtech     | etabPro4+                   | Tablet      | [ccf3636310](https://linux-hardware.org/?probe=ccf3636310) | Nov 21, 2022 |
| Google        | Sasuke                      | Notebook    | [35330e59ad](https://linux-hardware.org/?probe=35330e59ad) | Nov 20, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [aaa2d66240](https://linux-hardware.org/?probe=aaa2d66240) | Nov 20, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3ecbc7acb4](https://linux-hardware.org/?probe=3ecbc7acb4) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [07ca09898f](https://linux-hardware.org/?probe=07ca09898f) | Nov 20, 2022 |
| HP            | Notebook                    | Notebook    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [b9d2b8c218](https://linux-hardware.org/?probe=b9d2b8c218) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Acer          | aspire5740                  | Notebook    | [6cdc4f5cfc](https://linux-hardware.org/?probe=6cdc4f5cfc) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [835c000337](https://linux-hardware.org/?probe=835c000337) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | Desktop     | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [4f04b7d627](https://linux-hardware.org/?probe=4f04b7d627) | Nov 19, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [3b15bcfd88](https://linux-hardware.org/?probe=3b15bcfd88) | Nov 19, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Olidata       | T7700                       | Notebook    | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f1724d63d5](https://linux-hardware.org/?probe=f1724d63d5) | Nov 19, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c2d79be90d](https://linux-hardware.org/?probe=c2d79be90d) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| HP            | Presario CQ58               | Notebook    | [fc1d1892ef](https://linux-hardware.org/?probe=fc1d1892ef) | Nov 19, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [c11ad764af](https://linux-hardware.org/?probe=c11ad764af) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| Sony          | VPCYA1C5E                   | Notebook    | [416067b991](https://linux-hardware.org/?probe=416067b991) | Nov 18, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [f58db71272](https://linux-hardware.org/?probe=f58db71272) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e18aef24ac](https://linux-hardware.org/?probe=e18aef24ac) | Nov 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Acer          | E946GZ                      | Desktop     | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | Notebook    | [aa7f8583b6](https://linux-hardware.org/?probe=aa7f8583b6) | Nov 17, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [3f03d0cbaa](https://linux-hardware.org/?probe=3f03d0cbaa) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | Notebook    | [c15d4ee015](https://linux-hardware.org/?probe=c15d4ee015) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | Notebook    | [b5106cb728](https://linux-hardware.org/?probe=b5106cb728) | Nov 17, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| HP            | 250 G4                      | Notebook    | [3f2660a101](https://linux-hardware.org/?probe=3f2660a101) | Nov 16, 2022 |
| HP            | 250 G4                      | Notebook    | [cc4a368fd3](https://linux-hardware.org/?probe=cc4a368fd3) | Nov 16, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [61f5cf6214](https://linux-hardware.org/?probe=61f5cf6214) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8312099aa4](https://linux-hardware.org/?probe=8312099aa4) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [e2492ba1c1](https://linux-hardware.org/?probe=e2492ba1c1) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [df8344d098](https://linux-hardware.org/?probe=df8344d098) | Nov 16, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [cbfdfc82b4](https://linux-hardware.org/?probe=cbfdfc82b4) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Fujitsu       | LIFEBOOK E557               | Notebook    | [a57972523b](https://linux-hardware.org/?probe=a57972523b) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| System76      | Oryx Pro                    | Notebook    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | Desktop     | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| Huanan        | X99-F8                      | Desktop     | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| ASUSTek       | N751JX                      | Notebook    | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Olidata       | T7700                       | Notebook    | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Microtech     | ebookLite                   | Notebook    | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [211fdda09b](https://linux-hardware.org/?probe=211fdda09b) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [9fe2a7d245](https://linux-hardware.org/?probe=9fe2a7d245) | Nov 14, 2022 |
| Acer          | TravelMate P259-G2-MG       | Notebook    | [27d3da0f8a](https://linux-hardware.org/?probe=27d3da0f8a) | Nov 14, 2022 |
| HP            | 802F                        | Desktop     | [8e7dbc3f9f](https://linux-hardware.org/?probe=8e7dbc3f9f) | Nov 14, 2022 |
| HP            | 802F                        | Desktop     | [89441a53f7](https://linux-hardware.org/?probe=89441a53f7) | Nov 14, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [c3573fb12b](https://linux-hardware.org/?probe=c3573fb12b) | Nov 14, 2022 |
| Sony          | VGN-NS21M_W                 | Notebook    | [b3f4aef7a4](https://linux-hardware.org/?probe=b3f4aef7a4) | Nov 14, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4e6d343f5c](https://linux-hardware.org/?probe=4e6d343f5c) | Nov 14, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [99c1eee67d](https://linux-hardware.org/?probe=99c1eee67d) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| HP            | 3397                        | Desktop     | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | Desktop     | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | Notebook    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | ZH77A-G43                   | Desktop     | [a8f49c1ad8](https://linux-hardware.org/?probe=a8f49c1ad8) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | Notebook    | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7d72f2fa26](https://linux-hardware.org/?probe=7d72f2fa26) | Nov 12, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3                    | Desktop     | [7c25342680](https://linux-hardware.org/?probe=7c25342680) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [768efc0c32](https://linux-hardware.org/?probe=768efc0c32) | Nov 12, 2022 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Acer          | aspire5740                  | Notebook    | [5218638790](https://linux-hardware.org/?probe=5218638790) | Nov 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 889       | 12.85%  |
| Ubuntu 18.04                 | 557       | 8.05%   |
| Ubuntu 22.04                 | 327       | 4.73%   |
| OpenMandriva 4.2             | 213       | 3.08%   |
| OpenMandriva 4.3             | 177       | 2.56%   |
| Arch Rolling                 | 169       | 2.44%   |
| Debian 11                    | 160       | 2.31%   |
| Fedora 36                    | 146       | 2.11%   |
| Ubuntu 20.10                 | 129       | 1.86%   |
| Arch                         | 123       | 1.78%   |
| Ubuntu 19.10                 | 120       | 1.73%   |
| Ubuntu 19.04                 | 108       | 1.56%   |
| Xubuntu 18.04                | 107       | 1.55%   |
| KDE neon 20.04               | 102       | 1.47%   |
| Xubuntu 20.04                | 100       | 1.45%   |
| Ubuntu 21.10                 | 96        | 1.39%   |
| Linux Mint 20.3              | 93        | 1.34%   |
| Pop!_OS 22.04                | 89        | 1.29%   |
| Ubuntu 22.10                 | 88        | 1.27%   |
| Zorin 16                     | 84        | 1.21%   |
| Ubuntu 21.04                 | 83        | 1.2%    |
| Linux Mint 21                | 81        | 1.17%   |
| Debian 10                    | 80        | 1.16%   |
| Zorin 15                     | 69        | 1%      |
| Ubuntu 18.10                 | 68        | 0.98%   |
| Fedora 35                    | 68        | 0.98%   |
| Kubuntu 20.04                | 66        | 0.95%   |
| Linux Mint 19.3              | 65        | 0.94%   |
| ROSA R10                     | 62        | 0.9%    |
| Manjaro                      | 61        | 0.88%   |
| Linux Mint 20.1              | 60        | 0.87%   |
| Linux Mint 20.2              | 59        | 0.85%   |
| Pop!_OS 20.10                | 57        | 0.82%   |
| Linux Mint 20                | 57        | 0.82%   |
| Linux Mint 21.1              | 56        | 0.81%   |
| Fedora 37                    | 56        | 0.81%   |
| EndeavourOS Rolling          | 56        | 0.81%   |
| Fedora 33                    | 54        | 0.78%   |
| Kubuntu 22.04                | 52        | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 46        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2376      | 36.18%  |
| OpenMandriva  | 493       | 7.51%   |
| Linux Mint    | 477       | 7.26%   |
| Fedora        | 416       | 6.33%   |
| Debian        | 302       | 4.6%    |
| Xubuntu       | 288       | 4.39%   |
| Arch          | 286       | 4.36%   |
| Pop!_OS       | 239       | 3.64%   |
| Manjaro       | 201       | 3.06%   |
| ROSA          | 179       | 2.73%   |
| Kubuntu       | 179       | 2.73%   |
| Zorin         | 163       | 2.48%   |
| KDE neon      | 134       | 2.04%   |
| Lubuntu       | 85        | 1.29%   |
| Ubuntu MATE   | 68        | 1.04%   |
| openSUSE      | 65        | 0.99%   |
| EndeavourOS   | 62        | 0.94%   |
| Elementary    | 55        | 0.84%   |
| Endless       | 47        | 0.72%   |
| Ubuntu Unity  | 40        | 0.61%   |
| Clear Linux   | 36        | 0.55%   |
| BlackPanther  | 35        | 0.53%   |
| ArcoLinux     | 29        | 0.44%   |
| LMDE          | 28        | 0.43%   |
| Gentoo        | 28        | 0.43%   |
| MX            | 26        | 0.4%    |
| Kali          | 21        | 0.32%   |
| Peppermint    | 20        | 0.3%    |
| Garuda Linux  | 19        | 0.29%   |
| Ubuntu Budgie | 17        | 0.26%   |
| Parrot        | 11        | 0.17%   |
| LinuxFX       | 11        | 0.17%   |
| Ubuntu Studio | 10        | 0.15%   |
| Slackware     | 8         | 0.12%   |
| CentOS        | 8         | 0.12%   |
| SteamOS       | 7         | 0.11%   |
| Raspbian      | 7         | 0.11%   |
| Chrome OS     | 7         | 0.11%   |
| Q4OS          | 5         | 0.08%   |
| Xero          | 4         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 206       | 2.7%    |
| 5.16.7-desktop-1omv4003  | 172       | 2.25%   |
| 5.15.0-52-generic        | 165       | 2.16%   |
| 5.4.0-42-generic         | 125       | 1.64%   |
| 5.15.0-56-generic        | 100       | 1.31%   |
| 5.4.0-52-generic         | 81        | 1.06%   |
| 5.15.0-47-generic        | 70        | 0.92%   |
| 5.4.0-26-generic         | 66        | 0.86%   |
| 5.3.0-46-generic         | 66        | 0.86%   |
| 5.15.0-46-generic        | 65        | 0.85%   |
| 5.4.0-58-generic         | 60        | 0.79%   |
| 5.4.0-29-generic         | 59        | 0.77%   |
| 5.3.0-40-generic         | 58        | 0.76%   |
| 5.4.0-48-generic         | 56        | 0.73%   |
| 5.15.0-58-generic        | 55        | 0.72%   |
| 5.15.0-43-generic        | 51        | 0.67%   |
| 5.3.0-42-generic         | 48        | 0.63%   |
| 5.4.0-54-generic         | 46        | 0.6%    |
| 5.19.0-23-generic        | 41        | 0.54%   |
| 5.15.0-53-generic        | 41        | 0.54%   |
| 5.10.0-19-amd64          | 41        | 0.54%   |
| 6.0.2-arch1-1            | 40        | 0.52%   |
| 5.4.0-28-generic         | 40        | 0.52%   |
| 5.0.0-37-generic         | 39        | 0.51%   |
| 6.1.1-desktop-1omv2290   | 38        | 0.5%    |
| 5.4.0-56-generic         | 38        | 0.5%    |
| 5.4.0-37-generic         | 38        | 0.5%    |
| 5.4.0-33-generic         | 38        | 0.5%    |
| 5.4.0-47-generic         | 37        | 0.48%   |
| 5.15.0-48-generic        | 37        | 0.48%   |
| 5.11.0-38-generic        | 37        | 0.48%   |
| 5.4.0-40-generic         | 35        | 0.46%   |
| 5.15.0-41-generic        | 35        | 0.46%   |
| 5.13.0-28-generic        | 35        | 0.46%   |
| 5.15.0-50-generic        | 34        | 0.45%   |
| 5.13.0-39-generic        | 33        | 0.43%   |
| 4.18.16-desktop-1bP      | 32        | 0.42%   |
| 5.4.0-31-generic         | 31        | 0.41%   |
| 5.19.16-200.fc36.x86_64  | 31        | 0.41%   |
| 4.18.0-15-generic        | 31        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1241      | 17.41%  |
| 5.15.0  | 700       | 9.82%   |
| 4.15.0  | 464       | 6.51%   |
| 5.8.0   | 394       | 5.53%   |
| 5.3.0   | 384       | 5.39%   |
| 5.11.0  | 308       | 4.32%   |
| 5.13.0  | 295       | 4.14%   |
| 5.0.0   | 224       | 3.14%   |
| 5.10.14 | 207       | 2.9%    |
| 5.10.0  | 192       | 2.69%   |
| 5.16.7  | 175       | 2.45%   |
| 4.18.0  | 158       | 2.22%   |
| 5.19.0  | 152       | 2.13%   |
| 6.0.2   | 83        | 1.16%   |
| 4.19.0  | 77        | 1.08%   |
| 6.1.1   | 50        | 0.7%    |
| 5.19.16 | 47        | 0.66%   |
| 4.9.60  | 36        | 0.5%    |
| 4.9.20  | 36        | 0.5%    |
| 6.0.6   | 34        | 0.48%   |
| 4.18.16 | 34        | 0.48%   |
| 5.17.5  | 32        | 0.45%   |
| 6.0.0   | 30        | 0.42%   |
| 5.19.6  | 28        | 0.39%   |
| 4.4.0   | 26        | 0.36%   |
| 6.0.12  | 25        | 0.35%   |
| 6.0.10  | 22        | 0.31%   |
| 6.0.5   | 21        | 0.29%   |
| 6.0.7   | 20        | 0.28%   |
| 5.16.11 | 20        | 0.28%   |
| 6.0.9   | 19        | 0.27%   |
| 5.17.1  | 19        | 0.27%   |
| 5.12.4  | 18        | 0.25%   |
| 5.19.4  | 16        | 0.22%   |
| 5.18.0  | 16        | 0.22%   |
| 5.16.0  | 16        | 0.22%   |
| 6.0.8   | 15        | 0.21%   |
| 5.19.12 | 15        | 0.21%   |
| 5.17.0  | 15        | 0.21%   |
| 5.8.18  | 14        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1320      | 18.74%  |
| 5.15    | 858       | 12.18%  |
| 5.10    | 489       | 6.94%   |
| 4.15    | 466       | 6.61%   |
| 5.8     | 464       | 6.59%   |
| 5.3     | 414       | 5.88%   |
| 5.11    | 370       | 5.25%   |
| 5.19    | 335       | 4.76%   |
| 5.13    | 327       | 4.64%   |
| 6.0     | 300       | 4.26%   |
| 5.16    | 264       | 3.75%   |
| 5.0     | 232       | 3.29%   |
| 4.18    | 199       | 2.82%   |
| 4.9     | 122       | 1.73%   |
| 5.17    | 105       | 1.49%   |
| 4.19    | 102       | 1.45%   |
| 6.1     | 95        | 1.35%   |
| 5.18    | 95        | 1.35%   |
| 5.9     | 82        | 1.16%   |
| 5.14    | 75        | 1.06%   |
| 5.6     | 64        | 0.91%   |
| 5.12    | 62        | 0.88%   |
| 5.7     | 50        | 0.71%   |
| 5.5     | 47        | 0.67%   |
| 4.4     | 28        | 0.4%    |
| 4.1     | 16        | 0.23%   |
| 5.2     | 13        | 0.18%   |
| 4.13    | 12        | 0.17%   |
| 5.1     | 7         | 0.1%    |
| 4.20    | 5         | 0.07%   |
| 4.17    | 5         | 0.07%   |
| 4.12    | 5         | 0.07%   |
| 4.14    | 4         | 0.06%   |
| 3.10    | 3         | 0.04%   |
| 4.16    | 2         | 0.03%   |
| 4.10    | 2         | 0.03%   |
| 4.8     | 1         | 0.01%   |
| 4.7     | 1         | 0.01%   |
| 3.4     | 1         | 0.01%   |
| 3.16    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6009      | 94.42%  |
| i686    | 311       | 4.89%   |
| aarch64 | 34        | 0.53%   |
| armv7l  | 10        | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2825      | 42.58%  |
| KDE5             | 1196      | 18.03%  |
| Unknown          | 808       | 12.18%  |
| XFCE             | 556       | 8.38%   |
| X-Cinnamon       | 391       | 5.89%   |
| MATE             | 178       | 2.68%   |
| KDE              | 137       | 2.07%   |
| KDE4             | 108       | 1.63%   |
| LXQt             | 97        | 1.46%   |
| Pantheon         | 54        | 0.81%   |
| Cinnamon         | 49        | 0.74%   |
| LXDE             | 46        | 0.69%   |
| Unity            | 42        | 0.63%   |
| GNOME Flashback  | 27        | 0.41%   |
| Budgie           | 25        | 0.38%   |
| i3               | 20        | 0.3%    |
| GNOME Classic    | 10        | 0.15%   |
| Deepin           | 10        | 0.15%   |
| Openbox          | 9         | 0.14%   |
| sway             | 6         | 0.09%   |
| Hyprland         | 6         | 0.09%   |
| bspwm            | 6         | 0.09%   |
| lightdm-xsession | 5         | 0.08%   |
| Trinity          | 4         | 0.06%   |
| DWM              | 4         | 0.06%   |
| xubuntu          | 2         | 0.03%   |
| qtile            | 2         | 0.03%   |
| enlightenment    | 2         | 0.03%   |
| ubuntu           | 1         | 0.02%   |
| none+i3          | 1         | 0.02%   |
| none+bspwm       | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| herbstluftwm     | 1         | 0.02%   |
| gamescope        | 1         | 0.02%   |
| FVWM             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5074      | 77.36%  |
| Wayland | 981       | 14.96%  |
| Unknown | 420       | 6.4%    |
| Tty     | 84        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3165      | 47.82%  |
| SDDM    | 1126      | 17.01%  |
| GDM     | 722       | 10.91%  |
| GDM3    | 699       | 10.56%  |
| LightDM | 599       | 9.05%   |
| TDM     | 168       | 2.54%   |
| KDM     | 111       | 1.68%   |
| XDM     | 12        | 0.18%   |
| SLiM    | 5         | 0.08%   |
| LXDM    | 4         | 0.06%   |
| GREETD  | 3         | 0.05%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| it_IT        | 4026      | 61.7%   |
| en_US        | 1289      | 19.75%  |
| Unknown      | 855       | 13.1%   |
| en_GB        | 142       | 2.18%   |
| C            | 99        | 1.52%   |
| de_DE        | 21        | 0.32%   |
| fr_FR        | 13        | 0.2%    |
| es_ES        | 11        | 0.17%   |
| de_IT        | 10        | 0.15%   |
| ru_RU        | 8         | 0.12%   |
| it_CH        | 8         | 0.12%   |
| POSIX        | 7         | 0.11%   |
| en_IE        | 4         | 0.06%   |
| de_AT        | 4         | 0.06%   |
| en_AU        | 3         | 0.05%   |
| en_AG        | 3         | 0.05%   |
| it_IT@euro   | 2         | 0.03%   |
| en_US.UTF8   | 2         | 0.03%   |
| ro_RO        | 1         | 0.02%   |
| pt_BR        | 1         | 0.02%   |
| pl_PL        | 1         | 0.02%   |
| it_ITutf8    | 1         | 0.02%   |
| it_IT.UTF -8 | 1         | 0.02%   |
| hu_HU        | 1         | 0.02%   |
| fur_IT       | 1         | 0.02%   |
| fr_BE        | 1         | 0.02%   |
| es_US        | 1         | 0.02%   |
| es_MX        | 1         | 0.02%   |
| en_US@euro   | 1         | 0.02%   |
| en_US.utf-8  | 1         | 0.02%   |
| en_US.ASCII  | 1         | 0.02%   |
| en_IN        | 1         | 0.02%   |
| de_CH        | 1         | 0.02%   |
| Default      | 1         | 0.02%   |
| C.UTF8       | 1         | 0.02%   |
| bg_BG        | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3398      | 52.41%  |
| EFI  | 3085      | 47.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5020      | 77.42%  |
| Overlay  | 626       | 9.65%   |
| Btrfs    | 463       | 7.14%   |
| Unknown  | 230       | 3.55%   |
| Xfs      | 59        | 0.91%   |
| Zfs      | 29        | 0.45%   |
| Ext2     | 18        | 0.28%   |
| Ext3     | 14        | 0.22%   |
| Tmpfs    | 9         | 0.14%   |
| F2fs     | 9         | 0.14%   |
| XXX4     | 2         | 0.03%   |
| Aufs     | 2         | 0.03%   |
| XXXX     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3430      | 52.65%  |
| GPT     | 2324      | 35.67%  |
| MBR     | 761       | 11.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5462      | 84.32%  |
| Yes       | 1016      | 15.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4111      | 63.34%  |
| Yes       | 2379      | 36.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1358      | 21.36%  |
| Hewlett-Packard         | 1073      | 16.88%  |
| Lenovo                  | 713       | 11.22%  |
| Acer                    | 516       | 8.12%   |
| Dell                    | 515       | 8.1%    |
| MSI                     | 348       | 5.47%   |
| ASRock                  | 298       | 4.69%   |
| Gigabyte Technology     | 224       | 3.52%   |
| Apple                   | 133       | 2.09%   |
| Toshiba                 | 98        | 1.54%   |
| Intel                   | 95        | 1.49%   |
| Sony                    | 89        | 1.4%    |
| HUAWEI                  | 86        | 1.35%   |
| Fujitsu                 | 68        | 1.07%   |
| Samsung Electronics     | 67        | 1.05%   |
| Unknown                 | 64        | 1.01%   |
| Packard Bell            | 54        | 0.85%   |
| Pegatron                | 41        | 0.64%   |
| Raspberry Pi Foundation | 32        | 0.5%    |
| Fujitsu Siemens         | 30        | 0.47%   |
| Chuwi                   | 26        | 0.41%   |
| Teclast                 | 25        | 0.39%   |
| Mediacom                | 24        | 0.38%   |
| Foxconn                 | 22        | 0.35%   |
| Microsoft               | 21        | 0.33%   |
| Notebook                | 19        | 0.3%    |
| AMI                     | 19        | 0.3%    |
| Timi                    | 15        | 0.24%   |
| Microtech               | 15        | 0.24%   |
| BESSTAR Tech            | 15        | 0.24%   |
| TUXEDO                  | 12        | 0.19%   |
| Supermicro              | 11        | 0.17%   |
| PC Specialist           | 11        | 0.17%   |
| AZW                     | 10        | 0.16%   |
| eMachines               | 9         | 0.14%   |
| SANTECH                 | 8         | 0.13%   |
| Biostar                 | 8         | 0.13%   |
| Alienware               | 8         | 0.13%   |
| TrekStor                | 7         | 0.11%   |
| IBM                     | 7         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 79        | 1.24%   |
| ASUS All Series                        | 68        | 1.07%   |
| HP Pavilion dv6                        | 51        | 0.8%    |
| HP Notebook                            | 37        | 0.58%   |
| HP Pavilion 15                         | 23        | 0.36%   |
| HP Pavilion g6                         | 21        | 0.33%   |
| HP 255 G8 Notebook PC                  | 17        | 0.27%   |
| HUAWEI NBLK-WAX9X                      | 16        | 0.25%   |
| HP 15                                  | 15        | 0.24%   |
| ASUS PRIME A320M-K                     | 15        | 0.24%   |
| MSI MS-7C37                            | 13        | 0.2%    |
| MSI MS-7B86                            | 12        | 0.19%   |
| HP 255 G7 Notebook PC                  | 12        | 0.19%   |
| Dell XPS 15 7590                       | 12        | 0.19%   |
| Dell OptiPlex 7010                     | 12        | 0.19%   |
| Apple MacBook4,1                       | 12        | 0.19%   |
| HUAWEI KLVL-WXX9                       | 11        | 0.17%   |
| HP Pavilion x2 Detachable              | 11        | 0.17%   |
| HP G62                                 | 11        | 0.17%   |
| HP 255 G6 Notebook PC                  | 11        | 0.17%   |
| ASUS T101HA                            | 11        | 0.17%   |
| RPi Raspberry Pi                       | 10        | 0.16%   |
| MSI MS-7C56                            | 10        | 0.16%   |
| Mediacom SmartBook 14 FullHD - SB14UC  | 10        | 0.16%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 10        | 0.16%   |
| HP Compaq Elite 8300 SFF               | 10        | 0.16%   |
| HP 250 G6 Notebook PC                  | 10        | 0.16%   |
| HP Laptop 15s-eq2xxx                   | 9         | 0.14%   |
| Gigabyte B450M DS3H                    | 9         | 0.14%   |
| Dell XPS 15 9570                       | 9         | 0.14%   |
| Dell XPS 15 9560                       | 9         | 0.14%   |
| Lenovo V145-15AST 81MT                 | 8         | 0.13%   |
| HP ProBook 450 G5                      | 8         | 0.13%   |
| HP Pavilion dv7                        | 8         | 0.13%   |
| HP ENVY 15                             | 8         | 0.13%   |
| HP Compaq 6730s                        | 8         | 0.13%   |
| Dell Inspiron 5570                     | 8         | 0.13%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD | 8         | 0.13%   |
| ASUS TUF Gaming X570-PLUS              | 8         | 0.13%   |
| ASUS K53SC                             | 8         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 327       | 5.14%   |
| Lenovo ThinkPad       | 290       | 4.56%   |
| HP Pavilion           | 250       | 3.93%   |
| Dell Latitude         | 145       | 2.28%   |
| HP Compaq             | 142       | 2.23%   |
| Lenovo IdeaPad        | 135       | 2.12%   |
| ASUS PRIME            | 107       | 1.68%   |
| HP EliteBook          | 102       | 1.6%    |
| Dell XPS              | 91        | 1.43%   |
| ASUS VivoBook         | 91        | 1.43%   |
| Dell Inspiron         | 88        | 1.38%   |
| Toshiba Satellite     | 86        | 1.35%   |
| HP Laptop             | 79        | 1.24%   |
| Unknown               | 79        | 1.24%   |
| HP ProBook            | 75        | 1.18%   |
| Dell OptiPlex         | 70        | 1.1%    |
| ASUS All              | 68        | 1.07%   |
| ASUS ROG              | 63        | 0.99%   |
| HP 255                | 54        | 0.85%   |
| ASUS TUF              | 51        | 0.8%    |
| Dell Precision        | 50        | 0.79%   |
| Lenovo ThinkCentre    | 49        | 0.77%   |
| HP 250                | 44        | 0.69%   |
| HP Notebook           | 37        | 0.58%   |
| Fujitsu LIFEBOOK      | 36        | 0.57%   |
| Dell Vostro           | 36        | 0.57%   |
| RPi Raspberry         | 32        | 0.5%    |
| Acer TravelMate       | 32        | 0.5%    |
| Acer Swift            | 32        | 0.5%    |
| Acer Extensa          | 32        | 0.5%    |
| Lenovo ThinkBook      | 29        | 0.46%   |
| Acer Veriton          | 29        | 0.46%   |
| Lenovo Yoga           | 27        | 0.42%   |
| Fujitsu ESPRIMO       | 27        | 0.42%   |
| HP ENVY               | 26        | 0.41%   |
| Packard Bell EasyNote | 22        | 0.35%   |
| Microsoft Surface     | 21        | 0.33%   |
| ASUS P8H61-M          | 19        | 0.3%    |
| HP ProDesk            | 18        | 0.28%   |
| Packard Bell IMEDIA   | 17        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 557       | 8.76%   |
| 2019    | 519       | 8.16%   |
| 2020    | 514       | 8.09%   |
| 2013    | 443       | 6.97%   |
| 2012    | 415       | 6.53%   |
| 2017    | 405       | 6.37%   |
| 2008    | 391       | 6.15%   |
| 2011    | 388       | 6.1%    |
| 2009    | 373       | 5.87%   |
| 2014    | 367       | 5.77%   |
| 2021    | 364       | 5.73%   |
| 2010    | 359       | 5.65%   |
| 2016    | 344       | 5.41%   |
| 2015    | 337       | 5.3%    |
| 2007    | 237       | 3.73%   |
| 2006    | 132       | 2.08%   |
| 2022    | 88        | 1.38%   |
| 2005    | 63        | 0.99%   |
| Unknown | 39        | 0.61%   |
| 2004    | 14        | 0.22%   |
| 2003    | 5         | 0.08%   |
| 2001    | 2         | 0.03%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3576      | 56.25%  |
| Desktop        | 2346      | 36.9%   |
| Convertible    | 132       | 2.08%   |
| Mini pc        | 89        | 1.4%    |
| All in one     | 78        | 1.23%   |
| Tablet         | 76        | 1.2%    |
| System on chip | 42        | 0.66%   |
| Server         | 17        | 0.27%   |
| Phone          | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5938      | 92.78%  |
| Enabled  | 462       | 7.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6343      | 99.78%  |
| Yes  | 14        | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1512      | 23.47%  |
| 4.01-8.0        | 1503      | 23.33%  |
| 16.01-24.0      | 1131      | 17.56%  |
| 8.01-16.0       | 1119      | 17.37%  |
| 32.01-64.0      | 411       | 6.38%   |
| 1.01-2.0        | 405       | 6.29%   |
| 2.01-3.0        | 124       | 1.93%   |
| 64.01-256.0     | 79        | 1.23%   |
| 0.51-1.0        | 76        | 1.18%   |
| 24.01-32.0      | 70        | 1.09%   |
| 0.01-0.5        | 6         | 0.09%   |
| More than 256.0 | 5         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2803      | 39.98%  |
| 2.01-3.0   | 1667      | 23.78%  |
| 4.01-8.0   | 807       | 11.51%  |
| 3.01-4.0   | 785       | 11.2%   |
| 0.51-1.0   | 631       | 9%      |
| 8.01-16.0  | 198       | 2.82%   |
| 0.01-0.5   | 91        | 1.3%    |
| 16.01-24.0 | 18        | 0.26%   |
| 24.01-32.0 | 7         | 0.1%    |
| Unknown    | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3972      | 60.9%   |
| 2       | 1621      | 24.85%  |
| 3       | 478       | 7.33%   |
| 4       | 214       | 3.28%   |
| 5       | 94        | 1.44%   |
| 0       | 59        | 0.9%    |
| 6       | 43        | 0.66%   |
| 7       | 17        | 0.26%   |
| 8       | 11        | 0.17%   |
| 10      | 4         | 0.06%   |
| 12      | 3         | 0.05%   |
| 9       | 3         | 0.05%   |
| Unknown | 2         | 0.03%   |
| 13      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3297      | 51.48%  |
| Yes       | 3107      | 48.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5444      | 85.33%  |
| No        | 936       | 14.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4861      | 76.07%  |
| No        | 1529      | 23.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3527      | 54.7%   |
| No        | 2921      | 45.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 6357      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 873       | 12.24%  |
| Rome                | 753       | 10.56%  |
| Turin               | 235       | 3.3%    |
| Bologna             | 162       | 2.27%   |
| Naples              | 136       | 1.91%   |
| Florence            | 128       | 1.79%   |
| Genoa               | 104       | 1.46%   |
| Rho                 | 95        | 1.33%   |
| Padova              | 87        | 1.22%   |
| Palermo             | 80        | 1.12%   |
| Verona              | 72        | 1.01%   |
| Bari                | 54        | 0.76%   |
| Catania             | 53        | 0.74%   |
| Brescia             | 50        | 0.7%    |
| Trieste             | 49        | 0.69%   |
| Venice              | 40        | 0.56%   |
| Parma               | 40        | 0.56%   |
| Bergamo             | 38        | 0.53%   |
| Modena              | 36        | 0.5%    |
| Pisa                | 35        | 0.49%   |
| Reggio Emilia       | 34        | 0.48%   |
| Sesto San Giovanni  | 32        | 0.45%   |
| Pescara             | 32        | 0.45%   |
| Casalecchio di Reno | 32        | 0.45%   |
| Cagliari            | 32        | 0.45%   |
| Trento              | 30        | 0.42%   |
| Perugia             | 28        | 0.39%   |
| Monza               | 28        | 0.39%   |
| Bolzano             | 28        | 0.39%   |
| Taranto             | 25        | 0.35%   |
| Mestre              | 23        | 0.32%   |
| Udine               | 22        | 0.31%   |
| Seregno             | 22        | 0.31%   |
| Como                | 22        | 0.31%   |
| Vicenza             | 20        | 0.28%   |
| Reggio Calabria     | 20        | 0.28%   |
| Salerno             | 19        | 0.27%   |
| Forlì              | 19        | 0.27%   |
| Legnano             | 18        | 0.25%   |
| Cesena              | 17        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1493      | 2099   | 16.33%  |
| Seagate                   | 1326      | 1986   | 14.5%   |
| WDC                       | 1288      | 1920   | 14.08%  |
| Kingston                  | 586       | 760    | 6.41%   |
| Toshiba                   | 556       | 761    | 6.08%   |
| Crucial                   | 522       | 646    | 5.71%   |
| SanDisk                   | 454       | 614    | 4.96%   |
| Unknown                   | 434       | 588    | 4.75%   |
| Hitachi                   | 369       | 472    | 4.03%   |
| SK hynix                  | 198       | 240    | 2.17%   |
| HGST                      | 189       | 248    | 2.07%   |
| Maxtor                    | 173       | 235    | 1.89%   |
| Micron Technology         | 135       | 167    | 1.48%   |
| Intel                     | 135       | 172    | 1.48%   |
| Phison                    | 93        | 126    | 1.02%   |
| China                     | 69        | 77     | 0.75%   |
| KIOXIA                    | 64        | 83     | 0.7%    |
| SPCC                      | 55        | 67     | 0.6%    |
| Fujitsu                   | 53        | 62     | 0.58%   |
| Intenso                   | 43        | 54     | 0.47%   |
| Transcend                 | 42        | 53     | 0.46%   |
| Apple                     | 42        | 52     | 0.46%   |
| Corsair                   | 36        | 53     | 0.39%   |
| A-DATA Technology         | 35        | 46     | 0.38%   |
| Micron/Crucial Technology | 32        | 44     | 0.35%   |
| KingDian                  | 31        | 37     | 0.34%   |
| PNY                       | 30        | 37     | 0.33%   |
| JMicron Technology        | 30        | 33     | 0.33%   |
| LITEON                    | 28        | 34     | 0.31%   |
| Phison Electronics        | 24        | 27     | 0.26%   |
| OCZ                       | 24        | 26     | 0.26%   |
| Silicon Motion            | 23        | 31     | 0.25%   |
| Patriot                   | 22        | 29     | 0.24%   |
| Netac                     | 22        | 24     | 0.24%   |
| Drevo                     | 22        | 24     | 0.24%   |
| Teclast                   | 19        | 25     | 0.21%   |
| SABRENT                   | 17        | 17     | 0.19%   |
| LITEONIT                  | 16        | 26     | 0.17%   |
| Dogfish                   | 16        | 20     | 0.17%   |
| Unknown                   | 16        | 21     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 154       | 1.54%   |
| Samsung SSD 860 EVO 500GB                           | 133       | 1.33%   |
| Crucial CT500MX500SSD1 500GB                        | 118       | 1.18%   |
| Samsung SSD 850 EVO 250GB                           | 116       | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                     | 96        | 0.96%   |
| Kingston SA400S37480G 480GB SSD                     | 84        | 0.84%   |
| Samsung SSD 850 EVO 500GB                           | 83        | 0.83%   |
| Unknown MMC Card  32GB                              | 82        | 0.82%   |
| Toshiba MQ01ABF050 500GB                            | 68        | 0.68%   |
| Samsung SSD 860 EVO 250GB                           | 67        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 65        | 0.65%   |
| Unknown MMC Card  64GB                              | 64        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                      | 64        | 0.64%   |
| Toshiba DT01ACA100 1TB                              | 57        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 53        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 52        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 50        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 49        | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 49        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                         | 49        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB                      | 48        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD                    | 48        | 0.48%   |
| Crucial CT480BX500SSD1 480GB                        | 48        | 0.48%   |
| Seagate ST3500418AS 500GB                           | 47        | 0.47%   |
| HGST HTS545050A7E680 500GB                          | 47        | 0.47%   |
| HGST HTS721010A9E630 1TB                            | 46        | 0.46%   |
| Samsung NVMe SSD Drive 512GB                        | 43        | 0.43%   |
| Seagate M3 Portable 4TB                             | 42        | 0.42%   |
| SanDisk SSD PLUS 240GB                              | 42        | 0.42%   |
| Samsung SSD 840 EVO 250GB                           | 41        | 0.41%   |
| Seagate ST31000528AS 1TB                            | 38        | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB                      | 38        | 0.38%   |
| Samsung SSD 860 EVO 1TB                             | 38        | 0.38%   |
| Toshiba MQ01ABD100 1TB                              | 37        | 0.37%   |
| Seagate ST9500325AS 500GB                           | 37        | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 36        | 0.36%   |
| Unknown SD/MMC/MS PRO 2GB                           | 35        | 0.35%   |
| Seagate Expansion 240GB                             | 35        | 0.35%   |
| SanDisk NVMe SSD Drive 512GB                        | 34        | 0.34%   |
| Samsung NVMe SSD Drive 500GB                        | 34        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1286      | 1917   | 33.7%   |
| WDC                 | 1081      | 1615   | 28.33%  |
| Toshiba             | 412       | 559    | 10.8%   |
| Hitachi             | 369       | 472    | 9.67%   |
| HGST                | 188       | 247    | 4.93%   |
| Maxtor              | 171       | 233    | 4.48%   |
| Samsung Electronics | 136       | 172    | 3.56%   |
| Fujitsu             | 53        | 62     | 1.39%   |
| Unknown             | 48        | 58     | 1.26%   |
| SABRENT             | 17        | 17     | 0.45%   |
| Apple               | 11        | 13     | 0.29%   |
| ASMT                | 9         | 12     | 0.24%   |
| USB3.0              | 5         | 6      | 0.13%   |
| HGST HTS            | 5         | 5      | 0.13%   |
| IBM/Hitachi         | 4         | 5      | 0.1%    |
| WD MediaMax         | 2         | 2      | 0.05%   |
| Intenso             | 2         | 4      | 0.05%   |
| Hewlett-Packard     | 2         | 3      | 0.05%   |
| ASMT109x            | 2         | 2      | 0.05%   |
| USB 3.0             | 1         | 2      | 0.03%   |
| USB                 | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| Promise             | 1         | 1      | 0.03%   |
| PI-041              | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 2      | 0.03%   |
| IBM-ESXS            | 1         | 2      | 0.03%   |
| IBM-207x            | 1         | 4      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| FC-1307             | 1         | 2      | 0.03%   |
| DAS                 | 1         | 4      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 844       | 1151   | 27.08%  |
| Kingston            | 505       | 654    | 16.2%   |
| Crucial             | 470       | 585    | 15.08%  |
| SanDisk             | 281       | 382    | 9.02%   |
| WDC                 | 110       | 148    | 3.53%   |
| China               | 68        | 76     | 2.18%   |
| Micron Technology   | 64        | 80     | 2.05%   |
| Toshiba             | 51        | 72     | 1.64%   |
| SPCC                | 45        | 55     | 1.44%   |
| SK hynix            | 45        | 53     | 1.44%   |
| Transcend           | 40        | 51     | 1.28%   |
| Intenso             | 36        | 44     | 1.15%   |
| Intel               | 33        | 43     | 1.06%   |
| KingDian            | 30        | 36     | 0.96%   |
| Corsair             | 30        | 45     | 0.96%   |
| PNY                 | 28        | 34     | 0.9%    |
| A-DATA Technology   | 28        | 38     | 0.9%    |
| LITEON              | 24        | 27     | 0.77%   |
| Apple               | 24        | 25     | 0.77%   |
| OCZ                 | 23        | 25     | 0.74%   |
| Patriot             | 22        | 29     | 0.71%   |
| Teclast             | 19        | 25     | 0.61%   |
| Netac               | 19        | 20     | 0.61%   |
| Drevo               | 17        | 18     | 0.55%   |
| LITEONIT            | 16        | 26     | 0.51%   |
| Dogfish             | 16        | 20     | 0.51%   |
| GOODRAM             | 15        | 21     | 0.48%   |
| TCSUNBOW            | 13        | 14     | 0.42%   |
| JMicron Technology  | 13        | 14     | 0.42%   |
| Team                | 11        | 16     | 0.35%   |
| Unknown             | 10        | 11     | 0.32%   |
| FORESEE             | 10        | 12     | 0.32%   |
| Verbatim            | 9         | 14     | 0.29%   |
| KingSpec            | 8         | 10     | 0.26%   |
| BAITITON            | 8         | 9      | 0.26%   |
| Unknown             | 8         | 13     | 0.26%   |
| Microtech           | 7         | 16     | 0.22%   |
| TO Exter            | 6         | 6      | 0.19%   |
| Lexar               | 5         | 6      | 0.16%   |
| ASMT                | 5         | 5      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3223      | 5427   | 39.34%  |
| SSD     | 2784      | 4052   | 33.98%  |
| NVMe    | 1638      | 2290   | 20%     |
| MMC     | 391       | 548    | 4.77%   |
| Unknown | 156       | 193    | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4920      | 9249   | 67.55%  |
| NVMe | 1630      | 2272   | 22.38%  |
| MMC  | 391       | 548    | 5.37%   |
| SAS  | 342       | 441    | 4.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4056      | 6353   | 66.55%  |
| 0.51-1.0   | 1459      | 2130   | 23.94%  |
| 1.01-2.0   | 325       | 544    | 5.33%   |
| 3.01-4.0   | 106       | 179    | 1.74%   |
| 2.01-3.0   | 92        | 154    | 1.51%   |
| 4.01-10.0  | 51        | 108    | 0.84%   |
| 10.01-20.0 | 6         | 11     | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1860      | 27.65%  |
| 251-500        | 1481      | 22.01%  |
| 501-1000       | 793       | 11.79%  |
| 1-20           | 642       | 9.54%   |
| 51-100         | 552       | 8.2%    |
| 1001-2000      | 462       | 6.87%   |
| 21-50          | 322       | 4.79%   |
| More than 3000 | 246       | 3.66%   |
| 2001-3000      | 188       | 2.79%   |
| Unknown        | 182       | 2.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2900      | 41.58%  |
| 21-50          | 1059      | 15.18%  |
| 101-250        | 835       | 11.97%  |
| 51-100         | 770       | 11.04%  |
| 251-500        | 516       | 7.4%    |
| 501-1000       | 364       | 5.22%   |
| Unknown        | 182       | 2.61%   |
| 1001-2000      | 179       | 2.57%   |
| More than 3000 | 96        | 1.38%   |
| 2001-3000      | 73        | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 15        | 17     | 2.73%   |
| HGST HTS545050A7E680 500GB            | 13        | 14     | 2.36%   |
| Seagate ST3500418AS 500GB             | 10        | 14     | 1.82%   |
| Seagate ST9500325AS 500GB             | 8         | 8      | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB        | 7         | 7      | 1.27%   |
| Hitachi HTS725050A9A364 500GB         | 7         | 7      | 1.27%   |
| Toshiba MQ01ABF050 500GB              | 6         | 6      | 1.09%   |
| Maxtor STM3250310AS 250GB             | 6         | 6      | 1.09%   |
| WDC WD3200BEVT-60A23T0 320GB          | 5         | 5      | 0.91%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 5         | 5      | 0.91%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 4         | 4      | 0.73%   |
| WDC WD40EFRX-68N32N0 4TB              | 4         | 5      | 0.73%   |
| Unknown MM0500EANCR 500GB             | 4         | 9      | 0.73%   |
| Seagate ST31500341AS 1TB              | 4         | 4      | 0.73%   |
| Seagate ST31000528AS 1TB              | 4         | 7      | 0.73%   |
| Maxtor STM3320820AS 320GB             | 4         | 4      | 0.73%   |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 0.73%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 0.73%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3         | 4      | 0.55%   |
| WDC WD10EZEX-60WN4A0 1TB              | 3         | 4      | 0.55%   |
| Toshiba MQ01ABD100 1TB                | 3         | 3      | 0.55%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 3         | 3      | 0.55%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.55%   |
| Seagate ST3500413AS 500GB             | 3         | 5      | 0.55%   |
| Seagate ST3500320AS 500GB             | 3         | 3      | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 7      | 0.55%   |
| SanDisk SSD PLUS 480GB                | 3         | 3      | 0.55%   |
| Samsung Electronics SSD 970 EVO 1TB   | 3         | 3      | 0.55%   |
| Samsung Electronics SSD 860 EVO 500GB | 3         | 4      | 0.55%   |
| Samsung Electronics HD103UJ 1TB       | 3         | 3      | 0.55%   |
| Maxtor 6Y080L0 81GB                   | 3         | 3      | 0.55%   |
| Kingston SA400S37480G 480GB SSD       | 3         | 3      | 0.55%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.55%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.55%   |
| Hitachi HTS543225L9A300 250GB         | 3         | 3      | 0.55%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 0.55%   |
| HGST HTS541075A9E680 752GB            | 3         | 3      | 0.55%   |
| HGST HTS541010A9E680 1TB              | 3         | 4      | 0.55%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 144       | 186    | 26.87%  |
| WDC                 | 109       | 131    | 20.34%  |
| Hitachi             | 63        | 67     | 11.75%  |
| Toshiba             | 36        | 36     | 6.72%   |
| Samsung Electronics | 33        | 37     | 6.16%   |
| Maxtor              | 32        | 36     | 5.97%   |
| HGST                | 28        | 30     | 5.22%   |
| Kingston            | 15        | 15     | 2.8%    |
| Crucial             | 13        | 13     | 2.43%   |
| SK hynix            | 8         | 9      | 1.49%   |
| Micron Technology   | 8         | 8      | 1.49%   |
| SanDisk             | 7         | 7      | 1.31%   |
| Unknown             | 5         | 10     | 0.93%   |
| Intel               | 5         | 7      | 0.93%   |
| Fujitsu             | 5         | 5      | 0.93%   |
| OCZ                 | 3         | 3      | 0.56%   |
| Drevo               | 3         | 3      | 0.56%   |
| TCSUNBOW            | 2         | 2      | 0.37%   |
| Intenso             | 2         | 3      | 0.37%   |
| BAITITON            | 2         | 3      | 0.37%   |
| ASMT                | 2         | 2      | 0.37%   |
| WDC WDS2            | 1         | 1      | 0.19%   |
| WD MediaMax         | 1         | 1      | 0.19%   |
| USB3.0              | 1         | 1      | 0.19%   |
| Transcend           | 1         | 2      | 0.19%   |
| NGFF                | 1         | 1      | 0.19%   |
| LITEONIT            | 1         | 1      | 0.19%   |
| LITEON              | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 1      | 0.19%   |
| KingDian            | 1         | 1      | 0.19%   |
| CT1000P1            | 1         | 2      | 0.19%   |
| Corsair             | 1         | 2      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 144       | 186    | 32.51%  |
| WDC                 | 107       | 127    | 24.15%  |
| Hitachi             | 63        | 67     | 14.22%  |
| Toshiba             | 35        | 35     | 7.9%    |
| Maxtor              | 32        | 36     | 7.22%   |
| HGST                | 28        | 30     | 6.32%   |
| Samsung Electronics | 20        | 22     | 4.51%   |
| Unknown             | 5         | 10     | 1.13%   |
| Fujitsu             | 5         | 5      | 1.13%   |
| ASMT                | 2         | 2      | 0.45%   |
| WD MediaMax         | 1         | 1      | 0.23%   |
| USB3.0              | 1         | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 415       | 522    | 81.53%  |
| SSD  | 83        | 90     | 16.31%  |
| NVMe | 11        | 15     | 2.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB            | 2         | 4      | 14.29%  |
| Seagate ST500DM002-1BD142 500GB      | 2         | 3      | 14.29%  |
| WDC WD5000BEVT-26A0RT0 500GB         | 1         | 1      | 7.14%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 1      | 7.14%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 7.14%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 1      | 7.14%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 7.14%   |
| Seagate STM3250318AS 250GB           | 1         | 1      | 7.14%   |
| Seagate ST2000LX001-1RG174 2TB       | 1         | 1      | 7.14%   |
| Hitachi HTS725050A7E630 500GB        | 1         | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 7.14%   |
| Hitachi HTS543216L9A300 160GB        | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 9      | 42.86%  |
| WDC     | 4         | 4      | 28.57%  |
| Hitachi | 3         | 3      | 21.43%  |
| Toshiba | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3893      | 7526   | 56.56%  |
| Works    | 2477      | 4340   | 35.99%  |
| Malfunc  | 499       | 627    | 7.25%   |
| Failed   | 14        | 17     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4301      | 55.76%  |
| AMD                              | 1060      | 13.74%  |
| Samsung Electronics              | 617       | 8%      |
| SanDisk                          | 254       | 3.29%   |
| Nvidia                           | 175       | 2.27%   |
| SK hynix                         | 143       | 1.85%   |
| Phison Electronics               | 125       | 1.62%   |
| JMicron Technology               | 122       | 1.58%   |
| Marvell Technology Group         | 119       | 1.54%   |
| ASMedia Technology               | 116       | 1.5%    |
| Toshiba America Info Systems     | 99        | 1.28%   |
| Kingston Technology Company      | 95        | 1.23%   |
| Micron/Crucial Technology        | 81        | 1.05%   |
| Micron Technology                | 76        | 0.99%   |
| KIOXIA                           | 70        | 0.91%   |
| VIA Technologies                 | 54        | 0.7%    |
| Silicon Integrated Systems [SiS] | 32        | 0.41%   |
| Silicon Motion                   | 31        | 0.4%    |
| ADATA Technology                 | 15        | 0.19%   |
| Adaptec                          | 15        | 0.19%   |
| Union Memory (Shenzhen)          | 14        | 0.18%   |
| Silicon Image                    | 12        | 0.16%   |
| Solid State Storage Technology   | 9         | 0.12%   |
| Broadcom / LSI                   | 9         | 0.12%   |
| Apple                            | 9         | 0.12%   |
| LSI Logic / Symbios Logic        | 7         | 0.09%   |
| Lenovo                           | 7         | 0.09%   |
| Lite-On Technology               | 6         | 0.08%   |
| Seagate Technology               | 5         | 0.06%   |
| Realtek Semiconductor            | 5         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.05%   |
| Shenzhen Longsys Electronics     | 3         | 0.04%   |
| Promise Technology               | 3         | 0.04%   |
| Hewlett-Packard                  | 3         | 0.04%   |
| Broadcom                         | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| INNOGRIT                         | 2         | 0.03%   |
| HighPoint Technologies           | 2         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 697       | 7.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 338       | 3.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 320       | 3.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 259       | 2.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 247       | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 226       | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 201       | 2.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 174       | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 164       | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 150       | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 148       | 1.63%   |
| Samsung NVMe SSD Controller 980                                                | 146       | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                         | 139       | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 132       | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 126       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 125       | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 123       | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 122       | 1.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 121       | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 111       | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 108       | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 104       | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 104       | 1.15%   |
| Intel SATA Controller [RAID mode]                                              | 103       | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 102       | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 94        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 94        | 1.04%   |
| Phison E12 NVMe Controller                                                     | 83        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 83        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 83        | 0.91%   |
| Micron Non-Volatile memory controller                                          | 76        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 76        | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 74        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 73        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 71        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 67        | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                             | 65        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 61        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 61        | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 60        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4389      | 56.05%  |
| NVMe | 1644      | 21%     |
| IDE  | 1239      | 15.82%  |
| RAID | 539       | 6.88%   |
| SAS  | 10        | 0.13%   |
| SCSI | 9         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4933      | 77.6%   |
| AMD          | 1376      | 21.65%  |
| ARM          | 44        | 0.69%   |
| CentaurHauls | 3         | 0.05%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 84        | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 70        | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 69        | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 67        | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 65        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 52        | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 47        | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 47        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 46        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 45        | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 43        | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 42        | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 37        | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 37        | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 36        | 0.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 35        | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.53%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 34        | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 33        | 0.52%   |
| ARM Processor                                 | 32        | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 31        | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 31        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 28        | 0.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 28        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 27        | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 27        | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 27        | 0.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 27        | 0.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 25        | 0.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 25        | 0.39%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 24        | 0.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1261      | 19.81%  |
| Intel Core i5           | 1220      | 19.16%  |
| Intel Core i3           | 445       | 6.99%   |
| Intel Core 2 Duo        | 377       | 5.92%   |
| Intel Celeron           | 337       | 5.29%   |
| Other                   | 313       | 4.92%   |
| AMD Ryzen 5             | 300       | 4.71%   |
| Intel Atom              | 233       | 3.66%   |
| AMD Ryzen 7             | 225       | 3.53%   |
| Intel Pentium           | 120       | 1.88%   |
| Intel Pentium Dual-Core | 113       | 1.77%   |
| Intel Core 2 Quad       | 102       | 1.6%    |
| Intel Xeon              | 94        | 1.48%   |
| Intel Core 2            | 69        | 1.08%   |
| AMD FX                  | 68        | 1.07%   |
| AMD Ryzen 3             | 66        | 1.04%   |
| Intel Pentium Dual      | 65        | 1.02%   |
| Intel Pentium 4         | 62        | 0.97%   |
| AMD Ryzen 9             | 58        | 0.91%   |
| AMD A8                  | 56        | 0.88%   |
| AMD Athlon 64 X2        | 49        | 0.77%   |
| AMD E1                  | 47        | 0.74%   |
| AMD A4                  | 45        | 0.71%   |
| AMD A10                 | 43        | 0.68%   |
| Intel Core i9           | 41        | 0.64%   |
| AMD A6                  | 41        | 0.64%   |
| Intel Genuine           | 38        | 0.6%    |
| AMD Sempron             | 31        | 0.49%   |
| AMD Phenom II X4        | 28        | 0.44%   |
| Intel Pentium D         | 24        | 0.38%   |
| AMD E2                  | 24        | 0.38%   |
| AMD Phenom II X6        | 19        | 0.3%    |
| Intel Pentium Silver    | 18        | 0.28%   |
| AMD Athlon II X2        | 18        | 0.28%   |
| Intel Pentium M         | 16        | 0.25%   |
| AMD Ryzen 5 PRO         | 16        | 0.25%   |
| AMD Turion 64 X2 Mobile | 15        | 0.24%   |
| AMD Ryzen 7 PRO         | 15        | 0.24%   |
| AMD Athlon II X4        | 15        | 0.24%   |
| AMD Athlon              | 15        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2655      | 41.7%   |
| 4       | 2395      | 37.62%  |
| 6       | 503       | 7.9%    |
| 8       | 351       | 5.51%   |
| 1       | 291       | 4.57%   |
| 12      | 55        | 0.86%   |
| 3       | 31        | 0.49%   |
| 14      | 26        | 0.41%   |
| 10      | 22        | 0.35%   |
| 16      | 20        | 0.31%   |
| Unknown | 6         | 0.09%   |
| 24      | 5         | 0.08%   |
| 20      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 64      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6302      | 99.13%  |
| 2       | 48        | 0.76%   |
| Unknown | 4         | 0.06%   |
| 4       | 2         | 0.03%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3757      | 59.02%  |
| 1       | 2601      | 40.86%  |
| Unknown | 6         | 0.09%   |
| 4       | 2         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6163      | 96.77%  |
| 32-bit         | 119       | 1.87%   |
| Unknown        | 85        | 1.33%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1299      | 19.77%  |
| 0x206a7    | 351       | 5.34%   |
| 0x306a9    | 331       | 5.04%   |
| 0x1067a    | 280       | 4.26%   |
| 0x306c3    | 268       | 4.08%   |
| 0x806ea    | 163       | 2.48%   |
| 0x906ea    | 142       | 2.16%   |
| 0x40651    | 136       | 2.07%   |
| 0x806ec    | 134       | 2.04%   |
| 0x806c1    | 133       | 2.02%   |
| 0x806e9    | 132       | 2.01%   |
| 0x6fd      | 125       | 1.9%    |
| 0x506e3    | 125       | 1.9%    |
| 0x406e3    | 122       | 1.86%   |
| 0x906e9    | 111       | 1.69%   |
| 0x20655    | 109       | 1.66%   |
| 0x10676    | 100       | 1.52%   |
| 0x08108109 | 89        | 1.35%   |
| 0x306d4    | 86        | 1.31%   |
| 0x08701021 | 84        | 1.28%   |
| 0x406c4    | 79        | 1.2%    |
| 0x6fb      | 77        | 1.17%   |
| 0x30678    | 68        | 1.04%   |
| 0x406c3    | 63        | 0.96%   |
| 0x706e5    | 61        | 0.93%   |
| 0x706a1    | 59        | 0.9%    |
| 0x20652    | 59        | 0.9%    |
| 0x0a50000c | 52        | 0.79%   |
| 0x806eb    | 51        | 0.78%   |
| 0x6f6      | 49        | 0.75%   |
| 0x010000c8 | 48        | 0.73%   |
| 0x706a8    | 47        | 0.72%   |
| 0x106e5    | 46        | 0.7%    |
| 0x06006705 | 45        | 0.68%   |
| 0x08608103 | 44        | 0.67%   |
| 0x506c9    | 43        | 0.65%   |
| 0x106ca    | 43        | 0.65%   |
| 0xa0652    | 41        | 0.62%   |
| 0x0800820d | 39        | 0.59%   |
| 0x906ed    | 37        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 952       | 14.95%  |
| Haswell          | 514       | 8.07%   |
| Penryn           | 465       | 7.3%    |
| SandyBridge      | 425       | 6.67%   |
| IvyBridge        | 405       | 6.36%   |
| Core             | 329       | 5.17%   |
| Skylake          | 315       | 4.95%   |
| Silvermont       | 254       | 3.99%   |
| Zen 2            | 215       | 3.38%   |
| Westmere         | 209       | 3.28%   |
| Zen+             | 184       | 2.89%   |
| TigerLake        | 164       | 2.57%   |
| K10              | 157       | 2.47%   |
| Unknown          | 156       | 2.45%   |
| Zen 3            | 125       | 1.96%   |
| Goldmont plus    | 124       | 1.95%   |
| CometLake        | 122       | 1.92%   |
| K8 Hammer        | 111       | 1.74%   |
| Broadwell        | 103       | 1.62%   |
| Excavator        | 101       | 1.59%   |
| Zen              | 99        | 1.55%   |
| IceLake          | 97        | 1.52%   |
| Bonnell          | 94        | 1.48%   |
| Piledriver       | 93        | 1.46%   |
| NetBurst         | 93        | 1.46%   |
| Nehalem          | 88        | 1.38%   |
| Goldmont         | 59        | 0.93%   |
| P6               | 58        | 0.91%   |
| Jaguar           | 48        | 0.75%   |
| Puma             | 46        | 0.72%   |
| Alderlake Hybrid | 38        | 0.6%    |
| K10 Llano        | 34        | 0.53%   |
| Bobcat           | 32        | 0.5%    |
| Steamroller      | 29        | 0.46%   |
| K8 & K10 hybrid  | 16        | 0.25%   |
| Bulldozer        | 10        | 0.16%   |
| Tremont          | 4         | 0.06%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3547      | 47.69%  |
| Nvidia                                       | 2132      | 28.66%  |
| AMD                                          | 1699      | 22.84%  |
| Silicon Integrated Systems [SiS]             | 19        | 0.26%   |
| Matrox Electronics Systems                   | 16        | 0.22%   |
| VIA Technologies                             | 15        | 0.2%    |
| ASPEED Technology                            | 6         | 0.08%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.04%   |
| S3 Graphics                                  | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 291       | 3.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 236       | 3.05%   |
| Intel UHD Graphics 620                                                                   | 180       | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 168       | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 163       | 2.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 152       | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 136       | 1.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 133       | 1.72%   |
| Intel HD Graphics 620                                                                    | 131       | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 131       | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 117       | 1.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 110       | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 106       | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 106       | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 101       | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 97        | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 91        | 1.18%   |
| AMD Renoir                                                                               | 90        | 1.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 89        | 1.15%   |
| Intel HD Graphics 5500                                                                   | 84        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 84        | 1.09%   |
| Intel HD Graphics 630                                                                    | 72        | 0.93%   |
| Intel HD Graphics 530                                                                    | 72        | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 71        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 71        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 66        | 0.85%   |
| AMD Lucienne                                                                             | 66        | 0.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 65        | 0.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 65        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 65        | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 65        | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 58        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 57        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 56        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 55        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 53        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 51        | 0.66%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 50        | 0.65%   |
| Intel HD Graphics 500                                                                    | 49        | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 49        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2500      | 39.19%  |
| 1 x AMD                 | 1331      | 20.87%  |
| 1 x Nvidia              | 1238      | 19.41%  |
| Intel + Nvidia          | 821       | 12.87%  |
| Intel + AMD             | 172       | 2.7%    |
| 2 x AMD                 | 131       | 2.05%   |
| AMD + Nvidia            | 59        | 0.92%   |
| Other                   | 51        | 0.8%    |
| 1 x SiS                 | 19        | 0.3%    |
| 1 x VIA                 | 15        | 0.24%   |
| 1 x Matrox              | 9         | 0.14%   |
| 2 x Nvidia              | 8         | 0.13%   |
| 2 x Intel               | 4         | 0.06%   |
| Nvidia + Matrox         | 4         | 0.06%   |
| 1 x XGI                 | 3         | 0.05%   |
| 1 x ASPEED              | 3         | 0.05%   |
| Nvidia + ASPEED         | 2         | 0.03%   |
| AMD + Matrox            | 2         | 0.03%   |
| 3 x AMD                 | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.02%   |
| 1 x S3 Graphics         | 1         | 0.02%   |
| Intel + 2 x AMD         | 1         | 0.02%   |
| AMD + 2 x Nvidia        | 1         | 0.02%   |
| AMD + ASPEED            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5196      | 80.55%  |
| Proprietary | 1026      | 15.9%   |
| Unknown     | 229       | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3416      | 52.25%  |
| 0.01-0.5   | 929       | 14.21%  |
| 1.01-2.0   | 883       | 13.51%  |
| 0.51-1.0   | 597       | 9.13%   |
| 3.01-4.0   | 356       | 5.45%   |
| 7.01-8.0   | 157       | 2.4%    |
| 5.01-6.0   | 125       | 1.91%   |
| 2.01-3.0   | 43        | 0.66%   |
| 8.01-16.0  | 30        | 0.46%   |
| 4.01-5.0   | 1         | 0.02%   |
| 16.01-24.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 993       | 14.81%  |
| AU Optronics            | 809       | 12.07%  |
| Chimei Innolux          | 586       | 8.74%   |
| LG Display              | 542       | 8.09%   |
| BOE                     | 530       | 7.91%   |
| Hewlett-Packard         | 326       | 4.86%   |
| Goldstar                | 322       | 4.8%    |
| Philips                 | 304       | 4.54%   |
| Ancor Communications    | 266       | 3.97%   |
| Acer                    | 224       | 3.34%   |
| Dell                    | 163       | 2.43%   |
| BenQ                    | 153       | 2.28%   |
| Chi Mei Optoelectronics | 130       | 1.94%   |
| Sharp                   | 120       | 1.79%   |
| Apple                   | 113       | 1.69%   |
| AOC                     | 113       | 1.69%   |
| Lenovo                  | 93        | 1.39%   |
| HannStar                | 70        | 1.04%   |
| Sony                    | 60        | 0.9%    |
| LG Philips              | 60        | 0.9%    |
| PANDA                   | 57        | 0.85%   |
| ASUSTek Computer        | 39        | 0.58%   |
| InfoVision              | 38        | 0.57%   |
| Unknown                 | 37        | 0.55%   |
| LG Electronics          | 37        | 0.55%   |
| Eizo                    | 21        | 0.31%   |
| CPT                     | 21        | 0.31%   |
| MSI                     | 19        | 0.28%   |
| CSO                     | 18        | 0.27%   |
| Fujitsu Siemens         | 17        | 0.25%   |
| Toshiba                 | 16        | 0.24%   |
| Vestel Elektronik       | 13        | 0.19%   |
| Quanta Display          | 13        | 0.19%   |
| Packard Bell            | 13        | 0.19%   |
| LGD                     | 13        | 0.19%   |
| Panasonic               | 12        | 0.18%   |
| Mi                      | 12        | 0.18%   |
| Iiyama                  | 11        | 0.16%   |
| NEC Computers           | 10        | 0.15%   |
| CVT                     | 10        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 61        | 0.89%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 35        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 35        | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 35        | 0.51%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 33        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 31        | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 29        | 0.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 29        | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 28        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 27        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 27        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 24        | 0.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 24        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 23        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 23        | 0.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.32%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 22        | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 21        | 0.3%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 20        | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 19        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 19        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 18        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 18        | 0.26%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 17        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 17        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 16        | 0.23%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 16        | 0.23%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 16        | 0.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 15        | 0.22%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 15        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 15        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 15        | 0.22%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 14        | 0.2%    |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch            | 14        | 0.2%    |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 13        | 0.19%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 13        | 0.19%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 13        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2775      | 42.99%  |
| 1366x768 (WXGA)    | 1345      | 20.84%  |
| 3840x2160 (4K)     | 324       | 5.02%   |
| 1280x1024 (SXGA)   | 296       | 4.59%   |
| 1280x800 (WXGA)    | 277       | 4.29%   |
| 1440x900 (WXGA+)   | 216       | 3.35%   |
| 1680x1050 (WSXGA+) | 196       | 3.04%   |
| 2560x1440 (QHD)    | 185       | 2.87%   |
| 1600x900 (HD+)     | 171       | 2.65%   |
| 1920x1200 (WUXGA)  | 98        | 1.52%   |
| 1360x768           | 63        | 0.98%   |
| 1024x600           | 56        | 0.87%   |
| Unknown            | 55        | 0.85%   |
| 2560x1080          | 45        | 0.7%    |
| 1024x768 (XGA)     | 35        | 0.54%   |
| 2560x1600          | 34        | 0.53%   |
| 2160x1440          | 30        | 0.46%   |
| 3440x1440          | 29        | 0.45%   |
| 3840x1080          | 26        | 0.4%    |
| 2880x1800          | 20        | 0.31%   |
| 1600x1200          | 15        | 0.23%   |
| 3840x2400          | 14        | 0.22%   |
| 1920x540           | 13        | 0.2%    |
| 1280x720 (HD)      | 10        | 0.15%   |
| 3200x1800 (QHD+)   | 8         | 0.12%   |
| 3000x2000          | 8         | 0.12%   |
| 2736x1824          | 8         | 0.12%   |
| 1920x1280          | 8         | 0.12%   |
| 800x1280           | 5         | 0.08%   |
| 3072x1920          | 5         | 0.08%   |
| 2880x1920          | 4         | 0.06%   |
| 2288x1287          | 4         | 0.06%   |
| 2256x1504          | 4         | 0.06%   |
| 1800x1200          | 4         | 0.06%   |
| 1400x1050          | 4         | 0.06%   |
| 1280x768           | 4         | 0.06%   |
| 4480x1440          | 3         | 0.05%   |
| 3840x1600          | 3         | 0.05%   |
| 3200x1080          | 3         | 0.05%   |
| 2520x1680          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2083      | 31.04%  |
| 13      | 553       | 8.24%   |
| 24      | 458       | 6.83%   |
| 27      | 443       | 6.6%    |
| 21      | 419       | 6.24%   |
| 14      | 365       | 5.44%   |
| 23      | 361       | 5.38%   |
| Unknown | 359       | 5.35%   |
| 17      | 317       | 4.72%   |
| 19      | 260       | 3.87%   |
| 18      | 143       | 2.13%   |
| 12      | 118       | 1.76%   |
| 20      | 106       | 1.58%   |
| 22      | 102       | 1.52%   |
| 10      | 75        | 1.12%   |
| 31      | 72        | 1.07%   |
| 34      | 67        | 1%      |
| 11      | 64        | 0.95%   |
| 40      | 44        | 0.66%   |
| 16      | 39        | 0.58%   |
| 84      | 37        | 0.55%   |
| 54      | 31        | 0.46%   |
| 72      | 27        | 0.4%    |
| 25      | 22        | 0.33%   |
| 32      | 17        | 0.25%   |
| 52      | 10        | 0.15%   |
| 48      | 9         | 0.13%   |
| 28      | 9         | 0.13%   |
| 47      | 8         | 0.12%   |
| 42      | 8         | 0.12%   |
| 26      | 8         | 0.12%   |
| 46      | 7         | 0.1%    |
| 37      | 7         | 0.1%    |
| 43      | 6         | 0.09%   |
| 8       | 6         | 0.09%   |
| 65      | 5         | 0.07%   |
| 39      | 5         | 0.07%   |
| 29      | 5         | 0.07%   |
| 142     | 4         | 0.06%   |
| 60      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2786      | 42.06%  |
| 501-600        | 1175      | 17.74%  |
| 401-500        | 871       | 13.15%  |
| 201-300        | 582       | 8.79%   |
| 351-400        | 391       | 5.9%    |
| Unknown        | 359       | 5.42%   |
| 601-700        | 134       | 2.02%   |
| 701-800        | 88        | 1.33%   |
| 1001-1500      | 84        | 1.27%   |
| 1501-2000      | 66        | 1%      |
| 801-900        | 60        | 0.91%   |
| 901-1000       | 14        | 0.21%   |
| 101-200        | 8         | 0.12%   |
| More than 2000 | 4         | 0.06%   |
| 1-100          | 2         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4501      | 72.87%  |
| 16/10   | 838       | 13.57%  |
| Unknown | 296       | 4.79%   |
| 5/4     | 283       | 4.58%   |
| 3/2     | 85        | 1.38%   |
| 4/3     | 72        | 1.17%   |
| 21/9    | 72        | 1.17%   |
| 6/5     | 12        | 0.19%   |
| 32/9    | 7         | 0.11%   |
| 1.00    | 4         | 0.06%   |
| 0.62    | 3         | 0.05%   |
| 0.67    | 2         | 0.03%   |
| 2.65    | 1         | 0.02%   |
| 2.21    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2079      | 31.26%  |
| 201-250        | 1082      | 16.27%  |
| 81-90          | 661       | 9.94%   |
| 151-200        | 513       | 7.71%   |
| 301-350        | 451       | 6.78%   |
| Unknown        | 359       | 5.4%    |
| 71-80          | 258       | 3.88%   |
| 141-150        | 226       | 3.4%    |
| 351-500        | 164       | 2.47%   |
| 251-300        | 147       | 2.21%   |
| 121-130        | 147       | 2.21%   |
| More than 1000 | 133       | 2%      |
| 61-70          | 108       | 1.62%   |
| 501-1000       | 96        | 1.44%   |
| 41-50          | 74        | 1.11%   |
| 51-60          | 66        | 0.99%   |
| 131-140        | 33        | 0.5%    |
| 111-120        | 28        | 0.42%   |
| 91-100         | 17        | 0.26%   |
| 1-40           | 9         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2322      | 35.59%  |
| 101-120       | 1734      | 26.58%  |
| 121-160       | 1520      | 23.3%   |
| Unknown       | 359       | 5.5%    |
| 161-240       | 356       | 5.46%   |
| 1-50          | 122       | 1.87%   |
| More than 240 | 111       | 1.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5371      | 82.82%  |
| 2     | 798       | 12.31%  |
| 0     | 245       | 3.78%   |
| 3     | 68        | 1.05%   |
| 4     | 3         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3470      | 36.09%  |
| Intel                             | 2727      | 28.36%  |
| Qualcomm Atheros                  | 1198      | 12.46%  |
| Broadcom                          | 578       | 6.01%   |
| Marvell Technology Group          | 195       | 2.03%   |
| Broadcom Limited                  | 138       | 1.44%   |
| TP-Link                           | 135       | 1.4%    |
| Nvidia                            | 134       | 1.39%   |
| Ralink Technology                 | 123       | 1.28%   |
| Ralink                            | 106       | 1.1%    |
| MediaTek                          | 77        | 0.8%    |
| Qualcomm Atheros Communications   | 50        | 0.52%   |
| Huawei Technologies               | 50        | 0.52%   |
| ASIX Electronics                  | 40        | 0.42%   |
| D-Link System                     | 39        | 0.41%   |
| Xiaomi                            | 33        | 0.34%   |
| Samsung Electronics               | 33        | 0.34%   |
| D-Link                            | 32        | 0.33%   |
| VIA Technologies                  | 30        | 0.31%   |
| Sitecom Europe                    | 30        | 0.31%   |
| Dell                              | 26        | 0.27%   |
| NetGear                           | 24        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 23        | 0.24%   |
| ASUSTek Computer                  | 20        | 0.21%   |
| Sierra Wireless                   | 18        | 0.19%   |
| Ericsson Business Mobile Networks | 17        | 0.18%   |
| Microsoft                         | 16        | 0.17%   |
| JMicron Technology                | 16        | 0.17%   |
| Attansic Technology               | 16        | 0.17%   |
| Belkin Components                 | 12        | 0.12%   |
| Qualcomm                          | 11        | 0.11%   |
| Microchip Technology              | 11        | 0.11%   |
| Hewlett-Packard                   | 11        | 0.11%   |
| DisplayLink                       | 11        | 0.11%   |
| Gemtek                            | 9         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 8         | 0.08%   |
| OPPO Electronics                  | 8         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 8         | 0.08%   |
| Lenovo                            | 7         | 0.07%   |
| Aquantia                          | 7         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2363      | 21.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 421       | 3.79%   |
| Intel Wi-Fi 6 AX200                                                     | 215       | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 202       | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 197       | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 180       | 1.62%   |
| Intel Wireless 8265 / 8275                                              | 174       | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 167       | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 157       | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 151       | 1.36%   |
| Intel Wireless 7265                                                     | 150       | 1.35%   |
| Intel Wireless 3165                                                     | 141       | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 133       | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 125       | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 116       | 1.05%   |
| Intel Ethernet Connection (2) I219-V                                    | 101       | 0.91%   |
| Intel I211 Gigabit Network Connection                                   | 99        | 0.89%   |
| Intel Wireless 7260                                                     | 98        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 93        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 82        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 82        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 80        | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 78        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 71        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                 | 71        | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                       | 68        | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 68        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 67        | 0.6%    |
| Intel Wireless 8260                                                     | 66        | 0.59%   |
| Intel WiFi Link 5100                                                    | 65        | 0.59%   |
| Intel Ethernet Connection I217-LM                                       | 55        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 55        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 54        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 53        | 0.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 49        | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 48        | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 47        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2044      | 39.76%  |
| Qualcomm Atheros                      | 1001      | 19.47%  |
| Realtek Semiconductor                 | 909       | 17.68%  |
| Broadcom                              | 376       | 7.31%   |
| TP-Link                               | 125       | 2.43%   |
| Ralink Technology                     | 123       | 2.39%   |
| Ralink                                | 106       | 2.06%   |
| Broadcom Limited                      | 77        | 1.5%    |
| MediaTek                              | 68        | 1.32%   |
| Qualcomm Atheros Communications       | 50        | 0.97%   |
| D-Link System                         | 31        | 0.6%    |
| D-Link                                | 31        | 0.6%    |
| Sitecom Europe                        | 29        | 0.56%   |
| NetGear                               | 23        | 0.45%   |
| ASUSTek Computer                      | 19        | 0.37%   |
| Sierra Wireless                       | 18        | 0.35%   |
| Dell                                  | 16        | 0.31%   |
| Microsoft                             | 13        | 0.25%   |
| Marvell Technology Group              | 12        | 0.23%   |
| Belkin Components                     | 12        | 0.23%   |
| Gemtek                                | 9         | 0.18%   |
| Ericsson Business Mobile Networks     | 7         | 0.14%   |
| Linksys                               | 6         | 0.12%   |
| Fibocom                               | 6         | 0.12%   |
| AVM                                   | 6         | 0.12%   |
| ZyDAS                                 | 4         | 0.08%   |
| Qualcomm                              | 3         | 0.06%   |
| ZyXEL Communications                  | 2         | 0.04%   |
| U.S. Robotics                         | 2         | 0.04%   |
| Qcom                                  | 2         | 0.04%   |
| Hewlett-Packard                       | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 215       | 4.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 202       | 3.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 180       | 3.48%   |
| Intel Wireless 8265 / 8275                                              | 174       | 3.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 167       | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 157       | 3.04%   |
| Intel Wireless 7265                                                     | 150       | 2.9%    |
| Intel Wireless 3165                                                     | 141       | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 133       | 2.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 125       | 2.42%   |
| Intel Wi-Fi 6 AX201                                                     | 116       | 2.24%   |
| Intel Wireless 7260                                                     | 98        | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 93        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 82        | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 80        | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 78        | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 71        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 68        | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 67        | 1.3%    |
| Intel Wireless 8260                                                     | 66        | 1.28%   |
| Intel WiFi Link 5100                                                    | 65        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 55        | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 54        | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 49        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 48        | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                         | 47        | 0.91%   |
| Intel Wireless-AC 9260                                                  | 46        | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 44        | 0.85%   |
| Realtek 802.11ac NIC                                                    | 44        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 43        | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 40        | 0.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 39        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 39        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 37        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 34        | 0.66%   |
| Intel Centrino Advanced-N 6200                                          | 34        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 32        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3131      | 54.45%  |
| Intel                             | 1278      | 22.23%  |
| Qualcomm Atheros                  | 318       | 5.53%   |
| Broadcom                          | 272       | 4.73%   |
| Marvell Technology Group          | 183       | 3.18%   |
| Nvidia                            | 133       | 2.31%   |
| Broadcom Limited                  | 62        | 1.08%   |
| Huawei Technologies               | 42        | 0.73%   |
| ASIX Electronics                  | 40        | 0.7%    |
| Xiaomi                            | 33        | 0.57%   |
| Samsung Electronics               | 31        | 0.54%   |
| VIA Technologies                  | 29        | 0.5%    |
| Silicon Integrated Systems [SiS]  | 21        | 0.37%   |
| JMicron Technology                | 16        | 0.28%   |
| Attansic Technology               | 16        | 0.28%   |
| DisplayLink                       | 11        | 0.19%   |
| TP-Link                           | 10        | 0.17%   |
| MediaTek                          | 9         | 0.16%   |
| Qualcomm                          | 8         | 0.14%   |
| OPPO Electronics                  | 8         | 0.14%   |
| D-Link System                     | 8         | 0.14%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 7         | 0.12%   |
| Microchip Technology              | 7         | 0.12%   |
| Lenovo                            | 7         | 0.12%   |
| Aquantia                          | 7         | 0.12%   |
| Apple                             | 7         | 0.12%   |
| HMD Global                        | 6         | 0.1%    |
| 3Com                              | 5         | 0.09%   |
| T & A Mobile Phones               | 4         | 0.07%   |
| Motorola PCS                      | 4         | 0.07%   |
| ICS Advent                        | 4         | 0.07%   |
| LG Electronics                    | 3         | 0.05%   |
| Spreadtrum Communications         | 2         | 0.03%   |
| Hewlett-Packard                   | 2         | 0.03%   |
| Google                            | 2         | 0.03%   |
| Foxconn / Hon Hai                 | 2         | 0.03%   |
| ULi Electronics                   | 1         | 0.02%   |
| SysKonnect                        | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2363      | 40.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 421       | 7.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 197       | 3.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 151       | 2.59%   |
| Intel Ethernet Connection (2) I219-V                              | 101       | 1.73%   |
| Intel I211 Gigabit Network Connection                             | 99        | 1.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 82        | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 71        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 68        | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 55        | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 53        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 41        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 41        | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 41        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 39        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 35        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 31        | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 30        | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 30        | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 30        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 29        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 29        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 28        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 28        | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 27        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 27        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 27        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 26        | 0.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.45%   |
| Huawei ELS-NX9                                                    | 25        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.39%   |
| Intel Ethernet Connection (10) I219-V                             | 23        | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 22        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5430      | 52.29%  |
| WiFi     | 4857      | 46.77%  |
| Modem    | 86        | 0.83%   |
| Unknown  | 11        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3796      | 58.44%  |
| Ethernet | 2695      | 41.49%  |
| Unknown  | 3         | 0.05%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3437      | 53.9%   |
| 1     | 2672      | 41.9%   |
| 0     | 154       | 2.41%   |
| 3     | 96        | 1.51%   |
| 4     | 13        | 0.2%    |
| 5     | 2         | 0.03%   |
| 12    | 1         | 0.02%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6043      | 94.33%  |
| Yes  | 363       | 5.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1558      | 43.69%  |
| Realtek Semiconductor           | 420       | 11.78%  |
| Cambridge Silicon Radio         | 224       | 6.28%   |
| Qualcomm Atheros Communications | 217       | 6.09%   |
| Broadcom                        | 193       | 5.41%   |
| IMC Networks                    | 184       | 5.16%   |
| Lite-On Technology              | 159       | 4.46%   |
| Foxconn / Hon Hai               | 123       | 3.45%   |
| Apple                           | 123       | 3.45%   |
| Hewlett-Packard                 | 61        | 1.71%   |
| ASUSTek Computer                | 55        | 1.54%   |
| Realtek                         | 52        | 1.46%   |
| Dell                            | 39        | 1.09%   |
| Ralink                          | 32        | 0.9%    |
| Toshiba                         | 31        | 0.87%   |
| Alps Electric                   | 15        | 0.42%   |
| Marvell Semiconductor           | 12        | 0.34%   |
| Integrated System Solution      | 10        | 0.28%   |
| MediaTek                        | 9         | 0.25%   |
| Ralink Technology               | 7         | 0.2%    |
| TP-Link                         | 6         | 0.17%   |
| Foxconn International           | 5         | 0.14%   |
| Sitecom Europe                  | 4         | 0.11%   |
| Belkin Components               | 4         | 0.11%   |
| Askey Computer                  | 4         | 0.11%   |
| Chicony Electronics             | 3         | 0.08%   |
| Unknown                         | 2         | 0.06%   |
| Taiyo Yuden                     | 2         | 0.06%   |
| D-Link System                   | 2         | 0.06%   |
| Conwise Technology              | 2         | 0.06%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu Siemens Computers       | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| 3Com                            | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 653       | 18.31%  |
| Realtek Bluetooth Radio                                                             | 275       | 7.71%   |
| Intel Bluetooth Device                                                              | 275       | 7.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 232       | 6.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 224       | 6.28%   |
| Intel AX200 Bluetooth                                                               | 198       | 5.55%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 117       | 3.28%   |
| Lite-On Bluetooth Device                                                            | 95        | 2.66%   |
| IMC Networks Bluetooth Device                                                       | 90        | 2.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 84        | 2.35%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 66        | 1.85%   |
| Realtek Bluetooth Radio                                                             | 52        | 1.46%   |
| Apple Bluetooth Host Controller                                                     | 49        | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 47        | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 47        | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 44        | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 43        | 1.21%   |
| IMC Networks Bluetooth Radio                                                        | 42        | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 38        | 1.07%   |
| Broadcom BCM2045 Bluetooth                                                          | 37        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 36        | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 33        | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 32        | 0.9%    |
| Intel AX210 Bluetooth                                                               | 29        | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 29        | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 29        | 0.81%   |
| Apple Bluetooth USB Host Controller                                                 | 28        | 0.78%   |
| Apple Bluetooth HCI                                                                 | 26        | 0.73%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 25        | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 23        | 0.64%   |
| IMC Networks Wireless_Device                                                        | 20        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 17        | 0.48%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 16        | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 16        | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 15        | 0.42%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 14        | 0.39%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 14        | 0.39%   |
| Toshiba Integrated Bluetooth HCI                                                    | 13        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4613      | 54.88%  |
| AMD                                  | 1681      | 20%     |
| Nvidia                               | 1367      | 16.26%  |
| C-Media Electronics                  | 143       | 1.7%    |
| Logitech                             | 52        | 0.62%   |
| Creative Labs                        | 46        | 0.55%   |
| VIA Technologies                     | 38        | 0.45%   |
| Silicon Integrated Systems [SiS]     | 32        | 0.38%   |
| JMTek                                | 27        | 0.32%   |
| GN Netcom                            | 23        | 0.27%   |
| Texas Instruments                    | 21        | 0.25%   |
| Generalplus Technology               | 19        | 0.23%   |
| Realtek Semiconductor                | 18        | 0.21%   |
| Creative Technology                  | 18        | 0.21%   |
| Razer USA                            | 16        | 0.19%   |
| M-Audio                              | 15        | 0.18%   |
| Focusrite-Novation                   | 15        | 0.18%   |
| Kingston Technology                  | 11        | 0.13%   |
| BEHRINGER International              | 10        | 0.12%   |
| ASUSTek Computer                     | 10        | 0.12%   |
| Tenx Technology                      | 8         | 0.1%    |
| Samson Technologies                  | 8         | 0.1%    |
| Plantronics                          | 8         | 0.1%    |
| Micro Star International             | 8         | 0.1%    |
| Trust                                | 7         | 0.08%   |
| Microsoft                            | 7         | 0.08%   |
| Lenovo                               | 7         | 0.08%   |
| Hewlett-Packard                      | 7         | 0.08%   |
| Ensoniq                              | 7         | 0.08%   |
| Dell                                 | 7         | 0.08%   |
| CMX Systems                          | 6         | 0.07%   |
| Apple                                | 6         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.06%   |
| Sony                                 | 5         | 0.06%   |
| Corsair                              | 5         | 0.06%   |
| Cambridge Silicon Radio              | 5         | 0.06%   |
| Yamaha                               | 4         | 0.05%   |
| XMOS                                 | 4         | 0.05%   |
| SAVITECH                             | 4         | 0.05%   |
| Huawei Technologies                  | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 491       | 4.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 419       | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 400       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 392       | 3.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 295       | 3%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 293       | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 286       | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 249       | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 216       | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 212       | 2.16%   |
| AMD FCH Azalia Controller                                                  | 207       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 192       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 191       | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 176       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 173       | 1.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 169       | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 165       | 1.68%   |
| Intel 8 Series HD Audio Controller                                         | 165       | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 164       | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 145       | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 130       | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 125       | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 123       | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 119       | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                   | 117       | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 115       | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 106       | 1.08%   |
| Nvidia High Definition Audio Controller                                    | 104       | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 102       | 1.04%   |
| Intel Broadwell-U Audio Controller                                         | 101       | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 99        | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 96        | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 94        | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 93        | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 92        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 79        | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 78        | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 71        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 70        | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 65        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 859       | 22.12%  |
| SK hynix                     | 653       | 16.81%  |
| Kingston                     | 477       | 12.28%  |
| Unknown                      | 462       | 11.89%  |
| Micron Technology            | 382       | 9.84%   |
| Crucial                      | 259       | 6.67%   |
| Corsair                      | 231       | 5.95%   |
| G.Skill                      | 79        | 2.03%   |
| Ramaxel Technology           | 76        | 1.96%   |
| Unknown (ABCD)               | 69        | 1.78%   |
| Elpida                       | 68        | 1.75%   |
| A-DATA Technology            | 56        | 1.44%   |
| Nanya Technology             | 42        | 1.08%   |
| Team                         | 32        | 0.82%   |
| Patriot                      | 23        | 0.59%   |
| Unknown                      | 18        | 0.46%   |
| Transcend                    | 13        | 0.33%   |
| ASint Technology             | 10        | 0.26%   |
| Unifosa                      | 7         | 0.18%   |
| Toshiba                      | 6         | 0.15%   |
| Qimonda                      | 6         | 0.15%   |
| 48spaces                     | 4         | 0.1%    |
| Timetec                      | 3         | 0.08%   |
| Silicon Power                | 3         | 0.08%   |
| Patriot Memory (PDP Systems) | 3         | 0.08%   |
| Hewlett-Packard              | 3         | 0.08%   |
| GeIL                         | 3         | 0.08%   |
| Unknown (AB)                 | 2         | 0.05%   |
| PLEXHD                       | 2         | 0.05%   |
| GOODRAM                      | 2         | 0.05%   |
| Goldkey                      | 2         | 0.05%   |
| CSX                          | 2         | 0.05%   |
| A Force                      | 2         | 0.05%   |
| V-Color                      | 1         | 0.03%   |
| Unknown (D386)               | 1         | 0.03%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.03%   |
| Unknown (0x8551)             | 1         | 0.03%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.03%   |
| Unigen                       | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 52        | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 39        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 29        | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 28        | 0.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 27        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 22        | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 22        | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.48%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 20        | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.43%   |
| Unknown                                                          | 18        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 17        | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 17        | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 17        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 16        | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 15        | 0.36%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 15        | 0.36%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 14        | 0.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.33%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 14        | 0.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 14        | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                      | 13        | 0.31%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 13        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1499      | 43.88%  |
| DDR3    | 1158      | 33.9%   |
| DDR2    | 240       | 7.03%   |
| LPDDR4  | 160       | 4.68%   |
| SDRAM   | 123       | 3.6%    |
| LPDDR3  | 95        | 2.78%   |
| Unknown | 76        | 2.22%   |
| DDR     | 30        | 0.88%   |
| DDR5    | 19        | 0.56%   |
| DRAM    | 10        | 0.29%   |
| LPDDR5  | 6         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1973      | 58.2%   |
| DIMM         | 1147      | 33.83%  |
| Row Of Chips | 255       | 7.52%   |
| Chip         | 9         | 0.27%   |
| FB-DIMM      | 4         | 0.12%   |
| Unknown      | 2         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1332      | 36.11%  |
| 4096  | 1125      | 30.5%   |
| 2048  | 569       | 15.42%  |
| 16384 | 419       | 11.36%  |
| 1024  | 147       | 3.98%   |
| 32768 | 55        | 1.49%   |
| 512   | 34        | 0.92%   |
| 256   | 5         | 0.14%   |
| 3072  | 2         | 0.05%   |
| 32    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 696       | 18.93%  |
| 2667    | 518       | 14.09%  |
| 3200    | 466       | 12.67%  |
| 2400    | 304       | 8.27%   |
| 1333    | 242       | 6.58%   |
| 2133    | 166       | 4.51%   |
| 1334    | 138       | 3.75%   |
| Unknown | 120       | 3.26%   |
| 667     | 110       | 2.99%   |
| 3600    | 108       | 2.94%   |
| 800     | 100       | 2.72%   |
| 1867    | 91        | 2.47%   |
| 4267    | 53        | 1.44%   |
| 1066    | 52        | 1.41%   |
| 3266    | 44        | 1.2%    |
| 1067    | 33        | 0.9%    |
| 3000    | 29        | 0.79%   |
| 2933    | 28        | 0.76%   |
| 3466    | 25        | 0.68%   |
| 3400    | 24        | 0.65%   |
| 3733    | 22        | 0.6%    |
| 533     | 22        | 0.6%    |
| 1866    | 20        | 0.54%   |
| 4800    | 18        | 0.49%   |
| 2048    | 18        | 0.49%   |
| 4199    | 17        | 0.46%   |
| 1800    | 16        | 0.44%   |
| 8400    | 15        | 0.41%   |
| 400     | 15        | 0.41%   |
| 266     | 15        | 0.41%   |
| 2666    | 11        | 0.3%    |
| 4266    | 9         | 0.24%   |
| 3800    | 9         | 0.24%   |
| 975     | 9         | 0.24%   |
| 333     | 9         | 0.24%   |
| 2800    | 8         | 0.22%   |
| 2000    | 7         | 0.19%   |
| 1639    | 7         | 0.19%   |
| 6400    | 6         | 0.16%   |
| 49926   | 4         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 101       | 37.69%  |
| Samsung Electronics   | 43        | 16.04%  |
| Canon                 | 37        | 13.81%  |
| Brother Industries    | 31        | 11.57%  |
| Seiko Epson           | 28        | 10.45%  |
| Lexmark International | 4         | 1.49%   |
| Dymo-CoStar           | 4         | 1.49%   |
| Xerox                 | 3         | 1.12%   |
| Pantum                | 3         | 1.12%   |
| Prolific Technology   | 2         | 0.75%   |
| Oki Data              | 2         | 0.75%   |
| Apple                 | 2         | 0.75%   |
| Toshiba TEC           | 1         | 0.37%   |
| STMicroelectronics    | 1         | 0.37%   |
| Sato                  | 1         | 0.37%   |
| Sagem                 | 1         | 0.37%   |
| Ricoh                 | 1         | 0.37%   |
| QinHeng Electronics   | 1         | 0.37%   |
| Kyocera               | 1         | 0.37%   |
| ICS Advent            | 1         | 0.37%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2510 Series                                            | 8         | 2.97%   |
| Samsung M2020 Series                                                  | 7         | 2.6%    |
| HP OfficeJet 6950                                                     | 7         | 2.6%    |
| Samsung M267x 287x Series                                             | 6         | 2.23%   |
| HP Deskjet 2050 J510                                                  | 6         | 2.23%   |
| Seiko Epson Printer                                                   | 5         | 1.86%   |
| Samsung ML-216x Series Laser Printer                                  | 5         | 1.86%   |
| HP ENVY 4520 series                                                   | 5         | 1.86%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 4         | 1.49%   |
| HP Officejet 2620 series                                              | 4         | 1.49%   |
| HP LaserJet 1018                                                      | 4         | 1.49%   |
| Canon PIXMA MG3600 Series                                             | 4         | 1.49%   |
| Samsung ML-1660 Series                                                | 3         | 1.12%   |
| Samsung ML-1640 Series Laser Printer                                  | 3         | 1.12%   |
| Samsung M2070 Series                                                  | 3         | 1.12%   |
| Samsung Composite Device                                              | 3         | 1.12%   |
| HP LaserJet Professional P 1102w                                      | 3         | 1.12%   |
| HP LaserJet P1102                                                     | 3         | 1.12%   |
| HP LaserJet P1005                                                     | 3         | 1.12%   |
| HP LaserJet 1200                                                      | 3         | 1.12%   |
| HP ENVY 5000 series                                                   | 3         | 1.12%   |
| HP Deskjet F4500 series                                               | 3         | 1.12%   |
| HP Deskjet 3520 series                                                | 3         | 1.12%   |
| HP Deskjet 3050A                                                      | 3         | 1.12%   |
| Dymo-CoStar LabelWriter 450                                           | 3         | 1.12%   |
| Canon PIXMA MG2500 Series                                             | 3         | 1.12%   |
| Canon LiDE 400                                                        | 3         | 1.12%   |
| Brother MFC-L2700DW                                                   | 3         | 1.12%   |
| Brother HL-3140CW series                                              | 3         | 1.12%   |
| Brother DCP-1610W                                                     | 3         | 1.12%   |
| Seiko Epson ET-2820 Series                                            | 2         | 0.74%   |
| Samsung SCX-4623 Series                                               | 2         | 0.74%   |
| Prolific PL2305 Parallel Port                                         | 2         | 0.74%   |
| Oki Data USB Device                                                   | 2         | 0.74%   |
| Lexmark International InkJet Color Printer                            | 2         | 0.74%   |
| HP Officejet Pro 6230                                                 | 2         | 0.74%   |
| HP OfficeJet 5200 series                                              | 2         | 0.74%   |
| HP OfficeJet 4650 series                                              | 2         | 0.74%   |
| HP Officejet 4630 series                                              | 2         | 0.74%   |
| HP Officejet 4500 G510n-z                                             | 2         | 0.74%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 37        | 52.11%  |
| Seiko Epson        | 19        | 26.76%  |
| Hewlett-Packard    | 9         | 12.68%  |
| Mustek Systems     | 4         | 5.63%   |
| Ultima Electronics | 1         | 1.41%   |
| Plustek            | 1         | 1.41%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 9         | 12.5%   |
| Canon CanoScan LiDE 210                                                               | 5         | 6.94%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 5.56%   |
| Canon CanoScan LiDE 120                                                               | 4         | 5.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 4.17%   |
| Canon CanoScan LiDE 100                                                               | 3         | 4.17%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2         | 2.78%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2         | 2.78%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.78%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 2.78%   |
| HP Scanjet 200                                                                        | 2         | 2.78%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.78%   |
| Canon CanoScan LIDE 25                                                                | 2         | 2.78%   |
| Canon CanoScan LiDE 220                                                               | 2         | 2.78%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.39%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 1.39%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 1.39%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 1.39%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.39%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.39%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.39%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1         | 1.39%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.39%   |
| Seiko Epson ES-D400 [GT-S80]                                                          | 1         | 1.39%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.39%   |
| Plustek 600DPI USB Scanner                                                            | 1         | 1.39%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.39%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 1.39%   |
| HP Scanjet G2710                                                                      | 1         | 1.39%   |
| HP ScanJet 3800c                                                                      | 1         | 1.39%   |
| HP ScanJet 3570c                                                                      | 1         | 1.39%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.39%   |
| HP ScanJet 2400c                                                                      | 1         | 1.39%   |
| HP PSC 1200                                                                           | 1         | 1.39%   |
| HP HP4470C                                                                            | 1         | 1.39%   |
| Canon CanoScan LiDE 90                                                                | 1         | 1.39%   |
| Canon CanoScan LiDE 700F                                                              | 1         | 1.39%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.39%   |
| Canon CanoScan LiDE 60                                                                | 1         | 1.39%   |
| Canon CanoScan 4400F                                                                  | 1         | 1.39%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 910       | 23.41%  |
| IMC Networks                           | 419       | 10.78%  |
| Microdia                               | 294       | 7.56%   |
| Realtek Semiconductor                  | 272       | 7%      |
| Acer                                   | 266       | 6.84%   |
| Logitech                               | 190       | 4.89%   |
| Quanta                                 | 174       | 4.48%   |
| Suyin                                  | 172       | 4.42%   |
| Sunplus Innovation Technology          | 163       | 4.19%   |
| Cheng Uei Precision Industry (Foxlink) | 145       | 3.73%   |
| Apple                                  | 103       | 2.65%   |
| Alcor Micro                            | 90        | 2.31%   |
| Syntek                                 | 84        | 2.16%   |
| Lite-On Technology                     | 82        | 2.11%   |
| Microsoft                              | 59        | 1.52%   |
| Luxvisions Innotech Limited            | 58        | 1.49%   |
| Ricoh                                  | 46        | 1.18%   |
| Silicon Motion                         | 44        | 1.13%   |
| Z-Star Microelectronics                | 25        | 0.64%   |
| Samsung Electronics                    | 23        | 0.59%   |
| ARC International                      | 21        | 0.54%   |
| Trust                                  | 15        | 0.39%   |
| Generalplus Technology                 | 15        | 0.39%   |
| ALi                                    | 15        | 0.39%   |
| Primax Electronics                     | 13        | 0.33%   |
| KYE Systems (Mouse Systems)            | 10        | 0.26%   |
| GEMBIRD                                | 10        | 0.26%   |
| SunplusIT                              | 9         | 0.23%   |
| icSpring                               | 9         | 0.23%   |
| Cubeternet                             | 9         | 0.23%   |
| WaveRider Communications               | 8         | 0.21%   |
| Genesys Logic                          | 8         | 0.21%   |
| Sunplus Technology                     | 7         | 0.18%   |
| Sonix Technology                       | 7         | 0.18%   |
| Lenovo                                 | 7         | 0.18%   |
| Sunplus IT                             | 6         | 0.15%   |
| Importek                               | 6         | 0.15%   |
| Huawei Technologies                    | 6         | 0.15%   |
| DigiTech                               | 6         | 0.15%   |
| 2M UVC CAMERA                          | 6         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 137       | 3.5%    |
| Microdia Integrated_Webcam_HD                           | 98        | 2.5%    |
| Chicony HD WebCam                                       | 89        | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 76        | 1.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 70        | 1.79%   |
| IMC Networks Integrated Camera                          | 68        | 1.74%   |
| Realtek Integrated_Webcam_HD                            | 65        | 1.66%   |
| Acer Integrated Camera                                  | 63        | 1.61%   |
| Logitech Webcam C270                                    | 56        | 1.43%   |
| Realtek USB Camera                                      | 52        | 1.33%   |
| Syntek Integrated Camera                                | 43        | 1.1%    |
| Chicony USB2.0 HD UVC WebCam                            | 42        | 1.07%   |
| Alcor Micro USB Camera                                  | 42        | 1.07%   |
| Chicony USB2.0 VGA UVC WebCam                           | 39        | 1%      |
| Chicony HP Truevision HD                                | 39        | 1%      |
| Sunplus Integrated_Webcam_HD                            | 36        | 0.92%   |
| Apple Built-in iSight                                   | 34        | 0.87%   |
| Acer Lenovo EasyCamera                                  | 34        | 0.87%   |
| Quanta HP TrueVision HD Camera                          | 33        | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 32        | 0.82%   |
| Chicony HP Wide Vision HD Camera                        | 29        | 0.74%   |
| Chicony FJ Camera                                       | 29        | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE                               | 29        | 0.74%   |
| Microsoft LifeCam HD-3000                               | 28        | 0.72%   |
| Microdia Webcam Vitade AF                               | 28        | 0.72%   |
| Chicony HP Webcam                                       | 28        | 0.72%   |
| Chicony HP TrueVision HD Camera                         | 27        | 0.69%   |
| Chicony HP HD Camera                                    | 27        | 0.69%   |
| Quanta HP Webcam                                        | 25        | 0.64%   |
| IMC Networks ov9734_azurewave_camera                    | 25        | 0.64%   |
| Sunplus HD WebCam                                       | 24        | 0.61%   |
| Microdia USB 2.0 Camera                                 | 24        | 0.61%   |
| Logitech HD Pro Webcam C920                             | 24        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 24        | 0.61%   |
| Samsung Galaxy A5 (MTP)                                 | 23        | 0.59%   |
| Realtek USB2.0 VGA UVC WebCam                           | 23        | 0.59%   |
| Microdia Sonix USB 2.0 Camera                           | 23        | 0.59%   |
| Alcor Micro Asus Integrated Webcam                      | 23        | 0.59%   |
| Suyin HP Truevision HD                                  | 22        | 0.56%   |
| Logitech Webcam C170                                    | 22        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 194       | 29%     |
| Synaptics                          | 173       | 25.86%  |
| Shenzhen Goodix Technology         | 115       | 17.19%  |
| Elan Microelectronics              | 73        | 10.91%  |
| Upek                               | 34        | 5.08%   |
| LighTuning Technology              | 34        | 5.08%   |
| AuthenTec                          | 34        | 5.08%   |
| STMicroelectronics                 | 5         | 0.75%   |
| Focal-systems.Corp                 | 4         | 0.6%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.3%    |
| Microsoft                          | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 78        | 11.66%  |
| Unknown                                                                    | 65        | 9.72%   |
| Elan ELAN:ARM-M4                                                           | 48        | 7.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 6.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 5.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 4.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 4.04%   |
| Elan ELAN:Fingerprint                                                      | 25        | 3.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 24        | 3.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 2.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 19        | 2.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.69%   |
| Synaptics  WBDI                                                            | 18        | 2.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 2.54%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 2.24%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 1.79%   |
| Validity Sensors VFS491                                                    | 10        | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.49%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 1.49%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.35%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.2%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.2%    |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.05%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.05%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 6         | 0.9%    |
| AuthenTec AES1600                                                          | 6         | 0.9%    |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.75%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 0.75%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.75%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.75%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.6%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.6%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.45%   |
| AuthenTec AES2810                                                          | 3         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 100       | 34.01%  |
| Alcor Micro               | 83        | 28.23%  |
| O2 Micro                  | 27        | 9.18%   |
| Advanced Card Systems     | 20        | 6.8%    |
| Lenovo                    | 15        | 5.1%    |
| Upek                      | 10        | 3.4%    |
| BIT4ID                    | 9         | 3.06%   |
| Gemalto (was Gemplus)     | 8         | 2.72%   |
| Realtek Semiconductor     | 7         | 2.38%   |
| SCM Microsystems          | 4         | 1.36%   |
| OmniKey                   | 3         | 1.02%   |
| Clay Logic                | 3         | 1.02%   |
| Reiner SCT Kartensysteme  | 2         | 0.68%   |
| Microchip Technology      | 1         | 0.34%   |
| In Focus Systems          | 1         | 0.34%   |
| Fujitsu Siemens Computers | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 79        | 26.78%  |
| Broadcom 58200                                                               | 31        | 10.51%  |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 10.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 7.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 6.78%   |
| Broadcom 5880                                                                | 17        | 5.76%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 17        | 5.76%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 5.08%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 3.39%   |
| BIT4ID miniLector EVO                                                        | 9         | 3.05%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 7         | 2.37%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.36%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.36%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.02%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 1.02%   |
| Advanced Card Systems ACR122U                                                | 3         | 1.02%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 2         | 0.68%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.68%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.34%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.34%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.34%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.34%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.34%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.34%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.34%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.34%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4658      | 71.57%  |
| 1     | 1482      | 22.77%  |
| 2     | 320       | 4.92%   |
| 3     | 30        | 0.46%   |
| 4     | 11        | 0.17%   |
| 5     | 5         | 0.08%   |
| 6     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 662       | 30.15%  |
| Graphics card            | 514       | 23.41%  |
| Net/wireless             | 275       | 12.52%  |
| Chipcard                 | 245       | 11.16%  |
| Multimedia controller    | 97        | 4.42%   |
| Camera                   | 78        | 3.55%   |
| Communication controller | 71        | 3.23%   |
| Bluetooth                | 60        | 2.73%   |
| Sound                    | 31        | 1.41%   |
| Unassigned class         | 28        | 1.28%   |
| Storage                  | 28        | 1.28%   |
| Modem                    | 23        | 1.05%   |
| Card reader              | 22        | 1%      |
| Flash memory             | 18        | 0.82%   |
| Net/ethernet             | 15        | 0.68%   |
| Network                  | 7         | 0.32%   |
| Storage/raid             | 5         | 0.23%   |
| Dvb card                 | 5         | 0.23%   |
| Firewire controller      | 4         | 0.18%   |
| Video                    | 2         | 0.09%   |
| Tv card                  | 2         | 0.09%   |
| Storage/ide              | 2         | 0.09%   |
| Wireless                 | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |


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

Total: 1207

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Dell          | Precision 7730              | Notebook    | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | Notebook    | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| MSI           | MS-AEC21                    | All in one  | [e541cd3043](https://linux-hardware.org/?probe=e541cd3043) | Jan 23, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d2b797f3de](https://linux-hardware.org/?probe=d2b797f3de) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bfaffed5d2](https://linux-hardware.org/?probe=bfaffed5d2) | Jan 21, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a9d66d6af6](https://linux-hardware.org/?probe=a9d66d6af6) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0bc976587f](https://linux-hardware.org/?probe=0bc976587f) | Jan 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | Desktop     | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [6286dbdb0b](https://linux-hardware.org/?probe=6286dbdb0b) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | Notebook    | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| HP            | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [774322328a](https://linux-hardware.org/?probe=774322328a) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d94fa63122](https://linux-hardware.org/?probe=d94fa63122) | Jan 08, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [391d13c7ba](https://linux-hardware.org/?probe=391d13c7ba) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a5b2453630](https://linux-hardware.org/?probe=a5b2453630) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | Desktop     | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | Notebook    | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| HP            | Beats 15                    | Notebook    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Acer          | Aspire A517-53              | Notebook    | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | Notebook    | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| SGIN          | laptop                      | Notebook    | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| HP            | Sona                        | Notebook    | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [3d563943d4](https://linux-hardware.org/?probe=3d563943d4) | Dec 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | Notebook    | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1cbc80c6fb](https://linux-hardware.org/?probe=1cbc80c6fb) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | NOK                         | Desktop     | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8745419f51](https://linux-hardware.org/?probe=8745419f51) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [55e56516e5](https://linux-hardware.org/?probe=55e56516e5) | Dec 06, 2022 |
| HP            | Beats 15                    | Notebook    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HP            | EliteBook x360 1040 G5      | Convertible | [02c80899f7](https://linux-hardware.org/?probe=02c80899f7) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | Notebook    | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| Haier         | A1420EM                     | Notebook    | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fc681f2f42](https://linux-hardware.org/?probe=fc681f2f42) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [d876db7f78](https://linux-hardware.org/?probe=d876db7f78) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | Notebook    | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | Desktop     | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [12fe5843d1](https://linux-hardware.org/?probe=12fe5843d1) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | Notebook    | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | Notebook    | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [317efeba98](https://linux-hardware.org/?probe=317efeba98) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | Notebook    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [abfee9c5f7](https://linux-hardware.org/?probe=abfee9c5f7) | Oct 18, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [b106ebaef6](https://linux-hardware.org/?probe=b106ebaef6) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [159150cc56](https://linux-hardware.org/?probe=159150cc56) | Oct 17, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| JWIPC         | A320I S1                    | Desktop     | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | Notebook    | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [eb5e8725ae](https://linux-hardware.org/?probe=eb5e8725ae) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
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
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
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
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 67        | 6.91%   |
| 5.15.0-52-generic    | 66        | 6.81%   |
| 5.15.0-48-generic    | 41        | 4.23%   |
| 5.15.0-58-generic    | 40        | 4.13%   |
| 5.15.0-43-generic    | 37        | 3.82%   |
| 5.15.0-47-generic    | 36        | 3.72%   |
| 5.15.0-53-generic    | 33        | 3.41%   |
| 5.15.0-46-generic    | 33        | 3.41%   |
| 5.15.0-60-generic    | 32        | 3.3%    |
| 5.15.0-41-generic    | 29        | 2.99%   |
| 5.19.0-35-generic    | 28        | 2.89%   |
| 5.15.0-25-generic    | 27        | 2.79%   |
| 5.15.0-40-generic    | 26        | 2.68%   |
| 5.15.0-67-generic    | 25        | 2.58%   |
| 5.15.0-27-generic    | 24        | 2.48%   |
| 5.19.0-38-generic    | 22        | 2.27%   |
| 5.15.0-50-generic    | 22        | 2.27%   |
| 5.19.0-41-generic    | 18        | 1.86%   |
| 5.15.0-33-generic    | 18        | 1.86%   |
| 5.19.0-32-generic    | 17        | 1.75%   |
| 5.15.0-69-generic    | 15        | 1.55%   |
| 5.15.0-71-generic    | 14        | 1.44%   |
| 5.15.0-57-generic    | 14        | 1.44%   |
| 5.19.0-42-generic    | 13        | 1.34%   |
| 5.15.0-73-generic    | 12        | 1.24%   |
| 5.19.0-43-generic    | 11        | 1.14%   |
| 5.15.0-72-generic    | 11        | 1.14%   |
| 5.15.0-37-generic    | 10        | 1.03%   |
| 5.15.0-30-generic    | 10        | 1.03%   |
| 5.15.0-39-generic    | 9         | 0.93%   |
| 5.15.0-43-lowlatency | 8         | 0.83%   |
| 5.19.0-40-generic    | 7         | 0.72%   |
| 5.15.0-48-lowlatency | 7         | 0.72%   |
| 5.19.0-45-generic    | 6         | 0.62%   |
| 5.15.0-35-generic    | 6         | 0.62%   |
| 5.15.0-58-lowlatency | 5         | 0.52%   |
| 5.15.0-56-lowlatency | 5         | 0.52%   |
| 5.15.0-52-lowlatency | 5         | 0.52%   |
| 5.15.0-18-generic    | 5         | 0.52%   |
| 5.19.0-46-generic    | 4         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 702       | 77.14%  |
| 5.19.0  | 129       | 14.18%  |
| 5.17.0  | 16        | 1.76%   |
| 6.0.0   | 6         | 0.66%   |
| 5.13.0  | 6         | 0.66%   |
| 6.1.0   | 4         | 0.44%   |
| 6.2.2   | 2         | 0.22%   |
| 6.1.5   | 2         | 0.22%   |
| 6.0.7   | 2         | 0.22%   |
| 6.0.1   | 2         | 0.22%   |
| 5.19.5  | 2         | 0.22%   |
| 5.18.4  | 2         | 0.22%   |
| 5.18.10 | 2         | 0.22%   |
| 6.3.8   | 1         | 0.11%   |
| 6.3.6   | 1         | 0.11%   |
| 6.3.4   | 1         | 0.11%   |
| 6.3.1   | 1         | 0.11%   |
| 6.3.0   | 1         | 0.11%   |
| 6.2.8   | 1         | 0.11%   |
| 6.1.9   | 1         | 0.11%   |
| 6.1.12  | 1         | 0.11%   |
| 6.0.9   | 1         | 0.11%   |
| 6.0.8   | 1         | 0.11%   |
| 6.0.6   | 1         | 0.11%   |
| 5.4.0   | 1         | 0.11%   |
| 5.19.2  | 1         | 0.11%   |
| 5.19.12 | 1         | 0.11%   |
| 5.19.11 | 1         | 0.11%   |
| 5.18.6  | 1         | 0.11%   |
| 5.18.19 | 1         | 0.11%   |
| 5.18.15 | 1         | 0.11%   |
| 5.18.12 | 1         | 0.11%   |
| 5.17.6  | 1         | 0.11%   |
| 5.17.5  | 1         | 0.11%   |
| 5.17.4  | 1         | 0.11%   |
| 5.17.2  | 1         | 0.11%   |
| 5.17.14 | 1         | 0.11%   |
| 5.16.2  | 1         | 0.11%   |
| 5.16.11 | 1         | 0.11%   |
| 5.16.0  | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 704       | 77.53%  |
| 5.19    | 134       | 14.76%  |
| 5.17    | 21        | 2.31%   |
| 6.0     | 12        | 1.32%   |
| 6.1     | 8         | 0.88%   |
| 5.18    | 8         | 0.88%   |
| 5.13    | 6         | 0.66%   |
| 6.3     | 5         | 0.55%   |
| 6.2     | 3         | 0.33%   |
| 5.16    | 3         | 0.33%   |
| 5.4     | 1         | 0.11%   |
| 5.14    | 1         | 0.11%   |
| 5.11    | 1         | 0.11%   |
| 5.10    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 889       | 99.89%  |
| aarch64 | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 875       | 98.09%  |
| GNOME      | 6         | 0.67%   |
| KDE        | 4         | 0.45%   |
| XFCE       | 1         | 0.11%   |
| X-Cinnamon | 1         | 0.11%   |
| MATE       | 1         | 0.11%   |
| i3         | 1         | 0.11%   |
| GNUstep    | 1         | 0.11%   |
| Cinnamon   | 1         | 0.11%   |
| Budgie     | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 851       | 95.19%  |
| Wayland | 29        | 3.24%   |
| Tty     | 13        | 1.45%   |
| Web     | 1         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 662       | 73.97%  |
| Unknown | 159       | 17.77%  |
| GDM3    | 48        | 5.36%   |
| LightDM | 23        | 2.57%   |
| SLiM    | 1         | 0.11%   |
| LXDM    | 1         | 0.11%   |
| GDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 437       | 48.94%  |
| de_DE   | 71        | 7.95%   |
| it_IT   | 49        | 5.49%   |
| fr_FR   | 46        | 5.15%   |
| ru_RU   | 44        | 4.93%   |
| en_GB   | 36        | 4.03%   |
| pt_BR   | 23        | 2.58%   |
| en_AU   | 20        | 2.24%   |
| pl_PL   | 19        | 2.13%   |
| es_ES   | 18        | 2.02%   |
| en_IN   | 17        | 1.9%    |
| en_CA   | 13        | 1.46%   |
| hu_HU   | 6         | 0.67%   |
| es_AR   | 6         | 0.67%   |
| en_PH   | 6         | 0.67%   |
| en_NZ   | 6         | 0.67%   |
| tr_TR   | 5         | 0.56%   |
| en_ZA   | 5         | 0.56%   |
| en_SG   | 5         | 0.56%   |
| cs_CZ   | 5         | 0.56%   |
| C       | 4         | 0.45%   |
| zh_CN   | 3         | 0.34%   |
| nl_NL   | 3         | 0.34%   |
| el_GR   | 3         | 0.34%   |
| sl_SI   | 2         | 0.22%   |
| pt_PT   | 2         | 0.22%   |
| nl_BE   | 2         | 0.22%   |
| fr_CH   | 2         | 0.22%   |
| fr_BE   | 2         | 0.22%   |
| fi_FI   | 2         | 0.22%   |
| es_VE   | 2         | 0.22%   |
| es_MX   | 2         | 0.22%   |
| es_CO   | 2         | 0.22%   |
| es_CL   | 2         | 0.22%   |
| en_DE   | 2         | 0.22%   |
| de_CH   | 2         | 0.22%   |
| de_AT   | 2         | 0.22%   |
| Default | 2         | 0.22%   |
| zh_TW   | 1         | 0.11%   |
| sv_SE   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 493       | 55.02%  |
| BIOS | 403       | 44.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 792       | 88.49%  |
| Btrfs   | 39        | 4.36%   |
| Overlay | 33        | 3.69%   |
| Tmpfs   | 22        | 2.46%   |
| Xfs     | 5         | 0.56%   |
| Zfs     | 2         | 0.22%   |
| Ext3    | 1         | 0.11%   |
| Ext2    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 606       | 67.56%  |
| Unknown | 232       | 25.86%  |
| MBR     | 59        | 6.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 806       | 90.16%  |
| Yes       | 88        | 9.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 543       | 60.87%  |
| Yes       | 349       | 39.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 152       | 17.08%  |
| ASUSTek Computer    | 141       | 15.84%  |
| Hewlett-Packard     | 120       | 13.48%  |
| Dell                | 109       | 12.25%  |
| Gigabyte Technology | 67        | 7.53%   |
| MSI                 | 62        | 6.97%   |
| Acer                | 45        | 5.06%   |
| ASRock              | 29        | 3.26%   |
| Apple               | 18        | 2.02%   |
| HUAWEI              | 14        | 1.57%   |
| Samsung Electronics | 12        | 1.35%   |
| Toshiba             | 6         | 0.67%   |
| Supermicro          | 6         | 0.67%   |
| Intel               | 6         | 0.67%   |
| Google              | 6         | 0.67%   |
| Notebook            | 5         | 0.56%   |
| Fujitsu             | 5         | 0.56%   |
| Alienware           | 5         | 0.56%   |
| TUXEDO              | 4         | 0.45%   |
| Timi                | 4         | 0.45%   |
| Biostar             | 4         | 0.45%   |
| AZW                 | 4         | 0.45%   |
| Sony                | 3         | 0.34%   |
| Microsoft           | 3         | 0.34%   |
| Framework           | 3         | 0.34%   |
| Unknown             | 3         | 0.34%   |
| System76            | 2         | 0.22%   |
| Shuttle             | 2         | 0.22%   |
| Schenker            | 2         | 0.22%   |
| Razer               | 2         | 0.22%   |
| Positivo            | 2         | 0.22%   |
| Panasonic           | 2         | 0.22%   |
| HONOR               | 2         | 0.22%   |
| Haier               | 2         | 0.22%   |
| GPU Company         | 2         | 0.22%   |
| Carbon Systems      | 2         | 0.22%   |
| ZOTAC               | 1         | 0.11%   |
| VALE                | 1         | 0.11%   |
| TrekStor            | 1         | 0.11%   |
| Thomson             | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 13        | 1.46%   |
| Unknown                                | 7         | 0.79%   |
| HUAWEI HVY-WXX9                        | 5         | 0.56%   |
| ASUS ROG STRIX B550-F GAMING           | 5         | 0.56%   |
| MSI MS-7B79                            | 4         | 0.45%   |
| HP 255 G8 Notebook PC                  | 4         | 0.45%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 3         | 0.34%   |
| HP ProBook 6470b                       | 3         | 0.34%   |
| HP Pavilion g6                         | 3         | 0.34%   |
| HP OMEN Laptop 15-en0xxx               | 3         | 0.34%   |
| HP Laptop 15-ef2xxx                    | 3         | 0.34%   |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.34%   |
| Gigabyte B450M DS3H                    | 3         | 0.34%   |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.34%   |
| Dell XPS 15 9560                       | 3         | 0.34%   |
| Dell OptiPlex 7010                     | 3         | 0.34%   |
| Dell Latitude 5420                     | 3         | 0.34%   |
| Dell Latitude 3420                     | 3         | 0.34%   |
| Timi TM1701                            | 2         | 0.22%   |
| Supermicro SKAGIT09                    | 2         | 0.22%   |
| MSI MS-7C95                            | 2         | 0.22%   |
| MSI MS-7C56                            | 2         | 0.22%   |
| MSI MS-7B86                            | 2         | 0.22%   |
| MSI MS-7B84                            | 2         | 0.22%   |
| MSI MS-7A40                            | 2         | 0.22%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.22%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 2         | 0.22%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 2         | 0.22%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 2         | 0.22%   |
| HUAWEI CREM-WXX9                       | 2         | 0.22%   |
| HP ZBook 15 G6                         | 2         | 0.22%   |
| HP x2 Detachable 10-p0XX               | 2         | 0.22%   |
| HP ProBook 6570b                       | 2         | 0.22%   |
| HP ProBook 440 G8 Notebook PC          | 2         | 0.22%   |
| HP Pavilion Laptop 15-eh1xxx           | 2         | 0.22%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 2         | 0.22%   |
| HP Pavilion dv6                        | 2         | 0.22%   |
| HP Notebook                            | 2         | 0.22%   |
| HP Laptop 17-by3xxx                    | 2         | 0.22%   |
| HP Laptop 15-da0xxx                    | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 64        | 7.19%   |
| Lenovo IdeaPad     | 33        | 3.71%   |
| Dell Latitude      | 27        | 3.03%   |
| Acer Aspire        | 25        | 2.81%   |
| ASUS ROG           | 24        | 2.7%    |
| Dell Inspiron      | 23        | 2.58%   |
| HP Pavilion        | 19        | 2.13%   |
| HP ProBook         | 17        | 1.91%   |
| Dell XPS           | 17        | 1.91%   |
| ASUS PRIME         | 16        | 1.8%    |
| HP Laptop          | 14        | 1.57%   |
| HP EliteBook       | 14        | 1.57%   |
| Dell Precision     | 14        | 1.57%   |
| Dell OptiPlex      | 13        | 1.46%   |
| ASUS All           | 13        | 1.46%   |
| Lenovo ThinkCentre | 11        | 1.24%   |
| ASUS VivoBook      | 11        | 1.24%   |
| ASUS TUF           | 11        | 1.24%   |
| Lenovo Legion      | 9         | 1.01%   |
| Lenovo Yoga        | 8         | 0.9%    |
| Lenovo ThinkBook   | 8         | 0.9%    |
| HP ENVY            | 8         | 0.9%    |
| Acer Nitro         | 8         | 0.9%    |
| Unknown            | 7         | 0.79%   |
| Dell Vostro        | 6         | 0.67%   |
| Toshiba Satellite  | 5         | 0.56%   |
| HUAWEI HVY-WXX9    | 5         | 0.56%   |
| HP OMEN            | 5         | 0.56%   |
| HP 255             | 5         | 0.56%   |
| Gigabyte X570      | 5         | 0.56%   |
| MSI MS-7B79        | 4         | 0.45%   |
| Lenovo IdeaCentre  | 4         | 0.45%   |
| HP ZBook           | 4         | 0.45%   |
| HP Spectre         | 4         | 0.45%   |
| Gigabyte B450      | 4         | 0.45%   |
| ASUS ASUS          | 4         | 0.45%   |
| Acer Swift         | 4         | 0.45%   |
| Acer Predator      | 4         | 0.45%   |
| Microsoft Surface  | 3         | 0.34%   |
| HP ProDesk         | 3         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 148       | 16.63%  |
| 2020    | 126       | 14.16%  |
| 2019    | 85        | 9.55%   |
| 2022    | 75        | 8.43%   |
| 2018    | 72        | 8.09%   |
| 2012    | 62        | 6.97%   |
| 2017    | 53        | 5.96%   |
| 2014    | 49        | 5.51%   |
| 2016    | 45        | 5.06%   |
| 2013    | 45        | 5.06%   |
| 2015    | 39        | 4.38%   |
| 2011    | 35        | 3.93%   |
| 2010    | 16        | 1.8%    |
| 2008    | 12        | 1.35%   |
| 2009    | 10        | 1.12%   |
| 2023    | 9         | 1.01%   |
| 2007    | 8         | 0.9%    |
| Unknown | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 501       | 56.29%  |
| Desktop        | 315       | 35.39%  |
| Convertible    | 35        | 3.93%   |
| Mini pc        | 16        | 1.8%    |
| All in one     | 11        | 1.24%   |
| Tablet         | 7         | 0.79%   |
| Server         | 4         | 0.45%   |
| System on chip | 1         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 796       | 89.04%  |
| Enabled  | 98        | 10.96%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 883       | 99.21%  |
| Yes  | 7         | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 246       | 27.49%  |
| 4.01-8.0        | 190       | 21.23%  |
| 8.01-16.0       | 168       | 18.77%  |
| 32.01-64.0      | 139       | 15.53%  |
| 3.01-4.0        | 71        | 7.93%   |
| 64.01-256.0     | 47        | 5.25%   |
| 24.01-32.0      | 25        | 2.79%   |
| 1.01-2.0        | 4         | 0.45%   |
| 2.01-3.0        | 3         | 0.34%   |
| More than 256.0 | 2         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 246       | 26.28%  |
| 4.01-8.0   | 229       | 24.47%  |
| 3.01-4.0   | 191       | 20.41%  |
| 1.01-2.0   | 185       | 19.76%  |
| 8.01-16.0  | 61        | 6.52%   |
| 16.01-24.0 | 13        | 1.39%   |
| 0.51-1.0   | 7         | 0.75%   |
| 32.01-64.0 | 2         | 0.21%   |
| 24.01-32.0 | 1         | 0.11%   |
| 0.01-0.5   | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 477       | 53.12%  |
| 2      | 252       | 28.06%  |
| 3      | 85        | 9.47%   |
| 4      | 37        | 4.12%   |
| 5      | 21        | 2.34%   |
| 6      | 13        | 1.45%   |
| 7      | 7         | 0.78%   |
| 9      | 2         | 0.22%   |
| 0      | 2         | 0.22%   |
| 11     | 1         | 0.11%   |
| 8      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 657       | 73.65%  |
| Yes       | 235       | 26.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 722       | 81.12%  |
| No        | 168       | 18.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 735       | 82.4%   |
| No        | 157       | 17.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 642       | 71.73%  |
| No        | 253       | 28.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 199       | 22.31%  |
| Germany      | 93        | 10.43%  |
| Italy        | 65        | 7.29%   |
| France       | 58        | 6.5%    |
| Russia       | 52        | 5.83%   |
| Brazil       | 34        | 3.81%   |
| UK           | 33        | 3.7%    |
| Poland       | 28        | 3.14%   |
| Spain        | 22        | 2.47%   |
| India        | 18        | 2.02%   |
| Canada       | 18        | 2.02%   |
| Australia    | 18        | 2.02%   |
| Netherlands  | 16        | 1.79%   |
| Switzerland  | 13        | 1.46%   |
| Hungary      | 10        | 1.12%   |
| Argentina    | 10        | 1.12%   |
| Indonesia    | 9         | 1.01%   |
| Turkey       | 8         | 0.9%    |
| Slovenia     | 8         | 0.9%    |
| Portugal     | 8         | 0.9%    |
| Mexico       | 8         | 0.9%    |
| Czechia      | 8         | 0.9%    |
| Belgium      | 8         | 0.9%    |
| Sweden       | 7         | 0.78%   |
| Philippines  | 7         | 0.78%   |
| New Zealand  | 7         | 0.78%   |
| Finland      | 7         | 0.78%   |
| Bulgaria     | 7         | 0.78%   |
| Greece       | 6         | 0.67%   |
| Thailand     | 5         | 0.56%   |
| South Africa | 5         | 0.56%   |
| Singapore    | 5         | 0.56%   |
| Serbia       | 5         | 0.56%   |
| Austria      | 5         | 0.56%   |
| Romania      | 4         | 0.45%   |
| Estonia      | 4         | 0.45%   |
| Denmark      | 4         | 0.45%   |
| China        | 4         | 0.45%   |
| Ukraine      | 3         | 0.34%   |
| UAE          | 3         | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 17        | 1.85%   |
| Milan             | 15        | 1.63%   |
| Berlin            | 11        | 1.2%    |
| Paris             | 9         | 0.98%   |
| Warsaw            | 7         | 0.76%   |
| Munich            | 7         | 0.76%   |
| Castro Valley     | 7         | 0.76%   |
| Montreal          | 6         | 0.65%   |
| Madrid            | 6         | 0.65%   |
| Bengaluru         | 6         | 0.65%   |
| Wroclaw           | 5         | 0.54%   |
| Vladivostok       | 5         | 0.54%   |
| Sydney            | 5         | 0.54%   |
| St Petersburg     | 5         | 0.54%   |
| Singapore         | 5         | 0.54%   |
| Sao Paulo         | 5         | 0.54%   |
| Rio de Janeiro    | 5         | 0.54%   |
| Prague            | 5         | 0.54%   |
| Dallas            | 5         | 0.54%   |
| Auckland          | 5         | 0.54%   |
| Amsterdam         | 5         | 0.54%   |
| Washington        | 4         | 0.44%   |
| Vienna            | 4         | 0.44%   |
| Turin             | 4         | 0.44%   |
| New York          | 4         | 0.44%   |
| Jakarta           | 4         | 0.44%   |
| Jacksonville      | 4         | 0.44%   |
| Houston           | 4         | 0.44%   |
| Hamburg           | 4         | 0.44%   |
| Frankfurt am Main | 4         | 0.44%   |
| Belgrade          | 4         | 0.44%   |
| Zurich            | 3         | 0.33%   |
| Vilnius           | 3         | 0.33%   |
| Tallinn           | 3         | 0.33%   |
| Sofia             | 3         | 0.33%   |
| Seattle           | 3         | 0.33%   |
| Rome              | 3         | 0.33%   |
| Porto             | 3         | 0.33%   |
| London            | 3         | 0.33%   |
| Ljubljana         | 3         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 238       | 346    | 17.11%  |
| WDC                         | 186       | 250    | 13.37%  |
| Seagate                     | 149       | 242    | 10.71%  |
| Kingston                    | 92        | 106    | 6.61%   |
| Sandisk                     | 84        | 108    | 6.04%   |
| Toshiba                     | 82        | 106    | 5.9%    |
| Crucial                     | 49        | 57     | 3.52%   |
| Unknown                     | 47        | 62     | 3.38%   |
| SK hynix                    | 44        | 51     | 3.16%   |
| Intel                       | 38        | 47     | 2.73%   |
| Hitachi                     | 33        | 36     | 2.37%   |
| Micron Technology           | 30        | 32     | 2.16%   |
| HGST                        | 23        | 28     | 1.65%   |
| A-DATA Technology           | 22        | 23     | 1.58%   |
| KIOXIA                      | 19        | 20     | 1.37%   |
| China                       | 15        | 19     | 1.08%   |
| Phison                      | 13        | 13     | 0.93%   |
| PNY                         | 12        | 16     | 0.86%   |
| Phison Electronics          | 11        | 11     | 0.79%   |
| Apple                       | 11        | 12     | 0.79%   |
| Patriot                     | 10        | 13     | 0.72%   |
| SPCC                        | 9         | 9      | 0.65%   |
| Micron/Crucial Technology   | 8         | 11     | 0.58%   |
| Unknown                     | 8         | 8      | 0.58%   |
| Silicon Motion              | 6         | 6      | 0.43%   |
| Maxtor                      | 6         | 7      | 0.43%   |
| SSSTC                       | 5         | 5      | 0.36%   |
| LITEON                      | 5         | 5      | 0.36%   |
| Lexar                       | 5         | 5      | 0.36%   |
| Verbatim                    | 4         | 4      | 0.29%   |
| SABRENT                     | 4         | 6      | 0.29%   |
| Realtek Semiconductor       | 4         | 4      | 0.29%   |
| OCZ                         | 4         | 4      | 0.29%   |
| Netac                       | 4         | 4      | 0.29%   |
| Kingston Technology Company | 4         | 5      | 0.29%   |
| JMicron Technology          | 4         | 4      | 0.29%   |
| Intenso                     | 4         | 5      | 0.29%   |
| GOODRAM                     | 4         | 4      | 0.29%   |
| Emtec                       | 4         | 4      | 0.29%   |
| Corsair                     | 4         | 5      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 18        | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 14        | 0.91%   |
| Samsung SSD 860 EVO 500GB                           | 13        | 0.84%   |
| Kingston SA400S37480G 480GB SSD                     | 13        | 0.84%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB                        | 9         | 0.58%   |
| Toshiba MQ01ABD100 1TB                              | 8         | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8         | 0.52%   |
| Samsung SSD 980 PRO 1TB                             | 8         | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                      | 8         | 0.52%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.52%   |
| Unknown                                             | 8         | 0.52%   |
| Unknown MMC Card  64GB                              | 7         | 0.45%   |
| Toshiba DT01ACA100 1TB                              | 7         | 0.45%   |
| Seagate Expansion 1TB                               | 7         | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                          | 7         | 0.45%   |
| Kingston SA2000M81000G 1TB                          | 7         | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 7         | 0.45%   |
| Unknown MMC Card  32GB                              | 6         | 0.39%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 0.39%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 6         | 0.39%   |
| SanDisk NVMe SSD Drive 500GB                        | 6         | 0.39%   |
| Samsung SSD 970 EVO Plus 2TB                        | 6         | 0.39%   |
| Samsung SSD 970 EVO Plus 250GB                      | 6         | 0.39%   |
| Samsung SSD 870 EVO 1TB                             | 6         | 0.39%   |
| Samsung SSD 860 EVO 1TB                             | 6         | 0.39%   |
| Crucial CT500MX500SSD1 500GB                        | 6         | 0.39%   |
| Crucial CT1000MX500SSD1 1TB                         | 6         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 5         | 0.32%   |
| Seagate ST2000LM007-1R8174 2TB                      | 5         | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5         | 0.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 5         | 0.32%   |
| Samsung SSD 980 500GB                               | 5         | 0.32%   |
| Samsung SSD 980 1TB                                 | 5         | 0.32%   |
| Samsung SSD 870 QVO 1TB                             | 5         | 0.32%   |
| Samsung SSD 860 QVO 1TB                             | 5         | 0.32%   |
| Samsung SSD 840 EVO 250GB                           | 5         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 143       | 228    | 34.71%  |
| WDC                 | 126       | 162    | 30.58%  |
| Toshiba             | 50        | 63     | 12.14%  |
| Hitachi             | 33        | 36     | 8.01%   |
| HGST                | 23        | 28     | 5.58%   |
| Samsung Electronics | 17        | 21     | 4.13%   |
| Maxtor              | 5         | 6      | 1.21%   |
| Unknown             | 3         | 3      | 0.73%   |
| Apple               | 3         | 3      | 0.73%   |
| USB3.0              | 2         | 2      | 0.49%   |
| SAGE                | 1         | 1      | 0.24%   |
| KESU                | 1         | 1      | 0.24%   |
| JMicron Technology  | 1         | 1      | 0.24%   |
| IET                 | 1         | 1      | 0.24%   |
| HPE                 | 1         | 6      | 0.24%   |
| HGST HTS            | 1         | 1      | 0.24%   |
| ASMT                | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 116       | 166    | 25.22%  |
| Kingston            | 62        | 68     | 13.48%  |
| SanDisk             | 41        | 49     | 8.91%   |
| Crucial             | 38        | 44     | 8.26%   |
| WDC                 | 28        | 40     | 6.09%   |
| A-DATA Technology   | 18        | 19     | 3.91%   |
| China               | 14        | 18     | 3.04%   |
| Intel               | 11        | 15     | 2.39%   |
| PNY                 | 10        | 14     | 2.17%   |
| Patriot             | 10        | 13     | 2.17%   |
| Toshiba             | 7         | 10     | 1.52%   |
| Micron Technology   | 7         | 7      | 1.52%   |
| SPCC                | 6         | 6      | 1.3%    |
| LITEON              | 5         | 5      | 1.09%   |
| Verbatim            | 4         | 4      | 0.87%   |
| OCZ                 | 4         | 4      | 0.87%   |
| Lexar               | 4         | 4      | 0.87%   |
| GOODRAM             | 4         | 4      | 0.87%   |
| Apple               | 4         | 4      | 0.87%   |
| Team                | 3         | 3      | 0.65%   |
| SK hynix            | 3         | 3      | 0.65%   |
| Mushkin             | 3         | 4      | 0.65%   |
| LITEONIT            | 3         | 3      | 0.65%   |
| Intenso             | 3         | 3      | 0.65%   |
| Hewlett-Packard     | 3         | 3      | 0.65%   |
| Emtec               | 3         | 3      | 0.65%   |
| Transcend           | 2         | 2      | 0.43%   |
| Smart               | 2         | 2      | 0.43%   |
| Plextor             | 2         | 2      | 0.43%   |
| Netac               | 2         | 2      | 0.43%   |
| KODAK               | 2         | 2      | 0.43%   |
| Apacer              | 2         | 2      | 0.43%   |
| ADATA SU            | 2         | 2      | 0.43%   |
| Unknown             | 2         | 2      | 0.43%   |
| VISIPRO             | 1         | 2      | 0.22%   |
| ValueTech           | 1         | 1      | 0.22%   |
| tecmiyo             | 1         | 3      | 0.22%   |
| T-FORCE             | 1         | 1      | 0.22%   |
| Smartbuy            | 1         | 1      | 0.22%   |
| ShiJi               | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 451       | 587    | 36.14%  |
| SSD     | 395       | 567    | 31.65%  |
| HDD     | 334       | 564    | 26.76%  |
| MMC     | 45        | 54     | 3.61%   |
| Unknown | 23        | 32     | 1.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 548       | 1074   | 49.82%  |
| NVMe | 446       | 578    | 40.55%  |
| SAS  | 61        | 98     | 5.55%   |
| MMC  | 45        | 54     | 4.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 387       | 591    | 50.65%  |
| 0.51-1.0   | 218       | 300    | 28.53%  |
| 1.01-2.0   | 83        | 113    | 10.86%  |
| 3.01-4.0   | 38        | 68     | 4.97%   |
| 4.01-10.0  | 23        | 38     | 3.01%   |
| 2.01-3.0   | 11        | 13     | 1.44%   |
| 10.01-20.0 | 4         | 8      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 211       | 23.21%  |
| 101-250        | 195       | 21.45%  |
| 501-1000       | 163       | 17.93%  |
| 1001-2000      | 128       | 14.08%  |
| More than 3000 | 75        | 8.25%   |
| 2001-3000      | 58        | 6.38%   |
| 51-100         | 35        | 3.85%   |
| 1-20           | 31        | 3.41%   |
| 21-50          | 11        | 1.21%   |
| Unknown        | 2         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 186       | 20.2%   |
| 101-250        | 170       | 18.46%  |
| 51-100         | 123       | 13.36%  |
| 251-500        | 121       | 13.14%  |
| 21-50          | 118       | 12.81%  |
| 501-1000       | 95        | 10.31%  |
| 1001-2000      | 57        | 6.19%   |
| More than 3000 | 33        | 3.58%   |
| 2001-3000      | 16        | 1.74%   |
| Unknown        | 2         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB               | 2         | 2      | 2.13%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 2.13%   |
| SK hynix BC711 HFM256GD3JX013N 256GB | 2         | 2      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 2.13%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 2      | 2.13%   |
| Samsung Electronics SSD 870 EVO 1TB  | 2         | 2      | 2.13%   |
| Kingston SUV400S37240G 240GB SSD     | 2         | 2      | 2.13%   |
| Hitachi HDS721010CLA630 1TB          | 2         | 2      | 2.13%   |
| HGST HTS721010A9E630 1TB             | 2         | 2      | 2.13%   |
| Crucial CT525MX300SSD1 528GB         | 2         | 2      | 2.13%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 1.06%   |
| WDC WD5000AZRX-00A3KB0 500GB         | 1         | 1      | 1.06%   |
| WDC WD5000AVVS-63M8B0 500GB          | 1         | 1      | 1.06%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 1.06%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 2      | 1.06%   |
| WDC WD20EADS-14R6B0 2TB              | 1         | 1      | 1.06%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1      | 1.06%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 1      | 1.06%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 1.06%   |
| WDC WD10EURX-73C57Y0 1TB             | 1         | 1      | 1.06%   |
| WDC WD10EARS-00MVWB0 1TB             | 1         | 1      | 1.06%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 1      | 1.06%   |
| WDC WD10EACS-65D6B0 1TB              | 1         | 1      | 1.06%   |
| VISIPRO SSD 256GB                    | 1         | 2      | 1.06%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 1         | 1      | 1.06%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1      | 1.06%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.06%   |
| tecmiyo SATA SSD 128GB               | 1         | 3      | 1.06%   |
| T-FORCE SSD 512GB                    | 1         | 1      | 1.06%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 1.06%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 1.06%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 1.06%   |
| Seagate ST4000VN008-2DR166 4TB       | 1         | 2      | 1.06%   |
| Seagate ST3500630AS 500GB            | 1         | 1      | 1.06%   |
| Seagate ST3250310AS 250GB            | 1         | 1      | 1.06%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 1.06%   |
| Seagate ST3160827AS 160GB            | 1         | 1      | 1.06%   |
| Seagate ST3160023A 160GB             | 1         | 1      | 1.06%   |
| Seagate ST31500341AS 1TB             | 1         | 1      | 1.06%   |
| Seagate ST31000524AS 1TB             | 1         | 2      | 1.06%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 22     | 19.78%  |
| WDC                 | 12        | 14     | 13.19%  |
| Samsung Electronics | 9         | 11     | 9.89%   |
| Hitachi             | 9         | 9      | 9.89%   |
| Crucial             | 7         | 7      | 7.69%   |
| Toshiba             | 5         | 5      | 5.49%   |
| SK hynix            | 4         | 4      | 4.4%    |
| HGST                | 4         | 4      | 4.4%    |
| SanDisk             | 3         | 3      | 3.3%    |
| Kingston            | 3         | 3      | 3.3%    |
| Micron Technology   | 2         | 2      | 2.2%    |
| Maxtor              | 2         | 2      | 2.2%    |
| Intel               | 2         | 5      | 2.2%    |
| A-DATA Technology   | 2         | 2      | 2.2%    |
| VISIPRO             | 1         | 2      | 1.1%    |
| tecmiyo             | 1         | 3      | 1.1%    |
| T-FORCE             | 1         | 1      | 1.1%    |
| R580                | 1         | 1      | 1.1%    |
| Phison Electronics  | 1         | 1      | 1.1%    |
| OCZ                 | 1         | 1      | 1.1%    |
| LITEONIT            | 1         | 1      | 1.1%    |
| Intenso             | 1         | 1      | 1.1%    |
| BAITITON            | 1         | 1      | 1.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 22     | 35.29%  |
| WDC                 | 11        | 13     | 21.57%  |
| Hitachi             | 9         | 9      | 17.65%  |
| Toshiba             | 4         | 4      | 7.84%   |
| HGST                | 4         | 4      | 7.84%   |
| Samsung Electronics | 3         | 5      | 5.88%   |
| Maxtor              | 2         | 2      | 3.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 59     | 55.17%  |
| SSD  | 31        | 38     | 35.63%  |
| NVMe | 8         | 8      | 9.2%    |

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
| Works    | 502       | 876    | 49.95%  |
| Detected | 417       | 821    | 41.49%  |
| Malfunc  | 85        | 105    | 8.46%   |
| Failed   | 1         | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 526       | 42.63%  |
| AMD                            | 198       | 16.05%  |
| Samsung Electronics            | 127       | 10.29%  |
| Sandisk                        | 88        | 7.13%   |
| SK hynix                       | 41        | 3.32%   |
| Kingston Technology Company    | 36        | 2.92%   |
| Phison Electronics             | 31        | 2.51%   |
| Toshiba America Info Systems   | 27        | 2.19%   |
| Micron Technology              | 23        | 1.86%   |
| ASMedia Technology             | 22        | 1.78%   |
| Micron/Crucial Technology      | 20        | 1.62%   |
| KIOXIA                         | 18        | 1.46%   |
| Silicon Motion                 | 8         | 0.65%   |
| JMicron Technology             | 8         | 0.65%   |
| Solid State Storage Technology | 7         | 0.57%   |
| Realtek Semiconductor          | 7         | 0.57%   |
| Marvell Technology Group       | 6         | 0.49%   |
| ADATA Technology               | 6         | 0.49%   |
| Union Memory (Shenzhen)        | 5         | 0.41%   |
| LSI Logic / Symbios Logic      | 5         | 0.41%   |
| Seagate Technology             | 4         | 0.32%   |
| Apple                          | 4         | 0.32%   |
| Nvidia                         | 3         | 0.24%   |
| Netac Technology               | 2         | 0.16%   |
| Broadcom / LSI                 | 2         | 0.16%   |
| Zhaoxin                        | 1         | 0.08%   |
| Yangtze Memory Technologies    | 1         | 0.08%   |
| VIA Technologies               | 1         | 0.08%   |
| Silicon Image                  | 1         | 0.08%   |
| Shenzhen Longsys Electronics   | 1         | 0.08%   |
| OCZ Technology Group           | 1         | 0.08%   |
| O2 Micro                       | 1         | 0.08%   |
| INNOGRIT                       | 1         | 0.08%   |
| Hewlett-Packard                | 1         | 0.08%   |
| Unknown                        | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 146       | 10.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 60        | 4.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 51        | 3.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 45        | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 43        | 3.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 41        | 2.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 32        | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 32        | 2.3%    |
| Samsung NVMe SSD Controller 980                                                | 28        | 2.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 26        | 1.87%   |
| AMD 500 Series Chipset SATA Controller                                         | 22        | 1.58%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 21        | 1.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 21        | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 21        | 1.51%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 20        | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 19        | 1.36%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 18        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 17        | 1.22%   |
| SanDisk Non-Volatile memory controller                                         | 15        | 1.08%   |
| Micron NVMe Storage Controller                                                 | 15        | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 15        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 1.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 15        | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 14        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 1.01%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 13        | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 13        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 0.86%   |
| Intel SSD 660P Series                                                          | 12        | 0.86%   |
| Intel SATA Controller [RAID mode]                                              | 12        | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 0.86%   |
| Phison E12 NVMe Controller                                                     | 11        | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 0.72%   |
| Kingston Company A2000 NVMe SSD                                                | 9         | 0.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 627       | 51.06%  |
| NVMe | 444       | 36.16%  |
| RAID | 98        | 7.98%   |
| IDE  | 53        | 4.32%   |
| SAS  | 4         | 0.33%   |
| SCSI | 2         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 623       | 70%     |
| AMD          | 265       | 29.78%  |
| CentaurHauls | 1         | 0.11%   |
| ARM          | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 19        | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 19        | 2.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 17        | 1.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 1.69%   |
| Intel 12th Gen Core i7-12700H           | 13        | 1.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 1.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 12        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 11        | 1.24%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 11        | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 8         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 8         | 0.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 8         | 0.9%    |
| Intel 12th Gen Core i7-1260P            | 8         | 0.9%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 8         | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 7         | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 0.79%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 7         | 0.79%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 7         | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 6         | 0.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 0.67%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 6         | 0.67%   |
| Intel 12th Gen Core i7-1255U            | 6         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 5         | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 5         | 0.56%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 5         | 0.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 5         | 0.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 5         | 0.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 5         | 0.56%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 5         | 0.56%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 5         | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 5         | 0.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 5         | 0.56%   |
| AMD Ryzen 5 3600 6-Core Processor       | 5         | 0.56%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 5         | 0.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 4         | 0.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 4         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 189       | 21.24%  |
| Intel Core i5           | 158       | 17.75%  |
| Other                   | 129       | 14.49%  |
| AMD Ryzen 7             | 77        | 8.65%   |
| AMD Ryzen 5             | 75        | 8.43%   |
| Intel Core i3           | 42        | 4.72%   |
| Intel Celeron           | 30        | 3.37%   |
| AMD Ryzen 9             | 28        | 3.15%   |
| Intel Xeon              | 21        | 2.36%   |
| Intel Pentium           | 16        | 1.8%    |
| Intel Core 2 Duo        | 14        | 1.57%   |
| AMD Ryzen 3             | 14        | 1.57%   |
| AMD Ryzen 7 PRO         | 11        | 1.24%   |
| AMD FX                  | 10        | 1.12%   |
| Intel Core i9           | 9         | 1.01%   |
| AMD A6                  | 8         | 0.9%    |
| Intel Pentium Silver    | 7         | 0.79%   |
| AMD A8                  | 6         | 0.67%   |
| AMD A10                 | 4         | 0.45%   |
| Intel Core 2 Quad       | 3         | 0.34%   |
| AMD Ryzen Threadripper  | 3         | 0.34%   |
| AMD Ryzen 5 PRO         | 3         | 0.34%   |
| AMD Phenom II X4        | 3         | 0.34%   |
| AMD Athlon              | 3         | 0.34%   |
| Intel Pentium Gold      | 2         | 0.22%   |
| Intel Core m3           | 2         | 0.22%   |
| Intel Atom              | 2         | 0.22%   |
| AMD PRO A10             | 2         | 0.22%   |
| AMD Phenom II X2        | 2         | 0.22%   |
| AMD Opteron             | 2         | 0.22%   |
| AMD E                   | 2         | 0.22%   |
| AMD Athlon 64 X2        | 2         | 0.22%   |
| AMD A4                  | 2         | 0.22%   |
| Intel Core M            | 1         | 0.11%   |
| Intel Core 2            | 1         | 0.11%   |
| Intel Celeron Dual-Core | 1         | 0.11%   |
| AMD Sempron             | 1         | 0.11%   |
| AMD Phenom II X6        | 1         | 0.11%   |
| AMD Phenom              | 1         | 0.11%   |
| AMD E1                  | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 324       | 36.4%   |
| 2       | 232       | 26.07%  |
| 6       | 134       | 15.06%  |
| 8       | 119       | 13.37%  |
| 12      | 25        | 2.81%   |
| 14      | 18        | 2.02%   |
| 16      | 14        | 1.57%   |
| 10      | 12        | 1.35%   |
| 1       | 5         | 0.56%   |
| 24      | 3         | 0.34%   |
| 36      | 1         | 0.11%   |
| 5       | 1         | 0.11%   |
| 3       | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 884       | 99.33%  |
| 2       | 5         | 0.56%   |
| Unknown | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 715       | 80.16%  |
| 1       | 176       | 19.73%  |
| Unknown | 1         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 890       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 341       | 37.68%  |
| 0x806c1    | 36        | 3.98%   |
| 0x306a9    | 31        | 3.43%   |
| 0x0a50000c | 31        | 3.43%   |
| 0x906a3    | 28        | 3.09%   |
| 0x306c3    | 25        | 2.76%   |
| 0x806ea    | 23        | 2.54%   |
| 0x906ea    | 21        | 2.32%   |
| 0x806ec    | 17        | 1.88%   |
| 0x08608103 | 16        | 1.77%   |
| 0x08600106 | 16        | 1.77%   |
| 0x206a7    | 14        | 1.55%   |
| 0x806e9    | 13        | 1.44%   |
| 0x506e3    | 13        | 1.44%   |
| 0x08701021 | 13        | 1.44%   |
| 0x906e9    | 12        | 1.33%   |
| 0x406e3    | 11        | 1.22%   |
| 0x906ed    | 8         | 0.88%   |
| 0x906a4    | 8         | 0.88%   |
| 0x0800820d | 8         | 0.88%   |
| 0xa0653    | 7         | 0.77%   |
| 0xa0652    | 7         | 0.77%   |
| 0x806c2    | 7         | 0.77%   |
| 0x706a8    | 7         | 0.77%   |
| 0x1067a    | 7         | 0.77%   |
| 0x08108109 | 7         | 0.77%   |
| 0x806d1    | 6         | 0.66%   |
| 0x706a1    | 6         | 0.66%   |
| 0x40651    | 6         | 0.66%   |
| 0x0a50000d | 6         | 0.66%   |
| 0x08608102 | 6         | 0.66%   |
| 0xa0655    | 5         | 0.55%   |
| 0x406f1    | 5         | 0.55%   |
| 0x40661    | 5         | 0.55%   |
| 0x0a201205 | 5         | 0.55%   |
| 0x010000c8 | 5         | 0.55%   |
| 0x90672    | 4         | 0.44%   |
| 0x706e5    | 4         | 0.44%   |
| 0x506c9    | 4         | 0.44%   |
| 0x306d4    | 4         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 148       | 16.59%  |
| Haswell          | 76        | 8.52%   |
| Zen 3            | 75        | 8.41%   |
| IvyBridge        | 72        | 8.07%   |
| TigerLake        | 61        | 6.84%   |
| Unknown          | 59        | 6.61%   |
| Zen 2            | 46        | 5.16%   |
| Alderlake Hybrid | 41        | 4.6%    |
| Skylake          | 39        | 4.37%   |
| Zen+             | 36        | 4.04%   |
| SandyBridge      | 33        | 3.7%    |
| CometLake        | 28        | 3.14%   |
| Goldmont plus    | 23        | 2.58%   |
| Zen              | 19        | 2.13%   |
| IceLake          | 17        | 1.91%   |
| Piledriver       | 16        | 1.79%   |
| Broadwell        | 15        | 1.68%   |
| Penryn           | 14        | 1.57%   |
| Excavator        | 11        | 1.23%   |
| K10              | 10        | 1.12%   |
| Westmere         | 9         | 1.01%   |
| Silvermont       | 9         | 1.01%   |
| Nehalem          | 8         | 0.9%    |
| Core             | 7         | 0.78%   |
| Goldmont         | 6         | 0.67%   |
| K10 Llano        | 4         | 0.45%   |
| Puma             | 3         | 0.34%   |
| Steamroller      | 2         | 0.22%   |
| K8 Hammer        | 2         | 0.22%   |
| Bobcat           | 2         | 0.22%   |
| K8 & K10 hybrid  | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 481       | 43.85%  |
| Nvidia                     | 333       | 30.36%  |
| AMD                        | 275       | 25.07%  |
| Matrox Electronics Systems | 5         | 0.46%   |
| ASPEED Technology          | 2         | 0.18%   |
| Zhaoxin                    | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 53        | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 42        | 3.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 38        | 3.41%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 27        | 2.42%   |
| AMD Renoir                                                                            | 26        | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 25        | 2.24%   |
| AMD Lucienne                                                                          | 25        | 2.24%   |
| Intel UHD Graphics 620                                                                | 24        | 2.15%   |
| Intel HD Graphics 620                                                                 | 24        | 2.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 21        | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 20        | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 20        | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 18        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 17        | 1.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 16        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 16        | 1.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 15        | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 15        | 1.35%   |
| Intel HD Graphics 630                                                                 | 13        | 1.17%   |
| Intel HD Graphics 530                                                                 | 12        | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 11        | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 10        | 0.9%    |
| AMD Rembrandt [Radeon 680M]                                                           | 10        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 0.81%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 9         | 0.81%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 9         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 8         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 8         | 0.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 8         | 0.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                | 8         | 0.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 8         | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 7         | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 7         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 7         | 0.63%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 7         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 7         | 0.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 0.63%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 7         | 0.63%   |
| Intel HD Graphics 5500                                                                | 7         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 307       | 34.42%  |
| 1 x AMD                  | 202       | 22.65%  |
| 1 x Nvidia               | 174       | 19.51%  |
| Intel + Nvidia           | 125       | 14.01%  |
| AMD + Nvidia             | 29        | 3.25%   |
| Intel + AMD              | 28        | 3.14%   |
| 2 x AMD                  | 12        | 1.35%   |
| Other                    | 3         | 0.34%   |
| 2 x Nvidia               | 3         | 0.34%   |
| Nvidia + ASPEED          | 2         | 0.22%   |
| 1 x Matrox               | 2         | 0.22%   |
| AMD + Matrox             | 2         | 0.22%   |
| 1 x Zhaoxin              | 1         | 0.11%   |
| Nvidia + Matrox          | 1         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 631       | 70.58%  |
| Proprietary | 242       | 27.07%  |
| Unknown     | 21        | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 559       | 62.04%  |
| 0.01-0.5   | 82        | 9.1%    |
| 1.01-2.0   | 79        | 8.77%   |
| 3.01-4.0   | 51        | 5.66%   |
| 0.51-1.0   | 44        | 4.88%   |
| 7.01-8.0   | 41        | 4.55%   |
| 5.01-6.0   | 26        | 2.89%   |
| 8.01-16.0  | 14        | 1.55%   |
| 16.01-24.0 | 3         | 0.33%   |
| 4.01-5.0   | 1         | 0.11%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 136       | 12.93%  |
| BOE                     | 113       | 10.74%  |
| AU Optronics            | 103       | 9.79%   |
| Chimei Innolux          | 100       | 9.51%   |
| LG Display              | 81        | 7.7%    |
| Dell                    | 67        | 6.37%   |
| Goldstar                | 62        | 5.89%   |
| Hewlett-Packard         | 47        | 4.47%   |
| Acer                    | 32        | 3.04%   |
| Philips                 | 31        | 2.95%   |
| BenQ                    | 27        | 2.57%   |
| Sharp                   | 22        | 2.09%   |
| AOC                     | 19        | 1.81%   |
| Ancor Communications    | 19        | 1.81%   |
| ASUSTek Computer        | 16        | 1.52%   |
| InfoVision              | 13        | 1.24%   |
| Apple                   | 13        | 1.24%   |
| Iiyama                  | 12        | 1.14%   |
| Lenovo                  | 11        | 1.05%   |
| CSO                     | 10        | 0.95%   |
| Sony                    | 8         | 0.76%   |
| Chi Mei Optoelectronics | 7         | 0.67%   |
| ViewSonic               | 6         | 0.57%   |
| NEC Computers           | 5         | 0.48%   |
| Vizio                   | 4         | 0.38%   |
| Eizo                    | 4         | 0.38%   |
| Sceptre Tech            | 3         | 0.29%   |
| PANDA                   | 3         | 0.29%   |
| Panasonic               | 3         | 0.29%   |
| MSI                     | 3         | 0.29%   |
| LG Electronics          | 3         | 0.29%   |
| Idek Iiyama             | 3         | 0.29%   |
| HKC                     | 3         | 0.29%   |
| Gigabyte Technology     | 3         | 0.29%   |
| Fujitsu Siemens         | 3         | 0.29%   |
| Xiaomi                  | 2         | 0.19%   |
| Vestel Elektronik       | 2         | 0.19%   |
| SLD                     | 2         | 0.19%   |
| RTK                     | 2         | 0.19%   |
| Planar                  | 2         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4         | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.37%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 4         | 0.37%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.28%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 3         | 0.28%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 3         | 0.28%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.28%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 3         | 0.28%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3         | 0.28%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 3         | 0.28%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.28%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch        | 3         | 0.28%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch        | 3         | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.28%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3         | 0.28%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 2         | 0.18%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch  | 2         | 0.18%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2         | 0.18%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 2         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 500       | 51.12%  |
| 1366x768 (WXGA)    | 121       | 12.37%  |
| 3840x2160 (4K)     | 75        | 7.67%   |
| 2560x1440 (QHD)    | 52        | 5.32%   |
| 1920x1200 (WUXGA)  | 44        | 4.5%    |
| 1680x1050 (WSXGA+) | 28        | 2.86%   |
| 1600x900 (HD+)     | 24        | 2.45%   |
| 1280x1024 (SXGA)   | 17        | 1.74%   |
| 3440x1440          | 16        | 1.64%   |
| 2560x1600          | 15        | 1.53%   |
| 2880x1800          | 13        | 1.33%   |
| 2560x1080          | 11        | 1.12%   |
| 1440x900 (WXGA+)   | 6         | 0.61%   |
| 3840x1080          | 5         | 0.51%   |
| 1280x800 (WXGA)    | 5         | 0.51%   |
| Unknown            | 5         | 0.51%   |
| 1360x768           | 4         | 0.41%   |
| 2256x1504          | 3         | 0.31%   |
| 2240x1400          | 3         | 0.31%   |
| 2160x1440          | 3         | 0.31%   |
| 1024x768 (XGA)     | 3         | 0.31%   |
| 3840x2400          | 2         | 0.2%    |
| 2520x1680          | 2         | 0.2%    |
| 1920x540           | 2         | 0.2%    |
| 1280x720 (HD)      | 2         | 0.2%    |
| 6160x1440          | 1         | 0.1%    |
| 5760x2160          | 1         | 0.1%    |
| 5760x1080          | 1         | 0.1%    |
| 480x1920           | 1         | 0.1%    |
| 4800x1080          | 1         | 0.1%    |
| 3840x1600          | 1         | 0.1%    |
| 3840x1200          | 1         | 0.1%    |
| 3600x1200          | 1         | 0.1%    |
| 3072x1920          | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2736x1824          | 1         | 0.1%    |
| 2496x1664          | 1         | 0.1%    |
| 2288x1287          | 1         | 0.1%    |
| 2160x1350          | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 247       | 23.55%  |
| 24      | 97        | 9.25%   |
| 14      | 97        | 9.25%   |
| 27      | 87        | 8.29%   |
| 13      | 84        | 8.01%   |
| 23      | 76        | 7.24%   |
| 21      | 63        | 6.01%   |
| 17      | 52        | 4.96%   |
| 31      | 29        | 2.76%   |
| 34      | 26        | 2.48%   |
| 16      | 26        | 2.48%   |
| Unknown | 21        | 2%      |
| 22      | 17        | 1.62%   |
| 19      | 15        | 1.43%   |
| 32      | 10        | 0.95%   |
| 18      | 10        | 0.95%   |
| 12      | 10        | 0.95%   |
| 11      | 9         | 0.86%   |
| 72      | 8         | 0.76%   |
| 54      | 7         | 0.67%   |
| 40      | 6         | 0.57%   |
| 25      | 6         | 0.57%   |
| 20      | 6         | 0.57%   |
| 84      | 4         | 0.38%   |
| 65      | 3         | 0.29%   |
| 49      | 3         | 0.29%   |
| 46      | 3         | 0.29%   |
| 36      | 3         | 0.29%   |
| 28      | 3         | 0.29%   |
| 69      | 2         | 0.19%   |
| 60      | 2         | 0.19%   |
| 48      | 2         | 0.19%   |
| 42      | 2         | 0.19%   |
| 26      | 2         | 0.19%   |
| 10      | 2         | 0.19%   |
| 142     | 1         | 0.1%    |
| 78      | 1         | 0.1%    |
| 63      | 1         | 0.1%    |
| 55      | 1         | 0.1%    |
| 47      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 394       | 38.51%  |
| 501-600        | 231       | 22.58%  |
| 401-500        | 102       | 9.97%   |
| 351-400        | 71        | 6.94%   |
| 201-300        | 70        | 6.84%   |
| 601-700        | 45        | 4.4%    |
| 701-800        | 39        | 3.81%   |
| 1001-1500      | 23        | 2.25%   |
| Unknown        | 21        | 2.05%   |
| 1501-2000      | 15        | 1.47%   |
| 801-900        | 8         | 0.78%   |
| 901-1000       | 3         | 0.29%   |
| More than 2000 | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 706       | 77.92%  |
| 16/10   | 118       | 13.02%  |
| 21/9    | 28        | 3.09%   |
| Unknown | 17        | 1.88%   |
| 5/4     | 14        | 1.55%   |
| 3/2     | 14        | 1.55%   |
| 32/9    | 4         | 0.44%   |
| 4/3     | 3         | 0.33%   |
| 1.00    | 1         | 0.11%   |
| 0.25    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 255       | 24.83%  |
| 201-250        | 191       | 18.6%   |
| 81-90          | 144       | 14.02%  |
| 301-350        | 89        | 8.67%   |
| 351-500        | 65        | 6.33%   |
| 121-130        | 45        | 4.38%   |
| 71-80          | 38        | 3.7%    |
| 151-200        | 38        | 3.7%    |
| 251-300        | 34        | 3.31%   |
| More than 1000 | 31        | 3.02%   |
| 501-1000       | 22        | 2.14%   |
| Unknown        | 21        | 2.04%   |
| 111-120        | 17        | 1.66%   |
| 141-150        | 14        | 1.36%   |
| 61-70          | 9         | 0.88%   |
| 51-60          | 9         | 0.88%   |
| 41-50          | 2         | 0.19%   |
| 131-140        | 2         | 0.19%   |
| 91-100         | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 322       | 32.53%  |
| 51-100        | 295       | 29.8%   |
| 101-120       | 197       | 19.9%   |
| 161-240       | 94        | 9.49%   |
| 1-50          | 33        | 3.33%   |
| More than 240 | 28        | 2.83%   |
| Unknown       | 21        | 2.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 656       | 72.81%  |
| 2     | 188       | 20.87%  |
| 3     | 27        | 3%      |
| 0     | 23        | 2.55%   |
| 4     | 7         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 501       | 36.84%  |
| Intel                             | 474       | 34.85%  |
| Qualcomm Atheros                  | 115       | 8.46%   |
| Broadcom                          | 57        | 4.19%   |
| MediaTek                          | 51        | 3.75%   |
| Ralink Technology                 | 18        | 1.32%   |
| TP-Link                           | 14        | 1.03%   |
| Samsung Electronics               | 11        | 0.81%   |
| ASIX Electronics                  | 11        | 0.81%   |
| Ralink                            | 9         | 0.66%   |
| Aquantia                          | 9         | 0.66%   |
| Sierra Wireless                   | 6         | 0.44%   |
| Lenovo                            | 6         | 0.44%   |
| Huawei Technologies               | 6         | 0.44%   |
| Broadcom Limited                  | 6         | 0.44%   |
| Marvell Technology Group          | 5         | 0.37%   |
| Xiaomi                            | 4         | 0.29%   |
| Qualcomm                          | 4         | 0.29%   |
| Qualcomm Atheros Communications   | 3         | 0.22%   |
| Nvidia                            | 3         | 0.22%   |
| DisplayLink                       | 3         | 0.22%   |
| Belkin Components                 | 3         | 0.22%   |
| ASUSTek Computer                  | 3         | 0.22%   |
| VIA Technologies                  | 2         | 0.15%   |
| NetGear                           | 2         | 0.15%   |
| Hewlett-Packard                   | 2         | 0.15%   |
| Google                            | 2         | 0.15%   |
| Ericsson Business Mobile Networks | 2         | 0.15%   |
| Edimax Technology                 | 2         | 0.15%   |
| Dell                              | 2         | 0.15%   |
| D-Link System                     | 2         | 0.15%   |
| D-Link                            | 2         | 0.15%   |
| Apple                             | 2         | 0.15%   |
| ZyXEL Communications              | 1         | 0.07%   |
| Wilocity                          | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Shenzhen Goodix Technology        | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| NIIMBOT                           | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 321       | 20.05%  |
| Intel Wi-Fi 6 AX200                                               | 56        | 3.5%    |
| Intel Wi-Fi 6 AX201                                               | 45        | 2.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 37        | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 36        | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 33        | 2.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 33        | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 1.81%   |
| Intel Wireless 8265 / 8275                                        | 23        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 1.37%   |
| Intel I211 Gigabit Network Connection                             | 22        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 1.31%   |
| Intel Ethernet Controller I225-V                                  | 21        | 1.31%   |
| Intel Wireless 7260                                               | 20        | 1.25%   |
| Intel Wireless 7265                                               | 18        | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.94%   |
| Intel Wireless 8260                                               | 14        | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.81%   |
| Realtek 802.11ac NIC                                              | 12        | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.75%   |
| Intel Wireless 3165                                               | 11        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 11        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 11        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 9         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 363       | 46.9%   |
| Realtek Semiconductor           | 152       | 19.64%  |
| Qualcomm Atheros                | 85        | 10.98%  |
| MediaTek                        | 50        | 6.46%   |
| Broadcom                        | 42        | 5.43%   |
| Ralink Technology               | 18        | 2.33%   |
| TP-Link                         | 12        | 1.55%   |
| Ralink                          | 9         | 1.16%   |
| Sierra Wireless                 | 6         | 0.78%   |
| Broadcom Limited                | 5         | 0.65%   |
| Qualcomm                        | 4         | 0.52%   |
| Qualcomm Atheros Communications | 3         | 0.39%   |
| Belkin Components               | 3         | 0.39%   |
| ASUSTek Computer                | 3         | 0.39%   |
| NetGear                         | 2         | 0.26%   |
| Marvell Technology Group        | 2         | 0.26%   |
| Edimax Technology               | 2         | 0.26%   |
| Dell                            | 2         | 0.26%   |
| D-Link System                   | 2         | 0.26%   |
| D-Link                          | 2         | 0.26%   |
| ZyXEL Communications            | 1         | 0.13%   |
| Wilocity                        | 1         | 0.13%   |
| Microsoft                       | 1         | 0.13%   |
| Mercucys                        | 1         | 0.13%   |
| Linksys                         | 1         | 0.13%   |
| LG Electronics                  | 1         | 0.13%   |
| Fibocom                         | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 56        | 7.14%   |
| Intel Wi-Fi 6 AX201                                           | 45        | 5.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 36        | 4.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 33        | 4.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 30        | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 29        | 3.7%    |
| Intel Wireless 8265 / 8275                                    | 23        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 22        | 2.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 21        | 2.68%   |
| Intel Wireless 7260                                           | 20        | 2.55%   |
| Intel Wireless 7265                                           | 18        | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 18        | 2.3%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 17        | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 16        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 15        | 1.91%   |
| Intel Wireless 8260                                           | 14        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 14        | 1.79%   |
| Realtek 802.11ac NIC                                          | 12        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                | 12        | 1.53%   |
| Intel Wireless 3165                                           | 11        | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 11        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 10        | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 9         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 9         | 1.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 9         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 9         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 8         | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 8         | 1.02%   |
| Realtek 802.11n WLAN Adapter                                  | 8         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 7         | 0.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 6         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 6         | 0.77%   |
| Ralink MT7601U Wireless Adapter                               | 6         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 6         | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 6         | 0.77%   |
| Intel Wireless-AC 9260                                        | 6         | 0.77%   |
| Intel Centrino Advanced-N 6235                                | 6         | 0.77%   |
| Ralink RT5370 Wireless Adapter                                | 5         | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 5         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 425       | 54.49%  |
| Intel                    | 233       | 29.87%  |
| Qualcomm Atheros         | 33        | 4.23%   |
| Broadcom                 | 23        | 2.95%   |
| ASIX Electronics         | 11        | 1.41%   |
| Aquantia                 | 9         | 1.15%   |
| Samsung Electronics      | 8         | 1.03%   |
| Lenovo                   | 6         | 0.77%   |
| Huawei Technologies      | 6         | 0.77%   |
| Xiaomi                   | 4         | 0.51%   |
| Nvidia                   | 3         | 0.38%   |
| Marvell Technology Group | 3         | 0.38%   |
| DisplayLink              | 3         | 0.38%   |
| VIA Technologies         | 2         | 0.26%   |
| TP-Link                  | 2         | 0.26%   |
| Google                   | 2         | 0.26%   |
| Apple                    | 2         | 0.26%   |
| MediaTek                 | 1         | 0.13%   |
| JMicron Technology       | 1         | 0.13%   |
| ICS Advent               | 1         | 0.13%   |
| IBM                      | 1         | 0.13%   |
| Broadcom Limited         | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 321       | 40.02%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 37        | 4.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 33        | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 3.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 3.62%   |
| Intel I211 Gigabit Network Connection                             | 22        | 2.74%   |
| Intel Ethernet Controller I225-V                                  | 21        | 2.62%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 1.87%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 1.62%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 1.5%    |
| Intel Ethernet Connection (2) I219-V                              | 11        | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 1%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.87%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.87%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.87%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.87%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7         | 0.87%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.75%   |
| Intel Ethernet Connection (14) I219-V                             | 6         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.5%    |
| Huawei LLD-L21                                                    | 4         | 0.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.37%   |
| Intel I350 Gigabit Network Connection                             | 3         | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.37%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.37%   |
| Intel Ethernet Connection (16) I219-LM                            | 3         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 735       | 50%     |
| Ethernet | 721       | 49.05%  |
| Modem    | 11        | 0.75%   |
| Unknown  | 3         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 569       | 60.99%  |
| Ethernet | 364       | 39.01%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 474       | 53.26%  |
| 1     | 374       | 42.02%  |
| 3     | 21        | 2.36%   |
| 0     | 16        | 1.8%    |
| 4     | 4         | 0.45%   |
| 6     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 631       | 70.5%   |
| Yes  | 264       | 29.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 319       | 48.63%  |
| Realtek Semiconductor           | 82        | 12.5%   |
| Cambridge Silicon Radio         | 43        | 6.55%   |
| Qualcomm Atheros Communications | 40        | 6.1%    |
| IMC Networks                    | 30        | 4.57%   |
| Foxconn / Hon Hai               | 27        | 4.12%   |
| Broadcom                        | 27        | 4.12%   |
| Lite-On Technology              | 18        | 2.74%   |
| ASUSTek Computer                | 14        | 2.13%   |
| Apple                           | 13        | 1.98%   |
| MediaTek                        | 8         | 1.22%   |
| Realtek                         | 5         | 0.76%   |
| Dell                            | 5         | 0.76%   |
| TP-Link                         | 4         | 0.61%   |
| Toshiba                         | 4         | 0.61%   |
| Edimax Technology               | 4         | 0.61%   |
| Ralink                          | 2         | 0.3%    |
| Marvell Semiconductor           | 2         | 0.3%    |
| Hewlett-Packard                 | 2         | 0.3%    |
| USI                             | 1         | 0.15%   |
| SINO WEALTH                     | 1         | 0.15%   |
| Foxconn International           | 1         | 0.15%   |
| D-Link                          | 1         | 0.15%   |
| Conwise Technology              | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 83        | 12.63%  |
| Intel AX201 Bluetooth                               | 77        | 11.72%  |
| Realtek Bluetooth Radio                             | 64        | 9.74%   |
| Intel AX200 Bluetooth                               | 54        | 8.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 43        | 6.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 40        | 6.09%   |
| Intel Bluetooth Device                              | 28        | 4.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 3.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 2.28%   |
| Intel AX210 Bluetooth                               | 13        | 1.98%   |
| IMC Networks Wireless_Device                        | 13        | 1.98%   |
| Lite-On Wireless_Device                             | 11        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 1.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 11        | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 1.52%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.37%   |
| MediaTek Wireless_Device                            | 8         | 1.22%   |
| Apple Bluetooth Host Controller                     | 8         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.07%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.91%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 0.91%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.91%   |
| Realtek Bluetooth Radio                             | 5         | 0.76%   |
| IMC Networks Bluetooth Device                       | 5         | 0.76%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.76%   |
| TP-Link UB500 Adapter                               | 4         | 0.61%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 4         | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.46%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.3%    |
| Ralink RT3290 Bluetooth                             | 2         | 0.3%    |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.3%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.3%    |
| Edimax Bluetooth Adapter                            | 2         | 0.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.3%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 608       | 45.37%  |
| AMD                       | 310       | 23.13%  |
| Nvidia                    | 253       | 18.88%  |
| C-Media Electronics       | 27        | 2.01%   |
| JMTek                     | 11        | 0.82%   |
| GN Netcom                 | 11        | 0.82%   |
| Lenovo                    | 8         | 0.6%    |
| Razer USA                 | 6         | 0.45%   |
| Texas Instruments         | 5         | 0.37%   |
| Logitech                  | 5         | 0.37%   |
| Creative Labs             | 5         | 0.37%   |
| VIA Technologies          | 4         | 0.3%    |
| Realtek Semiconductor     | 4         | 0.3%    |
| Kingston Technology       | 4         | 0.3%    |
| Generalplus Technology    | 4         | 0.3%    |
| Corsair                   | 4         | 0.3%    |
| Blue Microphones          | 4         | 0.3%    |
| Tenx Technology           | 3         | 0.22%   |
| Micro Star International  | 3         | 0.22%   |
| Hewlett-Packard           | 3         | 0.22%   |
| Focusrite-Novation        | 3         | 0.22%   |
| Apple                     | 3         | 0.22%   |
| ZOOM                      | 2         | 0.15%   |
| TerraTec Electronic       | 2         | 0.15%   |
| SteelSeries ApS           | 2         | 0.15%   |
| Scarlett                  | 2         | 0.15%   |
| M-Audio                   | 2         | 0.15%   |
| KORG                      | 2         | 0.15%   |
| BY EDIFIER                | 2         | 0.15%   |
| ASUSTek Computer          | 2         | 0.15%   |
| Arturia                   | 2         | 0.15%   |
| Zhaoxin                   | 1         | 0.07%   |
| Yamaha                    | 1         | 0.07%   |
| Veho                      | 1         | 0.07%   |
| Unknown                   | 1         | 0.07%   |
| Sony                      | 1         | 0.07%   |
| Silicon Motion            | 1         | 0.07%   |
| Sennheiser Communications | 1         | 0.07%   |
| Samson Technologies       | 1         | 0.07%   |
| Roland                    | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 138       | 8.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 90        | 5.64%   |
| Intel Sunrise Point-LP HD Audio                                            | 71        | 4.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 63        | 3.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 61        | 3.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 2.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 43        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 41        | 2.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 40        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 38        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27        | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 26        | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 23        | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 1.19%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17        | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 1%      |
| AMD FCH Azalia Controller                                                  | 16        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 15        | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 15        | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15        | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 15        | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 14        | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 12        | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 0.75%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 12        | 0.75%   |
| Nvidia High Definition Audio Controller                                    | 11        | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 173       | 24.44%  |
| SK hynix            | 106       | 14.97%  |
| Kingston            | 82        | 11.58%  |
| Micron Technology   | 75        | 10.59%  |
| Crucial             | 63        | 8.9%    |
| Corsair             | 39        | 5.51%   |
| Unknown             | 31        | 4.38%   |
| G.Skill             | 29        | 4.1%    |
| Unknown (ABCD)      | 13        | 1.84%   |
| A-DATA Technology   | 12        | 1.69%   |
| Ramaxel Technology  | 9         | 1.27%   |
| Unknown             | 9         | 1.27%   |
| Team                | 7         | 0.99%   |
| Elpida              | 6         | 0.85%   |
| Patriot             | 5         | 0.71%   |
| Nanya Technology    | 4         | 0.56%   |
| AMD                 | 4         | 0.56%   |
| Wilk                | 3         | 0.42%   |
| Smart               | 3         | 0.42%   |
| Silicon Power       | 3         | 0.42%   |
| PNY                 | 3         | 0.42%   |
| Transcend           | 2         | 0.28%   |
| Teikon              | 2         | 0.28%   |
| GOODRAM             | 2         | 0.28%   |
| Atermiter           | 2         | 0.28%   |
| Unknown (8A02)      | 1         | 0.14%   |
| Unifosa             | 1         | 0.14%   |
| Super Talent        | 1         | 0.14%   |
| Shenzhen Zhongteng  | 1         | 0.14%   |
| Shenzhen WODPOSIT   | 1         | 0.14%   |
| SHARETRONIC         | 1         | 0.14%   |
| Qumo                | 1         | 0.14%   |
| Qimonda             | 1         | 0.14%   |
| Neo Forza           | 1         | 0.14%   |
| Lexar               | 1         | 0.14%   |
| Kingmax             | 1         | 0.14%   |
| Imation             | 1         | 0.14%   |
| Hewlett-Packard     | 1         | 0.14%   |
| Goldkey             | 1         | 0.14%   |
| Gold Key            | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 11        | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 1.21%   |
| Unknown                                                          | 9         | 1.21%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 8         | 1.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.54%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 4         | 0.54%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 3         | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.4%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.4%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 3         | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.4%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.4%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.4%    |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 3         | 0.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 371       | 61.42%  |
| DDR3    | 133       | 22.02%  |
| LPDDR4  | 37        | 6.13%   |
| DDR5    | 20        | 3.31%   |
| LPDDR5  | 10        | 1.66%   |
| DDR2    | 9         | 1.49%   |
| LPDDR3  | 8         | 1.32%   |
| SDRAM   | 7         | 1.16%   |
| Unknown | 7         | 1.16%   |
| DDR     | 2         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 353       | 57.68%  |
| DIMM         | 189       | 30.88%  |
| Row Of Chips | 62        | 10.13%  |
| Chip         | 4         | 0.65%   |
| Unknown      | 3         | 0.49%   |
| RIMM         | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 302       | 46.18%  |
| 16384 | 138       | 21.1%   |
| 4096  | 138       | 21.1%   |
| 2048  | 36        | 5.5%    |
| 32768 | 35        | 5.35%   |
| 1024  | 5         | 0.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 170       | 26.44%  |
| 1600    | 96        | 14.93%  |
| 2667    | 90        | 14%     |
| 2400    | 57        | 8.86%   |
| 1333    | 29        | 4.51%   |
| 3600    | 25        | 3.89%   |
| 2133    | 23        | 3.58%   |
| 4800    | 16        | 2.49%   |
| 4267    | 16        | 2.49%   |
| 1867    | 13        | 2.02%   |
| 6400    | 10        | 1.56%   |
| 3800    | 7         | 1.09%   |
| 2666    | 7         | 1.09%   |
| 1334    | 7         | 1.09%   |
| 3266    | 6         | 0.93%   |
| 3000    | 5         | 0.78%   |
| 2933    | 5         | 0.78%   |
| 1066    | 5         | 0.78%   |
| 667     | 5         | 0.78%   |
| 4266    | 4         | 0.62%   |
| 3333    | 3         | 0.47%   |
| 3066    | 3         | 0.47%   |
| 2800    | 3         | 0.47%   |
| 1866    | 3         | 0.47%   |
| 8400    | 2         | 0.31%   |
| 6000    | 2         | 0.31%   |
| 3866    | 2         | 0.31%   |
| 3666    | 2         | 0.31%   |
| 800     | 2         | 0.31%   |
| 400     | 2         | 0.31%   |
| Unknown | 2         | 0.31%   |
| 52217   | 1         | 0.16%   |
| 5800    | 1         | 0.16%   |
| 5200    | 1         | 0.16%   |
| 4199    | 1         | 0.16%   |
| 4133    | 1         | 0.16%   |
| 4000    | 1         | 0.16%   |
| 3933    | 1         | 0.16%   |
| 3733    | 1         | 0.16%   |
| 3533    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 33.33%  |
| Seiko Epson         | 6         | 20%     |
| Brother Industries  | 4         | 13.33%  |
| Canon               | 3         | 10%     |
| Samsung Electronics | 2         | 6.67%   |
| Xerox               | 1         | 3.33%   |
| Prolific Technology | 1         | 3.33%   |
| Kyocera             | 1         | 3.33%   |
| Dymo-CoStar         | 1         | 3.33%   |
| Datamax-O'Neil      | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson L3110 Series              | 2         | 6.67%   |
| Seiko Epson L220 Series               | 2         | 6.67%   |
| Samsung M2070 Series                  | 2         | 6.67%   |
| Brother MFC-J460DW                    | 2         | 6.67%   |
| Xerox Phaser 3140 and 3155            | 1         | 3.33%   |
| Seiko Epson XP-3100 Series            | 1         | 3.33%   |
| Seiko Epson ET-2700 Series            | 1         | 3.33%   |
| Prolific PL2305 Parallel Port         | 1         | 3.33%   |
| Kyocera Mita FS-820                   | 1         | 3.33%   |
| HP OfficeJet 5500 series              | 1         | 3.33%   |
| HP LaserJet Professional P 1102w      | 1         | 3.33%   |
| HP LaserJet P2015 series              | 1         | 3.33%   |
| HP LaserJet 1022                      | 1         | 3.33%   |
| HP LaserJet 1012                      | 1         | 3.33%   |
| HP ENVY 4500 series                   | 1         | 3.33%   |
| HP DeskJet D2300                      | 1         | 3.33%   |
| HP DeskJet 3700 series                | 1         | 3.33%   |
| HP DeskJet 3630 series                | 1         | 3.33%   |
| HP ColorLaserJet M253-M254            | 1         | 3.33%   |
| Dymo-CoStar LabelWriter 450           | 1         | 3.33%   |
| Datamax-O'Neil Datamax E-4304         | 1         | 3.33%   |
| Canon PIXMA MX470 Series              | 1         | 3.33%   |
| Canon LaserShot LBP-1120 Printer      | 1         | 3.33%   |
| Canon iP2600 series                   | 1         | 3.33%   |
| Brother PT-P700 P-touch Label Printer | 1         | 3.33%   |
| Brother HL-2230 series                | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 5         | 71.43%  |
| Seiko Epson    | 1         | 14.29%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2         | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 14.29%  |
| Canon CanoScan LiDE 220                     | 1         | 14.29%  |
| Canon CanoScan LiDE 210                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 108       | 17.76%  |
| Microdia                               | 61        | 10.03%  |
| IMC Networks                           | 58        | 9.54%   |
| Quanta                                 | 48        | 7.89%   |
| Logitech                               | 48        | 7.89%   |
| Realtek Semiconductor                  | 41        | 6.74%   |
| Bison Electronics                      | 30        | 4.93%   |
| Acer                                   | 28        | 4.61%   |
| Sunplus Innovation Technology          | 27        | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.78%   |
| Luxvisions Innotech Limited            | 15        | 2.47%   |
| Syntek                                 | 13        | 2.14%   |
| Lite-On Technology                     | 10        | 1.64%   |
| Silicon Motion                         | 8         | 1.32%   |
| Samsung Electronics                    | 8         | 1.32%   |
| Apple                                  | 8         | 1.32%   |
| Generalplus Technology                 | 6         | 0.99%   |
| Microsoft                              | 5         | 0.82%   |
| Alcor Micro                            | 5         | 0.82%   |
| Y Media                                | 4         | 0.66%   |
| Z-Star Microelectronics                | 3         | 0.49%   |
| USB Camera                             | 3         | 0.49%   |
| Suyin                                  | 3         | 0.49%   |
| SunplusIT                              | 3         | 0.49%   |
| Sonix Technology                       | 3         | 0.49%   |
| KYE Systems (Mouse Systems)            | 3         | 0.49%   |
| ARC International                      | 3         | 0.49%   |
| YGTek                                  | 2         | 0.33%   |
| Unknown                                | 2         | 0.33%   |
| Lenovo                                 | 2         | 0.33%   |
| Jieli Technology                       | 2         | 0.33%   |
| GEMBIRD                                | 2         | 0.33%   |
| Xiaomi                                 | 1         | 0.16%   |
| USB Camera CS                          | 1         | 0.16%   |
| Sunplus IT                             | 1         | 0.16%   |
| STEREOLABS                             | 1         | 0.16%   |
| SN0002                                 | 1         | 0.16%   |
| ShineTech                              | 1         | 0.16%   |
| Ricoh                                  | 1         | 0.16%   |
| Razer USA                              | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 33        | 5.4%    |
| Microdia Integrated_Webcam_HD                                   | 29        | 4.75%   |
| IMC Networks Integrated Camera                                  | 21        | 3.44%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 15        | 2.45%   |
| Realtek Integrated_Webcam_HD                                    | 14        | 2.29%   |
| Acer Integrated Camera                                          | 14        | 2.29%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.8%    |
| Chicony HD WebCam                                               | 11        | 1.8%    |
| Bison Integrated Camera                                         | 11        | 1.8%    |
| Sunplus Integrated_Webcam_HD                                    | 10        | 1.64%   |
| Logitech HD Pro Webcam C920                                     | 10        | 1.64%   |
| Syntek Integrated Camera                                        | 9         | 1.47%   |
| Chicony HD User Facing                                          | 9         | 1.47%   |
| Samsung Galaxy A5 (MTP)                                         | 8         | 1.31%   |
| Quanta HD User Facing                                           | 7         | 1.15%   |
| Logitech Webcam C270                                            | 7         | 1.15%   |
| Microdia Webcam Vitade AF                                       | 6         | 0.98%   |
| Microdia Integrated_Webcam_FHD                                  | 6         | 0.98%   |
| Logitech C922 Pro Stream Webcam                                 | 6         | 0.98%   |
| IMC Networks HD Camera                                          | 6         | 0.98%   |
| Chicony HP Wide Vision HD Camera                                | 6         | 0.98%   |
| Chicony HP HD Camera                                            | 6         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.98%   |
| Acer HD Webcam                                                  | 6         | 0.98%   |
| Quanta HP Wide Vision HD Camera                                 | 5         | 0.82%   |
| Luxvisions Innotech Limited Integrated Camera                   | 5         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 0.82%   |
| Y Media USB Camera                                              | 4         | 0.65%   |
| Realtek USB Camera                                              | 4         | 0.65%   |
| Quanta HP HD Camera                                             | 4         | 0.65%   |
| Quanta HD Webcam                                                | 4         | 0.65%   |
| Quanta ACER HD User Facing                                      | 4         | 0.65%   |
| Microdia REDRAGON Live Camera Audio                             | 4         | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.65%   |
| Logitech C920 PRO HD Webcam                                     | 4         | 0.65%   |
| Chicony USB2.0 Camera                                           | 4         | 0.65%   |
| Chicony HP TrueVision HD Camera                                 | 4         | 0.65%   |
| Chicony HP Truevision HD                                        | 4         | 0.65%   |
| Apple FaceTime HD Camera (Built-in)                             | 4         | 0.65%   |
| USB Camera USB Camera                                           | 3         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 38        | 31.4%   |
| Shenzhen Goodix Technology         | 33        | 27.27%  |
| Validity Sensors                   | 29        | 23.97%  |
| Elan Microelectronics              | 10        | 8.26%   |
| Upek                               | 3         | 2.48%   |
| AuthenTec                          | 3         | 2.48%   |
| LighTuning Technology              | 2         | 1.65%   |
| STMicroelectronics                 | 1         | 0.83%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.83%   |
| Focal-systems.Corp                 | 1         | 0.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 24        | 19.83%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 6.61%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 5.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.96%   |
| Elan ELAN:ARM-M4                                                           | 6         | 4.96%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.13%   |
| Synaptics UWP WBDI                                                         | 5         | 4.13%   |
| Synaptics WBDI                                                             | 4         | 3.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.31%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.31%   |
| Validity Sensors VFS491                                                    | 3         | 2.48%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.48%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.48%   |
| Synaptics UWP WBDI Device                                                  | 3         | 2.48%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.65%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.65%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.65%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.65%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 1.65%   |
| Synaptics  WBDI                                                            | 2         | 1.65%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.65%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.65%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.83%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.83%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.83%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.83%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.83%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.83%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.83%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 18        | 37.5%   |
| Alcor Micro           | 17        | 35.42%  |
| Upek                  | 4         | 8.33%   |
| BIT4ID                | 2         | 4.17%   |
| SCM Microsystems      | 1         | 2.08%   |
| OmniKey               | 1         | 2.08%   |
| O2 Micro              | 1         | 2.08%   |
| Lenovo                | 1         | 2.08%   |
| Gemalto (was Gemplus) | 1         | 2.08%   |
| Clay Logic            | 1         | 2.08%   |
| Advanced Card Systems | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 35.42%  |
| Broadcom 58200                                                               | 8         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 8.33%   |
| Broadcom 5880                                                                | 4         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 6.25%   |
| BIT4ID miniLector EVO                                                        | 2         | 4.17%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 2.08%   |
| OmniKey CardMan 1021                                                         | 1         | 2.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.08%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.08%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.08%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 2.08%   |
| Advanced Card Systems ACR39U                                                 | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 617       | 68.03%  |
| 1     | 230       | 25.36%  |
| 2     | 51        | 5.62%   |
| 3     | 7         | 0.77%   |
| 9     | 1         | 0.11%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 120       | 34.48%  |
| Graphics card            | 52        | 14.94%  |
| Chipcard                 | 43        | 12.36%  |
| Net/wireless             | 41        | 11.78%  |
| Camera                   | 24        | 6.9%    |
| Multimedia controller    | 18        | 5.17%   |
| Unassigned class         | 12        | 3.45%   |
| Bluetooth                | 10        | 2.87%   |
| Sound                    | 8         | 2.3%    |
| Communication controller | 8         | 2.3%    |
| Network                  | 3         | 0.86%   |
| Net/ethernet             | 3         | 0.86%   |
| Modem                    | 2         | 0.57%   |
| Card reader              | 2         | 0.57%   |
| Storage                  | 1         | 0.29%   |
| Dvb card                 | 1         | 0.29%   |


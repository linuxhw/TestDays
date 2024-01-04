Linux in South Africa - Tested Hardware & Statistics
----------------------------------------------------

A project to collect tested hardware configurations for Linux in South Africa.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/South_Africa/Desktop/README.md) and [notebooks](/Location/South_Africa/Notebook/README.md).

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

Total: 1842

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G50-70 20351                | Notebook    | [cb1029f101](https://linux-hardware.org/?probe=cb1029f101) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [a9ddfb0974](https://linux-hardware.org/?probe=a9ddfb0974) | Jan 02, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f7f3e0ddc9](https://linux-hardware.org/?probe=f7f3e0ddc9) | Jan 01, 2024 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [769eb69c0e](https://linux-hardware.org/?probe=769eb69c0e) | Jan 01, 2024 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [faf34bf75f](https://linux-hardware.org/?probe=faf34bf75f) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [36856f5ac1](https://linux-hardware.org/?probe=36856f5ac1) | Dec 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c0a8fdcf6f](https://linux-hardware.org/?probe=c0a8fdcf6f) | Dec 29, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [25e443386a](https://linux-hardware.org/?probe=25e443386a) | Dec 26, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd911fd507](https://linux-hardware.org/?probe=dd911fd507) | Dec 24, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1dc0b2a06a](https://linux-hardware.org/?probe=1dc0b2a06a) | Dec 22, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [706947928d](https://linux-hardware.org/?probe=706947928d) | Dec 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [4e773891cd](https://linux-hardware.org/?probe=4e773891cd) | Dec 21, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9a3cef62bc](https://linux-hardware.org/?probe=9a3cef62bc) | Dec 20, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [b6ca701110](https://linux-hardware.org/?probe=b6ca701110) | Dec 18, 2023 |
| GIADA         | Cherry Trail CR JHS60V      | Notebook    | [18734ee033](https://linux-hardware.org/?probe=18734ee033) | Dec 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [863d50a5a5](https://linux-hardware.org/?probe=863d50a5a5) | Dec 13, 2023 |
| Dell          | Precision 7510              | Notebook    | [dddb88520a](https://linux-hardware.org/?probe=dddb88520a) | Dec 13, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [18f6c41058](https://linux-hardware.org/?probe=18f6c41058) | Dec 10, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [df48d704bb](https://linux-hardware.org/?probe=df48d704bb) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [45c2afd3f1](https://linux-hardware.org/?probe=45c2afd3f1) | Dec 08, 2023 |
| Sony          | VPCW216AG                   | Notebook    | [fb60613609](https://linux-hardware.org/?probe=fb60613609) | Dec 08, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [b15f912ae7](https://linux-hardware.org/?probe=b15f912ae7) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3c212a9547](https://linux-hardware.org/?probe=3c212a9547) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [99293a328c](https://linux-hardware.org/?probe=99293a328c) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [b8e3a992b3](https://linux-hardware.org/?probe=b8e3a992b3) | Dec 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [27ca1601a1](https://linux-hardware.org/?probe=27ca1601a1) | Dec 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [00c7b2faf9](https://linux-hardware.org/?probe=00c7b2faf9) | Dec 01, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [384fc3c571](https://linux-hardware.org/?probe=384fc3c571) | Nov 29, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [16a605c091](https://linux-hardware.org/?probe=16a605c091) | Nov 28, 2023 |
| Acer          | Veriton M290                | Desktop     | [30dd8ffe84](https://linux-hardware.org/?probe=30dd8ffe84) | Nov 26, 2023 |
| Lenovo        | ThinkPad E560 20EV0000ZA    | Notebook    | [dad936ca8a](https://linux-hardware.org/?probe=dad936ca8a) | Nov 22, 2023 |
| Lenovo        | ThinkPad E560 20EV0000ZA    | Notebook    | [6cb322f4cb](https://linux-hardware.org/?probe=6cb322f4cb) | Nov 22, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [30d6da52fa](https://linux-hardware.org/?probe=30d6da52fa) | Nov 22, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [1d8de35042](https://linux-hardware.org/?probe=1d8de35042) | Nov 21, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [0b8966c181](https://linux-hardware.org/?probe=0b8966c181) | Nov 19, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [28440e547a](https://linux-hardware.org/?probe=28440e547a) | Nov 18, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [10abd64eac](https://linux-hardware.org/?probe=10abd64eac) | Nov 18, 2023 |
| Dell          | 500                         | Notebook    | [9a40219351](https://linux-hardware.org/?probe=9a40219351) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [9ac3245bda](https://linux-hardware.org/?probe=9ac3245bda) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [e66475e9e4](https://linux-hardware.org/?probe=e66475e9e4) | Nov 16, 2023 |
| HP            | Unknown                     | Notebook    | [3827b1fa19](https://linux-hardware.org/?probe=3827b1fa19) | Nov 16, 2023 |
| HP            | Unknown                     | Notebook    | [ef19087623](https://linux-hardware.org/?probe=ef19087623) | Nov 16, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [71786a484b](https://linux-hardware.org/?probe=71786a484b) | Nov 16, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [1cf432335c](https://linux-hardware.org/?probe=1cf432335c) | Nov 15, 2023 |
| Acer          | Nitro AN16-51               | Notebook    | [14641b614b](https://linux-hardware.org/?probe=14641b614b) | Nov 15, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [3d78cda725](https://linux-hardware.org/?probe=3d78cda725) | Nov 14, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [133a963c15](https://linux-hardware.org/?probe=133a963c15) | Nov 13, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [f29ef35eec](https://linux-hardware.org/?probe=f29ef35eec) | Nov 13, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [b3c22e6ea8](https://linux-hardware.org/?probe=b3c22e6ea8) | Nov 13, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [75735f5b69](https://linux-hardware.org/?probe=75735f5b69) | Nov 11, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [6de52fa703](https://linux-hardware.org/?probe=6de52fa703) | Nov 11, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [70755c93a9](https://linux-hardware.org/?probe=70755c93a9) | Nov 10, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [b7f860630b](https://linux-hardware.org/?probe=b7f860630b) | Nov 10, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [13fbc97a18](https://linux-hardware.org/?probe=13fbc97a18) | Nov 08, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a22610f17c](https://linux-hardware.org/?probe=a22610f17c) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eef004b620](https://linux-hardware.org/?probe=eef004b620) | Nov 05, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [128a0a94c7](https://linux-hardware.org/?probe=128a0a94c7) | Nov 02, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [e5a9bbe278](https://linux-hardware.org/?probe=e5a9bbe278) | Oct 31, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d8590bb026](https://linux-hardware.org/?probe=d8590bb026) | Oct 30, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [7c4b363241](https://linux-hardware.org/?probe=7c4b363241) | Oct 28, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [37b9c54cea](https://linux-hardware.org/?probe=37b9c54cea) | Oct 26, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [1f7bb1fb21](https://linux-hardware.org/?probe=1f7bb1fb21) | Oct 25, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [8e0cdb93fe](https://linux-hardware.org/?probe=8e0cdb93fe) | Oct 25, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [31129675c0](https://linux-hardware.org/?probe=31129675c0) | Oct 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [57c5525fd7](https://linux-hardware.org/?probe=57c5525fd7) | Oct 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [f927a69d11](https://linux-hardware.org/?probe=f927a69d11) | Oct 20, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e07bf20a8a](https://linux-hardware.org/?probe=e07bf20a8a) | Oct 20, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [eb391611f3](https://linux-hardware.org/?probe=eb391611f3) | Oct 19, 2023 |
| HP            | 3397                        | Desktop     | [555ad3c716](https://linux-hardware.org/?probe=555ad3c716) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [7148bf6db9](https://linux-hardware.org/?probe=7148bf6db9) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9cbbb0364b](https://linux-hardware.org/?probe=9cbbb0364b) | Oct 19, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [df408e2203](https://linux-hardware.org/?probe=df408e2203) | Oct 18, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [da6815d760](https://linux-hardware.org/?probe=da6815d760) | Oct 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8d41cb80bf](https://linux-hardware.org/?probe=8d41cb80bf) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [339d1c4a25](https://linux-hardware.org/?probe=339d1c4a25) | Oct 13, 2023 |
| Dell          | Latitude 5590               | Notebook    | [b788f92c64](https://linux-hardware.org/?probe=b788f92c64) | Oct 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [12ad8a9467](https://linux-hardware.org/?probe=12ad8a9467) | Oct 09, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [fa291615c6](https://linux-hardware.org/?probe=fa291615c6) | Oct 08, 2023 |
| Dell          | Latitude 3440               | Notebook    | [88a0ec8369](https://linux-hardware.org/?probe=88a0ec8369) | Oct 08, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [9e30a64927](https://linux-hardware.org/?probe=9e30a64927) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7513e708f6](https://linux-hardware.org/?probe=7513e708f6) | Oct 07, 2023 |
| Unknown       | H102150IWU                  | Tablet      | [47f7356154](https://linux-hardware.org/?probe=47f7356154) | Oct 06, 2023 |
| Proline       | V1165C4                     | Notebook    | [393d14039b](https://linux-hardware.org/?probe=393d14039b) | Oct 05, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4ea4c9812f](https://linux-hardware.org/?probe=4ea4c9812f) | Oct 04, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [fa2c7e0da1](https://linux-hardware.org/?probe=fa2c7e0da1) | Oct 03, 2023 |
| System76      | Gazelle Professional        | Notebook    | [f33ed13bf5](https://linux-hardware.org/?probe=f33ed13bf5) | Oct 02, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [10ebab5a3f](https://linux-hardware.org/?probe=10ebab5a3f) | Oct 02, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [da95378bd3](https://linux-hardware.org/?probe=da95378bd3) | Oct 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [1d1c00db51](https://linux-hardware.org/?probe=1d1c00db51) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [2b0868267b](https://linux-hardware.org/?probe=2b0868267b) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [d8e6101d6d](https://linux-hardware.org/?probe=d8e6101d6d) | Oct 02, 2023 |
| HP            | 0A50h                       | Desktop     | [e2082963e9](https://linux-hardware.org/?probe=e2082963e9) | Oct 01, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e6d8dfa4a1](https://linux-hardware.org/?probe=e6d8dfa4a1) | Sep 29, 2023 |
| HP            | 3397                        | Desktop     | [e0396e65c6](https://linux-hardware.org/?probe=e0396e65c6) | Sep 26, 2023 |
| Dell          | 0WXF9V A02                  | Server      | [842186b04e](https://linux-hardware.org/?probe=842186b04e) | Sep 24, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [77c3039fdc](https://linux-hardware.org/?probe=77c3039fdc) | Sep 24, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [f870f9e3ac](https://linux-hardware.org/?probe=f870f9e3ac) | Sep 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [3847c20962](https://linux-hardware.org/?probe=3847c20962) | Sep 21, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [4e5ae95013](https://linux-hardware.org/?probe=4e5ae95013) | Sep 20, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [0f12c482a1](https://linux-hardware.org/?probe=0f12c482a1) | Sep 20, 2023 |
| Lenovo        | ThinkPad T570 20H90011ZA    | Notebook    | [f59a257ab5](https://linux-hardware.org/?probe=f59a257ab5) | Sep 14, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [4de6e83768](https://linux-hardware.org/?probe=4de6e83768) | Sep 11, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [b23d13eddc](https://linux-hardware.org/?probe=b23d13eddc) | Sep 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [08fd5b59f4](https://linux-hardware.org/?probe=08fd5b59f4) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [d3d6e283d0](https://linux-hardware.org/?probe=d3d6e283d0) | Sep 10, 2023 |
| Dell          | Latitude E6330              | Notebook    | [2a3c06d056](https://linux-hardware.org/?probe=2a3c06d056) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [2fc59172dd](https://linux-hardware.org/?probe=2fc59172dd) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f3bdad3061](https://linux-hardware.org/?probe=f3bdad3061) | Sep 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [08dd85e58d](https://linux-hardware.org/?probe=08dd85e58d) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e65692f205](https://linux-hardware.org/?probe=e65692f205) | Sep 05, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [99b1fcf2e9](https://linux-hardware.org/?probe=99b1fcf2e9) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9e7e8b4fbd](https://linux-hardware.org/?probe=9e7e8b4fbd) | Sep 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [d4335c9520](https://linux-hardware.org/?probe=d4335c9520) | Sep 01, 2023 |
| ASUSTek       | PRIME Z790-P D4             | Desktop     | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | Desktop     | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [1782829fec](https://linux-hardware.org/?probe=1782829fec) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d627b8c625](https://linux-hardware.org/?probe=d627b8c625) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [54930549e6](https://linux-hardware.org/?probe=54930549e6) | Aug 28, 2023 |
| HP            | 829A                        | Mini pc     | [603dced1cd](https://linux-hardware.org/?probe=603dced1cd) | Aug 27, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | Notebook    | [d0f87a58ec](https://linux-hardware.org/?probe=d0f87a58ec) | Aug 23, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| MSI           | G31M3-F V2                  | Desktop     | [fa4595b9f1](https://linux-hardware.org/?probe=fa4595b9f1) | Aug 21, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [cb333c6fae](https://linux-hardware.org/?probe=cb333c6fae) | Aug 20, 2023 |
| Dell          | Latitude 5490               | Notebook    | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| MSI           | G31M3-F V2                  | Desktop     | [3007f122d0](https://linux-hardware.org/?probe=3007f122d0) | Aug 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [7e196f2365](https://linux-hardware.org/?probe=7e196f2365) | Aug 19, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c43c2f3798](https://linux-hardware.org/?probe=c43c2f3798) | Aug 18, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [64428e8ca9](https://linux-hardware.org/?probe=64428e8ca9) | Aug 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [e8f61a39e7](https://linux-hardware.org/?probe=e8f61a39e7) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| Intel         | S3420GP E51976-405          | Server      | [b14cc4b52a](https://linux-hardware.org/?probe=b14cc4b52a) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [64a1b8ad5d](https://linux-hardware.org/?probe=64a1b8ad5d) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9d7d216fc0](https://linux-hardware.org/?probe=9d7d216fc0) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [4963974f47](https://linux-hardware.org/?probe=4963974f47) | Aug 12, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [63861067de](https://linux-hardware.org/?probe=63861067de) | Aug 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [2939f44178](https://linux-hardware.org/?probe=2939f44178) | Aug 12, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [b99e595bfc](https://linux-hardware.org/?probe=b99e595bfc) | Aug 12, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [1fa34106f1](https://linux-hardware.org/?probe=1fa34106f1) | Aug 11, 2023 |
| Dell          | G3 3590                     | Notebook    | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| Dell          | Precision 7740              | Notebook    | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [ee882ba789](https://linux-hardware.org/?probe=ee882ba789) | Aug 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [779c23fe06](https://linux-hardware.org/?probe=779c23fe06) | Aug 05, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [13c8b276bb](https://linux-hardware.org/?probe=13c8b276bb) | Aug 04, 2023 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [a3ff56579a](https://linux-hardware.org/?probe=a3ff56579a) | Aug 03, 2023 |
| Dell          | G3 3590                     | Notebook    | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Toshiba       | Satellite C850-F74T         | Notebook    | [7756db419e](https://linux-hardware.org/?probe=7756db419e) | Aug 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [51541062dc](https://linux-hardware.org/?probe=51541062dc) | Jul 31, 2023 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c15cd0e6c0](https://linux-hardware.org/?probe=c15cd0e6c0) | Jul 29, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [b464dbd11c](https://linux-hardware.org/?probe=b464dbd11c) | Jul 27, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| Intel         | DQ965GF AAD41676-601        | Desktop     | [384577dee3](https://linux-hardware.org/?probe=384577dee3) | Jul 25, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [3f4e603493](https://linux-hardware.org/?probe=3f4e603493) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| Intel         | DH67BL AAG10189-209         | Desktop     | [8065e7b83a](https://linux-hardware.org/?probe=8065e7b83a) | Jul 20, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [b84e3b9a04](https://linux-hardware.org/?probe=b84e3b9a04) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| CONNEX        | L1415-BAY                   | Notebook    | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [a097322114](https://linux-hardware.org/?probe=a097322114) | Jul 17, 2023 |
| Dell          | Latitude E6410              | Notebook    | [78131f9d4b](https://linux-hardware.org/?probe=78131f9d4b) | Jul 14, 2023 |
| Dell          | Latitude E6530              | Notebook    | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [202ada5369](https://linux-hardware.org/?probe=202ada5369) | Jul 13, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [88982c878a](https://linux-hardware.org/?probe=88982c878a) | Jul 13, 2023 |
| HP            | 1495                        | Desktop     | [8fa2ff9487](https://linux-hardware.org/?probe=8fa2ff9487) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [39b5c3bb23](https://linux-hardware.org/?probe=39b5c3bb23) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8890be41ec](https://linux-hardware.org/?probe=8890be41ec) | Jul 10, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| HP            | 0A50h                       | Desktop     | [125782672d](https://linux-hardware.org/?probe=125782672d) | Jul 06, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b0c1a875c3](https://linux-hardware.org/?probe=b0c1a875c3) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [0d847f64a0](https://linux-hardware.org/?probe=0d847f64a0) | Jul 05, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [36ca0aa203](https://linux-hardware.org/?probe=36ca0aa203) | Jul 03, 2023 |
| HP            | ProBook 455 G6              | Notebook    | [f4b853f43e](https://linux-hardware.org/?probe=f4b853f43e) | Jul 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | Notebook    | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [faff66ca26](https://linux-hardware.org/?probe=faff66ca26) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [b34e147b1c](https://linux-hardware.org/?probe=b34e147b1c) | Jun 25, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | Notebook    | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [186a7eedb6](https://linux-hardware.org/?probe=186a7eedb6) | Jun 25, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a243aaac72](https://linux-hardware.org/?probe=a243aaac72) | Jun 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [4c4335bcff](https://linux-hardware.org/?probe=4c4335bcff) | Jun 23, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [f82fbc50e3](https://linux-hardware.org/?probe=f82fbc50e3) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2310257292](https://linux-hardware.org/?probe=2310257292) | Jun 19, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ee6f9906b5](https://linux-hardware.org/?probe=ee6f9906b5) | Jun 19, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [d5ac5e48ce](https://linux-hardware.org/?probe=d5ac5e48ce) | Jun 18, 2023 |
| Lenovo        | ThinkPad T430 2349S33       | Notebook    | [c8c46af444](https://linux-hardware.org/?probe=c8c46af444) | Jun 18, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ce94354489](https://linux-hardware.org/?probe=ce94354489) | Jun 18, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a581f2e058](https://linux-hardware.org/?probe=a581f2e058) | Jun 18, 2023 |
| I-Life Dig... | ZED Air Plus                | Notebook    | [c8bb1a5e0e](https://linux-hardware.org/?probe=c8bb1a5e0e) | Jun 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [e2357f72af](https://linux-hardware.org/?probe=e2357f72af) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | Desktop     | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b67a3f74c3](https://linux-hardware.org/?probe=b67a3f74c3) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8ad5106aca](https://linux-hardware.org/?probe=8ad5106aca) | Jun 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [1e6933ec61](https://linux-hardware.org/?probe=1e6933ec61) | Jun 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 1495                        | Desktop     | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| MECER         | MW10Q17                     | Tablet      | [36fd3d704b](https://linux-hardware.org/?probe=36fd3d704b) | Jun 05, 2023 |
| MECER         | MW10Q17                     | Tablet      | [3cdab95833](https://linux-hardware.org/?probe=3cdab95833) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | Desktop     | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| HP            | 1497                        | Desktop     | [5f1886622a](https://linux-hardware.org/?probe=5f1886622a) | May 29, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [f9bc4694e4](https://linux-hardware.org/?probe=f9bc4694e4) | May 28, 2023 |
| HP            | 1495                        | Desktop     | [15b94cba50](https://linux-hardware.org/?probe=15b94cba50) | May 28, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | Notebook    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Toshiba       | Satellite Pro C650          | Notebook    | [50fc04b16c](https://linux-hardware.org/?probe=50fc04b16c) | May 25, 2023 |
| Acer          | Aspire V3-731               | Notebook    | [d07d017c32](https://linux-hardware.org/?probe=d07d017c32) | May 24, 2023 |
| Lenovo        | ThinkPad X250 20CLS65E00    | Notebook    | [e65932f3a9](https://linux-hardware.org/?probe=e65932f3a9) | May 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7afbe545bc](https://linux-hardware.org/?probe=7afbe545bc) | May 21, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [438d9b5e18](https://linux-hardware.org/?probe=438d9b5e18) | May 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1fdf5742d0](https://linux-hardware.org/?probe=1fdf5742d0) | May 21, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [36d4349090](https://linux-hardware.org/?probe=36d4349090) | May 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [aa7e36874d](https://linux-hardware.org/?probe=aa7e36874d) | May 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8dc0c0b41](https://linux-hardware.org/?probe=e8dc0c0b41) | May 17, 2023 |
| Intel         | Tiger Hill                  | Desktop     | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Dell          | Latitude E6530              | Notebook    | [632b8094e3](https://linux-hardware.org/?probe=632b8094e3) | May 15, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [1e7e92e7e8](https://linux-hardware.org/?probe=1e7e92e7e8) | May 15, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e4d8abe098](https://linux-hardware.org/?probe=e4d8abe098) | May 15, 2023 |
| Dell          | Latitude E6520              | Notebook    | [78aaf99b7b](https://linux-hardware.org/?probe=78aaf99b7b) | May 14, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [d266be713a](https://linux-hardware.org/?probe=d266be713a) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [afde593648](https://linux-hardware.org/?probe=afde593648) | May 10, 2023 |
| Intel         | H61                         | Desktop     | [cd89c5b708](https://linux-hardware.org/?probe=cd89c5b708) | May 06, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [1d74519195](https://linux-hardware.org/?probe=1d74519195) | May 04, 2023 |
| Dell          | Latitude E6400              | Notebook    | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| Gigabyte      | P75-D3                      | Desktop     | [4f6987c722](https://linux-hardware.org/?probe=4f6987c722) | Apr 30, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [4cd1484039](https://linux-hardware.org/?probe=4cd1484039) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [0796e35c73](https://linux-hardware.org/?probe=0796e35c73) | Apr 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [abf277ec59](https://linux-hardware.org/?probe=abf277ec59) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| Acer          | AOHAPPY                     | Notebook    | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Acer          | AOHAPPY                     | Notebook    | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| Acer          | Aspire A315-54K             | Notebook    | [4c3d8d685a](https://linux-hardware.org/?probe=4c3d8d685a) | Apr 20, 2023 |
| ASRock        | G31M-S                      | Desktop     | [7c2bfcaeca](https://linux-hardware.org/?probe=7c2bfcaeca) | Apr 20, 2023 |
| Dell          | Latitude E5510              | Notebook    | [7e57f9e0f0](https://linux-hardware.org/?probe=7e57f9e0f0) | Apr 20, 2023 |
| Dell          | Latitude E5510              | Notebook    | [08e03aa4d8](https://linux-hardware.org/?probe=08e03aa4d8) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23a61dfa8f](https://linux-hardware.org/?probe=23a61dfa8f) | Apr 19, 2023 |
| Acer          | FQ965M MP                   | Desktop     | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| HP            | Spectre Folio Convertibl... | Convertible | [e39dd8fa42](https://linux-hardware.org/?probe=e39dd8fa42) | Apr 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [936f8f8810](https://linux-hardware.org/?probe=936f8f8810) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Intel         | DH67BL AAG10189-209         | Desktop     | [b8e206486d](https://linux-hardware.org/?probe=b8e206486d) | Apr 13, 2023 |
| Dell          | Latitude 3510               | Notebook    | [48fe09d0a3](https://linux-hardware.org/?probe=48fe09d0a3) | Apr 12, 2023 |
| Dell          | Latitude 3510               | Notebook    | [582f6705cb](https://linux-hardware.org/?probe=582f6705cb) | Apr 12, 2023 |
| HP            | 339A                        | Desktop     | [877e64e105](https://linux-hardware.org/?probe=877e64e105) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ef5829077e](https://linux-hardware.org/?probe=ef5829077e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e0e2242a64](https://linux-hardware.org/?probe=e0e2242a64) | Apr 11, 2023 |
| Dell          | Vostro 2521                 | Notebook    | [fdb9903ab4](https://linux-hardware.org/?probe=fdb9903ab4) | Apr 09, 2023 |
| HP            | 339A                        | Desktop     | [eb409991d2](https://linux-hardware.org/?probe=eb409991d2) | Apr 09, 2023 |
| HP            | 2AA2                        | Desktop     | [28c42fc95f](https://linux-hardware.org/?probe=28c42fc95f) | Apr 05, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6ad0f579b6](https://linux-hardware.org/?probe=6ad0f579b6) | Apr 05, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| Supermicro    | X12SDV-8C-SP6F              | Server      | [3751d50dde](https://linux-hardware.org/?probe=3751d50dde) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Lenovo        | 36DB SDK0J40688 WIN 3424... | All in one  | [07c690a090](https://linux-hardware.org/?probe=07c690a090) | Mar 31, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [6aae8ca2a0](https://linux-hardware.org/?probe=6aae8ca2a0) | Mar 30, 2023 |
| Clevo         | W150HNM/W170HN              | Notebook    | [8a86bbf31c](https://linux-hardware.org/?probe=8a86bbf31c) | Mar 29, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [28a9f53f42](https://linux-hardware.org/?probe=28a9f53f42) | Mar 28, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| HP            | 1495                        | Desktop     | [3fe89757bb](https://linux-hardware.org/?probe=3fe89757bb) | Mar 21, 2023 |
| Dell          | XPS L421X                   | Notebook    | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [662d96a2ed](https://linux-hardware.org/?probe=662d96a2ed) | Mar 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6219b24b47](https://linux-hardware.org/?probe=6219b24b47) | Mar 15, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [77b68431f7](https://linux-hardware.org/?probe=77b68431f7) | Mar 14, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [aee5d96875](https://linux-hardware.org/?probe=aee5d96875) | Mar 14, 2023 |
| Dell          | G15 5510                    | Notebook    | [fa6a50c541](https://linux-hardware.org/?probe=fa6a50c541) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| Proline       | V146SH                      | Notebook    | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [53649dddb6](https://linux-hardware.org/?probe=53649dddb6) | Mar 10, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| HP            | ProBook 4530s               | Notebook    | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Latitude E7470              | Notebook    | [51b40c1604](https://linux-hardware.org/?probe=51b40c1604) | Mar 09, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5b98ac00da](https://linux-hardware.org/?probe=5b98ac00da) | Mar 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82551d929c](https://linux-hardware.org/?probe=82551d929c) | Mar 09, 2023 |
| Lenovo        | ThinkPad T500 2241BU3       | Notebook    | [6cd14d1366](https://linux-hardware.org/?probe=6cd14d1366) | Mar 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| Lenovo        | ThinkPad T500 2241BU3       | Notebook    | [da7eb1619d](https://linux-hardware.org/?probe=da7eb1619d) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| HP            | 620                         | Notebook    | [d272a54b5d](https://linux-hardware.org/?probe=d272a54b5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [0f0f44b0ee](https://linux-hardware.org/?probe=0f0f44b0ee) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| HP            | 1497                        | Desktop     | [c74b2b540e](https://linux-hardware.org/?probe=c74b2b540e) | Mar 02, 2023 |
| Dell          | 05R2TK A01                  | All in one  | [efa9d9069d](https://linux-hardware.org/?probe=efa9d9069d) | Mar 01, 2023 |
| HP            | 805D                        | Desktop     | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| Biostar       | H81MLV3                     | Desktop     | [ccba1a8217](https://linux-hardware.org/?probe=ccba1a8217) | Feb 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [a52b9c7637](https://linux-hardware.org/?probe=a52b9c7637) | Feb 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [45e989b539](https://linux-hardware.org/?probe=45e989b539) | Feb 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [17429e7813](https://linux-hardware.org/?probe=17429e7813) | Feb 27, 2023 |
| HP            | 620                         | Notebook    | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude 5490               | Notebook    | [ccde867e7d](https://linux-hardware.org/?probe=ccde867e7d) | Feb 24, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [186b84313d](https://linux-hardware.org/?probe=186b84313d) | Feb 22, 2023 |
| HP            | ProBook 4540s               | Notebook    | [079a5f512d](https://linux-hardware.org/?probe=079a5f512d) | Feb 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [586653a4a6](https://linux-hardware.org/?probe=586653a4a6) | Feb 18, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [fcbec20556](https://linux-hardware.org/?probe=fcbec20556) | Feb 17, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [8cd6645d36](https://linux-hardware.org/?probe=8cd6645d36) | Feb 16, 2023 |
| Biostar       | H61MHB                      | Desktop     | [c8d5686c80](https://linux-hardware.org/?probe=c8d5686c80) | Feb 15, 2023 |
| Biostar       | H61MHB                      | Desktop     | [565eeeb040](https://linux-hardware.org/?probe=565eeeb040) | Feb 15, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| Lenovo        | ThinkPad T410 25376B8       | Notebook    | [fc0430b8fe](https://linux-hardware.org/?probe=fc0430b8fe) | Feb 14, 2023 |
| Lenovo        | ThinkPad Edge 057872G       | Notebook    | [98ed3bb274](https://linux-hardware.org/?probe=98ed3bb274) | Feb 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [cbf6311f2c](https://linux-hardware.org/?probe=cbf6311f2c) | Feb 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a545753206](https://linux-hardware.org/?probe=a545753206) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c7de2e3ca2](https://linux-hardware.org/?probe=c7de2e3ca2) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [47c66d7783](https://linux-hardware.org/?probe=47c66d7783) | Feb 08, 2023 |
| Lenovo        | ThinkPad P51 20HH0002ZA     | Notebook    | [db1061d4db](https://linux-hardware.org/?probe=db1061d4db) | Feb 07, 2023 |
| Getac         | S410G4                      | Notebook    | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac         | S410G4                      | Notebook    | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [baf04bdc65](https://linux-hardware.org/?probe=baf04bdc65) | Feb 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cfaa43cc81](https://linux-hardware.org/?probe=cfaa43cc81) | Feb 04, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [135dcf2c12](https://linux-hardware.org/?probe=135dcf2c12) | Feb 02, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [ec3d16bb4e](https://linux-hardware.org/?probe=ec3d16bb4e) | Feb 01, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [50c552026e](https://linux-hardware.org/?probe=50c552026e) | Feb 01, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [9b91cecab9](https://linux-hardware.org/?probe=9b91cecab9) | Jan 31, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [8a5dee0d52](https://linux-hardware.org/?probe=8a5dee0d52) | Jan 27, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a0c1ab03da](https://linux-hardware.org/?probe=a0c1ab03da) | Jan 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [ac467a864d](https://linux-hardware.org/?probe=ac467a864d) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [c49f3c0e92](https://linux-hardware.org/?probe=c49f3c0e92) | Jan 24, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [0cff571f25](https://linux-hardware.org/?probe=0cff571f25) | Jan 24, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [eac6804cbb](https://linux-hardware.org/?probe=eac6804cbb) | Jan 24, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [c4a4bd6895](https://linux-hardware.org/?probe=c4a4bd6895) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4c6da4840e](https://linux-hardware.org/?probe=4c6da4840e) | Jan 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [96f20a9e2f](https://linux-hardware.org/?probe=96f20a9e2f) | Jan 18, 2023 |
| ASRock        | G31M-S                      | Desktop     | [50bc0b52b3](https://linux-hardware.org/?probe=50bc0b52b3) | Jan 18, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [4589a3ea25](https://linux-hardware.org/?probe=4589a3ea25) | Jan 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [217353eb32](https://linux-hardware.org/?probe=217353eb32) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efeae454c8](https://linux-hardware.org/?probe=efeae454c8) | Jan 13, 2023 |
| Dell          | G7 7790                     | Notebook    | [bdaed261a4](https://linux-hardware.org/?probe=bdaed261a4) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [d6e6c13962](https://linux-hardware.org/?probe=d6e6c13962) | Jan 08, 2023 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [a3b2e995a5](https://linux-hardware.org/?probe=a3b2e995a5) | Jan 08, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [69969b5a27](https://linux-hardware.org/?probe=69969b5a27) | Jan 07, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5905bea3a2](https://linux-hardware.org/?probe=5905bea3a2) | Jan 06, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [790f459294](https://linux-hardware.org/?probe=790f459294) | Jan 05, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [7076e737af](https://linux-hardware.org/?probe=7076e737af) | Jan 04, 2023 |
| MSI           | H81M-P33                    | Desktop     | [041ee2fde1](https://linux-hardware.org/?probe=041ee2fde1) | Jan 03, 2023 |
| MECER         | MW10Q16+S                   | Tablet      | [e9e77e2e77](https://linux-hardware.org/?probe=e9e77e2e77) | Jan 03, 2023 |
| HP            | ProBook 450 G0              | Notebook    | [eb2116c5e2](https://linux-hardware.org/?probe=eb2116c5e2) | Jan 03, 2023 |
| Acer          | Aspire R7-572G              | Notebook    | [56e5de8317](https://linux-hardware.org/?probe=56e5de8317) | Jan 03, 2023 |
| Lenovo        | 36DB SDK0J40688 WIN 3424... | All in one  | [ddad62bbcb](https://linux-hardware.org/?probe=ddad62bbcb) | Dec 31, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [03b6f5a97d](https://linux-hardware.org/?probe=03b6f5a97d) | Dec 30, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [ceb89aefed](https://linux-hardware.org/?probe=ceb89aefed) | Dec 30, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [7af9125172](https://linux-hardware.org/?probe=7af9125172) | Dec 29, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [9c28036440](https://linux-hardware.org/?probe=9c28036440) | Dec 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6c67e1435e](https://linux-hardware.org/?probe=6c67e1435e) | Dec 29, 2022 |
| HP            | G62                         | Notebook    | [05ad917600](https://linux-hardware.org/?probe=05ad917600) | Dec 28, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| HP            | 1495                        | Desktop     | [b8e1dc67eb](https://linux-hardware.org/?probe=b8e1dc67eb) | Dec 26, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| ASRock        | G31M-S                      | Desktop     | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| ASRock        | G31M-S                      | Desktop     | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Dell          | MXG071                      | Notebook    | [b999ae7bba](https://linux-hardware.org/?probe=b999ae7bba) | Dec 19, 2022 |
| Dell          | MXG071                      | Notebook    | [587b5fb932](https://linux-hardware.org/?probe=587b5fb932) | Dec 19, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [5de13fdffa](https://linux-hardware.org/?probe=5de13fdffa) | Dec 19, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [98fe52d91e](https://linux-hardware.org/?probe=98fe52d91e) | Dec 17, 2022 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [3f4e01746b](https://linux-hardware.org/?probe=3f4e01746b) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [9768b1fe82](https://linux-hardware.org/?probe=9768b1fe82) | Dec 16, 2022 |
| MECER         | CA11Q5_PRO                  | Notebook    | [b8d784f0ef](https://linux-hardware.org/?probe=b8d784f0ef) | Dec 16, 2022 |
| MECER         | CA11Q5_PRO                  | Notebook    | [e2e6c34fde](https://linux-hardware.org/?probe=e2e6c34fde) | Dec 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [facc218586](https://linux-hardware.org/?probe=facc218586) | Dec 15, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [f384f924ee](https://linux-hardware.org/?probe=f384f924ee) | Dec 12, 2022 |
| IBM           | M97IP SIT                   | Desktop     | [c4041b26f3](https://linux-hardware.org/?probe=c4041b26f3) | Dec 11, 2022 |
| LG Electro... | C500                        | Notebook    | [078e13cadd](https://linux-hardware.org/?probe=078e13cadd) | Dec 08, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [969406ce12](https://linux-hardware.org/?probe=969406ce12) | Dec 08, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [87ecb2b41d](https://linux-hardware.org/?probe=87ecb2b41d) | Dec 07, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [07aa2d3665](https://linux-hardware.org/?probe=07aa2d3665) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [51120805b1](https://linux-hardware.org/?probe=51120805b1) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [7a809e9dbd](https://linux-hardware.org/?probe=7a809e9dbd) | Dec 02, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| Standard      | Unknown                     | Notebook    | [723d9c3551](https://linux-hardware.org/?probe=723d9c3551) | Nov 30, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [c0e4685d23](https://linux-hardware.org/?probe=c0e4685d23) | Nov 30, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [cbae74a53a](https://linux-hardware.org/?probe=cbae74a53a) | Nov 29, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [4f13d9a2cc](https://linux-hardware.org/?probe=4f13d9a2cc) | Nov 29, 2022 |
| MECER         | YA13Q20-DP_PRO              | Notebook    | [c51a900a73](https://linux-hardware.org/?probe=c51a900a73) | Nov 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [f735b3e731](https://linux-hardware.org/?probe=f735b3e731) | Nov 23, 2022 |
| Unknown       | Apple Mac mini (M1, 2020... | Mini pc     | [f6634d3a58](https://linux-hardware.org/?probe=f6634d3a58) | Nov 21, 2022 |
| MECER         | YA13Q20-DP_PRO              | Notebook    | [81cdfb4100](https://linux-hardware.org/?probe=81cdfb4100) | Nov 20, 2022 |
| MSI           | H410M-A PRO                 | Desktop     | [36716fb1f4](https://linux-hardware.org/?probe=36716fb1f4) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| Unknown       | Apple Mac mini (M1, 2020... | Mini pc     | [c2b90b8fc8](https://linux-hardware.org/?probe=c2b90b8fc8) | Nov 14, 2022 |
| HP            | Unknown                     | Notebook    | [1a144cae82](https://linux-hardware.org/?probe=1a144cae82) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [7af4696c1b](https://linux-hardware.org/?probe=7af4696c1b) | Nov 12, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [13286af46e](https://linux-hardware.org/?probe=13286af46e) | Nov 10, 2022 |
| RIZZEN        | NOVABOOK R40                | Notebook    | [84890252a6](https://linux-hardware.org/?probe=84890252a6) | Nov 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c62cbe8eb5](https://linux-hardware.org/?probe=c62cbe8eb5) | Nov 08, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [b65108d66e](https://linux-hardware.org/?probe=b65108d66e) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [032920f109](https://linux-hardware.org/?probe=032920f109) | Nov 02, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [d81e8b3ea2](https://linux-hardware.org/?probe=d81e8b3ea2) | Nov 01, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [a3abf820e1](https://linux-hardware.org/?probe=a3abf820e1) | Oct 31, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [53754d84e7](https://linux-hardware.org/?probe=53754d84e7) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [99ac55823d](https://linux-hardware.org/?probe=99ac55823d) | Oct 29, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [560f96a33a](https://linux-hardware.org/?probe=560f96a33a) | Oct 28, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [a5c7ddd00c](https://linux-hardware.org/?probe=a5c7ddd00c) | Oct 25, 2022 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [0d42e2c113](https://linux-hardware.org/?probe=0d42e2c113) | Oct 24, 2022 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [7c3c3f8b72](https://linux-hardware.org/?probe=7c3c3f8b72) | Oct 24, 2022 |
| Mustek        | Z140C                       | Notebook    | [9188dbd3a5](https://linux-hardware.org/?probe=9188dbd3a5) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| HP            | 2000                        | Notebook    | [6bb35d5fe9](https://linux-hardware.org/?probe=6bb35d5fe9) | Oct 21, 2022 |
| HP            | Unknown                     | Notebook    | [3b5effbcc5](https://linux-hardware.org/?probe=3b5effbcc5) | Oct 20, 2022 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [abfee9c5f7](https://linux-hardware.org/?probe=abfee9c5f7) | Oct 18, 2022 |
| LG Electro... | C500                        | Notebook    | [f688cc0536](https://linux-hardware.org/?probe=f688cc0536) | Oct 18, 2022 |
| HP            | 339A                        | Desktop     | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| Mustek        | Z140C                       | Notebook    | [02a81c2c1f](https://linux-hardware.org/?probe=02a81c2c1f) | Oct 16, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [a5a47837e5](https://linux-hardware.org/?probe=a5a47837e5) | Oct 15, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [614d4b0dc3](https://linux-hardware.org/?probe=614d4b0dc3) | Oct 15, 2022 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [2a1c89201f](https://linux-hardware.org/?probe=2a1c89201f) | Oct 12, 2022 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [e952835a2f](https://linux-hardware.org/?probe=e952835a2f) | Oct 12, 2022 |
| HP            | 1495                        | Desktop     | [7125a7b95b](https://linux-hardware.org/?probe=7125a7b95b) | Oct 11, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | Notebook    | [9f2e301993](https://linux-hardware.org/?probe=9f2e301993) | Oct 10, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | Notebook    | [af662698b9](https://linux-hardware.org/?probe=af662698b9) | Oct 10, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [22b023a49f](https://linux-hardware.org/?probe=22b023a49f) | Oct 10, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [62e134c294](https://linux-hardware.org/?probe=62e134c294) | Oct 09, 2022 |
| HP            | 1495                        | Desktop     | [bf20b30af3](https://linux-hardware.org/?probe=bf20b30af3) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [b95ff9d622](https://linux-hardware.org/?probe=b95ff9d622) | Oct 02, 2022 |
| Dell          | Latitude E5250              | Notebook    | [aeb221e727](https://linux-hardware.org/?probe=aeb221e727) | Oct 01, 2022 |
| Dell          | Latitude E5250              | Notebook    | [43f7cf1b59](https://linux-hardware.org/?probe=43f7cf1b59) | Oct 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [583fe6d90d](https://linux-hardware.org/?probe=583fe6d90d) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2ad6238f03](https://linux-hardware.org/?probe=2ad6238f03) | Sep 25, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [753d8c4211](https://linux-hardware.org/?probe=753d8c4211) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Toshiba       | Satellite C850-F21B         | Notebook    | [6d336c1e89](https://linux-hardware.org/?probe=6d336c1e89) | Sep 23, 2022 |
| Toshiba       | Satellite C850-F21B         | Notebook    | [dc1e853bbf](https://linux-hardware.org/?probe=dc1e853bbf) | Sep 23, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d13fb4e622](https://linux-hardware.org/?probe=d13fb4e622) | Sep 19, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [db02122f3d](https://linux-hardware.org/?probe=db02122f3d) | Sep 14, 2022 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [21744558cb](https://linux-hardware.org/?probe=21744558cb) | Sep 12, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [b85068c001](https://linux-hardware.org/?probe=b85068c001) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [0612f13b64](https://linux-hardware.org/?probe=0612f13b64) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fa0d296a6d](https://linux-hardware.org/?probe=fa0d296a6d) | Sep 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6566bc7d09](https://linux-hardware.org/?probe=6566bc7d09) | Sep 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [63efab9aef](https://linux-hardware.org/?probe=63efab9aef) | Aug 30, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | Desktop     | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| Intel         | DQ965GF AAD41676-601        | Desktop     | [a163a7fc6d](https://linux-hardware.org/?probe=a163a7fc6d) | Aug 25, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [176c458f3a](https://linux-hardware.org/?probe=176c458f3a) | Aug 25, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [42cd205688](https://linux-hardware.org/?probe=42cd205688) | Aug 25, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| MSI           | MS-7528                     | Desktop     | [723f567e19](https://linux-hardware.org/?probe=723f567e19) | Aug 19, 2022 |
| MSI           | MS-7528                     | Desktop     | [4d549f68ce](https://linux-hardware.org/?probe=4d549f68ce) | Aug 19, 2022 |
| HP            | 1497                        | Desktop     | [c0b6759020](https://linux-hardware.org/?probe=c0b6759020) | Aug 16, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [81b8b0400d](https://linux-hardware.org/?probe=81b8b0400d) | Aug 14, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [d7550029db](https://linux-hardware.org/?probe=d7550029db) | Aug 12, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [a9b5863c1a](https://linux-hardware.org/?probe=a9b5863c1a) | Aug 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [a6b418356a](https://linux-hardware.org/?probe=a6b418356a) | Aug 11, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [42f35776a6](https://linux-hardware.org/?probe=42f35776a6) | Aug 10, 2022 |
| Intel         | DP35DP AAD81073-207         | Desktop     | [3f55eb1ae4](https://linux-hardware.org/?probe=3f55eb1ae4) | Aug 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [51ba94d8f9](https://linux-hardware.org/?probe=51ba94d8f9) | Aug 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [c28a56202d](https://linux-hardware.org/?probe=c28a56202d) | Aug 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [dc6f7b4c01](https://linux-hardware.org/?probe=dc6f7b4c01) | Aug 09, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3a348c35e7](https://linux-hardware.org/?probe=3a348c35e7) | Aug 09, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [0ad516c20b](https://linux-hardware.org/?probe=0ad516c20b) | Aug 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f79c49386d](https://linux-hardware.org/?probe=f79c49386d) | Aug 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2d4b30ec72](https://linux-hardware.org/?probe=2d4b30ec72) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | Notebook    | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Lenovo        | ThinkPad T540p 20BFA06P0... | Notebook    | [2f51f6572f](https://linux-hardware.org/?probe=2f51f6572f) | Aug 06, 2022 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [3d64e8f950](https://linux-hardware.org/?probe=3d64e8f950) | Aug 04, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [0012f5d4c5](https://linux-hardware.org/?probe=0012f5d4c5) | Aug 01, 2022 |
| HP            | ProBook 4310s               | Notebook    | [d15b493637](https://linux-hardware.org/?probe=d15b493637) | Jul 31, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [28b8a96420](https://linux-hardware.org/?probe=28b8a96420) | Jul 31, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [8fe6a402e7](https://linux-hardware.org/?probe=8fe6a402e7) | Jul 30, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [ec939adba9](https://linux-hardware.org/?probe=ec939adba9) | Jul 30, 2022 |
| Lenovo        | ThinkPad T540p 20BFA06P0... | Notebook    | [824d231d52](https://linux-hardware.org/?probe=824d231d52) | Jul 29, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [4a49386ad2](https://linux-hardware.org/?probe=4a49386ad2) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b3e3c79dae](https://linux-hardware.org/?probe=b3e3c79dae) | Jul 22, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [85ae8afd7d](https://linux-hardware.org/?probe=85ae8afd7d) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c0e1145ccf](https://linux-hardware.org/?probe=c0e1145ccf) | Jul 21, 2022 |
| Acer          | Veriton M290                | Desktop     | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [69bd4cdcd9](https://linux-hardware.org/?probe=69bd4cdcd9) | Jul 19, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [797f0ea7fe](https://linux-hardware.org/?probe=797f0ea7fe) | Jul 18, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [baa6fdeed9](https://linux-hardware.org/?probe=baa6fdeed9) | Jul 13, 2022 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [3d3076977a](https://linux-hardware.org/?probe=3d3076977a) | Jul 12, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [320a4240ce](https://linux-hardware.org/?probe=320a4240ce) | Jul 12, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [292a5032e3](https://linux-hardware.org/?probe=292a5032e3) | Jul 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [d234e8543d](https://linux-hardware.org/?probe=d234e8543d) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| Dell          | Latitude E6500              | Notebook    | [e1ad93da4a](https://linux-hardware.org/?probe=e1ad93da4a) | Jul 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [0d90a39160](https://linux-hardware.org/?probe=0d90a39160) | Jul 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [0a4fd044e4](https://linux-hardware.org/?probe=0a4fd044e4) | Jul 10, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [25b5baa226](https://linux-hardware.org/?probe=25b5baa226) | Jul 10, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [670abf3d2b](https://linux-hardware.org/?probe=670abf3d2b) | Jul 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [274f459142](https://linux-hardware.org/?probe=274f459142) | Jul 07, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [48a83358b5](https://linux-hardware.org/?probe=48a83358b5) | Jul 06, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [ae5c00cbd0](https://linux-hardware.org/?probe=ae5c00cbd0) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1c5025c952](https://linux-hardware.org/?probe=1c5025c952) | Jul 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4178b8c79f](https://linux-hardware.org/?probe=4178b8c79f) | Jun 28, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [1571a4ab8e](https://linux-hardware.org/?probe=1571a4ab8e) | Jun 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6338462156](https://linux-hardware.org/?probe=6338462156) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | Desktop     | [1faf7dc08f](https://linux-hardware.org/?probe=1faf7dc08f) | Jun 25, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | Desktop     | [87e5572caa](https://linux-hardware.org/?probe=87e5572caa) | Jun 24, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [e2790ebf7e](https://linux-hardware.org/?probe=e2790ebf7e) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [c99aceab3b](https://linux-hardware.org/?probe=c99aceab3b) | Jun 23, 2022 |
| Dell          | Latitude 5490               | Notebook    | [f0726860d4](https://linux-hardware.org/?probe=f0726860d4) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [3d2faf0e14](https://linux-hardware.org/?probe=3d2faf0e14) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Biostar       | H81MLV3                     | Desktop     | [d24427bbc8](https://linux-hardware.org/?probe=d24427bbc8) | Jun 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4dc736e2b5](https://linux-hardware.org/?probe=4dc736e2b5) | Jun 16, 2022 |
| Nvidia        | MCP73                       | Desktop     | [4af86ef214](https://linux-hardware.org/?probe=4af86ef214) | Jun 15, 2022 |
| Nvidia        | MCP73                       | Desktop     | [bc4b2de5bc](https://linux-hardware.org/?probe=bc4b2de5bc) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [bf09de57ad](https://linux-hardware.org/?probe=bf09de57ad) | Jun 14, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [33c22b2507](https://linux-hardware.org/?probe=33c22b2507) | Jun 13, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [a776aa706c](https://linux-hardware.org/?probe=a776aa706c) | Jun 13, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [1908660d1a](https://linux-hardware.org/?probe=1908660d1a) | Jun 13, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [8c47e36905](https://linux-hardware.org/?probe=8c47e36905) | Jun 13, 2022 |
| Radxa         | Zero                        | Soc         | [8b8b6527f5](https://linux-hardware.org/?probe=8b8b6527f5) | Jun 12, 2022 |
| Supermicro    | X8STi                       | Desktop     | [d99d775afe](https://linux-hardware.org/?probe=d99d775afe) | Jun 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a5474363da](https://linux-hardware.org/?probe=a5474363da) | Jun 12, 2022 |
| Lenovo        | E50-70 80JA                 | Notebook    | [2eb0d9bb23](https://linux-hardware.org/?probe=2eb0d9bb23) | Jun 11, 2022 |
| Intel         | DQ965GF AAD41676-601        | Desktop     | [13eadd3c2f](https://linux-hardware.org/?probe=13eadd3c2f) | Jun 10, 2022 |
| Lenovo        | E50-70 80JA                 | Notebook    | [1391106844](https://linux-hardware.org/?probe=1391106844) | Jun 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [cf46fd5c4e](https://linux-hardware.org/?probe=cf46fd5c4e) | Jun 03, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [94db4f10be](https://linux-hardware.org/?probe=94db4f10be) | Jun 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ee38b0dd57](https://linux-hardware.org/?probe=ee38b0dd57) | Jun 02, 2022 |
| Dell          | G5 5590                     | Notebook    | [4e53892479](https://linux-hardware.org/?probe=4e53892479) | Jun 02, 2022 |
| HP            | 871A                        | Mini pc     | [5710666139](https://linux-hardware.org/?probe=5710666139) | Jun 01, 2022 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [923699ceec](https://linux-hardware.org/?probe=923699ceec) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | Latitude E6400              | Notebook    | [d70c53a9df](https://linux-hardware.org/?probe=d70c53a9df) | May 31, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Dell          | Latitude 3410               | Notebook    | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1eecb7a012](https://linux-hardware.org/?probe=1eecb7a012) | May 26, 2022 |
| HP            | 635                         | Notebook    | [79aa62cc98](https://linux-hardware.org/?probe=79aa62cc98) | May 25, 2022 |
| HP            | 635                         | Notebook    | [f97ec34a67](https://linux-hardware.org/?probe=f97ec34a67) | May 24, 2022 |
| LG Electro... | C500                        | Notebook    | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [6c4aff8f5f](https://linux-hardware.org/?probe=6c4aff8f5f) | May 18, 2022 |
| Dell          | Precision 3520              | Notebook    | [9e2b1878d1](https://linux-hardware.org/?probe=9e2b1878d1) | May 18, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8026841674](https://linux-hardware.org/?probe=8026841674) | May 15, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| Mustek6376... | 945GZT-M ECS                | Desktop     | [0d5f40920b](https://linux-hardware.org/?probe=0d5f40920b) | May 14, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| Standard      | Unknown                     | Notebook    | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| Dell          | Latitude 5490               | Notebook    | [9445f416cb](https://linux-hardware.org/?probe=9445f416cb) | Apr 30, 2022 |
| Dell          | Latitude 5520               | Notebook    | [d35917a603](https://linux-hardware.org/?probe=d35917a603) | Apr 29, 2022 |
| Dell          | Latitude 5520               | Notebook    | [9851c7847d](https://linux-hardware.org/?probe=9851c7847d) | Apr 29, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [9b78e9af72](https://linux-hardware.org/?probe=9b78e9af72) | Apr 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [fd2d8cc4f6](https://linux-hardware.org/?probe=fd2d8cc4f6) | Apr 29, 2022 |
| HP            | 871A                        | Mini pc     | [2072675717](https://linux-hardware.org/?probe=2072675717) | Apr 28, 2022 |
| HP            | ProBook 4310s               | Notebook    | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [009a9c8ce0](https://linux-hardware.org/?probe=009a9c8ce0) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4a76d57188](https://linux-hardware.org/?probe=4a76d57188) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ee546b53aa](https://linux-hardware.org/?probe=ee546b53aa) | Apr 23, 2022 |
| Proline       | V146A                       | Notebook    | [30cc5fb7c1](https://linux-hardware.org/?probe=30cc5fb7c1) | Apr 22, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [b0dc5471af](https://linux-hardware.org/?probe=b0dc5471af) | Apr 22, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [6e37f18366](https://linux-hardware.org/?probe=6e37f18366) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b251d7f8e6](https://linux-hardware.org/?probe=b251d7f8e6) | Apr 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [a8af23856d](https://linux-hardware.org/?probe=a8af23856d) | Apr 20, 2022 |
| Toshiba       | Satellite C850-F31Q         | Notebook    | [e7a2a2ff69](https://linux-hardware.org/?probe=e7a2a2ff69) | Apr 19, 2022 |
| MECER         | YA13Q20-DP_PRO              | Notebook    | [d4cf4e840f](https://linux-hardware.org/?probe=d4cf4e840f) | Apr 18, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [00dc9c3cca](https://linux-hardware.org/?probe=00dc9c3cca) | Apr 18, 2022 |
| Dell          | Latitude 3550               | Notebook    | [03ed6ab7b4](https://linux-hardware.org/?probe=03ed6ab7b4) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| HP            | Presario CQ57               | Notebook    | [110b597e47](https://linux-hardware.org/?probe=110b597e47) | Apr 14, 2022 |
| Dell          | Latitude 3550               | Notebook    | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [26be53ebd1](https://linux-hardware.org/?probe=26be53ebd1) | Apr 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [af56c63db4](https://linux-hardware.org/?probe=af56c63db4) | Apr 12, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [1aee3c0b22](https://linux-hardware.org/?probe=1aee3c0b22) | Apr 12, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6565c955db](https://linux-hardware.org/?probe=6565c955db) | Apr 12, 2022 |
| NCR           | Pocono BIOS.5.1             | Desktop     | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Intel         | DQ965GF AAD41676-601        | Desktop     | [61fca7acbc](https://linux-hardware.org/?probe=61fca7acbc) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f6c87488b0](https://linux-hardware.org/?probe=f6c87488b0) | Apr 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [48f70d4c5a](https://linux-hardware.org/?probe=48f70d4c5a) | Apr 05, 2022 |
| MSI           | X58M                        | Desktop     | [d4146d0724](https://linux-hardware.org/?probe=d4146d0724) | Apr 05, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [6354cfe078](https://linux-hardware.org/?probe=6354cfe078) | Apr 04, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [1395229a99](https://linux-hardware.org/?probe=1395229a99) | Apr 04, 2022 |
| Dell          | 0FPP7F A00                  | Desktop     | [8e8bee474f](https://linux-hardware.org/?probe=8e8bee474f) | Apr 03, 2022 |
| HP            | 871A                        | Mini pc     | [b71bc66f21](https://linux-hardware.org/?probe=b71bc66f21) | Apr 02, 2022 |
| Dell          | Latitude 5500               | Notebook    | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| CONNEX        | L1470                       | Notebook    | [6c1aaac1ee](https://linux-hardware.org/?probe=6c1aaac1ee) | Apr 02, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | Notebook    | [00630dc1b2](https://linux-hardware.org/?probe=00630dc1b2) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | Notebook    | [373ac41605](https://linux-hardware.org/?probe=373ac41605) | Apr 01, 2022 |
| ASUSTek       | UL80VT                      | Notebook    | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [af3543aaed](https://linux-hardware.org/?probe=af3543aaed) | Mar 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [cb353468c2](https://linux-hardware.org/?probe=cb353468c2) | Mar 28, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [e0b9178226](https://linux-hardware.org/?probe=e0b9178226) | Mar 28, 2022 |
| HP            | Pavilion g6                 | Notebook    | [79ebe026b7](https://linux-hardware.org/?probe=79ebe026b7) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [74a1c6bd00](https://linux-hardware.org/?probe=74a1c6bd00) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [e352bc299f](https://linux-hardware.org/?probe=e352bc299f) | Mar 26, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [2a333a0767](https://linux-hardware.org/?probe=2a333a0767) | Mar 25, 2022 |
| Dell          | Latitude E5540              | Notebook    | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da34cf7e5c](https://linux-hardware.org/?probe=da34cf7e5c) | Mar 24, 2022 |
| ASUSTek       | Strix GL704GV_GL704GV       | Notebook    | [87c17cc6e1](https://linux-hardware.org/?probe=87c17cc6e1) | Mar 22, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [26a88b6d1f](https://linux-hardware.org/?probe=26a88b6d1f) | Mar 21, 2022 |
| Dell          | Latitude 5420               | Notebook    | [b1a1e20ab3](https://linux-hardware.org/?probe=b1a1e20ab3) | Mar 21, 2022 |
| Lenovo        | ThinkPad 20LB000DZA         | Notebook    | [e4b122e82a](https://linux-hardware.org/?probe=e4b122e82a) | Mar 21, 2022 |
| Lenovo        | ThinkPad 20LB000DZA         | Notebook    | [879224cf79](https://linux-hardware.org/?probe=879224cf79) | Mar 20, 2022 |
| Biostar       | G41D3+                      | Desktop     | [8d6a4e54b1](https://linux-hardware.org/?probe=8d6a4e54b1) | Mar 20, 2022 |
| Lenovo        | ThinkPad T520 424067G       | Notebook    | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| Biostar       | Hi-Fi H61S3                 | Desktop     | [469edf935f](https://linux-hardware.org/?probe=469edf935f) | Mar 14, 2022 |
| Dell          | Latitude 3550               | Notebook    | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | Notebook    | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [e6d7592af0](https://linux-hardware.org/?probe=e6d7592af0) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [65026cfb9e](https://linux-hardware.org/?probe=65026cfb9e) | Mar 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7557102b76](https://linux-hardware.org/?probe=7557102b76) | Mar 08, 2022 |
| HP            | Laptop 14 14s-dq1008ni      | Notebook    | [8184627283](https://linux-hardware.org/?probe=8184627283) | Mar 07, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [87bcae98bc](https://linux-hardware.org/?probe=87bcae98bc) | Mar 07, 2022 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [8aa740825f](https://linux-hardware.org/?probe=8aa740825f) | Mar 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [0e9a8aa6cc](https://linux-hardware.org/?probe=0e9a8aa6cc) | Mar 06, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| Acer          | Aspire VN7-591G             | Notebook    | [57452c9459](https://linux-hardware.org/?probe=57452c9459) | Mar 03, 2022 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [e2956753b7](https://linux-hardware.org/?probe=e2956753b7) | Mar 02, 2022 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [ccf1a5fa76](https://linux-hardware.org/?probe=ccf1a5fa76) | Mar 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [f10ea4bbca](https://linux-hardware.org/?probe=f10ea4bbca) | Mar 02, 2022 |
| Dell          | Precision 3520              | Notebook    | [4b9a52ac5c](https://linux-hardware.org/?probe=4b9a52ac5c) | Feb 24, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [9e1f07c164](https://linux-hardware.org/?probe=9e1f07c164) | Feb 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8e2cd5844e](https://linux-hardware.org/?probe=8e2cd5844e) | Feb 21, 2022 |
| HP            | 1494                        | Desktop     | [f2b67d46d0](https://linux-hardware.org/?probe=f2b67d46d0) | Feb 19, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4b25f5d025](https://linux-hardware.org/?probe=4b25f5d025) | Feb 19, 2022 |
| Dell          | Latitude D630               | Notebook    | [e427bda7a4](https://linux-hardware.org/?probe=e427bda7a4) | Feb 17, 2022 |
| Dell          | Latitude D630               | Notebook    | [bca39271ba](https://linux-hardware.org/?probe=bca39271ba) | Feb 17, 2022 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [5ca51d5bb5](https://linux-hardware.org/?probe=5ca51d5bb5) | Feb 17, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [e0b1929884](https://linux-hardware.org/?probe=e0b1929884) | Feb 17, 2022 |
| Acer          | Predator G9-793             | Notebook    | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| Sony          | VPCEH38FG                   | Notebook    | [15472f67f5](https://linux-hardware.org/?probe=15472f67f5) | Feb 15, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [5c4a8043b1](https://linux-hardware.org/?probe=5c4a8043b1) | Feb 15, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [aee089a0aa](https://linux-hardware.org/?probe=aee089a0aa) | Feb 14, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [469ab361d5](https://linux-hardware.org/?probe=469ab361d5) | Feb 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [0d9d3a0b9b](https://linux-hardware.org/?probe=0d9d3a0b9b) | Feb 12, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [1447e1f0e6](https://linux-hardware.org/?probe=1447e1f0e6) | Feb 11, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [456d12240c](https://linux-hardware.org/?probe=456d12240c) | Feb 11, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [305921eee8](https://linux-hardware.org/?probe=305921eee8) | Feb 11, 2022 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [078b45782e](https://linux-hardware.org/?probe=078b45782e) | Feb 11, 2022 |
| System76      | Oryx Pro                    | Notebook    | [f8437eee6d](https://linux-hardware.org/?probe=f8437eee6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [80b214a273](https://linux-hardware.org/?probe=80b214a273) | Feb 10, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [b29422e3cd](https://linux-hardware.org/?probe=b29422e3cd) | Feb 10, 2022 |
| HP            | 1497                        | Desktop     | [3781103124](https://linux-hardware.org/?probe=3781103124) | Feb 09, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4e741a6acc](https://linux-hardware.org/?probe=4e741a6acc) | Feb 08, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [006afe98fe](https://linux-hardware.org/?probe=006afe98fe) | Feb 07, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b4fe3a7a24](https://linux-hardware.org/?probe=b4fe3a7a24) | Feb 07, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [ff87ac3184](https://linux-hardware.org/?probe=ff87ac3184) | Feb 07, 2022 |
| HP            | 635                         | Notebook    | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [66fb2bc907](https://linux-hardware.org/?probe=66fb2bc907) | Feb 06, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [becd915336](https://linux-hardware.org/?probe=becd915336) | Feb 04, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [e514d0d302](https://linux-hardware.org/?probe=e514d0d302) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [3df622872c](https://linux-hardware.org/?probe=3df622872c) | Feb 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [4a1bfbe60f](https://linux-hardware.org/?probe=4a1bfbe60f) | Feb 01, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Dell          | Latitude E6220              | Notebook    | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Toshiba       | TECRA A10                   | Notebook    | [bdaff089b2](https://linux-hardware.org/?probe=bdaff089b2) | Jan 28, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [94eb262136](https://linux-hardware.org/?probe=94eb262136) | Jan 28, 2022 |
| I-Life Dig... | ZED BOOK II                 | Tablet      | [731ad572d1](https://linux-hardware.org/?probe=731ad572d1) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [d66879ebac](https://linux-hardware.org/?probe=d66879ebac) | Jan 27, 2022 |
| Intel         | H81                         | Desktop     | [1f7ff2e980](https://linux-hardware.org/?probe=1f7ff2e980) | Jan 26, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [80295dd814](https://linux-hardware.org/?probe=80295dd814) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3b58afceea](https://linux-hardware.org/?probe=3b58afceea) | Jan 21, 2022 |
| WinSome       | A14C .B005                  | Notebook    | [d685b78944](https://linux-hardware.org/?probe=d685b78944) | Jan 19, 2022 |
| Dell          | Latitude D630               | Notebook    | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [72d6b552aa](https://linux-hardware.org/?probe=72d6b552aa) | Jan 17, 2022 |
| ECS           | G31T-M7                     | Desktop     | [12ad49d909](https://linux-hardware.org/?probe=12ad49d909) | Jan 16, 2022 |
| ECS           | G31T-M7                     | Desktop     | [5c10976292](https://linux-hardware.org/?probe=5c10976292) | Jan 16, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES0... | Convertible | [c7eaebd796](https://linux-hardware.org/?probe=c7eaebd796) | Jan 16, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES0... | Convertible | [d8c5bf5691](https://linux-hardware.org/?probe=d8c5bf5691) | Jan 16, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c9dbc0c289](https://linux-hardware.org/?probe=c9dbc0c289) | Jan 14, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e36e312cf4](https://linux-hardware.org/?probe=e36e312cf4) | Jan 09, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [d187087325](https://linux-hardware.org/?probe=d187087325) | Jan 09, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [32cae94f00](https://linux-hardware.org/?probe=32cae94f00) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [c103969fdf](https://linux-hardware.org/?probe=c103969fdf) | Jan 06, 2022 |
| HP            | 2000                        | Notebook    | [3c3f60019b](https://linux-hardware.org/?probe=3c3f60019b) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 1294BL5         | Notebook    | [2cd6f5fbb0](https://linux-hardware.org/?probe=2cd6f5fbb0) | Jan 01, 2022 |
| Biostar       | Hi-Fi H61S3                 | Desktop     | [6d68cbf5a2](https://linux-hardware.org/?probe=6d68cbf5a2) | Dec 31, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [8806a9db07](https://linux-hardware.org/?probe=8806a9db07) | Dec 29, 2021 |
| Acer          | TravelMate P255             | Notebook    | [1efdd6ce09](https://linux-hardware.org/?probe=1efdd6ce09) | Dec 26, 2021 |
| Dell          | Latitude 3540               | Notebook    | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Dell          | Latitude E6430              | Notebook    | [c5ac7574f0](https://linux-hardware.org/?probe=c5ac7574f0) | Dec 22, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [6d1e6100ef](https://linux-hardware.org/?probe=6d1e6100ef) | Dec 21, 2021 |
| Acer          | Aspire VN7-572G             | Notebook    | [895dca26b0](https://linux-hardware.org/?probe=895dca26b0) | Dec 21, 2021 |
| Toshiba       | TECRA A10                   | Notebook    | [e5b76a4673](https://linux-hardware.org/?probe=e5b76a4673) | Dec 21, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | Notebook    | [0b0d4dd23f](https://linux-hardware.org/?probe=0b0d4dd23f) | Dec 21, 2021 |
| Lenovo        | ThinkPad E580 20KS001QZA    | Notebook    | [202290bb62](https://linux-hardware.org/?probe=202290bb62) | Dec 20, 2021 |
| Lenovo        | ThinkPad E580 20KS001QZA    | Notebook    | [8a131f560b](https://linux-hardware.org/?probe=8a131f560b) | Dec 20, 2021 |
| HP            | 0A58h                       | Desktop     | [2fce860bda](https://linux-hardware.org/?probe=2fce860bda) | Dec 19, 2021 |
| TYAN Compu... | S7002                       | Server      | [7636863c25](https://linux-hardware.org/?probe=7636863c25) | Dec 18, 2021 |
| TYAN Compu... | S7002                       | Server      | [8cf4b6b014](https://linux-hardware.org/?probe=8cf4b6b014) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | Desktop     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [15e7aaf611](https://linux-hardware.org/?probe=15e7aaf611) | Dec 17, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d678da8a69](https://linux-hardware.org/?probe=d678da8a69) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | Desktop     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | TravelMate 6594             | Notebook    | [d706658ff8](https://linux-hardware.org/?probe=d706658ff8) | Dec 15, 2021 |
| Biostar       | Hi-Fi H61S3                 | Desktop     | [e1362b0ad2](https://linux-hardware.org/?probe=e1362b0ad2) | Dec 14, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [b93d5f0c9c](https://linux-hardware.org/?probe=b93d5f0c9c) | Dec 14, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [f1213e164f](https://linux-hardware.org/?probe=f1213e164f) | Dec 13, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ebf80cd948](https://linux-hardware.org/?probe=ebf80cd948) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | Notebook    | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [1e9841c0eb](https://linux-hardware.org/?probe=1e9841c0eb) | Dec 12, 2021 |
| TCL Commun... | 8085                        | Notebook    | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Precision M6800             | Notebook    | [da95c95a07](https://linux-hardware.org/?probe=da95c95a07) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [d0e3422cba](https://linux-hardware.org/?probe=d0e3422cba) | Dec 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dde283bed5](https://linux-hardware.org/?probe=dde283bed5) | Dec 07, 2021 |
| Dell          | Precision M6800             | Notebook    | [3a4d66818c](https://linux-hardware.org/?probe=3a4d66818c) | Dec 07, 2021 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| Dell          | Precision M6800             | Notebook    | [3b4f2f0a57](https://linux-hardware.org/?probe=3b4f2f0a57) | Dec 06, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [a700683a6f](https://linux-hardware.org/?probe=a700683a6f) | Dec 05, 2021 |
| Dell          | Latitude 5590               | Notebook    | [5f9747af05](https://linux-hardware.org/?probe=5f9747af05) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Acer          | Predator G9-793             | Notebook    | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Lenovo        | ThinkPad T580 20L90024ZA    | Notebook    | [6b8493406e](https://linux-hardware.org/?probe=6b8493406e) | Nov 28, 2021 |
| Lenovo        | ThinkPad T580 20L90024ZA    | Notebook    | [4a398efa1b](https://linux-hardware.org/?probe=4a398efa1b) | Nov 28, 2021 |
| Gigabyte      | XP-M5S661GX                 | Desktop     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| HP            | ProBook 4310s               | Notebook    | [9f467df8a8](https://linux-hardware.org/?probe=9f467df8a8) | Nov 27, 2021 |
| HP            | ProBook 4310s               | Notebook    | [6d339b7843](https://linux-hardware.org/?probe=6d339b7843) | Nov 27, 2021 |
| HP            | 1497                        | Desktop     | [9a7d6ebc52](https://linux-hardware.org/?probe=9a7d6ebc52) | Nov 26, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7d4b6453e9](https://linux-hardware.org/?probe=7d4b6453e9) | Nov 24, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [ce783dccca](https://linux-hardware.org/?probe=ce783dccca) | Nov 24, 2021 |
| LattePanda    | Delta                       | Notebook    | [5950a5a8ac](https://linux-hardware.org/?probe=5950a5a8ac) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e9b4b7ecba](https://linux-hardware.org/?probe=e9b4b7ecba) | Nov 24, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [ea27790fc4](https://linux-hardware.org/?probe=ea27790fc4) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | Desktop     | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [7ddf0db7ec](https://linux-hardware.org/?probe=7ddf0db7ec) | Nov 22, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [e0f0471cee](https://linux-hardware.org/?probe=e0f0471cee) | Nov 20, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | Notebook    | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e8ef916c87](https://linux-hardware.org/?probe=e8ef916c87) | Nov 18, 2021 |
| HP            | Notebook                    | Notebook    | [12d501a930](https://linux-hardware.org/?probe=12d501a930) | Nov 17, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [86d02c7f2c](https://linux-hardware.org/?probe=86d02c7f2c) | Nov 17, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [7114246672](https://linux-hardware.org/?probe=7114246672) | Nov 15, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [2cb8a3b9ff](https://linux-hardware.org/?probe=2cb8a3b9ff) | Nov 15, 2021 |
| HP            | Presario CQ56               | Notebook    | [a514e96472](https://linux-hardware.org/?probe=a514e96472) | Nov 15, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [1515779722](https://linux-hardware.org/?probe=1515779722) | Nov 15, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [b74fb29b9b](https://linux-hardware.org/?probe=b74fb29b9b) | Nov 15, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c62a6022e8](https://linux-hardware.org/?probe=c62a6022e8) | Nov 14, 2021 |
| ASUSTek       | P8P67-M                     | Desktop     | [1cb5f14632](https://linux-hardware.org/?probe=1cb5f14632) | Nov 13, 2021 |
| MSI           | CR72 7ML                    | Notebook    | [9fdd485636](https://linux-hardware.org/?probe=9fdd485636) | Nov 12, 2021 |
| MSI           | CR72 7ML                    | Notebook    | [1165c3e22f](https://linux-hardware.org/?probe=1165c3e22f) | Nov 12, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [b7579cb355](https://linux-hardware.org/?probe=b7579cb355) | Nov 12, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [39e3c646ff](https://linux-hardware.org/?probe=39e3c646ff) | Nov 11, 2021 |
| ASUSTek       | P8P67-M                     | Desktop     | [701e60decc](https://linux-hardware.org/?probe=701e60decc) | Nov 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [62ba7df7ec](https://linux-hardware.org/?probe=62ba7df7ec) | Nov 11, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [383b7f1862](https://linux-hardware.org/?probe=383b7f1862) | Nov 11, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [02f1a55757](https://linux-hardware.org/?probe=02f1a55757) | Nov 08, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [0c1d65f646](https://linux-hardware.org/?probe=0c1d65f646) | Nov 08, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| Dell          | Studio 1735                 | Notebook    | [6a444456ef](https://linux-hardware.org/?probe=6a444456ef) | Nov 06, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [57417d57e3](https://linux-hardware.org/?probe=57417d57e3) | Nov 06, 2021 |
| Gigabyte      | P17FV5                      | Notebook    | [379e023c65](https://linux-hardware.org/?probe=379e023c65) | Nov 04, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [f51fee36d1](https://linux-hardware.org/?probe=f51fee36d1) | Nov 04, 2021 |
| HP            | ProBook 4310s               | Notebook    | [bb95a3f04d](https://linux-hardware.org/?probe=bb95a3f04d) | Nov 03, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [293a751aaf](https://linux-hardware.org/?probe=293a751aaf) | Nov 02, 2021 |
| Gigabyte      | P17FV5                      | Notebook    | [7304aa43c3](https://linux-hardware.org/?probe=7304aa43c3) | Nov 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [4a72082fdb](https://linux-hardware.org/?probe=4a72082fdb) | Nov 01, 2021 |
| Packard Be... | ENTE11HC                    | Notebook    | [e31fe4eef0](https://linux-hardware.org/?probe=e31fe4eef0) | Nov 01, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | Notebook    | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [b0f6309320](https://linux-hardware.org/?probe=b0f6309320) | Oct 31, 2021 |
| MECER         | Z140C+Home                  | Notebook    | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [dd22d96d07](https://linux-hardware.org/?probe=dd22d96d07) | Oct 30, 2021 |
| ASUSTek       | X58C                        | Notebook    | [fdd83a3517](https://linux-hardware.org/?probe=fdd83a3517) | Oct 28, 2021 |
| Dell          | Latitude E5570              | Notebook    | [e7a049a026](https://linux-hardware.org/?probe=e7a049a026) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d43c3cb973](https://linux-hardware.org/?probe=d43c3cb973) | Oct 27, 2021 |
| Biostar       | B350GTN                     | Desktop     | [53c5fd6db4](https://linux-hardware.org/?probe=53c5fd6db4) | Oct 26, 2021 |
| HP            | Presario CQ56               | Notebook    | [10acff551d](https://linux-hardware.org/?probe=10acff551d) | Oct 25, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [eaf7694813](https://linux-hardware.org/?probe=eaf7694813) | Oct 24, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [44b5186950](https://linux-hardware.org/?probe=44b5186950) | Oct 24, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [37ae9a9258](https://linux-hardware.org/?probe=37ae9a9258) | Oct 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [4a961ff6da](https://linux-hardware.org/?probe=4a961ff6da) | Oct 22, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [9bde1214a9](https://linux-hardware.org/?probe=9bde1214a9) | Oct 22, 2021 |
| Dell          | Latitude E6430              | Notebook    | [b127732e59](https://linux-hardware.org/?probe=b127732e59) | Oct 19, 2021 |
| Lenovo        | ThinkCentre M91p 4512A12    | Desktop     | [1ecb7a6910](https://linux-hardware.org/?probe=1ecb7a6910) | Oct 19, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [fcc82222d9](https://linux-hardware.org/?probe=fcc82222d9) | Oct 17, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [d837406f2a](https://linux-hardware.org/?probe=d837406f2a) | Oct 16, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [0a048a009d](https://linux-hardware.org/?probe=0a048a009d) | Oct 15, 2021 |
| Lenovo        | E50-80 80J2                 | Notebook    | [c3d31689ec](https://linux-hardware.org/?probe=c3d31689ec) | Oct 11, 2021 |
| HP            | 81C3                        | Desktop     | [df2caaf484](https://linux-hardware.org/?probe=df2caaf484) | Oct 11, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [a3f3c59edc](https://linux-hardware.org/?probe=a3f3c59edc) | Oct 11, 2021 |
| Acer          | Aspire VN7-792G             | Notebook    | [4985d6b90c](https://linux-hardware.org/?probe=4985d6b90c) | Oct 10, 2021 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [e39ce9ade6](https://linux-hardware.org/?probe=e39ce9ade6) | Oct 09, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [d804de918d](https://linux-hardware.org/?probe=d804de918d) | Oct 08, 2021 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [5a5c0c8f90](https://linux-hardware.org/?probe=5a5c0c8f90) | Oct 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [080e5a9a9f](https://linux-hardware.org/?probe=080e5a9a9f) | Oct 06, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d9b26b9fec](https://linux-hardware.org/?probe=d9b26b9fec) | Oct 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cb307dd929](https://linux-hardware.org/?probe=cb307dd929) | Oct 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f85d75b229](https://linux-hardware.org/?probe=f85d75b229) | Oct 05, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [42a76fbc95](https://linux-hardware.org/?probe=42a76fbc95) | Oct 05, 2021 |
| HP            | 650                         | Notebook    | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [ec92b38160](https://linux-hardware.org/?probe=ec92b38160) | Oct 05, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [65388cbcfc](https://linux-hardware.org/?probe=65388cbcfc) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [97dde270fa](https://linux-hardware.org/?probe=97dde270fa) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| Nvidia        | MCP73                       | Desktop     | [7099e6ef4b](https://linux-hardware.org/?probe=7099e6ef4b) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1585f476de](https://linux-hardware.org/?probe=1585f476de) | Oct 02, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [6b9d5f5444](https://linux-hardware.org/?probe=6b9d5f5444) | Oct 02, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [8fe1edb38b](https://linux-hardware.org/?probe=8fe1edb38b) | Sep 30, 2021 |
| HP            | 1497                        | Desktop     | [a792022089](https://linux-hardware.org/?probe=a792022089) | Sep 30, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e9dd5491e8](https://linux-hardware.org/?probe=e9dd5491e8) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [44d29122aa](https://linux-hardware.org/?probe=44d29122aa) | Sep 28, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [3255b4d143](https://linux-hardware.org/?probe=3255b4d143) | Sep 28, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [7af0b1b5dd](https://linux-hardware.org/?probe=7af0b1b5dd) | Sep 27, 2021 |
| Acer          | TravelMate P255             | Notebook    | [c6b7f1d5d9](https://linux-hardware.org/?probe=c6b7f1d5d9) | Sep 26, 2021 |
| Acer          | Aspire VN7-792G             | Notebook    | [b555c8cd95](https://linux-hardware.org/?probe=b555c8cd95) | Sep 25, 2021 |
| Dell          | Latitude E6220              | Notebook    | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [2da6abda17](https://linux-hardware.org/?probe=2da6abda17) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [9d9796386e](https://linux-hardware.org/?probe=9d9796386e) | Sep 21, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [33781ae35f](https://linux-hardware.org/?probe=33781ae35f) | Sep 21, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [23324e6aed](https://linux-hardware.org/?probe=23324e6aed) | Sep 17, 2021 |
| Acer          | Extensa 2511                | Notebook    | [b38f9bfa33](https://linux-hardware.org/?probe=b38f9bfa33) | Sep 16, 2021 |
| Dell          | Latitude E7440              | Notebook    | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Gigabyte      | H55M-S2H                    | Desktop     | [82fe8d569f](https://linux-hardware.org/?probe=82fe8d569f) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| Dell          | Precision 7550              | Notebook    | [42890f7542](https://linux-hardware.org/?probe=42890f7542) | Sep 10, 2021 |
| Dell          | Precision 7550              | Notebook    | [a4a1a56132](https://linux-hardware.org/?probe=a4a1a56132) | Sep 09, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [03445cb511](https://linux-hardware.org/?probe=03445cb511) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [1ee958abc3](https://linux-hardware.org/?probe=1ee958abc3) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| HP            | Presario CQ56               | Notebook    | [b5666dc71b](https://linux-hardware.org/?probe=b5666dc71b) | Sep 08, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| MSI           | Z170A PC MATE               | Desktop     | [192a0d3f1a](https://linux-hardware.org/?probe=192a0d3f1a) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Dell          | Latitude 7480               | Notebook    | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [beefff4447](https://linux-hardware.org/?probe=beefff4447) | Sep 06, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [43c7b5b039](https://linux-hardware.org/?probe=43c7b5b039) | Sep 06, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| Dell          | 0GM819                      | Desktop     | [f0cc146236](https://linux-hardware.org/?probe=f0cc146236) | Sep 04, 2021 |
| ASUSTek       | G551JM                      | Notebook    | [4309f5e034](https://linux-hardware.org/?probe=4309f5e034) | Sep 04, 2021 |
| ASUSTek       | G551JM                      | Notebook    | [0dad1d056d](https://linux-hardware.org/?probe=0dad1d056d) | Sep 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [866d479f07](https://linux-hardware.org/?probe=866d479f07) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7b86b0dee4](https://linux-hardware.org/?probe=7b86b0dee4) | Sep 03, 2021 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [dc703ecae4](https://linux-hardware.org/?probe=dc703ecae4) | Sep 03, 2021 |
| HP            | Notebook                    | Notebook    | [552535c21e](https://linux-hardware.org/?probe=552535c21e) | Sep 02, 2021 |
| HP            | Notebook                    | Notebook    | [0405b5aa6c](https://linux-hardware.org/?probe=0405b5aa6c) | Sep 02, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [1579919ebb](https://linux-hardware.org/?probe=1579919ebb) | Sep 01, 2021 |
| Intel         | D865GLC AAC28906-407        | Desktop     | [5936f5b3ba](https://linux-hardware.org/?probe=5936f5b3ba) | Sep 01, 2021 |
| HP            | EliteBook 8730w             | Notebook    | [93ee7aecde](https://linux-hardware.org/?probe=93ee7aecde) | Aug 31, 2021 |
| HP            | EliteBook 8730w             | Notebook    | [c99d13438f](https://linux-hardware.org/?probe=c99d13438f) | Aug 30, 2021 |
| Intel         | DH55HC AAE70933-504         | Desktop     | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [87f2a544c5](https://linux-hardware.org/?probe=87f2a544c5) | Aug 30, 2021 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [0b340c6818](https://linux-hardware.org/?probe=0b340c6818) | Aug 29, 2021 |
| HP            | 212B                        | Desktop     | [10646959ce](https://linux-hardware.org/?probe=10646959ce) | Aug 27, 2021 |
| Biostar       | H61MGV3                     | Desktop     | [fa2b470ff5](https://linux-hardware.org/?probe=fa2b470ff5) | Aug 26, 2021 |
| Biostar       | H61MGV3                     | Desktop     | [19eacc88f5](https://linux-hardware.org/?probe=19eacc88f5) | Aug 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 0HH807                      | Desktop     | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| Mustek        | W35xSS_370SS                | Notebook    | [ee70b31c91](https://linux-hardware.org/?probe=ee70b31c91) | Aug 24, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [b28b036f78](https://linux-hardware.org/?probe=b28b036f78) | Aug 22, 2021 |
| HP            | 0A50h                       | Desktop     | [f7ea4959d2](https://linux-hardware.org/?probe=f7ea4959d2) | Aug 21, 2021 |
| Intel         | S5000PSL                    | Server      | [2aea05d635](https://linux-hardware.org/?probe=2aea05d635) | Aug 20, 2021 |
| MSI           | G41M4                       | Desktop     | [c5c2a6945a](https://linux-hardware.org/?probe=c5c2a6945a) | Aug 20, 2021 |
| MSI           | G41M4                       | Desktop     | [3862c2333b](https://linux-hardware.org/?probe=3862c2333b) | Aug 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ef99e18e2](https://linux-hardware.org/?probe=9ef99e18e2) | Aug 19, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [82ff6985ce](https://linux-hardware.org/?probe=82ff6985ce) | Aug 18, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [d9923e15e0](https://linux-hardware.org/?probe=d9923e15e0) | Aug 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f7a1b3b0e4](https://linux-hardware.org/?probe=f7a1b3b0e4) | Aug 18, 2021 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [0a023d2778](https://linux-hardware.org/?probe=0a023d2778) | Aug 17, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [16503fc58a](https://linux-hardware.org/?probe=16503fc58a) | Aug 16, 2021 |
| Dell          | Latitude E6430              | Notebook    | [31491d6a83](https://linux-hardware.org/?probe=31491d6a83) | Aug 15, 2021 |
| Dell          | Latitude 5580               | Notebook    | [1c57f7bb76](https://linux-hardware.org/?probe=1c57f7bb76) | Aug 15, 2021 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a8d4959fde](https://linux-hardware.org/?probe=a8d4959fde) | Aug 14, 2021 |
| MSI           | 970A-G46                    | Desktop     | [1d552fc481](https://linux-hardware.org/?probe=1d552fc481) | Aug 14, 2021 |
| MSI           | 970A-G46                    | Desktop     | [ee8d3d8ed0](https://linux-hardware.org/?probe=ee8d3d8ed0) | Aug 14, 2021 |
| HP            | 3031h                       | Desktop     | [201543483c](https://linux-hardware.org/?probe=201543483c) | Aug 13, 2021 |
| ASUSTek       | Rampage II GENE             | Desktop     | [ec056ad7c5](https://linux-hardware.org/?probe=ec056ad7c5) | Aug 12, 2021 |
| HP            | Pavilion dv4                | Notebook    | [bc1ab4b47e](https://linux-hardware.org/?probe=bc1ab4b47e) | Aug 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [1f6745d6bb](https://linux-hardware.org/?probe=1f6745d6bb) | Aug 11, 2021 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [a771e9b877](https://linux-hardware.org/?probe=a771e9b877) | Aug 11, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| HP            | Pavilion dv4                | Notebook    | [34b7ad0d24](https://linux-hardware.org/?probe=34b7ad0d24) | Aug 09, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [e1a51f61f1](https://linux-hardware.org/?probe=e1a51f61f1) | Aug 08, 2021 |
| Lenovo        | ThinkPad T440p 2000CT0      | Notebook    | [574392d159](https://linux-hardware.org/?probe=574392d159) | Aug 07, 2021 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [cd6e2c268a](https://linux-hardware.org/?probe=cd6e2c268a) | Aug 07, 2021 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [95ed07c904](https://linux-hardware.org/?probe=95ed07c904) | Aug 05, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [cf42c809f2](https://linux-hardware.org/?probe=cf42c809f2) | Aug 04, 2021 |
| MSI           | G31M3-F V2                  | Desktop     | [8f821ac3a7](https://linux-hardware.org/?probe=8f821ac3a7) | Aug 02, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [80d1826ee1](https://linux-hardware.org/?probe=80d1826ee1) | Aug 02, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [ac364c0278](https://linux-hardware.org/?probe=ac364c0278) | Aug 01, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/South_Africa/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 187       | 14.89%  |
| Ubuntu 18.04       | 74        | 5.89%   |
| Ubuntu 22.04       | 73        | 5.81%   |
| Zorin 16           | 42        | 3.34%   |
| KDE neon 20.04     | 30        | 2.39%   |
| Linux Mint 20.3    | 25        | 1.99%   |
| Pop!_OS 21.04      | 23        | 1.83%   |
| Pop!_OS 20.04      | 23        | 1.83%   |
| Linux Mint 19.3    | 22        | 1.75%   |
| Pop!_OS 20.10      | 21        | 1.67%   |
| ArcoLinux Rolling  | 21        | 1.67%   |
| Zorin 15           | 20        | 1.59%   |
| Manjaro            | 20        | 1.59%   |
| Pop!_OS 22.04      | 19        | 1.51%   |
| Linux Mint 20.1    | 19        | 1.51%   |
| Debian 11          | 19        | 1.51%   |
| Ubuntu 21.04       | 18        | 1.43%   |
| Arch Rolling       | 18        | 1.43%   |
| OpenMandriva 4.2   | 17        | 1.35%   |
| Linux Mint 21.1    | 17        | 1.35%   |
| Ubuntu 19.10       | 15        | 1.19%   |
| Linux Mint 20.2    | 14        | 1.11%   |
| Debian 12          | 14        | 1.11%   |
| OpenMandriva 4.3   | 13        | 1.04%   |
| Ubuntu 23.04       | 12        | 0.96%   |
| Ubuntu 20.10       | 12        | 0.96%   |
| Ubuntu 22.10       | 11        | 0.88%   |
| KDE neon 22.04     | 11        | 0.88%   |
| Ubuntu 21.10       | 10        | 0.8%    |
| Ubuntu 19.04       | 10        | 0.8%    |
| Linux Mint 21.2    | 10        | 0.8%    |
| Kubuntu 20.04      | 10        | 0.8%    |
| OpenMandriva 23.03 | 9         | 0.72%   |
| OpenMandriva 23.01 | 9         | 0.72%   |
| Linux Mint 20      | 9         | 0.72%   |
| Fedora 37          | 9         | 0.72%   |
| Pop!_OS 21.10      | 8         | 0.64%   |
| Linux Mint 19      | 8         | 0.64%   |
| Fedora 35          | 8         | 0.64%   |
| Fedora 34          | 8         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 415       | 34.73%  |
| Linux Mint    | 138       | 11.55%  |
| Pop!_OS       | 93        | 7.78%   |
| Zorin         | 64        | 5.36%   |
| OpenMandriva  | 52        | 4.35%   |
| Debian        | 48        | 4.02%   |
| Fedora        | 45        | 3.77%   |
| KDE neon      | 42        | 3.51%   |
| Manjaro       | 29        | 2.43%   |
| Kubuntu       | 28        | 2.34%   |
| Arch          | 25        | 2.09%   |
| ArcoLinux     | 21        | 1.76%   |
| Xubuntu       | 15        | 1.26%   |
| Kali          | 14        | 1.17%   |
| openSUSE      | 11        | 0.92%   |
| Ubuntu Unity  | 10        | 0.84%   |
| ROSA          | 10        | 0.84%   |
| Elementary    | 10        | 0.84%   |
| Endless       | 9         | 0.75%   |
| Clear Linux   | 8         | 0.67%   |
| Lubuntu       | 7         | 0.59%   |
| CentOS        | 6         | 0.5%    |
| Ubuntu Budgie | 5         | 0.42%   |
| LMDE          | 5         | 0.42%   |
| Gentoo        | 5         | 0.42%   |
| EndeavourOS   | 5         | 0.42%   |
| BlackPanther  | 5         | 0.42%   |
| Rocky Linux   | 4         | 0.33%   |
| RHEL          | 4         | 0.33%   |
| Parrot        | 4         | 0.33%   |
| LinuxFX       | 4         | 0.33%   |
| Garuda Linux  | 4         | 0.33%   |
| Xero          | 3         | 0.25%   |
| TUXEDO OS     | 3         | 0.25%   |
| Slackware     | 3         | 0.25%   |
| MX            | 3         | 0.25%   |
| Ubuntu MATE   | 2         | 0.17%   |
| Raspbian      | 2         | 0.17%   |
| Peppermint    | 2         | 0.17%   |
| Nobara        | 2         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 29        | 2.08%   |
| 5.4.0-58-generic         | 16        | 1.15%   |
| 5.15.0-56-generic        | 16        | 1.15%   |
| 5.10.14-desktop-1omv4002 | 15        | 1.07%   |
| 5.4.0-52-generic         | 14        | 1%      |
| 5.16.7-desktop-1omv4003  | 13        | 0.93%   |
| 5.13.0-7614-generic      | 13        | 0.93%   |
| 5.11.0-38-generic        | 13        | 0.93%   |
| 5.11.0-27-generic        | 12        | 0.86%   |
| 5.4.0-72-generic         | 11        | 0.79%   |
| 5.8.0-7642-generic       | 10        | 0.72%   |
| 5.4.0-40-generic         | 10        | 0.72%   |
| 5.15.0-52-generic        | 10        | 0.72%   |
| 5.15.0-48-generic        | 10        | 0.72%   |
| 6.2.6-desktop-1omv2390   | 9         | 0.64%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.64%   |
| 5.8.0-43-generic         | 9         | 0.64%   |
| 5.4.0-29-generic         | 9         | 0.64%   |
| 5.13.0-28-generic        | 9         | 0.64%   |
| 5.11.0-40-generic        | 9         | 0.64%   |
| 5.0.0-37-generic         | 9         | 0.64%   |
| 5.8.0-7630-generic       | 8         | 0.57%   |
| 5.4.0-7634-generic       | 8         | 0.57%   |
| 5.4.0-26-generic         | 8         | 0.57%   |
| 5.19.0-38-generic        | 8         | 0.57%   |
| 5.19.0-35-generic        | 8         | 0.57%   |
| 5.13.0-39-generic        | 8         | 0.57%   |
| 5.11.0-41-generic        | 8         | 0.57%   |
| 5.11.0-25-generic        | 8         | 0.57%   |
| 6.2.6-76060206-generic   | 7         | 0.5%    |
| 5.4.0-7642-generic       | 7         | 0.5%    |
| 5.4.0-73-generic         | 7         | 0.5%    |
| 5.4.0-33-generic         | 7         | 0.5%    |
| 5.4.0-31-generic         | 7         | 0.5%    |
| 5.15.0-58-generic        | 7         | 0.5%    |
| 5.11.0-37-generic        | 7         | 0.5%    |
| 4.15.0-54-generic        | 7         | 0.5%    |
| 6.4.11-desktop-1omv2390  | 6         | 0.43%   |
| 6.1.0-13-amd64           | 6         | 0.43%   |
| 5.8.0-63-generic         | 6         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 240       | 18.48%  |
| 5.15.0  | 118       | 9.08%   |
| 5.11.0  | 95        | 7.31%   |
| 5.8.0   | 85        | 6.54%   |
| 5.13.0  | 72        | 5.54%   |
| 4.15.0  | 68        | 5.23%   |
| 5.3.0   | 50        | 3.85%   |
| 5.19.0  | 45        | 3.46%   |
| 6.2.0   | 36        | 2.77%   |
| 5.10.0  | 30        | 2.31%   |
| 5.0.0   | 25        | 1.92%   |
| 4.18.0  | 25        | 1.92%   |
| 6.1.0   | 21        | 1.62%   |
| 6.2.6   | 17        | 1.31%   |
| 5.10.14 | 15        | 1.15%   |
| 5.16.7  | 14        | 1.08%   |
| 6.1.1   | 12        | 0.92%   |
| 5.14.0  | 11        | 0.85%   |
| 5.17.5  | 10        | 0.77%   |
| 6.4.11  | 8         | 0.62%   |
| 4.19.0  | 7         | 0.54%   |
| 6.5.0   | 6         | 0.46%   |
| 6.4.12  | 5         | 0.38%   |
| 5.15.15 | 5         | 0.38%   |
| 4.4.0   | 5         | 0.38%   |
| 4.18.16 | 5         | 0.38%   |
| 6.0.12  | 4         | 0.31%   |
| 5.18.0  | 4         | 0.31%   |
| 5.14.21 | 4         | 0.31%   |
| 6.6.6   | 3         | 0.23%   |
| 6.1.7   | 3         | 0.23%   |
| 5.9.0   | 3         | 0.23%   |
| 5.6.0   | 3         | 0.23%   |
| 5.16.18 | 3         | 0.23%   |
| 5.16.11 | 3         | 0.23%   |
| 5.15.5  | 3         | 0.23%   |
| 5.15.32 | 3         | 0.23%   |
| 5.14.9  | 3         | 0.23%   |
| 4.9.20  | 3         | 0.23%   |
| 6.6.8   | 2         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 250       | 19.49%  |
| 5.15    | 144       | 11.22%  |
| 5.11    | 103       | 8.03%   |
| 5.8     | 93        | 7.25%   |
| 5.13    | 80        | 6.24%   |
| 4.15    | 68        | 5.3%    |
| 6.2     | 65        | 5.07%   |
| 5.10    | 61        | 4.75%   |
| 5.3     | 52        | 4.05%   |
| 5.19    | 49        | 3.82%   |
| 6.1     | 46        | 3.59%   |
| 4.18    | 30        | 2.34%   |
| 5.16    | 27        | 2.1%    |
| 5.0     | 25        | 1.95%   |
| 6.4     | 22        | 1.71%   |
| 5.14    | 21        | 1.64%   |
| 5.17    | 20        | 1.56%   |
| 6.0     | 15        | 1.17%   |
| 5.18    | 14        | 1.09%   |
| 6.5     | 13        | 1.01%   |
| 6.6     | 12        | 0.94%   |
| 5.6     | 10        | 0.78%   |
| 4.19    | 9         | 0.7%    |
| 5.9     | 8         | 0.62%   |
| 5.12    | 7         | 0.55%   |
| 4.9     | 7         | 0.55%   |
| 5.7     | 6         | 0.47%   |
| 6.3     | 5         | 0.39%   |
| 5.5     | 5         | 0.39%   |
| 4.4     | 5         | 0.39%   |
| 3.10    | 3         | 0.23%   |
| 5.2     | 1         | 0.08%   |
| 5.1     | 1         | 0.08%   |
| 4.16    | 1         | 0.08%   |
| 4.13    | 1         | 0.08%   |
| 4.12    | 1         | 0.08%   |
| 4.1     | 1         | 0.08%   |
| 3.16    | 1         | 0.08%   |
| 3.13    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1109      | 96.1%   |
| i686    | 29        | 2.51%   |
| aarch64 | 16        | 1.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 567       | 47.33%  |
| KDE5             | 185       | 15.44%  |
| Unknown          | 114       | 9.52%   |
| X-Cinnamon       | 109       | 9.1%    |
| XFCE             | 74        | 6.18%   |
| KDE              | 37        | 3.09%   |
| MATE             | 25        | 2.09%   |
| Unity            | 10        | 0.83%   |
| Pantheon         | 10        | 0.83%   |
| LXDE             | 10        | 0.83%   |
| Cinnamon         | 10        | 0.83%   |
| LXQt             | 9         | 0.75%   |
| KDE4             | 6         | 0.5%    |
| i3               | 6         | 0.5%    |
| Budgie           | 6         | 0.5%    |
| Deepin           | 5         | 0.42%   |
| GNOME Flashback  | 3         | 0.25%   |
| awesome          | 3         | 0.25%   |
| sway             | 2         | 0.17%   |
| lightdm-xsession | 2         | 0.17%   |
| GNOME Classic    | 2         | 0.17%   |
| trinity          | 1         | 0.08%   |
| Hyprland         | 1         | 0.08%   |
| bspwm            | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 932       | 77.86%  |
| Wayland | 190       | 15.87%  |
| Unknown | 47        | 3.93%   |
| Tty     | 28        | 2.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 698       | 58.17%  |
| GDM3    | 159       | 13.25%  |
| SDDM    | 146       | 12.17%  |
| LightDM | 96        | 8%      |
| GDM     | 72        | 6%      |
| TDM     | 22        | 1.83%   |
| KDM     | 5         | 0.42%   |
| SLiM    | 2         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_ZA   | 762       | 63.55%  |
| en_US   | 242       | 20.18%  |
| Unknown | 85        | 7.09%   |
| en_GB   | 71        | 5.92%   |
| C       | 19        | 1.58%   |
| en_ZW   | 9         | 0.75%   |
| fr_FR   | 3         | 0.25%   |
| af_ZA   | 3         | 0.25%   |
| en_BW   | 2         | 0.17%   |
| en_AU   | 1         | 0.08%   |
| de_DE   | 1         | 0.08%   |
| C.UTF8  | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 675       | 57.11%  |
| EFI  | 507       | 42.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 932       | 78.52%  |
| Btrfs   | 80        | 6.74%   |
| Overlay | 63        | 5.31%   |
| Tmpfs   | 39        | 3.29%   |
| Unknown | 27        | 2.27%   |
| Xfs     | 26        | 2.19%   |
| Zfs     | 13        | 1.1%    |
| Ext2    | 2         | 0.17%   |
| Aufs    | 2         | 0.17%   |
| Rootfs  | 1         | 0.08%   |
| F2fs    | 1         | 0.08%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 738       | 62.33%  |
| GPT     | 343       | 28.97%  |
| MBR     | 103       | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1027      | 87.26%  |
| Yes       | 150       | 12.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 869       | 74.02%  |
| Yes       | 305       | 25.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 187       | 16.23%  |
| Dell                            | 180       | 15.63%  |
| Lenovo                          | 154       | 13.37%  |
| ASUSTek Computer                | 131       | 11.37%  |
| MSI                             | 97        | 8.42%   |
| Gigabyte Technology             | 77        | 6.68%   |
| Acer                            | 60        | 5.21%   |
| Intel                           | 58        | 5.03%   |
| Apple                           | 28        | 2.43%   |
| ASRock                          | 22        | 1.91%   |
| Foxconn                         | 15        | 1.3%    |
| Biostar                         | 15        | 1.3%    |
| Raspberry Pi Foundation         | 12        | 1.04%   |
| Toshiba                         | 11        | 0.95%   |
| Unknown                         | 9         | 0.78%   |
| Samsung Electronics             | 7         | 0.61%   |
| MECER                           | 7         | 0.61%   |
| Sony                            | 5         | 0.43%   |
| Packard Bell                    | 5         | 0.43%   |
| Fujitsu                         | 5         | 0.43%   |
| Supermicro                      | 4         | 0.35%   |
| Standard                        | 4         | 0.35%   |
| Proline                         | 4         | 0.35%   |
| Mustek                          | 4         | 0.35%   |
| I-Life Digital Technologies     | 4         | 0.35%   |
| ECS                             | 4         | 0.35%   |
| CONNEX                          | 4         | 0.35%   |
| System76                        | 2         | 0.17%   |
| Purism                          | 2         | 0.17%   |
| PINNACLEMICRO                   | 2         | 0.17%   |
| Panasonic                       | 2         | 0.17%   |
| Nvidia                          | 2         | 0.17%   |
| NCR                             | 2         | 0.17%   |
| IBM                             | 2         | 0.17%   |
| HUAWEI                          | 2         | 0.17%   |
| YiFang                          | 1         | 0.09%   |
| WinSome                         | 1         | 0.09%   |
| Universal Exports Group Limited | 1         | 0.09%   |
| TYAN Computer                   | 1         | 0.09%   |
| TCL Communication               | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 18        | 1.56%   |
| Dell Inspiron 15-3567                | 10        | 0.87%   |
| MSI MS-7817                          | 8         | 0.69%   |
| ASUS All Series                      | 7         | 0.61%   |
| Gigabyte G31M-ES2C                   | 6         | 0.52%   |
| Dell Latitude E6400                  | 6         | 0.52%   |
| Lenovo IdeaPad 110-15IBR 80T7        | 5         | 0.43%   |
| HP ProBook 4530s                     | 5         | 0.43%   |
| Gigabyte H61M-DS2                    | 5         | 0.43%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.43%   |
| Acer Aspire E1-571                   | 5         | 0.43%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 4         | 0.35%   |
| MSI MS-7C37                          | 4         | 0.35%   |
| MSI MS-7B89                          | 4         | 0.35%   |
| MSI MS-7B84                          | 4         | 0.35%   |
| HP ProLiant MicroServer              | 4         | 0.35%   |
| HP Pavilion dv7                      | 4         | 0.35%   |
| HP Notebook                          | 4         | 0.35%   |
| HP Laptop 15-da0xxx                  | 4         | 0.35%   |
| HP 635                               | 4         | 0.35%   |
| Gigabyte B75M-D3H                    | 4         | 0.35%   |
| Dell XPS 13 9310                     | 4         | 0.35%   |
| Dell Latitude E6430                  | 4         | 0.35%   |
| ASUS PRIME X570-P                    | 4         | 0.35%   |
| MSI MS-7B79                          | 3         | 0.26%   |
| MSI MS-7A15                          | 3         | 0.26%   |
| MSI MS-7756                          | 3         | 0.26%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 3         | 0.26%   |
| Lenovo G500 20236                    | 3         | 0.26%   |
| Intel Mecer_X102                     | 3         | 0.26%   |
| HP ProBook 4520s                     | 3         | 0.26%   |
| HP Pavilion dv6                      | 3         | 0.26%   |
| HP Laptop 15-dw3xxx                  | 3         | 0.26%   |
| HP Laptop 15-bs1xx                   | 3         | 0.26%   |
| HP Laptop 15-bs0xx                   | 3         | 0.26%   |
| HP EliteBook 840 G3                  | 3         | 0.26%   |
| HP Compaq 8200 Elite SFF PC          | 3         | 0.26%   |
| HP 620                               | 3         | 0.26%   |
| HP 255 G7 Notebook PC                | 3         | 0.26%   |
| Gigabyte X58A-UD3R                   | 3         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 62        | 5.38%   |
| Dell Latitude      | 57        | 4.95%   |
| Dell Inspiron      | 47        | 4.08%   |
| Lenovo IdeaPad     | 40        | 3.47%   |
| Acer Aspire        | 38        | 3.3%    |
| HP ProBook         | 32        | 2.78%   |
| HP Laptop          | 21        | 1.82%   |
| HP Compaq          | 21        | 1.82%   |
| ASUS VivoBook      | 21        | 1.82%   |
| Lenovo ThinkCentre | 20        | 1.74%   |
| HP EliteBook       | 20        | 1.74%   |
| Dell OptiPlex      | 18        | 1.56%   |
| Unknown            | 18        | 1.56%   |
| HP Pavilion        | 17        | 1.48%   |
| Dell XPS           | 16        | 1.39%   |
| Dell Vostro        | 14        | 1.22%   |
| ASUS PRIME         | 13        | 1.13%   |
| RPi Raspberry      | 12        | 1.04%   |
| Toshiba Satellite  | 10        | 0.87%   |
| HP ProLiant        | 9         | 0.78%   |
| Dell Precision     | 9         | 0.78%   |
| MSI MS-7817        | 8         | 0.69%   |
| HP 250             | 8         | 0.69%   |
| ASUS ROG           | 8         | 0.69%   |
| ASUS TUF           | 7         | 0.61%   |
| ASUS All           | 7         | 0.61%   |
| Acer TravelMate    | 7         | 0.61%   |
| HP 255             | 6         | 0.52%   |
| Gigabyte G31M-ES2C | 6         | 0.52%   |
| Dell G3            | 6         | 0.52%   |
| HP ZBook           | 5         | 0.43%   |
| Gigabyte H61M-DS2  | 5         | 0.43%   |
| ASUS ASUS          | 5         | 0.43%   |
| MSI MS-7C37        | 4         | 0.35%   |
| MSI MS-7B89        | 4         | 0.35%   |
| MSI MS-7B84        | 4         | 0.35%   |
| Intel Mecer        | 4         | 0.35%   |
| Intel DH61WW       | 4         | 0.35%   |
| I-Life Digital ZED | 4         | 0.35%   |
| HP Notebook        | 4         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 114       | 9.9%    |
| 2012    | 112       | 9.72%   |
| 2018    | 110       | 9.55%   |
| 2013    | 90        | 7.81%   |
| 2016    | 77        | 6.68%   |
| 2020    | 75        | 6.51%   |
| 2017    | 75        | 6.51%   |
| 2019    | 70        | 6.08%   |
| 2010    | 70        | 6.08%   |
| 2008    | 66        | 5.73%   |
| 2015    | 55        | 4.77%   |
| 2009    | 50        | 4.34%   |
| 2021    | 49        | 4.25%   |
| 2014    | 48        | 4.17%   |
| 2007    | 35        | 3.04%   |
| 2022    | 19        | 1.65%   |
| Unknown | 13        | 1.13%   |
| 2006    | 12        | 1.04%   |
| 2023    | 8         | 0.69%   |
| 2005    | 3         | 0.26%   |
| 2004    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 640       | 55.56%  |
| Desktop        | 432       | 37.5%   |
| Convertible    | 19        | 1.65%   |
| System on chip | 15        | 1.3%    |
| Mini pc        | 15        | 1.3%    |
| All in one     | 11        | 0.95%   |
| Tablet         | 10        | 0.87%   |
| Server         | 10        | 0.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1067      | 91.67%  |
| Enabled  | 97        | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1148      | 99.65%  |
| Yes  | 4         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 265       | 22.65%  |
| 3.01-4.0        | 265       | 22.65%  |
| 8.01-16.0       | 207       | 17.69%  |
| 16.01-24.0      | 198       | 16.92%  |
| 32.01-64.0      | 85        | 7.26%   |
| 1.01-2.0        | 83        | 7.09%   |
| 2.01-3.0        | 22        | 1.88%   |
| 24.01-32.0      | 17        | 1.45%   |
| 64.01-256.0     | 17        | 1.45%   |
| 0.51-1.0        | 10        | 0.85%   |
| More than 256.0 | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 487       | 37.84%  |
| 2.01-3.0    | 316       | 24.55%  |
| 4.01-8.0    | 179       | 13.91%  |
| 3.01-4.0    | 138       | 10.72%  |
| 0.51-1.0    | 83        | 6.45%   |
| 8.01-16.0   | 56        | 4.35%   |
| 0.01-0.5    | 13        | 1.01%   |
| 16.01-24.0  | 10        | 0.78%   |
| 32.01-64.0  | 2         | 0.16%   |
| 24.01-32.0  | 1         | 0.08%   |
| 64.01-256.0 | 1         | 0.08%   |
| Unknown     | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 670       | 56.21%  |
| 2       | 320       | 26.85%  |
| 3       | 95        | 7.97%   |
| 4       | 59        | 4.95%   |
| 0       | 18        | 1.51%   |
| 5       | 9         | 0.76%   |
| 7       | 7         | 0.59%   |
| 6       | 7         | 0.59%   |
| 8       | 4         | 0.34%   |
| 22      | 1         | 0.08%   |
| 14      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 662       | 56.68%  |
| Yes       | 506       | 43.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1026      | 89.06%  |
| No        | 126       | 10.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 826       | 71.39%  |
| No        | 331       | 28.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 623       | 52.98%  |
| No        | 553       | 47.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| South Africa | 1152      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Johannesburg     | 326       | 26.48%  |
| Cape Town        | 295       | 23.96%  |
| Pretoria         | 143       | 11.62%  |
| Durban           | 65        | 5.28%   |
| Centurion        | 36        | 2.92%   |
| Port Elizabeth   | 27        | 2.19%   |
| Benoni           | 15        | 1.22%   |
| Sandton          | 14        | 1.14%   |
| Pietermaritzburg | 13        | 1.06%   |
| East London      | 12        | 0.97%   |
| Kempton Park     | 11        | 0.89%   |
| Bloemfontein     | 10        | 0.81%   |
| Alberton         | 10        | 0.81%   |
| Midrand          | 9         | 0.73%   |
| Somerset West    | 8         | 0.65%   |
| Potchefstroom    | 8         | 0.65%   |
| George           | 8         | 0.65%   |
| Bellville        | 8         | 0.65%   |
| Stellenbosch     | 7         | 0.57%   |
| Roodepoort       | 7         | 0.57%   |
| Randburg         | 7         | 0.57%   |
| Boksburg         | 7         | 0.57%   |
| Polokwane        | 6         | 0.49%   |
| Germiston        | 6         | 0.49%   |
| Thabazimbi       | 5         | 0.41%   |
| Edenvale         | 5         | 0.41%   |
| Vanderbijlpark   | 4         | 0.32%   |
| Sasolburg        | 4         | 0.32%   |
| Paarl            | 4         | 0.32%   |
| Oudtshoorn       | 4         | 0.32%   |
| Nelspruit        | 4         | 0.32%   |
| Klerksdorp       | 4         | 0.32%   |
| Hermanus         | 4         | 0.32%   |
| White River      | 3         | 0.24%   |
| Westville        | 3         | 0.24%   |
| Port Alfred      | 3         | 0.24%   |
| Plettenberg Bay  | 3         | 0.24%   |
| Middelburg       | 3         | 0.24%   |
| Louis Trichardt  | 3         | 0.24%   |
| Lichtenburg      | 3         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 362       | 642    | 21.32%  |
| WDC                 | 329       | 475    | 19.38%  |
| Samsung Electronics | 179       | 252    | 10.54%  |
| Toshiba             | 133       | 164    | 7.83%   |
| Unknown             | 77        | 97     | 4.53%   |
| Hitachi             | 68        | 97     | 4%      |
| SanDisk             | 44        | 57     | 2.59%   |
| Kingston            | 43        | 51     | 2.53%   |
| HGST                | 35        | 42     | 2.06%   |
| Transcend           | 31        | 43     | 1.83%   |
| Silicon Motion      | 31        | 45     | 1.83%   |
| SK hynix            | 29        | 33     | 1.71%   |
| Crucial             | 28        | 30     | 1.65%   |
| A-DATA Technology   | 28        | 39     | 1.65%   |
| Intel               | 26        | 32     | 1.53%   |
| TO Exter            | 16        | 18     | 0.94%   |
| Micron Technology   | 15        | 17     | 0.88%   |
| Hewlett-Packard     | 15        | 19     | 0.88%   |
| Apple               | 13        | 17     | 0.77%   |
| Hikvision           | 11        | 13     | 0.65%   |
| Rogueware           | 9         | 12     | 0.53%   |
| KIOXIA              | 8         | 8      | 0.47%   |
| HS-SSD-E100         | 8         | 11     | 0.47%   |
| HS-SSD-C100         | 8         | 12     | 0.47%   |
| Mushkin             | 7         | 9      | 0.41%   |
| Kingmax             | 7         | 8      | 0.41%   |
| Phison              | 6         | 8      | 0.35%   |
| Maxtor              | 6         | 7      | 0.35%   |
| Fujitsu             | 6         | 7      | 0.35%   |
| External            | 6         | 7      | 0.35%   |
| Corsair             | 6         | 10     | 0.35%   |
| China               | 6         | 6      | 0.35%   |
| OCZ                 | 5         | 7      | 0.29%   |
| LITEONIT            | 5         | 6      | 0.29%   |
| LITEON              | 5         | 6      | 0.29%   |
| Gigabyte Technology | 5         | 6      | 0.29%   |
| Apacer              | 5         | 7      | 0.29%   |
| Patriot             | 4         | 4      | 0.24%   |
| Netac               | 4         | 4      | 0.24%   |
| Lexar               | 4         | 5      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 34        | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB                    | 32        | 1.68%   |
| Unknown MMC Card  32GB                            | 23        | 1.21%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 22        | 1.16%   |
| Seagate ST3500418AS 500GB                         | 22        | 1.16%   |
| Toshiba MQ01ABF050 500GB                          | 18        | 0.95%   |
| Toshiba MQ04ABF100 1TB                            | 16        | 0.84%   |
| TO Exter nal USB 3.0 480GB                        | 16        | 0.84%   |
| Toshiba MQ01ABD100 1TB                            | 14        | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 12        | 0.63%   |
| Unknown MMC Card  64GB                            | 12        | 0.63%   |
| Seagate ST380815AS 80GB                           | 12        | 0.63%   |
| Seagate ST500LT012-1DG142 500GB                   | 11        | 0.58%   |
| Seagate ST3500413AS 500GB                         | 11        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 11        | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB                    | 10        | 0.53%   |
| Samsung HD103SI 1TB                               | 10        | 0.53%   |
| Hitachi HTS543232A7A384 320GB                     | 10        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 9         | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 9         | 0.47%   |
| Unknown MMC Card  128GB                           | 9         | 0.47%   |
| Seagate ST3250318AS 250GB                         | 9         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB                    | 9         | 0.47%   |
| HGST HTS721010A9E630 1TB                          | 9         | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 8         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 8         | 0.42%   |
| Toshiba MQ01ACF050 500GB                          | 8         | 0.42%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 8         | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB                    | 8         | 0.42%   |
| Seagate ST4000DM000-1F2168 4TB                    | 8         | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB                    | 8         | 0.42%   |
| Samsung SSD 850 EVO 250GB                         | 8         | 0.42%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 8         | 0.42%   |
| Samsung HD502HI 500GB                             | 8         | 0.42%   |
| HGST HTS541010A9E680 1TB                          | 8         | 0.42%   |
| WDC WD20EARX-00PASB0 2TB                          | 7         | 0.37%   |
| Transcend TS256GSSD230S 256GB                     | 7         | 0.37%   |
| Toshiba DT01ACA100 1TB                            | 7         | 0.37%   |
| Seagate ST500LM021-1KJ152 500GB                   | 7         | 0.37%   |
| Seagate ST3160815AS 160GB                         | 7         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 353       | 617    | 36.73%  |
| WDC                 | 275       | 395    | 28.62%  |
| Toshiba             | 113       | 140    | 11.76%  |
| Hitachi             | 68        | 97     | 7.08%   |
| Samsung Electronics | 56        | 75     | 5.83%   |
| HGST                | 35        | 42     | 3.64%   |
| TO Exter            | 16        | 18     | 1.66%   |
| Hewlett-Packard     | 8         | 11     | 0.83%   |
| Apple               | 7         | 7      | 0.73%   |
| Maxtor              | 6         | 7      | 0.62%   |
| Fujitsu             | 6         | 7      | 0.62%   |
| External            | 6         | 7      | 0.62%   |
| Unknown             | 5         | 6      | 0.52%   |
| StoreJet            | 3         | 3      | 0.31%   |
| HGST HTS            | 2         | 2      | 0.21%   |
| USB                 | 1         | 1      | 0.1%    |
| HPE                 | 1         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 74        | 102    | 18.93%  |
| WDC                 | 58        | 73     | 14.83%  |
| Kingston            | 32        | 37     | 8.18%   |
| Transcend           | 27        | 38     | 6.91%   |
| Crucial             | 26        | 28     | 6.65%   |
| SanDisk             | 23        | 26     | 5.88%   |
| A-DATA Technology   | 23        | 34     | 5.88%   |
| Rogueware           | 9         | 12     | 2.3%    |
| SK hynix            | 8         | 10     | 2.05%   |
| Intel               | 8         | 10     | 2.05%   |
| Toshiba             | 7         | 8      | 1.79%   |
| Micron Technology   | 7         | 8      | 1.79%   |
| Kingmax             | 7         | 8      | 1.79%   |
| China               | 6         | 6      | 1.53%   |
| Seagate             | 5         | 9      | 1.28%   |
| OCZ                 | 5         | 7      | 1.28%   |
| LITEONIT            | 5         | 6      | 1.28%   |
| Apacer              | 5         | 7      | 1.28%   |
| Netac               | 4         | 4      | 1.02%   |
| LITEON              | 4         | 5      | 1.02%   |
| HS-SSD-E100         | 4         | 4      | 1.02%   |
| Corsair             | 4         | 8      | 1.02%   |
| Plextor             | 3         | 4      | 0.77%   |
| Patriot             | 3         | 3      | 0.77%   |
| Mushkin             | 3         | 3      | 0.77%   |
| Lexar               | 3         | 4      | 0.77%   |
| Hewlett-Packard     | 3         | 3      | 0.77%   |
| Gigabyte Technology | 3         | 4      | 0.77%   |
| ASMT                | 3         | 3      | 0.77%   |
| AFOX                | 2         | 2      | 0.51%   |
| XPG                 | 1         | 1      | 0.26%   |
| Union Memory        | 1         | 1      | 0.26%   |
| SOLIDATA            | 1         | 1      | 0.26%   |
| Radeon              | 1         | 1      | 0.26%   |
| Neo Forza           | 1         | 1      | 0.26%   |
| MyDigitalSSD        | 1         | 1      | 0.26%   |
| KingSpec            | 1         | 2      | 0.26%   |
| INTEL SS            | 1         | 1      | 0.26%   |
| Innodisk            | 1         | 1      | 0.26%   |
| Indilinx            | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 762       | 1437   | 52.7%   |
| SSD     | 346       | 494    | 23.93%  |
| NVMe    | 237       | 345    | 16.39%  |
| MMC     | 71        | 93     | 4.91%   |
| Unknown | 30        | 41     | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 942       | 1860   | 71.04%  |
| NVMe | 237       | 345    | 17.87%  |
| SAS  | 76        | 112    | 5.73%   |
| MMC  | 71        | 93     | 5.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 710       | 1113   | 56.89%  |
| 0.51-1.0   | 361       | 511    | 28.93%  |
| 1.01-2.0   | 100       | 161    | 8.01%   |
| 3.01-4.0   | 34        | 64     | 2.72%   |
| 2.01-3.0   | 24        | 32     | 1.92%   |
| 4.01-10.0  | 16        | 45     | 1.28%   |
| 10.01-20.0 | 3         | 5      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 305       | 24.66%  |
| 101-250        | 288       | 23.28%  |
| 501-1000       | 196       | 15.84%  |
| 1001-2000      | 115       | 9.3%    |
| 51-100         | 73        | 5.9%    |
| More than 3000 | 68        | 5.5%    |
| 1-20           | 68        | 5.5%    |
| 21-50          | 49        | 3.96%   |
| 2001-3000      | 45        | 3.64%   |
| Unknown        | 30        | 2.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 423       | 32.92%  |
| 21-50          | 238       | 18.52%  |
| 51-100         | 155       | 12.06%  |
| 101-250        | 150       | 11.67%  |
| 251-500        | 120       | 9.34%   |
| 501-1000       | 78        | 6.07%   |
| 1001-2000      | 44        | 3.42%   |
| More than 3000 | 30        | 2.33%   |
| Unknown        | 30        | 2.33%   |
| 2001-3000      | 17        | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 6         | 6      | 5.77%   |
| Seagate ST3500418AS 500GB          | 5         | 6      | 4.81%   |
| Seagate ST320LT007-9ZV142 320GB    | 4         | 4      | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 3.85%   |
| Toshiba MQ01ABD100 1TB             | 3         | 4      | 2.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 4      | 2.88%   |
| WDC WD3200AAJS-00RYA0 320GB        | 2         | 2      | 1.92%   |
| WDC WD1600AAJS-08L7A0 160GB        | 2         | 2      | 1.92%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 2      | 1.92%   |
| Seagate ST3000DM001-1CH166 3TB     | 2         | 2      | 1.92%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 2      | 1.92%   |
| HGST HTS725050A7E630 500GB         | 2         | 2      | 1.92%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 1.92%   |
| WDC WD6400AAKS-75A7B0 640GB        | 1         | 1      | 0.96%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 0.96%   |
| WDC WD5000AVVS-63ZWB0 500GB        | 1         | 1      | 0.96%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 1         | 1      | 0.96%   |
| WDC WD5000AAKX-221CA1 500GB        | 1         | 1      | 0.96%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 2      | 0.96%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.96%   |
| WDC WD3200AAJS-60Z0A0 320GB        | 1         | 1      | 0.96%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1         | 1      | 0.96%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 3      | 0.96%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 1      | 0.96%   |
| WDC WD2500BEVS-60UST0 250GB        | 1         | 1      | 0.96%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1         | 1      | 0.96%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1         | 1      | 0.96%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 2      | 0.96%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 1      | 0.96%   |
| WDC WD15EADS-00P8B0 1TB            | 1         | 1      | 0.96%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 0.96%   |
| WDC WD10EVDS-63N5B1 1TB            | 1         | 2      | 0.96%   |
| WDC WD10EFRX-68PJCN0 1TB           | 1         | 1      | 0.96%   |
| WDC WD10EADS-67M2B0 1TB            | 1         | 2      | 0.96%   |
| WDC WD10EACS-00ZJB0 1TB            | 1         | 1      | 0.96%   |
| Transcend TS64GSSD720 64GB         | 1         | 1      | 0.96%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.96%   |
| Toshiba MK5065GSXF 500GB           | 1         | 1      | 0.96%   |
| TO Exter nal USB 3.0 480GB         | 1         | 1      | 0.96%   |
| SOLIDATA SSD 120GB                 | 1         | 1      | 0.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 58     | 39%     |
| WDC                 | 27        | 34     | 27%     |
| Hitachi             | 7         | 7      | 7%      |
| Toshiba             | 5         | 6      | 5%      |
| HGST                | 5         | 5      | 5%      |
| Samsung Electronics | 3         | 4      | 3%      |
| Intel               | 3         | 5      | 3%      |
| Micron Technology   | 2         | 2      | 2%      |
| Kingston            | 2         | 2      | 2%      |
| Hewlett-Packard     | 2         | 2      | 2%      |
| Transcend           | 1         | 1      | 1%      |
| TO Exter            | 1         | 1      | 1%      |
| SOLIDATA            | 1         | 1      | 1%      |
| SK hynix            | 1         | 1      | 1%      |
| Indilinx            | 1         | 1      | 1%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 58     | 44.32%  |
| WDC                 | 27        | 34     | 30.68%  |
| Hitachi             | 7         | 7      | 7.95%   |
| Toshiba             | 5         | 6      | 5.68%   |
| HGST                | 5         | 5      | 5.68%   |
| Samsung Electronics | 3         | 4      | 3.41%   |
| TO Exter            | 1         | 1      | 1.14%   |
| Hewlett-Packard     | 1         | 1      | 1.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 76        | 116    | 86.36%  |
| SSD  | 10        | 12     | 11.36%  |
| NVMe | 2         | 2      | 2.27%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD20EZRX-00D8PB0 2TB | 2         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 824       | 1684   | 66.77%  |
| Works    | 322       | 594    | 26.09%  |
| Malfunc  | 86        | 130    | 6.97%   |
| Failed   | 2         | 2      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 906       | 66.96%  |
| AMD                              | 120       | 8.87%   |
| Samsung Electronics              | 58        | 4.29%   |
| Silicon Motion                   | 42        | 3.1%    |
| SanDisk                          | 25        | 1.85%   |
| SK hynix                         | 21        | 1.55%   |
| Toshiba America Info Systems     | 19        | 1.4%    |
| Nvidia                           | 16        | 1.18%   |
| Phison Electronics               | 15        | 1.11%   |
| Marvell Technology Group         | 15        | 1.11%   |
| JMicron Technology               | 15        | 1.11%   |
| ASMedia Technology               | 14        | 1.03%   |
| Kingston Technology Company      | 13        | 0.96%   |
| KIOXIA                           | 9         | 0.67%   |
| Micron Technology                | 8         | 0.59%   |
| ADATA Technology                 | 6         | 0.44%   |
| Micron/Crucial Technology        | 5         | 0.37%   |
| Apple                            | 5         | 0.37%   |
| VIA Technologies                 | 3         | 0.22%   |
| Silicon Integrated Systems [SiS] | 3         | 0.22%   |
| Silicon Image                    | 3         | 0.22%   |
| Seagate Technology               | 3         | 0.22%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.22%   |
| LSI Logic / Symbios Logic        | 3         | 0.22%   |
| Hewlett-Packard                  | 3         | 0.22%   |
| Broadcom / LSI                   | 3         | 0.22%   |
| Union Memory (Shenzhen)          | 2         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Realtek Semiconductor            | 2         | 0.15%   |
| Lite-On Technology               | 2         | 0.15%   |
| INNOGRIT                         | 2         | 0.15%   |
| Adaptec                          | 2         | 0.15%   |
| Transcend                        | 1         | 0.07%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| HighPoint Technologies           | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 81        | 4.99%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 75        | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 70        | 4.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 54        | 3.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50        | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 49        | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 41        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 40        | 2.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 37        | 2.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 36        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 34        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 34        | 2.1%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 29        | 1.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 27        | 1.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24        | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 22        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 22        | 1.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 21        | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21        | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 20        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 20        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 20        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 19        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 18        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 17        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 17        | 1.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 16        | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 16        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 15        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14        | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 13        | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 13        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 12        | 0.74%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11        | 0.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 10        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 772       | 55.9%   |
| NVMe | 242       | 17.52%  |
| IDE  | 229       | 16.58%  |
| RAID | 129       | 9.34%   |
| SAS  | 5         | 0.36%   |
| SCSI | 4         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 988       | 85.76%  |
| AMD     | 148       | 12.85%  |
| ARM     | 15        | 1.3%    |
| Unknown | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz        | 17        | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 1.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 13        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 1.04%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 12        | 1.04%   |
| ARM Processor                           | 12        | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 11        | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 11        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 11        | 0.95%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 11        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 11        | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.95%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 11        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 10        | 0.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 10        | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 10        | 0.87%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 9         | 0.78%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 9         | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 9         | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 8         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 8         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 0.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 0.69%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 8         | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 0.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 8         | 0.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 8         | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 7         | 0.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 7         | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 7         | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 6         | 0.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 6         | 0.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 6         | 0.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 0.52%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 6         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 273       | 23.68%  |
| Intel Core i7           | 244       | 21.16%  |
| Intel Core i3           | 122       | 10.58%  |
| Intel Celeron           | 85        | 7.37%   |
| Intel Core 2 Duo        | 68        | 5.9%    |
| Other                   | 65        | 5.64%   |
| AMD Ryzen 5             | 38        | 3.3%    |
| Intel Pentium           | 32        | 2.78%   |
| AMD Ryzen 7             | 31        | 2.69%   |
| Intel Xeon              | 24        | 2.08%   |
| Intel Atom              | 24        | 2.08%   |
| Intel Core 2 Quad       | 14        | 1.21%   |
| Intel Pentium Dual-Core | 13        | 1.13%   |
| AMD Ryzen 9             | 13        | 1.13%   |
| Intel Pentium Dual      | 9         | 0.78%   |
| AMD FX                  | 8         | 0.69%   |
| Intel Pentium 4         | 7         | 0.61%   |
| AMD E                   | 7         | 0.61%   |
| AMD Ryzen 3             | 6         | 0.52%   |
| AMD A4                  | 6         | 0.52%   |
| Intel Core 2            | 5         | 0.43%   |
| Intel Genuine           | 4         | 0.35%   |
| Intel Core i9           | 4         | 0.35%   |
| AMD Turion II Neo       | 4         | 0.35%   |
| AMD Athlon 64 X2        | 4         | 0.35%   |
| Intel Pentium D         | 3         | 0.26%   |
| Intel Celeron Dual-Core | 3         | 0.26%   |
| AMD Ryzen 5 PRO         | 3         | 0.26%   |
| AMD E2                  | 3         | 0.26%   |
| Intel Core Duo          | 2         | 0.17%   |
| ARM BCM                 | 2         | 0.17%   |
| AMD Ryzen 7 PRO         | 2         | 0.17%   |
| AMD Phenom II X4        | 2         | 0.17%   |
| AMD Phenom II X2        | 2         | 0.17%   |
| AMD E1                  | 2         | 0.17%   |
| AMD A6                  | 2         | 0.17%   |
| Intel Pentium Silver    | 1         | 0.09%   |
| Intel Core 2 Extreme    | 1         | 0.09%   |
| Intel Celeron M         | 1         | 0.09%   |
| Intel Celeron D         | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 560       | 48.57%  |
| 4       | 392       | 34%     |
| 6       | 82        | 7.11%   |
| 8       | 55        | 4.77%   |
| 1       | 30        | 2.6%    |
| 16      | 10        | 0.87%   |
| 12      | 9         | 0.78%   |
| 10      | 4         | 0.35%   |
| 3       | 4         | 0.35%   |
| Unknown | 3         | 0.26%   |
| 24      | 2         | 0.17%   |
| 14      | 2         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1140      | 98.96%  |
| 2       | 9         | 0.78%   |
| Unknown | 3         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 721       | 62.42%  |
| 1       | 431       | 37.32%  |
| Unknown | 3         | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1120      | 96.89%  |
| Unknown        | 24        | 2.08%   |
| 32-bit         | 8         | 0.69%   |
| 64-bit         | 4         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 391       | 32.18%  |
| 0x206a7    | 85        | 7%      |
| 0x306a9    | 77        | 6.34%   |
| 0x306c3    | 46        | 3.79%   |
| 0x1067a    | 43        | 3.54%   |
| 0x406e3    | 35        | 2.88%   |
| 0x806e9    | 32        | 2.63%   |
| 0x506e3    | 29        | 2.39%   |
| 0x906ea    | 27        | 2.22%   |
| 0x20655    | 27        | 2.22%   |
| 0x806ea    | 23        | 1.89%   |
| 0x406c4    | 22        | 1.81%   |
| 0x906e9    | 20        | 1.65%   |
| 0x806c1    | 18        | 1.48%   |
| 0x6fd      | 18        | 1.48%   |
| 0x306d4    | 17        | 1.4%    |
| 0x806ec    | 15        | 1.23%   |
| 0x10676    | 15        | 1.23%   |
| 0x20652    | 14        | 1.15%   |
| 0x506c9    | 13        | 1.07%   |
| 0x40651    | 13        | 1.07%   |
| 0x6fb      | 10        | 0.82%   |
| 0x08701021 | 9         | 0.74%   |
| 0x06006705 | 9         | 0.74%   |
| 0xa0652    | 8         | 0.66%   |
| 0x406c3    | 8         | 0.66%   |
| 0x806eb    | 7         | 0.58%   |
| 0x106e5    | 7         | 0.58%   |
| 0x106a5    | 7         | 0.58%   |
| 0x706e5    | 6         | 0.49%   |
| 0x0a50000c | 6         | 0.49%   |
| 0x08600106 | 6         | 0.49%   |
| 0xa0653    | 5         | 0.41%   |
| 0x706a1    | 5         | 0.41%   |
| 0x206d7    | 5         | 0.41%   |
| 0x08108109 | 5         | 0.41%   |
| 0x0800820d | 5         | 0.41%   |
| 0x06000852 | 5         | 0.41%   |
| 0x010000db | 5         | 0.41%   |
| 0x010000c8 | 5         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 177       | 15.32%  |
| SandyBridge      | 123       | 10.65%  |
| IvyBridge        | 111       | 9.61%   |
| Haswell          | 94        | 8.14%   |
| Penryn           | 83        | 7.19%   |
| Skylake          | 79        | 6.84%   |
| Westmere         | 53        | 4.59%   |
| Core             | 52        | 4.5%    |
| Silvermont       | 41        | 3.55%   |
| Unknown          | 38        | 3.29%   |
| Zen 2            | 28        | 2.42%   |
| TigerLake        | 28        | 2.42%   |
| Zen 3            | 26        | 2.25%   |
| Broadwell        | 25        | 2.16%   |
| Nehalem          | 19        | 1.65%   |
| Zen+             | 16        | 1.39%   |
| IceLake          | 16        | 1.39%   |
| Goldmont         | 16        | 1.39%   |
| CometLake        | 16        | 1.39%   |
| Excavator        | 15        | 1.3%    |
| Goldmont plus    | 13        | 1.13%   |
| Zen              | 12        | 1.04%   |
| NetBurst         | 12        | 1.04%   |
| Alderlake Hybrid | 12        | 1.04%   |
| K10              | 11        | 0.95%   |
| Bobcat           | 9         | 0.78%   |
| Bonnell          | 8         | 0.69%   |
| Piledriver       | 7         | 0.61%   |
| K8 Hammer        | 6         | 0.52%   |
| P6               | 3         | 0.26%   |
| Jaguar           | 2         | 0.17%   |
| Tremont          | 1         | 0.09%   |
| Steamroller      | 1         | 0.09%   |
| Puma             | 1         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 770       | 57.98%  |
| Nvidia                           | 331       | 24.92%  |
| AMD                              | 210       | 15.81%  |
| Matrox Electronics Systems       | 11        | 0.83%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| ASPEED Technology                | 2         | 0.15%   |
| VIA Technologies                 | 1         | 0.08%   |
| Silicon Motion                   | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 94        | 6.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 45        | 3.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 3.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 36        | 2.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 2.57%   |
| Intel HD Graphics 620                                                                    | 34        | 2.5%    |
| Intel UHD Graphics 620                                                                   | 30        | 2.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 1.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 1.91%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 23        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 1.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 22        | 1.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 1.47%   |
| Intel HD Graphics 630                                                                    | 18        | 1.32%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 1.1%    |
| Intel HD Graphics 500                                                                    | 15        | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.96%   |
| Intel HD Graphics 530                                                                    | 13        | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.81%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 9         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.51%   |
| Nvidia GM108M [GeForce MX130]                                                            | 7         | 0.51%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 7         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 587       | 50.82%  |
| 1 x Nvidia         | 188       | 16.28%  |
| 1 x AMD            | 149       | 12.9%   |
| Intel + Nvidia     | 130       | 11.26%  |
| Intel + AMD        | 38        | 3.29%   |
| Other              | 18        | 1.56%   |
| AMD + Nvidia       | 12        | 1.04%   |
| 2 x AMD            | 11        | 0.95%   |
| 1 x Matrox         | 9         | 0.78%   |
| 2 x Intel          | 5         | 0.43%   |
| 1 x SiS            | 2         | 0.17%   |
| 1 x VIA            | 1         | 0.09%   |
| 1 x Silicon Motion | 1         | 0.09%   |
| Nvidia + Matrox    | 1         | 0.09%   |
| Nvidia + ASPEED    | 1         | 0.09%   |
| 1 x ASPEED         | 1         | 0.09%   |
| AMD + Matrox       | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 937       | 80.22%  |
| Proprietary | 174       | 14.9%   |
| Unknown     | 57        | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 783       | 65.52%  |
| 1.01-2.0   | 128       | 10.71%  |
| 0.01-0.5   | 83        | 6.95%   |
| 0.51-1.0   | 71        | 5.94%   |
| 3.01-4.0   | 63        | 5.27%   |
| 5.01-6.0   | 27        | 2.26%   |
| 7.01-8.0   | 24        | 2.01%   |
| 2.01-3.0   | 8         | 0.67%   |
| 8.01-16.0  | 6         | 0.5%    |
| 16.01-24.0 | 2         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 228       | 17.98%  |
| Dell                    | 149       | 11.75%  |
| AU Optronics            | 142       | 11.2%   |
| LG Display              | 115       | 9.07%   |
| BOE                     | 115       | 9.07%   |
| Chimei Innolux          | 101       | 7.97%   |
| Goldstar                | 94        | 7.41%   |
| Chi Mei Optoelectronics | 26        | 2.05%   |
| Lenovo                  | 21        | 1.66%   |
| Hewlett-Packard         | 21        | 1.66%   |
| AOC                     | 21        | 1.66%   |
| Philips                 | 20        | 1.58%   |
| Apple                   | 20        | 1.58%   |
| Sharp                   | 14        | 1.1%    |
| Unknown                 | 12        | 0.95%   |
| LG Electronics          | 10        | 0.79%   |
| BenQ                    | 10        | 0.79%   |
| Acer                    | 10        | 0.79%   |
| LG Philips              | 9         | 0.71%   |
| VIE                     | 8         | 0.63%   |
| Toshiba                 | 7         | 0.55%   |
| Fujitsu Siemens         | 7         | 0.55%   |
| SKY                     | 6         | 0.47%   |
| PANDA                   | 6         | 0.47%   |
| ViewSonic               | 5         | 0.39%   |
| Hitachi                 | 5         | 0.39%   |
| Plain Tree Systems      | 4         | 0.32%   |
| Ancor Communications    | 4         | 0.32%   |
| Sony                    | 3         | 0.24%   |
| PRI                     | 3         | 0.24%   |
| Panasonic               | 3         | 0.24%   |
| MECER                   | 3         | 0.24%   |
| Unknown                 | 3         | 0.24%   |
| ___                     | 2         | 0.16%   |
| Tatung                  | 2         | 0.16%   |
| STD                     | 2         | 0.16%   |
| SKG                     | 2         | 0.16%   |
| Sampo                   | 2         | 0.16%   |
| Quanta Display          | 2         | 0.16%   |
| Onkyo                   | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 14        | 1.06%   |
| Dell SE2416H DELD082 1920x1080 530x300mm 24.0-inch                       | 11        | 0.83%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 10        | 0.76%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                       | 10        | 0.76%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 10        | 0.76%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 9         | 0.68%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 9         | 0.68%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 8         | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.61%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                       | 7         | 0.53%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 6         | 0.45%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6         | 0.45%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                      | 6         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 5         | 0.38%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.38%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                    | 5         | 0.38%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                        | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.38%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 4         | 0.3%    |
| Samsung Electronics SMBX2031 SAM076B 1600x900 443x249mm 20.0-inch        | 4         | 0.3%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 4         | 0.3%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 4         | 0.3%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 4         | 0.3%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.3%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.3%    |
| Goldstar W2443 GSM571B 1920x1080 474x296mm 22.0-inch                     | 4         | 0.3%    |
| Goldstar W2343 GSM5700 1920x1080 474x296mm 22.0-inch                     | 4         | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 4         | 0.3%    |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                    | 4         | 0.3%    |
| Dell SE2419HX DELF109 1920x1080 527x296mm 23.8-inch                      | 4         | 0.3%    |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                        | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 444       | 36.63%  |
| 1366x768 (WXGA)    | 332       | 27.39%  |
| 1600x900 (HD+)     | 82        | 6.77%   |
| 1280x1024 (SXGA)   | 45        | 3.71%   |
| 3840x2160 (4K)     | 44        | 3.63%   |
| 1280x800 (WXGA)    | 40        | 3.3%    |
| 2560x1440 (QHD)    | 37        | 3.05%   |
| 1440x900 (WXGA+)   | 35        | 2.89%   |
| 1680x1050 (WSXGA+) | 26        | 2.15%   |
| 1920x1200 (WUXGA)  | 21        | 1.73%   |
| 1360x768           | 19        | 1.57%   |
| 1024x768 (XGA)     | 14        | 1.16%   |
| 2560x1080          | 12        | 0.99%   |
| Unknown            | 11        | 0.91%   |
| 3840x1080          | 6         | 0.5%    |
| 2880x1800          | 6         | 0.5%    |
| 1920x540           | 5         | 0.41%   |
| 1600x1200          | 4         | 0.33%   |
| 3072x1920          | 3         | 0.25%   |
| 1152x864           | 3         | 0.25%   |
| 1024x600           | 3         | 0.25%   |
| 5120x1080          | 2         | 0.17%   |
| 4480x1080          | 2         | 0.17%   |
| 720x480            | 1         | 0.08%   |
| 4880x1080          | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 3440x1440          | 1         | 0.08%   |
| 3360x1080          | 1         | 0.08%   |
| 3286x1080          | 1         | 0.08%   |
| 3280x1200          | 1         | 0.08%   |
| 2880x1920          | 1         | 0.08%   |
| 2880x1620          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 2048x1536          | 1         | 0.08%   |
| 1x1                | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |
| 1280x720 (HD)      | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 419       | 32.71%  |
| 23      | 92        | 7.18%   |
| 13      | 75        | 5.85%   |
| 17      | 74        | 5.78%   |
| 24      | 73        | 5.7%    |
| 14      | 69        | 5.39%   |
| 21      | 63        | 4.92%   |
| 27      | 60        | 4.68%   |
| Unknown | 53        | 4.14%   |
| 19      | 52        | 4.06%   |
| 18      | 46        | 3.59%   |
| 20      | 43        | 3.36%   |
| 22      | 25        | 1.95%   |
| 31      | 22        | 1.72%   |
| 12      | 13        | 1.01%   |
| 34      | 12        | 0.94%   |
| 40      | 11        | 0.86%   |
| 84      | 7         | 0.55%   |
| 72      | 7         | 0.55%   |
| 16      | 7         | 0.55%   |
| 11      | 7         | 0.55%   |
| 48      | 6         | 0.47%   |
| 32      | 6         | 0.47%   |
| 52      | 5         | 0.39%   |
| 26      | 5         | 0.39%   |
| 10      | 4         | 0.31%   |
| 54      | 3         | 0.23%   |
| 49      | 3         | 0.23%   |
| 46      | 3         | 0.23%   |
| 25      | 3         | 0.23%   |
| 64      | 2         | 0.16%   |
| 63      | 2         | 0.16%   |
| 39      | 2         | 0.16%   |
| 97      | 1         | 0.08%   |
| 86      | 1         | 0.08%   |
| 67      | 1         | 0.08%   |
| 44      | 1         | 0.08%   |
| 43      | 1         | 0.08%   |
| 28      | 1         | 0.08%   |
| 8       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 545       | 43.53%  |
| 501-600        | 207       | 16.53%  |
| 401-500        | 207       | 16.53%  |
| 351-400        | 76        | 6.07%   |
| 201-300        | 60        | 4.79%   |
| Unknown        | 53        | 4.23%   |
| 601-700        | 29        | 2.32%   |
| 1001-1500      | 25        | 2%      |
| 701-800        | 18        | 1.44%   |
| 1501-2000      | 14        | 1.12%   |
| 801-900        | 13        | 1.04%   |
| 901-1000       | 2         | 0.16%   |
| More than 2000 | 1         | 0.08%   |
| 101-200        | 1         | 0.08%   |
| 1-100          | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 848       | 76.19%  |
| 16/10   | 134       | 12.04%  |
| Unknown | 37        | 3.32%   |
| 5/4     | 35        | 3.14%   |
| 4/3     | 29        | 2.61%   |
| 21/9    | 12        | 1.08%   |
| 3/2     | 7         | 0.63%   |
| 32/9    | 6         | 0.54%   |
| 1.96    | 3         | 0.27%   |
| 0.56    | 1         | 0.09%   |
| 0.00    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 411       | 32.7%   |
| 201-250        | 211       | 16.79%  |
| 81-90          | 119       | 9.47%   |
| 151-200        | 113       | 8.99%   |
| 301-350        | 63        | 5.01%   |
| 141-150        | 60        | 4.77%   |
| Unknown        | 54        | 4.3%    |
| 121-130        | 49        | 3.9%    |
| 351-500        | 40        | 3.18%   |
| More than 1000 | 31        | 2.47%   |
| 71-80          | 25        | 1.99%   |
| 501-1000       | 24        | 1.91%   |
| 111-120        | 15        | 1.19%   |
| 251-300        | 14        | 1.11%   |
| 61-70          | 12        | 0.95%   |
| 51-60          | 7         | 0.56%   |
| 131-140        | 4         | 0.32%   |
| 41-50          | 3         | 0.24%   |
| 1-40           | 1         | 0.08%   |
| 91-100         | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 457       | 37.52%  |
| 101-120       | 382       | 31.36%  |
| 121-160       | 246       | 20.2%   |
| Unknown       | 53        | 4.35%   |
| 161-240       | 35        | 2.87%   |
| 1-50          | 32        | 2.63%   |
| More than 240 | 13        | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 901       | 75.65%  |
| 2     | 214       | 17.97%  |
| 0     | 51        | 4.28%   |
| 3     | 21        | 1.76%   |
| 4     | 4         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 633       | 35.99%  |
| Intel                             | 492       | 27.97%  |
| Qualcomm Atheros                  | 205       | 11.65%  |
| Broadcom                          | 100       | 5.69%   |
| Huawei Technologies               | 28        | 1.59%   |
| Dell                              | 28        | 1.59%   |
| TP-Link                           | 25        | 1.42%   |
| Samsung Electronics               | 24        | 1.36%   |
| Broadcom Limited                  | 21        | 1.19%   |
| Ralink Technology                 | 19        | 1.08%   |
| Ralink                            | 19        | 1.08%   |
| MediaTek                          | 18        | 1.02%   |
| Marvell Technology Group          | 17        | 0.97%   |
| Nvidia                            | 13        | 0.74%   |
| D-Link                            | 9         | 0.51%   |
| Ericsson Business Mobile Networks | 7         | 0.4%    |
| D-Link System                     | 7         | 0.4%    |
| ASIX Electronics                  | 7         | 0.4%    |
| Sierra Wireless                   | 6         | 0.34%   |
| JMicron Technology                | 6         | 0.34%   |
| Microsoft                         | 5         | 0.28%   |
| Hewlett-Packard                   | 5         | 0.28%   |
| Apple                             | 5         | 0.28%   |
| Spreadtrum Communications         | 4         | 0.23%   |
| Aquantia                          | 4         | 0.23%   |
| ZyXEL Communications              | 3         | 0.17%   |
| Xiaomi                            | 3         | 0.17%   |
| TRENDnet                          | 3         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.17%   |
| DisplayLink                       | 3         | 0.17%   |
| Qualcomm Atheros Communications   | 2         | 0.11%   |
| NetGear                           | 2         | 0.11%   |
| Mellanox Technologies             | 2         | 0.11%   |
| Lenovo                            | 2         | 0.11%   |
| IBM                               | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| Arduino SA                        | 2         | 0.11%   |
| ZyDAS                             | 1         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| U-Blox                            | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 421       | 20.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 5.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 2.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 37        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 1.35%   |
| Intel Wireless 8265 / 8275                                        | 25        | 1.21%   |
| Intel Wireless 8260                                               | 22        | 1.06%   |
| Intel Wi-Fi 6 AX200                                               | 22        | 1.06%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 20        | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 20        | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.82%   |
| Intel Wireless 3165                                               | 15        | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 15        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                   | 14        | 0.68%   |
| Intel Wireless 7265                                               | 14        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.68%   |
| Intel Centrino Advanced-N 6200                                    | 14        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 13        | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 12        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 12        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.53%   |
| Intel Wireless 3160                                               | 11        | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 11        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 11        | 0.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 10        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 337       | 38.12%  |
| Qualcomm Atheros                  | 168       | 19%     |
| Realtek Semiconductor             | 161       | 18.21%  |
| Broadcom                          | 67        | 7.58%   |
| TP-Link                           | 23        | 2.6%    |
| Ralink Technology                 | 19        | 2.15%   |
| Ralink                            | 19        | 2.15%   |
| Dell                              | 17        | 1.92%   |
| MediaTek                          | 16        | 1.81%   |
| Broadcom Limited                  | 11        | 1.24%   |
| D-Link                            | 9         | 1.02%   |
| Sierra Wireless                   | 6         | 0.68%   |
| Microsoft                         | 5         | 0.57%   |
| ZyXEL Communications              | 3         | 0.34%   |
| TRENDnet                          | 3         | 0.34%   |
| Ericsson Business Mobile Networks | 3         | 0.34%   |
| Qualcomm Atheros Communications   | 2         | 0.23%   |
| NetGear                           | 2         | 0.23%   |
| D-Link System                     | 2         | 0.23%   |
| ASUSTek Computer                  | 2         | 0.23%   |
| ZyDAS                             | 1         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.11%   |
| Tenda                             | 1         | 0.11%   |
| Marvell Technology Group          | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| Fibocom                           | 1         | 0.11%   |
| Edimax Technology                 | 1         | 0.11%   |
| CyberTAN Technology               | 1         | 0.11%   |
| Belkin Components                 | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 37        | 4.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 3.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 3.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 29        | 3.25%   |
| Intel Wireless 8265 / 8275                                     | 25        | 2.81%   |
| Intel Wireless 8260                                            | 22        | 2.47%   |
| Intel Wi-Fi 6 AX200                                            | 22        | 2.47%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 2.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 20        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.91%   |
| Intel Wireless 3165                                            | 15        | 1.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 1.68%   |
| Ralink MT7601U Wireless Adapter                                | 14        | 1.57%   |
| Intel Wireless 7265                                            | 14        | 1.57%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 1.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 12        | 1.35%   |
| Intel Wireless 3160                                            | 11        | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 11        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 1.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 10        | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 10        | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 10        | 1.12%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 10        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 9         | 1.01%   |
| Intel Wireless 7260                                            | 9         | 1.01%   |
| Intel WiFi Link 5100                                           | 9         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.01%   |
| Intel Centrino Wireless-N 2230                                 | 9         | 1.01%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 8         | 0.9%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 8         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 581       | 52.63%  |
| Intel                            | 292       | 26.45%  |
| Qualcomm Atheros                 | 55        | 4.98%   |
| Broadcom                         | 50        | 4.53%   |
| Huawei Technologies              | 18        | 1.63%   |
| Marvell Technology Group         | 16        | 1.45%   |
| Nvidia                           | 13        | 1.18%   |
| Samsung Electronics              | 12        | 1.09%   |
| Broadcom Limited                 | 11        | 1%      |
| ASIX Electronics                 | 7         | 0.63%   |
| JMicron Technology               | 6         | 0.54%   |
| D-Link System                    | 5         | 0.45%   |
| Apple                            | 5         | 0.45%   |
| Spreadtrum Communications        | 4         | 0.36%   |
| Aquantia                         | 4         | 0.36%   |
| Xiaomi                           | 3         | 0.27%   |
| Silicon Integrated Systems [SiS] | 3         | 0.27%   |
| DisplayLink                      | 3         | 0.27%   |
| TP-Link                          | 2         | 0.18%   |
| Mellanox Technologies            | 2         | 0.18%   |
| MediaTek                         | 2         | 0.18%   |
| Lenovo                           | 2         | 0.18%   |
| Qualcomm                         | 1         | 0.09%   |
| Microchip Technology             | 1         | 0.09%   |
| Insyde Software                  | 1         | 0.09%   |
| IBM                              | 1         | 0.09%   |
| HMD Global                       | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| Foxconn / Hon Hai                | 1         | 0.09%   |
| Attansic Technology              | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 421       | 37.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 9.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 5.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 2.5%    |
| Intel 82579V Gigabit Network Connection                           | 20        | 1.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.89%   |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 9         | 0.8%    |
| Intel 82578DM Gigabit Network Connection                          | 9         | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.71%   |
| Huawei E353/E3131                                                 | 8         | 0.71%   |
| Huawei MAR-LX1M                                                   | 7         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.53%   |
| Intel 82578DC Gigabit Network Connection                          | 6         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.45%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.45%   |
| Intel 82566DM Gigabit Network Connection                          | 5         | 0.45%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 5         | 0.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1026      | 54%     |
| WiFi     | 821       | 43.21%  |
| Modem    | 49        | 2.58%   |
| Unknown  | 4         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 658       | 55.39%  |
| Ethernet | 528       | 44.44%  |
| Modem    | 2         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 630       | 54.45%  |
| 1     | 456       | 39.41%  |
| 0     | 54        | 4.67%   |
| 3     | 12        | 1.04%   |
| 4     | 3         | 0.26%   |
| 6     | 2         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1119      | 96.97%  |
| Yes  | 35        | 3.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 235       | 37.3%   |
| Qualcomm Atheros Communications | 71        | 11.27%  |
| Realtek Semiconductor           | 63        | 10%     |
| Cambridge Silicon Radio         | 41        | 6.51%   |
| Broadcom                        | 34        | 5.4%    |
| IMC Networks                    | 29        | 4.6%    |
| Foxconn / Hon Hai               | 26        | 4.13%   |
| Lite-On Technology              | 25        | 3.97%   |
| Hewlett-Packard                 | 23        | 3.65%   |
| Dell                            | 22        | 3.49%   |
| Apple                           | 20        | 3.17%   |
| Ralink                          | 10        | 1.59%   |
| Toshiba                         | 9         | 1.43%   |
| ASUSTek Computer                | 6         | 0.95%   |
| TP-Link                         | 2         | 0.32%   |
| MediaTek                        | 2         | 0.32%   |
| Alps Electric                   | 2         | 0.32%   |
| USI                             | 1         | 0.16%   |
| Realtek                         | 1         | 0.16%   |
| Mobile Action Technology        | 1         | 0.16%   |
| Micro Star International        | 1         | 0.16%   |
| Marvell Semiconductor           | 1         | 0.16%   |
| Logitech                        | 1         | 0.16%   |
| Integrated System Solution      | 1         | 0.16%   |
| Foxconn International           | 1         | 0.16%   |
| Edimax Technology               | 1         | 0.16%   |
| Askey Computer                  | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 100       | 15.87%  |
| Intel Bluetooth Device                              | 47        | 7.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 41        | 6.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 38        | 6.03%   |
| Realtek Bluetooth Radio                             | 35        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 32        | 5.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 3.33%   |
| Intel AX200 Bluetooth                               | 20        | 3.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 2.54%   |
| IMC Networks Bluetooth Radio                        | 13        | 2.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 1.75%   |
| Ralink RT3290 Bluetooth                             | 10        | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 1.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 9         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 1.27%   |
| Lite-On Bluetooth Device                            | 7         | 1.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.11%   |
| IMC Networks Wireless_Device                        | 6         | 0.95%   |
| IMC Networks Bluetooth Device                       | 6         | 0.95%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 0.79%   |
| Apple Bluetooth HCI                                 | 5         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.63%   |
| Apple Bluetooth Host Controller                     | 4         | 0.63%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.48%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 3         | 0.48%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 0.48%   |
| Dell Wireless 360 Bluetooth                         | 3         | 0.48%   |
| Dell Wireless 355 Bluetooth                         | 3         | 0.48%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.48%   |
| Broadcom Broadcom BCM2070 Bluetooth Device          | 3         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 931       | 62.07%  |
| Nvidia                           | 235       | 15.67%  |
| AMD                              | 197       | 13.13%  |
| C-Media Electronics              | 28        | 1.87%   |
| Logitech                         | 11        | 0.73%   |
| Corsair                          | 10        | 0.67%   |
| Creative Labs                    | 8         | 0.53%   |
| DSEA A/S                         | 5         | 0.33%   |
| Realtek Semiconductor            | 4         | 0.27%   |
| JMTek                            | 4         | 0.27%   |
| GN Netcom                        | 4         | 0.27%   |
| Generalplus Technology           | 4         | 0.27%   |
| Apple                            | 4         | 0.27%   |
| VIA Technologies                 | 3         | 0.2%    |
| Silicon Integrated Systems [SiS] | 3         | 0.2%    |
| Razer USA                        | 3         | 0.2%    |
| Plantronics                      | 3         | 0.2%    |
| Lenovo                           | 3         | 0.2%    |
| Hewlett-Packard                  | 3         | 0.2%    |
| ASUSTek Computer                 | 3         | 0.2%    |
| Texas Instruments                | 2         | 0.13%   |
| Syntek                           | 2         | 0.13%   |
| Sony                             | 2         | 0.13%   |
| Samson Technologies              | 2         | 0.13%   |
| Microsoft                        | 2         | 0.13%   |
| Cooler Master                    | 2         | 0.13%   |
| Conexant Systems                 | 2         | 0.13%   |
| Xiaomi                           | 1         | 0.07%   |
| Trust                            | 1         | 0.07%   |
| Tenx Technology                  | 1         | 0.07%   |
| Steinberg Soft-und Hardware      | 1         | 0.07%   |
| Schiit Audio                     | 1         | 0.07%   |
| Micro Star International         | 1         | 0.07%   |
| Magic Control Technology         | 1         | 0.07%   |
| M-Audio                          | 1         | 0.07%   |
| iPassion Technology              | 1         | 0.07%   |
| GYROCOM C&C                      | 1         | 0.07%   |
| Focusrite-Novation               | 1         | 0.07%   |
| FIFINE Microphones               | 1         | 0.07%   |
| Elgato Systems                   | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 125       | 7.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 108       | 6.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 98        | 5.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 65        | 3.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 60        | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 59        | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 52        | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 50        | 2.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 45        | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 38        | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 37        | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 1.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 26        | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 25        | 1.46%   |
| Intel Broadwell-U Audio Controller                                                                | 25        | 1.46%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 25        | 1.46%   |
| Nvidia High Definition Audio Controller                                                           | 24        | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 22        | 1.29%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 21        | 1.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 20        | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 19        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 18        | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 16        | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 14        | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 13        | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 13        | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 13        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 0.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 0.64%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 0.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| SK hynix                       | 127       | 20.29%  |
| Samsung Electronics            | 123       | 19.65%  |
| Kingston                       | 72        | 11.5%   |
| Micron Technology              | 52        | 8.31%   |
| Unknown                        | 47        | 7.51%   |
| Corsair                        | 37        | 5.91%   |
| Crucial                        | 31        | 4.95%   |
| Transcend                      | 27        | 4.31%   |
| G.Skill                        | 18        | 2.88%   |
| A-DATA Technology              | 17        | 2.72%   |
| Elpida                         | 10        | 1.6%    |
| Ramaxel Technology             | 9         | 1.44%   |
| Patriot                        | 9         | 1.44%   |
| KLEVV                          | 9         | 1.44%   |
| Nanya Technology               | 8         | 1.28%   |
| Unknown (ABCD)                 | 5         | 0.8%    |
| Strontium                      | 3         | 0.48%   |
| Apacer                         | 3         | 0.48%   |
| Unknown                        | 3         | 0.48%   |
| Team                           | 2         | 0.32%   |
| Kingmax                        | 2         | 0.32%   |
| Innodisk                       | 2         | 0.32%   |
| Essencore Limited              | 2         | 0.32%   |
| Essencore                      | 2         | 0.32%   |
| Silicon Power                  | 1         | 0.16%   |
| Qimonda                        | 1         | 0.16%   |
| Neo Forza                      | 1         | 0.16%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.16%   |
| Hewlett-Packard                | 1         | 0.16%   |
| A-DA                           | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 1.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1.05%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 6         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 6         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.75%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.75%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.75%   |
| KLEVV RAM KD4AGUA8A-26N1900 16GB DIMM DDR4 2667MT/s              | 5         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.6%    |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 3         | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.45%   |
| Transcend RAM TS512MLK64V6H 4GB DIMM DDR3 1600MT/s               | 3         | 0.45%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.45%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.45%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.45%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.45%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 3         | 0.45%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 3         | 0.45%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 3         | 0.45%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 3         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 219       | 45.25%  |
| DDR3    | 184       | 38.02%  |
| DDR2    | 19        | 3.93%   |
| Unknown | 19        | 3.93%   |
| LPDDR4  | 16        | 3.31%   |
| DDR5    | 9         | 1.86%   |
| SDRAM   | 7         | 1.45%   |
| LPDDR3  | 7         | 1.45%   |
| LPDDR5  | 2         | 0.41%   |
| DDR     | 2         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 293       | 59.67%  |
| DIMM         | 169       | 34.42%  |
| Row Of Chips | 23        | 4.68%   |
| Chip         | 4         | 0.81%   |
| FB-DIMM      | 1         | 0.2%    |
| Unknown      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 185       | 33.45%  |
| 4096  | 169       | 30.56%  |
| 2048  | 82        | 14.83%  |
| 16384 | 81        | 14.65%  |
| 1024  | 16        | 2.89%   |
| 32768 | 15        | 2.71%   |
| 512   | 5         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 117       | 21.27%  |
| 2667    | 92        | 16.73%  |
| 3200    | 60        | 10.91%  |
| 1333    | 48        | 8.73%   |
| 2400    | 32        | 5.82%   |
| 2133    | 31        | 5.64%   |
| 1334    | 21        | 3.82%   |
| 800     | 13        | 2.36%   |
| 3266    | 11        | 2%      |
| 667     | 10        | 1.82%   |
| 3600    | 9         | 1.64%   |
| 1867    | 9         | 1.64%   |
| 4800    | 7         | 1.27%   |
| 1067    | 7         | 1.27%   |
| 4267    | 5         | 0.91%   |
| 2933    | 5         | 0.91%   |
| 400     | 5         | 0.91%   |
| Unknown | 5         | 0.91%   |
| 3866    | 4         | 0.73%   |
| 2048    | 4         | 0.73%   |
| 1066    | 4         | 0.73%   |
| 3000    | 3         | 0.55%   |
| 2666    | 3         | 0.55%   |
| 975     | 3         | 0.55%   |
| 8400    | 2         | 0.36%   |
| 6400    | 2         | 0.36%   |
| 6000    | 2         | 0.36%   |
| 3800    | 2         | 0.36%   |
| 3733    | 2         | 0.36%   |
| 3100    | 2         | 0.36%   |
| 3066    | 2         | 0.36%   |
| 2934    | 2         | 0.36%   |
| 2448    | 2         | 0.36%   |
| 2200    | 2         | 0.36%   |
| 2187    | 2         | 0.36%   |
| 1800    | 2         | 0.36%   |
| 1648    | 2         | 0.36%   |
| 41632   | 1         | 0.18%   |
| 4199    | 1         | 0.18%   |
| 3533    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 8         | 25.81%  |
| Canon                 | 8         | 25.81%  |
| Hewlett-Packard       | 6         | 19.35%  |
| Pantum                | 3         | 9.68%   |
| Brother Industries    | 2         | 6.45%   |
| Seiko Epson           | 1         | 3.23%   |
| Oki Data              | 1         | 3.23%   |
| Lexmark International | 1         | 3.23%   |
| Dell                  | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pantum P2200 series                        | 3         | 9.68%   |
| Samsung M267x 287x Series                  | 2         | 6.45%   |
| Canon PIXMA MG2500 Series                  | 2         | 6.45%   |
| Seiko Epson L3110 Series                   | 1         | 3.23%   |
| Samsung SCX-4623 Series                    | 1         | 3.23%   |
| Samsung SCX-4600 Series                    | 1         | 3.23%   |
| Samsung M2070 Series                       | 1         | 3.23%   |
| Samsung M2020 Series                       | 1         | 3.23%   |
| Samsung Composite Device                   | 1         | 3.23%   |
| Samsung C460 Series                        | 1         | 3.23%   |
| Oki Data USB Device                        | 1         | 3.23%   |
| Lexmark International InkJet Color Printer | 1         | 3.23%   |
| HP OfficeJet Pro 9010 series               | 1         | 3.23%   |
| HP Officejet J4500 series                  | 1         | 3.23%   |
| HP OfficeJet 5600 (USBHUB)                 | 1         | 3.23%   |
| HP LaserJet 1022                           | 1         | 3.23%   |
| HP LaserJet 1018                           | 1         | 3.23%   |
| HP DeskJet 3830 series                     | 1         | 3.23%   |
| Dell 1250c Color Printer                   | 1         | 3.23%   |
| Canon PIXMA MX410                          | 1         | 3.23%   |
| Canon PIXMA MG3600 Series                  | 1         | 3.23%   |
| Canon MG2400 series                        | 1         | 3.23%   |
| Canon MF210 Series                         | 1         | 3.23%   |
| Canon G4000 series                         | 1         | 3.23%   |
| Canon G3010 series                         | 1         | 3.23%   |
| Brother MFC-L2700DW                        | 1         | 3.23%   |
| Brother HL-2130 series                     | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1         | 33.33%  |
| HP OfficeJet 6110                                  | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20                 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 115       | 16.91%  |
| Microdia                                          | 71        | 10.44%  |
| Realtek Semiconductor                             | 59        | 8.68%   |
| Sunplus Innovation Technology                     | 47        | 6.91%   |
| IMC Networks                                      | 46        | 6.76%   |
| Bison Electronics                                 | 41        | 6.03%   |
| Quanta                                            | 32        | 4.71%   |
| Apple                                             | 30        | 4.41%   |
| Logitech                                          | 27        | 3.97%   |
| Cheng Uei Precision Industry (Foxlink)            | 26        | 3.82%   |
| Syntek                                            | 21        | 3.09%   |
| Lite-On Technology                                | 19        | 2.79%   |
| Samsung Electronics                               | 18        | 2.65%   |
| Suyin                                             | 15        | 2.21%   |
| Microsoft                                         | 14        | 2.06%   |
| Acer                                              | 12        | 1.76%   |
| Silicon Motion                                    | 8         | 1.18%   |
| Ricoh                                             | 8         | 1.18%   |
| Luxvisions Innotech Limited                       | 8         | 1.18%   |
| Alcor Micro                                       | 8         | 1.18%   |
| Sonix Technology                                  | 6         | 0.88%   |
| Z-Star Microelectronics                           | 5         | 0.74%   |
| Primax Electronics                                | 5         | 0.74%   |
| icSpring                                          | 5         | 0.74%   |
| Lenovo                                            | 4         | 0.59%   |
| Importek                                          | 3         | 0.44%   |
| GEMBIRD                                           | 3         | 0.44%   |
| SN0002                                            | 2         | 0.29%   |
| LG Electronics                                    | 2         | 0.29%   |
| ALi                                               | 2         | 0.29%   |
| Y Media                                           | 1         | 0.15%   |
| TASCORP                                           | 1         | 0.15%   |
| Sunplus Technology                                | 1         | 0.15%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 0.15%   |
| Spreadtrum Communications                         | 1         | 0.15%   |
| ShineTech                                         | 1         | 0.15%   |
| Panasonic (Matsushita)                            | 1         | 0.15%   |
| Owl Labs                                          | 1         | 0.15%   |
| OPPO Electronics                                  | 1         | 0.15%   |
| OmniVision Technologies                           | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 26        | 3.81%   |
| Realtek Integrated_Webcam_HD                  | 22        | 3.22%   |
| Sunplus Integrated_Webcam_HD                  | 19        | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)       | 17        | 2.49%   |
| Chicony Integrated Camera                     | 17        | 2.49%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 15        | 2.2%    |
| Bison Integrated Camera                       | 15        | 2.2%    |
| IMC Networks USB2.0 HD UVC WebCam             | 12        | 1.76%   |
| Apple iPhone 5/5C/5S/6/SE                     | 12        | 1.76%   |
| Microdia Integrated Webcam                    | 11        | 1.61%   |
| IMC Networks Integrated Camera                | 10        | 1.46%   |
| Chicony EasyCamera                            | 8         | 1.17%   |
| Apple FaceTime HD Camera (Built-in)           | 8         | 1.17%   |
| Syntek Integrated Camera                      | 7         | 1.02%   |
| Syntek EasyCamera                             | 7         | 1.02%   |
| Sunplus HD WebCam                             | 7         | 1.02%   |
| Quanta VGA Webcam                             | 7         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 7         | 1.02%   |
| Realtek Integrated Webcam HD                  | 6         | 0.88%   |
| Quanta HP HD Camera                           | 6         | 0.88%   |
| Microsoft LifeCam HD-3000                     | 6         | 0.88%   |
| Logitech Webcam C270                          | 6         | 0.88%   |
| Chicony HP Webcam                             | 6         | 0.88%   |
| Chicony HP TrueVision HD Camera               | 6         | 0.88%   |
| Chicony HD WebCam                             | 6         | 0.88%   |
| Sonix USB2.0 HD UVC WebCam                    | 5         | 0.73%   |
| Realtek Integrated Webcam                     | 5         | 0.73%   |
| Realtek HP Truevision HD                      | 5         | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD          | 5         | 0.73%   |
| Logitech Webcam C170                          | 5         | 0.73%   |
| Lite-On HP HD Camera                          | 5         | 0.73%   |
| icSpring camera                               | 5         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                 | 5         | 0.73%   |
| Chicony Integrated IR Camera                  | 5         | 0.73%   |
| Bison Lenovo EasyCamera                       | 5         | 0.73%   |
| Bison EasyCamera                              | 5         | 0.73%   |
| Apple FaceTime HD Camera                      | 5         | 0.73%   |
| Apple Built-in iSight                         | 5         | 0.73%   |
| Alcor Micro USB 2.0 Camera                    | 5         | 0.73%   |
| Syntek Lenovo EasyCamera                      | 4         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 66        | 48.53%  |
| Synaptics                          | 25        | 18.38%  |
| Shenzhen Goodix Technology         | 14        | 10.29%  |
| Upek                               | 12        | 8.82%   |
| AuthenTec                          | 9         | 6.62%   |
| LighTuning Technology              | 5         | 3.68%   |
| Focal-systems.Corp                 | 2         | 1.47%   |
| STMicroelectronics                 | 1         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.74%   |
| Elan Microelectronics              | 1         | 0.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 16        | 11.76%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 11        | 8.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 9         | 6.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 8         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 7         | 5.15%   |
| Shenzhen Goodix Fingerprint Reader                              | 7         | 5.15%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 5         | 3.68%   |
| Validity Sensors Synaptics WBDI                                 | 5         | 3.68%   |
| Validity Sensors Fingerprint scanner                            | 4         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 2.94%   |
| Synaptics Fingerprint reader [HP G6]                            | 4         | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                             | 4         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 3         | 2.21%   |
| Validity Sensors VFS491                                         | 3         | 2.21%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 3         | 2.21%   |
| Synaptics WBDI                                                  | 3         | 2.21%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 3         | 2.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 2.21%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 2.21%   |
| AuthenTec AES2810                                               | 3         | 2.21%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 2.21%   |
| Synaptics  WBDI                                                 | 2         | 1.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 1.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 2         | 1.47%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 2         | 1.47%   |
| AuthenTec Fingerprint Sensor                                    | 2         | 1.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 0.74%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 0.74%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 102                       | 1         | 0.74%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 0.74%   |
| Synaptics UWP WBDI                                              | 1         | 0.74%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 0.74%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 0.74%   |
| LighTuning Fingerprint Sensor                                   | 1         | 0.74%   |
| LighTuning Fingerprint Reader                                   | 1         | 0.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 0.74%   |
| Elan ELAN:ARM-M4                                                | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 48        | 71.64%  |
| Alcor Micro | 7         | 10.45%  |
| O2 Micro    | 5         | 7.46%   |
| Lenovo      | 5         | 7.46%   |
| Upek        | 2         | 2.99%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 23.88%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 20.9%   |
| Broadcom 5880                                                                | 11        | 16.42%  |
| Broadcom 58200                                                               | 7         | 10.45%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 10.45%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 7.46%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 7.46%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 2.99%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 802       | 68.26%  |
| 1     | 305       | 25.96%  |
| 2     | 57        | 4.85%   |
| 3     | 8         | 0.68%   |
| 9     | 1         | 0.09%   |
| 7     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 135       | 30.47%  |
| Graphics card            | 89        | 20.09%  |
| Chipcard                 | 61        | 13.77%  |
| Net/wireless             | 53        | 11.96%  |
| Multimedia controller    | 22        | 4.97%   |
| Communication controller | 18        | 4.06%   |
| Bluetooth                | 14        | 3.16%   |
| Camera                   | 12        | 2.71%   |
| Storage                  | 7         | 1.58%   |
| Sound                    | 7         | 1.58%   |
| Unassigned class         | 6         | 1.35%   |
| Modem                    | 5         | 1.13%   |
| Network                  | 4         | 0.9%    |
| Storage/raid             | 3         | 0.68%   |
| Card reader              | 3         | 0.68%   |
| Net/ethernet             | 2         | 0.45%   |
| Storage/nvme             | 1         | 0.23%   |
| Flash memory             | 1         | 0.23%   |


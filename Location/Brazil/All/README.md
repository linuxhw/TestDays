Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 16147

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Daten Tecn... | DT02-M4                     | Notebook    | [cdd5c3cca0](https://linux-hardware.org/?probe=cdd5c3cca0) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [7d43f3c00b](https://linux-hardware.org/?probe=7d43f3c00b) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [39cb4cb083](https://linux-hardware.org/?probe=39cb4cb083) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47c34f9269](https://linux-hardware.org/?probe=47c34f9269) | Nov 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [09c2704bb0](https://linux-hardware.org/?probe=09c2704bb0) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | H61M-P31                    | Desktop     | [819c124b25](https://linux-hardware.org/?probe=819c124b25) | Nov 01, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [9704a12e23](https://linux-hardware.org/?probe=9704a12e23) | Nov 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [dab530a737](https://linux-hardware.org/?probe=dab530a737) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [973fc77891](https://linux-hardware.org/?probe=973fc77891) | Oct 31, 2022 |
| Pegatron      | 2AABh                       | Desktop     | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| LG Electro... | A560-T.BG77P1               | Notebook    | [cad4120a42](https://linux-hardware.org/?probe=cad4120a42) | Oct 31, 2022 |
| Avell High... | B.ON                        | Notebook    | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0c1875c94f](https://linux-hardware.org/?probe=0c1875c94f) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c8970ae94a](https://linux-hardware.org/?probe=c8970ae94a) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9991d15803](https://linux-hardware.org/?probe=9991d15803) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c11b330691](https://linux-hardware.org/?probe=c11b330691) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [13a12cbd22](https://linux-hardware.org/?probe=13a12cbd22) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [182d67f23e](https://linux-hardware.org/?probe=182d67f23e) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| Dell          | Precision 5750              | Notebook    | [9b9addd3b7](https://linux-hardware.org/?probe=9b9addd3b7) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | Notebook    | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [e9ce2f5011](https://linux-hardware.org/?probe=e9ce2f5011) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Intel         | B75                         | Desktop     | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [e377db3a9e](https://linux-hardware.org/?probe=e377db3a9e) | Oct 28, 2022 |
| Avell High... | B.ON                        | Notebook    | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [9c7127a256](https://linux-hardware.org/?probe=9c7127a256) | Oct 27, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [fe1166a134](https://linux-hardware.org/?probe=fe1166a134) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [b35b1298a8](https://linux-hardware.org/?probe=b35b1298a8) | Oct 27, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [973ebfcf3e](https://linux-hardware.org/?probe=973ebfcf3e) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [98cd87adf9](https://linux-hardware.org/?probe=98cd87adf9) | Oct 27, 2022 |
| Intel         | H55                         | Desktop     | [fb3cf518ac](https://linux-hardware.org/?probe=fb3cf518ac) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [a7a8cc4cff](https://linux-hardware.org/?probe=a7a8cc4cff) | Oct 27, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [ccdf105523](https://linux-hardware.org/?probe=ccdf105523) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Sony          | VPCEA23FB                   | Notebook    | [1b9688e23f](https://linux-hardware.org/?probe=1b9688e23f) | Oct 26, 2022 |
| ASUSTek       | P7H57D-V EVO                | Desktop     | [785405287b](https://linux-hardware.org/?probe=785405287b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | Notebook    | [a0adbfd7fe](https://linux-hardware.org/?probe=a0adbfd7fe) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ff62c670fd](https://linux-hardware.org/?probe=ff62c670fd) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | Notebook    | [519384ee8a](https://linux-hardware.org/?probe=519384ee8a) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| Toshiba       | STI 005492G                 | Desktop     | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [562c9438d1](https://linux-hardware.org/?probe=562c9438d1) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | K201                        | Notebook    | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [31cae2266e](https://linux-hardware.org/?probe=31cae2266e) | Oct 24, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [9a9880cc6a](https://linux-hardware.org/?probe=9a9880cc6a) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [bc57450141](https://linux-hardware.org/?probe=bc57450141) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4540d714bc](https://linux-hardware.org/?probe=4540d714bc) | Oct 24, 2022 |
| Biostar       | A320MH                      | Desktop     | [b38eca2979](https://linux-hardware.org/?probe=b38eca2979) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [da9c01eb20](https://linux-hardware.org/?probe=da9c01eb20) | Oct 23, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| HP            | 1489                        | All in one  | [3b3379c0e2](https://linux-hardware.org/?probe=3b3379c0e2) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [3baeb7ee26](https://linux-hardware.org/?probe=3baeb7ee26) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | Notebook    | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | Notebook    | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| Avell High... | B.ON                        | Notebook    | [17ce0979b3](https://linux-hardware.org/?probe=17ce0979b3) | Oct 21, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [462091e8a8](https://linux-hardware.org/?probe=462091e8a8) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| Positivo      | C4120F                      | Notebook    | [92338290da](https://linux-hardware.org/?probe=92338290da) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | 0YXT71 A02                  | Desktop     | [137e154b2d](https://linux-hardware.org/?probe=137e154b2d) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [d46ae4e597](https://linux-hardware.org/?probe=d46ae4e597) | Oct 19, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [c395183020](https://linux-hardware.org/?probe=c395183020) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [e57ed46372](https://linux-hardware.org/?probe=e57ed46372) | Oct 19, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [83da6e6509](https://linux-hardware.org/?probe=83da6e6509) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5e02a12da7](https://linux-hardware.org/?probe=5e02a12da7) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [d9b4d01e7f](https://linux-hardware.org/?probe=d9b4d01e7f) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d458ae27cf](https://linux-hardware.org/?probe=d458ae27cf) | Oct 18, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6718ea22a9](https://linux-hardware.org/?probe=6718ea22a9) | Oct 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| Unknown       | Beelink GT-King Pro         | Soc         | [9d29015602](https://linux-hardware.org/?probe=9d29015602) | Oct 17, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| Unknown       | Beelink GT-King Pro         | Soc         | [2e5287f2cb](https://linux-hardware.org/?probe=2e5287f2cb) | Oct 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [464ce69071](https://linux-hardware.org/?probe=464ce69071) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Multilaser    | PC024                       | Notebook    | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [81cec7c137](https://linux-hardware.org/?probe=81cec7c137) | Oct 16, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [2d843ba905](https://linux-hardware.org/?probe=2d843ba905) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Intel         | H55                         | Desktop     | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| Alienware     | m15 R6                      | Notebook    | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [8e16d67f02](https://linux-hardware.org/?probe=8e16d67f02) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Compaq        | 420                         | Notebook    | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [19d249aa9c](https://linux-hardware.org/?probe=19d249aa9c) | Oct 14, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b5cfcb5d6c](https://linux-hardware.org/?probe=b5cfcb5d6c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a65b043bb7](https://linux-hardware.org/?probe=a65b043bb7) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [491ba5984a](https://linux-hardware.org/?probe=491ba5984a) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [d22d4118a7](https://linux-hardware.org/?probe=d22d4118a7) | Oct 14, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f13203e3ce](https://linux-hardware.org/?probe=f13203e3ce) | Oct 14, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [f8eae084ac](https://linux-hardware.org/?probe=f8eae084ac) | Oct 13, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [990bec11d7](https://linux-hardware.org/?probe=990bec11d7) | Oct 13, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [754608b701](https://linux-hardware.org/?probe=754608b701) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | Desktop     | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [3c99de982b](https://linux-hardware.org/?probe=3c99de982b) | Oct 13, 2022 |
| Samsung       | 930QDB                      | Convertible | [8cc56657cc](https://linux-hardware.org/?probe=8cc56657cc) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Pegatron      | 2AD2A                       | Desktop     | [01827879c5](https://linux-hardware.org/?probe=01827879c5) | Oct 13, 2022 |
| Positivo      | DH8BW01                     | All in one  | [95e8bed16f](https://linux-hardware.org/?probe=95e8bed16f) | Oct 12, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b271788734](https://linux-hardware.org/?probe=b271788734) | Oct 12, 2022 |
| Lenovo        | ThinkPad T480 20L6S1U700    | Notebook    | [df4489e9fb](https://linux-hardware.org/?probe=df4489e9fb) | Oct 12, 2022 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [d0fe56248f](https://linux-hardware.org/?probe=d0fe56248f) | Oct 12, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [7741ed43d0](https://linux-hardware.org/?probe=7741ed43d0) | Oct 12, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [585b7e9773](https://linux-hardware.org/?probe=585b7e9773) | Oct 12, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [b566c0179a](https://linux-hardware.org/?probe=b566c0179a) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f512c7bf3f](https://linux-hardware.org/?probe=f512c7bf3f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [3414f3f4c0](https://linux-hardware.org/?probe=3414f3f4c0) | Oct 10, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Dell          | Latitude 5410               | Notebook    | [c69cc79a8e](https://linux-hardware.org/?probe=c69cc79a8e) | Oct 10, 2022 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [01ebc77ef1](https://linux-hardware.org/?probe=01ebc77ef1) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [bfce31736f](https://linux-hardware.org/?probe=bfce31736f) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| PINE64        | Pinebook Pro                | Soc         | [8d79fe1eba](https://linux-hardware.org/?probe=8d79fe1eba) | Oct 09, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [be45a704e2](https://linux-hardware.org/?probe=be45a704e2) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [cdd4dd4637](https://linux-hardware.org/?probe=cdd4dd4637) | Oct 08, 2022 |
| Positivo      | Q232A                       | Notebook    | [658da8785e](https://linux-hardware.org/?probe=658da8785e) | Oct 08, 2022 |
| Standard      | MB40II                      | Notebook    | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | Notebook    | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0085d792fd](https://linux-hardware.org/?probe=0085d792fd) | Oct 07, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [dd91590e9f](https://linux-hardware.org/?probe=dd91590e9f) | Oct 07, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [fe1e7b060c](https://linux-hardware.org/?probe=fe1e7b060c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Positivo B... | VJC141F11X-B0111L           | Notebook    | [6f08bf3d68](https://linux-hardware.org/?probe=6f08bf3d68) | Oct 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| Positivo      | W940SU2                     | Notebook    | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ff783e01db](https://linux-hardware.org/?probe=ff783e01db) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [75f96017fd](https://linux-hardware.org/?probe=75f96017fd) | Oct 05, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Intel         | B75                         | Desktop     | [a15b4ede9b](https://linux-hardware.org/?probe=a15b4ede9b) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| Avell High... | B.ON                        | Notebook    | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0ed1bfe4ef](https://linux-hardware.org/?probe=0ed1bfe4ef) | Oct 05, 2022 |
| HP            | 2AA2                        | Desktop     | [e6bc6050b6](https://linux-hardware.org/?probe=e6bc6050b6) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c45d949c](https://linux-hardware.org/?probe=23c45d949c) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [10fec0d039](https://linux-hardware.org/?probe=10fec0d039) | Oct 04, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [d96984ac77](https://linux-hardware.org/?probe=d96984ac77) | Oct 04, 2022 |
| Intel         | W7645                       | Notebook    | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [16f99421ab](https://linux-hardware.org/?probe=16f99421ab) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [f30bf7e978](https://linux-hardware.org/?probe=f30bf7e978) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [a9281e38d4](https://linux-hardware.org/?probe=a9281e38d4) | Oct 04, 2022 |
| Dell          | G3 3500                     | Notebook    | [9a574c1075](https://linux-hardware.org/?probe=9a574c1075) | Oct 04, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c277d88bb6](https://linux-hardware.org/?probe=c277d88bb6) | Oct 03, 2022 |
| Sony          | VPCCA15FX                   | Notebook    | [c6c2a651b9](https://linux-hardware.org/?probe=c6c2a651b9) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [bdb7d444f0](https://linux-hardware.org/?probe=bdb7d444f0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | Notebook    | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | Desktop     | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| ASUSTek       | A78M-A                      | Desktop     | [91434dfd86](https://linux-hardware.org/?probe=91434dfd86) | Oct 02, 2022 |
| Dell          | XPS L421X                   | Notebook    | [dc90cf9dbf](https://linux-hardware.org/?probe=dc90cf9dbf) | Oct 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9b2e1432f2](https://linux-hardware.org/?probe=9b2e1432f2) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [ba82d9366c](https://linux-hardware.org/?probe=ba82d9366c) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Avell High... | B.ON                        | Notebook    | [240b350525](https://linux-hardware.org/?probe=240b350525) | Oct 02, 2022 |
| Positivo      | Mobile                      | Notebook    | [640bc1a962](https://linux-hardware.org/?probe=640bc1a962) | Oct 01, 2022 |
| Positivo      | POS-PIH81DL                 | Desktop     | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| ASUSTek       | A78M-A                      | Desktop     | [5ad2e5f2a6](https://linux-hardware.org/?probe=5ad2e5f2a6) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | Notebook    | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Sony          | VPCCA15FX                   | Notebook    | [96eb3d8cf7](https://linux-hardware.org/?probe=96eb3d8cf7) | Oct 01, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [e666344187](https://linux-hardware.org/?probe=e666344187) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [27bb1c39eb](https://linux-hardware.org/?probe=27bb1c39eb) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [b62ddbdab0](https://linux-hardware.org/?probe=b62ddbdab0) | Oct 01, 2022 |
| Biostar       | A320MH                      | Desktop     | [b07b6c4fc5](https://linux-hardware.org/?probe=b07b6c4fc5) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [9a047ee214](https://linux-hardware.org/?probe=9a047ee214) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [4c0a153a12](https://linux-hardware.org/?probe=4c0a153a12) | Oct 01, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [3edc4043a3](https://linux-hardware.org/?probe=3edc4043a3) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Intel         | H61                         | Desktop     | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [2c08befa41](https://linux-hardware.org/?probe=2c08befa41) | Sep 30, 2022 |
| Positivo      | Mobile                      | Notebook    | [dcf8b09bec](https://linux-hardware.org/?probe=dcf8b09bec) | Sep 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3c0e0b12ee](https://linux-hardware.org/?probe=3c0e0b12ee) | Sep 30, 2022 |
| Positivo      | Mobile                      | Notebook    | [6d2584bcb8](https://linux-hardware.org/?probe=6d2584bcb8) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [5cdce489b9](https://linux-hardware.org/?probe=5cdce489b9) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [3bfbb3744e](https://linux-hardware.org/?probe=3bfbb3744e) | Sep 30, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [149337514c](https://linux-hardware.org/?probe=149337514c) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fa00f3d0ca](https://linux-hardware.org/?probe=fa00f3d0ca) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [64a7e86e22](https://linux-hardware.org/?probe=64a7e86e22) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [62d808a3e5](https://linux-hardware.org/?probe=62d808a3e5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [7e4413a053](https://linux-hardware.org/?probe=7e4413a053) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bbd715eb5a](https://linux-hardware.org/?probe=bbd715eb5a) | Sep 28, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [f7e628a5a1](https://linux-hardware.org/?probe=f7e628a5a1) | Sep 28, 2022 |
| Positivo      | S14CT01                     | Notebook    | [66e0c53646](https://linux-hardware.org/?probe=66e0c53646) | Sep 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [3e450900da](https://linux-hardware.org/?probe=3e450900da) | Sep 28, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [a325f5eb86](https://linux-hardware.org/?probe=a325f5eb86) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | Desktop     | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Philco        | PNB14.1AC14S128W10          | Notebook    | [ee4bc98535](https://linux-hardware.org/?probe=ee4bc98535) | Sep 27, 2022 |
| Lenovo        | ThinkPad T410 2537AT9       | Notebook    | [553490bb4c](https://linux-hardware.org/?probe=553490bb4c) | Sep 27, 2022 |
| Standard      | AHV                         | Notebook    | [a80b2d344d](https://linux-hardware.org/?probe=a80b2d344d) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| Intel         | H55                         | Desktop     | [a155052bce](https://linux-hardware.org/?probe=a155052bce) | Sep 26, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| Dell          | Latitude 5420               | Notebook    | [bd81c07917](https://linux-hardware.org/?probe=bd81c07917) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | Notebook    | [60933ed48b](https://linux-hardware.org/?probe=60933ed48b) | Sep 26, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [bab009e0b7](https://linux-hardware.org/?probe=bab009e0b7) | Sep 26, 2022 |
| Positivo      | S14CT01                     | Notebook    | [2191cd2dd1](https://linux-hardware.org/?probe=2191cd2dd1) | Sep 26, 2022 |
| HP            | G42                         | Notebook    | [39a4836398](https://linux-hardware.org/?probe=39a4836398) | Sep 26, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [6bce247e38](https://linux-hardware.org/?probe=6bce247e38) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| Positivo      | S14SL01                     | Notebook    | [a6b3c260f4](https://linux-hardware.org/?probe=a6b3c260f4) | Sep 25, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Positivo      | S14SL01                     | Notebook    | [e09fcd6e38](https://linux-hardware.org/?probe=e09fcd6e38) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [107011cb20](https://linux-hardware.org/?probe=107011cb20) | Sep 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [939bba43d1](https://linux-hardware.org/?probe=939bba43d1) | Sep 25, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [b867406b76](https://linux-hardware.org/?probe=b867406b76) | Sep 25, 2022 |
| Acer          | AO532h                      | Notebook    | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [7fb024bb5d](https://linux-hardware.org/?probe=7fb024bb5d) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [1190ad2886](https://linux-hardware.org/?probe=1190ad2886) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [118cf21173](https://linux-hardware.org/?probe=118cf21173) | Sep 24, 2022 |
| Dell          | Latitude E5400              | Notebook    | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| Dell          | Latitude 3410               | Notebook    | [ba10ea9fc5](https://linux-hardware.org/?probe=ba10ea9fc5) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2322475867](https://linux-hardware.org/?probe=2322475867) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [170a3248f6](https://linux-hardware.org/?probe=170a3248f6) | Sep 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4658ef6703](https://linux-hardware.org/?probe=4658ef6703) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | Desktop     | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e9a7dd793](https://linux-hardware.org/?probe=1e9a7dd793) | Sep 24, 2022 |
| ASUSTek       | M2N68                       | Desktop     | [4b23dadbca](https://linux-hardware.org/?probe=4b23dadbca) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| Foxconn       | Q77M                        | Desktop     | [63d0fe0c57](https://linux-hardware.org/?probe=63d0fe0c57) | Sep 23, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [4ed9eae431](https://linux-hardware.org/?probe=4ed9eae431) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [76d9b33c76](https://linux-hardware.org/?probe=76d9b33c76) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [b02d161acb](https://linux-hardware.org/?probe=b02d161acb) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c05619dc16](https://linux-hardware.org/?probe=c05619dc16) | Sep 23, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [fef79bcff4](https://linux-hardware.org/?probe=fef79bcff4) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [fb451b6d7d](https://linux-hardware.org/?probe=fb451b6d7d) | Sep 22, 2022 |
| Avell High... | B.ON                        | Notebook    | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Sony          | SVE15125CBW                 | Notebook    | [50b65906b1](https://linux-hardware.org/?probe=50b65906b1) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | Desktop     | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [183f486a54](https://linux-hardware.org/?probe=183f486a54) | Sep 21, 2022 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Avell High... | B.ON                        | Notebook    | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [74d69dbd69](https://linux-hardware.org/?probe=74d69dbd69) | Sep 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5c6ebb2cfe](https://linux-hardware.org/?probe=5c6ebb2cfe) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [b5aad7f903](https://linux-hardware.org/?probe=b5aad7f903) | Sep 20, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [14351cab57](https://linux-hardware.org/?probe=14351cab57) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [55f97310c8](https://linux-hardware.org/?probe=55f97310c8) | Sep 20, 2022 |
| LG Electro... | C400-G.BC31P1               | Notebook    | [66c8977810](https://linux-hardware.org/?probe=66c8977810) | Sep 19, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [aaedf90f31](https://linux-hardware.org/?probe=aaedf90f31) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [37fc6237e2](https://linux-hardware.org/?probe=37fc6237e2) | Sep 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [40629d6fbc](https://linux-hardware.org/?probe=40629d6fbc) | Sep 19, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [b98206a5fb](https://linux-hardware.org/?probe=b98206a5fb) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| Positivo      | C14CR21                     | Notebook    | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Samsung       | 370E4K                      | Notebook    | [1a297b75f9](https://linux-hardware.org/?probe=1a297b75f9) | Sep 18, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [2905913e7e](https://linux-hardware.org/?probe=2905913e7e) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [411449bc6d](https://linux-hardware.org/?probe=411449bc6d) | Sep 18, 2022 |
| Intel         | H61                         | Desktop     | [923e50e023](https://linux-hardware.org/?probe=923e50e023) | Sep 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7b918ebeb8](https://linux-hardware.org/?probe=7b918ebeb8) | Sep 18, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [50758a53dd](https://linux-hardware.org/?probe=50758a53dd) | Sep 18, 2022 |
| MSI           | J1800I                      | Desktop     | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [edc0c871cb](https://linux-hardware.org/?probe=edc0c871cb) | Sep 17, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [89706d3dac](https://linux-hardware.org/?probe=89706d3dac) | Sep 17, 2022 |
| Intel         | X79M-S                      | Desktop     | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| Intel         | X79M-S                      | Desktop     | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [d70dc7ab47](https://linux-hardware.org/?probe=d70dc7ab47) | Sep 16, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [0bcb975501](https://linux-hardware.org/?probe=0bcb975501) | Sep 16, 2022 |
| Intel         | H61                         | Desktop     | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [8fed7863dd](https://linux-hardware.org/?probe=8fed7863dd) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [59811273b4](https://linux-hardware.org/?probe=59811273b4) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [d391ace7f8](https://linux-hardware.org/?probe=d391ace7f8) | Sep 16, 2022 |
| Dell          | G7 7588                     | Notebook    | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| HP            | ProBook 4530s               | Notebook    | [821a6eda47](https://linux-hardware.org/?probe=821a6eda47) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [0a02b8ef94](https://linux-hardware.org/?probe=0a02b8ef94) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| Positivo      | Mobile                      | Notebook    | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [24ba1c9bc3](https://linux-hardware.org/?probe=24ba1c9bc3) | Sep 15, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8ec7217b7d](https://linux-hardware.org/?probe=8ec7217b7d) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [0879f8d9ce](https://linux-hardware.org/?probe=0879f8d9ce) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [16cf967fc8](https://linux-hardware.org/?probe=16cf967fc8) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | Desktop     | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47ff6a8255](https://linux-hardware.org/?probe=47ff6a8255) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | Desktop     | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Compal        | NCL60/61                    | Notebook    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc83707f72](https://linux-hardware.org/?probe=bc83707f72) | Sep 12, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [4bae06f3d0](https://linux-hardware.org/?probe=4bae06f3d0) | Sep 12, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| Intel         | H61                         | Desktop     | [d805e24841](https://linux-hardware.org/?probe=d805e24841) | Sep 12, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Avell High... | B.ON                        | Notebook    | [f30bca74ab](https://linux-hardware.org/?probe=f30bca74ab) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Chuwi         | UBook                       | Tablet      | [89a54f0af1](https://linux-hardware.org/?probe=89a54f0af1) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [aa4d90c7e7](https://linux-hardware.org/?probe=aa4d90c7e7) | Sep 11, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [064b2bd5f2](https://linux-hardware.org/?probe=064b2bd5f2) | Sep 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7aad54fefa](https://linux-hardware.org/?probe=7aad54fefa) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [fab48b6c15](https://linux-hardware.org/?probe=fab48b6c15) | Sep 10, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [6bbebcbcb1](https://linux-hardware.org/?probe=6bbebcbcb1) | Sep 10, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| ASUSTek       | K53E                        | Notebook    | [d39f35f5d9](https://linux-hardware.org/?probe=d39f35f5d9) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b8a5448c05](https://linux-hardware.org/?probe=b8a5448c05) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [9f5bc258b6](https://linux-hardware.org/?probe=9f5bc258b6) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | Notebook    | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| Intel         | Unknown                     | Desktop     | [74059aa424](https://linux-hardware.org/?probe=74059aa424) | Sep 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [e6c0d3de61](https://linux-hardware.org/?probe=e6c0d3de61) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [944fa39fb6](https://linux-hardware.org/?probe=944fa39fb6) | Sep 09, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [8efdbea978](https://linux-hardware.org/?probe=8efdbea978) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [c716a6bba5](https://linux-hardware.org/?probe=c716a6bba5) | Sep 09, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [1cc84e9a0d](https://linux-hardware.org/?probe=1cc84e9a0d) | Sep 09, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [745c098d8a](https://linux-hardware.org/?probe=745c098d8a) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cc0a825c8e](https://linux-hardware.org/?probe=cc0a825c8e) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Intel         | X99                         | Desktop     | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| Dell          | Inspiron 5457               | Notebook    | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [f04353bb0e](https://linux-hardware.org/?probe=f04353bb0e) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [1d73ebcfb8](https://linux-hardware.org/?probe=1d73ebcfb8) | Sep 08, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [d3df9a2592](https://linux-hardware.org/?probe=d3df9a2592) | Sep 08, 2022 |
| Digibras      | US41II1                     | Notebook    | [890a4894cf](https://linux-hardware.org/?probe=890a4894cf) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [de1ddd77dd](https://linux-hardware.org/?probe=de1ddd77dd) | Sep 08, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [4942b09228](https://linux-hardware.org/?probe=4942b09228) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | Desktop     | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| Biostar       | G41D3C                      | Desktop     | [2825db69bf](https://linux-hardware.org/?probe=2825db69bf) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [104331cf4c](https://linux-hardware.org/?probe=104331cf4c) | Sep 07, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [f547e07cca](https://linux-hardware.org/?probe=f547e07cca) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| Positivo      | Smash                       | Notebook    | [0051f458c6](https://linux-hardware.org/?probe=0051f458c6) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b12a6d2146](https://linux-hardware.org/?probe=b12a6d2146) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [48a1236943](https://linux-hardware.org/?probe=48a1236943) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [b1bdd1703e](https://linux-hardware.org/?probe=b1bdd1703e) | Sep 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [1020dfb637](https://linux-hardware.org/?probe=1020dfb637) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f61f170b4c](https://linux-hardware.org/?probe=f61f170b4c) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Intel         | H61                         | Desktop     | [b2d888f266](https://linux-hardware.org/?probe=b2d888f266) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [93d596fc4f](https://linux-hardware.org/?probe=93d596fc4f) | Sep 05, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| Multilaser    | PC112                       | Convertible | [b4a0a8d399](https://linux-hardware.org/?probe=b4a0a8d399) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Alienware     | m15 R7                      | Notebook    | [c9d5bcb40f](https://linux-hardware.org/?probe=c9d5bcb40f) | Sep 05, 2022 |
| Intel         | B75                         | Desktop     | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f44a7ef51c](https://linux-hardware.org/?probe=f44a7ef51c) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| ASUSTek       | X45C                        | Notebook    | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [0e3fd8d374](https://linux-hardware.org/?probe=0e3fd8d374) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c876beae17](https://linux-hardware.org/?probe=c876beae17) | Sep 04, 2022 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [078680a25d](https://linux-hardware.org/?probe=078680a25d) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [e6fa43e12e](https://linux-hardware.org/?probe=e6fa43e12e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [920bfdae34](https://linux-hardware.org/?probe=920bfdae34) | Sep 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| Timi          | TM1701                      | Notebook    | [740d59830a](https://linux-hardware.org/?probe=740d59830a) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Intel         | H61                         | Desktop     | [af78b53f51](https://linux-hardware.org/?probe=af78b53f51) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [b697980a15](https://linux-hardware.org/?probe=b697980a15) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [11dd923e56](https://linux-hardware.org/?probe=11dd923e56) | Sep 02, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| AMI           | T3 MRD                      | Desktop     | [d0a254e1b7](https://linux-hardware.org/?probe=d0a254e1b7) | Sep 02, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [0e65ce891e](https://linux-hardware.org/?probe=0e65ce891e) | Sep 02, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [595f13e0b9](https://linux-hardware.org/?probe=595f13e0b9) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [9525064f53](https://linux-hardware.org/?probe=9525064f53) | Sep 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f42a136e4f](https://linux-hardware.org/?probe=f42a136e4f) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | G15 5510                    | Notebook    | [78f2f5c95a](https://linux-hardware.org/?probe=78f2f5c95a) | Sep 01, 2022 |
| Dell          | G3 3590                     | Notebook    | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| Lenovo        | 3168 NOK                    | Desktop     | [58c82b01e2](https://linux-hardware.org/?probe=58c82b01e2) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [ab93c1f314](https://linux-hardware.org/?probe=ab93c1f314) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [6e337cb132](https://linux-hardware.org/?probe=6e337cb132) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [cdac9cafaf](https://linux-hardware.org/?probe=cdac9cafaf) | Sep 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ad36524b16](https://linux-hardware.org/?probe=ad36524b16) | Sep 01, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [7759e41b1d](https://linux-hardware.org/?probe=7759e41b1d) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [c1d60c7b0b](https://linux-hardware.org/?probe=c1d60c7b0b) | Aug 31, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [dafd789095](https://linux-hardware.org/?probe=dafd789095) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e9386667fa](https://linux-hardware.org/?probe=e9386667fa) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [c26bf23cdd](https://linux-hardware.org/?probe=c26bf23cdd) | Aug 31, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [c72797ddaa](https://linux-hardware.org/?probe=c72797ddaa) | Aug 31, 2022 |
| Samsung       | 930QDB                      | Convertible | [90bcd97cbb](https://linux-hardware.org/?probe=90bcd97cbb) | Aug 31, 2022 |
| Samsung       | 930QDB                      | Convertible | [fec5bf86f1](https://linux-hardware.org/?probe=fec5bf86f1) | Aug 31, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [454c7382bd](https://linux-hardware.org/?probe=454c7382bd) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9fe8c04ec6](https://linux-hardware.org/?probe=9fe8c04ec6) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [dbc18dad43](https://linux-hardware.org/?probe=dbc18dad43) | Aug 30, 2022 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [251b320d54](https://linux-hardware.org/?probe=251b320d54) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Intel         | NUC7JYB M37316-500          | Mini pc     | [0d75ce63f8](https://linux-hardware.org/?probe=0d75ce63f8) | Aug 29, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [eedd8fa1eb](https://linux-hardware.org/?probe=eedd8fa1eb) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [59959102e0](https://linux-hardware.org/?probe=59959102e0) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| Sony          | VPCEB36GM                   | Notebook    | [4495872308](https://linux-hardware.org/?probe=4495872308) | Aug 29, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [ee3156dfc5](https://linux-hardware.org/?probe=ee3156dfc5) | Aug 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [c7ace10271](https://linux-hardware.org/?probe=c7ace10271) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | Notebook    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| Google        | Eve                         | Notebook    | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [211edd7b18](https://linux-hardware.org/?probe=211edd7b18) | Aug 28, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [6ba36ee616](https://linux-hardware.org/?probe=6ba36ee616) | Aug 28, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [8d86f689b4](https://linux-hardware.org/?probe=8d86f689b4) | Aug 28, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [09d8066f44](https://linux-hardware.org/?probe=09d8066f44) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [420036f4d6](https://linux-hardware.org/?probe=420036f4d6) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [d8a638184b](https://linux-hardware.org/?probe=d8a638184b) | Aug 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [7d3e13cfa9](https://linux-hardware.org/?probe=7d3e13cfa9) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [975f6a801d](https://linux-hardware.org/?probe=975f6a801d) | Aug 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [85e0bc5d57](https://linux-hardware.org/?probe=85e0bc5d57) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Positivo      | C14CR01                     | Notebook    | [bb9a4c427a](https://linux-hardware.org/?probe=bb9a4c427a) | Aug 27, 2022 |
| Alienware     | m15 R6                      | Notebook    | [d39642f1ce](https://linux-hardware.org/?probe=d39642f1ce) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [b51f7dfba6](https://linux-hardware.org/?probe=b51f7dfba6) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [c8d0dcb323](https://linux-hardware.org/?probe=c8d0dcb323) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [84b14ba399](https://linux-hardware.org/?probe=84b14ba399) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [f2de49c59b](https://linux-hardware.org/?probe=f2de49c59b) | Aug 26, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [d71a1ce240](https://linux-hardware.org/?probe=d71a1ce240) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [21e69486fd](https://linux-hardware.org/?probe=21e69486fd) | Aug 26, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [46512c691b](https://linux-hardware.org/?probe=46512c691b) | Aug 26, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [47efe2482f](https://linux-hardware.org/?probe=47efe2482f) | Aug 25, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Samsung       | 550XDA                      | Notebook    | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [da0b51aa63](https://linux-hardware.org/?probe=da0b51aa63) | Aug 25, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [635925265e](https://linux-hardware.org/?probe=635925265e) | Aug 25, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [437118237f](https://linux-hardware.org/?probe=437118237f) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0b0b30459b](https://linux-hardware.org/?probe=0b0b30459b) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| OEM           | A320                        | Desktop     | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| HP            | 3397                        | Desktop     | [f65d0fdb85](https://linux-hardware.org/?probe=f65d0fdb85) | Aug 24, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [37c79f953b](https://linux-hardware.org/?probe=37c79f953b) | Aug 24, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fce2c90c7e](https://linux-hardware.org/?probe=fce2c90c7e) | Aug 24, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [b456a14fe0](https://linux-hardware.org/?probe=b456a14fe0) | Aug 24, 2022 |
| ASUSTek       | X202E                       | Notebook    | [b814b9f427](https://linux-hardware.org/?probe=b814b9f427) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | Notebook    | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d5b057d1c9](https://linux-hardware.org/?probe=d5b057d1c9) | Aug 23, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3507cf3eab](https://linux-hardware.org/?probe=3507cf3eab) | Aug 23, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [d394d086d9](https://linux-hardware.org/?probe=d394d086d9) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | Notebook    | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [514172ddcc](https://linux-hardware.org/?probe=514172ddcc) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [dd86526296](https://linux-hardware.org/?probe=dd86526296) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | Notebook    | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| AMI           | Cherry Trail Tablet         | Desktop     | [8cdf70d6e3](https://linux-hardware.org/?probe=8cdf70d6e3) | Aug 23, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [092dcdf5b7](https://linux-hardware.org/?probe=092dcdf5b7) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3c41ecc4e0](https://linux-hardware.org/?probe=3c41ecc4e0) | Aug 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [323faca611](https://linux-hardware.org/?probe=323faca611) | Aug 22, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [53a4b425d3](https://linux-hardware.org/?probe=53a4b425d3) | Aug 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ea0218b031](https://linux-hardware.org/?probe=ea0218b031) | Aug 22, 2022 |
| AMI           | Unknown                     | Notebook    | [b6004987ab](https://linux-hardware.org/?probe=b6004987ab) | Aug 22, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [5270930555](https://linux-hardware.org/?probe=5270930555) | Aug 22, 2022 |
| ASUSTek       | X45U                        | Notebook    | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| ASUSTek       | K53E                        | Notebook    | [65ddd1bb6f](https://linux-hardware.org/?probe=65ddd1bb6f) | Aug 22, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [9d0f972a5f](https://linux-hardware.org/?probe=9d0f972a5f) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | Desktop     | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [2f3937854b](https://linux-hardware.org/?probe=2f3937854b) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [64b9832653](https://linux-hardware.org/?probe=64b9832653) | Aug 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
| HP            | Mini 110-3100               | Notebook    | [1e27123078](https://linux-hardware.org/?probe=1e27123078) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Acer          | Unknown                     | Notebook    | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [d9ab8accea](https://linux-hardware.org/?probe=d9ab8accea) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6ff066abac](https://linux-hardware.org/?probe=6ff066abac) | Aug 21, 2022 |
| Positivo      | C14RV01                     | Notebook    | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | Desktop     | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [cae0d518ee](https://linux-hardware.org/?probe=cae0d518ee) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [aaacebef4a](https://linux-hardware.org/?probe=aaacebef4a) | Aug 21, 2022 |
| Positivo      | C14CU51                     | Notebook    | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| Positivo      | Mobile                      | Notebook    | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | Notebook    | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6503feb8b7](https://linux-hardware.org/?probe=6503feb8b7) | Aug 20, 2022 |
| Positivo      | Q4128C-S                    | Notebook    | [abe16f9b0c](https://linux-hardware.org/?probe=abe16f9b0c) | Aug 19, 2022 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [2e1445b2c8](https://linux-hardware.org/?probe=2e1445b2c8) | Aug 19, 2022 |
| Dell          | 0TVR1F A01                  | Desktop     | [1b8906bb20](https://linux-hardware.org/?probe=1b8906bb20) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| Gateway       | NV55C                       | Notebook    | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| ASUSTek       | K45A                        | Notebook    | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Arquimedes... | 760GM                       | Desktop     | [5f653afdff](https://linux-hardware.org/?probe=5f653afdff) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [00a40c053e](https://linux-hardware.org/?probe=00a40c053e) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4242f8b9c2](https://linux-hardware.org/?probe=4242f8b9c2) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [bac870dd75](https://linux-hardware.org/?probe=bac870dd75) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [52b9313de4](https://linux-hardware.org/?probe=52b9313de4) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | Notebook    | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| Intel         | Unknown                     | Desktop     | [23f3bdae8a](https://linux-hardware.org/?probe=23f3bdae8a) | Aug 18, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [aa18fee893](https://linux-hardware.org/?probe=aa18fee893) | Aug 18, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [039ab9ead1](https://linux-hardware.org/?probe=039ab9ead1) | Aug 17, 2022 |
| HP            | 14                          | Notebook    | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| Positivo      | S14CT01                     | Notebook    | [22d8d4f3a2](https://linux-hardware.org/?probe=22d8d4f3a2) | Aug 17, 2022 |
| Positivo      | S14CT01                     | Notebook    | [2b561def97](https://linux-hardware.org/?probe=2b561def97) | Aug 17, 2022 |
| ASUSTek       | K45A                        | Notebook    | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| HP            | 2215                        | Desktop     | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | Desktop     | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | Notebook    | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | Notebook    | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [3e3ab3842f](https://linux-hardware.org/?probe=3e3ab3842f) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3e7b575743](https://linux-hardware.org/?probe=3e7b575743) | Aug 16, 2022 |
| VS Company    | H61H2                       | Desktop     | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Intel         | B75                         | Desktop     | [8eb918ea53](https://linux-hardware.org/?probe=8eb918ea53) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| AMI           | Unknown                     | Notebook    | [a1a8c0b2c5](https://linux-hardware.org/?probe=a1a8c0b2c5) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| Sony          | VGN-NR230AE                 | Notebook    | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | Notebook    | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [bfcafd66de](https://linux-hardware.org/?probe=bfcafd66de) | Aug 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1e198f7c54](https://linux-hardware.org/?probe=1e198f7c54) | Aug 15, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [3a6b82f27f](https://linux-hardware.org/?probe=3a6b82f27f) | Aug 15, 2022 |
| ASUSTek       | K84C                        | Notebook    | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Itautec       | Infoway W7425               | Notebook    | [64b3153e8a](https://linux-hardware.org/?probe=64b3153e8a) | Aug 15, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [cafdc06a51](https://linux-hardware.org/?probe=cafdc06a51) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [dc086ed32c](https://linux-hardware.org/?probe=dc086ed32c) | Aug 14, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [7c37c2a6d7](https://linux-hardware.org/?probe=7c37c2a6d7) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [6c7f56d3cd](https://linux-hardware.org/?probe=6c7f56d3cd) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [4443a6c129](https://linux-hardware.org/?probe=4443a6c129) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [082a5297bd](https://linux-hardware.org/?probe=082a5297bd) | Aug 14, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [83b14f40e6](https://linux-hardware.org/?probe=83b14f40e6) | Aug 14, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [15633ed7b1](https://linux-hardware.org/?probe=15633ed7b1) | Aug 14, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [c5737e52bd](https://linux-hardware.org/?probe=c5737e52bd) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [42223a802a](https://linux-hardware.org/?probe=42223a802a) | Aug 14, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [14fa58515f](https://linux-hardware.org/?probe=14fa58515f) | Aug 13, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [7f8289a8f3](https://linux-hardware.org/?probe=7f8289a8f3) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | Notebook    | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e39c1b59a6](https://linux-hardware.org/?probe=e39c1b59a6) | Aug 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b7418c601b](https://linux-hardware.org/?probe=b7418c601b) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [f17b91fcb8](https://linux-hardware.org/?probe=f17b91fcb8) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [837e6e891d](https://linux-hardware.org/?probe=837e6e891d) | Aug 13, 2022 |
| Positivo      | Mobile                      | Notebook    | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| Samsung       | 550XDA                      | Notebook    | [4964cf32aa](https://linux-hardware.org/?probe=4964cf32aa) | Aug 12, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [be52876050](https://linux-hardware.org/?probe=be52876050) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| Samsung       | R430/R480/R440              | Notebook    | [39323c99dc](https://linux-hardware.org/?probe=39323c99dc) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Positivo      | Q4128C-S                    | Notebook    | [4f8b07c958](https://linux-hardware.org/?probe=4f8b07c958) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | Notebook    | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [074b25e3a3](https://linux-hardware.org/?probe=074b25e3a3) | Aug 12, 2022 |
| Positivo      | C14CR21                     | Notebook    | [6e7b0da365](https://linux-hardware.org/?probe=6e7b0da365) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [98cc4a3075](https://linux-hardware.org/?probe=98cc4a3075) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [9aae49b54c](https://linux-hardware.org/?probe=9aae49b54c) | Aug 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3f67c470be](https://linux-hardware.org/?probe=3f67c470be) | Aug 11, 2022 |
| Avell High... | B.ON                        | Notebook    | [b057c64850](https://linux-hardware.org/?probe=b057c64850) | Aug 11, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [087818a904](https://linux-hardware.org/?probe=087818a904) | Aug 11, 2022 |
| Dell          | Vostro 3460                 | Notebook    | [fbaf8208cb](https://linux-hardware.org/?probe=fbaf8208cb) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | Notebook    | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [c66de39c4c](https://linux-hardware.org/?probe=c66de39c4c) | Aug 11, 2022 |
| ASUSTek       | X510UR                      | Notebook    | [3faeed2cc1](https://linux-hardware.org/?probe=3faeed2cc1) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [d081204e0a](https://linux-hardware.org/?probe=d081204e0a) | Aug 10, 2022 |
| Dell          | G3 3590                     | Notebook    | [6284e4a400](https://linux-hardware.org/?probe=6284e4a400) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [19c10fbafb](https://linux-hardware.org/?probe=19c10fbafb) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [3151f7847e](https://linux-hardware.org/?probe=3151f7847e) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3aa3a0b4ee](https://linux-hardware.org/?probe=3aa3a0b4ee) | Aug 10, 2022 |
| Compaq        | Presario CQ-31              | Notebook    | [d22794a255](https://linux-hardware.org/?probe=d22794a255) | Aug 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e54e09e3cf](https://linux-hardware.org/?probe=e54e09e3cf) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d34fcfc4f7](https://linux-hardware.org/?probe=d34fcfc4f7) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5a84fd5a16](https://linux-hardware.org/?probe=5a84fd5a16) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [350a6d8583](https://linux-hardware.org/?probe=350a6d8583) | Aug 09, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a24a03a6dd](https://linux-hardware.org/?probe=a24a03a6dd) | Aug 09, 2022 |
| Alienware     | x15 R1                      | Notebook    | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [95de2fe5b3](https://linux-hardware.org/?probe=95de2fe5b3) | Aug 08, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [742452483f](https://linux-hardware.org/?probe=742452483f) | Aug 08, 2022 |
| Lenovo        | ThinkPad L450 20DSS0DH1N    | Notebook    | [1aa79c3fef](https://linux-hardware.org/?probe=1aa79c3fef) | Aug 08, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [65b4e485ad](https://linux-hardware.org/?probe=65b4e485ad) | Aug 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [221d7636db](https://linux-hardware.org/?probe=221d7636db) | Aug 08, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7bb5745101](https://linux-hardware.org/?probe=7bb5745101) | Aug 08, 2022 |
| Intel         | H61                         | Desktop     | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [aada9001dd](https://linux-hardware.org/?probe=aada9001dd) | Aug 08, 2022 |
| HP            | Mini 110-3100               | Notebook    | [f91eefcb06](https://linux-hardware.org/?probe=f91eefcb06) | Aug 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| Avell High... | B.ON                        | Notebook    | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| HP            | 1998                        | Desktop     | [1ae818eb7c](https://linux-hardware.org/?probe=1ae818eb7c) | Aug 07, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [7e9a6b9e85](https://linux-hardware.org/?probe=7e9a6b9e85) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | Desktop     | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| PCWare        | IPX3060E                    | Desktop     | [3fc0886f3b](https://linux-hardware.org/?probe=3fc0886f3b) | Aug 06, 2022 |
| Positivo      | Mobile                      | Notebook    | [017b8eeb6b](https://linux-hardware.org/?probe=017b8eeb6b) | Aug 06, 2022 |
| Positivo      | Mobile                      | Notebook    | [fe169d2119](https://linux-hardware.org/?probe=fe169d2119) | Aug 06, 2022 |
| Sony          | VPCSB35FB                   | Notebook    | [edbd7a9cb8](https://linux-hardware.org/?probe=edbd7a9cb8) | Aug 06, 2022 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [cf3ed2131f](https://linux-hardware.org/?probe=cf3ed2131f) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | Notebook    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [39b2c17704](https://linux-hardware.org/?probe=39b2c17704) | Aug 06, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [6cec3fa330](https://linux-hardware.org/?probe=6cec3fa330) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | Desktop     | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Compaq        | 430                         | Notebook    | [581a8bbf00](https://linux-hardware.org/?probe=581a8bbf00) | Aug 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3f1ac55a4b](https://linux-hardware.org/?probe=3f1ac55a4b) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| HP            | ProBook 4440s               | Notebook    | [cb7b9336ac](https://linux-hardware.org/?probe=cb7b9336ac) | Aug 04, 2022 |
| MSI           | Katana GF66 11UC            | Notebook    | [8d210c5007](https://linux-hardware.org/?probe=8d210c5007) | Aug 04, 2022 |
| PCWare        | IPX3060E                    | Desktop     | [d5045f1364](https://linux-hardware.org/?probe=d5045f1364) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [2030bc92d7](https://linux-hardware.org/?probe=2030bc92d7) | Aug 04, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0ef9fef16d](https://linux-hardware.org/?probe=0ef9fef16d) | Aug 04, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5fe90b268d](https://linux-hardware.org/?probe=5fe90b268d) | Aug 04, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [8bd9c2f957](https://linux-hardware.org/?probe=8bd9c2f957) | Aug 04, 2022 |
| Positivo      | S14BW01                     | Notebook    | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| Sony          | VPCCW13FB                   | Notebook    | [34db85d2d4](https://linux-hardware.org/?probe=34db85d2d4) | Aug 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [91ecf4a05f](https://linux-hardware.org/?probe=91ecf4a05f) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | Notebook    | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [aed4690a47](https://linux-hardware.org/?probe=aed4690a47) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1eb69af2d](https://linux-hardware.org/?probe=a1eb69af2d) | Aug 03, 2022 |
| Clevo         | W240BU                      | Notebook    | [df5302b1c3](https://linux-hardware.org/?probe=df5302b1c3) | Aug 03, 2022 |
| MSI           | Boston                      | Desktop     | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| Positivo      | Smash                       | Notebook    | [fd44d353d3](https://linux-hardware.org/?probe=fd44d353d3) | Aug 03, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [1dfd4fe5ba](https://linux-hardware.org/?probe=1dfd4fe5ba) | Aug 03, 2022 |
| Biostar       | G41D3C                      | Desktop     | [8a5b81e472](https://linux-hardware.org/?probe=8a5b81e472) | Aug 03, 2022 |
| Sony          | VPCCW13FB                   | Notebook    | [2d36ec46e0](https://linux-hardware.org/?probe=2d36ec46e0) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [03770f280e](https://linux-hardware.org/?probe=03770f280e) | Aug 02, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [cd42712c4c](https://linux-hardware.org/?probe=cd42712c4c) | Aug 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8a4208caa8](https://linux-hardware.org/?probe=8a4208caa8) | Aug 02, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [be6e34d630](https://linux-hardware.org/?probe=be6e34d630) | Aug 02, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | G15 5510                    | Notebook    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| HP            | 3047h                       | Desktop     | [a8301b8155](https://linux-hardware.org/?probe=a8301b8155) | Aug 02, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ec7e5864c2](https://linux-hardware.org/?probe=ec7e5864c2) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [73658d3308](https://linux-hardware.org/?probe=73658d3308) | Aug 02, 2022 |
| Positivo      | Q232A                       | Notebook    | [da99b8ab1e](https://linux-hardware.org/?probe=da99b8ab1e) | Aug 01, 2022 |
| Positivo      | Q232A                       | Notebook    | [7d860e8f5d](https://linux-hardware.org/?probe=7d860e8f5d) | Aug 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2c00e0e66e](https://linux-hardware.org/?probe=2c00e0e66e) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| Unknown       | 1.0                         | All in one  | [8145704100](https://linux-hardware.org/?probe=8145704100) | Aug 01, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [0843909534](https://linux-hardware.org/?probe=0843909534) | Aug 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | Notebook    | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 1494      | 12.92%  |
| Ubuntu 18.04      | 1022      | 8.84%   |
| OpenMandriva 4.2  | 335       | 2.9%    |
| Pop!_OS 20.04     | 316       | 2.73%   |
| Linux Mint 20     | 313       | 2.71%   |
| Linux Mint 19.3   | 282       | 2.44%   |
| OpenMandriva 4.3  | 239       | 2.07%   |
| Linux Mint 19.1   | 235       | 2.03%   |
| Ubuntu 22.04      | 233       | 2.02%   |
| Ubuntu 19.04      | 218       | 1.89%   |
| KDE neon 20.04    | 213       | 1.84%   |
| Linux Mint 20.1   | 202       | 1.75%   |
| Linux Mint 20.3   | 190       | 1.64%   |
| Arch              | 189       | 1.63%   |
| Linux Mint 20.2   | 177       | 1.53%   |
| Ubuntu 19.10      | 173       | 1.5%    |
| Manjaro           | 163       | 1.41%   |
| Debian 10         | 155       | 1.34%   |
| Zorin 15          | 147       | 1.27%   |
| Zorin 16          | 139       | 1.2%    |
| Pop!_OS 21.04     | 127       | 1.1%    |
| Pop!_OS 20.10     | 127       | 1.1%    |
| Debian 11         | 126       | 1.09%   |
| Fedora 34         | 119       | 1.03%   |
| Xubuntu 20.04     | 114       | 0.99%   |
| Pop!_OS 22.04     | 111       | 0.96%   |
| Fedora 32         | 111       | 0.96%   |
| Pop!_OS 21.10     | 110       | 0.95%   |
| Fedora 35         | 107       | 0.93%   |
| Fedora 36         | 105       | 0.91%   |
| Fedora 33         | 105       | 0.91%   |
| Linux Mint 19.2   | 102       | 0.88%   |
| Kubuntu 20.04     | 101       | 0.87%   |
| Ubuntu 20.10      | 98        | 0.85%   |
| Ubuntu MATE 20.04 | 97        | 0.84%   |
| Arch Rolling      | 95        | 0.82%   |
| Ubuntu 18.10      | 83        | 0.72%   |
| Endless 3.7.8     | 77        | 0.67%   |
| Ubuntu 21.10      | 76        | 0.66%   |
| Endless 3.9.5     | 72        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3416      | 30.86%  |
| Linux Mint    | 1524      | 13.77%  |
| Endless       | 983       | 8.88%   |
| Pop!_OS       | 760       | 6.87%   |
| OpenMandriva  | 631       | 5.7%    |
| Fedora        | 603       | 5.45%   |
| Debian        | 372       | 3.36%   |
| Manjaro       | 335       | 3.03%   |
| Zorin         | 295       | 2.67%   |
| Arch          | 272       | 2.46%   |
| KDE neon      | 251       | 2.27%   |
| Xubuntu       | 210       | 1.9%    |
| Kubuntu       | 189       | 1.71%   |
| Ubuntu MATE   | 129       | 1.17%   |
| ROSA          | 120       | 1.08%   |
| Lubuntu       | 96        | 0.87%   |
| openSUSE      | 89        | 0.8%    |
| Elementary    | 84        | 0.76%   |
| Ubuntu Unity  | 79        | 0.71%   |
| LMDE          | 56        | 0.51%   |
| Kali          | 46        | 0.42%   |
| Deepin        | 45        | 0.41%   |
| LinuxFX       | 40        | 0.36%   |
| Ubuntu Budgie | 38        | 0.34%   |
| ArcoLinux     | 38        | 0.34%   |
| Clear Linux   | 34        | 0.31%   |
| BlackPanther  | 30        | 0.27%   |
| CentOS        | 28        | 0.25%   |
| BigLinux      | 19        | 0.17%   |
| EndeavourOS   | 18        | 0.16%   |
| Gentoo        | 16        | 0.14%   |
| Peppermint    | 14        | 0.13%   |
| Parrot        | 14        | 0.13%   |
| UbuntuDDE     | 12        | 0.11%   |
| MX            | 12        | 0.11%   |
| Solus         | 11        | 0.1%    |
| Linux Lite    | 11        | 0.1%    |
| Garuda Linux  | 11        | 0.1%    |
| Reborn OS     | 10        | 0.09%   |
| Void Linux    | 7         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 708       | 5.69%   |
| 5.10.14-desktop-1omv4002 | 324       | 2.6%    |
| 5.8.0-14-generic         | 295       | 2.37%   |
| 5.16.7-desktop-1omv4003  | 232       | 1.86%   |
| 4.15.0-46-generic        | 156       | 1.25%   |
| 5.3.0-28-generic         | 145       | 1.16%   |
| 5.4.0-48-generic         | 138       | 1.11%   |
| 5.4.0-19-generic         | 138       | 1.11%   |
| 5.4.0-7634-generic       | 123       | 0.99%   |
| 5.4.0-40-generic         | 111       | 0.89%   |
| 5.4.0-58-generic         | 108       | 0.87%   |
| 5.4.0-26-generic         | 105       | 0.84%   |
| 5.4.0-52-generic         | 101       | 0.81%   |
| 4.18.0-15-generic        | 97        | 0.78%   |
| 5.4.0-47-generic         | 96        | 0.77%   |
| 5.11.0-35-generic        | 90        | 0.72%   |
| 5.3.0-40-generic         | 89        | 0.72%   |
| 5.11.0-7620-generic      | 78        | 0.63%   |
| 5.0.0-32-generic         | 78        | 0.63%   |
| 5.3.0-46-generic         | 77        | 0.62%   |
| 5.0.0-37-generic         | 72        | 0.58%   |
| 4.15.0-20-generic        | 72        | 0.58%   |
| 5.4.0-70-generic         | 71        | 0.57%   |
| 5.4.0-72-generic         | 68        | 0.55%   |
| 5.4.0-91-generic         | 63        | 0.51%   |
| 5.4.0-80-generic         | 63        | 0.51%   |
| 5.3.0-23-generic         | 63        | 0.51%   |
| 5.4.0-29-generic         | 62        | 0.5%    |
| 5.15.0-46-generic        | 62        | 0.5%    |
| 4.18.0-16-generic        | 62        | 0.5%    |
| 5.4.0-65-generic         | 61        | 0.49%   |
| 5.4.0-37-generic         | 61        | 0.49%   |
| 5.4.0-39-generic         | 60        | 0.48%   |
| 5.0.0-25-generic         | 60        | 0.48%   |
| 5.8.0-7630-generic       | 58        | 0.47%   |
| 5.4.0-74-generic         | 58        | 0.47%   |
| 5.3.0-19-generic         | 58        | 0.47%   |
| 5.13.0-30-generic        | 58        | 0.47%   |
| 5.11.0-37-generic        | 58        | 0.47%   |
| 5.11.0-27-generic        | 58        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 2974      | 25.26%  |
| 4.15.0  | 938       | 7.97%   |
| 5.8.0   | 876       | 7.44%   |
| 5.3.0   | 798       | 6.78%   |
| 5.11.0  | 675       | 5.73%   |
| 5.0.0   | 561       | 4.77%   |
| 5.13.0  | 455       | 3.86%   |
| 4.18.0  | 415       | 3.53%   |
| 5.15.0  | 406       | 3.45%   |
| 5.10.14 | 326       | 2.77%   |
| 5.16.7  | 232       | 1.97%   |
| 4.19.0  | 184       | 1.56%   |
| 5.10.0  | 171       | 1.45%   |
| 5.17.5  | 54        | 0.46%   |
| 5.19.0  | 49        | 0.42%   |
| 5.7.9   | 47        | 0.4%    |
| 4.4.0   | 45        | 0.38%   |
| 5.16.11 | 40        | 0.34%   |
| 4.9.0   | 38        | 0.32%   |
| 5.14.0  | 33        | 0.28%   |
| 5.15.5  | 31        | 0.26%   |
| 5.7.0   | 30        | 0.25%   |
| 5.15.15 | 30        | 0.25%   |
| 5.9.16  | 28        | 0.24%   |
| 5.6.19  | 27        | 0.23%   |
| 4.9.60  | 27        | 0.23%   |
| 5.3.18  | 25        | 0.21%   |
| 4.18.16 | 25        | 0.21%   |
| 5.13.19 | 24        | 0.2%    |
| 5.7.10  | 22        | 0.19%   |
| 5.11.12 | 22        | 0.19%   |
| 5.16.15 | 21        | 0.18%   |
| 5.18.12 | 20        | 0.17%   |
| 5.18.10 | 20        | 0.17%   |
| 5.15.8  | 20        | 0.17%   |
| 5.12.4  | 19        | 0.16%   |
| 5.9.11  | 18        | 0.15%   |
| 5.6.15  | 18        | 0.15%   |
| 5.16.0  | 18        | 0.15%   |
| 4.9.20  | 18        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3097      | 26.62%  |
| 5.8     | 989       | 8.5%    |
| 4.15    | 938       | 8.06%   |
| 5.3     | 869       | 7.47%   |
| 5.11    | 769       | 6.61%   |
| 5.10    | 687       | 5.91%   |
| 5.15    | 638       | 5.48%   |
| 5.0     | 603       | 5.18%   |
| 5.13    | 547       | 4.7%    |
| 4.18    | 448       | 3.85%   |
| 5.16    | 406       | 3.49%   |
| 4.19    | 220       | 1.89%   |
| 5.7     | 172       | 1.48%   |
| 5.17    | 144       | 1.24%   |
| 5.19    | 138       | 1.19%   |
| 5.18    | 129       | 1.11%   |
| 5.6     | 126       | 1.08%   |
| 5.14    | 121       | 1.04%   |
| 5.12    | 113       | 0.97%   |
| 5.9     | 110       | 0.95%   |
| 4.9     | 103       | 0.89%   |
| 5.5     | 50        | 0.43%   |
| 4.4     | 50        | 0.43%   |
| 5.1     | 39        | 0.34%   |
| 5.2     | 29        | 0.25%   |
| 6.0     | 23        | 0.2%    |
| 3.10    | 14        | 0.12%   |
| 4.13    | 13        | 0.11%   |
| 4.1     | 12        | 0.1%    |
| 4.20    | 10        | 0.09%   |
| 4.10    | 8         | 0.07%   |
| 4.12    | 6         | 0.05%   |
| 4.14    | 5         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 4.17    | 2         | 0.02%   |
| 6.1     | 1         | 0.01%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 10295     | 96.98%  |
| i686    | 294       | 2.77%   |
| aarch64 | 16        | 0.15%   |
| armv7l  | 11        | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 5048      | 45.53%  |
| Unknown                  | 1783      | 16.08%  |
| KDE5                     | 1245      | 11.23%  |
| X-Cinnamon               | 875       | 7.89%   |
| XFCE                     | 733       | 6.61%   |
| MATE                     | 323       | 2.91%   |
| KDE                      | 310       | 2.8%    |
| Cinnamon                 | 215       | 1.94%   |
| LXQt                     | 90        | 0.81%   |
| Unity                    | 81        | 0.73%   |
| Pantheon                 | 72        | 0.65%   |
| KDE4                     | 66        | 0.6%    |
| Deepin                   | 56        | 0.51%   |
| Budgie                   | 55        | 0.5%    |
| LXDE                     | 48        | 0.43%   |
| i3                       | 26        | 0.23%   |
| GNOME Flashback          | 16        | 0.14%   |
| GNOME Classic            | 12        | 0.11%   |
| awesome                  | 9         | 0.08%   |
| Enlightenment            | 5         | 0.05%   |
| sway                     | 4         | 0.04%   |
| Openbox                  | 4         | 0.04%   |
| bspwm                    | 3         | 0.03%   |
| qtile                    | 2         | 0.02%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| jwm                      | 1         | 0.01%   |
| icewm                    | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 8981      | 82.71%  |
| Wayland | 934       | 8.6%    |
| Unknown | 870       | 8.01%   |
| Tty     | 72        | 0.66%   |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7127      | 65.02%  |
| SDDM    | 1128      | 10.29%  |
| GDM     | 1125      | 10.26%  |
| TDM     | 538       | 4.91%   |
| LightDM | 483       | 4.41%   |
| GDM3    | 476       | 4.34%   |
| KDM     | 66        | 0.6%    |
| XDM     | 8         | 0.07%   |
| SLiM    | 5         | 0.05%   |
| LXDM    | 3         | 0.03%   |
| MDM     | 2         | 0.02%   |
| SLIMSKI | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 7093      | 65.37%  |
| en_US       | 1785      | 16.45%  |
| Unknown     | 1691      | 15.59%  |
| C           | 151       | 1.39%   |
| en_GB       | 42        | 0.39%   |
| pt_PT       | 38        | 0.35%   |
| es_ES       | 14        | 0.13%   |
| en_CA       | 6         | 0.06%   |
| de_DE       | 5         | 0.05%   |
| fr_FR       | 4         | 0.04%   |
| POSIX       | 3         | 0.03%   |
| ja_JP       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| C.UTF8      | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6229      | 57.38%  |
| EFI  | 4626      | 42.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 8531      | 78.66%  |
| Overlay | 795       | 7.33%   |
| Unknown | 702       | 6.47%   |
| Btrfs   | 630       | 5.81%   |
| Xfs     | 76        | 0.7%    |
| Zfs     | 37        | 0.34%   |
| Tmpfs   | 23        | 0.21%   |
| Ext3    | 21        | 0.19%   |
| Ext2    | 16        | 0.15%   |
| F2fs    | 11        | 0.1%    |
| Aufs    | 3         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7507      | 69.16%  |
| GPT     | 2172      | 20.01%  |
| MBR     | 1176      | 10.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9546      | 88.72%  |
| Yes       | 1214      | 11.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7978      | 73.99%  |
| Yes       | 2805      | 26.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1715      | 16.17%  |
| ASUSTek Computer        | 1417      | 13.36%  |
| Acer                    | 1284      | 12.1%   |
| Lenovo                  | 891       | 8.4%    |
| Gigabyte Technology     | 694       | 6.54%   |
| Positivo                | 623       | 5.87%   |
| Hewlett-Packard         | 577       | 5.44%   |
| Samsung Electronics     | 544       | 5.13%   |
| Intel                   | 375       | 3.53%   |
| ASRock                  | 352       | 3.32%   |
| Unknown                 | 206       | 1.94%   |
| MSI                     | 184       | 1.73%   |
| Sony                    | 142       | 1.34%   |
| LG Electronics          | 114       | 1.07%   |
| Apple                   | 104       | 0.98%   |
| Semp Toshiba            | 100       | 0.94%   |
| Itautec                 | 100       | 0.94%   |
| PCWare                  | 98        | 0.92%   |
| Biostar                 | 78        | 0.74%   |
| Avell High Performance  | 65        | 0.61%   |
| Pegatron                | 64        | 0.6%    |
| Digibras                | 63        | 0.59%   |
| ECS                     | 58        | 0.55%   |
| OEM                     | 47        | 0.44%   |
| Philco                  | 44        | 0.41%   |
| Multilaser              | 40        | 0.38%   |
| Toshiba                 | 33        | 0.31%   |
| Compaq                  | 33        | 0.31%   |
| Positivo Bahia - VAIO   | 28        | 0.26%   |
| Megaware                | 28        | 0.26%   |
| Foxconn                 | 27        | 0.25%   |
| Notebook                | 24        | 0.23%   |
| Huanan                  | 24        | 0.23%   |
| Clevo                   | 21        | 0.2%    |
| Gateway                 | 19        | 0.18%   |
| Login Informatica       | 18        | 0.17%   |
| Compal                  | 18        | 0.17%   |
| Raspberry Pi Foundation | 17        | 0.16%   |
| Supermicro              | 14        | 0.13%   |
| Qbex                    | 14        | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 261       | 2.46%   |
| Acer Nitro AN515-54                         | 132       | 1.24%   |
| ASUS All Series                             | 131       | 1.23%   |
| Positivo Mobile                             | 114       | 1.07%   |
| Acer Nitro AN515-44                         | 75        | 0.71%   |
| Acer Aspire A315-53                         | 67        | 0.63%   |
| Samsung 340XAA/350XAA/550XAA                | 65        | 0.61%   |
| Intel H61                                   | 62        | 0.58%   |
| Dell Inspiron 5566                          | 54        | 0.51%   |
| ASUS PRIME B450M-GAMING/BR                  | 54        | 0.51%   |
| Lenovo IdeaPad S145-15API 81V7              | 53        | 0.5%    |
| Dell Inspiron 3583                          | 53        | 0.5%    |
| Lenovo IdeaPad 330-15IKB 81FE               | 52        | 0.49%   |
| Acer Aspire A315-34                         | 52        | 0.49%   |
| Acer Nitro AN517-51                         | 50        | 0.47%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 48        | 0.45%   |
| Dell Inspiron 15-3567                       | 47        | 0.44%   |
| ASRock A320M-HD                             | 47        | 0.44%   |
| ASUS PRIME A320M-K/BR                       | 46        | 0.43%   |
| Acer Nitro AN515-43                         | 44        | 0.41%   |
| Acer Aspire A515-51                         | 44        | 0.41%   |
| Semp Toshiba STI                            | 42        | 0.4%    |
| Intel H55                                   | 41        | 0.39%   |
| ASUS M5A78L-M LX/BR                         | 41        | 0.39%   |
| HP G42                                      | 39        | 0.37%   |
| Samsung 300E5M/300E5L                       | 37        | 0.35%   |
| Positivo S14CT01                            | 37        | 0.35%   |
| Itautec Infoway                             | 37        | 0.35%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 36        | 0.34%   |
| Acer Nitro AN515-52                         | 36        | 0.34%   |
| Dell Inspiron 3442                          | 35        | 0.33%   |
| Dell Inspiron 3421                          | 35        | 0.33%   |
| Gigabyte H61M-S1                            | 34        | 0.32%   |
| Dell Inspiron N4050                         | 32        | 0.3%    |
| Dell Inspiron 7520                          | 32        | 0.3%    |
| ASUS P8H61-M LX3 R2.0                       | 31        | 0.29%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 30        | 0.28%   |
| HP Pavilion g4                              | 30        | 0.28%   |
| Gigabyte A320M-S2H                          | 30        | 0.28%   |
| Dell Inspiron 1545                          | 30        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 999       | 9.42%   |
| Acer Aspire        | 828       | 7.8%    |
| Lenovo IdeaPad     | 425       | 4.01%   |
| Acer Nitro         | 367       | 3.46%   |
| Unknown            | 261       | 2.46%   |
| Dell Vostro        | 211       | 1.99%   |
| ASUS PRIME         | 205       | 1.93%   |
| Lenovo ThinkPad    | 183       | 1.72%   |
| HP Pavilion        | 180       | 1.7%    |
| Dell Latitude      | 154       | 1.45%   |
| Dell OptiPlex      | 139       | 1.31%   |
| ASUS All           | 131       | 1.23%   |
| Positivo Mobile    | 114       | 1.07%   |
| ASUS M5A78L-M      | 109       | 1.03%   |
| Itautec Infoway    | 97        | 0.91%   |
| HP Compaq          | 89        | 0.84%   |
| ASUS TUF           | 87        | 0.82%   |
| ASUS VivoBook      | 79        | 0.74%   |
| ASUS P8H61-M       | 75        | 0.71%   |
| Samsung 340XAA     | 65        | 0.61%   |
| Intel H61          | 64        | 0.6%    |
| Lenovo ThinkCentre | 52        | 0.49%   |
| Semp Toshiba STI   | 49        | 0.46%   |
| Dell G3            | 49        | 0.46%   |
| ASRock A320M-HD    | 48        | 0.45%   |
| Dell XPS           | 47        | 0.44%   |
| ASUS ROG           | 47        | 0.44%   |
| HP ProBook         | 44        | 0.41%   |
| Samsung RV411      | 42        | 0.4%    |
| Intel H55          | 41        | 0.39%   |
| HP G42             | 39        | 0.37%   |
| Samsung 300E5M     | 37        | 0.35%   |
| Positivo S14CT01   | 37        | 0.35%   |
| Dell System        | 36        | 0.34%   |
| Gigabyte H61M-S1   | 34        | 0.32%   |
| HP EliteBook       | 33        | 0.31%   |
| Gigabyte B450M     | 31        | 0.29%   |
| Gigabyte A320M-S2H | 30        | 0.28%   |
| Gigabyte B75M-D3H  | 29        | 0.27%   |
| Acer Predator      | 29        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1137      | 10.72%  |
| 2012    | 1107      | 10.43%  |
| 2011    | 1029      | 9.7%    |
| 2018    | 1013      | 9.55%   |
| 2017    | 853       | 8.04%   |
| 2013    | 841       | 7.93%   |
| 2010    | 713       | 6.72%   |
| 2016    | 670       | 6.32%   |
| 2014    | 647       | 6.1%    |
| 2020    | 520       | 4.9%    |
| 2009    | 469       | 4.42%   |
| 2008    | 454       | 4.28%   |
| 2015    | 413       | 3.89%   |
| 2021    | 274       | 2.58%   |
| 2007    | 270       | 2.55%   |
| 2006    | 94        | 0.89%   |
| Unknown | 43        | 0.41%   |
| 2022    | 26        | 0.25%   |
| 2005    | 26        | 0.25%   |
| 2004    | 9         | 0.08%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6346      | 59.82%  |
| Desktop        | 3996      | 37.67%  |
| All in one     | 83        | 0.78%   |
| Convertible    | 70        | 0.66%   |
| Mini pc        | 38        | 0.36%   |
| Server         | 32        | 0.3%    |
| System on chip | 24        | 0.23%   |
| Tablet         | 19        | 0.18%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 9566      | 89.62%  |
| Enabled  | 1108      | 10.38%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10593     | 99.85%  |
| Yes  | 16        | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 2909      | 26.97%  |
| 4.01-8.0        | 2895      | 26.84%  |
| 8.01-16.0       | 1879      | 17.42%  |
| 16.01-24.0      | 1581      | 14.66%  |
| 1.01-2.0        | 757       | 7.02%   |
| 32.01-64.0      | 301       | 2.79%   |
| 2.01-3.0        | 244       | 2.26%   |
| 24.01-32.0      | 83        | 0.77%   |
| 64.01-256.0     | 70        | 0.65%   |
| 0.51-1.0        | 58        | 0.54%   |
| More than 256.0 | 6         | 0.06%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 4440      | 37.96%  |
| 2.01-3.0    | 3147      | 26.91%  |
| 3.01-4.0    | 1455      | 12.44%  |
| 4.01-8.0    | 1322      | 11.3%   |
| 0.51-1.0    | 926       | 7.92%   |
| 8.01-16.0   | 255       | 2.18%   |
| 0.01-0.5    | 112       | 0.96%   |
| 16.01-24.0  | 23        | 0.2%    |
| 24.01-32.0  | 5         | 0.04%   |
| Unknown     | 5         | 0.04%   |
| 32.01-64.0  | 3         | 0.03%   |
| 64.01-256.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6795      | 62.49%  |
| 2       | 2967      | 27.29%  |
| 3       | 632       | 5.81%   |
| 4       | 236       | 2.17%   |
| 0       | 101       | 0.93%   |
| 5       | 73        | 0.67%   |
| 6       | 44        | 0.4%    |
| 7       | 10        | 0.09%   |
| 8       | 6         | 0.06%   |
| 9       | 5         | 0.05%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6482      | 60.68%  |
| Yes       | 4201      | 39.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9803      | 92.26%  |
| No        | 822       | 7.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7767      | 72.72%  |
| No        | 2914      | 27.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5396      | 50.4%   |
| Yes       | 5311      | 49.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 10609     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Sao Paulo            | 1402      | 12.64%  |
| Rio de Janeiro       | 632       | 5.7%    |
| Brasília            | 347       | 3.13%   |
| Belo Horizonte       | 309       | 2.79%   |
| Curitiba             | 301       | 2.71%   |
| Porto Alegre         | 240       | 2.16%   |
| Fortaleza            | 233       | 2.1%    |
| Salvador             | 166       | 1.5%    |
| Campinas             | 158       | 1.42%   |
| Recife               | 148       | 1.33%   |
| Goiânia             | 129       | 1.16%   |
| Santo André         | 118       | 1.06%   |
| Florianópolis       | 116       | 1.05%   |
| Natal                | 95        | 0.86%   |
| Manaus               | 89        | 0.8%    |
| Osasco               | 85        | 0.77%   |
| Campo Grande         | 85        | 0.77%   |
| Niterói             | 83        | 0.75%   |
| Guarulhos            | 82        | 0.74%   |
| Sao José dos Campos | 81        | 0.73%   |
| Sao Luís            | 73        | 0.66%   |
| Belém               | 72        | 0.65%   |
| Maringá             | 71        | 0.64%   |
| Sorocaba             | 69        | 0.62%   |
| Joinville            | 69        | 0.62%   |
| Teresina             | 66        | 0.6%    |
| Londrina             | 62        | 0.56%   |
| Joao Pessoa          | 60        | 0.54%   |
| Ribeirao Preto       | 58        | 0.52%   |
| Uberlândia          | 57        | 0.51%   |
| Juiz de Fora         | 57        | 0.51%   |
| Aracaju              | 57        | 0.51%   |
| Maceió              | 54        | 0.49%   |
| Sao Jose             | 52        | 0.47%   |
| Serra                | 51        | 0.46%   |
| Vitória             | 49        | 0.44%   |
| Cuiabá              | 48        | 0.43%   |
| Duque de Caxias      | 47        | 0.42%   |
| Sao Carlos           | 46        | 0.41%   |
| Canoas               | 45        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3057      | 3896   | 21%     |
| Seagate                        | 2919      | 4080   | 20.06%  |
| Samsung Electronics            | 1483      | 2030   | 10.19%  |
| Kingston                       | 1464      | 1876   | 10.06%  |
| Toshiba                        | 875       | 1024   | 6.01%   |
| SanDisk                        | 748       | 999    | 5.14%   |
| Unknown                        | 441       | 602    | 3.03%   |
| A-DATA Technology              | 385       | 480    | 2.65%   |
| Hitachi                        | 355       | 435    | 2.44%   |
| Intel                          | 291       | 351    | 2%      |
| China                          | 273       | 319    | 1.88%   |
| Crucial                        | 255       | 330    | 1.75%   |
| Silicon Motion                 | 141       | 178    | 0.97%   |
| ADATA Technology               | 127       | 153    | 0.87%   |
| HGST                           | 124       | 147    | 0.85%   |
| LITEON                         | 116       | 135    | 0.8%    |
| Maxtor                         | 115       | 134    | 0.79%   |
| SK hynix                       | 112       | 150    | 0.77%   |
| KingSpec                       | 82        | 94     | 0.56%   |
| Lexar                          | 79        | 93     | 0.54%   |
| Phison                         | 62        | 83     | 0.43%   |
| Corsair                        | 58        | 69     | 0.4%    |
| Realtek Semiconductor          | 56        | 69     | 0.38%   |
| JMicron Technology             | 55        | 64     | 0.38%   |
| XPG                            | 54        | 67     | 0.37%   |
| Fujitsu                        | 52        | 60     | 0.36%   |
| PNY                            | 38        | 45     | 0.26%   |
| Hewlett-Packard                | 38        | 46     | 0.26%   |
| Netac                          | 37        | 47     | 0.25%   |
| Apple                          | 36        | 52     | 0.25%   |
| Patriot                        | 32        | 43     | 0.22%   |
| Solid State Storage Technology | 30        | 39     | 0.21%   |
| Gigabyte Technology            | 30        | 42     | 0.21%   |
| SSSTC                          | 28        | 29     | 0.19%   |
| Unknown                        | 27        | 27     | 0.19%   |
| Smart                          | 26        | 30     | 0.18%   |
| KingDian                       | 26        | 33     | 0.18%   |
| KIOXIA                         | 22        | 26     | 0.15%   |
| XrayDisk                       | 21        | 26     | 0.14%   |
| Micron/Crucial Technology      | 17        | 22     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 499       | 3.21%   |
| WDC WD10SPZX-21Z10T0 1TB            | 459       | 2.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 290       | 1.87%   |
| Kingston SA400S37120G 120GB SSD     | 271       | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 265       | 1.71%   |
| Kingston SA400S37480G 480GB SSD     | 239       | 1.54%   |
| Seagate ST500DM002-1BD142 500GB     | 228       | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB      | 184       | 1.19%   |
| Toshiba MQ01ABD100 1TB              | 140       | 0.9%    |
| Kingston SV300S37A120G 120GB SSD    | 131       | 0.84%   |
| Unknown MMC Card  32GB              | 128       | 0.82%   |
| SanDisk SSD PLUS 240GB              | 128       | 0.82%   |
| WDC WD10SPZX-24Z10 1TB              | 124       | 0.8%    |
| Samsung HD322HJ 320GB               | 111       | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB      | 106       | 0.68%   |
| Seagate Expansion 2TB               | 106       | 0.68%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB            | 98        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 96        | 0.62%   |
| Samsung HM321HI 320GB               | 94        | 0.61%   |
| Samsung HD161HJ 160GB               | 94        | 0.61%   |
| SanDisk SSD PLUS 120GB              | 92        | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB      | 90        | 0.58%   |
| Samsung HD502HJ 500GB               | 90        | 0.58%   |
| Samsung HD502HI 500GB               | 89        | 0.57%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 87        | 0.56%   |
| Seagate ST9500325AS 500GB           | 84        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB      | 84        | 0.54%   |
| Crucial CT240BX500SSD1 240GB        | 82        | 0.53%   |
| WDC WD10SPZX-75Z10T2 1TB            | 78        | 0.5%    |
| SanDisk SDSSDA240G 240GB            | 75        | 0.48%   |
| WDC WD5000AAKX-003CA0 500GB         | 73        | 0.47%   |
| Toshiba MQ01ABF050 500GB            | 73        | 0.47%   |
| Intel SSDPEKKW256G7 256GB           | 71        | 0.46%   |
| Toshiba MQ04ABF100 1TB              | 69        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB        | 69        | 0.44%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 68        | 0.44%   |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.44%   |
| Seagate ST3500418AS 500GB           | 66        | 0.43%   |
| WDC WD10EARS-00Y5B1 1TB             | 64        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2907      | 4051   | 35.29%  |
| WDC                 | 2745      | 3412   | 33.32%  |
| Samsung Electronics | 1031      | 1341   | 12.52%  |
| Toshiba             | 831       | 971    | 10.09%  |
| Hitachi             | 355       | 435    | 4.31%   |
| HGST                | 124       | 147    | 1.51%   |
| Maxtor              | 106       | 124    | 1.29%   |
| Fujitsu             | 51        | 58     | 0.62%   |
| Unknown             | 28        | 30     | 0.34%   |
| Apple               | 16        | 27     | 0.19%   |
| Hewlett-Packard     | 13        | 15     | 0.16%   |
| ExcelStor           | 9         | 10     | 0.11%   |
| JMicron Technology  | 5         | 6      | 0.06%   |
| SAGE                | 4         | 6      | 0.05%   |
| USB3.0              | 1         | 1      | 0.01%   |
| SABRENT             | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| Initio              | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1421      | 1805   | 33.26%  |
| SanDisk             | 573       | 797    | 13.41%  |
| WDC                 | 323       | 397    | 7.56%   |
| Samsung Electronics | 313       | 471    | 7.33%   |
| China               | 272       | 318    | 6.37%   |
| A-DATA Technology   | 247       | 297    | 5.78%   |
| Crucial             | 243       | 314    | 5.69%   |
| LITEON              | 102       | 120    | 2.39%   |
| KingSpec            | 81        | 93     | 1.9%    |
| Lexar               | 78        | 92     | 1.83%   |
| Intel               | 48        | 60     | 1.12%   |
| Corsair             | 46        | 54     | 1.08%   |
| PNY                 | 36        | 43     | 0.84%   |
| Netac               | 32        | 41     | 0.75%   |
| Patriot             | 30        | 40     | 0.7%    |
| Smart               | 26        | 30     | 0.61%   |
| KingDian            | 25        | 32     | 0.59%   |
| Gigabyte Technology | 25        | 36     | 0.59%   |
| Unknown             | 22        | 24     | 0.51%   |
| Apple               | 20        | 23     | 0.47%   |
| SK hynix            | 19        | 23     | 0.44%   |
| Hewlett-Packard     | 18        | 22     | 0.42%   |
| Unknown             | 17        | 17     | 0.4%    |
| Toshiba             | 15        | 18     | 0.35%   |
| Seagate             | 14        | 17     | 0.33%   |
| OCZ                 | 14        | 14     | 0.33%   |
| LITEONIT            | 12        | 18     | 0.28%   |
| BHT                 | 12        | 16     | 0.28%   |
| Micron Technology   | 10        | 12     | 0.23%   |
| Maxtor              | 9         | 10     | 0.21%   |
| XrayDisk            | 7         | 8      | 0.16%   |
| Team                | 7         | 14     | 0.16%   |
| RZX                 | 7         | 10     | 0.16%   |
| Plextor             | 7         | 8      | 0.16%   |
| S3+                 | 6         | 6      | 0.14%   |
| BIWIN               | 6         | 6      | 0.14%   |
| Win Memory          | 5         | 6      | 0.12%   |
| Pichau              | 5         | 5      | 0.12%   |
| KINGBANK            | 5         | 8      | 0.12%   |
| HUSKY               | 5         | 5      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7329      | 10650  | 55.24%  |
| SSD     | 3893      | 5460   | 29.34%  |
| NVMe    | 1595      | 2121   | 12.02%  |
| MMC     | 334       | 481    | 2.52%   |
| Unknown | 117       | 151    | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9452      | 15886  | 81.09%  |
| NVMe | 1554      | 2066   | 13.33%  |
| MMC  | 334       | 481    | 2.87%   |
| SAS  | 316       | 430    | 2.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7129      | 10575  | 63.37%  |
| 0.51-1.0   | 3432      | 4493   | 30.51%  |
| 1.01-2.0   | 507       | 729    | 4.51%   |
| 3.01-4.0   | 70        | 146    | 0.62%   |
| 2.01-3.0   | 62        | 92     | 0.55%   |
| 4.01-10.0  | 46        | 69     | 0.41%   |
| 10.01-20.0 | 4         | 6      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3122      | 27.91%  |
| 251-500        | 2723      | 24.34%  |
| 501-1000       | 1875      | 16.76%  |
| 1-20           | 810       | 7.24%   |
| 1001-2000      | 783       | 7%      |
| 51-100         | 742       | 6.63%   |
| 21-50          | 528       | 4.72%   |
| 2001-3000      | 224       | 2%      |
| Unknown        | 196       | 1.75%   |
| More than 3000 | 184       | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4465      | 38.62%  |
| 21-50          | 2465      | 21.32%  |
| 101-250        | 1428      | 12.35%  |
| 51-100         | 1396      | 12.08%  |
| 251-500        | 759       | 6.57%   |
| 501-1000       | 517       | 4.47%   |
| 1001-2000      | 227       | 1.96%   |
| Unknown        | 196       | 1.7%    |
| 2001-3000      | 59        | 0.51%   |
| More than 3000 | 48        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 40        | 43     | 3.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 38     | 3.21%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 26        | 28     | 2.39%   |
| WDC WD5000AAKX-003CA0 500GB         | 24        | 24     | 2.2%    |
| Seagate ST9500325AS 500GB           | 22        | 24     | 2.02%   |
| Samsung Electronics HD322HJ 320GB   | 19        | 21     | 1.74%   |
| Samsung Electronics HD161HJ 160GB   | 17        | 18     | 1.56%   |
| Samsung Electronics HD502HI 500GB   | 16        | 18     | 1.47%   |
| Samsung Electronics HD502HJ 500GB   | 13        | 13     | 1.19%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 12     | 1.1%    |
| WDC WD10EARS-00Y5B1 1TB             | 11        | 13     | 1.01%   |
| Toshiba MQ01ABD050 500GB            | 11        | 11     | 1.01%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 12     | 1.01%   |
| Seagate ST9320325AS 320GB           | 10        | 10     | 0.92%   |
| Seagate ST3500418AS 500GB           | 10        | 14     | 0.92%   |
| WDC WD3200AAJS-00L7A0 320GB         | 9         | 9      | 0.83%   |
| Samsung Electronics HD080HJ 80GB    | 9         | 11     | 0.83%   |
| Maxtor STM3160215AS 160GB           | 9         | 10     | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB      | 8         | 11     | 0.73%   |
| Samsung Electronics HM321HI 320GB   | 8         | 8      | 0.73%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 10     | 0.73%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 8      | 0.73%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 12     | 0.73%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 7         | 8      | 0.64%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.64%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 9      | 0.64%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 8      | 0.64%   |
| Seagate ST3320418AS 320GB           | 7         | 11     | 0.64%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7         | 7      | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 9      | 0.64%   |
| Samsung Electronics HD250HJ 250GB   | 7         | 8      | 0.64%   |
| Kingston SA400S37480G 480GB SSD     | 7         | 8      | 0.64%   |
| Toshiba MQ01ABF050 500GB            | 6         | 6      | 0.55%   |
| Toshiba MQ01ABD032 320GB            | 6         | 7      | 0.55%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 6         | 7      | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 7      | 0.55%   |
| Seagate ST1000DM003-9YN162 1TB      | 6         | 6      | 0.55%   |
| Samsung Electronics HM160HI 160GB   | 6         | 6      | 0.55%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 6      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 347       | 413    | 33.33%  |
| WDC                 | 234       | 262    | 22.48%  |
| Samsung Electronics | 158       | 195    | 15.18%  |
| Toshiba             | 94        | 102    | 9.03%   |
| Hitachi             | 55        | 58     | 5.28%   |
| Kingston            | 42        | 50     | 4.03%   |
| Maxtor              | 18        | 19     | 1.73%   |
| SanDisk             | 17        | 17     | 1.63%   |
| China               | 13        | 14     | 1.25%   |
| A-DATA Technology   | 8         | 8      | 0.77%   |
| HGST                | 7         | 7      | 0.67%   |
| Intel               | 6         | 6      | 0.58%   |
| Fujitsu             | 5         | 6      | 0.48%   |
| XPG                 | 4         | 4      | 0.38%   |
| PNY                 | 4         | 5      | 0.38%   |
| Crucial             | 4         | 4      | 0.38%   |
| OCZ                 | 3         | 3      | 0.29%   |
| Apple               | 3         | 3      | 0.29%   |
| LITEON              | 2         | 2      | 0.19%   |
| Corsair             | 2         | 2      | 0.19%   |
| walram              | 1         | 1      | 0.1%    |
| SK hynix            | 1         | 1      | 0.1%    |
| ShiJi               | 1         | 1      | 0.1%    |
| QIANGHE             | 1         | 1      | 0.1%    |
| Plextor             | 1         | 1      | 0.1%    |
| OCZ-VERTEX3         | 1         | 1      | 0.1%    |
| Netac               | 1         | 1      | 0.1%    |
| Mushkin             | 1         | 1      | 0.1%    |
| Micron Technology   | 1         | 1      | 0.1%    |
| LITEONIT            | 1         | 2      | 0.1%    |
| Initio              | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 1      | 0.1%    |
| FEASSO              | 1         | 2      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 347       | 413    | 38.26%  |
| WDC                 | 222       | 250    | 24.48%  |
| Samsung Electronics | 154       | 191    | 16.98%  |
| Toshiba             | 93        | 101    | 10.25%  |
| Hitachi             | 55        | 58     | 6.06%   |
| Maxtor              | 18        | 19     | 1.98%   |
| HGST                | 7         | 7      | 0.77%   |
| Fujitsu             | 5         | 6      | 0.55%   |
| Apple               | 2         | 2      | 0.22%   |
| Initio              | 1         | 1      | 0.11%   |
| Hewlett-Packard     | 1         | 1      | 0.11%   |
| FEASSO              | 1         | 2      | 0.11%   |
| ExcelStor           | 1         | 2      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 833       | 1053   | 86.23%  |
| SSD  | 119       | 131    | 12.32%  |
| NVMe | 14        | 14     | 1.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 8.33%   |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 8.33%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 4.17%   |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 4.17%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 4.17%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 4.17%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 4.17%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 4.17%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 4.17%   |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 4.17%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 4.17%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 4.17%   |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 4.17%   |
| Samsung Electronics HD502HJ 500GB                | 1         | 3      | 4.17%   |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 4.17%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 4.17%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 4.17%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 4.17%   |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 11     | 37.5%   |
| Seagate             | 7         | 7      | 29.17%  |
| WDC                 | 3         | 3      | 12.5%   |
| Toshiba             | 3         | 3      | 12.5%   |
| Maxtor              | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 7665      | 13450  | 68.13%  |
| Works    | 2624      | 4189   | 23.32%  |
| Malfunc  | 938       | 1198   | 8.34%   |
| Failed   | 24        | 26     | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8144      | 68.46%  |
| AMD                              | 1680      | 14.12%  |
| ADATA Technology                 | 294       | 2.47%   |
| Nvidia                           | 242       | 2.03%   |
| SanDisk                          | 217       | 1.82%   |
| Samsung Electronics              | 186       | 1.56%   |
| Silicon Motion                   | 160       | 1.34%   |
| Silicon Integrated Systems [SiS] | 100       | 0.84%   |
| Realtek Semiconductor            | 88        | 0.74%   |
| SK hynix                         | 87        | 0.73%   |
| Phison Electronics               | 86        | 0.72%   |
| Solid State Storage Technology   | 83        | 0.7%    |
| Marvell Technology Group         | 78        | 0.66%   |
| JMicron Technology               | 76        | 0.64%   |
| VIA Technologies                 | 70        | 0.59%   |
| ASMedia Technology               | 61        | 0.51%   |
| Kingston Technology Company      | 54        | 0.45%   |
| Micron/Crucial Technology        | 29        | 0.24%   |
| Lite-On Technology               | 26        | 0.22%   |
| Toshiba America Info Systems     | 23        | 0.19%   |
| KIOXIA                           | 22        | 0.18%   |
| LSI Logic / Symbios Logic        | 18        | 0.15%   |
| Broadcom / LSI                   | 12        | 0.1%    |
| Micron Technology                | 7         | 0.06%   |
| Union Memory (Shenzhen)          | 6         | 0.05%   |
| Silicon Image                    | 6         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.05%   |
| Seagate Technology               | 5         | 0.04%   |
| Shenzhen Longsys Electronics     | 4         | 0.03%   |
| OCZ Technology Group             | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| Hewlett-Packard                  | 3         | 0.03%   |
| Beijing Starblaze Technology     | 3         | 0.03%   |
| Lenovo                           | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| Apple                            | 2         | 0.02%   |
| Unknown                          | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |
| Netac Technology                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1010      | 6.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 913       | 6.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 778       | 5.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 591       | 4.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 552       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 434       | 2.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 432       | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 369       | 2.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 356       | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 342       | 2.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 297       | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 292       | 2%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 286       | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 276       | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 231       | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 224       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 222       | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 222       | 1.52%   |
| ADATA Non-Volatile memory controller                                                    | 222       | 1.52%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 200       | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 198       | 1.35%   |
| AMD FCH SATA Controller D                                                               | 198       | 1.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 192       | 1.31%   |
| Nvidia MCP61 SATA Controller                                                            | 170       | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 151       | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 147       | 1%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 144       | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 144       | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 139       | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 137       | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 135       | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 131       | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 130       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 126       | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 123       | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 118       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 117       | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 116       | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 114       | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 107       | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8111      | 64.79%  |
| IDE  | 2196      | 17.54%  |
| NVMe | 1566      | 12.51%  |
| RAID | 626       | 5%      |
| SCSI | 12        | 0.1%    |
| SAS  | 7         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 8660      | 81.63%  |
| AMD          | 1917      | 18.07%  |
| ARM          | 26        | 0.25%   |
| CentaurHauls | 5         | 0.05%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 230       | 2.16%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 158       | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 135       | 1.27%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 135       | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 127       | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 120       | 1.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 120       | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 113       | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 111       | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 109       | 1.02%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 104       | 0.98%   |
| AMD FX-6300 Six-Core Processor                | 88        | 0.83%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 86        | 0.81%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 84        | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 83        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 82        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 81        | 0.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 81        | 0.76%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 78        | 0.73%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 78        | 0.73%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 74        | 0.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 74        | 0.7%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 73        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 72        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 71        | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 70        | 0.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 70        | 0.66%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 68        | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 66        | 0.62%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 66        | 0.62%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 61        | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 60        | 0.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 60        | 0.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 59        | 0.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 59        | 0.55%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 59        | 0.55%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 58        | 0.55%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 58        | 0.55%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 56        | 0.53%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 55        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2629      | 24.73%  |
| Intel Core i7           | 1726      | 16.24%  |
| Intel Core i3           | 1476      | 13.89%  |
| Intel Celeron           | 728       | 6.85%   |
| Intel Core 2 Duo        | 477       | 4.49%   |
| AMD Ryzen 5             | 442       | 4.16%   |
| Intel Pentium Dual-Core | 301       | 2.83%   |
| Intel Atom              | 273       | 2.57%   |
| AMD Ryzen 7             | 265       | 2.49%   |
| Intel Pentium           | 247       | 2.32%   |
| AMD FX                  | 242       | 2.28%   |
| Other                   | 198       | 1.86%   |
| Intel Xeon              | 195       | 1.83%   |
| Intel Pentium Dual      | 140       | 1.32%   |
| AMD Ryzen 3             | 97        | 0.91%   |
| Intel Core 2 Quad       | 93        | 0.87%   |
| AMD Phenom II X4        | 70        | 0.66%   |
| AMD Athlon II X2        | 64        | 0.6%    |
| AMD A4                  | 58        | 0.55%   |
| AMD A10                 | 55        | 0.52%   |
| AMD E                   | 53        | 0.5%    |
| Intel Core 2            | 51        | 0.48%   |
| AMD Athlon 64 X2        | 45        | 0.42%   |
| AMD A8                  | 43        | 0.4%    |
| AMD A6                  | 43        | 0.4%    |
| Intel Genuine           | 41        | 0.39%   |
| AMD C-60                | 41        | 0.39%   |
| AMD Athlon              | 38        | 0.36%   |
| AMD E1                  | 33        | 0.31%   |
| AMD Ryzen 9             | 32        | 0.3%    |
| AMD Sempron             | 31        | 0.29%   |
| Intel Pentium 4         | 29        | 0.27%   |
| AMD Phenom II X6        | 26        | 0.24%   |
| AMD C-70                | 24        | 0.23%   |
| Intel Pentium Gold      | 21        | 0.2%    |
| Intel Core i9           | 19        | 0.18%   |
| AMD Athlon II X4        | 18        | 0.17%   |
| AMD Phenom II X2        | 17        | 0.16%   |
| AMD C-50                | 16        | 0.15%   |
| Intel Celeron Dual-Core | 15        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5779      | 54.37%  |
| 4       | 3335      | 31.37%  |
| 6       | 667       | 6.27%   |
| 1       | 315       | 2.96%   |
| 8       | 306       | 2.88%   |
| 3       | 129       | 1.21%   |
| 12      | 37        | 0.35%   |
| 16      | 17        | 0.16%   |
| Unknown | 15        | 0.14%   |
| 10      | 14        | 0.13%   |
| 20      | 6         | 0.06%   |
| 14      | 5         | 0.05%   |
| 24      | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10571     | 99.63%  |
| 2       | 36        | 0.34%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6808      | 64.11%  |
| 1       | 3795      | 35.74%  |
| Unknown | 15        | 0.14%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10023     | 93.9%   |
| Unknown        | 542       | 5.08%   |
| 32-bit         | 61        | 0.57%   |
| 64-bit         | 48        | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1964      | 17.92%  |
| 0x306a9    | 927       | 8.46%   |
| 0x206a7    | 905       | 8.26%   |
| 0x1067a    | 598       | 5.46%   |
| 0x906ea    | 388       | 3.54%   |
| 0x806e9    | 374       | 3.41%   |
| 0x306c3    | 341       | 3.11%   |
| 0x20655    | 341       | 3.11%   |
| 0x40651    | 321       | 2.93%   |
| 0x806ec    | 306       | 2.79%   |
| 0x406e3    | 263       | 2.4%    |
| 0x306d4    | 261       | 2.38%   |
| 0x806ea    | 244       | 2.23%   |
| 0x6fd      | 234       | 2.13%   |
| 0x906e9    | 203       | 1.85%   |
| 0x406c4    | 158       | 1.44%   |
| 0x06000852 | 147       | 1.34%   |
| 0x08108109 | 127       | 1.16%   |
| 0x30678    | 123       | 1.12%   |
| 0x010000c8 | 123       | 1.12%   |
| 0x806c1    | 122       | 1.11%   |
| 0x05000119 | 93        | 0.85%   |
| 0x20652    | 89        | 0.81%   |
| 0x906ed    | 84        | 0.77%   |
| 0x08600103 | 77        | 0.7%    |
| 0x10676    | 74        | 0.68%   |
| 0x0800820d | 74        | 0.68%   |
| 0x08108102 | 73        | 0.67%   |
| 0x706a1    | 71        | 0.65%   |
| 0x506e3    | 68        | 0.62%   |
| 0x08701021 | 67        | 0.61%   |
| 0x6fb      | 65        | 0.59%   |
| 0x706e5    | 61        | 0.56%   |
| 0x106ca    | 59        | 0.54%   |
| 0x806eb    | 53        | 0.48%   |
| 0x08701013 | 50        | 0.46%   |
| 0x406c3    | 49        | 0.45%   |
| 0x10661    | 49        | 0.45%   |
| 0x706a8    | 47        | 0.43%   |
| 0x0810100b | 45        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1991      | 18.75%  |
| IvyBridge        | 1127      | 10.61%  |
| SandyBridge      | 1065      | 10.03%  |
| Haswell          | 824       | 7.76%   |
| Penryn           | 776       | 7.31%   |
| Westmere         | 509       | 4.79%   |
| Core             | 449       | 4.23%   |
| Silvermont       | 407       | 3.83%   |
| Skylake          | 395       | 3.72%   |
| Zen+             | 352       | 3.31%   |
| Broadwell        | 311       | 2.93%   |
| K10              | 278       | 2.62%   |
| Piledriver       | 260       | 2.45%   |
| Zen 2            | 237       | 2.23%   |
| Zen              | 205       | 1.93%   |
| Bobcat           | 158       | 1.49%   |
| TigerLake        | 153       | 1.44%   |
| Goldmont plus    | 132       | 1.24%   |
| CometLake        | 121       | 1.14%   |
| Bonnell          | 116       | 1.09%   |
| K8 Hammer        | 101       | 0.95%   |
| IceLake          | 86        | 0.81%   |
| Nehalem          | 67        | 0.63%   |
| Excavator        | 67        | 0.63%   |
| Unknown          | 66        | 0.62%   |
| Zen 3            | 65        | 0.61%   |
| NetBurst         | 49        | 0.46%   |
| Goldmont         | 46        | 0.43%   |
| K10 Llano        | 43        | 0.4%    |
| Bulldozer        | 39        | 0.37%   |
| Steamroller      | 38        | 0.36%   |
| Jaguar           | 37        | 0.35%   |
| P6               | 26        | 0.24%   |
| K8 & K10 hybrid  | 10        | 0.09%   |
| Puma             | 7         | 0.07%   |
| Alderlake Hybrid | 5         | 0.05%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7195      | 56.56%  |
| Nvidia                           | 3147      | 24.74%  |
| AMD                              | 2192      | 17.23%  |
| Silicon Integrated Systems [SiS] | 97        | 0.76%   |
| VIA Technologies                 | 54        | 0.42%   |
| Matrox Electronics Systems       | 22        | 0.17%   |
| ASPEED Technology                | 7         | 0.06%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 3         | 0.02%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 879       | 6.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 681       | 5.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 442       | 3.39%   |
| Intel HD Graphics 620                                                                    | 434       | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 373       | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 357       | 2.74%   |
| Intel HD Graphics 5500                                                                   | 283       | 2.17%   |
| Intel UHD Graphics 620                                                                   | 276       | 2.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 268       | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 268       | 2.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 253       | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 246       | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 237       | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 230       | 1.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 219       | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 165       | 1.27%   |
| Intel HD Graphics 630                                                                    | 163       | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 161       | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 156       | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 151       | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 149       | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 148       | 1.14%   |
| Nvidia GT218 [GeForce 210]                                                               | 136       | 1.04%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 135       | 1.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 132       | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 132       | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 125       | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 125       | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 97        | 0.74%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 94        | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 93        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 93        | 0.71%   |
| AMD Renoir                                                                               | 92        | 0.71%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 91        | 0.7%    |
| Nvidia TU117M                                                                            | 87        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 86        | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 85        | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 81        | 0.62%   |
| Nvidia GM108M [GeForce MX110]                                                            | 80        | 0.61%   |
| AMD RS780L [Radeon 3000]                                                                 | 74        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 5276      | 49.41%  |
| 1 x AMD                 | 1566      | 14.67%  |
| 1 x Nvidia              | 1504      | 14.09%  |
| Intel + Nvidia          | 1470      | 13.77%  |
| Intel + AMD             | 384       | 3.6%    |
| AMD + Nvidia            | 146       | 1.37%   |
| 2 x AMD                 | 99        | 0.93%   |
| 1 x SiS                 | 97        | 0.91%   |
| 1 x VIA                 | 53        | 0.5%    |
| Other                   | 29        | 0.27%   |
| 1 x Matrox              | 21        | 0.2%    |
| 2 x Nvidia              | 13        | 0.12%   |
| 1 x ASPEED              | 6         | 0.06%   |
| 2 x Intel               | 4         | 0.04%   |
| Intel + Silicon Motion  | 2         | 0.02%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 8469      | 78.91%  |
| Proprietary | 1840      | 17.14%  |
| Unknown     | 423       | 3.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6466      | 59.5%   |
| 1.01-2.0   | 1602      | 14.74%  |
| 0.01-0.5   | 953       | 8.77%   |
| 0.51-1.0   | 744       | 6.85%   |
| 3.01-4.0   | 701       | 6.45%   |
| 5.01-6.0   | 165       | 1.52%   |
| 7.01-8.0   | 159       | 1.46%   |
| 2.01-3.0   | 54        | 0.5%    |
| 8.01-16.0  | 19        | 0.17%   |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1676      | 14.64%  |
| Goldstar                | 1467      | 12.81%  |
| AU Optronics            | 1414      | 12.35%  |
| BOE                     | 1328      | 11.6%   |
| Chimei Innolux          | 1060      | 9.26%   |
| LG Display              | 1039      | 9.07%   |
| AOC                     | 759       | 6.63%   |
| Dell                    | 480       | 4.19%   |
| Philips                 | 301       | 2.63%   |
| Acer                    | 172       | 1.5%    |
| Chi Mei Optoelectronics | 141       | 1.23%   |
| LG Electronics          | 140       | 1.22%   |
| InfoVision              | 112       | 0.98%   |
| Hewlett-Packard         | 111       | 0.97%   |
| PANDA                   | 102       | 0.89%   |
| Lenovo                  | 97        | 0.85%   |
| Apple                   | 90        | 0.79%   |
| Sony                    | 79        | 0.69%   |
| BenQ                    | 62        | 0.54%   |
| Unknown                 | 55        | 0.48%   |
| HannStar                | 48        | 0.42%   |
| CPT                     | 46        | 0.4%    |
| RTK                     | 41        | 0.36%   |
| Positivo                | 38        | 0.33%   |
| LG Philips              | 33        | 0.29%   |
| Panasonic               | 30        | 0.26%   |
| InnoLux Display         | 28        | 0.24%   |
| Ancor Communications    | 24        | 0.21%   |
| ASUSTek Computer        | 22        | 0.19%   |
| Sharp                   | 21        | 0.18%   |
| SLD                     | 20        | 0.17%   |
| Toshiba                 | 18        | 0.16%   |
| GDH                     | 18        | 0.16%   |
| NCS                     | 16        | 0.14%   |
| MTD                     | 16        | 0.14%   |
| HB@                     | 15        | 0.13%   |
| AGO                     | 14        | 0.12%   |
| Envision                | 13        | 0.11%   |
| TXD                     | 12        | 0.1%    |
| STA                     | 12        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 157       | 1.33%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 111       | 0.94%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 105       | 0.89%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 100       | 0.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 96        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 95        | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 94        | 0.8%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 94        | 0.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 91        | 0.77%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 78        | 0.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 73        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 70        | 0.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 69        | 0.59%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 64        | 0.54%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 63        | 0.54%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 61        | 0.52%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 59        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 58        | 0.49%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 56        | 0.48%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 54        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 54        | 0.46%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 53        | 0.45%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 53        | 0.45%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 53        | 0.45%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 53        | 0.45%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 52        | 0.44%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 50        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 49        | 0.42%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 49        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 49        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 48        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 47        | 0.4%    |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 45        | 0.38%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.37%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 43        | 0.37%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 41        | 0.35%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 40        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 39        | 0.33%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 37        | 0.31%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 37        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4554      | 40.83%  |
| 1920x1080 (FHD)    | 3459      | 31.01%  |
| 1600x900 (HD+)     | 470       | 4.21%   |
| 1440x900 (WXGA+)   | 372       | 3.34%   |
| 2560x1080          | 347       | 3.11%   |
| 1360x768           | 311       | 2.79%   |
| 1280x1024 (SXGA)   | 306       | 2.74%   |
| 1280x800 (WXGA)    | 280       | 2.51%   |
| 3840x2160 (4K)     | 240       | 2.15%   |
| 1680x1050 (WSXGA+) | 171       | 1.53%   |
| 1024x768 (XGA)     | 114       | 1.02%   |
| Unknown            | 96        | 0.86%   |
| 2560x1440 (QHD)    | 84        | 0.75%   |
| 1920x1200 (WUXGA)  | 55        | 0.49%   |
| 1280x720 (HD)      | 46        | 0.41%   |
| 1024x600           | 40        | 0.36%   |
| 1920x540           | 30        | 0.27%   |
| 3840x1080          | 27        | 0.24%   |
| 2288x1287          | 20        | 0.18%   |
| 3440x1440          | 12        | 0.11%   |
| 1152x864           | 9         | 0.08%   |
| 2560x1600          | 8         | 0.07%   |
| 5760x1080          | 5         | 0.04%   |
| 4480x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 1600x1200          | 5         | 0.04%   |
| 1280x960           | 5         | 0.04%   |
| 3360x1080          | 4         | 0.04%   |
| 3200x1080          | 4         | 0.04%   |
| 2736x1824          | 4         | 0.04%   |
| 3840x2400          | 3         | 0.03%   |
| 3200x1800 (QHD+)   | 3         | 0.03%   |
| 2880x1800          | 3         | 0.03%   |
| 2732x768           | 3         | 0.03%   |
| 6400x1080          | 2         | 0.02%   |
| 3600x1080          | 2         | 0.02%   |
| 3520x1080          | 2         | 0.02%   |
| 3360x1050          | 2         | 0.02%   |
| 2800x900           | 2         | 0.02%   |
| 2720x1024          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3413      | 29.7%   |
| 14      | 1405      | 12.22%  |
| 13      | 1231      | 10.71%  |
| 18      | 757       | 6.59%   |
| 21      | 719       | 6.26%   |
| 23      | 654       | 5.69%   |
| Unknown | 475       | 4.13%   |
| 17      | 474       | 4.12%   |
| 24      | 321       | 2.79%   |
| 34      | 300       | 2.61%   |
| 20      | 277       | 2.41%   |
| 19      | 271       | 2.36%   |
| 27      | 256       | 2.23%   |
| 31      | 120       | 1.04%   |
| 22      | 107       | 0.93%   |
| 11      | 107       | 0.93%   |
| 12      | 69        | 0.6%    |
| 72      | 58        | 0.5%    |
| 40      | 54        | 0.47%   |
| 32      | 50        | 0.44%   |
| 10      | 46        | 0.4%    |
| 28      | 45        | 0.39%   |
| 54      | 40        | 0.35%   |
| 84      | 39        | 0.34%   |
| 16      | 34        | 0.3%    |
| 26      | 31        | 0.27%   |
| 52      | 30        | 0.26%   |
| 46      | 25        | 0.22%   |
| 47      | 15        | 0.13%   |
| 142     | 9         | 0.08%   |
| 48      | 9         | 0.08%   |
| 37      | 9         | 0.08%   |
| 65      | 5         | 0.04%   |
| 39      | 5         | 0.04%   |
| 25      | 5         | 0.04%   |
| 43      | 4         | 0.03%   |
| 41      | 4         | 0.03%   |
| 50      | 3         | 0.03%   |
| 60      | 2         | 0.02%   |
| 55      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 5966      | 52.68%  |
| 401-500        | 2018      | 17.82%  |
| 501-600        | 1175      | 10.38%  |
| Unknown        | 475       | 4.19%   |
| 201-300        | 417       | 3.68%   |
| 351-400        | 404       | 3.57%   |
| 701-800        | 350       | 3.09%   |
| 601-700        | 198       | 1.75%   |
| 1001-1500      | 133       | 1.17%   |
| 1501-2000      | 98        | 0.87%   |
| 801-900        | 69        | 0.61%   |
| 901-1000       | 10        | 0.09%   |
| More than 2000 | 9         | 0.08%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 8274      | 79.74%  |
| 16/10   | 835       | 8.05%   |
| Unknown | 405       | 3.9%    |
| 21/9    | 328       | 3.16%   |
| 5/4     | 305       | 2.94%   |
| 4/3     | 167       | 1.61%   |
| 3/2     | 49        | 0.47%   |
| 1.00    | 9         | 0.09%   |
| 32/9    | 2         | 0.02%   |
| 6/5     | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3372      | 29.49%  |
| 81-90          | 2484      | 21.73%  |
| 201-250        | 1513      | 13.23%  |
| 141-150        | 923       | 8.07%   |
| 151-200        | 809       | 7.08%   |
| 351-500        | 485       | 4.24%   |
| Unknown        | 475       | 4.15%   |
| 301-350        | 263       | 2.3%    |
| More than 1000 | 198       | 1.73%   |
| 71-80          | 153       | 1.34%   |
| 121-130        | 127       | 1.11%   |
| 501-1000       | 122       | 1.07%   |
| 251-300        | 121       | 1.06%   |
| 51-60          | 107       | 0.94%   |
| 131-140        | 107       | 0.94%   |
| 91-100         | 49        | 0.43%   |
| 41-50          | 46        | 0.4%    |
| 61-70          | 39        | 0.34%   |
| 111-120        | 38        | 0.33%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 4723      | 42.52%  |
| 51-100        | 3615      | 32.54%  |
| 121-160       | 1844      | 16.6%   |
| Unknown       | 476       | 4.29%   |
| 1-50          | 294       | 2.65%   |
| 161-240       | 134       | 1.21%   |
| More than 240 | 22        | 0.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8629      | 79.6%   |
| 2     | 1677      | 15.47%  |
| 0     | 442       | 4.08%   |
| 3     | 86        | 0.79%   |
| 4     | 6         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 7547      | 44.63%  |
| Qualcomm Atheros                  | 3410      | 20.17%  |
| Intel                             | 2784      | 16.46%  |
| Broadcom                          | 784       | 4.64%   |
| Ralink Technology                 | 386       | 2.28%   |
| Marvell Technology Group          | 219       | 1.3%    |
| Nvidia                            | 202       | 1.19%   |
| Ralink                            | 197       | 1.16%   |
| JMicron Technology                | 195       | 1.15%   |
| Broadcom Limited                  | 174       | 1.03%   |
| TP-Link                           | 161       | 0.95%   |
| Qualcomm Atheros Communications   | 118       | 0.7%    |
| Samsung Electronics               | 100       | 0.59%   |
| Silicon Integrated Systems [SiS]  | 98        | 0.58%   |
| VIA Technologies                  | 68        | 0.4%    |
| D-Link                            | 66        | 0.39%   |
| Motorola PCS                      | 44        | 0.26%   |
| Xiaomi                            | 40        | 0.24%   |
| Microsoft                         | 39        | 0.23%   |
| D-Link System                     | 35        | 0.21%   |
| ASIX Electronics                  | 29        | 0.17%   |
| MediaTek                          | 26        | 0.15%   |
| ICS Advent                        | 17        | 0.1%    |
| Motorola                          | 13        | 0.08%   |
| DisplayLink                       | 11        | 0.07%   |
| Edimax Technology                 | 7         | 0.04%   |
| ASUSTek Computer                  | 7         | 0.04%   |
| Microchip Technology              | 6         | 0.04%   |
| Mercucys                          | 6         | 0.04%   |
| LG Electronics                    | 6         | 0.04%   |
| Huawei Technologies               | 6         | 0.04%   |
| Dell                              | 6         | 0.04%   |
| Qualcomm                          | 5         | 0.03%   |
| 3Com                              | 5         | 0.03%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| Lenovo                            | 4         | 0.02%   |
| Attansic Technology               | 4         | 0.02%   |
| Arduino SA                        | 4         | 0.02%   |
| AMD                               | 4         | 0.02%   |
| Accton Technology                 | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4966      | 26.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1678      | 9.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 792       | 4.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 688       | 3.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 616       | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 341       | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 299       | 1.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 294       | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 290       | 1.57%   |
| Ralink MT7601U Wireless Adapter                                   | 215       | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 201       | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 163       | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 157       | 0.85%   |
| Intel Wireless 7265                                               | 154       | 0.83%   |
| Nvidia MCP61 Ethernet                                             | 150       | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 141       | 0.76%   |
| Intel Wi-Fi 6 AX201                                               | 139       | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 138       | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 131       | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 111       | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 109       | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 107       | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                   | 105       | 0.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 102       | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 100       | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 93        | 0.5%    |
| Intel Wireless 7260                                               | 93        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 92        | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 91        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 91        | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 90        | 0.49%   |
| Intel Wireless 3165                                               | 90        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 85        | 0.46%   |
| Intel Ethernet Connection (2) I219-V                              | 83        | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 80        | 0.43%   |
| Ralink RT5370 Wireless Adapter                                    | 80        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 74        | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 74        | 0.4%    |
| Intel I211 Gigabit Network Connection                             | 74        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 73        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2980      | 36.88%  |
| Intel                                 | 2122      | 26.26%  |
| Realtek Semiconductor                 | 1342      | 16.61%  |
| Broadcom                              | 490       | 6.06%   |
| Ralink Technology                     | 386       | 4.78%   |
| Ralink                                | 197       | 2.44%   |
| TP-Link                               | 148       | 1.83%   |
| Qualcomm Atheros Communications       | 118       | 1.46%   |
| Broadcom Limited                      | 99        | 1.23%   |
| D-Link                                | 66        | 0.82%   |
| Microsoft                             | 39        | 0.48%   |
| D-Link System                         | 24        | 0.3%    |
| MediaTek                              | 18        | 0.22%   |
| Marvell Technology Group              | 7         | 0.09%   |
| Edimax Technology                     | 7         | 0.09%   |
| Mercucys                              | 6         | 0.07%   |
| NetGear                               | 3         | 0.04%   |
| Micro Star International              | 3         | 0.04%   |
| Linksys                               | 3         | 0.04%   |
| Encore Electronics                    | 3         | 0.04%   |
| Dell                                  | 3         | 0.04%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 792       | 9.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 688       | 8.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 616       | 7.58%   |
| Intel Wi-Fi 6 AX200                                                     | 341       | 4.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 299       | 3.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 294       | 3.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 290       | 3.57%   |
| Ralink MT7601U Wireless Adapter                                         | 215       | 2.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 201       | 2.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 157       | 1.93%   |
| Intel Wireless 7265                                                     | 154       | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 139       | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 131       | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 111       | 1.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 109       | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                         | 105       | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 102       | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 100       | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 93        | 1.14%   |
| Intel Wireless 7260                                                     | 93        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 90        | 1.11%   |
| Intel Wireless 3165                                                     | 90        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 80        | 0.98%   |
| Ralink RT5370 Wireless Adapter                                          | 80        | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 74        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 73        | 0.9%    |
| Intel Wireless 3160                                                     | 71        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 67        | 0.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 62        | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 62        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 61        | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 57        | 0.7%    |
| Intel Wireless 8265 / 8275                                              | 56        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 55        | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 54        | 0.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 53        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 50        | 0.62%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 50        | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 48        | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 47        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 6967      | 68.62%  |
| Intel                             | 978       | 9.63%   |
| Qualcomm Atheros                  | 666       | 6.56%   |
| Broadcom                          | 365       | 3.59%   |
| Marvell Technology Group          | 212       | 2.09%   |
| Nvidia                            | 201       | 1.98%   |
| JMicron Technology                | 195       | 1.92%   |
| Samsung Electronics               | 99        | 0.98%   |
| Silicon Integrated Systems [SiS]  | 98        | 0.97%   |
| Broadcom Limited                  | 81        | 0.8%    |
| VIA Technologies                  | 67        | 0.66%   |
| Xiaomi                            | 40        | 0.39%   |
| Motorola PCS                      | 33        | 0.33%   |
| ASIX Electronics                  | 29        | 0.29%   |
| ICS Advent                        | 17        | 0.17%   |
| TP-Link                           | 13        | 0.13%   |
| DisplayLink                       | 11        | 0.11%   |
| D-Link System                     | 11        | 0.11%   |
| MediaTek                          | 7         | 0.07%   |
| Microchip Technology              | 5         | 0.05%   |
| ASUSTek Computer                  | 5         | 0.05%   |
| 3Com                              | 5         | 0.05%   |
| Sundance Technology Inc / IC Plus | 4         | 0.04%   |
| Qualcomm                          | 4         | 0.04%   |
| LG Electronics                    | 4         | 0.04%   |
| Lenovo                            | 4         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |
| OPPO Electronics                  | 3         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Huawei Technologies               | 2         | 0.02%   |
| Aquantia                          | 2         | 0.02%   |
| Apple                             | 2         | 0.02%   |
| Accton Technology                 | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |
| OnePlus                           | 1         | 0.01%   |
| NetXen Incorporated               | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4966      | 48.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1678      | 16.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 163       | 1.59%   |
| Nvidia MCP61 Ethernet                                             | 150       | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 141       | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 138       | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 107       | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 92        | 0.9%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 91        | 0.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 91        | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 85        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 83        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 74        | 0.72%   |
| Intel I211 Gigabit Network Connection                             | 74        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 73        | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 72        | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 71        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 66        | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 65        | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 64        | 0.62%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 57        | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 55        | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 51        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 50        | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 46        | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 43        | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 39        | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 39        | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 37        | 0.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 34        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 33        | 0.32%   |
| Motorola PCS moto g(6) plus                                       | 33        | 0.32%   |
| Intel 82578DC Gigabit Network Connection                          | 32        | 0.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 31        | 0.3%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 30        | 0.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 29        | 0.28%   |
| Intel Ethernet Connection (2) I218-V                              | 29        | 0.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 26        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 9795      | 55.53%  |
| WiFi     | 7766      | 44.03%  |
| Modem    | 53        | 0.3%    |
| Unknown  | 25        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6405      | 58.17%  |
| Ethernet | 4601      | 41.79%  |
| Unknown  | 4         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6227      | 58.48%  |
| 1     | 4017      | 37.73%  |
| 0     | 314       | 2.95%   |
| 3     | 68        | 0.64%   |
| 4     | 16        | 0.15%   |
| 10    | 3         | 0.03%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8741      | 80.5%   |
| Yes  | 2118      | 19.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1795      | 33.58%  |
| Qualcomm Atheros Communications | 1425      | 26.66%  |
| Lite-On Technology              | 605       | 11.32%  |
| Cambridge Silicon Radio         | 448       | 8.38%   |
| Broadcom                        | 215       | 4.02%   |
| Realtek Semiconductor           | 191       | 3.57%   |
| Foxconn / Hon Hai               | 111       | 2.08%   |
| Apple                           | 108       | 2.02%   |
| IMC Networks                    | 107       | 2%      |
| Dell                            | 71        | 1.33%   |
| Ralink                          | 47        | 0.88%   |
| Hewlett-Packard                 | 47        | 0.88%   |
| Unknown                         | 42        | 0.79%   |
| Qcom                            | 25        | 0.47%   |
| ASUSTek Computer                | 21        | 0.39%   |
| Ralink Technology               | 16        | 0.3%    |
| Alps Electric                   | 13        | 0.24%   |
| Foxconn International           | 12        | 0.22%   |
| Integrated System Solution      | 8         | 0.15%   |
| Askey Computer                  | 8         | 0.15%   |
| MediaTek                        | 7         | 0.13%   |
| Toshiba                         | 4         | 0.07%   |
| Micro Star International        | 4         | 0.07%   |
| Conwise Technology              | 3         | 0.06%   |
| Unknown                         | 3         | 0.06%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Marvell Semiconductor           | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 801       | 14.98%  |
| Intel Bluetooth wireless interface                                                  | 626       | 11.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 448       | 8.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 446       | 8.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 353       | 6.6%    |
| Intel AX200 Bluetooth                                                               | 332       | 6.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 223       | 4.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 142       | 2.66%   |
| Intel AX201 Bluetooth                                                               | 138       | 2.58%   |
| Realtek Bluetooth Radio                                                             | 133       | 2.49%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 130       | 2.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 111       | 2.08%   |
| Lite-On Bluetooth Device                                                            | 84        | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 82        | 1.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 81        | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 65        | 1.22%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 58        | 1.08%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 56        | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 54        | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 54        | 1.01%   |
| Ralink RT3290 Bluetooth                                                             | 47        | 0.88%   |
| Unknown Bluetooth Device                                                            | 42        | 0.79%   |
| IMC Networks Bluetooth Radio                                                        | 40        | 0.75%   |
| Apple Bluetooth Host Controller                                                     | 39        | 0.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 36        | 0.67%   |
| Apple Bluetooth USB Host Controller                                                 | 36        | 0.67%   |
| Dell Wireless 365 Bluetooth                                                         | 31        | 0.58%   |
| IMC Networks Bluetooth Device                                                       | 30        | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 29        | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 29        | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 25        | 0.47%   |
| Lite-On Atheros Bluetooth                                                           | 22        | 0.41%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 21        | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 20        | 0.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 17        | 0.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 16        | 0.3%    |
| Realtek RTL8723A Bluetooth                                                          | 15        | 0.28%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.28%   |
| Intel AX210 Bluetooth                                                               | 15        | 0.28%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 15        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 8239      | 60.87%  |
| AMD                                             | 2124      | 15.69%  |
| Nvidia                                          | 2095      | 15.48%  |
| C-Media Electronics                             | 223       | 1.65%   |
| Generalplus Technology                          | 107       | 0.79%   |
| Silicon Integrated Systems [SiS]                | 99        | 0.73%   |
| Logitech                                        | 75        | 0.55%   |
| VIA Technologies                                | 72        | 0.53%   |
| JMTek                                           | 59        | 0.44%   |
| Kingston Technology                             | 41        | 0.3%    |
| Creative Labs                                   | 36        | 0.27%   |
| Texas Instruments                               | 34        | 0.25%   |
| Corsair                                         | 27        | 0.2%    |
| Microsoft                                       | 21        | 0.16%   |
| Plantronics                                     | 18        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 15        | 0.11%   |
| Tenx Technology                                 | 14        | 0.1%    |
| Razer USA                                       | 14        | 0.1%    |
| GN Netcom                                       | 14        | 0.1%    |
| BEHRINGER International                         | 13        | 0.1%    |
| Sony                                            | 11        | 0.08%   |
| Realtek Semiconductor                           | 10        | 0.07%   |
| M-Audio                                         | 8         | 0.06%   |
| Focusrite-Novation                              | 8         | 0.06%   |
| Dell                                            | 8         | 0.06%   |
| SteelSeries ApS                                 | 7         | 0.05%   |
| Goldvish                                        | 7         | 0.05%   |
| BY EDIFIER                                      | 7         | 0.05%   |
| Philips (or NXP)                                | 6         | 0.04%   |
| JBL                                             | 6         | 0.04%   |
| Fry's Electronics                               | 6         | 0.04%   |
| Creative Technology                             | 6         | 0.04%   |
| Samsung Electronics                             | 5         | 0.04%   |
| Cirrus Logic                                    | 5         | 0.04%   |
| Turtle Beach                                    | 4         | 0.03%   |
| Tdlasunnic                                      | 4         | 0.03%   |
| Lenovo                                          | 4         | 0.03%   |
| Elite Silicon                                   | 4         | 0.03%   |
| Astro Gaming                                    | 4         | 0.03%   |
| UCQ01000                                        | 3         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1098      | 6.98%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1048      | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1043      | 6.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 649       | 4.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 538       | 3.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 508       | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 506       | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 489       | 3.11%   |
| Intel 8 Series HD Audio Controller                                                                | 373       | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 369       | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 365       | 2.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 331       | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 321       | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 301       | 1.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 300       | 1.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 299       | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 285       | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 271       | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 239       | 1.52%   |
| AMD FCH Azalia Controller                                                                         | 238       | 1.51%   |
| Nvidia High Definition Audio Controller                                                           | 218       | 1.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 195       | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 183       | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 176       | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 169       | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 167       | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                                | 164       | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 164       | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 158       | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 152       | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 152       | 0.97%   |
| AMD Wrestler HDMI Audio                                                                           | 142       | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 134       | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 132       | 0.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 126       | 0.8%    |
| Intel 200 Series PCH HD Audio                                                                     | 126       | 0.8%    |
| Generalplus Technology USB Audio Device                                                           | 107       | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 107       | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 101       | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 99        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 777       | 18.06%  |
| Kingston            | 704       | 16.36%  |
| Smart               | 590       | 13.71%  |
| Samsung Electronics | 398       | 9.25%   |
| SK hynix            | 288       | 6.69%   |
| A-DATA Technology   | 233       | 5.41%   |
| Corsair             | 213       | 4.95%   |
| Teikon              | 158       | 3.67%   |
| Crucial             | 147       | 3.42%   |
| Micron Technology   | 139       | 3.23%   |
| Smart Brazil        | 90        | 2.09%   |
| High Bridge         | 56        | 1.3%    |
| Elpida              | 44        | 1.02%   |
| Multilaser          | 40        | 0.93%   |
| Team                | 37        | 0.86%   |
| G.Skill             | 34        | 0.79%   |
| Unknown             | 34        | 0.79%   |
| Apacer              | 28        | 0.65%   |
| Unknown (ABCD)      | 25        | 0.58%   |
| Patriot             | 24        | 0.56%   |
| Nanya Technology    | 20        | 0.46%   |
| Kllisre             | 14        | 0.33%   |
| Ramaxel Technology  | 11        | 0.26%   |
| HT Micron           | 11        | 0.26%   |
| Avant               | 11        | 0.26%   |
| Atermiter           | 11        | 0.26%   |
| Smart Modular       | 9         | 0.21%   |
| Kreton              | 9         | 0.21%   |
| RZX                 | 8         | 0.19%   |
| HBS                 | 8         | 0.19%   |
| GeIL                | 7         | 0.16%   |
| CSX                 | 7         | 0.16%   |
| PUSKILL             | 6         | 0.14%   |
| Kingmax             | 6         | 0.14%   |
| Carry               | 6         | 0.14%   |
| Unknown (82B5)      | 5         | 0.12%   |
| Positivo            | 5         | 0.12%   |
| MemoWise            | 4         | 0.09%   |
| GLOWAY              | 4         | 0.09%   |
| Walton Chaintech    | 3         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 69        | 1.46%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 49        | 1.04%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 44        | 0.93%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 42        | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 41        | 0.87%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 38        | 0.8%    |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 36        | 0.76%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s         | 34        | 0.72%   |
| Unknown                                                          | 34        | 0.72%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 32        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.63%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 30        | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 30        | 0.63%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.61%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 29        | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 29        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 28        | 0.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 27        | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 25        | 0.53%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 24        | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 23        | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 0.49%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 20        | 0.42%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 19        | 0.4%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 19        | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.4%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s        | 18        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.38%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 17        | 0.36%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                      | 17        | 0.36%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 16        | 0.34%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 16        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 16        | 0.34%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s              | 16        | 0.34%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 15        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 15        | 0.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 15        | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 15        | 0.32%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 15        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1611      | 43.85%  |
| DDR4         | 1304      | 35.49%  |
| DDR2         | 254       | 6.91%   |
| Unknown      | 182       | 4.95%   |
| SDRAM        | 169       | 4.6%    |
| LPDDR4       | 62        | 1.69%   |
| DDR          | 43        | 1.17%   |
| LPDDR3       | 26        | 0.71%   |
| DRAM         | 18        | 0.49%   |
| DDR5         | 2         | 0.05%   |
| RAM          | 1         | 0.03%   |
| LPDDR5       | 1         | 0.03%   |
| DDR2 FB-DIMM | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1983      | 54.57%  |
| DIMM         | 1566      | 43.09%  |
| Row Of Chips | 68        | 1.87%   |
| Unknown      | 9         | 0.25%   |
| RIMM         | 3         | 0.08%   |
| FB-DIMM      | 3         | 0.08%   |
| Chip         | 2         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1577      | 38.06%  |
| 8192  | 1131      | 27.3%   |
| 2048  | 870       | 21%     |
| 16384 | 341       | 8.23%   |
| 1024  | 146       | 3.52%   |
| 32768 | 57        | 1.38%   |
| 512   | 17        | 0.41%   |
| 256   | 2         | 0.05%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 900       | 21.92%  |
| 1333    | 555       | 13.52%  |
| 2667    | 516       | 12.57%  |
| 2400    | 397       | 9.67%   |
| Unknown | 219       | 5.33%   |
| 1334    | 208       | 5.07%   |
| 3200    | 158       | 3.85%   |
| 800     | 144       | 3.51%   |
| 2133    | 134       | 3.26%   |
| 667     | 129       | 3.14%   |
| 1066    | 57        | 1.39%   |
| 1067    | 56        | 1.36%   |
| 3400    | 55        | 1.34%   |
| 3600    | 53        | 1.29%   |
| 3000    | 53        | 1.29%   |
| 1867    | 48        | 1.17%   |
| 4199    | 37        | 0.9%    |
| 1866    | 31        | 0.76%   |
| 3466    | 30        | 0.73%   |
| 533     | 30        | 0.73%   |
| 4267    | 26        | 0.63%   |
| 2800    | 23        | 0.56%   |
| 2933    | 22        | 0.54%   |
| 2666    | 20        | 0.49%   |
| 2048    | 20        | 0.49%   |
| 975     | 19        | 0.46%   |
| 3151    | 16        | 0.39%   |
| 400     | 16        | 0.39%   |
| 333     | 14        | 0.34%   |
| 3733    | 13        | 0.32%   |
| 3266    | 12        | 0.29%   |
| 3800    | 10        | 0.24%   |
| 3334    | 8         | 0.19%   |
| 8400    | 6         | 0.15%   |
| 3333    | 6         | 0.15%   |
| 1200    | 5         | 0.12%   |
| 41632   | 4         | 0.1%    |
| 3066    | 3         | 0.07%   |
| 2733    | 3         | 0.07%   |
| 2132    | 3         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 105       | 44.87%  |
| Seiko Epson           | 61        | 26.07%  |
| Samsung Electronics   | 21        | 8.97%   |
| Canon                 | 19        | 8.12%   |
| Brother Industries    | 16        | 6.84%   |
| QinHeng Electronics   | 2         | 0.85%   |
| Lexmark International | 2         | 0.85%   |
| Apple                 | 2         | 0.85%   |
| Xerox                 | 1         | 0.43%   |
| Ricoh                 | 1         | 0.43%   |
| Prolific Technology   | 1         | 0.43%   |
| Oki Data              | 1         | 0.43%   |
| MIIIW                 | 1         | 0.43%   |
| ARGOX                 | 1         | 0.43%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 12        | 5.11%   |
| Seiko Epson L395 Series                      | 10        | 4.26%   |
| HP Ink Tank Wireless 410 series              | 8         | 3.4%    |
| HP DeskJet 2130 series                       | 8         | 3.4%    |
| Seiko Epson L355 Series                      | 7         | 2.98%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.98%   |
| HP Deskjet 2540 series                       | 7         | 2.98%   |
| Seiko Epson L365 Series                      | 6         | 2.55%   |
| Canon G3010 series                           | 6         | 2.55%   |
| Samsung SCX-4200 series                      | 5         | 2.13%   |
| HP LaserJet Professional P1102w              | 5         | 2.13%   |
| HP LaserJet 1020                             | 5         | 2.13%   |
| HP DeskJet F4100 Printer series              | 5         | 2.13%   |
| HP DeskJet 2700 series                       | 5         | 2.13%   |
| Samsung M2070 Series                         | 4         | 1.7%    |
| HP LaserJet P1005                            | 4         | 1.7%    |
| HP DeskJet F4200 series                      | 4         | 1.7%    |
| HP DeskJet 3630 series                       | 4         | 1.7%    |
| HP DeskJet 2620 All-in-One Printer           | 4         | 1.7%    |
| HP Deskjet 2050 J510                         | 4         | 1.7%    |
| Seiko Epson L210 Series                      | 3         | 1.28%   |
| Samsung M2020 Series                         | 3         | 1.28%   |
| HP LaserJet 1018                             | 3         | 1.28%   |
| HP Deskjet F4400 series                      | 3         | 1.28%   |
| Brother HL-1200 series                       | 3         | 1.28%   |
| Seiko Epson XP-243 245 247 Series            | 2         | 0.85%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2         | 0.85%   |
| Seiko Epson L4150 Series                     | 2         | 0.85%   |
| Seiko Epson L375 Series                      | 2         | 0.85%   |
| Seiko Epson L3110 Series                     | 2         | 0.85%   |
| Seiko Epson L222 Series                      | 2         | 0.85%   |
| Seiko Epson ET-3750 Series                   | 2         | 0.85%   |
| Samsung SCX-3200 Series                      | 2         | 0.85%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.85%   |
| QinHeng CH340S                               | 2         | 0.85%   |
| HP Printing Support                          | 2         | 0.85%   |
| HP DeskJet D1360                             | 2         | 0.85%   |
| HP Deskjet 4620 series                       | 2         | 0.85%   |
| HP DeskJet 2300 series                       | 2         | 0.85%   |
| Canon PIXMA MG3000 series                    | 2         | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 8         | 42.11%  |
| Canon           | 8         | 42.11%  |
| Seiko Epson     | 2         | 10.53%  |
| Mustek Systems  | 1         | 5.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 26.32%  |
| Canon CanoScan LIDE 25                                  | 4         | 21.05%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.26%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 5.26%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 5.26%   |
| HP ScanJet G4050                                        | 1         | 5.26%   |
| HP ScanJet 3800c                                        | 1         | 5.26%   |
| HP Scanjet 200                                          | 1         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.26%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.26%   |
| Canon CanoScan LiDE 210                                 | 1         | 5.26%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1303      | 19.9%   |
| Microdia                               | 730       | 11.15%  |
| Realtek Semiconductor                  | 603       | 9.21%   |
| Quanta                                 | 554       | 8.46%   |
| Silicon Motion                         | 497       | 7.59%   |
| Sunplus Innovation Technology          | 460       | 7.02%   |
| Acer                                   | 424       | 6.47%   |
| IMC Networks                           | 268       | 4.09%   |
| Suyin                                  | 254       | 3.88%   |
| Logitech                               | 237       | 3.62%   |
| Syntek                                 | 183       | 2.79%   |
| Alcor Micro                            | 133       | 2.03%   |
| Apple                                  | 93        | 1.42%   |
| Samsung Electronics                    | 82        | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) | 77        | 1.18%   |
| Z-Star Microelectronics                | 56        | 0.86%   |
| Generalplus Technology                 | 53        | 0.81%   |
| Microsoft                              | 50        | 0.76%   |
| Ricoh                                  | 44        | 0.67%   |
| ALi                                    | 42        | 0.64%   |
| Unknown                                | 29        | 0.44%   |
| Aveo Technology                        | 26        | 0.4%    |
| Lite-On Technology                     | 22        | 0.34%   |
| OmniVision Technologies                | 21        | 0.32%   |
| Importek                               | 21        | 0.32%   |
| GEMBIRD                                | 21        | 0.32%   |
| Pixart Imaging                         | 19        | 0.29%   |
| LG Electronics                         | 18        | 0.27%   |
| Lenovo                                 | 16        | 0.24%   |
| Jieli Technology                       | 16        | 0.24%   |
| Cubeternet                             | 14        | 0.21%   |
| Sonix Technology                       | 11        | 0.17%   |
| icSpring                               | 11        | 0.17%   |
| Intel                                  | 10        | 0.15%   |
| Genesys Logic                          | 10        | 0.15%   |
| SunplusIT                              | 9         | 0.14%   |
| Sunplus Technology                     | 9         | 0.14%   |
| Camera                                 | 9         | 0.14%   |
| Y Media                                | 7         | 0.11%   |
| MacroSilicon                           | 7         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD              | 259       | 3.95%   |
| Microdia Integrated_Webcam_HD             | 245       | 3.73%   |
| Quanta HD User Facing                     | 233       | 3.55%   |
| Chicony HD User Facing                    | 192       | 2.93%   |
| Chicony HD Webcam                         | 190       | 2.9%    |
| Silicon Motion Web Camera                 | 182       | 2.77%   |
| Sunplus Integrated_Webcam_HD              | 176       | 2.68%   |
| Quanta VGA WebCam                         | 171       | 2.61%   |
| Chicony USB 2.0 Camera                    | 140       | 2.13%   |
| Chicony VGA WebCam                        | 132       | 2.01%   |
| Chicony Integrated Camera                 | 128       | 1.95%   |
| Syntek Integrated Camera                  | 98        | 1.49%   |
| Realtek Integrated Webcam                 | 97        | 1.48%   |
| Quanta HD Webcam                          | 95        | 1.45%   |
| Sunplus HD WebCam                         | 94        | 1.43%   |
| Microdia Laptop_Integrated_Webcam_HD      | 93        | 1.42%   |
| Logitech Webcam C270                      | 91        | 1.39%   |
| Alcor Micro USB 2.0 WebCamera             | 83        | 1.27%   |
| Samsung Galaxy series, misc. (MTP mode)   | 81        | 1.23%   |
| Acer BisonCam, NB Pro                     | 69        | 1.05%   |
| Acer EasyCamera                           | 64        | 0.98%   |
| Acer Lenovo EasyCamera                    | 61        | 0.93%   |
| Microdia Dell Laptop Integrated Webcam HD | 53        | 0.81%   |
| Logitech HD Pro Webcam C920               | 50        | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N      | 47        | 0.72%   |
| Microdia Integrated Webcam HD             | 44        | 0.67%   |
| IMC Networks Integrated Camera            | 43        | 0.66%   |
| Acer VGA WebCam                           | 43        | 0.66%   |
| Realtek USB Camera                        | 42        | 0.64%   |
| Realtek HD WebCam                         | 40        | 0.61%   |
| Generalplus GENERAL WEBCAM                | 40        | 0.61%   |
| Chicony EasyCamera                        | 40        | 0.61%   |
| Suyin Integrated_Webcam_HD                | 39        | 0.59%   |
| Silicon Motion WebCam SCB-1100N           | 39        | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 39        | 0.59%   |
| Silicon Motion WebCam SC-13HDL11939N      | 37        | 0.56%   |
| Acer HD Webcam                            | 36        | 0.55%   |
| Syntek EasyCamera                         | 35        | 0.53%   |
| Acer USB Camera                           | 34        | 0.52%   |
| Silicon Motion WebCam SC-0311139N         | 33        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 263       | 47.39%  |
| Synaptics                  | 65        | 11.71%  |
| Shenzhen Goodix Technology | 61        | 10.99%  |
| AuthenTec                  | 54        | 9.73%   |
| Upek                       | 52        | 9.37%   |
| LighTuning Technology      | 29        | 5.23%   |
| Samsung Electronics        | 15        | 2.7%    |
| Elan Microelectronics      | 8         | 1.44%   |
| STMicroelectronics         | 3         | 0.54%   |
| Dell                       | 2         | 0.36%   |
| Futronic Technology        | 1         | 0.18%   |
| Focal-systems.Corp         | 1         | 0.18%   |
| DigitalPersona             | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 100       | 18.02%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 44        | 7.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 41        | 7.39%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 4.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.68%   |
| LighTuning EgisTec_ES603                                                   | 24        | 4.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 3.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.78%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.24%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 15        | 2.7%    |
| Synaptics  WBDI                                                            | 15        | 2.7%    |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 2.7%    |
| Samsung Fingerprint Device                                                 | 15        | 2.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 2.34%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.16%   |
| AuthenTec AES2810                                                          | 12        | 2.16%   |
| Validity Sensors VFS491                                                    | 11        | 1.98%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.8%    |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.62%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.44%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.44%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.26%   |
| Unknown                                                                    | 7         | 1.26%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.08%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.54%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.36%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.36%   |
| AuthenTec AES1600                                                          | 2         | 0.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.18%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.18%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.18%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.18%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 72        | 41.86%  |
| Alcor Micro                       | 27        | 15.7%   |
| Gemalto (was Gemplus)             | 14        | 8.14%   |
| Lenovo                            | 13        | 7.56%   |
| Giesecke & Devrient               | 11        | 6.4%    |
| Upek                              | 8         | 4.65%   |
| Watchdata                         | 6         | 3.49%   |
| Aladdin Knowledge Systems         | 6         | 3.49%   |
| SCM Microsystems                  | 3         | 1.74%   |
| OmniKey                           | 3         | 1.74%   |
| O2 Micro                          | 3         | 1.74%   |
| Chicony Electronics               | 3         | 1.74%   |
| VASCO Data Security International | 1         | 0.58%   |
| Realtek Semiconductor             | 1         | 0.58%   |
| Advanced Card Systems             | 1         | 0.58%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 15.7%   |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 11.63%  |
| Broadcom 58200                                                               | 19        | 11.05%  |
| Broadcom 5880                                                                | 17        | 9.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 9.3%    |
| Lenovo Integrated Smart Card Reader                                          | 13        | 7.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 13        | 7.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 4.65%   |
| Watchdata USB Key                                                            | 6         | 3.49%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.49%   |
| Aladdin Knowledge Systems Token JC                                           | 6         | 3.49%   |
| Giesecke & Devrient StarSign CUT S                                           | 5         | 2.91%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.74%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 1.16%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.16%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.16%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.58%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.58%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.58%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.58%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.58%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.58%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.58%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8601      | 79.8%   |
| 1     | 1906      | 17.68%  |
| 2     | 219       | 2.03%   |
| 3     | 31        | 0.29%   |
| 4     | 13        | 0.12%   |
| 7     | 4         | 0.04%   |
| 8     | 2         | 0.02%   |
| 5     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 734       | 30.13%  |
| Fingerprint reader       | 551       | 22.62%  |
| Net/wireless             | 308       | 12.64%  |
| Multimedia controller    | 201       | 8.25%   |
| Chipcard                 | 147       | 6.03%   |
| Communication controller | 95        | 3.9%    |
| Bluetooth                | 82        | 3.37%   |
| Camera                   | 69        | 2.83%   |
| Sound                    | 52        | 2.13%   |
| Unassigned class         | 49        | 2.01%   |
| Storage                  | 37        | 1.52%   |
| Net/ethernet             | 28        | 1.15%   |
| Modem                    | 23        | 0.94%   |
| Flash memory             | 20        | 0.82%   |
| Card reader              | 13        | 0.53%   |
| Network                  | 8         | 0.33%   |
| Storage/ide              | 6         | 0.25%   |
| Firewire controller      | 5         | 0.21%   |
| Storage/raid             | 4         | 0.16%   |
| Video                    | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |


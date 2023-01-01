Linux in Saudi Arabia - Tested Hardware & Statistics
----------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Saudi_Arabia/Desktop/README.md) and [notebooks](/Location/Saudi_Arabia/Notebook/README.md).

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

Total: 422

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Spin SP513-54N              | Convertible | [0cb6dfa7ce](https://linux-hardware.org/?probe=0cb6dfa7ce) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [eeec310401](https://linux-hardware.org/?probe=eeec310401) | Dec 26, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [13d0daca4c](https://linux-hardware.org/?probe=13d0daca4c) | Dec 23, 2022 |
| HP            | 212B                        | Desktop     | [3df121c98b](https://linux-hardware.org/?probe=3df121c98b) | Dec 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [42584fd968](https://linux-hardware.org/?probe=42584fd968) | Dec 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [eb95cbbbe0](https://linux-hardware.org/?probe=eb95cbbbe0) | Dec 03, 2022 |
| Toshiba       | Satellite L635              | Notebook    | [be223c0ff1](https://linux-hardware.org/?probe=be223c0ff1) | Dec 03, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [a92a0830e9](https://linux-hardware.org/?probe=a92a0830e9) | Nov 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| HP            | 212B                        | Desktop     | [d5cc313fba](https://linux-hardware.org/?probe=d5cc313fba) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [3e86b56fb8](https://linux-hardware.org/?probe=3e86b56fb8) | Oct 23, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [7f90427c64](https://linux-hardware.org/?probe=7f90427c64) | Oct 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [61f05a7c32](https://linux-hardware.org/?probe=61f05a7c32) | Oct 10, 2022 |
| Sony          | SVF15A13SAB                 | Notebook    | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [de59de7b14](https://linux-hardware.org/?probe=de59de7b14) | Oct 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [bf7151a851](https://linux-hardware.org/?probe=bf7151a851) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| Dell          | G15 5515                    | Notebook    | [ae769dae75](https://linux-hardware.org/?probe=ae769dae75) | Sep 24, 2022 |
| Dell          | G15 5515                    | Notebook    | [893c248dec](https://linux-hardware.org/?probe=893c248dec) | Sep 24, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a934e23e1f](https://linux-hardware.org/?probe=a934e23e1f) | Sep 16, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c65050e714](https://linux-hardware.org/?probe=c65050e714) | Sep 09, 2022 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [8373c5268a](https://linux-hardware.org/?probe=8373c5268a) | Sep 05, 2022 |
| Dell          | Latitude 7275               | Tablet      | [fce77a6b4b](https://linux-hardware.org/?probe=fce77a6b4b) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [896ceefe29](https://linux-hardware.org/?probe=896ceefe29) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [b87b0407d9](https://linux-hardware.org/?probe=b87b0407d9) | Aug 29, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [fbb579a5d6](https://linux-hardware.org/?probe=fbb579a5d6) | Aug 29, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [4ecdbb8b4b](https://linux-hardware.org/?probe=4ecdbb8b4b) | Aug 15, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [1364037a8f](https://linux-hardware.org/?probe=1364037a8f) | Aug 01, 2022 |
| eMachines     | Unknown                     | Notebook    | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| Dell          | 06WXJT A02                  | Server      | [2dfd532279](https://linux-hardware.org/?probe=2dfd532279) | Jun 08, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [870c420b4b](https://linux-hardware.org/?probe=870c420b4b) | Jun 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [34a1b11f96](https://linux-hardware.org/?probe=34a1b11f96) | Jun 02, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d7d06bf7ef](https://linux-hardware.org/?probe=d7d06bf7ef) | May 26, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| Dell          | 0M9KCM A01                  | Desktop     | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [b7443972f3](https://linux-hardware.org/?probe=b7443972f3) | Apr 28, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8c3b142c85](https://linux-hardware.org/?probe=8c3b142c85) | Apr 23, 2022 |
| Dell          | Latitude 7275               | Tablet      | [8b373dc563](https://linux-hardware.org/?probe=8b373dc563) | Apr 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Unknown       | HX90                        | Desktop     | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [45548a6fe5](https://linux-hardware.org/?probe=45548a6fe5) | Apr 07, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [1f1a2dbacc](https://linux-hardware.org/?probe=1f1a2dbacc) | Apr 05, 2022 |
| Dell          | Latitude 7275               | Tablet      | [4e3f9ca88e](https://linux-hardware.org/?probe=4e3f9ca88e) | Apr 02, 2022 |
| Unknown       | HX90                        | Desktop     | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| Unknown       | HX90                        | Desktop     | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bc999f46f9](https://linux-hardware.org/?probe=bc999f46f9) | Mar 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [1e0ad3b3cd](https://linux-hardware.org/?probe=1e0ad3b3cd) | Mar 27, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [50131c5da4](https://linux-hardware.org/?probe=50131c5da4) | Mar 21, 2022 |
| Acer          | AO751h                      | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b2f7222ddb](https://linux-hardware.org/?probe=b2f7222ddb) | Feb 27, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [bb620cc0f9](https://linux-hardware.org/?probe=bb620cc0f9) | Feb 26, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [007ec5dbf5](https://linux-hardware.org/?probe=007ec5dbf5) | Feb 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [14bcc9219c](https://linux-hardware.org/?probe=14bcc9219c) | Feb 18, 2022 |
| Dell          | Latitude 7275               | Tablet      | [143e5a0a20](https://linux-hardware.org/?probe=143e5a0a20) | Feb 16, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [43b019326c](https://linux-hardware.org/?probe=43b019326c) | Feb 12, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [70f23c3da0](https://linux-hardware.org/?probe=70f23c3da0) | Feb 12, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [fe9b9a47f1](https://linux-hardware.org/?probe=fe9b9a47f1) | Feb 11, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| ASRock        | B365M Phantom Gaming 4      | Desktop     | [9dd59e5403](https://linux-hardware.org/?probe=9dd59e5403) | Feb 08, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e0748343d9](https://linux-hardware.org/?probe=e0748343d9) | Feb 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| HP            | 15                          | Notebook    | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [92f528e80b](https://linux-hardware.org/?probe=92f528e80b) | Jan 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [261fe8bda7](https://linux-hardware.org/?probe=261fe8bda7) | Jan 07, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [3fbda09d01](https://linux-hardware.org/?probe=3fbda09d01) | Jan 01, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [be19f6df45](https://linux-hardware.org/?probe=be19f6df45) | Dec 29, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Packard Be... | EasyNote TJ65               | Notebook    | [b98b9252fa](https://linux-hardware.org/?probe=b98b9252fa) | Dec 29, 2021 |
| MSI           | MS-7529                     | Desktop     | [c9b87dcf45](https://linux-hardware.org/?probe=c9b87dcf45) | Dec 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [046dcdd20d](https://linux-hardware.org/?probe=046dcdd20d) | Dec 25, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [af71cff698](https://linux-hardware.org/?probe=af71cff698) | Dec 21, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [609baca194](https://linux-hardware.org/?probe=609baca194) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [35ec8b1dbb](https://linux-hardware.org/?probe=35ec8b1dbb) | Dec 16, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [2a151de62b](https://linux-hardware.org/?probe=2a151de62b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [25ca2e2c75](https://linux-hardware.org/?probe=25ca2e2c75) | Dec 04, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 20RA008CAD     | Notebook    | [35fab17b69](https://linux-hardware.org/?probe=35fab17b69) | Dec 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [a1abd4e08e](https://linux-hardware.org/?probe=a1abd4e08e) | Nov 26, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [e37587fbac](https://linux-hardware.org/?probe=e37587fbac) | Nov 23, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [b050debd0a](https://linux-hardware.org/?probe=b050debd0a) | Nov 22, 2021 |
| Dell          | G3 3590                     | Notebook    | [605f0870d0](https://linux-hardware.org/?probe=605f0870d0) | Nov 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [5bfafc889c](https://linux-hardware.org/?probe=5bfafc889c) | Nov 16, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | V570 1066AJU                | Notebook    | [ffb36aac10](https://linux-hardware.org/?probe=ffb36aac10) | Nov 05, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [41451fb2a2](https://linux-hardware.org/?probe=41451fb2a2) | Nov 05, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a5026c4013](https://linux-hardware.org/?probe=a5026c4013) | Oct 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5233ea30c6](https://linux-hardware.org/?probe=5233ea30c6) | Oct 09, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [65c4bea87a](https://linux-hardware.org/?probe=65c4bea87a) | Oct 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [d91c23c12c](https://linux-hardware.org/?probe=d91c23c12c) | Oct 08, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b22e6dc21a](https://linux-hardware.org/?probe=b22e6dc21a) | Oct 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [428e41ed23](https://linux-hardware.org/?probe=428e41ed23) | Oct 05, 2021 |
| Lenovo        | ThinkPad P52s 20LBS0JC00    | Notebook    | [4c8c63da2f](https://linux-hardware.org/?probe=4c8c63da2f) | Oct 05, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2e99b047ff](https://linux-hardware.org/?probe=2e99b047ff) | Oct 04, 2021 |
| Dell          | Latitude 7275               | Tablet      | [c844ef39cd](https://linux-hardware.org/?probe=c844ef39cd) | Oct 03, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [85a91a83fa](https://linux-hardware.org/?probe=85a91a83fa) | Oct 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [de6b4e47d4](https://linux-hardware.org/?probe=de6b4e47d4) | Oct 01, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [28332170d1](https://linux-hardware.org/?probe=28332170d1) | Sep 28, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Dell          | 054KM3 A01                  | Desktop     | [6d277dcd36](https://linux-hardware.org/?probe=6d277dcd36) | Sep 18, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [ef4fb4b996](https://linux-hardware.org/?probe=ef4fb4b996) | Aug 28, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e5251674c0](https://linux-hardware.org/?probe=e5251674c0) | Aug 25, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [3d5e02e265](https://linux-hardware.org/?probe=3d5e02e265) | Aug 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [4c8282bb42](https://linux-hardware.org/?probe=4c8282bb42) | Aug 16, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f91acefb07](https://linux-hardware.org/?probe=f91acefb07) | Aug 14, 2021 |
| Dell          | 03X6X0 A06                  | Server      | [d52db39eeb](https://linux-hardware.org/?probe=d52db39eeb) | Jul 26, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [162b090056](https://linux-hardware.org/?probe=162b090056) | Jul 14, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [8d7689bceb](https://linux-hardware.org/?probe=8d7689bceb) | Jul 14, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [5bcc11cd03](https://linux-hardware.org/?probe=5bcc11cd03) | Jul 08, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| ASUSTek       | K43SJ                       | Notebook    | [f4702e95b4](https://linux-hardware.org/?probe=f4702e95b4) | Jul 05, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | 0W0CHX A01                  | Desktop     | [e0a09aa1a5](https://linux-hardware.org/?probe=e0a09aa1a5) | Jul 01, 2021 |
| Dell          | G3 3590                     | Notebook    | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Dell          | 0XHGV1 A01                  | Desktop     | [4fcd4b7e98](https://linux-hardware.org/?probe=4fcd4b7e98) | Jun 22, 2021 |
| Intel         | BTC-T37                     | Desktop     | [6cd9eb4fd4](https://linux-hardware.org/?probe=6cd9eb4fd4) | Jun 19, 2021 |
| Intel         | BTC-T37                     | Desktop     | [3f0a790d81](https://linux-hardware.org/?probe=3f0a790d81) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [06f25de7e3](https://linux-hardware.org/?probe=06f25de7e3) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [3fcbd5cd4f](https://linux-hardware.org/?probe=3fcbd5cd4f) | Jun 18, 2021 |
| Dell          | G3 3590                     | Notebook    | [877018f0d3](https://linux-hardware.org/?probe=877018f0d3) | Jun 18, 2021 |
| Dell          | G3 3590                     | Notebook    | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [7e5e7767c0](https://linux-hardware.org/?probe=7e5e7767c0) | Jun 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [88e51bfd39](https://linux-hardware.org/?probe=88e51bfd39) | May 23, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ea32add5cd](https://linux-hardware.org/?probe=ea32add5cd) | May 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [96e19f007a](https://linux-hardware.org/?probe=96e19f007a) | May 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cfcef26a52](https://linux-hardware.org/?probe=cfcef26a52) | May 20, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [f146c310d6](https://linux-hardware.org/?probe=f146c310d6) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1d4c05756f](https://linux-hardware.org/?probe=1d4c05756f) | May 01, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [febcf69966](https://linux-hardware.org/?probe=febcf69966) | Apr 28, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [34b2d651e1](https://linux-hardware.org/?probe=34b2d651e1) | Apr 28, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9b03874730](https://linux-hardware.org/?probe=9b03874730) | Apr 27, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e0acc229ef](https://linux-hardware.org/?probe=e0acc229ef) | Apr 25, 2021 |
| Dell          | Latitude E7470              | Notebook    | [1058573f86](https://linux-hardware.org/?probe=1058573f86) | Apr 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [14fd40d980](https://linux-hardware.org/?probe=14fd40d980) | Apr 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b31da2d02](https://linux-hardware.org/?probe=0b31da2d02) | Apr 16, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [82dd7f530a](https://linux-hardware.org/?probe=82dd7f530a) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [f97ecb74c0](https://linux-hardware.org/?probe=f97ecb74c0) | Apr 09, 2021 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [cd64675ac7](https://linux-hardware.org/?probe=cd64675ac7) | Mar 30, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [9ede240e19](https://linux-hardware.org/?probe=9ede240e19) | Mar 20, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [7d8acdd5b6](https://linux-hardware.org/?probe=7d8acdd5b6) | Mar 19, 2021 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [f568952b1d](https://linux-hardware.org/?probe=f568952b1d) | Mar 10, 2021 |
| Huanan        | X99-F8                      | Desktop     | [3bbee45dc4](https://linux-hardware.org/?probe=3bbee45dc4) | Mar 10, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c03aab940e](https://linux-hardware.org/?probe=c03aab940e) | Feb 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [66003aa802](https://linux-hardware.org/?probe=66003aa802) | Feb 28, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [290dbb71c2](https://linux-hardware.org/?probe=290dbb71c2) | Feb 25, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [260d78f7c8](https://linux-hardware.org/?probe=260d78f7c8) | Feb 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [30bcebb4be](https://linux-hardware.org/?probe=30bcebb4be) | Feb 16, 2021 |
| HP            | 8591                        | Desktop     | [b6b7f6af35](https://linux-hardware.org/?probe=b6b7f6af35) | Feb 15, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c8b28bb334](https://linux-hardware.org/?probe=c8b28bb334) | Feb 13, 2021 |
| Lenovo        | ThinkPad E460 20ET000MAD    | Notebook    | [cd000b8e6b](https://linux-hardware.org/?probe=cd000b8e6b) | Feb 11, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [5ed908976b](https://linux-hardware.org/?probe=5ed908976b) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5407a15ab7](https://linux-hardware.org/?probe=5407a15ab7) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [0802cedb25](https://linux-hardware.org/?probe=0802cedb25) | Feb 09, 2021 |
| Dell          | Latitude E4310              | Notebook    | [9c6781e592](https://linux-hardware.org/?probe=9c6781e592) | Feb 08, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [1d97b5c83d](https://linux-hardware.org/?probe=1d97b5c83d) | Jan 31, 2021 |
| ASUSTek       | ROG Strix G512LWS_G512LW... | Notebook    | [d4d3110510](https://linux-hardware.org/?probe=d4d3110510) | Jan 29, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [5911afaa7a](https://linux-hardware.org/?probe=5911afaa7a) | Jan 27, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [6bdd3b4a5d](https://linux-hardware.org/?probe=6bdd3b4a5d) | Jan 27, 2021 |
| Acer          | Spin SP111-33               | Convertible | [0a09d00b74](https://linux-hardware.org/?probe=0a09d00b74) | Jan 23, 2021 |
| Toshiba       | Satellite C855D             | Notebook    | [46d5bf62c7](https://linux-hardware.org/?probe=46d5bf62c7) | Jan 19, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [99f1a1ac09](https://linux-hardware.org/?probe=99f1a1ac09) | Jan 16, 2021 |
| Sony          | VGN-FZ250E                  | Notebook    | [d0d77ffe81](https://linux-hardware.org/?probe=d0d77ffe81) | Jan 15, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92ea4004af](https://linux-hardware.org/?probe=92ea4004af) | Jan 15, 2021 |
| Sony          | VGN-FZ250E                  | Notebook    | [68ddc53941](https://linux-hardware.org/?probe=68ddc53941) | Jan 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [b21e44d0c4](https://linux-hardware.org/?probe=b21e44d0c4) | Jan 11, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [e57dfe6f39](https://linux-hardware.org/?probe=e57dfe6f39) | Dec 30, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2249011658](https://linux-hardware.org/?probe=2249011658) | Dec 30, 2020 |
| Dell          | 0GN6JF A01                  | Desktop     | [b4ea210c79](https://linux-hardware.org/?probe=b4ea210c79) | Dec 27, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [216df384d8](https://linux-hardware.org/?probe=216df384d8) | Dec 22, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [bec1b16786](https://linux-hardware.org/?probe=bec1b16786) | Dec 22, 2020 |
| LG Electro... | R490-G.ARL5RE2              | Notebook    | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| OEM           | B250                        | Desktop     | [80af247c92](https://linux-hardware.org/?probe=80af247c92) | Dec 09, 2020 |
| HP            | 198E                        | Desktop     | [d6e4336d03](https://linux-hardware.org/?probe=d6e4336d03) | Dec 08, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [6c1033e9f9](https://linux-hardware.org/?probe=6c1033e9f9) | Dec 04, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [1e0a7199b7](https://linux-hardware.org/?probe=1e0a7199b7) | Dec 03, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [239675db8d](https://linux-hardware.org/?probe=239675db8d) | Nov 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dfcc723611](https://linux-hardware.org/?probe=dfcc723611) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b164be6cfc](https://linux-hardware.org/?probe=b164be6cfc) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| HP            | 843C                        | Desktop     | [fd8c0fa877](https://linux-hardware.org/?probe=fd8c0fa877) | Nov 10, 2020 |
| OEM           | B250                        | Desktop     | [f6bcb7135c](https://linux-hardware.org/?probe=f6bcb7135c) | Nov 10, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [cce5403051](https://linux-hardware.org/?probe=cce5403051) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| I-Life Dig... | ZED Air Plus                | Notebook    | [b1a43bf9f2](https://linux-hardware.org/?probe=b1a43bf9f2) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e9ca4c8d42](https://linux-hardware.org/?probe=e9ca4c8d42) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c45580b2f3](https://linux-hardware.org/?probe=c45580b2f3) | Oct 28, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [1816b1fb29](https://linux-hardware.org/?probe=1816b1fb29) | Oct 23, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e80544ed81](https://linux-hardware.org/?probe=e80544ed81) | Oct 20, 2020 |
| MSI           | MS-1454                     | Notebook    | [0accbf6c77](https://linux-hardware.org/?probe=0accbf6c77) | Oct 14, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [1d466d105c](https://linux-hardware.org/?probe=1d466d105c) | Oct 12, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1c5dde63a](https://linux-hardware.org/?probe=e1c5dde63a) | Oct 12, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [a1665a6de1](https://linux-hardware.org/?probe=a1665a6de1) | Sep 26, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ec057ab8d](https://linux-hardware.org/?probe=3ec057ab8d) | Sep 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [d52f9c5bc7](https://linux-hardware.org/?probe=d52f9c5bc7) | Sep 18, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [6963343ed4](https://linux-hardware.org/?probe=6963343ed4) | Sep 17, 2020 |
| ASRock        | Z270M Pro4                  | Desktop     | [ed0a963b78](https://linux-hardware.org/?probe=ed0a963b78) | Sep 05, 2020 |
| Clevo         | P15xEMx                     | Notebook    | [83d0f6aae6](https://linux-hardware.org/?probe=83d0f6aae6) | Aug 28, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [8634132c3a](https://linux-hardware.org/?probe=8634132c3a) | Aug 24, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [54032f9ee7](https://linux-hardware.org/?probe=54032f9ee7) | Aug 19, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | Notebook    | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [c04081db17](https://linux-hardware.org/?probe=c04081db17) | Aug 07, 2020 |
| HP            | Pavilion g6                 | Notebook    | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [fa825c1fce](https://linux-hardware.org/?probe=fa825c1fce) | Jul 26, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [3098a39bdb](https://linux-hardware.org/?probe=3098a39bdb) | Jul 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [1c82bd39f0](https://linux-hardware.org/?probe=1c82bd39f0) | Jul 01, 2020 |
| Microsoft     | Surface Pro 7               | Tablet      | [69744692b0](https://linux-hardware.org/?probe=69744692b0) | Jun 30, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | Notebook    | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | Notebook    | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Dell          | 0GN6JF A01                  | Desktop     | [452e0f2712](https://linux-hardware.org/?probe=452e0f2712) | Jun 16, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [c5f91bc1ff](https://linux-hardware.org/?probe=c5f91bc1ff) | Jun 16, 2020 |
| Dell          | Inspiron N5030              | Notebook    | [5641d9b86e](https://linux-hardware.org/?probe=5641d9b86e) | Jun 14, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6c1261f611](https://linux-hardware.org/?probe=6c1261f611) | Jun 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [eb4135b12e](https://linux-hardware.org/?probe=eb4135b12e) | Jun 07, 2020 |
| Pegatron      | 2A84h                       | Desktop     | [a5884bfb13](https://linux-hardware.org/?probe=a5884bfb13) | Jun 01, 2020 |
| ASUSTek       | UX390UAK                    | Notebook    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Gigabyte      | H61M-S2P                    | Desktop     | [aecc9b0111](https://linux-hardware.org/?probe=aecc9b0111) | May 25, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [447ac858da](https://linux-hardware.org/?probe=447ac858da) | May 24, 2020 |
| Sony          | SVF153290X                  | Notebook    | [e19f1c716f](https://linux-hardware.org/?probe=e19f1c716f) | May 23, 2020 |
| Gigabyte      | B75M-HD3                    | Desktop     | [bedfc8fa0f](https://linux-hardware.org/?probe=bedfc8fa0f) | May 21, 2020 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [874c2cb817](https://linux-hardware.org/?probe=874c2cb817) | May 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [117bc7af0e](https://linux-hardware.org/?probe=117bc7af0e) | May 17, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [1947ac6d52](https://linux-hardware.org/?probe=1947ac6d52) | May 16, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [dc7f6cc9e8](https://linux-hardware.org/?probe=dc7f6cc9e8) | May 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0444dd48d1](https://linux-hardware.org/?probe=0444dd48d1) | May 09, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [8ee1846a65](https://linux-hardware.org/?probe=8ee1846a65) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [bff527c13e](https://linux-hardware.org/?probe=bff527c13e) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8b02fac19f](https://linux-hardware.org/?probe=8b02fac19f) | Apr 26, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [48acf05b1b](https://linux-hardware.org/?probe=48acf05b1b) | Apr 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [640431a321](https://linux-hardware.org/?probe=640431a321) | Apr 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [095b8a5cdc](https://linux-hardware.org/?probe=095b8a5cdc) | Apr 16, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [874b42a4b7](https://linux-hardware.org/?probe=874b42a4b7) | Apr 16, 2020 |
| HP            | 15                          | Notebook    | [68b0d776a9](https://linux-hardware.org/?probe=68b0d776a9) | Apr 08, 2020 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [784de80b54](https://linux-hardware.org/?probe=784de80b54) | Apr 08, 2020 |
| HP            | Notebook                    | Notebook    | [f22cd145c5](https://linux-hardware.org/?probe=f22cd145c5) | Apr 07, 2020 |
| HP            | 15                          | Notebook    | [27ef1499e3](https://linux-hardware.org/?probe=27ef1499e3) | Apr 06, 2020 |
| HP            | 15                          | Notebook    | [0c2b7adf55](https://linux-hardware.org/?probe=0c2b7adf55) | Apr 06, 2020 |
| HP            | 15                          | Notebook    | [ee5fd88936](https://linux-hardware.org/?probe=ee5fd88936) | Apr 03, 2020 |
| HP            | 15                          | Notebook    | [bfd4fe41b3](https://linux-hardware.org/?probe=bfd4fe41b3) | Apr 03, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [cdce411ba5](https://linux-hardware.org/?probe=cdce411ba5) | Mar 13, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [6e7a1c3bc6](https://linux-hardware.org/?probe=6e7a1c3bc6) | Mar 13, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d3d2a3b89f](https://linux-hardware.org/?probe=d3d2a3b89f) | Mar 05, 2020 |
| ASUSTek       | X555QA                      | Notebook    | [2f0a038eaf](https://linux-hardware.org/?probe=2f0a038eaf) | Feb 11, 2020 |
| ASUSTek       | X555QA                      | Notebook    | [e8062aced5](https://linux-hardware.org/?probe=e8062aced5) | Feb 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [5aaf89e123](https://linux-hardware.org/?probe=5aaf89e123) | Feb 03, 2020 |
| Dell          | Vostro 1440                 | Notebook    | [203e61a7c9](https://linux-hardware.org/?probe=203e61a7c9) | Feb 01, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [fbdcd4fb9f](https://linux-hardware.org/?probe=fbdcd4fb9f) | Jan 30, 2020 |
| HP            | Notebook                    | Notebook    | [86dc2687ad](https://linux-hardware.org/?probe=86dc2687ad) | Jan 29, 2020 |
| HP            | Notebook                    | Notebook    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | Notebook    | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | Notebook    | [953a43ae80](https://linux-hardware.org/?probe=953a43ae80) | Jan 02, 2020 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [bb1c5e0c3a](https://linux-hardware.org/?probe=bb1c5e0c3a) | Jan 01, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [0da4e7552a](https://linux-hardware.org/?probe=0da4e7552a) | Dec 29, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [c137a7866b](https://linux-hardware.org/?probe=c137a7866b) | Dec 14, 2019 |
| Lenovo        | ThinkPad X230 2325OA3       | Notebook    | [ad8913bb6b](https://linux-hardware.org/?probe=ad8913bb6b) | Dec 09, 2019 |
| GPD           | MicroPC                     | Notebook    | [37bfeee080](https://linux-hardware.org/?probe=37bfeee080) | Dec 09, 2019 |
| MSI           | 2A78h                       | Desktop     | [83e806e50e](https://linux-hardware.org/?probe=83e806e50e) | Oct 25, 2019 |
| MSI           | 2A78h                       | Desktop     | [b5679811c8](https://linux-hardware.org/?probe=b5679811c8) | Oct 25, 2019 |
| MSI           | B360M GAMING PLUS           | Desktop     | [f54aa10fcc](https://linux-hardware.org/?probe=f54aa10fcc) | Oct 24, 2019 |
| MSI           | B360M GAMING PLUS           | Desktop     | [96ee6c9f88](https://linux-hardware.org/?probe=96ee6c9f88) | Oct 24, 2019 |
| ASUSTek       | SABERTOOTH Z97 MARK 2/US... | Desktop     | [4976e1673d](https://linux-hardware.org/?probe=4976e1673d) | Oct 01, 2019 |
| ASUSTek       | X555LDB                     | Notebook    | [fffe9c8500](https://linux-hardware.org/?probe=fffe9c8500) | Sep 04, 2019 |
| ASUSTek       | X555LDB                     | Notebook    | [60bc2f13a4](https://linux-hardware.org/?probe=60bc2f13a4) | Sep 04, 2019 |
| Dell          | 0HN7XN A01                  | Desktop     | [b9dd067151](https://linux-hardware.org/?probe=b9dd067151) | Aug 18, 2019 |
| Dell          | 0HN7XN A01                  | Desktop     | [67161826ca](https://linux-hardware.org/?probe=67161826ca) | Aug 18, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [0a1b8c3a29](https://linux-hardware.org/?probe=0a1b8c3a29) | Aug 17, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [4b1cbc26db](https://linux-hardware.org/?probe=4b1cbc26db) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [5670d72491](https://linux-hardware.org/?probe=5670d72491) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [81bd1c9f07](https://linux-hardware.org/?probe=81bd1c9f07) | Aug 13, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [bc9f90fd94](https://linux-hardware.org/?probe=bc9f90fd94) | Jul 20, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [a5dd292f0e](https://linux-hardware.org/?probe=a5dd292f0e) | Jul 20, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [78b4fe060a](https://linux-hardware.org/?probe=78b4fe060a) | Jul 19, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [b3224eb5fc](https://linux-hardware.org/?probe=b3224eb5fc) | Jul 19, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [f8b4fc087b](https://linux-hardware.org/?probe=f8b4fc087b) | Jul 13, 2019 |
| Sony          | VPCEA36FA                   | Notebook    | [069db5e1d5](https://linux-hardware.org/?probe=069db5e1d5) | Jul 11, 2019 |
| HUAWEI        | MateBook D                  | Notebook    | [0c82ca3724](https://linux-hardware.org/?probe=0c82ca3724) | Jul 06, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [b66944b7d8](https://linux-hardware.org/?probe=b66944b7d8) | Jun 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [630f59eb30](https://linux-hardware.org/?probe=630f59eb30) | Jun 12, 2019 |
| Dell          | Latitude 5285               | Tablet      | [73b87c222f](https://linux-hardware.org/?probe=73b87c222f) | Jun 12, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [3d424bc8d3](https://linux-hardware.org/?probe=3d424bc8d3) | Jun 07, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [8b98fb721c](https://linux-hardware.org/?probe=8b98fb721c) | Jun 07, 2019 |
| Dell          | 0PC5F7 A02                  | Desktop     | [d5c119cb28](https://linux-hardware.org/?probe=d5c119cb28) | Jun 04, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [9a655727f9](https://linux-hardware.org/?probe=9a655727f9) | Jun 02, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [5bca621b29](https://linux-hardware.org/?probe=5bca621b29) | May 31, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [ced21dc1f3](https://linux-hardware.org/?probe=ced21dc1f3) | May 21, 2019 |
| Dell          | Latitude 5285               | Tablet      | [fcedd9ded7](https://linux-hardware.org/?probe=fcedd9ded7) | Apr 25, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [14b4f17a8a](https://linux-hardware.org/?probe=14b4f17a8a) | Apr 22, 2019 |
| Sony          | SVF14N13CXB                 | Notebook    | [37e231ce84](https://linux-hardware.org/?probe=37e231ce84) | Apr 07, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [4a17c281b7](https://linux-hardware.org/?probe=4a17c281b7) | Apr 05, 2019 |
| HP            | 15                          | Notebook    | [e900ad9cfc](https://linux-hardware.org/?probe=e900ad9cfc) | Mar 15, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [8366ef739b](https://linux-hardware.org/?probe=8366ef739b) | Jan 19, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [8c5dcea151](https://linux-hardware.org/?probe=8c5dcea151) | Jan 07, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [f238cfd7d7](https://linux-hardware.org/?probe=f238cfd7d7) | Jan 07, 2019 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d44c9b123d](https://linux-hardware.org/?probe=d44c9b123d) | Dec 19, 2018 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b0c7903cb1](https://linux-hardware.org/?probe=b0c7903cb1) | Dec 19, 2018 |
| Lenovo        | NOK                         | Desktop     | [2761f888c3](https://linux-hardware.org/?probe=2761f888c3) | Nov 16, 2018 |
| Acer          | Aspire E1-532P              | Notebook    | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [3e2fa165a6](https://linux-hardware.org/?probe=3e2fa165a6) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [a7272b3797](https://linux-hardware.org/?probe=a7272b3797) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [9c149f8d89](https://linux-hardware.org/?probe=9c149f8d89) | Oct 28, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [5c682ba446](https://linux-hardware.org/?probe=5c682ba446) | Oct 26, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [28a72027c5](https://linux-hardware.org/?probe=28a72027c5) | Oct 25, 2018 |
| Gigabyte      | P35-DS3R                    | Desktop     | [2f8f1a592b](https://linux-hardware.org/?probe=2f8f1a592b) | Aug 14, 2018 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [d9e3df518a](https://linux-hardware.org/?probe=d9e3df518a) | Dec 08, 2017 |
| Dell          | 0VNP2H A00                  | Desktop     | [68fa7ad805](https://linux-hardware.org/?probe=68fa7ad805) | Nov 25, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Ubuntu 20.04           | 36        | 13.04%  |
| Ubuntu 18.04           | 18        | 6.52%   |
| OpenMandriva 4.2       | 13        | 4.71%   |
| OpenMandriva 4.3       | 9         | 3.26%   |
| Ubuntu 22.04           | 8         | 2.9%    |
| Fedora 35              | 7         | 2.54%   |
| Pop!_OS 21.10          | 6         | 2.17%   |
| Ubuntu 20.10           | 5         | 1.81%   |
| Ubuntu 19.04           | 5         | 1.81%   |
| Pop!_OS 22.04          | 5         | 1.81%   |
| Pop!_OS 21.04          | 5         | 1.81%   |
| Manjaro                | 5         | 1.81%   |
| KDE neon 20.04         | 5         | 1.81%   |
| Arch                   | 5         | 1.81%   |
| Zorin 16               | 4         | 1.45%   |
| Ubuntu 21.04           | 4         | 1.45%   |
| Ubuntu 19.10           | 4         | 1.45%   |
| Kubuntu 20.04          | 4         | 1.45%   |
| Fedora 36              | 4         | 1.45%   |
| Debian Testing         | 4         | 1.45%   |
| Debian 11              | 4         | 1.45%   |
| Debian 10              | 4         | 1.45%   |
| Ubuntu 21.10           | 3         | 1.09%   |
| ROSA R10               | 3         | 1.09%   |
| Pop!_OS 20.10          | 3         | 1.09%   |
| Pop!_OS 20.04          | 3         | 1.09%   |
| Manjaro 20.0.3         | 3         | 1.09%   |
| Linux Mint 20.3        | 3         | 1.09%   |
| Linux Mint 20.1        | 3         | 1.09%   |
| Kubuntu 22.10          | 3         | 1.09%   |
| Endless 3.3.20-nexthw1 | 3         | 1.09%   |
| ArcoLinux Rolling      | 3         | 1.09%   |
| Zorin 15               | 2         | 0.72%   |
| Ubuntu 22.10           | 2         | 0.72%   |
| Manjaro 20.2           | 2         | 0.72%   |
| Linux Mint 21          | 2         | 0.72%   |
| Linux Mint 20          | 2         | 0.72%   |
| Kali 2021.2            | 2         | 0.72%   |
| Fedora 37              | 2         | 0.72%   |
| Fedora 33              | 2         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 81        | 32.02%  |
| OpenMandriva     | 23        | 9.09%   |
| Endless          | 18        | 7.11%   |
| Fedora           | 16        | 6.32%   |
| Pop!_OS          | 15        | 5.93%   |
| Manjaro          | 14        | 5.53%   |
| Debian           | 12        | 4.74%   |
| Linux Mint       | 10        | 3.95%   |
| Kubuntu          | 7         | 2.77%   |
| Zorin            | 6         | 2.37%   |
| ROSA             | 6         | 2.37%   |
| KDE neon         | 6         | 2.37%   |
| Kali             | 5         | 1.98%   |
| Arch             | 5         | 1.98%   |
| Xubuntu          | 4         | 1.58%   |
| Clear Linux      | 3         | 1.19%   |
| ArcoLinux        | 3         | 1.19%   |
| Ubuntu Unity     | 2         | 0.79%   |
| Solus            | 2         | 0.79%   |
| EndeavourOS      | 2         | 0.79%   |
| Ubuntu MATE      | 1         | 0.4%    |
| Ubuntu Budgie    | 1         | 0.4%    |
| RHEL             | 1         | 0.4%    |
| Q4OS             | 1         | 0.4%    |
| Pear OS          | 1         | 0.4%    |
| Parrot           | 1         | 0.4%    |
| org.kde.Platform | 1         | 0.4%    |
| Lubuntu          | 1         | 0.4%    |
| Liberty OS       | 1         | 0.4%    |
| Gentoo           | 1         | 0.4%    |
| Elementary       | 1         | 0.4%    |
| Drauger OS       | 1         | 0.4%    |
| CentOS           | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 12        | 3.99%   |
| 5.16.7-desktop-1omv4003         | 9         | 2.99%   |
| 5.4.0-42-generic                | 6         | 1.99%   |
| 5.4.0-19-generic                | 4         | 1.33%   |
| 5.3.0-28-generic                | 4         | 1.33%   |
| 5.19.0-26-generic               | 4         | 1.33%   |
| 5.15.0-48-generic               | 4         | 1.33%   |
| 5.13.0-7614-generic             | 4         | 1.33%   |
| 5.11.0-43-generic               | 4         | 1.33%   |
| 4.15.0-15-generic               | 4         | 1.33%   |
| 5.8.0-14-generic                | 3         | 1%      |
| 5.16.19-76051619-generic        | 3         | 1%      |
| 5.15.5-76051505-generic         | 3         | 1%      |
| 5.15.0-46-generic               | 3         | 1%      |
| 5.13.0-37-generic               | 3         | 1%      |
| 5.11.0-41-generic               | 3         | 1%      |
| 5.11.0-40-generic               | 3         | 1%      |
| 5.11.0-31-generic               | 3         | 1%      |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 1%      |
| 4.18.0-17-generic               | 3         | 1%      |
| 4.15.0-29-generic               | 3         | 1%      |
| 5.9.11-3-MANJARO                | 2         | 0.66%   |
| 5.8.0-53-generic                | 2         | 0.66%   |
| 5.8.0-44-generic                | 2         | 0.66%   |
| 5.8.0-41-generic                | 2         | 0.66%   |
| 5.8.0-38-generic                | 2         | 0.66%   |
| 5.8.0-36-generic                | 2         | 0.66%   |
| 5.8.0-25-generic                | 2         | 0.66%   |
| 5.7.9-1-MANJARO                 | 2         | 0.66%   |
| 5.4.0-58-generic                | 2         | 0.66%   |
| 5.4.0-47-generic                | 2         | 0.66%   |
| 5.4.0-39-generic                | 2         | 0.66%   |
| 5.4.0-37-generic                | 2         | 0.66%   |
| 5.4.0-31-generic                | 2         | 0.66%   |
| 5.3.0-2-amd64                   | 2         | 0.66%   |
| 5.19.0-23-generic               | 2         | 0.66%   |
| 5.15.15-76051515-generic        | 2         | 0.66%   |
| 5.15.0-27-generic               | 2         | 0.66%   |
| 5.13.19-2-MANJARO               | 2         | 0.66%   |
| 5.13.0-39-generic               | 2         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 35        | 12.15%  |
| 5.8.0   | 24        | 8.33%   |
| 5.11.0  | 21        | 7.29%   |
| 5.15.0  | 17        | 5.9%    |
| 5.3.0   | 16        | 5.56%   |
| 4.15.0  | 14        | 4.86%   |
| 5.10.14 | 12        | 4.17%   |
| 5.13.0  | 10        | 3.47%   |
| 4.18.0  | 10        | 3.47%   |
| 5.16.7  | 9         | 3.13%   |
| 5.19.0  | 8         | 2.78%   |
| 5.0.0   | 8         | 2.78%   |
| 5.10.0  | 7         | 2.43%   |
| 5.16.19 | 3         | 1.04%   |
| 5.16.11 | 3         | 1.04%   |
| 5.15.5  | 3         | 1.04%   |
| 4.9.60  | 3         | 1.04%   |
| 6.0.8   | 2         | 0.69%   |
| 5.9.11  | 2         | 0.69%   |
| 5.7.9   | 2         | 0.69%   |
| 5.6.15  | 2         | 0.69%   |
| 5.5.0   | 2         | 0.69%   |
| 5.19.12 | 2         | 0.69%   |
| 5.15.15 | 2         | 0.69%   |
| 5.13.19 | 2         | 0.69%   |
| 4.19.0  | 2         | 0.69%   |
| 6.1.0   | 1         | 0.35%   |
| 6.0.6   | 1         | 0.35%   |
| 6.0.5   | 1         | 0.35%   |
| 6.0.15  | 1         | 0.35%   |
| 6.0.0   | 1         | 0.35%   |
| 5.9.10  | 1         | 0.35%   |
| 5.9.0   | 1         | 0.35%   |
| 5.8.5   | 1         | 0.35%   |
| 5.8.18  | 1         | 0.35%   |
| 5.8.11  | 1         | 0.35%   |
| 5.7.0   | 1         | 0.35%   |
| 5.6.4   | 1         | 0.35%   |
| 5.6.14  | 1         | 0.35%   |
| 5.6.0   | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 13.17%  |
| 5.15    | 29        | 10.32%  |
| 5.8     | 27        | 9.61%   |
| 5.11    | 24        | 8.54%   |
| 5.10    | 23        | 8.19%   |
| 5.16    | 19        | 6.76%   |
| 5.3     | 16        | 5.69%   |
| 4.15    | 14        | 4.98%   |
| 5.13    | 13        | 4.63%   |
| 5.19    | 12        | 4.27%   |
| 4.18    | 11        | 3.91%   |
| 5.0     | 8         | 2.85%   |
| 6.0     | 6         | 2.14%   |
| 4.9     | 6         | 2.14%   |
| 5.6     | 5         | 1.78%   |
| 5.17    | 5         | 1.78%   |
| 5.9     | 4         | 1.42%   |
| 5.5     | 4         | 1.42%   |
| 5.18    | 4         | 1.42%   |
| 5.7     | 3         | 1.07%   |
| 5.14    | 3         | 1.07%   |
| 5.12    | 2         | 0.71%   |
| 4.19    | 2         | 0.71%   |
| 6.1     | 1         | 0.36%   |
| 4.20    | 1         | 0.36%   |
| 4.13    | 1         | 0.36%   |
| 4.1     | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 226       | 97.41%  |
| i686   | 6         | 2.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 115       | 46.18%  |
| KDE5       | 48        | 19.28%  |
| Unknown    | 33        | 13.25%  |
| XFCE       | 12        | 4.82%   |
| X-Cinnamon | 10        | 4.02%   |
| KDE        | 9         | 3.61%   |
| KDE4       | 4         | 1.61%   |
| Cinnamon   | 4         | 1.61%   |
| Budgie     | 3         | 1.2%    |
| Unity      | 2         | 0.8%    |
| MATE       | 2         | 0.8%    |
| trinity    | 1         | 0.4%    |
| Pantheon   | 1         | 0.4%    |
| openbox    | 1         | 0.4%    |
| LXQt       | 1         | 0.4%    |
| i3         | 1         | 0.4%    |
| Deepin     | 1         | 0.4%    |
| bspwm      | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 182       | 76.15%  |
| Wayland | 29        | 12.13%  |
| Unknown | 23        | 9.62%   |
| Tty     | 5         | 2.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 141       | 57.09%  |
| SDDM    | 42        | 17%     |
| GDM     | 23        | 9.31%   |
| GDM3    | 20        | 8.1%    |
| TDM     | 9         | 3.64%   |
| LightDM | 8         | 3.24%   |
| KDM     | 4         | 1.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 162       | 66.67%  |
| Unknown | 33        | 13.58%  |
| ar_SA   | 14        | 5.76%   |
| ar_EG   | 11        | 4.53%   |
| en_GB   | 9         | 3.7%    |
| C       | 4         | 1.65%   |
| ar_AE   | 3         | 1.23%   |
| en_IN   | 1         | 0.41%   |
| en_IL   | 1         | 0.41%   |
| en_AU   | 1         | 0.41%   |
| en_AG   | 1         | 0.41%   |
| de_DE   | 1         | 0.41%   |
| Default | 1         | 0.41%   |
| cs_CZ   | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 128       | 53.11%  |
| EFI  | 113       | 46.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 188       | 78.01%  |
| Btrfs   | 17        | 7.05%   |
| Overlay | 15        | 6.22%   |
| Unknown | 12        | 4.98%   |
| Xfs     | 3         | 1.24%   |
| Ext2    | 3         | 1.24%   |
| Tmpfs   | 2         | 0.83%   |
| Zfs     | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 156       | 63.67%  |
| GPT     | 69        | 28.16%  |
| MBR     | 20        | 8.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 86.55%  |
| Yes       | 32        | 13.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 70.17%  |
| Yes       | 71        | 29.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Dell                        | 50        | 21.55%  |
| ASUSTek Computer            | 37        | 15.95%  |
| Lenovo                      | 28        | 12.07%  |
| Hewlett-Packard             | 25        | 10.78%  |
| MSI                         | 15        | 6.47%   |
| Gigabyte Technology         | 15        | 6.47%   |
| Acer                        | 13        | 5.6%    |
| ASRock                      | 8         | 3.45%   |
| Toshiba                     | 6         | 2.59%   |
| Sony                        | 6         | 2.59%   |
| HUAWEI                      | 4         | 1.72%   |
| Apple                       | 4         | 1.72%   |
| Pegatron                    | 2         | 0.86%   |
| Notebook                    | 2         | 0.86%   |
| Microsoft                   | 2         | 0.86%   |
| Intel                       | 2         | 0.86%   |
| Unknown                     | 2         | 0.86%   |
| Samsung Electronics         | 1         | 0.43%   |
| Packard Bell                | 1         | 0.43%   |
| OEM                         | 1         | 0.43%   |
| LG Electronics              | 1         | 0.43%   |
| I-Life Digital Technologies | 1         | 0.43%   |
| Huanan                      | 1         | 0.43%   |
| GPD                         | 1         | 0.43%   |
| Fujitsu Siemens             | 1         | 0.43%   |
| eMachines                   | 1         | 0.43%   |
| Clevo                       | 1         | 0.43%   |
| Biostar                     | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 1.72%   |
| HP 15                                      | 3         | 1.29%   |
| Dell G3 3590                               | 3         | 1.29%   |
| Unknown                                    | 3         | 1.29%   |
| Microsoft Surface Pro 7                    | 2         | 0.86%   |
| HP Pavilion g6                             | 2         | 0.86%   |
| HP Notebook                                | 2         | 0.86%   |
| HP ENVY x360 Convertible 15-ed1xxx         | 2         | 0.86%   |
| Gigabyte H81M-S2PH                         | 2         | 0.86%   |
| Dell OptiPlex 9020                         | 2         | 0.86%   |
| Dell OptiPlex 9010                         | 2         | 0.86%   |
| Dell OptiPlex 7050                         | 2         | 0.86%   |
| Dell OptiPlex 7010                         | 2         | 0.86%   |
| Dell Latitude 5285                         | 2         | 0.86%   |
| Dell Inspiron 3542                         | 2         | 0.86%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 2         | 0.86%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 0.86%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 0.86%   |
| ASUS All Series                            | 2         | 0.86%   |
| Acer Aspire 4752                           | 2         | 0.86%   |
| Toshiba Satellite S55t-A                   | 1         | 0.43%   |
| Toshiba Satellite L635                     | 1         | 0.43%   |
| Toshiba Satellite L500                     | 1         | 0.43%   |
| Toshiba Satellite C855D                    | 1         | 0.43%   |
| Toshiba Satellite C55-B                    | 1         | 0.43%   |
| Toshiba QOSMIO X875                        | 1         | 0.43%   |
| Sony VPCEA36FA                             | 1         | 0.43%   |
| Sony VPCCA35FA                             | 1         | 0.43%   |
| Sony VGN-FZ250E                            | 1         | 0.43%   |
| Sony SVF15A13SAB                           | 1         | 0.43%   |
| Sony SVF153290X                            | 1         | 0.43%   |
| Sony SVF14N13CXB                           | 1         | 0.43%   |
| Samsung 870Z5E/880Z5E/680Z5E               | 1         | 0.43%   |
| Pegatron h8-1400ex                         | 1         | 0.43%   |
| Pegatron Compaq dx7500 Microtower          | 1         | 0.43%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.43%   |
| OEM B250                                   | 1         | 0.43%   |
| Notebook PD5x_7xPNP_PNN_PNT                | 1         | 0.43%   |
| Notebook NH5xAx                            | 1         | 0.43%   |
| MSI MS-7D20                                | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell OptiPlex      | 16        | 6.9%    |
| Dell Inspiron      | 11        | 4.74%   |
| ASUS VivoBook      | 10        | 4.31%   |
| Lenovo ThinkPad    | 9         | 3.88%   |
| HP Pavilion        | 7         | 3.02%   |
| Dell Latitude      | 7         | 3.02%   |
| Acer Aspire        | 7         | 3.02%   |
| Toshiba Satellite  | 5         | 2.16%   |
| HP Laptop          | 5         | 2.16%   |
| Dell Vostro        | 5         | 2.16%   |
| Lenovo IdeaPad     | 4         | 1.72%   |
| ASUS ROG           | 4         | 1.72%   |
| Lenovo Yoga        | 3         | 1.29%   |
| Lenovo ThinkCentre | 3         | 1.29%   |
| HP 15              | 3         | 1.29%   |
| Dell G3            | 3         | 1.29%   |
| ASUS TUF           | 3         | 1.29%   |
| Unknown            | 3         | 1.29%   |
| Microsoft Surface  | 2         | 0.86%   |
| Lenovo Legion      | 2         | 0.86%   |
| HP Notebook        | 2         | 0.86%   |
| HP ENVY            | 2         | 0.86%   |
| Gigabyte H81M-S2PH | 2         | 0.86%   |
| Dell XPS           | 2         | 0.86%   |
| Dell Precision     | 2         | 0.86%   |
| Dell PowerEdge     | 2         | 0.86%   |
| ASUS PRIME         | 2         | 0.86%   |
| ASUS All           | 2         | 0.86%   |
| ASRock X570        | 2         | 0.86%   |
| Acer Spin          | 2         | 0.86%   |
| Toshiba QOSMIO     | 1         | 0.43%   |
| Sony VPCEA36FA     | 1         | 0.43%   |
| Sony VPCCA35FA     | 1         | 0.43%   |
| Sony VGN-FZ250E    | 1         | 0.43%   |
| Sony SVF15A13SAB   | 1         | 0.43%   |
| Sony SVF153290X    | 1         | 0.43%   |
| Sony SVF14N13CXB   | 1         | 0.43%   |
| Samsung 870Z5E     | 1         | 0.43%   |
| Pegatron h8-1400ex | 1         | 0.43%   |
| Pegatron Compaq    | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 33        | 14.22%  |
| 2019 | 29        | 12.5%   |
| 2020 | 24        | 10.34%  |
| 2017 | 19        | 8.19%   |
| 2013 | 18        | 7.76%   |
| 2012 | 18        | 7.76%   |
| 2021 | 15        | 6.47%   |
| 2014 | 14        | 6.03%   |
| 2011 | 14        | 6.03%   |
| 2010 | 12        | 5.17%   |
| 2015 | 11        | 4.74%   |
| 2016 | 9         | 3.88%   |
| 2009 | 5         | 2.16%   |
| 2008 | 4         | 1.72%   |
| 2007 | 3         | 1.29%   |
| 2022 | 2         | 0.86%   |
| 2006 | 1         | 0.43%   |
| 2002 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 124       | 53.45%  |
| Desktop     | 85        | 36.64%  |
| Convertible | 10        | 4.31%   |
| Tablet      | 8         | 3.45%   |
| All in one  | 2         | 0.86%   |
| Server      | 2         | 0.86%   |
| Mini pc     | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 213       | 91.03%  |
| Enabled  | 21        | 8.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 232       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 52        | 21.85%  |
| 4.01-8.0    | 51        | 21.43%  |
| 16.01-24.0  | 45        | 18.91%  |
| 8.01-16.0   | 41        | 17.23%  |
| 32.01-64.0  | 22        | 9.24%   |
| 1.01-2.0    | 12        | 5.04%   |
| 2.01-3.0    | 5         | 2.1%    |
| 64.01-256.0 | 5         | 2.1%    |
| 24.01-32.0  | 4         | 1.68%   |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 94        | 35.34%  |
| 2.01-3.0   | 66        | 24.81%  |
| 3.01-4.0   | 40        | 15.04%  |
| 4.01-8.0   | 39        | 14.66%  |
| 0.51-1.0   | 16        | 6.02%   |
| 8.01-16.0  | 10        | 3.76%   |
| 16.01-24.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 153       | 62.2%   |
| 2      | 52        | 21.14%  |
| 3      | 26        | 10.57%  |
| 4      | 5         | 2.03%   |
| 6      | 4         | 1.63%   |
| 5      | 4         | 1.63%   |
| 7      | 1         | 0.41%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 59.75%  |
| Yes       | 95        | 40.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 81.28%  |
| No        | 44        | 18.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 81.97%  |
| No        | 42        | 18.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 67.66%  |
| No        | 76        | 32.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 232       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Riyadh               | 92        | 37.25%  |
| Jeddah               | 67        | 27.13%  |
| Makkah               | 20        | 8.1%    |
| Medina               | 18        | 7.29%   |
| Dammam               | 17        | 6.88%   |
| Khobar               | 8         | 3.24%   |
| Al Qatif             | 8         | 3.24%   |
| Thuwal               | 3         | 1.21%   |
| Dhahran              | 3         | 1.21%   |
| Ta'if                | 2         | 0.81%   |
| Buraidah             | 2         | 0.81%   |
| Baq`a' ash Sharqiyah | 2         | 0.81%   |
| Al Faruq             | 2         | 0.81%   |
| Sayhat               | 1         | 0.4%    |
| Jubail               | 1         | 0.4%    |
| Al Hufuf             | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 68        | 109    | 19.43%  |
| Seagate                   | 58        | 83     | 16.57%  |
| Samsung Electronics       | 36        | 57     | 10.29%  |
| Toshiba                   | 35        | 43     | 10%     |
| Kingston                  | 34        | 57     | 9.71%   |
| SanDisk                   | 17        | 18     | 4.86%   |
| Unknown                   | 14        | 26     | 4%      |
| Crucial                   | 9         | 12     | 2.57%   |
| SK hynix                  | 7         | 14     | 2%      |
| Intel                     | 7         | 15     | 2%      |
| Hitachi                   | 7         | 8      | 2%      |
| Silicon Motion            | 5         | 6      | 1.43%   |
| Team                      | 4         | 4      | 1.14%   |
| Phison                    | 4         | 4      | 1.14%   |
| Lexar                     | 4         | 4      | 1.14%   |
| Micron/Crucial Technology | 3         | 3      | 0.86%   |
| KingSpec                  | 3         | 3      | 0.86%   |
| SPCC                      | 2         | 2      | 0.57%   |
| PNY                       | 2         | 2      | 0.57%   |
| Phison Electronics        | 2         | 2      | 0.57%   |
| JMicron Technology        | 2         | 2      | 0.57%   |
| HS-SSD-C100               | 2         | 3      | 0.57%   |
| HGST                      | 2         | 5      | 0.57%   |
| Hewlett-Packard           | 2         | 2      | 0.57%   |
| Fujitsu                   | 2         | 2      | 0.57%   |
| China                     | 2         | 2      | 0.57%   |
| Apple                     | 2         | 4      | 0.57%   |
| YMTC                      | 1         | 1      | 0.29%   |
| XrayDisk                  | 1         | 1      | 0.29%   |
| WD MediaMax               | 1         | 1      | 0.29%   |
| UMIS                      | 1         | 1      | 0.29%   |
| SPCC Sol                  | 1         | 1      | 0.29%   |
| OYUNKEY                   | 1         | 1      | 0.29%   |
| Micron Technology         | 1         | 1      | 0.29%   |
| Maxtor                    | 1         | 1      | 0.29%   |
| LITEON                    | 1         | 1      | 0.29%   |
| KIOXIA                    | 1         | 1      | 0.29%   |
| Hoodisk                   | 1         | 1      | 0.29%   |
| G-DRIVE                   | 1         | 1      | 0.29%   |
| Biostar                   | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 12        | 3.04%   |
| Toshiba MQ04ABF100 1TB             | 9         | 2.28%   |
| Kingston SA400S37240G 240GB SSD    | 9         | 2.28%   |
| Kingston SA400S37480G 480GB SSD    | 7         | 1.77%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 5         | 1.27%   |
| Samsung NVMe SSD Drive 1024GB      | 5         | 1.27%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 4         | 1.01%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.01%   |
| Kingston SA400S37120G 120GB SSD    | 4         | 1.01%   |
| WDC WD10EZEX-75WN4A1 1TB           | 3         | 0.76%   |
| Toshiba MQ01ABF050 500GB           | 3         | 0.76%   |
| Toshiba MQ01ABD100 1TB             | 3         | 0.76%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB     | 3         | 0.76%   |
| SanDisk NVMe SSD Drive 512GB       | 3         | 0.76%   |
| SanDisk NVMe SSD Drive 128GB       | 3         | 0.76%   |
| Samsung SSD 860 EVO 500GB          | 3         | 0.76%   |
| Samsung SSD 860 EVO 1TB            | 3         | 0.76%   |
| Lexar 128GB SSD                    | 3         | 0.76%   |
| Kingston SA400S37960G 960GB SSD    | 3         | 0.76%   |
| Intel NVMe SSD Drive 1024GB        | 3         | 0.76%   |
| Crucial CT1000MX500SSD1 1TB        | 3         | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 2         | 0.51%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 2         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.51%   |
| WDC WD10EADS-00M2B0 1TB            | 2         | 0.51%   |
| Unknown MMC Card  64GB             | 2         | 0.51%   |
| Unknown MMC Card  32GB             | 2         | 0.51%   |
| Unknown MMC Card  134GB            | 2         | 0.51%   |
| Unknown ED4QT  128GB               | 2         | 0.51%   |
| Toshiba NVMe SSD Drive 256GB       | 2         | 0.51%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.51%   |
| Toshiba MK1059GSM 1TB              | 2         | 0.51%   |
| Toshiba DT01ACA050 500GB           | 2         | 0.51%   |
| SK hynix NVMe SSD Drive 1024GB     | 2         | 0.51%   |
| Silicon Motion NVMe SSD Drive 2TB  | 2         | 0.51%   |
| Seagate ST9500325AS 500GB          | 2         | 0.51%   |
| Seagate ST1000DM003-9YN162 1TB     | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 58        | 93     | 35.8%   |
| Seagate | 58        | 83     | 35.8%   |
| Toshiba | 32        | 36     | 19.75%  |
| Hitachi | 7         | 8      | 4.32%   |
| HGST    | 2         | 5      | 1.23%   |
| Fujitsu | 2         | 2      | 1.23%   |
| Unknown | 1         | 3      | 0.62%   |
| Maxtor  | 1         | 1      | 0.62%   |
| Apple   | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 52     | 31.91%  |
| Samsung Electronics | 15        | 27     | 15.96%  |
| Crucial             | 9         | 11     | 9.57%   |
| SanDisk             | 7         | 7      | 7.45%   |
| WDC                 | 5         | 8      | 5.32%   |
| Lexar               | 4         | 4      | 4.26%   |
| Team                | 3         | 3      | 3.19%   |
| KingSpec            | 3         | 3      | 3.19%   |
| SK hynix            | 2         | 3      | 2.13%   |
| PNY                 | 2         | 2      | 2.13%   |
| China               | 2         | 2      | 2.13%   |
| XrayDisk            | 1         | 1      | 1.06%   |
| SPCC Sol            | 1         | 1      | 1.06%   |
| SPCC                | 1         | 1      | 1.06%   |
| OYUNKEY             | 1         | 1      | 1.06%   |
| LITEON              | 1         | 1      | 1.06%   |
| JMicron Technology  | 1         | 1      | 1.06%   |
| Intel               | 1         | 4      | 1.06%   |
| Hoodisk             | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| G-DRIVE             | 1         | 1      | 1.06%   |
| A-DATA Technology   | 1         | 1      | 1.06%   |
| Unknown             | 1         | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 137       | 232    | 44.05%  |
| SSD     | 86        | 137    | 27.65%  |
| NVMe    | 71        | 109    | 22.83%  |
| MMC     | 13        | 24     | 4.18%   |
| Unknown | 4         | 5      | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 362    | 66.54%  |
| NVMe | 71        | 109    | 26.1%   |
| MMC  | 13        | 24     | 4.78%   |
| SAS  | 7         | 12     | 2.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 182    | 44.93%  |
| 0.51-1.0   | 93        | 142    | 40.97%  |
| 1.01-2.0   | 21        | 32     | 9.25%   |
| 3.01-4.0   | 8         | 8      | 3.52%   |
| 2.01-3.0   | 2         | 3      | 0.88%   |
| 4.01-10.0  | 1         | 2      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 22.53%  |
| 251-500        | 56        | 22.13%  |
| 501-1000       | 54        | 21.34%  |
| 51-100         | 21        | 8.3%    |
| 1-20           | 17        | 6.72%   |
| 1001-2000      | 13        | 5.14%   |
| More than 3000 | 12        | 4.74%   |
| 21-50          | 10        | 3.95%   |
| 2001-3000      | 9         | 3.56%   |
| Unknown        | 4         | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 109       | 40.98%  |
| 21-50          | 56        | 21.05%  |
| 51-100         | 28        | 10.53%  |
| 251-500        | 22        | 8.27%   |
| 101-250        | 21        | 7.89%   |
| 501-1000       | 11        | 4.14%   |
| 1001-2000      | 9         | 3.38%   |
| Unknown        | 4         | 1.5%    |
| More than 3000 | 3         | 1.13%   |
| 2001-3000      | 2         | 0.75%   |
| 0              | 1         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-00WWPA0 500GB       | 1         | 1      | 5.26%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 5.26%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 5.26%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1         | 1      | 5.26%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1         | 1      | 5.26%   |
| WDC WD10PURZ-85U8XY0 1TB           | 1         | 1      | 5.26%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 5.26%   |
| WDC WD10EUCX-73YZ1Y0 1TB           | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB    | 1         | 1      | 5.26%   |
| Seagate ST2000DM001-1CH164 2TB     | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-9YN162 1TB     | 1         | 1      | 5.26%   |
| OYUNKEY SSD 120GB                  | 1         | 1      | 5.26%   |
| Kingston SA400S37480G 480GB SSD    | 1         | 1      | 5.26%   |
| Hitachi HDS721032CLA362 320GB      | 1         | 1      | 5.26%   |
| Unknown                            | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 8         | 8      | 44.44%  |
| Seagate  | 5         | 6      | 27.78%  |
| Toshiba  | 1         | 1      | 5.56%   |
| OYUNKEY  | 1         | 1      | 5.56%   |
| Kingston | 1         | 1      | 5.56%   |
| Hitachi  | 1         | 1      | 5.56%   |
| Unknown  | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 53.33%  |
| Seagate | 5         | 6      | 33.33%  |
| Toshiba | 1         | 1      | 6.67%   |
| Hitachi | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 81.25%  |
| SSD  | 3         | 3      | 18.75%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 165       | 348    | 63.71%  |
| Works    | 79        | 140    | 30.5%   |
| Malfunc  | 15        | 19     | 5.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 179       | 62.15%  |
| AMD                              | 27        | 9.38%   |
| Samsung Electronics              | 22        | 7.64%   |
| SanDisk                          | 13        | 4.51%   |
| Silicon Motion                   | 7         | 2.43%   |
| SK hynix                         | 5         | 1.74%   |
| Phison Electronics               | 5         | 1.74%   |
| Kingston Technology Company      | 5         | 1.74%   |
| Toshiba America Info Systems     | 4         | 1.39%   |
| Micron/Crucial Technology        | 4         | 1.39%   |
| ASMedia Technology               | 4         | 1.39%   |
| Broadcom / LSI                   | 2         | 0.69%   |
| Yangtze Memory Technologies      | 1         | 0.35%   |
| VIA Technologies                 | 1         | 0.35%   |
| Union Memory (Shenzhen)          | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Realtek Semiconductor            | 1         | 0.35%   |
| Nvidia                           | 1         | 0.35%   |
| Micron Technology                | 1         | 0.35%   |
| LSI Logic / Symbios Logic        | 1         | 0.35%   |
| JMicron Technology               | 1         | 0.35%   |
| Apple                            | 1         | 0.35%   |
| ADATA Technology                 | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 6.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 5.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 3.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 3.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 3.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 2.83%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.52%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.26%   |
| Intel SSD 660P Series                                                          | 4         | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 4         | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.26%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4         | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.94%   |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.94%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.94%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.63%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.63%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 167       | 58.6%   |
| NVMe | 71        | 24.91%  |
| RAID | 25        | 8.77%   |
| IDE  | 21        | 7.37%   |
| SAS  | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 202       | 87.07%  |
| AMD    | 30        | 12.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 3%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 2.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.29%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 1.29%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 1.29%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 1.29%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.29%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.29%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.29%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.29%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.86%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.86%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.86%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.86%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.86%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.86%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.86%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.86%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.86%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.86%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.86%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.86%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.86%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 66        | 28.33%  |
| Intel Core i5           | 61        | 26.18%  |
| Intel Core i3           | 17        | 7.3%    |
| Intel Celeron           | 16        | 6.87%   |
| AMD Ryzen 5             | 12        | 5.15%   |
| Other                   | 10        | 4.29%   |
| Intel Core 2 Duo        | 8         | 3.43%   |
| AMD Ryzen 7             | 8         | 3.43%   |
| AMD Ryzen 9             | 6         | 2.58%   |
| Intel Xeon              | 5         | 2.15%   |
| Intel Atom              | 5         | 2.15%   |
| Intel Pentium Dual-Core | 3         | 1.29%   |
| Intel Pentium           | 3         | 1.29%   |
| AMD FX                  | 2         | 0.86%   |
| Intel Xeon Silver       | 1         | 0.43%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Pentium 4         | 1         | 0.43%   |
| Intel Mobile Pentium 4  | 1         | 0.43%   |
| Intel Core m5           | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| Intel Core 2 Quad       | 1         | 0.43%   |
| Intel Core 2            | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD E2                  | 1         | 0.43%   |
| AMD A12                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 91        | 39.06%  |
| 2      | 88        | 37.77%  |
| 6      | 22        | 9.44%   |
| 8      | 16        | 6.87%   |
| 1      | 7         | 3%      |
| 16     | 2         | 0.86%   |
| 14     | 2         | 0.86%   |
| 12     | 2         | 0.86%   |
| 10     | 2         | 0.86%   |
| 20     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 230       | 99.14%  |
| 2      | 2         | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 161       | 69.1%   |
| 1      | 71        | 30.47%  |
| 8      | 1         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 225       | 96.57%  |
| Unknown        | 6         | 2.58%   |
| 32-bit         | 2         | 0.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 28.4%   |
| 0x306a9    | 19        | 7.6%    |
| 0x306c3    | 13        | 5.2%    |
| 0x206a7    | 13        | 5.2%    |
| 0x40651    | 11        | 4.4%    |
| 0x1067a    | 11        | 4.4%    |
| 0x906e9    | 7         | 2.8%    |
| 0x806e9    | 7         | 2.8%    |
| 0x906ea    | 6         | 2.4%    |
| 0x806ec    | 6         | 2.4%    |
| 0x806ea    | 6         | 2.4%    |
| 0x706e5    | 6         | 2.4%    |
| 0x406e3    | 6         | 2.4%    |
| 0x806c1    | 5         | 2%      |
| 0x706a1    | 5         | 2%      |
| 0x20655    | 4         | 1.6%    |
| 0x08108109 | 4         | 1.6%    |
| 0x30673    | 3         | 1.2%    |
| 0x20652    | 3         | 1.2%    |
| 0xa0653    | 2         | 0.8%    |
| 0x906ed    | 2         | 0.8%    |
| 0x906a3    | 2         | 0.8%    |
| 0x806eb    | 2         | 0.8%    |
| 0x506c9    | 2         | 0.8%    |
| 0x406c4    | 2         | 0.8%    |
| 0x306d4    | 2         | 0.8%    |
| 0x08701021 | 2         | 0.8%    |
| 0x08701013 | 2         | 0.8%    |
| 0xf64      | 1         | 0.4%    |
| 0xf27      | 1         | 0.4%    |
| 0xa0655    | 1         | 0.4%    |
| 0xa0652    | 1         | 0.4%    |
| 0x906ec    | 1         | 0.4%    |
| 0x906eb    | 1         | 0.4%    |
| 0x906c0    | 1         | 0.4%    |
| 0x706a8    | 1         | 0.4%    |
| 0x6fa      | 1         | 0.4%    |
| 0x6f2      | 1         | 0.4%    |
| 0x506e3    | 1         | 0.4%    |
| 0x50657    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 54        | 23.18%  |
| Haswell          | 26        | 11.16%  |
| IvyBridge        | 23        | 9.87%   |
| SandyBridge      | 15        | 6.44%   |
| Skylake          | 13        | 5.58%   |
| Penryn           | 12        | 5.15%   |
| Zen 3            | 10        | 4.29%   |
| Goldmont plus    | 9         | 3.86%   |
| Zen+             | 8         | 3.43%   |
| Westmere         | 8         | 3.43%   |
| Zen 2            | 7         | 3%      |
| IceLake          | 7         | 3%      |
| TigerLake        | 5         | 2.15%   |
| Silvermont       | 5         | 2.15%   |
| CometLake        | 4         | 1.72%   |
| Unknown          | 4         | 1.72%   |
| Nehalem          | 3         | 1.29%   |
| Goldmont         | 3         | 1.29%   |
| Core             | 3         | 1.29%   |
| Broadwell        | 3         | 1.29%   |
| Piledriver       | 2         | 0.86%   |
| NetBurst         | 2         | 0.86%   |
| Alderlake Hybrid | 2         | 0.86%   |
| Zen              | 1         | 0.43%   |
| Tremont          | 1         | 0.43%   |
| Excavator        | 1         | 0.43%   |
| Bonnell          | 1         | 0.43%   |
| Bobcat           | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 157       | 53.4%   |
| Nvidia                           | 85        | 28.91%  |
| AMD                              | 48        | 16.33%  |
| Matrox Electronics Systems       | 2         | 0.68%   |
| VIA Technologies                 | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 4.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 12        | 4.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 3.69%   |
| Intel HD Graphics 620                                                         | 10        | 3.36%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 9         | 3.02%   |
| Intel UHD Graphics 620                                                        | 8         | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 7         | 2.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 2.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 2.35%   |
| Intel HD Graphics 630                                                         | 6         | 2.01%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6         | 2.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6         | 2.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 2.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 1.34%   |
| Nvidia GK208B [GeForce GT 730]                                                | 4         | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 1.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 1.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 1.34%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 1.34%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 3         | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 3         | 1.01%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3         | 1.01%   |
| Intel Iris Plus Graphics G7                                                   | 3         | 1.01%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 1.01%   |
| Intel HD Graphics 5500                                                        | 3         | 1.01%   |
| Intel HD Graphics 500                                                         | 3         | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 3         | 1.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 1.01%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 3         | 1.01%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 2         | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2         | 0.67%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 0.67%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 43.16%  |
| 1 x Nvidia     | 42        | 17.95%  |
| Intel + Nvidia | 38        | 16.24%  |
| 1 x AMD        | 30        | 12.82%  |
| Intel + AMD    | 14        | 5.98%   |
| AMD + Nvidia   | 4         | 1.71%   |
| 1 x Matrox     | 2         | 0.85%   |
| 2 x AMD        | 1         | 0.43%   |
| 1 x VIA        | 1         | 0.43%   |
| 1 x SiS        | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 186       | 77.5%   |
| Proprietary | 50        | 20.83%  |
| Unknown     | 4         | 1.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 144       | 59.75%  |
| 1.01-2.0   | 36        | 14.94%  |
| 3.01-4.0   | 17        | 7.05%   |
| 7.01-8.0   | 14        | 5.81%   |
| 0.51-1.0   | 11        | 4.56%   |
| 0.01-0.5   | 10        | 4.15%   |
| 2.01-3.0   | 5         | 2.07%   |
| 8.01-16.0  | 3         | 1.24%   |
| 5.01-6.0   | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 42        | 17%     |
| LG Display           | 27        | 10.93%  |
| Dell                 | 23        | 9.31%   |
| Samsung Electronics  | 22        | 8.91%   |
| Chimei Innolux       | 21        | 8.5%    |
| AU Optronics         | 20        | 8.1%    |
| BenQ                 | 11        | 4.45%   |
| Lenovo               | 8         | 3.24%   |
| Goldstar             | 8         | 3.24%   |
| Sharp                | 7         | 2.83%   |
| Unknown              | 6         | 2.43%   |
| Hewlett-Packard      | 5         | 2.02%   |
| Sony                 | 4         | 1.62%   |
| InfoVision           | 4         | 1.62%   |
| Apple                | 4         | 1.62%   |
| Acer                 | 4         | 1.62%   |
| PANDA                | 3         | 1.21%   |
| Ancor Communications | 3         | 1.21%   |
| ViewSonic            | 2         | 0.81%   |
| TCL                  | 2         | 0.81%   |
| SKY                  | 2         | 0.81%   |
| ASUSTek Computer     | 2         | 0.81%   |
| AOC                  | 2         | 0.81%   |
| ___                  | 1         | 0.4%    |
| Tech Concepts        | 1         | 0.4%    |
| Sun                  | 1         | 0.4%    |
| SHC                  | 1         | 0.4%    |
| RTK                  | 1         | 0.4%    |
| RGT                  | 1         | 0.4%    |
| Philips              | 1         | 0.4%    |
| LG Electronics       | 1         | 0.4%    |
| Lenovo Group Limited | 1         | 0.4%    |
| Konka                | 1         | 0.4%    |
| InnoLux Display      | 1         | 0.4%    |
| Gigabyte Technology  | 1         | 0.4%    |
| GDH                  | 1         | 0.4%    |
| eMachines            | 1         | 0.4%    |
| AGO                  | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 4         | 1.55%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch                | 3         | 1.16%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                       | 3         | 1.16%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                   | 3         | 1.16%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 3         | 1.16%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 1.16%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                     | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 410x230mm 18.5-inch   | 2         | 0.78%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch            | 2         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 0.78%   |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch                | 2         | 0.78%   |
| Dell U2413 DELF047 1920x1200 518x324mm 24.1-inch                        | 2         | 0.78%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                   | 2         | 0.78%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                       | 2         | 0.78%   |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1517 1920x1080 344x193mm 15.5-inch        | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.78%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                   | 2         | 0.78%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                   | 2         | 0.78%   |
| BOE LCD Monitor BOE06DC 1920x1280 259x173mm 12.3-inch                   | 2         | 0.78%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch           | 2         | 0.78%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch        | 2         | 0.78%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1         | 0.39%   |
| ViewSonic VX2253 Series VSC0A28 1920x1080 476x268mm 21.5-inch           | 1         | 0.39%   |
| ViewSonic VA712-2SERIES VSC941C 1280x1024 338x270mm 17.0-inch           | 1         | 0.39%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                    | 1         | 0.39%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                        | 1         | 0.39%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.39%   |
| Unknown LCD Monitor SCEI MONITOR 1920x1080                              | 1         | 0.39%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1         | 0.39%   |
| Unknown LCD Monitor AAA HDTV 1366x768                                   | 1         | 0.39%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                        | 1         | 0.39%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 101       | 42.62%  |
| 1366x768 (WXGA)    | 73        | 30.8%   |
| 3840x2160 (4K)     | 19        | 8.02%   |
| 2560x1440 (QHD)    | 10        | 4.22%   |
| 1920x1200 (WUXGA)  | 4         | 1.69%   |
| 1440x900 (WXGA+)   | 4         | 1.69%   |
| 1280x1024 (SXGA)   | 3         | 1.27%   |
| 3440x1440          | 2         | 0.84%   |
| 2736x1824          | 2         | 0.84%   |
| 2560x1080          | 2         | 0.84%   |
| 1920x1280          | 2         | 0.84%   |
| 1360x768           | 2         | 0.84%   |
| Unknown            | 2         | 0.84%   |
| 7040x1440          | 1         | 0.42%   |
| 3840x2400          | 1         | 0.42%   |
| 3840x1600          | 1         | 0.42%   |
| 3840x1080          | 1         | 0.42%   |
| 2880x1800          | 1         | 0.42%   |
| 2560x1600          | 1         | 0.42%   |
| 2256x1504          | 1         | 0.42%   |
| 2160x1440          | 1         | 0.42%   |
| 1680x1050 (WSXGA+) | 1         | 0.42%   |
| 1600x900 (HD+)     | 1         | 0.42%   |
| 1280x800 (WXGA)    | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 77        | 30.8%   |
| 13      | 26        | 10.4%   |
| 24      | 19        | 7.6%    |
| 14      | 19        | 7.6%    |
| 27      | 18        | 7.2%    |
| 23      | 13        | 5.2%    |
| Unknown | 11        | 4.4%    |
| 12      | 8         | 3.2%    |
| 21      | 7         | 2.8%    |
| 18      | 7         | 2.8%    |
| 54      | 6         | 2.4%    |
| 31      | 6         | 2.4%    |
| 17      | 6         | 2.4%    |
| 34      | 4         | 1.6%    |
| 72      | 3         | 1.2%    |
| 32      | 3         | 1.2%    |
| 84      | 2         | 0.8%    |
| 52      | 2         | 0.8%    |
| 40      | 2         | 0.8%    |
| 22      | 2         | 0.8%    |
| 19      | 2         | 0.8%    |
| 16      | 2         | 0.8%    |
| 65      | 1         | 0.4%    |
| 57      | 1         | 0.4%    |
| 37      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| 11      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 47.54%  |
| 501-600     | 44        | 18.03%  |
| 401-500     | 18        | 7.38%   |
| 201-300     | 17        | 6.97%   |
| Unknown     | 11        | 4.51%   |
| 1001-1500   | 10        | 4.1%    |
| 601-700     | 8         | 3.28%   |
| 701-800     | 7         | 2.87%   |
| 351-400     | 5         | 2.05%   |
| 1501-2000   | 5         | 2.05%   |
| 801-900     | 3         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 187       | 83.11%  |
| 16/10   | 13        | 5.78%   |
| Unknown | 10        | 4.44%   |
| 3/2     | 6         | 2.67%   |
| 21/9    | 5         | 2.22%   |
| 5/4     | 3         | 1.33%   |
| 4/3     | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 76        | 30.77%  |
| 81-90          | 39        | 15.79%  |
| 201-250        | 33        | 13.36%  |
| 301-350        | 18        | 7.29%   |
| More than 1000 | 15        | 6.07%   |
| 351-500        | 13        | 5.26%   |
| Unknown        | 11        | 4.45%   |
| 141-150        | 10        | 4.05%   |
| 71-80          | 7         | 2.83%   |
| 61-70          | 6         | 2.43%   |
| 251-300        | 6         | 2.43%   |
| 151-200        | 3         | 1.21%   |
| 501-1000       | 3         | 1.21%   |
| 121-130        | 2         | 0.81%   |
| 111-120        | 2         | 0.81%   |
| 51-60          | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 77        | 32.08%  |
| 51-100        | 68        | 28.33%  |
| 121-160       | 59        | 24.58%  |
| 1-50          | 11        | 4.58%   |
| Unknown       | 11        | 4.58%   |
| 161-240       | 10        | 4.17%   |
| More than 240 | 4         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 199       | 83.26%  |
| 2     | 26        | 10.88%  |
| 0     | 7         | 2.93%   |
| 3     | 6         | 2.51%   |
| 4     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 126       | 34.62%  |
| Intel                            | 105       | 28.85%  |
| Qualcomm Atheros                 | 52        | 14.29%  |
| Broadcom                         | 24        | 6.59%   |
| Samsung Electronics              | 7         | 1.92%   |
| Ralink Technology                | 7         | 1.92%   |
| Ralink                           | 6         | 1.65%   |
| MediaTek                         | 4         | 1.1%    |
| TP-Link                          | 3         | 0.82%   |
| Microsoft                        | 3         | 0.82%   |
| Marvell Technology Group         | 3         | 0.82%   |
| Dell                             | 3         | 0.82%   |
| Linksys                          | 2         | 0.55%   |
| D-Link                           | 2         | 0.55%   |
| Apple                            | 2         | 0.55%   |
| Xiaomi                           | 1         | 0.27%   |
| Wilocity                         | 1         | 0.27%   |
| VIA Technologies                 | 1         | 0.27%   |
| T & A Mobile Phones              | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Qualcomm                         | 1         | 0.27%   |
| OPPO Electronics                 | 1         | 0.27%   |
| Nvidia                           | 1         | 0.27%   |
| ICS Advent                       | 1         | 0.27%   |
| Huawei Technologies              | 1         | 0.27%   |
| Edimax Technology                | 1         | 0.27%   |
| DisplayLink                      | 1         | 0.27%   |
| Broadcom Limited                 | 1         | 0.27%   |
| Belkin Components                | 1         | 0.27%   |
| ASIX Electronics                 | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 18.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 3.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.44%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5         | 1.2%    |
| Intel Wireless 8260                                               | 5         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.2%    |
| Intel Wireless 3165                                               | 4         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.72%   |
| Intel Wireless-AC 9260                                            | 3         | 0.72%   |
| Intel Wireless 7265                                               | 3         | 0.72%   |
| Intel Wireless 7260                                               | 3         | 0.72%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.72%   |
| Dell Wireless 5570e HSPA+ (42Mbps) Mobile Broadband Card          | 3         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.48%   |
| Realtek RTL8187 Wireless Adapter                                  | 2         | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 36.1%   |
| Qualcomm Atheros      | 46        | 22.44%  |
| Realtek Semiconductor | 38        | 18.54%  |
| Broadcom              | 14        | 6.83%   |
| Ralink Technology     | 7         | 3.41%   |
| Ralink                | 6         | 2.93%   |
| MediaTek              | 4         | 1.95%   |
| TP-Link               | 3         | 1.46%   |
| Dell                  | 3         | 1.46%   |
| Linksys               | 2         | 0.98%   |
| D-Link                | 2         | 0.98%   |
| Wilocity              | 1         | 0.49%   |
| Qualcomm              | 1         | 0.49%   |
| Microsoft             | 1         | 0.49%   |
| Edimax Technology     | 1         | 0.49%   |
| Broadcom Limited      | 1         | 0.49%   |
| Belkin Components     | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 6.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 6.34%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 5.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.9%    |
| Intel Wireless 8265 / 8275                                     | 8         | 3.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5         | 2.44%   |
| Intel Wireless 8260                                            | 5         | 2.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.44%   |
| Intel Wireless 3165                                            | 4         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.46%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 1.46%   |
| Intel Wireless-AC 9260                                         | 3         | 1.46%   |
| Intel Wireless 7265                                            | 3         | 1.46%   |
| Intel Wireless 7260                                            | 3         | 1.46%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.46%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 1.46%   |
| Dell Wireless 5570e HSPA+ (42Mbps) Mobile Broadband Card       | 3         | 1.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.98%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.98%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 0.98%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 110       | 53.4%   |
| Intel                            | 51        | 24.76%  |
| Broadcom                         | 13        | 6.31%   |
| Qualcomm Atheros                 | 8         | 3.88%   |
| Samsung Electronics              | 7         | 3.4%    |
| Marvell Technology Group         | 3         | 1.46%   |
| Microsoft                        | 2         | 0.97%   |
| Apple                            | 2         | 0.97%   |
| Xiaomi                           | 1         | 0.49%   |
| VIA Technologies                 | 1         | 0.49%   |
| T & A Mobile Phones              | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| OPPO Electronics                 | 1         | 0.49%   |
| Nvidia                           | 1         | 0.49%   |
| ICS Advent                       | 1         | 0.49%   |
| Huawei Technologies              | 1         | 0.49%   |
| DisplayLink                      | 1         | 0.49%   |
| ASIX Electronics                 | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 76        | 36.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 26        | 12.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 4.29%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 7         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.86%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.86%   |
| Intel Ethernet Connection (7) I219-V                                           | 5         | 2.38%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 2.38%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.95%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.95%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.95%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.95%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.95%   |
| Intel 82583V Gigabit Network Connection                                        | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.95%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 0.95%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.95%   |
| Apple iPad 4/Mini1                                                             | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.48%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                                | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.48%   |
| OPPO RMX3263                                                                   | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.48%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.48%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.48%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 50.13%  |
| Ethernet | 189       | 49.61%  |
| Modem    | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 60.42%  |
| Ethernet | 95        | 39.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 128       | 54.94%  |
| 1     | 99        | 42.49%  |
| 4     | 2         | 0.86%   |
| 3     | 2         | 0.86%   |
| 0     | 2         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 183       | 75.93%  |
| Yes  | 58        | 24.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 39.38%  |
| Qualcomm Atheros Communications | 20        | 12.5%   |
| Realtek Semiconductor           | 18        | 11.25%  |
| Cambridge Silicon Radio         | 13        | 8.13%   |
| IMC Networks                    | 10        | 6.25%   |
| Foxconn / Hon Hai               | 10        | 6.25%   |
| Lite-On Technology              | 5         | 3.13%   |
| Broadcom                        | 5         | 3.13%   |
| Toshiba                         | 3         | 1.88%   |
| Ralink                          | 3         | 1.88%   |
| Apple                           | 3         | 1.88%   |
| Dell                            | 2         | 1.25%   |
| TP-Link                         | 1         | 0.63%   |
| Realtek                         | 1         | 0.63%   |
| Qcom                            | 1         | 0.63%   |
| MediaTek                        | 1         | 0.63%   |
| ASUSTek Computer                | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 14.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 8.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 8.13%   |
| Realtek Bluetooth Radio                                                             | 11        | 6.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 6.88%   |
| Intel AX201 Bluetooth                                                               | 10        | 6.25%   |
| Intel AX200 Bluetooth                                                               | 10        | 6.25%   |
| IMC Networks Bluetooth Device                                                       | 7         | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 3.75%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.88%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.88%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.88%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 1.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.25%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.25%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.25%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.25%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.63%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.63%   |
| Toshiba Askey for                                                                   | 1         | 0.63%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.63%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.63%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.63%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.63%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.63%   |
| MediaTek Wireless_Device                                                            | 1         | 0.63%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.63%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.63%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.63%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.63%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.63%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 192       | 59.63%  |
| Nvidia                           | 60        | 18.63%  |
| AMD                              | 45        | 13.98%  |
| C-Media Electronics              | 8         | 2.48%   |
| Creative Labs                    | 3         | 0.93%   |
| Cooler Master                    | 2         | 0.62%   |
| VIA Technologies                 | 1         | 0.31%   |
| Texas Instruments                | 1         | 0.31%   |
| Tenx Technology                  | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Samson Technologies              | 1         | 0.31%   |
| Plantronics                      | 1         | 0.31%   |
| Microsoft                        | 1         | 0.31%   |
| KTMicro                          | 1         | 0.31%   |
| Kingston Technology              | 1         | 0.31%   |
| JMTek                            | 1         | 0.31%   |
| Creative Technology              | 1         | 0.31%   |
| Corsair                          | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 27        | 7.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 5.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 4.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 3.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 2.97%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 2.97%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 2.43%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 2.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 1.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4         | 1.08%   |
| C-Media Electronics CM108 Audio Controller                                 | 4         | 1.08%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.81%   |
| Nvidia GM206 High Definition Audio Controller                              | 3         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.81%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 0.81%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 27        | 21.09%  |
| SK hynix                             | 23        | 17.97%  |
| Micron Technology                    | 19        | 14.84%  |
| Kingston                             | 14        | 10.94%  |
| Unknown                              | 11        | 8.59%   |
| Crucial                              | 8         | 6.25%   |
| G.Skill                              | 6         | 4.69%   |
| Team                                 | 3         | 2.34%   |
| Elpida                               | 3         | 2.34%   |
| Hikvision                            | 2         | 1.56%   |
| Unknown (ABCD)                       | 1         | 0.78%   |
| Toshiba                              | 1         | 0.78%   |
| Silicon Power                        | 1         | 0.78%   |
| Ramaxel Technology                   | 1         | 0.78%   |
| Patriot Memory (PDP Systems)         | 1         | 0.78%   |
| Nanya Technology                     | 1         | 0.78%   |
| Lexar Co Limited                     | 1         | 0.78%   |
| KLEVV                                | 1         | 0.78%   |
| Corsair                              | 1         | 0.78%   |
| Chun Well Technology Holding Limited | 1         | 0.78%   |
| ASint Technology                     | 1         | 0.78%   |
| A-DATA Technology                    | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.96%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 3         | 2.22%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s               | 2         | 1.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.48%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 1.48%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 2         | 1.48%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.48%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s        | 2         | 1.48%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.74%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.74%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.74%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 0.74%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s           | 1         | 0.74%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.74%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT112S6TFR8C-G7 1GB SODIMM DDR3 1067MT/s           | 1         | 0.74%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851U6DJR6N-XN 4096MB DIMM DDR4 3200MT/s          | 1         | 0.74%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.74%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 49        | 47.57%  |
| DDR3    | 37        | 35.92%  |
| LPDDR4  | 6         | 5.83%   |
| DDR2    | 4         | 3.88%   |
| Unknown | 3         | 2.91%   |
| SDRAM   | 2         | 1.94%   |
| LPDDR3  | 2         | 1.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 59.41%  |
| DIMM         | 34        | 33.66%  |
| Row Of Chips | 7         | 6.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 38        | 33.93%  |
| 4096  | 38        | 33.93%  |
| 16384 | 16        | 14.29%  |
| 2048  | 13        | 11.61%  |
| 1024  | 4         | 3.57%   |
| 32768 | 3         | 2.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 19        | 16.1%   |
| 1600    | 19        | 16.1%   |
| 2667    | 18        | 15.25%  |
| 1333    | 10        | 8.47%   |
| 2400    | 8         | 6.78%   |
| 2133    | 8         | 6.78%   |
| 1334    | 6         | 5.08%   |
| 3266    | 4         | 3.39%   |
| 1067    | 3         | 2.54%   |
| 800     | 3         | 2.54%   |
| 4267    | 2         | 1.69%   |
| 3733    | 2         | 1.69%   |
| 3600    | 2         | 1.69%   |
| 1867    | 2         | 1.69%   |
| 1866    | 2         | 1.69%   |
| 1800    | 2         | 1.69%   |
| 4199    | 1         | 0.85%   |
| 3866    | 1         | 0.85%   |
| 3466    | 1         | 0.85%   |
| 1648    | 1         | 0.85%   |
| 1066    | 1         | 0.85%   |
| 975     | 1         | 0.85%   |
| 667     | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 6         | 66.67%  |
| Brother Industries     | 2         | 22.22%  |
| Panasonic (Matsushita) | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Brother HL-2130 series             | 2         | 20%     |
| Panasonic (Matsushita) KX-MB1500RU | 1         | 10%     |
| HP LaserJet P2055 series           | 1         | 10%     |
| HP LaserJet P2015 series           | 1         | 10%     |
| HP LaserJet M101-M106              | 1         | 10%     |
| HP LaserJet CP 1025                | 1         | 10%     |
| HP DeskJet Plus 4100 series        | 1         | 10%     |
| HP DeskJet 2700 series             | 1         | 10%     |
| HP DeskJet 2130 series             | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 500F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 19.23%  |
| IMC Networks                           | 20        | 15.38%  |
| Microdia                               | 13        | 10%     |
| Realtek Semiconductor                  | 9         | 6.92%   |
| Acer                                   | 9         | 6.92%   |
| Lite-On Technology                     | 7         | 5.38%   |
| Apple                                  | 7         | 5.38%   |
| Suyin                                  | 6         | 4.62%   |
| Sunplus Innovation Technology          | 6         | 4.62%   |
| Quanta                                 | 4         | 3.08%   |
| Samsung Electronics                    | 3         | 2.31%   |
| Microsoft                              | 3         | 2.31%   |
| Importek                               | 3         | 2.31%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.31%   |
| Syntek                                 | 2         | 1.54%   |
| Ricoh                                  | 2         | 1.54%   |
| ARC International                      | 2         | 1.54%   |
| Alcor Micro                            | 2         | 1.54%   |
| Silicon Motion                         | 1         | 0.77%   |
| Logitech                               | 1         | 0.77%   |
| Lenovo                                 | 1         | 0.77%   |
| Arkmicro Technologies                  | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 9.23%   |
| Chicony Integrated Camera                           | 8         | 6.15%   |
| Microdia Integrated_Webcam_HD                       | 7         | 5.38%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 3.85%   |
| Apple iPhone5/5C/5S/6                               | 4         | 3.08%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.31%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 2.31%   |
| Lite-On HP TrueVision HD Camera                     | 3         | 2.31%   |
| Chicony HD WebCam                                   | 3         | 2.31%   |
| Acer Integrated Camera                              | 3         | 2.31%   |
| Sunplus HD WebCam                                   | 2         | 1.54%   |
| Realtek Integrated Webcam HD                        | 2         | 1.54%   |
| Realtek Integrated Webcam                           | 2         | 1.54%   |
| Realtek HP Truevision HD integrated webcam          | 2         | 1.54%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.54%   |
| Microdia USB 2.0 Camera                             | 2         | 1.54%   |
| Chicony Front Camera                                | 2         | 1.54%   |
| ARC International Camera                            | 2         | 1.54%   |
| Alcor Micro Asus Integrated Webcam                  | 2         | 1.54%   |
| Syntek Integrated Camera                            | 1         | 0.77%   |
| Syntek EasyCamera                                   | 1         | 0.77%   |
| Suyin USB 2.0 Camera                                | 1         | 0.77%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.77%   |
| Suyin HP TrueVision HD                              | 1         | 0.77%   |
| Suyin HP Integrated Webcam                          | 1         | 0.77%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.77%   |
| Suyin 1.3M Front                                    | 1         | 0.77%   |
| Sunplus Feeltek Full HD Webcam 1080P                | 1         | 0.77%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.77%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 1         | 0.77%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.77%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.77%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.77%   |
| Realtek HP Truevision HD                            | 1         | 0.77%   |
| Quanta LG Webcam                                    | 1         | 0.77%   |
| Quanta FHD Camera                                   | 1         | 0.77%   |
| Microsoft MicrosoftÂ LifeCam Cinema                | 1         | 0.77%   |
| Microsoft LifeCam HD-5000                           | 1         | 0.77%   |
| Microsoft LifeCam Cinema                            | 1         | 0.77%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 42.11%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Elan Microelectronics      | 3         | 15.79%  |
| Upek                       | 2         | 10.53%  |
| LighTuning Technology      | 2         | 10.53%  |
| Validity Sensors           | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics  WBDI                                        | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 10.53%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 10.53%  |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 10.53%  |
| Elan ELAN:Fingerprint                                  | 2         | 10.53%  |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 5.26%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.26%   |
| Shenzhen Goodix FingerPrint                            | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.26%   |
| Unknown                                                | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 75%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 50%     |
| Broadcom 5880                                                                | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 171       | 71.55%  |
| 1     | 56        | 23.43%  |
| 2     | 9         | 3.77%   |
| 3     | 2         | 0.84%   |
| 4     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 24.36%  |
| Net/wireless             | 17        | 21.79%  |
| Graphics card            | 16        | 20.51%  |
| Multimedia controller    | 6         | 7.69%   |
| Communication controller | 6         | 7.69%   |
| Chipcard                 | 4         | 5.13%   |
| Unassigned class         | 3         | 3.85%   |
| Bluetooth                | 3         | 3.85%   |
| Camera                   | 2         | 2.56%   |
| Storage/raid             | 1         | 1.28%   |
| Modem                    | 1         | 1.28%   |


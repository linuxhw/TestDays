Ubuntu Budgie 22.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_22.04/Notebook/README.md).

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

Total: 200

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite A300              | Notebook    | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [a293b54992](https://linux-hardware.org/?probe=a293b54992) | Nov 24, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [c172f735d2](https://linux-hardware.org/?probe=c172f735d2) | Nov 15, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [5efa262121](https://linux-hardware.org/?probe=5efa262121) | Nov 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [143fa66e87](https://linux-hardware.org/?probe=143fa66e87) | Nov 08, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [c6d6619fd9](https://linux-hardware.org/?probe=c6d6619fd9) | Nov 06, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [b3a6489f94](https://linux-hardware.org/?probe=b3a6489f94) | Oct 20, 2023 |
| HP            | 8054                        | Desktop     | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [921d699e5d](https://linux-hardware.org/?probe=921d699e5d) | Aug 19, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e31d121593](https://linux-hardware.org/?probe=e31d121593) | Jul 15, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9c3135decf](https://linux-hardware.org/?probe=9c3135decf) | Jul 10, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | Desktop     | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | Notebook    | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | Notebook    | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | Notebook    | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Intel         | H61                         | Desktop     | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [de3f21b51b](https://linux-hardware.org/?probe=de3f21b51b) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [329e7b7105](https://linux-hardware.org/?probe=329e7b7105) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0c8a9895bd](https://linux-hardware.org/?probe=0c8a9895bd) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [b3bc8de731](https://linux-hardware.org/?probe=b3bc8de731) | Jan 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a5e1965b89](https://linux-hardware.org/?probe=a5e1965b89) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell          | 0RW199                      | Desktop     | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-27-generic    | 11        | 6.88%   |
| 5.15.0-52-generic    | 9         | 5.63%   |
| 5.15.0-50-generic    | 7         | 4.38%   |
| 5.15.0-48-generic    | 6         | 3.75%   |
| 5.15.0-30-generic    | 6         | 3.75%   |
| 5.19.0-46-generic    | 5         | 3.13%   |
| 5.15.0-46-generic    | 5         | 3.13%   |
| 5.15.0-43-generic    | 5         | 3.13%   |
| 5.15.0-39-generic    | 5         | 3.13%   |
| 6.2.0-26-generic     | 4         | 2.5%    |
| 5.19.0-35-generic    | 4         | 2.5%    |
| 5.15.0-57-generic    | 4         | 2.5%    |
| 5.15.0-56-generic    | 4         | 2.5%    |
| 5.15.0-33-generic    | 4         | 2.5%    |
| 5.15.0-25-generic    | 4         | 2.5%    |
| 6.2.0-33-generic     | 3         | 1.88%   |
| 5.19.0-45-generic    | 3         | 1.88%   |
| 5.19.0-41-generic    | 3         | 1.88%   |
| 5.19.0-40-generic    | 3         | 1.88%   |
| 5.15.0-58-generic    | 3         | 1.88%   |
| 5.15.0-53-generic    | 3         | 1.88%   |
| 5.15.0-47-generic    | 3         | 1.88%   |
| 5.15.0-40-generic    | 3         | 1.88%   |
| 6.2.0-32-generic     | 2         | 1.25%   |
| 6.2.0-10007-tuxedo   | 2         | 1.25%   |
| 5.19.0-42-generic    | 2         | 1.25%   |
| 5.19.0-38-generic    | 2         | 1.25%   |
| 5.15.0-67-generic    | 2         | 1.25%   |
| 5.15.0-41-generic    | 2         | 1.25%   |
| 6.5.0-10008-tuxedo   | 1         | 0.63%   |
| 6.3.1-060301-generic | 1         | 0.63%   |
| 6.2.0-39-generic     | 1         | 0.63%   |
| 6.2.0-37-generic     | 1         | 0.63%   |
| 6.2.0-36-generic     | 1         | 0.63%   |
| 6.2.0-35-generic     | 1         | 0.63%   |
| 6.2.0-34-generic     | 1         | 0.63%   |
| 6.2.0-10018-tuxedo   | 1         | 0.63%   |
| 6.1.0-060100-generic | 1         | 0.63%   |
| 5.19.0-50-generic    | 1         | 0.63%   |
| 5.19.0-32-generic    | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 101       | 67.33%  |
| 5.19.0  | 24        | 16%     |
| 6.2.0   | 16        | 10.67%  |
| 5.13.0  | 3         | 2%      |
| 6.5.0   | 1         | 0.67%   |
| 6.3.1   | 1         | 0.67%   |
| 6.1.0   | 1         | 0.67%   |
| 5.17.2  | 1         | 0.67%   |
| 5.16.2  | 1         | 0.67%   |
| 5.15.92 | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 102       | 68%     |
| 5.19    | 24        | 16%     |
| 6.2     | 16        | 10.67%  |
| 5.13    | 3         | 2%      |
| 6.5     | 1         | 0.67%   |
| 6.3     | 1         | 0.67%   |
| 6.1     | 1         | 0.67%   |
| 5.17    | 1         | 0.67%   |
| 5.16    | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 143       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 137       | 95.8%   |
| GNOME  | 5         | 3.5%    |
| KDE5   | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 139       | 97.2%   |
| Wayland | 4         | 2.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 101       | 70.63%  |
| Unknown | 27        | 18.88%  |
| GDM3    | 13        | 9.09%   |
| SDDM    | 1         | 0.7%    |
| GDM     | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 53        | 37.06%  |
| de_DE | 19        | 13.29%  |
| fr_FR | 13        | 9.09%   |
| pt_BR | 10        | 6.99%   |
| en_GB | 8         | 5.59%   |
| es_ES | 4         | 2.8%    |
| en_CA | 4         | 2.8%    |
| it_IT | 3         | 2.1%    |
| fr_BE | 3         | 2.1%    |
| en_AU | 3         | 2.1%    |
| ru_RU | 2         | 1.4%    |
| hu_HU | 2         | 1.4%    |
| es_MX | 2         | 1.4%    |
| es_AR | 2         | 1.4%    |
| en_IE | 2         | 1.4%    |
| pl_PL | 1         | 0.7%    |
| mt_MT | 1         | 0.7%    |
| ja_JP | 1         | 0.7%    |
| es_PE | 1         | 0.7%    |
| es_EC | 1         | 0.7%    |
| es_CL | 1         | 0.7%    |
| en_ZA | 1         | 0.7%    |
| en_SG | 1         | 0.7%    |
| en_NZ | 1         | 0.7%    |
| en_IL | 1         | 0.7%    |
| el_GR | 1         | 0.7%    |
| cs_CZ | 1         | 0.7%    |
| C     | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 86        | 59.72%  |
| EFI  | 58        | 40.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 123       | 84.25%  |
| Tmpfs   | 9         | 6.16%   |
| Overlay | 6         | 4.11%   |
| Zfs     | 4         | 2.74%   |
| Btrfs   | 3         | 2.05%   |
| Xfs     | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 92        | 63.89%  |
| Unknown | 45        | 31.25%  |
| MBR     | 7         | 4.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 85.31%  |
| Yes       | 21        | 14.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 65.97%  |
| Yes       | 49        | 34.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 23        | 16.08%  |
| Hewlett-Packard        | 20        | 13.99%  |
| Dell                   | 17        | 11.89%  |
| ASUSTek Computer       | 17        | 11.89%  |
| Gigabyte Technology    | 10        | 6.99%   |
| TUXEDO                 | 9         | 6.29%   |
| MSI                    | 9         | 6.29%   |
| Apple                  | 8         | 5.59%   |
| Intel                  | 4         | 2.8%    |
| Fujitsu                | 3         | 2.1%    |
| ASRock                 | 3         | 2.1%    |
| Toshiba                | 2         | 1.4%    |
| Google                 | 2         | 1.4%    |
| AZW                    | 2         | 1.4%    |
| Acer                   | 2         | 1.4%    |
| Timi                   | 1         | 0.7%    |
| Semp Toshiba           | 1         | 0.7%    |
| Samsung Electronics    | 1         | 0.7%    |
| Razer                  | 1         | 0.7%    |
| HUAWEI                 | 1         | 0.7%    |
| Digibras               | 1         | 0.7%    |
| COM1                   | 1         | 0.7%    |
| Chuwi                  | 1         | 0.7%    |
| Biostar                | 1         | 0.7%    |
| BANGHO                 | 1         | 0.7%    |
| AXIOO                  | 1         | 0.7%    |
| Avell High Performance | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 1.4%    |
| Lenovo G50-45 80E3                                   | 2         | 1.4%    |
| HP EliteBook 840 G3                                  | 2         | 1.4%    |
| AZW SER                                              | 2         | 1.4%    |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.7%    |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.7%    |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 0.7%    |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.7%    |
| TUXEDO Book XP1511                                   | 1         | 0.7%    |
| TUXEDO Book BA1510                                   | 1         | 0.7%    |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.7%    |
| Toshiba Satellite A505                               | 1         | 0.7%    |
| Toshiba Satellite A300                               | 1         | 0.7%    |
| Timi TM1604                                          | 1         | 0.7%    |
| Semp Toshiba STI                                     | 1         | 0.7%    |
| Samsung 740U3M                                       | 1         | 0.7%    |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.7%    |
| MSI MS-7C95                                          | 1         | 0.7%    |
| MSI MS-7C51                                          | 1         | 0.7%    |
| MSI MS-7B86                                          | 1         | 0.7%    |
| MSI MS-7A32                                          | 1         | 0.7%    |
| MSI MS-7885                                          | 1         | 0.7%    |
| MSI MS-7721                                          | 1         | 0.7%    |
| MSI Modern 15 A10M                                   | 1         | 0.7%    |
| MSI GL62 6QF                                         | 1         | 0.7%    |
| MSI Alpha 15 B5EEK                                   | 1         | 0.7%    |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.7%    |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 0.7%    |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon 5th 20HR002SIV             | 1         | 0.7%    |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 0.7%    |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 0.7%    |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 0.7%    |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 0.7%    |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 0.7%    |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 0.7%    |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 0.7%    |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 0.7%    |
| Lenovo IdeaPadFlex 5 14ALC7 82R9                     | 1         | 0.7%    |
| Lenovo IdeaPad Z500 20202                            | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 9         | 6.29%   |
| Lenovo IdeaPad      | 7         | 4.9%    |
| Dell Latitude       | 5         | 3.5%    |
| Dell Inspiron       | 5         | 3.5%    |
| HP EliteBook        | 4         | 2.8%    |
| ASUS VivoBook       | 4         | 2.8%    |
| TUXEDO Book         | 3         | 2.1%    |
| HP ProBook          | 3         | 2.1%    |
| HP Pavilion         | 3         | 2.1%    |
| TUXEDO Pulse        | 2         | 1.4%    |
| TUXEDO InfinityBook | 2         | 1.4%    |
| Toshiba Satellite   | 2         | 1.4%    |
| Lenovo G50-45       | 2         | 1.4%    |
| HP EliteDesk        | 2         | 1.4%    |
| Fujitsu ESPRIMO     | 2         | 1.4%    |
| Dell XPS            | 2         | 1.4%    |
| Dell Precision      | 2         | 1.4%    |
| Dell OptiPlex       | 2         | 1.4%    |
| AZW SER             | 2         | 1.4%    |
| ASUS ROG            | 2         | 1.4%    |
| Acer Aspire         | 2         | 1.4%    |
| TUXEDO Polaris      | 1         | 0.7%    |
| TUXEDO Aura         | 1         | 0.7%    |
| Timi TM1604         | 1         | 0.7%    |
| Semp Toshiba STI    | 1         | 0.7%    |
| Samsung 740U3M      | 1         | 0.7%    |
| Razer Blade         | 1         | 0.7%    |
| MSI MS-7C95         | 1         | 0.7%    |
| MSI MS-7C51         | 1         | 0.7%    |
| MSI MS-7B86         | 1         | 0.7%    |
| MSI MS-7A32         | 1         | 0.7%    |
| MSI MS-7885         | 1         | 0.7%    |
| MSI MS-7721         | 1         | 0.7%    |
| MSI Modern          | 1         | 0.7%    |
| MSI GL62            | 1         | 0.7%    |
| MSI Alpha           | 1         | 0.7%    |
| Lenovo V15          | 1         | 0.7%    |
| Lenovo ThinkStation | 1         | 0.7%    |
| Lenovo Legion       | 1         | 0.7%    |
| Lenovo IdeaPadFlex  | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 20        | 13.99%  |
| 2020 | 18        | 12.59%  |
| 2014 | 15        | 10.49%  |
| 2018 | 12        | 8.39%   |
| 2016 | 12        | 8.39%   |
| 2019 | 10        | 6.99%   |
| 2022 | 9         | 6.29%   |
| 2017 | 8         | 5.59%   |
| 2015 | 8         | 5.59%   |
| 2011 | 6         | 4.2%    |
| 2010 | 6         | 4.2%    |
| 2013 | 5         | 3.5%    |
| 2012 | 5         | 3.5%    |
| 2009 | 4         | 2.8%    |
| 2008 | 4         | 2.8%    |
| 2023 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 89        | 62.24%  |
| Desktop     | 39        | 27.27%  |
| Convertible | 6         | 4.2%    |
| Mini pc     | 5         | 3.5%    |
| All in one  | 3         | 2.1%    |
| Tablet      | 1         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 136       | 95.1%   |
| Enabled  | 7         | 4.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 140       | 97.9%   |
| Yes  | 3         | 2.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 40        | 27.78%  |
| 16.01-24.0      | 39        | 27.08%  |
| 8.01-16.0       | 26        | 18.06%  |
| 3.01-4.0        | 14        | 9.72%   |
| 32.01-64.0      | 12        | 8.33%   |
| 64.01-256.0     | 6         | 4.17%   |
| 24.01-32.0      | 4         | 2.78%   |
| 1.01-2.0        | 2         | 1.39%   |
| More than 256.0 | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 51        | 33.33%  |
| 1.01-2.0   | 40        | 26.14%  |
| 4.01-8.0   | 27        | 17.65%  |
| 3.01-4.0   | 19        | 12.42%  |
| 8.01-16.0  | 11        | 7.19%   |
| 16.01-24.0 | 3         | 1.96%   |
| 24.01-32.0 | 2         | 1.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 60.96%  |
| 2      | 39        | 26.71%  |
| 3      | 9         | 6.16%   |
| 4      | 5         | 3.42%   |
| 6      | 2         | 1.37%   |
| 8      | 1         | 0.68%   |
| 7      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 74.13%  |
| Yes       | 37        | 25.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 80.56%  |
| No        | 28        | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 84.62%  |
| No        | 22        | 15.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 70.63%  |
| No        | 42        | 29.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 27        | 18.88%  |
| Germany            | 21        | 14.69%  |
| France             | 14        | 9.79%   |
| Brazil             | 12        | 8.39%   |
| UK                 | 5         | 3.5%    |
| Spain              | 3         | 2.1%    |
| Poland             | 3         | 2.1%    |
| Italy              | 3         | 2.1%    |
| Canada             | 3         | 2.1%    |
| Belgium            | 3         | 2.1%    |
| Austria            | 3         | 2.1%    |
| Australia          | 3         | 2.1%    |
| Argentina          | 3         | 2.1%    |
| Switzerland        | 2         | 1.4%    |
| Slovenia           | 2         | 1.4%    |
| Romania            | 2         | 1.4%    |
| Peru               | 2         | 1.4%    |
| Netherlands        | 2         | 1.4%    |
| Mexico             | 2         | 1.4%    |
| Ireland            | 2         | 1.4%    |
| Hungary            | 2         | 1.4%    |
| Greece             | 2         | 1.4%    |
| Sweden             | 1         | 0.7%    |
| South Africa       | 1         | 0.7%    |
| Singapore          | 1         | 0.7%    |
| Saudi Arabia       | 1         | 0.7%    |
| Russia             | 1         | 0.7%    |
| Norway             | 1         | 0.7%    |
| New Zealand        | 1         | 0.7%    |
| Malta              | 1         | 0.7%    |
| Japan              | 1         | 0.7%    |
| Israel             | 1         | 0.7%    |
| Indonesia          | 1         | 0.7%    |
| Ghana              | 1         | 0.7%    |
| Ecuador            | 1         | 0.7%    |
| Dominican Republic | 1         | 0.7%    |
| Czechia            | 1         | 0.7%    |
| Cuba               | 1         | 0.7%    |
| Croatia            | 1         | 0.7%    |
| Chile              | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Brasília             | 4         | 2.7%    |
| Berlin                | 4         | 2.7%    |
| Warsaw                | 2         | 1.35%   |
| Vienna                | 2         | 1.35%   |
| Victoria              | 2         | 1.35%   |
| Nuremberg             | 2         | 1.35%   |
| Milwaukee             | 2         | 1.35%   |
| London                | 2         | 1.35%   |
| Frankfurt am Main     | 2         | 1.35%   |
| Dublin                | 2         | 1.35%   |
| Budapest              | 2         | 1.35%   |
| Athens                | 2         | 1.35%   |
| Zurich                | 1         | 0.68%   |
| West Lafayette        | 1         | 0.68%   |
| Wertheim am Main      | 1         | 0.68%   |
| Weisswasser           | 1         | 0.68%   |
| Weilheim              | 1         | 0.68%   |
| Washington            | 1         | 0.68%   |
| Walled Lake           | 1         | 0.68%   |
| Venray                | 1         | 0.68%   |
| Trondheim             | 1         | 0.68%   |
| Torun                 | 1         | 0.68%   |
| Tocantins             | 1         | 0.68%   |
| Targu Frumos          | 1         | 0.68%   |
| Tarakan               | 1         | 0.68%   |
| Tann                  | 1         | 0.68%   |
| Tampa                 | 1         | 0.68%   |
| Sunnyvale             | 1         | 0.68%   |
| St Petersburg         | 1         | 0.68%   |
| Sofia                 | 1         | 0.68%   |
| Singapore             | 1         | 0.68%   |
| Siegen                | 1         | 0.68%   |
| Shirakuni             | 1         | 0.68%   |
| Sétif                | 1         | 0.68%   |
| Seelze                | 1         | 0.68%   |
| Seattle               | 1         | 0.68%   |
| Sao Paulo             | 1         | 0.68%   |
| Sao Bernardo do Campo | 1         | 0.68%   |
| Santo Domingo Este    | 1         | 0.68%   |
| Santiago              | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 38        | 64     | 17.92%  |
| Seagate                        | 22        | 30     | 10.38%  |
| WDC                            | 18        | 20     | 8.49%   |
| Unknown                        | 15        | 15     | 7.08%   |
| Crucial                        | 14        | 19     | 6.6%    |
| Toshiba                        | 13        | 16     | 6.13%   |
| Micron Technology              | 10        | 10     | 4.72%   |
| SK hynix                       | 8         | 8      | 3.77%   |
| SanDisk                        | 8         | 9      | 3.77%   |
| Kingston                       | 6         | 7      | 2.83%   |
| Intel                          | 6         | 8      | 2.83%   |
| SPCC                           | 4         | 5      | 1.89%   |
| China                          | 4         | 5      | 1.89%   |
| A-DATA Technology              | 4         | 5      | 1.89%   |
| OCZ                            | 3         | 3      | 1.42%   |
| JMicron Technology             | 3         | 3      | 1.42%   |
| Apple                          | 3         | 3      | 1.42%   |
| Transcend                      | 2         | 2      | 0.94%   |
| PNY                            | 2         | 2      | 0.94%   |
| Phison                         | 2         | 2      | 0.94%   |
| HGST                           | 2         | 2      | 0.94%   |
| Zheino                         | 1         | 1      | 0.47%   |
| YMTC                           | 1         | 1      | 0.47%   |
| VISIPRO                        | 1         | 1      | 0.47%   |
| Union Memory                   | 1         | 1      | 0.47%   |
| TO Exter                       | 1         | 1      | 0.47%   |
| Solid State Storage Technology | 1         | 1      | 0.47%   |
| SABRENT                        | 1         | 1      | 0.47%   |
| Realtek Semiconductor          | 1         | 1      | 0.47%   |
| Phison Electronics             | 1         | 1      | 0.47%   |
| OWC                            | 1         | 1      | 0.47%   |
| Netac                          | 1         | 1      | 0.47%   |
| Mushkin                        | 1         | 1      | 0.47%   |
| Micron/Crucial Technology      | 1         | 1      | 0.47%   |
| MicroFrom                      | 1         | 1      | 0.47%   |
| Maxtor                         | 1         | 1      | 0.47%   |
| LITEON                         | 1         | 1      | 0.47%   |
| KIOXIA                         | 1         | 1      | 0.47%   |
| Kingston Technology Company    | 1         | 1      | 0.47%   |
| Intenso                        | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 1.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.3%    |
| Crucial CT480BX500SSD1 480GB                        | 3         | 1.3%    |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.87%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.87%   |
| Unknown SD64G  64GB                                 | 2         | 0.87%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.87%   |
| Unknown MMC Card  64GB                              | 2         | 0.87%   |
| Unknown MMC Card  128GB                             | 2         | 0.87%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.87%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2         | 0.87%   |
| SanDisk SDSSDA120G 120GB                            | 2         | 0.87%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 0.87%   |
| Samsung SSD 980 500GB                               | 2         | 0.87%   |
| Samsung SSD 870 EVO 250GB                           | 2         | 0.87%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 0.87%   |
| Samsung SSD 850 PRO 256GB                           | 2         | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.87%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.87%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 2         | 0.87%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 0.87%   |
| JMicron Generic 250GB                               | 2         | 0.87%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.87%   |
| Zheino CHN-25SATAC3-120 120GB SSD                   | 1         | 0.43%   |
| YMTC PC005 1TB                                      | 1         | 0.43%   |
| WDC WD40PURZ-85TTDY0 4TB                            | 1         | 0.43%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 1         | 0.43%   |
| WDC WD3200LPVX-22V0TT0 320GB                        | 1         | 0.43%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 0.43%   |
| WDC WD1600AAJS-60WAA0 160GB                         | 1         | 0.43%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 0.43%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1         | 0.43%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 0.43%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 1         | 0.43%   |
| WDC WD Green 2.5 240GB SSD                          | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 29     | 40.74%  |
| WDC                 | 13        | 14     | 24.07%  |
| Toshiba             | 8         | 8      | 14.81%  |
| Samsung Electronics | 3         | 4      | 5.56%   |
| Unknown             | 2         | 2      | 3.7%    |
| HGST                | 2         | 2      | 3.7%    |
| TO Exter            | 1         | 1      | 1.85%   |
| Maxtor              | 1         | 1      | 1.85%   |
| ASMT109x            | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 34     | 19.48%  |
| Crucial             | 13        | 18     | 16.88%  |
| SanDisk             | 5         | 5      | 6.49%   |
| Micron Technology   | 4         | 4      | 5.19%   |
| China               | 4         | 5      | 5.19%   |
| WDC                 | 3         | 3      | 3.9%    |
| SPCC                | 3         | 4      | 3.9%    |
| Kingston            | 3         | 4      | 3.9%    |
| SK hynix            | 2         | 2      | 2.6%    |
| PNY                 | 2         | 2      | 2.6%    |
| OCZ                 | 2         | 2      | 2.6%    |
| JMicron Technology  | 2         | 2      | 2.6%    |
| Apple               | 2         | 2      | 2.6%    |
| A-DATA Technology   | 2         | 2      | 2.6%    |
| Zheino              | 1         | 1      | 1.3%    |
| VISIPRO             | 1         | 1      | 1.3%    |
| Union Memory        | 1         | 1      | 1.3%    |
| Transcend           | 1         | 1      | 1.3%    |
| Toshiba             | 1         | 1      | 1.3%    |
| OWC                 | 1         | 1      | 1.3%    |
| Netac               | 1         | 1      | 1.3%    |
| Mushkin             | 1         | 1      | 1.3%    |
| MicroFrom           | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| Hewlett-Packard     | 1         | 1      | 1.3%    |
| Gigabyte Technology | 1         | 1      | 1.3%    |
| Corsair             | 1         | 2      | 1.3%    |
| 4Life               | 1         | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 67        | 105    | 35.26%  |
| NVMe    | 62        | 77     | 32.63%  |
| HDD     | 44        | 63     | 23.16%  |
| MMC     | 15        | 17     | 7.89%   |
| Unknown | 2         | 2      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 161    | 50.87%  |
| NVMe | 62        | 76     | 35.84%  |
| MMC  | 15        | 17     | 8.67%   |
| SAS  | 8         | 10     | 4.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 106    | 59.17%  |
| 0.51-1.0   | 32        | 41     | 26.67%  |
| 1.01-2.0   | 10        | 12     | 8.33%   |
| 3.01-4.0   | 6         | 7      | 5%      |
| 4.01-10.0  | 1         | 2      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 30.77%  |
| 251-500        | 37        | 25.87%  |
| 501-1000       | 19        | 13.29%  |
| 51-100         | 13        | 9.09%   |
| 1001-2000      | 10        | 6.99%   |
| 21-50          | 6         | 4.2%    |
| 1-20           | 6         | 4.2%    |
| More than 3000 | 5         | 3.5%    |
| 2001-3000      | 3         | 2.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 39        | 26.53%  |
| 21-50          | 37        | 25.17%  |
| 101-250        | 24        | 16.33%  |
| 51-100         | 21        | 14.29%  |
| 251-500        | 11        | 7.48%   |
| 1001-2000      | 7         | 4.76%   |
| 501-1000       | 6         | 4.08%   |
| More than 3000 | 1         | 0.68%   |
| 2001-3000      | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 25%     |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 25%     |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 87        | 163    | 56.13%  |
| Works    | 63        | 96     | 40.65%  |
| Malfunc  | 4         | 4      | 2.58%   |
| Failed   | 1         | 1      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 87        | 48.88%  |
| AMD                            | 25        | 14.04%  |
| Samsung Electronics            | 23        | 12.92%  |
| Micron Technology              | 6         | 3.37%   |
| SanDisk                        | 5         | 2.81%   |
| SK hynix                       | 4         | 2.25%   |
| Kingston Technology Company    | 4         | 2.25%   |
| Toshiba America Info Systems   | 3         | 1.69%   |
| Phison Electronics             | 3         | 1.69%   |
| Nvidia                         | 3         | 1.69%   |
| Micron/Crucial Technology      | 2         | 1.12%   |
| Marvell Technology Group       | 2         | 1.12%   |
| KIOXIA                         | 2         | 1.12%   |
| ADATA Technology               | 2         | 1.12%   |
| Yangtze Memory Technologies    | 1         | 0.56%   |
| Transcend                      | 1         | 0.56%   |
| Solid State Storage Technology | 1         | 0.56%   |
| Seagate Technology             | 1         | 0.56%   |
| Realtek Semiconductor          | 1         | 0.56%   |
| OCZ Technology Group           | 1         | 0.56%   |
| JMicron Technology             | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 8.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 6.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 4.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 3.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.53%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.52%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 1.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.01%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 1.01%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 1.01%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.01%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.01%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 2         | 1.01%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.01%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.01%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.01%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 1.01%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 99        | 53.51%  |
| NVMe | 62        | 33.51%  |
| RAID | 12        | 6.49%   |
| IDE  | 12        | 6.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 110       | 76.92%  |
| AMD    | 33        | 23.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 3.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.1%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 2.1%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.1%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.4%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.4%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.4%    |
| Intel Core i5-4590T CPU @ 2.00GHz             | 2         | 1.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.4%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.4%    |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 1.4%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.4%    |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.4%    |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 1.4%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.4%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.4%    |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.4%    |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 0.7%    |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.7%    |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 0.7%    |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.7%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.7%    |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.7%    |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.7%    |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 23.78%  |
| Intel Core i7           | 24        | 16.78%  |
| Other                   | 19        | 13.29%  |
| AMD Ryzen 5             | 11        | 7.69%   |
| AMD Ryzen 7             | 8         | 5.59%   |
| Intel Core i3           | 7         | 4.9%    |
| Intel Celeron           | 7         | 4.9%    |
| Intel Xeon              | 4         | 2.8%    |
| Intel Atom              | 4         | 2.8%    |
| Intel Pentium           | 3         | 2.1%    |
| Intel Core 2 Duo        | 3         | 2.1%    |
| Intel Pentium Silver    | 2         | 1.4%    |
| AMD Ryzen 9             | 2         | 1.4%    |
| AMD Ryzen 3             | 2         | 1.4%    |
| AMD A8                  | 2         | 1.4%    |
| AMD A4                  | 2         | 1.4%    |
| Intel Pentium Dual-Core | 1         | 0.7%    |
| Intel Core i9           | 1         | 0.7%    |
| Intel Core 2 Quad       | 1         | 0.7%    |
| AMD Phenom II X4        | 1         | 0.7%    |
| AMD FX                  | 1         | 0.7%    |
| AMD Athlon X4           | 1         | 0.7%    |
| AMD Athlon II X3        | 1         | 0.7%    |
| AMD Athlon              | 1         | 0.7%    |
| AMD A10                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 59        | 41.26%  |
| 2      | 46        | 32.17%  |
| 8      | 15        | 10.49%  |
| 6      | 14        | 9.79%   |
| 12     | 3         | 2.1%    |
| 10     | 2         | 1.4%    |
| 1      | 2         | 1.4%    |
| 16     | 1         | 0.7%    |
| 3      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 141       | 98.6%   |
| 2      | 2         | 1.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 105       | 73.43%  |
| 1      | 38        | 26.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 143       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 56.08%  |
| 0x806c1    | 5         | 3.38%   |
| 0x806ec    | 4         | 2.7%    |
| 0x306a9    | 4         | 2.7%    |
| 0x08600106 | 4         | 2.7%    |
| 0x706a8    | 3         | 2.03%   |
| 0x206a7    | 3         | 2.03%   |
| 0x08108102 | 3         | 2.03%   |
| 0x806ea    | 2         | 1.35%   |
| 0x806e9    | 2         | 1.35%   |
| 0x806d1    | 2         | 1.35%   |
| 0x506e3    | 2         | 1.35%   |
| 0x406f1    | 2         | 1.35%   |
| 0x406e3    | 2         | 1.35%   |
| 0x306c3    | 2         | 1.35%   |
| 0x20655    | 2         | 1.35%   |
| 0x106e5    | 2         | 1.35%   |
| 0x0a50000c | 2         | 1.35%   |
| 0xa0671    | 1         | 0.68%   |
| 0x906eb    | 1         | 0.68%   |
| 0x906ea    | 1         | 0.68%   |
| 0x906a3    | 1         | 0.68%   |
| 0x806eb    | 1         | 0.68%   |
| 0x506c9    | 1         | 0.68%   |
| 0x406c4    | 1         | 0.68%   |
| 0x40651    | 1         | 0.68%   |
| 0x306d4    | 1         | 0.68%   |
| 0x30678    | 1         | 0.68%   |
| 0x1067a    | 1         | 0.68%   |
| 0x10677    | 1         | 0.68%   |
| 0x0a201205 | 1         | 0.68%   |
| 0x08608104 | 1         | 0.68%   |
| 0x08608103 | 1         | 0.68%   |
| 0x08108109 | 1         | 0.68%   |
| 0x07030105 | 1         | 0.68%   |
| 0x07030104 | 1         | 0.68%   |
| 0x06001119 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 16.78%  |
| Skylake          | 12        | 8.39%   |
| TigerLake        | 11        | 7.69%   |
| Unknown          | 10        | 6.99%   |
| IvyBridge        | 8         | 5.59%   |
| Haswell          | 8         | 5.59%   |
| Zen+             | 7         | 4.9%    |
| Zen 3            | 7         | 4.9%    |
| Zen 2            | 6         | 4.2%    |
| SandyBridge      | 6         | 4.2%    |
| Penryn           | 6         | 4.2%    |
| Silvermont       | 5         | 3.5%    |
| Broadwell        | 5         | 3.5%    |
| Icelake          | 4         | 2.8%    |
| Goldmont plus    | 4         | 2.8%    |
| Westmere         | 3         | 2.1%    |
| Nehalem          | 3         | 2.1%    |
| CometLake        | 3         | 2.1%    |
| Puma             | 2         | 1.4%    |
| Piledriver       | 2         | 1.4%    |
| K10              | 2         | 1.4%    |
| Steamroller      | 1         | 0.7%    |
| Goldmont         | 1         | 0.7%    |
| Excavator        | 1         | 0.7%    |
| Bulldozer        | 1         | 0.7%    |
| Alderlake Hybrid | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 95        | 56.89%  |
| Nvidia | 38        | 22.75%  |
| AMD    | 34        | 20.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 6.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.68%   |
| Intel UHD Graphics 620                                                                   | 6         | 3.51%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.51%   |
| Intel HD Graphics 620                                                                    | 5         | 2.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 2.34%   |
| Intel HD Graphics 530                                                                    | 4         | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.75%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.75%   |
| AMD Lucienne                                                                             | 3         | 1.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.17%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.17%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.17%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.17%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.58%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                   | 1         | 0.58%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 50.35%  |
| 1 x AMD        | 26        | 18.18%  |
| 1 x Nvidia     | 18        | 12.59%  |
| Intel + Nvidia | 17        | 11.89%  |
| 2 x AMD        | 3         | 2.1%    |
| AMD + Nvidia   | 3         | 2.1%    |
| Intel + AMD    | 2         | 1.4%    |
| Other          | 1         | 0.7%    |
| 2 x Intel      | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 120       | 83.33%  |
| Proprietary | 21        | 14.58%  |
| Unknown     | 3         | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 76.92%  |
| 1.01-2.0   | 8         | 5.59%   |
| 0.01-0.5   | 8         | 5.59%   |
| 7.01-8.0   | 5         | 3.5%    |
| 3.01-4.0   | 5         | 3.5%    |
| 0.51-1.0   | 4         | 2.8%    |
| 2.01-3.0   | 2         | 1.4%    |
| 16.01-24.0 | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 25        | 15.72%  |
| BOE                     | 25        | 15.72%  |
| Chimei Innolux          | 23        | 14.47%  |
| AU Optronics            | 14        | 8.81%   |
| LG Display              | 9         | 5.66%   |
| Goldstar                | 7         | 4.4%    |
| Apple                   | 7         | 4.4%    |
| AOC                     | 5         | 3.14%   |
| Sharp                   | 4         | 2.52%   |
| Philips                 | 4         | 2.52%   |
| Hewlett-Packard         | 4         | 2.52%   |
| BenQ                    | 3         | 1.89%   |
| SANYO                   | 2         | 1.26%   |
| Lenovo                  | 2         | 1.26%   |
| HKC                     | 2         | 1.26%   |
| Fujitsu Siemens         | 2         | 1.26%   |
| Dell                    | 2         | 1.26%   |
| Vizio                   | 1         | 0.63%   |
| Vestel Elektronik       | 1         | 0.63%   |
| Unknown (XXX)           | 1         | 0.63%   |
| Unknown (AAA)           | 1         | 0.63%   |
| TMX                     | 1         | 0.63%   |
| Sony                    | 1         | 0.63%   |
| PANDA                   | 1         | 0.63%   |
| Panasonic               | 1         | 0.63%   |
| ONN                     | 1         | 0.63%   |
| MStar                   | 1         | 0.63%   |
| LG Philips              | 1         | 0.63%   |
| LG Electronics          | 1         | 0.63%   |
| KDC                     | 1         | 0.63%   |
| IBM                     | 1         | 0.63%   |
| Denver                  | 1         | 0.63%   |
| Daewoo                  | 1         | 0.63%   |
| Chi Mei Optoelectronics | 1         | 0.63%   |
| Ancor Communications    | 1         | 0.63%   |
| Acer                    | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch        | 2         | 1.22%   |
| Vizio E320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                      | 1         | 0.61%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch      | 1         | 0.61%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.61%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                | 1         | 0.61%   |
| TMX TL142GDXP10-0 TMX1420 2520x1680 300x200mm 14.2-inch                 | 1         | 0.61%   |
| Sony TV SNYEE01 1920x1080                                               | 1         | 0.61%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                 | 1         | 0.61%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.61%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.61%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                 | 1         | 0.61%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                  | 1         | 0.61%   |
| SANYO LCD SAN0A12 1920x540                                              | 1         | 0.61%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch    | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch    | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch    | 1         | 0.61%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch     | 1         | 0.61%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch       | 1         | 0.61%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.61%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 0.61%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 0.61%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1         | 0.61%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch     | 1         | 0.61%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1         | 0.61%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch       | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch    | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch   | 1         | 0.61%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch       | 1         | 0.61%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 47.33%  |
| 1366x768 (WXGA)    | 26        | 17.33%  |
| 3840x2160 (4K)     | 11        | 7.33%   |
| 2560x1440 (QHD)    | 7         | 4.67%   |
| 1920x1200 (WUXGA)  | 6         | 4%      |
| 1680x1050 (WSXGA+) | 4         | 2.67%   |
| 1600x900 (HD+)     | 4         | 2.67%   |
| 1280x800 (WXGA)    | 4         | 2.67%   |
| 1920x540           | 3         | 2%      |
| 3440x1440          | 2         | 1.33%   |
| 2560x1080          | 2         | 1.33%   |
| 1440x900 (WXGA+)   | 2         | 1.33%   |
| 3456x2160          | 1         | 0.67%   |
| 2880x1800          | 1         | 0.67%   |
| 2736x1824          | 1         | 0.67%   |
| 2560x1600          | 1         | 0.67%   |
| 2520x1680          | 1         | 0.67%   |
| 2240x1400          | 1         | 0.67%   |
| 1360x768           | 1         | 0.67%   |
| 1280x1024 (SXGA)   | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 29.01%  |
| 13      | 23        | 14.2%   |
| 24      | 12        | 7.41%   |
| 14      | 12        | 7.41%   |
| 23      | 11        | 6.79%   |
| 27      | 10        | 6.17%   |
| 21      | 7         | 4.32%   |
| 17      | 5         | 3.09%   |
| 34      | 4         | 2.47%   |
| 31      | 4         | 2.47%   |
| Unknown | 4         | 2.47%   |
| 40      | 3         | 1.85%   |
| 12      | 3         | 1.85%   |
| 11      | 3         | 1.85%   |
| 84      | 2         | 1.23%   |
| 54      | 2         | 1.23%   |
| 72      | 1         | 0.62%   |
| 60      | 1         | 0.62%   |
| 33      | 1         | 0.62%   |
| 28      | 1         | 0.62%   |
| 26      | 1         | 0.62%   |
| 22      | 1         | 0.62%   |
| 20      | 1         | 0.62%   |
| 19      | 1         | 0.62%   |
| 18      | 1         | 0.62%   |
| 10      | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 70        | 44.03%  |
| 501-600     | 29        | 18.24%  |
| 201-300     | 18        | 11.32%  |
| 401-500     | 12        | 7.55%   |
| 601-700     | 6         | 3.77%   |
| 351-400     | 6         | 3.77%   |
| 701-800     | 5         | 3.14%   |
| Unknown     | 4         | 2.52%   |
| 801-900     | 3         | 1.89%   |
| 1501-2000   | 3         | 1.89%   |
| 1001-1500   | 3         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 78.47%  |
| 16/10   | 20        | 13.89%  |
| 21/9    | 4         | 2.78%   |
| 3/2     | 3         | 2.08%   |
| Unknown | 2         | 1.39%   |
| 4/3     | 1         | 0.69%   |
| 32/9    | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 29.56%  |
| 81-90          | 28        | 17.61%  |
| 201-250        | 23        | 14.47%  |
| 351-500        | 10        | 6.29%   |
| 301-350        | 10        | 6.29%   |
| More than 1000 | 6         | 3.77%   |
| 71-80          | 6         | 3.77%   |
| 151-200        | 5         | 3.14%   |
| 251-300        | 4         | 2.52%   |
| 121-130        | 4         | 2.52%   |
| Unknown        | 4         | 2.52%   |
| 61-70          | 3         | 1.89%   |
| 51-60          | 3         | 1.89%   |
| 501-1000       | 3         | 1.89%   |
| 41-50          | 1         | 0.63%   |
| 141-150        | 1         | 0.63%   |
| 91-100         | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 51        | 32.08%  |
| 51-100        | 40        | 25.16%  |
| 101-120       | 35        | 22.01%  |
| 161-240       | 15        | 9.43%   |
| More than 240 | 7         | 4.4%    |
| 1-50          | 7         | 4.4%    |
| Unknown       | 4         | 2.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 115       | 79.86%  |
| 2     | 27        | 18.75%  |
| 0     | 2         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 36.97%  |
| Realtek Semiconductor | 72        | 34.12%  |
| Qualcomm Atheros      | 18        | 8.53%   |
| Broadcom              | 13        | 6.16%   |
| MediaTek              | 7         | 3.32%   |
| Broadcom Limited      | 4         | 1.9%    |
| Nvidia                | 3         | 1.42%   |
| ASIX Electronics      | 3         | 1.42%   |
| Hewlett-Packard       | 2         | 0.95%   |
| Xiaomi                | 1         | 0.47%   |
| TP-Link               | 1         | 0.47%   |
| T & A Mobile Phones   | 1         | 0.47%   |
| Sierra Wireless       | 1         | 0.47%   |
| Ralink Technology     | 1         | 0.47%   |
| Microsoft             | 1         | 0.47%   |
| Lenovo                | 1         | 0.47%   |
| JMicron Technology    | 1         | 0.47%   |
| Huawei Technologies   | 1         | 0.47%   |
| Fibocom               | 1         | 0.47%   |
| ASUSTek Computer      | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 46        | 18.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 3.98%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 3.98%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 3.59%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.99%   |
| Intel Wireless 8260                                                     | 5         | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.59%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.2%    |
| Intel Wireless 7265                                                     | 3         | 1.2%    |
| Intel Ethernet Controller I225-V                                        | 3         | 1.2%    |
| Intel Ethernet Connection I219-V                                        | 3         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.8%    |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.8%    |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.8%    |
| Intel Ethernet Connection (2) I218-V                                    | 2         | 0.8%    |
| Intel Ethernet Connection (14) I219-V                                   | 2         | 0.8%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                       | 2         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.4%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.4%    |
| T & A Mobile Phones TCL 20E                                             | 1         | 0.4%    |
| Sierra Wireless EM7455                                                  | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 50.79%  |
| Realtek Semiconductor | 21        | 16.67%  |
| Qualcomm Atheros      | 14        | 11.11%  |
| Broadcom              | 11        | 8.73%   |
| MediaTek              | 7         | 5.56%   |
| Broadcom Limited      | 2         | 1.59%   |
| TP-Link               | 1         | 0.79%   |
| Sierra Wireless       | 1         | 0.79%   |
| Ralink Technology     | 1         | 0.79%   |
| Microsoft             | 1         | 0.79%   |
| Hewlett-Packard       | 1         | 0.79%   |
| Fibocom               | 1         | 0.79%   |
| ASUSTek Computer      | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 7.94%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 7.14%   |
| Intel Wireless 8265 / 8275                                              | 8         | 6.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.97%   |
| Intel Wireless 8260                                                     | 5         | 3.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 3.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 3.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.38%   |
| Intel Wireless 7265                                                     | 3         | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 2.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.59%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.79%   |
| Sierra Wireless EM7455                                                  | 1         | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.79%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.79%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.79%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 0.79%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 64        | 53.33%  |
| Intel                 | 33        | 27.5%   |
| Broadcom              | 6         | 5%      |
| Qualcomm Atheros      | 4         | 3.33%   |
| Nvidia                | 3         | 2.5%    |
| ASIX Electronics      | 3         | 2.5%    |
| Broadcom Limited      | 2         | 1.67%   |
| Xiaomi                | 1         | 0.83%   |
| T & A Mobile Phones   | 1         | 0.83%   |
| Lenovo                | 1         | 0.83%   |
| JMicron Technology    | 1         | 0.83%   |
| Hewlett-Packard       | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 37.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 8.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 5.65%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.23%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.42%   |
| Intel Ethernet Connection I219-V                                  | 3         | 2.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.61%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.61%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.61%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.61%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.81%   |
| T & A Mobile Phones TCL 20E                                       | 1         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.81%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.81%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.81%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.81%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.81%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 51.05%  |
| Ethernet | 115       | 48.52%  |
| Modem    | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 64.38%  |
| Ethernet | 52        | 35.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 82        | 57.34%  |
| 1     | 57        | 39.86%  |
| 0     | 4         | 2.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 69.86%  |
| Yes  | 44        | 30.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 55.45%  |
| Realtek Semiconductor           | 8         | 7.92%   |
| Apple                           | 8         | 7.92%   |
| Qualcomm Atheros Communications | 7         | 6.93%   |
| Broadcom                        | 6         | 5.94%   |
| IMC Networks                    | 5         | 4.95%   |
| MediaTek                        | 2         | 1.98%   |
| Dell                            | 2         | 1.98%   |
| Cambridge Silicon Radio         | 2         | 1.98%   |
| Smart Modular Technologies      | 1         | 0.99%   |
| Realtek                         | 1         | 0.99%   |
| Lite-On Technology              | 1         | 0.99%   |
| Foxconn International           | 1         | 0.99%   |
| Foxconn / Hon Hai               | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 17.82%  |
| Intel AX201 Bluetooth                               | 15        | 14.85%  |
| Intel AX200 Bluetooth                               | 10        | 9.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.95%   |
| Apple Bluetooth USB Host Controller                 | 5         | 4.95%   |
| Realtek Bluetooth Radio                             | 4         | 3.96%   |
| Intel AX210 Bluetooth                               | 4         | 3.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.97%   |
| IMC Networks Wireless_Device                        | 3         | 2.97%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.98%   |
| MediaTek Wireless_Device                            | 2         | 1.98%   |
| Intel Bluetooth Device                              | 2         | 1.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.98%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.98%   |
| Apple Bluetooth Host Controller                     | 2         | 1.98%   |
| Smart Modular Bluetooth Device                      | 1         | 0.99%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.99%   |
| Realtek Bluetooth Radio                             | 1         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.99%   |
| Lite-On Bluetooth Radio                             | 1         | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.99%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.99%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.99%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.99%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.99%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.99%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 103       | 56.28%  |
| AMD                     | 37        | 20.22%  |
| Nvidia                  | 26        | 14.21%  |
| Plantronics             | 3         | 1.64%   |
| Logitech                | 2         | 1.09%   |
| DSEA A/S                | 2         | 1.09%   |
| Texas Instruments       | 1         | 0.55%   |
| Shure                   | 1         | 0.55%   |
| Realtek Semiconductor   | 1         | 0.55%   |
| LINE TECH INDUSTRIAL    | 1         | 0.55%   |
| Creative Technology     | 1         | 0.55%   |
| ClearOne Communications | 1         | 0.55%   |
| ASUSTek Computer        | 1         | 0.55%   |
| Arturia                 | 1         | 0.55%   |
| Apple                   | 1         | 0.55%   |
| AKAI Professional M.I.  | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 9.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 6.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.73%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.36%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.36%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.91%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.91%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.91%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.91%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2         | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.91%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.45%   |
| Shure MV88+                                                                | 1         | 0.45%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 26.8%   |
| SK hynix            | 22        | 22.68%  |
| Kingston            | 12        | 12.37%  |
| Crucial             | 9         | 9.28%   |
| Micron Technology   | 8         | 8.25%   |
| Elpida              | 4         | 4.12%   |
| Unknown (ABCD)      | 2         | 2.06%   |
| Ramaxel Technology  | 2         | 2.06%   |
| Corsair             | 2         | 2.06%   |
| A-DATA Technology   | 2         | 2.06%   |
| Unknown             | 1         | 1.03%   |
| Transcend           | 1         | 1.03%   |
| Teikon              | 1         | 1.03%   |
| Nanya Technology    | 1         | 1.03%   |
| Magnum Tech         | 1         | 1.03%   |
| fef5                | 1         | 1.03%   |
| ChangXin Memory     | 1         | 1.03%   |
| 8945000080AD        | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.92%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 1.92%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.92%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.96%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 0.96%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.96%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 0.96%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.96%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 0.96%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 0.96%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.96%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.96%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.96%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 0.96%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 0.96%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.96%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.96%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.96%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.96%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.96%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 1         | 0.96%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 56.79%  |
| DDR3    | 21        | 25.93%  |
| LPDDR4  | 9         | 11.11%  |
| SDRAM   | 2         | 2.47%   |
| LPDDR3  | 2         | 2.47%   |
| Unknown | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 70.89%  |
| DIMM         | 13        | 16.46%  |
| Row Of Chips | 7         | 8.86%   |
| Unknown      | 2         | 2.53%   |
| Chip         | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 42.17%  |
| 4096  | 17        | 20.48%  |
| 16384 | 14        | 16.87%  |
| 2048  | 8         | 9.64%   |
| 32768 | 7         | 8.43%   |
| 1024  | 2         | 2.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 21        | 23.86%  |
| 2667  | 15        | 17.05%  |
| 1600  | 15        | 17.05%  |
| 2400  | 11        | 12.5%   |
| 2133  | 5         | 5.68%   |
| 1333  | 4         | 4.55%   |
| 4267  | 3         | 3.41%   |
| 1067  | 3         | 3.41%   |
| 1867  | 2         | 2.27%   |
| 1334  | 2         | 2.27%   |
| 1066  | 2         | 2.27%   |
| 4199  | 1         | 1.14%   |
| 3733  | 1         | 1.14%   |
| 3600  | 1         | 1.14%   |
| 3266  | 1         | 1.14%   |
| 2933  | 1         | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Dymo-CoStar         | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 20%     |
| HP LaserJet 1320              | 1         | 20%     |
| HP DeskJet 3700 series        | 1         | 20%     |
| Dymo-CoStar LabelWriter 450   | 1         | 20%     |
| Canon LiDE 400                | 1         | 20%     |

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
| Chicony Electronics                    | 29        | 30.21%  |
| IMC Networks                           | 9         | 9.38%   |
| Realtek Semiconductor                  | 8         | 8.33%   |
| Microdia                               | 6         | 6.25%   |
| Luxvisions Innotech Limited            | 6         | 6.25%   |
| Bison Electronics                      | 6         | 6.25%   |
| Apple                                  | 6         | 6.25%   |
| Sunplus Innovation Technology          | 5         | 5.21%   |
| Syntek                                 | 3         | 3.13%   |
| Logitech                               | 3         | 3.13%   |
| Samsung Electronics                    | 2         | 2.08%   |
| Quanta                                 | 2         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.08%   |
| WaveRider Communications               | 1         | 1.04%   |
| ValueHD                                | 1         | 1.04%   |
| Unknown (3730304233333731323245)       | 1         | 1.04%   |
| Unknown                                | 1         | 1.04%   |
| Polycom                                | 1         | 1.04%   |
| Generalplus Technology                 | 1         | 1.04%   |
| Alcor Micro                            | 1         | 1.04%   |
| Acer                                   | 1         | 1.04%   |
| Unknown                                | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 5         | 5.21%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 4.17%   |
| Chicony Integrated Camera                            | 4         | 4.17%   |
| Chicony HP HD Camera                                 | 4         | 4.17%   |
| Realtek Integrated_Webcam_HD                         | 3         | 3.13%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.13%   |
| Logitech HD Pro Webcam C920                          | 3         | 3.13%   |
| IMC Networks Integrated Camera                       | 3         | 3.13%   |
| Bison SunplusIT Integrated Camera                    | 3         | 3.13%   |
| Syntek Integrated Camera                             | 2         | 2.08%   |
| Sunplus FHD Camera Microphone                        | 2         | 2.08%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.08%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 2.08%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 2.08%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 2.08%   |
| Chicony USB2.0 Camera                                | 2         | 2.08%   |
| Bison EasyCamera                                     | 2         | 2.08%   |
| Apple FaceTime HD Camera                             | 2         | 2.08%   |
| Apple Built-in iSight                                | 2         | 2.08%   |
| WaveRider USB 2.0 Camera                             | 1         | 1.04%   |
| ValueHD Konftel Cam20                                | 1         | 1.04%   |
| Unknown ATIV VGA CAMERA                              | 1         | 1.04%   |
| Unknown (3730304233333731323245) USB Camera          | 1         | 1.04%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.04%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.04%   |
| Sunplus HD WebCam                                    | 1         | 1.04%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 1.04%   |
| Realtek USB Camera                                   | 1         | 1.04%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.04%   |
| Realtek Integrated Webcam HD                         | 1         | 1.04%   |
| Realtek Integrated Webcam                            | 1         | 1.04%   |
| Quanta USB2.0 HD UVC WebCam                          | 1         | 1.04%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.04%   |
| Polycom Poly Studio P5 webcam                        | 1         | 1.04%   |
| Microdia Lenovo EasyCamera                           | 1         | 1.04%   |
| Microdia Integrated Webcam HD                        | 1         | 1.04%   |
| Microdia Camera                                      | 1         | 1.04%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 1         | 1.04%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 40%     |
| Validity Sensors           | 6         | 24%     |
| Shenzhen Goodix Technology | 6         | 24%     |
| Elan Microelectronics      | 2         | 8%      |
| LighTuning Technology      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 12%     |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 12%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 8%      |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 4%      |
| Validity Sensors Synaptics WBDI                           | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 4%      |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 4%      |
| Synaptics UWP WBDI Device                                 | 1         | 4%      |
| Synaptics TouchPad                                        | 1         | 4%      |
| Synaptics  WBDI                                           | 1         | 4%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 4%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4%      |
| Shenzhen Goodix FingerPrint                               | 1         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 4%      |
| Elan ELAN:Fingerprint                                     | 1         | 4%      |
| Elan ELAN:ARM-M4                                          | 1         | 4%      |
| Unknown                                                   | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 60%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 64.83%  |
| 1     | 35        | 24.14%  |
| 2     | 12        | 8.28%   |
| 3     | 2         | 1.38%   |
| 6     | 1         | 0.69%   |
| 4     | 1         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 35.82%  |
| Net/wireless             | 8         | 11.94%  |
| Graphics card            | 8         | 11.94%  |
| Chipcard                 | 5         | 7.46%   |
| Sound                    | 4         | 5.97%   |
| Communication controller | 4         | 5.97%   |
| Unassigned class         | 3         | 4.48%   |
| Multimedia controller    | 3         | 4.48%   |
| Camera                   | 3         | 4.48%   |
| Card reader              | 2         | 2.99%   |
| Bluetooth                | 2         | 2.99%   |
| Net/ethernet             | 1         | 1.49%   |


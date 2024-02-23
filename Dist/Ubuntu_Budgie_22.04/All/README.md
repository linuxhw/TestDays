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

Total: 213

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c80a1f64fc](https://linux-hardware.org/?probe=c80a1f64fc) | Jan 18, 2024 |
| Toshiba       | Satellite C855D-11X         | Notebook    | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | Notebook    | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [66efe29bec](https://linux-hardware.org/?probe=66efe29bec) | Jan 11, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [462cb61dd3](https://linux-hardware.org/?probe=462cb61dd3) | Jan 05, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [03e7ada99a](https://linux-hardware.org/?probe=03e7ada99a) | Jan 04, 2024 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [7efa5db123](https://linux-hardware.org/?probe=7efa5db123) | Dec 29, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
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
| 5.15.0-27-generic    | 11        | 6.47%   |
| 5.15.0-52-generic    | 9         | 5.29%   |
| 5.15.0-50-generic    | 7         | 4.12%   |
| 5.15.0-48-generic    | 6         | 3.53%   |
| 5.15.0-30-generic    | 6         | 3.53%   |
| 6.2.0-39-generic     | 5         | 2.94%   |
| 5.19.0-46-generic    | 5         | 2.94%   |
| 5.15.0-46-generic    | 5         | 2.94%   |
| 5.15.0-43-generic    | 5         | 2.94%   |
| 5.15.0-39-generic    | 5         | 2.94%   |
| 6.2.0-26-generic     | 4         | 2.35%   |
| 5.19.0-35-generic    | 4         | 2.35%   |
| 5.15.0-57-generic    | 4         | 2.35%   |
| 5.15.0-56-generic    | 4         | 2.35%   |
| 5.15.0-33-generic    | 4         | 2.35%   |
| 5.15.0-25-generic    | 4         | 2.35%   |
| 6.2.0-33-generic     | 3         | 1.76%   |
| 5.19.0-45-generic    | 3         | 1.76%   |
| 5.19.0-41-generic    | 3         | 1.76%   |
| 5.19.0-40-generic    | 3         | 1.76%   |
| 5.15.0-58-generic    | 3         | 1.76%   |
| 5.15.0-53-generic    | 3         | 1.76%   |
| 5.15.0-47-generic    | 3         | 1.76%   |
| 5.15.0-40-generic    | 3         | 1.76%   |
| 6.5.0-14-generic     | 2         | 1.18%   |
| 6.5.0-10013-tuxedo   | 2         | 1.18%   |
| 6.2.0-37-generic     | 2         | 1.18%   |
| 6.2.0-32-generic     | 2         | 1.18%   |
| 6.2.0-10007-tuxedo   | 2         | 1.18%   |
| 5.19.0-42-generic    | 2         | 1.18%   |
| 5.19.0-38-generic    | 2         | 1.18%   |
| 5.15.0-67-generic    | 2         | 1.18%   |
| 5.15.0-60-generic    | 2         | 1.18%   |
| 5.15.0-41-generic    | 2         | 1.18%   |
| 6.5.0-10008-tuxedo   | 1         | 0.59%   |
| 6.3.1-060301-generic | 1         | 0.59%   |
| 6.2.0-36-generic     | 1         | 0.59%   |
| 6.2.0-35-generic     | 1         | 0.59%   |
| 6.2.0-34-generic     | 1         | 0.59%   |
| 6.2.0-10018-tuxedo   | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 102       | 64.56%  |
| 5.19.0  | 24        | 15.19%  |
| 6.2.0   | 20        | 12.66%  |
| 6.5.0   | 4         | 2.53%   |
| 5.13.0  | 3         | 1.9%    |
| 6.3.1   | 1         | 0.63%   |
| 6.1.0   | 1         | 0.63%   |
| 5.17.2  | 1         | 0.63%   |
| 5.16.2  | 1         | 0.63%   |
| 5.15.92 | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 103       | 65.19%  |
| 5.19    | 24        | 15.19%  |
| 6.2     | 20        | 12.66%  |
| 6.5     | 4         | 2.53%   |
| 5.13    | 3         | 1.9%    |
| 6.3     | 1         | 0.63%   |
| 6.1     | 1         | 0.63%   |
| 5.17    | 1         | 0.63%   |
| 5.16    | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 151       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 145       | 96.03%  |
| GNOME  | 5         | 3.31%   |
| KDE5   | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 147       | 97.35%  |
| Wayland | 4         | 2.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 108       | 71.52%  |
| Unknown | 27        | 17.88%  |
| GDM3    | 14        | 9.27%   |
| SDDM    | 1         | 0.66%   |
| GDM     | 1         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 55        | 36.42%  |
| de_DE | 19        | 12.58%  |
| fr_FR | 13        | 8.61%   |
| pt_BR | 10        | 6.62%   |
| en_GB | 10        | 6.62%   |
| en_CA | 5         | 3.31%   |
| es_ES | 4         | 2.65%   |
| it_IT | 3         | 1.99%   |
| fr_BE | 3         | 1.99%   |
| en_AU | 3         | 1.99%   |
| ru_RU | 2         | 1.32%   |
| hu_HU | 2         | 1.32%   |
| es_MX | 2         | 1.32%   |
| es_AR | 2         | 1.32%   |
| en_SG | 2         | 1.32%   |
| en_IE | 2         | 1.32%   |
| pl_PL | 1         | 0.66%   |
| mt_MT | 1         | 0.66%   |
| ja_JP | 1         | 0.66%   |
| eu_ES | 1         | 0.66%   |
| es_PE | 1         | 0.66%   |
| es_EC | 1         | 0.66%   |
| es_CL | 1         | 0.66%   |
| en_ZA | 1         | 0.66%   |
| en_NZ | 1         | 0.66%   |
| en_IL | 1         | 0.66%   |
| el_GR | 1         | 0.66%   |
| da_DK | 1         | 0.66%   |
| cs_CZ | 1         | 0.66%   |
| C     | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 90        | 59.21%  |
| EFI  | 62        | 40.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 127       | 82.47%  |
| Tmpfs   | 13        | 8.44%   |
| Overlay | 6         | 3.9%    |
| Zfs     | 4         | 2.6%    |
| Btrfs   | 3         | 1.95%   |
| Xfs     | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 100       | 65.79%  |
| Unknown | 45        | 29.61%  |
| MBR     | 7         | 4.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 85.43%  |
| Yes       | 22        | 14.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 65.79%  |
| Yes       | 52        | 34.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 24        | 15.89%  |
| Hewlett-Packard        | 20        | 13.25%  |
| ASUSTek Computer       | 18        | 11.92%  |
| Dell                   | 17        | 11.26%  |
| Gigabyte Technology    | 11        | 7.28%   |
| TUXEDO                 | 10        | 6.62%   |
| MSI                    | 10        | 6.62%   |
| Apple                  | 9         | 5.96%   |
| Intel                  | 4         | 2.65%   |
| Toshiba                | 3         | 1.99%   |
| Fujitsu                | 3         | 1.99%   |
| ASRock                 | 3         | 1.99%   |
| Google                 | 2         | 1.32%   |
| AZW                    | 2         | 1.32%   |
| Acer                   | 2         | 1.32%   |
| Timi                   | 1         | 0.66%   |
| Semp Toshiba           | 1         | 0.66%   |
| Samsung Electronics    | 1         | 0.66%   |
| Razer                  | 1         | 0.66%   |
| HUAWEI                 | 1         | 0.66%   |
| Digibras               | 1         | 0.66%   |
| COM1                   | 1         | 0.66%   |
| Chuwi                  | 1         | 0.66%   |
| Biostar                | 1         | 0.66%   |
| BANGHO                 | 1         | 0.66%   |
| AXIOO                  | 1         | 0.66%   |
| Avell High Performance | 1         | 0.66%   |
| Alurin                 | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 1.32%   |
| Lenovo G50-45 80E3                                   | 2         | 1.32%   |
| HP EliteBook 840 G3                                  | 2         | 1.32%   |
| AZW SER                                              | 2         | 1.32%   |
| TUXEDO Pulse 14 Gen1                                 | 1         | 0.66%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.66%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.66%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 0.66%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.66%   |
| TUXEDO Book XP1511                                   | 1         | 0.66%   |
| TUXEDO Book BA1510                                   | 1         | 0.66%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.66%   |
| Toshiba Satellite C855D-11X                          | 1         | 0.66%   |
| Toshiba Satellite A505                               | 1         | 0.66%   |
| Toshiba Satellite A300                               | 1         | 0.66%   |
| Timi TM1604                                          | 1         | 0.66%   |
| Semp Toshiba STI                                     | 1         | 0.66%   |
| Samsung 740U3M                                       | 1         | 0.66%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.66%   |
| MSI MS-7C95                                          | 1         | 0.66%   |
| MSI MS-7C51                                          | 1         | 0.66%   |
| MSI MS-7B86                                          | 1         | 0.66%   |
| MSI MS-7A38                                          | 1         | 0.66%   |
| MSI MS-7A32                                          | 1         | 0.66%   |
| MSI MS-7885                                          | 1         | 0.66%   |
| MSI MS-7721                                          | 1         | 0.66%   |
| MSI Modern 15 A10M                                   | 1         | 0.66%   |
| MSI GL62 6QF                                         | 1         | 0.66%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.66%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.66%   |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 0.66%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 0.66%   |
| Lenovo ThinkPad X220 4291G75                         | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002SIV             | 1         | 0.66%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 0.66%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 0.66%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 0.66%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 0.66%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 0.66%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 10        | 6.62%   |
| Lenovo IdeaPad      | 7         | 4.64%   |
| Dell Latitude       | 5         | 3.31%   |
| Dell Inspiron       | 5         | 3.31%   |
| HP EliteBook        | 4         | 2.65%   |
| ASUS VivoBook       | 4         | 2.65%   |
| TUXEDO Pulse        | 3         | 1.99%   |
| TUXEDO Book         | 3         | 1.99%   |
| Toshiba Satellite   | 3         | 1.99%   |
| HP ProBook          | 3         | 1.99%   |
| HP Pavilion         | 3         | 1.99%   |
| TUXEDO InfinityBook | 2         | 1.32%   |
| Lenovo G50-45       | 2         | 1.32%   |
| HP EliteDesk        | 2         | 1.32%   |
| Fujitsu ESPRIMO     | 2         | 1.32%   |
| Dell XPS            | 2         | 1.32%   |
| Dell Precision      | 2         | 1.32%   |
| Dell OptiPlex       | 2         | 1.32%   |
| AZW SER             | 2         | 1.32%   |
| ASUS ZenBook        | 2         | 1.32%   |
| ASUS ROG            | 2         | 1.32%   |
| Apple MacBookPro8   | 2         | 1.32%   |
| Acer Aspire         | 2         | 1.32%   |
| TUXEDO Polaris      | 1         | 0.66%   |
| TUXEDO Aura         | 1         | 0.66%   |
| Timi TM1604         | 1         | 0.66%   |
| Semp Toshiba STI    | 1         | 0.66%   |
| Samsung 740U3M      | 1         | 0.66%   |
| Razer Blade         | 1         | 0.66%   |
| MSI MS-7C95         | 1         | 0.66%   |
| MSI MS-7C51         | 1         | 0.66%   |
| MSI MS-7B86         | 1         | 0.66%   |
| MSI MS-7A38         | 1         | 0.66%   |
| MSI MS-7A32         | 1         | 0.66%   |
| MSI MS-7885         | 1         | 0.66%   |
| MSI MS-7721         | 1         | 0.66%   |
| MSI Modern          | 1         | 0.66%   |
| MSI GL62            | 1         | 0.66%   |
| MSI Alpha           | 1         | 0.66%   |
| Lenovo V15          | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 21        | 13.91%  |
| 2020 | 19        | 12.58%  |
| 2014 | 15        | 9.93%   |
| 2018 | 13        | 8.61%   |
| 2016 | 12        | 7.95%   |
| 2022 | 10        | 6.62%   |
| 2019 | 10        | 6.62%   |
| 2017 | 8         | 5.3%    |
| 2015 | 8         | 5.3%    |
| 2012 | 7         | 4.64%   |
| 2011 | 7         | 4.64%   |
| 2010 | 6         | 3.97%   |
| 2013 | 5         | 3.31%   |
| 2009 | 4         | 2.65%   |
| 2008 | 4         | 2.65%   |
| 2023 | 2         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 95        | 62.91%  |
| Desktop     | 41        | 27.15%  |
| Convertible | 6         | 3.97%   |
| Mini pc     | 5         | 3.31%   |
| All in one  | 3         | 1.99%   |
| Tablet      | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 142       | 94.04%  |
| Enabled  | 9         | 5.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 98.01%  |
| Yes  | 3         | 1.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 43        | 28.29%  |
| 16.01-24.0      | 41        | 26.97%  |
| 8.01-16.0       | 28        | 18.42%  |
| 3.01-4.0        | 14        | 9.21%   |
| 32.01-64.0      | 13        | 8.55%   |
| 64.01-256.0     | 6         | 3.95%   |
| 24.01-32.0      | 4         | 2.63%   |
| 1.01-2.0        | 2         | 1.32%   |
| More than 256.0 | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 56        | 34.36%  |
| 1.01-2.0   | 42        | 25.77%  |
| 4.01-8.0   | 29        | 17.79%  |
| 3.01-4.0   | 19        | 11.66%  |
| 8.01-16.0  | 12        | 7.36%   |
| 16.01-24.0 | 3         | 1.84%   |
| 24.01-32.0 | 2         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 60.39%  |
| 2      | 42        | 27.27%  |
| 3      | 9         | 5.84%   |
| 4      | 6         | 3.9%    |
| 6      | 2         | 1.3%    |
| 8      | 1         | 0.65%   |
| 7      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 74.17%  |
| Yes       | 39        | 25.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 80.92%  |
| No        | 29        | 19.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 84.77%  |
| No        | 23        | 15.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 70.86%  |
| No        | 44        | 29.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 28        | 18.54%  |
| Germany            | 21        | 13.91%  |
| France             | 14        | 9.27%   |
| Brazil             | 12        | 7.95%   |
| UK                 | 6         | 3.97%   |
| Spain              | 5         | 3.31%   |
| Canada             | 4         | 2.65%   |
| Poland             | 3         | 1.99%   |
| Italy              | 3         | 1.99%   |
| Belgium            | 3         | 1.99%   |
| Austria            | 3         | 1.99%   |
| Australia          | 3         | 1.99%   |
| Argentina          | 3         | 1.99%   |
| Switzerland        | 2         | 1.32%   |
| Slovenia           | 2         | 1.32%   |
| Singapore          | 2         | 1.32%   |
| Romania            | 2         | 1.32%   |
| Peru               | 2         | 1.32%   |
| Netherlands        | 2         | 1.32%   |
| Mexico             | 2         | 1.32%   |
| Ireland            | 2         | 1.32%   |
| Indonesia          | 2         | 1.32%   |
| Hungary            | 2         | 1.32%   |
| Greece             | 2         | 1.32%   |
| Sweden             | 1         | 0.66%   |
| South Africa       | 1         | 0.66%   |
| Saudi Arabia       | 1         | 0.66%   |
| Russia             | 1         | 0.66%   |
| Norway             | 1         | 0.66%   |
| New Zealand        | 1         | 0.66%   |
| Malta              | 1         | 0.66%   |
| Japan              | 1         | 0.66%   |
| Israel             | 1         | 0.66%   |
| Ghana              | 1         | 0.66%   |
| Ecuador            | 1         | 0.66%   |
| Dominican Republic | 1         | 0.66%   |
| Denmark            | 1         | 0.66%   |
| Czechia            | 1         | 0.66%   |
| Cuba               | 1         | 0.66%   |
| Croatia            | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Brasília             | 4         | 2.55%   |
| Berlin                | 4         | 2.55%   |
| Warsaw                | 2         | 1.27%   |
| Vienna                | 2         | 1.27%   |
| Victoria              | 2         | 1.27%   |
| Singapore             | 2         | 1.27%   |
| Nuremberg             | 2         | 1.27%   |
| Milwaukee             | 2         | 1.27%   |
| London                | 2         | 1.27%   |
| Laval                 | 2         | 1.27%   |
| Frankfurt am Main     | 2         | 1.27%   |
| Dublin                | 2         | 1.27%   |
| Budapest              | 2         | 1.27%   |
| Athens                | 2         | 1.27%   |
| Zurich                | 1         | 0.64%   |
| Yogyakarta            | 1         | 0.64%   |
| West Lafayette        | 1         | 0.64%   |
| Wertheim am Main      | 1         | 0.64%   |
| Weisswasser           | 1         | 0.64%   |
| Weilheim              | 1         | 0.64%   |
| Washington            | 1         | 0.64%   |
| Walled Lake           | 1         | 0.64%   |
| Venray                | 1         | 0.64%   |
| Trondheim             | 1         | 0.64%   |
| Torun                 | 1         | 0.64%   |
| Tocantins             | 1         | 0.64%   |
| Targu Frumos          | 1         | 0.64%   |
| Tarakan               | 1         | 0.64%   |
| Tann                  | 1         | 0.64%   |
| Tampa                 | 1         | 0.64%   |
| Sunnyvale             | 1         | 0.64%   |
| St Petersburg         | 1         | 0.64%   |
| Sofia                 | 1         | 0.64%   |
| Siegen                | 1         | 0.64%   |
| Shirakuni             | 1         | 0.64%   |
| Sétif                | 1         | 0.64%   |
| Seelze                | 1         | 0.64%   |
| Seattle               | 1         | 0.64%   |
| Sao Paulo             | 1         | 0.64%   |
| Sao Bernardo do Campo | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 41        | 69     | 18.3%   |
| Seagate                        | 23        | 31     | 10.27%  |
| WDC                            | 21        | 25     | 9.38%   |
| Unknown                        | 15        | 15     | 6.7%    |
| Toshiba                        | 14        | 17     | 6.25%   |
| Crucial                        | 14        | 19     | 6.25%   |
| Micron Technology              | 11        | 11     | 4.91%   |
| SK hynix                       | 8         | 8      | 3.57%   |
| SanDisk                        | 8         | 9      | 3.57%   |
| Kingston                       | 7         | 8      | 3.13%   |
| Intel                          | 6         | 8      | 2.68%   |
| SPCC                           | 4         | 5      | 1.79%   |
| China                          | 4         | 5      | 1.79%   |
| A-DATA Technology              | 4         | 5      | 1.79%   |
| OCZ                            | 3         | 3      | 1.34%   |
| JMicron Technology             | 3         | 3      | 1.34%   |
| Apple                          | 3         | 3      | 1.34%   |
| Transcend                      | 2         | 2      | 0.89%   |
| PNY                            | 2         | 2      | 0.89%   |
| Phison                         | 2         | 2      | 0.89%   |
| Micron/Crucial Technology      | 2         | 2      | 0.89%   |
| HGST                           | 2         | 2      | 0.89%   |
| Zheino                         | 1         | 1      | 0.45%   |
| YMTC                           | 1         | 1      | 0.45%   |
| VISIPRO                        | 1         | 1      | 0.45%   |
| Union Memory                   | 1         | 1      | 0.45%   |
| TO Exter                       | 1         | 1      | 0.45%   |
| Solid State Storage Technology | 1         | 1      | 0.45%   |
| Silicon Motion                 | 1         | 1      | 0.45%   |
| SABRENT                        | 1         | 1      | 0.45%   |
| Realtek Semiconductor          | 1         | 1      | 0.45%   |
| Phison Electronics             | 1         | 1      | 0.45%   |
| OWC                            | 1         | 1      | 0.45%   |
| Netac                          | 1         | 1      | 0.45%   |
| Mushkin                        | 1         | 1      | 0.45%   |
| MicroFrom                      | 1         | 1      | 0.45%   |
| Maxtor                         | 1         | 1      | 0.45%   |
| LITEON                         | 1         | 1      | 0.45%   |
| KIOXIA                         | 1         | 1      | 0.45%   |
| Kingston Technology Company    | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 3         | 1.23%   |
| Crucial CT480BX500SSD1 480GB                      | 3         | 1.23%   |
| Crucial CT240BX500SSD1 240GB                      | 3         | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 0.82%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.82%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.82%   |
| Unknown SD64G  64GB                               | 2         | 0.82%   |
| Unknown SD/MMC/MS PRO 256GB                       | 2         | 0.82%   |
| Unknown MMC Card  64GB                            | 2         | 0.82%   |
| Unknown MMC Card  128GB                           | 2         | 0.82%   |
| Seagate ST3500418AS 500GB                         | 2         | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB                    | 2         | 0.82%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 2         | 0.82%   |
| SanDisk SDSSDA120G 120GB                          | 2         | 0.82%   |
| Samsung SSD 980 PRO 2TB                           | 2         | 0.82%   |
| Samsung SSD 980 500GB                             | 2         | 0.82%   |
| Samsung SSD 870 EVO 250GB                         | 2         | 0.82%   |
| Samsung SSD 860 EVO M.2 500GB                     | 2         | 0.82%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.82%   |
| Samsung SSD 850 PRO 256GB                         | 2         | 0.82%   |
| Samsung SSD 850 EVO 500GB                         | 2         | 0.82%   |
| Samsung SSD 840 EVO 250GB                         | 2         | 0.82%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 2         | 0.82%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 2         | 0.82%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 0.82%   |
| JMicron Generic 8GB                               | 2         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 0.82%   |
| Zheino CHN-25SATAC3-120 120GB SSD                 | 1         | 0.41%   |
| YMTC PC005 1TB                                    | 1         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.41%   |
| WDC WDS100T2B0C 1TB                               | 1         | 0.41%   |
| WDC WD40PURZ-85TTDY0 4TB                          | 1         | 0.41%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 1         | 0.41%   |
| WDC WD40EFAX-68JH4N1 4TB                          | 1         | 0.41%   |
| WDC WD3200LPVX-22V0TT0 320GB                      | 1         | 0.41%   |
| WDC WD20EARX-00PASB0 2TB                          | 1         | 0.41%   |
| WDC WD1600AAJS-60WAA0 160GB                       | 1         | 0.41%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 30     | 38.98%  |
| WDC                 | 14        | 16     | 23.73%  |
| Toshiba             | 9         | 9      | 15.25%  |
| Samsung Electronics | 3         | 5      | 5.08%   |
| Unknown             | 2         | 2      | 3.39%   |
| JMicron Technology  | 2         | 2      | 3.39%   |
| HGST                | 2         | 2      | 3.39%   |
| TO Exter            | 1         | 1      | 1.69%   |
| Maxtor              | 1         | 1      | 1.69%   |
| ASMT109x            | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 36     | 20%     |
| Crucial             | 13        | 18     | 16.25%  |
| SanDisk             | 5         | 5      | 6.25%   |
| Micron Technology   | 5         | 5      | 6.25%   |
| WDC                 | 4         | 4      | 5%      |
| Kingston            | 4         | 5      | 5%      |
| China               | 4         | 5      | 5%      |
| SPCC                | 3         | 4      | 3.75%   |
| SK hynix            | 2         | 2      | 2.5%    |
| PNY                 | 2         | 2      | 2.5%    |
| OCZ                 | 2         | 2      | 2.5%    |
| Apple               | 2         | 2      | 2.5%    |
| A-DATA Technology   | 2         | 2      | 2.5%    |
| Zheino              | 1         | 1      | 1.25%   |
| VISIPRO             | 1         | 1      | 1.25%   |
| Union Memory        | 1         | 1      | 1.25%   |
| Transcend           | 1         | 1      | 1.25%   |
| Toshiba             | 1         | 1      | 1.25%   |
| SABRENT             | 1         | 1      | 1.25%   |
| OWC                 | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| Mushkin             | 1         | 1      | 1.25%   |
| MicroFrom           | 1         | 1      | 1.25%   |
| LITEON              | 1         | 1      | 1.25%   |
| Intel               | 1         | 1      | 1.25%   |
| Hewlett-Packard     | 1         | 1      | 1.25%   |
| Gigabyte Technology | 1         | 1      | 1.25%   |
| Corsair             | 1         | 2      | 1.25%   |
| 4Life               | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 71        | 109    | 35.32%  |
| NVMe    | 67        | 82     | 33.33%  |
| HDD     | 46        | 70     | 22.89%  |
| MMC     | 15        | 17     | 7.46%   |
| Unknown | 2         | 2      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 170    | 50.27%  |
| NVMe | 67        | 82     | 36.61%  |
| MMC  | 15        | 17     | 8.2%    |
| SAS  | 9         | 11     | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 115    | 60.63%  |
| 0.51-1.0   | 31        | 40     | 24.41%  |
| 1.01-2.0   | 11        | 14     | 8.66%   |
| 3.01-4.0   | 7         | 8      | 5.51%   |
| 4.01-10.0  | 1         | 2      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 31.13%  |
| 251-500        | 40        | 26.49%  |
| 501-1000       | 20        | 13.25%  |
| 51-100         | 13        | 8.61%   |
| 1001-2000      | 10        | 6.62%   |
| More than 3000 | 6         | 3.97%   |
| 21-50          | 6         | 3.97%   |
| 1-20           | 6         | 3.97%   |
| 2001-3000      | 3         | 1.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 26.92%  |
| 21-50          | 39        | 25%     |
| 101-250        | 27        | 17.31%  |
| 51-100         | 21        | 13.46%  |
| 251-500        | 11        | 7.05%   |
| 1001-2000      | 7         | 4.49%   |
| 501-1000       | 6         | 3.85%   |
| More than 3000 | 2         | 1.28%   |
| 2001-3000      | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 20%     |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 20%     |
| Seagate ST500DM002-1BD142 500GB    | 1         | 1      | 20%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 20%     |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

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
| Detected | 92        | 172    | 55.76%  |
| Works    | 67        | 102    | 40.61%  |
| Malfunc  | 5         | 5      | 3.03%   |
| Failed   | 1         | 1      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 90        | 47.12%  |
| AMD                            | 29        | 15.18%  |
| Samsung Electronics            | 25        | 13.09%  |
| SanDisk                        | 7         | 3.66%   |
| Micron Technology              | 6         | 3.14%   |
| SK hynix                       | 4         | 2.09%   |
| Kingston Technology Company    | 4         | 2.09%   |
| Toshiba America Info Systems   | 3         | 1.57%   |
| Phison Electronics             | 3         | 1.57%   |
| Nvidia                         | 3         | 1.57%   |
| Micron/Crucial Technology      | 3         | 1.57%   |
| Marvell Technology Group       | 2         | 1.05%   |
| KIOXIA                         | 2         | 1.05%   |
| ADATA Technology               | 2         | 1.05%   |
| Yangtze Memory Technologies    | 1         | 0.52%   |
| Transcend                      | 1         | 0.52%   |
| Solid State Storage Technology | 1         | 0.52%   |
| Silicon Motion                 | 1         | 0.52%   |
| Seagate Technology             | 1         | 0.52%   |
| Realtek Semiconductor          | 1         | 0.52%   |
| OCZ Technology Group           | 1         | 0.52%   |
| JMicron Technology             | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 8.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 6.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 3.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.42%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 1.42%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.95%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.95%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.95%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.95%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 2         | 0.95%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.95%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.95%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.95%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 0.95%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 0.95%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 106       | 53.81%  |
| NVMe | 67        | 34.01%  |
| RAID | 12        | 6.09%   |
| IDE  | 12        | 6.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 113       | 74.83%  |
| AMD    | 38        | 25.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 3.31%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 2.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.99%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.99%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.32%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.32%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.32%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 2         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.32%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.32%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 1.32%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.32%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 1.32%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.32%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.32%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.32%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 0.66%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.66%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 0.66%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.66%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.66%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.66%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.66%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 23.18%  |
| Intel Core i7           | 25        | 16.56%  |
| Other                   | 19        | 12.58%  |
| AMD Ryzen 7             | 11        | 7.28%   |
| AMD Ryzen 5             | 11        | 7.28%   |
| Intel Celeron           | 8         | 5.3%    |
| Intel Core i3           | 7         | 4.64%   |
| Intel Xeon              | 4         | 2.65%   |
| Intel Atom              | 4         | 2.65%   |
| Intel Pentium           | 3         | 1.99%   |
| Intel Core 2 Duo        | 3         | 1.99%   |
| AMD Ryzen 9             | 3         | 1.99%   |
| Intel Pentium Silver    | 2         | 1.32%   |
| AMD Ryzen 3             | 2         | 1.32%   |
| AMD A8                  | 2         | 1.32%   |
| AMD A4                  | 2         | 1.32%   |
| Intel Pentium Dual-Core | 1         | 0.66%   |
| Intel Core i9           | 1         | 0.66%   |
| Intel Core 2 Quad       | 1         | 0.66%   |
| AMD Phenom II X4        | 1         | 0.66%   |
| AMD FX                  | 1         | 0.66%   |
| AMD Athlon X4           | 1         | 0.66%   |
| AMD Athlon II X3        | 1         | 0.66%   |
| AMD Athlon              | 1         | 0.66%   |
| AMD A6                  | 1         | 0.66%   |
| AMD A10                 | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 60        | 39.74%  |
| 2      | 48        | 31.79%  |
| 8      | 18        | 11.92%  |
| 6      | 14        | 9.27%   |
| 12     | 4         | 2.65%   |
| 1      | 3         | 1.99%   |
| 10     | 2         | 1.32%   |
| 16     | 1         | 0.66%   |
| 3      | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 149       | 98.68%  |
| 2      | 2         | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 112       | 74.17%  |
| 1      | 39        | 25.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 151       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 55.77%  |
| 0x806c1    | 5         | 3.21%   |
| 0x806ec    | 4         | 2.56%   |
| 0x306a9    | 4         | 2.56%   |
| 0x08600106 | 4         | 2.56%   |
| 0x706a8    | 3         | 1.92%   |
| 0x206a7    | 3         | 1.92%   |
| 0x08108102 | 3         | 1.92%   |
| 0x806ea    | 2         | 1.28%   |
| 0x806e9    | 2         | 1.28%   |
| 0x806d1    | 2         | 1.28%   |
| 0x506e3    | 2         | 1.28%   |
| 0x406f1    | 2         | 1.28%   |
| 0x406e3    | 2         | 1.28%   |
| 0x306c3    | 2         | 1.28%   |
| 0x20655    | 2         | 1.28%   |
| 0x106e5    | 2         | 1.28%   |
| 0x0a50000c | 2         | 1.28%   |
| 0x08608103 | 2         | 1.28%   |
| 0xa0671    | 1         | 0.64%   |
| 0x906eb    | 1         | 0.64%   |
| 0x906ea    | 1         | 0.64%   |
| 0x906a3    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x506c9    | 1         | 0.64%   |
| 0x406c4    | 1         | 0.64%   |
| 0x40651    | 1         | 0.64%   |
| 0x306d4    | 1         | 0.64%   |
| 0x30678    | 1         | 0.64%   |
| 0x1067a    | 1         | 0.64%   |
| 0x10677    | 1         | 0.64%   |
| 0x0a601206 | 1         | 0.64%   |
| 0x0a201205 | 1         | 0.64%   |
| 0x0a201016 | 1         | 0.64%   |
| 0x08608104 | 1         | 0.64%   |
| 0x08600103 | 1         | 0.64%   |
| 0x08108109 | 1         | 0.64%   |
| 0x07030105 | 1         | 0.64%   |
| 0x07030104 | 1         | 0.64%   |
| 0x06001119 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 15.89%  |
| Skylake          | 12        | 7.95%   |
| Unknown          | 12        | 7.95%   |
| TigerLake        | 11        | 7.28%   |
| Zen 3            | 8         | 5.3%    |
| SandyBridge      | 8         | 5.3%    |
| IvyBridge        | 8         | 5.3%    |
| Haswell          | 8         | 5.3%    |
| Zen+             | 7         | 4.64%   |
| Zen 2            | 7         | 4.64%   |
| Penryn           | 6         | 3.97%   |
| Silvermont       | 5         | 3.31%   |
| Goldmont plus    | 5         | 3.31%   |
| Broadwell        | 5         | 3.31%   |
| IceLake          | 4         | 2.65%   |
| Westmere         | 3         | 1.99%   |
| Piledriver       | 3         | 1.99%   |
| Nehalem          | 3         | 1.99%   |
| CometLake        | 3         | 1.99%   |
| Puma             | 2         | 1.32%   |
| K10              | 2         | 1.32%   |
| Steamroller      | 1         | 0.66%   |
| Goldmont         | 1         | 0.66%   |
| Excavator        | 1         | 0.66%   |
| Bulldozer        | 1         | 0.66%   |
| Alderlake Hybrid | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 98        | 55.68%  |
| AMD    | 40        | 22.73%  |
| Nvidia | 38        | 21.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 6.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.89%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 3.89%   |
| Intel UHD Graphics 620                                                                   | 6         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.33%   |
| Intel HD Graphics 620                                                                    | 5         | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 2.22%   |
| Intel HD Graphics 530                                                                    | 4         | 2.22%   |
| AMD Lucienne                                                                             | 4         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.67%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.11%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 1.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.11%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.11%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.11%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                                           | 2         | 1.11%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.11%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.56%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                   | 1         | 0.56%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 49.01%  |
| 1 x AMD        | 31        | 20.53%  |
| 1 x Nvidia     | 18        | 11.92%  |
| Intel + Nvidia | 17        | 11.26%  |
| 2 x AMD        | 3         | 1.99%   |
| Intel + AMD    | 3         | 1.99%   |
| AMD + Nvidia   | 3         | 1.99%   |
| Other          | 1         | 0.66%   |
| 2 x Intel      | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 84.21%  |
| Proprietary | 21        | 13.82%  |
| Unknown     | 3         | 1.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 75.5%   |
| 0.01-0.5   | 9         | 5.96%   |
| 1.01-2.0   | 8         | 5.3%    |
| 3.01-4.0   | 6         | 3.97%   |
| 7.01-8.0   | 5         | 3.31%   |
| 0.51-1.0   | 5         | 3.31%   |
| 2.01-3.0   | 2         | 1.32%   |
| 16.01-24.0 | 2         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 26        | 15.29%  |
| BOE                     | 25        | 14.71%  |
| Chimei Innolux          | 24        | 14.12%  |
| AU Optronics            | 15        | 8.82%   |
| LG Display              | 10        | 5.88%   |
| Apple                   | 8         | 4.71%   |
| Goldstar                | 7         | 4.12%   |
| Hewlett-Packard         | 5         | 2.94%   |
| AOC                     | 5         | 2.94%   |
| Sharp                   | 4         | 2.35%   |
| Philips                 | 4         | 2.35%   |
| BenQ                    | 3         | 1.76%   |
| Sony                    | 2         | 1.18%   |
| SANYO                   | 2         | 1.18%   |
| PANDA                   | 2         | 1.18%   |
| Lenovo                  | 2         | 1.18%   |
| HKC                     | 2         | 1.18%   |
| Fujitsu Siemens         | 2         | 1.18%   |
| Dell                    | 2         | 1.18%   |
| Ancor Communications    | 2         | 1.18%   |
| Vizio                   | 1         | 0.59%   |
| Vestel Elektronik       | 1         | 0.59%   |
| Unknown (XXX)           | 1         | 0.59%   |
| Unknown (AAA)           | 1         | 0.59%   |
| TMX                     | 1         | 0.59%   |
| RTK                     | 1         | 0.59%   |
| Panasonic               | 1         | 0.59%   |
| ONN                     | 1         | 0.59%   |
| MStar                   | 1         | 0.59%   |
| LG Philips              | 1         | 0.59%   |
| LG Electronics          | 1         | 0.59%   |
| KDC                     | 1         | 0.59%   |
| JDZ                     | 1         | 0.59%   |
| IBM                     | 1         | 0.59%   |
| Denver                  | 1         | 0.59%   |
| Daewoo                  | 1         | 0.59%   |
| Chi Mei Optoelectronics | 1         | 0.59%   |
| Acer                    | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch        | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch        | 2         | 1.14%   |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                      | 1         | 0.57%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch    | 1         | 0.57%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.57%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                | 1         | 0.57%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                 | 1         | 0.57%   |
| Sony TV SNYEE01 1920x1080                                               | 1         | 0.57%   |
| Sony TV SNYAB03 1920x1080                                               | 1         | 0.57%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                 | 1         | 0.57%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.57%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.57%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                 | 1         | 0.57%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                  | 1         | 0.57%   |
| SANYO LCD SAN0A12 1920x540                                              | 1         | 0.57%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch    | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch    | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch    | 1         | 0.57%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch     | 1         | 0.57%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch       | 1         | 0.57%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.57%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 0.57%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 0.57%   |
| Samsung Electronics Odyssey G7 SAM72BF 3840x2160 697x392mm 31.5-inch    | 1         | 0.57%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1         | 0.57%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch     | 1         | 0.57%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1         | 0.57%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch       | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch  | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 46.88%  |
| 1366x768 (WXGA)    | 28        | 17.5%   |
| 3840x2160 (4K)     | 12        | 7.5%    |
| 2560x1440 (QHD)    | 8         | 5%      |
| 1920x1200 (WUXGA)  | 7         | 4.38%   |
| 1680x1050 (WSXGA+) | 4         | 2.5%    |
| 1600x900 (HD+)     | 4         | 2.5%    |
| 1280x800 (WXGA)    | 4         | 2.5%    |
| 3440x1440          | 3         | 1.88%   |
| 1920x540           | 3         | 1.88%   |
| 2560x1080          | 2         | 1.25%   |
| 1440x900 (WXGA+)   | 2         | 1.25%   |
| 3456x2160          | 1         | 0.63%   |
| 2880x1800          | 1         | 0.63%   |
| 2736x1824          | 1         | 0.63%   |
| 2560x1600          | 1         | 0.63%   |
| 2520x1680          | 1         | 0.63%   |
| 2240x1400          | 1         | 0.63%   |
| 1360x768           | 1         | 0.63%   |
| 1280x1024 (SXGA)   | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 49        | 28.32%  |
| 13      | 24        | 13.87%  |
| 14      | 13        | 7.51%   |
| 24      | 12        | 6.94%   |
| 27      | 11        | 6.36%   |
| 23      | 11        | 6.36%   |
| 21      | 7         | 4.05%   |
| 17      | 6         | 3.47%   |
| 34      | 5         | 2.89%   |
| 31      | 5         | 2.89%   |
| 12      | 4         | 2.31%   |
| Unknown | 4         | 2.31%   |
| 40      | 3         | 1.73%   |
| 11      | 3         | 1.73%   |
| 84      | 2         | 1.16%   |
| 72      | 2         | 1.16%   |
| 54      | 2         | 1.16%   |
| 60      | 1         | 0.58%   |
| 46      | 1         | 0.58%   |
| 33      | 1         | 0.58%   |
| 28      | 1         | 0.58%   |
| 26      | 1         | 0.58%   |
| 22      | 1         | 0.58%   |
| 20      | 1         | 0.58%   |
| 19      | 1         | 0.58%   |
| 18      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 43.53%  |
| 501-600     | 30        | 17.65%  |
| 201-300     | 19        | 11.18%  |
| 401-500     | 12        | 7.06%   |
| 601-700     | 7         | 4.12%   |
| 351-400     | 7         | 4.12%   |
| 701-800     | 6         | 3.53%   |
| 1501-2000   | 4         | 2.35%   |
| 1001-1500   | 4         | 2.35%   |
| Unknown     | 4         | 2.35%   |
| 801-900     | 3         | 1.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 120       | 78.43%  |
| 16/10   | 21        | 13.73%  |
| 21/9    | 5         | 3.27%   |
| 3/2     | 3         | 1.96%   |
| Unknown | 2         | 1.31%   |
| 4/3     | 1         | 0.65%   |
| 32/9    | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 28.82%  |
| 81-90          | 30        | 17.65%  |
| 201-250        | 23        | 13.53%  |
| 351-500        | 12        | 7.06%   |
| 301-350        | 11        | 6.47%   |
| More than 1000 | 7         | 4.12%   |
| 71-80          | 6         | 3.53%   |
| 151-200        | 5         | 2.94%   |
| 61-70          | 4         | 2.35%   |
| 251-300        | 4         | 2.35%   |
| 121-130        | 4         | 2.35%   |
| 501-1000       | 4         | 2.35%   |
| Unknown        | 4         | 2.35%   |
| 51-60          | 3         | 1.76%   |
| 41-50          | 1         | 0.59%   |
| 141-150        | 1         | 0.59%   |
| 131-140        | 1         | 0.59%   |
| 91-100         | 1         | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 33.53%  |
| 51-100        | 40        | 23.53%  |
| 101-120       | 38        | 22.35%  |
| 161-240       | 15        | 8.82%   |
| 1-50          | 9         | 5.29%   |
| More than 240 | 7         | 4.12%   |
| Unknown       | 4         | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 120       | 78.95%  |
| 2     | 30        | 19.74%  |
| 0     | 2         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 36.32%  |
| Realtek Semiconductor | 78        | 34.98%  |
| Qualcomm Atheros      | 18        | 8.07%   |
| Broadcom              | 14        | 6.28%   |
| MediaTek              | 8         | 3.59%   |
| Broadcom Limited      | 4         | 1.79%   |
| Nvidia                | 3         | 1.35%   |
| ASIX Electronics      | 3         | 1.35%   |
| Hewlett-Packard       | 2         | 0.9%    |
| Xiaomi                | 1         | 0.45%   |
| TP-Link               | 1         | 0.45%   |
| T & A Mobile Phones   | 1         | 0.45%   |
| Sierra Wireless       | 1         | 0.45%   |
| Raspberry Pi          | 1         | 0.45%   |
| Ralink Technology     | 1         | 0.45%   |
| Microsoft             | 1         | 0.45%   |
| Lenovo                | 1         | 0.45%   |
| JMicron Technology    | 1         | 0.45%   |
| Huawei Technologies   | 1         | 0.45%   |
| Fibocom               | 1         | 0.45%   |
| ASUSTek Computer      | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 47        | 17.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 4.14%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 4.14%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 3.38%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.88%   |
| Intel Wireless 8260                                                     | 5         | 1.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.88%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.13%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.13%   |
| Intel Wireless 7265                                                     | 3         | 1.13%   |
| Intel Ethernet Controller I225-V                                        | 3         | 1.13%   |
| Intel Ethernet Connection I219-V                                        | 3         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 1.13%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.75%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.75%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.75%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                    | 2         | 0.75%   |
| Intel Ethernet Connection (14) I219-V                                   | 2         | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.75%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                       | 2         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 50.38%  |
| Realtek Semiconductor | 23        | 17.29%  |
| Qualcomm Atheros      | 14        | 10.53%  |
| Broadcom              | 12        | 9.02%   |
| MediaTek              | 8         | 6.02%   |
| Broadcom Limited      | 2         | 1.5%    |
| TP-Link               | 1         | 0.75%   |
| Sierra Wireless       | 1         | 0.75%   |
| Ralink Technology     | 1         | 0.75%   |
| Microsoft             | 1         | 0.75%   |
| Hewlett-Packard       | 1         | 0.75%   |
| Fibocom               | 1         | 0.75%   |
| ASUSTek Computer      | 1         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 11        | 8.27%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 6.77%   |
| Intel Wireless 8265 / 8275                                              | 8         | 6.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.76%   |
| Intel Wireless 8260                                                     | 5         | 3.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 3.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 3.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 3.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.26%   |
| Intel Wireless 7265                                                     | 3         | 2.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 2.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.5%    |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.75%   |
| Sierra Wireless EM7455                                                  | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.75%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.75%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.75%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 69        | 54.33%  |
| Intel                 | 34        | 26.77%  |
| Broadcom              | 7         | 5.51%   |
| Qualcomm Atheros      | 4         | 3.15%   |
| Nvidia                | 3         | 2.36%   |
| ASIX Electronics      | 3         | 2.36%   |
| Broadcom Limited      | 2         | 1.57%   |
| Xiaomi                | 1         | 0.79%   |
| T & A Mobile Phones   | 1         | 0.79%   |
| Lenovo                | 1         | 0.79%   |
| JMicron Technology    | 1         | 0.79%   |
| Hewlett-Packard       | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 47        | 35.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 8.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 5.34%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 3.05%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 2.29%   |
| Intel Ethernet Controller I225-V                                       | 3         | 2.29%   |
| Intel Ethernet Connection I219-V                                       | 3         | 2.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 2.29%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 2.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.53%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 1.53%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.53%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 1.53%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.76%   |
| T & A Mobile Phones TCL 20E                                            | 1         | 0.76%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.76%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.76%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.76%   |
| Lenovo ThinkPad Lan                                                    | 1         | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.76%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.76%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 0.76%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.76%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.76%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.76%   |
| Intel 82578DC Gigabit Network Connection                               | 1         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 128       | 50.79%  |
| Ethernet | 122       | 48.41%  |
| Modem    | 2         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 64.29%  |
| Ethernet | 55        | 35.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 87        | 57.62%  |
| 1     | 59        | 39.07%  |
| 0     | 5         | 3.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 69.48%  |
| Yes  | 47        | 30.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 54.21%  |
| Apple                           | 9         | 8.41%   |
| Realtek Semiconductor           | 8         | 7.48%   |
| Qualcomm Atheros Communications | 7         | 6.54%   |
| Broadcom                        | 7         | 6.54%   |
| IMC Networks                    | 6         | 5.61%   |
| Cambridge Silicon Radio         | 3         | 2.8%    |
| MediaTek                        | 2         | 1.87%   |
| Dell                            | 2         | 1.87%   |
| Smart Modular Technologies      | 1         | 0.93%   |
| Realtek                         | 1         | 0.93%   |
| Lite-On Technology              | 1         | 0.93%   |
| Foxconn International           | 1         | 0.93%   |
| Foxconn / Hon Hai               | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 16.82%  |
| Intel AX201 Bluetooth                               | 15        | 14.02%  |
| Intel AX200 Bluetooth                               | 11        | 10.28%  |
| Realtek Bluetooth Radio                             | 6         | 5.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.67%   |
| Intel AX210 Bluetooth                               | 5         | 4.67%   |
| Apple Bluetooth USB Host Controller                 | 5         | 4.67%   |
| IMC Networks Wireless_Device                        | 4         | 3.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.8%    |
| Apple Bluetooth Host Controller                     | 3         | 2.8%    |
| MediaTek Wireless_Device                            | 2         | 1.87%   |
| Intel Bluetooth Device                              | 2         | 1.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.87%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.87%   |
| Smart Modular Bluetooth Device                      | 1         | 0.93%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.93%   |
| Realtek Bluetooth Radio                             | 1         | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.93%   |
| Lite-On Bluetooth Radio                             | 1         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.93%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.93%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.93%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.93%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.93%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.93%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 106       | 54.64%  |
| AMD                     | 43        | 22.16%  |
| Nvidia                  | 26        | 13.4%   |
| Plantronics             | 3         | 1.55%   |
| Logitech                | 3         | 1.55%   |
| DSEA A/S                | 2         | 1.03%   |
| Texas Instruments       | 1         | 0.52%   |
| Shure                   | 1         | 0.52%   |
| Realtek Semiconductor   | 1         | 0.52%   |
| LINE TECH INDUSTRIAL    | 1         | 0.52%   |
| GN Netcom               | 1         | 0.52%   |
| Creative Technology     | 1         | 0.52%   |
| ClearOne Communications | 1         | 0.52%   |
| ASUSTek Computer        | 1         | 0.52%   |
| Arturia                 | 1         | 0.52%   |
| Apple                   | 1         | 0.52%   |
| AKAI Professional M.I.  | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 9.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 8.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 6.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 4.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 3.39%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 2.12%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 2.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.27%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.27%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.85%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.85%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.85%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.85%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.85%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 27.18%  |
| SK hynix            | 23        | 22.33%  |
| Kingston            | 13        | 12.62%  |
| Micron Technology   | 9         | 8.74%   |
| Crucial             | 9         | 8.74%   |
| Elpida              | 4         | 3.88%   |
| Unknown (ABCD)      | 2         | 1.94%   |
| Ramaxel Technology  | 2         | 1.94%   |
| Corsair             | 2         | 1.94%   |
| A-DATA Technology   | 2         | 1.94%   |
| Unknown             | 1         | 0.97%   |
| Transcend           | 1         | 0.97%   |
| Teikon              | 1         | 0.97%   |
| Nanya Technology    | 1         | 0.97%   |
| Magnum Tech         | 1         | 0.97%   |
| G.Skill             | 1         | 0.97%   |
| fef5                | 1         | 0.97%   |
| ChangXin Memory     | 1         | 0.97%   |
| 8945000080AD        | 1         | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 4         | 3.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 2.73%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.82%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s               | 2         | 1.82%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 2         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                         | 1         | 0.91%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s                  | 1         | 0.91%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s              | 1         | 0.91%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.91%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                        | 1         | 0.91%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 0.91%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                | 1         | 0.91%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                          | 1         | 0.91%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                       | 1         | 0.91%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.91%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.91%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s                | 1         | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.91%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.91%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.91%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.91%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.91%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.91%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s                | 1         | 0.91%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s       | 1         | 0.91%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                            | 1         | 0.91%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s    | 1         | 0.91%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.91%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 1         | 0.91%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.91%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                           | 1         | 0.91%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 0.91%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.91%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 55.81%  |
| DDR3    | 22        | 25.58%  |
| LPDDR4  | 10        | 11.63%  |
| SDRAM   | 2         | 2.33%   |
| LPDDR3  | 2         | 2.33%   |
| DDR5    | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 70.24%  |
| DIMM         | 15        | 17.86%  |
| Row Of Chips | 7         | 8.33%   |
| Unknown      | 2         | 2.38%   |
| Chip         | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 37        | 42.05%  |
| 4096  | 19        | 21.59%  |
| 16384 | 15        | 17.05%  |
| 2048  | 8         | 9.09%   |
| 32768 | 7         | 7.95%   |
| 1024  | 2         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 22        | 23.4%   |
| 1600  | 16        | 17.02%  |
| 2667  | 15        | 15.96%  |
| 2400  | 11        | 11.7%   |
| 2133  | 5         | 5.32%   |
| 1333  | 5         | 5.32%   |
| 4267  | 3         | 3.19%   |
| 1067  | 3         | 3.19%   |
| 1867  | 2         | 2.13%   |
| 1334  | 2         | 2.13%   |
| 1066  | 2         | 2.13%   |
| 6000  | 1         | 1.06%   |
| 4266  | 1         | 1.06%   |
| 4199  | 1         | 1.06%   |
| 3733  | 1         | 1.06%   |
| 3600  | 1         | 1.06%   |
| 3266  | 1         | 1.06%   |
| 3000  | 1         | 1.06%   |
| 2933  | 1         | 1.06%   |

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
| Chicony Electronics                    | 30        | 29.13%  |
| Realtek Semiconductor                  | 9         | 8.74%   |
| IMC Networks                           | 9         | 8.74%   |
| Apple                                  | 7         | 6.8%    |
| Microdia                               | 6         | 5.83%   |
| Sunplus Innovation Technology          | 5         | 4.85%   |
| Luxvisions Innotech Limited            | 5         | 4.85%   |
| Logitech                               | 5         | 4.85%   |
| Acer                                   | 4         | 3.88%   |
| Syntek                                 | 3         | 2.91%   |
| Quanta                                 | 3         | 2.91%   |
| Bison Electronics                      | 3         | 2.91%   |
| Samsung Electronics                    | 2         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.94%   |
| WaveRider Communications               | 1         | 0.97%   |
| ValueHD                                | 1         | 0.97%   |
| Unknown (3730304233333731323245)       | 1         | 0.97%   |
| Unknown                                | 1         | 0.97%   |
| Polycom                                | 1         | 0.97%   |
| Pixart Imaging                         | 1         | 0.97%   |
| Generalplus Technology                 | 1         | 0.97%   |
| Alcor Micro                            | 1         | 0.97%   |
| 8SSC21D67422V1SR3AV5KW1                | 1         | 0.97%   |
| Unknown                                | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 6         | 5.83%   |
| Realtek Integrated_Webcam_HD                         | 4         | 3.88%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 3.88%   |
| Chicony Integrated Camera                            | 4         | 3.88%   |
| Chicony HP HD Camera                                 | 4         | 3.88%   |
| Microdia Integrated_Webcam_HD                        | 3         | 2.91%   |
| Logitech HD Pro Webcam C920                          | 3         | 2.91%   |
| IMC Networks Integrated Camera                       | 3         | 2.91%   |
| Chicony USB2.0 Camera                                | 3         | 2.91%   |
| Apple FaceTime HD Camera                             | 3         | 2.91%   |
| Acer SunplusIT Integrated Camera                     | 3         | 2.91%   |
| Syntek Integrated Camera                             | 2         | 1.94%   |
| Sunplus FHD Camera Microphone                        | 2         | 1.94%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 1.94%   |
| Realtek USB Camera                                   | 2         | 1.94%   |
| Quanta USB2.0 HD UVC WebCam                          | 2         | 1.94%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 1.94%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 1.94%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.94%   |
| Bison EasyCamera                                     | 2         | 1.94%   |
| Apple Built-in iSight                                | 2         | 1.94%   |
| WaveRider USB 2.0 Camera                             | 1         | 0.97%   |
| ValueHD Konftel Cam20                                | 1         | 0.97%   |
| Unknown ATIV VGA CAMERA                              | 1         | 0.97%   |
| Unknown (3730304233333731323245) USB Camera          | 1         | 0.97%   |
| Syntek Lenovo EasyCamera                             | 1         | 0.97%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.97%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.97%   |
| Sunplus HD WebCam                                    | 1         | 0.97%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 0.97%   |
| Realtek Lenovo EasyCamera                            | 1         | 0.97%   |
| Realtek Integrated Webcam                            | 1         | 0.97%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 0.97%   |
| Polycom Poly Studio P5 webcam                        | 1         | 0.97%   |
| Pixart Imaging USB_2.0_Webcam                        | 1         | 0.97%   |
| Microdia Lenovo EasyCamera                           | 1         | 0.97%   |
| Microdia Integrated Webcam HD                        | 1         | 0.97%   |
| Microdia Camera                                      | 1         | 0.97%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.97%   |
| Logitech StreamCam                                   | 1         | 0.97%   |

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
| 0     | 101       | 66.01%  |
| 1     | 37        | 24.18%  |
| 2     | 11        | 7.19%   |
| 3     | 2         | 1.31%   |
| 7     | 1         | 0.65%   |
| 4     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 35.82%  |
| Net/wireless             | 8         | 11.94%  |
| Graphics card            | 7         | 10.45%  |
| Chipcard                 | 5         | 7.46%   |
| Sound                    | 4         | 5.97%   |
| Communication controller | 4         | 5.97%   |
| Camera                   | 4         | 5.97%   |
| Unassigned class         | 3         | 4.48%   |
| Multimedia controller    | 3         | 4.48%   |
| Card reader              | 2         | 2.99%   |
| Bluetooth                | 2         | 2.99%   |
| Net/ethernet             | 1         | 1.49%   |


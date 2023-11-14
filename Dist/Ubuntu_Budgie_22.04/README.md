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

Total: 190

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-27-generic      | 11        | 7.14%   |
| 5.15.0-52-generic      | 9         | 5.84%   |
| 5.15.0-50-generic      | 7         | 4.55%   |
| 5.15.0-48-generic      | 6         | 3.9%    |
| 5.15.0-30-generic      | 6         | 3.9%    |
| 5.19.0-46-generic      | 5         | 3.25%   |
| 5.15.0-46-generic      | 5         | 3.25%   |
| 5.15.0-43-generic      | 5         | 3.25%   |
| 5.15.0-39-generic      | 5         | 3.25%   |
| 6.2.0-26-generic       | 4         | 2.6%    |
| 5.19.0-35-generic      | 4         | 2.6%    |
| 5.15.0-57-generic      | 4         | 2.6%    |
| 5.15.0-56-generic      | 4         | 2.6%    |
| 5.15.0-33-generic      | 4         | 2.6%    |
| 5.15.0-25-generic      | 4         | 2.6%    |
| 6.2.0-33-generic       | 3         | 1.95%   |
| 5.19.0-45-generic      | 3         | 1.95%   |
| 5.19.0-41-generic      | 3         | 1.95%   |
| 5.19.0-40-generic      | 3         | 1.95%   |
| 5.15.0-58-generic      | 3         | 1.95%   |
| 5.15.0-53-generic      | 3         | 1.95%   |
| 5.15.0-47-generic      | 3         | 1.95%   |
| 5.15.0-40-generic      | 3         | 1.95%   |
| 6.2.0-32-generic       | 2         | 1.3%    |
| 6.2.0-10007-tuxedo     | 2         | 1.3%    |
| 5.19.0-42-generic      | 2         | 1.3%    |
| 5.19.0-38-generic      | 2         | 1.3%    |
| 5.15.0-67-generic      | 2         | 1.3%    |
| 5.15.0-41-generic      | 2         | 1.3%    |
| 6.3.1-060301-generic   | 1         | 0.65%   |
| 6.2.0-35-generic       | 1         | 0.65%   |
| 6.2.0-10018-tuxedo     | 1         | 0.65%   |
| 6.1.0-060100-generic   | 1         | 0.65%   |
| 5.19.0-50-generic      | 1         | 0.65%   |
| 5.19.0-32-generic      | 1         | 0.65%   |
| 5.19.0-051900-generic  | 1         | 0.65%   |
| 5.17.2-051702-generic  | 1         | 0.65%   |
| 5.16.2                 | 1         | 0.65%   |
| 5.15.92-051592-generic | 1         | 0.65%   |
| 5.15.0-88-lowlatency   | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 100       | 69.44%  |
| 5.19.0  | 24        | 16.67%  |
| 6.2.0   | 12        | 8.33%   |
| 5.13.0  | 3         | 2.08%   |
| 6.3.1   | 1         | 0.69%   |
| 6.1.0   | 1         | 0.69%   |
| 5.17.2  | 1         | 0.69%   |
| 5.16.2  | 1         | 0.69%   |
| 5.15.92 | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 101       | 70.14%  |
| 5.19    | 24        | 16.67%  |
| 6.2     | 12        | 8.33%   |
| 5.13    | 3         | 2.08%   |
| 6.3     | 1         | 0.69%   |
| 6.1     | 1         | 0.69%   |
| 5.17    | 1         | 0.69%   |
| 5.16    | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 139       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 134       | 96.4%   |
| GNOME  | 5         | 3.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 135       | 97.12%  |
| Wayland | 4         | 2.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 98        | 70.5%   |
| Unknown | 27        | 19.42%  |
| GDM3    | 13        | 9.35%   |
| GDM     | 1         | 0.72%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 53        | 38.13%  |
| de_DE | 19        | 13.67%  |
| fr_FR | 12        | 8.63%   |
| pt_BR | 9         | 6.47%   |
| en_GB | 8         | 5.76%   |
| es_ES | 4         | 2.88%   |
| en_CA | 4         | 2.88%   |
| it_IT | 3         | 2.16%   |
| fr_BE | 3         | 2.16%   |
| en_AU | 3         | 2.16%   |
| ru_RU | 2         | 1.44%   |
| hu_HU | 2         | 1.44%   |
| es_MX | 2         | 1.44%   |
| en_IE | 2         | 1.44%   |
| pl_PL | 1         | 0.72%   |
| mt_MT | 1         | 0.72%   |
| ja_JP | 1         | 0.72%   |
| es_PE | 1         | 0.72%   |
| es_EC | 1         | 0.72%   |
| es_CL | 1         | 0.72%   |
| es_AR | 1         | 0.72%   |
| en_ZA | 1         | 0.72%   |
| en_SG | 1         | 0.72%   |
| en_NZ | 1         | 0.72%   |
| el_GR | 1         | 0.72%   |
| cs_CZ | 1         | 0.72%   |
| C     | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 83        | 59.29%  |
| EFI  | 57        | 40.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 121       | 85.82%  |
| Tmpfs   | 6         | 4.26%   |
| Overlay | 6         | 4.26%   |
| Zfs     | 4         | 2.84%   |
| Btrfs   | 3         | 2.13%   |
| Xfs     | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 88        | 62.86%  |
| Unknown | 45        | 32.14%  |
| MBR     | 7         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 84.89%  |
| Yes       | 21        | 15.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 66.43%  |
| Yes       | 47        | 33.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 15.83%  |
| Hewlett-Packard        | 20        | 14.39%  |
| Dell                   | 17        | 12.23%  |
| ASUSTek Computer       | 16        | 11.51%  |
| Gigabyte Technology    | 10        | 7.19%   |
| TUXEDO                 | 9         | 6.47%   |
| MSI                    | 9         | 6.47%   |
| Apple                  | 8         | 5.76%   |
| Intel                  | 4         | 2.88%   |
| Fujitsu                | 3         | 2.16%   |
| ASRock                 | 3         | 2.16%   |
| Google                 | 2         | 1.44%   |
| AZW                    | 2         | 1.44%   |
| Acer                   | 2         | 1.44%   |
| Toshiba                | 1         | 0.72%   |
| Timi                   | 1         | 0.72%   |
| Samsung Electronics    | 1         | 0.72%   |
| Razer                  | 1         | 0.72%   |
| HUAWEI                 | 1         | 0.72%   |
| Digibras               | 1         | 0.72%   |
| COM1                   | 1         | 0.72%   |
| Chuwi                  | 1         | 0.72%   |
| Biostar                | 1         | 0.72%   |
| BANGHO                 | 1         | 0.72%   |
| AXIOO                  | 1         | 0.72%   |
| Avell High Performance | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 1.44%   |
| Lenovo G50-45 80E3                                   | 2         | 1.44%   |
| HP EliteBook 840 G3                                  | 2         | 1.44%   |
| AZW SER                                              | 2         | 1.44%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.72%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.72%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 0.72%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.72%   |
| TUXEDO Book XP1511                                   | 1         | 0.72%   |
| TUXEDO Book BA1510                                   | 1         | 0.72%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.72%   |
| Toshiba Satellite A505                               | 1         | 0.72%   |
| Timi TM1604                                          | 1         | 0.72%   |
| Samsung 740U3M                                       | 1         | 0.72%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.72%   |
| MSI MS-7C95                                          | 1         | 0.72%   |
| MSI MS-7C51                                          | 1         | 0.72%   |
| MSI MS-7B86                                          | 1         | 0.72%   |
| MSI MS-7A32                                          | 1         | 0.72%   |
| MSI MS-7885                                          | 1         | 0.72%   |
| MSI MS-7721                                          | 1         | 0.72%   |
| MSI Modern 15 A10M                                   | 1         | 0.72%   |
| MSI GL62 6QF                                         | 1         | 0.72%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.72%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.72%   |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 0.72%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 0.72%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 0.72%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 0.72%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 0.72%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 0.72%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 0.72%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 0.72%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 0.72%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 0.72%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9                     | 1         | 0.72%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 0.72%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 0.72%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 0.72%   |
| Lenovo IdeaPad 520-15IKB 81BF                        | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 5.76%   |
| Lenovo IdeaPad      | 7         | 5.04%   |
| Dell Latitude       | 5         | 3.6%    |
| Dell Inspiron       | 5         | 3.6%    |
| HP EliteBook        | 4         | 2.88%   |
| ASUS VivoBook       | 4         | 2.88%   |
| TUXEDO Book         | 3         | 2.16%   |
| HP ProBook          | 3         | 2.16%   |
| HP Pavilion         | 3         | 2.16%   |
| TUXEDO Pulse        | 2         | 1.44%   |
| TUXEDO InfinityBook | 2         | 1.44%   |
| Lenovo G50-45       | 2         | 1.44%   |
| HP EliteDesk        | 2         | 1.44%   |
| Fujitsu ESPRIMO     | 2         | 1.44%   |
| Dell XPS            | 2         | 1.44%   |
| Dell Precision      | 2         | 1.44%   |
| Dell OptiPlex       | 2         | 1.44%   |
| AZW SER             | 2         | 1.44%   |
| ASUS ROG            | 2         | 1.44%   |
| Acer Aspire         | 2         | 1.44%   |
| TUXEDO Polaris      | 1         | 0.72%   |
| TUXEDO Aura         | 1         | 0.72%   |
| Toshiba Satellite   | 1         | 0.72%   |
| Timi TM1604         | 1         | 0.72%   |
| Samsung 740U3M      | 1         | 0.72%   |
| Razer Blade         | 1         | 0.72%   |
| MSI MS-7C95         | 1         | 0.72%   |
| MSI MS-7C51         | 1         | 0.72%   |
| MSI MS-7B86         | 1         | 0.72%   |
| MSI MS-7A32         | 1         | 0.72%   |
| MSI MS-7885         | 1         | 0.72%   |
| MSI MS-7721         | 1         | 0.72%   |
| MSI Modern          | 1         | 0.72%   |
| MSI GL62            | 1         | 0.72%   |
| MSI Alpha           | 1         | 0.72%   |
| Lenovo V15          | 1         | 0.72%   |
| Lenovo ThinkStation | 1         | 0.72%   |
| Lenovo Legion       | 1         | 0.72%   |
| Lenovo IdeaPadFlex  | 1         | 0.72%   |
| Lenovo G500         | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 20        | 14.39%  |
| 2020 | 18        | 12.95%  |
| 2014 | 15        | 10.79%  |
| 2018 | 12        | 8.63%   |
| 2016 | 12        | 8.63%   |
| 2019 | 11        | 7.91%   |
| 2022 | 9         | 6.47%   |
| 2017 | 7         | 5.04%   |
| 2015 | 7         | 5.04%   |
| 2010 | 6         | 4.32%   |
| 2013 | 5         | 3.6%    |
| 2011 | 5         | 3.6%    |
| 2012 | 4         | 2.88%   |
| 2009 | 4         | 2.88%   |
| 2008 | 3         | 2.16%   |
| 2023 | 1         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 86        | 61.87%  |
| Desktop     | 38        | 27.34%  |
| Convertible | 6         | 4.32%   |
| Mini pc     | 5         | 3.6%    |
| All in one  | 3         | 2.16%   |
| Tablet      | 1         | 0.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 132       | 94.96%  |
| Enabled  | 7         | 5.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 97.84%  |
| Yes  | 3         | 2.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 39        | 27.86%  |
| 16.01-24.0      | 38        | 27.14%  |
| 8.01-16.0       | 26        | 18.57%  |
| 32.01-64.0      | 12        | 8.57%   |
| 3.01-4.0        | 12        | 8.57%   |
| 64.01-256.0     | 6         | 4.29%   |
| 24.01-32.0      | 4         | 2.86%   |
| 1.01-2.0        | 2         | 1.43%   |
| More than 256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 49        | 33.33%  |
| 1.01-2.0   | 39        | 26.53%  |
| 4.01-8.0   | 26        | 17.69%  |
| 3.01-4.0   | 17        | 11.56%  |
| 8.01-16.0  | 11        | 7.48%   |
| 16.01-24.0 | 3         | 2.04%   |
| 24.01-32.0 | 2         | 1.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 60.28%  |
| 2      | 38        | 26.95%  |
| 3      | 9         | 6.38%   |
| 4      | 5         | 3.55%   |
| 6      | 2         | 1.42%   |
| 8      | 1         | 0.71%   |
| 7      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 74.1%   |
| Yes       | 36        | 25.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 80.71%  |
| No        | 27        | 19.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 84.89%  |
| No        | 21        | 15.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 71.94%  |
| No        | 39        | 28.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 27        | 19.42%  |
| Germany            | 21        | 15.11%  |
| France             | 13        | 9.35%   |
| Brazil             | 11        | 7.91%   |
| UK                 | 5         | 3.6%    |
| Spain              | 3         | 2.16%   |
| Poland             | 3         | 2.16%   |
| Italy              | 3         | 2.16%   |
| Canada             | 3         | 2.16%   |
| Belgium            | 3         | 2.16%   |
| Austria            | 3         | 2.16%   |
| Australia          | 3         | 2.16%   |
| Argentina          | 3         | 2.16%   |
| Switzerland        | 2         | 1.44%   |
| Slovenia           | 2         | 1.44%   |
| Romania            | 2         | 1.44%   |
| Netherlands        | 2         | 1.44%   |
| Mexico             | 2         | 1.44%   |
| Ireland            | 2         | 1.44%   |
| Hungary            | 2         | 1.44%   |
| Greece             | 2         | 1.44%   |
| Sweden             | 1         | 0.72%   |
| South Africa       | 1         | 0.72%   |
| Singapore          | 1         | 0.72%   |
| Saudi Arabia       | 1         | 0.72%   |
| Russia             | 1         | 0.72%   |
| Peru               | 1         | 0.72%   |
| Norway             | 1         | 0.72%   |
| New Zealand        | 1         | 0.72%   |
| Malta              | 1         | 0.72%   |
| Japan              | 1         | 0.72%   |
| Indonesia          | 1         | 0.72%   |
| Ghana              | 1         | 0.72%   |
| Ecuador            | 1         | 0.72%   |
| Dominican Republic | 1         | 0.72%   |
| Czechia            | 1         | 0.72%   |
| Cuba               | 1         | 0.72%   |
| Croatia            | 1         | 0.72%   |
| Chile              | 1         | 0.72%   |
| Cabo Verde         | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Berlin                | 4         | 2.8%    |
| Brasília             | 3         | 2.1%    |
| Warsaw                | 2         | 1.4%    |
| Vienna                | 2         | 1.4%    |
| Victoria              | 2         | 1.4%    |
| Milwaukee             | 2         | 1.4%    |
| London                | 2         | 1.4%    |
| Frankfurt am Main     | 2         | 1.4%    |
| Dublin                | 2         | 1.4%    |
| Budapest              | 2         | 1.4%    |
| Athens                | 2         | 1.4%    |
| Zurich                | 1         | 0.7%    |
| West Lafayette        | 1         | 0.7%    |
| Wertheim am Main      | 1         | 0.7%    |
| Weisswasser           | 1         | 0.7%    |
| Weilheim              | 1         | 0.7%    |
| Washington            | 1         | 0.7%    |
| Walled Lake           | 1         | 0.7%    |
| Venray                | 1         | 0.7%    |
| Trondheim             | 1         | 0.7%    |
| Torun                 | 1         | 0.7%    |
| Tocantins             | 1         | 0.7%    |
| Targu Frumos          | 1         | 0.7%    |
| Tarakan               | 1         | 0.7%    |
| Tann                  | 1         | 0.7%    |
| Tampa                 | 1         | 0.7%    |
| Sunnyvale             | 1         | 0.7%    |
| St Petersburg         | 1         | 0.7%    |
| Sofia                 | 1         | 0.7%    |
| Singapore             | 1         | 0.7%    |
| Siegen                | 1         | 0.7%    |
| Shirakuni             | 1         | 0.7%    |
| Sétif                | 1         | 0.7%    |
| Seelze                | 1         | 0.7%    |
| Seattle               | 1         | 0.7%    |
| Sao Paulo             | 1         | 0.7%    |
| Sao Bernardo do Campo | 1         | 0.7%    |
| Santo Domingo Este    | 1         | 0.7%    |
| Santiago              | 1         | 0.7%    |
| San Luis Potosí City | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 37        | 62     | 17.87%  |
| Seagate                        | 22        | 30     | 10.63%  |
| WDC                            | 17        | 19     | 8.21%   |
| Crucial                        | 14        | 19     | 6.76%   |
| Unknown                        | 13        | 13     | 6.28%   |
| Toshiba                        | 13        | 16     | 6.28%   |
| Micron Technology              | 10        | 10     | 4.83%   |
| SK hynix                       | 8         | 8      | 3.86%   |
| SanDisk                        | 8         | 9      | 3.86%   |
| Kingston                       | 6         | 7      | 2.9%    |
| Intel                          | 6         | 8      | 2.9%    |
| SPCC                           | 4         | 4      | 1.93%   |
| China                          | 4         | 5      | 1.93%   |
| A-DATA Technology              | 4         | 5      | 1.93%   |
| OCZ                            | 3         | 3      | 1.45%   |
| JMicron Technology             | 3         | 3      | 1.45%   |
| Apple                          | 3         | 3      | 1.45%   |
| Transcend                      | 2         | 2      | 0.97%   |
| PNY                            | 2         | 2      | 0.97%   |
| Phison                         | 2         | 2      | 0.97%   |
| HGST                           | 2         | 2      | 0.97%   |
| Zheino                         | 1         | 1      | 0.48%   |
| YMTC                           | 1         | 1      | 0.48%   |
| VISIPRO                        | 1         | 1      | 0.48%   |
| Union Memory                   | 1         | 1      | 0.48%   |
| TO Exter                       | 1         | 1      | 0.48%   |
| Solid State Storage Technology | 1         | 1      | 0.48%   |
| SABRENT                        | 1         | 1      | 0.48%   |
| Realtek Semiconductor          | 1         | 1      | 0.48%   |
| Phison Electronics             | 1         | 1      | 0.48%   |
| OWC                            | 1         | 1      | 0.48%   |
| Netac                          | 1         | 1      | 0.48%   |
| Mushkin                        | 1         | 1      | 0.48%   |
| Micron/Crucial Technology      | 1         | 1      | 0.48%   |
| MicroFrom                      | 1         | 1      | 0.48%   |
| Maxtor                         | 1         | 1      | 0.48%   |
| LITEON                         | 1         | 1      | 0.48%   |
| KIOXIA                         | 1         | 1      | 0.48%   |
| Kingston Technology Company    | 1         | 1      | 0.48%   |
| Intenso                        | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 3         | 1.33%   |
| Crucial CT480BX500SSD1 480GB                      | 3         | 1.33%   |
| Crucial CT240BX500SSD1 240GB                      | 3         | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 0.89%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.89%   |
| Unknown SD64G  64GB                               | 2         | 0.89%   |
| Unknown SD/MMC/MS PRO 16GB                        | 2         | 0.89%   |
| Unknown MMC Card  64GB                            | 2         | 0.89%   |
| Unknown MMC Card  128GB                           | 2         | 0.89%   |
| Seagate ST3500418AS 500GB                         | 2         | 0.89%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB                    | 2         | 0.89%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 2         | 0.89%   |
| SanDisk SDSSDA120G 120GB                          | 2         | 0.89%   |
| Samsung SSD 980 PRO 2TB                           | 2         | 0.89%   |
| Samsung SSD 980 500GB                             | 2         | 0.89%   |
| Samsung SSD 870 EVO 250GB                         | 2         | 0.89%   |
| Samsung SSD 860 EVO M.2 500GB                     | 2         | 0.89%   |
| Samsung SSD 850 PRO 256GB                         | 2         | 0.89%   |
| Samsung SSD 850 EVO 500GB                         | 2         | 0.89%   |
| Samsung SSD 840 EVO 250GB                         | 2         | 0.89%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 2         | 0.89%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 2         | 0.89%   |
| JMicron Generic 256GB                             | 2         | 0.89%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 0.89%   |
| Zheino CHN-25SATAC3-120 120GB SSD                 | 1         | 0.44%   |
| YMTC PC005 1TB                                    | 1         | 0.44%   |
| WDC WD40PURZ-85TTDY0 4TB                          | 1         | 0.44%   |
| WDC WD40EZAZ-00SF3B0 4TB                          | 1         | 0.44%   |
| WDC WD3200LPVX-22V0TT0 320GB                      | 1         | 0.44%   |
| WDC WD20EARX-00PASB0 2TB                          | 1         | 0.44%   |
| WDC WD1600AAJS-60WAA0 160GB                       | 1         | 0.44%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1         | 0.44%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 1         | 0.44%   |
| WDC WD10EARS-00Y5B1 1TB                           | 1         | 0.44%   |
| WDC WD10EADS-00M2B0 1TB                           | 1         | 0.44%   |
| WDC WD1003FZEX-00MK2A0 1TB                        | 1         | 0.44%   |
| WDC PC SN730 NVMe 256GB                           | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 29     | 41.51%  |
| WDC                 | 13        | 14     | 24.53%  |
| Toshiba             | 8         | 8      | 15.09%  |
| Samsung Electronics | 3         | 4      | 5.66%   |
| Unknown             | 2         | 2      | 3.77%   |
| HGST                | 2         | 2      | 3.77%   |
| Maxtor              | 1         | 1      | 1.89%   |
| ASMT109x            | 1         | 1      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 33     | 20%     |
| Crucial             | 13        | 18     | 17.33%  |
| SanDisk             | 5         | 5      | 6.67%   |
| Micron Technology   | 4         | 4      | 5.33%   |
| China               | 4         | 5      | 5.33%   |
| SPCC                | 3         | 3      | 4%      |
| Kingston            | 3         | 4      | 4%      |
| WDC                 | 2         | 2      | 2.67%   |
| SK hynix            | 2         | 2      | 2.67%   |
| PNY                 | 2         | 2      | 2.67%   |
| OCZ                 | 2         | 2      | 2.67%   |
| Apple               | 2         | 2      | 2.67%   |
| A-DATA Technology   | 2         | 2      | 2.67%   |
| Zheino              | 1         | 1      | 1.33%   |
| VISIPRO             | 1         | 1      | 1.33%   |
| Union Memory        | 1         | 1      | 1.33%   |
| Transcend           | 1         | 1      | 1.33%   |
| Toshiba             | 1         | 1      | 1.33%   |
| TO Exter            | 1         | 1      | 1.33%   |
| SABRENT             | 1         | 1      | 1.33%   |
| OWC                 | 1         | 1      | 1.33%   |
| Netac               | 1         | 1      | 1.33%   |
| Mushkin             | 1         | 1      | 1.33%   |
| MicroFrom           | 1         | 1      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |
| Intel               | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |
| Corsair             | 1         | 2      | 1.33%   |
| 4Life               | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 66        | 101    | 35.48%  |
| NVMe    | 62        | 77     | 33.33%  |
| HDD     | 43        | 62     | 23.12%  |
| MMC     | 13        | 15     | 6.99%   |
| Unknown | 2         | 2      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 157    | 51.19%  |
| NVMe | 61        | 75     | 36.31%  |
| MMC  | 13        | 15     | 7.74%   |
| SAS  | 8         | 10     | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 103    | 59.32%  |
| 0.51-1.0   | 31        | 40     | 26.27%  |
| 1.01-2.0   | 10        | 11     | 8.47%   |
| 3.01-4.0   | 6         | 7      | 5.08%   |
| 4.01-10.0  | 1         | 2      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 30.22%  |
| 251-500        | 37        | 26.62%  |
| 501-1000       | 18        | 12.95%  |
| 51-100         | 13        | 9.35%   |
| 1001-2000      | 10        | 7.19%   |
| 1-20           | 6         | 4.32%   |
| More than 3000 | 5         | 3.6%    |
| 21-50          | 5         | 3.6%    |
| 2001-3000      | 3         | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 38        | 26.76%  |
| 21-50          | 36        | 25.35%  |
| 101-250        | 24        | 16.9%   |
| 51-100         | 20        | 14.08%  |
| 251-500        | 10        | 7.04%   |
| 1001-2000      | 7         | 4.93%   |
| 501-1000       | 5         | 3.52%   |
| More than 3000 | 1         | 0.7%    |
| 2001-3000      | 1         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 25%     |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 25%     |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 85        | 158    | 56.29%  |
| Works    | 61        | 94     | 40.4%   |
| Malfunc  | 4         | 4      | 2.65%   |
| Failed   | 1         | 1      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 85        | 48.57%  |
| AMD                            | 25        | 14.29%  |
| Samsung Electronics            | 22        | 12.57%  |
| Micron Technology              | 6         | 3.43%   |
| SanDisk                        | 5         | 2.86%   |
| SK hynix                       | 4         | 2.29%   |
| Kingston Technology Company    | 4         | 2.29%   |
| Toshiba America Info Systems   | 3         | 1.71%   |
| Phison Electronics             | 3         | 1.71%   |
| Nvidia                         | 3         | 1.71%   |
| Micron/Crucial Technology      | 2         | 1.14%   |
| Marvell Technology Group       | 2         | 1.14%   |
| KIOXIA                         | 2         | 1.14%   |
| ADATA Technology               | 2         | 1.14%   |
| Yangtze Memory Technologies    | 1         | 0.57%   |
| Transcend                      | 1         | 0.57%   |
| Solid State Storage Technology | 1         | 0.57%   |
| Seagate Technology             | 1         | 0.57%   |
| Realtek Semiconductor          | 1         | 0.57%   |
| OCZ Technology Group           | 1         | 0.57%   |
| JMicron Technology             | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 8.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 6.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 4.1%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 3.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 2.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.03%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 1.03%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 1.03%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.03%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.03%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 2         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.03%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.03%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.03%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 1.03%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 53.59%  |
| NVMe | 60        | 33.15%  |
| RAID | 12        | 6.63%   |
| IDE  | 12        | 6.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 106       | 76.26%  |
| AMD    | 33        | 23.74%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 3.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 2.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.16%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.44%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.44%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 2         | 1.44%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.44%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.44%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 1.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.44%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.44%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 1.44%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.44%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.44%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.44%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 0.72%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.72%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 0.72%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 0.72%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.72%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.72%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.72%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.72%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 1         | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 34        | 24.46%  |
| Intel Core i7        | 23        | 16.55%  |
| Other                | 19        | 13.67%  |
| AMD Ryzen 5          | 11        | 7.91%   |
| AMD Ryzen 7          | 8         | 5.76%   |
| Intel Core i3        | 7         | 5.04%   |
| Intel Celeron        | 6         | 4.32%   |
| Intel Xeon           | 4         | 2.88%   |
| Intel Atom           | 4         | 2.88%   |
| Intel Core 2 Duo     | 3         | 2.16%   |
| Intel Pentium Silver | 2         | 1.44%   |
| Intel Pentium        | 2         | 1.44%   |
| AMD Ryzen 9          | 2         | 1.44%   |
| AMD Ryzen 3          | 2         | 1.44%   |
| AMD A8               | 2         | 1.44%   |
| AMD A4               | 2         | 1.44%   |
| Intel Core i9        | 1         | 0.72%   |
| Intel Core 2 Quad    | 1         | 0.72%   |
| AMD Phenom II X4     | 1         | 0.72%   |
| AMD FX               | 1         | 0.72%   |
| AMD Athlon X4        | 1         | 0.72%   |
| AMD Athlon II X3     | 1         | 0.72%   |
| AMD Athlon           | 1         | 0.72%   |
| AMD A10              | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 59        | 42.45%  |
| 2      | 42        | 30.22%  |
| 8      | 15        | 10.79%  |
| 6      | 14        | 10.07%  |
| 12     | 3         | 2.16%   |
| 10     | 2         | 1.44%   |
| 1      | 2         | 1.44%   |
| 16     | 1         | 0.72%   |
| 3      | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 98.56%  |
| 2      | 2         | 1.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 74.82%  |
| 1      | 35        | 25.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 139       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 55.56%  |
| 0x806c1    | 5         | 3.47%   |
| 0x806ec    | 4         | 2.78%   |
| 0x306a9    | 4         | 2.78%   |
| 0x08600106 | 4         | 2.78%   |
| 0x706a8    | 3         | 2.08%   |
| 0x206a7    | 3         | 2.08%   |
| 0x08108102 | 3         | 2.08%   |
| 0x806ea    | 2         | 1.39%   |
| 0x806d1    | 2         | 1.39%   |
| 0x506e3    | 2         | 1.39%   |
| 0x406f1    | 2         | 1.39%   |
| 0x406e3    | 2         | 1.39%   |
| 0x306c3    | 2         | 1.39%   |
| 0x20655    | 2         | 1.39%   |
| 0x106e5    | 2         | 1.39%   |
| 0x0a50000c | 2         | 1.39%   |
| 0xa0671    | 1         | 0.69%   |
| 0x906eb    | 1         | 0.69%   |
| 0x906ea    | 1         | 0.69%   |
| 0x906a3    | 1         | 0.69%   |
| 0x806eb    | 1         | 0.69%   |
| 0x806e9    | 1         | 0.69%   |
| 0x506c9    | 1         | 0.69%   |
| 0x406c4    | 1         | 0.69%   |
| 0x40651    | 1         | 0.69%   |
| 0x306d4    | 1         | 0.69%   |
| 0x30678    | 1         | 0.69%   |
| 0x1067a    | 1         | 0.69%   |
| 0x10677    | 1         | 0.69%   |
| 0x0a201205 | 1         | 0.69%   |
| 0x08608104 | 1         | 0.69%   |
| 0x08608103 | 1         | 0.69%   |
| 0x08108109 | 1         | 0.69%   |
| 0x07030105 | 1         | 0.69%   |
| 0x07030104 | 1         | 0.69%   |
| 0x06001119 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 16.55%  |
| Skylake          | 12        | 8.63%   |
| TigerLake        | 11        | 7.91%   |
| Unknown          | 10        | 7.19%   |
| IvyBridge        | 8         | 5.76%   |
| Haswell          | 8         | 5.76%   |
| Zen+             | 7         | 5.04%   |
| Zen 3            | 7         | 5.04%   |
| Zen 2            | 6         | 4.32%   |
| SandyBridge      | 5         | 3.6%    |
| Penryn           | 5         | 3.6%    |
| Broadwell        | 5         | 3.6%    |
| Silvermont       | 4         | 2.88%   |
| IceLake          | 4         | 2.88%   |
| Goldmont plus    | 4         | 2.88%   |
| Westmere         | 3         | 2.16%   |
| Nehalem          | 3         | 2.16%   |
| CometLake        | 3         | 2.16%   |
| Puma             | 2         | 1.44%   |
| Piledriver       | 2         | 1.44%   |
| K10              | 2         | 1.44%   |
| Steamroller      | 1         | 0.72%   |
| Goldmont         | 1         | 0.72%   |
| Excavator        | 1         | 0.72%   |
| Bulldozer        | 1         | 0.72%   |
| Alderlake Hybrid | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 55.83%  |
| Nvidia | 38        | 23.31%  |
| AMD    | 34        | 20.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 11        | 6.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 8         | 4.79%   |
| Intel UHD Graphics 620                                                      | 6         | 3.59%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 6         | 3.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 3.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 2.99%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 2.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 2.4%    |
| Intel HD Graphics 620                                                       | 4         | 2.4%    |
| Intel HD Graphics 530                                                       | 4         | 2.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.8%    |
| Intel HD Graphics 5500                                                      | 3         | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.8%    |
| AMD Lucienne                                                                | 3         | 1.8%    |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.2%    |
| Intel JasperLake [UHD Graphics]                                             | 2         | 1.2%    |
| Intel GeminiLake [UHD Graphics 605]                                         | 2         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.2%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.2%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.2%    |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 0.6%    |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                      | 1         | 0.6%    |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 48.92%  |
| 1 x AMD        | 26        | 18.71%  |
| 1 x Nvidia     | 18        | 12.95%  |
| Intel + Nvidia | 17        | 12.23%  |
| 2 x AMD        | 3         | 2.16%   |
| AMD + Nvidia   | 3         | 2.16%   |
| Intel + AMD    | 2         | 1.44%   |
| Other          | 1         | 0.72%   |
| 2 x Intel      | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 83.57%  |
| Proprietary | 21        | 15%     |
| Unknown     | 2         | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 76.26%  |
| 1.01-2.0   | 8         | 5.76%   |
| 0.01-0.5   | 8         | 5.76%   |
| 7.01-8.0   | 5         | 3.6%    |
| 3.01-4.0   | 5         | 3.6%    |
| 0.51-1.0   | 4         | 2.88%   |
| 2.01-3.0   | 2         | 1.44%   |
| 16.01-24.0 | 1         | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 25        | 15.92%  |
| BOE                     | 25        | 15.92%  |
| Chimei Innolux          | 23        | 14.65%  |
| AU Optronics            | 13        | 8.28%   |
| LG Display              | 9         | 5.73%   |
| Goldstar                | 7         | 4.46%   |
| Apple                   | 7         | 4.46%   |
| AOC                     | 5         | 3.18%   |
| Sharp                   | 4         | 2.55%   |
| Philips                 | 4         | 2.55%   |
| Hewlett-Packard         | 4         | 2.55%   |
| BenQ                    | 3         | 1.91%   |
| SANYO                   | 2         | 1.27%   |
| Lenovo                  | 2         | 1.27%   |
| HKC                     | 2         | 1.27%   |
| Fujitsu Siemens         | 2         | 1.27%   |
| Dell                    | 2         | 1.27%   |
| Vizio                   | 1         | 0.64%   |
| Vestel Elektronik       | 1         | 0.64%   |
| Unknown (XXX)           | 1         | 0.64%   |
| Unknown (AAA)           | 1         | 0.64%   |
| TMX                     | 1         | 0.64%   |
| Sony                    | 1         | 0.64%   |
| PANDA                   | 1         | 0.64%   |
| Panasonic               | 1         | 0.64%   |
| ONN                     | 1         | 0.64%   |
| MStar                   | 1         | 0.64%   |
| LG Electronics          | 1         | 0.64%   |
| KDC                     | 1         | 0.64%   |
| IBM                     | 1         | 0.64%   |
| Denver                  | 1         | 0.64%   |
| Daewoo                  | 1         | 0.64%   |
| Chi Mei Optoelectronics | 1         | 0.64%   |
| Ancor Communications    | 1         | 0.64%   |
| Acer                    | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 2         | 1.23%   |
| Vizio D320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                    | 1         | 0.62%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 1         | 0.62%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.62%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1         | 0.62%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch               | 1         | 0.62%   |
| Sony TV SNYEE01 1920x1080                                             | 1         | 0.62%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.62%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1         | 0.62%   |
| SANYO LCD SAN0A12 1920x540                                            | 1         | 0.62%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 0.62%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch   | 1         | 0.62%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1         | 0.62%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.62%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1         | 0.62%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.62%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch   | 1         | 0.62%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.62%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.62%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1         | 0.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.62%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 70        | 47.3%   |
| 1366x768 (WXGA)    | 26        | 17.57%  |
| 3840x2160 (4K)     | 11        | 7.43%   |
| 2560x1440 (QHD)    | 7         | 4.73%   |
| 1920x1200 (WUXGA)  | 6         | 4.05%   |
| 1680x1050 (WSXGA+) | 4         | 2.7%    |
| 1600x900 (HD+)     | 4         | 2.7%    |
| 1920x540           | 3         | 2.03%   |
| 1280x800 (WXGA)    | 3         | 2.03%   |
| 3440x1440          | 2         | 1.35%   |
| 2560x1080          | 2         | 1.35%   |
| 1440x900 (WXGA+)   | 2         | 1.35%   |
| 3456x2160          | 1         | 0.68%   |
| 2880x1800          | 1         | 0.68%   |
| 2736x1824          | 1         | 0.68%   |
| 2560x1600          | 1         | 0.68%   |
| 2520x1680          | 1         | 0.68%   |
| 2240x1400          | 1         | 0.68%   |
| 1360x768           | 1         | 0.68%   |
| 1280x1024 (SXGA)   | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 28.75%  |
| 13      | 23        | 14.38%  |
| 24      | 12        | 7.5%    |
| 23      | 11        | 6.88%   |
| 14      | 11        | 6.88%   |
| 27      | 10        | 6.25%   |
| 21      | 7         | 4.38%   |
| 17      | 5         | 3.13%   |
| 34      | 4         | 2.5%    |
| 31      | 4         | 2.5%    |
| Unknown | 4         | 2.5%    |
| 40      | 3         | 1.88%   |
| 12      | 3         | 1.88%   |
| 11      | 3         | 1.88%   |
| 84      | 2         | 1.25%   |
| 54      | 2         | 1.25%   |
| 72      | 1         | 0.63%   |
| 60      | 1         | 0.63%   |
| 33      | 1         | 0.63%   |
| 28      | 1         | 0.63%   |
| 26      | 1         | 0.63%   |
| 22      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |
| 19      | 1         | 0.63%   |
| 18      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 43.31%  |
| 501-600     | 29        | 18.47%  |
| 201-300     | 18        | 11.46%  |
| 401-500     | 12        | 7.64%   |
| 601-700     | 6         | 3.82%   |
| 351-400     | 6         | 3.82%   |
| 701-800     | 5         | 3.18%   |
| Unknown     | 4         | 2.55%   |
| 801-900     | 3         | 1.91%   |
| 1501-2000   | 3         | 1.91%   |
| 1001-1500   | 3         | 1.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 112       | 78.87%  |
| 16/10   | 19        | 13.38%  |
| 21/9    | 4         | 2.82%   |
| 3/2     | 3         | 2.11%   |
| Unknown | 2         | 1.41%   |
| 4/3     | 1         | 0.7%    |
| 32/9    | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 29.3%   |
| 81-90          | 27        | 17.2%   |
| 201-250        | 23        | 14.65%  |
| 351-500        | 10        | 6.37%   |
| 301-350        | 10        | 6.37%   |
| More than 1000 | 6         | 3.82%   |
| 71-80          | 6         | 3.82%   |
| 151-200        | 5         | 3.18%   |
| 251-300        | 4         | 2.55%   |
| 121-130        | 4         | 2.55%   |
| Unknown        | 4         | 2.55%   |
| 61-70          | 3         | 1.91%   |
| 51-60          | 3         | 1.91%   |
| 501-1000       | 3         | 1.91%   |
| 41-50          | 1         | 0.64%   |
| 141-150        | 1         | 0.64%   |
| 91-100         | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 31.85%  |
| 51-100        | 39        | 24.84%  |
| 101-120       | 35        | 22.29%  |
| 161-240       | 15        | 9.55%   |
| More than 240 | 7         | 4.46%   |
| 1-50          | 7         | 4.46%   |
| Unknown       | 4         | 2.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 112       | 80%     |
| 2     | 27        | 19.29%  |
| 0     | 1         | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 77        | 37.56%  |
| Realtek Semiconductor | 71        | 34.63%  |
| Qualcomm Atheros      | 15        | 7.32%   |
| Broadcom              | 13        | 6.34%   |
| MediaTek              | 7         | 3.41%   |
| Broadcom Limited      | 4         | 1.95%   |
| Nvidia                | 3         | 1.46%   |
| ASIX Electronics      | 3         | 1.46%   |
| Hewlett-Packard       | 2         | 0.98%   |
| Xiaomi                | 1         | 0.49%   |
| TP-Link               | 1         | 0.49%   |
| T & A Mobile Phones   | 1         | 0.49%   |
| Ralink Technology     | 1         | 0.49%   |
| Microsoft             | 1         | 0.49%   |
| Lenovo                | 1         | 0.49%   |
| JMicron Technology    | 1         | 0.49%   |
| Huawei Technologies   | 1         | 0.49%   |
| Fibocom               | 1         | 0.49%   |
| ASUSTek Computer      | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 18.85%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 4.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.69%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.87%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.05%   |
| Intel Wireless 8260                                               | 5         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.23%   |
| Intel Wireless 7265                                               | 3         | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.23%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.82%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.82%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.82%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.82%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.41%   |
| T & A Mobile Phones TCL 20E                                       | 1         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 51.64%  |
| Realtek Semiconductor | 21        | 17.21%  |
| Qualcomm Atheros      | 12        | 9.84%   |
| Broadcom              | 11        | 9.02%   |
| MediaTek              | 7         | 5.74%   |
| Broadcom Limited      | 2         | 1.64%   |
| TP-Link               | 1         | 0.82%   |
| Ralink Technology     | 1         | 0.82%   |
| Microsoft             | 1         | 0.82%   |
| Hewlett-Packard       | 1         | 0.82%   |
| Fibocom               | 1         | 0.82%   |
| ASUSTek Computer      | 1         | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 8.2%    |
| Intel Wi-Fi 6 AX201                                                     | 9         | 7.38%   |
| Intel Wireless 8265 / 8275                                              | 7         | 5.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 4.1%    |
| Intel Wireless 8260                                                     | 5         | 4.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 4.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 3.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 3.28%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.46%   |
| Intel Wireless 7265                                                     | 3         | 2.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 2.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.64%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.82%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.82%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.82%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.82%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 0.82%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.82%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.82%   |
| Intel Wireless 7260                                                     | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 63        | 53.85%  |
| Intel                 | 32        | 27.35%  |
| Broadcom              | 6         | 5.13%   |
| Qualcomm Atheros      | 3         | 2.56%   |
| Nvidia                | 3         | 2.56%   |
| ASIX Electronics      | 3         | 2.56%   |
| Broadcom Limited      | 2         | 1.71%   |
| Xiaomi                | 1         | 0.85%   |
| T & A Mobile Phones   | 1         | 0.85%   |
| Lenovo                | 1         | 0.85%   |
| JMicron Technology    | 1         | 0.85%   |
| Hewlett-Packard       | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 38.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 5.79%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.31%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.48%   |
| Intel Ethernet Connection I219-V                                  | 3         | 2.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.65%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.65%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.65%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.65%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.83%   |
| T & A Mobile Phones TCL 20E                                       | 1         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.83%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.83%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.83%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.83%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.83%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.83%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.83%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.83%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 51.08%  |
| Ethernet | 112       | 48.48%  |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 64.08%  |
| Ethernet | 51        | 35.92%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 57.55%  |
| 1     | 55        | 39.57%  |
| 0     | 4         | 2.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 69.72%  |
| Yes  | 43        | 30.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 56%     |
| Realtek Semiconductor           | 8         | 8%      |
| Apple                           | 8         | 8%      |
| Qualcomm Atheros Communications | 7         | 7%      |
| Broadcom                        | 6         | 6%      |
| IMC Networks                    | 4         | 4%      |
| MediaTek                        | 2         | 2%      |
| Dell                            | 2         | 2%      |
| Cambridge Silicon Radio         | 2         | 2%      |
| Smart Modular Technologies      | 1         | 1%      |
| Realtek                         | 1         | 1%      |
| Lite-On Technology              | 1         | 1%      |
| Foxconn International           | 1         | 1%      |
| Foxconn / Hon Hai               | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 18%     |
| Intel AX201 Bluetooth                               | 15        | 15%     |
| Intel AX200 Bluetooth                               | 10        | 10%     |
| Realtek Bluetooth Radio                             | 5         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 5%      |
| Apple Bluetooth USB Host Controller                 | 5         | 5%      |
| Intel AX210 Bluetooth                               | 4         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 3%      |
| IMC Networks Wireless_Device                        | 3         | 3%      |
| MediaTek Wireless_Device                            | 2         | 2%      |
| Intel Bluetooth Device                              | 2         | 2%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2%      |
| Dell DW375 Bluetooth Module                         | 2         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2%      |
| Apple Bluetooth Host Controller                     | 2         | 2%      |
| Smart Modular Bluetooth Device                      | 1         | 1%      |
| Realtek RTL8821A Bluetooth                          | 1         | 1%      |
| Realtek RTL8723B Bluetooth                          | 1         | 1%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1%      |
| Realtek Bluetooth Radio                             | 1         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1%      |
| Lite-On Bluetooth Radio                             | 1         | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1%      |
| IMC Networks Bluetooth Radio                        | 1         | 1%      |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1%      |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 99        | 55.62%  |
| AMD                     | 37        | 20.79%  |
| Nvidia                  | 26        | 14.61%  |
| Plantronics             | 3         | 1.69%   |
| Logitech                | 2         | 1.12%   |
| DSEA A/S                | 2         | 1.12%   |
| Texas Instruments       | 1         | 0.56%   |
| Shure                   | 1         | 0.56%   |
| Realtek Semiconductor   | 1         | 0.56%   |
| LINE TECH INDUSTRIAL    | 1         | 0.56%   |
| Creative Technology     | 1         | 0.56%   |
| ClearOne Communications | 1         | 0.56%   |
| ASUSTek Computer        | 1         | 0.56%   |
| Apple                   | 1         | 0.56%   |
| AKAI Professional M.I.  | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 9.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 19        | 8.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 6.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 5.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.79%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.4%    |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.4%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.4%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.4%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.93%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.93%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.93%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.93%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.93%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.47%   |
| Shure MV88+                                                                | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.47%   |
| Plantronics HD1                                                            | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 27.37%  |
| SK hynix            | 21        | 22.11%  |
| Kingston            | 12        | 12.63%  |
| Crucial             | 9         | 9.47%   |
| Micron Technology   | 8         | 8.42%   |
| Elpida              | 4         | 4.21%   |
| Unknown (ABCD)      | 2         | 2.11%   |
| Ramaxel Technology  | 2         | 2.11%   |
| A-DATA Technology   | 2         | 2.11%   |
| Unknown             | 1         | 1.05%   |
| Transcend           | 1         | 1.05%   |
| Teikon              | 1         | 1.05%   |
| Nanya Technology    | 1         | 1.05%   |
| Magnum Tech         | 1         | 1.05%   |
| fef5                | 1         | 1.05%   |
| Corsair             | 1         | 1.05%   |
| ChangXin Memory     | 1         | 1.05%   |
| 8945000080AD        | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 3.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.94%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.96%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 1.96%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.96%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.98%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 0.98%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.98%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 0.98%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.98%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 0.98%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 0.98%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.98%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.98%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 0.98%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 0.98%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.98%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.98%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.98%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 0.98%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 58.23%  |
| DDR3    | 20        | 25.32%  |
| LPDDR4  | 9         | 11.39%  |
| SDRAM   | 2         | 2.53%   |
| LPDDR3  | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 72.73%  |
| DIMM         | 12        | 15.58%  |
| Row Of Chips | 6         | 7.79%   |
| Unknown      | 2         | 2.6%    |
| Chip         | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 41.98%  |
| 4096  | 16        | 19.75%  |
| 16384 | 14        | 17.28%  |
| 2048  | 8         | 9.88%   |
| 32768 | 7         | 8.64%   |
| 1024  | 2         | 2.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 21        | 24.42%  |
| 2667  | 15        | 17.44%  |
| 1600  | 15        | 17.44%  |
| 2400  | 11        | 12.79%  |
| 2133  | 5         | 5.81%   |
| 4267  | 3         | 3.49%   |
| 1333  | 3         | 3.49%   |
| 1067  | 3         | 3.49%   |
| 1334  | 2         | 2.33%   |
| 1066  | 2         | 2.33%   |
| 4199  | 1         | 1.16%   |
| 3733  | 1         | 1.16%   |
| 3600  | 1         | 1.16%   |
| 3266  | 1         | 1.16%   |
| 2933  | 1         | 1.16%   |
| 1867  | 1         | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Dymo-CoStar         | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 29.35%  |
| IMC Networks                           | 9         | 9.78%   |
| Realtek Semiconductor                  | 7         | 7.61%   |
| Microdia                               | 6         | 6.52%   |
| Apple                                  | 6         | 6.52%   |
| Sunplus Innovation Technology          | 5         | 5.43%   |
| Luxvisions Innotech Limited            | 5         | 5.43%   |
| Bison Electronics                      | 5         | 5.43%   |
| Syntek                                 | 3         | 3.26%   |
| Logitech                               | 3         | 3.26%   |
| Samsung Electronics                    | 2         | 2.17%   |
| Quanta                                 | 2         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.17%   |
| Acer                                   | 2         | 2.17%   |
| ValueHD                                | 1         | 1.09%   |
| Unknown (3730304233345731394146)       | 1         | 1.09%   |
| Unknown                                | 1         | 1.09%   |
| Polycom                                | 1         | 1.09%   |
| Generalplus Technology                 | 1         | 1.09%   |
| Alcor Micro                            | 1         | 1.09%   |
| 8SSC21D67422V1SR28902JL                | 1         | 1.09%   |
| Unknown                                | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 5         | 5.43%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 4.35%   |
| Chicony HP HD Camera                                 | 4         | 4.35%   |
| Realtek Integrated_Webcam_HD                         | 3         | 3.26%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.26%   |
| Logitech HD Pro Webcam C920                          | 3         | 3.26%   |
| IMC Networks Integrated Camera                       | 3         | 3.26%   |
| Chicony USB2.0 Camera                                | 3         | 3.26%   |
| Chicony Integrated Camera                            | 3         | 3.26%   |
| Bison SunplusIT Integrated Camera                    | 3         | 3.26%   |
| Syntek Integrated Camera                             | 2         | 2.17%   |
| Sunplus MTD Camera                                   | 2         | 2.17%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.17%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 2.17%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 2.17%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 2.17%   |
| Apple FaceTime HD Camera                             | 2         | 2.17%   |
| Apple Built-in iSight                                | 2         | 2.17%   |
| ValueHD Konftel Cam20                                | 1         | 1.09%   |
| Unknown ATIV VGA CAMERA                              | 1         | 1.09%   |
| Unknown (3730304233345731394146) USB Camera          | 1         | 1.09%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.09%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.09%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.09%   |
| Sunplus HD WebCam                                    | 1         | 1.09%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 1.09%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.09%   |
| Realtek Integrated Webcam HD                         | 1         | 1.09%   |
| Realtek Integrated Webcam                            | 1         | 1.09%   |
| Quanta USB2.0 HD UVC WebCam                          | 1         | 1.09%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.09%   |
| Polycom Poly Studio P5 webcam                        | 1         | 1.09%   |
| Microdia Lenovo EasyCamera                           | 1         | 1.09%   |
| Microdia Integrated Webcam HD                        | 1         | 1.09%   |
| Microdia Camera                                      | 1         | 1.09%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.09%   |
| IMC Networks Integrated RGB Camera                   | 1         | 1.09%   |
| Generalplus 808 Camera #9 (web-cam mode)             | 1         | 1.09%   |
| Chicony XiaoMi USB 2.0 Webcam                        | 1         | 1.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 41.67%  |
| Shenzhen Goodix Technology | 6         | 25%     |
| Validity Sensors           | 5         | 20.83%  |
| Elan Microelectronics      | 2         | 8.33%   |
| LighTuning Technology      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 4.17%   |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 4.17%   |
| Synaptics UWP WBDI Device                                 | 1         | 4.17%   |
| Synaptics TouchPad                                        | 1         | 4.17%   |
| Synaptics  WBDI                                           | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 4.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.17%   |
| Shenzhen Goodix FingerPrint                               | 1         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                     | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                          | 1         | 4.17%   |
| Unknown                                                   | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 65.25%  |
| 1     | 34        | 24.11%  |
| 2     | 11        | 7.8%    |
| 3     | 2         | 1.42%   |
| 7     | 1         | 0.71%   |
| 4     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 35.94%  |
| Net/wireless             | 8         | 12.5%   |
| Graphics card            | 6         | 9.38%   |
| Chipcard                 | 5         | 7.81%   |
| Sound                    | 4         | 6.25%   |
| Communication controller | 4         | 6.25%   |
| Unassigned class         | 3         | 4.69%   |
| Multimedia controller    | 3         | 4.69%   |
| Camera                   | 3         | 4.69%   |
| Card reader              | 2         | 3.13%   |
| Bluetooth                | 2         | 3.13%   |
| Net/ethernet             | 1         | 1.56%   |


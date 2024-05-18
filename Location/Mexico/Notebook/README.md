Linux in Mexico - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 2802

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| SDZ           | X133                        | [442d4da2a4](https://linux-hardware.org/?probe=442d4da2a4) | May 09, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [161509c62b](https://linux-hardware.org/?probe=161509c62b) | May 09, 2024 |
| Dell          | Vostro 1220                 | [a4ee382052](https://linux-hardware.org/?probe=a4ee382052) | May 09, 2024 |
| Dell          | Vostro 1220                 | [7f6372d340](https://linux-hardware.org/?probe=7f6372d340) | May 08, 2024 |
| Dell          | Inspiron 5420               | [24c2d41566](https://linux-hardware.org/?probe=24c2d41566) | May 08, 2024 |
| Sony          | SVE1412BCXB                 | [593942e0e3](https://linux-hardware.org/?probe=593942e0e3) | May 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [61b3a490a8](https://linux-hardware.org/?probe=61b3a490a8) | May 07, 2024 |
| Acer          | Aspire A315-24P             | [3fbbffc4e8](https://linux-hardware.org/?probe=3fbbffc4e8) | May 04, 2024 |
| Chuwi         | CoreBook X                  | [b1b4be48b3](https://linux-hardware.org/?probe=b1b4be48b3) | May 04, 2024 |
| Toshiba       | Satellite L745              | [797c23bdbc](https://linux-hardware.org/?probe=797c23bdbc) | May 03, 2024 |
| Apple         | MacBookPro11,5              | [fdf75026c9](https://linux-hardware.org/?probe=fdf75026c9) | May 03, 2024 |
| Gigabyte      | B450M DS3H-CF               | [eb1d061242](https://linux-hardware.org/?probe=eb1d061242) | May 02, 2024 |
| Acer          | Aspire A315-23              | [ee01c6ee48](https://linux-hardware.org/?probe=ee01c6ee48) | May 01, 2024 |
| MSI           | Bravo 15 B5DD               | [c3ea06def8](https://linux-hardware.org/?probe=c3ea06def8) | May 01, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1QU0... | [5429ec2fa3](https://linux-hardware.org/?probe=5429ec2fa3) | Apr 30, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1QU0... | [60d21b08c6](https://linux-hardware.org/?probe=60d21b08c6) | Apr 30, 2024 |
| Dell          | System Vostro 3450          | [eede1fda8a](https://linux-hardware.org/?probe=eede1fda8a) | Apr 30, 2024 |
| Toshiba       | Satellite C75D-A            | [cf14ec8d91](https://linux-hardware.org/?probe=cf14ec8d91) | Apr 30, 2024 |
| Toshiba       | Satellite C75D-A            | [2aa3b0b51b](https://linux-hardware.org/?probe=2aa3b0b51b) | Apr 30, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fc7d5ed265](https://linux-hardware.org/?probe=fc7d5ed265) | Apr 29, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b6a512b4fc](https://linux-hardware.org/?probe=b6a512b4fc) | Apr 29, 2024 |
| HP            | 14                          | [e3828c3dc9](https://linux-hardware.org/?probe=e3828c3dc9) | Apr 29, 2024 |
| HP            | 14                          | [a1017c1b83](https://linux-hardware.org/?probe=a1017c1b83) | Apr 29, 2024 |
| HP            | ProBook 4510s               | [8de734fc37](https://linux-hardware.org/?probe=8de734fc37) | Apr 28, 2024 |
| HUAWEI        | HVY-WXX9                    | [0f16f57261](https://linux-hardware.org/?probe=0f16f57261) | Apr 28, 2024 |
| Timi          | Redmi G 2022                | [42d8e2e055](https://linux-hardware.org/?probe=42d8e2e055) | Apr 28, 2024 |
| Lenovo        | ThinkPad T430 2349G87       | [44960bd729](https://linux-hardware.org/?probe=44960bd729) | Apr 27, 2024 |
| HP            | ZBook 14                    | [42c92ec19d](https://linux-hardware.org/?probe=42c92ec19d) | Apr 27, 2024 |
| Lenovo        | ThinkPad T430 2349G87       | [f84eda1847](https://linux-hardware.org/?probe=f84eda1847) | Apr 27, 2024 |
| HUAWEI        | HVY-WXX9                    | [5d98ce8c7a](https://linux-hardware.org/?probe=5d98ce8c7a) | Apr 27, 2024 |
| Acer          | Aspire A314-35              | [b81c267e1b](https://linux-hardware.org/?probe=b81c267e1b) | Apr 27, 2024 |
| HP            | Laptop 17t-cn200            | [d2301475ae](https://linux-hardware.org/?probe=d2301475ae) | Apr 26, 2024 |
| HP            | ZBook 14                    | [d6e2400956](https://linux-hardware.org/?probe=d6e2400956) | Apr 26, 2024 |
| GPD           | G1618-04                    | [2c1da6a68d](https://linux-hardware.org/?probe=2c1da6a68d) | Apr 26, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [256b1160a5](https://linux-hardware.org/?probe=256b1160a5) | Apr 25, 2024 |
| Apple         | MacBookPro11,5              | [cfd10a22a4](https://linux-hardware.org/?probe=cfd10a22a4) | Apr 25, 2024 |
| Dell          | Inspiron 15 3520            | [3c7367dc40](https://linux-hardware.org/?probe=3c7367dc40) | Apr 25, 2024 |
| Unknown       | W1415A                      | [50907a4878](https://linux-hardware.org/?probe=50907a4878) | Apr 25, 2024 |
| Sony          | SVF14211CLB                 | [715b8f68ea](https://linux-hardware.org/?probe=715b8f68ea) | Apr 25, 2024 |
| Notebook      | PA70ES                      | [866c7351b4](https://linux-hardware.org/?probe=866c7351b4) | Apr 24, 2024 |
| THUNDEROBO... | ZERO                        | [9f1b5806e2](https://linux-hardware.org/?probe=9f1b5806e2) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | [ecc36cef1b](https://linux-hardware.org/?probe=ecc36cef1b) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | [5a88798ad6](https://linux-hardware.org/?probe=5a88798ad6) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | [3d7326b94d](https://linux-hardware.org/?probe=3d7326b94d) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | [d217b8e5ee](https://linux-hardware.org/?probe=d217b8e5ee) | Apr 22, 2024 |
| Dell          | Latitude E5400              | [fba5edc10c](https://linux-hardware.org/?probe=fba5edc10c) | Apr 21, 2024 |
| Valve         | Jupiter                     | [da44a88ec3](https://linux-hardware.org/?probe=da44a88ec3) | Apr 19, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [b3e2fd82b1](https://linux-hardware.org/?probe=b3e2fd82b1) | Apr 18, 2024 |
| HP            | ZBook 15                    | [f581a351ed](https://linux-hardware.org/?probe=f581a351ed) | Apr 15, 2024 |
| HUAWEI        | HVY-WXX9                    | [8e08ea7707](https://linux-hardware.org/?probe=8e08ea7707) | Apr 15, 2024 |
| Apple         | MacBookPro9,2               | [a34c77d581](https://linux-hardware.org/?probe=a34c77d581) | Apr 15, 2024 |
| Apple         | MacBookPro9,2               | [64dad1f2cc](https://linux-hardware.org/?probe=64dad1f2cc) | Apr 15, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [4d70d7056d](https://linux-hardware.org/?probe=4d70d7056d) | Apr 15, 2024 |
| MSI           | GF63 Thin 9SCSR             | [f0aa2a4553](https://linux-hardware.org/?probe=f0aa2a4553) | Apr 14, 2024 |
| Unknown       | Unknown                     | [b6ce023a2a](https://linux-hardware.org/?probe=b6ce023a2a) | Apr 13, 2024 |
| Toshiba       | Satellite S55t-A            | [83f4844e2a](https://linux-hardware.org/?probe=83f4844e2a) | Apr 12, 2024 |
| Toshiba       | Satellite M645              | [f5c39a1c49](https://linux-hardware.org/?probe=f5c39a1c49) | Apr 12, 2024 |
| Dell          | Inspiron 15-3567            | [7e75593e22](https://linux-hardware.org/?probe=7e75593e22) | Apr 11, 2024 |
| Dell          | Inspiron 15 3525            | [a10b3d14be](https://linux-hardware.org/?probe=a10b3d14be) | Apr 11, 2024 |
| Chuwi         | GemiBook Pro                | [1e7a6a55d7](https://linux-hardware.org/?probe=1e7a6a55d7) | Apr 11, 2024 |
| HP            | ProBook 440 G2              | [1761f221f8](https://linux-hardware.org/?probe=1761f221f8) | Apr 09, 2024 |
| HP            | ProBook 440 G2              | [84b8f6128b](https://linux-hardware.org/?probe=84b8f6128b) | Apr 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [c149854fdc](https://linux-hardware.org/?probe=c149854fdc) | Apr 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [072ce57a20](https://linux-hardware.org/?probe=072ce57a20) | Apr 09, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [009000b54c](https://linux-hardware.org/?probe=009000b54c) | Apr 09, 2024 |
| HUAWEI        | HVY-WXX9                    | [15856bf371](https://linux-hardware.org/?probe=15856bf371) | Apr 08, 2024 |
| HUAWEI        | HVY-WXX9                    | [9e68874b1d](https://linux-hardware.org/?probe=9e68874b1d) | Apr 08, 2024 |
| HP            | ProBook 650 G2              | [693d207c41](https://linux-hardware.org/?probe=693d207c41) | Apr 07, 2024 |
| HP            | ProBook 650 G2              | [5e5491e5cd](https://linux-hardware.org/?probe=5e5491e5cd) | Apr 07, 2024 |
| Lenovo        | G50-30 80G0                 | [901e9f9640](https://linux-hardware.org/?probe=901e9f9640) | Apr 07, 2024 |
| Apple         | MacBookAir5,1               | [b78a1f13a5](https://linux-hardware.org/?probe=b78a1f13a5) | Apr 06, 2024 |
| Apple         | MacBookAir5,1               | [4fcbb0c76e](https://linux-hardware.org/?probe=4fcbb0c76e) | Apr 06, 2024 |
| Valve         | Jupiter                     | [70c2145a5e](https://linux-hardware.org/?probe=70c2145a5e) | Apr 06, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [1c39800ffb](https://linux-hardware.org/?probe=1c39800ffb) | Apr 06, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [d7dbb4d491](https://linux-hardware.org/?probe=d7dbb4d491) | Apr 06, 2024 |
| HUAWEI        | NBLK-WAX9X                  | [fb40c0b7f8](https://linux-hardware.org/?probe=fb40c0b7f8) | Apr 06, 2024 |
| Valve         | Jupiter                     | [04c5de9351](https://linux-hardware.org/?probe=04c5de9351) | Apr 05, 2024 |
| Valve         | Jupiter                     | [a981f41f5c](https://linux-hardware.org/?probe=a981f41f5c) | Apr 05, 2024 |
| Toshiba       | Satellite C645D             | [b7665d5de2](https://linux-hardware.org/?probe=b7665d5de2) | Apr 05, 2024 |
| HP            | Pavilion dm4                | [928ce1826d](https://linux-hardware.org/?probe=928ce1826d) | Apr 04, 2024 |
| Toshiba       | Satellite NB15t-A           | [812de2aaae](https://linux-hardware.org/?probe=812de2aaae) | Apr 04, 2024 |
| Lenovo        | G50-30 80G0                 | [8ad07875a5](https://linux-hardware.org/?probe=8ad07875a5) | Apr 04, 2024 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [8dfb911855](https://linux-hardware.org/?probe=8dfb911855) | Apr 03, 2024 |
| Alienware     | 17 R4                       | [0c83302e22](https://linux-hardware.org/?probe=0c83302e22) | Apr 02, 2024 |
| HP            | Laptop 15-bs0xx             | [1e796b8f8c](https://linux-hardware.org/?probe=1e796b8f8c) | Apr 01, 2024 |
| Acer          | Aspire A315-24P             | [e8817f1766](https://linux-hardware.org/?probe=e8817f1766) | Apr 01, 2024 |
| Apple         | MacBookPro9,2               | [cccef069f7](https://linux-hardware.org/?probe=cccef069f7) | Apr 01, 2024 |
| HP            | Laptop 15-dw1xxx            | [e28e296839](https://linux-hardware.org/?probe=e28e296839) | Mar 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a6e6eec43a](https://linux-hardware.org/?probe=a6e6eec43a) | Mar 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [e49cbff800](https://linux-hardware.org/?probe=e49cbff800) | Mar 30, 2024 |
| ASUSTek       | Unknown                     | [f0d50801ff](https://linux-hardware.org/?probe=f0d50801ff) | Mar 30, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [b75c8663ed](https://linux-hardware.org/?probe=b75c8663ed) | Mar 29, 2024 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [8d88a75722](https://linux-hardware.org/?probe=8d88a75722) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [e23a935b8e](https://linux-hardware.org/?probe=e23a935b8e) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [650cc5973f](https://linux-hardware.org/?probe=650cc5973f) | Mar 27, 2024 |
| ASUSTek       | Unknown                     | [c405404136](https://linux-hardware.org/?probe=c405404136) | Mar 26, 2024 |
| Apple         | MacBookPro9,1               | [b0266d88c6](https://linux-hardware.org/?probe=b0266d88c6) | Mar 25, 2024 |
| Lenovo        | ThinkPad T470p 20J7A004L... | [7aa99b8f2b](https://linux-hardware.org/?probe=7aa99b8f2b) | Mar 24, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [e22abd24d3](https://linux-hardware.org/?probe=e22abd24d3) | Mar 24, 2024 |
| HP            | ENVY Notebook               | [cc51a9f994](https://linux-hardware.org/?probe=cc51a9f994) | Mar 23, 2024 |
| HUAWEI        | BoDE-WXX9                   | [7a3e14e618](https://linux-hardware.org/?probe=7a3e14e618) | Mar 20, 2024 |
| Dell          | Latitude E7470              | [ab8a5e8ce5](https://linux-hardware.org/?probe=ab8a5e8ce5) | Mar 20, 2024 |
| Acer          | Aspire E1-422               | [e6ff98fb07](https://linux-hardware.org/?probe=e6ff98fb07) | Mar 19, 2024 |
| Alienware     | 17 R3                       | [7a56c80abc](https://linux-hardware.org/?probe=7a56c80abc) | Mar 19, 2024 |
| HP            | Stream Laptop 14-ds0xxx     | [e003a1215d](https://linux-hardware.org/?probe=e003a1215d) | Mar 19, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5603a5896d](https://linux-hardware.org/?probe=5603a5896d) | Mar 17, 2024 |
| Sony          | VPCF236FM                   | [82b1f5dd66](https://linux-hardware.org/?probe=82b1f5dd66) | Mar 17, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [250f1255fd](https://linux-hardware.org/?probe=250f1255fd) | Mar 16, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [b24d70c129](https://linux-hardware.org/?probe=b24d70c129) | Mar 16, 2024 |
| Acer          | Aspire 5745                 | [512b58fc90](https://linux-hardware.org/?probe=512b58fc90) | Mar 16, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1QU0... | [0aeadde0d2](https://linux-hardware.org/?probe=0aeadde0d2) | Mar 15, 2024 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [597ac47473](https://linux-hardware.org/?probe=597ac47473) | Mar 15, 2024 |
| HP            | Pavilion g6                 | [992ebee68f](https://linux-hardware.org/?probe=992ebee68f) | Mar 15, 2024 |
| Google        | Celes                       | [996befe940](https://linux-hardware.org/?probe=996befe940) | Mar 13, 2024 |
| Toshiba       | Satellite C845D             | [dba3c8f7b1](https://linux-hardware.org/?probe=dba3c8f7b1) | Mar 12, 2024 |
| Dell          | Inspiron 15 3515            | [ed5c4423dc](https://linux-hardware.org/?probe=ed5c4423dc) | Mar 12, 2024 |
| Dell          | Inspiron 15 3525            | [5fc6a99a63](https://linux-hardware.org/?probe=5fc6a99a63) | Mar 11, 2024 |
| HUAWEI        | BOHB-WAX9                   | [dd6d973cd5](https://linux-hardware.org/?probe=dd6d973cd5) | Mar 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b7c41acc81](https://linux-hardware.org/?probe=b7c41acc81) | Mar 11, 2024 |
| Gigabyte      | B550M DS3H AC               | [1550ac647f](https://linux-hardware.org/?probe=1550ac647f) | Mar 10, 2024 |
| HUAWEI        | MACH-WX9                    | [c0ec9884e2](https://linux-hardware.org/?probe=c0ec9884e2) | Mar 10, 2024 |
| Acer          | Aspire 4552                 | [37b07d052c](https://linux-hardware.org/?probe=37b07d052c) | Mar 08, 2024 |
| HP            | Victus by Gaming Laptop ... | [4ba0cd9d57](https://linux-hardware.org/?probe=4ba0cd9d57) | Mar 08, 2024 |
| HP            | Pavilion Notebook           | [83525aec38](https://linux-hardware.org/?probe=83525aec38) | Mar 07, 2024 |
| Apple         | MacBookAir7,2               | [9dae6d704f](https://linux-hardware.org/?probe=9dae6d704f) | Mar 07, 2024 |
| HUAWEI        | NBM-WXX9                    | [164e1486c4](https://linux-hardware.org/?probe=164e1486c4) | Mar 07, 2024 |
| HUAWEI        | NBM-WXX9                    | [97f11050b4](https://linux-hardware.org/?probe=97f11050b4) | Mar 06, 2024 |
| MSI           | Katana GF66 12UC            | [13e9499bcc](https://linux-hardware.org/?probe=13e9499bcc) | Mar 05, 2024 |
| MSI           | Katana GF66 12UC            | [27e54c1325](https://linux-hardware.org/?probe=27e54c1325) | Mar 05, 2024 |
| HP            | Victus by Gaming Laptop ... | [f6557a8982](https://linux-hardware.org/?probe=f6557a8982) | Mar 04, 2024 |
| Apple         | MacBookAir7,1               | [f50392faa6](https://linux-hardware.org/?probe=f50392faa6) | Mar 02, 2024 |
| Valve         | Jupiter                     | [8b06ba52f8](https://linux-hardware.org/?probe=8b06ba52f8) | Mar 02, 2024 |
| Valve         | Jupiter                     | [610fa788bb](https://linux-hardware.org/?probe=610fa788bb) | Mar 01, 2024 |
| Acer          | Nitro AN515-42              | [d0b8c0c8e3](https://linux-hardware.org/?probe=d0b8c0c8e3) | Mar 01, 2024 |
| Acer          | Nitro AN515-42              | [ea076d2fa1](https://linux-hardware.org/?probe=ea076d2fa1) | Mar 01, 2024 |
| Apple         | MacBookAir7,1               | [35c1cbf028](https://linux-hardware.org/?probe=35c1cbf028) | Mar 01, 2024 |
| Acer          | Aspire VN7-592G             | [85e5cb8bbf](https://linux-hardware.org/?probe=85e5cb8bbf) | Feb 29, 2024 |
| Toshiba       | PORTEGE Z10t-A              | [6eae7deb8c](https://linux-hardware.org/?probe=6eae7deb8c) | Feb 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fb716bf15a](https://linux-hardware.org/?probe=fb716bf15a) | Feb 27, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [135aa487e2](https://linux-hardware.org/?probe=135aa487e2) | Feb 27, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [e82d50f527](https://linux-hardware.org/?probe=e82d50f527) | Feb 26, 2024 |
| Apple         | MacBookPro12,1              | [3e204ee57c](https://linux-hardware.org/?probe=3e204ee57c) | Feb 25, 2024 |
| Lenovo        | 80VR                        | [28bf028644](https://linux-hardware.org/?probe=28bf028644) | Feb 25, 2024 |
| HP            | Pavilion dv6                | [2f035fa111](https://linux-hardware.org/?probe=2f035fa111) | Feb 24, 2024 |
| Apple         | MacBookPro11,3              | [024ce1892f](https://linux-hardware.org/?probe=024ce1892f) | Feb 24, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [854b480d0e](https://linux-hardware.org/?probe=854b480d0e) | Feb 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [31008e9ce3](https://linux-hardware.org/?probe=31008e9ce3) | Feb 23, 2024 |
| HUAWEI        | NBM-WXX9                    | [4e5db7ef0b](https://linux-hardware.org/?probe=4e5db7ef0b) | Feb 23, 2024 |
| Apple         | MacBookPro11,3              | [39c63d2ac1](https://linux-hardware.org/?probe=39c63d2ac1) | Feb 23, 2024 |
| Dell          | Precision 5520              | [ef95414cdd](https://linux-hardware.org/?probe=ef95414cdd) | Feb 22, 2024 |
| Lenovo        | ThinkPad T420 4236MBS       | [bcba4e78e0](https://linux-hardware.org/?probe=bcba4e78e0) | Feb 21, 2024 |
| Acer          | Aspire one                  | [39289d9272](https://linux-hardware.org/?probe=39289d9272) | Feb 19, 2024 |
| HP            | ZBook Firefly 15.6 inch ... | [d0562f4f40](https://linux-hardware.org/?probe=d0562f4f40) | Feb 19, 2024 |
| Lenovo        | ThinkPad T470s 20HGS15V0... | [60bc5e5ff6](https://linux-hardware.org/?probe=60bc5e5ff6) | Feb 19, 2024 |
| HP            | 240 G7 Notebook PC          | [5d25d52442](https://linux-hardware.org/?probe=5d25d52442) | Feb 18, 2024 |
| Dell          | Latitude 5430               | [87697e2371](https://linux-hardware.org/?probe=87697e2371) | Feb 18, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [f934645327](https://linux-hardware.org/?probe=f934645327) | Feb 17, 2024 |
| Dell          | Latitude E7270              | [1fa10e0cbb](https://linux-hardware.org/?probe=1fa10e0cbb) | Feb 17, 2024 |
| HUAWEI        | HVY-WXX9                    | [47841ddf05](https://linux-hardware.org/?probe=47841ddf05) | Feb 17, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0139d27bce](https://linux-hardware.org/?probe=0139d27bce) | Feb 17, 2024 |
| ASUSTek       | X550EA                      | [9e0a3e5b40](https://linux-hardware.org/?probe=9e0a3e5b40) | Feb 16, 2024 |
| HP            | Laptop 14-ck0xxx            | [d36ca0b771](https://linux-hardware.org/?probe=d36ca0b771) | Feb 16, 2024 |
| HP            | Laptop 14-ck0xxx            | [4317b0643f](https://linux-hardware.org/?probe=4317b0643f) | Feb 16, 2024 |
| ASUSTek       | X550EA                      | [2b9bdf9093](https://linux-hardware.org/?probe=2b9bdf9093) | Feb 15, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [b5bad706ef](https://linux-hardware.org/?probe=b5bad706ef) | Feb 15, 2024 |
| Valve         | Jupiter                     | [3cc9a72587](https://linux-hardware.org/?probe=3cc9a72587) | Feb 15, 2024 |
| HUAWEI        | HVY-WXX9                    | [c26220f7e3](https://linux-hardware.org/?probe=c26220f7e3) | Feb 14, 2024 |
| Unknown       | W1415A                      | [923b811bb5](https://linux-hardware.org/?probe=923b811bb5) | Feb 14, 2024 |
| Unknown       | W1415A                      | [a0c020f290](https://linux-hardware.org/?probe=a0c020f290) | Feb 13, 2024 |
| Dell          | Inspiron 5570               | [6d494e469d](https://linux-hardware.org/?probe=6d494e469d) | Feb 12, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fd93dfb574](https://linux-hardware.org/?probe=fd93dfb574) | Feb 10, 2024 |
| Toshiba       | PORTEGE Z30-A               | [bdaddeea3c](https://linux-hardware.org/?probe=bdaddeea3c) | Feb 10, 2024 |
| Toshiba       | PORTEGE Z30-A               | [695c229b60](https://linux-hardware.org/?probe=695c229b60) | Feb 10, 2024 |
| Dell          | Latitude E7440              | [e4f0f96f3d](https://linux-hardware.org/?probe=e4f0f96f3d) | Feb 10, 2024 |
| HP            | Laptop 15-da0xxx            | [cc4ac646f5](https://linux-hardware.org/?probe=cc4ac646f5) | Feb 10, 2024 |
| Apple         | MacBookPro11,3              | [911f8b9339](https://linux-hardware.org/?probe=911f8b9339) | Feb 08, 2024 |
| HP            | Laptop 17t-cn200            | [ade07084cc](https://linux-hardware.org/?probe=ade07084cc) | Feb 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [578f387ae6](https://linux-hardware.org/?probe=578f387ae6) | Feb 06, 2024 |
| Apple         | MacBookPro11,3              | [7ae8f18923](https://linux-hardware.org/?probe=7ae8f18923) | Feb 06, 2024 |
| LG Electro... | 13ZD970-GX3PK               | [30c8b7026c](https://linux-hardware.org/?probe=30c8b7026c) | Feb 04, 2024 |
| Valve         | Jupiter                     | [6c300e05f5](https://linux-hardware.org/?probe=6c300e05f5) | Feb 03, 2024 |
| HUAWEI        | NBM-WXX9                    | [b0956fb9c4](https://linux-hardware.org/?probe=b0956fb9c4) | Feb 02, 2024 |
| Toshiba       | Satellite L55-C             | [f32d9dc51a](https://linux-hardware.org/?probe=f32d9dc51a) | Feb 02, 2024 |
| HP            | Pavilion dv4                | [09400a55bb](https://linux-hardware.org/?probe=09400a55bb) | Feb 01, 2024 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [4f9b6c7262](https://linux-hardware.org/?probe=4f9b6c7262) | Jan 31, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [40f306477e](https://linux-hardware.org/?probe=40f306477e) | Jan 31, 2024 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [0e068176e4](https://linux-hardware.org/?probe=0e068176e4) | Jan 31, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [25fe740321](https://linux-hardware.org/?probe=25fe740321) | Jan 30, 2024 |
| Dell          | Inspiron 1545               | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| HUAWEI        | NbDE-WXX9                   | [39f2e4dc9e](https://linux-hardware.org/?probe=39f2e4dc9e) | Jan 29, 2024 |
| HUAWEI        | NbDE-WXX9                   | [bf90b37fe4](https://linux-hardware.org/?probe=bf90b37fe4) | Jan 29, 2024 |
| HP            | Laptop 15-da0xxx            | [0001a7672a](https://linux-hardware.org/?probe=0001a7672a) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [67781b5f97](https://linux-hardware.org/?probe=67781b5f97) | Jan 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [32f526010e](https://linux-hardware.org/?probe=32f526010e) | Jan 27, 2024 |
| VPU Compan... | VWNC71429-S                 | [5f72f42958](https://linux-hardware.org/?probe=5f72f42958) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430s 2356GRS      | [c12736937f](https://linux-hardware.org/?probe=c12736937f) | Jan 26, 2024 |
| Apple         | MacBookPro9,2               | [5591f82595](https://linux-hardware.org/?probe=5591f82595) | Jan 26, 2024 |
| Acer          | Aspire ES1-531              | [7faffb7f83](https://linux-hardware.org/?probe=7faffb7f83) | Jan 25, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [7ea2706c0f](https://linux-hardware.org/?probe=7ea2706c0f) | Jan 23, 2024 |
| HP            | 240 G7 Notebook PC          | [5225ed2250](https://linux-hardware.org/?probe=5225ed2250) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Lenovo        | G40-80 80E4                 | [d03cd5d338](https://linux-hardware.org/?probe=d03cd5d338) | Jan 19, 2024 |
| HP            | Victus by Gaming Laptop ... | [3dfc03f457](https://linux-hardware.org/?probe=3dfc03f457) | Jan 19, 2024 |
| HP            | Victus by Gaming Laptop ... | [f3ce87bc3c](https://linux-hardware.org/?probe=f3ce87bc3c) | Jan 19, 2024 |
| Acer          | Aspire F5-573               | [9a2df369e8](https://linux-hardware.org/?probe=9a2df369e8) | Jan 19, 2024 |
| HP            | Laptop 14-dq1xxx            | [048c8842d1](https://linux-hardware.org/?probe=048c8842d1) | Jan 19, 2024 |
| Lenovo        | G40-80 80E4                 | [b32403a45f](https://linux-hardware.org/?probe=b32403a45f) | Jan 16, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [7398e123b9](https://linux-hardware.org/?probe=7398e123b9) | Jan 16, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [0fee6d88f1](https://linux-hardware.org/?probe=0fee6d88f1) | Jan 15, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [3382b10d32](https://linux-hardware.org/?probe=3382b10d32) | Jan 14, 2024 |
| Apple         | MacBookPro8,1               | [56c544af3a](https://linux-hardware.org/?probe=56c544af3a) | Jan 12, 2024 |
| Apple         | MacBookPro8,1               | [a245d0825c](https://linux-hardware.org/?probe=a245d0825c) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [5479dc0213](https://linux-hardware.org/?probe=5479dc0213) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [48bddf33da](https://linux-hardware.org/?probe=48bddf33da) | Jan 11, 2024 |
| Dell          | Precision 7720              | [7466090144](https://linux-hardware.org/?probe=7466090144) | Jan 11, 2024 |
| Toshiba       | Satellite A215              | [486dfc11fe](https://linux-hardware.org/?probe=486dfc11fe) | Jan 11, 2024 |
| ASUSTek       | N56JR                       | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Dell          | Inspiron N5110              | [1665424e63](https://linux-hardware.org/?probe=1665424e63) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Dell          | Inspiron N5110              | [5e233e08dc](https://linux-hardware.org/?probe=5e233e08dc) | Jan 10, 2024 |
| HP            | ENVY Laptop 13-ah0xxx       | [8fde8d2ee6](https://linux-hardware.org/?probe=8fde8d2ee6) | Jan 09, 2024 |
| HP            | Laptop 15-ef1xxx            | [ab9812dca2](https://linux-hardware.org/?probe=ab9812dca2) | Jan 08, 2024 |
| ASUSTek       | Unknown                     | [1a45402238](https://linux-hardware.org/?probe=1a45402238) | Jan 08, 2024 |
| Toshiba       | Satellite L655              | [29fa7bdb5e](https://linux-hardware.org/?probe=29fa7bdb5e) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [0fbaacab13](https://linux-hardware.org/?probe=0fbaacab13) | Jan 07, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [e26a035827](https://linux-hardware.org/?probe=e26a035827) | Jan 07, 2024 |
| Toshiba       | Satellite L55D-B            | [e0358ccedc](https://linux-hardware.org/?probe=e0358ccedc) | Jan 06, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [42bd246eae](https://linux-hardware.org/?probe=42bd246eae) | Jan 05, 2024 |
| HP            | Laptop 15-ef1xxx            | [3f8d3f0aec](https://linux-hardware.org/?probe=3f8d3f0aec) | Jan 04, 2024 |
| Toshiba       | Satellite L635              | [c32ce4ff4d](https://linux-hardware.org/?probe=c32ce4ff4d) | Jan 04, 2024 |
| Acer          | Aspire A315-21              | [7d4f4c0cbc](https://linux-hardware.org/?probe=7d4f4c0cbc) | Jan 04, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [ab04c74157](https://linux-hardware.org/?probe=ab04c74157) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| Apple         | MacBookPro7,1               | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [6a6513cf92](https://linux-hardware.org/?probe=6a6513cf92) | Jan 01, 2024 |
| Google        | Blorb                       | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| HP            | ENVY m4                     | [6416f24210](https://linux-hardware.org/?probe=6416f24210) | Dec 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [394c35d74b](https://linux-hardware.org/?probe=394c35d74b) | Dec 30, 2023 |
| HP            | ENVY m4                     | [f0cd285399](https://linux-hardware.org/?probe=f0cd285399) | Dec 30, 2023 |
| Razer         | Blade                       | [87f8a27b0a](https://linux-hardware.org/?probe=87f8a27b0a) | Dec 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [d5ac5fcf72](https://linux-hardware.org/?probe=d5ac5fcf72) | Dec 29, 2023 |
| Lenovo        | 3000 N500 42333GS           | [523a81b813](https://linux-hardware.org/?probe=523a81b813) | Dec 29, 2023 |
| Gateway       | MX3235m                     | [074b414446](https://linux-hardware.org/?probe=074b414446) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [283075fa43](https://linux-hardware.org/?probe=283075fa43) | Dec 28, 2023 |
| Dell          | Latitude 3380               | [4f9660f132](https://linux-hardware.org/?probe=4f9660f132) | Dec 28, 2023 |
| Dell          | Latitude 3380               | [bb1422b9bd](https://linux-hardware.org/?probe=bb1422b9bd) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [82dda49ee8](https://linux-hardware.org/?probe=82dda49ee8) | Dec 27, 2023 |
| Lenovo        | IdeaPad S145-14API 81UV     | [bd8145e3db](https://linux-hardware.org/?probe=bd8145e3db) | Dec 27, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [df9f1cce5b](https://linux-hardware.org/?probe=df9f1cce5b) | Dec 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [626b056720](https://linux-hardware.org/?probe=626b056720) | Dec 27, 2023 |
| Apple         | MacBookPro13,1              | [63344458c9](https://linux-hardware.org/?probe=63344458c9) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | [c7758c21ce](https://linux-hardware.org/?probe=c7758c21ce) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | [a456e712b7](https://linux-hardware.org/?probe=a456e712b7) | Dec 26, 2023 |
| HP            | ENVY Notebook               | [6ffaa62d3d](https://linux-hardware.org/?probe=6ffaa62d3d) | Dec 26, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [53e2517636](https://linux-hardware.org/?probe=53e2517636) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| HP            | Pavilion dm4                | [f077672580](https://linux-hardware.org/?probe=f077672580) | Dec 25, 2023 |
| Apple         | MacBookPro13,1              | [555e444fe5](https://linux-hardware.org/?probe=555e444fe5) | Dec 25, 2023 |
| ASUSTek       | X411UN                      | [c0cf1b362d](https://linux-hardware.org/?probe=c0cf1b362d) | Dec 25, 2023 |
| Lenovo        | ThinkPad T400 6474AV5       | [b98f0a2c09](https://linux-hardware.org/?probe=b98f0a2c09) | Dec 24, 2023 |
| Acer          | Aspire 5250                 | [224ca602f3](https://linux-hardware.org/?probe=224ca602f3) | Dec 24, 2023 |
| Gateway       | NV59C                       | [1537866140](https://linux-hardware.org/?probe=1537866140) | Dec 23, 2023 |
| Unknown       | W1415A                      | [f1fbd72c23](https://linux-hardware.org/?probe=f1fbd72c23) | Dec 23, 2023 |
| Gateway       | NV59C                       | [62d62c0a3b](https://linux-hardware.org/?probe=62d62c0a3b) | Dec 22, 2023 |
| HP            | ENVY Notebook               | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| Google        | Bobba                       | [c0e8038184](https://linux-hardware.org/?probe=c0e8038184) | Dec 22, 2023 |
| Google        | Bobba                       | [c03b219f2e](https://linux-hardware.org/?probe=c03b219f2e) | Dec 22, 2023 |
| Dell          | Inspiron 3541               | [67f350fefc](https://linux-hardware.org/?probe=67f350fefc) | Dec 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| Dell          | G7 7700                     | [506de63cb5](https://linux-hardware.org/?probe=506de63cb5) | Dec 20, 2023 |
| HP            | EliteBook 8460p             | [38ac246006](https://linux-hardware.org/?probe=38ac246006) | Dec 19, 2023 |
| Toshiba       | NB505                       | [7aa351f4c3](https://linux-hardware.org/?probe=7aa351f4c3) | Dec 19, 2023 |
| Toshiba       | NB505                       | [9ed9ded2ea](https://linux-hardware.org/?probe=9ed9ded2ea) | Dec 19, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [b0526a42f4](https://linux-hardware.org/?probe=b0526a42f4) | Dec 18, 2023 |
| HP            | Compaq CQ45                 | [2d0f39803d](https://linux-hardware.org/?probe=2d0f39803d) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | [e85c54f3fd](https://linux-hardware.org/?probe=e85c54f3fd) | Dec 17, 2023 |
| HUAWEI        | BoDE-WXX9                   | [e9f2e211bd](https://linux-hardware.org/?probe=e9f2e211bd) | Dec 16, 2023 |
| HP            | G60                         | [9fabfc936c](https://linux-hardware.org/?probe=9fabfc936c) | Dec 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Dell          | Inspiron 3501               | [67a35f1dd7](https://linux-hardware.org/?probe=67a35f1dd7) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| Dell          | Latitude 3480               | [ee6070cfbe](https://linux-hardware.org/?probe=ee6070cfbe) | Dec 09, 2023 |
| HP            | Compaq 6720s                | [63200c945b](https://linux-hardware.org/?probe=63200c945b) | Dec 08, 2023 |
| HUAWEI        | BoDE-WXX9                   | [44e608daff](https://linux-hardware.org/?probe=44e608daff) | Dec 08, 2023 |
| VPU Compan... | VWNC71429-S                 | [c0b0f86403](https://linux-hardware.org/?probe=c0b0f86403) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| MSI           | GF63 Thin 10SC              | [9c8600990d](https://linux-hardware.org/?probe=9c8600990d) | Dec 07, 2023 |
| Valve         | Jupiter                     | [bbb500139e](https://linux-hardware.org/?probe=bbb500139e) | Dec 07, 2023 |
| HP            | EliteBook 8460p             | [747cf33a22](https://linux-hardware.org/?probe=747cf33a22) | Dec 06, 2023 |
| HP            | ENVY Notebook               | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| ASUSTek       | X556UQK                     | [de505ab1fd](https://linux-hardware.org/?probe=de505ab1fd) | Dec 05, 2023 |
| Toshiba       | Satellite S75-B             | [dbec4c564e](https://linux-hardware.org/?probe=dbec4c564e) | Dec 05, 2023 |
| Valve         | Jupiter                     | [2a17ca7efe](https://linux-hardware.org/?probe=2a17ca7efe) | Dec 05, 2023 |
| Acer          | Aspire A515-55              | [0c467a2af3](https://linux-hardware.org/?probe=0c467a2af3) | Dec 04, 2023 |
| HP            | Laptop 17t-cn200            | [26c356c486](https://linux-hardware.org/?probe=26c356c486) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Gateway       | M-6812M                     | [008f6448dc](https://linux-hardware.org/?probe=008f6448dc) | Dec 03, 2023 |
| GPU Compan... | GWNR71517                   | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [54f08c139f](https://linux-hardware.org/?probe=54f08c139f) | Dec 02, 2023 |
| HP            | Laptop 15-da0xxx            | [6aff076a55](https://linux-hardware.org/?probe=6aff076a55) | Dec 01, 2023 |
| Toshiba       | Satellite A215              | [dcde3a9390](https://linux-hardware.org/?probe=dcde3a9390) | Dec 01, 2023 |
| Dell          | Latitude 3480               | [f83ad2bb01](https://linux-hardware.org/?probe=f83ad2bb01) | Nov 30, 2023 |
| Dell          | Latitude E6420              | [12b36e0bb9](https://linux-hardware.org/?probe=12b36e0bb9) | Nov 30, 2023 |
| PC Special... | Recoil 16                   | [3dd3569b17](https://linux-hardware.org/?probe=3dd3569b17) | Nov 29, 2023 |
| ASUSTek       | X441NA                      | [6965a13f84](https://linux-hardware.org/?probe=6965a13f84) | Nov 29, 2023 |
| HP            | 245 G4 Notebook PC          | [ef0bb61d83](https://linux-hardware.org/?probe=ef0bb61d83) | Nov 27, 2023 |
| HP            | 245 G4 Notebook PC          | [4a48fe8985](https://linux-hardware.org/?probe=4a48fe8985) | Nov 27, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [54e171f5dc](https://linux-hardware.org/?probe=54e171f5dc) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | [c3c18efc38](https://linux-hardware.org/?probe=c3c18efc38) | Nov 27, 2023 |
| HP            | G42                         | [b53c2fe1be](https://linux-hardware.org/?probe=b53c2fe1be) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | [33d8baae78](https://linux-hardware.org/?probe=33d8baae78) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [c68a8b3cc0](https://linux-hardware.org/?probe=c68a8b3cc0) | Nov 25, 2023 |
| HUAWEI        | HVY-WXX9                    | [e17bdfe79f](https://linux-hardware.org/?probe=e17bdfe79f) | Nov 25, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [5cbdf33238](https://linux-hardware.org/?probe=5cbdf33238) | Nov 25, 2023 |
| HP            | Laptop 15-da0xxx            | [ea0a7aa615](https://linux-hardware.org/?probe=ea0a7aa615) | Nov 24, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [432ec62dd0](https://linux-hardware.org/?probe=432ec62dd0) | Nov 24, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [85f5270891](https://linux-hardware.org/?probe=85f5270891) | Nov 23, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [8b107cb438](https://linux-hardware.org/?probe=8b107cb438) | Nov 23, 2023 |
| HUAWEI        | NbDE-WXX9                   | [c5d9332805](https://linux-hardware.org/?probe=c5d9332805) | Nov 23, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [522acd0620](https://linux-hardware.org/?probe=522acd0620) | Nov 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6b88b81e69](https://linux-hardware.org/?probe=6b88b81e69) | Nov 21, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [7273b32790](https://linux-hardware.org/?probe=7273b32790) | Nov 20, 2023 |
| Alienware     | m15 R7 AMD                  | [cc1ff7f9a8](https://linux-hardware.org/?probe=cc1ff7f9a8) | Nov 18, 2023 |
| Dell          | Inspiron 15 3515            | [c526bb7fac](https://linux-hardware.org/?probe=c526bb7fac) | Nov 17, 2023 |
| Dell          | Inspiron 15 3515            | [ea21fd1e60](https://linux-hardware.org/?probe=ea21fd1e60) | Nov 17, 2023 |
| Dell          | Latitude 5520               | [234733a1e4](https://linux-hardware.org/?probe=234733a1e4) | Nov 17, 2023 |
| Dell          | System XPS L502X            | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [3e6ad056d6](https://linux-hardware.org/?probe=3e6ad056d6) | Nov 16, 2023 |
| Dell          | Precision 7520              | [f004d80157](https://linux-hardware.org/?probe=f004d80157) | Nov 16, 2023 |
| Acer          | Aspire ES1-512              | [03c6bfd1ee](https://linux-hardware.org/?probe=03c6bfd1ee) | Nov 15, 2023 |
| Acer          | Aspire ES1-512              | [41ae79ffa6](https://linux-hardware.org/?probe=41ae79ffa6) | Nov 15, 2023 |
| Apple         | MacBookPro5,5               | [870fedf2eb](https://linux-hardware.org/?probe=870fedf2eb) | Nov 15, 2023 |
| Dell          | Latitude 7390 2-in-1        | [f92b2d58ec](https://linux-hardware.org/?probe=f92b2d58ec) | Nov 14, 2023 |
| ASUSTek       | X555QG                      | [243bc51d12](https://linux-hardware.org/?probe=243bc51d12) | Nov 14, 2023 |
| Unknown       | Unknown                     | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| Apple         | MacBookPro5,5               | [87e3c4fa90](https://linux-hardware.org/?probe=87e3c4fa90) | Nov 12, 2023 |
| Valve         | Jupiter                     | [1f6282ce11](https://linux-hardware.org/?probe=1f6282ce11) | Nov 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [0c76c82295](https://linux-hardware.org/?probe=0c76c82295) | Nov 11, 2023 |
| HP            | Pavilion Notebook           | [164a2ae911](https://linux-hardware.org/?probe=164a2ae911) | Nov 10, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [71b28a2547](https://linux-hardware.org/?probe=71b28a2547) | Nov 10, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [89417204e0](https://linux-hardware.org/?probe=89417204e0) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [4af4346c2a](https://linux-hardware.org/?probe=4af4346c2a) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [745cc9650d](https://linux-hardware.org/?probe=745cc9650d) | Nov 08, 2023 |
| MACHENIKE     | L16P                        | [c8e67672f3](https://linux-hardware.org/?probe=c8e67672f3) | Nov 08, 2023 |
| Apple         | MacBook5,1                  | [ed339d2cbb](https://linux-hardware.org/?probe=ed339d2cbb) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [5cfd80c832](https://linux-hardware.org/?probe=5cfd80c832) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [675571ef30](https://linux-hardware.org/?probe=675571ef30) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b3df6b76e8](https://linux-hardware.org/?probe=b3df6b76e8) | Nov 08, 2023 |
| Acer          | Aspire ES1-531              | [9fd8344477](https://linux-hardware.org/?probe=9fd8344477) | Nov 07, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [5cfef4c0b7](https://linux-hardware.org/?probe=5cfef4c0b7) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [f1d9fe0bb7](https://linux-hardware.org/?probe=f1d9fe0bb7) | Nov 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| American M... | A6                          | [4ff43d7d31](https://linux-hardware.org/?probe=4ff43d7d31) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| Alienware     | 14                          | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| Toshiba       | Satellite A215              | [de8e05d9e3](https://linux-hardware.org/?probe=de8e05d9e3) | Nov 01, 2023 |
| Toshiba       | Satellite A215              | [4c2cc71fc2](https://linux-hardware.org/?probe=4c2cc71fc2) | Nov 01, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| Dell          | Latitude 5480               | [1bf5aeba87](https://linux-hardware.org/?probe=1bf5aeba87) | Nov 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [d7b08bbbab](https://linux-hardware.org/?probe=d7b08bbbab) | Nov 01, 2023 |
| Toshiba       | Satellite L845              | [90e266bd8e](https://linux-hardware.org/?probe=90e266bd8e) | Oct 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17f4f01635](https://linux-hardware.org/?probe=17f4f01635) | Oct 30, 2023 |
| Lenovo        | B40-45 20394                | [ef45bdcea9](https://linux-hardware.org/?probe=ef45bdcea9) | Oct 28, 2023 |
| HP            | 6360t                       | [d0f94e770b](https://linux-hardware.org/?probe=d0f94e770b) | Oct 28, 2023 |
| Dell          | Inspiron 3451               | [2c1267e536](https://linux-hardware.org/?probe=2c1267e536) | Oct 27, 2023 |
| HP            | Notebook                    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [303c4197c7](https://linux-hardware.org/?probe=303c4197c7) | Oct 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [b270ca3670](https://linux-hardware.org/?probe=b270ca3670) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Acer          | Aspire R3-431T              | [eb6c623c2d](https://linux-hardware.org/?probe=eb6c623c2d) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| Apple         | MacBookPro8,1               | [fde726622c](https://linux-hardware.org/?probe=fde726622c) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | [116946c81c](https://linux-hardware.org/?probe=116946c81c) | Oct 22, 2023 |
| HP            | Notebook                    | [e8c7b38b1b](https://linux-hardware.org/?probe=e8c7b38b1b) | Oct 21, 2023 |
| Google        | Pirika                      | [98eea3bc0f](https://linux-hardware.org/?probe=98eea3bc0f) | Oct 20, 2023 |
| HP            | ProBook 655 G1              | [8e1cb99809](https://linux-hardware.org/?probe=8e1cb99809) | Oct 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| HP            | ProBook 655 G1              | [a80cd678f2](https://linux-hardware.org/?probe=a80cd678f2) | Oct 18, 2023 |
| Dell          | G7 7790                     | [250d61d6a7](https://linux-hardware.org/?probe=250d61d6a7) | Oct 18, 2023 |
| Apple         | MacBookPro6,2               | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [501f7abc3b](https://linux-hardware.org/?probe=501f7abc3b) | Oct 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [4593a22b63](https://linux-hardware.org/?probe=4593a22b63) | Oct 18, 2023 |
| Google        | Treeya                      | [1cf43225f5](https://linux-hardware.org/?probe=1cf43225f5) | Oct 17, 2023 |
| Google        | Treeya                      | [6f05b84b18](https://linux-hardware.org/?probe=6f05b84b18) | Oct 17, 2023 |
| HP            | 630                         | [db6efff83b](https://linux-hardware.org/?probe=db6efff83b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| HP            | Laptop 15-dy2xxx            | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| Dell          | Inspiron 5575               | [c50573f4ae](https://linux-hardware.org/?probe=c50573f4ae) | Oct 14, 2023 |
| HP            | 240 G8 Notebook PC          | [df4a5a4722](https://linux-hardware.org/?probe=df4a5a4722) | Oct 14, 2023 |
| Dell          | Inspiron 1318               | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| Timi          | RedmiBook 13 R              | [a39c380c4f](https://linux-hardware.org/?probe=a39c380c4f) | Oct 13, 2023 |
| Sony          | VPCEB15EL                   | [f7a3de3793](https://linux-hardware.org/?probe=f7a3de3793) | Oct 13, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [94e6d9d3cb](https://linux-hardware.org/?probe=94e6d9d3cb) | Oct 13, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [fb51024b14](https://linux-hardware.org/?probe=fb51024b14) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | [27b7cf72ac](https://linux-hardware.org/?probe=27b7cf72ac) | Oct 13, 2023 |
| Lenovo        | G40-45 80E1                 | [365f77219e](https://linux-hardware.org/?probe=365f77219e) | Oct 11, 2023 |
| HP            | 240 G8 Notebook PC          | [d582dc334c](https://linux-hardware.org/?probe=d582dc334c) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| Dell          | Latitude E6440              | [7471faa299](https://linux-hardware.org/?probe=7471faa299) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| Dell          | XPS 15 9530                 | [e1ff6e4124](https://linux-hardware.org/?probe=e1ff6e4124) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [83fd464aa8](https://linux-hardware.org/?probe=83fd464aa8) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [035c4dbf68](https://linux-hardware.org/?probe=035c4dbf68) | Oct 08, 2023 |
| Toshiba       | Satellite A305D             | [d2fc1d1762](https://linux-hardware.org/?probe=d2fc1d1762) | Oct 07, 2023 |
| Thomson       | WWN15I5-8BK1T               | [10ca155743](https://linux-hardware.org/?probe=10ca155743) | Oct 06, 2023 |
| Acer          | Aspire E1-531               | [9d54872fa1](https://linux-hardware.org/?probe=9d54872fa1) | Oct 05, 2023 |
| Acer          | Aspire E1-531               | [ad0cc18353](https://linux-hardware.org/?probe=ad0cc18353) | Oct 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ef041058aa](https://linux-hardware.org/?probe=ef041058aa) | Oct 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [75be134738](https://linux-hardware.org/?probe=75be134738) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Sony          | VPCEG10EL                   | [1c789caaec](https://linux-hardware.org/?probe=1c789caaec) | Oct 04, 2023 |
| HP            | Laptop 15-db0xxx            | [d2e42707c6](https://linux-hardware.org/?probe=d2e42707c6) | Oct 04, 2023 |
| Dell          | Latitude E6410              | [0b58de80dd](https://linux-hardware.org/?probe=0b58de80dd) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Toshiba       | Satellite L735              | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| Sony          | VPCEG10EL                   | [8271942cc2](https://linux-hardware.org/?probe=8271942cc2) | Sep 30, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Acer          | Aspire E1-531               | [6b981869d7](https://linux-hardware.org/?probe=6b981869d7) | Sep 27, 2023 |
| Sony          | VPCEG10EL                   | [7bfbe9b21d](https://linux-hardware.org/?probe=7bfbe9b21d) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | [d47b59c89b](https://linux-hardware.org/?probe=d47b59c89b) | Sep 27, 2023 |
| Toshiba       | dynabook T350/46BW          | [26ffaa1c0f](https://linux-hardware.org/?probe=26ffaa1c0f) | Sep 27, 2023 |
| Acer          | Nitro AN515-44              | [0ba9157463](https://linux-hardware.org/?probe=0ba9157463) | Sep 27, 2023 |
| HP            | Pavilion 14                 | [a7589d8c93](https://linux-hardware.org/?probe=a7589d8c93) | Sep 26, 2023 |
| HP            | Pavilion 14                 | [1aed6aba04](https://linux-hardware.org/?probe=1aed6aba04) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| Dell          | Latitude E5470              | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| HP            | Laptop 14-cm0xxx            | [2af47d0dca](https://linux-hardware.org/?probe=2af47d0dca) | Sep 24, 2023 |
| GPU Compan... | GWNR71517                   | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| Dell          | Inspiron 1464               | [026e1e3391](https://linux-hardware.org/?probe=026e1e3391) | Sep 21, 2023 |
| Valve         | Jupiter                     | [2b2966eb3d](https://linux-hardware.org/?probe=2b2966eb3d) | Sep 21, 2023 |
| Dell          | Inspiron 1464               | [bdb084e4a8](https://linux-hardware.org/?probe=bdb084e4a8) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| HP            | ProBook 6475b               | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| HP            | Dragonfly Pro               | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | Inspiron 1464               | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [361c6cb056](https://linux-hardware.org/?probe=361c6cb056) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [4ff9edf944](https://linux-hardware.org/?probe=4ff9edf944) | Sep 12, 2023 |
| Dell          | XPS 15 9530                 | [26b3fd07ae](https://linux-hardware.org/?probe=26b3fd07ae) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Dell          | Precision 7520              | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| ASUSTek       | G750JW                      | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| Unknown       | W1415A                      | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Google        | Pirika                      | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Dell          | Latitude 5480               | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E5450              | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Apple         | MacBookPro13,1              | [54f48be7f6](https://linux-hardware.org/?probe=54f48be7f6) | Sep 06, 2023 |
| Google        | Pirika                      | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Acer          | Aspire E1-531               | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| HP            | 240 G3                      | [24381b91f7](https://linux-hardware.org/?probe=24381b91f7) | Sep 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [6b895a5320](https://linux-hardware.org/?probe=6b895a5320) | Sep 03, 2023 |
| Valve         | Jupiter                     | [9e037b28bc](https://linux-hardware.org/?probe=9e037b28bc) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | [88d1350771](https://linux-hardware.org/?probe=88d1350771) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [de36e26c21](https://linux-hardware.org/?probe=de36e26c21) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | [fe660fb390](https://linux-hardware.org/?probe=fe660fb390) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| HP            | ProBook 6460b               | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Dell          | Inspiron 1464               | [1020c99eec](https://linux-hardware.org/?probe=1020c99eec) | Aug 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Google        | Treeya                      | [396f71a402](https://linux-hardware.org/?probe=396f71a402) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| HP            | Laptop 15-bs0xx             | [f8a316e74c](https://linux-hardware.org/?probe=f8a316e74c) | Aug 27, 2023 |
| Acer          | Aspire V5-471P              | [fcbacf6769](https://linux-hardware.org/?probe=fcbacf6769) | Aug 26, 2023 |
| Dell          | G15 5510                    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| Google        | Pirika                      | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Unknown       | Unknown                     | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Dell          | Latitude E6430              | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| Acer          | Aspire E1-531               | [ca5348bd31](https://linux-hardware.org/?probe=ca5348bd31) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| Dell          | Latitude E6430              | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Dell          | Latitude E7440              | [edae1bc7d3](https://linux-hardware.org/?probe=edae1bc7d3) | Aug 21, 2023 |
| Dell          | Latitude E6430              | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| Lenovo        | G50-30 80G0                 | [54c2ded452](https://linux-hardware.org/?probe=54c2ded452) | Aug 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [68df495196](https://linux-hardware.org/?probe=68df495196) | Aug 19, 2023 |
| Lenovo        | Rev B 82KU                  | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| Lenovo        | S10-3                       | [d1c8fb66ec](https://linux-hardware.org/?probe=d1c8fb66ec) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| Dell          | Inspiron 3505               | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| Acer          | Nitro AN515-55              | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Valve         | Jupiter                     | [069bfd618c](https://linux-hardware.org/?probe=069bfd618c) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [d6f18c79f6](https://linux-hardware.org/?probe=d6f18c79f6) | Aug 10, 2023 |
| Toshiba       | Satellite L745D             | [9576dab2b0](https://linux-hardware.org/?probe=9576dab2b0) | Aug 09, 2023 |
| Dell          | Precision 3551              | [a9b776ade0](https://linux-hardware.org/?probe=a9b776ade0) | Aug 09, 2023 |
| ASUSTek       | X455LA                      | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [0c8aef568d](https://linux-hardware.org/?probe=0c8aef568d) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [597f8ddaf2](https://linux-hardware.org/?probe=597f8ddaf2) | Aug 06, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [9f813efccc](https://linux-hardware.org/?probe=9f813efccc) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [349326315f](https://linux-hardware.org/?probe=349326315f) | Aug 05, 2023 |
| Dell          | Latitude 5490               | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Dell          | Latitude E6440              | [c00884f2cd](https://linux-hardware.org/?probe=c00884f2cd) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Anbernic      | Win600                      | [6d076e4bc9](https://linux-hardware.org/?probe=6d076e4bc9) | Aug 02, 2023 |
| Dell          | Inspiron 5567               | [6f220fcf23](https://linux-hardware.org/?probe=6f220fcf23) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d6c2eae395](https://linux-hardware.org/?probe=d6c2eae395) | Aug 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [39774f9f5d](https://linux-hardware.org/?probe=39774f9f5d) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| VPU Compan... | VWNC71429-S                 | [2a21ab7b53](https://linux-hardware.org/?probe=2a21ab7b53) | Jul 31, 2023 |
| HP            | 255 G7 Notebook PC          | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| HONOR         | BMH-WCX9                    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| Lenovo        | G40-45 80E1                 | [27af99ec54](https://linux-hardware.org/?probe=27af99ec54) | Jul 28, 2023 |
| HUAWEI        | BOM-WXX9                    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| Dell          | Inspiron 5570               | [fb125d5fcb](https://linux-hardware.org/?probe=fb125d5fcb) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Apple         | MacBookPro8,1               | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| Dell          | Latitude E7450              | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [39ea43d323](https://linux-hardware.org/?probe=39ea43d323) | Jul 20, 2023 |
| Dell          | Latitude 5420               | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| HP            | ENVY Notebook               | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [666c1c0162](https://linux-hardware.org/?probe=666c1c0162) | Jul 18, 2023 |
| HP            | G42                         | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| Apple         | MacBookAir6,2               | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| MSI           | GE72MVR 7RG                 | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| HP            | Laptop 14-fq1xxx            | [2687ecdde1](https://linux-hardware.org/?probe=2687ecdde1) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| GPU Compan... | GWTC51427                   | [138ef93d27](https://linux-hardware.org/?probe=138ef93d27) | Jul 13, 2023 |
| Apple         | MacBookPro12,1              | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| HP            | Laptop 14-cm0xxx            | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| Acer          | Aspire ES1-511              | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| Dell          | Precision M6700             | [ec5b230e37](https://linux-hardware.org/?probe=ec5b230e37) | Jul 09, 2023 |
| Sony          | VPCF236FM                   | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [883185ea85](https://linux-hardware.org/?probe=883185ea85) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Acer          | Aspire V5-472               | [663adbe947](https://linux-hardware.org/?probe=663adbe947) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| Dell          | Inspiron 5555               | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| HP            | 550                         | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Lenovo        | ThinkPad L430 246634S       | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Alienware     | 17 R4                       | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | [683b7b2dc2](https://linux-hardware.org/?probe=683b7b2dc2) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | [558a5b8a7f](https://linux-hardware.org/?probe=558a5b8a7f) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [ef5eb06f90](https://linux-hardware.org/?probe=ef5eb06f90) | Jun 24, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [44b5bb5453](https://linux-hardware.org/?probe=44b5bb5453) | Jun 23, 2023 |
| Dell          | Latitude E5470              | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [696e42eaba](https://linux-hardware.org/?probe=696e42eaba) | Jun 20, 2023 |
| ASUSTek       | TP501UA                     | [e883c61561](https://linux-hardware.org/?probe=e883c61561) | Jun 19, 2023 |
| Dell          | Latitude 5531               | [bf22616526](https://linux-hardware.org/?probe=bf22616526) | Jun 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude E6320              | [f1552f3016](https://linux-hardware.org/?probe=f1552f3016) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | [1869c3f4dc](https://linux-hardware.org/?probe=1869c3f4dc) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | [2aed95c237](https://linux-hardware.org/?probe=2aed95c237) | Jun 16, 2023 |
| Dell          | Inspiron 5548               | [547ffd8db7](https://linux-hardware.org/?probe=547ffd8db7) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| Acer          | Aspire V5-472               | [58dc632831](https://linux-hardware.org/?probe=58dc632831) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| HP            | Laptop 15-db0xxx            | [ca0a511cd7](https://linux-hardware.org/?probe=ca0a511cd7) | Jun 14, 2023 |
| HP            | G61                         | [52e962e82d](https://linux-hardware.org/?probe=52e962e82d) | Jun 14, 2023 |
| Dell          | Latitude 5590               | [56f8f9bbaf](https://linux-hardware.org/?probe=56f8f9bbaf) | Jun 14, 2023 |
| HP            | Pavilion Notebook           | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Gateway       | NE572                       | [771f8d0d63](https://linux-hardware.org/?probe=771f8d0d63) | Jun 13, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| HUAWEI        | HVY-WXX9                    | [4cf431ecc8](https://linux-hardware.org/?probe=4cf431ecc8) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2c5f9d83bd](https://linux-hardware.org/?probe=2c5f9d83bd) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| Dell          | Latitude 5590               | [f6347f5d6b](https://linux-hardware.org/?probe=f6347f5d6b) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| HP            | Laptop 15-db0xxx            | [03f0e4060e](https://linux-hardware.org/?probe=03f0e4060e) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| Acer          | Nitro AN515-55              | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Latitude E6400              | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| HP            | Pavilion g4                 | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Dell          | Inspiron 5559               | [9ee7eff678](https://linux-hardware.org/?probe=9ee7eff678) | Jun 04, 2023 |
| Lanix         | AL V9                       | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| Dell          | Inspiron 5555               | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Dell          | Latitude E5470              | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| Valve         | Jupiter                     | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Acer          | AO756                       | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Acer          | Aspire E5-573               | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Dell          | Latitude E5470              | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Dell          | Inspiron 5548               | [5665ccbc0a](https://linux-hardware.org/?probe=5665ccbc0a) | May 23, 2023 |
| Toshiba       | Satellite C645D             | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| HP            | Pavilion dm4                | [81f264e4ef](https://linux-hardware.org/?probe=81f264e4ef) | May 22, 2023 |
| HP            | Pavilion dm4                | [1f1a9e3f62](https://linux-hardware.org/?probe=1f1a9e3f62) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| HP            | Pavilion dm4                | [e25186a486](https://linux-hardware.org/?probe=e25186a486) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| Apple         | MacBookPro12,1              | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| Lenovo        | G50-30 80G0                 | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HP            | Pavilion Notebook           | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| ASUSTek       | G73Sw                       | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Samsung       | R530/R730                   | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| Apple         | MacBookPro9,2               | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | Laptop 14-dk0xxx            | [e644ef3b24](https://linux-hardware.org/?probe=e644ef3b24) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| eMachines     | E625                        | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| eMachines     | E625                        | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | [82c3d7dd74](https://linux-hardware.org/?probe=82c3d7dd74) | May 09, 2023 |
| Lanix Amer... | A V19                       | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| HP            | 15                          | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| Apple         | MacBookPro9,2               | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| HP            | Pavilion g4                 | [55a4a7978e](https://linux-hardware.org/?probe=55a4a7978e) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | [fe2f2e420f](https://linux-hardware.org/?probe=fe2f2e420f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| Acer          | Aspire A315-56              | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| DERE          | X16                         | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Toshiba       | Satellite C845              | [8174d09074](https://linux-hardware.org/?probe=8174d09074) | Apr 21, 2023 |
| Dell          | G15 5510                    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| HP            | ProBook 655 G1              | [aaef8a36db](https://linux-hardware.org/?probe=aaef8a36db) | Apr 10, 2023 |
| Gateway       | M-6812M                     | [6101b79a06](https://linux-hardware.org/?probe=6101b79a06) | Apr 08, 2023 |
| Samsung       | RV415/RV515                 | [fe77afbdfa](https://linux-hardware.org/?probe=fe77afbdfa) | Apr 07, 2023 |
| HP            | ProBook 6360b               | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| Acer          | Aspire 3680                 | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| Apple         | MacBookPro10,2              | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Notebook      | L140PU                      | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Valve         | Jupiter                     | [7a6dcc077f](https://linux-hardware.org/?probe=7a6dcc077f) | Apr 03, 2023 |
| HP            | Unknown                     | [bd783cf180](https://linux-hardware.org/?probe=bd783cf180) | Apr 03, 2023 |
| HP            | 2000                        | [3fffec7875](https://linux-hardware.org/?probe=3fffec7875) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Dell          | System XPS L502X            | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [111eeac3b3](https://linux-hardware.org/?probe=111eeac3b3) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [2fcab6a925](https://linux-hardware.org/?probe=2fcab6a925) | Apr 01, 2023 |
| EVOO          | EVC156-1                    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [f5db7a6030](https://linux-hardware.org/?probe=f5db7a6030) | Mar 30, 2023 |
| HP            | Notebook                    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Apple         | MacBookPro8,3               | [90fadbf903](https://linux-hardware.org/?probe=90fadbf903) | Mar 28, 2023 |
| Apple         | MacBookPro9,2               | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | [5e4e7975c1](https://linux-hardware.org/?probe=5e4e7975c1) | Mar 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Toshiba       | Satellite C845D             | [32341bde2a](https://linux-hardware.org/?probe=32341bde2a) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| American M... | XA133PR110                  | [7e49d89ca8](https://linux-hardware.org/?probe=7e49d89ca8) | Mar 25, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| HP            | Unknown                     | [c27dcda931](https://linux-hardware.org/?probe=c27dcda931) | Mar 24, 2023 |
| Dell          | Inspiron 7559               | [51aab276a2](https://linux-hardware.org/?probe=51aab276a2) | Mar 23, 2023 |
| ASUSTek       | X202EP                      | [5cc1f3216b](https://linux-hardware.org/?probe=5cc1f3216b) | Mar 23, 2023 |
| HP            | Unknown                     | [913aa678bf](https://linux-hardware.org/?probe=913aa678bf) | Mar 23, 2023 |
| Lenovo        | Yoga 500-14IBD 80N4         | [f364402e8a](https://linux-hardware.org/?probe=f364402e8a) | Mar 23, 2023 |
| HONOR         | BBR-WAX9                    | [b16e6324ed](https://linux-hardware.org/?probe=b16e6324ed) | Mar 22, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | G15 5510                    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [8a70a156a4](https://linux-hardware.org/?probe=8a70a156a4) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6dc3256710](https://linux-hardware.org/?probe=6dc3256710) | Mar 21, 2023 |
| HP            | Unknown                     | [66723d18e0](https://linux-hardware.org/?probe=66723d18e0) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [56b1138062](https://linux-hardware.org/?probe=56b1138062) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | [1fe782c379](https://linux-hardware.org/?probe=1fe782c379) | Mar 21, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Lenovo        | G40-80 80E4                 | [70b2fab92b](https://linux-hardware.org/?probe=70b2fab92b) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Toshiba       | Satellite P55t-B            | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Acer          | Aspire R3-131T              | [94435f58ed](https://linux-hardware.org/?probe=94435f58ed) | Mar 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| Dell          | G3 3500                     | [5cfed5bee9](https://linux-hardware.org/?probe=5cfed5bee9) | Mar 10, 2023 |
| HP            | Pavilion dv4                | [79a8c505ef](https://linux-hardware.org/?probe=79a8c505ef) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Dell          | Inspiron 5567               | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6f7e8084e5](https://linux-hardware.org/?probe=6f7e8084e5) | Mar 04, 2023 |
| HP            | ProBook 6360b               | [8b6826988f](https://linux-hardware.org/?probe=8b6826988f) | Mar 03, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [c3113c9da6](https://linux-hardware.org/?probe=c3113c9da6) | Mar 02, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [73efff8199](https://linux-hardware.org/?probe=73efff8199) | Mar 02, 2023 |
| HP            | Pavilion 14                 | [ae0e65f5d1](https://linux-hardware.org/?probe=ae0e65f5d1) | Feb 28, 2023 |
| Dell          | Latitude E7270              | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| HP            | Pavilion 14                 | [c9b9f213b5](https://linux-hardware.org/?probe=c9b9f213b5) | Feb 26, 2023 |
| Lenovo        | B40-45 20394                | [8472ed364a](https://linux-hardware.org/?probe=8472ed364a) | Feb 26, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| Valve         | Jupiter                     | [0ec37b6ef2](https://linux-hardware.org/?probe=0ec37b6ef2) | Feb 25, 2023 |
| Chuwi         | HeroBook Air                | [8daed679c2](https://linux-hardware.org/?probe=8daed679c2) | Feb 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [bfd3019210](https://linux-hardware.org/?probe=bfd3019210) | Feb 22, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Toshiba       | Satellite C50D-A            | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| HP            | Pavilion g6                 | [2b4de6efbe](https://linux-hardware.org/?probe=2b4de6efbe) | Feb 18, 2023 |
| Dell          | Studio 1558                 | [4a2f0524b9](https://linux-hardware.org/?probe=4a2f0524b9) | Feb 17, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Dell          | Latitude E7440              | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | [269420c3fe](https://linux-hardware.org/?probe=269420c3fe) | Feb 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de592b6218](https://linux-hardware.org/?probe=de592b6218) | Feb 14, 2023 |
| Dell          | Latitude E7270              | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| HP            | Laptop 15-da2xxx            | [41bf5d50f8](https://linux-hardware.org/?probe=41bf5d50f8) | Feb 14, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [cfeb6479d1](https://linux-hardware.org/?probe=cfeb6479d1) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Dell          | Latitude E7270              | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| HP            | 240 G3                      | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| HP            | Laptop 15-bw0xx             | [da8dac3c03](https://linux-hardware.org/?probe=da8dac3c03) | Feb 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [f7c5e9e498](https://linux-hardware.org/?probe=f7c5e9e498) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [44aed7e81a](https://linux-hardware.org/?probe=44aed7e81a) | Feb 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [5acc007668](https://linux-hardware.org/?probe=5acc007668) | Feb 04, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 240 G3                      | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| HUAWEI        | KLVD-WXX9                   | [6546c6e279](https://linux-hardware.org/?probe=6546c6e279) | Feb 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [73230e9490](https://linux-hardware.org/?probe=73230e9490) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| ASUSTek       | N56VB                       | [d5b5c983c9](https://linux-hardware.org/?probe=d5b5c983c9) | Feb 02, 2023 |
| Apple         | MacBookPro15,2              | [7c17db143e](https://linux-hardware.org/?probe=7c17db143e) | Feb 01, 2023 |
| Apple         | MacBookPro8,1               | [13467e9e83](https://linux-hardware.org/?probe=13467e9e83) | Feb 01, 2023 |
| Dell          | Latitude 5430               | [2afa57d0fa](https://linux-hardware.org/?probe=2afa57d0fa) | Feb 01, 2023 |
| Apple         | MacBookPro15,2              | [7612aba4cb](https://linux-hardware.org/?probe=7612aba4cb) | Jan 31, 2023 |
| Lenovo        | ThinkPad T430 2349A44       | [9f8528c5da](https://linux-hardware.org/?probe=9f8528c5da) | Jan 31, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| HP            | Laptop 15-dw1xxx            | [c7d825c34c](https://linux-hardware.org/?probe=c7d825c34c) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bd58d910f7](https://linux-hardware.org/?probe=bd58d910f7) | Jan 25, 2023 |
| Dell          | Latitude E5440              | [f8e7f1785b](https://linux-hardware.org/?probe=f8e7f1785b) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [65b6391803](https://linux-hardware.org/?probe=65b6391803) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Dell          | Inspiron 5558               | [bf87467519](https://linux-hardware.org/?probe=bf87467519) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [57ed6980d4](https://linux-hardware.org/?probe=57ed6980d4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [0667ad7cee](https://linux-hardware.org/?probe=0667ad7cee) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c9279b845](https://linux-hardware.org/?probe=9c9279b845) | Jan 19, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | [7e61f98275](https://linux-hardware.org/?probe=7e61f98275) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [3709c83303](https://linux-hardware.org/?probe=3709c83303) | Jan 15, 2023 |
| HUAWEI        | EMD-WXX                     | [6eeac14bb9](https://linux-hardware.org/?probe=6eeac14bb9) | Jan 15, 2023 |
| Dell          | Latitude E6440              | [d04d05f246](https://linux-hardware.org/?probe=d04d05f246) | Jan 14, 2023 |
| Lenovo        | B490 20205                  | [14243e79d2](https://linux-hardware.org/?probe=14243e79d2) | Jan 13, 2023 |
| HP            | ProBook 4230s               | [63a87864b9](https://linux-hardware.org/?probe=63a87864b9) | Jan 12, 2023 |
| HP            | ProBook 4230s               | [9a6505c0aa](https://linux-hardware.org/?probe=9a6505c0aa) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Lenovo        | Y50-70 20378                | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| Sony          | VPCEH1AFX                   | [3f64681bc7](https://linux-hardware.org/?probe=3f64681bc7) | Jan 11, 2023 |
| HP            | Pavilion Notebook           | [2132701432](https://linux-hardware.org/?probe=2132701432) | Jan 11, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Valve         | Jupiter                     | [57b570af42](https://linux-hardware.org/?probe=57b570af42) | Jan 09, 2023 |
| HP            | Pavilion 15                 | [2937882035](https://linux-hardware.org/?probe=2937882035) | Jan 08, 2023 |
| Notebook      | W9x0LU                      | [a81dd09b0c](https://linux-hardware.org/?probe=a81dd09b0c) | Jan 07, 2023 |
| HP            | Stream Laptop 11-y0XX       | [b40a3e32e9](https://linux-hardware.org/?probe=b40a3e32e9) | Jan 06, 2023 |
| HP            | Stream Laptop 11-y0XX       | [73db1ffcf6](https://linux-hardware.org/?probe=73db1ffcf6) | Jan 06, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| Lenovo        | G580 20157                  | [c0199fa7bf](https://linux-hardware.org/?probe=c0199fa7bf) | Jan 05, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | EliteBook 8460p             | [3365055862](https://linux-hardware.org/?probe=3365055862) | Jan 02, 2023 |
| HP            | EliteBook 8460p             | [45184e1f70](https://linux-hardware.org/?probe=45184e1f70) | Jan 02, 2023 |
| HP            | Laptop 15-dy2xxx            | [8c76b9ad8e](https://linux-hardware.org/?probe=8c76b9ad8e) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| Acer          | Aspire R7-371T              | [057e717cb7](https://linux-hardware.org/?probe=057e717cb7) | Dec 30, 2022 |
| HP            | 240 G7 Notebook PC          | [414db30bff](https://linux-hardware.org/?probe=414db30bff) | Dec 30, 2022 |
| ASUSTek       | N56VB                       | [6201ddc028](https://linux-hardware.org/?probe=6201ddc028) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Dell          | Inspiron MM061              | [34804f8a34](https://linux-hardware.org/?probe=34804f8a34) | Dec 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | Laptop 14-fq0xxx            | [e020678b51](https://linux-hardware.org/?probe=e020678b51) | Dec 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [8e2393e7b4](https://linux-hardware.org/?probe=8e2393e7b4) | Dec 26, 2022 |
| Acer          | Aspire E1-522               | [8bf37cf82d](https://linux-hardware.org/?probe=8bf37cf82d) | Dec 26, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Google        | Bobba360                    | [bdad461cec](https://linux-hardware.org/?probe=bdad461cec) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Dell          | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Acer          | Aspire A515-51              | [29af4c3712](https://linux-hardware.org/?probe=29af4c3712) | Dec 20, 2022 |
| Google        | Coral                       | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [96dcb47ba1](https://linux-hardware.org/?probe=96dcb47ba1) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Valve         | Jupiter                     | [f89644c711](https://linux-hardware.org/?probe=f89644c711) | Dec 15, 2022 |
| HP            | Laptop 15-da2xxx            | [cd64f27416](https://linux-hardware.org/?probe=cd64f27416) | Dec 14, 2022 |
| MSI           | GL75 Leopard 10SDK          | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [36bd6688bb](https://linux-hardware.org/?probe=36bd6688bb) | Dec 14, 2022 |
| Acer          | Aspire ES1-531              | [ed5d274c1a](https://linux-hardware.org/?probe=ed5d274c1a) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Alienware     | 15 R4                       | [f365266667](https://linux-hardware.org/?probe=f365266667) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Toshiba       | Satellite L855              | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| Sony          | VPCEE27FL                   | [dd2bc8b6ff](https://linux-hardware.org/?probe=dd2bc8b6ff) | Dec 10, 2022 |
| Dell          | Latitude E6420              | [acd81c73d0](https://linux-hardware.org/?probe=acd81c73d0) | Dec 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [38d274571d](https://linux-hardware.org/?probe=38d274571d) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Acer          | TravelMate B117-M           | [00ff19b078](https://linux-hardware.org/?probe=00ff19b078) | Dec 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 169       | 8.56%   |
| Ubuntu 22.04       | 137       | 6.94%   |
| Ubuntu 18.04       | 114       | 5.77%   |
| Zorin 16           | 54        | 2.73%   |
| Fedora 38          | 53        | 2.68%   |
| Debian 11          | 48        | 2.43%   |
| OpenMandriva 4.3   | 47        | 2.38%   |
| Manjaro            | 45        | 2.28%   |
| OpenMandriva 4.2   | 43        | 2.18%   |
| KDE neon 20.04     | 36        | 1.82%   |
| Pop!_OS 22.04      | 32        | 1.62%   |
| Arch Rolling       | 32        | 1.62%   |
| Fedora 36          | 31        | 1.57%   |
| Linux Mint 20.3    | 29        | 1.47%   |
| Fedora 39          | 29        | 1.47%   |
| KDE neon 22.04     | 25        | 1.27%   |
| Pop!_OS 20.04      | 23        | 1.16%   |
| ArcoLinux Rolling  | 23        | 1.16%   |
| OpenMandriva 23.03 | 22        | 1.11%   |
| Linux Mint 21.2    | 21        | 1.06%   |
| Fedora 37          | 21        | 1.06%   |
| Arch               | 21        | 1.06%   |
| Zorin 15           | 20        | 1.01%   |
| Linux Mint 21.1    | 20        | 1.01%   |
| Linux Mint 20      | 20        | 1.01%   |
| Debian 12          | 20        | 1.01%   |
| OpenMandriva 23.08 | 19        | 0.96%   |
| Ubuntu 19.10       | 18        | 0.91%   |
| Ubuntu 19.04       | 18        | 0.91%   |
| Linux Mint 19.3    | 18        | 0.91%   |
| Debian 10          | 18        | 0.91%   |
| Ubuntu 22.10       | 16        | 0.81%   |
| Ubuntu 21.10       | 16        | 0.81%   |
| Ubuntu 23.10       | 15        | 0.76%   |
| Ubuntu 23.04       | 15        | 0.76%   |
| Pop!_OS 21.04      | 15        | 0.76%   |
| Linux Mint 21      | 15        | 0.76%   |
| Kubuntu 20.04      | 15        | 0.76%   |
| Fedora 34          | 15        | 0.76%   |
| Xubuntu 18.04      | 14        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 533       | 28.16%  |
| Fedora        | 193       | 10.2%   |
| OpenMandriva  | 152       | 8.03%   |
| Linux Mint    | 150       | 7.92%   |
| Debian        | 97        | 5.12%   |
| Zorin         | 88        | 4.65%   |
| Pop!_OS       | 82        | 4.33%   |
| Manjaro       | 76        | 4.01%   |
| KDE neon      | 64        | 3.38%   |
| Arch          | 53        | 2.8%    |
| Kubuntu       | 42        | 2.22%   |
| Xubuntu       | 32        | 1.69%   |
| Kali          | 32        | 1.69%   |
| Elementary    | 31        | 1.64%   |
| ArcoLinux     | 23        | 1.22%   |
| openSUSE      | 22        | 1.16%   |
| SteamOS       | 17        | 0.9%    |
| ROSA          | 17        | 0.9%    |
| Lubuntu       | 14        | 0.74%   |
| Nobara        | 12        | 0.63%   |
| Endless       | 12        | 0.63%   |
| Clear Linux   | 12        | 0.63%   |
| LMDE          | 11        | 0.58%   |
| EndeavourOS   | 10        | 0.53%   |
| Ubuntu Unity  | 9         | 0.48%   |
| Ubuntu MATE   | 8         | 0.42%   |
| Ubuntu Budgie | 8         | 0.42%   |
| MX            | 8         | 0.42%   |
| Gentoo        | 8         | 0.42%   |
| Parrot        | 6         | 0.32%   |
| Garuda Linux  | 6         | 0.32%   |
| CentOS        | 6         | 0.32%   |
| Xero          | 5         | 0.26%   |
| Archcraft     | 4         | 0.21%   |
| RHEL          | 3         | 0.16%   |
| Peppermint    | 3         | 0.16%   |
| UbuntuDDE     | 2         | 0.11%   |
| Ubuntu Studio | 2         | 0.11%   |
| Solus         | 2         | 0.11%   |
| Reborn OS     | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 47        | 2.18%   |
| 5.10.14-desktop-1omv4002 | 43        | 2%      |
| 5.4.0-42-generic         | 27        | 1.25%   |
| 6.2.6-desktop-1omv2390   | 19        | 0.88%   |
| 5.4.0-58-generic         | 18        | 0.84%   |
| 5.15.0-56-generic        | 18        | 0.84%   |
| 6.4.11-desktop-1omv2390  | 17        | 0.79%   |
| 5.4.0-52-generic         | 14        | 0.65%   |
| 5.3.0-46-generic         | 14        | 0.65%   |
| 5.15.0-48-generic        | 13        | 0.6%    |
| 6.1.1-desktop-1omv2290   | 12        | 0.56%   |
| 5.4.0-91-generic         | 12        | 0.56%   |
| 5.4.0-48-generic         | 12        | 0.56%   |
| 5.19.0-38-generic        | 12        | 0.56%   |
| 5.15.0-58-generic        | 12        | 0.56%   |
| 5.11.0-27-generic        | 12        | 0.56%   |
| 5.0.0-37-generic         | 12        | 0.56%   |
| 5.3.0-40-generic         | 11        | 0.51%   |
| 5.19.0-43-generic        | 11        | 0.51%   |
| 5.15.0-43-generic        | 11        | 0.51%   |
| 5.3.0-42-generic         | 10        | 0.46%   |
| 5.19.0-35-generic        | 10        | 0.46%   |
| 5.15.0-47-generic        | 10        | 0.46%   |
| 5.13.0-39-generic        | 10        | 0.46%   |
| 5.13.0-28-generic        | 10        | 0.46%   |
| 5.11.0-43-generic        | 10        | 0.46%   |
| 6.5.0-14-generic         | 9         | 0.42%   |
| 6.2.0-37-generic         | 9         | 0.42%   |
| 6.2.0-33-generic         | 9         | 0.42%   |
| 5.4.0-7642-generic       | 9         | 0.42%   |
| 5.4.0-74-generic         | 9         | 0.42%   |
| 5.4.0-65-generic         | 9         | 0.42%   |
| 5.4.0-45-generic         | 9         | 0.42%   |
| 5.3.0-28-generic         | 9         | 0.42%   |
| 5.15.0-91-generic        | 9         | 0.42%   |
| 5.15.0-52-generic        | 9         | 0.42%   |
| 5.13.0-40-generic        | 9         | 0.42%   |
| 5.11.0-7620-generic      | 9         | 0.42%   |
| 5.11.0-37-generic        | 9         | 0.42%   |
| 6.2.6-76060206-generic   | 8         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 239       | 11.73%  |
| 5.15.0  | 193       | 9.47%   |
| 5.11.0  | 85        | 4.17%   |
| 5.13.0  | 82        | 4.02%   |
| 5.8.0   | 73        | 3.58%   |
| 5.3.0   | 72        | 3.53%   |
| 5.19.0  | 71        | 3.48%   |
| 4.15.0  | 67        | 3.29%   |
| 6.2.0   | 62        | 3.04%   |
| 6.5.0   | 61        | 2.99%   |
| 5.0.0   | 54        | 2.65%   |
| 5.10.0  | 53        | 2.6%    |
| 5.16.7  | 48        | 2.36%   |
| 4.18.0  | 48        | 2.36%   |
| 5.10.14 | 43        | 2.11%   |
| 6.1.0   | 34        | 1.67%   |
| 4.19.0  | 28        | 1.37%   |
| 6.2.6   | 27        | 1.32%   |
| 6.4.11  | 22        | 1.08%   |
| 6.1.1   | 18        | 0.88%   |
| 6.8.7   | 12        | 0.59%   |
| 6.4.6   | 9         | 0.44%   |
| 6.2.15  | 9         | 0.44%   |
| 6.1.52  | 9         | 0.44%   |
| 6.6.2   | 8         | 0.39%   |
| 6.5.6   | 8         | 0.39%   |
| 6.0.12  | 8         | 0.39%   |
| 5.17.5  | 8         | 0.39%   |
| 5.14.0  | 7         | 0.34%   |
| 6.6.9   | 6         | 0.29%   |
| 6.2.9   | 6         | 0.29%   |
| 6.2.14  | 6         | 0.29%   |
| 6.8.0   | 5         | 0.25%   |
| 6.7.4   | 5         | 0.25%   |
| 6.6.15  | 5         | 0.25%   |
| 6.6.10  | 5         | 0.25%   |
| 6.4.12  | 5         | 0.25%   |
| 6.0.0   | 5         | 0.25%   |
| 5.9.1   | 5         | 0.25%   |
| 5.15.8  | 5         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 256       | 12.76%  |
| 5.15    | 244       | 12.16%  |
| 5.10    | 126       | 6.28%   |
| 6.2     | 120       | 5.98%   |
| 5.19    | 97        | 4.84%   |
| 6.5     | 95        | 4.74%   |
| 5.13    | 94        | 4.69%   |
| 5.11    | 94        | 4.69%   |
| 6.1     | 85        | 4.24%   |
| 5.3     | 83        | 4.14%   |
| 5.8     | 80        | 3.99%   |
| 5.16    | 70        | 3.49%   |
| 4.15    | 67        | 3.34%   |
| 6.4     | 56        | 2.79%   |
| 5.0     | 54        | 2.69%   |
| 4.18    | 49        | 2.44%   |
| 6.6     | 46        | 2.29%   |
| 6.0     | 30        | 1.5%    |
| 4.19    | 30        | 1.5%    |
| 6.8     | 29        | 1.45%   |
| 5.17    | 27        | 1.35%   |
| 6.3     | 26        | 1.3%    |
| 5.18    | 23        | 1.15%   |
| 5.14    | 22        | 1.1%    |
| 6.7     | 19        | 0.95%   |
| 5.9     | 16        | 0.8%    |
| 5.6     | 12        | 0.6%    |
| 4.9     | 12        | 0.6%    |
| 5.12    | 11        | 0.55%   |
| 5.7     | 10        | 0.5%    |
| 5.5     | 7         | 0.35%   |
| 4.4     | 4         | 0.2%    |
| 4.13    | 3         | 0.15%   |
| 5.2     | 2         | 0.1%    |
| 4.12    | 2         | 0.1%    |
| 3.10    | 2         | 0.1%    |
| 5.1     | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 3.2     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1758      | 97.13%  |
| i686    | 51        | 2.82%   |
| aarch64 | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 873       | 46.17%  |
| KDE5              | 364       | 19.25%  |
| Unknown           | 146       | 7.72%   |
| XFCE              | 137       | 7.24%   |
| X-Cinnamon        | 121       | 6.4%    |
| KDE               | 56        | 2.96%   |
| MATE              | 48        | 2.54%   |
| Pantheon          | 30        | 1.59%   |
| LXQt              | 19        | 1%      |
| Cinnamon          | 16        | 0.85%   |
| KDE6              | 11        | 0.58%   |
| Budgie            | 10        | 0.53%   |
| Unity             | 9         | 0.48%   |
| LXDE              | 9         | 0.48%   |
| i3                | 6         | 0.32%   |
| Deepin            | 6         | 0.32%   |
| KDE4              | 5         | 0.26%   |
| openbox           | 4         | 0.21%   |
| Hyprland          | 4         | 0.21%   |
| Enlightenment     | 4         | 0.21%   |
| trinity           | 2         | 0.11%   |
| lightdm-xsession  | 2         | 0.11%   |
| GNOME Classic     | 2         | 0.11%   |
| Yaru:ubuntu:GNOME | 1         | 0.05%   |
| xmonad            | 1         | 0.05%   |
| wayland           | 1         | 0.05%   |
| qtile             | 1         | 0.05%   |
| i3-with-shmlog    | 1         | 0.05%   |
| GNOME-Classic     | 1         | 0.05%   |
| GNOME Flashback   | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1323      | 70.6%   |
| Wayland | 452       | 24.12%  |
| Unknown | 88        | 4.7%    |
| Tty     | 11        | 0.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 920       | 48.86%  |
| SDDM    | 301       | 15.99%  |
| GDM3    | 232       | 12.32%  |
| GDM     | 204       | 10.83%  |
| LightDM | 175       | 9.29%   |
| TDM     | 34        | 1.81%   |
| KDM     | 5         | 0.27%   |
| XDM     | 4         | 0.21%   |
| SLiM    | 3         | 0.16%   |
| LXDM    | 2         | 0.11%   |
| MDM     | 1         | 0.05%   |
| LY-DM   | 1         | 0.05%   |
| Ly      | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_MX      | 904       | 48.81%  |
| en_US      | 598       | 32.29%  |
| Unknown    | 134       | 7.24%   |
| es_ES      | 124       | 6.7%    |
| C          | 43        | 2.32%   |
| en_GB      | 16        | 0.86%   |
| es_US      | 6         | 0.32%   |
| fr_FR      | 4         | 0.22%   |
| en_CA      | 3         | 0.16%   |
| it_IT      | 2         | 0.11%   |
| es_MX.UTF8 | 2         | 0.11%   |
| es_AR      | 2         | 0.11%   |
| en_MX      | 2         | 0.11%   |
| C.UTF8     | 2         | 0.11%   |
| uk_UA      | 1         | 0.05%   |
| ru_RU      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| POSIX      | 1         | 0.05%   |
| es_PE      | 1         | 0.05%   |
| es_CR      | 1         | 0.05%   |
| es_419     | 1         | 0.05%   |
| en_US.UTF8 | 1         | 0.05%   |
| en_IE      | 1         | 0.05%   |
| en_DK      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 932       | 50.24%  |
| BIOS | 923       | 49.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 1325      | 71.08%  |
| Btrfs               | 230       | 12.34%  |
| Overlay             | 153       | 8.21%   |
| Tmpfs               | 72        | 3.86%   |
| Unknown             | 36        | 1.93%   |
| Xfs                 | 28        | 1.5%    |
| Zfs                 | 9         | 0.48%   |
| Ext2                | 4         | 0.21%   |
| XXXXXXX             | 2         | 0.11%   |
| Ext3                | 2         | 0.11%   |
| Reiserfs            | 1         | 0.05%   |
| Fuse.fuse-overlayfs | 1         | 0.05%   |
| Aufs                | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 984       | 52.93%  |
| GPT     | 683       | 36.74%  |
| MBR     | 192       | 10.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1649      | 89.77%  |
| Yes       | 188       | 10.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1296      | 70.24%  |
| Yes       | 549       | 29.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 414       | 22.89%  |
| Lenovo              | 338       | 18.68%  |
| Dell                | 275       | 15.2%   |
| Acer                | 134       | 7.41%   |
| ASUSTek Computer    | 133       | 7.35%   |
| Toshiba             | 91        | 5.03%   |
| HUAWEI              | 84        | 4.64%   |
| Apple               | 79        | 4.37%   |
| Sony                | 44        | 2.43%   |
| MSI                 | 25        | 1.38%   |
| Samsung Electronics | 20        | 1.11%   |
| Gateway             | 20        | 1.11%   |
| Google              | 18        | 1%      |
| Valve               | 16        | 0.88%   |
| Alienware           | 14        | 0.77%   |
| Unknown             | 14        | 0.77%   |
| Chuwi               | 9         | 0.5%    |
| Lanix               | 7         | 0.39%   |
| GPU Company         | 7         | 0.39%   |
| Timi                | 5         | 0.28%   |
| A-DATA Technology   | 5         | 0.28%   |
| Notebook            | 4         | 0.22%   |
| HONOR               | 4         | 0.22%   |
| EVOO                | 4         | 0.22%   |
| System76            | 3         | 0.17%   |
| eMachines           | 3         | 0.17%   |
| American Megatrends | 3         | 0.17%   |
| VPU Company         | 2         | 0.11%   |
| Razer               | 2         | 0.11%   |
| Panasonic           | 2         | 0.11%   |
| LG Electronics      | 2         | 0.11%   |
| Insyde              | 2         | 0.11%   |
| Gigabyte Technology | 2         | 0.11%   |
| GHIA                | 2         | 0.11%   |
| Corporativo Lanix   | 2         | 0.11%   |
| THUNDEROBOT         | 1         | 0.06%   |
| Thomson             | 1         | 0.06%   |
| TECH PAD            | 1         | 0.06%   |
| SK hynix            | 1         | 0.06%   |
| SDZ                 | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 29        | 1.6%    |
| Unknown                       | 29        | 1.6%    |
| HUAWEI HVY-WXX9               | 21        | 1.16%   |
| HP Pavilion Laptop 15-cw0xxx  | 17        | 0.94%   |
| Valve Jupiter                 | 16        | 0.88%   |
| HP Pavilion g4                | 16        | 0.88%   |
| HP Pavilion Notebook          | 15        | 0.83%   |
| Apple MacBookPro9,2           | 13        | 0.72%   |
| HP Pavilion Laptop 15-cw1xxx  | 11        | 0.61%   |
| Apple MacBookPro8,1           | 11        | 0.61%   |
| HP Laptop 15-da0xxx           | 10        | 0.55%   |
| Dell Latitude E6430           | 10        | 0.55%   |
| HP EliteBook 8460p            | 9         | 0.5%    |
| Lenovo IdeaPad 330-14AST 81D5 | 8         | 0.44%   |
| HUAWEI NBLK-WAX9X             | 8         | 0.44%   |
| HP Pavilion dv4               | 8         | 0.44%   |
| HP Laptop 15-bw0xx            | 8         | 0.44%   |
| Dell Inspiron 5559            | 8         | 0.44%   |
| Apple MacBookPro12,1          | 8         | 0.44%   |
| HUAWEI NBLB-WAX9N             | 7         | 0.39%   |
| HP Laptop 15-db0xxx           | 7         | 0.39%   |
| Lenovo IdeaPad 3 14ALC6 82KT  | 6         | 0.33%   |
| Lenovo G50-30 80G0            | 6         | 0.33%   |
| Lenovo G40-45 80E1            | 6         | 0.33%   |
| HUAWEI BOHK-WAX9X             | 6         | 0.33%   |
| HP Pavilion dv5               | 6         | 0.33%   |
| HP Pavilion 14                | 6         | 0.33%   |
| HP Laptop 15-bs0xx            | 6         | 0.33%   |
| HP Laptop 14-cm0xxx           | 6         | 0.33%   |
| HP G42                        | 6         | 0.33%   |
| GPU Company GWNR71517         | 6         | 0.33%   |
| Dell Inspiron 5570            | 6         | 0.33%   |
| Dell Inspiron 3421            | 6         | 0.33%   |
| Acer Aspire E5-573            | 6         | 0.33%   |
| Lenovo Y720-15IKB 80VR        | 5         | 0.28%   |
| Lenovo Y50-70 20378           | 5         | 0.28%   |
| Lenovo IdeaPad 330-15AST 81D6 | 5         | 0.28%   |
| Lenovo IdeaPad 330-14IGM 81D0 | 5         | 0.28%   |
| HUAWEI NBM-WXX9               | 5         | 0.28%   |
| HUAWEI BOM-WXX9               | 5         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 129       | 7.13%   |
| Lenovo ThinkPad    | 128       | 7.08%   |
| HP Pavilion        | 126       | 6.97%   |
| Dell Latitude      | 105       | 5.8%    |
| Dell Inspiron      | 103       | 5.69%   |
| Acer Aspire        | 98        | 5.42%   |
| Toshiba Satellite  | 82        | 4.53%   |
| HP Laptop          | 76        | 4.2%    |
| HP ProBook         | 30        | 1.66%   |
| ASUS VivoBook      | 30        | 1.66%   |
| HP Notebook        | 29        | 1.6%    |
| HP EliteBook       | 29        | 1.6%    |
| Unknown            | 29        | 1.6%    |
| HUAWEI HVY-WXX9    | 21        | 1.16%   |
| Valve Jupiter      | 16        | 0.88%   |
| HP Compaq          | 15        | 0.83%   |
| Apple MacBookPro9  | 15        | 0.83%   |
| HP ENVY            | 14        | 0.77%   |
| HP 240             | 14        | 0.77%   |
| Lenovo Legion      | 12        | 0.66%   |
| Dell XPS           | 12        | 0.66%   |
| Dell Vostro        | 12        | 0.66%   |
| Dell Precision     | 12        | 0.66%   |
| Apple MacBookPro8  | 12        | 0.66%   |
| ASUS ASUS          | 11        | 0.61%   |
| HP ZBook           | 10        | 0.55%   |
| HP OMEN            | 9         | 0.5%    |
| Dell Studio        | 9         | 0.5%    |
| Acer Nitro         | 9         | 0.5%    |
| HUAWEI NBLK-WAX9X  | 8         | 0.44%   |
| Apple MacBookPro12 | 8         | 0.44%   |
| MSI GF63           | 7         | 0.39%   |
| HUAWEI NBLB-WAX9N  | 7         | 0.39%   |
| ASUS Zenbook       | 7         | 0.39%   |
| ASUS ROG           | 7         | 0.39%   |
| Lenovo G50-30      | 6         | 0.33%   |
| Lenovo G40-45      | 6         | 0.33%   |
| HUAWEI BOHK-WAX9X  | 6         | 0.33%   |
| HP Stream          | 6         | 0.33%   |
| HP G42             | 6         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 162       | 8.96%   |
| 2020    | 150       | 8.29%   |
| 2011    | 147       | 8.13%   |
| 2019    | 143       | 7.9%    |
| 2012    | 136       | 7.52%   |
| 2021    | 134       | 7.41%   |
| 2013    | 121       | 6.69%   |
| 2017    | 120       | 6.63%   |
| 2014    | 117       | 6.47%   |
| 2015    | 116       | 6.41%   |
| 2010    | 99        | 5.47%   |
| 2016    | 92        | 5.09%   |
| 2008    | 85        | 4.7%    |
| 2022    | 58        | 3.21%   |
| 2009    | 41        | 2.27%   |
| 2023    | 32        | 1.77%   |
| 2007    | 32        | 1.77%   |
| 2006    | 9         | 0.5%    |
| Unknown | 6         | 0.33%   |
| 2005    | 4         | 0.22%   |
| 2024    | 3         | 0.17%   |
| 2004    | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1809      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1620      | 88.48%  |
| Enabled  | 211       | 11.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1789      | 98.89%  |
| Yes  | 20        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 549       | 29.97%  |
| 3.01-4.0    | 412       | 22.49%  |
| 8.01-16.0   | 357       | 19.49%  |
| 16.01-24.0  | 240       | 13.1%   |
| 1.01-2.0    | 104       | 5.68%   |
| 32.01-64.0  | 65        | 3.55%   |
| 2.01-3.0    | 40        | 2.18%   |
| 24.01-32.0  | 27        | 1.47%   |
| 64.01-256.0 | 20        | 1.09%   |
| 0.51-1.0    | 18        | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 694       | 34.65%  |
| 2.01-3.0   | 571       | 28.51%  |
| 3.01-4.0   | 276       | 13.78%  |
| 4.01-8.0   | 254       | 12.68%  |
| 0.51-1.0   | 120       | 5.99%   |
| 8.01-16.0  | 65        | 3.25%   |
| 0.01-0.5   | 15        | 0.75%   |
| 16.01-24.0 | 6         | 0.3%    |
| 32.01-64.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1376      | 74.54%  |
| 2      | 410       | 22.21%  |
| 3      | 32        | 1.73%   |
| 0      | 20        | 1.08%   |
| 4      | 6         | 0.33%   |
| 6      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1207      | 66.43%  |
| Yes       | 610       | 33.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1431      | 79.02%  |
| No        | 380       | 20.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1781      | 98.4%   |
| No        | 29        | 1.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1380      | 75.37%  |
| No        | 451       | 24.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Mexico  | 1809      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 383       | 20.04%  |
| Guadalajara           | 87        | 4.55%   |
| Puebla City           | 61        | 3.19%   |
| Monterrey             | 60        | 3.14%   |
| Zapopan               | 56        | 2.93%   |
| Tijuana               | 54        | 2.83%   |
| Queretaro             | 34        | 1.78%   |
| Mérida               | 34        | 1.78%   |
| Toluca                | 29        | 1.52%   |
| Xalapa                | 24        | 1.26%   |
| Cancún               | 24        | 1.26%   |
| Veracruz              | 23        | 1.2%    |
| Ecatepec              | 23        | 1.2%    |
| León                 | 22        | 1.15%   |
| Naucalpan             | 21        | 1.1%    |
| Morelia               | 21        | 1.1%    |
| Cuernavaca            | 21        | 1.1%    |
| Ciudad Juárez        | 21        | 1.1%    |
| Tlalnepantla          | 20        | 1.05%   |
| Mexicali              | 20        | 1.05%   |
| Ciudad Lopez Mateos   | 20        | 1.05%   |
| Hermosillo            | 18        | 0.94%   |
| Culiacán             | 18        | 0.94%   |
| Chihuahua City        | 18        | 0.94%   |
| Apodaca               | 18        | 0.94%   |
| Iztapalapa            | 16        | 0.84%   |
| Ciudad Nezahualcoyotl | 16        | 0.84%   |
| Saltillo              | 15        | 0.78%   |
| Gustavo Adolfo Madero | 15        | 0.78%   |
| Guadalupe             | 15        | 0.78%   |
| Villahermosa          | 14        | 0.73%   |
| San Luis Potosí City | 14        | 0.73%   |
| Querétaro City       | 14        | 0.73%   |
| Oaxaca City           | 14        | 0.73%   |
| Chalco                | 14        | 0.73%   |
| Celaya                | 14        | 0.73%   |
| Aguascalientes        | 13        | 0.68%   |
| Pachuca               | 12        | 0.63%   |
| Ensenada              | 12        | 0.63%   |
| Durango               | 12        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 299       | 371    | 13.43%  |
| WDC                         | 267       | 338    | 11.99%  |
| Toshiba                     | 221       | 268    | 9.92%   |
| Kingston                    | 211       | 258    | 9.47%   |
| Samsung Electronics         | 178       | 232    | 7.99%   |
| A-DATA Technology           | 140       | 165    | 6.29%   |
| Unknown                     | 126       | 156    | 5.66%   |
| SanDisk                     | 99        | 124    | 4.45%   |
| Hitachi                     | 90        | 102    | 4.04%   |
| HGST                        | 75        | 80     | 3.37%   |
| SK hynix                    | 52        | 62     | 2.33%   |
| Intel                       | 44        | 64     | 1.98%   |
| Apple                       | 37        | 49     | 1.66%   |
| Micron Technology           | 32        | 40     | 1.44%   |
| Crucial                     | 26        | 30     | 1.17%   |
| KIOXIA                      | 19        | 24     | 0.85%   |
| Silicon Motion              | 18        | 20     | 0.81%   |
| Kingston Technology Company | 17        | 17     | 0.76%   |
| XPG                         | 15        | 23     | 0.67%   |
| Fujitsu                     | 15        | 16     | 0.67%   |
| LITEON                      | 14        | 19     | 0.63%   |
| Phison                      | 13        | 14     | 0.58%   |
| Unknown                     | 13        | 13     | 0.58%   |
| China                       | 12        | 12     | 0.54%   |
| ADATA Technology            | 12        | 14     | 0.54%   |
| Realtek Semiconductor       | 11        | 12     | 0.49%   |
| Phison Electronics          | 11        | 14     | 0.49%   |
| PNY                         | 9         | 11     | 0.4%    |
| YMTC                        | 8         | 10     | 0.36%   |
| UMIS                        | 6         | 8      | 0.27%   |
| Netac                       | 6         | 6      | 0.27%   |
| Hewlett-Packard             | 6         | 7      | 0.27%   |
| Wibtek                      | 5         | 5      | 0.22%   |
| Micron/Crucial Technology   | 5         | 6      | 0.22%   |
| JMicron Technology          | 5         | 5      | 0.22%   |
| AS201                       | 5         | 5      | 0.22%   |
| Union Memory (Shenzhen)     | 4         | 4      | 0.18%   |
| Team                        | 4         | 4      | 0.18%   |
| Patriot                     | 4         | 7      | 0.18%   |
| O2 Micro                    | 4         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 68        | 2.95%   |
| Kingston SA400S37240G 240GB SSD                   | 50        | 2.17%   |
| Kingston SA400S37480G 480GB SSD                   | 44        | 1.91%   |
| Toshiba MQ01ABD100 1TB                            | 41        | 1.78%   |
| Toshiba MQ04ABF100 1TB                            | 38        | 1.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 38        | 1.65%   |
| Seagate ST500LT012-1DG142 500GB                   | 28        | 1.22%   |
| Toshiba MQ01ABF050 500GB                          | 27        | 1.17%   |
| A-DATA SU630 240GB SSD                            | 26        | 1.13%   |
| Unknown MMC Card  32GB                            | 25        | 1.09%   |
| Kingston SA400S37960G 960GB SSD                   | 21        | 0.91%   |
| A-DATA SU650 120GB SSD                            | 21        | 0.91%   |
| Unknown MMC Card  64GB                            | 19        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 19        | 0.83%   |
| A-DATA SU630 480GB SSD                            | 15        | 0.65%   |
| Seagate ST9500325AS 500GB                         | 14        | 0.61%   |
| HGST HTS725050A7E630 500GB                        | 14        | 0.61%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 13        | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB                   | 13        | 0.56%   |
| HGST HTS721010A9E630 1TB                          | 13        | 0.56%   |
| HGST HTS541010A9E680 1TB                          | 13        | 0.56%   |
| Unknown                                           | 13        | 0.56%   |
| Unknown MMC Card  128GB                           | 12        | 0.52%   |
| Silicon Motion PCIe-8 SSD 512GB                   | 12        | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                | 12        | 0.52%   |
| Unknown MMC Card  16GB                            | 11        | 0.48%   |
| Samsung NVMe SSD Drive 512GB                      | 11        | 0.48%   |
| A-DATA SU650 240GB SSD                            | 11        | 0.48%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 10        | 0.43%   |
| WDC WD10SPZX-08Z10 1TB                            | 10        | 0.43%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 10        | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 10        | 0.43%   |
| Seagate ST2000LM007-1R8174 2TB                    | 10        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                   | 10        | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 9         | 0.39%   |
| Seagate Expansion 2TB                             | 9         | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                      | 9         | 0.39%   |
| Kingston Company SNV2S1000G 1TB                   | 9         | 0.39%   |
| HGST HTS545050A7E680 500GB                        | 9         | 0.39%   |
| HGST HTS541075A9E680 752GB                        | 9         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 366    | 32.1%   |
| WDC                 | 217       | 268    | 23.54%  |
| Toshiba             | 193       | 234    | 20.93%  |
| Hitachi             | 90        | 102    | 9.76%   |
| HGST                | 75        | 80     | 8.13%   |
| Samsung Electronics | 15        | 17     | 1.63%   |
| Fujitsu             | 15        | 16     | 1.63%   |
| Unknown             | 7         | 7      | 0.76%   |
| Apple               | 5         | 6      | 0.54%   |
| JMicron Technology  | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 2      | 0.22%   |
| SAGE                | 1         | 1      | 0.11%   |
| SABRENT             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 2      | 0.11%   |
| IBM/Hitachi         | 1         | 1      | 0.11%   |
| ASMedia             | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 185       | 224    | 29.7%   |
| A-DATA Technology   | 132       | 157    | 21.19%  |
| Samsung Electronics | 52        | 58     | 8.35%   |
| SanDisk             | 33        | 39     | 5.3%    |
| WDC                 | 28        | 39     | 4.49%   |
| Apple               | 24        | 27     | 3.85%   |
| Crucial             | 22        | 23     | 3.53%   |
| SK hynix            | 12        | 13     | 1.93%   |
| China               | 12        | 12     | 1.93%   |
| Micron Technology   | 11        | 12     | 1.77%   |
| LITEON              | 11        | 16     | 1.77%   |
| PNY                 | 9         | 11     | 1.44%   |
| Intel               | 7         | 9      | 1.12%   |
| Netac               | 6         | 6      | 0.96%   |
| Wibtek              | 5         | 5      | 0.8%    |
| Toshiba             | 5         | 6      | 0.8%    |
| AS201               | 5         | 5      | 0.8%    |
| Team                | 4         | 4      | 0.64%   |
| LITEONIT            | 4         | 4      | 0.64%   |
| Hewlett-Packard     | 4         | 5      | 0.64%   |
| Blackpcs            | 4         | 4      | 0.64%   |
| BHT                 | 4         | 4      | 0.64%   |
| Unknown             | 4         | 4      | 0.64%   |
| Pioneer             | 3         | 5      | 0.48%   |
| Patriot             | 3         | 6      | 0.48%   |
| Gigabyte Technology | 3         | 3      | 0.48%   |
| Unknown             | 2         | 2      | 0.32%   |
| tecmiyo             | 2         | 4      | 0.32%   |
| OCZ                 | 2         | 4      | 0.32%   |
| Dogfish             | 2         | 5      | 0.32%   |
| Acer                | 2         | 2      | 0.32%   |
| ZTC                 | 1         | 1      | 0.16%   |
| Zheino              | 1         | 1      | 0.16%   |
| Yeyian              | 1         | 4      | 0.16%   |
| Transcend           | 1         | 1      | 0.16%   |
| Timetec             | 1         | 1      | 0.16%   |
| StoreJet            | 1         | 1      | 0.16%   |
| SSSTC               | 1         | 1      | 0.16%   |
| SPCC                | 1         | 1      | 0.16%   |
| sobetter            | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 900       | 1106   | 42.1%   |
| SSD     | 586       | 750    | 27.41%  |
| NVMe    | 502       | 693    | 23.48%  |
| MMC     | 125       | 157    | 5.85%   |
| Unknown | 25        | 30     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1347      | 1803   | 65.84%  |
| NVMe | 501       | 691    | 24.49%  |
| MMC  | 125       | 157    | 6.11%   |
| SAS  | 73        | 85     | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 939       | 1181   | 63.4%   |
| 0.51-1.0   | 488       | 595    | 32.95%  |
| 1.01-2.0   | 46        | 70     | 3.11%   |
| 3.01-4.0   | 5         | 6      | 0.34%   |
| 4.01-10.0  | 2         | 3      | 0.14%   |
| 10.01-20.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 503       | 26.47%  |
| 251-500        | 489       | 25.74%  |
| 501-1000       | 314       | 16.53%  |
| 51-100         | 157       | 8.26%   |
| 1-20           | 155       | 8.16%   |
| 1001-2000      | 119       | 6.26%   |
| 21-50          | 82        | 4.32%   |
| More than 3000 | 34        | 1.79%   |
| 2001-3000      | 25        | 1.32%   |
| Unknown        | 22        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 839       | 42.48%  |
| 21-50          | 397       | 20.1%   |
| 101-250        | 248       | 12.56%  |
| 51-100         | 219       | 11.09%  |
| 251-500        | 136       | 6.89%   |
| 501-1000       | 74        | 3.75%   |
| 1001-2000      | 29        | 1.47%   |
| Unknown        | 22        | 1.11%   |
| More than 3000 | 7         | 0.35%   |
| 2001-3000      | 3         | 0.15%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                  | 6         | 7      | 3.75%   |
| Seagate ST500LT012-1DG142 500GB         | 6         | 7      | 3.75%   |
| Seagate ST500LM021-1KJ152 500GB         | 5         | 5      | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 6      | 3.13%   |
| HGST HTS541010A9E680 1TB                | 5         | 5      | 3.13%   |
| Toshiba MQ01ABF050 500GB                | 4         | 4      | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB          | 4         | 4      | 2.5%    |
| Hitachi HTS545050B9A300 500GB           | 4         | 4      | 2.5%    |
| HGST HTS541075A9E680 752GB              | 4         | 4      | 2.5%    |
| WDC WD5000LPCX-60VHAT0 500GB            | 3         | 3      | 1.88%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 3      | 1.88%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.88%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2      | 1.25%   |
| WDC WD2500BEVS-60UST0 250GB             | 2         | 2      | 1.25%   |
| WDC WD10JPVX-60JC3T0 1TB                | 2         | 2      | 1.25%   |
| Seagate ST9500420AS 500GB               | 2         | 2      | 1.25%   |
| Seagate ST9320325AS 320GB               | 2         | 4      | 1.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 3      | 1.25%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 2         | 2      | 1.25%   |
| LITEON CV8-8E128-HP 128GB SSD           | 2         | 2      | 1.25%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 1.25%   |
| Hitachi HTS727575A9E364 752GB           | 2         | 3      | 1.25%   |
| Hitachi HTS545016B9A300 160GB           | 2         | 2      | 1.25%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 2      | 1.25%   |
| HGST HTS541010A7E630 1TB                | 2         | 2      | 1.25%   |
| China SSD 256GB                         | 2         | 2      | 1.25%   |
| A-DATA Technology SU650 240GB SSD       | 2         | 2      | 1.25%   |
| WDC WD5000BPVT-22HXZT1 500GB            | 1         | 2      | 0.63%   |
| WDC WD50 00BEVT-11ZAT0 500GB            | 1         | 1      | 0.63%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1      | 0.63%   |
| WDC WD3200BEVT-22A23T0 320GB            | 1         | 1      | 0.63%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 1      | 0.63%   |
| WDC WD2500BEVT-80A23T0 250GB            | 1         | 2      | 0.63%   |
| WDC WD1600BEVT-60ZCT0 160GB             | 1         | 1      | 0.63%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1         | 1      | 0.63%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 1      | 0.63%   |
| WDC WD10SPCX-60KHST0 1TB                | 1         | 1      | 0.63%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 1      | 0.63%   |
| WDC WD10JPVX-55JC3T3 1TB                | 1         | 1      | 0.63%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 1      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 41     | 22.01%  |
| Toshiba             | 31        | 39     | 19.5%   |
| Hitachi             | 24        | 25     | 15.09%  |
| WDC                 | 22        | 24     | 13.84%  |
| HGST                | 14        | 15     | 8.81%   |
| Kingston            | 10        | 10     | 6.29%   |
| SanDisk             | 4         | 4      | 2.52%   |
| LITEON              | 4         | 4      | 2.52%   |
| Fujitsu             | 4         | 4      | 2.52%   |
| Samsung Electronics | 3         | 3      | 1.89%   |
| Crucial             | 2         | 2      | 1.26%   |
| China               | 2         | 2      | 1.26%   |
| A-DATA Technology   | 2         | 2      | 1.26%   |
| Micron Technology   | 1         | 1      | 0.63%   |
| Intel               | 1         | 1      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 41     | 26.52%  |
| Toshiba             | 31        | 39     | 23.48%  |
| Hitachi             | 24        | 25     | 18.18%  |
| WDC                 | 22        | 24     | 16.67%  |
| HGST                | 14        | 15     | 10.61%  |
| Fujitsu             | 4         | 4      | 3.03%   |
| Samsung Electronics | 2         | 2      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 131       | 150    | 82.91%  |
| SSD  | 21        | 21     | 13.29%  |
| NVMe | 6         | 6      | 3.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB  | 1         | 1      | 33.33%  |
| Toshiba MK1234GSX 118GB       | 1         | 1      | 33.33%  |
| Hitachi HTS545016B9A300 160GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1152      | 1735   | 60.6%   |
| Works    | 591       | 821    | 31.09%  |
| Malfunc  | 155       | 177    | 8.15%   |
| Failed   | 3         | 3      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1166      | 56.74%  |
| AMD                                     | 349       | 16.98%  |
| Samsung Electronics                     | 125       | 6.08%   |
| SanDisk                                 | 87        | 4.23%   |
| Kingston Technology Company             | 45        | 2.19%   |
| SK hynix                                | 40        | 1.95%   |
| ADATA Technology                        | 26        | 1.27%   |
| Phison Electronics                      | 25        | 1.22%   |
| Toshiba America Info Systems            | 24        | 1.17%   |
| Nvidia                                  | 21        | 1.02%   |
| Micron Technology                       | 21        | 1.02%   |
| KIOXIA                                  | 19        | 0.92%   |
| Silicon Motion                          | 18        | 0.88%   |
| Realtek Semiconductor                   | 16        | 0.78%   |
| Union Memory (Shenzhen)                 | 14        | 0.68%   |
| Yangtze Memory Technologies             | 10        | 0.49%   |
| Micron/Crucial Technology               | 9         | 0.44%   |
| Marvell Technology Group                | 7         | 0.34%   |
| Apple                                   | 7         | 0.34%   |
| O2 Micro                                | 4         | 0.19%   |
| Lite-On Technology                      | 4         | 0.19%   |
| Solid State Storage Technology          | 3         | 0.15%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.15%   |
| Shenzhen Longsys Electronics            | 2         | 0.1%    |
| Lenovo                                  | 2         | 0.1%    |
| VIA Technologies                        | 1         | 0.05%   |
| Solidigm                                | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.05%   |
| Shenzhen Unionmemory Information System | 1         | 0.05%   |
| Seagate Technology                      | 1         | 0.05%   |
| INNOGRIT                                | 1         | 0.05%   |
| Biwin Storage Technology                | 1         | 0.05%   |
| Unknown                                 | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 285       | 12.98%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 128       | 5.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 127       | 5.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 106       | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 99        | 4.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 55        | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 53        | 2.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 50        | 2.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 44        | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 42        | 1.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 42        | 1.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 42        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 42        | 1.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 41        | 1.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 40        | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 38        | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                              | 35        | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 35        | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 32        | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 28        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 28        | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 23        | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 22        | 1%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 21        | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 21        | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 19        | 0.87%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 18        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 17        | 0.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 16        | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 16        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 0.73%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 15        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 14        | 0.64%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 0.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 14        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 14        | 0.64%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 14        | 0.64%   |
| Silicon Motion Non-Volatile memory controller                                    | 13        | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 12        | 0.55%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 12        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1324      | 62.31%  |
| NVMe | 502       | 23.62%  |
| RAID | 172       | 8.09%   |
| IDE  | 127       | 5.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1331      | 73.58%  |
| AMD     | 477       | 26.37%  |
| Unknown | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics        | 27        | 1.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 27        | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 1.44%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 23        | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 22        | 1.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 1.22%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 22        | 1.22%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 21        | 1.16%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 20        | 1.1%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 20        | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 1.05%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 19        | 1.05%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.88%   |
| AMD Custom APU 0405                           | 16        | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 15        | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 14        | 0.77%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 14        | 0.77%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 14        | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 13        | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 13        | 0.72%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 0.66%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 12        | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 11        | 0.61%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.61%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 11        | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 11        | 0.61%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 11        | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 10        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 354       | 19.57%  |
| Intel Core i7                  | 323       | 17.86%  |
| Intel Celeron                  | 193       | 10.67%  |
| Intel Core i3                  | 156       | 8.62%   |
| Other                          | 139       | 7.68%   |
| AMD Ryzen 5                    | 107       | 5.91%   |
| Intel Core 2 Duo               | 70        | 3.87%   |
| AMD Ryzen 7                    | 62        | 3.43%   |
| Intel Atom                     | 45        | 2.49%   |
| AMD A6                         | 34        | 1.88%   |
| AMD Ryzen 3                    | 32        | 1.77%   |
| Intel Pentium                  | 31        | 1.71%   |
| AMD A8                         | 30        | 1.66%   |
| AMD A4                         | 24        | 1.33%   |
| AMD E                          | 23        | 1.27%   |
| AMD A10                        | 23        | 1.27%   |
| Intel Pentium Dual             | 17        | 0.94%   |
| Intel Pentium Dual-Core        | 11        | 0.61%   |
| AMD Turion 64 X2 Mobile        | 10        | 0.55%   |
| AMD Athlon II                  | 10        | 0.55%   |
| Intel Genuine                  | 9         | 0.5%    |
| AMD Ryzen 9                    | 9         | 0.5%    |
| AMD E1                         | 8         | 0.44%   |
| AMD Athlon                     | 8         | 0.44%   |
| Intel Core 2                   | 7         | 0.39%   |
| AMD Ryzen 5 PRO                | 7         | 0.39%   |
| AMD FX                         | 6         | 0.33%   |
| Intel Pentium Silver           | 5         | 0.28%   |
| Intel Celeron M                | 5         | 0.28%   |
| AMD Athlon 64 X2               | 5         | 0.28%   |
| AMD A12                        | 5         | 0.28%   |
| AMD E2                         | 4         | 0.22%   |
| AMD Sempron                    | 3         | 0.17%   |
| Intel Xeon                     | 2         | 0.11%   |
| Intel Pentium M                | 2         | 0.11%   |
| Intel Core Duo                 | 2         | 0.11%   |
| AMD V120                       | 2         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.11%   |
| AMD PRO A10                    | 2         | 0.11%   |
| AMD Phenom II                  | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1018      | 56.27%  |
| 4      | 507       | 28.03%  |
| 6      | 129       | 7.13%   |
| 1      | 72        | 3.98%   |
| 8      | 53        | 2.93%   |
| 10     | 11        | 0.61%   |
| 14     | 8         | 0.44%   |
| 12     | 6         | 0.33%   |
| 24     | 2         | 0.11%   |
| 3      | 2         | 0.11%   |
| 16     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1809      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1207      | 66.69%  |
| 1      | 602       | 33.26%  |
| 4      | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1770      | 97.84%  |
| 32-bit         | 19        | 1.05%   |
| Unknown        | 14        | 0.77%   |
| 64-bit         | 6         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 626       | 33.21%  |
| 0x206a7    | 96        | 5.09%   |
| 0x306a9    | 76        | 4.03%   |
| 0x40651    | 55        | 2.92%   |
| 0x806ec    | 43        | 2.28%   |
| 0x30678    | 40        | 2.12%   |
| 0x306d4    | 39        | 2.07%   |
| 0x08108109 | 39        | 2.07%   |
| 0x806e9    | 38        | 2.02%   |
| 0x06006705 | 36        | 1.91%   |
| 0x1067a    | 35        | 1.86%   |
| 0x406e3    | 34        | 1.8%    |
| 0x806ea    | 33        | 1.75%   |
| 0x806c1    | 32        | 1.7%    |
| 0x906ea    | 31        | 1.64%   |
| 0x20655    | 29        | 1.54%   |
| 0x08600106 | 27        | 1.43%   |
| 0x6fd      | 24        | 1.27%   |
| 0x406c4    | 24        | 1.27%   |
| 0x08608103 | 24        | 1.27%   |
| 0x406c3    | 23        | 1.22%   |
| 0x306c3    | 23        | 1.22%   |
| 0x106ca    | 22        | 1.17%   |
| 0x506e3    | 21        | 1.11%   |
| 0x0810100b | 21        | 1.11%   |
| 0x10676    | 19        | 1.01%   |
| 0x08108102 | 19        | 1.01%   |
| 0x20652    | 17        | 0.9%    |
| 0x07030105 | 17        | 0.9%    |
| 0xa0652    | 16        | 0.85%   |
| 0x706e5    | 16        | 0.85%   |
| 0x06001119 | 16        | 0.85%   |
| 0x05000119 | 16        | 0.85%   |
| 0x906e9    | 15        | 0.8%    |
| 0x706a1    | 15        | 0.8%    |
| 0x506c9    | 15        | 0.8%    |
| 0x010000c8 | 13        | 0.69%   |
| 0x706a8    | 11        | 0.58%   |
| 0x06006704 | 11        | 0.58%   |
| 0x106c2    | 9         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 250       | 13.82%  |
| SandyBridge      | 141       | 7.79%   |
| Haswell          | 113       | 6.25%   |
| IvyBridge        | 112       | 6.19%   |
| Silvermont       | 106       | 5.86%   |
| Unknown          | 88        | 4.86%   |
| Skylake          | 85        | 4.7%    |
| Zen+             | 75        | 4.15%   |
| Excavator        | 75        | 4.15%   |
| Penryn           | 70        | 3.87%   |
| Broadwell        | 64        | 3.54%   |
| Westmere         | 63        | 3.48%   |
| TigerLake        | 54        | 2.99%   |
| Core             | 52        | 2.87%   |
| Goldmont plus    | 50        | 2.76%   |
| Zen 2            | 48        | 2.65%   |
| Zen              | 33        | 1.82%   |
| Bonnell          | 33        | 1.82%   |
| CometLake        | 32        | 1.77%   |
| Bobcat           | 32        | 1.77%   |
| Puma             | 30        | 1.66%   |
| Piledriver       | 27        | 1.49%   |
| IceLake          | 24        | 1.33%   |
| Goldmont         | 24        | 1.33%   |
| Alderlake Hybrid | 23        | 1.27%   |
| K10              | 20        | 1.11%   |
| K8 Hammer        | 19        | 1.05%   |
| Zen 3            | 17        | 0.94%   |
| Jaguar           | 12        | 0.66%   |
| P6               | 11        | 0.61%   |
| K8 & K10 hybrid  | 9         | 0.5%    |
| K10 Llano        | 6         | 0.33%   |
| Tremont          | 4         | 0.22%   |
| Steamroller      | 3         | 0.17%   |
| Nehalem          | 2         | 0.11%   |
| Gracemont        | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1260      | 59.6%   |
| AMD                              | 529       | 25.02%  |
| Nvidia                           | 323       | 15.28%  |
| VIA Technologies                 | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 132       | 6%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 105       | 4.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 80        | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 72        | 3.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 56        | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 55        | 2.5%    |
| Intel HD Graphics 5500                                                                   | 52        | 2.36%   |
| Intel HD Graphics 620                                                                    | 51        | 2.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 51        | 2.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 49        | 2.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 2.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 49        | 2.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 47        | 2.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 47        | 2.14%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 47        | 2.14%   |
| Intel UHD Graphics 620                                                                   | 44        | 2%      |
| AMD Lucienne                                                                             | 37        | 1.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 35        | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 34        | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 34        | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 32        | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 1.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 28        | 1.27%   |
| Intel HD Graphics 530                                                                    | 27        | 1.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 26        | 1.18%   |
| Intel HD Graphics 630                                                                    | 25        | 1.14%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 24        | 1.09%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 23        | 1.05%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 22        | 1%      |
| Intel HD Graphics 500                                                                    | 21        | 0.95%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 18        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 17        | 0.77%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 16        | 0.73%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 16        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 14        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 971       | 53.56%  |
| 1 x AMD        | 421       | 23.22%  |
| Intel + Nvidia | 225       | 12.41%  |
| 1 x Nvidia     | 67        | 3.7%    |
| Intel + AMD    | 44        | 2.43%   |
| 2 x AMD        | 33        | 1.82%   |
| AMD + Nvidia   | 31        | 1.71%   |
| 2 x Intel      | 13        | 0.72%   |
| Other          | 6         | 0.33%   |
| 1 x VIA        | 1         | 0.06%   |
| 1 x SiS        | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1630      | 89.51%  |
| Proprietary | 153       | 8.4%    |
| Unknown     | 38        | 2.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1240      | 67.1%   |
| 0.01-0.5   | 250       | 13.53%  |
| 1.01-2.0   | 141       | 7.63%   |
| 0.51-1.0   | 112       | 6.06%   |
| 3.01-4.0   | 61        | 3.3%    |
| 5.01-6.0   | 24        | 1.3%    |
| 7.01-8.0   | 15        | 0.81%   |
| 2.01-3.0   | 5         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 352       | 17.21%  |
| AU Optronics            | 352       | 17.21%  |
| Chimei Innolux          | 288       | 14.08%  |
| LG Display              | 260       | 12.71%  |
| Samsung Electronics     | 213       | 10.42%  |
| Apple                   | 80        | 3.91%   |
| Chi Mei Optoelectronics | 43        | 2.1%    |
| Hewlett-Packard         | 41        | 2%      |
| Goldstar                | 39        | 1.91%   |
| Lenovo                  | 35        | 1.71%   |
| Dell                    | 30        | 1.47%   |
| BenQ                    | 26        | 1.27%   |
| LG Philips              | 25        | 1.22%   |
| PANDA                   | 22        | 1.08%   |
| Sharp                   | 21        | 1.03%   |
| Acer                    | 19        | 0.93%   |
| Valve                   | 14        | 0.68%   |
| HannStar                | 12        | 0.59%   |
| AOC                     | 12        | 0.59%   |
| Unknown                 | 10        | 0.49%   |
| InfoVision              | 10        | 0.49%   |
| Sony                    | 7         | 0.34%   |
| SLD                     | 7         | 0.34%   |
| HKC                     | 7         | 0.34%   |
| CSO                     | 7         | 0.34%   |
| TMX                     | 5         | 0.24%   |
| JDI                     | 5         | 0.24%   |
| InnoLux Display         | 5         | 0.24%   |
| CPT                     | 5         | 0.24%   |
| ASUSTek Computer        | 5         | 0.24%   |
| Unknown (AAA)           | 4         | 0.2%    |
| MSI                     | 4         | 0.2%    |
| Insignia                | 4         | 0.2%    |
| HUAWEI                  | 4         | 0.2%    |
| Gateway                 | 4         | 0.2%    |
| FOX                     | 4         | 0.2%    |
| Ancor Communications    | 4         | 0.2%    |
| ___                     | 3         | 0.15%   |
| Westinghouse            | 3         | 0.15%   |
| Vizio                   | 3         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 22        | 1.07%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 19        | 0.92%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 17        | 0.82%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                 | 17        | 0.82%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 17        | 0.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 15        | 0.73%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 15        | 0.73%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 14        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 14        | 0.68%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 14        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 13        | 0.63%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 13        | 0.63%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 13        | 0.63%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 12        | 0.58%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 12        | 0.58%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 12        | 0.58%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 10        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 10        | 0.48%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 10        | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 9         | 0.44%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 9         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 9         | 0.44%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 9         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 9         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 8         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 8         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 8         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch      | 8         | 0.39%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 8         | 0.39%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                 | 7         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 7         | 0.34%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 7         | 0.34%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 340x190mm 15.3-inch      | 7         | 0.34%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 7         | 0.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 7         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 898       | 46.24%  |
| 1920x1080 (FHD)    | 583       | 30.02%  |
| 1280x800 (WXGA)    | 108       | 5.56%   |
| 1600x900 (HD+)     | 53        | 2.73%   |
| 1440x900 (WXGA+)   | 34        | 1.75%   |
| 3840x2160 (4K)     | 33        | 1.7%    |
| 1024x600           | 27        | 1.39%   |
| 2560x1600          | 24        | 1.24%   |
| 2160x1440          | 18        | 0.93%   |
| 2560x1440 (QHD)    | 17        | 0.88%   |
| 800x1280           | 15        | 0.77%   |
| 1920x1200 (WUXGA)  | 15        | 0.77%   |
| 2880x1800          | 13        | 0.67%   |
| 3440x1440          | 11        | 0.57%   |
| 1680x1050 (WSXGA+) | 11        | 0.57%   |
| 1280x1024 (SXGA)   | 11        | 0.57%   |
| 2560x1080          | 10        | 0.51%   |
| 1360x768           | 10        | 0.51%   |
| 1024x768 (XGA)     | 8         | 0.41%   |
| 3000x2000          | 6         | 0.31%   |
| 3840x2400          | 5         | 0.26%   |
| 3200x1800 (QHD+)   | 5         | 0.26%   |
| Unknown            | 4         | 0.21%   |
| 2520x1680          | 3         | 0.15%   |
| 2288x1287          | 2         | 0.1%    |
| 2240x1400          | 2         | 0.1%    |
| 1600x1200          | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 1152x864           | 2         | 0.1%    |
| 6000x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |
| 1920x540           | 1         | 0.05%   |
| 1600x2560          | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |
| 1366x912           | 1         | 0.05%   |
| 1200x1920          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 752       | 36.81%  |
| 13      | 406       | 19.87%  |
| 14      | 314       | 15.37%  |
| 11      | 66        | 3.23%   |
| 17      | 64        | 3.13%   |
| 21      | 48        | 2.35%   |
| 24      | 40        | 1.96%   |
| 16      | 39        | 1.91%   |
| 23      | 37        | 1.81%   |
| 12      | 33        | 1.62%   |
| 27      | 32        | 1.57%   |
| 10      | 25        | 1.22%   |
| 18      | 21        | 1.03%   |
| 34      | 19        | 0.93%   |
| Unknown | 19        | 0.93%   |
| 31      | 16        | 0.78%   |
| 20      | 16        | 0.78%   |
| 7       | 15        | 0.73%   |
| 19      | 12        | 0.59%   |
| 84      | 10        | 0.49%   |
| 22      | 7         | 0.34%   |
| 40      | 6         | 0.29%   |
| 72      | 5         | 0.24%   |
| 32      | 5         | 0.24%   |
| 54      | 4         | 0.2%    |
| 8       | 4         | 0.2%    |
| 52      | 3         | 0.15%   |
| 39      | 3         | 0.15%   |
| 29      | 3         | 0.15%   |
| 25      | 3         | 0.15%   |
| 142     | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 26      | 2         | 0.1%    |
| 86      | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 63      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1329      | 65.47%  |
| 201-300        | 262       | 12.91%  |
| 501-600        | 109       | 5.37%   |
| 401-500        | 102       | 5.02%   |
| 351-400        | 101       | 4.98%   |
| 701-800        | 25        | 1.23%   |
| 601-700        | 20        | 0.99%   |
| Unknown        | 19        | 0.94%   |
| 1501-2000      | 16        | 0.79%   |
| 1-100          | 16        | 0.79%   |
| 1001-1500      | 12        | 0.59%   |
| 801-900        | 10        | 0.49%   |
| 101-200        | 4         | 0.2%    |
| 901-1000       | 3         | 0.15%   |
| More than 2000 | 2         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1506      | 82.3%   |
| 16/10   | 214       | 11.69%  |
| 3/2     | 31        | 1.69%   |
| 21/9    | 21        | 1.15%   |
| 0.67    | 15        | 0.82%   |
| 4/3     | 14        | 0.77%   |
| Unknown | 12        | 0.66%   |
| 5/4     | 10        | 0.55%   |
| 1.00    | 2         | 0.11%   |
| 0.62    | 2         | 0.11%   |
| 0.56    | 2         | 0.11%   |
| 6/5     | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 773       | 37.87%  |
| 81-90          | 644       | 31.55%  |
| 201-250        | 108       | 5.29%   |
| 71-80          | 75        | 3.67%   |
| 51-60          | 66        | 3.23%   |
| 121-130        | 47        | 2.3%    |
| 351-500        | 43        | 2.11%   |
| 151-200        | 37        | 1.81%   |
| 301-350        | 34        | 1.67%   |
| 61-70          | 31        | 1.52%   |
| More than 1000 | 29        | 1.42%   |
| 141-150        | 28        | 1.37%   |
| 41-50          | 25        | 1.22%   |
| 1-40           | 20        | 0.98%   |
| Unknown        | 19        | 0.93%   |
| 251-300        | 16        | 0.78%   |
| 111-120        | 16        | 0.78%   |
| 501-1000       | 13        | 0.64%   |
| 131-140        | 12        | 0.59%   |
| 91-100         | 5         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 933       | 46.44%  |
| 121-160       | 595       | 29.62%  |
| 51-100        | 290       | 14.44%  |
| 161-240       | 100       | 4.98%   |
| More than 240 | 36        | 1.79%   |
| 1-50          | 36        | 1.79%   |
| Unknown       | 19        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1498      | 80.71%  |
| 2     | 291       | 15.68%  |
| 0     | 40        | 2.16%   |
| 3     | 26        | 1.4%    |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1038      | 37.49%  |
| Intel                                  | 699       | 25.24%  |
| Qualcomm Atheros                       | 423       | 15.28%  |
| Broadcom                               | 254       | 9.17%   |
| Broadcom Limited                       | 55        | 1.99%   |
| Ralink                                 | 43        | 1.55%   |
| Marvell Technology Group               | 40        | 1.44%   |
| MediaTek                               | 36        | 1.3%    |
| TP-Link                                | 29        | 1.05%   |
| Ralink Technology                      | 24        | 0.87%   |
| ASIX Electronics                       | 18        | 0.65%   |
| Nvidia                                 | 17        | 0.61%   |
| DisplayLink                            | 11        | 0.4%    |
| Huawei Technologies                    | 10        | 0.36%   |
| Qualcomm Atheros Communications        | 8         | 0.29%   |
| Xiaomi                                 | 7         | 0.25%   |
| Spreadtrum Communications              | 5         | 0.18%   |
| Samsung Electronics                    | 5         | 0.18%   |
| Motorola PCS                           | 5         | 0.18%   |
| Qualcomm                               | 4         | 0.14%   |
| OPPO Electronics                       | 4         | 0.14%   |
| ICS Advent                             | 4         | 0.14%   |
| Lenovo                                 | 3         | 0.11%   |
| JMicron Technology                     | 2         | 0.07%   |
| Google                                 | 2         | 0.07%   |
| Dell                                   | 2         | 0.07%   |
| D-Link                                 | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| VIA Technologies                       | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Shenzhen Goodix Technology             | 1         | 0.04%   |
| Qualcomm Technologies                  | 1         | 0.04%   |
| OpenMoko                               | 1         | 0.04%   |
| NIIMBOT                                | 1         | 0.04%   |
| NetGear                                | 1         | 0.04%   |
| Mercucys                               | 1         | 0.04%   |
| Linksys                                | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 495       | 14.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 302       | 8.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 102       | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 79        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 79        | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 66        | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 61        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 56        | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 55        | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 53        | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 52        | 1.52%   |
| Intel Wireless 8265 / 8275                                             | 51        | 1.49%   |
| Intel Wi-Fi 6 AX200                                                    | 49        | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                          | 48        | 1.41%   |
| Intel Wi-Fi 6 AX201                                                    | 44        | 1.29%   |
| Intel Wireless 7265                                                    | 42        | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 42        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 40        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 39        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 38        | 1.11%   |
| Intel Wireless 7260                                                    | 34        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                        | 33        | 0.97%   |
| Intel Wireless 8260                                                    | 31        | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 27        | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 27        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 26        | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 25        | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 23        | 0.67%   |
| Intel Ethernet Connection I218-LM                                      | 23        | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 22        | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 22        | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                              | 22        | 0.64%   |
| Intel Wireless 3160                                                    | 21        | 0.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 21        | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 20        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 20        | 0.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 20        | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 19        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 18        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 655       | 35.05%  |
| Realtek Semiconductor                 | 451       | 24.13%  |
| Qualcomm Atheros                      | 357       | 19.1%   |
| Broadcom                              | 221       | 11.82%  |
| Ralink                                | 43        | 2.3%    |
| Broadcom Limited                      | 42        | 2.25%   |
| MediaTek                              | 32        | 1.71%   |
| TP-Link                               | 25        | 1.34%   |
| Ralink Technology                     | 24        | 1.28%   |
| Qualcomm Atheros Communications       | 8         | 0.43%   |
| Qualcomm                              | 3         | 0.16%   |
| D-Link                                | 2         | 0.11%   |
| Qualcomm Technologies                 | 1         | 0.05%   |
| NetGear                               | 1         | 0.05%   |
| Mercucys                              | 1         | 0.05%   |
| Dell                                  | 1         | 0.05%   |
| D-Link System                         | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 102       | 5.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 79        | 4.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 79        | 4.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 66        | 3.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 61        | 3.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 55        | 2.9%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 53        | 2.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 52        | 2.74%   |
| Intel Wireless 8265 / 8275                                              | 51        | 2.69%   |
| Intel Wi-Fi 6 AX200                                                     | 49        | 2.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 48        | 2.53%   |
| Intel Wi-Fi 6 AX201                                                     | 44        | 2.32%   |
| Intel Wireless 7265                                                     | 42        | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 39        | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 38        | 2%      |
| Intel Wireless 7260                                                     | 34        | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 1.74%   |
| Intel Wireless 8260                                                     | 31        | 1.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 27        | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 26        | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 23        | 1.21%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 22        | 1.16%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 22        | 1.16%   |
| Intel Wireless 3160                                                     | 21        | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 21        | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 20        | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 20        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 19        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 18        | 0.95%   |
| Intel Wireless 3165                                                     | 18        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 17        | 0.9%    |
| Realtek 802.11ac NIC                                                    | 16        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 14        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 856       | 57.41%  |
| Intel                                  | 263       | 17.64%  |
| Qualcomm Atheros                       | 129       | 8.65%   |
| Broadcom                               | 82        | 5.5%    |
| Marvell Technology Group               | 40        | 2.68%   |
| ASIX Electronics                       | 18        | 1.21%   |
| Nvidia                                 | 17        | 1.14%   |
| Broadcom Limited                       | 13        | 0.87%   |
| DisplayLink                            | 11        | 0.74%   |
| Huawei Technologies                    | 9         | 0.6%    |
| Xiaomi                                 | 7         | 0.47%   |
| Spreadtrum Communications              | 5         | 0.34%   |
| Samsung Electronics                    | 5         | 0.34%   |
| TP-Link                                | 4         | 0.27%   |
| OPPO Electronics                       | 4         | 0.27%   |
| MediaTek                               | 4         | 0.27%   |
| ICS Advent                             | 4         | 0.27%   |
| Lenovo                                 | 3         | 0.2%    |
| Motorola PCS                           | 2         | 0.13%   |
| JMicron Technology                     | 2         | 0.13%   |
| Google                                 | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| VIA Technologies                       | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.07%   |
| Qualcomm                               | 1         | 0.07%   |
| Linksys                                | 1         | 0.07%   |
| LG Electronics                         | 1         | 0.07%   |
| Lab126                                 | 1         | 0.07%   |
| HTC (High Tech Computer)               | 1         | 0.07%   |
| Foxconn / Hon Hai                      | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 495       | 32.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 302       | 20.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 56        | 3.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 40        | 2.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 27        | 1.8%    |
| Intel Ethernet Connection I218-LM                                              | 23        | 1.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 22        | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 20        | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                          | 19        | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                                          | 15        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                                  | 15        | 1%      |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 14        | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                       | 14        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 13        | 0.87%   |
| Intel 82577LM Gigabit Network Connection                                       | 13        | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 12        | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 12        | 0.8%    |
| Intel Ethernet Connection I219-LM                                              | 12        | 0.8%    |
| Intel Ethernet Connection I217-LM                                              | 12        | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 0.8%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 10        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 8         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 0.53%   |
| Huawei VTR-L09                                                                 | 8         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.47%   |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.47%   |
| Intel Ethernet Connection I219-V                                               | 7         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                           | 7         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 7         | 0.47%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 6         | 0.4%    |
| Intel Ethernet Connection (16) I219-LM                                         | 6         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 6         | 0.4%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 6         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1781      | 55.21%  |
| Ethernet | 1429      | 44.3%   |
| Modem    | 10        | 0.31%   |
| Unknown  | 6         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1468      | 76.22%  |
| Ethernet | 457       | 23.73%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1316      | 72.75%  |
| 1     | 453       | 25.04%  |
| 0     | 34        | 1.88%   |
| 3     | 6         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1207      | 65%     |
| Yes  | 650       | 35%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 481       | 34.65%  |
| Realtek Semiconductor           | 254       | 18.3%   |
| Qualcomm Atheros Communications | 133       | 9.58%   |
| Broadcom                        | 92        | 6.63%   |
| IMC Networks                    | 71        | 5.12%   |
| Apple                           | 70        | 5.04%   |
| Lite-On Technology              | 63        | 4.54%   |
| Foxconn / Hon Hai               | 49        | 3.53%   |
| Realtek                         | 39        | 2.81%   |
| Dell                            | 31        | 2.23%   |
| Hewlett-Packard                 | 25        | 1.8%    |
| Toshiba                         | 23        | 1.66%   |
| Ralink                          | 18        | 1.3%    |
| Cambridge Silicon Radio         | 13        | 0.94%   |
| Ralink Technology               | 8         | 0.58%   |
| Foxconn International           | 4         | 0.29%   |
| Alps Electric                   | 4         | 0.29%   |
| MediaTek                        | 3         | 0.22%   |
| USI                             | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |
| ASUSTek Computer                | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                                                             | 118       | 8.49%   |
| Intel Bluetooth wireless interface                                                  | 118       | 8.49%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 96        | 6.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 96        | 6.91%   |
| Intel AX201 Bluetooth                                                               | 83        | 5.97%   |
| Intel Bluetooth Device                                                              | 73        | 5.25%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 70        | 5.04%   |
| Intel AX200 Bluetooth                                                               | 48        | 3.45%   |
| Realtek Bluetooth Radio                                                             | 39        | 2.81%   |
| Apple Bluetooth Host Controller                                                     | 35        | 2.52%   |
| IMC Networks Bluetooth Radio                                                        | 32        | 2.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 26        | 1.87%   |
| Apple Bluetooth USB Host Controller                                                 | 24        | 1.73%   |
| Lite-On Bluetooth Device                                                            | 23        | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 1.37%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 19        | 1.37%   |
| Ralink RT3290 Bluetooth                                                             | 18        | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 18        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 18        | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 18        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 17        | 1.22%   |
| IMC Networks Wireless_Device                                                        | 16        | 1.15%   |
| Realtek RTL8723B Bluetooth                                                          | 15        | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 1.01%   |
| Intel AX211 Bluetooth                                                               | 14        | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 14        | 1.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 12        | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 0.79%   |
| Realtek RTL8821A Bluetooth                                                          | 10        | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 8         | 0.58%   |
| IMC Networks Bluetooth Device                                                       | 8         | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.58%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 7         | 0.5%    |
| Dell Wireless 355 Bluetooth                                                         | 7         | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 7         | 0.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 7         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1309      | 62.04%  |
| AMD                                             | 483       | 22.89%  |
| Nvidia                                          | 211       | 10%     |
| Logitech                                        | 11        | 0.52%   |
| Texas Instruments                               | 7         | 0.33%   |
| Realtek Semiconductor                           | 7         | 0.33%   |
| GN Netcom                                       | 7         | 0.33%   |
| C-Media Electronics                             | 7         | 0.33%   |
| Lenovo                                          | 6         | 0.28%   |
| Generalplus Technology                          | 6         | 0.28%   |
| Plantronics                                     | 5         | 0.24%   |
| Kingston Technology                             | 5         | 0.24%   |
| Tenx Technology                                 | 4         | 0.19%   |
| JMTek                                           | 4         | 0.19%   |
| ASUSTek Computer                                | 4         | 0.19%   |
| Sony                                            | 3         | 0.14%   |
| DCMT Technology                                 | 3         | 0.14%   |
| Creative Technology                             | 3         | 0.14%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.09%   |
| Syntek                                          | 2         | 0.09%   |
| Synaptics                                       | 2         | 0.09%   |
| Samson Technologies                             | 2         | 0.09%   |
| Apple                                           | 2         | 0.09%   |
| Yamaha                                          | 1         | 0.05%   |
| VIA Technologies                                | 1         | 0.05%   |
| Silicon Motion                                  | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.05%   |
| Shure                                           | 1         | 0.05%   |
| Sennheiser Communications                       | 1         | 0.05%   |
| Samsung Electronics                             | 1         | 0.05%   |
| Razer USA                                       | 1         | 0.05%   |
| M-Audio                                         | 1         | 0.05%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.05%   |
| Huawei Technologies                             | 1         | 0.05%   |
| Focusrite-Novation                              | 1         | 0.05%   |
| Focusrite                                       | 1         | 0.05%   |
| DisplayLink                                     | 1         | 0.05%   |
| Cambridge Audio                                 | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 190       | 7.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 154       | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 145       | 5.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 108       | 4.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 105       | 3.96%   |
| AMD FCH Azalia Controller                                                                         | 91        | 3.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 87        | 3.28%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 74        | 2.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 73        | 2.75%   |
| Intel 8 Series HD Audio Controller                                                                | 73        | 2.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 68        | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 65        | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 64        | 2.41%   |
| Intel Broadwell-U Audio Controller                                                                | 64        | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 60        | 2.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 55        | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 54        | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 54        | 2.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 1.88%   |
| AMD High Definition Audio Controller                                                              | 49        | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 47        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 47        | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 47        | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 43        | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 40        | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 35        | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 33        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                                         | 31        | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 29        | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 27        | 1.02%   |
| AMD Trinity HDMI Audio Controller                                                                 | 27        | 1.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 25        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 24        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 0.79%   |
| Nvidia Audio device                                                                               | 21        | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 309       | 28.17%  |
| SK hynix                                         | 241       | 21.97%  |
| Micron Technology                                | 146       | 13.31%  |
| Kingston                                         | 136       | 12.4%   |
| Unknown                                          | 70        | 6.38%   |
| A-DATA Technology                                | 46        | 4.19%   |
| Ramaxel Technology                               | 32        | 2.92%   |
| Crucial                                          | 23        | 2.1%    |
| Elpida                                           | 21        | 1.91%   |
| Nanya Technology                                 | 14        | 1.28%   |
| Unknown (ABCD)                                   | 13        | 1.19%   |
| Corsair                                          | 10        | 0.91%   |
| ChangXin Memory                                  | 6         | 0.55%   |
| Team                                             | 3         | 0.27%   |
| Qimonda                                          | 3         | 0.27%   |
| PNY                                              | 3         | 0.27%   |
| Unknown                                          | 3         | 0.27%   |
| Transcend                                        | 2         | 0.18%   |
| Patriot                                          | 2         | 0.18%   |
| Unknown (0x8AF1)                                 | 1         | 0.09%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.09%   |
| Unknown (0x0C75)                                 | 1         | 0.09%   |
| Timetec                                          | 1         | 0.09%   |
| SHARETRONIC                                      | 1         | 0.09%   |
| Goldkey                                          | 1         | 0.09%   |
| G.Skill                                          | 1         | 0.09%   |
| ff                                               | 1         | 0.09%   |
| Avant                                            | 1         | 0.09%   |
| ASint Technology                                 | 1         | 0.09%   |
| A-TECH                                           | 1         | 0.09%   |
| 4ea5                                             | 1         | 0.09%   |
| 3235CB0010E4                                     | 1         | 0.09%   |
| 0161000080AD                                     | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 31        | 2.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 19        | 1.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.19%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 1.19%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 1.11%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 1.02%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 8         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 8         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 8         | 0.68%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 8         | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 7         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 6         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 6         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 6         | 0.51%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.43%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.43%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.43%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 5         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 385       | 43.16%  |
| DDR3    | 339       | 38%     |
| DDR2    | 52        | 5.83%   |
| LPDDR4  | 38        | 4.26%   |
| LPDDR3  | 26        | 2.91%   |
| SDRAM   | 18        | 2.02%   |
| LPDDR5  | 12        | 1.35%   |
| DDR5    | 9         | 1.01%   |
| DDR     | 7         | 0.78%   |
| Unknown | 5         | 0.56%   |
| RAM     | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 774       | 86.38%  |
| Row Of Chips | 112       | 12.5%   |
| Chip         | 6         | 0.67%   |
| Unknown      | 3         | 0.33%   |
| DIMM         | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 383       | 37.04%  |
| 4096  | 355       | 34.33%  |
| 2048  | 147       | 14.22%  |
| 16384 | 87        | 8.41%   |
| 1024  | 40        | 3.87%   |
| 32768 | 17        | 1.64%   |
| 512   | 3         | 0.29%   |
| 12288 | 1         | 0.1%    |
| 256   | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 259       | 26.21%  |
| 2667    | 181       | 18.32%  |
| 3200    | 141       | 14.27%  |
| 2400    | 66        | 6.68%   |
| 2133    | 51        | 5.16%   |
| 1334    | 46        | 4.66%   |
| 1333    | 40        | 4.05%   |
| 3266    | 31        | 3.14%   |
| 667     | 31        | 3.14%   |
| Unknown | 21        | 2.13%   |
| 4267    | 15        | 1.52%   |
| 800     | 13        | 1.32%   |
| 6400    | 11        | 1.11%   |
| 2048    | 11        | 1.11%   |
| 1067    | 11        | 1.11%   |
| 1867    | 8         | 0.81%   |
| 4800    | 7         | 0.71%   |
| 4199    | 7         | 0.71%   |
| 975     | 7         | 0.71%   |
| 533     | 7         | 0.71%   |
| 3733    | 6         | 0.61%   |
| 1066    | 5         | 0.51%   |
| 8400    | 4         | 0.4%    |
| 1866    | 3         | 0.3%    |
| 2933    | 2         | 0.2%    |
| 5600    | 1         | 0.1%    |
| 5500    | 1         | 0.1%    |
| 5200    | 1         | 0.1%    |
| 400     | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 3         | 18.75%  |
| Samsung Electronics    | 3         | 18.75%  |
| Brother Industries     | 3         | 18.75%  |
| Hewlett-Packard        | 2         | 12.5%   |
| Canon                  | 2         | 12.5%   |
| TSC Auto ID Technology | 1         | 6.25%   |
| Kyocera                | 1         | 6.25%   |
| BIXOLON                | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung M2020 Series    | 2         | 12.5%   |
| HP DeskJet 2300 series  | 2         | 12.5%   |
| TSC Auto ID Printer     | 1         | 6.25%   |
| Seiko Epson L555 Series | 1         | 6.25%   |
| Seiko Epson L210 Series | 1         | 6.25%   |
| Seiko Epson L120 Series | 1         | 6.25%   |
| Samsung ML-1660 Series  | 1         | 6.25%   |
| Kyocera FS-1116MFP      | 1         | 6.25%   |
| Canon iP2600 series     | 1         | 6.25%   |
| Canon G2010 series      | 1         | 6.25%   |
| Brother MFC-J470DW      | 1         | 6.25%   |
| Brother DCP-1600        | 1         | 6.25%   |
| Brother DCP-1510        | 1         | 6.25%   |
| BIXOLON SRP-350plusIII  | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| HP ScanJet 5590 | 2         | 66.67%  |
| HP Scanjet 300  | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 373       | 22.87%  |
| IMC Networks                           | 172       | 10.55%  |
| Microdia                               | 152       | 9.32%   |
| Realtek Semiconductor                  | 111       | 6.81%   |
| Sunplus Innovation Technology          | 95        | 5.82%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 5.52%   |
| Quanta                                 | 85        | 5.21%   |
| Suyin                                  | 73        | 4.48%   |
| Bison Electronics                      | 71        | 4.35%   |
| Syntek                                 | 54        | 3.31%   |
| Apple                                  | 49        | 3%      |
| Lite-On Technology                     | 44        | 2.7%    |
| Acer                                   | 34        | 2.08%   |
| Silicon Motion                         | 23        | 1.41%   |
| Ricoh                                  | 23        | 1.41%   |
| Importek                               | 20        | 1.23%   |
| Logitech                               | 19        | 1.16%   |
| Luxvisions Innotech Limited            | 16        | 0.98%   |
| Alcor Micro                            | 16        | 0.98%   |
| Sonix Technology                       | 10        | 0.61%   |
| Primax Electronics                     | 9         | 0.55%   |
| Y Media                                | 8         | 0.49%   |
| ALi                                    | 8         | 0.49%   |
| OmniVision Technologies                | 6         | 0.37%   |
| HRY                                    | 6         | 0.37%   |
| Generalplus Technology                 | 6         | 0.37%   |
| SunplusIT                              | 4         | 0.25%   |
| Samsung Electronics                    | 4         | 0.25%   |
| Microsoft                              | 4         | 0.25%   |
| Lenovo                                 | 4         | 0.25%   |
| icSpring                               | 4         | 0.25%   |
| Genesys Logic                          | 4         | 0.25%   |
| MacroSilicon                           | 3         | 0.18%   |
| Z-Star Microelectronics                | 2         | 0.12%   |
| Tobii Technology AB                    | 2         | 0.12%   |
| Sunplus Technology                     | 2         | 0.12%   |
| Jieli Technology                       | 2         | 0.12%   |
| Intel                                  | 2         | 0.12%   |
| Goodong Industry                       | 2         | 0.12%   |
| DigiTech                               | 2         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 60        | 3.66%   |
| Microdia Integrated_Webcam_HD                                  | 49        | 2.99%   |
| Chicony HD WebCam                                              | 39        | 2.38%   |
| IMC Networks Integrated Camera                                 | 37        | 2.26%   |
| Sunplus Integrated_Webcam_HD                                   | 32        | 1.95%   |
| Realtek Integrated_Webcam_HD                                   | 31        | 1.89%   |
| IMC Networks HD Camera                                         | 28        | 1.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 26        | 1.59%   |
| Apple FaceTime HD Camera                                       | 25        | 1.52%   |
| Bison Integrated Camera                                        | 24        | 1.46%   |
| Chicony HP Webcam                                              | 22        | 1.34%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 21        | 1.28%   |
| Chicony HP TrueVision HD Camera                                | 21        | 1.28%   |
| Syntek Integrated Camera                                       | 20        | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 20        | 1.22%   |
| Chicony HP Truevision HD                                       | 19        | 1.16%   |
| Quanta HP Webcam                                               | 18        | 1.1%    |
| Acer Integrated Camera                                         | 17        | 1.04%   |
| Microdia Integrated Webcam                                     | 16        | 0.98%   |
| IMC Networks ov9734_azurewave_camera                           | 16        | 0.98%   |
| Syntek Lenovo EasyCamera                                       | 15        | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 14        | 0.85%   |
| Sunplus HD WebCam                                              | 13        | 0.79%   |
| Realtek USB Camera                                             | 13        | 0.79%   |
| Microdia Sonix USB 2.0 Camera                                  | 13        | 0.79%   |
| Microdia Lenovo EasyCamera                                     | 13        | 0.79%   |
| Lite-On HP Wide Vision HD Camera                               | 13        | 0.79%   |
| IMC Networks EasyCamera                                        | 13        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 13        | 0.79%   |
| Bison EasyCamera                                               | 13        | 0.79%   |
| Chicony TOSHIBA Web Camera - HD                                | 12        | 0.73%   |
| Chicony HP Wide Vision HD Camera                               | 12        | 0.73%   |
| Chicony HP HD Camera                                           | 12        | 0.73%   |
| Suyin HP Truevision HD                                         | 11        | 0.67%   |
| Quanta HP TrueVision HD Camera                                 | 11        | 0.67%   |
| Quanta HD Camera                                               | 11        | 0.67%   |
| Chicony HD User Facing                                         | 11        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 11        | 0.67%   |
| Realtek Integrated Webcam                                      | 10        | 0.61%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 10        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 103       | 33.88%  |
| Shenzhen Goodix Technology         | 79        | 25.99%  |
| Synaptics                          | 44        | 14.47%  |
| AuthenTec                          | 25        | 8.22%   |
| Upek                               | 19        | 6.25%   |
| Elan Microelectronics              | 11        | 3.62%   |
| Focal-systems.Corp                 | 9         | 2.96%   |
| STMicroelectronics                 | 5         | 1.64%   |
| LighTuning Technology              | 3         | 0.99%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.66%   |
| Suprema                            | 1         | 0.33%   |
| Samsung Electronics                | 1         | 0.33%   |
| GDMicroelectronics                 | 1         | 0.33%   |
| FocalTech                          | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 74        | 24.34%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 7.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 5.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.59%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 4.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 4.28%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 4.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 3.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.62%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 9         | 2.96%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.63%   |
| Validity Sensors VFS491                                                    | 6         | 1.97%   |
| AuthenTec AES2810                                                          | 6         | 1.97%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.64%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.64%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.64%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.99%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.99%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.99%   |
| Elan ELAN:Fingerprint                                                      | 3         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.99%   |
| AuthenTec AES1600                                                          | 3         | 0.99%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.66%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.66%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.66%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.66%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.66%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.66%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.33%   |
| Synaptics WBDI Device                                                      | 1         | 0.33%   |
| Synaptics WBDI                                                             | 1         | 0.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.33%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.33%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 54        | 64.29%  |
| Alcor Micro           | 14        | 16.67%  |
| Upek                  | 8         | 9.52%   |
| Lenovo                | 6         | 7.14%   |
| O2 Micro              | 1         | 1.19%   |
| Gemalto (was Gemplus) | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 16.67%  |
| Broadcom 5880                                                                | 12        | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 9.52%   |
| Broadcom 58200                                                               | 7         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.19%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1166      | 63.13%  |
| 1     | 564       | 30.54%  |
| 2     | 105       | 5.68%   |
| 3     | 7         | 0.38%   |
| 5     | 3         | 0.16%   |
| 7     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 301       | 37.25%  |
| Graphics card            | 138       | 17.08%  |
| Net/wireless             | 104       | 12.87%  |
| Chipcard                 | 80        | 9.9%    |
| Multimedia controller    | 62        | 7.67%   |
| Camera                   | 30        | 3.71%   |
| Bluetooth                | 30        | 3.71%   |
| Communication controller | 13        | 1.61%   |
| Storage                  | 11        | 1.36%   |
| Net/ethernet             | 10        | 1.24%   |
| Sound                    | 9         | 1.11%   |
| Card reader              | 9         | 1.11%   |
| Modem                    | 5         | 0.62%   |
| Network                  | 3         | 0.37%   |
| Storage/ide              | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |
| Dvb card                 | 1         | 0.12%   |


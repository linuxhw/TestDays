Linux in Dominican Republic - Tested Hardware & Statistics
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Dominican Republic.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Dominican_Republic/Desktop/README.md) and [notebooks](/Location/Dominican_Republic/Notebook/README.md).

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

Total: 216

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | Notebook    | [ea7f9b7eef](https://linux-hardware.org/?probe=ea7f9b7eef) | Apr 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [d3526466e8](https://linux-hardware.org/?probe=d3526466e8) | Apr 20, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [b7e04c4c41](https://linux-hardware.org/?probe=b7e04c4c41) | Apr 12, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [7a44108d05](https://linux-hardware.org/?probe=7a44108d05) | Mar 16, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [0b91c54846](https://linux-hardware.org/?probe=0b91c54846) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [4687219ca3](https://linux-hardware.org/?probe=4687219ca3) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [687328ccb0](https://linux-hardware.org/?probe=687328ccb0) | Mar 06, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [b12a53ec1e](https://linux-hardware.org/?probe=b12a53ec1e) | Mar 06, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [0620aa7f6f](https://linux-hardware.org/?probe=0620aa7f6f) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [df734c276f](https://linux-hardware.org/?probe=df734c276f) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [00e573a880](https://linux-hardware.org/?probe=00e573a880) | Feb 23, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [6de5bc549f](https://linux-hardware.org/?probe=6de5bc549f) | Jan 29, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [fb42067a32](https://linux-hardware.org/?probe=fb42067a32) | Jan 20, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| HP            | 18E5                        | Desktop     | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Dell          | XPS M1330                   | Notebook    | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | OptiPlex 3020               | Desktop     | [2adcd09348](https://linux-hardware.org/?probe=2adcd09348) | Nov 25, 2022 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [ac7791c167](https://linux-hardware.org/?probe=ac7791c167) | Nov 24, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [1a1f5f8d90](https://linux-hardware.org/?probe=1a1f5f8d90) | Nov 22, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [b2772ed1b3](https://linux-hardware.org/?probe=b2772ed1b3) | Nov 22, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | Notebook    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Dell          | Latitude 5590               | Notebook    | [bbb332cf90](https://linux-hardware.org/?probe=bbb332cf90) | Nov 11, 2022 |
| Dell          | 0VNP2H A00                  | Desktop     | [dff6013531](https://linux-hardware.org/?probe=dff6013531) | Nov 09, 2022 |
| Eluktronic... | P670RE3                     | Notebook    | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [ff4216edcd](https://linux-hardware.org/?probe=ff4216edcd) | Oct 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [240d883d49](https://linux-hardware.org/?probe=240d883d49) | Oct 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Dell          | Latitude 2110               | Notebook    | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [08bd609dbe](https://linux-hardware.org/?probe=08bd609dbe) | Sep 20, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [2b09076619](https://linux-hardware.org/?probe=2b09076619) | Jul 30, 2022 |
| Dell          | OptiPlex 780                | Desktop     | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | Latitude E5440              | Notebook    | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [9cd0caeff2](https://linux-hardware.org/?probe=9cd0caeff2) | Jul 14, 2022 |
| ECS           | ClassMate                   | Notebook    | [c86fa72fe1](https://linux-hardware.org/?probe=c86fa72fe1) | Jun 13, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [fb6db84371](https://linux-hardware.org/?probe=fb6db84371) | Jun 11, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [578aee86ed](https://linux-hardware.org/?probe=578aee86ed) | May 27, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e1e9853d49](https://linux-hardware.org/?probe=e1e9853d49) | May 26, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [62c1081de8](https://linux-hardware.org/?probe=62c1081de8) | May 23, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [c72447a3ea](https://linux-hardware.org/?probe=c72447a3ea) | May 03, 2022 |
| TODOS INDU... | Easytouch_2022_V1           | Notebook    | [efc26220c4](https://linux-hardware.org/?probe=efc26220c4) | May 01, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [454226474b](https://linux-hardware.org/?probe=454226474b) | Apr 29, 2022 |
| Gigabyte      | Z87X-UD5 TH-CF              | Desktop     | [5dc83ea64b](https://linux-hardware.org/?probe=5dc83ea64b) | Apr 24, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [3447b4c67a](https://linux-hardware.org/?probe=3447b4c67a) | Apr 07, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [9d5011b41d](https://linux-hardware.org/?probe=9d5011b41d) | Mar 23, 2022 |
| ASUSTek       | K53E                        | Notebook    | [3a0af085ae](https://linux-hardware.org/?probe=3a0af085ae) | Mar 17, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| Samsung       | 930QCG                      | Convertible | [fb417d6589](https://linux-hardware.org/?probe=fb417d6589) | Feb 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [2322337991](https://linux-hardware.org/?probe=2322337991) | Feb 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [507f27294e](https://linux-hardware.org/?probe=507f27294e) | Feb 15, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [53e23140c0](https://linux-hardware.org/?probe=53e23140c0) | Jan 23, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [b32fd5f07f](https://linux-hardware.org/?probe=b32fd5f07f) | Dec 07, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [9164883468](https://linux-hardware.org/?probe=9164883468) | Nov 27, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [b137bf3459](https://linux-hardware.org/?probe=b137bf3459) | Nov 27, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [e402a0b407](https://linux-hardware.org/?probe=e402a0b407) | Aug 31, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| HP            | 8265                        | Desktop     | [9a7e706a6b](https://linux-hardware.org/?probe=9a7e706a6b) | Aug 07, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7fc508d633](https://linux-hardware.org/?probe=7fc508d633) | Jul 19, 2021 |
| Google        | Winky                       | Notebook    | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ed828bab0](https://linux-hardware.org/?probe=3ed828bab0) | Jul 11, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [9b650cfab3](https://linux-hardware.org/?probe=9b650cfab3) | Jul 11, 2021 |
| Dell          | Latitude E6420              | Notebook    | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [772842d291](https://linux-hardware.org/?probe=772842d291) | Jul 06, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cc6035ae99](https://linux-hardware.org/?probe=cc6035ae99) | Jun 28, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fda4879b12](https://linux-hardware.org/?probe=fda4879b12) | Jun 19, 2021 |
| Dell          | Latitude E6530              | Notebook    | [40566262f5](https://linux-hardware.org/?probe=40566262f5) | Jun 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [9ec2685f9d](https://linux-hardware.org/?probe=9ec2685f9d) | Jun 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [6098210314](https://linux-hardware.org/?probe=6098210314) | Jun 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [2170036527](https://linux-hardware.org/?probe=2170036527) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d310246b09](https://linux-hardware.org/?probe=d310246b09) | Apr 30, 2021 |
| Dell          | Latitude D830               | Notebook    | [f6f0884fca](https://linux-hardware.org/?probe=f6f0884fca) | Apr 28, 2021 |
| Dell          | Latitude E6540              | Notebook    | [522d36a07e](https://linux-hardware.org/?probe=522d36a07e) | Apr 21, 2021 |
| Dell          | Latitude E6540              | Notebook    | [3c76496221](https://linux-hardware.org/?probe=3c76496221) | Apr 21, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [dc8b47f73d](https://linux-hardware.org/?probe=dc8b47f73d) | Feb 14, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [4adcccb57c](https://linux-hardware.org/?probe=4adcccb57c) | Feb 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [96d33743db](https://linux-hardware.org/?probe=96d33743db) | Jan 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [2cf1c789ec](https://linux-hardware.org/?probe=2cf1c789ec) | Dec 29, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | Notebook    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [f18b7b439b](https://linux-hardware.org/?probe=f18b7b439b) | Dec 05, 2020 |
| Fujitsu       | LIFEBOOK AH562              | Notebook    | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [012580c2a7](https://linux-hardware.org/?probe=012580c2a7) | Nov 10, 2020 |
| HP            | Notebook                    | Notebook    | [5176e73c5a](https://linux-hardware.org/?probe=5176e73c5a) | Oct 27, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [d6729d6c6a](https://linux-hardware.org/?probe=d6729d6c6a) | Oct 17, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [907bc464e9](https://linux-hardware.org/?probe=907bc464e9) | Oct 13, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [03c52e4d49](https://linux-hardware.org/?probe=03c52e4d49) | Oct 10, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| HP            | 3647h                       | Desktop     | [5788758b90](https://linux-hardware.org/?probe=5788758b90) | Oct 08, 2020 |
| Dell          | 0MM599                      | Desktop     | [fce90bd449](https://linux-hardware.org/?probe=fce90bd449) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fd73b699f6](https://linux-hardware.org/?probe=fd73b699f6) | Oct 05, 2020 |
| Dell          | Latitude D620               | Notebook    | [3832d0c33e](https://linux-hardware.org/?probe=3832d0c33e) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [80611690cf](https://linux-hardware.org/?probe=80611690cf) | Sep 13, 2020 |
| Dell          | Latitude D620               | Notebook    | [d14cb277b7](https://linux-hardware.org/?probe=d14cb277b7) | Sep 12, 2020 |
| HP            | ProBook 6470b               | Notebook    | [c622e7298d](https://linux-hardware.org/?probe=c622e7298d) | Sep 07, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9b34b0a6c3](https://linux-hardware.org/?probe=9b34b0a6c3) | Sep 03, 2020 |
| Dell          | Vostro 5471                 | Notebook    | [6d24c75bcf](https://linux-hardware.org/?probe=6d24c75bcf) | Sep 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [d24cd3858d](https://linux-hardware.org/?probe=d24cd3858d) | Aug 29, 2020 |
| Nuvision      | L1W6_I1101_G Reserved       | Notebook    | [b3e73aa9ba](https://linux-hardware.org/?probe=b3e73aa9ba) | Aug 29, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9eda45f755](https://linux-hardware.org/?probe=9eda45f755) | Aug 20, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d7d672869f](https://linux-hardware.org/?probe=d7d672869f) | Aug 16, 2020 |
| MSI           | H81M-E33                    | Desktop     | [ba3577fb00](https://linux-hardware.org/?probe=ba3577fb00) | Aug 14, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [081a2c3e4c](https://linux-hardware.org/?probe=081a2c3e4c) | Aug 03, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [6bedf88c28](https://linux-hardware.org/?probe=6bedf88c28) | Jul 30, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [fcbd102a50](https://linux-hardware.org/?probe=fcbd102a50) | Jul 30, 2020 |
| MSI           | B350 GAMING PLUS            | Desktop     | [ca22d3b169](https://linux-hardware.org/?probe=ca22d3b169) | Jul 24, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [4877877772](https://linux-hardware.org/?probe=4877877772) | Jul 04, 2020 |
| Dell          | Vostro A860                 | Notebook    | [16ded4e283](https://linux-hardware.org/?probe=16ded4e283) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| MSI           | H81M-E33                    | Desktop     | [2d531766ab](https://linux-hardware.org/?probe=2d531766ab) | Jun 26, 2020 |
| HP            | 250 G3                      | Notebook    | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Biostar       | G41D3C                      | Desktop     | [15959c0828](https://linux-hardware.org/?probe=15959c0828) | Jun 15, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | Notebook    | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | Notebook    | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | Notebook    | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | Notebook    | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | Notebook    | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| HP            | 3031h                       | Desktop     | [0278ac4043](https://linux-hardware.org/?probe=0278ac4043) | Apr 07, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [87496c419f](https://linux-hardware.org/?probe=87496c419f) | Apr 07, 2020 |
| Dell          | 0WG864                      | Desktop     | [b7c74749f8](https://linux-hardware.org/?probe=b7c74749f8) | Mar 30, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [860893085c](https://linux-hardware.org/?probe=860893085c) | Mar 29, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [48e8186c4f](https://linux-hardware.org/?probe=48e8186c4f) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [080f6bbb80](https://linux-hardware.org/?probe=080f6bbb80) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [740334eed7](https://linux-hardware.org/?probe=740334eed7) | Mar 28, 2020 |
| Dell          | Latitude 3330               | Notebook    | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [44fe9bdc7d](https://linux-hardware.org/?probe=44fe9bdc7d) | Mar 20, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [970faeadaf](https://linux-hardware.org/?probe=970faeadaf) | Mar 19, 2020 |
| HP            | 3031h                       | Desktop     | [3b10a92ee2](https://linux-hardware.org/?probe=3b10a92ee2) | Mar 19, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4f152e3015](https://linux-hardware.org/?probe=4f152e3015) | Mar 06, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [4775efe228](https://linux-hardware.org/?probe=4775efe228) | Feb 27, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [3212549df1](https://linux-hardware.org/?probe=3212549df1) | Feb 05, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [661a8243a3](https://linux-hardware.org/?probe=661a8243a3) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ee353d9346](https://linux-hardware.org/?probe=ee353d9346) | Feb 01, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [51c3c0bb31](https://linux-hardware.org/?probe=51c3c0bb31) | Jan 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [4df330ed80](https://linux-hardware.org/?probe=4df330ed80) | Jan 07, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [a61df97ccd](https://linux-hardware.org/?probe=a61df97ccd) | Dec 19, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [4437a2deed](https://linux-hardware.org/?probe=4437a2deed) | Dec 18, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [edddb5eb5b](https://linux-hardware.org/?probe=edddb5eb5b) | Dec 18, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [e4a03527b5](https://linux-hardware.org/?probe=e4a03527b5) | Dec 11, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [a760ea9cb2](https://linux-hardware.org/?probe=a760ea9cb2) | Nov 14, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [b2477d7154](https://linux-hardware.org/?probe=b2477d7154) | Nov 07, 2019 |
| Gigabyte      | B450 AORUS M                | Desktop     | [628a2983df](https://linux-hardware.org/?probe=628a2983df) | Nov 05, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [cb7b5a4d2e](https://linux-hardware.org/?probe=cb7b5a4d2e) | Oct 13, 2019 |
| Dell          | Latitude E6430              | Notebook    | [49d71b26e7](https://linux-hardware.org/?probe=49d71b26e7) | Oct 08, 2019 |
| Dell          | Latitude E6430              | Notebook    | [b3ef7b4357](https://linux-hardware.org/?probe=b3ef7b4357) | Oct 06, 2019 |
| Dell          | 0M132G A00                  | Desktop     | [b79e419f05](https://linux-hardware.org/?probe=b79e419f05) | Aug 24, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [9a7d44bf28](https://linux-hardware.org/?probe=9a7d44bf28) | Aug 15, 2019 |
| HP            | Pavilion ze2000 (EC201UA... | Notebook    | [572baa05f4](https://linux-hardware.org/?probe=572baa05f4) | Jun 15, 2019 |
| HP            | 3397                        | Desktop     | [24770f4baf](https://linux-hardware.org/?probe=24770f4baf) | Jun 06, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [412e4da0ce](https://linux-hardware.org/?probe=412e4da0ce) | May 21, 2019 |
| HP            | 3396                        | Desktop     | [46d189dc80](https://linux-hardware.org/?probe=46d189dc80) | May 20, 2019 |
| Lenovo        | G40-70 20369                | Notebook    | [1f456620db](https://linux-hardware.org/?probe=1f456620db) | May 05, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0b9c00412b](https://linux-hardware.org/?probe=0b9c00412b) | Dec 14, 2018 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [e30bc2b8f2](https://linux-hardware.org/?probe=e30bc2b8f2) | Nov 02, 2018 |
| Dell          | 0PU052                      | Desktop     | [a5f063bc44](https://linux-hardware.org/?probe=a5f063bc44) | Apr 19, 2018 |
| Dell          | 0PU052                      | Desktop     | [e8fb115c06](https://linux-hardware.org/?probe=e8fb115c06) | Jan 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 21        | 14.29%  |
| Ubuntu 18.04                 | 17        | 11.56%  |
| Ubuntu 22.04                 | 8         | 5.44%   |
| OpenMandriva 4.3             | 7         | 4.76%   |
| Arch Rolling                 | 6         | 4.08%   |
| OpenMandriva 4.2             | 5         | 3.4%    |
| Fedora 37                    | 4         | 2.72%   |
| Fedora 36                    | 4         | 2.72%   |
| Linux Mint 20.3              | 3         | 2.04%   |
| Fedora 34                    | 3         | 2.04%   |
| Debian 11                    | 3         | 2.04%   |
| Arch                         | 3         | 2.04%   |
| Zorin 16                     | 2         | 1.36%   |
| Ubuntu 22.10                 | 2         | 1.36%   |
| Ubuntu 21.10                 | 2         | 1.36%   |
| Pop!_OS 20.10                | 2         | 1.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.36%   |
| OpenMandriva 23.03           | 2         | 1.36%   |
| Linux Mint 21                | 2         | 1.36%   |
| Linux Mint 20.1              | 2         | 1.36%   |
| Linux Mint 19.3              | 2         | 1.36%   |
| Fedora 33                    | 2         | 1.36%   |
| ArcoLinux Rolling            | 2         | 1.36%   |
| Xubuntu 19.10                | 1         | 0.68%   |
| Xubuntu 18.04                | 1         | 0.68%   |
| Void Linux Rolling           | 1         | 0.68%   |
| Ubuntu Budgie 22.04          | 1         | 0.68%   |
| Ubuntu Budgie 21.10          | 1         | 0.68%   |
| Ubuntu Budgie 20.04          | 1         | 0.68%   |
| Ubuntu 21.04                 | 1         | 0.68%   |
| Ubuntu 19.10                 | 1         | 0.68%   |
| Ubuntu 19.04                 | 1         | 0.68%   |
| Solus 4.1                    | 1         | 0.68%   |
| ROSA R10                     | 1         | 0.68%   |
| Pop!_OS 22.04                | 1         | 0.68%   |
| Pop!_OS 21.04                | 1         | 0.68%   |
| Pop!_OS 20.04                | 1         | 0.68%   |
| OpenMandriva 4.90            | 1         | 0.68%   |
| OpenMandriva 23.01           | 1         | 0.68%   |
| Manjaro 22.0.0               | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 51        | 35.66%  |
| OpenMandriva  | 15        | 10.49%  |
| Fedora        | 15        | 10.49%  |
| Linux Mint    | 12        | 8.39%   |
| Arch          | 9         | 6.29%   |
| Pop!_OS       | 5         | 3.5%    |
| Manjaro       | 4         | 2.8%    |
| Debian        | 4         | 2.8%    |
| Ubuntu Budgie | 3         | 2.1%    |
| Clear Linux   | 3         | 2.1%    |
| Zorin         | 2         | 1.4%    |
| Xubuntu       | 2         | 1.4%    |
| openSUSE      | 2         | 1.4%    |
| KDE neon      | 2         | 1.4%    |
| ArcoLinux     | 2         | 1.4%    |
| Void Linux    | 1         | 0.7%    |
| Solus         | 1         | 0.7%    |
| ROSA          | 1         | 0.7%    |
| Lubuntu       | 1         | 0.7%    |
| LMDE          | 1         | 0.7%    |
| Kubuntu       | 1         | 0.7%    |
| Kali          | 1         | 0.7%    |
| Endless       | 1         | 0.7%    |
| Elementary    | 1         | 0.7%    |
| CentOS        | 1         | 0.7%    |
| BlackPanther  | 1         | 0.7%    |
| Archcraft     | 1         | 0.7%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 7         | 4.24%   |
| 5.4.0-48-generic         | 4         | 2.42%   |
| 5.4.0-42-generic         | 4         | 2.42%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.42%   |
| 5.15.0-53-generic        | 3         | 1.82%   |
| 5.13.0-22-generic        | 3         | 1.82%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.21%   |
| 5.4.0-77-generic         | 2         | 1.21%   |
| 5.4.0-52-generic         | 2         | 1.21%   |
| 5.4.0-33-generic         | 2         | 1.21%   |
| 5.3.0-51-generic         | 2         | 1.21%   |
| 5.3.0-46-generic         | 2         | 1.21%   |
| 5.3.0-42-generic         | 2         | 1.21%   |
| 5.15.0-58-generic        | 2         | 1.21%   |
| 5.15.0-50-generic        | 2         | 1.21%   |
| 5.15.0-41-generic        | 2         | 1.21%   |
| 5.11.0-40-generic        | 2         | 1.21%   |
| 5.11.0-25-generic        | 2         | 1.21%   |
| 5.0.0-32-generic         | 2         | 1.21%   |
| 6.2.7-arch1-1            | 1         | 0.61%   |
| 6.2.6-desktop-1omv2390   | 1         | 0.61%   |
| 6.1.5-200.fc37.x86_64    | 1         | 0.61%   |
| 6.1.18-200.fc37.x86_64   | 1         | 0.61%   |
| 6.0.6-300.fc37.x86_64    | 1         | 0.61%   |
| 6.0.14-300.fc37.x86_64   | 1         | 0.61%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.61%   |
| 5.9.12-xanmod1           | 1         | 0.61%   |
| 5.9.11-arch2-1           | 1         | 0.61%   |
| 5.9.1-arch1-1            | 1         | 0.61%   |
| 5.8.8-arch1-1            | 1         | 0.61%   |
| 5.8.5-arch1-1            | 1         | 0.61%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.61%   |
| 5.8.12_1                 | 1         | 0.61%   |
| 5.8.0-38-generic         | 1         | 0.61%   |
| 5.7.7-zen1-1-zen         | 1         | 0.61%   |
| 5.7.7-arch1-1            | 1         | 0.61%   |
| 5.7.10-201.fc32.x86_64   | 1         | 0.61%   |
| 5.6.19-158.current       | 1         | 0.61%   |
| 5.5.13-arch1-1           | 1         | 0.61%   |
| 5.4.60-2-MANJARO         | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 16.34%  |
| 5.15.0  | 14        | 9.15%   |
| 5.13.0  | 10        | 6.54%   |
| 5.3.0   | 9         | 5.88%   |
| 5.11.0  | 8         | 5.23%   |
| 5.16.7  | 7         | 4.58%   |
| 4.15.0  | 6         | 3.92%   |
| 5.0.0   | 5         | 3.27%   |
| 5.19.0  | 4         | 2.61%   |
| 5.10.14 | 4         | 2.61%   |
| 5.10.0  | 3         | 1.96%   |
| 6.1.1   | 2         | 1.31%   |
| 5.7.7   | 2         | 1.31%   |
| 4.19.0  | 2         | 1.31%   |
| 4.18.0  | 2         | 1.31%   |
| 6.2.7   | 1         | 0.65%   |
| 6.2.6   | 1         | 0.65%   |
| 6.1.5   | 1         | 0.65%   |
| 6.1.18  | 1         | 0.65%   |
| 6.0.6   | 1         | 0.65%   |
| 6.0.14  | 1         | 0.65%   |
| 5.9.16  | 1         | 0.65%   |
| 5.9.12  | 1         | 0.65%   |
| 5.9.11  | 1         | 0.65%   |
| 5.9.1   | 1         | 0.65%   |
| 5.8.8   | 1         | 0.65%   |
| 5.8.5   | 1         | 0.65%   |
| 5.8.15  | 1         | 0.65%   |
| 5.8.12  | 1         | 0.65%   |
| 5.8.0   | 1         | 0.65%   |
| 5.7.10  | 1         | 0.65%   |
| 5.6.19  | 1         | 0.65%   |
| 5.5.13  | 1         | 0.65%   |
| 5.4.60  | 1         | 0.65%   |
| 5.4.4   | 1         | 0.65%   |
| 5.4.15  | 1         | 0.65%   |
| 5.19.7  | 1         | 0.65%   |
| 5.19.14 | 1         | 0.65%   |
| 5.19.12 | 1         | 0.65%   |
| 5.18.17 | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 18.54%  |
| 5.15    | 16        | 10.6%   |
| 5.13    | 11        | 7.28%   |
| 5.11    | 10        | 6.62%   |
| 5.3     | 9         | 5.96%   |
| 5.10    | 8         | 5.3%    |
| 5.19    | 7         | 4.64%   |
| 5.16    | 7         | 4.64%   |
| 5.0     | 6         | 3.97%   |
| 4.15    | 6         | 3.97%   |
| 5.8     | 5         | 3.31%   |
| 6.1     | 4         | 2.65%   |
| 5.9     | 4         | 2.65%   |
| 5.18    | 4         | 2.65%   |
| 5.12    | 4         | 2.65%   |
| 4.18    | 4         | 2.65%   |
| 5.7     | 3         | 1.99%   |
| 4.19    | 3         | 1.99%   |
| 6.2     | 2         | 1.32%   |
| 6.0     | 2         | 1.32%   |
| 5.17    | 2         | 1.32%   |
| 5.1     | 2         | 1.32%   |
| 5.6     | 1         | 0.66%   |
| 5.5     | 1         | 0.66%   |
| 5.14    | 1         | 0.66%   |
| 4.9     | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 139       | 97.2%   |
| i686   | 4         | 2.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 70        | 48.61%  |
| KDE5       | 25        | 17.36%  |
| Unknown    | 12        | 8.33%   |
| XFCE       | 11        | 7.64%   |
| X-Cinnamon | 10        | 6.94%   |
| KDE        | 4         | 2.78%   |
| Budgie     | 4         | 2.78%   |
| MATE       | 2         | 1.39%   |
| LXQt       | 2         | 1.39%   |
| sway       | 1         | 0.69%   |
| LXDE       | 1         | 0.69%   |
| KDE4       | 1         | 0.69%   |
| DWM        | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 115       | 79.31%  |
| Wayland | 23        | 15.86%  |
| Unknown | 5         | 3.45%   |
| Tty     | 2         | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 48.95%  |
| SDDM    | 28        | 19.58%  |
| GDM     | 16        | 11.19%  |
| GDM3    | 15        | 10.49%  |
| LightDM | 9         | 6.29%   |
| TDM     | 4         | 2.8%    |
| KDM     | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 75        | 51.37%  |
| es_DO   | 42        | 28.77%  |
| Unknown | 14        | 9.59%   |
| es_ES   | 6         | 4.11%   |
| es_MX   | 3         | 2.05%   |
| en_CA   | 2         | 1.37%   |
| ru_RU   | 1         | 0.68%   |
| fr_FR   | 1         | 0.68%   |
| es_US   | 1         | 0.68%   |
| C       | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 79        | 55.24%  |
| EFI  | 64        | 44.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 107       | 74.31%  |
| Overlay | 15        | 10.42%  |
| Btrfs   | 14        | 9.72%   |
| Xfs     | 4         | 2.78%   |
| Unknown | 2         | 1.39%   |
| Zfs     | 1         | 0.69%   |
| F2fs    | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 75        | 51.37%  |
| GPT     | 56        | 38.36%  |
| MBR     | 15        | 10.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 81.38%  |
| Yes       | 27        | 18.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 66.21%  |
| Yes       | 49        | 33.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 45        | 31.47%  |
| Hewlett-Packard     | 21        | 14.69%  |
| Lenovo              | 18        | 12.59%  |
| Gigabyte Technology | 10        | 6.99%   |
| ASUSTek Computer    | 10        | 6.99%   |
| Acer                | 5         | 3.5%    |
| MSI                 | 4         | 2.8%    |
| Apple               | 4         | 2.8%    |
| Samsung Electronics | 3         | 2.1%    |
| ASRock              | 3         | 2.1%    |
| Unknown             | 3         | 2.1%    |
| Google              | 2         | 1.4%    |
| EVOO                | 2         | 1.4%    |
| VTEX                | 1         | 0.7%    |
| Toshiba             | 1         | 0.7%    |
| TODOS INDUSTRIAL    | 1         | 0.7%    |
| SAELITE             | 1         | 0.7%    |
| Nuvision            | 1         | 0.7%    |
| Microsoft           | 1         | 0.7%    |
| Fujitsu             | 1         | 0.7%    |
| Foxconn             | 1         | 0.7%    |
| Eluktronics         | 1         | 0.7%    |
| ECS                 | 1         | 0.7%    |
| Chuwi               | 1         | 0.7%    |
| Biostar             | 1         | 0.7%    |
| AMI                 | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 3         | 2.1%    |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 1.4%    |
| HP EliteBook 8460p                                | 2         | 1.4%    |
| Gigabyte GA-78LMT-USB3 6.0                        | 2         | 1.4%    |
| EVOO EV-C-116-7                                   | 2         | 1.4%    |
| Dell OptiPlex 990                                 | 2         | 1.4%    |
| Dell OptiPlex 3010                                | 2         | 1.4%    |
| Dell Latitude E6540                               | 2         | 1.4%    |
| Dell Latitude E6430                               | 2         | 1.4%    |
| Dell Latitude E6420                               | 2         | 1.4%    |
| Dell Latitude E6410                               | 2         | 1.4%    |
| Dell Inspiron 5570                                | 2         | 1.4%    |
| Apple MacBookPro8,1                               | 2         | 1.4%    |
| VTEX NOTEBOOK                                     | 1         | 0.7%    |
| Toshiba Satellite C55-A                           | 1         | 0.7%    |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.7%    |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.7%    |
| Samsung 930QCG                                    | 1         | 0.7%    |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.7%    |
| SAELITE ES1AU11                                   | 1         | 0.7%    |
| Nuvision NES11                                    | 1         | 0.7%    |
| MSI MS-7A34                                       | 1         | 0.7%    |
| MSI MS-7817                                       | 1         | 0.7%    |
| MSI GE62 6QC                                      | 1         | 0.7%    |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.7%    |
| Microsoft Surface Go                              | 1         | 0.7%    |
| Lenovo Z50-75 80EC                                | 1         | 0.7%    |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.7%    |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.7%    |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 0.7%    |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.7%    |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.7%    |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 0.7%    |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.7%    |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.7%    |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.7%    |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.7%    |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.7%    |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.7%    |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 18        | 12.59%  |
| Dell OptiPlex              | 12        | 8.39%   |
| Dell Inspiron              | 9         | 6.29%   |
| Lenovo ThinkPad            | 8         | 5.59%   |
| Acer Aspire                | 5         | 3.5%    |
| Lenovo IdeaPad             | 4         | 2.8%    |
| HP Compaq                  | 4         | 2.8%    |
| HP Pavilion                | 3         | 2.1%    |
| HP EliteBook               | 3         | 2.1%    |
| Gigabyte GA-78LMT-USB3     | 3         | 2.1%    |
| Unknown                    | 3         | 2.1%    |
| HP ProBook                 | 2         | 1.4%    |
| HP Laptop                  | 2         | 1.4%    |
| HP EliteDesk               | 2         | 1.4%    |
| Gigabyte B450M             | 2         | 1.4%    |
| EVOO EV-C-116-7            | 2         | 1.4%    |
| Dell Vostro                | 2         | 1.4%    |
| ASUS VivoBook              | 2         | 1.4%    |
| Apple MacBookPro8          | 2         | 1.4%    |
| VTEX NOTEBOOK              | 1         | 0.7%    |
| Toshiba Satellite          | 1         | 0.7%    |
| TODOS INDUSTRIAL Easytouch | 1         | 0.7%    |
| Samsung RV420              | 1         | 0.7%    |
| Samsung 930QCG             | 1         | 0.7%    |
| Samsung 905S3G             | 1         | 0.7%    |
| SAELITE ES1AU11            | 1         | 0.7%    |
| Nuvision NES11             | 1         | 0.7%    |
| MSI MS-7A34                | 1         | 0.7%    |
| MSI MS-7817                | 1         | 0.7%    |
| MSI GE62                   | 1         | 0.7%    |
| MSI CR70                   | 1         | 0.7%    |
| Microsoft Surface          | 1         | 0.7%    |
| Lenovo Z50-75              | 1         | 0.7%    |
| Lenovo Yoga                | 1         | 0.7%    |
| Lenovo ThinkBook           | 1         | 0.7%    |
| Lenovo Legion              | 1         | 0.7%    |
| Lenovo G505s               | 1         | 0.7%    |
| Lenovo G40-70              | 1         | 0.7%    |
| HP Notebook                | 1         | 0.7%    |
| HP G60                     | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 17        | 11.89%  |
| 2017 | 16        | 11.19%  |
| 2014 | 13        | 9.09%   |
| 2013 | 13        | 9.09%   |
| 2019 | 11        | 7.69%   |
| 2012 | 11        | 7.69%   |
| 2018 | 8         | 5.59%   |
| 2021 | 7         | 4.9%    |
| 2020 | 7         | 4.9%    |
| 2010 | 7         | 4.9%    |
| 2008 | 7         | 4.9%    |
| 2016 | 6         | 4.2%    |
| 2015 | 6         | 4.2%    |
| 2009 | 5         | 3.5%    |
| 2007 | 4         | 2.8%    |
| 2022 | 2         | 1.4%    |
| 2006 | 2         | 1.4%    |
| 2005 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 95        | 66.43%  |
| Desktop     | 42        | 29.37%  |
| Tablet      | 2         | 1.4%    |
| Convertible | 2         | 1.4%    |
| Mini pc     | 1         | 0.7%    |
| All in one  | 1         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 138       | 96.5%   |
| Enabled  | 5         | 3.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 98.6%   |
| Yes  | 2         | 1.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 42        | 29.37%  |
| 4.01-8.0    | 37        | 25.87%  |
| 8.01-16.0   | 24        | 16.78%  |
| 16.01-24.0  | 20        | 13.99%  |
| 2.01-3.0    | 5         | 3.5%    |
| 1.01-2.0    | 5         | 3.5%    |
| 32.01-64.0  | 4         | 2.8%    |
| 24.01-32.0  | 3         | 2.1%    |
| 0.51-1.0    | 2         | 1.4%    |
| 64.01-256.0 | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 61        | 40.13%  |
| 2.01-3.0  | 40        | 26.32%  |
| 3.01-4.0  | 26        | 17.11%  |
| 4.01-8.0  | 13        | 8.55%   |
| 0.51-1.0  | 10        | 6.58%   |
| 8.01-16.0 | 2         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 101       | 69.66%  |
| 2      | 33        | 22.76%  |
| 3      | 7         | 4.83%   |
| 4      | 4         | 2.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 55.24%  |
| Yes       | 64        | 44.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 84.62%  |
| No        | 22        | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 83.33%  |
| No        | 24        | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 56.25%  |
| No        | 63        | 43.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 143       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 87        | 58.78%  |
| Santiago de los Caballeros | 14        | 9.46%   |
| Santo Domingo              | 7         | 4.73%   |
| La Romana                  | 6         | 4.05%   |
| Alejandro Bass             | 4         | 2.7%    |
| San Pedro de Macorís      | 3         | 2.03%   |
| San Cristobal              | 3         | 2.03%   |
| Sosua, Cabarete            | 2         | 1.35%   |
| Santa Cruz de Barahona     | 2         | 1.35%   |
| San Juan                   | 2         | 1.35%   |
| Nacional                   | 2         | 1.35%   |
| Constanza                  | 2         | 1.35%   |
| Bajos de Haina             | 2         | 1.35%   |
| Santo Domingo Oeste        | 1         | 0.68%   |
| San Francisco de Macorís  | 1         | 0.68%   |
| Salcedo                    | 1         | 0.68%   |
| Punta Cana                 | 1         | 0.68%   |
| Moca                       | 1         | 0.68%   |
| Los Hidalgos               | 1         | 0.68%   |
| Guaymate                   | 1         | 0.68%   |
| Cotui                      | 1         | 0.68%   |
| Concepción de la Vega     | 1         | 0.68%   |
| Cancino                    | 1         | 0.68%   |
| Boca Chica                 | 1         | 0.68%   |
| Baní                      | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 42        | 55     | 22.58%  |
| Samsung Electronics       | 22        | 27     | 11.83%  |
| Toshiba                   | 20        | 25     | 10.75%  |
| WDC                       | 19        | 24     | 10.22%  |
| Hitachi                   | 14        | 17     | 7.53%   |
| Kingston                  | 13        | 14     | 6.99%   |
| SanDisk                   | 10        | 14     | 5.38%   |
| Unknown                   | 8         | 10     | 4.3%    |
| SK hynix                  | 5         | 6      | 2.69%   |
| Intel                     | 4         | 4      | 2.15%   |
| Unknown                   | 3         | 3      | 1.61%   |
| Transcend                 | 2         | 2      | 1.08%   |
| Micron Technology         | 2         | 2      | 1.08%   |
| FORESEE                   | 2         | 2      | 1.08%   |
| Crucial                   | 2         | 3      | 1.08%   |
| China                     | 2         | 3      | 1.08%   |
| A-DATA Technology         | 2         | 2      | 1.08%   |
| UMIS                      | 1         | 1      | 0.54%   |
| SPCC                      | 1         | 1      | 0.54%   |
| PNY                       | 1         | 1      | 0.54%   |
| Phison Electronics        | 1         | 1      | 0.54%   |
| Patriot                   | 1         | 1      | 0.54%   |
| OCZ                       | 1         | 1      | 0.54%   |
| Micron/Crucial Technology | 1         | 1      | 0.54%   |
| Maxtor                    | 1         | 1      | 0.54%   |
| LITEONIT                  | 1         | 2      | 0.54%   |
| Indilinx                  | 1         | 1      | 0.54%   |
| Hewlett-Packard           | 1         | 1      | 0.54%   |
| Eluktro                   | 1         | 1      | 0.54%   |
| ELOTEC                    | 1         | 1      | 0.54%   |
| AirDisk                   | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB  | 4         | 2.01%   |
| Unknown MMC Card  32GB           | 3         | 1.51%   |
| Toshiba MQ01ACF050 500GB         | 3         | 1.51%   |
| Toshiba MK3275GSX 320GB          | 3         | 1.51%   |
| Seagate ST500DM002-1BD142 500GB  | 3         | 1.51%   |
| Samsung SSD 860 EVO 500GB        | 3         | 1.51%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.51%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 1.51%   |
| Unknown                          | 3         | 1.51%   |
| Unknown MMC Card  64GB           | 2         | 1.01%   |
| Unknown MMC Card  16GB           | 2         | 1.01%   |
| Toshiba MK2556GSY 250GB          | 2         | 1.01%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.01%   |
| Seagate ST9250315AS 250GB        | 2         | 1.01%   |
| Seagate ST380815AS 80GB          | 2         | 1.01%   |
| Seagate ST3500418AS 500GB        | 2         | 1.01%   |
| Seagate ST3160815AS 160GB        | 2         | 1.01%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 1.01%   |
| Seagate ST1000LM035-1RK172 970GB | 2         | 1.01%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.01%   |
| Samsung SSD 850 EVO 250GB        | 2         | 1.01%   |
| Kingston SV300S37A120G 120GB SSD | 2         | 1.01%   |
| Kingston SA400S37240G 240GB SSD  | 2         | 1.01%   |
| FORESEE 128GB SSD                | 2         | 1.01%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1         | 0.5%    |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 0.5%    |
| WDC WD6400AAKS-22A7B2 640GB      | 1         | 0.5%    |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.5%    |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.5%    |
| WDC WD5000AAKX-75U6AA0 500GB     | 1         | 0.5%    |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.5%    |
| WDC WD3200LPVX-75V0TT0 320GB     | 1         | 0.5%    |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 0.5%    |
| WDC WD2500BEVT-75A23T0 250GB     | 1         | 0.5%    |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 0.5%    |
| WDC WD2500BEKT-60A25T1 250GB     | 1         | 0.5%    |
| WDC WD2500AAKX-001CA0 250GB      | 1         | 0.5%    |
| WDC WD2500AAJS-75M0A0 250GB      | 1         | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.5%    |
| WDC WD1600BEVT-75ZCT1 160GB      | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 55     | 43.75%  |
| Toshiba             | 18        | 22     | 18.75%  |
| WDC                 | 17        | 22     | 17.71%  |
| Hitachi             | 14        | 17     | 14.58%  |
| Samsung Electronics | 4         | 6      | 4.17%   |
| Maxtor              | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 22.81%  |
| Kingston            | 12        | 13     | 21.05%  |
| SanDisk             | 7         | 11     | 12.28%  |
| WDC                 | 2         | 2      | 3.51%   |
| Transcend           | 2         | 2      | 3.51%   |
| SK hynix            | 2         | 2      | 3.51%   |
| Intel               | 2         | 2      | 3.51%   |
| FORESEE             | 2         | 2      | 3.51%   |
| Crucial             | 2         | 3      | 3.51%   |
| China               | 2         | 3      | 3.51%   |
| A-DATA Technology   | 2         | 2      | 3.51%   |
| SPCC                | 1         | 1      | 1.75%   |
| PNY                 | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| OCZ                 | 1         | 1      | 1.75%   |
| LITEONIT            | 1         | 2      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |
| Eluktro             | 1         | 1      | 1.75%   |
| AirDisk             | 1         | 1      | 1.75%   |
| Unknown             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 84        | 123    | 49.41%  |
| SSD     | 52        | 66     | 30.59%  |
| NVMe    | 21        | 24     | 12.35%  |
| MMC     | 10        | 12     | 5.88%   |
| Unknown | 3         | 3      | 1.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 121       | 187    | 77.56%  |
| NVMe | 21        | 24     | 13.46%  |
| MMC  | 10        | 12     | 6.41%   |
| SAS  | 4         | 5      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 141    | 70.8%   |
| 0.51-1.0   | 29        | 36     | 21.17%  |
| 1.01-2.0   | 5         | 5      | 3.65%   |
| 3.01-4.0   | 3         | 3      | 2.19%   |
| 4.01-10.0  | 3         | 4      | 2.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 32.45%  |
| 251-500        | 26        | 17.22%  |
| 501-1000       | 25        | 16.56%  |
| 1-20           | 16        | 10.6%   |
| 51-100         | 14        | 9.27%   |
| 21-50          | 7         | 4.64%   |
| More than 3000 | 5         | 3.31%   |
| 1001-2000      | 5         | 3.31%   |
| Unknown        | 3         | 1.99%   |
| 2001-3000      | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 40.63%  |
| 21-50          | 31        | 19.38%  |
| 51-100         | 22        | 13.75%  |
| 101-250        | 16        | 10%     |
| 251-500        | 10        | 6.25%   |
| 501-1000       | 7         | 4.38%   |
| 2001-3000      | 3         | 1.88%   |
| Unknown        | 3         | 1.88%   |
| 1001-2000      | 2         | 1.25%   |
| More than 3000 | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MK3275GSX 320GB           | 2         | 2      | 7.69%   |
| WDC WD6400AAKS-22A7B2 640GB       | 1         | 1      | 3.85%   |
| WDC WD5000AZLX-60K2TA0 500GB      | 1         | 1      | 3.85%   |
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050V 500GB         | 1         | 1      | 3.85%   |
| Toshiba MK6465GSXN 640GB          | 1         | 1      | 3.85%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 3.85%   |
| Toshiba MK2556GSY 250GB           | 1         | 1      | 3.85%   |
| Toshiba MK1655GSX 160GB           | 1         | 1      | 3.85%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 3.85%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 3.85%   |
| Seagate ST3250318AS 250GB         | 1         | 1      | 3.85%   |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 3.85%   |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 3.85%   |
| Samsung Electronics HD154UI 1TB   | 1         | 1      | 3.85%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 3.85%   |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 3.85%   |
| Hitachi HTS722020K9SA00 200GB     | 1         | 1      | 3.85%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 3.85%   |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 3.85%   |
| Hitachi HDT721025SLA380 250GB     | 1         | 1      | 3.85%   |
| Crucial CT240BX500SSD1 240GB      | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 26.92%  |
| Hitachi             | 7         | 7      | 26.92%  |
| Seagate             | 6         | 6      | 23.08%  |
| WDC                 | 3         | 3      | 11.54%  |
| Samsung Electronics | 2         | 2      | 7.69%   |
| Crucial             | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 28%     |
| Hitachi             | 7         | 7      | 28%     |
| Seagate             | 6         | 6      | 24%     |
| WDC                 | 3         | 3      | 12%     |
| Samsung Electronics | 2         | 2      | 8%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 25     | 95.65%  |
| SSD  | 1         | 1      | 4.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HDS721025CLA382 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 86        | 138    | 55.48%  |
| Works    | 46        | 63     | 29.68%  |
| Malfunc  | 22        | 26     | 14.19%  |
| Failed   | 1         | 1      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 102       | 66.67%  |
| AMD                              | 27        | 17.65%  |
| Samsung Electronics              | 6         | 3.92%   |
| SanDisk                          | 3         | 1.96%   |
| Toshiba America Info Systems     | 2         | 1.31%   |
| SK hynix                         | 2         | 1.31%   |
| Micron Technology                | 2         | 1.31%   |
| VIA Technologies                 | 1         | 0.65%   |
| Union Memory (Shenzhen)          | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Phison Electronics               | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| Micron/Crucial Technology        | 1         | 0.65%   |
| Marvell Technology Group         | 1         | 0.65%   |
| Kingston Technology Company      | 1         | 0.65%   |
| ASMedia Technology               | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 10.61%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 5.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 5.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 3.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.79%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 2.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.68%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3         | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.68%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.12%   |
| Micron NVMe Storage Controller                                                 | 2         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.12%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 1.12%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.56%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 1         | 0.56%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.56%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.56%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.56%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 0.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.56%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 101       | 61.96%  |
| IDE  | 25        | 15.34%  |
| NVMe | 21        | 12.88%  |
| RAID | 16        | 9.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 114       | 79.72%  |
| AMD    | 29        | 20.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 2.8%    |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 2.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 2.1%    |
| Intel Celeron N4120 CPU @ 1.10GHz           | 3         | 2.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.4%    |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.4%    |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.4%    |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 1.4%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.4%    |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.4%    |
| AMD FX-8320 Eight-Core Processor            | 2         | 1.4%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.4%    |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.7%    |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.7%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.7%    |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.7%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.7%    |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.7%    |
| Intel Pentium CPU 4415Y @ 1.60GHz           | 1         | 0.7%    |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.7%    |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.7%    |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.7%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.7%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 30.07%  |
| Intel Core i7           | 16        | 11.19%  |
| Intel Celeron           | 16        | 11.19%  |
| Intel Core i3           | 12        | 8.39%   |
| AMD Ryzen 5             | 8         | 5.59%   |
| Intel Core 2 Duo        | 7         | 4.9%    |
| Intel Atom              | 4         | 2.8%    |
| AMD FX                  | 4         | 2.8%    |
| Intel Pentium           | 3         | 2.1%    |
| Intel Xeon              | 2         | 1.4%    |
| Intel Pentium Dual-Core | 2         | 1.4%    |
| Intel Core 2            | 2         | 1.4%    |
| AMD Ryzen 7             | 2         | 1.4%    |
| AMD Ryzen 3             | 2         | 1.4%    |
| AMD A8                  | 2         | 1.4%    |
| AMD A6                  | 2         | 1.4%    |
| AMD A10                 | 2         | 1.4%    |
| Other                   | 1         | 0.7%    |
| Intel Pentium Dual      | 1         | 0.7%    |
| Intel Pentium D         | 1         | 0.7%    |
| Intel Pentium 4         | 1         | 0.7%    |
| Intel Genuine           | 1         | 0.7%    |
| Intel Core i9           | 1         | 0.7%    |
| Intel Core 2 Quad       | 1         | 0.7%    |
| AMD Sempron             | 1         | 0.7%    |
| AMD Quad-Core           | 1         | 0.7%    |
| AMD PRO A10             | 1         | 0.7%    |
| AMD Phenom II X4        | 1         | 0.7%    |
| AMD Mobile Sempron      | 1         | 0.7%    |
| AMD A4                  | 1         | 0.7%    |
| AMD A12                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 78        | 54.55%  |
| 4      | 50        | 34.97%  |
| 6      | 6         | 4.2%    |
| 1      | 5         | 3.5%    |
| 8      | 2         | 1.4%    |
| 12     | 1         | 0.7%    |
| 3      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 142       | 99.3%   |
| 2      | 1         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 81        | 56.64%  |
| 1      | 62        | 43.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 97.92%  |
| 64-bit         | 1         | 0.69%   |
| 32-bit         | 1         | 0.69%   |
| Unknown        | 1         | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 18.62%  |
| 0x206a7    | 14        | 9.66%   |
| 0x306a9    | 11        | 7.59%   |
| 0x306c3    | 8         | 5.52%   |
| 0x1067a    | 7         | 4.83%   |
| 0x806e9    | 6         | 4.14%   |
| 0x506e3    | 6         | 4.14%   |
| 0x40651    | 5         | 3.45%   |
| 0x806ea    | 4         | 2.76%   |
| 0x706a1    | 4         | 2.76%   |
| 0x30678    | 3         | 2.07%   |
| 0x0800820d | 3         | 2.07%   |
| 0x07030105 | 3         | 2.07%   |
| 0x06000852 | 3         | 2.07%   |
| 0x806ec    | 2         | 1.38%   |
| 0x706a8    | 2         | 1.38%   |
| 0x6fb      | 2         | 1.38%   |
| 0x6f6      | 2         | 1.38%   |
| 0x20655    | 2         | 1.38%   |
| 0x20652    | 2         | 1.38%   |
| 0x10676    | 2         | 1.38%   |
| 0x08108109 | 2         | 1.38%   |
| 0x0600611a | 2         | 1.38%   |
| 0xf65      | 1         | 0.69%   |
| 0xf49      | 1         | 0.69%   |
| 0x906ea    | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x806c1    | 1         | 0.69%   |
| 0x706e5    | 1         | 0.69%   |
| 0x6fd      | 1         | 0.69%   |
| 0x506c9    | 1         | 0.69%   |
| 0x406c3    | 1         | 0.69%   |
| 0x30679    | 1         | 0.69%   |
| 0x106ca    | 1         | 0.69%   |
| 0x106c2    | 1         | 0.69%   |
| 0x10661    | 1         | 0.69%   |
| 0x08608103 | 1         | 0.69%   |
| 0x08608102 | 1         | 0.69%   |
| 0x08600103 | 1         | 0.69%   |
| 0x08108102 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 14.69%  |
| SandyBridge   | 15        | 10.49%  |
| Haswell       | 15        | 10.49%  |
| IvyBridge     | 13        | 9.09%   |
| Penryn        | 9         | 6.29%   |
| Silvermont    | 8         | 5.59%   |
| Zen+          | 7         | 4.9%    |
| Westmere      | 7         | 4.9%    |
| Goldmont plus | 7         | 4.9%    |
| Skylake       | 6         | 4.2%    |
| Core          | 6         | 4.2%    |
| Piledriver    | 4         | 2.8%    |
| Puma          | 3         | 2.1%    |
| Excavator     | 3         | 2.1%    |
| NetBurst      | 2         | 1.4%    |
| K8 Hammer     | 2         | 1.4%    |
| Bonnell       | 2         | 1.4%    |
| Unknown       | 2         | 1.4%    |
| Zen 3         | 1         | 0.7%    |
| Zen 2         | 1         | 0.7%    |
| Zen           | 1         | 0.7%    |
| TigerLake     | 1         | 0.7%    |
| Steamroller   | 1         | 0.7%    |
| K10 Llano     | 1         | 0.7%    |
| K10           | 1         | 0.7%    |
| Jaguar        | 1         | 0.7%    |
| IceLake       | 1         | 0.7%    |
| Goldmont      | 1         | 0.7%    |
| Bulldozer     | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 100       | 63.29%  |
| AMD                              | 33        | 20.89%  |
| Nvidia                           | 23        | 14.56%  |
| VIA Technologies                 | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 7.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 5.52%   |
| Intel UHD Graphics 620                                                                   | 7         | 4.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 4.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 3.68%   |
| Intel HD Graphics 620                                                                    | 6         | 3.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.68%   |
| Intel HD Graphics 530                                                                    | 5         | 3.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.23%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 1.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.23%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 1.23%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.23%   |
| AMD Lucienne                                                                             | 2         | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.23%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.61%   |
| Nvidia TU117M                                                                            | 1         | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.61%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.61%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.61%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 60.84%  |
| 1 x AMD        | 25        | 17.48%  |
| 1 x Nvidia     | 14        | 9.79%   |
| Intel + Nvidia | 7         | 4.9%    |
| Intel + AMD    | 4         | 2.8%    |
| 2 x AMD        | 2         | 1.4%    |
| AMD + Nvidia   | 2         | 1.4%    |
| 1 x VIA        | 1         | 0.7%    |
| 1 x SiS        | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 129       | 89.58%  |
| Proprietary | 12        | 8.33%   |
| Unknown     | 3         | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 66.67%  |
| 1.01-2.0   | 14        | 9.72%   |
| 0.01-0.5   | 13        | 9.03%   |
| 0.51-1.0   | 10        | 6.94%   |
| 3.01-4.0   | 6         | 4.17%   |
| 7.01-8.0   | 3         | 2.08%   |
| 2.01-3.0   | 2         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 13.7%   |
| BOE                     | 18        | 12.33%  |
| Samsung Electronics     | 15        | 10.27%  |
| LG Display              | 15        | 10.27%  |
| Dell                    | 15        | 10.27%  |
| Chimei Innolux          | 14        | 9.59%   |
| Hewlett-Packard         | 7         | 4.79%   |
| Chi Mei Optoelectronics | 5         | 3.42%   |
| AOC                     | 5         | 3.42%   |
| Apple                   | 4         | 2.74%   |
| Sony                    | 3         | 2.05%   |
| Acer                    | 3         | 2.05%   |
| Goldstar                | 2         | 1.37%   |
| ZTR                     | 1         | 0.68%   |
| Westinghouse            | 1         | 0.68%   |
| Vizio                   | 1         | 0.68%   |
| ViewSonic               | 1         | 0.68%   |
| Unknown (XXX)           | 1         | 0.68%   |
| Sharp                   | 1         | 0.68%   |
| Philips                 | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| Panasonic               | 1         | 0.68%   |
| NEC Computers           | 1         | 0.68%   |
| LG Philips              | 1         | 0.68%   |
| LG Electronics          | 1         | 0.68%   |
| Lenovo                  | 1         | 0.68%   |
| KTC                     | 1         | 0.68%   |
| KDC                     | 1         | 0.68%   |
| InnoLux Display         | 1         | 0.68%   |
| InfoVision              | 1         | 0.68%   |
| CHR                     | 1         | 0.68%   |
| BenQ                    | 1         | 0.68%   |
| Ancor Communications    | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 3         | 2.03%   |
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                           | 2         | 1.35%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 2         | 1.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch           | 2         | 1.35%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                        | 2         | 1.35%   |
| ZTR LCD Monitor ZTR0001 1366x768 309x173mm 13.9-inch                    | 1         | 0.68%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch            | 1         | 0.68%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.68%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.68%   |
| Unknown (XXX) Philco XXX0030 1600x1200 708x398mm 32.0-inch              | 1         | 0.68%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                           | 1         | 0.68%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch                 | 1         | 0.68%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch    | 1         | 0.68%   |
| Philips 32 LCD TV PHL4650 1280x1024 760x450mm 34.8-inch                 | 1         | 0.68%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch                 | 1         | 0.68%   |
| Panasonic TV MEI0206 1920x1080                                          | 1         | 0.68%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch            | 1         | 0.68%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch             | 1         | 0.68%   |
| LG Electronics LCD Monitor W1943 1984x768                               | 1         | 0.68%   |
| LG Electronics LCD Monitor LG TV                                        | 1         | 0.68%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch             | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 51        | 36.43%  |
| 1920x1080 (FHD)    | 44        | 31.43%  |
| 1600x900 (HD+)     | 8         | 5.71%   |
| 1280x800 (WXGA)    | 7         | 5%      |
| 1280x1024 (SXGA)   | 7         | 5%      |
| 1680x1050 (WSXGA+) | 5         | 3.57%   |
| 3840x2160 (4K)     | 3         | 2.14%   |
| 1360x768           | 3         | 2.14%   |
| 2560x1440 (QHD)    | 2         | 1.43%   |
| 1440x900 (WXGA+)   | 2         | 1.43%   |
| 1024x768 (XGA)     | 2         | 1.43%   |
| 3840x1100          | 1         | 0.71%   |
| 1984x768           | 1         | 0.71%   |
| 1800x1200          | 1         | 0.71%   |
| 1280x768           | 1         | 0.71%   |
| 1024x600           | 1         | 0.71%   |
| Unknown            | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 32.19%  |
| 13      | 20        | 13.7%   |
| 14      | 14        | 9.59%   |
| 17      | 9         | 6.16%   |
| 11      | 8         | 5.48%   |
| 22      | 6         | 4.11%   |
| 21      | 6         | 4.11%   |
| 19      | 6         | 4.11%   |
| 24      | 5         | 3.42%   |
| 27      | 4         | 2.74%   |
| Unknown | 4         | 2.74%   |
| 18      | 3         | 2.05%   |
| 50      | 2         | 1.37%   |
| 32      | 2         | 1.37%   |
| 10      | 2         | 1.37%   |
| 84      | 1         | 0.68%   |
| 72      | 1         | 0.68%   |
| 41      | 1         | 0.68%   |
| 40      | 1         | 0.68%   |
| 34      | 1         | 0.68%   |
| 31      | 1         | 0.68%   |
| 23      | 1         | 0.68%   |
| 20      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 73        | 51.05%  |
| 401-500     | 20        | 13.99%  |
| 201-300     | 19        | 13.29%  |
| 501-600     | 10        | 6.99%   |
| 351-400     | 7         | 4.9%    |
| Unknown     | 4         | 2.8%    |
| 701-800     | 3         | 2.1%    |
| 1501-2000   | 2         | 1.4%    |
| 1001-1500   | 2         | 1.4%    |
| 801-900     | 1         | 0.7%    |
| 601-700     | 1         | 0.7%    |
| 901-1000    | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 78.03%  |
| 16/10   | 16        | 12.12%  |
| 5/4     | 7         | 5.3%    |
| Unknown | 3         | 2.27%   |
| 4/3     | 1         | 0.76%   |
| 3/2     | 1         | 0.76%   |
| 3.40    | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 32.19%  |
| 81-90          | 27        | 18.49%  |
| 201-250        | 13        | 8.9%    |
| 151-200        | 11        | 7.53%   |
| 51-60          | 9         | 6.16%   |
| 141-150        | 9         | 6.16%   |
| 71-80          | 6         | 4.11%   |
| More than 1000 | 4         | 2.74%   |
| 301-350        | 4         | 2.74%   |
| Unknown        | 4         | 2.74%   |
| 351-500        | 3         | 2.05%   |
| 121-130        | 3         | 2.05%   |
| 501-1000       | 3         | 2.05%   |
| 41-50          | 2         | 1.37%   |
| 251-300        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 54        | 38.03%  |
| 51-100        | 40        | 28.17%  |
| 121-160       | 33        | 23.24%  |
| 1-50          | 6         | 4.23%   |
| 161-240       | 4         | 2.82%   |
| Unknown       | 4         | 2.82%   |
| More than 240 | 1         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 117       | 80.69%  |
| 2     | 20        | 13.79%  |
| 0     | 7         | 4.83%   |
| 3     | 1         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 70        | 32.41%  |
| Intel                           | 66        | 30.56%  |
| Qualcomm Atheros                | 31        | 14.35%  |
| Broadcom                        | 20        | 9.26%   |
| Ralink Technology               | 8         | 3.7%    |
| Qualcomm Atheros Communications | 3         | 1.39%   |
| Broadcom Limited                | 3         | 1.39%   |
| Marvell Technology Group        | 2         | 0.93%   |
| Linksys                         | 2         | 0.93%   |
| Lenovo                          | 2         | 0.93%   |
| VIA Technologies                | 1         | 0.46%   |
| Tul Corporation / PowerColor    | 1         | 0.46%   |
| TP-Link                         | 1         | 0.46%   |
| Nvidia                          | 1         | 0.46%   |
| MediaTek                        | 1         | 0.46%   |
| JCM                             | 1         | 0.46%   |
| HTC (High Tech Computer)        | 1         | 0.46%   |
| Dell                            | 1         | 0.46%   |
| AMD                             | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 15.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 5.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.7%    |
| Ralink MT7601U Wireless Adapter                                   | 6         | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.93%   |
| Intel Wireless 7260                                               | 5         | 1.93%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.54%   |
| Intel Wireless 3165                                               | 4         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.16%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.16%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.77%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.77%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.77%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.77%   |
| Intel Wireless 7265                                               | 2         | 0.77%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.77%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.77%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.77%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 37.5%   |
| Realtek Semiconductor           | 25        | 19.53%  |
| Qualcomm Atheros                | 25        | 19.53%  |
| Broadcom                        | 13        | 10.16%  |
| Ralink Technology               | 8         | 6.25%   |
| Qualcomm Atheros Communications | 3         | 2.34%   |
| Linksys                         | 2         | 1.56%   |
| TP-Link                         | 1         | 0.78%   |
| MediaTek                        | 1         | 0.78%   |
| Dell                            | 1         | 0.78%   |
| Broadcom Limited                | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 6.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 5.43%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 4.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.88%   |
| Intel Wireless 7260                                            | 5         | 3.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 3.1%    |
| Intel Wireless 3165                                            | 4         | 3.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.33%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 2.33%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.33%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.55%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 1.55%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.55%   |
| Intel Wireless 7265                                            | 2         | 1.55%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.55%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.55%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.78%   |
| Realtek 802.11ac NIC                                           | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 46.46%  |
| Intel                    | 41        | 32.28%  |
| Broadcom                 | 10        | 7.87%   |
| Qualcomm Atheros         | 8         | 6.3%    |
| Marvell Technology Group | 2         | 1.57%   |
| Lenovo                   | 2         | 1.57%   |
| Broadcom Limited         | 2         | 1.57%   |
| VIA Technologies         | 1         | 0.79%   |
| Nvidia                   | 1         | 0.79%   |
| HTC (High Tech Computer) | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 32.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 11.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 10.24%  |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.94%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 3.15%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.57%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.57%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.57%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.79%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.79%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.79%   |
| Intel 82562V 10/100 Network Connection                            | 1         | 0.79%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1         | 0.79%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.79%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 49.59%  |
| WiFi     | 120       | 49.18%  |
| Modem    | 2         | 0.82%   |
| Unknown  | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 63.27%  |
| Ethernet | 54        | 36.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 86        | 60.14%  |
| 1     | 52        | 36.36%  |
| 0     | 5         | 3.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 94.52%  |
| Yes  | 8         | 5.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 38.27%  |
| Qualcomm Atheros Communications | 13        | 16.05%  |
| IMC Networks                    | 8         | 9.88%   |
| Dell                            | 6         | 7.41%   |
| Cambridge Silicon Radio         | 6         | 7.41%   |
| Realtek Semiconductor           | 5         | 6.17%   |
| Apple                           | 4         | 4.94%   |
| Broadcom                        | 3         | 3.7%    |
| Lite-On Technology              | 2         | 2.47%   |
| Hewlett-Packard                 | 1         | 1.23%   |
| Dynex                           | 1         | 1.23%   |
| ASUSTek Computer                | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 16        | 19.75%  |
| Qualcomm Atheros  Bluetooth Device                       | 8         | 9.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 6         | 7.41%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5         | 6.17%   |
| IMC Networks Bluetooth Radio                             | 5         | 6.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 3         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 3.7%    |
| Dell BCM20702A0 Bluetooth Module                         | 3         | 3.7%    |
| Apple Bluetooth Host Controller                          | 3         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                           | 2         | 2.47%   |
| Realtek Bluetooth Radio                                  | 2         | 2.47%   |
| Intel AX201 Bluetooth                                    | 2         | 2.47%   |
| Intel AX200 Bluetooth                                    | 2         | 2.47%   |
| Realtek RTL8723B Bluetooth                               | 1         | 1.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 1.23%   |
| Lite-On Wireless_Device                                  | 1         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 1.23%   |
| IMC Networks Bluetooth Device                            | 1         | 1.23%   |
| IMC Networks Bluetooth                                   | 1         | 1.23%   |
| IMC Networks BCM20702A0                                  | 1         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 1.23%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 1.23%   |
| Dell Wireless 360 Bluetooth                              | 1         | 1.23%   |
| Dell Wireless 355 Bluetooth                              | 1         | 1.23%   |
| Dell Wireless 350 Bluetooth                              | 1         | 1.23%   |
| Broadcom HP Portable SoftSailing                         | 1         | 1.23%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 1.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1         | 1.23%   |
| Apple Bluetooth HCI                                      | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 108       | 63.16%  |
| AMD                              | 32        | 18.71%  |
| Nvidia                           | 18        | 10.53%  |
| Logitech                         | 4         | 2.34%   |
| C-Media Electronics              | 2         | 1.17%   |
| VIA Technologies                 | 1         | 0.58%   |
| Sony                             | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| JMTek                            | 1         | 0.58%   |
| Creative Labs                    | 1         | 0.58%   |
| Blue Microphones                 | 1         | 0.58%   |
| BigBen Interactive               | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 7.73%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 6.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 5.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 4.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 4.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 3.38%   |
| AMD FCH Azalia Controller                                                  | 7         | 3.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 2.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 2.42%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.97%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2         | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 0.97%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 0.48%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.48%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 27        | 27.55%  |
| Samsung Electronics | 23        | 23.47%  |
| Micron Technology   | 9         | 9.18%   |
| Unknown             | 6         | 6.12%   |
| Kingston            | 6         | 6.12%   |
| Crucial             | 5         | 5.1%    |
| Unknown (ABCD)      | 3         | 3.06%   |
| Ramaxel Technology  | 3         | 3.06%   |
| Nanya Technology    | 3         | 3.06%   |
| Corsair             | 3         | 3.06%   |
| A-DATA Technology   | 2         | 2.04%   |
| V-Color             | 1         | 1.02%   |
| Sesame              | 1         | 1.02%   |
| Qimonda             | 1         | 1.02%   |
| Patriot             | 1         | 1.02%   |
| G.Skill             | 1         | 1.02%   |
| Elpida              | 1         | 1.02%   |
| Avant               | 1         | 1.02%   |
| Unknown             | 1         | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 2.91%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 1.94%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.94%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.94%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.94%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 2         | 1.94%   |
| V-Color RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s              | 1         | 0.97%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.97%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.97%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.97%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.97%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.97%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.97%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 0.97%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.97%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 1331MT/s              | 1         | 0.97%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.97%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s             | 1         | 0.97%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 0.97%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.97%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.97%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.97%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.97%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.97%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 2667MT/s                | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 37.33%  |
| DDR4    | 27        | 36%     |
| SDRAM   | 7         | 9.33%   |
| LPDDR4  | 6         | 8%      |
| DDR2    | 3         | 4%      |
| Unknown | 2         | 2.67%   |
| LPDDR3  | 1         | 1.33%   |
| DDR     | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 66.67%  |
| DIMM         | 21        | 29.17%  |
| Row Of Chips | 3         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 30        | 37.04%  |
| 8192  | 25        | 30.86%  |
| 2048  | 16        | 19.75%  |
| 16384 | 7         | 8.64%   |
| 1024  | 2         | 2.47%   |
| 512   | 1         | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 23.86%  |
| 1333    | 11        | 12.5%   |
| 2667    | 10        | 11.36%  |
| 2400    | 10        | 11.36%  |
| 2133    | 6         | 6.82%   |
| 3200    | 4         | 4.55%   |
| 1334    | 3         | 3.41%   |
| 4199    | 2         | 2.27%   |
| 3266    | 2         | 2.27%   |
| 2933    | 2         | 2.27%   |
| 1867    | 2         | 2.27%   |
| 1067    | 2         | 2.27%   |
| 667     | 2         | 2.27%   |
| 49926   | 1         | 1.14%   |
| 4267    | 1         | 1.14%   |
| 3600    | 1         | 1.14%   |
| 2934    | 1         | 1.14%   |
| 2666    | 1         | 1.14%   |
| 2048    | 1         | 1.14%   |
| 1648    | 1         | 1.14%   |
| 1331    | 1         | 1.14%   |
| 975     | 1         | 1.14%   |
| 533     | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 16        | 17.2%   |
| Microdia                               | 12        | 12.9%   |
| Sunplus Innovation Technology          | 8         | 8.6%    |
| IMC Networks                           | 7         | 7.53%   |
| Suyin                                  | 6         | 6.45%   |
| Realtek Semiconductor                  | 6         | 6.45%   |
| Apple                                  | 5         | 5.38%   |
| Syntek                                 | 4         | 4.3%    |
| Silicon Motion                         | 3         | 3.23%   |
| Ricoh                                  | 3         | 3.23%   |
| OmniVision Technologies                | 3         | 3.23%   |
| Microsoft                              | 3         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.23%   |
| Quanta                                 | 2         | 2.15%   |
| Primax Electronics                     | 2         | 2.15%   |
| Logitech                               | 2         | 2.15%   |
| Bison Electronics                      | 2         | 2.15%   |
| Sonix Technology                       | 1         | 1.08%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.08%   |
| Samsung Electronics                    | 1         | 1.08%   |
| Jieli Technology                       | 1         | 1.08%   |
| globaloptics                           | 1         | 1.08%   |
| Alcor Micro                            | 1         | 1.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 5         | 5.38%   |
| Chicony Integrated Camera                                      | 5         | 5.38%   |
| IMC Networks Integrated Camera                                 | 3         | 3.23%   |
| Syntek Lenovo EasyCamera                                       | 2         | 2.15%   |
| Microsoft MicrosoftÂ LifeCam HD-5001                          | 2         | 2.15%   |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 2.15%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.15%   |
| Microdia Integrated Webcam                                     | 2         | 2.15%   |
| Microdia HP Integrated Webcam                                  | 2         | 2.15%   |
| Microdia Dell Integrated HD Webcam                             | 2         | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 2.15%   |
| Chicony USB2.0 HD UVC WebCam                                   | 2         | 2.15%   |
| Chicony Integrated HP HD Webcam                                | 2         | 2.15%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 2.15%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 2.15%   |
| Apple FaceTime HD Camera                                       | 2         | 2.15%   |
| Syntek Integrated Camera                                       | 1         | 1.08%   |
| Syntek EasyCamera                                              | 1         | 1.08%   |
| Suyin VGA Webcam                                               | 1         | 1.08%   |
| Suyin TOSHIBA Web Camera - HD                                  | 1         | 1.08%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 1.08%   |
| Suyin HP TrueVision HD                                         | 1         | 1.08%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 1.08%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.08%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 1.08%   |
| Sonix HP Webcam-101                                            | 1         | 1.08%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 1.08%   |
| Silicon Motion WebCam SC-10HDD13335N                           | 1         | 1.08%   |
| Silicon Motion Real HD WebCam                                  | 1         | 1.08%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 1.08%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 1.08%   |
| Ricoh Laptop_Integrated_Webcam_FHD                             | 1         | 1.08%   |
| Ricoh Integrated Webcam                                        | 1         | 1.08%   |
| Ricoh HD Webcam                                                | 1         | 1.08%   |
| Realtek USB2.0 camera                                          | 1         | 1.08%   |
| Realtek Integrated Webcam HD                                   | 1         | 1.08%   |
| Realtek Integrated Webcam                                      | 1         | 1.08%   |
| Realtek Integrated Camera                                      | 1         | 1.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 46.67%  |
| Synaptics                  | 4         | 26.67%  |
| STMicroelectronics         | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| Samsung Electronics        | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 6.67%   |
| Validity Sensors VFS491                           | 1         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                   | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner              | 1         | 6.67%   |
| Synaptics  WBDI                                   | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader             | 1         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 6.67%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 63.64%  |
| O2 Micro    | 2         | 18.18%  |
| Alcor Micro | 2         | 18.18%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 18.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 105       | 72.92%  |
| 1     | 34        | 23.61%  |
| 2     | 5         | 3.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 34.09%  |
| Graphics card         | 10        | 22.73%  |
| Chipcard              | 9         | 20.45%  |
| Storage               | 2         | 4.55%   |
| Net/wireless          | 2         | 4.55%   |
| Multimedia controller | 2         | 4.55%   |
| Network               | 1         | 2.27%   |
| Card reader           | 1         | 2.27%   |
| Camera                | 1         | 2.27%   |
| Bluetooth             | 1         | 2.27%   |


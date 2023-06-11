Linux in Indonesia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Indonesia/Desktop/README.md) and [notebooks](/Location/Indonesia/Notebook/README.md).

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

Total: 1702

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | Notebook    | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | Notebook    | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [b88a90f9d3](https://linux-hardware.org/?probe=b88a90f9d3) | May 25, 2023 |
| Panasonic     | CFSZ5-2                     | Notebook    | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| MSI           | 2A9C                        | Desktop     | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| MSI           | 2A9C                        | Desktop     | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [59902928be](https://linux-hardware.org/?probe=59902928be) | May 18, 2023 |
| ASUSTek       | V241EA                      | All in one  | [e4f05ea74b](https://linux-hardware.org/?probe=e4f05ea74b) | May 16, 2023 |
| Acer          | One Z1402                   | Notebook    | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [6353fe7194](https://linux-hardware.org/?probe=6353fe7194) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | Notebook    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | Notebook    | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [036d26ffb3](https://linux-hardware.org/?probe=036d26ffb3) | May 10, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | Notebook    | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f1537beedf](https://linux-hardware.org/?probe=f1537beedf) | May 01, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| Dell          | Latitude 7300               | Notebook    | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [fc811580c9](https://linux-hardware.org/?probe=fc811580c9) | Apr 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ca58518a03](https://linux-hardware.org/?probe=ca58518a03) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| AZW           | U59                         | Desktop     | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| HP            | Notebook                    | Notebook    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | Notebook    | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| Toshiba       | Satellite L640              | Notebook    | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | Notebook    | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | Notebook    | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | Desktop     | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | Notebook    | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Gigabyte      | P41T-D3                     | Desktop     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | Notebook    | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4b6ecef29b](https://linux-hardware.org/?probe=4b6ecef29b) | Mar 19, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | Notebook    | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | Notebook    | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | Notebook    | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| GALAX         | B550M                       | Desktop     | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | Notebook    | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | Notebook    | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | Notebook    | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | Notebook    | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASRock        | 970A-G                      | Desktop     | [bfdb227a9d](https://linux-hardware.org/?probe=bfdb227a9d) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| ASRock        | A88M-G                      | Desktop     | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | Notebook    | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [e9cfac6aa3](https://linux-hardware.org/?probe=e9cfac6aa3) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | Notebook    | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | Notebook    | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | 198E                        | Desktop     | [7dedbbef80](https://linux-hardware.org/?probe=7dedbbef80) | Feb 04, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | Notebook    | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | 3102 NO DPK                 | Desktop     | [fa7b131a50](https://linux-hardware.org/?probe=fa7b131a50) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Unknown       | Unknown                     | Phone       | [71abbc8c47](https://linux-hardware.org/?probe=71abbc8c47) | Jan 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Intel         | Unknown                     | Desktop     | [6928fe7911](https://linux-hardware.org/?probe=6928fe7911) | Jan 11, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Acer          | TravelMate P214             | Notebook    | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | Notebook    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| ASUSTek       | A4110                       | All in one  | [fa417dc5c7](https://linux-hardware.org/?probe=fa417dc5c7) | Dec 28, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [7b4b133211](https://linux-hardware.org/?probe=7b4b133211) | Dec 27, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [68963cb64b](https://linux-hardware.org/?probe=68963cb64b) | Dec 25, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| MSI           | H61M-P20                    | Desktop     | [07b5fe983c](https://linux-hardware.org/?probe=07b5fe983c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | Desktop     | [e1d50cc8f4](https://linux-hardware.org/?probe=e1d50cc8f4) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | Notebook    | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [00437ce174](https://linux-hardware.org/?probe=00437ce174) | Dec 16, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [d09b578699](https://linux-hardware.org/?probe=d09b578699) | Dec 15, 2022 |
| Acer          | EX-215-52                   | Notebook    | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | Notebook    | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Dell          | 0VC7DK A03                  | Server      | [5e9bc6749d](https://linux-hardware.org/?probe=5e9bc6749d) | Dec 10, 2022 |
| Dell          | 0VC7DK A03                  | Server      | [f7958003c5](https://linux-hardware.org/?probe=f7958003c5) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | Notebook    | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [7bde3abe5d](https://linux-hardware.org/?probe=7bde3abe5d) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | Notebook    | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1cd6da46f3](https://linux-hardware.org/?probe=1cd6da46f3) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | Notebook    | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| Dell          | Latitude 3420               | Notebook    | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [de105b99e4](https://linux-hardware.org/?probe=de105b99e4) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| Lenovo        | B40-70 20392                | Notebook    | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| ASUSTek       | E203NAH                     | Notebook    | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | Notebook    | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | Notebook    | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | Notebook    | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | Notebook    | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| MSI           | H510M PRO                   | Desktop     | [182b91241d](https://linux-hardware.org/?probe=182b91241d) | Nov 20, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | Notebook    | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [f67cd83e31](https://linux-hardware.org/?probe=f67cd83e31) | Nov 14, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | Notebook    | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| MSI           | 2A9C                        | Desktop     | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| MSI           | 2A9C                        | Desktop     | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | Notebook    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | Notebook    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [6331807ba3](https://linux-hardware.org/?probe=6331807ba3) | Nov 07, 2022 |
| Unknown       | Unknown                     | Server      | [3facb2e9a7](https://linux-hardware.org/?probe=3facb2e9a7) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [433a068c09](https://linux-hardware.org/?probe=433a068c09) | Nov 07, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [a3236bc9e8](https://linux-hardware.org/?probe=a3236bc9e8) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [fab16fdb8d](https://linux-hardware.org/?probe=fab16fdb8d) | Nov 07, 2022 |
| Lenovo        | 7Y51CTO1WW                  | Server      | [ce01f7d898](https://linux-hardware.org/?probe=ce01f7d898) | Nov 07, 2022 |
| Lenovo        | 7X04CTO1WW                  | Server      | [8b79ae4568](https://linux-hardware.org/?probe=8b79ae4568) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| Intel         | P61A-D3                     | Desktop     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | Notebook    | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6d5c1da4b7](https://linux-hardware.org/?probe=6d5c1da4b7) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | Convertible | [6e32a194d3](https://linux-hardware.org/?probe=6e32a194d3) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | Notebook    | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [a6eb228e33](https://linux-hardware.org/?probe=a6eb228e33) | Oct 10, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [6f6704ea90](https://linux-hardware.org/?probe=6f6704ea90) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [5e9a9b60e6](https://linux-hardware.org/?probe=5e9a9b60e6) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [4a285e2052](https://linux-hardware.org/?probe=4a285e2052) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| HP            | 198E                        | Desktop     | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| ECS           | A55F2-M4                    | Desktop     | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [fddeb02707](https://linux-hardware.org/?probe=fddeb02707) | Sep 18, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | Notebook    | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | Notebook    | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | Notebook    | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | Notebook    | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [9ac20fda5a](https://linux-hardware.org/?probe=9ac20fda5a) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| HP            | 14                          | Notebook    | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | Notebook    | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | Notebook    | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| Dell          | G3 3579                     | Notebook    | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | Notebook    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| Dell          | 0WCWFJ A00                  | All in one  | [89a6f4711c](https://linux-hardware.org/?probe=89a6f4711c) | Jul 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | Notebook    | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Toshiba       | Satellite C640              | Notebook    | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | Notebook    | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | Notebook    | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | Notebook    | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| MSI           | 2A9C                        | Desktop     | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Acer          | AO756                       | Notebook    | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | Notebook    | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| MSI           | H81I                        | Desktop     | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| ASRock        | A88M-G                      | Desktop     | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | Notebook    | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | Notebook    | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | K43U                        | Notebook    | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | Notebook    | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASRock        | A88M-G                      | Desktop     | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | K43U                        | Notebook    | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | Notebook    | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | Notebook    | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | Desktop     | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [c0bfa1dddf](https://linux-hardware.org/?probe=c0bfa1dddf) | May 06, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | Notebook    | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | Notebook    | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Lenovo        | 36F2 SDK0Q55754 WIN 3273... | All in one  | [64bc773e5b](https://linux-hardware.org/?probe=64bc773e5b) | Mar 30, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | Notebook    | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| Koloe         | X58                         | Desktop     | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | Notebook    | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | Desktop     | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | Notebook    | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| Intel         | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | Notebook    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| ZYREX COMP... | TACTICAL                    | Desktop     | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | Notebook    | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | Notebook    | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | Notebook    | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [3b3c38ec7d](https://linux-hardware.org/?probe=3b3c38ec7d) | Feb 24, 2022 |
| Acer          | Aspire M3970                | Desktop     | [ba6546f689](https://linux-hardware.org/?probe=ba6546f689) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| Dell          | 0GM819                      | Desktop     | [28011d003e](https://linux-hardware.org/?probe=28011d003e) | Feb 23, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | Notebook    | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [1e54431036](https://linux-hardware.org/?probe=1e54431036) | Feb 15, 2022 |
| Fujitsu       | FMVNA1SE                    | Notebook    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Khadas        | VIM2                        | Soc         | [c3e2b43e74](https://linux-hardware.org/?probe=c3e2b43e74) | Feb 13, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [3a6bb92957](https://linux-hardware.org/?probe=3a6bb92957) | Feb 13, 2022 |
| Toshiba       | Satellite C840              | Notebook    | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | Notebook    | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [276233dff5](https://linux-hardware.org/?probe=276233dff5) | Feb 11, 2022 |
| Biostar       | A68MHE                      | Desktop     | [d66f9ea911](https://linux-hardware.org/?probe=d66f9ea911) | Feb 10, 2022 |
| Biostar       | A68MHE                      | Desktop     | [edc710a49e](https://linux-hardware.org/?probe=edc710a49e) | Feb 10, 2022 |
| Toshiba       | Satellite C800D             | Notebook    | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | Notebook    | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | Notebook    | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | Notebook    | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | Notebook    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | Notebook    | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | Notebook    | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | Notebook    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | Notebook    | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | Notebook    | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Biostar       | H81MHV3                     | Desktop     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [af3d4f8c4d](https://linux-hardware.org/?probe=af3d4f8c4d) | Jan 02, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [2956508483](https://linux-hardware.org/?probe=2956508483) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | Notebook    | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [b5cd12bc15](https://linux-hardware.org/?probe=b5cd12bc15) | Dec 24, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [25ca0533b3](https://linux-hardware.org/?probe=25ca0533b3) | Dec 24, 2021 |
| Fujitsu       | FMVNA7BEC                   | Notebook    | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | Notebook    | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | Notebook    | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | UX360UAK                    | Convertible | [76fcef9590](https://linux-hardware.org/?probe=76fcef9590) | Dec 05, 2021 |
| Foxconn       | 17A0                        | Desktop     | [f3b593c1cf](https://linux-hardware.org/?probe=f3b593c1cf) | Dec 04, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | Notebook    | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [473e7afa6d](https://linux-hardware.org/?probe=473e7afa6d) | Dec 01, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Foxconn       | 17A0                        | Desktop     | [9683f8f23c](https://linux-hardware.org/?probe=9683f8f23c) | Nov 29, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | Desktop     | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| HP            | EliteBook x360 830 G7 No... | Convertible | [4c596fa022](https://linux-hardware.org/?probe=4c596fa022) | Nov 24, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [e84acf2bba](https://linux-hardware.org/?probe=e84acf2bba) | Nov 19, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [6d67037961](https://linux-hardware.org/?probe=6d67037961) | Nov 16, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | Notebook    | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| Foxconn       | 17A0                        | Desktop     | [ed1128211e](https://linux-hardware.org/?probe=ed1128211e) | Nov 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | Notebook    | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | Notebook    | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| Foxconn       | 17A0                        | Desktop     | [17ff85bc35](https://linux-hardware.org/?probe=17ff85bc35) | Nov 09, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| HP            | Notebook                    | Notebook    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [a6cafee332](https://linux-hardware.org/?probe=a6cafee332) | Nov 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | Desktop     | [4fa9117126](https://linux-hardware.org/?probe=4fa9117126) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | Desktop     | [e4fc3665f7](https://linux-hardware.org/?probe=e4fc3665f7) | Oct 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [93b56b7543](https://linux-hardware.org/?probe=93b56b7543) | Oct 29, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [e94404d654](https://linux-hardware.org/?probe=e94404d654) | Oct 26, 2021 |
| Dell          | Latitude E6440              | Notebook    | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | Notebook    | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | Notebook    | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Pegatron      | 2AD4                        | Desktop     | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| HPE           | ProLiant DL360 Gen10        | Server      | [7ab4f05613](https://linux-hardware.org/?probe=7ab4f05613) | Oct 18, 2021 |
| Dell          | Inspiron 1440               | Notebook    | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | Notebook    | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [ee1862fa4f](https://linux-hardware.org/?probe=ee1862fa4f) | Oct 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [9d1380f4a8](https://linux-hardware.org/?probe=9d1380f4a8) | Oct 15, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| Dell          | 0773VG A01                  | Desktop     | [84fc704eaa](https://linux-hardware.org/?probe=84fc704eaa) | Oct 09, 2021 |
| ASUSTek       | K43SV                       | Notebook    | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | Notebook    | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| Lenovo        | H310                        | Desktop     | [ce491df5a4](https://linux-hardware.org/?probe=ce491df5a4) | Oct 06, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | Notebook    | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | Notebook    | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [4038d4a0a6](https://linux-hardware.org/?probe=4038d4a0a6) | Sep 29, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [5854a1e114](https://linux-hardware.org/?probe=5854a1e114) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [f8fd88bca1](https://linux-hardware.org/?probe=f8fd88bca1) | Sep 26, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | Notebook    | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Foxconn       | 17A0                        | Desktop     | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [5d60817fb5](https://linux-hardware.org/?probe=5d60817fb5) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| HP            | Convertible x360 11-ab1X... | Convertible | [5863fa858f](https://linux-hardware.org/?probe=5863fa858f) | Sep 07, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | Notebook    | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [541ab60180](https://linux-hardware.org/?probe=541ab60180) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [9ab0b9612a](https://linux-hardware.org/?probe=9ab0b9612a) | Aug 30, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [924e556648](https://linux-hardware.org/?probe=924e556648) | Aug 28, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [83393788bf](https://linux-hardware.org/?probe=83393788bf) | Aug 26, 2021 |
| HP            | ProBook 4430s               | Notebook    | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| Gigabyte      | EP45-DS3                    | Desktop     | [a2a6e3ee32](https://linux-hardware.org/?probe=a2a6e3ee32) | Aug 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| ECS           | A960M-MV                    | Desktop     | [684f50eff8](https://linux-hardware.org/?probe=684f50eff8) | Aug 18, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| HP            | 2B3C                        | Desktop     | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | Notebook    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2aa00ea596](https://linux-hardware.org/?probe=2aa00ea596) | Aug 15, 2021 |
| Toshiba       | Satellite R630              | Notebook    | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [2da83ae7b5](https://linux-hardware.org/?probe=2da83ae7b5) | Aug 12, 2021 |
| HP            | ENVY Notebook               | Notebook    | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | Notebook    | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [557e4010c3](https://linux-hardware.org/?probe=557e4010c3) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | Notebook    | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6a935239e8](https://linux-hardware.org/?probe=6a935239e8) | Aug 05, 2021 |
| ASUSTek       | X455YA                      | Notebook    | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | Notebook    | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | Notebook    | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [b4a1e99fc0](https://linux-hardware.org/?probe=b4a1e99fc0) | Jul 28, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [cc1c71078c](https://linux-hardware.org/?probe=cc1c71078c) | Jul 28, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [20dc9f0df4](https://linux-hardware.org/?probe=20dc9f0df4) | Jul 27, 2021 |
| Dell          | Inspiron 3458               | Notebook    | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [85fddcd068](https://linux-hardware.org/?probe=85fddcd068) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Acer          | Veriton L4630G V:1.0        | Desktop     | [c486fbf03f](https://linux-hardware.org/?probe=c486fbf03f) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | Notebook    | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c989b48f08](https://linux-hardware.org/?probe=c989b48f08) | Jul 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fec68f6675](https://linux-hardware.org/?probe=fec68f6675) | Jul 23, 2021 |
| ECS           | G41T-M12                    | Desktop     | [bc6dbc46b6](https://linux-hardware.org/?probe=bc6dbc46b6) | Jul 23, 2021 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Biostar       | H61MH                       | Desktop     | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | Desktop     | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | Notebook    | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [7f0ce9114c](https://linux-hardware.org/?probe=7f0ce9114c) | Jul 21, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | Notebook    | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | Notebook    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | Desktop     | [533da05156](https://linux-hardware.org/?probe=533da05156) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [e336800a84](https://linux-hardware.org/?probe=e336800a84) | Jul 10, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [bdce45de75](https://linux-hardware.org/?probe=bdce45de75) | Jul 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9765ba93ab](https://linux-hardware.org/?probe=9765ba93ab) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | Notebook    | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [064817cd28](https://linux-hardware.org/?probe=064817cd28) | Jul 05, 2021 |
| ASUSTek       | K84L                        | Notebook    | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | Notebook    | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | Notebook    | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| MSI           | 870A-G54                    | Desktop     | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Biostar       | TA870+                      | Desktop     | [c86568a140](https://linux-hardware.org/?probe=c86568a140) | Jun 09, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a3cef73da9](https://linux-hardware.org/?probe=a3cef73da9) | Jun 09, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | Desktop     | [414008f0a3](https://linux-hardware.org/?probe=414008f0a3) | Jun 08, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | Desktop     | [744392b18f](https://linux-hardware.org/?probe=744392b18f) | Jun 08, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| HP            | 85A2                        | All in one  | [f0691e6eda](https://linux-hardware.org/?probe=f0691e6eda) | Jun 02, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [0a074f7196](https://linux-hardware.org/?probe=0a074f7196) | Jun 02, 2021 |
| HP            | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | Notebook    | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| ECS           | G41T-M12                    | Desktop     | [086ce490f7](https://linux-hardware.org/?probe=086ce490f7) | May 29, 2021 |
| ECS           | A55F2-M4                    | Desktop     | [b08197df02](https://linux-hardware.org/?probe=b08197df02) | May 29, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| Gigabyte      | P85-D3                      | Desktop     | [a85613d8a6](https://linux-hardware.org/?probe=a85613d8a6) | May 24, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [c75161deac](https://linux-hardware.org/?probe=c75161deac) | May 20, 2021 |
| ASUSTek       | X550JX                      | Notebook    | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [8f39af876c](https://linux-hardware.org/?probe=8f39af876c) | May 19, 2021 |
| Acer          | Okinawa                     | Notebook    | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | Notebook    | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [80070c566e](https://linux-hardware.org/?probe=80070c566e) | May 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [f900105a8a](https://linux-hardware.org/?probe=f900105a8a) | May 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Acer          | Veriton M2611 v1.0          | Desktop     | [82b2ea1868](https://linux-hardware.org/?probe=82b2ea1868) | May 06, 2021 |
| Acer          | Veriton M2611 v1.0          | Desktop     | [218de62b27](https://linux-hardware.org/?probe=218de62b27) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [327d214403](https://linux-hardware.org/?probe=327d214403) | May 04, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | Notebook    | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| ECS           | 945GCT-M2                   | Desktop     | [3f73514b16](https://linux-hardware.org/?probe=3f73514b16) | Apr 26, 2021 |
| ECS           | 945GCT-M2                   | Desktop     | [289b6cba53](https://linux-hardware.org/?probe=289b6cba53) | Apr 25, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | Notebook    | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | Notebook    | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [ca62d8f11b](https://linux-hardware.org/?probe=ca62d8f11b) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f71c55764e](https://linux-hardware.org/?probe=f71c55764e) | Apr 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [2352caa9cf](https://linux-hardware.org/?probe=2352caa9cf) | Apr 19, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [47d0215e94](https://linux-hardware.org/?probe=47d0215e94) | Apr 17, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 160       | 12.64%  |
| Ubuntu 18.04        | 104       | 8.21%   |
| OpenMandriva 4.3    | 58        | 4.58%   |
| Ubuntu 22.04        | 57        | 4.5%    |
| OpenMandriva 4.2    | 32        | 2.53%   |
| Arch Rolling        | 28        | 2.21%   |
| KDE neon 20.04      | 26        | 2.05%   |
| Zorin 15            | 23        | 1.82%   |
| Arch                | 22        | 1.74%   |
| Fedora 36           | 21        | 1.66%   |
| Pop!_OS 22.04       | 19        | 1.5%    |
| Pop!_OS 20.04       | 18        | 1.42%   |
| Manjaro             | 18        | 1.42%   |
| Elementary 6.1      | 18        | 1.42%   |
| ArcoLinux Rolling   | 18        | 1.42%   |
| Debian 11           | 17        | 1.34%   |
| Ubuntu 21.10        | 16        | 1.26%   |
| Fedora 35           | 16        | 1.26%   |
| Ubuntu 19.10        | 15        | 1.18%   |
| Linux Mint 20.3     | 15        | 1.18%   |
| Zorin 16            | 14        | 1.11%   |
| OpenMandriva 23.03  | 14        | 1.11%   |
| Linux Mint 19.3     | 14        | 1.11%   |
| Fedora 37           | 14        | 1.11%   |
| Xubuntu 20.04       | 13        | 1.03%   |
| OpenMandriva 23.01  | 13        | 1.03%   |
| Debian 10           | 11        | 0.87%   |
| Linux Mint 21.1     | 10        | 0.79%   |
| Linux Mint 20       | 10        | 0.79%   |
| Fedora 32           | 10        | 0.79%   |
| Ubuntu 16.04        | 9         | 0.71%   |
| Pop!_OS 21.04       | 9         | 0.71%   |
| Kubuntu 22.04       | 9         | 0.71%   |
| Kubuntu 20.04       | 9         | 0.71%   |
| Fedora 33           | 9         | 0.71%   |
| EndeavourOS Rolling | 9         | 0.71%   |
| Ubuntu 21.04        | 8         | 0.63%   |
| Linux Mint 21       | 8         | 0.63%   |
| Linux Mint 20.2     | 8         | 0.63%   |
| Fedora 34           | 8         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 376       | 31.31%  |
| OpenMandriva  | 115       | 9.58%   |
| Fedora        | 75        | 6.24%   |
| Linux Mint    | 69        | 5.75%   |
| Pop!_OS       | 52        | 4.33%   |
| Arch          | 50        | 4.16%   |
| Manjaro       | 47        | 3.91%   |
| Zorin         | 41        | 3.41%   |
| Elementary    | 37        | 3.08%   |
| Endless       | 33        | 2.75%   |
| KDE neon      | 31        | 2.58%   |
| Debian        | 31        | 2.58%   |
| Xubuntu       | 27        | 2.25%   |
| Kubuntu       | 27        | 2.25%   |
| Kali          | 24        | 2%      |
| ArcoLinux     | 19        | 1.58%   |
| ROSA          | 14        | 1.17%   |
| Lubuntu       | 14        | 1.17%   |
| Ubuntu Unity  | 9         | 0.75%   |
| EndeavourOS   | 9         | 0.75%   |
| Ubuntu MATE   | 8         | 0.67%   |
| openSUSE      | 8         | 0.67%   |
| Clear Linux   | 8         | 0.67%   |
| Parrot        | 5         | 0.42%   |
| LMDE          | 5         | 0.42%   |
| Deepin        | 5         | 0.42%   |
| Android       | 5         | 0.42%   |
| Sparky        | 4         | 0.33%   |
| Nobara        | 4         | 0.33%   |
| MX            | 4         | 0.33%   |
| CentOS        | 4         | 0.33%   |
| Artix         | 4         | 0.33%   |
| Ubuntu Budgie | 3         | 0.25%   |
| Gentoo        | 3         | 0.25%   |
| UbuntuDDE     | 2         | 0.17%   |
| SteamOS       | 2         | 0.17%   |
| Solus         | 2         | 0.17%   |
| Rocky Linux   | 2         | 0.17%   |
| RHEL          | 2         | 0.17%   |
| Devuan        | 2         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 57        | 4.22%   |
| 5.10.14-desktop-1omv4002 | 29        | 2.15%   |
| 5.4.0-42-generic         | 27        | 2%      |
| 5.15.0-56-generic        | 22        | 1.63%   |
| 5.4.0-26-generic         | 17        | 1.26%   |
| 5.4.0-52-generic         | 16        | 1.19%   |
| 5.4.0-58-generic         | 15        | 1.11%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.96%   |
| 4.18.0-15-generic        | 12        | 0.89%   |
| 6.1.1-desktop-1omv2290   | 11        | 0.81%   |
| 5.0.0-25-generic         | 11        | 0.81%   |
| 5.15.0-48-generic        | 10        | 0.74%   |
| 5.15.0-46-generic        | 10        | 0.74%   |
| 5.15.0-43-generic        | 10        | 0.74%   |
| 5.15.0-41-generic        | 10        | 0.74%   |
| 5.4.0-80-generic         | 9         | 0.67%   |
| 5.11.0-37-generic        | 9         | 0.67%   |
| 5.4.0-54-generic         | 8         | 0.59%   |
| 5.3.0-46-generic         | 8         | 0.59%   |
| 5.3.0-40-generic         | 8         | 0.59%   |
| 5.15.0-47-generic        | 8         | 0.59%   |
| 5.8.0-48-generic         | 7         | 0.52%   |
| 5.8.0-14-generic         | 7         | 0.52%   |
| 5.19.0-35-generic        | 7         | 0.52%   |
| 5.15.0-58-generic        | 7         | 0.52%   |
| 5.15.0-52-generic        | 7         | 0.52%   |
| 5.11.0-43-generic        | 7         | 0.52%   |
| 5.11.0-40-generic        | 7         | 0.52%   |
| 5.11.0-27-generic        | 7         | 0.52%   |
| 5.4.0-33-generic         | 6         | 0.44%   |
| 5.11.0-7620-generic      | 6         | 0.44%   |
| 5.11.0-38-generic        | 6         | 0.44%   |
| 5.11.0-35-generic        | 6         | 0.44%   |
| 5.0.0-32-generic         | 6         | 0.44%   |
| 5.0.0-23-generic         | 6         | 0.44%   |
| 5.8.0-41-generic         | 5         | 0.37%   |
| 5.4.0-81-generic         | 5         | 0.37%   |
| 5.4.0-65-generic         | 5         | 0.37%   |
| 5.4.0-48-generic         | 5         | 0.37%   |
| 5.4.0-45-generic         | 5         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 204       | 15.68%  |
| 5.15.0  | 119       | 9.15%   |
| 5.11.0  | 72        | 5.53%   |
| 5.8.0   | 61        | 4.69%   |
| 5.16.7  | 59        | 4.53%   |
| 4.15.0  | 55        | 4.23%   |
| 5.13.0  | 52        | 4%      |
| 5.3.0   | 51        | 3.92%   |
| 5.0.0   | 44        | 3.38%   |
| 4.18.0  | 32        | 2.46%   |
| 5.10.14 | 30        | 2.31%   |
| 5.10.0  | 29        | 2.23%   |
| 5.19.0  | 25        | 1.92%   |
| 6.1.1   | 17        | 1.31%   |
| 6.2.6   | 16        | 1.23%   |
| 4.19.0  | 15        | 1.15%   |
| 5.17.5  | 8         | 0.61%   |
| 5.14.0  | 8         | 0.61%   |
| 4.4.0   | 7         | 0.54%   |
| 6.2.0   | 6         | 0.46%   |
| 6.1.0   | 6         | 0.46%   |
| 5.16.0  | 6         | 0.46%   |
| 5.9.16  | 5         | 0.38%   |
| 5.16.12 | 5         | 0.38%   |
| 6.2.9   | 4         | 0.31%   |
| 6.2.8   | 4         | 0.31%   |
| 6.0.9   | 4         | 0.31%   |
| 6.0.6   | 4         | 0.31%   |
| 6.0.12  | 4         | 0.31%   |
| 6.0.10  | 4         | 0.31%   |
| 6.0.0   | 4         | 0.31%   |
| 5.8.12  | 4         | 0.31%   |
| 5.18.0  | 4         | 0.31%   |
| 5.15.12 | 4         | 0.31%   |
| 5.14.16 | 4         | 0.31%   |
| 5.11.11 | 4         | 0.31%   |
| 4.9.20  | 4         | 0.31%   |
| 6.3.5   | 3         | 0.23%   |
| 6.3.3   | 3         | 0.23%   |
| 6.1.6   | 3         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 5.4       | 214       | 16.68%  |
| 5.15      | 146       | 11.38%  |
| 5.10      | 97        | 7.56%   |
| 5.16      | 81        | 6.31%   |
| 5.11      | 81        | 6.31%   |
| 5.8       | 76        | 5.92%   |
| 5.13      | 60        | 4.68%   |
| 5.3       | 55        | 4.29%   |
| 4.15      | 55        | 4.29%   |
| 5.0       | 46        | 3.59%   |
| 6.1       | 41        | 3.2%    |
| 5.19      | 40        | 3.12%   |
| 6.2       | 37        | 2.88%   |
| 4.18      | 35        | 2.73%   |
| 6.0       | 31        | 2.42%   |
| 5.14      | 24        | 1.87%   |
| 5.17      | 22        | 1.71%   |
| 4.19      | 20        | 1.56%   |
| 5.18      | 19        | 1.48%   |
| 5.9       | 16        | 1.25%   |
| 5.12      | 12        | 0.94%   |
| 4.9       | 11        | 0.86%   |
| 6.3       | 10        | 0.78%   |
| 5.7       | 10        | 0.78%   |
| 5.6       | 10        | 0.78%   |
| 4.4       | 9         | 0.7%    |
| 5.5       | 6         | 0.47%   |
| 5.2       | 3         | 0.23%   |
| 4.13      | 3         | 0.23%   |
| 4.14      | 2         | 0.16%   |
| 4.10      | 2         | 0.16%   |
| 4.1       | 2         | 0.16%   |
| 5.1       | 1         | 0.08%   |
| 5         | 1         | 0.08%   |
| 4.3       | 1         | 0.08%   |
| 4.17      | 1         | 0.08%   |
| 4.14.194  | 1         | 0.08%   |
| 3.16      | 1         | 0.08%   |
| 3.10      | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1125      | 96.73%  |
| i686    | 29        | 2.49%   |
| aarch64 | 4         | 0.34%   |
| armv8l  | 3         | 0.26%   |
| armv7l  | 2         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 502       | 41.83%  |
| KDE5              | 224       | 18.67%  |
| Unknown           | 141       | 11.75%  |
| XFCE              | 93        | 7.75%   |
| X-Cinnamon        | 61        | 5.08%   |
| Pantheon          | 35        | 2.92%   |
| MATE              | 25        | 2.08%   |
| KDE               | 22        | 1.83%   |
| LXQt              | 17        | 1.42%   |
| Cinnamon          | 14        | 1.17%   |
| Unity             | 9         | 0.75%   |
| Deepin            | 8         | 0.67%   |
| Budgie            | 7         | 0.58%   |
| KDE4              | 5         | 0.42%   |
| i3                | 4         | 0.33%   |
| GNOME Flashback   | 4         | 0.33%   |
| sway              | 3         | 0.25%   |
| ICEWM             | 3         | 0.25%   |
| Hyprland          | 3         | 0.25%   |
| DWM               | 3         | 0.25%   |
| Cutefish          | 3         | 0.25%   |
| Bspwm             | 3         | 0.25%   |
| xmonad            | 2         | 0.17%   |
| qtile             | 2         | 0.17%   |
| Yaru:ubuntu:GNOME | 1         | 0.08%   |
| Peux Gnome        | 1         | 0.08%   |
| openbox           | 1         | 0.08%   |
| LXDE              | 1         | 0.08%   |
| Lubuntu           | 1         | 0.08%   |
| lightdm-xsession  | 1         | 0.08%   |
| awesomeminimal    | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 907       | 76.28%  |
| Wayland | 171       | 14.38%  |
| Unknown | 96        | 8.07%   |
| Tty     | 15        | 1.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 573       | 47.71%  |
| SDDM    | 216       | 17.99%  |
| GDM     | 155       | 12.91%  |
| LightDM | 110       | 9.16%   |
| GDM3    | 100       | 8.33%   |
| TDM     | 37        | 3.08%   |
| KDM     | 5         | 0.42%   |
| SLiM    | 3         | 0.25%   |
| Ly      | 1         | 0.08%   |
| LXDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 937       | 79.41%  |
| Unknown | 123       | 10.42%  |
| id_ID   | 78        | 6.61%   |
| C       | 13        | 1.1%    |
| en_GB   | 12        | 1.02%   |
| en_AG   | 4         | 0.34%   |
| en_SG   | 3         | 0.25%   |
| en_AU   | 2         | 0.17%   |
| jv_ID   | 1         | 0.08%   |
| it_IT   | 1         | 0.08%   |
| fr_FR   | 1         | 0.08%   |
| en_IN   | 1         | 0.08%   |
| en_CA   | 1         | 0.08%   |
| de_DE   | 1         | 0.08%   |
| de_CH   | 1         | 0.08%   |
| Default | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 626       | 52.69%  |
| BIOS | 562       | 47.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 918       | 77.6%   |
| Btrfs   | 97        | 8.2%    |
| Overlay | 94        | 7.95%   |
| Unknown | 45        | 3.8%    |
| Xfs     | 13        | 1.1%    |
| Zfs     | 5         | 0.42%   |
| Ext2    | 5         | 0.42%   |
| F2fs    | 3         | 0.25%   |
| Ext3    | 2         | 0.17%   |
| Tmpfs   | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 588       | 49.54%  |
| GPT     | 437       | 36.82%  |
| MBR     | 162       | 13.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1028      | 87.04%  |
| Yes       | 153       | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 685       | 57.81%  |
| Yes       | 500       | 42.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 242       | 20.81%  |
| ASUSTek Computer        | 232       | 19.95%  |
| Hewlett-Packard         | 147       | 12.64%  |
| Acer                    | 126       | 10.83%  |
| Dell                    | 88        | 7.57%   |
| MSI                     | 53        | 4.56%   |
| Gigabyte Technology     | 43        | 3.7%    |
| ASRock                  | 36        | 3.1%    |
| Toshiba                 | 26        | 2.24%   |
| Intel                   | 22        | 1.89%   |
| Biostar                 | 18        | 1.55%   |
| ECS                     | 17        | 1.46%   |
| Apple                   | 14        | 1.2%    |
| AXIOO                   | 11        | 0.95%   |
| Unknown                 | 11        | 0.95%   |
| Sony                    | 8         | 0.69%   |
| Fujitsu                 | 7         | 0.6%    |
| Samsung Electronics     | 4         | 0.34%   |
| Infinix                 | 4         | 0.34%   |
| HUAWEI                  | 3         | 0.26%   |
| Foxconn                 | 3         | 0.26%   |
| Clevo                   | 3         | 0.26%   |
| AZW                     | 3         | 0.26%   |
| Timi                    | 2         | 0.17%   |
| Supermicro              | 2         | 0.17%   |
| Raspberry Pi Foundation | 2         | 0.17%   |
| Pegatron                | 2         | 0.17%   |
| Panasonic               | 2         | 0.17%   |
| OEM                     | 2         | 0.17%   |
| LORD ELECTRONICS        | 2         | 0.17%   |
| Langchao                | 2         | 0.17%   |
| ZYREX COMPUTER SYSTEMS  | 1         | 0.09%   |
| Wearnes                 | 1         | 0.09%   |
| Valve                   | 1         | 0.09%   |
| SPECTRUM UTAMA          | 1         | 0.09%   |
| Sole                    | 1         | 0.09%   |
| Rockchip                | 1         | 0.09%   |
| Quanta                  | 1         | 0.09%   |
| Qualcomm Technologies   | 1         | 0.09%   |
| Phoenix/SiS             | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 17        | 1.46%   |
| Lenovo IdeaPad 330-14AST 81D5           | 10        | 0.86%   |
| Lenovo G40-45 80E1                      | 10        | 0.86%   |
| HP Notebook                             | 9         | 0.77%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 8         | 0.69%   |
| Intel H61                               | 6         | 0.52%   |
| HP Laptop 14-bw0xx                      | 6         | 0.52%   |
| HP 14                                   | 6         | 0.52%   |
| Acer Aspire 4752                        | 6         | 0.52%   |
| Lenovo IdeaPad S340-14API 81NB          | 5         | 0.43%   |
| Lenovo G400 20235                       | 5         | 0.43%   |
| HP Pavilion g4                          | 5         | 0.43%   |
| ASUS X455YA                             | 5         | 0.43%   |
| ASUS X455LF                             | 5         | 0.43%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.43%   |
| ASUS All Series                         | 5         | 0.43%   |
| Apple MacBookPro12,1                    | 5         | 0.43%   |
| Acer Aspire 4750                        | 5         | 0.43%   |
| Lenovo Yoga C640-13IML 81UE             | 4         | 0.34%   |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.34%   |
| Lenovo G40-30 80FY                      | 4         | 0.34%   |
| HP Pavilion 14                          | 4         | 0.34%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.34%   |
| HP Laptop 14-bs0xx                      | 4         | 0.34%   |
| HP 1000                                 | 4         | 0.34%   |
| Dell OptiPlex 7010                      | 4         | 0.34%   |
| ASUS X456URK                            | 4         | 0.34%   |
| ASUS X453SA                             | 4         | 0.34%   |
| ASUS X442URR                            | 4         | 0.34%   |
| ASUS X200MA                             | 4         | 0.34%   |
| ASUS GL553VD                            | 4         | 0.34%   |
| Acer Swift SF314-71                     | 4         | 0.34%   |
| Acer One Z1402                          | 4         | 0.34%   |
| Acer Aspire E5-475G                     | 4         | 0.34%   |
| Lenovo V310-14ISK 80SX                  | 3         | 0.26%   |
| Lenovo ThinkSystem SR550 -[7X04CTO1WW]  | 3         | 0.26%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.26%   |
| Lenovo IdeaPad C340-14IWL 81N4          | 3         | 0.26%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 3         | 0.26%   |
| Lenovo IdeaPad 3 14ARE05 81W3           | 3         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 83        | 7.14%   |
| Acer Aspire        | 73        | 6.28%   |
| Lenovo ThinkPad    | 69        | 5.93%   |
| HP Laptop          | 31        | 2.67%   |
| ASUS VivoBook      | 31        | 2.67%   |
| HP Pavilion        | 30        | 2.58%   |
| Dell Latitude      | 30        | 2.58%   |
| Dell Inspiron      | 21        | 1.81%   |
| Toshiba Satellite  | 18        | 1.55%   |
| Acer Swift         | 18        | 1.55%   |
| Unknown            | 17        | 1.46%   |
| HP EliteBook       | 14        | 1.2%    |
| Dell OptiPlex      | 13        | 1.12%   |
| Dell Vostro        | 12        | 1.03%   |
| Lenovo Yoga        | 11        | 0.95%   |
| Lenovo ThinkCentre | 10        | 0.86%   |
| Lenovo G40-45      | 10        | 0.86%   |
| Lenovo ThinkBook   | 9         | 0.77%   |
| HP Notebook        | 9         | 0.77%   |
| ASUS ROG           | 9         | 0.77%   |
| HP ENVY            | 8         | 0.69%   |
| ASUS TUF           | 8         | 0.69%   |
| Acer Nitro         | 8         | 0.69%   |
| ASUS PRIME         | 7         | 0.6%    |
| MSI Modern         | 6         | 0.52%   |
| Lenovo ThinkSystem | 6         | 0.52%   |
| Intel H61          | 6         | 0.52%   |
| HP Compaq          | 6         | 0.52%   |
| HP 14              | 6         | 0.52%   |
| Toshiba PORTEGE    | 5         | 0.43%   |
| Lenovo G400        | 5         | 0.43%   |
| HP ProLiant        | 5         | 0.43%   |
| HP ProBook         | 5         | 0.43%   |
| ASUS X455YA        | 5         | 0.43%   |
| ASUS X455LF        | 5         | 0.43%   |
| ASUS P5KPL-AM      | 5         | 0.43%   |
| ASUS ASUS          | 5         | 0.43%   |
| ASUS All           | 5         | 0.43%   |
| Apple MacBookPro12 | 5         | 0.43%   |
| Acer One           | 5         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 114       | 9.8%    |
| 2019    | 108       | 9.29%   |
| 2013    | 106       | 9.11%   |
| 2012    | 95        | 8.17%   |
| 2011    | 95        | 8.17%   |
| 2017    | 85        | 7.31%   |
| 2014    | 85        | 7.31%   |
| 2020    | 84        | 7.22%   |
| 2021    | 78        | 6.71%   |
| 2015    | 70        | 6.02%   |
| 2010    | 65        | 5.59%   |
| 2016    | 62        | 5.33%   |
| 2009    | 34        | 2.92%   |
| 2008    | 30        | 2.58%   |
| 2022    | 24        | 2.06%   |
| 2007    | 16        | 1.38%   |
| Unknown | 8         | 0.69%   |
| 2006    | 3         | 0.26%   |
| 2023    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 799       | 68.7%   |
| Desktop        | 282       | 24.25%  |
| Convertible    | 27        | 2.32%   |
| Server         | 20        | 1.72%   |
| All in one     | 14        | 1.2%    |
| Tablet         | 6         | 0.52%   |
| Mini pc        | 6         | 0.52%   |
| Phone          | 5         | 0.43%   |
| System on chip | 4         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1087      | 92.51%  |
| Enabled  | 88        | 7.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1162      | 99.91%  |
| Yes  | 1         | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 346       | 29.42%  |
| 3.01-4.0        | 307       | 26.11%  |
| 8.01-16.0       | 207       | 17.6%   |
| 16.01-24.0      | 158       | 13.44%  |
| 1.01-2.0        | 90        | 7.65%   |
| 32.01-64.0      | 28        | 2.38%   |
| 2.01-3.0        | 15        | 1.28%   |
| 24.01-32.0      | 9         | 0.77%   |
| 64.01-256.0     | 8         | 0.68%   |
| 0.51-1.0        | 7         | 0.6%    |
| More than 256.0 | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 458       | 35.87%  |
| 2.01-3.0   | 359       | 28.11%  |
| 4.01-8.0   | 167       | 13.08%  |
| 3.01-4.0   | 164       | 12.84%  |
| 0.51-1.0   | 92        | 7.2%    |
| 8.01-16.0  | 25        | 1.96%   |
| 0.01-0.5   | 8         | 0.63%   |
| 16.01-24.0 | 3         | 0.23%   |
| Unknown    | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 794       | 66.89%  |
| 2       | 306       | 25.78%  |
| 3       | 52        | 4.38%   |
| 4       | 20        | 1.68%   |
| 0       | 9         | 0.76%   |
| 5       | 4         | 0.34%   |
| 15      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 764       | 65.08%  |
| Yes       | 410       | 34.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 981       | 84.28%  |
| No        | 183       | 15.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 993       | 84.87%  |
| No        | 177       | 15.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 731       | 62.32%  |
| No        | 442       | 37.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Indonesia | 1163      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Jakarta         | 356       | 28.19%  |
| Surabaya        | 117       | 9.26%   |
| Bandung         | 94        | 7.44%   |
| Yogyakarta      | 54        | 4.28%   |
| Semarang        | 40        | 3.17%   |
| Bogor           | 37        | 2.93%   |
| Tangerang       | 32        | 2.53%   |
| Malang          | 32        | 2.53%   |
| Bekasi          | 30        | 2.38%   |
| Medan           | 27        | 2.14%   |
| South Tangerang | 25        | 1.98%   |
| Denpasar        | 23        | 1.82%   |
| Makassar        | 15        | 1.19%   |
| Depok           | 15        | 1.19%   |
| Palembang       | 13        | 1.03%   |
| Banjarmasin     | 13        | 1.03%   |
| Sleman          | 12        | 0.95%   |
| Tasikmalaya     | 9         | 0.71%   |
| Gresik          | 9         | 0.71%   |
| Balikpapan      | 9         | 0.71%   |
| Surakarta       | 8         | 0.63%   |
| Banda Aceh      | 8         | 0.63%   |
| Samarinda       | 7         | 0.55%   |
| Pasuruan        | 7         | 0.55%   |
| Blitar          | 7         | 0.55%   |
| Pontianak       | 6         | 0.48%   |
| Mataram         | 6         | 0.48%   |
| Cirebon         | 6         | 0.48%   |
| Brebes          | 6         | 0.48%   |
| Batam           | 6         | 0.48%   |
| Sukabumi        | 5         | 0.4%    |
| Pekan Baru      | 5         | 0.4%    |
| Magelang        | 5         | 0.4%    |
| Kediri          | 5         | 0.4%    |
| Tanjung Pinang  | 4         | 0.32%   |
| Purwokerto      | 4         | 0.32%   |
| Kudus           | 4         | 0.32%   |
| Jember          | 4         | 0.32%   |
| Jambi City      | 4         | 0.32%   |
| Demak           | 4         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 313       | 419    | 20.5%   |
| WDC                   | 222       | 294    | 14.54%  |
| Samsung Electronics   | 140       | 182    | 9.17%   |
| Toshiba               | 126       | 139    | 8.25%   |
| HGST                  | 62        | 72     | 4.06%   |
| Hitachi               | 59        | 70     | 3.86%   |
| Unknown               | 54        | 69     | 3.54%   |
| SanDisk               | 46        | 57     | 3.01%   |
| Kingston              | 42        | 52     | 2.75%   |
| Intel                 | 37        | 56     | 2.42%   |
| V-GeN                 | 36        | 39     | 2.36%   |
| A-DATA Technology     | 34        | 41     | 2.23%   |
| SK hynix              | 28        | 34     | 1.83%   |
| Micron Technology     | 26        | 33     | 1.7%    |
| MidasForce            | 22        | 24     | 1.44%   |
| China                 | 20        | 22     | 1.31%   |
| Unknown               | 17        | 18     | 1.11%   |
| Apacer                | 15        | 16     | 0.98%   |
| JMicron Technology    | 14        | 15     | 0.92%   |
| Patriot               | 12        | 19     | 0.79%   |
| Fujitsu               | 11        | 12     | 0.72%   |
| Team                  | 10        | 13     | 0.65%   |
| Silicon Motion        | 10        | 11     | 0.65%   |
| Apple                 | 9         | 10     | 0.59%   |
| VISIPRO               | 8         | 11     | 0.52%   |
| Crucial               | 7         | 9      | 0.46%   |
| Transcend             | 6         | 10     | 0.39%   |
| RX7                   | 6         | 7      | 0.39%   |
| Pioneer               | 6         | 6      | 0.39%   |
| ADATA Technology      | 6         | 9      | 0.39%   |
| XPG                   | 5         | 8      | 0.33%   |
| Phison Electronics    | 5         | 6      | 0.33%   |
| Hewlett-Packard       | 5         | 5      | 0.33%   |
| Realtek Semiconductor | 4         | 4      | 0.26%   |
| Phison                | 4         | 6      | 0.26%   |
| EYOTA                 | 4         | 4      | 0.26%   |
| External              | 4         | 4      | 0.26%   |
| Wellcomm              | 3         | 3      | 0.2%    |
| Smart                 | 3         | 3      | 0.2%    |
| Ramos Technology      | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB    | 40        | 2.46%   |
| Seagate ST1000LM035-1RK172 1TB     | 39        | 2.4%    |
| Toshiba MQ01ABF050 500GB           | 23        | 1.42%   |
| Toshiba MQ04ABF100 1TB             | 21        | 1.29%   |
| Toshiba MQ01ABD100 1TB             | 20        | 1.23%   |
| Seagate ST3500312CS 500GB          | 19        | 1.17%   |
| Seagate ST500DM002-1BD142 500GB    | 18        | 1.11%   |
| A-DATA SU650 120GB SSD             | 18        | 1.11%   |
| HGST HTS545050A7E680 500GB         | 17        | 1.05%   |
| Unknown                            | 17        | 1.05%   |
| Seagate ST9500325AS 500GB          | 11        | 0.68%   |
| Samsung SSD 850 EVO 250GB          | 10        | 0.62%   |
| Hitachi HTS545050A7E380 500GB      | 10        | 0.62%   |
| Hitachi HTS543232A7A384 320GB      | 10        | 0.62%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 9         | 0.55%   |
| Seagate ST500LT012-9WS142 500GB    | 9         | 0.55%   |
| Seagate ST3250318AS 250GB          | 9         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 9         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 9         | 0.55%   |
| SanDisk NVMe SSD Drive 512GB       | 9         | 0.55%   |
| MidasForce SSD 128GB               | 9         | 0.55%   |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.55%   |
| HGST HTS721010A9E630 1TB           | 9         | 0.55%   |
| Unknown MMC Card  128GB            | 8         | 0.49%   |
| Seagate ST9320325AS 320GB          | 8         | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 8         | 0.49%   |
| JMicron Generic 320GB              | 8         | 0.49%   |
| HGST HTS545050A7E380 500GB         | 8         | 0.49%   |
| Apacer AS340 240GB SSD             | 8         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 7         | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB           | 7         | 0.43%   |
| Unknown MMC Card  64GB             | 7         | 0.43%   |
| Unknown MMC Card  32GB             | 7         | 0.43%   |
| Seagate ST2000LM007-1R8174 2TB     | 7         | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB     | 7         | 0.43%   |
| Intel NVMe SSD Drive 512GB         | 7         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 6         | 0.37%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 6         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB     | 6         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 311       | 413    | 40.6%   |
| WDC                 | 174       | 228    | 22.72%  |
| Toshiba             | 112       | 124    | 14.62%  |
| HGST                | 62        | 72     | 8.09%   |
| Hitachi             | 59        | 70     | 7.7%    |
| Samsung Electronics | 13        | 13     | 1.7%    |
| Fujitsu             | 9         | 9      | 1.17%   |
| Unknown             | 6         | 6      | 0.78%   |
| External            | 4         | 4      | 0.52%   |
| Maxtor              | 3         | 3      | 0.39%   |
| Hewlett-Packard     | 3         | 3      | 0.39%   |
| Apple               | 3         | 3      | 0.39%   |
| Pioneer             | 2         | 2      | 0.26%   |
| USB3.0              | 1         | 1      | 0.13%   |
| JMicron Technology  | 1         | 1      | 0.13%   |
| HGST HTS            | 1         | 3      | 0.13%   |
| ExcelStor           | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 83     | 16.13%  |
| WDC                 | 32        | 41     | 7.94%   |
| Kingston            | 26        | 29     | 6.45%   |
| A-DATA Technology   | 25        | 31     | 6.2%    |
| SanDisk             | 24        | 32     | 5.96%   |
| MidasForce          | 22        | 24     | 5.46%   |
| China               | 20        | 22     | 4.96%   |
| V-GeN               | 19        | 22     | 4.71%   |
| Apacer              | 15        | 16     | 3.72%   |
| Patriot             | 12        | 19     | 2.98%   |
| Unknown             | 9         | 9      | 2.23%   |
| Team                | 8         | 11     | 1.99%   |
| JMicron Technology  | 8         | 8      | 1.99%   |
| Intel               | 8         | 12     | 1.99%   |
| Crucial             | 7         | 9      | 1.74%   |
| VISIPRO             | 6         | 9      | 1.49%   |
| Toshiba             | 5         | 5      | 1.24%   |
| Seagate             | 5         | 5      | 1.24%   |
| Apple               | 5         | 5      | 1.24%   |
| Transcend           | 4         | 7      | 0.99%   |
| RX7                 | 4         | 5      | 0.99%   |
| Pioneer             | 4         | 4      | 0.99%   |
| Micron Technology   | 4         | 5      | 0.99%   |
| Wellcomm            | 3         | 3      | 0.74%   |
| Unknown             | 3         | 4      | 0.74%   |
| SK hynix            | 3         | 4      | 0.74%   |
| Ramos Technology    | 3         | 3      | 0.74%   |
| OCZ                 | 3         | 3      | 0.74%   |
| LITEONIT            | 3         | 4      | 0.74%   |
| LITEON              | 3         | 4      | 0.74%   |
| Kingmax             | 3         | 3      | 0.74%   |
| GALAX               | 3         | 3      | 0.74%   |
| XSTAR               | 2         | 2      | 0.5%    |
| TO Exter            | 2         | 2      | 0.5%    |
| SPCC                | 2         | 2      | 0.5%    |
| Smart               | 2         | 2      | 0.5%    |
| Memory              | 2         | 2      | 0.5%    |
| Lexar               | 2         | 2      | 0.5%    |
| FORESEE             | 2         | 2      | 0.5%    |
| EYOTA               | 2         | 2      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 697       | 957    | 49.08%  |
| SSD     | 371       | 488    | 26.13%  |
| NVMe    | 266       | 355    | 18.73%  |
| Unknown | 44        | 51     | 3.1%    |
| MMC     | 42        | 58     | 2.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 923       | 1438   | 72%     |
| NVMe | 266       | 354    | 20.75%  |
| SAS  | 51        | 59     | 3.98%   |
| MMC  | 42        | 58     | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 701       | 1000   | 67.02%  |
| 0.51-1.0   | 285       | 359    | 27.25%  |
| 1.01-2.0   | 44        | 67     | 4.21%   |
| 3.01-4.0   | 7         | 10     | 0.67%   |
| 2.01-3.0   | 5         | 5      | 0.48%   |
| 4.01-10.0  | 4         | 4      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 339       | 27.81%  |
| 251-500        | 304       | 24.94%  |
| 501-1000       | 138       | 11.32%  |
| 51-100         | 133       | 10.91%  |
| 1-20           | 91        | 7.47%   |
| 1001-2000      | 87        | 7.14%   |
| 21-50          | 70        | 5.74%   |
| Unknown        | 25        | 2.05%   |
| More than 3000 | 17        | 1.39%   |
| 2001-3000      | 15        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 488       | 38.49%  |
| 21-50          | 225       | 17.74%  |
| 101-250        | 159       | 12.54%  |
| 51-100         | 152       | 11.99%  |
| 251-500        | 110       | 8.68%   |
| 501-1000       | 75        | 5.91%   |
| Unknown        | 25        | 1.97%   |
| 1001-2000      | 21        | 1.66%   |
| More than 3000 | 8         | 0.63%   |
| 2001-3000      | 5         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 8         | 8      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB  | 7         | 9      | 4.17%   |
| Seagate ST9500325AS 500GB        | 5         | 5      | 2.98%   |
| Seagate ST500LT012-9WS142 500GB  | 5         | 5      | 2.98%   |
| Seagate ST500LT012-1DG142 500GB  | 5         | 5      | 2.98%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 3         | 3      | 1.79%   |
| Toshiba MQ01ABD032 320GB         | 3         | 3      | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB   | 3         | 3      | 1.79%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 3      | 1.79%   |
| HGST HTS725050A7E630 500GB       | 3         | 3      | 1.79%   |
| WDC WD800JD-08LSA0 80GB          | 2         | 2      | 1.19%   |
| WDC WD3200BEKT-60V5T1 320GB      | 2         | 2      | 1.19%   |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 3      | 1.19%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2         | 2      | 1.19%   |
| Toshiba MQ01ABF050 500GB         | 2         | 2      | 1.19%   |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 1.19%   |
| Toshiba MK5059GSXP 500GB         | 2         | 2      | 1.19%   |
| Toshiba MK3265GSX 320GB          | 2         | 3      | 1.19%   |
| Seagate ST9500420AS 500GB        | 2         | 2      | 1.19%   |
| Seagate ST9250410AS 250GB        | 2         | 2      | 1.19%   |
| Seagate ST1000LX015-1U7172 1TB   | 2         | 3      | 1.19%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 2      | 1.19%   |
| Hitachi HTS545050B9A300 500GB    | 2         | 2      | 1.19%   |
| Hitachi HTS545016B9A300 160GB    | 2         | 2      | 1.19%   |
| HGST HTS545050A7E380 500GB       | 2         | 3      | 1.19%   |
| WellcommMaster 128GB SSD         | 1         | 1      | 0.6%    |
| Wellcomm Master 128GB SSD        | 1         | 1      | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.6%    |
| WDC WD7500BPVT-55HXZT4 752GB     | 1         | 1      | 0.6%    |
| WDC WD6400AADS-00M2B0 640GB      | 1         | 1      | 0.6%    |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000LPCX-22VHAT0 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000L 500GB                | 1         | 1      | 0.6%    |
| WDC WD5000BPVT-60HXZT3 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000BPVT-08HXZT3 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000AZLX-00JKKA0 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-08U6AA0 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-08ERMA0 500GB     | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-083CA1 500GB      | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 60     | 30%     |
| WDC                 | 34        | 40     | 21.25%  |
| Toshiba             | 19        | 21     | 11.88%  |
| Hitachi             | 17        | 17     | 10.63%  |
| HGST                | 15        | 17     | 9.38%   |
| Samsung Electronics | 5         | 6      | 3.13%   |
| SanDisk             | 3         | 3      | 1.88%   |
| Micron Technology   | 2         | 2      | 1.25%   |
| Kingston            | 2         | 2      | 1.25%   |
| China               | 2         | 2      | 1.25%   |
| A-DATA Technology   | 2         | 3      | 1.25%   |
| WellcommMaster      | 1         | 1      | 0.63%   |
| Wellcomm            | 1         | 1      | 0.63%   |
| VISIPRO             | 1         | 3      | 0.63%   |
| ValueTech           | 1         | 1      | 0.63%   |
| T-FORCE             | 1         | 1      | 0.63%   |
| RX7                 | 1         | 1      | 0.63%   |
| Maxtor              | 1         | 1      | 0.63%   |
| KLEVV               | 1         | 1      | 0.63%   |
| Intel               | 1         | 1      | 0.63%   |
| Crucial             | 1         | 1      | 0.63%   |
| Apacer              | 1         | 2      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 60     | 35.29%  |
| WDC                 | 33        | 39     | 24.26%  |
| Toshiba             | 19        | 21     | 13.97%  |
| Hitachi             | 17        | 17     | 12.5%   |
| HGST                | 15        | 17     | 11.03%  |
| Samsung Electronics | 3         | 3      | 2.21%   |
| Maxtor              | 1         | 1      | 0.74%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 128       | 158    | 84.77%  |
| SSD  | 21        | 26     | 13.91%  |
| NVMe | 2         | 3      | 1.32%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB     | 2         | 2      | 50%     |
| WDC WD5000BPVT-60HXZT1 500GB  | 1         | 1      | 25%     |
| Hitachi HTS545050A7E380 500GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 656       | 1045   | 52.27%  |
| Works    | 448       | 673    | 35.7%   |
| Malfunc  | 147       | 187    | 11.71%  |
| Failed   | 4         | 4      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 804       | 59.6%   |
| AMD                              | 247       | 18.31%  |
| Samsung Electronics              | 70        | 5.19%   |
| SanDisk                          | 41        | 3.04%   |
| SK hynix                         | 24        | 1.78%   |
| Micron Technology                | 22        | 1.63%   |
| ADATA Technology                 | 19        | 1.41%   |
| Kingston Technology Company      | 17        | 1.26%   |
| Silicon Motion                   | 16        | 1.19%   |
| Phison Electronics               | 14        | 1.04%   |
| ASMedia Technology               | 9         | 0.67%   |
| Toshiba America Info Systems     | 7         | 0.52%   |
| Realtek Semiconductor            | 6         | 0.44%   |
| Broadcom / LSI                   | 6         | 0.44%   |
| Union Memory (Shenzhen)          | 5         | 0.37%   |
| Nvidia                           | 5         | 0.37%   |
| KIOXIA                           | 5         | 0.37%   |
| JMicron Technology               | 5         | 0.37%   |
| VIA Technologies                 | 4         | 0.3%    |
| Silicon Integrated Systems [SiS] | 4         | 0.3%    |
| Hewlett-Packard                  | 4         | 0.3%    |
| Marvell Technology Group         | 3         | 0.22%   |
| Micron/Crucial Technology        | 2         | 0.15%   |
| LSI Logic / Symbios Logic        | 2         | 0.15%   |
| Adaptec                          | 2         | 0.15%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| O2 Micro                         | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 197       | 12.79%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 77        | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 72        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 49        | 3.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 44        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43        | 2.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 42        | 2.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 37        | 2.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 31        | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 30        | 1.95%   |
| Samsung NVMe SSD Controller 980                                                         | 29        | 1.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 25        | 1.62%   |
| Micron NVMe Storage Controller                                                          | 22        | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 20        | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 20        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20        | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 19        | 1.23%   |
| Intel SSD 660P Series                                                                   | 18        | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 17        | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 17        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16        | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 15        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15        | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 15        | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 14        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 13        | 0.84%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 13        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 13        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 12        | 0.78%   |
| AMD FCH IDE Controller                                                                  | 12        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 11        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 0.71%   |
| SK hynix BC511                                                                          | 10        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 10        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 898       | 64.23%  |
| NVMe | 266       | 19.03%  |
| IDE  | 149       | 10.66%  |
| RAID | 80        | 5.72%   |
| SAS  | 4         | 0.29%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 865       | 74.38%  |
| AMD      | 289       | 24.85%  |
| ARM      | 6         | 0.52%   |
| QUALCOMM | 3         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 1.29%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 14        | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.12%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.12%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 12        | 1.03%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 12        | 1.03%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 12        | 1.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 0.95%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 11        | 0.95%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 11        | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 10        | 0.86%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 10        | 0.86%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 10        | 0.86%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 9         | 0.77%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 9         | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 9         | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.69%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 8         | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.69%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.69%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.6%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.6%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 7         | 0.6%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 7         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 273       | 23.45%  |
| Intel Core i3           | 155       | 13.32%  |
| Intel Core i7           | 147       | 12.63%  |
| Intel Celeron           | 78        | 6.7%    |
| Other                   | 76        | 6.53%   |
| AMD Ryzen 5             | 70        | 6.01%   |
| Intel Core 2 Duo        | 51        | 4.38%   |
| AMD Ryzen 3             | 32        | 2.75%   |
| Intel Pentium           | 29        | 2.49%   |
| AMD Ryzen 7             | 26        | 2.23%   |
| AMD A8                  | 26        | 2.23%   |
| Intel Xeon              | 23        | 1.98%   |
| Intel Atom              | 16        | 1.37%   |
| AMD A6                  | 13        | 1.12%   |
| AMD A4                  | 13        | 1.12%   |
| Intel Pentium Dual-Core | 12        | 1.03%   |
| Intel Core 2 Quad       | 9         | 0.77%   |
| AMD FX                  | 9         | 0.77%   |
| AMD E1                  | 9         | 0.77%   |
| Intel Genuine           | 7         | 0.6%    |
| AMD E2                  | 7         | 0.6%    |
| AMD E                   | 7         | 0.6%    |
| AMD A10                 | 7         | 0.6%    |
| Intel Pentium Dual      | 6         | 0.52%   |
| AMD Ryzen 9             | 6         | 0.52%   |
| AMD Athlon II X2        | 6         | 0.52%   |
| AMD Athlon              | 5         | 0.43%   |
| Intel Xeon Bronze       | 4         | 0.34%   |
| Intel Core 2            | 4         | 0.34%   |
| AMD Phenom II X6        | 4         | 0.34%   |
| QUALCOMM AArch64        | 3         | 0.26%   |
| AMD Phenom II X4        | 3         | 0.26%   |
| AMD C-60                | 3         | 0.26%   |
| Intel Xeon Silver       | 2         | 0.17%   |
| Intel Pentium Silver    | 2         | 0.17%   |
| AMD Ryzen 5 PRO         | 2         | 0.17%   |
| AMD Ryzen 3 PRO         | 2         | 0.17%   |
| AMD Athlon X4           | 2         | 0.17%   |
| AMD A12                 | 2         | 0.17%   |
| Intel Pentium Gold      | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 649       | 55.76%  |
| 4       | 343       | 29.47%  |
| 6       | 91        | 7.82%   |
| 8       | 43        | 3.69%   |
| 1       | 15        | 1.29%   |
| 12      | 9         | 0.77%   |
| 10      | 7         | 0.6%    |
| 3       | 3         | 0.26%   |
| 44      | 1         | 0.09%   |
| 16      | 1         | 0.09%   |
| 14      | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1151      | 98.97%  |
| 2       | 9         | 0.77%   |
| 3       | 2         | 0.17%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 750       | 64.49%  |
| 1       | 412       | 35.43%  |
| Unknown | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1136      | 97.68%  |
| Unknown        | 21        | 1.81%   |
| 32-bit         | 4         | 0.34%   |
| 64-bit         | 2         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 216       | 17.87%  |
| 0x206a7    | 88        | 7.28%   |
| 0x306a9    | 78        | 6.45%   |
| 0x1067a    | 47        | 3.89%   |
| 0x306c3    | 42        | 3.47%   |
| 0x40651    | 40        | 3.31%   |
| 0x306d4    | 33        | 2.73%   |
| 0x806ea    | 30        | 2.48%   |
| 0x806ec    | 29        | 2.4%    |
| 0x906ea    | 28        | 2.32%   |
| 0x806e9    | 26        | 2.15%   |
| 0x06006705 | 25        | 2.07%   |
| 0x406e3    | 23        | 1.9%    |
| 0x20655    | 23        | 1.9%    |
| 0x806c1    | 22        | 1.82%   |
| 0x0a50000c | 19        | 1.57%   |
| 0x08108109 | 19        | 1.57%   |
| 0x906e9    | 18        | 1.49%   |
| 0x6fd      | 16        | 1.32%   |
| 0x806eb    | 15        | 1.24%   |
| 0x08108102 | 14        | 1.16%   |
| 0x07030105 | 14        | 1.16%   |
| 0x706e5    | 13        | 1.08%   |
| 0x30678    | 13        | 1.08%   |
| 0x706a8    | 11        | 0.91%   |
| 0x506e3    | 11        | 0.91%   |
| 0x20652    | 11        | 0.91%   |
| 0x0810100b | 11        | 0.91%   |
| 0x06001119 | 11        | 0.91%   |
| 0x406c4    | 10        | 0.83%   |
| 0x406c3    | 10        | 0.83%   |
| 0x08600104 | 10        | 0.83%   |
| 0x08608103 | 9         | 0.74%   |
| 0x10676    | 8         | 0.66%   |
| 0x6fb      | 7         | 0.58%   |
| 0x08101007 | 7         | 0.58%   |
| 0x05000119 | 7         | 0.58%   |
| 0x03000027 | 7         | 0.58%   |
| 0x706a1    | 6         | 0.5%    |
| 0x08701021 | 6         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 182       | 15.65%  |
| SandyBridge      | 106       | 9.11%   |
| Haswell          | 96        | 8.25%   |
| IvyBridge        | 93        | 8%      |
| Penryn           | 58        | 4.99%   |
| Westmere         | 47        | 4.04%   |
| Skylake          | 46        | 3.96%   |
| Excavator        | 44        | 3.78%   |
| Silvermont       | 43        | 3.7%    |
| Broadwell        | 42        | 3.61%   |
| Zen+             | 39        | 3.35%   |
| Zen              | 31        | 2.67%   |
| Unknown          | 31        | 2.67%   |
| Core             | 30        | 2.58%   |
| Zen 3            | 29        | 2.49%   |
| Zen 2            | 29        | 2.49%   |
| TigerLake        | 26        | 2.24%   |
| Puma             | 25        | 2.15%   |
| Goldmont plus    | 20        | 1.72%   |
| Piledriver       | 19        | 1.63%   |
| IceLake          | 17        | 1.46%   |
| CometLake        | 15        | 1.29%   |
| Bobcat           | 15        | 1.29%   |
| K10              | 14        | 1.2%    |
| Alderlake Hybrid | 11        | 0.95%   |
| Jaguar           | 9         | 0.77%   |
| K10 Llano        | 8         | 0.69%   |
| Bonnell          | 8         | 0.69%   |
| Steamroller      | 7         | 0.6%    |
| Nehalem          | 7         | 0.6%    |
| Goldmont         | 7         | 0.6%    |
| Tremont          | 3         | 0.26%   |
| P6               | 2         | 0.17%   |
| K8 Hammer        | 2         | 0.17%   |
| NetBurst         | 1         | 0.09%   |
| Bulldozer        | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 747       | 52.57%  |
| AMD                              | 364       | 25.62%  |
| Nvidia                           | 287       | 20.2%   |
| Matrox Electronics Systems       | 13        | 0.91%   |
| ASPEED Technology                | 5         | 0.35%   |
| Silicon Integrated Systems [SiS] | 4         | 0.28%   |
| Silicon Motion                   | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 90        | 6.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 3.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 3.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 37        | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 2.5%    |
| Intel UHD Graphics 620                                                                   | 33        | 2.23%   |
| Intel HD Graphics 5500                                                                   | 33        | 2.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 33        | 2.23%   |
| Intel HD Graphics 620                                                                    | 32        | 2.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 2.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23        | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 22        | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 22        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 1.42%   |
| AMD Renoir                                                                               | 21        | 1.42%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 1.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 1.35%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 20        | 1.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17        | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 1.15%   |
| Intel HD Graphics 630                                                                    | 14        | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 0.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 0.74%   |
| AMD Lucienne                                                                             | 11        | 0.74%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 10        | 0.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 10        | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 509       | 43.54%  |
| 1 x AMD                | 252       | 21.56%  |
| Intel + Nvidia         | 179       | 15.31%  |
| 1 x Nvidia             | 78        | 6.67%   |
| Intel + AMD            | 49        | 4.19%   |
| 2 x AMD                | 38        | 3.25%   |
| AMD + Nvidia           | 25        | 2.14%   |
| 1 x Matrox             | 13        | 1.11%   |
| Other                  | 10        | 0.86%   |
| 1 x SiS                | 4         | 0.34%   |
| 1 x ASPEED             | 4         | 0.34%   |
| 2 x Intel              | 3         | 0.26%   |
| 2 x Nvidia             | 2         | 0.17%   |
| 1 x Silicon Motion     | 1         | 0.09%   |
| Nvidia + ASPEED        | 1         | 0.09%   |
| 1 x Intel + 4 x Nvidia | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 994       | 84.24%  |
| Proprietary | 148       | 12.54%  |
| Unknown     | 38        | 3.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 687       | 57.44%  |
| 1.01-2.0   | 191       | 15.97%  |
| 0.01-0.5   | 141       | 11.79%  |
| 0.51-1.0   | 85        | 7.11%   |
| 3.01-4.0   | 60        | 5.02%   |
| 5.01-6.0   | 15        | 1.25%   |
| 7.01-8.0   | 11        | 0.92%   |
| 8.01-16.0  | 4         | 0.33%   |
| 2.01-3.0   | 2         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 197       | 16.84%  |
| Chimei Innolux          | 171       | 14.62%  |
| BOE                     | 141       | 12.05%  |
| LG Display              | 113       | 9.66%   |
| Samsung Electronics     | 110       | 9.4%    |
| Goldstar                | 105       | 8.97%   |
| Dell                    | 42        | 3.59%   |
| Lenovo                  | 33        | 2.82%   |
| Hewlett-Packard         | 22        | 1.88%   |
| AOC                     | 19        | 1.62%   |
| Acer                    | 16        | 1.37%   |
| Philips                 | 15        | 1.28%   |
| PANDA                   | 14        | 1.2%    |
| InfoVision              | 14        | 1.2%    |
| Apple                   | 13        | 1.11%   |
| ViewSonic               | 12        | 1.03%   |
| Sharp                   | 12        | 1.03%   |
| Chi Mei Optoelectronics | 10        | 0.85%   |
| BenQ                    | 10        | 0.85%   |
| Toshiba                 | 8         | 0.68%   |
| InnoLux Display         | 8         | 0.68%   |
| LG Electronics          | 7         | 0.6%    |
| Ancor Communications    | 6         | 0.51%   |
| LG Philips              | 5         | 0.43%   |
| Sony                    | 4         | 0.34%   |
| CPT                     | 4         | 0.34%   |
| Unknown                 | 3         | 0.26%   |
| Quanta Display          | 3         | 0.26%   |
| QCM                     | 3         | 0.26%   |
| Panasonic               | 3         | 0.26%   |
| Mi                      | 3         | 0.26%   |
| KDC                     | 3         | 0.26%   |
| HannStar                | 3         | 0.26%   |
| ASUSTek Computer        | 3         | 0.26%   |
| SPC                     | 2         | 0.17%   |
| Seiko/Epson             | 2         | 0.17%   |
| RTK                     | 2         | 0.17%   |
| JRY                     | 2         | 0.17%   |
| HJC                     | 2         | 0.17%   |
| GDH                     | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 19        | 1.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 15        | 1.27%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 15        | 1.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 15        | 1.27%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 14        | 1.18%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 14        | 1.18%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 14        | 1.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 11        | 0.93%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 11        | 0.93%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 11        | 0.93%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 10        | 0.85%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 10        | 0.85%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 10        | 0.85%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 10        | 0.85%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 9         | 0.76%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 9         | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 8         | 0.68%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                 | 8         | 0.68%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 8         | 0.68%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 7         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch      | 7         | 0.59%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch      | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 6         | 0.51%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 6         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.51%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 5         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch | 5         | 0.42%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch          | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 5         | 0.42%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 5         | 0.42%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 5         | 0.42%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch        | 5         | 0.42%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch            | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch | 4         | 0.34%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch              | 4         | 0.34%   |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch         | 4         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 534       | 47.26%  |
| 1920x1080 (FHD)    | 379       | 33.54%  |
| 3840x2160 (4K)     | 34        | 3.01%   |
| 1600x900 (HD+)     | 29        | 2.57%   |
| 1440x900 (WXGA+)   | 28        | 2.48%   |
| 1280x800 (WXGA)    | 24        | 2.12%   |
| 2560x1440 (QHD)    | 15        | 1.33%   |
| 1360x768           | 15        | 1.33%   |
| 1920x1200 (WUXGA)  | 11        | 0.97%   |
| 2560x1600          | 8         | 0.71%   |
| 2560x1080          | 7         | 0.62%   |
| 1280x1024 (SXGA)   | 7         | 0.62%   |
| 2880x1800          | 5         | 0.44%   |
| 1024x768 (XGA)     | 4         | 0.35%   |
| 1024x600           | 4         | 0.35%   |
| 3440x1440          | 3         | 0.27%   |
| 2800x1752          | 3         | 0.27%   |
| Unknown            | 3         | 0.27%   |
| 3840x2400          | 2         | 0.18%   |
| 3840x1080          | 2         | 0.18%   |
| 1680x1050 (WSXGA+) | 2         | 0.18%   |
| 1280x720 (HD)      | 2         | 0.18%   |
| 800x1280           | 1         | 0.09%   |
| 640x480            | 1         | 0.09%   |
| 5760x2160          | 1         | 0.09%   |
| 3200x1800 (QHD+)   | 1         | 0.09%   |
| 2966x900           | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2240x1400          | 1         | 0.09%   |
| 1280x960           | 1         | 0.09%   |
| 1152x864           | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 278       | 23.84%  |
| 14      | 256       | 21.96%  |
| 15      | 196       | 16.81%  |
| 18      | 80        | 6.86%   |
| 21      | 65        | 5.57%   |
| 23      | 58        | 4.97%   |
| 12      | 37        | 3.17%   |
| 19      | 29        | 2.49%   |
| 11      | 28        | 2.4%    |
| 24      | 25        | 2.14%   |
| Unknown | 25        | 2.14%   |
| 27      | 18        | 1.54%   |
| 17      | 12        | 1.03%   |
| 40      | 8         | 0.69%   |
| 34      | 8         | 0.69%   |
| 31      | 6         | 0.51%   |
| 48      | 4         | 0.34%   |
| 10      | 4         | 0.34%   |
| 66      | 3         | 0.26%   |
| 20      | 3         | 0.26%   |
| 16      | 3         | 0.26%   |
| 72      | 2         | 0.17%   |
| 60      | 2         | 0.17%   |
| 52      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 22      | 2         | 0.17%   |
| 84      | 1         | 0.09%   |
| 65      | 1         | 0.09%   |
| 57      | 1         | 0.09%   |
| 54      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 39      | 1         | 0.09%   |
| 36      | 1         | 0.09%   |
| 35      | 1         | 0.09%   |
| 9       | 1         | 0.09%   |
| 7       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 658       | 56.97%  |
| 401-500     | 171       | 14.81%  |
| 201-300     | 133       | 11.52%  |
| 501-600     | 97        | 8.4%    |
| Unknown     | 25        | 2.16%   |
| 351-400     | 22        | 1.9%    |
| 801-900     | 12        | 1.04%   |
| 601-700     | 12        | 1.04%   |
| 701-800     | 10        | 0.87%   |
| 1001-1500   | 10        | 0.87%   |
| 1501-2000   | 3         | 0.26%   |
| 901-1000    | 1         | 0.09%   |
| 1-100       | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 946       | 87.84%  |
| 16/10   | 77        | 7.15%   |
| Unknown | 24        | 2.23%   |
| 21/9    | 9         | 0.84%   |
| 4/3     | 7         | 0.65%   |
| 5/4     | 6         | 0.56%   |
| 3/2     | 3         | 0.28%   |
| 0.45    | 3         | 0.28%   |
| 0.67    | 1         | 0.09%   |
| 0.56    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 478       | 41.03%  |
| 101-110        | 190       | 16.31%  |
| 201-250        | 128       | 10.99%  |
| 141-150        | 82        | 7.04%   |
| 71-80          | 52        | 4.46%   |
| 151-200        | 47        | 4.03%   |
| 61-70          | 36        | 3.09%   |
| 51-60          | 28        | 2.4%    |
| Unknown        | 25        | 2.15%   |
| 301-350        | 18        | 1.55%   |
| More than 1000 | 17        | 1.46%   |
| 351-500        | 15        | 1.29%   |
| 501-1000       | 13        | 1.12%   |
| 91-100         | 9         | 0.77%   |
| 251-300        | 7         | 0.6%    |
| 41-50          | 5         | 0.43%   |
| 121-130        | 5         | 0.43%   |
| 111-120        | 5         | 0.43%   |
| 131-140        | 4         | 0.34%   |
| 1-40           | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 482       | 41.77%  |
| 121-160       | 293       | 25.39%  |
| 51-100        | 260       | 22.53%  |
| 161-240       | 55        | 4.77%   |
| Unknown       | 25        | 2.17%   |
| 1-50          | 23        | 1.99%   |
| More than 240 | 16        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1009      | 85%     |
| 2     | 116       | 9.77%   |
| 0     | 59        | 4.97%   |
| 3     | 3         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 733       | 39.86%  |
| Intel                             | 401       | 21.81%  |
| Qualcomm Atheros                  | 323       | 17.56%  |
| Broadcom                          | 104       | 5.66%   |
| Ralink Technology                 | 38        | 2.07%   |
| MediaTek                          | 31        | 1.69%   |
| TP-Link                           | 30        | 1.63%   |
| Xiaomi                            | 26        | 1.41%   |
| Samsung Electronics               | 20        | 1.09%   |
| Broadcom Limited                  | 17        | 0.92%   |
| Qualcomm Atheros Communications   | 14        | 0.76%   |
| Ralink                            | 13        | 0.71%   |
| Marvell Technology Group          | 10        | 0.54%   |
| OPPO Electronics                  | 8         | 0.44%   |
| JMicron Technology                | 6         | 0.33%   |
| IBM                               | 6         | 0.33%   |
| ASIX Electronics                  | 6         | 0.33%   |
| Qualcomm                          | 5         | 0.27%   |
| Huawei Technologies               | 5         | 0.27%   |
| Nvidia                            | 4         | 0.22%   |
| D-Link System                     | 4         | 0.22%   |
| D-Link                            | 4         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.16%   |
| Ericsson Business Mobile Networks | 3         | 0.16%   |
| Attansic Technology               | 3         | 0.16%   |
| AboCom Systems                    | 3         | 0.16%   |
| Sierra Wireless                   | 2         | 0.11%   |
| Lenovo                            | 2         | 0.11%   |
| ICS Advent                        | 2         | 0.11%   |
| HMD Global                        | 2         | 0.11%   |
| Hewlett-Packard                   | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| vivo                              | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| QinHeng Electronics               | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| HTC (High Tech Computer)          | 1         | 0.05%   |
| Foxconn / Hon Hai                 | 1         | 0.05%   |
| Edimax Technology                 | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 479       | 22.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 143       | 6.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 3.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 72        | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 51        | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 39        | 1.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 37        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 1.53%   |
| Intel Wireless 8265 / 8275                                        | 30        | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 1.21%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 25        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                   | 25        | 1.16%   |
| Intel Wireless 7265                                               | 25        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 1.12%   |
| Intel Wi-Fi 6 AX200                                               | 23        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 20        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.88%   |
| Intel Wireless 7260                                               | 19        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                     | 19        | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 16        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 16        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.74%   |
| Intel Wireless 8260                                               | 15        | 0.7%    |
| Intel Wi-Fi 6 AX201                                               | 15        | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 14        | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                   | 14        | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 14        | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 13        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 321       | 30.87%  |
| Qualcomm Atheros                | 279       | 26.83%  |
| Realtek Semiconductor           | 232       | 22.31%  |
| Broadcom                        | 70        | 6.73%   |
| Ralink Technology               | 38        | 3.65%   |
| TP-Link                         | 25        | 2.4%    |
| MediaTek                        | 22        | 2.12%   |
| Qualcomm Atheros Communications | 14        | 1.35%   |
| Ralink                          | 13        | 1.25%   |
| Broadcom Limited                | 13        | 1.25%   |
| D-Link                          | 4         | 0.38%   |
| AboCom Systems                  | 3         | 0.29%   |
| Sierra Wireless                 | 2         | 0.19%   |
| D-Link System                   | 2         | 0.19%   |
| Edimax Technology               | 1         | 0.1%    |
| ASUSTek Computer                | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 81        | 7.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 72        | 6.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 51        | 4.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 37        | 3.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 3.15%   |
| Intel Wireless 8265 / 8275                                     | 30        | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 2.48%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 25        | 2.39%   |
| Ralink MT7601U Wireless Adapter                                | 25        | 2.39%   |
| Intel Wireless 7265                                            | 25        | 2.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 24        | 2.29%   |
| Intel Wi-Fi 6 AX200                                            | 23        | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 20        | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 20        | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.81%   |
| Intel Wireless 7260                                            | 19        | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 19        | 1.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 16        | 1.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16        | 1.53%   |
| Intel Wireless 8260                                            | 15        | 1.43%   |
| Intel Wi-Fi 6 AX201                                            | 15        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                | 14        | 1.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 14        | 1.34%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 13        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 1.05%   |
| Intel Wireless 3165                                            | 11        | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 10        | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.76%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 6         | 0.57%   |
| Realtek 802.11n WLAN Adapter                                   | 6         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 646       | 60.21%  |
| Intel                            | 174       | 16.22%  |
| Qualcomm Atheros                 | 79        | 7.36%   |
| Broadcom                         | 44        | 4.1%    |
| Xiaomi                           | 26        | 2.42%   |
| Samsung Electronics              | 14        | 1.3%    |
| Marvell Technology Group         | 10        | 0.93%   |
| MediaTek                         | 9         | 0.84%   |
| OPPO Electronics                 | 8         | 0.75%   |
| JMicron Technology               | 6         | 0.56%   |
| IBM                              | 6         | 0.56%   |
| Broadcom Limited                 | 6         | 0.56%   |
| ASIX Electronics                 | 6         | 0.56%   |
| TP-Link                          | 5         | 0.47%   |
| Qualcomm                         | 5         | 0.47%   |
| Nvidia                           | 4         | 0.37%   |
| Silicon Integrated Systems [SiS] | 3         | 0.28%   |
| Attansic Technology              | 3         | 0.28%   |
| Lenovo                           | 2         | 0.19%   |
| ICS Advent                       | 2         | 0.19%   |
| Huawei Technologies              | 2         | 0.19%   |
| HMD Global                       | 2         | 0.19%   |
| Hewlett-Packard                  | 2         | 0.19%   |
| D-Link System                    | 2         | 0.19%   |
| vivo                             | 1         | 0.09%   |
| VIA Technologies                 | 1         | 0.09%   |
| QinHeng Electronics              | 1         | 0.09%   |
| Microchip Technology             | 1         | 0.09%   |
| HTC (High Tech Computer)         | 1         | 0.09%   |
| Foxconn / Hon Hai                | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 479       | 43.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 143       | 13.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 39        | 3.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 1.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.1%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.92%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 8         | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.64%   |
| MediaTek TECNO SPARK 9T                                           | 7         | 0.64%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 6         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 0.55%   |
| IBM RNDIS/Ethernet Gadget                                         | 6         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.37%   |
| Qualcomm Fairphone 4 5G                                           | 4         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.37%   |
| Intel Ethernet Connection X722 for 1GbE                           | 4         | 0.37%   |
| Intel Ethernet Connection X722                                    | 4         | 0.37%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.37%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 993       | 50.03%  |
| Ethernet | 980       | 49.37%  |
| Modem    | 12        | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 834       | 73.16%  |
| Ethernet | 304       | 26.67%  |
| Modem    | 2         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 698       | 59.86%  |
| 1     | 416       | 35.68%  |
| 0     | 24        | 2.06%   |
| 3     | 16        | 1.37%   |
| 4     | 10        | 0.86%   |
| 8     | 1         | 0.09%   |
| 6     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1106      | 94.05%  |
| Yes  | 70        | 5.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 34.42%  |
| Realtek Semiconductor           | 120       | 16.33%  |
| Qualcomm Atheros Communications | 75        | 10.2%   |
| IMC Networks                    | 72        | 9.8%    |
| Lite-On Technology              | 55        | 7.48%   |
| Broadcom                        | 41        | 5.58%   |
| Cambridge Silicon Radio         | 39        | 5.31%   |
| Foxconn / Hon Hai               | 26        | 3.54%   |
| Apple                           | 12        | 1.63%   |
| Toshiba                         | 10        | 1.36%   |
| Dell                            | 7         | 0.95%   |
| Ralink                          | 5         | 0.68%   |
| Hewlett-Packard                 | 4         | 0.54%   |
| Foxconn International           | 4         | 0.54%   |
| Realtek                         | 3         | 0.41%   |
| MediaTek                        | 3         | 0.41%   |
| ASUSTek Computer                | 3         | 0.41%   |
| Micro Star International        | 2         | 0.27%   |
| Chicony Electronics             | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 101       | 13.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 67        | 9.12%   |
| Realtek Bluetooth Radio                             | 58        | 7.89%   |
| IMC Networks Bluetooth Device                       | 48        | 6.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 5.31%   |
| Qualcomm Atheros  Bluetooth Device                  | 35        | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 33        | 4.49%   |
| Intel AX201 Bluetooth                               | 31        | 4.22%   |
| Intel AX200 Bluetooth                               | 23        | 3.13%   |
| Lite-On Bluetooth Device                            | 20        | 2.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 2.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.63%   |
| Realtek RTL8723B Bluetooth                          | 11        | 1.5%    |
| Realtek RTL8821A Bluetooth                          | 10        | 1.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.36%   |
| Lite-On Wireless_Device                             | 9         | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 1.09%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.09%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 8         | 1.09%   |
| Intel Bluetooth Device                              | 7         | 0.95%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.82%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.82%   |
| Apple Bluetooth Host Controller                     | 6         | 0.82%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.68%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.54%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.54%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.54%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.54%   |
| Realtek Bluetooth Radio                             | 3         | 0.41%   |
| MediaTek Wireless_Device                            | 3         | 0.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.41%   |
| Intel AX210 Bluetooth                               | 3         | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 827       | 61.49%  |
| AMD                              | 327       | 24.31%  |
| Nvidia                           | 136       | 10.11%  |
| C-Media Electronics              | 10        | 0.74%   |
| Generalplus Technology           | 8         | 0.59%   |
| JMTek                            | 5         | 0.37%   |
| Silicon Integrated Systems [SiS] | 4         | 0.3%    |
| Samson Technologies              | 3         | 0.22%   |
| Creative Labs                    | 3         | 0.22%   |
| Samsung Electronics              | 2         | 0.15%   |
| Logitech                         | 2         | 0.15%   |
| KTMicro                          | 2         | 0.15%   |
| Barco Display Systems            | 2         | 0.15%   |
| ASUSTek Computer                 | 2         | 0.15%   |
| Texas Instruments                | 1         | 0.07%   |
| SteelSeries ApS                  | 1         | 0.07%   |
| Sony                             | 1         | 0.07%   |
| Solid State Logic                | 1         | 0.07%   |
| SAVITECH                         | 1         | 0.07%   |
| Razer USA                        | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| FDUCE PRO AUDIO MADE             | 1         | 0.07%   |
| Creative Technology              | 1         | 0.07%   |
| Cooler Master                    | 1         | 0.07%   |
| Conexant Systems                 | 1         | 0.07%   |
| BR23                             | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 125       | 7.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 102       | 5.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 94        | 5.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 88        | 5.12%   |
| AMD FCH Azalia Controller                                                                         | 72        | 4.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 56        | 3.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 51        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 48        | 2.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 46        | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 46        | 2.68%   |
| Intel 8 Series HD Audio Controller                                                                | 46        | 2.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 44        | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 43        | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 41        | 2.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 38        | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 38        | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 2.04%   |
| AMD High Definition Audio Controller                                                              | 33        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 32        | 1.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 1.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 27        | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 25        | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 24        | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 20        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 0.81%   |
| AMD Wrestler HDMI Audio                                                                           | 14        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 12        | 0.7%    |
| AMD Trinity HDMI Audio Controller                                                                 | 12        | 0.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 12        | 0.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 0.64%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 214       | 26.58%  |
| SK hynix            | 153       | 19.01%  |
| Micron Technology   | 77        | 9.57%   |
| Unknown             | 73        | 9.07%   |
| Kingston            | 73        | 9.07%   |
| Corsair             | 37        | 4.6%    |
| Team                | 32        | 3.98%   |
| V-GeN               | 23        | 2.86%   |
| Ramaxel Technology  | 21        | 2.61%   |
| Elpida              | 16        | 1.99%   |
| Nanya Technology    | 10        | 1.24%   |
| A-DATA Technology   | 9         | 1.12%   |
| Unknown (ABCD)      | 8         | 0.99%   |
| Unknown             | 8         | 0.99%   |
| G.Skill             | 7         | 0.87%   |
| Crucial             | 5         | 0.62%   |
| Transcend           | 4         | 0.5%    |
| Apacer              | 4         | 0.5%    |
| Visipro             | 3         | 0.37%   |
| Unknown (0x0DD5)    | 2         | 0.25%   |
| Patriot             | 2         | 0.25%   |
| Kingmax             | 2         | 0.25%   |
| Hewlett-Packard     | 2         | 0.25%   |
| ASint Technology    | 2         | 0.25%   |
| A Force             | 2         | 0.25%   |
| Unknown (8AA1)      | 1         | 0.12%   |
| Unknown (8A02)      | 1         | 0.12%   |
| Super Talent        | 1         | 0.12%   |
| Strontium           | 1         | 0.12%   |
| Silicon Power       | 1         | 0.12%   |
| SHARETRONIC         | 1         | 0.12%   |
| Qumo                | 1         | 0.12%   |
| Lexar               | 1         | 0.12%   |
| HPE                 | 1         | 0.12%   |
| GOODRAM             | 1         | 0.12%   |
| Goldkey             | 1         | 0.12%   |
| Foxline             | 1         | 0.12%   |
| ff                  | 1         | 0.12%   |
| Essencore           | 1         | 0.12%   |
| 4ea5                | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 1.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 1.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 1.27%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 1.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.15%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 9         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.92%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.92%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 8         | 0.92%   |
| Unknown                                                          | 8         | 0.92%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 6         | 0.69%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 6         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.69%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.58%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.58%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 5         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.46%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 4         | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.46%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 281       | 44.04%  |
| DDR3    | 268       | 42.01%  |
| LPDDR4  | 24        | 3.76%   |
| DDR2    | 24        | 3.76%   |
| SDRAM   | 15        | 2.35%   |
| Unknown | 12        | 1.88%   |
| LPDDR3  | 7         | 1.1%    |
| LPDDR5  | 4         | 0.63%   |
| DRAM    | 1         | 0.16%   |
| DDR5    | 1         | 0.16%   |
| DDR     | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 470       | 73.21%  |
| DIMM         | 130       | 20.25%  |
| Row Of Chips | 36        | 5.61%   |
| Chip         | 5         | 0.78%   |
| Unknown      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 292       | 40.5%   |
| 8192  | 232       | 32.18%  |
| 2048  | 112       | 15.53%  |
| 16384 | 47        | 6.52%   |
| 32768 | 18        | 2.5%    |
| 1024  | 18        | 2.5%    |
| 65536 | 1         | 0.14%   |
| 512   | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 193       | 26.37%  |
| 2667    | 113       | 15.44%  |
| 3200    | 90        | 12.3%   |
| 2400    | 66        | 9.02%   |
| 1333    | 49        | 6.69%   |
| 2133    | 31        | 4.23%   |
| 1334    | 29        | 3.96%   |
| 3266    | 17        | 2.32%   |
| 1067    | 16        | 2.19%   |
| 800     | 16        | 2.19%   |
| Unknown | 13        | 1.78%   |
| 667     | 11        | 1.5%    |
| 4266    | 7         | 0.96%   |
| 1867    | 7         | 0.96%   |
| 8400    | 6         | 0.82%   |
| 4267    | 5         | 0.68%   |
| 3600    | 5         | 0.68%   |
| 6400    | 4         | 0.55%   |
| 4199    | 4         | 0.55%   |
| 3800    | 4         | 0.55%   |
| 2666    | 4         | 0.55%   |
| 1866    | 4         | 0.55%   |
| 3733    | 3         | 0.41%   |
| 1800    | 3         | 0.41%   |
| 1066    | 3         | 0.41%   |
| 533     | 3         | 0.41%   |
| 333     | 3         | 0.41%   |
| 3151    | 2         | 0.27%   |
| 3000    | 2         | 0.27%   |
| 2048    | 2         | 0.27%   |
| 50410   | 1         | 0.14%   |
| 5200    | 1         | 0.14%   |
| 4040    | 1         | 0.14%   |
| 3866    | 1         | 0.14%   |
| 3666    | 1         | 0.14%   |
| 3534    | 1         | 0.14%   |
| 3533    | 1         | 0.14%   |
| 3466    | 1         | 0.14%   |
| 3400    | 1         | 0.14%   |
| 3333    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 21        | 61.76%  |
| Hewlett-Packard    | 5         | 14.71%  |
| Canon              | 3         | 8.82%   |
| Brother Industries | 3         | 8.82%   |
| STMicroelectronics | 1         | 2.94%   |
| Fuji Xerox         | 1         | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L120 Series          | 6         | 17.65%  |
| Seiko Epson L220 Series          | 5         | 14.71%  |
| Seiko Epson L310 Series          | 3         | 8.82%   |
| Seiko Epson L3110 Series         | 2         | 5.88%   |
| Canon iP2700 series              | 2         | 5.88%   |
| Brother DCP-T300                 | 2         | 5.88%   |
| STMicroelectronics JRSVC Printer | 1         | 2.94%   |
| Seiko Epson L405 Series          | 1         | 2.94%   |
| Seiko Epson L355 Series          | 1         | 2.94%   |
| Seiko Epson L3210 Series         | 1         | 2.94%   |
| Seiko Epson L300 Series          | 1         | 2.94%   |
| Seiko Epson L1300 Series         | 1         | 2.94%   |
| HP LaserJet P1102                | 1         | 2.94%   |
| HP LaserJet P1006                | 1         | 2.94%   |
| HP LaserJet M101-M106            | 1         | 2.94%   |
| HP Ink Tank 110 series           | 1         | 2.94%   |
| HP DeskJet 5820 series           | 1         | 2.94%   |
| Fuji Xerox DocuPrint M205 b      | 1         | 2.94%   |
| Canon LiDE 300                   | 1         | 2.94%   |
| Brother DCP-T310                 | 1         | 2.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 50%     |
| Canon CanoScan 4400F   | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 218       | 27.46%  |
| IMC Networks                           | 107       | 13.48%  |
| Realtek Semiconductor                  | 73        | 9.19%   |
| Quanta                                 | 44        | 5.54%   |
| Sunplus Innovation Technology          | 42        | 5.29%   |
| Syntek                                 | 38        | 4.79%   |
| Bison Electronics                      | 38        | 4.79%   |
| Microdia                               | 34        | 4.28%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 4.16%   |
| Acer                                   | 30        | 3.78%   |
| Alcor Micro                            | 23        | 2.9%    |
| Suyin                                  | 20        | 2.52%   |
| Apple                                  | 12        | 1.51%   |
| Lite-On Technology                     | 10        | 1.26%   |
| Luxvisions Innotech Limited            | 6         | 0.76%   |
| Silicon Motion                         | 5         | 0.63%   |
| Ricoh                                  | 5         | 0.63%   |
| Logitech                               | 5         | 0.63%   |
| Importek                               | 5         | 0.63%   |
| Jieli Technology                       | 4         | 0.5%    |
| Sonix Technology                       | 3         | 0.38%   |
| Lenovo                                 | 3         | 0.38%   |
| Generalplus Technology                 | 3         | 0.38%   |
| GEMBIRD                                | 3         | 0.38%   |
| SN0002                                 | 2         | 0.25%   |
| Primax Electronics                     | 2         | 0.25%   |
| Huawei Technologies                    | 2         | 0.25%   |
| Cubeternet                             | 2         | 0.25%   |
| ANYKA                                  | 2         | 0.25%   |
| ALi                                    | 2         | 0.25%   |
| Unknown                                | 2         | 0.25%   |
| Z-Star Microelectronics                | 1         | 0.13%   |
| webcam                                 | 1         | 0.13%   |
| WCM_USB                                | 1         | 0.13%   |
| Tripath Technology                     | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| Razer USA                              | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| OPPO Electronics                       | 1         | 0.13%   |
| Omnivision                             | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 34        | 4.26%   |
| Chicony HD WebCam                                               | 31        | 3.88%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 30        | 3.76%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 28        | 3.51%   |
| Syntek Integrated Camera                                        | 23        | 2.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 21        | 2.63%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 2.13%   |
| Chicony USB2.0 HD UVC WebCam                                    | 16        | 2.01%   |
| Microdia Integrated_Webcam_HD                                   | 15        | 1.88%   |
| IMC Networks Integrated Camera                                  | 13        | 1.63%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.5%    |
| Chicony HP TrueVision HD Camera                                 | 12        | 1.5%    |
| Realtek USB Camera                                              | 11        | 1.38%   |
| IMC Networks EasyCamera                                         | 11        | 1.38%   |
| Realtek Integrated_Webcam_HD                                    | 10        | 1.25%   |
| Quanta HD User Facing                                           | 10        | 1.25%   |
| Sunplus Asus Webcam                                             | 9         | 1.13%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.13%   |
| Acer Lenovo EasyCamera                                          | 9         | 1.13%   |
| Syntek EasyCamera                                               | 8         | 1%      |
| Quanta VGA WebCam                                               | 8         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 8         | 1%      |
| Bison Integrated Camera                                         | 8         | 1%      |
| Sunplus Integrated_Webcam_HD                                    | 7         | 0.88%   |
| Realtek USB2.0 HD UVC WebCam                                    | 7         | 0.88%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.88%   |
| Microdia Integrated Webcam                                      | 7         | 0.88%   |
| Chicony HP Truevision HD                                        | 7         | 0.88%   |
| Chicony EasyCamera                                              | 7         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.88%   |
| Bison Lenovo EasyCamera                                         | 7         | 0.88%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 0.88%   |
| Acer Integrated Camera                                          | 7         | 0.88%   |
| Suyin 1.3M HD WebCam                                            | 6         | 0.75%   |
| Chicony HD User Facing                                          | 6         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 6         | 0.75%   |
| Bison EasyCamera                                                | 6         | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 6         | 0.75%   |
| Alcor Micro USB 2.0 Camera                                      | 6         | 0.75%   |
| Acer HD Webcam                                                  | 6         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 37        | 29.6%   |
| Synaptics                  | 24        | 19.2%   |
| Elan Microelectronics      | 24        | 19.2%   |
| Shenzhen Goodix Technology | 15        | 12%     |
| LighTuning Technology      | 11        | 8.8%    |
| AuthenTec                  | 6         | 4.8%    |
| Upek                       | 5         | 4%      |
| STMicroelectronics         | 3         | 2.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                           | 12        | 9.6%    |
| Elan ELAN:Fingerprint                                      | 11        | 8.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                | 10        | 8%      |
| Shenzhen Goodix Fingerprint Reader                         | 9         | 7.2%    |
| Validity Sensors VFS 5011 fingerprint sensor               | 8         | 6.4%    |
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 5.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 7         | 5.6%    |
| Shenzhen Goodix  FingerPrint Device                        | 6         | 4.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                | 5         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 4%      |
| Validity Sensors VFS Fingerprint sensor                    | 4         | 3.2%    |
| Validity Sensors Swipe Fingerprint Sensor                  | 4         | 3.2%    |
| Synaptics  WBDI                                            | 4         | 3.2%    |
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 2.4%    |
| Synaptics WBDI                                             | 3         | 2.4%    |
| Synaptics UWP WBDI                                         | 3         | 2.4%    |
| STMicroelectronics Fingerprint Reader                      | 3         | 2.4%    |
| AuthenTec AES1600                                          | 3         | 2.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 1.6%    |
| Validity Sensors VFS491                                    | 2         | 1.6%    |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 1.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 1.6%    |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 1.6%    |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 0.8%    |
| Validity Sensors Synaptics WBDI                            | 1         | 0.8%    |
| Synaptics WBDI Fingerprint Reader USB 102                  | 1         | 0.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.8%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 0.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 0.8%    |
| Elan fingerprint sensor [FeinTech FPS00200]                | 1         | 0.8%    |
| AuthenTec AES2810                                          | 1         | 0.8%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 50%     |
| O2 Micro    | 5         | 16.67%  |
| Upek        | 4         | 13.33%  |
| Alcor Micro | 4         | 13.33%  |
| Lenovo      | 2         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 26.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 13.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.33%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |
| Broadcom 5880                                                                | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 862       | 72.87%  |
| 1     | 247       | 20.88%  |
| 2     | 58        | 4.9%    |
| 3     | 9         | 0.76%   |
| 4     | 5         | 0.42%   |
| 6     | 2         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 123       | 31.54%  |
| Graphics card            | 89        | 22.82%  |
| Net/wireless             | 46        | 11.79%  |
| Chipcard                 | 28        | 7.18%   |
| Multimedia controller    | 24        | 6.15%   |
| Communication controller | 20        | 5.13%   |
| Bluetooth                | 18        | 4.62%   |
| Unassigned class         | 10        | 2.56%   |
| Net/ethernet             | 10        | 2.56%   |
| Camera                   | 8         | 2.05%   |
| Storage                  | 4         | 1.03%   |
| Sound                    | 2         | 0.51%   |
| Flash memory             | 2         | 0.51%   |
| Card reader              | 2         | 0.51%   |
| Wireless                 | 1         | 0.26%   |
| Video                    | 1         | 0.26%   |
| Storage/ide              | 1         | 0.26%   |
| Network                  | 1         | 0.26%   |


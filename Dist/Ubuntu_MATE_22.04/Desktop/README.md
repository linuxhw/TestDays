Ubuntu MATE 22.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 278

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0VHWTR A02                  | [3d32552ab3](https://linux-hardware.org/?probe=3d32552ab3) | Nov 28, 2024 |
| Lenovo        | ThinkStation D20 4158GK1    | [8af2b2f494](https://linux-hardware.org/?probe=8af2b2f494) | Nov 24, 2024 |
| AZW           | MINI S                      | [0fc266941c](https://linux-hardware.org/?probe=0fc266941c) | Nov 22, 2024 |
| Dell          | 0C4H12 A00                  | [53891c4e7e](https://linux-hardware.org/?probe=53891c4e7e) | Nov 10, 2024 |
| Dell          | 0HMX8D A01                  | [715b506ea4](https://linux-hardware.org/?probe=715b506ea4) | Nov 08, 2024 |
| Gigabyte      | G41MT-S2                    | [7705d36266](https://linux-hardware.org/?probe=7705d36266) | Oct 23, 2024 |
| ASUSTek       | M4A78-E                     | [2c29f9d339](https://linux-hardware.org/?probe=2c29f9d339) | Oct 15, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [154b1e5c1b](https://linux-hardware.org/?probe=154b1e5c1b) | Oct 07, 2024 |
| Acer          | EQ45M                       | [0d9b3aab5f](https://linux-hardware.org/?probe=0d9b3aab5f) | Oct 02, 2024 |
| Gigabyte      | H67MA-UD2H-B3               | [21b8f6e55c](https://linux-hardware.org/?probe=21b8f6e55c) | Sep 21, 2024 |
| ASUSTek       | EX-A320M-GAMING             | [846c96bd78](https://linux-hardware.org/?probe=846c96bd78) | Sep 10, 2024 |
| ASRock        | Z77E-ITX                    | [142d4baaa5](https://linux-hardware.org/?probe=142d4baaa5) | Aug 28, 2024 |
| ASUSTek       | X99-DELUXE                  | [a54338842b](https://linux-hardware.org/?probe=a54338842b) | Jul 31, 2024 |
| Gigabyte      | B450M K-CF                  | [f223f80f64](https://linux-hardware.org/?probe=f223f80f64) | Jul 30, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [ba43243222](https://linux-hardware.org/?probe=ba43243222) | Jul 26, 2024 |
| HP            | 2AF7                        | [09f9029668](https://linux-hardware.org/?probe=09f9029668) | Jul 25, 2024 |
| HP            | 2AF7                        | [2d3a654d52](https://linux-hardware.org/?probe=2d3a654d52) | Jul 25, 2024 |
| MSI           | B550 GAMING GEN3            | [b1883fc0b9](https://linux-hardware.org/?probe=b1883fc0b9) | Jul 20, 2024 |
| MSI           | B550 GAMING GEN3            | [938ac7f923](https://linux-hardware.org/?probe=938ac7f923) | Jul 20, 2024 |
| Dell          | 040DDP A01                  | [bf9438a172](https://linux-hardware.org/?probe=bf9438a172) | Jul 17, 2024 |
| Gigabyte      | B550M K                     | [c4a4380ddc](https://linux-hardware.org/?probe=c4a4380ddc) | Jul 11, 2024 |
| Gigabyte      | B460 HD3                    | [324898f64e](https://linux-hardware.org/?probe=324898f64e) | Jul 02, 2024 |
| AMI           | Intel                       | [5d8240cda1](https://linux-hardware.org/?probe=5d8240cda1) | Jun 26, 2024 |
| Dell          | 08NPPY A00                  | [75cff17c2a](https://linux-hardware.org/?probe=75cff17c2a) | Jun 22, 2024 |
| Dell          | 0MWYPT A02                  | [0188202fa9](https://linux-hardware.org/?probe=0188202fa9) | Jun 14, 2024 |
| Dell          | 0NNNCT A01                  | [9cd3c023df](https://linux-hardware.org/?probe=9cd3c023df) | Jun 13, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [720d7ca6cb](https://linux-hardware.org/?probe=720d7ca6cb) | May 31, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [0429104dcc](https://linux-hardware.org/?probe=0429104dcc) | May 30, 2024 |
| ASUSTek       | M5A78L LE                   | [5afe282618](https://linux-hardware.org/?probe=5afe282618) | May 27, 2024 |
| Lenovo        | ThinkStation S30 0606AD5    | [81204f95a0](https://linux-hardware.org/?probe=81204f95a0) | May 15, 2024 |
| ASUSTek       | PRIME B450M-A II            | [2ddbbe35d9](https://linux-hardware.org/?probe=2ddbbe35d9) | May 14, 2024 |
| ASRock        | B650E Taichi                | [cdd2468f64](https://linux-hardware.org/?probe=cdd2468f64) | Apr 20, 2024 |
| Toshiba       | STI 001387                  | [240e193806](https://linux-hardware.org/?probe=240e193806) | Apr 20, 2024 |
| Gigabyte      | H97M-D3H                    | [15a0f07250](https://linux-hardware.org/?probe=15a0f07250) | Apr 20, 2024 |
| ASRock        | J4105B-ITX                  | [ecb84ecf2a](https://linux-hardware.org/?probe=ecb84ecf2a) | Apr 12, 2024 |
| ASUSTek       | H97M-E                      | [431b3ef7f6](https://linux-hardware.org/?probe=431b3ef7f6) | Apr 11, 2024 |
| ASRock        | B650M-H/M.2+                | [38f4136e38](https://linux-hardware.org/?probe=38f4136e38) | Apr 03, 2024 |
| Dell          | 02YRK5 A02                  | [4c860be642](https://linux-hardware.org/?probe=4c860be642) | Mar 29, 2024 |
| Gigabyte      | H87-HD3                     | [39e7b8c321](https://linux-hardware.org/?probe=39e7b8c321) | Mar 22, 2024 |
| Acer          | Aspire XC-886 V:2.0         | [624e1874e9](https://linux-hardware.org/?probe=624e1874e9) | Mar 20, 2024 |
| Gigabyte      | B550 GAMING X V2            | [fc818b5a1b](https://linux-hardware.org/?probe=fc818b5a1b) | Mar 18, 2024 |
| Lenovo        | ThinkStation S30 0606AD5    | [8a703c6f02](https://linux-hardware.org/?probe=8a703c6f02) | Mar 17, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [e2617d5a43](https://linux-hardware.org/?probe=e2617d5a43) | Mar 17, 2024 |
| ASUSTek       | PRIME B760-PLUS             | [bb52ad6052](https://linux-hardware.org/?probe=bb52ad6052) | Mar 15, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [daec1c4210](https://linux-hardware.org/?probe=daec1c4210) | Mar 11, 2024 |
| ASRock        | A320M-HDV R4.0              | [69ef5f3bb0](https://linux-hardware.org/?probe=69ef5f3bb0) | Feb 24, 2024 |
| Biostar       | B450MHP                     | [5c5906ef27](https://linux-hardware.org/?probe=5c5906ef27) | Feb 21, 2024 |
| Biostar       | B450MHP                     | [81eca30554](https://linux-hardware.org/?probe=81eca30554) | Feb 18, 2024 |
| Dell          | OptiPlex 980                | [9554536e5f](https://linux-hardware.org/?probe=9554536e5f) | Feb 18, 2024 |
| Biostar       | B450MHP                     | [1c50343bc4](https://linux-hardware.org/?probe=1c50343bc4) | Feb 17, 2024 |
| Lenovo        | ThinkCentre A58 75227MG     | [bf324db579](https://linux-hardware.org/?probe=bf324db579) | Feb 07, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [7a5a8be027](https://linux-hardware.org/?probe=7a5a8be027) | Jan 25, 2024 |
| Positivo      | POS-EIBTPDC                 | [120ebd1d10](https://linux-hardware.org/?probe=120ebd1d10) | Jan 24, 2024 |
| Gigabyte      | Z370N WIFI-CF               | [01eeec96ca](https://linux-hardware.org/?probe=01eeec96ca) | Jan 16, 2024 |
| ASRock        | X570 Steel Legend           | [192feda06a](https://linux-hardware.org/?probe=192feda06a) | Jan 16, 2024 |
| Gigabyte      | A520I AC                    | [1279f6d244](https://linux-hardware.org/?probe=1279f6d244) | Jan 13, 2024 |
| Lenovo        | ThinkCentre M55e 9645W2C    | [7f8c8e496a](https://linux-hardware.org/?probe=7f8c8e496a) | Jan 02, 2024 |
| ASUSTek       | PRIME B760-PLUS             | [f3149a6f22](https://linux-hardware.org/?probe=f3149a6f22) | Dec 19, 2023 |
| ASUSTek       | PRIME B760-PLUS             | [b7a7aa8d5d](https://linux-hardware.org/?probe=b7a7aa8d5d) | Dec 17, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [991503ccf4](https://linux-hardware.org/?probe=991503ccf4) | Dec 10, 2023 |
| HP            | ProLiant MicroServer        | [5451582602](https://linux-hardware.org/?probe=5451582602) | Dec 08, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [18a5ca0a40](https://linux-hardware.org/?probe=18a5ca0a40) | Dec 07, 2023 |
| Gigabyte      | G41MT-S2                    | [06a0da716b](https://linux-hardware.org/?probe=06a0da716b) | Dec 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Gigabyte      | Z590 UD AC                  | [416fbc3923](https://linux-hardware.org/?probe=416fbc3923) | Nov 28, 2023 |
| ASUSTek       | PRIME Z490-P                | [47d33f722e](https://linux-hardware.org/?probe=47d33f722e) | Nov 25, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [502e296060](https://linux-hardware.org/?probe=502e296060) | Nov 23, 2023 |
| ASRock        | X99 Extreme4                | [dfb480c40a](https://linux-hardware.org/?probe=dfb480c40a) | Nov 17, 2023 |
| ASUSTek       | P8P67-M PRO                 | [9d1c329ebb](https://linux-hardware.org/?probe=9d1c329ebb) | Nov 14, 2023 |
| Lenovo        | T530-28ICB                  | [ba883f99a0](https://linux-hardware.org/?probe=ba883f99a0) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [d2d21dcf50](https://linux-hardware.org/?probe=d2d21dcf50) | Nov 01, 2023 |
| MSI           | A320M PRO-M2 V2             | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| ASRock        | Z370 Killer SLI             | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| HP            | 3646h                       | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| ASRock        | J4105-ITX                   | [f4d4b23c31](https://linux-hardware.org/?probe=f4d4b23c31) | Oct 02, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [b9b34bef50](https://linux-hardware.org/?probe=b9b34bef50) | Oct 02, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [b952cdd71d](https://linux-hardware.org/?probe=b952cdd71d) | Sep 29, 2023 |
| HP            | 8643 SMVB                   | [64f1cd854d](https://linux-hardware.org/?probe=64f1cd854d) | Sep 26, 2023 |
| Foxconn       | 2ABF                        | [2be1547618](https://linux-hardware.org/?probe=2be1547618) | Sep 26, 2023 |
| ASUSTek       | M5A78L-M LX                 | [450edd6547](https://linux-hardware.org/?probe=450edd6547) | Sep 24, 2023 |
| ASRock        | A320M-HD                    | [00ce48a639](https://linux-hardware.org/?probe=00ce48a639) | Sep 19, 2023 |
| Unknown       | X79M2-Q                     | [670ca9e147](https://linux-hardware.org/?probe=670ca9e147) | Sep 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [103e7031fe](https://linux-hardware.org/?probe=103e7031fe) | Sep 14, 2023 |
| Intel         | DH67CL AAG10212-210         | [21932b1004](https://linux-hardware.org/?probe=21932b1004) | Sep 14, 2023 |
| ASUSTek       | P8P67-M PRO                 | [799a135aca](https://linux-hardware.org/?probe=799a135aca) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [7cea54ec70](https://linux-hardware.org/?probe=7cea54ec70) | Sep 13, 2023 |
| ASUSTek       | P8P67-M PRO                 | [6ec67cd2f1](https://linux-hardware.org/?probe=6ec67cd2f1) | Sep 08, 2023 |
| ASUSTek       | H61M-K                      | [0e82099e8f](https://linux-hardware.org/?probe=0e82099e8f) | Sep 01, 2023 |
| MSI           | Z97-G43                     | [74492b4424](https://linux-hardware.org/?probe=74492b4424) | Aug 30, 2023 |
| ASRock        | A320M-HD                    | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Dell          | OptiPlex 5050               | [045411a33d](https://linux-hardware.org/?probe=045411a33d) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| ASRock        | B450M Pro4                  | [cdbe8c2f04](https://linux-hardware.org/?probe=cdbe8c2f04) | Aug 21, 2023 |
| Dell          | OptiPlex 5050               | [e2c9cecddd](https://linux-hardware.org/?probe=e2c9cecddd) | Aug 18, 2023 |
| HP            | 829D                        | [448bb23145](https://linux-hardware.org/?probe=448bb23145) | Aug 15, 2023 |
| Gigabyte      | B85M-D3H                    | [6602bb3d0a](https://linux-hardware.org/?probe=6602bb3d0a) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [5a809fe1c3](https://linux-hardware.org/?probe=5a809fe1c3) | Aug 13, 2023 |
| Biostar       | A10N-8800E                  | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Unknown       | Unknown                     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| Gigabyte      | B85M-D3H                    | [32e3874db3](https://linux-hardware.org/?probe=32e3874db3) | Jul 28, 2023 |
| Lenovo        | 3740 NOK                    | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| Gigabyte      | B85M-D3H                    | [67daf82d15](https://linux-hardware.org/?probe=67daf82d15) | Jul 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| ASUSTek       | PRIME Z590-P                | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| Gigabyte      | G41MT-S2                    | [d625267663](https://linux-hardware.org/?probe=d625267663) | Jul 17, 2023 |
| Gigabyte      | B85M-D3H                    | [1e85aec604](https://linux-hardware.org/?probe=1e85aec604) | Jul 09, 2023 |
| Gigabyte      | B85M-D3H                    | [f73623381d](https://linux-hardware.org/?probe=f73623381d) | Jul 08, 2023 |
| Gigabyte      | B85M-D3H                    | [d37d74ba93](https://linux-hardware.org/?probe=d37d74ba93) | Jul 07, 2023 |
| ASRock        | Z370 Killer SLI             | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| Unknown       | Unknown                     | [23956fd693](https://linux-hardware.org/?probe=23956fd693) | Jul 04, 2023 |
| Gigabyte      | B85M-D3H                    | [ce2d3b5375](https://linux-hardware.org/?probe=ce2d3b5375) | Jul 02, 2023 |
| Gigabyte      | B85M-D3H                    | [0bb17f7e1b](https://linux-hardware.org/?probe=0bb17f7e1b) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| Gigabyte      | B85M-D3H                    | [99b07ae636](https://linux-hardware.org/?probe=99b07ae636) | Jun 30, 2023 |
| Gigabyte      | B85M-D3H                    | [498eb9b539](https://linux-hardware.org/?probe=498eb9b539) | Jun 30, 2023 |
| ASUSTek       | H61M-K                      | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| ASUSTek       | P7P55 LX                    | [e700828afa](https://linux-hardware.org/?probe=e700828afa) | Jun 23, 2023 |
| ASUSTek       | P7P55 LX                    | [cd9b9aae75](https://linux-hardware.org/?probe=cd9b9aae75) | Jun 23, 2023 |
| Gigabyte      | B85M-D3H                    | [033c027010](https://linux-hardware.org/?probe=033c027010) | Jun 18, 2023 |
| Gigabyte      | B85M-D3H                    | [fe0d892e82](https://linux-hardware.org/?probe=fe0d892e82) | Jun 16, 2023 |
| HP            | 8643 SMVB                   | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Gigabyte      | B85M-D3H                    | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| HP            | 1998                        | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Gigabyte      | B85M-D3H                    | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Unknown       | HX90                        | [d38fff55af](https://linux-hardware.org/?probe=d38fff55af) | May 28, 2023 |
| Gigabyte      | B85M-D3H                    | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Acer          | Aspire X1430                | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Gigabyte      | B85M-D3H                    | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| Gigabyte      | B85M-D3H                    | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Gigabyte      | B85M-D3H                    | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| Gigabyte      | P55-UD3                     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Gigabyte      | B85M-D3H                    | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| ASUSTek       | Z170-P                      | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| AMI           | Intel                       | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| AMI           | Intel                       | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| HP            | 1494                        | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| Gigabyte      | B85M-D3H                    | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Gigabyte      | B85M-D3H                    | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Gigabyte      | B85M-D3H                    | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| ASUSTek       | H61M-K                      | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| CCE           | NM70-I                      | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | M5A78L LE                   | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| HP            | 339A                        | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [ee115bdfb8](https://linux-hardware.org/?probe=ee115bdfb8) | Mar 11, 2023 |
| MSI           | X370 SLI PLUS               | [d2ac8dd020](https://linux-hardware.org/?probe=d2ac8dd020) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | [adce83e80e](https://linux-hardware.org/?probe=adce83e80e) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | [9178ffc6f9](https://linux-hardware.org/?probe=9178ffc6f9) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| Gigabyte      | B85M-D3H                    | [9f5aaa2900](https://linux-hardware.org/?probe=9f5aaa2900) | Mar 04, 2023 |
| ASUSTek       | M5A78L-M LX                 | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| Gigabyte      | B85M-D3H                    | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| ASUSTek       | PRIME B360M-C               | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Gigabyte      | B85M-D3H                    | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Gigabyte      | H510M H                     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| HP            | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP            | ProLiant ML350p Gen8        | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Gigabyte      | B85M-D3H                    | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Dell          | 0J1C3P A00                  | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| ASRock        | B550M-ITX/ac                | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| ASRock        | 990FX Extreme3              | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| HP            | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI           | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock        | Z77 Extreme4                | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| ASUSTek       | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| MSI           | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| MSI           | H81M-P33                    | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| MSI           | 870-G45                     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire X3950                | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| HP            | 2ADC                        | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| HP            | 18E4                        | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| AZW           | GK55                        | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| MSI           | H170M PRO-VDH               | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| MSI           | MS-77311                    | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 8433 11                     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Dell          | 0KWVT8 A03                  | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| MSI           | 2AE0                        | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Medion        | MS-7797                     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Dell          | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Gigabyte      | Z87-HD3                     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP            | 3646h                       | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| Acer          | Aspire X3950                | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| HP            | 3397                        | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Unknown       | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP            | 8433 11                     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| Gigabyte      | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.15.0-56-generic  | 13       | 6.53%   |
| 5.15.0-47-generic  | 11       | 5.53%   |
| 6.2.0-26-generic   | 7        | 3.52%   |
| 5.15.0-67-generic  | 7        | 3.52%   |
| 5.15.0-48-generic  | 7        | 3.52%   |
| 6.2.0-32-generic   | 6        | 3.02%   |
| 5.15.0-76-generic  | 5        | 2.51%   |
| 5.15.0-60-generic  | 5        | 2.51%   |
| 5.15.0-50-generic  | 5        | 2.51%   |
| 6.5.0-35-generic   | 4        | 2.01%   |
| 6.5.0-14-generic   | 4        | 2.01%   |
| 5.19.0-32-generic  | 4        | 2.01%   |
| 5.15.0-52-generic  | 4        | 2.01%   |
| 5.15.0-25-generic  | 4        | 2.01%   |
| 5.15.0-101-generic | 4        | 2.01%   |
| 6.5.0-27-generic   | 3        | 1.51%   |
| 6.5.0-25-generic   | 3        | 1.51%   |
| 6.2.0-37-generic   | 3        | 1.51%   |
| 5.19.0-38-generic  | 3        | 1.51%   |
| 5.15.0-94-generic  | 3        | 1.51%   |
| 5.15.0-89-generic  | 3        | 1.51%   |
| 5.15.0-46-generic  | 3        | 1.51%   |
| 5.15.0-40-generic  | 3        | 1.51%   |
| 5.15.0-27-generic  | 3        | 1.51%   |
| 6.8.0-45-generic   | 2        | 1.01%   |
| 6.5.0-41-generic   | 2        | 1.01%   |
| 6.5.0-28-generic   | 2        | 1.01%   |
| 6.2.0-39-generic   | 2        | 1.01%   |
| 6.2.0-35-generic   | 2        | 1.01%   |
| 6.2.0-33-generic   | 2        | 1.01%   |
| 5.19.0-35-generic  | 2        | 1.01%   |
| 5.15.0-84-generic  | 2        | 1.01%   |
| 5.15.0-82-generic  | 2        | 1.01%   |
| 5.15.0-71-generic  | 2        | 1.01%   |
| 5.15.0-70-generic  | 2        | 1.01%   |
| 5.15.0-69-generic  | 2        | 1.01%   |
| 5.15.0-58-generic  | 2        | 1.01%   |
| 5.15.0-57-generic  | 2        | 1.01%   |
| 5.15.0-41-generic  | 2        | 1.01%   |
| 5.15.0-37-generic  | 2        | 1.01%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 107      | 61.49%  |
| 6.2.0   | 22       | 12.64%  |
| 6.5.0   | 19       | 10.92%  |
| 5.19.0  | 15       | 8.62%   |
| 6.8.0   | 5        | 2.87%   |
| 5.13.0  | 2        | 1.15%   |
| 6.8.9   | 1        | 0.57%   |
| 6.4.0   | 1        | 0.57%   |
| 5.18.0  | 1        | 0.57%   |
| 5.14.0  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 107      | 61.49%  |
| 6.2     | 22       | 12.64%  |
| 6.5     | 19       | 10.92%  |
| 5.19    | 15       | 8.62%   |
| 6.8     | 6        | 3.45%   |
| 5.13    | 2        | 1.15%   |
| 6.4     | 1        | 0.57%   |
| 5.18    | 1        | 0.57%   |
| 5.14    | 1        | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 169      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 163      | 96.45%  |
| KDE5       | 2        | 1.18%   |
| GNOME      | 2        | 1.18%   |
| X-Cinnamon | 1        | 0.59%   |
| Budgie     | 1        | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 157      | 92.9%   |
| Tty     | 7        | 4.14%   |
| Wayland | 5        | 2.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 135      | 78.95%  |
| GDM3    | 21       | 12.28%  |
| Unknown | 15       | 8.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 62       | 36.69%  |
| fr_FR   | 27       | 15.98%  |
| it_IT   | 15       | 8.88%   |
| de_DE   | 12       | 7.1%    |
| en_AU   | 5        | 2.96%   |
| ru_RU   | 4        | 2.37%   |
| pt_BR   | 4        | 2.37%   |
| en_GB   | 4        | 2.37%   |
| en_CA   | 4        | 2.37%   |
| es_ES   | 3        | 1.78%   |
| de_CH   | 3        | 1.78%   |
| C       | 3        | 1.78%   |
| tr_TR   | 2        | 1.18%   |
| hr_HR   | 2        | 1.18%   |
| es_AR   | 2        | 1.18%   |
| zh_TW   | 1        | 0.59%   |
| pl_PL   | 1        | 0.59%   |
| nl_NL   | 1        | 0.59%   |
| nb_NO   | 1        | 0.59%   |
| hu_HU   | 1        | 0.59%   |
| fi_FI   | 1        | 0.59%   |
| et_EE   | 1        | 0.59%   |
| es_VE   | 1        | 0.59%   |
| es_PE   | 1        | 0.59%   |
| es_MX   | 1        | 0.59%   |
| en_IL   | 1        | 0.59%   |
| el_GR   | 1        | 0.59%   |
| de_AT   | 1        | 0.59%   |
| da_DK   | 1        | 0.59%   |
| cs_CZ   | 1        | 0.59%   |
| ar_KW   | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 96       | 56.14%  |
| EFI  | 75       | 43.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 137      | 76.97%  |
| Tmpfs   | 25       | 14.04%  |
| Overlay | 6        | 3.37%   |
| Btrfs   | 6        | 3.37%   |
| Xfs     | 2        | 1.12%   |
| Zfs     | 1        | 0.56%   |
| Ext2    | 1        | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 123      | 71.1%   |
| Unknown | 27       | 15.61%  |
| MBR     | 23       | 13.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 74.85%  |
| Yes       | 43       | 25.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 59.65%  |
| Yes       | 69       | 40.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 43       | 25.44%  |
| Gigabyte Technology                  | 21       | 12.43%  |
| MSI                                  | 19       | 11.24%  |
| Hewlett-Packard                      | 19       | 11.24%  |
| ASRock                               | 18       | 10.65%  |
| Dell                                 | 14       | 8.28%   |
| Lenovo                               | 10       | 5.92%   |
| Unknown                              | 6        | 3.55%   |
| Acer                                 | 4        | 2.37%   |
| Biostar                              | 2        | 1.18%   |
| AZW                                  | 2        | 1.18%   |
| AMI                                  | 2        | 1.18%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.59%   |
| Semp Toshiba                         | 1        | 0.59%   |
| Positivo                             | 1        | 0.59%   |
| Medion                               | 1        | 0.59%   |
| MACHINIST                            | 1        | 0.59%   |
| Intel                                | 1        | 0.59%   |
| Foxconn                              | 1        | 0.59%   |
| CCE                                  | 1        | 0.59%   |
| 3Logic Group                         | 1        | 0.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 6        | 3.55%   |
| MSI MS-7C56                                 | 2        | 1.18%   |
| HP EliteDesk 800 G1 SFF                     | 2        | 1.18%   |
| HP Desktop M01-F0xxx                        | 2        | 1.18%   |
| HP Compaq Elite 8300 SFF                    | 2        | 1.18%   |
| HP Compaq 8000 Elite SFF PC                 | 2        | 1.18%   |
| Gigabyte B85M-D3H                           | 2        | 1.18%   |
| Dell OptiPlex 3020                          | 2        | 1.18%   |
| ASUS PRIME B760-PLUS                        | 2        | 1.18%   |
| ASUS PRIME B450M-A II                       | 2        | 1.18%   |
| ASUS M5A78L LE                              | 2        | 1.18%   |
| ASUS All Series                             | 2        | 1.18%   |
| ASRock A320M-HDV R4.0                       | 2        | 1.18%   |
| AMI Intel                                   | 2        | 1.18%   |
| Shenzhen Meigao Electronic Equipment HX90G  | 1        | 0.59%   |
| Semp Toshiba STI                            | 1        | 0.59%   |
| Positivo POS-EIBTPDC                        | 1        | 0.59%   |
| MSI p6-2330                                 | 1        | 0.59%   |
| MSI MS-7E07                                 | 1        | 0.59%   |
| MSI MS-7D43                                 | 1        | 0.59%   |
| MSI MS-7C52                                 | 1        | 0.59%   |
| MSI MS-7C37                                 | 1        | 0.59%   |
| MSI MS-7C09                                 | 1        | 0.59%   |
| MSI MS-7C02                                 | 1        | 0.59%   |
| MSI MS-7B86                                 | 1        | 0.59%   |
| MSI MS-7B84                                 | 1        | 0.59%   |
| MSI MS-7A33                                 | 1        | 0.59%   |
| MSI MS-7982                                 | 1        | 0.59%   |
| MSI MS-7918                                 | 1        | 0.59%   |
| MSI MS-7817                                 | 1        | 0.59%   |
| MSI MS-7816                                 | 1        | 0.59%   |
| MSI MS-7758                                 | 1        | 0.59%   |
| MSI MS-7599                                 | 1        | 0.59%   |
| MSI B02311                                  | 1        | 0.59%   |
| Medion MS-7797                              | 1        | 0.59%   |
| MACHINIST E5 MR9A PRO MAX V1.1              | 1        | 0.59%   |
| Lenovo ThinkStation S30 0606AD5             | 1        | 0.59%   |
| Lenovo ThinkStation D20 4158GK1             | 1        | 0.59%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE00A7AX | 1        | 0.59%   |
| Lenovo ThinkCentre M710q 10MQSC0N00         | 1        | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 12       | 7.1%    |
| Dell OptiPlex                              | 8        | 4.73%   |
| HP Compaq                                  | 6        | 3.55%   |
| ASUS ROG                                   | 6        | 3.55%   |
| Unknown                                    | 6        | 3.55%   |
| Lenovo ThinkCentre                         | 4        | 2.37%   |
| HP EliteDesk                               | 4        | 2.37%   |
| Dell Precision                             | 3        | 1.78%   |
| Acer Aspire                                | 3        | 1.78%   |
| MSI MS-7C56                                | 2        | 1.18%   |
| Lenovo ThinkStation                        | 2        | 1.18%   |
| Lenovo IdeaCentre                          | 2        | 1.18%   |
| HP ProLiant                                | 2        | 1.18%   |
| HP ProDesk                                 | 2        | 1.18%   |
| HP Desktop                                 | 2        | 1.18%   |
| Gigabyte B85M-D3H                          | 2        | 1.18%   |
| Gigabyte B450M                             | 2        | 1.18%   |
| ASUS TUF                                   | 2        | 1.18%   |
| ASUS P8Z77-V                               | 2        | 1.18%   |
| ASUS M5A78L-M                              | 2        | 1.18%   |
| ASUS M5A78L                                | 2        | 1.18%   |
| ASUS All                                   | 2        | 1.18%   |
| ASRock A320M-HDV                           | 2        | 1.18%   |
| AMI Intel                                  | 2        | 1.18%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.59%   |
| Semp Toshiba STI                           | 1        | 0.59%   |
| Positivo POS-EIBTPDC                       | 1        | 0.59%   |
| MSI p6-2330                                | 1        | 0.59%   |
| MSI MS-7E07                                | 1        | 0.59%   |
| MSI MS-7D43                                | 1        | 0.59%   |
| MSI MS-7C52                                | 1        | 0.59%   |
| MSI MS-7C37                                | 1        | 0.59%   |
| MSI MS-7C09                                | 1        | 0.59%   |
| MSI MS-7C02                                | 1        | 0.59%   |
| MSI MS-7B86                                | 1        | 0.59%   |
| MSI MS-7B84                                | 1        | 0.59%   |
| MSI MS-7A33                                | 1        | 0.59%   |
| MSI MS-7982                                | 1        | 0.59%   |
| MSI MS-7918                                | 1        | 0.59%   |
| MSI MS-7817                                | 1        | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 19       | 11.24%  |
| 2012 | 19       | 11.24%  |
| 2022 | 14       | 8.28%   |
| 2021 | 14       | 8.28%   |
| 2014 | 12       | 7.1%    |
| 2011 | 12       | 7.1%    |
| 2020 | 11       | 6.51%   |
| 2019 | 11       | 6.51%   |
| 2013 | 11       | 6.51%   |
| 2009 | 10       | 5.92%   |
| 2017 | 9        | 5.33%   |
| 2023 | 8        | 4.73%   |
| 2010 | 6        | 3.55%   |
| 2015 | 5        | 2.96%   |
| 2016 | 3        | 1.78%   |
| 2008 | 2        | 1.18%   |
| 2006 | 2        | 1.18%   |
| 2007 | 1        | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 169      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 161      | 94.71%  |
| Enabled  | 9        | 5.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 169      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 35       | 20.59%  |
| 8.01-16.0   | 32       | 18.82%  |
| 32.01-64.0  | 30       | 17.65%  |
| 4.01-8.0    | 26       | 15.29%  |
| 3.01-4.0    | 19       | 11.18%  |
| 64.01-256.0 | 16       | 9.41%   |
| 24.01-32.0  | 7        | 4.12%   |
| 1.01-2.0    | 4        | 2.35%   |
| 2.01-3.0    | 1        | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 52       | 28.89%  |
| 1.01-2.0   | 52       | 28.89%  |
| 4.01-8.0   | 34       | 18.89%  |
| 3.01-4.0   | 22       | 12.22%  |
| 8.01-16.0  | 13       | 7.22%   |
| 24.01-32.0 | 2        | 1.11%   |
| 16.01-24.0 | 2        | 1.11%   |
| 0.51-1.0   | 2        | 1.11%   |
| 32.01-64.0 | 1        | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 31.76%  |
| 2      | 53       | 31.18%  |
| 3      | 26       | 15.29%  |
| 4      | 19       | 11.18%  |
| 6      | 6        | 3.53%   |
| 5      | 6        | 3.53%   |
| 0      | 2        | 1.18%   |
| 20     | 1        | 0.59%   |
| 9      | 1        | 0.59%   |
| 8      | 1        | 0.59%   |
| 7      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 91       | 53.85%  |
| No        | 78       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 168      | 99.41%  |
| No        | 1        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 54.44%  |
| Yes       | 77       | 45.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 66.86%  |
| Yes       | 56       | 33.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 32       | 18.93%  |
| France       | 27       | 15.98%  |
| Italy        | 16       | 9.47%   |
| Germany      | 14       | 8.28%   |
| Brazil       | 8        | 4.73%   |
| Russia       | 5        | 2.96%   |
| Australia    | 5        | 2.96%   |
| UK           | 4        | 2.37%   |
| Switzerland  | 4        | 2.37%   |
| Poland       | 4        | 2.37%   |
| Canada       | 4        | 2.37%   |
| Spain        | 3        | 1.78%   |
| Portugal     | 3        | 1.78%   |
| Croatia      | 3        | 1.78%   |
| Belgium      | 3        | 1.78%   |
| Austria      | 3        | 1.78%   |
| Argentina    | 3        | 1.78%   |
| Turkey       | 2        | 1.18%   |
| Hungary      | 2        | 1.18%   |
| Greece       | 2        | 1.18%   |
| Finland      | 2        | 1.18%   |
| Denmark      | 2        | 1.18%   |
| Vietnam      | 1        | 0.59%   |
| Venezuela    | 1        | 0.59%   |
| Uruguay      | 1        | 0.59%   |
| Ukraine      | 1        | 0.59%   |
| Taiwan       | 1        | 0.59%   |
| Saudi Arabia | 1        | 0.59%   |
| Peru         | 1        | 0.59%   |
| Norway       | 1        | 0.59%   |
| New Zealand  | 1        | 0.59%   |
| Netherlands  | 1        | 0.59%   |
| Morocco      | 1        | 0.59%   |
| Moldova      | 1        | 0.59%   |
| Mexico       | 1        | 0.59%   |
| Israel       | 1        | 0.59%   |
| Isle of Man  | 1        | 0.59%   |
| Estonia      | 1        | 0.59%   |
| Czechia      | 1        | 0.59%   |
| Algeria      | 1        | 0.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Rome              | 4        | 2.21%   |
| Ozarow Mazowiecki | 3        | 1.66%   |
| Zagreb            | 2        | 1.1%    |
| St Petersburg     | 2        | 1.1%    |
| Paris             | 2        | 1.1%    |
| Melbourne         | 2        | 1.1%    |
| Los Angeles       | 2        | 1.1%    |
| Lansdale          | 2        | 1.1%    |
| Forlì            | 2        | 1.1%    |
| Bologna           | 2        | 1.1%    |
| Berlin            | 2        | 1.1%    |
| Zottegem          | 1        | 0.55%   |
| York              | 1        | 0.55%   |
| Yonkers           | 1        | 0.55%   |
| Wuelfrath         | 1        | 0.55%   |
| Wittingen         | 1        | 0.55%   |
| Wintzenheim       | 1        | 0.55%   |
| Wilmington        | 1        | 0.55%   |
| Whanganui         | 1        | 0.55%   |
| Washington        | 1        | 0.55%   |
| Warsaw            | 1        | 0.55%   |
| Villefontaine     | 1        | 0.55%   |
| Viljandi          | 1        | 0.55%   |
| Viana do Castelo  | 1        | 0.55%   |
| Versailles        | 1        | 0.55%   |
| Velyki Mosty      | 1        | 0.55%   |
| Vancouver         | 1        | 0.55%   |
| Untersiggenthal   | 1        | 0.55%   |
| Uberaba           | 1        | 0.55%   |
| Turku             | 1        | 0.55%   |
| Trondheim         | 1        | 0.55%   |
| Toulouse          | 1        | 0.55%   |
| Toulon            | 1        | 0.55%   |
| Torring           | 1        | 0.55%   |
| Tighina           | 1        | 0.55%   |
| Terrace           | 1        | 0.55%   |
| Tel Aviv          | 1        | 0.55%   |
| Taranto           | 1        | 0.55%   |
| Tampere           | 1        | 0.55%   |
| Talence           | 1        | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 65       | 114    | 21.74%  |
| Seagate                     | 49       | 87     | 16.39%  |
| Samsung Electronics         | 45       | 88     | 15.05%  |
| Crucial                     | 20       | 27     | 6.69%   |
| Kingston                    | 18       | 26     | 6.02%   |
| Toshiba                     | 13       | 40     | 4.35%   |
| SanDisk                     | 13       | 16     | 4.35%   |
| Hitachi                     | 7        | 9      | 2.34%   |
| Unknown                     | 6        | 14     | 2.01%   |
| A-DATA Technology           | 5        | 6      | 1.67%   |
| Phison                      | 4        | 4      | 1.34%   |
| Intel                       | 4        | 4      | 1.34%   |
| SPCC                        | 3        | 5      | 1%      |
| Phison Electronics          | 3        | 3      | 1%      |
| China                       | 3        | 3      | 1%      |
| Team                        | 2        | 2      | 0.67%   |
| SK hynix                    | 2        | 2      | 0.67%   |
| PNY                         | 2        | 2      | 0.67%   |
| LDLC                        | 2        | 2      | 0.67%   |
| KingSpec                    | 2        | 2      | 0.67%   |
| KingFast                    | 2        | 2      | 0.67%   |
| Hewlett-Packard             | 2        | 5      | 0.67%   |
| ASMT                        | 2        | 3      | 0.67%   |
| Apacer                      | 2        | 2      | 0.67%   |
| Transcend                   | 1        | 5      | 0.33%   |
| T-FORCE                     | 1        | 1      | 0.33%   |
| RZX                         | 1        | 1      | 0.33%   |
| Realtek Semiconductor       | 1        | 1      | 0.33%   |
| Pichau                      | 1        | 1      | 0.33%   |
| Patriot                     | 1        | 1      | 0.33%   |
| OCZ                         | 1        | 1      | 0.33%   |
| NGFF                        | 1        | 1      | 0.33%   |
| Maxtor                      | 1        | 1      | 0.33%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.33%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.33%   |
| Kingston Technology Company | 1        | 1      | 0.33%   |
| Kimtigo                     | 1        | 1      | 0.33%   |
| KESU                        | 1        | 1      | 0.33%   |
| Intenso                     | 1        | 1      | 0.33%   |
| HGST                        | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 6        | 1.6%    |
| Seagate ST500DM002-1BD142 500GB                     | 6        | 1.6%    |
| Seagate ST1000DM003-1ER162 1TB                      | 5        | 1.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5        | 1.33%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.06%   |
| Crucial CT1000BX500SSD1 1TB                         | 4        | 1.06%   |
| WDC WD5003AZEX-00K3CA0 500GB                        | 3        | 0.8%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 3        | 0.8%    |
| Unknown SD/MMC 1073GB                               | 3        | 0.8%    |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 0.8%    |
| Unknown Compact Flash 977MB                         | 3        | 0.8%    |
| Seagate ST4000DM004-2CV104 4TB                      | 3        | 0.8%    |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.8%    |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 0.8%    |
| Samsung SSD 870 QVO 1TB                             | 3        | 0.8%    |
| Samsung SSD 870 EVO 500GB                           | 3        | 0.8%    |
| Samsung SSD 850 EVO 500GB                           | 3        | 0.8%    |
| Kingston SA400S37480G 480GB SSD                     | 3        | 0.8%    |
| Crucial CT480BX500SSD1 480GB                        | 3        | 0.8%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 2        | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2        | 0.53%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2        | 0.53%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2        | 0.53%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 2        | 0.53%   |
| Toshiba HDWD130 3TB                                 | 2        | 0.53%   |
| Toshiba DT01ACA100 1TB                              | 2        | 0.53%   |
| Toshiba DT01ACA050 500GB                            | 2        | 0.53%   |
| Seagate ST9500325AS 500GB                           | 2        | 0.53%   |
| Seagate ST3500312CS 500GB                           | 2        | 0.53%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.53%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 0.53%   |
| Samsung SSD 980 PRO 2TB                             | 2        | 0.53%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 0.53%   |
| Samsung SSD 980 1TB                                 | 2        | 0.53%   |
| Samsung SSD 870 QVO 2TB                             | 2        | 0.53%   |
| Samsung SSD 860 QVO 1TB                             | 2        | 0.53%   |
| Samsung SSD 860 PRO 256GB                           | 2        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.53%   |
| Samsung SSD 840 Series 120GB                        | 2        | 0.53%   |
| Samsung SSD 840 EVO 500GB                           | 2        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 60       | 105    | 42.55%  |
| Seagate             | 49       | 87     | 34.75%  |
| Toshiba             | 10       | 35     | 7.09%   |
| Samsung Electronics | 7        | 15     | 4.96%   |
| Hitachi             | 7        | 9      | 4.96%   |
| Hewlett-Packard     | 2        | 5      | 1.42%   |
| ASMT                | 2        | 3      | 1.42%   |
| Maxtor              | 1        | 1      | 0.71%   |
| KESU                | 1        | 1      | 0.71%   |
| HGST                | 1        | 1      | 0.71%   |
| DAS                 | 1        | 6      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 45     | 26.17%  |
| Crucial             | 18       | 24     | 16.82%  |
| Kingston            | 13       | 21     | 12.15%  |
| SanDisk             | 7        | 9      | 6.54%   |
| WDC                 | 6        | 6      | 5.61%   |
| SPCC                | 3        | 5      | 2.8%    |
| China               | 3        | 3      | 2.8%    |
| A-DATA Technology   | 3        | 3      | 2.8%    |
| Toshiba             | 2        | 4      | 1.87%   |
| LDLC                | 2        | 2      | 1.87%   |
| KingSpec            | 2        | 2      | 1.87%   |
| KingFast            | 2        | 2      | 1.87%   |
| Apacer              | 2        | 2      | 1.87%   |
| Unknown             | 1        | 1      | 0.93%   |
| Transcend           | 1        | 5      | 0.93%   |
| Team                | 1        | 1      | 0.93%   |
| T-FORCE             | 1        | 1      | 0.93%   |
| RZX                 | 1        | 1      | 0.93%   |
| PNY                 | 1        | 1      | 0.93%   |
| Pichau              | 1        | 1      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 1      | 0.93%   |
| NGFF                | 1        | 1      | 0.93%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.93%   |
| Intel               | 1        | 1      | 0.93%   |
| GOODRAM             | 1        | 1      | 0.93%   |
| FORESEE             | 1        | 1      | 0.93%   |
| BAITITON            | 1        | 1      | 0.93%   |
| Unknown             | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 114      | 268    | 44.19%  |
| SSD     | 89       | 148    | 34.5%   |
| NVMe    | 49       | 69     | 18.99%  |
| Unknown | 4        | 16     | 1.55%   |
| MMC     | 2        | 2      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 150      | 396    | 70.09%  |
| NVMe | 49       | 69     | 22.9%   |
| SAS  | 13       | 36     | 6.07%   |
| MMC  | 2        | 2      | 0.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 107      | 190    | 45.53%  |
| 0.51-1.0   | 66       | 114    | 28.09%  |
| 1.01-2.0   | 29       | 37     | 12.34%  |
| 3.01-4.0   | 17       | 25     | 7.23%   |
| 4.01-10.0  | 9        | 39     | 3.83%   |
| 2.01-3.0   | 7        | 11     | 2.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 35       | 20.11%  |
| 101-250        | 33       | 18.97%  |
| More than 3000 | 32       | 18.39%  |
| 251-500        | 29       | 16.67%  |
| 1001-2000      | 20       | 11.49%  |
| 2001-3000      | 7        | 4.02%   |
| 51-100         | 7        | 4.02%   |
| 1-20           | 5        | 2.87%   |
| 21-50          | 4        | 2.3%    |
| Unknown        | 2        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 34       | 18.89%  |
| 101-250        | 30       | 16.67%  |
| 21-50          | 26       | 14.44%  |
| 51-100         | 20       | 11.11%  |
| More than 3000 | 19       | 10.56%  |
| 1001-2000      | 16       | 8.89%   |
| 251-500        | 14       | 7.78%   |
| 501-1000       | 14       | 7.78%   |
| 2001-3000      | 5        | 2.78%   |
| Unknown        | 2        | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                 | Desktops | Drives | Percent |
|-------------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 2        | 2      | 6.67%   |
| WDC WD5000AAKX-22ERMA0 500GB                          | 1        | 1      | 3.33%   |
| WDC WD5000AAKS-00V1A0 500GB                           | 1        | 1      | 3.33%   |
| WDC WD5000AADS-00S9B0 500GB                           | 1        | 1      | 3.33%   |
| WDC WD4000FYYZ-01UL1B3 4TB                            | 1        | 1      | 3.33%   |
| WDC WD40 EFRX-68WT0N0 4TB                             | 1        | 1      | 3.33%   |
| WDC WD2500AVJS-63B6A0 250GB                           | 1        | 1      | 3.33%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 1        | 1      | 3.33%   |
| WDC WD10EAVS-00D7B0 1TB                               | 1        | 1      | 3.33%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 1        | 1      | 3.33%   |
| Seagate ST9640320AS 640GB                             | 1        | 1      | 3.33%   |
| Seagate ST9500325AS 500GB                             | 1        | 1      | 3.33%   |
| Seagate ST9160821AS 160GB                             | 1        | 1      | 3.33%   |
| Seagate ST3250312AS 250GB                             | 1        | 1      | 3.33%   |
| Seagate ST32000644NS 2TB                              | 1        | 1      | 3.33%   |
| Seagate ST250DM000-1BD141 250GB                       | 1        | 1      | 3.33%   |
| Seagate ST2000DM001-1ER164 2TB                        | 1        | 1      | 3.33%   |
| Seagate ST1000DM003-1ER162 1TB                        | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 970 EVO 500GB S466NX0K863648L | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 960 PRO 1TB                   | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB                   | 1        | 1      | 3.33%   |
| OCZ AGILITY3 240GB SSD                                | 1        | 1      | 3.33%   |
| NGFF 2280 256GB SSD                                   | 1        | 1      | 3.33%   |
| LDLC SSD 120GB                                        | 1        | 1      | 3.33%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD               | 1        | 1      | 3.33%   |
| Hitachi HTS721080G9SA00 80GB                          | 1        | 1      | 3.33%   |
| Hitachi HTS547550A9E384 500GB                         | 1        | 1      | 3.33%   |
| DAS TerraMaster 6TB                                   | 1        | 3      | 3.33%   |
| China SSD 180GB                                       | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 10     | 34.48%  |
| WDC                 | 8        | 9      | 27.59%  |
| Samsung Electronics | 3        | 3      | 10.34%  |
| Hitachi             | 2        | 2      | 6.9%    |
| OCZ                 | 1        | 1      | 3.45%   |
| NGFF                | 1        | 1      | 3.45%   |
| LDLC                | 1        | 1      | 3.45%   |
| Kingston            | 1        | 1      | 3.45%   |
| DAS                 | 1        | 3      | 3.45%   |
| China               | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 10     | 47.62%  |
| WDC     | 8        | 9      | 38.1%   |
| Hitachi | 2        | 2      | 9.52%   |
| DAS     | 1        | 3      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 24     | 70.37%  |
| SSD  | 6        | 6      | 22.22%  |
| NVMe | 2        | 2      | 7.41%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 103      | 278    | 51.5%   |
| Detected | 70       | 193    | 35%     |
| Malfunc  | 27       | 32     | 13.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 111      | 46.84%  |
| AMD                          | 58       | 24.47%  |
| Samsung Electronics          | 17       | 7.17%   |
| Phison Electronics           | 10       | 4.22%   |
| ASMedia Technology           | 10       | 4.22%   |
| SanDisk                      | 8        | 3.38%   |
| Kingston Technology Company  | 6        | 2.53%   |
| JMicron Technology           | 3        | 1.27%   |
| SK hynix                     | 2        | 0.84%   |
| Micron/Crucial Technology    | 2        | 0.84%   |
| Marvell Technology Group     | 2        | 0.84%   |
| ADATA Technology             | 2        | 0.84%   |
| Toshiba America Info Systems | 1        | 0.42%   |
| Silicon Motion               | 1        | 0.42%   |
| Realtek Semiconductor        | 1        | 0.42%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.42%   |
| LSI Logic / Symbios Logic    | 1        | 0.42%   |
| Hewlett-Packard              | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32       | 10.67%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 4%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12       | 4%      |
| AMD 400 Series Chipset SATA Controller                                         | 12       | 4%      |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10       | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 2.67%   |
| Intel SATA Controller [RAID mode]                                              | 8        | 2.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8        | 2.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8        | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8        | 2.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 2.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6        | 2%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6        | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 2%      |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 6        | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5        | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5        | 1.67%   |
| AMD 600 Series Chipset SATA Controller                                         | 5        | 1.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 1.33%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 3        | 1%      |
| Intel Volume Management Device NVMe RAID Controller                            | 3        | 1%      |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 1%      |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 3        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1%      |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1%      |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2        | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.67%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2        | 0.67%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 0.67%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 0.67%   |
| Phison E8 PCIe3 x2 NVMe Controller                                             | 2        | 0.67%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.67%   |
| Phison E12 NVMe Controller                                                     | 2        | 0.67%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 0.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 141      | 58.02%  |
| NVMe | 49       | 20.16%  |
| IDE  | 35       | 14.4%   |
| RAID | 17       | 7%      |
| SCSI | 1        | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 111      | 65.68%  |
| AMD    | 58       | 34.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics        | 4        | 2.37%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 3        | 1.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3        | 1.78%   |
| Intel Celeron J4105 CPU @ 1.50GHz             | 3        | 1.78%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3        | 1.78%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3        | 1.78%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 1.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2        | 1.18%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2        | 1.18%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 2        | 1.18%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2        | 1.18%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2        | 1.18%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2        | 1.18%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 2        | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2        | 1.18%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 2        | 1.18%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 2        | 1.18%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.18%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 2        | 1.18%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz       | 2        | 1.18%   |
| AMD Ryzen 7 7700 8-Core Processor             | 2        | 1.18%   |
| AMD Ryzen 5 5500                              | 2        | 1.18%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2        | 1.18%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2        | 1.18%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 1.18%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2        | 1.18%   |
| AMD FX-6300 Six-Core Processor                | 2        | 1.18%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 2        | 1.18%   |
| Intel Xeon D-2796TE CPU @ 2.00GHz             | 1        | 0.59%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1        | 0.59%   |
| Intel Xeon CPU E5-4640 0 @ 2.40GHz            | 1        | 0.59%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz           | 1        | 0.59%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz           | 1        | 0.59%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz            | 1        | 0.59%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1        | 0.59%   |
| Intel Xeon CPU E3120 @ 3.16GHz                | 1        | 0.59%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1        | 0.59%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz           | 1        | 0.59%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1        | 0.59%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 22.49%  |
| AMD Ryzen 5             | 18       | 10.65%  |
| Intel Core i7           | 17       | 10.06%  |
| Other                   | 14       | 8.28%   |
| Intel Xeon              | 10       | 5.92%   |
| Intel Core i3           | 9        | 5.33%   |
| Intel Celeron           | 8        | 4.73%   |
| AMD Ryzen 7             | 8        | 4.73%   |
| AMD Ryzen 9             | 6        | 3.55%   |
| AMD FX                  | 6        | 3.55%   |
| AMD Ryzen 3             | 5        | 2.96%   |
| Intel Pentium           | 4        | 2.37%   |
| Intel Core 2 Duo        | 4        | 2.37%   |
| AMD A8                  | 3        | 1.78%   |
| Intel Pentium Dual-Core | 2        | 1.18%   |
| Intel Core 2 Quad       | 2        | 1.18%   |
| AMD E                   | 2        | 1.18%   |
| AMD Athlon II X2        | 2        | 1.18%   |
| Intel Pentium D         | 1        | 0.59%   |
| Intel Pentium 4         | 1        | 0.59%   |
| Intel Core i9           | 1        | 0.59%   |
| AMD Turion II Neo       | 1        | 0.59%   |
| AMD Phenom II X6        | 1        | 0.59%   |
| AMD Phenom II X4        | 1        | 0.59%   |
| AMD Athlon II X4        | 1        | 0.59%   |
| AMD Athlon              | 1        | 0.59%   |
| AMD A6                  | 1        | 0.59%   |
| AMD A4                  | 1        | 0.59%   |
| AMD A10                 | 1        | 0.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 59       | 34.91%  |
| 2      | 37       | 21.89%  |
| 6      | 36       | 21.3%   |
| 8      | 18       | 10.65%  |
| 12     | 4        | 2.37%   |
| 16     | 3        | 1.78%   |
| 3      | 3        | 1.78%   |
| 1      | 3        | 1.78%   |
| 20     | 2        | 1.18%   |
| 10     | 2        | 1.18%   |
| 24     | 1        | 0.59%   |
| 14     | 1        | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 167      | 98.82%  |
| 2      | 2        | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 97       | 57.4%   |
| 1      | 72       | 42.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 169      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 86       | 50%     |
| 0x306c3    | 10       | 5.81%   |
| 0x206a7    | 6        | 3.49%   |
| 0xa0671    | 5        | 2.91%   |
| 0x906ea    | 5        | 2.91%   |
| 0x506e3    | 5        | 2.91%   |
| 0x306a9    | 5        | 2.91%   |
| 0x0a50000c | 4        | 2.33%   |
| 0x0800820d | 4        | 2.33%   |
| 0x706a1    | 3        | 1.74%   |
| 0x08701021 | 3        | 1.74%   |
| 0x08108109 | 3        | 1.74%   |
| 0xa0653    | 2        | 1.16%   |
| 0x20655    | 2        | 1.16%   |
| 0x106e5    | 2        | 1.16%   |
| 0x0a601203 | 2        | 1.16%   |
| 0x0a50000d | 2        | 1.16%   |
| 0x0600611a | 2        | 1.16%   |
| 0x06001119 | 2        | 1.16%   |
| 0x06000852 | 2        | 1.16%   |
| 0x05000119 | 2        | 1.16%   |
| 0x906ed    | 1        | 0.58%   |
| 0x90672    | 1        | 0.58%   |
| 0x6fd      | 1        | 0.58%   |
| 0x606c1    | 1        | 0.58%   |
| 0x306f2    | 1        | 0.58%   |
| 0x206d7    | 1        | 0.58%   |
| 0x1067a    | 1        | 0.58%   |
| 0x10677    | 1        | 0.58%   |
| 0x10676    | 1        | 0.58%   |
| 0x0810100b | 1        | 0.58%   |
| 0x08001138 | 1        | 0.58%   |
| 0x06003106 | 1        | 0.58%   |
| 0x0600063e | 1        | 0.58%   |
| 0x010000dc | 1        | 0.58%   |
| 0x010000c8 | 1        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 20       | 11.76%  |
| Unknown          | 14       | 8.24%   |
| KabyLake         | 13       | 7.65%   |
| SandyBridge      | 11       | 6.47%   |
| Zen 3            | 10       | 5.88%   |
| IvyBridge        | 10       | 5.88%   |
| Zen+             | 9        | 5.29%   |
| Skylake          | 9        | 5.29%   |
| Penryn           | 8        | 4.71%   |
| Zen 2            | 7        | 4.12%   |
| Zen              | 7        | 4.12%   |
| Piledriver       | 6        | 3.53%   |
| K10              | 6        | 3.53%   |
| Icelake          | 5        | 2.94%   |
| Goldmont plus    | 5        | 2.94%   |
| CometLake        | 5        | 2.94%   |
| Westmere         | 4        | 2.35%   |
| Excavator        | 3        | 1.76%   |
| Alderlake Hybrid | 3        | 1.76%   |
| NetBurst         | 2        | 1.18%   |
| Nehalem          | 2        | 1.18%   |
| Bulldozer        | 2        | 1.18%   |
| Broadwell        | 2        | 1.18%   |
| Bobcat           | 2        | 1.18%   |
| Tremont          | 1        | 0.59%   |
| Steamroller      | 1        | 0.59%   |
| Silvermont       | 1        | 0.59%   |
| Gracemont        | 1        | 0.59%   |
| Core             | 1        | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 63       | 35%     |
| AMD                        | 58       | 32.22%  |
| Nvidia                     | 57       | 31.67%  |
| Matrox Electronics Systems | 1        | 0.56%   |
| ASPEED Technology          | 1        | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 5.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 4.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 4.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 3.85%   |
| Intel HD Graphics 530                                                       | 6        | 3.3%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 2.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 2.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.75%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4        | 2.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.2%    |
| AMD Raphael                                                                 | 4        | 2.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.2%    |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.65%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 3        | 1.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.1%    |
| Nvidia GP107GL [Quadro P620]                                                | 2        | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.1%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.1%    |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 1.1%    |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 1.1%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.1%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.1%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.1%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.1%    |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 2        | 1.1%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.1%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.1%    |
| Nvidia TU117GL [T400 4GB / T400E]                                           | 1        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.55%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.55%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 54       | 31.95%  |
| 1 x AMD        | 53       | 31.36%  |
| 1 x Nvidia     | 51       | 30.18%  |
| Intel + Nvidia | 4        | 2.37%   |
| 2 x AMD        | 2        | 1.18%   |
| AMD + Nvidia   | 2        | 1.18%   |
| 1 x Matrox     | 1        | 0.59%   |
| Intel + AMD    | 1        | 0.59%   |
| 1 x ASPEED     | 1        | 0.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 121      | 71.18%  |
| Proprietary | 43       | 25.29%  |
| Unknown     | 6        | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 90       | 52.94%  |
| 1.01-2.0   | 19       | 11.18%  |
| 0.51-1.0   | 17       | 10%     |
| 0.01-0.5   | 15       | 8.82%   |
| 3.01-4.0   | 10       | 5.88%   |
| 5.01-6.0   | 7        | 4.12%   |
| 7.01-8.0   | 6        | 3.53%   |
| 16.01-24.0 | 3        | 1.76%   |
| 8.01-16.0  | 2        | 1.18%   |
| 2.01-3.0   | 1        | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 36       | 19.35%  |
| Goldstar             | 23       | 12.37%  |
| Hewlett-Packard      | 15       | 8.06%   |
| Dell                 | 15       | 8.06%   |
| Philips              | 13       | 6.99%   |
| Acer                 | 13       | 6.99%   |
| Iiyama               | 12       | 6.45%   |
| BenQ                 | 9        | 4.84%   |
| AOC                  | 5        | 2.69%   |
| Ancor Communications | 5        | 2.69%   |
| Lenovo               | 4        | 2.15%   |
| ViewSonic            | 3        | 1.61%   |
| Sony                 | 2        | 1.08%   |
| NEC Computers        | 2        | 1.08%   |
| Westinghouse         | 1        | 0.54%   |
| VMO                  | 1        | 0.54%   |
| Vizio                | 1        | 0.54%   |
| Vita                 | 1        | 0.54%   |
| SNC                  | 1        | 0.54%   |
| SKG                  | 1        | 0.54%   |
| SGX                  | 1        | 0.54%   |
| Sceptre Tech         | 1        | 0.54%   |
| PXO                  | 1        | 0.54%   |
| Panasonic            | 1        | 0.54%   |
| Packard Bell         | 1        | 0.54%   |
| OEM                  | 1        | 0.54%   |
| NYC                  | 1        | 0.54%   |
| Medion               | 1        | 0.54%   |
| LG Electronics       | 1        | 0.54%   |
| Lenovo Group Limited | 1        | 0.54%   |
| Lanix                | 1        | 0.54%   |
| Kogan                | 1        | 0.54%   |
| ITE                  | 1        | 0.54%   |
| Insignia             | 1        | 0.54%   |
| Idek Iiyama          | 1        | 0.54%   |
| HPN                  | 1        | 0.54%   |
| Gateway              | 1        | 0.54%   |
| Fujitsu Siemens      | 1        | 0.54%   |
| Envision Peripherals | 1        | 0.54%   |
| D&T                  | 1        | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 2        | 1.02%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 2        | 1.02%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 2        | 1.02%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 2        | 1.02%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                  | 2        | 1.02%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                  | 2        | 1.02%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                     | 2        | 1.02%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                    | 2        | 1.02%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch          | 1        | 0.51%   |
| VMO LCD WQHD HDMI VMO1506 2560x1440 1600x1000mm 74.3-inch             | 1        | 0.51%   |
| Vizio XVT323SV VIZ0063 1920x1080 698x393mm 31.5-inch                  | 1        | 0.51%   |
| Vita LCD Monitor VIT0780 1920x1080                                    | 1        | 0.51%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 610x360mm 27.9-inch         | 1        | 0.51%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch         | 1        | 0.51%   |
| ViewSonic VA2046 SERIES VSC6D2E 1600x900 432x240mm 19.5-inch          | 1        | 0.51%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                         | 1        | 0.51%   |
| Sony LCD Monitor TV 3840x1080                                         | 1        | 0.51%   |
| Sony LCD Monitor TV                                                   | 1        | 0.51%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                  | 1        | 0.51%   |
| SKG VG2791SEF SKG2713 1920x1080 597x336mm 27.0-inch                   | 1        | 0.51%   |
| SGX LCD Monitor SGX1000 1280x1024                                     | 1        | 0.51%   |
| Sceptre Tech Sceptre H40 SPT0FF1 1920x1080 575x323mm 26.0-inch        | 1        | 0.51%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch  | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 459x296mm 21.5-inch  | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch   | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM006A 1280x1024 338x270mm 17.0-inch  | 1        | 0.51%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch    | 1        | 0.51%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1        | 0.51%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 1        | 0.51%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 1        | 0.51%   |
| Samsung Electronics SAMTRON STN001C 1024x768 267x200mm 13.1-inch      | 1        | 0.51%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1        | 0.51%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 0.51%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch     | 1        | 0.51%   |
| Samsung Electronics S27F358 SAM0D72 1920x1080 598x336mm 27.0-inch     | 1        | 0.51%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 0.51%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch     | 1        | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 84       | 47.73%  |
| 2560x1440 (QHD)    | 19       | 10.8%   |
| 1280x1024 (SXGA)   | 15       | 8.52%   |
| 3840x2160 (4K)     | 11       | 6.25%   |
| 1680x1050 (WSXGA+) | 7        | 3.98%   |
| 1440x900 (WXGA+)   | 6        | 3.41%   |
| 3440x1440          | 5        | 2.84%   |
| 1600x900 (HD+)     | 5        | 2.84%   |
| 1366x768 (WXGA)    | 5        | 2.84%   |
| Unknown            | 4        | 2.27%   |
| 1920x1200 (WUXGA)  | 3        | 1.7%    |
| 3840x1080          | 2        | 1.14%   |
| 2560x1080          | 2        | 1.14%   |
| 1360x768           | 2        | 1.14%   |
| 4480x1440          | 1        | 0.57%   |
| 3840x1600          | 1        | 0.57%   |
| 3840x1200          | 1        | 0.57%   |
| 2560x1600          | 1        | 0.57%   |
| 1280x720 (HD)      | 1        | 0.57%   |
| 1024x768 (XGA)     | 1        | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 36       | 19.57%  |
| 21      | 26       | 14.13%  |
| 24      | 23       | 12.5%   |
| 23      | 16       | 8.7%    |
| 19      | 13       | 7.07%   |
| Unknown | 13       | 7.07%   |
| 31      | 9        | 4.89%   |
| 17      | 9        | 4.89%   |
| 34      | 8        | 4.35%   |
| 22      | 5        | 2.72%   |
| 18      | 5        | 2.72%   |
| 26      | 3        | 1.63%   |
| 54      | 2        | 1.09%   |
| 46      | 2        | 1.09%   |
| 38      | 2        | 1.09%   |
| 32      | 2        | 1.09%   |
| 15      | 2        | 1.09%   |
| 84      | 1        | 0.54%   |
| 74      | 1        | 0.54%   |
| 72      | 1        | 0.54%   |
| 40      | 1        | 0.54%   |
| 33      | 1        | 0.54%   |
| 25      | 1        | 0.54%   |
| 20      | 1        | 0.54%   |
| 13      | 1        | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 67       | 37.64%  |
| 401-500     | 45       | 25.28%  |
| 601-700     | 14       | 7.87%   |
| Unknown     | 13       | 7.3%    |
| 701-800     | 11       | 6.18%   |
| 301-350     | 10       | 5.62%   |
| 351-400     | 7        | 3.93%   |
| 1001-1500   | 4        | 2.25%   |
| 801-900     | 3        | 1.69%   |
| 1501-2000   | 3        | 1.69%   |
| 201-300     | 1        | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 115      | 68.45%  |
| 16/10   | 20       | 11.9%   |
| 5/4     | 15       | 8.93%   |
| 21/9    | 9        | 5.36%   |
| Unknown | 8        | 4.76%   |
| 4/3     | 1        | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 54       | 30.34%  |
| 301-350        | 37       | 20.79%  |
| 151-200        | 21       | 11.8%   |
| 351-500        | 20       | 11.24%  |
| Unknown        | 13       | 7.3%    |
| 141-150        | 11       | 6.18%   |
| 251-300        | 8        | 4.49%   |
| More than 1000 | 5        | 2.81%   |
| 501-1000       | 5        | 2.81%   |
| 101-110        | 2        | 1.12%   |
| 81-90          | 1        | 0.56%   |
| 131-140        | 1        | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 100      | 57.8%   |
| 101-120 | 44       | 25.43%  |
| Unknown | 13       | 7.51%   |
| 1-50    | 8        | 4.62%   |
| 121-160 | 8        | 4.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 125      | 73.1%   |
| 2     | 40       | 23.39%  |
| 0     | 5        | 2.92%   |
| 3     | 1        | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 116      | 49.15%  |
| Intel                           | 69       | 29.24%  |
| Broadcom                        | 12       | 5.08%   |
| Qualcomm Atheros                | 10       | 4.24%   |
| MediaTek                        | 6        | 2.54%   |
| TP-Link                         | 4        | 1.69%   |
| Ralink                          | 3        | 1.27%   |
| Xiaomi                          | 2        | 0.85%   |
| Ralink Technology               | 2        | 0.85%   |
| Qualcomm Atheros Communications | 2        | 0.85%   |
| Marvell Technology Group        | 2        | 0.85%   |
| ZyDAS                           | 1        | 0.42%   |
| Realtek                         | 1        | 0.42%   |
| Qualcomm Technologies           | 1        | 0.42%   |
| NetXen Incorporated             | 1        | 0.42%   |
| NetGear                         | 1        | 0.42%   |
| Motorola PCS                    | 1        | 0.42%   |
| Broadcom Limited                | 1        | 0.42%   |
| ASUSTek Computer                | 1        | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 90       | 33.33%  |
| Realtek RTL8125 2.5GbE Controller                                      | 11       | 4.07%   |
| Intel Ethernet Controller I225-V                                       | 11       | 4.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 2.22%   |
| Intel Ethernet Connection (2) I219-V                                   | 6        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 2.22%   |
| Intel I211 Gigabit Network Connection                                  | 5        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 1.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 3        | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 3        | 1.11%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 1.11%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.11%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 3        | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2        | 0.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2        | 0.74%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2        | 0.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.74%   |
| Realtek 802.11ac NIC                                                   | 2        | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 0.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.74%   |
| Intel Wireless 7265                                                    | 2        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.74%   |
| ZyDAS ZD1211B 802.11g                                                  | 1        | 0.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.37%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.37%   |
| TP-Link Archer T4U ver.3                                               | 1        | 0.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.37%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 32.91%  |
| Realtek Semiconductor           | 24       | 30.38%  |
| Qualcomm Atheros                | 5        | 6.33%   |
| MediaTek                        | 5        | 6.33%   |
| TP-Link                         | 4        | 5.06%   |
| Ralink                          | 3        | 3.8%    |
| Broadcom                        | 3        | 3.8%    |
| Ralink Technology               | 2        | 2.53%   |
| Qualcomm Atheros Communications | 2        | 2.53%   |
| ZyDAS                           | 1        | 1.27%   |
| Realtek                         | 1        | 1.27%   |
| Qualcomm Technologies           | 1        | 1.27%   |
| NetGear                         | 1        | 1.27%   |
| ASUSTek Computer                | 1        | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]        | 6        | 7.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 3        | 3.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter         | 3        | 3.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 3        | 3.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 3        | 3.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 3        | 3.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 2        | 2.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 2        | 2.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter            | 2        | 2.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 2        | 2.53%   |
| Realtek 802.11ac NIC                                             | 2        | 2.53%   |
| Qualcomm Atheros AR9271 802.11n                                  | 2        | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 2        | 2.53%   |
| Intel Wireless 7265                                              | 2        | 2.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                   | 2        | 2.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 2        | 2.53%   |
| ZyDAS ZD1211B 802.11g                                            | 1        | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                      | 1        | 1.27%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                              | 1        | 1.27%   |
| TP-Link Archer T4U ver.3                                         | 1        | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 1        | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 1        | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1        | 1.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                       | 1        | 1.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                  | 1        | 1.27%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                           | 1        | 1.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1        | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 1        | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 1        | 1.27%   |
| Realtek 802.11ac WLAN Adapter                                    | 1        | 1.27%   |
| Ralink RT2870 Wireless Adapter                                   | 1        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                  | 1        | 1.27%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter           | 1        | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 1        | 1.27%   |
| Ralink RT2561/RT61 802.11g PCI                                   | 1        | 1.27%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800] | 1        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1        | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 1        | 1.27%   |
| NetGear A6150                                                    | 1        | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 106      | 59.22%  |
| Intel                    | 51       | 28.49%  |
| Broadcom                 | 9        | 5.03%   |
| Qualcomm Atheros         | 5        | 2.79%   |
| Xiaomi                   | 2        | 1.12%   |
| Marvell Technology Group | 2        | 1.12%   |
| NetXen Incorporated      | 1        | 0.56%   |
| Motorola PCS             | 1        | 0.56%   |
| MediaTek                 | 1        | 0.56%   |
| Broadcom Limited         | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 90       | 47.12%  |
| Realtek RTL8125 2.5GbE Controller                                      | 11       | 5.76%   |
| Intel Ethernet Controller I225-V                                       | 11       | 5.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 6        | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 3.14%   |
| Intel I211 Gigabit Network Connection                                  | 5        | 2.62%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 1.57%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.57%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.57%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 3        | 1.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 1.05%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2        | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 1.05%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.52%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter   | 1        | 0.52%   |
| Motorola PCS moto g84 5G                                               | 1        | 0.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 0.52%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1        | 0.52%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.52%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.52%   |
| Intel Ethernet Controller X550                                         | 1        | 0.52%   |
| Intel Ethernet Controller I225-IT                                      | 1        | 0.52%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.52%   |
| Intel Ethernet Connection E823-C for SFP                               | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.52%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 0.52%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 168      | 68.57%  |
| WiFi     | 77       | 31.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 142      | 80.68%  |
| WiFi     | 34       | 19.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 55.62%  |
| 2     | 64       | 37.87%  |
| 3     | 5        | 2.96%   |
| 4     | 3        | 1.78%   |
| 6     | 1        | 0.59%   |
| 5     | 1        | 0.59%   |
| 0     | 1        | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 68.79%  |
| Yes  | 54       | 31.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 40.35%  |
| Cambridge Silicon Radio         | 8        | 14.04%  |
| Realtek Semiconductor           | 7        | 12.28%  |
| MediaTek                        | 4        | 7.02%   |
| TP-Link                         | 2        | 3.51%   |
| IMC Networks                    | 2        | 3.51%   |
| Foxconn / Hon Hai               | 2        | 3.51%   |
| Broadcom                        | 2        | 3.51%   |
| Belkin Components               | 2        | 3.51%   |
| ASUSTek Computer                | 2        | 3.51%   |
| Ralink                          | 1        | 1.75%   |
| Qualcomm Atheros Communications | 1        | 1.75%   |
| Integrated System Solution      | 1        | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 14.04%  |
| Intel Bluetooth wireless interface                    | 5        | 8.77%   |
| Intel AX210 Bluetooth                                 | 5        | 8.77%   |
| MediaTek Wireless_Device                              | 4        | 7.02%   |
| Intel AX201 Bluetooth                                 | 4        | 7.02%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 5.26%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 2        | 3.51%   |
| Realtek RTL8723B Bluetooth                            | 2        | 3.51%   |
| Realtek Bluetooth Radio                               | 2        | 3.51%   |
| Ralink RT3290 Bluetooth                               | 1        | 1.75%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.75%   |
| Intel AX211 Bluetooth                                 | 1        | 1.75%   |
| Intel AX200 Bluetooth                                 | 1        | 1.75%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.75%   |
| IMC Networks Wireless_Device                          | 1        | 1.75%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.75%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.75%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.75%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 1        | 1.75%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 1.75%   |
| Belkin Components F8T013 Bluetooth Adapter            | 1        | 1.75%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.75%   |
| ASUS Bluetooth Radio                                  | 1        | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 106      | 38.55%  |
| AMD                      | 71       | 25.82%  |
| Nvidia                   | 56       | 20.36%  |
| C-Media Electronics      | 12       | 4.36%   |
| ASUSTek Computer         | 5        | 1.82%   |
| GN Netcom                | 3        | 1.09%   |
| Generalplus Technology   | 3        | 1.09%   |
| Kingston Technology      | 2        | 0.73%   |
| Walmart                  | 1        | 0.36%   |
| VIA Technologies         | 1        | 0.36%   |
| Texas Instruments        | 1        | 0.36%   |
| TerraTec Electronic      | 1        | 0.36%   |
| Tenx Technology          | 1        | 0.36%   |
| SteelSeries ApS          | 1        | 0.36%   |
| Micro Star International | 1        | 0.36%   |
| Logitech                 | 1        | 0.36%   |
| JMTek                    | 1        | 0.36%   |
| Focusrite-Novation       | 1        | 0.36%   |
| DSEA A/S                 | 1        | 0.36%   |
| Creative Technology      | 1        | 0.36%   |
| Corsair                  | 1        | 0.36%   |
| Cambridge Silicon Radio  | 1        | 0.36%   |
| Best Buy                 | 1        | 0.36%   |
| ASRock                   | 1        | 0.36%   |
| Alesis                   | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 22       | 6.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 4.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 3.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 3.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 3.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 3.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10       | 3.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 2.74%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 2.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 1.82%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.52%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5        | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.52%   |
| ASUSTek Computer USB Audio                                                 | 5        | 1.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4        | 1.22%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.22%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.91%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 0.91%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.91%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.91%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.91%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 0.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3        | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 19       | 14.07%  |
| Corsair             | 19       | 14.07%  |
| Unknown             | 16       | 11.85%  |
| Crucial             | 14       | 10.37%  |
| SK hynix            | 13       | 9.63%   |
| Samsung Electronics | 13       | 9.63%   |
| G.Skill             | 12       | 8.89%   |
| Micron Technology   | 7        | 5.19%   |
| Unknown             | 3        | 2.22%   |
| Unknown (ABCD)      | 2        | 1.48%   |
| Team                | 2        | 1.48%   |
| Hewlett-Packard     | 2        | 1.48%   |
| Elpida              | 2        | 1.48%   |
| A-DATA Technology   | 2        | 1.48%   |
| Unknown (0x7FFF)    | 1        | 0.74%   |
| Unifosa             | 1        | 0.74%   |
| Transcend           | 1        | 0.74%   |
| Ramaxel Technology  | 1        | 0.74%   |
| OLOY                | 1        | 0.74%   |
| HBS                 | 1        | 0.74%   |
| GOODRAM             | 1        | 0.74%   |
| Atermiter           | 1        | 0.74%   |
| AMD                 | 1        | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown                                                         | 3        | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                       | 2        | 1.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 1.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s    | 2        | 1.42%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s            | 2        | 1.42%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s             | 2        | 1.42%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s                  | 2        | 1.42%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s              | 2        | 1.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 2        | 1.42%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3733MT/s           | 2        | 1.42%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s            | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s           | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s           | 2        | 1.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                       | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                        | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                        | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM                                     | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                       | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                         | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 133MT/s                         | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                        | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                            | 1        | 0.71%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s         | 1        | 0.71%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s       | 1        | 0.71%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s           | 1        | 0.71%   |
| Unknown (0x7FFF) RAM GRAVITON 8GB-288P01 8GB DIMM DDR4 2667MT/s | 1        | 0.71%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s               | 1        | 0.71%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s              | 1        | 0.71%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                           | 1        | 0.71%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 0.71%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.71%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s             | 1        | 0.71%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s            | 1        | 0.71%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s            | 1        | 0.71%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.71%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.71%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 57       | 48.72%  |
| DDR3    | 38       | 32.48%  |
| DDR5    | 8        | 6.84%   |
| Unknown | 5        | 4.27%   |
| DDR     | 3        | 2.56%   |
| SDRAM   | 2        | 1.71%   |
| LPDDR4  | 2        | 1.71%   |
| DDR2    | 2        | 1.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 107      | 91.45%  |
| SODIMM | 10       | 8.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 43       | 33.33%  |
| 16384  | 33       | 25.58%  |
| 4096   | 32       | 24.81%  |
| 32768  | 9        | 6.98%   |
| 2048   | 9        | 6.98%   |
| 1024   | 2        | 1.55%   |
| 131072 | 1        | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 16.15%  |
| 1333    | 15       | 11.54%  |
| 3600    | 9        | 6.92%   |
| 3200    | 9        | 6.92%   |
| 2667    | 9        | 6.92%   |
| 2400    | 7        | 5.38%   |
| 2133    | 5        | 3.85%   |
| 800     | 5        | 3.85%   |
| 6400    | 4        | 3.08%   |
| 3733    | 3        | 2.31%   |
| 3466    | 3        | 2.31%   |
| 2666    | 3        | 2.31%   |
| 1866    | 3        | 2.31%   |
| 1800    | 3        | 2.31%   |
| 4000    | 2        | 1.54%   |
| 3800    | 2        | 1.54%   |
| 3400    | 2        | 1.54%   |
| 3266    | 2        | 1.54%   |
| 3000    | 2        | 1.54%   |
| 1867    | 2        | 1.54%   |
| 5900    | 1        | 0.77%   |
| 5808    | 1        | 0.77%   |
| 4802    | 1        | 0.77%   |
| 4800    | 1        | 0.77%   |
| 3933    | 1        | 0.77%   |
| 3334    | 1        | 0.77%   |
| 3333    | 1        | 0.77%   |
| 3100    | 1        | 0.77%   |
| 2933    | 1        | 0.77%   |
| 2800    | 1        | 0.77%   |
| 2747    | 1        | 0.77%   |
| 2734    | 1        | 0.77%   |
| 2448    | 1        | 0.77%   |
| 1648    | 1        | 0.77%   |
| 1632    | 1        | 0.77%   |
| 1066    | 1        | 0.77%   |
| 667     | 1        | 0.77%   |
| 133     | 1        | 0.77%   |
| Unknown | 1        | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 3        | 37.5%   |
| Seiko Epson        | 2        | 25%     |
| Hewlett-Packard    | 2        | 25%     |
| Graphtec America   | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series        | 1        | 12.5%   |
| Seiko Epson Printer               | 1        | 12.5%   |
| HP LaserJet Professional P1102w   | 1        | 12.5%   |
| HP DeskJet 2700 series            | 1        | 12.5%   |
| Graphtec America Graphtec Printer | 1        | 12.5%   |
| Brother Printer                   | 1        | 12.5%   |
| Brother HL-3140CW series          | 1        | 12.5%   |
| Brother DCP-L5500DN series        | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 75%     |
| Hewlett-Packard | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 2        | 50%     |
| HP ScanJet G4010        | 1        | 25%     |
| Canon CanoScan LiDE 120 | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 28.95%  |
| Microdia                      | 7        | 18.42%  |
| Sunplus Innovation Technology | 3        | 7.89%   |
| Z-Star Microelectronics       | 2        | 5.26%   |
| Samsung Electronics           | 2        | 5.26%   |
| Generalplus Technology        | 2        | 5.26%   |
| WaveRider Communications      | 1        | 2.63%   |
| Realtek Semiconductor         | 1        | 2.63%   |
| Razer USA                     | 1        | 2.63%   |
| Microsoft                     | 1        | 2.63%   |
| LeCroy                        | 1        | 2.63%   |
| KYE Systems (Mouse Systems)   | 1        | 2.63%   |
| Guillemot                     | 1        | 2.63%   |
| ARC International             | 1        | 2.63%   |
| Apple                         | 1        | 2.63%   |
| Alcorlink                     | 1        | 2.63%   |
| Alcor Micro                   | 1        | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 4        | 10.53%  |
| Microdia Webcam Vitade AF                  | 3        | 7.89%   |
| Microdia USB 2.0 Camera                    | 3        | 7.89%   |
| Logitech Webcam C270                       | 3        | 7.89%   |
| Sunplus FULL HD webcam                     | 2        | 5.26%   |
| Samsung Galaxy series, misc. (MTP mode)    | 2        | 5.26%   |
| Z-Star Venus USB2.0 Camera                 | 1        | 2.63%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA       | 1        | 2.63%   |
| WaveRider USB 2.0 Camera                   | 1        | 2.63%   |
| Sunplus Integrated_Webcam_HD               | 1        | 2.63%   |
| Realtek HP 1.0MP High Definition Webcam    | 1        | 2.63%   |
| Razer USA Gaming Webcam [Kiyo]             | 1        | 2.63%   |
| Microsoft LifeCam VX-500 [1357]            | 1        | 2.63%   |
| Microdia Streaming Camera W8GS             | 1        | 2.63%   |
| Logitech QuickCam E 3500                   | 1        | 2.63%   |
| Logitech Quickcam 3000 For Business        | 1        | 2.63%   |
| Logitech Logitech Webcam C925e             | 1        | 2.63%   |
| Logitech Logitech Webcam C100              | 1        | 2.63%   |
| LeCroy USB 2.0 PC Camera                   | 1        | 2.63%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 2.63%   |
| Guillemot Hercules HD Twist                | 1        | 2.63%   |
| Generalplus GENERAL WEBCAM                 | 1        | 2.63%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 1        | 2.63%   |
| ARC International Camera                   | 1        | 2.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR         | 1        | 2.63%   |
| Alcorlink USB 2.0 Camera                   | 1        | 2.63%   |
| Alcor Micro USB 2.0 PC Camera              | 1        | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 50%     |
| OmniKey          | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| SCM Microsystems Identiv SmartOS Reader | 1        | 50%     |
| OmniKey CardMan 1021                    | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 144      | 84.71%  |
| 1     | 23       | 13.53%  |
| 2     | 2        | 1.18%   |
| 3     | 1        | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 33.33%  |
| Net/wireless             | 6        | 22.22%  |
| Unassigned class         | 4        | 14.81%  |
| Communication controller | 3        | 11.11%  |
| Bluetooth                | 2        | 7.41%   |
| Sound                    | 1        | 3.7%    |
| Chipcard                 | 1        | 3.7%    |
| Card reader              | 1        | 3.7%    |


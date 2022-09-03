Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

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

Total: 687

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [3a8803f198](https://linux-hardware.org/?probe=3a8803f198) | Sep 01, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [b6cc2513ff](https://linux-hardware.org/?probe=b6cc2513ff) | Aug 31, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [e8b26fc530](https://linux-hardware.org/?probe=e8b26fc530) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [f262848655](https://linux-hardware.org/?probe=f262848655) | Aug 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0da338038e](https://linux-hardware.org/?probe=0da338038e) | Aug 29, 2022 |
| Standard      | Unknown                     | Notebook    | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [155267063a](https://linux-hardware.org/?probe=155267063a) | Aug 28, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | Notebook    | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [9ffe8ee96e](https://linux-hardware.org/?probe=9ffe8ee96e) | Aug 24, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [4709584652](https://linux-hardware.org/?probe=4709584652) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [364b450a4f](https://linux-hardware.org/?probe=364b450a4f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | Notebook    | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | 805D                        | Desktop     | [6748d722e7](https://linux-hardware.org/?probe=6748d722e7) | Aug 19, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f8675baa98](https://linux-hardware.org/?probe=f8675baa98) | Aug 18, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [59456f2a25](https://linux-hardware.org/?probe=59456f2a25) | Aug 16, 2022 |
| HP            | 2AF7                        | Desktop     | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [fb8a250b12](https://linux-hardware.org/?probe=fb8a250b12) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [0f4b093f48](https://linux-hardware.org/?probe=0f4b093f48) | Aug 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | Notebook    | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | Notebook    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | Notebook    | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | Notebook    | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [fc8e3b6a3b](https://linux-hardware.org/?probe=fc8e3b6a3b) | Aug 05, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73488d7a09](https://linux-hardware.org/?probe=73488d7a09) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | Notebook    | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | Notebook    | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [e430a435bf](https://linux-hardware.org/?probe=e430a435bf) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4a6d0213a4](https://linux-hardware.org/?probe=4a6d0213a4) | Aug 02, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [7be7ab2e7e](https://linux-hardware.org/?probe=7be7ab2e7e) | Jul 31, 2022 |
| Dell          | Latitude E6320              | Notebook    | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Dell          | Latitude D630               | Notebook    | [37250474ae](https://linux-hardware.org/?probe=37250474ae) | Jul 29, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [ab8af10726](https://linux-hardware.org/?probe=ab8af10726) | Jul 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | Notebook    | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [4cc1f4384c](https://linux-hardware.org/?probe=4cc1f4384c) | Jul 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [0b7a9cbc2a](https://linux-hardware.org/?probe=0b7a9cbc2a) | Jul 12, 2022 |
| HP            | Notebook                    | Notebook    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [e4b17550d0](https://linux-hardware.org/?probe=e4b17550d0) | Jul 06, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [d07e96a623](https://linux-hardware.org/?probe=d07e96a623) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [90c166f77b](https://linux-hardware.org/?probe=90c166f77b) | Jun 25, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | Desktop     | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | Desktop     | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [50e049e6fb](https://linux-hardware.org/?probe=50e049e6fb) | Jun 23, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| Alienware     | m17 R3                      | Notebook    | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | Notebook    | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| T-bao         | MINI PC                     | Desktop     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Samsung       | Lumpy                       | Notebook    | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | Notebook    | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Samsung       | Lumpy                       | Notebook    | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [25a8936801](https://linux-hardware.org/?probe=25a8936801) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| HP            | Notebook                    | Notebook    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| MSI           | B85I                        | Desktop     | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| HP            | ProBook 4540s               | Notebook    | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | Desktop     | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [fc581d0fb4](https://linux-hardware.org/?probe=fc581d0fb4) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | Notebook    | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| MSI           | H97M-P35                    | Desktop     | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8cd4fba0ca](https://linux-hardware.org/?probe=8cd4fba0ca) | May 22, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| AMI           | Intel                       | Notebook    | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | Notebook    | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| MSI           | B85I                        | Desktop     | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | Notebook    | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | Notebook    | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | K55A                        | Notebook    | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [4521ae6617](https://linux-hardware.org/?probe=4521ae6617) | May 14, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [513d1e2c73](https://linux-hardware.org/?probe=513d1e2c73) | May 14, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | Notebook    | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| eMachines     | E525                        | Notebook    | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [271a0aaed2](https://linux-hardware.org/?probe=271a0aaed2) | May 01, 2022 |
| ASUSTek       | X202E                       | Notebook    | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| HP            | 0B48h                       | Desktop     | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [317f2966c3](https://linux-hardware.org/?probe=317f2966c3) | Apr 25, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | Notebook    | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| AZW           | GTi                         | Desktop     | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | Notebook    | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b720cd5fc5](https://linux-hardware.org/?probe=b720cd5fc5) | Apr 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | Notebook    | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | Desktop     | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | Notebook    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| ASRock        | C226 WS                     | Desktop     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| HP            | Notebook                    | Notebook    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Dell          | Inspiron 5481               | Convertible | [e364cee660](https://linux-hardware.org/?probe=e364cee660) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | Notebook    | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | Notebook    | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | Notebook    | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b39b0fda2](https://linux-hardware.org/?probe=2b39b0fda2) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [78df63a35f](https://linux-hardware.org/?probe=78df63a35f) | Mar 20, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1268effe7d](https://linux-hardware.org/?probe=1268effe7d) | Mar 17, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [9eb7577acd](https://linux-hardware.org/?probe=9eb7577acd) | Mar 12, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| MSI           | B85I                        | Desktop     | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| Teclast       | F15S                        | Notebook    | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | Desktop     | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | Notebook    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| HP            | 1589                        | Desktop     | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| HP            | 805D                        | Desktop     | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [1f32b0aa84](https://linux-hardware.org/?probe=1f32b0aa84) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ef94f0dd4d](https://linux-hardware.org/?probe=ef94f0dd4d) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | Notebook    | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| MSI           | B85I                        | Desktop     | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Google        | Lulu                        | Notebook    | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f7500c309c](https://linux-hardware.org/?probe=f7500c309c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| HP            | 339A                        | Desktop     | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| HP            | 805D                        | Desktop     | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| FIRICH        | J1900                       | Desktop     | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Dell          | Latitude E5400              | Notebook    | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | Notebook    | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 110       | 19.96%  |
| 5.13.0-28-generic          | 54        | 9.8%    |
| 5.13.0-30-generic          | 40        | 7.26%   |
| 5.13.0-39-generic          | 35        | 6.35%   |
| 5.13.0-27-generic          | 35        | 6.35%   |
| 5.15.0-46-generic          | 28        | 5.08%   |
| 5.15.0-41-generic          | 26        | 4.72%   |
| 5.13.0-40-generic          | 25        | 4.54%   |
| 5.13.0-35-generic          | 23        | 4.17%   |
| 5.13.0-37-generic          | 19        | 3.45%   |
| 5.11.0-44-generic          | 17        | 3.09%   |
| 5.13.0-52-generic          | 16        | 2.9%    |
| 5.13.0-51-generic          | 16        | 2.9%    |
| 5.13.0-41-generic          | 14        | 2.54%   |
| 5.15.0-43-generic          | 13        | 2.36%   |
| 5.13.0-44-generic          | 13        | 2.36%   |
| 5.11.0-46-generic          | 12        | 2.18%   |
| 5.11.0-41-generic          | 10        | 1.81%   |
| 5.13.0-48-generic          | 9         | 1.63%   |
| 5.13.0-25-generic          | 4         | 0.73%   |
| 5.11.0-40-generic          | 3         | 0.54%   |
| 5.15.36-xanmod1            | 2         | 0.36%   |
| 5.8.0-50-generic           | 1         | 0.18%   |
| 5.4.0-122-generic          | 1         | 0.18%   |
| 5.4.0-1055-raspi           | 1         | 0.18%   |
| 5.19.4-surface             | 1         | 0.18%   |
| 5.19.3-051903-generic      | 1         | 0.18%   |
| 5.18.3-051803-generic      | 1         | 0.18%   |
| 5.17.3-xanmod1             | 1         | 0.18%   |
| 5.16.16-051616-generic     | 1         | 0.18%   |
| 5.16.11-surface            | 1         | 0.18%   |
| 5.16.10-051610-generic     | 1         | 0.18%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.18%   |
| 5.15.6-surface             | 1         | 0.18%   |
| 5.15.5-051505-generic      | 1         | 0.18%   |
| 5.15.3-xanmod1             | 1         | 0.18%   |
| 5.15.21-051521-generic     | 1         | 0.18%   |
| 5.15.13-xanmod1            | 1         | 0.18%   |
| 5.15.12-xanmod1-tt         | 1         | 0.18%   |
| 5.15.11-t2-big-sur         | 1         | 0.18%   |
| 5.15.10-xanmod1            | 1         | 0.18%   |
| 5.14.10-051410-generic     | 1         | 0.18%   |
| 5.14.0-1042-oem            | 1         | 0.18%   |
| 5.14.0-1029-oem            | 1         | 0.18%   |
| 5.14.0-1011-oem            | 1         | 0.18%   |
| 5.13.0-28-lowlatency       | 1         | 0.18%   |
| 5.13.0-22-generic          | 1         | 0.18%   |
| 5.11.0-43-lowlatency       | 1         | 0.18%   |
| 5.11.0-37-generic          | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 281       | 53.73%  |
| 5.11.0  | 152       | 29.06%  |
| 5.15.0  | 65        | 12.43%  |
| 5.14.0  | 3         | 0.57%   |
| 5.4.0   | 2         | 0.38%   |
| 5.15.36 | 2         | 0.38%   |
| 5.8.0   | 1         | 0.19%   |
| 5.19.4  | 1         | 0.19%   |
| 5.19.3  | 1         | 0.19%   |
| 5.18.3  | 1         | 0.19%   |
| 5.17.3  | 1         | 0.19%   |
| 5.16.16 | 1         | 0.19%   |
| 5.16.11 | 1         | 0.19%   |
| 5.16.10 | 1         | 0.19%   |
| 5.16.0  | 1         | 0.19%   |
| 5.15.6  | 1         | 0.19%   |
| 5.15.5  | 1         | 0.19%   |
| 5.15.3  | 1         | 0.19%   |
| 5.15.21 | 1         | 0.19%   |
| 5.15.13 | 1         | 0.19%   |
| 5.15.12 | 1         | 0.19%   |
| 5.15.11 | 1         | 0.19%   |
| 5.15.10 | 1         | 0.19%   |
| 5.14.10 | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 281       | 53.83%  |
| 5.11    | 152       | 29.12%  |
| 5.15    | 75        | 14.37%  |
| 5.14    | 4         | 0.77%   |
| 5.16    | 3         | 0.57%   |
| 5.4     | 2         | 0.38%   |
| 5.19    | 2         | 0.38%   |
| 5.8     | 1         | 0.19%   |
| 5.18    | 1         | 0.19%   |
| 5.17    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 512       | 99.81%  |
| aarch64 | 1         | 0.19%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 510       | 99.42%  |
| KDE5     | 1         | 0.19%   |
| GNOME    | 1         | 0.19%   |
| Unknown  | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 513       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 410       | 79.61%  |
| LightDM | 102       | 19.81%  |
| GDM3    | 2         | 0.39%   |
| GDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 228       | 44.36%  |
| de_DE   | 65        | 12.65%  |
| es_ES   | 41        | 7.98%   |
| en_GB   | 25        | 4.86%   |
| ru_RU   | 24        | 4.67%   |
| fr_FR   | 24        | 4.67%   |
| pt_BR   | 22        | 4.28%   |
| it_IT   | 19        | 3.7%    |
| pl_PL   | 11        | 2.14%   |
| nl_NL   | 6         | 1.17%   |
| en_CA   | 6         | 1.17%   |
| en_AU   | 6         | 1.17%   |
| tr_TR   | 5         | 0.97%   |
| pt_PT   | 5         | 0.97%   |
| zh_CN   | 3         | 0.58%   |
| uk_UA   | 2         | 0.39%   |
| sv_SE   | 2         | 0.39%   |
| nb_NO   | 2         | 0.39%   |
| ja_JP   | 2         | 0.39%   |
| hu_HU   | 2         | 0.39%   |
| de_CH   | 2         | 0.39%   |
| C       | 2         | 0.39%   |
| sr_RS   | 1         | 0.19%   |
| id_ID   | 1         | 0.19%   |
| hr_HR   | 1         | 0.19%   |
| fr_CA   | 1         | 0.19%   |
| fi_FI   | 1         | 0.19%   |
| et_EE   | 1         | 0.19%   |
| da_DK   | 1         | 0.19%   |
| cs_CZ   | 1         | 0.19%   |
| bg_BG   | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 345       | 66.73%  |
| BIOS | 172       | 33.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 495       | 96.49%  |
| Btrfs   | 11        | 2.14%   |
| Overlay | 5         | 0.97%   |
| Xfs     | 2         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 436       | 84.66%  |
| GPT     | 69        | 13.4%   |
| MBR     | 10        | 1.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 493       | 95.73%  |
| Yes       | 22        | 4.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 478       | 93%     |
| Yes       | 36        | 7%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 82        | 15.98%  |
| Lenovo                  | 73        | 14.23%  |
| Hewlett-Packard         | 72        | 14.04%  |
| Apple                   | 57        | 11.11%  |
| Dell                    | 48        | 9.36%   |
| Acer                    | 28        | 5.46%   |
| MSI                     | 25        | 4.87%   |
| Gigabyte Technology     | 20        | 3.9%    |
| Sony                    | 9         | 1.75%   |
| HUAWEI                  | 9         | 1.75%   |
| ASRock                  | 9         | 1.75%   |
| Samsung Electronics     | 7         | 1.36%   |
| Microsoft               | 7         | 1.36%   |
| Toshiba                 | 6         | 1.17%   |
| Intel                   | 6         | 1.17%   |
| Biostar                 | 4         | 0.78%   |
| Teclast                 | 3         | 0.58%   |
| Notebook                | 3         | 0.58%   |
| Foxconn                 | 3         | 0.58%   |
| AMI                     | 3         | 0.58%   |
| Timi                    | 2         | 0.39%   |
| Star Labs               | 2         | 0.39%   |
| Pegatron                | 2         | 0.39%   |
| Monster                 | 2         | 0.39%   |
| LG Electronics          | 2         | 0.39%   |
| Fujitsu                 | 2         | 0.39%   |
| ECS                     | 2         | 0.39%   |
| Unknown                 | 2         | 0.39%   |
| Wortmann AG             | 1         | 0.19%   |
| TrekStor                | 1         | 0.19%   |
| T-bao                   | 1         | 0.19%   |
| Standard                | 1         | 0.19%   |
| Razer                   | 1         | 0.19%   |
| Raspberry Pi Foundation | 1         | 0.19%   |
| PIPO                    | 1         | 0.19%   |
| Packard Bell            | 1         | 0.19%   |
| Medion                  | 1         | 0.19%   |
| LORD ELECTRONICS        | 1         | 0.19%   |
| iOTA                    | 1         | 0.19%   |
| Google                  | 1         | 0.19%   |
| FIRICH                  | 1         | 0.19%   |
| eMachines               | 1         | 0.19%   |
| Complet                 | 1         | 0.19%   |
| Compaq                  | 1         | 0.19%   |
| Casper                  | 1         | 0.19%   |
| BANGHO                  | 1         | 0.19%   |
| AZW                     | 1         | 0.19%   |
| Avell High Performance  | 1         | 0.19%   |
| AOpen                   | 1         | 0.19%   |
| Alienware               | 1         | 0.19%   |
| Acidanthera             | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 4         | 0.78%   |
| Apple MacBookPro8,2                | 4         | 0.78%   |
| Apple MacBook5,1                   | 4         | 0.78%   |
| HUAWEI MACHD-WXX9                  | 3         | 0.58%   |
| HP Notebook                        | 3         | 0.58%   |
| ASUS ZenBook UX425EA_UX425EA       | 3         | 0.58%   |
| ASUS X550CA                        | 3         | 0.58%   |
| Apple MacBookAir4,2                | 3         | 0.58%   |
| Apple MacBook4,1                   | 3         | 0.58%   |
| Apple iMac7,1                      | 3         | 0.58%   |
| Unknown                            | 3         | 0.58%   |
| Timi TM1613                        | 2         | 0.39%   |
| MSI Prestige 15 A11UC              | 2         | 0.39%   |
| MSI MS-7C35                        | 2         | 0.39%   |
| Lenovo IdeaPad 310-15IKB 80TV      | 2         | 0.39%   |
| HUAWEI NBLK-WAX9X                  | 2         | 0.39%   |
| HP ProBook 4540s                   | 2         | 0.39%   |
| HP Pavilion g6                     | 2         | 0.39%   |
| HP Pavilion g4                     | 2         | 0.39%   |
| HP Pavilion 17                     | 2         | 0.39%   |
| HP Laptop 15-db0xxx                | 2         | 0.39%   |
| HP ENVY x360 Convertible 13-ay0xxx | 2         | 0.39%   |
| HP EliteBook 8460p                 | 2         | 0.39%   |
| HP EliteBook 840 G1                | 2         | 0.39%   |
| HP Compaq Pro 6300 MT              | 2         | 0.39%   |
| Gigabyte Z390 UD                   | 2         | 0.39%   |
| Dell XPS 13 9343                   | 2         | 0.39%   |
| Dell Inspiron N5050                | 2         | 0.39%   |
| Dell Inspiron 5537                 | 2         | 0.39%   |
| Dell Inspiron 15-3567              | 2         | 0.39%   |
| ASUS TUF Gaming B550M-PLUS         | 2         | 0.39%   |
| Apple Macmini5,1                   | 2         | 0.39%   |
| Apple MacBookPro6,2                | 2         | 0.39%   |
| Apple MacBookPro5,5                | 2         | 0.39%   |
| Apple MacBookPro11,5               | 2         | 0.39%   |
| Apple MacBookAir7,2                | 2         | 0.39%   |
| Apple MacBookAir7,1                | 2         | 0.39%   |
| Apple MacBookAir6,2                | 2         | 0.39%   |
| Apple iMac9,1                      | 2         | 0.39%   |
| Apple iMac8,1                      | 2         | 0.39%   |
| Apple iMac11,3                     | 2         | 0.39%   |
| Acer Swift SF114-32                | 2         | 0.39%   |
| Wortmann AG 1220729_1470271        | 1         | 0.19%   |
| TrekStor Notebook Slim S130        | 1         | 0.19%   |
| Toshiba Satellite T130             | 1         | 0.19%   |
| Toshiba Satellite L875-11M         | 1         | 0.19%   |
| Toshiba Satellite L850D-BJS        | 1         | 0.19%   |
| Toshiba Satellite L50D-C           | 1         | 0.19%   |
| Toshiba Satellite C70D-A           | 1         | 0.19%   |
| Toshiba PORTEGE Z830               | 1         | 0.19%   |
| Teclast X6 plus                    | 1         | 0.19%   |
| Teclast F7                         | 1         | 0.19%   |
| Teclast F15S                       | 1         | 0.19%   |
| T-bao MINI PC                      | 1         | 0.19%   |
| Star Labs StarBook                 | 1         | 0.19%   |
| Star Labs LabTop                   | 1         | 0.19%   |
| Sony VPCYB20AL                     | 1         | 0.19%   |
| Sony VPCEB23FM                     | 1         | 0.19%   |
| Sony VPCEA3S1E                     | 1         | 0.19%   |
| Sony VPCCA4E1E                     | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 34        | 6.63%   |
| Lenovo IdeaPad     | 20        | 3.9%    |
| Acer Aspire        | 19        | 3.7%    |
| Dell Inspiron      | 16        | 3.12%   |
| HP Pavilion        | 13        | 2.53%   |
| Dell Latitude      | 12        | 2.34%   |
| HP ProBook         | 10        | 1.95%   |
| HP EliteBook       | 10        | 1.95%   |
| ASUS VivoBook      | 8         | 1.56%   |
| Microsoft Surface  | 7         | 1.36%   |
| ASUS ZenBook       | 7         | 1.36%   |
| ASUS PRIME         | 7         | 1.36%   |
| HP Laptop          | 6         | 1.17%   |
| Dell XPS           | 6         | 1.17%   |
| Dell OptiPlex      | 6         | 1.17%   |
| ASUS TUF           | 6         | 1.17%   |
| ASUS ROG           | 6         | 1.17%   |
| Apple MacBookPro8  | 6         | 1.17%   |
| Toshiba Satellite  | 5         | 0.97%   |
| HP ENVY            | 5         | 0.97%   |
| Dell Precision     | 5         | 0.97%   |
| Apple MacBook5     | 5         | 0.97%   |
| Acer Swift         | 5         | 0.97%   |
| HP Compaq          | 4         | 0.78%   |
| ASUS All           | 4         | 0.78%   |
| Apple MacBookPro5  | 4         | 0.78%   |
| Apple MacBookAir7  | 4         | 0.78%   |
| Lenovo ThinkCentre | 3         | 0.58%   |
| Lenovo ThinkBook   | 3         | 0.58%   |
| Lenovo Legion      | 3         | 0.58%   |
| HUAWEI MACHD-WXX9  | 3         | 0.58%   |
| HP ProDesk         | 3         | 0.58%   |
| HP Notebook        | 3         | 0.58%   |
| Dell Vostro        | 3         | 0.58%   |
| ASUS X550CA        | 3         | 0.58%   |
| ASUS P8H61-M       | 3         | 0.58%   |
| Apple MacBookAir6  | 3         | 0.58%   |
| Apple MacBookAir4  | 3         | 0.58%   |
| Apple MacBook4     | 3         | 0.58%   |
| Apple iMac7        | 3         | 0.58%   |
| Apple iMac11       | 3         | 0.58%   |
| Unknown            | 3         | 0.58%   |
| Timi TM1613        | 2         | 0.39%   |
| MSI Prestige       | 2         | 0.39%   |
| MSI MS-7C35        | 2         | 0.39%   |
| MSI Modern         | 2         | 0.39%   |
| Lenovo Yoga        | 2         | 0.39%   |
| Lenovo IdeaCentre  | 2         | 0.39%   |
| Lenovo G550        | 2         | 0.39%   |
| HUAWEI NBLK-WAX9X  | 2         | 0.39%   |
| HP Stream          | 2         | 0.39%   |
| HP ProLiant        | 2         | 0.39%   |
| HP 255             | 2         | 0.39%   |
| HP 240             | 2         | 0.39%   |
| Gigabyte Z390      | 2         | 0.39%   |
| Apple Macmini5     | 2         | 0.39%   |
| Apple MacBookPro9  | 2         | 0.39%   |
| Apple MacBookPro6  | 2         | 0.39%   |
| Apple MacBookPro11 | 2         | 0.39%   |
| Apple iMac9        | 2         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 59        | 11.5%   |
| 2018    | 50        | 9.75%   |
| 2012    | 47        | 9.16%   |
| 2019    | 45        | 8.77%   |
| 2021    | 42        | 8.19%   |
| 2011    | 38        | 7.41%   |
| 2015    | 36        | 7.02%   |
| 2013    | 36        | 7.02%   |
| 2016    | 31        | 6.04%   |
| 2010    | 30        | 5.85%   |
| 2014    | 28        | 5.46%   |
| 2017    | 23        | 4.48%   |
| 2009    | 21        | 4.09%   |
| 2008    | 15        | 2.92%   |
| 2007    | 5         | 0.97%   |
| 2022    | 4         | 0.78%   |
| 2006    | 2         | 0.39%   |
| Unknown | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 328       | 63.94%  |
| Desktop        | 137       | 26.71%  |
| All in one     | 16        | 3.12%   |
| Tablet         | 11        | 2.14%   |
| Convertible    | 11        | 2.14%   |
| Mini pc        | 8         | 1.56%   |
| System on chip | 1         | 0.19%   |
| Server         | 1         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 443       | 86.19%  |
| Enabled  | 71        | 13.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 509       | 99.22%  |
| Yes  | 4         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 148       | 28.68%  |
| 3.01-4.0    | 111       | 21.51%  |
| 16.01-24.0  | 94        | 18.22%  |
| 8.01-16.0   | 88        | 17.05%  |
| 32.01-64.0  | 45        | 8.72%   |
| 1.01-2.0    | 16        | 3.1%    |
| 64.01-256.0 | 7         | 1.36%   |
| 24.01-32.0  | 4         | 0.78%   |
| 2.01-3.0    | 3         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 206       | 37.59%  |
| 2.01-3.0   | 164       | 29.93%  |
| 3.01-4.0   | 82        | 14.96%  |
| 4.01-8.0   | 58        | 10.58%  |
| 0.51-1.0   | 19        | 3.47%   |
| 8.01-16.0  | 17        | 3.1%    |
| 24.01-32.0 | 1         | 0.18%   |
| 16.01-24.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 324       | 62.55%  |
| 2      | 138       | 26.64%  |
| 3      | 28        | 5.41%   |
| 4      | 14        | 2.7%    |
| 5      | 6         | 1.16%   |
| 6      | 4         | 0.77%   |
| 7      | 2         | 0.39%   |
| 0      | 2         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 326       | 62.93%  |
| Yes       | 192       | 37.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 404       | 78.75%  |
| No        | 109       | 21.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 435       | 84.3%   |
| No        | 81        | 15.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 393       | 76.02%  |
| No        | 124       | 23.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 73        | 14.23%  |
| Germany         | 60        | 11.7%   |
| Brazil          | 30        | 5.85%   |
| UK              | 29        | 5.65%   |
| Russia          | 27        | 5.26%   |
| Italy           | 22        | 4.29%   |
| India           | 19        | 3.7%    |
| France          | 18        | 3.51%   |
| Spain           | 17        | 3.31%   |
| Indonesia       | 14        | 2.73%   |
| Canada          | 14        | 2.73%   |
| Australia       | 14        | 2.73%   |
| Poland          | 13        | 2.53%   |
| Turkey          | 12        | 2.34%   |
| Mexico          | 10        | 1.95%   |
| Austria         | 9         | 1.75%   |
| Argentina       | 9         | 1.75%   |
| Switzerland     | 8         | 1.56%   |
| Netherlands     | 8         | 1.56%   |
| Belgium         | 7         | 1.36%   |
| Chile           | 6         | 1.17%   |
| Portugal        | 5         | 0.97%   |
| New Zealand     | 5         | 0.97%   |
| Sweden          | 4         | 0.78%   |
| Romania         | 4         | 0.78%   |
| Norway          | 4         | 0.78%   |
| Japan           | 4         | 0.78%   |
| Czechia         | 4         | 0.78%   |
| Ukraine         | 3         | 0.58%   |
| South Africa    | 3         | 0.58%   |
| Iran            | 3         | 0.58%   |
| Hungary         | 3         | 0.58%   |
| Colombia        | 3         | 0.58%   |
| China           | 3         | 0.58%   |
| Belarus         | 3         | 0.58%   |
| Sri Lanka       | 2         | 0.39%   |
| Serbia          | 2         | 0.39%   |
| Pakistan        | 2         | 0.39%   |
| Malaysia        | 2         | 0.39%   |
| Lithuania       | 2         | 0.39%   |
| Kenya           | 2         | 0.39%   |
| Israel          | 2         | 0.39%   |
| Ireland         | 2         | 0.39%   |
| Finland         | 2         | 0.39%   |
| Estonia         | 2         | 0.39%   |
| Croatia         | 2         | 0.39%   |
| Bulgaria        | 2         | 0.39%   |
| Zambia          | 1         | 0.19%   |
| Vietnam         | 1         | 0.19%   |
| Venezuela       | 1         | 0.19%   |
| Thailand        | 1         | 0.19%   |
| Taiwan          | 1         | 0.19%   |
| Senegal         | 1         | 0.19%   |
| Peru            | 1         | 0.19%   |
| North Macedonia | 1         | 0.19%   |
| Nicaragua       | 1         | 0.19%   |
| Mozambique      | 1         | 0.19%   |
| Luxembourg      | 1         | 0.19%   |
| Latvia          | 1         | 0.19%   |
| Iceland         | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sydney                 | 9         | 1.69%   |
| Moscow                 | 9         | 1.69%   |
| Warsaw                 | 6         | 1.13%   |
| Munich                 | 6         | 1.13%   |
| Hamburg                | 6         | 1.13%   |
| Istanbul               | 5         | 0.94%   |
| Vienna                 | 4         | 0.75%   |
| The Hague              | 4         | 0.75%   |
| St Petersburg          | 4         | 0.75%   |
| Tangerang              | 3         | 0.56%   |
| Sao Paulo              | 3         | 0.56%   |
| Rome                   | 3         | 0.56%   |
| Paris                  | 3         | 0.56%   |
| Milan                  | 3         | 0.56%   |
| Madrid                 | 3         | 0.56%   |
| Jakarta                | 3         | 0.56%   |
| Bogor                  | 3         | 0.56%   |
| Berlin                 | 3         | 0.56%   |
| Ankara                 | 3         | 0.56%   |
| Wroclaw                | 2         | 0.38%   |
| Wolgast                | 2         | 0.38%   |
| Tucson                 | 2         | 0.38%   |
| Toronto                | 2         | 0.38%   |
| Teresina               | 2         | 0.38%   |
| Tel Aviv               | 2         | 0.38%   |
| Tehran                 | 2         | 0.38%   |
| Santo André           | 2         | 0.38%   |
| Porto                  | 2         | 0.38%   |
| Nairobi                | 2         | 0.38%   |
| Muralto                | 2         | 0.38%   |
| Mumbai                 | 2         | 0.38%   |
| Monza                  | 2         | 0.38%   |
| Montornès del Vallès | 2         | 0.38%   |
| Minsk                  | 2         | 0.38%   |
| Louisville             | 2         | 0.38%   |
| Liverpool              | 2         | 0.38%   |
| Kingston               | 2         | 0.38%   |
| Islamabad              | 2         | 0.38%   |
| Dublin                 | 2         | 0.38%   |
| Dresden                | 2         | 0.38%   |
| Denver                 | 2         | 0.38%   |
| Cologne                | 2         | 0.38%   |
| Chelyabinsk            | 2         | 0.38%   |
| Caslano                | 2         | 0.38%   |
| Cankaya                | 2         | 0.38%   |
| Brisbane               | 2         | 0.38%   |
| Bonn                   | 2         | 0.38%   |
| Bern                   | 2         | 0.38%   |
| Belo Horizonte         | 2         | 0.38%   |
| Austin                 | 2         | 0.38%   |
| Antalya                | 2         | 0.38%   |
| Zhengzhou              | 1         | 0.19%   |
| Zagreb                 | 1         | 0.19%   |
| Yucca Valley           | 1         | 0.19%   |
| Ypres                  | 1         | 0.19%   |
| Yokohama               | 1         | 0.19%   |
| Yaroslavl              | 1         | 0.19%   |
| Yarang                 | 1         | 0.19%   |
| Wuhan                  | 1         | 0.19%   |
| Woolloongabba          | 1         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 109       | 144    | 15.06%  |
| Seagate                   | 90        | 106    | 12.43%  |
| WDC                       | 88        | 118    | 12.15%  |
| Toshiba                   | 49        | 58     | 6.77%   |
| Kingston                  | 48        | 59     | 6.63%   |
| SanDisk                   | 40        | 43     | 5.52%   |
| Crucial                   | 30        | 35     | 4.14%   |
| Unknown                   | 29        | 40     | 4.01%   |
| HGST                      | 18        | 19     | 2.49%   |
| SK hynix                  | 17        | 18     | 2.35%   |
| Apple                     | 17        | 20     | 2.35%   |
| Intel                     | 16        | 18     | 2.21%   |
| Hitachi                   | 16        | 16     | 2.21%   |
| A-DATA Technology         | 11        | 11     | 1.52%   |
| Phison                    | 10        | 10     | 1.38%   |
| Micron Technology         | 9         | 11     | 1.24%   |
| PNY                       | 8         | 14     | 1.1%    |
| KIOXIA                    | 8         | 9      | 1.1%    |
| Micron/Crucial Technology | 6         | 9      | 0.83%   |
| China                     | 6         | 6      | 0.83%   |
| JMicron Technology        | 5         | 5      | 0.69%   |
| Silicon Motion            | 4         | 4      | 0.55%   |
| Unknown                   | 4         | 5      | 0.55%   |
| Transcend                 | 3         | 3      | 0.41%   |
| Team                      | 3         | 4      | 0.41%   |
| OCZ                       | 3         | 5      | 0.41%   |
| Maxtor                    | 3         | 3      | 0.41%   |
| LITEON                    | 3         | 3      | 0.41%   |
| Leven                     | 3         | 3      | 0.41%   |
| Fujitsu                   | 3         | 3      | 0.41%   |
| ASMT                      | 3         | 3      | 0.41%   |
| XPG                       | 2         | 2      | 0.28%   |
| TO Exter                  | 2         | 2      | 0.28%   |
| Teclast                   | 2         | 2      | 0.28%   |
| Realtek Semiconductor     | 2         | 2      | 0.28%   |
| Plextor                   | 2         | 3      | 0.28%   |
| Netac                     | 2         | 2      | 0.28%   |
| Lite-On                   | 2         | 2      | 0.28%   |
| KingDian                  | 2         | 2      | 0.28%   |
| GOODRAM                   | 2         | 2      | 0.28%   |
| FORESEE                   | 2         | 2      | 0.28%   |
| EYOTA                     | 2         | 2      | 0.28%   |
| Dogfish                   | 2         | 2      | 0.28%   |
| Apacer                    | 2         | 2      | 0.28%   |
| ZTE                       | 1         | 1      | 0.14%   |
| V-GeN                     | 1         | 1      | 0.14%   |
| UMIS                      | 1         | 1      | 0.14%   |
| Timetec                   | 1         | 1      | 0.14%   |
| tigo                      | 1         | 1      | 0.14%   |
| Super Talent              | 1         | 1      | 0.14%   |
| Star Drive                | 1         | 1      | 0.14%   |
| Star                      | 1         | 1      | 0.14%   |
| SSSTC                     | 1         | 1      | 0.14%   |
| SSK                       | 1         | 1      | 0.14%   |
| SSDPR-CX                  | 1         | 1      | 0.14%   |
| SPCC                      | 1         | 1      | 0.14%   |
| Smartbuy                  | 1         | 1      | 0.14%   |
| SABRENT                   | 1         | 1      | 0.14%   |
| Pichau                    | 1         | 1      | 0.14%   |
| Patriot                   | 1         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 11        | 1.42%   |
| Samsung NVMe SSD Drive 500GB            | 10        | 1.3%    |
| Samsung NVMe SSD Drive 256GB            | 10        | 1.3%    |
| Kingston SA400S37240G 240GB SSD         | 10        | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB          | 9         | 1.17%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 0.91%   |
| SK hynix NVMe SSD Drive 256GB           | 7         | 0.91%   |
| SanDisk NVMe SSD Drive 512GB            | 7         | 0.91%   |
| Samsung SSD 860 EVO 250GB               | 7         | 0.91%   |
| Unknown MMC Card  32GB                  | 6         | 0.78%   |
| Samsung SSD 850 EVO 250GB               | 6         | 0.78%   |
| Kingston SA400S37120G 120GB SSD         | 6         | 0.78%   |
| Intel NVMe SSD Drive 512GB              | 6         | 0.78%   |
| Crucial CT240BX500SSD1 240GB            | 6         | 0.78%   |
| Toshiba DT01ACA050 500GB                | 5         | 0.65%   |
| Seagate ST500LT012-1DG142 500GB         | 5         | 0.65%   |
| Phison NVMe SSD Drive 1TB               | 5         | 0.65%   |
| Micron/Crucial NVMe SSD Drive 1TB       | 5         | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 4         | 0.52%   |
| Unknown MMC Card  64GB                  | 4         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB            | 4         | 0.52%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 0.52%   |
| Toshiba MQ01ABF050 500GB                | 4         | 0.52%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 4         | 0.52%   |
| SK hynix NVMe SSD Drive 512GB           | 4         | 0.52%   |
| Seagate ST3500418AS 500GB               | 4         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB          | 4         | 0.52%   |
| Samsung SSD 860 EVO 500GB               | 4         | 0.52%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 4         | 0.52%   |
| Samsung NVMe SSD Drive 1TB              | 4         | 0.52%   |
| PNY CS900 480GB SSD                     | 4         | 0.52%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 4         | 0.52%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 0.52%   |
| Kingston NVMe SSD Drive 500GB           | 4         | 0.52%   |
| JMicron Tech 250GB                      | 4         | 0.52%   |
| HGST HTS721010A9E630 1TB                | 4         | 0.52%   |
| HGST HTS545050A7E680 500GB              | 4         | 0.52%   |
| HGST HTS541010B7E610 1TB                | 4         | 0.52%   |
| Crucial CT480BX500SSD1 480GB            | 4         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.52%   |
| Unknown                                 | 4         | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 3         | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                | 3         | 0.39%   |
| Unknown SD/MMC 16GB                     | 3         | 0.39%   |
| Unknown MMC Card  128GB                 | 3         | 0.39%   |
| Unknown M.S./M.S.Pro/HG 16GB            | 3         | 0.39%   |
| Toshiba DT01ACA100 1TB                  | 3         | 0.39%   |
| Seagate ST9500325AS 500GB               | 3         | 0.39%   |
| Seagate ST500DM002-1BD142 500GB         | 3         | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.39%   |
| SanDisk NVMe SSD Drive 1024GB           | 3         | 0.39%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.39%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.39%   |
| Samsung SSD 840 EVO 250GB               | 3         | 0.39%   |
| Samsung SSD 840 EVO 120GB               | 3         | 0.39%   |
| Kingston NVMe SSD Drive 1TB             | 3         | 0.39%   |
| A-DATA SU650 120GB SSD                  | 3         | 0.39%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.26%   |
| WDC WD5000AAKX-001CA0 500GB             | 2         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 102    | 34.8%   |
| WDC                 | 69        | 90     | 27.6%   |
| Toshiba             | 38        | 46     | 15.2%   |
| HGST                | 18        | 19     | 7.2%    |
| Hitachi             | 16        | 16     | 6.4%    |
| Samsung Electronics | 7         | 8      | 2.8%    |
| Fujitsu             | 3         | 3      | 1.2%    |
| ASMT                | 3         | 3      | 1.2%    |
| Unknown             | 2         | 2      | 0.8%    |
| Maxtor              | 2         | 2      | 0.8%    |
| Apple               | 2         | 2      | 0.8%    |
| SABRENT             | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| Ext Hard            | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 77     | 22.47%  |
| Kingston            | 34        | 38     | 12.73%  |
| Crucial             | 29        | 33     | 10.86%  |
| SanDisk             | 23        | 25     | 8.61%   |
| WDC                 | 14        | 18     | 5.24%   |
| Apple               | 14        | 15     | 5.24%   |
| A-DATA Technology   | 9         | 9      | 3.37%   |
| PNY                 | 8         | 14     | 3%      |
| Micron Technology   | 6         | 7      | 2.25%   |
| Intel               | 6         | 6      | 2.25%   |
| China               | 6         | 6      | 2.25%   |
| Transcend           | 3         | 3      | 1.12%   |
| Toshiba             | 3         | 3      | 1.12%   |
| Team                | 3         | 4      | 1.12%   |
| OCZ                 | 3         | 5      | 1.12%   |
| LITEON              | 3         | 3      | 1.12%   |
| TO Exter            | 2         | 2      | 0.75%   |
| Teclast             | 2         | 2      | 0.75%   |
| Plextor             | 2         | 3      | 0.75%   |
| Leven               | 2         | 2      | 0.75%   |
| GOODRAM             | 2         | 2      | 0.75%   |
| FORESEE             | 2         | 2      | 0.75%   |
| Dogfish             | 2         | 2      | 0.75%   |
| Apacer              | 2         | 2      | 0.75%   |
| tigo                | 1         | 1      | 0.37%   |
| Super Talent        | 1         | 1      | 0.37%   |
| Star                | 1         | 1      | 0.37%   |
| SPCC                | 1         | 1      | 0.37%   |
| Smartbuy            | 1         | 1      | 0.37%   |
| SK hynix            | 1         | 1      | 0.37%   |
| Seagate             | 1         | 2      | 0.37%   |
| Pichau              | 1         | 1      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| Patriot             | 1         | 2      | 0.37%   |
| OCZ-VERTEX2         | 1         | 1      | 0.37%   |
| NGFF                | 1         | 1      | 0.37%   |
| Netac               | 1         | 1      | 0.37%   |
| MidasForce          | 1         | 1      | 0.37%   |
| MENGMI              | 1         | 1      | 0.37%   |
| Maxtor              | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| KingSpec            | 1         | 1      | 0.37%   |
| KingDian            | 1         | 1      | 0.37%   |
| JMicron Technology  | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| Gigabyte Technology | 1         | 1      | 0.37%   |
| EYOTA               | 1         | 1      | 0.37%   |
| EVM                 | 1         | 1      | 0.37%   |
| Corsair             | 1         | 1      | 0.37%   |
| Colorful            | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 247       | 312    | 36.54%  |
| HDD     | 223       | 296    | 32.99%  |
| NVMe    | 154       | 195    | 22.78%  |
| MMC     | 27        | 31     | 3.99%   |
| Unknown | 25        | 36     | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 391       | 602    | 64.74%  |
| NVMe | 154       | 195    | 25.5%   |
| SAS  | 32        | 42     | 5.3%    |
| MMC  | 27        | 31     | 4.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 308       | 411    | 67.54%  |
| 0.51-1.0   | 106       | 141    | 23.25%  |
| 1.01-2.0   | 22        | 27     | 4.82%   |
| 3.01-4.0   | 7         | 8      | 1.54%   |
| 2.01-3.0   | 7         | 14     | 1.54%   |
| 4.01-10.0  | 6         | 7      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 201       | 38.65%  |
| 251-500        | 131       | 25.19%  |
| 501-1000       | 81        | 15.58%  |
| 51-100         | 40        | 7.69%   |
| 1001-2000      | 30        | 5.77%   |
| 21-50          | 21        | 4.04%   |
| More than 3000 | 11        | 2.12%   |
| 2001-3000      | 3         | 0.58%   |
| 1-20           | 1         | 0.19%   |
| Unknown        | 1         | 0.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 245       | 45.54%  |
| 21-50          | 120       | 22.3%   |
| 51-100         | 61        | 11.34%  |
| 101-250        | 54        | 10.04%  |
| 251-500        | 27        | 5.02%   |
| 501-1000       | 18        | 3.35%   |
| 1001-2000      | 7         | 1.3%    |
| More than 3000 | 3         | 0.56%   |
| 2001-3000      | 2         | 0.37%   |
| Unknown        | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB            | 1         | 1      | 8.33%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 8.33%   |
| Toshiba KBG30ZPZ128G 128GB              | 1         | 1      | 8.33%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1      | 8.33%   |
| Seagate ST3500312CS 500GB               | 1         | 1      | 8.33%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 8.33%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 8.33%   |
| Kingston SUV400S37480G 480GB SSD        | 1         | 1      | 8.33%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 8.33%   |
| Crucial CT512M550SSD3 512GB             | 1         | 1      | 8.33%   |
| Apple SSD SM256C 256GB                  | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 3         | 3      | 25%     |
| WDC      | 2         | 2      | 16.67%  |
| Seagate  | 2         | 2      | 16.67%  |
| Toshiba  | 1         | 1      | 8.33%   |
| SanDisk  | 1         | 1      | 8.33%   |
| HGST     | 1         | 1      | 8.33%   |
| Crucial  | 1         | 1      | 8.33%   |
| Apple    | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 6      | 50%     |
| HDD  | 5         | 5      | 41.67%  |
| NVMe | 1         | 1      | 8.33%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 452       | 755    | 84.49%  |
| Works    | 71        | 103    | 13.27%  |
| Malfunc  | 12        | 12     | 2.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 349       | 56.29%  |
| AMD                            | 75        | 12.1%   |
| Samsung Electronics            | 55        | 8.87%   |
| SanDisk                        | 21        | 3.39%   |
| Nvidia                         | 20        | 3.23%   |
| SK hynix                       | 16        | 2.58%   |
| Kingston Technology Company    | 16        | 2.58%   |
| Phison Electronics             | 10        | 1.61%   |
| Toshiba America Info Systems   | 8         | 1.29%   |
| Micron/Crucial Technology      | 7         | 1.13%   |
| Marvell Technology Group       | 7         | 1.13%   |
| KIOXIA                         | 6         | 0.97%   |
| Silicon Motion                 | 4         | 0.65%   |
| Realtek Semiconductor          | 4         | 0.65%   |
| ASMedia Technology             | 4         | 0.65%   |
| Micron Technology              | 3         | 0.48%   |
| Seagate Technology             | 2         | 0.32%   |
| Lite-On Technology             | 2         | 0.32%   |
| JMicron Technology             | 2         | 0.32%   |
| Apple                          | 2         | 0.32%   |
| ADATA Technology               | 2         | 0.32%   |
| Union Memory (Shenzhen)        | 1         | 0.16%   |
| Solid State Storage Technology | 1         | 0.16%   |
| LSI Logic / Symbios Logic      | 1         | 0.16%   |
| Hewlett-Packard                | 1         | 0.16%   |
| Biwin Storage Technology       | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 59        | 8.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 32        | 4.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 29        | 4.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20        | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20        | 2.91%   |
| Samsung NVMe SSD Controller 980                                                         | 16        | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15        | 2.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 14        | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 1.74%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.6%    |
| Nvidia MCP79 AHCI Controller                                                            | 10        | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 10        | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 1.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 1.31%   |
| Intel SSD 660P Series                                                                   | 8         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 1.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6         | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 0.87%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 6         | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                         | 6         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 6         | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6         | 0.87%   |
| SK hynix Gold P31 SSD                                                                   | 5         | 0.73%   |
| SK hynix BC511                                                                          | 5         | 0.73%   |
| Samsung Electronics SATA controller                                                     | 5         | 0.73%   |
| Phison E12 NVMe Controller                                                              | 5         | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.73%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.58%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 4         | 0.58%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 0.58%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 0.58%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 0.58%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.44%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.44%   |
| Realtek Realtek Non-Volatile memory controller                                          | 3         | 0.44%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.44%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 3         | 0.44%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 3         | 0.44%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 390       | 62.1%   |
| NVMe | 152       | 24.2%   |
| IDE  | 54        | 8.6%    |
| RAID | 31        | 4.94%   |
| SAS  | 1         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 410       | 79.92%  |
| AMD    | 102       | 19.88%  |
| ARM    | 1         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 2.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 0.97%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.97%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.78%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.58%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.58%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 3         | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.58%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 3         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.58%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 3         | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.58%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.58%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.58%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.58%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.58%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 3         | 0.58%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 3         | 0.58%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 3         | 0.58%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.58%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.39%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.39%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.39%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.39%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.39%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 2         | 0.39%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 2         | 0.39%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.39%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.39%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 2         | 0.39%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.39%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.39%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 114       | 22.22%  |
| Intel Core i7           | 109       | 21.25%  |
| Intel Core i3           | 52        | 10.14%  |
| Intel Celeron           | 32        | 6.24%   |
| Intel Core 2 Duo        | 31        | 6.04%   |
| Other                   | 30        | 5.85%   |
| AMD Ryzen 5             | 30        | 5.85%   |
| AMD Ryzen 7             | 21        | 4.09%   |
| Intel Xeon              | 12        | 2.34%   |
| Intel Pentium           | 11        | 2.14%   |
| AMD Ryzen 9             | 6         | 1.17%   |
| AMD Ryzen 3             | 6         | 1.17%   |
| Intel Atom              | 5         | 0.97%   |
| AMD A8                  | 4         | 0.78%   |
| AMD A6                  | 4         | 0.78%   |
| AMD A10                 | 4         | 0.78%   |
| Intel Pentium Silver    | 3         | 0.58%   |
| Intel Core 2 Quad       | 3         | 0.58%   |
| AMD Ryzen 7 PRO         | 3         | 0.58%   |
| AMD Phenom II X4        | 3         | 0.58%   |
| AMD FX                  | 3         | 0.58%   |
| AMD Athlon II X2        | 3         | 0.58%   |
| AMD A12                 | 3         | 0.58%   |
| Intel Pentium Dual-Core | 2         | 0.39%   |
| Intel Genuine           | 2         | 0.39%   |
| Intel Core i9           | 2         | 0.39%   |
| Intel Celeron Dual-Core | 2         | 0.39%   |
| AMD Athlon              | 2         | 0.39%   |
| AMD A4                  | 2         | 0.39%   |
| Intel Pentium Dual      | 1         | 0.19%   |
| Intel Core m5           | 1         | 0.19%   |
| Intel Core m3           | 1         | 0.19%   |
| Intel Core 2            | 1         | 0.19%   |
| AMD Ryzen 5 PRO         | 1         | 0.19%   |
| AMD E1                  | 1         | 0.19%   |
| AMD E                   | 1         | 0.19%   |
| AMD Athlon X4           | 1         | 0.19%   |
| AMD Athlon II X4        | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 237       | 46.02%  |
| 4      | 190       | 36.89%  |
| 8      | 39        | 7.57%   |
| 6      | 36        | 6.99%   |
| 12     | 6         | 1.17%   |
| 1      | 4         | 0.78%   |
| 16     | 2         | 0.39%   |
| 3      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 510       | 99.42%  |
| 2      | 3         | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 357       | 69.46%  |
| 1      | 157       | 30.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 512       | 99.81%  |
| 64-bit         | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 47        | 9.07%   |
| 0x306a9    | 40        | 7.72%   |
| Unknown    | 39        | 7.53%   |
| 0x306c3    | 23        | 4.44%   |
| 0x1067a    | 21        | 4.05%   |
| 0x806c1    | 17        | 3.28%   |
| 0x306d4    | 16        | 3.09%   |
| 0x406e3    | 15        | 2.9%    |
| 0x40651    | 15        | 2.9%    |
| 0x20655    | 15        | 2.9%    |
| 0x806ec    | 13        | 2.51%   |
| 0x806e9    | 13        | 2.51%   |
| 0x10676    | 11        | 2.12%   |
| 0x08108109 | 10        | 1.93%   |
| 0x806ea    | 9         | 1.74%   |
| 0xa0652    | 8         | 1.54%   |
| 0x706a8    | 8         | 1.54%   |
| 0x506e3    | 8         | 1.54%   |
| 0x08701021 | 8         | 1.54%   |
| 0x906ea    | 7         | 1.35%   |
| 0x906e9    | 7         | 1.35%   |
| 0x706e5    | 7         | 1.35%   |
| 0x20652    | 7         | 1.35%   |
| 0x08600106 | 7         | 1.35%   |
| 0x506c9    | 6         | 1.16%   |
| 0x406c3    | 6         | 1.16%   |
| 0x30678    | 6         | 1.16%   |
| 0x906ed    | 5         | 0.97%   |
| 0x806eb    | 5         | 0.97%   |
| 0x706a1    | 5         | 0.97%   |
| 0x0a50000c | 5         | 0.97%   |
| 0x08608103 | 5         | 0.97%   |
| 0x06006705 | 5         | 0.97%   |
| 0x6fd      | 4         | 0.77%   |
| 0x406c4    | 4         | 0.77%   |
| 0x206d7    | 4         | 0.77%   |
| 0x106e5    | 4         | 0.77%   |
| 0x08108102 | 4         | 0.77%   |
| 0x0800820d | 4         | 0.77%   |
| 0x06001119 | 4         | 0.77%   |
| 0xa0671    | 3         | 0.58%   |
| 0x906eb    | 3         | 0.58%   |
| 0x806c2    | 3         | 0.58%   |
| 0x6fb      | 3         | 0.58%   |
| 0x6fa      | 3         | 0.58%   |
| 0x08600104 | 3         | 0.58%   |
| 0x0810100b | 3         | 0.58%   |
| 0x08101007 | 3         | 0.58%   |
| 0x010000c8 | 3         | 0.58%   |
| 0xa0655    | 2         | 0.39%   |
| 0xa0653    | 2         | 0.39%   |
| 0x40661    | 2         | 0.39%   |
| 0x0a201016 | 2         | 0.39%   |
| 0x08701013 | 2         | 0.39%   |
| 0x08001138 | 2         | 0.39%   |
| 0x0700010f | 2         | 0.39%   |
| 0x0600611a | 2         | 0.39%   |
| 0x06003106 | 2         | 0.39%   |
| 0x06000852 | 2         | 0.39%   |
| 0x03000027 | 2         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 74        | 14.42%  |
| SandyBridge      | 53        | 10.33%  |
| Haswell          | 44        | 8.58%   |
| IvyBridge        | 42        | 8.19%   |
| Penryn           | 32        | 6.24%   |
| Zen 2            | 24        | 4.68%   |
| Skylake          | 24        | 4.68%   |
| Westmere         | 23        | 4.48%   |
| TigerLake        | 22        | 4.29%   |
| Zen+             | 20        | 3.9%    |
| Silvermont       | 17        | 3.31%   |
| Broadwell        | 17        | 3.31%   |
| Goldmont plus    | 13        | 2.53%   |
| CometLake        | 13        | 2.53%   |
| Core             | 12        | 2.34%   |
| Zen 3            | 10        | 1.95%   |
| IceLake          | 10        | 1.95%   |
| Excavator        | 10        | 1.95%   |
| Zen              | 9         | 1.75%   |
| K10              | 7         | 1.36%   |
| Unknown          | 7         | 1.36%   |
| Piledriver       | 6         | 1.17%   |
| Goldmont         | 6         | 1.17%   |
| Nehalem          | 5         | 0.97%   |
| Steamroller      | 2         | 0.39%   |
| Puma             | 2         | 0.39%   |
| K10 Llano        | 2         | 0.39%   |
| Jaguar           | 2         | 0.39%   |
| Tremont          | 1         | 0.19%   |
| Bulldozer        | 1         | 0.19%   |
| Bonnell          | 1         | 0.19%   |
| Bobcat           | 1         | 0.19%   |
| Alderlake Hybrid | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 322       | 52.87%  |
| AMD                        | 154       | 25.29%  |
| Nvidia                     | 132       | 21.67%  |
| Matrox Electronics Systems | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 7.01%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 4.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 2.55%   |
| AMD Renoir                                                                               | 14        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 1.91%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.91%   |
| Intel UHD Graphics 620                                                                   | 11        | 1.75%   |
| Intel HD Graphics 620                                                                    | 11        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.43%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.96%   |
| AMD Lucienne                                                                             | 6         | 0.96%   |
| Intel HD Graphics 630                                                                    | 5         | 0.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.8%    |
| AMD Cezanne                                                                              | 5         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.64%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.64%   |
| Intel HD Graphics 530                                                                    | 4         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.64%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.64%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 4         | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4         | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 0.48%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.48%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.48%   |
| Intel HD Graphics 500                                                                    | 3         | 0.48%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.48%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.48%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.48%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 3         | 0.48%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.32%   |
| Nvidia TU117M                                                                            | 2         | 0.32%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.32%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.32%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 231       | 44.85%  |
| 1 x AMD        | 116       | 22.52%  |
| 1 x Nvidia     | 64        | 12.43%  |
| Intel + Nvidia | 62        | 12.04%  |
| Intel + AMD    | 25        | 4.85%   |
| 2 x AMD        | 9         | 1.75%   |
| AMD + Nvidia   | 4         | 0.78%   |
| 2 x Nvidia     | 2         | 0.39%   |
| Other          | 1         | 0.19%   |
| 1 x Matrox     | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 450       | 87.38%  |
| Proprietary | 61        | 11.84%  |
| Unknown     | 4         | 0.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 269       | 51.83%  |
| 1.01-2.0   | 68        | 13.1%   |
| 0.01-0.5   | 68        | 13.1%   |
| 0.51-1.0   | 50        | 9.63%   |
| 3.01-4.0   | 34        | 6.55%   |
| 5.01-6.0   | 13        | 2.5%    |
| 7.01-8.0   | 11        | 2.12%   |
| 2.01-3.0   | 3         | 0.58%   |
| 8.01-16.0  | 3         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 11.9%   |
| Samsung Electronics     | 62        | 10.69%  |
| LG Display              | 61        | 10.52%  |
| Apple                   | 55        | 9.48%   |
| Chimei Innolux          | 48        | 8.28%   |
| BOE                     | 45        | 7.76%   |
| Dell                    | 23        | 3.97%   |
| Hewlett-Packard         | 22        | 3.79%   |
| Goldstar                | 22        | 3.79%   |
| Acer                    | 18        | 3.1%    |
| Lenovo                  | 15        | 2.59%   |
| Sharp                   | 14        | 2.41%   |
| Philips                 | 12        | 2.07%   |
| AOC                     | 10        | 1.72%   |
| Chi Mei Optoelectronics | 9         | 1.55%   |
| BenQ                    | 9         | 1.55%   |
| Ancor Communications    | 8         | 1.38%   |
| PANDA                   | 7         | 1.21%   |
| InfoVision              | 6         | 1.03%   |
| Sony                    | 5         | 0.86%   |
| CSO                     | 4         | 0.69%   |
| ViewSonic               | 3         | 0.52%   |
| Unknown                 | 3         | 0.52%   |
| NEC Computers           | 3         | 0.52%   |
| LG Electronics          | 3         | 0.52%   |
| AUS                     | 3         | 0.52%   |
| Vizio                   | 2         | 0.34%   |
| Panasonic               | 2         | 0.34%   |
| Onkyo                   | 2         | 0.34%   |
| Iiyama                  | 2         | 0.34%   |
| HPN                     | 2         | 0.34%   |
| Fujitsu Siemens         | 2         | 0.34%   |
| ___                     | 1         | 0.17%   |
| Vestel                  | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| TMX                     | 1         | 0.17%   |
| SPC                     | 1         | 0.17%   |
| SANYO                   | 1         | 0.17%   |
| Plain Tree Systems      | 1         | 0.17%   |
| Packard Bell            | 1         | 0.17%   |
| MSI                     | 1         | 0.17%   |
| Mi                      | 1         | 0.17%   |
| Marantz                 | 1         | 0.17%   |
| LLP                     | 1         | 0.17%   |
| LG Philips              | 1         | 0.17%   |
| Konka                   | 1         | 0.17%   |
| JDI                     | 1         | 0.17%   |
| IOD                     | 1         | 0.17%   |
| HUAWEI                  | 1         | 0.17%   |
| HJC                     | 1         | 0.17%   |
| Hitachi                 | 1         | 0.17%   |
| HannStar                | 1         | 0.17%   |
| Gateway                 | 1         | 0.17%   |
| EXP                     | 1         | 0.17%   |
| Element                 | 1         | 0.17%   |
| Eizo                    | 1         | 0.17%   |
| DPL                     | 1         | 0.17%   |
| CPT                     | 1         | 0.17%   |
| CHR                     | 1         | 0.17%   |
| CHD                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.67%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 0.67%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3         | 0.5%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.5%    |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.5%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.5%    |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.5%    |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.5%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.5%    |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 3         | 0.5%    |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 3         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.33%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 2         | 0.33%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch             | 2         | 0.33%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.33%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.33%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 344x193mm 15.5-inch      | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x174mm 14.0-inch       | 2         | 0.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.33%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.33%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 2         | 0.33%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.33%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.33%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.33%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 2         | 0.33%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 2         | 0.33%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 0.33%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.33%   |
| Apple Color LCD APP9CD7 2560x1440 597x336mm 27.0-inch                 | 2         | 0.33%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.33%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.17%   |
| Vizio VO320E VIZ0035 1280x720 700x390mm 31.5-inch                     | 1         | 0.17%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                   | 1         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 222       | 39.43%  |
| 1366x768 (WXGA)    | 126       | 22.38%  |
| 3840x2160 (4K)     | 32        | 5.68%   |
| 2560x1440 (QHD)    | 27        | 4.8%    |
| 1600x900 (HD+)     | 24        | 4.26%   |
| 1440x900 (WXGA+)   | 24        | 4.26%   |
| 1680x1050 (WSXGA+) | 22        | 3.91%   |
| 1280x800 (WXGA)    | 16        | 2.84%   |
| 1920x1200 (WUXGA)  | 12        | 2.13%   |
| 1280x1024 (SXGA)   | 7         | 1.24%   |
| 1360x768           | 5         | 0.89%   |
| Unknown            | 5         | 0.89%   |
| 3840x1080          | 4         | 0.71%   |
| 3000x2000          | 4         | 0.71%   |
| 2880x1800          | 4         | 0.71%   |
| 3440x1440          | 3         | 0.53%   |
| 2560x1080          | 3         | 0.53%   |
| 5120x1440          | 2         | 0.36%   |
| 3840x2400          | 2         | 0.36%   |
| 3200x1800 (QHD+)   | 2         | 0.36%   |
| 2736x1824          | 2         | 0.36%   |
| 2560x1600          | 2         | 0.36%   |
| 1920x540           | 2         | 0.36%   |
| 1920x1280          | 2         | 0.36%   |
| 7680x2160          | 1         | 0.18%   |
| 3840x1200          | 1         | 0.18%   |
| 3840x1100          | 1         | 0.18%   |
| 3072x1920          | 1         | 0.18%   |
| 2880x1920          | 1         | 0.18%   |
| 2496x1664          | 1         | 0.18%   |
| 1800x1200          | 1         | 0.18%   |
| 1400x1050          | 1         | 0.18%   |
| 1280x720 (HD)      | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 146       | 25.13%  |
| 13      | 82        | 14.11%  |
| 14      | 61        | 10.5%   |
| 24      | 31        | 5.34%   |
| 23      | 31        | 5.34%   |
| 27      | 29        | 4.99%   |
| 17      | 29        | 4.99%   |
| Unknown | 28        | 4.82%   |
| 21      | 23        | 3.96%   |
| 11      | 14        | 2.41%   |
| 31      | 13        | 2.24%   |
| 22      | 13        | 2.24%   |
| 20      | 13        | 2.24%   |
| 12      | 12        | 2.07%   |
| 18      | 8         | 1.38%   |
| 19      | 6         | 1.03%   |
| 34      | 5         | 0.86%   |
| 72      | 4         | 0.69%   |
| 16      | 4         | 0.69%   |
| 84      | 3         | 0.52%   |
| 32      | 3         | 0.52%   |
| 26      | 3         | 0.52%   |
| 25      | 3         | 0.52%   |
| 65      | 2         | 0.34%   |
| 52      | 2         | 0.34%   |
| 43      | 2         | 0.34%   |
| 10      | 2         | 0.34%   |
| 55      | 1         | 0.17%   |
| 49      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 47      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 36      | 1         | 0.17%   |
| 33      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 238       | 41.83%  |
| 501-600     | 86        | 15.11%  |
| 201-300     | 78        | 13.71%  |
| 401-500     | 60        | 10.54%  |
| 351-400     | 32        | 5.62%   |
| Unknown     | 28        | 4.92%   |
| 601-700     | 18        | 3.16%   |
| 701-800     | 10        | 1.76%   |
| 1001-1500   | 8         | 1.41%   |
| 1501-2000   | 7         | 1.23%   |
| 801-900     | 2         | 0.35%   |
| 901-1000    | 2         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 393       | 74.57%  |
| 16/10   | 81        | 15.37%  |
| Unknown | 24        | 4.55%   |
| 3/2     | 14        | 2.66%   |
| 5/4     | 6         | 1.14%   |
| 21/9    | 6         | 1.14%   |
| 4/3     | 1         | 0.19%   |
| 32/9    | 1         | 0.19%   |
| 3.40    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 144       | 25.13%  |
| 81-90          | 108       | 18.85%  |
| 201-250        | 71        | 12.39%  |
| 71-80          | 36        | 6.28%   |
| 301-350        | 30        | 5.24%   |
| Unknown        | 28        | 4.89%   |
| 151-200        | 25        | 4.36%   |
| 351-500        | 22        | 3.84%   |
| 251-300        | 20        | 3.49%   |
| 121-130        | 19        | 3.32%   |
| 51-60          | 15        | 2.62%   |
| More than 1000 | 13        | 2.27%   |
| 141-150        | 12        | 2.09%   |
| 61-70          | 10        | 1.75%   |
| 501-1000       | 7         | 1.22%   |
| 131-140        | 5         | 0.87%   |
| 111-120        | 4         | 0.7%    |
| 41-50          | 2         | 0.35%   |
| 91-100         | 2         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 169       | 29.86%  |
| 101-120       | 165       | 29.15%  |
| 51-100        | 140       | 24.73%  |
| 161-240       | 32        | 5.65%   |
| Unknown       | 28        | 4.95%   |
| More than 240 | 19        | 3.36%   |
| 1-50          | 13        | 2.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 439       | 84.91%  |
| 2     | 65        | 12.57%  |
| 3     | 10        | 1.93%   |
| 0     | 2         | 0.39%   |
| 4     | 1         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 245       | 32.19%  |
| Intel                             | 227       | 29.83%  |
| Qualcomm Atheros                  | 89        | 11.7%   |
| Broadcom                          | 79        | 10.38%  |
| Nvidia                            | 17        | 2.23%   |
| Marvell Technology Group          | 17        | 2.23%   |
| Broadcom Limited                  | 14        | 1.84%   |
| Ralink Technology                 | 9         | 1.18%   |
| Ralink                            | 9         | 1.18%   |
| TP-Link                           | 7         | 0.92%   |
| Xiaomi                            | 5         | 0.66%   |
| Samsung Electronics               | 5         | 0.66%   |
| Huawei Technologies               | 3         | 0.39%   |
| ASIX Electronics                  | 3         | 0.39%   |
| TRENDnet                          | 2         | 0.26%   |
| MediaTek                          | 2         | 0.26%   |
| Linksys                           | 2         | 0.26%   |
| Lenovo                            | 2         | 0.26%   |
| Google                            | 2         | 0.26%   |
| Apple                             | 2         | 0.26%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.13%   |
| vivo                              | 1         | 0.13%   |
| Sitecom Europe                    | 1         | 0.13%   |
| Sierra Wireless                   | 1         | 0.13%   |
| Realtek                           | 1         | 0.13%   |
| Qualcomm Atheros Communications   | 1         | 0.13%   |
| Qualcomm                          | 1         | 0.13%   |
| OPPO Electronics                  | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.13%   |
| Motorola PCS                      | 1         | 0.13%   |
| Microsoft                         | 1         | 0.13%   |
| LG Electronics                    | 1         | 0.13%   |
| JMicron Technology                | 1         | 0.13%   |
| Hewlett-Packard                   | 1         | 0.13%   |
| Ericsson Business Mobile Networks | 1         | 0.13%   |
| D-Link System                     | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| AVM                               | 1         | 0.13%   |
| Aquantia                          | 1         | 0.13%   |
| AboCom Systems                    | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 151       | 16.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 4.7%    |
| Intel Wi-Fi 6 AX200                                               | 21        | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 2.01%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 2.01%   |
| Intel Wireless 8260                                               | 16        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.34%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 12        | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.23%   |
| Nvidia MCP79 Ethernet                                             | 11        | 1.23%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 11        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.12%   |
| Intel Wireless 7265                                               | 10        | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 10        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.01%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 9         | 1.01%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 9         | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.89%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.89%   |
| Intel Wireless 7260                                               | 8         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 7         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 0.67%   |
| Intel Wireless 3165                                               | 6         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 0.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 6         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.56%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 5         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.45%   |
| Realtek 802.11ac NIC                                              | 4         | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 0.45%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.45%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 184       | 40.17%  |
| Qualcomm Atheros                | 74        | 16.16%  |
| Broadcom                        | 71        | 15.5%   |
| Realtek Semiconductor           | 70        | 15.28%  |
| Broadcom Limited                | 13        | 2.84%   |
| Ralink Technology               | 9         | 1.97%   |
| Ralink                          | 9         | 1.97%   |
| TP-Link                         | 7         | 1.53%   |
| Marvell Technology Group        | 4         | 0.87%   |
| TRENDnet                        | 2         | 0.44%   |
| MediaTek                        | 2         | 0.44%   |
| Linksys                         | 2         | 0.44%   |
| Sitecom Europe                  | 1         | 0.22%   |
| Sierra Wireless                 | 1         | 0.22%   |
| Realtek                         | 1         | 0.22%   |
| Qualcomm Atheros Communications | 1         | 0.22%   |
| Qualcomm                        | 1         | 0.22%   |
| Microsoft                       | 1         | 0.22%   |
| LG Electronics                  | 1         | 0.22%   |
| D-Link System                   | 1         | 0.22%   |
| D-Link                          | 1         | 0.22%   |
| AVM                             | 1         | 0.22%   |
| AboCom Systems                  | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 21        | 4.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 3.9%    |
| Intel Wi-Fi 6 AX201                                            | 18        | 3.9%    |
| Intel Wireless 8260                                            | 16        | 3.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 3.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 2.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.39%   |
| Intel Wireless 8265 / 8275                                     | 11        | 2.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 11        | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.17%   |
| Intel Wireless 7265                                            | 10        | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 2.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.95%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 9         | 1.95%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 9         | 1.95%   |
| Intel Wireless 7260                                            | 8         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 7         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 1.3%    |
| Intel Wireless 3165                                            | 6         | 1.3%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.08%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 5         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.87%   |
| Realtek 802.11ac NIC                                           | 4         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 0.65%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 3         | 0.65%   |
| Intel Wireless-AC 9260                                         | 3         | 0.65%   |
| Intel Wireless 3160                                            | 3         | 0.65%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 0.65%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 3         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.65%   |
| TP-Link TL-WN722N v2                                           | 2         | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.43%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter        | 2         | 0.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2         | 0.43%   |
| Ralink RT5372 Wireless Adapter                                 | 2         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 215       | 50.47%  |
| Intel                    | 101       | 23.71%  |
| Broadcom                 | 26        | 6.1%    |
| Qualcomm Atheros         | 25        | 5.87%   |
| Nvidia                   | 17        | 3.99%   |
| Marvell Technology Group | 13        | 3.05%   |
| Xiaomi                   | 5         | 1.17%   |
| Samsung Electronics      | 5         | 1.17%   |
| ASIX Electronics         | 3         | 0.7%    |
| Lenovo                   | 2         | 0.47%   |
| Huawei Technologies      | 2         | 0.47%   |
| Google                   | 2         | 0.47%   |
| Broadcom Limited         | 2         | 0.47%   |
| Apple                    | 2         | 0.47%   |
| vivo                     | 1         | 0.23%   |
| OPPO Electronics         | 1         | 0.23%   |
| Motorola PCS             | 1         | 0.23%   |
| JMicron Technology       | 1         | 0.23%   |
| Hewlett-Packard          | 1         | 0.23%   |
| Aquantia                 | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 151       | 35.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 42        | 9.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 4.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 12        | 2.8%    |
| Nvidia MCP79 Ethernet                                                          | 11        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                              | 10        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 1.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.86%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 8         | 1.86%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                           | 6         | 1.4%    |
| Intel Ethernet Controller I225-V                                               | 5         | 1.17%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.17%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 1.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.93%   |
| Nvidia MCP61 Ethernet                                                          | 4         | 0.93%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.7%    |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.47%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.47%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.47%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.47%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.47%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.47%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.47%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.47%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.47%   |
| Huawei JNY-LX1                                                                 | 2         | 0.47%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.47%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.47%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.23%   |
| vivo 1806                                                                      | 1         | 0.23%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.23%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 437       | 51.84%  |
| Ethernet | 402       | 47.69%  |
| Modem    | 3         | 0.36%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 340       | 66.8%   |
| Ethernet | 169       | 33.2%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 284       | 55.15%  |
| 1     | 211       | 40.97%  |
| 3     | 10        | 1.94%   |
| 0     | 9         | 1.75%   |
| 4     | 1         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 363       | 70.08%  |
| Yes  | 155       | 29.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 160       | 40.1%   |
| Apple                           | 58        | 14.54%  |
| Realtek Semiconductor           | 41        | 10.28%  |
| Qualcomm Atheros Communications | 25        | 6.27%   |
| Broadcom                        | 22        | 5.51%   |
| Cambridge Silicon Radio         | 19        | 4.76%   |
| Lite-On Technology              | 15        | 3.76%   |
| IMC Networks                    | 15        | 3.76%   |
| Foxconn / Hon Hai               | 11        | 2.76%   |
| Ralink                          | 6         | 1.5%    |
| Hewlett-Packard                 | 6         | 1.5%    |
| Marvell Semiconductor           | 5         | 1.25%   |
| Toshiba                         | 4         | 1%      |
| ASUSTek Computer                | 4         | 1%      |
| Realtek                         | 3         | 0.75%   |
| Dell                            | 3         | 0.75%   |
| Qcom                            | 1         | 0.25%   |
| Edimax Technology               | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 59        | 14.79%  |
| Intel AX201 Bluetooth                                                               | 36        | 9.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 26        | 6.52%   |
| Realtek Bluetooth Radio                                                             | 25        | 6.27%   |
| Apple Bluetooth Host Controller                                                     | 22        | 5.51%   |
| Intel AX200 Bluetooth                                                               | 20        | 5.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 4.01%   |
| Apple Bluetooth USB Host Controller                                                 | 15        | 3.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 11        | 2.76%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 10        | 2.51%   |
| Apple Bluetooth HCI                                                                 | 10        | 2.51%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 1.5%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.25%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.25%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1%      |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1%      |
| IMC Networks Bluetooth Radio                                                        | 4         | 1%      |
| IMC Networks Bluetooth Device                                                       | 4         | 1%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1%      |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 1%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.75%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.75%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 3         | 0.75%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.75%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.5%    |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 0.5%    |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.5%    |
| IMC Networks Wireless_Device                                                        | 2         | 0.5%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.5%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.5%    |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.25%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.25%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.25%   |
| Toshiba Askey for                                                                   | 1         | 0.25%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.25%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.25%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.25%   |
| Intel Bluetooth Device                                                              | 1         | 0.25%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.25%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.25%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.25%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.25%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.25%   |
| Edimax Bluetooth Adapter                                                            | 1         | 0.25%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 385       | 56.95%  |
| AMD                       | 140       | 20.71%  |
| Nvidia                    | 95        | 14.05%  |
| C-Media Electronics       | 14        | 2.07%   |
| Creative Labs             | 8         | 1.18%   |
| Logitech                  | 7         | 1.04%   |
| Texas Instruments         | 2         | 0.3%    |
| Generalplus Technology    | 2         | 0.3%    |
| Focusrite-Novation        | 2         | 0.3%    |
| ESS Technology            | 2         | 0.3%    |
| Corsair                   | 2         | 0.3%    |
| Unknown                   | 1         | 0.15%   |
| SteelSeries ApS           | 1         | 0.15%   |
| Sennheiser Communications | 1         | 0.15%   |
| Realtek Semiconductor     | 1         | 0.15%   |
| Razer USA                 | 1         | 0.15%   |
| No brand                  | 1         | 0.15%   |
| Native Instruments        | 1         | 0.15%   |
| Microsoft                 | 1         | 0.15%   |
| Micro Star International  | 1         | 0.15%   |
| GN Netcom                 | 1         | 0.15%   |
| Fry's Electronics         | 1         | 0.15%   |
| Edifier Technology        | 1         | 0.15%   |
| Dell                      | 1         | 0.15%   |
| Creative Technology       | 1         | 0.15%   |
| BEHRINGER International   | 1         | 0.15%   |
| ASUSTek Computer          | 1         | 0.15%   |
| Apple                     | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 51        | 6.29%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 46        | 5.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 5.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 4.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 3.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 24        | 2.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 2.59%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 2.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 1.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 1.97%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 1.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.48%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.48%   |
| Nvidia MCP79 High Definition Audio                                                                | 11        | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 10        | 1.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.11%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 8         | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 0.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.74%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 0.74%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 6         | 0.74%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.62%   |
| Nvidia TU104 HD Audio Controller                                                                  | 5         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 0.49%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.37%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.37%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.37%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.37%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.37%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 30.48%  |
| SK hynix            | 21        | 20%     |
| Micron Technology   | 13        | 12.38%  |
| Unknown             | 7         | 6.67%   |
| Kingston            | 7         | 6.67%   |
| Unknown (ABCD)      | 3         | 2.86%   |
| G.Skill             | 3         | 2.86%   |
| Crucial             | 3         | 2.86%   |
| Corsair             | 3         | 2.86%   |
| A-DATA Technology   | 3         | 2.86%   |
| Ramaxel Technology  | 2         | 1.9%    |
| Unknown (0x038A)    | 1         | 0.95%   |
| Transcend           | 1         | 0.95%   |
| SHARETRONIC         | 1         | 0.95%   |
| PNY                 | 1         | 0.95%   |
| Patriot             | 1         | 0.95%   |
| Hewlett-Packard     | 1         | 0.95%   |
| GSkill              | 1         | 0.95%   |
| Elpida              | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s  | 3         | 2.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 3         | 2.63%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s               | 3         | 2.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                | 3         | 2.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                | 2         | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s             | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s             | 2         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                | 2         | 1.75%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                            | 1         | 0.88%   |
| Unknown RAM Module 8192MB SODIMM DDR3                                | 1         | 0.88%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                         | 1         | 0.88%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                              | 1         | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                            | 1         | 0.88%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                       | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.88%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s             | 1         | 0.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.88%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                    | 1         | 0.88%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.88%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.88%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s                | 1         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 0.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 0.88%   |
| SK hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s             | 1         | 0.88%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s              | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 0.88%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s            | 1         | 0.88%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 0.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s               | 1         | 0.88%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s               | 1         | 0.88%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s               | 1         | 0.88%   |
| SK hynix RAM H9HCNNNFAMALTR-NEE 16384MB Row Of Chips LPDDR4 3733MT/s | 1         | 0.88%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s           | 1         | 0.88%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.88%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.88%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                       | 1         | 0.88%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                         | 1         | 0.88%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s                       | 1         | 0.88%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s                | 1         | 0.88%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                | 1         | 0.88%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                | 1         | 0.88%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s             | 1         | 0.88%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s                | 1         | 0.88%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s               | 1         | 0.88%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s         | 1         | 0.88%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s            | 1         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                | 1         | 0.88%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                | 1         | 0.88%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s                | 1         | 0.88%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                | 1         | 0.88%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s                  | 1         | 0.88%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                  | 1         | 0.88%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 44        | 47.31%  |
| DDR3    | 32        | 34.41%  |
| LPDDR4  | 10        | 10.75%  |
| LPDDR3  | 3         | 3.23%   |
| DDR2    | 2         | 2.15%   |
| Unknown | 2         | 2.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 68.82%  |
| DIMM         | 19        | 20.43%  |
| Row Of Chips | 9         | 9.68%   |
| Chip         | 1         | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 43        | 41.75%  |
| 4096  | 33        | 32.04%  |
| 16384 | 14        | 13.59%  |
| 2048  | 12        | 11.65%  |
| 32768 | 1         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 20        | 20%     |
| 3200    | 16        | 16%     |
| 2667    | 15        | 15%     |
| 2400    | 9         | 9%      |
| 1333    | 7         | 7%      |
| 4267    | 4         | 4%      |
| 2133    | 4         | 4%      |
| 1066    | 4         | 4%      |
| 8400    | 3         | 3%      |
| 3266    | 2         | 2%      |
| 1867    | 2         | 2%      |
| 1334    | 2         | 2%      |
| 4800    | 1         | 1%      |
| 4266    | 1         | 1%      |
| 3733    | 1         | 1%      |
| 3600    | 1         | 1%      |
| 2933    | 1         | 1%      |
| 2800    | 1         | 1%      |
| 2666    | 1         | 1%      |
| 2200    | 1         | 1%      |
| 1800    | 1         | 1%      |
| 800     | 1         | 1%      |
| 667     | 1         | 1%      |
| Unknown | 1         | 1%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 3         | 25%     |
| Samsung Electronics             | 2         | 16.67%  |
| Hewlett-Packard                 | 2         | 16.67%  |
| Brother Industries              | 2         | 16.67%  |
| Prolific Technology             | 1         | 8.33%   |
| Dymo-CoStar                     | 1         | 8.33%   |
| cab Produkttechnik GmbH & Co KG | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 2         | 16.67%  |
| Prolific PL2305 Parallel Port            | 1         | 8.33%   |
| HP OfficeJet 5200 series                 | 1         | 8.33%   |
| HP Ink Tank 110 series                   | 1         | 8.33%   |
| Dymo-CoStar LabelWriter 450              | 1         | 8.33%   |
| Canon PIXMA MG3600 Series                | 1         | 8.33%   |
| Canon PIXMA MG2500 Series                | 1         | 8.33%   |
| Canon G3000 series                       | 1         | 8.33%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 8.33%   |
| Brother MFC-L2750DW series               | 1         | 8.33%   |
| Brother MFC-J5335DW                      | 1         | 8.33%   |

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
| Chicony Electronics                    | 72        | 19.67%  |
| Apple                                  | 47        | 12.84%  |
| IMC Networks                           | 39        | 10.66%  |
| Realtek Semiconductor                  | 29        | 7.92%   |
| Quanta                                 | 23        | 6.28%   |
| Acer                                   | 23        | 6.28%   |
| Microdia                               | 22        | 6.01%   |
| Sunplus Innovation Technology          | 14        | 3.83%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 3.83%   |
| Suyin                                  | 12        | 3.28%   |
| Logitech                               | 11        | 3.01%   |
| Alcor Micro                            | 9         | 2.46%   |
| Syntek                                 | 8         | 2.19%   |
| Silicon Motion                         | 6         | 1.64%   |
| Microsoft                              | 5         | 1.37%   |
| Luxvisions Innotech Limited            | 4         | 1.09%   |
| Lenovo                                 | 4         | 1.09%   |
| Ricoh                                  | 2         | 0.55%   |
| Primax Electronics                     | 2         | 0.55%   |
| KYE Systems (Mouse Systems)            | 2         | 0.55%   |
| Foxconn / Hon Hai                      | 2         | 0.55%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| Y Media                                | 1         | 0.27%   |
| Unknown                                | 1         | 0.27%   |
| SunplusIT                              | 1         | 0.27%   |
| Sony                                   | 1         | 0.27%   |
| Samsung Electronics                    | 1         | 0.27%   |
| Razer USA                              | 1         | 0.27%   |
| Lite-On Technology                     | 1         | 0.27%   |
| kingcome                               | 1         | 0.27%   |
| Jieli Technology                       | 1         | 0.27%   |
| Importek                               | 1         | 0.27%   |
| Google                                 | 1         | 0.27%   |
| Generalplus Technology                 | 1         | 0.27%   |
| Cubeternet                             | 1         | 0.27%   |
| ANYKA                                  | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 21        | 5.66%   |
| Chicony Integrated Camera                                                  | 18        | 4.85%   |
| IMC Networks Integrated Camera                                             | 13        | 3.5%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 10        | 2.7%    |
| Chicony HD Webcam                                                          | 9         | 2.43%   |
| Syntek Integrated Camera                                                   | 8         | 2.16%   |
| Realtek Integrated_Webcam_HD                                               | 8         | 2.16%   |
| Apple FaceTime HD Camera                                                   | 8         | 2.16%   |
| Microdia Integrated_Webcam_HD                                              | 7         | 1.89%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 7         | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 1.62%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 1.35%   |
| Chicony USB 2.0 Camera                                                     | 5         | 1.35%   |
| Apple FaceTime HD Camera (Built-in)                                        | 5         | 1.35%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.08%   |
| Realtek USB2.0 HD UVC WebCam                                               | 4         | 1.08%   |
| Quanta VGA WebCam                                                          | 4         | 1.08%   |
| Quanta HD User Facing                                                      | 4         | 1.08%   |
| Apple FaceTime Camera                                                      | 4         | 1.08%   |
| Acer Lenovo EasyCamera                                                     | 4         | 1.08%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 0.81%   |
| Realtek Integrated Webcam                                                  | 3         | 0.81%   |
| Quanta HP Webcam                                                           | 3         | 0.81%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 3         | 0.81%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 0.81%   |
| Alcor Micro USB 2.0 PC Camera                                              | 3         | 0.81%   |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 0.81%   |
| Acer HD Webcam                                                             | 3         | 0.81%   |
| Acer HD Camera                                                             | 3         | 0.81%   |
| Acer EasyCamera                                                            | 3         | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 2         | 0.54%   |
| Sunplus ASUS USB2.0 Webcam                                                 | 2         | 0.54%   |
| Realtek USB Camera                                                         | 2         | 0.54%   |
| Realtek Built-In Video Camera                                              | 2         | 0.54%   |
| Realtek Acer 640 x 480 laptop camera                                       | 2         | 0.54%   |
| Microsoft Rear LifeCam                                                     | 2         | 0.54%   |
| Microsoft Front LifeCam                                                    | 2         | 0.54%   |
| Microdia USB 2.0 Camera                                                    | 2         | 0.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.54%   |
| Logitech Logi 4K Stream Edition                                            | 2         | 0.54%   |
| Logitech HD Webcam C615                                                    | 2         | 0.54%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.54%   |
| Lenovo Integrated Webcam                                                   | 2         | 0.54%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 2         | 0.54%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.54%   |
| IMC Networks EasyCamera                                                    | 2         | 0.54%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 2         | 0.54%   |
| Chicony VGA WebCam                                                         | 2         | 0.54%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.54%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 0.54%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.54%   |
| Chicony Sony Visual Communication Camera                                   | 2         | 0.54%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 0.54%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 0.54%   |
| Chicony HP TrueVision HD                                                   | 2         | 0.54%   |
| Chicony HP High Definition 1MP Webcam                                      | 2         | 0.54%   |
| Chicony HP HD Camera                                                       | 2         | 0.54%   |
| Chicony EasyCamera                                                         | 2         | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 37.93%  |
| Validity Sensors           | 15        | 25.86%  |
| Shenzhen Goodix Technology | 7         | 12.07%  |
| LighTuning Technology      | 7         | 12.07%  |
| Upek                       | 5         | 8.62%   |
| Elan Microelectronics      | 2         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 9         | 15.52%  |
| Shenzhen Goodix  FingerPrint Device                        | 6         | 10.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 8.62%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 6.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 6.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 6.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 5.17%   |
| Validity Sensors VFS491                                    | 3         | 5.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 5.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 5.17%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 3.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.72%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 1.72%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.72%   |
| Synaptics  WBDI                                            | 1         | 1.72%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.72%   |
| Shenzhen Goodix FingerPrint                                | 1         | 1.72%   |
| LighTuning Fingerprint Sensor                              | 1         | 1.72%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.72%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 44.44%  |
| Alcor Micro           | 5         | 27.78%  |
| Lenovo                | 2         | 11.11%  |
| O2 Micro              | 1         | 5.56%   |
| Gemalto (was Gemplus) | 1         | 5.56%   |
| Chicony Electronics   | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor         | 5         | 27.78%  |
| Alcor Micro AU9540 Smartcard Reader                    | 5         | 27.78%  |
| Lenovo Integrated Smart Card Reader                    | 2         | 11.11%  |
| Broadcom 58200                                         | 2         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 5.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 5.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1         | 5.56%   |
| Broadcom 5880                                          | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 388       | 74.9%   |
| 1     | 103       | 19.88%  |
| 2     | 25        | 4.83%   |
| 4     | 1         | 0.19%   |
| 3     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 37.18%  |
| Net/wireless             | 28        | 17.95%  |
| Multimedia controller    | 18        | 11.54%  |
| Chipcard                 | 17        | 10.9%   |
| Graphics card            | 11        | 7.05%   |
| Bluetooth                | 8         | 5.13%   |
| Camera                   | 4         | 2.56%   |
| Card reader              | 3         | 1.92%   |
| Unassigned class         | 2         | 1.28%   |
| Sound                    | 2         | 1.28%   |
| Net/ethernet             | 2         | 1.28%   |
| Storage/ide              | 1         | 0.64%   |
| Storage                  | 1         | 0.64%   |
| Communication controller | 1         | 0.64%   |


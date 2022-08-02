Linux in Bulgaria - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bulgaria/Desktop/README.md) and [notebooks](/Location/Bulgaria/Notebook/README.md).

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

Total: 1162

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P5KC                        | Desktop     | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [54c42c649d](https://linux-hardware.org/?probe=54c42c649d) | Jul 24, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [69bd504820](https://linux-hardware.org/?probe=69bd504820) | Jul 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | Notebook    | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | Desktop     | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [2c0dd875b3](https://linux-hardware.org/?probe=2c0dd875b3) | Jun 21, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [d660c2066c](https://linux-hardware.org/?probe=d660c2066c) | Jun 16, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | Desktop     | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [8adba273fb](https://linux-hardware.org/?probe=8adba273fb) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [bb07dfbc56](https://linux-hardware.org/?probe=bb07dfbc56) | May 21, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | Notebook    | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| Acer          | Predator G3-605             | Desktop     | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| Gigabyte      | H97N                        | Desktop     | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| MSI           | PRO B660-A DDR4             | Desktop     | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | Notebook    | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Dell          | Precision M6800             | Notebook    | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | Notebook    | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | Notebook    | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | Notebook    | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| ASUSTek       | N551VW                      | Notebook    | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88a943ec80](https://linux-hardware.org/?probe=88a943ec80) | Feb 16, 2022 |
| Dell          | Latitude E6330              | Notebook    | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | Notebook    | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| Dell          | Inspiron 5482               | Convertible | [17584ae0e4](https://linux-hardware.org/?probe=17584ae0e4) | Feb 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | Desktop     | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | Desktop     | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | Notebook    | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| ASUSTek       | P5E                         | Desktop     | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | Notebook    | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | Notebook    | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | Notebook    | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | Notebook    | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | Notebook    | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | Notebook    | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3ab004eed4](https://linux-hardware.org/?probe=3ab004eed4) | Oct 17, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| Acer          | Aspire A515-52G             | Notebook    | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| Acer          | Extensa 5630                | Notebook    | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | Notebook    | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Lenovo        | ThinkStation D20 4158E93    | Desktop     | [fde770f309](https://linux-hardware.org/?probe=fde770f309) | Sep 11, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [a95e304baf](https://linux-hardware.org/?probe=a95e304baf) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [a37b749b27](https://linux-hardware.org/?probe=a37b749b27) | Sep 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [92e21fb915](https://linux-hardware.org/?probe=92e21fb915) | Sep 06, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | Notebook    | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [7c76ac10d8](https://linux-hardware.org/?probe=7c76ac10d8) | Sep 04, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d831e8693d](https://linux-hardware.org/?probe=d831e8693d) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [7d634f76ad](https://linux-hardware.org/?probe=7d634f76ad) | Aug 31, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [8f10e30326](https://linux-hardware.org/?probe=8f10e30326) | Aug 28, 2021 |
| HP            | 18E4                        | Desktop     | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [0c191944fc](https://linux-hardware.org/?probe=0c191944fc) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [a08f9bd38d](https://linux-hardware.org/?probe=a08f9bd38d) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | Notebook    | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| HP            | ProBook 6450b               | Notebook    | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [5d62f330ba](https://linux-hardware.org/?probe=5d62f330ba) | Jul 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [5ce964530d](https://linux-hardware.org/?probe=5ce964530d) | Jul 13, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | Notebook    | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [13af782a58](https://linux-hardware.org/?probe=13af782a58) | Jun 29, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| HP            | 1493                        | Desktop     | [cd54c7db25](https://linux-hardware.org/?probe=cd54c7db25) | Jun 26, 2021 |
| HP            | 1493                        | Desktop     | [5b7dd91534](https://linux-hardware.org/?probe=5b7dd91534) | Jun 26, 2021 |
| Dell          | Latitude 5410               | Notebook    | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | Notebook    | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | Notebook    | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e7e3e4138d](https://linux-hardware.org/?probe=e7e3e4138d) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [c4f55611e4](https://linux-hardware.org/?probe=c4f55611e4) | Jun 20, 2021 |
| Acer          | Extensa 5630                | Notebook    | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [f200ec0bda](https://linux-hardware.org/?probe=f200ec0bda) | Jun 08, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [9a2b696908](https://linux-hardware.org/?probe=9a2b696908) | Jun 05, 2021 |
| HP            | Pavilion dv5                | Notebook    | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | Notebook    | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [6bc1b9dcc9](https://linux-hardware.org/?probe=6bc1b9dcc9) | May 31, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [c050f79e2b](https://linux-hardware.org/?probe=c050f79e2b) | May 29, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [7f510d13fb](https://linux-hardware.org/?probe=7f510d13fb) | May 28, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | Notebook    | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [493f6f8057](https://linux-hardware.org/?probe=493f6f8057) | May 18, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | Notebook    | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [4d5f23e6ba](https://linux-hardware.org/?probe=4d5f23e6ba) | May 17, 2021 |
| Dell          | Studio 1535                 | Notebook    | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [14ea7483bc](https://linux-hardware.org/?probe=14ea7483bc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [22657f3929](https://linux-hardware.org/?probe=22657f3929) | May 15, 2021 |
| HP            | 3396                        | Desktop     | [ed3fa57f54](https://linux-hardware.org/?probe=ed3fa57f54) | May 15, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [3ad2c89a0a](https://linux-hardware.org/?probe=3ad2c89a0a) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | Notebook    | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| ASRock        | X79 Extreme4                | Desktop     | [d3383d57ef](https://linux-hardware.org/?probe=d3383d57ef) | May 01, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| ASUSTek       | Amberine M                  | Desktop     | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| HP            | Notebook                    | Notebook    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| Lenovo        | ThinkPad X230 232425U       | Notebook    | [69e5ab7b60](https://linux-hardware.org/?probe=69e5ab7b60) | Apr 24, 2021 |
| ASRock        | B360M Pro4                  | Desktop     | [b1f9a4880e](https://linux-hardware.org/?probe=b1f9a4880e) | Apr 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | Notebook    | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [e6cc5fbf7f](https://linux-hardware.org/?probe=e6cc5fbf7f) | Apr 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [a7b1f80885](https://linux-hardware.org/?probe=a7b1f80885) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [8c83051b44](https://linux-hardware.org/?probe=8c83051b44) | Apr 12, 2021 |
| ASRock        | Z68 Extreme7 Gen3           | Desktop     | [d8e2ac9e9b](https://linux-hardware.org/?probe=d8e2ac9e9b) | Apr 11, 2021 |
| Dell          | Vostro 3558                 | Notebook    | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [658ec2843e](https://linux-hardware.org/?probe=658ec2843e) | Apr 03, 2021 |
| HP            | 1850                        | Desktop     | [517c6137a3](https://linux-hardware.org/?probe=517c6137a3) | Apr 01, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [333c645cc4](https://linux-hardware.org/?probe=333c645cc4) | Apr 01, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | Notebook    | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | Notebook    | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [bd779f8e4e](https://linux-hardware.org/?probe=bd779f8e4e) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [072483c895](https://linux-hardware.org/?probe=072483c895) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [11e59c84c6](https://linux-hardware.org/?probe=11e59c84c6) | Mar 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | Notebook    | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Seco          | C40 C                       | Desktop     | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [e5f799a9f1](https://linux-hardware.org/?probe=e5f799a9f1) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d2d43a5a92](https://linux-hardware.org/?probe=d2d43a5a92) | Mar 17, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ef2bfba994](https://linux-hardware.org/?probe=ef2bfba994) | Mar 17, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [39fb7fbfdd](https://linux-hardware.org/?probe=39fb7fbfdd) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [30047ff89f](https://linux-hardware.org/?probe=30047ff89f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [3fc42af6ee](https://linux-hardware.org/?probe=3fc42af6ee) | Mar 13, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [3403829400](https://linux-hardware.org/?probe=3403829400) | Mar 13, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [e2bd9d6df8](https://linux-hardware.org/?probe=e2bd9d6df8) | Mar 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5ff3194762](https://linux-hardware.org/?probe=5ff3194762) | Mar 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a76ade188b](https://linux-hardware.org/?probe=a76ade188b) | Mar 07, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [b3a1ae5051](https://linux-hardware.org/?probe=b3a1ae5051) | Mar 06, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [f14a8d2de0](https://linux-hardware.org/?probe=f14a8d2de0) | Mar 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ee7f196bf2](https://linux-hardware.org/?probe=ee7f196bf2) | Feb 28, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | Notebook    | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| Intel         | X99 V102                    | Desktop     | [e4884fdd22](https://linux-hardware.org/?probe=e4884fdd22) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| HP            | 3396                        | Desktop     | [dd8601c672](https://linux-hardware.org/?probe=dd8601c672) | Feb 24, 2021 |
| HP            | 3396                        | Desktop     | [5c5fde40cd](https://linux-hardware.org/?probe=5c5fde40cd) | Feb 24, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [53d26490a1](https://linux-hardware.org/?probe=53d26490a1) | Feb 23, 2021 |
| Dell          | Inspiron 3584               | Notebook    | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| HP            | 1494                        | Desktop     | [c369d28059](https://linux-hardware.org/?probe=c369d28059) | Feb 23, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5ad971da58](https://linux-hardware.org/?probe=5ad971da58) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [698bd7ab9c](https://linux-hardware.org/?probe=698bd7ab9c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [e5ae830bbf](https://linux-hardware.org/?probe=e5ae830bbf) | Feb 21, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b9b1df7b2d](https://linux-hardware.org/?probe=b9b1df7b2d) | Feb 21, 2021 |
| ASUSTek       | G752VL                      | Notebook    | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [71a10bba93](https://linux-hardware.org/?probe=71a10bba93) | Feb 16, 2021 |
| Toshiba       | TECRA A11                   | Notebook    | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| MSI           | MS-7250                     | Desktop     | [e1f266f412](https://linux-hardware.org/?probe=e1f266f412) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| MSI           | H61M-P31                    | Desktop     | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| ASUSTek       | A8N-E                       | Desktop     | [a35eff4bb9](https://linux-hardware.org/?probe=a35eff4bb9) | Feb 14, 2021 |
| iEi           | B202 V1.0                   | Desktop     | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [b6b357f26c](https://linux-hardware.org/?probe=b6b357f26c) | Feb 14, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| ASRock        | 890GX Extreme3              | Desktop     | [1168daa7de](https://linux-hardware.org/?probe=1168daa7de) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [dc1822ee72](https://linux-hardware.org/?probe=dc1822ee72) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [8fedc4a9c1](https://linux-hardware.org/?probe=8fedc4a9c1) | Feb 12, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [2d6363ed19](https://linux-hardware.org/?probe=2d6363ed19) | Feb 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | Notebook    | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | Notebook    | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| ASRock        | FM2A85X Extreme4            | Desktop     | [2f1725cb23](https://linux-hardware.org/?probe=2f1725cb23) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5e824ae0f4](https://linux-hardware.org/?probe=5e824ae0f4) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| ASRock        | H87M Pro4                   | Desktop     | [88e1834599](https://linux-hardware.org/?probe=88e1834599) | Jan 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [194dbb8e46](https://linux-hardware.org/?probe=194dbb8e46) | Jan 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [bdee5c1907](https://linux-hardware.org/?probe=bdee5c1907) | Jan 23, 2021 |
| ASRock        | H110M-HDV                   | Desktop     | [6eecfdfd4b](https://linux-hardware.org/?probe=6eecfdfd4b) | Jan 21, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [e10b7bc8cf](https://linux-hardware.org/?probe=e10b7bc8cf) | Jan 21, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| MiTAC         | E220 6A7                    | Desktop     | [0d75e5ba34](https://linux-hardware.org/?probe=0d75e5ba34) | Jan 14, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [20416ee115](https://linux-hardware.org/?probe=20416ee115) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | Notebook    | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | Notebook    | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | Notebook    | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | Notebook    | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [1c948eea28](https://linux-hardware.org/?probe=1c948eea28) | Jan 05, 2021 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [13e7f80b8f](https://linux-hardware.org/?probe=13e7f80b8f) | Jan 03, 2021 |
| Packard Be... | EasyNote TK87               | Notebook    | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [5232dd577c](https://linux-hardware.org/?probe=5232dd577c) | Jan 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | Notebook    | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [50edfe4e5e](https://linux-hardware.org/?probe=50edfe4e5e) | Jan 01, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [05fcb61de6](https://linux-hardware.org/?probe=05fcb61de6) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b2e6caf193](https://linux-hardware.org/?probe=b2e6caf193) | Dec 25, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [06f63c2119](https://linux-hardware.org/?probe=06f63c2119) | Dec 24, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [fed52f343a](https://linux-hardware.org/?probe=fed52f343a) | Dec 24, 2020 |
| MiTAC         | E220 6A7                    | Desktop     | [e051bc126d](https://linux-hardware.org/?probe=e051bc126d) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | Notebook    | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Dell          | 0K240Y A02                  | Desktop     | [d522c503da](https://linux-hardware.org/?probe=d522c503da) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [ad3ac7bcee](https://linux-hardware.org/?probe=ad3ac7bcee) | Dec 19, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Unknown       | GSUO H61                    | Desktop     | [3c4c6c8bd0](https://linux-hardware.org/?probe=3c4c6c8bd0) | Dec 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [d0388f0066](https://linux-hardware.org/?probe=d0388f0066) | Dec 12, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [2c39a254ee](https://linux-hardware.org/?probe=2c39a254ee) | Dec 11, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6502e1050d](https://linux-hardware.org/?probe=6502e1050d) | Dec 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [b7e98a5926](https://linux-hardware.org/?probe=b7e98a5926) | Dec 04, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [d12dc95e76](https://linux-hardware.org/?probe=d12dc95e76) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [02c7320eaf](https://linux-hardware.org/?probe=02c7320eaf) | Dec 03, 2020 |
| ASRock        | G41M-S3                     | Desktop     | [1f91a14ff2](https://linux-hardware.org/?probe=1f91a14ff2) | Dec 03, 2020 |
| Dell          | Latitude 5591               | Notebook    | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | Notebook    | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | Notebook    | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | Notebook    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | Notebook    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [7b8b964ce4](https://linux-hardware.org/?probe=7b8b964ce4) | Nov 29, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Dell          | 0K240Y A02                  | Desktop     | [6f8d2322b6](https://linux-hardware.org/?probe=6f8d2322b6) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | Notebook    | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| HP            | 2B56                        | All in one  | [3db64c4252](https://linux-hardware.org/?probe=3db64c4252) | Nov 17, 2020 |
| HP            | 2B56                        | All in one  | [1eb0afe0ed](https://linux-hardware.org/?probe=1eb0afe0ed) | Nov 17, 2020 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a2ac4f643a](https://linux-hardware.org/?probe=a2ac4f643a) | Nov 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | Notebook    | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [7698cbedd0](https://linux-hardware.org/?probe=7698cbedd0) | Nov 12, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1df930d7e](https://linux-hardware.org/?probe=c1df930d7e) | Nov 10, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | Notebook    | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| HP            | ProBook 6470b               | Notebook    | [18f5fab938](https://linux-hardware.org/?probe=18f5fab938) | Oct 31, 2020 |
| ASUSTek       | V222GA                      | All in one  | [6792dcd0de](https://linux-hardware.org/?probe=6792dcd0de) | Oct 30, 2020 |
| iEi           | B202 V1.0                   | Desktop     | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| Dell          | Vostro 3580                 | Notebook    | [a0e40c6f16](https://linux-hardware.org/?probe=a0e40c6f16) | Oct 29, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [a4497b52bb](https://linux-hardware.org/?probe=a4497b52bb) | Oct 28, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [4643cfe86d](https://linux-hardware.org/?probe=4643cfe86d) | Oct 27, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [da5ad20c60](https://linux-hardware.org/?probe=da5ad20c60) | Oct 27, 2020 |
| Dell          | Latitude 5480               | Notebook    | [4191db79b7](https://linux-hardware.org/?probe=4191db79b7) | Oct 25, 2020 |
| Toshiba       | Satellite S70-B             | Notebook    | [a6521e505a](https://linux-hardware.org/?probe=a6521e505a) | Oct 25, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [89f32e3856](https://linux-hardware.org/?probe=89f32e3856) | Oct 23, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [76852e9990](https://linux-hardware.org/?probe=76852e9990) | Oct 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [74b57e7887](https://linux-hardware.org/?probe=74b57e7887) | Oct 21, 2020 |
| Packard Be... | IMEDIA S2185                | Desktop     | [5fd02031d2](https://linux-hardware.org/?probe=5fd02031d2) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a1a02fe851](https://linux-hardware.org/?probe=a1a02fe851) | Oct 18, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [dd68c7b3f6](https://linux-hardware.org/?probe=dd68c7b3f6) | Oct 18, 2020 |
| Dell          | 0XHGV1 A00                  | Desktop     | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [fdc8cb1b11](https://linux-hardware.org/?probe=fdc8cb1b11) | Oct 16, 2020 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [f5c8360ae3](https://linux-hardware.org/?probe=f5c8360ae3) | Oct 15, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f72e0309a](https://linux-hardware.org/?probe=3f72e0309a) | Oct 15, 2020 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [bfe71baced](https://linux-hardware.org/?probe=bfe71baced) | Oct 14, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [ba66ad5205](https://linux-hardware.org/?probe=ba66ad5205) | Oct 12, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [5e14548b50](https://linux-hardware.org/?probe=5e14548b50) | Oct 12, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [bbae413f9c](https://linux-hardware.org/?probe=bbae413f9c) | Oct 10, 2020 |
| ASUSTek       | K53U                        | Notebook    | [59444922e7](https://linux-hardware.org/?probe=59444922e7) | Oct 10, 2020 |
| ASUSTek       | K53U                        | Notebook    | [5c5b3815f7](https://linux-hardware.org/?probe=5c5b3815f7) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [25fb29514f](https://linux-hardware.org/?probe=25fb29514f) | Oct 10, 2020 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [61b3d8f426](https://linux-hardware.org/?probe=61b3d8f426) | Oct 09, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [b178beac46](https://linux-hardware.org/?probe=b178beac46) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [86c3c25832](https://linux-hardware.org/?probe=86c3c25832) | Oct 05, 2020 |
| ASUSTek       | P10S-V Series               | Desktop     | [ab381f976a](https://linux-hardware.org/?probe=ab381f976a) | Oct 04, 2020 |
| HP            | 250 G3                      | Notebook    | [ab75ccc4f8](https://linux-hardware.org/?probe=ab75ccc4f8) | Oct 02, 2020 |
| Dell          | Inspiron 3583               | Notebook    | [419cd76be1](https://linux-hardware.org/?probe=419cd76be1) | Oct 01, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [18199ffdaf](https://linux-hardware.org/?probe=18199ffdaf) | Sep 30, 2020 |
| Gigabyte      | P35-S3G                     | Desktop     | [c55cb88668](https://linux-hardware.org/?probe=c55cb88668) | Sep 30, 2020 |
| Dell          | G7 7588                     | Notebook    | [0d38edaf0c](https://linux-hardware.org/?probe=0d38edaf0c) | Sep 28, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [33020554c0](https://linux-hardware.org/?probe=33020554c0) | Sep 27, 2020 |
| Acer          | EG43M                       | Desktop     | [f70bf9f37f](https://linux-hardware.org/?probe=f70bf9f37f) | Sep 26, 2020 |
| Acer          | EG43M                       | Desktop     | [93fe9368c0](https://linux-hardware.org/?probe=93fe9368c0) | Sep 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [e330dd752b](https://linux-hardware.org/?probe=e330dd752b) | Sep 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [18afb6b15d](https://linux-hardware.org/?probe=18afb6b15d) | Sep 22, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [c078093e0f](https://linux-hardware.org/?probe=c078093e0f) | Sep 22, 2020 |
| HP            | Compaq tc4400 (RH489ES#A... | Notebook    | [c0305edfae](https://linux-hardware.org/?probe=c0305edfae) | Sep 20, 2020 |
| ASUSTek       | K50C                        | Notebook    | [d4e11f2289](https://linux-hardware.org/?probe=d4e11f2289) | Sep 18, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [db3c1d0348](https://linux-hardware.org/?probe=db3c1d0348) | Sep 13, 2020 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [7ab72b120c](https://linux-hardware.org/?probe=7ab72b120c) | Sep 12, 2020 |
| Acer          | Extensa 5630                | Notebook    | [9040e8e334](https://linux-hardware.org/?probe=9040e8e334) | Sep 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [a66f1b519a](https://linux-hardware.org/?probe=a66f1b519a) | Sep 10, 2020 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [fd2b790572](https://linux-hardware.org/?probe=fd2b790572) | Sep 09, 2020 |
| Shuttle       | FH81                        | Desktop     | [f7d3c868f1](https://linux-hardware.org/?probe=f7d3c868f1) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| HP            | ENVY x360 m Convertible     | Convertible | [03ff5b116c](https://linux-hardware.org/?probe=03ff5b116c) | Sep 03, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [bc5ee009b9](https://linux-hardware.org/?probe=bc5ee009b9) | Aug 29, 2020 |
| Lenovo        | ThinkPad X250 20CLS2YH00    | Notebook    | [cee4231640](https://linux-hardware.org/?probe=cee4231640) | Aug 29, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [9820c3c8bd](https://linux-hardware.org/?probe=9820c3c8bd) | Aug 28, 2020 |
| HP            | 0AA4h                       | Desktop     | [e1d187b146](https://linux-hardware.org/?probe=e1d187b146) | Aug 24, 2020 |
| Dell          | Precision M4800             | Notebook    | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| Dell          | Precision M4800             | Notebook    | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| HP            | 250 G3                      | Notebook    | [ff5c3ce273](https://linux-hardware.org/?probe=ff5c3ce273) | Aug 19, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [bf7ae9d5bf](https://linux-hardware.org/?probe=bf7ae9d5bf) | Aug 19, 2020 |
| HP            | 250 G3                      | Notebook    | [01f2866b5c](https://linux-hardware.org/?probe=01f2866b5c) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [1619b6bb6c](https://linux-hardware.org/?probe=1619b6bb6c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b636cd4fc2](https://linux-hardware.org/?probe=b636cd4fc2) | Aug 10, 2020 |
| Lenovo        | ThinkCentre M90p 5864BQ9    | Desktop     | [2f13897020](https://linux-hardware.org/?probe=2f13897020) | Aug 06, 2020 |
| HP            | 1632                        | Desktop     | [051549bbcd](https://linux-hardware.org/?probe=051549bbcd) | Aug 03, 2020 |
| HP            | 1496                        | Desktop     | [814a9396ee](https://linux-hardware.org/?probe=814a9396ee) | Aug 01, 2020 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [d6af935ba5](https://linux-hardware.org/?probe=d6af935ba5) | Jul 30, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [ec4e8d2f6b](https://linux-hardware.org/?probe=ec4e8d2f6b) | Jul 30, 2020 |
| ASRock        | ConRoe945PL-GLAN            | Desktop     | [006d3a68b4](https://linux-hardware.org/?probe=006d3a68b4) | Jul 30, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [18c07b157f](https://linux-hardware.org/?probe=18c07b157f) | Jul 29, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [8051286600](https://linux-hardware.org/?probe=8051286600) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [974c9ebd9c](https://linux-hardware.org/?probe=974c9ebd9c) | Jul 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [511636781f](https://linux-hardware.org/?probe=511636781f) | Jul 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [06120056c3](https://linux-hardware.org/?probe=06120056c3) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [2afa9387d5](https://linux-hardware.org/?probe=2afa9387d5) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [8ced06cd1f](https://linux-hardware.org/?probe=8ced06cd1f) | Jul 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8d593715c](https://linux-hardware.org/?probe=e8d593715c) | Jul 25, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [7b8022aa05](https://linux-hardware.org/?probe=7b8022aa05) | Jul 23, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [42fc06b0e4](https://linux-hardware.org/?probe=42fc06b0e4) | Jul 23, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [1de3848a94](https://linux-hardware.org/?probe=1de3848a94) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | Notebook    | [223cceb869](https://linux-hardware.org/?probe=223cceb869) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | Notebook    | [699033745c](https://linux-hardware.org/?probe=699033745c) | Jul 19, 2020 |
| Acer          | E5-575G                     | Notebook    | [9fb1e1bee4](https://linux-hardware.org/?probe=9fb1e1bee4) | Jul 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee5e7f9151](https://linux-hardware.org/?probe=ee5e7f9151) | Jul 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [968247c419](https://linux-hardware.org/?probe=968247c419) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c1fb882fc5](https://linux-hardware.org/?probe=c1fb882fc5) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ac0d845ddb](https://linux-hardware.org/?probe=ac0d845ddb) | Jul 13, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [54f20878cf](https://linux-hardware.org/?probe=54f20878cf) | Jul 12, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7387ae682a](https://linux-hardware.org/?probe=7387ae682a) | Jul 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [46702d58d5](https://linux-hardware.org/?probe=46702d58d5) | Jul 04, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | Notebook    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| Fujitsu Si... | AMILO L Series              | Notebook    | [33762202ef](https://linux-hardware.org/?probe=33762202ef) | Jul 01, 2020 |
| MSI           | B150 GAMING M3              | Desktop     | [4e837b8686](https://linux-hardware.org/?probe=4e837b8686) | Jul 01, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [9b54e3f16c](https://linux-hardware.org/?probe=9b54e3f16c) | Jun 30, 2020 |
| ASUSTek       | P8H61-I LX R2.0/RM/SI       | Desktop     | [a5f5e5572b](https://linux-hardware.org/?probe=a5f5e5572b) | Jun 30, 2020 |
| Dell          | Latitude E6410              | Notebook    | [79c1af2581](https://linux-hardware.org/?probe=79c1af2581) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [078efbe676](https://linux-hardware.org/?probe=078efbe676) | Jun 29, 2020 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [a79843ff43](https://linux-hardware.org/?probe=a79843ff43) | Jun 27, 2020 |
| Acer          | Swift SF314-57G             | Notebook    | [9bd6123d76](https://linux-hardware.org/?probe=9bd6123d76) | Jun 25, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5d93931a70](https://linux-hardware.org/?probe=5d93931a70) | Jun 21, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d318a0db0](https://linux-hardware.org/?probe=6d318a0db0) | Jun 21, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f2f35bedba](https://linux-hardware.org/?probe=f2f35bedba) | Jun 20, 2020 |
| Toshiba       | Satellite C55-A-1HL         | Notebook    | [c6d6bb3ba1](https://linux-hardware.org/?probe=c6d6bb3ba1) | Jun 18, 2020 |
| Toshiba       | Satellite C55-A-1HL         | Notebook    | [d16857f500](https://linux-hardware.org/?probe=d16857f500) | Jun 17, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [22ca9e31e5](https://linux-hardware.org/?probe=22ca9e31e5) | Jun 15, 2020 |
| ASRock        | H110M-HDV                   | Desktop     | [9a04c60269](https://linux-hardware.org/?probe=9a04c60269) | Jun 15, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [1b58de62cc](https://linux-hardware.org/?probe=1b58de62cc) | Jun 14, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [5a279c96a5](https://linux-hardware.org/?probe=5a279c96a5) | Jun 13, 2020 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [7a3bd1d810](https://linux-hardware.org/?probe=7a3bd1d810) | Jun 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1e9b7bd7d0](https://linux-hardware.org/?probe=1e9b7bd7d0) | Jun 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65f523b6f2](https://linux-hardware.org/?probe=65f523b6f2) | Jun 06, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [c8ddcb0ec8](https://linux-hardware.org/?probe=c8ddcb0ec8) | Jun 06, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d23bc12452](https://linux-hardware.org/?probe=d23bc12452) | Jun 04, 2020 |
| ASRock        | 970M Pro3                   | Desktop     | [f40c51e426](https://linux-hardware.org/?probe=f40c51e426) | Jun 03, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [efa59eef1c](https://linux-hardware.org/?probe=efa59eef1c) | Jun 01, 2020 |
| HP            | 250 G3                      | Notebook    | [99be1919b2](https://linux-hardware.org/?probe=99be1919b2) | Jun 01, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [8eb9fa72de](https://linux-hardware.org/?probe=8eb9fa72de) | May 31, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [6860a03dd0](https://linux-hardware.org/?probe=6860a03dd0) | May 31, 2020 |
| HP            | 250 G3                      | Notebook    | [a4e1d1f904](https://linux-hardware.org/?probe=a4e1d1f904) | May 29, 2020 |
| Lenovo        | ThinkPad T495 20NJ0010BM    | Notebook    | [6974ca5761](https://linux-hardware.org/?probe=6974ca5761) | May 29, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [edcc0b8c05](https://linux-hardware.org/?probe=edcc0b8c05) | May 29, 2020 |
| ASUSTek       | X540LJ                      | Notebook    | [67a3981fe5](https://linux-hardware.org/?probe=67a3981fe5) | May 27, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [9c341d7259](https://linux-hardware.org/?probe=9c341d7259) | May 25, 2020 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5bd26cbc33](https://linux-hardware.org/?probe=5bd26cbc33) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| ASUSTek       | X705UNR                     | Notebook    | [015957a390](https://linux-hardware.org/?probe=015957a390) | May 22, 2020 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [34d65fc5b5](https://linux-hardware.org/?probe=34d65fc5b5) | May 22, 2020 |
| HP            | ProBook 6460b               | Notebook    | [babf988605](https://linux-hardware.org/?probe=babf988605) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| HP            | 1496                        | Desktop     | [64b345823f](https://linux-hardware.org/?probe=64b345823f) | May 18, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [5d67f4aace](https://linux-hardware.org/?probe=5d67f4aace) | May 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33722345b4](https://linux-hardware.org/?probe=33722345b4) | May 13, 2020 |
| HP            | 255 G2                      | Notebook    | [ad9ef87735](https://linux-hardware.org/?probe=ad9ef87735) | May 13, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [88fc8f3bc8](https://linux-hardware.org/?probe=88fc8f3bc8) | May 13, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d4a5246eaa](https://linux-hardware.org/?probe=d4a5246eaa) | May 12, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [715f4fa65b](https://linux-hardware.org/?probe=715f4fa65b) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [96cd96c818](https://linux-hardware.org/?probe=96cd96c818) | May 12, 2020 |
| HP            | ProBook 4710s               | Notebook    | [b2680d0881](https://linux-hardware.org/?probe=b2680d0881) | May 11, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [6da190e95d](https://linux-hardware.org/?probe=6da190e95d) | May 10, 2020 |
| HP            | 255 G2                      | Notebook    | [ee5dcad518](https://linux-hardware.org/?probe=ee5dcad518) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Dell          | Latitude 7490               | Notebook    | [94b949eb90](https://linux-hardware.org/?probe=94b949eb90) | May 08, 2020 |
| Acer          | E5-575G                     | Notebook    | [4de3c815fd](https://linux-hardware.org/?probe=4de3c815fd) | May 08, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [3b379abf6a](https://linux-hardware.org/?probe=3b379abf6a) | May 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| HP            | 255 G2                      | Notebook    | [162f37494e](https://linux-hardware.org/?probe=162f37494e) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ea793cbae5](https://linux-hardware.org/?probe=ea793cbae5) | May 06, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b26d2727c](https://linux-hardware.org/?probe=8b26d2727c) | May 06, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [cbcdbbc816](https://linux-hardware.org/?probe=cbcdbbc816) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [72e18e38ce](https://linux-hardware.org/?probe=72e18e38ce) | May 04, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [35d925dbae](https://linux-hardware.org/?probe=35d925dbae) | May 04, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [02c7c61130](https://linux-hardware.org/?probe=02c7c61130) | May 03, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [d987f6c242](https://linux-hardware.org/?probe=d987f6c242) | May 03, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [029da6ffcc](https://linux-hardware.org/?probe=029da6ffcc) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | Notebook    | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [c3b3575e58](https://linux-hardware.org/?probe=c3b3575e58) | May 02, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [77202c9853](https://linux-hardware.org/?probe=77202c9853) | May 02, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [f74dab71c3](https://linux-hardware.org/?probe=f74dab71c3) | May 01, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [7ac5247653](https://linux-hardware.org/?probe=7ac5247653) | May 01, 2020 |
| MSI           | MS-7368                     | Desktop     | [090e6cd15c](https://linux-hardware.org/?probe=090e6cd15c) | May 01, 2020 |
| MSI           | MS-7368                     | Desktop     | [308c2e01f6](https://linux-hardware.org/?probe=308c2e01f6) | Apr 30, 2020 |
| ASUSTek       | M2N68-CM                    | Desktop     | [6f787e35a1](https://linux-hardware.org/?probe=6f787e35a1) | Apr 27, 2020 |
| Acer          | Aspire 3830G                | Notebook    | [1af95987d0](https://linux-hardware.org/?probe=1af95987d0) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7dceeca2dd](https://linux-hardware.org/?probe=7dceeca2dd) | Apr 24, 2020 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [2dde18f51f](https://linux-hardware.org/?probe=2dde18f51f) | Apr 24, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [2d93805421](https://linux-hardware.org/?probe=2d93805421) | Apr 23, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [155a39180a](https://linux-hardware.org/?probe=155a39180a) | Apr 23, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [28fa6e8b6e](https://linux-hardware.org/?probe=28fa6e8b6e) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [73f401be06](https://linux-hardware.org/?probe=73f401be06) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [562403e85f](https://linux-hardware.org/?probe=562403e85f) | Apr 21, 2020 |
| Gigabyte      | P85-D3                      | Desktop     | [5972095107](https://linux-hardware.org/?probe=5972095107) | Apr 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee479d0e5d](https://linux-hardware.org/?probe=ee479d0e5d) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [a78b041d0c](https://linux-hardware.org/?probe=a78b041d0c) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [fbfdc3b5e3](https://linux-hardware.org/?probe=fbfdc3b5e3) | Apr 20, 2020 |
| Sony          | VPCEB4L1E                   | Notebook    | [f1a3807b60](https://linux-hardware.org/?probe=f1a3807b60) | Apr 20, 2020 |
| Compal        | HEL80I                      | Notebook    | [41fd098e10](https://linux-hardware.org/?probe=41fd098e10) | Apr 20, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [00cedd86e4](https://linux-hardware.org/?probe=00cedd86e4) | Apr 19, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6b8e555d43](https://linux-hardware.org/?probe=6b8e555d43) | Apr 18, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f3b92c302c](https://linux-hardware.org/?probe=f3b92c302c) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [d1e3e7d629](https://linux-hardware.org/?probe=d1e3e7d629) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [a9b4abdd56](https://linux-hardware.org/?probe=a9b4abdd56) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [43f93a43d6](https://linux-hardware.org/?probe=43f93a43d6) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [20b4b0a6ad](https://linux-hardware.org/?probe=20b4b0a6ad) | Apr 16, 2020 |
| Dell          | 08NPPY A00                  | Desktop     | [895a4ce7cb](https://linux-hardware.org/?probe=895a4ce7cb) | Apr 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5fc32fd27b](https://linux-hardware.org/?probe=5fc32fd27b) | Apr 12, 2020 |
| Shuttle       | FH81                        | Desktop     | [61209bcee3](https://linux-hardware.org/?probe=61209bcee3) | Apr 11, 2020 |
| ASRock        | 890GX Extreme3              | Desktop     | [2f70e1ae2c](https://linux-hardware.org/?probe=2f70e1ae2c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [53b2f1863a](https://linux-hardware.org/?probe=53b2f1863a) | Apr 07, 2020 |
| ASRock        | 970 Extreme3                | Desktop     | [679cdbade2](https://linux-hardware.org/?probe=679cdbade2) | Apr 05, 2020 |
| HP            | 0A64h                       | Desktop     | [79aa6d6301](https://linux-hardware.org/?probe=79aa6d6301) | Apr 05, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [6b0efa548b](https://linux-hardware.org/?probe=6b0efa548b) | Apr 04, 2020 |
| ASUSTek       | P5K                         | Desktop     | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [a7f7938a12](https://linux-hardware.org/?probe=a7f7938a12) | Apr 02, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4db785101b](https://linux-hardware.org/?probe=4db785101b) | Apr 01, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e3c52f3d96](https://linux-hardware.org/?probe=e3c52f3d96) | Apr 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [c1582b3202](https://linux-hardware.org/?probe=c1582b3202) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [d018206f33](https://linux-hardware.org/?probe=d018206f33) | Mar 31, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [5038965b3b](https://linux-hardware.org/?probe=5038965b3b) | Mar 30, 2020 |
| HP            | ProBook 4540s               | Notebook    | [6b9b373a1f](https://linux-hardware.org/?probe=6b9b373a1f) | Mar 30, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [99865fe49f](https://linux-hardware.org/?probe=99865fe49f) | Mar 29, 2020 |
| ASUSTek       | P5K SE                      | Desktop     | [8492263fc0](https://linux-hardware.org/?probe=8492263fc0) | Mar 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c7eda36111](https://linux-hardware.org/?probe=c7eda36111) | Mar 28, 2020 |
| Acer          | Predator G3-572             | Notebook    | [9434c59ae1](https://linux-hardware.org/?probe=9434c59ae1) | Mar 28, 2020 |
| Acer          | Predator G3-572             | Notebook    | [11828122f2](https://linux-hardware.org/?probe=11828122f2) | Mar 28, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [edf4388f6a](https://linux-hardware.org/?probe=edf4388f6a) | Mar 26, 2020 |
| ASUSTek       | P5K SE                      | Desktop     | [fd766dda01](https://linux-hardware.org/?probe=fd766dda01) | Mar 26, 2020 |
| HP            | 620                         | Notebook    | [633afcbbef](https://linux-hardware.org/?probe=633afcbbef) | Mar 25, 2020 |
| HP            | 620                         | Notebook    | [8487590fa2](https://linux-hardware.org/?probe=8487590fa2) | Mar 25, 2020 |
| ASRock        | G41M-S3                     | Desktop     | [19c0625a28](https://linux-hardware.org/?probe=19c0625a28) | Mar 24, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c63e1ec4fd](https://linux-hardware.org/?probe=c63e1ec4fd) | Mar 23, 2020 |
| ASUSTek       | M4A3000E                    | Desktop     | [76ec7cf71b](https://linux-hardware.org/?probe=76ec7cf71b) | Mar 23, 2020 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [0d2e81fb9b](https://linux-hardware.org/?probe=0d2e81fb9b) | Mar 20, 2020 |
| ASUSTek       | P5K                         | Desktop     | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | Desktop     | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [b343a21e42](https://linux-hardware.org/?probe=b343a21e42) | Mar 17, 2020 |
| Lenovo        | ThinkPad T470p 20J6S0A30... | Notebook    | [b02f5ffeeb](https://linux-hardware.org/?probe=b02f5ffeeb) | Mar 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [14544480a5](https://linux-hardware.org/?probe=14544480a5) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [ccc20cb679](https://linux-hardware.org/?probe=ccc20cb679) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [7b2e2dc41d](https://linux-hardware.org/?probe=7b2e2dc41d) | Mar 15, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [252c5a9ab3](https://linux-hardware.org/?probe=252c5a9ab3) | Mar 15, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [810b827dfe](https://linux-hardware.org/?probe=810b827dfe) | Mar 15, 2020 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [13768f8615](https://linux-hardware.org/?probe=13768f8615) | Mar 14, 2020 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [53d0f3f5fc](https://linux-hardware.org/?probe=53d0f3f5fc) | Mar 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4c0f104328](https://linux-hardware.org/?probe=4c0f104328) | Mar 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [4587e48bf4](https://linux-hardware.org/?probe=4587e48bf4) | Mar 11, 2020 |
| Unknown       | K8NF6G-VSTA                 | Desktop     | [b4f0d62c45](https://linux-hardware.org/?probe=b4f0d62c45) | Mar 08, 2020 |
| Unknown       | K8NF6G-VSTA                 | Desktop     | [08691dfde3](https://linux-hardware.org/?probe=08691dfde3) | Mar 08, 2020 |
| ASRock        | 890FX Deluxe4               | Desktop     | [391c431de9](https://linux-hardware.org/?probe=391c431de9) | Mar 05, 2020 |
| HP            | Unknown                     | Notebook    | [453696ff5e](https://linux-hardware.org/?probe=453696ff5e) | Mar 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [5b7e72604e](https://linux-hardware.org/?probe=5b7e72604e) | Mar 04, 2020 |
| Dell          | G3 3579                     | Notebook    | [12a87598d6](https://linux-hardware.org/?probe=12a87598d6) | Mar 02, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [4c1a03683b](https://linux-hardware.org/?probe=4c1a03683b) | Mar 01, 2020 |
| Intel         | DQ57TM AAE92694-402         | Desktop     | [e82b578dad](https://linux-hardware.org/?probe=e82b578dad) | Feb 28, 2020 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [a513552c14](https://linux-hardware.org/?probe=a513552c14) | Feb 27, 2020 |
| HP            | Unknown                     | Notebook    | [f8a7212a74](https://linux-hardware.org/?probe=f8a7212a74) | Feb 26, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [d008370d87](https://linux-hardware.org/?probe=d008370d87) | Feb 24, 2020 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | Desktop     | [455dbd81e1](https://linux-hardware.org/?probe=455dbd81e1) | Feb 22, 2020 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [b09f7bb137](https://linux-hardware.org/?probe=b09f7bb137) | Feb 22, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [9c5def065e](https://linux-hardware.org/?probe=9c5def065e) | Feb 22, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8231b2fe22](https://linux-hardware.org/?probe=8231b2fe22) | Feb 18, 2020 |
| Dell          | Latitude 5401               | Notebook    | [76f6ff2608](https://linux-hardware.org/?probe=76f6ff2608) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | Notebook    | [4df7386234](https://linux-hardware.org/?probe=4df7386234) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | Notebook    | [d8f25b08f2](https://linux-hardware.org/?probe=d8f25b08f2) | Feb 16, 2020 |
| Lenovo        | ThinkPad T560 20FJS1YD00    | Notebook    | [b379bf7743](https://linux-hardware.org/?probe=b379bf7743) | Feb 15, 2020 |
| Acer          | Aspire 5541                 | Notebook    | [6bf6d1c16b](https://linux-hardware.org/?probe=6bf6d1c16b) | Feb 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [60281c26f1](https://linux-hardware.org/?probe=60281c26f1) | Feb 14, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [3977fb1ddb](https://linux-hardware.org/?probe=3977fb1ddb) | Feb 12, 2020 |
| ASUSTek       | A88XM-E                     | Desktop     | [ea21444fa7](https://linux-hardware.org/?probe=ea21444fa7) | Feb 11, 2020 |
| ASUSTek       | X501A                       | Notebook    | [9e5a342bac](https://linux-hardware.org/?probe=9e5a342bac) | Feb 10, 2020 |
| ASUSTek       | A88XM-E                     | Desktop     | [984a9c83fd](https://linux-hardware.org/?probe=984a9c83fd) | Feb 10, 2020 |
| HP            | 0A64h                       | Desktop     | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | Desktop     | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [c080de1bad](https://linux-hardware.org/?probe=c080de1bad) | Feb 03, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [75079b3cba](https://linux-hardware.org/?probe=75079b3cba) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [b3e528be2c](https://linux-hardware.org/?probe=b3e528be2c) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [8db2dfbc60](https://linux-hardware.org/?probe=8db2dfbc60) | Jan 29, 2020 |
| ASUSTek       | M2N68-CM                    | Desktop     | [201ca7dd72](https://linux-hardware.org/?probe=201ca7dd72) | Jan 28, 2020 |
| Lenovo        | ThinkPad X220 4291B24       | Notebook    | [ce7dd499a5](https://linux-hardware.org/?probe=ce7dd499a5) | Jan 24, 2020 |
| Toshiba       | Satellite L300              | Notebook    | [f5faa63427](https://linux-hardware.org/?probe=f5faa63427) | Jan 12, 2020 |
| ASUSTek       | K55VM                       | Notebook    | [c1595f145d](https://linux-hardware.org/?probe=c1595f145d) | Jan 11, 2020 |
| ASRock        | AB350M Pro4 R2.0            | Desktop     | [11e945005f](https://linux-hardware.org/?probe=11e945005f) | Jan 08, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6056ef2c40](https://linux-hardware.org/?probe=6056ef2c40) | Jan 07, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [601d03392f](https://linux-hardware.org/?probe=601d03392f) | Jan 05, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [3f4d79ea3b](https://linux-hardware.org/?probe=3f4d79ea3b) | Jan 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [aa34232c5a](https://linux-hardware.org/?probe=aa34232c5a) | Jan 01, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [6bca5f0ae4](https://linux-hardware.org/?probe=6bca5f0ae4) | Jan 01, 2020 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [353a1db8ac](https://linux-hardware.org/?probe=353a1db8ac) | Dec 31, 2019 |
| TUXEDO        | Unknown                     | Notebook    | [8393427822](https://linux-hardware.org/?probe=8393427822) | Dec 27, 2019 |
| HP            | 530 Notebook PC(KP479AA#... | Notebook    | [3e6684e155](https://linux-hardware.org/?probe=3e6684e155) | Dec 27, 2019 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [f885d0ee5f](https://linux-hardware.org/?probe=f885d0ee5f) | Dec 23, 2019 |
| Dell          | Inspiron 5482               | Notebook    | [85bb9ecf3b](https://linux-hardware.org/?probe=85bb9ecf3b) | Dec 20, 2019 |
| Acer          | Switch SA5-271              | Tablet      | [2d71938fc4](https://linux-hardware.org/?probe=2d71938fc4) | Dec 20, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| Lenovo        | B51-30 80LK                 | Notebook    | [32d296fee0](https://linux-hardware.org/?probe=32d296fee0) | Dec 19, 2019 |
| Foxconn       | A55MX                       | Desktop     | [05c6b7995d](https://linux-hardware.org/?probe=05c6b7995d) | Dec 19, 2019 |
| Lenovo        | ThinkCentre M91p 7033W9N    | Desktop     | [3eb7eb388c](https://linux-hardware.org/?probe=3eb7eb388c) | Dec 17, 2019 |
| Lenovo        | ThinkCentre M91p 7033W9N    | Desktop     | [aaa8d34fff](https://linux-hardware.org/?probe=aaa8d34fff) | Dec 17, 2019 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6e09a0e0aa](https://linux-hardware.org/?probe=6e09a0e0aa) | Dec 16, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [d5fec65df9](https://linux-hardware.org/?probe=d5fec65df9) | Dec 13, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [0a74735da6](https://linux-hardware.org/?probe=0a74735da6) | Dec 12, 2019 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [a9a218f5dd](https://linux-hardware.org/?probe=a9a218f5dd) | Dec 06, 2019 |
| Dell          | Studio 1747                 | Notebook    | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Acer          | Aspire E5-572G              | Notebook    | [0c710c33f6](https://linux-hardware.org/?probe=0c710c33f6) | Dec 04, 2019 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [87afd7dd02](https://linux-hardware.org/?probe=87afd7dd02) | Dec 04, 2019 |
| Dell          | Studio 1747                 | Notebook    | [2daf1225e6](https://linux-hardware.org/?probe=2daf1225e6) | Dec 04, 2019 |
| Dell          | Studio 1747                 | Notebook    | [dfba5a95c8](https://linux-hardware.org/?probe=dfba5a95c8) | Dec 04, 2019 |
| Dell          | Studio 1747                 | Notebook    | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| HP            | 1850                        | Desktop     | [898f2b7197](https://linux-hardware.org/?probe=898f2b7197) | Dec 01, 2019 |
| ASRock        | B85M Pro4                   | Desktop     | [c6b09d560f](https://linux-hardware.org/?probe=c6b09d560f) | Nov 30, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [ade7b4eb87](https://linux-hardware.org/?probe=ade7b4eb87) | Nov 29, 2019 |
| ASUSTek       | H97-PLUS                    | Desktop     | [5b9bb1aedb](https://linux-hardware.org/?probe=5b9bb1aedb) | Nov 28, 2019 |
| ASUSTek       | H97-PLUS                    | Desktop     | [115ab4a8a7](https://linux-hardware.org/?probe=115ab4a8a7) | Nov 28, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [781e93ad34](https://linux-hardware.org/?probe=781e93ad34) | Nov 26, 2019 |
| ASRock        | H61M-GS                     | Desktop     | [b0cff72d0c](https://linux-hardware.org/?probe=b0cff72d0c) | Nov 24, 2019 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9081234810](https://linux-hardware.org/?probe=9081234810) | Nov 22, 2019 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f61b57f6fc](https://linux-hardware.org/?probe=f61b57f6fc) | Nov 22, 2019 |
| ASUSTek       | X505BP                      | Notebook    | [a881fdcf1b](https://linux-hardware.org/?probe=a881fdcf1b) | Nov 21, 2019 |
| iEi           | B202 V1.0                   | Desktop     | [16699afe19](https://linux-hardware.org/?probe=16699afe19) | Nov 13, 2019 |
| ASRock        | H61M-VG3                    | Desktop     | [6bc9ab22bf](https://linux-hardware.org/?probe=6bc9ab22bf) | Nov 11, 2019 |
| Gigabyte      | W348M                       | Notebook    | [0db51928b9](https://linux-hardware.org/?probe=0db51928b9) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [a2fe589062](https://linux-hardware.org/?probe=a2fe589062) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [2e5a5d8827](https://linux-hardware.org/?probe=2e5a5d8827) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [616c5e7edb](https://linux-hardware.org/?probe=616c5e7edb) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [a5359e7def](https://linux-hardware.org/?probe=a5359e7def) | Oct 29, 2019 |
| Foxconn       | A6VMX 0A                    | Desktop     | [74249dc009](https://linux-hardware.org/?probe=74249dc009) | Oct 29, 2019 |
| Dell          | Latitude E6410              | Notebook    | [2888ece276](https://linux-hardware.org/?probe=2888ece276) | Oct 27, 2019 |
| Dell          | G7 7588                     | Notebook    | [2479b39b58](https://linux-hardware.org/?probe=2479b39b58) | Oct 27, 2019 |
| iEi           | B202 V1.0                   | Desktop     | [bffdad4a05](https://linux-hardware.org/?probe=bffdad4a05) | Oct 26, 2019 |
| Dell          | Inspiron 3580               | Notebook    | [29ff86014c](https://linux-hardware.org/?probe=29ff86014c) | Oct 22, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASRock        | H61M-VG3                    | Desktop     | [260918f990](https://linux-hardware.org/?probe=260918f990) | Oct 22, 2019 |
| Dell          | Inspiron 3580               | Notebook    | [8e4e877bc9](https://linux-hardware.org/?probe=8e4e877bc9) | Oct 22, 2019 |
| ASUSTek       | N53SN                       | Notebook    | [b41d353d8b](https://linux-hardware.org/?probe=b41d353d8b) | Oct 18, 2019 |
| Acer          | Aspire C22-865              | All in one  | [c861864ed7](https://linux-hardware.org/?probe=c861864ed7) | Oct 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [cc14742c63](https://linux-hardware.org/?probe=cc14742c63) | Oct 16, 2019 |
| Foxconn       | A6VMX 0A                    | Desktop     | [7991685c3a](https://linux-hardware.org/?probe=7991685c3a) | Oct 14, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [592a40c6d4](https://linux-hardware.org/?probe=592a40c6d4) | Oct 13, 2019 |
| Dell          | G3 3579                     | Notebook    | [d04a01d41c](https://linux-hardware.org/?probe=d04a01d41c) | Oct 10, 2019 |
| Dell          | Latitude E6320              | Notebook    | [0c6c848244](https://linux-hardware.org/?probe=0c6c848244) | Oct 09, 2019 |
| HP            | ProBook 470 G0              | Notebook    | [d04f4a23f0](https://linux-hardware.org/?probe=d04f4a23f0) | Oct 07, 2019 |
| Dell          | Latitude E6320              | Notebook    | [0bc384b06e](https://linux-hardware.org/?probe=0bc384b06e) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [59d8f18e3d](https://linux-hardware.org/?probe=59d8f18e3d) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [79c9edf47a](https://linux-hardware.org/?probe=79c9edf47a) | Oct 06, 2019 |
| Dell          | G3 3579                     | Notebook    | [349416fbb3](https://linux-hardware.org/?probe=349416fbb3) | Oct 05, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [0c0cfccb6f](https://linux-hardware.org/?probe=0c0cfccb6f) | Oct 02, 2019 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [54db2b52da](https://linux-hardware.org/?probe=54db2b52da) | Oct 02, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [bb0a5f1b8e](https://linux-hardware.org/?probe=bb0a5f1b8e) | Sep 28, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [28b8e9271b](https://linux-hardware.org/?probe=28b8e9271b) | Sep 27, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3cf419c507](https://linux-hardware.org/?probe=3cf419c507) | Sep 27, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [e1a5ba64a3](https://linux-hardware.org/?probe=e1a5ba64a3) | Sep 23, 2019 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | Desktop     | [fbd6f89151](https://linux-hardware.org/?probe=fbd6f89151) | Sep 19, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [3a2e4ab12c](https://linux-hardware.org/?probe=3a2e4ab12c) | Sep 18, 2019 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [5c664d23d8](https://linux-hardware.org/?probe=5c664d23d8) | Sep 17, 2019 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [ff27a61c6c](https://linux-hardware.org/?probe=ff27a61c6c) | Sep 16, 2019 |
| HP            | Compaq 6715s (GR762ES#AB... | Notebook    | [320661ca9f](https://linux-hardware.org/?probe=320661ca9f) | Sep 16, 2019 |
| Toshiba       | Satellite L855              | Notebook    | [f5d2dffc84](https://linux-hardware.org/?probe=f5d2dffc84) | Sep 13, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [fca2fc959c](https://linux-hardware.org/?probe=fca2fc959c) | Sep 13, 2019 |
| Notebook      | P17SM-A                     | Notebook    | [6ccaea7ee4](https://linux-hardware.org/?probe=6ccaea7ee4) | Sep 11, 2019 |
| HP            | Pavilion dv6                | Notebook    | [4ddfed675e](https://linux-hardware.org/?probe=4ddfed675e) | Sep 07, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [612c5f53a4](https://linux-hardware.org/?probe=612c5f53a4) | Sep 07, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [9f517e5081](https://linux-hardware.org/?probe=9f517e5081) | Aug 31, 2019 |
| ASUSTek       | K55VD                       | Notebook    | [072fcfd6de](https://linux-hardware.org/?probe=072fcfd6de) | Aug 29, 2019 |
| Dell          | Precision M4600             | Notebook    | [9a70878de0](https://linux-hardware.org/?probe=9a70878de0) | Aug 26, 2019 |
| ASRock        | A75M-HVS                    | Desktop     | [c5d625831f](https://linux-hardware.org/?probe=c5d625831f) | Aug 23, 2019 |
| Dell          | Vostro 3559                 | Notebook    | [0ec7ad0379](https://linux-hardware.org/?probe=0ec7ad0379) | Aug 22, 2019 |
| Fujitsu       | CELSIUS H730                | Notebook    | [69d7eea0f3](https://linux-hardware.org/?probe=69d7eea0f3) | Aug 21, 2019 |
| Fujitsu       | CELSIUS H730                | Notebook    | [896ecfb0f1](https://linux-hardware.org/?probe=896ecfb0f1) | Aug 21, 2019 |
| Fujitsu       | CELSIUS H730                | Notebook    | [f94cbdeb8e](https://linux-hardware.org/?probe=f94cbdeb8e) | Aug 21, 2019 |
| Dell          | 0XCR8D A02                  | Desktop     | [ed9cabe6d7](https://linux-hardware.org/?probe=ed9cabe6d7) | Aug 16, 2019 |
| Dell          | Inspiron 5482               | Notebook    | [637995a063](https://linux-hardware.org/?probe=637995a063) | Aug 15, 2019 |
| HP            | Compaq 6830s                | Notebook    | [525e681524](https://linux-hardware.org/?probe=525e681524) | Aug 07, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [8cfc8e44ca](https://linux-hardware.org/?probe=8cfc8e44ca) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | Desktop     | [97e0e3e7ce](https://linux-hardware.org/?probe=97e0e3e7ce) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | Desktop     | [662d4876ce](https://linux-hardware.org/?probe=662d4876ce) | Aug 04, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [1e288a14af](https://linux-hardware.org/?probe=1e288a14af) | Aug 03, 2019 |
| Fujitsu       | LIFEBOOK N532               | Notebook    | [b9a4817612](https://linux-hardware.org/?probe=b9a4817612) | Jul 28, 2019 |
| Fujitsu Si... | D2344-A3 S26361-D2344-A3    | Desktop     | [82e5d349d1](https://linux-hardware.org/?probe=82e5d349d1) | Jul 28, 2019 |
| HP            | 09F8h                       | Desktop     | [c52ee1274d](https://linux-hardware.org/?probe=c52ee1274d) | Jul 27, 2019 |
| Medion        | P7648 MD99980               | Notebook    | [ac77e66d3f](https://linux-hardware.org/?probe=ac77e66d3f) | Jul 24, 2019 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [6790768959](https://linux-hardware.org/?probe=6790768959) | Jul 20, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [b531eab1de](https://linux-hardware.org/?probe=b531eab1de) | Jul 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [06603d3dce](https://linux-hardware.org/?probe=06603d3dce) | Jul 14, 2019 |
| Dell          | Latitude E4300              | Notebook    | [59050a5736](https://linux-hardware.org/?probe=59050a5736) | Jul 10, 2019 |
| Dell          | Inspiron 3551               | Notebook    | [ff1bf9089c](https://linux-hardware.org/?probe=ff1bf9089c) | Jul 08, 2019 |
| Dell          | Inspiron 3551               | Notebook    | [8add5e4718](https://linux-hardware.org/?probe=8add5e4718) | Jul 08, 2019 |
| Acer          | Aspire 5552G                | Notebook    | [e5d4cddd0b](https://linux-hardware.org/?probe=e5d4cddd0b) | Jul 07, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [1811b66e00](https://linux-hardware.org/?probe=1811b66e00) | Jul 05, 2019 |
| HP            | Pavilion 15                 | Notebook    | [bc7f328871](https://linux-hardware.org/?probe=bc7f328871) | Jul 02, 2019 |
| Pegatron      | A15                         | Notebook    | [754abad872](https://linux-hardware.org/?probe=754abad872) | Jul 01, 2019 |
| Acer          | Aspire A315-31              | Notebook    | [475d99370e](https://linux-hardware.org/?probe=475d99370e) | Jul 01, 2019 |
| ASUSTek       | M4A78T-E                    | Desktop     | [607db49638](https://linux-hardware.org/?probe=607db49638) | Jun 22, 2019 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [d8c3110cba](https://linux-hardware.org/?probe=d8c3110cba) | Jun 22, 2019 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [dfc4a93cdf](https://linux-hardware.org/?probe=dfc4a93cdf) | Jun 21, 2019 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [b95d164f8c](https://linux-hardware.org/?probe=b95d164f8c) | Jun 19, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [ae491db991](https://linux-hardware.org/?probe=ae491db991) | Jun 15, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7a53859124](https://linux-hardware.org/?probe=7a53859124) | Jun 15, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [30068f1670](https://linux-hardware.org/?probe=30068f1670) | Jun 09, 2019 |
| Foxconn       | 945 7MD Series              | Desktop     | [1acc3bbabb](https://linux-hardware.org/?probe=1acc3bbabb) | Jun 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c6ced8e5a5](https://linux-hardware.org/?probe=c6ced8e5a5) | Jun 02, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [d78c1d6096](https://linux-hardware.org/?probe=d78c1d6096) | May 27, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [c8bb3e23f9](https://linux-hardware.org/?probe=c8bb3e23f9) | May 27, 2019 |
| Lenovo        | Unknown                     | Notebook    | [157cdcf284](https://linux-hardware.org/?probe=157cdcf284) | May 26, 2019 |
| ASUSTek       | K73SD                       | Notebook    | [d00a49591e](https://linux-hardware.org/?probe=d00a49591e) | May 22, 2019 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [d814f4eab3](https://linux-hardware.org/?probe=d814f4eab3) | May 21, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [9ed71fdbcf](https://linux-hardware.org/?probe=9ed71fdbcf) | May 20, 2019 |
| Acer          | Aspire VN7-592G             | Notebook    | [5423f5da6b](https://linux-hardware.org/?probe=5423f5da6b) | May 19, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [b18be16b85](https://linux-hardware.org/?probe=b18be16b85) | May 17, 2019 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [673c1426f0](https://linux-hardware.org/?probe=673c1426f0) | May 12, 2019 |
| Acer          | Aspire A315-31              | Notebook    | [e19546ffd9](https://linux-hardware.org/?probe=e19546ffd9) | May 12, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [5fa03a3e8f](https://linux-hardware.org/?probe=5fa03a3e8f) | May 07, 2019 |
| ASUSTek       | M2N-X                       | Desktop     | [aa1ba4b47d](https://linux-hardware.org/?probe=aa1ba4b47d) | May 07, 2019 |
| Dell          | Latitude E6540              | Notebook    | [a12e80fc14](https://linux-hardware.org/?probe=a12e80fc14) | May 04, 2019 |
| HP            | 1906                        | Desktop     | [7ea8acd893](https://linux-hardware.org/?probe=7ea8acd893) | May 01, 2019 |
| Fujitsu       | D3004-A1 S26361-D3004-A1    | Desktop     | [17448d5b73](https://linux-hardware.org/?probe=17448d5b73) | Apr 29, 2019 |
| LG Electro... | FS-2A46HS                   | Notebook    | [c71f72f074](https://linux-hardware.org/?probe=c71f72f074) | Apr 27, 2019 |
| LG Electro... | FS-2A46HS                   | Notebook    | [aafcf2ac24](https://linux-hardware.org/?probe=aafcf2ac24) | Apr 27, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [8bdeeb7120](https://linux-hardware.org/?probe=8bdeeb7120) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [803ca8464c](https://linux-hardware.org/?probe=803ca8464c) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [01575f8e47](https://linux-hardware.org/?probe=01575f8e47) | Apr 22, 2019 |
| Lenovo        | IdeaPad Z580                | Notebook    | [88ec17f6dc](https://linux-hardware.org/?probe=88ec17f6dc) | Apr 18, 2019 |
| HP            | ProBook 6470b               | Notebook    | [6008fdba9d](https://linux-hardware.org/?probe=6008fdba9d) | Apr 17, 2019 |
| ASRock        | B150M Pro4                  | Desktop     | [8227df5ae7](https://linux-hardware.org/?probe=8227df5ae7) | Apr 13, 2019 |
| HP            | EliteBook 8740w             | Notebook    | [adfd8e7463](https://linux-hardware.org/?probe=adfd8e7463) | Apr 12, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [f0021f0fdc](https://linux-hardware.org/?probe=f0021f0fdc) | Apr 12, 2019 |
| Dell          | Inspiron 3737               | Notebook    | [86eb821fa9](https://linux-hardware.org/?probe=86eb821fa9) | Apr 11, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [de1581a896](https://linux-hardware.org/?probe=de1581a896) | Apr 11, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [092bae147c](https://linux-hardware.org/?probe=092bae147c) | Apr 09, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [51988ce7c2](https://linux-hardware.org/?probe=51988ce7c2) | Apr 09, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [5be2bd43e2](https://linux-hardware.org/?probe=5be2bd43e2) | Apr 07, 2019 |
| Lenovo        | G580                        | Notebook    | [1b00fafcef](https://linux-hardware.org/?probe=1b00fafcef) | Apr 07, 2019 |
| Acer          | Switch SA5-271              | Tablet      | [d6efa0f211](https://linux-hardware.org/?probe=d6efa0f211) | Apr 04, 2019 |
| Acer          | Switch SA5-271              | Tablet      | [16c137508d](https://linux-hardware.org/?probe=16c137508d) | Mar 25, 2019 |
| Dell          | 0K240Y A02                  | Desktop     | [e206f8f36e](https://linux-hardware.org/?probe=e206f8f36e) | Mar 25, 2019 |
| Acer          | TravelMate P645-SG          | Notebook    | [e6ed7a4f8d](https://linux-hardware.org/?probe=e6ed7a4f8d) | Mar 24, 2019 |
| Lenovo        | ThinkPad X220 42903WG       | Notebook    | [edaa665dea](https://linux-hardware.org/?probe=edaa665dea) | Mar 19, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [a74f00993b](https://linux-hardware.org/?probe=a74f00993b) | Mar 12, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [b484a879d4](https://linux-hardware.org/?probe=b484a879d4) | Mar 08, 2019 |
| Lenovo        | G580                        | Notebook    | [2f4b4e326a](https://linux-hardware.org/?probe=2f4b4e326a) | Mar 01, 2019 |
| ASUSTek       | K55A                        | Notebook    | [cbd602db5a](https://linux-hardware.org/?probe=cbd602db5a) | Mar 01, 2019 |
| ASUSTek       | K55A                        | Notebook    | [48f636d07e](https://linux-hardware.org/?probe=48f636d07e) | Mar 01, 2019 |
| ASUSTek       | X541UJ                      | Notebook    | [98740161c5](https://linux-hardware.org/?probe=98740161c5) | Feb 26, 2019 |
| ASUSTek       | X541UJ                      | Notebook    | [0dc58e8846](https://linux-hardware.org/?probe=0dc58e8846) | Feb 26, 2019 |
| Dell          | Latitude E7440              | Notebook    | [c0f66137fc](https://linux-hardware.org/?probe=c0f66137fc) | Feb 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [713a79e7e2](https://linux-hardware.org/?probe=713a79e7e2) | Feb 15, 2019 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [651cb8fea0](https://linux-hardware.org/?probe=651cb8fea0) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | Desktop     | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | Desktop     | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ASUSTek       | P5P43TD                     | Desktop     | [8d55cb4dca](https://linux-hardware.org/?probe=8d55cb4dca) | Feb 10, 2019 |
| Medion        | E1210                       | Notebook    | [5dfe8d16da](https://linux-hardware.org/?probe=5dfe8d16da) | Jan 26, 2019 |
| ASRock        | Z97 Anniversary             | Desktop     | [672985bb0e](https://linux-hardware.org/?probe=672985bb0e) | Jan 26, 2019 |
| ASUSTek       | X705UNR                     | Notebook    | [b9e37eb37f](https://linux-hardware.org/?probe=b9e37eb37f) | Jan 20, 2019 |
| ASUSTek       | X705UNR                     | Notebook    | [45fa0ef0e3](https://linux-hardware.org/?probe=45fa0ef0e3) | Jan 20, 2019 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [7d38422be6](https://linux-hardware.org/?probe=7d38422be6) | Jan 19, 2019 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [9c98fa7c5a](https://linux-hardware.org/?probe=9c98fa7c5a) | Jan 19, 2019 |
| ASUSTek       | GL553VE                     | Notebook    | [1ccc6b1335](https://linux-hardware.org/?probe=1ccc6b1335) | Jan 12, 2019 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [e74d60bf4b](https://linux-hardware.org/?probe=e74d60bf4b) | Jan 08, 2019 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [f5081cb119](https://linux-hardware.org/?probe=f5081cb119) | Jan 08, 2019 |
| Acer          | Extensa X2610G              | Desktop     | [92c3e82d58](https://linux-hardware.org/?probe=92c3e82d58) | Jan 02, 2019 |
| ASUSTek       | GL553VE                     | Notebook    | [468cd6a626](https://linux-hardware.org/?probe=468cd6a626) | Dec 25, 2018 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [38757f20cd](https://linux-hardware.org/?probe=38757f20cd) | Dec 16, 2018 |
| ASRock        | B85M Pro3                   | Desktop     | [70f28e74b9](https://linux-hardware.org/?probe=70f28e74b9) | Dec 10, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [e54f5af29a](https://linux-hardware.org/?probe=e54f5af29a) | Dec 08, 2018 |
| Dell          | Precision M4600             | Notebook    | [812a28db21](https://linux-hardware.org/?probe=812a28db21) | Dec 05, 2018 |
| Dell          | Precision M4600             | Notebook    | [8057a5e7af](https://linux-hardware.org/?probe=8057a5e7af) | Dec 05, 2018 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [2821650e1b](https://linux-hardware.org/?probe=2821650e1b) | Dec 03, 2018 |
| ASRock        | Z370 Pro4                   | Desktop     | [7594332b68](https://linux-hardware.org/?probe=7594332b68) | Dec 02, 2018 |
| ASRock        | Z370 Pro4                   | Desktop     | [900f783b11](https://linux-hardware.org/?probe=900f783b11) | Dec 02, 2018 |
| ASUSTek       | X541NA                      | Notebook    | [bdaeaf5ca2](https://linux-hardware.org/?probe=bdaeaf5ca2) | Nov 30, 2018 |
| Acer          | TravelMate P645-SG          | Notebook    | [b4dc1aeb7a](https://linux-hardware.org/?probe=b4dc1aeb7a) | Nov 25, 2018 |
| ASUSTek       | X541NA                      | Notebook    | [aee08bb40e](https://linux-hardware.org/?probe=aee08bb40e) | Nov 18, 2018 |
| ASRock        | B360M-HDV                   | Desktop     | [fb017cece0](https://linux-hardware.org/?probe=fb017cece0) | Nov 16, 2018 |
| ASRock        | Z77 Extreme3                | Desktop     | [a85b28c3f9](https://linux-hardware.org/?probe=a85b28c3f9) | Nov 15, 2018 |
| HP            | ProBook 4540s               | Notebook    | [06de7c3363](https://linux-hardware.org/?probe=06de7c3363) | Oct 14, 2018 |
| Gigabyte      | H81M-S2V                    | Desktop     | [801b3fb729](https://linux-hardware.org/?probe=801b3fb729) | Jun 27, 2018 |
| Lenovo        | ThinkPad W500 4063E94       | Notebook    | [1501370ab2](https://linux-hardware.org/?probe=1501370ab2) | Jun 23, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [c3e231dcc8](https://linux-hardware.org/?probe=c3e231dcc8) | Jun 16, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [2f69425a7c](https://linux-hardware.org/?probe=2f69425a7c) | Apr 30, 2018 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ee5ac544fa](https://linux-hardware.org/?probe=ee5ac544fa) | Feb 24, 2018 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [fbd1d0b016](https://linux-hardware.org/?probe=fbd1d0b016) | Feb 23, 2018 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cbd88fab14](https://linux-hardware.org/?probe=cbd88fab14) | Feb 18, 2018 |
| HP            | Mini 311-1000               | Notebook    | [82a73faa41](https://linux-hardware.org/?probe=82a73faa41) | Feb 06, 2018 |
| Notebook      | P17SM-A                     | Notebook    | [5231746786](https://linux-hardware.org/?probe=5231746786) | Jan 25, 2018 |
| Acer          | Aspire XC-605               | Desktop     | [cbd8d79578](https://linux-hardware.org/?probe=cbd8d79578) | Jan 19, 2018 |
| Lenovo        | ThinkPad X200 2024A11       | Notebook    | [cebad9ea77](https://linux-hardware.org/?probe=cebad9ea77) | Jan 08, 2018 |
| HP            | Mini 311-1000               | Notebook    | [f0cf0539e0](https://linux-hardware.org/?probe=f0cf0539e0) | Jan 04, 2018 |
| Lenovo        | ThinkPad X200 2024A11       | Notebook    | [751eb89800](https://linux-hardware.org/?probe=751eb89800) | Dec 27, 2017 |
| Toshiba       | Satellite L300              | Notebook    | [62a451c290](https://linux-hardware.org/?probe=62a451c290) | Dec 21, 2017 |
| Foxconn       | A6VMX 0A                    | Desktop     | [8ba0c7f4c3](https://linux-hardware.org/?probe=8ba0c7f4c3) | Dec 21, 2017 |
| Toshiba       | Satellite Pro R850          | Notebook    | [8f76c37692](https://linux-hardware.org/?probe=8f76c37692) | Dec 11, 2017 |
| HP            | Mini 311-1000               | Notebook    | [53f93e34f5](https://linux-hardware.org/?probe=53f93e34f5) | Nov 30, 2017 |
| ASUSTek       | K53SV                       | Notebook    | [ddd21d12ef](https://linux-hardware.org/?probe=ddd21d12ef) | Nov 28, 2017 |
| Toshiba       | Satellite L300              | Notebook    | [5ff5de6e1c](https://linux-hardware.org/?probe=5ff5de6e1c) | Nov 14, 2017 |
| Lenovo        | G50-45 80E3                 | Notebook    | [150bc63715](https://linux-hardware.org/?probe=150bc63715) | Nov 06, 2017 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [9722b2d773](https://linux-hardware.org/?probe=9722b2d773) | Oct 31, 2017 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [728c8e49b2](https://linux-hardware.org/?probe=728c8e49b2) | Oct 27, 2017 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8db3dd798e](https://linux-hardware.org/?probe=8db3dd798e) | Sep 05, 2017 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [9f96da724a](https://linux-hardware.org/?probe=9f96da724a) | Sep 05, 2017 |
| Dell          | 0NKW6Y A00                  | Desktop     | [212f6d0514](https://linux-hardware.org/?probe=212f6d0514) | Sep 03, 2017 |
| HP            | Compaq nx7400 (RU430ET#A... | Notebook    | [6d9cfb4cb9](https://linux-hardware.org/?probe=6d9cfb4cb9) | Jul 30, 2017 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [0c3b83b208](https://linux-hardware.org/?probe=0c3b83b208) | Jun 06, 2017 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [0a1b2311b5](https://linux-hardware.org/?probe=0a1b2311b5) | May 28, 2017 |
| ASUSTek       | X540LJ                      | Notebook    | [7cd67a8489](https://linux-hardware.org/?probe=7cd67a8489) | Apr 26, 2017 |
| ASUSTek       | X540LJ                      | Notebook    | [f79d8f68ca](https://linux-hardware.org/?probe=f79d8f68ca) | Apr 26, 2017 |
| Supermicro    | C2SBC-Q                     | Desktop     | [671517f196](https://linux-hardware.org/?probe=671517f196) | Apr 15, 2017 |
| Acer          | Aspire V5-573G              | Notebook    | [fb0bbb47d3](https://linux-hardware.org/?probe=fb0bbb47d3) | Feb 23, 2017 |
| ASRock        | H61M-GS                     | Desktop     | [5625f5be6e](https://linux-hardware.org/?probe=5625f5be6e) | Jan 30, 2017 |
| ASRock        | H61M-GS                     | Desktop     | [f309dd0e46](https://linux-hardware.org/?probe=f309dd0e46) | Jan 24, 2017 |
| ASRock        | H61M-GS                     | Desktop     | [eb755563bf](https://linux-hardware.org/?probe=eb755563bf) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 107       | 12.97%  |
| Ubuntu 18.04                 | 80        | 9.7%    |
| OpenMandriva 4.2             | 29        | 3.52%   |
| ROSA R11                     | 18        | 2.18%   |
| OpenMandriva 4.3             | 17        | 2.06%   |
| Linux Mint 20.1              | 17        | 2.06%   |
| KDE neon 20.04               | 17        | 2.06%   |
| Debian 11                    | 17        | 2.06%   |
| ROSA R10                     | 16        | 1.94%   |
| Manjaro                      | 16        | 1.94%   |
| Linux Mint 19.3              | 14        | 1.7%    |
| Ubuntu 22.04                 | 13        | 1.58%   |
| Ubuntu 19.04                 | 13        | 1.58%   |
| Arch                         | 13        | 1.58%   |
| Xubuntu 18.04                | 12        | 1.45%   |
| Ubuntu 19.10                 | 12        | 1.45%   |
| Ubuntu 16.04                 | 12        | 1.45%   |
| Linux Mint 20.2              | 12        | 1.45%   |
| Kubuntu 20.04                | 12        | 1.45%   |
| Zorin 15                     | 11        | 1.33%   |
| Linux Mint 20                | 11        | 1.33%   |
| ArcoLinux Rolling            | 11        | 1.33%   |
| Xubuntu 20.04                | 10        | 1.21%   |
| Pop!_OS 20.10                | 10        | 1.21%   |
| Linux Mint 20.3              | 10        | 1.21%   |
| Fedora 33                    | 10        | 1.21%   |
| Ubuntu 20.10                 | 9         | 1.09%   |
| LMDE 4                       | 9         | 1.09%   |
| Zorin 16                     | 7         | 0.85%   |
| ROSA R9                      | 7         | 0.85%   |
| Pop!_OS 20.04                | 7         | 0.85%   |
| Fedora 35                    | 7         | 0.85%   |
| Fedora 34                    | 7         | 0.85%   |
| Fedora 31                    | 7         | 0.85%   |
| ROSA R11.1                   | 6         | 0.73%   |
| Pop!_OS 21.10                | 6         | 0.73%   |
| Pop!_OS 21.04                | 6         | 0.73%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.73%   |
| Ubuntu 21.10                 | 5         | 0.61%   |
| ROSA R8.1                    | 5         | 0.61%   |
| OpenMandriva 4.50            | 5         | 0.61%   |
| Fedora 36                    | 5         | 0.61%   |
| Debian 10                    | 5         | 0.61%   |
| Arch Rolling                 | 5         | 0.61%   |
| Ubuntu 21.04                 | 4         | 0.48%   |
| KDE neon 18.04               | 4         | 0.48%   |
| CentOS 7                     | 4         | 0.48%   |
| Void Linux Rolling           | 3         | 0.36%   |
| Ubuntu 18.10                 | 3         | 0.36%   |
| Manjaro 21.2.0               | 3         | 0.36%   |
| Manjaro 20.2                 | 3         | 0.36%   |
| Manjaro 20.0.3               | 3         | 0.36%   |
| Kali 2021.4                  | 3         | 0.36%   |
| Gentoo 2.6                   | 3         | 0.36%   |
| Fedora 32                    | 3         | 0.36%   |
| Fedora 29                    | 3         | 0.36%   |
| Debian 9                     | 3         | 0.36%   |
| Xubuntu 21.10                | 2         | 0.24%   |
| Ubuntu MATE 20.04            | 2         | 0.24%   |
| ROSA R8                      | 2         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 246       | 32.54%  |
| Linux Mint    | 65        | 8.6%    |
| OpenMandriva  | 51        | 6.75%   |
| ROSA          | 47        | 6.22%   |
| Manjaro       | 35        | 4.63%   |
| Fedora        | 35        | 4.63%   |
| Pop!_OS       | 30        | 3.97%   |
| Endless       | 27        | 3.57%   |
| Debian        | 26        | 3.44%   |
| Xubuntu       | 24        | 3.17%   |
| KDE neon      | 21        | 2.78%   |
| Zorin         | 18        | 2.38%   |
| Arch          | 18        | 2.38%   |
| Kubuntu       | 17        | 2.25%   |
| ArcoLinux     | 13        | 1.72%   |
| Clear Linux   | 12        | 1.59%   |
| LMDE          | 9         | 1.19%   |
| Kali          | 9         | 1.19%   |
| openSUSE      | 7         | 0.93%   |
| Lubuntu       | 7         | 0.93%   |
| CentOS        | 6         | 0.79%   |
| Elementary    | 5         | 0.66%   |
| Artix         | 4         | 0.53%   |
| Void Linux    | 3         | 0.4%    |
| Gentoo        | 3         | 0.4%    |
| Ubuntu MATE   | 2         | 0.26%   |
| Novos         | 2         | 0.26%   |
| EndeavourOS   | 2         | 0.26%   |
| Ubuntu Studio | 1         | 0.13%   |
| Ubuntu Budgie | 1         | 0.13%   |
| Slackware     | 1         | 0.13%   |
| RHEL          | 1         | 0.13%   |
| PureOS        | 1         | 0.13%   |
| Peppermint    | 1         | 0.13%   |
| Parrot        | 1         | 0.13%   |
| Oracle Linux  | 1         | 0.13%   |
| Mageia        | 1         | 0.13%   |
| Feren OS      | 1         | 0.13%   |
| Deepin        | 1         | 0.13%   |
| BlackPanther  | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002         | 29        | 3.2%    |
| 5.4.0-42-generic                 | 17        | 1.87%   |
| 5.16.7-desktop-1omv4003          | 17        | 1.87%   |
| 5.4.0-58-generic                 | 13        | 1.43%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 13        | 1.43%   |
| 5.3.0-40-generic                 | 10        | 1.1%    |
| 5.9.16-1-MANJARO                 | 8         | 0.88%   |
| 5.4.0-48-generic                 | 7         | 0.77%   |
| 5.4.0-29-generic                 | 7         | 0.77%   |
| 5.4.0-26-generic                 | 7         | 0.77%   |
| 5.3.0-28-generic                 | 7         | 0.77%   |
| 5.10.0-8-amd64                   | 7         | 0.77%   |
| 5.0.0-37-generic                 | 7         | 0.77%   |
| 5.8.0-14-generic                 | 6         | 0.66%   |
| 5.4.0-65-generic                 | 6         | 0.66%   |
| 5.4.0-56-generic                 | 6         | 0.66%   |
| 5.4.0-40-generic                 | 6         | 0.66%   |
| 5.3.0-46-generic                 | 6         | 0.66%   |
| 5.3.0-42-generic                 | 6         | 0.66%   |
| 5.11.0-37-generic                | 6         | 0.66%   |
| 5.11.0-27-generic                | 6         | 0.66%   |
| 5.0.0-23-generic                 | 6         | 0.66%   |
| 4.9.20-nrj-desktop-1rosa-x86_64  | 6         | 0.66%   |
| 5.8.0-7642-generic               | 5         | 0.55%   |
| 5.8.0-43-generic                 | 5         | 0.55%   |
| 5.4.0-91-generic                 | 5         | 0.55%   |
| 5.4.0-77-generic                 | 5         | 0.55%   |
| 5.4.0-67-generic                 | 5         | 0.55%   |
| 5.4.0-19-generic                 | 5         | 0.55%   |
| 5.13.0-28-generic                | 5         | 0.55%   |
| 5.0.0-32-generic                 | 5         | 0.55%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 5         | 0.55%   |
| 4.18.0-25-generic                | 5         | 0.55%   |
| 4.15.0-20-generic                | 5         | 0.55%   |
| 5.8.0-40-generic                 | 4         | 0.44%   |
| 5.4.0-81-generic                 | 4         | 0.44%   |
| 5.4.0-74-generic                 | 4         | 0.44%   |
| 5.4.0-73-generic                 | 4         | 0.44%   |
| 5.4.0-72-generic                 | 4         | 0.44%   |
| 5.4.0-47-generic                 | 4         | 0.44%   |
| 5.4.0-37-generic                 | 4         | 0.44%   |
| 5.4.0-28-generic                 | 4         | 0.44%   |
| 5.3.0-53-generic                 | 4         | 0.44%   |
| 5.3.0-51-generic                 | 4         | 0.44%   |
| 5.3.0-45-generic                 | 4         | 0.44%   |
| 5.13.0-30-generic                | 4         | 0.44%   |
| 5.13.0-27-generic                | 4         | 0.44%   |
| 5.13.0-22-generic                | 4         | 0.44%   |
| 5.12.4-desktop-1omv4050          | 4         | 0.44%   |
| 5.11.0-44-generic                | 4         | 0.44%   |
| 5.11.0-41-generic                | 4         | 0.44%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 4         | 0.44%   |
| 4.19.0-8-amd64                   | 4         | 0.44%   |
| 4.15.0-45-generic                | 4         | 0.44%   |
| 4.15.0-29-generic                | 4         | 0.44%   |
| 5.8.11-1-MANJARO                 | 3         | 0.33%   |
| 5.8.0-63-generic                 | 3         | 0.33%   |
| 5.8.0-59-generic                 | 3         | 0.33%   |
| 5.8.0-53-generic                 | 3         | 0.33%   |
| 5.8.0-33-generic                 | 3         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 157       | 18.41%  |
| 4.15.0  | 78        | 9.14%   |
| 5.8.0   | 52        | 6.1%    |
| 5.3.0   | 49        | 5.74%   |
| 5.11.0  | 39        | 4.57%   |
| 5.0.0   | 37        | 4.34%   |
| 5.13.0  | 31        | 3.63%   |
| 5.10.14 | 30        | 3.52%   |
| 4.18.0  | 23        | 2.7%    |
| 5.10.0  | 21        | 2.46%   |
| 5.15.0  | 18        | 2.11%   |
| 5.16.7  | 17        | 1.99%   |
| 4.19.0  | 12        | 1.41%   |
| 5.9.16  | 11        | 1.29%   |
| 4.9.20  | 9         | 1.06%   |
| 5.17.5  | 6         | 0.7%    |
| 4.9.60  | 6         | 0.7%    |
| 4.4.0   | 6         | 0.7%    |
| 5.8.18  | 5         | 0.59%   |
| 4.9.124 | 5         | 0.59%   |
| 5.8.11  | 4         | 0.47%   |
| 5.6.8   | 4         | 0.47%   |
| 5.6.0   | 4         | 0.47%   |
| 5.16.0  | 4         | 0.47%   |
| 5.12.4  | 4         | 0.47%   |
| 5.11.12 | 4         | 0.47%   |
| 5.7.6   | 3         | 0.35%   |
| 5.3.16  | 3         | 0.35%   |
| 5.17.9  | 3         | 0.35%   |
| 5.17.6  | 3         | 0.35%   |
| 5.17.11 | 3         | 0.35%   |
| 5.16.15 | 3         | 0.35%   |
| 5.16.11 | 3         | 0.35%   |
| 5.15.8  | 3         | 0.35%   |
| 5.12.14 | 3         | 0.35%   |
| 5.10.74 | 3         | 0.35%   |
| 4.9.76  | 3         | 0.35%   |
| 4.9.155 | 3         | 0.35%   |
| 4.1.38  | 3         | 0.35%   |
| 3.10.0  | 3         | 0.35%   |
| 5.9.10  | 2         | 0.23%   |
| 5.8.14  | 2         | 0.23%   |
| 5.7.7   | 2         | 0.23%   |
| 5.7.19  | 2         | 0.23%   |
| 5.5.13  | 2         | 0.23%   |
| 5.4.83  | 2         | 0.23%   |
| 5.4.80  | 2         | 0.23%   |
| 5.4.32  | 2         | 0.23%   |
| 5.4.18  | 2         | 0.23%   |
| 5.3.14  | 2         | 0.23%   |
| 5.3.12  | 2         | 0.23%   |
| 5.18.11 | 2         | 0.23%   |
| 5.18.10 | 2         | 0.23%   |
| 5.17.4  | 2         | 0.23%   |
| 5.15.7  | 2         | 0.23%   |
| 5.15.6  | 2         | 0.23%   |
| 5.15.5  | 2         | 0.23%   |
| 5.14.0  | 2         | 0.23%   |
| 5.13.8  | 2         | 0.23%   |
| 5.13.6  | 2         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 167       | 20.12%  |
| 4.15    | 78        | 9.4%    |
| 5.10    | 74        | 8.92%   |
| 5.8     | 65        | 7.83%   |
| 5.3     | 58        | 6.99%   |
| 5.11    | 50        | 6.02%   |
| 5.0     | 40        | 4.82%   |
| 5.15    | 38        | 4.58%   |
| 5.13    | 37        | 4.46%   |
| 5.16    | 35        | 4.22%   |
| 4.9     | 26        | 3.13%   |
| 4.18    | 24        | 2.89%   |
| 5.17    | 19        | 2.29%   |
| 5.9     | 17        | 2.05%   |
| 4.19    | 17        | 2.05%   |
| 5.6     | 16        | 1.93%   |
| 5.7     | 11        | 1.33%   |
| 5.12    | 11        | 1.33%   |
| 5.14    | 8         | 0.96%   |
| 5.5     | 7         | 0.84%   |
| 4.4     | 6         | 0.72%   |
| 5.2     | 5         | 0.6%    |
| 5.18    | 5         | 0.6%    |
| 4.1     | 4         | 0.48%   |
| 5.1     | 3         | 0.36%   |
| 3.10    | 3         | 0.36%   |
| 4.7     | 1         | 0.12%   |
| 4.20    | 1         | 0.12%   |
| 4.13    | 1         | 0.12%   |
| 4.10    | 1         | 0.12%   |
| 3.13    | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 694       | 96.39%  |
| i686   | 26        | 3.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 276       | 35.66%  |
| Unknown          | 121       | 15.63%  |
| KDE5             | 119       | 15.37%  |
| XFCE             | 70        | 9.04%   |
| X-Cinnamon       | 49        | 6.33%   |
| KDE4             | 33        | 4.26%   |
| KDE              | 28        | 3.62%   |
| MATE             | 19        | 2.45%   |
| Cinnamon         | 13        | 1.68%   |
| Unity            | 10        | 1.29%   |
| LXQt             | 7         | 0.9%    |
| Pantheon         | 5         | 0.65%   |
| GNOME Flashback  | 5         | 0.65%   |
| Budgie           | 3         | 0.39%   |
| bspwm            | 3         | 0.39%   |
| xmonad           | 2         | 0.26%   |
| lightdm-xsession | 2         | 0.26%   |
| i3               | 2         | 0.26%   |
| Deepin           | 2         | 0.26%   |
| qtile            | 1         | 0.13%   |
| LXDE             | 1         | 0.13%   |
| GNOME Classic    | 1         | 0.13%   |
| DWM              | 1         | 0.13%   |
| awesome          | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 620       | 83.22%  |
| Unknown | 63        | 8.46%   |
| Wayland | 54        | 7.25%   |
| Tty     | 8         | 1.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 422       | 56.12%  |
| SDDM    | 119       | 15.82%  |
| GDM     | 60        | 7.98%   |
| LightDM | 55        | 7.31%   |
| TDM     | 32        | 4.26%   |
| KDM     | 32        | 4.26%   |
| GDM3    | 30        | 3.99%   |
| XDM     | 1         | 0.13%   |
| MDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 429       | 57.05%  |
| Unknown | 143       | 19.02%  |
| bg_BG   | 135       | 17.95%  |
| en_GB   | 18        | 2.39%   |
| C       | 12        | 1.6%    |
| ru_RU   | 5         | 0.66%   |
| de_DE   | 5         | 0.66%   |
| POSIX   | 1         | 0.13%   |
| it_IT   | 1         | 0.13%   |
| fr_FR   | 1         | 0.13%   |
| en_DK   | 1         | 0.13%   |
| C.UTF8  | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 439       | 59.32%  |
| EFI  | 301       | 40.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 566       | 75.97%  |
| Overlay | 58        | 7.79%   |
| Unknown | 56        | 7.52%   |
| Btrfs   | 35        | 4.7%    |
| Xfs     | 14        | 1.88%   |
| Zfs     | 6         | 0.81%   |
| Ext3    | 3         | 0.4%    |
| Ext2    | 3         | 0.4%    |
| Tmpfs   | 2         | 0.27%   |
| Jfs     | 1         | 0.13%   |
| F2fs    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 445       | 60.14%  |
| GPT     | 189       | 25.54%  |
| MBR     | 106       | 14.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 623       | 84.53%  |
| Yes       | 114       | 15.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 510       | 69.67%  |
| Yes       | 222       | 30.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 134       | 18.66%  |
| ASUSTek Computer    | 128       | 17.83%  |
| Hewlett-Packard     | 99        | 13.79%  |
| Dell                | 85        | 11.84%  |
| ASRock              | 55        | 7.66%   |
| Acer                | 48        | 6.69%   |
| Gigabyte Technology | 42        | 5.85%   |
| Toshiba             | 26        | 3.62%   |
| MSI                 | 23        | 3.2%    |
| Fujitsu             | 14        | 1.95%   |
| Intel               | 7         | 0.97%   |
| Apple               | 7         | 0.97%   |
| Fujitsu Siemens     | 6         | 0.84%   |
| Foxconn             | 4         | 0.56%   |
| AMI                 | 4         | 0.56%   |
| Unknown             | 4         | 0.56%   |
| Samsung Electronics | 3         | 0.42%   |
| Pegatron            | 3         | 0.42%   |
| Packard Bell        | 3         | 0.42%   |
| Wibtek              | 2         | 0.28%   |
| TUXEDO              | 2         | 0.28%   |
| Sony                | 2         | 0.28%   |
| Medion              | 2         | 0.28%   |
| HUAWEI              | 2         | 0.28%   |
| Thecus              | 1         | 0.14%   |
| Supermicro          | 1         | 0.14%   |
| Shuttle             | 1         | 0.14%   |
| Seco                | 1         | 0.14%   |
| Razer               | 1         | 0.14%   |
| Notebook            | 1         | 0.14%   |
| MiTAC               | 1         | 0.14%   |
| LG Electronics      | 1         | 0.14%   |
| iEi                 | 1         | 0.14%   |
| IBM                 | 1         | 0.14%   |
| ECS                 | 1         | 0.14%   |
| Cube                | 1         | 0.14%   |
| Compal              | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 0.97%   |
| ASUS All Series                            | 5         | 0.7%    |
| Lenovo H520S 2561                          | 4         | 0.56%   |
| Lenovo G500 20236                          | 4         | 0.56%   |
| HP ProBook 4540s                           | 4         | 0.56%   |
| HP ProBook 450 G0                          | 3         | 0.42%   |
| Dell Latitude E6410                        | 3         | 0.42%   |
| Dell Inspiron N5110                        | 3         | 0.42%   |
| ASUS X541NA                                | 3         | 0.42%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.42%   |
| ASUS N551VW                                | 3         | 0.42%   |
| ASRock Z97 Anniversary                     | 3         | 0.42%   |
| Acer Aspire 5738                           | 3         | 0.42%   |
| Wibtek H61-M HDMI2                         | 2         | 0.28%   |
| Toshiba Satellite L300                     | 2         | 0.28%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.28%   |
| Toshiba Satellite A200                     | 2         | 0.28%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.28%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.28%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.28%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.28%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.28%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.28%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.28%   |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.28%   |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.28%   |
| Lenovo ThinkBook 13s-IML 20RR              | 2         | 0.28%   |
| Lenovo Legion Y740-17IRHg 81UJ             | 2         | 0.28%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.28%   |
| Lenovo IdeaPad Y510P 20217                 | 2         | 0.28%   |
| Lenovo IdeaPad Y500 20193                  | 2         | 0.28%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.28%   |
| Lenovo H520e 10159                         | 2         | 0.28%   |
| Lenovo G50-80 80E5                         | 2         | 0.28%   |
| HP ProBook 6470b                           | 2         | 0.28%   |
| HP ProBook 455 G8 Notebook PC              | 2         | 0.28%   |
| HP ProBook 450 G8 Notebook PC              | 2         | 0.28%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.28%   |
| HP Pavilion dv5                            | 2         | 0.28%   |
| HP Pavilion 15                             | 2         | 0.28%   |
| HP Notebook                                | 2         | 0.28%   |
| HP EliteBook 8560p                         | 2         | 0.28%   |
| HP EliteBook 8460p                         | 2         | 0.28%   |
| HP EliteBook 840 G1                        | 2         | 0.28%   |
| HP EliteBook 820 G2                        | 2         | 0.28%   |
| Gigabyte X99-UD4-CF                        | 2         | 0.28%   |
| Gigabyte H370AORUSGAMING3WIFI              | 2         | 0.28%   |
| Gigabyte B450 AORUS M                      | 2         | 0.28%   |
| Fujitsu ESPRIMO P710                       | 2         | 0.28%   |
| Dell Vostro 3580                           | 2         | 0.28%   |
| Dell Studio 1747                           | 2         | 0.28%   |
| Dell Precision Tower 5810                  | 2         | 0.28%   |
| Dell Precision M4600                       | 2         | 0.28%   |
| Dell OptiPlex 780                          | 2         | 0.28%   |
| Dell Latitude E6430                        | 2         | 0.28%   |
| Dell Latitude E6330                        | 2         | 0.28%   |
| Dell Latitude E5430 non-vPro               | 2         | 0.28%   |
| Dell Latitude E4300                        | 2         | 0.28%   |
| Dell Inspiron N5010                        | 2         | 0.28%   |
| Dell Inspiron 7577                         | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 62        | 8.64%   |
| Acer Aspire                   | 33        | 4.6%    |
| Dell Latitude                 | 26        | 3.62%   |
| Dell Inspiron                 | 25        | 3.48%   |
| Lenovo IdeaPad                | 23        | 3.2%    |
| Toshiba Satellite             | 21        | 2.92%   |
| HP ProBook                    | 21        | 2.92%   |
| HP Compaq                     | 19        | 2.65%   |
| HP EliteBook                  | 18        | 2.51%   |
| HP Pavilion                   | 17        | 2.37%   |
| ASUS VivoBook                 | 15        | 2.09%   |
| ASUS PRIME                    | 9         | 1.25%   |
| Fujitsu ESPRIMO               | 8         | 1.11%   |
| Dell OptiPlex                 | 8         | 1.11%   |
| Lenovo ThinkCentre            | 7         | 0.97%   |
| Dell Precision                | 7         | 0.97%   |
| ASUS ROG                      | 7         | 0.97%   |
| Unknown                       | 7         | 0.97%   |
| Lenovo Legion                 | 6         | 0.84%   |
| Dell Vostro                   | 6         | 0.84%   |
| Lenovo Yoga                   | 5         | 0.7%    |
| Dell XPS                      | 5         | 0.7%    |
| ASUS All                      | 5         | 0.7%    |
| Lenovo H520S                  | 4         | 0.56%   |
| Lenovo G500                   | 4         | 0.56%   |
| HP 250                        | 4         | 0.56%   |
| ASUS TUF                      | 4         | 0.56%   |
| ASUS P5K                      | 4         | 0.56%   |
| MSI Modern                    | 3         | 0.42%   |
| MSI GF63                      | 3         | 0.42%   |
| Lenovo ThinkBook              | 3         | 0.42%   |
| HP Laptop                     | 3         | 0.42%   |
| Gigabyte X570                 | 3         | 0.42%   |
| Fujitsu Siemens AMILO         | 3         | 0.42%   |
| Fujitsu LIFEBOOK              | 3         | 0.42%   |
| Dell Studio                   | 3         | 0.42%   |
| ASUS X541NA                   | 3         | 0.42%   |
| ASUS N551VW                   | 3         | 0.42%   |
| ASRock Z97                    | 3         | 0.42%   |
| ASRock X570                   | 3         | 0.42%   |
| Acer TravelMate               | 3         | 0.42%   |
| Acer Predator                 | 3         | 0.42%   |
| Acer Nitro                    | 3         | 0.42%   |
| Wibtek H61-M                  | 2         | 0.28%   |
| Toshiba PORTEGE               | 2         | 0.28%   |
| Samsung 300E4Z                | 2         | 0.28%   |
| Lenovo Y520-15IKBN            | 2         | 0.28%   |
| Lenovo ThinkStation           | 2         | 0.28%   |
| Lenovo H520e                  | 2         | 0.28%   |
| Lenovo G50-80                 | 2         | 0.28%   |
| Intel X99                     | 2         | 0.28%   |
| HP Notebook                   | 2         | 0.28%   |
| HP 255                        | 2         | 0.28%   |
| Gigabyte Z490                 | 2         | 0.28%   |
| Gigabyte X99-UD4-CF           | 2         | 0.28%   |
| Gigabyte H370AORUSGAMING3WIFI | 2         | 0.28%   |
| Gigabyte B450                 | 2         | 0.28%   |
| Fujitsu Siemens ESPRIMO       | 2         | 0.28%   |
| Fujitsu CELSIUS               | 2         | 0.28%   |
| Dell G7                       | 2         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 67        | 9.33%   |
| 2019 | 65        | 9.05%   |
| 2012 | 65        | 9.05%   |
| 2013 | 60        | 8.36%   |
| 2017 | 59        | 8.22%   |
| 2018 | 55        | 7.66%   |
| 2015 | 49        | 6.82%   |
| 2020 | 48        | 6.69%   |
| 2014 | 47        | 6.55%   |
| 2010 | 43        | 5.99%   |
| 2008 | 40        | 5.57%   |
| 2009 | 30        | 4.18%   |
| 2007 | 27        | 3.76%   |
| 2021 | 22        | 3.06%   |
| 2016 | 22        | 3.06%   |
| 2006 | 13        | 1.81%   |
| 2005 | 3         | 0.42%   |
| 2004 | 2         | 0.28%   |
| 2022 | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 435       | 60.58%  |
| Desktop     | 265       | 36.91%  |
| Mini pc     | 7         | 0.97%   |
| Convertible | 6         | 0.84%   |
| All in one  | 4         | 0.56%   |
| Tablet      | 1         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 685       | 95.01%  |
| Enabled  | 36        | 4.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 717       | 99.86%  |
| Yes  | 1         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 191       | 25.78%  |
| 3.01-4.0    | 166       | 22.4%   |
| 8.01-16.0   | 143       | 19.3%   |
| 16.01-24.0  | 111       | 14.98%  |
| 32.01-64.0  | 53        | 7.15%   |
| 1.01-2.0    | 31        | 4.18%   |
| 2.01-3.0    | 20        | 2.7%    |
| 24.01-32.0  | 14        | 1.89%   |
| 64.01-256.0 | 9         | 1.21%   |
| 0.51-1.0    | 3         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 296       | 35.79%  |
| 2.01-3.0   | 217       | 26.24%  |
| 4.01-8.0   | 108       | 13.06%  |
| 3.01-4.0   | 103       | 12.45%  |
| 0.51-1.0   | 69        | 8.34%   |
| 8.01-16.0  | 25        | 3.02%   |
| 0.01-0.5   | 5         | 0.6%    |
| 16.01-24.0 | 2         | 0.24%   |
| 24.01-32.0 | 1         | 0.12%   |
| Unknown    | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 457       | 61.67%  |
| 2      | 199       | 26.86%  |
| 3      | 44        | 5.94%   |
| 4      | 14        | 1.89%   |
| 5      | 12        | 1.62%   |
| 6      | 5         | 0.67%   |
| 0      | 5         | 0.67%   |
| 7      | 2         | 0.27%   |
| 11     | 1         | 0.13%   |
| 9      | 1         | 0.13%   |
| 8      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 399       | 54.51%  |
| Yes       | 333       | 45.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 656       | 91.11%  |
| No        | 64        | 8.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 514       | 71.29%  |
| No        | 207       | 28.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 396       | 54.17%  |
| No        | 335       | 45.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Bulgaria | 718       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Sofia               | 377       | 50.4%   |
| Varna               | 61        | 8.16%   |
| Plovdiv             | 46        | 6.15%   |
| Burgas              | 29        | 3.88%   |
| Stara Zagora        | 20        | 2.67%   |
| Rousse              | 14        | 1.87%   |
| Pernik              | 13        | 1.74%   |
| Veliko Tarnovo      | 10        | 1.34%   |
| Pleven              | 10        | 1.34%   |
| Yambol              | 9         | 1.2%    |
| Haskovo             | 9         | 1.2%    |
| Sliven              | 8         | 1.07%   |
| Kazanlak            | 8         | 1.07%   |
| Shumen              | 7         | 0.94%   |
| Dobrich             | 6         | 0.8%    |
| Asenovgrad          | 6         | 0.8%    |
| Razgrad             | 4         | 0.53%   |
| Pazardzhik          | 4         | 0.53%   |
| Montana             | 4         | 0.53%   |
| Gabrovo             | 4         | 0.53%   |
| Vidin               | 3         | 0.4%    |
| Svoge               | 3         | 0.4%    |
| Svilengrad          | 3         | 0.4%    |
| Sistov              | 3         | 0.4%    |
| Kyustendil          | 3         | 0.4%    |
| Blagoevgrad         | 3         | 0.4%    |
| Vratsa              | 2         | 0.27%   |
| Targovishte         | 2         | 0.27%   |
| Smolyan             | 2         | 0.27%   |
| Slashten            | 2         | 0.27%   |
| Silistra            | 2         | 0.27%   |
| Sevlievo            | 2         | 0.27%   |
| Omurtag             | 2         | 0.27%   |
| Novi Pazar          | 2         | 0.27%   |
| Novi Iskar          | 2         | 0.27%   |
| Nane                | 2         | 0.27%   |
| Mezdra              | 2         | 0.27%   |
| Krumovgrad          | 2         | 0.27%   |
| Karlovo             | 2         | 0.27%   |
| Gorna Oryahovitsa   | 2         | 0.27%   |
| Dimitrovgrad        | 2         | 0.27%   |
| Cherven             | 2         | 0.27%   |
| Bozhurishte         | 2         | 0.27%   |
| Zlatitsa            | 1         | 0.13%   |
| Voluyak             | 1         | 0.13%   |
| Velingrad           | 1         | 0.13%   |
| Tvarditsa           | 1         | 0.13%   |
| Troyan Municipality | 1         | 0.13%   |
| Toros               | 1         | 0.13%   |
| Slatina             | 1         | 0.13%   |
| Skutare             | 1         | 0.13%   |
| Septemvri           | 1         | 0.13%   |
| Sarafovo            | 1         | 0.13%   |
| Sandanski           | 1         | 0.13%   |
| Ruen                | 1         | 0.13%   |
| Rogozen             | 1         | 0.13%   |
| Rakovski            | 1         | 0.13%   |
| Primorsko           | 1         | 0.13%   |
| Popovo              | 1         | 0.13%   |
| Petrich             | 1         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 163       | 236    | 15.96%  |
| WDC                       | 153       | 229    | 14.99%  |
| Samsung Electronics       | 142       | 212    | 13.91%  |
| Toshiba                   | 92        | 125    | 9.01%   |
| Hitachi                   | 62        | 85     | 6.07%   |
| Kingston                  | 60        | 87     | 5.88%   |
| SanDisk                   | 41        | 52     | 4.02%   |
| A-DATA Technology         | 36        | 51     | 3.53%   |
| Intel                     | 34        | 49     | 3.33%   |
| HGST                      | 31        | 47     | 3.04%   |
| Unknown                   | 26        | 35     | 2.55%   |
| Crucial                   | 16        | 24     | 1.57%   |
| Team                      | 15        | 16     | 1.47%   |
| SK hynix                  | 15        | 18     | 1.47%   |
| SPCC                      | 11        | 13     | 1.08%   |
| China                     | 11        | 12     | 1.08%   |
| Transcend                 | 7         | 8      | 0.69%   |
| Phison                    | 7         | 7      | 0.69%   |
| Patriot                   | 7         | 8      | 0.69%   |
| Micron Technology         | 7         | 7      | 0.69%   |
| KingSpec                  | 7         | 8      | 0.69%   |
| KIOXIA                    | 6         | 7      | 0.59%   |
| Fujitsu                   | 6         | 9      | 0.59%   |
| Realtek Semiconductor     | 5         | 7      | 0.49%   |
| Maxtor                    | 5         | 9      | 0.49%   |
| LITEON                    | 4         | 5      | 0.39%   |
| Apple                     | 4         | 6      | 0.39%   |
| XPG                       | 3         | 5      | 0.29%   |
| TO Exter                  | 3         | 3      | 0.29%   |
| Silicon Motion            | 3         | 6      | 0.29%   |
| LITEONIT                  | 3         | 3      | 0.29%   |
| Union Memory (Shenzhen)   | 2         | 5      | 0.2%    |
| Teclast                   | 2         | 2      | 0.2%    |
| PNY                       | 2         | 2      | 0.2%    |
| OCZ                       | 2         | 2      | 0.2%    |
| JMicron Technology        | 2         | 3      | 0.2%    |
| Intenso                   | 2         | 2      | 0.2%    |
| Hewlett-Packard           | 2         | 1      | 0.2%    |
| ExcelStor                 | 2         | 6      | 0.2%    |
| AMD                       | 2         | 4      | 0.2%    |
| Realtek                   | 1         | 1      | 0.1%    |
| OCZ-VERTEX3               | 1         | 1      | 0.1%    |
| Netac                     | 1         | 3      | 0.1%    |
| Micron/Crucial Technology | 1         | 1      | 0.1%    |
| Mass                      | 1         | 1      | 0.1%    |
| Lenovo                    | 1         | 1      | 0.1%    |
| KingFast                  | 1         | 1      | 0.1%    |
| Innodisk                  | 1         | 1      | 0.1%    |
| IBM/Hitachi               | 1         | 2      | 0.1%    |
| HGST HTS                  | 1         | 1      | 0.1%    |
| Goodram                   | 1         | 1      | 0.1%    |
| Gigabyte Technology       | 1         | 8      | 0.1%    |
| FORESEE                   | 1         | 1      | 0.1%    |
| EDGE                      | 1         | 1      | 0.1%    |
| Corsair                   | 1         | 1      | 0.1%    |
| ATP                       | 1         | 2      | 0.1%    |
| ASMedia                   | 1         | 1      | 0.1%    |
| Unknown                   | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 16        | 1.44%   |
| Seagate ST500DM002-1BD142 500GB    | 15        | 1.35%   |
| Kingston SA400S37120G 120GB SSD    | 14        | 1.26%   |
| Toshiba MQ01ABF050 500GB           | 13        | 1.17%   |
| Toshiba MQ01ABD100 1TB             | 13        | 1.17%   |
| Samsung SSD 860 EVO 250GB          | 13        | 1.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 0.99%   |
| HGST HTS721010A9E630 1TB           | 11        | 0.99%   |
| Samsung SSD 850 EVO 250GB          | 10        | 0.9%    |
| Samsung NVMe SSD Drive 512GB       | 10        | 0.9%    |
| SanDisk NVMe SSD Drive 512GB       | 8         | 0.72%   |
| Samsung SSD 860 EVO 500GB          | 8         | 0.72%   |
| Kingston SA400S37480G 480GB SSD    | 8         | 0.72%   |
| Kingston SA400S37240G 240GB SSD    | 8         | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 7         | 0.63%   |
| Toshiba DT01ACA100 1TB             | 7         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB     | 7         | 0.63%   |
| Samsung NVMe SSD Drive 500GB       | 7         | 0.63%   |
| HGST HTS541010A9E680 1TB           | 7         | 0.63%   |
| WDC WD10SPZX-21Z10T0 1TB           | 6         | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB     | 6         | 0.54%   |
| Samsung SSD 970 EVO 250GB          | 6         | 0.54%   |
| Samsung SSD 850 PRO 256GB          | 6         | 0.54%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 0.54%   |
| A-DATA SU650 240GB SSD             | 6         | 0.54%   |
| Unknown MMC Card  64GB             | 5         | 0.45%   |
| Unknown MMC Card  32GB             | 5         | 0.45%   |
| Toshiba DT01ACA050 500GB           | 5         | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB     | 5         | 0.45%   |
| Samsung SSD 860 EVO 1TB            | 5         | 0.45%   |
| Samsung SSD 850 EVO 500GB          | 5         | 0.45%   |
| Samsung NVMe SSD Drive 1024GB      | 5         | 0.45%   |
| Intel SSDSC2CW120A3 120GB          | 5         | 0.45%   |
| Intel NVMe SSD Drive 512GB         | 5         | 0.45%   |
| Hitachi HTS547575A9E384 752GB      | 5         | 0.45%   |
| Hitachi HDP725050GLA360 500GB      | 5         | 0.45%   |
| HGST HTS545050A7E680 500GB         | 5         | 0.45%   |
| A-DATA SU650 120GB SSD             | 5         | 0.45%   |
| Toshiba NVMe SSD Drive 256GB       | 4         | 0.36%   |
| Toshiba DT01ACA200 2TB             | 4         | 0.36%   |
| SPCC Solid State Disk 512GB        | 4         | 0.36%   |
| Seagate ST9750420AS 752GB          | 4         | 0.36%   |
| Seagate ST9500325AS 500GB          | 4         | 0.36%   |
| SanDisk NVMe SSD Drive 256GB       | 4         | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB     | 4         | 0.36%   |
| Samsung NVMe SSD Drive 250GB       | 4         | 0.36%   |
| Hitachi HDS721616PLA380 160GB      | 4         | 0.36%   |
| Hitachi HDS721050CLA362 500GB      | 4         | 0.36%   |
| XPG NVMe SSD Drive 512GB           | 3         | 0.27%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 3         | 0.27%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 3         | 0.27%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 3         | 0.27%   |
| WDC WD2002FAEX-007BA0 2TB          | 3         | 0.27%   |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 0.27%   |
| WDC WD10EZEX-22BN5A0 1TB           | 3         | 0.27%   |
| WDC WD10EZEX-00WN4A0 1TB           | 3         | 0.27%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 3         | 0.27%   |
| Toshiba MQ04ABF100 1TB             | 3         | 0.27%   |
| Toshiba MQ01ABD075 752GB           | 3         | 0.27%   |
| Toshiba HDWD110 1TB                | 3         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 162       | 235    | 33.06%  |
| WDC                 | 134       | 197    | 27.35%  |
| Toshiba             | 75        | 101    | 15.31%  |
| Hitachi             | 62        | 85     | 12.65%  |
| HGST                | 31        | 47     | 6.33%   |
| Samsung Electronics | 7         | 10     | 1.43%   |
| Fujitsu             | 6         | 9      | 1.22%   |
| Maxtor              | 5         | 9      | 1.02%   |
| ExcelStor           | 2         | 6      | 0.41%   |
| Unknown             | 1         | 2      | 0.2%    |
| IBM/Hitachi         | 1         | 2      | 0.2%    |
| HGST HTS            | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 82        | 102    | 24.7%   |
| Kingston            | 49        | 67     | 14.76%  |
| A-DATA Technology   | 30        | 43     | 9.04%   |
| SanDisk             | 25        | 30     | 7.53%   |
| WDC                 | 16        | 24     | 4.82%   |
| Intel               | 16        | 22     | 4.82%   |
| Team                | 15        | 16     | 4.52%   |
| Crucial             | 15        | 23     | 4.52%   |
| China               | 11        | 12     | 3.31%   |
| SPCC                | 10        | 12     | 3.01%   |
| Transcend           | 7         | 8      | 2.11%   |
| Patriot             | 7         | 8      | 2.11%   |
| KingSpec            | 6         | 7      | 1.81%   |
| Toshiba             | 5         | 5      | 1.51%   |
| Micron Technology   | 4         | 4      | 1.2%    |
| LITEON              | 4         | 5      | 1.2%    |
| TO Exter            | 3         | 3      | 0.9%    |
| LITEONIT            | 3         | 3      | 0.9%    |
| Apple               | 3         | 5      | 0.9%    |
| Teclast             | 2         | 2      | 0.6%    |
| PNY                 | 2         | 2      | 0.6%    |
| OCZ                 | 2         | 2      | 0.6%    |
| Intenso             | 2         | 2      | 0.6%    |
| AMD                 | 2         | 4      | 0.6%    |
| Unknown             | 1         | 1      | 0.3%    |
| SK hynix            | 1         | 1      | 0.3%    |
| OCZ-VERTEX3         | 1         | 1      | 0.3%    |
| Netac               | 1         | 3      | 0.3%    |
| JMicron Technology  | 1         | 2      | 0.3%    |
| Goodram             | 1         | 1      | 0.3%    |
| Gigabyte Technology | 1         | 8      | 0.3%    |
| FORESEE             | 1         | 1      | 0.3%    |
| EDGE                | 1         | 1      | 0.3%    |
| Corsair             | 1         | 1      | 0.3%    |
| ATP                 | 1         | 2      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 432       | 707    | 46.3%   |
| SSD     | 299       | 433    | 32.05%  |
| NVMe    | 172       | 269    | 18.44%  |
| MMC     | 22        | 27     | 2.36%   |
| Unknown | 8         | 9      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 599       | 1124   | 73.59%  |
| NVMe | 170       | 267    | 20.88%  |
| SAS  | 23        | 27     | 2.83%   |
| MMC  | 22        | 27     | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 457       | 705    | 61.84%  |
| 0.51-1.0   | 223       | 338    | 30.18%  |
| 1.01-2.0   | 30        | 43     | 4.06%   |
| 3.01-4.0   | 12        | 28     | 1.62%   |
| 2.01-3.0   | 10        | 17     | 1.35%   |
| 4.01-10.0  | 4         | 6      | 0.54%   |
| 10.01-20.0 | 3         | 3      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 204       | 26.53%  |
| 251-500        | 164       | 21.33%  |
| 501-1000       | 123       | 15.99%  |
| 1001-2000      | 71        | 9.23%   |
| 1-20           | 66        | 8.58%   |
| 51-100         | 52        | 6.76%   |
| 21-50          | 35        | 4.55%   |
| More than 3000 | 24        | 3.12%   |
| Unknown        | 19        | 2.47%   |
| 2001-3000      | 11        | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 326       | 39.61%  |
| 21-50          | 135       | 16.4%   |
| 101-250        | 108       | 13.12%  |
| 51-100         | 96        | 11.66%  |
| 251-500        | 51        | 6.2%    |
| 501-1000       | 47        | 5.71%   |
| 1001-2000      | 25        | 3.04%   |
| Unknown        | 19        | 2.31%   |
| More than 3000 | 8         | 0.97%   |
| 2001-3000      | 8         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 3         | 3      | 3.7%    |
| WDC WD6000HLHX-01JJPV0 600GB          | 2         | 3      | 2.47%   |
| WDC WD5000AAKX-603CA0 500GB           | 2         | 6      | 2.47%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 2.47%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 2.47%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 2.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 2.47%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 2.47%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 1      | 1.23%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1         | 1      | 1.23%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 1.23%   |
| WDC WD5000AACS-00G8B1 500GB           | 1         | 1      | 1.23%   |
| WDC WD3200BEVT-80A0RT0 320GB          | 1         | 1      | 1.23%   |
| WDC WD3200AAJS-07M0A0 320GB           | 1         | 2      | 1.23%   |
| WDC WD2500JS-00MHB0 250GB             | 1         | 1      | 1.23%   |
| WDC WD1600BEVT-80A23T0 160GB          | 1         | 1      | 1.23%   |
| WDC WD15EARS-00S8B1 1TB               | 1         | 1      | 1.23%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 1.23%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.23%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 1.23%   |
| Toshiba MK2552GSX 250GB               | 1         | 3      | 1.23%   |
| Toshiba MK1637GSX 160GB               | 1         | 1      | 1.23%   |
| Toshiba DT01ACA300 3TB                | 1         | 1      | 1.23%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.23%   |
| Seagate ST9500420AS 500GB             | 1         | 2      | 1.23%   |
| Seagate ST94019A 40GB                 | 1         | 1      | 1.23%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.23%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.23%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 1      | 1.23%   |
| Seagate ST380215A 80GB                | 1         | 1      | 1.23%   |
| Seagate ST3500830AS 500GB             | 1         | 1      | 1.23%   |
| Seagate ST3320311CS 320GB             | 1         | 1      | 1.23%   |
| Seagate ST31000333AS 1TB              | 1         | 1      | 1.23%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 1      | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.23%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.23%   |
| SanDisk SDSSDX480GG25 480GB           | 1         | 1      | 1.23%   |
| Samsung Electronics SSD 970 EVO 250GB | 1         | 1      | 1.23%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 1.23%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 1.23%   |
| Patriot P200 512GB SSD                | 1         | 1      | 1.23%   |
| Maxtor 6Y160M0 160GB                  | 1         | 1      | 1.23%   |
| Maxtor 6L080P0 81GB                   | 1         | 1      | 1.23%   |
| Maxtor 2F040L0 41GB                   | 1         | 1      | 1.23%   |
| Kingston SV300S37A60G 64GB SSD        | 1         | 1      | 1.23%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 1.23%   |
| Kingston SUV500240G 240GB SSD         | 1         | 1      | 1.23%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 1.23%   |
| KingSpec P3-256 256GB                 | 1         | 1      | 1.23%   |
| KingSpec P3-128 128GB SSD             | 1         | 1      | 1.23%   |
| Intel SSDSC2BW480A4 480GB             | 1         | 2      | 1.23%   |
| Intel SSDSC2BW120A3F 120GB            | 1         | 1      | 1.23%   |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 1.23%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 1.23%   |
| Hitachi HTS543225L9SA00 250GB         | 1         | 2      | 1.23%   |
| Hitachi HTS543225L9A300 250GB         | 1         | 1      | 1.23%   |
| Hitachi HTS541616J9SA00 160GB         | 1         | 1      | 1.23%   |
| Hitachi HDT722525DLA380 250GB         | 1         | 1      | 1.23%   |
| Hitachi HDT721010SLA360 1TB           | 1         | 1      | 1.23%   |
| Hitachi HDS721010CLA330 1TB           | 1         | 1      | 1.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 25.93%  |
| WDC                 | 14        | 21     | 17.28%  |
| Hitachi             | 9         | 10     | 11.11%  |
| Toshiba             | 8         | 10     | 9.88%   |
| A-DATA Technology   | 6         | 6      | 7.41%   |
| Kingston            | 4         | 4      | 4.94%   |
| Intel               | 4         | 5      | 4.94%   |
| Samsung Electronics | 3         | 4      | 3.7%    |
| Maxtor              | 3         | 3      | 3.7%    |
| KingSpec            | 2         | 2      | 2.47%   |
| ExcelStor           | 2         | 3      | 2.47%   |
| SanDisk             | 1         | 1      | 1.23%   |
| Patriot             | 1         | 1      | 1.23%   |
| HGST                | 1         | 1      | 1.23%   |
| Fujitsu             | 1         | 2      | 1.23%   |
| China               | 1         | 1      | 1.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 21        | 22     | 36.21%  |
| WDC       | 13        | 20     | 22.41%  |
| Hitachi   | 9         | 10     | 15.52%  |
| Toshiba   | 8         | 10     | 13.79%  |
| Maxtor    | 3         | 3      | 5.17%   |
| ExcelStor | 2         | 3      | 3.45%   |
| HGST      | 1         | 1      | 1.72%   |
| Fujitsu   | 1         | 2      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 71     | 71.43%  |
| SSD  | 20        | 22     | 25.97%  |
| NVMe | 2         | 3      | 2.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 50%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 461       | 901    | 58.43%  |
| Works    | 254       | 446    | 32.19%  |
| Malfunc  | 72        | 96     | 9.13%   |
| Failed   | 2         | 2      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 536       | 61.26%  |
| AMD                              | 116       | 13.26%  |
| Samsung Electronics              | 71        | 8.11%   |
| SanDisk                          | 22        | 2.51%   |
| JMicron Technology               | 17        | 1.94%   |
| Nvidia                           | 16        | 1.83%   |
| SK hynix                         | 14        | 1.6%    |
| Kingston Technology Company      | 11        | 1.26%   |
| Toshiba America Info Systems     | 10        | 1.14%   |
| Realtek Semiconductor            | 9         | 1.03%   |
| KIOXIA                           | 9         | 1.03%   |
| Phison Electronics               | 8         | 0.91%   |
| Marvell Technology Group         | 8         | 0.91%   |
| ASMedia Technology               | 7         | 0.8%    |
| ADATA Technology                 | 7         | 0.8%    |
| Silicon Motion                   | 3         | 0.34%   |
| Micron Technology                | 3         | 0.34%   |
| Union Memory (Shenzhen)          | 2         | 0.23%   |
| Micron/Crucial Technology        | 2         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| Lenovo                           | 1         | 0.11%   |
| Integrated Technology Express    | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 72        | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 50        | 4.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 45        | 4.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 33        | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32        | 3.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 30        | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 28        | 2.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 24        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23        | 2.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 18        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 16        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16        | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 14        | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13        | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 12        | 1.16%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 1.07%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 11        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10        | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10        | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 0.97%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 0.87%   |
| Intel SSD 660P Series                                                                   | 9         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 9         | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 0.78%   |
| Nvidia MCP61 SATA Controller                                                            | 8         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 8         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 0.78%   |
| Realtek Realtek Non-Volatile memory controller                                          | 7         | 0.68%   |
| Nvidia MCP61 IDE                                                                        | 7         | 0.68%   |
| JMicron JMB368 IDE controller                                                           | 7         | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7         | 0.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 0.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 0.68%   |
| AMD FCH IDE Controller                                                                  | 7         | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7         | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6         | 0.58%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 6         | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 6         | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6         | 0.58%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 0.58%   |
| SK hynix Gold P31 SSD                                                                   | 5         | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5         | 0.48%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5         | 0.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 5         | 0.48%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.48%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 5         | 0.48%   |
| AMD SB600 IDE                                                                           | 5         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 521       | 58.67%  |
| NVMe | 175       | 19.71%  |
| IDE  | 144       | 16.22%  |
| RAID | 47        | 5.29%   |
| SAS  | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 569       | 79.25%  |
| AMD    | 149       | 20.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 11        | 1.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 9         | 1.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 9         | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 9         | 1.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 8         | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 6         | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 0.83%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 5         | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 5         | 0.69%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 5         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 5         | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 5         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 5         | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5         | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 0.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 5         | 0.69%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 5         | 0.69%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 4         | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.55%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 4         | 0.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 0.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 0.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 0.55%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 4         | 0.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 4         | 0.55%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 0.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 4         | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4         | 0.55%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 4         | 0.55%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 4         | 0.55%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 4         | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4         | 0.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 0.55%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4         | 0.55%   |
| AMD FX-6300 Six-Core Processor              | 4         | 0.55%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 3         | 0.42%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 3         | 0.42%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 3         | 0.42%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 3         | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 3         | 0.42%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 3         | 0.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 0.42%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3         | 0.42%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3         | 0.42%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3         | 0.42%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.42%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3         | 0.42%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.42%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 0.42%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 3         | 0.42%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 155       | 21.5%   |
| Intel Core i7           | 153       | 21.22%  |
| Intel Core i3           | 56        | 7.77%   |
| Intel Core 2 Duo        | 41        | 5.69%   |
| Intel Pentium           | 36        | 4.99%   |
| Intel Celeron           | 34        | 4.72%   |
| AMD Ryzen 5             | 32        | 4.44%   |
| AMD Ryzen 7             | 24        | 3.33%   |
| Intel Xeon              | 15        | 2.08%   |
| Other                   | 12        | 1.66%   |
| Intel Core 2 Quad       | 12        | 1.66%   |
| Intel Pentium Dual-Core | 11        | 1.53%   |
| Intel Atom              | 9         | 1.25%   |
| AMD Ryzen 3             | 9         | 1.25%   |
| AMD Athlon 64 X2        | 9         | 1.25%   |
| Intel Pentium Dual      | 8         | 1.11%   |
| Intel Core 2            | 7         | 0.97%   |
| AMD FX                  | 7         | 0.97%   |
| AMD Ryzen 9             | 6         | 0.83%   |
| Intel Pentium Silver    | 5         | 0.69%   |
| AMD Ryzen 7 PRO         | 5         | 0.69%   |
| AMD Athlon 64           | 5         | 0.69%   |
| AMD A8                  | 5         | 0.69%   |
| Intel Core i9           | 4         | 0.55%   |
| AMD Ryzen 5 PRO         | 4         | 0.55%   |
| AMD Phenom II X4        | 4         | 0.55%   |
| AMD E1                  | 4         | 0.55%   |
| AMD Athlon II X2        | 4         | 0.55%   |
| AMD Sempron             | 3         | 0.42%   |
| AMD Athlon II X4        | 3         | 0.42%   |
| AMD A6                  | 3         | 0.42%   |
| Intel Pentium M         | 2         | 0.28%   |
| Intel Pentium Gold      | 2         | 0.28%   |
| Intel Genuine           | 2         | 0.28%   |
| AMD Phenom II X6        | 2         | 0.28%   |
| AMD Phenom II X2        | 2         | 0.28%   |
| AMD Phenom              | 2         | 0.28%   |
| AMD Athlon X4           | 2         | 0.28%   |
| AMD A10                 | 2         | 0.28%   |
| Intel Pentium D         | 1         | 0.14%   |
| Intel Mobile Pentium 4  | 1         | 0.14%   |
| Intel Core m3           | 1         | 0.14%   |
| Intel Core M            | 1         | 0.14%   |
| Intel Core Duo          | 1         | 0.14%   |
| Intel Core 2 Solo       | 1         | 0.14%   |
| Intel Celeron M         | 1         | 0.14%   |
| Intel Celeron Dual-Core | 1         | 0.14%   |
| AMD Turion 64 X2 Mobile | 1         | 0.14%   |
| AMD Turion 64 Mobile    | 1         | 0.14%   |
| AMD Ryzen Embedded      | 1         | 0.14%   |
| AMD Phenom II X3        | 1         | 0.14%   |
| AMD Phenom II           | 1         | 0.14%   |
| AMD GX                  | 1         | 0.14%   |
| AMD E2                  | 1         | 0.14%   |
| AMD E                   | 1         | 0.14%   |
| AMD C-50                | 1         | 0.14%   |
| AMD Athlon II X3        | 1         | 0.14%   |
| AMD Athlon II Dual-Core | 1         | 0.14%   |
| AMD A4                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 339       | 46.95%  |
| 4       | 240       | 33.24%  |
| 6       | 65        | 9%      |
| 8       | 34        | 4.71%   |
| 1       | 23        | 3.19%   |
| 3       | 9         | 1.25%   |
| 12      | 7         | 0.97%   |
| Unknown | 2         | 0.28%   |
| 18      | 1         | 0.14%   |
| 16      | 1         | 0.14%   |
| 14      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 716       | 99.72%  |
| 2      | 2         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 434       | 60.11%  |
| 1       | 286       | 39.61%  |
| Unknown | 2         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 690       | 95.04%  |
| Unknown        | 26        | 3.58%   |
| 32-bit         | 10        | 1.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 20.51%  |
| 0x306a9    | 57        | 7.59%   |
| 0x206a7    | 54        | 7.19%   |
| 0x306c3    | 40        | 5.33%   |
| 0x1067a    | 33        | 4.39%   |
| 0x906ea    | 22        | 2.93%   |
| 0x806ec    | 22        | 2.93%   |
| 0x306d4    | 22        | 2.93%   |
| 0x506e3    | 19        | 2.53%   |
| 0x906e9    | 18        | 2.4%    |
| 0x20655    | 18        | 2.4%    |
| 0x6fd      | 15        | 2%      |
| 0x406e3    | 15        | 2%      |
| 0x40651    | 15        | 2%      |
| 0x806ea    | 13        | 1.73%   |
| 0x10676    | 12        | 1.6%    |
| 0x706a1    | 10        | 1.33%   |
| 0x010000c8 | 10        | 1.33%   |
| 0x506c9    | 9         | 1.2%    |
| 0x6fb      | 8         | 1.07%   |
| 0x08108109 | 8         | 1.07%   |
| 0x806e9    | 7         | 0.93%   |
| 0x08108102 | 7         | 0.93%   |
| 0x806c1    | 6         | 0.8%    |
| 0x6f6      | 6         | 0.8%    |
| 0x406c3    | 6         | 0.8%    |
| 0x306f2    | 6         | 0.8%    |
| 0x08608103 | 6         | 0.8%    |
| 0xa0652    | 5         | 0.67%   |
| 0x806eb    | 5         | 0.67%   |
| 0x706e5    | 5         | 0.67%   |
| 0x08600106 | 5         | 0.67%   |
| 0x08600103 | 5         | 0.67%   |
| 0x106e5    | 4         | 0.53%   |
| 0x106c2    | 4         | 0.53%   |
| 0x0a50000c | 4         | 0.53%   |
| 0x0a201009 | 4         | 0.53%   |
| 0x0800820d | 4         | 0.53%   |
| 0x0700010f | 4         | 0.53%   |
| 0x06000852 | 4         | 0.53%   |
| 0xa0671    | 3         | 0.4%    |
| 0xa0655    | 3         | 0.4%    |
| 0x30678    | 3         | 0.4%    |
| 0x08701013 | 3         | 0.4%    |
| 0x08600104 | 3         | 0.4%    |
| 0x06003106 | 3         | 0.4%    |
| 0x06001119 | 3         | 0.4%    |
| 0x03000027 | 3         | 0.4%    |
| 0x906ed    | 2         | 0.27%   |
| 0x6f2      | 2         | 0.27%   |
| 0x6d8      | 2         | 0.27%   |
| 0x406c4    | 2         | 0.27%   |
| 0x206c2    | 2         | 0.27%   |
| 0x0a201204 | 2         | 0.27%   |
| 0x08101007 | 2         | 0.27%   |
| 0x08001138 | 2         | 0.27%   |
| 0x06006704 | 2         | 0.27%   |
| 0x010000db | 2         | 0.27%   |
| 0xf64      | 1         | 0.13%   |
| 0x906eb    | 1         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 107       | 14.88%  |
| IvyBridge        | 73        | 10.15%  |
| Haswell          | 72        | 10.01%  |
| SandyBridge      | 65        | 9.04%   |
| Penryn           | 52        | 7.23%   |
| Skylake          | 37        | 5.15%   |
| Core             | 34        | 4.73%   |
| Broadwell        | 26        | 3.62%   |
| Zen+             | 24        | 3.34%   |
| Zen 2            | 24        | 3.34%   |
| Westmere         | 24        | 3.34%   |
| K10              | 21        | 2.92%   |
| Zen 3            | 17        | 2.36%   |
| K8 Hammer        | 17        | 2.36%   |
| Silvermont       | 12        | 1.67%   |
| Goldmont plus    | 12        | 1.67%   |
| Piledriver       | 11        | 1.53%   |
| CometLake        | 11        | 1.53%   |
| Zen              | 10        | 1.39%   |
| Goldmont         | 9         | 1.25%   |
| Unknown          | 9         | 1.25%   |
| TigerLake        | 7         | 0.97%   |
| IceLake          | 7         | 0.97%   |
| P6               | 5         | 0.7%    |
| Nehalem          | 5         | 0.7%    |
| Bonnell          | 5         | 0.7%    |
| Jaguar           | 4         | 0.56%   |
| Excavator        | 4         | 0.56%   |
| Steamroller      | 3         | 0.42%   |
| K10 Llano        | 3         | 0.42%   |
| Puma             | 2         | 0.28%   |
| NetBurst         | 2         | 0.28%   |
| Bobcat           | 2         | 0.28%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |
| Alderlake Hybrid | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 434       | 48.6%   |
| Nvidia                           | 253       | 28.33%  |
| AMD                              | 205       | 22.96%  |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 49        | 5.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 5.22%   |
| Intel HD Graphics 5500                                                                   | 23        | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 2.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 2.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.85%   |
| AMD Renoir                                                                               | 17        | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16        | 1.74%   |
| Intel HD Graphics 630                                                                    | 15        | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 1.41%   |
| Intel UHD Graphics 620                                                                   | 13        | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.31%   |
| Intel HD Graphics 530                                                                    | 11        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.2%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 1.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.98%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.76%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.76%   |
| AMD Cezanne                                                                              | 7         | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.65%   |
| Intel HD Graphics 620                                                                    | 6         | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 0.65%   |
| AMD Lucienne                                                                             | 6         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5         | 0.54%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.54%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.54%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 5         | 0.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 0.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 0.54%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.44%   |
| Nvidia TU117M                                                                            | 4         | 0.44%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4         | 0.44%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 4         | 0.44%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.44%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 4         | 0.44%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.44%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.44%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 4         | 0.44%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 4         | 0.44%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.44%   |
| Intel HD Graphics 500                                                                    | 4         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 272       | 37.31%  |
| 1 x AMD        | 161       | 22.09%  |
| Intel + Nvidia | 125       | 17.15%  |
| 1 x Nvidia     | 122       | 16.74%  |
| Intel + AMD    | 30        | 4.12%   |
| 2 x AMD        | 10        | 1.37%   |
| AMD + Nvidia   | 8         | 1.1%    |
| 1 x SiS        | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 564       | 76.94%  |
| Proprietary | 137       | 18.69%  |
| Unknown     | 32        | 4.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 364       | 48.4%   |
| 1.01-2.0   | 129       | 17.15%  |
| 0.01-0.5   | 85        | 11.3%   |
| 3.01-4.0   | 69        | 9.18%   |
| 0.51-1.0   | 59        | 7.85%   |
| 7.01-8.0   | 26        | 3.46%   |
| 5.01-6.0   | 12        | 1.6%    |
| 2.01-3.0   | 4         | 0.53%   |
| 8.01-16.0  | 3         | 0.4%    |
| 16.01-24.0 | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 131       | 17.01%  |
| Samsung Electronics     | 80        | 10.39%  |
| AU Optronics            | 77        | 10%     |
| Chimei Innolux          | 53        | 6.88%   |
| Dell                    | 51        | 6.62%   |
| BOE                     | 49        | 6.36%   |
| Goldstar                | 37        | 4.81%   |
| Philips                 | 34        | 4.42%   |
| Acer                    | 27        | 3.51%   |
| Lenovo                  | 21        | 2.73%   |
| Ancor Communications    | 21        | 2.73%   |
| Hewlett-Packard         | 18        | 2.34%   |
| Chi Mei Optoelectronics | 15        | 1.95%   |
| BenQ                    | 15        | 1.95%   |
| AOC                     | 13        | 1.69%   |
| PANDA                   | 9         | 1.17%   |
| LG Philips              | 9         | 1.17%   |
| Sharp                   | 7         | 0.91%   |
| LG Electronics          | 7         | 0.91%   |
| Fujitsu Siemens         | 7         | 0.91%   |
| Sony                    | 6         | 0.78%   |
| Panasonic               | 6         | 0.78%   |
| Apple                   | 5         | 0.65%   |
| NEC Computers           | 4         | 0.52%   |
| HannStar                | 4         | 0.52%   |
| Eizo                    | 4         | 0.52%   |
| CPT                     | 4         | 0.52%   |
| ViewSonic               | 3         | 0.39%   |
| Vestel Elektronik       | 3         | 0.39%   |
| Unknown                 | 3         | 0.39%   |
| WST                     | 2         | 0.26%   |
| Vestel                  | 2         | 0.26%   |
| Toshiba                 | 2         | 0.26%   |
| MSI                     | 2         | 0.26%   |
| Lenovo Group Limited    | 2         | 0.26%   |
| InnoLux Display         | 2         | 0.26%   |
| Iiyama                  | 2         | 0.26%   |
| Gigabyte Technology     | 2         | 0.26%   |
| Belinea                 | 2         | 0.26%   |
| ASUSTek Computer        | 2         | 0.26%   |
| ___                     | 1         | 0.13%   |
| WIN                     | 1         | 0.13%   |
| TSL                     | 1         | 0.13%   |
| TAR                     | 1         | 0.13%   |
| SUNNY                   | 1         | 0.13%   |
| Seiko/Epson             | 1         | 0.13%   |
| PRISM+                  | 1         | 0.13%   |
| PEGA                    | 1         | 0.13%   |
| Packard Bell            | 1         | 0.13%   |
| Optoma                  | 1         | 0.13%   |
| NUG                     | 1         | 0.13%   |
| NCS                     | 1         | 0.13%   |
| KTC                     | 1         | 0.13%   |
| JDI                     | 1         | 0.13%   |
| Idek Iiyama             | 1         | 0.13%   |
| IBM                     | 1         | 0.13%   |
| HPN                     | 1         | 0.13%   |
| HKC                     | 1         | 0.13%   |
| HJW                     | 1         | 0.13%   |
| Hitachi                 | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 1.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.75%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 4         | 0.5%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.5%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 4         | 0.5%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.5%    |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.5%    |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.38%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.38%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.38%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 3         | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 3         | 0.38%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 3         | 0.38%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                        | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.38%   |
| Acer G257HL ACR0415 1920x1080 553x309mm 24.9-inch                        | 3         | 0.38%   |
| Samsung Electronics SMXL2370HD SAM072B 1920x1080 510x287mm 23.0-inch     | 2         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch    | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch    | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch   | 2         | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.25%   |
| Philips 234CL PHLC066 1920x1080 509x286mm 23.0-inch                      | 2         | 0.25%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 2         | 0.25%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.25%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch              | 2         | 0.25%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.25%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.25%   |
| LG Display LCD Monitor LGD063A 1920x1080 344x194mm 15.5-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD05E9 1920x1080 294x165mm 13.3-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD05E0 1920x1080 382x215mm 17.3-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch             | 2         | 0.25%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 332       | 44.68%  |
| 1366x768 (WXGA)    | 141       | 18.98%  |
| 1680x1050 (WSXGA+) | 35        | 4.71%   |
| 1280x1024 (SXGA)   | 34        | 4.58%   |
| 3840x2160 (4K)     | 28        | 3.77%   |
| 1600x900 (HD+)     | 28        | 3.77%   |
| 2560x1440 (QHD)    | 26        | 3.5%    |
| 1280x800 (WXGA)    | 25        | 3.36%   |
| 1440x900 (WXGA+)   | 17        | 2.29%   |
| 1920x1200 (WUXGA)  | 13        | 1.75%   |
| Unknown            | 13        | 1.75%   |
| 2560x1080          | 5         | 0.67%   |
| 3840x1080          | 4         | 0.54%   |
| 3440x1440          | 4         | 0.54%   |
| 1024x768 (XGA)     | 4         | 0.54%   |
| 1024x600           | 4         | 0.54%   |
| 3840x1200          | 3         | 0.4%    |
| 2560x1600          | 3         | 0.4%    |
| 1600x1200          | 3         | 0.4%    |
| 1360x768           | 3         | 0.4%    |
| 3200x1080          | 2         | 0.27%   |
| 1400x1050          | 2         | 0.27%   |
| 1280x720 (HD)      | 2         | 0.27%   |
| 6784x2160          | 1         | 0.13%   |
| 6400x1080          | 1         | 0.13%   |
| 5120x1080          | 1         | 0.13%   |
| 4240x1440          | 1         | 0.13%   |
| 3600x1200          | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2160x1440          | 1         | 0.13%   |
| 2048x1152          | 1         | 0.13%   |
| 1921x1080          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1820x1023          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 250       | 32.47%  |
| 13      | 57        | 7.4%    |
| 24      | 51        | 6.62%   |
| 23      | 46        | 5.97%   |
| 21      | 46        | 5.97%   |
| 17      | 45        | 5.84%   |
| 14      | 45        | 5.84%   |
| Unknown | 41        | 5.32%   |
| 27      | 31        | 4.03%   |
| 19      | 25        | 3.25%   |
| 22      | 21        | 2.73%   |
| 12      | 21        | 2.73%   |
| 20      | 14        | 1.82%   |
| 84      | 10        | 1.3%    |
| 18      | 10        | 1.3%    |
| 34      | 9         | 1.17%   |
| 31      | 9         | 1.17%   |
| 54      | 6         | 0.78%   |
| 25      | 5         | 0.65%   |
| 10      | 5         | 0.65%   |
| 40      | 4         | 0.52%   |
| 11      | 4         | 0.52%   |
| 72      | 3         | 0.39%   |
| 26      | 2         | 0.26%   |
| 16      | 2         | 0.26%   |
| 75      | 1         | 0.13%   |
| 65      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 340       | 44.33%  |
| 501-600     | 126       | 16.43%  |
| 401-500     | 101       | 13.17%  |
| 201-300     | 54        | 7.04%   |
| 351-400     | 50        | 6.52%   |
| Unknown     | 41        | 5.35%   |
| 601-700     | 16        | 2.09%   |
| 1501-2000   | 14        | 1.83%   |
| 701-800     | 11        | 1.43%   |
| 1001-1500   | 9         | 1.17%   |
| 801-900     | 5         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 512       | 73.04%  |
| 16/10   | 95        | 13.55%  |
| Unknown | 37        | 5.28%   |
| 5/4     | 31        | 4.42%   |
| 4/3     | 11        | 1.57%   |
| 21/9    | 9         | 1.28%   |
| 3/2     | 4         | 0.57%   |
| 6/5     | 1         | 0.14%   |
| 32/9    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 249       | 32.68%  |
| 201-250        | 130       | 17.06%  |
| 81-90          | 82        | 10.76%  |
| 151-200        | 50        | 6.56%   |
| Unknown        | 41        | 5.38%   |
| 301-350        | 33        | 4.33%   |
| 141-150        | 24        | 3.15%   |
| 121-130        | 24        | 3.15%   |
| 251-300        | 23        | 3.02%   |
| More than 1000 | 22        | 2.89%   |
| 71-80          | 22        | 2.89%   |
| 351-500        | 21        | 2.76%   |
| 61-70          | 19        | 2.49%   |
| 501-1000       | 6         | 0.79%   |
| 41-50          | 5         | 0.66%   |
| 51-60          | 4         | 0.52%   |
| 131-140        | 4         | 0.52%   |
| 111-120        | 2         | 0.26%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 248       | 33.2%   |
| 121-160       | 214       | 28.65%  |
| 101-120       | 192       | 25.7%   |
| Unknown       | 41        | 5.49%   |
| 161-240       | 28        | 3.75%   |
| 1-50          | 16        | 2.14%   |
| More than 240 | 8         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 594       | 80.05%  |
| 2     | 101       | 13.61%  |
| 0     | 37        | 4.99%   |
| 3     | 9         | 1.21%   |
| 4     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 377       | 34.24%  |
| Intel                                 | 358       | 32.52%  |
| Qualcomm Atheros                      | 131       | 11.9%   |
| Broadcom                              | 52        | 4.72%   |
| Broadcom Limited                      | 24        | 2.18%   |
| Ralink                                | 19        | 1.73%   |
| TP-Link                               | 16        | 1.45%   |
| Nvidia                                | 16        | 1.45%   |
| Marvell Technology Group              | 14        | 1.27%   |
| Ralink Technology                     | 11        | 1%      |
| Qualcomm Atheros Communications       | 11        | 1%      |
| Sierra Wireless                       | 9         | 0.82%   |
| Ericsson Business Mobile Networks     | 9         | 0.82%   |
| MediaTek                              | 8         | 0.73%   |
| Huawei Technologies                   | 4         | 0.36%   |
| Hewlett-Packard                       | 4         | 0.36%   |
| Dell                                  | 4         | 0.36%   |
| Xiaomi                                | 3         | 0.27%   |
| Sundance Technology Inc / IC Plus     | 3         | 0.27%   |
| D-Link                                | 3         | 0.27%   |
| AMD                                   | 3         | 0.27%   |
| Toshiba                               | 2         | 0.18%   |
| Motorola PCS                          | 2         | 0.18%   |
| Microsoft                             | 2         | 0.18%   |
| Davicom Semiconductor                 | 2         | 0.18%   |
| Quectel Wireless Solutions            | 1         | 0.09%   |
| NetGear                               | 1         | 0.09%   |
| Micro Star International              | 1         | 0.09%   |
| JMicron Technology                    | 1         | 0.09%   |
| ICS Advent                            | 1         | 0.09%   |
| Google                                | 1         | 0.09%   |
| Gemtek                                | 1         | 0.09%   |
| DisplayLink                           | 1         | 0.09%   |
| D-Link System                         | 1         | 0.09%   |
| Cypress Semiconductor                 | 1         | 0.09%   |
| Chelsio Communications                | 1         | 0.09%   |
| ASIX Electronics                      | 1         | 0.09%   |
| Aquantia                              | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 253       | 19.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 4.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 44        | 3.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 24        | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 21        | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 1.48%   |
| Intel Wireless 7265                                               | 19        | 1.48%   |
| Intel Wireless 7260                                               | 19        | 1.48%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 1.33%   |
| Intel Wireless 3160                                               | 12        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.86%   |
| Intel I211 Gigabit Network Connection                             | 11        | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 11        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                   | 10        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.7%    |
| Intel WiFi Link 5100                                              | 9         | 0.7%    |
| Intel Centrino Ultimate-N 6300                                    | 9         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 8         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 7         | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 7         | 0.55%   |
| Intel Wireless-AC 9260                                            | 7         | 0.55%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 7         | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 7         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.55%   |
| Sierra Wireless EM7345 4G LTE                                     | 6         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 6         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.47%   |
| Intel Wireless 8260                                               | 6         | 0.47%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.47%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 265       | 48.27%  |
| Qualcomm Atheros                      | 93        | 16.94%  |
| Realtek Semiconductor                 | 69        | 12.57%  |
| Broadcom                              | 33        | 6.01%   |
| Ralink                                | 19        | 3.46%   |
| TP-Link                               | 14        | 2.55%   |
| Ralink Technology                     | 11        | 2%      |
| Qualcomm Atheros Communications       | 11        | 2%      |
| Sierra Wireless                       | 9         | 1.64%   |
| Broadcom Limited                      | 8         | 1.46%   |
| MediaTek                              | 7         | 1.28%   |
| Microsoft                             | 2         | 0.36%   |
| Quectel Wireless Solutions            | 1         | 0.18%   |
| NetGear                               | 1         | 0.18%   |
| Micro Star International              | 1         | 0.18%   |
| Hewlett-Packard                       | 1         | 0.18%   |
| Gemtek                                | 1         | 0.18%   |
| Dell                                  | 1         | 0.18%   |
| D-Link                                | 1         | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 25        | 4.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 24        | 4.36%   |
| Intel Wireless 8265 / 8275                                     | 21        | 3.81%   |
| Intel Wireless 7265                                            | 19        | 3.45%   |
| Intel Wireless 7260                                            | 19        | 3.45%   |
| Intel Wi-Fi 6 AX200                                            | 19        | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 3.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 3.09%   |
| Intel Wireless 3160                                            | 12        | 2.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.81%   |
| Qualcomm Atheros AR9271 802.11n                                | 10        | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 1.63%   |
| Intel WiFi Link 5100                                           | 9         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                 | 9         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7         | 1.27%   |
| Intel Wireless-AC 9260                                         | 7         | 1.27%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 7         | 1.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.27%   |
| Sierra Wireless EM7345 4G LTE                                  | 6         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 1.09%   |
| Intel Wireless 8260                                            | 6         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.09%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 5         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.73%   |
| Realtek RTL8187B Wireless Adapter                              | 4         | 0.73%   |
| Realtek RTL8187 Wireless Adapter                               | 4         | 0.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 0.73%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.73%   |
| Intel Wireless 3165                                            | 4         | 0.73%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 0.73%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.73%   |
| TP-Link 802.11ac NIC                                           | 3         | 0.54%   |
| Sierra Wireless EM7455                                         | 3         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.54%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 3         | 0.54%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.54%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.54%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 2         | 0.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.36%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 343       | 49.57%  |
| Intel                             | 203       | 29.34%  |
| Qualcomm Atheros                  | 51        | 7.37%   |
| Broadcom                          | 22        | 3.18%   |
| Nvidia                            | 16        | 2.31%   |
| Broadcom Limited                  | 16        | 2.31%   |
| Marvell Technology Group          | 14        | 2.02%   |
| Xiaomi                            | 3         | 0.43%   |
| Sundance Technology Inc / IC Plus | 3         | 0.43%   |
| Huawei Technologies               | 3         | 0.43%   |
| TP-Link                           | 2         | 0.29%   |
| Motorola PCS                      | 2         | 0.29%   |
| Davicom Semiconductor             | 2         | 0.29%   |
| D-Link                            | 2         | 0.29%   |
| MediaTek                          | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| ICS Advent                        | 1         | 0.14%   |
| Google                            | 1         | 0.14%   |
| DisplayLink                       | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| Cypress Semiconductor             | 1         | 0.14%   |
| Chelsio Communications            | 1         | 0.14%   |
| ASIX Electronics                  | 1         | 0.14%   |
| Aquantia                          | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 253       | 35.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 56        | 7.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 44        | 6.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 19        | 2.7%    |
| Intel Ethernet Connection I217-LM                                              | 12        | 1.7%    |
| Intel I211 Gigabit Network Connection                                          | 11        | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 1.56%   |
| Intel Ethernet Connection (2) I219-V                                           | 11        | 1.56%   |
| Intel 82579V Gigabit Network Connection                                        | 10        | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 1.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 1.13%   |
| Nvidia MCP61 Ethernet                                                          | 8         | 1.13%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 1.13%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 7         | 0.99%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                           | 7         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 0.85%   |
| Intel Ethernet Controller I225-V                                               | 6         | 0.85%   |
| Intel Ethernet Connection (2) I218-V                                           | 6         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.71%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.57%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.57%   |
| Intel Ethernet Connection I217-V                                               | 4         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 4         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 4         | 0.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 4         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.43%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 3         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.43%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 3         | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 3         | 0.43%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.43%   |
| Intel 82578DM Gigabit Network Connection                                       | 3         | 0.43%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 3         | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 2         | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.28%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2         | 0.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.28%   |
| Nvidia MCP65 Ethernet                                                          | 2         | 0.28%   |
| Nvidia MCP55 Ethernet                                                          | 2         | 0.28%   |
| Motorola PCS moto g(9) play                                                    | 2         | 0.28%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.28%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.28%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.28%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.28%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.28%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.28%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 656       | 54.94%  |
| WiFi     | 514       | 43.05%  |
| Modem    | 24        | 2.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 415       | 55.33%  |
| Ethernet | 335       | 44.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 427       | 59.22%  |
| 1     | 276       | 38.28%  |
| 3     | 10        | 1.39%   |
| 0     | 6         | 0.83%   |
| 5     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 712       | 98.61%  |
| Yes  | 10        | 1.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 179       | 44.2%   |
| Qualcomm Atheros Communications | 30        | 7.41%   |
| Cambridge Silicon Radio         | 28        | 6.91%   |
| Realtek Semiconductor           | 25        | 6.17%   |
| Broadcom                        | 25        | 6.17%   |
| IMC Networks                    | 22        | 5.43%   |
| Lite-On Technology              | 16        | 3.95%   |
| Foxconn / Hon Hai               | 13        | 3.21%   |
| Toshiba                         | 11        | 2.72%   |
| Hewlett-Packard                 | 11        | 2.72%   |
| Dell                            | 11        | 2.72%   |
| Ralink                          | 9         | 2.22%   |
| Apple                           | 7         | 1.73%   |
| Integrated System Solution      | 5         | 1.23%   |
| Foxconn International           | 4         | 0.99%   |
| ASUSTek Computer                | 4         | 0.99%   |
| Ralink Technology               | 2         | 0.49%   |
| MediaTek                        | 2         | 0.49%   |
| Realtek                         | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 76        | 18.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 35        | 8.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 28        | 6.91%   |
| Intel AX201 Bluetooth                                                               | 25        | 6.17%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 21        | 5.19%   |
| Intel AX200 Bluetooth                                                               | 19        | 4.69%   |
| Realtek Bluetooth Radio                                                             | 18        | 4.44%   |
| Intel Bluetooth Device                                                              | 12        | 2.96%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 2.96%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 2.22%   |
| Lite-On Bluetooth Device                                                            | 8         | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.98%   |
| IMC Networks Bluetooth Device                                                       | 6         | 1.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 1.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.48%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 1.23%   |
| IMC Networks Wireless_Device                                                        | 4         | 0.99%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.99%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.99%   |
| Apple Bluetooth Host Controller                                                     | 4         | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.74%   |
| Integrated System Solution Bluetooth Device                                         | 3         | 0.74%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.74%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.74%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.74%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.49%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.49%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.49%   |
| MediaTek Wireless_Device                                                            | 2         | 0.49%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.49%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.49%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.49%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.25%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.25%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.25%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.25%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.25%   |
| Ralink CSR BS8510                                                                   | 1         | 0.25%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.25%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.25%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.25%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.25%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.25%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.25%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.25%   |
| Dell BCM2046 Bluetooth Device                                                       | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 551       | 55.83%  |
| AMD                                  | 192       | 19.45%  |
| Nvidia                               | 162       | 16.41%  |
| C-Media Electronics                  | 18        | 1.82%   |
| Creative Labs                        | 9         | 0.91%   |
| GN Netcom                            | 7         | 0.71%   |
| Logitech                             | 5         | 0.51%   |
| Texas Instruments                    | 4         | 0.41%   |
| Razer USA                            | 4         | 0.41%   |
| Plantronics                          | 4         | 0.41%   |
| Creative Technology                  | 4         | 0.41%   |
| Generalplus Technology               | 3         | 0.3%    |
| ASUSTek Computer                     | 3         | 0.3%    |
| Thesycon Systemsoftware & Consulting | 2         | 0.2%    |
| Tenx Technology                      | 2         | 0.2%    |
| Lenovo                               | 2         | 0.2%    |
| BEHRINGER International              | 2         | 0.2%    |
| VIA Technologies                     | 1         | 0.1%    |
| SteelSeries ApS                      | 1         | 0.1%    |
| Silicon Integrated Systems [SiS]     | 1         | 0.1%    |
| Samson Technologies                  | 1         | 0.1%    |
| Realtek Semiconductor                | 1         | 0.1%    |
| NAD Electronics                      | 1         | 0.1%    |
| M-Audio                              | 1         | 0.1%    |
| JMTek                                | 1         | 0.1%    |
| FiiO Electronics Technology          | 1         | 0.1%    |
| Evolution Electronics                | 1         | 0.1%    |
| ESS Technology                       | 1         | 0.1%    |
| DSEA A/S                             | 1         | 0.1%    |
| Corsair                              | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 67        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 65        | 5.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 52        | 4.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 45        | 3.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 3.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 34        | 2.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 28        | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 28        | 2.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 26        | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 2.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 1.7%    |
| Intel 8 Series HD Audio Controller                                                                | 20        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.53%   |
| AMD FCH Azalia Controller                                                                         | 18        | 1.53%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 17        | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 16        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 14        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 13        | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 13        | 1.11%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 12        | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 1.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 12        | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 0.77%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.77%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 9         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.68%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 8         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 0.6%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 7         | 0.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7         | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 6         | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 0.51%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 6         | 0.51%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 5         | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.43%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 5         | 0.43%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 87        | 20.19%  |
| SK hynix                                | 78        | 18.1%   |
| Kingston                                | 61        | 14.15%  |
| Unknown                                 | 48        | 11.14%  |
| Micron Technology                       | 33        | 7.66%   |
| Corsair                                 | 23        | 5.34%   |
| A-DATA Technology                       | 20        | 4.64%   |
| Ramaxel Technology                      | 17        | 3.94%   |
| Nanya Technology                        | 10        | 2.32%   |
| Team                                    | 8         | 1.86%   |
| Crucial                                 | 8         | 1.86%   |
| Transcend                               | 7         | 1.62%   |
| Elpida                                  | 6         | 1.39%   |
| G.Skill                                 | 5         | 1.16%   |
| Apacer                                  | 3         | 0.7%    |
| Silicon Power                           | 2         | 0.46%   |
| pqi                                     | 2         | 0.46%   |
| Goodram                                 | 2         | 0.46%   |
| Atermiter                               | 2         | 0.46%   |
| Unknown (ABCD)                          | 1         | 0.23%   |
| Thermaltake                             | 1         | 0.23%   |
| Silicon Power Computer & Communications | 1         | 0.23%   |
| Qimonda                                 | 1         | 0.23%   |
| HBS                                     | 1         | 0.23%   |
| CSX                                     | 1         | 0.23%   |
| ASint Technology                        | 1         | 0.23%   |
| A Force                                 | 1         | 0.23%   |
| Unknown                                 | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 8         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 1.29%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.86%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 4         | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 4         | 0.86%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s      | 4         | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 3         | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 3         | 0.64%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 0.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.64%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 0.64%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 3         | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 0.64%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 3         | 0.64%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s       | 3         | 0.64%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 3         | 0.64%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 3         | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2         | 0.43%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.43%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2         | 0.43%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR                         | 2         | 0.43%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s          | 2         | 0.43%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s         | 2         | 0.43%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 2         | 0.43%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                   | 2         | 0.43%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                | 2         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.43%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.43%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 2         | 0.43%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s         | 2         | 0.43%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 2         | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s    | 2         | 0.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s              | 2         | 0.43%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.43%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 2         | 0.43%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.43%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 2         | 0.43%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 2         | 0.43%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s | 2         | 0.43%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 2         | 0.43%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.43%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s             | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 154       | 42.78%  |
| DDR4    | 141       | 39.17%  |
| DDR2    | 23        | 6.39%   |
| SDRAM   | 14        | 3.89%   |
| Unknown | 13        | 3.61%   |
| LPDDR3  | 5         | 1.39%   |
| DDR     | 5         | 1.39%   |
| LPDDR4  | 3         | 0.83%   |
| DRAM    | 2         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 211       | 59.44%  |
| DIMM         | 132       | 37.18%  |
| Row Of Chips | 6         | 1.69%   |
| Chip         | 4         | 1.13%   |
| RIMM         | 1         | 0.28%   |
| FB-DIMM      | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 135       | 34.88%  |
| 8192    | 117       | 30.23%  |
| 2048    | 54        | 13.95%  |
| 16384   | 46        | 11.89%  |
| 1024    | 19        | 4.91%   |
| 32768   | 11        | 2.84%   |
| 512     | 3         | 0.78%   |
| 256     | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 99        | 25.13%  |
| 2667    | 60        | 15.23%  |
| 1333    | 37        | 9.39%   |
| 3200    | 35        | 8.88%   |
| 2400    | 24        | 6.09%   |
| 1334    | 20        | 5.08%   |
| 800     | 16        | 4.06%   |
| 2133    | 15        | 3.81%   |
| Unknown | 14        | 3.55%   |
| 667     | 10        | 2.54%   |
| 3600    | 9         | 2.28%   |
| 1867    | 6         | 1.52%   |
| 3266    | 5         | 1.27%   |
| 3000    | 4         | 1.02%   |
| 3466    | 3         | 0.76%   |
| 2933    | 3         | 0.76%   |
| 1067    | 3         | 0.76%   |
| 1066    | 3         | 0.76%   |
| 333     | 3         | 0.76%   |
| 4199    | 2         | 0.51%   |
| 3800    | 2         | 0.51%   |
| 3333    | 2         | 0.51%   |
| 2800    | 2         | 0.51%   |
| 1866    | 2         | 0.51%   |
| 1800    | 2         | 0.51%   |
| 57535   | 1         | 0.25%   |
| 4267    | 1         | 0.25%   |
| 3733    | 1         | 0.25%   |
| 3467    | 1         | 0.25%   |
| 3066    | 1         | 0.25%   |
| 2666    | 1         | 0.25%   |
| 2481    | 1         | 0.25%   |
| 2048    | 1         | 0.25%   |
| 2000    | 1         | 0.25%   |
| 1639    | 1         | 0.25%   |
| 975     | 1         | 0.25%   |
| 533     | 1         | 0.25%   |
| 400     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 33.33%  |
| Brother Industries  | 4         | 22.22%  |
| Samsung Electronics | 3         | 16.67%  |
| Xerox               | 2         | 11.11%  |
| Kyocera             | 1         | 5.56%   |
| Canon               | 1         | 5.56%   |
| ATEN International  | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP LaserJet 1020                         | 2         | 11.11%  |
| Xerox Phaser 3140 and 3155               | 1         | 5.56%   |
| Xerox Phaser 3020                        | 1         | 5.56%   |
| Samsung ML-2010P Mono Laser Printer      | 1         | 5.56%   |
| Samsung M332x 382x 402x Series           | 1         | 5.56%   |
| Samsung M267x 287x Series                | 1         | 5.56%   |
| Kyocera ECOSYS P2040dn                   | 1         | 5.56%   |
| HP LaserJet Professional P1566           | 1         | 5.56%   |
| HP LaserJet P1102                        | 1         | 5.56%   |
| HP LaserJet 4350                         | 1         | 5.56%   |
| HP DeskJet 4530 series                   | 1         | 5.56%   |
| Canon PIXMA MP240                        | 1         | 5.56%   |
| Brother Printer                          | 1         | 5.56%   |
| Brother MFC-B7715DW series               | 1         | 5.56%   |
| Brother DCP-T300                         | 1         | 5.56%   |
| Brother DCP-7055 scanner/printer         | 1         | 5.56%   |
| ATEN International UC-1284B Printer Port | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22        | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 110            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 113       | 26.16%  |
| IMC Networks                           | 48        | 11.11%  |
| Microdia                               | 41        | 9.49%   |
| Realtek Semiconductor                  | 38        | 8.8%    |
| Acer                                   | 32        | 7.41%   |
| Sunplus Innovation Technology          | 22        | 5.09%   |
| Quanta                                 | 18        | 4.17%   |
| Suyin                                  | 13        | 3.01%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.01%   |
| Lite-On Technology                     | 12        | 2.78%   |
| Logitech                               | 11        | 2.55%   |
| Syntek                                 | 9         | 2.08%   |
| Z-Star Microelectronics                | 8         | 1.85%   |
| Microsoft                              | 6         | 1.39%   |
| Alcor Micro                            | 6         | 1.39%   |
| Silicon Motion                         | 5         | 1.16%   |
| Luxvisions Innotech Limited            | 5         | 1.16%   |
| Apple                                  | 4         | 0.93%   |
| Samsung Electronics                    | 3         | 0.69%   |
| Ricoh                                  | 2         | 0.46%   |
| Lenovo                                 | 2         | 0.46%   |
| Importek                               | 2         | 0.46%   |
| Hewlett-Packard                        | 2         | 0.46%   |
| Creative Technology                    | 2         | 0.46%   |
| Alpha Imaging Technology               | 2         | 0.46%   |
| Unknown                                | 1         | 0.23%   |
| Sunplus Technology                     | 1         | 0.23%   |
| Sonix Technology                       | 1         | 0.23%   |
| Razer USA                              | 1         | 0.23%   |
| Primax Electronics                     | 1         | 0.23%   |
| Pixart Imaging                         | 1         | 0.23%   |
| Google                                 | 1         | 0.23%   |
| Genesys Logic                          | 1         | 0.23%   |
| Generalplus Technology                 | 1         | 0.23%   |
| GEMBIRD                                | 1         | 0.23%   |
| Divio                                  | 1         | 0.23%   |
| Aveo Technology                        | 1         | 0.23%   |
| Arkmicro Technologies                  | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 21        | 4.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 19        | 4.4%    |
| IMC Networks Integrated Camera                                           | 15        | 3.47%   |
| Chicony HD Webcam                                                        | 14        | 3.24%   |
| Microdia Integrated_Webcam_HD                                            | 10        | 2.31%   |
| Realtek Integrated_Webcam_HD                                             | 8         | 1.85%   |
| Sunplus Integrated_Webcam_HD                                             | 7         | 1.62%   |
| Realtek Lenovo EasyCamera                                                | 7         | 1.62%   |
| Acer SunplusIT Integrated Camera                                         | 7         | 1.62%   |
| Chicony USB 2.0 Camera                                                   | 6         | 1.39%   |
| Acer Lenovo EasyCamera                                                   | 6         | 1.39%   |
| Acer Integrated Camera                                                   | 6         | 1.39%   |
| Chicony TOSHIBA Web Camera - HD                                          | 5         | 1.16%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 5         | 1.16%   |
| Chicony HD WebCam (Asus N-series)                                        | 5         | 1.16%   |
| Quanta HD Webcam                                                         | 4         | 0.93%   |
| Microdia Integrated Webcam                                               | 4         | 0.93%   |
| Logitech Webcam C270                                                     | 4         | 0.93%   |
| Lite-On Integrated Camera                                                | 4         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 4         | 0.93%   |
| Chicony Lenovo EasyCamera                                                | 4         | 0.93%   |
| Z-Star Venus USB2.0 Camera                                               | 3         | 0.69%   |
| Z-Star A4 TECH HD PC Camera                                              | 3         | 0.69%   |
| Syntek Integrated Camera                                                 | 3         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 3         | 0.69%   |
| Sunplus Laptop Integrated Webcam HD                                      | 3         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                                             | 3         | 0.69%   |
| Samsung Galaxy A5 (MTP)                                                  | 3         | 0.69%   |
| Realtek EasyCamera                                                       | 3         | 0.69%   |
| Quanta HP TrueVision HD Camera                                           | 3         | 0.69%   |
| Quanta HP HD Camera                                                      | 3         | 0.69%   |
| Microsoft LifeCam HD-3000                                                | 3         | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 0.69%   |
| Microdia Dell Integrated HD Webcam                                       | 3         | 0.69%   |
| Microdia Camera                                                          | 3         | 0.69%   |
| Lite-On TOSHIBA Web Camera - HD                                          | 3         | 0.69%   |
| Lite-On HP HD Webcam                                                     | 3         | 0.69%   |
| IMC Networks UVC VGA Webcam                                              | 3         | 0.69%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 0.69%   |
| Chicony Integrated Camera (1280x720@30)                                  | 3         | 0.69%   |
| Chicony HP Webcam [2 MP Macro]                                           | 3         | 0.69%   |
| Chicony HP HD Webcam [Fixed]                                             | 3         | 0.69%   |
| Chicony HP HD Webcam                                                     | 3         | 0.69%   |
| Chicony FJ Camera                                                        | 3         | 0.69%   |
| Chicony CKF7063 Webcam (HP)                                              | 3         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.69%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 3         | 0.69%   |
| Alcor Micro Acer Integrated Webcam                                       | 3         | 0.69%   |
| Acer HD Webcam                                                           | 3         | 0.69%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 0.46%   |
| Suyin HP TrueVision HD Integrated Webcam                                 | 2         | 0.46%   |
| Suyin Asus Integrated Webcam                                             | 2         | 0.46%   |
| Sunplus HD WebCam                                                        | 2         | 0.46%   |
| Sunplus Dell HD Webcam                                                   | 2         | 0.46%   |
| Silicon Motion WebCam SC-0311139N                                        | 2         | 0.46%   |
| Realtek USB2.0 HD UVC WebCam                                             | 2         | 0.46%   |
| Realtek Integrated Webcam HD                                             | 2         | 0.46%   |
| Realtek HP Truevision HD integrated webcam                               | 2         | 0.46%   |
| Realtek HD WebCam                                                        | 2         | 0.46%   |
| Quanta VGA WebCam                                                        | 2         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 41.38%  |
| Synaptics                  | 21        | 24.14%  |
| AuthenTec                  | 11        | 12.64%  |
| Shenzhen Goodix Technology | 6         | 6.9%    |
| Elan Microelectronics      | 5         | 5.75%   |
| Upek                       | 4         | 4.6%    |
| LighTuning Technology      | 3         | 3.45%   |
| STMicroelectronics         | 1         | 1.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 11.49%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 10.34%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 5.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 5.75%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 4.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 4.6%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 4.6%    |
| AuthenTec AES2810                                                          | 4         | 4.6%    |
| Unknown                                                                    | 4         | 4.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.45%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.3%    |
| Validity Sensors VFS491                                                    | 2         | 2.3%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.3%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.3%    |
| Elan ELAN:Fingerprint                                                      | 2         | 2.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.3%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.15%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.15%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 1.15%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.15%   |
| AuthenTec AES1600                                                          | 1         | 1.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 19        | 35.19%  |
| Alcor Micro           | 17        | 31.48%  |
| O2 Micro              | 5         | 9.26%   |
| Lenovo                | 4         | 7.41%   |
| Upek                  | 3         | 5.56%   |
| SCM Microsystems      | 2         | 3.7%    |
| OmniKey               | 2         | 3.7%    |
| Advanced Card Systems | 2         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 31.48%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 9.26%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 7.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.56%   |
| Broadcom 5880                                                                | 3         | 5.56%   |
| Broadcom 58200                                                               | 3         | 5.56%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 3.7%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.85%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.85%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 499       | 67.62%  |
| 1     | 187       | 25.34%  |
| 2     | 48        | 6.5%    |
| 3     | 3         | 0.41%   |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 87        | 31.29%  |
| Graphics card            | 56        | 20.14%  |
| Chipcard                 | 45        | 16.19%  |
| Net/wireless             | 21        | 7.55%   |
| Multimedia controller    | 14        | 5.04%   |
| Bluetooth                | 11        | 3.96%   |
| Unassigned class         | 8         | 2.88%   |
| Storage                  | 7         | 2.52%   |
| Communication controller | 7         | 2.52%   |
| Camera                   | 6         | 2.16%   |
| Card reader              | 4         | 1.44%   |
| Net/ethernet             | 3         | 1.08%   |
| Firewire controller      | 3         | 1.08%   |
| Sound                    | 2         | 0.72%   |
| Modem                    | 2         | 0.72%   |
| Storage/ata              | 1         | 0.36%   |
| Flash memory             | 1         | 0.36%   |


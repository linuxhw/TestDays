Linux in Bulgaria - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

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

Total: 722

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 14-bf0xx    | [54c42c649d](https://linux-hardware.org/?probe=54c42c649d) | Jul 24, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Toshiba       | PORTEGE Z930                | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [d660c2066c](https://linux-hardware.org/?probe=d660c2066c) | Jun 16, 2022 |
| HP            | ProBook 450 G3              | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| HP            | ProBook 450 G0              | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| HP            | Compaq 6730s                | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [8adba273fb](https://linux-hardware.org/?probe=8adba273fb) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [bb07dfbc56](https://linux-hardware.org/?probe=bb07dfbc56) | May 21, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Dell          | XPS 15 9570                 | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Acer          | Aspire E5-571               | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| ASUSTek       | X540LJ                      | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Toshiba       | Satellite C650              | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Dell          | Precision M6800             | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| MSI           | Modern 15 A4M               | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| HP            | ProBook 455 G7              | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Dell          | Precision M4600             | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Dell          | Inspiron 7559               | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASUSTek       | N551VW                      | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Dell          | Latitude E6330              | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| HP            | 250 G6 Notebook PC          | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| Toshiba       | Satellite A200              | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| HP            | Notebook                    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| Acer          | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| HP            | ProBook 4540s               | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| HP            | EliteBook 8460p             | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| HP            | Pavilion dv7                | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Acer          | Aspire A515-52G             | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| Acer          | Extensa 5630                | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| HP            | EliteBook 850 G5            | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| AMI           | Cherry Trail CR             | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | ProBook 6450b               | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Lenovo        | V15-ADA 82C7                | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| Acer          | Aspire V3-571G              | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Dell          | Latitude 5410               | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Acer          | Extensa 5630                | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Dell          | Studio 1747                 | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| ASUSTek       | GL553VE                     | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| Dell          | Studio 1535                 | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| HP            | EliteBook 8460p             | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Lenovo        | ThinkPad T61 765912G        | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| HP            | EliteBook 850 G5            | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| HP            | Notebook                    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| Lenovo        | ThinkPad X230 232425U       | [69e5ab7b60](https://linux-hardware.org/?probe=69e5ab7b60) | Apr 24, 2021 |
| Dell          | Vostro 3580                 | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Dell          | Vostro 3558                 | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Acer          | Nitro AN515-43              | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| Dell          | Latitude E6330              | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| Dell          | Inspiron MM061              | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| Dell          | Inspiron 3584               | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| ASUSTek       | G752VL                      | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Toshiba       | TECRA A11                   | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| Dell          | Vostro 3580                 | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| Dell          | Vostro 3580                 | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| Apple         | MacBook4,1                  | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| HP            | Laptop 15-da0xxx            | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| MSI           | GP60 2PE                    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| HP            | EliteBook 850 G5            | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Packard Be... | EasyNote TK87               | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Dell          | Latitude E6410              | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| Toshiba       | Satellite C50-A-19T         | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Apple         | MacBook4,1                  | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Dell          | Latitude E5430 non-vPro     | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Apple         | MacBook4,1                  | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| HP            | EliteBook 8560p             | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| Dell          | Latitude 5591               | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| Dell          | Inspiron N5110              | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| ASUSTek       | G551JM                      | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| HP            | ProBook 6470b               | [18f5fab938](https://linux-hardware.org/?probe=18f5fab938) | Oct 31, 2020 |
| Dell          | Vostro 3580                 | [a0e40c6f16](https://linux-hardware.org/?probe=a0e40c6f16) | Oct 29, 2020 |
| ASUSTek       | X541NA                      | [a4497b52bb](https://linux-hardware.org/?probe=a4497b52bb) | Oct 28, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | [4643cfe86d](https://linux-hardware.org/?probe=4643cfe86d) | Oct 27, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | [da5ad20c60](https://linux-hardware.org/?probe=da5ad20c60) | Oct 27, 2020 |
| Dell          | Latitude 5480               | [4191db79b7](https://linux-hardware.org/?probe=4191db79b7) | Oct 25, 2020 |
| Toshiba       | Satellite S70-B             | [a6521e505a](https://linux-hardware.org/?probe=a6521e505a) | Oct 25, 2020 |
| Lenovo        | G50-80 80E5                 | [89f32e3856](https://linux-hardware.org/?probe=89f32e3856) | Oct 23, 2020 |
| ASUSTek       | N551VW                      | [76852e9990](https://linux-hardware.org/?probe=76852e9990) | Oct 22, 2020 |
| Lenovo        | G570 20079                  | [74b57e7887](https://linux-hardware.org/?probe=74b57e7887) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a1a02fe851](https://linux-hardware.org/?probe=a1a02fe851) | Oct 18, 2020 |
| Dell          | Latitude E5430 non-vPro     | [dd68c7b3f6](https://linux-hardware.org/?probe=dd68c7b3f6) | Oct 18, 2020 |
| Toshiba       | Satellite P300              | [fdc8cb1b11](https://linux-hardware.org/?probe=fdc8cb1b11) | Oct 16, 2020 |
| Lenovo        | Yoga 2 11 20428             | [f5c8360ae3](https://linux-hardware.org/?probe=f5c8360ae3) | Oct 15, 2020 |
| Lenovo        | G50-80 80E5                 | [3f72e0309a](https://linux-hardware.org/?probe=3f72e0309a) | Oct 15, 2020 |
| Lenovo        | G570 20079                  | [ba66ad5205](https://linux-hardware.org/?probe=ba66ad5205) | Oct 12, 2020 |
| Lenovo        | G570 20079                  | [5e14548b50](https://linux-hardware.org/?probe=5e14548b50) | Oct 12, 2020 |
| HP            | EliteBook 8560p             | [bbae413f9c](https://linux-hardware.org/?probe=bbae413f9c) | Oct 10, 2020 |
| ASUSTek       | K53U                        | [59444922e7](https://linux-hardware.org/?probe=59444922e7) | Oct 10, 2020 |
| ASUSTek       | K53U                        | [5c5b3815f7](https://linux-hardware.org/?probe=5c5b3815f7) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [25fb29514f](https://linux-hardware.org/?probe=25fb29514f) | Oct 10, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Acer          | Aspire V3-571G              | [86c3c25832](https://linux-hardware.org/?probe=86c3c25832) | Oct 05, 2020 |
| HP            | 250 G3                      | [ab75ccc4f8](https://linux-hardware.org/?probe=ab75ccc4f8) | Oct 02, 2020 |
| Dell          | Inspiron 3583               | [419cd76be1](https://linux-hardware.org/?probe=419cd76be1) | Oct 01, 2020 |
| Acer          | Aspire 5738                 | [18199ffdaf](https://linux-hardware.org/?probe=18199ffdaf) | Sep 30, 2020 |
| Dell          | G7 7588                     | [0d38edaf0c](https://linux-hardware.org/?probe=0d38edaf0c) | Sep 28, 2020 |
| Toshiba       | Satellite P300              | [33020554c0](https://linux-hardware.org/?probe=33020554c0) | Sep 27, 2020 |
| HP            | EliteBook 8470p             | [e330dd752b](https://linux-hardware.org/?probe=e330dd752b) | Sep 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Nitro AN515-44              | [18afb6b15d](https://linux-hardware.org/?probe=18afb6b15d) | Sep 22, 2020 |
| Acer          | Nitro AN515-44              | [c078093e0f](https://linux-hardware.org/?probe=c078093e0f) | Sep 22, 2020 |
| HP            | Compaq tc4400 (RH489ES#A... | [c0305edfae](https://linux-hardware.org/?probe=c0305edfae) | Sep 20, 2020 |
| ASUSTek       | K50C                        | [d4e11f2289](https://linux-hardware.org/?probe=d4e11f2289) | Sep 18, 2020 |
| Acer          | Extensa 5630                | [9040e8e334](https://linux-hardware.org/?probe=9040e8e334) | Sep 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [a66f1b519a](https://linux-hardware.org/?probe=a66f1b519a) | Sep 10, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| Lenovo        | ThinkPad X250 20CLS2YH00    | [cee4231640](https://linux-hardware.org/?probe=cee4231640) | Aug 29, 2020 |
| Fujitsu       | LIFEBOOK E752               | [9820c3c8bd](https://linux-hardware.org/?probe=9820c3c8bd) | Aug 28, 2020 |
| Dell          | Precision M4800             | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| Dell          | Precision M4800             | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| HP            | 250 G3                      | [ff5c3ce273](https://linux-hardware.org/?probe=ff5c3ce273) | Aug 19, 2020 |
| HP            | EliteBook 8560w             | [bf7ae9d5bf](https://linux-hardware.org/?probe=bf7ae9d5bf) | Aug 19, 2020 |
| HP            | 250 G3                      | [01f2866b5c](https://linux-hardware.org/?probe=01f2866b5c) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [1619b6bb6c](https://linux-hardware.org/?probe=1619b6bb6c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [18c07b157f](https://linux-hardware.org/?probe=18c07b157f) | Jul 29, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [8051286600](https://linux-hardware.org/?probe=8051286600) | Jul 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06120056c3](https://linux-hardware.org/?probe=06120056c3) | Jul 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8d593715c](https://linux-hardware.org/?probe=e8d593715c) | Jul 25, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [42fc06b0e4](https://linux-hardware.org/?probe=42fc06b0e4) | Jul 23, 2020 |
| Packard Be... | DOTS E2                     | [223cceb869](https://linux-hardware.org/?probe=223cceb869) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | [699033745c](https://linux-hardware.org/?probe=699033745c) | Jul 19, 2020 |
| Acer          | E5-575G                     | [9fb1e1bee4](https://linux-hardware.org/?probe=9fb1e1bee4) | Jul 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee5e7f9151](https://linux-hardware.org/?probe=ee5e7f9151) | Jul 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [968247c419](https://linux-hardware.org/?probe=968247c419) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c1fb882fc5](https://linux-hardware.org/?probe=c1fb882fc5) | Jul 17, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ac0d845ddb](https://linux-hardware.org/?probe=ac0d845ddb) | Jul 13, 2020 |
| ASUSTek       | X510UQR                     | [54f20878cf](https://linux-hardware.org/?probe=54f20878cf) | Jul 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| Fujitsu Si... | AMILO L Series              | [33762202ef](https://linux-hardware.org/?probe=33762202ef) | Jul 01, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [9b54e3f16c](https://linux-hardware.org/?probe=9b54e3f16c) | Jun 30, 2020 |
| Dell          | Latitude E6410              | [79c1af2581](https://linux-hardware.org/?probe=79c1af2581) | Jun 29, 2020 |
| Acer          | Swift SF314-57G             | [9bd6123d76](https://linux-hardware.org/?probe=9bd6123d76) | Jun 25, 2020 |
| Toshiba       | Satellite C55-A-1HL         | [c6d6bb3ba1](https://linux-hardware.org/?probe=c6d6bb3ba1) | Jun 18, 2020 |
| Toshiba       | Satellite C55-A-1HL         | [d16857f500](https://linux-hardware.org/?probe=d16857f500) | Jun 17, 2020 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [7a3bd1d810](https://linux-hardware.org/?probe=7a3bd1d810) | Jun 10, 2020 |
| Acer          | Nitro AN515-43              | [65f523b6f2](https://linux-hardware.org/?probe=65f523b6f2) | Jun 06, 2020 |
| Acer          | Nitro AN515-43              | [c8ddcb0ec8](https://linux-hardware.org/?probe=c8ddcb0ec8) | Jun 06, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d23bc12452](https://linux-hardware.org/?probe=d23bc12452) | Jun 04, 2020 |
| HP            | 250 G3                      | [99be1919b2](https://linux-hardware.org/?probe=99be1919b2) | Jun 01, 2020 |
| Toshiba       | Satellite P300              | [8eb9fa72de](https://linux-hardware.org/?probe=8eb9fa72de) | May 31, 2020 |
| Lenovo        | G505 20240                  | [6860a03dd0](https://linux-hardware.org/?probe=6860a03dd0) | May 31, 2020 |
| HP            | 250 G3                      | [a4e1d1f904](https://linux-hardware.org/?probe=a4e1d1f904) | May 29, 2020 |
| Lenovo        | ThinkPad T495 20NJ0010BM    | [6974ca5761](https://linux-hardware.org/?probe=6974ca5761) | May 29, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [edcc0b8c05](https://linux-hardware.org/?probe=edcc0b8c05) | May 29, 2020 |
| ASUSTek       | X540LJ                      | [67a3981fe5](https://linux-hardware.org/?probe=67a3981fe5) | May 27, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| ASUSTek       | X705UNR                     | [015957a390](https://linux-hardware.org/?probe=015957a390) | May 22, 2020 |
| HP            | ProBook 6460b               | [babf988605](https://linux-hardware.org/?probe=babf988605) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | EliteBook 840 G1            | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33722345b4](https://linux-hardware.org/?probe=33722345b4) | May 13, 2020 |
| HP            | 255 G2                      | [ad9ef87735](https://linux-hardware.org/?probe=ad9ef87735) | May 13, 2020 |
| Acer          | Aspire 5742G                | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| HP            | ProBook 450 G0              | [88fc8f3bc8](https://linux-hardware.org/?probe=88fc8f3bc8) | May 13, 2020 |
| Acer          | Aspire 5742G                | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [715f4fa65b](https://linux-hardware.org/?probe=715f4fa65b) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [96cd96c818](https://linux-hardware.org/?probe=96cd96c818) | May 12, 2020 |
| HP            | ProBook 4710s               | [b2680d0881](https://linux-hardware.org/?probe=b2680d0881) | May 11, 2020 |
| HP            | EliteBook 840 G1            | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Acer          | Nitro AN515-43              | [6da190e95d](https://linux-hardware.org/?probe=6da190e95d) | May 10, 2020 |
| HP            | 255 G2                      | [ee5dcad518](https://linux-hardware.org/?probe=ee5dcad518) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Dell          | Latitude 7490               | [94b949eb90](https://linux-hardware.org/?probe=94b949eb90) | May 08, 2020 |
| Acer          | E5-575G                     | [4de3c815fd](https://linux-hardware.org/?probe=4de3c815fd) | May 08, 2020 |
| HP            | EliteBook 820 G2            | [3b379abf6a](https://linux-hardware.org/?probe=3b379abf6a) | May 07, 2020 |
| HP            | EliteBook 840 G1            | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| HP            | 255 G2                      | [162f37494e](https://linux-hardware.org/?probe=162f37494e) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ea793cbae5](https://linux-hardware.org/?probe=ea793cbae5) | May 06, 2020 |
| Dell          | Latitude E4300              | [8b26d2727c](https://linux-hardware.org/?probe=8b26d2727c) | May 06, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [cbcdbbc816](https://linux-hardware.org/?probe=cbcdbbc816) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [72e18e38ce](https://linux-hardware.org/?probe=72e18e38ce) | May 04, 2020 |
| HP            | Pavilion Notebook           | [35d925dbae](https://linux-hardware.org/?probe=35d925dbae) | May 04, 2020 |
| Dell          | Inspiron 7577               | [02c7c61130](https://linux-hardware.org/?probe=02c7c61130) | May 03, 2020 |
| Dell          | Inspiron 7577               | [d987f6c242](https://linux-hardware.org/?probe=d987f6c242) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [c3b3575e58](https://linux-hardware.org/?probe=c3b3575e58) | May 02, 2020 |
| ASUSTek       | G771JW                      | [77202c9853](https://linux-hardware.org/?probe=77202c9853) | May 02, 2020 |
| HP            | ProBook 450 G0              | [f74dab71c3](https://linux-hardware.org/?probe=f74dab71c3) | May 01, 2020 |
| HP            | ProBook 450 G0              | [7ac5247653](https://linux-hardware.org/?probe=7ac5247653) | May 01, 2020 |
| Acer          | Aspire 3830G                | [1af95987d0](https://linux-hardware.org/?probe=1af95987d0) | Apr 26, 2020 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [2dde18f51f](https://linux-hardware.org/?probe=2dde18f51f) | Apr 24, 2020 |
| ASUSTek       | N551VW                      | [2d93805421](https://linux-hardware.org/?probe=2d93805421) | Apr 23, 2020 |
| ASUSTek       | N551VW                      | [155a39180a](https://linux-hardware.org/?probe=155a39180a) | Apr 23, 2020 |
| HP            | 250 G7 Notebook PC          | [28fa6e8b6e](https://linux-hardware.org/?probe=28fa6e8b6e) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [73f401be06](https://linux-hardware.org/?probe=73f401be06) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [562403e85f](https://linux-hardware.org/?probe=562403e85f) | Apr 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee479d0e5d](https://linux-hardware.org/?probe=ee479d0e5d) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [a78b041d0c](https://linux-hardware.org/?probe=a78b041d0c) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fbfdc3b5e3](https://linux-hardware.org/?probe=fbfdc3b5e3) | Apr 20, 2020 |
| Sony          | VPCEB4L1E                   | [f1a3807b60](https://linux-hardware.org/?probe=f1a3807b60) | Apr 20, 2020 |
| Compal        | HEL80I                      | [41fd098e10](https://linux-hardware.org/?probe=41fd098e10) | Apr 20, 2020 |
| HP            | 250 G7 Notebook PC          | [6b8e555d43](https://linux-hardware.org/?probe=6b8e555d43) | Apr 18, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f3b92c302c](https://linux-hardware.org/?probe=f3b92c302c) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | [d1e3e7d629](https://linux-hardware.org/?probe=d1e3e7d629) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | [a9b4abdd56](https://linux-hardware.org/?probe=a9b4abdd56) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | [43f93a43d6](https://linux-hardware.org/?probe=43f93a43d6) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | [20b4b0a6ad](https://linux-hardware.org/?probe=20b4b0a6ad) | Apr 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5fc32fd27b](https://linux-hardware.org/?probe=5fc32fd27b) | Apr 12, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Inspiron 3521               | [53b2f1863a](https://linux-hardware.org/?probe=53b2f1863a) | Apr 07, 2020 |
| Acer          | Nitro AN515-43              | [6b0efa548b](https://linux-hardware.org/?probe=6b0efa548b) | Apr 04, 2020 |
| HP            | ProBook 4540s               | [e3c52f3d96](https://linux-hardware.org/?probe=e3c52f3d96) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [d018206f33](https://linux-hardware.org/?probe=d018206f33) | Mar 31, 2020 |
| HP            | EliteBook 8560w             | [5038965b3b](https://linux-hardware.org/?probe=5038965b3b) | Mar 30, 2020 |
| HP            | ProBook 4540s               | [6b9b373a1f](https://linux-hardware.org/?probe=6b9b373a1f) | Mar 30, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [99865fe49f](https://linux-hardware.org/?probe=99865fe49f) | Mar 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c7eda36111](https://linux-hardware.org/?probe=c7eda36111) | Mar 28, 2020 |
| Acer          | Predator G3-572             | [9434c59ae1](https://linux-hardware.org/?probe=9434c59ae1) | Mar 28, 2020 |
| Acer          | Predator G3-572             | [11828122f2](https://linux-hardware.org/?probe=11828122f2) | Mar 28, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [edf4388f6a](https://linux-hardware.org/?probe=edf4388f6a) | Mar 26, 2020 |
| HP            | 620                         | [633afcbbef](https://linux-hardware.org/?probe=633afcbbef) | Mar 25, 2020 |
| HP            | 620                         | [8487590fa2](https://linux-hardware.org/?probe=8487590fa2) | Mar 25, 2020 |
| HP            | 250 G7 Notebook PC          | [c63e1ec4fd](https://linux-hardware.org/?probe=c63e1ec4fd) | Mar 23, 2020 |
| Toshiba       | Satellite L50-C             | [b343a21e42](https://linux-hardware.org/?probe=b343a21e42) | Mar 17, 2020 |
| Lenovo        | ThinkPad T470p 20J6S0A30... | [b02f5ffeeb](https://linux-hardware.org/?probe=b02f5ffeeb) | Mar 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [14544480a5](https://linux-hardware.org/?probe=14544480a5) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ccc20cb679](https://linux-hardware.org/?probe=ccc20cb679) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [7b2e2dc41d](https://linux-hardware.org/?probe=7b2e2dc41d) | Mar 15, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [252c5a9ab3](https://linux-hardware.org/?probe=252c5a9ab3) | Mar 15, 2020 |
| ASUSTek       | GL553VE                     | [810b827dfe](https://linux-hardware.org/?probe=810b827dfe) | Mar 15, 2020 |
| Lenovo        | ThinkPad E480 20KN004TBM    | [13768f8615](https://linux-hardware.org/?probe=13768f8615) | Mar 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4c0f104328](https://linux-hardware.org/?probe=4c0f104328) | Mar 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [4587e48bf4](https://linux-hardware.org/?probe=4587e48bf4) | Mar 11, 2020 |
| HP            | Unknown                     | [453696ff5e](https://linux-hardware.org/?probe=453696ff5e) | Mar 04, 2020 |
| Dell          | G3 3579                     | [12a87598d6](https://linux-hardware.org/?probe=12a87598d6) | Mar 02, 2020 |
| HP            | Unknown                     | [f8a7212a74](https://linux-hardware.org/?probe=f8a7212a74) | Feb 26, 2020 |
| Acer          | Aspire 5738                 | [d008370d87](https://linux-hardware.org/?probe=d008370d87) | Feb 24, 2020 |
| HP            | Laptop 15-dw0xxx            | [9c5def065e](https://linux-hardware.org/?probe=9c5def065e) | Feb 22, 2020 |
| Dell          | Latitude 5401               | [76f6ff2608](https://linux-hardware.org/?probe=76f6ff2608) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | [4df7386234](https://linux-hardware.org/?probe=4df7386234) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | [d8f25b08f2](https://linux-hardware.org/?probe=d8f25b08f2) | Feb 16, 2020 |
| Lenovo        | ThinkPad T560 20FJS1YD00    | [b379bf7743](https://linux-hardware.org/?probe=b379bf7743) | Feb 15, 2020 |
| Acer          | Aspire 5541                 | [6bf6d1c16b](https://linux-hardware.org/?probe=6bf6d1c16b) | Feb 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [60281c26f1](https://linux-hardware.org/?probe=60281c26f1) | Feb 14, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [3977fb1ddb](https://linux-hardware.org/?probe=3977fb1ddb) | Feb 12, 2020 |
| ASUSTek       | X501A                       | [9e5a342bac](https://linux-hardware.org/?probe=9e5a342bac) | Feb 10, 2020 |
| Dell          | Inspiron 3584               | [c080de1bad](https://linux-hardware.org/?probe=c080de1bad) | Feb 03, 2020 |
| Toshiba       | Satellite L40               | [75079b3cba](https://linux-hardware.org/?probe=75079b3cba) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | [b3e528be2c](https://linux-hardware.org/?probe=b3e528be2c) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | [8db2dfbc60](https://linux-hardware.org/?probe=8db2dfbc60) | Jan 29, 2020 |
| Lenovo        | ThinkPad X220 4291B24       | [ce7dd499a5](https://linux-hardware.org/?probe=ce7dd499a5) | Jan 24, 2020 |
| Toshiba       | Satellite L300              | [f5faa63427](https://linux-hardware.org/?probe=f5faa63427) | Jan 12, 2020 |
| ASUSTek       | K55VM                       | [c1595f145d](https://linux-hardware.org/?probe=c1595f145d) | Jan 11, 2020 |
| Dell          | Inspiron 5520               | [601d03392f](https://linux-hardware.org/?probe=601d03392f) | Jan 05, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [3f4d79ea3b](https://linux-hardware.org/?probe=3f4d79ea3b) | Jan 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [aa34232c5a](https://linux-hardware.org/?probe=aa34232c5a) | Jan 01, 2020 |
| ASUSTek       | X540NV                      | [6bca5f0ae4](https://linux-hardware.org/?probe=6bca5f0ae4) | Jan 01, 2020 |
| Lenovo        | ThinkPad T420 4236A87       | [353a1db8ac](https://linux-hardware.org/?probe=353a1db8ac) | Dec 31, 2019 |
| TUXEDO        | Unknown                     | [8393427822](https://linux-hardware.org/?probe=8393427822) | Dec 27, 2019 |
| HP            | 530 Notebook PC(KP479AA#... | [3e6684e155](https://linux-hardware.org/?probe=3e6684e155) | Dec 27, 2019 |
| ASUSTek       | X541NA                      | [f885d0ee5f](https://linux-hardware.org/?probe=f885d0ee5f) | Dec 23, 2019 |
| Dell          | Inspiron 5482               | [85bb9ecf3b](https://linux-hardware.org/?probe=85bb9ecf3b) | Dec 20, 2019 |
| Lenovo        | B51-30 80LK                 | [32d296fee0](https://linux-hardware.org/?probe=32d296fee0) | Dec 19, 2019 |
| Dell          | Inspiron N5010              | [d5fec65df9](https://linux-hardware.org/?probe=d5fec65df9) | Dec 13, 2019 |
| MSI           | GS65 Stealth Thin 8RE       | [a9a218f5dd](https://linux-hardware.org/?probe=a9a218f5dd) | Dec 06, 2019 |
| Dell          | Studio 1747                 | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Acer          | Aspire E5-572G              | [0c710c33f6](https://linux-hardware.org/?probe=0c710c33f6) | Dec 04, 2019 |
| Fujitsu Si... | AMILO Xi 3650               | [87afd7dd02](https://linux-hardware.org/?probe=87afd7dd02) | Dec 04, 2019 |
| Dell          | Studio 1747                 | [2daf1225e6](https://linux-hardware.org/?probe=2daf1225e6) | Dec 04, 2019 |
| Dell          | Studio 1747                 | [dfba5a95c8](https://linux-hardware.org/?probe=dfba5a95c8) | Dec 04, 2019 |
| Dell          | Studio 1747                 | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | [781e93ad34](https://linux-hardware.org/?probe=781e93ad34) | Nov 26, 2019 |
| Dell          | Latitude E5530 non-vPro     | [9081234810](https://linux-hardware.org/?probe=9081234810) | Nov 22, 2019 |
| Dell          | Latitude E5530 non-vPro     | [f61b57f6fc](https://linux-hardware.org/?probe=f61b57f6fc) | Nov 22, 2019 |
| ASUSTek       | X505BP                      | [a881fdcf1b](https://linux-hardware.org/?probe=a881fdcf1b) | Nov 21, 2019 |
| Gigabyte      | W348M                       | [0db51928b9](https://linux-hardware.org/?probe=0db51928b9) | Oct 29, 2019 |
| Dell          | Latitude E6410              | [2888ece276](https://linux-hardware.org/?probe=2888ece276) | Oct 27, 2019 |
| Dell          | G7 7588                     | [2479b39b58](https://linux-hardware.org/?probe=2479b39b58) | Oct 27, 2019 |
| Dell          | Inspiron 3580               | [29ff86014c](https://linux-hardware.org/?probe=29ff86014c) | Oct 22, 2019 |
| Dell          | Inspiron 3580               | [8e4e877bc9](https://linux-hardware.org/?probe=8e4e877bc9) | Oct 22, 2019 |
| ASUSTek       | N53SN                       | [b41d353d8b](https://linux-hardware.org/?probe=b41d353d8b) | Oct 18, 2019 |
| Lenovo        | G500 20236                  | [cc14742c63](https://linux-hardware.org/?probe=cc14742c63) | Oct 16, 2019 |
| Lenovo        | G500 20236                  | [592a40c6d4](https://linux-hardware.org/?probe=592a40c6d4) | Oct 13, 2019 |
| Dell          | G3 3579                     | [d04a01d41c](https://linux-hardware.org/?probe=d04a01d41c) | Oct 10, 2019 |
| Dell          | Latitude E6320              | [0c6c848244](https://linux-hardware.org/?probe=0c6c848244) | Oct 09, 2019 |
| HP            | ProBook 470 G0              | [d04f4a23f0](https://linux-hardware.org/?probe=d04f4a23f0) | Oct 07, 2019 |
| Dell          | Latitude E6320              | [0bc384b06e](https://linux-hardware.org/?probe=0bc384b06e) | Oct 06, 2019 |
| Dell          | Latitude E6320              | [59d8f18e3d](https://linux-hardware.org/?probe=59d8f18e3d) | Oct 06, 2019 |
| Dell          | Latitude E6320              | [79c9edf47a](https://linux-hardware.org/?probe=79c9edf47a) | Oct 06, 2019 |
| Dell          | G3 3579                     | [349416fbb3](https://linux-hardware.org/?probe=349416fbb3) | Oct 05, 2019 |
| ASUSTek       | X542UQ                      | [0c0cfccb6f](https://linux-hardware.org/?probe=0c0cfccb6f) | Oct 02, 2019 |
| ASUSTek       | X542UQ                      | [bb0a5f1b8e](https://linux-hardware.org/?probe=bb0a5f1b8e) | Sep 28, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | [e1a5ba64a3](https://linux-hardware.org/?probe=e1a5ba64a3) | Sep 23, 2019 |
| ASUSTek       | N550JK                      | [3a2e4ab12c](https://linux-hardware.org/?probe=3a2e4ab12c) | Sep 18, 2019 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [5c664d23d8](https://linux-hardware.org/?probe=5c664d23d8) | Sep 17, 2019 |
| HP            | Compaq 6715s (GR762ES#AB... | [320661ca9f](https://linux-hardware.org/?probe=320661ca9f) | Sep 16, 2019 |
| Toshiba       | Satellite L855              | [f5d2dffc84](https://linux-hardware.org/?probe=f5d2dffc84) | Sep 13, 2019 |
| ASUSTek       | X542UQ                      | [fca2fc959c](https://linux-hardware.org/?probe=fca2fc959c) | Sep 13, 2019 |
| Notebook      | P17SM-A                     | [6ccaea7ee4](https://linux-hardware.org/?probe=6ccaea7ee4) | Sep 11, 2019 |
| HP            | Pavilion dv6                | [4ddfed675e](https://linux-hardware.org/?probe=4ddfed675e) | Sep 07, 2019 |
| ASUSTek       | K55VD                       | [072fcfd6de](https://linux-hardware.org/?probe=072fcfd6de) | Aug 29, 2019 |
| Dell          | Precision M4600             | [9a70878de0](https://linux-hardware.org/?probe=9a70878de0) | Aug 26, 2019 |
| Dell          | Vostro 3559                 | [0ec7ad0379](https://linux-hardware.org/?probe=0ec7ad0379) | Aug 22, 2019 |
| Fujitsu       | CELSIUS H730                | [69d7eea0f3](https://linux-hardware.org/?probe=69d7eea0f3) | Aug 21, 2019 |
| Fujitsu       | CELSIUS H730                | [896ecfb0f1](https://linux-hardware.org/?probe=896ecfb0f1) | Aug 21, 2019 |
| Fujitsu       | CELSIUS H730                | [f94cbdeb8e](https://linux-hardware.org/?probe=f94cbdeb8e) | Aug 21, 2019 |
| Dell          | Inspiron 5482               | [637995a063](https://linux-hardware.org/?probe=637995a063) | Aug 15, 2019 |
| HP            | Compaq 6830s                | [525e681524](https://linux-hardware.org/?probe=525e681524) | Aug 07, 2019 |
| ASUSTek       | N550JK                      | [8cfc8e44ca](https://linux-hardware.org/?probe=8cfc8e44ca) | Aug 04, 2019 |
| Fujitsu       | LIFEBOOK N532               | [b9a4817612](https://linux-hardware.org/?probe=b9a4817612) | Jul 28, 2019 |
| Medion        | P7648 MD99980               | [ac77e66d3f](https://linux-hardware.org/?probe=ac77e66d3f) | Jul 24, 2019 |
| ASUSTek       | X542UQ                      | [b531eab1de](https://linux-hardware.org/?probe=b531eab1de) | Jul 16, 2019 |
| Lenovo        | G500 20236                  | [06603d3dce](https://linux-hardware.org/?probe=06603d3dce) | Jul 14, 2019 |
| Dell          | Latitude E4300              | [59050a5736](https://linux-hardware.org/?probe=59050a5736) | Jul 10, 2019 |
| Dell          | Inspiron 3551               | [ff1bf9089c](https://linux-hardware.org/?probe=ff1bf9089c) | Jul 08, 2019 |
| Dell          | Inspiron 3551               | [8add5e4718](https://linux-hardware.org/?probe=8add5e4718) | Jul 08, 2019 |
| Acer          | Aspire 5552G                | [e5d4cddd0b](https://linux-hardware.org/?probe=e5d4cddd0b) | Jul 07, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | [1811b66e00](https://linux-hardware.org/?probe=1811b66e00) | Jul 05, 2019 |
| HP            | Pavilion 15                 | [bc7f328871](https://linux-hardware.org/?probe=bc7f328871) | Jul 02, 2019 |
| Pegatron      | A15                         | [754abad872](https://linux-hardware.org/?probe=754abad872) | Jul 01, 2019 |
| Acer          | Aspire A315-31              | [475d99370e](https://linux-hardware.org/?probe=475d99370e) | Jul 01, 2019 |
| ASUSTek       | VivoBook S15 X510UF         | [b95d164f8c](https://linux-hardware.org/?probe=b95d164f8c) | Jun 19, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | [ae491db991](https://linux-hardware.org/?probe=ae491db991) | Jun 15, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7a53859124](https://linux-hardware.org/?probe=7a53859124) | Jun 15, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | [30068f1670](https://linux-hardware.org/?probe=30068f1670) | Jun 09, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c6ced8e5a5](https://linux-hardware.org/?probe=c6ced8e5a5) | Jun 02, 2019 |
| Lenovo        | Unknown                     | [157cdcf284](https://linux-hardware.org/?probe=157cdcf284) | May 26, 2019 |
| ASUSTek       | K73SD                       | [d00a49591e](https://linux-hardware.org/?probe=d00a49591e) | May 22, 2019 |
| Lenovo        | Y520-15IKBM 80YY            | [d814f4eab3](https://linux-hardware.org/?probe=d814f4eab3) | May 21, 2019 |
| Acer          | Aspire VN7-592G             | [5423f5da6b](https://linux-hardware.org/?probe=5423f5da6b) | May 19, 2019 |
| Acer          | Aspire A315-31              | [e19546ffd9](https://linux-hardware.org/?probe=e19546ffd9) | May 12, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [5fa03a3e8f](https://linux-hardware.org/?probe=5fa03a3e8f) | May 07, 2019 |
| Dell          | Latitude E6540              | [a12e80fc14](https://linux-hardware.org/?probe=a12e80fc14) | May 04, 2019 |
| LG Electro... | FS-2A46HS                   | [c71f72f074](https://linux-hardware.org/?probe=c71f72f074) | Apr 27, 2019 |
| LG Electro... | FS-2A46HS                   | [aafcf2ac24](https://linux-hardware.org/?probe=aafcf2ac24) | Apr 27, 2019 |
| ASUSTek       | N551VW                      | [8bdeeb7120](https://linux-hardware.org/?probe=8bdeeb7120) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | [803ca8464c](https://linux-hardware.org/?probe=803ca8464c) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | [01575f8e47](https://linux-hardware.org/?probe=01575f8e47) | Apr 22, 2019 |
| Lenovo        | IdeaPad Z580                | [88ec17f6dc](https://linux-hardware.org/?probe=88ec17f6dc) | Apr 18, 2019 |
| HP            | ProBook 6470b               | [6008fdba9d](https://linux-hardware.org/?probe=6008fdba9d) | Apr 17, 2019 |
| HP            | EliteBook 8740w             | [adfd8e7463](https://linux-hardware.org/?probe=adfd8e7463) | Apr 12, 2019 |
| Lenovo        | G500 20236                  | [f0021f0fdc](https://linux-hardware.org/?probe=f0021f0fdc) | Apr 12, 2019 |
| Dell          | Inspiron 3737               | [86eb821fa9](https://linux-hardware.org/?probe=86eb821fa9) | Apr 11, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | [de1581a896](https://linux-hardware.org/?probe=de1581a896) | Apr 11, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | [092bae147c](https://linux-hardware.org/?probe=092bae147c) | Apr 09, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | [51988ce7c2](https://linux-hardware.org/?probe=51988ce7c2) | Apr 09, 2019 |
| Lenovo        | G500 20236                  | [5be2bd43e2](https://linux-hardware.org/?probe=5be2bd43e2) | Apr 07, 2019 |
| Lenovo        | G580                        | [1b00fafcef](https://linux-hardware.org/?probe=1b00fafcef) | Apr 07, 2019 |
| Acer          | TravelMate P645-SG          | [e6ed7a4f8d](https://linux-hardware.org/?probe=e6ed7a4f8d) | Mar 24, 2019 |
| Lenovo        | ThinkPad X220 42903WG       | [edaa665dea](https://linux-hardware.org/?probe=edaa665dea) | Mar 19, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | [a74f00993b](https://linux-hardware.org/?probe=a74f00993b) | Mar 12, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | [b484a879d4](https://linux-hardware.org/?probe=b484a879d4) | Mar 08, 2019 |
| Lenovo        | G580                        | [2f4b4e326a](https://linux-hardware.org/?probe=2f4b4e326a) | Mar 01, 2019 |
| ASUSTek       | K55A                        | [cbd602db5a](https://linux-hardware.org/?probe=cbd602db5a) | Mar 01, 2019 |
| ASUSTek       | K55A                        | [48f636d07e](https://linux-hardware.org/?probe=48f636d07e) | Mar 01, 2019 |
| ASUSTek       | X541UJ                      | [98740161c5](https://linux-hardware.org/?probe=98740161c5) | Feb 26, 2019 |
| ASUSTek       | X541UJ                      | [0dc58e8846](https://linux-hardware.org/?probe=0dc58e8846) | Feb 26, 2019 |
| Dell          | Latitude E7440              | [c0f66137fc](https://linux-hardware.org/?probe=c0f66137fc) | Feb 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [713a79e7e2](https://linux-hardware.org/?probe=713a79e7e2) | Feb 15, 2019 |
| Lenovo        | ThinkPad E480 20KN004TBM    | [651cb8fea0](https://linux-hardware.org/?probe=651cb8fea0) | Feb 12, 2019 |
| Medion        | E1210                       | [5dfe8d16da](https://linux-hardware.org/?probe=5dfe8d16da) | Jan 26, 2019 |
| ASUSTek       | X705UNR                     | [b9e37eb37f](https://linux-hardware.org/?probe=b9e37eb37f) | Jan 20, 2019 |
| ASUSTek       | X705UNR                     | [45fa0ef0e3](https://linux-hardware.org/?probe=45fa0ef0e3) | Jan 20, 2019 |
| Fujitsu Si... | AMILO Pi 3540               | [7d38422be6](https://linux-hardware.org/?probe=7d38422be6) | Jan 19, 2019 |
| Fujitsu Si... | AMILO Pi 3540               | [9c98fa7c5a](https://linux-hardware.org/?probe=9c98fa7c5a) | Jan 19, 2019 |
| ASUSTek       | GL553VE                     | [1ccc6b1335](https://linux-hardware.org/?probe=1ccc6b1335) | Jan 12, 2019 |
| ASUSTek       | GL553VE                     | [468cd6a626](https://linux-hardware.org/?probe=468cd6a626) | Dec 25, 2018 |
| Lenovo        | ThinkPad E480 20KN004TBM    | [38757f20cd](https://linux-hardware.org/?probe=38757f20cd) | Dec 16, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | [e54f5af29a](https://linux-hardware.org/?probe=e54f5af29a) | Dec 08, 2018 |
| Dell          | Precision M4600             | [812a28db21](https://linux-hardware.org/?probe=812a28db21) | Dec 05, 2018 |
| Dell          | Precision M4600             | [8057a5e7af](https://linux-hardware.org/?probe=8057a5e7af) | Dec 05, 2018 |
| Lenovo        | ThinkPad T530 2429AR7       | [2821650e1b](https://linux-hardware.org/?probe=2821650e1b) | Dec 03, 2018 |
| ASUSTek       | X541NA                      | [bdaeaf5ca2](https://linux-hardware.org/?probe=bdaeaf5ca2) | Nov 30, 2018 |
| Acer          | TravelMate P645-SG          | [b4dc1aeb7a](https://linux-hardware.org/?probe=b4dc1aeb7a) | Nov 25, 2018 |
| ASUSTek       | X541NA                      | [aee08bb40e](https://linux-hardware.org/?probe=aee08bb40e) | Nov 18, 2018 |
| HP            | ProBook 4540s               | [06de7c3363](https://linux-hardware.org/?probe=06de7c3363) | Oct 14, 2018 |
| Lenovo        | ThinkPad W500 4063E94       | [1501370ab2](https://linux-hardware.org/?probe=1501370ab2) | Jun 23, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | [c3e231dcc8](https://linux-hardware.org/?probe=c3e231dcc8) | Jun 16, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | [2f69425a7c](https://linux-hardware.org/?probe=2f69425a7c) | Apr 30, 2018 |
| Lenovo        | G50-45 80E3                 | [cbd88fab14](https://linux-hardware.org/?probe=cbd88fab14) | Feb 18, 2018 |
| HP            | Mini 311-1000               | [82a73faa41](https://linux-hardware.org/?probe=82a73faa41) | Feb 06, 2018 |
| Notebook      | P17SM-A                     | [5231746786](https://linux-hardware.org/?probe=5231746786) | Jan 25, 2018 |
| Lenovo        | ThinkPad X200 2024A11       | [cebad9ea77](https://linux-hardware.org/?probe=cebad9ea77) | Jan 08, 2018 |
| HP            | Mini 311-1000               | [f0cf0539e0](https://linux-hardware.org/?probe=f0cf0539e0) | Jan 04, 2018 |
| Lenovo        | ThinkPad X200 2024A11       | [751eb89800](https://linux-hardware.org/?probe=751eb89800) | Dec 27, 2017 |
| Toshiba       | Satellite L300              | [62a451c290](https://linux-hardware.org/?probe=62a451c290) | Dec 21, 2017 |
| Toshiba       | Satellite Pro R850          | [8f76c37692](https://linux-hardware.org/?probe=8f76c37692) | Dec 11, 2017 |
| HP            | Mini 311-1000               | [53f93e34f5](https://linux-hardware.org/?probe=53f93e34f5) | Nov 30, 2017 |
| ASUSTek       | K53SV                       | [ddd21d12ef](https://linux-hardware.org/?probe=ddd21d12ef) | Nov 28, 2017 |
| Toshiba       | Satellite L300              | [5ff5de6e1c](https://linux-hardware.org/?probe=5ff5de6e1c) | Nov 14, 2017 |
| Lenovo        | G50-45 80E3                 | [150bc63715](https://linux-hardware.org/?probe=150bc63715) | Nov 06, 2017 |
| HP            | Compaq nx7400 (RU430ET#A... | [6d9cfb4cb9](https://linux-hardware.org/?probe=6d9cfb4cb9) | Jul 30, 2017 |
| ASUSTek       | X540LJ                      | [7cd67a8489](https://linux-hardware.org/?probe=7cd67a8489) | Apr 26, 2017 |
| ASUSTek       | X540LJ                      | [f79d8f68ca](https://linux-hardware.org/?probe=f79d8f68ca) | Apr 26, 2017 |
| Acer          | Aspire V5-573G              | [fb0bbb47d3](https://linux-hardware.org/?probe=fb0bbb47d3) | Feb 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 64        | 12.6%   |
| Ubuntu 18.04                 | 50        | 9.84%   |
| OpenMandriva 4.3             | 13        | 2.56%   |
| OpenMandriva 4.2             | 13        | 2.56%   |
| KDE neon 20.04               | 12        | 2.36%   |
| Linux Mint 20.1              | 11        | 2.17%   |
| ROSA R11                     | 10        | 1.97%   |
| Linux Mint 19.3              | 10        | 1.97%   |
| Ubuntu 22.04                 | 9         | 1.77%   |
| Ubuntu 19.04                 | 9         | 1.77%   |
| Linux Mint 20.3              | 9         | 1.77%   |
| Linux Mint 20.2              | 9         | 1.77%   |
| Kubuntu 20.04                | 9         | 1.77%   |
| Xubuntu 20.04                | 8         | 1.57%   |
| ROSA R10                     | 8         | 1.57%   |
| Manjaro                      | 8         | 1.57%   |
| Linux Mint 20                | 8         | 1.57%   |
| Fedora 33                    | 8         | 1.57%   |
| Ubuntu 19.10                 | 7         | 1.38%   |
| Ubuntu 16.04                 | 7         | 1.38%   |
| Arch                         | 7         | 1.38%   |
| Zorin 16                     | 6         | 1.18%   |
| Xubuntu 18.04                | 6         | 1.18%   |
| ROSA R9                      | 6         | 1.18%   |
| LMDE 4                       | 6         | 1.18%   |
| Debian 11                    | 6         | 1.18%   |
| Zorin 15                     | 5         | 0.98%   |
| Pop!_OS 20.10                | 5         | 0.98%   |
| Fedora 35                    | 5         | 0.98%   |
| Fedora 34                    | 5         | 0.98%   |
| Fedora 31                    | 5         | 0.98%   |
| Ubuntu 21.10                 | 4         | 0.79%   |
| ROSA R11.1                   | 4         | 0.79%   |
| Pop!_OS 21.04                | 4         | 0.79%   |
| Debian 10                    | 4         | 0.79%   |
| ArcoLinux Rolling            | 4         | 0.79%   |
| Pop!_OS 20.04                | 3         | 0.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.59%   |
| OpenMandriva 4.50            | 3         | 0.59%   |
| Fedora 36                    | 3         | 0.59%   |
| Fedora 32                    | 3         | 0.59%   |
| Fedora 29                    | 3         | 0.59%   |
| Arch Rolling                 | 3         | 0.59%   |
| Void Linux Rolling           | 2         | 0.39%   |
| Ubuntu 20.10                 | 2         | 0.39%   |
| Ubuntu 18.10                 | 2         | 0.39%   |
| ROSA R8.1                    | 2         | 0.39%   |
| Pop!_OS 22.04                | 2         | 0.39%   |
| Pop!_OS 21.10                | 2         | 0.39%   |
| openSUSE Leap-15.2           | 2         | 0.39%   |
| Manjaro 20.0.3               | 2         | 0.39%   |
| Manjaro 19.0.2               | 2         | 0.39%   |
| KDE neon 18.04               | 2         | 0.39%   |
| Kali 2022.2                  | 2         | 0.39%   |
| Kali 2021.4                  | 2         | 0.39%   |
| Kali 2021.3                  | 2         | 0.39%   |
| Kali 2020.3                  | 2         | 0.39%   |
| Kali 2020.1                  | 2         | 0.39%   |
| Endless 3.9.3                | 2         | 0.39%   |
| Endless 3.9.1                | 2         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 147       | 32.31%  |
| Linux Mint    | 46        | 10.11%  |
| OpenMandriva  | 29        | 6.37%   |
| ROSA          | 27        | 5.93%   |
| Fedora        | 26        | 5.71%   |
| Endless       | 23        | 5.05%   |
| Manjaro       | 17        | 3.74%   |
| Pop!_OS       | 15        | 3.3%    |
| Xubuntu       | 14        | 3.08%   |
| KDE neon      | 14        | 3.08%   |
| Zorin         | 11        | 2.42%   |
| Kubuntu       | 11        | 2.42%   |
| Debian        | 10        | 2.2%    |
| Arch          | 10        | 2.2%    |
| Clear Linux   | 9         | 1.98%   |
| Kali          | 8         | 1.76%   |
| LMDE          | 6         | 1.32%   |
| ArcoLinux     | 6         | 1.32%   |
| openSUSE      | 4         | 0.88%   |
| Lubuntu       | 3         | 0.66%   |
| CentOS        | 3         | 0.66%   |
| Void Linux    | 2         | 0.44%   |
| Elementary    | 2         | 0.44%   |
| Artix         | 2         | 0.44%   |
| Ubuntu Studio | 1         | 0.22%   |
| RHEL          | 1         | 0.22%   |
| Peppermint    | 1         | 0.22%   |
| Parrot        | 1         | 0.22%   |
| Oracle Linux  | 1         | 0.22%   |
| Mageia        | 1         | 0.22%   |
| Gentoo        | 1         | 0.22%   |
| Feren OS      | 1         | 0.22%   |
| EndeavourOS   | 1         | 0.22%   |
| Deepin        | 1         | 0.22%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 13        | 2.34%   |
| 5.10.14-desktop-1omv4002        | 13        | 2.34%   |
| 5.4.0-42-generic                | 10        | 1.8%    |
| 5.4.0-58-generic                | 8         | 1.44%   |
| 5.3.0-28-generic                | 7         | 1.26%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 7         | 1.26%   |
| 5.8.0-14-generic                | 6         | 1.08%   |
| 5.4.0-91-generic                | 5         | 0.9%    |
| 5.4.0-48-generic                | 5         | 0.9%    |
| 5.4.0-29-generic                | 5         | 0.9%    |
| 5.4.0-26-generic                | 5         | 0.9%    |
| 5.9.16-1-MANJARO                | 4         | 0.72%   |
| 5.4.0-77-generic                | 4         | 0.72%   |
| 5.4.0-73-generic                | 4         | 0.72%   |
| 5.4.0-65-generic                | 4         | 0.72%   |
| 5.4.0-47-generic                | 4         | 0.72%   |
| 5.4.0-40-generic                | 4         | 0.72%   |
| 5.4.0-19-generic                | 4         | 0.72%   |
| 5.3.0-53-generic                | 4         | 0.72%   |
| 5.13.0-28-generic               | 4         | 0.72%   |
| 5.13.0-27-generic               | 4         | 0.72%   |
| 5.11.0-41-generic               | 4         | 0.72%   |
| 5.11.0-37-generic               | 4         | 0.72%   |
| 5.0.0-37-generic                | 4         | 0.72%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 0.72%   |
| 4.19.0-8-amd64                  | 4         | 0.72%   |
| 4.15.0-20-generic               | 4         | 0.72%   |
| 5.8.0-63-generic                | 3         | 0.54%   |
| 5.4.0-90-generic                | 3         | 0.54%   |
| 5.4.0-81-generic                | 3         | 0.54%   |
| 5.4.0-74-generic                | 3         | 0.54%   |
| 5.4.0-72-generic                | 3         | 0.54%   |
| 5.4.0-67-generic                | 3         | 0.54%   |
| 5.4.0-56-generic                | 3         | 0.54%   |
| 5.3.0-51-generic                | 3         | 0.54%   |
| 5.3.0-46-generic                | 3         | 0.54%   |
| 5.3.0-42-generic                | 3         | 0.54%   |
| 5.3.0-40-generic                | 3         | 0.54%   |
| 5.13.0-51-generic               | 3         | 0.54%   |
| 5.11.0-44-generic               | 3         | 0.54%   |
| 5.10.0-8-amd64                  | 3         | 0.54%   |
| 5.0.0-32-generic                | 3         | 0.54%   |
| 5.0.0-23-generic                | 3         | 0.54%   |
| 4.18.0-25-generic               | 3         | 0.54%   |
| 4.18.0-12-generic               | 3         | 0.54%   |
| 4.15.0-47-generic               | 3         | 0.54%   |
| 5.9.16-200.fc33.x86_64          | 2         | 0.36%   |
| 5.8.0-kali3-amd64               | 2         | 0.36%   |
| 5.8.0-59-generic                | 2         | 0.36%   |
| 5.8.0-53-generic                | 2         | 0.36%   |
| 5.8.0-50-generic                | 2         | 0.36%   |
| 5.8.0-41-generic                | 2         | 0.36%   |
| 5.6.8-300.fc32.x86_64           | 2         | 0.36%   |
| 5.4.32-generic-2rosa-x86_64     | 2         | 0.36%   |
| 5.4.0-70-generic                | 2         | 0.36%   |
| 5.4.0-52-generic                | 2         | 0.36%   |
| 5.4.0-39-generic                | 2         | 0.36%   |
| 5.4.0-28-generic                | 2         | 0.36%   |
| 5.3.0-29-generic                | 2         | 0.36%   |
| 5.3.0-24-generic                | 2         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 106       | 20.27%  |
| 4.15.0  | 44        | 8.41%   |
| 5.3.0   | 31        | 5.93%   |
| 5.8.0   | 30        | 5.74%   |
| 5.11.0  | 25        | 4.78%   |
| 5.13.0  | 24        | 4.59%   |
| 5.0.0   | 23        | 4.4%    |
| 4.18.0  | 16        | 3.06%   |
| 5.10.14 | 14        | 2.68%   |
| 5.16.7  | 13        | 2.49%   |
| 5.15.0  | 11        | 2.1%    |
| 5.10.0  | 9         | 1.72%   |
| 4.19.0  | 8         | 1.53%   |
| 5.9.16  | 7         | 1.34%   |
| 4.9.20  | 6         | 1.15%   |
| 5.6.8   | 4         | 0.76%   |
| 5.17.5  | 4         | 0.76%   |
| 4.4.0   | 4         | 0.76%   |
| 5.16.0  | 3         | 0.57%   |
| 5.12.14 | 3         | 0.57%   |
| 5.11.12 | 3         | 0.57%   |
| 4.9.60  | 3         | 0.57%   |
| 4.9.155 | 3         | 0.57%   |
| 4.9.124 | 3         | 0.57%   |
| 5.9.10  | 2         | 0.38%   |
| 5.8.18  | 2         | 0.38%   |
| 5.8.11  | 2         | 0.38%   |
| 5.7.19  | 2         | 0.38%   |
| 5.6.0   | 2         | 0.38%   |
| 5.5.13  | 2         | 0.38%   |
| 5.4.32  | 2         | 0.38%   |
| 5.3.12  | 2         | 0.38%   |
| 5.17.9  | 2         | 0.38%   |
| 5.15.8  | 2         | 0.38%   |
| 5.15.7  | 2         | 0.38%   |
| 5.15.5  | 2         | 0.38%   |
| 5.13.8  | 2         | 0.38%   |
| 5.12.4  | 2         | 0.38%   |
| 5.10.74 | 2         | 0.38%   |
| 4.9.95  | 2         | 0.38%   |
| 4.9.9   | 2         | 0.38%   |
| 5.9.9   | 1         | 0.19%   |
| 5.9.8   | 1         | 0.19%   |
| 5.9.6   | 1         | 0.19%   |
| 5.9.0   | 1         | 0.19%   |
| 5.8.14  | 1         | 0.19%   |
| 5.7.6   | 1         | 0.19%   |
| 5.7.13  | 1         | 0.19%   |
| 5.7.0   | 1         | 0.19%   |
| 5.6.19  | 1         | 0.19%   |
| 5.6.15  | 1         | 0.19%   |
| 5.6.14  | 1         | 0.19%   |
| 5.6.11  | 1         | 0.19%   |
| 5.6.1   | 1         | 0.19%   |
| 5.5.9   | 1         | 0.19%   |
| 5.5.5   | 1         | 0.19%   |
| 5.5.17  | 1         | 0.19%   |
| 5.5.16  | 1         | 0.19%   |
| 5.4.83  | 1         | 0.19%   |
| 5.4.80  | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 113       | 22.29%  |
| 4.15    | 44        | 8.68%   |
| 5.8     | 35        | 6.9%    |
| 5.3     | 35        | 6.9%    |
| 5.10    | 34        | 6.71%   |
| 5.11    | 31        | 6.11%   |
| 5.13    | 28        | 5.52%   |
| 5.0     | 26        | 5.13%   |
| 5.16    | 23        | 4.54%   |
| 5.15    | 23        | 4.54%   |
| 4.18    | 17        | 3.35%   |
| 4.9     | 15        | 2.96%   |
| 4.19    | 13        | 2.56%   |
| 5.9     | 12        | 2.37%   |
| 5.6     | 11        | 2.17%   |
| 5.17    | 11        | 2.17%   |
| 5.12    | 7         | 1.38%   |
| 5.5     | 6         | 1.18%   |
| 5.7     | 5         | 0.99%   |
| 5.14    | 4         | 0.79%   |
| 4.4     | 4         | 0.79%   |
| 5.18    | 3         | 0.59%   |
| 5.1     | 2         | 0.39%   |
| 5.2     | 1         | 0.2%    |
| 4.13    | 1         | 0.2%    |
| 4.1     | 1         | 0.2%    |
| 3.13    | 1         | 0.2%    |
| 3.10    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 416       | 95.19%  |
| i686   | 21        | 4.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 172       | 36.99%  |
| Unknown          | 70        | 15.05%  |
| KDE5             | 66        | 14.19%  |
| XFCE             | 45        | 9.68%   |
| X-Cinnamon       | 33        | 7.1%    |
| KDE4             | 18        | 3.87%   |
| KDE              | 17        | 3.66%   |
| Cinnamon         | 12        | 2.58%   |
| MATE             | 10        | 2.15%   |
| Unity            | 5         | 1.08%   |
| LXQt             | 3         | 0.65%   |
| GNOME Flashback  | 3         | 0.65%   |
| Pantheon         | 2         | 0.43%   |
| lightdm-xsession | 2         | 0.43%   |
| Deepin           | 2         | 0.43%   |
| xmonad           | 1         | 0.22%   |
| LXDE             | 1         | 0.22%   |
| i3               | 1         | 0.22%   |
| GNOME Classic    | 1         | 0.22%   |
| bspwm            | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 370       | 81.68%  |
| Unknown | 43        | 9.49%   |
| Wayland | 37        | 8.17%   |
| Tty     | 3         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 256       | 56.14%  |
| SDDM    | 64        | 14.04%  |
| GDM     | 40        | 8.77%   |
| LightDM | 38        | 8.33%   |
| GDM3    | 21        | 4.61%   |
| TDM     | 18        | 3.95%   |
| KDM     | 17        | 3.73%   |
| XDM     | 1         | 0.22%   |
| MDM     | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 269       | 58.99%  |
| Unknown | 85        | 18.64%  |
| bg_BG   | 79        | 17.32%  |
| en_GB   | 12        | 2.63%   |
| C       | 5         | 1.1%    |
| ru_RU   | 4         | 0.88%   |
| fr_FR   | 1         | 0.22%   |
| en_DK   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 246       | 54.91%  |
| EFI  | 202       | 45.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 346       | 77.58%  |
| Unknown | 32        | 7.17%   |
| Overlay | 31        | 6.95%   |
| Btrfs   | 20        | 4.48%   |
| Xfs     | 9         | 2.02%   |
| Ext2    | 3         | 0.67%   |
| Zfs     | 2         | 0.45%   |
| Ext3    | 2         | 0.45%   |
| Tmpfs   | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 276       | 61.47%  |
| GPT     | 113       | 25.17%  |
| MBR     | 60        | 13.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 384       | 86.88%  |
| Yes       | 58        | 13.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 316       | 71.17%  |
| Yes       | 128       | 28.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 116       | 26.67%  |
| Hewlett-Packard     | 80        | 18.39%  |
| Dell                | 71        | 16.32%  |
| ASUSTek Computer    | 55        | 12.64%  |
| Acer                | 42        | 9.66%   |
| Toshiba             | 26        | 5.98%   |
| MSI                 | 9         | 2.07%   |
| Fujitsu             | 5         | 1.15%   |
| Fujitsu Siemens     | 4         | 0.92%   |
| Apple               | 4         | 0.92%   |
| Samsung Electronics | 3         | 0.69%   |
| TUXEDO              | 2         | 0.46%   |
| Sony                | 2         | 0.46%   |
| Packard Bell        | 2         | 0.46%   |
| Medion              | 2         | 0.46%   |
| HUAWEI              | 2         | 0.46%   |
| AMI                 | 2         | 0.46%   |
| Razer               | 1         | 0.23%   |
| Pegatron            | 1         | 0.23%   |
| Notebook            | 1         | 0.23%   |
| LG Electronics      | 1         | 0.23%   |
| IBM                 | 1         | 0.23%   |
| Gigabyte Technology | 1         | 0.23%   |
| Cube                | 1         | 0.23%   |
| Compal              | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo G500 20236                          | 4         | 0.92%   |
| HP ProBook 4540s                           | 4         | 0.92%   |
| HP ProBook 450 G0                          | 3         | 0.69%   |
| Dell Latitude E6410                        | 3         | 0.69%   |
| Dell Inspiron N5110                        | 3         | 0.69%   |
| ASUS X541NA                                | 3         | 0.69%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.69%   |
| ASUS N551VW                                | 3         | 0.69%   |
| Acer Aspire 5738                           | 3         | 0.69%   |
| Unknown                                    | 3         | 0.69%   |
| Toshiba Satellite L300                     | 2         | 0.46%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.46%   |
| Toshiba Satellite A200                     | 2         | 0.46%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.46%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.46%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.46%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.46%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.46%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.46%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.46%   |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.46%   |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.46%   |
| Lenovo ThinkBook 13s-IML 20RR              | 2         | 0.46%   |
| Lenovo Legion Y740-17IRHg 81UJ             | 2         | 0.46%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.46%   |
| Lenovo IdeaPad Y510P 20217                 | 2         | 0.46%   |
| Lenovo IdeaPad Y500 20193                  | 2         | 0.46%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.46%   |
| Lenovo G50-80 80E5                         | 2         | 0.46%   |
| HP ProBook 6470b                           | 2         | 0.46%   |
| HP ProBook 455 G8 Notebook PC              | 2         | 0.46%   |
| HP ProBook 450 G8 Notebook PC              | 2         | 0.46%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.46%   |
| HP Pavilion dv5                            | 2         | 0.46%   |
| HP Pavilion 15                             | 2         | 0.46%   |
| HP Notebook                                | 2         | 0.46%   |
| HP EliteBook 8560p                         | 2         | 0.46%   |
| HP EliteBook 8460p                         | 2         | 0.46%   |
| HP EliteBook 840 G1                        | 2         | 0.46%   |
| HP EliteBook 820 G2                        | 2         | 0.46%   |
| Dell Vostro 3580                           | 2         | 0.46%   |
| Dell Studio 1747                           | 2         | 0.46%   |
| Dell Precision M4600                       | 2         | 0.46%   |
| Dell Latitude E6430                        | 2         | 0.46%   |
| Dell Latitude E6330                        | 2         | 0.46%   |
| Dell Latitude E5430 non-vPro               | 2         | 0.46%   |
| Dell Latitude E4300                        | 2         | 0.46%   |
| Dell Inspiron N5010                        | 2         | 0.46%   |
| Dell Inspiron 7577                         | 2         | 0.46%   |
| Dell Inspiron 3584                         | 2         | 0.46%   |
| Dell Inspiron 3521                         | 2         | 0.46%   |
| Dell G7 7588                               | 2         | 0.46%   |
| Dell G3 3579                               | 2         | 0.46%   |
| ASUS ZenBook UX425UAZ_UM425UAZ             | 2         | 0.46%   |
| ASUS VivoBook_ASUSLaptop X509DAP_M509DA    | 2         | 0.46%   |
| ASUS TP300LA                               | 2         | 0.46%   |
| ASUS GL553VE                               | 2         | 0.46%   |
| Apple MacBookPro11,1                       | 2         | 0.46%   |
| AMI Cherry Trail CR                        | 2         | 0.46%   |
| Acer Nitro AN515-43                        | 2         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 60        | 13.79%  |
| Acer Aspire           | 30        | 6.9%    |
| Dell Latitude         | 26        | 5.98%   |
| Dell Inspiron         | 24        | 5.52%   |
| Lenovo IdeaPad        | 23        | 5.29%   |
| Toshiba Satellite     | 21        | 4.83%   |
| HP ProBook            | 21        | 4.83%   |
| HP EliteBook          | 18        | 4.14%   |
| HP Pavilion           | 16        | 3.68%   |
| ASUS VivoBook         | 15        | 3.45%   |
| HP Compaq             | 8         | 1.84%   |
| Lenovo Legion         | 6         | 1.38%   |
| Dell Vostro           | 6         | 1.38%   |
| Lenovo Yoga           | 5         | 1.15%   |
| Lenovo G500           | 4         | 0.92%   |
| HP 250                | 4         | 0.92%   |
| Dell Precision        | 4         | 0.92%   |
| MSI Modern            | 3         | 0.69%   |
| MSI GF63              | 3         | 0.69%   |
| Lenovo ThinkBook      | 3         | 0.69%   |
| HP Laptop             | 3         | 0.69%   |
| Fujitsu Siemens AMILO | 3         | 0.69%   |
| Fujitsu LIFEBOOK      | 3         | 0.69%   |
| Dell XPS              | 3         | 0.69%   |
| Dell Studio           | 3         | 0.69%   |
| ASUS X541NA           | 3         | 0.69%   |
| ASUS N551VW           | 3         | 0.69%   |
| Acer TravelMate       | 3         | 0.69%   |
| Acer Nitro            | 3         | 0.69%   |
| Unknown               | 3         | 0.69%   |
| Toshiba PORTEGE       | 2         | 0.46%   |
| Samsung 300E4Z        | 2         | 0.46%   |
| Lenovo Y520-15IKBN    | 2         | 0.46%   |
| Lenovo G50-80         | 2         | 0.46%   |
| HP Notebook           | 2         | 0.46%   |
| HP 255                | 2         | 0.46%   |
| Fujitsu CELSIUS       | 2         | 0.46%   |
| Dell G7               | 2         | 0.46%   |
| Dell G3               | 2         | 0.46%   |
| ASUS ZenBook          | 2         | 0.46%   |
| ASUS TP300LA          | 2         | 0.46%   |
| ASUS ROG              | 2         | 0.46%   |
| ASUS GL553VE          | 2         | 0.46%   |
| ASUS ASUS             | 2         | 0.46%   |
| Apple MacBookPro11    | 2         | 0.46%   |
| AMI Cherry            | 2         | 0.46%   |
| Acer Swift            | 2         | 0.46%   |
| Acer Predator         | 2         | 0.46%   |
| TUXEDO Pulse          | 1         | 0.23%   |
| Toshiba TECRA         | 1         | 0.23%   |
| Toshiba QOSMIO        | 1         | 0.23%   |
| Toshiba Equium        | 1         | 0.23%   |
| Sony VPCEB4L1E        | 1         | 0.23%   |
| Sony VPCEA3L1E        | 1         | 0.23%   |
| Samsung RV411         | 1         | 0.23%   |
| Razer Blade           | 1         | 0.23%   |
| Pegatron A15          | 1         | 0.23%   |
| Packard Bell EasyNote | 1         | 0.23%   |
| Packard Bell DOTS     | 1         | 0.23%   |
| Notebook P17SM-A      | 1         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 43        | 9.89%   |
| 2012 | 41        | 9.43%   |
| 2017 | 39        | 8.97%   |
| 2011 | 39        | 8.97%   |
| 2020 | 35        | 8.05%   |
| 2013 | 34        | 7.82%   |
| 2018 | 33        | 7.59%   |
| 2015 | 33        | 7.59%   |
| 2014 | 27        | 6.21%   |
| 2010 | 27        | 6.21%   |
| 2008 | 26        | 5.98%   |
| 2021 | 15        | 3.45%   |
| 2009 | 14        | 3.22%   |
| 2016 | 13        | 2.99%   |
| 2007 | 9         | 2.07%   |
| 2006 | 5         | 1.15%   |
| 2004 | 2         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 435       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 409       | 93.59%  |
| Enabled  | 28        | 6.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 434       | 99.77%  |
| Yes  | 1         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 30.2%   |
| 3.01-4.0    | 104       | 23.27%  |
| 8.01-16.0   | 89        | 19.91%  |
| 16.01-24.0  | 55        | 12.3%   |
| 32.01-64.0  | 24        | 5.37%   |
| 1.01-2.0    | 19        | 4.25%   |
| 2.01-3.0    | 11        | 2.46%   |
| 24.01-32.0  | 5         | 1.12%   |
| 64.01-256.0 | 3         | 0.67%   |
| 0.51-1.0    | 2         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 184       | 36.51%  |
| 2.01-3.0   | 138       | 27.38%  |
| 4.01-8.0   | 64        | 12.7%   |
| 3.01-4.0   | 61        | 12.1%   |
| 0.51-1.0   | 35        | 6.94%   |
| 8.01-16.0  | 17        | 3.37%   |
| 0.01-0.5   | 3         | 0.6%    |
| 16.01-24.0 | 1         | 0.2%    |
| Unknown    | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 328       | 74.04%  |
| 2      | 105       | 23.7%   |
| 3      | 7         | 1.58%   |
| 0      | 3         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 250       | 56.82%  |
| Yes       | 190       | 43.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 379       | 86.73%  |
| No        | 58        | 13.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 432       | 99.31%  |
| No        | 3         | 0.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 330       | 74.49%  |
| No        | 113       | 25.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Bulgaria | 435       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sofia               | 248       | 54.63%  |
| Varna               | 37        | 8.15%   |
| Plovdiv             | 26        | 5.73%   |
| Burgas              | 20        | 4.41%   |
| Stara Zagora        | 11        | 2.42%   |
| Yambol              | 7         | 1.54%   |
| Pleven              | 7         | 1.54%   |
| Pernik              | 7         | 1.54%   |
| Veliko Tarnovo      | 6         | 1.32%   |
| Kazanlak            | 5         | 1.1%    |
| Haskovo             | 5         | 1.1%    |
| Rousse              | 4         | 0.88%   |
| Svilengrad          | 3         | 0.66%   |
| Shumen              | 3         | 0.66%   |
| Pazardzhik          | 3         | 0.66%   |
| Montana             | 3         | 0.66%   |
| Dobrich             | 3         | 0.66%   |
| Asenovgrad          | 3         | 0.66%   |
| Svoge               | 2         | 0.44%   |
| Sliven              | 2         | 0.44%   |
| Sevlievo            | 2         | 0.44%   |
| Gabrovo             | 2         | 0.44%   |
| Blagoevgrad         | 2         | 0.44%   |
| Vratsa              | 1         | 0.22%   |
| Voluyak             | 1         | 0.22%   |
| Vidin               | 1         | 0.22%   |
| Troyan Municipality | 1         | 0.22%   |
| Smolyan             | 1         | 0.22%   |
| Slashten            | 1         | 0.22%   |
| Skutare             | 1         | 0.22%   |
| Sistov              | 1         | 0.22%   |
| Silistra            | 1         | 0.22%   |
| Sarafovo            | 1         | 0.22%   |
| Sandanski           | 1         | 0.22%   |
| Ruen                | 1         | 0.22%   |
| Rogozen             | 1         | 0.22%   |
| Razgrad             | 1         | 0.22%   |
| Primorsko           | 1         | 0.22%   |
| Perushtitsa         | 1         | 0.22%   |
| Omurtag             | 1         | 0.22%   |
| Nesebar             | 1         | 0.22%   |
| Nane                | 1         | 0.22%   |
| Momchilgrad         | 1         | 0.22%   |
| Mezdra              | 1         | 0.22%   |
| Lyulin              | 1         | 0.22%   |
| Kyustendil          | 1         | 0.22%   |
| Katunitsa           | 1         | 0.22%   |
| Karlovo             | 1         | 0.22%   |
| Kardzhali           | 1         | 0.22%   |
| Ihtiman             | 1         | 0.22%   |
| Govedare            | 1         | 0.22%   |
| Gotse Delchev       | 1         | 0.22%   |
| Gorna Oryahovitsa   | 1         | 0.22%   |
| General Toshevo     | 1         | 0.22%   |
| Dimitrovgrad        | 1         | 0.22%   |
| Devnya              | 1         | 0.22%   |
| Chirpan             | 1         | 0.22%   |
| Bozhurishte         | 1         | 0.22%   |
| Botevgrad           | 1         | 0.22%   |
| Borovan             | 1         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 74        | 113     | 13.88%  |
| Seagate                   | 69        | 87      | 12.95%  |
| WDC                       | 67        | 87      | 12.57%  |
| Toshiba                   | 63        | 84      | 11.82%  |
| SanDisk                   | 32        | 42      | 6%      |
| Kingston                  | 27        | 40      | 5.07%   |
| HGST                      | 26        | 38      | 4.88%   |
| Intel                     | 24        | 36      | 4.5%    |
| Hitachi                   | 22        | 23      | 4.13%   |
| Unknown                   | 21        | 27      | 3.94%   |
| A-DATA Technology         | 16        | 24      | 3%      |
| SK hynix                  | 15        | 18      | 2.81%   |
| Crucial                   | 9         | 11      | 1.69%   |
| Transcend                 | 6         | 6       | 1.13%   |
| Fujitsu                   | 6         | 9       | 1.13%   |
| Micron Technology         | 5         | 5       | 0.94%   |
| KingSpec                  | 5         | 6       | 0.94%   |
| Team                      | 4         | 4       | 0.75%   |
| SPCC                      | 4         | 5       | 0.75%   |
| KIOXIA                    | 4         | 5       | 0.75%   |
| China                     | 4         | 5       | 0.75%   |
| LITEONIT                  | 3         | 3       | 0.56%   |
| LITEON                    | 3         | 4       | 0.56%   |
| Apple                     | 3         | 5       | 0.56%   |
| Teclast                   | 2         | 2       | 0.38%   |
| PNY                       | 2         | 2       | 0.38%   |
| Patriot                   | 2         | 2       | 0.38%   |
| Union Memory (Shenzhen)   | 1         | 1       | 0.19%   |
| TO Exter                  | 1         | 1       | 0.19%   |
| Realtek Semiconductor     | 1         | 2       | 0.19%   |
| Realtek                   | 1         | 1       | 0.19%   |
| Netac                     | 1         | 3       | 0.19%   |
| Micron/Crucial Technology | 1         | 1       | 0.19%   |
| Lenovo                    | 1         | 1       | 0.19%   |
| KingFast                  | 1         | 1       | 0.19%   |
| Intenso                   | 1         | 1       | 0.19%   |
| IBM/Hitachi               | 1         | 2       | 0.19%   |
| Hewlett-Packard           | 1         | Unknown | 0.19%   |
| Goodram                   | 1         | 1       | 0.19%   |
| FORESEE                   | 1         | 1       | 0.19%   |
| EDGE                      | 1         | 1       | 0.19%   |
| AMD                       | 1         | 2       | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 16        | 2.89%   |
| Toshiba MQ01ABD100 1TB               | 13        | 2.35%   |
| Toshiba MQ01ABF050 500GB             | 12        | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 1.81%   |
| HGST HTS721010A9E630 1TB             | 10        | 1.81%   |
| Samsung NVMe SSD Drive 512GB         | 9         | 1.63%   |
| Samsung SSD 860 EVO 250GB            | 8         | 1.45%   |
| SanDisk NVMe SSD Drive 512GB         | 7         | 1.27%   |
| WDC WD10SPZX-21Z10T0 1TB             | 6         | 1.08%   |
| HGST HTS541010A9E680 1TB             | 6         | 1.08%   |
| Unknown MMC Card  64GB               | 5         | 0.9%    |
| Unknown MMC Card  32GB               | 5         | 0.9%    |
| Samsung SSD 860 EVO 500GB            | 5         | 0.9%    |
| Samsung SSD 850 EVO 250GB            | 5         | 0.9%    |
| Samsung NVMe SSD Drive 1024GB        | 5         | 0.9%    |
| Kingston SA400S37120G 120GB SSD      | 5         | 0.9%    |
| Toshiba NVMe SSD Drive 256GB         | 4         | 0.72%   |
| Seagate ST9750420AS 752GB            | 4         | 0.72%   |
| Seagate ST9500325AS 500GB            | 4         | 0.72%   |
| SanDisk NVMe SSD Drive 256GB         | 4         | 0.72%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 0.72%   |
| Intel NVMe SSD Drive 512GB           | 4         | 0.72%   |
| Hitachi HTS547575A9E384 752GB        | 4         | 0.72%   |
| HGST HTS545050A7E680 500GB           | 4         | 0.72%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 3         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 3         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.54%   |
| Toshiba MQ04ABF100 1TB               | 3         | 0.54%   |
| Toshiba MQ01ABD075 752GB             | 3         | 0.54%   |
| SPCC Solid State Disk 512GB          | 3         | 0.54%   |
| SK hynix NVMe SSD Drive 256GB        | 3         | 0.54%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 3         | 0.54%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.54%   |
| Kingston NVMe SSD Drive 1TB          | 3         | 0.54%   |
| Intel SSDSC2CW120A3 120GB            | 3         | 0.54%   |
| Hitachi HTS723232A7A364 320GB        | 3         | 0.54%   |
| Hitachi HTS541616J9SA00 160GB        | 3         | 0.54%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 2         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.36%   |
| WDC WD7500BPKX-22HPJT0 752GB         | 2         | 0.36%   |
| WDC WD5000BPVT-35HXZT1 500GB         | 2         | 0.36%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 2         | 0.36%   |
| WDC WD3200BPVT-75JJ5T0 320GB         | 2         | 0.36%   |
| Unknown 064G70  64GB                 | 2         | 0.36%   |
| Toshiba MK2552GSX 250GB              | 2         | 0.36%   |
| Toshiba MK1646GSX 160GB              | 2         | 0.36%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 2         | 0.36%   |
| SK hynix PC401 NVMe 512GB            | 2         | 0.36%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 0.36%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 0.36%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.36%   |
| Seagate Expansion 1TB                | 2         | 0.36%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.36%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.36%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.36%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.36%   |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.36%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.36%   |
| Samsung MZVLB1T0HALR-000L2 1TB       | 2         | 0.36%   |
| Samsung MZ7LN256HMJP-00000 256GB SSD | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 68        | 86     | 29.82%  |
| WDC                 | 55        | 67     | 24.12%  |
| Toshiba             | 48        | 62     | 21.05%  |
| HGST                | 26        | 38     | 11.4%   |
| Hitachi             | 22        | 23     | 9.65%   |
| Fujitsu             | 6         | 9      | 2.63%   |
| Unknown             | 1         | 2      | 0.44%   |
| Samsung Electronics | 1         | 2      | 0.44%   |
| IBM/Hitachi         | 1         | 2      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 52     | 25.29%  |
| SanDisk             | 19        | 23     | 11.18%  |
| Kingston            | 17        | 21     | 10%     |
| A-DATA Technology   | 12        | 20     | 7.06%   |
| WDC                 | 10        | 15     | 5.88%   |
| Intel               | 8         | 11     | 4.71%   |
| Crucial             | 8         | 10     | 4.71%   |
| Transcend           | 6         | 6      | 3.53%   |
| Toshiba             | 4         | 4      | 2.35%   |
| Team                | 4         | 4      | 2.35%   |
| SPCC                | 4         | 5      | 2.35%   |
| KingSpec            | 4         | 5      | 2.35%   |
| China               | 4         | 5      | 2.35%   |
| Micron Technology   | 3         | 3      | 1.76%   |
| LITEONIT            | 3         | 3      | 1.76%   |
| LITEON              | 3         | 4      | 1.76%   |
| Apple               | 3         | 5      | 1.76%   |
| Teclast             | 2         | 2      | 1.18%   |
| PNY                 | 2         | 2      | 1.18%   |
| Patriot             | 2         | 2      | 1.18%   |
| Unknown             | 1         | 1      | 0.59%   |
| TO Exter            | 1         | 1      | 0.59%   |
| SK hynix            | 1         | 1      | 0.59%   |
| Netac               | 1         | 3      | 0.59%   |
| Intenso             | 1         | 1      | 0.59%   |
| Goodram             | 1         | 1      | 0.59%   |
| FORESEE             | 1         | 1      | 0.59%   |
| EDGE                | 1         | 1      | 0.59%   |
| AMD                 | 1         | 2      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 221       | 291    | 42.58%  |
| SSD     | 162       | 214    | 31.21%  |
| NVMe    | 113       | 180    | 21.77%  |
| MMC     | 18        | 23     | 3.47%   |
| Unknown | 5         | 4      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 337       | 497    | 70.21%  |
| NVMe | 112       | 179    | 23.33%  |
| MMC  | 18        | 23     | 3.75%   |
| SAS  | 13        | 13     | 2.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 246       | 326    | 65.08%  |
| 0.51-1.0   | 130       | 177    | 34.39%  |
| 3.01-4.0   | 1         | 1      | 0.26%   |
| 1.01-2.0   | 1         | 1      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 129       | 27.92%  |
| 251-500        | 111       | 24.03%  |
| 501-1000       | 81        | 17.53%  |
| 1001-2000      | 37        | 8.01%   |
| 1-20           | 36        | 7.79%   |
| 51-100         | 28        | 6.06%   |
| 21-50          | 26        | 5.63%   |
| Unknown        | 7         | 1.52%   |
| More than 3000 | 5         | 1.08%   |
| 2001-3000      | 2         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 194       | 38.72%  |
| 21-50          | 90        | 17.96%  |
| 101-250        | 73        | 14.57%  |
| 51-100         | 64        | 12.77%  |
| 251-500        | 35        | 6.99%   |
| 501-1000       | 25        | 4.99%   |
| 1001-2000      | 9         | 1.8%    |
| Unknown        | 7         | 1.4%    |
| 2001-3000      | 3         | 0.6%    |
| More than 3000 | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 3         | 3      | 8.82%   |
| Toshiba MQ01ABF050 500GB           | 2         | 2      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 5.88%   |
| Intel SSDSC2CW120A3 120GB          | 2         | 2      | 5.88%   |
| WDC WDS100T2B0B-00YS70 1TB SSD     | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 2.94%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 1      | 2.94%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2.94%   |
| Toshiba MK2552GSX 250GB            | 1         | 3      | 2.94%   |
| Toshiba MK1637GSX 160GB            | 1         | 1      | 2.94%   |
| Seagate ST9500420AS 500GB          | 1         | 2      | 2.94%   |
| Seagate ST94019A 40GB              | 1         | 1      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 2.94%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 2.94%   |
| Seagate ST500LM000-1EJ162 500GB    | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 2.94%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1         | 1      | 2.94%   |
| KingSpec P3-256 256GB              | 1         | 1      | 2.94%   |
| KingSpec P3-128 128GB SSD          | 1         | 1      | 2.94%   |
| Hitachi HTS547550A9E384 500GB      | 1         | 1      | 2.94%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.94%   |
| Hitachi HTS543225L9SA00 250GB      | 1         | 2      | 2.94%   |
| Hitachi HTS543225L9A300 250GB      | 1         | 1      | 2.94%   |
| Hitachi HTS541616J9SA00 160GB      | 1         | 1      | 2.94%   |
| Fujitsu MJA2160BH G2 160GB         | 1         | 2      | 2.94%   |
| A-DATA Technology SX300 64GB SSD   | 1         | 1      | 2.94%   |
| A-DATA Technology SU650 480GB SSD  | 1         | 1      | 2.94%   |
| A-DATA Technology SU650 120GB SSD  | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 12        | 13     | 35.29%  |
| Toshiba           | 5         | 7      | 14.71%  |
| Hitachi           | 5         | 6      | 14.71%  |
| WDC               | 4         | 4      | 11.76%  |
| A-DATA Technology | 3         | 3      | 8.82%   |
| KingSpec          | 2         | 2      | 5.88%   |
| Intel             | 2         | 2      | 5.88%   |
| Fujitsu           | 1         | 2      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 13     | 46.15%  |
| Toshiba | 5         | 7      | 19.23%  |
| Hitachi | 5         | 6      | 19.23%  |
| WDC     | 3         | 3      | 11.54%  |
| Fujitsu | 1         | 2      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 75.76%  |
| SSD  | 8         | 8      | 24.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 50%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 281       | 446    | 60.82%  |
| Works    | 147       | 225    | 31.82%  |
| Malfunc  | 32        | 39     | 6.93%   |
| Failed   | 2         | 2      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 351       | 70.77%  |
| Samsung Electronics              | 38        | 7.66%   |
| AMD                              | 36        | 7.26%   |
| SanDisk                          | 17        | 3.43%   |
| SK hynix                         | 14        | 2.82%   |
| Kingston Technology Company      | 10        | 2.02%   |
| Toshiba America Info Systems     | 9         | 1.81%   |
| KIOXIA                           | 7         | 1.41%   |
| Realtek Semiconductor            | 4         | 0.81%   |
| Micron/Crucial Technology        | 2         | 0.4%    |
| Micron Technology                | 2         | 0.4%    |
| Union Memory (Shenzhen)          | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Nvidia                           | 1         | 0.2%    |
| Marvell Technology Group         | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| ADATA Technology                 | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 49        | 9.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 30        | 5.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 29        | 5.49%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 27        | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 26        | 4.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 24        | 4.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 24        | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 23        | 4.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 18        | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 17        | 3.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 15        | 2.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 14        | 2.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 11        | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 8         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 8         | 1.52%   |
| Samsung NVMe SSD Controller 980                                                        | 7         | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 7         | 1.33%   |
| Intel SSD 660P Series                                                                  | 7         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 7         | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 6         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 6         | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 6         | 1.14%   |
| SK hynix Gold P31 SSD                                                                  | 5         | 0.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 5         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 5         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 5         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 5         | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 4         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 4         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.57%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 3         | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 0.57%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 3         | 0.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 0.57%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 2         | 0.38%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.38%   |
| SK hynix Non-Volatile memory controller                                                | 2         | 0.38%   |
| SK hynix BC511                                                                         | 2         | 0.38%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.38%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.38%   |
| SanDisk PC SN520 NVMe SSD                                                              | 2         | 0.38%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 0.38%   |
| Samsung Electronics SATA controller                                                    | 2         | 0.38%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 2         | 0.38%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.38%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 2         | 0.38%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.38%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 316       | 61.96%  |
| NVMe | 116       | 22.75%  |
| IDE  | 44        | 8.63%   |
| RAID | 34        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 382       | 87.82%  |
| AMD    | 53        | 12.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 2.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 2.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 2.07%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 2.07%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 1.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 1.15%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.15%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 5         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 5         | 1.15%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.15%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 1.15%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 5         | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.92%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.92%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 4         | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.92%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 4         | 0.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.92%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 0.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.92%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.69%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 3         | 0.69%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.69%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 3         | 0.69%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.69%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 3         | 0.69%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 3         | 0.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.69%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 3         | 0.69%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.69%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 3         | 0.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.69%   |
| Intel Celeron CPU 1005M @ 1.90GHz             | 3         | 0.69%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 3         | 0.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 0.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.69%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.69%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.46%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.46%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 129       | 29.66%  |
| Intel Core i5           | 101       | 23.22%  |
| Intel Core i3           | 36        | 8.28%   |
| Intel Core 2 Duo        | 27        | 6.21%   |
| Intel Pentium           | 24        | 5.52%   |
| Intel Celeron           | 18        | 4.14%   |
| AMD Ryzen 7             | 15        | 3.45%   |
| AMD Ryzen 5             | 13        | 2.99%   |
| Other                   | 8         | 1.84%   |
| Intel Atom              | 8         | 1.84%   |
| Intel Pentium Dual-Core | 6         | 1.38%   |
| Intel Pentium Silver    | 5         | 1.15%   |
| Intel Core 2            | 5         | 1.15%   |
| AMD Ryzen 3             | 5         | 1.15%   |
| Intel Pentium Dual      | 4         | 0.92%   |
| AMD Ryzen 7 PRO         | 3         | 0.69%   |
| Intel Pentium M         | 2         | 0.46%   |
| Intel Genuine           | 2         | 0.46%   |
| AMD Ryzen 5 PRO         | 2         | 0.46%   |
| AMD E1                  | 2         | 0.46%   |
| AMD A6                  | 2         | 0.46%   |
| Intel Mobile Pentium 4  | 1         | 0.23%   |
| Intel Core m3           | 1         | 0.23%   |
| Intel Core M            | 1         | 0.23%   |
| Intel Core i9           | 1         | 0.23%   |
| Intel Core Duo          | 1         | 0.23%   |
| Intel Core 2 Solo       | 1         | 0.23%   |
| Intel Celeron M         | 1         | 0.23%   |
| Intel Celeron Dual-Core | 1         | 0.23%   |
| AMD Turion 64 X2 Mobile | 1         | 0.23%   |
| AMD Turion 64 Mobile    | 1         | 0.23%   |
| AMD Sempron             | 1         | 0.23%   |
| AMD Ryzen 9             | 1         | 0.23%   |
| AMD Phenom II           | 1         | 0.23%   |
| AMD E2                  | 1         | 0.23%   |
| AMD E                   | 1         | 0.23%   |
| AMD C-50                | 1         | 0.23%   |
| AMD Athlon II Dual-Core | 1         | 0.23%   |
| AMD A10                 | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 236       | 54.13%  |
| 4       | 138       | 31.65%  |
| 6       | 31        | 7.11%   |
| 8       | 15        | 3.44%   |
| 1       | 14        | 3.21%   |
| 3       | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 435       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 314       | 72.02%  |
| 1       | 121       | 27.75%  |
| Unknown | 1         | 0.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 412       | 93.85%  |
| Unknown        | 17        | 3.87%   |
| 32-bit         | 10        | 2.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 16.81%  |
| 0x306a9    | 42        | 9.29%   |
| 0x206a7    | 33        | 7.3%    |
| 0x306d4    | 22        | 4.87%   |
| 0x806ec    | 19        | 4.2%    |
| 0x1067a    | 19        | 4.2%    |
| 0x306c3    | 16        | 3.54%   |
| 0x20655    | 15        | 3.32%   |
| 0x906ea    | 14        | 3.1%    |
| 0x406e3    | 14        | 3.1%    |
| 0x40651    | 14        | 3.1%    |
| 0x906e9    | 11        | 2.43%   |
| 0x806ea    | 11        | 2.43%   |
| 0x706a1    | 9         | 1.99%   |
| 0x6fd      | 9         | 1.99%   |
| 0x506e3    | 8         | 1.77%   |
| 0x506c9    | 8         | 1.77%   |
| 0x10676    | 8         | 1.77%   |
| 0x806e9    | 7         | 1.55%   |
| 0x08108102 | 7         | 1.55%   |
| 0x806c1    | 6         | 1.33%   |
| 0x08608103 | 6         | 1.33%   |
| 0x08108109 | 6         | 1.33%   |
| 0xa0652    | 5         | 1.11%   |
| 0x806eb    | 5         | 1.11%   |
| 0x706e5    | 5         | 1.11%   |
| 0x406c3    | 5         | 1.11%   |
| 0x6f6      | 4         | 0.88%   |
| 0x106c2    | 4         | 0.88%   |
| 0x08600106 | 4         | 0.88%   |
| 0x106e5    | 3         | 0.66%   |
| 0x0a50000c | 3         | 0.66%   |
| 0x08600103 | 3         | 0.66%   |
| 0x906ed    | 2         | 0.44%   |
| 0x6d8      | 2         | 0.44%   |
| 0x08600104 | 2         | 0.44%   |
| 0x0700010f | 2         | 0.44%   |
| 0x06006704 | 2         | 0.44%   |
| 0x706a8    | 1         | 0.22%   |
| 0x6fb      | 1         | 0.22%   |
| 0x6fa      | 1         | 0.22%   |
| 0x6f2      | 1         | 0.22%   |
| 0x6ec      | 1         | 0.22%   |
| 0x6e8      | 1         | 0.22%   |
| 0x6d6      | 1         | 0.22%   |
| 0x406c4    | 1         | 0.22%   |
| 0x30678    | 1         | 0.22%   |
| 0x20652    | 1         | 0.22%   |
| 0x106ca    | 1         | 0.22%   |
| 0x10661    | 1         | 0.22%   |
| 0x0a50000b | 1         | 0.22%   |
| 0x08101007 | 1         | 0.22%   |
| 0x07030104 | 1         | 0.22%   |
| 0x0600611a | 1         | 0.22%   |
| 0x05000029 | 1         | 0.22%   |
| 0x05000028 | 1         | 0.22%   |
| 0x03000027 | 1         | 0.22%   |
| 0x02000032 | 1         | 0.22%   |
| 0x010000b6 | 1         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 81        | 18.62%  |
| IvyBridge       | 53        | 12.18%  |
| SandyBridge     | 37        | 8.51%   |
| Haswell         | 37        | 8.51%   |
| Penryn          | 28        | 6.44%   |
| Broadwell       | 26        | 5.98%   |
| Skylake         | 23        | 5.29%   |
| Westmere        | 18        | 4.14%   |
| Core            | 18        | 4.14%   |
| Zen+            | 15        | 3.45%   |
| Zen 2           | 12        | 2.76%   |
| Goldmont plus   | 11        | 2.53%   |
| Silvermont      | 8         | 1.84%   |
| Goldmont        | 8         | 1.84%   |
| TigerLake       | 7         | 1.61%   |
| CometLake       | 7         | 1.61%   |
| Unknown         | 7         | 1.61%   |
| Zen 3           | 5         | 1.15%   |
| P6              | 5         | 1.15%   |
| IceLake         | 5         | 1.15%   |
| Bonnell         | 5         | 1.15%   |
| Nehalem         | 3         | 0.69%   |
| Excavator       | 3         | 0.69%   |
| K8 Hammer       | 2         | 0.46%   |
| K10             | 2         | 0.46%   |
| Jaguar          | 2         | 0.46%   |
| Bobcat          | 2         | 0.46%   |
| Zen             | 1         | 0.23%   |
| Puma            | 1         | 0.23%   |
| NetBurst        | 1         | 0.23%   |
| K8 & K10 hybrid | 1         | 0.23%   |
| K10 Llano       | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 339       | 57.85%  |
| Nvidia                           | 143       | 24.4%   |
| AMD                              | 103       | 17.58%  |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 48        | 7.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 5.45%   |
| Intel HD Graphics 5500                                                                   | 23        | 3.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 3.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 3.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 2.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 2.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 2.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 2.15%   |
| Intel HD Graphics 630                                                                    | 13        | 2.15%   |
| Intel UHD Graphics 620                                                                   | 12        | 1.98%   |
| AMD Renoir                                                                               | 12        | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.82%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 1.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.65%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 1.32%   |
| Intel HD Graphics 530                                                                    | 8         | 1.32%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.99%   |
| Intel HD Graphics 620                                                                    | 6         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.99%   |
| AMD Lucienne                                                                             | 6         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.83%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.83%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 0.83%   |
| AMD Cezanne                                                                              | 5         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.66%   |
| Nvidia TU117M                                                                            | 4         | 0.66%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.66%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.66%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.66%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 4         | 0.66%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.66%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 4         | 0.66%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 4         | 0.66%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.5%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.5%    |
| Nvidia GF108M [GeForce GT 525M]                                                          | 3         | 0.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.5%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.5%    |
| Intel HD Graphics 500                                                                    | 3         | 0.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.5%    |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 3         | 0.5%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.5%    |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.5%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 3         | 0.5%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.33%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 2         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 195       | 44.42%  |
| Intel + Nvidia | 119       | 27.11%  |
| 1 x AMD        | 66        | 15.03%  |
| Intel + AMD    | 27        | 6.15%   |
| 1 x Nvidia     | 21        | 4.78%   |
| 2 x AMD        | 5         | 1.14%   |
| AMD + Nvidia   | 5         | 1.14%   |
| 1 x SiS        | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 358       | 80.63%  |
| Proprietary | 68        | 15.32%  |
| Unknown     | 18        | 4.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 255       | 56.29%  |
| 1.01-2.0   | 82        | 18.1%   |
| 0.01-0.5   | 47        | 10.38%  |
| 3.01-4.0   | 34        | 7.51%   |
| 0.51-1.0   | 26        | 5.74%   |
| 5.01-6.0   | 7         | 1.55%   |
| 7.01-8.0   | 1         | 0.22%   |
| 2.01-3.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 131       | 27.58%  |
| AU Optronics            | 77        | 16.21%  |
| Chimei Innolux          | 51        | 10.74%  |
| BOE                     | 46        | 9.68%   |
| Samsung Electronics     | 41        | 8.63%   |
| Dell                    | 17        | 3.58%   |
| Lenovo                  | 16        | 3.37%   |
| Chi Mei Optoelectronics | 15        | 3.16%   |
| PANDA                   | 9         | 1.89%   |
| LG Philips              | 9         | 1.89%   |
| Philips                 | 7         | 1.47%   |
| Goldstar                | 7         | 1.47%   |
| Sharp                   | 5         | 1.05%   |
| Hewlett-Packard         | 5         | 1.05%   |
| BenQ                    | 5         | 1.05%   |
| Apple                   | 5         | 1.05%   |
| CPT                     | 4         | 0.84%   |
| Sony                    | 3         | 0.63%   |
| Ancor Communications    | 3         | 0.63%   |
| Acer                    | 3         | 0.63%   |
| Toshiba                 | 2         | 0.42%   |
| InnoLux Display         | 2         | 0.42%   |
| ViewSonic               | 1         | 0.21%   |
| Vestel Elektronik       | 1         | 0.21%   |
| Seiko/Epson             | 1         | 0.21%   |
| Panasonic               | 1         | 0.21%   |
| NEC Computers           | 1         | 0.21%   |
| MSI                     | 1         | 0.21%   |
| JDI                     | 1         | 0.21%   |
| IBM                     | 1         | 0.21%   |
| Eizo                    | 1         | 0.21%   |
| CSO                     | 1         | 0.21%   |
| APD                     | 1         | 0.21%   |
| AOC                     | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 2.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 1.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 1.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 1.05%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.84%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 4         | 0.84%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.84%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.84%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.84%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.84%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.63%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.63%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.63%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.63%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.63%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.63%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch   | 2         | 0.42%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 2         | 0.42%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.42%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.42%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.42%   |
| LG Display LCD Monitor LGD063A 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD05E9 1920x1080 294x165mm 13.3-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD05E0 1920x1080 382x215mm 17.3-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.42%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD0290 1366x768 293x165mm 13.2-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 2         | 0.42%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.42%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 0.42%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 2         | 0.42%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.42%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                        | 2         | 0.42%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 2         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 204       | 45.95%  |
| 1366x768 (WXGA)    | 135       | 30.41%  |
| 1280x800 (WXGA)    | 25        | 5.63%   |
| 1600x900 (HD+)     | 22        | 4.95%   |
| 1680x1050 (WSXGA+) | 11        | 2.48%   |
| 3840x2160 (4K)     | 9         | 2.03%   |
| 2560x1440 (QHD)    | 6         | 1.35%   |
| 1920x1200 (WUXGA)  | 5         | 1.13%   |
| 1280x1024 (SXGA)   | 5         | 1.13%   |
| 1440x900 (WXGA+)   | 4         | 0.9%    |
| 1024x600           | 4         | 0.9%    |
| 2560x1600          | 3         | 0.68%   |
| 2560x1080          | 3         | 0.68%   |
| 3840x1080          | 1         | 0.23%   |
| 3200x1800 (QHD+)   | 1         | 0.23%   |
| 3000x2000          | 1         | 0.23%   |
| 2048x1152          | 1         | 0.23%   |
| 1600x1200          | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |
| 1024x768 (XGA)     | 1         | 0.23%   |
| Unknown            | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 247       | 52.11%  |
| 13      | 53        | 11.18%  |
| 14      | 44        | 9.28%   |
| 17      | 30        | 6.33%   |
| 12      | 18        | 3.8%    |
| 24      | 16        | 3.38%   |
| 23      | 14        | 2.95%   |
| 21      | 8         | 1.69%   |
| 27      | 7         | 1.48%   |
| 10      | 5         | 1.05%   |
| 54      | 4         | 0.84%   |
| 22      | 4         | 0.84%   |
| 18      | 4         | 0.84%   |
| 11      | 4         | 0.84%   |
| 34      | 3         | 0.63%   |
| 19      | 3         | 0.63%   |
| 40      | 2         | 0.42%   |
| 20      | 2         | 0.42%   |
| 16      | 2         | 0.42%   |
| 84      | 1         | 0.21%   |
| 72      | 1         | 0.21%   |
| 25      | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 320       | 67.65%  |
| 201-300     | 49        | 10.36%  |
| 351-400     | 38        | 8.03%   |
| 501-600     | 36        | 7.61%   |
| 401-500     | 17        | 3.59%   |
| 1001-1500   | 4         | 0.85%   |
| 701-800     | 3         | 0.63%   |
| 801-900     | 2         | 0.42%   |
| 1501-2000   | 2         | 0.42%   |
| 601-700     | 1         | 0.21%   |
| Unknown     | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 359       | 84.47%  |
| 16/10   | 52        | 12.24%  |
| 5/4     | 6         | 1.41%   |
| 21/9    | 3         | 0.71%   |
| 4/3     | 2         | 0.47%   |
| 3/2     | 2         | 0.47%   |
| Unknown | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 246       | 51.9%   |
| 81-90          | 79        | 16.67%  |
| 201-250        | 35        | 7.38%   |
| 121-130        | 24        | 5.06%   |
| 71-80          | 18        | 3.8%    |
| 61-70          | 18        | 3.8%    |
| 301-350        | 7         | 1.48%   |
| 251-300        | 7         | 1.48%   |
| More than 1000 | 6         | 1.27%   |
| 151-200        | 6         | 1.27%   |
| 141-150        | 6         | 1.27%   |
| 41-50          | 5         | 1.05%   |
| 51-60          | 4         | 0.84%   |
| 131-140        | 4         | 0.84%   |
| 351-500        | 3         | 0.63%   |
| 111-120        | 2         | 0.42%   |
| 501-1000       | 2         | 0.42%   |
| 91-100         | 1         | 0.21%   |
| Unknown        | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 203       | 43.38%  |
| 101-120       | 143       | 30.56%  |
| 51-100        | 87        | 18.59%  |
| 161-240       | 21        | 4.49%   |
| More than 240 | 8         | 1.71%   |
| 1-50          | 5         | 1.07%   |
| Unknown       | 1         | 0.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 362       | 80.44%  |
| 2     | 63        | 14%     |
| 0     | 19        | 4.22%   |
| 3     | 6         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 251       | 34.29%  |
| Realtek Semiconductor             | 223       | 30.46%  |
| Qualcomm Atheros                  | 103       | 14.07%  |
| Broadcom                          | 42        | 5.74%   |
| Ralink                            | 18        | 2.46%   |
| Broadcom Limited                  | 16        | 2.19%   |
| Marvell Technology Group          | 10        | 1.37%   |
| TP-Link                           | 9         | 1.23%   |
| Sierra Wireless                   | 9         | 1.23%   |
| Ericsson Business Mobile Networks | 9         | 1.23%   |
| MediaTek                          | 6         | 0.82%   |
| Hewlett-Packard                   | 4         | 0.55%   |
| Dell                              | 4         | 0.55%   |
| Ralink Technology                 | 3         | 0.41%   |
| Huawei Technologies               | 3         | 0.41%   |
| AMD                               | 3         | 0.41%   |
| Toshiba                           | 2         | 0.27%   |
| Motorola PCS                      | 2         | 0.27%   |
| Davicom Semiconductor             | 2         | 0.27%   |
| D-Link                            | 2         | 0.27%   |
| Xiaomi                            | 1         | 0.14%   |
| Quectel Wireless Solutions        | 1         | 0.14%   |
| Qualcomm Atheros Communications   | 1         | 0.14%   |
| Nvidia                            | 1         | 0.14%   |
| NetGear                           | 1         | 0.14%   |
| Micro Star International          | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| ICS Advent                        | 1         | 0.14%   |
| Google                            | 1         | 0.14%   |
| DisplayLink                       | 1         | 0.14%   |
| ASIX Electronics                  | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 140       | 15.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46        | 5.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 3.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 24        | 2.73%   |
| Intel Wireless 8265 / 8275                                        | 20        | 2.28%   |
| Intel Wireless 7265                                               | 19        | 2.16%   |
| Intel Wireless 7260                                               | 19        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.71%   |
| Intel Wireless 3160                                               | 12        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 1.14%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 9         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 1.02%   |
| Intel WiFi Link 5100                                              | 9         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                    | 9         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.8%    |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 7         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 7         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 0.8%    |
| Sierra Wireless EM7345 4G LTE                                     | 6         | 0.68%   |
| Intel Wireless-AC 9260                                            | 6         | 0.68%   |
| Intel Wireless 8260                                               | 6         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.68%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.57%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 5         | 0.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 5         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.46%   |
| Realtek RTL8187B Wireless Adapter                                 | 4         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.46%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4         | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.34%   |
| Sierra Wireless EM7455                                            | 3         | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 238       | 51.4%   |
| Qualcomm Atheros                | 85        | 18.36%  |
| Realtek Semiconductor           | 55        | 11.88%  |
| Broadcom                        | 30        | 6.48%   |
| Ralink                          | 18        | 3.89%   |
| Sierra Wireless                 | 9         | 1.94%   |
| TP-Link                         | 7         | 1.51%   |
| MediaTek                        | 6         | 1.3%    |
| Broadcom Limited                | 6         | 1.3%    |
| Ralink Technology               | 3         | 0.65%   |
| Quectel Wireless Solutions      | 1         | 0.22%   |
| Qualcomm Atheros Communications | 1         | 0.22%   |
| NetGear                         | 1         | 0.22%   |
| Micro Star International        | 1         | 0.22%   |
| Hewlett-Packard                 | 1         | 0.22%   |
| Dell                            | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 5.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 24        | 5.16%   |
| Intel Wireless 8265 / 8275                                     | 20        | 4.3%    |
| Intel Wireless 7265                                            | 19        | 4.09%   |
| Intel Wireless 7260                                            | 19        | 4.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 3.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15        | 3.23%   |
| Intel Wireless 3160                                            | 12        | 2.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 10        | 2.15%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 2.15%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 1.94%   |
| Intel WiFi Link 5100                                           | 9         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 1.94%   |
| Intel Centrino Ultimate-N 6300                                 | 9         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.51%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 1.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 7         | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 1.51%   |
| Sierra Wireless EM7345 4G LTE                                  | 6         | 1.29%   |
| Intel Wireless-AC 9260                                         | 6         | 1.29%   |
| Intel Wireless 8260                                            | 6         | 1.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.29%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.29%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 5         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.86%   |
| Realtek RTL8187B Wireless Adapter                              | 4         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.86%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.65%   |
| Sierra Wireless EM7455                                         | 3         | 0.65%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.65%   |
| Intel Wireless 3165                                            | 3         | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.65%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.65%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.43%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.43%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.43%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 2         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.43%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.43%   |
| Intel Centrino Wireless-N 2200                                 | 2         | 0.43%   |
| Intel Centrino Wireless-N 130                                  | 2         | 0.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.43%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 196       | 50.39%  |
| Intel                    | 109       | 28.02%  |
| Qualcomm Atheros         | 31        | 7.97%   |
| Broadcom                 | 15        | 3.86%   |
| Marvell Technology Group | 10        | 2.57%   |
| Broadcom Limited         | 10        | 2.57%   |
| TP-Link                  | 2         | 0.51%   |
| Motorola PCS             | 2         | 0.51%   |
| Huawei Technologies      | 2         | 0.51%   |
| Davicom Semiconductor    | 2         | 0.51%   |
| D-Link                   | 2         | 0.51%   |
| Xiaomi                   | 1         | 0.26%   |
| Nvidia                   | 1         | 0.26%   |
| MediaTek                 | 1         | 0.26%   |
| JMicron Technology       | 1         | 0.26%   |
| ICS Advent               | 1         | 0.26%   |
| Google                   | 1         | 0.26%   |
| DisplayLink              | 1         | 0.26%   |
| ASIX Electronics         | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 140       | 35.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 46        | 11.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 30        | 7.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 2.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 2.05%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 1.79%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.79%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.53%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.53%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.28%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.28%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 1.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 1.02%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 1.02%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 4         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.77%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.77%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 3         | 0.77%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 0.77%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.77%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 2         | 0.51%   |
| Motorola PCS moto g(9) play                                                    | 2         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.51%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.51%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.51%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.51%   |
| Davicom DM9621A USB To FastEther                                               | 2         | 0.51%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.B1) [ASIX AX88772]                   | 2         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.51%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.51%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.26%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.26%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.26%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.26%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.26%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.26%   |
| MediaTek moto e(6) plus                                                        | 1         | 0.26%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.26%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.26%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.26%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.26%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.26%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.26%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.26%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 432       | 51.8%   |
| Ethernet | 379       | 45.44%  |
| Modem    | 23        | 2.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 370       | 79.06%  |
| Ethernet | 98        | 20.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 357       | 82.07%  |
| 1     | 72        | 16.55%  |
| 3     | 3         | 0.69%   |
| 0     | 3         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 431       | 98.18%  |
| Yes  | 8         | 1.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 45.54%  |
| Qualcomm Atheros Communications | 30        | 8.93%   |
| Realtek Semiconductor           | 22        | 6.55%   |
| Broadcom                        | 22        | 6.55%   |
| IMC Networks                    | 20        | 5.95%   |
| Lite-On Technology              | 15        | 4.46%   |
| Foxconn / Hon Hai               | 12        | 3.57%   |
| Toshiba                         | 11        | 3.27%   |
| Hewlett-Packard                 | 11        | 3.27%   |
| Dell                            | 11        | 3.27%   |
| Ralink                          | 9         | 2.68%   |
| Cambridge Silicon Radio         | 7         | 2.08%   |
| Foxconn International           | 4         | 1.19%   |
| Apple                           | 4         | 1.19%   |
| Ralink Technology               | 2         | 0.6%    |
| Realtek                         | 1         | 0.3%    |
| MediaTek                        | 1         | 0.3%    |
| ASUSTek Computer                | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 74        | 22.02%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 28        | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 21        | 6.25%   |
| Intel AX201 Bluetooth                                                               | 21        | 6.25%   |
| Realtek Bluetooth Radio                                                             | 17        | 5.06%   |
| Intel Bluetooth Device                                                              | 11        | 3.27%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 3.27%   |
| Intel AX200 Bluetooth                                                               | 10        | 2.98%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 2.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 2.38%   |
| Lite-On Bluetooth Device                                                            | 7         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 2.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 1.79%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.49%   |
| IMC Networks Bluetooth Device                                                       | 5         | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 1.49%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.19%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.19%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.89%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.89%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.6%    |
| Toshiba Bluetooth Device                                                            | 2         | 0.6%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 0.6%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.6%    |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.6%    |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.6%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.6%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.6%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.6%    |
| Apple Bluetooth Host Controller                                                     | 2         | 0.6%    |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.3%    |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.3%    |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.3%    |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.3%    |
| Realtek Bluetooth Radio                                                             | 1         | 0.3%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.3%    |
| Ralink CSR BS8510                                                                   | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.3%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.3%    |
| MediaTek Wireless_Device                                                            | 1         | 0.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.3%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.3%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.3%    |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.3%    |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.3%    |
| Dell BCM2046 Bluetooth Device                                                       | 1         | 0.3%    |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.3%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.3%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.3%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 375       | 71.43%  |
| AMD                              | 70        | 13.33%  |
| Nvidia                           | 60        | 11.43%  |
| Razer USA                        | 3         | 0.57%   |
| Logitech                         | 3         | 0.57%   |
| GN Netcom                        | 3         | 0.57%   |
| Lenovo                           | 2         | 0.38%   |
| C-Media Electronics              | 2         | 0.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Realtek Semiconductor            | 1         | 0.19%   |
| Plantronics                      | 1         | 0.19%   |
| JMTek                            | 1         | 0.19%   |
| Generalplus Technology           | 1         | 0.19%   |
| Creative Technology              | 1         | 0.19%   |
| ASUSTek Computer                 | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 57        | 8.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 39        | 6.15%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 5.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 5.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 32        | 5.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 4.1%    |
| Intel Broadwell-U Audio Controller                                                                | 26        | 4.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 3.31%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 3.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 3%      |
| Intel 8 Series HD Audio Controller                                                                | 19        | 3%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 2.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 2.37%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 2.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 1.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.1%    |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.63%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.47%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.47%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.47%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.32%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.32%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.32%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 0.32%   |
| GN Netcom Jabra Link 370                                                                          | 2         | 0.32%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.32%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.32%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.32%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.32%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.32%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.16%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.16%   |
| Razer USA Razer Banshee                                                                           | 1         | 0.16%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.16%   |
| Razer USA Electra V2 USB                                                                          | 1         | 0.16%   |
| Plantronics BT600                                                                                 | 1         | 0.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 72        | 27.38%  |
| SK hynix                                | 64        | 24.33%  |
| Kingston                                | 25        | 9.51%   |
| Micron Technology                       | 24        | 9.13%   |
| Unknown                                 | 17        | 6.46%   |
| Ramaxel Technology                      | 15        | 5.7%    |
| A-DATA Technology                       | 10        | 3.8%    |
| Transcend                               | 6         | 2.28%   |
| Nanya Technology                        | 6         | 2.28%   |
| Elpida                                  | 5         | 1.9%    |
| Corsair                                 | 5         | 1.9%    |
| Crucial                                 | 3         | 1.14%   |
| Apacer                                  | 3         | 1.14%   |
| Team                                    | 2         | 0.76%   |
| Unknown (ABCD)                          | 1         | 0.38%   |
| Silicon Power Computer & Communications | 1         | 0.38%   |
| Silicon Power                           | 1         | 0.38%   |
| Qimonda                                 | 1         | 0.38%   |
| ASint Technology                        | 1         | 0.38%   |
| A Force                                 | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 8         | 2.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 2.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 4         | 1.42%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s      | 4         | 1.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 3         | 1.06%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 1.06%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 1.06%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 1.06%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 3         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 1.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 3         | 1.06%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 3         | 1.06%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 3         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR                         | 2         | 0.71%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 2         | 0.71%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                | 2         | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.71%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.71%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.71%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.71%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 2         | 0.71%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 2         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s    | 2         | 0.71%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s              | 2         | 0.71%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.71%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 2         | 0.71%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.71%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 2         | 0.71%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s | 2         | 0.71%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 2         | 0.71%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.71%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s             | 2         | 0.71%   |
| A-DATA RAM Module 4096MB SODIMM DDR3 1333MT/s                | 2         | 0.71%   |
| Unknown RAM Module DIMM DDR2                                 | 1         | 0.35%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                  | 1         | 0.35%   |
| Unknown RAM Module 512MB SODIMM DRAM                         | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                | 1         | 0.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.35%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                 | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                       | 1         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR3                        | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 99        | 46.7%   |
| DDR4    | 85        | 40.09%  |
| DDR2    | 9         | 4.25%   |
| SDRAM   | 4         | 1.89%   |
| LPDDR3  | 4         | 1.89%   |
| LPDDR4  | 3         | 1.42%   |
| DDR     | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| DRAM    | 2         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 199       | 94.31%  |
| Row Of Chips | 5         | 2.37%   |
| Chip         | 4         | 1.9%    |
| DIMM         | 3         | 1.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 85        | 37.28%  |
| 8192    | 77        | 33.77%  |
| 16384   | 26        | 11.4%   |
| 2048    | 21        | 9.21%   |
| 1024    | 10        | 4.39%   |
| 32768   | 7         | 3.07%   |
| 512     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 68        | 28.94%  |
| 2667    | 51        | 21.7%   |
| 3200    | 26        | 11.06%  |
| 1334    | 20        | 8.51%   |
| 2400    | 16        | 6.81%   |
| 1333    | 13        | 5.53%   |
| Unknown | 10        | 4.26%   |
| 667     | 7         | 2.98%   |
| 2133    | 6         | 2.55%   |
| 3266    | 4         | 1.7%    |
| 1066    | 3         | 1.28%   |
| 800     | 3         | 1.28%   |
| 4199    | 2         | 0.85%   |
| 1067    | 2         | 0.85%   |
| 4267    | 1         | 0.43%   |
| 2048    | 1         | 0.43%   |
| 1867    | 1         | 0.43%   |
| 975     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung M332x 382x 402x Series   | 1         | 25%     |
| Samsung M267x 287x Series        | 1         | 25%     |
| Canon PIXMA MP240                | 1         | 25%     |
| Brother DCP-7055 scanner/printer | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 108       | 28.35%  |
| IMC Networks                           | 47        | 12.34%  |
| Microdia                               | 35        | 9.19%   |
| Realtek Semiconductor                  | 34        | 8.92%   |
| Acer                                   | 32        | 8.4%    |
| Sunplus Innovation Technology          | 22        | 5.77%   |
| Quanta                                 | 18        | 4.72%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.41%   |
| Suyin                                  | 12        | 3.15%   |
| Lite-On Technology                     | 12        | 3.15%   |
| Syntek                                 | 9         | 2.36%   |
| Luxvisions Innotech Limited            | 5         | 1.31%   |
| Logitech                               | 5         | 1.31%   |
| Alcor Micro                            | 5         | 1.31%   |
| Silicon Motion                         | 4         | 1.05%   |
| Z-Star Microelectronics                | 2         | 0.52%   |
| Samsung Electronics                    | 2         | 0.52%   |
| Ricoh                                  | 2         | 0.52%   |
| Lenovo                                 | 2         | 0.52%   |
| Importek                               | 2         | 0.52%   |
| Alpha Imaging Technology               | 2         | 0.52%   |
| Sunplus Technology                     | 1         | 0.26%   |
| Sonix Technology                       | 1         | 0.26%   |
| Primax Electronics                     | 1         | 0.26%   |
| Microsoft                              | 1         | 0.26%   |
| Hewlett-Packard                        | 1         | 0.26%   |
| Aveo Technology                        | 1         | 0.26%   |
| Arkmicro Technologies                  | 1         | 0.26%   |
| Apple                                  | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 20        | 5.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 19        | 4.99%   |
| IMC Networks Integrated Camera                                           | 15        | 3.94%   |
| Chicony HD Webcam                                                        | 14        | 3.67%   |
| Microdia Integrated_Webcam_HD                                            | 10        | 2.62%   |
| Sunplus Integrated_Webcam_HD                                             | 7         | 1.84%   |
| Realtek Lenovo EasyCamera                                                | 7         | 1.84%   |
| Realtek Integrated_Webcam_HD                                             | 7         | 1.84%   |
| Acer SunplusIT Integrated Camera                                         | 7         | 1.84%   |
| Chicony USB 2.0 Camera                                                   | 6         | 1.57%   |
| Acer Lenovo EasyCamera                                                   | 6         | 1.57%   |
| Acer Integrated Camera                                                   | 6         | 1.57%   |
| Chicony TOSHIBA Web Camera - HD                                          | 5         | 1.31%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 5         | 1.31%   |
| Chicony HD WebCam (Asus N-series)                                        | 5         | 1.31%   |
| Quanta HD Webcam                                                         | 4         | 1.05%   |
| Microdia Integrated Webcam                                               | 4         | 1.05%   |
| Lite-On Integrated Camera                                                | 4         | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 4         | 1.05%   |
| Chicony Lenovo EasyCamera                                                | 4         | 1.05%   |
| Syntek Integrated Camera                                                 | 3         | 0.79%   |
| Sunplus Laptop Integrated Webcam HD                                      | 3         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]                                             | 3         | 0.79%   |
| Realtek EasyCamera                                                       | 3         | 0.79%   |
| Quanta HP TrueVision HD Camera                                           | 3         | 0.79%   |
| Quanta HP HD Camera                                                      | 3         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 0.79%   |
| Microdia Dell Integrated HD Webcam                                       | 3         | 0.79%   |
| Logitech Webcam C270                                                     | 3         | 0.79%   |
| Lite-On TOSHIBA Web Camera - HD                                          | 3         | 0.79%   |
| Lite-On HP HD Webcam                                                     | 3         | 0.79%   |
| IMC Networks UVC VGA Webcam                                              | 3         | 0.79%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 0.79%   |
| Chicony HP Webcam [2 MP Macro]                                           | 3         | 0.79%   |
| Chicony HP HD Webcam [Fixed]                                             | 3         | 0.79%   |
| Chicony HP HD Webcam                                                     | 3         | 0.79%   |
| Chicony FJ Camera                                                        | 3         | 0.79%   |
| Chicony CKF7063 Webcam (HP)                                              | 3         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.79%   |
| Alcor Micro Acer Integrated Webcam                                       | 3         | 0.79%   |
| Acer HD Webcam                                                           | 3         | 0.79%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 0.52%   |
| Suyin HP TrueVision HD Integrated Webcam                                 | 2         | 0.52%   |
| Suyin Asus Integrated Webcam                                             | 2         | 0.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 2         | 0.52%   |
| Sunplus HD WebCam                                                        | 2         | 0.52%   |
| Sunplus Dell HD Webcam                                                   | 2         | 0.52%   |
| Silicon Motion WebCam SC-0311139N                                        | 2         | 0.52%   |
| Samsung Galaxy A5 (MTP)                                                  | 2         | 0.52%   |
| Realtek USB2.0 HD UVC WebCam                                             | 2         | 0.52%   |
| Realtek HP Truevision HD integrated webcam                               | 2         | 0.52%   |
| Realtek HD WebCam                                                        | 2         | 0.52%   |
| Quanta VGA WebCam                                                        | 2         | 0.52%   |
| Quanta USB2.0 HD UVC WebCam                                              | 2         | 0.52%   |
| Quanta HD User Facing                                                    | 2         | 0.52%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 2         | 0.52%   |
| Microdia Laptop_Integrated_Webcam_2M                                     | 2         | 0.52%   |
| Microdia Integrated_Webcam_2M                                            | 2         | 0.52%   |
| Microdia Dell Laptop Integrated Webcam HD                                | 2         | 0.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                     | 2         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 42.68%  |
| Synaptics                  | 19        | 23.17%  |
| AuthenTec                  | 11        | 13.41%  |
| Shenzhen Goodix Technology | 5         | 6.1%    |
| Upek                       | 4         | 4.88%   |
| Elan Microelectronics      | 4         | 4.88%   |
| LighTuning Technology      | 3         | 3.66%   |
| STMicroelectronics         | 1         | 1.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 10.98%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 10.98%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 6.1%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 4.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 4.88%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 4.88%   |
| AuthenTec AES2810                                                          | 4         | 4.88%   |
| Unknown                                                                    | 4         | 4.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 3.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.44%   |
| Validity Sensors VFS491                                                    | 2         | 2.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.44%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.44%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.44%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.22%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.22%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.22%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 1.22%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.22%   |
| AuthenTec AES1600                                                          | 1         | 1.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 19        | 37.25%  |
| Alcor Micro           | 17        | 33.33%  |
| O2 Micro              | 5         | 9.8%    |
| Lenovo                | 4         | 7.84%   |
| Upek                  | 3         | 5.88%   |
| SCM Microsystems      | 2         | 3.92%   |
| Advanced Card Systems | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 17.65%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 9.8%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 7.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.88%   |
| Broadcom 5880                                                                | 3         | 5.88%   |
| Broadcom 58200                                                               | 3         | 5.88%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 3.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.96%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 263       | 58.19%  |
| 1     | 141       | 31.19%  |
| 2     | 46        | 10.18%  |
| 3     | 2         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 82        | 36.77%  |
| Chipcard                 | 44        | 19.73%  |
| Graphics card            | 38        | 17.04%  |
| Net/wireless             | 16        | 7.17%   |
| Multimedia controller    | 11        | 4.93%   |
| Bluetooth                | 11        | 4.93%   |
| Storage                  | 7         | 3.14%   |
| Communication controller | 3         | 1.35%   |
| Camera                   | 3         | 1.35%   |
| Modem                    | 2         | 0.9%    |
| Firewire controller      | 2         | 0.9%    |
| Card reader              | 2         | 0.9%    |
| Net/ethernet             | 1         | 0.45%   |
| Flash memory             | 1         | 0.45%   |


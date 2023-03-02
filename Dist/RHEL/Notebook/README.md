RHEL - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for RHEL.

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

Total: 227

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| Lenovo   | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| Dell     | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI      | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Lenovo   | ThinkPad T480s 20L8S2N80... | [2a4e6ab2d4](https://linux-hardware.org/?probe=2a4e6ab2d4) | Feb 07, 2023 |
| Getac    | S410G4                      | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac    | S410G4                      | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo   | ThinkPad T14 Gen 2i 20W1... | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Dell     | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell     | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [34169c74c5](https://linux-hardware.org/?probe=34169c74c5) | Dec 31, 2022 |
| HP       | EliteBook 2570p             | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| MSI      | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo   | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP       | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| Dell     | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| Lenovo   | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo   | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek  | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek  | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP       | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer    | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [8656acec04](https://linux-hardware.org/?probe=8656acec04) | Sep 14, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [23649c49e3](https://linux-hardware.org/?probe=23649c49e3) | Sep 14, 2022 |
| Dell     | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Dell     | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo   | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo   | ThinkPad T480 20L60034MX    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo   | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo   | ThinkPad T15 Gen 2i 20W5... | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| Lenovo   | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo   | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo   | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| ASUSTek  | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| Dell     | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell     | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo   | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo   | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell     | Precision 5550              | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell     | Precision 7560              | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo   | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| Lenovo   | ThinkPad X1 Yoga 1st 20F... | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Dell     | Latitude E5570              | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| Lenovo   | ThinkPad T490 20N3S5DV0S    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP       | EliteBook 8460p             | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Samsung  | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| ASUSTek  | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| Toshiba  | Satellite Pro R50-C         | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba  | Satellite Pro R50-C         | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Dell     | Precision 3551              | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo   | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer     | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP       | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo   | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo   | ThinkPad P50 20ENS1L000     | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo   | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo   | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| HP       | ZBook Firefly 15 inch G8... | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| Lenovo   | ThinkPad P50 20ENS1L000     | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K90... | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| Lenovo   | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo   | ThinkPad X230 Tablet 343... | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell     | XPS 15 9560                 | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek  | TUF Gaming FX505DU_FX505... | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek  | TUF Gaming FX505DU_FX505... | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell     | XPS 15 9560                 | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| HP       | ZBook 15 G5                 | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Dell     | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP       | EliteBook 850 G7 Noteboo... | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell     | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell     | Latitude E6430              | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell     | Latitude E6430              | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo   | ThinkPad P15 Gen 1 20SUS... | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Dell     | Precision 3541              | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP       | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP       | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell     | Latitude E6530              | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| Lenovo   | ThinkPad T470p 20J7S0FA0... | [bf95cd0ce7](https://linux-hardware.org/?probe=bf95cd0ce7) | Apr 20, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell     | Inspiron 3559               | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP       | OMEN by Laptop 15-dc1xxx    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo   | ThinkPad T460 20FMS1VA09    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo   | ThinkPad T460 20FMS1VA09    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo   | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek  | Zephyrus G GU502DU_GA502... | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| Dell     | Precision 5510              | [2d4aed7f6c](https://linux-hardware.org/?probe=2d4aed7f6c) | Feb 22, 2021 |
| Sony     | VPCEB4L1R                   | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP       | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Lenovo   | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo   | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo   | ThinkPad L480 20LSCTO1WW    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo   | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| Lenovo   | ThinkPad T480s 20L8S2N80... | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| Lenovo   | ThinkPad T14s Gen 1 20T1... | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo   | ThinkPad T490s 20NYS7K91... | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Dell     | Latitude 5290               | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell     | Latitude 5290               | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP       | Pavilion 14                 | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo   | ThinkPad X250 20CLS0H807    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo   | ThinkPad X250 20CLS0H807    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo   | ThinkPad X250 20CLS0H807    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo   | ThinkPad T460 20BUS0QT0A    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP       | ZBook 14u G6                | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell     | Precision 7510              | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| TUXEDO   | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell     | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell     | Latitude E6420              | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell     | Latitude E6420              | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| TUXEDO   | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO   | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell     | Precision 7510              | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP       | Pavilion 14                 | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell     | Precision 7510              | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo   | ThinkPad T520 42404CG       | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo   | ThinkPad T520 42404CG       | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo   | ThinkPad T14s Gen 1 20UJ... | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell     | Latitude 5300               | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell     | Latitude 5300               | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP       | Pavilion 14                 | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo   | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo   | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| Lenovo   | ThinkPad P50 20EN0005UK     | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| Lenovo   | ThinkPad T470p 20J7S0FA0... | [e3dab03999](https://linux-hardware.org/?probe=e3dab03999) | Sep 01, 2020 |
| HP       | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell     | Inspiron N5110              | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell     | Inspiron N5110              | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| Lenovo   | ThinkPad T470p 20J7S0FA0... | [93b236ab24](https://linux-hardware.org/?probe=93b236ab24) | Aug 01, 2020 |
| ASUSTek  | GL502VMK                    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| Lenovo   | ThinkPad T490 20N3S5DU27    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell     | Latitude 5300               | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi     | TM1707                      | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi     | TM1707                      | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek  | GL502VMK                    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell     | Latitude 5300               | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0N    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0N    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| Lenovo   | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| HP       | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP       | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell     | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell     | Precision 5540              | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Lenovo   | ThinkPad T450s 20BWS0B50... | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC0N    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC00    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo   | ThinkPad T590 20N5S2NC00    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Lenovo   | ThinkPad T450s 20BWS0B50... | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Sony     | VPCEB23FM                   | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony     | VPCEB23FM                   | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo   | ThinkPad P52 20M9CTO1WW     | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo   | ThinkPad P52 20M9CTO1WW     | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo   | ThinkPad T490s 20NX002HU... | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo   | ThinkPad P1 Gen 2 20QUS1... | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo   | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Dell     | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP       | 250 G4 Notebook PC          | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP       | 250 G4 Notebook PC          | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Lenovo   | ThinkPad T590 20N5S2NC0V    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo   | ThinkPad T480s 20L8S2N80... | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |
| Dell     | Latitude 7390               | [9b0861a491](https://linux-hardware.org/?probe=9b0861a491) | Jul 04, 2019 |
| Dell     | Latitude 7390               | [5090404699](https://linux-hardware.org/?probe=5090404699) | Jul 04, 2019 |
| Lenovo   | ThinkPad L480 20LSS0M100    | [b1b6812c4f](https://linux-hardware.org/?probe=b1b6812c4f) | May 19, 2019 |
| Lenovo   | ThinkPad X131e 3368CTO      | [c3f67b75e2](https://linux-hardware.org/?probe=c3f67b75e2) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| RHEL 8 | 111       | 79.29%  |
| RHEL 9 | 20        | 14.29%  |
| RHEL 7 | 9         | 6.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| RHEL | 139       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 10        | 5.95%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 5.95%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 4.76%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 4.76%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 7         | 4.17%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 4.17%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 2.38%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 4         | 2.38%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 2.38%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 2.38%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 2.38%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 2.38%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 2.38%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 2.38%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 2.38%   |
| 4.18.0-193.el8.x86_64        | 4         | 2.38%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 4         | 2.38%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 1.79%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 1.79%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 3         | 1.79%   |
| 4.18.0-425.3.1.el8.x86_64    | 3         | 1.79%   |
| 4.18.0-372.9.1.el8.x86_64    | 3         | 1.79%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 1.79%   |
| 4.18.0-305.el8.x86_64        | 3         | 1.79%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 1.79%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 1.79%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 1.79%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 1.79%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 1.19%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 1.19%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.19%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.19%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.19%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 2         | 1.19%   |
| 3.10.0-1127.13.1.el7.x86_64  | 2         | 1.19%   |
| 3.10.0-1062.18.1.el7.x86_64  | 2         | 1.19%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.6%    |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 0.6%    |
| 5.14.0-39.el9.x86_64         | 1         | 0.6%    |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 110       | 78.57%  |
| 5.14.0  | 20        | 14.29%  |
| 3.10.0  | 9         | 6.43%   |
| 5.9.1   | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 110       | 78.57%  |
| 5.14    | 20        | 14.29%  |
| 3.10    | 9         | 6.43%   |
| 5.9     | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 139       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 120       | 82.76%  |
| Unknown       | 13        | 8.97%   |
| GNOME Classic | 9         | 6.21%   |
| KDE5          | 2         | 1.38%   |
| Cinnamon      | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 82        | 57.34%  |
| Wayland | 56        | 39.16%  |
| Unknown | 5         | 3.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 110       | 75.86%  |
| GDM     | 34        | 23.45%  |
| SDDM    | 1         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 101       | 70.63%  |
| Unknown | 10        | 6.99%   |
| en_GB   | 7         | 4.9%    |
| pt_BR   | 4         | 2.8%    |
| fr_FR   | 4         | 2.8%    |
| pl_PL   | 2         | 1.4%    |
| nl_NL   | 2         | 1.4%    |
| en_IN   | 2         | 1.4%    |
| en_IE   | 2         | 1.4%    |
| de_DE   | 2         | 1.4%    |
| ru_RU   | 1         | 0.7%    |
| ja_JP   | 1         | 0.7%    |
| it_IT   | 1         | 0.7%    |
| es_ES   | 1         | 0.7%    |
| es_EC   | 1         | 0.7%    |
| en_DK   | 1         | 0.7%    |
| de_CH   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 116       | 81.12%  |
| BIOS | 27        | 18.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 119       | 84.4%   |
| Ext4    | 14        | 9.93%   |
| Unknown | 8         | 5.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 74.48%  |
| GPT     | 34        | 23.45%  |
| MBR     | 3         | 2.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 133       | 93.66%  |
| Yes       | 9         | 6.34%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 90.85%  |
| Yes       | 13        | 9.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 78        | 56.12%  |
| Dell                | 28        | 20.14%  |
| Hewlett-Packard     | 14        | 10.07%  |
| ASUSTek Computer    | 7         | 5.04%   |
| Sony                | 2         | 1.44%   |
| MSI                 | 2         | 1.44%   |
| TUXEDO              | 1         | 0.72%   |
| Toshiba             | 1         | 0.72%   |
| Timi                | 1         | 0.72%   |
| Samsung Electronics | 1         | 0.72%   |
| Razer               | 1         | 0.72%   |
| Gigabyte Technology | 1         | 0.72%   |
| Getac               | 1         | 0.72%   |
| Acer                | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X        | 4         | 2.88%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401   | 2         | 1.44%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00   | 2         | 1.44%   |
| Lenovo ThinkPad T590 20N5S2NC0N            | 2         | 1.44%   |
| Lenovo ThinkPad T490s 20NYS7K91R           | 2         | 1.44%   |
| Lenovo ThinkPad T480s 20L8S2N800           | 2         | 1.44%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08      | 2         | 1.44%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q        | 2         | 1.44%   |
| HP EliteBook 8460p                         | 2         | 1.44%   |
| Dell Precision 7560                        | 2         | 1.44%   |
| Dell Precision 7510                        | 2         | 1.44%   |
| Dell Latitude E6430                        | 2         | 1.44%   |
| Dell Latitude 5300                         | 2         | 1.44%   |
| TUXEDO N13xWU                              | 1         | 0.72%   |
| Toshiba Satellite Pro R50-C                | 1         | 0.72%   |
| Timi TM1707                                | 1         | 0.72%   |
| Sony VPCEB4L1R                             | 1         | 0.72%   |
| Sony VPCEB23FM                             | 1         | 0.72%   |
| Samsung 730QCJ/730QCR                      | 1         | 0.72%   |
| Razer Blade 15 Mid 2019-Base               | 1         | 0.72%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.72%   |
| MSI GE72VR 7RF                             | 1         | 0.72%   |
| Lenovo Z40-70 20366                        | 1         | 0.72%   |
| Lenovo ThinkPad X270 20HN001EMC            | 1         | 0.72%   |
| Lenovo ThinkPad X250 20CLS0H807            | 1         | 0.72%   |
| Lenovo ThinkPad X230 Tablet 34373KU        | 1         | 0.72%   |
| Lenovo ThinkPad X201 3680PKS               | 1         | 0.72%   |
| Lenovo ThinkPad X131e 3368CTO              | 1         | 0.72%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100     | 1         | 0.72%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US   | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G | 1         | 0.72%   |
| Lenovo ThinkPad W530 2441B32               | 1         | 0.72%   |
| Lenovo ThinkPad W520 4284GN2               | 1         | 0.72%   |
| Lenovo ThinkPad T590 20N5S2NC0V            | 1         | 0.72%   |
| Lenovo ThinkPad T590 20N5S2NC00            | 1         | 0.72%   |
| Lenovo ThinkPad T520 42404CG               | 1         | 0.72%   |
| Lenovo ThinkPad T490s 20NYS7K905           | 1         | 0.72%   |
| Lenovo ThinkPad T490s 20NX002HUS           | 1         | 0.72%   |
| Lenovo ThinkPad T490 20N3S5DV0S            | 1         | 0.72%   |
| Lenovo ThinkPad T490 20N3S5DU27            | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 75        | 53.96%  |
| Dell Latitude     | 12        | 8.63%   |
| Dell Precision    | 9         | 6.47%   |
| HP EliteBook      | 5         | 3.6%    |
| Dell Inspiron     | 4         | 2.88%   |
| HP ZBook          | 3         | 2.16%   |
| Dell XPS          | 2         | 1.44%   |
| ASUS TUF          | 2         | 1.44%   |
| TUXEDO N13xWU     | 1         | 0.72%   |
| Toshiba Satellite | 1         | 0.72%   |
| Timi TM1707       | 1         | 0.72%   |
| Sony VPCEB4L1R    | 1         | 0.72%   |
| Sony VPCEB23FM    | 1         | 0.72%   |
| Samsung 730QCJ    | 1         | 0.72%   |
| Razer Blade       | 1         | 0.72%   |
| MSI GP75          | 1         | 0.72%   |
| MSI GE72VR        | 1         | 0.72%   |
| Lenovo Z40-70     | 1         | 0.72%   |
| Lenovo ThinkBook  | 1         | 0.72%   |
| Lenovo Legion     | 1         | 0.72%   |
| HP ProBook        | 1         | 0.72%   |
| HP Pavilion       | 1         | 0.72%   |
| HP OMEN           | 1         | 0.72%   |
| HP Laptop         | 1         | 0.72%   |
| HP 340S           | 1         | 0.72%   |
| HP 250            | 1         | 0.72%   |
| Gigabyte AERO     | 1         | 0.72%   |
| Getac S410G4      | 1         | 0.72%   |
| Dell G3           | 1         | 0.72%   |
| ASUS Zephyrus     | 1         | 0.72%   |
| ASUS Z450LA       | 1         | 0.72%   |
| ASUS X550VX       | 1         | 0.72%   |
| ASUS VivoBook     | 1         | 0.72%   |
| ASUS GL502VMK     | 1         | 0.72%   |
| Acer Nitro        | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 31        | 22.3%   |
| 2019 | 29        | 20.86%  |
| 2018 | 18        | 12.95%  |
| 2021 | 11        | 7.91%   |
| 2017 | 9         | 6.47%   |
| 2016 | 9         | 6.47%   |
| 2015 | 8         | 5.76%   |
| 2011 | 7         | 5.04%   |
| 2012 | 6         | 4.32%   |
| 2022 | 3         | 2.16%   |
| 2013 | 3         | 2.16%   |
| 2010 | 3         | 2.16%   |
| 2014 | 2         | 1.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 139       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 119       | 85%     |
| Enabled  | 21        | 15%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 139       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 48        | 33.57%  |
| 8.01-16.0   | 31        | 21.68%  |
| 4.01-8.0    | 23        | 16.08%  |
| 16.01-24.0  | 23        | 16.08%  |
| 64.01-256.0 | 9         | 6.29%   |
| 3.01-4.0    | 7         | 4.9%    |
| 24.01-32.0  | 2         | 1.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 65        | 41.94%  |
| 8.01-16.0  | 26        | 16.77%  |
| 3.01-4.0   | 24        | 15.48%  |
| 2.01-3.0   | 22        | 14.19%  |
| 1.01-2.0   | 12        | 7.74%   |
| 24.01-32.0 | 2         | 1.29%   |
| 16.01-24.0 | 2         | 1.29%   |
| 32.01-64.0 | 1         | 0.65%   |
| 0.51-1.0   | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 75.35%  |
| 2      | 24        | 16.9%   |
| 3      | 10        | 7.04%   |
| 4      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 86.43%  |
| Yes       | 19        | 13.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 86.43%  |
| No        | 19        | 13.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 98.56%  |
| No        | 2         | 1.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 77.93%  |
| No        | 32        | 22.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 34        | 24.46%  |
| India        | 17        | 12.23%  |
| Germany      | 7         | 5.04%   |
| UK           | 6         | 4.32%   |
| France       | 5         | 3.6%    |
| Czechia      | 5         | 3.6%    |
| Brazil       | 5         | 3.6%    |
| Spain        | 4         | 2.88%   |
| Switzerland  | 3         | 2.16%   |
| South Africa | 3         | 2.16%   |
| Netherlands  | 3         | 2.16%   |
| Mexico       | 3         | 2.16%   |
| Turkey       | 2         | 1.44%   |
| Singapore    | 2         | 1.44%   |
| Romania      | 2         | 1.44%   |
| Poland       | 2         | 1.44%   |
| Japan        | 2         | 1.44%   |
| Italy        | 2         | 1.44%   |
| Finland      | 2         | 1.44%   |
| Chile        | 2         | 1.44%   |
| Canada       | 2         | 1.44%   |
| Australia    | 2         | 1.44%   |
| Sri Lanka    | 1         | 0.72%   |
| Saudi Arabia | 1         | 0.72%   |
| Russia       | 1         | 0.72%   |
| Portugal     | 1         | 0.72%   |
| Pakistan     | 1         | 0.72%   |
| Norway       | 1         | 0.72%   |
| Nepal        | 1         | 0.72%   |
| Myanmar      | 1         | 0.72%   |
| Morocco      | 1         | 0.72%   |
| Luxembourg   | 1         | 0.72%   |
| Lithuania    | 1         | 0.72%   |
| Kuwait       | 1         | 0.72%   |
| Kenya        | 1         | 0.72%   |
| Jordan       | 1         | 0.72%   |
| Israel       | 1         | 0.72%   |
| Ireland      | 1         | 0.72%   |
| Georgia      | 1         | 0.72%   |
| Egypt        | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Prague                   | 4         | 2.7%    |
| Munich                   | 3         | 2.03%   |
| Mexico City              | 3         | 2.03%   |
| Chennai                  | 3         | 2.03%   |
| Turku                    | 2         | 1.35%   |
| Singapore                | 2         | 1.35%   |
| Milan                    | 2         | 1.35%   |
| Madrid                   | 2         | 1.35%   |
| Houston                  | 2         | 1.35%   |
| Zaragoza                 | 1         | 0.68%   |
| Webster                  | 1         | 0.68%   |
| Vardenis                 | 1         | 0.68%   |
| Udaipur                  | 1         | 0.68%   |
| Temuco                   | 1         | 0.68%   |
| Temara                   | 1         | 0.68%   |
| Taringa                  | 1         | 0.68%   |
| Talkha                   | 1         | 0.68%   |
| Syracuse                 | 1         | 0.68%   |
| Streatham                | 1         | 0.68%   |
| Steamboat Springs        | 1         | 0.68%   |
| Sofia                    | 1         | 0.68%   |
| Skien                    | 1         | 0.68%   |
| Šilalė                 | 1         | 0.68%   |
| Sheffield                | 1         | 0.68%   |
| Sao Paulo                | 1         | 0.68%   |
| Santiago                 | 1         | 0.68%   |
| San Jose                 | 1         | 0.68%   |
| San Francisco            | 1         | 0.68%   |
| Salt Lake City           | 1         | 0.68%   |
| Saint-Ismier             | 1         | 0.68%   |
| Saint-Alphonse-Rodriguez | 1         | 0.68%   |
| Saint Paul               | 1         | 0.68%   |
| Roha                     | 1         | 0.68%   |
| Rochester                | 1         | 0.68%   |
| Reims                    | 1         | 0.68%   |
| Raleigh                  | 1         | 0.68%   |
| Quito                    | 1         | 0.68%   |
| Queenscliff              | 1         | 0.68%   |
| Queens                   | 1         | 0.68%   |
| Providence               | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 39        | 62     | 21.67%  |
| Toshiba                     | 20        | 24     | 11.11%  |
| WDC                         | 17        | 21     | 9.44%   |
| SanDisk                     | 15        | 19     | 8.33%   |
| SK hynix                    | 14        | 15     | 7.78%   |
| Seagate                     | 13        | 18     | 7.22%   |
| Intel                       | 9         | 12     | 5%      |
| Micron Technology           | 7         | 9      | 3.89%   |
| Unknown                     | 6         | 8      | 3.33%   |
| Kingston                    | 6         | 6      | 3.33%   |
| HGST                        | 4         | 4      | 2.22%   |
| Lenovo                      | 3         | 3      | 1.67%   |
| KIOXIA                      | 3         | 3      | 1.67%   |
| Crucial                     | 3         | 3      | 1.67%   |
| A-DATA Technology           | 3         | 3      | 1.67%   |
| SSSTC                       | 2         | 2      | 1.11%   |
| Silicon Motion              | 2         | 3      | 1.11%   |
| UMIS                        | 1         | 1      | 0.56%   |
| Transcend                   | 1         | 1      | 0.56%   |
| Team                        | 1         | 2      | 0.56%   |
| SMI                         | 1         | 2      | 0.56%   |
| SABRENT                     | 1         | 1      | 0.56%   |
| PNY                         | 1         | 2      | 0.56%   |
| Plextor                     | 1         | 1      | 0.56%   |
| Phison                      | 1         | 1      | 0.56%   |
| Lite-On                     | 1         | 1      | 0.56%   |
| Kingston Technology Company | 1         | 1      | 0.56%   |
| Golden                      | 1         | 1      | 0.56%   |
| Gigabyte Technology         | 1         | 1      | 0.56%   |
| Corsair                     | 1         | 1      | 0.56%   |
| China                       | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                        | 10        | 5.15%   |
| SanDisk NVMe SSD Drive 256GB                         | 6         | 3.09%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 6         | 3.09%   |
| Samsung NVMe SSD Drive 512GB                         | 6         | 3.09%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 2.58%   |
| Toshiba NVMe SSD Drive 256GB                         | 4         | 2.06%   |
| Intel NVMe SSD Drive 512GB                           | 4         | 2.06%   |
| Toshiba NVMe SSD Drive 512GB                         | 3         | 1.55%   |
| Samsung NVMe SSD Drive 2TB                           | 3         | 1.55%   |
| Samsung NVMe SSD Drive 1TB                           | 3         | 1.55%   |
| Micron NVMe SSD Drive 256GB                          | 3         | 1.55%   |
| HGST HTS721010A9E630 1TB                             | 3         | 1.55%   |
| Unknown NVMe SSD Drive 256GB                         | 2         | 1.03%   |
| Toshiba NVMe SSD Drive 1024GB                        | 2         | 1.03%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 1.03%   |
| Toshiba KXG6AZNV256G 256GB                           | 2         | 1.03%   |
| SK hynix NVMe SSD Drive 1024GB                       | 2         | 1.03%   |
| Seagate ST1000LM049-2GH172 1TB                       | 2         | 1.03%   |
| Seagate Expansion 1TB                                | 2         | 1.03%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 2         | 1.03%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 1.03%   |
| Samsung SSD 860 EVO 1TB                              | 2         | 1.03%   |
| Samsung Portable SSD T5 500GB                        | 2         | 1.03%   |
| Samsung NVMe SSD Drive 500GB                         | 2         | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 2         | 1.03%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                           | 2         | 1.03%   |
| Intel NVMe SSD Drive 2TB                             | 2         | 1.03%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 1         | 0.52%   |
| WDC WDS400T2B0A-00SM50 4TB SSD                       | 1         | 0.52%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                       | 1         | 0.52%   |
| WDC WD6400BPVT-75HXZT1 640GB                         | 1         | 0.52%   |
| WDC WD5000LPLX-08ZNTT0 500GB                         | 1         | 0.52%   |
| WDC WD2500BEVT-60ZCT1 250GB                          | 1         | 0.52%   |
| WDC WD20 SPZX-11UA7T0 2TB                            | 1         | 0.52%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 0.52%   |
| WDC WD10SPZX-22Z10T0 1TB                             | 1         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 1         | 0.52%   |
| WDC WD10SPZX-08Z10 1TB                               | 1         | 0.52%   |
| WDC WD10SPCX-75KHST0 1TB                             | 1         | 0.52%   |
| WDC WD10JPVX-75JC3T0 1TB                             | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 17     | 37.14%  |
| WDC     | 10        | 12     | 28.57%  |
| Toshiba | 7         | 9      | 20%     |
| HGST    | 4         | 4      | 11.43%  |
| SABRENT | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 15     | 36.84%  |
| WDC                 | 3         | 4      | 7.89%   |
| SanDisk             | 3         | 4      | 7.89%   |
| Kingston            | 3         | 3      | 7.89%   |
| Crucial             | 3         | 3      | 7.89%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| Transcend           | 1         | 1      | 2.63%   |
| Toshiba             | 1         | 1      | 2.63%   |
| Team                | 1         | 2      | 2.63%   |
| Seagate             | 1         | 1      | 2.63%   |
| PNY                 | 1         | 2      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Corsair             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 97        | 138    | 55.75%  |
| SSD     | 36        | 43     | 20.69%  |
| HDD     | 35        | 43     | 20.11%  |
| MMC     | 4         | 5      | 2.3%    |
| Unknown | 2         | 3      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 97        | 138    | 58.79%  |
| SATA | 54        | 76     | 32.73%  |
| SAS  | 10        | 13     | 6.06%   |
| MMC  | 4         | 5      | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 38     | 46.38%  |
| 0.51-1.0   | 28        | 37     | 40.58%  |
| 1.01-2.0   | 5         | 5      | 7.25%   |
| 3.01-4.0   | 2         | 2      | 2.9%    |
| 4.01-10.0  | 2         | 4      | 2.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 61        | 42.07%  |
| 251-500        | 28        | 19.31%  |
| 501-1000       | 21        | 14.48%  |
| 1001-2000      | 11        | 7.59%   |
| 51-100         | 7         | 4.83%   |
| More than 3000 | 6         | 4.14%   |
| 21-50          | 3         | 2.07%   |
| 2001-3000      | 3         | 2.07%   |
| Unknown        | 3         | 2.07%   |
| 1-20           | 2         | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 36        | 23.53%  |
| 1-20           | 33        | 21.57%  |
| 101-250        | 31        | 20.26%  |
| 51-100         | 25        | 16.34%  |
| 251-500        | 13        | 8.5%    |
| 501-1000       | 7         | 4.58%   |
| 1001-2000      | 3         | 1.96%   |
| Unknown        | 3         | 1.96%   |
| More than 3000 | 1         | 0.65%   |
| 2001-3000      | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Transcend TS512GMTS800 512GB SSD | 1         | 1      | 33.33%  |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 33.33%  |
| Intel SSDSC2BA800G4R 800GB       | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Notebooks | Drives | Percent |
|-----------|-----------|--------|---------|
| Transcend | 1         | 1      | 33.33%  |
| Seagate   | 1         | 1      | 33.33%  |
| Intel     | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 112       | 187    | 75.68%  |
| Works    | 33        | 42     | 22.3%   |
| Malfunc  | 3         | 3      | 2.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 71        | 42.26%  |
| Samsung Electronics            | 27        | 16.07%  |
| SanDisk                        | 16        | 9.52%   |
| SK hynix                       | 14        | 8.33%   |
| Toshiba America Info Systems   | 12        | 7.14%   |
| Micron Technology              | 6         | 3.57%   |
| KIOXIA                         | 5         | 2.98%   |
| Lenovo                         | 3         | 1.79%   |
| Kingston Technology Company    | 3         | 1.79%   |
| AMD                            | 3         | 1.79%   |
| Silicon Motion                 | 2         | 1.19%   |
| Phison Electronics             | 2         | 1.19%   |
| Union Memory (Shenzhen)        | 1         | 0.6%    |
| Solid State Storage Technology | 1         | 0.6%    |
| Lite-On Technology             | 1         | 0.6%    |
| ADATA Technology               | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 20        | 11.76%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 11        | 6.47%   |
| SK hynix Non-Volatile memory controller                                       | 11        | 6.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 11        | 6.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 9         | 5.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 7         | 4.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 7         | 4.12%   |
| Micron Non-Volatile memory controller                                         | 6         | 3.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 6         | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 3.53%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 4         | 2.35%   |
| Intel SSD 660P Series                                                         | 4         | 2.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 4         | 2.35%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 3         | 1.76%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 3         | 1.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 3         | 1.76%   |
| KIOXIA NVMe SSD Controller BG4                                                | 3         | 1.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 1.76%   |
| Intel SATA Controller [RAID mode]                                             | 3         | 1.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 1.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 1.76%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 1.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 2         | 1.18%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 2         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.18%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 1.18%   |
| Lenovo Non-Volatile memory controller                                         | 2         | 1.18%   |
| KIOXIA Non-Volatile memory controller                                         | 2         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.18%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                 | 1         | 0.59%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.59%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 0.59%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 0.59%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.59%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 96        | 58.54%  |
| SATA | 56        | 34.15%  |
| RAID | 12        | 7.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 132       | 94.96%  |
| AMD    | 7         | 5.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 7.91%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 6.47%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 9         | 6.47%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 4.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 3.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 2.16%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 2.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.16%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.16%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.44%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.44%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.44%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.44%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.72%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 0.72%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.72%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.72%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.72%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.72%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.72%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.72%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.72%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.72%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.72%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 74        | 53.24%  |
| Intel Core i5   | 33        | 23.74%  |
| Other           | 11        | 7.91%   |
| Intel Xeon      | 6         | 4.32%   |
| Intel Core i3   | 5         | 3.6%    |
| AMD Ryzen 7     | 5         | 3.6%    |
| Intel Core i9   | 2         | 1.44%   |
| Intel Pentium   | 1         | 0.72%   |
| AMD Ryzen 7 PRO | 1         | 0.72%   |
| AMD Ryzen 5     | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 68        | 48.92%  |
| 2      | 34        | 24.46%  |
| 6      | 24        | 17.27%  |
| 8      | 11        | 7.91%   |
| 12     | 1         | 0.72%   |
| 10     | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 139       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 135       | 97.12%  |
| 1      | 4         | 2.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 134       | 95.04%  |
| Unknown        | 7         | 4.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 32        | 22.7%   |
| 0x806ea    | 14        | 9.93%   |
| 0xa0652    | 12        | 8.51%   |
| 0x906ea    | 8         | 5.67%   |
| 0x506e3    | 7         | 4.96%   |
| 0x306a9    | 7         | 4.96%   |
| 0x206a7    | 7         | 4.96%   |
| 0x406e3    | 6         | 4.26%   |
| 0x906ed    | 5         | 3.55%   |
| 0x806d1    | 5         | 3.55%   |
| 0x806c1    | 5         | 3.55%   |
| 0x906e9    | 4         | 2.84%   |
| 0x806e9    | 4         | 2.84%   |
| 0x306d4    | 4         | 2.84%   |
| 0x40651    | 3         | 2.13%   |
| 0x20655    | 3         | 2.13%   |
| Unknown    | 3         | 2.13%   |
| 0x08600103 | 2         | 1.42%   |
| 0x08108102 | 2         | 1.42%   |
| 0x906a4    | 1         | 0.71%   |
| 0x906a3    | 1         | 0.71%   |
| 0x90672    | 1         | 0.71%   |
| 0x706e5    | 1         | 0.71%   |
| 0x20652    | 1         | 0.71%   |
| 0x0a50000c | 1         | 0.71%   |
| 0x08600104 | 1         | 0.71%   |
| 0x08108109 | 1         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 68        | 48.57%  |
| Skylake          | 13        | 9.29%   |
| CometLake        | 12        | 8.57%   |
| SandyBridge      | 7         | 5%      |
| IvyBridge        | 7         | 5%      |
| Icelake          | 6         | 4.29%   |
| TigerLake        | 5         | 3.57%   |
| Westmere         | 4         | 2.86%   |
| Broadwell        | 4         | 2.86%   |
| Zen+             | 3         | 2.14%   |
| Zen 2            | 3         | 2.14%   |
| Haswell          | 3         | 2.14%   |
| Alderlake Hybrid | 3         | 2.14%   |
| Zen 3            | 1         | 0.71%   |
| Unknown          | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 119       | 66.85%  |
| Nvidia | 42        | 23.6%   |
| AMD    | 17        | 9.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 17        | 9.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 15        | 8.43%   |
| Intel UHD Graphics 620                                                        | 14        | 7.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 11        | 6.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 5.06%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 3.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 6         | 3.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 2.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 2.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 2.25%   |
| Intel HD Graphics 620                                                         | 4         | 2.25%   |
| Intel HD Graphics 5500                                                        | 4         | 2.25%   |
| Intel HD Graphics 530                                                         | 4         | 2.25%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 3         | 1.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 3         | 1.69%   |
| Intel HD Graphics 630                                                         | 3         | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 1.69%   |
| AMD Renoir                                                                    | 3         | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.12%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 2         | 1.12%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 2         | 1.12%   |
| Nvidia GM107GLM [Quadro M1000M]                                               | 2         | 1.12%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 2         | 1.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 1.12%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 1.12%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 1.12%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 0.56%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 0.56%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.56%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 1         | 0.56%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 1         | 0.56%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                              | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.56%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 1         | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 59.29%  |
| Intel + Nvidia | 29        | 20.71%  |
| 1 x Nvidia     | 11        | 7.86%   |
| Intel + AMD    | 7         | 5%      |
| 1 x AMD        | 7         | 5%      |
| AMD + Nvidia   | 3         | 2.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 121       | 85.21%  |
| Proprietary | 15        | 10.56%  |
| Unknown     | 6         | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 68.79%  |
| 1.01-2.0   | 13        | 9.22%   |
| 3.01-4.0   | 12        | 8.51%   |
| 5.01-6.0   | 7         | 4.96%   |
| 0.51-1.0   | 5         | 3.55%   |
| 0.01-0.5   | 3         | 2.13%   |
| 7.01-8.0   | 1         | 0.71%   |
| 2.01-3.0   | 1         | 0.71%   |
| 16.01-24.0 | 1         | 0.71%   |
| 8.01-16.0  | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 16.15%  |
| BOE                     | 25        | 13.02%  |
| Chimei Innolux          | 22        | 11.46%  |
| LG Display              | 21        | 10.94%  |
| Dell                    | 18        | 9.38%   |
| Samsung Electronics     | 17        | 8.85%   |
| Lenovo                  | 13        | 6.77%   |
| Sharp                   | 8         | 4.17%   |
| Goldstar                | 6         | 3.13%   |
| InfoVision              | 5         | 2.6%    |
| Hewlett-Packard         | 5         | 2.6%    |
| Acer                    | 3         | 1.56%   |
| Philips                 | 2         | 1.04%   |
| PANDA                   | 2         | 1.04%   |
| LGD                     | 2         | 1.04%   |
| BOE Technology Group    | 2         | 1.04%   |
| AOC                     | 2         | 1.04%   |
| Sun                     | 1         | 0.52%   |
| Sceptre Tech            | 1         | 0.52%   |
| Planar                  | 1         | 0.52%   |
| ITE                     | 1         | 0.52%   |
| Eizo                    | 1         | 0.52%   |
| CSO                     | 1         | 0.52%   |
| Chi Mei Optoelectronics | 1         | 0.52%   |
| ASUSTek Computer        | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 3.47%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 2.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 5         | 2.48%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 1.98%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 1.98%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.49%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3         | 1.49%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.49%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.49%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 3         | 1.49%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.99%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 2         | 0.99%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.99%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 0.99%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.99%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.99%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.99%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 2         | 0.99%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.99%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch            | 2         | 0.99%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.99%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.5%    |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch               | 1         | 0.5%    |
| Sceptre Tech Sceptre M24 SPT098C 1920x1080 544x303mm 24.5-inch        | 1         | 0.5%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.5%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.5%    |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.5%    |
| Samsung Electronics SMBX2431 SAM0771 1920x1080 531x299mm 24.0-inch    | 1         | 0.5%    |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1         | 0.5%    |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 59.15%  |
| 1366x768 (WXGA)    | 21        | 12.8%   |
| 3840x2160 (4K)     | 10        | 6.1%    |
| 2560x1440 (QHD)    | 8         | 4.88%   |
| 1600x900 (HD+)     | 7         | 4.27%   |
| 1920x1200 (WUXGA)  | 6         | 3.66%   |
| 2560x1080          | 3         | 1.83%   |
| 3440x1440          | 2         | 1.22%   |
| 1680x1050 (WSXGA+) | 2         | 1.22%   |
| Unknown            | 2         | 1.22%   |
| 6400x2160          | 1         | 0.61%   |
| 3840x1080          | 1         | 0.61%   |
| 2160x1350          | 1         | 0.61%   |
| 2048x1152          | 1         | 0.61%   |
| 1440x900 (WXGA+)   | 1         | 0.61%   |
| 1280x800 (WXGA)    | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 49        | 25.52%  |
| 14      | 38        | 19.79%  |
| 13      | 29        | 15.1%   |
| 24      | 18        | 9.38%   |
| 27      | 14        | 7.29%   |
| 23      | 10        | 5.21%   |
| 17      | 6         | 3.13%   |
| 34      | 5         | 2.6%    |
| 12      | 5         | 2.6%    |
| 21      | 4         | 2.08%   |
| Unknown | 4         | 2.08%   |
| 31      | 2         | 1.04%   |
| 22      | 2         | 1.04%   |
| 72      | 1         | 0.52%   |
| 49      | 1         | 0.52%   |
| 32      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| 18      | 1         | 0.52%   |
| 11      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 57.45%  |
| 501-600     | 35        | 18.62%  |
| 201-300     | 14        | 7.45%   |
| 401-500     | 8         | 4.26%   |
| 701-800     | 6         | 3.19%   |
| 351-400     | 6         | 3.19%   |
| 601-700     | 5         | 2.66%   |
| Unknown     | 4         | 2.13%   |
| 1501-2000   | 1         | 0.53%   |
| 1001-1500   | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 126       | 83.44%  |
| 16/10   | 14        | 9.27%   |
| 21/9    | 5         | 3.31%   |
| Unknown | 4         | 2.65%   |
| 32/9    | 1         | 0.66%   |
| 3/2     | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 59        | 31.05%  |
| 101-110        | 49        | 25.79%  |
| 201-250        | 25        | 13.16%  |
| 301-350        | 14        | 7.37%   |
| 71-80          | 8         | 4.21%   |
| 251-300        | 8         | 4.21%   |
| 351-500        | 7         | 3.68%   |
| 121-130        | 6         | 3.16%   |
| 61-70          | 5         | 2.63%   |
| Unknown        | 4         | 2.11%   |
| More than 1000 | 1         | 0.53%   |
| 51-60          | 1         | 0.53%   |
| 151-200        | 1         | 0.53%   |
| 141-150        | 1         | 0.53%   |
| 501-1000       | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 97        | 52.72%  |
| 51-100        | 39        | 21.2%   |
| 101-120       | 29        | 15.76%  |
| 161-240       | 9         | 4.89%   |
| More than 240 | 6         | 3.26%   |
| Unknown       | 4         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 60.54%  |
| 2     | 43        | 29.25%  |
| 3     | 8         | 5.44%   |
| 0     | 6         | 4.08%   |
| 4     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 122       | 58.1%   |
| Realtek Semiconductor             | 41        | 19.52%  |
| Lenovo                            | 17        | 8.1%    |
| Qualcomm Atheros                  | 8         | 3.81%   |
| Sierra Wireless                   | 2         | 0.95%   |
| Marvell Technology Group          | 2         | 0.95%   |
| Ericsson Business Mobile Networks | 2         | 0.95%   |
| Dell                              | 2         | 0.95%   |
| Broadcom Limited                  | 2         | 0.95%   |
| ASIX Electronics                  | 2         | 0.95%   |
| Xiaomi                            | 1         | 0.48%   |
| Samsung Electronics               | 1         | 0.48%   |
| Ralink                            | 1         | 0.48%   |
| Qualcomm Atheros Communications   | 1         | 0.48%   |
| MediaTek                          | 1         | 0.48%   |
| Luminary Micro                    | 1         | 0.48%   |
| ICS Advent                        | 1         | 0.48%   |
| Huawei Technologies               | 1         | 0.48%   |
| DisplayLink                       | 1         | 0.48%   |
| Broadcom                          | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 21        | 7.24%   |
| Intel Wireless 8265 / 8275                                                     | 18        | 6.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 15        | 5.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 15        | 5.17%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 12        | 4.14%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 3.79%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.45%   |
| Intel Wireless 8260                                                            | 9         | 3.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 3.1%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 2.76%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 2.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 2.07%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 2.07%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 2.07%   |
| Intel Wi-Fi 6 AX201                                                            | 5         | 1.72%   |
| Intel Wireless 7265                                                            | 4         | 1.38%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.38%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.38%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.38%   |
| Lenovo USB-C to LAN                                                            | 3         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.03%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 0.69%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.69%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.69%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.69%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.69%   |
| Intel Wireless 3165                                                            | 2         | 0.69%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.69%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 0.69%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 119       | 82.64%  |
| Realtek Semiconductor             | 10        | 6.94%   |
| Qualcomm Atheros                  | 6         | 4.17%   |
| Sierra Wireless                   | 2         | 1.39%   |
| Dell                              | 2         | 1.39%   |
| Ralink                            | 1         | 0.69%   |
| Qualcomm Atheros Communications   | 1         | 0.69%   |
| Ericsson Business Mobile Networks | 1         | 0.69%   |
| Broadcom Limited                  | 1         | 0.69%   |
| Broadcom                          | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 18        | 12.5%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 10.42%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 10.42%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 8.33%   |
| Intel Wireless 8260                                            | 9         | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 6.25%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 4.17%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.47%   |
| Intel Wireless 7265                                            | 4         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.39%   |
| Intel Wireless-AC 9260                                         | 2         | 1.39%   |
| Intel Wireless 3165                                            | 2         | 1.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.39%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 2         | 1.39%   |
| Sierra Wireless EM7565 QualcommÂ Snapdragonâ¢ X16 LTE-A   | 1         | 0.69%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                | 1         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.69%   |
| Intel Wireless 3160                                            | 1         | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.69%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1         | 0.69%   |
| Ericsson Business Mobile Networks N5321 gw                     | 1         | 0.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 79        | 54.86%  |
| Realtek Semiconductor    | 35        | 24.31%  |
| Lenovo                   | 17        | 11.81%  |
| Qualcomm Atheros         | 2         | 1.39%   |
| Marvell Technology Group | 2         | 1.39%   |
| ASIX Electronics         | 2         | 1.39%   |
| Xiaomi                   | 1         | 0.69%   |
| Samsung Electronics      | 1         | 0.69%   |
| MediaTek                 | 1         | 0.69%   |
| ICS Advent               | 1         | 0.69%   |
| Huawei Technologies      | 1         | 0.69%   |
| DisplayLink              | 1         | 0.69%   |
| Broadcom Limited         | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 21        | 14.58%  |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 7.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 7.64%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 6.94%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 5.56%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 4.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 4.17%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 4.17%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.78%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 2.78%   |
| Lenovo USB-C to LAN                                                            | 3         | 2.08%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 2.08%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 2.08%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.39%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.39%   |
| Lenovo ThinkPad Lan                                                            | 2         | 1.39%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.39%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.39%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 1.39%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.69%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.69%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.69%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.69%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.69%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.69%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 0.69%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.69%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.69%   |
| Huawei E353/E3131                                                              | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 52.69%  |
| Ethernet | 121       | 46.54%  |
| Modem    | 2         | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 67.97%  |
| Ethernet | 49        | 32.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 111       | 79.86%  |
| 1     | 28        | 20.14%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 127       | 90.71%  |
| Yes  | 13        | 9.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 80.7%   |
| Broadcom                        | 7         | 6.14%   |
| Realtek Semiconductor           | 4         | 3.51%   |
| IMC Networks                    | 3         | 2.63%   |
| Qualcomm Atheros Communications | 2         | 1.75%   |
| Foxconn / Hon Hai               | 2         | 1.75%   |
| Cambridge Silicon Radio         | 2         | 1.75%   |
| Ralink                          | 1         | 0.88%   |
| Dell                            | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 34        | 29.82%  |
| Intel Bluetooth wireless interface                                                  | 26        | 22.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 20        | 17.54%  |
| Intel AX200 Bluetooth                                                               | 6         | 5.26%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.75%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.75%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.75%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.88%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.88%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.88%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.88%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.88%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 132       | 62.86%  |
| Nvidia                 | 26        | 12.38%  |
| Lenovo                 | 13        | 6.19%   |
| AMD                    | 11        | 5.24%   |
| Realtek Semiconductor  | 4         | 1.9%    |
| GN Netcom              | 4         | 1.9%    |
| Texas Instruments      | 3         | 1.43%   |
| Plantronics            | 3         | 1.43%   |
| Generalplus Technology | 2         | 0.95%   |
| C-Media Electronics    | 2         | 0.95%   |
| Sony                   | 1         | 0.48%   |
| Logitech               | 1         | 0.48%   |
| LG Electronics         | 1         | 0.48%   |
| JMTek                  | 1         | 0.48%   |
| Google                 | 1         | 0.48%   |
| Focusrite-Novation     | 1         | 0.48%   |
| DSEA A/S               | 1         | 0.48%   |
| Dell                   | 1         | 0.48%   |
| Corsair                | 1         | 0.48%   |
| Blue Microphones       | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 24        | 10.81%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 18        | 8.11%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 15        | 6.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 13        | 5.86%   |
| Intel Comet Lake PCH cAVS                                                         | 12        | 5.41%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 8         | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 3.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 3.15%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 2.25%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5         | 2.25%   |
| Realtek Semiconductor USB Audio                                                   | 4         | 1.8%    |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 1.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 1.8%    |
| Intel CM238 HD Audio Controller                                                   | 4         | 1.8%    |
| Intel Broadwell-U Audio Controller                                                | 4         | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.8%    |
| Plantronics BT600                                                                 | 3         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                | 3         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.35%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 0.9%    |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 0.9%    |
| Nvidia Audio device                                                               | 2         | 0.9%    |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 0.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.9%    |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                 | 1         | 0.45%   |
| Sony DualSense wireless controller (PS5)                                          | 1         | 0.45%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.45%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.45%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 39.62%  |
| SK hynix            | 16        | 30.19%  |
| Kingston            | 3         | 5.66%   |
| Crucial             | 3         | 5.66%   |
| Unknown             | 2         | 3.77%   |
| Smart               | 2         | 3.77%   |
| Micron Technology   | 2         | 3.77%   |
| Unknown (0x0B5E)    | 1         | 1.89%   |
| Innodisk            | 1         | 1.89%   |
| GOODRAM             | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 5.36%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 5.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 3.57%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 3.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 3.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 3.57%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.79%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.79%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.79%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.79%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.79%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.79%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.79%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.79%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s      | 1         | 1.79%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.79%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 1.79%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 1         | 1.79%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.79%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 1.79%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s           | 1         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s           | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 64.29%  |
| DDR3   | 12        | 28.57%  |
| LPDDR5 | 1         | 2.38%   |
| LPDDR4 | 1         | 2.38%   |
| LPDDR3 | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 95.12%  |
| Row Of Chips | 2         | 4.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 16        | 35.56%  |
| 8192  | 16        | 35.56%  |
| 4096  | 10        | 22.22%  |
| 32768 | 2         | 4.44%   |
| 2048  | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 12        | 26.67%  |
| 2667  | 12        | 26.67%  |
| 1600  | 9         | 20%     |
| 2133  | 4         | 8.89%   |
| 2400  | 3         | 6.67%   |
| 1333  | 3         | 6.67%   |
| 6400  | 1         | 2.22%   |
| 1334  | 1         | 2.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| HP ENVY 4500 series | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 31.03%  |
| IMC Networks                           | 22        | 15.17%  |
| Acer                                   | 16        | 11.03%  |
| Realtek Semiconductor                  | 11        | 7.59%   |
| Microdia                               | 10        | 6.9%    |
| Sunplus Innovation Technology          | 8         | 5.52%   |
| Logitech                               | 7         | 4.83%   |
| Suyin                                  | 4         | 2.76%   |
| Lite-On Technology                     | 3         | 2.07%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.07%   |
| Unknown                                | 2         | 1.38%   |
| Syntek                                 | 2         | 1.38%   |
| Samsung Electronics                    | 2         | 1.38%   |
| Quanta                                 | 2         | 1.38%   |
| Microsoft                              | 2         | 1.38%   |
| Ruision                                | 1         | 0.69%   |
| Remo Tech                              | 1         | 0.69%   |
| Luxvisions Innotech Limited            | 1         | 0.69%   |
| LG Electronics                         | 1         | 0.69%   |
| Lenovo                                 | 1         | 0.69%   |
| KYE Systems (Mouse Systems)            | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 23        | 15.54%  |
| IMC Networks Integrated Camera                    | 18        | 12.16%  |
| Realtek Integrated_Webcam_HD                      | 9         | 6.08%   |
| Acer Integrated Camera                            | 8         | 5.41%   |
| Sunplus Integrated_Webcam_HD                      | 5         | 3.38%   |
| Chicony Integrated Camera (1280x720@30)           | 5         | 3.38%   |
| Acer SunplusIT Integrated Camera                  | 5         | 3.38%   |
| Microdia Integrated_Webcam_HD                     | 4         | 2.7%    |
| Logitech HD Pro Webcam C920                       | 4         | 2.7%    |
| Chicony HP HD Camera                              | 4         | 2.7%    |
| Lite-On Integrated Camera                         | 3         | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.03%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 2.03%   |
| Suyin Integrated_Webcam_HD                        | 2         | 1.35%   |
| Samsung Galaxy A5 (MTP)                           | 2         | 1.35%   |
| Microdia Webcam                                   | 2         | 1.35%   |
| Microdia Integrated Webcam                        | 2         | 1.35%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.35%   |
| Acer Integrated IR Camera                         | 2         | 1.35%   |
| Unknown FULL HD 1080P Webcam                      | 1         | 0.68%   |
| Unknown 720p HD Camera                            | 1         | 0.68%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.68%   |
| Syntek Integrated Camera                          | 1         | 0.68%   |
| Suyin RGBIR Camera                                | 1         | 0.68%   |
| Suyin HP Truevision HD                            | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.68%   |
| Sunplus Integrated Webcam                         | 1         | 0.68%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.68%   |
| Ruision UVC Camera                                | 1         | 0.68%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.68%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.68%   |
| Realtek NexiGo N960E FHD Webcam                   | 1         | 0.68%   |
| Quanta HP TrueVision HD Camera                    | 1         | 0.68%   |
| Quanta HP HD Camera                               | 1         | 0.68%   |
| Microsoft LifeCam VX-2000                         | 1         | 0.68%   |
| Microsoft LifeCam Cinema                          | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_E4HD            | 1         | 0.68%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.68%   |
| Logitech Webcam C925e                             | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 35        | 59.32%  |
| Validity Sensors           | 16        | 27.12%  |
| Shenzhen Goodix Technology | 4         | 6.78%   |
| Upek                       | 2         | 3.39%   |
| Samsung Electronics        | 1         | 1.69%   |
| Elan Microelectronics      | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 42.37%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 11.86%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.08%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.39%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.39%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS491                                                    | 1         | 1.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.69%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.69%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.69%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 55.56%  |
| Alcor Micro | 5         | 27.78%  |
| Lenovo      | 2         | 11.11%  |
| Upek        | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 27.78%  |
| Broadcom 5880                                              | 4         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 16.67%  |
| Broadcom 58200                                             | 3         | 16.67%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 50%     |
| 0     | 55        | 38.73%  |
| 2     | 12        | 8.45%   |
| 3     | 3         | 2.11%   |
| 4     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 54.63%  |
| Graphics card            | 17        | 15.74%  |
| Chipcard                 | 11        | 10.19%  |
| Multimedia controller    | 5         | 4.63%   |
| Card reader              | 5         | 4.63%   |
| Net/wireless             | 4         | 3.7%    |
| Net/ethernet             | 2         | 1.85%   |
| Bluetooth                | 2         | 1.85%   |
| Storage                  | 1         | 0.93%   |
| Communication controller | 1         | 0.93%   |
| Camera                   | 1         | 0.93%   |


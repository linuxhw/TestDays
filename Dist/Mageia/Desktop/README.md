Mageia - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 124

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte | GA-78LMT-USB3 SEx           | [2955e87822](https://linux-hardware.org/?probe=2955e87822) | Mar 29, 2022 |
| Gigabyte | G31M-S2C                    | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
| Gigabyte | H81M-S2H                    | [eac8a02717](https://linux-hardware.org/?probe=eac8a02717) | Mar 15, 2022 |
| Gigabyte | X570 AORUS ELITE WIFI       | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| MSI      | Z590-A PRO                  | [5f37c84d61](https://linux-hardware.org/?probe=5f37c84d61) | Mar 06, 2022 |
| Gigabyte | G31M-S2C                    | [d419223147](https://linux-hardware.org/?probe=d419223147) | Mar 06, 2022 |
| Gigabyte | X570 AORUS ELITE WIFI       | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASRock   | M3A UCC                     | [eaa75fb3f4](https://linux-hardware.org/?probe=eaa75fb3f4) | Feb 20, 2022 |
| ASRock   | M3A UCC                     | [ce306a4c86](https://linux-hardware.org/?probe=ce306a4c86) | Feb 20, 2022 |
| MSI      | B250M BAZOOKA               | [4a8f0501a2](https://linux-hardware.org/?probe=4a8f0501a2) | Feb 11, 2022 |
| ASRock   | G41M-VS3                    | [825356bf6c](https://linux-hardware.org/?probe=825356bf6c) | Feb 02, 2022 |
| HP       | 1589                        | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Gigabyte | H81M-DS2                    | [c0328d5402](https://linux-hardware.org/?probe=c0328d5402) | Jan 27, 2022 |
| Lenovo   | ThinkCentre M58e 7491B1G    | [568741947f](https://linux-hardware.org/?probe=568741947f) | Jan 12, 2022 |
| Gigabyte | B450 AORUS M                | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte | B450 AORUS M                | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| Gigabyte | B450 AORUS M                | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Lenovo   | ThinkCentre M58e 7491B1G    | [a77218c72c](https://linux-hardware.org/?probe=a77218c72c) | Jan 09, 2022 |
| Gigabyte | Z87X-UD5H-CF                | [a1a7854f7a](https://linux-hardware.org/?probe=a1a7854f7a) | Jan 04, 2022 |
| Gigabyte | Z87X-UD5H-CF                | [c44573411d](https://linux-hardware.org/?probe=c44573411d) | Dec 27, 2021 |
| MSI      | MPG X570 GAMING EDGE WIF... | [c1d67915d0](https://linux-hardware.org/?probe=c1d67915d0) | Dec 26, 2021 |
| ASUSTek  | ROG ZENITH EXTREME          | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| MSI      | MPG X570 GAMING EDGE WIF... | [fdc65fea9d](https://linux-hardware.org/?probe=fdc65fea9d) | Dec 08, 2021 |
| Gigabyte | H81M-S2H                    | [ceefdd4eac](https://linux-hardware.org/?probe=ceefdd4eac) | Dec 06, 2021 |
| Dell     | 0TP412                      | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [665331e075](https://linux-hardware.org/?probe=665331e075) | Nov 22, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| Gigabyte | H170-D3H-CF                 | [e18761a6b2](https://linux-hardware.org/?probe=e18761a6b2) | Sep 28, 2021 |
| Gigabyte | H170-D3H-CF                 | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| Dell     | 0TP412                      | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| MSI      | MAG B460M MORTAR            | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
| Gigabyte | H81M-S2H                    | [46740d8f33](https://linux-hardware.org/?probe=46740d8f33) | Aug 22, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [31e9013879](https://linux-hardware.org/?probe=31e9013879) | Aug 18, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [809f094941](https://linux-hardware.org/?probe=809f094941) | Aug 17, 2021 |
| Gigabyte | H81M-S2H                    | [894c915ecc](https://linux-hardware.org/?probe=894c915ecc) | Aug 17, 2021 |
| Gigabyte | B450 AORUS PRO WIFI-CF      | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [88ddc09b9e](https://linux-hardware.org/?probe=88ddc09b9e) | Jul 28, 2021 |
| Gigabyte | H81M-S2H                    | [f52713e401](https://linux-hardware.org/?probe=f52713e401) | Jul 28, 2021 |
| Dell     | 0TP412                      | [8788d078a0](https://linux-hardware.org/?probe=8788d078a0) | Jul 19, 2021 |
| ASUSTek  | PRIME X399-A                | [a2b6af1a6a](https://linux-hardware.org/?probe=a2b6af1a6a) | Jul 14, 2021 |
| Gigabyte | Z68XP-UD3P                  | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| Gigabyte | B450M DS3H-CF               | [1be802a26e](https://linux-hardware.org/?probe=1be802a26e) | Apr 18, 2021 |
| ECS      | IC780M-A2                   | [e3cbd0879b](https://linux-hardware.org/?probe=e3cbd0879b) | Apr 17, 2021 |
| ASUSTek  | Z170-P                      | [1ebcf0ea2c](https://linux-hardware.org/?probe=1ebcf0ea2c) | Apr 16, 2021 |
| ASUSTek  | Z170-P                      | [a95896e05e](https://linux-hardware.org/?probe=a95896e05e) | Apr 16, 2021 |
| Medion   | Z370H4-EM                   | [57435ad8fb](https://linux-hardware.org/?probe=57435ad8fb) | Apr 16, 2021 |
| ASUSTek  | SABERTOOTH P67              | [6d81c9d615](https://linux-hardware.org/?probe=6d81c9d615) | Apr 16, 2021 |
| Gigabyte | H61M-S2PV                   | [dce1091d81](https://linux-hardware.org/?probe=dce1091d81) | Apr 15, 2021 |
| Medion   | Z370H4-EM                   | [b88834e15d](https://linux-hardware.org/?probe=b88834e15d) | Apr 15, 2021 |
| HP       | 212B                        | [697e2f24f0](https://linux-hardware.org/?probe=697e2f24f0) | Apr 03, 2021 |
| Intel    | STL2-bd A28808-302          | [d6b5151873](https://linux-hardware.org/?probe=d6b5151873) | Apr 01, 2021 |
| Gigabyte | B450M DS3H-CF               | [dbb3c1865f](https://linux-hardware.org/?probe=dbb3c1865f) | Mar 29, 2021 |
| HP       | 212B                        | [69f528da9b](https://linux-hardware.org/?probe=69f528da9b) | Mar 28, 2021 |
| ASUSTek  | PRIME A320M-K               | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASRock   | M3A UCC                     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| HP       | 339A                        | [43e759b593](https://linux-hardware.org/?probe=43e759b593) | Feb 14, 2021 |
| HP       | 339A                        | [39d23c03ca](https://linux-hardware.org/?probe=39d23c03ca) | Feb 13, 2021 |
| Gigabyte | H81M-S2H                    | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Gigabyte | Z87X-UD5H-CF                | [adabf5b11e](https://linux-hardware.org/?probe=adabf5b11e) | Jan 31, 2021 |
| Gigabyte | B450M DS3H-CF               | [a399a43535](https://linux-hardware.org/?probe=a399a43535) | Jan 16, 2021 |
| Gigabyte | H81M-S2H                    | [0b7e0d2152](https://linux-hardware.org/?probe=0b7e0d2152) | Jan 15, 2021 |
| ASUSTek  | Z87-DELUXE                  | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| HP       | 339A                        | [ea7792c224](https://linux-hardware.org/?probe=ea7792c224) | Dec 26, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [932603ce99](https://linux-hardware.org/?probe=932603ce99) | Dec 25, 2020 |
| ASUSTek  | ROG ZENITH EXTREME          | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| Lenovo   | ThinkServer TS140           | [ec475a7f9a](https://linux-hardware.org/?probe=ec475a7f9a) | Dec 09, 2020 |
| ASRock   | H87M Pro4                   | [12185c0c75](https://linux-hardware.org/?probe=12185c0c75) | Dec 07, 2020 |
| ASRock   | H87M Pro4                   | [747bc56208](https://linux-hardware.org/?probe=747bc56208) | Dec 07, 2020 |
| Gigabyte | F2A88XM-DS2                 | [1b5123770e](https://linux-hardware.org/?probe=1b5123770e) | Dec 06, 2020 |
| Gigabyte | H81M-S2H                    | [3f948a0756](https://linux-hardware.org/?probe=3f948a0756) | Dec 03, 2020 |
| Gigabyte | H81M-S2H                    | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| Gigabyte | GA-78LMT-USB3 R2            | [1aec57de3b](https://linux-hardware.org/?probe=1aec57de3b) | Nov 20, 2020 |
| Gigabyte | H81M-S2H                    | [8f031786c5](https://linux-hardware.org/?probe=8f031786c5) | Nov 16, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [1bdc158142](https://linux-hardware.org/?probe=1bdc158142) | Nov 16, 2020 |
| ASUSTek  | PRIME B360-PLUS             | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| MSI      | MPG X570 GAMING EDGE WIF... | [fb717dc126](https://linux-hardware.org/?probe=fb717dc126) | Nov 05, 2020 |
| Gigabyte | H170-D3H-CF                 | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| Gigabyte | H81M-S2H                    | [a854973bf5](https://linux-hardware.org/?probe=a854973bf5) | Oct 25, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [e50d2bd553](https://linux-hardware.org/?probe=e50d2bd553) | Oct 18, 2020 |
| ZOTAC    | Unknown                     | [624888f3ab](https://linux-hardware.org/?probe=624888f3ab) | Oct 14, 2020 |
| Gigabyte | H170-D3H-CF                 | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| Gigabyte | H81M-S2H                    | [1a7d01552e](https://linux-hardware.org/?probe=1a7d01552e) | Oct 04, 2020 |
| Lenovo   | ThinkServer TS140           | [87f4eac666](https://linux-hardware.org/?probe=87f4eac666) | Sep 27, 2020 |
| Gigabyte | H81M-S2H                    | [8fa69c952c](https://linux-hardware.org/?probe=8fa69c952c) | Sep 15, 2020 |
| ASRock   | M3A UCC                     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock   | M3A UCC                     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| Gigabyte | H81M-S2H                    | [f6c7b24ad6](https://linux-hardware.org/?probe=f6c7b24ad6) | Aug 31, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [7fd8c75c95](https://linux-hardware.org/?probe=7fd8c75c95) | Aug 19, 2020 |
| Gigabyte | H81M-S2H                    | [14955a6413](https://linux-hardware.org/?probe=14955a6413) | Aug 19, 2020 |
| ASUSTek  | P8H61-M LE                  | [2ca048a380](https://linux-hardware.org/?probe=2ca048a380) | Jun 29, 2020 |
| ASRock   | H81M-VG4 R2.0               | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| HP       | 339A                        | [bbd2341205](https://linux-hardware.org/?probe=bbd2341205) | May 09, 2020 |
| HP       | 339A                        | [1334fcea56](https://linux-hardware.org/?probe=1334fcea56) | May 09, 2020 |
| MSI      | B360M MORTAR                | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [f6e5343aa5](https://linux-hardware.org/?probe=f6e5343aa5) | Mar 31, 2020 |
| ASUSTek  | H170M-PLUS                  | [6dd350fc4a](https://linux-hardware.org/?probe=6dd350fc4a) | Mar 31, 2020 |
| ASUSTek  | PRIME A320M-K               | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| Vorke    | V1 Plus                     | [c49c2bb635](https://linux-hardware.org/?probe=c49c2bb635) | Mar 29, 2020 |
| Gigabyte | H81M-S2H                    | [c61a5bbb12](https://linux-hardware.org/?probe=c61a5bbb12) | Mar 05, 2020 |
| ASRock   | X470 Taichi                 | [5125778e67](https://linux-hardware.org/?probe=5125778e67) | Mar 02, 2020 |
| Gigabyte | B85M-D3H                    | [00442cfd17](https://linux-hardware.org/?probe=00442cfd17) | Feb 25, 2020 |
| Gigabyte | Z87X-UD5H-CF                | [71a967abf8](https://linux-hardware.org/?probe=71a967abf8) | Feb 22, 2020 |
| Gigabyte | H81M-S2H                    | [52c3f45c8f](https://linux-hardware.org/?probe=52c3f45c8f) | Feb 22, 2020 |
| ASUSTek  | H170M-PLUS                  | [0ae790ac85](https://linux-hardware.org/?probe=0ae790ac85) | Feb 01, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [506294e8e9](https://linux-hardware.org/?probe=506294e8e9) | Jan 13, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [16e8d236b4](https://linux-hardware.org/?probe=16e8d236b4) | Jan 12, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [7df7d9c296](https://linux-hardware.org/?probe=7df7d9c296) | Dec 20, 2019 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [0c42dfc62c](https://linux-hardware.org/?probe=0c42dfc62c) | Dec 08, 2019 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | [2ef79b672c](https://linux-hardware.org/?probe=2ef79b672c) | Nov 15, 2019 |
| ASUSTek  | A55BM-K                     | [d58dbcdd06](https://linux-hardware.org/?probe=d58dbcdd06) | Nov 08, 2019 |
| MSI      | Z97-G43                     | [87e4cd50ce](https://linux-hardware.org/?probe=87e4cd50ce) | Apr 26, 2019 |
| ASRock   | X470 Taichi                 | [14a8808d2b](https://linux-hardware.org/?probe=14a8808d2b) | Apr 26, 2019 |
| Gigabyte | Z68X-UD3H-B3                | [28ea4213cb](https://linux-hardware.org/?probe=28ea4213cb) | Feb 25, 2019 |
| Gigabyte | Z68X-UD3H-B3                | [b9c55f2790](https://linux-hardware.org/?probe=b9c55f2790) | Feb 25, 2019 |
| ASRock   | X470 Taichi                 | [7b6ec43d58](https://linux-hardware.org/?probe=7b6ec43d58) | Jan 08, 2019 |
| ASRock   | X470 Taichi                 | [117cb09799](https://linux-hardware.org/?probe=117cb09799) | Dec 31, 2018 |
| Gigabyte | Z68X-UD3H-B3                | [0a61436f40](https://linux-hardware.org/?probe=0a61436f40) | Feb 15, 2018 |
| ASUSTek  | M5A97 R2.0                  | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |
| ASUSTek  | M4A78 PLUS                  | [ed9d8a148d](https://linux-hardware.org/?probe=ed9d8a148d) | Mar 06, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Mageia 8 | 32       | 50.79%  |
| Mageia 7 | 22       | 34.92%  |
| Mageia 9 | 4        | 6.35%   |
| Mageia 6 | 4        | 6.35%   |
| Mageia 5 | 1        | 1.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Mageia | 53       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.7.19-desktop-3.mga7      | 10       | 10.64%  |
| 5.10.27-desktop-1.mga8     | 7        | 7.45%   |
| 5.7.19-desktop-1.mga7      | 4        | 4.26%   |
| 5.5.4-desktop-1.mga7       | 4        | 4.26%   |
| 5.5.9-desktop-1.mga7       | 3        | 3.19%   |
| 5.15.23-desktop-1.mga8     | 3        | 3.19%   |
| 5.10.25-desktop-1.mga8     | 3        | 3.19%   |
| 5.10.12-desktop-1.mga7     | 3        | 3.19%   |
| 5.7.14-desktop-1.mga7      | 2        | 2.13%   |
| 5.6.14-desktop-2.mga7      | 2        | 2.13%   |
| 5.3.7-desktop-4.mga7       | 2        | 2.13%   |
| 5.15.16-desktop-1.mga8     | 2        | 2.13%   |
| 5.15.11-desktop-3.mga8     | 2        | 2.13%   |
| 5.10.60-desktop-2.mga8     | 2        | 2.13%   |
| 5.10.56-desktop-1.mga8     | 2        | 2.13%   |
| 5.10.52-desktop-1.mga8     | 2        | 2.13%   |
| 5.10.14-desktop-1.mga7     | 2        | 2.13%   |
| 5.9.3-desktop-1.mga8       | 1        | 1.06%   |
| 5.9.1-desktop-1.mga8       | 1        | 1.06%   |
| 5.8.14-desktop-1.mga8      | 1        | 1.06%   |
| 5.6.8-desktop-1.mga7       | 1        | 1.06%   |
| 5.6.6-desktop-1.mga7       | 1        | 1.06%   |
| 5.5.6-desktop-2.mga7       | 1        | 1.06%   |
| 5.5.13-desktop-1.mga7      | 1        | 1.06%   |
| 5.4.8-desktop-1.mga7       | 1        | 1.06%   |
| 5.4.12-desktop-1.mga7      | 1        | 1.06%   |
| 5.3.13-desktop-2.mga7      | 1        | 1.06%   |
| 5.16.18-server-1.mga8      | 1        | 1.06%   |
| 5.16.12-desktop-1.mga8     | 1        | 1.06%   |
| 5.16.10-desktop-2.mga8     | 1        | 1.06%   |
| 5.15.6-desktop-2.mga9      | 1        | 1.06%   |
| 5.15.6-desktop-2.mga8      | 1        | 1.06%   |
| 5.15.2-desktop-2.mga9      | 1        | 1.06%   |
| 5.15.18-desktop-2.mga8     | 1        | 1.06%   |
| 5.15.15-desktop-1.mga8     | 1        | 1.06%   |
| 5.15.10-desktop-1.mga9     | 1        | 1.06%   |
| 5.15.10-desktop-1.mga8     | 1        | 1.06%   |
| 5.14.9-desktop-1.mga9      | 1        | 1.06%   |
| 5.14.12-desktop-2.mga9     | 1        | 1.06%   |
| 5.14.10-desktop-1.mga8     | 1        | 1.06%   |
| 5.13.12-desktop-2.mga8     | 1        | 1.06%   |
| 5.12.15-desktop-1.mga8     | 1        | 1.06%   |
| 5.10.8-desktop-2.mga7      | 1        | 1.06%   |
| 5.10.78-desktop-1.mga8     | 1        | 1.06%   |
| 5.10.6-desktop-1.mga7      | 1        | 1.06%   |
| 5.10.48-desktop-1.mga8     | 1        | 1.06%   |
| 5.10.45-desktop-2.mga8     | 1        | 1.06%   |
| 5.10.20-desktop-2.mga7     | 1        | 1.06%   |
| 5.10.2-desktop-1.mga8      | 1        | 1.06%   |
| 5.1.0-desktop-0.rc6.1.mga7 | 1        | 1.06%   |
| 4.9.56-server-1.mga6       | 1        | 1.06%   |
| 4.19.13-desktop-1.mga7     | 1        | 1.06%   |
| 4.14.18-desktop-1.mga6     | 1        | 1.06%   |
| 4.14.106-desktop-1.mga6    | 1        | 1.06%   |
| 4.14.100-desktop-1.mga6    | 1        | 1.06%   |
| 4.1.15-desktop-2.mga5      | 1        | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.7.19   | 11       | 12.09%  |
| 5.10.27  | 7        | 7.69%   |
| 5.5.4    | 4        | 4.4%    |
| 5.5.9    | 3        | 3.3%    |
| 5.15.23  | 3        | 3.3%    |
| 5.10.25  | 3        | 3.3%    |
| 5.10.12  | 3        | 3.3%    |
| 5.7.14   | 2        | 2.2%    |
| 5.6.14   | 2        | 2.2%    |
| 5.3.7    | 2        | 2.2%    |
| 5.15.6   | 2        | 2.2%    |
| 5.15.16  | 2        | 2.2%    |
| 5.15.11  | 2        | 2.2%    |
| 5.15.10  | 2        | 2.2%    |
| 5.10.60  | 2        | 2.2%    |
| 5.10.56  | 2        | 2.2%    |
| 5.10.52  | 2        | 2.2%    |
| 5.10.14  | 2        | 2.2%    |
| 5.9.3    | 1        | 1.1%    |
| 5.9.1    | 1        | 1.1%    |
| 5.8.14   | 1        | 1.1%    |
| 5.6.8    | 1        | 1.1%    |
| 5.6.6    | 1        | 1.1%    |
| 5.5.6    | 1        | 1.1%    |
| 5.5.13   | 1        | 1.1%    |
| 5.4.8    | 1        | 1.1%    |
| 5.4.12   | 1        | 1.1%    |
| 5.3.13   | 1        | 1.1%    |
| 5.16.18  | 1        | 1.1%    |
| 5.16.12  | 1        | 1.1%    |
| 5.16.10  | 1        | 1.1%    |
| 5.15.2   | 1        | 1.1%    |
| 5.15.18  | 1        | 1.1%    |
| 5.15.15  | 1        | 1.1%    |
| 5.14.9   | 1        | 1.1%    |
| 5.14.12  | 1        | 1.1%    |
| 5.14.10  | 1        | 1.1%    |
| 5.13.12  | 1        | 1.1%    |
| 5.12.15  | 1        | 1.1%    |
| 5.10.8   | 1        | 1.1%    |
| 5.10.78  | 1        | 1.1%    |
| 5.10.6   | 1        | 1.1%    |
| 5.10.48  | 1        | 1.1%    |
| 5.10.45  | 1        | 1.1%    |
| 5.10.20  | 1        | 1.1%    |
| 5.10.2   | 1        | 1.1%    |
| 5.1.0    | 1        | 1.1%    |
| 4.9.56   | 1        | 1.1%    |
| 4.19.13  | 1        | 1.1%    |
| 4.14.18  | 1        | 1.1%    |
| 4.14.106 | 1        | 1.1%    |
| 4.14.100 | 1        | 1.1%    |
| 4.1.15   | 1        | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 19       | 24.68%  |
| 5.15    | 13       | 16.88%  |
| 5.7     | 11       | 14.29%  |
| 5.5     | 8        | 10.39%  |
| 5.6     | 4        | 5.19%   |
| 5.16    | 3        | 3.9%    |
| 5.14    | 3        | 3.9%    |
| 4.14    | 3        | 3.9%    |
| 5.9     | 2        | 2.6%    |
| 5.4     | 2        | 2.6%    |
| 5.3     | 2        | 2.6%    |
| 5.8     | 1        | 1.3%    |
| 5.13    | 1        | 1.3%    |
| 5.12    | 1        | 1.3%    |
| 5.1     | 1        | 1.3%    |
| 4.9     | 1        | 1.3%    |
| 4.19    | 1        | 1.3%    |
| 4.1     | 1        | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 52       | 98.11%  |
| i686   | 1        | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KDE5          | 20       | 32.26%  |
| KDE           | 16       | 25.81%  |
| GNOME         | 7        | 11.29%  |
| Unknown       | 7        | 11.29%  |
| Cinnamon      | 5        | 8.06%   |
| LXDE          | 3        | 4.84%   |
| MATE          | 1        | 1.61%   |
| LXQt          | 1        | 1.61%   |
| KDE4          | 1        | 1.61%   |
| GNOME Classic | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 51       | 94.44%  |
| Wayland | 2        | 3.7%    |
| Tty     | 1        | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 53.7%   |
| SDDM    | 20       | 37.04%  |
| LightDM | 2        | 3.7%    |
| XDM     | 1        | 1.85%   |
| TDM     | 1        | 1.85%   |
| GDM     | 1        | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| fr_FR   | 11       | 20%     |
| en_US   | 8        | 14.55%  |
| Unknown | 8        | 14.55%  |
| de_DE   | 7        | 12.73%  |
| ru_RU   | 5        | 9.09%   |
| en_GB   | 3        | 5.45%   |
| sv_SE   | 2        | 3.64%   |
| pt_BR   | 2        | 3.64%   |
| it_IT   | 2        | 3.64%   |
| zh_TW   | 1        | 1.82%   |
| sl_SI   | 1        | 1.82%   |
| pl_PL   | 1        | 1.82%   |
| fr_BE   | 1        | 1.82%   |
| es_AR   | 1        | 1.82%   |
| en_CA   | 1        | 1.82%   |
| cs_CZ   | 1        | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 38       | 70.37%  |
| EFI  | 16       | 29.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 41       | 74.55%  |
| Unknown  | 6        | 10.91%  |
| Xfs      | 5        | 9.09%   |
| Btrfs    | 2        | 3.64%   |
| Reiserfs | 1        | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 42.59%  |
| GPT     | 18       | 33.33%  |
| MBR     | 13       | 24.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 86.79%  |
| Yes       | 7        | 13.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 79.63%  |
| Yes       | 11       | 20.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 16       | 30.19%  |
| ASUSTek Computer    | 14       | 26.42%  |
| MSI                 | 6        | 11.32%  |
| ASRock              | 5        | 9.43%   |
| Hewlett-Packard     | 3        | 5.66%   |
| Lenovo              | 2        | 3.77%   |
| Dell                | 2        | 3.77%   |
| ZOTAC               | 1        | 1.89%   |
| Vorke               | 1        | 1.89%   |
| Medion              | 1        | 1.89%   |
| Intel               | 1        | 1.89%   |
| ECS                 | 1        | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Gigabyte Z68X-UD3H-B3               | 2        | 3.77%   |
| Dell Precision WorkStation T3400    | 2        | 3.77%   |
| ASUS SABERTOOTH 990FX R2.0          | 2        | 3.77%   |
| Vorke V1 Plus                       | 1        | 1.89%   |
| MSI MS-7D09                         | 1        | 1.89%   |
| MSI MS-7C82                         | 1        | 1.89%   |
| MSI MS-7C37                         | 1        | 1.89%   |
| MSI MS-7B23                         | 1        | 1.89%   |
| MSI MS-7A70                         | 1        | 1.89%   |
| MSI MS-7816                         | 1        | 1.89%   |
| Medion MD34161/C708                 | 1        | 1.89%   |
| Lenovo ThinkCentre M58e 7491B1G     | 1        | 1.89%   |
| Lenovo 70A4000HUX ThinkServer TS140 | 1        | 1.89%   |
| Intel STL2                          | 1        | 1.89%   |
| HP Z440 Workstation                 | 1        | 1.89%   |
| HP Z420 Workstation                 | 1        | 1.89%   |
| HP Compaq Pro 6300 SFF              | 1        | 1.89%   |
| Gigabyte Z87X-UD5H                  | 1        | 1.89%   |
| Gigabyte Z68XP-UD3P                 | 1        | 1.89%   |
| Gigabyte X570 AORUS ELITE WIFI      | 1        | 1.89%   |
| Gigabyte H81M-S2H                   | 1        | 1.89%   |
| Gigabyte H81M-DS2                   | 1        | 1.89%   |
| Gigabyte H61M-S2PV                  | 1        | 1.89%   |
| Gigabyte H170-D3H                   | 1        | 1.89%   |
| Gigabyte GA-78LMT-USB3 R2           | 1        | 1.89%   |
| Gigabyte GA-78LMT-USB3 6.0          | 1        | 1.89%   |
| Gigabyte G31M-ES2C                  | 1        | 1.89%   |
| Gigabyte F2A88XM-DS2                | 1        | 1.89%   |
| Gigabyte B85M-D3H                   | 1        | 1.89%   |
| Gigabyte B450M DS3H                 | 1        | 1.89%   |
| Gigabyte B450 AORUS PRO WIFI        | 1        | 1.89%   |
| ECS IC780M-A2                       | 1        | 1.89%   |
| ASUS Z170-P                         | 1        | 1.89%   |
| ASUS SABERTOOTH P67                 | 1        | 1.89%   |
| ASUS ROG ZENITH EXTREME             | 1        | 1.89%   |
| ASUS PRIME X399-A                   | 1        | 1.89%   |
| ASUS PRIME B360-PLUS                | 1        | 1.89%   |
| ASUS PRIME A320M-K                  | 1        | 1.89%   |
| ASUS P8H61-M LE                     | 1        | 1.89%   |
| ASUS M5A97 R2.0                     | 1        | 1.89%   |
| ASUS M4A78 PLUS                     | 1        | 1.89%   |
| ASUS H170M-PLUS                     | 1        | 1.89%   |
| ASUS All Series                     | 1        | 1.89%   |
| ASUS A55BM-K                        | 1        | 1.89%   |
| ASRock X470 Taichi                  | 1        | 1.89%   |
| ASRock M3A UCC                      | 1        | 1.89%   |
| ASRock H87M Pro4                    | 1        | 1.89%   |
| ASRock H81M-VG4 R2.0                | 1        | 1.89%   |
| ASRock G41M-VS3                     | 1        | 1.89%   |
| Unknown                             | 1        | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS SABERTOOTH        | 3        | 5.66%   |
| ASUS PRIME             | 3        | 5.66%   |
| Gigabyte Z68X-UD3H-B3  | 2        | 3.77%   |
| Gigabyte GA-78LMT-USB3 | 2        | 3.77%   |
| Dell Precision         | 2        | 3.77%   |
| Vorke V1               | 1        | 1.89%   |
| MSI MS-7D09            | 1        | 1.89%   |
| MSI MS-7C82            | 1        | 1.89%   |
| MSI MS-7C37            | 1        | 1.89%   |
| MSI MS-7B23            | 1        | 1.89%   |
| MSI MS-7A70            | 1        | 1.89%   |
| MSI MS-7816            | 1        | 1.89%   |
| Medion MD34161         | 1        | 1.89%   |
| Lenovo ThinkCentre     | 1        | 1.89%   |
| Lenovo 70A4000HUX      | 1        | 1.89%   |
| Intel STL2             | 1        | 1.89%   |
| HP Z440                | 1        | 1.89%   |
| HP Z420                | 1        | 1.89%   |
| HP Compaq              | 1        | 1.89%   |
| Gigabyte Z87X-UD5H     | 1        | 1.89%   |
| Gigabyte Z68XP-UD3P    | 1        | 1.89%   |
| Gigabyte X570          | 1        | 1.89%   |
| Gigabyte H81M-S2H      | 1        | 1.89%   |
| Gigabyte H81M-DS2      | 1        | 1.89%   |
| Gigabyte H61M-S2PV     | 1        | 1.89%   |
| Gigabyte H170-D3H      | 1        | 1.89%   |
| Gigabyte G31M-ES2C     | 1        | 1.89%   |
| Gigabyte F2A88XM-DS2   | 1        | 1.89%   |
| Gigabyte B85M-D3H      | 1        | 1.89%   |
| Gigabyte B450M         | 1        | 1.89%   |
| Gigabyte B450          | 1        | 1.89%   |
| ECS IC780M-A2          | 1        | 1.89%   |
| ASUS Z170-P            | 1        | 1.89%   |
| ASUS ROG               | 1        | 1.89%   |
| ASUS P8H61-M           | 1        | 1.89%   |
| ASUS M5A97             | 1        | 1.89%   |
| ASUS M4A78             | 1        | 1.89%   |
| ASUS H170M-PLUS        | 1        | 1.89%   |
| ASUS All               | 1        | 1.89%   |
| ASUS A55BM-K           | 1        | 1.89%   |
| ASRock X470            | 1        | 1.89%   |
| ASRock M3A             | 1        | 1.89%   |
| ASRock H87M            | 1        | 1.89%   |
| ASRock H81M-VG4        | 1        | 1.89%   |
| ASRock G41M-VS3        | 1        | 1.89%   |
| Unknown                | 1        | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 18.87%  |
| 2018 | 6        | 11.32%  |
| 2012 | 6        | 11.32%  |
| 2017 | 5        | 9.43%   |
| 2015 | 4        | 7.55%   |
| 2014 | 4        | 7.55%   |
| 2019 | 3        | 5.66%   |
| 2011 | 3        | 5.66%   |
| 2009 | 3        | 5.66%   |
| 2008 | 3        | 5.66%   |
| 2010 | 2        | 3.77%   |
| 2021 | 1        | 1.89%   |
| 2020 | 1        | 1.89%   |
| 2016 | 1        | 1.89%   |
| 2002 | 1        | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 53       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 53       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 30.36%  |
| 8.01-16.0   | 11       | 19.64%  |
| 32.01-64.0  | 9        | 16.07%  |
| 4.01-8.0    | 8        | 14.29%  |
| 3.01-4.0    | 5        | 8.93%   |
| 64.01-256.0 | 4        | 7.14%   |
| 24.01-32.0  | 2        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 18       | 25.71%  |
| 1.01-2.0   | 18       | 25.71%  |
| 4.01-8.0   | 15       | 21.43%  |
| 3.01-4.0   | 10       | 14.29%  |
| 8.01-16.0  | 6        | 8.57%   |
| 0.51-1.0   | 2        | 2.86%   |
| 16.01-24.0 | 1        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 16       | 28.57%  |
| 2      | 16       | 28.57%  |
| 1      | 10       | 17.86%  |
| 5      | 6        | 10.71%  |
| 4      | 4        | 7.14%   |
| 6      | 2        | 3.57%   |
| 8      | 1        | 1.79%   |
| 7      | 1        | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 50.94%  |
| No        | 26       | 49.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 51       | 96.23%  |
| No        | 2        | 3.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 72.22%  |
| Yes       | 15       | 27.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 60.38%  |
| Yes       | 21       | 39.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| France     | 12       | 22.64%  |
| USA        | 8        | 15.09%  |
| Germany    | 7        | 13.21%  |
| UK         | 4        | 7.55%   |
| Ukraine    | 3        | 5.66%   |
| Sweden     | 2        | 3.77%   |
| Russia     | 2        | 3.77%   |
| Canada     | 2        | 3.77%   |
| Brazil     | 2        | 3.77%   |
| Taiwan     | 1        | 1.89%   |
| Slovenia   | 1        | 1.89%   |
| Poland     | 1        | 1.89%   |
| Luxembourg | 1        | 1.89%   |
| Kenya      | 1        | 1.89%   |
| Italy      | 1        | 1.89%   |
| Greece     | 1        | 1.89%   |
| Czechia    | 1        | 1.89%   |
| Belgium    | 1        | 1.89%   |
| Belarus    | 1        | 1.89%   |
| Argentina  | 1        | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Desktops | Percent |
|------------------------------|----------|---------|
| Waterloo                     | 3        | 4.23%   |
| Paris                        | 3        | 4.23%   |
| Mala Danylivka               | 3        | 4.23%   |
| Kharkiv                      | 3        | 4.23%   |
| Oakland                      | 2        | 2.82%   |
| Kingston upon Thames         | 2        | 2.82%   |
| Grants Pass                  | 2        | 2.82%   |
| Cologne                      | 2        | 2.82%   |
| Basingstoke                  | 2        | 2.82%   |
| Yakutsk                      | 1        | 1.41%   |
| Werl                         | 1        | 1.41%   |
| Voronezh                     | 1        | 1.41%   |
| Volos                        | 1        | 1.41%   |
| Turin                        | 1        | 1.41%   |
| Tresserve                    | 1        | 1.41%   |
| Teddington                   | 1        | 1.41%   |
| Strasbourg                   | 1        | 1.41%   |
| Sternberk                    | 1        | 1.41%   |
| Sartrouville                 | 1        | 1.41%   |
| Sainte-GeneviÃ¨ve-des-Bois | 1        | 1.41%   |
| Saint-Michel-sur-Orge        | 1        | 1.41%   |
| Rio de Janeiro               | 1        | 1.41%   |
| Penmarch                     | 1        | 1.41%   |
| Palermo                      | 1        | 1.41%   |
| Nova Vodolaha                | 1        | 1.41%   |
| Nova Gorica                  | 1        | 1.41%   |
| Niedermodern                 | 1        | 1.41%   |
| New Taipei                   | 1        | 1.41%   |
| Nairobi                      | 1        | 1.41%   |
| Munich                       | 1        | 1.41%   |
| Mannheim                     | 1        | 1.41%   |
| Luxembourg                   | 1        | 1.41%   |
| Londrina                     | 1        | 1.41%   |
| LiГЁge                     | 1        | 1.41%   |
| Le Plessis-Robinson          | 1        | 1.41%   |
| Kehychivka                   | 1        | 1.41%   |
| Kalisz                       | 1        | 1.41%   |
| Jena                         | 1        | 1.41%   |
| Huty                         | 1        | 1.41%   |
| Helsingborg                  | 1        | 1.41%   |
| Hammersmith                  | 1        | 1.41%   |
| Frankfurt am Main            | 1        | 1.41%   |
| Fort Bragg                   | 1        | 1.41%   |
| Farnborough                  | 1        | 1.41%   |
| Essen                        | 1        | 1.41%   |
| Erlangen                     | 1        | 1.41%   |
| Edinburgh                    | 1        | 1.41%   |
| Draveil                      | 1        | 1.41%   |
| Delta                        | 1        | 1.41%   |
| Concarneau                   | 1        | 1.41%   |
| Colindale                    | 1        | 1.41%   |
| Beurlay                      | 1        | 1.41%   |
| Berlezh                      | 1        | 1.41%   |
| Bamberg                      | 1        | 1.41%   |
| Arlington                    | 1        | 1.41%   |
| Arboga                       | 1        | 1.41%   |
| Angers                       | 1        | 1.41%   |
| Aix-les-Bains                | 1        | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 146    | 27.91%  |
| Seagate             | 21       | 38     | 16.28%  |
| Samsung Electronics | 15       | 19     | 11.63%  |
| Kingston            | 9        | 17     | 6.98%   |
| SanDisk             | 7        | 13     | 5.43%   |
| Toshiba             | 6        | 13     | 4.65%   |
| Hitachi             | 5        | 5      | 3.88%   |
| PNY                 | 4        | 5      | 3.1%    |
| HGST                | 3        | 3      | 2.33%   |
| Crucial             | 3        | 7      | 2.33%   |
| Unknown             | 2        | 2      | 1.55%   |
| OCZ-VERTEX          | 2        | 2      | 1.55%   |
| OCZ                 | 2        | 2      | 1.55%   |
| Intel               | 2        | 2      | 1.55%   |
| A-DATA Technology   | 2        | 3      | 1.55%   |
| XPG                 | 1        | 4      | 0.78%   |
| Verbatim            | 1        | 1      | 0.78%   |
| Transcend           | 1        | 1      | 0.78%   |
| Team                | 1        | 1      | 0.78%   |
| SK Hynix            | 1        | 1      | 0.78%   |
| Phison              | 1        | 2      | 0.78%   |
| HUAWEI              | 1        | 1      | 0.78%   |
| FORESEE             | 1        | 1      | 0.78%   |
| Corsair             | 1        | 1      | 0.78%   |
| Asmedia             | 1        | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4        | 2.67%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 2%      |
| Samsung SSD 860 EVO 250GB        | 3        | 2%      |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2        | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 1.33%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2        | 1.33%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 1.33%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 1.33%   |
| WDC WD10EFRX-68PJCN0 1TB         | 2        | 1.33%   |
| Toshiba HDWD120 2TB              | 2        | 1.33%   |
| Seagate ST3500418AS 500GB        | 2        | 1.33%   |
| Seagate ST32000644NS 2TB         | 2        | 1.33%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.33%   |
| SanDisk SDSSDA120G 120GB         | 2        | 1.33%   |
| SanDisk Extreme SSD 2TB          | 2        | 1.33%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.33%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.33%   |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2        | 1.33%   |
| Kingston SV300S37A240G 240GB SSD | 2        | 1.33%   |
| Kingston SH103S3120G 120GB SSD   | 2        | 1.33%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.33%   |
| Intel SSDSC2CW120A3 120GB        | 2        | 1.33%   |
| Hitachi HDS722020ALA330 2TB      | 2        | 1.33%   |
| HGST HUS726040ALE611 4TB         | 2        | 1.33%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 1.33%   |
| XPG NVMe SSD Drive 2TB           | 1        | 0.67%   |
| XPG NVMe SSD Drive 1024GB        | 1        | 0.67%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1        | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.67%   |
| WDC WDS100T2B0A 1TB SSD          | 1        | 0.67%   |
| WDC WD800BB-00JHC0 80GB          | 1        | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.67%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.67%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.67%   |
| WDC WD4000FYYZ-01UL1B2 4TB       | 1        | 0.67%   |
| WDC WD3200KS-00PFB0 320GB        | 1        | 0.67%   |
| WDC WD3200AAJS-00B4A0 320GB      | 1        | 0.67%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1        | 0.67%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1        | 0.67%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 0.67%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1        | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.67%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 0.67%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.67%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1        | 0.67%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 0.67%   |
| WDC WD141KRYZ-01C66B0 14TB       | 1        | 0.67%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1        | 0.67%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1        | 0.67%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 0.67%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.67%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.67%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.67%   |
| WDC WD10EARS-00MVWB0 1TB         | 1        | 0.67%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.67%   |
| WDC WD1001FAES-75W7A0 1TB        | 1        | 0.67%   |
| Verbatim USB External SSD 256GB  | 1        | 0.67%   |
| Unknown SD/MMC/MS PRO 32GB       | 1        | 0.67%   |
| Unknown L200 Hard drive 2TB      | 1        | 0.67%   |
| Transcend TS512GSSD370 512GB     | 1        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 129    | 42.86%  |
| Seagate             | 20       | 36     | 28.57%  |
| Toshiba             | 6        | 13     | 8.57%   |
| Hitachi             | 5        | 5      | 7.14%   |
| Samsung Electronics | 3        | 5      | 4.29%   |
| HGST                | 3        | 3      | 4.29%   |
| Unknown             | 2        | 2      | 2.86%   |
| Asmedia             | 1        | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 12     | 21.57%  |
| Kingston            | 8        | 14     | 15.69%  |
| WDC                 | 6        | 16     | 11.76%  |
| SanDisk             | 5        | 7      | 9.8%    |
| PNY                 | 4        | 5      | 7.84%   |
| Crucial             | 3        | 7      | 5.88%   |
| OCZ-VERTEX          | 2        | 2      | 3.92%   |
| OCZ                 | 2        | 2      | 3.92%   |
| Intel               | 2        | 2      | 3.92%   |
| A-DATA Technology   | 2        | 3      | 3.92%   |
| Verbatim            | 1        | 1      | 1.96%   |
| Transcend           | 1        | 1      | 1.96%   |
| Team                | 1        | 1      | 1.96%   |
| SK Hynix            | 1        | 1      | 1.96%   |
| FORESEE             | 1        | 1      | 1.96%   |
| Corsair             | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 194    | 52.81%  |
| SSD     | 33       | 76     | 37.08%  |
| NVMe    | 7        | 18     | 7.87%   |
| Unknown | 2        | 3      | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 54       | 256    | 78.26%  |
| SAS  | 8        | 17     | 11.59%  |
| NVMe | 7        | 18     | 10.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 45       | 99     | 43.69%  |
| 0.51-1.0   | 28       | 92     | 27.18%  |
| 1.01-2.0   | 16       | 22     | 15.53%  |
| 2.01-3.0   | 6        | 44     | 5.83%   |
| 3.01-4.0   | 5        | 7      | 4.85%   |
| 4.01-10.0  | 2        | 5      | 1.94%   |
| 10.01-20.0 | 1        | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 15       | 26.32%  |
| 501-1000       | 13       | 22.81%  |
| 2001-3000      | 8        | 14.04%  |
| 1001-2000      | 7        | 12.28%  |
| 101-250        | 6        | 10.53%  |
| 251-500        | 5        | 8.77%   |
| 51-100         | 2        | 3.51%   |
| Unknown        | 1        | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 17.46%  |
| 251-500        | 10       | 15.87%  |
| 1001-2000      | 10       | 15.87%  |
| 501-1000       | 9        | 14.29%  |
| 51-100         | 8        | 12.7%   |
| More than 3000 | 6        | 9.52%   |
| 1-20           | 5        | 7.94%   |
| 2001-3000      | 2        | 3.17%   |
| 21-50          | 1        | 1.59%   |
| Unknown        | 1        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2        | 2      | 16.67%  |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 8.33%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 8.33%   |
| WDC WD1001FAES-75W7A0 1TB             | 1        | 1      | 8.33%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 8.33%   |
| Seagate ST3250410AS 250GB             | 1        | 1      | 8.33%   |
| Seagate ST2000VN004-2E4164 2TB        | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 8.33%   |
| OCZ VERTEX3 120GB SSD                 | 1        | 1      | 8.33%   |
| HGST HTS725050A7E630 500GB            | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 4        | 4      | 36.36%  |
| WDC      | 2        | 3      | 18.18%  |
| Intel    | 2        | 2      | 18.18%  |
| SK Hynix | 1        | 1      | 9.09%   |
| OCZ      | 1        | 1      | 9.09%   |
| HGST     | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 57.14%  |
| WDC     | 2        | 3      | 28.57%  |
| HGST    | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 8      | 60%     |
| SSD  | 4        | 4      | 40%     |

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
| Detected | 29       | 119    | 43.94%  |
| Works    | 27       | 160    | 40.91%  |
| Malfunc  | 10       | 12     | 15.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 34       | 45.95%  |
| AMD                         | 18       | 24.32%  |
| Marvell Technology Group    | 7        | 9.46%   |
| ASMedia Technology          | 5        | 6.76%   |
| Sandisk                     | 3        | 4.05%   |
| Phison Electronics          | 2        | 2.7%    |
| Samsung Electronics         | 1        | 1.35%   |
| Kingston Technology Company | 1        | 1.35%   |
| JMicron Technology          | 1        | 1.35%   |
| Broadcom                    | 1        | 1.35%   |
| ADATA Technology            | 1        | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 8.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 7.29%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 5.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 5.21%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4        | 4.17%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 4.17%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.13%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.08%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.08%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.04%   |
| Phison E7 NVMe Controller                                                               | 1        | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.04%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.04%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.04%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.04%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.04%   |
| Intel C610/X99 series chipset 4-port SATA Controller [IDE mode]                         | 1        | 1.04%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.04%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.04%   |
| Broadcom OSB4 IDE Controller                                                            | 1        | 1.04%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1        | 1.04%   |
| AMD SB600 IDE                                                                           | 1        | 1.04%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.04%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.04%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 44       | 62.86%  |
| IDE  | 15       | 21.43%  |
| NVMe | 7        | 10%     |
| RAID | 3        | 4.29%   |
| SAS  | 1        | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 66.04%  |
| AMD    | 18       | 33.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz                | 2        | 3.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz               | 2        | 3.7%    |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2        | 3.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 3.7%    |
| AMD FX-8350 Eight-Core Processor                | 2        | 3.7%    |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz              | 1        | 1.85%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1        | 1.85%   |
| Intel Pentium III (Coppermine)                  | 1        | 1.85%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1        | 1.85%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 1.85%   |
| Intel Pentium CPU G3450 @ 3.40GHz               | 1        | 1.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 1.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 1.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 1.85%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 1.85%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1        | 1.85%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.85%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 1.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.85%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 1.85%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.85%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.85%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 1.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 1.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.85%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 1        | 1.85%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 1.85%   |
| Intel Celeron CPU G1830 @ 2.80GHz               | 1        | 1.85%   |
| Intel 11th Gen Core i9-11900 @ 2.50GHz          | 1        | 1.85%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.85%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1        | 1.85%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 1.85%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 1.85%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 1.85%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 1.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1        | 1.85%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 1.85%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 1.85%   |
| AMD Phenom II X6 1100T Processor                | 1        | 1.85%   |
| AMD Phenom II X4 955 Processor                  | 1        | 1.85%   |
| AMD FX-8320 Eight-Core Processor                | 1        | 1.85%   |
| AMD FX-8120 Eight-Core Processor                | 1        | 1.85%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 1.85%   |
| AMD Athlon II X3 455 Processor                  | 1        | 1.85%   |
| AMD A8-6600K APU with Radeon HD Graphics        | 1        | 1.85%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 9        | 16.98%  |
| Intel Core i5           | 8        | 15.09%  |
| Intel Core i3           | 5        | 9.43%   |
| AMD FX                  | 5        | 9.43%   |
| Intel Xeon              | 2        | 3.77%   |
| Intel Core 2 Duo        | 2        | 3.77%   |
| Intel Celeron           | 2        | 3.77%   |
| AMD Ryzen Threadripper  | 2        | 3.77%   |
| AMD Ryzen 7             | 2        | 3.77%   |
| AMD Ryzen 5             | 2        | 3.77%   |
| Other                   | 1        | 1.89%   |
| Intel Pentium III       | 1        | 1.89%   |
| Intel Pentium Gold      | 1        | 1.89%   |
| Intel Pentium Dual-Core | 1        | 1.89%   |
| Intel Pentium           | 1        | 1.89%   |
| Intel Core 2 Quad       | 1        | 1.89%   |
| Intel Core 2            | 1        | 1.89%   |
| AMD Ryzen 9             | 1        | 1.89%   |
| AMD Ryzen 3             | 1        | 1.89%   |
| AMD Phenom II X6        | 1        | 1.89%   |
| AMD Phenom II X4        | 1        | 1.89%   |
| AMD Athlon II X3        | 1        | 1.89%   |
| AMD A8                  | 1        | 1.89%   |
| AMD A10                 | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 27       | 50%     |
| 2      | 14       | 25.93%  |
| 6      | 5        | 9.26%   |
| 8      | 3        | 5.56%   |
| 3      | 2        | 3.7%    |
| 32     | 1        | 1.85%   |
| 16     | 1        | 1.85%   |
| 12     | 1        | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 98.11%  |
| 2      | 1        | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 60.38%  |
| 1      | 21       | 39.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 51       | 92.73%  |
| Unknown        | 3        | 5.45%   |
| 32-bit         | 1        | 1.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 20.34%  |
| 0x306c3    | 7        | 11.86%  |
| 0x206a7    | 5        | 8.47%   |
| 0x1067a    | 3        | 5.08%   |
| 0x06000852 | 3        | 5.08%   |
| 0x306a9    | 2        | 3.39%   |
| 0x08701021 | 2        | 3.39%   |
| 0x0800820d | 2        | 3.39%   |
| 0x010000c8 | 2        | 3.39%   |
| 0xa0671    | 1        | 1.69%   |
| 0xa0653    | 1        | 1.69%   |
| 0x906eb    | 1        | 1.69%   |
| 0x906ea    | 1        | 1.69%   |
| 0x906e9    | 1        | 1.69%   |
| 0x6fb      | 1        | 1.69%   |
| 0x6f6      | 1        | 1.69%   |
| 0x686      | 1        | 1.69%   |
| 0x506c9    | 1        | 1.69%   |
| 0x306f2    | 1        | 1.69%   |
| 0x206d7    | 1        | 1.69%   |
| 0x08701013 | 1        | 1.69%   |
| 0x08108109 | 1        | 1.69%   |
| 0x08108102 | 1        | 1.69%   |
| 0x08101016 | 1        | 1.69%   |
| 0x0800820b | 1        | 1.69%   |
| 0x08001137 | 1        | 1.69%   |
| 0x06003104 | 1        | 1.69%   |
| 0x06001119 | 1        | 1.69%   |
| 0x0600084f | 1        | 1.69%   |
| 0x010000bf | 1        | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 10       | 18.52%  |
| SandyBridge | 6        | 11.11%  |
| KabyLake    | 6        | 11.11%  |
| Piledriver  | 5        | 9.26%   |
| Zen+        | 4        | 7.41%   |
| Zen 2       | 3        | 5.56%   |
| Penryn      | 3        | 5.56%   |
| K10         | 3        | 5.56%   |
| Zen         | 2        | 3.7%    |
| Skylake     | 2        | 3.7%    |
| IvyBridge   | 2        | 3.7%    |
| Core        | 2        | 3.7%    |
| Steamroller | 1        | 1.85%   |
| P6          | 1        | 1.85%   |
| Icelake     | 1        | 1.85%   |
| Goldmont    | 1        | 1.85%   |
| CometLake   | 1        | 1.85%   |
| Bulldozer   | 1        | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 32       | 54.24%  |
| Intel  | 15       | 25.42%  |
| AMD    | 12       | 20.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 6.78%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 6.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 5.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.08%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3        | 5.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.39%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 3.39%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 3.39%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.39%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 3.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.69%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1        | 1.69%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 1.69%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.69%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.69%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.69%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.69%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.69%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.69%   |
| Nvidia G73 [GeForce 7300 GT]                                                | 1        | 1.69%   |
| Intel UHD Graphics 620                                                      | 1        | 1.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.69%   |
| Intel HD Graphics 630                                                       | 1        | 1.69%   |
| Intel HD Graphics 500                                                       | 1        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.69%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.69%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 1.69%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.69%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 28       | 51.85%  |
| 1 x Intel      | 11       | 20.37%  |
| 1 x AMD        | 11       | 20.37%  |
| Intel + Nvidia | 3        | 5.56%   |
| AMD + Nvidia   | 1        | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 52.73%  |
| Proprietary | 13       | 23.64%  |
| Unknown     | 13       | 23.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 14       | 25.93%  |
| 0.51-1.0   | 12       | 22.22%  |
| Unknown    | 12       | 22.22%  |
| 3.01-4.0   | 4        | 7.41%   |
| 0.01-0.5   | 4        | 7.41%   |
| 5.01-6.0   | 3        | 5.56%   |
| 7.01-8.0   | 2        | 3.7%    |
| 2.01-3.0   | 2        | 3.7%    |
| 8.01-16.0  | 1        | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Ancor Communications | 7        | 11.11%  |
| Dell                 | 6        | 9.52%   |
| BenQ                 | 5        | 7.94%   |
| AOC                  | 5        | 7.94%   |
| SNC                  | 4        | 6.35%   |
| Samsung Electronics  | 4        | 6.35%   |
| Goldstar             | 4        | 6.35%   |
| Acer                 | 4        | 6.35%   |
| ViewSonic            | 3        | 4.76%   |
| Sony                 | 3        | 4.76%   |
| Philips              | 3        | 4.76%   |
| LG Electronics       | 3        | 4.76%   |
| Hewlett-Packard      | 2        | 3.17%   |
| Unknown              | 1        | 1.59%   |
| RTK                  | 1        | 1.59%   |
| QBell                | 1        | 1.59%   |
| PKB                  | 1        | 1.59%   |
| ONKYO                | 1        | 1.59%   |
| Medion               | 1        | 1.59%   |
| HannStar             | 1        | 1.59%   |
| Eizo                 | 1        | 1.59%   |
| Compal               | 1        | 1.59%   |
| ASUSTek Computer     | 1        | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 4        | 5.56%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2        | 2.78%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 2        | 2.78%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2        | 2.78%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch         | 1        | 1.39%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1        | 1.39%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1        | 1.39%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 1.39%   |
| Sony TV SNYF301 1920x1080                                             | 1        | 1.39%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 1.39%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1        | 1.39%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 1        | 1.39%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1        | 1.39%   |
| Samsung Electronics LCD Monitor S24D330                               | 1        | 1.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.39%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1        | 1.39%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1        | 1.39%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1        | 1.39%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 1        | 1.39%   |
| Philips LCD Monitor PHLC0BF 1600x900 430x240mm 19.4-inch              | 1        | 1.39%   |
| Philips LCD Monitor FTV                                               | 1        | 1.39%   |
| ONKYO LCD Monitor TX-SR608 5760x2160                                  | 1        | 1.39%   |
| ONKYO LCD Monitor TX-SR608                                            | 1        | 1.39%   |
| ONKYO LCD Monitor AV Receiver 5760x2160                               | 1        | 1.39%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1        | 1.39%   |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                        | 1        | 1.39%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 1.39%   |
| LG Electronics LCD Monitor 23MB35 1920x1080                           | 1        | 1.39%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch         | 1        | 1.39%   |
| Hewlett-Packard w22 HWP26AE 1680x1050 470x300mm 22.0-inch             | 1        | 1.39%   |
| Hewlett-Packard LP1965 HWP2693 1280x1024 380x300mm 19.1-inch          | 1        | 1.39%   |
| HannStar HF225 HSP18BB 1920x1080 477x268mm 21.5-inch                  | 1        | 1.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 1.39%   |
| Goldstar 22BK55 GSM5A30 1680x1050 480x300mm 22.3-inch                 | 1        | 1.39%   |
| Eizo EV2436W ENC2384 1920x1200 519x324mm 24.1-inch                    | 1        | 1.39%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                     | 1        | 1.39%   |
| Dell P2715Q DEL40BF 3840x2160 597x336mm 27.0-inch                     | 1        | 1.39%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                     | 1        | 1.39%   |
| Dell LCD Monitor U2715H 2560x1440                                     | 1        | 1.39%   |
| Dell LCD Monitor ST2420L                                              | 1        | 1.39%   |
| Dell LCD Monitor SP2309W                                              | 1        | 1.39%   |
| Dell LCD Monitor P190S 2560x1024                                      | 1        | 1.39%   |
| Compal TERRA 2450W WOR2450 1920x1080 341x256mm 16.8-inch              | 1        | 1.39%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 1        | 1.39%   |
| BenQ LCD Monitor LCD 4480x1440                                        | 1        | 1.39%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 1.39%   |
| BenQ G900 BNQ7804 1280x1024 376x301mm 19.0-inch                       | 1        | 1.39%   |
| BenQ FP71G+ BNQ7688 1280x1024 338x270mm 17.0-inch                     | 1        | 1.39%   |
| ASUSTek Computer VG278 AUS27AF 1920x1080 598x336mm 27.0-inch          | 1        | 1.39%   |
| AOC LCD Monitor 2060W 3520x1080                                       | 1        | 1.39%   |
| AOC LCD Monitor 2060W 3200x900                                        | 1        | 1.39%   |
| AOC CT500G AOCE556 1024x768 280x210mm 13.8-inch                       | 1        | 1.39%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 1        | 1.39%   |
| AOC 2240w AOC2240 1920x1080 480x270mm 21.7-inch                       | 1        | 1.39%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                        | 1        | 1.39%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1        | 1.39%   |
| Ancor Communications LCD Monitor ASUS VE278 3840x1080                 | 1        | 1.39%   |
| Ancor Communications ASUS VH222 ACI22AB 1920x1080 477x268mm 21.5-inch | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 40.63%  |
| Unknown            | 7        | 10.94%  |
| 3840x2160 (4K)     | 5        | 7.81%   |
| 1280x1024 (SXGA)   | 5        | 7.81%   |
| 1366x768 (WXGA)    | 4        | 6.25%   |
| 1920x1200 (WUXGA)  | 3        | 4.69%   |
| 3840x1080          | 2        | 3.13%   |
| 1680x1050 (WSXGA+) | 2        | 3.13%   |
| 1600x900 (HD+)     | 2        | 3.13%   |
| 5760x2160          | 1        | 1.56%   |
| 4480x1440          | 1        | 1.56%   |
| 3520x1080          | 1        | 1.56%   |
| 3200x900           | 1        | 1.56%   |
| 2560x1440 (QHD)    | 1        | 1.56%   |
| 2560x1024          | 1        | 1.56%   |
| 1440x900 (WXGA+)   | 1        | 1.56%   |
| 1024x768 (XGA)     | 1        | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 20%     |
| 27      | 9        | 15%     |
| 21      | 8        | 13.33%  |
| 24      | 6        | 10%     |
| 19      | 6        | 10%     |
| 18      | 4        | 6.67%   |
| 46      | 2        | 3.33%   |
| 25      | 2        | 3.33%   |
| 23      | 2        | 3.33%   |
| 22      | 2        | 3.33%   |
| 72      | 1        | 1.67%   |
| 54      | 1        | 1.67%   |
| 42      | 1        | 1.67%   |
| 32      | 1        | 1.67%   |
| 20      | 1        | 1.67%   |
| 17      | 1        | 1.67%   |
| 13      | 1        | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 30.51%  |
| 401-500     | 16       | 27.12%  |
| Unknown     | 12       | 20.34%  |
| 351-400     | 4        | 6.78%   |
| 1001-1500   | 3        | 5.08%   |
| 701-800     | 1        | 1.69%   |
| 601-700     | 1        | 1.69%   |
| 301-350     | 1        | 1.69%   |
| 201-300     | 1        | 1.69%   |
| 1501-2000   | 1        | 1.69%   |
| 901-1000    | 1        | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 55.36%  |
| Unknown | 12       | 21.43%  |
| 16/10   | 7        | 12.5%   |
| 5/4     | 5        | 8.93%   |
| 4/3     | 1        | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 20.69%  |
| Unknown        | 12       | 20.69%  |
| 301-350        | 9        | 15.52%  |
| 151-200        | 9        | 15.52%  |
| 141-150        | 5        | 8.62%   |
| 251-300        | 4        | 6.9%    |
| 501-1000       | 3        | 5.17%   |
| More than 1000 | 2        | 3.45%   |
| 351-500        | 1        | 1.72%   |
| 91-100         | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 51.79%  |
| Unknown | 12       | 21.43%  |
| 101-120 | 8        | 14.29%  |
| 1-50    | 4        | 7.14%   |
| 161-240 | 2        | 3.57%   |
| 121-160 | 1        | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 68.52%  |
| 2     | 17       | 31.48%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 31       | 43.06%  |
| Intel                    | 28       | 38.89%  |
| Qualcomm Atheros         | 3        | 4.17%   |
| Broadcom                 | 3        | 4.17%   |
| Wilocity                 | 1        | 1.39%   |
| Ultimarc                 | 1        | 1.39%   |
| MediaTek                 | 1        | 1.39%   |
| Marvell Technology Group | 1        | 1.39%   |
| Huawei Technologies      | 1        | 1.39%   |
| D-Link System            | 1        | 1.39%   |
| Aquantia                 | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 30.95%  |
| Intel I211 Gigabit Network Connection                             | 5        | 5.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 4.76%   |
| Intel Wireless 3165                                               | 3        | 3.57%   |
| Intel Ethernet Connection I217-V                                  | 3        | 3.57%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2        | 2.38%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 2.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 2.38%   |
| Intel Wireless 7265                                               | 2        | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.38%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 2.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 2.38%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 1.19%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1        | 1.19%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.19%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.19%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.19%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.19%   |
| MediaTek WiFi                                                     | 1        | 1.19%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.19%   |
| Intel Wireless 8260                                               | 1        | 1.19%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.19%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.19%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.19%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.19%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.19%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.19%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.19%   |
| Huawei Mass Storage                                               | 1        | 1.19%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.19%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.19%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.19%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 55%     |
| Realtek Semiconductor | 5        | 25%     |
| Wilocity              | 1        | 5%      |
| Qualcomm Atheros      | 1        | 5%      |
| MediaTek              | 1        | 5%      |
| Broadcom              | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4        | 16.67%  |
| Intel Wireless 3165                                        | 3        | 12.5%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 2        | 8.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 2        | 8.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 2        | 8.33%   |
| Intel Wireless 7265                                        | 2        | 8.33%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 4.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1        | 4.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 4.17%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 1        | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1        | 4.17%   |
| MediaTek WiFi                                              | 1        | 4.17%   |
| Intel Wireless 8260                                        | 1        | 4.17%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 4.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 29       | 51.79%  |
| Intel                    | 20       | 35.71%  |
| Qualcomm Atheros         | 2        | 3.57%   |
| Broadcom                 | 2        | 3.57%   |
| Marvell Technology Group | 1        | 1.79%   |
| D-Link System            | 1        | 1.79%   |
| Aquantia                 | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 44.83%  |
| Intel I211 Gigabit Network Connection                             | 5        | 8.62%   |
| Intel Ethernet Connection I217-V                                  | 3        | 5.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.45%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 3.45%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 3.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.72%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.72%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.72%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.72%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.72%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.72%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 1.72%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 51       | 73.91%  |
| WiFi     | 16       | 23.19%  |
| Modem    | 1        | 1.45%   |
| Unknown  | 1        | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 77.97%  |
| WiFi     | 12       | 20.34%  |
| Unknown  | 1        | 1.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 66.67%  |
| 2     | 13       | 22.81%  |
| 3     | 4        | 7.02%   |
| 4     | 1        | 1.75%   |
| 0     | 1        | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 87.27%  |
| Yes  | 7        | 12.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 45.83%  |
| Cambridge Silicon Radio | 7        | 29.17%  |
| ASUSTek Computer        | 3        | 12.5%   |
| Broadcom                | 2        | 8.33%   |
| Realtek Semiconductor   | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 29.17%  |
| Intel Bluetooth wireless interface                  | 6        | 25%     |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 16.67%  |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| Intel AX200 Bluetooth                               | 1        | 4.17%   |
| Broadcom Bluetooth dongle                           | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.17%   |
| ASUS Bluetooth Device                               | 1        | 4.17%   |
| ASUS BCM20702A0                                     | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 34       | 35.42%  |
| Nvidia                     | 30       | 31.25%  |
| AMD                        | 20       | 20.83%  |
| C-Media Electronics        | 6        | 6.25%   |
| Samsung Electronics        | 1        | 1.04%   |
| Mackie Designs             | 1        | 1.04%   |
| Logitech                   | 1        | 1.04%   |
| Corsair                    | 1        | 1.04%   |
| BEHRINGER International    | 1        | 1.04%   |
| Altec Lansing Technologies | 1        | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 7.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 5.66%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 3.77%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4        | 3.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 3.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 2.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.83%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3        | 2.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.89%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.89%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.89%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.89%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 1.89%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2        | 1.89%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.89%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.89%   |
| Samsung Electronics USB C Earphones                                        | 1        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.94%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.94%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.94%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.94%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.94%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.94%   |
| Mackie Designs ProFX                                                       | 1        | 0.94%   |
| Logitech Headset H340                                                      | 1        | 0.94%   |
| Intel USB PnP Sound Device                                                 | 1        | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 0.94%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 0.94%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 0.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 0.94%   |
| Corsair Corsair ST100 Headset Output                                      | 1        | 0.94%   |
| BEHRINGER International UMC404HD 192k                                      | 1        | 0.94%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 0.94%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 0.94%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 0.94%   |
| Altec Lansing Technologies ADA-305 Speakers                                | 1        | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 29.03%  |
| G.Skill             | 6        | 19.35%  |
| Unknown             | 5        | 16.13%  |
| Team                | 2        | 6.45%   |
| Samsung Electronics | 2        | 6.45%   |
| Corsair             | 2        | 6.45%   |
| Unknown (ABCD)      | 1        | 3.23%   |
| Nanya Technology    | 1        | 3.23%   |
| Micron Technology   | 1        | 3.23%   |
| GOODRAM             | 1        | 3.23%   |
| Crucial             | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s         | 2        | 5.71%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s        | 2        | 5.71%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 2.86%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1        | 2.86%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                         | 1        | 2.86%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 2.86%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 1        | 2.86%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 2.86%   |
| Team RAM Elite-16 4GB DIMM DDR3 1600MT/s                       | 1        | 2.86%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                     | 1        | 2.86%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s           | 1        | 2.86%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 2.86%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4096MB DIMM DDR3 1600MT/s          | 1        | 2.86%   |
| Micron RAM 18JSF51272AZ-1G6M 4GB DIMM DDR3 1600MT/s            | 1        | 2.86%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s              | 1        | 2.86%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 1        | 2.86%   |
| Kingston RAM KHX2133C11D3/8GX 8192MB DIMM DDR3 2133MT/s        | 1        | 2.86%   |
| Kingston RAM KHX1600C9D3/8G 8192MB DIMM DDR3 1600MT/s          | 1        | 2.86%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s            | 1        | 2.86%   |
| Kingston RAM 99U5584-009.A00LF 4096MB DIMM DDR3 1600MT/s       | 1        | 2.86%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s           | 1        | 2.86%   |
| Kingston RAM 9905624-054.A00G 8GB SODIMM DDR4 2400MT/s         | 1        | 2.86%   |
| GOODRAM RAM GY1600D364L10/8G 8192MB DIMM DDR3 1600MT/s         | 1        | 2.86%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s          | 1        | 2.86%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 1        | 2.86%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 1        | 2.86%   |
| G.Skill RAM F4-2133C15-8GNT 8GB DIMM DDR4 2133MT/s             | 1        | 2.86%   |
| Crucial RAM CT51264BA1339.D16F 4096MB DIMM DDR3 1333MT/s       | 1        | 2.86%   |
| Corsair RAM CMZ32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s           | 1        | 2.86%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s        | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 13       | 44.83%  |
| DDR4    | 11       | 37.93%  |
| Unknown | 3        | 10.34%  |
| LPDDR4  | 1        | 3.45%   |
| DDR2    | 1        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 96.55%  |
| SODIMM | 1        | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 53.13%  |
| 4096  | 8        | 25%     |
| 16384 | 4        | 12.5%   |
| 2048  | 3        | 9.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 9        | 29.03%  |
| 2133  | 4        | 12.9%   |
| 1333  | 4        | 12.9%   |
| 3200  | 3        | 9.68%   |
| 3334  | 2        | 6.45%   |
| 2400  | 2        | 6.45%   |
| 3733  | 1        | 3.23%   |
| 3500  | 1        | 3.23%   |
| 2933  | 1        | 3.23%   |
| 2667  | 1        | 3.23%   |
| 1867  | 1        | 3.23%   |
| 800   | 1        | 3.23%   |
| 667   | 1        | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Xerox               | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |
| Canon               | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155   | 1        | 20%     |
| Samsung CLP-300 Series       | 1        | 20%     |
| HP OfficeJet 6950            | 1        | 20%     |
| Canon PIXMA MG3600 Series    | 1        | 20%     |
| Brother QL-570 Label Printer | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson Scanner                    | 1        | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500]  | 1        | 33.33%  |
| Seiko Epson GT-9800F [Perfection 3200] | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Logitech    | 4        | 40%     |
| Microdia    | 3        | 30%     |
| Microsoft   | 2        | 20%     |
| Leap Motion | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia Camera               | 2        | 20%     |
| Microsoft LifeCam VX-800      | 1        | 10%     |
| Microsoft LifeCam HD-3000     | 1        | 10%     |
| Microdia Sonix USB 2.0 Camera | 1        | 10%     |
| Logitech Webcam C210          | 1        | 10%     |
| Logitech Webcam C200          | 1        | 10%     |
| Logitech Webcam C110          | 1        | 10%     |
| Logitech QuickCam Pro 9000    | 1        | 10%     |
| Leap Motion Controller        | 1        | 10%     |

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


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Avtor  | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Avtor SecureToken | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 46       | 83.64%  |
| 1     | 8        | 14.55%  |
| 2     | 1        | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 44.44%  |
| Unassigned class         | 1        | 11.11%  |
| Sound                    | 1        | 11.11%  |
| Multimedia controller    | 1        | 11.11%  |
| Communication controller | 1        | 11.11%  |
| Chipcard                 | 1        | 11.11%  |


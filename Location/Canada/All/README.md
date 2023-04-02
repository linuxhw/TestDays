Linux in Canada - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 8084

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 09KPNV A01                  | Desktop     | [2b25e4872f](https://linux-hardware.org/?probe=2b25e4872f) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [ad3ead1116](https://linux-hardware.org/?probe=ad3ead1116) | Apr 01, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [d6d1ab6c61](https://linux-hardware.org/?probe=d6d1ab6c61) | Apr 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | Desktop     | [d774a892d1](https://linux-hardware.org/?probe=d774a892d1) | Apr 01, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [f05009caac](https://linux-hardware.org/?probe=f05009caac) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [a91aee62d3](https://linux-hardware.org/?probe=a91aee62d3) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | TS10                        | Desktop     | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Dell          | XPS M1330                   | Notebook    | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [925759c41c](https://linux-hardware.org/?probe=925759c41c) | Mar 31, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [d729a0a559](https://linux-hardware.org/?probe=d729a0a559) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [5f163f6a24](https://linux-hardware.org/?probe=5f163f6a24) | Mar 31, 2023 |
| ASUSTek       | UN65U                       | Desktop     | [70d0f8f069](https://linux-hardware.org/?probe=70d0f8f069) | Mar 31, 2023 |
| Dell          | Latitude 7490               | Notebook    | [06928c624b](https://linux-hardware.org/?probe=06928c624b) | Mar 31, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f5e2675cdd](https://linux-hardware.org/?probe=f5e2675cdd) | Mar 30, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [41f23ded68](https://linux-hardware.org/?probe=41f23ded68) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [c6cbeeb984](https://linux-hardware.org/?probe=c6cbeeb984) | Mar 30, 2023 |
| Shuttle       | FH270                       | Desktop     | [83c990d212](https://linux-hardware.org/?probe=83c990d212) | Mar 30, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [1e3ec03234](https://linux-hardware.org/?probe=1e3ec03234) | Mar 30, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [fe068bd78d](https://linux-hardware.org/?probe=fe068bd78d) | Mar 30, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [aaeb2f2269](https://linux-hardware.org/?probe=aaeb2f2269) | Mar 29, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [9a4f4be1ab](https://linux-hardware.org/?probe=9a4f4be1ab) | Mar 29, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [6024b90eea](https://linux-hardware.org/?probe=6024b90eea) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| ECS           | G31T-M                      | Desktop     | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [e27d6594a6](https://linux-hardware.org/?probe=e27d6594a6) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| HP            | 0AACh                       | Desktop     | [e313c99b98](https://linux-hardware.org/?probe=e313c99b98) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [19ffc63f56](https://linux-hardware.org/?probe=19ffc63f56) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | All in one  | [fcd01e22d7](https://linux-hardware.org/?probe=fcd01e22d7) | Mar 28, 2023 |
| Dell          | Studio 1558                 | Notebook    | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [cdb2c38b76](https://linux-hardware.org/?probe=cdb2c38b76) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| HP            | 0AACh                       | Desktop     | [f354a2f03e](https://linux-hardware.org/?probe=f354a2f03e) | Mar 27, 2023 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | Desktop     | [943075edf7](https://linux-hardware.org/?probe=943075edf7) | Mar 27, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6f41d8a22c](https://linux-hardware.org/?probe=6f41d8a22c) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [58ccd5d7e0](https://linux-hardware.org/?probe=58ccd5d7e0) | Mar 27, 2023 |
| Acer          | Aspire M3910                | Desktop     | [8cc87c48d1](https://linux-hardware.org/?probe=8cc87c48d1) | Mar 27, 2023 |
| HP            | 18E4                        | Desktop     | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [8decb2b6c4](https://linux-hardware.org/?probe=8decb2b6c4) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [7dbe4350b5](https://linux-hardware.org/?probe=7dbe4350b5) | Mar 26, 2023 |
| Lenovo        | ThinkPad X220 4290LR3       | Notebook    | [dffa03da18](https://linux-hardware.org/?probe=dffa03da18) | Mar 26, 2023 |
| Lenovo        | ThinkPad T430 4237ZC7       | Notebook    | [845a2ed117](https://linux-hardware.org/?probe=845a2ed117) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [3772f7397b](https://linux-hardware.org/?probe=3772f7397b) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [915cac124b](https://linux-hardware.org/?probe=915cac124b) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b9095b98c4](https://linux-hardware.org/?probe=b9095b98c4) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [811be842de](https://linux-hardware.org/?probe=811be842de) | Mar 25, 2023 |
| Dell          | 0PU052                      | Desktop     | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [aeb58a6898](https://linux-hardware.org/?probe=aeb58a6898) | Mar 24, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [fea1e4cf50](https://linux-hardware.org/?probe=fea1e4cf50) | Mar 24, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [b5cecce6b9](https://linux-hardware.org/?probe=b5cecce6b9) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c65fd15277](https://linux-hardware.org/?probe=c65fd15277) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [c91fa425a5](https://linux-hardware.org/?probe=c91fa425a5) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [0c587f1f7f](https://linux-hardware.org/?probe=0c587f1f7f) | Mar 22, 2023 |
| HP            | 339A                        | Desktop     | [a09a5bd5a9](https://linux-hardware.org/?probe=a09a5bd5a9) | Mar 22, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [ebbb5efcbc](https://linux-hardware.org/?probe=ebbb5efcbc) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Biostar       | TZ77A                       | Desktop     | [9484c73494](https://linux-hardware.org/?probe=9484c73494) | Mar 21, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [87bce00c67](https://linux-hardware.org/?probe=87bce00c67) | Mar 21, 2023 |
| Framework     | Laptop                      | Notebook    | [a7dc7b28c9](https://linux-hardware.org/?probe=a7dc7b28c9) | Mar 21, 2023 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Nvidia        | Tegra                       | Soc         | [68ac87675a](https://linux-hardware.org/?probe=68ac87675a) | Mar 20, 2023 |
| Nvidia        | Tegra                       | Soc         | [e6398a18ac](https://linux-hardware.org/?probe=e6398a18ac) | Mar 20, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [db7d70cd41](https://linux-hardware.org/?probe=db7d70cd41) | Mar 20, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [65db0797b0](https://linux-hardware.org/?probe=65db0797b0) | Mar 19, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fdedfdf220](https://linux-hardware.org/?probe=fdedfdf220) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [22e0286a24](https://linux-hardware.org/?probe=22e0286a24) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [0018c1237d](https://linux-hardware.org/?probe=0018c1237d) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASUSTek       | P5K                         | Desktop     | [5f34498a89](https://linux-hardware.org/?probe=5f34498a89) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| HP            | 18E8                        | Desktop     | [bf7c3c9080](https://linux-hardware.org/?probe=bf7c3c9080) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [a721b1b9d6](https://linux-hardware.org/?probe=a721b1b9d6) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [33fb26b354](https://linux-hardware.org/?probe=33fb26b354) | Mar 17, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [0c7a43b36b](https://linux-hardware.org/?probe=0c7a43b36b) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7df2952615](https://linux-hardware.org/?probe=7df2952615) | Mar 17, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [d21c2315d1](https://linux-hardware.org/?probe=d21c2315d1) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1b43670875](https://linux-hardware.org/?probe=1b43670875) | Mar 16, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [63893daa0f](https://linux-hardware.org/?probe=63893daa0f) | Mar 16, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [39994acde2](https://linux-hardware.org/?probe=39994acde2) | Mar 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [e89d2059c0](https://linux-hardware.org/?probe=e89d2059c0) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ae37b87da6](https://linux-hardware.org/?probe=ae37b87da6) | Mar 16, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [10e835b353](https://linux-hardware.org/?probe=10e835b353) | Mar 16, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d5cd9be69a](https://linux-hardware.org/?probe=d5cd9be69a) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Matsushita... | CF-18KH2ZXBC                | Notebook    | [9aa73891cd](https://linux-hardware.org/?probe=9aa73891cd) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| Dell          | 0W0CHX A01                  | Desktop     | [29197fc6e4](https://linux-hardware.org/?probe=29197fc6e4) | Mar 15, 2023 |
| HP            | 21D0                        | Desktop     | [9b7d2f0a4f](https://linux-hardware.org/?probe=9b7d2f0a4f) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [4707dc8ed6](https://linux-hardware.org/?probe=4707dc8ed6) | Mar 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e6033259b6](https://linux-hardware.org/?probe=e6033259b6) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cd389d99a0](https://linux-hardware.org/?probe=cd389d99a0) | Mar 14, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [3ea59ee8c5](https://linux-hardware.org/?probe=3ea59ee8c5) | Mar 14, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [047e561901](https://linux-hardware.org/?probe=047e561901) | Mar 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [9332803ca3](https://linux-hardware.org/?probe=9332803ca3) | Mar 13, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2b942e22c2](https://linux-hardware.org/?probe=2b942e22c2) | Mar 13, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [e2379c1008](https://linux-hardware.org/?probe=e2379c1008) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | Notebook    | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1f67ba4519](https://linux-hardware.org/?probe=1f67ba4519) | Mar 13, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| Google        | Droid                       | Notebook    | [b2a41c71ac](https://linux-hardware.org/?probe=b2a41c71ac) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [2eb6d39ced](https://linux-hardware.org/?probe=2eb6d39ced) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [01f61fad51](https://linux-hardware.org/?probe=01f61fad51) | Mar 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [d1336c09a0](https://linux-hardware.org/?probe=d1336c09a0) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | Desktop     | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| HP            | 0AACh                       | Desktop     | [83f0c7df93](https://linux-hardware.org/?probe=83f0c7df93) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [e4fe786b7a](https://linux-hardware.org/?probe=e4fe786b7a) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [bf2d3857fd](https://linux-hardware.org/?probe=bf2d3857fd) | Mar 09, 2023 |
| Dell          | Latitude 3180               | Notebook    | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | Desktop     | [1140b33d95](https://linux-hardware.org/?probe=1140b33d95) | Mar 09, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [515a056886](https://linux-hardware.org/?probe=515a056886) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [da38390eca](https://linux-hardware.org/?probe=da38390eca) | Mar 09, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [fba90acf4d](https://linux-hardware.org/?probe=fba90acf4d) | Mar 09, 2023 |
| HP            | 8591                        | Desktop     | [1620787dc3](https://linux-hardware.org/?probe=1620787dc3) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [1162f373d9](https://linux-hardware.org/?probe=1162f373d9) | Mar 08, 2023 |
| Lenovo        | ThinkCentre M91p 4524B61    | Desktop     | [ed46b4c885](https://linux-hardware.org/?probe=ed46b4c885) | Mar 07, 2023 |
| Lenovo        | ThinkCentre M91p 4524B61    | Desktop     | [87a3321cf9](https://linux-hardware.org/?probe=87a3321cf9) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | Notebook    | [faaa24cfbf](https://linux-hardware.org/?probe=faaa24cfbf) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| Dell          | Studio 1537                 | Notebook    | [2cadadec43](https://linux-hardware.org/?probe=2cadadec43) | Mar 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [5e7340faf5](https://linux-hardware.org/?probe=5e7340faf5) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | Notebook    | [fe3f99601c](https://linux-hardware.org/?probe=fe3f99601c) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Datto         | 1000                        | Notebook    | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| ECS           | X58B-A                      | Desktop     | [e074c61884](https://linux-hardware.org/?probe=e074c61884) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5f35f09385](https://linux-hardware.org/?probe=5f35f09385) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| HP            | 18E4                        | Desktop     | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [64d9894f5e](https://linux-hardware.org/?probe=64d9894f5e) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ccca18039f](https://linux-hardware.org/?probe=ccca18039f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [effde33b49](https://linux-hardware.org/?probe=effde33b49) | Mar 05, 2023 |
| HP            | 828A                        | Desktop     | [a6609046b5](https://linux-hardware.org/?probe=a6609046b5) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [886fdbe7c9](https://linux-hardware.org/?probe=886fdbe7c9) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [2fdc151d2f](https://linux-hardware.org/?probe=2fdc151d2f) | Mar 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [b014753659](https://linux-hardware.org/?probe=b014753659) | Mar 05, 2023 |
| HP            | 0AA0h                       | Desktop     | [657f888891](https://linux-hardware.org/?probe=657f888891) | Mar 04, 2023 |
| HP            | Presario CQ61               | Notebook    | [912b79009b](https://linux-hardware.org/?probe=912b79009b) | Mar 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [6181549e93](https://linux-hardware.org/?probe=6181549e93) | Mar 04, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [b9a0465659](https://linux-hardware.org/?probe=b9a0465659) | Mar 04, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [8c0488a140](https://linux-hardware.org/?probe=8c0488a140) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [6258e45123](https://linux-hardware.org/?probe=6258e45123) | Mar 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e106ed41e](https://linux-hardware.org/?probe=0e106ed41e) | Mar 04, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9aebf534a5](https://linux-hardware.org/?probe=9aebf534a5) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | Notebook    | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [01de5e633e](https://linux-hardware.org/?probe=01de5e633e) | Mar 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a8904b4cc0](https://linux-hardware.org/?probe=a8904b4cc0) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [52b43673bb](https://linux-hardware.org/?probe=52b43673bb) | Mar 03, 2023 |
| Acer          | Aspire M3970                | Desktop     | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Win elemen... | M600                        | Desktop     | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [a64d1078d4](https://linux-hardware.org/?probe=a64d1078d4) | Mar 03, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [03db87f6d8](https://linux-hardware.org/?probe=03db87f6d8) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e08a9cdac6](https://linux-hardware.org/?probe=e08a9cdac6) | Mar 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [3cabf6cbe4](https://linux-hardware.org/?probe=3cabf6cbe4) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| Microsoft     | Surface Book                | Tablet      | [cc3ad3e0d2](https://linux-hardware.org/?probe=cc3ad3e0d2) | Mar 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4d68c19c3e](https://linux-hardware.org/?probe=4d68c19c3e) | Mar 02, 2023 |
| HP            | 212B                        | Desktop     | [f771bfe252](https://linux-hardware.org/?probe=f771bfe252) | Mar 02, 2023 |
| HP            | 18E4                        | Desktop     | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Dell          | Precision 5520              | Notebook    | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6525b5d0a4](https://linux-hardware.org/?probe=6525b5d0a4) | Mar 01, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d58385d1e6](https://linux-hardware.org/?probe=d58385d1e6) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [a6c009eb9c](https://linux-hardware.org/?probe=a6c009eb9c) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [903b322b17](https://linux-hardware.org/?probe=903b322b17) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [006fbf48e9](https://linux-hardware.org/?probe=006fbf48e9) | Mar 01, 2023 |
| Acer          | Aspire E1-532P              | Notebook    | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c937edbfcd](https://linux-hardware.org/?probe=c937edbfcd) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [483db5a7bd](https://linux-hardware.org/?probe=483db5a7bd) | Feb 28, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [d8b58a8ea1](https://linux-hardware.org/?probe=d8b58a8ea1) | Feb 28, 2023 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [1ad2cb5102](https://linux-hardware.org/?probe=1ad2cb5102) | Feb 28, 2023 |
| Alienware     | x15 R2                      | Notebook    | [f0335542ce](https://linux-hardware.org/?probe=f0335542ce) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| Unknown       | HX90                        | Desktop     | [bc8bed9135](https://linux-hardware.org/?probe=bc8bed9135) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [618e3d30fc](https://linux-hardware.org/?probe=618e3d30fc) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [a9a8184201](https://linux-hardware.org/?probe=a9a8184201) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [07f46e8e62](https://linux-hardware.org/?probe=07f46e8e62) | Feb 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [8de57c03d5](https://linux-hardware.org/?probe=8de57c03d5) | Feb 27, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [97b08529eb](https://linux-hardware.org/?probe=97b08529eb) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | Desktop     | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | Notebook    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [c863d76de9](https://linux-hardware.org/?probe=c863d76de9) | Feb 25, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [fbb2478f8c](https://linux-hardware.org/?probe=fbb2478f8c) | Feb 25, 2023 |
| HP            | G60                         | Notebook    | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| Protectli     | VP2420                      | Desktop     | [ea5f851cf3](https://linux-hardware.org/?probe=ea5f851cf3) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [6053547fd3](https://linux-hardware.org/?probe=6053547fd3) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [79bb0eb4c9](https://linux-hardware.org/?probe=79bb0eb4c9) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3575d2e78d](https://linux-hardware.org/?probe=3575d2e78d) | Feb 25, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e162d5848c](https://linux-hardware.org/?probe=e162d5848c) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| Gateway       | SX2185                      | Desktop     | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASUSTek       | P5K                         | Desktop     | [2fb7f1713b](https://linux-hardware.org/?probe=2fb7f1713b) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [e0687d11bb](https://linux-hardware.org/?probe=e0687d11bb) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [49e71eb5b4](https://linux-hardware.org/?probe=49e71eb5b4) | Feb 22, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4a9371ec87](https://linux-hardware.org/?probe=4a9371ec87) | Feb 22, 2023 |
| Acer          | Aspire X3470                | Desktop     | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| AWOW          | NY PC BOX                   | Mini pc     | [3e9e7c877c](https://linux-hardware.org/?probe=3e9e7c877c) | Feb 22, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [7599e919d9](https://linux-hardware.org/?probe=7599e919d9) | Feb 22, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [d003c3ed81](https://linux-hardware.org/?probe=d003c3ed81) | Feb 22, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [7234bd12f6](https://linux-hardware.org/?probe=7234bd12f6) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a28282663a](https://linux-hardware.org/?probe=a28282663a) | Feb 22, 2023 |
| Dell          | 0PM2CW A05                  | Server      | [13c1bd9dcd](https://linux-hardware.org/?probe=13c1bd9dcd) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [524153d219](https://linux-hardware.org/?probe=524153d219) | Feb 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [ade0244936](https://linux-hardware.org/?probe=ade0244936) | Feb 21, 2023 |
| Dell          | Inspiron 5493               | Notebook    | [ad7bee8a6e](https://linux-hardware.org/?probe=ad7bee8a6e) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [04130aaf41](https://linux-hardware.org/?probe=04130aaf41) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [40ae7724b9](https://linux-hardware.org/?probe=40ae7724b9) | Feb 20, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [08d8865fcf](https://linux-hardware.org/?probe=08d8865fcf) | Feb 20, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [924264cbec](https://linux-hardware.org/?probe=924264cbec) | Feb 20, 2023 |
| AZW           | GK mini                     | Desktop     | [6fc9af1346](https://linux-hardware.org/?probe=6fc9af1346) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| Dell          | Precision M4500             | Notebook    | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [7228f7a915](https://linux-hardware.org/?probe=7228f7a915) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [58ca93166c](https://linux-hardware.org/?probe=58ca93166c) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9978dc62b3](https://linux-hardware.org/?probe=9978dc62b3) | Feb 18, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [6b7a3b68f3](https://linux-hardware.org/?probe=6b7a3b68f3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [041cf0d3d8](https://linux-hardware.org/?probe=041cf0d3d8) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [20dc6d6c5c](https://linux-hardware.org/?probe=20dc6d6c5c) | Feb 18, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [af3167a0d4](https://linux-hardware.org/?probe=af3167a0d4) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [9ab628bcf2](https://linux-hardware.org/?probe=9ab628bcf2) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [aaa83a4af0](https://linux-hardware.org/?probe=aaa83a4af0) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [18b6274238](https://linux-hardware.org/?probe=18b6274238) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [33d9c73cb9](https://linux-hardware.org/?probe=33d9c73cb9) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| Google        | Coral                       | Notebook    | [7a9869ff50](https://linux-hardware.org/?probe=7a9869ff50) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| ASRock        | B360M Xtreme                | Desktop     | [0804d226b0](https://linux-hardware.org/?probe=0804d226b0) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| HP            | 1825                        | Desktop     | [858ebd3baf](https://linux-hardware.org/?probe=858ebd3baf) | Feb 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [395a5da0fb](https://linux-hardware.org/?probe=395a5da0fb) | Feb 17, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [92901492fc](https://linux-hardware.org/?probe=92901492fc) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361eb28148](https://linux-hardware.org/?probe=361eb28148) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0e694f49fe](https://linux-hardware.org/?probe=0e694f49fe) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [af47a30d6a](https://linux-hardware.org/?probe=af47a30d6a) | Feb 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [987c9b1854](https://linux-hardware.org/?probe=987c9b1854) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| IBM           | 811328U                     | Desktop     | [dc9536a0f2](https://linux-hardware.org/?probe=dc9536a0f2) | Feb 14, 2023 |
| IBM           | 811328U                     | Desktop     | [6ad9b1f22a](https://linux-hardware.org/?probe=6ad9b1f22a) | Feb 14, 2023 |
| Pegatron      | Narra6                      | Desktop     | [13f0acba4c](https://linux-hardware.org/?probe=13f0acba4c) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4262fa293e](https://linux-hardware.org/?probe=4262fa293e) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [43d2279955](https://linux-hardware.org/?probe=43d2279955) | Feb 14, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [500a5cf614](https://linux-hardware.org/?probe=500a5cf614) | Feb 14, 2023 |
| HP            | 83EE                        | Desktop     | [f83f333b3c](https://linux-hardware.org/?probe=f83f333b3c) | Feb 14, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [256f660b72](https://linux-hardware.org/?probe=256f660b72) | Feb 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [60ddb51b98](https://linux-hardware.org/?probe=60ddb51b98) | Feb 13, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [2d99eeaca6](https://linux-hardware.org/?probe=2d99eeaca6) | Feb 13, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [c435502e6e](https://linux-hardware.org/?probe=c435502e6e) | Feb 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1VL0... | Notebook    | [d4b5ca228c](https://linux-hardware.org/?probe=d4b5ca228c) | Feb 13, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [bea8c0162f](https://linux-hardware.org/?probe=bea8c0162f) | Feb 12, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [3a0ce0730a](https://linux-hardware.org/?probe=3a0ce0730a) | Feb 12, 2023 |
| Lenovo        | 4030                        | Desktop     | [a0052fd936](https://linux-hardware.org/?probe=a0052fd936) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [866ad6408c](https://linux-hardware.org/?probe=866ad6408c) | Feb 12, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [d517f63625](https://linux-hardware.org/?probe=d517f63625) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [10084e1b16](https://linux-hardware.org/?probe=10084e1b16) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3982ec4e74](https://linux-hardware.org/?probe=3982ec4e74) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a034121d24](https://linux-hardware.org/?probe=a034121d24) | Feb 12, 2023 |
| Pegatron      | Narra6                      | Desktop     | [77bed4b6f3](https://linux-hardware.org/?probe=77bed4b6f3) | Feb 12, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7092ef977d](https://linux-hardware.org/?probe=7092ef977d) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | Presario V6000 (RN927UA#... | Notebook    | [0524b3b524](https://linux-hardware.org/?probe=0524b3b524) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [266a3eff3f](https://linux-hardware.org/?probe=266a3eff3f) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [18b84d9ea2](https://linux-hardware.org/?probe=18b84d9ea2) | Feb 10, 2023 |
| Google        | Droid                       | Notebook    | [33dbb43623](https://linux-hardware.org/?probe=33dbb43623) | Feb 10, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [663cbf83ff](https://linux-hardware.org/?probe=663cbf83ff) | Feb 10, 2023 |
| HP            | Notebook                    | Notebook    | [17664bf689](https://linux-hardware.org/?probe=17664bf689) | Feb 10, 2023 |
| Supermicro    | C7Z370-CG-IW                | Server      | [5145e7d26e](https://linux-hardware.org/?probe=5145e7d26e) | Feb 10, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [0a74293474](https://linux-hardware.org/?probe=0a74293474) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ed180eeb68](https://linux-hardware.org/?probe=ed180eeb68) | Feb 09, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fff827c027](https://linux-hardware.org/?probe=fff827c027) | Feb 09, 2023 |
| Acer          | Aspire M3970                | Desktop     | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [d236f5fa51](https://linux-hardware.org/?probe=d236f5fa51) | Feb 09, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aaa509fed7](https://linux-hardware.org/?probe=aaa509fed7) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [148b3b0adc](https://linux-hardware.org/?probe=148b3b0adc) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [7b17cbd936](https://linux-hardware.org/?probe=7b17cbd936) | Feb 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| ASUSTek       | B150 PRO GAMING D3          | Desktop     | [8178f6bf56](https://linux-hardware.org/?probe=8178f6bf56) | Feb 08, 2023 |
| Lenovo        | Unknown                     | Notebook    | [67c2761551](https://linux-hardware.org/?probe=67c2761551) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ebe5940bd7](https://linux-hardware.org/?probe=ebe5940bd7) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | Notebook    | [bd02e4c770](https://linux-hardware.org/?probe=bd02e4c770) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | Notebook    | [43a7194d4b](https://linux-hardware.org/?probe=43a7194d4b) | Feb 07, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [b7fdb6cd73](https://linux-hardware.org/?probe=b7fdb6cd73) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [70f715ffb4](https://linux-hardware.org/?probe=70f715ffb4) | Feb 06, 2023 |
| Acer          | Okinawa                     | Notebook    | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7ca9a94c5](https://linux-hardware.org/?probe=f7ca9a94c5) | Feb 06, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c73a4ad56a](https://linux-hardware.org/?probe=c73a4ad56a) | Feb 06, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [a0b1f2a7b4](https://linux-hardware.org/?probe=a0b1f2a7b4) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [b452c164d0](https://linux-hardware.org/?probe=b452c164d0) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c35fa9b7f5](https://linux-hardware.org/?probe=c35fa9b7f5) | Feb 05, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [f3f4d9fc40](https://linux-hardware.org/?probe=f3f4d9fc40) | Feb 04, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [486f19af99](https://linux-hardware.org/?probe=486f19af99) | Feb 04, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| MSI           | 870-G45                     | Desktop     | [92b840c75e](https://linux-hardware.org/?probe=92b840c75e) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [d78de63927](https://linux-hardware.org/?probe=d78de63927) | Feb 04, 2023 |
| HP            | 0AACh                       | Desktop     | [86d994993f](https://linux-hardware.org/?probe=86d994993f) | Feb 03, 2023 |
| AZW           | SER                         | Mini pc     | [ce867dfcef](https://linux-hardware.org/?probe=ce867dfcef) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [afadbdee59](https://linux-hardware.org/?probe=afadbdee59) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [93630ab2ea](https://linux-hardware.org/?probe=93630ab2ea) | Feb 03, 2023 |
| Xunlong       | Orange Pi Zero              | Soc         | [3af57a322f](https://linux-hardware.org/?probe=3af57a322f) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [c2bdc49f09](https://linux-hardware.org/?probe=c2bdc49f09) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| Dell          | Latitude 3400               | Notebook    | [c954aad23a](https://linux-hardware.org/?probe=c954aad23a) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef1817a829](https://linux-hardware.org/?probe=ef1817a829) | Feb 02, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [d2696b9042](https://linux-hardware.org/?probe=d2696b9042) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ab92a33bdf](https://linux-hardware.org/?probe=ab92a33bdf) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| HP            | 0AACh                       | Desktop     | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [5dcda0d3e5](https://linux-hardware.org/?probe=5dcda0d3e5) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [1b880dbac2](https://linux-hardware.org/?probe=1b880dbac2) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| Dell          | 0PU052                      | Desktop     | [d2f241353d](https://linux-hardware.org/?probe=d2f241353d) | Feb 01, 2023 |
| Intel         | DG965OT AAD75595-200        | Desktop     | [8ab85c58be](https://linux-hardware.org/?probe=8ab85c58be) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [b5bd231bf3](https://linux-hardware.org/?probe=b5bd231bf3) | Jan 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [21b6d00ff2](https://linux-hardware.org/?probe=21b6d00ff2) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d59770af38](https://linux-hardware.org/?probe=d59770af38) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3a5ae3d1e8](https://linux-hardware.org/?probe=3a5ae3d1e8) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [ff0aa8c4ed](https://linux-hardware.org/?probe=ff0aa8c4ed) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS0BR00     | Notebook    | [6c05048c9d](https://linux-hardware.org/?probe=6c05048c9d) | Jan 31, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| MSI           | 870-G45                     | Desktop     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [6296345ebb](https://linux-hardware.org/?probe=6296345ebb) | Jan 31, 2023 |
| HP            | 339A                        | Desktop     | [e3078cd4d7](https://linux-hardware.org/?probe=e3078cd4d7) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0eac708be5](https://linux-hardware.org/?probe=0eac708be5) | Jan 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [1196b501d5](https://linux-hardware.org/?probe=1196b501d5) | Jan 31, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [9edd1a1969](https://linux-hardware.org/?probe=9edd1a1969) | Jan 30, 2023 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [3e004045f7](https://linux-hardware.org/?probe=3e004045f7) | Jan 30, 2023 |
| HP            | Notebook                    | Notebook    | [fc93f8e357](https://linux-hardware.org/?probe=fc93f8e357) | Jan 30, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [cbfcb68cc6](https://linux-hardware.org/?probe=cbfcb68cc6) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f0000c6ae7](https://linux-hardware.org/?probe=f0000c6ae7) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [3fcf581653](https://linux-hardware.org/?probe=3fcf581653) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | Notebook    | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [77c9cc065f](https://linux-hardware.org/?probe=77c9cc065f) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [1ddc17833b](https://linux-hardware.org/?probe=1ddc17833b) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | B150M-C                     | Desktop     | [6eb1a5b38e](https://linux-hardware.org/?probe=6eb1a5b38e) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [9f2e4066f6](https://linux-hardware.org/?probe=9f2e4066f6) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [f2bf9c3c82](https://linux-hardware.org/?probe=f2bf9c3c82) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [2d2e42ae23](https://linux-hardware.org/?probe=2d2e42ae23) | Jan 28, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [3e7c902731](https://linux-hardware.org/?probe=3e7c902731) | Jan 28, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [8eec8468fb](https://linux-hardware.org/?probe=8eec8468fb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [991bb71df8](https://linux-hardware.org/?probe=991bb71df8) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [d86e915f12](https://linux-hardware.org/?probe=d86e915f12) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [ec0e3da69d](https://linux-hardware.org/?probe=ec0e3da69d) | Jan 27, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [06c6af6032](https://linux-hardware.org/?probe=06c6af6032) | Jan 27, 2023 |
| ASUSTek       | P5K                         | Desktop     | [6d496e6965](https://linux-hardware.org/?probe=6d496e6965) | Jan 27, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c7e2bde422](https://linux-hardware.org/?probe=c7e2bde422) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [38e4843e09](https://linux-hardware.org/?probe=38e4843e09) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [55477da159](https://linux-hardware.org/?probe=55477da159) | Jan 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [2e014cf1ba](https://linux-hardware.org/?probe=2e014cf1ba) | Jan 27, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [021d999708](https://linux-hardware.org/?probe=021d999708) | Jan 27, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [f83ff94df6](https://linux-hardware.org/?probe=f83ff94df6) | Jan 27, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6766a92ee5](https://linux-hardware.org/?probe=6766a92ee5) | Jan 27, 2023 |
| HP            | Compaq 8200 Elite SFF PC    | Desktop     | [73f629ca61](https://linux-hardware.org/?probe=73f629ca61) | Jan 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [9837928212](https://linux-hardware.org/?probe=9837928212) | Jan 26, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [931a186515](https://linux-hardware.org/?probe=931a186515) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [08204bf161](https://linux-hardware.org/?probe=08204bf161) | Jan 26, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [45ea832a59](https://linux-hardware.org/?probe=45ea832a59) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Samsung       | 930QED                      | Convertible | [1a699655f8](https://linux-hardware.org/?probe=1a699655f8) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [ba217c947c](https://linux-hardware.org/?probe=ba217c947c) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [ffd9523db2](https://linux-hardware.org/?probe=ffd9523db2) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [755bed02ff](https://linux-hardware.org/?probe=755bed02ff) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [6ccfafe0d6](https://linux-hardware.org/?probe=6ccfafe0d6) | Jan 24, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [4bdccd0680](https://linux-hardware.org/?probe=4bdccd0680) | Jan 24, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a4e4317d4d](https://linux-hardware.org/?probe=a4e4317d4d) | Jan 24, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [0300fb4b9a](https://linux-hardware.org/?probe=0300fb4b9a) | Jan 24, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [ea0a73ca90](https://linux-hardware.org/?probe=ea0a73ca90) | Jan 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [610ffedb4c](https://linux-hardware.org/?probe=610ffedb4c) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | Desktop     | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [8bbff4abbd](https://linux-hardware.org/?probe=8bbff4abbd) | Jan 24, 2023 |
| HP            | 339A                        | Desktop     | [a2784a6575](https://linux-hardware.org/?probe=a2784a6575) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [f981af502a](https://linux-hardware.org/?probe=f981af502a) | Jan 24, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Acer          | AO722                       | Notebook    | [85f48171a2](https://linux-hardware.org/?probe=85f48171a2) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [77d4494f3b](https://linux-hardware.org/?probe=77d4494f3b) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [f3d76bcb70](https://linux-hardware.org/?probe=f3d76bcb70) | Jan 23, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [ff122405db](https://linux-hardware.org/?probe=ff122405db) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [bb77ccdda7](https://linux-hardware.org/?probe=bb77ccdda7) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M90z 5205W5Q    | All in one  | [ed812a8a26](https://linux-hardware.org/?probe=ed812a8a26) | Jan 22, 2023 |
| Acer          | Aspire C24-960              | All in one  | [ff5e69ca71](https://linux-hardware.org/?probe=ff5e69ca71) | Jan 22, 2023 |
| MSI           | MS-AF82                     | All in one  | [7340fe42ba](https://linux-hardware.org/?probe=7340fe42ba) | Jan 22, 2023 |
| ASUSTek       | P5K                         | Desktop     | [dc5b823cb5](https://linux-hardware.org/?probe=dc5b823cb5) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [2189958490](https://linux-hardware.org/?probe=2189958490) | Jan 22, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Notebook    | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [6afc30df3b](https://linux-hardware.org/?probe=6afc30df3b) | Jan 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8e037468e4](https://linux-hardware.org/?probe=8e037468e4) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6ae7274931](https://linux-hardware.org/?probe=6ae7274931) | Jan 22, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [217c63b8f6](https://linux-hardware.org/?probe=217c63b8f6) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [330a3844cb](https://linux-hardware.org/?probe=330a3844cb) | Jan 21, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [32faa4aac5](https://linux-hardware.org/?probe=32faa4aac5) | Jan 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3eb2d3a903](https://linux-hardware.org/?probe=3eb2d3a903) | Jan 21, 2023 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | Notebook    | [e0b197c0c4](https://linux-hardware.org/?probe=e0b197c0c4) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| HP            | Laptop 15-dy3xxx            | Notebook    | [1053d34e69](https://linux-hardware.org/?probe=1053d34e69) | Jan 20, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [cd42f89819](https://linux-hardware.org/?probe=cd42f89819) | Jan 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [e29a7a31ae](https://linux-hardware.org/?probe=e29a7a31ae) | Jan 20, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [c79dd9971a](https://linux-hardware.org/?probe=c79dd9971a) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| Dell          | Studio XPS 1647             | Notebook    | [4086a6120a](https://linux-hardware.org/?probe=4086a6120a) | Jan 20, 2023 |
| Lenovo        | 3767 WIN SDK0T76461 3422... | All in one  | [f9f38488a8](https://linux-hardware.org/?probe=f9f38488a8) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| Toshiba       | Satellite L650D             | Notebook    | [86d99d74cd](https://linux-hardware.org/?probe=86d99d74cd) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8af55733d7](https://linux-hardware.org/?probe=8af55733d7) | Jan 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9a99559833](https://linux-hardware.org/?probe=9a99559833) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [3ab44ae2f5](https://linux-hardware.org/?probe=3ab44ae2f5) | Jan 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b45cef8a55](https://linux-hardware.org/?probe=b45cef8a55) | Jan 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d173b719da](https://linux-hardware.org/?probe=d173b719da) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| MSI           | MS-AF82                     | All in one  | [82cc6bd7b4](https://linux-hardware.org/?probe=82cc6bd7b4) | Jan 17, 2023 |
| MSI           | MS-AF82                     | All in one  | [57e12122db](https://linux-hardware.org/?probe=57e12122db) | Jan 17, 2023 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c371212092](https://linux-hardware.org/?probe=c371212092) | Jan 17, 2023 |
| MSI           | MS-AF82                     | All in one  | [6fb499c15a](https://linux-hardware.org/?probe=6fb499c15a) | Jan 17, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [2d46e86664](https://linux-hardware.org/?probe=2d46e86664) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [a602bcd50a](https://linux-hardware.org/?probe=a602bcd50a) | Jan 17, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c5387e7fd9](https://linux-hardware.org/?probe=c5387e7fd9) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | Notebook    | [1bd88ff8c7](https://linux-hardware.org/?probe=1bd88ff8c7) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b355faaee](https://linux-hardware.org/?probe=2b355faaee) | Jan 16, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [da7f445f06](https://linux-hardware.org/?probe=da7f445f06) | Jan 16, 2023 |
| Foxconn       | ALOE                        | Desktop     | [0b3564ef16](https://linux-hardware.org/?probe=0b3564ef16) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [bbddcc3653](https://linux-hardware.org/?probe=bbddcc3653) | Jan 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9b1e965bca](https://linux-hardware.org/?probe=9b1e965bca) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | Notebook    | [e04d230b62](https://linux-hardware.org/?probe=e04d230b62) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [422f31719c](https://linux-hardware.org/?probe=422f31719c) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c16748dc74](https://linux-hardware.org/?probe=c16748dc74) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f7422d49df](https://linux-hardware.org/?probe=f7422d49df) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [b893aecea2](https://linux-hardware.org/?probe=b893aecea2) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| Dell          | 0WK833                      | Desktop     | [100d6694e5](https://linux-hardware.org/?probe=100d6694e5) | Jan 15, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [227b58bf8f](https://linux-hardware.org/?probe=227b58bf8f) | Jan 15, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [23748f30aa](https://linux-hardware.org/?probe=23748f30aa) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | P5B-VM                      | Desktop     | [53b563ef2f](https://linux-hardware.org/?probe=53b563ef2f) | Jan 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9bc8bf29b](https://linux-hardware.org/?probe=c9bc8bf29b) | Jan 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [9527eef253](https://linux-hardware.org/?probe=9527eef253) | Jan 15, 2023 |
| Dell          | 0UW457 A04                  | Desktop     | [0c637493cc](https://linux-hardware.org/?probe=0c637493cc) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6194c3a2fe](https://linux-hardware.org/?probe=6194c3a2fe) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [a24b95f891](https://linux-hardware.org/?probe=a24b95f891) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4776fc6062](https://linux-hardware.org/?probe=4776fc6062) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [f9fe88837c](https://linux-hardware.org/?probe=f9fe88837c) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [59607f5e75](https://linux-hardware.org/?probe=59607f5e75) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a4b4747500](https://linux-hardware.org/?probe=a4b4747500) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [4340505060](https://linux-hardware.org/?probe=4340505060) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [03f7a5fdea](https://linux-hardware.org/?probe=03f7a5fdea) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [9e4c15fff7](https://linux-hardware.org/?probe=9e4c15fff7) | Jan 14, 2023 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [06aff9f10a](https://linux-hardware.org/?probe=06aff9f10a) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [77d37c245a](https://linux-hardware.org/?probe=77d37c245a) | Jan 14, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [9cf1da2d69](https://linux-hardware.org/?probe=9cf1da2d69) | Jan 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e7c4823aee](https://linux-hardware.org/?probe=e7c4823aee) | Jan 14, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [4ab9753ab5](https://linux-hardware.org/?probe=4ab9753ab5) | Jan 14, 2023 |
| HP            | Notebook                    | Notebook    | [e242059a08](https://linux-hardware.org/?probe=e242059a08) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| Lenovo        | ThinkCentre XXXX 7360EHF    | Desktop     | [fdfe8c5881](https://linux-hardware.org/?probe=fdfe8c5881) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [9730761eb1](https://linux-hardware.org/?probe=9730761eb1) | Jan 13, 2023 |
| Acer          | Aspire X1800                | Desktop     | [16f6ad749f](https://linux-hardware.org/?probe=16f6ad749f) | Jan 13, 2023 |
| Dell          | 0UW457 A04                  | Desktop     | [4c5689de9c](https://linux-hardware.org/?probe=4c5689de9c) | Jan 13, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [eeec2db688](https://linux-hardware.org/?probe=eeec2db688) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [fa6e296766](https://linux-hardware.org/?probe=fa6e296766) | Jan 13, 2023 |
| Acer          | Aspire X1800                | Desktop     | [929228726d](https://linux-hardware.org/?probe=929228726d) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [da5cb78b32](https://linux-hardware.org/?probe=da5cb78b32) | Jan 12, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [dad2489f95](https://linux-hardware.org/?probe=dad2489f95) | Jan 12, 2023 |
| ASUSTek       | P5K                         | Desktop     | [ec9ba21c49](https://linux-hardware.org/?probe=ec9ba21c49) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [354d25ae30](https://linux-hardware.org/?probe=354d25ae30) | Jan 12, 2023 |
| Acer          | Aspire M3450                | Desktop     | [0ed84a21b2](https://linux-hardware.org/?probe=0ed84a21b2) | Jan 12, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [f39178befb](https://linux-hardware.org/?probe=f39178befb) | Jan 12, 2023 |
| Dell          | 0DXJD9 A01                  | Desktop     | [78549912fa](https://linux-hardware.org/?probe=78549912fa) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| ECS           | A55F-M2                     | Desktop     | [b891de98a1](https://linux-hardware.org/?probe=b891de98a1) | Jan 11, 2023 |
| Matsushita... | CF-18KH2ZXBC                | Notebook    | [41e8ef7b23](https://linux-hardware.org/?probe=41e8ef7b23) | Jan 11, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [f78e703512](https://linux-hardware.org/?probe=f78e703512) | Jan 11, 2023 |
| Dell          | 0PM2CW A05                  | Server      | [d76d38ba9b](https://linux-hardware.org/?probe=d76d38ba9b) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [b4b3e05975](https://linux-hardware.org/?probe=b4b3e05975) | Jan 11, 2023 |
| HP            | 18E4                        | Desktop     | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [6bfa934fb6](https://linux-hardware.org/?probe=6bfa934fb6) | Jan 11, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [1705a3f042](https://linux-hardware.org/?probe=1705a3f042) | Jan 11, 2023 |
| Dell          | G5 5590                     | Notebook    | [846a462365](https://linux-hardware.org/?probe=846a462365) | Jan 10, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [c6e3650e2b](https://linux-hardware.org/?probe=c6e3650e2b) | Jan 10, 2023 |
| HP            | 18E4                        | Desktop     | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 8433 11                     | Desktop     | [2036bb2c1a](https://linux-hardware.org/?probe=2036bb2c1a) | Jan 10, 2023 |
| ASUSTek       | P5K                         | Desktop     | [64c746ef0b](https://linux-hardware.org/?probe=64c746ef0b) | Jan 10, 2023 |
| System76      | Darter Pro                  | Notebook    | [ffaaf5c90e](https://linux-hardware.org/?probe=ffaaf5c90e) | Jan 10, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| Google        | Blooglet                    | Notebook    | [bf644ec6f4](https://linux-hardware.org/?probe=bf644ec6f4) | Jan 10, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [86cfa19622](https://linux-hardware.org/?probe=86cfa19622) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [66ffdd11c5](https://linux-hardware.org/?probe=66ffdd11c5) | Jan 10, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [302f3a5ebe](https://linux-hardware.org/?probe=302f3a5ebe) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [0a2fd6c8e7](https://linux-hardware.org/?probe=0a2fd6c8e7) | Jan 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [2bbe617df6](https://linux-hardware.org/?probe=2bbe617df6) | Jan 09, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [f2895e4b94](https://linux-hardware.org/?probe=f2895e4b94) | Jan 09, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d6115e24c1](https://linux-hardware.org/?probe=d6115e24c1) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [5626a7c211](https://linux-hardware.org/?probe=5626a7c211) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [f884203e84](https://linux-hardware.org/?probe=f884203e84) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [b518c0a817](https://linux-hardware.org/?probe=b518c0a817) | Jan 09, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [272bff51c5](https://linux-hardware.org/?probe=272bff51c5) | Jan 09, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [7aaeb8fbfc](https://linux-hardware.org/?probe=7aaeb8fbfc) | Jan 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [11cb3f9636](https://linux-hardware.org/?probe=11cb3f9636) | Jan 08, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [c8e96fe453](https://linux-hardware.org/?probe=c8e96fe453) | Jan 08, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [b95882e5cf](https://linux-hardware.org/?probe=b95882e5cf) | Jan 08, 2023 |
| HP            | 2B05                        | Desktop     | [a6f3a8c157](https://linux-hardware.org/?probe=a6f3a8c157) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [cfcc0a49c6](https://linux-hardware.org/?probe=cfcc0a49c6) | Jan 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e8e8ca3959](https://linux-hardware.org/?probe=e8e8ca3959) | Jan 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [4c96ccba44](https://linux-hardware.org/?probe=4c96ccba44) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2e22cc1bb2](https://linux-hardware.org/?probe=2e22cc1bb2) | Jan 08, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [2dfeda8d20](https://linux-hardware.org/?probe=2dfeda8d20) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Lenovo        | ThinkPad W520 4284A24       | Notebook    | [263e00840a](https://linux-hardware.org/?probe=263e00840a) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| Dell          | XPS 9320                    | Notebook    | [55be119900](https://linux-hardware.org/?probe=55be119900) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [60b8fb9dc4](https://linux-hardware.org/?probe=60b8fb9dc4) | Jan 07, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [be50406f89](https://linux-hardware.org/?probe=be50406f89) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [83ec1382a3](https://linux-hardware.org/?probe=83ec1382a3) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [354b2538a4](https://linux-hardware.org/?probe=354b2538a4) | Jan 07, 2023 |
| HP            | Pavilion dv4                | Notebook    | [5caee4abe0](https://linux-hardware.org/?probe=5caee4abe0) | Jan 07, 2023 |
| Lenovo        | ThinkCentre M90z 5205W5Q    | All in one  | [3267811ed5](https://linux-hardware.org/?probe=3267811ed5) | Jan 07, 2023 |
| ASUSTek       | Z97-C                       | Desktop     | [2b61136e8d](https://linux-hardware.org/?probe=2b61136e8d) | Jan 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [15eaac1fac](https://linux-hardware.org/?probe=15eaac1fac) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [22894be0e8](https://linux-hardware.org/?probe=22894be0e8) | Jan 06, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [1720ed7ed6](https://linux-hardware.org/?probe=1720ed7ed6) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1608711aa0](https://linux-hardware.org/?probe=1608711aa0) | Jan 06, 2023 |
| ASUSTek       | X301A1                      | Notebook    | [e575482522](https://linux-hardware.org/?probe=e575482522) | Jan 06, 2023 |
| Dell          | G15 5525                    | Notebook    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [4d2721777a](https://linux-hardware.org/?probe=4d2721777a) | Jan 06, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f9f6df3b14](https://linux-hardware.org/?probe=f9f6df3b14) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | Notebook    | [d2ee3f78a9](https://linux-hardware.org/?probe=d2ee3f78a9) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | Notebook    | [9c9801b860](https://linux-hardware.org/?probe=9c9801b860) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [907ceedda1](https://linux-hardware.org/?probe=907ceedda1) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| ASUSTek       | P5WD2-E Premium             | Desktop     | [c97e28eb76](https://linux-hardware.org/?probe=c97e28eb76) | Jan 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [47938bccb6](https://linux-hardware.org/?probe=47938bccb6) | Jan 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0fb5f590d5](https://linux-hardware.org/?probe=0fb5f590d5) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [0ff94735bd](https://linux-hardware.org/?probe=0ff94735bd) | Jan 04, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [872a58377f](https://linux-hardware.org/?probe=872a58377f) | Jan 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [2da57c3386](https://linux-hardware.org/?probe=2da57c3386) | Jan 04, 2023 |
| HP            | 1998                        | Desktop     | [7c067688db](https://linux-hardware.org/?probe=7c067688db) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| HP            | 1998                        | Desktop     | [1eb07196f7](https://linux-hardware.org/?probe=1eb07196f7) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [3d589a827c](https://linux-hardware.org/?probe=3d589a827c) | Jan 04, 2023 |
| Dell          | 0M9KCM A02                  | Desktop     | [dc9d77448b](https://linux-hardware.org/?probe=dc9d77448b) | Jan 04, 2023 |
| Dell          | Latitude D520               | Notebook    | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Datto         | Unknown                     | Notebook    | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [50da80ab44](https://linux-hardware.org/?probe=50da80ab44) | Jan 04, 2023 |
| Lenovo        | MAHOBAY No DPK              | Desktop     | [b829ec9d52](https://linux-hardware.org/?probe=b829ec9d52) | Jan 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [71ebcdc5ff](https://linux-hardware.org/?probe=71ebcdc5ff) | Jan 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| HP            | 0AACh                       | Desktop     | [216ba22b5a](https://linux-hardware.org/?probe=216ba22b5a) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| HP            | 0AACh                       | Desktop     | [0730634b36](https://linux-hardware.org/?probe=0730634b36) | Jan 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f252f31761](https://linux-hardware.org/?probe=f252f31761) | Jan 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [1dedff3ad9](https://linux-hardware.org/?probe=1dedff3ad9) | Jan 01, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [13c0ee7f2d](https://linux-hardware.org/?probe=13c0ee7f2d) | Jan 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| HP            | 18E4                        | Desktop     | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [d9b5e3cfc3](https://linux-hardware.org/?probe=d9b5e3cfc3) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | Notebook    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| HP            | 18E4                        | Desktop     | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [92ce347d5f](https://linux-hardware.org/?probe=92ce347d5f) | Dec 31, 2022 |
| ASUSTek       | TP501UA                     | Notebook    | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [37d47ff0dc](https://linux-hardware.org/?probe=37d47ff0dc) | Dec 30, 2022 |
| ASUSTek       | P8B-M Series                | Server      | [b559ad98cf](https://linux-hardware.org/?probe=b559ad98cf) | Dec 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [4f3bc75747](https://linux-hardware.org/?probe=4f3bc75747) | Dec 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [e0f8b8c7b9](https://linux-hardware.org/?probe=e0f8b8c7b9) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a323cc954e](https://linux-hardware.org/?probe=a323cc954e) | Dec 30, 2022 |
| Acer          | Aspire A115-32              | Notebook    | [7c8ec90c8a](https://linux-hardware.org/?probe=7c8ec90c8a) | Dec 30, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d8ae46ad2b](https://linux-hardware.org/?probe=d8ae46ad2b) | Dec 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4d915292f4](https://linux-hardware.org/?probe=4d915292f4) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| Dell          | 0UW457 A04                  | Desktop     | [047e7036d4](https://linux-hardware.org/?probe=047e7036d4) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [1cab27a65e](https://linux-hardware.org/?probe=1cab27a65e) | Dec 29, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [36074d3f54](https://linux-hardware.org/?probe=36074d3f54) | Dec 29, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [ec9251ac5d](https://linux-hardware.org/?probe=ec9251ac5d) | Dec 28, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9e95d6a4ac](https://linux-hardware.org/?probe=9e95d6a4ac) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fba6e6e090](https://linux-hardware.org/?probe=fba6e6e090) | Dec 27, 2022 |
| Acer          | Aspire M3970                | Desktop     | [c2232f44d6](https://linux-hardware.org/?probe=c2232f44d6) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| Microsoft     | Surface Book                | Tablet      | [c374cd1b63](https://linux-hardware.org/?probe=c374cd1b63) | Dec 27, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [bfc68f7816](https://linux-hardware.org/?probe=bfc68f7816) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkPad T500 205545F       | Notebook    | [c12d9f8c6a](https://linux-hardware.org/?probe=c12d9f8c6a) | Dec 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e9380c21e6](https://linux-hardware.org/?probe=e9380c21e6) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [c9668c2e08](https://linux-hardware.org/?probe=c9668c2e08) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [877e3cd944](https://linux-hardware.org/?probe=877e3cd944) | Dec 26, 2022 |
| Dell          | Latitude E4310              | Notebook    | [f63df6ad2c](https://linux-hardware.org/?probe=f63df6ad2c) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [7b965d8da8](https://linux-hardware.org/?probe=7b965d8da8) | Dec 25, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [61be8271df](https://linux-hardware.org/?probe=61be8271df) | Dec 25, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [90a67d3589](https://linux-hardware.org/?probe=90a67d3589) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [91be8cc560](https://linux-hardware.org/?probe=91be8cc560) | Dec 25, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [dc6cc81a73](https://linux-hardware.org/?probe=dc6cc81a73) | Dec 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [c8b4b6d3bc](https://linux-hardware.org/?probe=c8b4b6d3bc) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| System76      | Pangolin                    | Notebook    | [1c936bfe04](https://linux-hardware.org/?probe=1c936bfe04) | Dec 24, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [90802fc782](https://linux-hardware.org/?probe=90802fc782) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d1e21fd9ca](https://linux-hardware.org/?probe=d1e21fd9ca) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [7fe5933133](https://linux-hardware.org/?probe=7fe5933133) | Dec 23, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [9ca4075241](https://linux-hardware.org/?probe=9ca4075241) | Dec 23, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [099b612c13](https://linux-hardware.org/?probe=099b612c13) | Dec 23, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [723811132a](https://linux-hardware.org/?probe=723811132a) | Dec 23, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [939e438746](https://linux-hardware.org/?probe=939e438746) | Dec 22, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [828e019570](https://linux-hardware.org/?probe=828e019570) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [13e778509f](https://linux-hardware.org/?probe=13e778509f) | Dec 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [b4f32be15b](https://linux-hardware.org/?probe=b4f32be15b) | Dec 22, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [68a977c101](https://linux-hardware.org/?probe=68a977c101) | Dec 22, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [b8f7268dcf](https://linux-hardware.org/?probe=b8f7268dcf) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude D820               | Notebook    | [e79993028e](https://linux-hardware.org/?probe=e79993028e) | Dec 21, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [6651a137ce](https://linux-hardware.org/?probe=6651a137ce) | Dec 20, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [77bf96f401](https://linux-hardware.org/?probe=77bf96f401) | Dec 20, 2022 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [51c1da3d29](https://linux-hardware.org/?probe=51c1da3d29) | Dec 20, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [18e982583e](https://linux-hardware.org/?probe=18e982583e) | Dec 20, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | Desktop     | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [6044a618cf](https://linux-hardware.org/?probe=6044a618cf) | Dec 19, 2022 |
| MSI           | H81M-E34                    | Desktop     | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5ba954d88a](https://linux-hardware.org/?probe=5ba954d88a) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [318b7c1400](https://linux-hardware.org/?probe=318b7c1400) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | Desktop     | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [a5f6a25d72](https://linux-hardware.org/?probe=a5f6a25d72) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [2b955ca3b3](https://linux-hardware.org/?probe=2b955ca3b3) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| HP            | 85BA 00100                  | All in one  | [a67c97653f](https://linux-hardware.org/?probe=a67c97653f) | Dec 18, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| Alienware     | 02XRCM A02                  | Desktop     | [ece4e302f1](https://linux-hardware.org/?probe=ece4e302f1) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | Notebook    | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| Lenovo        | IdeaPad Z570 10249UU        | Notebook    | [2160e3e2c3](https://linux-hardware.org/?probe=2160e3e2c3) | Dec 18, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [071b57d5f6](https://linux-hardware.org/?probe=071b57d5f6) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c5adff1ad5](https://linux-hardware.org/?probe=c5adff1ad5) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [a12207ff89](https://linux-hardware.org/?probe=a12207ff89) | Dec 16, 2022 |
| Google        | Blorb                       | Notebook    | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [20240705a9](https://linux-hardware.org/?probe=20240705a9) | Dec 16, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [8f89f95e37](https://linux-hardware.org/?probe=8f89f95e37) | Dec 16, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e4734e61ed](https://linux-hardware.org/?probe=e4734e61ed) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [2751fbc549](https://linux-hardware.org/?probe=2751fbc549) | Dec 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8968e6816e](https://linux-hardware.org/?probe=8968e6816e) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [7b92a8398f](https://linux-hardware.org/?probe=7b92a8398f) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [36afd57275](https://linux-hardware.org/?probe=36afd57275) | Dec 14, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [c0c28e38d0](https://linux-hardware.org/?probe=c0c28e38d0) | Dec 14, 2022 |
| MSI           | GE72VR 6RF                  | Notebook    | [ce2ebf80a1](https://linux-hardware.org/?probe=ce2ebf80a1) | Dec 14, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [2d1d10e6b9](https://linux-hardware.org/?probe=2d1d10e6b9) | Dec 14, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [32901a2ae5](https://linux-hardware.org/?probe=32901a2ae5) | Dec 13, 2022 |
| Dell          | Latitude E4310              | Notebook    | [dd3e716d03](https://linux-hardware.org/?probe=dd3e716d03) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [c3ad967780](https://linux-hardware.org/?probe=c3ad967780) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [a6ca46d45a](https://linux-hardware.org/?probe=a6ca46d45a) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [4059f02137](https://linux-hardware.org/?probe=4059f02137) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [f89f577056](https://linux-hardware.org/?probe=f89f577056) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [667ee69b40](https://linux-hardware.org/?probe=667ee69b40) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | Desktop     | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [51ddf66bff](https://linux-hardware.org/?probe=51ddf66bff) | Dec 12, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Dell          | Latitude 7430               | Notebook    | [87e9348100](https://linux-hardware.org/?probe=87e9348100) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [ca560a74e4](https://linux-hardware.org/?probe=ca560a74e4) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [d8bb31c8c7](https://linux-hardware.org/?probe=d8bb31c8c7) | Dec 11, 2022 |
| Alienware     | 18                          | Notebook    | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [9451601259](https://linux-hardware.org/?probe=9451601259) | Dec 11, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [51263f4a54](https://linux-hardware.org/?probe=51263f4a54) | Dec 11, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [890f5f6529](https://linux-hardware.org/?probe=890f5f6529) | Dec 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48ccfd51b4](https://linux-hardware.org/?probe=48ccfd51b4) | Dec 11, 2022 |
| ASUSTek       | P5K                         | Desktop     | [7cef6adb1e](https://linux-hardware.org/?probe=7cef6adb1e) | Dec 11, 2022 |
| HP            | 8860 A                      | Desktop     | [c039452bd4](https://linux-hardware.org/?probe=c039452bd4) | Dec 11, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [1a83431b77](https://linux-hardware.org/?probe=1a83431b77) | Dec 11, 2022 |
| Google        | Candy                       | Notebook    | [12e6466598](https://linux-hardware.org/?probe=12e6466598) | Dec 11, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [be6c0926b1](https://linux-hardware.org/?probe=be6c0926b1) | Dec 10, 2022 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [20a5e76a25](https://linux-hardware.org/?probe=20a5e76a25) | Dec 10, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [56347e9ad2](https://linux-hardware.org/?probe=56347e9ad2) | Dec 10, 2022 |
| Dell          | G5 5505                     | Notebook    | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5f3e259429](https://linux-hardware.org/?probe=5f3e259429) | Dec 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [4e829bc252](https://linux-hardware.org/?probe=4e829bc252) | Dec 10, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [fc58d30c61](https://linux-hardware.org/?probe=fc58d30c61) | Dec 10, 2022 |
| HP            | 18E4                        | Desktop     | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| ASUSTek       | P5K                         | Desktop     | [9db010e6f2](https://linux-hardware.org/?probe=9db010e6f2) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [ed7cb7fb48](https://linux-hardware.org/?probe=ed7cb7fb48) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [182502f08c](https://linux-hardware.org/?probe=182502f08c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [aebce6bc5f](https://linux-hardware.org/?probe=aebce6bc5f) | Dec 08, 2022 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [548e2f6cd0](https://linux-hardware.org/?probe=548e2f6cd0) | Dec 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4c7a6feb83](https://linux-hardware.org/?probe=4c7a6feb83) | Dec 08, 2022 |
| ASUSTek       | P5K                         | Desktop     | [832ef547a1](https://linux-hardware.org/?probe=832ef547a1) | Dec 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [91aa6eb03e](https://linux-hardware.org/?probe=91aa6eb03e) | Dec 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [963477cf57](https://linux-hardware.org/?probe=963477cf57) | Dec 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57373e16ba](https://linux-hardware.org/?probe=57373e16ba) | Dec 07, 2022 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [12676c4b5b](https://linux-hardware.org/?probe=12676c4b5b) | Dec 07, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [4c5be8eaf3](https://linux-hardware.org/?probe=4c5be8eaf3) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [388bcfc8e6](https://linux-hardware.org/?probe=388bcfc8e6) | Dec 07, 2022 |
| Dell          | Latitude 5421               | Notebook    | [f310b80613](https://linux-hardware.org/?probe=f310b80613) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [ce36965c1f](https://linux-hardware.org/?probe=ce36965c1f) | Dec 06, 2022 |
| Dell          | Latitude 5421               | Notebook    | [5114034147](https://linux-hardware.org/?probe=5114034147) | Dec 06, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [109d33ef14](https://linux-hardware.org/?probe=109d33ef14) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | Desktop     | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| MSI           | GE72VR 6RF                  | Notebook    | [23a83a5e8e](https://linux-hardware.org/?probe=23a83a5e8e) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [cda3502c1e](https://linux-hardware.org/?probe=cda3502c1e) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| HP            | 15                          | Notebook    | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | Desktop     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| MSI           | GS66 Stealth 11UH           | Notebook    | [b16c3a06ba](https://linux-hardware.org/?probe=b16c3a06ba) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1421946e24](https://linux-hardware.org/?probe=1421946e24) | Dec 05, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [137dd6d1ba](https://linux-hardware.org/?probe=137dd6d1ba) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| Dell          | Latitude 7430               | Notebook    | [d153a4f803](https://linux-hardware.org/?probe=d153a4f803) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | 8158 A01                    | Mini pc     | [f64d5afb00](https://linux-hardware.org/?probe=f64d5afb00) | Dec 05, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d321abafcd](https://linux-hardware.org/?probe=d321abafcd) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| System76      | Gazelle                     | Notebook    | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [8fc8a7552b](https://linux-hardware.org/?probe=8fc8a7552b) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a57440ec11](https://linux-hardware.org/?probe=a57440ec11) | Dec 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [dcd57e5862](https://linux-hardware.org/?probe=dcd57e5862) | Dec 04, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [831d9e3a99](https://linux-hardware.org/?probe=831d9e3a99) | Dec 04, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [6ac526e02a](https://linux-hardware.org/?probe=6ac526e02a) | Dec 04, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [a3ee070c79](https://linux-hardware.org/?probe=a3ee070c79) | Dec 03, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [45543562ff](https://linux-hardware.org/?probe=45543562ff) | Dec 03, 2022 |
| Dell          | Latitude E5450              | Notebook    | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [bee1776fbf](https://linux-hardware.org/?probe=bee1776fbf) | Dec 03, 2022 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [5d702b9b28](https://linux-hardware.org/?probe=5d702b9b28) | Dec 03, 2022 |
| HP            | 1494                        | Desktop     | [d9dd7b9fc1](https://linux-hardware.org/?probe=d9dd7b9fc1) | Dec 03, 2022 |
| HP            | G62                         | Notebook    | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [29d43d4af8](https://linux-hardware.org/?probe=29d43d4af8) | Dec 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| Toshiba       | Satellite S50-A             | Notebook    | [ac76869bea](https://linux-hardware.org/?probe=ac76869bea) | Dec 02, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [a0fe553fc7](https://linux-hardware.org/?probe=a0fe553fc7) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| ASUSTek       | ZenBook UX362FA_UX362FA     | Convertible | [06148b5d6a](https://linux-hardware.org/?probe=06148b5d6a) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [3c05de2bb5](https://linux-hardware.org/?probe=3c05de2bb5) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [17e6d4dbb5](https://linux-hardware.org/?probe=17e6d4dbb5) | Dec 02, 2022 |
| Dell          | Latitude E6410              | Notebook    | [92bae2f9d5](https://linux-hardware.org/?probe=92bae2f9d5) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Notebook    | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [5b22a7d584](https://linux-hardware.org/?probe=5b22a7d584) | Dec 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [019a1b2e2a](https://linux-hardware.org/?probe=019a1b2e2a) | Dec 01, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [5900d34c9a](https://linux-hardware.org/?probe=5900d34c9a) | Dec 01, 2022 |
| HP            | 18E4                        | Desktop     | [b0254c66c7](https://linux-hardware.org/?probe=b0254c66c7) | Dec 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [443bd561a5](https://linux-hardware.org/?probe=443bd561a5) | Dec 01, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [3d92c6cbc8](https://linux-hardware.org/?probe=3d92c6cbc8) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [19c2f41d14](https://linux-hardware.org/?probe=19c2f41d14) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [473821d177](https://linux-hardware.org/?probe=473821d177) | Nov 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [83ef480c7d](https://linux-hardware.org/?probe=83ef480c7d) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [26a5aa815f](https://linux-hardware.org/?probe=26a5aa815f) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 807       | 14.49%  |
| Ubuntu 18.04        | 423       | 7.6%    |
| Ubuntu 22.04        | 238       | 4.27%   |
| OpenMandriva 4.2    | 116       | 2.08%   |
| Debian 11           | 116       | 2.08%   |
| OpenMandriva 4.3    | 115       | 2.07%   |
| Linux Mint 20.3     | 110       | 1.98%   |
| Pop!_OS 22.04       | 109       | 1.96%   |
| KDE neon 20.04      | 100       | 1.8%    |
| Zorin 16            | 98        | 1.76%   |
| Xubuntu 20.04       | 96        | 1.72%   |
| Manjaro             | 94        | 1.69%   |
| Pop!_OS 20.04       | 88        | 1.58%   |
| Pop!_OS 21.04       | 84        | 1.51%   |
| Arch                | 80        | 1.44%   |
| Linux Mint 20.1     | 78        | 1.4%    |
| Arch Rolling        | 77        | 1.38%   |
| Linux Mint 19.3     | 76        | 1.36%   |
| Ubuntu 19.10        | 71        | 1.27%   |
| Zorin 15            | 69        | 1.24%   |
| Ubuntu 21.10        | 69        | 1.24%   |
| Fedora 35           | 68        | 1.22%   |
| ArcoLinux Rolling   | 67        | 1.2%    |
| Ubuntu 20.10        | 66        | 1.19%   |
| OpenMandriva 23.01  | 66        | 1.19%   |
| Pop!_OS 20.10       | 65        | 1.17%   |
| Linux Mint 20.2     | 64        | 1.15%   |
| Fedora 33           | 64        | 1.15%   |
| Linux Mint 20       | 60        | 1.08%   |
| Fedora 32           | 56        | 1.01%   |
| Fedora 37           | 54        | 0.97%   |
| Ubuntu 21.04        | 53        | 0.95%   |
| Fedora 34           | 50        | 0.9%    |
| Ubuntu 19.04        | 48        | 0.86%   |
| Pop!_OS 21.10       | 48        | 0.86%   |
| Fedora 36           | 48        | 0.86%   |
| Linux Mint 21       | 46        | 0.83%   |
| Ubuntu 22.10        | 44        | 0.79%   |
| Linux Mint 21.1     | 38        | 0.68%   |
| EndeavourOS Rolling | 34        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1784      | 33.76%  |
| Linux Mint    | 480       | 9.08%   |
| Pop!_OS       | 379       | 7.17%   |
| Fedora        | 351       | 6.64%   |
| OpenMandriva  | 336       | 6.36%   |
| Manjaro       | 203       | 3.84%   |
| Debian        | 189       | 3.58%   |
| Zorin         | 176       | 3.33%   |
| Arch          | 152       | 2.88%   |
| Xubuntu       | 148       | 2.8%    |
| KDE neon      | 123       | 2.33%   |
| Kubuntu       | 91        | 1.72%   |
| ROSA          | 76        | 1.44%   |
| ArcoLinux     | 71        | 1.34%   |
| Gentoo        | 52        | 0.98%   |
| Elementary    | 45        | 0.85%   |
| openSUSE      | 39        | 0.74%   |
| EndeavourOS   | 38        | 0.72%   |
| Lubuntu       | 36        | 0.68%   |
| Endless       | 35        | 0.66%   |
| SteamOS       | 34        | 0.64%   |
| Ubuntu MATE   | 30        | 0.57%   |
| Clear Linux   | 28        | 0.53%   |
| CentOS        | 28        | 0.53%   |
| BlackPanther  | 28        | 0.53%   |
| Ubuntu Unity  | 26        | 0.49%   |
| Kali          | 26        | 0.49%   |
| LMDE          | 23        | 0.44%   |
| Ubuntu Budgie | 21        | 0.4%    |
| MX            | 18        | 0.34%   |
| Garuda Linux  | 16        | 0.3%    |
| Nobara        | 13        | 0.25%   |
| Peppermint    | 11        | 0.21%   |
| LinuxFX       | 11        | 0.21%   |
| Alpine        | 10        | 0.19%   |
| Rocky Linux   | 8         | 0.15%   |
| RHEL          | 8         | 0.15%   |
| Parrot        | 8         | 0.15%   |
| Reborn OS     | 7         | 0.13%   |
| Raspbian      | 7         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 113       | 1.82%   |
| 5.16.7-desktop-1omv4003  | 108       | 1.74%   |
| 5.4.0-42-generic         | 92        | 1.48%   |
| 5.15.0-56-generic        | 68        | 1.1%    |
| 6.1.1-desktop-1omv2290   | 60        | 0.97%   |
| 5.11.0-27-generic        | 59        | 0.95%   |
| 5.4.0-58-generic         | 53        | 0.85%   |
| 5.15.0-58-generic        | 52        | 0.84%   |
| 5.4.0-48-generic         | 50        | 0.81%   |
| 5.3.0-40-generic         | 50        | 0.81%   |
| 5.15.0-52-generic        | 45        | 0.72%   |
| 5.4.0-52-generic         | 44        | 0.71%   |
| 5.4.0-29-generic         | 43        | 0.69%   |
| 5.8.0-7630-generic       | 42        | 0.68%   |
| 5.11.0-40-generic        | 42        | 0.68%   |
| 5.4.0-40-generic         | 38        | 0.61%   |
| 5.0.0-37-generic         | 38        | 0.61%   |
| 5.4.0-26-generic         | 36        | 0.58%   |
| 5.13.0-39-generic        | 36        | 0.58%   |
| 5.4.0-54-generic         | 35        | 0.56%   |
| 5.3.0-46-generic         | 35        | 0.56%   |
| 5.15.0-48-generic        | 35        | 0.56%   |
| 5.15.0-47-generic        | 33        | 0.53%   |
| 5.15.0-41-generic        | 33        | 0.53%   |
| 5.11.0-7620-generic      | 33        | 0.53%   |
| 5.4.0-37-generic         | 32        | 0.52%   |
| 5.8.0-50-generic         | 31        | 0.5%    |
| 5.4.0-66-generic         | 30        | 0.48%   |
| 5.4.0-45-generic         | 29        | 0.47%   |
| 5.15.0-46-generic        | 29        | 0.47%   |
| 5.4.0-47-generic         | 27        | 0.43%   |
| 5.11.0-38-generic        | 27        | 0.43%   |
| 5.4.0-91-generic         | 26        | 0.42%   |
| 5.4.0-7634-generic       | 26        | 0.42%   |
| 5.4.0-56-generic         | 26        | 0.42%   |
| 5.4.0-33-generic         | 26        | 0.42%   |
| 5.3.0-42-generic         | 26        | 0.42%   |
| 5.19.0-35-generic        | 26        | 0.42%   |
| 5.15.0-60-generic        | 26        | 0.42%   |
| 5.8.0-59-generic         | 25        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1065      | 18.38%  |
| 5.15.0  | 433       | 7.47%   |
| 5.11.0  | 352       | 6.08%   |
| 5.8.0   | 337       | 5.82%   |
| 4.15.0  | 321       | 5.54%   |
| 5.13.0  | 313       | 5.4%    |
| 5.3.0   | 272       | 4.69%   |
| 5.0.0   | 151       | 2.61%   |
| 5.10.0  | 125       | 2.16%   |
| 5.10.14 | 115       | 1.98%   |
| 5.19.0  | 111       | 1.92%   |
| 5.16.7  | 110       | 1.9%    |
| 4.18.0  | 109       | 1.88%   |
| 6.1.1   | 68        | 1.17%   |
| 4.19.0  | 43        | 0.74%   |
| 6.0.12  | 29        | 0.5%    |
| 5.14.0  | 27        | 0.47%   |
| 6.0.6   | 26        | 0.45%   |
| 5.17.5  | 26        | 0.45%   |
| 5.15.5  | 23        | 0.4%    |
| 4.18.16 | 23        | 0.4%    |
| 6.0.0   | 22        | 0.38%   |
| 4.9.20  | 20        | 0.35%   |
| 6.2.6   | 19        | 0.33%   |
| 4.4.0   | 18        | 0.31%   |
| 4.9.60  | 17        | 0.29%   |
| 5.18.0  | 15        | 0.26%   |
| 5.16.0  | 15        | 0.26%   |
| 5.15.11 | 15        | 0.26%   |
| 5.12.4  | 15        | 0.26%   |
| 5.9.16  | 14        | 0.24%   |
| 5.9.11  | 14        | 0.24%   |
| 5.17.9  | 14        | 0.24%   |
| 5.7.0   | 13        | 0.22%   |
| 5.16.13 | 13        | 0.22%   |
| 3.10.0  | 13        | 0.22%   |
| 5.18.12 | 12        | 0.21%   |
| 5.17.0  | 12        | 0.21%   |
| 5.16.11 | 12        | 0.21%   |
| 5.15.15 | 12        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1155      | 20.28%  |
| 5.15    | 617       | 10.84%  |
| 5.8     | 431       | 7.57%   |
| 5.11    | 407       | 7.15%   |
| 5.13    | 368       | 6.46%   |
| 5.10    | 345       | 6.06%   |
| 4.15    | 322       | 5.66%   |
| 5.3     | 293       | 5.15%   |
| 5.16    | 216       | 3.79%   |
| 5.19    | 169       | 2.97%   |
| 5.0     | 160       | 2.81%   |
| 6.0     | 142       | 2.49%   |
| 6.1     | 137       | 2.41%   |
| 4.18    | 132       | 2.32%   |
| 5.17    | 97        | 1.7%    |
| 5.9     | 84        | 1.48%   |
| 5.14    | 81        | 1.42%   |
| 5.18    | 74        | 1.3%    |
| 5.12    | 71        | 1.25%   |
| 4.9     | 66        | 1.16%   |
| 5.6     | 61        | 1.07%   |
| 4.19    | 58        | 1.02%   |
| 5.7     | 51        | 0.9%    |
| 6.2     | 47        | 0.83%   |
| 5.5     | 29        | 0.51%   |
| 4.4     | 22        | 0.39%   |
| 3.10    | 16        | 0.28%   |
| 5.2     | 11        | 0.19%   |
| 4.1     | 6         | 0.11%   |
| 4.13    | 5         | 0.09%   |
| 5.1     | 4         | 0.07%   |
| 4.14    | 3         | 0.05%   |
| 4.8     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.16    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| Unknown | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.11    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4885      | 96.54%  |
| i686    | 114       | 2.25%   |
| aarch64 | 38        | 0.75%   |
| armv7l  | 19        | 0.38%   |
| mips64  | 2         | 0.04%   |
| armv8l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GNOME                | 2344      | 44.04%  |
| KDE5                 | 818       | 15.37%  |
| Unknown              | 707       | 13.28%  |
| X-Cinnamon           | 381       | 7.16%   |
| XFCE                 | 379       | 7.12%   |
| KDE                  | 146       | 2.74%   |
| MATE                 | 118       | 2.22%   |
| Cinnamon             | 68        | 1.28%   |
| KDE4                 | 57        | 1.07%   |
| LXQt                 | 44        | 0.83%   |
| Pantheon             | 43        | 0.81%   |
| i3                   | 36        | 0.68%   |
| Budgie               | 33        | 0.62%   |
| LXDE                 | 30        | 0.56%   |
| Unity                | 29        | 0.54%   |
| GNOME Flashback      | 19        | 0.36%   |
| Deepin               | 13        | 0.24%   |
| GNOME Classic        | 8         | 0.15%   |
| qtile                | 7         | 0.13%   |
| DWM                  | 7         | 0.13%   |
| awesome              | 6         | 0.11%   |
| sway                 | 4         | 0.08%   |
| Openbox              | 4         | 0.08%   |
| Enlightenment        | 4         | 0.08%   |
| xmonad               | 3         | 0.06%   |
| bspwm                | 2         | 0.04%   |
| xsession             | 1         | 0.02%   |
| wmaker-common        | 1         | 0.02%   |
| ubuntustudio         | 1         | 0.02%   |
| trinity              | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| spectrwm             | 1         | 0.02%   |
| river                | 1         | 0.02%   |
| Lubuntu              | 1         | 0.02%   |
| lightdm-xsession     | 1         | 0.02%   |
| LeftWM               | 1         | 0.02%   |
| Hyprland             | 1         | 0.02%   |
| chadwm               | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4053      | 77.69%  |
| Wayland | 684       | 13.11%  |
| Unknown | 352       | 6.75%   |
| Tty     | 123       | 2.36%   |
| Web     | 5         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2907      | 55.05%  |
| SDDM    | 709       | 13.43%  |
| GDM     | 552       | 10.45%  |
| GDM3    | 477       | 9.03%   |
| LightDM | 412       | 7.8%    |
| TDM     | 142       | 2.69%   |
| KDM     | 51        | 0.97%   |
| XDM     | 13        | 0.25%   |
| SLiM    | 7         | 0.13%   |
| Ly      | 5         | 0.09%   |
| LXDM    | 3         | 0.06%   |
| GREETD  | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_CA      | 2681      | 51.13%  |
| en_US      | 1366      | 26.05%  |
| Unknown    | 574       | 10.95%  |
| fr_CA      | 354       | 6.75%   |
| C          | 119       | 2.27%   |
| fr_FR      | 52        | 0.99%   |
| en_GB      | 31        | 0.59%   |
| POSIX      | 8         | 0.15%   |
| en_AU      | 8         | 0.15%   |
| zh_CN      | 4         | 0.08%   |
| pt_BR      | 4         | 0.08%   |
| es_ES      | 4         | 0.08%   |
| en_IN      | 4         | 0.08%   |
| C.UTF8     | 4         | 0.08%   |
| uk_UA      | 3         | 0.06%   |
| ru_RU      | 3         | 0.06%   |
| de_DE      | 3         | 0.06%   |
| zh_TW      | 2         | 0.04%   |
| pl_PL      | 2         | 0.04%   |
| pa_IN      | 2         | 0.04%   |
| ro_RO      | 1         | 0.02%   |
| nan_TW     | 1         | 0.02%   |
| iu_CA      | 1         | 0.02%   |
| hu_HU      | 1         | 0.02%   |
| hr_HR      | 1         | 0.02%   |
| ga_IE      | 1         | 0.02%   |
| es_CL      | 1         | 0.02%   |
| es_BO      | 1         | 0.02%   |
| en_ZM      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_NZ      | 1         | 0.02%   |
| en_IE      | 1         | 0.02%   |
| en_FI      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| co_FR      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2828      | 54.45%  |
| EFI  | 2366      | 45.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3954      | 76.08%  |
| Btrfs   | 443       | 8.52%   |
| Overlay | 432       | 8.31%   |
| Unknown | 177       | 3.41%   |
| Xfs     | 87        | 1.67%   |
| Zfs     | 51        | 0.98%   |
| Ext2    | 19        | 0.37%   |
| Ext3    | 10        | 0.19%   |
| F2fs    | 8         | 0.15%   |
| Aufs    | 8         | 0.15%   |
| Tmpfs   | 5         | 0.1%    |
| Jfs     | 2         | 0.04%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2991      | 57.55%  |
| GPT     | 1684      | 32.4%   |
| MBR     | 522       | 10.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4339      | 83.76%  |
| Yes       | 841       | 16.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3773      | 73.12%  |
| Yes       | 1387      | 26.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 943       | 18.66%  |
| Dell                    | 749       | 14.82%  |
| Lenovo                  | 659       | 13.04%  |
| Hewlett-Packard         | 625       | 12.37%  |
| Acer                    | 377       | 7.46%   |
| MSI                     | 313       | 6.19%   |
| Gigabyte Technology     | 309       | 6.11%   |
| Apple                   | 178       | 3.52%   |
| ASRock                  | 129       | 2.55%   |
| Toshiba                 | 97        | 1.92%   |
| Intel                   | 74        | 1.46%   |
| Raspberry Pi Foundation | 36        | 0.71%   |
| Alienware               | 36        | 0.71%   |
| Sony                    | 33        | 0.65%   |
| Unknown                 | 33        | 0.65%   |
| Valve                   | 29        | 0.57%   |
| Pegatron                | 29        | 0.57%   |
| Supermicro              | 28        | 0.55%   |
| Microsoft               | 28        | 0.55%   |
| Gateway                 | 28        | 0.55%   |
| Foxconn                 | 26        | 0.51%   |
| Samsung Electronics     | 25        | 0.49%   |
| Google                  | 25        | 0.49%   |
| System76                | 18        | 0.36%   |
| Panasonic               | 17        | 0.34%   |
| ECS                     | 12        | 0.24%   |
| Biostar                 | 11        | 0.22%   |
| AZW                     | 11        | 0.22%   |
| ZOTAC                   | 9         | 0.18%   |
| Razer                   | 8         | 0.16%   |
| Fujitsu                 | 8         | 0.16%   |
| Notebook                | 5         | 0.1%    |
| HUAWEI                  | 5         | 0.1%    |
| Framework               | 5         | 0.1%    |
| eMachines               | 5         | 0.1%    |
| ASRockRack              | 5         | 0.1%    |
| AMI                     | 5         | 0.1%    |
| TYAN Computer           | 4         | 0.08%   |
| ReachingTech            | 4         | 0.08%   |
| LG Electronics          | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 59        | 1.17%   |
| Unknown                            | 44        | 0.87%   |
| Valve Jupiter                      | 29        | 0.57%   |
| HP Notebook                        | 22        | 0.44%   |
| ASUS TUF Gaming X570-PLUS          | 19        | 0.38%   |
| HP Pavilion g6                     | 18        | 0.36%   |
| Acer Aspire A315-21                | 15        | 0.3%    |
| MSI MS-7C37                        | 13        | 0.26%   |
| MSI MS-7C02                        | 13        | 0.26%   |
| Dell XPS 15 7590                   | 13        | 0.26%   |
| Dell OptiPlex 790                  | 13        | 0.26%   |
| Dell Latitude E6410                | 13        | 0.26%   |
| ASUS PRIME B450M-A                 | 13        | 0.26%   |
| HP Z400 Workstation                | 12        | 0.24%   |
| Dell XPS 15 9500                   | 12        | 0.24%   |
| Dell Latitude E6420                | 12        | 0.24%   |
| RPi Raspberry Pi                   | 11        | 0.22%   |
| HP Pavilion dv6                    | 11        | 0.22%   |
| ASRock B450M Pro4                  | 11        | 0.22%   |
| Apple MacBookPro9,2                | 11        | 0.22%   |
| Apple iMac8,1                      | 11        | 0.22%   |
| HP Pavilion 15                     | 10        | 0.2%    |
| HP EliteBook 8460p                 | 10        | 0.2%    |
| Dell OptiPlex 780                  | 10        | 0.2%    |
| ASUS TP410UAR                      | 10        | 0.2%    |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.2%    |
| ASUS M5A97 LE R2.0                 | 10        | 0.2%    |
| Apple MacBookPro8,1                | 10        | 0.2%    |
| Apple iMac7,1                      | 10        | 0.2%    |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 9         | 0.18%   |
| MSI MS-7C95                        | 9         | 0.18%   |
| MSI MS-7C84                        | 9         | 0.18%   |
| MSI MS-7C56                        | 9         | 0.18%   |
| MSI MS-7693                        | 9         | 0.18%   |
| HP Pavilion Notebook               | 9         | 0.18%   |
| Gigabyte B450 AORUS PRO WIFI       | 9         | 0.18%   |
| Dell OptiPlex 7010                 | 9         | 0.18%   |
| ASUS M5A99FX PRO R2.0              | 9         | 0.18%   |
| Toshiba Satellite A200             | 8         | 0.16%   |
| HP Compaq Pro 6300 SFF             | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 335       | 6.63%   |
| Acer Aspire         | 296       | 5.86%   |
| Dell Inspiron       | 162       | 3.21%   |
| Dell Latitude       | 160       | 3.17%   |
| Dell XPS            | 133       | 2.63%   |
| Dell OptiPlex       | 122       | 2.41%   |
| HP Pavilion         | 120       | 2.37%   |
| ASUS PRIME          | 115       | 2.28%   |
| Lenovo ThinkCentre  | 104       | 2.06%   |
| ASUS ROG            | 104       | 2.06%   |
| HP Compaq           | 83        | 1.64%   |
| Toshiba Satellite   | 82        | 1.62%   |
| Lenovo IdeaPad      | 81        | 1.6%    |
| HP EliteBook        | 76        | 1.5%    |
| ASUS All            | 59        | 1.17%   |
| Dell Precision      | 57        | 1.13%   |
| ASUS TUF            | 57        | 1.13%   |
| ASUS VivoBook       | 54        | 1.07%   |
| HP Laptop           | 51        | 1.01%   |
| Unknown             | 44        | 0.87%   |
| HP ProBook          | 40        | 0.79%   |
| HP ENVY             | 40        | 0.79%   |
| RPi Raspberry       | 36        | 0.71%   |
| Dell Vostro         | 31        | 0.61%   |
| Valve Jupiter       | 29        | 0.57%   |
| Microsoft Surface   | 28        | 0.55%   |
| Dell Studio         | 27        | 0.53%   |
| Gigabyte X570       | 26        | 0.51%   |
| HP EliteDesk        | 24        | 0.47%   |
| ASUS M5A97          | 23        | 0.46%   |
| HP Notebook         | 22        | 0.44%   |
| ASUS ZenBook        | 22        | 0.44%   |
| Gigabyte B450       | 21        | 0.42%   |
| Acer Swift          | 20        | 0.4%    |
| Lenovo Legion       | 19        | 0.38%   |
| Dell PowerEdge      | 19        | 0.38%   |
| Acer Nitro          | 19        | 0.38%   |
| Lenovo Yoga         | 18        | 0.36%   |
| Lenovo ThinkStation | 18        | 0.36%   |
| ASUS SABERTOOTH     | 18        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 447       | 8.84%   |
| 2020    | 437       | 8.65%   |
| 2012    | 436       | 8.63%   |
| 2011    | 421       | 8.33%   |
| 2019    | 420       | 8.31%   |
| 2013    | 362       | 7.16%   |
| 2017    | 329       | 6.51%   |
| 2010    | 296       | 5.86%   |
| 2014    | 291       | 5.76%   |
| 2008    | 252       | 4.99%   |
| 2016    | 233       | 4.61%   |
| 2021    | 230       | 4.55%   |
| 2009    | 220       | 4.35%   |
| 2015    | 215       | 4.25%   |
| 2007    | 164       | 3.24%   |
| 2022    | 159       | 3.15%   |
| 2006    | 68        | 1.35%   |
| Unknown | 43        | 0.85%   |
| 2005    | 22        | 0.44%   |
| 2004    | 6         | 0.12%   |
| 2023    | 3         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2354      | 46.58%  |
| Desktop        | 2251      | 44.54%  |
| Convertible    | 140       | 2.77%   |
| All in one     | 96        | 1.9%    |
| Mini pc        | 61        | 1.21%   |
| Server         | 60        | 1.19%   |
| System on chip | 49        | 0.97%   |
| Tablet         | 40        | 0.79%   |
| Phone          | 3         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4775      | 93.81%  |
| Enabled  | 315       | 6.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5014      | 99.17%  |
| Yes  | 42        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1107      | 21.55%  |
| 4.01-8.0        | 1103      | 21.48%  |
| 8.01-16.0       | 944       | 18.38%  |
| 3.01-4.0        | 799       | 15.56%  |
| 32.01-64.0      | 598       | 11.64%  |
| 1.01-2.0        | 190       | 3.7%    |
| 64.01-256.0     | 170       | 3.31%   |
| 24.01-32.0      | 98        | 1.91%   |
| 2.01-3.0        | 72        | 1.4%    |
| 0.51-1.0        | 37        | 0.72%   |
| More than 256.0 | 8         | 0.16%   |
| 0.01-0.5        | 8         | 0.16%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1978      | 34.9%   |
| 2.01-3.0    | 1373      | 24.23%  |
| 4.01-8.0    | 851       | 15.02%  |
| 3.01-4.0    | 713       | 12.58%  |
| 0.51-1.0    | 358       | 6.32%   |
| 8.01-16.0   | 235       | 4.15%   |
| 0.01-0.5    | 89        | 1.57%   |
| 24.01-32.0  | 22        | 0.39%   |
| 32.01-64.0  | 20        | 0.35%   |
| 16.01-24.0  | 19        | 0.34%   |
| 64.01-256.0 | 5         | 0.09%   |
| Unknown     | 4         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2954      | 56%     |
| 2       | 1242      | 23.55%  |
| 3       | 460       | 8.72%   |
| 4       | 263       | 4.99%   |
| 5       | 136       | 2.58%   |
| 6       | 65        | 1.23%   |
| 0       | 55        | 1.04%   |
| 7       | 38        | 0.72%   |
| 8       | 21        | 0.4%    |
| 9       | 12        | 0.23%   |
| 10      | 8         | 0.15%   |
| 11      | 6         | 0.11%   |
| 13      | 4         | 0.08%   |
| 12      | 4         | 0.08%   |
| Unknown | 4         | 0.08%   |
| 14      | 2         | 0.04%   |
| 16      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2904      | 56.8%   |
| Yes       | 2209      | 43.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4423      | 87.27%  |
| No        | 645       | 12.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3758      | 73.74%  |
| No        | 1338      | 26.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2875      | 55.97%  |
| No        | 2262      | 44.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 5054      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Toronto         | 508       | 9.53%   |
| Montreal        | 507       | 9.51%   |
| Vancouver       | 232       | 4.35%   |
| Calgary         | 207       | 3.88%   |
| Ottawa          | 194       | 3.64%   |
| Edmonton        | 170       | 3.19%   |
| Québec         | 110       | 2.06%   |
| Winnipeg        | 105       | 1.97%   |
| Mississauga     | 82        | 1.54%   |
| Victoria        | 76        | 1.43%   |
| Surrey          | 62        | 1.16%   |
| Regina          | 57        | 1.07%   |
| Laval           | 56        | 1.05%   |
| Brampton        | 54        | 1.01%   |
| Kitchener       | 53        | 0.99%   |
| London          | 52        | 0.98%   |
| Saskatoon       | 47        | 0.88%   |
| Hamilton        | 47        | 0.88%   |
| Burnaby         | 44        | 0.83%   |
| Gatineau        | 41        | 0.77%   |
| Windsor         | 40        | 0.75%   |
| Halifax         | 37        | 0.69%   |
| Oshawa          | 36        | 0.68%   |
| Sherbrooke      | 32        | 0.6%    |
| Scarborough     | 31        | 0.58%   |
| Kingston        | 31        | 0.58%   |
| Richmond Hill   | 29        | 0.54%   |
| Markham         | 28        | 0.53%   |
| Trois-Rivières | 26        | 0.49%   |
| Oakville        | 26        | 0.49%   |
| New Westminster | 26        | 0.49%   |
| Moncton         | 26        | 0.49%   |
| Barrie          | 26        | 0.49%   |
| North Vancouver | 23        | 0.43%   |
| Kelowna         | 23        | 0.43%   |
| Waterloo        | 22        | 0.41%   |
| Red Deer        | 22        | 0.41%   |
| Fredericton     | 22        | 0.41%   |
| Levis           | 21        | 0.39%   |
| Dartmouth       | 21        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 1428      | 2372   | 18.48%  |
| Seagate                     | 1377      | 2404   | 17.82%  |
| Samsung Electronics         | 1068      | 1687   | 13.82%  |
| Kingston                    | 480       | 665    | 6.21%   |
| Toshiba                     | 407       | 530    | 5.27%   |
| SanDisk                     | 354       | 449    | 4.58%   |
| Unknown                     | 329       | 450    | 4.26%   |
| Hitachi                     | 267       | 352    | 3.46%   |
| Intel                       | 226       | 346    | 2.92%   |
| Crucial                     | 214       | 299    | 2.77%   |
| A-DATA Technology           | 174       | 234    | 2.25%   |
| SK hynix                    | 160       | 193    | 2.07%   |
| HGST                        | 124       | 162    | 1.6%    |
| Micron Technology           | 81        | 114    | 1.05%   |
| Apple                       | 60        | 76     | 0.78%   |
| Phison                      | 54        | 81     | 0.7%    |
| SPCC                        | 43        | 54     | 0.56%   |
| Fujitsu                     | 43        | 55     | 0.56%   |
| OCZ                         | 38        | 50     | 0.49%   |
| KIOXIA                      | 36        | 41     | 0.47%   |
| Silicon Motion              | 33        | 52     | 0.43%   |
| Corsair                     | 32        | 39     | 0.41%   |
| China                       | 32        | 36     | 0.41%   |
| LITEONIT                    | 30        | 33     | 0.39%   |
| PNY                         | 28        | 41     | 0.36%   |
| Micron/Crucial Technology   | 25        | 39     | 0.32%   |
| Patriot                     | 23        | 27     | 0.3%    |
| Mushkin                     | 23        | 27     | 0.3%    |
| ASMT                        | 23        | 28     | 0.3%    |
| LITEON                      | 22        | 24     | 0.28%   |
| Team                        | 20        | 25     | 0.26%   |
| XPG                         | 19        | 28     | 0.25%   |
| JMicron Technology          | 19        | 26     | 0.25%   |
| Phison Electronics          | 18        | 22     | 0.23%   |
| Hewlett-Packard             | 18        | 29     | 0.23%   |
| Unknown                     | 18        | 18     | 0.23%   |
| Kingston Technology Company | 17        | 18     | 0.22%   |
| Maxtor                      | 16        | 22     | 0.21%   |
| KingFast                    | 15        | 18     | 0.19%   |
| SABRENT                     | 14        | 19     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 118       | 1.34%   |
| Samsung SSD 850 EVO 250GB                           | 85        | 0.96%   |
| Samsung SSD 860 EVO 500GB                           | 79        | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB                      | 68        | 0.77%   |
| Kingston SA400S37120G 120GB SSD                     | 64        | 0.73%   |
| Samsung SSD 850 EVO 500GB                           | 63        | 0.71%   |
| Samsung SSD 860 EVO 1TB                             | 56        | 0.63%   |
| Unknown MMC Card  32GB                              | 54        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                      | 54        | 0.61%   |
| Samsung NVMe SSD Drive 500GB                        | 54        | 0.61%   |
| Kingston SA400S37480G 480GB SSD                     | 54        | 0.61%   |
| SanDisk NVMe SSD Drive 500GB                        | 52        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 50        | 0.57%   |
| Unknown MMC Card  64GB                              | 50        | 0.57%   |
| Toshiba MQ01ABD100 1TB                              | 50        | 0.57%   |
| Unknown SD/MMC/MS PRO 64GB                          | 47        | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB                      | 46        | 0.52%   |
| SanDisk NVMe SSD Drive 1TB                          | 45        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 44        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 44        | 0.5%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 43        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                     | 43        | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 0.49%   |
| Samsung SSD 860 EVO 250GB                           | 43        | 0.49%   |
| Kingston SV300S37A120G 120GB SSD                    | 43        | 0.49%   |
| Seagate ST1000LX015-1U7172 1TB                      | 41        | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB                      | 40        | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                      | 40        | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                         | 38        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 37        | 0.42%   |
| Toshiba DT01ACA200 2TB                              | 36        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB                      | 36        | 0.41%   |
| HGST HTS721010A9E630 1TB                            | 36        | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 35        | 0.4%    |
| Seagate Expansion Desk 8TB                          | 34        | 0.39%   |
| Seagate Expansion+ 2TB                              | 33        | 0.37%   |
| Seagate ST3500418AS 500GB                           | 31        | 0.35%   |
| Toshiba DT01ACA100 1TB                              | 30        | 0.34%   |
| Seagate ST31000528AS 1TB                            | 29        | 0.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 29        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1333      | 2309   | 38.9%   |
| WDC                 | 1126      | 1873   | 32.86%  |
| Toshiba             | 330       | 437    | 9.63%   |
| Hitachi             | 267       | 352    | 7.79%   |
| HGST                | 124       | 162    | 3.62%   |
| Samsung Electronics | 53        | 72     | 1.55%   |
| Unknown             | 47        | 61     | 1.37%   |
| Fujitsu             | 43        | 55     | 1.25%   |
| Apple               | 24        | 26     | 0.7%    |
| ASMT                | 18        | 23     | 0.53%   |
| Maxtor              | 16        | 22     | 0.47%   |
| SABRENT             | 13        | 18     | 0.38%   |
| Maxone              | 6         | 8      | 0.18%   |
| JMicron Technology  | 5         | 7      | 0.15%   |
| USB 3.0             | 2         | 6      | 0.06%   |
| Hewlett-Packard     | 2         | 9      | 0.06%   |
| External            | 2         | 2      | 0.06%   |
| DAS                 | 2         | 14     | 0.06%   |
| USB3.0              | 1         | 2      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 6      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 629       | 952    | 25.24%  |
| Kingston            | 414       | 571    | 16.61%  |
| WDC                 | 225       | 314    | 9.03%   |
| Crucial             | 193       | 261    | 7.74%   |
| SanDisk             | 159       | 187    | 6.38%   |
| A-DATA Technology   | 154       | 208    | 6.18%   |
| Intel               | 98        | 133    | 3.93%   |
| Micron Technology   | 51        | 76     | 2.05%   |
| SPCC                | 39        | 50     | 1.57%   |
| OCZ                 | 37        | 46     | 1.48%   |
| China               | 32        | 36     | 1.28%   |
| Seagate             | 31        | 46     | 1.24%   |
| Apple               | 31        | 37     | 1.24%   |
| SK hynix            | 30        | 38     | 1.2%    |
| LITEONIT            | 30        | 33     | 1.2%    |
| PNY                 | 28        | 41     | 1.12%   |
| Toshiba             | 25        | 29     | 1%      |
| Patriot             | 23        | 27     | 0.92%   |
| Mushkin             | 21        | 25     | 0.84%   |
| Team                | 19        | 24     | 0.76%   |
| Corsair             | 19        | 22     | 0.76%   |
| LITEON              | 18        | 19     | 0.72%   |
| Dogfish             | 14        | 18     | 0.56%   |
| TO Exter            | 12        | 14     | 0.48%   |
| Hewlett-Packard     | 10        | 13     | 0.4%    |
| OWC                 | 9         | 18     | 0.36%   |
| NGFF                | 8         | 9      | 0.32%   |
| Transcend           | 7         | 8      | 0.28%   |
| Lexar               | 7         | 8      | 0.28%   |
| KingFast            | 7         | 7      | 0.28%   |
| KingDian            | 7         | 7      | 0.28%   |
| JMicron Technology  | 6         | 9      | 0.24%   |
| Timetec             | 5         | 11     | 0.2%    |
| TCSUNBOW            | 5         | 6      | 0.2%    |
| T-FORCE             | 5         | 5      | 0.2%    |
| WDC WDS             | 4         | 5      | 0.16%   |
| KingSpec            | 4         | 6      | 0.16%   |
| Vaseky              | 3         | 4      | 0.12%   |
| TSA                 | 3         | 3      | 0.12%   |
| Super Talent        | 3         | 4      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2817      | 5477   | 41.61%  |
| SSD     | 2119      | 3408   | 31.3%   |
| NVMe    | 1426      | 2171   | 21.06%  |
| MMC     | 273       | 372    | 4.03%   |
| Unknown | 135       | 184    | 1.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3969      | 8405   | 65.05%  |
| NVMe | 1415      | 2147   | 23.19%  |
| SAS  | 444       | 688    | 7.28%   |
| MMC  | 273       | 372    | 4.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2848      | 4531   | 52.34%  |
| 0.51-1.0        | 1550      | 2445   | 28.49%  |
| 1.01-2.0        | 551       | 958    | 10.13%  |
| 4.01-10.0       | 182       | 380    | 3.34%   |
| 3.01-4.0        | 168       | 295    | 3.09%   |
| 2.01-3.0        | 131       | 249    | 2.41%   |
| 10.01-20.0      | 10        | 24     | 0.18%   |
| More than 100.0 | 1         | 3      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1263      | 23.23%  |
| 251-500        | 1173      | 21.58%  |
| 501-1000       | 840       | 15.45%  |
| 1001-2000      | 456       | 8.39%   |
| 1-20           | 425       | 7.82%   |
| More than 3000 | 387       | 7.12%   |
| 51-100         | 293       | 5.39%   |
| 21-50          | 209       | 3.84%   |
| Unknown        | 201       | 3.7%    |
| 2001-3000      | 189       | 3.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2208      | 39.18%  |
| 21-50          | 946       | 16.78%  |
| 101-250        | 634       | 11.25%  |
| 51-100         | 577       | 10.24%  |
| 251-500        | 382       | 6.78%   |
| 501-1000       | 275       | 4.88%   |
| Unknown        | 201       | 3.57%   |
| 1001-2000      | 193       | 3.42%   |
| More than 3000 | 142       | 2.52%   |
| 2001-3000      | 77        | 1.37%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8         | 9      | 1.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 8      | 1.47%   |
| Toshiba MQ01ABD100 1TB              | 6         | 8      | 1.26%   |
| Seagate ST9500325AS 500GB           | 6         | 6      | 1.26%   |
| Seagate ST500LM000-1EJ162 500GB     | 6         | 6      | 1.26%   |
| WDC WD2500HHTZ-04N21V0 250GB        | 5         | 5      | 1.05%   |
| WDC WD20EARS-00MVWB0 2TB            | 5         | 6      | 1.05%   |
| Seagate ST9500420AS 500GB           | 5         | 5      | 1.05%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.05%   |
| Seagate ST3500418AS 500GB           | 5         | 6      | 1.05%   |
| Seagate ST31000528AS 1TB            | 5         | 5      | 1.05%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.05%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 17     | 0.84%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 7      | 0.84%   |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.84%   |
| Samsung Electronics SSD 870 EVO 1TB | 4         | 5      | 0.84%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 6      | 0.84%   |
| Intel SSDSA1M080G2LE 80GB           | 4         | 4      | 0.84%   |
| Hitachi HDS721010CLA332 1TB         | 4         | 4      | 0.84%   |
| HGST HTS725050A7E630 500GB          | 4         | 5      | 0.84%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.84%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 0.84%   |
| WDC WD6400AAKS-22A7B2 640GB         | 3         | 3      | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB            | 3         | 4      | 0.63%   |
| WDC WD10EARX-00N0YB0 1TB            | 3         | 4      | 0.63%   |
| Toshiba MK3261GSYN 320GB            | 3         | 3      | 0.63%   |
| Toshiba MK2555GSXF 250GB            | 3         | 3      | 0.63%   |
| Seagate ST9320325AS 320GB           | 3         | 6      | 0.63%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 3      | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 4      | 0.63%   |
| Crucial CT1000P1SSD8 1TB            | 3         | 9      | 0.63%   |
| A-DATA Technology SX900 256GB SSD   | 3         | 3      | 0.63%   |
| WDC WD6400AAKS-65Z7B0 640GB         | 2         | 3      | 0.42%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.42%   |
| WDC WD30EZRX-00MMMB0 3TB            | 2         | 6      | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 2         | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 147       | 192    | 31.96%  |
| WDC                 | 120       | 162    | 26.09%  |
| Hitachi             | 38        | 40     | 8.26%   |
| Toshiba             | 30        | 32     | 6.52%   |
| Samsung Electronics | 26        | 35     | 5.65%   |
| HGST                | 18        | 19     | 3.91%   |
| Kingston            | 16        | 22     | 3.48%   |
| Intel               | 13        | 14     | 2.83%   |
| Crucial             | 10        | 17     | 2.17%   |
| A-DATA Technology   | 10        | 11     | 2.17%   |
| SK hynix            | 3         | 3      | 0.65%   |
| Mushkin             | 3         | 3      | 0.65%   |
| LITEONIT            | 3         | 3      | 0.65%   |
| Fujitsu             | 3         | 5      | 0.65%   |
| Apple               | 3         | 3      | 0.65%   |
| SanDisk             | 2         | 2      | 0.43%   |
| OCZ                 | 2         | 2      | 0.43%   |
| Hewlett-Packard     | 2         | 2      | 0.43%   |
| ASMT                | 2         | 3      | 0.43%   |
| Super Talent        | 1         | 1      | 0.22%   |
| Micron Technology   | 1         | 1      | 0.22%   |
| Maxtor              | 1         | 1      | 0.22%   |
| LITEON              | 1         | 1      | 0.22%   |
| LaCie               | 1         | 1      | 0.22%   |
| Drevo               | 1         | 1      | 0.22%   |
| DAS                 | 1         | 3      | 0.22%   |
| Corsair             | 1         | 1      | 0.22%   |
| China               | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 147       | 192    | 39.84%  |
| WDC                 | 120       | 162    | 32.52%  |
| Hitachi             | 38        | 40     | 10.3%   |
| Toshiba             | 28        | 30     | 7.59%   |
| HGST                | 18        | 19     | 4.88%   |
| Samsung Electronics | 8         | 15     | 2.17%   |
| Fujitsu             | 3         | 5      | 0.81%   |
| ASMT                | 2         | 3      | 0.54%   |
| Apple               | 2         | 2      | 0.54%   |
| Maxtor              | 1         | 1      | 0.27%   |
| LaCie               | 1         | 1      | 0.27%   |
| DAS                 | 1         | 3      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 343       | 473    | 78.85%  |
| SSD  | 76        | 85     | 17.47%  |
| NVMe | 16        | 23     | 3.68%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2003FYYS-18W0B0 2TB         | 1         | 1      | 20%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 20%     |
| LITEON CA3-8D512 512GB            | 1         | 2      | 20%     |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 20%     |
| Hewlett-Packard EF0450FARMV 450GB | 1         | 4      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEON              | 1         | 2      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hewlett-Packard     | 1         | 4      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3341      | 7463   | 60.24%  |
| Works    | 1780      | 3559   | 32.1%   |
| Malfunc  | 420       | 581    | 7.57%   |
| Failed   | 5         | 9      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3247      | 50.17%  |
| AMD                              | 1167      | 18.03%  |
| Samsung Electronics              | 504       | 7.79%   |
| SanDisk                          | 332       | 5.13%   |
| ASMedia Technology               | 149       | 2.3%    |
| Marvell Technology Group         | 128       | 1.98%   |
| SK hynix                         | 126       | 1.95%   |
| Nvidia                           | 115       | 1.78%   |
| JMicron Technology               | 92        | 1.42%   |
| Kingston Technology Company      | 84        | 1.3%    |
| Phison Electronics               | 83        | 1.28%   |
| Toshiba America Info Systems     | 54        | 0.83%   |
| Micron/Crucial Technology        | 47        | 0.73%   |
| ADATA Technology                 | 46        | 0.71%   |
| Silicon Motion                   | 44        | 0.68%   |
| LSI Logic / Symbios Logic        | 39        | 0.6%    |
| KIOXIA                           | 39        | 0.6%    |
| Micron Technology                | 32        | 0.49%   |
| Broadcom / LSI                   | 25        | 0.39%   |
| Silicon Image                    | 15        | 0.23%   |
| Realtek Semiconductor            | 15        | 0.23%   |
| Seagate Technology               | 13        | 0.2%    |
| VIA Technologies                 | 9         | 0.14%   |
| Union Memory (Shenzhen)          | 9         | 0.14%   |
| Lite-On Technology               | 7         | 0.11%   |
| Lenovo                           | 7         | 0.11%   |
| Hewlett-Packard                  | 7         | 0.11%   |
| Apple                            | 6         | 0.09%   |
| INNOGRIT                         | 5         | 0.08%   |
| HighPoint Technologies           | 4         | 0.06%   |
| Adaptec                          | 4         | 0.06%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| OCZ Technology Group             | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 770       | 10.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 262       | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 226       | 2.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 207       | 2.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 174       | 2.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 167       | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 167       | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 165       | 2.16%   |
| Intel SATA Controller [RAID mode]                                              | 146       | 1.91%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 140       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 137       | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 135       | 1.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 117       | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 115       | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 105       | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 98        | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 95        | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 94        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 90        | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 89        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 87        | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 83        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 82        | 1.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 80        | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 78        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 78        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 77        | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 75        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 74        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 70        | 0.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 70        | 0.92%   |
| Samsung NVMe SSD Controller 980                                                | 66        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 63        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 63        | 0.83%   |
| Intel SSD 660P Series                                                          | 58        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 57        | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 49        | 0.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 49        | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                             | 48        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 47        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3675      | 56.75%  |
| NVMe | 1431      | 22.1%   |
| IDE  | 807       | 12.46%  |
| RAID | 504       | 7.78%   |
| SAS  | 46        | 0.71%   |
| SCSI | 13        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 3623      | 71.69%  |
| AMD      | 1371      | 27.13%  |
| ARM      | 53        | 1.05%   |
| Unknown  | 6         | 0.12%   |
| QUALCOMM | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 55        | 1.09%   |
| AMD Ryzen 5 3600 6-Core Processor       | 50        | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 43        | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 40        | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 39        | 0.77%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 39        | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 38        | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 34        | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 34        | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 34        | 0.67%   |
| ARM Processor                           | 34        | 0.67%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 34        | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 33        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 32        | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 31        | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 31        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 30        | 0.59%   |
| AMD Custom APU 0405                     | 29        | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 28        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 28        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 27        | 0.53%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 27        | 0.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 27        | 0.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 27        | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 26        | 0.51%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 26        | 0.51%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 25        | 0.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 25        | 0.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 25        | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 25        | 0.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 23        | 0.45%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 23        | 0.45%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 23        | 0.45%   |
| AMD FX-8350 Eight-Core Processor        | 23        | 0.45%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 22        | 0.43%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 21        | 0.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 21        | 0.41%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 21        | 0.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 21        | 0.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 20        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1067      | 21.08%  |
| Intel Core i7           | 1041      | 20.56%  |
| Other                   | 307       | 6.06%   |
| AMD Ryzen 5             | 262       | 5.18%   |
| AMD Ryzen 7             | 254       | 5.02%   |
| Intel Core i3           | 251       | 4.96%   |
| Intel Core 2 Duo        | 248       | 4.9%    |
| Intel Xeon              | 185       | 3.65%   |
| Intel Celeron           | 152       | 3%      |
| AMD FX                  | 107       | 2.11%   |
| AMD Ryzen 9             | 97        | 1.92%   |
| Intel Pentium           | 92        | 1.82%   |
| AMD A6                  | 72        | 1.42%   |
| AMD A10                 | 66        | 1.3%    |
| Intel Core 2 Quad       | 62        | 1.22%   |
| Intel Atom              | 62        | 1.22%   |
| Intel Pentium Dual-Core | 57        | 1.13%   |
| AMD Ryzen 3             | 47        | 0.93%   |
| Intel Core i9           | 44        | 0.87%   |
| AMD A8                  | 42        | 0.83%   |
| AMD Athlon 64 X2        | 40        | 0.79%   |
| Intel Pentium Dual      | 39        | 0.77%   |
| Intel Core 2            | 37        | 0.73%   |
| AMD A4                  | 35        | 0.69%   |
| Intel Genuine           | 22        | 0.43%   |
| AMD Athlon II X2        | 22        | 0.43%   |
| AMD Phenom II X4        | 19        | 0.38%   |
| AMD Phenom II X6        | 18        | 0.36%   |
| AMD E                   | 18        | 0.36%   |
| AMD Phenom              | 17        | 0.34%   |
| Intel Pentium Silver    | 16        | 0.32%   |
| Intel Pentium D         | 16        | 0.32%   |
| Intel Pentium 4         | 15        | 0.3%    |
| AMD Ryzen Threadripper  | 14        | 0.28%   |
| AMD Athlon              | 14        | 0.28%   |
| AMD E2                  | 13        | 0.26%   |
| AMD E1                  | 13        | 0.26%   |
| AMD Ryzen 5 PRO         | 11        | 0.22%   |
| AMD Turion 64 X2 Mobile | 10        | 0.2%    |
| AMD Athlon X2           | 10        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1881      | 37.09%  |
| 2       | 1856      | 36.6%   |
| 6       | 523       | 10.31%  |
| 8       | 406       | 8.01%   |
| 1       | 107       | 2.11%   |
| 12      | 104       | 2.05%   |
| 16      | 55        | 1.08%   |
| 3       | 50        | 0.99%   |
| 10      | 30        | 0.59%   |
| 14      | 26        | 0.51%   |
| 24      | 12        | 0.24%   |
| Unknown | 11        | 0.22%   |
| 20      | 5         | 0.1%    |
| 56      | 2         | 0.04%   |
| 64      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 7       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4968      | 98.22%  |
| 2       | 79        | 1.56%   |
| Unknown | 9         | 0.18%   |
| 3       | 2         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3263      | 64.42%  |
| 1       | 1789      | 35.32%  |
| Unknown | 11        | 0.22%   |
| 12      | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4909      | 96.75%  |
| Unknown        | 118       | 2.33%   |
| 32-bit         | 38        | 0.75%   |
| 64-bit         | 9         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1335      | 25.37%  |
| 0x306a9    | 292       | 5.55%   |
| 0x206a7    | 278       | 5.28%   |
| 0x306c3    | 222       | 4.22%   |
| 0x1067a    | 180       | 3.42%   |
| 0x906ea    | 134       | 2.55%   |
| 0x506e3    | 99        | 1.88%   |
| 0x806ea    | 92        | 1.75%   |
| 0x40651    | 88        | 1.67%   |
| 0x08701021 | 88        | 1.67%   |
| 0x20655    | 86        | 1.63%   |
| 0x906e9    | 85        | 1.62%   |
| 0x6fd      | 73        | 1.39%   |
| 0x806e9    | 71        | 1.35%   |
| 0x406e3    | 70        | 1.33%   |
| 0x806ec    | 59        | 1.12%   |
| 0x06001119 | 58        | 1.1%    |
| 0x306d4    | 55        | 1.05%   |
| 0x20652    | 55        | 1.05%   |
| 0x10676    | 52        | 0.99%   |
| 0x806c1    | 50        | 0.95%   |
| 0x6fb      | 50        | 0.95%   |
| 0x106e5    | 49        | 0.93%   |
| 0x08701013 | 49        | 0.93%   |
| 0x0800820d | 49        | 0.93%   |
| 0x06000852 | 48        | 0.91%   |
| 0xa0652    | 46        | 0.87%   |
| 0x010000c8 | 44        | 0.84%   |
| 0x706e5    | 37        | 0.7%    |
| 0x0a50000c | 37        | 0.7%    |
| 0x206d7    | 36        | 0.68%   |
| 0x30678    | 35        | 0.67%   |
| 0x406c4    | 33        | 0.63%   |
| 0x906ed    | 32        | 0.61%   |
| 0x08108109 | 32        | 0.61%   |
| 0x906a3    | 31        | 0.59%   |
| 0x106a5    | 31        | 0.59%   |
| 0x206c2    | 27        | 0.51%   |
| 0x03000027 | 27        | 0.51%   |
| 0x08108102 | 26        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 661       | 13.07%  |
| Haswell          | 441       | 8.72%   |
| IvyBridge        | 390       | 7.71%   |
| SandyBridge      | 378       | 7.47%   |
| Penryn           | 286       | 5.65%   |
| Zen 2            | 253       | 5%      |
| Skylake          | 230       | 4.55%   |
| Westmere         | 200       | 3.95%   |
| Core             | 199       | 3.93%   |
| Unknown          | 194       | 3.83%   |
| Zen+             | 152       | 3%      |
| Piledriver       | 148       | 2.93%   |
| Zen 3            | 142       | 2.81%   |
| K10              | 127       | 2.51%   |
| Silvermont       | 118       | 2.33%   |
| CometLake        | 118       | 2.33%   |
| Zen              | 111       | 2.19%   |
| Nehalem          | 104       | 2.06%   |
| Excavator        | 88        | 1.74%   |
| Broadwell        | 88        | 1.74%   |
| TigerLake        | 77        | 1.52%   |
| K8 Hammer        | 65        | 1.28%   |
| IceLake          | 64        | 1.27%   |
| Alderlake Hybrid | 56        | 1.11%   |
| Goldmont plus    | 46        | 0.91%   |
| Puma             | 39        | 0.77%   |
| Bobcat           | 39        | 0.77%   |
| NetBurst         | 36        | 0.71%   |
| K10 Llano        | 35        | 0.69%   |
| Bulldozer        | 34        | 0.67%   |
| Bonnell          | 27        | 0.53%   |
| Jaguar           | 26        | 0.51%   |
| Goldmont         | 25        | 0.49%   |
| P6               | 23        | 0.45%   |
| Steamroller      | 21        | 0.42%   |
| K8 & K10 hybrid  | 12        | 0.24%   |
| Tremont          | 6         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2544      | 44.39%  |
| Nvidia                                       | 1660      | 28.97%  |
| AMD                                          | 1456      | 25.41%  |
| Matrox Electronics Systems                   | 39        | 0.68%   |
| ASPEED Technology                            | 23        | 0.4%    |
| Silicon Integrated Systems [SiS]             | 3         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.03%   |
| VIA Technologies                             | 2         | 0.03%   |
| Loongson Technology                          | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 242       | 4.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 182       | 3.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 142       | 2.39%   |
| Intel UHD Graphics 620                                                                   | 124       | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 122       | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 110       | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 104       | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 94        | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 93        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 82        | 1.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 81        | 1.36%   |
| Intel HD Graphics 530                                                                    | 79        | 1.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 76        | 1.28%   |
| Intel HD Graphics 620                                                                    | 73        | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 71        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 70        | 1.18%   |
| AMD Renoir                                                                               | 67        | 1.13%   |
| Intel HD Graphics 5500                                                                   | 64        | 1.08%   |
| Intel HD Graphics 630                                                                    | 62        | 1.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 60        | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 58        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 55        | 0.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 54        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 53        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 50        | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 50        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 46        | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 45        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 41        | 0.69%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 39        | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 36        | 0.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 0.6%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 36        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 35        | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 35        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 34        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 1929      | 37.79%  |
| 1 x AMD                   | 1234      | 24.18%  |
| 1 x Nvidia                | 1078      | 21.12%  |
| Intel + Nvidia            | 455       | 8.91%   |
| Intel + AMD               | 75        | 1.47%   |
| AMD + Nvidia              | 73        | 1.43%   |
| 2 x AMD                   | 70        | 1.37%   |
| Other                     | 66        | 1.29%   |
| 2 x Nvidia                | 39        | 0.76%   |
| 1 x Matrox                | 29        | 0.57%   |
| 1 x ASPEED                | 19        | 0.37%   |
| 2 x Intel                 | 8         | 0.16%   |
| Nvidia + Matrox           | 8         | 0.16%   |
| Intel + 2 x Nvidia        | 4         | 0.08%   |
| 1 x SiS                   | 3         | 0.06%   |
| Nvidia + ASPEED           | 3         | 0.06%   |
| 1 x VIA                   | 2         | 0.04%   |
| AMD + Matrox              | 2         | 0.04%   |
| 5 x Nvidia                | 1         | 0.02%   |
| 2 x Loongson Technology   | 1         | 0.02%   |
| 1 x XGI                   | 1         | 0.02%   |
| 1 x Intel + 3 x AMD       | 1         | 0.02%   |
| AMD + 2 x Nvidia          | 1         | 0.02%   |
| AMD + XGI                 | 1         | 0.02%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3942      | 76.68%  |
| Proprietary | 949       | 18.46%  |
| Unknown     | 250       | 4.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2802      | 53.38%  |
| 0.01-0.5   | 642       | 12.23%  |
| 1.01-2.0   | 545       | 10.38%  |
| 0.51-1.0   | 386       | 7.35%   |
| 7.01-8.0   | 306       | 5.83%   |
| 3.01-4.0   | 300       | 5.72%   |
| 5.01-6.0   | 140       | 2.67%   |
| 8.01-16.0  | 79        | 1.51%   |
| 2.01-3.0   | 42        | 0.8%    |
| 4.01-5.0   | 3         | 0.06%   |
| 16.01-24.0 | 3         | 0.06%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 737       | 13.11%  |
| AU Optronics            | 550       | 9.79%   |
| LG Display              | 406       | 7.22%   |
| Dell                    | 378       | 6.73%   |
| Goldstar                | 336       | 5.98%   |
| Chimei Innolux          | 309       | 5.5%    |
| Acer                    | 309       | 5.5%    |
| BOE                     | 264       | 4.7%    |
| Hewlett-Packard         | 238       | 4.23%   |
| Ancor Communications    | 209       | 3.72%   |
| Sharp                   | 167       | 2.97%   |
| BenQ                    | 166       | 2.95%   |
| Apple                   | 157       | 2.79%   |
| Lenovo                  | 134       | 2.38%   |
| ViewSonic               | 114       | 2.03%   |
| ASUSTek Computer        | 105       | 1.87%   |
| Chi Mei Optoelectronics | 75        | 1.33%   |
| LG Electronics          | 66        | 1.17%   |
| Unknown                 | 58        | 1.03%   |
| Toshiba                 | 57        | 1.01%   |
| Philips                 | 57        | 1.01%   |
| Sony                    | 54        | 0.96%   |
| AOC                     | 52        | 0.93%   |
| PANDA                   | 43        | 0.77%   |
| LG Philips              | 31        | 0.55%   |
| InfoVision              | 25        | 0.44%   |
| NEC Computers           | 24        | 0.43%   |
| MSI                     | 24        | 0.43%   |
| Panasonic               | 23        | 0.41%   |
| HannStar                | 19        | 0.34%   |
| Valve                   | 16        | 0.28%   |
| Insignia                | 15        | 0.27%   |
| HKC                     | 15        | 0.27%   |
| Gigabyte Technology     | 15        | 0.27%   |
| Gateway                 | 15        | 0.27%   |
| Unknown                 | 15        | 0.27%   |
| Vizio                   | 12        | 0.21%   |
| AUS                     | 12        | 0.21%   |
| Sceptre Tech            | 10        | 0.18%   |
| Hitachi                 | 10        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 31        | 0.52%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 31        | 0.52%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 30        | 0.51%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 24        | 0.41%   |
| Toshiba TV TSB0206 1920x1080                                             | 21        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 18        | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 18        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch    | 17        | 0.29%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 16        | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 15        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.25%   |
| Unknown                                                                  | 15        | 0.25%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 14        | 0.24%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                   | 14        | 0.24%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 13        | 0.22%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 13        | 0.22%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch    | 13        | 0.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 12        | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.2%    |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                        | 12        | 0.2%    |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch             | 12        | 0.2%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 11        | 0.19%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 11        | 0.19%   |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                         | 11        | 0.19%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                   | 11        | 0.19%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.19%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.19%   |
| Toshiba TV TSB0205 1360x765 886x498mm 40.0-inch                          | 10        | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 10        | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.17%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                        | 10        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2168      | 40.06%  |
| 1366x768 (WXGA)    | 838       | 15.48%  |
| 3840x2160 (4K)     | 359       | 6.63%   |
| 1680x1050 (WSXGA+) | 262       | 4.84%   |
| 2560x1440 (QHD)    | 250       | 4.62%   |
| 1600x900 (HD+)     | 232       | 4.29%   |
| 1280x1024 (SXGA)   | 188       | 3.47%   |
| 1920x1200 (WUXGA)  | 152       | 2.81%   |
| 1280x800 (WXGA)    | 152       | 2.81%   |
| 1440x900 (WXGA+)   | 134       | 2.48%   |
| Unknown            | 119       | 2.2%    |
| 3440x1440          | 57        | 1.05%   |
| 1360x768           | 56        | 1.03%   |
| 3840x1080          | 49        | 0.91%   |
| 2560x1080          | 34        | 0.63%   |
| 1920x540           | 32        | 0.59%   |
| 2880x1800          | 26        | 0.48%   |
| 2560x1600          | 22        | 0.41%   |
| 1600x1200          | 20        | 0.37%   |
| 800x1280           | 16        | 0.3%    |
| 1024x768 (XGA)     | 16        | 0.3%    |
| 3840x2400          | 15        | 0.28%   |
| 3200x1800 (QHD+)   | 14        | 0.26%   |
| 1280x720 (HD)      | 14        | 0.26%   |
| 1024x600           | 13        | 0.24%   |
| 2736x1824          | 12        | 0.22%   |
| 5760x1080          | 7         | 0.13%   |
| 3840x1200          | 7         | 0.13%   |
| 3600x1080          | 7         | 0.13%   |
| 2160x1440          | 7         | 0.13%   |
| 7680x2160          | 6         | 0.11%   |
| 3200x2000          | 6         | 0.11%   |
| 2256x1504          | 6         | 0.11%   |
| 2048x1152          | 6         | 0.11%   |
| 3200x1080          | 5         | 0.09%   |
| 2288x1287          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 3456x2160          | 4         | 0.07%   |
| 3280x1080          | 4         | 0.07%   |
| 5760x2160          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1214      | 21.76%  |
| 27      | 450       | 8.07%   |
| 13      | 416       | 7.46%   |
| 24      | 407       | 7.3%    |
| Unknown | 398       | 7.13%   |
| 23      | 389       | 6.97%   |
| 21      | 340       | 6.09%   |
| 14      | 323       | 5.79%   |
| 17      | 282       | 5.05%   |
| 19      | 175       | 3.14%   |
| 22      | 152       | 2.72%   |
| 31      | 148       | 2.65%   |
| 20      | 142       | 2.55%   |
| 34      | 76        | 1.36%   |
| 18      | 75        | 1.34%   |
| 12      | 72        | 1.29%   |
| 72      | 59        | 1.06%   |
| 11      | 54        | 0.97%   |
| 84      | 53        | 0.95%   |
| 32      | 38        | 0.68%   |
| 40      | 26        | 0.47%   |
| 25      | 23        | 0.41%   |
| 74      | 21        | 0.38%   |
| 54      | 19        | 0.34%   |
| 16      | 19        | 0.34%   |
| 37      | 18        | 0.32%   |
| 26      | 18        | 0.32%   |
| 10      | 18        | 0.32%   |
| 7       | 14        | 0.25%   |
| 43      | 13        | 0.23%   |
| 48      | 12        | 0.22%   |
| 28      | 12        | 0.22%   |
| 47      | 9         | 0.16%   |
| 36      | 9         | 0.16%   |
| 46      | 8         | 0.14%   |
| 49      | 7         | 0.13%   |
| 52      | 6         | 0.11%   |
| 42      | 6         | 0.11%   |
| 39      | 6         | 0.11%   |
| 69      | 5         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1765      | 32.4%   |
| 501-600        | 1128      | 20.71%  |
| 401-500        | 769       | 14.12%  |
| Unknown        | 398       | 7.31%   |
| 201-300        | 368       | 6.76%   |
| 351-400        | 361       | 6.63%   |
| 601-700        | 215       | 3.95%   |
| 1501-2000      | 142       | 2.61%   |
| 701-800        | 123       | 2.26%   |
| 1001-1500      | 81        | 1.49%   |
| 801-900        | 59        | 1.08%   |
| 901-1000       | 21        | 0.39%   |
| 1-100          | 14        | 0.26%   |
| More than 2000 | 2         | 0.04%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3465      | 69.42%  |
| 16/10   | 767       | 15.37%  |
| Unknown | 325       | 6.51%   |
| 5/4     | 174       | 3.49%   |
| 21/9    | 84        | 1.68%   |
| 3/2     | 65        | 1.3%    |
| 4/3     | 48        | 0.96%   |
| 32/9    | 19        | 0.38%   |
| 6/5     | 14        | 0.28%   |
| 0.67    | 14        | 0.28%   |
| 1.96    | 4         | 0.08%   |
| 3.40    | 2         | 0.04%   |
| 1.00    | 2         | 0.04%   |
| 0.62    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1204      | 21.97%  |
| 201-250        | 1032      | 18.83%  |
| 81-90          | 562       | 10.26%  |
| 301-350        | 463       | 8.45%   |
| 151-200        | 405       | 7.39%   |
| Unknown        | 398       | 7.26%   |
| 351-500        | 274       | 5%      |
| More than 1000 | 194       | 3.54%   |
| 71-80          | 175       | 3.19%   |
| 121-130        | 169       | 3.08%   |
| 141-150        | 139       | 2.54%   |
| 251-300        | 136       | 2.48%   |
| 501-1000       | 113       | 2.06%   |
| 61-70          | 59        | 1.08%   |
| 51-60          | 57        | 1.04%   |
| 131-140        | 31        | 0.57%   |
| 111-120        | 24        | 0.44%   |
| 41-50          | 17        | 0.31%   |
| 1-40           | 15        | 0.27%   |
| 91-100         | 13        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1945      | 36.71%  |
| 101-120       | 1312      | 24.76%  |
| 121-160       | 1072      | 20.23%  |
| Unknown       | 398       | 7.51%   |
| 161-240       | 250       | 4.72%   |
| 1-50          | 199       | 3.76%   |
| More than 240 | 123       | 2.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3919      | 75.42%  |
| 2     | 869       | 16.72%  |
| 0     | 253       | 4.87%   |
| 3     | 141       | 2.71%   |
| 4     | 11        | 0.21%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2646      | 34.81%  |
| Realtek Semiconductor           | 2371      | 31.19%  |
| Qualcomm Atheros                | 849       | 11.17%  |
| Broadcom                        | 526       | 6.92%   |
| Broadcom Limited                | 132       | 1.74%   |
| Marvell Technology Group        | 122       | 1.6%    |
| Ralink                          | 99        | 1.3%    |
| Nvidia                          | 99        | 1.3%    |
| Ralink Technology               | 73        | 0.96%   |
| TP-Link                         | 70        | 0.92%   |
| MediaTek                        | 63        | 0.83%   |
| D-Link                          | 61        | 0.8%    |
| ASIX Electronics                | 59        | 0.78%   |
| Linksys                         | 43        | 0.57%   |
| D-Link System                   | 33        | 0.43%   |
| ASUSTek Computer                | 33        | 0.43%   |
| Samsung Electronics             | 29        | 0.38%   |
| Qualcomm Atheros Communications | 27        | 0.36%   |
| Microsoft                       | 21        | 0.28%   |
| Aquantia                        | 21        | 0.28%   |
| NetGear                         | 19        | 0.25%   |
| Lenovo                          | 17        | 0.22%   |
| DisplayLink                     | 17        | 0.22%   |
| Google                          | 12        | 0.16%   |
| Belkin Components               | 10        | 0.13%   |
| Sierra Wireless                 | 9         | 0.12%   |
| Qualcomm                        | 6         | 0.08%   |
| Motorola PCS                    | 6         | 0.08%   |
| Apple                           | 6         | 0.08%   |
| Microchip Technology            | 5         | 0.07%   |
| Edimax Technology               | 5         | 0.07%   |
| Arduino SA                      | 5         | 0.07%   |
| AMD                             | 5         | 0.07%   |
| VIA Technologies                | 4         | 0.05%   |
| Micro Star International        | 4         | 0.05%   |
| LG Electronics                  | 4         | 0.05%   |
| Hewlett-Packard                 | 4         | 0.05%   |
| Gemtek                          | 4         | 0.05%   |
| Dell                            | 4         | 0.05%   |
| ZyDAS                           | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1577      | 17.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 289       | 3.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 270       | 3%      |
| Intel Wi-Fi 6 AX200                                               | 251       | 2.79%   |
| Intel I211 Gigabit Network Connection                             | 160       | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 153       | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 128       | 1.42%   |
| Intel Wireless 7260                                               | 114       | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 112       | 1.25%   |
| Intel Wireless 7265                                               | 106       | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 105       | 1.17%   |
| Intel Ethernet Connection (2) I219-V                              | 95        | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 93        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 92        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 90        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 88        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 87        | 0.97%   |
| Intel Wireless 8260                                               | 86        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 83        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 82        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 82        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 72        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 70        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 61        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 61        | 0.68%   |
| Intel Wi-Fi 6 AX201                                               | 59        | 0.66%   |
| Intel Wireless-AC 9260                                            | 57        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 52        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 51        | 0.57%   |
| Intel Wireless 3165                                               | 50        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48        | 0.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 47        | 0.52%   |
| Intel Centrino Ultimate-N 6300                                    | 47        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 47        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 46        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 45        | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 45        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1802      | 44.66%  |
| Qualcomm Atheros                      | 672       | 16.65%  |
| Realtek Semiconductor                 | 551       | 13.66%  |
| Broadcom                              | 346       | 8.57%   |
| Ralink                                | 99        | 2.45%   |
| Broadcom Limited                      | 78        | 1.93%   |
| Ralink Technology                     | 73        | 1.81%   |
| TP-Link                               | 64        | 1.59%   |
| MediaTek                              | 61        | 1.51%   |
| D-Link                                | 60        | 1.49%   |
| Linksys                               | 41        | 1.02%   |
| ASUSTek Computer                      | 33        | 0.82%   |
| Qualcomm Atheros Communications       | 27        | 0.67%   |
| Marvell Technology Group              | 21        | 0.52%   |
| D-Link System                         | 21        | 0.52%   |
| NetGear                               | 19        | 0.47%   |
| Microsoft                             | 15        | 0.37%   |
| Belkin Components                     | 10        | 0.25%   |
| Sierra Wireless                       | 9         | 0.22%   |
| Qualcomm                              | 5         | 0.12%   |
| Edimax Technology                     | 5         | 0.12%   |
| Micro Star International              | 4         | 0.1%    |
| Gemtek                                | 4         | 0.1%    |
| ZyDAS                                 | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| Dell                                  | 2         | 0.05%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Cypress Semiconductor                 | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| Belkin                                | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 251       | 6.16%   |
| Intel Wireless 8265 / 8275                                     | 153       | 3.75%   |
| Intel Wireless 7260                                            | 114       | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 112       | 2.75%   |
| Intel Wireless 7265                                            | 106       | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 92        | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 90        | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 88        | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 87        | 2.13%   |
| Intel Wireless 8260                                            | 86        | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 83        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 82        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 82        | 2.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 72        | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 70        | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 61        | 1.5%    |
| Intel Wi-Fi 6 AX201                                            | 59        | 1.45%   |
| Intel Wireless-AC 9260                                         | 57        | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 51        | 1.25%   |
| Intel Wireless 3165                                            | 50        | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 47        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                 | 47        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 47        | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 45        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 45        | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 43        | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 41        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 39        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 37        | 0.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 37        | 0.91%   |
| Realtek 802.11ac NIC                                           | 35        | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 34        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 34        | 0.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 33        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 32        | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 32        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 31        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 30        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 30        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 30        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2126      | 44.99%  |
| Intel                             | 1557      | 32.95%  |
| Broadcom                          | 275       | 5.82%   |
| Qualcomm Atheros                  | 264       | 5.59%   |
| Marvell Technology Group          | 101       | 2.14%   |
| Nvidia                            | 98        | 2.07%   |
| Broadcom Limited                  | 59        | 1.25%   |
| ASIX Electronics                  | 59        | 1.25%   |
| Samsung Electronics               | 29        | 0.61%   |
| Aquantia                          | 21        | 0.44%   |
| DisplayLink                       | 17        | 0.36%   |
| Lenovo                            | 16        | 0.34%   |
| D-Link System                     | 12        | 0.25%   |
| Google                            | 10        | 0.21%   |
| TP-Link                           | 8         | 0.17%   |
| Apple                             | 6         | 0.13%   |
| VIA Technologies                  | 4         | 0.08%   |
| Microsoft                         | 4         | 0.08%   |
| LG Electronics                    | 4         | 0.08%   |
| Hewlett-Packard                   | 4         | 0.08%   |
| Xiaomi                            | 3         | 0.06%   |
| Research In Motion                | 3         | 0.06%   |
| Microchip Technology              | 3         | 0.06%   |
| Mellanox Technologies             | 3         | 0.06%   |
| JMicron Technology                | 3         | 0.06%   |
| 3Com                              | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.04%   |
| Motorola PCS                      | 2         | 0.04%   |
| MediaTek                          | 2         | 0.04%   |
| Linksys                           | 2         | 0.04%   |
| ICS Advent                        | 2         | 0.04%   |
| IBM                               | 2         | 0.04%   |
| Huawei Technologies               | 2         | 0.04%   |
| HMD Global                        | 2         | 0.04%   |
| Dell                              | 2         | 0.04%   |
| D-Link                            | 2         | 0.04%   |
| Chelsio Communications            | 2         | 0.04%   |
| American Megatrends               | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Sun Microsystems                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1577      | 32.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 289       | 5.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 270       | 5.57%   |
| Intel I211 Gigabit Network Connection                             | 160       | 3.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 128       | 2.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 105       | 2.16%   |
| Intel Ethernet Connection (2) I219-V                              | 95        | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 93        | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 61        | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 52        | 1.07%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48        | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 46        | 0.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 42        | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 41        | 0.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 41        | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 38        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 35        | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 33        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 29        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 29        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 29        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24        | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 21        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 21        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4417      | 53.68%  |
| WiFi     | 3753      | 45.61%  |
| Modem    | 46        | 0.56%   |
| Unknown  | 12        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2793      | 52.43%  |
| Ethernet | 2534      | 47.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2802      | 55.05%  |
| 1     | 1983      | 38.96%  |
| 3     | 149       | 2.93%   |
| 0     | 106       | 2.08%   |
| 4     | 29        | 0.57%   |
| 5     | 11        | 0.22%   |
| 6     | 6         | 0.12%   |
| 22    | 1         | 0.02%   |
| 21    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4427      | 86.31%  |
| Yes  | 702       | 13.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1401      | 47.67%  |
| Broadcom                        | 209       | 7.11%   |
| Qualcomm Atheros Communications | 196       | 6.67%   |
| Realtek Semiconductor           | 195       | 6.63%   |
| Apple                           | 165       | 5.61%   |
| Cambridge Silicon Radio         | 159       | 5.41%   |
| IMC Networks                    | 138       | 4.7%    |
| Lite-On Technology              | 124       | 4.22%   |
| ASUSTek Computer                | 83        | 2.82%   |
| Foxconn / Hon Hai               | 77        | 2.62%   |
| Dell                            | 41        | 1.4%    |
| Hewlett-Packard                 | 27        | 0.92%   |
| Marvell Semiconductor           | 19        | 0.65%   |
| Ralink                          | 15        | 0.51%   |
| Toshiba                         | 14        | 0.48%   |
| Dynex                           | 13        | 0.44%   |
| MediaTek                        | 11        | 0.37%   |
| Realtek                         | 8         | 0.27%   |
| Alps Electric                   | 7         | 0.24%   |
| TP-Link                         | 6         | 0.2%    |
| Logitech                        | 5         | 0.17%   |
| Micro Star International        | 4         | 0.14%   |
| Primax Electronics              | 3         | 0.1%    |
| Integrated System Solution      | 3         | 0.1%    |
| SINO WEALTH                     | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Zeevo                           | 1         | 0.03%   |
| USI                             | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Nintendo                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Foxconn International           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 508       | 17.26%  |
| Intel AX200 Bluetooth                                    | 244       | 8.29%   |
| Intel AX201 Bluetooth                                    | 197       | 6.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 159       | 5.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 152       | 5.16%   |
| Realtek Bluetooth Radio                                  | 132       | 4.49%   |
| Intel Wireless-AC 3168 Bluetooth                         | 92        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                       | 91        | 3.09%   |
| IMC Networks Bluetooth Radio                             | 74        | 2.51%   |
| Apple Bluetooth Host Controller                          | 74        | 2.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 57        | 1.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 56        | 1.9%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 55        | 1.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 46        | 1.56%   |
| Intel AX210 Bluetooth                                    | 41        | 1.39%   |
| Intel Bluetooth Device                                   | 40        | 1.36%   |
| Realtek  Bluetooth 4.2 Adapter                           | 38        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                       | 35        | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                         | 34        | 1.16%   |
| Apple Bluetooth USB Host Controller                      | 33        | 1.12%   |
| Apple Bluetooth HCI                                      | 33        | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 31        | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                              | 29        | 0.99%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 28        | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 26        | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 24        | 0.82%   |
| Lite-On Bluetooth Device                                 | 23        | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 21        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 20        | 0.68%   |
| IMC Networks Bluetooth Device                            | 19        | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 18        | 0.61%   |
| IMC Networks Wireless_Device                             | 17        | 0.58%   |
| Broadcom HP Portable SoftSailing                         | 17        | 0.58%   |
| Ralink RT3290 Bluetooth                                  | 15        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                        | 15        | 0.51%   |
| Marvell Bluetooth and Wireless LAN Composite             | 14        | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                         | 14        | 0.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 13        | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 13        | 0.44%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 13        | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3435      | 46.91%  |
| AMD                                  | 1662      | 22.7%   |
| Nvidia                               | 1329      | 18.15%  |
| C-Media Electronics                  | 155       | 2.12%   |
| Logitech                             | 80        | 1.09%   |
| Creative Labs                        | 59        | 0.81%   |
| Realtek Semiconductor                | 32        | 0.44%   |
| Corsair                              | 31        | 0.42%   |
| JMTek                                | 29        | 0.4%    |
| Texas Instruments                    | 26        | 0.36%   |
| Blue Microphones                     | 26        | 0.36%   |
| SteelSeries ApS                      | 23        | 0.31%   |
| Focusrite-Novation                   | 22        | 0.3%    |
| Creative Technology                  | 22        | 0.3%    |
| Razer USA                            | 21        | 0.29%   |
| ASUSTek Computer                     | 18        | 0.25%   |
| Plantronics                          | 17        | 0.23%   |
| Lenovo                               | 17        | 0.23%   |
| GN Netcom                            | 17        | 0.23%   |
| Kingston Technology                  | 16        | 0.22%   |
| GYROCOM C&C                          | 14        | 0.19%   |
| Samson Technologies                  | 13        | 0.18%   |
| Sony                                 | 12        | 0.16%   |
| Generalplus Technology               | 12        | 0.16%   |
| VIA Technologies                     | 9         | 0.12%   |
| M-Audio                              | 9         | 0.12%   |
| Dell                                 | 8         | 0.11%   |
| Micro Star International             | 7         | 0.1%    |
| FiiO Electronics Technology          | 7         | 0.1%    |
| Audio-Technica                       | 7         | 0.1%    |
| Yamaha                               | 6         | 0.08%   |
| XMOS                                 | 6         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.08%   |
| Tenx Technology                      | 6         | 0.08%   |
| SAVITECH                             | 6         | 0.08%   |
| Cambridge Silicon Radio              | 6         | 0.08%   |
| Bose                                 | 6         | 0.08%   |
| NAD Electronics                      | 5         | 0.07%   |
| Apple                                | 5         | 0.07%   |
| Sennheiser Communications            | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 368       | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 327       | 3.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 303       | 3.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 302       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 256       | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 248       | 2.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 244       | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 218       | 2.53%   |
| AMD FCH Azalia Controller                                                  | 205       | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 190       | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 183       | 2.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 181       | 2.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 148       | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 143       | 1.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 135       | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 133       | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 112       | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 107       | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 107       | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 107       | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 106       | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 102       | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 99        | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                   | 98        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 97        | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 93        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 87        | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 85        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                  | 84        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 79        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 79        | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 78        | 0.91%   |
| Intel Broadwell-U Audio Controller                                         | 78        | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 77        | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 72        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 71        | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                         | 69        | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 65        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 60        | 0.7%    |
| AMD Navi 10 HDMI Audio                                                     | 58        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 573       | 19.66%  |
| SK hynix                                         | 533       | 18.28%  |
| Kingston                                         | 354       | 12.14%  |
| Unknown                                          | 288       | 9.88%   |
| Micron Technology                                | 285       | 9.78%   |
| G.Skill                                          | 203       | 6.96%   |
| Corsair                                          | 180       | 6.17%   |
| Crucial                                          | 127       | 4.36%   |
| Elpida                                           | 57        | 1.96%   |
| Nanya Technology                                 | 56        | 1.92%   |
| Ramaxel Technology                               | 48        | 1.65%   |
| A-DATA Technology                                | 48        | 1.65%   |
| Patriot                                          | 29        | 0.99%   |
| Unknown                                          | 15        | 0.51%   |
| Team                                             | 13        | 0.45%   |
| Unknown (ABCD)                                   | 8         | 0.27%   |
| Unifosa                                          | 8         | 0.27%   |
| Transcend                                        | 8         | 0.27%   |
| Timetec                                          | 7         | 0.24%   |
| ASint Technology                                 | 7         | 0.24%   |
| Toshiba                                          | 6         | 0.21%   |
| Goldkey                                          | 4         | 0.14%   |
| Avant                                            | 4         | 0.14%   |
| Qimonda                                          | 3         | 0.1%    |
| PNY                                              | 3         | 0.1%    |
| OCZ                                              | 3         | 0.1%    |
| Neo Forza                                        | 3         | 0.1%    |
| CSX                                              | 3         | 0.1%    |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.07%   |
| SHARETRONIC                                      | 2         | 0.07%   |
| Sesame                                           | 2         | 0.07%   |
| Mushkin                                          | 2         | 0.07%   |
| Hewlett-Packard                                  | 2         | 0.07%   |
| ff                                               | 2         | 0.07%   |
| Axiom                                            | 2         | 0.07%   |
| Apacer                                           | 2         | 0.07%   |
| 4ea5                                             | 2         | 0.07%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.03%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.03%   |
| Unknown (0x0C26)                                 | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 31        | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.57%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 18        | 0.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 18        | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.51%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.47%   |
| Unknown                                                          | 15        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 12        | 0.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.38%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 0.35%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 11        | 0.35%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 10        | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.32%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 10        | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.32%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 9         | 0.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 9         | 0.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.28%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 8         | 0.25%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1067      | 43.01%  |
| DDR3    | 907       | 36.56%  |
| DDR2    | 146       | 5.88%   |
| LPDDR4  | 81        | 3.26%   |
| SDRAM   | 72        | 2.9%    |
| LPDDR3  | 70        | 2.82%   |
| Unknown | 65        | 2.62%   |
| DDR     | 32        | 1.29%   |
| DDR5    | 31        | 1.25%   |
| LPDDR5  | 8         | 0.32%   |
| DRAM    | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1206      | 49.14%  |
| DIMM         | 1063      | 43.32%  |
| Row Of Chips | 155       | 6.32%   |
| Chip         | 17        | 0.69%   |
| Unknown      | 10        | 0.41%   |
| FB-DIMM      | 3         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 997       | 36.28%  |
| 4096   | 774       | 28.17%  |
| 16384  | 391       | 14.23%  |
| 2048   | 380       | 13.83%  |
| 1024   | 119       | 4.33%   |
| 32768  | 72        | 2.62%   |
| 512    | 12        | 0.44%   |
| 129408 | 1         | 0.04%   |
| 65536  | 1         | 0.04%   |
| 256    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 553       | 20.38%  |
| 3200    | 319       | 11.76%  |
| 2667    | 315       | 11.61%  |
| 1333    | 239       | 8.81%   |
| 2400    | 194       | 7.15%   |
| 2133    | 138       | 5.09%   |
| 3600    | 93        | 3.43%   |
| 667     | 79        | 2.91%   |
| 1334    | 72        | 2.65%   |
| 800     | 71        | 2.62%   |
| 1867    | 64        | 2.36%   |
| 1067    | 47        | 1.73%   |
| Unknown | 39        | 1.44%   |
| 4267    | 38        | 1.4%    |
| 1066    | 37        | 1.36%   |
| 3266    | 27        | 1%      |
| 4800    | 22        | 0.81%   |
| 3733    | 22        | 0.81%   |
| 1866    | 22        | 0.81%   |
| 3400    | 20        | 0.74%   |
| 3866    | 19        | 0.7%    |
| 3800    | 19        | 0.7%    |
| 2666    | 19        | 0.7%    |
| 3466    | 17        | 0.63%   |
| 3000    | 16        | 0.59%   |
| 2933    | 15        | 0.55%   |
| 533     | 14        | 0.52%   |
| 6400    | 13        | 0.48%   |
| 4199    | 13        | 0.48%   |
| 8400    | 12        | 0.44%   |
| 4266    | 9         | 0.33%   |
| 975     | 9         | 0.33%   |
| 2800    | 8         | 0.29%   |
| 2048    | 8         | 0.29%   |
| 1639    | 8         | 0.29%   |
| 2465    | 7         | 0.26%   |
| 2000    | 7         | 0.26%   |
| 1800    | 7         | 0.26%   |
| 400     | 7         | 0.26%   |
| 3100    | 6         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Brother Industries       | 69        | 33.33%  |
| Hewlett-Packard          | 56        | 27.05%  |
| Samsung Electronics      | 31        | 14.98%  |
| Canon                    | 30        | 14.49%  |
| Seiko Epson              | 10        | 4.83%   |
| Lexmark International    | 3         | 1.45%   |
| Dymo-CoStar              | 3         | 1.45%   |
| Dell                     | 2         | 0.97%   |
| Zhuhai Poskey Technology | 1         | 0.48%   |
| Xerox                    | 1         | 0.48%   |
| Prolific Technology      | 1         | 0.48%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Brother Printer                      | 9         | 4.25%   |
| HP LaserJet 1018                     | 5         | 2.36%   |
| Brother HL-L2390DW                   | 5         | 2.36%   |
| Brother HL-L2320D series             | 5         | 2.36%   |
| Seiko Epson ET-3750 Series           | 4         | 1.89%   |
| HP LaserJet 1020                     | 4         | 1.89%   |
| Brother HL-5370DW series             | 4         | 1.89%   |
| Samsung ML-216x Series Laser Printer | 3         | 1.42%   |
| Samsung ML-1670 Series               | 3         | 1.42%   |
| Samsung M267x 287x Series            | 3         | 1.42%   |
| HP LaserJet 4250                     | 3         | 1.42%   |
| HP ENVY 4520 series                  | 3         | 1.42%   |
| HP DeskJet 3630 series               | 3         | 1.42%   |
| HP DeskJet 2600 series               | 3         | 1.42%   |
| Canon PIXMA MX920 Series             | 3         | 1.42%   |
| Canon PIXMA MG2900 Series            | 3         | 1.42%   |
| Brother MFC-J480DW                   | 3         | 1.42%   |
| Brother MFC-9130CW                   | 3         | 1.42%   |
| Brother HL-L2360D series             | 3         | 1.42%   |
| Brother HL-2270DW Laser Printer      | 3         | 1.42%   |
| Brother DCP-L2540DW                  | 3         | 1.42%   |
| Seiko Epson WF-3520 Series           | 2         | 0.94%   |
| Samsung ML-1660 Series               | 2         | 0.94%   |
| Samsung M2070 Series                 | 2         | 0.94%   |
| Samsung M2020 Series                 | 2         | 0.94%   |
| Samsung CLP-310 Color Laser Printer  | 2         | 0.94%   |
| Samsung C460 Series                  | 2         | 0.94%   |
| HP OfficeJet 3830 series             | 2         | 0.94%   |
| HP LaserJet Pro M202dw               | 2         | 0.94%   |
| HP LaserJet M101-M106                | 2         | 0.94%   |
| HP DeskJet 3700 series               | 2         | 0.94%   |
| Dymo-CoStar LabelWriter 450          | 2         | 0.94%   |
| Canon PIXMA MX530 Series             | 2         | 0.94%   |
| Canon MG2100 series                  | 2         | 0.94%   |
| Canon MF4410                         | 2         | 0.94%   |
| Canon MF3010                         | 2         | 0.94%   |
| Brother MFC-J485DW                   | 2         | 0.94%   |
| Brother MFC-9330CDW                  | 2         | 0.94%   |
| Brother HL-L3290CDW series           | 2         | 0.94%   |
| Brother HL-2140 series               | 2         | 0.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 19        | 59.38%  |
| Hewlett-Packard | 8         | 25%     |
| Seiko Epson     | 5         | 15.63%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 700F                                | 4         | 12.5%   |
| Canon CanoScan LiDE 220                                 | 4         | 12.5%   |
| Canon CanoScan LiDE 210                                 | 4         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 3.13%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.13%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1         | 3.13%   |
| HP ScanJet G4050                                        | 1         | 3.13%   |
| HP ScanJet G4010                                        | 1         | 3.13%   |
| HP ScanJet 82x0C                                        | 1         | 3.13%   |
| HP ScanJet 5590                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                        | 1         | 3.13%   |
| HP ScanJet 3670                                         | 1         | 3.13%   |
| HP ScanJet 3400cse                                      | 1         | 3.13%   |
| HP ScanJet 2200c                                        | 1         | 3.13%   |
| Canon CanoScan LiDE 70                                  | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 3.13%   |
| Canon CanoScan LiDE 200                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 110                                 | 1         | 3.13%   |
| Canon CanoScan 4200F                                    | 1         | 3.13%   |
| Canon CanoScan                                          | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 530       | 19.22%  |
| Microdia                               | 285       | 10.33%  |
| Logitech                               | 260       | 9.43%   |
| IMC Networks                           | 226       | 8.19%   |
| Realtek Semiconductor                  | 192       | 6.96%   |
| Apple                                  | 167       | 6.06%   |
| Acer                                   | 151       | 5.47%   |
| Sunplus Innovation Technology          | 145       | 5.26%   |
| Suyin                                  | 94        | 3.41%   |
| Quanta                                 | 93        | 3.37%   |
| Microsoft                              | 74        | 2.68%   |
| Cheng Uei Precision Industry (Foxlink) | 65        | 2.36%   |
| Syntek                                 | 38        | 1.38%   |
| Samsung Electronics                    | 36        | 1.31%   |
| Lite-On Technology                     | 36        | 1.31%   |
| Bison Electronics                      | 31        | 1.12%   |
| Ricoh                                  | 29        | 1.05%   |
| Silicon Motion                         | 28        | 1.02%   |
| Luxvisions Innotech Limited            | 27        | 0.98%   |
| Lenovo                                 | 23        | 0.83%   |
| Importek                               | 19        | 0.69%   |
| Z-Star Microelectronics                | 16        | 0.58%   |
| AVerMedia Technologies                 | 15        | 0.54%   |
| MacroSilicon                           | 14        | 0.51%   |
| Alcor Micro                            | 14        | 0.51%   |
| OmniVision Technologies                | 9         | 0.33%   |
| ALi                                    | 9         | 0.33%   |
| Sonix Technology                       | 8         | 0.29%   |
| Cubeternet                             | 8         | 0.29%   |
| Primax Electronics                     | 7         | 0.25%   |
| LG Electronics                         | 7         | 0.25%   |
| Creative Technology                    | 7         | 0.25%   |
| webcam                                 | 6         | 0.22%   |
| Generalplus Technology                 | 6         | 0.22%   |
| Razer USA                              | 5         | 0.18%   |
| Huawei Technologies                    | 5         | 0.18%   |
| Hewlett-Packard                        | 5         | 0.18%   |
| Genesys Logic                          | 5         | 0.18%   |
| YGTek                                  | 4         | 0.15%   |
| Canon                                  | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 117       | 4.21%   |
| Microdia Integrated_Webcam_HD        | 107       | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam    | 82        | 2.95%   |
| Realtek Integrated_Webcam_HD         | 75        | 2.7%    |
| Apple Built-in iSight                | 60        | 2.16%   |
| Logitech HD Pro Webcam C920          | 57        | 2.05%   |
| Logitech Webcam C270                 | 54        | 1.94%   |
| Chicony HD WebCam                    | 48        | 1.73%   |
| IMC Networks Integrated Camera       | 47        | 1.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X      | 47        | 1.69%   |
| Acer Integrated Camera               | 38        | 1.37%   |
| Samsung Galaxy A5 (MTP)              | 36        | 1.29%   |
| Sunplus Integrated_Webcam_HD         | 33        | 1.19%   |
| Microdia Integrated Webcam           | 32        | 1.15%   |
| Apple FaceTime HD Camera (Built-in)  | 32        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 29        | 1.04%   |
| Syntek Integrated Camera             | 27        | 0.97%   |
| Sunplus HD WebCam                    | 24        | 0.86%   |
| Microdia Webcam Vitade AF            | 24        | 0.86%   |
| Microdia USB 2.0 Camera              | 23        | 0.83%   |
| Logitech C922 Pro Stream Webcam      | 23        | 0.83%   |
| Apple FaceTime HD Camera             | 23        | 0.83%   |
| Microsoft LifeCam HD-3000            | 22        | 0.79%   |
| Chicony VGA WebCam                   | 22        | 0.79%   |
| Chicony HP Truevision HD             | 20        | 0.72%   |
| Acer Lenovo EasyCamera               | 19        | 0.68%   |
| Acer HD Webcam                       | 19        | 0.68%   |
| Quanta VGA WebCam                    | 18        | 0.65%   |
| Lite-On Integrated Camera            | 18        | 0.65%   |
| Chicony USB2.0 HD UVC WebCam         | 18        | 0.65%   |
| Quanta HD User Facing                | 16        | 0.58%   |
| Chicony USB 2.0 Camera               | 16        | 0.58%   |
| Realtek USB Camera                   | 15        | 0.54%   |
| Quanta HP TrueVision HD Camera       | 15        | 0.54%   |
| Chicony HP HD Camera                 | 15        | 0.54%   |
| Acer SunplusIT Integrated Camera     | 15        | 0.54%   |
| Chicony TOSHIBA Web Camera - HD      | 14        | 0.5%    |
| Chicony HD User Facing               | 14        | 0.5%    |
| Microdia Laptop_Integrated_Webcam_HD | 13        | 0.47%   |
| MacroSilicon USB Video               | 13        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 190       | 37.48%  |
| Synaptics                          | 118       | 23.27%  |
| Shenzhen Goodix Technology         | 48        | 9.47%   |
| Elan Microelectronics              | 37        | 7.3%    |
| Upek                               | 34        | 6.71%   |
| AuthenTec                          | 31        | 6.11%   |
| LighTuning Technology              | 23        | 4.54%   |
| STMicroelectronics                 | 16        | 3.16%   |
| Focal-systems.Corp                 | 3         | 0.59%   |
| Samsung Electronics                | 2         | 0.39%   |
| Microsoft                          | 2         | 0.39%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.2%    |
| HOLTEK                             | 1         | 0.2%    |
| Dell                               | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 8.68%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 6.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 6.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 6.11%   |
| Elan ELAN:Fingerprint                                                      | 30        | 5.92%   |
| Validity Sensors Synaptics WBDI                                            | 23        | 4.54%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.54%   |
| Shenzhen Goodix FingerPrint                                                | 23        | 4.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 3.75%   |
| Validity Sensors VFS491                                                    | 18        | 3.55%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 3.16%   |
| AuthenTec AES2810                                                          | 14        | 2.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 2.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 2.37%   |
| Synaptics  WBDI                                                            | 12        | 2.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 2.37%   |
| Synaptics WBDI                                                             | 11        | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.17%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.78%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 1.58%   |
| Synaptics UWP WBDI                                                         | 8         | 1.58%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.58%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 1.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.18%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.18%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.18%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.99%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.99%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.59%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 0.59%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.59%   |
| AuthenTec AES1600                                                          | 3         | 0.59%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.39%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.39%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.39%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 83        | 43.46%  |
| Alcor Micro               | 36        | 18.85%  |
| O2 Micro                  | 25        | 13.09%  |
| Upek                      | 22        | 11.52%  |
| Lenovo                    | 12        | 6.28%   |
| Gemalto (was Gemplus)     | 4         | 2.09%   |
| Yubico.com                | 2         | 1.05%   |
| SCM Microsystems          | 2         | 1.05%   |
| Aladdin Knowledge Systems | 2         | 1.05%   |
| In Focus Systems          | 1         | 0.52%   |
| Giesecke & Devrient       | 1         | 0.52%   |
| Clay Logic                | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 46        | 24.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 17.8%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 11.52%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.99%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 8.9%    |
| Broadcom 5880                                                                | 13        | 6.81%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 6.28%   |
| Broadcom 58200                                                               | 6         | 3.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.09%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 2.09%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.05%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.05%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.52%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.52%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.52%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.52%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.52%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.52%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3666      | 70.58%  |
| 1     | 1221      | 23.51%  |
| 2     | 251       | 4.83%   |
| 3     | 36        | 0.69%   |
| 4     | 11        | 0.21%   |
| 5     | 5         | 0.1%    |
| 8     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 499       | 27.3%   |
| Graphics card            | 412       | 22.54%  |
| Net/wireless             | 265       | 14.5%   |
| Chipcard                 | 175       | 9.57%   |
| Communication controller | 107       | 5.85%   |
| Multimedia controller    | 93        | 5.09%   |
| Unassigned class         | 42        | 2.3%    |
| Bluetooth                | 38        | 2.08%   |
| Camera                   | 33        | 1.81%   |
| Storage                  | 32        | 1.75%   |
| Sound                    | 32        | 1.75%   |
| Net/ethernet             | 26        | 1.42%   |
| Network                  | 15        | 0.82%   |
| Modem                    | 11        | 0.6%    |
| Card reader              | 9         | 0.49%   |
| Dvb card                 | 8         | 0.44%   |
| Storage/raid             | 7         | 0.38%   |
| Storage/ide              | 7         | 0.38%   |
| Firewire controller      | 7         | 0.38%   |
| Flash memory             | 4         | 0.22%   |
| Tv card                  | 2         | 0.11%   |
| Video                    | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |


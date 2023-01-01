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

Total: 7332

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| MSI           | GF75 Thin 9SC               | Notebook    | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | Notebook    | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [4aafb7e858](https://linux-hardware.org/?probe=4aafb7e858) | Nov 29, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [e473c1c45c](https://linux-hardware.org/?probe=e473c1c45c) | Nov 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [cc75562371](https://linux-hardware.org/?probe=cc75562371) | Nov 29, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [c52689296b](https://linux-hardware.org/?probe=c52689296b) | Nov 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [a6ea0d5259](https://linux-hardware.org/?probe=a6ea0d5259) | Nov 29, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [66525e5501](https://linux-hardware.org/?probe=66525e5501) | Nov 29, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6d711e74c3](https://linux-hardware.org/?probe=6d711e74c3) | Nov 28, 2022 |
| Dell          | Latitude 7480               | Notebook    | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f038c3cc67](https://linux-hardware.org/?probe=f038c3cc67) | Nov 28, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [7f9d229259](https://linux-hardware.org/?probe=7f9d229259) | Nov 28, 2022 |
| Dell          | 09WH54 A00                  | Desktop     | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0149d91a8d](https://linux-hardware.org/?probe=0149d91a8d) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| HP            | 212B                        | Desktop     | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [cbd36eefe1](https://linux-hardware.org/?probe=cbd36eefe1) | Nov 27, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [508e04de6e](https://linux-hardware.org/?probe=508e04de6e) | Nov 27, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [fada18bff7](https://linux-hardware.org/?probe=fada18bff7) | Nov 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5d04cf0f9](https://linux-hardware.org/?probe=d5d04cf0f9) | Nov 26, 2022 |
| HP            | 18E4                        | Desktop     | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f76927c5ef](https://linux-hardware.org/?probe=f76927c5ef) | Nov 26, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [2734591eb0](https://linux-hardware.org/?probe=2734591eb0) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [26bfa13122](https://linux-hardware.org/?probe=26bfa13122) | Nov 25, 2022 |
| Sony          | VGN-NS110E                  | Notebook    | [5ccfd5f230](https://linux-hardware.org/?probe=5ccfd5f230) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | Desktop     | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Sony          | VGN-NS110E                  | Notebook    | [999e5f4ed6](https://linux-hardware.org/?probe=999e5f4ed6) | Nov 25, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [eb243079e8](https://linux-hardware.org/?probe=eb243079e8) | Nov 25, 2022 |
| HP            | 18E4                        | Desktop     | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [575f0a8c5a](https://linux-hardware.org/?probe=575f0a8c5a) | Nov 24, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [581cd43952](https://linux-hardware.org/?probe=581cd43952) | Nov 24, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [95ebdc23ea](https://linux-hardware.org/?probe=95ebdc23ea) | Nov 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1986287453](https://linux-hardware.org/?probe=1986287453) | Nov 24, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [344721473a](https://linux-hardware.org/?probe=344721473a) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [4f6911ae2c](https://linux-hardware.org/?probe=4f6911ae2c) | Nov 23, 2022 |
| Dell          | Latitude E6530              | Notebook    | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [96e8bf5249](https://linux-hardware.org/?probe=96e8bf5249) | Nov 23, 2022 |
| HP            | 339A                        | Desktop     | [13c1a4b520](https://linux-hardware.org/?probe=13c1a4b520) | Nov 23, 2022 |
| Toshiba       | PORTEGE R930                | Notebook    | [9e5d02ab88](https://linux-hardware.org/?probe=9e5d02ab88) | Nov 23, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | Notebook    | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| AZW           | BT3 PRO                     | Notebook    | [ee8fc8db42](https://linux-hardware.org/?probe=ee8fc8db42) | Nov 22, 2022 |
| AZW           | BT3 PRO                     | Notebook    | [48047be395](https://linux-hardware.org/?probe=48047be395) | Nov 21, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [5360c65b7a](https://linux-hardware.org/?probe=5360c65b7a) | Nov 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [489592e334](https://linux-hardware.org/?probe=489592e334) | Nov 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5c1c053b03](https://linux-hardware.org/?probe=5c1c053b03) | Nov 21, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [66f37717f6](https://linux-hardware.org/?probe=66f37717f6) | Nov 21, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [d7f34b8543](https://linux-hardware.org/?probe=d7f34b8543) | Nov 21, 2022 |
| HP            | 18E4                        | Desktop     | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [150565ed00](https://linux-hardware.org/?probe=150565ed00) | Nov 20, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [0f231b600d](https://linux-hardware.org/?probe=0f231b600d) | Nov 20, 2022 |
| Dell          | Latitude 5285               | Notebook    | [145341899a](https://linux-hardware.org/?probe=145341899a) | Nov 20, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [ad20223c29](https://linux-hardware.org/?probe=ad20223c29) | Nov 20, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [7a475c6f79](https://linux-hardware.org/?probe=7a475c6f79) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7ac338ce0d](https://linux-hardware.org/?probe=7ac338ce0d) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [50bd30f30d](https://linux-hardware.org/?probe=50bd30f30d) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480 20L6S09E00    | Notebook    | [cd7fb0289f](https://linux-hardware.org/?probe=cd7fb0289f) | Nov 19, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [6fb901efa3](https://linux-hardware.org/?probe=6fb901efa3) | Nov 19, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [ea98e803d1](https://linux-hardware.org/?probe=ea98e803d1) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [da04bee118](https://linux-hardware.org/?probe=da04bee118) | Nov 18, 2022 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [42f0e4b33e](https://linux-hardware.org/?probe=42f0e4b33e) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| Alienware     | m17                         | Notebook    | [e3e14a271a](https://linux-hardware.org/?probe=e3e14a271a) | Nov 17, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [f85255857d](https://linux-hardware.org/?probe=f85255857d) | Nov 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [01810a4098](https://linux-hardware.org/?probe=01810a4098) | Nov 17, 2022 |
| HP            | 18E4                        | Desktop     | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [5648565f20](https://linux-hardware.org/?probe=5648565f20) | Nov 17, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [7c530443f0](https://linux-hardware.org/?probe=7c530443f0) | Nov 17, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b21e07c887](https://linux-hardware.org/?probe=b21e07c887) | Nov 16, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [39aedb7818](https://linux-hardware.org/?probe=39aedb7818) | Nov 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ba362db69a](https://linux-hardware.org/?probe=ba362db69a) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| MSI           | 870-G45                     | Desktop     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [d0bcf66bd1](https://linux-hardware.org/?probe=d0bcf66bd1) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e6c94e04c](https://linux-hardware.org/?probe=5e6c94e04c) | Nov 15, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [4c5b1fed6f](https://linux-hardware.org/?probe=4c5b1fed6f) | Nov 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| Alienware     | m17                         | Notebook    | [4140c68e95](https://linux-hardware.org/?probe=4140c68e95) | Nov 15, 2022 |
| Dell          | 0RY007                      | Desktop     | [84453b7c4b](https://linux-hardware.org/?probe=84453b7c4b) | Nov 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [5fa04fae9e](https://linux-hardware.org/?probe=5fa04fae9e) | Nov 15, 2022 |
| Dell          | 0RY007                      | Desktop     | [dc49babf5c](https://linux-hardware.org/?probe=dc49babf5c) | Nov 15, 2022 |
| Razer         | Blade Stealth               | Notebook    | [52ac7c7393](https://linux-hardware.org/?probe=52ac7c7393) | Nov 14, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6f8078d5ec](https://linux-hardware.org/?probe=6f8078d5ec) | Nov 14, 2022 |
| Acer          | E1-532P                     | Notebook    | [1e666341f7](https://linux-hardware.org/?probe=1e666341f7) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [1485faa2cc](https://linux-hardware.org/?probe=1485faa2cc) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [80cce966ce](https://linux-hardware.org/?probe=80cce966ce) | Nov 14, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [25df2f9dc5](https://linux-hardware.org/?probe=25df2f9dc5) | Nov 14, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [970f0b9990](https://linux-hardware.org/?probe=970f0b9990) | Nov 13, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [c8b868a9b2](https://linux-hardware.org/?probe=c8b868a9b2) | Nov 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [4788a2a91d](https://linux-hardware.org/?probe=4788a2a91d) | Nov 13, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [18b42b8ead](https://linux-hardware.org/?probe=18b42b8ead) | Nov 13, 2022 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [575d67b22c](https://linux-hardware.org/?probe=575d67b22c) | Nov 13, 2022 |
| HP            | 18E4                        | Desktop     | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [2d2cdbb40b](https://linux-hardware.org/?probe=2d2cdbb40b) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [632037506d](https://linux-hardware.org/?probe=632037506d) | Nov 12, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8d1eaa5bf0](https://linux-hardware.org/?probe=8d1eaa5bf0) | Nov 10, 2022 |
| Google        | Droid                       | Notebook    | [e73c485f75](https://linux-hardware.org/?probe=e73c485f75) | Nov 10, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [94c1e12b90](https://linux-hardware.org/?probe=94c1e12b90) | Nov 09, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [431acad421](https://linux-hardware.org/?probe=431acad421) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [d8638412d9](https://linux-hardware.org/?probe=d8638412d9) | Nov 09, 2022 |
| Google        | Cyan                        | Notebook    | [814cdea7b3](https://linux-hardware.org/?probe=814cdea7b3) | Nov 08, 2022 |
| AZW           | Gemini T34                  | Desktop     | [b8aee41f46](https://linux-hardware.org/?probe=b8aee41f46) | Nov 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [be28c34da3](https://linux-hardware.org/?probe=be28c34da3) | Nov 07, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f0e91578b7](https://linux-hardware.org/?probe=f0e91578b7) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [a1d8f7bbca](https://linux-hardware.org/?probe=a1d8f7bbca) | Nov 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f18ccfd249](https://linux-hardware.org/?probe=f18ccfd249) | Nov 07, 2022 |
| HP            | ENVY 17                     | Notebook    | [83906ebbfc](https://linux-hardware.org/?probe=83906ebbfc) | Nov 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3febd144a4](https://linux-hardware.org/?probe=3febd144a4) | Nov 07, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [5cee459a0f](https://linux-hardware.org/?probe=5cee459a0f) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [caf9066e2a](https://linux-hardware.org/?probe=caf9066e2a) | Nov 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d137598aff](https://linux-hardware.org/?probe=d137598aff) | Nov 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [4f7462e06e](https://linux-hardware.org/?probe=4f7462e06e) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | Desktop     | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [fab8493ac2](https://linux-hardware.org/?probe=fab8493ac2) | Nov 04, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [a2362fefe3](https://linux-hardware.org/?probe=a2362fefe3) | Nov 04, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6491b1d525](https://linux-hardware.org/?probe=6491b1d525) | Nov 04, 2022 |
| HP            | 18E4                        | Desktop     | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| Dell          | G3 3590                     | Notebook    | [03fec4f4d4](https://linux-hardware.org/?probe=03fec4f4d4) | Nov 04, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| MSI           | 870-G45                     | Desktop     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ab0a9cd47d](https://linux-hardware.org/?probe=ab0a9cd47d) | Nov 03, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7255a61579](https://linux-hardware.org/?probe=7255a61579) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [608c7f56e6](https://linux-hardware.org/?probe=608c7f56e6) | Nov 03, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [953e399168](https://linux-hardware.org/?probe=953e399168) | Nov 03, 2022 |
| ASRock        | Z270 Taichi                 | Desktop     | [60996cd2dc](https://linux-hardware.org/?probe=60996cd2dc) | Nov 02, 2022 |
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [fde67e1423](https://linux-hardware.org/?probe=fde67e1423) | Nov 02, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | 8054                        | Desktop     | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [18db43ffed](https://linux-hardware.org/?probe=18db43ffed) | Oct 31, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-201        | Desktop     | [b3403874f4](https://linux-hardware.org/?probe=b3403874f4) | Oct 31, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [dfdf6532b6](https://linux-hardware.org/?probe=dfdf6532b6) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [296d9a0f38](https://linux-hardware.org/?probe=296d9a0f38) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [07a165b373](https://linux-hardware.org/?probe=07a165b373) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [54c64976ee](https://linux-hardware.org/?probe=54c64976ee) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [768d0e85c9](https://linux-hardware.org/?probe=768d0e85c9) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [91f4cd151f](https://linux-hardware.org/?probe=91f4cd151f) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| HP            | 18E4                        | Desktop     | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| Acer          | Aspire TC-710 V:1.1         | Desktop     | [b9c0f59afa](https://linux-hardware.org/?probe=b9c0f59afa) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| HP            | G60                         | Notebook    | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [2829b0b18f](https://linux-hardware.org/?probe=2829b0b18f) | Oct 28, 2022 |
| Acer          | AOD257                      | Notebook    | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Acer          | AOD257                      | Notebook    | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [f3c9ea3e12](https://linux-hardware.org/?probe=f3c9ea3e12) | Oct 27, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ddfefe06a3](https://linux-hardware.org/?probe=ddfefe06a3) | Oct 27, 2022 |
| Oracle        | ASSY,MOTHERBOARD,1U         | Server      | [fec3d1a36e](https://linux-hardware.org/?probe=fec3d1a36e) | Oct 27, 2022 |
| Oracle        | ASSY,MB,X4-2, 1U            | Server      | [4622ac730a](https://linux-hardware.org/?probe=4622ac730a) | Oct 26, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [6faf6b40b1](https://linux-hardware.org/?probe=6faf6b40b1) | Oct 26, 2022 |
| Dell          | Precision 5570              | Notebook    | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [c19eaa0502](https://linux-hardware.org/?probe=c19eaa0502) | Oct 26, 2022 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [126f440ca7](https://linux-hardware.org/?probe=126f440ca7) | Oct 26, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [07d56a833e](https://linux-hardware.org/?probe=07d56a833e) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ce143b473f](https://linux-hardware.org/?probe=ce143b473f) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [9312be9510](https://linux-hardware.org/?probe=9312be9510) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | Desktop     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [33bef6bb6f](https://linux-hardware.org/?probe=33bef6bb6f) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [da114c9e74](https://linux-hardware.org/?probe=da114c9e74) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [77bbf74390](https://linux-hardware.org/?probe=77bbf74390) | Oct 22, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [acbf2e94c1](https://linux-hardware.org/?probe=acbf2e94c1) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [66fae864f2](https://linux-hardware.org/?probe=66fae864f2) | Oct 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2a02bdc30d](https://linux-hardware.org/?probe=2a02bdc30d) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eaff8befe8](https://linux-hardware.org/?probe=eaff8befe8) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9042357a86](https://linux-hardware.org/?probe=9042357a86) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| Sony          | VPCEH3QFX                   | Notebook    | [def39e1ddd](https://linux-hardware.org/?probe=def39e1ddd) | Oct 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [21d541f98a](https://linux-hardware.org/?probe=21d541f98a) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [bfdfd5d11e](https://linux-hardware.org/?probe=bfdfd5d11e) | Oct 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ccc97b1211](https://linux-hardware.org/?probe=ccc97b1211) | Oct 21, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0312fb4d88](https://linux-hardware.org/?probe=0312fb4d88) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [837845f259](https://linux-hardware.org/?probe=837845f259) | Oct 20, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [9485d1e744](https://linux-hardware.org/?probe=9485d1e744) | Oct 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [33a4634aab](https://linux-hardware.org/?probe=33a4634aab) | Oct 20, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [b27ee147cf](https://linux-hardware.org/?probe=b27ee147cf) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6be0c6ee5f](https://linux-hardware.org/?probe=6be0c6ee5f) | Oct 20, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [a753c7bd58](https://linux-hardware.org/?probe=a753c7bd58) | Oct 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8105425af8](https://linux-hardware.org/?probe=8105425af8) | Oct 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1f8284bf7d](https://linux-hardware.org/?probe=1f8284bf7d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6271fbb0fb](https://linux-hardware.org/?probe=6271fbb0fb) | Oct 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8dd98e14a1](https://linux-hardware.org/?probe=8dd98e14a1) | Oct 19, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [f275b2167f](https://linux-hardware.org/?probe=f275b2167f) | Oct 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [3c91e0c6ec](https://linux-hardware.org/?probe=3c91e0c6ec) | Oct 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e000a30c5](https://linux-hardware.org/?probe=1e000a30c5) | Oct 18, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| Acer          | Spin SP513-52N              | Convertible | [465c32fbf8](https://linux-hardware.org/?probe=465c32fbf8) | Oct 18, 2022 |
| Acer          | Aspire one                  | Notebook    | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [9fb7d8bf7f](https://linux-hardware.org/?probe=9fb7d8bf7f) | Oct 17, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [ac8367f142](https://linux-hardware.org/?probe=ac8367f142) | Oct 17, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [8c187fa369](https://linux-hardware.org/?probe=8c187fa369) | Oct 17, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [def45e1980](https://linux-hardware.org/?probe=def45e1980) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [63f9315478](https://linux-hardware.org/?probe=63f9315478) | Oct 16, 2022 |
| Google        | Coral                       | Notebook    | [a1811601a0](https://linux-hardware.org/?probe=a1811601a0) | Oct 15, 2022 |
| Google        | Coral                       | Notebook    | [93a674ea2b](https://linux-hardware.org/?probe=93a674ea2b) | Oct 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [beb41f73d2](https://linux-hardware.org/?probe=beb41f73d2) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [7d6c345f35](https://linux-hardware.org/?probe=7d6c345f35) | Oct 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3a6855c328](https://linux-hardware.org/?probe=3a6855c328) | Oct 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS4U300    | Notebook    | [bcdea92f5d](https://linux-hardware.org/?probe=bcdea92f5d) | Oct 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS4U300    | Notebook    | [1a5aa81d1a](https://linux-hardware.org/?probe=1a5aa81d1a) | Oct 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [3f4c203116](https://linux-hardware.org/?probe=3f4c203116) | Oct 15, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d38b191e7](https://linux-hardware.org/?probe=2d38b191e7) | Oct 14, 2022 |
| HP            | 2B5B                        | Desktop     | [fc24a4bc99](https://linux-hardware.org/?probe=fc24a4bc99) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2fb7882f4a](https://linux-hardware.org/?probe=2fb7882f4a) | Oct 14, 2022 |
| Dell          | Latitude E6400              | Notebook    | [3516901ea0](https://linux-hardware.org/?probe=3516901ea0) | Oct 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [76678b6d58](https://linux-hardware.org/?probe=76678b6d58) | Oct 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4a4b8d42fc](https://linux-hardware.org/?probe=4a4b8d42fc) | Oct 13, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [9c9ad77c56](https://linux-hardware.org/?probe=9c9ad77c56) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| ASUSTek       | K53E                        | Notebook    | [ee3acd2da1](https://linux-hardware.org/?probe=ee3acd2da1) | Oct 11, 2022 |
| ASUSTek       | K53E                        | Notebook    | [8a8058467a](https://linux-hardware.org/?probe=8a8058467a) | Oct 11, 2022 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [89ee3db150](https://linux-hardware.org/?probe=89ee3db150) | Oct 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Alienware     | Area-51m                    | Notebook    | [a227d548e4](https://linux-hardware.org/?probe=a227d548e4) | Oct 11, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c69cf9f20a](https://linux-hardware.org/?probe=c69cf9f20a) | Oct 11, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d96c361919](https://linux-hardware.org/?probe=d96c361919) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [eca505496f](https://linux-hardware.org/?probe=eca505496f) | Oct 10, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [669c570a2e](https://linux-hardware.org/?probe=669c570a2e) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [b8e434e4db](https://linux-hardware.org/?probe=b8e434e4db) | Oct 10, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [8315e5ed7d](https://linux-hardware.org/?probe=8315e5ed7d) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| HP            | 18E4                        | Desktop     | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [c2193db5fb](https://linux-hardware.org/?probe=c2193db5fb) | Oct 09, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [0709f63ca7](https://linux-hardware.org/?probe=0709f63ca7) | Oct 09, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [67256f654b](https://linux-hardware.org/?probe=67256f654b) | Oct 08, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [dfeb0c2791](https://linux-hardware.org/?probe=dfeb0c2791) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | Desktop     | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [60c519a7dd](https://linux-hardware.org/?probe=60c519a7dd) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b7c6acd46c](https://linux-hardware.org/?probe=b7c6acd46c) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [b31ac1623d](https://linux-hardware.org/?probe=b31ac1623d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [9eaff58099](https://linux-hardware.org/?probe=9eaff58099) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c4888023c3](https://linux-hardware.org/?probe=c4888023c3) | Oct 04, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Dell          | 082WXT A03                  | Desktop     | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [4e56098080](https://linux-hardware.org/?probe=4e56098080) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bc437ef3d](https://linux-hardware.org/?probe=6bc437ef3d) | Oct 03, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1f77699521](https://linux-hardware.org/?probe=1f77699521) | Oct 03, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [56fbace4f2](https://linux-hardware.org/?probe=56fbace4f2) | Oct 03, 2022 |
| Google        | Droid                       | Notebook    | [40550baeb8](https://linux-hardware.org/?probe=40550baeb8) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [5c5353c8b6](https://linux-hardware.org/?probe=5c5353c8b6) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [5077b42a8b](https://linux-hardware.org/?probe=5077b42a8b) | Oct 01, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [c92633e1ee](https://linux-hardware.org/?probe=c92633e1ee) | Oct 01, 2022 |
| Dell          | Latitude E4300              | Notebook    | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | Notebook    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [f9cf849f23](https://linux-hardware.org/?probe=f9cf849f23) | Sep 30, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [6cf53adb30](https://linux-hardware.org/?probe=6cf53adb30) | Sep 30, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| HP            | 3398                        | Desktop     | [2f7b1d28b4](https://linux-hardware.org/?probe=2f7b1d28b4) | Sep 30, 2022 |
| HP            | 1496                        | Desktop     | [e89f06542b](https://linux-hardware.org/?probe=e89f06542b) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [aa0eeeda6b](https://linux-hardware.org/?probe=aa0eeeda6b) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Acer          | Veriton X6610G              | Desktop     | [66733e59e2](https://linux-hardware.org/?probe=66733e59e2) | Sep 29, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [75c8af47c2](https://linux-hardware.org/?probe=75c8af47c2) | Sep 29, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f3e5e0005d](https://linux-hardware.org/?probe=f3e5e0005d) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [fe6539c021](https://linux-hardware.org/?probe=fe6539c021) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | Notebook    | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [8086625f5a](https://linux-hardware.org/?probe=8086625f5a) | Sep 28, 2022 |
| HP            | 212B                        | Desktop     | [38aa6e5478](https://linux-hardware.org/?probe=38aa6e5478) | Sep 28, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc3501546b](https://linux-hardware.org/?probe=bc3501546b) | Sep 28, 2022 |
| Dell          | 01V648 A06                  | Server      | [209c9b938c](https://linux-hardware.org/?probe=209c9b938c) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [e5405dd3d8](https://linux-hardware.org/?probe=e5405dd3d8) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [ac96a56edf](https://linux-hardware.org/?probe=ac96a56edf) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [45031620df](https://linux-hardware.org/?probe=45031620df) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [a9ac678198](https://linux-hardware.org/?probe=a9ac678198) | Sep 26, 2022 |
| ASUSTek       | K52N                        | Notebook    | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| MSI           | GE75 Raider 8SF             | Notebook    | [094a9b115b](https://linux-hardware.org/?probe=094a9b115b) | Sep 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [9a7ec70bad](https://linux-hardware.org/?probe=9a7ec70bad) | Sep 25, 2022 |
| Dell          | Inspiron 1440               | Notebook    | [c928a944c0](https://linux-hardware.org/?probe=c928a944c0) | Sep 24, 2022 |
| Gateway       | IPISB-VR                    | Desktop     | [21ee50eb69](https://linux-hardware.org/?probe=21ee50eb69) | Sep 24, 2022 |
| Dell          | Latitude E5510              | Notebook    | [04f4e9a803](https://linux-hardware.org/?probe=04f4e9a803) | Sep 24, 2022 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [405ea9a4ca](https://linux-hardware.org/?probe=405ea9a4ca) | Sep 24, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| Lenovo        | ThinkPad T61p 64575KU       | Notebook    | [a5e3ca7c25](https://linux-hardware.org/?probe=a5e3ca7c25) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| MSI           | 870-G45                     | Desktop     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| HP            | 8309                        | Desktop     | [118f235878](https://linux-hardware.org/?probe=118f235878) | Sep 22, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [fb1cce613c](https://linux-hardware.org/?probe=fb1cce613c) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [58b83fee74](https://linux-hardware.org/?probe=58b83fee74) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [920bf9a750](https://linux-hardware.org/?probe=920bf9a750) | Sep 22, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [e40a8996c4](https://linux-hardware.org/?probe=e40a8996c4) | Sep 22, 2022 |
| Acer          | Aspire M3450                | Desktop     | [ff7d0a2394](https://linux-hardware.org/?probe=ff7d0a2394) | Sep 21, 2022 |
| Razer         | Blade                       | Notebook    | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [deb21d492d](https://linux-hardware.org/?probe=deb21d492d) | Sep 21, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [06dc3db422](https://linux-hardware.org/?probe=06dc3db422) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | Notebook    | [1d0f80e0f1](https://linux-hardware.org/?probe=1d0f80e0f1) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | Notebook    | [f349ec9700](https://linux-hardware.org/?probe=f349ec9700) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [9d26eb4243](https://linux-hardware.org/?probe=9d26eb4243) | Sep 19, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [66596e407c](https://linux-hardware.org/?probe=66596e407c) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [d984474cba](https://linux-hardware.org/?probe=d984474cba) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [943bb9e023](https://linux-hardware.org/?probe=943bb9e023) | Sep 19, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [06f5febda2](https://linux-hardware.org/?probe=06f5febda2) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [b707354c65](https://linux-hardware.org/?probe=b707354c65) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [2e1e251503](https://linux-hardware.org/?probe=2e1e251503) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [916e9d7e5e](https://linux-hardware.org/?probe=916e9d7e5e) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [5f56e8b10f](https://linux-hardware.org/?probe=5f56e8b10f) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| MSI           | 870-G45                     | Desktop     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1b40e531b5](https://linux-hardware.org/?probe=1b40e531b5) | Sep 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4f1e683ced](https://linux-hardware.org/?probe=4f1e683ced) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | Desktop     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [e31f54dfa3](https://linux-hardware.org/?probe=e31f54dfa3) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| HP            | 1998                        | Desktop     | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [31f9854044](https://linux-hardware.org/?probe=31f9854044) | Sep 16, 2022 |
| AZW           | GK mini                     | Desktop     | [19b8b4dc85](https://linux-hardware.org/?probe=19b8b4dc85) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Google        | Droid                       | Notebook    | [b4acc4ee70](https://linux-hardware.org/?probe=b4acc4ee70) | Sep 15, 2022 |
| IBT.ca (IB... | MI836                       | Desktop     | [a180af0292](https://linux-hardware.org/?probe=a180af0292) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T510 4349BR8       | Notebook    | [d60b0c8539](https://linux-hardware.org/?probe=d60b0c8539) | Sep 14, 2022 |
| HP            | 1998                        | Desktop     | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [f614aa6ae7](https://linux-hardware.org/?probe=f614aa6ae7) | Sep 14, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [fc1d1cb3bc](https://linux-hardware.org/?probe=fc1d1cb3bc) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | Notebook    | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| HP            | 3031h                       | Desktop     | [9312c20d49](https://linux-hardware.org/?probe=9312c20d49) | Sep 13, 2022 |
| HP            | 3031h                       | Desktop     | [1bbfd867b0](https://linux-hardware.org/?probe=1bbfd867b0) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| DFI           | HD631-Q87CRM                | Desktop     | [b7ed9b1d64](https://linux-hardware.org/?probe=b7ed9b1d64) | Sep 12, 2022 |
| Dell          | XPS 9315                    | Notebook    | [77ecec9e58](https://linux-hardware.org/?probe=77ecec9e58) | Sep 12, 2022 |
| Dell          | XPS 9315                    | Notebook    | [cfaae58ffa](https://linux-hardware.org/?probe=cfaae58ffa) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| ECS           | Nettle3                     | Desktop     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [5a114e6867](https://linux-hardware.org/?probe=5a114e6867) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [276e6547f9](https://linux-hardware.org/?probe=276e6547f9) | Sep 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [14d836c020](https://linux-hardware.org/?probe=14d836c020) | Sep 11, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc6ffac174](https://linux-hardware.org/?probe=bc6ffac174) | Sep 11, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [f8be9f1680](https://linux-hardware.org/?probe=f8be9f1680) | Sep 11, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [51857d9758](https://linux-hardware.org/?probe=51857d9758) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | Notebook    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| HP            | 1998                        | Desktop     | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | Desktop     | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [39c0297cb1](https://linux-hardware.org/?probe=39c0297cb1) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9ce6958b9c](https://linux-hardware.org/?probe=9ce6958b9c) | Sep 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| IBT.ca (IB... | MI836                       | Desktop     | [6155d5bd47](https://linux-hardware.org/?probe=6155d5bd47) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9690933a68](https://linux-hardware.org/?probe=9690933a68) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | Notebook    | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [e5067297e8](https://linux-hardware.org/?probe=e5067297e8) | Sep 07, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [6f32b647ec](https://linux-hardware.org/?probe=6f32b647ec) | Sep 07, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [2f4e7d54e0](https://linux-hardware.org/?probe=2f4e7d54e0) | Sep 07, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6d6c3a5320](https://linux-hardware.org/?probe=6d6c3a5320) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| ASUSTek       | ET2040I                     | Desktop     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b506daf143](https://linux-hardware.org/?probe=b506daf143) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ab4f06e457](https://linux-hardware.org/?probe=ab4f06e457) | Sep 05, 2022 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [0853f0ca45](https://linux-hardware.org/?probe=0853f0ca45) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [3c578ac6c8](https://linux-hardware.org/?probe=3c578ac6c8) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [565c10e82f](https://linux-hardware.org/?probe=565c10e82f) | Sep 05, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e12af15c84](https://linux-hardware.org/?probe=e12af15c84) | Sep 05, 2022 |
| Samsung       | 730QED                      | Convertible | [9af6e3d69d](https://linux-hardware.org/?probe=9af6e3d69d) | Sep 05, 2022 |
| Dell          | Inspiron 15 3525            | Notebook    | [0ec2aca595](https://linux-hardware.org/?probe=0ec2aca595) | Sep 04, 2022 |
| ASUSTek       | Q170M-C                     | Desktop     | [6710f3ecd0](https://linux-hardware.org/?probe=6710f3ecd0) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | Desktop     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Intel         | DQ67SW AAG12527-306         | Desktop     | [9ab6c11be2](https://linux-hardware.org/?probe=9ab6c11be2) | Sep 04, 2022 |
| MSI           | H81M-E34                    | Desktop     | [0fa7f79fdc](https://linux-hardware.org/?probe=0fa7f79fdc) | Sep 03, 2022 |
| Lenovo        | IdeaPad Flex-15IWL 81SR     | Convertible | [6723781de1](https://linux-hardware.org/?probe=6723781de1) | Sep 03, 2022 |
| Dell          | 0FGCC7 A01                  | Server      | [4689cac5c7](https://linux-hardware.org/?probe=4689cac5c7) | Sep 03, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9567e25730](https://linux-hardware.org/?probe=9567e25730) | Sep 03, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | Notebook    | [9b61c2fbcc](https://linux-hardware.org/?probe=9b61c2fbcc) | Sep 02, 2022 |
| Acer          | Aspire M3910                | Desktop     | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [27840cf8d2](https://linux-hardware.org/?probe=27840cf8d2) | Sep 02, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [18756268eb](https://linux-hardware.org/?probe=18756268eb) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Acer          | Aspire TC-605               | Desktop     | [fa13174432](https://linux-hardware.org/?probe=fa13174432) | Sep 02, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | Notebook    | [95e8dcce67](https://linux-hardware.org/?probe=95e8dcce67) | Sep 02, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [969ebd4d3a](https://linux-hardware.org/?probe=969ebd4d3a) | Sep 01, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [02af50752e](https://linux-hardware.org/?probe=02af50752e) | Sep 01, 2022 |
| Acer          | Aspire TC-605               | Desktop     | [fdc6b95d8b](https://linux-hardware.org/?probe=fdc6b95d8b) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a2878122de](https://linux-hardware.org/?probe=a2878122de) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [836d60c547](https://linux-hardware.org/?probe=836d60c547) | Sep 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [d48b9efca4](https://linux-hardware.org/?probe=d48b9efca4) | Sep 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [18822e9fbe](https://linux-hardware.org/?probe=18822e9fbe) | Sep 01, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [6f807b1a84](https://linux-hardware.org/?probe=6f807b1a84) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| JGINYUE       | B85I PLUS V2.1              | Desktop     | [d171691ef3](https://linux-hardware.org/?probe=d171691ef3) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b2456009ae](https://linux-hardware.org/?probe=b2456009ae) | Aug 31, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [4f026584d7](https://linux-hardware.org/?probe=4f026584d7) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20da9d42a4](https://linux-hardware.org/?probe=20da9d42a4) | Aug 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [39ae8218f6](https://linux-hardware.org/?probe=39ae8218f6) | Aug 30, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8acbb8d0b](https://linux-hardware.org/?probe=a8acbb8d0b) | Aug 28, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [b9803fd1ba](https://linux-hardware.org/?probe=b9803fd1ba) | Aug 28, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [f0e2de2452](https://linux-hardware.org/?probe=f0e2de2452) | Aug 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [3ce9a33fed](https://linux-hardware.org/?probe=3ce9a33fed) | Aug 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [2adf8e9ff6](https://linux-hardware.org/?probe=2adf8e9ff6) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [995ab78b23](https://linux-hardware.org/?probe=995ab78b23) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [505d987d1e](https://linux-hardware.org/?probe=505d987d1e) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [8faac70cfa](https://linux-hardware.org/?probe=8faac70cfa) | Aug 27, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [72cf4f38cf](https://linux-hardware.org/?probe=72cf4f38cf) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [814718547c](https://linux-hardware.org/?probe=814718547c) | Aug 27, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | Notebook    | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [83377b24dc](https://linux-hardware.org/?probe=83377b24dc) | Aug 25, 2022 |
| MSI           | WF75 10TK                   | Notebook    | [8f395376ba](https://linux-hardware.org/?probe=8f395376ba) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [73a97b425c](https://linux-hardware.org/?probe=73a97b425c) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d2e2d5484c](https://linux-hardware.org/?probe=d2e2d5484c) | Aug 25, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [005afabbff](https://linux-hardware.org/?probe=005afabbff) | Aug 25, 2022 |
| HP            | 18E4                        | Desktop     | [13d5c6848a](https://linux-hardware.org/?probe=13d5c6848a) | Aug 24, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [5e62f9adde](https://linux-hardware.org/?probe=5e62f9adde) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bcd3bcb389](https://linux-hardware.org/?probe=bcd3bcb389) | Aug 22, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5f90bb65a6](https://linux-hardware.org/?probe=5f90bb65a6) | Aug 21, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c8d31e4708](https://linux-hardware.org/?probe=c8d31e4708) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| Sony          | VPCEB12FD                   | Notebook    | [f98be4240a](https://linux-hardware.org/?probe=f98be4240a) | Aug 20, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Toshiba       | PORTEGE M780                | Notebook    | [8b7e72c5d9](https://linux-hardware.org/?probe=8b7e72c5d9) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [1eca9d2f2d](https://linux-hardware.org/?probe=1eca9d2f2d) | Aug 19, 2022 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [ebc0328fe0](https://linux-hardware.org/?probe=ebc0328fe0) | Aug 19, 2022 |
| Dell          | Latitude E6410              | Notebook    | [3304a70394](https://linux-hardware.org/?probe=3304a70394) | Aug 19, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [3f966fdafa](https://linux-hardware.org/?probe=3f966fdafa) | Aug 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [ac42df990f](https://linux-hardware.org/?probe=ac42df990f) | Aug 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [eec78b1552](https://linux-hardware.org/?probe=eec78b1552) | Aug 17, 2022 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [a8c5b732f4](https://linux-hardware.org/?probe=a8c5b732f4) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [1ab8003e04](https://linux-hardware.org/?probe=1ab8003e04) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [2a3c6446e5](https://linux-hardware.org/?probe=2a3c6446e5) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2a3764a87e](https://linux-hardware.org/?probe=2a3764a87e) | Aug 16, 2022 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [4d5eb5e332](https://linux-hardware.org/?probe=4d5eb5e332) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [239daef655](https://linux-hardware.org/?probe=239daef655) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| Lenovo        | ThinkPad E550 20DF0040CA    | Notebook    | [0f657d4798](https://linux-hardware.org/?probe=0f657d4798) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [286fd1791a](https://linux-hardware.org/?probe=286fd1791a) | Aug 14, 2022 |
| HP            | ENVY m6                     | Notebook    | [74d1a937cf](https://linux-hardware.org/?probe=74d1a937cf) | Aug 14, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| Dell          | G3 3590                     | Notebook    | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Toshiba       | PORTEGE M780                | Notebook    | [b7304a84fd](https://linux-hardware.org/?probe=b7304a84fd) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Dell          | 08GMV7 A00                  | All in one  | [d796aac0eb](https://linux-hardware.org/?probe=d796aac0eb) | Aug 12, 2022 |
| Dell          | 08GMV7 A00                  | All in one  | [40803a469b](https://linux-hardware.org/?probe=40803a469b) | Aug 12, 2022 |
| Dell          | 07PR60 A02                  | Desktop     | [7ed59c8c10](https://linux-hardware.org/?probe=7ed59c8c10) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| Dell          | Latitude 7420               | Notebook    | [26cd6bbb87](https://linux-hardware.org/?probe=26cd6bbb87) | Aug 12, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [b961bc0427](https://linux-hardware.org/?probe=b961bc0427) | Aug 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [426365299d](https://linux-hardware.org/?probe=426365299d) | Aug 10, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [b188230a8a](https://linux-hardware.org/?probe=b188230a8a) | Aug 10, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [7586fd5a58](https://linux-hardware.org/?probe=7586fd5a58) | Aug 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c257fb6e7](https://linux-hardware.org/?probe=9c257fb6e7) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c5e5976db](https://linux-hardware.org/?probe=9c5e5976db) | Aug 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [59250f2c2f](https://linux-hardware.org/?probe=59250f2c2f) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| ASUSTek       | G10DK                       | Desktop     | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| ASUSTek       | TP410UAR                    | Convertible | [e1f77d1f94](https://linux-hardware.org/?probe=e1f77d1f94) | Aug 07, 2022 |
| AZW           | GTR V01                     | Mini pc     | [504142e8e0](https://linux-hardware.org/?probe=504142e8e0) | Aug 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3ef9c93317](https://linux-hardware.org/?probe=3ef9c93317) | Aug 06, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c4a323d350](https://linux-hardware.org/?probe=c4a323d350) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [dca6f9dfbd](https://linux-hardware.org/?probe=dca6f9dfbd) | Aug 06, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1b55cc875](https://linux-hardware.org/?probe=a1b55cc875) | Aug 06, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b1ec54ce80](https://linux-hardware.org/?probe=b1ec54ce80) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [4acbeffc03](https://linux-hardware.org/?probe=4acbeffc03) | Aug 05, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [f25dd33bc3](https://linux-hardware.org/?probe=f25dd33bc3) | Aug 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3b290b6c0b](https://linux-hardware.org/?probe=3b290b6c0b) | Aug 04, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [db66e72de8](https://linux-hardware.org/?probe=db66e72de8) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| Google        | Droid                       | Notebook    | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [323c68d80f](https://linux-hardware.org/?probe=323c68d80f) | Aug 03, 2022 |
| HP            | 339A                        | Desktop     | [27ddbfd51d](https://linux-hardware.org/?probe=27ddbfd51d) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| Alienware     | x17 R2                      | Notebook    | [48772fabd8](https://linux-hardware.org/?probe=48772fabd8) | Aug 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [0df3af0bc5](https://linux-hardware.org/?probe=0df3af0bc5) | Aug 02, 2022 |
| Alienware     | x17 R2                      | Notebook    | [606b777651](https://linux-hardware.org/?probe=606b777651) | Aug 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [4bd0f9e461](https://linux-hardware.org/?probe=4bd0f9e461) | Aug 02, 2022 |
| HP            | Unknown                     | Notebook    | [bd6c9221e7](https://linux-hardware.org/?probe=bd6c9221e7) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [442aaa6069](https://linux-hardware.org/?probe=442aaa6069) | Aug 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ec13dcb17f](https://linux-hardware.org/?probe=ec13dcb17f) | Aug 01, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [ec1e513893](https://linux-hardware.org/?probe=ec1e513893) | Aug 01, 2022 |
| Dell          | 0GXM1W A01                  | Desktop     | [91d2f28256](https://linux-hardware.org/?probe=91d2f28256) | Aug 01, 2022 |
| Dell          | 0GXM1W A01                  | Desktop     | [ab895fc1a2](https://linux-hardware.org/?probe=ab895fc1a2) | Aug 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [15382de4bf](https://linux-hardware.org/?probe=15382de4bf) | Aug 01, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [13cbc87486](https://linux-hardware.org/?probe=13cbc87486) | Jul 31, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | Laptop 15-dy3xxx            | Notebook    | [e54cde5e86](https://linux-hardware.org/?probe=e54cde5e86) | Jul 31, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a1923838e1](https://linux-hardware.org/?probe=a1923838e1) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [22b4bcc010](https://linux-hardware.org/?probe=22b4bcc010) | Jul 31, 2022 |
| Dell          | CS24-TY                     | Server      | [c307dd98ff](https://linux-hardware.org/?probe=c307dd98ff) | Jul 30, 2022 |
| EVGA          | 134-KS-E377                 | Desktop     | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7682000c35](https://linux-hardware.org/?probe=7682000c35) | Jul 30, 2022 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [2fe4fe7fe5](https://linux-hardware.org/?probe=2fe4fe7fe5) | Jul 30, 2022 |
| HP            | 339A                        | Desktop     | [7f2505acd4](https://linux-hardware.org/?probe=7f2505acd4) | Jul 30, 2022 |
| AMI           | T3 MRD                      | Notebook    | [7e0a2ced92](https://linux-hardware.org/?probe=7e0a2ced92) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [38fae80720](https://linux-hardware.org/?probe=38fae80720) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| Clevo         | W150HNM/W170HN              | Notebook    | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [a6237b3a28](https://linux-hardware.org/?probe=a6237b3a28) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [5a12531bf9](https://linux-hardware.org/?probe=5a12531bf9) | Jul 29, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| ASUSTek       | G10DK                       | Desktop     | [70a71d84a6](https://linux-hardware.org/?probe=70a71d84a6) | Jul 28, 2022 |
| Dell          | Latitude E7440              | Notebook    | [ff1e9aae86](https://linux-hardware.org/?probe=ff1e9aae86) | Jul 28, 2022 |
| HP            | 18E6                        | Desktop     | [60d1a8e6da](https://linux-hardware.org/?probe=60d1a8e6da) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b6dea628df](https://linux-hardware.org/?probe=b6dea628df) | Jul 27, 2022 |
| Lenovo        | ThinkPad X270 20HMS0GJ00    | Notebook    | [fa45b52c07](https://linux-hardware.org/?probe=fa45b52c07) | Jul 27, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [e4c1d0bdeb](https://linux-hardware.org/?probe=e4c1d0bdeb) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | Notebook    | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fc499e7600](https://linux-hardware.org/?probe=fc499e7600) | Jul 27, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [5f7787d9e3](https://linux-hardware.org/?probe=5f7787d9e3) | Jul 27, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [c5f4ae1ac4](https://linux-hardware.org/?probe=c5f4ae1ac4) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [b61b6b5fa5](https://linux-hardware.org/?probe=b61b6b5fa5) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| Lenovo        | ThinkPad W530 24472SU       | Notebook    | [52f731db42](https://linux-hardware.org/?probe=52f731db42) | Jul 25, 2022 |
| Dell          | CS24-TY                     | Server      | [230ad2532f](https://linux-hardware.org/?probe=230ad2532f) | Jul 24, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [acc848feda](https://linux-hardware.org/?probe=acc848feda) | Jul 24, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [0084e69574](https://linux-hardware.org/?probe=0084e69574) | Jul 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [60b06048f3](https://linux-hardware.org/?probe=60b06048f3) | Jul 24, 2022 |
| Gateway       | DX4840                      | Desktop     | [0df8a716b1](https://linux-hardware.org/?probe=0df8a716b1) | Jul 24, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8e2855140c](https://linux-hardware.org/?probe=8e2855140c) | Jul 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [4c0cb4fd92](https://linux-hardware.org/?probe=4c0cb4fd92) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [c8ce65cd26](https://linux-hardware.org/?probe=c8ce65cd26) | Jul 23, 2022 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [54e6e291bd](https://linux-hardware.org/?probe=54e6e291bd) | Jul 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [dce15b4c00](https://linux-hardware.org/?probe=dce15b4c00) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2e97c3de0b](https://linux-hardware.org/?probe=2e97c3de0b) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d567131bf9](https://linux-hardware.org/?probe=d567131bf9) | Jul 21, 2022 |
| Dell          | Precision 7560              | Notebook    | [c76f72f8c7](https://linux-hardware.org/?probe=c76f72f8c7) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| HP            | 158B                        | Desktop     | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [afbe55b100](https://linux-hardware.org/?probe=afbe55b100) | Jul 20, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [f843e569ed](https://linux-hardware.org/?probe=f843e569ed) | Jul 20, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0ce9af7993](https://linux-hardware.org/?probe=0ce9af7993) | Jul 20, 2022 |
| Dell          | G3 3590                     | Notebook    | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| ASUSTek       | X555QA                      | Notebook    | [a34b1c5684](https://linux-hardware.org/?probe=a34b1c5684) | Jul 18, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6aac7a75e7](https://linux-hardware.org/?probe=6aac7a75e7) | Jul 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [10be1cd329](https://linux-hardware.org/?probe=10be1cd329) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75990d47d7](https://linux-hardware.org/?probe=75990d47d7) | Jul 17, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ec770759cd](https://linux-hardware.org/?probe=ec770759cd) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [38ebe8f368](https://linux-hardware.org/?probe=38ebe8f368) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [129bcce64f](https://linux-hardware.org/?probe=129bcce64f) | Jul 17, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [236812ea49](https://linux-hardware.org/?probe=236812ea49) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [e762750617](https://linux-hardware.org/?probe=e762750617) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c020ff87e8](https://linux-hardware.org/?probe=c020ff87e8) | Jul 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| HP            | Notebook                    | Notebook    | [8ef9afa771](https://linux-hardware.org/?probe=8ef9afa771) | Jul 16, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [4d57e57019](https://linux-hardware.org/?probe=4d57e57019) | Jul 15, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [d5a6b5628b](https://linux-hardware.org/?probe=d5a6b5628b) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46ef1a2cd6](https://linux-hardware.org/?probe=46ef1a2cd6) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| AMI           | T3 MRD                      | Notebook    | [d29d5d14c8](https://linux-hardware.org/?probe=d29d5d14c8) | Jul 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [386dd1ac4b](https://linux-hardware.org/?probe=386dd1ac4b) | Jul 14, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [e5c9e4e4d9](https://linux-hardware.org/?probe=e5c9e4e4d9) | Jul 13, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [e007a2fbc2](https://linux-hardware.org/?probe=e007a2fbc2) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [fdae528732](https://linux-hardware.org/?probe=fdae528732) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [063f846aad](https://linux-hardware.org/?probe=063f846aad) | Jul 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| Dell          | Latitude 5510               | Notebook    | [5f1abb9d12](https://linux-hardware.org/?probe=5f1abb9d12) | Jul 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [32cbf49371](https://linux-hardware.org/?probe=32cbf49371) | Jul 11, 2022 |
| AWOW          | NY41                        | Mini pc     | [a08b96a066](https://linux-hardware.org/?probe=a08b96a066) | Jul 11, 2022 |
| AWOW          | NY41                        | Mini pc     | [330ebff5e1](https://linux-hardware.org/?probe=330ebff5e1) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 802       | 15.77%  |
| Ubuntu 18.04                 | 420       | 8.26%   |
| Ubuntu 22.04                 | 164       | 3.23%   |
| OpenMandriva 4.2             | 115       | 2.26%   |
| OpenMandriva 4.3             | 107       | 2.1%    |
| Linux Mint 20.3              | 104       | 2.05%   |
| KDE neon 20.04               | 99        | 1.95%   |
| Xubuntu 20.04                | 94        | 1.85%   |
| Debian 11                    | 91        | 1.79%   |
| Manjaro                      | 89        | 1.75%   |
| Pop!_OS 20.04                | 88        | 1.73%   |
| Pop!_OS 22.04                | 84        | 1.65%   |
| Pop!_OS 21.04                | 84        | 1.65%   |
| Zorin 16                     | 81        | 1.59%   |
| Arch                         | 81        | 1.59%   |
| Linux Mint 20.1              | 78        | 1.53%   |
| Linux Mint 19.3              | 76        | 1.49%   |
| Ubuntu 19.10                 | 71        | 1.4%    |
| Zorin 15                     | 69        | 1.36%   |
| Ubuntu 21.10                 | 69        | 1.36%   |
| Fedora 35                    | 68        | 1.34%   |
| Ubuntu 20.10                 | 66        | 1.3%    |
| Pop!_OS 20.10                | 65        | 1.28%   |
| Fedora 33                    | 64        | 1.26%   |
| Linux Mint 20.2              | 63        | 1.24%   |
| Arch Rolling                 | 63        | 1.24%   |
| ArcoLinux Rolling            | 62        | 1.22%   |
| Linux Mint 20                | 58        | 1.14%   |
| Fedora 32                    | 56        | 1.1%    |
| Ubuntu 21.04                 | 53        | 1.04%   |
| Fedora 34                    | 50        | 0.98%   |
| Ubuntu 19.04                 | 48        | 0.94%   |
| Pop!_OS 21.10                | 48        | 0.94%   |
| Fedora 36                    | 48        | 0.94%   |
| Linux Mint 21                | 41        | 0.81%   |
| Fedora 31                    | 33        | 0.65%   |
| Debian 10                    | 33        | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 31        | 0.61%   |
| EndeavourOS Rolling          | 31        | 0.61%   |
| Linux Mint 19.2              | 29        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1680      | 34.77%  |
| Linux Mint    | 435       | 9%      |
| Pop!_OS       | 354       | 7.33%   |
| Fedora        | 315       | 6.52%   |
| OpenMandriva  | 255       | 5.28%   |
| Manjaro       | 195       | 4.04%   |
| Zorin         | 159       | 3.29%   |
| Debian        | 159       | 3.29%   |
| Xubuntu       | 141       | 2.92%   |
| Arch          | 139       | 2.88%   |
| KDE neon      | 117       | 2.42%   |
| ROSA          | 76        | 1.57%   |
| Kubuntu       | 75        | 1.55%   |
| ArcoLinux     | 66        | 1.37%   |
| Gentoo        | 47        | 0.97%   |
| Elementary    | 42        | 0.87%   |
| openSUSE      | 37        | 0.77%   |
| Lubuntu       | 36        | 0.75%   |
| Endless       | 35        | 0.72%   |
| EndeavourOS   | 35        | 0.72%   |
| Ubuntu MATE   | 29        | 0.6%    |
| Clear Linux   | 27        | 0.56%   |
| CentOS        | 27        | 0.56%   |
| BlackPanther  | 27        | 0.56%   |
| Ubuntu Unity  | 25        | 0.52%   |
| Kali          | 25        | 0.52%   |
| LMDE          | 22        | 0.46%   |
| Ubuntu Budgie | 21        | 0.43%   |
| SteamOS       | 21        | 0.43%   |
| MX            | 14        | 0.29%   |
| Garuda Linux  | 14        | 0.29%   |
| Peppermint    | 10        | 0.21%   |
| LinuxFX       | 10        | 0.21%   |
| Nobara        | 9         | 0.19%   |
| Parrot        | 8         | 0.17%   |
| Alpine        | 8         | 0.17%   |
| RHEL          | 7         | 0.14%   |
| Reborn OS     | 7         | 0.14%   |
| Raspbian      | 7         | 0.14%   |
| NixOS         | 7         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 112       | 1.98%   |
| 5.16.7-desktop-1omv4003  | 102       | 1.8%    |
| 5.4.0-42-generic         | 92        | 1.62%   |
| 5.11.0-27-generic        | 59        | 1.04%   |
| 5.4.0-58-generic         | 53        | 0.94%   |
| 5.4.0-48-generic         | 50        | 0.88%   |
| 5.3.0-40-generic         | 50        | 0.88%   |
| 5.15.0-56-generic        | 46        | 0.81%   |
| 5.4.0-52-generic         | 44        | 0.78%   |
| 5.15.0-52-generic        | 44        | 0.78%   |
| 5.4.0-29-generic         | 43        | 0.76%   |
| 5.8.0-7630-generic       | 42        | 0.74%   |
| 5.11.0-40-generic        | 42        | 0.74%   |
| 5.4.0-40-generic         | 38        | 0.67%   |
| 5.0.0-37-generic         | 38        | 0.67%   |
| 5.4.0-26-generic         | 36        | 0.64%   |
| 5.13.0-39-generic        | 36        | 0.64%   |
| 5.3.0-46-generic         | 35        | 0.62%   |
| 5.15.0-48-generic        | 35        | 0.62%   |
| 5.4.0-54-generic         | 34        | 0.6%    |
| 5.15.0-47-generic        | 33        | 0.58%   |
| 5.11.0-7620-generic      | 33        | 0.58%   |
| 5.4.0-37-generic         | 32        | 0.57%   |
| 5.8.0-50-generic         | 31        | 0.55%   |
| 5.15.0-41-generic        | 31        | 0.55%   |
| 5.4.0-66-generic         | 30        | 0.53%   |
| 5.4.0-45-generic         | 29        | 0.51%   |
| 5.15.0-46-generic        | 29        | 0.51%   |
| 5.4.0-47-generic         | 27        | 0.48%   |
| 5.11.0-38-generic        | 27        | 0.48%   |
| 5.4.0-91-generic         | 26        | 0.46%   |
| 5.4.0-7634-generic       | 26        | 0.46%   |
| 5.4.0-56-generic         | 26        | 0.46%   |
| 5.4.0-33-generic         | 26        | 0.46%   |
| 5.3.0-42-generic         | 26        | 0.46%   |
| 5.8.0-59-generic         | 25        | 0.44%   |
| 5.8.0-44-generic         | 25        | 0.44%   |
| 5.13.0-7614-generic      | 25        | 0.44%   |
| 5.8.0-43-generic         | 24        | 0.42%   |
| 5.8.0-41-generic         | 24        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1047      | 19.81%  |
| 5.11.0  | 352       | 6.66%   |
| 5.8.0   | 337       | 6.38%   |
| 4.15.0  | 319       | 6.04%   |
| 5.15.0  | 309       | 5.85%   |
| 5.13.0  | 298       | 5.64%   |
| 5.3.0   | 272       | 5.15%   |
| 5.0.0   | 151       | 2.86%   |
| 5.10.14 | 114       | 2.16%   |
| 4.18.0  | 107       | 2.02%   |
| 5.10.0  | 105       | 1.99%   |
| 5.16.7  | 104       | 1.97%   |
| 5.19.0  | 44        | 0.83%   |
| 4.19.0  | 43        | 0.81%   |
| 5.17.5  | 26        | 0.49%   |
| 6.0.6   | 25        | 0.47%   |
| 5.15.5  | 23        | 0.44%   |
| 5.14.0  | 22        | 0.42%   |
| 4.18.16 | 22        | 0.42%   |
| 4.9.20  | 20        | 0.38%   |
| 4.4.0   | 18        | 0.34%   |
| 4.9.60  | 17        | 0.32%   |
| 5.18.0  | 15        | 0.28%   |
| 5.16.0  | 15        | 0.28%   |
| 5.15.11 | 15        | 0.28%   |
| 5.12.4  | 15        | 0.28%   |
| 6.0.0   | 14        | 0.26%   |
| 5.9.16  | 14        | 0.26%   |
| 5.9.11  | 14        | 0.26%   |
| 5.17.9  | 14        | 0.26%   |
| 6.0.12  | 13        | 0.25%   |
| 5.7.0   | 13        | 0.25%   |
| 3.10.0  | 13        | 0.25%   |
| 5.17.0  | 12        | 0.23%   |
| 5.16.11 | 12        | 0.23%   |
| 5.15.15 | 12        | 0.23%   |
| 5.11.12 | 12        | 0.23%   |
| 5.19.9  | 11        | 0.21%   |
| 5.18.12 | 11        | 0.21%   |
| 5.17.15 | 11        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1137      | 21.89%  |
| 5.15    | 480       | 9.24%   |
| 5.8     | 431       | 8.3%    |
| 5.11    | 407       | 7.84%   |
| 5.13    | 353       | 6.8%    |
| 5.10    | 323       | 6.22%   |
| 4.15    | 320       | 6.16%   |
| 5.3     | 293       | 5.64%   |
| 5.16    | 208       | 4.01%   |
| 5.0     | 160       | 3.08%   |
| 4.18    | 129       | 2.48%   |
| 6.0     | 104       | 2%      |
| 5.19    | 99        | 1.91%   |
| 5.17    | 96        | 1.85%   |
| 5.9     | 84        | 1.62%   |
| 5.14    | 76        | 1.46%   |
| 5.18    | 72        | 1.39%   |
| 5.12    | 71        | 1.37%   |
| 4.9     | 64        | 1.23%   |
| 5.6     | 60        | 1.16%   |
| 4.19    | 58        | 1.12%   |
| 5.7     | 51        | 0.98%   |
| 5.5     | 29        | 0.56%   |
| 4.4     | 22        | 0.42%   |
| 3.10    | 16        | 0.31%   |
| 5.2     | 11        | 0.21%   |
| 6.1     | 8         | 0.15%   |
| 4.1     | 6         | 0.12%   |
| 4.13    | 5         | 0.1%    |
| 5.1     | 4         | 0.08%   |
| 4.14    | 3         | 0.06%   |
| 4.8     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.16    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.11    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4465      | 96.37%  |
| i686    | 113       | 2.44%   |
| aarch64 | 34        | 0.73%   |
| armv7l  | 18        | 0.39%   |
| mips64  | 1         | 0.02%   |
| armv8l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GNOME                | 2152      | 44.16%  |
| Unknown              | 684       | 14.04%  |
| KDE5                 | 679       | 13.93%  |
| X-Cinnamon           | 350       | 7.18%   |
| XFCE                 | 348       | 7.14%   |
| KDE                  | 145       | 2.98%   |
| MATE                 | 112       | 2.3%    |
| Cinnamon             | 62        | 1.27%   |
| KDE4                 | 57        | 1.17%   |
| LXQt                 | 41        | 0.84%   |
| Pantheon             | 40        | 0.82%   |
| i3                   | 34        | 0.7%    |
| Budgie               | 33        | 0.68%   |
| Unity                | 28        | 0.57%   |
| LXDE                 | 26        | 0.53%   |
| GNOME Flashback      | 18        | 0.37%   |
| Deepin               | 13        | 0.27%   |
| GNOME Classic        | 7         | 0.14%   |
| DWM                  | 7         | 0.14%   |
| qtile                | 6         | 0.12%   |
| awesome              | 6         | 0.12%   |
| Openbox              | 4         | 0.08%   |
| Enlightenment        | 4         | 0.08%   |
| xmonad               | 3         | 0.06%   |
| sway                 | 3         | 0.06%   |
| wmaker-common        | 1         | 0.02%   |
| ubuntustudio         | 1         | 0.02%   |
| trinity              | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| spectrwm             | 1         | 0.02%   |
| river                | 1         | 0.02%   |
| Lubuntu              | 1         | 0.02%   |
| lightdm-xsession     | 1         | 0.02%   |
| LeftWM               | 1         | 0.02%   |
| hyprland             | 1         | 0.02%   |
| bspwm                | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3755      | 78.75%  |
| Wayland | 559       | 11.72%  |
| Unknown | 343       | 7.19%   |
| Tty     | 106       | 2.22%   |
| Web     | 5         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2752      | 57.01%  |
| SDDM    | 594       | 12.31%  |
| GDM     | 522       | 10.81%  |
| GDM3    | 375       | 7.77%   |
| LightDM | 362       | 7.5%    |
| TDM     | 142       | 2.94%   |
| KDM     | 51        | 1.06%   |
| XDM     | 13        | 0.27%   |
| SLiM    | 7         | 0.15%   |
| Ly      | 4         | 0.08%   |
| LXDM    | 2         | 0.04%   |
| GREETD  | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_CA      | 2451      | 51.11%  |
| en_US      | 1203      | 25.08%  |
| Unknown    | 571       | 11.91%  |
| fr_CA      | 332       | 6.92%   |
| C          | 104       | 2.17%   |
| fr_FR      | 46        | 0.96%   |
| en_GB      | 25        | 0.52%   |
| POSIX      | 8         | 0.17%   |
| en_AU      | 7         | 0.15%   |
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
| ga_IE      | 1         | 0.02%   |
| es_CL      | 1         | 0.02%   |
| es_BO      | 1         | 0.02%   |
| en_ZM      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_NZ      | 1         | 0.02%   |
| en_FI      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| co_FR      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2603      | 54.77%  |
| EFI  | 2150      | 45.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3656      | 76.95%  |
| Btrfs   | 381       | 8.02%   |
| Overlay | 362       | 7.62%   |
| Unknown | 177       | 3.73%   |
| Xfs     | 78        | 1.64%   |
| Zfs     | 47        | 0.99%   |
| Ext2    | 19        | 0.4%    |
| Ext3    | 10        | 0.21%   |
| Aufs    | 8         | 0.17%   |
| F2fs    | 6         | 0.13%   |
| Tmpfs   | 4         | 0.08%   |
| Jfs     | 2         | 0.04%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2857      | 60.25%  |
| GPT     | 1416      | 29.86%  |
| MBR     | 469       | 9.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3994      | 84.3%   |
| Yes       | 744       | 15.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3452      | 73.07%  |
| Yes       | 1272      | 26.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 844       | 18.24%  |
| Dell                    | 687       | 14.85%  |
| Lenovo                  | 606       | 13.1%   |
| Hewlett-Packard         | 587       | 12.69%  |
| Acer                    | 353       | 7.63%   |
| Gigabyte Technology     | 290       | 6.27%   |
| MSI                     | 282       | 6.09%   |
| Apple                   | 166       | 3.59%   |
| ASRock                  | 116       | 2.51%   |
| Toshiba                 | 95        | 2.05%   |
| Intel                   | 68        | 1.47%   |
| Raspberry Pi Foundation | 34        | 0.73%   |
| Alienware               | 34        | 0.73%   |
| Sony                    | 32        | 0.69%   |
| Unknown                 | 31        | 0.67%   |
| Gateway                 | 28        | 0.61%   |
| Pegatron                | 27        | 0.58%   |
| Supermicro              | 26        | 0.56%   |
| Microsoft               | 25        | 0.54%   |
| Foxconn                 | 24        | 0.52%   |
| Samsung Electronics     | 23        | 0.5%    |
| Google                  | 22        | 0.48%   |
| Valve                   | 18        | 0.39%   |
| System76                | 17        | 0.37%   |
| Panasonic               | 15        | 0.32%   |
| Biostar                 | 10        | 0.22%   |
| ZOTAC                   | 9         | 0.19%   |
| ECS                     | 9         | 0.19%   |
| Razer                   | 8         | 0.17%   |
| Fujitsu                 | 7         | 0.15%   |
| AZW                     | 6         | 0.13%   |
| HUAWEI                  | 5         | 0.11%   |
| eMachines               | 5         | 0.11%   |
| AMI                     | 5         | 0.11%   |
| TYAN Computer           | 4         | 0.09%   |
| Notebook                | 4         | 0.09%   |
| LG Electronics          | 4         | 0.09%   |
| Fanless Mini PC         | 4         | 0.09%   |
| EVGA                    | 4         | 0.09%   |
| EUROCOM                 | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 50        | 1.08%   |
| Unknown                            | 41        | 0.89%   |
| HP Notebook                        | 19        | 0.41%   |
| ASUS TUF Gaming X570-PLUS          | 19        | 0.41%   |
| Valve Jupiter                      | 18        | 0.39%   |
| HP Pavilion g6                     | 18        | 0.39%   |
| Acer Aspire A315-21                | 14        | 0.3%    |
| MSI MS-7C02                        | 13        | 0.28%   |
| Dell XPS 15 7590                   | 13        | 0.28%   |
| Dell OptiPlex 790                  | 13        | 0.28%   |
| Dell Latitude E6410                | 13        | 0.28%   |
| MSI MS-7C37                        | 12        | 0.26%   |
| HP Z400 Workstation                | 12        | 0.26%   |
| Dell XPS 15 9500                   | 12        | 0.26%   |
| RPi Raspberry Pi                   | 11        | 0.24%   |
| ASUS PRIME B450M-A                 | 11        | 0.24%   |
| Apple iMac8,1                      | 11        | 0.24%   |
| HP Pavilion 15                     | 10        | 0.22%   |
| Dell OptiPlex 780                  | 10        | 0.22%   |
| Dell Latitude E6420                | 10        | 0.22%   |
| ASUS TP410UAR                      | 10        | 0.22%   |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.22%   |
| ASUS M5A97 LE R2.0                 | 10        | 0.22%   |
| ASRock B450M Pro4                  | 10        | 0.22%   |
| Apple iMac7,1                      | 10        | 0.22%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 9         | 0.19%   |
| MSI MS-7C84                        | 9         | 0.19%   |
| HP Pavilion Notebook               | 9         | 0.19%   |
| HP Pavilion dv6                    | 9         | 0.19%   |
| HP EliteBook 8460p                 | 9         | 0.19%   |
| Gigabyte B450 AORUS PRO WIFI       | 9         | 0.19%   |
| Dell OptiPlex 7010                 | 9         | 0.19%   |
| ASUS M5A99FX PRO R2.0              | 9         | 0.19%   |
| Apple MacBookPro9,2                | 9         | 0.19%   |
| Toshiba Satellite A200             | 8         | 0.17%   |
| MSI MS-7C95                        | 8         | 0.17%   |
| MSI MS-7C56                        | 8         | 0.17%   |
| MSI MS-7693                        | 8         | 0.17%   |
| Dell Inspiron 1545                 | 8         | 0.17%   |
| ASUS M5A97 R2.0                    | 8         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 311       | 6.72%   |
| Acer Aspire         | 278       | 6.01%   |
| Dell Inspiron       | 151       | 3.26%   |
| Dell Latitude       | 147       | 3.18%   |
| Dell XPS            | 126       | 2.72%   |
| HP Pavilion         | 114       | 2.46%   |
| Dell OptiPlex       | 108       | 2.33%   |
| ASUS ROG            | 95        | 2.05%   |
| Lenovo ThinkCentre  | 94        | 2.03%   |
| ASUS PRIME          | 93        | 2.01%   |
| HP Compaq           | 81        | 1.75%   |
| Toshiba Satellite   | 80        | 1.73%   |
| Lenovo IdeaPad      | 74        | 1.6%    |
| HP EliteBook        | 72        | 1.56%   |
| ASUS TUF            | 54        | 1.17%   |
| Dell Precision      | 52        | 1.12%   |
| ASUS All            | 50        | 1.08%   |
| HP Laptop           | 48        | 1.04%   |
| ASUS VivoBook       | 43        | 0.93%   |
| Unknown             | 41        | 0.89%   |
| HP ProBook          | 39        | 0.84%   |
| RPi Raspberry       | 34        | 0.73%   |
| HP ENVY             | 34        | 0.73%   |
| Dell Vostro         | 28        | 0.61%   |
| Microsoft Surface   | 25        | 0.54%   |
| Gigabyte X570       | 24        | 0.52%   |
| Dell Studio         | 23        | 0.5%    |
| ASUS M5A97          | 23        | 0.5%    |
| HP EliteDesk        | 22        | 0.48%   |
| HP Notebook         | 19        | 0.41%   |
| Gigabyte B450       | 19        | 0.41%   |
| Acer Nitro          | 19        | 0.41%   |
| Valve Jupiter       | 18        | 0.39%   |
| Lenovo ThinkStation | 18        | 0.39%   |
| Lenovo Legion       | 18        | 0.39%   |
| Lenovo Yoga         | 17        | 0.37%   |
| Dell PowerEdge      | 17        | 0.37%   |
| ASUS ZenBook        | 17        | 0.37%   |
| ASUS SABERTOOTH     | 16        | 0.35%   |
| ASRock B450M        | 16        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 412       | 8.9%    |
| 2012    | 403       | 8.71%   |
| 2019    | 400       | 8.64%   |
| 2020    | 399       | 8.62%   |
| 2011    | 395       | 8.54%   |
| 2013    | 336       | 7.26%   |
| 2017    | 311       | 6.72%   |
| 2010    | 285       | 6.16%   |
| 2014    | 266       | 5.75%   |
| 2008    | 236       | 5.1%    |
| 2016    | 210       | 4.54%   |
| 2015    | 207       | 4.47%   |
| 2009    | 203       | 4.39%   |
| 2021    | 197       | 4.26%   |
| 2007    | 152       | 3.29%   |
| 2022    | 86        | 1.86%   |
| 2006    | 63        | 1.36%   |
| Unknown | 38        | 0.82%   |
| 2005    | 22        | 0.48%   |
| 2004    | 6         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2170      | 46.9%   |
| Desktop        | 2049      | 44.28%  |
| Convertible    | 124       | 2.68%   |
| All in one     | 89        | 1.92%   |
| Server         | 57        | 1.23%   |
| Mini pc        | 54        | 1.17%   |
| System on chip | 44        | 0.95%   |
| Tablet         | 37        | 0.8%    |
| Phone          | 3         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4380      | 93.95%  |
| Enabled  | 282       | 6.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4591      | 99.2%   |
| Yes  | 37        | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1020      | 21.69%  |
| 4.01-8.0        | 1014      | 21.56%  |
| 8.01-16.0       | 863       | 18.35%  |
| 3.01-4.0        | 748       | 15.9%   |
| 32.01-64.0      | 526       | 11.18%  |
| 1.01-2.0        | 179       | 3.81%   |
| 64.01-256.0     | 150       | 3.19%   |
| 24.01-32.0      | 83        | 1.76%   |
| 2.01-3.0        | 69        | 1.47%   |
| 0.51-1.0        | 35        | 0.74%   |
| More than 256.0 | 8         | 0.17%   |
| 0.01-0.5        | 6         | 0.13%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1846      | 35.63%  |
| 2.01-3.0    | 1246      | 24.05%  |
| 4.01-8.0    | 746       | 14.4%   |
| 3.01-4.0    | 651       | 12.57%  |
| 0.51-1.0    | 336       | 6.49%   |
| 8.01-16.0   | 215       | 4.15%   |
| 0.01-0.5    | 78        | 1.51%   |
| 24.01-32.0  | 21        | 0.41%   |
| 32.01-64.0  | 18        | 0.35%   |
| 16.01-24.0  | 15        | 0.29%   |
| 64.01-256.0 | 5         | 0.1%    |
| Unknown     | 4         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2707      | 56.05%  |
| 2       | 1130      | 23.4%   |
| 3       | 426       | 8.82%   |
| 4       | 240       | 4.97%   |
| 5       | 125       | 2.59%   |
| 6       | 59        | 1.22%   |
| 0       | 50        | 1.04%   |
| 7       | 37        | 0.77%   |
| 8       | 19        | 0.39%   |
| 9       | 11        | 0.23%   |
| 10      | 8         | 0.17%   |
| 11      | 5         | 0.1%    |
| 12      | 4         | 0.08%   |
| Unknown | 4         | 0.08%   |
| 14      | 2         | 0.04%   |
| 13      | 2         | 0.04%   |
| 16      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2609      | 55.71%  |
| Yes       | 2074      | 44.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4073      | 87.8%   |
| No        | 566       | 12.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3437      | 73.66%  |
| No        | 1229      | 26.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2612      | 55.54%  |
| No        | 2091      | 44.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 4627      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Toronto         | 481       | 9.87%   |
| Montreal        | 467       | 9.59%   |
| Vancouver       | 206       | 4.23%   |
| Calgary         | 191       | 3.92%   |
| Ottawa          | 175       | 3.59%   |
| Edmonton        | 155       | 3.18%   |
| Québec         | 100       | 2.05%   |
| Winnipeg        | 93        | 1.91%   |
| Mississauga     | 73        | 1.5%    |
| Victoria        | 69        | 1.42%   |
| Surrey          | 60        | 1.23%   |
| Regina          | 53        | 1.09%   |
| London          | 51        | 1.05%   |
| Laval           | 50        | 1.03%   |
| Kitchener       | 49        | 1.01%   |
| Brampton        | 49        | 1.01%   |
| Hamilton        | 47        | 0.96%   |
| Saskatoon       | 44        | 0.9%    |
| Burnaby         | 41        | 0.84%   |
| Gatineau        | 39        | 0.8%    |
| Windsor         | 35        | 0.72%   |
| Halifax         | 35        | 0.72%   |
| Oshawa          | 32        | 0.66%   |
| Sherbrooke      | 30        | 0.62%   |
| Kingston        | 28        | 0.57%   |
| Scarborough     | 27        | 0.55%   |
| Richmond Hill   | 27        | 0.55%   |
| Trois-Rivières | 26        | 0.53%   |
| New Westminster | 26        | 0.53%   |
| Moncton         | 25        | 0.51%   |
| Oakville        | 23        | 0.47%   |
| North Vancouver | 23        | 0.47%   |
| Markham         | 23        | 0.47%   |
| Barrie          | 23        | 0.47%   |
| Kelowna         | 22        | 0.45%   |
| Waterloo        | 21        | 0.43%   |
| Red Deer        | 21        | 0.43%   |
| Levis           | 20        | 0.41%   |
| Dartmouth       | 20        | 0.41%   |
| Sherwood Park   | 19        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 1310      | 2161   | 18.58%  |
| Seagate                   | 1295      | 2247   | 18.37%  |
| Samsung Electronics       | 967       | 1516   | 13.72%  |
| Kingston                  | 431       | 600    | 6.11%   |
| Toshiba                   | 378       | 487    | 5.36%   |
| SanDisk                   | 301       | 377    | 4.27%   |
| Unknown                   | 297       | 407    | 4.21%   |
| Hitachi                   | 252       | 333    | 3.57%   |
| Intel                     | 210       | 323    | 2.98%   |
| Crucial                   | 195       | 269    | 2.77%   |
| A-DATA Technology         | 167       | 222    | 2.37%   |
| SK hynix                  | 143       | 175    | 2.03%   |
| HGST                      | 117       | 153    | 1.66%   |
| Micron Technology         | 73        | 101    | 1.04%   |
| Apple                     | 59        | 74     | 0.84%   |
| Phison                    | 54        | 80     | 0.77%   |
| Fujitsu                   | 41        | 50     | 0.58%   |
| OCZ                       | 38        | 47     | 0.54%   |
| SPCC                      | 34        | 42     | 0.48%   |
| China                     | 30        | 34     | 0.43%   |
| Corsair                   | 29        | 35     | 0.41%   |
| KIOXIA                    | 28        | 33     | 0.4%    |
| LITEONIT                  | 27        | 28     | 0.38%   |
| Silicon Motion            | 26        | 36     | 0.37%   |
| PNY                       | 26        | 39     | 0.37%   |
| Patriot                   | 22        | 26     | 0.31%   |
| ASMT                      | 22        | 27     | 0.31%   |
| Mushkin                   | 21        | 25     | 0.3%    |
| Micron/Crucial Technology | 21        | 31     | 0.3%    |
| XPG                       | 19        | 28     | 0.27%   |
| LITEON                    | 19        | 21     | 0.27%   |
| Team                      | 18        | 20     | 0.26%   |
| JMicron Technology        | 18        | 24     | 0.26%   |
| Hewlett-Packard           | 17        | 28     | 0.24%   |
| Maxtor                    | 16        | 22     | 0.23%   |
| Unknown                   | 15        | 15     | 0.21%   |
| SABRENT                   | 14        | 19     | 0.2%    |
| KingFast                  | 13        | 16     | 0.18%   |
| External                  | 11        | 18     | 0.16%   |
| TO Exter                  | 10        | 12     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 106       | 1.32%   |
| Samsung SSD 850 EVO 250GB              | 80        | 1%      |
| Samsung SSD 860 EVO 500GB              | 73        | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB         | 62        | 0.77%   |
| Samsung SSD 850 EVO 500GB              | 56        | 0.7%    |
| Kingston SA400S37120G 120GB SSD        | 56        | 0.7%    |
| Samsung SSD 860 EVO 1TB                | 54        | 0.67%   |
| Samsung NVMe SSD Drive 500GB           | 54        | 0.67%   |
| Unknown MMC Card  32GB                 | 52        | 0.65%   |
| SanDisk NVMe SSD Drive 500GB           | 49        | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 48        | 0.6%    |
| Kingston SA400S37480G 480GB SSD        | 47        | 0.58%   |
| Unknown SD/MMC/MS PRO 64GB             | 46        | 0.57%   |
| Toshiba MQ01ABD100 1TB                 | 46        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB         | 44        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB        | 43        | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB         | 43        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD       | 43        | 0.53%   |
| Unknown MMC Card  64GB                 | 42        | 0.52%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 41        | 0.51%   |
| Seagate ST1000LX015-1U7172 1TB         | 40        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 40        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB               | 39        | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB         | 39        | 0.49%   |
| SanDisk NVMe SSD Drive 1TB             | 38        | 0.47%   |
| Samsung SSD 860 EVO 250GB              | 38        | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB         | 37        | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB         | 37        | 0.46%   |
| Toshiba DT01ACA200 2TB                 | 35        | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB         | 35        | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB         | 34        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB            | 34        | 0.42%   |
| HGST HTS721010A9E630 1TB               | 33        | 0.41%   |
| Seagate Expansion Desk 5TB             | 32        | 0.4%    |
| Seagate ST3500418AS 500GB              | 31        | 0.39%   |
| Seagate Expansion 4TB                  | 31        | 0.39%   |
| Seagate ST31000528AS 1TB               | 29        | 0.36%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 29        | 0.36%   |
| Samsung NVMe SSD Drive 512GB           | 29        | 0.36%   |
| Kingston SV300S37A240G 240GB SSD       | 28        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1252      | 2156   | 39.2%   |
| WDC                 | 1042      | 1715   | 32.62%  |
| Toshiba             | 306       | 402    | 9.58%   |
| Hitachi             | 252       | 333    | 7.89%   |
| HGST                | 117       | 153    | 3.66%   |
| Samsung Electronics | 50        | 66     | 1.57%   |
| Unknown             | 46        | 59     | 1.44%   |
| Fujitsu             | 41        | 50     | 1.28%   |
| Apple               | 23        | 25     | 0.72%   |
| Maxtor              | 16        | 22     | 0.5%    |
| ASMT                | 16        | 21     | 0.5%    |
| Maxone              | 6         | 8      | 0.19%   |
| JMicron Technology  | 5         | 6      | 0.16%   |
| USB 3.0             | 2         | 6      | 0.06%   |
| Hewlett-Packard     | 2         | 9      | 0.06%   |
| External            | 2         | 2      | 0.06%   |
| DAS                 | 2         | 14     | 0.06%   |
| USB3.0              | 1         | 2      | 0.03%   |
| SABRENT             | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 6      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 576       | 877    | 25.42%  |
| Kingston            | 372       | 516    | 16.42%  |
| WDC                 | 197       | 277    | 8.69%   |
| Crucial             | 176       | 233    | 7.77%   |
| A-DATA Technology   | 147       | 196    | 6.49%   |
| SanDisk             | 143       | 170    | 6.31%   |
| Intel               | 95        | 128    | 4.19%   |
| Micron Technology   | 49        | 71     | 2.16%   |
| OCZ                 | 37        | 43     | 1.63%   |
| Apple               | 31        | 36     | 1.37%   |
| SPCC                | 30        | 38     | 1.32%   |
| Seagate             | 30        | 43     | 1.32%   |
| China               | 30        | 34     | 1.32%   |
| SK hynix            | 28        | 36     | 1.24%   |
| LITEONIT            | 27        | 28     | 1.19%   |
| PNY                 | 26        | 39     | 1.15%   |
| Toshiba             | 22        | 26     | 0.97%   |
| Patriot             | 22        | 26     | 0.97%   |
| Mushkin             | 19        | 23     | 0.84%   |
| Corsair             | 18        | 20     | 0.79%   |
| Team                | 17        | 19     | 0.75%   |
| LITEON              | 15        | 16     | 0.66%   |
| TO Exter            | 10        | 12     | 0.44%   |
| Hewlett-Packard     | 10        | 13     | 0.44%   |
| Dogfish             | 10        | 13     | 0.44%   |
| OWC                 | 8         | 17     | 0.35%   |
| Transcend           | 7         | 8      | 0.31%   |
| NGFF                | 7         | 8      | 0.31%   |
| Lexar               | 6         | 7      | 0.26%   |
| KingDian            | 6         | 6      | 0.26%   |
| JMicron Technology  | 6         | 9      | 0.26%   |
| TCSUNBOW            | 5         | 6      | 0.22%   |
| KingFast            | 5         | 5      | 0.22%   |
| ASMT                | 5         | 5      | 0.22%   |
| WDC WDS             | 4         | 5      | 0.18%   |
| Vaseky              | 3         | 4      | 0.13%   |
| TSA                 | 3         | 3      | 0.13%   |
| T-FORCE             | 3         | 3      | 0.13%   |
| SUNEAST             | 3         | 3      | 0.13%   |
| OCZ-VERTEX3         | 3         | 3      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2632      | 5068   | 42.59%  |
| SSD     | 1934      | 3096   | 31.29%  |
| NVMe    | 1251      | 1896   | 20.24%  |
| MMC     | 242       | 329    | 3.92%   |
| Unknown | 121       | 168    | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3689      | 7728   | 66.18%  |
| NVMe | 1233      | 1858   | 22.12%  |
| SAS  | 410       | 642    | 7.36%   |
| MMC  | 242       | 329    | 4.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2663      | 4216   | 52.88%  |
| 0.51-1.0   | 1420      | 2216   | 28.2%   |
| 1.01-2.0   | 473       | 826    | 9.39%   |
| 3.01-4.0   | 203       | 334    | 4.03%   |
| 4.01-10.0  | 152       | 320    | 3.02%   |
| 2.01-3.0   | 113       | 224    | 2.24%   |
| 10.01-20.0 | 11        | 22     | 0.22%   |
| 20.01-50.0 | 1         | 6      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1158      | 23.29%  |
| 251-500        | 1089      | 21.9%   |
| 501-1000       | 754       | 15.16%  |
| 1001-2000      | 411       | 8.27%   |
| 1-20           | 380       | 7.64%   |
| More than 3000 | 356       | 7.16%   |
| 51-100         | 270       | 5.43%   |
| 21-50          | 192       | 3.86%   |
| Unknown        | 182       | 3.66%   |
| 2001-3000      | 180       | 3.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2023      | 39.27%  |
| 21-50          | 855       | 16.6%   |
| 101-250        | 589       | 11.43%  |
| 51-100         | 520       | 10.1%   |
| 251-500        | 352       | 6.83%   |
| 501-1000       | 253       | 4.91%   |
| Unknown        | 182       | 3.53%   |
| 1001-2000      | 176       | 3.42%   |
| More than 3000 | 130       | 2.52%   |
| 2001-3000      | 71        | 1.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8         | 9      | 1.86%   |
| Seagate ST500LM000-1EJ162 500GB     | 6         | 6      | 1.39%   |
| WDC WD2500HHTZ-04N21V0 250GB        | 5         | 5      | 1.16%   |
| WDC WD20EARS-00MVWB0 2TB            | 5         | 6      | 1.16%   |
| Seagate ST9500420AS 500GB           | 5         | 5      | 1.16%   |
| Seagate ST9500325AS 500GB           | 5         | 5      | 1.16%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.16%   |
| Seagate ST3500418AS 500GB           | 5         | 5      | 1.16%   |
| Seagate ST31000528AS 1TB            | 5         | 5      | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 6      | 1.16%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.16%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 17     | 0.93%   |
| Toshiba MQ01ABD100 1TB              | 4         | 5      | 0.93%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 5      | 0.93%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 6      | 0.93%   |
| Intel SSDSA1M080G2LE 80GB           | 4         | 4      | 0.93%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.93%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 0.93%   |
| WDC WD6400AAKS-22A7B2 640GB         | 3         | 3      | 0.7%    |
| WDC WD10EARX-00N0YB0 1TB            | 3         | 4      | 0.7%    |
| Seagate ST9320325AS 320GB           | 3         | 6      | 0.7%    |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.7%    |
| Seagate ST31500341AS 1TB            | 3         | 3      | 0.7%    |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 3      | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 0.7%    |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 4      | 0.7%    |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 3      | 0.7%    |
| Hitachi HDS721010CLA332 1TB         | 3         | 3      | 0.7%    |
| HGST HTS725050A7E630 500GB          | 3         | 3      | 0.7%    |
| Crucial CT1000P1SSD8 1TB            | 3         | 9      | 0.7%    |
| A-DATA Technology SX900 256GB SSD   | 3         | 3      | 0.7%    |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.46%   |
| WDC WD30EFRX-68EUZN0 3TB            | 2         | 2      | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 2         | 2      | 0.46%   |
| WDC WD20EARS-00J2GB0 2TB            | 2         | 2      | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 2      | 0.46%   |
| WDC WD10EZEX-08M2NA0 1TB            | 2         | 3      | 0.46%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 137       | 174    | 32.93%  |
| WDC                 | 109       | 143    | 26.2%   |
| Hitachi             | 34        | 35     | 8.17%   |
| Toshiba             | 22        | 23     | 5.29%   |
| Samsung Electronics | 22        | 27     | 5.29%   |
| HGST                | 17        | 17     | 4.09%   |
| Kingston            | 14        | 19     | 3.37%   |
| Intel               | 13        | 14     | 3.13%   |
| Crucial             | 10        | 17     | 2.4%    |
| A-DATA Technology   | 10        | 11     | 2.4%    |
| SK hynix            | 3         | 3      | 0.72%   |
| LITEONIT            | 3         | 3      | 0.72%   |
| Apple               | 3         | 3      | 0.72%   |
| OCZ                 | 2         | 2      | 0.48%   |
| Mushkin             | 2         | 2      | 0.48%   |
| Fujitsu             | 2         | 2      | 0.48%   |
| ASMT                | 2         | 3      | 0.48%   |
| Super Talent        | 1         | 1      | 0.24%   |
| Sandisk             | 1         | 1      | 0.24%   |
| Micron Technology   | 1         | 1      | 0.24%   |
| Maxtor              | 1         | 1      | 0.24%   |
| LITEON              | 1         | 1      | 0.24%   |
| LaCie               | 1         | 1      | 0.24%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| Drevo               | 1         | 1      | 0.24%   |
| DAS                 | 1         | 3      | 0.24%   |
| Corsair             | 1         | 1      | 0.24%   |
| China               | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 137       | 174    | 40.9%   |
| WDC                 | 109       | 143    | 32.54%  |
| Hitachi             | 34        | 35     | 10.15%  |
| Toshiba             | 21        | 22     | 6.27%   |
| HGST                | 17        | 17     | 5.07%   |
| Samsung Electronics | 8         | 12     | 2.39%   |
| Fujitsu             | 2         | 2      | 0.6%    |
| ASMT                | 2         | 3      | 0.6%    |
| Apple               | 2         | 2      | 0.6%    |
| Maxtor              | 1         | 1      | 0.3%    |
| LaCie               | 1         | 1      | 0.3%    |
| DAS                 | 1         | 3      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 317       | 415    | 79.45%  |
| SSD  | 69        | 76     | 17.29%  |
| NVMe | 13        | 20     | 3.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


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

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3110      | 6906   | 61.33%  |
| Works    | 1572      | 3131   | 31%     |
| Malfunc  | 384       | 511    | 7.57%   |
| Failed   | 5         | 9      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3001      | 50.98%  |
| AMD                              | 1059      | 17.99%  |
| Samsung Electronics              | 448       | 7.61%   |
| SanDisk                          | 283       | 4.81%   |
| ASMedia Technology               | 133       | 2.26%   |
| Marvell Technology Group         | 120       | 2.04%   |
| SK hynix                         | 112       | 1.9%    |
| Nvidia                           | 104       | 1.77%   |
| JMicron Technology               | 85        | 1.44%   |
| Phison Electronics               | 75        | 1.27%   |
| Kingston Technology Company      | 69        | 1.17%   |
| Toshiba America Info Systems     | 51        | 0.87%   |
| ADATA Technology                 | 44        | 0.75%   |
| Micron/Crucial Technology        | 41        | 0.7%    |
| Silicon Motion                   | 36        | 0.61%   |
| LSI Logic / Symbios Logic        | 36        | 0.61%   |
| KIOXIA                           | 31        | 0.53%   |
| Micron Technology                | 26        | 0.44%   |
| Broadcom / LSI                   | 23        | 0.39%   |
| Realtek Semiconductor            | 15        | 0.25%   |
| Silicon Image                    | 14        | 0.24%   |
| Seagate Technology               | 11        | 0.19%   |
| VIA Technologies                 | 9         | 0.15%   |
| Union Memory (Shenzhen)          | 8         | 0.14%   |
| Lite-On Technology               | 7         | 0.12%   |
| Hewlett-Packard                  | 7         | 0.12%   |
| Apple                            | 6         | 0.1%    |
| Lenovo                           | 5         | 0.08%   |
| INNOGRIT                         | 4         | 0.07%   |
| HighPoint Technologies           | 4         | 0.07%   |
| Adaptec                          | 4         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Solid State Storage Technology   | 2         | 0.03%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| OCZ Technology Group             | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| Loongson Technology              | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 706       | 10.13%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 239       | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 209       | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 197       | 2.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 164       | 2.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 158       | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 152       | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 150       | 2.15%   |
| Intel SATA Controller [RAID mode]                                              | 134       | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 133       | 1.91%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 125       | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 124       | 1.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 108       | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 106       | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 96        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 96        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 86        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 86        | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 83        | 1.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 82        | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 81        | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 77        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 75        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 73        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 72        | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 69        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 69        | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 66        | 0.95%   |
| AMD 500 Series Chipset SATA Controller                                         | 65        | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 61        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 60        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 59        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 58        | 0.83%   |
| Samsung NVMe SSD Controller 980                                                | 54        | 0.77%   |
| Intel SSD 660P Series                                                          | 52        | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 46        | 0.66%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 44        | 0.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 44        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                             | 43        | 0.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 42        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3375      | 57.27%  |
| NVMe | 1249      | 21.19%  |
| IDE  | 759       | 12.88%  |
| RAID | 455       | 7.72%   |
| SAS  | 42        | 0.71%   |
| SCSI | 13        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 3342      | 72.23%  |
| AMD      | 1231      | 26.6%   |
| ARM      | 49        | 1.06%   |
| Unknown  | 4         | 0.09%   |
| QUALCOMM | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 53        | 1.14%   |
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 39        | 0.84%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 38        | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 36        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 35        | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 34        | 0.73%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 33        | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 0.69%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 32        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 32        | 0.69%   |
| ARM Processor                                 | 31        | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 30        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 27        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 25        | 0.54%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 25        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 24        | 0.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 23        | 0.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 0.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 23        | 0.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 22        | 0.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 22        | 0.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 0.45%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 20        | 0.43%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 20        | 0.43%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 20        | 0.43%   |
| AMD FX-8350 Eight-Core Processor              | 20        | 0.43%   |
| AMD FX-8320 Eight-Core Processor              | 20        | 0.43%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 0.41%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 986       | 21.28%  |
| Intel Core i7           | 972       | 20.98%  |
| Other                   | 250       | 5.39%   |
| Intel Core 2 Duo        | 235       | 5.07%   |
| Intel Core i3           | 233       | 5.03%   |
| AMD Ryzen 5             | 230       | 4.96%   |
| AMD Ryzen 7             | 218       | 4.7%    |
| Intel Xeon              | 172       | 3.71%   |
| Intel Celeron           | 132       | 2.85%   |
| AMD FX                  | 97        | 2.09%   |
| AMD Ryzen 9             | 85        | 1.83%   |
| Intel Pentium           | 84        | 1.81%   |
| AMD A6                  | 68        | 1.47%   |
| AMD A10                 | 65        | 1.4%    |
| Intel Atom              | 60        | 1.29%   |
| Intel Core 2 Quad       | 59        | 1.27%   |
| Intel Pentium Dual-Core | 55        | 1.19%   |
| AMD Ryzen 3             | 43        | 0.93%   |
| Intel Core i9           | 39        | 0.84%   |
| AMD Athlon 64 X2        | 39        | 0.84%   |
| AMD A8                  | 39        | 0.84%   |
| Intel Pentium Dual      | 38        | 0.82%   |
| Intel Core 2            | 34        | 0.73%   |
| AMD A4                  | 33        | 0.71%   |
| Intel Genuine           | 22        | 0.47%   |
| AMD Athlon II X2        | 21        | 0.45%   |
| AMD Phenom II X4        | 19        | 0.41%   |
| AMD Phenom              | 17        | 0.37%   |
| AMD E                   | 17        | 0.37%   |
| Intel Pentium D         | 15        | 0.32%   |
| AMD Phenom II X6        | 15        | 0.32%   |
| Intel Pentium Silver    | 14        | 0.3%    |
| Intel Pentium 4         | 14        | 0.3%    |
| AMD Ryzen Threadripper  | 14        | 0.3%    |
| AMD E2                  | 13        | 0.28%   |
| AMD Athlon              | 13        | 0.28%   |
| AMD E1                  | 12        | 0.26%   |
| ARM BCM                 | 9         | 0.19%   |
| AMD Turion 64 X2 Mobile | 9         | 0.19%   |
| AMD Ryzen 5 PRO         | 9         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1736      | 37.38%  |
| 2       | 1728      | 37.21%  |
| 6       | 467       | 10.06%  |
| 8       | 361       | 7.77%   |
| 1       | 101       | 2.17%   |
| 12      | 91        | 1.96%   |
| 16      | 47        | 1.01%   |
| 3       | 45        | 0.97%   |
| 10      | 22        | 0.47%   |
| 14      | 18        | 0.39%   |
| 24      | 9         | 0.19%   |
| Unknown | 9         | 0.19%   |
| 20      | 5         | 0.11%   |
| 56      | 2         | 0.04%   |
| 64      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 7       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4547      | 98.19%  |
| 2       | 76        | 1.64%   |
| Unknown | 7         | 0.15%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2976      | 64.17%  |
| 1       | 1653      | 35.64%  |
| Unknown | 9         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4488      | 96.58%  |
| Unknown        | 113       | 2.43%   |
| 32-bit         | 38        | 0.82%   |
| 64-bit         | 8         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1169      | 24.3%   |
| 0x306a9    | 276       | 5.74%   |
| 0x206a7    | 264       | 5.49%   |
| 0x306c3    | 205       | 4.26%   |
| 0x1067a    | 173       | 3.6%    |
| 0x906ea    | 126       | 2.62%   |
| 0x506e3    | 87        | 1.81%   |
| 0x806ea    | 86        | 1.79%   |
| 0x20655    | 85        | 1.77%   |
| 0x08701021 | 81        | 1.68%   |
| 0x40651    | 80        | 1.66%   |
| 0x906e9    | 79        | 1.64%   |
| 0x806e9    | 69        | 1.43%   |
| 0x6fd      | 69        | 1.43%   |
| 0x406e3    | 67        | 1.39%   |
| 0x06001119 | 58        | 1.21%   |
| 0x806ec    | 57        | 1.18%   |
| 0x306d4    | 53        | 1.1%    |
| 0x10676    | 51        | 1.06%   |
| 0x20652    | 49        | 1.02%   |
| 0x6fb      | 48        | 1%      |
| 0x106e5    | 47        | 0.98%   |
| 0x08701013 | 47        | 0.98%   |
| 0x0800820d | 46        | 0.96%   |
| 0x06000852 | 45        | 0.94%   |
| 0xa0652    | 44        | 0.91%   |
| 0x010000c8 | 44        | 0.91%   |
| 0x806c1    | 43        | 0.89%   |
| 0x706e5    | 36        | 0.75%   |
| 0x30678    | 35        | 0.73%   |
| 0x206d7    | 35        | 0.73%   |
| 0x106a5    | 31        | 0.64%   |
| 0x406c4    | 29        | 0.6%    |
| 0x0a50000c | 29        | 0.6%    |
| 0x08108109 | 29        | 0.6%    |
| 0x906ed    | 27        | 0.56%   |
| 0x206c2    | 27        | 0.56%   |
| 0x806eb    | 25        | 0.52%   |
| 0x06006705 | 25        | 0.52%   |
| 0x03000027 | 25        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 610       | 13.17%  |
| Haswell          | 401       | 8.66%   |
| IvyBridge        | 367       | 7.92%   |
| SandyBridge      | 356       | 7.69%   |
| Penryn           | 273       | 5.9%    |
| Zen 2            | 235       | 5.07%   |
| Skylake          | 209       | 4.51%   |
| Westmere         | 190       | 4.1%    |
| Core             | 186       | 4.02%   |
| Zen+             | 141       | 3.04%   |
| Unknown          | 141       | 3.04%   |
| Piledriver       | 139       | 3%      |
| K10              | 115       | 2.48%   |
| Zen 3            | 111       | 2.4%    |
| Silvermont       | 109       | 2.35%   |
| Zen              | 108       | 2.33%   |
| CometLake        | 108       | 2.33%   |
| Nehalem          | 99        | 2.14%   |
| Excavator        | 84        | 1.81%   |
| Broadwell        | 83        | 1.79%   |
| TigerLake        | 67        | 1.45%   |
| K8 Hammer        | 63        | 1.36%   |
| IceLake          | 60        | 1.3%    |
| Puma             | 38        | 0.82%   |
| Goldmont plus    | 38        | 0.82%   |
| Bobcat           | 36        | 0.78%   |
| Alderlake Hybrid | 36        | 0.78%   |
| NetBurst         | 34        | 0.73%   |
| K10 Llano        | 32        | 0.69%   |
| Bulldozer        | 32        | 0.69%   |
| Bonnell          | 27        | 0.58%   |
| Jaguar           | 24        | 0.52%   |
| P6               | 23        | 0.5%    |
| Goldmont         | 22        | 0.48%   |
| Steamroller      | 19        | 0.41%   |
| K8 & K10 hybrid  | 10        | 0.22%   |
| Tremont          | 5         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2336      | 44.49%  |
| Nvidia                                       | 1530      | 29.14%  |
| AMD                                          | 1321      | 25.16%  |
| Matrox Electronics Systems                   | 36        | 0.69%   |
| ASPEED Technology                            | 19        | 0.36%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.04%   |
| VIA Technologies                             | 2         | 0.04%   |
| Loongson Technology                          | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 227       | 4.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 173       | 3.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 134       | 2.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 117       | 2.14%   |
| Intel UHD Graphics 620                                                                   | 115       | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 94        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 93        | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 93        | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 88        | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 74        | 1.35%   |
| Intel HD Graphics 530                                                                    | 70        | 1.28%   |
| Intel HD Graphics 620                                                                    | 67        | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 67        | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 66        | 1.21%   |
| AMD Renoir                                                                               | 64        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 61        | 1.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 1.1%    |
| Intel HD Graphics 5500                                                                   | 59        | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 58        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 55        | 1.01%   |
| Intel HD Graphics 630                                                                    | 54        | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 52        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 51        | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 50        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 50        | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 48        | 0.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 47        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 46        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 45        | 0.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 44        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 39        | 0.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 35        | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 33        | 0.6%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 33        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 31        | 0.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 31        | 0.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 31        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 1770      | 37.88%  |
| 1 x AMD                   | 1117      | 23.9%   |
| 1 x Nvidia                | 997       | 21.34%  |
| Intel + Nvidia            | 419       | 8.97%   |
| Intel + AMD               | 73        | 1.56%   |
| 2 x AMD                   | 65        | 1.39%   |
| AMD + Nvidia              | 63        | 1.35%   |
| Other                     | 59        | 1.26%   |
| 2 x Nvidia                | 38        | 0.81%   |
| 1 x Matrox                | 28        | 0.6%    |
| 1 x ASPEED                | 16        | 0.34%   |
| Nvidia + Matrox           | 7         | 0.15%   |
| Intel + 2 x Nvidia        | 4         | 0.09%   |
| 1 x SiS                   | 3         | 0.06%   |
| 2 x Intel                 | 2         | 0.04%   |
| 1 x VIA                   | 2         | 0.04%   |
| Nvidia + ASPEED           | 2         | 0.04%   |
| 5 x Nvidia                | 1         | 0.02%   |
| 2 x Loongson Technology   | 1         | 0.02%   |
| 1 x XGI                   | 1         | 0.02%   |
| 1 x Intel + 3 x AMD       | 1         | 0.02%   |
| AMD + 2 x Nvidia          | 1         | 0.02%   |
| AMD + XGI                 | 1         | 0.02%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.02%   |
| AMD + Matrox              | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3588      | 76.21%  |
| Proprietary | 892       | 18.95%  |
| Unknown     | 228       | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2530      | 52.58%  |
| 0.01-0.5   | 598       | 12.43%  |
| 1.01-2.0   | 516       | 10.72%  |
| 0.51-1.0   | 364       | 7.56%   |
| 3.01-4.0   | 285       | 5.92%   |
| 7.01-8.0   | 278       | 5.78%   |
| 5.01-6.0   | 128       | 2.66%   |
| 8.01-16.0  | 66        | 1.37%   |
| 2.01-3.0   | 41        | 0.85%   |
| 4.01-5.0   | 3         | 0.06%   |
| 16.01-24.0 | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 681       | 13.12%  |
| AU Optronics            | 517       | 9.96%   |
| LG Display              | 378       | 7.28%   |
| Dell                    | 358       | 6.9%    |
| Goldstar                | 315       | 6.07%   |
| Chimei Innolux          | 281       | 5.41%   |
| Acer                    | 279       | 5.37%   |
| BOE                     | 241       | 4.64%   |
| Hewlett-Packard         | 216       | 4.16%   |
| Ancor Communications    | 192       | 3.7%    |
| Sharp                   | 155       | 2.99%   |
| BenQ                    | 155       | 2.99%   |
| Apple                   | 146       | 2.81%   |
| Lenovo                  | 121       | 2.33%   |
| ViewSonic               | 103       | 1.98%   |
| ASUSTek Computer        | 92        | 1.77%   |
| Chi Mei Optoelectronics | 70        | 1.35%   |
| LG Electronics          | 62        | 1.19%   |
| Unknown                 | 54        | 1.04%   |
| Philips                 | 54        | 1.04%   |
| Toshiba                 | 53        | 1.02%   |
| Sony                    | 48        | 0.92%   |
| AOC                     | 48        | 0.92%   |
| PANDA                   | 39        | 0.75%   |
| LG Philips              | 29        | 0.56%   |
| Panasonic               | 23        | 0.44%   |
| NEC Computers           | 23        | 0.44%   |
| InfoVision              | 22        | 0.42%   |
| MSI                     | 19        | 0.37%   |
| HannStar                | 19        | 0.37%   |
| Insignia                | 15        | 0.29%   |
| Gigabyte Technology     | 14        | 0.27%   |
| ANX                     | 14        | 0.27%   |
| Gateway                 | 13        | 0.25%   |
| Vizio                   | 12        | 0.23%   |
| AUS                     | 12        | 0.23%   |
| HKC                     | 11        | 0.21%   |
| Unknown                 | 11        | 0.21%   |
| Sceptre Tech            | 10        | 0.19%   |
| Quanta Display          | 9         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 30        | 0.55%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 30        | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 27        | 0.49%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 20        | 0.37%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 19        | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 18        | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 18        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 0.31%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 17        | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 16        | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 16        | 0.29%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 15        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 0.27%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 14        | 0.26%   |
| ANX ANX7530 U ANX7539 800x1280                                        | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch        | 13        | 0.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 12        | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 12        | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 12        | 0.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 12        | 0.22%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 12        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 12        | 0.22%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 11        | 0.2%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 11        | 0.2%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 11        | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 11        | 0.2%    |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 11        | 0.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.2%    |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 11        | 0.2%    |
| Unknown                                                               | 11        | 0.2%    |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                      | 10        | 0.18%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 10        | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 10        | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 10        | 0.18%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 10        | 0.18%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 9         | 0.16%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 9         | 0.16%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 9         | 0.16%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 9         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1992      | 39.86%  |
| 1366x768 (WXGA)    | 782       | 15.65%  |
| 3840x2160 (4K)     | 331       | 6.62%   |
| 1680x1050 (WSXGA+) | 244       | 4.88%   |
| 2560x1440 (QHD)    | 220       | 4.4%    |
| 1600x900 (HD+)     | 218       | 4.36%   |
| 1280x1024 (SXGA)   | 182       | 3.64%   |
| 1280x800 (WXGA)    | 142       | 2.84%   |
| 1920x1200 (WUXGA)  | 136       | 2.72%   |
| 1440x900 (WXGA+)   | 124       | 2.48%   |
| Unknown            | 111       | 2.22%   |
| 1360x768           | 54        | 1.08%   |
| 3440x1440          | 52        | 1.04%   |
| 3840x1080          | 48        | 0.96%   |
| 1920x540           | 31        | 0.62%   |
| 2560x1080          | 28        | 0.56%   |
| 2880x1800          | 22        | 0.44%   |
| 2560x1600          | 19        | 0.38%   |
| 800x1280           | 18        | 0.36%   |
| 1600x1200          | 17        | 0.34%   |
| 1024x768 (XGA)     | 15        | 0.3%    |
| 3200x1800 (QHD+)   | 14        | 0.28%   |
| 1280x720 (HD)      | 13        | 0.26%   |
| 1024x600           | 13        | 0.26%   |
| 2736x1824          | 12        | 0.24%   |
| 3840x2400          | 11        | 0.22%   |
| 5760x1080          | 7         | 0.14%   |
| 3840x1200          | 7         | 0.14%   |
| 3600x1080          | 7         | 0.14%   |
| 3200x2000          | 6         | 0.12%   |
| 2160x1440          | 6         | 0.12%   |
| 2048x1152          | 6         | 0.12%   |
| 7680x2160          | 5         | 0.1%    |
| 3200x1080          | 5         | 0.1%    |
| 3456x2160          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 2256x1504          | 4         | 0.08%   |
| 1920x1280          | 4         | 0.08%   |
| 5760x2160          | 3         | 0.06%   |
| 5120x1440          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1142      | 22.2%   |
| 27      | 417       | 8.11%   |
| Unknown | 392       | 7.62%   |
| 13      | 381       | 7.41%   |
| 24      | 373       | 7.25%   |
| 23      | 354       | 6.88%   |
| 21      | 304       | 5.91%   |
| 14      | 294       | 5.72%   |
| 17      | 271       | 5.27%   |
| 19      | 165       | 3.21%   |
| 22      | 137       | 2.66%   |
| 20      | 134       | 2.6%    |
| 31      | 129       | 2.51%   |
| 18      | 69        | 1.34%   |
| 34      | 67        | 1.3%    |
| 12      | 67        | 1.3%    |
| 72      | 48        | 0.93%   |
| 84      | 47        | 0.91%   |
| 11      | 44        | 0.86%   |
| 32      | 34        | 0.66%   |
| 25      | 22        | 0.43%   |
| 40      | 21        | 0.41%   |
| 74      | 19        | 0.37%   |
| 54      | 18        | 0.35%   |
| 37      | 17        | 0.33%   |
| 10      | 17        | 0.33%   |
| 26      | 16        | 0.31%   |
| 16      | 14        | 0.27%   |
| 43      | 12        | 0.23%   |
| 48      | 11        | 0.21%   |
| 28      | 10        | 0.19%   |
| 49      | 9         | 0.17%   |
| 46      | 8         | 0.16%   |
| 47      | 7         | 0.14%   |
| 42      | 6         | 0.12%   |
| 39      | 6         | 0.12%   |
| 69      | 5         | 0.1%    |
| 52      | 5         | 0.1%    |
| 36      | 5         | 0.1%    |
| 35      | 5         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1650      | 32.84%  |
| 501-600        | 1034      | 20.58%  |
| 401-500        | 699       | 13.91%  |
| Unknown        | 392       | 7.8%    |
| 351-400        | 345       | 6.87%   |
| 201-300        | 328       | 6.53%   |
| 601-700        | 192       | 3.82%   |
| 1501-2000      | 124       | 2.47%   |
| 701-800        | 106       | 2.11%   |
| 1001-1500      | 75        | 1.49%   |
| 801-900        | 53        | 1.05%   |
| 901-1000       | 21        | 0.42%   |
| 1-100          | 3         | 0.06%   |
| More than 2000 | 1         | 0.02%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3185      | 69.09%  |
| 16/10   | 699       | 15.16%  |
| Unknown | 312       | 6.77%   |
| 5/4     | 169       | 3.67%   |
| 21/9    | 73        | 1.58%   |
| 3/2     | 61        | 1.32%   |
| 4/3     | 46        | 1%      |
| 32/9    | 21        | 0.46%   |
| 0.62    | 16        | 0.35%   |
| 6/5     | 14        | 0.3%    |
| 1.96    | 4         | 0.09%   |
| 0.67    | 3         | 0.07%   |
| 3.40    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1134      | 22.43%  |
| 201-250        | 940       | 18.6%   |
| 81-90          | 517       | 10.23%  |
| 301-350        | 428       | 8.47%   |
| Unknown        | 392       | 7.75%   |
| 151-200        | 375       | 7.42%   |
| 351-500        | 242       | 4.79%   |
| More than 1000 | 169       | 3.34%   |
| 121-130        | 161       | 3.18%   |
| 71-80          | 158       | 3.13%   |
| 141-150        | 134       | 2.65%   |
| 251-300        | 123       | 2.43%   |
| 501-1000       | 103       | 2.04%   |
| 61-70          | 54        | 1.07%   |
| 51-60          | 46        | 0.91%   |
| 131-140        | 29        | 0.57%   |
| 111-120        | 18        | 0.36%   |
| 41-50          | 17        | 0.34%   |
| 91-100         | 11        | 0.22%   |
| 1-40           | 4         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1786      | 36.5%   |
| 101-120       | 1212      | 24.77%  |
| 121-160       | 987       | 20.17%  |
| Unknown       | 392       | 8.01%   |
| 161-240       | 219       | 4.48%   |
| 1-50          | 184       | 3.76%   |
| More than 240 | 113       | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3599      | 75.67%  |
| 2     | 785       | 16.51%  |
| 0     | 229       | 4.81%   |
| 3     | 130       | 2.73%   |
| 4     | 10        | 0.21%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2423      | 34.72%  |
| Realtek Semiconductor           | 2163      | 31%     |
| Qualcomm Atheros                | 797       | 11.42%  |
| Broadcom                        | 489       | 7.01%   |
| Broadcom Limited                | 123       | 1.76%   |
| Marvell Technology Group        | 117       | 1.68%   |
| Ralink                          | 95        | 1.36%   |
| Nvidia                          | 89        | 1.28%   |
| Ralink Technology               | 69        | 0.99%   |
| TP-Link                         | 65        | 0.93%   |
| D-Link                          | 56        | 0.8%    |
| ASIX Electronics                | 56        | 0.8%    |
| MediaTek                        | 43        | 0.62%   |
| Linksys                         | 41        | 0.59%   |
| D-Link System                   | 31        | 0.44%   |
| ASUSTek Computer                | 29        | 0.42%   |
| Samsung Electronics             | 28        | 0.4%    |
| Qualcomm Atheros Communications | 24        | 0.34%   |
| Microsoft                       | 19        | 0.27%   |
| NetGear                         | 18        | 0.26%   |
| Aquantia                        | 18        | 0.26%   |
| Lenovo                          | 16        | 0.23%   |
| DisplayLink                     | 16        | 0.23%   |
| Belkin Components               | 10        | 0.14%   |
| Google                          | 9         | 0.13%   |
| Sierra Wireless                 | 8         | 0.11%   |
| Motorola PCS                    | 5         | 0.07%   |
| Microchip Technology            | 5         | 0.07%   |
| Edimax Technology               | 5         | 0.07%   |
| Arduino SA                      | 5         | 0.07%   |
| Apple                           | 5         | 0.07%   |
| AMD                             | 5         | 0.07%   |
| VIA Technologies                | 4         | 0.06%   |
| Qualcomm                        | 4         | 0.06%   |
| Micro Star International        | 4         | 0.06%   |
| Hewlett-Packard                 | 4         | 0.06%   |
| Dell                            | 4         | 0.06%   |
| ZyDAS                           | 3         | 0.04%   |
| Xiaomi                          | 3         | 0.04%   |
| Research In Motion              | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1456      | 17.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 275       | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 258       | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 228       | 2.76%   |
| Intel I211 Gigabit Network Connection                             | 151       | 1.83%   |
| Intel Wireless 8265 / 8275                                        | 136       | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 111       | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 105       | 1.27%   |
| Intel Wireless 7260                                               | 103       | 1.25%   |
| Intel Wireless 7265                                               | 96        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 89        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 87        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 85        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 85        | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 83        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 82        | 0.99%   |
| Intel Wireless 8260                                               | 79        | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 78        | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 77        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 73        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 70        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 69        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 65        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 60        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 59        | 0.72%   |
| Intel Wireless-AC 9260                                            | 54        | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 51        | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 48        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 47        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 46        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 46        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 45        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 45        | 0.55%   |
| Intel Wireless 3165                                               | 44        | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 44        | 0.53%   |
| Intel Centrino Ultimate-N 6300                                    | 43        | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 41        | 0.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 41        | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 40        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 39        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1647      | 44.54%  |
| Qualcomm Atheros                      | 634       | 17.14%  |
| Realtek Semiconductor                 | 491       | 13.28%  |
| Broadcom                              | 324       | 8.76%   |
| Ralink                                | 95        | 2.57%   |
| Broadcom Limited                      | 74        | 2%      |
| Ralink Technology                     | 69        | 1.87%   |
| TP-Link                               | 59        | 1.6%    |
| D-Link                                | 55        | 1.49%   |
| MediaTek                              | 41        | 1.11%   |
| Linksys                               | 39        | 1.05%   |
| ASUSTek Computer                      | 29        | 0.78%   |
| Qualcomm Atheros Communications       | 24        | 0.65%   |
| Marvell Technology Group              | 19        | 0.51%   |
| D-Link System                         | 19        | 0.51%   |
| NetGear                               | 18        | 0.49%   |
| Microsoft                             | 14        | 0.38%   |
| Belkin Components                     | 10        | 0.27%   |
| Sierra Wireless                       | 8         | 0.22%   |
| Edimax Technology                     | 5         | 0.14%   |
| Qualcomm                              | 4         | 0.11%   |
| Micro Star International              | 4         | 0.11%   |
| ZyDAS                                 | 3         | 0.08%   |
| Gemtek                                | 3         | 0.08%   |
| Dell                                  | 2         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.05%   |
| Wilocity                              | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| Belkin                                | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 228       | 6.11%   |
| Intel Wireless 8265 / 8275                                     | 136       | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 105       | 2.81%   |
| Intel Wireless 7260                                            | 103       | 2.76%   |
| Intel Wireless 7265                                            | 96        | 2.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 87        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 85        | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 85        | 2.28%   |
| Intel Wireless 8260                                            | 79        | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 78        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 77        | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 73        | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 70        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 69        | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 65        | 1.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 59        | 1.58%   |
| Intel Wireless-AC 9260                                         | 54        | 1.45%   |
| Intel Wi-Fi 6 AX201                                            | 51        | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 46        | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 45        | 1.21%   |
| Intel Wireless 3165                                            | 44        | 1.18%   |
| Intel Centrino Ultimate-N 6300                                 | 43        | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 41        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 40        | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 38        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 37        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 36        | 0.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 33        | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 33        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 32        | 0.86%   |
| Realtek 802.11ac NIC                                           | 31        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 30        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 30        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 29        | 0.78%   |
| Intel Centrino Wireless-N 2230                                 | 29        | 0.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 29        | 0.78%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 29        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 28        | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 28        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1952      | 44.91%  |
| Intel                                  | 1432      | 32.95%  |
| Broadcom                               | 253       | 5.82%   |
| Qualcomm Atheros                       | 247       | 5.68%   |
| Marvell Technology Group               | 98        | 2.25%   |
| Nvidia                                 | 88        | 2.02%   |
| ASIX Electronics                       | 56        | 1.29%   |
| Broadcom Limited                       | 54        | 1.24%   |
| Samsung Electronics                    | 28        | 0.64%   |
| Aquantia                               | 18        | 0.41%   |
| DisplayLink                            | 16        | 0.37%   |
| Lenovo                                 | 15        | 0.35%   |
| D-Link System                          | 12        | 0.28%   |
| TP-Link                                | 8         | 0.18%   |
| Google                                 | 8         | 0.18%   |
| Apple                                  | 5         | 0.12%   |
| VIA Technologies                       | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Xiaomi                                 | 3         | 0.07%   |
| Research In Motion                     | 3         | 0.07%   |
| Microsoft                              | 3         | 0.07%   |
| Microchip Technology                   | 3         | 0.07%   |
| JMicron Technology                     | 3         | 0.07%   |
| 3Com                                   | 3         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.05%   |
| Mellanox Technologies                  | 2         | 0.05%   |
| MediaTek                               | 2         | 0.05%   |
| Linksys                                | 2         | 0.05%   |
| LG Electronics                         | 2         | 0.05%   |
| ICS Advent                             | 2         | 0.05%   |
| IBM                                    | 2         | 0.05%   |
| Huawei Technologies                    | 2         | 0.05%   |
| D-Link                                 | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| HTC (High Tech Computer)               | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1456      | 32.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 275       | 6.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 258       | 5.79%   |
| Intel I211 Gigabit Network Connection                             | 151       | 3.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 111       | 2.49%   |
| Intel Ethernet Connection (2) I219-V                              | 89        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 82        | 1.84%   |
| Intel Ethernet Connection I217-LM                                 | 82        | 1.84%   |
| Intel 82579V Gigabit Network Connection                           | 60        | 1.35%   |
| Intel Ethernet Controller I225-V                                  | 48        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 47        | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 46        | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 45        | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                     | 44        | 0.99%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 39        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 38        | 0.85%   |
| Intel 82574L Gigabit Network Connection                           | 38        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.7%    |
| Intel Ethernet Connection (2) I218-V                              | 31        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 30        | 0.67%   |
| Nvidia MCP61 Ethernet                                             | 29        | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 27        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 20        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 19        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4067      | 53.8%   |
| WiFi     | 3433      | 45.42%  |
| Modem    | 44        | 0.58%   |
| Unknown  | 15        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2562      | 52.5%   |
| Ethernet | 2317      | 47.48%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2586      | 55.49%  |
| 1     | 1797      | 38.56%  |
| 3     | 139       | 2.98%   |
| 0     | 95        | 2.04%   |
| 4     | 26        | 0.56%   |
| 5     | 10        | 0.21%   |
| 6     | 4         | 0.09%   |
| 22    | 1         | 0.02%   |
| 21    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4088      | 87.11%  |
| Yes  | 605       | 12.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1270      | 47.55%  |
| Broadcom                        | 194       | 7.26%   |
| Qualcomm Atheros Communications | 178       | 6.66%   |
| Realtek Semiconductor           | 175       | 6.55%   |
| Apple                           | 154       | 5.77%   |
| Cambridge Silicon Radio         | 149       | 5.58%   |
| Lite-On Technology              | 118       | 4.42%   |
| IMC Networks                    | 117       | 4.38%   |
| ASUSTek Computer                | 75        | 2.81%   |
| Foxconn / Hon Hai               | 67        | 2.51%   |
| Dell                            | 40        | 1.5%    |
| Hewlett-Packard                 | 27        | 1.01%   |
| Marvell Semiconductor           | 18        | 0.67%   |
| Toshiba                         | 14        | 0.52%   |
| Ralink                          | 14        | 0.52%   |
| Dynex                           | 13        | 0.49%   |
| Realtek                         | 6         | 0.22%   |
| MediaTek                        | 6         | 0.22%   |
| Alps Electric                   | 6         | 0.22%   |
| Logitech                        | 5         | 0.19%   |
| Micro Star International        | 4         | 0.15%   |
| Primax Electronics              | 3         | 0.11%   |
| Integrated System Solution      | 3         | 0.11%   |
| TP-Link                         | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Zeevo                           | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Foxconn International           | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 459       | 17.16%  |
| Intel AX200 Bluetooth                                    | 221       | 8.26%   |
| Intel AX201 Bluetooth                                    | 180       | 6.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 149       | 5.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 139       | 5.2%    |
| Realtek Bluetooth Radio                                  | 126       | 4.71%   |
| Intel Wireless-AC 3168 Bluetooth                         | 87        | 3.25%   |
| Qualcomm Atheros  Bluetooth Device                       | 83        | 3.1%    |
| IMC Networks Bluetooth Radio                             | 57        | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 55        | 2.06%   |
| Apple Bluetooth Host Controller                          | 54        | 2.02%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 53        | 1.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 51        | 1.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 44        | 1.64%   |
| Apple Bluetooth USB Host Controller                      | 43        | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                           | 37        | 1.38%   |
| Intel AX210 Bluetooth                                    | 36        | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                       | 34        | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                         | 33        | 1.23%   |
| Apple Bluetooth HCI                                      | 33        | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 29        | 1.08%   |
| Broadcom BCM2045B (BDC-2.1)                              | 25        | 0.93%   |
| Intel Bluetooth Device                                   | 24        | 0.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 24        | 0.9%    |
| Lite-On Bluetooth Device                                 | 23        | 0.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 23        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 22        | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 20        | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 20        | 0.75%   |
| IMC Networks Bluetooth Device                            | 18        | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 17        | 0.64%   |
| Broadcom HP Portable SoftSailing                         | 16        | 0.6%    |
| Ralink RT3290 Bluetooth                                  | 14        | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite             | 14        | 0.52%   |
| IMC Networks Wireless_Device                             | 14        | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                         | 14        | 0.52%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 13        | 0.49%   |
| ASUS Bluetooth Device                                    | 13        | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 12        | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 12        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3169      | 47.26%  |
| AMD                                  | 1504      | 22.43%  |
| Nvidia                               | 1220      | 18.19%  |
| C-Media Electronics                  | 142       | 2.12%   |
| Logitech                             | 73        | 1.09%   |
| Creative Labs                        | 55        | 0.82%   |
| Corsair                              | 28        | 0.42%   |
| Realtek Semiconductor                | 27        | 0.4%    |
| Texas Instruments                    | 25        | 0.37%   |
| JMTek                                | 24        | 0.36%   |
| Blue Microphones                     | 24        | 0.36%   |
| SteelSeries ApS                      | 22        | 0.33%   |
| Focusrite-Novation                   | 19        | 0.28%   |
| Creative Technology                  | 19        | 0.28%   |
| Razer USA                            | 17        | 0.25%   |
| Lenovo                               | 17        | 0.25%   |
| GN Netcom                            | 17        | 0.25%   |
| Kingston Technology                  | 15        | 0.22%   |
| ASUSTek Computer                     | 15        | 0.22%   |
| Plantronics                          | 14        | 0.21%   |
| GYROCOM C&C                          | 13        | 0.19%   |
| Sony                                 | 12        | 0.18%   |
| Samson Technologies                  | 12        | 0.18%   |
| Generalplus Technology               | 10        | 0.15%   |
| M-Audio                              | 9         | 0.13%   |
| VIA Technologies                     | 8         | 0.12%   |
| FiiO Electronics Technology          | 7         | 0.1%    |
| Yamaha                               | 6         | 0.09%   |
| XMOS                                 | 6         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.09%   |
| SAVITECH                             | 6         | 0.09%   |
| Dell                                 | 6         | 0.09%   |
| Bose                                 | 6         | 0.09%   |
| Audio-Technica                       | 6         | 0.09%   |
| Tenx Technology                      | 5         | 0.07%   |
| Sennheiser Communications            | 5         | 0.07%   |
| NAD Electronics                      | 5         | 0.07%   |
| KTMicro                              | 5         | 0.07%   |
| Cambridge Silicon Radio              | 5         | 0.07%   |
| Micro Star International             | 4         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 346       | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 308       | 3.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 281       | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 251       | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 235       | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 224       | 2.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 222       | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 206       | 2.62%   |
| AMD FCH Azalia Controller                                                  | 195       | 2.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 174       | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 170       | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 168       | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 134       | 1.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 130       | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 118       | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 116       | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 106       | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 101       | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 97        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 96        | 1.22%   |
| Intel 8 Series HD Audio Controller                                         | 96        | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 94        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 93        | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                   | 93        | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 91        | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 91        | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 81        | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 81        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 79        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 75        | 0.95%   |
| Intel Broadwell-U Audio Controller                                         | 73        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 70        | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 68        | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                         | 67        | 0.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 67        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 66        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 65        | 0.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 64        | 0.81%   |
| AMD Navi 10 HDMI Audio                                                     | 57        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 54        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 510       | 19.49%  |
| SK hynix                                         | 486       | 18.57%  |
| Kingston                                         | 316       | 12.07%  |
| Unknown                                          | 265       | 10.13%  |
| Micron Technology                                | 257       | 9.82%   |
| G.Skill                                          | 180       | 6.88%   |
| Corsair                                          | 160       | 6.11%   |
| Crucial                                          | 117       | 4.47%   |
| Nanya Technology                                 | 51        | 1.95%   |
| Elpida                                           | 51        | 1.95%   |
| Ramaxel Technology                               | 40        | 1.53%   |
| A-DATA Technology                                | 40        | 1.53%   |
| Patriot                                          | 26        | 0.99%   |
| Unknown                                          | 14        | 0.53%   |
| Team                                             | 9         | 0.34%   |
| Unknown (ABCD)                                   | 8         | 0.31%   |
| Transcend                                        | 7         | 0.27%   |
| ASint Technology                                 | 7         | 0.27%   |
| Unifosa                                          | 6         | 0.23%   |
| Toshiba                                          | 6         | 0.23%   |
| Timetec                                          | 5         | 0.19%   |
| Avant                                            | 4         | 0.15%   |
| Qimonda                                          | 3         | 0.11%   |
| PNY                                              | 3         | 0.11%   |
| OCZ                                              | 3         | 0.11%   |
| CSX                                              | 3         | 0.11%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.08%   |
| SHARETRONIC                                      | 2         | 0.08%   |
| Sesame                                           | 2         | 0.08%   |
| Neo Forza                                        | 2         | 0.08%   |
| Mushkin                                          | 2         | 0.08%   |
| Hewlett-Packard                                  | 2         | 0.08%   |
| Goldkey                                          | 2         | 0.08%   |
| Axiom                                            | 2         | 0.08%   |
| Apacer                                           | 2         | 0.08%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.04%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.04%   |
| Unknown (0x0C26)                                 | 1         | 0.04%   |
| Unknown (0x0080)                                 | 1         | 0.04%   |
| Unknown (08AE)                                   | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 25        | 0.88%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 19        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 18        | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 18        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 16        | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 14        | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 14        | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.49%   |
| Unknown                                                          | 14        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.42%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.39%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 10        | 0.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.35%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 10        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.35%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 10        | 0.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 9         | 0.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.32%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 0.32%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 9         | 0.32%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 8         | 0.28%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 8         | 0.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 8         | 0.28%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 8         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 950       | 42.74%  |
| DDR3    | 828       | 37.25%  |
| DDR2    | 133       | 5.98%   |
| LPDDR4  | 67        | 3.01%   |
| LPDDR3  | 67        | 3.01%   |
| Unknown | 66        | 2.97%   |
| SDRAM   | 61        | 2.74%   |
| DDR     | 28        | 1.26%   |
| DDR5    | 18        | 0.81%   |
| LPDDR5  | 3         | 0.13%   |
| DRAM    | 2         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1082      | 49.23%  |
| DIMM         | 952       | 43.31%  |
| Row Of Chips | 136       | 6.19%   |
| Chip         | 15        | 0.68%   |
| Unknown      | 10        | 0.45%   |
| FB-DIMM      | 3         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 891       | 36.12%  |
| 4096   | 699       | 28.33%  |
| 2048   | 351       | 14.23%  |
| 16384  | 344       | 13.94%  |
| 1024   | 108       | 4.38%   |
| 32768  | 60        | 2.43%   |
| 512    | 11        | 0.45%   |
| 129408 | 1         | 0.04%   |
| 65536  | 1         | 0.04%   |
| 256    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 501       | 20.6%   |
| 3200    | 296       | 12.17%  |
| 2667    | 278       | 11.43%  |
| 1333    | 228       | 9.38%   |
| 2400    | 175       | 7.2%    |
| 2133    | 129       | 5.3%    |
| 3600    | 87        | 3.58%   |
| 667     | 71        | 2.92%   |
| 800     | 67        | 2.75%   |
| 1334    | 65        | 2.67%   |
| 1867    | 58        | 2.38%   |
| 1067    | 43        | 1.77%   |
| 1066    | 37        | 1.52%   |
| Unknown | 36        | 1.48%   |
| 4267    | 32        | 1.32%   |
| 2666    | 22        | 0.9%    |
| 3866    | 19        | 0.78%   |
| 3733    | 19        | 0.78%   |
| 3266    | 19        | 0.78%   |
| 4800    | 17        | 0.7%    |
| 3400    | 17        | 0.7%    |
| 1866    | 17        | 0.7%    |
| 3000    | 15        | 0.62%   |
| 2933    | 14        | 0.58%   |
| 4199    | 13        | 0.53%   |
| 3466    | 13        | 0.53%   |
| 3800    | 12        | 0.49%   |
| 533     | 12        | 0.49%   |
| 8400    | 9         | 0.37%   |
| 2048    | 7         | 0.29%   |
| 1800    | 7         | 0.29%   |
| 975     | 7         | 0.29%   |
| 400     | 7         | 0.29%   |
| 6400    | 6         | 0.25%   |
| 2800    | 6         | 0.25%   |
| 2000    | 6         | 0.25%   |
| 1639    | 6         | 0.25%   |
| 3100    | 5         | 0.21%   |
| 2465    | 5         | 0.21%   |
| 49926   | 4         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Brother Industries       | 65        | 34.57%  |
| Hewlett-Packard          | 55        | 29.26%  |
| Samsung Electronics      | 27        | 14.36%  |
| Canon                    | 25        | 13.3%   |
| Seiko Epson              | 8         | 4.26%   |
| Lexmark International    | 2         | 1.06%   |
| Dymo-CoStar              | 2         | 1.06%   |
| Dell                     | 2         | 1.06%   |
| Zhuhai Poskey Technology | 1         | 0.53%   |
| Prolific Technology      | 1         | 0.53%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Brother Printer                      | 9         | 4.66%   |
| HP LaserJet 1018                     | 5         | 2.59%   |
| Seiko Epson ET-3750 Series           | 4         | 2.07%   |
| HP LaserJet 1020                     | 4         | 2.07%   |
| Brother HL-L2390DW                   | 4         | 2.07%   |
| Brother HL-L2320D series             | 4         | 2.07%   |
| Brother HL-5370DW series             | 4         | 2.07%   |
| Samsung ML-216x Series Laser Printer | 3         | 1.55%   |
| Samsung ML-1670 Series               | 3         | 1.55%   |
| HP LaserJet 4250                     | 3         | 1.55%   |
| HP ENVY 4520 series                  | 3         | 1.55%   |
| HP DeskJet 3630 series               | 3         | 1.55%   |
| HP DeskJet 2620 All-in-One Printer   | 3         | 1.55%   |
| Canon PIXMA MX920 Series             | 3         | 1.55%   |
| Canon PIXMA MG2900 Series            | 3         | 1.55%   |
| Brother MFC-J480DW                   | 3         | 1.55%   |
| Brother MFC-9130CW                   | 3         | 1.55%   |
| Brother HL-L2360D series             | 3         | 1.55%   |
| Brother HL-2270DW Laser Printer      | 3         | 1.55%   |
| Brother DCP-L2540DW                  | 3         | 1.55%   |
| Samsung ML-1660 Series               | 2         | 1.04%   |
| Samsung M267x 287x Series            | 2         | 1.04%   |
| Samsung M2070 Series                 | 2         | 1.04%   |
| Samsung M2020 Series                 | 2         | 1.04%   |
| HP OfficeJet 3830 series             | 2         | 1.04%   |
| HP LaserJet Pro M202dw               | 2         | 1.04%   |
| HP LaserJet M101-M106                | 2         | 1.04%   |
| HP DeskJet 3700 series               | 2         | 1.04%   |
| Dymo-CoStar LabelWriter 450          | 2         | 1.04%   |
| Canon PIXMA MX530 Series             | 2         | 1.04%   |
| Canon MF3010                         | 2         | 1.04%   |
| Brother MFC-J485DW                   | 2         | 1.04%   |
| Brother MFC-9330CDW                  | 2         | 1.04%   |
| Brother HL-L3290CDW series           | 2         | 1.04%   |
| Brother HL-2140 series               | 2         | 1.04%   |
| Zhuhai Poskey Printer                | 1         | 0.52%   |
| Seiko Epson XP-4100 Series           | 1         | 0.52%   |
| Seiko Epson WF-3520 Series           | 1         | 0.52%   |
| Seiko Epson L3160 Series             | 1         | 0.52%   |
| Seiko Epson ET-4760 Series           | 1         | 0.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 18        | 60%     |
| Hewlett-Packard | 7         | 23.33%  |
| Seiko Epson     | 5         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 700F                                | 4         | 13.33%  |
| Canon CanoScan LiDE 220                                 | 4         | 13.33%  |
| Canon CanoScan LiDE 210                                 | 3         | 10%     |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 6.67%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 3.33%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.33%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1         | 3.33%   |
| HP ScanJet G4050                                        | 1         | 3.33%   |
| HP ScanJet G4010                                        | 1         | 3.33%   |
| HP ScanJet 82x0C                                        | 1         | 3.33%   |
| HP ScanJet 5590                                         | 1         | 3.33%   |
| HP ScanJet 5200c                                        | 1         | 3.33%   |
| HP ScanJet 3670                                         | 1         | 3.33%   |
| HP ScanJet 2200c                                        | 1         | 3.33%   |
| Canon CanoScan LiDE 70                                  | 1         | 3.33%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 3.33%   |
| Canon CanoScan LiDE 200                                 | 1         | 3.33%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.33%   |
| Canon CanoScan LiDE 110                                 | 1         | 3.33%   |
| Canon CanoScan 4200F                                    | 1         | 3.33%   |
| Canon CanoScan                                          | 1         | 3.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 495       | 19.53%  |
| Microdia                               | 260       | 10.26%  |
| Logitech                               | 234       | 9.23%   |
| IMC Networks                           | 204       | 8.05%   |
| Realtek Semiconductor                  | 179       | 7.06%   |
| Acer                                   | 172       | 6.79%   |
| Apple                                  | 153       | 6.04%   |
| Sunplus Innovation Technology          | 132       | 5.21%   |
| Suyin                                  | 90        | 3.55%   |
| Quanta                                 | 84        | 3.31%   |
| Microsoft                              | 64        | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 59        | 2.33%   |
| Syntek                                 | 37        | 1.46%   |
| Lite-On Technology                     | 36        | 1.42%   |
| Samsung Electronics                    | 35        | 1.38%   |
| Ricoh                                  | 26        | 1.03%   |
| Silicon Motion                         | 24        | 0.95%   |
| Luxvisions Innotech Limited            | 23        | 0.91%   |
| Lenovo                                 | 23        | 0.91%   |
| Importek                               | 18        | 0.71%   |
| Z-Star Microelectronics                | 15        | 0.59%   |
| AVerMedia Technologies                 | 14        | 0.55%   |
| Alcor Micro                            | 14        | 0.55%   |
| MacroSilicon                           | 12        | 0.47%   |
| ALi                                    | 9         | 0.36%   |
| OmniVision Technologies                | 8         | 0.32%   |
| Primax Electronics                     | 7         | 0.28%   |
| LG Electronics                         | 7         | 0.28%   |
| Cubeternet                             | 7         | 0.28%   |
| Sonix Technology                       | 6         | 0.24%   |
| Creative Technology                    | 6         | 0.24%   |
| Razer USA                              | 5         | 0.2%    |
| Huawei Technologies                    | 5         | 0.2%    |
| Hewlett-Packard                        | 5         | 0.2%    |
| HD 2MP WEBCAM                          | 5         | 0.2%    |
| Genesys Logic                          | 5         | 0.2%    |
| Unknown                                | 4         | 0.16%   |
| Generalplus Technology                 | 4         | 0.16%   |
| Valve Software                         | 3         | 0.12%   |
| Linux Foundation                       | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 104       | 4.07%   |
| Microdia Integrated_Webcam_HD            | 100       | 3.91%   |
| IMC Networks USB2.0 HD UVC WebCam        | 73        | 2.85%   |
| Realtek Integrated_Webcam_HD             | 71        | 2.78%   |
| Acer Integrated Camera                   | 57        | 2.23%   |
| Apple Built-in iSight                    | 55        | 2.15%   |
| Logitech HD Pro Webcam C920              | 54        | 2.11%   |
| Logitech Webcam C270                     | 47        | 1.84%   |
| Chicony HD WebCam                        | 47        | 1.84%   |
| IMC Networks Integrated Camera           | 43        | 1.68%   |
| Apple iPhone5/5C/5S/6                    | 42        | 1.64%   |
| Samsung Galaxy A5 (MTP)                  | 35        | 1.37%   |
| Apple FaceTime HD Camera (Built-in)      | 32        | 1.25%   |
| Microdia Integrated Webcam               | 31        | 1.21%   |
| Sunplus Integrated_Webcam_HD             | 28        | 1.09%   |
| Syntek Integrated Camera                 | 27        | 1.06%   |
| Microdia USB 2.0 Camera                  | 25        | 0.98%   |
| Microdia Webcam Vitade AF                | 23        | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 23        | 0.9%    |
| Sunplus HD WebCam                        | 22        | 0.86%   |
| Chicony VGA WebCam                       | 22        | 0.86%   |
| Realtek USB Camera                       | 21        | 0.82%   |
| Apple FaceTime HD Camera                 | 20        | 0.78%   |
| Acer Lenovo EasyCamera                   | 20        | 0.78%   |
| Microsoft LifeCam HD-3000                | 19        | 0.74%   |
| Logitech C922 Pro Stream Webcam          | 19        | 0.74%   |
| Lite-On Integrated Camera                | 18        | 0.7%    |
| Chicony HP Truevision HD                 | 18        | 0.7%    |
| Acer HD Webcam                           | 18        | 0.7%    |
| Chicony USB2.0 HD UVC WebCam             | 17        | 0.66%   |
| Quanta VGA WebCam                        | 16        | 0.63%   |
| Chicony USB 2.0 Camera                   | 16        | 0.63%   |
| Quanta HP TrueVision HD Camera           | 15        | 0.59%   |
| Quanta HD User Facing                    | 15        | 0.59%   |
| Acer SunplusIT Integrated Camera         | 15        | 0.59%   |
| Microdia Laptop_Integrated_Webcam_HD     | 14        | 0.55%   |
| Chicony TOSHIBA Web Camera - HD          | 14        | 0.55%   |
| Chicony USB2.0 VGA UVC WebCam            | 13        | 0.51%   |
| Chicony HP HD Camera                     | 13        | 0.51%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 12        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 172       | 37.23%  |
| Synaptics                          | 108       | 23.38%  |
| Shenzhen Goodix Technology         | 46        | 9.96%   |
| Upek                               | 31        | 6.71%   |
| Elan Microelectronics              | 31        | 6.71%   |
| AuthenTec                          | 30        | 6.49%   |
| LighTuning Technology              | 21        | 4.55%   |
| STMicroelectronics                 | 15        | 3.25%   |
| Samsung Electronics                | 2         | 0.43%   |
| Microsoft                          | 2         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.22%   |
| HOLTEK                             | 1         | 0.22%   |
| Focal-systems.Corp                 | 1         | 0.22%   |
| Dell                               | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 9.31%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 31        | 6.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 6.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 5.84%   |
| Elan ELAN:Fingerprint                                                      | 25        | 5.41%   |
| Unknown                                                                    | 24        | 5.19%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.98%   |
| Shenzhen Goodix FingerPrint                                                | 23        | 4.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 3.9%    |
| Validity Sensors VFS491                                                    | 18        | 3.9%    |
| Validity Sensors Synaptics WBDI                                            | 18        | 3.9%    |
| STMicroelectronics Fingerprint Reader                                      | 15        | 3.25%   |
| AuthenTec AES2810                                                          | 14        | 3.03%   |
| Synaptics  WBDI                                                            | 12        | 2.6%    |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 2.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 2.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.38%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 1.52%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.08%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.65%   |
| AuthenTec AES1600                                                          | 3         | 0.65%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.43%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.43%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.43%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.43%   |
| Microsoft Fingerprint Reader                                               | 2         | 0.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.22%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.22%   |
| Synaptics WBDI Device                                                      | 1         | 0.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 77        | 42.54%  |
| Alcor Micro               | 35        | 19.34%  |
| O2 Micro                  | 23        | 12.71%  |
| Upek                      | 21        | 11.6%   |
| Lenovo                    | 12        | 6.63%   |
| Gemalto (was Gemplus)     | 4         | 2.21%   |
| Yubico.com                | 2         | 1.1%    |
| SCM Microsystems          | 2         | 1.1%    |
| Aladdin Knowledge Systems | 2         | 1.1%    |
| In Focus Systems          | 1         | 0.55%   |
| Giesecke & Devrient       | 1         | 0.55%   |
| Clay Logic                | 1         | 0.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 42        | 23.2%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 18.23%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 11.6%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 10.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 9.39%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 6.63%   |
| Broadcom 5880                                                                | 11        | 6.08%   |
| Broadcom 58200                                                               | 6         | 3.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.21%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 2.21%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.1%    |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.1%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.55%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.55%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.55%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.55%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.55%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.55%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3410      | 71.68%  |
| 1     | 1075      | 22.6%   |
| 2     | 218       | 4.58%   |
| 3     | 35        | 0.74%   |
| 4     | 11        | 0.23%   |
| 5     | 5         | 0.11%   |
| 8     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 454       | 28.15%  |
| Graphics card            | 314       | 19.47%  |
| Net/wireless             | 239       | 14.82%  |
| Chipcard                 | 165       | 10.23%  |
| Communication controller | 96        | 5.95%   |
| Multimedia controller    | 85        | 5.27%   |
| Unassigned class         | 41        | 2.54%   |
| Bluetooth                | 35        | 2.17%   |
| Sound                    | 31        | 1.92%   |
| Storage                  | 30        | 1.86%   |
| Camera                   | 30        | 1.86%   |
| Net/ethernet             | 25        | 1.55%   |
| Network                  | 15        | 0.93%   |
| Modem                    | 11        | 0.68%   |
| Card reader              | 8         | 0.5%    |
| Storage/ide              | 7         | 0.43%   |
| Dvb card                 | 7         | 0.43%   |
| Storage/raid             | 6         | 0.37%   |
| Firewire controller      | 5         | 0.31%   |
| Flash memory             | 4         | 0.25%   |
| Tv card                  | 2         | 0.12%   |
| Video                    | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |

